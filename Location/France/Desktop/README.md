Linux in France - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in France.

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

Total: 5091

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Pegatron      | Benicia                     | [c57fee6ea0](https://linux-hardware.org/?probe=c57fee6ea0) | Jun 10, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [0eae3567d9](https://linux-hardware.org/?probe=0eae3567d9) | Jun 10, 2023 |
| HP            | 339B                        | [bc6de07e07](https://linux-hardware.org/?probe=bc6de07e07) | Jun 09, 2023 |
| ASUSTek       | PRIME X370-PRO              | [77145a587d](https://linux-hardware.org/?probe=77145a587d) | Jun 09, 2023 |
| Gigabyte      | X570 UD                     | [98a10d2fd9](https://linux-hardware.org/?probe=98a10d2fd9) | Jun 08, 2023 |
| Dell          | 0GY6Y8 A02                  | [65f988a0c3](https://linux-hardware.org/?probe=65f988a0c3) | Jun 08, 2023 |
| AZW           | SEi                         | [399b4a7add](https://linux-hardware.org/?probe=399b4a7add) | Jun 08, 2023 |
| Unknown       | Unknown                     | [2c3b00b1ae](https://linux-hardware.org/?probe=2c3b00b1ae) | Jun 08, 2023 |
| Gigabyte      | GA-A75M-D2H                 | [f78a07f792](https://linux-hardware.org/?probe=f78a07f792) | Jun 08, 2023 |
| Techvision    | TVI7309X B0                 | [57b238a5ff](https://linux-hardware.org/?probe=57b238a5ff) | Jun 08, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [87f789c059](https://linux-hardware.org/?probe=87f789c059) | Jun 07, 2023 |
| MSI           | A88XM-E35                   | [efe1285363](https://linux-hardware.org/?probe=efe1285363) | Jun 07, 2023 |
| HP            | 8169                        | [45543e5040](https://linux-hardware.org/?probe=45543e5040) | Jun 07, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [933978a1ae](https://linux-hardware.org/?probe=933978a1ae) | Jun 07, 2023 |
| ASUSTek       | PRIME B360-PLUS             | [8b82994313](https://linux-hardware.org/?probe=8b82994313) | Jun 07, 2023 |
| ASUSTek       | H97M-E                      | [97140e9688](https://linux-hardware.org/?probe=97140e9688) | Jun 07, 2023 |
| Lenovo        | Kabini CRB 31900058 STD     | [8f3282c700](https://linux-hardware.org/?probe=8f3282c700) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | [326a620bbd](https://linux-hardware.org/?probe=326a620bbd) | Jun 06, 2023 |
| MSI           | B85-G43 GAMING              | [9cfd61dae7](https://linux-hardware.org/?probe=9cfd61dae7) | Jun 06, 2023 |
| ASRock        | G41M-GS3                    | [f8789775fe](https://linux-hardware.org/?probe=f8789775fe) | Jun 05, 2023 |
| Intel         | DE3815TYKH H26998-402       | [d2f97c16e9](https://linux-hardware.org/?probe=d2f97c16e9) | Jun 05, 2023 |
| Dell          | 0DF42J A00                  | [c68dff0dd7](https://linux-hardware.org/?probe=c68dff0dd7) | Jun 05, 2023 |
| Gigabyte      | F2A55M-DS2                  | [74b01a9071](https://linux-hardware.org/?probe=74b01a9071) | Jun 05, 2023 |
| HP            | 1850                        | [bddc14be8b](https://linux-hardware.org/?probe=bddc14be8b) | Jun 05, 2023 |
| Intel         | DH55HC AAE70933-503         | [b3d5e112eb](https://linux-hardware.org/?probe=b3d5e112eb) | Jun 04, 2023 |
| MSI           | H81M-P32                    | [f2423b3ef9](https://linux-hardware.org/?probe=f2423b3ef9) | Jun 04, 2023 |
| MSI           | H81M-P32                    | [f1d0b1d487](https://linux-hardware.org/?probe=f1d0b1d487) | Jun 04, 2023 |
| Acer          | Aspire TC-705               | [8aa3bc4947](https://linux-hardware.org/?probe=8aa3bc4947) | Jun 03, 2023 |
| MSI           | H97M-G43                    | [6bd1b61977](https://linux-hardware.org/?probe=6bd1b61977) | Jun 03, 2023 |
| Gigabyte      | B650M GAMING X AX           | [610ba5871f](https://linux-hardware.org/?probe=610ba5871f) | Jun 03, 2023 |
| Acer          | Aspire X3950                | [82aa882647](https://linux-hardware.org/?probe=82aa882647) | Jun 02, 2023 |
| ASRockRack    | X470D4U2-2T                 | [43901d3db7](https://linux-hardware.org/?probe=43901d3db7) | Jun 02, 2023 |
| ECS           | Nettle2                     | [6fe297e475](https://linux-hardware.org/?probe=6fe297e475) | Jun 02, 2023 |
| Acer          | Aspire X3950                | [1c7f0f7567](https://linux-hardware.org/?probe=1c7f0f7567) | Jun 02, 2023 |
| HP            | 802E                        | [1837c96bfd](https://linux-hardware.org/?probe=1837c96bfd) | Jun 02, 2023 |
| MSI           | H81M-E34                    | [26362cac22](https://linux-hardware.org/?probe=26362cac22) | Jun 02, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [def2c6020b](https://linux-hardware.org/?probe=def2c6020b) | Jun 01, 2023 |
| MSI           | H81M-E34                    | [9f04387a7c](https://linux-hardware.org/?probe=9f04387a7c) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | [f517c1893a](https://linux-hardware.org/?probe=f517c1893a) | Jun 01, 2023 |
| HP            | 18E5                        | [9d89c3065b](https://linux-hardware.org/?probe=9d89c3065b) | Jun 01, 2023 |
| MSI           | H510M-A PRO                 | [8557cd4efa](https://linux-hardware.org/?probe=8557cd4efa) | Jun 01, 2023 |
| Supermicro    | X12STD-F                    | [8511ce89ad](https://linux-hardware.org/?probe=8511ce89ad) | Jun 01, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [9faf2de183](https://linux-hardware.org/?probe=9faf2de183) | Jun 01, 2023 |
| MSI           | B85M-G43                    | [38fb05719a](https://linux-hardware.org/?probe=38fb05719a) | May 31, 2023 |
| ASRock        | X570 Phantom Gaming 4       | [6c3655186f](https://linux-hardware.org/?probe=6c3655186f) | May 31, 2023 |
| ASUSTek       | P4S8L                       | [c26269028e](https://linux-hardware.org/?probe=c26269028e) | May 30, 2023 |
| Cincoze       | 1.0.01.001                  | [1552e93368](https://linux-hardware.org/?probe=1552e93368) | May 30, 2023 |
| MSI           | H55M-ED55                   | [a89bdc8ec0](https://linux-hardware.org/?probe=a89bdc8ec0) | May 30, 2023 |
| HP            | 0B54h D                     | [c7813156eb](https://linux-hardware.org/?probe=c7813156eb) | May 30, 2023 |
| ASUSTek       | PRIME Z370-P                | [afb02cee29](https://linux-hardware.org/?probe=afb02cee29) | May 29, 2023 |
| MSI           | Z170A MPOWER GAMING TITA... | [0e9239c5f7](https://linux-hardware.org/?probe=0e9239c5f7) | May 29, 2023 |
| Gigabyte      | H410M H                     | [7a52f09646](https://linux-hardware.org/?probe=7a52f09646) | May 29, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [a46f523ea2](https://linux-hardware.org/?probe=a46f523ea2) | May 29, 2023 |
| MSI           | A320M-A PRO                 | [88f3c7f5e5](https://linux-hardware.org/?probe=88f3c7f5e5) | May 29, 2023 |
| ASUSTek       | H81M-C                      | [ece00aac41](https://linux-hardware.org/?probe=ece00aac41) | May 29, 2023 |
| Dell          | 048DY8 A01                  | [9bfe61714e](https://linux-hardware.org/?probe=9bfe61714e) | May 28, 2023 |
| ASRock        | Z370 Professional Gaming... | [f7d00f30cb](https://linux-hardware.org/?probe=f7d00f30cb) | May 28, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [7af2cff4d7](https://linux-hardware.org/?probe=7af2cff4d7) | May 27, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [449d13baa5](https://linux-hardware.org/?probe=449d13baa5) | May 27, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [7d4df58daf](https://linux-hardware.org/?probe=7d4df58daf) | May 27, 2023 |
| MSI           | H55M-ED55                   | [61e1fc3841](https://linux-hardware.org/?probe=61e1fc3841) | May 27, 2023 |
| Dell          | 0TP406                      | [c7300f35f4](https://linux-hardware.org/?probe=c7300f35f4) | May 26, 2023 |
| ASRock        | X300M-STX                   | [c3af0f3242](https://linux-hardware.org/?probe=c3af0f3242) | May 26, 2023 |
| Dell          | 0NDYHG A01                  | [07be92d6f3](https://linux-hardware.org/?probe=07be92d6f3) | May 26, 2023 |
| ASUSTek       | P4S8L                       | [75096a0d55](https://linux-hardware.org/?probe=75096a0d55) | May 25, 2023 |
| ASRock        | H61M-VG4                    | [4a6c3586fa](https://linux-hardware.org/?probe=4a6c3586fa) | May 25, 2023 |
| Foxconn       | 2ABF                        | [a764ae9f3c](https://linux-hardware.org/?probe=a764ae9f3c) | May 25, 2023 |
| Acer          | EG31M R01-A4                | [447645dad3](https://linux-hardware.org/?probe=447645dad3) | May 25, 2023 |
| Foxconn       | 2ABF                        | [9fbeb26e54](https://linux-hardware.org/?probe=9fbeb26e54) | May 24, 2023 |
| HP            | 1496                        | [2edc574902](https://linux-hardware.org/?probe=2edc574902) | May 24, 2023 |
| Gigabyte      | GA-MA785GMT-UD2H            | [8fd8cdb823](https://linux-hardware.org/?probe=8fd8cdb823) | May 24, 2023 |
| Lenovo        | 318E SDK0L22692 WIN 3792... | [5fb6f16a6d](https://linux-hardware.org/?probe=5fb6f16a6d) | May 24, 2023 |
| ASRock        | E350M1                      | [d366f5f318](https://linux-hardware.org/?probe=d366f5f318) | May 24, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [5837575ac6](https://linux-hardware.org/?probe=5837575ac6) | May 23, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [dc47e13a60](https://linux-hardware.org/?probe=dc47e13a60) | May 23, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [4e817c1abf](https://linux-hardware.org/?probe=4e817c1abf) | May 23, 2023 |
| ASRock        | E350M1                      | [1debe3dcdf](https://linux-hardware.org/?probe=1debe3dcdf) | May 23, 2023 |
| MSI           | H81M-E34                    | [4247f30888](https://linux-hardware.org/?probe=4247f30888) | May 23, 2023 |
| Unknown       | Unknown                     | [977cf42905](https://linux-hardware.org/?probe=977cf42905) | May 23, 2023 |
| HP            | 1791                        | [7fa95d1b7b](https://linux-hardware.org/?probe=7fa95d1b7b) | May 22, 2023 |
| ASRock        | B450 Steel Legend           | [012c721256](https://linux-hardware.org/?probe=012c721256) | May 22, 2023 |
| Gigabyte      | B450M DS3H-CF               | [2b2367f9b1](https://linux-hardware.org/?probe=2b2367f9b1) | May 22, 2023 |
| MSI           | PRO Z690-A DDR4             | [b3fb445705](https://linux-hardware.org/?probe=b3fb445705) | May 22, 2023 |
| Dell          | 0PC5F7 A03                  | [8b4b66a085](https://linux-hardware.org/?probe=8b4b66a085) | May 22, 2023 |
| HP            | 1589                        | [a7d56849a5](https://linux-hardware.org/?probe=a7d56849a5) | May 22, 2023 |
| Lenovo        | 3753 NOK                    | [f2971c14a7](https://linux-hardware.org/?probe=f2971c14a7) | May 21, 2023 |
| Gigabyte      | B450M H                     | [9db5706bfc](https://linux-hardware.org/?probe=9db5706bfc) | May 21, 2023 |
| ASRock        | B550M Phantom Gaming 4      | [31c946c569](https://linux-hardware.org/?probe=31c946c569) | May 21, 2023 |
| Gigabyte      | Z490I AORUS ULTRA           | [14e978a000](https://linux-hardware.org/?probe=14e978a000) | May 20, 2023 |
| ASUSTek       | P8Z77-V                     | [b38a68e146](https://linux-hardware.org/?probe=b38a68e146) | May 20, 2023 |
| MSI           | H97M-G43                    | [2e31a2b7e0](https://linux-hardware.org/?probe=2e31a2b7e0) | May 20, 2023 |
| Pegatron      | Benicia                     | [24fc512198](https://linux-hardware.org/?probe=24fc512198) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [9f1830f264](https://linux-hardware.org/?probe=9f1830f264) | May 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [52bfbb69ee](https://linux-hardware.org/?probe=52bfbb69ee) | May 19, 2023 |
| ASUSTek       | TUF Gaming Z490-PLUS        | [6d04bdb08d](https://linux-hardware.org/?probe=6d04bdb08d) | May 19, 2023 |
| Gigabyte      | H55M-USB3                   | [bb5b5bd73c](https://linux-hardware.org/?probe=bb5b5bd73c) | May 19, 2023 |
| Pegatron      | Benicia                     | [6bb420fe9a](https://linux-hardware.org/?probe=6bb420fe9a) | May 19, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [d8d391a609](https://linux-hardware.org/?probe=d8d391a609) | May 18, 2023 |
| Packard Be... | PT890-8237A                 | [b15e7cc105](https://linux-hardware.org/?probe=b15e7cc105) | May 18, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [c09d32ebc2](https://linux-hardware.org/?probe=c09d32ebc2) | May 18, 2023 |
| ASUSTek       | P5KPL-SE                    | [2914e5278a](https://linux-hardware.org/?probe=2914e5278a) | May 18, 2023 |
| ASUSTek       | M4A77TD                     | [ccd791a9d4](https://linux-hardware.org/?probe=ccd791a9d4) | May 18, 2023 |
| Gateway       | DS10G                       | [556a92e56a](https://linux-hardware.org/?probe=556a92e56a) | May 18, 2023 |
| Pegatron      | Benicia                     | [8d49889e39](https://linux-hardware.org/?probe=8d49889e39) | May 18, 2023 |
| Gigabyte      | B560 HD3                    | [2a6dcbf826](https://linux-hardware.org/?probe=2a6dcbf826) | May 17, 2023 |
| ASUSTek       | PRIME B365-PLUS             | [d43fc4e5b9](https://linux-hardware.org/?probe=d43fc4e5b9) | May 17, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [863f20642f](https://linux-hardware.org/?probe=863f20642f) | May 17, 2023 |
| ASUSTek       | B150-PLUS                   | [41b19667a8](https://linux-hardware.org/?probe=41b19667a8) | May 17, 2023 |
| ASRock        | A300M-STX                   | [b06c75ac5e](https://linux-hardware.org/?probe=b06c75ac5e) | May 16, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [4529ae76bb](https://linux-hardware.org/?probe=4529ae76bb) | May 15, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [6a8a2f481e](https://linux-hardware.org/?probe=6a8a2f481e) | May 15, 2023 |
| ASUSTek       | M5A88-V EVO                 | [02da78340f](https://linux-hardware.org/?probe=02da78340f) | May 15, 2023 |
| HP            | 8436                        | [ae94b377fd](https://linux-hardware.org/?probe=ae94b377fd) | May 15, 2023 |
| Gigabyte      | Z77X-D3H                    | [2e2744285f](https://linux-hardware.org/?probe=2e2744285f) | May 15, 2023 |
| HP            | 3397                        | [c6f97f09f1](https://linux-hardware.org/?probe=c6f97f09f1) | May 13, 2023 |
| ASUSTek       | P5N-E SLI                   | [56783f77b9](https://linux-hardware.org/?probe=56783f77b9) | May 13, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [ede664c4ca](https://linux-hardware.org/?probe=ede664c4ca) | May 13, 2023 |
| Fujitsu       | D3011-A1 S26361-D3011-A1    | [4849aadd59](https://linux-hardware.org/?probe=4849aadd59) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | [ef9c6905f1](https://linux-hardware.org/?probe=ef9c6905f1) | May 13, 2023 |
| MSI           | MAG B550M BAZOOKA           | [bfff1b604f](https://linux-hardware.org/?probe=bfff1b604f) | May 13, 2023 |
| ASUSTek       | GL10CS                      | [270c5658e6](https://linux-hardware.org/?probe=270c5658e6) | May 13, 2023 |
| Dell          | 0D883F A05                  | [99e782e805](https://linux-hardware.org/?probe=99e782e805) | May 13, 2023 |
| Gigabyte      | X570S AORUS PRO AX          | [30bda7d8cb](https://linux-hardware.org/?probe=30bda7d8cb) | May 12, 2023 |
| ASUSTek       | P5B-Deluxe                  | [87edc3a632](https://linux-hardware.org/?probe=87edc3a632) | May 12, 2023 |
| Dell          | 04YP6J A02                  | [aec2bbbb46](https://linux-hardware.org/?probe=aec2bbbb46) | May 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [64159d4a10](https://linux-hardware.org/?probe=64159d4a10) | May 11, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [68caa87cfd](https://linux-hardware.org/?probe=68caa87cfd) | May 11, 2023 |
| Dell          | 09M8Y8 A01                  | [6131eb37d1](https://linux-hardware.org/?probe=6131eb37d1) | May 11, 2023 |
| ASRockRack    | X470D4U2-2T                 | [25b993b097](https://linux-hardware.org/?probe=25b993b097) | May 10, 2023 |
| ASUSTek       | PRIME Z370-P II             | [4d84deed6b](https://linux-hardware.org/?probe=4d84deed6b) | May 09, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [dc1db599ea](https://linux-hardware.org/?probe=dc1db599ea) | May 09, 2023 |
| MSI           | B85-G43                     | [461e3ed4bc](https://linux-hardware.org/?probe=461e3ed4bc) | May 09, 2023 |
| Gigabyte      | F2A78M-HD2                  | [0a758d5a5d](https://linux-hardware.org/?probe=0a758d5a5d) | May 08, 2023 |
| Dell          | 0XCR8D A02                  | [5bc5ccdcad](https://linux-hardware.org/?probe=5bc5ccdcad) | May 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [4e424e0ad2](https://linux-hardware.org/?probe=4e424e0ad2) | May 08, 2023 |
| Dell          | 0T656F A01                  | [94294c8cf0](https://linux-hardware.org/?probe=94294c8cf0) | May 08, 2023 |
| HP            | 3031h                       | [dc7b257f83](https://linux-hardware.org/?probe=dc7b257f83) | May 08, 2023 |
| ASUSTek       | P5Q SE2                     | [c7d1eac585](https://linux-hardware.org/?probe=c7d1eac585) | May 07, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [0fa7cb39ce](https://linux-hardware.org/?probe=0fa7cb39ce) | May 07, 2023 |
| ASRock        | X570 Phantom Gaming X       | [4681975f9d](https://linux-hardware.org/?probe=4681975f9d) | May 07, 2023 |
| Shuttle       | FZ77                        | [e4a71bcb2d](https://linux-hardware.org/?probe=e4a71bcb2d) | May 07, 2023 |
| Intel         | WADE-8076-ST-WMS            | [ae71682181](https://linux-hardware.org/?probe=ae71682181) | May 06, 2023 |
| HP            | 1589                        | [dd3e55b423](https://linux-hardware.org/?probe=dd3e55b423) | May 05, 2023 |
| Dell          | 0PU052                      | [03c6b8486e](https://linux-hardware.org/?probe=03c6b8486e) | May 05, 2023 |
| Gigabyte      | B550 GAMING X V2            | [11a0e59867](https://linux-hardware.org/?probe=11a0e59867) | May 04, 2023 |
| Acer          | Aspire X1430                | [4bdb74f57e](https://linux-hardware.org/?probe=4bdb74f57e) | May 04, 2023 |
| ASUSTek       | Z170I PRO GAMING            | [da8be5a40f](https://linux-hardware.org/?probe=da8be5a40f) | May 04, 2023 |
| Acer          | H57M01                      | [affe73e1a5](https://linux-hardware.org/?probe=affe73e1a5) | May 03, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [456582ed94](https://linux-hardware.org/?probe=456582ed94) | May 03, 2023 |
| Gigabyte      | P55A-UD3                    | [c338210639](https://linux-hardware.org/?probe=c338210639) | May 03, 2023 |
| Gigabyte      | X670E AORUS MASTER          | [f115308631](https://linux-hardware.org/?probe=f115308631) | May 03, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [ee33a17baa](https://linux-hardware.org/?probe=ee33a17baa) | May 02, 2023 |
| HP            | 2AFB                        | [a2d8494867](https://linux-hardware.org/?probe=a2d8494867) | May 01, 2023 |
| MSI           | A320M-A PRO MAX             | [6bfbb6bee6](https://linux-hardware.org/?probe=6bfbb6bee6) | May 01, 2023 |
| ASRock        | H61M-VS                     | [4946cab965](https://linux-hardware.org/?probe=4946cab965) | May 01, 2023 |
| Intel         | DG41RQ AAE54511-203         | [4eb2bc6e88](https://linux-hardware.org/?probe=4eb2bc6e88) | May 01, 2023 |
| ASUSTek       | P8Z77-V DELUXE              | [2fd44c38fd](https://linux-hardware.org/?probe=2fd44c38fd) | May 01, 2023 |
| MSI           | B85-G43 GAMING              | [0d041ed447](https://linux-hardware.org/?probe=0d041ed447) | May 01, 2023 |
| MSI           | X99A GAMING 7               | [dfb285267c](https://linux-hardware.org/?probe=dfb285267c) | May 01, 2023 |
| MSI           | Z77A-G43                    | [02c2bfee54](https://linux-hardware.org/?probe=02c2bfee54) | May 01, 2023 |
| MSI           | IONA                        | [966ec83038](https://linux-hardware.org/?probe=966ec83038) | Apr 30, 2023 |
| Pegatron      | NARRA5                      | [4c8bb5eff0](https://linux-hardware.org/?probe=4c8bb5eff0) | Apr 30, 2023 |
| Lenovo        | 370A SDK0J40700 WIN 3258... | [9a1d443928](https://linux-hardware.org/?probe=9a1d443928) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | [8cb7a3612c](https://linux-hardware.org/?probe=8cb7a3612c) | Apr 30, 2023 |
| Gigabyte      | B660 GAMING X DDR4          | [c203c197b7](https://linux-hardware.org/?probe=c203c197b7) | Apr 29, 2023 |
| ASUSTek       | PRIME X470-PRO              | [244cfe88a4](https://linux-hardware.org/?probe=244cfe88a4) | Apr 29, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [815dd8e866](https://linux-hardware.org/?probe=815dd8e866) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | [266688994a](https://linux-hardware.org/?probe=266688994a) | Apr 28, 2023 |
| MSI           | PRO X670-P WIFI             | [af0663fd52](https://linux-hardware.org/?probe=af0663fd52) | Apr 28, 2023 |
| ASUSTek       | P5Q                         | [6daa7002c8](https://linux-hardware.org/?probe=6daa7002c8) | Apr 27, 2023 |
| ASUSTek       | Z97-P                       | [8d94344086](https://linux-hardware.org/?probe=8d94344086) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [e694779b17](https://linux-hardware.org/?probe=e694779b17) | Apr 26, 2023 |
| Lenovo        | SHARKBAY NOK                | [1e07e42dd3](https://linux-hardware.org/?probe=1e07e42dd3) | Apr 26, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [474c43577f](https://linux-hardware.org/?probe=474c43577f) | Apr 26, 2023 |
| ASUSTek       | P8H67-M                     | [7bed835979](https://linux-hardware.org/?probe=7bed835979) | Apr 26, 2023 |
| HP            | 1825                        | [5a26051aec](https://linux-hardware.org/?probe=5a26051aec) | Apr 26, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [a89604dccd](https://linux-hardware.org/?probe=a89604dccd) | Apr 26, 2023 |
| MSI           | H110M PRO-VD                | [d9decf6f0a](https://linux-hardware.org/?probe=d9decf6f0a) | Apr 26, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [a343d9158a](https://linux-hardware.org/?probe=a343d9158a) | Apr 26, 2023 |
| ASRock        | G31M-S                      | [98c2b2c382](https://linux-hardware.org/?probe=98c2b2c382) | Apr 25, 2023 |
| ASUSTek       | PRIME X570-P                | [290f3ebad7](https://linux-hardware.org/?probe=290f3ebad7) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | [cb8885f205](https://linux-hardware.org/?probe=cb8885f205) | Apr 25, 2023 |
| Gigabyte      | P55-UD3                     | [cacc141f4f](https://linux-hardware.org/?probe=cacc141f4f) | Apr 25, 2023 |
| Lenovo        | 103D SDK0J40697 WIN 3305... | [f82b3152d0](https://linux-hardware.org/?probe=f82b3152d0) | Apr 25, 2023 |
| ASUSTek       | PRIME B550M-A               | [e4c737a64d](https://linux-hardware.org/?probe=e4c737a64d) | Apr 25, 2023 |
| MSI           | H110M ECO                   | [bfa2b17374](https://linux-hardware.org/?probe=bfa2b17374) | Apr 24, 2023 |
| ASUSTek       | PRIME Z590-P                | [ebe492b020](https://linux-hardware.org/?probe=ebe492b020) | Apr 24, 2023 |
| Gigabyte      | Z97-D3H-CF                  | [a62e386eae](https://linux-hardware.org/?probe=a62e386eae) | Apr 24, 2023 |
| G7-2011       | X79                         | [5070a0a7a7](https://linux-hardware.org/?probe=5070a0a7a7) | Apr 24, 2023 |
| Dell          | 0VHRW1 A03                  | [6316886f98](https://linux-hardware.org/?probe=6316886f98) | Apr 24, 2023 |
| MSI           | B450M PRO-VDH PLUS          | [5e6b796278](https://linux-hardware.org/?probe=5e6b796278) | Apr 24, 2023 |
| Gigabyte      | Z97-D3H-CF                  | [bd9d832f72](https://linux-hardware.org/?probe=bd9d832f72) | Apr 23, 2023 |
| Gigabyte      | Z97P-D3                     | [5da4c37f75](https://linux-hardware.org/?probe=5da4c37f75) | Apr 23, 2023 |
| Shuttle       | DS20U                       | [2e8e79b5ff](https://linux-hardware.org/?probe=2e8e79b5ff) | Apr 23, 2023 |
| HP            | 845A                        | [41a0cad635](https://linux-hardware.org/?probe=41a0cad635) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [ccb49b32a0](https://linux-hardware.org/?probe=ccb49b32a0) | Apr 23, 2023 |
| Gigabyte      | B550 VISION D-P             | [2651f47f8c](https://linux-hardware.org/?probe=2651f47f8c) | Apr 23, 2023 |
| MSI           | X370 GAMING PLUS            | [5d61deb4d4](https://linux-hardware.org/?probe=5d61deb4d4) | Apr 23, 2023 |
| Gigabyte      | B760M GAMING X AX DDR4      | [a68d32d442](https://linux-hardware.org/?probe=a68d32d442) | Apr 23, 2023 |
| Gigabyte      | EP45-UD3                    | [5d45f63468](https://linux-hardware.org/?probe=5d45f63468) | Apr 22, 2023 |
| Dell          | 0CRH6C A00                  | [cbb78e1785](https://linux-hardware.org/?probe=cbb78e1785) | Apr 22, 2023 |
| Gigabyte      | Z390 UD                     | [c9e17ad011](https://linux-hardware.org/?probe=c9e17ad011) | Apr 22, 2023 |
| MSI           | X399 SLI PLUS               | [ebb44ab29d](https://linux-hardware.org/?probe=ebb44ab29d) | Apr 22, 2023 |
| ASUSTek       | M5A97 R2.0                  | [90e0cff0ad](https://linux-hardware.org/?probe=90e0cff0ad) | Apr 22, 2023 |
| ASUSTek       | PRIME X570-P                | [f23eeda727](https://linux-hardware.org/?probe=f23eeda727) | Apr 22, 2023 |
| Gigabyte      | EX58-UD5                    | [1ffb09ff2a](https://linux-hardware.org/?probe=1ffb09ff2a) | Apr 22, 2023 |
| Medion        | MS-7621                     | [efb8293786](https://linux-hardware.org/?probe=efb8293786) | Apr 21, 2023 |
| Intel         | D54250WYK H13922-305        | [a7ef0d6dad](https://linux-hardware.org/?probe=a7ef0d6dad) | Apr 21, 2023 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [fd91075868](https://linux-hardware.org/?probe=fd91075868) | Apr 21, 2023 |
| MSI           | MAG Z390 TOMAHAWK           | [9f81660d12](https://linux-hardware.org/?probe=9f81660d12) | Apr 20, 2023 |
| Gigabyte      | H61M-DS2                    | [8c43353ee9](https://linux-hardware.org/?probe=8c43353ee9) | Apr 20, 2023 |
| Lenovo        | ThinkCentre M90p 3282B5G    | [9741f7bd1e](https://linux-hardware.org/?probe=9741f7bd1e) | Apr 20, 2023 |
| ASUSTek       | PRIME X570-PRO              | [6ea882bacb](https://linux-hardware.org/?probe=6ea882bacb) | Apr 20, 2023 |
| Gigabyte      | B550 GAMING X               | [a815ec2fa2](https://linux-hardware.org/?probe=a815ec2fa2) | Apr 19, 2023 |
| Gigabyte      | Z97-HD3                     | [8b560b455e](https://linux-hardware.org/?probe=8b560b455e) | Apr 19, 2023 |
| Dell          | 0NDYHG A01                  | [64ea7a1e04](https://linux-hardware.org/?probe=64ea7a1e04) | Apr 19, 2023 |
| HP            | 8906 SMVB                   | [65eb0fa6be](https://linux-hardware.org/?probe=65eb0fa6be) | Apr 19, 2023 |
| Intel         | D510MO AAE76523-401         | [cf5c07a318](https://linux-hardware.org/?probe=cf5c07a318) | Apr 19, 2023 |
| ZOTAC         | H67ITX-C-E 02/03/05         | [27131cb048](https://linux-hardware.org/?probe=27131cb048) | Apr 19, 2023 |
| Unknown       | Unknown                     | [bac14fb22e](https://linux-hardware.org/?probe=bac14fb22e) | Apr 19, 2023 |
| ASUSTek       | SABERTOOTH X58              | [270e47ceb8](https://linux-hardware.org/?probe=270e47ceb8) | Apr 19, 2023 |
| HP            | 1825                        | [5c637a9ef6](https://linux-hardware.org/?probe=5c637a9ef6) | Apr 18, 2023 |
| HP            | 18E7                        | [ef0b00cf80](https://linux-hardware.org/?probe=ef0b00cf80) | Apr 17, 2023 |
| ASUSTek       | P4C800-E                    | [4521f2b9b4](https://linux-hardware.org/?probe=4521f2b9b4) | Apr 17, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [64e06d7111](https://linux-hardware.org/?probe=64e06d7111) | Apr 17, 2023 |
| ASUSTek       | P5Q DELUXE                  | [ebd62c0513](https://linux-hardware.org/?probe=ebd62c0513) | Apr 16, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [7820a9b7bc](https://linux-hardware.org/?probe=7820a9b7bc) | Apr 16, 2023 |
| Gigabyte      | Z170-Gaming K3              | [c31465c0a1](https://linux-hardware.org/?probe=c31465c0a1) | Apr 16, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [fec4fc20a6](https://linux-hardware.org/?probe=fec4fc20a6) | Apr 16, 2023 |
| eMachines     | E945GCU                     | [4e6aa4be24](https://linux-hardware.org/?probe=4e6aa4be24) | Apr 16, 2023 |
| MSI           | PRO H610M-B DDR4            | [65b2e4afa9](https://linux-hardware.org/?probe=65b2e4afa9) | Apr 16, 2023 |
| Dell          | 0TP412                      | [7491d6d66d](https://linux-hardware.org/?probe=7491d6d66d) | Apr 16, 2023 |
| ASRock        | B560M Pro4                  | [af72ecc689](https://linux-hardware.org/?probe=af72ecc689) | Apr 16, 2023 |
| Dell          | 0TP412                      | [c5f0ba736e](https://linux-hardware.org/?probe=c5f0ba736e) | Apr 16, 2023 |
| MSI           | B150A GAMING PRO            | [26432a7622](https://linux-hardware.org/?probe=26432a7622) | Apr 16, 2023 |
| HP            | 83E2                        | [af01123687](https://linux-hardware.org/?probe=af01123687) | Apr 15, 2023 |
| HP            | 83E2                        | [f5052291a4](https://linux-hardware.org/?probe=f5052291a4) | Apr 15, 2023 |
| HP            | 2B4B                        | [9103ce1fce](https://linux-hardware.org/?probe=9103ce1fce) | Apr 14, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [e5b11f4136](https://linux-hardware.org/?probe=e5b11f4136) | Apr 14, 2023 |
| Gigabyte      | P55-UD3R                    | [5e8538987d](https://linux-hardware.org/?probe=5e8538987d) | Apr 14, 2023 |
| Lenovo        | 3098 SDK0J40705 WIN         | [9ab9baf194](https://linux-hardware.org/?probe=9ab9baf194) | Apr 14, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [30d6d32fc1](https://linux-hardware.org/?probe=30d6d32fc1) | Apr 13, 2023 |
| ASUSTek       | M5A97 EVO R2.0              | [70e0ac9475](https://linux-hardware.org/?probe=70e0ac9475) | Apr 13, 2023 |
| ASRock        | H410M-HVS R2.0              | [7f388965d7](https://linux-hardware.org/?probe=7f388965d7) | Apr 13, 2023 |
| Gigabyte      | B460M DS3H V2               | [4e09a1cd3e](https://linux-hardware.org/?probe=4e09a1cd3e) | Apr 13, 2023 |
| Gigabyte      | GA-78LMT-S2P                | [d79266b94f](https://linux-hardware.org/?probe=d79266b94f) | Apr 13, 2023 |
| Lenovo        | MAHOBAY                     | [527e436d2b](https://linux-hardware.org/?probe=527e436d2b) | Apr 12, 2023 |
| ASRock        | Z97M Pro4                   | [d98390c8a7](https://linux-hardware.org/?probe=d98390c8a7) | Apr 12, 2023 |
| Lenovo        | 3098 SDK0E50510 WIN         | [0d8eb6aa86](https://linux-hardware.org/?probe=0d8eb6aa86) | Apr 12, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | [796f3afe73](https://linux-hardware.org/?probe=796f3afe73) | Apr 12, 2023 |
| Dell          | 0XHGV1 A00                  | [6cbdeb350e](https://linux-hardware.org/?probe=6cbdeb350e) | Apr 12, 2023 |
| Intel         | D33217GKE G76540-203        | [c07a4d67ca](https://linux-hardware.org/?probe=c07a4d67ca) | Apr 12, 2023 |
| Unknown       | SKYBAY                      | [9cd0292459](https://linux-hardware.org/?probe=9cd0292459) | Apr 12, 2023 |
| Gigabyte      | X570S UD                    | [2d599510b8](https://linux-hardware.org/?probe=2d599510b8) | Apr 12, 2023 |
| HP            | 2AF7                        | [e9621d5a9c](https://linux-hardware.org/?probe=e9621d5a9c) | Apr 11, 2023 |
| HP            | 2AF7                        | [b187733415](https://linux-hardware.org/?probe=b187733415) | Apr 11, 2023 |
| HP            | 8298                        | [ccde341ebf](https://linux-hardware.org/?probe=ccde341ebf) | Apr 11, 2023 |
| HP            | 8298                        | [bab1bd2943](https://linux-hardware.org/?probe=bab1bd2943) | Apr 11, 2023 |
| ASRock        | B85M-HDS R2.0               | [24bdbac13a](https://linux-hardware.org/?probe=24bdbac13a) | Apr 11, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [c31f7b3b5c](https://linux-hardware.org/?probe=c31f7b3b5c) | Apr 10, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [35f953cfe0](https://linux-hardware.org/?probe=35f953cfe0) | Apr 10, 2023 |
| Dell          | 0F6X5P A00                  | [ab53417291](https://linux-hardware.org/?probe=ab53417291) | Apr 10, 2023 |
| ASUSTek       | P5KPL-AM SE                 | [979e7ab8f3](https://linux-hardware.org/?probe=979e7ab8f3) | Apr 10, 2023 |
| Gigabyte      | H61M-D2-B3                  | [bf18b5af69](https://linux-hardware.org/?probe=bf18b5af69) | Apr 10, 2023 |
| Dell          | 0TTDMJ A00                  | [2b039ea053](https://linux-hardware.org/?probe=2b039ea053) | Apr 09, 2023 |
| MSI           | A320M PRO-VD PLUS           | [709cc4af2c](https://linux-hardware.org/?probe=709cc4af2c) | Apr 09, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | [0f364f6e82](https://linux-hardware.org/?probe=0f364f6e82) | Apr 09, 2023 |
| Gigabyte      | B450M H                     | [7806838777](https://linux-hardware.org/?probe=7806838777) | Apr 09, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [d01569c067](https://linux-hardware.org/?probe=d01569c067) | Apr 08, 2023 |
| Fujitsu       | D3603-A1 S26361-D3603-A1    | [9cd5518f53](https://linux-hardware.org/?probe=9cd5518f53) | Apr 08, 2023 |
| MSI           | B85-G43                     | [49c7de9ea6](https://linux-hardware.org/?probe=49c7de9ea6) | Apr 08, 2023 |
| ASRock        | X79 Extreme6                | [2b3f00ac79](https://linux-hardware.org/?probe=2b3f00ac79) | Apr 08, 2023 |
| Fujitsu       | D3128-A1 S26361-D3128-A1    | [64b9978ed0](https://linux-hardware.org/?probe=64b9978ed0) | Apr 06, 2023 |
| QTQD          | Unknown                     | [5cb163c75a](https://linux-hardware.org/?probe=5cb163c75a) | Apr 06, 2023 |
| ASRock        | H61M-DGS                    | [e2dd28ca36](https://linux-hardware.org/?probe=e2dd28ca36) | Apr 06, 2023 |
| Dell          | 0F5C5X A00                  | [0e0a176bf8](https://linux-hardware.org/?probe=0e0a176bf8) | Apr 06, 2023 |
| ASUSTek       | H97M-E                      | [4d639304bf](https://linux-hardware.org/?probe=4d639304bf) | Apr 05, 2023 |
| HP            | 84FD                        | [7e80c3baf0](https://linux-hardware.org/?probe=7e80c3baf0) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | [eb35e0beff](https://linux-hardware.org/?probe=eb35e0beff) | Apr 05, 2023 |
| MSI           | B75MA-E33                   | [d89431372f](https://linux-hardware.org/?probe=d89431372f) | Apr 05, 2023 |
| Gigabyte      | 970-GAMING                  | [6ec3c125d5](https://linux-hardware.org/?probe=6ec3c125d5) | Apr 05, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [b5106f816a](https://linux-hardware.org/?probe=b5106f816a) | Apr 04, 2023 |
| MSI           | H110M ECO                   | [983153c81e](https://linux-hardware.org/?probe=983153c81e) | Apr 04, 2023 |
| ASRock        | A320M-DVS R3.0              | [518d9bcac3](https://linux-hardware.org/?probe=518d9bcac3) | Apr 04, 2023 |
| MSI           | MAG B560M MORTAR            | [bbb597effc](https://linux-hardware.org/?probe=bbb597effc) | Apr 04, 2023 |
| Gigabyte      | B560M AORUS ELITE           | [e6b864d24e](https://linux-hardware.org/?probe=e6b864d24e) | Apr 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [248ef68079](https://linux-hardware.org/?probe=248ef68079) | Apr 03, 2023 |
| MSI           | 760GM-P23                   | [7c446415d8](https://linux-hardware.org/?probe=7c446415d8) | Apr 03, 2023 |
| Dell          | 07N90W A02                  | [fd992821e0](https://linux-hardware.org/?probe=fd992821e0) | Apr 03, 2023 |
| Intel         | DG41TY AAE47335-302         | [ecd1f451f0](https://linux-hardware.org/?probe=ecd1f451f0) | Apr 03, 2023 |
| ASRock        | G31M-S                      | [70f35c82f1](https://linux-hardware.org/?probe=70f35c82f1) | Apr 03, 2023 |
| Intel         | DN2820FYK H24582-204        | [ed4e86ebbb](https://linux-hardware.org/?probe=ed4e86ebbb) | Apr 03, 2023 |
| HP            | 1905                        | [2044e303ea](https://linux-hardware.org/?probe=2044e303ea) | Apr 02, 2023 |
| MSI           | A88XM-E35                   | [fb40e13d92](https://linux-hardware.org/?probe=fb40e13d92) | Apr 02, 2023 |
| ASUSTek       | Z97-K                       | [d56ea84c5f](https://linux-hardware.org/?probe=d56ea84c5f) | Apr 02, 2023 |
| Dell          | 0D883F A04                  | [5bdaaa0d23](https://linux-hardware.org/?probe=5bdaaa0d23) | Apr 02, 2023 |
| ASRock        | FM2A88X+ Killer             | [e1c055e8dc](https://linux-hardware.org/?probe=e1c055e8dc) | Apr 02, 2023 |
| Acer          | Veriton X2632G V:1.0        | [f5eafafc96](https://linux-hardware.org/?probe=f5eafafc96) | Apr 02, 2023 |
| Gigabyte      | Z77P-D3                     | [e97e71fc7a](https://linux-hardware.org/?probe=e97e71fc7a) | Apr 02, 2023 |
| Gigabyte      | Z77P-D3                     | [f96e01d74d](https://linux-hardware.org/?probe=f96e01d74d) | Apr 01, 2023 |
| Dell          | 040DDP A00                  | [0771f1547e](https://linux-hardware.org/?probe=0771f1547e) | Apr 01, 2023 |
| Acer          | RS880M05                    | [bddd902030](https://linux-hardware.org/?probe=bddd902030) | Apr 01, 2023 |
| Acer          | Aspire X3400                | [093b0a0239](https://linux-hardware.org/?probe=093b0a0239) | Apr 01, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [79ef948789](https://linux-hardware.org/?probe=79ef948789) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [35bae3b94d](https://linux-hardware.org/?probe=35bae3b94d) | Apr 01, 2023 |
| ASUSTek       | PRIME B350M-A               | [f8afb163dc](https://linux-hardware.org/?probe=f8afb163dc) | Apr 01, 2023 |
| MSI           | H97M-G43                    | [b93caf26e4](https://linux-hardware.org/?probe=b93caf26e4) | Apr 01, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [3599b8e875](https://linux-hardware.org/?probe=3599b8e875) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [d79127e48c](https://linux-hardware.org/?probe=d79127e48c) | Mar 31, 2023 |
| ASUSTek       | P8Z77-V                     | [498726ce78](https://linux-hardware.org/?probe=498726ce78) | Mar 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | [624d23335b](https://linux-hardware.org/?probe=624d23335b) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [d6b6c88578](https://linux-hardware.org/?probe=d6b6c88578) | Mar 31, 2023 |
| MSI           | X470 GAMING PLUS MAX        | [704145641e](https://linux-hardware.org/?probe=704145641e) | Mar 31, 2023 |
| Foxconn       | 2ABF                        | [8daf4bf0a5](https://linux-hardware.org/?probe=8daf4bf0a5) | Mar 30, 2023 |
| MSI           | A320M PRO-VD PLUS           | [9e43a17d1a](https://linux-hardware.org/?probe=9e43a17d1a) | Mar 30, 2023 |
| ASRock        | FM2A88X Extreme6+           | [ad1392d8c0](https://linux-hardware.org/?probe=ad1392d8c0) | Mar 30, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [76e09994d0](https://linux-hardware.org/?probe=76e09994d0) | Mar 30, 2023 |
| Packard Be... | MCP73PV                     | [2082d90602](https://linux-hardware.org/?probe=2082d90602) | Mar 30, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [de5bf4239c](https://linux-hardware.org/?probe=de5bf4239c) | Mar 30, 2023 |
| HP            | 82B4                        | [0829a64947](https://linux-hardware.org/?probe=0829a64947) | Mar 30, 2023 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | [cfe80f22f8](https://linux-hardware.org/?probe=cfe80f22f8) | Mar 30, 2023 |
| ASUSTek       | M5A97                       | [4d12d122e1](https://linux-hardware.org/?probe=4d12d122e1) | Mar 30, 2023 |
| Shuttle       | FH170                       | [0fa0f1ab72](https://linux-hardware.org/?probe=0fa0f1ab72) | Mar 30, 2023 |
| ASRockRack    | X470D4U2-2T                 | [38e3ecfb84](https://linux-hardware.org/?probe=38e3ecfb84) | Mar 29, 2023 |
| ASUSTek       | Q170M2                      | [8808e457a1](https://linux-hardware.org/?probe=8808e457a1) | Mar 29, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [dadeec8815](https://linux-hardware.org/?probe=dadeec8815) | Mar 29, 2023 |
| ASRock        | X470 Master SLI             | [e4d56ca8c8](https://linux-hardware.org/?probe=e4d56ca8c8) | Mar 28, 2023 |
| ASRock        | H61M-DG3/USB3               | [6e7b188568](https://linux-hardware.org/?probe=6e7b188568) | Mar 28, 2023 |
| HP            | 0A60h                       | [6ad65f4f2b](https://linux-hardware.org/?probe=6ad65f4f2b) | Mar 28, 2023 |
| MSI           | B85-G43                     | [3dac8c76c2](https://linux-hardware.org/?probe=3dac8c76c2) | Mar 28, 2023 |
| Lenovo        | 36D9 SDK0J40700 WIN 3258... | [16db0eb166](https://linux-hardware.org/?probe=16db0eb166) | Mar 28, 2023 |
| Dell          | 0WR7PY A01                  | [5f0453caf8](https://linux-hardware.org/?probe=5f0453caf8) | Mar 28, 2023 |
| ASRock        | G31M-S                      | [4ad324790c](https://linux-hardware.org/?probe=4ad324790c) | Mar 28, 2023 |
| ASRock        | G31M-S                      | [225f122e05](https://linux-hardware.org/?probe=225f122e05) | Mar 28, 2023 |
| HP            | 1497                        | [94c6f8a63a](https://linux-hardware.org/?probe=94c6f8a63a) | Mar 27, 2023 |
| Gigabyte      | WRX80-SU8                   | [88c24f7e44](https://linux-hardware.org/?probe=88c24f7e44) | Mar 27, 2023 |
| Dell          | 0G919G A00                  | [139207e1a7](https://linux-hardware.org/?probe=139207e1a7) | Mar 27, 2023 |
| ASUSTek       | M5A97 R2.0                  | [d56f48b9d1](https://linux-hardware.org/?probe=d56f48b9d1) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [ebed945eae](https://linux-hardware.org/?probe=ebed945eae) | Mar 27, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fd16b858df](https://linux-hardware.org/?probe=fd16b858df) | Mar 27, 2023 |
| ASUSTek       | P8H61-M LE                  | [e834f14d64](https://linux-hardware.org/?probe=e834f14d64) | Mar 27, 2023 |
| HP            | ProLiant ML350 G5           | [b0000fc633](https://linux-hardware.org/?probe=b0000fc633) | Mar 26, 2023 |
| Packard Be... | MCP73PV                     | [87d1fd7511](https://linux-hardware.org/?probe=87d1fd7511) | Mar 26, 2023 |
| Wistron       | ProLiant ML110 G6           | [2e14ac2984](https://linux-hardware.org/?probe=2e14ac2984) | Mar 26, 2023 |
| Dell          | 0VHRW1 A03                  | [9aa3215de8](https://linux-hardware.org/?probe=9aa3215de8) | Mar 26, 2023 |
| ASUSTek       | PRIME H510M-K               | [54e2f18738](https://linux-hardware.org/?probe=54e2f18738) | Mar 26, 2023 |
| Dell          | 0VHRW1 A03                  | [129c2be9aa](https://linux-hardware.org/?probe=129c2be9aa) | Mar 26, 2023 |
| Lenovo        | 36F7 SDK0J40700 WIN 3258... | [e6219e18b1](https://linux-hardware.org/?probe=e6219e18b1) | Mar 25, 2023 |
| Dell          | 0654JC A01                  | [3771b8bf2e](https://linux-hardware.org/?probe=3771b8bf2e) | Mar 25, 2023 |
| ASUSTek       | P5B-Deluxe                  | [3d8b7a6d89](https://linux-hardware.org/?probe=3d8b7a6d89) | Mar 25, 2023 |
| ASUSTek       | H97-PLUS                    | [30d5652df2](https://linux-hardware.org/?probe=30d5652df2) | Mar 25, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [276aa0b036](https://linux-hardware.org/?probe=276aa0b036) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | [34d3fc12b2](https://linux-hardware.org/?probe=34d3fc12b2) | Mar 25, 2023 |
| Dell          | 00V62H A00                  | [f7aaf1dcd0](https://linux-hardware.org/?probe=f7aaf1dcd0) | Mar 25, 2023 |
| ASUSTek       | PRIME B550M-A               | [623f5742ab](https://linux-hardware.org/?probe=623f5742ab) | Mar 25, 2023 |
| Gigabyte      | GA-890FXA-UD5               | [5fccdb098d](https://linux-hardware.org/?probe=5fccdb098d) | Mar 24, 2023 |
| Lenovo        | SDK0E50519 WIN              | [2fb6bb5874](https://linux-hardware.org/?probe=2fb6bb5874) | Mar 24, 2023 |
| Dell          | 0NK5PH A00                  | [f76bc64ee4](https://linux-hardware.org/?probe=f76bc64ee4) | Mar 24, 2023 |
| ASUSTek       | PRIME X470-PRO              | [8af246641b](https://linux-hardware.org/?probe=8af246641b) | Mar 24, 2023 |
| ASUSTek       | PRIME Z590M-PLUS            | [0027308e3d](https://linux-hardware.org/?probe=0027308e3d) | Mar 23, 2023 |
| HP            | 3048h                       | [8cee790d83](https://linux-hardware.org/?probe=8cee790d83) | Mar 23, 2023 |
| HP            | 1905                        | [7bccc34bf4](https://linux-hardware.org/?probe=7bccc34bf4) | Mar 23, 2023 |
| ASUSTek       | ROG Rampage VI EXTREME O... | [d5afcaf7a1](https://linux-hardware.org/?probe=d5afcaf7a1) | Mar 22, 2023 |
| AZW           | GK35                        | [bd935978b7](https://linux-hardware.org/?probe=bd935978b7) | Mar 22, 2023 |
| Dell          | 0HHV7N A00                  | [7b10e71784](https://linux-hardware.org/?probe=7b10e71784) | Mar 22, 2023 |
| MSI           | Z77A-GD80                   | [bcb120034c](https://linux-hardware.org/?probe=bcb120034c) | Mar 21, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [57a69bcf57](https://linux-hardware.org/?probe=57a69bcf57) | Mar 21, 2023 |
| HP            | 21F5                        | [865a85e5bc](https://linux-hardware.org/?probe=865a85e5bc) | Mar 20, 2023 |
| MSI           | H310M PRO-VD                | [1b98d965e7](https://linux-hardware.org/?probe=1b98d965e7) | Mar 20, 2023 |
| ASUSTek       | PRIME Z370-P II             | [3b81f87409](https://linux-hardware.org/?probe=3b81f87409) | Mar 20, 2023 |
| ASUSTek       | M3A78-EMH HDMI              | [0aa8c2bf55](https://linux-hardware.org/?probe=0aa8c2bf55) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [b5d9053f1c](https://linux-hardware.org/?probe=b5d9053f1c) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | [660ae0f7ed](https://linux-hardware.org/?probe=660ae0f7ed) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | [bbe02b925a](https://linux-hardware.org/?probe=bbe02b925a) | Mar 19, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | [d376f92f8d](https://linux-hardware.org/?probe=d376f92f8d) | Mar 19, 2023 |
| Gigabyte      | Z77X-UD5H                   | [dc0a9ba834](https://linux-hardware.org/?probe=dc0a9ba834) | Mar 19, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [1e96b578fa](https://linux-hardware.org/?probe=1e96b578fa) | Mar 18, 2023 |
| ASUSTek       | F2A85-M PRO                 | [5e3e1f990b](https://linux-hardware.org/?probe=5e3e1f990b) | Mar 18, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [0e6f572d41](https://linux-hardware.org/?probe=0e6f572d41) | Mar 18, 2023 |
| Gigabyte      | G41MT-D3                    | [9a4ac88209](https://linux-hardware.org/?probe=9a4ac88209) | Mar 17, 2023 |
| Gigabyte      | AX370-Gaming 5              | [97d434b3b5](https://linux-hardware.org/?probe=97d434b3b5) | Mar 16, 2023 |
| HP            | 158A                        | [4a023a55d8](https://linux-hardware.org/?probe=4a023a55d8) | Mar 16, 2023 |
| Gigabyte      | AX370-Gaming 5              | [dd101b4b05](https://linux-hardware.org/?probe=dd101b4b05) | Mar 16, 2023 |
| Gigabyte      | F2A68HM-DS2                 | [293b961af2](https://linux-hardware.org/?probe=293b961af2) | Mar 16, 2023 |
| Gigabyte      | F2A88XM-D3H                 | [c7a98e4c15](https://linux-hardware.org/?probe=c7a98e4c15) | Mar 16, 2023 |
| ASUSTek       | M5A97 R2.0                  | [526e33e980](https://linux-hardware.org/?probe=526e33e980) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | [34ad3eb730](https://linux-hardware.org/?probe=34ad3eb730) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | [06c53ecdec](https://linux-hardware.org/?probe=06c53ecdec) | Mar 15, 2023 |
| MSI           | H510M-A PRO                 | [92c35e8f43](https://linux-hardware.org/?probe=92c35e8f43) | Mar 15, 2023 |
| MSI           | FM2-A55M-E33                | [d6106fe9e3](https://linux-hardware.org/?probe=d6106fe9e3) | Mar 14, 2023 |
| ASUSTek       | M5A97 R2.0                  | [2f69480899](https://linux-hardware.org/?probe=2f69480899) | Mar 14, 2023 |
| Packard Be... | IMEDIA S3840                | [b54abceafe](https://linux-hardware.org/?probe=b54abceafe) | Mar 14, 2023 |
| HP            | 339A                        | [3110e1b98c](https://linux-hardware.org/?probe=3110e1b98c) | Mar 14, 2023 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [49737df106](https://linux-hardware.org/?probe=49737df106) | Mar 14, 2023 |
| Foxconn       | 2AAF                        | [6d5e3ffeed](https://linux-hardware.org/?probe=6d5e3ffeed) | Mar 13, 2023 |
| MSI           | B85-G43                     | [7e9ce07cb8](https://linux-hardware.org/?probe=7e9ce07cb8) | Mar 13, 2023 |
| MSI           | B85-G43                     | [9a9a70ade3](https://linux-hardware.org/?probe=9a9a70ade3) | Mar 13, 2023 |
| ASUSTek       | PRIME A320M-K               | [e259b3e70a](https://linux-hardware.org/?probe=e259b3e70a) | Mar 12, 2023 |
| HP            | 339A                        | [fa78907d67](https://linux-hardware.org/?probe=fa78907d67) | Mar 12, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [053e36ef52](https://linux-hardware.org/?probe=053e36ef52) | Mar 12, 2023 |
| MSI           | MAG B660M BAZOOKA DDR4      | [cb1be19cd3](https://linux-hardware.org/?probe=cb1be19cd3) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | [28e364aa1a](https://linux-hardware.org/?probe=28e364aa1a) | Mar 11, 2023 |
| MSI           | Z77A-GD80                   | [932497a278](https://linux-hardware.org/?probe=932497a278) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [ef3ba694a9](https://linux-hardware.org/?probe=ef3ba694a9) | Mar 11, 2023 |
| MSI           | B85-G43                     | [47ac638c2e](https://linux-hardware.org/?probe=47ac638c2e) | Mar 11, 2023 |
| Dell          | 0T10XW A00                  | [a47baaadde](https://linux-hardware.org/?probe=a47baaadde) | Mar 11, 2023 |
| HP            | 212B                        | [0ea1ad02f7](https://linux-hardware.org/?probe=0ea1ad02f7) | Mar 11, 2023 |
| Intel         | DH55HC AAE70933-503         | [4d1f3745ac](https://linux-hardware.org/?probe=4d1f3745ac) | Mar 10, 2023 |
| Intel         | DH55HC AAE70933-503         | [46160d5ef3](https://linux-hardware.org/?probe=46160d5ef3) | Mar 10, 2023 |
| Gigabyte      | A320M-H-CF                  | [d519ac8d3e](https://linux-hardware.org/?probe=d519ac8d3e) | Mar 09, 2023 |
| MSI           | Z77A-GD80                   | [3b63adee43](https://linux-hardware.org/?probe=3b63adee43) | Mar 09, 2023 |
| MSI           | Z77A-GD80                   | [f447b1afca](https://linux-hardware.org/?probe=f447b1afca) | Mar 09, 2023 |
| Pegatron      | 2AB5                        | [7e36ff0272](https://linux-hardware.org/?probe=7e36ff0272) | Mar 08, 2023 |
| ASUSTek       | PRIME X570-P                | [588a008ee1](https://linux-hardware.org/?probe=588a008ee1) | Mar 08, 2023 |
| ASUSTek       | H110M-K                     | [f69aaa84ed](https://linux-hardware.org/?probe=f69aaa84ed) | Mar 08, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [cea86809fd](https://linux-hardware.org/?probe=cea86809fd) | Mar 08, 2023 |
| Dell          | 0T10XW A00                  | [fd255666fc](https://linux-hardware.org/?probe=fd255666fc) | Mar 08, 2023 |
| Intel         | D33217GKE G76540-203        | [f18444c5dd](https://linux-hardware.org/?probe=f18444c5dd) | Mar 08, 2023 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | [79459b8b4b](https://linux-hardware.org/?probe=79459b8b4b) | Mar 08, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [b1a69ac03b](https://linux-hardware.org/?probe=b1a69ac03b) | Mar 08, 2023 |
| MSI           | A320M PRO-VD PLUS           | [85e83db4dc](https://linux-hardware.org/?probe=85e83db4dc) | Mar 08, 2023 |
| Packard Be... | IXTREME M5850               | [60b6ba7904](https://linux-hardware.org/?probe=60b6ba7904) | Mar 07, 2023 |
| Pegatron      | 2AD5                        | [3356f97e00](https://linux-hardware.org/?probe=3356f97e00) | Mar 06, 2023 |
| ASUSTek       | Z97-A                       | [6bc7428949](https://linux-hardware.org/?probe=6bc7428949) | Mar 06, 2023 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [98f8bd8557](https://linux-hardware.org/?probe=98f8bd8557) | Mar 06, 2023 |
| ASUSTek       | PRIME A320M-K               | [38cb86265f](https://linux-hardware.org/?probe=38cb86265f) | Mar 06, 2023 |
| Dell          | 048DY8 A00                  | [2ae03ba26f](https://linux-hardware.org/?probe=2ae03ba26f) | Mar 06, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [39187f7b13](https://linux-hardware.org/?probe=39187f7b13) | Mar 06, 2023 |
| Gigabyte      | Z68X-UD3-B3                 | [f2be73745e](https://linux-hardware.org/?probe=f2be73745e) | Mar 06, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [e6421e9301](https://linux-hardware.org/?probe=e6421e9301) | Mar 06, 2023 |
| MSI           | PRO B760M-A WIFI DDR4       | [06bb73cbaa](https://linux-hardware.org/?probe=06bb73cbaa) | Mar 05, 2023 |
| Packard Be... | FIH57                       | [06cd872d9b](https://linux-hardware.org/?probe=06cd872d9b) | Mar 05, 2023 |
| Gigabyte      | MZBAYAP-00                  | [b090a8b795](https://linux-hardware.org/?probe=b090a8b795) | Mar 05, 2023 |
| Medion        | MS-7800                     | [980dc395c7](https://linux-hardware.org/?probe=980dc395c7) | Mar 05, 2023 |
| Medion        | MS-7800                     | [80b8165141](https://linux-hardware.org/?probe=80b8165141) | Mar 05, 2023 |
| ASUSTek       | P8P67                       | [70ee1f3c06](https://linux-hardware.org/?probe=70ee1f3c06) | Mar 04, 2023 |
| Intel         | DH55HC AAE70933-503         | [e038320969](https://linux-hardware.org/?probe=e038320969) | Mar 04, 2023 |
| MSI           | B450M-A PRO MAX             | [bd65553838](https://linux-hardware.org/?probe=bd65553838) | Mar 04, 2023 |
| Pegatron      | 2AD5                        | [86b939ac1a](https://linux-hardware.org/?probe=86b939ac1a) | Mar 03, 2023 |
| ASUSTek       | STRIX H270I GAMING          | [2ff7fe6634](https://linux-hardware.org/?probe=2ff7fe6634) | Mar 03, 2023 |
| Lenovo        | Annapurna CRB NOK           | [5316a545d0](https://linux-hardware.org/?probe=5316a545d0) | Mar 03, 2023 |
| Foxconn       | 2A8C                        | [1cf53baf99](https://linux-hardware.org/?probe=1cf53baf99) | Mar 03, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | [3908191101](https://linux-hardware.org/?probe=3908191101) | Mar 03, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [1da5b61697](https://linux-hardware.org/?probe=1da5b61697) | Mar 02, 2023 |
| Foxconn       | 2ABF                        | [f9213f29ca](https://linux-hardware.org/?probe=f9213f29ca) | Mar 01, 2023 |
| Packard Be... | IMEDIA S3840                | [d0ce638961](https://linux-hardware.org/?probe=d0ce638961) | Mar 01, 2023 |
| ASRock        | B650E PG Riptide WiFi       | [a637650ff7](https://linux-hardware.org/?probe=a637650ff7) | Mar 01, 2023 |
| MSI           | MAG B365M MORTAR            | [26f53549dd](https://linux-hardware.org/?probe=26f53549dd) | Feb 28, 2023 |
| Acer          | Aspire X3995                | [eccac5b752](https://linux-hardware.org/?probe=eccac5b752) | Feb 28, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [2b434f0b1d](https://linux-hardware.org/?probe=2b434f0b1d) | Feb 28, 2023 |
| MSI           | A320M PRO-VD PLUS           | [6677ab11b2](https://linux-hardware.org/?probe=6677ab11b2) | Feb 28, 2023 |
| ASUSTek       | CM6870                      | [e338b721af](https://linux-hardware.org/?probe=e338b721af) | Feb 28, 2023 |
| ASRockRack    | X470D4U2-2T                 | [4d3d5e02a1](https://linux-hardware.org/?probe=4d3d5e02a1) | Feb 28, 2023 |
| MSI           | A320M PRO-M2 V2             | [0264556bba](https://linux-hardware.org/?probe=0264556bba) | Feb 28, 2023 |
| HP            | 3047h                       | [db6be92c4f](https://linux-hardware.org/?probe=db6be92c4f) | Feb 27, 2023 |
| ASUSTek       | Z10PE-D16 WS                | [dd74cb518b](https://linux-hardware.org/?probe=dd74cb518b) | Feb 27, 2023 |
| Unknown       | Unknown                     | [1a407f82b9](https://linux-hardware.org/?probe=1a407f82b9) | Feb 27, 2023 |
| ASRock        | A320M-HDV R4.0              | [37d2aab670](https://linux-hardware.org/?probe=37d2aab670) | Feb 27, 2023 |
| MSI           | Z270 PC MATE                | [6ef23fd12a](https://linux-hardware.org/?probe=6ef23fd12a) | Feb 26, 2023 |
| ASUSTek       | PRIME B350M-A               | [4cd492ee3e](https://linux-hardware.org/?probe=4cd492ee3e) | Feb 26, 2023 |
| ASRock        | B85 Pro4                    | [0b4daba4fb](https://linux-hardware.org/?probe=0b4daba4fb) | Feb 26, 2023 |
| Foxconn       | 2ABF                        | [ead0312777](https://linux-hardware.org/?probe=ead0312777) | Feb 26, 2023 |
| ASUSTek       | PRIME B350M-A               | [9471b0f763](https://linux-hardware.org/?probe=9471b0f763) | Feb 26, 2023 |
| ASRock        | AB350 Pro4                  | [887241ec59](https://linux-hardware.org/?probe=887241ec59) | Feb 26, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [724039adf2](https://linux-hardware.org/?probe=724039adf2) | Feb 26, 2023 |
| Pegatron      | 2AD5                        | [0f487c3a2a](https://linux-hardware.org/?probe=0f487c3a2a) | Feb 26, 2023 |
| MSI           | A320M PRO-VD PLUS           | [bd6c07d84d](https://linux-hardware.org/?probe=bd6c07d84d) | Feb 26, 2023 |
| HP            | 3398                        | [5e7ae4c866](https://linux-hardware.org/?probe=5e7ae4c866) | Feb 25, 2023 |
| HP            | 18E7                        | [7b52dfac52](https://linux-hardware.org/?probe=7b52dfac52) | Feb 25, 2023 |
| HP            | 3047h                       | [8f7d5acf1f](https://linux-hardware.org/?probe=8f7d5acf1f) | Feb 25, 2023 |
| Pegatron      | 2AD5                        | [4c68f5ea84](https://linux-hardware.org/?probe=4c68f5ea84) | Feb 25, 2023 |
| MSI           | B360M PRO-VH                | [fad0bd20e1](https://linux-hardware.org/?probe=fad0bd20e1) | Feb 24, 2023 |
| Dell          | 0VRWRC A00                  | [7089ab33b3](https://linux-hardware.org/?probe=7089ab33b3) | Feb 24, 2023 |
| ASRock        | X370 Professional Gaming    | [cff46cb07b](https://linux-hardware.org/?probe=cff46cb07b) | Feb 24, 2023 |
| MSI           | Z87M GAMING                 | [0603accd89](https://linux-hardware.org/?probe=0603accd89) | Feb 24, 2023 |
| MSI           | X370 GAMING PLUS            | [4d45d5880b](https://linux-hardware.org/?probe=4d45d5880b) | Feb 23, 2023 |
| ASUSTek       | H97M-PLUS                   | [f82cea1be8](https://linux-hardware.org/?probe=f82cea1be8) | Feb 23, 2023 |
| T-bao         | MINI PC                     | [68ba9fc610](https://linux-hardware.org/?probe=68ba9fc610) | Feb 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | [ce8874cff4](https://linux-hardware.org/?probe=ce8874cff4) | Feb 22, 2023 |
| AZW           | U59                         | [9289537f45](https://linux-hardware.org/?probe=9289537f45) | Feb 22, 2023 |
| ASRockRack    | X470D4U2-2T                 | [9d233c96b5](https://linux-hardware.org/?probe=9d233c96b5) | Feb 22, 2023 |
| ASUSTek       | A_F_K20CE                   | [2dffc350dd](https://linux-hardware.org/?probe=2dffc350dd) | Feb 22, 2023 |
| Gigabyte      | H81M-S2PV                   | [ad365efca1](https://linux-hardware.org/?probe=ad365efca1) | Feb 22, 2023 |
| Foxconn       | Lucknow                     | [3ca9a4f66e](https://linux-hardware.org/?probe=3ca9a4f66e) | Feb 22, 2023 |
| Gigabyte      | B360 AORUS GAMING 3 WIFI... | [1d2132b142](https://linux-hardware.org/?probe=1d2132b142) | Feb 22, 2023 |
| ASUSTek       | G11CD                       | [4fc47f45be](https://linux-hardware.org/?probe=4fc47f45be) | Feb 21, 2023 |
| MSI           | B85-G43                     | [62273631b2](https://linux-hardware.org/?probe=62273631b2) | Feb 21, 2023 |
| MSI           | Z170A XPOWER GAMING TITA... | [b644019f77](https://linux-hardware.org/?probe=b644019f77) | Feb 21, 2023 |
| ASUSTek       | PRIME B450M-A               | [8c97a04c10](https://linux-hardware.org/?probe=8c97a04c10) | Feb 21, 2023 |
| Pegatron      | 2A73h                       | [835743de83](https://linux-hardware.org/?probe=835743de83) | Feb 21, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c61a513a81](https://linux-hardware.org/?probe=c61a513a81) | Feb 20, 2023 |
| Lenovo        | 30BC SDK0J40697 WIN 3305... | [2a403bdb2b](https://linux-hardware.org/?probe=2a403bdb2b) | Feb 20, 2023 |
| Gigabyte      | 945P-S3                     | [2cdcb107ab](https://linux-hardware.org/?probe=2cdcb107ab) | Feb 20, 2023 |
| ASRock        | H81M-HDS R2.0               | [32b47345a6](https://linux-hardware.org/?probe=32b47345a6) | Feb 20, 2023 |
| ASUSTek       | SABERTOOTH X99              | [422b14d8d7](https://linux-hardware.org/?probe=422b14d8d7) | Feb 19, 2023 |
| Gigabyte      | X570S AORUS ELITE AX        | [7e45218236](https://linux-hardware.org/?probe=7e45218236) | Feb 19, 2023 |
| ASUSTek       | G10AC                       | [8a367bb885](https://linux-hardware.org/?probe=8a367bb885) | Feb 19, 2023 |
| ASUSTek       | STRIX X99 GAMING            | [8dd1992835](https://linux-hardware.org/?probe=8dd1992835) | Feb 18, 2023 |
| IP3 Tech      | Cherry Trail CR             | [0ff2dc2202](https://linux-hardware.org/?probe=0ff2dc2202) | Feb 17, 2023 |
| Gigabyte      | Z590 AORUS ELITE AX         | [8da7f7cbdc](https://linux-hardware.org/?probe=8da7f7cbdc) | Feb 17, 2023 |
| MSI           | MS-7267                     | [0b89f039c1](https://linux-hardware.org/?probe=0b89f039c1) | Feb 17, 2023 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | [4a3d5fee69](https://linux-hardware.org/?probe=4a3d5fee69) | Feb 17, 2023 |
| Acer          | Veriton M4610G              | [7c5f2f584e](https://linux-hardware.org/?probe=7c5f2f584e) | Feb 17, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | [078d55d158](https://linux-hardware.org/?probe=078d55d158) | Feb 16, 2023 |
| MSI           | H61M-E33                    | [f0c902ce04](https://linux-hardware.org/?probe=f0c902ce04) | Feb 16, 2023 |
| Gigabyte      | F2A78M-HD2                  | [9f9cc6f9e2](https://linux-hardware.org/?probe=9f9cc6f9e2) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [e1bbf14222](https://linux-hardware.org/?probe=e1bbf14222) | Feb 16, 2023 |
| MSI           | X370 GAMING PRO CARBON      | [ba96494c0f](https://linux-hardware.org/?probe=ba96494c0f) | Feb 16, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [e8dc5253a3](https://linux-hardware.org/?probe=e8dc5253a3) | Feb 15, 2023 |
| Dell          | 0NK5PH A00                  | [5455b577db](https://linux-hardware.org/?probe=5455b577db) | Feb 15, 2023 |
| Supermicro    | X7DCL                       | [49e545591c](https://linux-hardware.org/?probe=49e545591c) | Feb 15, 2023 |
| ASUSTek       | PRIME Z590-V                | [4d00371a70](https://linux-hardware.org/?probe=4d00371a70) | Feb 15, 2023 |
| ASUSTek       | PRIME Z690-P WIFI           | [b30e6a84c8](https://linux-hardware.org/?probe=b30e6a84c8) | Feb 14, 2023 |
| HP            | 805D                        | [217784712c](https://linux-hardware.org/?probe=217784712c) | Feb 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [5d2153f4f2](https://linux-hardware.org/?probe=5d2153f4f2) | Feb 14, 2023 |
| Lenovo        | 30BE SDK0K17763 WIN 1801... | [837c0bcb6a](https://linux-hardware.org/?probe=837c0bcb6a) | Feb 14, 2023 |
| Gigabyte      | H87-D3H-CF                  | [2914a1866d](https://linux-hardware.org/?probe=2914a1866d) | Feb 14, 2023 |
| Lenovo        | SHARKBAY NOK                | [4ccd4c2da2](https://linux-hardware.org/?probe=4ccd4c2da2) | Feb 14, 2023 |
| ASUSTek       | Z170-A                      | [6cf7a75c9e](https://linux-hardware.org/?probe=6cf7a75c9e) | Feb 13, 2023 |
| MSI           | MS-B9181                    | [a155bc9fc3](https://linux-hardware.org/?probe=a155bc9fc3) | Feb 13, 2023 |
| ASRock        | E350M1                      | [ac69adceb6](https://linux-hardware.org/?probe=ac69adceb6) | Feb 13, 2023 |
| MSI           | B450M MORTAR                | [5b93510482](https://linux-hardware.org/?probe=5b93510482) | Feb 13, 2023 |
| Gigabyte      | X299 AORUS Gaming 3 Pro-... | [24d20958ab](https://linux-hardware.org/?probe=24d20958ab) | Feb 13, 2023 |
| MSI           | B450M PRO-M2 MAX            | [2032f6e202](https://linux-hardware.org/?probe=2032f6e202) | Feb 13, 2023 |
| Dell          | 0KWVT8 A03                  | [eec95070bb](https://linux-hardware.org/?probe=eec95070bb) | Feb 13, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [68db95ee9b](https://linux-hardware.org/?probe=68db95ee9b) | Feb 12, 2023 |
| ASUSTek       | M5A99X EVO R2.0             | [a74e071a54](https://linux-hardware.org/?probe=a74e071a54) | Feb 12, 2023 |
| Dell          | 0WMJ54 A01                  | [350850e668](https://linux-hardware.org/?probe=350850e668) | Feb 11, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [127e027611](https://linux-hardware.org/?probe=127e027611) | Feb 10, 2023 |
| Gigabyte      | H77N-WIFI                   | [756bc1fc3b](https://linux-hardware.org/?probe=756bc1fc3b) | Feb 10, 2023 |
| Gigabyte      | H77N-WIFI                   | [769b226f8e](https://linux-hardware.org/?probe=769b226f8e) | Feb 10, 2023 |
| Gigabyte      | B365M H                     | [fca49121d5](https://linux-hardware.org/?probe=fca49121d5) | Feb 09, 2023 |
| Supermicro    | X9DAi                       | [546ea7c2e8](https://linux-hardware.org/?probe=546ea7c2e8) | Feb 09, 2023 |
| ASUSTek       | Z97-K                       | [afaaed1c36](https://linux-hardware.org/?probe=afaaed1c36) | Feb 09, 2023 |
| ASRock        | B550 Pro4                   | [9d947022b0](https://linux-hardware.org/?probe=9d947022b0) | Feb 09, 2023 |
| Packard Be... | IMEDIA S3840                | [cc92542e21](https://linux-hardware.org/?probe=cc92542e21) | Feb 08, 2023 |
| Dell          | 0NC2VH A01                  | [85ab2e4223](https://linux-hardware.org/?probe=85ab2e4223) | Feb 08, 2023 |
| Packard Be... | IMEDIA S3840                | [190d8c3b40](https://linux-hardware.org/?probe=190d8c3b40) | Feb 08, 2023 |
| ASUSTek       | H81-PLUS                    | [c01a8b01f0](https://linux-hardware.org/?probe=c01a8b01f0) | Feb 08, 2023 |
| ASUSTek       | PRIME X399-A                | [22ba7d722f](https://linux-hardware.org/?probe=22ba7d722f) | Feb 07, 2023 |
| Dell          | 0T568R A00                  | [b4cafb34f7](https://linux-hardware.org/?probe=b4cafb34f7) | Feb 07, 2023 |
| Dell          | 0HHV7N A00                  | [e67a1c86b7](https://linux-hardware.org/?probe=e67a1c86b7) | Feb 07, 2023 |
| Dell          | 0HD5W2 A01                  | [02260ca8b3](https://linux-hardware.org/?probe=02260ca8b3) | Feb 06, 2023 |
| Dell          | 06JWJY A00                  | [9745edaf8e](https://linux-hardware.org/?probe=9745edaf8e) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M LX3                | [6519e2ca2f](https://linux-hardware.org/?probe=6519e2ca2f) | Feb 06, 2023 |
| Dell          | 0TTDMJ A00                  | [0bd327136a](https://linux-hardware.org/?probe=0bd327136a) | Feb 06, 2023 |
| MSI           | PRO H610M-B DDR4            | [6217fdc070](https://linux-hardware.org/?probe=6217fdc070) | Feb 06, 2023 |
| HP            | 0A64h                       | [40ef639345](https://linux-hardware.org/?probe=40ef639345) | Feb 05, 2023 |
| Dell          | 0TTDMJ A00                  | [6dd8a1b58a](https://linux-hardware.org/?probe=6dd8a1b58a) | Feb 05, 2023 |
| MSI           | B250M PRO-VDH               | [b8675ca2ee](https://linux-hardware.org/?probe=b8675ca2ee) | Feb 05, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [bc0593280c](https://linux-hardware.org/?probe=bc0593280c) | Feb 05, 2023 |
| ASUSTek       | H87M-PLUS                   | [99dc5ad30d](https://linux-hardware.org/?probe=99dc5ad30d) | Feb 05, 2023 |
| ASUSTek       | P5V-VM DH                   | [9d090675b1](https://linux-hardware.org/?probe=9d090675b1) | Feb 05, 2023 |
| ASUSTek       | B75M-PLUS                   | [d2981f72e6](https://linux-hardware.org/?probe=d2981f72e6) | Feb 05, 2023 |
| MSI           | A320M PRO-M2                | [3fa2ac81f2](https://linux-hardware.org/?probe=3fa2ac81f2) | Feb 05, 2023 |
| HP            | 3396                        | [96a3376aa0](https://linux-hardware.org/?probe=96a3376aa0) | Feb 05, 2023 |
| Dell          | 0D4MD1 A00                  | [7198c3d131](https://linux-hardware.org/?probe=7198c3d131) | Feb 05, 2023 |
| ASUSTek       | Basswood                    | [7de223a121](https://linux-hardware.org/?probe=7de223a121) | Feb 04, 2023 |
| HP            | 1589                        | [7b3a0cf51b](https://linux-hardware.org/?probe=7b3a0cf51b) | Feb 04, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [e12e1d2598](https://linux-hardware.org/?probe=e12e1d2598) | Feb 04, 2023 |
| ASUSTek       | PRIME X570-P                | [a8dcc6b4c1](https://linux-hardware.org/?probe=a8dcc6b4c1) | Feb 03, 2023 |
| Intel         | D33217GKE G76540-203        | [0f43f169d1](https://linux-hardware.org/?probe=0f43f169d1) | Feb 03, 2023 |
| ASUSTek       | P8P67 PRO                   | [49d8a19239](https://linux-hardware.org/?probe=49d8a19239) | Feb 03, 2023 |
| Dell          | 05WNJ2 A02                  | [4619f572c5](https://linux-hardware.org/?probe=4619f572c5) | Feb 03, 2023 |
| ASRock        | FM2A88X Extreme4+           | [9f812fe2a7](https://linux-hardware.org/?probe=9f812fe2a7) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [795ee67158](https://linux-hardware.org/?probe=795ee67158) | Feb 02, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [1fddf279a5](https://linux-hardware.org/?probe=1fddf279a5) | Feb 02, 2023 |
| MSI           | H110M PRO-VD                | [b35d6e3a08](https://linux-hardware.org/?probe=b35d6e3a08) | Feb 02, 2023 |
| MSI           | H110M PRO-VD                | [cc717bffbe](https://linux-hardware.org/?probe=cc717bffbe) | Feb 02, 2023 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | [203e3fe693](https://linux-hardware.org/?probe=203e3fe693) | Feb 01, 2023 |
| ASUSTek       | K8N-DL                      | [dde5c844f2](https://linux-hardware.org/?probe=dde5c844f2) | Feb 01, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [4644d239d7](https://linux-hardware.org/?probe=4644d239d7) | Feb 01, 2023 |
| MSI           | A520M-A PRO                 | [f7a88d0dea](https://linux-hardware.org/?probe=f7a88d0dea) | Feb 01, 2023 |
| ASRock        | X570 Pro4                   | [81b19ff917](https://linux-hardware.org/?probe=81b19ff917) | Feb 01, 2023 |
| Dell          | 0XHGV1 A00                  | [05a6fd1857](https://linux-hardware.org/?probe=05a6fd1857) | Jan 31, 2023 |
| ASUSTek       | Z97-PRO GAMER               | [9ce51b923e](https://linux-hardware.org/?probe=9ce51b923e) | Jan 31, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [01c7dbecde](https://linux-hardware.org/?probe=01c7dbecde) | Jan 31, 2023 |
| ASRock        | X570 Pro4                   | [37999411ed](https://linux-hardware.org/?probe=37999411ed) | Jan 31, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [32dfb5ebe2](https://linux-hardware.org/?probe=32dfb5ebe2) | Jan 31, 2023 |
| Dell          | 0TP412                      | [5db177340d](https://linux-hardware.org/?probe=5db177340d) | Jan 30, 2023 |
| MSI           | 970 GAMING                  | [7bc39da7c1](https://linux-hardware.org/?probe=7bc39da7c1) | Jan 30, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | [529b411b46](https://linux-hardware.org/?probe=529b411b46) | Jan 30, 2023 |
| ASUSTek       | E3 PRO GAMING V5            | [b7917146d8](https://linux-hardware.org/?probe=b7917146d8) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | [7983249b4c](https://linux-hardware.org/?probe=7983249b4c) | Jan 30, 2023 |
| HP            | 0A64h                       | [da7b36ad47](https://linux-hardware.org/?probe=da7b36ad47) | Jan 30, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [4fb612b680](https://linux-hardware.org/?probe=4fb612b680) | Jan 29, 2023 |
| MSI           | MPG B550I GAMING EDGE MA... | [ff186606cd](https://linux-hardware.org/?probe=ff186606cd) | Jan 29, 2023 |
| Gigabyte      | Z170XP-SLI-CF               | [b9a38b7494](https://linux-hardware.org/?probe=b9a38b7494) | Jan 29, 2023 |
| Dell          | 0F8098                      | [d6066c739e](https://linux-hardware.org/?probe=d6066c739e) | Jan 28, 2023 |
| ASUSTek       | Z97-K                       | [e3f865cd20](https://linux-hardware.org/?probe=e3f865cd20) | Jan 28, 2023 |
| ASUSTek       | Pro WS X570-ACE             | [6e55ab69b8](https://linux-hardware.org/?probe=6e55ab69b8) | Jan 28, 2023 |
| Lenovo        | NO DPK                      | [0abc762f30](https://linux-hardware.org/?probe=0abc762f30) | Jan 28, 2023 |
| Gigabyte      | B660M GAMING DDR4           | [c7fc79b5f1](https://linux-hardware.org/?probe=c7fc79b5f1) | Jan 28, 2023 |
| MSI           | H410M PRO                   | [d8c1dc4e25](https://linux-hardware.org/?probe=d8c1dc4e25) | Jan 28, 2023 |
| MSI           | H410M PRO                   | [72f5a735fb](https://linux-hardware.org/?probe=72f5a735fb) | Jan 28, 2023 |
| Medion        | H61H2-LM3                   | [e9d671848c](https://linux-hardware.org/?probe=e9d671848c) | Jan 27, 2023 |
| Acer          | Aspire X1700                | [beab94f1ee](https://linux-hardware.org/?probe=beab94f1ee) | Jan 27, 2023 |
| Gigabyte      | H310M S2H                   | [6aa78b855a](https://linux-hardware.org/?probe=6aa78b855a) | Jan 27, 2023 |
| Gigabyte      | Z87-D3HP-CF                 | [812c00440c](https://linux-hardware.org/?probe=812c00440c) | Jan 26, 2023 |
| HP            | 805D                        | [b1996094a9](https://linux-hardware.org/?probe=b1996094a9) | Jan 26, 2023 |
| ASUSTek       | PRIME X370-A                | [b1371b8883](https://linux-hardware.org/?probe=b1371b8883) | Jan 26, 2023 |
| Gigabyte      | EX38-DS4                    | [4d5b828cfc](https://linux-hardware.org/?probe=4d5b828cfc) | Jan 25, 2023 |
| HP            | 1495                        | [d600418bf6](https://linux-hardware.org/?probe=d600418bf6) | Jan 25, 2023 |
| MSI           | MS-7032                     | [7b481f4c8c](https://linux-hardware.org/?probe=7b481f4c8c) | Jan 25, 2023 |
| Intel         | B75                         | [20853a8c8d](https://linux-hardware.org/?probe=20853a8c8d) | Jan 25, 2023 |
| MSI           | H110M GAMING                | [2622dcb32e](https://linux-hardware.org/?probe=2622dcb32e) | Jan 25, 2023 |
| Dell          | 0NK5PH A00                  | [fc7e90e419](https://linux-hardware.org/?probe=fc7e90e419) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [026efbc485](https://linux-hardware.org/?probe=026efbc485) | Jan 25, 2023 |
| Gigabyte      | B550 AORUS ELITE AX         | [184de230c5](https://linux-hardware.org/?probe=184de230c5) | Jan 25, 2023 |
| MSI           | B350M MORTAR                | [1c843535db](https://linux-hardware.org/?probe=1c843535db) | Jan 24, 2023 |
| ASUSTek       | PRIME B450M-A               | [da95f58140](https://linux-hardware.org/?probe=da95f58140) | Jan 23, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | [8b280b4152](https://linux-hardware.org/?probe=8b280b4152) | Jan 23, 2023 |
| Dell          | 0NNNCT A01                  | [b80dda96de](https://linux-hardware.org/?probe=b80dda96de) | Jan 23, 2023 |
| MSI           | MS-7388                     | [4d5146a81f](https://linux-hardware.org/?probe=4d5146a81f) | Jan 22, 2023 |
| MSI           | H81M-E34                    | [c11041ba13](https://linux-hardware.org/?probe=c11041ba13) | Jan 22, 2023 |
| ASUSTek       | Z97-K                       | [1261e08a8a](https://linux-hardware.org/?probe=1261e08a8a) | Jan 22, 2023 |
| Shenzhen M... | F6BFC                       | [21f62b0eac](https://linux-hardware.org/?probe=21f62b0eac) | Jan 21, 2023 |
| Lenovo        | 30C0 SDK0J40697 WIN 3305... | [f6f1f5e32b](https://linux-hardware.org/?probe=f6f1f5e32b) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming B560M-E          | [0bbafaf9fe](https://linux-hardware.org/?probe=0bbafaf9fe) | Jan 21, 2023 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [0f3a750cdc](https://linux-hardware.org/?probe=0f3a750cdc) | Jan 21, 2023 |
| ASRock        | B550M Pro4                  | [22b030cc5c](https://linux-hardware.org/?probe=22b030cc5c) | Jan 21, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [69bf20ee28](https://linux-hardware.org/?probe=69bf20ee28) | Jan 21, 2023 |
| MSI           | Z490-A PRO                  | [0a3fe4cb00](https://linux-hardware.org/?probe=0a3fe4cb00) | Jan 21, 2023 |
| Gigabyte      | B150M-D2V DDR3-CF           | [dfd88e113a](https://linux-hardware.org/?probe=dfd88e113a) | Jan 21, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [7a067fe264](https://linux-hardware.org/?probe=7a067fe264) | Jan 21, 2023 |
| Gigabyte      | B550 GAMING X V2            | [f1d22db1d7](https://linux-hardware.org/?probe=f1d22db1d7) | Jan 21, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [6134837cfe](https://linux-hardware.org/?probe=6134837cfe) | Jan 21, 2023 |
| ASUSTek       | P5QL PRO                    | [9f700f7e19](https://linux-hardware.org/?probe=9f700f7e19) | Jan 21, 2023 |
| ASUSTek       | PRIME B450-PLUS             | [e3525b1f86](https://linux-hardware.org/?probe=e3525b1f86) | Jan 21, 2023 |
| ASUSTek       | P8Z68-V LX                  | [49f0bb23ea](https://linux-hardware.org/?probe=49f0bb23ea) | Jan 20, 2023 |
| ASRock        | A520M-HDVP/DASH             | [72421e0506](https://linux-hardware.org/?probe=72421e0506) | Jan 20, 2023 |
| Gigabyte      | Z590 UD AC                  | [91dea34a76](https://linux-hardware.org/?probe=91dea34a76) | Jan 20, 2023 |
| Dell          | 0KJCC5 A00                  | [08502cda27](https://linux-hardware.org/?probe=08502cda27) | Jan 20, 2023 |
| Lenovo        | 3642 SDK0J40700 WIN 3258... | [bb1826bf63](https://linux-hardware.org/?probe=bb1826bf63) | Jan 20, 2023 |
| Gigabyte      | M61PME-S2                   | [110d9cb0f9](https://linux-hardware.org/?probe=110d9cb0f9) | Jan 20, 2023 |
| Gigabyte      | H310M S2H                   | [57a7b7d914](https://linux-hardware.org/?probe=57a7b7d914) | Jan 20, 2023 |
| Lenovo        | 7033EW4                     | [fd4303de2e](https://linux-hardware.org/?probe=fd4303de2e) | Jan 20, 2023 |
| ASUSTek       | PRIME B365M-A               | [c08f2e5961](https://linux-hardware.org/?probe=c08f2e5961) | Jan 19, 2023 |
| ASUSTek       | PRIME B350M-A               | [6f50700657](https://linux-hardware.org/?probe=6f50700657) | Jan 19, 2023 |
| MSI           | H110M PRO-VD                | [e000402b1c](https://linux-hardware.org/?probe=e000402b1c) | Jan 19, 2023 |
| MSI           | H110M PRO-VD                | [79e6461b99](https://linux-hardware.org/?probe=79e6461b99) | Jan 19, 2023 |
| MSI           | X570-A PRO                  | [9c0b3ef63b](https://linux-hardware.org/?probe=9c0b3ef63b) | Jan 19, 2023 |
| ASUSTek       | PRIME B250M-A               | [d2ecbd7302](https://linux-hardware.org/?probe=d2ecbd7302) | Jan 18, 2023 |
| ASUSTek       | PRIME Z270-A                | [8e511beda6](https://linux-hardware.org/?probe=8e511beda6) | Jan 18, 2023 |
| Lenovo        | 7033EW4                     | [df0d8cd728](https://linux-hardware.org/?probe=df0d8cd728) | Jan 18, 2023 |
| Gigabyte      | H77-D3H                     | [15da5de3ae](https://linux-hardware.org/?probe=15da5de3ae) | Jan 18, 2023 |
| Lenovo        | 314F SDK0J40697 WIN 3305... | [f7efc3545d](https://linux-hardware.org/?probe=f7efc3545d) | Jan 18, 2023 |
| MSI           | H310M PRO-M2                | [6bdc0bc1c7](https://linux-hardware.org/?probe=6bdc0bc1c7) | Jan 17, 2023 |
| ASUSTek       | PRIME Z270-A                | [ad9172f4a9](https://linux-hardware.org/?probe=ad9172f4a9) | Jan 17, 2023 |
| MSI           | A320M-A PRO MAX             | [5a0f8a7ea6](https://linux-hardware.org/?probe=5a0f8a7ea6) | Jan 17, 2023 |
| Gigabyte      | Z170-HD3P-CF                | [851c4f03fc](https://linux-hardware.org/?probe=851c4f03fc) | Jan 17, 2023 |
| Fujitsu       | D3230-A1 S26361-D3230-A1    | [6c3aa30aa8](https://linux-hardware.org/?probe=6c3aa30aa8) | Jan 17, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | [41839ed038](https://linux-hardware.org/?probe=41839ed038) | Jan 17, 2023 |
| Dell          | 01D4TT A00                  | [509404e50f](https://linux-hardware.org/?probe=509404e50f) | Jan 17, 2023 |
| Dell          | 0HHV7N A00                  | [8e4a061e95](https://linux-hardware.org/?probe=8e4a061e95) | Jan 16, 2023 |
| Lenovo        | 3102 SDK0K13476 WIN 3306... | [fd843f48f5](https://linux-hardware.org/?probe=fd843f48f5) | Jan 16, 2023 |
| ASUSTek       | PRIME Z270-A                | [8bdec78777](https://linux-hardware.org/?probe=8bdec78777) | Jan 16, 2023 |
| MSI           | H61M-P20                    | [bf79928a7a](https://linux-hardware.org/?probe=bf79928a7a) | Jan 16, 2023 |
| ASRock        | FM2A88X+ Killer             | [ce91a77f1c](https://linux-hardware.org/?probe=ce91a77f1c) | Jan 16, 2023 |
| MSI           | B450 TOMAHAWK MAX           | [3b4a530695](https://linux-hardware.org/?probe=3b4a530695) | Jan 15, 2023 |
| MSI           | MAG B560M MORTAR            | [45da89106d](https://linux-hardware.org/?probe=45da89106d) | Jan 15, 2023 |
| Dell          | 0M863N A01                  | [4d7e5c21fc](https://linux-hardware.org/?probe=4d7e5c21fc) | Jan 15, 2023 |
| Gigabyte      | B550M AORUS PRO             | [0b375cb78b](https://linux-hardware.org/?probe=0b375cb78b) | Jan 14, 2023 |
| Gigabyte      | H55M-UD2H                   | [a14f62fa30](https://linux-hardware.org/?probe=a14f62fa30) | Jan 14, 2023 |
| ASUSTek       | PRIME X570-P                | [32026c5c05](https://linux-hardware.org/?probe=32026c5c05) | Jan 14, 2023 |
| Lenovo        | 30D2 SDK0J40697 WIN 3305... | [67d3d3c57a](https://linux-hardware.org/?probe=67d3d3c57a) | Jan 14, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [9774dee993](https://linux-hardware.org/?probe=9774dee993) | Jan 14, 2023 |
| Gigabyte      | Z77-D3H                     | [d09a603b10](https://linux-hardware.org/?probe=d09a603b10) | Jan 14, 2023 |
| HP            | 8054                        | [faf1c97cea](https://linux-hardware.org/?probe=faf1c97cea) | Jan 14, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [1a25eeba6f](https://linux-hardware.org/?probe=1a25eeba6f) | Jan 14, 2023 |
| Gigabyte      | H310M S2H                   | [04381152c2](https://linux-hardware.org/?probe=04381152c2) | Jan 14, 2023 |
| Gigabyte      | H310M S2H                   | [a153e6f458](https://linux-hardware.org/?probe=a153e6f458) | Jan 14, 2023 |
| ASUSTek       | TUF B450-PLUS GAMING        | [ed18454667](https://linux-hardware.org/?probe=ed18454667) | Jan 14, 2023 |
| Gigabyte      | B550M DS3H                  | [5de8333ea3](https://linux-hardware.org/?probe=5de8333ea3) | Jan 14, 2023 |
| Dell          | 0M5DCD A00                  | [f6e2ab2124](https://linux-hardware.org/?probe=f6e2ab2124) | Jan 13, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [a399f30ea9](https://linux-hardware.org/?probe=a399f30ea9) | Jan 13, 2023 |
| Dell          | 0M5DCD A00                  | [83bed4df76](https://linux-hardware.org/?probe=83bed4df76) | Jan 13, 2023 |
| HC            | HCAR357-MI V1.0             | [516f1ed052](https://linux-hardware.org/?probe=516f1ed052) | Jan 13, 2023 |
| ASUSTek       | P8Z77-V LK                  | [f954b55a5c](https://linux-hardware.org/?probe=f954b55a5c) | Jan 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [c331071e8a](https://linux-hardware.org/?probe=c331071e8a) | Jan 13, 2023 |
| ASUSTek       | H110S2                      | [d783389831](https://linux-hardware.org/?probe=d783389831) | Jan 13, 2023 |
| Gigabyte      | H310M S2H                   | [9aec47cbf0](https://linux-hardware.org/?probe=9aec47cbf0) | Jan 12, 2023 |
| HP            | 21EF                        | [0d5e3a9354](https://linux-hardware.org/?probe=0d5e3a9354) | Jan 12, 2023 |
| Gigabyte      | H310M S2H                   | [b3cccc4043](https://linux-hardware.org/?probe=b3cccc4043) | Jan 12, 2023 |
| HP            | 21EF                        | [cdeab03273](https://linux-hardware.org/?probe=cdeab03273) | Jan 12, 2023 |
| Intel         | DN2800MT AAG81515-900       | [546f31d89f](https://linux-hardware.org/?probe=546f31d89f) | Jan 12, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | [4687ae7d43](https://linux-hardware.org/?probe=4687ae7d43) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [190d9b58b8](https://linux-hardware.org/?probe=190d9b58b8) | Jan 12, 2023 |
| ASUSTek       | P8H77-M PRO                 | [24461e4b9f](https://linux-hardware.org/?probe=24461e4b9f) | Jan 12, 2023 |
| ASRock        | ION3D-HT                    | [48707e3794](https://linux-hardware.org/?probe=48707e3794) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z370-G GAMING     | [d92a983612](https://linux-hardware.org/?probe=d92a983612) | Jan 12, 2023 |
| ASUSTek       | M5A78L LE                   | [ea76077171](https://linux-hardware.org/?probe=ea76077171) | Jan 11, 2023 |
| Intel         | DQ77KB AAG81483-500         | [0e8844064e](https://linux-hardware.org/?probe=0e8844064e) | Jan 11, 2023 |
| Intel         | JSL MRD                     | [d1b9dbaae0](https://linux-hardware.org/?probe=d1b9dbaae0) | Jan 11, 2023 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [ff44388b68](https://linux-hardware.org/?probe=ff44388b68) | Jan 11, 2023 |
| Dell          | 0M5DCD A00                  | [4f6e8d1ac5](https://linux-hardware.org/?probe=4f6e8d1ac5) | Jan 10, 2023 |
| ASUSTek       | PRIME Z390M-PLUS            | [b0475049e8](https://linux-hardware.org/?probe=b0475049e8) | Jan 10, 2023 |
| ASUSTek       | M5A78L LE                   | [0b9c1c2841](https://linux-hardware.org/?probe=0b9c1c2841) | Jan 09, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [1f77d36501](https://linux-hardware.org/?probe=1f77d36501) | Jan 09, 2023 |
| Gigabyte      | B560I AORUS PRO AX          | [bd760b375b](https://linux-hardware.org/?probe=bd760b375b) | Jan 09, 2023 |
| ASUSTek       | Z97M-PLUS                   | [6746287398](https://linux-hardware.org/?probe=6746287398) | Jan 09, 2023 |
| HP            | 802F                        | [1dd3655605](https://linux-hardware.org/?probe=1dd3655605) | Jan 09, 2023 |
| Gigabyte      | B550 GAMING X V2            | [e64cca399f](https://linux-hardware.org/?probe=e64cca399f) | Jan 09, 2023 |
| Gigabyte      | Z77-D3H                     | [8d02a61d53](https://linux-hardware.org/?probe=8d02a61d53) | Jan 09, 2023 |
| HP            | 0A98h                       | [a26fc3d5f4](https://linux-hardware.org/?probe=a26fc3d5f4) | Jan 08, 2023 |
| MSI           | B450M MORTAR MAX            | [474907a53e](https://linux-hardware.org/?probe=474907a53e) | Jan 08, 2023 |
| Lenovo        | MAHOBAY NO DPK              | [df436102d6](https://linux-hardware.org/?probe=df436102d6) | Jan 08, 2023 |
| MSI           | 990XA-GD55                  | [b4525a8431](https://linux-hardware.org/?probe=b4525a8431) | Jan 08, 2023 |
| Gigabyte      | B550M DS3H                  | [faf4eff378](https://linux-hardware.org/?probe=faf4eff378) | Jan 08, 2023 |
| MSI           | MPG B550 GAMING PLUS        | [a763320a37](https://linux-hardware.org/?probe=a763320a37) | Jan 08, 2023 |
| ASUSTek       | P8Z68-V LX                  | [f090331efa](https://linux-hardware.org/?probe=f090331efa) | Jan 07, 2023 |
| ASUSTek       | P7P55D                      | [d6f1a60435](https://linux-hardware.org/?probe=d6f1a60435) | Jan 07, 2023 |
| Gigabyte      | H310M S2H                   | [1530f96142](https://linux-hardware.org/?probe=1530f96142) | Jan 07, 2023 |
| Pegatron      | Eureka3                     | [c3aacdc606](https://linux-hardware.org/?probe=c3aacdc606) | Jan 07, 2023 |
| MSI           | PRO B660M-B DDR4            | [cceab9ef33](https://linux-hardware.org/?probe=cceab9ef33) | Jan 07, 2023 |
| Dell          | 04MFRM A02                  | [7b29154637](https://linux-hardware.org/?probe=7b29154637) | Jan 07, 2023 |
| Dell          | 042P49 A00                  | [91c410b89a](https://linux-hardware.org/?probe=91c410b89a) | Jan 07, 2023 |
| ASRock        | X470 Master SLI             | [c138f9159c](https://linux-hardware.org/?probe=c138f9159c) | Jan 07, 2023 |
| Acer          | Aspire XC-885 V:1.1         | [3a51845b72](https://linux-hardware.org/?probe=3a51845b72) | Jan 07, 2023 |
| ASUSTek       | M5A99X EVO                  | [d4111f62a5](https://linux-hardware.org/?probe=d4111f62a5) | Jan 07, 2023 |
| MSI           | H510M-A PRO                 | [38bc046bdd](https://linux-hardware.org/?probe=38bc046bdd) | Jan 07, 2023 |
| Gigabyte      | B450 AORUS ELITE V2         | [7fd8978322](https://linux-hardware.org/?probe=7fd8978322) | Jan 06, 2023 |
| ASRock        | H370M Pro4                  | [69d73f2269](https://linux-hardware.org/?probe=69d73f2269) | Jan 06, 2023 |
| MSI           | MEG Z490 UNIFY              | [cb25b352e0](https://linux-hardware.org/?probe=cb25b352e0) | Jan 06, 2023 |
| Gigabyte      | Z87X-D3H-CF                 | [a4b5bc192d](https://linux-hardware.org/?probe=a4b5bc192d) | Jan 06, 2023 |
| ASRock        | FM2A78 Pro4+                | [a2038e788c](https://linux-hardware.org/?probe=a2038e788c) | Jan 05, 2023 |
| HP            | 3397                        | [ef794d730d](https://linux-hardware.org/?probe=ef794d730d) | Jan 05, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [0ae0a8d91b](https://linux-hardware.org/?probe=0ae0a8d91b) | Jan 05, 2023 |
| ASUSTek       | G20AJ                       | [9be7e0b11f](https://linux-hardware.org/?probe=9be7e0b11f) | Jan 05, 2023 |
| HP            | 8055                        | [5f51faab6e](https://linux-hardware.org/?probe=5f51faab6e) | Jan 05, 2023 |
| Dell          | 0XHGV1 A00                  | [84b31ee7de](https://linux-hardware.org/?probe=84b31ee7de) | Jan 05, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [03f117a662](https://linux-hardware.org/?probe=03f117a662) | Jan 05, 2023 |
| MSI           | MPG Z390 GAMING EDGE AC     | [4ff5066793](https://linux-hardware.org/?probe=4ff5066793) | Jan 05, 2023 |
| Dell          | 0TP412                      | [b608bcbdcf](https://linux-hardware.org/?probe=b608bcbdcf) | Jan 04, 2023 |
| MSI           | 970 GAMING                  | [7931ef67b2](https://linux-hardware.org/?probe=7931ef67b2) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | [113e1b51b7](https://linux-hardware.org/?probe=113e1b51b7) | Jan 04, 2023 |
| Dell          | 042P49 A00                  | [192e7fac1d](https://linux-hardware.org/?probe=192e7fac1d) | Jan 03, 2023 |
| ASUSTek       | PRIME B560M-A               | [f560abfd7f](https://linux-hardware.org/?probe=f560abfd7f) | Jan 03, 2023 |
| ASUSTek       | Berkeley                    | [746d7be693](https://linux-hardware.org/?probe=746d7be693) | Jan 03, 2023 |
| HP            | 339A                        | [c35711cb53](https://linux-hardware.org/?probe=c35711cb53) | Jan 03, 2023 |
| HP            | 339A                        | [2a4cb6de27](https://linux-hardware.org/?probe=2a4cb6de27) | Jan 03, 2023 |
| ASUSTek       | ROG STRIX Z690-G GAMING ... | [7c98c0b00d](https://linux-hardware.org/?probe=7c98c0b00d) | Jan 02, 2023 |
| MSI           | 970 GAMING                  | [1fa699405c](https://linux-hardware.org/?probe=1fa699405c) | Jan 02, 2023 |
| Dell          | 0WMJ54 A01                  | [c6feaa89a0](https://linux-hardware.org/?probe=c6feaa89a0) | Jan 01, 2023 |
| Lenovo        | SHARKBAY NOK                | [7c72451666](https://linux-hardware.org/?probe=7c72451666) | Jan 01, 2023 |
| Gigabyte      | B365 HD3                    | [195240c264](https://linux-hardware.org/?probe=195240c264) | Jan 01, 2023 |
| Foxconn       | 2ACA                        | [505262a4b1](https://linux-hardware.org/?probe=505262a4b1) | Jan 01, 2023 |
| ASUSTek       | PRIME B250M-K               | [9db6f0fda7](https://linux-hardware.org/?probe=9db6f0fda7) | Dec 31, 2022 |
| ASRock        | B550 Steel Legend           | [8705e10ac6](https://linux-hardware.org/?probe=8705e10ac6) | Dec 31, 2022 |
| Gigabyte      | GA-78LMT-USB3               | [6de26a316e](https://linux-hardware.org/?probe=6de26a316e) | Dec 30, 2022 |
| MSI           | H61M-P22                    | [23b5356c0a](https://linux-hardware.org/?probe=23b5356c0a) | Dec 30, 2022 |
| ASRock        | 960GM-GS3 FX                | [1d8b5f0509](https://linux-hardware.org/?probe=1d8b5f0509) | Dec 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | [0842d26251](https://linux-hardware.org/?probe=0842d26251) | Dec 30, 2022 |
| ASUSTek       | PRIME B450M-A II            | [d91b55f9f1](https://linux-hardware.org/?probe=d91b55f9f1) | Dec 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | [47f838ca34](https://linux-hardware.org/?probe=47f838ca34) | Dec 30, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [6cf8d26754](https://linux-hardware.org/?probe=6cf8d26754) | Dec 30, 2022 |
| Acer          | Aspire X3960                | [f045d61192](https://linux-hardware.org/?probe=f045d61192) | Dec 29, 2022 |
| Acer          | Aspire X3960                | [75e053c90f](https://linux-hardware.org/?probe=75e053c90f) | Dec 29, 2022 |
| Dell          | 0T10XW A01                  | [8b16a66b73](https://linux-hardware.org/?probe=8b16a66b73) | Dec 29, 2022 |
| ASRock        | H61M-ITX                    | [0ee8e9bb5b](https://linux-hardware.org/?probe=0ee8e9bb5b) | Dec 28, 2022 |
| Dell          | 0YXT71 A01                  | [ed5e31a6bc](https://linux-hardware.org/?probe=ed5e31a6bc) | Dec 28, 2022 |
| ASUSTek       | PRIME B360M-K               | [48f161dfc8](https://linux-hardware.org/?probe=48f161dfc8) | Dec 27, 2022 |
| MSI           | MPG Z390 GAMING EDGE AC     | [31f25029c1](https://linux-hardware.org/?probe=31f25029c1) | Dec 27, 2022 |
| Gigabyte      | 970-GAMING                  | [4a2d0b56d6](https://linux-hardware.org/?probe=4a2d0b56d6) | Dec 27, 2022 |
| Gigabyte      | Z690 AORUS MASTER           | [ebf2a443c2](https://linux-hardware.org/?probe=ebf2a443c2) | Dec 26, 2022 |
| Acer          | Veriton NBU                 | [cca454d1bd](https://linux-hardware.org/?probe=cca454d1bd) | Dec 26, 2022 |
| Gigabyte      | 970-GAMING                  | [9df04c213d](https://linux-hardware.org/?probe=9df04c213d) | Dec 26, 2022 |
| HP            | 2AF7                        | [96344d97ba](https://linux-hardware.org/?probe=96344d97ba) | Dec 26, 2022 |
| Dell          | 0MN1TX A02                  | [513af674c0](https://linux-hardware.org/?probe=513af674c0) | Dec 25, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [d66772a936](https://linux-hardware.org/?probe=d66772a936) | Dec 25, 2022 |
| ASUSTek       | PRIME A320M-K               | [1762f53462](https://linux-hardware.org/?probe=1762f53462) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | [ef0c06d132](https://linux-hardware.org/?probe=ef0c06d132) | Dec 25, 2022 |
| Gigabyte      | 970-GAMING                  | [9de3d146ff](https://linux-hardware.org/?probe=9de3d146ff) | Dec 25, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8df9791e32](https://linux-hardware.org/?probe=8df9791e32) | Dec 24, 2022 |
| Dell          | 0J3C2F A00                  | [f993ebb9ed](https://linux-hardware.org/?probe=f993ebb9ed) | Dec 23, 2022 |
| ASRock        | H270 Pro4                   | [548ba72d05](https://linux-hardware.org/?probe=548ba72d05) | Dec 23, 2022 |
| ASRock        | A320M-HDV R4.0              | [41ec48c0e5](https://linux-hardware.org/?probe=41ec48c0e5) | Dec 23, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | [841b610817](https://linux-hardware.org/?probe=841b610817) | Dec 23, 2022 |
| ASUSTek       | PRIME B450M-A               | [360e473cf9](https://linux-hardware.org/?probe=360e473cf9) | Dec 22, 2022 |
| Dell          | 0YJPT1 A00                  | [f78b9b1a90](https://linux-hardware.org/?probe=f78b9b1a90) | Dec 22, 2022 |
| Acer          | Predator PO3-600 V:1.1      | [4a49555de6](https://linux-hardware.org/?probe=4a49555de6) | Dec 22, 2022 |
| Acer          | Predator PO3-600 V:1.1      | [8cb7f41543](https://linux-hardware.org/?probe=8cb7f41543) | Dec 22, 2022 |
| Gigabyte      | Z490I AORUS ULTRA           | [de140c1edd](https://linux-hardware.org/?probe=de140c1edd) | Dec 22, 2022 |
| HP            | 81C9                        | [cb40ddba01](https://linux-hardware.org/?probe=cb40ddba01) | Dec 22, 2022 |
| Dell          | 0T10XW A02                  | [f39488c597](https://linux-hardware.org/?probe=f39488c597) | Dec 21, 2022 |
| MSI           | H97M-G43                    | [a34bd69442](https://linux-hardware.org/?probe=a34bd69442) | Dec 21, 2022 |
| Dell          | 0T10XW A02                  | [0243df6ce4](https://linux-hardware.org/?probe=0243df6ce4) | Dec 21, 2022 |
| Acer          | ERC410M                     | [e25233896a](https://linux-hardware.org/?probe=e25233896a) | Dec 21, 2022 |
| Gigabyte      | H170M-DS3H-CF               | [714dafad38](https://linux-hardware.org/?probe=714dafad38) | Dec 21, 2022 |
| MSI           | MAG B560M MORTAR            | [9b1e668d0a](https://linux-hardware.org/?probe=9b1e668d0a) | Dec 21, 2022 |
| HP            | ProLiant MicroServer Gen... | [57182d09ed](https://linux-hardware.org/?probe=57182d09ed) | Dec 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | [827c7f9bd3](https://linux-hardware.org/?probe=827c7f9bd3) | Dec 21, 2022 |
| Gigabyte      | H61M-USB3V                  | [3161a64c4b](https://linux-hardware.org/?probe=3161a64c4b) | Dec 19, 2022 |
| MSI           | MPG B550I GAMING EDGE WI... | [1e7aff6742](https://linux-hardware.org/?probe=1e7aff6742) | Dec 19, 2022 |
| Lenovo        | ThinkCentre M70E 0830W4E    | [199c8776ef](https://linux-hardware.org/?probe=199c8776ef) | Dec 18, 2022 |
| MSI           | Z87M GAMING                 | [bf27014217](https://linux-hardware.org/?probe=bf27014217) | Dec 18, 2022 |
| Gigabyte      | H310M S2H                   | [ed996739df](https://linux-hardware.org/?probe=ed996739df) | Dec 18, 2022 |
| Packard Be... | PT890-8237A                 | [bb9e8d2cd7](https://linux-hardware.org/?probe=bb9e8d2cd7) | Dec 17, 2022 |
| Gigabyte      | F2A55M-DS2                  | [a38c2f49be](https://linux-hardware.org/?probe=a38c2f49be) | Dec 17, 2022 |
| MSI           | X370 GAMING PLUS            | [893af38c43](https://linux-hardware.org/?probe=893af38c43) | Dec 16, 2022 |
| Dell          | 0M5DCD A00                  | [f58cc5bcba](https://linux-hardware.org/?probe=f58cc5bcba) | Dec 16, 2022 |
| Gigabyte      | H310M S2H                   | [2c008886c6](https://linux-hardware.org/?probe=2c008886c6) | Dec 16, 2022 |
| ZOTAC         | ION                         | [f02f6b8382](https://linux-hardware.org/?probe=f02f6b8382) | Dec 15, 2022 |
| Lenovo        | 364F SDK0J40700 WIN 3258... | [ffe60f958c](https://linux-hardware.org/?probe=ffe60f958c) | Dec 15, 2022 |
| ASRock        | FM2A78 Pro4+                | [51ea57e65f](https://linux-hardware.org/?probe=51ea57e65f) | Dec 15, 2022 |
| HP            | 2AFB                        | [4c57ea0ee7](https://linux-hardware.org/?probe=4c57ea0ee7) | Dec 15, 2022 |
| ASRock        | H310CM-HDV                  | [8f21b4e9c9](https://linux-hardware.org/?probe=8f21b4e9c9) | Dec 14, 2022 |
| ASRock        | H310CM-HDV                  | [b3c5f73f5a](https://linux-hardware.org/?probe=b3c5f73f5a) | Dec 14, 2022 |
| ASRock        | FM2A78 Pro4+                | [cb63c9ad7f](https://linux-hardware.org/?probe=cb63c9ad7f) | Dec 14, 2022 |
| Dell          | 0H8367                      | [7fff4bfffc](https://linux-hardware.org/?probe=7fff4bfffc) | Dec 14, 2022 |
| Gigabyte      | GA-970A-D3                  | [9bc1aec0dc](https://linux-hardware.org/?probe=9bc1aec0dc) | Dec 14, 2022 |
| Optimized ... | KVM                         | [d62625a751](https://linux-hardware.org/?probe=d62625a751) | Dec 13, 2022 |
| ASUSTek       | A88XM-A                     | [64176404e2](https://linux-hardware.org/?probe=64176404e2) | Dec 13, 2022 |
| HP            | 304Ah                       | [d8b600f39e](https://linux-hardware.org/?probe=d8b600f39e) | Dec 13, 2022 |
| Intel         | DH61AG AAG23736-505         | [352a377398](https://linux-hardware.org/?probe=352a377398) | Dec 13, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI      | [1beb5ff3c4](https://linux-hardware.org/?probe=1beb5ff3c4) | Dec 13, 2022 |
| Medion        | H61H2-LM3                   | [af98dc76b3](https://linux-hardware.org/?probe=af98dc76b3) | Dec 12, 2022 |
| Gigabyte      | H77N-WIFI                   | [9704c6b7c4](https://linux-hardware.org/?probe=9704c6b7c4) | Dec 12, 2022 |
| ASUSTek       | PRIME B350M-A               | [349781adbb](https://linux-hardware.org/?probe=349781adbb) | Dec 12, 2022 |
| Gigabyte      | B550M DS3H                  | [8370a57760](https://linux-hardware.org/?probe=8370a57760) | Dec 12, 2022 |
| ASUSTek       | PRIME B350M-A               | [25e5e8d887](https://linux-hardware.org/?probe=25e5e8d887) | Dec 11, 2022 |
| MSI           | B350 TOMAHAWK               | [0ce6563922](https://linux-hardware.org/?probe=0ce6563922) | Dec 11, 2022 |
| Dell          | 0Y5DDC A00                  | [22f4cdc5d7](https://linux-hardware.org/?probe=22f4cdc5d7) | Dec 11, 2022 |
| MSI           | H81M-E34                    | [a9cc317647](https://linux-hardware.org/?probe=a9cc317647) | Dec 11, 2022 |
| ASRock        | X79 Extreme6                | [8ef84e95c1](https://linux-hardware.org/?probe=8ef84e95c1) | Dec 11, 2022 |
| ASUSTek       | H81I-PLUS                   | [b252b33238](https://linux-hardware.org/?probe=b252b33238) | Dec 11, 2022 |
| Gigabyte      | B150M-D2V DDR3-CF           | [9d689be2ab](https://linux-hardware.org/?probe=9d689be2ab) | Dec 11, 2022 |
| AZW           | Gemini T45                  | [e0b5dab1b4](https://linux-hardware.org/?probe=e0b5dab1b4) | Dec 11, 2022 |
| AZW           | Gemini T45                  | [d169b1be26](https://linux-hardware.org/?probe=d169b1be26) | Dec 11, 2022 |
| ASUSTek       | PRIME B550M-A               | [05f65af47e](https://linux-hardware.org/?probe=05f65af47e) | Dec 10, 2022 |
| Gigabyte      | B550M DS3H                  | [6dd02812db](https://linux-hardware.org/?probe=6dd02812db) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | [5625437112](https://linux-hardware.org/?probe=5625437112) | Dec 10, 2022 |
| ASUSTek       | PRIME X570-P                | [6466139b57](https://linux-hardware.org/?probe=6466139b57) | Dec 10, 2022 |
| ASUSTek       | P8Z77-V LX                  | [363ac45af6](https://linux-hardware.org/?probe=363ac45af6) | Dec 10, 2022 |
| MSI           | H97M-G43                    | [c62f2a0b49](https://linux-hardware.org/?probe=c62f2a0b49) | Dec 10, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [a80714c4ec](https://linux-hardware.org/?probe=a80714c4ec) | Dec 09, 2022 |
| ASRock        | X570 Pro4                   | [347fc5c7ec](https://linux-hardware.org/?probe=347fc5c7ec) | Dec 09, 2022 |
| MSI           | 970 GAMING                  | [6269ce6b15](https://linux-hardware.org/?probe=6269ce6b15) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX Z370-E GAMING     | [19986ba651](https://linux-hardware.org/?probe=19986ba651) | Dec 08, 2022 |
| ASUSTek       | P8Z77-V LX                  | [1a61a83764](https://linux-hardware.org/?probe=1a61a83764) | Dec 08, 2022 |
| MSI           | 760GM-P23                   | [29337f7359](https://linux-hardware.org/?probe=29337f7359) | Dec 08, 2022 |
| HP            | 339A                        | [64e1121397](https://linux-hardware.org/?probe=64e1121397) | Dec 08, 2022 |
| ASUSTek       | F2A55                       | [a8ed6d4071](https://linux-hardware.org/?probe=a8ed6d4071) | Dec 08, 2022 |
| MSI           | H97M-G43                    | [53754acfcb](https://linux-hardware.org/?probe=53754acfcb) | Dec 08, 2022 |
| Gigabyte      | B360N WIFI-CF               | [5abfdbdcba](https://linux-hardware.org/?probe=5abfdbdcba) | Dec 07, 2022 |
| MSI           | X399 SLI PLUS               | [c97bfe2139](https://linux-hardware.org/?probe=c97bfe2139) | Dec 07, 2022 |
| AZW           | U59                         | [ba4e2d8f5d](https://linux-hardware.org/?probe=ba4e2d8f5d) | Dec 07, 2022 |
| Foxconn       | 2ABF                        | [90af9a1be5](https://linux-hardware.org/?probe=90af9a1be5) | Dec 06, 2022 |
| Fujitsu       | D3498-A1 S26361-D3498-A1    | [03cd265cef](https://linux-hardware.org/?probe=03cd265cef) | Dec 05, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [f11d4ebe40](https://linux-hardware.org/?probe=f11d4ebe40) | Dec 05, 2022 |
| Dell          | 0T10XW A00                  | [d6f876fa52](https://linux-hardware.org/?probe=d6f876fa52) | Dec 05, 2022 |
| ASUSTek       | A_F_K31AN                   | [440d9055ff](https://linux-hardware.org/?probe=440d9055ff) | Dec 05, 2022 |
| ASRock        | B450 Pro4                   | [f96de923f4](https://linux-hardware.org/?probe=f96de923f4) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | [b7b2f976e8](https://linux-hardware.org/?probe=b7b2f976e8) | Dec 05, 2022 |
| Acer          | Veriton X2631G V:1.0        | [363d58e88d](https://linux-hardware.org/?probe=363d58e88d) | Dec 05, 2022 |
| Acer          | Veriton X2631G V:1.0        | [f8607ccc53](https://linux-hardware.org/?probe=f8607ccc53) | Dec 05, 2022 |
| Dell          | 0M863N A01                  | [ee8183087b](https://linux-hardware.org/?probe=ee8183087b) | Dec 04, 2022 |
| Dell          | 0TDG4V A01                  | [1129691459](https://linux-hardware.org/?probe=1129691459) | Dec 04, 2022 |
| Unknown       | Unknown                     | [a89e9e55cb](https://linux-hardware.org/?probe=a89e9e55cb) | Dec 04, 2022 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | [db7cd6f0dc](https://linux-hardware.org/?probe=db7cd6f0dc) | Dec 04, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [1dbda8e648](https://linux-hardware.org/?probe=1dbda8e648) | Dec 04, 2022 |
| ASUSTek       | LEUCITE3                    | [4f28bb5933](https://linux-hardware.org/?probe=4f28bb5933) | Dec 04, 2022 |
| HP            | 339A                        | [91ed08d2a9](https://linux-hardware.org/?probe=91ed08d2a9) | Dec 04, 2022 |
| MSI           | MAG B560M MORTAR            | [1725274555](https://linux-hardware.org/?probe=1725274555) | Dec 03, 2022 |
| Lenovo        | SHARKBAY NOK                | [c7cf7a1604](https://linux-hardware.org/?probe=c7cf7a1604) | Dec 03, 2022 |
| Lenovo        | SHARKBAY NOK                | [67c278b32e](https://linux-hardware.org/?probe=67c278b32e) | Dec 03, 2022 |
| Gigabyte      | GA-880GM-UD2H               | [f6bb91c588](https://linux-hardware.org/?probe=f6bb91c588) | Dec 03, 2022 |
| ASUSTek       | ET1610PT                    | [d8b1840336](https://linux-hardware.org/?probe=d8b1840336) | Dec 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [6c05e05a15](https://linux-hardware.org/?probe=6c05e05a15) | Dec 03, 2022 |
| ASRock        | G41C-GS R2.0                | [87b13a5112](https://linux-hardware.org/?probe=87b13a5112) | Dec 02, 2022 |
| ASRock        | G41C-GS R2.0                | [82c0eb6155](https://linux-hardware.org/?probe=82c0eb6155) | Dec 02, 2022 |
| Acer          | Aspire XC-705               | [86a503df2a](https://linux-hardware.org/?probe=86a503df2a) | Dec 01, 2022 |
| Gigabyte      | B450M DS3H-CF               | [5e7bc65683](https://linux-hardware.org/?probe=5e7bc65683) | Dec 01, 2022 |
| ASUSTek       | A88XM-A                     | [f883ed1fd1](https://linux-hardware.org/?probe=f883ed1fd1) | Dec 01, 2022 |
| Gigabyte      | H170-HD3-CF                 | [1d293c6d72](https://linux-hardware.org/?probe=1d293c6d72) | Nov 30, 2022 |
| ASUSTek       | Z97-A                       | [da1400c491](https://linux-hardware.org/?probe=da1400c491) | Nov 30, 2022 |
| Foxconn       | 2ABF                        | [09a9309a2a](https://linux-hardware.org/?probe=09a9309a2a) | Nov 30, 2022 |
| MSI           | Z370 GAMING PLUS            | [bd1c91dba9](https://linux-hardware.org/?probe=bd1c91dba9) | Nov 30, 2022 |
| Foxconn       | 2ABF                        | [b585d891a8](https://linux-hardware.org/?probe=b585d891a8) | Nov 30, 2022 |
| ASRock        | FM2A78 Pro4+                | [7eae5fad47](https://linux-hardware.org/?probe=7eae5fad47) | Nov 29, 2022 |
| Intel         | DH67BL AAG10189-213         | [11252af398](https://linux-hardware.org/?probe=11252af398) | Nov 28, 2022 |
| Dell          | 0NK5PH A00                  | [d889c3c50a](https://linux-hardware.org/?probe=d889c3c50a) | Nov 28, 2022 |
| Dell          | 0773VG A00                  | [a21b1834c2](https://linux-hardware.org/?probe=a21b1834c2) | Nov 28, 2022 |
| Dell          | 0773VG A00                  | [04125afb72](https://linux-hardware.org/?probe=04125afb72) | Nov 28, 2022 |
| ASRock        | FM2A78 Pro4+                | [908283c378](https://linux-hardware.org/?probe=908283c378) | Nov 28, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [bc515374ae](https://linux-hardware.org/?probe=bc515374ae) | Nov 27, 2022 |
| Dell          | 05XGC8 A00                  | [e0e0efb9be](https://linux-hardware.org/?probe=e0e0efb9be) | Nov 27, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [7cb4ad7428](https://linux-hardware.org/?probe=7cb4ad7428) | Nov 27, 2022 |
| Gigabyte      | B450M DS3H-CF               | [54d005e599](https://linux-hardware.org/?probe=54d005e599) | Nov 27, 2022 |
| ASUSTek       | P7P55D-E LX                 | [8b913d5510](https://linux-hardware.org/?probe=8b913d5510) | Nov 26, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [02b1483a02](https://linux-hardware.org/?probe=02b1483a02) | Nov 26, 2022 |
| Dell          | 04MFRM A02                  | [43239e45b1](https://linux-hardware.org/?probe=43239e45b1) | Nov 26, 2022 |
| ASUSTek       | Z97-A                       | [9163dc4b5d](https://linux-hardware.org/?probe=9163dc4b5d) | Nov 26, 2022 |
| Dell          | 05XGC8 A00                  | [6ea1a60122](https://linux-hardware.org/?probe=6ea1a60122) | Nov 26, 2022 |
| ASUSTek       | P8B75-M LX PLUS             | [7948a35f59](https://linux-hardware.org/?probe=7948a35f59) | Nov 25, 2022 |
| Gigabyte      | 970A-DS3P                   | [2787600567](https://linux-hardware.org/?probe=2787600567) | Nov 25, 2022 |
| Intel         | BTC-T37                     | [f52a08ae38](https://linux-hardware.org/?probe=f52a08ae38) | Nov 25, 2022 |
| MSI           | 970 GAMING                  | [de56ed9d3f](https://linux-hardware.org/?probe=de56ed9d3f) | Nov 25, 2022 |
| Gigabyte      | G1.SNIPER B7-CF             | [c53295ce70](https://linux-hardware.org/?probe=c53295ce70) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [97ede0876f](https://linux-hardware.org/?probe=97ede0876f) | Nov 25, 2022 |
| ASUSTek       | ROG STRIX Z790-E GAMING ... | [1817579f89](https://linux-hardware.org/?probe=1817579f89) | Nov 25, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | [dad5599996](https://linux-hardware.org/?probe=dad5599996) | Nov 24, 2022 |
| HP            | 0AE8h                       | [c49d643fae](https://linux-hardware.org/?probe=c49d643fae) | Nov 24, 2022 |
| MSI           | B75A-G43                    | [7f635dae7f](https://linux-hardware.org/?probe=7f635dae7f) | Nov 24, 2022 |
| Unknown       | Unknown                     | [0904a442f0](https://linux-hardware.org/?probe=0904a442f0) | Nov 24, 2022 |
| Gigabyte      | H97-HD3                     | [7c2db201dc](https://linux-hardware.org/?probe=7c2db201dc) | Nov 24, 2022 |
| MSI           | MAG B550 TORPEDO            | [ca3bcfa403](https://linux-hardware.org/?probe=ca3bcfa403) | Nov 23, 2022 |
| ASUSTek       | PRIME B550-PLUS             | [b0e5869f2d](https://linux-hardware.org/?probe=b0e5869f2d) | Nov 23, 2022 |
| Acer          | FIH57                       | [008bcadcd9](https://linux-hardware.org/?probe=008bcadcd9) | Nov 23, 2022 |
| MSI           | H61M-E33                    | [d0277334cf](https://linux-hardware.org/?probe=d0277334cf) | Nov 23, 2022 |
| Gigabyte      | B650M DS3H                  | [fc9449798a](https://linux-hardware.org/?probe=fc9449798a) | Nov 23, 2022 |
| ASUSTek       | H81M2                       | [f06b4252d7](https://linux-hardware.org/?probe=f06b4252d7) | Nov 22, 2022 |
| Gigabyte      | GA-MA770T-UD3               | [29b92290e8](https://linux-hardware.org/?probe=29b92290e8) | Nov 22, 2022 |
| Acer          | Veriton X2631G V:1.0        | [af2a85dd3c](https://linux-hardware.org/?probe=af2a85dd3c) | Nov 22, 2022 |
| Dell          | 0GY6Y8 A02                  | [8789b14e39](https://linux-hardware.org/?probe=8789b14e39) | Nov 21, 2022 |
| HP            | 8184 X4                     | [f38ad9d963](https://linux-hardware.org/?probe=f38ad9d963) | Nov 21, 2022 |
| ASUSTek       | V-P5G43 R1.04G              | [b400ca5e29](https://linux-hardware.org/?probe=b400ca5e29) | Nov 21, 2022 |
| MSI           | MAG B560M MORTAR            | [18a3c1f2bf](https://linux-hardware.org/?probe=18a3c1f2bf) | Nov 21, 2022 |
| HP            | 3399                        | [bce6df1ffb](https://linux-hardware.org/?probe=bce6df1ffb) | Nov 21, 2022 |
| ASUSTek       | F1A55-M LE                  | [f2120128c1](https://linux-hardware.org/?probe=f2120128c1) | Nov 21, 2022 |
| MSI           | A68HM-E33 V2                | [a93dbf13df](https://linux-hardware.org/?probe=a93dbf13df) | Nov 21, 2022 |
| MSI           | A68HM-E33 V2                | [50ca61403f](https://linux-hardware.org/?probe=50ca61403f) | Nov 21, 2022 |
| Acer          | FIH57                       | [70bcc47286](https://linux-hardware.org/?probe=70bcc47286) | Nov 21, 2022 |
| Acer          | Veriton X2631G V:1.0        | [df71eef5cb](https://linux-hardware.org/?probe=df71eef5cb) | Nov 21, 2022 |
| Acer          | Veriton N4640G              | [a7984c4a95](https://linux-hardware.org/?probe=a7984c4a95) | Nov 20, 2022 |
| HP            | 339A                        | [f5f01373e9](https://linux-hardware.org/?probe=f5f01373e9) | Nov 20, 2022 |
| ASRock        | 990FX Extreme3              | [84b8daa5c4](https://linux-hardware.org/?probe=84b8daa5c4) | Nov 20, 2022 |
| MSI           | X299 RAIDER                 | [544b8ae2b7](https://linux-hardware.org/?probe=544b8ae2b7) | Nov 19, 2022 |
| Gigabyte      | 970A-DS3P                   | [fc7b21bd04](https://linux-hardware.org/?probe=fc7b21bd04) | Nov 18, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [a0495a1ea1](https://linux-hardware.org/?probe=a0495a1ea1) | Nov 18, 2022 |
| HP            | 8643 SMVB                   | [3556ffb814](https://linux-hardware.org/?probe=3556ffb814) | Nov 18, 2022 |
| Dell          | 0Y7WYT A00                  | [d5306443e9](https://linux-hardware.org/?probe=d5306443e9) | Nov 18, 2022 |
| Dell          | 0773VG A00                  | [754a16b847](https://linux-hardware.org/?probe=754a16b847) | Nov 18, 2022 |
| Dell          | 0Y7WYT A00                  | [516b201857](https://linux-hardware.org/?probe=516b201857) | Nov 18, 2022 |
| Dell          | 04MFRM A02                  | [677ab8eb16](https://linux-hardware.org/?probe=677ab8eb16) | Nov 16, 2022 |
| ASUSTek       | H81M-A                      | [ff63827781](https://linux-hardware.org/?probe=ff63827781) | Nov 15, 2022 |
| MSI           | PRO H610M-B DDR4            | [5ffe9844bd](https://linux-hardware.org/?probe=5ffe9844bd) | Nov 15, 2022 |
| ASUSTek       | P5QL-ASUS-SE                | [6dd2bbbe51](https://linux-hardware.org/?probe=6dd2bbbe51) | Nov 15, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [21ea41871f](https://linux-hardware.org/?probe=21ea41871f) | Nov 14, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [7bf6427590](https://linux-hardware.org/?probe=7bf6427590) | Nov 14, 2022 |
| Gigabyte      | H97-HD3                     | [8a2f5e3f03](https://linux-hardware.org/?probe=8a2f5e3f03) | Nov 14, 2022 |
| Gigabyte      | H97-HD3                     | [b99ae215e4](https://linux-hardware.org/?probe=b99ae215e4) | Nov 14, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [851afe02f6](https://linux-hardware.org/?probe=851afe02f6) | Nov 13, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [71c62efbb1](https://linux-hardware.org/?probe=71c62efbb1) | Nov 13, 2022 |
| Foxconn       | 2ADA                        | [4ddae3c3a0](https://linux-hardware.org/?probe=4ddae3c3a0) | Nov 13, 2022 |
| Gigabyte      | B150M-D3H-CF                | [3b46bafe87](https://linux-hardware.org/?probe=3b46bafe87) | Nov 13, 2022 |
| MSI           | H97 GUARD-PRO               | [3ea9d7a74a](https://linux-hardware.org/?probe=3ea9d7a74a) | Nov 13, 2022 |
| ASUSTek       | M2NPV-VM                    | [db28f53298](https://linux-hardware.org/?probe=db28f53298) | Nov 12, 2022 |
| ASUSTek       | P7P55D-E LX                 | [cef5f6aa9f](https://linux-hardware.org/?probe=cef5f6aa9f) | Nov 12, 2022 |
| Intel         | DQ77KB AAG81483-500         | [eceaef0c0c](https://linux-hardware.org/?probe=eceaef0c0c) | Nov 12, 2022 |
| Biostar       | A70MD PRO                   | [8c9796cb09](https://linux-hardware.org/?probe=8c9796cb09) | Nov 12, 2022 |
| MSI           | B75MA-P45                   | [3db5e45a80](https://linux-hardware.org/?probe=3db5e45a80) | Nov 12, 2022 |
| Lenovo        | SDK0E50510 WIN              | [d77bd1633c](https://linux-hardware.org/?probe=d77bd1633c) | Nov 11, 2022 |
| MSI           | B75A-G43                    | [75822f5ac0](https://linux-hardware.org/?probe=75822f5ac0) | Nov 11, 2022 |
| Gigabyte      | H410M S2H V3                | [2172ca7325](https://linux-hardware.org/?probe=2172ca7325) | Nov 11, 2022 |
| Dell          | 0D441T A00                  | [8825499c05](https://linux-hardware.org/?probe=8825499c05) | Nov 11, 2022 |
| ASUSTek       | Benicia                     | [03ce113379](https://linux-hardware.org/?probe=03ce113379) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | [0664261b3a](https://linux-hardware.org/?probe=0664261b3a) | Nov 11, 2022 |
| ASUSTek       | EB1501P                     | [ad47bcfb8b](https://linux-hardware.org/?probe=ad47bcfb8b) | Nov 11, 2022 |
| ASUSTek       | X99-DELUXE                  | [a1243611f4](https://linux-hardware.org/?probe=a1243611f4) | Nov 11, 2022 |
| Dell          | 0NNNCT A01                  | [472bcb70c1](https://linux-hardware.org/?probe=472bcb70c1) | Nov 10, 2022 |
| ASUSTek       | X99-DELUXE                  | [784b2e30e1](https://linux-hardware.org/?probe=784b2e30e1) | Nov 10, 2022 |
| Dell          | 04YP6J A02                  | [6a3833051e](https://linux-hardware.org/?probe=6a3833051e) | Nov 10, 2022 |
| Gigabyte      | Z690 GAMING X DDR4          | [ddbdf3da0f](https://linux-hardware.org/?probe=ddbdf3da0f) | Nov 10, 2022 |
| Acer          | RS880M05                    | [cb216f090c](https://linux-hardware.org/?probe=cb216f090c) | Nov 09, 2022 |
| Gigabyte      | GA-MA770T-UD3               | [6e773a6bf0](https://linux-hardware.org/?probe=6e773a6bf0) | Nov 09, 2022 |
| ASUSTek       | B150M-C                     | [d2dd725b2e](https://linux-hardware.org/?probe=d2dd725b2e) | Nov 09, 2022 |
| BESSTAR Te... | TH50                        | [9e0784517f](https://linux-hardware.org/?probe=9e0784517f) | Nov 09, 2022 |
| Acer          | Aspire XC600 v1.0           | [9eddda7671](https://linux-hardware.org/?probe=9eddda7671) | Nov 09, 2022 |
| Gigabyte      | B450 AORUS ELITE            | [08be836975](https://linux-hardware.org/?probe=08be836975) | Nov 08, 2022 |
| MSI           | MAG B560M MORTAR            | [d06c10f1cf](https://linux-hardware.org/?probe=d06c10f1cf) | Nov 08, 2022 |
| MSI           | 970 GAMING                  | [d2ab3af437](https://linux-hardware.org/?probe=d2ab3af437) | Nov 08, 2022 |
| MSI           | PRO H610M-B DDR4            | [377df38ed7](https://linux-hardware.org/?probe=377df38ed7) | Nov 08, 2022 |
| MSI           | X370 GAMING PRO CARBON      | [2796faab6c](https://linux-hardware.org/?probe=2796faab6c) | Nov 08, 2022 |
| MSI           | MAG B560M MORTAR            | [5fe681b53d](https://linux-hardware.org/?probe=5fe681b53d) | Nov 07, 2022 |
| Unknown       | Unknown                     | [dc375c11c7](https://linux-hardware.org/?probe=dc375c11c7) | Nov 07, 2022 |
| Gigabyte      | X670 GAMING X AX            | [1a96ebec7a](https://linux-hardware.org/?probe=1a96ebec7a) | Nov 07, 2022 |
| Dell          | 0N826N A03                  | [2126bcff1e](https://linux-hardware.org/?probe=2126bcff1e) | Nov 06, 2022 |
| Acer          | Aspire XC600 v1.0           | [440f3f42f9](https://linux-hardware.org/?probe=440f3f42f9) | Nov 06, 2022 |
| ASUSTek       | PRO H410T                   | [66a809ab24](https://linux-hardware.org/?probe=66a809ab24) | Nov 05, 2022 |
| ASUSTek       | P7P55D-E LX                 | [2a79c24ee2](https://linux-hardware.org/?probe=2a79c24ee2) | Nov 05, 2022 |
| HP            | 83E9                        | [837b4320c1](https://linux-hardware.org/?probe=837b4320c1) | Nov 05, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [ffb4ff83fd](https://linux-hardware.org/?probe=ffb4ff83fd) | Nov 05, 2022 |
| Foxconn       | 2ABF                        | [75884710cd](https://linux-hardware.org/?probe=75884710cd) | Nov 04, 2022 |
| Gigabyte      | H97-HD3                     | [bb8dbe6d52](https://linux-hardware.org/?probe=bb8dbe6d52) | Nov 04, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [acb00ae29c](https://linux-hardware.org/?probe=acb00ae29c) | Nov 03, 2022 |
| MSI           | MAG B560M MORTAR            | [82a755ae03](https://linux-hardware.org/?probe=82a755ae03) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | [eb15ca5b98](https://linux-hardware.org/?probe=eb15ca5b98) | Nov 03, 2022 |
| ASUSTek       | K30AD_M31AD_M51AD_M32AD     | [5ace066925](https://linux-hardware.org/?probe=5ace066925) | Nov 03, 2022 |
| ASUSTek       | P8Z77-V                     | [adb4579fb7](https://linux-hardware.org/?probe=adb4579fb7) | Nov 03, 2022 |
| Intel         | D33217GKE G76540-203        | [20824af437](https://linux-hardware.org/?probe=20824af437) | Nov 03, 2022 |
| Gigabyte      | Z390 UD                     | [c54743b7e8](https://linux-hardware.org/?probe=c54743b7e8) | Nov 02, 2022 |
| Gigabyte      | Z390 UD                     | [24a3f977bf](https://linux-hardware.org/?probe=24a3f977bf) | Nov 02, 2022 |
| Dell          | 0JGM7F A00                  | [28f4800b2b](https://linux-hardware.org/?probe=28f4800b2b) | Nov 02, 2022 |
| Gigabyte      | 970A-DS3P                   | [65231808f8](https://linux-hardware.org/?probe=65231808f8) | Nov 02, 2022 |
| Dell          | 0XR1GT A00                  | [8f551aaa52](https://linux-hardware.org/?probe=8f551aaa52) | Nov 01, 2022 |
| Dell          | 03NVJ6 A03                  | [adebd09dc4](https://linux-hardware.org/?probe=adebd09dc4) | Oct 31, 2022 |
| ASRock        | B560M Pro4                  | [865aef7529](https://linux-hardware.org/?probe=865aef7529) | Oct 31, 2022 |
| ASUSTek       | P7P55D-E PRO                | [1e0daee604](https://linux-hardware.org/?probe=1e0daee604) | Oct 30, 2022 |
| Foxconn       | 2ABF                        | [ad558f1150](https://linux-hardware.org/?probe=ad558f1150) | Oct 30, 2022 |
| HP            | 158B                        | [9c02b7fe58](https://linux-hardware.org/?probe=9c02b7fe58) | Oct 30, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Location/France/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name               | Desktops | Percent |
|--------------------|----------|---------|
| Ubuntu 20.04       | 670      | 17.74%  |
| Ubuntu 22.04       | 222      | 5.88%   |
| Ubuntu 18.04       | 218      | 5.77%   |
| OpenMandriva 4.2   | 181      | 4.79%   |
| Debian 11          | 148      | 3.92%   |
| OpenMandriva 4.3   | 137      | 3.63%   |
| Xubuntu 20.04      | 78       | 2.07%   |
| OpenMandriva 23.01 | 67       | 1.77%   |
| Arch Rolling       | 66       | 1.75%   |
| Linux Mint 20.3    | 65       | 1.72%   |
| Linux Mint 20.1    | 58       | 1.54%   |
| Debian 10          | 58       | 1.54%   |
| Linux Mint 21.1    | 45       | 1.19%   |
| Linux Mint 20.2    | 43       | 1.14%   |
| Ubuntu 20.10       | 41       | 1.09%   |
| Ubuntu 21.04       | 40       | 1.06%   |
| Ubuntu 21.10       | 39       | 1.03%   |
| OpenMandriva 23.03 | 39       | 1.03%   |
| Linux Mint 19.3    | 37       | 0.98%   |
| Arch               | 37       | 0.98%   |
| Kubuntu 20.04      | 36       | 0.95%   |
| Fedora 33          | 35       | 0.93%   |
| Manjaro            | 33       | 0.87%   |
| Linux Mint 20      | 33       | 0.87%   |
| Zorin 16           | 32       | 0.85%   |
| Fedora 35          | 32       | 0.85%   |
| KDE neon 20.04     | 31       | 0.82%   |
| Pop!_OS 22.04      | 30       | 0.79%   |
| Linux Mint 21      | 30       | 0.79%   |
| Ubuntu 19.04       | 29       | 0.77%   |
| Ubuntu 19.10       | 26       | 0.69%   |
| Xubuntu 18.04      | 25       | 0.66%   |
| Ubuntu MATE 20.04  | 25       | 0.66%   |
| OpenMandriva 4.50  | 25       | 0.66%   |
| Lubuntu 20.04      | 24       | 0.64%   |
| Fedora 36          | 24       | 0.64%   |
| Fedora 32          | 24       | 0.64%   |
| Ubuntu 22.10       | 23       | 0.61%   |
| Kubuntu 22.04      | 23       | 0.61%   |
| Fedora 34          | 23       | 0.61%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Desktops | Percent |
|---------------|----------|---------|
| Ubuntu        | 1298     | 36.52%  |
| OpenMandriva  | 444      | 12.49%  |
| Linux Mint    | 307      | 8.64%   |
| Debian        | 238      | 6.7%    |
| Xubuntu       | 144      | 4.05%   |
| Fedora        | 142      | 4%      |
| Arch          | 99       | 2.79%   |
| ROSA          | 94       | 2.64%   |
| Manjaro       | 94       | 2.64%   |
| Kubuntu       | 79       | 2.22%   |
| Pop!_OS       | 77       | 2.17%   |
| Ubuntu MATE   | 54       | 1.52%   |
| Zorin         | 49       | 1.38%   |
| Ubuntu Unity  | 46       | 1.29%   |
| Lubuntu       | 45       | 1.27%   |
| KDE neon      | 40       | 1.13%   |
| Gentoo        | 28       | 0.79%   |
| openSUSE      | 24       | 0.68%   |
| ArcoLinux     | 22       | 0.62%   |
| LMDE          | 18       | 0.51%   |
| Ubuntu Budgie | 16       | 0.45%   |
| Mageia        | 16       | 0.45%   |
| BlackPanther  | 16       | 0.45%   |
| Elementary    | 15       | 0.42%   |
| CentOS        | 15       | 0.42%   |
| EndeavourOS   | 13       | 0.37%   |
| Nobara        | 11       | 0.31%   |
| Clear Linux   | 11       | 0.31%   |
| Ubuntu Studio | 10       | 0.28%   |
| Kali          | 10       | 0.28%   |
| Endless       | 7        | 0.2%    |
| Devuan        | 7        | 0.2%    |
| Artix         | 7        | 0.2%    |
| MX            | 6        | 0.17%   |
| SteamOS       | 5        | 0.14%   |
| LinuxFX       | 5        | 0.14%   |
| Trisquel      | 4        | 0.11%   |
| Sparky        | 3        | 0.08%   |
| Solus         | 3        | 0.08%   |
| Garuda Linux  | 3        | 0.08%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Desktops | Percent |
|--------------------------|----------|---------|
| 5.10.14-desktop-1omv4002 | 174      | 4.16%   |
| 5.16.7-desktop-1omv4003  | 123      | 2.94%   |
| 6.1.1-desktop-1omv2290   | 60       | 1.43%   |
| 5.4.0-58-generic         | 50       | 1.2%    |
| 5.4.0-42-generic         | 44       | 1.05%   |
| 5.15.0-56-generic        | 43       | 1.03%   |
| 5.15.0-52-generic        | 39       | 0.93%   |
| 6.2.6-desktop-1omv2390   | 34       | 0.81%   |
| 5.15.0-58-generic        | 34       | 0.81%   |
| 5.4.0-65-generic         | 31       | 0.74%   |
| 5.4.0-48-generic         | 31       | 0.74%   |
| 5.4.0-52-generic         | 30       | 0.72%   |
| 5.4.0-29-generic         | 30       | 0.72%   |
| 5.11.0-37-generic        | 30       | 0.72%   |
| 5.4.0-26-generic         | 28       | 0.67%   |
| 5.15.0-48-generic        | 28       | 0.67%   |
| 5.11.0-27-generic        | 28       | 0.67%   |
| 5.8.0-43-generic         | 27       | 0.65%   |
| 5.15.0-46-generic        | 27       | 0.65%   |
| 5.15.0-43-generic        | 27       | 0.65%   |
| 5.13.0-28-generic        | 27       | 0.65%   |
| 5.8.0-50-generic         | 26       | 0.62%   |
| 5.19.0-38-generic        | 26       | 0.62%   |
| 5.13.0-39-generic        | 26       | 0.62%   |
| 5.4.0-54-generic         | 25       | 0.6%    |
| 5.11.0-38-generic        | 23       | 0.55%   |
| 5.4.0-81-generic         | 21       | 0.5%    |
| 5.15.0-47-generic        | 21       | 0.5%    |
| 5.8.0-48-generic         | 20       | 0.48%   |
| 5.4.0-74-generic         | 20       | 0.48%   |
| 5.19.0-35-generic        | 20       | 0.48%   |
| 5.11.0-40-generic        | 20       | 0.48%   |
| 5.8.0-44-generic         | 19       | 0.45%   |
| 5.4.0-91-generic         | 19       | 0.45%   |
| 5.4.0-73-generic         | 19       | 0.45%   |
| 5.4.0-70-generic         | 19       | 0.45%   |
| 5.4.0-37-generic         | 19       | 0.45%   |
| 5.11.0-41-generic        | 19       | 0.45%   |
| 5.4.0-72-generic         | 18       | 0.43%   |
| 5.4.0-66-generic         | 18       | 0.43%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 739      | 18.93%  |
| 5.15.0  | 383      | 9.81%   |
| 5.11.0  | 236      | 6.05%   |
| 5.8.0   | 218      | 5.59%   |
| 4.15.0  | 204      | 5.23%   |
| 5.13.0  | 179      | 4.59%   |
| 5.10.14 | 176      | 4.51%   |
| 5.10.0  | 140      | 3.59%   |
| 5.16.7  | 125      | 3.2%    |
| 5.19.0  | 124      | 3.18%   |
| 5.3.0   | 104      | 2.66%   |
| 6.1.1   | 64       | 1.64%   |
| 5.0.0   | 60       | 1.54%   |
| 4.19.0  | 59       | 1.51%   |
| 4.18.0  | 59       | 1.51%   |
| 6.2.6   | 45       | 1.15%   |
| 4.9.20  | 19       | 0.49%   |
| 4.9.60  | 16       | 0.41%   |
| 5.16.13 | 15       | 0.38%   |
| 5.18.0  | 14       | 0.36%   |
| 5.11.12 | 14       | 0.36%   |
| 4.4.0   | 14       | 0.36%   |
| 4.18.16 | 14       | 0.36%   |
| 5.18.12 | 13       | 0.33%   |
| 5.12.4  | 13       | 0.33%   |
| 6.1.0   | 12       | 0.31%   |
| 6.0.0   | 12       | 0.31%   |
| 5.4.32  | 11       | 0.28%   |
| 5.17.5  | 10       | 0.26%   |
| 6.2.11  | 9        | 0.23%   |
| 6.0.12  | 9        | 0.23%   |
| 5.19.12 | 9        | 0.23%   |
| 5.14.0  | 9        | 0.23%   |
| 3.10.0  | 9        | 0.23%   |
| 5.9.16  | 8        | 0.2%    |
| 5.9.0   | 8        | 0.2%    |
| 6.2.0   | 7        | 0.18%   |
| 5.8.16  | 7        | 0.18%   |
| 5.6.19  | 7        | 0.18%   |
| 5.3.18  | 7        | 0.18%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 780      | 20.21%  |
| 5.15    | 454      | 11.76%  |
| 5.10    | 363      | 9.41%   |
| 5.11    | 276      | 7.15%   |
| 5.8     | 260      | 6.74%   |
| 5.13    | 213      | 5.52%   |
| 4.15    | 205      | 5.31%   |
| 5.16    | 175      | 4.53%   |
| 5.19    | 158      | 4.09%   |
| 5.3     | 120      | 3.11%   |
| 6.1     | 112      | 2.9%    |
| 6.2     | 89       | 2.31%   |
| 4.18    | 74       | 1.92%   |
| 5.0     | 67       | 1.74%   |
| 4.19    | 66       | 1.71%   |
| 4.9     | 63       | 1.63%   |
| 5.18    | 52       | 1.35%   |
| 6.0     | 46       | 1.19%   |
| 5.9     | 43       | 1.11%   |
| 5.17    | 39       | 1.01%   |
| 5.14    | 33       | 0.86%   |
| 5.6     | 29       | 0.75%   |
| 5.7     | 27       | 0.7%    |
| 5.12    | 27       | 0.7%    |
| 5.5     | 15       | 0.39%   |
| 4.4     | 15       | 0.39%   |
| 6.3     | 14       | 0.36%   |
| 4.1     | 13       | 0.34%   |
| 3.10    | 9        | 0.23%   |
| 4.20    | 5        | 0.13%   |
| 4.12    | 4        | 0.1%    |
| 5.2     | 3        | 0.08%   |
| 4.14    | 3        | 0.08%   |
| 5.1     | 2        | 0.05%   |
| 4.8     | 2        | 0.05%   |
| 4.13    | 2        | 0.05%   |
| 2.6     | 1        | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 3339     | 97.12%  |
| i686   | 97       | 2.82%   |
| armv7l | 2        | 0.06%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 1442     | 40.21%  |
| KDE5            | 707      | 19.72%  |
| Unknown         | 391      | 10.9%   |
| XFCE            | 308      | 8.59%   |
| X-Cinnamon      | 237      | 6.61%   |
| MATE            | 145      | 4.04%   |
| KDE4            | 60       | 1.67%   |
| LXQt            | 54       | 1.51%   |
| KDE             | 50       | 1.39%   |
| Unity           | 46       | 1.28%   |
| Cinnamon        | 40       | 1.12%   |
| Budgie          | 19       | 0.53%   |
| LXDE            | 18       | 0.5%    |
| Pantheon        | 17       | 0.47%   |
| i3              | 11       | 0.31%   |
| GNOME Flashback | 8        | 0.22%   |
| GNOME Classic   | 7        | 0.2%    |
| qtile           | 4        | 0.11%   |
| Deepin          | 3        | 0.08%   |
| bspwm           | 3        | 0.08%   |
| sway            | 2        | 0.06%   |
| ICEWM           | 2        | 0.06%   |
| awesome         | 2        | 0.06%   |
| trinity         | 1        | 0.03%   |
| Openbox         | 1        | 0.03%   |
| LeftWM          | 1        | 0.03%   |
| INPT            | 1        | 0.03%   |
| Hyprland        | 1        | 0.03%   |
| GNUstep         | 1        | 0.03%   |
| fluxbox         | 1        | 0.03%   |
| Enlightenment   | 1        | 0.03%   |
| DWM             | 1        | 0.03%   |
| chadwm          | 1        | 0.03%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 2830     | 80.1%   |
| Wayland | 386      | 10.93%  |
| Unknown | 169      | 4.78%   |
| Tty     | 148      | 4.19%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1361     | 37.89%  |
| SDDM    | 711      | 19.79%  |
| GDM     | 525      | 14.62%  |
| LightDM | 407      | 11.33%  |
| GDM3    | 376      | 10.47%  |
| TDM     | 139      | 3.87%   |
| KDM     | 58       | 1.61%   |
| Ly      | 5        | 0.14%   |
| SLiM    | 4        | 0.11%   |
| XDM     | 2        | 0.06%   |
| LXDM    | 2        | 0.06%   |
| WDM     | 1        | 0.03%   |
| NODM    | 1        | 0.03%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang        | Desktops | Percent |
|-------------|----------|---------|
| fr_FR       | 2546     | 72.43%  |
| en_US       | 474      | 13.49%  |
| Unknown     | 322      | 9.16%   |
| en_GB       | 50       | 1.42%   |
| C           | 42       | 1.19%   |
| de_DE       | 14       | 0.4%    |
| ru_RU       | 9        | 0.26%   |
| en_IE       | 6        | 0.17%   |
| pt_PT       | 5        | 0.14%   |
| nl_NL       | 5        | 0.14%   |
| es_ES       | 5        | 0.14%   |
| fr_CA       | 4        | 0.11%   |
| it_IT       | 3        | 0.09%   |
| fr_CH       | 3        | 0.09%   |
| en_DK       | 3        | 0.09%   |
| C.UTF8      | 3        | 0.09%   |
| sv_SE       | 2        | 0.06%   |
| fr_FR.UTF8  | 2        | 0.06%   |
| fr_BE       | 2        | 0.06%   |
| sr_RS@latin | 1        | 0.03%   |
| sr_RS       | 1        | 0.03%   |
| ru_UA       | 1        | 0.03%   |
| POSIX       | 1        | 0.03%   |
| nb_NO       | 1        | 0.03%   |
| fr_LU       | 1        | 0.03%   |
| fr_FR.utf-8 | 1        | 0.03%   |
| fi_FI       | 1        | 0.03%   |
| es_ES@euro  | 1        | 0.03%   |
| es_BO       | 1        | 0.03%   |
| en_US.utf-8 | 1        | 0.03%   |
| en_EN       | 1        | 0.03%   |
| en_AU       | 1        | 0.03%   |
| en_AG       | 1        | 0.03%   |
| ar_SA       | 1        | 0.03%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 2051     | 58.5%   |
| EFI  | 1455     | 41.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Desktops | Percent |
|----------|----------|---------|
| Ext4     | 2741     | 77.45%  |
| Overlay  | 400      | 11.3%   |
| Btrfs    | 191      | 5.4%    |
| Unknown  | 97       | 2.74%   |
| Xfs      | 47       | 1.33%   |
| Zfs      | 25       | 0.71%   |
| Tmpfs    | 20       | 0.57%   |
| Ext2     | 6        | 0.17%   |
| Ext3     | 5        | 0.14%   |
| F2fs     | 3        | 0.08%   |
| Reiserfs | 2        | 0.06%   |
| Rootfs   | 1        | 0.03%   |
| Aufs     | 1        | 0.03%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 1424     | 40.16%  |
| GPT     | 1413     | 39.85%  |
| MBR     | 709      | 19.99%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2603     | 73.84%  |
| Yes       | 922      | 26.16%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 2230     | 63.3%   |
| Yes       | 1293     | 36.7%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUSTek Computer            | 944      | 27.47%  |
| MSI                         | 568      | 16.53%  |
| Gigabyte Technology         | 499      | 14.52%  |
| Dell                        | 319      | 9.28%   |
| Hewlett-Packard             | 244      | 7.1%    |
| ASRock                      | 218      | 6.34%   |
| Lenovo                      | 118      | 3.43%   |
| Acer                        | 82       | 2.39%   |
| Intel                       | 60       | 1.75%   |
| Foxconn                     | 51       | 1.48%   |
| Pegatron                    | 44       | 1.28%   |
| Packard Bell                | 38       | 1.11%   |
| Unknown                     | 37       | 1.08%   |
| Fujitsu                     | 23       | 0.67%   |
| Medion                      | 20       | 0.58%   |
| eMachines                   | 17       | 0.49%   |
| Shuttle                     | 16       | 0.47%   |
| Supermicro                  | 15       | 0.44%   |
| ECS                         | 14       | 0.41%   |
| AZW                         | 11       | 0.32%   |
| Biostar                     | 7        | 0.2%    |
| Apple                       | 7        | 0.2%    |
| ASRockRack                  | 6        | 0.17%   |
| AMI                         | 6        | 0.17%   |
| Alienware                   | 6        | 0.17%   |
| ZOTAC                       | 4        | 0.12%   |
| NEC Computers               | 4        | 0.12%   |
| Huanan                      | 4        | 0.12%   |
| Fujitsu Siemens             | 4        | 0.12%   |
| BESSTAR Tech                | 4        | 0.12%   |
| OEM                         | 3        | 0.09%   |
| Gateway                     | 3        | 0.09%   |
| ABIT                        | 3        | 0.09%   |
| Wistron                     | 2        | 0.06%   |
| ICP / iEi                   | 2        | 0.06%   |
| WinFast                     | 1        | 0.03%   |
| Vorke                       | 1        | 0.03%   |
| TYAN Computer               | 1        | 0.03%   |
| TECO Electric and Machinery | 1        | 0.03%   |
| Techvision                  | 1        | 0.03%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                        | Desktops | Percent |
|-----------------------------|----------|---------|
| ASUS All Series             | 122      | 3.55%   |
| Unknown                     | 40       | 1.16%   |
| Gigabyte B450M DS3H         | 29       | 0.84%   |
| Dell OptiPlex 390           | 21       | 0.61%   |
| Dell OptiPlex 7010          | 20       | 0.58%   |
| Dell OptiPlex 9020          | 19       | 0.55%   |
| MSI MS-7816                 | 17       | 0.49%   |
| ASUS PRIME A320M-K          | 17       | 0.49%   |
| MSI MS-7C91                 | 16       | 0.47%   |
| MSI MS-7C02                 | 15       | 0.44%   |
| MSI MS-7C37                 | 14       | 0.41%   |
| MSI MS-7817                 | 14       | 0.41%   |
| MSI MS-7758                 | 13       | 0.38%   |
| HP Compaq Elite 8300 SFF    | 13       | 0.38%   |
| Gigabyte B450 AORUS ELITE   | 13       | 0.38%   |
| Gigabyte 970A-DS3P          | 13       | 0.38%   |
| Dell OptiPlex 3020          | 13       | 0.38%   |
| MSI MS-7693                 | 12       | 0.35%   |
| ASUS TUF Gaming X570-PLUS   | 12       | 0.35%   |
| ASUS PRIME B450M-A          | 12       | 0.35%   |
| MSI MS-7B79                 | 11       | 0.32%   |
| MSI MS-7A38                 | 11       | 0.32%   |
| ASUS PRIME X470-PRO         | 11       | 0.32%   |
| MSI MS-7721                 | 10       | 0.29%   |
| MSI MS-7B86                 | 9        | 0.26%   |
| MSI MS-7B84                 | 9        | 0.26%   |
| MSI MS-7850                 | 9        | 0.26%   |
| HP Compaq 8200 Elite SFF PC | 9        | 0.26%   |
| Dell OptiPlex 3010          | 9        | 0.26%   |
| ASUS TUF Gaming B550-PLUS   | 9        | 0.26%   |
| ASUS TUF B450-PLUS GAMING   | 9        | 0.26%   |
| ASUS P8Z77-V                | 9        | 0.26%   |
| ASUS P7P55D                 | 9        | 0.26%   |
| ASRock B450M Pro4           | 9        | 0.26%   |
| MSI MS-7B89                 | 8        | 0.23%   |
| MSI MS-7A34                 | 8        | 0.23%   |
| MSI MS-7A32                 | 8        | 0.23%   |
| MSI MS-7924                 | 8        | 0.23%   |
| MSI MS-7821                 | 8        | 0.23%   |
| Gigabyte G41M-Combo         | 8        | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 183      | 5.33%   |
| ASUS PRIME          | 152      | 4.42%   |
| ASUS All            | 122      | 3.55%   |
| Dell Precision      | 92       | 2.68%   |
| Lenovo ThinkCentre  | 86       | 2.5%    |
| HP Compaq           | 83       | 2.42%   |
| ASUS ROG            | 76       | 2.21%   |
| ASUS TUF            | 66       | 1.92%   |
| Acer Aspire         | 49       | 1.43%   |
| Unknown             | 40       | 1.16%   |
| Gigabyte B450M      | 35       | 1.02%   |
| Packard Bell IMEDIA | 30       | 0.87%   |
| HP EliteDesk        | 29       | 0.84%   |
| HP ProDesk          | 27       | 0.79%   |
| ASUS P8Z77-V        | 25       | 0.73%   |
| Gigabyte B450       | 24       | 0.7%    |
| Acer Veriton        | 22       | 0.64%   |
| Gigabyte X570       | 18       | 0.52%   |
| Fujitsu ESPRIMO     | 18       | 0.52%   |
| MSI MS-7816         | 17       | 0.49%   |
| MSI MS-7C91         | 16       | 0.47%   |
| Gigabyte B550       | 16       | 0.47%   |
| MSI MS-7C02         | 15       | 0.44%   |
| HP Pavilion         | 15       | 0.44%   |
| Dell Inspiron       | 15       | 0.44%   |
| ASUS P8P67          | 15       | 0.44%   |
| ASUS P8H61-M        | 15       | 0.44%   |
| MSI MS-7C37         | 14       | 0.41%   |
| MSI MS-7817         | 14       | 0.41%   |
| HP ProLiant         | 14       | 0.41%   |
| Gigabyte 970A-DS3P  | 14       | 0.41%   |
| ASUS P7P55D         | 14       | 0.41%   |
| MSI MS-7758         | 13       | 0.38%   |
| Gigabyte Z390       | 13       | 0.38%   |
| ASUS M5A97          | 13       | 0.38%   |
| ASRock B450M        | 13       | 0.38%   |
| MSI MS-7693         | 12       | 0.35%   |
| Dell XPS            | 12       | 0.35%   |
| ASUS SABERTOOTH     | 12       | 0.35%   |
| ASUS M5A78L-M       | 12       | 0.35%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2018    | 350      | 10.19%  |
| 2012    | 328      | 9.55%   |
| 2013    | 320      | 9.31%   |
| 2011    | 255      | 7.42%   |
| 2014    | 244      | 7.1%    |
| 2020    | 222      | 6.46%   |
| 2010    | 221      | 6.43%   |
| 2019    | 212      | 6.17%   |
| 2009    | 205      | 5.97%   |
| 2017    | 185      | 5.38%   |
| 2015    | 185      | 5.38%   |
| 2008    | 164      | 4.77%   |
| 2016    | 143      | 4.16%   |
| 2021    | 134      | 3.9%    |
| 2007    | 99       | 2.88%   |
| 2006    | 67       | 1.95%   |
| 2022    | 42       | 1.22%   |
| 2005    | 32       | 0.93%   |
| 2004    | 9        | 0.26%   |
| 2003    | 8        | 0.23%   |
| 2023    | 5        | 0.15%   |
| Unknown | 3        | 0.09%   |
| 2001    | 2        | 0.06%   |
| 2002    | 1        | 0.03%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 3436     | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 3337     | 96.89%  |
| Enabled  | 107      | 3.11%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 3435     | 99.97%  |
| Yes  | 1        | 0.03%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 16.01-24.0      | 884      | 25.19%  |
| 8.01-16.0       | 695      | 19.81%  |
| 3.01-4.0        | 612      | 17.44%  |
| 4.01-8.0        | 504      | 14.36%  |
| 32.01-64.0      | 408      | 11.63%  |
| 1.01-2.0        | 126      | 3.59%   |
| 64.01-256.0     | 109      | 3.11%   |
| 24.01-32.0      | 88       | 2.51%   |
| 2.01-3.0        | 51       | 1.45%   |
| 0.51-1.0        | 23       | 0.66%   |
| More than 256.0 | 3        | 0.09%   |
| 0.01-0.5        | 3        | 0.09%   |
| Unknown         | 3        | 0.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 1.01-2.0    | 1383     | 36.24%  |
| 2.01-3.0    | 854      | 22.38%  |
| 4.01-8.0    | 545      | 14.28%  |
| 3.01-4.0    | 461      | 12.08%  |
| 0.51-1.0    | 288      | 7.55%   |
| 8.01-16.0   | 159      | 4.17%   |
| 0.01-0.5    | 65       | 1.7%    |
| 16.01-24.0  | 36       | 0.94%   |
| 32.01-64.0  | 11       | 0.29%   |
| 24.01-32.0  | 7        | 0.18%   |
| Unknown     | 4        | 0.1%    |
| 64.01-256.0 | 3        | 0.08%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Desktops | Percent |
|---------|----------|---------|
| 1       | 1336     | 37.24%  |
| 2       | 1006     | 28.04%  |
| 3       | 599      | 16.69%  |
| 4       | 327      | 9.11%   |
| 5       | 144      | 4.01%   |
| 6       | 76       | 2.12%   |
| 7       | 38       | 1.06%   |
| 0       | 28       | 0.78%   |
| 8       | 14       | 0.39%   |
| 9       | 9        | 0.25%   |
| Unknown | 3        | 0.08%   |
| 25      | 1        | 0.03%   |
| 22      | 1        | 0.03%   |
| 21      | 1        | 0.03%   |
| 17      | 1        | 0.03%   |
| 14      | 1        | 0.03%   |
| 13      | 1        | 0.03%   |
| 11      | 1        | 0.03%   |
| 10      | 1        | 0.03%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 1963     | 56.23%  |
| No        | 1528     | 43.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 3415     | 99.39%  |
| No        | 21       | 0.61%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2161     | 61.81%  |
| Yes       | 1335     | 38.19%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 2590     | 74.23%  |
| Yes       | 899      | 25.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| France  | 3436     | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Desktops | Percent |
|------------------|----------|---------|
| Paris            | 435      | 11.73%  |
| Marseille        | 68       | 1.83%   |
| Lyon             | 62       | 1.67%   |
| Strasbourg       | 48       | 1.29%   |
| Toulouse         | 40       | 1.08%   |
| Nantes           | 37       | 1%      |
| Roubaix          | 33       | 0.89%   |
| Nice             | 31       | 0.84%   |
| Montpellier      | 31       | 0.84%   |
| Rennes           | 28       | 0.75%   |
| Clichy-sous-Bois | 27       | 0.73%   |
| Bordeaux         | 26       | 0.7%    |
| Tours            | 22       | 0.59%   |
| Grenoble         | 22       | 0.59%   |
| Lille            | 19       | 0.51%   |
| La Rochelle      | 17       | 0.46%   |
| Toulon           | 16       | 0.43%   |
| Poitiers         | 16       | 0.43%   |
| Caen             | 16       | 0.43%   |
| Nîmes           | 15       | 0.4%    |
| Amiens           | 14       | 0.38%   |
| Dijon            | 13       | 0.35%   |
| Versailles       | 12       | 0.32%   |
| Perpignan        | 12       | 0.32%   |
| Pau              | 12       | 0.32%   |
| Limoges          | 12       | 0.32%   |
| Aubervilliers    | 12       | 0.32%   |
| Vannes           | 11       | 0.3%    |
| Rouen            | 11       | 0.3%    |
| Colomiers        | 11       | 0.3%    |
| Clermont-Ferrand | 11       | 0.3%    |
| Brest            | 11       | 0.3%    |
| Besançon        | 11       | 0.3%    |
| Argenteuil       | 11       | 0.3%    |
| Aix-en-Provence  | 11       | 0.3%    |
| Saint-Nazaire    | 10       | 0.27%   |
| Niort            | 10       | 0.27%   |
| Valenciennes     | 9        | 0.24%   |
| Rosny-sous-Bois  | 9        | 0.24%   |
| Nancy            | 9        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate                   | 1342     | 2173   | 21.1%   |
| WDC                       | 1167     | 1981   | 18.35%  |
| Samsung Electronics       | 972      | 1677   | 15.29%  |
| Crucial                   | 514      | 753    | 8.08%   |
| Kingston                  | 333      | 419    | 5.24%   |
| Toshiba                   | 314      | 432    | 4.94%   |
| SanDisk                   | 240      | 324    | 3.77%   |
| Hitachi                   | 211      | 295    | 3.32%   |
| PNY                       | 111      | 142    | 1.75%   |
| Maxtor                    | 106      | 136    | 1.67%   |
| Intel                     | 90       | 109    | 1.42%   |
| Unknown                   | 74       | 108    | 1.16%   |
| HGST                      | 65       | 106    | 1.02%   |
| China                     | 55       | 71     | 0.86%   |
| Phison                    | 53       | 69     | 0.83%   |
| LDLC                      | 51       | 77     | 0.8%    |
| Corsair                   | 51       | 59     | 0.8%    |
| OCZ                       | 42       | 56     | 0.66%   |
| Micron/Crucial Technology | 40       | 57     | 0.63%   |
| SK hynix                  | 35       | 43     | 0.55%   |
| Transcend                 | 34       | 42     | 0.53%   |
| SPCC                      | 27       | 38     | 0.42%   |
| Micron Technology         | 26       | 32     | 0.41%   |
| A-DATA Technology         | 25       | 28     | 0.39%   |
| Gigabyte Technology       | 18       | 21     | 0.28%   |
| Phison Electronics        | 17       | 23     | 0.27%   |
| Emtec                     | 16       | 21     | 0.25%   |
| Intenso                   | 13       | 15     | 0.2%    |
| Hewlett-Packard           | 12       | 42     | 0.19%   |
| ASMT                      | 12       | 16     | 0.19%   |
| TEXTORM                   | 11       | 12     | 0.17%   |
| Silicon Motion            | 11       | 18     | 0.17%   |
| LITEONIT                  | 11       | 11     | 0.17%   |
| Unknown                   | 11       | 15     | 0.17%   |
| JMicron Technology        | 10       | 18     | 0.16%   |
| Fujitsu                   | 9        | 18     | 0.14%   |
| Patriot                   | 8        | 13     | 0.13%   |
| Magnetic Data             | 7        | 8      | 0.11%   |
| LITEON                    | 7        | 7      | 0.11%   |
| LaCie                     | 7        | 8      | 0.11%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Seagate ST2000DM008-2FR102 2TB   | 89       | 1.2%    |
| Seagate ST500DM002-1BD142 500GB  | 85       | 1.15%   |
| Seagate ST1000DM010-2EP102 1TB   | 85       | 1.15%   |
| Samsung SSD 860 EVO 500GB        | 83       | 1.12%   |
| Crucial CT240BX500SSD1 240GB     | 80       | 1.08%   |
| Samsung SSD 850 EVO 250GB        | 67       | 0.9%    |
| Seagate ST2000DM001-1ER164 2TB   | 66       | 0.89%   |
| Crucial CT500MX500SSD1 500GB     | 64       | 0.86%   |
| Seagate ST1000DM003-1ER162 1TB   | 61       | 0.82%   |
| Seagate ST1000DM003-1CH162 1TB   | 61       | 0.82%   |
| Samsung SSD 850 EVO 500GB        | 60       | 0.81%   |
| Kingston SA400S37240G 240GB SSD  | 57       | 0.77%   |
| Toshiba DT01ACA100 1TB           | 55       | 0.74%   |
| Seagate ST2000DM001-1CH164 2TB   | 51       | 0.69%   |
| Samsung SSD 860 EVO 250GB        | 48       | 0.65%   |
| Samsung SSD 860 EVO 1TB          | 47       | 0.63%   |
| Crucial CT1000MX500SSD1 1TB      | 45       | 0.61%   |
| Seagate ST2000DM006-2DM164 2TB   | 41       | 0.55%   |
| Crucial CT480BX500SSD1 480GB     | 41       | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB   | 40       | 0.54%   |
| Kingston SA400S37120G 120GB SSD  | 40       | 0.54%   |
| WDC WD10EZEX-08WN4A0 1TB         | 38       | 0.51%   |
| Seagate ST3500418AS 500GB        | 38       | 0.51%   |
| Samsung NVMe SSD Drive 500GB     | 38       | 0.51%   |
| Samsung HD103SJ 1TB              | 38       | 0.51%   |
| PNY CS900 120GB SSD              | 38       | 0.51%   |
| Kingston SV300S37A120G 120GB SSD | 38       | 0.51%   |
| Unknown SD/MMC/MS PRO 64GB       | 35       | 0.47%   |
| Kingston SA400S37480G 480GB SSD  | 33       | 0.44%   |
| WDC WD20EZRX-00D8PB0 2TB         | 32       | 0.43%   |
| Samsung SSD 870 QVO 1TB          | 30       | 0.4%    |
| PNY CS900 240GB SSD              | 30       | 0.4%    |
| Toshiba HDWD110 1TB              | 29       | 0.39%   |
| Samsung SSD 860 QVO 1TB          | 29       | 0.39%   |
| Seagate ST31000524AS 1TB         | 28       | 0.38%   |
| WDC WD10EZEX-00BN5A0 1TB         | 27       | 0.36%   |
| Toshiba DT01ACA050 500GB         | 27       | 0.36%   |
| Seagate ST31000528AS 1TB         | 27       | 0.36%   |
| Seagate ST1000DM003-1SB102 1TB   | 27       | 0.36%   |
| WDC WD20EZRZ-00Z5HB0 2TB         | 26       | 0.35%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 1321     | 2119   | 39.15%  |
| WDC                 | 1077     | 1823   | 31.92%  |
| Toshiba             | 288      | 390    | 8.54%   |
| Samsung Electronics | 212      | 309    | 6.28%   |
| Hitachi             | 211      | 295    | 6.25%   |
| Maxtor              | 106      | 136    | 3.14%   |
| HGST                | 64       | 104    | 1.9%    |
| Unknown             | 38       | 45     | 1.13%   |
| Fujitsu             | 9        | 18     | 0.27%   |
| Hewlett-Packard     | 8        | 14     | 0.24%   |
| ASMT                | 6        | 8      | 0.18%   |
| Magnetic Data       | 5        | 5      | 0.15%   |
| ASMedia             | 4        | 6      | 0.12%   |
| USB3.0              | 3        | 3      | 0.09%   |
| LaCie               | 3        | 3      | 0.09%   |
| Inateck             | 3        | 3      | 0.09%   |
| ASMT109x            | 3        | 4      | 0.09%   |
| H/W                 | 2        | 10     | 0.06%   |
| Apple               | 2        | 2      | 0.06%   |
| Storeva             | 1        | 1      | 0.03%   |
| RSH-319             | 1        | 1      | 0.03%   |
| QEMU                | 1        | 1      | 0.03%   |
| PHD 3.0             | 1        | 1      | 0.03%   |
| MDT                 | 1        | 1      | 0.03%   |
| MARVELL             | 1        | 1      | 0.03%   |
| JMicron Technology  | 1        | 4      | 0.03%   |
| Intenso             | 1        | 2      | 0.03%   |
| ExcelStor           | 1        | 1      | 0.03%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 604      | 918    | 26.4%   |
| Crucial             | 455      | 659    | 19.89%  |
| Kingston            | 297      | 374    | 12.98%  |
| SanDisk             | 196      | 247    | 8.57%   |
| PNY                 | 105      | 132    | 4.59%   |
| WDC                 | 82       | 98     | 3.58%   |
| Intel               | 63       | 78     | 2.75%   |
| China               | 55       | 71     | 2.4%    |
| OCZ                 | 41       | 52     | 1.79%   |
| Transcend           | 33       | 41     | 1.44%   |
| LDLC                | 33       | 40     | 1.44%   |
| Corsair             | 30       | 33     | 1.31%   |
| SPCC                | 25       | 36     | 1.09%   |
| A-DATA Technology   | 21       | 24     | 0.92%   |
| SK hynix            | 19       | 25     | 0.83%   |
| Toshiba             | 18       | 26     | 0.79%   |
| Micron Technology   | 17       | 21     | 0.74%   |
| Emtec               | 14       | 17     | 0.61%   |
| LITEONIT            | 11       | 11     | 0.48%   |
| TEXTORM             | 10       | 11     | 0.44%   |
| Intenso             | 9        | 10     | 0.39%   |
| Patriot             | 8        | 13     | 0.35%   |
| JMicron Technology  | 8        | 13     | 0.35%   |
| Gigabyte Technology | 7        | 9      | 0.31%   |
| Unknown             | 7        | 10     | 0.31%   |
| Verbatim            | 6        | 6      | 0.26%   |
| Plextor             | 6        | 6      | 0.26%   |
| LITEON              | 6        | 6      | 0.26%   |
| KingSpec            | 6        | 8      | 0.26%   |
| SABRENT             | 5        | 5      | 0.22%   |
| KingDian            | 5        | 9      | 0.22%   |
| GOODRAM             | 5        | 7      | 0.22%   |
| GALAX               | 5        | 5      | 0.22%   |
| ASMT                | 5        | 7      | 0.22%   |
| TO Exter            | 4        | 4      | 0.17%   |
| Seagate             | 4        | 4      | 0.17%   |
| BAITITON            | 4        | 4      | 0.17%   |
| Apacer              | 4        | 4      | 0.17%   |
| TCSUNBOW            | 3        | 6      | 0.13%   |
| Integral            | 3        | 3      | 0.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 2539     | 5310   | 48.71%  |
| SSD     | 1870     | 3112   | 35.87%  |
| NVMe    | 678      | 1100   | 13.01%  |
| Unknown | 102      | 191    | 1.96%   |
| MMC     | 24       | 30     | 0.46%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 3203     | 8215   | 77.4%   |
| NVMe | 676      | 1091   | 16.34%  |
| SAS  | 235      | 407    | 5.68%   |
| MMC  | 24       | 30     | 0.58%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 2469     | 4564   | 51.17%  |
| 0.51-1.0   | 1352     | 2198   | 28.02%  |
| 1.01-2.0   | 573      | 945    | 11.88%  |
| 3.01-4.0   | 209      | 337    | 4.33%   |
| 2.01-3.0   | 133      | 204    | 2.76%   |
| 4.01-10.0  | 69       | 128    | 1.43%   |
| 10.01-20.0 | 20       | 46     | 0.41%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 775      | 21.07%  |
| 251-500        | 643      | 17.48%  |
| 501-1000       | 544      | 14.79%  |
| 1001-2000      | 452      | 12.29%  |
| More than 3000 | 336      | 9.13%   |
| 1-20           | 298      | 8.1%    |
| 2001-3000      | 205      | 5.57%   |
| Unknown        | 170      | 4.62%   |
| 51-100         | 164      | 4.46%   |
| 21-50          | 92       | 2.5%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 1191     | 31.57%  |
| 21-50          | 470      | 12.46%  |
| 101-250        | 430      | 11.4%   |
| 51-100         | 374      | 9.91%   |
| 501-1000       | 346      | 9.17%   |
| 251-500        | 341      | 9.04%   |
| 1001-2000      | 245      | 6.49%   |
| Unknown        | 170      | 4.51%   |
| More than 3000 | 121      | 3.21%   |
| 2001-3000      | 84       | 2.23%   |
| 0              | 1        | 0.03%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Desktops | Drives | Percent |
|-----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB   | 11       | 12     | 1.71%   |
| Seagate ST2000DM001-1CH164 2TB    | 8        | 9      | 1.24%   |
| Seagate ST31000528AS 1TB          | 7        | 7      | 1.09%   |
| Samsung Electronics HD103SJ 1TB   | 7        | 8      | 1.09%   |
| WDC WD10EADS-22M2B0 1TB           | 6        | 6      | 0.93%   |
| Seagate ST3250310AS 250GB         | 6        | 6      | 0.93%   |
| Seagate ST31000524AS 1TB          | 6        | 6      | 0.93%   |
| WDC WD6400AAKS-22A7B2 640GB       | 5        | 7      | 0.78%   |
| Toshiba DT01ACA100 1TB            | 5        | 6      | 0.78%   |
| Seagate ST2000DM001-1ER164 2TB    | 5        | 6      | 0.78%   |
| LDLC SSD 120GB                    | 5        | 5      | 0.78%   |
| WDC WD5000AAKX-001CA0 500GB       | 4        | 5      | 0.62%   |
| WDC WD3200AAKS-00L9A0 320GB       | 4        | 4      | 0.62%   |
| WDC WD10EARS-00Y5B1 1TB           | 4        | 5      | 0.62%   |
| WDC WD10EADS-65L5B1 1TB           | 4        | 4      | 0.62%   |
| WDC WD10EADS-00M2B0 1TB           | 4        | 6      | 0.62%   |
| Seagate ST3500418AS 500GB         | 4        | 4      | 0.62%   |
| Seagate ST3500320AS 500GB         | 4        | 4      | 0.62%   |
| Seagate ST3320820AS 320GB         | 4        | 4      | 0.62%   |
| Seagate ST250DM000-1BD141 250GB   | 4        | 4      | 0.62%   |
| Seagate ST2000DM001-9YN164 2TB    | 4        | 4      | 0.62%   |
| Seagate ST1000DM003-9YN162 1TB    | 4        | 5      | 0.62%   |
| Seagate ST1000DM003-1CH162 1TB    | 4        | 4      | 0.62%   |
| Samsung Electronics HD321KJ 320GB | 4        | 4      | 0.62%   |
| Samsung Electronics HD103UJ 1TB   | 4        | 5      | 0.62%   |
| Samsung Electronics HD103SI 1TB   | 4        | 4      | 0.62%   |
| Maxtor STM3500320AS 500GB         | 4        | 5      | 0.62%   |
| Maxtor STM3250310AS 250GB         | 4        | 6      | 0.62%   |
| Kingston SV300S37A120G 120GB SSD  | 4        | 6      | 0.62%   |
| Hitachi HDS721010CLA332 1TB       | 4        | 6      | 0.62%   |
| Crucial CT240M500SSD1 240GB       | 4        | 5      | 0.62%   |
| Crucial CT128MX100SSD1 128GB      | 4        | 4      | 0.62%   |
| WDC WD5000AAKX-22ERMA0 500GB      | 3        | 4      | 0.47%   |
| WDC WD5000AAKX-00ERMA0 500GB      | 3        | 3      | 0.47%   |
| WDC WD5000AADS-00S9B0 500GB       | 3        | 3      | 0.47%   |
| WDC WD3200AAJS-08L7A0 320GB       | 3        | 3      | 0.47%   |
| WDC WD20PURZ-85GU6Y0 2TB          | 3        | 3      | 0.47%   |
| WDC WD20EARX-00PASB0 2TB          | 3        | 3      | 0.47%   |
| WDC WD20EARS-00MVWB0 2TB          | 3        | 4      | 0.47%   |
| WDC WD10EZEX-21M2NA0 1TB          | 3        | 3      | 0.47%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 185      | 231    | 29.7%   |
| Seagate             | 171      | 200    | 27.45%  |
| Samsung Electronics | 55       | 64     | 8.83%   |
| Hitachi             | 39       | 47     | 6.26%   |
| Maxtor              | 35       | 39     | 5.62%   |
| Crucial             | 24       | 27     | 3.85%   |
| Toshiba             | 22       | 29     | 3.53%   |
| Kingston            | 17       | 21     | 2.73%   |
| Intel               | 15       | 16     | 2.41%   |
| HGST                | 9        | 12     | 1.44%   |
| OCZ                 | 7        | 8      | 1.12%   |
| LDLC                | 7        | 7      | 1.12%   |
| SanDisk             | 6        | 8      | 0.96%   |
| SK hynix            | 5        | 9      | 0.8%    |
| China               | 3        | 3      | 0.48%   |
| A-DATA Technology   | 3        | 3      | 0.48%   |
| SPCC                | 2        | 2      | 0.32%   |
| Micron Technology   | 2        | 2      | 0.32%   |
| LITEONIT            | 2        | 2      | 0.32%   |
| Hewlett-Packard     | 2        | 2      | 0.32%   |
| Fujitsu             | 2        | 2      | 0.32%   |
| Corsair             | 2        | 2      | 0.32%   |
| TEXTORM             | 1        | 1      | 0.16%   |
| OCZ-VERTEX          | 1        | 1      | 0.16%   |
| Netac               | 1        | 1      | 0.16%   |
| KingSpec            | 1        | 1      | 0.16%   |
| JMicron Technology  | 1        | 1      | 0.16%   |
| INNOVATION IT       | 1        | 1      | 0.16%   |
| ASMT                | 1        | 1      | 0.16%   |
| Apacer              | 1        | 1      | 0.16%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 182      | 228    | 36.18%  |
| Seagate             | 171      | 200    | 34%     |
| Samsung Electronics | 41       | 47     | 8.15%   |
| Hitachi             | 39       | 47     | 7.75%   |
| Maxtor              | 35       | 39     | 6.96%   |
| Toshiba             | 21       | 28     | 4.17%   |
| HGST                | 9        | 12     | 1.79%   |
| Hewlett-Packard     | 2        | 2      | 0.4%    |
| Fujitsu             | 2        | 2      | 0.4%    |
| ASMT                | 1        | 1      | 0.2%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 443      | 606    | 78.97%  |
| SSD     | 111      | 131    | 19.79%  |
| NVMe    | 6        | 6      | 1.07%   |
| Unknown | 1        | 1      | 0.18%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Desktops | Drives | Percent |
|--------------------------------------------------|----------|--------|---------|
| WDC WD4000FYYZ-01UL1B2 4TB                       | 1        | 1      | 7.69%   |
| WDC WD3200AAJS-22VWA0 320GB                      | 1        | 1      | 7.69%   |
| WDC WD20EARS-00MVWB0 2TB                         | 1        | 2      | 7.69%   |
| WDC WD20EARS-00J99B0 2TB                         | 1        | 2      | 7.69%   |
| WDC WD10EALX-759BA1 1TB                          | 1        | 1      | 7.69%   |
| Seagate ST3500418AS 500GB                        | 1        | 1      | 7.69%   |
| Seagate ST3250318AS 250GB                        | 1        | 1      | 7.69%   |
| Samsung Electronics SSD PM871 2.5 7mm 128GB      | 1        | 1      | 7.69%   |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 1        | 2      | 7.69%   |
| Samsung Electronics HD753LJ 752GB                | 1        | 1      | 7.69%   |
| Samsung Electronics HD501LJ 500GB                | 1        | 1      | 7.69%   |
| Kingston SMS200S360G 64GB SSD                    | 1        | 1      | 7.69%   |
| Intel SSDSC2KW256G8 256GB                        | 1        | 1      | 7.69%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 5        | 7      | 38.46%  |
| Samsung Electronics | 4        | 5      | 30.77%  |
| Seagate             | 2        | 2      | 15.38%  |
| Kingston            | 1        | 1      | 7.69%   |
| Intel               | 1        | 1      | 7.69%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Works    | 1806     | 4262   | 45.23%  |
| Detected | 1634     | 4721   | 40.92%  |
| Malfunc  | 540      | 744    | 13.52%  |
| Failed   | 13       | 16     | 0.33%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2284     | 48.59%  |
| AMD                              | 965      | 20.53%  |
| Samsung Electronics              | 288      | 6.13%   |
| Marvell Technology Group         | 149      | 3.17%   |
| ASMedia Technology               | 149      | 3.17%   |
| Nvidia                           | 141      | 3%      |
| JMicron Technology               | 132      | 2.81%   |
| Micron/Crucial Technology        | 103      | 2.19%   |
| Phison Electronics               | 101      | 2.15%   |
| SanDisk                          | 95       | 2.02%   |
| VIA Technologies                 | 51       | 1.08%   |
| Kingston Technology Company      | 47       | 1%      |
| Silicon Image                    | 19       | 0.4%    |
| Silicon Motion                   | 17       | 0.36%   |
| SK hynix                         | 16       | 0.34%   |
| Micron Technology                | 16       | 0.34%   |
| LSI Logic / Symbios Logic        | 16       | 0.34%   |
| Broadcom / LSI                   | 15       | 0.32%   |
| Toshiba America Info Systems     | 14       | 0.3%    |
| Seagate Technology               | 11       | 0.23%   |
| ADATA Technology                 | 9        | 0.19%   |
| Adaptec                          | 9        | 0.19%   |
| Silicon Integrated Systems [SiS] | 8        | 0.17%   |
| Integrated Technology Express    | 7        | 0.15%   |
| Shenzhen Longsys Electronics     | 5        | 0.11%   |
| Realtek Semiconductor            | 5        | 0.11%   |
| KIOXIA                           | 5        | 0.11%   |
| Hewlett-Packard                  | 5        | 0.11%   |
| Promise Technology               | 3        | 0.06%   |
| Union Memory (Shenzhen)          | 2        | 0.04%   |
| MAXIO Technology (Hangzhou)      | 2        | 0.04%   |
| Lite-On Technology               | 2        | 0.04%   |
| ULi Electronics                  | 1        | 0.02%   |
| Transcend                        | 1        | 0.02%   |
| Tekram Technology                | 1        | 0.02%   |
| Solidigm                         | 1        | 0.02%   |
| Red Hat                          | 1        | 0.02%   |
| OCZ Technology Group             | 1        | 0.02%   |
| Netac Technology                 | 1        | 0.02%   |
| Artop Electronic                 | 1        | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 542      | 9.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 291      | 4.88%   |
| AMD 400 Series Chipset SATA Controller                                                  | 216      | 3.62%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 188      | 3.15%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 181      | 3.04%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 171      | 2.87%   |
| Intel SATA Controller [RAID mode]                                                       | 167      | 2.8%    |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 156      | 2.62%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 151      | 2.53%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 135      | 2.27%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 133      | 2.23%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 131      | 2.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 130      | 2.18%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 120      | 2.01%   |
| AMD 500 Series Chipset SATA Controller                                                  | 118      | 1.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 115      | 1.93%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 98       | 1.64%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 90       | 1.51%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 83       | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 83       | 1.39%   |
| Nvidia MCP61 SATA Controller                                                            | 72       | 1.21%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 72       | 1.21%   |
| Nvidia MCP61 IDE                                                                        | 62       | 1.04%   |
| AMD FCH SATA Controller D                                                               | 59       | 0.99%   |
| Phison E12 NVMe Controller                                                              | 55       | 0.92%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 54       | 0.91%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                         | 51       | 0.86%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 51       | 0.86%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 51       | 0.86%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 48       | 0.81%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 44       | 0.74%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 43       | 0.72%   |
| Samsung NVMe SSD Controller 980                                                         | 41       | 0.69%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 40       | 0.67%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 40       | 0.67%   |
| AMD 300 Series Chipset SATA Controller                                                  | 37       | 0.62%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 36       | 0.6%    |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 35       | 0.59%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 35       | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 34       | 0.57%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 2605     | 56.79%  |
| IDE  | 962      | 20.97%  |
| NVMe | 683      | 14.89%  |
| RAID | 292      | 6.37%   |
| SAS  | 25       | 0.55%   |
| SCSI | 20       | 0.44%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Intel                 | 2341     | 68.13%  |
| AMD                   | 1091     | 31.75%  |
| CentaurHauls          | 2        | 0.06%   |
| Marvell Semiconductor | 1        | 0.03%   |
| ARM                   | 1        | 0.03%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 63       | 1.83%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 52       | 1.51%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 49       | 1.42%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 38       | 1.1%    |
| Intel Core i3-2120 CPU @ 3.30GHz            | 38       | 1.1%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 34       | 0.99%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 33       | 0.96%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 33       | 0.96%   |
| Intel Core i7-4790K CPU @ 4.00GHz           | 32       | 0.93%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 31       | 0.9%    |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 31       | 0.9%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 31       | 0.9%    |
| Intel Core i5-3470 CPU @ 3.20GHz            | 30       | 0.87%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 30       | 0.87%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 27       | 0.78%   |
| Intel Core i5-3570K CPU @ 3.40GHz           | 26       | 0.75%   |
| AMD FX-8350 Eight-Core Processor            | 26       | 0.75%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 25       | 0.72%   |
| Intel Core i5-8400 CPU @ 2.80GHz            | 25       | 0.72%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 23       | 0.67%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 23       | 0.67%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 23       | 0.67%   |
| Intel Core i7-6700 CPU @ 3.40GHz            | 22       | 0.64%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 22       | 0.64%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 22       | 0.64%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 22       | 0.64%   |
| AMD FX-6300 Six-Core Processor              | 22       | 0.64%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 21       | 0.61%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 21       | 0.61%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 21       | 0.61%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 21       | 0.61%   |
| Intel Core i7-8700 CPU @ 3.20GHz            | 20       | 0.58%   |
| Intel Core i5-7400 CPU @ 3.00GHz            | 20       | 0.58%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 20       | 0.58%   |
| Intel Core i5-4670K CPU @ 3.40GHz           | 20       | 0.58%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 19       | 0.55%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 19       | 0.55%   |
| Intel Core i3-6100 CPU @ 3.70GHz            | 19       | 0.55%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 19       | 0.55%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 19       | 0.55%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 691      | 20.05%  |
| Intel Core i7           | 468      | 13.58%  |
| AMD Ryzen 5             | 262      | 7.6%    |
| Intel Core i3           | 260      | 7.54%   |
| Intel Xeon              | 176      | 5.11%   |
| AMD Ryzen 7             | 173      | 5.02%   |
| Intel Core 2 Duo        | 120      | 3.48%   |
| Intel Pentium           | 101      | 2.93%   |
| AMD FX                  | 96       | 2.79%   |
| Intel Core 2 Quad       | 95       | 2.76%   |
| Intel Celeron           | 90       | 2.61%   |
| Other                   | 73       | 2.12%   |
| AMD Ryzen 9             | 68       | 1.97%   |
| Intel Pentium Dual-Core | 65       | 1.89%   |
| AMD Athlon II X2        | 62       | 1.8%    |
| AMD Ryzen 3             | 58       | 1.68%   |
| AMD Athlon 64 X2        | 49       | 1.42%   |
| Intel Atom              | 47       | 1.36%   |
| AMD Phenom II X4        | 41       | 1.19%   |
| Intel Pentium Dual      | 34       | 0.99%   |
| Intel Core 2            | 32       | 0.93%   |
| AMD A8                  | 31       | 0.9%    |
| Intel Pentium 4         | 30       | 0.87%   |
| AMD A4                  | 29       | 0.84%   |
| Intel Core i9           | 27       | 0.78%   |
| Intel Pentium D         | 21       | 0.61%   |
| AMD A6                  | 19       | 0.55%   |
| AMD Athlon 64           | 18       | 0.52%   |
| AMD Ryzen Threadripper  | 17       | 0.49%   |
| Intel Pentium Gold      | 16       | 0.46%   |
| AMD Athlon II X4        | 16       | 0.46%   |
| AMD A10                 | 15       | 0.44%   |
| AMD Sempron             | 14       | 0.41%   |
| AMD Phenom II X6        | 14       | 0.41%   |
| AMD Athlon              | 12       | 0.35%   |
| AMD E                   | 10       | 0.29%   |
| AMD Athlon X4           | 9        | 0.26%   |
| AMD Athlon Dual Core    | 9        | 0.26%   |
| AMD Ryzen 5 PRO         | 8        | 0.23%   |
| AMD Athlon II X3        | 8        | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 4       | 1410     | 40.81%  |
| 2       | 951      | 27.53%  |
| 6       | 474      | 13.72%  |
| 8       | 271      | 7.84%   |
| 1       | 124      | 3.59%   |
| 12      | 82       | 2.37%   |
| 3       | 50       | 1.45%   |
| 16      | 34       | 0.98%   |
| Unknown | 21       | 0.61%   |
| 10      | 17       | 0.49%   |
| 32      | 6        | 0.17%   |
| 24      | 4        | 0.12%   |
| 14      | 4        | 0.12%   |
| 64      | 3        | 0.09%   |
| 20      | 3        | 0.09%   |
| 40      | 1        | 0.03%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 3388     | 98.57%  |
| 2      | 47       | 1.37%   |
| 4      | 1        | 0.03%   |
| 0      | 1        | 0.03%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Desktops | Percent |
|---------|----------|---------|
| 2       | 1742     | 50.45%  |
| 1       | 1689     | 48.91%  |
| Unknown | 21       | 0.61%   |
| 4       | 1        | 0.03%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 3388     | 98.4%   |
| Unknown        | 29       | 0.84%   |
| 32-bit         | 26       | 0.76%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 703      | 19.71%  |
| 0x306c3    | 362      | 10.15%  |
| 0x206a7    | 214      | 6%      |
| 0x306a9    | 209      | 5.86%   |
| 0x1067a    | 179      | 5.02%   |
| 0x506e3    | 141      | 3.95%   |
| 0x906ea    | 103      | 2.89%   |
| 0x08701021 | 99       | 2.78%   |
| 0x010000c8 | 86       | 2.41%   |
| 0x906e9    | 79       | 2.21%   |
| 0x0800820d | 78       | 2.19%   |
| 0x06000852 | 54       | 1.51%   |
| 0x08701013 | 51       | 1.43%   |
| 0x06001119 | 50       | 1.4%    |
| 0x6fd      | 46       | 1.29%   |
| 0x106e5    | 43       | 1.21%   |
| 0x08108109 | 39       | 1.09%   |
| 0x10676    | 36       | 1.01%   |
| 0x6fb      | 34       | 0.95%   |
| 0xa0653    | 32       | 0.9%    |
| 0x906ed    | 32       | 0.9%    |
| 0x0a201016 | 32       | 0.9%    |
| 0xa0655    | 27       | 0.76%   |
| 0xa0671    | 26       | 0.73%   |
| 0x08001138 | 26       | 0.73%   |
| 0x306f2    | 25       | 0.7%    |
| 0x106a5    | 25       | 0.7%    |
| 0x206d7    | 22       | 0.62%   |
| 0x10677    | 19       | 0.53%   |
| 0x08001137 | 19       | 0.53%   |
| 0x906ec    | 18       | 0.5%    |
| 0x6f6      | 18       | 0.5%    |
| 0x20655    | 18       | 0.5%    |
| 0x906eb    | 16       | 0.45%   |
| 0x0a201009 | 16       | 0.45%   |
| 0x90672    | 15       | 0.42%   |
| 0x08600106 | 15       | 0.42%   |
| 0x08101016 | 15       | 0.42%   |
| 0x010000db | 15       | 0.42%   |
| 0x010000c7 | 15       | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 464      | 13.48%  |
| KabyLake         | 313      | 9.09%   |
| SandyBridge      | 274      | 7.96%   |
| Penryn           | 252      | 7.32%   |
| IvyBridge        | 248      | 7.21%   |
| Zen 2            | 221      | 6.42%   |
| Skylake          | 198      | 5.75%   |
| K10              | 169      | 4.91%   |
| Zen+             | 152      | 4.42%   |
| Piledriver       | 140      | 4.07%   |
| Core             | 126      | 3.66%   |
| Zen 3            | 114      | 3.31%   |
| Zen              | 103      | 2.99%   |
| K8 Hammer        | 91       | 2.64%   |
| Nehalem          | 86       | 2.5%    |
| CometLake        | 81       | 2.35%   |
| NetBurst         | 57       | 1.66%   |
| Westmere         | 55       | 1.6%    |
| Unknown          | 40       | 1.16%   |
| Bonnell          | 33       | 0.96%   |
| Silvermont       | 32       | 0.93%   |
| Broadwell        | 25       | 0.73%   |
| Icelake          | 22       | 0.64%   |
| Alderlake Hybrid | 22       | 0.64%   |
| Excavator        | 20       | 0.58%   |
| Goldmont plus    | 16       | 0.46%   |
| Steamroller      | 15       | 0.44%   |
| Bobcat           | 15       | 0.44%   |
| K10 Llano        | 14       | 0.41%   |
| Bulldozer        | 12       | 0.35%   |
| Puma             | 9        | 0.26%   |
| Goldmont         | 9        | 0.26%   |
| Jaguar           | 5        | 0.15%   |
| Tremont          | 4        | 0.12%   |
| K6               | 4        | 0.12%   |
| TigerLake        | 1        | 0.03%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Nvidia                                       | 1644     | 44.67%  |
| Intel                                        | 997      | 27.09%  |
| AMD                                          | 991      | 26.93%  |
| Matrox Electronics Systems                   | 16       | 0.43%   |
| ASPEED Technology                            | 16       | 0.43%   |
| VIA Technologies                             | 6        | 0.16%   |
| Silicon Integrated Systems [SiS]             | 5        | 0.14%   |
| ATI Technologies                             | 2        | 0.05%   |
| XGI Technology (eXtreme Graphics Innovation) | 1        | 0.03%   |
| S3 Graphics                                  | 1        | 0.03%   |
| Red Hat                                      | 1        | 0.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 193      | 5.09%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 111      | 2.93%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 99       | 2.61%   |
| Nvidia GK208B [GeForce GT 710]                                              | 96       | 2.53%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 85       | 2.24%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 82       | 2.16%   |
| Intel HD Graphics 530                                                       | 78       | 2.06%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 72       | 1.9%    |
| Nvidia GT218 [GeForce 210]                                                  | 68       | 1.79%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 60       | 1.58%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 55       | 1.45%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 54       | 1.42%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 52       | 1.37%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 49       | 1.29%   |
| Nvidia GK208B [GeForce GT 730]                                              | 49       | 1.29%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 45       | 1.19%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 43       | 1.13%   |
| Nvidia GF119 [GeForce GT 610]                                               | 39       | 1.03%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 39       | 1.03%   |
| Intel HD Graphics 630                                                       | 39       | 1.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 38       | 1%      |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                      | 32       | 0.84%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 31       | 0.82%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 30       | 0.79%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 28       | 0.74%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                           | 27       | 0.71%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 26       | 0.69%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 26       | 0.69%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                      | 26       | 0.69%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 25       | 0.66%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 24       | 0.63%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 24       | 0.63%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 23       | 0.61%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 22       | 0.58%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 22       | 0.58%   |
| AMD Renoir                                                                  | 22       | 0.58%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 22       | 0.58%   |
| AMD RS780L [Radeon 3000]                                                    | 21       | 0.55%   |
| AMD Juniper XT [Radeon HD 5770]                                             | 21       | 0.55%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                      | 20       | 0.53%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| 1 x Nvidia           | 1539     | 44.02%  |
| 1 x AMD              | 880      | 25.17%  |
| 1 x Intel            | 816      | 23.34%  |
| Intel + Nvidia       | 67       | 1.92%   |
| 2 x AMD              | 52       | 1.49%   |
| AMD + Nvidia         | 30       | 0.86%   |
| Intel + AMD          | 28       | 0.8%    |
| 2 x Nvidia           | 20       | 0.57%   |
| 1 x Matrox           | 14       | 0.4%    |
| 1 x ASPEED           | 13       | 0.37%   |
| 2 x Intel            | 8        | 0.23%   |
| 1 x VIA              | 6        | 0.17%   |
| Other                | 5        | 0.14%   |
| 1 x SiS              | 5        | 0.14%   |
| 3 x AMD              | 2        | 0.06%   |
| 3 x Nvidia           | 1        | 0.03%   |
| 2 x AMD + 1 x Nvidia | 1        | 0.03%   |
| 2 x AMD + 1 x ASPEED | 1        | 0.03%   |
| 1 x XGI              | 1        | 0.03%   |
| 1 x S3 Graphics      | 1        | 0.03%   |
| 1 x Red Hat          | 1        | 0.03%   |
| Nvidia + Matrox      | 1        | 0.03%   |
| Nvidia + ASPEED      | 1        | 0.03%   |
| Intel + 2 x Nvidia   | 1        | 0.03%   |
| Intel + 2 x AMD      | 1        | 0.03%   |
| AMD + ASPEED         | 1        | 0.03%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 2482     | 70.51%  |
| Proprietary | 851      | 24.18%  |
| Unknown     | 187      | 5.31%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 1296     | 36.35%  |
| 1.01-2.0   | 546      | 15.32%  |
| 0.01-0.5   | 476      | 13.35%  |
| 0.51-1.0   | 472      | 13.24%  |
| 3.01-4.0   | 278      | 7.8%    |
| 7.01-8.0   | 231      | 6.48%   |
| 5.01-6.0   | 120      | 3.37%   |
| 8.01-16.0  | 85       | 2.38%   |
| 2.01-3.0   | 45       | 1.26%   |
| 16.01-24.0 | 11       | 0.31%   |
| 4.01-5.0   | 5        | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 579      | 15.65%  |
| Iiyama               | 372      | 10.06%  |
| Dell                 | 314      | 8.49%   |
| Hewlett-Packard      | 291      | 7.87%   |
| Acer                 | 251      | 6.79%   |
| Goldstar             | 249      | 6.73%   |
| Ancor Communications | 222      | 6%      |
| Philips              | 206      | 5.57%   |
| AOC                  | 166      | 4.49%   |
| BenQ                 | 142      | 3.84%   |
| ViewSonic            | 81       | 2.19%   |
| ASUSTek Computer     | 59       | 1.6%    |
| Lenovo               | 50       | 1.35%   |
| Unknown              | 43       | 1.16%   |
| Idek Iiyama          | 36       | 0.97%   |
| Sony                 | 35       | 0.95%   |
| HannStar             | 34       | 0.92%   |
| LG Electronics       | 32       | 0.87%   |
| Packard Bell         | 29       | 0.78%   |
| NEC Computers        | 24       | 0.65%   |
| Eizo                 | 22       | 0.59%   |
| Vestel Elektronik    | 20       | 0.54%   |
| Hitachi              | 19       | 0.51%   |
| Medion               | 18       | 0.49%   |
| Fujitsu Siemens      | 18       | 0.49%   |
| Denver               | 18       | 0.49%   |
| SNC                  | 17       | 0.46%   |
| MSI                  | 15       | 0.41%   |
| Hyundai ImageQuest   | 15       | 0.41%   |
| HKC                  | 13       | 0.35%   |
| Toshiba              | 11       | 0.3%    |
| Belinea              | 11       | 0.3%    |
| Unknown              | 11       | 0.3%    |
| NECCI                | 10       | 0.27%   |
| RTK                  | 9        | 0.24%   |
| RS                   | 9        | 0.24%   |
| Panasonic            | 9        | 0.24%   |
| Plain Tree Systems   | 8        | 0.22%   |
| Gigabyte Technology  | 8        | 0.22%   |
| Apple                | 6        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| Iiyama PLE2483H IVM6113 1920x1080 531x299mm 24.0-inch                 | 34       | 0.86%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 22       | 0.56%   |
| Vestel Elektronik 43UHD_LCD_TV VES3700 3840x2160 950x540mm 43.0-inch  | 20       | 0.51%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 19       | 0.48%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch     | 16       | 0.4%    |
| Iiyama PLE2283H IVM562E 1920x1080 477x268mm 21.5-inch                 | 15       | 0.38%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                     | 15       | 0.38%   |
| ViewSonic VX2457 VSCB931 1920x1080 521x293mm 23.5-inch                | 13       | 0.33%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 13       | 0.33%   |
| AOC 24B1W1 AOC2401 1920x1080 527x296mm 23.8-inch                      | 12       | 0.3%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch | 12       | 0.3%    |
| Iiyama PLX2783H IVM6611 1920x1080 598x336mm 27.0-inch                 | 11       | 0.28%   |
| Iiyama PL2409HD IVM560C 1920x1080 521x293mm 23.5-inch                 | 11       | 0.28%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 11       | 0.28%   |
| Unknown                                                               | 11       | 0.28%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch               | 10       | 0.25%   |
| Iiyama PL2530H IVM6132 1920x1080 544x303mm 24.5-inch                  | 10       | 0.25%   |
| Hewlett-Packard v220 HWP26FE 1680x1050 473x296mm 22.0-inch            | 10       | 0.25%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 10       | 0.25%   |
| AOC 27P2DG5 AOC2702 1920x1080 598x336mm 27.0-inch                     | 10       | 0.25%   |
| Ancor Communications VE247 ACI2493 1920x1080 531x299mm 24.0-inch      | 10       | 0.25%   |
| Acer G246HL ACR02FF 1920x1080 531x299mm 24.0-inch                     | 10       | 0.25%   |
| Samsung Electronics SyncMaster SAM0304 1680x1050 494x320mm 23.2-inch  | 9        | 0.23%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch     | 9        | 0.23%   |
| Iiyama X2483/2481 IVM6128 1920x1080 527x296mm 23.8-inch               | 9        | 0.23%   |
| Iiyama PLB2403WS IVM5601 1920x1200 519x324mm 24.1-inch                | 9        | 0.23%   |
| Iiyama PL2492H IVM612F 1920x1080 530x300mm 24.0-inch                  | 9        | 0.23%   |
| AOC V22 AOC2200 1680x1050 526x296mm 23.8-inch                         | 9        | 0.23%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 9        | 0.23%   |
| Ancor Communications VX238 ACI23C1 1920x1080 510x290mm 23.1-inch      | 9        | 0.23%   |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch | 9        | 0.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 8        | 0.2%    |
| Iiyama PL2776HD IVM6605 1920x1080 598x336mm 27.0-inch                 | 8        | 0.2%    |
| Iiyama PL2530H IVM6133 1920x1080 544x303mm 24.5-inch                  | 8        | 0.2%    |
| Hewlett-Packard S2231 HWP2905 1920x1080 477x268mm 21.5-inch           | 8        | 0.2%    |
| Ancor Communications ASUS VW193D ACI19D5 1440x900 408x255mm 18.9-inch | 8        | 0.2%    |
| Ancor Communications ASUS VP228 ACI22C3 1920x1080 476x268mm 21.5-inch | 8        | 0.2%    |
| Ancor Communications ASUS VE278 ACI27F6 1920x1080 598x336mm 27.0-inch | 8        | 0.2%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 7        | 0.18%   |
| Iiyama PLX2783H IVM6648 1920x1080 598x336mm 27.0-inch                 | 7        | 0.18%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 1715     | 47.4%   |
| 1680x1050 (WSXGA+) | 299      | 8.26%   |
| 1280x1024 (SXGA)   | 299      | 8.26%   |
| 2560x1440 (QHD)    | 248      | 6.85%   |
| 3840x2160 (4K)     | 214      | 5.91%   |
| 1440x900 (WXGA+)   | 149      | 4.12%   |
| 1920x1200 (WUXGA)  | 131      | 3.62%   |
| Unknown            | 104      | 2.87%   |
| 1600x900 (HD+)     | 81       | 2.24%   |
| 1366x768 (WXGA)    | 55       | 1.52%   |
| 1360x768           | 46       | 1.27%   |
| 3840x1080          | 45       | 1.24%   |
| 3440x1440          | 39       | 1.08%   |
| 2560x1080          | 34       | 0.94%   |
| 1600x1200          | 23       | 0.64%   |
| 1024x768 (XGA)     | 19       | 0.53%   |
| 2288x1287          | 9        | 0.25%   |
| 1920x540           | 9        | 0.25%   |
| 4480x1440          | 7        | 0.19%   |
| 3200x1080          | 7        | 0.19%   |
| 3840x1600          | 6        | 0.17%   |
| 3600x1080          | 6        | 0.17%   |
| 5760x1080          | 5        | 0.14%   |
| 2560x1600          | 5        | 0.14%   |
| 1280x960           | 4        | 0.11%   |
| 5760x2160          | 3        | 0.08%   |
| 5760x1200          | 3        | 0.08%   |
| 2560x1024          | 3        | 0.08%   |
| 2048x1152          | 3        | 0.08%   |
| 1280x768           | 3        | 0.08%   |
| 1280x720 (HD)      | 3        | 0.08%   |
| 7680x2160          | 2        | 0.06%   |
| 3360x1050          | 2        | 0.06%   |
| 3280x1080          | 2        | 0.06%   |
| 3200x1200          | 2        | 0.06%   |
| 3120x1050          | 2        | 0.06%   |
| 2960x1050          | 2        | 0.06%   |
| 720x480            | 1        | 0.03%   |
| 6720x2160          | 1        | 0.03%   |
| 6400x2160          | 1        | 0.03%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 550      | 14.97%  |
| 24      | 528      | 14.37%  |
| 27      | 491      | 13.36%  |
| 21      | 420      | 11.43%  |
| Unknown | 362      | 9.85%   |
| 19      | 279      | 7.59%   |
| 22      | 194      | 5.28%   |
| 17      | 151      | 4.11%   |
| 20      | 124      | 3.37%   |
| 18      | 94       | 2.56%   |
| 31      | 85       | 2.31%   |
| 34      | 59       | 1.61%   |
| 84      | 41       | 1.12%   |
| 40      | 31       | 0.84%   |
| 25      | 31       | 0.84%   |
| 32      | 30       | 0.82%   |
| 15      | 29       | 0.79%   |
| 72      | 28       | 0.76%   |
| 54      | 17       | 0.46%   |
| 33      | 17       | 0.46%   |
| 65      | 9        | 0.24%   |
| 46      | 9        | 0.24%   |
| 48      | 8        | 0.22%   |
| 29      | 8        | 0.22%   |
| 142     | 7        | 0.19%   |
| 26      | 7        | 0.19%   |
| 12      | 7        | 0.19%   |
| 42      | 6        | 0.16%   |
| 52      | 5        | 0.14%   |
| 38      | 5        | 0.14%   |
| 36      | 5        | 0.14%   |
| 35      | 5        | 0.14%   |
| 49      | 4        | 0.11%   |
| 37      | 4        | 0.11%   |
| 16      | 4        | 0.11%   |
| 47      | 3        | 0.08%   |
| 39      | 3        | 0.08%   |
| 28      | 3        | 0.08%   |
| 14      | 3        | 0.08%   |
| 75      | 1        | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 1424     | 40.25%  |
| 401-500        | 941      | 26.6%   |
| Unknown        | 362      | 10.23%  |
| 301-350        | 174      | 4.92%   |
| 351-400        | 172      | 4.86%   |
| 601-700        | 151      | 4.27%   |
| 701-800        | 112      | 3.17%   |
| 1501-2000      | 70       | 1.98%   |
| 1001-1500      | 60       | 1.7%    |
| 801-900        | 48       | 1.36%   |
| 201-300        | 10       | 0.28%   |
| More than 2000 | 7        | 0.2%    |
| 901-1000       | 7        | 0.2%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 2071     | 60.61%  |
| 16/10   | 543      | 15.89%  |
| Unknown | 320      | 9.36%   |
| 5/4     | 278      | 8.14%   |
| 21/9    | 73       | 2.14%   |
| 4/3     | 57       | 1.67%   |
| 3/2     | 35       | 1.02%   |
| 6/5     | 18       | 0.53%   |
| 32/9    | 10       | 0.29%   |
| 1.00    | 7        | 0.2%    |
| 11/10   | 2        | 0.06%   |
| 2.00    | 1        | 0.03%   |
| 1.03    | 1        | 0.03%   |
| 0.56    | 1        | 0.03%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 1359     | 37.98%  |
| 151-200        | 536      | 14.98%  |
| 301-350        | 500      | 13.97%  |
| Unknown        | 362      | 10.12%  |
| 351-500        | 197      | 5.51%   |
| 251-300        | 194      | 5.42%   |
| 141-150        | 189      | 5.28%   |
| More than 1000 | 116      | 3.24%   |
| 501-1000       | 78       | 2.18%   |
| 101-110        | 25       | 0.7%    |
| 71-80          | 7        | 0.2%    |
| 131-140        | 5        | 0.14%   |
| 121-130        | 4        | 0.11%   |
| 111-120        | 4        | 0.11%   |
| 81-90          | 2        | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 2225     | 65.13%  |
| 101-120 | 597      | 17.48%  |
| Unknown | 362      | 10.6%   |
| 121-160 | 110      | 3.22%   |
| 1-50    | 91       | 2.66%   |
| 161-240 | 31       | 0.91%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2626     | 74.77%  |
| 2     | 608      | 17.31%  |
| 0     | 220      | 6.26%   |
| 3     | 55       | 1.57%   |
| 4     | 3        | 0.09%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Realtek Semiconductor            | 2081     | 43.78%  |
| Intel                            | 1310     | 27.56%  |
| Qualcomm Atheros                 | 333      | 7.01%   |
| Broadcom                         | 158      | 3.32%   |
| Nvidia                           | 107      | 2.25%   |
| TP-Link                          | 76       | 1.6%    |
| Marvell Technology Group         | 69       | 1.45%   |
| Ralink                           | 62       | 1.3%    |
| Ralink Technology                | 59       | 1.24%   |
| NetGear                          | 57       | 1.2%    |
| Broadcom Limited                 | 37       | 0.78%   |
| D-Link System                    | 35       | 0.74%   |
| MediaTek                         | 28       | 0.59%   |
| Samsung Electronics              | 25       | 0.53%   |
| Aquantia                         | 23       | 0.48%   |
| VIA Technologies                 | 22       | 0.46%   |
| D-Link                           | 22       | 0.46%   |
| Microsoft                        | 20       | 0.42%   |
| Belkin Components                | 19       | 0.4%    |
| Qualcomm Atheros Communications  | 16       | 0.34%   |
| ASIX Electronics                 | 13       | 0.27%   |
| Guillemot                        | 12       | 0.25%   |
| Xiaomi                           | 9        | 0.19%   |
| ASUSTek Computer                 | 9        | 0.19%   |
| Huawei Technologies              | 8        | 0.17%   |
| Edimax Technology                | 8        | 0.17%   |
| Google                           | 7        | 0.15%   |
| IMC Networks                     | 5        | 0.11%   |
| TRENDnet                         | 4        | 0.08%   |
| Silicon Integrated Systems [SiS] | 4        | 0.08%   |
| Sagem                            | 4        | 0.08%   |
| Qualcomm                         | 4        | 0.08%   |
| OPPO Electronics                 | 4        | 0.08%   |
| OnePlus Technology (Shenzhen)    | 4        | 0.08%   |
| JMicron Technology               | 4        | 0.08%   |
| Gemtek                           | 4        | 0.08%   |
| 3Com                             | 4        | 0.08%   |
| STMicroelectronics               | 3        | 0.06%   |
| QLogic                           | 3        | 0.06%   |
| Motorola PCS                     | 3        | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1683     | 31.69%  |
| Realtek RTL8125 2.5GbE Controller                                 | 145      | 2.73%   |
| Intel I211 Gigabit Network Connection                             | 134      | 2.52%   |
| Intel Ethernet Connection (2) I219-V                              | 131      | 2.47%   |
| Intel Wi-Fi 6 AX200                                               | 125      | 2.35%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 123      | 2.32%   |
| Intel Ethernet Connection I217-LM                                 | 86       | 1.62%   |
| Intel 82579V Gigabit Network Connection                           | 77       | 1.45%   |
| Intel Ethernet Connection (7) I219-V                              | 67       | 1.26%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 59       | 1.11%   |
| Nvidia MCP61 Ethernet                                             | 54       | 1.02%   |
| Intel Ethernet Connection (2) I218-V                              | 52       | 0.98%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 50       | 0.94%   |
| Intel Ethernet Controller I225-V                                  | 50       | 0.94%   |
| Intel Ethernet Connection (2) I219-LM                             | 49       | 0.92%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 46       | 0.87%   |
| Intel Ethernet Connection I217-V                                  | 41       | 0.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 39       | 0.73%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39       | 0.73%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 38       | 0.72%   |
| Intel Wireless-AC 9260                                            | 38       | 0.72%   |
| Intel 82574L Gigabit Network Connection                           | 38       | 0.72%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 36       | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 32       | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30       | 0.56%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 29       | 0.55%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 29       | 0.55%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 28       | 0.53%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 27       | 0.51%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 27       | 0.51%   |
| Intel I210 Gigabit Network Connection                             | 26       | 0.49%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                  | 25       | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25       | 0.47%   |
| Intel Wireless 3165                                               | 25       | 0.47%   |
| Intel Ethernet Connection (7) I219-LM                             | 25       | 0.47%   |
| Realtek 802.11ac NIC                                              | 24       | 0.45%   |
| Ralink MT7601U Wireless Adapter                                   | 24       | 0.45%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 23       | 0.43%   |
| Intel Wireless 7260                                               | 23       | 0.43%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 21       | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Intel                                 | 384      | 27.12%  |
| Realtek Semiconductor                 | 364      | 25.71%  |
| Qualcomm Atheros                      | 174      | 12.29%  |
| TP-Link                               | 74       | 5.23%   |
| Ralink                                | 62       | 4.38%   |
| Ralink Technology                     | 59       | 4.17%   |
| NetGear                               | 56       | 3.95%   |
| Broadcom                              | 50       | 3.53%   |
| MediaTek                              | 22       | 1.55%   |
| D-Link                                | 22       | 1.55%   |
| Microsoft                             | 20       | 1.41%   |
| Belkin Components                     | 19       | 1.34%   |
| D-Link System                         | 17       | 1.2%    |
| Qualcomm Atheros Communications       | 16       | 1.13%   |
| Guillemot                             | 12       | 0.85%   |
| Broadcom Limited                      | 10       | 0.71%   |
| ASUSTek Computer                      | 9        | 0.64%   |
| Edimax Technology                     | 8        | 0.56%   |
| IMC Networks                          | 5        | 0.35%   |
| TRENDnet                              | 4        | 0.28%   |
| Sagem                                 | 4        | 0.28%   |
| Gemtek                                | 4        | 0.28%   |
| Marvell Technology Group              | 3        | 0.21%   |
| Toshiba                               | 2        | 0.14%   |
| Realtek                               | 2        | 0.14%   |
| Linksys                               | 2        | 0.14%   |
| Fujitsu Siemens Computers             | 2        | 0.14%   |
| Accton Technology                     | 2        | 0.14%   |
| ZyDAS                                 | 1        | 0.07%   |
| Z-Com                                 | 1        | 0.07%   |
| Yoctopuce Sarl                        | 1        | 0.07%   |
| Wilocity                              | 1        | 0.07%   |
| Wacom                                 | 1        | 0.07%   |
| Micro Star International              | 1        | 0.07%   |
| BUFFALO                               | 1        | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.07%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                            | 125      | 8.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 39       | 2.73%   |
| Intel Wireless-AC 9260                                         | 38       | 2.66%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 36       | 2.52%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 32       | 2.24%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 29       | 2.03%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 29       | 2.03%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 27       | 1.89%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 27       | 1.89%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter               | 25       | 1.75%   |
| Intel Wireless 3165                                            | 25       | 1.75%   |
| Realtek 802.11ac NIC                                           | 24       | 1.68%   |
| Ralink MT7601U Wireless Adapter                                | 24       | 1.68%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 23       | 1.61%   |
| Intel Wireless 7260                                            | 23       | 1.61%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 20       | 1.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 20       | 1.4%    |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                     | 19       | 1.33%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                         | 19       | 1.33%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 19       | 1.33%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 18       | 1.26%   |
| Intel Wireless 7265                                            | 18       | 1.26%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter             | 17       | 1.19%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                | 16       | 1.12%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter       | 15       | 1.05%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                        | 15       | 1.05%   |
| Intel Wireless 8260                                            | 15       | 1.05%   |
| Realtek RTL8188EE Wireless Network Adapter                     | 14       | 0.98%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 14       | 0.98%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter             | 14       | 0.98%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 13       | 0.91%   |
| Qualcomm Atheros AR9271 802.11n                                | 13       | 0.91%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter     | 13       | 0.91%   |
| NetGear A6210                                                  | 13       | 0.91%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 13       | 0.91%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                         | 12       | 0.84%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 12       | 0.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 12       | 0.84%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                         | 11       | 0.77%   |
| Ralink RT5370 Wireless Adapter                                 | 11       | 0.77%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 1946     | 52.58%  |
| Intel                             | 1092     | 29.51%  |
| Qualcomm Atheros                  | 176      | 4.76%   |
| Broadcom                          | 108      | 2.92%   |
| Nvidia                            | 107      | 2.89%   |
| Marvell Technology Group          | 66       | 1.78%   |
| Broadcom Limited                  | 27       | 0.73%   |
| Aquantia                          | 23       | 0.62%   |
| Samsung Electronics               | 21       | 0.57%   |
| VIA Technologies                  | 20       | 0.54%   |
| D-Link System                     | 18       | 0.49%   |
| ASIX Electronics                  | 13       | 0.35%   |
| Xiaomi                            | 9        | 0.24%   |
| Huawei Technologies               | 8        | 0.22%   |
| Google                            | 7        | 0.19%   |
| MediaTek                          | 5        | 0.14%   |
| Qualcomm                          | 4        | 0.11%   |
| OPPO Electronics                  | 4        | 0.11%   |
| OnePlus Technology (Shenzhen)     | 4        | 0.11%   |
| JMicron Technology                | 4        | 0.11%   |
| 3Com                              | 4        | 0.11%   |
| Silicon Integrated Systems [SiS]  | 3        | 0.08%   |
| QLogic                            | 3        | 0.08%   |
| Motorola PCS                      | 3        | 0.08%   |
| HTC (High Tech Computer)          | 3        | 0.08%   |
| TP-Link                           | 2        | 0.05%   |
| Mellanox Technologies             | 2        | 0.05%   |
| ICS Advent                        | 2        | 0.05%   |
| DisplayLink                       | 2        | 0.05%   |
| Tehuti Networks                   | 1        | 0.03%   |
| Sundance Technology Inc / IC Plus | 1        | 0.03%   |
| Spreadtrum Communications         | 1        | 0.03%   |
| NetGear                           | 1        | 0.03%   |
| Netchip Technology                | 1        | 0.03%   |
| National Semiconductor            | 1        | 0.03%   |
| MYRICOM                           | 1        | 0.03%   |
| Linksys                           | 1        | 0.03%   |
| Lenovo                            | 1        | 0.03%   |
| Intellon                          | 1        | 0.03%   |
| Insyde Software                   | 1        | 0.03%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 1683     | 43.92%  |
| Realtek RTL8125 2.5GbE Controller                                 | 145      | 3.78%   |
| Intel I211 Gigabit Network Connection                             | 134      | 3.5%    |
| Intel Ethernet Connection (2) I219-V                              | 131      | 3.42%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 123      | 3.21%   |
| Intel Ethernet Connection I217-LM                                 | 86       | 2.24%   |
| Intel 82579V Gigabit Network Connection                           | 77       | 2.01%   |
| Intel Ethernet Connection (7) I219-V                              | 67       | 1.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 59       | 1.54%   |
| Nvidia MCP61 Ethernet                                             | 54       | 1.41%   |
| Intel Ethernet Connection (2) I218-V                              | 52       | 1.36%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 50       | 1.3%    |
| Intel Ethernet Controller I225-V                                  | 50       | 1.3%    |
| Intel Ethernet Connection (2) I219-LM                             | 49       | 1.28%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 46       | 1.2%    |
| Intel Ethernet Connection I217-V                                  | 41       | 1.07%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 39       | 1.02%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 38       | 0.99%   |
| Intel 82574L Gigabit Network Connection                           | 38       | 0.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 30       | 0.78%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 28       | 0.73%   |
| Intel I210 Gigabit Network Connection                             | 26       | 0.68%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 25       | 0.65%   |
| Intel Ethernet Connection (7) I219-LM                             | 25       | 0.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 21       | 0.55%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                  | 21       | 0.55%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 18       | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 18       | 0.47%   |
| Intel Ethernet Connection (5) I219-LM                             | 17       | 0.44%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 16       | 0.42%   |
| D-Link System DGE-528T Gigabit Ethernet Adapter                   | 15       | 0.39%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 14       | 0.37%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                 | 14       | 0.37%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                        | 12       | 0.31%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 12       | 0.31%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 12       | 0.31%   |
| Nvidia MCP77 Ethernet                                             | 12       | 0.31%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 12       | 0.31%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 12       | 0.31%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 12       | 0.31%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 3415     | 71.22%  |
| WiFi     | 1332     | 27.78%  |
| Modem    | 39       | 0.81%   |
| Unknown  | 9        | 0.19%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 2874     | 80.35%  |
| WiFi     | 703      | 19.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 2303     | 66.39%  |
| 2     | 1010     | 29.12%  |
| 3     | 103      | 2.97%   |
| 0     | 22       | 0.63%   |
| 4     | 17       | 0.49%   |
| 5     | 7        | 0.2%    |
| 7     | 3        | 0.09%   |
| 6     | 2        | 0.06%   |
| 9     | 1        | 0.03%   |
| 8     | 1        | 0.03%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 2166     | 61.08%  |
| Yes  | 1380     | 38.92%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 339      | 36.73%  |
| Cambridge Silicon Radio         | 265      | 28.71%  |
| ASUSTek Computer                | 75       | 8.13%   |
| Realtek Semiconductor           | 59       | 6.39%   |
| Broadcom                        | 38       | 4.12%   |
| IMC Networks                    | 33       | 3.58%   |
| Qualcomm Atheros Communications | 26       | 2.82%   |
| Belkin Components               | 19       | 2.06%   |
| TP-Link                         | 13       | 1.41%   |
| MediaTek                        | 13       | 1.41%   |
| Apple                           | 10       | 1.08%   |
| Lite-On Technology              | 6        | 0.65%   |
| Integrated System Solution      | 5        | 0.54%   |
| Foxconn / Hon Hai               | 4        | 0.43%   |
| HTC (High Tech Computer)        | 3        | 0.33%   |
| Realtek                         | 2        | 0.22%   |
| TRENDnet                        | 1        | 0.11%   |
| Toshiba                         | 1        | 0.11%   |
| Micro Star International        | 1        | 0.11%   |
| Logitech                        | 1        | 0.11%   |
| Kensington                      | 1        | 0.11%   |
| Fujitsu                         | 1        | 0.11%   |
| Edimax Technology               | 1        | 0.11%   |
| Dell                            | 1        | 0.11%   |
| D-Link System                   | 1        | 0.11%   |
| D-Link                          | 1        | 0.11%   |
| Creative Technology             | 1        | 0.11%   |
| Conwise Technology              | 1        | 0.11%   |
| Com One                         | 1        | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                | Desktops | Percent |
|----------------------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                  | 265      | 28.71%  |
| Intel AX200 Bluetooth                                                | 110      | 11.92%  |
| Intel Bluetooth wireless interface                                   | 81       | 8.78%   |
| Realtek Bluetooth Radio                                              | 46       | 4.98%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                             | 37       | 4.01%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                       | 31       | 3.36%   |
| Intel Wireless-AC 3168 Bluetooth                                     | 30       | 3.25%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                   | 23       | 2.49%   |
| IMC Networks Bluetooth Radio                                         | 22       | 2.38%   |
| Intel AX201 Bluetooth                                                | 21       | 2.28%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                    | 21       | 2.28%   |
| Intel AX210 Bluetooth                                                | 17       | 1.84%   |
| Qualcomm Atheros AR3011 Bluetooth                                    | 14       | 1.52%   |
| TP-Link UB500 Adapter                                                | 13       | 1.41%   |
| MediaTek Wireless_Device                                             | 13       | 1.41%   |
| ASUS Qualcomm Bluetooth 4.1                                          | 11       | 1.19%   |
| Realtek  Bluetooth 4.2 Adapter                                       | 10       | 1.08%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter                | 10       | 1.08%   |
| ASUS Bluetooth Adapter                                               | 10       | 1.08%   |
| ASUS ASUS USB-BT500                                                  | 10       | 1.08%   |
| ASUS Bluetooth Radio                                                 | 9        | 0.98%   |
| ASUS BCM20702A0                                                      | 8        | 0.87%   |
| Intel Centrino Bluetooth Wireless Transceiver                        | 6        | 0.65%   |
| Intel Bluetooth Device                                               | 6        | 0.65%   |
| Belkin Components Bluetooth Mini Dongle                              | 6        | 0.65%   |
| IMC Networks Bluetooth Device                                        | 5        | 0.54%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                               | 4        | 0.43%   |
| Qualcomm Atheros Bluetooth USB Host Controller                       | 4        | 0.43%   |
| Qualcomm Atheros  Bluetooth Device                                   | 3        | 0.33%   |
| Integrated System Solution Bluetooth Device                          | 3        | 0.33%   |
| IMC Networks BCM20702A0                                              | 3        | 0.33%   |
| HTC (High Tech Computer) Vive Hub Bluetooth 4.1 (Broadcom BCM920703) | 3        | 0.33%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter                     | 3        | 0.33%   |
| Broadcom BCM2045 Bluetooth                                           | 3        | 0.33%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                 | 3        | 0.33%   |
| Apple Bluetooth Host Controller                                      | 3        | 0.33%   |
| Realtek Bluetooth 5.1 Radio                                          | 2        | 0.22%   |
| Realtek Bluetooth Radio                                              | 2        | 0.22%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                           | 2        | 0.22%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                | 2        | 0.22%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Desktops | Percent |
|----------------------------------|----------|---------|
| Intel                            | 2183     | 37.03%  |
| Nvidia                           | 1529     | 25.93%  |
| AMD                              | 1339     | 22.71%  |
| C-Media Electronics              | 141      | 2.39%   |
| Logitech                         | 82       | 1.39%   |
| Creative Labs                    | 80       | 1.36%   |
| VIA Technologies                 | 35       | 0.59%   |
| Texas Instruments                | 32       | 0.54%   |
| Corsair                          | 30       | 0.51%   |
| Kingston Technology              | 29       | 0.49%   |
| GN Netcom                        | 28       | 0.47%   |
| Focusrite-Novation               | 27       | 0.46%   |
| JMTek                            | 20       | 0.34%   |
| Generalplus Technology           | 20       | 0.34%   |
| SteelSeries ApS                  | 19       | 0.32%   |
| Razer USA                        | 19       | 0.32%   |
| Plantronics                      | 16       | 0.27%   |
| ASUSTek Computer                 | 15       | 0.25%   |
| Sennheiser Communications        | 12       | 0.2%    |
| XMOS                             | 11       | 0.19%   |
| Creative Technology              | 9        | 0.15%   |
| Silicon Integrated Systems [SiS] | 8        | 0.14%   |
| M-Audio                          | 8        | 0.14%   |
| DSEA A/S                         | 8        | 0.14%   |
| Ensoniq                          | 7        | 0.12%   |
| BEHRINGER International          | 7        | 0.12%   |
| Turtle Beach                     | 6        | 0.1%    |
| Tenx Technology                  | 6        | 0.1%    |
| Sony                             | 6        | 0.1%    |
| RODE Microphones                 | 6        | 0.1%    |
| Micro Star International         | 6        | 0.1%    |
| GYROCOM C&C                      | 6        | 0.1%    |
| Yamaha                           | 5        | 0.08%   |
| PreSonus Audio Electronics       | 5        | 0.08%   |
| AKAI Professional M.I.           | 5        | 0.08%   |
| Realtek Semiconductor            | 4        | 0.07%   |
| Medeli Electronics               | 4        | 0.07%   |
| Dell                             | 4        | 0.07%   |
| Alesis                           | 4        | 0.07%   |
| Trust                            | 3        | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                             | Desktops | Percent |
|-----------------------------------------------------------------------------------|----------|---------|
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller               | 315      | 4.7%    |
| AMD Starship/Matisse HD Audio Controller                                          | 276      | 4.11%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller        | 274      | 4.08%   |
| AMD SBx00 Azalia (Intel HDA)                                                      | 230      | 3.43%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                  | 219      | 3.26%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                   | 191      | 2.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller               | 190      | 2.83%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                               | 173      | 2.58%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                           | 169      | 2.52%   |
| Nvidia GK208 HDMI/DP Audio Controller                                             | 157      | 2.34%   |
| Intel 200 Series PCH HD Audio                                                     | 155      | 2.31%   |
| Nvidia GP107GL High Definition Audio Controller                                   | 140      | 2.09%   |
| AMD Family 17h/19h HD Audio Controller                                            | 131      | 1.95%   |
| Intel Cannon Lake PCH cAVS                                                        | 130      | 1.94%   |
| Intel 9 Series Chipset Family HD Audio Controller                                 | 107      | 1.59%   |
| AMD FCH Azalia Controller                                                         | 107      | 1.59%   |
| Nvidia High Definition Audio Controller                                           | 105      | 1.57%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                  | 101      | 1.51%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                        | 101      | 1.51%   |
| Nvidia GP106 High Definition Audio Controller                                     | 80       | 1.19%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                          | 79       | 1.18%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]           | 77       | 1.15%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                    | 70       | 1.04%   |
| Nvidia MCP61 High Definition Audio                                                | 69       | 1.03%   |
| Nvidia GF119 HDMI Audio Controller                                                | 68       | 1.01%   |
| Nvidia GP104 High Definition Audio Controller                                     | 67       | 1%      |
| AMD Navi 21/23 HDMI/DP Audio Controller                                           | 64       | 0.95%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                               | 62       | 0.92%   |
| Nvidia GK104 HDMI Audio Controller                                                | 60       | 0.89%   |
| Nvidia GF108 High Definition Audio Controller                                     | 60       | 0.89%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                     | 59       | 0.88%   |
| Nvidia TU116 High Definition Audio Controller                                     | 58       | 0.86%   |
| Nvidia GM206 High Definition Audio Controller                                     | 57       | 0.85%   |
| Nvidia GM204 High Definition Audio Controller                                     | 57       | 0.85%   |
| Nvidia TU106 High Definition Audio Controller                                     | 55       | 0.82%   |
| Nvidia GP108 High Definition Audio Controller                                     | 55       | 0.82%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                            | 55       | 0.82%   |
| Nvidia GK107 HDMI Audio Controller                                                | 53       | 0.79%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM] | 53       | 0.79%   |
| AMD Renoir Radeon High Definition Audio Controller                                | 50       | 0.75%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Kingston            | 395      | 15.33%  |
| Unknown             | 394      | 15.29%  |
| Corsair             | 373      | 14.47%  |
| G.Skill             | 275      | 10.67%  |
| Samsung Electronics | 267      | 10.36%  |
| SK hynix            | 238      | 9.24%   |
| Crucial             | 229      | 8.89%   |
| Micron Technology   | 145      | 5.63%   |
| Nanya Technology    | 39       | 1.51%   |
| Elpida              | 23       | 0.89%   |
| Transcend           | 22       | 0.85%   |
| Ramaxel Technology  | 22       | 0.85%   |
| Team                | 14       | 0.54%   |
| A-DATA Technology   | 14       | 0.54%   |
| Unifosa             | 13       | 0.5%    |
| PNY                 | 13       | 0.5%    |
| Unknown             | 13       | 0.5%    |
| Unknown (ABCD)      | 12       | 0.47%   |
| Patriot             | 12       | 0.47%   |
| Unknown (0x0C97)    | 5        | 0.19%   |
| Timetec             | 5        | 0.19%   |
| Qimonda             | 5        | 0.19%   |
| TEXTORM             | 3        | 0.12%   |
| OCZ                 | 3        | 0.12%   |
| Hewlett-Packard     | 3        | 0.12%   |
| ASint Technology    | 3        | 0.12%   |
| Toshiba             | 2        | 0.08%   |
| Swissbit            | 2        | 0.08%   |
| Ramos Technology    | 2        | 0.08%   |
| Lexar               | 2        | 0.08%   |
| Kllisre             | 2        | 0.08%   |
| Innodisk            | 2        | 0.08%   |
| Unknown (F301)      | 1        | 0.04%   |
| Unknown (07FB)      | 1        | 0.04%   |
| Thermaltake         | 1        | 0.04%   |
| Texas_Instrument    | 1        | 0.04%   |
| TakeMS              | 1        | 0.04%   |
| Silicon Power       | 1        | 0.04%   |
| Sesame              | 1        | 0.04%   |
| QEMU                | 1        | 0.04%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                          | Desktops | Percent |
|----------------------------------------------------------------|----------|---------|
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s          | 35       | 1.24%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s            | 23       | 0.81%   |
| G.Skill RAM F3-12800CL9-4GBXL 4GB DIMM DDR3 1867MT/s           | 19       | 0.67%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s           | 18       | 0.64%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s            | 16       | 0.56%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                           | 15       | 0.53%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s          | 15       | 0.53%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s              | 13       | 0.46%   |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1600MT/s            | 13       | 0.46%   |
| Unknown                                                        | 13       | 0.46%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                        | 12       | 0.42%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                       | 12       | 0.42%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s | 12       | 0.42%   |
| SK hynix RAM HMA41GU6AFR8N-TF 8GB DIMM DDR4 2465MT/s           | 12       | 0.42%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s            | 12       | 0.42%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s         | 12       | 0.42%   |
| Corsair RAM CMK16GX4M2E3200C16 8GB DIMM DDR4 3200MT/s          | 12       | 0.42%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                        | 11       | 0.39%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s            | 11       | 0.39%   |
| Corsair RAM CMV4GX3M1A1333C9 4GB DIMM DDR3 1600MT/s            | 11       | 0.39%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                           | 10       | 0.35%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                    | 10       | 0.35%   |
| Samsung RAM M378B5173QH0-CK0 4GB DIMM DDR3 1600MT/s            | 10       | 0.35%   |
| Kingston RAM KHX2400C15/8G 8192MB DIMM DDR4 3400MT/s           | 10       | 0.35%   |
| Kingston RAM KHX2133C14D4/4G 4GB DIMM DDR4 2933MT/s            | 10       | 0.35%   |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s            | 10       | 0.35%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s            | 10       | 0.35%   |
| Corsair RAM CMK32GX4M2E3200C16 16GB DIMM DDR4 3534MT/s         | 10       | 0.35%   |
| Unknown RAM Module 1024MB DIMM SDRAM                           | 9        | 0.32%   |
| SK hynix RAM HMT451U6BFR8A-PB 4096MB DIMM DDR3 1648MT/s        | 9        | 0.32%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s           | 9        | 0.32%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s            | 9        | 0.32%   |
| Kingston RAM 99U5584-005.A00LF 4GB DIMM DDR3 1600MT/s          | 9        | 0.32%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s        | 9        | 0.32%   |
| Corsair RAM CMK16GX4M2D3000C16 8GB DIMM DDR4 3200MT/s          | 9        | 0.32%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                      | 8        | 0.28%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s                    | 8        | 0.28%   |
| Unknown RAM Module 2GB DIMM 800MT/s                            | 8        | 0.28%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s                    | 8        | 0.28%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                         | 8        | 0.28%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 896      | 39.26%  |
| DDR3    | 872      | 38.21%  |
| DDR2    | 170      | 7.45%   |
| Unknown | 139      | 6.09%   |
| SDRAM   | 130      | 5.7%    |
| DDR     | 45       | 1.97%   |
| LPDDR4  | 16       | 0.7%    |
| DDR5    | 10       | 0.44%   |
| DRAM    | 3        | 0.13%   |
| RAM     | 1        | 0.04%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| DIMM         | 2093     | 93.86%  |
| SODIMM       | 119      | 5.34%   |
| RIMM         | 9        | 0.4%    |
| FB-DIMM      | 7        | 0.31%   |
| Row Of Chips | 2        | 0.09%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 846      | 33.79%  |
| 4096  | 734      | 29.31%  |
| 2048  | 421      | 16.81%  |
| 16384 | 270      | 10.78%  |
| 1024  | 166      | 6.63%   |
| 32768 | 36       | 1.44%   |
| 512   | 29       | 1.16%   |
| 256   | 2        | 0.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 474      | 18.92%  |
| 1333    | 300      | 11.98%  |
| 3200    | 183      | 7.31%   |
| 2400    | 157      | 6.27%   |
| 2667    | 127      | 5.07%   |
| 3600    | 124      | 4.95%   |
| 2133    | 123      | 4.91%   |
| 800     | 123      | 4.91%   |
| 667     | 83       | 3.31%   |
| 1867    | 70       | 2.79%   |
| 1066    | 59       | 2.36%   |
| Unknown | 53       | 2.12%   |
| 1866    | 44       | 1.76%   |
| 3000    | 43       | 1.72%   |
| 1800    | 40       | 1.6%    |
| 2933    | 37       | 1.48%   |
| 2666    | 37       | 1.48%   |
| 3400    | 36       | 1.44%   |
| 1067    | 21       | 0.84%   |
| 400     | 21       | 0.84%   |
| 2800    | 20       | 0.8%    |
| 2048    | 19       | 0.76%   |
| 3733    | 18       | 0.72%   |
| 3533    | 18       | 0.72%   |
| 533     | 18       | 0.72%   |
| 3800    | 17       | 0.68%   |
| 3466    | 16       | 0.64%   |
| 3666    | 15       | 0.6%    |
| 3266    | 12       | 0.48%   |
| 2465    | 12       | 0.48%   |
| 2000    | 11       | 0.44%   |
| 3866    | 10       | 0.4%    |
| 3534    | 10       | 0.4%    |
| 1639    | 10       | 0.4%    |
| 1334    | 10       | 0.4%    |
| 333     | 10       | 0.4%    |
| 2733    | 9        | 0.36%   |
| 1648    | 9        | 0.36%   |
| 4800    | 8        | 0.32%   |
| 3100    | 8        | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Hewlett-Packard       | 91       | 43.75%  |
| Brother Industries    | 36       | 17.31%  |
| Canon                 | 30       | 14.42%  |
| Samsung Electronics   | 28       | 13.46%  |
| Seiko Epson           | 12       | 5.77%   |
| Prolific Technology   | 3        | 1.44%   |
| Lexmark International | 2        | 0.96%   |
| Xerox                 | 1        | 0.48%   |
| STMicroelectronics    | 1        | 0.48%   |
| Ricoh                 | 1        | 0.48%   |
| QinHeng Electronics   | 1        | 0.48%   |
| Kyocera               | 1        | 0.48%   |
| Apple                 | 1        | 0.48%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Samsung M2070 Series                                      | 8        | 3.83%   |
| HP ENVY 4520 series                                       | 8        | 3.83%   |
| HP DeskJet 3630 series                                    | 6        | 2.87%   |
| HP DeskJet 2700 series                                    | 6        | 2.87%   |
| HP ENVY Photo 6200 series                                 | 5        | 2.39%   |
| HP ENVY 5000 series                                       | 4        | 1.91%   |
| HP DeskJet 3700 series                                    | 4        | 1.91%   |
| HP DeskJet 2600 series                                    | 4        | 1.91%   |
| Canon PIXMA MG3600 Series                                 | 4        | 1.91%   |
| Brother HL-2030 Laser Printer                             | 4        | 1.91%   |
| Seiko Epson XP-243 245 247 Series                         | 3        | 1.44%   |
| Samsung CLX-3170 Series                                   | 3        | 1.44%   |
| Prolific PL2305 Parallel Port                             | 3        | 1.44%   |
| HP DeskJet Plus 4100 series                               | 3        | 1.44%   |
| HP Deskjet 3050A                                          | 3        | 1.44%   |
| Brother Printer                                           | 3        | 1.44%   |
| Brother DCP-7055 scanner/printer                          | 3        | 1.44%   |
| Seiko Epson XP-2100 Series                                | 2        | 0.96%   |
| Samsung SCX-3400 Series                                   | 2        | 0.96%   |
| Samsung ML-1660 Series                                    | 2        | 0.96%   |
| Samsung ML-1640 Series Laser Printer                      | 2        | 0.96%   |
| Samsung ML-1630 Series                                    | 2        | 0.96%   |
| Samsung M2020 Series                                      | 2        | 0.96%   |
| Samsung CLX-3180 Series                                   | 2        | 0.96%   |
| HP OfficeJet 3830 series                                  | 2        | 0.96%   |
| HP LaserJet 1200                                          | 2        | 0.96%   |
| HP DeskJet F4200 series                                   | 2        | 0.96%   |
| HP DeskJet 5550                                           | 2        | 0.96%   |
| HP Deskjet 3070 B611 series                               | 2        | 0.96%   |
| HP DeskJet 2130 series                                    | 2        | 0.96%   |
| HP Deskjet 1510                                           | 2        | 0.96%   |
| Canon TS5100 series                                       | 2        | 0.96%   |
| Canon iP7200 series                                       | 2        | 0.96%   |
| Brother MFC-L2710DW series                                | 2        | 0.96%   |
| Brother MFC-9330CDW                                       | 2        | 0.96%   |
| Brother HL-L2375DW series                                 | 2        | 0.96%   |
| Brother HL-L2350DW series                                 | 2        | 0.96%   |
| Xerox ColorQube 8580DN                                    | 1        | 0.48%   |
| STMicroelectronics LED badge -- mini LED display -- 11x44 | 1        | 0.48%   |
| Seiko Epson XP-255 257 Series                             | 1        | 0.48%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 50       | 64.1%   |
| Seiko Epson     | 17       | 21.79%  |
| Hewlett-Packard | 7        | 8.97%   |
| AGFA-Gevaert NV | 4        | 5.13%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                         | Desktops | Percent |
|---------------------------------------------------------------|----------|---------|
| Canon CanoScan N670U/N676U/LiDE 20                            | 8        | 10.26%  |
| Canon CanoScan N1240U/LiDE 30                                 | 8        | 10.26%  |
| Canon CanoScan LIDE 25                                        | 6        | 7.69%   |
| Canon CanoScan LiDE 110                                       | 6        | 7.69%   |
| Seiko Epson GT-X770 [Perfection V500]                         | 4        | 5.13%   |
| Canon CanoScan LiDE 60                                        | 3        | 3.85%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                        | 3        | 3.85%   |
| Canon CanoScan LiDE 200                                       | 3        | 3.85%   |
| AGFA-Gevaert NV SnapScan e20                                  | 3        | 3.85%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 2        | 2.56%   |
| Seiko Epson GT-F700 [Perfection V350]                         | 2        | 2.56%   |
| Seiko Epson GT-9800F [Perfection 3200]                        | 2        | 2.56%   |
| Seiko Epson GT-6600U [Perfection 610]                         | 2        | 2.56%   |
| Canon CanoScan LiDE 220                                       | 2        | 2.56%   |
| Canon CanoScan LiDE 210                                       | 2        | 2.56%   |
| Canon CanoScan LiDE 120                                       | 2        | 2.56%   |
| Canon CanoScan 4200F                                          | 2        | 2.56%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]             | 1        | 1.28%   |
| Seiko Epson GT-F600 [Perfection 4180]                         | 1        | 1.28%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1        | 1.28%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]            | 1        | 1.28%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]   | 1        | 1.28%   |
| HP ScanJet G4010                                              | 1        | 1.28%   |
| HP ScanJet 5200c                                              | 1        | 1.28%   |
| HP ScanJet 4570c                                              | 1        | 1.28%   |
| HP ScanJet 3570c                                              | 1        | 1.28%   |
| HP ScanJet 3500c                                              | 1        | 1.28%   |
| HP ScanJet 2300c                                              | 1        | 1.28%   |
| HP PSC 1200                                                   | 1        | 1.28%   |
| Canon CanoScan N650U/N656U                                    | 1        | 1.28%   |
| Canon CanoScan LiDE 70                                        | 1        | 1.28%   |
| Canon CanoScan LiDE 100                                       | 1        | 1.28%   |
| Canon CanoScan 9000F Mark II                                  | 1        | 1.28%   |
| Canon CanoScan 4400F                                          | 1        | 1.28%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                            | 1        | 1.28%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 283      | 44.64%  |
| Microdia                      | 43       | 6.78%   |
| Microsoft                     | 39       | 6.15%   |
| Samsung Electronics           | 29       | 4.57%   |
| Sunplus Innovation Technology | 22       | 3.47%   |
| Guillemot                     | 22       | 3.47%   |
| Chicony Electronics           | 15       | 2.37%   |
| ARC International             | 13       | 2.05%   |
| Realtek Semiconductor         | 12       | 1.89%   |
| Creative Technology           | 12       | 1.89%   |
| Apple                         | 11       | 1.74%   |
| Sonix Technology              | 10       | 1.58%   |
| Generalplus Technology        | 10       | 1.58%   |
| Hewlett-Packard               | 9        | 1.42%   |
| KYE Systems (Mouse Systems)   | 8        | 1.26%   |
| GEMBIRD                       | 8        | 1.26%   |
| webcam                        | 6        | 0.95%   |
| Sunplus IT                    | 6        | 0.95%   |
| Z-Star Microelectronics       | 5        | 0.79%   |
| Cubeternet                    | 5        | 0.79%   |
| AVerMedia Technologies        | 5        | 0.79%   |
| WaveRider Communications      | 4        | 0.63%   |
| Arkmicro Technologies         | 4        | 0.63%   |
| Trust                         | 3        | 0.47%   |
| Jieli Technology              | 3        | 0.47%   |
| Huawei Technologies           | 3        | 0.47%   |
| Xiongmai                      | 2        | 0.32%   |
| Syntek                        | 2        | 0.32%   |
| Razer USA                     | 2        | 0.32%   |
| Philips (or NXP)              | 2        | 0.32%   |
| MacroSilicon                  | 2        | 0.32%   |
| IMC Networks                  | 2        | 0.32%   |
| Genesys Logic                 | 2        | 0.32%   |
| Alcor Micro                   | 2        | 0.32%   |
| YGTek                         | 1        | 0.16%   |
| Yealink Network Technology    | 1        | 0.16%   |
| Xiaomi                        | 1        | 0.16%   |
| WCM_USB                       | 1        | 0.16%   |
| ViewSonic                     | 1        | 0.16%   |
| Valve Software                | 1        | 0.16%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Logitech Webcam C270                              | 63       | 9.94%   |
| Logitech HD Pro Webcam C920                       | 37       | 5.84%   |
| Samsung Galaxy series, misc. (MTP mode)           | 29       | 4.57%   |
| Logitech HD Webcam C525                           | 28       | 4.42%   |
| Logitech Webcam C170                              | 16       | 2.52%   |
| Logitech C922 Pro Stream Webcam                   | 14       | 2.21%   |
| Microsoft LifeCam HD-3000                         | 13       | 2.05%   |
| Logitech Webcam C310                              | 13       | 2.05%   |
| ARC International Camera                          | 13       | 2.05%   |
| Microdia Webcam Vitade AF                         | 11       | 1.74%   |
| Microdia Camera                                   | 11       | 1.74%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                   | 11       | 1.74%   |
| Guillemot Hercules HD Twist                       | 9        | 1.42%   |
| Sonix USB Camera                                  | 8        | 1.26%   |
| Logitech BRIO Ultra HD Webcam                     | 8        | 1.26%   |
| Realtek FULL HD 1080P Webcam                      | 7        | 1.1%    |
| Microdia Sonix USB 2.0 Camera                     | 7        | 1.1%    |
| Logitech HD Webcam C910                           | 7        | 1.1%    |
| Logitech BRIO 4K Stream Edition                   | 7        | 1.1%    |
| webcam webcam                                     | 6        | 0.95%   |
| Sunplus Full HD webcam                            | 6        | 0.95%   |
| Microdia USB 2.0 Camera                           | 6        | 0.95%   |
| Logitech Webcam C300                              | 6        | 0.95%   |
| Logitech StreamCam                                | 6        | 0.95%   |
| Logitech QuickCam Pro 4000                        | 6        | 0.95%   |
| Logitech HD Webcam C615                           | 6        | 0.95%   |
| KYE Systems (Mouse Systems) PC-W3 Camera          | 6        | 0.95%   |
| HP Webcam HD 4310                                 | 6        | 0.95%   |
| Guillemot Hercules Dualpix Exchange               | 6        | 0.95%   |
| Generalplus 808 Camera #9 (web-cam mode)          | 6        | 0.95%   |
| GEMBIRD Generic UVC 1.00 camera [AppoTech AX2311] | 6        | 0.95%   |
| Sunplus IT AUKEY PC-LM1 USB Camera                | 5        | 0.79%   |
| Microsoft LifeCam VX-5000                         | 5        | 0.79%   |
| Microsoft LifeCam Cinema                          | 5        | 0.79%   |
| Logitech Webcam Pro 9000                          | 5        | 0.79%   |
| Logitech Webcam C930e                             | 5        | 0.79%   |
| Logitech Webcam C250                              | 5        | 0.79%   |
| Logitech Webcam C200                              | 5        | 0.79%   |
| Logitech QuickCam Pro 9000                        | 5        | 0.79%   |
| Logitech QuickCam Pro 5000                        | 5        | 0.79%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Validity Sensors           | 1        | 20%     |
| Synaptics                  | 1        | 20%     |
| Shenzhen Goodix Technology | 1        | 20%     |
| Elan Microelectronics      | 1        | 20%     |
| AuthenTec                  | 1        | 20%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor | 1        | 20%     |
| Synaptics  WBDI Fingerprint Reader - USB 052                | 1        | 20%     |
| Shenzhen Goodix  Fingerprint Device                         | 1        | 20%     |
| Elan fingerprint sensor [FeinTech FPS00200]                 | 1        | 20%     |
| AuthenTec AES2501 Fingerprint Sensor                        | 1        | 20%     |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| Hewlett-Packard           | 4        | 17.39%  |
| Gemalto (was Gemplus)     | 4        | 17.39%  |
| SCM Microsystems          | 2        | 8.7%    |
| Realtek Semiconductor     | 2        | 8.7%    |
| Chicony Electronics       | 2        | 8.7%    |
| Aladdin Knowledge Systems | 2        | 8.7%    |
| Yubico.com                | 1        | 4.35%   |
| ST-Ericsson               | 1        | 4.35%   |
| Feitian Technologies      | 1        | 4.35%   |
| Clay Logic                | 1        | 4.35%   |
| Cherry                    | 1        | 4.35%   |
| Alcor Micro               | 1        | 4.35%   |
| Advanced Card Systems     | 1        | 4.35%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                | Desktops | Percent |
|------------------------------------------------------|----------|---------|
| Hewlett-Packard SC Keyboard - Apollo (Liteon)        | 4        | 17.39%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader    | 3        | 13.04%  |
| Realtek Semiconductor Smart Card Reader Interface    | 2        | 8.7%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard | 2        | 8.7%    |
| Aladdin Knowledge Systems Token JC                   | 2        | 8.7%    |
| Yubico.com Yubikey 4/5 U2F+CCID                      | 1        | 4.35%   |
| ST-Ericsson Chipcard Reader                          | 1        | 4.35%   |
| SCM Microsystems SCR335 SmartCard Reader             | 1        | 4.35%   |
| SCM Microsystems CLOUD 2700 F Smart Card Reader      | 1        | 4.35%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader     | 1        | 4.35%   |
| Feitian Technologies FT SCR310                       | 1        | 4.35%   |
| Clay Logic Nitrokey Pro                              | 1        | 4.35%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0           | 1        | 4.35%   |
| Alcor Micro Watchdata W 1981                         | 1        | 4.35%   |
| Advanced Card Systems ACR122U                        | 1        | 4.35%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 2985     | 85.04%  |
| 1     | 436      | 12.42%  |
| 2     | 68       | 1.94%   |
| 4     | 10       | 0.28%   |
| 3     | 8        | 0.23%   |
| 5     | 2        | 0.06%   |
| 9     | 1        | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 254      | 41.64%  |
| Net/wireless             | 119      | 19.51%  |
| Communication controller | 51       | 8.36%   |
| Unassigned class         | 50       | 8.2%    |
| Multimedia controller    | 29       | 4.75%   |
| Sound                    | 22       | 3.61%   |
| Bluetooth                | 13       | 2.13%   |
| Net/ethernet             | 12       | 1.97%   |
| Chipcard                 | 10       | 1.64%   |
| Camera                   | 10       | 1.64%   |
| Storage/raid             | 7        | 1.15%   |
| Network                  | 7        | 1.15%   |
| Storage/ide              | 5        | 0.82%   |
| Firewire controller      | 5        | 0.82%   |
| Card reader              | 5        | 0.82%   |
| Modem                    | 4        | 0.66%   |
| Fingerprint reader       | 4        | 0.66%   |
| Tv card                  | 2        | 0.33%   |
| Dvb card                 | 1        | 0.16%   |

