Linux in Brazil - Tested Hardware & Statistics
----------------------------------------------

A project to collect tested hardware configurations for Linux in Brazil.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Brazil/Desktop/README.md) and [notebooks](/Location/Brazil/Notebook/README.md).

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

Total: 21687

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Unknown       | DH61BR G32662-203           | Desktop     | [06cb46d18c](https://linux-hardware.org/?probe=06cb46d18c) | Feb 02, 2024 |
| Unknown       | DH61BR G32662-203           | Desktop     | [7496b90e09](https://linux-hardware.org/?probe=7496b90e09) | Feb 02, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | Notebook    | [2389b9fc2f](https://linux-hardware.org/?probe=2389b9fc2f) | Feb 02, 2024 |
| Lenovo        | Legion Slim 5 16IRH8 83D... | Notebook    | [32facc4f9e](https://linux-hardware.org/?probe=32facc4f9e) | Feb 02, 2024 |
| Dell          | Inspiron 3583               | Notebook    | [3c532c85ec](https://linux-hardware.org/?probe=3c532c85ec) | Feb 02, 2024 |
| Dell          | Inspiron 3442               | Notebook    | [ca29fa6852](https://linux-hardware.org/?probe=ca29fa6852) | Feb 02, 2024 |
| Pegatron      | IPM41-D3                    | Desktop     | [5884d40085](https://linux-hardware.org/?probe=5884d40085) | Feb 02, 2024 |
| Dell          | G7 7588                     | Notebook    | [fdc746ce61](https://linux-hardware.org/?probe=fdc746ce61) | Feb 02, 2024 |
| Dell          | Latitude 7420               | Notebook    | [5eb0b85732](https://linux-hardware.org/?probe=5eb0b85732) | Feb 02, 2024 |
| Dell          | 0PV3YR A05                  | Server      | [25e7def18b](https://linux-hardware.org/?probe=25e7def18b) | Feb 02, 2024 |
| GX55          | Unknown                     | Tablet      | [99db62ac14](https://linux-hardware.org/?probe=99db62ac14) | Feb 02, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [6259b53b1c](https://linux-hardware.org/?probe=6259b53b1c) | Feb 02, 2024 |
| Dell          | Inspiron 5547               | Notebook    | [507fad3c00](https://linux-hardware.org/?probe=507fad3c00) | Feb 02, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e5bbf9598f](https://linux-hardware.org/?probe=e5bbf9598f) | Feb 01, 2024 |
| Pegatron      | IPM41-D3                    | Desktop     | [7969244295](https://linux-hardware.org/?probe=7969244295) | Feb 01, 2024 |
| Dell          | 0PV3YR A05                  | Server      | [58467e737b](https://linux-hardware.org/?probe=58467e737b) | Feb 01, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [7def8ee544](https://linux-hardware.org/?probe=7def8ee544) | Feb 01, 2024 |
| Samsung       | 750XFH                      | Notebook    | [47d573ccf5](https://linux-hardware.org/?probe=47d573ccf5) | Feb 01, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [a58037b70a](https://linux-hardware.org/?probe=a58037b70a) | Feb 01, 2024 |
| Gigabyte      | AB350M-D3H-CF               | Desktop     | [d9345d1a97](https://linux-hardware.org/?probe=d9345d1a97) | Feb 01, 2024 |
| Intel         | B75                         | Desktop     | [2984342e49](https://linux-hardware.org/?probe=2984342e49) | Jan 31, 2024 |
| Unknown       | Unknown                     | Desktop     | [66102cc055](https://linux-hardware.org/?probe=66102cc055) | Jan 31, 2024 |
| Acer          | Swift SF514-56T             | Notebook    | [320f3db548](https://linux-hardware.org/?probe=320f3db548) | Jan 31, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [13a76a1fcf](https://linux-hardware.org/?probe=13a76a1fcf) | Jan 31, 2024 |
| Evolute       | B14HM21                     | Notebook    | [c5a911ad90](https://linux-hardware.org/?probe=c5a911ad90) | Jan 31, 2024 |
| Dell          | Inspiron N4050              | Notebook    | [9126475882](https://linux-hardware.org/?probe=9126475882) | Jan 31, 2024 |
| Dell          | 0PV3YR A05                  | Server      | [399221e733](https://linux-hardware.org/?probe=399221e733) | Jan 31, 2024 |
| ASUSTek       | TP550LA                     | Notebook    | [2fa23ece92](https://linux-hardware.org/?probe=2fa23ece92) | Jan 31, 2024 |
| Avell         | B.ON                        | Notebook    | [45a01901e9](https://linux-hardware.org/?probe=45a01901e9) | Jan 31, 2024 |
| Dell          | Inspiron 5537               | Notebook    | [7c7904f383](https://linux-hardware.org/?probe=7c7904f383) | Jan 31, 2024 |
| Intel         | B75                         | Desktop     | [000ad7f808](https://linux-hardware.org/?probe=000ad7f808) | Jan 31, 2024 |
| Dell          | Inspiron 5537               | Notebook    | [7a4e4ac7ba](https://linux-hardware.org/?probe=7a4e4ac7ba) | Jan 31, 2024 |
| Dell          | Studio 1450                 | Notebook    | [cdeeb53e43](https://linux-hardware.org/?probe=cdeeb53e43) | Jan 31, 2024 |
| HP            | Presario C700               | Notebook    | [d309190dbb](https://linux-hardware.org/?probe=d309190dbb) | Jan 30, 2024 |
| Dell          | G15 5510                    | Notebook    | [9f3691e991](https://linux-hardware.org/?probe=9f3691e991) | Jan 30, 2024 |
| ASUSTek       | B85M-E/BR                   | Desktop     | [d3a20c90d1](https://linux-hardware.org/?probe=d3a20c90d1) | Jan 30, 2024 |
| Gigabyte      | H55M-S2HP                   | Desktop     | [a1a4140c7e](https://linux-hardware.org/?probe=a1a4140c7e) | Jan 30, 2024 |
| QIYIDA        | ED4 V1.1                    | Desktop     | [3583de3c82](https://linux-hardware.org/?probe=3583de3c82) | Jan 30, 2024 |
| MSI           | B450M BAZOOKA V2            | Desktop     | [fbf883eddb](https://linux-hardware.org/?probe=fbf883eddb) | Jan 30, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [6f8f587ec5](https://linux-hardware.org/?probe=6f8f587ec5) | Jan 30, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0b6e8d1e4b](https://linux-hardware.org/?probe=0b6e8d1e4b) | Jan 30, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [e5435a9682](https://linux-hardware.org/?probe=e5435a9682) | Jan 30, 2024 |
| ASRock        | A320M-HD                    | Desktop     | [5c0864b392](https://linux-hardware.org/?probe=5c0864b392) | Jan 29, 2024 |
| Acer          | Nitro AN515-44              | Notebook    | [05ec6529d7](https://linux-hardware.org/?probe=05ec6529d7) | Jan 29, 2024 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [21628b2a5b](https://linux-hardware.org/?probe=21628b2a5b) | Jan 29, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [c1af8d7ca2](https://linux-hardware.org/?probe=c1af8d7ca2) | Jan 29, 2024 |
| Itautec       | ST 4253 ST-4253 Padrao 0... | Desktop     | [26ae99cfe2](https://linux-hardware.org/?probe=26ae99cfe2) | Jan 29, 2024 |
| Compaq        | Presario CQ-21              | Notebook    | [b947b6f2b8](https://linux-hardware.org/?probe=b947b6f2b8) | Jan 29, 2024 |
| MSI           | A520M-A PRO                 | Desktop     | [97b12146a9](https://linux-hardware.org/?probe=97b12146a9) | Jan 29, 2024 |
| Acer          | Aspire 5750                 | Notebook    | [f05ba6ae6f](https://linux-hardware.org/?probe=f05ba6ae6f) | Jan 29, 2024 |
| Apple         | Mac-F227BEC8 PVT            | All in one  | [7eaf280c7a](https://linux-hardware.org/?probe=7eaf280c7a) | Jan 29, 2024 |
| Microsoft     | Surface Pro 3               | Tablet      | [20ca543652](https://linux-hardware.org/?probe=20ca543652) | Jan 29, 2024 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [1d8dbbd8af](https://linux-hardware.org/?probe=1d8dbbd8af) | Jan 29, 2024 |
| Biostar       | B550MH                      | Desktop     | [18a98ffa2c](https://linux-hardware.org/?probe=18a98ffa2c) | Jan 28, 2024 |
| Biostar       | B550MH                      | Desktop     | [7e52e1855c](https://linux-hardware.org/?probe=7e52e1855c) | Jan 28, 2024 |
| Avell High... | B.ON                        | Notebook    | [8b9b2f2129](https://linux-hardware.org/?probe=8b9b2f2129) | Jan 28, 2024 |
| Intel         | DX58SO AAE29331-503         | Desktop     | [57959fa365](https://linux-hardware.org/?probe=57959fa365) | Jan 28, 2024 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [81e9c9a499](https://linux-hardware.org/?probe=81e9c9a499) | Jan 28, 2024 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [a89b017c8e](https://linux-hardware.org/?probe=a89b017c8e) | Jan 28, 2024 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [af418fe886](https://linux-hardware.org/?probe=af418fe886) | Jan 28, 2024 |
| ASUSTek       | PRIME H510M-E               | Desktop     | [f8f08ce899](https://linux-hardware.org/?probe=f8f08ce899) | Jan 28, 2024 |
| Lenovo        | IdeaPad 130-15AST 81H5      | Notebook    | [465b69ceca](https://linux-hardware.org/?probe=465b69ceca) | Jan 28, 2024 |
| Intel         | H110                        | Desktop     | [2252be4fdb](https://linux-hardware.org/?probe=2252be4fdb) | Jan 28, 2024 |
| Positivo      | POS-EINM10CB POSITIVO       | Desktop     | [efe2537d0f](https://linux-hardware.org/?probe=efe2537d0f) | Jan 28, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [9ce085875f](https://linux-hardware.org/?probe=9ce085875f) | Jan 27, 2024 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c1312a18b3](https://linux-hardware.org/?probe=c1312a18b3) | Jan 27, 2024 |
| Intel         | 35901                       | Desktop     | [2851a5f3bd](https://linux-hardware.org/?probe=2851a5f3bd) | Jan 27, 2024 |
| HP            | Pavilion 14                 | Notebook    | [93fffe502f](https://linux-hardware.org/?probe=93fffe502f) | Jan 27, 2024 |
| Lenovo        | G50-80 80R0                 | Notebook    | [980165425e](https://linux-hardware.org/?probe=980165425e) | Jan 27, 2024 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [e458188420](https://linux-hardware.org/?probe=e458188420) | Jan 26, 2024 |
| Lenovo        | G50-80 80R0                 | Notebook    | [eeee227df0](https://linux-hardware.org/?probe=eeee227df0) | Jan 26, 2024 |
| Dell          | Latitude 3480               | Notebook    | [5ccc62ce95](https://linux-hardware.org/?probe=5ccc62ce95) | Jan 26, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [afbea953be](https://linux-hardware.org/?probe=afbea953be) | Jan 26, 2024 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [8cafa419c5](https://linux-hardware.org/?probe=8cafa419c5) | Jan 26, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7dd8607755](https://linux-hardware.org/?probe=7dd8607755) | Jan 26, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [99eeba6228](https://linux-hardware.org/?probe=99eeba6228) | Jan 26, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [411e5a0261](https://linux-hardware.org/?probe=411e5a0261) | Jan 26, 2024 |
| Lenovo        | ThinkPad Edge E430 3254H... | Notebook    | [ec87598c40](https://linux-hardware.org/?probe=ec87598c40) | Jan 26, 2024 |
| ASRock        | Z77 Extreme4                | Desktop     | [ea6ee7eaee](https://linux-hardware.org/?probe=ea6ee7eaee) | Jan 26, 2024 |
| Lenovo        | G460 0677                   | Notebook    | [d4624cb524](https://linux-hardware.org/?probe=d4624cb524) | Jan 26, 2024 |
| Gigabyte      | H81M-S2PV                   | Desktop     | [c609c40476](https://linux-hardware.org/?probe=c609c40476) | Jan 25, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [01a72ce274](https://linux-hardware.org/?probe=01a72ce274) | Jan 25, 2024 |
| Intel         | B75                         | Desktop     | [b9a4ea0b9b](https://linux-hardware.org/?probe=b9a4ea0b9b) | Jan 25, 2024 |
| Gigabyte      | B450M GAMING                | Desktop     | [c25c76b288](https://linux-hardware.org/?probe=c25c76b288) | Jan 25, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [606adf78f9](https://linux-hardware.org/?probe=606adf78f9) | Jan 24, 2024 |
| Positivo      | POS-EIBTPDC                 | Desktop     | [120ebd1d10](https://linux-hardware.org/?probe=120ebd1d10) | Jan 24, 2024 |
| ASRock        | A320M-HD R4.0               | Desktop     | [0020153fc0](https://linux-hardware.org/?probe=0020153fc0) | Jan 24, 2024 |
| ODM           | Unknown                     | Notebook    | [2d8310fe96](https://linux-hardware.org/?probe=2d8310fe96) | Jan 24, 2024 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [876874e8b5](https://linux-hardware.org/?probe=876874e8b5) | Jan 24, 2024 |
| MSI           | H55M-E33                    | Desktop     | [2935476b48](https://linux-hardware.org/?probe=2935476b48) | Jan 23, 2024 |
| Dell          | 0VTJVC A00                  | Desktop     | [634478296d](https://linux-hardware.org/?probe=634478296d) | Jan 23, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ed52617ade](https://linux-hardware.org/?probe=ed52617ade) | Jan 23, 2024 |
| ASUSTek       | PRIME A320M-K/BR            | Desktop     | [8bf8602f25](https://linux-hardware.org/?probe=8bf8602f25) | Jan 23, 2024 |
| Dell          | Vostro 5490                 | Notebook    | [ef2aff4ed1](https://linux-hardware.org/?probe=ef2aff4ed1) | Jan 23, 2024 |
| HP            | Pavilion g4                 | Notebook    | [f0cc56ebca](https://linux-hardware.org/?probe=f0cc56ebca) | Jan 23, 2024 |
| ASUSTek       | ROG STRIX Z590-F GAMING ... | Desktop     | [988f12d3d7](https://linux-hardware.org/?probe=988f12d3d7) | Jan 23, 2024 |
| Acer          | Aspire A315-54              | Notebook    | [83570af6ad](https://linux-hardware.org/?probe=83570af6ad) | Jan 23, 2024 |
| Valve         | Jupiter                     | Notebook    | [9ac816140b](https://linux-hardware.org/?probe=9ac816140b) | Jan 23, 2024 |
| Positivo      | Mobile                      | Notebook    | [d1ca90b4f5](https://linux-hardware.org/?probe=d1ca90b4f5) | Jan 23, 2024 |
| Gigabyte      | X570 GAMING X               | Desktop     | [a2f925963a](https://linux-hardware.org/?probe=a2f925963a) | Jan 22, 2024 |
| Dell          | Inspiron 5570               | Notebook    | [9fd4f31b80](https://linux-hardware.org/?probe=9fd4f31b80) | Jan 22, 2024 |
| Dell          | 0NW73C A00                  | Desktop     | [fcf03eefc9](https://linux-hardware.org/?probe=fcf03eefc9) | Jan 22, 2024 |
| Dell          | Inspiron 3421               | Notebook    | [a15cb7d764](https://linux-hardware.org/?probe=a15cb7d764) | Jan 22, 2024 |
| Intel         | DX58SO AAE29331-503         | Desktop     | [ed61279750](https://linux-hardware.org/?probe=ed61279750) | Jan 22, 2024 |
| AZW           | GTR V01                     | Mini pc     | [b051db0609](https://linux-hardware.org/?probe=b051db0609) | Jan 22, 2024 |
| Dell          | Inspiron 5490               | Notebook    | [e879f5dd00](https://linux-hardware.org/?probe=e879f5dd00) | Jan 22, 2024 |
| Gigabyte      | H510M H                     | Notebook    | [88b87b3353](https://linux-hardware.org/?probe=88b87b3353) | Jan 22, 2024 |
| HP            | Folio 13                    | Notebook    | [a4be721bb8](https://linux-hardware.org/?probe=a4be721bb8) | Jan 22, 2024 |
| HC            | HCAR357-MI V1.0             | Desktop     | [1f15fb2119](https://linux-hardware.org/?probe=1f15fb2119) | Jan 22, 2024 |
| Biostar       | A68MHE                      | Desktop     | [bd1cb81b9d](https://linux-hardware.org/?probe=bd1cb81b9d) | Jan 22, 2024 |
| ASUSTek       | S400CA                      | Notebook    | [87f5dfadc9](https://linux-hardware.org/?probe=87f5dfadc9) | Jan 22, 2024 |
| Acer          | Aspire A315-58              | Notebook    | [4a991bd59b](https://linux-hardware.org/?probe=4a991bd59b) | Jan 22, 2024 |
| Dell          | 0VTJVC A00                  | Desktop     | [006ea19b6d](https://linux-hardware.org/?probe=006ea19b6d) | Jan 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [9e62126d95](https://linux-hardware.org/?probe=9e62126d95) | Jan 21, 2024 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [e83d57317e](https://linux-hardware.org/?probe=e83d57317e) | Jan 21, 2024 |
| Lenovo        | G460 20041                  | Notebook    | [becc9c140b](https://linux-hardware.org/?probe=becc9c140b) | Jan 21, 2024 |
| Valve         | Jupiter                     | Notebook    | [4d7a6b2c71](https://linux-hardware.org/?probe=4d7a6b2c71) | Jan 21, 2024 |
| Acer          | Nitro AN515-55              | Notebook    | [428442a3ab](https://linux-hardware.org/?probe=428442a3ab) | Jan 21, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [07f3899f3a](https://linux-hardware.org/?probe=07f3899f3a) | Jan 21, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [7bb9b69a14](https://linux-hardware.org/?probe=7bb9b69a14) | Jan 21, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [124da06515](https://linux-hardware.org/?probe=124da06515) | Jan 21, 2024 |
| Acer          | Aspire A315-59              | Notebook    | [01d1c30937](https://linux-hardware.org/?probe=01d1c30937) | Jan 21, 2024 |
| MACHINIST     | X99 PR9                     | Desktop     | [2cac18e4ae](https://linux-hardware.org/?probe=2cac18e4ae) | Jan 21, 2024 |
| ASUSTek       | TUF B450M-PLUS GAMING       | Desktop     | [80001dbe10](https://linux-hardware.org/?probe=80001dbe10) | Jan 21, 2024 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [09c4a32231](https://linux-hardware.org/?probe=09c4a32231) | Jan 21, 2024 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [a5aac63320](https://linux-hardware.org/?probe=a5aac63320) | Jan 20, 2024 |
| Samsung       | 270E5K/270E5Q/271E5K/257... | Notebook    | [e8a23ca7a0](https://linux-hardware.org/?probe=e8a23ca7a0) | Jan 20, 2024 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [ef0e698daf](https://linux-hardware.org/?probe=ef0e698daf) | Jan 20, 2024 |
| MACHINIST     | X79 Z9-D7 PRO V1.0          | Desktop     | [066ef702e4](https://linux-hardware.org/?probe=066ef702e4) | Jan 20, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [48653c026b](https://linux-hardware.org/?probe=48653c026b) | Jan 20, 2024 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [4dfe57b817](https://linux-hardware.org/?probe=4dfe57b817) | Jan 20, 2024 |
| MACHINIST     | X79 Z9-D7 PRO V1.0          | Desktop     | [278fae59fe](https://linux-hardware.org/?probe=278fae59fe) | Jan 20, 2024 |
| Multilaser    | PC301                       | Convertible | [3349d29af4](https://linux-hardware.org/?probe=3349d29af4) | Jan 20, 2024 |
| HP            | Presario CQ43               | Notebook    | [ad1175a3a8](https://linux-hardware.org/?probe=ad1175a3a8) | Jan 20, 2024 |
| ASRock        | FM2A68M-HD+ R2.0            | Desktop     | [793d303d19](https://linux-hardware.org/?probe=793d303d19) | Jan 20, 2024 |
| Dell          | Latitude 3490               | Notebook    | [367100a9ad](https://linux-hardware.org/?probe=367100a9ad) | Jan 20, 2024 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [f88694f40b](https://linux-hardware.org/?probe=f88694f40b) | Jan 20, 2024 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [1ce9d8eb2f](https://linux-hardware.org/?probe=1ce9d8eb2f) | Jan 20, 2024 |
| HP            | ProLiant ML110 Gen9         | Desktop     | [ec93a55951](https://linux-hardware.org/?probe=ec93a55951) | Jan 19, 2024 |
| Samsung       | 960XFH                      | Notebook    | [fa6946bc7b](https://linux-hardware.org/?probe=fa6946bc7b) | Jan 19, 2024 |
| Intel         | X99H                        | Desktop     | [3feec5f356](https://linux-hardware.org/?probe=3feec5f356) | Jan 19, 2024 |
| Intel         | JSL MRD                     | Desktop     | [96bcf87520](https://linux-hardware.org/?probe=96bcf87520) | Jan 19, 2024 |
| Dell          | Inspiron 7520               | Notebook    | [5768e68147](https://linux-hardware.org/?probe=5768e68147) | Jan 19, 2024 |
| Dell          | 05CNYF A01                  | Desktop     | [913528cc80](https://linux-hardware.org/?probe=913528cc80) | Jan 19, 2024 |
| Samsung       | RV415/RV515                 | Notebook    | [5002fd9959](https://linux-hardware.org/?probe=5002fd9959) | Jan 19, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [dafbbbb67c](https://linux-hardware.org/?probe=dafbbbb67c) | Jan 19, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [c7ab1232bb](https://linux-hardware.org/?probe=c7ab1232bb) | Jan 18, 2024 |
| Dell          | Inspiron 3480               | Notebook    | [0c15974fbb](https://linux-hardware.org/?probe=0c15974fbb) | Jan 18, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [3bb54b1a3a](https://linux-hardware.org/?probe=3bb54b1a3a) | Jan 18, 2024 |
| Dell          | Inspiron 3583               | Notebook    | [e70de12740](https://linux-hardware.org/?probe=e70de12740) | Jan 18, 2024 |
| HP            | 3048h                       | Desktop     | [e24f1cffa1](https://linux-hardware.org/?probe=e24f1cffa1) | Jan 18, 2024 |
| HP            | 2B0F                        | Desktop     | [ce5907f486](https://linux-hardware.org/?probe=ce5907f486) | Jan 18, 2024 |
| Samsung       | RV415/RV515                 | Notebook    | [282ae0ae50](https://linux-hardware.org/?probe=282ae0ae50) | Jan 18, 2024 |
| Acer          | Aspire A315-42G             | Notebook    | [5f7172f388](https://linux-hardware.org/?probe=5f7172f388) | Jan 18, 2024 |
| Megaware      | MW-H55H-CM                  | Desktop     | [69700659c8](https://linux-hardware.org/?probe=69700659c8) | Jan 18, 2024 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [86d22c9b40](https://linux-hardware.org/?probe=86d22c9b40) | Jan 17, 2024 |
| Acer          | Aspire A515-54              | Notebook    | [4d6487e7f5](https://linux-hardware.org/?probe=4d6487e7f5) | Jan 17, 2024 |
| Intel         | H61                         | Desktop     | [1d639194e4](https://linux-hardware.org/?probe=1d639194e4) | Jan 17, 2024 |
| ASUSTek       | K43E                        | Notebook    | [ac83dcf66b](https://linux-hardware.org/?probe=ac83dcf66b) | Jan 17, 2024 |
| Dell          | Inspiron 7348               | Notebook    | [a3c452af85](https://linux-hardware.org/?probe=a3c452af85) | Jan 17, 2024 |
| MSI           | G41M-S01                    | Desktop     | [373595b73a](https://linux-hardware.org/?probe=373595b73a) | Jan 16, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Notebook    | [6cfbe412a8](https://linux-hardware.org/?probe=6cfbe412a8) | Jan 16, 2024 |
| LG Electro... | A530-U.BE54P1               | Notebook    | [b396bdcd52](https://linux-hardware.org/?probe=b396bdcd52) | Jan 16, 2024 |
| Compaq        | 430                         | Notebook    | [a8dc50fedd](https://linux-hardware.org/?probe=a8dc50fedd) | Jan 16, 2024 |
| Acer          | Aspire F5-573G              | Notebook    | [6ba3da1f95](https://linux-hardware.org/?probe=6ba3da1f95) | Jan 16, 2024 |
| Dell          | 0C2KJT A00                  | Desktop     | [ef30ea4bc9](https://linux-hardware.org/?probe=ef30ea4bc9) | Jan 16, 2024 |
| Lenovo        | ThinkPad E490 20N90000BR    | Notebook    | [94ef2c20ba](https://linux-hardware.org/?probe=94ef2c20ba) | Jan 16, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [e5de4620f2](https://linux-hardware.org/?probe=e5de4620f2) | Jan 16, 2024 |
| Lenovo        | Yoga 300-11IBR 80M1         | Notebook    | [8bbf7916f3](https://linux-hardware.org/?probe=8bbf7916f3) | Jan 15, 2024 |
| PCWare        | IPMH510E                    | Desktop     | [a52f228033](https://linux-hardware.org/?probe=a52f228033) | Jan 15, 2024 |
| Acer          | Nitro AN515-58              | Notebook    | [ed413e1907](https://linux-hardware.org/?probe=ed413e1907) | Jan 15, 2024 |
| ASUSTek       | Z97M-PLUS/BR                | Desktop     | [8c2cab8ef9](https://linux-hardware.org/?probe=8c2cab8ef9) | Jan 15, 2024 |
| Gigabyte      | H410M H V3                  | Desktop     | [4c8c27e50b](https://linux-hardware.org/?probe=4c8c27e50b) | Jan 15, 2024 |
| Dell          | 0VHRW1 A03                  | Desktop     | [668e361f20](https://linux-hardware.org/?probe=668e361f20) | Jan 15, 2024 |
| Multilaser    | MLGW08                      | Notebook    | [abfe537d6f](https://linux-hardware.org/?probe=abfe537d6f) | Jan 15, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [29522391fa](https://linux-hardware.org/?probe=29522391fa) | Jan 15, 2024 |
| Gigabyte      | B85M-D3PH                   | Desktop     | [48dc7c39eb](https://linux-hardware.org/?probe=48dc7c39eb) | Jan 14, 2024 |
| Dell          | 0C2KJT A00                  | Desktop     | [72e5220f30](https://linux-hardware.org/?probe=72e5220f30) | Jan 14, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [95569b47c5](https://linux-hardware.org/?probe=95569b47c5) | Jan 14, 2024 |
| Apple         | MacBookPro11,1              | Notebook    | [e865dbe75e](https://linux-hardware.org/?probe=e865dbe75e) | Jan 14, 2024 |
| Lenovo        | Yoga Slim 6 14IAP8 83C7     | Notebook    | [4e4c095efb](https://linux-hardware.org/?probe=4e4c095efb) | Jan 14, 2024 |
| Positivo      | Harrison                    | Notebook    | [bc50c3c3ca](https://linux-hardware.org/?probe=bc50c3c3ca) | Jan 14, 2024 |
| Positivo      | POS-EINM10CB POSITIVO       | Desktop     | [ed11587f82](https://linux-hardware.org/?probe=ed11587f82) | Jan 14, 2024 |
| Samsung       | 300E5M/300E5L               | Notebook    | [9c43a79143](https://linux-hardware.org/?probe=9c43a79143) | Jan 14, 2024 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [c7e3069d99](https://linux-hardware.org/?probe=c7e3069d99) | Jan 14, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [dd179e8321](https://linux-hardware.org/?probe=dd179e8321) | Jan 14, 2024 |
| Lenovo        | ThinkPad T400 6474EU3       | Notebook    | [0d9d328c8d](https://linux-hardware.org/?probe=0d9d328c8d) | Jan 14, 2024 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [74cdfb120c](https://linux-hardware.org/?probe=74cdfb120c) | Jan 14, 2024 |
| Positivo      | Mobile                      | Notebook    | [750ee7ae05](https://linux-hardware.org/?probe=750ee7ae05) | Jan 14, 2024 |
| Biostar       | B350GT3                     | Desktop     | [d210ea56f8](https://linux-hardware.org/?probe=d210ea56f8) | Jan 14, 2024 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [b30f8df03f](https://linux-hardware.org/?probe=b30f8df03f) | Jan 14, 2024 |
| Positivo B... | VJFE53F11X-XXXXXX           | Notebook    | [ebd0135392](https://linux-hardware.org/?probe=ebd0135392) | Jan 14, 2024 |
| Digibras      | NH4CU03                     | Notebook    | [7cccdf824c](https://linux-hardware.org/?probe=7cccdf824c) | Jan 13, 2024 |
| Gigabyte      | H410M H V3                  | Desktop     | [ccf2a01168](https://linux-hardware.org/?probe=ccf2a01168) | Jan 13, 2024 |
| Intel         | B75                         | Desktop     | [9043007717](https://linux-hardware.org/?probe=9043007717) | Jan 13, 2024 |
| Samsung       | 550XED                      | Notebook    | [a9cdc1201c](https://linux-hardware.org/?probe=a9cdc1201c) | Jan 13, 2024 |
| ASUSTek       | M5A78L LE                   | Desktop     | [eae0903af4](https://linux-hardware.org/?probe=eae0903af4) | Jan 13, 2024 |
| Acer          | Nitro AN515-47              | Notebook    | [521b0ef15b](https://linux-hardware.org/?probe=521b0ef15b) | Jan 13, 2024 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [593bf4f394](https://linux-hardware.org/?probe=593bf4f394) | Jan 13, 2024 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [8d503de9a9](https://linux-hardware.org/?probe=8d503de9a9) | Jan 13, 2024 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [63d2ac1744](https://linux-hardware.org/?probe=63d2ac1744) | Jan 13, 2024 |
| Intel         | H81                         | Desktop     | [fee8b2f668](https://linux-hardware.org/?probe=fee8b2f668) | Jan 13, 2024 |
| Gigabyte      | GA-78LMT-S2P 78LMT2         | Desktop     | [b81e3342c6](https://linux-hardware.org/?probe=b81e3342c6) | Jan 13, 2024 |
| Dell          | Latitude E5450              | Notebook    | [a9275ec728](https://linux-hardware.org/?probe=a9275ec728) | Jan 13, 2024 |
| Apple         | MacBookPro10,1              | Notebook    | [dc905da8e7](https://linux-hardware.org/?probe=dc905da8e7) | Jan 12, 2024 |
| Dell          | Latitude 3440               | Notebook    | [b8145337d1](https://linux-hardware.org/?probe=b8145337d1) | Jan 12, 2024 |
| Dell          | Inspiron 5447               | Notebook    | [12ec54ffaf](https://linux-hardware.org/?probe=12ec54ffaf) | Jan 12, 2024 |
| Gigabyte      | B450M DS3H WIFI-CF          | Desktop     | [50ff1c2eb6](https://linux-hardware.org/?probe=50ff1c2eb6) | Jan 12, 2024 |
| Biostar       | A320MH                      | Desktop     | [5bec64f55c](https://linux-hardware.org/?probe=5bec64f55c) | Jan 12, 2024 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [3c870dba10](https://linux-hardware.org/?probe=3c870dba10) | Jan 12, 2024 |
| Gigabyte      | A520M H                     | Desktop     | [0394447477](https://linux-hardware.org/?probe=0394447477) | Jan 12, 2024 |
| Acer          | Predator PH315-53           | Notebook    | [bb3670e4b7](https://linux-hardware.org/?probe=bb3670e4b7) | Jan 12, 2024 |
| Gigabyte      | H97M-Gaming 3               | Desktop     | [6230f1ef11](https://linux-hardware.org/?probe=6230f1ef11) | Jan 12, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6b5cc546b5](https://linux-hardware.org/?probe=6b5cc546b5) | Jan 12, 2024 |
| HP            | Folio 13                    | Notebook    | [c2c19d8d51](https://linux-hardware.org/?probe=c2c19d8d51) | Jan 11, 2024 |
| Positivo      | S14SL01                     | Notebook    | [0dd36639d2](https://linux-hardware.org/?probe=0dd36639d2) | Jan 11, 2024 |
| Acer          | Aspire F5-573G              | Notebook    | [e37a928b80](https://linux-hardware.org/?probe=e37a928b80) | Jan 11, 2024 |
| Dell          | Inspiron 7572               | Notebook    | [19c0615c74](https://linux-hardware.org/?probe=19c0615c74) | Jan 11, 2024 |
| Dell          | Inspiron 7572               | Notebook    | [62b4f5a943](https://linux-hardware.org/?probe=62b4f5a943) | Jan 11, 2024 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [d109d298a5](https://linux-hardware.org/?probe=d109d298a5) | Jan 11, 2024 |
| Intel         | D945GCPE AAD97209-201       | Desktop     | [585f20355c](https://linux-hardware.org/?probe=585f20355c) | Jan 11, 2024 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [9d4a2ac12b](https://linux-hardware.org/?probe=9d4a2ac12b) | Jan 11, 2024 |
| Dell          | Inspiron 11-3168            | Notebook    | [f7763a1298](https://linux-hardware.org/?probe=f7763a1298) | Jan 10, 2024 |
| HP            | 1589                        | Desktop     | [57f5f20e09](https://linux-hardware.org/?probe=57f5f20e09) | Jan 10, 2024 |
| Intel         | H81                         | Desktop     | [1a1c6de235](https://linux-hardware.org/?probe=1a1c6de235) | Jan 10, 2024 |
| Positivo      | C14CU51                     | Notebook    | [efceb077f1](https://linux-hardware.org/?probe=efceb077f1) | Jan 10, 2024 |
| Toshiba       | STI NI 1401                 | Notebook    | [be4bcf5468](https://linux-hardware.org/?probe=be4bcf5468) | Jan 10, 2024 |
| Gigazone      | X107(B-B)                   | Notebook    | [a72cbb0097](https://linux-hardware.org/?probe=a72cbb0097) | Jan 10, 2024 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [f5e36298bf](https://linux-hardware.org/?probe=f5e36298bf) | Jan 10, 2024 |
| HP            | EliteBook 2540p             | Notebook    | [088dbf4c2f](https://linux-hardware.org/?probe=088dbf4c2f) | Jan 10, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [0420a7ddaa](https://linux-hardware.org/?probe=0420a7ddaa) | Jan 09, 2024 |
| Gigazone      | X107(B-B)                   | Notebook    | [54085fcb32](https://linux-hardware.org/?probe=54085fcb32) | Jan 09, 2024 |
| Dell          | Inspiron 15 3515            | Notebook    | [1ca72e6562](https://linux-hardware.org/?probe=1ca72e6562) | Jan 09, 2024 |
| Pegatron      | IPMIP-GS                    | Desktop     | [b732edef8d](https://linux-hardware.org/?probe=b732edef8d) | Jan 09, 2024 |
| Login Info... | LOG-QAL30                   | Notebook    | [7d09dd9a16](https://linux-hardware.org/?probe=7d09dd9a16) | Jan 09, 2024 |
| Lenovo        | SKYBAY SDK0J40700 WIN 32... | All in one  | [d22ff7b37d](https://linux-hardware.org/?probe=d22ff7b37d) | Jan 09, 2024 |
| Dell          | XPS 13 9300                 | Notebook    | [c054440c09](https://linux-hardware.org/?probe=c054440c09) | Jan 09, 2024 |
| Dell          | 00V62H A01                  | Desktop     | [e191ccd074](https://linux-hardware.org/?probe=e191ccd074) | Jan 09, 2024 |
| Toshiba       | IS 1413G                    | Notebook    | [5fa474d76d](https://linux-hardware.org/?probe=5fa474d76d) | Jan 09, 2024 |
| ASRock        | N68-S3 FX                   | Desktop     | [ce413f7140](https://linux-hardware.org/?probe=ce413f7140) | Jan 09, 2024 |
| Lenovo        | ThinkPad Edge E430 3254H... | Notebook    | [9ff97bbae7](https://linux-hardware.org/?probe=9ff97bbae7) | Jan 09, 2024 |
| Intel         | B75                         | Desktop     | [cc1767546e](https://linux-hardware.org/?probe=cc1767546e) | Jan 09, 2024 |
| Samsung       | 550XBE/350XBE               | Notebook    | [40266fb2b6](https://linux-hardware.org/?probe=40266fb2b6) | Jan 08, 2024 |
| Login Info... | LOG-QAL30                   | Notebook    | [73a33a80ae](https://linux-hardware.org/?probe=73a33a80ae) | Jan 08, 2024 |
| Digiboard     | NM70-TI                     | Desktop     | [9f740d246e](https://linux-hardware.org/?probe=9f740d246e) | Jan 08, 2024 |
| Pegatron      | IPMH61P1                    | Desktop     | [4a65448cb8](https://linux-hardware.org/?probe=4a65448cb8) | Jan 08, 2024 |
| Positivo B... | VJFE42F11X-B2891H           | Notebook    | [95a3cef171](https://linux-hardware.org/?probe=95a3cef171) | Jan 08, 2024 |
| MSI           | 970 GAMING                  | Desktop     | [68c61980ac](https://linux-hardware.org/?probe=68c61980ac) | Jan 08, 2024 |
| ALDO          | C2016-BSWI-D2               | Desktop     | [1e3d4c2e55](https://linux-hardware.org/?probe=1e3d4c2e55) | Jan 08, 2024 |
| Toshiba       | IS 1413G                    | Notebook    | [714f151f30](https://linux-hardware.org/?probe=714f151f30) | Jan 08, 2024 |
| Biostar       | A68MHE                      | Desktop     | [ed7007dc1f](https://linux-hardware.org/?probe=ed7007dc1f) | Jan 07, 2024 |
| Intel         | H61                         | Desktop     | [a0d05acffb](https://linux-hardware.org/?probe=a0d05acffb) | Jan 07, 2024 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [015e318a3b](https://linux-hardware.org/?probe=015e318a3b) | Jan 07, 2024 |
| Samsung       | RV415/RV515                 | Notebook    | [5451d552aa](https://linux-hardware.org/?probe=5451d552aa) | Jan 07, 2024 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [2c36dcaa22](https://linux-hardware.org/?probe=2c36dcaa22) | Jan 07, 2024 |
| ASUSTek       | PRIME H410M-E               | Desktop     | [3e11f092ef](https://linux-hardware.org/?probe=3e11f092ef) | Jan 07, 2024 |
| Lenovo        | ThinkPad L14 Gen 3 21C60... | Notebook    | [739eae84a2](https://linux-hardware.org/?probe=739eae84a2) | Jan 07, 2024 |
| Biostar       | A320MH                      | Desktop     | [9bec9420ab](https://linux-hardware.org/?probe=9bec9420ab) | Jan 06, 2024 |
| Acer          | Aspire E5-574               | Notebook    | [4c6e591812](https://linux-hardware.org/?probe=4c6e591812) | Jan 06, 2024 |
| AMD           | A520                        | Desktop     | [844129c6ba](https://linux-hardware.org/?probe=844129c6ba) | Jan 06, 2024 |
| Acer          | Aspire A514-54              | Notebook    | [513f1c7737](https://linux-hardware.org/?probe=513f1c7737) | Jan 06, 2024 |
| Acer          | Aspire A514-54              | Notebook    | [97b3214a42](https://linux-hardware.org/?probe=97b3214a42) | Jan 06, 2024 |
| Intel         | B75                         | Desktop     | [b2190f0cff](https://linux-hardware.org/?probe=b2190f0cff) | Jan 06, 2024 |
| Unknown       | MZ-B75-S                    | Desktop     | [2821ddba00](https://linux-hardware.org/?probe=2821ddba00) | Jan 06, 2024 |
| ASRock        | B550M-HDV                   | Desktop     | [b247cc09d2](https://linux-hardware.org/?probe=b247cc09d2) | Jan 06, 2024 |
| Intel         | B75                         | Desktop     | [648128d27a](https://linux-hardware.org/?probe=648128d27a) | Jan 06, 2024 |
| AMD           | A520                        | Desktop     | [ab02db5a08](https://linux-hardware.org/?probe=ab02db5a08) | Jan 06, 2024 |
| HP            | Pavilion 14                 | Notebook    | [82550ce5ae](https://linux-hardware.org/?probe=82550ce5ae) | Jan 06, 2024 |
| Gigabyte      | Z97X-UD5H-BK                | Desktop     | [ad5cae0bab](https://linux-hardware.org/?probe=ad5cae0bab) | Jan 06, 2024 |
| Dell          | Latitude 3420               | Notebook    | [39d522ead5](https://linux-hardware.org/?probe=39d522ead5) | Jan 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [d135277737](https://linux-hardware.org/?probe=d135277737) | Jan 05, 2024 |
| MSI           | B560M PRO-E                 | Desktop     | [0fd8636acb](https://linux-hardware.org/?probe=0fd8636acb) | Jan 05, 2024 |
| Unknown       | Unknown                     | Notebook    | [5e7209bd1a](https://linux-hardware.org/?probe=5e7209bd1a) | Jan 05, 2024 |
| Toshiba       | IS 1413G                    | Notebook    | [5e4cd95800](https://linux-hardware.org/?probe=5e4cd95800) | Jan 05, 2024 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [05f8b32828](https://linux-hardware.org/?probe=05f8b32828) | Jan 05, 2024 |
| ASUSTek       | TP301UA                     | Notebook    | [0617a0e757](https://linux-hardware.org/?probe=0617a0e757) | Jan 05, 2024 |
| Digibras      | NH4CU03                     | Notebook    | [be0eab4038](https://linux-hardware.org/?probe=be0eab4038) | Jan 05, 2024 |
| Dell          | 01XK1W A00                  | Desktop     | [90e3c8644a](https://linux-hardware.org/?probe=90e3c8644a) | Jan 05, 2024 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | Desktop     | [34984994c3](https://linux-hardware.org/?probe=34984994c3) | Jan 05, 2024 |
| Samsung       | 670Z5E                      | Notebook    | [c4bce26993](https://linux-hardware.org/?probe=c4bce26993) | Jan 04, 2024 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [8ea8935806](https://linux-hardware.org/?probe=8ea8935806) | Jan 04, 2024 |
| MSI           | A320M-A PRO                 | Desktop     | [a5cb369ad3](https://linux-hardware.org/?probe=a5cb369ad3) | Jan 04, 2024 |
| Acer          | Nitro AN515-44              | Notebook    | [6a2df7d4aa](https://linux-hardware.org/?probe=6a2df7d4aa) | Jan 04, 2024 |
| Acer          | Aspire A515-56G             | Notebook    | [084e91606c](https://linux-hardware.org/?probe=084e91606c) | Jan 04, 2024 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [e4413dc480](https://linux-hardware.org/?probe=e4413dc480) | Jan 04, 2024 |
| LG Electro... | 23V545-G.BK55P1             | Notebook    | [6cf752515c](https://linux-hardware.org/?probe=6cf752515c) | Jan 04, 2024 |
| Acer          | Aspire E1-572               | Notebook    | [a68d0f8100](https://linux-hardware.org/?probe=a68d0f8100) | Jan 04, 2024 |
| Acer          | Aspire A515-56G             | Notebook    | [e1554fcb98](https://linux-hardware.org/?probe=e1554fcb98) | Jan 04, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [31b1e0e2ed](https://linux-hardware.org/?probe=31b1e0e2ed) | Jan 04, 2024 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [3557687358](https://linux-hardware.org/?probe=3557687358) | Jan 04, 2024 |
| Positivo      | Q4128CI                     | Notebook    | [3b0b3095d2](https://linux-hardware.org/?probe=3b0b3095d2) | Jan 03, 2024 |
| Positivo      | Q4128CI                     | Notebook    | [7f3766e4dc](https://linux-hardware.org/?probe=7f3766e4dc) | Jan 03, 2024 |
| Intel         | X99 V1.0                    | Desktop     | [554fbc7716](https://linux-hardware.org/?probe=554fbc7716) | Jan 03, 2024 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [781084af86](https://linux-hardware.org/?probe=781084af86) | Jan 03, 2024 |
| Positivo      | C4128A-15                   | Notebook    | [52bd86685b](https://linux-hardware.org/?probe=52bd86685b) | Jan 03, 2024 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [1755330be9](https://linux-hardware.org/?probe=1755330be9) | Jan 03, 2024 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [c278d1e669](https://linux-hardware.org/?probe=c278d1e669) | Jan 03, 2024 |
| Dell          | Inspiron 3442               | Notebook    | [6d9d64e6f6](https://linux-hardware.org/?probe=6d9d64e6f6) | Jan 03, 2024 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [fb4e22f4a6](https://linux-hardware.org/?probe=fb4e22f4a6) | Jan 03, 2024 |
| Dell          | 0PV3YR A05                  | Server      | [cb77338610](https://linux-hardware.org/?probe=cb77338610) | Jan 03, 2024 |
| Acer          | Nitro AN515-52              | Notebook    | [b789e33c24](https://linux-hardware.org/?probe=b789e33c24) | Jan 03, 2024 |
| Positivo B... | VJFE42F11X-B2891H           | Notebook    | [47c3c6c806](https://linux-hardware.org/?probe=47c3c6c806) | Jan 03, 2024 |
| Acer          | Aspire ES1-572              | Notebook    | [65c6d98c36](https://linux-hardware.org/?probe=65c6d98c36) | Jan 02, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [a948fd2006](https://linux-hardware.org/?probe=a948fd2006) | Jan 02, 2024 |
| Dell          | 0VHXCD A03                  | Desktop     | [1c46ebc4c4](https://linux-hardware.org/?probe=1c46ebc4c4) | Jan 02, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [589f53595e](https://linux-hardware.org/?probe=589f53595e) | Jan 02, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [c038b7f7e4](https://linux-hardware.org/?probe=c038b7f7e4) | Jan 02, 2024 |
| Dell          | Inspiron 15-3567            | Notebook    | [50d926ec76](https://linux-hardware.org/?probe=50d926ec76) | Jan 02, 2024 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [daf43e4658](https://linux-hardware.org/?probe=daf43e4658) | Jan 02, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [88bc9fe11f](https://linux-hardware.org/?probe=88bc9fe11f) | Jan 02, 2024 |
| Dell          | 0PV3YR A05                  | Server      | [d87da5bee4](https://linux-hardware.org/?probe=d87da5bee4) | Jan 02, 2024 |
| HP            | 15 Notebook PC              | Notebook    | [9eb25ba0bf](https://linux-hardware.org/?probe=9eb25ba0bf) | Jan 02, 2024 |
| Acer          | Nitro AN515-44              | Notebook    | [9ac5286530](https://linux-hardware.org/?probe=9ac5286530) | Jan 02, 2024 |
| Philco        | 14M2                        | Notebook    | [b5771423fb](https://linux-hardware.org/?probe=b5771423fb) | Jan 02, 2024 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [3de5d6e06c](https://linux-hardware.org/?probe=3de5d6e06c) | Jan 02, 2024 |
| Positivo      | C464C                       | Convertible | [2301ed86ce](https://linux-hardware.org/?probe=2301ed86ce) | Jan 02, 2024 |
| Acer          | Aspire A515-51G             | Notebook    | [e7b0efb20a](https://linux-hardware.org/?probe=e7b0efb20a) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [14df5ebb53](https://linux-hardware.org/?probe=14df5ebb53) | Jan 02, 2024 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [00ee13cdb6](https://linux-hardware.org/?probe=00ee13cdb6) | Jan 01, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [cdb97873fa](https://linux-hardware.org/?probe=cdb97873fa) | Jan 01, 2024 |
| Timi          | RedmiBook Pro 14S           | Notebook    | [08718e205b](https://linux-hardware.org/?probe=08718e205b) | Jan 01, 2024 |
| Notebook      | NJx0MU                      | Notebook    | [f9d4fa4d55](https://linux-hardware.org/?probe=f9d4fa4d55) | Jan 01, 2024 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [6f2227d209](https://linux-hardware.org/?probe=6f2227d209) | Jan 01, 2024 |
| Sony          | VJF153                      | Notebook    | [9bf924f424](https://linux-hardware.org/?probe=9bf924f424) | Jan 01, 2024 |
| Dell          | Latitude 5310               | Notebook    | [87c543db6f](https://linux-hardware.org/?probe=87c543db6f) | Jan 01, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [e8e24c9091](https://linux-hardware.org/?probe=e8e24c9091) | Jan 01, 2024 |
| ASUSTek       | M2N68-AM SE2                | Desktop     | [553bcade60](https://linux-hardware.org/?probe=553bcade60) | Jan 01, 2024 |
| Sony          | VJF153                      | Notebook    | [b3949d3670](https://linux-hardware.org/?probe=b3949d3670) | Jan 01, 2024 |
| Dell          | 0PV3YR A05                  | Server      | [0bf596656b](https://linux-hardware.org/?probe=0bf596656b) | Jan 01, 2024 |
| ASUSTek       | PRIME J4005I-C/BR           | Desktop     | [12a957b14b](https://linux-hardware.org/?probe=12a957b14b) | Jan 01, 2024 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [c6a3df522b](https://linux-hardware.org/?probe=c6a3df522b) | Dec 31, 2023 |
| ASUSTek       | PRIME J4005I-C/BR           | Desktop     | [7f4bbc6a71](https://linux-hardware.org/?probe=7f4bbc6a71) | Dec 31, 2023 |
| ASUSTek       | PRIME J4005I-C/BR           | Desktop     | [5b8817b3de](https://linux-hardware.org/?probe=5b8817b3de) | Dec 31, 2023 |
| Positivo      | POS-PIH55BXA                | Desktop     | [6ab5cb395f](https://linux-hardware.org/?probe=6ab5cb395f) | Dec 31, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [61946a6719](https://linux-hardware.org/?probe=61946a6719) | Dec 31, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [390160b8e5](https://linux-hardware.org/?probe=390160b8e5) | Dec 31, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [76a4e84057](https://linux-hardware.org/?probe=76a4e84057) | Dec 31, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [b67462ae25](https://linux-hardware.org/?probe=b67462ae25) | Dec 31, 2023 |
| Toshiba       | STI 013442                  | Desktop     | [c8488906f2](https://linux-hardware.org/?probe=c8488906f2) | Dec 31, 2023 |
| Toshiba       | STI 013442                  | Desktop     | [ed56d2dcb5](https://linux-hardware.org/?probe=ed56d2dcb5) | Dec 31, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c7f2d68d77](https://linux-hardware.org/?probe=c7f2d68d77) | Dec 30, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [495efd257e](https://linux-hardware.org/?probe=495efd257e) | Dec 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [2352ac6075](https://linux-hardware.org/?probe=2352ac6075) | Dec 30, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [5f33ce2d18](https://linux-hardware.org/?probe=5f33ce2d18) | Dec 30, 2023 |
| Dell          | Inspiron 7460               | Notebook    | [1085eef155](https://linux-hardware.org/?probe=1085eef155) | Dec 30, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5d1ed5c106](https://linux-hardware.org/?probe=5d1ed5c106) | Dec 30, 2023 |
| Intel         | B75                         | Desktop     | [df9a51de80](https://linux-hardware.org/?probe=df9a51de80) | Dec 30, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82MD       | Notebook    | [33556742c3](https://linux-hardware.org/?probe=33556742c3) | Dec 30, 2023 |
| Positivo      | C4128A-15                   | Notebook    | [6416d967b8](https://linux-hardware.org/?probe=6416d967b8) | Dec 30, 2023 |
| Positivo      | C4128A-15                   | Notebook    | [bd9afc6d73](https://linux-hardware.org/?probe=bd9afc6d73) | Dec 30, 2023 |
| Positivo      | Harrison                    | Notebook    | [bf31594bef](https://linux-hardware.org/?probe=bf31594bef) | Dec 30, 2023 |
| Lenovo        | SDK0K11822 WIN              | Desktop     | [075f05f3df](https://linux-hardware.org/?probe=075f05f3df) | Dec 30, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [35e2f8c10c](https://linux-hardware.org/?probe=35e2f8c10c) | Dec 29, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [c7e5dc5d9b](https://linux-hardware.org/?probe=c7e5dc5d9b) | Dec 29, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [e3ecbaedf9](https://linux-hardware.org/?probe=e3ecbaedf9) | Dec 29, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | Desktop     | [342164a6a4](https://linux-hardware.org/?probe=342164a6a4) | Dec 29, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [64dddef2fa](https://linux-hardware.org/?probe=64dddef2fa) | Dec 29, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [03199adbd4](https://linux-hardware.org/?probe=03199adbd4) | Dec 29, 2023 |
| Dell          | Inspiron 3443               | Notebook    | [0c56a0465b](https://linux-hardware.org/?probe=0c56a0465b) | Dec 29, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [dffaa09f84](https://linux-hardware.org/?probe=dffaa09f84) | Dec 29, 2023 |
| Dell          | Inspiron 3584               | Notebook    | [818e96295f](https://linux-hardware.org/?probe=818e96295f) | Dec 29, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [3133f699e1](https://linux-hardware.org/?probe=3133f699e1) | Dec 29, 2023 |
| Lenovo        | B490 37722KP                | Notebook    | [194971e987](https://linux-hardware.org/?probe=194971e987) | Dec 29, 2023 |
| Positivo      | P5GC-MX/CKD/POST/SI         | Desktop     | [1503c2f4b8](https://linux-hardware.org/?probe=1503c2f4b8) | Dec 29, 2023 |
| Positivo      | P5GC-MX/CKD/POST/SI         | Desktop     | [08dadf5cbb](https://linux-hardware.org/?probe=08dadf5cbb) | Dec 29, 2023 |
| Acer          | Aspire 4736Z                | Notebook    | [ea8dffb40f](https://linux-hardware.org/?probe=ea8dffb40f) | Dec 29, 2023 |
| HP            | Pavilion dv6                | Notebook    | [9992f9523e](https://linux-hardware.org/?probe=9992f9523e) | Dec 29, 2023 |
| Pegatron      | IPMIP-GS                    | Desktop     | [d8ace6bbb7](https://linux-hardware.org/?probe=d8ace6bbb7) | Dec 29, 2023 |
| Intel         | H61                         | Desktop     | [ee2aa1c105](https://linux-hardware.org/?probe=ee2aa1c105) | Dec 29, 2023 |
| Intel         | H61                         | Desktop     | [baec7a3074](https://linux-hardware.org/?probe=baec7a3074) | Dec 28, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [a86830ecd2](https://linux-hardware.org/?probe=a86830ecd2) | Dec 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [2d53ff60cb](https://linux-hardware.org/?probe=2d53ff60cb) | Dec 28, 2023 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [4f74bf57df](https://linux-hardware.org/?probe=4f74bf57df) | Dec 28, 2023 |
| Rockchip      | RK3588 OPi 5 Plus           | Soc         | [59ae3d3d52](https://linux-hardware.org/?probe=59ae3d3d52) | Dec 28, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [e01ab0c412](https://linux-hardware.org/?probe=e01ab0c412) | Dec 28, 2023 |
| Positivo      | Harrison                    | Notebook    | [e12b67378a](https://linux-hardware.org/?probe=e12b67378a) | Dec 28, 2023 |
| Lenovo        | SDK0K11822 WIN              | Desktop     | [449d548765](https://linux-hardware.org/?probe=449d548765) | Dec 28, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [404320e4d7](https://linux-hardware.org/?probe=404320e4d7) | Dec 28, 2023 |
| MACHINIST     | E5-D8-MAX V1.1              | Desktop     | [1cdeeaefff](https://linux-hardware.org/?probe=1cdeeaefff) | Dec 28, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [a1652ba789](https://linux-hardware.org/?probe=a1652ba789) | Dec 28, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [255c0c95bc](https://linux-hardware.org/?probe=255c0c95bc) | Dec 28, 2023 |
| Intel         | B85                         | Desktop     | [ae03ff7103](https://linux-hardware.org/?probe=ae03ff7103) | Dec 28, 2023 |
| win elemen... | MoreFine S500+              | Notebook    | [6880205d9e](https://linux-hardware.org/?probe=6880205d9e) | Dec 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [09d63b8472](https://linux-hardware.org/?probe=09d63b8472) | Dec 28, 2023 |
| Purism        | Librem 14                   | Notebook    | [215d922345](https://linux-hardware.org/?probe=215d922345) | Dec 28, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [8c5f1e135b](https://linux-hardware.org/?probe=8c5f1e135b) | Dec 28, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [c62c257897](https://linux-hardware.org/?probe=c62c257897) | Dec 27, 2023 |
| HP            | 1589                        | Desktop     | [c52940817e](https://linux-hardware.org/?probe=c52940817e) | Dec 27, 2023 |
| Dell          | G3 3500                     | Notebook    | [87c0216250](https://linux-hardware.org/?probe=87c0216250) | Dec 27, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [84242f4904](https://linux-hardware.org/?probe=84242f4904) | Dec 27, 2023 |
| ASUSTek       | H81M-A/BR                   | Desktop     | [87cae62baf](https://linux-hardware.org/?probe=87cae62baf) | Dec 27, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [de1dd08f64](https://linux-hardware.org/?probe=de1dd08f64) | Dec 27, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [04601b4053](https://linux-hardware.org/?probe=04601b4053) | Dec 27, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [6369debba7](https://linux-hardware.org/?probe=6369debba7) | Dec 26, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [40a7073595](https://linux-hardware.org/?probe=40a7073595) | Dec 26, 2023 |
| PCWare        | IPMH310G PRO                | Desktop     | [c4668fe41d](https://linux-hardware.org/?probe=c4668fe41d) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [971e3fe3eb](https://linux-hardware.org/?probe=971e3fe3eb) | Dec 26, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [7d873eb94f](https://linux-hardware.org/?probe=7d873eb94f) | Dec 26, 2023 |
| Acer          | Predator Orion PO5-620      | Desktop     | [2d7731ff10](https://linux-hardware.org/?probe=2d7731ff10) | Dec 26, 2023 |
| Intel         | X99-P4 V1.0                 | Desktop     | [69e399de83](https://linux-hardware.org/?probe=69e399de83) | Dec 25, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [a68e5c51b4](https://linux-hardware.org/?probe=a68e5c51b4) | Dec 25, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [022fc838b1](https://linux-hardware.org/?probe=022fc838b1) | Dec 25, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [e50028a157](https://linux-hardware.org/?probe=e50028a157) | Dec 25, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [eade6242b7](https://linux-hardware.org/?probe=eade6242b7) | Dec 25, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [7f11ff0265](https://linux-hardware.org/?probe=7f11ff0265) | Dec 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [850fedd929](https://linux-hardware.org/?probe=850fedd929) | Dec 25, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [02f6066234](https://linux-hardware.org/?probe=02f6066234) | Dec 25, 2023 |
| Google        | Aleena                      | Notebook    | [a5a888a877](https://linux-hardware.org/?probe=a5a888a877) | Dec 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [75a45b1c88](https://linux-hardware.org/?probe=75a45b1c88) | Dec 25, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [6705535031](https://linux-hardware.org/?probe=6705535031) | Dec 25, 2023 |
| Intel         | H61                         | Desktop     | [0396f0429a](https://linux-hardware.org/?probe=0396f0429a) | Dec 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [87cef435db](https://linux-hardware.org/?probe=87cef435db) | Dec 24, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [a54e95fcab](https://linux-hardware.org/?probe=a54e95fcab) | Dec 24, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [a5d5ac012b](https://linux-hardware.org/?probe=a5d5ac012b) | Dec 24, 2023 |
| Intel         | H61                         | Desktop     | [a10f481c10](https://linux-hardware.org/?probe=a10f481c10) | Dec 24, 2023 |
| Valve         | Jupiter                     | Notebook    | [19f8d4f0b4](https://linux-hardware.org/?probe=19f8d4f0b4) | Dec 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [43718a5746](https://linux-hardware.org/?probe=43718a5746) | Dec 24, 2023 |
| Samsung       | RV415/RV515                 | Notebook    | [da980644b4](https://linux-hardware.org/?probe=da980644b4) | Dec 24, 2023 |
| Intel         | B85                         | Desktop     | [5b462c9ed1](https://linux-hardware.org/?probe=5b462c9ed1) | Dec 24, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [b57fdd9854](https://linux-hardware.org/?probe=b57fdd9854) | Dec 24, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [cc87c11e7b](https://linux-hardware.org/?probe=cc87c11e7b) | Dec 24, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [dd658b1151](https://linux-hardware.org/?probe=dd658b1151) | Dec 23, 2023 |
| ASUSTek       | TUF B360-PLUS GAMING        | Desktop     | [b1c3408d24](https://linux-hardware.org/?probe=b1c3408d24) | Dec 23, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [52a7a4d6d8](https://linux-hardware.org/?probe=52a7a4d6d8) | Dec 23, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [d409d2fe79](https://linux-hardware.org/?probe=d409d2fe79) | Dec 23, 2023 |
| Lenovo        | IdeaPad S145-15IGM 81WT     | Notebook    | [eae7bab112](https://linux-hardware.org/?probe=eae7bab112) | Dec 23, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [aaf6ab3d26](https://linux-hardware.org/?probe=aaf6ab3d26) | Dec 23, 2023 |
| Dell          | 0NW73C A00                  | Desktop     | [5ac83b9740](https://linux-hardware.org/?probe=5ac83b9740) | Dec 23, 2023 |
| Lenovo        | ThinkPad E14 20RB000UBR     | Notebook    | [d65cca0578](https://linux-hardware.org/?probe=d65cca0578) | Dec 22, 2023 |
| Intel         | H61                         | Desktop     | [72c7724ef0](https://linux-hardware.org/?probe=72c7724ef0) | Dec 22, 2023 |
| Colorful T... | A320M-M.2 PRO V15           | Desktop     | [821494cfbf](https://linux-hardware.org/?probe=821494cfbf) | Dec 22, 2023 |
| Positivo      | W940TU                      | Notebook    | [40dff18a74](https://linux-hardware.org/?probe=40dff18a74) | Dec 22, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c83a6a5f5d](https://linux-hardware.org/?probe=c83a6a5f5d) | Dec 22, 2023 |
| PCWare        | IPMH61R3                    | Desktop     | [891c2058a8](https://linux-hardware.org/?probe=891c2058a8) | Dec 22, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [5f1c04a086](https://linux-hardware.org/?probe=5f1c04a086) | Dec 22, 2023 |
| Dell          | Inspiron 7572               | Notebook    | [b6a03a82a6](https://linux-hardware.org/?probe=b6a03a82a6) | Dec 22, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [e0cd6655cb](https://linux-hardware.org/?probe=e0cd6655cb) | Dec 22, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [1767c5b291](https://linux-hardware.org/?probe=1767c5b291) | Dec 21, 2023 |
| Dell          | 0HD5W2 A00                  | Desktop     | [2bd748691b](https://linux-hardware.org/?probe=2bd748691b) | Dec 21, 2023 |
| Gigabyte      | B560M AORUS ELITE           | Desktop     | [82304c2a5f](https://linux-hardware.org/?probe=82304c2a5f) | Dec 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [808fe0568d](https://linux-hardware.org/?probe=808fe0568d) | Dec 21, 2023 |
| Dell          | Inspiron 5448               | Notebook    | [edf818740d](https://linux-hardware.org/?probe=edf818740d) | Dec 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [2675cca8c2](https://linux-hardware.org/?probe=2675cca8c2) | Dec 21, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [2c9d7daa8b](https://linux-hardware.org/?probe=2c9d7daa8b) | Dec 21, 2023 |
| Dell          | Inspiron 7572               | Notebook    | [cd9385a64b](https://linux-hardware.org/?probe=cd9385a64b) | Dec 21, 2023 |
| Alienware     | m16 R1 AMD                  | Notebook    | [8fc737975c](https://linux-hardware.org/?probe=8fc737975c) | Dec 21, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [d0276bd5b7](https://linux-hardware.org/?probe=d0276bd5b7) | Dec 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [aecbb83cd6](https://linux-hardware.org/?probe=aecbb83cd6) | Dec 20, 2023 |
| Unknown       | Orange Pi 5B                | Soc         | [f809840436](https://linux-hardware.org/?probe=f809840436) | Dec 20, 2023 |
| Unknown       | Generic RK322x TV Box       | Mini pc     | [6b0274e802](https://linux-hardware.org/?probe=6b0274e802) | Dec 20, 2023 |
| ASUSTek       | X556URK                     | Notebook    | [b4f01c5bd5](https://linux-hardware.org/?probe=b4f01c5bd5) | Dec 19, 2023 |
| Daten Tecn... | DT02-M4                     | Notebook    | [8f754589f6](https://linux-hardware.org/?probe=8f754589f6) | Dec 19, 2023 |
| ANGXUN        | X79-VG2 V1.3                | Desktop     | [532c5b5ddc](https://linux-hardware.org/?probe=532c5b5ddc) | Dec 19, 2023 |
| Gigabyte      | 970-GAMING                  | Desktop     | [403d617fdd](https://linux-hardware.org/?probe=403d617fdd) | Dec 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [ec86cf0c12](https://linux-hardware.org/?probe=ec86cf0c12) | Dec 19, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [bd012749e2](https://linux-hardware.org/?probe=bd012749e2) | Dec 19, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cc583aec32](https://linux-hardware.org/?probe=cc583aec32) | Dec 19, 2023 |
| Biostar       | A320MH                      | Desktop     | [9ec714a02b](https://linux-hardware.org/?probe=9ec714a02b) | Dec 19, 2023 |
| Acer          | Nitro AN515-43              | Notebook    | [963de967ae](https://linux-hardware.org/?probe=963de967ae) | Dec 19, 2023 |
| ECS           | H61H2-M2                    | Desktop     | [d38a6ca473](https://linux-hardware.org/?probe=d38a6ca473) | Dec 19, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [c387c14ff7](https://linux-hardware.org/?probe=c387c14ff7) | Dec 18, 2023 |
| Intel         | DH61WW AAG23116-206         | Desktop     | [a1760c437e](https://linux-hardware.org/?probe=a1760c437e) | Dec 18, 2023 |
| Acer          | Aspire E5-571               | Notebook    | [55a802f43c](https://linux-hardware.org/?probe=55a802f43c) | Dec 18, 2023 |
| Dell          | Latitude 3420               | Notebook    | [5fdda723cd](https://linux-hardware.org/?probe=5fdda723cd) | Dec 18, 2023 |
| MSI           | B560M PRO-E                 | Desktop     | [f8bcb73f0b](https://linux-hardware.org/?probe=f8bcb73f0b) | Dec 18, 2023 |
| GPD           | G1619-04                    | Notebook    | [63b517665b](https://linux-hardware.org/?probe=63b517665b) | Dec 18, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [e4935d995b](https://linux-hardware.org/?probe=e4935d995b) | Dec 18, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [6d6246b5bf](https://linux-hardware.org/?probe=6d6246b5bf) | Dec 18, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [458a8fb3f1](https://linux-hardware.org/?probe=458a8fb3f1) | Dec 18, 2023 |
| Dell          | G3 3590                     | Notebook    | [15decf2dfc](https://linux-hardware.org/?probe=15decf2dfc) | Dec 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [ec4da8d1a3](https://linux-hardware.org/?probe=ec4da8d1a3) | Dec 18, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [b06e8fbef4](https://linux-hardware.org/?probe=b06e8fbef4) | Dec 18, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [1bd5e5e36f](https://linux-hardware.org/?probe=1bd5e5e36f) | Dec 18, 2023 |
| Compal        | PBL1011                     | Notebook    | [8983f2e331](https://linux-hardware.org/?probe=8983f2e331) | Dec 18, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [c18f5d3a21](https://linux-hardware.org/?probe=c18f5d3a21) | Dec 18, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [982ae3655c](https://linux-hardware.org/?probe=982ae3655c) | Dec 18, 2023 |
| ASRock        | H61M-HP4                    | Desktop     | [05fe81411e](https://linux-hardware.org/?probe=05fe81411e) | Dec 18, 2023 |
| Biostar       | B550MH                      | Desktop     | [32131b6631](https://linux-hardware.org/?probe=32131b6631) | Dec 17, 2023 |
| Biostar       | B550MH                      | Desktop     | [97d9affd9d](https://linux-hardware.org/?probe=97d9affd9d) | Dec 17, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [ddf72aef4e](https://linux-hardware.org/?probe=ddf72aef4e) | Dec 17, 2023 |
| Dell          | 07N90W A02                  | Desktop     | [0c471e8b44](https://linux-hardware.org/?probe=0c471e8b44) | Dec 17, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [b6b44f1b80](https://linux-hardware.org/?probe=b6b44f1b80) | Dec 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [1446130ae9](https://linux-hardware.org/?probe=1446130ae9) | Dec 17, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [dde306e444](https://linux-hardware.org/?probe=dde306e444) | Dec 17, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [4e47d91bc7](https://linux-hardware.org/?probe=4e47d91bc7) | Dec 17, 2023 |
| Dell          | 053CWD A00                  | Desktop     | [6cee8cbfd7](https://linux-hardware.org/?probe=6cee8cbfd7) | Dec 17, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [720421dab6](https://linux-hardware.org/?probe=720421dab6) | Dec 17, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [80281cb193](https://linux-hardware.org/?probe=80281cb193) | Dec 17, 2023 |
| Dell          | Inspiron N4030              | Notebook    | [a77869199a](https://linux-hardware.org/?probe=a77869199a) | Dec 17, 2023 |
| Samsung       | 550XDA                      | Notebook    | [10ec283ed4](https://linux-hardware.org/?probe=10ec283ed4) | Dec 17, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [be717cf064](https://linux-hardware.org/?probe=be717cf064) | Dec 16, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [570a822273](https://linux-hardware.org/?probe=570a822273) | Dec 16, 2023 |
| Intel         | SHARKBAY                    | Desktop     | [efe58ba5df](https://linux-hardware.org/?probe=efe58ba5df) | Dec 16, 2023 |
| OEM           | B75 Ver:1.41                | Desktop     | [4117a986c8](https://linux-hardware.org/?probe=4117a986c8) | Dec 16, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [890cf9cc41](https://linux-hardware.org/?probe=890cf9cc41) | Dec 16, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [7da400b028](https://linux-hardware.org/?probe=7da400b028) | Dec 16, 2023 |
| Dell          | Vostro 5490                 | Notebook    | [ca117be9d4](https://linux-hardware.org/?probe=ca117be9d4) | Dec 16, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [de83793263](https://linux-hardware.org/?probe=de83793263) | Dec 16, 2023 |
| PCWare        | IPMH61R3                    | Desktop     | [ecac398c88](https://linux-hardware.org/?probe=ecac398c88) | Dec 15, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [09d89c7989](https://linux-hardware.org/?probe=09d89c7989) | Dec 15, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [06ed7608bf](https://linux-hardware.org/?probe=06ed7608bf) | Dec 15, 2023 |
| Dell          | Inspiron 1525               | Notebook    | [b9daaa5978](https://linux-hardware.org/?probe=b9daaa5978) | Dec 15, 2023 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [39094226f9](https://linux-hardware.org/?probe=39094226f9) | Dec 15, 2023 |
| Supermicro    | X10SAE                      | Server      | [a3dda288d1](https://linux-hardware.org/?probe=a3dda288d1) | Dec 15, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [7e43febcae](https://linux-hardware.org/?probe=7e43febcae) | Dec 15, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [a043c13550](https://linux-hardware.org/?probe=a043c13550) | Dec 14, 2023 |
| ASUSTek       | TUF Gaming B650M-PLUS       | Desktop     | [a142ccc9e7](https://linux-hardware.org/?probe=a142ccc9e7) | Dec 14, 2023 |
| Dell          | 0NW6H5 A00                  | Desktop     | [eb487bbab2](https://linux-hardware.org/?probe=eb487bbab2) | Dec 14, 2023 |
| Intel         | DH61BF AAG81311-101         | Desktop     | [9d6455339e](https://linux-hardware.org/?probe=9d6455339e) | Dec 14, 2023 |
| MSI           | MEG Z390 GODLIKE            | Desktop     | [e384ee26a6](https://linux-hardware.org/?probe=e384ee26a6) | Dec 14, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [c16cb0947e](https://linux-hardware.org/?probe=c16cb0947e) | Dec 14, 2023 |
| Dell          | G15 5520                    | Notebook    | [12b6fa0914](https://linux-hardware.org/?probe=12b6fa0914) | Dec 14, 2023 |
| Biostar       | X370GT3                     | Desktop     | [b910738e8f](https://linux-hardware.org/?probe=b910738e8f) | Dec 14, 2023 |
| Dell          | Inspiron 7560               | Notebook    | [83034fb404](https://linux-hardware.org/?probe=83034fb404) | Dec 14, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [d2b1e67451](https://linux-hardware.org/?probe=d2b1e67451) | Dec 14, 2023 |
| Dell          | G15 5520                    | Notebook    | [d212fe82aa](https://linux-hardware.org/?probe=d212fe82aa) | Dec 14, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [1ff0d683f4](https://linux-hardware.org/?probe=1ff0d683f4) | Dec 13, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [1522c84fb7](https://linux-hardware.org/?probe=1522c84fb7) | Dec 13, 2023 |
| Positivo      | POS-PIQ57BQ POSITIVO        | Desktop     | [1a2fe7c9ef](https://linux-hardware.org/?probe=1a2fe7c9ef) | Dec 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [bd8707be32](https://linux-hardware.org/?probe=bd8707be32) | Dec 13, 2023 |
| Dell          | Latitude E5470              | Notebook    | [cc7982deb0](https://linux-hardware.org/?probe=cc7982deb0) | Dec 13, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [41dbdcf594](https://linux-hardware.org/?probe=41dbdcf594) | Dec 13, 2023 |
| Dell          | Latitude 3420               | Notebook    | [b344d71410](https://linux-hardware.org/?probe=b344d71410) | Dec 13, 2023 |
| Positivo      | POS-PIH81DL                 | Desktop     | [55cf834e17](https://linux-hardware.org/?probe=55cf834e17) | Dec 13, 2023 |
| Dell          | System XPS L502X            | Notebook    | [75c612f90d](https://linux-hardware.org/?probe=75c612f90d) | Dec 13, 2023 |
| Dell          | G3 3590                     | Notebook    | [e764bfc760](https://linux-hardware.org/?probe=e764bfc760) | Dec 13, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [295f9127b0](https://linux-hardware.org/?probe=295f9127b0) | Dec 12, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [74dc572dd7](https://linux-hardware.org/?probe=74dc572dd7) | Dec 12, 2023 |
| MACHINIST     | X79 Z9-D7 PRO V1.0          | Desktop     | [aaeef17ed2](https://linux-hardware.org/?probe=aaeef17ed2) | Dec 12, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [74c0490d28](https://linux-hardware.org/?probe=74c0490d28) | Dec 12, 2023 |
| Lenovo        | Unknown                     | Desktop     | [d49ddc416f](https://linux-hardware.org/?probe=d49ddc416f) | Dec 12, 2023 |
| Intel         | JSL MRD                     | Desktop     | [c811c8be03](https://linux-hardware.org/?probe=c811c8be03) | Dec 12, 2023 |
| Positivo      | H14BT58                     | Notebook    | [74530bb40a](https://linux-hardware.org/?probe=74530bb40a) | Dec 12, 2023 |
| Positivo      | CHT12CP                     | Notebook    | [d9d4327551](https://linux-hardware.org/?probe=d9d4327551) | Dec 12, 2023 |
| Acer          | Predator G3-572             | Notebook    | [7de00d4eab](https://linux-hardware.org/?probe=7de00d4eab) | Dec 12, 2023 |
| Acer          | Aspire A315-510P            | Notebook    | [e2bdedca29](https://linux-hardware.org/?probe=e2bdedca29) | Dec 12, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [e72a787933](https://linux-hardware.org/?probe=e72a787933) | Dec 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [843d02bea4](https://linux-hardware.org/?probe=843d02bea4) | Dec 11, 2023 |
| Positivo      | Q464C                       | Notebook    | [47071c986c](https://linux-hardware.org/?probe=47071c986c) | Dec 11, 2023 |
| Samsung       | Q470C/500P4C                | Notebook    | [f904c4ea67](https://linux-hardware.org/?probe=f904c4ea67) | Dec 11, 2023 |
| Dell          | 07VWPG A01                  | Desktop     | [a9ad39cd38](https://linux-hardware.org/?probe=a9ad39cd38) | Dec 11, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [132b7b57ba](https://linux-hardware.org/?probe=132b7b57ba) | Dec 11, 2023 |
| Unknown       | X99H                        | Desktop     | [799324c839](https://linux-hardware.org/?probe=799324c839) | Dec 11, 2023 |
| Dell          | Inspiron 3442               | Notebook    | [deced1a058](https://linux-hardware.org/?probe=deced1a058) | Dec 11, 2023 |
| Gigabyte      | GA-78LMT-S2P                | Desktop     | [3818e85705](https://linux-hardware.org/?probe=3818e85705) | Dec 11, 2023 |
| Intel         | H61                         | Desktop     | [611b51b6c1](https://linux-hardware.org/?probe=611b51b6c1) | Dec 11, 2023 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [4b2be67e0f](https://linux-hardware.org/?probe=4b2be67e0f) | Dec 11, 2023 |
| Dell          | System XPS L502X            | Notebook    | [a612ae1881](https://linux-hardware.org/?probe=a612ae1881) | Dec 11, 2023 |
| Intel         | HM570                       | Desktop     | [a0f2eecda0](https://linux-hardware.org/?probe=a0f2eecda0) | Dec 11, 2023 |
| PCWare        | IPMH61R1                    | Desktop     | [0d3a1ef029](https://linux-hardware.org/?probe=0d3a1ef029) | Dec 11, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [66edf53f93](https://linux-hardware.org/?probe=66edf53f93) | Dec 10, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [60ea2483e2](https://linux-hardware.org/?probe=60ea2483e2) | Dec 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [4af70588d9](https://linux-hardware.org/?probe=4af70588d9) | Dec 10, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [bedb502b74](https://linux-hardware.org/?probe=bedb502b74) | Dec 10, 2023 |
| Pegatron      | IPMH61P1                    | Desktop     | [0d0474a798](https://linux-hardware.org/?probe=0d0474a798) | Dec 10, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [1adc377142](https://linux-hardware.org/?probe=1adc377142) | Dec 10, 2023 |
| Daten Tecn... | DA75PRO                     | Desktop     | [a4e18252cc](https://linux-hardware.org/?probe=a4e18252cc) | Dec 10, 2023 |
| MSI           | Modern 15 B7M               | Notebook    | [cc6c41e7fd](https://linux-hardware.org/?probe=cc6c41e7fd) | Dec 10, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e7872542e1](https://linux-hardware.org/?probe=e7872542e1) | Dec 10, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [e04ad23cd3](https://linux-hardware.org/?probe=e04ad23cd3) | Dec 10, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [425eac625e](https://linux-hardware.org/?probe=425eac625e) | Dec 10, 2023 |
| PCWare        | IPMH310G PRO                | Desktop     | [2abdb88ca3](https://linux-hardware.org/?probe=2abdb88ca3) | Dec 09, 2023 |
| ASUSTek       | A88XM-A                     | Desktop     | [2b60976ef6](https://linux-hardware.org/?probe=2b60976ef6) | Dec 09, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [b5f0453a4b](https://linux-hardware.org/?probe=b5f0453a4b) | Dec 09, 2023 |
| Gigabyte      | B650 GAMING X AX            | Desktop     | [b5f3fbe4c5](https://linux-hardware.org/?probe=b5f3fbe4c5) | Dec 09, 2023 |
| Dell          | Vostro 3550                 | Notebook    | [f1a1a0841c](https://linux-hardware.org/?probe=f1a1a0841c) | Dec 08, 2023 |
| Dell          | Inspiron 15 3520            | Notebook    | [6452783d8a](https://linux-hardware.org/?probe=6452783d8a) | Dec 08, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [9f878d8d30](https://linux-hardware.org/?probe=9f878d8d30) | Dec 08, 2023 |
| Acer          | Aspire A315-41              | Notebook    | [778176acbe](https://linux-hardware.org/?probe=778176acbe) | Dec 08, 2023 |
| ANGXUN        | X99 V1.0                    | Desktop     | [88919a1403](https://linux-hardware.org/?probe=88919a1403) | Dec 08, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [2b349d78ce](https://linux-hardware.org/?probe=2b349d78ce) | Dec 07, 2023 |
| Biostar       | A520MH                      | Desktop     | [de9fc0f8f2](https://linux-hardware.org/?probe=de9fc0f8f2) | Dec 07, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [d96cb11edc](https://linux-hardware.org/?probe=d96cb11edc) | Dec 07, 2023 |
| Pegatron      | IPMH61P1                    | Desktop     | [264229998e](https://linux-hardware.org/?probe=264229998e) | Dec 07, 2023 |
| Dell          | 0NW73C A00                  | Desktop     | [4c87b0a972](https://linux-hardware.org/?probe=4c87b0a972) | Dec 07, 2023 |
| Intel         | JSL MRD                     | Desktop     | [fb3b75c8cc](https://linux-hardware.org/?probe=fb3b75c8cc) | Dec 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [88ed0c98a0](https://linux-hardware.org/?probe=88ed0c98a0) | Dec 07, 2023 |
| Samsung       | 550XDA                      | Notebook    | [6501dce45c](https://linux-hardware.org/?probe=6501dce45c) | Dec 07, 2023 |
| Positivo      | Q4128C-S                    | Notebook    | [018aab637c](https://linux-hardware.org/?probe=018aab637c) | Dec 07, 2023 |
| Positivo B... | VJFE59F11X-B1011H           | Notebook    | [2f497e2103](https://linux-hardware.org/?probe=2f497e2103) | Dec 06, 2023 |
| Intel         | Unknown                     | Desktop     | [1e70326ef4](https://linux-hardware.org/?probe=1e70326ef4) | Dec 06, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [1f2c85d176](https://linux-hardware.org/?probe=1f2c85d176) | Dec 06, 2023 |
| Intel         | H61                         | Desktop     | [fbc4dc7436](https://linux-hardware.org/?probe=fbc4dc7436) | Dec 06, 2023 |
| ALDO          | C2016-BSWI-D2               | Desktop     | [4dec414c2e](https://linux-hardware.org/?probe=4dec414c2e) | Dec 06, 2023 |
| Dell          | 0P42M6 A01                  | Desktop     | [2deb37f773](https://linux-hardware.org/?probe=2deb37f773) | Dec 06, 2023 |
| ASUSTek       | K45A                        | Notebook    | [a5e618b2f9](https://linux-hardware.org/?probe=a5e618b2f9) | Dec 06, 2023 |
| ASUSTek       | K45A                        | Notebook    | [96d1051ede](https://linux-hardware.org/?probe=96d1051ede) | Dec 06, 2023 |
| YiFang        | NXM1106CWP                  | Tablet      | [2a43b298f8](https://linux-hardware.org/?probe=2a43b298f8) | Dec 06, 2023 |
| Acer          | Nitro AN515-57              | Notebook    | [5b38f6200a](https://linux-hardware.org/?probe=5b38f6200a) | Dec 06, 2023 |
| Dell          | Inspiron 7472               | Notebook    | [ef77efb220](https://linux-hardware.org/?probe=ef77efb220) | Dec 06, 2023 |
| ASUSTek       | M4A79XTD EVO                | Desktop     | [e52613f035](https://linux-hardware.org/?probe=e52613f035) | Dec 06, 2023 |
| Dell          | Precision 7720              | Notebook    | [da0616987d](https://linux-hardware.org/?probe=da0616987d) | Dec 05, 2023 |
| Dell          | 00V62H A01                  | Desktop     | [3a19753377](https://linux-hardware.org/?probe=3a19753377) | Dec 05, 2023 |
| Samsung       | RV419/RV420                 | Notebook    | [5f29bdfad1](https://linux-hardware.org/?probe=5f29bdfad1) | Dec 05, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [4ae43e0af1](https://linux-hardware.org/?probe=4ae43e0af1) | Dec 05, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [2691ac3f7d](https://linux-hardware.org/?probe=2691ac3f7d) | Dec 05, 2023 |
| Dell          | G7 7588                     | Notebook    | [8564f8e395](https://linux-hardware.org/?probe=8564f8e395) | Dec 05, 2023 |
| Valve         | Jupiter                     | Notebook    | [4ffa224365](https://linux-hardware.org/?probe=4ffa224365) | Dec 05, 2023 |
| Acer          | Aspire AV15-51              | Notebook    | [758a277d68](https://linux-hardware.org/?probe=758a277d68) | Dec 04, 2023 |
| Samsung       | 730QED                      | Convertible | [e7b8057036](https://linux-hardware.org/?probe=e7b8057036) | Dec 04, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [03fe12170c](https://linux-hardware.org/?probe=03fe12170c) | Dec 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [549c56d2f8](https://linux-hardware.org/?probe=549c56d2f8) | Dec 04, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [9714fadd61](https://linux-hardware.org/?probe=9714fadd61) | Dec 04, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [56afeffd34](https://linux-hardware.org/?probe=56afeffd34) | Dec 04, 2023 |
| Samsung       | 550XDA                      | Notebook    | [b5bfe47576](https://linux-hardware.org/?probe=b5bfe47576) | Dec 04, 2023 |
| Intel         | B75                         | Desktop     | [4290424c1d](https://linux-hardware.org/?probe=4290424c1d) | Dec 04, 2023 |
| MSI           | Modern 15 B7M               | Notebook    | [f1757e8248](https://linux-hardware.org/?probe=f1757e8248) | Dec 04, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [675f997c0b](https://linux-hardware.org/?probe=675f997c0b) | Dec 03, 2023 |
| Gigabyte      | H81M-S2PH                   | Desktop     | [2cd108c526](https://linux-hardware.org/?probe=2cd108c526) | Dec 03, 2023 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [6fce5f3dec](https://linux-hardware.org/?probe=6fce5f3dec) | Dec 03, 2023 |
| Gigabyte      | 970A-DS3P FX                | Desktop     | [358a92be0d](https://linux-hardware.org/?probe=358a92be0d) | Dec 03, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [6c21c9ac7d](https://linux-hardware.org/?probe=6c21c9ac7d) | Dec 03, 2023 |
| Intel         | H61                         | Desktop     | [71c32c973c](https://linux-hardware.org/?probe=71c32c973c) | Dec 03, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [3222457362](https://linux-hardware.org/?probe=3222457362) | Dec 03, 2023 |
| Lenovo        | ThinkPad T480 20L6S9UY00    | Notebook    | [318a41e343](https://linux-hardware.org/?probe=318a41e343) | Dec 03, 2023 |
| Gigabyte      | B450M AORUS ELITE           | Desktop     | [369e921b6f](https://linux-hardware.org/?probe=369e921b6f) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [a7c5eb788c](https://linux-hardware.org/?probe=a7c5eb788c) | Dec 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [5aeec2e399](https://linux-hardware.org/?probe=5aeec2e399) | Dec 03, 2023 |
| Positivo      | POS-SIGL40BX POSITIVO       | Desktop     | [d6bdfaf7b5](https://linux-hardware.org/?probe=d6bdfaf7b5) | Dec 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X571... | Notebook    | [da6b435afa](https://linux-hardware.org/?probe=da6b435afa) | Dec 02, 2023 |
| Gigabyte      | Z490M GAMING X              | Desktop     | [39640ce07b](https://linux-hardware.org/?probe=39640ce07b) | Dec 02, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2492e6ae2e](https://linux-hardware.org/?probe=2492e6ae2e) | Dec 02, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [c4839c409c](https://linux-hardware.org/?probe=c4839c409c) | Dec 02, 2023 |
| Acer          | Aspire V5-472               | Notebook    | [0dc4701502](https://linux-hardware.org/?probe=0dc4701502) | Dec 02, 2023 |
| Dell          | 02YRK5 A03                  | Desktop     | [ae544eff63](https://linux-hardware.org/?probe=ae544eff63) | Dec 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [ae8ecce4bd](https://linux-hardware.org/?probe=ae8ecce4bd) | Dec 02, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [0b017377f1](https://linux-hardware.org/?probe=0b017377f1) | Dec 02, 2023 |
| Dell          | Latitude 3540               | Notebook    | [64067574ad](https://linux-hardware.org/?probe=64067574ad) | Dec 02, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [6d97271c61](https://linux-hardware.org/?probe=6d97271c61) | Dec 02, 2023 |
| LG Electro... | 24V360 FAB2                 | All in one  | [d364581a07](https://linux-hardware.org/?probe=d364581a07) | Dec 02, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [0cff3cecd5](https://linux-hardware.org/?probe=0cff3cecd5) | Dec 02, 2023 |
| Dell          | G15 5510                    | Notebook    | [bdfca2648a](https://linux-hardware.org/?probe=bdfca2648a) | Dec 02, 2023 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [2fcc002511](https://linux-hardware.org/?probe=2fcc002511) | Dec 02, 2023 |
| Dell          | Vostro 3525                 | Notebook    | [6d84ce1284](https://linux-hardware.org/?probe=6d84ce1284) | Dec 01, 2023 |
| ASUSTek       | M4A88TD-M EVO               | Desktop     | [7f6b5fd810](https://linux-hardware.org/?probe=7f6b5fd810) | Dec 01, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [520e1bdfa8](https://linux-hardware.org/?probe=520e1bdfa8) | Dec 01, 2023 |
| Acer          | Aspire A515-45              | Notebook    | [9875097d6a](https://linux-hardware.org/?probe=9875097d6a) | Dec 01, 2023 |
| Lenovo        | IdeaPad 3 15IML05 82BS      | Notebook    | [32a0e568cc](https://linux-hardware.org/?probe=32a0e568cc) | Dec 01, 2023 |
| Intel         | B75                         | Desktop     | [488e28204b](https://linux-hardware.org/?probe=488e28204b) | Dec 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | Notebook    | [dcbc9946d8](https://linux-hardware.org/?probe=dcbc9946d8) | Dec 01, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20YD0... | Notebook    | [95221dfaaf](https://linux-hardware.org/?probe=95221dfaaf) | Dec 01, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [65480134bd](https://linux-hardware.org/?probe=65480134bd) | Dec 01, 2023 |
| HP            | Presario CQ43               | Notebook    | [5edf6adf85](https://linux-hardware.org/?probe=5edf6adf85) | Dec 01, 2023 |
| Dell          | Latitude E5410              | Notebook    | [074e7de8d8](https://linux-hardware.org/?probe=074e7de8d8) | Dec 01, 2023 |
| Multilaser    | PC31X                       | Notebook    | [1f63edb2f9](https://linux-hardware.org/?probe=1f63edb2f9) | Dec 01, 2023 |
| Intel         | X99H                        | Desktop     | [147f088343](https://linux-hardware.org/?probe=147f088343) | Dec 01, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [14b776bc4a](https://linux-hardware.org/?probe=14b776bc4a) | Dec 01, 2023 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [aa1896b627](https://linux-hardware.org/?probe=aa1896b627) | Nov 30, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [162854d649](https://linux-hardware.org/?probe=162854d649) | Nov 30, 2023 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [a17de72370](https://linux-hardware.org/?probe=a17de72370) | Nov 30, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [ad8164f124](https://linux-hardware.org/?probe=ad8164f124) | Nov 30, 2023 |
| Pegatron      | IPMIP-GS                    | Desktop     | [ebe5fd5255](https://linux-hardware.org/?probe=ebe5fd5255) | Nov 30, 2023 |
| Pegatron      | IPMIP-GS                    | Desktop     | [7b6f94666e](https://linux-hardware.org/?probe=7b6f94666e) | Nov 30, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [bb1fc18586](https://linux-hardware.org/?probe=bb1fc18586) | Nov 30, 2023 |
| ASUSTek       | TUF H310M-PLUS GAMING/BR    | Desktop     | [cf7d8fdbf1](https://linux-hardware.org/?probe=cf7d8fdbf1) | Nov 30, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4bac6b7cd5](https://linux-hardware.org/?probe=4bac6b7cd5) | Nov 30, 2023 |
| Samsung       | 550XDA                      | Notebook    | [5778304f73](https://linux-hardware.org/?probe=5778304f73) | Nov 30, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [ede8970ea9](https://linux-hardware.org/?probe=ede8970ea9) | Nov 30, 2023 |
| Dell          | G15 5511                    | Notebook    | [f77d3ad016](https://linux-hardware.org/?probe=f77d3ad016) | Nov 30, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [a803eec9f3](https://linux-hardware.org/?probe=a803eec9f3) | Nov 30, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [bd6506d274](https://linux-hardware.org/?probe=bd6506d274) | Nov 30, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [43e0c71549](https://linux-hardware.org/?probe=43e0c71549) | Nov 30, 2023 |
| ASUSTek       | C8HM70-I/HDMI               | Desktop     | [3284d74583](https://linux-hardware.org/?probe=3284d74583) | Nov 30, 2023 |
| AMI           | AMD                         | Notebook    | [9f3f9ba617](https://linux-hardware.org/?probe=9f3f9ba617) | Nov 29, 2023 |
| Avell High... | B.ON                        | Notebook    | [22a1430347](https://linux-hardware.org/?probe=22a1430347) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [d9b203868f](https://linux-hardware.org/?probe=d9b203868f) | Nov 29, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [a05b28f5b1](https://linux-hardware.org/?probe=a05b28f5b1) | Nov 29, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [7db0c2781b](https://linux-hardware.org/?probe=7db0c2781b) | Nov 29, 2023 |
| HP            | Pavilion dv6                | Notebook    | [ddce26dd72](https://linux-hardware.org/?probe=ddce26dd72) | Nov 29, 2023 |
| HP            | Pavilion 11 x360 PC         | Notebook    | [c6f9c552b6](https://linux-hardware.org/?probe=c6f9c552b6) | Nov 29, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [11d3e45e2d](https://linux-hardware.org/?probe=11d3e45e2d) | Nov 29, 2023 |
| ASUSTek       | ROG STRIX Z390-I GAMING     | Desktop     | [bd474c263c](https://linux-hardware.org/?probe=bd474c263c) | Nov 29, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [d2dcb1f2da](https://linux-hardware.org/?probe=d2dcb1f2da) | Nov 29, 2023 |
| Acer          | Aspire 4732Z                | Notebook    | [6a849535fb](https://linux-hardware.org/?probe=6a849535fb) | Nov 29, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [20007eacdb](https://linux-hardware.org/?probe=20007eacdb) | Nov 28, 2023 |
| Dell          | Inspiron 15 3515            | Notebook    | [e41d34ea1c](https://linux-hardware.org/?probe=e41d34ea1c) | Nov 28, 2023 |
| HP            | Presario CQ43               | Notebook    | [eaab50d59c](https://linux-hardware.org/?probe=eaab50d59c) | Nov 28, 2023 |
| Gigabyte      | G31-S3G                     | Desktop     | [895a8554b4](https://linux-hardware.org/?probe=895a8554b4) | Nov 28, 2023 |
| Dell          | Vostro 3583                 | Notebook    | [68c6f002f5](https://linux-hardware.org/?probe=68c6f002f5) | Nov 28, 2023 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [c4949cf710](https://linux-hardware.org/?probe=c4949cf710) | Nov 28, 2023 |
| Gigabyte      | X570S GAMING X              | Desktop     | [cc96f8e9bb](https://linux-hardware.org/?probe=cc96f8e9bb) | Nov 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [33388f794b](https://linux-hardware.org/?probe=33388f794b) | Nov 28, 2023 |
| Lenovo        | IdeaPad S145-15IIL 82DJ     | Notebook    | [1eda316922](https://linux-hardware.org/?probe=1eda316922) | Nov 28, 2023 |
| Dell          | 03NVJ6 A03                  | Desktop     | [2eae8e704b](https://linux-hardware.org/?probe=2eae8e704b) | Nov 28, 2023 |
| Unknown       | Unknown                     | Desktop     | [34cbcf6478](https://linux-hardware.org/?probe=34cbcf6478) | Nov 28, 2023 |
| ASRock        | H310CM-HG4                  | Desktop     | [bd3a1b9c9a](https://linux-hardware.org/?probe=bd3a1b9c9a) | Nov 28, 2023 |
| ASUSTek       | PRIME X670-P                | Desktop     | [1ace58fcdf](https://linux-hardware.org/?probe=1ace58fcdf) | Nov 28, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [330921f980](https://linux-hardware.org/?probe=330921f980) | Nov 27, 2023 |
| Google        | Eve                         | Convertible | [d6e1955713](https://linux-hardware.org/?probe=d6e1955713) | Nov 27, 2023 |
| MSI           | Z97-GD65 GAMING             | Desktop     | [86230be0a7](https://linux-hardware.org/?probe=86230be0a7) | Nov 27, 2023 |
| Lenovo        | ThinkPad E480 20KQ000EBR    | Notebook    | [3531e02313](https://linux-hardware.org/?probe=3531e02313) | Nov 27, 2023 |
| Daten Tecn... | DCM3A-4                     | Notebook    | [66b8d06d48](https://linux-hardware.org/?probe=66b8d06d48) | Nov 27, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [8a9e7f2ec1](https://linux-hardware.org/?probe=8a9e7f2ec1) | Nov 27, 2023 |
| Pegatron      | IPM41-D3                    | Desktop     | [0ce4abd06b](https://linux-hardware.org/?probe=0ce4abd06b) | Nov 27, 2023 |
| Positivo      | POS-EIH61CE SIM             | Desktop     | [85a576e6fc](https://linux-hardware.org/?probe=85a576e6fc) | Nov 27, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [1138c4c71b](https://linux-hardware.org/?probe=1138c4c71b) | Nov 27, 2023 |
| Dell          | 02YRK5 A03                  | Desktop     | [3b55d8f733](https://linux-hardware.org/?probe=3b55d8f733) | Nov 27, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [df3eed7cc0](https://linux-hardware.org/?probe=df3eed7cc0) | Nov 27, 2023 |
| Dell          | Vostro 1510                 | Notebook    | [8cb1e628c2](https://linux-hardware.org/?probe=8cb1e628c2) | Nov 27, 2023 |
| Lenovo        | ThinkPad T410 2522F25       | Notebook    | [d6988c10b5](https://linux-hardware.org/?probe=d6988c10b5) | Nov 27, 2023 |
| Lenovo        | ThinkPad T410 2522F25       | Notebook    | [aadbbad61f](https://linux-hardware.org/?probe=aadbbad61f) | Nov 27, 2023 |
| Intel         | H61                         | Desktop     | [5146767aa6](https://linux-hardware.org/?probe=5146767aa6) | Nov 26, 2023 |
| Positivo      | POS-EIH61CQ POSITIVO        | Desktop     | [bed32da0ed](https://linux-hardware.org/?probe=bed32da0ed) | Nov 26, 2023 |
| Intel         | B75                         | Desktop     | [fab278b6c3](https://linux-hardware.org/?probe=fab278b6c3) | Nov 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [a208b7bd3a](https://linux-hardware.org/?probe=a208b7bd3a) | Nov 26, 2023 |
| Philco        | 14H                         | Notebook    | [f4256fe390](https://linux-hardware.org/?probe=f4256fe390) | Nov 26, 2023 |
| Acer          | Swift SF514-56T             | Notebook    | [687fc34fd5](https://linux-hardware.org/?probe=687fc34fd5) | Nov 26, 2023 |
| Lenovo        | Unknown                     | Notebook    | [504a4bd033](https://linux-hardware.org/?probe=504a4bd033) | Nov 26, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [47ec694370](https://linux-hardware.org/?probe=47ec694370) | Nov 26, 2023 |
| Dell          | 0NK5PH A00                  | Desktop     | [ed6b4827c0](https://linux-hardware.org/?probe=ed6b4827c0) | Nov 26, 2023 |
| HP            | Pavilion 14                 | Notebook    | [af5d0c670a](https://linux-hardware.org/?probe=af5d0c670a) | Nov 26, 2023 |
| Dell          | 0GYT9V A00                  | Desktop     | [a0fe7b3987](https://linux-hardware.org/?probe=a0fe7b3987) | Nov 26, 2023 |
| Dell          | 0NW73C A00                  | Desktop     | [eef7971d44](https://linux-hardware.org/?probe=eef7971d44) | Nov 26, 2023 |
| Dell          | 0NW73C A00                  | Desktop     | [9fd25914ff](https://linux-hardware.org/?probe=9fd25914ff) | Nov 26, 2023 |
| Intel         | H61 V124A                   | Desktop     | [eaa125b476](https://linux-hardware.org/?probe=eaa125b476) | Nov 26, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [8ce722dacd](https://linux-hardware.org/?probe=8ce722dacd) | Nov 26, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [b8c7347da7](https://linux-hardware.org/?probe=b8c7347da7) | Nov 26, 2023 |
| Gigabyte      | B560M DS3H                  | Desktop     | [7130842b5a](https://linux-hardware.org/?probe=7130842b5a) | Nov 26, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [568b4fa435](https://linux-hardware.org/?probe=568b4fa435) | Nov 26, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0f05f2568e](https://linux-hardware.org/?probe=0f05f2568e) | Nov 25, 2023 |
| ASRock        | H470M-ITX/ac                | Desktop     | [5b558c30c8](https://linux-hardware.org/?probe=5b558c30c8) | Nov 25, 2023 |
| Foxconn       | H61MXT1/F2/-S/-V            | Desktop     | [0529750c82](https://linux-hardware.org/?probe=0529750c82) | Nov 25, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [186ea5595b](https://linux-hardware.org/?probe=186ea5595b) | Nov 25, 2023 |
| Positivo      | C41TF                       | Notebook    | [09be1cbd3a](https://linux-hardware.org/?probe=09be1cbd3a) | Nov 25, 2023 |
| Gigabyte      | GA-78LMT-USB3 x.x           | Desktop     | [b9b8e57c7c](https://linux-hardware.org/?probe=b9b8e57c7c) | Nov 25, 2023 |
| Dell          | Latitude 7430               | Notebook    | [1074b5c005](https://linux-hardware.org/?probe=1074b5c005) | Nov 25, 2023 |
| ASRock        | G31M-S                      | Desktop     | [01866950a6](https://linux-hardware.org/?probe=01866950a6) | Nov 25, 2023 |
| Positivo      | POS-PIH55BX POSITIVO        | Desktop     | [5dd3b907da](https://linux-hardware.org/?probe=5dd3b907da) | Nov 25, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [0c42791b33](https://linux-hardware.org/?probe=0c42791b33) | Nov 25, 2023 |
| Dell          | Inspiron 5468               | Notebook    | [3422c91458](https://linux-hardware.org/?probe=3422c91458) | Nov 24, 2023 |
| Positivo      | S14CT01                     | Notebook    | [c1b3f4bc65](https://linux-hardware.org/?probe=c1b3f4bc65) | Nov 24, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [0f9d912f7f](https://linux-hardware.org/?probe=0f9d912f7f) | Nov 24, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [d69be34130](https://linux-hardware.org/?probe=d69be34130) | Nov 24, 2023 |
| A14CR         | Unknown                     | Notebook    | [c0924a368e](https://linux-hardware.org/?probe=c0924a368e) | Nov 24, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [606a157eb4](https://linux-hardware.org/?probe=606a157eb4) | Nov 24, 2023 |
| HP            | G62                         | Notebook    | [9d6424c4cc](https://linux-hardware.org/?probe=9d6424c4cc) | Nov 24, 2023 |
| Gigabyte      | G41MT-S2P                   | Desktop     | [00ef59a95d](https://linux-hardware.org/?probe=00ef59a95d) | Nov 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [199f9814a0](https://linux-hardware.org/?probe=199f9814a0) | Nov 24, 2023 |
| Samsung       | 960XFH                      | Notebook    | [2ad3d93589](https://linux-hardware.org/?probe=2ad3d93589) | Nov 24, 2023 |
| Compaq        | 420                         | Notebook    | [651aec3a5c](https://linux-hardware.org/?probe=651aec3a5c) | Nov 24, 2023 |
| Compaq        | 420                         | Notebook    | [df09fad001](https://linux-hardware.org/?probe=df09fad001) | Nov 23, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ecad990a24](https://linux-hardware.org/?probe=ecad990a24) | Nov 23, 2023 |
| Samsung       | 270E5J/2570EJ               | Notebook    | [d6ab9c6df5](https://linux-hardware.org/?probe=d6ab9c6df5) | Nov 23, 2023 |
| Avell High... | A70 MOB                     | Notebook    | [d936aa95ef](https://linux-hardware.org/?probe=d936aa95ef) | Nov 23, 2023 |
| MSI           | A68HM-E33 V2                | Desktop     | [e257380edc](https://linux-hardware.org/?probe=e257380edc) | Nov 23, 2023 |
| Itautec       | SM 3322 SM-3322 Padrao 0... | Desktop     | [2cf2808a7f](https://linux-hardware.org/?probe=2cf2808a7f) | Nov 23, 2023 |
| HP            | ProBook 4430s               | Notebook    | [847fb6fb22](https://linux-hardware.org/?probe=847fb6fb22) | Nov 23, 2023 |
| Gigabyte      | B550I AORUS PRO AX          | Notebook    | [07e6828b2e](https://linux-hardware.org/?probe=07e6828b2e) | Nov 23, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [676da26c54](https://linux-hardware.org/?probe=676da26c54) | Nov 23, 2023 |
| Colorful T... | iGame Z270 Ymir             | Desktop     | [62929668f5](https://linux-hardware.org/?probe=62929668f5) | Nov 23, 2023 |
| Gigabyte      | GA-78LMT-USB3 SEx           | Desktop     | [8414b3b3f1](https://linux-hardware.org/?probe=8414b3b3f1) | Nov 23, 2023 |
| HOUTER        | IPMIP-GS                    | Desktop     | [1daae127f8](https://linux-hardware.org/?probe=1daae127f8) | Nov 23, 2023 |
| HP            | ProBook 4430s               | Notebook    | [1b34dd379f](https://linux-hardware.org/?probe=1b34dd379f) | Nov 23, 2023 |
| HP            | 430                         | Notebook    | [a5ad87647a](https://linux-hardware.org/?probe=a5ad87647a) | Nov 23, 2023 |
| Acer          | Aspire ES1-531              | Notebook    | [01d429e284](https://linux-hardware.org/?probe=01d429e284) | Nov 22, 2023 |
| Lenovo        | IdeaPad 1 15AMN7 82X5       | Notebook    | [8d944b2cf7](https://linux-hardware.org/?probe=8d944b2cf7) | Nov 22, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [93a21a43d5](https://linux-hardware.org/?probe=93a21a43d5) | Nov 22, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [b8a36c00e8](https://linux-hardware.org/?probe=b8a36c00e8) | Nov 22, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [e95ef90dec](https://linux-hardware.org/?probe=e95ef90dec) | Nov 22, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [eb86dc0b36](https://linux-hardware.org/?probe=eb86dc0b36) | Nov 22, 2023 |
| Dell          | Latitude 7430               | Notebook    | [44557e3a83](https://linux-hardware.org/?probe=44557e3a83) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [0a82a8edc6](https://linux-hardware.org/?probe=0a82a8edc6) | Nov 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [f30de31399](https://linux-hardware.org/?probe=f30de31399) | Nov 22, 2023 |
| Samsung       | 300E5EV/300E4EV/270E5EV/... | Notebook    | [2d0d992e3e](https://linux-hardware.org/?probe=2d0d992e3e) | Nov 22, 2023 |
| Positivo      | S14CT01                     | Notebook    | [dab6f65392](https://linux-hardware.org/?probe=dab6f65392) | Nov 22, 2023 |
| Positivo      | S14CT01                     | Notebook    | [b92cdc7457](https://linux-hardware.org/?probe=b92cdc7457) | Nov 22, 2023 |
| Samsung       | 530XBB                      | Notebook    | [c31efedbdf](https://linux-hardware.org/?probe=c31efedbdf) | Nov 22, 2023 |
| Dell          | Inspiron N5010              | Notebook    | [688d81c63c](https://linux-hardware.org/?probe=688d81c63c) | Nov 22, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [2f025c011d](https://linux-hardware.org/?probe=2f025c011d) | Nov 22, 2023 |
| Samsung       | 960XFH                      | Notebook    | [c8ff018414](https://linux-hardware.org/?probe=c8ff018414) | Nov 22, 2023 |
| Samsung       | 960XFH                      | Notebook    | [a379f59fb3](https://linux-hardware.org/?probe=a379f59fb3) | Nov 22, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [713583bc52](https://linux-hardware.org/?probe=713583bc52) | Nov 22, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [d679a12a36](https://linux-hardware.org/?probe=d679a12a36) | Nov 21, 2023 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [0edf2befff](https://linux-hardware.org/?probe=0edf2befff) | Nov 21, 2023 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [cc2aa981d3](https://linux-hardware.org/?probe=cc2aa981d3) | Nov 21, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [8e8de2388b](https://linux-hardware.org/?probe=8e8de2388b) | Nov 21, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [0ed3e8195d](https://linux-hardware.org/?probe=0ed3e8195d) | Nov 21, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [618916ad03](https://linux-hardware.org/?probe=618916ad03) | Nov 21, 2023 |
| HP            | 430                         | Notebook    | [65a26f2a32](https://linux-hardware.org/?probe=65a26f2a32) | Nov 21, 2023 |
| Samsung       | 550XDA                      | Notebook    | [4c1328b562](https://linux-hardware.org/?probe=4c1328b562) | Nov 21, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [078c28606a](https://linux-hardware.org/?probe=078c28606a) | Nov 21, 2023 |
| Intel         | B75                         | Desktop     | [0620da2ddb](https://linux-hardware.org/?probe=0620da2ddb) | Nov 21, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [a166dbb3cf](https://linux-hardware.org/?probe=a166dbb3cf) | Nov 20, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [6e05364421](https://linux-hardware.org/?probe=6e05364421) | Nov 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [d6c8994c15](https://linux-hardware.org/?probe=d6c8994c15) | Nov 20, 2023 |
| Pegatron      | SM 3322                     | Desktop     | [aed1cc686d](https://linux-hardware.org/?probe=aed1cc686d) | Nov 20, 2023 |
| Pegatron      | SM 3322                     | Desktop     | [4f37480be5](https://linux-hardware.org/?probe=4f37480be5) | Nov 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [96d6ec7f1f](https://linux-hardware.org/?probe=96d6ec7f1f) | Nov 20, 2023 |
| ECS           | H61H2-M2                    | Desktop     | [29293282c2](https://linux-hardware.org/?probe=29293282c2) | Nov 20, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [66b4ff8f76](https://linux-hardware.org/?probe=66b4ff8f76) | Nov 20, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [c0a0353d6f](https://linux-hardware.org/?probe=c0a0353d6f) | Nov 20, 2023 |
| Dell          | G15 5530                    | Notebook    | [0d608c0d48](https://linux-hardware.org/?probe=0d608c0d48) | Nov 20, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [b93c6fb412](https://linux-hardware.org/?probe=b93c6fb412) | Nov 20, 2023 |
| Digibras      | NH4CU53                     | Notebook    | [25fff3f773](https://linux-hardware.org/?probe=25fff3f773) | Nov 20, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [a8e951e3b6](https://linux-hardware.org/?probe=a8e951e3b6) | Nov 20, 2023 |
| HP            | Presario C700               | Notebook    | [c8a9963f71](https://linux-hardware.org/?probe=c8a9963f71) | Nov 19, 2023 |
| Intel         | B75                         | Desktop     | [f184a18fb9](https://linux-hardware.org/?probe=f184a18fb9) | Nov 19, 2023 |
| Intel         | H61                         | Desktop     | [bdab1dc80a](https://linux-hardware.org/?probe=bdab1dc80a) | Nov 19, 2023 |
| Gigabyte      | H61M-S1                     | Desktop     | [4106ef0cba](https://linux-hardware.org/?probe=4106ef0cba) | Nov 19, 2023 |
| Intel         | H61                         | Desktop     | [4b5806ba4c](https://linux-hardware.org/?probe=4b5806ba4c) | Nov 19, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [ac68da4f7c](https://linux-hardware.org/?probe=ac68da4f7c) | Nov 19, 2023 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [5edc51a963](https://linux-hardware.org/?probe=5edc51a963) | Nov 19, 2023 |
| Acer          | Predator PH315-52           | Notebook    | [b53d35a567](https://linux-hardware.org/?probe=b53d35a567) | Nov 19, 2023 |
| Gigabyte      | A520M H                     | Desktop     | [abba035964](https://linux-hardware.org/?probe=abba035964) | Nov 19, 2023 |
| Dell          | Inspiron 5548               | Notebook    | [63fec114db](https://linux-hardware.org/?probe=63fec114db) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [e26c4bc5ff](https://linux-hardware.org/?probe=e26c4bc5ff) | Nov 19, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [97ebdb3c3a](https://linux-hardware.org/?probe=97ebdb3c3a) | Nov 19, 2023 |
| Dell          | Inspiron 15-5568            | Notebook    | [18712e5bfd](https://linux-hardware.org/?probe=18712e5bfd) | Nov 19, 2023 |
| Acer          | Aspire 5920                 | Notebook    | [ceafa361bc](https://linux-hardware.org/?probe=ceafa361bc) | Nov 19, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [07aecd2eb5](https://linux-hardware.org/?probe=07aecd2eb5) | Nov 19, 2023 |
| Lenovo        | ThinkPad T480 20L6S9UY00    | Notebook    | [21433a0601](https://linux-hardware.org/?probe=21433a0601) | Nov 19, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [a9b37fa8a9](https://linux-hardware.org/?probe=a9b37fa8a9) | Nov 19, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [0e1fa61401](https://linux-hardware.org/?probe=0e1fa61401) | Nov 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [9073144bc1](https://linux-hardware.org/?probe=9073144bc1) | Nov 19, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [5f9c8945b0](https://linux-hardware.org/?probe=5f9c8945b0) | Nov 18, 2023 |
| Intel         | H81                         | Desktop     | [1d1b5d11ec](https://linux-hardware.org/?probe=1d1b5d11ec) | Nov 18, 2023 |
| Dell          | Inspiron 5558               | Notebook    | [29cde3b62e](https://linux-hardware.org/?probe=29cde3b62e) | Nov 18, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [37139a6fd4](https://linux-hardware.org/?probe=37139a6fd4) | Nov 18, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [8ec5ebb443](https://linux-hardware.org/?probe=8ec5ebb443) | Nov 18, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [669208a0f6](https://linux-hardware.org/?probe=669208a0f6) | Nov 18, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [c8b5a88695](https://linux-hardware.org/?probe=c8b5a88695) | Nov 18, 2023 |
| Daten Tecn... | DCM4D-4 v4                  | Notebook    | [a8095f2a1a](https://linux-hardware.org/?probe=a8095f2a1a) | Nov 18, 2023 |
| Multilaser    | MLSH1H LINUX                | Notebook    | [01d7e1aa14](https://linux-hardware.org/?probe=01d7e1aa14) | Nov 18, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [a61196eaad](https://linux-hardware.org/?probe=a61196eaad) | Nov 18, 2023 |
| HP            | Compaq Presario CQ50        | Notebook    | [b8b635e62f](https://linux-hardware.org/?probe=b8b635e62f) | Nov 18, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [eeef8f244c](https://linux-hardware.org/?probe=eeef8f244c) | Nov 18, 2023 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [a6f504cf47](https://linux-hardware.org/?probe=a6f504cf47) | Nov 17, 2023 |
| Compaq        | Presario CQ-17              | Notebook    | [7b53a480e4](https://linux-hardware.org/?probe=7b53a480e4) | Nov 17, 2023 |
| Compal        | PBL1011                     | Notebook    | [d015fafb32](https://linux-hardware.org/?probe=d015fafb32) | Nov 17, 2023 |
| Dell          | Vostro 15 5510              | Notebook    | [21505599dd](https://linux-hardware.org/?probe=21505599dd) | Nov 17, 2023 |
| Dell          | Latitude 5420               | Notebook    | [cc85910964](https://linux-hardware.org/?probe=cc85910964) | Nov 17, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [44d575bc98](https://linux-hardware.org/?probe=44d575bc98) | Nov 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [57d850fe75](https://linux-hardware.org/?probe=57d850fe75) | Nov 17, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [97bc4b516e](https://linux-hardware.org/?probe=97bc4b516e) | Nov 17, 2023 |
| Dell          | Latitude 3540               | Notebook    | [85737e7d24](https://linux-hardware.org/?probe=85737e7d24) | Nov 17, 2023 |
| Huanan        | X99-8M-F V1.3               | Desktop     | [58b38ab609](https://linux-hardware.org/?probe=58b38ab609) | Nov 17, 2023 |
| Huanan        | X99-8M-F V1.3               | Desktop     | [db7291c1da](https://linux-hardware.org/?probe=db7291c1da) | Nov 17, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [18a6603dd9](https://linux-hardware.org/?probe=18a6603dd9) | Nov 17, 2023 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [8a23e4f586](https://linux-hardware.org/?probe=8a23e4f586) | Nov 16, 2023 |
| MACHINIST     | E5 MR9A PRO MAX V1.1        | Desktop     | [199a544882](https://linux-hardware.org/?probe=199a544882) | Nov 16, 2023 |
| Dell          | Vostro 3300                 | Notebook    | [90986d4cf6](https://linux-hardware.org/?probe=90986d4cf6) | Nov 16, 2023 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [a32c2cc638](https://linux-hardware.org/?probe=a32c2cc638) | Nov 16, 2023 |
| LG Electro... | 22V30R FAB1                 | All in one  | [868b385080](https://linux-hardware.org/?probe=868b385080) | Nov 16, 2023 |
| Intel         | DH55TC AAG26116-302         | Desktop     | [7fabbf9cb1](https://linux-hardware.org/?probe=7fabbf9cb1) | Nov 16, 2023 |
| Samsung       | 550XDA                      | Notebook    | [a823e2b0a5](https://linux-hardware.org/?probe=a823e2b0a5) | Nov 16, 2023 |
| Dell          | Inspiron 5567               | Notebook    | [ae0f1ed771](https://linux-hardware.org/?probe=ae0f1ed771) | Nov 16, 2023 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [4c58693314](https://linux-hardware.org/?probe=4c58693314) | Nov 16, 2023 |
| HP            | Pavilion g4                 | Notebook    | [37d7289eb6](https://linux-hardware.org/?probe=37d7289eb6) | Nov 16, 2023 |
| Intel         | X99-P4 V1.0                 | Desktop     | [b4caa65027](https://linux-hardware.org/?probe=b4caa65027) | Nov 16, 2023 |
| Samsung       | 300E5M/300E5L               | Notebook    | [0f53418be5](https://linux-hardware.org/?probe=0f53418be5) | Nov 16, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [f1ba9de4ad](https://linux-hardware.org/?probe=f1ba9de4ad) | Nov 16, 2023 |
| MSI           | Z97-G43 GAMING              | Desktop     | [86f598c692](https://linux-hardware.org/?probe=86f598c692) | Nov 16, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [0ab66fd189](https://linux-hardware.org/?probe=0ab66fd189) | Nov 16, 2023 |
| Dell          | 0478VN A00                  | Desktop     | [d2b8c293ea](https://linux-hardware.org/?probe=d2b8c293ea) | Nov 16, 2023 |
| Alienware     | m15 R6                      | Notebook    | [c341b25df2](https://linux-hardware.org/?probe=c341b25df2) | Nov 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1fa32b3cb7](https://linux-hardware.org/?probe=1fa32b3cb7) | Nov 15, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [68dbf5814b](https://linux-hardware.org/?probe=68dbf5814b) | Nov 15, 2023 |
| Huanan        | X99-F8 GAMING V2.0          | Desktop     | [160e8325ba](https://linux-hardware.org/?probe=160e8325ba) | Nov 15, 2023 |
| Positivo      | POS-EIH61CE POSITIVO        | Desktop     | [fd1391a823](https://linux-hardware.org/?probe=fd1391a823) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [d4c7bc8dc8](https://linux-hardware.org/?probe=d4c7bc8dc8) | Nov 15, 2023 |
| Dell          | Vostro 3583                 | Notebook    | [4ddc04a5ba](https://linux-hardware.org/?probe=4ddc04a5ba) | Nov 15, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [fb6bd38558](https://linux-hardware.org/?probe=fb6bd38558) | Nov 15, 2023 |
| MSI           | B150M MORTAR                | Desktop     | [78bfcd18a8](https://linux-hardware.org/?probe=78bfcd18a8) | Nov 15, 2023 |
| MACHINIST     | E5-RS9 V1.11                | Desktop     | [13df1b5b7e](https://linux-hardware.org/?probe=13df1b5b7e) | Nov 15, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [adaa2215c6](https://linux-hardware.org/?probe=adaa2215c6) | Nov 15, 2023 |
| ECS           | H61H2-M2                    | Desktop     | [df572cd989](https://linux-hardware.org/?probe=df572cd989) | Nov 15, 2023 |
| Acer          | Aspire E1-572               | Notebook    | [c7c8df77be](https://linux-hardware.org/?probe=c7c8df77be) | Nov 15, 2023 |
| Intel         | B75                         | Desktop     | [b05bcd24eb](https://linux-hardware.org/?probe=b05bcd24eb) | Nov 15, 2023 |
| ASUSTek       | P5GC-MX/CKD/SI              | Desktop     | [08053c4143](https://linux-hardware.org/?probe=08053c4143) | Nov 15, 2023 |
| Sony          | VGN-NS130AE                 | Notebook    | [7a70acb426](https://linux-hardware.org/?probe=7a70acb426) | Nov 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82MF       | Notebook    | [0fe7515de5](https://linux-hardware.org/?probe=0fe7515de5) | Nov 15, 2023 |
| Dell          | Vostro 3583                 | Notebook    | [6bf67ac977](https://linux-hardware.org/?probe=6bf67ac977) | Nov 15, 2023 |
| Dell          | Vostro 15 3510              | Notebook    | [9c0b7c2706](https://linux-hardware.org/?probe=9c0b7c2706) | Nov 15, 2023 |
| Dell          | Inspiron 1545               | Notebook    | [fd459af24b](https://linux-hardware.org/?probe=fd459af24b) | Nov 15, 2023 |
| Toshiba       | STI 010433                  | Desktop     | [c172f735d2](https://linux-hardware.org/?probe=c172f735d2) | Nov 15, 2023 |
| Lenovo        | ThinkPad E14 20RBS25S00     | Notebook    | [3be8e07c6c](https://linux-hardware.org/?probe=3be8e07c6c) | Nov 14, 2023 |
| Dell          | Inspiron 3583               | Notebook    | [d014ceb833](https://linux-hardware.org/?probe=d014ceb833) | Nov 14, 2023 |
| MSI           | PRO H610M-G DDR4            | Desktop     | [1d0338a823](https://linux-hardware.org/?probe=1d0338a823) | Nov 14, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [09ef1df759](https://linux-hardware.org/?probe=09ef1df759) | Nov 14, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [f2a6eea13e](https://linux-hardware.org/?probe=f2a6eea13e) | Nov 14, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [4e7f0bb4bc](https://linux-hardware.org/?probe=4e7f0bb4bc) | Nov 14, 2023 |
| Phoenix/Si... | M730SR                      | Notebook    | [59e9d07293](https://linux-hardware.org/?probe=59e9d07293) | Nov 14, 2023 |
| Acer          | Aspire A515-51G             | Notebook    | [50a49f6aa3](https://linux-hardware.org/?probe=50a49f6aa3) | Nov 14, 2023 |
| JHZD          | BQM5                        | Desktop     | [cab813ae6e](https://linux-hardware.org/?probe=cab813ae6e) | Nov 14, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [33064ccfdf](https://linux-hardware.org/?probe=33064ccfdf) | Nov 14, 2023 |
| Lenovo        | IdeaPad S145-15IKB 81XM     | Notebook    | [65712a4bc0](https://linux-hardware.org/?probe=65712a4bc0) | Nov 14, 2023 |
| HP            | Pavilion dv5                | Notebook    | [f08fc1d52e](https://linux-hardware.org/?probe=f08fc1d52e) | Nov 13, 2023 |
| HP            | 2215                        | Desktop     | [452b632947](https://linux-hardware.org/?probe=452b632947) | Nov 13, 2023 |
| Intel         | H61                         | Desktop     | [cbefae3544](https://linux-hardware.org/?probe=cbefae3544) | Nov 13, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [37423cedf9](https://linux-hardware.org/?probe=37423cedf9) | Nov 13, 2023 |
| Sony          | VPCYB35AB                   | Notebook    | [2bc35e6541](https://linux-hardware.org/?probe=2bc35e6541) | Nov 13, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [6a15b4fb46](https://linux-hardware.org/?probe=6a15b4fb46) | Nov 13, 2023 |
| Intel         | B75                         | Desktop     | [5ecbc90751](https://linux-hardware.org/?probe=5ecbc90751) | Nov 13, 2023 |
| MSI           | 880GMA-E35                  | Desktop     | [a03280c10b](https://linux-hardware.org/?probe=a03280c10b) | Nov 12, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [656ba48c77](https://linux-hardware.org/?probe=656ba48c77) | Nov 12, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [6fb9ac1dd2](https://linux-hardware.org/?probe=6fb9ac1dd2) | Nov 12, 2023 |
| Gigabyte      | H81M-S1                     | Desktop     | [cd607f9e87](https://linux-hardware.org/?probe=cd607f9e87) | Nov 12, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [f1f44353e2](https://linux-hardware.org/?probe=f1f44353e2) | Nov 12, 2023 |
| Dell          | Latitude 3420               | Notebook    | [5e829237c5](https://linux-hardware.org/?probe=5e829237c5) | Nov 12, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [cbde46d416](https://linux-hardware.org/?probe=cbde46d416) | Nov 12, 2023 |
| Toshiba       | IS 1413G                    | Notebook    | [9a070023f0](https://linux-hardware.org/?probe=9a070023f0) | Nov 12, 2023 |
| Dell          | 08YDFF A00                  | Desktop     | [4eee0e211a](https://linux-hardware.org/?probe=4eee0e211a) | Nov 12, 2023 |
| ASUSTek       | P5KPL-AM-CKD-VISUM-SI       | Desktop     | [fd1be084ac](https://linux-hardware.org/?probe=fd1be084ac) | Nov 12, 2023 |
| raspberryp... | Raspberry Pi 4 Model B R... | Soc         | [9511365ff2](https://linux-hardware.org/?probe=9511365ff2) | Nov 12, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [64b6fe3b3a](https://linux-hardware.org/?probe=64b6fe3b3a) | Nov 11, 2023 |
| Samsung       | 730QFG                      | Convertible | [85cddf4fa5](https://linux-hardware.org/?probe=85cddf4fa5) | Nov 11, 2023 |
| HP            | G42                         | Notebook    | [8a331f427d](https://linux-hardware.org/?probe=8a331f427d) | Nov 11, 2023 |
| HP            | Pavilion Sleekbook 14 PC    | Notebook    | [5168262bbe](https://linux-hardware.org/?probe=5168262bbe) | Nov 11, 2023 |
| Intel         | H61                         | Desktop     | [c65f2e03f6](https://linux-hardware.org/?probe=c65f2e03f6) | Nov 11, 2023 |
| Philco        | 14H                         | Notebook    | [01ddcfeb9e](https://linux-hardware.org/?probe=01ddcfeb9e) | Nov 11, 2023 |
| Acer          | Nitro AN515-51              | Notebook    | [bcbad28ab7](https://linux-hardware.org/?probe=bcbad28ab7) | Nov 11, 2023 |
| Toshiba       | STI 010433                  | Desktop     | [03007d4f6a](https://linux-hardware.org/?probe=03007d4f6a) | Nov 11, 2023 |
| Samsung       | 550XDA                      | Notebook    | [036d014b91](https://linux-hardware.org/?probe=036d014b91) | Nov 10, 2023 |
| Acer          | Aspire A315-54              | Notebook    | [a83ac39876](https://linux-hardware.org/?probe=a83ac39876) | Nov 10, 2023 |
| HP            | 339A                        | Desktop     | [a89c7d0d5f](https://linux-hardware.org/?probe=a89c7d0d5f) | Nov 10, 2023 |
| Samsung       | RF511/RF411/RF711           | Notebook    | [04eea37363](https://linux-hardware.org/?probe=04eea37363) | Nov 10, 2023 |
| HP            | ProBook 4430s               | Notebook    | [47b4ab5ae1](https://linux-hardware.org/?probe=47b4ab5ae1) | Nov 10, 2023 |
| HP            | ProBook 4430s               | Notebook    | [69a5aa0675](https://linux-hardware.org/?probe=69a5aa0675) | Nov 10, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [95ea718240](https://linux-hardware.org/?probe=95ea718240) | Nov 10, 2023 |
| ASUSTek       | G60JX                       | Notebook    | [0ac4f1dfc0](https://linux-hardware.org/?probe=0ac4f1dfc0) | Nov 10, 2023 |
| Lenovo        | ThinkPad E14 20RB001YBR     | Notebook    | [5c84f04d34](https://linux-hardware.org/?probe=5c84f04d34) | Nov 10, 2023 |
| Lenovo        | IdeaPad 300-15ISK 80RS      | Notebook    | [0cacf99f8a](https://linux-hardware.org/?probe=0cacf99f8a) | Nov 09, 2023 |
| Samsung       | 730QFG                      | Convertible | [f46cab3d9c](https://linux-hardware.org/?probe=f46cab3d9c) | Nov 09, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [1f65a38863](https://linux-hardware.org/?probe=1f65a38863) | Nov 09, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [431101ce2f](https://linux-hardware.org/?probe=431101ce2f) | Nov 09, 2023 |
| ASUSTek       | S400CA                      | Notebook    | [0e5628865a](https://linux-hardware.org/?probe=0e5628865a) | Nov 09, 2023 |
| Dell          | 0N820C                      | Desktop     | [fe88368da2](https://linux-hardware.org/?probe=fe88368da2) | Nov 09, 2023 |
| Dell          | 0C27VV A01                  | Desktop     | [cc977cc459](https://linux-hardware.org/?probe=cc977cc459) | Nov 09, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [54073a3305](https://linux-hardware.org/?probe=54073a3305) | Nov 09, 2023 |
| Intel         | H61                         | Desktop     | [138c553c5a](https://linux-hardware.org/?probe=138c553c5a) | Nov 09, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [f1ba64ccfc](https://linux-hardware.org/?probe=f1ba64ccfc) | Nov 09, 2023 |
| HP            | G42                         | Notebook    | [f440217af5](https://linux-hardware.org/?probe=f440217af5) | Nov 09, 2023 |
| Samsung       | 730QFG                      | Convertible | [c53539f90d](https://linux-hardware.org/?probe=c53539f90d) | Nov 09, 2023 |
| Dell          | Vostro 5402                 | Notebook    | [67a604ba54](https://linux-hardware.org/?probe=67a604ba54) | Nov 08, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [d788a3221f](https://linux-hardware.org/?probe=d788a3221f) | Nov 08, 2023 |
| Acer          | Nitro AN515-54              | Notebook    | [fbdaa89128](https://linux-hardware.org/?probe=fbdaa89128) | Nov 08, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [17d6ddf22a](https://linux-hardware.org/?probe=17d6ddf22a) | Nov 08, 2023 |
| Acer          | Nitro AN515-47              | Notebook    | [b5982ee614](https://linux-hardware.org/?probe=b5982ee614) | Nov 08, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [6970492955](https://linux-hardware.org/?probe=6970492955) | Nov 08, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [741dbb7024](https://linux-hardware.org/?probe=741dbb7024) | Nov 08, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [f77e4d524d](https://linux-hardware.org/?probe=f77e4d524d) | Nov 08, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [00b9675b99](https://linux-hardware.org/?probe=00b9675b99) | Nov 08, 2023 |
| Dell          | Latitude 3480               | Notebook    | [993ca1c423](https://linux-hardware.org/?probe=993ca1c423) | Nov 08, 2023 |
| Acer          | Nitro AN515-47              | Notebook    | [3cf76cfbda](https://linux-hardware.org/?probe=3cf76cfbda) | Nov 08, 2023 |
| Acer          | Nitro AN515-46              | Notebook    | [69541ca76a](https://linux-hardware.org/?probe=69541ca76a) | Nov 07, 2023 |
| ASUSTek       | G60JX                       | Notebook    | [af79a74a4e](https://linux-hardware.org/?probe=af79a74a4e) | Nov 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [b662e225f4](https://linux-hardware.org/?probe=b662e225f4) | Nov 07, 2023 |
| MACHINIST     | X99-RS9 V2.0                | Desktop     | [84527b43d1](https://linux-hardware.org/?probe=84527b43d1) | Nov 07, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [c88fd34c8f](https://linux-hardware.org/?probe=c88fd34c8f) | Nov 07, 2023 |
| Dell          | Latitude 3480               | Notebook    | [58e8983502](https://linux-hardware.org/?probe=58e8983502) | Nov 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [eda7dcde73](https://linux-hardware.org/?probe=eda7dcde73) | Nov 07, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [0cc84d3b82](https://linux-hardware.org/?probe=0cc84d3b82) | Nov 07, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [c7d84926af](https://linux-hardware.org/?probe=c7d84926af) | Nov 07, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [70cdbefd00](https://linux-hardware.org/?probe=70cdbefd00) | Nov 07, 2023 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [8ee0ec30d3](https://linux-hardware.org/?probe=8ee0ec30d3) | Nov 06, 2023 |
| HP            | EliteBook 850 G6            | Notebook    | [0d00c42688](https://linux-hardware.org/?probe=0d00c42688) | Nov 06, 2023 |
| HP            | ENVY 15                     | Notebook    | [5f301610ee](https://linux-hardware.org/?probe=5f301610ee) | Nov 06, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [5fafb134cf](https://linux-hardware.org/?probe=5fafb134cf) | Nov 06, 2023 |
| HP            | ENVY 15                     | Notebook    | [150ca6a1a0](https://linux-hardware.org/?probe=150ca6a1a0) | Nov 06, 2023 |
| Samsung       | 550P5C/550P7C               | Notebook    | [f87e3a97c4](https://linux-hardware.org/?probe=f87e3a97c4) | Nov 06, 2023 |
| Gigabyte      | B450M GAMING                | Desktop     | [7974075b64](https://linux-hardware.org/?probe=7974075b64) | Nov 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [bb021ca517](https://linux-hardware.org/?probe=bb021ca517) | Nov 06, 2023 |
| Acer          | Aspire A315-53              | Notebook    | [3daa9909b3](https://linux-hardware.org/?probe=3daa9909b3) | Nov 06, 2023 |
| Positivo      | C41TF                       | Notebook    | [4bb5f6150c](https://linux-hardware.org/?probe=4bb5f6150c) | Nov 06, 2023 |
| Notebook      | NJx0MU                      | Notebook    | [24a052bf0c](https://linux-hardware.org/?probe=24a052bf0c) | Nov 06, 2023 |
| ASRock        | Z97 Killer                  | Desktop     | [f575f3121e](https://linux-hardware.org/?probe=f575f3121e) | Nov 06, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [99a6c38b5d](https://linux-hardware.org/?probe=99a6c38b5d) | Nov 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [f0b35f0acb](https://linux-hardware.org/?probe=f0b35f0acb) | Nov 05, 2023 |
| Lenovo        | IdeaPad S145-15IWL 81S9     | Notebook    | [7060a82ed0](https://linux-hardware.org/?probe=7060a82ed0) | Nov 05, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [c520e5a3b2](https://linux-hardware.org/?probe=c520e5a3b2) | Nov 05, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [d6cd277a79](https://linux-hardware.org/?probe=d6cd277a79) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [486d28dfeb](https://linux-hardware.org/?probe=486d28dfeb) | Nov 05, 2023 |
| ASUSTek       | PRIME B450M-GAMING/BR       | Desktop     | [f45893cbf7](https://linux-hardware.org/?probe=f45893cbf7) | Nov 05, 2023 |
| Digibras      | NH4CU53                     | Notebook    | [2c274cbad8](https://linux-hardware.org/?probe=2c274cbad8) | Nov 05, 2023 |
| Toshiba       | IS 1412                     | Notebook    | [d423a5c34a](https://linux-hardware.org/?probe=d423a5c34a) | Nov 04, 2023 |
| ASUSTek       | M5A78L-M LX/BR              | Desktop     | [459eb3cd2a](https://linux-hardware.org/?probe=459eb3cd2a) | Nov 04, 2023 |
| Toshiba       | STI 001359                  | Desktop     | [ebf464dbb3](https://linux-hardware.org/?probe=ebf464dbb3) | Nov 04, 2023 |
| Dell          | Latitude E6430              | Notebook    | [6a724d5aa8](https://linux-hardware.org/?probe=6a724d5aa8) | Nov 04, 2023 |
| ASUSTek       | UX31A                       | Notebook    | [013a7815c3](https://linux-hardware.org/?probe=013a7815c3) | Nov 04, 2023 |
| ASUSTek       | PRIME X470-PRO              | Desktop     | [c1523fb6a1](https://linux-hardware.org/?probe=c1523fb6a1) | Nov 04, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [80d949b057](https://linux-hardware.org/?probe=80d949b057) | Nov 04, 2023 |
| Google        | Bluebird                    | Notebook    | [55dbc11653](https://linux-hardware.org/?probe=55dbc11653) | Nov 04, 2023 |
| MSI           | MS-1759                     | Notebook    | [2dd46c2a71](https://linux-hardware.org/?probe=2dd46c2a71) | Nov 04, 2023 |
| Google        | Bluebird                    | Notebook    | [9e12130a28](https://linux-hardware.org/?probe=9e12130a28) | Nov 04, 2023 |
| HP            | 246 G6 Notebook PC          | Notebook    | [cd997e5a97](https://linux-hardware.org/?probe=cd997e5a97) | Nov 03, 2023 |
| Dell          | Inspiron N4010              | Notebook    | [f8aed4abab](https://linux-hardware.org/?probe=f8aed4abab) | Nov 03, 2023 |
| Dell          | Latitude 3420               | Notebook    | [9211e0f588](https://linux-hardware.org/?probe=9211e0f588) | Nov 03, 2023 |
| Multilaser    | PC13X                       | Notebook    | [1c6a314055](https://linux-hardware.org/?probe=1c6a314055) | Nov 03, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [baf30122ca](https://linux-hardware.org/?probe=baf30122ca) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | Desktop     | [2aa4f1a7f7](https://linux-hardware.org/?probe=2aa4f1a7f7) | Nov 03, 2023 |
| Acer          | Aspire 5750                 | Notebook    | [429b14ee32](https://linux-hardware.org/?probe=429b14ee32) | Nov 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a08b1cfa29](https://linux-hardware.org/?probe=a08b1cfa29) | Nov 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TB0... | Notebook    | [6987861086](https://linux-hardware.org/?probe=6987861086) | Nov 03, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [5d06dbbe5f](https://linux-hardware.org/?probe=5d06dbbe5f) | Nov 03, 2023 |
| Dell          | Inspiron 5547               | Notebook    | [e14eb66450](https://linux-hardware.org/?probe=e14eb66450) | Nov 03, 2023 |
| Lenovo        | IdeaPad 330-15IGM 81FN      | Notebook    | [9552d5f729](https://linux-hardware.org/?probe=9552d5f729) | Nov 02, 2023 |
| Acer          | AO722                       | Notebook    | [3464dc7b3c](https://linux-hardware.org/?probe=3464dc7b3c) | Nov 02, 2023 |
| HP            | 0B54h D                     | Desktop     | [4ec7776a76](https://linux-hardware.org/?probe=4ec7776a76) | Nov 02, 2023 |
| Dell          | Latitude 3440               | Notebook    | [b50ed47992](https://linux-hardware.org/?probe=b50ed47992) | Nov 02, 2023 |
| ASRock        | H81M-HG4 R4.0               | Desktop     | [0f5f162498](https://linux-hardware.org/?probe=0f5f162498) | Nov 02, 2023 |
| Dell          | Latitude 3440               | Notebook    | [9426910684](https://linux-hardware.org/?probe=9426910684) | Nov 02, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Brazil/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 1551      | 10.08%  |
| Ubuntu 18.04       | 1042      | 6.77%   |
| Ubuntu 22.04       | 730       | 4.74%   |
| OpenMandriva 4.2   | 344       | 2.24%   |
| Pop!_OS 20.04      | 319       | 2.07%   |
| Linux Mint 20      | 315       | 2.05%   |
| OpenMandriva 4.3   | 304       | 1.98%   |
| Pop!_OS 22.04      | 300       | 1.95%   |
| Linux Mint 19.3    | 289       | 1.88%   |
| Zorin 16           | 244       | 1.59%   |
| Manjaro            | 240       | 1.56%   |
| Linux Mint 20.3    | 238       | 1.55%   |
| Linux Mint 19.1    | 235       | 1.53%   |
| Arch Rolling       | 225       | 1.46%   |
| Ubuntu 19.04       | 218       | 1.42%   |
| KDE neon 20.04     | 215       | 1.4%    |
| Linux Mint 20.1    | 213       | 1.38%   |
| Debian 11          | 208       | 1.35%   |
| Fedora 38          | 204       | 1.33%   |
| Arch               | 189       | 1.23%   |
| Linux Mint 20.2    | 186       | 1.21%   |
| Linux Mint 21.1    | 183       | 1.19%   |
| Ubuntu 19.10       | 173       | 1.12%   |
| Debian 10          | 155       | 1.01%   |
| Zorin 15           | 152       | 0.99%   |
| OpenMandriva 23.08 | 143       | 0.93%   |
| OpenMandriva 23.01 | 134       | 0.87%   |
| OpenMandriva 23.03 | 128       | 0.83%   |
| Pop!_OS 21.04      | 127       | 0.83%   |
| Pop!_OS 20.10      | 127       | 0.83%   |
| Fedora 37          | 124       | 0.81%   |
| Xubuntu 20.04      | 121       | 0.79%   |
| Linux Mint 21.2    | 121       | 0.79%   |
| Fedora 34          | 120       | 0.78%   |
| Fedora 36          | 119       | 0.77%   |
| Linux Mint 21      | 111       | 0.72%   |
| Fedora 32          | 111       | 0.72%   |
| Pop!_OS 21.10      | 110       | 0.71%   |
| Fedora 35          | 110       | 0.71%   |
| Fedora 33          | 105       | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 4131      | 28.28%  |
| Linux Mint    | 1951      | 13.36%  |
| OpenMandriva  | 1105      | 7.57%   |
| Endless       | 1088      | 7.45%   |
| Fedora        | 977       | 6.69%   |
| Pop!_OS       | 948       | 6.49%   |
| Debian        | 565       | 3.87%   |
| Manjaro       | 435       | 2.98%   |
| Zorin         | 424       | 2.9%    |
| Arch          | 401       | 2.75%   |
| KDE neon      | 294       | 2.01%   |
| Xubuntu       | 252       | 1.73%   |
| Kubuntu       | 238       | 1.63%   |
| openSUSE      | 166       | 1.14%   |
| Ubuntu MATE   | 144       | 0.99%   |
| ROSA          | 136       | 0.93%   |
| Lubuntu       | 118       | 0.81%   |
| Elementary    | 108       | 0.74%   |
| Ubuntu Unity  | 90        | 0.62%   |
| ArcoLinux     | 90        | 0.62%   |
| LMDE          | 84        | 0.58%   |
| Kali          | 77        | 0.53%   |
| BigLinux      | 70        | 0.48%   |
| Ubuntu Budgie | 48        | 0.33%   |
| Deepin        | 47        | 0.32%   |
| LinuxFX       | 40        | 0.27%   |
| Clear Linux   | 40        | 0.27%   |
| CentOS        | 35        | 0.24%   |
| SteamOS       | 31        | 0.21%   |
| EndeavourOS   | 30        | 0.21%   |
| BlackPanther  | 30        | 0.21%   |
| Nobara        | 26        | 0.18%   |
| Gentoo        | 24        | 0.16%   |
| Garuda Linux  | 20        | 0.14%   |
| Parrot        | 19        | 0.13%   |
| MX            | 17        | 0.12%   |
| Peppermint    | 16        | 0.11%   |
| Xero          | 15        | 0.1%    |
| Linux Lite    | 15        | 0.1%    |
| Solus         | 14        | 0.1%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.4.0-42-generic         | 710       | 4.27%   |
| 5.10.14-desktop-1omv4002 | 333       | 2%      |
| 5.8.0-14-generic         | 318       | 1.91%   |
| 5.16.7-desktop-1omv4003  | 283       | 1.7%    |
| 4.15.0-46-generic        | 156       | 0.94%   |
| 5.3.0-28-generic         | 146       | 0.88%   |
| 5.4.0-48-generic         | 138       | 0.83%   |
| 5.4.0-19-generic         | 138       | 0.83%   |
| 6.2.6-desktop-1omv2390   | 126       | 0.76%   |
| 6.1.1-desktop-1omv2290   | 124       | 0.75%   |
| 5.4.0-7634-generic       | 123       | 0.74%   |
| 5.15.0-56-generic        | 121       | 0.73%   |
| 6.4.11-desktop-1omv2390  | 114       | 0.69%   |
| 5.11.0-35-generic        | 113       | 0.68%   |
| 5.4.0-58-generic         | 111       | 0.67%   |
| 5.4.0-40-generic         | 111       | 0.67%   |
| 5.4.0-26-generic         | 106       | 0.64%   |
| 5.4.0-52-generic         | 101       | 0.61%   |
| 4.18.0-15-generic        | 97        | 0.58%   |
| 5.4.0-47-generic         | 96        | 0.58%   |
| 5.3.0-40-generic         | 89        | 0.54%   |
| 5.11.0-7620-generic      | 78        | 0.47%   |
| 5.0.0-32-generic         | 78        | 0.47%   |
| 5.3.0-46-generic         | 77        | 0.46%   |
| 5.15.0-47-generic        | 73        | 0.44%   |
| 5.0.0-37-generic         | 72        | 0.43%   |
| 4.15.0-20-generic        | 72        | 0.43%   |
| 6.2.6-76060206-generic   | 71        | 0.43%   |
| 5.4.0-70-generic         | 71        | 0.43%   |
| 5.15.0-46-generic        | 70        | 0.42%   |
| 5.15.0-52-generic        | 69        | 0.42%   |
| 5.4.0-91-generic         | 68        | 0.41%   |
| 5.4.0-72-generic         | 68        | 0.41%   |
| 5.4.0-80-generic         | 63        | 0.38%   |
| 5.3.0-23-generic         | 63        | 0.38%   |
| 5.4.0-29-generic         | 62        | 0.37%   |
| 5.15.0-43-generic        | 62        | 0.37%   |
| 4.18.0-16-generic        | 62        | 0.37%   |
| 5.4.0-65-generic         | 61        | 0.37%   |
| 5.4.0-37-generic         | 61        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 3072      | 19.47%  |
| 5.15.0  | 1163      | 7.37%   |
| 4.15.0  | 954       | 6.05%   |
| 5.8.0   | 903       | 5.72%   |
| 5.3.0   | 799       | 5.06%   |
| 5.11.0  | 724       | 4.59%   |
| 5.0.0   | 566       | 3.59%   |
| 5.13.0  | 473       | 3%      |
| 4.18.0  | 417       | 2.64%   |
| 5.19.0  | 375       | 2.38%   |
| 5.10.14 | 335       | 2.12%   |
| 6.2.0   | 305       | 1.93%   |
| 5.16.7  | 283       | 1.79%   |
| 5.10.0  | 273       | 1.73%   |
| 6.2.6   | 203       | 1.29%   |
| 4.19.0  | 184       | 1.17%   |
| 6.1.0   | 147       | 0.93%   |
| 6.1.1   | 134       | 0.85%   |
| 6.4.11  | 131       | 0.83%   |
| 6.5.0   | 110       | 0.7%    |
| 5.17.5  | 59        | 0.37%   |
| 4.4.0   | 49        | 0.31%   |
| 6.0.12  | 48        | 0.3%    |
| 6.6.2   | 47        | 0.3%    |
| 5.7.9   | 47        | 0.3%    |
| 5.14.0  | 45        | 0.29%   |
| 4.9.0   | 42        | 0.27%   |
| 6.4.8   | 41        | 0.26%   |
| 5.16.11 | 41        | 0.26%   |
| 6.5.6   | 40        | 0.25%   |
| 6.5.5   | 36        | 0.23%   |
| 6.4.6   | 36        | 0.23%   |
| 6.2.9   | 32        | 0.2%    |
| 5.15.5  | 31        | 0.2%    |
| 5.14.21 | 31        | 0.2%    |
| 5.7.0   | 30        | 0.19%   |
| 5.15.15 | 30        | 0.19%   |
| 5.16.13 | 29        | 0.18%   |
| 5.9.16  | 28        | 0.18%   |
| 5.6.19  | 27        | 0.17%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 3198      | 20.55%  |
| 5.15    | 1450      | 9.32%   |
| 5.8     | 1016      | 6.53%   |
| 4.15    | 954       | 6.13%   |
| 5.3     | 870       | 5.59%   |
| 5.11    | 822       | 5.28%   |
| 5.10    | 807       | 5.19%   |
| 6.2     | 676       | 4.34%   |
| 5.0     | 608       | 3.91%   |
| 5.13    | 566       | 3.64%   |
| 6.1     | 498       | 3.2%    |
| 5.19    | 477       | 3.07%   |
| 5.16    | 475       | 3.05%   |
| 4.18    | 450       | 2.89%   |
| 6.4     | 323       | 2.08%   |
| 6.5     | 289       | 1.86%   |
| 4.19    | 220       | 1.41%   |
| 6.0     | 200       | 1.29%   |
| 6.6     | 183       | 1.18%   |
| 5.7     | 172       | 1.11%   |
| 5.17    | 156       | 1%      |
| 5.14    | 153       | 0.98%   |
| 5.18    | 139       | 0.89%   |
| 5.6     | 128       | 0.82%   |
| 6.3     | 125       | 0.8%    |
| 5.12    | 113       | 0.73%   |
| 5.9     | 111       | 0.71%   |
| 4.9     | 110       | 0.71%   |
| 4.4     | 56        | 0.36%   |
| 5.5     | 50        | 0.32%   |
| 5.1     | 39        | 0.25%   |
| 5.2     | 29        | 0.19%   |
| 3.10    | 21        | 0.13%   |
| 6.7     | 14        | 0.09%   |
| 4.13    | 13        | 0.08%   |
| 4.1     | 12        | 0.08%   |
| 4.20    | 10        | 0.06%   |
| 4.10    | 9         | 0.06%   |
| 4.12    | 6         | 0.04%   |
| 4.14    | 5         | 0.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 13587     | 97.5%   |
| i686    | 307       | 2.2%    |
| aarch64 | 26        | 0.19%   |
| armv7l  | 15        | 0.11%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 6704      | 45.97%  |
| KDE5            | 2096      | 14.37%  |
| Unknown         | 1860      | 12.75%  |
| X-Cinnamon      | 1226      | 8.41%   |
| XFCE            | 995       | 6.82%   |
| MATE            | 400       | 2.74%   |
| KDE             | 315       | 2.16%   |
| Cinnamon        | 240       | 1.65%   |
| LXQt            | 141       | 0.97%   |
| Pantheon        | 97        | 0.67%   |
| Unity           | 92        | 0.63%   |
| Budgie          | 71        | 0.49%   |
| KDE4            | 66        | 0.45%   |
| Deepin          | 65        | 0.45%   |
| LXDE            | 57        | 0.39%   |
| i3              | 41        | 0.28%   |
| GNOME Flashback | 17        | 0.12%   |
| GNOME Classic   | 17        | 0.12%   |
| Endless:GNOME   | 15        | 0.1%    |
| sway            | 11        | 0.08%   |
| awesome         | 11        | 0.08%   |
| openbox         | 8         | 0.05%   |
| Hyprland        | 8         | 0.05%   |
| Enlightenment   | 7         | 0.05%   |
| bspwm           | 4         | 0.03%   |
| icewm           | 3         | 0.02%   |
| qtile           | 2         | 0.01%   |
| xmonad          | 1         | 0.01%   |
| WindowMaker     | 1         | 0.01%   |
| Trinity         | 1         | 0.01%   |
| Phosh:GNOME     | 1         | 0.01%   |
| Lubuntu         | 1         | 0.01%   |
| jwm             | 1         | 0.01%   |
| i3-with-shmlog  | 1         | 0.01%   |
| Hypr            | 1         | 0.01%   |
| GNUstep         | 1         | 0.01%   |
| GNOME:Phosh     | 1         | 0.01%   |
| GNOME-Classic   | 1         | 0.01%   |
| fluxbox         | 1         | 0.01%   |
| DDE             | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 11152     | 77.68%  |
| Wayland | 2178      | 15.17%  |
| Unknown | 925       | 6.44%   |
| Tty     | 100       | 0.7%    |
| Web     | 2         | 0.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8628      | 59.65%  |
| SDDM    | 1794      | 12.4%   |
| GDM     | 1349      | 9.33%   |
| GDM3    | 1210      | 8.37%   |
| LightDM | 849       | 5.87%   |
| TDM     | 538       | 3.72%   |
| KDM     | 66        | 0.46%   |
| XDM     | 12        | 0.08%   |
| SLiM    | 8         | 0.06%   |
| LXDM    | 4         | 0.03%   |
| SLIMSKI | 2         | 0.01%   |
| MDM     | 2         | 0.01%   |
| Ly      | 2         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang        | Computers | Percent |
|-------------|-----------|---------|
| pt_BR       | 9452      | 66.27%  |
| en_US       | 2674      | 18.75%  |
| Unknown     | 1709      | 11.98%  |
| C           | 221       | 1.55%   |
| en_GB       | 65        | 0.46%   |
| pt_PT       | 57        | 0.4%    |
| es_ES       | 21        | 0.15%   |
| en_CA       | 12        | 0.08%   |
| de_DE       | 7         | 0.05%   |
| fr_FR       | 6         | 0.04%   |
| POSIX       | 3         | 0.02%   |
| en_DK       | 3         | 0.02%   |
| C.UTF8      | 3         | 0.02%   |
| pt_BRutf8   | 2         | 0.01%   |
| ja_JP       | 2         | 0.01%   |
| it_IT       | 2         | 0.01%   |
| es_CL       | 2         | 0.01%   |
| en_AG       | 2         | 0.01%   |
| UTF-8       | 1         | 0.01%   |
| ru_RU       | 1         | 0.01%   |
| pt_BR~      | 1         | 0.01%   |
| pt_BR.UTF8  | 1         | 0.01%   |
| es_VE       | 1         | 0.01%   |
| es_PY       | 1         | 0.01%   |
| es_MX       | 1         | 0.01%   |
| es_AR       | 1         | 0.01%   |
| eo          | 1         | 0.01%   |
| en_ZA       | 1         | 0.01%   |
| en_US.UTF8  | 1         | 0.01%   |
| en_US.utf-8 | 1         | 0.01%   |
| en_US.UFT-8 | 1         | 0.01%   |
| en_IN       | 1         | 0.01%   |
| en_IE.UTF8  | 1         | 0.01%   |
| en-US       | 1         | 0.01%   |
| em_US       | 1         | 0.01%   |
| de_CH       | 1         | 0.01%   |
| ar_EG       | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 7998      | 55.98%  |
| EFI  | 6289      | 44.02%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 10603     | 73.84%  |
| Btrfs    | 1316      | 9.16%   |
| Overlay  | 1154      | 8.04%   |
| Unknown  | 707       | 4.92%   |
| Tmpfs    | 337       | 2.35%   |
| Xfs      | 119       | 0.83%   |
| Zfs      | 53        | 0.37%   |
| Ext3     | 23        | 0.16%   |
| Ext2     | 22        | 0.15%   |
| F2fs     | 19        | 0.13%   |
| Aufs     | 4         | 0.03%   |
| XXXXXXX  | 1         | 0.01%   |
| Reiserfs | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 8944      | 62.39%  |
| GPT     | 3792      | 26.45%  |
| MBR     | 1600      | 11.16%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 12477     | 88.02%  |
| Yes       | 1698      | 11.98%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 10525     | 74.2%   |
| Yes       | 3659      | 25.8%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Dell                   | 2255      | 16.19%  |
| ASUSTek Computer       | 1823      | 13.09%  |
| Acer                   | 1577      | 11.32%  |
| Lenovo                 | 1212      | 8.7%    |
| Gigabyte Technology    | 916       | 6.58%   |
| Positivo               | 774       | 5.56%   |
| Hewlett-Packard        | 739       | 5.31%   |
| Samsung Electronics    | 709       | 5.09%   |
| Intel                  | 554       | 3.98%   |
| ASRock                 | 450       | 3.23%   |
| MSI                    | 260       | 1.87%   |
| Unknown                | 255       | 1.83%   |
| Sony                   | 169       | 1.21%   |
| Apple                  | 158       | 1.13%   |
| LG Electronics         | 141       | 1.01%   |
| PCWare                 | 125       | 0.9%    |
| Itautec                | 125       | 0.9%    |
| Semp Toshiba           | 121       | 0.87%   |
| Biostar                | 114       | 0.82%   |
| Avell High Performance | 92        | 0.66%   |
| Pegatron               | 81        | 0.58%   |
| Digibras               | 78        | 0.56%   |
| ECS                    | 70        | 0.5%    |
| Multilaser             | 62        | 0.45%   |
| OEM                    | 57        | 0.41%   |
| Compaq                 | 54        | 0.39%   |
| Philco                 | 53        | 0.38%   |
| Positivo Bahia - VAIO  | 45        | 0.32%   |
| Huanan                 | 45        | 0.32%   |
| Toshiba                | 36        | 0.26%   |
| Megaware               | 36        | 0.26%   |
| Foxconn                | 33        | 0.24%   |
| Daten Tecnologia       | 29        | 0.21%   |
| Notebook               | 28        | 0.2%    |
| MACHINIST              | 26        | 0.19%   |
| Clevo                  | 26        | 0.19%   |
| Login Informatica      | 23        | 0.17%   |
| Google                 | 23        | 0.17%   |
| Gateway                | 23        | 0.17%   |
| Compal                 | 21        | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                           | Computers | Percent |
|--------------------------------|-----------|---------|
| Unknown                        | 323       | 2.32%   |
| ASUS All Series                | 156       | 1.12%   |
| Acer Nitro AN515-54            | 139       | 1%      |
| Positivo Mobile                | 131       | 0.94%   |
| Intel H61                      | 112       | 0.8%    |
| Acer Nitro AN515-44            | 91        | 0.65%   |
| Samsung 340XAA/350XAA/550XAA   | 73        | 0.52%   |
| ASUS PRIME B450M-GAMING/BR     | 71        | 0.51%   |
| Lenovo IdeaPad S145-15API 81V7 | 70        | 0.5%    |
| Dell Inspiron 5566             | 70        | 0.5%    |
| Acer Aspire A315-53            | 70        | 0.5%    |
| Dell Inspiron 15-3567          | 66        | 0.47%   |
| Dell Inspiron 3583             | 64        | 0.46%   |
| Lenovo IdeaPad 330-15IKB 81FE  | 62        | 0.45%   |
| ASRock A320M-HD                | 61        | 0.44%   |
| Lenovo IdeaPad S145-15IWL 81S9 | 59        | 0.42%   |
| Intel H55                      | 55        | 0.39%   |
| ASUS PRIME A320M-K/BR          | 55        | 0.39%   |
| Acer Aspire A515-51            | 54        | 0.39%   |
| Acer Aspire A315-34            | 54        | 0.39%   |
| Lenovo IdeaPad 320-15IKB 80YH  | 53        | 0.38%   |
| ASUS M5A78L-M LX/BR            | 53        | 0.38%   |
| Acer Nitro AN517-51            | 53        | 0.38%   |
| Semp Toshiba STI               | 52        | 0.37%   |
| Samsung 300E5M/300E5L          | 51        | 0.37%   |
| Samsung 550XDA                 | 49        | 0.35%   |
| Lenovo IdeaPad 3 15ALC6 82MF   | 48        | 0.34%   |
| Dell Inspiron 3442             | 47        | 0.34%   |
| Acer Nitro AN515-43            | 46        | 0.33%   |
| Positivo S14CT01               | 45        | 0.32%   |
| Intel B75                      | 44        | 0.32%   |
| Itautec Infoway                | 43        | 0.31%   |
| HP G42                         | 43        | 0.31%   |
| Gigabyte A320M-S2H             | 43        | 0.31%   |
| Gigabyte H61M-S1               | 41        | 0.29%   |
| Dell Inspiron N4050            | 41        | 0.29%   |
| Dell Inspiron 3421             | 40        | 0.29%   |
| Acer Nitro AN515-52            | 40        | 0.29%   |
| ASUS P8H61-M LX3 R2.0          | 38        | 0.27%   |
| HP Pavilion g4                 | 37        | 0.27%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Dell Inspiron      | 1255      | 9.01%   |
| Acer Aspire        | 1016      | 7.29%   |
| Lenovo IdeaPad     | 607       | 4.36%   |
| Acer Nitro         | 440       | 3.16%   |
| Unknown            | 323       | 2.32%   |
| Dell Vostro        | 282       | 2.02%   |
| ASUS PRIME         | 270       | 1.94%   |
| Lenovo ThinkPad    | 240       | 1.72%   |
| Dell Latitude      | 225       | 1.62%   |
| HP Pavilion        | 220       | 1.58%   |
| Dell OptiPlex      | 183       | 1.31%   |
| ASUS VivoBook      | 170       | 1.22%   |
| ASUS All           | 156       | 1.12%   |
| ASUS TUF           | 146       | 1.05%   |
| ASUS M5A78L-M      | 134       | 0.96%   |
| Positivo Mobile    | 131       | 0.94%   |
| Itautec Infoway    | 118       | 0.85%   |
| Intel H61          | 118       | 0.85%   |
| HP Compaq          | 116       | 0.83%   |
| ASUS P8H61-M       | 94        | 0.67%   |
| Lenovo ThinkCentre | 75        | 0.54%   |
| Samsung 340XAA     | 73        | 0.52%   |
| ASUS ROG           | 68        | 0.49%   |
| Dell XPS           | 66        | 0.47%   |
| ASRock A320M-HD    | 65        | 0.47%   |
| Dell G3            | 64        | 0.46%   |
| Semp Toshiba STI   | 61        | 0.44%   |
| Intel H55          | 55        | 0.39%   |
| HP ProBook         | 52        | 0.37%   |
| Samsung 300E5M     | 51        | 0.37%   |
| Samsung RV411      | 49        | 0.35%   |
| Samsung 550XDA     | 49        | 0.35%   |
| Intel B75          | 47        | 0.34%   |
| Positivo S14CT01   | 45        | 0.32%   |
| Gigabyte B450M     | 45        | 0.32%   |
| HP G42             | 43        | 0.31%   |
| Gigabyte A320M-S2H | 43        | 0.31%   |
| Acer Predator      | 43        | 0.31%   |
| HP EliteBook       | 42        | 0.3%    |
| Gigabyte H61M-S1   | 41        | 0.29%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2012    | 1414      | 10.15%  |
| 2019    | 1356      | 9.74%   |
| 2018    | 1286      | 9.23%   |
| 2011    | 1259      | 9.04%   |
| 2017    | 1118      | 8.03%   |
| 2013    | 1045      | 7.5%    |
| 2010    | 856       | 6.15%   |
| 2016    | 840       | 6.03%   |
| 2020    | 812       | 5.83%   |
| 2014    | 808       | 5.8%    |
| 2021    | 690       | 4.95%   |
| 2009    | 574       | 4.12%   |
| 2008    | 547       | 3.93%   |
| 2015    | 499       | 3.58%   |
| 2007    | 315       | 2.26%   |
| 2022    | 234       | 1.68%   |
| 2006    | 102       | 0.73%   |
| 2023    | 74        | 0.53%   |
| Unknown | 63        | 0.45%   |
| 2005    | 26        | 0.19%   |
| 2004    | 9         | 0.06%   |
| 2003    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 8215      | 58.98%  |
| Desktop        | 5313      | 38.15%  |
| All in one     | 116       | 0.83%   |
| Convertible    | 105       | 0.75%   |
| Mini pc        | 61        | 0.44%   |
| Server         | 49        | 0.35%   |
| System on chip | 36        | 0.26%   |
| Tablet         | 29        | 0.21%   |
| Phone          | 2         | 0.01%   |
| Other          | 1         | 0.01%   |
| Firewall       | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 12661     | 90.22%  |
| Enabled  | 1373      | 9.78%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 13901     | 99.81%  |
| Yes  | 27        | 0.19%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 3819      | 26.84%  |
| 3.01-4.0        | 3560      | 25.02%  |
| 8.01-16.0       | 2454      | 17.25%  |
| 16.01-24.0      | 2338      | 16.43%  |
| 1.01-2.0        | 874       | 6.14%   |
| 32.01-64.0      | 534       | 3.75%   |
| 2.01-3.0        | 294       | 2.07%   |
| 24.01-32.0      | 155       | 1.09%   |
| 64.01-256.0     | 123       | 0.86%   |
| 0.51-1.0        | 65        | 0.46%   |
| More than 256.0 | 7         | 0.05%   |
| 0.01-0.5        | 2         | 0.01%   |
| Unknown         | 2         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 5530      | 35.77%  |
| 2.01-3.0    | 4199      | 27.16%  |
| 3.01-4.0    | 2033      | 13.15%  |
| 4.01-8.0    | 2020      | 13.07%  |
| 0.51-1.0    | 1069      | 6.91%   |
| 8.01-16.0   | 405       | 2.62%   |
| 0.01-0.5    | 136       | 0.88%   |
| 16.01-24.0  | 47        | 0.3%    |
| 24.01-32.0  | 9         | 0.06%   |
| Unknown     | 6         | 0.04%   |
| 32.01-64.0  | 5         | 0.03%   |
| 64.01-256.0 | 2         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8804      | 61.44%  |
| 2       | 3942      | 27.51%  |
| 3       | 901       | 6.29%   |
| 4       | 345       | 2.41%   |
| 0       | 133       | 0.93%   |
| 5       | 106       | 0.74%   |
| 6       | 66        | 0.46%   |
| 7       | 12        | 0.08%   |
| 8       | 9         | 0.06%   |
| 9       | 6         | 0.04%   |
| 18      | 1         | 0.01%   |
| 15      | 1         | 0.01%   |
| 14      | 1         | 0.01%   |
| 10      | 1         | 0.01%   |
| Unknown | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 8953      | 63.73%  |
| Yes       | 5095      | 36.27%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 12682     | 90.9%   |
| No        | 1269      | 9.1%    |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 10198     | 72.61%  |
| No        | 3847      | 27.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7230      | 51.3%   |
| No        | 6864      | 48.7%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Brazil  | 13928     | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                  | Computers | Percent |
|-----------------------|-----------|---------|
| Sao Paulo             | 1763      | 12.06%  |
| Rio de Janeiro        | 862       | 5.9%    |
| Brasília             | 460       | 3.15%   |
| Curitiba              | 403       | 2.76%   |
| Belo Horizonte        | 391       | 2.68%   |
| Porto Alegre          | 323       | 2.21%   |
| Fortaleza             | 310       | 2.12%   |
| Campinas              | 223       | 1.53%   |
| Salvador              | 213       | 1.46%   |
| Recife                | 188       | 1.29%   |
| Goiânia              | 164       | 1.12%   |
| Santo André          | 158       | 1.08%   |
| Florianópolis        | 158       | 1.08%   |
| Manaus                | 127       | 0.87%   |
| Natal                 | 126       | 0.86%   |
| Osasco                | 124       | 0.85%   |
| Sao José dos Campos  | 115       | 0.79%   |
| Niterói              | 108       | 0.74%   |
| Guarulhos             | 108       | 0.74%   |
| Campo Grande          | 107       | 0.73%   |
| Belém                | 100       | 0.68%   |
| Maringá              | 94        | 0.64%   |
| Sao Luís             | 93        | 0.64%   |
| Sorocaba              | 91        | 0.62%   |
| Joao Pessoa           | 91        | 0.62%   |
| Joinville             | 90        | 0.62%   |
| Londrina              | 86        | 0.59%   |
| Teresina              | 81        | 0.55%   |
| Uberlândia           | 78        | 0.53%   |
| Aracaju               | 78        | 0.53%   |
| Ribeirao Preto        | 76        | 0.52%   |
| Juiz de Fora          | 74        | 0.51%   |
| Maceió               | 68        | 0.47%   |
| Serra                 | 64        | 0.44%   |
| Duque de Caxias       | 63        | 0.43%   |
| Sao Carlos            | 61        | 0.42%   |
| Sao Bernardo do Campo | 61        | 0.42%   |
| Sao Jose              | 60        | 0.41%   |
| Cuiabá               | 60        | 0.41%   |
| Vitória              | 59        | 0.4%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| WDC                            | 3813      | 4951   | 19.46%  |
| Seagate                        | 3599      | 5150   | 18.37%  |
| Kingston                       | 2032      | 2666   | 10.37%  |
| Samsung Electronics            | 1877      | 2624   | 9.58%   |
| Toshiba                        | 1076      | 1273   | 5.49%   |
| SanDisk                        | 1002      | 1355   | 5.11%   |
| Unknown                        | 592       | 821    | 3.02%   |
| A-DATA Technology              | 568       | 725    | 2.9%    |
| China                          | 525       | 637    | 2.68%   |
| Hitachi                        | 417       | 513    | 2.13%   |
| Crucial                        | 391       | 508    | 2%      |
| Intel                          | 330       | 411    | 1.68%   |
| ADATA Technology               | 257       | 301    | 1.31%   |
| Silicon Motion                 | 238       | 301    | 1.21%   |
| SK hynix                       | 179       | 249    | 0.91%   |
| KingSpec                       | 154       | 175    | 0.79%   |
| HGST                           | 154       | 183    | 0.79%   |
| LITEON                         | 140       | 169    | 0.71%   |
| Maxtor                         | 130       | 152    | 0.66%   |
| Lexar                          | 110       | 130    | 0.56%   |
| Realtek Semiconductor          | 105       | 138    | 0.54%   |
| JMicron Technology             | 88        | 98     | 0.45%   |
| Netac                          | 86        | 113    | 0.44%   |
| Phison                         | 71        | 93     | 0.36%   |
| Kingston Technology Company    | 69        | 86     | 0.35%   |
| Corsair                        | 67        | 79     | 0.34%   |
| SSSTC                          | 66        | 71     | 0.34%   |
| XPG                            | 62        | 77     | 0.32%   |
| XrayDisk                       | 61        | 84     | 0.31%   |
| Patriot                        | 61        | 82     | 0.31%   |
| Fujitsu                        | 61        | 74     | 0.31%   |
| Unknown                        | 61        | 70     | 0.31%   |
| PNY                            | 57        | 74     | 0.29%   |
| Apple                          | 57        | 77     | 0.29%   |
| Hewlett-Packard                | 52        | 63     | 0.27%   |
| Solid State Storage            | 51        | 64     | 0.26%   |
| MAXIO Technology (Hangzhou)    | 50        | 65     | 0.26%   |
| Solid State Storage Technology | 48        | 63     | 0.25%   |
| Micron Technology              | 45        | 49     | 0.23%   |
| KIOXIA                         | 43        | 52     | 0.22%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                                 | Computers | Percent |
|-------------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                       | 685       | 3.27%   |
| WDC WD10SPZX-21Z10T0 1TB                              | 505       | 2.41%   |
| Kingston SA400S37480G 480GB SSD                       | 372       | 1.78%   |
| Kingston SA400S37120G 120GB SSD                       | 340       | 1.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                    | 334       | 1.6%    |
| Seagate ST500LM012 HN-M500MBB 500GB                   | 326       | 1.56%   |
| Seagate ST500DM002-1BD142 500GB                       | 276       | 1.32%   |
| Seagate ST1000DM010-2EP102 1TB                        | 255       | 1.22%   |
| Toshiba MQ01ABD100 1TB                                | 166       | 0.79%   |
| Kingston SV300S37A120G 120GB SSD                      | 164       | 0.78%   |
| Unknown MMC Card  32GB                                | 161       | 0.77%   |
| SanDisk SSD PLUS 240GB                                | 158       | 0.75%   |
| WDC WD10SPZX-24Z10 1TB                                | 156       | 0.74%   |
| Samsung HD322HJ 320GB                                 | 140       | 0.67%   |
| Seagate Expansion 1TB                                 | 139       | 0.66%   |
| Seagate ST1000LM035-1RK172 1TB                        | 136       | 0.65%   |
| Crucial CT240BX500SSD1 240GB                          | 129       | 0.62%   |
| WDC WD10JPVX-22JC3T0 1TB                              | 123       | 0.59%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                      | 117       | 0.56%   |
| Samsung HD502HJ 500GB                                 | 115       | 0.55%   |
| Samsung HM321HI 320GB                                 | 113       | 0.54%   |
| Samsung HD161HJ 160GB                                 | 112       | 0.53%   |
| Seagate ST1000DM003-1ER162 1TB                        | 107       | 0.51%   |
| SanDisk SSD PLUS 120GB                                | 107       | 0.51%   |
| Seagate ST1000DM003-1CH162 1TB                        | 105       | 0.5%    |
| Samsung HD502HI 500GB                                 | 105       | 0.5%    |
| Intel NVMe SSD Drive 512GB                            | 103       | 0.49%   |
| Seagate ST9500325AS 500GB                             | 100       | 0.48%   |
| Toshiba MQ04ABF100 1TB                                | 99        | 0.47%   |
| A-DATA IM2S3338-128GD2 128GB SSD                      | 95        | 0.45%   |
| WDC WD10SPZX-75Z10T2 1TB                              | 93        | 0.44%   |
| Toshiba MQ01ABF050 500GB                              | 92        | 0.44%   |
| WDC WD5000AAKX-003CA0 500GB                           | 84        | 0.4%    |
| SanDisk SDSSDA240G 240GB                              | 84        | 0.4%    |
| Seagate ST3500418AS 500GB                             | 83        | 0.4%    |
| WDC WD10JPVX-75JC3T0 1TB                              | 79        | 0.38%   |
| SanDisk SSD PLUS 480GB                                | 78        | 0.37%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB | 76        | 0.36%   |
| Seagate ST3500312CS 500GB                             | 75        | 0.36%   |
| Seagate ST320LM001 HN-M320MBB 320GB                   | 75        | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 3581      | 5113   | 35.2%   |
| WDC                 | 3374      | 4257   | 33.17%  |
| Samsung Electronics | 1239      | 1639   | 12.18%  |
| Toshiba             | 1018      | 1201   | 10.01%  |
| Hitachi             | 417       | 513    | 4.1%    |
| HGST                | 154       | 183    | 1.51%   |
| Maxtor              | 120       | 140    | 1.18%   |
| JMicron Technology  | 73        | 83     | 0.72%   |
| Fujitsu             | 59        | 71     | 0.58%   |
| Unknown             | 38        | 44     | 0.37%   |
| Apple               | 23        | 35     | 0.23%   |
| Hewlett-Packard     | 19        | 24     | 0.19%   |
| ExcelStor           | 12        | 13     | 0.12%   |
| SAGE                | 8         | 13     | 0.08%   |
| XrayDisk            | 6         | 7      | 0.06%   |
| HPE                 | 6         | 6      | 0.06%   |
| TO Exter            | 4         | 5      | 0.04%   |
| External            | 4         | 4      | 0.04%   |
| Initio              | 2         | 2      | 0.02%   |
| WALRAM              | 1         | 1      | 0.01%   |
| USB3.0              | 1         | 1      | 0.01%   |
| Phison              | 1         | 1      | 0.01%   |
| NETAPP              | 1         | 3      | 0.01%   |
| MDT                 | 1         | 1      | 0.01%   |
| Maxtor 6            | 1         | 1      | 0.01%   |
| Lenovo              | 1         | 1      | 0.01%   |
| Intenso             | 1         | 1      | 0.01%   |
| IBM/Hitachi         | 1         | 2      | 0.01%   |
| IBM                 | 1         | 3      | 0.01%   |
| HGST HTS            | 1         | 1      | 0.01%   |
| FEASSO              | 1         | 2      | 0.01%   |
| CLOVER              | 1         | 1      | 0.01%   |
| China               | 1         | 2      | 0.01%   |
| Unknown             | 1         | 1      | 0.01%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 1917      | 2492   | 32.02%  |
| SanDisk             | 710       | 981    | 11.86%  |
| China               | 523       | 634    | 8.74%   |
| WDC                 | 441       | 564    | 7.37%   |
| Samsung Electronics | 382       | 590    | 6.38%   |
| Crucial             | 372       | 483    | 6.21%   |
| A-DATA Technology   | 314       | 381    | 5.25%   |
| KingSpec            | 148       | 169    | 2.47%   |
| LITEON              | 126       | 154    | 2.1%    |
| Lexar               | 102       | 122    | 1.7%    |
| Netac               | 60        | 79     | 1%      |
| Patriot             | 58        | 78     | 0.97%   |
| Intel               | 56        | 70     | 0.94%   |
| PNY                 | 55        | 72     | 0.92%   |
| Corsair             | 52        | 61     | 0.87%   |
| XrayDisk            | 34        | 41     | 0.57%   |
| Gigabyte Technology | 34        | 47     | 0.57%   |
| Unknown             | 32        | 34     | 0.53%   |
| Apple               | 31        | 37     | 0.52%   |
| KingDian            | 30        | 39     | 0.5%    |
| Smart               | 28        | 32     | 0.47%   |
| Hewlett-Packard     | 25        | 29     | 0.42%   |
| SK hynix            | 24        | 28     | 0.4%    |
| Unknown             | 22        | 24     | 0.37%   |
| Toshiba             | 22        | 29     | 0.37%   |
| Seagate             | 18        | 22     | 0.3%    |
| OCZ                 | 16        | 17     | 0.27%   |
| WALRAM              | 15        | 15     | 0.25%   |
| Team                | 14        | 36     | 0.23%   |
| BHT                 | 14        | 19     | 0.23%   |
| LITEONIT            | 13        | 20     | 0.22%   |
| HUSKY               | 13        | 19     | 0.22%   |
| Micron Technology   | 12        | 15     | 0.2%    |
| Win Memory          | 11        | 12     | 0.18%   |
| Maxtor              | 10        | 12     | 0.17%   |
| HS-SSD-C100         | 10        | 10     | 0.17%   |
| BIWIN               | 8         | 9      | 0.13%   |
| S3+                 | 7         | 7      | 0.12%   |
| RZX                 | 7         | 14     | 0.12%   |
| Plextor             | 7         | 8      | 0.12%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 8966      | 13375  | 50.66%  |
| SSD     | 5383      | 7763   | 30.41%  |
| NVMe    | 2681      | 3735   | 15.15%  |
| MMC     | 462       | 658    | 2.61%   |
| Unknown | 208       | 284    | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 11980     | 20770  | 76.8%   |
| NVMe | 2680      | 3732   | 17.18%  |
| SAS  | 477       | 655    | 3.06%   |
| MMC  | 462       | 658    | 2.96%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 9120      | 13859  | 63.61%  |
| 0.51-1.0        | 4409      | 6011   | 30.75%  |
| 1.01-2.0        | 559       | 801    | 3.9%    |
| 3.01-4.0        | 103       | 252    | 0.72%   |
| 2.01-3.0        | 80        | 117    | 0.56%   |
| 4.01-10.0       | 59        | 88     | 0.41%   |
| 10.01-20.0      | 6         | 8      | 0.04%   |
| More than 100.0 | 1         | 1      | 0.01%   |
| 0               | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 4104      | 27.7%   |
| 251-500        | 3542      | 23.91%  |
| 501-1000       | 2395      | 16.17%  |
| 1-20           | 1167      | 7.88%   |
| 1001-2000      | 1128      | 7.61%   |
| 51-100         | 938       | 6.33%   |
| 21-50          | 648       | 4.37%   |
| 2001-3000      | 323       | 2.18%   |
| More than 3000 | 299       | 2.02%   |
| Unknown        | 271       | 1.83%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 5777      | 37.72%  |
| 21-50          | 3224      | 21.05%  |
| 101-250        | 1926      | 12.58%  |
| 51-100         | 1878      | 12.26%  |
| 251-500        | 1039      | 6.78%   |
| 501-1000       | 720       | 4.7%    |
| 1001-2000      | 318       | 2.08%   |
| Unknown        | 271       | 1.77%   |
| 2001-3000      | 87        | 0.57%   |
| More than 3000 | 74        | 0.48%   |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 51        | 55     | 3.3%    |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 49        | 56     | 3.17%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 35        | 38     | 2.26%   |
| Samsung Electronics HD322HJ 320GB   | 31        | 43     | 2.01%   |
| WDC WD5000AAKX-003CA0 500GB         | 27        | 28     | 1.75%   |
| Seagate ST9500325AS 500GB           | 25        | 27     | 1.62%   |
| Samsung Electronics HD161HJ 160GB   | 24        | 25     | 1.55%   |
| Samsung Electronics HD502HI 500GB   | 21        | 26     | 1.36%   |
| Seagate ST1000LM035-1RK172 1TB      | 17        | 18     | 1.1%    |
| Samsung Electronics HD502HJ 500GB   | 16        | 17     | 1.03%   |
| Seagate ST500LT012-9WS142 500GB     | 15        | 17     | 0.97%   |
| Seagate ST1000DM010-2EP102 1TB      | 15        | 19     | 0.97%   |
| Toshiba MQ01ABD100 1TB              | 14        | 14     | 0.91%   |
| Toshiba MQ01ABD050 500GB            | 14        | 14     | 0.91%   |
| Kingston SV300S37A120G 120GB SSD    | 14        | 15     | 0.91%   |
| WDC WD10EARS-00Y5B1 1TB             | 13        | 15     | 0.84%   |
| Seagate ST9320325AS 320GB           | 13        | 13     | 0.84%   |
| Seagate ST3500418AS 500GB           | 12        | 17     | 0.78%   |
| Samsung Electronics HM321HI 320GB   | 12        | 12     | 0.78%   |
| Maxtor STM3160215AS 160GB           | 11        | 13     | 0.71%   |
| WDC WD3200AAJS-00L7A0 320GB         | 10        | 10     | 0.65%   |
| Seagate ST3320418AS 320GB           | 10        | 14     | 0.65%   |
| Samsung Electronics HM160HI 160GB   | 10        | 10     | 0.65%   |
| Samsung Electronics HD250HJ 250GB   | 10        | 11     | 0.65%   |
| Samsung Electronics HD103SI 1TB     | 10        | 13     | 0.65%   |
| Samsung Electronics HD080HJ 80GB    | 10        | 12     | 0.65%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 9         | 10     | 0.58%   |
| Seagate ST31000524AS 1TB            | 9         | 9      | 0.58%   |
| Samsung Electronics HD103SJ 1TB     | 9         | 11     | 0.58%   |
| Kingston SA400S37480G 480GB SSD     | 9         | 10     | 0.58%   |
| Kingston SA400S37240G 240GB SSD     | 9         | 9      | 0.58%   |
| China SSD 120GB                     | 9         | 10     | 0.58%   |
| Seagate ST3500413AS 500GB           | 8         | 9      | 0.52%   |
| Seagate ST3500312CS 500GB           | 8         | 8      | 0.52%   |
| Seagate ST2000DM001-1CH164 2TB      | 8         | 11     | 0.52%   |
| Seagate ST1000DM003-1ER162 1TB      | 8         | 10     | 0.52%   |
| Seagate ST1000DM003-1CH162 1TB      | 8         | 11     | 0.52%   |
| Kingston SA400S37120G 120GB SSD     | 8         | 15     | 0.52%   |
| WDC WD5000AAKX-083CA1 500GB         | 7         | 7      | 0.45%   |
| WDC WD10EZEX-08WN4A0 1TB            | 7         | 7      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| Seagate               | 473       | 567    | 31.92%  |
| WDC                   | 334       | 383    | 22.54%  |
| Samsung Electronics   | 224       | 283    | 15.11%  |
| Toshiba               | 117       | 128    | 7.89%   |
| Hitachi               | 73        | 78     | 4.93%   |
| Kingston              | 53        | 64     | 3.58%   |
| China                 | 38        | 42     | 2.56%   |
| Maxtor                | 25        | 28     | 1.69%   |
| SanDisk               | 23        | 25     | 1.55%   |
| A-DATA Technology     | 15        | 17     | 1.01%   |
| HGST                  | 13        | 14     | 0.88%   |
| XPG                   | 7         | 7      | 0.47%   |
| Intel                 | 7         | 7      | 0.47%   |
| Netac                 | 6         | 8      | 0.4%    |
| Crucial               | 6         | 6      | 0.4%    |
| LITEON                | 5         | 6      | 0.34%   |
| Fujitsu               | 5         | 6      | 0.34%   |
| PNY                   | 4         | 6      | 0.27%   |
| KingSpec              | 4         | 4      | 0.27%   |
| Unknown               | 4         | 4      | 0.27%   |
| OCZ                   | 3         | 3      | 0.2%    |
| JMicron Technology    | 3         | 3      | 0.2%    |
| Hewlett-Packard       | 3         | 4      | 0.2%    |
| Apple                 | 3         | 3      | 0.2%    |
| XrayDisk              | 2         | 4      | 0.13%   |
| WALRAM                | 2         | 2      | 0.13%   |
| Realtek Semiconductor | 2         | 3      | 0.13%   |
| Micron Technology     | 2         | 2      | 0.13%   |
| ExcelStor             | 2         | 3      | 0.13%   |
| Corsair               | 2         | 2      | 0.13%   |
| ADATA Technology      | 2         | 2      | 0.13%   |
| Team                  | 1         | 1      | 0.07%   |
| SSSTC                 | 1         | 1      | 0.07%   |
| SK hynix              | 1         | 1      | 0.07%   |
| Silicon Motion        | 1         | 1      | 0.07%   |
| ShiJi                 | 1         | 4      | 0.07%   |
| SAGE                  | 1         | 1      | 0.07%   |
| Reeinno               | 1         | 1      | 0.07%   |
| QIANGHE               | 1         | 1      | 0.07%   |
| Plextor               | 1         | 1      | 0.07%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 473       | 567    | 37.96%  |
| WDC                 | 310       | 356    | 24.88%  |
| Samsung Electronics | 218       | 276    | 17.5%   |
| Toshiba             | 116       | 127    | 9.31%   |
| Hitachi             | 73        | 78     | 5.86%   |
| Maxtor              | 25        | 28     | 2.01%   |
| HGST                | 13        | 14     | 1.04%   |
| Fujitsu             | 5         | 6      | 0.4%    |
| JMicron Technology  | 3         | 3      | 0.24%   |
| Hewlett-Packard     | 3         | 4      | 0.24%   |
| ExcelStor           | 2         | 3      | 0.16%   |
| Apple               | 2         | 2      | 0.16%   |
| SAGE                | 1         | 1      | 0.08%   |
| Initio              | 1         | 1      | 0.08%   |
| FEASSO              | 1         | 2      | 0.08%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 1141      | 1468   | 82.86%  |
| SSD  | 203       | 231    | 14.74%  |
| NVMe | 33        | 40     | 2.4%    |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 4         | 4      | 10.53%  |
| Samsung Electronics HD502HJ 500GB                | 3         | 7      | 7.89%   |
| Samsung Electronics HM321HI 320GB                | 2         | 2      | 5.26%   |
| Samsung Electronics HM250HI 250GB                | 2         | 2      | 5.26%   |
| Samsung Electronics HD103SJ 1TB                  | 2         | 2      | 5.26%   |
| WDC WD5000AAKS-00C8A0 500GB                      | 1         | 1      | 2.63%   |
| WDC WD3200BPVT-22JJ5T0 320GB                     | 1         | 1      | 2.63%   |
| WDC WD3200BPVT-00JJ5T0 320GB                     | 1         | 1      | 2.63%   |
| WDC WD1600BEVT-22ZCT0 160GB                      | 1         | 1      | 2.63%   |
| WDC WD10SPZX-75Z10T1 1TB                         | 1         | 1      | 2.63%   |
| WDC WD10SPZX-22Z10T0 1TB                         | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD100 1TB                           | 1         | 1      | 2.63%   |
| Toshiba MQ01ABD050 500GB                         | 1         | 1      | 2.63%   |
| Toshiba MK5065GSXN 500GB                         | 1         | 1      | 2.63%   |
| Toshiba DT01ACA100 1TB                           | 1         | 1      | 2.63%   |
| Seagate ST500LM012 HN-M500MBB 500GB              | 1         | 1      | 2.63%   |
| Seagate ST3320613AS 320GB                        | 1         | 1      | 2.63%   |
| Seagate ST3250318AS 250GB                        | 1         | 1      | 2.63%   |
| Seagate ST31000528AS 1TB                         | 1         | 1      | 2.63%   |
| Seagate ST31000340NS 1TB                         | 1         | 1      | 2.63%   |
| Seagate ST1000LM024 HN-M101MBB 1TB               | 1         | 1      | 2.63%   |
| Samsung Electronics MZNTY128HDHP-000H1 128GB SSD | 1         | 1      | 2.63%   |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD  | 1         | 1      | 2.63%   |
| Samsung Electronics HM641JI 640GB                | 1         | 1      | 2.63%   |
| Samsung Electronics HM320JI 320GB                | 1         | 1      | 2.63%   |
| Samsung Electronics HD322GJ 320GB                | 1         | 1      | 2.63%   |
| Samsung Electronics HD080HJ 80GB                 | 1         | 1      | 2.63%   |
| Maxtor STM380215AS 80GB                          | 1         | 1      | 2.63%   |
| Hitachi HTS545032B9A300 320GB                    | 1         | 1      | 2.63%   |
| Hitachi HDS721050DLE630 500GB                    | 1         | 1      | 2.63%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 15        | 19     | 39.47%  |
| Seagate             | 10        | 10     | 26.32%  |
| WDC                 | 6         | 6      | 15.79%  |
| Toshiba             | 4         | 4      | 10.53%  |
| Hitachi             | 2         | 2      | 5.26%   |
| Maxtor              | 1         | 1      | 2.63%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 9732      | 17642  | 65.14%  |
| Works    | 3844      | 6391   | 25.73%  |
| Malfunc  | 1326      | 1739   | 8.87%   |
| Failed   | 38        | 42     | 0.25%   |
| Limited  | 1         | 1      | 0.01%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 10479     | 64.64%  |
| AMD                              | 2334      | 14.4%   |
| ADATA Technology                 | 539       | 3.32%   |
| SanDisk                          | 368       | 2.27%   |
| Samsung Electronics              | 312       | 1.92%   |
| Nvidia                           | 272       | 1.68%   |
| Silicon Motion                   | 267       | 1.65%   |
| Kingston Technology Company      | 199       | 1.23%   |
| Solid State Storage Technology   | 172       | 1.06%   |
| SK hynix                         | 148       | 0.91%   |
| Realtek Semiconductor            | 142       | 0.88%   |
| Phison Electronics               | 135       | 0.83%   |
| Silicon Integrated Systems [SiS] | 108       | 0.67%   |
| Marvell Technology Group         | 99        | 0.61%   |
| JMicron Technology               | 90        | 0.56%   |
| ASMedia Technology               | 86        | 0.53%   |
| VIA Technologies                 | 76        | 0.47%   |
| MAXIO Technology (Hangzhou)      | 64        | 0.39%   |
| Micron/Crucial Technology        | 53        | 0.33%   |
| KIOXIA                           | 41        | 0.25%   |
| Micron Technology                | 33        | 0.2%    |
| Toshiba America Info Systems     | 31        | 0.19%   |
| Lite-On Technology               | 29        | 0.18%   |
| LSI Logic / Symbios Logic        | 27        | 0.17%   |
| Netac Technology                 | 19        | 0.12%   |
| Broadcom / LSI                   | 15        | 0.09%   |
| Union Memory (Shenzhen)          | 10        | 0.06%   |
| Shenzhen Longsys Electronics     | 8         | 0.05%   |
| Beijing Starblaze Technology     | 7         | 0.04%   |
| Silicon Image                    | 6         | 0.04%   |
| Seagate Technology               | 6         | 0.04%   |
| OCZ Technology Group             | 4         | 0.02%   |
| INNOGRIT                         | 4         | 0.02%   |
| Hewlett-Packard                  | 4         | 0.02%   |
| Dell                             | 4         | 0.02%   |
| Apple                            | 4         | 0.02%   |
| Adaptec                          | 4         | 0.02%   |
| TenaFe                           | 2         | 0.01%   |
| O2 Micro                         | 2         | 0.01%   |
| Lenovo                           | 2         | 0.01%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 1389      | 7.07%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 1147      | 5.84%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 936       | 4.76%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 700       | 3.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 646       | 3.29%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 541       | 2.75%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 500       | 2.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 489       | 2.49%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 465       | 2.37%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 439       | 2.23%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 371       | 1.89%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 354       | 1.8%    |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 343       | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 337       | 1.72%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 286       | 1.46%   |
| AMD FCH SATA Controller D                                                               | 279       | 1.42%   |
| AMD 400 Series Chipset SATA Controller                                                  | 274       | 1.39%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 270       | 1.37%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 267       | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 267       | 1.36%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 243       | 1.24%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 239       | 1.22%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 216       | 1.1%    |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 213       | 1.08%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 209       | 1.06%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 200       | 1.02%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 198       | 1.01%   |
| Nvidia MCP61 SATA Controller                                                            | 187       | 0.95%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 186       | 0.95%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 177       | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 177       | 0.9%    |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 169       | 0.86%   |
| ADATA IM2P33F8 series NVMe SSD (DRAM-less)                                              | 169       | 0.86%   |
| ADATA IM2P33F3 NVMe SSD (DRAM-less)                                                     | 169       | 0.86%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 168       | 0.86%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 166       | 0.84%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 164       | 0.83%   |
| Nvidia MCP61 IDE                                                                        | 153       | 0.78%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 152       | 0.77%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                          | 150       | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 10618     | 62.56%  |
| NVMe | 2693      | 15.87%  |
| IDE  | 2618      | 15.43%  |
| RAID | 1015      | 5.98%   |
| SCSI | 17        | 0.1%    |
| SAS  | 11        | 0.06%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Intel        | 11222     | 80.57%  |
| AMD          | 2660      | 19.1%   |
| ARM          | 38        | 0.27%   |
| CentaurHauls | 5         | 0.04%   |
| Qualcomm     | 2         | 0.01%   |
| Unknown      | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-7200U CPU @ 2.50GHz             | 296       | 2.12%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 169       | 1.21%   |
| Intel Core i3-6006U CPU @ 2.00GHz             | 164       | 1.17%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 157       | 1.12%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 156       | 1.12%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 147       | 1.05%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 145       | 1.04%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 144       | 1.03%   |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 139       | 0.99%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 127       | 0.91%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 125       | 0.89%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 119       | 0.85%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 117       | 0.84%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 108       | 0.77%   |
| AMD FX-6300 Six-Core Processor                | 105       | 0.75%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 104       | 0.74%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 103       | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 102       | 0.73%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 102       | 0.73%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 98        | 0.7%    |
| Intel Core i5-2450M CPU @ 2.50GHz             | 97        | 0.69%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 95        | 0.68%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 92        | 0.66%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 92        | 0.66%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 92        | 0.66%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 90        | 0.64%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 89        | 0.64%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 89        | 0.64%   |
| Intel Core i3-3217U CPU @ 1.80GHz             | 89        | 0.64%   |
| Intel Core i3-2100 CPU @ 3.10GHz              | 89        | 0.64%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 87        | 0.62%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 76        | 0.54%   |
| Intel Core i5-3330 CPU @ 3.00GHz              | 75        | 0.54%   |
| Intel Core i5 CPU 650 @ 3.20GHz               | 75        | 0.54%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 75        | 0.54%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 73        | 0.52%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 73        | 0.52%   |
| Intel Celeron CPU 847 @ 1.10GHz               | 73        | 0.52%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 72        | 0.52%   |
| AMD Ryzen 5 3600 6-Core Processor             | 72        | 0.52%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 3347      | 23.97%  |
| Intel Core i7           | 2146      | 15.37%  |
| Intel Core i3           | 1874      | 13.42%  |
| Intel Celeron           | 940       | 6.73%   |
| AMD Ryzen 5             | 716       | 5.13%   |
| Intel Core 2 Duo        | 587       | 4.2%    |
| Other                   | 574       | 4.11%   |
| AMD Ryzen 7             | 407       | 2.91%   |
| Intel Pentium Dual-Core | 346       | 2.48%   |
| Intel Atom              | 345       | 2.47%   |
| Intel Pentium           | 324       | 2.32%   |
| Intel Xeon              | 311       | 2.23%   |
| AMD FX                  | 294       | 2.11%   |
| Intel Pentium Dual      | 157       | 1.12%   |
| AMD Ryzen 3             | 132       | 0.95%   |
| Intel Core 2 Quad       | 110       | 0.79%   |
| AMD Phenom II X4        | 89        | 0.64%   |
| AMD Athlon II X2        | 78        | 0.56%   |
| AMD A4                  | 72        | 0.52%   |
| AMD E                   | 67        | 0.48%   |
| AMD A10                 | 65        | 0.47%   |
| AMD Ryzen 9             | 61        | 0.44%   |
| AMD A6                  | 60        | 0.43%   |
| Intel Core 2            | 59        | 0.42%   |
| AMD Athlon              | 57        | 0.41%   |
| AMD A8                  | 53        | 0.38%   |
| AMD Athlon 64 X2        | 51        | 0.37%   |
| AMD C-60                | 47        | 0.34%   |
| Intel Genuine           | 43        | 0.31%   |
| AMD E1                  | 38        | 0.27%   |
| AMD Sempron             | 33        | 0.24%   |
| AMD Phenom II X6        | 33        | 0.24%   |
| Intel Pentium 4         | 29        | 0.21%   |
| AMD C-70                | 27        | 0.19%   |
| Intel Pentium Gold      | 26        | 0.19%   |
| Intel Core i9           | 25        | 0.18%   |
| AMD Phenom II X2        | 22        | 0.16%   |
| AMD C-50                | 20        | 0.14%   |
| Intel Celeron Dual-Core | 18        | 0.13%   |
| AMD Athlon II X4        | 18        | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 7159      | 51.29%  |
| 4       | 4463      | 31.97%  |
| 6       | 1029      | 7.37%   |
| 8       | 518       | 3.71%   |
| 1       | 370       | 2.65%   |
| 3       | 156       | 1.12%   |
| 12      | 94        | 0.67%   |
| 10      | 63        | 0.45%   |
| 14      | 37        | 0.27%   |
| 16      | 28        | 0.2%    |
| Unknown | 19        | 0.14%   |
| 20      | 7         | 0.05%   |
| 24      | 6         | 0.04%   |
| 28      | 3         | 0.02%   |
| 18      | 3         | 0.02%   |
| 5       | 2         | 0.01%   |
| 32      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 13868     | 99.56%  |
| 2       | 53        | 0.38%   |
| Unknown | 6         | 0.04%   |
| 16      | 1         | 0.01%   |
| 4       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 9152      | 65.6%   |
| 1       | 4777      | 34.24%  |
| Unknown | 19        | 0.14%   |
| 4       | 2         | 0.01%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 13335     | 95.27%  |
| Unknown        | 547       | 3.91%   |
| 32-bit         | 63        | 0.45%   |
| 64-bit         | 52        | 0.37%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 3759      | 25.89%  |
| 0x306a9    | 1061      | 7.31%   |
| 0x206a7    | 1036      | 7.14%   |
| 0x1067a    | 681       | 4.69%   |
| 0x806e9    | 434       | 2.99%   |
| 0x906ea    | 426       | 2.93%   |
| 0x306c3    | 394       | 2.71%   |
| 0x20655    | 393       | 2.71%   |
| 0x40651    | 364       | 2.51%   |
| 0x806ec    | 341       | 2.35%   |
| 0x306d4    | 297       | 2.05%   |
| 0x406e3    | 288       | 1.98%   |
| 0x806ea    | 263       | 1.81%   |
| 0x6fd      | 259       | 1.78%   |
| 0x906e9    | 224       | 1.54%   |
| 0x806c1    | 223       | 1.54%   |
| 0x08108109 | 206       | 1.42%   |
| 0x406c4    | 193       | 1.33%   |
| 0x06000852 | 164       | 1.13%   |
| 0x010000c8 | 142       | 0.98%   |
| 0x30678    | 135       | 0.93%   |
| 0x05000119 | 103       | 0.71%   |
| 0x20652    | 102       | 0.7%    |
| 0x08600103 | 93        | 0.64%   |
| 0x0800820d | 92        | 0.63%   |
| 0x706e5    | 89        | 0.61%   |
| 0x906ed    | 88        | 0.61%   |
| 0x08108102 | 88        | 0.61%   |
| 0x10676    | 85        | 0.59%   |
| 0x706a1    | 81        | 0.56%   |
| 0x08701021 | 81        | 0.56%   |
| 0x506e3    | 80        | 0.55%   |
| 0x6fb      | 68        | 0.47%   |
| 0x406c3    | 67        | 0.46%   |
| 0x306f2    | 67        | 0.46%   |
| 0x106ca    | 65        | 0.45%   |
| 0x706a8    | 64        | 0.44%   |
| 0x806eb    | 58        | 0.4%    |
| 0x0600611a | 58        | 0.4%    |
| 0xa0652    | 56        | 0.39%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 2473      | 17.73%  |
| IvyBridge        | 1408      | 10.09%  |
| SandyBridge      | 1334      | 9.56%   |
| Haswell          | 1076      | 7.71%   |
| Penryn           | 930       | 6.67%   |
| Westmere         | 635       | 4.55%   |
| Silvermont       | 527       | 3.78%   |
| Core             | 521       | 3.74%   |
| Skylake          | 502       | 3.6%    |
| Zen+             | 494       | 3.54%   |
| Broadwell        | 391       | 2.8%    |
| TigerLake        | 339       | 2.43%   |
| K10              | 331       | 2.37%   |
| Zen 2            | 319       | 2.29%   |
| Piledriver       | 317       | 2.27%   |
| Zen              | 259       | 1.86%   |
| Unknown          | 259       | 1.86%   |
| CometLake        | 212       | 1.52%   |
| Zen 3            | 206       | 1.48%   |
| Goldmont plus    | 189       | 1.36%   |
| Bobcat           | 188       | 1.35%   |
| IceLake          | 173       | 1.24%   |
| Bonnell          | 140       | 1%      |
| K8 Hammer        | 113       | 0.81%   |
| Excavator        | 99        | 0.71%   |
| Nehalem          | 85        | 0.61%   |
| Alderlake Hybrid | 79        | 0.57%   |
| Goldmont         | 54        | 0.39%   |
| NetBurst         | 52        | 0.37%   |
| K10 Llano        | 50        | 0.36%   |
| Steamroller      | 49        | 0.35%   |
| Bulldozer        | 47        | 0.34%   |
| Jaguar           | 42        | 0.3%    |
| P6               | 26        | 0.19%   |
| K8 & K10 hybrid  | 11        | 0.08%   |
| Tremont          | 9         | 0.06%   |
| Puma             | 7         | 0.05%   |
| K6               | 1         | 0.01%   |
| Gracemont        | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 9316      | 56.02%  |
| Nvidia                           | 4052      | 24.37%  |
| AMD                              | 3051      | 18.35%  |
| Silicon Integrated Systems [SiS] | 105       | 0.63%   |
| VIA Technologies                 | 57        | 0.34%   |
| Matrox Electronics Systems       | 29        | 0.17%   |
| ASPEED Technology                | 9         | 0.05%   |
| Silicon Motion                   | 4         | 0.02%   |
| ATI Technologies                 | 4         | 0.02%   |
| S3 Graphics                      | 1         | 0.01%   |
| Red Hat                          | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 1104      | 6.48%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 811       | 4.76%   |
| Intel HD Graphics 620                                                                    | 590       | 3.46%   |
| Intel Core Processor Integrated Graphics Controller                                      | 541       | 3.18%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 461       | 2.71%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 423       | 2.48%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 399       | 2.34%   |
| Intel HD Graphics 5500                                                                   | 345       | 2.03%   |
| Intel UHD Graphics 620                                                                   | 338       | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 338       | 1.98%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 331       | 1.94%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 326       | 1.91%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 318       | 1.87%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 286       | 1.68%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 286       | 1.68%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 282       | 1.66%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 220       | 1.29%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 210       | 1.23%   |
| Intel HD Graphics 630                                                                    | 201       | 1.18%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 197       | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 196       | 1.15%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 189       | 1.11%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 186       | 1.09%   |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 178       | 1.05%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 162       | 0.95%   |
| Nvidia GT218 [GeForce 210]                                                               | 157       | 0.92%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 151       | 0.89%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 151       | 0.89%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 128       | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 120       | 0.7%    |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 114       | 0.67%   |
| Nvidia GP108M [GeForce MX150]                                                            | 110       | 0.65%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 107       | 0.63%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 106       | 0.62%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 104       | 0.61%   |
| Nvidia GM108M [GeForce MX110]                                                            | 103       | 0.6%    |
| Intel 82945G/GZ Integrated Graphics Controller                                           | 102       | 0.6%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 102       | 0.6%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 100       | 0.59%   |
| Silicon Integrated Systems [SiS] 771/671 PCIE VGA Display Adapter                        | 99        | 0.58%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 6860      | 48.91%  |
| 1 x AMD                 | 2259      | 16.11%  |
| 1 x Nvidia              | 1930      | 13.76%  |
| Intel + Nvidia          | 1880      | 13.4%   |
| Intel + AMD             | 460       | 3.28%   |
| AMD + Nvidia            | 208       | 1.48%   |
| 2 x AMD                 | 130       | 0.93%   |
| 1 x SiS                 | 105       | 0.75%   |
| 1 x VIA                 | 56        | 0.4%    |
| Other                   | 44        | 0.31%   |
| 2 x Intel               | 30        | 0.21%   |
| 1 x Matrox              | 28        | 0.2%    |
| 2 x Nvidia              | 18        | 0.13%   |
| 1 x ASPEED              | 8         | 0.06%   |
| Intel + Silicon Motion  | 2         | 0.01%   |
| 1 x Silicon Motion      | 1         | 0.01%   |
| 1 x S3 Graphics         | 1         | 0.01%   |
| 1 x Red Hat             | 1         | 0.01%   |
| Nvidia + Silicon Motion | 1         | 0.01%   |
| Nvidia + ASPEED         | 1         | 0.01%   |
| Intel + 2 x AMD         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |
| AMD + Matrox            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 11234     | 79.65%  |
| Proprietary | 2327      | 16.5%   |
| Unknown     | 543       | 3.85%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 8842      | 61.83%  |
| 1.01-2.0   | 1943      | 13.59%  |
| 0.01-0.5   | 1179      | 8.24%   |
| 0.51-1.0   | 895       | 6.26%   |
| 3.01-4.0   | 867       | 6.06%   |
| 7.01-8.0   | 264       | 1.85%   |
| 5.01-6.0   | 206       | 1.44%   |
| 2.01-3.0   | 68        | 0.48%   |
| 8.01-16.0  | 32        | 0.22%   |
| 16.01-24.0 | 3         | 0.02%   |
| 4.01-5.0   | 2         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 2170      | 14.36%  |
| Goldstar                | 1989      | 13.17%  |
| BOE                     | 1811      | 11.99%  |
| AU Optronics            | 1752      | 11.6%   |
| Chimei Innolux          | 1431      | 9.47%   |
| LG Display              | 1266      | 8.38%   |
| AOC                     | 1013      | 6.71%   |
| Dell                    | 620       | 4.1%    |
| Philips                 | 404       | 2.67%   |
| Acer                    | 237       | 1.57%   |
| Chi Mei Optoelectronics | 169       | 1.12%   |
| LG Electronics          | 166       | 1.1%    |
| Hewlett-Packard         | 156       | 1.03%   |
| InfoVision              | 140       | 0.93%   |
| PANDA                   | 137       | 0.91%   |
| Apple                   | 136       | 0.9%    |
| Lenovo                  | 132       | 0.87%   |
| Sony                    | 105       | 0.69%   |
| BenQ                    | 75        | 0.5%    |
| Unknown                 | 72        | 0.48%   |
| RTK                     | 55        | 0.36%   |
| HannStar                | 52        | 0.34%   |
| Positivo                | 51        | 0.34%   |
| CPT                     | 50        | 0.33%   |
| LG Philips              | 44        | 0.29%   |
| ASUSTek Computer        | 43        | 0.28%   |
| Panasonic               | 41        | 0.27%   |
| SLD                     | 36        | 0.24%   |
| InnoLux Display         | 33        | 0.22%   |
| GDH                     | 33        | 0.22%   |
| Unknown (XXX)           | 32        | 0.21%   |
| Sharp                   | 30        | 0.2%    |
| VIE                     | 28        | 0.19%   |
| Ancor Communications    | 28        | 0.19%   |
| NCS                     | 25        | 0.17%   |
| MTD                     | 21        | 0.14%   |
| Toshiba                 | 20        | 0.13%   |
| STA                     | 20        | 0.13%   |
| Valve                   | 17        | 0.11%   |
| SKY                     | 17        | 0.11%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch             | 195       | 1.26%   |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch      | 130       | 0.84%   |
| AU Optronics LCD Monitor AUO183C 1366x768 309x173mm 13.9-inch        | 130       | 0.84%   |
| Chimei Innolux LCD Monitor CMN15DC 1366x768 344x193mm 15.5-inch      | 129       | 0.83%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch        | 127       | 0.82%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch      | 119       | 0.77%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 114       | 0.73%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 112       | 0.72%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 110       | 0.71%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch          | 107       | 0.69%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 103       | 0.66%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 91        | 0.59%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 88        | 0.57%   |
| BOE LCD Monitor BOE0757 1366x768 344x194mm 15.5-inch                 | 82        | 0.53%   |
| BOE LCD Monitor BOE0672 1366x768 344x194mm 15.5-inch                 | 82        | 0.53%   |
| AU Optronics LCD Monitor AUO81EC 1366x768 344x193mm 15.5-inch        | 82        | 0.53%   |
| AOC 1970W AOC1970 1366x768 410x230mm 18.5-inch                       | 82        | 0.53%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 81        | 0.52%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 71        | 0.46%   |
| LG Display LCD Monitor LGD0385 1366x768 309x174mm 14.0-inch          | 70        | 0.45%   |
| Goldstar HD GSM5ACB 1366x768 410x230mm 18.5-inch                     | 70        | 0.45%   |
| BOE LCD Monitor BOE0818 1920x1080 344x194mm 15.5-inch                | 67        | 0.43%   |
| InfoVision M140NWR2 R1 IVO057A 1366x768 309x174mm 14.0-inch          | 63        | 0.41%   |
| AU Optronics LCD Monitor AUO303C 1366x768 309x173mm 13.9-inch        | 63        | 0.41%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch              | 61        | 0.39%   |
| Goldstar ULTRAWIDE GSM76F9 2560x1080 531x298mm 24.0-inch             | 61        | 0.39%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 60        | 0.39%   |
| Goldstar 23MP55 GSM5A23 1920x1080 510x290mm 23.1-inch                | 58        | 0.37%   |
| BOE LCD Monitor BOE07CE 1366x768 344x193mm 15.5-inch                 | 58        | 0.37%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch      | 57        | 0.37%   |
| Samsung Electronics LCD Monitor SEC4542 1366x768 309x174mm 14.0-inch | 56        | 0.36%   |
| Goldstar 2D HD TV GSM59CA 1366x768 509x286mm 23.0-inch               | 52        | 0.33%   |
| Chimei Innolux LCD Monitor CMN1470 1366x768 309x174mm 14.0-inch      | 52        | 0.33%   |
| AOC F19 AOC1900 1366x768 410x230mm 18.5-inch                         | 52        | 0.33%   |
| BOE LCD Monitor BOE0671 1366x768 344x194mm 15.5-inch                 | 51        | 0.33%   |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch        | 50        | 0.32%   |
| BOE LCD Monitor BOE0696 1366x768 309x173mm 13.9-inch                 | 49        | 0.32%   |
| LG Display LCD Monitor LGD065A 1920x1080 344x194mm 15.5-inch         | 47        | 0.3%    |
| BOE LCD Monitor BOE0808 1366x768 344x194mm 15.5-inch                 | 47        | 0.3%    |
| BOE LCD Monitor BOE05B1 1366x768 309x173mm 13.9-inch                 | 47        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1366x768 (WXGA)    | 5698      | 38.8%   |
| 1920x1080 (FHD)    | 4754      | 32.38%  |
| 1600x900 (HD+)     | 613       | 4.17%   |
| 2560x1080          | 479       | 3.26%   |
| 1440x900 (WXGA+)   | 473       | 3.22%   |
| 3840x2160 (4K)     | 399       | 2.72%   |
| 1360x768           | 393       | 2.68%   |
| 1280x1024 (SXGA)   | 382       | 2.6%    |
| 1280x800 (WXGA)    | 347       | 2.36%   |
| 1680x1050 (WSXGA+) | 216       | 1.47%   |
| 2560x1440 (QHD)    | 172       | 1.17%   |
| 1024x768 (XGA)     | 134       | 0.91%   |
| Unknown            | 112       | 0.76%   |
| 1920x1200 (WUXGA)  | 80        | 0.54%   |
| 1280x720 (HD)      | 57        | 0.39%   |
| 1920x540           | 48        | 0.33%   |
| 1024x600           | 44        | 0.3%    |
| 3840x1080          | 31        | 0.21%   |
| 2288x1287          | 29        | 0.2%    |
| 2560x1600          | 27        | 0.18%   |
| 3440x1440          | 24        | 0.16%   |
| 800x1280           | 16        | 0.11%   |
| 2880x1800          | 12        | 0.08%   |
| 1152x864           | 9         | 0.06%   |
| 1600x1200          | 8         | 0.05%   |
| 3840x2400          | 7         | 0.05%   |
| 1280x960           | 7         | 0.05%   |
| 5760x1080          | 6         | 0.04%   |
| 4480x1080          | 6         | 0.04%   |
| 2736x1824          | 6         | 0.04%   |
| 3360x1080          | 5         | 0.03%   |
| 3286x1080          | 5         | 0.03%   |
| 3200x1080          | 5         | 0.03%   |
| 3200x1800 (QHD+)   | 4         | 0.03%   |
| 3600x1080          | 3         | 0.02%   |
| 3520x1080          | 3         | 0.02%   |
| 2732x768           | 3         | 0.02%   |
| 2160x1440          | 3         | 0.02%   |
| 6400x1080          | 2         | 0.01%   |
| 5760x2160          | 2         | 0.01%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 4388      | 28.92%  |
| 14      | 1766      | 11.64%  |
| 13      | 1565      | 10.32%  |
| 18      | 999       | 6.58%   |
| 21      | 978       | 6.45%   |
| 23      | 913       | 6.02%   |
| 17      | 598       | 3.94%   |
| Unknown | 556       | 3.66%   |
| 24      | 484       | 3.19%   |
| 34      | 414       | 2.73%   |
| 27      | 392       | 2.58%   |
| 20      | 382       | 2.52%   |
| 19      | 356       | 2.35%   |
| 31      | 181       | 1.19%   |
| 11      | 140       | 0.92%   |
| 22      | 133       | 0.88%   |
| 12      | 94        | 0.62%   |
| 54      | 83        | 0.55%   |
| 40      | 79        | 0.52%   |
| 72      | 77        | 0.51%   |
| 28      | 74        | 0.49%   |
| 32      | 69        | 0.45%   |
| 84      | 66        | 0.44%   |
| 16      | 57        | 0.38%   |
| 10      | 50        | 0.33%   |
| 52      | 46        | 0.3%    |
| 26      | 45        | 0.3%    |
| 46      | 36        | 0.24%   |
| 142     | 17        | 0.11%   |
| 37      | 17        | 0.11%   |
| 7       | 16        | 0.11%   |
| 25      | 15        | 0.1%    |
| 48      | 13        | 0.09%   |
| 49      | 9         | 0.06%   |
| 65      | 7         | 0.05%   |
| 58      | 7         | 0.05%   |
| 43      | 7         | 0.05%   |
| 47      | 5         | 0.03%   |
| 41      | 5         | 0.03%   |
| 39      | 5         | 0.03%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 7589      | 50.72%  |
| 401-500        | 2708      | 18.1%   |
| 501-600        | 1719      | 11.49%  |
| 201-300        | 566       | 3.78%   |
| Unknown        | 556       | 3.72%   |
| 351-400        | 518       | 3.46%   |
| 701-800        | 486       | 3.25%   |
| 601-700        | 306       | 2.05%   |
| 1001-1500      | 219       | 1.46%   |
| 1501-2000      | 145       | 0.97%   |
| 801-900        | 104       | 0.7%    |
| More than 2000 | 17        | 0.11%   |
| 1-100          | 16        | 0.11%   |
| 901-1000       | 14        | 0.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 10888     | 79.92%  |
| 16/10   | 1102      | 8.09%   |
| 21/9    | 468       | 3.44%   |
| Unknown | 464       | 3.41%   |
| 5/4     | 380       | 2.79%   |
| 4/3     | 202       | 1.48%   |
| 3/2     | 65        | 0.48%   |
| 1.00    | 19        | 0.14%   |
| 0.67    | 16        | 0.12%   |
| 32/9    | 11        | 0.08%   |
| 2.00    | 3         | 0.02%   |
| 0.56    | 3         | 0.02%   |
| 6/5     | 2         | 0.01%   |
| 0.31    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 4349      | 28.81%  |
| 81-90          | 3109      | 20.6%   |
| 201-250        | 2125      | 14.08%  |
| 141-150        | 1197      | 7.93%   |
| 151-200        | 1065      | 7.06%   |
| 351-500        | 685       | 4.54%   |
| Unknown        | 556       | 3.68%   |
| 301-350        | 404       | 2.68%   |
| More than 1000 | 330       | 2.19%   |
| 71-80          | 225       | 1.49%   |
| 251-300        | 194       | 1.29%   |
| 501-1000       | 172       | 1.14%   |
| 121-130        | 169       | 1.12%   |
| 131-140        | 143       | 0.95%   |
| 51-60          | 140       | 0.93%   |
| 91-100         | 59        | 0.39%   |
| 61-70          | 53        | 0.35%   |
| 111-120        | 52        | 0.34%   |
| 41-50          | 50        | 0.33%   |
| 1-40           | 16        | 0.11%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 101-120       | 5980      | 40.87%  |
| 51-100        | 4895      | 33.46%  |
| 121-160       | 2500      | 17.09%  |
| Unknown       | 557       | 3.81%   |
| 1-50          | 423       | 2.89%   |
| 161-240       | 243       | 1.66%   |
| More than 240 | 33        | 0.23%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 11246     | 78.91%  |
| 2     | 2317      | 16.26%  |
| 0     | 560       | 3.93%   |
| 3     | 122       | 0.86%   |
| 4     | 7         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 9980      | 45.36%  |
| Qualcomm Atheros                  | 4123      | 18.74%  |
| Intel                             | 3870      | 17.59%  |
| Broadcom                          | 1003      | 4.56%   |
| Ralink Technology                 | 460       | 2.09%   |
| Marvell Technology Group          | 255       | 1.16%   |
| Ralink                            | 251       | 1.14%   |
| JMicron Technology                | 240       | 1.09%   |
| Nvidia                            | 224       | 1.02%   |
| TP-Link                           | 223       | 1.01%   |
| Broadcom Limited                  | 211       | 0.96%   |
| Qualcomm Atheros Communications   | 146       | 0.66%   |
| Samsung Electronics               | 133       | 0.6%    |
| Silicon Integrated Systems [SiS]  | 106       | 0.48%   |
| MediaTek                          | 93        | 0.42%   |
| D-Link                            | 87        | 0.4%    |
| VIA Technologies                  | 73        | 0.33%   |
| Xiaomi                            | 64        | 0.29%   |
| ASIX Electronics                  | 58        | 0.26%   |
| Motorola PCS                      | 55        | 0.25%   |
| Microsoft                         | 54        | 0.25%   |
| D-Link System                     | 46        | 0.21%   |
| ICS Advent                        | 20        | 0.09%   |
| DisplayLink                       | 16        | 0.07%   |
| Motorola                          | 14        | 0.06%   |
| Huawei Technologies               | 14        | 0.06%   |
| Dell                              | 11        | 0.05%   |
| Edimax Technology                 | 9         | 0.04%   |
| Qualcomm                          | 8         | 0.04%   |
| LG Electronics                    | 8         | 0.04%   |
| Microchip Technology              | 7         | 0.03%   |
| Mercucys                          | 7         | 0.03%   |
| ASUSTek Computer                  | 7         | 0.03%   |
| QinHeng Electronics               | 5         | 0.02%   |
| Lenovo                            | 5         | 0.02%   |
| Ericsson Business Mobile Networks | 5         | 0.02%   |
| Arduino SA                        | 5         | 0.02%   |
| Accton Technology                 | 5         | 0.02%   |
| 3Com                              | 5         | 0.02%   |
| Sundance Technology Inc / IC Plus | 4         | 0.02%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 6522      | 27.03%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2097      | 8.69%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 961       | 3.98%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 861       | 3.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 713       | 2.96%   |
| Intel Wi-Fi 6 AX200                                                    | 410       | 1.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 358       | 1.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                             | 351       | 1.45%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 351       | 1.45%   |
| Intel Wi-Fi 6 AX201                                                    | 311       | 1.29%   |
| Ralink MT7601U Wireless Adapter                                        | 262       | 1.09%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 239       | 0.99%   |
| Intel Wireless 7265                                                    | 206       | 0.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 203       | 0.84%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 194       | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 170       | 0.7%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 169       | 0.7%    |
| Nvidia MCP61 Ethernet                                                  | 165       | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 156       | 0.65%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 150       | 0.62%   |
| Realtek Killer E2600 GbE Controller                                    | 145       | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                      | 142       | 0.59%   |
| Realtek RTL8188EE Wireless Network Adapter                             | 137       | 0.57%   |
| Intel Wireless 7260                                                    | 132       | 0.55%   |
| Qualcomm Atheros AR9271 802.11n                                        | 131       | 0.54%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter                  | 123       | 0.51%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 123       | 0.51%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter               | 122       | 0.51%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 121       | 0.5%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 119       | 0.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 115       | 0.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 115       | 0.48%   |
| Intel Wireless 3165                                                    | 110       | 0.46%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 108       | 0.45%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 105       | 0.44%   |
| Realtek 802.11ac NIC                                                   | 104       | 0.43%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 99        | 0.41%   |
| Intel Ethernet Connection (2) I219-V                                   | 99        | 0.41%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 98        | 0.41%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                       | 97        | 0.4%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Qualcomm Atheros                      | 3598      | 33.87%  |
| Intel                                 | 3017      | 28.4%   |
| Realtek Semiconductor                 | 1890      | 17.79%  |
| Broadcom                              | 617       | 5.81%   |
| Ralink Technology                     | 460       | 4.33%   |
| Ralink                                | 251       | 2.36%   |
| TP-Link                               | 201       | 1.89%   |
| Qualcomm Atheros Communications       | 146       | 1.37%   |
| Broadcom Limited                      | 120       | 1.13%   |
| D-Link                                | 87        | 0.82%   |
| MediaTek                              | 79        | 0.74%   |
| Microsoft                             | 54        | 0.51%   |
| D-Link System                         | 32        | 0.3%    |
| Marvell Technology Group              | 10        | 0.09%   |
| Edimax Technology                     | 9         | 0.08%   |
| Mercucys                              | 7         | 0.07%   |
| Dell                                  | 7         | 0.07%   |
| Micro Star International              | 4         | 0.04%   |
| Linksys                               | 4         | 0.04%   |
| Encore Electronics                    | 4         | 0.04%   |
| NetGear                               | 3         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 3         | 0.03%   |
| Xiaomi                                | 2         | 0.02%   |
| Sierra Wireless                       | 2         | 0.02%   |
| Philips (or NXP)                      | 2         | 0.02%   |
| IMC Networks                          | 2         | 0.02%   |
| Ericsson Business Mobile Networks     | 2         | 0.02%   |
| ASUSTek Computer                      | 2         | 0.02%   |
| Accton Technology                     | 2         | 0.02%   |
| Texas Instruments                     | 1         | 0.01%   |
| Samsung Electronics                   | 1         | 0.01%   |
| Qualcomm Technologies                 | 1         | 0.01%   |
| Pegatron                              | 1         | 0.01%   |
| Guillemot                             | 1         | 0.01%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 961       | 8.99%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 861       | 8.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 713       | 6.67%   |
| Intel Wi-Fi 6 AX200                                            | 410       | 3.84%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 358       | 3.35%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 351       | 3.28%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 351       | 3.28%   |
| Intel Wi-Fi 6 AX201                                            | 311       | 2.91%   |
| Ralink MT7601U Wireless Adapter                                | 262       | 2.45%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 239       | 2.24%   |
| Intel Wireless 7265                                            | 206       | 1.93%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 194       | 1.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 156       | 1.46%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 150       | 1.4%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 137       | 1.28%   |
| Intel Wireless 7260                                            | 132       | 1.23%   |
| Qualcomm Atheros AR9271 802.11n                                | 131       | 1.23%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter          | 123       | 1.15%   |
| Realtek RTL8187B Wireless 802.11g 54Mbps Network Adapter       | 122       | 1.14%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 121       | 1.13%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 119       | 1.11%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 115       | 1.08%   |
| Intel Wireless 3165                                            | 110       | 1.03%   |
| Realtek 802.11ac NIC                                           | 104       | 0.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 97        | 0.91%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 95        | 0.89%   |
| Ralink RT5370 Wireless Adapter                                 | 94        | 0.88%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 93        | 0.87%   |
| Intel Wireless 3160                                            | 92        | 0.86%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 90        | 0.84%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 89        | 0.83%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 87        | 0.81%   |
| Intel Wireless 8265 / 8275                                     | 82        | 0.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 79        | 0.74%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 76        | 0.71%   |
| Intel Centrino Advanced-N 6235                                 | 75        | 0.7%    |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 72        | 0.67%   |
| Realtek RTL8191SEvB Wireless LAN Controller                    | 68        | 0.64%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 65        | 0.61%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 64        | 0.6%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 9130      | 69.4%   |
| Intel                             | 1292      | 9.82%   |
| Qualcomm Atheros                  | 800       | 6.08%   |
| Broadcom                          | 482       | 3.66%   |
| Marvell Technology Group          | 245       | 1.86%   |
| JMicron Technology                | 240       | 1.82%   |
| Nvidia                            | 223       | 1.7%    |
| Samsung Electronics               | 132       | 1%      |
| Silicon Integrated Systems [SiS]  | 106       | 0.81%   |
| Broadcom Limited                  | 98        | 0.74%   |
| VIA Technologies                  | 72        | 0.55%   |
| Xiaomi                            | 62        | 0.47%   |
| ASIX Electronics                  | 58        | 0.44%   |
| Motorola PCS                      | 43        | 0.33%   |
| TP-Link                           | 22        | 0.17%   |
| ICS Advent                        | 20        | 0.15%   |
| DisplayLink                       | 16        | 0.12%   |
| D-Link System                     | 14        | 0.11%   |
| MediaTek                          | 13        | 0.1%    |
| Huawei Technologies               | 9         | 0.07%   |
| Qualcomm                          | 7         | 0.05%   |
| LG Electronics                    | 6         | 0.05%   |
| Microchip Technology              | 5         | 0.04%   |
| Lenovo                            | 5         | 0.04%   |
| ASUSTek Computer                  | 5         | 0.04%   |
| 3Com                              | 5         | 0.04%   |
| Sundance Technology Inc / IC Plus | 4         | 0.03%   |
| OPPO Electronics                  | 4         | 0.03%   |
| Attansic Technology               | 4         | 0.03%   |
| Hangzhou Silan Microelectronics   | 3         | 0.02%   |
| Dell                              | 3         | 0.02%   |
| Aquantia                          | 3         | 0.02%   |
| Apple                             | 3         | 0.02%   |
| Accton Technology                 | 3         | 0.02%   |
| ZTE WCDMA Technologies MSM        | 2         | 0.02%   |
| T & A Mobile Phones               | 2         | 0.02%   |
| Standard Microsystems             | 2         | 0.02%   |
| Spreadtrum Communications         | 2         | 0.02%   |
| IBM                               | 2         | 0.02%   |
| SK hynix                          | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 6522      | 48.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 2097      | 15.71%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 203       | 1.52%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 170       | 1.27%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 169       | 1.27%   |
| Nvidia MCP61 Ethernet                                                  | 165       | 1.24%   |
| Realtek Killer E2600 GbE Controller                                    | 145       | 1.09%   |
| Realtek RTL8125 2.5GbE Controller                                      | 142       | 1.06%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 123       | 0.92%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 115       | 0.86%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                        | 108       | 0.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 105       | 0.79%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 99        | 0.74%   |
| Intel Ethernet Connection (2) I219-V                                   | 99        | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 98        | 0.73%   |
| Intel Ethernet Connection (7) I219-V                                   | 93        | 0.7%    |
| Intel I211 Gigabit Network Connection                                  | 89        | 0.67%   |
| Marvell Group 88E8040 PCI-E Fast Ethernet Controller                   | 84        | 0.63%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 83        | 0.62%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 77        | 0.58%   |
| Qualcomm Atheros AR8162 Fast Ethernet                                  | 74        | 0.55%   |
| Intel 82579V Gigabit Network Connection                                | 72        | 0.54%   |
| JMicron JMC260 PCI Express Fast Ethernet Controller                    | 71        | 0.53%   |
| Intel Ethernet Connection I217-LM                                      | 69        | 0.52%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                      | 57        | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 54        | 0.4%    |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 54        | 0.4%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                        | 53        | 0.4%    |
| ASIX AX88179 Gigabit Ethernet                                          | 50        | 0.37%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 48        | 0.36%   |
| Intel 82578DC Gigabit Network Connection                               | 46        | 0.34%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 45        | 0.34%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 43        | 0.32%   |
| Motorola PCS moto g52                                                  | 43        | 0.32%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 43        | 0.32%   |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                      | 42        | 0.31%   |
| Intel Ethernet Connection (4) I219-LM                                  | 38        | 0.28%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 37        | 0.28%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 36        | 0.27%   |
| Intel Ethernet Controller I225-V                                       | 36        | 0.27%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 12669     | 55.2%   |
| WiFi     | 10190     | 44.4%   |
| Modem    | 68        | 0.3%    |
| Unknown  | 26        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 8328      | 57.66%  |
| Ethernet | 6114      | 42.33%  |
| Unknown  | 2         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 7956      | 56.82%  |
| 1     | 5487      | 39.19%  |
| 0     | 429       | 3.06%   |
| 3     | 100       | 0.71%   |
| 4     | 21        | 0.15%   |
| 10    | 3         | 0.02%   |
| 5     | 3         | 0.02%   |
| 8     | 1         | 0.01%   |
| 6     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 10481     | 73.12%  |
| Yes  | 3852      | 26.88%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2616      | 35.92%  |
| Qualcomm Atheros Communications | 1771      | 24.32%  |
| Lite-On Technology              | 730       | 10.02%  |
| Cambridge Silicon Radio         | 616       | 8.46%   |
| Realtek Semiconductor           | 345       | 4.74%   |
| Broadcom                        | 248       | 3.41%   |
| IMC Networks                    | 184       | 2.53%   |
| Apple                           | 162       | 2.22%   |
| Foxconn / Hon Hai               | 144       | 1.98%   |
| Dell                            | 88        | 1.21%   |
| Hewlett-Packard                 | 65        | 0.89%   |
| Ralink                          | 60        | 0.82%   |
| Smart Modular Technologies      | 50        | 0.69%   |
| Qcom                            | 29        | 0.4%    |
| MediaTek                        | 27        | 0.37%   |
| ASUSTek Computer                | 24        | 0.33%   |
| Ralink Technology               | 18        | 0.25%   |
| Foxconn International           | 16        | 0.22%   |
| Alps Electric                   | 15        | 0.21%   |
| Askey Computer                  | 11        | 0.15%   |
| Actions                         | 10        | 0.14%   |
| Integrated System Solution      | 8         | 0.11%   |
| Toshiba                         | 6         | 0.08%   |
| Micro Star International        | 6         | 0.08%   |
| TP-Link                         | 5         | 0.07%   |
| Opticis                         | 5         | 0.07%   |
| Marvell Semiconductor           | 4         | 0.05%   |
| Realtek                         | 3         | 0.04%   |
| Conwise Technology              | 3         | 0.04%   |
| Unknown                         | 3         | 0.04%   |
| Syntek                          | 2         | 0.03%   |
| SINO WEALTH                     | 2         | 0.03%   |
| USI                             | 1         | 0.01%   |
| Motorola PCS                    | 1         | 0.01%   |
| Fujitsu                         | 1         | 0.01%   |
| Dynex                           | 1         | 0.01%   |
| D-Link                          | 1         | 0.01%   |
| AboCom Systems                  | 1         | 0.01%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros  Bluetooth Device                                                  | 1033      | 14.18%  |
| Intel Bluetooth wireless interface                                                  | 823       | 11.3%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 672       | 9.23%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 616       | 8.46%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 404       | 5.55%   |
| Intel AX200 Bluetooth                                                               | 399       | 5.48%   |
| Intel AX201 Bluetooth                                                               | 318       | 4.37%   |
| Realtek Bluetooth Radio                                                             | 273       | 3.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 265       | 3.64%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 161       | 2.21%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 158       | 2.17%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 134       | 1.84%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 106       | 1.46%   |
| Intel Bluetooth Device                                                              | 106       | 1.46%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 105       | 1.44%   |
| IMC Networks Bluetooth Radio                                                        | 102       | 1.4%    |
| Lite-On Bluetooth Device                                                            | 99        | 1.36%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 96        | 1.32%   |
| Apple Bluetooth Host Controller                                                     | 77        | 1.06%   |
| Lite-On Qualcomm Atheros Bluetooth                                                  | 71        | 0.97%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR                                                | 64        | 0.88%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 62        | 0.85%   |
| Ralink RT3290 Bluetooth                                                             | 60        | 0.82%   |
| Smart Modular Bluetooth Device                                                      | 50        | 0.69%   |
| Intel AX210 Bluetooth                                                               | 50        | 0.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 48        | 0.66%   |
| Dell Wireless 365 Bluetooth                                                         | 38        | 0.52%   |
| Apple Bluetooth USB Host Controller                                                 | 38        | 0.52%   |
| IMC Networks Bluetooth Device                                                       | 35        | 0.48%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 35        | 0.48%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 35        | 0.48%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 33        | 0.45%   |
| MediaTek Wireless_Device                                                            | 27        | 0.37%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 26        | 0.36%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 25        | 0.34%   |
| Lite-On Wireless_Device                                                             | 25        | 0.34%   |
| Foxconn / Hon Hai Bluetooth USB Host Controller                                     | 25        | 0.34%   |
| Lite-On Atheros Bluetooth                                                           | 24        | 0.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 23        | 0.32%   |
| Dell DW375 Bluetooth Module                                                         | 20        | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                                          | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Intel                                           | 10715     | 59.44%  |
| AMD                                             | 3029      | 16.8%   |
| Nvidia                                          | 2763      | 15.33%  |
| C-Media Electronics                             | 312       | 1.73%   |
| Generalplus Technology                          | 151       | 0.84%   |
| Logitech                                        | 115       | 0.64%   |
| Silicon Integrated Systems [SiS]                | 107       | 0.59%   |
| VIA Technologies                                | 80        | 0.44%   |
| JMTek                                           | 79        | 0.44%   |
| Kingston Technology                             | 75        | 0.42%   |
| Texas Instruments                               | 55        | 0.31%   |
| Creative Labs                                   | 42        | 0.23%   |
| Corsair                                         | 33        | 0.18%   |
| Microsoft                                       | 28        | 0.16%   |
| Plantronics                                     | 23        | 0.13%   |
| Razer USA                                       | 19        | 0.11%   |
| Sony                                            | 18        | 0.1%    |
| Realtek Semiconductor                           | 18        | 0.1%    |
| GN Netcom                                       | 18        | 0.1%    |
| Tenx Technology                                 | 17        | 0.09%   |
| BEHRINGER International                         | 17        | 0.09%   |
| Licensed by Sony Computer Entertainment America | 16        | 0.09%   |
| Dell                                            | 14        | 0.08%   |
| Goldvish                                        | 12        | 0.07%   |
| ASUSTek Computer                                | 12        | 0.07%   |
| JBL                                             | 11        | 0.06%   |
| Focusrite-Novation                              | 11        | 0.06%   |
| Samson Technologies                             | 10        | 0.06%   |
| M-Audio                                         | 9         | 0.05%   |
| FIFINE Microphones                              | 9         | 0.05%   |
| BR23                                            | 9         | 0.05%   |
| SteelSeries ApS                                 | 8         | 0.04%   |
| KTMicro                                         | 8         | 0.04%   |
| Samsung Electronics                             | 7         | 0.04%   |
| Fry's Electronics                               | 7         | 0.04%   |
| Creative Technology                             | 7         | 0.04%   |
| Philips (or NXP)                                | 6         | 0.03%   |
| Astro Gaming                                    | 6         | 0.03%   |
| Unknown                                         | 6         | 0.03%   |
| Tdlasunnic                                      | 5         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 1357      | 6.46%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1320      | 6.28%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1319      | 6.28%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 871       | 4.15%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 766       | 3.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 671       | 3.19%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 627       | 2.98%   |
| Intel Cannon Lake PCH cAVS                                                                        | 577       | 2.75%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 503       | 2.39%   |
| Intel 8 Series HD Audio Controller                                                                | 463       | 2.2%    |
| Intel Haswell-ULT HD Audio Controller                                                             | 458       | 2.18%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 449       | 2.14%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 416       | 1.98%   |
| Intel Broadwell-U Audio Controller                                                                | 368       | 1.75%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 365       | 1.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 357       | 1.7%    |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 345       | 1.64%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 338       | 1.61%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 332       | 1.58%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 307       | 1.46%   |
| AMD FCH Azalia Controller                                                                         | 286       | 1.36%   |
| Nvidia High Definition Audio Controller                                                           | 267       | 1.27%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 264       | 1.26%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 257       | 1.22%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 243       | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 236       | 1.12%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 228       | 1.09%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 221       | 1.05%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 207       | 0.99%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 194       | 0.92%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 189       | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 184       | 0.88%   |
| Nvidia MCP61 High Definition Audio                                                                | 181       | 0.86%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 171       | 0.81%   |
| Intel 200 Series PCH HD Audio                                                                     | 168       | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 166       | 0.79%   |
| AMD Wrestler HDMI Audio                                                                           | 165       | 0.79%   |
| Generalplus Technology USB Audio Device                                                           | 151       | 0.72%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 139       | 0.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 138       | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 1030      | 16.57%  |
| Kingston            | 995       | 16%     |
| Smart               | 826       | 13.29%  |
| Samsung Electronics | 591       | 9.51%   |
| SK hynix            | 406       | 6.53%   |
| A-DATA Technology   | 390       | 6.27%   |
| Corsair             | 275       | 4.42%   |
| Teikon              | 214       | 3.44%   |
| Crucial             | 213       | 3.43%   |
| Micron Technology   | 212       | 3.41%   |
| Smart Brazil        | 129       | 2.07%   |
| Unknown             | 93        | 1.5%    |
| High Bridge         | 71        | 1.14%   |
| Team                | 65        | 1.05%   |
| Elpida              | 56        | 0.9%    |
| Multilaser          | 54        | 0.87%   |
| Unknown (ABCD)      | 49        | 0.79%   |
| G.Skill             | 45        | 0.72%   |
| Apacer              | 36        | 0.58%   |
| Patriot             | 33        | 0.53%   |
| Nanya Technology    | 28        | 0.45%   |
| Kllisre             | 27        | 0.43%   |
| Atermiter           | 25        | 0.4%    |
| Avant               | 18        | 0.29%   |
| Ramaxel Technology  | 15        | 0.24%   |
| PUSKILL             | 15        | 0.24%   |
| Kreton              | 14        | 0.23%   |
| HT Micron           | 14        | 0.23%   |
| Smart Modular       | 12        | 0.19%   |
| HBS                 | 12        | 0.19%   |
| RZX                 | 10        | 0.16%   |
| GeIL                | 10        | 0.16%   |
| CSX                 | 10        | 0.16%   |
| Unknown (0x0B5E)    | 9         | 0.14%   |
| Transcend           | 9         | 0.14%   |
| Kingmax             | 9         | 0.14%   |
| Juhor               | 9         | 0.14%   |
| Asgard              | 9         | 0.14%   |
| Walton Chaintech    | 7         | 0.11%   |
| Hewlett-Packard     | 7         | 0.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                               | Computers | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Unknown                                                             | 93        | 1.37%   |
| Smart Brazil RAM SMS4TDC3C0K0446SCG 4GB SODIMM DDR4 2667MT/s        | 87        | 1.28%   |
| Smart RAM SH564128FJ8NWRNSQG 4GB SODIMM DDR3 1600MT/s               | 61        | 0.9%    |
| Smart RAM SH564568FH8NZPHSCR 2GB SODIMM DDR3 1334MT/s               | 59        | 0.87%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                   | 53        | 0.78%   |
| Smart RAM SH564128FH8NZPHSCG 4GB SODIMM DDR3 1334MT/s               | 51        | 0.75%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s               | 50        | 0.73%   |
| Smart RAM SH564128FJ8NWRNSQR 4GB SODIMM DDR3 1600MT/s               | 47        | 0.69%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s               | 47        | 0.69%   |
| Smart RAM SF4641G8CK8IEHLSBG 8GB SODIMM DDR4 2667MT/s               | 46        | 0.68%   |
| Unknown RAM Module 2GB DIMM SDRAM                                   | 43        | 0.63%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 43        | 0.63%   |
| Smart RAM SH564128FH8NZPHSCR 4GB SODIMM DDR3 1333MT/s               | 39        | 0.57%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                           | 36        | 0.53%   |
| Smart RAM SMS4TDC3C0K0446SCG 4096MB SODIMM DDR4 2667MT/s            | 34        | 0.5%    |
| Samsung RAM M471B5773CHS-CH9 2048MB SODIMM DDR3 4199MT/s            | 34        | 0.5%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                   | 34        | 0.5%    |
| Kingston RAM KHX1600C10D3/8G 8GB DIMM DDR3 1648MT/s                 | 33        | 0.49%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s                        | 31        | 0.46%   |
| Unknown RAM Module 2048MB DIMM SDRAM                                | 29        | 0.43%   |
| Smart RAM SH564128FJ8NZRNSDG 4GB SODIMM DDR3 1600MT/s               | 29        | 0.43%   |
| A-DATA RAM AM1P26KC8T1-BAAS 8GB SODIMM DDR4 2667MT/s                | 29        | 0.43%   |
| Smart RAM SH5641G8FJ8NWRNSQG 8GB SODIMM DDR3 1600MT/s               | 28        | 0.41%   |
| Smart RAM SH564128FJ8NZRNSDR 4GB SODIMM DDR3 1600MT/s               | 28        | 0.41%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                             | 26        | 0.38%   |
| Smart RAM SH564568FH8NZPHSCG 2GB SODIMM DDR3 1333MT/s               | 25        | 0.37%   |
| Unknown RAM Module 4096MB SODIMM DDR3                               | 24        | 0.35%   |
| Teikon RAM TMA81GS6AFR8N-UHSC 8GB SODIMM DDR4 2400MT/s              | 24        | 0.35%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s               | 24        | 0.35%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s               | 24        | 0.35%   |
| Smart RAM SMS4WEC8C1K0446FCG 8GB SODIMM DDR4 3200MT/s               | 23        | 0.34%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s               | 23        | 0.34%   |
| A-DATA RAM DDR4 3000 16GB DIMM DDR4 3600MT/s                        | 23        | 0.34%   |
| A-DATA RAM AM1P24HC4U1-BBGS 4GB SODIMM DDR4 2400MT/s                | 23        | 0.34%   |
| A-DATA RAM AE4S240038G17-BHYA 8GB SODIMM DDR4 2400MT/s              | 23        | 0.34%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                            | 22        | 0.32%   |
| Unknown RAM Module 2GB DIMM DDR2                                    | 21        | 0.31%   |
| Teikon RAM TMT451S6BFR8A-PBHJ 4GB SODIMM DDR3 1600MT/s              | 21        | 0.31%   |
| Unknown RAM Module 4GB SODIMM DDR3 1333MT/s                         | 20        | 0.29%   |
| Unknown RAM Module 4GB DIMM SDRAM                                   | 20        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR3         | 2181      | 41.53%  |
| DDR4         | 2001      | 38.11%  |
| DDR2         | 336       | 6.4%    |
| Unknown      | 231       | 4.4%    |
| SDRAM        | 219       | 4.17%   |
| LPDDR4       | 113       | 2.15%   |
| DDR          | 48        | 0.91%   |
| DDR5         | 42        | 0.8%    |
| LPDDR3       | 38        | 0.72%   |
| DRAM         | 24        | 0.46%   |
| LPDDR5       | 15        | 0.29%   |
| RAM          | 2         | 0.04%   |
| DDR2 FB-DIMM | 1         | 0.02%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2846      | 54.48%  |
| DIMM         | 2200      | 42.11%  |
| Row Of Chips | 149       | 2.85%   |
| Unknown      | 19        | 0.36%   |
| RIMM         | 4         | 0.08%   |
| FB-DIMM      | 4         | 0.08%   |
| Chip         | 2         | 0.04%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 2083      | 35.04%  |
| 8192  | 1779      | 29.92%  |
| 2048  | 1133      | 19.06%  |
| 16384 | 583       | 9.81%   |
| 1024  | 180       | 3.03%   |
| 32768 | 163       | 2.74%   |
| 512   | 18        | 0.3%    |
| 256   | 3         | 0.05%   |
| 15616 | 1         | 0.02%   |
| 1536  | 1         | 0.02%   |
| 16    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1267      | 21.53%  |
| 2667    | 746       | 12.67%  |
| 1333    | 713       | 12.11%  |
| 2400    | 521       | 8.85%   |
| 3200    | 435       | 7.39%   |
| Unknown | 296       | 5.03%   |
| 1334    | 280       | 4.76%   |
| 800     | 188       | 3.19%   |
| 2133    | 184       | 3.13%   |
| 667     | 172       | 2.92%   |
| 3600    | 93        | 1.58%   |
| 1066    | 85        | 1.44%   |
| 3400    | 71        | 1.21%   |
| 1067    | 65        | 1.1%    |
| 3000    | 61        | 1.04%   |
| 1867    | 55        | 0.93%   |
| 4199    | 45        | 0.76%   |
| 4267    | 44        | 0.75%   |
| 1866    | 40        | 0.68%   |
| 533     | 40        | 0.68%   |
| 3466    | 39        | 0.66%   |
| 2666    | 35        | 0.59%   |
| 4800    | 31        | 0.53%   |
| 2933    | 30        | 0.51%   |
| 3733    | 29        | 0.49%   |
| 975     | 25        | 0.42%   |
| 400     | 24        | 0.41%   |
| 3800    | 23        | 0.39%   |
| 2048    | 23        | 0.39%   |
| 3066    | 22        | 0.37%   |
| 3151    | 17        | 0.29%   |
| 333     | 17        | 0.29%   |
| 3266    | 14        | 0.24%   |
| 2800    | 14        | 0.24%   |
| 6400    | 12        | 0.2%    |
| 3334    | 10        | 0.17%   |
| 1800    | 8         | 0.14%   |
| 8400    | 7         | 0.12%   |
| 3333    | 7         | 0.12%   |
| 3933    | 6         | 0.1%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 128       | 42.24%  |
| Seiko Epson           | 84        | 27.72%  |
| Samsung Electronics   | 29        | 9.57%   |
| Canon                 | 25        | 8.25%   |
| Brother Industries    | 23        | 7.59%   |
| Lexmark International | 3         | 0.99%   |
| QinHeng Electronics   | 2         | 0.66%   |
| Apple                 | 2         | 0.66%   |
| Xerox                 | 1         | 0.33%   |
| Ricoh                 | 1         | 0.33%   |
| Prolific Technology   | 1         | 0.33%   |
| Pantum                | 1         | 0.33%   |
| Oki Data              | 1         | 0.33%   |
| MIIIW                 | 1         | 0.33%   |
| ARGOX                 | 1         | 0.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                        | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Seiko Epson L3150 Series                     | 15        | 4.89%   |
| Seiko Epson ET-2600 Series                   | 11        | 3.58%   |
| Seiko Epson L355 Series                      | 9         | 2.93%   |
| HP Ink Tank Wireless 410 series              | 9         | 2.93%   |
| HP DeskJet 2700 series                       | 9         | 2.93%   |
| HP DeskJet 2130 series                       | 9         | 2.93%   |
| Seiko Epson L365 Series                      | 8         | 2.61%   |
| Canon G3010 series                           | 8         | 2.61%   |
| HP Deskjet 3050 J610 series                  | 7         | 2.28%   |
| HP Deskjet 2540 series                       | 7         | 2.28%   |
| Samsung M2070 Series                         | 6         | 1.95%   |
| HP LaserJet 1020                             | 6         | 1.95%   |
| HP DeskJet F4100 Printer series              | 6         | 1.95%   |
| Samsung SCX-4200 series                      | 5         | 1.63%   |
| Samsung M2020 Series                         | 5         | 1.63%   |
| HP LaserJet Professional P1102w              | 5         | 1.63%   |
| HP LaserJet P1005                            | 5         | 1.63%   |
| HP DeskJet 3630 series                       | 5         | 1.63%   |
| HP DeskJet 2600 series                       | 5         | 1.63%   |
| HP Deskjet 2050 J510                         | 5         | 1.63%   |
| Seiko Epson L360 Series                      | 4         | 1.3%    |
| HP Deskjet F4400 series                      | 4         | 1.3%    |
| HP DeskJet F4200 series                      | 4         | 1.3%    |
| Seiko Epson XP-240 Series                    | 3         | 0.98%   |
| Seiko Epson ME 320/330 Series [Stylus SX125] | 3         | 0.98%   |
| Seiko Epson L375 Series                      | 3         | 0.98%   |
| Seiko Epson L3250 Series                     | 3         | 0.98%   |
| Seiko Epson L3110 Series                     | 3         | 0.98%   |
| Seiko Epson L210 Series                      | 3         | 0.98%   |
| Samsung SCX-3200 Series                      | 3         | 0.98%   |
| HP LaserJet 1018                             | 3         | 0.98%   |
| Canon PIXMA MG3600 Series                    | 3         | 0.98%   |
| Brother HL-1200 series                       | 3         | 0.98%   |
| Seiko Epson USB2.0 Printer                   | 2         | 0.65%   |
| Seiko Epson L6160 Series                     | 2         | 0.65%   |
| Seiko Epson L382 Series                      | 2         | 0.65%   |
| Seiko Epson L120 Series                      | 2         | 0.65%   |
| Seiko Epson ET-2700 Series                   | 2         | 0.65%   |
| Samsung SCX-3400 Series                      | 2         | 0.65%   |
| Samsung ML-216x Series Laser Printer         | 2         | 0.65%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 9         | 42.86%  |
| Hewlett-Packard | 8         | 38.1%   |
| Seiko Epson     | 2         | 9.52%   |
| Plustek         | 1         | 4.76%   |
| Mustek Systems  | 1         | 4.76%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| HP ScanJet 2400c                                        | 5         | 23.81%  |
| Canon CanoScan LIDE 25                                  | 4         | 19.05%  |
| Canon CanoScan LiDE 110                                 | 2         | 9.52%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo] | 1         | 4.76%   |
| Seiko Epson GT-F720 [GT-S620/Perfection V30/V300 Photo] | 1         | 4.76%   |
| Plustek 1200dpi USB Scanner                             | 1         | 4.76%   |
| Mustek Systems ScanExpress 1200 UB                      | 1         | 4.76%   |
| HP ScanJet G4050                                        | 1         | 4.76%   |
| HP ScanJet 3800c                                        | 1         | 4.76%   |
| HP Scanjet 200                                          | 1         | 4.76%   |
| Canon CanoScan N670U/N676U/LiDE 20                      | 1         | 4.76%   |
| Canon CanoScan N1240U/LiDE 30                           | 1         | 4.76%   |
| Canon CanoScan LiDE 210                                 | 1         | 4.76%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1632      | 18.95%  |
| Microdia                               | 998       | 11.59%  |
| Realtek Semiconductor                  | 790       | 9.17%   |
| Quanta                                 | 681       | 7.91%   |
| Silicon Motion                         | 616       | 7.15%   |
| Sunplus Innovation Technology          | 580       | 6.73%   |
| Bison Electronics                      | 412       | 4.78%   |
| IMC Networks                           | 370       | 4.3%    |
| Logitech                               | 332       | 3.85%   |
| Suyin                                  | 308       | 3.58%   |
| Syntek                                 | 258       | 3%      |
| Alcor Micro                            | 165       | 1.92%   |
| Apple                                  | 146       | 1.69%   |
| Acer                                   | 134       | 1.56%   |
| Samsung Electronics                    | 107       | 1.24%   |
| Cheng Uei Precision Industry (Foxlink) | 102       | 1.18%   |
| Generalplus Technology                 | 84        | 0.98%   |
| Z-Star Microelectronics                | 70        | 0.81%   |
| Microsoft                              | 64        | 0.74%   |
| Sonix Technology                       | 62        | 0.72%   |
| Ricoh                                  | 54        | 0.63%   |
| ALi                                    | 50        | 0.58%   |
| SunplusIT                              | 40        | 0.46%   |
| GEMBIRD                                | 30        | 0.35%   |
| Aveo Technology                        | 28        | 0.33%   |
| Lite-On Technology                     | 26        | 0.3%    |
| Unknown                                | 25        | 0.29%   |
| OmniVision Technologies                | 25        | 0.29%   |
| Importek                               | 25        | 0.29%   |
| USB Camera                             | 24        | 0.28%   |
| Jieli Technology                       | 24        | 0.28%   |
| Pixart Imaging                         | 22        | 0.26%   |
| LG Electronics                         | 20        | 0.23%   |
| Y Media                                | 19        | 0.22%   |
| Cubeternet                             | 19        | 0.22%   |
| Lenovo                                 | 18        | 0.21%   |
| Luxvisions Innotech Limited            | 16        | 0.19%   |
| Genesys Logic                          | 14        | 0.16%   |
| Sunplus Technology                     | 12        | 0.14%   |
| Shenzhen Kingcome Optoelectronic       | 11        | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                     | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Microdia Integrated_Webcam_HD             | 377       | 4.37%   |
| Realtek Integrated_Webcam_HD              | 350       | 4.06%   |
| Quanta HD User Facing                     | 297       | 3.44%   |
| Chicony HD WebCam                         | 250       | 2.9%    |
| Chicony HD User Facing                    | 238       | 2.76%   |
| Silicon Motion Web Camera                 | 229       | 2.65%   |
| Sunplus Integrated_Webcam_HD              | 227       | 2.63%   |
| Quanta VGA WebCam                         | 189       | 2.19%   |
| Chicony Integrated Camera                 | 179       | 2.07%   |
| Chicony USB 2.0 Camera                    | 166       | 1.92%   |
| Syntek Integrated Camera                  | 153       | 1.77%   |
| Chicony VGA WebCam                        | 151       | 1.75%   |
| Realtek Integrated Webcam                 | 125       | 1.45%   |
| Logitech Webcam C270                      | 116       | 1.34%   |
| Sunplus HD WebCam                         | 110       | 1.27%   |
| Quanta HD Webcam                          | 109       | 1.26%   |
| Microdia Laptop_Integrated_Webcam_HD      | 107       | 1.24%   |
| Samsung Galaxy series, misc. (MTP mode)   | 106       | 1.23%   |
| Alcor Micro USB 2.0 Camera                | 98        | 1.14%   |
| Realtek USB Camera                        | 84        | 0.97%   |
| IMC Networks Integrated Camera            | 77        | 0.89%   |
| Bison EasyCamera                          | 76        | 0.88%   |
| Logitech HD Pro Webcam C920               | 69        | 0.8%    |
| Bison Lenovo EasyCamera                   | 67        | 0.78%   |
| Microdia Dell Laptop Integrated Webcam HD | 65        | 0.75%   |
| Generalplus GENERAL WEBCAM                | 58        | 0.67%   |
| Sonix USB2.0 HD UVC WebCam                | 57        | 0.66%   |
| IMC Networks USB2.0 VGA UVC WebCam        | 57        | 0.66%   |
| Silicon Motion WebCam SC-10HDD12636N      | 55        | 0.64%   |
| Microdia Integrated Webcam HD             | 54        | 0.63%   |
| IMC Networks USB2.0 HD UVC WebCam         | 53        | 0.61%   |
| Acer BisonCam, NB Pro                     | 53        | 0.61%   |
| Bison VGA WebCam                          | 50        | 0.58%   |
| Bison Integrated Camera                   | 50        | 0.58%   |
| Chicony EasyCamera                        | 49        | 0.57%   |
| Silicon Motion WebCam SCB-1100N           | 47        | 0.54%   |
| Microdia USB 2.0 Camera                   | 47        | 0.54%   |
| Silicon Motion WebCam SC-0311139N         | 46        | 0.53%   |
| Bison HD Webcam                           | 46        | 0.53%   |
| Suyin Integrated_Webcam_HD                | 45        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 318       | 45.62%  |
| Synaptics                  | 91        | 13.06%  |
| Shenzhen Goodix Technology | 79        | 11.33%  |
| Upek                       | 65        | 9.33%   |
| AuthenTec                  | 64        | 9.18%   |
| LighTuning Technology      | 35        | 5.02%   |
| Samsung Electronics        | 20        | 2.87%   |
| Elan Microelectronics      | 12        | 1.72%   |
| STMicroelectronics         | 4         | 0.57%   |
| Futronic Technology        | 2         | 0.29%   |
| Focal-systems.Corp         | 2         | 0.29%   |
| Dell                       | 2         | 0.29%   |
| Next Biometrics            | 1         | 0.14%   |
| HOLTEK                     | 1         | 0.14%   |
| DigitalPersona             | 1         | 0.14%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Validity Sensors VFS5011 Fingerprint Reader            | 120       | 17.22%  |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor | 55        | 7.89%   |
| Shenzhen Goodix Fingerprint Reader                     | 47        | 6.74%   |
| Validity Sensors VFS495 Fingerprint Reader             | 30        | 4.3%    |
| Synaptics Metallica MOH Touch Fingerprint Reader       | 30        | 4.3%    |
| Validity Sensors VFS 5011 fingerprint sensor           | 27        | 3.87%   |
| Validity Sensors VFS471 Fingerprint Reader             | 26        | 3.73%   |
| LighTuning ES603 Swipe Fingerprint Sensor              | 26        | 3.73%   |
| Validity Sensors Fingerprint scanner                   | 24        | 3.44%   |
| Shenzhen Goodix  FingerPrint Device                    | 23        | 3.3%    |
| Validity Sensors VFS301 Fingerprint Reader             | 20        | 2.87%   |
| Synaptics  WBDI                                        | 20        | 2.87%   |
| Samsung Fingerprint Device                             | 20        | 2.87%   |
| AuthenTec AES1660 Fingerprint Sensor                   | 20        | 2.87%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader      | 18        | 2.58%   |
| Validity Sensors VFS101 Fingerprint Reader             | 14        | 2.01%   |
| AuthenTec AES2810                                      | 14        | 2.01%   |
| AuthenTec AES2501 Fingerprint Sensor                   | 14        | 2.01%   |
| Validity Sensors VFS451 Fingerprint Reader             | 13        | 1.87%   |
| Validity Sensors VFS491                                | 12        | 1.72%   |
| Elan ELAN:Fingerprint                                  | 12        | 1.72%   |
| AuthenTec Fingerprint Sensor                           | 12        | 1.72%   |
| Validity Sensors VFS300 Fingerprint Reader             | 10        | 1.43%   |
| Validity Sensors Swipe Fingerprint Sensor              | 9         | 1.29%   |
| Upek TCS5B Fingerprint sensor                          | 9         | 1.29%   |
| Synaptics Metallica MIS Touch Fingerprint Reader       | 9         | 1.29%   |
| Shenzhen Goodix FingerPrint                            | 9         | 1.29%   |
| Validity Sensors Synaptics WBDI                        | 6         | 0.86%   |
| Synaptics WBDI                                         | 6         | 0.86%   |
| LighTuning EgisTec Touch Fingerprint Sensor            | 6         | 0.86%   |
| STMicroelectronics Fingerprint Reader                  | 4         | 0.57%   |
| AuthenTec AES1600                                      | 4         | 0.57%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor      | 3         | 0.43%   |
| Synaptics Fingerprint reader [HP G6]                   | 3         | 0.43%   |
| LighTuning Fingerprint Sensor                          | 3         | 0.43%   |
| Futronic FS81 Fingerprint Scanner Module               | 2         | 0.29%   |
| Focal-systems.Corp FT9201Fingerprint.Ì              | 2         | 0.29%   |
| Dell MS819 Wired Mouse With Fingerprint Reader         | 2         | 0.29%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor      | 1         | 0.14%   |
| Validity Sensors VFS Fingerprint sensor                | 1         | 0.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Broadcom                          | 101       | 45.09%  |
| Alcor Micro                       | 30        | 13.39%  |
| Gemalto (was Gemplus)             | 19        | 8.48%   |
| Giesecke & Devrient               | 16        | 7.14%   |
| Lenovo                            | 15        | 6.7%    |
| Upek                              | 10        | 4.46%   |
| Aladdin Knowledge Systems         | 8         | 3.57%   |
| Watchdata                         | 7         | 3.13%   |
| SCM Microsystems                  | 4         | 1.79%   |
| OmniKey                           | 3         | 1.34%   |
| O2 Micro                          | 3         | 1.34%   |
| Chicony Electronics               | 3         | 1.34%   |
| Castles Technology                | 2         | 0.89%   |
| VASCO Data Security International | 1         | 0.45%   |
| Realtek Semiconductor             | 1         | 0.45%   |
| Advanced Card Systems             | 1         | 0.45%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom 58200                                                               | 30        | 13.39%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 30        | 13.39%  |
| Broadcom 5880                                                                | 26        | 11.61%  |
| Broadcom BCM5880 Secure Applications Processor                               | 25        | 11.16%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 8.93%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 18        | 8.04%   |
| Lenovo Integrated Smart Card Reader                                          | 15        | 6.7%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 10        | 4.46%   |
| Giesecke & Devrient StarSign CUT                                             | 9         | 4.02%   |
| Aladdin Knowledge Systems Token JC                                           | 8         | 3.57%   |
| Watchdata USB Key                                                            | 7         | 3.13%   |
| Giesecke & Devrient StarSign CUT S                                           | 7         | 3.13%   |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 3         | 1.34%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 2         | 0.89%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 2         | 0.89%   |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 0.89%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 2         | 0.89%   |
| Castles Technology EZCCID Smart Card Reader                                  | 2         | 0.89%   |
| VASCO Data Security International Digipass 905 SmartCard Reader              | 1         | 0.45%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.45%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.45%   |
| O2 Micro Oz776 SmartCard Reader                                              | 1         | 0.45%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.45%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 0.45%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 11230     | 79.13%  |
| 1     | 2555      | 18%     |
| 2     | 319       | 2.25%   |
| 3     | 56        | 0.39%   |
| 4     | 20        | 0.14%   |
| 7     | 4         | 0.03%   |
| 5     | 3         | 0.02%   |
| 8     | 2         | 0.01%   |
| 6     | 2         | 0.01%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1044      | 31.21%  |
| Fingerprint reader       | 692       | 20.69%  |
| Net/wireless             | 435       | 13%     |
| Multimedia controller    | 306       | 9.15%   |
| Chipcard                 | 187       | 5.59%   |
| Communication controller | 135       | 4.04%   |
| Bluetooth                | 109       | 3.26%   |
| Camera                   | 95        | 2.84%   |
| Unassigned class         | 74        | 2.21%   |
| Sound                    | 73        | 2.18%   |
| Storage                  | 49        | 1.46%   |
| Net/ethernet             | 43        | 1.29%   |
| Modem                    | 24        | 0.72%   |
| Flash memory             | 23        | 0.69%   |
| Card reader              | 14        | 0.42%   |
| Network                  | 12        | 0.36%   |
| Storage/raid             | 8         | 0.24%   |
| Storage/ide              | 8         | 0.24%   |
| Firewire controller      | 6         | 0.18%   |
| Storage/nvme             | 3         | 0.09%   |
| Wireless                 | 1         | 0.03%   |
| Video                    | 1         | 0.03%   |
| Unclassified device      | 1         | 0.03%   |
| Storage/ata              | 1         | 0.03%   |
| Dvb card                 | 1         | 0.03%   |

