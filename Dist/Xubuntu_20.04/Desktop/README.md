Xubuntu 20.04 - Tested Hardware & Statistics (Desktops)
-------------------------------------------------------

A project to collect tested hardware configurations for Xubuntu 20.04.

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

Total: 1195

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| ASUSTek       | H81M-A                      | [9ed3a001c9](https://linux-hardware.org/?probe=9ed3a001c9) | Nov 23, 2022 |
| ASUSTek       | PRIME X570-PRO              | [7399298a0f](https://linux-hardware.org/?probe=7399298a0f) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [a5cfd24a43](https://linux-hardware.org/?probe=a5cfd24a43) | Nov 18, 2022 |
| Gigabyte      | H97-HD3                     | [8a2f5e3f03](https://linux-hardware.org/?probe=8a2f5e3f03) | Nov 14, 2022 |
| ASRock        | Z68 Extreme3 Gen3           | [01cb4ff120](https://linux-hardware.org/?probe=01cb4ff120) | Nov 10, 2022 |
| ASUSTek       | B150M-C                     | [d2dd725b2e](https://linux-hardware.org/?probe=d2dd725b2e) | Nov 09, 2022 |
| ASUSTek       | VM40B                       | [5736f2e2ae](https://linux-hardware.org/?probe=5736f2e2ae) | Nov 08, 2022 |
| MSI           | CSM-H87M-G43                | [43ffdafb80](https://linux-hardware.org/?probe=43ffdafb80) | Nov 06, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [98a3c2457d](https://linux-hardware.org/?probe=98a3c2457d) | Nov 05, 2022 |
| Gigabyte      | Z390 AORUS ELITE-CF         | [1cf71a1b5c](https://linux-hardware.org/?probe=1cf71a1b5c) | Nov 05, 2022 |
| eMachines     | EL1358G                     | [48d6ba4c24](https://linux-hardware.org/?probe=48d6ba4c24) | Nov 03, 2022 |
| eMachines     | EL1358G                     | [1acbe713b6](https://linux-hardware.org/?probe=1acbe713b6) | Nov 03, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [7a29190887](https://linux-hardware.org/?probe=7a29190887) | Nov 01, 2022 |
| BCM           | MX110HD                     | [60c3eb0c5c](https://linux-hardware.org/?probe=60c3eb0c5c) | Nov 01, 2022 |
| ASUSTek       | P9X79                       | [3af3091881](https://linux-hardware.org/?probe=3af3091881) | Oct 31, 2022 |
| Dell          | 0GY6Y8 A03                  | [1c95e9ba40](https://linux-hardware.org/?probe=1c95e9ba40) | Oct 28, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [46d64e9947](https://linux-hardware.org/?probe=46d64e9947) | Oct 25, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [4ef2a348fc](https://linux-hardware.org/?probe=4ef2a348fc) | Oct 25, 2022 |
| ASRock        | B450M Pro4                  | [23a298a9a5](https://linux-hardware.org/?probe=23a298a9a5) | Oct 23, 2022 |
| ASUSTek       | PRIME H310M-R R2.0          | [d575515de3](https://linux-hardware.org/?probe=d575515de3) | Oct 20, 2022 |
| MSI           | A68HM-E33 V2                | [16f5eb4d25](https://linux-hardware.org/?probe=16f5eb4d25) | Oct 12, 2022 |
| MSI           | A68HM-E33 V2                | [1001ccbbaf](https://linux-hardware.org/?probe=1001ccbbaf) | Sep 30, 2022 |
| ASUSTek       | B85M-G                      | [ba607b91e0](https://linux-hardware.org/?probe=ba607b91e0) | Sep 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [41cc3cdcfd](https://linux-hardware.org/?probe=41cc3cdcfd) | Sep 26, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [d6924eb78d](https://linux-hardware.org/?probe=d6924eb78d) | Sep 26, 2022 |
| MSI           | Z77A-G43                    | [4b91f7a270](https://linux-hardware.org/?probe=4b91f7a270) | Sep 19, 2022 |
| Gigabyte      | H410M S2H                   | [d852f09d43](https://linux-hardware.org/?probe=d852f09d43) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [a0bdfffa04](https://linux-hardware.org/?probe=a0bdfffa04) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [196e6b048b](https://linux-hardware.org/?probe=196e6b048b) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [8e95a850da](https://linux-hardware.org/?probe=8e95a850da) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [499d354033](https://linux-hardware.org/?probe=499d354033) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [a830a7b6e5](https://linux-hardware.org/?probe=a830a7b6e5) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [19ba71f923](https://linux-hardware.org/?probe=19ba71f923) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [ad888e4455](https://linux-hardware.org/?probe=ad888e4455) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [d35bf4c513](https://linux-hardware.org/?probe=d35bf4c513) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [dce51bb6d6](https://linux-hardware.org/?probe=dce51bb6d6) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [3bc232858d](https://linux-hardware.org/?probe=3bc232858d) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [ca79460771](https://linux-hardware.org/?probe=ca79460771) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [1e24243624](https://linux-hardware.org/?probe=1e24243624) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [b0625e01e3](https://linux-hardware.org/?probe=b0625e01e3) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [f97cd53683](https://linux-hardware.org/?probe=f97cd53683) | Sep 15, 2022 |
| Gigabyte      | H410M S2H                   | [cd3fc03204](https://linux-hardware.org/?probe=cd3fc03204) | Sep 15, 2022 |
| Gigabyte      | H510M S2H                   | [f004b06a17](https://linux-hardware.org/?probe=f004b06a17) | Sep 12, 2022 |
| MSI           | Z77A-G43                    | [d0e5863756](https://linux-hardware.org/?probe=d0e5863756) | Sep 10, 2022 |
| Dell          | 0T10XW A02                  | [33faaf5341](https://linux-hardware.org/?probe=33faaf5341) | Sep 10, 2022 |
| Dell          | 0R092H                      | [a22af2bad5](https://linux-hardware.org/?probe=a22af2bad5) | Sep 09, 2022 |
| ASRock        | Q1900-ITX                   | [738bae7e52](https://linux-hardware.org/?probe=738bae7e52) | Sep 08, 2022 |
| ASUSTek       | M2N-E                       | [2737c0fd67](https://linux-hardware.org/?probe=2737c0fd67) | Sep 08, 2022 |
| MSI           | MPG X570 GAMING EDGE WIF... | [f714986404](https://linux-hardware.org/?probe=f714986404) | Sep 08, 2022 |
| MSI           | MS-7387                     | [1f49477abf](https://linux-hardware.org/?probe=1f49477abf) | Sep 06, 2022 |
| Dell          | 0NV0M7 A02                  | [23024b776e](https://linux-hardware.org/?probe=23024b776e) | Sep 06, 2022 |
| ASUSTek       | M4A78T-E                    | [6c0537c32c](https://linux-hardware.org/?probe=6c0537c32c) | Sep 05, 2022 |
| ECS           | G31T-M9                     | [c3212ee5a3](https://linux-hardware.org/?probe=c3212ee5a3) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [673b33ac0c](https://linux-hardware.org/?probe=673b33ac0c) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [18a2d69632](https://linux-hardware.org/?probe=18a2d69632) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [965107cf86](https://linux-hardware.org/?probe=965107cf86) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [d8f5734dd8](https://linux-hardware.org/?probe=d8f5734dd8) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [b2f37a3080](https://linux-hardware.org/?probe=b2f37a3080) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [91857942dd](https://linux-hardware.org/?probe=91857942dd) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [940fb9c208](https://linux-hardware.org/?probe=940fb9c208) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [10315fa577](https://linux-hardware.org/?probe=10315fa577) | Sep 02, 2022 |
| ECS           | G31T-M9                     | [aedc37e8e4](https://linux-hardware.org/?probe=aedc37e8e4) | Sep 02, 2022 |
| Medion        | H110H4-EM                   | [9f80ee3a09](https://linux-hardware.org/?probe=9f80ee3a09) | Sep 01, 2022 |
| ASUSTek       | TUF Gaming B450-PLUS II     | [efc46d8d23](https://linux-hardware.org/?probe=efc46d8d23) | Sep 01, 2022 |
| DNI           | SNDTP-1513N 5508015890      | [9570ee789c](https://linux-hardware.org/?probe=9570ee789c) | Aug 30, 2022 |
| Gigabyte      | H97M-D3H                    | [a8100fcf41](https://linux-hardware.org/?probe=a8100fcf41) | Aug 29, 2022 |
| Gigabyte      | H97M-D3H                    | [f8f42b0857](https://linux-hardware.org/?probe=f8f42b0857) | Aug 29, 2022 |
| Intel         | H61                         | [c829101789](https://linux-hardware.org/?probe=c829101789) | Aug 27, 2022 |
| HP            | 844C                        | [b56856200e](https://linux-hardware.org/?probe=b56856200e) | Aug 23, 2022 |
| Gigabyte      | Z97X-UD3H-CF                | [38fd87d37c](https://linux-hardware.org/?probe=38fd87d37c) | Aug 21, 2022 |
| ASUSTek       | Z10PE-D16 WS                | [d9ff119ebe](https://linux-hardware.org/?probe=d9ff119ebe) | Aug 21, 2022 |
| MSI           | X370 KRAIT GAMING           | [ea80c11a16](https://linux-hardware.org/?probe=ea80c11a16) | Aug 20, 2022 |
| Dell          | 07T4MC A06                  | [d6c22de1e9](https://linux-hardware.org/?probe=d6c22de1e9) | Aug 18, 2022 |
| Dell          | 0RY007                      | [a863b6949c](https://linux-hardware.org/?probe=a863b6949c) | Aug 16, 2022 |
| ASUSTek       | Z10PE-D16 WS                | [ea40fd79f3](https://linux-hardware.org/?probe=ea40fd79f3) | Aug 15, 2022 |
| Dell          | 0RY007                      | [592206f3e1](https://linux-hardware.org/?probe=592206f3e1) | Aug 14, 2022 |
| Dell          | 0RY007                      | [05edd2876d](https://linux-hardware.org/?probe=05edd2876d) | Aug 12, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [23005caccd](https://linux-hardware.org/?probe=23005caccd) | Aug 11, 2022 |
| ASRock        | X58 Extreme3                | [81f68d4fc7](https://linux-hardware.org/?probe=81f68d4fc7) | Aug 10, 2022 |
| OEM_MB        | NARRA3                      | [4574011966](https://linux-hardware.org/?probe=4574011966) | Aug 09, 2022 |
| OEM_MB        | NARRA3                      | [8454f0f091](https://linux-hardware.org/?probe=8454f0f091) | Aug 09, 2022 |
| ASUSTek       | Z170 PRO GAMING             | [20a93d57e6](https://linux-hardware.org/?probe=20a93d57e6) | Aug 08, 2022 |
| Gigabyte      | F2A78M-HD2                  | [64b08b679f](https://linux-hardware.org/?probe=64b08b679f) | Aug 05, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [b81c8578b9](https://linux-hardware.org/?probe=b81c8578b9) | Aug 03, 2022 |
| ASUSTek       | P5P43TD PRO                 | [7325fb8135](https://linux-hardware.org/?probe=7325fb8135) | Jul 30, 2022 |
| Intel         | SHARKBAY                    | [bd5b812271](https://linux-hardware.org/?probe=bd5b812271) | Jul 29, 2022 |
| ASUSTek       | P5QL/EPU                    | [797c3b1dc2](https://linux-hardware.org/?probe=797c3b1dc2) | Jul 28, 2022 |
| ASUSTek       | M5A78L-M PLUS/USB3          | [611f1d79e3](https://linux-hardware.org/?probe=611f1d79e3) | Jul 26, 2022 |
| ASUSTek       | M51BC                       | [4d6af73032](https://linux-hardware.org/?probe=4d6af73032) | Jul 26, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e2cd5c8d4b](https://linux-hardware.org/?probe=e2cd5c8d4b) | Jul 20, 2022 |
| Dell          | 0F6X5P A00                  | [528f781464](https://linux-hardware.org/?probe=528f781464) | Jul 16, 2022 |
| HP            | 1496                        | [7797b2d6dd](https://linux-hardware.org/?probe=7797b2d6dd) | Jul 14, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [0c70241041](https://linux-hardware.org/?probe=0c70241041) | Jul 13, 2022 |
| ASUSTek       | P8Z77-M PRO                 | [4929b942aa](https://linux-hardware.org/?probe=4929b942aa) | Jul 12, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [6ed805403a](https://linux-hardware.org/?probe=6ed805403a) | Jul 10, 2022 |
| HP            | 158A                        | [e1bec79951](https://linux-hardware.org/?probe=e1bec79951) | Jul 10, 2022 |
| ASUSTek       | P5KC                        | [0ce9dd5cee](https://linux-hardware.org/?probe=0ce9dd5cee) | Jul 08, 2022 |
| Gigabyte      | G41M-ES2L                   | [d1aa8fe23d](https://linux-hardware.org/?probe=d1aa8fe23d) | Jul 05, 2022 |
| Dell          | 0GY6Y8 A03                  | [5703355b59](https://linux-hardware.org/?probe=5703355b59) | Jul 04, 2022 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [3633eb51d4](https://linux-hardware.org/?probe=3633eb51d4) | Jul 01, 2022 |
| ASUSTek       | PRIME H670-PLUS D4          | [8f90bed577](https://linux-hardware.org/?probe=8f90bed577) | Jul 01, 2022 |
| ASUSTek       | M5A97 R2.0                  | [05e7378ad8](https://linux-hardware.org/?probe=05e7378ad8) | Jun 29, 2022 |
| Dell          | 0WMJ54 A01                  | [a55837dc17](https://linux-hardware.org/?probe=a55837dc17) | Jun 29, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [87b9ce1db1](https://linux-hardware.org/?probe=87b9ce1db1) | Jun 28, 2022 |
| Dell          | 0HN7XN A00                  | [4562c09862](https://linux-hardware.org/?probe=4562c09862) | Jun 24, 2022 |
| Lenovo        | ThinkCentre A70 7844H9G     | [8cf9d783a3](https://linux-hardware.org/?probe=8cf9d783a3) | Jun 23, 2022 |
| ASUSTek       | P8Z77-V                     | [e32a4e0214](https://linux-hardware.org/?probe=e32a4e0214) | Jun 20, 2022 |
| ASUSTek       | M5A78L-M/USB3               | [515b063f08](https://linux-hardware.org/?probe=515b063f08) | Jun 18, 2022 |
| Lenovo        | ThinkCentre M71e 5033AR1    | [dd0f797f78](https://linux-hardware.org/?probe=dd0f797f78) | Jun 17, 2022 |
| ASUSTek       | P8H67-M LE                  | [f340c1d172](https://linux-hardware.org/?probe=f340c1d172) | Jun 17, 2022 |
| Intel         | DG33BU AAD79951-407         | [5df0f93da9](https://linux-hardware.org/?probe=5df0f93da9) | Jun 10, 2022 |
| Gigabyte      | H97-HD3                     | [7f48bb6a8a](https://linux-hardware.org/?probe=7f48bb6a8a) | Jun 08, 2022 |
| ASUSTek       | Maximus VII HERO            | [064492c64d](https://linux-hardware.org/?probe=064492c64d) | Jun 07, 2022 |
| ASRockRack    | ROMED8-2T                   | [3ee16e0227](https://linux-hardware.org/?probe=3ee16e0227) | Jun 07, 2022 |
| HP            | 3397                        | [775c6990fd](https://linux-hardware.org/?probe=775c6990fd) | Jun 03, 2022 |
| ASUSTek       | VM60                        | [57bea34864](https://linux-hardware.org/?probe=57bea34864) | May 30, 2022 |
| ASUSTek       | VM60                        | [bf1dcb2901](https://linux-hardware.org/?probe=bf1dcb2901) | May 30, 2022 |
| HP            | 2B29                        | [d2ab16d631](https://linux-hardware.org/?probe=d2ab16d631) | May 28, 2022 |
| Pegatron      | Benicia                     | [64aa376623](https://linux-hardware.org/?probe=64aa376623) | May 28, 2022 |
| Gigabyte      | 970A-DS3P                   | [23d890ffc6](https://linux-hardware.org/?probe=23d890ffc6) | May 23, 2022 |
| Acer          | Aspire G7750                | [28f3018ecc](https://linux-hardware.org/?probe=28f3018ecc) | May 18, 2022 |
| HP            | 158A                        | [dd67e1f8d2](https://linux-hardware.org/?probe=dd67e1f8d2) | May 17, 2022 |
| MSI           | AM1I                        | [f22b398676](https://linux-hardware.org/?probe=f22b398676) | May 15, 2022 |
| ECS           | Asterope                    | [a0c032d6f6](https://linux-hardware.org/?probe=a0c032d6f6) | May 14, 2022 |
| HP            | 82B4                        | [3a1723a2ee](https://linux-hardware.org/?probe=3a1723a2ee) | May 13, 2022 |
| ASUSTek       | P5KC                        | [bf7fdb19c8](https://linux-hardware.org/?probe=bf7fdb19c8) | May 12, 2022 |
| ASUSTek       | TUF Gaming B550-PLUS        | [bf4afe4481](https://linux-hardware.org/?probe=bf4afe4481) | May 12, 2022 |
| ASUSTek       | B150-PLUS                   | [eb2447cec6](https://linux-hardware.org/?probe=eb2447cec6) | May 11, 2022 |
| Gigabyte      | Z68A-D3-B3                  | [573e425cb6](https://linux-hardware.org/?probe=573e425cb6) | May 08, 2022 |
| HP            | 3397                        | [157ef440d8](https://linux-hardware.org/?probe=157ef440d8) | May 06, 2022 |
| Gigabyte      | G33M-DS2R                   | [d4dff7f002](https://linux-hardware.org/?probe=d4dff7f002) | May 04, 2022 |
| HP            | 158A                        | [cb763d6fab](https://linux-hardware.org/?probe=cb763d6fab) | May 04, 2022 |
| ASUSTek       | B150-PLUS                   | [e2f5eb0a39](https://linux-hardware.org/?probe=e2f5eb0a39) | May 02, 2022 |
| Unknown       | Intel X79                   | [95d09d79ca](https://linux-hardware.org/?probe=95d09d79ca) | Apr 29, 2022 |
| MSI           | Z390-A PRO                  | [6c64775a71](https://linux-hardware.org/?probe=6c64775a71) | Apr 24, 2022 |
| Gigabyte      | G33M-DS2R                   | [d2cd51f72d](https://linux-hardware.org/?probe=d2cd51f72d) | Apr 22, 2022 |
| Gigabyte      | H310M S2H x.x               | [bde3fa1f37](https://linux-hardware.org/?probe=bde3fa1f37) | Apr 22, 2022 |
| ASUSTek       | P8Z77-V                     | [40e958c5e1](https://linux-hardware.org/?probe=40e958c5e1) | Apr 19, 2022 |
| Dell          | 0WR7PY A01                  | [6fa162f829](https://linux-hardware.org/?probe=6fa162f829) | Apr 19, 2022 |
| HP            | 18E5                        | [211d35a24b](https://linux-hardware.org/?probe=211d35a24b) | Apr 17, 2022 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [d2559a2f19](https://linux-hardware.org/?probe=d2559a2f19) | Apr 17, 2022 |
| Apple         | Mac-F221BEC8                | [32bdb05198](https://linux-hardware.org/?probe=32bdb05198) | Apr 16, 2022 |
| HP            | 21B4 A01                    | [ddd3a601b3](https://linux-hardware.org/?probe=ddd3a601b3) | Apr 15, 2022 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [0e7314b7c9](https://linux-hardware.org/?probe=0e7314b7c9) | Apr 14, 2022 |
| MSI           | B450M MORTAR TITANIUM       | [6b11750e41](https://linux-hardware.org/?probe=6b11750e41) | Apr 13, 2022 |
| Acer          | Nitro N50-610               | [f3581a0d9d](https://linux-hardware.org/?probe=f3581a0d9d) | Apr 11, 2022 |
| Dell          | 0GY6Y8 A03                  | [1fb7e31b37](https://linux-hardware.org/?probe=1fb7e31b37) | Apr 10, 2022 |
| Gigabyte      | P55A-UD3                    | [9c6781cf90](https://linux-hardware.org/?probe=9c6781cf90) | Apr 10, 2022 |
| Dell          | 00V62H A01                  | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | P5G41T-M LX                 | [db8350499d](https://linux-hardware.org/?probe=db8350499d) | Apr 09, 2022 |
| MSI           | Z77A-G45 GAMING             | [622ecbb225](https://linux-hardware.org/?probe=622ecbb225) | Apr 09, 2022 |
| ASUSTek       | Maximus V EXTREME           | [3718d92d8a](https://linux-hardware.org/?probe=3718d92d8a) | Apr 08, 2022 |
| ASUSTek       | Maximus V EXTREME           | [f6d9a139de](https://linux-hardware.org/?probe=f6d9a139de) | Apr 08, 2022 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | [b43ffa5ce5](https://linux-hardware.org/?probe=b43ffa5ce5) | Apr 07, 2022 |
| ASUSTek       | M51BC                       | [e205187536](https://linux-hardware.org/?probe=e205187536) | Apr 07, 2022 |
| Apple         | Mac-F221BEC8                | [e092f62bc4](https://linux-hardware.org/?probe=e092f62bc4) | Apr 07, 2022 |
| Dell          | 0GY6Y8 A03                  | [a971341576](https://linux-hardware.org/?probe=a971341576) | Apr 05, 2022 |
| Dell          | OptiPlex 760                | [fa3babeea9](https://linux-hardware.org/?probe=fa3babeea9) | Apr 04, 2022 |
| Dell          | OptiPlex 760                | [ca42b9f058](https://linux-hardware.org/?probe=ca42b9f058) | Apr 03, 2022 |
| Gigabyte      | H97-D3H-CF                  | [e7b9989223](https://linux-hardware.org/?probe=e7b9989223) | Apr 02, 2022 |
| HP            | 18E5                        | [3474ce6335](https://linux-hardware.org/?probe=3474ce6335) | Apr 02, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [521a29d065](https://linux-hardware.org/?probe=521a29d065) | Mar 31, 2022 |
| Gigabyte      | E350N WIN8                  | [a56241f1a8](https://linux-hardware.org/?probe=a56241f1a8) | Mar 30, 2022 |
| Dell          | OptiPlex 760                | [1ecb9c1cf3](https://linux-hardware.org/?probe=1ecb9c1cf3) | Mar 29, 2022 |
| HP            | 21B4 A01                    | [963752fd6f](https://linux-hardware.org/?probe=963752fd6f) | Mar 28, 2022 |
| Unknown       | T3 MRD                      | [3e12cb02f8](https://linux-hardware.org/?probe=3e12cb02f8) | Mar 26, 2022 |
| Pegatron      | Benicia                     | [cb852b48fb](https://linux-hardware.org/?probe=cb852b48fb) | Mar 25, 2022 |
| ASUSTek       | PRIME H270M-PLUS            | [b27c4a7fe4](https://linux-hardware.org/?probe=b27c4a7fe4) | Mar 24, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [39dc1025e9](https://linux-hardware.org/?probe=39dc1025e9) | Mar 24, 2022 |
| Gigabyte      | H310M H x.x                 | [5adb4614c4](https://linux-hardware.org/?probe=5adb4614c4) | Mar 23, 2022 |
| Gigabyte      | H310M H x.x                 | [d277e5c6bc](https://linux-hardware.org/?probe=d277e5c6bc) | Mar 23, 2022 |
| Unknown       | T3 MRD                      | [3ec2149915](https://linux-hardware.org/?probe=3ec2149915) | Mar 23, 2022 |
| ASRock        | B550 Phantom Gaming 4       | [2f0764ceb3](https://linux-hardware.org/?probe=2f0764ceb3) | Mar 23, 2022 |
| ECS           | H87H3-M                     | [f15990212f](https://linux-hardware.org/?probe=f15990212f) | Mar 20, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [a226a58819](https://linux-hardware.org/?probe=a226a58819) | Mar 19, 2022 |
| ASUSTek       | A68HM-K                     | [4491d23e02](https://linux-hardware.org/?probe=4491d23e02) | Mar 16, 2022 |
| Acer          | Aspire X1920                | [2b3d54ec4a](https://linux-hardware.org/?probe=2b3d54ec4a) | Mar 14, 2022 |
| Gigabyte      | GA-MA78GM-S2H               | [dfef2d9492](https://linux-hardware.org/?probe=dfef2d9492) | Mar 13, 2022 |
| Dell          | 0RW199                      | [2298b1db14](https://linux-hardware.org/?probe=2298b1db14) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [54c4f70c98](https://linux-hardware.org/?probe=54c4f70c98) | Mar 08, 2022 |
| Acer          | TPDS05 R3700                | [48fc5c9d8b](https://linux-hardware.org/?probe=48fc5c9d8b) | Mar 08, 2022 |
| Dell          | 00V62H A00                  | [b9ca0e3bde](https://linux-hardware.org/?probe=b9ca0e3bde) | Mar 07, 2022 |
| Dell          | 00V62H A00                  | [6f5adc1704](https://linux-hardware.org/?probe=6f5adc1704) | Mar 07, 2022 |
| MSI           | B350 TOMAHAWK               | [2525f81966](https://linux-hardware.org/?probe=2525f81966) | Mar 06, 2022 |
| Gigabyte      | X570 AORUS MASTER           | [2623cf5090](https://linux-hardware.org/?probe=2623cf5090) | Feb 28, 2022 |
| Lenovo        | NO DPK                      | [a720d5bcaf](https://linux-hardware.org/?probe=a720d5bcaf) | Feb 27, 2022 |
| Dell          | 042P49 A02                  | [9efbb51081](https://linux-hardware.org/?probe=9efbb51081) | Feb 25, 2022 |
| Acer          | TPDS05 R3700                | [df877f2b77](https://linux-hardware.org/?probe=df877f2b77) | Feb 24, 2022 |
| MSI           | G41M-P25                    | [c8ebea2807](https://linux-hardware.org/?probe=c8ebea2807) | Feb 23, 2022 |
| Pegatron      | 2AB5                        | [f2ee067b5f](https://linux-hardware.org/?probe=f2ee067b5f) | Feb 23, 2022 |
| ASRock        | K10N78M                     | [f8a578c070](https://linux-hardware.org/?probe=f8a578c070) | Feb 21, 2022 |
| MSI           | A55M-P33                    | [d891e34be9](https://linux-hardware.org/?probe=d891e34be9) | Feb 20, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [8f1ce82db7](https://linux-hardware.org/?probe=8f1ce82db7) | Feb 15, 2022 |
| MSI           | MEG X570 ACE                | [4cb6628353](https://linux-hardware.org/?probe=4cb6628353) | Feb 14, 2022 |
| MSI           | MEG X570 ACE                | [43ac6b6d18](https://linux-hardware.org/?probe=43ac6b6d18) | Feb 14, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [6f11ea4988](https://linux-hardware.org/?probe=6f11ea4988) | Feb 14, 2022 |
| HP            | 3031h                       | [1475e006cd](https://linux-hardware.org/?probe=1475e006cd) | Feb 13, 2022 |
| ASUSTek       | PRIME H570M-PLUS            | [adc14fca30](https://linux-hardware.org/?probe=adc14fca30) | Feb 12, 2022 |
| Unknown       | Intel X79                   | [f0dd6357fe](https://linux-hardware.org/?probe=f0dd6357fe) | Feb 12, 2022 |
| ASUSTek       | M5A97 R2.0                  | [0301e86e1b](https://linux-hardware.org/?probe=0301e86e1b) | Feb 09, 2022 |
| Unknown       | Intel X79                   | [089b663f84](https://linux-hardware.org/?probe=089b663f84) | Feb 06, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | [1feae56050](https://linux-hardware.org/?probe=1feae56050) | Feb 06, 2022 |
| Gigabyte      | GA-870A-UD3                 | [e4b5396bf7](https://linux-hardware.org/?probe=e4b5396bf7) | Feb 04, 2022 |
| Dell          | 0XCR8D A01                  | [a68034b1e8](https://linux-hardware.org/?probe=a68034b1e8) | Feb 03, 2022 |
| Dell          | 051FJ8 A00                  | [da74a4ea79](https://linux-hardware.org/?probe=da74a4ea79) | Feb 01, 2022 |
| Fujitsu       | D3613-A1 S26361-D3613-A1    | [27b9e98a16](https://linux-hardware.org/?probe=27b9e98a16) | Feb 01, 2022 |
| ASRock        | M3A UCC                     | [8ca7699b4c](https://linux-hardware.org/?probe=8ca7699b4c) | Jan 28, 2022 |
| Pegatron      | Benicia                     | [8d1af3f3af](https://linux-hardware.org/?probe=8d1af3f3af) | Jan 27, 2022 |
| Unknown       | Unknown                     | [018c871f94](https://linux-hardware.org/?probe=018c871f94) | Jan 25, 2022 |
| ASUSTek       | H87M-PLUS                   | [986b65d292](https://linux-hardware.org/?probe=986b65d292) | Jan 21, 2022 |
| Lenovo        | Myrtle CRB SDK0J40700 WI... | [44b718700d](https://linux-hardware.org/?probe=44b718700d) | Jan 19, 2022 |
| Gigabyte      | MZBSWBP-00                  | [a8699a0a00](https://linux-hardware.org/?probe=a8699a0a00) | Jan 18, 2022 |
| ASUSTek       | P9X79                       | [2afe3ef5cc](https://linux-hardware.org/?probe=2afe3ef5cc) | Jan 16, 2022 |
| Dell          | 0PP150 A00                  | [554774c3c8](https://linux-hardware.org/?probe=554774c3c8) | Jan 16, 2022 |
| Gigabyte      | EX58-UD4P                   | [368d168909](https://linux-hardware.org/?probe=368d168909) | Jan 15, 2022 |
| Lenovo        | ThinkCentre A70 7099A5G     | [78902354bb](https://linux-hardware.org/?probe=78902354bb) | Jan 14, 2022 |
| ASUSTek       | M4A78L-M                    | [dfb87ada40](https://linux-hardware.org/?probe=dfb87ada40) | Jan 13, 2022 |
| HP            | 3031h                       | [46b02ff904](https://linux-hardware.org/?probe=46b02ff904) | Jan 11, 2022 |
| HP            | 3031h                       | [2e78e6c7f8](https://linux-hardware.org/?probe=2e78e6c7f8) | Jan 10, 2022 |
| ASUSTek       | H87M-PLUS                   | [eb70946711](https://linux-hardware.org/?probe=eb70946711) | Jan 09, 2022 |
| ASUSTek       | M4A88T-M                    | [7f20d8ac9a](https://linux-hardware.org/?probe=7f20d8ac9a) | Jan 09, 2022 |
| MSI           | H61M-P23                    | [14690b4128](https://linux-hardware.org/?probe=14690b4128) | Jan 08, 2022 |
| ASRock        | N68-VS3 UCC                 | [0ea3f1d6fa](https://linux-hardware.org/?probe=0ea3f1d6fa) | Jan 08, 2022 |
| Dell          | 073MMW A03                  | [65c164f304](https://linux-hardware.org/?probe=65c164f304) | Jan 07, 2022 |
| Gigabyte      | GA-970A-D3                  | [0fe418c7b1](https://linux-hardware.org/?probe=0fe418c7b1) | Jan 07, 2022 |
| Gigabyte      | Z97X-UD3H-BK-CF             | [ef69bbfd12](https://linux-hardware.org/?probe=ef69bbfd12) | Jan 07, 2022 |
| HP            | 0AA8h                       | [9abf55a71f](https://linux-hardware.org/?probe=9abf55a71f) | Jan 05, 2022 |
| HP            | 0AA8h                       | [44c9ba4231](https://linux-hardware.org/?probe=44c9ba4231) | Jan 03, 2022 |
| Intel         | DP35DP AAD81073-209         | [f6ec40d0f8](https://linux-hardware.org/?probe=f6ec40d0f8) | Jan 01, 2022 |
| ASUSTek       | P5K-E                       | [f1c3532217](https://linux-hardware.org/?probe=f1c3532217) | Dec 31, 2021 |
| ECS           | G41T-M2                     | [6b4159a357](https://linux-hardware.org/?probe=6b4159a357) | Dec 29, 2021 |
| Gigabyte      | H110M-H-CF                  | [d8a2a90482](https://linux-hardware.org/?probe=d8a2a90482) | Dec 27, 2021 |
| Gigabyte      | H110M-H-CF                  | [63b3337725](https://linux-hardware.org/?probe=63b3337725) | Dec 26, 2021 |
| ASRock        | A75M-ITX                    | [1070ea74d9](https://linux-hardware.org/?probe=1070ea74d9) | Dec 25, 2021 |
| ASRock        | X570M Pro4                  | [602d3e0afd](https://linux-hardware.org/?probe=602d3e0afd) | Dec 23, 2021 |
| HP            | 3398                        | [759e3821b8](https://linux-hardware.org/?probe=759e3821b8) | Dec 22, 2021 |
| Dell          | 0M5DCD A00                  | [d29b59a855](https://linux-hardware.org/?probe=d29b59a855) | Dec 21, 2021 |
| Gigabyte      | B150M-D3H-CF                | [22f2f5c84b](https://linux-hardware.org/?probe=22f2f5c84b) | Dec 21, 2021 |
| HP            | 18E7                        | [b233eb9f3e](https://linux-hardware.org/?probe=b233eb9f3e) | Dec 20, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [32340d057e](https://linux-hardware.org/?probe=32340d057e) | Dec 20, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [8986819d3f](https://linux-hardware.org/?probe=8986819d3f) | Dec 19, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [a94bf3ef84](https://linux-hardware.org/?probe=a94bf3ef84) | Dec 19, 2021 |
| Dell          | 0VD5HY A04                  | [2aaa0df82d](https://linux-hardware.org/?probe=2aaa0df82d) | Dec 18, 2021 |
| ASUSTek       | P5GC-MX                     | [499a024e97](https://linux-hardware.org/?probe=499a024e97) | Dec 18, 2021 |
| Biostar       | H110MHC                     | [bb74f304fd](https://linux-hardware.org/?probe=bb74f304fd) | Dec 16, 2021 |
| MSI           | MS-B0501 100                | [ca4048db98](https://linux-hardware.org/?probe=ca4048db98) | Dec 14, 2021 |
| Gigabyte      | EX58-UD4P                   | [aa8da2e23c](https://linux-hardware.org/?probe=aa8da2e23c) | Dec 14, 2021 |
| Dell          | 0T656F A02                  | [c6fcad51e9](https://linux-hardware.org/?probe=c6fcad51e9) | Dec 13, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | [45a5dc5b06](https://linux-hardware.org/?probe=45a5dc5b06) | Dec 13, 2021 |
| Dell          | 073MMW A00                  | [c5c064c84f](https://linux-hardware.org/?probe=c5c064c84f) | Dec 13, 2021 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | [1f799f28c2](https://linux-hardware.org/?probe=1f799f28c2) | Dec 12, 2021 |
| ASUSTek       | M51BC                       | [11ff47f723](https://linux-hardware.org/?probe=11ff47f723) | Dec 12, 2021 |
| ASUSTek       | M51BC                       | [0dd637c0b8](https://linux-hardware.org/?probe=0dd637c0b8) | Dec 12, 2021 |
| ASUSTek       | P5G41T-M LX                 | [8b03acc524](https://linux-hardware.org/?probe=8b03acc524) | Dec 11, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [1b7f8b1fb9](https://linux-hardware.org/?probe=1b7f8b1fb9) | Dec 11, 2021 |
| ASUSTek       | M5A97 PLUS                  | [8684f34a9e](https://linux-hardware.org/?probe=8684f34a9e) | Dec 10, 2021 |
| Dell          | 06D7TR A00                  | [a4f61b0f15](https://linux-hardware.org/?probe=a4f61b0f15) | Dec 09, 2021 |
| Acer          | Veriton E430 v1.0           | [5c857f1bb6](https://linux-hardware.org/?probe=5c857f1bb6) | Dec 08, 2021 |
| ECS           | Nettle2                     | [bb67b27e67](https://linux-hardware.org/?probe=bb67b27e67) | Dec 07, 2021 |
| Dell          | 01W26N A00                  | [7c3e61ec94](https://linux-hardware.org/?probe=7c3e61ec94) | Dec 06, 2021 |
| Gigabyte      | EP35-DS4                    | [570104ad1e](https://linux-hardware.org/?probe=570104ad1e) | Dec 04, 2021 |
| Gigabyte      | B450M DS3H-CF               | [2e34a3a698](https://linux-hardware.org/?probe=2e34a3a698) | Dec 04, 2021 |
| Medion        | H81M-P33                    | [29b3a27675](https://linux-hardware.org/?probe=29b3a27675) | Dec 02, 2021 |
| HP            | 0AA4h                       | [f7438f59ac](https://linux-hardware.org/?probe=f7438f59ac) | Dec 01, 2021 |
| Gigabyte      | X99-UD4-CF                  | [190d1b6a29](https://linux-hardware.org/?probe=190d1b6a29) | Dec 01, 2021 |
| Shuttle       | NC03U                       | [2453ada3ba](https://linux-hardware.org/?probe=2453ada3ba) | Nov 30, 2021 |
| ASUSTek       | H81M-PLUS                   | [6d6caad964](https://linux-hardware.org/?probe=6d6caad964) | Nov 29, 2021 |
| ASUSTek       | A68HM-K                     | [29e9d64420](https://linux-hardware.org/?probe=29e9d64420) | Nov 29, 2021 |
| ASUSTek       | P7P55D                      | [85f288d39b](https://linux-hardware.org/?probe=85f288d39b) | Nov 29, 2021 |
| Acer          | EG43LMK                     | [28e31230a4](https://linux-hardware.org/?probe=28e31230a4) | Nov 28, 2021 |
| HP            | 0AA8h                       | [1d80d6636e](https://linux-hardware.org/?probe=1d80d6636e) | Nov 26, 2021 |
| Medion        | H110H4-EM                   | [8b1485f27d](https://linux-hardware.org/?probe=8b1485f27d) | Nov 25, 2021 |
| ASRock        | B450M Pro4                  | [76361c26c6](https://linux-hardware.org/?probe=76361c26c6) | Nov 24, 2021 |
| ASRock        | N68-GS4 FX R2.0             | [d61128f6f4](https://linux-hardware.org/?probe=d61128f6f4) | Nov 24, 2021 |
| Gigabyte      | Z97X-UD3H-CF                | [fe8ad04ad3](https://linux-hardware.org/?probe=fe8ad04ad3) | Nov 23, 2021 |
| ASUSTek       | M3N78-EM                    | [b358f07f1d](https://linux-hardware.org/?probe=b358f07f1d) | Nov 21, 2021 |
| Dell          | 0WMJ54 A01                  | [b1f845a48f](https://linux-hardware.org/?probe=b1f845a48f) | Nov 20, 2021 |
| ASUSTek       | M3N78-EM                    | [930c018424](https://linux-hardware.org/?probe=930c018424) | Nov 20, 2021 |
| Dell          | 014GRG A02                  | [c23455dd49](https://linux-hardware.org/?probe=c23455dd49) | Nov 20, 2021 |
| ASUSTek       | B150-PLUS                   | [3c4c353831](https://linux-hardware.org/?probe=3c4c353831) | Nov 19, 2021 |
| MSI           | 3666h                       | [21f11d2850](https://linux-hardware.org/?probe=21f11d2850) | Nov 19, 2021 |
| ASRock        | Z97 Extreme4                | [fc86b0fc2e](https://linux-hardware.org/?probe=fc86b0fc2e) | Nov 18, 2021 |
| MSI           | 3666h                       | [aad8cfbf76](https://linux-hardware.org/?probe=aad8cfbf76) | Nov 18, 2021 |
| ASUSTek       | P5LD2-VM                    | [befbf7345c](https://linux-hardware.org/?probe=befbf7345c) | Nov 17, 2021 |
| HP            | 0AA8h                       | [5cd5f5de04](https://linux-hardware.org/?probe=5cd5f5de04) | Nov 16, 2021 |
| ASRock        | H470 Phantom Gaming 4       | [07ef26c830](https://linux-hardware.org/?probe=07ef26c830) | Nov 16, 2021 |
| Lenovo        | ThinkCentre A58e 0841A2U    | [a8398f9036](https://linux-hardware.org/?probe=a8398f9036) | Nov 13, 2021 |
| ASUSTek       | PRIME B550M-A               | [269b146e10](https://linux-hardware.org/?probe=269b146e10) | Nov 10, 2021 |
| Fujitsu       | D3417-B2 S26361-D3417-B2    | [ab14080e40](https://linux-hardware.org/?probe=ab14080e40) | Nov 09, 2021 |
| Medion        | H110H4-EM                   | [3ecf7775d6](https://linux-hardware.org/?probe=3ecf7775d6) | Nov 09, 2021 |
| ASUSTek       | PRIME B550M-A               | [9456930b53](https://linux-hardware.org/?probe=9456930b53) | Nov 08, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [425b956614](https://linux-hardware.org/?probe=425b956614) | Nov 07, 2021 |
| NCR           | Pocono BIOS.3.1             | [985620ce15](https://linux-hardware.org/?probe=985620ce15) | Nov 07, 2021 |
| Medion        | MS-7366                     | [da9961f1ee](https://linux-hardware.org/?probe=da9961f1ee) | Nov 04, 2021 |
| Acer          | Aspire X3990                | [967427d98c](https://linux-hardware.org/?probe=967427d98c) | Oct 29, 2021 |
| Acer          | Aspire X3990                | [7ccc4b3004](https://linux-hardware.org/?probe=7ccc4b3004) | Oct 29, 2021 |
| HP            | 8433 11                     | [6183f8775b](https://linux-hardware.org/?probe=6183f8775b) | Oct 29, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [164b215164](https://linux-hardware.org/?probe=164b215164) | Oct 29, 2021 |
| ASUSTek       | P5KC                        | [109cb750a6](https://linux-hardware.org/?probe=109cb750a6) | Oct 25, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2b52b81540](https://linux-hardware.org/?probe=2b52b81540) | Oct 24, 2021 |
| Dell          | 042P49 A00                  | [7bb7c6c3cb](https://linux-hardware.org/?probe=7bb7c6c3cb) | Oct 23, 2021 |
| MSI           | Z97 GAMING 5                | [0273030434](https://linux-hardware.org/?probe=0273030434) | Oct 22, 2021 |
| HP            | 1998                        | [db3a3fbce2](https://linux-hardware.org/?probe=db3a3fbce2) | Oct 21, 2021 |
| Dell          | 0PU052                      | [7e7d0bc489](https://linux-hardware.org/?probe=7e7d0bc489) | Oct 21, 2021 |
| ASUSTek       | PRIME H310T                 | [b0e10a4766](https://linux-hardware.org/?probe=b0e10a4766) | Oct 20, 2021 |
| MSI           | B350 TOMAHAWK               | [a119d97189](https://linux-hardware.org/?probe=a119d97189) | Oct 20, 2021 |
| ASRock        | G31M-VS2                    | [555bb7179c](https://linux-hardware.org/?probe=555bb7179c) | Oct 19, 2021 |
| MSI           | H170M PRO-VDH               | [63cab5e07f](https://linux-hardware.org/?probe=63cab5e07f) | Oct 19, 2021 |
| MSI           | H170M PRO-VDH               | [355e464f7f](https://linux-hardware.org/?probe=355e464f7f) | Oct 19, 2021 |
| HP            | 8717                        | [23f7ea44ce](https://linux-hardware.org/?probe=23f7ea44ce) | Oct 18, 2021 |
| Gigabyte      | M68MT-D3P                   | [9debdd654c](https://linux-hardware.org/?probe=9debdd654c) | Oct 15, 2021 |
| NCR           | Pocono BIOS.3.1             | [53cafab8f3](https://linux-hardware.org/?probe=53cafab8f3) | Oct 15, 2021 |
| Clientron     | Pineview-D                  | [59bf0b789c](https://linux-hardware.org/?probe=59bf0b789c) | Oct 13, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [e922eda008](https://linux-hardware.org/?probe=e922eda008) | Oct 12, 2021 |
| Foxconn       | 2AB1h                       | [6216ce3f5c](https://linux-hardware.org/?probe=6216ce3f5c) | Oct 12, 2021 |
| MSI           | H170M PRO-VDH               | [56135a7fa6](https://linux-hardware.org/?probe=56135a7fa6) | Oct 11, 2021 |
| MSI           | H170M PRO-VDH               | [d7676eeb32](https://linux-hardware.org/?probe=d7676eeb32) | Oct 11, 2021 |
| Gigabyte      | B450 AORUS ELITE V2         | [c49cbf2f7a](https://linux-hardware.org/?probe=c49cbf2f7a) | Oct 11, 2021 |
| Medion        | B360H4-EM V1.0              | [6d2f43a452](https://linux-hardware.org/?probe=6d2f43a452) | Oct 09, 2021 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [6beb9ddceb](https://linux-hardware.org/?probe=6beb9ddceb) | Oct 09, 2021 |
| Gigabyte      | H510M S2H                   | [77205a87c4](https://linux-hardware.org/?probe=77205a87c4) | Oct 09, 2021 |
| ASUSTek       | PRIME H410M-K               | [a4da124d05](https://linux-hardware.org/?probe=a4da124d05) | Oct 08, 2021 |
| Gigabyte      | X38-DS4                     | [5e06d3cb35](https://linux-hardware.org/?probe=5e06d3cb35) | Oct 08, 2021 |
| Dell          | 05DN3X A00                  | [248c508eb0](https://linux-hardware.org/?probe=248c508eb0) | Oct 07, 2021 |
| Dell          | 05DN3X A00                  | [0735063fbe](https://linux-hardware.org/?probe=0735063fbe) | Oct 07, 2021 |
| Lenovo        | ThinkCentre A55 92658HG     | [edc1f2768d](https://linux-hardware.org/?probe=edc1f2768d) | Oct 05, 2021 |
| Acer          | Aspire X1430                | [0864e39368](https://linux-hardware.org/?probe=0864e39368) | Oct 05, 2021 |
| MSI           | MPG Z390 GAMING EDGE AC     | [37caf69047](https://linux-hardware.org/?probe=37caf69047) | Oct 02, 2021 |
| ASRock        | Z170 Gaming K4              | [f107c84c00](https://linux-hardware.org/?probe=f107c84c00) | Sep 30, 2021 |
| Insyde        | Harrisonville               | [2b7a8ba5fc](https://linux-hardware.org/?probe=2b7a8ba5fc) | Sep 30, 2021 |
| HP            | 2175                        | [856907ec52](https://linux-hardware.org/?probe=856907ec52) | Sep 28, 2021 |
| ASUSTek       | PRIME H310T                 | [58721f0765](https://linux-hardware.org/?probe=58721f0765) | Sep 28, 2021 |
| Dell          | 0N826N A03                  | [fc1d74c246](https://linux-hardware.org/?probe=fc1d74c246) | Sep 27, 2021 |
| ASUSTek       | PRIME H510M-K               | [c11c48b5d6](https://linux-hardware.org/?probe=c11c48b5d6) | Sep 24, 2021 |
| ASUSTek       | PRIME H510M-K               | [66900d1009](https://linux-hardware.org/?probe=66900d1009) | Sep 24, 2021 |
| HP            | 21F5                        | [d6613e1901](https://linux-hardware.org/?probe=d6613e1901) | Sep 22, 2021 |
| AAEON         | GENE-APL5 V1.0              | [7abd7a20df](https://linux-hardware.org/?probe=7abd7a20df) | Sep 21, 2021 |
| NCR           | Pocono                      | [bbd821ad81](https://linux-hardware.org/?probe=bbd821ad81) | Sep 18, 2021 |
| ASUSTek       | P8H67                       | [ad597e71b6](https://linux-hardware.org/?probe=ad597e71b6) | Sep 16, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | [ea9fbdbba6](https://linux-hardware.org/?probe=ea9fbdbba6) | Sep 14, 2021 |
| Dell          | 0XHGV1 A00                  | [c7f133cbb9](https://linux-hardware.org/?probe=c7f133cbb9) | Sep 14, 2021 |
| Foxconn       | 2A8C                        | [f7b2ed152f](https://linux-hardware.org/?probe=f7b2ed152f) | Sep 12, 2021 |
| ASUSTek       | M3N18L T-M3N8200            | [bd8410bceb](https://linux-hardware.org/?probe=bd8410bceb) | Sep 09, 2021 |
| Biostar       | G41D3C                      | [fc87e33227](https://linux-hardware.org/?probe=fc87e33227) | Sep 07, 2021 |
| ASUSTek       | H170M-PLUS                  | [7b81d32161](https://linux-hardware.org/?probe=7b81d32161) | Sep 07, 2021 |
| OEM           | BayTrail JHS365             | [e82d82c85b](https://linux-hardware.org/?probe=e82d82c85b) | Sep 03, 2021 |
| ASUSTek       | P8Z68-V LX                  | [899954b326](https://linux-hardware.org/?probe=899954b326) | Sep 02, 2021 |
| Acer          | Aspire XC-603G              | [888a6f7244](https://linux-hardware.org/?probe=888a6f7244) | Sep 02, 2021 |
| HP            | 3032h                       | [4b261dcd37](https://linux-hardware.org/?probe=4b261dcd37) | Sep 02, 2021 |
| Gigabyte      | G41M-ES2L                   | [b9fdcaf2f7](https://linux-hardware.org/?probe=b9fdcaf2f7) | Sep 02, 2021 |
| Biostar       | G41D3C                      | [985970ad93](https://linux-hardware.org/?probe=985970ad93) | Sep 01, 2021 |
| Biostar       | G41D3C                      | [a94c446d8d](https://linux-hardware.org/?probe=a94c446d8d) | Sep 01, 2021 |
| MSI           | Z97-G43                     | [364baf5248](https://linux-hardware.org/?probe=364baf5248) | Aug 31, 2021 |
| ASRock        | Q1900M                      | [bdb4eba3e4](https://linux-hardware.org/?probe=bdb4eba3e4) | Aug 31, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [89c397b882](https://linux-hardware.org/?probe=89c397b882) | Aug 29, 2021 |
| Lenovo        | SHARKBAY SDK0E50512 STD     | [aa1a98a9d6](https://linux-hardware.org/?probe=aa1a98a9d6) | Aug 25, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [fae18649fd](https://linux-hardware.org/?probe=fae18649fd) | Aug 24, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [f0824b7193](https://linux-hardware.org/?probe=f0824b7193) | Aug 24, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [8d43ff5f35](https://linux-hardware.org/?probe=8d43ff5f35) | Aug 23, 2021 |
| Acer          | Aspire TC-885 V:1.1         | [23fcf2122e](https://linux-hardware.org/?probe=23fcf2122e) | Aug 23, 2021 |
| Gigabyte      | B450M DS3H-CF               | [f128b4ee5a](https://linux-hardware.org/?probe=f128b4ee5a) | Aug 23, 2021 |
| Acer          | Aspire XC-603G              | [3aca23ef5f](https://linux-hardware.org/?probe=3aca23ef5f) | Aug 22, 2021 |
| Foxconn       | 2A8C                        | [f3ae3bb84c](https://linux-hardware.org/?probe=f3ae3bb84c) | Aug 21, 2021 |
| Alienware     | 0N4R4N A00                  | [bf5947b943](https://linux-hardware.org/?probe=bf5947b943) | Aug 20, 2021 |
| ASRock        | A320M-HDV                   | [42ab0a8ca5](https://linux-hardware.org/?probe=42ab0a8ca5) | Aug 20, 2021 |
| Acer          | Aspire X1470                | [79d5cfd4fd](https://linux-hardware.org/?probe=79d5cfd4fd) | Aug 20, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [dbb548b728](https://linux-hardware.org/?probe=dbb548b728) | Aug 18, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [4740529a1f](https://linux-hardware.org/?probe=4740529a1f) | Aug 17, 2021 |
| MSI           | Boston                      | [eb189f6da8](https://linux-hardware.org/?probe=eb189f6da8) | Aug 17, 2021 |
| HP            | 0B54h D                     | [f68a448d75](https://linux-hardware.org/?probe=f68a448d75) | Aug 17, 2021 |
| Gateway       | SX2185                      | [6e9745ae09](https://linux-hardware.org/?probe=6e9745ae09) | Aug 17, 2021 |
| HP            | 0B54h D                     | [9fd9d289f2](https://linux-hardware.org/?probe=9fd9d289f2) | Aug 17, 2021 |
| ASUSTek       | B85-PLUS                    | [10fd5746f0](https://linux-hardware.org/?probe=10fd5746f0) | Aug 14, 2021 |
| ASRock        | A300M-STX                   | [3ff1b8f6dc](https://linux-hardware.org/?probe=3ff1b8f6dc) | Aug 14, 2021 |
| HP            | 0B54h D                     | [49eb423362](https://linux-hardware.org/?probe=49eb423362) | Aug 11, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | [c69570237c](https://linux-hardware.org/?probe=c69570237c) | Aug 10, 2021 |
| Gigabyte      | X99-UD4-CF                  | [0b019ac936](https://linux-hardware.org/?probe=0b019ac936) | Aug 09, 2021 |
| ASUSTek       | H87M-PLUS                   | [c2ed04ce87](https://linux-hardware.org/?probe=c2ed04ce87) | Aug 09, 2021 |
| Intel         | D945GNT AAC96315-402        | [a2d256eee3](https://linux-hardware.org/?probe=a2d256eee3) | Aug 08, 2021 |
| Dell          | 0WMJ54 A00                  | [d577241d35](https://linux-hardware.org/?probe=d577241d35) | Aug 08, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [c45499e754](https://linux-hardware.org/?probe=c45499e754) | Aug 07, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [c3ac112d1b](https://linux-hardware.org/?probe=c3ac112d1b) | Aug 06, 2021 |
| HP            | 1998                        | [e6d0744e85](https://linux-hardware.org/?probe=e6d0744e85) | Aug 04, 2021 |
| HP            | 1998                        | [b3b909d152](https://linux-hardware.org/?probe=b3b909d152) | Aug 04, 2021 |
| HP            | 3646h                       | [60fb363058](https://linux-hardware.org/?probe=60fb363058) | Aug 02, 2021 |
| HP            | 2B29                        | [06babd8c13](https://linux-hardware.org/?probe=06babd8c13) | Aug 01, 2021 |
| HP            | 0B54h D                     | [a7f0b16b1f](https://linux-hardware.org/?probe=a7f0b16b1f) | Jul 31, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [0aae2dd454](https://linux-hardware.org/?probe=0aae2dd454) | Jul 30, 2021 |
| MSI           | MS-7181                     | [f2c624a258](https://linux-hardware.org/?probe=f2c624a258) | Jul 26, 2021 |
| WinFast       | 6100M2MA FAB1.0             | [f994eb2a66](https://linux-hardware.org/?probe=f994eb2a66) | Jul 26, 2021 |
| Intel         | DQ67SW AAG12527-310         | [36a4037b9d](https://linux-hardware.org/?probe=36a4037b9d) | Jul 26, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [69bc249119](https://linux-hardware.org/?probe=69bc249119) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [d6e4e7f445](https://linux-hardware.org/?probe=d6e4e7f445) | Jul 25, 2021 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [7d7ebd3f1e](https://linux-hardware.org/?probe=7d7ebd3f1e) | Jul 25, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | [56198fa6c1](https://linux-hardware.org/?probe=56198fa6c1) | Jul 24, 2021 |
| Dell          | 03KWTV A02                  | [b292aa69b5](https://linux-hardware.org/?probe=b292aa69b5) | Jul 24, 2021 |
| HP            | 1589                        | [2885bdaad2](https://linux-hardware.org/?probe=2885bdaad2) | Jul 23, 2021 |
| MSI           | Z370-A PRO                  | [b125a65313](https://linux-hardware.org/?probe=b125a65313) | Jul 22, 2021 |
| ASUSTek       | PRIME Z390-A                | [f8767723e4](https://linux-hardware.org/?probe=f8767723e4) | Jul 18, 2021 |
| ASRock        | 880GM-LE                    | [4808dde963](https://linux-hardware.org/?probe=4808dde963) | Jul 18, 2021 |
| Dell          | 0VNP2H A00                  | [167ec81986](https://linux-hardware.org/?probe=167ec81986) | Jul 17, 2021 |
| Gigabyte      | Z77X-D3H                    | [8263a1f725](https://linux-hardware.org/?probe=8263a1f725) | Jul 17, 2021 |
| ASRock        | X300M-STX                   | [3a35cafb7f](https://linux-hardware.org/?probe=3a35cafb7f) | Jul 17, 2021 |
| ASUSTek       | M3A-H/HDMI                  | [6c97b09b3f](https://linux-hardware.org/?probe=6c97b09b3f) | Jul 14, 2021 |
| Gigabyte      | H55M-UD2H                   | [d871a17735](https://linux-hardware.org/?probe=d871a17735) | Jul 14, 2021 |
| ASRock        | Z490 Phantom Gaming 4       | [ee2fa49a14](https://linux-hardware.org/?probe=ee2fa49a14) | Jul 13, 2021 |
| HP            | 0A64h                       | [317c62b0b9](https://linux-hardware.org/?probe=317c62b0b9) | Jul 13, 2021 |
| HP            | 0A64h                       | [7495976a12](https://linux-hardware.org/?probe=7495976a12) | Jul 13, 2021 |
| ASUSTek       | A68HM-K                     | [03c69f44e3](https://linux-hardware.org/?probe=03c69f44e3) | Jul 12, 2021 |
| Gigabyte      | Z77X-D3H                    | [5416b8d0da](https://linux-hardware.org/?probe=5416b8d0da) | Jul 10, 2021 |
| ASUSTek       | ROG STRIX Z590-A GAMING ... | [252d84e173](https://linux-hardware.org/?probe=252d84e173) | Jul 05, 2021 |
| MSI           | Boston                      | [72f1bfa2f0](https://linux-hardware.org/?probe=72f1bfa2f0) | Jul 05, 2021 |
| MSI           | Boston                      | [ff82275c70](https://linux-hardware.org/?probe=ff82275c70) | Jul 04, 2021 |
| ASRock        | J4105M                      | [b732da09a3](https://linux-hardware.org/?probe=b732da09a3) | Jul 04, 2021 |
| ASRock        | J4105M                      | [a2d5afa1d6](https://linux-hardware.org/?probe=a2d5afa1d6) | Jul 04, 2021 |
| Gigabyte      | F2A78M-HD2                  | [7974efd1a4](https://linux-hardware.org/?probe=7974efd1a4) | Jul 03, 2021 |
| Dell          | 0M863N A00                  | [a505e284ec](https://linux-hardware.org/?probe=a505e284ec) | Jun 27, 2021 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [1e4e8c8638](https://linux-hardware.org/?probe=1e4e8c8638) | Jun 27, 2021 |
| Lenovo        | ThinkStation D20 4158CM1    | [004bd0bb8e](https://linux-hardware.org/?probe=004bd0bb8e) | Jun 26, 2021 |
| Gigabyte      | B450M DS3H-CF               | [c40b02d888](https://linux-hardware.org/?probe=c40b02d888) | Jun 24, 2021 |
| HP            | 0AA8h                       | [8de391044c](https://linux-hardware.org/?probe=8de391044c) | Jun 24, 2021 |
| HP            | 0AA8h                       | [a477bc402f](https://linux-hardware.org/?probe=a477bc402f) | Jun 24, 2021 |
| MSI           | MPG X570 GAMING PRO CARB... | [f697fb056b](https://linux-hardware.org/?probe=f697fb056b) | Jun 24, 2021 |
| MSI           | B350M PRO-VDH               | [c1009474e9](https://linux-hardware.org/?probe=c1009474e9) | Jun 21, 2021 |
| Gigabyte      | A320M-S2H V2-CF             | [d2519fe6fd](https://linux-hardware.org/?probe=d2519fe6fd) | Jun 21, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [d5ebc8bdc6](https://linux-hardware.org/?probe=d5ebc8bdc6) | Jun 18, 2021 |
| Dell          | 0WG855                      | [02b09ef628](https://linux-hardware.org/?probe=02b09ef628) | Jun 17, 2021 |
| Dell          | 0WR7PY A02                  | [fb27aaebe4](https://linux-hardware.org/?probe=fb27aaebe4) | Jun 15, 2021 |
| MSI           | B350M PRO-VDH               | [b2d3b7546a](https://linux-hardware.org/?probe=b2d3b7546a) | Jun 15, 2021 |
| Gigabyte      | H55M-USB3                   | [3372e4c0ab](https://linux-hardware.org/?probe=3372e4c0ab) | Jun 14, 2021 |
| HP            | 1589                        | [531fd7a206](https://linux-hardware.org/?probe=531fd7a206) | Jun 12, 2021 |
| ASRock        | X300M-STX                   | [fd6970af13](https://linux-hardware.org/?probe=fd6970af13) | Jun 12, 2021 |
| Gigabyte      | B450M DS3H-CF               | [28cc50b8af](https://linux-hardware.org/?probe=28cc50b8af) | Jun 11, 2021 |
| Gigabyte      | H81M-D2W                    | [a5cf29d3fa](https://linux-hardware.org/?probe=a5cf29d3fa) | Jun 11, 2021 |
| ASUSTek       | Z170 PRO GAMING/AURA        | [6b3ad983d3](https://linux-hardware.org/?probe=6b3ad983d3) | Jun 11, 2021 |
| Packard Be... | WMCP78M                     | [c267385b22](https://linux-hardware.org/?probe=c267385b22) | Jun 11, 2021 |
| Dell          | 0MWYPT A01                  | [fb7b10919d](https://linux-hardware.org/?probe=fb7b10919d) | Jun 09, 2021 |
| Gigabyte      | 945PL-S3                    | [885dc78ef1](https://linux-hardware.org/?probe=885dc78ef1) | Jun 08, 2021 |
| Gateway       | SX2185                      | [541a86ceb1](https://linux-hardware.org/?probe=541a86ceb1) | Jun 08, 2021 |
| Intel         | H61                         | [50b0503c3c](https://linux-hardware.org/?probe=50b0503c3c) | Jun 07, 2021 |
| Gigabyte      | X58A-UD3R                   | [216d963387](https://linux-hardware.org/?probe=216d963387) | Jun 05, 2021 |
| MSI           | X99A SLI Krait Edition      | [f9626d011c](https://linux-hardware.org/?probe=f9626d011c) | Jun 05, 2021 |
| ASRock        | A320M-DVS R4.0              | [4ce3673d2d](https://linux-hardware.org/?probe=4ce3673d2d) | Jun 04, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [8684efd5c9](https://linux-hardware.org/?probe=8684efd5c9) | Jun 04, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [5dbe42cf75](https://linux-hardware.org/?probe=5dbe42cf75) | Jun 03, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [07eb1feeb4](https://linux-hardware.org/?probe=07eb1feeb4) | Jun 03, 2021 |
| HP            | 3032h                       | [dade0cb1d6](https://linux-hardware.org/?probe=dade0cb1d6) | Jun 03, 2021 |
| Packard Be... | IMEDIA S2110A               | [34a921fd71](https://linux-hardware.org/?probe=34a921fd71) | Jun 03, 2021 |
| QTQD          | Unknown                     | [f7d66120da](https://linux-hardware.org/?probe=f7d66120da) | Jun 01, 2021 |
| Intel         | DH61WW AAG23116-204         | [5b590117dd](https://linux-hardware.org/?probe=5b590117dd) | Jun 01, 2021 |
| MSI           | B250M PRO-VD                | [c90bb6eca1](https://linux-hardware.org/?probe=c90bb6eca1) | May 31, 2021 |
| HP            | 3032h                       | [ea009f77d1](https://linux-hardware.org/?probe=ea009f77d1) | May 31, 2021 |
| NCR           | Pocono                      | [73bfada83a](https://linux-hardware.org/?probe=73bfada83a) | May 30, 2021 |
| Intel         | DH61WW AAG23116-204         | [f109707413](https://linux-hardware.org/?probe=f109707413) | May 29, 2021 |
| MSI           | A68HM-E33 V2                | [a9971ed939](https://linux-hardware.org/?probe=a9971ed939) | May 29, 2021 |
| HP            | 18E7                        | [dbb0731dd9](https://linux-hardware.org/?probe=dbb0731dd9) | May 27, 2021 |
| Medion        | H110H4-EM                   | [09ca813f06](https://linux-hardware.org/?probe=09ca813f06) | May 25, 2021 |
| ASRock        | H110M-ITX/ac                | [f03f0287f4](https://linux-hardware.org/?probe=f03f0287f4) | May 24, 2021 |
| ECS           | H61H2-M2                    | [a6e86907bf](https://linux-hardware.org/?probe=a6e86907bf) | May 22, 2021 |
| ASUSTek       | A68HM-K                     | [d62c1cc4aa](https://linux-hardware.org/?probe=d62c1cc4aa) | May 22, 2021 |
| Acer          | H57M01                      | [8b9e2fb5f2](https://linux-hardware.org/?probe=8b9e2fb5f2) | May 19, 2021 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [21bb7408e3](https://linux-hardware.org/?probe=21bb7408e3) | May 18, 2021 |
| Gigabyte      | C847N                       | [7a17d8efef](https://linux-hardware.org/?probe=7a17d8efef) | May 17, 2021 |
| Gigabyte      | C847N                       | [deb3c6a79f](https://linux-hardware.org/?probe=deb3c6a79f) | May 17, 2021 |
| Acer          | H57M01                      | [a80686767d](https://linux-hardware.org/?probe=a80686767d) | May 16, 2021 |
| Intel         | BTC-T37                     | [dcfc697c0a](https://linux-hardware.org/?probe=dcfc697c0a) | May 16, 2021 |
| Lenovo        | MAHOBAY                     | [0299025f98](https://linux-hardware.org/?probe=0299025f98) | May 15, 2021 |
| Acer          | TPDS05 R3700                | [9abf1ed283](https://linux-hardware.org/?probe=9abf1ed283) | May 15, 2021 |
| Gigabyte      | A320M-S2H-CF                | [48f873b6de](https://linux-hardware.org/?probe=48f873b6de) | May 14, 2021 |
| MSI           | B450-A PRO MAX              | [7b40989bc7](https://linux-hardware.org/?probe=7b40989bc7) | May 13, 2021 |
| MSI           | B450-A PRO MAX              | [acff281d6b](https://linux-hardware.org/?probe=acff281d6b) | May 12, 2021 |
| Gigabyte      | EP45-UD3R                   | [25abeee3ef](https://linux-hardware.org/?probe=25abeee3ef) | May 12, 2021 |
| Gigabyte      | A320M-S2H-CF                | [a3f9e2334a](https://linux-hardware.org/?probe=a3f9e2334a) | May 11, 2021 |
| Dell          | 0CU409                      | [151b11acfc](https://linux-hardware.org/?probe=151b11acfc) | May 11, 2021 |
| Dell          | 0CU409                      | [3ea181ca1b](https://linux-hardware.org/?probe=3ea181ca1b) | May 10, 2021 |
| Medion        | H110H4-CM2                  | [c622bcf1bb](https://linux-hardware.org/?probe=c622bcf1bb) | May 09, 2021 |
| Acer          | H57M01                      | [ec79128c45](https://linux-hardware.org/?probe=ec79128c45) | May 09, 2021 |
| Gigabyte      | A520I AC                    | [eb32404ebf](https://linux-hardware.org/?probe=eb32404ebf) | May 07, 2021 |
| Lenovo        | ThinkStation D30 4223B35    | [e3c6a7b793](https://linux-hardware.org/?probe=e3c6a7b793) | May 06, 2021 |
| Gigabyte      | H110N-CF                    | [d03c007deb](https://linux-hardware.org/?probe=d03c007deb) | May 06, 2021 |
| HP            | 2B05                        | [0bfbf859ca](https://linux-hardware.org/?probe=0bfbf859ca) | May 05, 2021 |
| Huanan        | X58-RX3.0 V111              | [5181d65714](https://linux-hardware.org/?probe=5181d65714) | May 04, 2021 |
| ASUSTek       | PRIME X570-PRO              | [e1b742d511](https://linux-hardware.org/?probe=e1b742d511) | May 04, 2021 |
| HP            | 198E                        | [396de7f15d](https://linux-hardware.org/?probe=396de7f15d) | May 03, 2021 |
| Gigabyte      | H81M-DS2                    | [747c5516a4](https://linux-hardware.org/?probe=747c5516a4) | May 03, 2021 |
| Dell          | 02YRK5 A02                  | [0ff2e7f046](https://linux-hardware.org/?probe=0ff2e7f046) | May 02, 2021 |
| MSI           | Z490M-S01                   | [b2de3af507](https://linux-hardware.org/?probe=b2de3af507) | May 02, 2021 |
| Foxconn       | H67M-S/H67M-V/H67           | [f22a2df347](https://linux-hardware.org/?probe=f22a2df347) | May 01, 2021 |
| Gigabyte      | A320M-S2H-CF                | [0deafa542c](https://linux-hardware.org/?probe=0deafa542c) | Apr 29, 2021 |
| Gigabyte      | A320M-S2H-CF                | [04d81bb2f6](https://linux-hardware.org/?probe=04d81bb2f6) | Apr 29, 2021 |
| Acer          | FC51GM                      | [ace5e495f5](https://linux-hardware.org/?probe=ace5e495f5) | Apr 26, 2021 |
| HP            | 21B4 A01                    | [9193163279](https://linux-hardware.org/?probe=9193163279) | Apr 26, 2021 |
| ASUSTek       | H87M-PLUS                   | [7ecfe05882](https://linux-hardware.org/?probe=7ecfe05882) | Apr 25, 2021 |
| Gigabyte      | Z68MA-D2H-B3                | [f6e266a897](https://linux-hardware.org/?probe=f6e266a897) | Apr 25, 2021 |
| ASRock        | Z170 Gaming K4              | [69ec5d246b](https://linux-hardware.org/?probe=69ec5d246b) | Apr 25, 2021 |
| ASRock        | N68-VS3 FX                  | [b92a431094](https://linux-hardware.org/?probe=b92a431094) | Apr 24, 2021 |
| Intel         | DH61WW AAG23116-203         | [32aae9ea9a](https://linux-hardware.org/?probe=32aae9ea9a) | Apr 24, 2021 |
| HP            | 339A                        | [ed44deea1a](https://linux-hardware.org/?probe=ed44deea1a) | Apr 21, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [2517cbf080](https://linux-hardware.org/?probe=2517cbf080) | Apr 20, 2021 |
| MSI           | 770-G45                     | [85ebceeb24](https://linux-hardware.org/?probe=85ebceeb24) | Apr 20, 2021 |
| Dell          | 0M5DCD A02                  | [ef0ddc38ce](https://linux-hardware.org/?probe=ef0ddc38ce) | Apr 19, 2021 |
| Dell          | 0KRC95 A03                  | [61da77da82](https://linux-hardware.org/?probe=61da77da82) | Apr 18, 2021 |
| HP            | 3047h                       | [c426bd5393](https://linux-hardware.org/?probe=c426bd5393) | Apr 18, 2021 |
| Huanan        | X58-RX3.0 V111              | [52841d2dbf](https://linux-hardware.org/?probe=52841d2dbf) | Apr 17, 2021 |
| HP            | ML110 G4                    | [443a299302](https://linux-hardware.org/?probe=443a299302) | Apr 17, 2021 |
| Dell          | 0M5DCD A02                  | [91f1b586b4](https://linux-hardware.org/?probe=91f1b586b4) | Apr 16, 2021 |
| Acer          | TPDS05 R3700                | [4c7b9482f3](https://linux-hardware.org/?probe=4c7b9482f3) | Apr 15, 2021 |
| Pegatron      | 2AC2A                       | [87fa4f3888](https://linux-hardware.org/?probe=87fa4f3888) | Apr 13, 2021 |
| ASUSTek       | AM1I-A                      | [6c2469b32a](https://linux-hardware.org/?probe=6c2469b32a) | Apr 11, 2021 |
| Acer          | Aspire X1430                | [b3b59b7e37](https://linux-hardware.org/?probe=b3b59b7e37) | Apr 11, 2021 |
| ASUSTek       | AM1I-A                      | [56f187f014](https://linux-hardware.org/?probe=56f187f014) | Apr 11, 2021 |
| ASRock        | H270M-ITX/ac                | [071ce283c1](https://linux-hardware.org/?probe=071ce283c1) | Apr 11, 2021 |
| ASRock        | H270M-ITX/ac                | [73cf10f10a](https://linux-hardware.org/?probe=73cf10f10a) | Apr 11, 2021 |
| ASRock        | B450M/ac                    | [ef79828d94](https://linux-hardware.org/?probe=ef79828d94) | Apr 11, 2021 |
| Dell          | 0GM819                      | [95f4b4a653](https://linux-hardware.org/?probe=95f4b4a653) | Apr 10, 2021 |
| Gigabyte      | X99-UD4-CF                  | [2189f9be68](https://linux-hardware.org/?probe=2189f9be68) | Apr 10, 2021 |
| ASRock        | B450 Pro4                   | [e97c041e12](https://linux-hardware.org/?probe=e97c041e12) | Apr 10, 2021 |
| MSI           | 970A-G43                    | [4618a9eef4](https://linux-hardware.org/?probe=4618a9eef4) | Apr 09, 2021 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | [cb6c7d5ecb](https://linux-hardware.org/?probe=cb6c7d5ecb) | Apr 09, 2021 |
| ASUSTek       | P5VD2-VM SE                 | [922a324d57](https://linux-hardware.org/?probe=922a324d57) | Apr 09, 2021 |
| HP            | EG157AA-ABF m1260.fr        | [cf4f87aefd](https://linux-hardware.org/?probe=cf4f87aefd) | Apr 08, 2021 |
| Gigabyte      | B450M DS3H-CF               | [a66003eab5](https://linux-hardware.org/?probe=a66003eab5) | Apr 05, 2021 |
| Gigabyte      | H270-HD3-CF                 | [987824d49a](https://linux-hardware.org/?probe=987824d49a) | Apr 05, 2021 |
| Biostar       | TB250-BTC                   | [a1b3b845a7](https://linux-hardware.org/?probe=a1b3b845a7) | Apr 05, 2021 |
| Biostar       | TB250-BTC                   | [908171f266](https://linux-hardware.org/?probe=908171f266) | Apr 05, 2021 |
| ASUSTek       | B150I PRO GAMING/AURA       | [b33866b71b](https://linux-hardware.org/?probe=b33866b71b) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [817d1bb360](https://linux-hardware.org/?probe=817d1bb360) | Apr 03, 2021 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [ca1692012f](https://linux-hardware.org/?probe=ca1692012f) | Apr 03, 2021 |
| Gigabyte      | 990FXA-UD3                  | [327a4888d5](https://linux-hardware.org/?probe=327a4888d5) | Apr 03, 2021 |
| ASUSTek       | P8H61                       | [cb9797346b](https://linux-hardware.org/?probe=cb9797346b) | Mar 30, 2021 |
| Huanan        | X58-RX3.0 V111              | [c18bd3abe8](https://linux-hardware.org/?probe=c18bd3abe8) | Mar 30, 2021 |
| ASRock        | K10N78D                     | [500f4c7c38](https://linux-hardware.org/?probe=500f4c7c38) | Mar 29, 2021 |
| ASUSTek       | A68HM-K                     | [ef5acde9af](https://linux-hardware.org/?probe=ef5acde9af) | Mar 28, 2021 |
| eMachines     | EL1850                      | [7c2d95778c](https://linux-hardware.org/?probe=7c2d95778c) | Mar 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [47323e14e8](https://linux-hardware.org/?probe=47323e14e8) | Mar 26, 2021 |
| ASUSTek       | P8Z68 DELUXE                | [8ce30ac5a9](https://linux-hardware.org/?probe=8ce30ac5a9) | Mar 26, 2021 |
| HP            | 3646h                       | [b529769ddc](https://linux-hardware.org/?probe=b529769ddc) | Mar 25, 2021 |
| ASUSTek       | P5KC                        | [0d1ffacb54](https://linux-hardware.org/?probe=0d1ffacb54) | Mar 24, 2021 |
| Gigabyte      | Z97X-Gaming 3               | [56e94aaad4](https://linux-hardware.org/?probe=56e94aaad4) | Mar 23, 2021 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | [ca09a97564](https://linux-hardware.org/?probe=ca09a97564) | Mar 23, 2021 |
| AAEON         | GENE-APL5 V1.0              | [ee93b490f0](https://linux-hardware.org/?probe=ee93b490f0) | Mar 22, 2021 |
| Lenovo        | ThinkCentre A70 7844H9G     | [070c4000e1](https://linux-hardware.org/?probe=070c4000e1) | Mar 22, 2021 |
| Gigabyte      | B450M S2H                   | [deb06f914c](https://linux-hardware.org/?probe=deb06f914c) | Mar 19, 2021 |
| MSI           | Z97-G43                     | [984145ba36](https://linux-hardware.org/?probe=984145ba36) | Mar 18, 2021 |
| ASRock        | AB350M Pro4 R2.0            | [d5ddb563ac](https://linux-hardware.org/?probe=d5ddb563ac) | Mar 18, 2021 |
| ASRock        | AB350M Pro4 R2.0            | [af9b948ec2](https://linux-hardware.org/?probe=af9b948ec2) | Mar 17, 2021 |
| Intel         | X99                         | [eff3e65d6d](https://linux-hardware.org/?probe=eff3e65d6d) | Mar 17, 2021 |
| ASUSTek       | M4A78 PRO                   | [0d75059dc8](https://linux-hardware.org/?probe=0d75059dc8) | Mar 17, 2021 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [7cc0dfac27](https://linux-hardware.org/?probe=7cc0dfac27) | Mar 17, 2021 |
| Intel         | X99                         | [1f84949851](https://linux-hardware.org/?probe=1f84949851) | Mar 17, 2021 |
| MSI           | A88XM-E45                   | [96048dac39](https://linux-hardware.org/?probe=96048dac39) | Mar 17, 2021 |
| HP            | 2B17                        | [753cbbeb9e](https://linux-hardware.org/?probe=753cbbeb9e) | Mar 16, 2021 |
| ASRock        | FM2A88X-ITX+                | [7a38886add](https://linux-hardware.org/?probe=7a38886add) | Mar 14, 2021 |
| Dell          | 0T656F A02                  | [708eb1bf51](https://linux-hardware.org/?probe=708eb1bf51) | Mar 13, 2021 |
| HP            | 339A                        | [355b85c060](https://linux-hardware.org/?probe=355b85c060) | Mar 13, 2021 |
| Medion        | H110H4-EM                   | [c0f324b6aa](https://linux-hardware.org/?probe=c0f324b6aa) | Mar 13, 2021 |
| HP            | 18E7                        | [c0793d8023](https://linux-hardware.org/?probe=c0793d8023) | Mar 13, 2021 |
| HP            | 339A                        | [a24b4dd571](https://linux-hardware.org/?probe=a24b4dd571) | Mar 13, 2021 |
| ASUSTek       | P5KC                        | [d20831473f](https://linux-hardware.org/?probe=d20831473f) | Mar 12, 2021 |
| HP            | 212B                        | [6afcf12073](https://linux-hardware.org/?probe=6afcf12073) | Mar 12, 2021 |
| Dell          | 0T656F A02                  | [cc36a18a02](https://linux-hardware.org/?probe=cc36a18a02) | Mar 12, 2021 |
| Acer          | Aspire TC-780               | [5ac5e5625a](https://linux-hardware.org/?probe=5ac5e5625a) | Mar 12, 2021 |
| MSI           | B450M MORTAR MAX            | [a4da5e59df](https://linux-hardware.org/?probe=a4da5e59df) | Mar 11, 2021 |
| ASUSTek       | PRIME H310M-D R2.0          | [5f4e258cd5](https://linux-hardware.org/?probe=5f4e258cd5) | Mar 11, 2021 |
| Gigabyte      | B450M DS3H-CF               | [0d5694c1b3](https://linux-hardware.org/?probe=0d5694c1b3) | Mar 10, 2021 |
| ASUSTek       | P5K Premium                 | [868aaae2fd](https://linux-hardware.org/?probe=868aaae2fd) | Mar 09, 2021 |
| HP            | 21B4 A01                    | [1b6837c321](https://linux-hardware.org/?probe=1b6837c321) | Mar 08, 2021 |
| HP            | 339A                        | [dd14e6b8f8](https://linux-hardware.org/?probe=dd14e6b8f8) | Mar 08, 2021 |
| Gigabyte      | 970-GAMING                  | [f05a49c047](https://linux-hardware.org/?probe=f05a49c047) | Mar 08, 2021 |
| ASUSTek       | P5K Premium                 | [551f3363c1](https://linux-hardware.org/?probe=551f3363c1) | Mar 07, 2021 |
| HP            | 212B                        | [acee068006](https://linux-hardware.org/?probe=acee068006) | Mar 06, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [32e4837219](https://linux-hardware.org/?probe=32e4837219) | Mar 05, 2021 |
| ASUSTek       | M2N68-AM Plus               | [18268633d9](https://linux-hardware.org/?probe=18268633d9) | Mar 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | [c4e5bc819d](https://linux-hardware.org/?probe=c4e5bc819d) | Mar 02, 2021 |
| Gigabyte      | A320M-H-CF                  | [bfa3a17409](https://linux-hardware.org/?probe=bfa3a17409) | Mar 02, 2021 |
| Gigabyte      | A320M-H-CF                  | [4b9649e87e](https://linux-hardware.org/?probe=4b9649e87e) | Mar 02, 2021 |
| Gigabyte      | M61PME-S2P                  | [39f661106f](https://linux-hardware.org/?probe=39f661106f) | Mar 01, 2021 |
| Unknown       | Intel X79                   | [85e2bda5cc](https://linux-hardware.org/?probe=85e2bda5cc) | Feb 28, 2021 |
| Unknown       | Intel X79                   | [cbe66f456c](https://linux-hardware.org/?probe=cbe66f456c) | Feb 28, 2021 |
| Acer          | Veriton X2611G V1.0         | [0f52aff29d](https://linux-hardware.org/?probe=0f52aff29d) | Feb 27, 2021 |
| ASRock        | A320M-HDV R4.0              | [9057e2fabf](https://linux-hardware.org/?probe=9057e2fabf) | Feb 27, 2021 |
| Acer          | Veriton X2611G V1.0         | [ba907b59a6](https://linux-hardware.org/?probe=ba907b59a6) | Feb 27, 2021 |
| ASUSTek       | Rampage V EXTREME           | [8912ddde77](https://linux-hardware.org/?probe=8912ddde77) | Feb 23, 2021 |
| ASUSTek       | P5K                         | [26b7e4d025](https://linux-hardware.org/?probe=26b7e4d025) | Feb 22, 2021 |
| Intel         | DP55WB AAE64798-204         | [6e9ac2a13d](https://linux-hardware.org/?probe=6e9ac2a13d) | Feb 20, 2021 |
| ASUSTek       | A4110                       | [26905e1ebd](https://linux-hardware.org/?probe=26905e1ebd) | Feb 19, 2021 |
| eMachines     | WMCP61M                     | [087382e171](https://linux-hardware.org/?probe=087382e171) | Feb 18, 2021 |
| eMachines     | WMCP61M                     | [a1a77aa715](https://linux-hardware.org/?probe=a1a77aa715) | Feb 18, 2021 |
| ASUSTek       | M5A78L/USB3                 | [10ee841597](https://linux-hardware.org/?probe=10ee841597) | Feb 17, 2021 |
| Biostar       | H61MLC                      | [be5a5130e5](https://linux-hardware.org/?probe=be5a5130e5) | Feb 17, 2021 |
| Gigabyte      | M68MT-S2P                   | [74f31779a2](https://linux-hardware.org/?probe=74f31779a2) | Feb 15, 2021 |
| Seco          | C40 C                       | [1d98beaf5d](https://linux-hardware.org/?probe=1d98beaf5d) | Feb 14, 2021 |
| ASUSTek       | M2N68-AM SE2                | [4679546f16](https://linux-hardware.org/?probe=4679546f16) | Feb 14, 2021 |
| Dell          | 0C27VV A01                  | [bd2590461c](https://linux-hardware.org/?probe=bd2590461c) | Feb 13, 2021 |
| Gateway       | SX2185                      | [650152fe14](https://linux-hardware.org/?probe=650152fe14) | Feb 12, 2021 |
| MSI           | Z87-G45 GAMING              | [232dc2ff7f](https://linux-hardware.org/?probe=232dc2ff7f) | Feb 09, 2021 |
| Lenovo        | ThinkCentre M58 8910B4U     | [1ac9efa4af](https://linux-hardware.org/?probe=1ac9efa4af) | Feb 08, 2021 |
| ASRock        | N68C-S UCC                  | [c35f0c5e8f](https://linux-hardware.org/?probe=c35f0c5e8f) | Feb 08, 2021 |
| Gigabyte      | B85M-HD3                    | [d4efd5185b](https://linux-hardware.org/?probe=d4efd5185b) | Feb 08, 2021 |
| MSI           | X470 GAMING PLUS            | [5e431277e8](https://linux-hardware.org/?probe=5e431277e8) | Feb 08, 2021 |
| MSI           | X470 GAMING PLUS            | [f487bd28cd](https://linux-hardware.org/?probe=f487bd28cd) | Feb 07, 2021 |
| ASUSTek       | P5G41-M LE                  | [760db7896e](https://linux-hardware.org/?probe=760db7896e) | Feb 07, 2021 |
| ASUSTek       | P5KPL-AM/PS                 | [da10acb66c](https://linux-hardware.org/?probe=da10acb66c) | Feb 07, 2021 |
| Gigabyte      | GA-78LMT-USB3 R2 sex        | [67b240fcfb](https://linux-hardware.org/?probe=67b240fcfb) | Feb 06, 2021 |
| Dell          | 0C2KJT A00                  | [cf78c04cc2](https://linux-hardware.org/?probe=cf78c04cc2) | Feb 06, 2021 |
| Dell          | 0C2KJT A00                  | [aeb4ab8839](https://linux-hardware.org/?probe=aeb4ab8839) | Feb 06, 2021 |
| ASUSTek       | P5VD2-MX                    | [f0f594baaf](https://linux-hardware.org/?probe=f0f594baaf) | Feb 04, 2021 |
| ASRock        | HM87-MXM                    | [95efd1e9a2](https://linux-hardware.org/?probe=95efd1e9a2) | Feb 04, 2021 |
| Apple         | Mac-F221BEC8                | [04273ebc86](https://linux-hardware.org/?probe=04273ebc86) | Feb 04, 2021 |
| Gigabyte      | EP45-UD3LR                  | [a3dadb268d](https://linux-hardware.org/?probe=a3dadb268d) | Feb 03, 2021 |
| AMI           | Cherry Trail CR             | [61c97edba3](https://linux-hardware.org/?probe=61c97edba3) | Feb 03, 2021 |
| HP            | 1589                        | [9f0f12f814](https://linux-hardware.org/?probe=9f0f12f814) | Jan 31, 2021 |
| Packard Be... | IMEDIA S3840                | [c0a7dff96d](https://linux-hardware.org/?probe=c0a7dff96d) | Jan 31, 2021 |
| Gigabyte      | GA-780T-D3L                 | [e745405951](https://linux-hardware.org/?probe=e745405951) | Jan 29, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [193f9e8bab](https://linux-hardware.org/?probe=193f9e8bab) | Jan 28, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | [c0dd8179cd](https://linux-hardware.org/?probe=c0dd8179cd) | Jan 28, 2021 |
| HP            | 18E5                        | [2a72f13e4c](https://linux-hardware.org/?probe=2a72f13e4c) | Jan 27, 2021 |
| Gigabyte      | F2A75M-HD2                  | [66c8d532cc](https://linux-hardware.org/?probe=66c8d532cc) | Jan 26, 2021 |
| Gigabyte      | F2A75M-HD2                  | [068a50df4d](https://linux-hardware.org/?probe=068a50df4d) | Jan 26, 2021 |
| ASRock        | B450 Pro4                   | [b78244d995](https://linux-hardware.org/?probe=b78244d995) | Jan 26, 2021 |
| NEC Comput... | IS8XM                       | [5ef77bc965](https://linux-hardware.org/?probe=5ef77bc965) | Jan 25, 2021 |
| NCR           | Pocono                      | [8bd94573e3](https://linux-hardware.org/?probe=8bd94573e3) | Jan 25, 2021 |
| Gigabyte      | X99-UD4-CF                  | [27d1050290](https://linux-hardware.org/?probe=27d1050290) | Jan 24, 2021 |
| HP            | 2AFE                        | [f9e753f06a](https://linux-hardware.org/?probe=f9e753f06a) | Jan 23, 2021 |
| MSI           | B85-G43                     | [4955170f6b](https://linux-hardware.org/?probe=4955170f6b) | Jan 23, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [a16e38020e](https://linux-hardware.org/?probe=a16e38020e) | Jan 23, 2021 |
| ASUSTek       | PRIME X470-PRO              | [bf6fd8e5ac](https://linux-hardware.org/?probe=bf6fd8e5ac) | Jan 22, 2021 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | [2f3b56a94e](https://linux-hardware.org/?probe=2f3b56a94e) | Jan 22, 2021 |
| MSI           | G41TM-E43                   | [2d830938bf](https://linux-hardware.org/?probe=2d830938bf) | Jan 21, 2021 |
| ASUSTek       | Z97-PRO GAMER               | [79ea9e0ea5](https://linux-hardware.org/?probe=79ea9e0ea5) | Jan 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | [8d943aea44](https://linux-hardware.org/?probe=8d943aea44) | Jan 21, 2021 |
| ASUSTek       | P8H61-MX USB3               | [5f6d7de9fe](https://linux-hardware.org/?probe=5f6d7de9fe) | Jan 20, 2021 |
| Dell          | 033FF6 A00                  | [37d767af07](https://linux-hardware.org/?probe=37d767af07) | Jan 20, 2021 |
| Intel         | DG31GL AAE33912-200         | [14491b53d7](https://linux-hardware.org/?probe=14491b53d7) | Jan 20, 2021 |
| Lenovo        | 30BE SDK0J40697 WIN 3305... | [cd75d76c4a](https://linux-hardware.org/?probe=cd75d76c4a) | Jan 19, 2021 |
| HP            | 18E5                        | [5af2f3397e](https://linux-hardware.org/?probe=5af2f3397e) | Jan 17, 2021 |
| ASL           | Fusion JHS652               | [446053ce45](https://linux-hardware.org/?probe=446053ce45) | Jan 17, 2021 |
| Google        | Zako                        | [dec016baf8](https://linux-hardware.org/?probe=dec016baf8) | Jan 17, 2021 |
| Dell          | 07PR60 A01                  | [c28e9c99eb](https://linux-hardware.org/?probe=c28e9c99eb) | Jan 17, 2021 |
| Dell          | 07PR60 A01                  | [d97f00549e](https://linux-hardware.org/?probe=d97f00549e) | Jan 17, 2021 |
| ASUSTek       | P8H61-M LX2                 | [81d37f44c6](https://linux-hardware.org/?probe=81d37f44c6) | Jan 16, 2021 |
| Acer          | Aspire XC-602 V1.0          | [f9111a7765](https://linux-hardware.org/?probe=f9111a7765) | Jan 16, 2021 |
| HP            | 2129                        | [449a9223a3](https://linux-hardware.org/?probe=449a9223a3) | Jan 15, 2021 |
| ASRock        | 880GM-LE                    | [21afeee128](https://linux-hardware.org/?probe=21afeee128) | Jan 11, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [0265add193](https://linux-hardware.org/?probe=0265add193) | Jan 10, 2021 |
| Gigabyte      | B450M DS3H-CF               | [8b0a9a71b3](https://linux-hardware.org/?probe=8b0a9a71b3) | Jan 10, 2021 |
| ASUSTek       | PRIME B350-PLUS             | [497bf4005e](https://linux-hardware.org/?probe=497bf4005e) | Jan 10, 2021 |
| ASUSTek       | P8Z77-V DELUXE              | [18722316d8](https://linux-hardware.org/?probe=18722316d8) | Jan 10, 2021 |
| ASRock        | X399 Professional Gaming    | [cc3cbc6c76](https://linux-hardware.org/?probe=cc3cbc6c76) | Jan 10, 2021 |
| Foxconn       | 2A92                        | [88f28ae2bf](https://linux-hardware.org/?probe=88f28ae2bf) | Jan 09, 2021 |
| HP            | 3648h                       | [95ce8ac6d8](https://linux-hardware.org/?probe=95ce8ac6d8) | Jan 09, 2021 |
| Foxconn       | 2A92                        | [4b75fd00b3](https://linux-hardware.org/?probe=4b75fd00b3) | Jan 09, 2021 |
| MSI           | MAG B550M MORTAR WIFI       | [e5a628c858](https://linux-hardware.org/?probe=e5a628c858) | Jan 09, 2021 |
| HP            | 2B46                        | [9fc7425e3d](https://linux-hardware.org/?probe=9fc7425e3d) | Jan 09, 2021 |
| Fujitsu       | D3643-H1 S26361-D3643-H1    | [f09e35f12c](https://linux-hardware.org/?probe=f09e35f12c) | Jan 08, 2021 |
| Acer          | Aspire XC-602 V1.0          | [0e8be5137f](https://linux-hardware.org/?probe=0e8be5137f) | Jan 08, 2021 |
| ASUSTek       | P5LD2-VM SE                 | [71eec0354c](https://linux-hardware.org/?probe=71eec0354c) | Jan 07, 2021 |
| HP            | 158A                        | [0539eeeeb8](https://linux-hardware.org/?probe=0539eeeeb8) | Jan 07, 2021 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [4a237e25c2](https://linux-hardware.org/?probe=4a237e25c2) | Jan 06, 2021 |
| Gigabyte      | EX58-UD4P                   | [391d558985](https://linux-hardware.org/?probe=391d558985) | Jan 06, 2021 |
| Dell          | 0RY007                      | [91aeb1441d](https://linux-hardware.org/?probe=91aeb1441d) | Jan 05, 2021 |
| Dell          | 0X501H A03                  | [64a89d74d6](https://linux-hardware.org/?probe=64a89d74d6) | Jan 05, 2021 |
| Acer          | WMCP78M                     | [c5a4dd4ee4](https://linux-hardware.org/?probe=c5a4dd4ee4) | Jan 04, 2021 |
| MSI           | B150M MORTAR                | [467cca1579](https://linux-hardware.org/?probe=467cca1579) | Jan 04, 2021 |
| Acer          | Aspire XC-602 V1.0          | [bb166b2faa](https://linux-hardware.org/?probe=bb166b2faa) | Jan 03, 2021 |
| Unknown       | Intel X79                   | [6184467f17](https://linux-hardware.org/?probe=6184467f17) | Jan 02, 2021 |
| MSI           | P55-CD53                    | [4d4128c3a2](https://linux-hardware.org/?probe=4d4128c3a2) | Jan 01, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | [403e79415b](https://linux-hardware.org/?probe=403e79415b) | Jan 01, 2021 |
| ASUSTek       | PRIME H370M-PLUS            | [120cc88a70](https://linux-hardware.org/?probe=120cc88a70) | Dec 31, 2020 |
| Dell          | 0K83V0 A00                  | [3bcb7a7dc7](https://linux-hardware.org/?probe=3bcb7a7dc7) | Dec 31, 2020 |
| Dell          | 07PR60 A01                  | [de6e7ceac7](https://linux-hardware.org/?probe=de6e7ceac7) | Dec 31, 2020 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [db7addea20](https://linux-hardware.org/?probe=db7addea20) | Dec 30, 2020 |
| ASUSTek       | H81M-P                      | [e532649d15](https://linux-hardware.org/?probe=e532649d15) | Dec 30, 2020 |
| Medion        | MS-7728                     | [1c026dd4cb](https://linux-hardware.org/?probe=1c026dd4cb) | Dec 29, 2020 |
| HP            | 2B29                        | [3161742f5a](https://linux-hardware.org/?probe=3161742f5a) | Dec 28, 2020 |
| Lenovo        | ThinkServer TS140           | [41ce3f2b0a](https://linux-hardware.org/?probe=41ce3f2b0a) | Dec 28, 2020 |
| MSI           | MS-B1831                    | [8aeb261956](https://linux-hardware.org/?probe=8aeb261956) | Dec 27, 2020 |
| Gigabyte      | H61M-S2PV                   | [9f886b4496](https://linux-hardware.org/?probe=9f886b4496) | Dec 27, 2020 |
| Lenovo        | ThinkServer TS140           | [96b3895113](https://linux-hardware.org/?probe=96b3895113) | Dec 26, 2020 |
| ASRock        | X570M Pro4                  | [6c57972a71](https://linux-hardware.org/?probe=6c57972a71) | Dec 26, 2020 |
| ASUSTek       | P8P67 LE                    | [627ed8e703](https://linux-hardware.org/?probe=627ed8e703) | Dec 25, 2020 |
| ASUSTek       | M4A88T-M                    | [67714f54b0](https://linux-hardware.org/?probe=67714f54b0) | Dec 25, 2020 |
| Foxconn       | 2ABF                        | [9f73be02e9](https://linux-hardware.org/?probe=9f73be02e9) | Dec 24, 2020 |
| MSI           | MS-B1831                    | [2ece565439](https://linux-hardware.org/?probe=2ece565439) | Dec 23, 2020 |
| ECS           | H110M-C3D/C3V               | [aa44a6674f](https://linux-hardware.org/?probe=aa44a6674f) | Dec 23, 2020 |
| Dell          | 0Y958C A00                  | [1a60b18b20](https://linux-hardware.org/?probe=1a60b18b20) | Dec 23, 2020 |
| HP            | 18E4                        | [2c5cdbbd62](https://linux-hardware.org/?probe=2c5cdbbd62) | Dec 23, 2020 |
| HP            | 2B34                        | [e0d288fe64](https://linux-hardware.org/?probe=e0d288fe64) | Dec 22, 2020 |
| Dell          | 0Y958C A00                  | [edd17e8864](https://linux-hardware.org/?probe=edd17e8864) | Dec 22, 2020 |
| Gigabyte      | M61PME-S2P                  | [51114c4b75](https://linux-hardware.org/?probe=51114c4b75) | Dec 22, 2020 |
| ASUSTek       | Z170-P                      | [53291d247a](https://linux-hardware.org/?probe=53291d247a) | Dec 21, 2020 |
| ECS           | nForce3-A                   | [0150835d63](https://linux-hardware.org/?probe=0150835d63) | Dec 21, 2020 |
| ECS           | nForce3-A                   | [c08a9c2d3a](https://linux-hardware.org/?probe=c08a9c2d3a) | Dec 21, 2020 |
| Unknown       | mqmaker MiQi                | [7113abee46](https://linux-hardware.org/?probe=7113abee46) | Dec 21, 2020 |
| HP            | 158A                        | [d48f153026](https://linux-hardware.org/?probe=d48f153026) | Dec 21, 2020 |
| Gigabyte      | F2A78M-HD2                  | [e30f78c281](https://linux-hardware.org/?probe=e30f78c281) | Dec 20, 2020 |
| ASUSTek       | M3N78-EMH HDMI              | [72db0d0125](https://linux-hardware.org/?probe=72db0d0125) | Dec 20, 2020 |
| ASUSTek       | M4A88T-M                    | [ee7d610e8e](https://linux-hardware.org/?probe=ee7d610e8e) | Dec 20, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS_BR     | [a129449d5f](https://linux-hardware.org/?probe=a129449d5f) | Dec 19, 2020 |
| Gigabyte      | GA-770T-D3L                 | [f819b316d4](https://linux-hardware.org/?probe=f819b316d4) | Dec 17, 2020 |
| ASUSTek       | Z170-P                      | [d99338778f](https://linux-hardware.org/?probe=d99338778f) | Dec 16, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [94b7599bed](https://linux-hardware.org/?probe=94b7599bed) | Dec 16, 2020 |
| Dell          | 03NVJ6 A01                  | [8226cd7051](https://linux-hardware.org/?probe=8226cd7051) | Dec 15, 2020 |
| ASUSTek       | Z170-P                      | [c70d8ca3f9](https://linux-hardware.org/?probe=c70d8ca3f9) | Dec 14, 2020 |
| ASUSTek       | H81M-K                      | [fb9204c5ef](https://linux-hardware.org/?probe=fb9204c5ef) | Dec 13, 2020 |
| Gigabyte      | J3455N-D3H                  | [a9a1ba9727](https://linux-hardware.org/?probe=a9a1ba9727) | Dec 13, 2020 |
| Foxconn       | 2ADA                        | [0b3c20a9d9](https://linux-hardware.org/?probe=0b3c20a9d9) | Dec 12, 2020 |
| Foxconn       | 2ADA                        | [1aedfd747c](https://linux-hardware.org/?probe=1aedfd747c) | Dec 12, 2020 |
| Gigabyte      | H110M-H-CF                  | [168e6322d7](https://linux-hardware.org/?probe=168e6322d7) | Dec 12, 2020 |
| ASUSTek       | P9X79 WS                    | [5a4110ac7b](https://linux-hardware.org/?probe=5a4110ac7b) | Dec 11, 2020 |
| Medion        | MS-7728                     | [e1af3f1d3c](https://linux-hardware.org/?probe=e1af3f1d3c) | Dec 08, 2020 |
| Gigabyte      | GA-MA785GM-US2H             | [f9f42752ca](https://linux-hardware.org/?probe=f9f42752ca) | Dec 07, 2020 |
| Dell          | 0Y958C A00                  | [8a8d020fab](https://linux-hardware.org/?probe=8a8d020fab) | Dec 07, 2020 |
| HP            | 2B29                        | [7a5d8033c4](https://linux-hardware.org/?probe=7a5d8033c4) | Dec 06, 2020 |
| ECS           | G31T-M7                     | [da86a0de6d](https://linux-hardware.org/?probe=da86a0de6d) | Dec 06, 2020 |
| HP            | 2B29                        | [0de16218a6](https://linux-hardware.org/?probe=0de16218a6) | Dec 04, 2020 |
| Dell          | 0Y958C A00                  | [8dc6bd07d9](https://linux-hardware.org/?probe=8dc6bd07d9) | Dec 02, 2020 |
| HP            | 304Ah                       | [e0127b5745](https://linux-hardware.org/?probe=e0127b5745) | Dec 02, 2020 |
| ASUSTek       | STRIX B250G GAMING          | [442ae34c4c](https://linux-hardware.org/?probe=442ae34c4c) | Dec 02, 2020 |
| ASRock        | B450M Pro4-F                | [1e395f258f](https://linux-hardware.org/?probe=1e395f258f) | Dec 01, 2020 |
| ASUSTek       | M4N68T-M LE                 | [f500a90ee5](https://linux-hardware.org/?probe=f500a90ee5) | Dec 01, 2020 |
| ASUSTek       | M4N68T-M LE                 | [edda2cb008](https://linux-hardware.org/?probe=edda2cb008) | Dec 01, 2020 |
| HP            | 2B29                        | [0f5898cf39](https://linux-hardware.org/?probe=0f5898cf39) | Nov 29, 2020 |
| MSI           | MS-7387                     | [c0b3272c7c](https://linux-hardware.org/?probe=c0b3272c7c) | Nov 29, 2020 |
| HP            | ProLiant ML370 G6           | [0c4b40cafd](https://linux-hardware.org/?probe=0c4b40cafd) | Nov 29, 2020 |
| ASRock        | 990FX Extreme4              | [2168e642ab](https://linux-hardware.org/?probe=2168e642ab) | Nov 29, 2020 |
| eMachines     | EL1352                      | [b7646b7bf3](https://linux-hardware.org/?probe=b7646b7bf3) | Nov 29, 2020 |
| Gigabyte      | H61M-D2H-USB3               | [5de3c42e69](https://linux-hardware.org/?probe=5de3c42e69) | Nov 28, 2020 |
| Gigabyte      | X570 AORUS ELITE            | [294c2bf2e7](https://linux-hardware.org/?probe=294c2bf2e7) | Nov 28, 2020 |
| Lenovo        | ThinkCentre M58 7360A24     | [44fbb2b2f8](https://linux-hardware.org/?probe=44fbb2b2f8) | Nov 27, 2020 |
| Lenovo        | ThinkCentre M58 7360A24     | [d45b996432](https://linux-hardware.org/?probe=d45b996432) | Nov 27, 2020 |
| Lenovo        | 36EB SDK0J40700 WIN 3258... | [2ff8c7a3f8](https://linux-hardware.org/?probe=2ff8c7a3f8) | Nov 26, 2020 |
| Dell          | 0GXM1W A02                  | [baca597036](https://linux-hardware.org/?probe=baca597036) | Nov 26, 2020 |
| Dell          | 0GXM1W A02                  | [06de0c3923](https://linux-hardware.org/?probe=06de0c3923) | Nov 25, 2020 |
| Intel         | DB85FL AAG89861-201         | [936daa5428](https://linux-hardware.org/?probe=936daa5428) | Nov 25, 2020 |
| ASRock        | 990FX Extreme4              | [deffb50091](https://linux-hardware.org/?probe=deffb50091) | Nov 23, 2020 |
| ASRock        | FM2A88X Extreme6+           | [0ddc71518c](https://linux-hardware.org/?probe=0ddc71518c) | Nov 22, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [7e1033e8f3](https://linux-hardware.org/?probe=7e1033e8f3) | Nov 22, 2020 |
| ASUSTek       | M4A78L-M                    | [2c715cff4c](https://linux-hardware.org/?probe=2c715cff4c) | Nov 22, 2020 |
| ASUSTek       | PRIME Z390-A                | [c5b35954b5](https://linux-hardware.org/?probe=c5b35954b5) | Nov 22, 2020 |
| ASUSTek       | M4A77T                      | [8f463afca3](https://linux-hardware.org/?probe=8f463afca3) | Nov 22, 2020 |
| ASUSTek       | M4A77T                      | [8e1b9c4d71](https://linux-hardware.org/?probe=8e1b9c4d71) | Nov 22, 2020 |
| Foxconn       | 2ABF                        | [fa95d7cd22](https://linux-hardware.org/?probe=fa95d7cd22) | Nov 21, 2020 |
| HP            | 3397                        | [8c4414f5e6](https://linux-hardware.org/?probe=8c4414f5e6) | Nov 20, 2020 |
| ASRock        | Q1900M                      | [2d0b876209](https://linux-hardware.org/?probe=2d0b876209) | Nov 20, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [90e2e642cf](https://linux-hardware.org/?probe=90e2e642cf) | Nov 18, 2020 |
| Gigabyte      | G41M-Combo                  | [34ac1118fc](https://linux-hardware.org/?probe=34ac1118fc) | Nov 18, 2020 |
| ASRock        | B450 Gaming K4              | [f900377694](https://linux-hardware.org/?probe=f900377694) | Nov 18, 2020 |
| ASUSTek       | H81M-P                      | [32ccf4d815](https://linux-hardware.org/?probe=32ccf4d815) | Nov 18, 2020 |
| Gigabyte      | G41M-Combo                  | [43fc3c5473](https://linux-hardware.org/?probe=43fc3c5473) | Nov 17, 2020 |
| Lenovo        | ThinkServer TS140           | [303ae16f51](https://linux-hardware.org/?probe=303ae16f51) | Nov 17, 2020 |
| Dell          | 0F6X5P A00                  | [c5ed241b08](https://linux-hardware.org/?probe=c5ed241b08) | Nov 16, 2020 |
| Dell          | 088DT1 A01                  | [ac8f81ddbc](https://linux-hardware.org/?probe=ac8f81ddbc) | Nov 15, 2020 |
| HP            | 18E5                        | [9da8cd466f](https://linux-hardware.org/?probe=9da8cd466f) | Nov 15, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [be10f2c608](https://linux-hardware.org/?probe=be10f2c608) | Nov 13, 2020 |
| MSI           | Z77A-G45                    | [f3741b744f](https://linux-hardware.org/?probe=f3741b744f) | Nov 13, 2020 |
| Dell          | 088DT1 A01                  | [6fe876bc14](https://linux-hardware.org/?probe=6fe876bc14) | Nov 13, 2020 |
| Lenovo        | MAHOBAY NO DPK              | [c79b58ba5b](https://linux-hardware.org/?probe=c79b58ba5b) | Nov 13, 2020 |
| ASUSTek       | PRIME X370-A                | [6618ea7285](https://linux-hardware.org/?probe=6618ea7285) | Nov 12, 2020 |
| Gigabyte      | GA-MA785GM-US2H             | [79ba5e5e77](https://linux-hardware.org/?probe=79ba5e5e77) | Nov 11, 2020 |
| Gigabyte      | EX58-UD4P                   | [d5dfd8ab5b](https://linux-hardware.org/?probe=d5dfd8ab5b) | Nov 10, 2020 |
| HP            | 0A00h                       | [5515bf006a](https://linux-hardware.org/?probe=5515bf006a) | Nov 08, 2020 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | [d584773eee](https://linux-hardware.org/?probe=d584773eee) | Nov 08, 2020 |
| Gigabyte      | GA-970A-DS3                 | [58a8f1077b](https://linux-hardware.org/?probe=58a8f1077b) | Nov 06, 2020 |
| Medion        | MS-7797                     | [7e6563d31c](https://linux-hardware.org/?probe=7e6563d31c) | Nov 06, 2020 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [424e7b661d](https://linux-hardware.org/?probe=424e7b661d) | Nov 06, 2020 |
| Apple         | Mac-F221BEC8                | [ac6556242f](https://linux-hardware.org/?probe=ac6556242f) | Nov 06, 2020 |
| Apple         | Mac-F221BEC8                | [56d223bda7](https://linux-hardware.org/?probe=56d223bda7) | Nov 06, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [233cd75348](https://linux-hardware.org/?probe=233cd75348) | Nov 05, 2020 |
| Intel         | H61                         | [071d57e367](https://linux-hardware.org/?probe=071d57e367) | Nov 05, 2020 |
| NEC Comput... | IS8XM                       | [ca22c03b0e](https://linux-hardware.org/?probe=ca22c03b0e) | Nov 04, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f27791145e](https://linux-hardware.org/?probe=f27791145e) | Nov 03, 2020 |
| ASRock        | HM87-MXM                    | [d47723e369](https://linux-hardware.org/?probe=d47723e369) | Nov 03, 2020 |
| ASRock        | A300M-STX                   | [d16cbe4e3e](https://linux-hardware.org/?probe=d16cbe4e3e) | Nov 03, 2020 |
| Gigabyte      | X570 UD                     | [607e02b996](https://linux-hardware.org/?probe=607e02b996) | Nov 02, 2020 |
| HP            | 0A58h                       | [796cd4ef09](https://linux-hardware.org/?probe=796cd4ef09) | Nov 02, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [55c65411a0](https://linux-hardware.org/?probe=55c65411a0) | Nov 01, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [9f09e4b2e0](https://linux-hardware.org/?probe=9f09e4b2e0) | Nov 01, 2020 |
| ASUSTek       | M5A99FX PRO R2.0            | [8e7396c5f2](https://linux-hardware.org/?probe=8e7396c5f2) | Nov 01, 2020 |
| Gigabyte      | B150M-D3H-CF                | [57d7a8f5f7](https://linux-hardware.org/?probe=57d7a8f5f7) | Oct 31, 2020 |
| HP            | 3397                        | [cf461d2903](https://linux-hardware.org/?probe=cf461d2903) | Oct 31, 2020 |
| ASUSTek       | M4A785-M                    | [af85b28568](https://linux-hardware.org/?probe=af85b28568) | Oct 31, 2020 |
| HP            | 304Ah                       | [ebc4ca37d5](https://linux-hardware.org/?probe=ebc4ca37d5) | Oct 30, 2020 |
| Dell          | 04GJJT A00                  | [fc31c33025](https://linux-hardware.org/?probe=fc31c33025) | Oct 30, 2020 |
| ASUSTek       | P5KPL-AM SE                 | [b916a2471b](https://linux-hardware.org/?probe=b916a2471b) | Oct 29, 2020 |
| Foxconn       | 2AB1h                       | [dd42a7e94c](https://linux-hardware.org/?probe=dd42a7e94c) | Oct 29, 2020 |
| ASUSTek       | H87M-PLUS                   | [7df4485d80](https://linux-hardware.org/?probe=7df4485d80) | Oct 28, 2020 |
| Foxconn       | 2ABF                        | [98e0846229](https://linux-hardware.org/?probe=98e0846229) | Oct 28, 2020 |
| Dell          | 0K83V0 A00                  | [caa3f7d5c2](https://linux-hardware.org/?probe=caa3f7d5c2) | Oct 27, 2020 |
| Dell          | 0K83V0 A00                  | [8fc67df632](https://linux-hardware.org/?probe=8fc67df632) | Oct 27, 2020 |
| ASUSTek       | PRIME B360M-A               | [f52d2d566a](https://linux-hardware.org/?probe=f52d2d566a) | Oct 27, 2020 |
| HP            | 3397                        | [0c7f93cb53](https://linux-hardware.org/?probe=0c7f93cb53) | Oct 26, 2020 |
| Dell          | 0Y5DDC A00                  | [4a6901b354](https://linux-hardware.org/?probe=4a6901b354) | Oct 25, 2020 |
| Gigabyte      | Z170-HD3P-CF                | [e3920e0ddd](https://linux-hardware.org/?probe=e3920e0ddd) | Oct 24, 2020 |
| Dell          | 0X9M3X A03                  | [0fbdc774f7](https://linux-hardware.org/?probe=0fbdc774f7) | Oct 23, 2020 |
| ASRock        | N68C-S UCC                  | [e8b5a5c6c1](https://linux-hardware.org/?probe=e8b5a5c6c1) | Oct 22, 2020 |
| ASRock        | 970 Extreme3 R2.0           | [e9eab6369f](https://linux-hardware.org/?probe=e9eab6369f) | Oct 22, 2020 |
| ASRock        | 970 Extreme3 R2.0           | [ee3c78e7f9](https://linux-hardware.org/?probe=ee3c78e7f9) | Oct 22, 2020 |
| HP            | 18E7                        | [9b75d72659](https://linux-hardware.org/?probe=9b75d72659) | Oct 21, 2020 |
| MSI           | B85M-E45                    | [7d562c5a0b](https://linux-hardware.org/?probe=7d562c5a0b) | Oct 21, 2020 |
| HP            | 1589                        | [97e2a8328c](https://linux-hardware.org/?probe=97e2a8328c) | Oct 21, 2020 |
| HP            | 1589                        | [c01a481fe5](https://linux-hardware.org/?probe=c01a481fe5) | Oct 21, 2020 |
| Intel         | DH55HC AAE70933-501         | [6542fc1f81](https://linux-hardware.org/?probe=6542fc1f81) | Oct 20, 2020 |
| Lenovo        | ThinkServer TS140           | [cc871fe1eb](https://linux-hardware.org/?probe=cc871fe1eb) | Oct 20, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8892c91b74](https://linux-hardware.org/?probe=8892c91b74) | Oct 19, 2020 |
| ASRock        | N68C-S UCC                  | [2c05125698](https://linux-hardware.org/?probe=2c05125698) | Oct 19, 2020 |
| Intel         | DH67CF AAG10215-207         | [bdad9ec53e](https://linux-hardware.org/?probe=bdad9ec53e) | Oct 18, 2020 |
| ASRock        | N68C-GS FX                  | [9e5b81cf31](https://linux-hardware.org/?probe=9e5b81cf31) | Oct 17, 2020 |
| HP            | 82F2 A01                    | [9f775578b2](https://linux-hardware.org/?probe=9f775578b2) | Oct 17, 2020 |
| ASUSTek       | M4A78LT-M                   | [05d6ef0ede](https://linux-hardware.org/?probe=05d6ef0ede) | Oct 17, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [877be0d702](https://linux-hardware.org/?probe=877be0d702) | Oct 16, 2020 |
| ASRock        | X570 Phantom Gaming-ITX/... | [10afcab1dd](https://linux-hardware.org/?probe=10afcab1dd) | Oct 16, 2020 |
| Itautec       | ST 4265 ST-4265 Padrao 0... | [4c66a9acab](https://linux-hardware.org/?probe=4c66a9acab) | Oct 16, 2020 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [cacf226be4](https://linux-hardware.org/?probe=cacf226be4) | Oct 16, 2020 |
| HP            | 3397                        | [33fdc768a1](https://linux-hardware.org/?probe=33fdc768a1) | Oct 15, 2020 |
| ASRock        | 970 Extreme4                | [da013f2159](https://linux-hardware.org/?probe=da013f2159) | Oct 15, 2020 |
| ASRock        | A320M-HDV R4.0              | [753273ae7d](https://linux-hardware.org/?probe=753273ae7d) | Oct 14, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [aea7dc9a63](https://linux-hardware.org/?probe=aea7dc9a63) | Oct 14, 2020 |
| ASRock        | 990FX Professional          | [97ce7ab2bc](https://linux-hardware.org/?probe=97ce7ab2bc) | Oct 12, 2020 |
| ASUSTek       | P8H61-M LX2                 | [ec63552e89](https://linux-hardware.org/?probe=ec63552e89) | Oct 11, 2020 |
| ASUSTek       | M5A78L-M/USB3               | [964d90f42f](https://linux-hardware.org/?probe=964d90f42f) | Oct 11, 2020 |
| Lenovo        | MAHOBAY                     | [6427fb47dd](https://linux-hardware.org/?probe=6427fb47dd) | Oct 10, 2020 |
| Dell          | 096JG8 A01                  | [1c591aa639](https://linux-hardware.org/?probe=1c591aa639) | Oct 10, 2020 |
| HP            | 1495                        | [95e7609af2](https://linux-hardware.org/?probe=95e7609af2) | Oct 10, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [19ef25af06](https://linux-hardware.org/?probe=19ef25af06) | Oct 09, 2020 |
| MSI           | B450M-A PRO MAX             | [3712afebf5](https://linux-hardware.org/?probe=3712afebf5) | Oct 09, 2020 |
| HP            | 304Ah                       | [c05b24bee0](https://linux-hardware.org/?probe=c05b24bee0) | Oct 09, 2020 |
| HP            | 0A64h                       | [83fa351a56](https://linux-hardware.org/?probe=83fa351a56) | Oct 07, 2020 |
| MSI           | 970A-G46                    | [299e4a7770](https://linux-hardware.org/?probe=299e4a7770) | Oct 07, 2020 |
| Gigabyte      | P55M-UD2                    | [cf07ea3801](https://linux-hardware.org/?probe=cf07ea3801) | Oct 05, 2020 |
| MSI           | A68HM-E33 V2                | [a88be898c1](https://linux-hardware.org/?probe=a88be898c1) | Oct 05, 2020 |
| MSI           | MEG X570 ACE                | [707d8920a5](https://linux-hardware.org/?probe=707d8920a5) | Oct 04, 2020 |
| HP            | 0A64h                       | [212a85da51](https://linux-hardware.org/?probe=212a85da51) | Oct 04, 2020 |
| Dell          | 0TP406                      | [b9e8cd1651](https://linux-hardware.org/?probe=b9e8cd1651) | Oct 04, 2020 |
| ASUSTek       | M5A78L-M LX V2              | [8174433592](https://linux-hardware.org/?probe=8174433592) | Oct 04, 2020 |
| ASUSTek       | Z170 PRO GAMING             | [3c907dd84e](https://linux-hardware.org/?probe=3c907dd84e) | Oct 03, 2020 |
| Gigabyte      | Z97X-Gaming 3               | [b1aeaa645b](https://linux-hardware.org/?probe=b1aeaa645b) | Oct 03, 2020 |
| Gigabyte      | Z97X-Gaming 3               | [45bfa5eb3c](https://linux-hardware.org/?probe=45bfa5eb3c) | Oct 03, 2020 |
| HP            | 82F2 A01                    | [624aa6976f](https://linux-hardware.org/?probe=624aa6976f) | Oct 02, 2020 |
| Dell          | 0PU052                      | [e2e65a1fa7](https://linux-hardware.org/?probe=e2e65a1fa7) | Oct 02, 2020 |
| ASRock        | N68C-S UCC                  | [b82b064a51](https://linux-hardware.org/?probe=b82b064a51) | Oct 02, 2020 |
| ASUSTek       | P5K                         | [c1c290f102](https://linux-hardware.org/?probe=c1c290f102) | Oct 02, 2020 |
| Dell          | 0M863N A00                  | [4ffc77e348](https://linux-hardware.org/?probe=4ffc77e348) | Oct 02, 2020 |
| Dell          | 0M863N A00                  | [3719f7c699](https://linux-hardware.org/?probe=3719f7c699) | Oct 02, 2020 |
| ASUSTek       | Z87-A                       | [63e9e30049](https://linux-hardware.org/?probe=63e9e30049) | Oct 02, 2020 |
| Intel         | DG41TX AAE78178-303         | [2ba4c11c35](https://linux-hardware.org/?probe=2ba4c11c35) | Oct 02, 2020 |
| Dell          | 0WR7PY A02                  | [44ffa409aa](https://linux-hardware.org/?probe=44ffa409aa) | Oct 01, 2020 |
| ASUSTek       | H87M-PLUS                   | [07387013eb](https://linux-hardware.org/?probe=07387013eb) | Sep 30, 2020 |
| HP            | 1495                        | [0b848e88ef](https://linux-hardware.org/?probe=0b848e88ef) | Sep 30, 2020 |
| Unknown       | Unknown                     | [4ebc73788d](https://linux-hardware.org/?probe=4ebc73788d) | Sep 29, 2020 |
| MSI           | X470 GAMING PLUS            | [cfb285ef78](https://linux-hardware.org/?probe=cfb285ef78) | Sep 29, 2020 |
| ASUSTek       | PRIME B450M-A               | [0f6dc81b18](https://linux-hardware.org/?probe=0f6dc81b18) | Sep 29, 2020 |
| MSI           | X570-A PRO                  | [601b9c7dcf](https://linux-hardware.org/?probe=601b9c7dcf) | Sep 29, 2020 |
| Gigabyte      | H61M-S2PV                   | [97d6fcdf95](https://linux-hardware.org/?probe=97d6fcdf95) | Sep 28, 2020 |
| ASUSTek       | P5KPL-AM                    | [d42399006f](https://linux-hardware.org/?probe=d42399006f) | Sep 27, 2020 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [30a2037cce](https://linux-hardware.org/?probe=30a2037cce) | Sep 26, 2020 |
| Intel         | H61                         | [0ddeefc2fc](https://linux-hardware.org/?probe=0ddeefc2fc) | Sep 26, 2020 |
| HP            | 0AA8h                       | [244549772f](https://linux-hardware.org/?probe=244549772f) | Sep 25, 2020 |
| Intel         | H61                         | [87b485d42f](https://linux-hardware.org/?probe=87b485d42f) | Sep 25, 2020 |
| Lenovo        | MAHOBAY NOK                 | [052bf49b84](https://linux-hardware.org/?probe=052bf49b84) | Sep 25, 2020 |
| HP            | 0AA8h                       | [80cbff87bd](https://linux-hardware.org/?probe=80cbff87bd) | Sep 24, 2020 |
| ASUSTek       | M5A78L-M LX V2              | [918e747daf](https://linux-hardware.org/?probe=918e747daf) | Sep 24, 2020 |
| Gigabyte      | B450M DS3H-CF               | [c52887d7df](https://linux-hardware.org/?probe=c52887d7df) | Sep 24, 2020 |
| Dell          | 02K9CR A01                  | [c2e31c7ce8](https://linux-hardware.org/?probe=c2e31c7ce8) | Sep 24, 2020 |
| Positivo      | POS-AG31AP                  | [9dc1ba771f](https://linux-hardware.org/?probe=9dc1ba771f) | Sep 23, 2020 |
| Dell          | 0F6X5P A00                  | [a1cbd8f918](https://linux-hardware.org/?probe=a1cbd8f918) | Sep 23, 2020 |
| Dell          | 0X501H A03                  | [ebeee4544c](https://linux-hardware.org/?probe=ebeee4544c) | Sep 22, 2020 |
| Dell          | 0F6X5P A00                  | [0b548f3a3f](https://linux-hardware.org/?probe=0b548f3a3f) | Sep 22, 2020 |
| Dell          | 0X501H A03                  | [4a8ba3857a](https://linux-hardware.org/?probe=4a8ba3857a) | Sep 21, 2020 |
| Acer          | Aspire X3400G               | [80fdbf7a1b](https://linux-hardware.org/?probe=80fdbf7a1b) | Sep 20, 2020 |
| ASUSTek       | A88XM-PLUS                  | [bdae1a68a5](https://linux-hardware.org/?probe=bdae1a68a5) | Sep 18, 2020 |
| ASRock        | X99 WS-E/10G                | [cd3238583f](https://linux-hardware.org/?probe=cd3238583f) | Sep 17, 2020 |
| ASRock        | X99 WS-E/10G                | [bf1047170e](https://linux-hardware.org/?probe=bf1047170e) | Sep 16, 2020 |
| HP            | 1495                        | [94de1a6e23](https://linux-hardware.org/?probe=94de1a6e23) | Sep 16, 2020 |
| PCWare        | IPMH310G                    | [7231f076bd](https://linux-hardware.org/?probe=7231f076bd) | Sep 15, 2020 |
| PCWare        | IPMH310G                    | [181e5467d9](https://linux-hardware.org/?probe=181e5467d9) | Sep 15, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [2399ed18fd](https://linux-hardware.org/?probe=2399ed18fd) | Sep 14, 2020 |
| ASUSTek       | P6X58D-E                    | [09428a86cd](https://linux-hardware.org/?probe=09428a86cd) | Sep 14, 2020 |
| ASUSTek       | P5KPL-AM                    | [3f22ea2e15](https://linux-hardware.org/?probe=3f22ea2e15) | Sep 13, 2020 |
| ECS           | G31T-M7                     | [70c5208ec6](https://linux-hardware.org/?probe=70c5208ec6) | Sep 13, 2020 |
| Lenovo        | ThinkCentre M58p 6234DK6    | [f8dc9acb3f](https://linux-hardware.org/?probe=f8dc9acb3f) | Sep 13, 2020 |
| Lenovo        | ThinkCentre M58p 6234DK6    | [9f4325cb06](https://linux-hardware.org/?probe=9f4325cb06) | Sep 13, 2020 |
| Dell          | 0WG864                      | [fa12f9413f](https://linux-hardware.org/?probe=fa12f9413f) | Sep 12, 2020 |
| ASUSTek       | P5Q DELUXE                  | [960c7e17db](https://linux-hardware.org/?probe=960c7e17db) | Sep 12, 2020 |
| Dell          | 0WG864                      | [456382938e](https://linux-hardware.org/?probe=456382938e) | Sep 12, 2020 |
| ASRock        | X79 Extreme4                | [7cd6a3625c](https://linux-hardware.org/?probe=7cd6a3625c) | Sep 10, 2020 |
| ASUSTek       | P8H61-M LE                  | [4fdffb335a](https://linux-hardware.org/?probe=4fdffb335a) | Sep 08, 2020 |
| ASUSTek       | P8H61-M LE                  | [7c9c74b288](https://linux-hardware.org/?probe=7c9c74b288) | Sep 08, 2020 |
| Lenovo        | ThinkStation D20 4158CM1    | [a6077c212e](https://linux-hardware.org/?probe=a6077c212e) | Sep 08, 2020 |
| ASUSTek       | H87-PLUS                    | [ad2897518b](https://linux-hardware.org/?probe=ad2897518b) | Sep 08, 2020 |
| ASRock        | ALiveNF6P-VSTA              | [dd876ba784](https://linux-hardware.org/?probe=dd876ba784) | Sep 08, 2020 |
| ASRock        | ALiveNF6P-VSTA              | [42997fd9bd](https://linux-hardware.org/?probe=42997fd9bd) | Sep 08, 2020 |
| HP            | 339A                        | [109949681c](https://linux-hardware.org/?probe=109949681c) | Sep 06, 2020 |
| Dell          | 0200DY A02                  | [cfe26c9023](https://linux-hardware.org/?probe=cfe26c9023) | Sep 05, 2020 |
| ASRock        | Z87E-ITX                    | [d1095a7a24](https://linux-hardware.org/?probe=d1095a7a24) | Sep 05, 2020 |
| ASUSTek       | PRIME B450M-A               | [d4d40f1808](https://linux-hardware.org/?probe=d4d40f1808) | Sep 04, 2020 |
| ASUSTek       | H87-PLUS                    | [1602fc1f70](https://linux-hardware.org/?probe=1602fc1f70) | Sep 04, 2020 |
| MSI           | Z77A-G45                    | [278850fdd4](https://linux-hardware.org/?probe=278850fdd4) | Sep 04, 2020 |
| Medion        | MS-7797                     | [cae7e7f201](https://linux-hardware.org/?probe=cae7e7f201) | Sep 04, 2020 |
| ASRock        | Q2900-ITX                   | [1707f849a6](https://linux-hardware.org/?probe=1707f849a6) | Sep 04, 2020 |
| Dell          | 0Y5DDC A00                  | [beef376967](https://linux-hardware.org/?probe=beef376967) | Sep 04, 2020 |
| Medion        | MS-7708                     | [c58e461f9d](https://linux-hardware.org/?probe=c58e461f9d) | Sep 03, 2020 |
| MSI           | X570-A PRO                  | [18e8b1b893](https://linux-hardware.org/?probe=18e8b1b893) | Sep 03, 2020 |
| ASRock        | B450 Pro4                   | [4b4eb09724](https://linux-hardware.org/?probe=4b4eb09724) | Sep 03, 2020 |
| Acer          | Batman A01                  | [e9d0e3d9d4](https://linux-hardware.org/?probe=e9d0e3d9d4) | Sep 02, 2020 |
| ASRock        | TRX40 Creator               | [e8bbe1674e](https://linux-hardware.org/?probe=e8bbe1674e) | Sep 01, 2020 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | [89e7ddc6ec](https://linux-hardware.org/?probe=89e7ddc6ec) | Sep 01, 2020 |
| Medion        | MS-7857                     | [9ab3e2ae3f](https://linux-hardware.org/?probe=9ab3e2ae3f) | Aug 31, 2020 |
| Shuttle       | FH87                        | [087c5627a0](https://linux-hardware.org/?probe=087c5627a0) | Aug 30, 2020 |
| Medion        | MS-7857                     | [311d3d4895](https://linux-hardware.org/?probe=311d3d4895) | Aug 30, 2020 |
| Dell          | 0JC474                      | [0f799b70a5](https://linux-hardware.org/?probe=0f799b70a5) | Aug 29, 2020 |
| ASRock        | H170M Pro4                  | [10d84618d9](https://linux-hardware.org/?probe=10d84618d9) | Aug 29, 2020 |
| MSI           | B450M-A PRO MAX             | [e46d6617a9](https://linux-hardware.org/?probe=e46d6617a9) | Aug 28, 2020 |
| ASUSTek       | M4A78LT-M                   | [cae2109038](https://linux-hardware.org/?probe=cae2109038) | Aug 27, 2020 |
| ASUSTek       | ET1612I                     | [9cc05b2a9e](https://linux-hardware.org/?probe=9cc05b2a9e) | Aug 27, 2020 |
| ASRock        | B85 Pro4                    | [b75833748d](https://linux-hardware.org/?probe=b75833748d) | Aug 26, 2020 |
| ASUSTek       | X99-E                       | [c3e2a36b7e](https://linux-hardware.org/?probe=c3e2a36b7e) | Aug 25, 2020 |
| NCR           | Pocono                      | [96fac7c428](https://linux-hardware.org/?probe=96fac7c428) | Aug 25, 2020 |
| ASUSTek       | ET1612I                     | [a69dacee1d](https://linux-hardware.org/?probe=a69dacee1d) | Aug 24, 2020 |
| Gigabyte      | P61-USB3-B3                 | [9ecd34fe2e](https://linux-hardware.org/?probe=9ecd34fe2e) | Aug 24, 2020 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | [00834d5b62](https://linux-hardware.org/?probe=00834d5b62) | Aug 23, 2020 |
| MSI           | MS-B0501 100                | [12c7b9ccc6](https://linux-hardware.org/?probe=12c7b9ccc6) | Aug 22, 2020 |
| ASRock        | FM2A88M Extreme4+           | [bc5631611b](https://linux-hardware.org/?probe=bc5631611b) | Aug 21, 2020 |
| Gigabyte      | M68MT-S2                    | [da3fea7987](https://linux-hardware.org/?probe=da3fea7987) | Aug 21, 2020 |
| Dell          | 0PU052                      | [ad5edd5c3c](https://linux-hardware.org/?probe=ad5edd5c3c) | Aug 21, 2020 |
| MSI           | B450 TOMAHAWK MAX           | [532be87782](https://linux-hardware.org/?probe=532be87782) | Aug 20, 2020 |
| Dell          | 096JG8 A01                  | [76d74f26bd](https://linux-hardware.org/?probe=76d74f26bd) | Aug 20, 2020 |
| HP            | 3397                        | [fcdcfc7812](https://linux-hardware.org/?probe=fcdcfc7812) | Aug 20, 2020 |
| MSI           | B350 TOMAHAWK               | [d4c9b039ff](https://linux-hardware.org/?probe=d4c9b039ff) | Aug 20, 2020 |
| Dell          | 096JG8 A01                  | [083a1b24a2](https://linux-hardware.org/?probe=083a1b24a2) | Aug 20, 2020 |
| Dell          | 096JG8 A01                  | [b2e7162b8f](https://linux-hardware.org/?probe=b2e7162b8f) | Aug 19, 2020 |
| ASRock        | B450M Pro4                  | [49081ef429](https://linux-hardware.org/?probe=49081ef429) | Aug 19, 2020 |
| Biostar       | G41-M7                      | [dc33e9b8b5](https://linux-hardware.org/?probe=dc33e9b8b5) | Aug 18, 2020 |
| Biostar       | G41-M7                      | [c9bd27ee3c](https://linux-hardware.org/?probe=c9bd27ee3c) | Aug 18, 2020 |
| Fujitsu       | D3091-A1 S26361-D3091-A1    | [ea5ade72ff](https://linux-hardware.org/?probe=ea5ade72ff) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | [24c499fe18](https://linux-hardware.org/?probe=24c499fe18) | Aug 17, 2020 |
| Foxconn       | 2ABF                        | [1fbfbf3d96](https://linux-hardware.org/?probe=1fbfbf3d96) | Aug 17, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [dfd46d88c4](https://linux-hardware.org/?probe=dfd46d88c4) | Aug 16, 2020 |
| MSI           | E350DM-E33                  | [67f718b80b](https://linux-hardware.org/?probe=67f718b80b) | Aug 16, 2020 |
| MSI           | E350DM-E33                  | [df8f51adcb](https://linux-hardware.org/?probe=df8f51adcb) | Aug 16, 2020 |
| Gigabyte      | M68MT-S2                    | [064e495c95](https://linux-hardware.org/?probe=064e495c95) | Aug 16, 2020 |
| Gigabyte      | M68MT-S2                    | [cdeea77503](https://linux-hardware.org/?probe=cdeea77503) | Aug 16, 2020 |
| Dell          | 0PU052                      | [f7616a2cae](https://linux-hardware.org/?probe=f7616a2cae) | Aug 16, 2020 |
| Gigabyte      | P35T-DQ6                    | [5a25041427](https://linux-hardware.org/?probe=5a25041427) | Aug 15, 2020 |
| Pegatron      | IPM41-D3                    | [e51377d34f](https://linux-hardware.org/?probe=e51377d34f) | Aug 14, 2020 |
| HP            | 0B4Ch D                     | [fe39d25754](https://linux-hardware.org/?probe=fe39d25754) | Aug 11, 2020 |
| ASUSTek       | P7P55 LX                    | [c40dc64451](https://linux-hardware.org/?probe=c40dc64451) | Aug 11, 2020 |
| ASUSTek       | PRIME A320M-K/BR            | [09d2e03b31](https://linux-hardware.org/?probe=09d2e03b31) | Aug 11, 2020 |
| ASUSTek       | TUF Gaming X570-PLUS        | [437b159ba3](https://linux-hardware.org/?probe=437b159ba3) | Aug 10, 2020 |
| HP            | 1998                        | [98779de9f0](https://linux-hardware.org/?probe=98779de9f0) | Aug 09, 2020 |
| Dell          | 0RW199                      | [5d2cb2e44b](https://linux-hardware.org/?probe=5d2cb2e44b) | Aug 09, 2020 |
| Dell          | 0JC474                      | [f7f2128996](https://linux-hardware.org/?probe=f7f2128996) | Aug 08, 2020 |
| ASRock        | N68C-S UCC                  | [0c80b9688e](https://linux-hardware.org/?probe=0c80b9688e) | Aug 08, 2020 |
| ASRock        | N68C-S UCC                  | [28a4ff7761](https://linux-hardware.org/?probe=28a4ff7761) | Aug 07, 2020 |
| MSI           | X470 GAMING PLUS            | [9708e21a27](https://linux-hardware.org/?probe=9708e21a27) | Aug 07, 2020 |
| Intel         | MAHOBAY                     | [c0dde75b94](https://linux-hardware.org/?probe=c0dde75b94) | Aug 06, 2020 |
| ASRock        | Z68 Extreme3 Gen3           | [ab2cdb31ec](https://linux-hardware.org/?probe=ab2cdb31ec) | Aug 05, 2020 |
| Dell          | 0RY206                      | [52b96832f5](https://linux-hardware.org/?probe=52b96832f5) | Aug 05, 2020 |
| Dell          | 0RY206                      | [fea85531ff](https://linux-hardware.org/?probe=fea85531ff) | Aug 05, 2020 |
| Dell          | 0200DY A02                  | [88fc41cab0](https://linux-hardware.org/?probe=88fc41cab0) | Aug 01, 2020 |
| Dell          | 0200DY A02                  | [6ce85894b6](https://linux-hardware.org/?probe=6ce85894b6) | Aug 01, 2020 |
| ASUSTek       | P8P67 PRO                   | [2a5cd28ee2](https://linux-hardware.org/?probe=2a5cd28ee2) | Aug 01, 2020 |
| MSI           | A75MA-G55                   | [f6e27145ee](https://linux-hardware.org/?probe=f6e27145ee) | Aug 01, 2020 |
| Dell          | 0RW199                      | [336760aa9b](https://linux-hardware.org/?probe=336760aa9b) | Jul 31, 2020 |
| Intel         | MAHOBAY                     | [f79f3b002e](https://linux-hardware.org/?probe=f79f3b002e) | Jul 31, 2020 |
| Dell          | 0VNP2H A02                  | [def480a828](https://linux-hardware.org/?probe=def480a828) | Jul 29, 2020 |
| Dell          | 0M863N A00                  | [0359c45784](https://linux-hardware.org/?probe=0359c45784) | Jul 29, 2020 |
| Dell          | 0M863N A00                  | [6b435bdcb8](https://linux-hardware.org/?probe=6b435bdcb8) | Jul 29, 2020 |
| Acer          | EQ35M                       | [0a38bdbb37](https://linux-hardware.org/?probe=0a38bdbb37) | Jul 29, 2020 |
| ASRock        | G41M-VS3                    | [bfa97b70c7](https://linux-hardware.org/?probe=bfa97b70c7) | Jul 29, 2020 |
| Intel         | DG31PR AAD97573-302         | [56ad5a6a22](https://linux-hardware.org/?probe=56ad5a6a22) | Jul 29, 2020 |
| ASRock        | FM2A88M Extreme4+           | [94a586edcd](https://linux-hardware.org/?probe=94a586edcd) | Jul 28, 2020 |
| Positivo      | POS-PIG41BO POSITIVO        | [c815c1ad30](https://linux-hardware.org/?probe=c815c1ad30) | Jul 27, 2020 |
| Medion        | B360H4-EM V1.0              | [26e62910da](https://linux-hardware.org/?probe=26e62910da) | Jul 26, 2020 |
| Gigabyte      | GA-78LMT-USB3 SEx           | [5e834a1db4](https://linux-hardware.org/?probe=5e834a1db4) | Jul 26, 2020 |
| Gigabyte      | B365M D3H-CF                | [d573d41540](https://linux-hardware.org/?probe=d573d41540) | Jul 25, 2020 |
| Intel         | DG31PR AAD97573-302         | [8081f20c91](https://linux-hardware.org/?probe=8081f20c91) | Jul 25, 2020 |
| HP            | 1497                        | [ef31cca294](https://linux-hardware.org/?probe=ef31cca294) | Jul 25, 2020 |
| Positivo      | POS-MI945AA                 | [70488a83b5](https://linux-hardware.org/?probe=70488a83b5) | Jul 25, 2020 |
| Gigabyte      | GA-78LMT-S2                 | [71c07410ee](https://linux-hardware.org/?probe=71c07410ee) | Jul 25, 2020 |
| Gigabyte      | F2A78M-HD2                  | [25ca74bc56](https://linux-hardware.org/?probe=25ca74bc56) | Jul 24, 2020 |
| MSI           | G31TM-P35                   | [956c575a24](https://linux-hardware.org/?probe=956c575a24) | Jul 24, 2020 |
| Toshiba       | STI 910133                  | [21c7264a49](https://linux-hardware.org/?probe=21c7264a49) | Jul 24, 2020 |
| ASUSTek       | PRIME B250M-PLUS/BR         | [974995c15c](https://linux-hardware.org/?probe=974995c15c) | Jul 24, 2020 |
| ASRock        | A320M-HD                    | [2a85bda9fa](https://linux-hardware.org/?probe=2a85bda9fa) | Jul 24, 2020 |
| ASUSTek       | B150M-C D3/BR               | [b46f40c38a](https://linux-hardware.org/?probe=b46f40c38a) | Jul 24, 2020 |
| HP            | 1790                        | [7e30cf0101](https://linux-hardware.org/?probe=7e30cf0101) | Jul 23, 2020 |
| Gigabyte      | H110M-H-CF                  | [c96a8407b9](https://linux-hardware.org/?probe=c96a8407b9) | Jul 22, 2020 |
| HP            | 2AF7                        | [fadc92035e](https://linux-hardware.org/?probe=fadc92035e) | Jul 22, 2020 |
| Gigabyte      | G31M-ES2L                   | [cbad09cb89](https://linux-hardware.org/?probe=cbad09cb89) | Jul 21, 2020 |
| HP            | ProLiant ML10 v2            | [84badf8a6a](https://linux-hardware.org/?probe=84badf8a6a) | Jul 21, 2020 |
| MSI           | A75MA-G55                   | [9061f7d6fb](https://linux-hardware.org/?probe=9061f7d6fb) | Jul 20, 2020 |
| HP            | 158A                        | [68f61abed8](https://linux-hardware.org/?probe=68f61abed8) | Jul 20, 2020 |
| Lenovo        | ThinkStation S30 0606CW2    | [f25b0e7108](https://linux-hardware.org/?probe=f25b0e7108) | Jul 19, 2020 |
| ASRock        | FM2A88M Extreme4+           | [a51dee5095](https://linux-hardware.org/?probe=a51dee5095) | Jul 19, 2020 |
| Gigabyte      | H110M-H-CF                  | [f076c0e711](https://linux-hardware.org/?probe=f076c0e711) | Jul 18, 2020 |
| Pegatron      | 2AC2                        | [a7985ac6dc](https://linux-hardware.org/?probe=a7985ac6dc) | Jul 17, 2020 |
| Dell          | 0GM819                      | [b1fc765931](https://linux-hardware.org/?probe=b1fc765931) | Jul 15, 2020 |
| ASUSTek       | PRIME Z270-P                | [a50c792692](https://linux-hardware.org/?probe=a50c792692) | Jul 14, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | [6afbd4537c](https://linux-hardware.org/?probe=6afbd4537c) | Jul 14, 2020 |
| Gigabyte      | B365M D3H-CF                | [019ca65c62](https://linux-hardware.org/?probe=019ca65c62) | Jul 14, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Xubuntu_20.04/Desktop/Test_Cases.md>).

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version             | Desktops | Percent |
|---------------------|----------|---------|
| 5.4.0-42-generic    | 40       | 4.31%   |
| 5.4.0-48-generic    | 28       | 3.02%   |
| 5.4.0-52-generic    | 22       | 2.37%   |
| 5.4.0-42-lowlatency | 21       | 2.26%   |
| 5.4.0-58-generic    | 18       | 1.94%   |
| 5.4.0-65-generic    | 17       | 1.83%   |
| 5.4.0-54-generic    | 17       | 1.83%   |
| 5.4.0-37-generic    | 17       | 1.83%   |
| 5.4.0-26-generic    | 17       | 1.83%   |
| 5.4.0-29-generic    | 16       | 1.72%   |
| 5.4.0-126-generic   | 16       | 1.72%   |
| 5.4.0-40-lowlatency | 14       | 1.51%   |
| 5.4.0-40-generic    | 14       | 1.51%   |
| 5.4.0-29-lowlatency | 14       | 1.51%   |
| 5.4.0-125-generic   | 14       | 1.51%   |
| 5.4.0-72-generic    | 11       | 1.19%   |
| 5.4.0-70-generic    | 11       | 1.19%   |
| 5.4.0-66-generic    | 11       | 1.19%   |
| 5.4.0-52-lowlatency | 11       | 1.19%   |
| 5.4.0-37-lowlatency | 11       | 1.19%   |
| 5.4.0-91-generic    | 10       | 1.08%   |
| 5.4.0-47-lowlatency | 10       | 1.08%   |
| 5.4.0-45-generic    | 10       | 1.08%   |
| 5.4.0-33-generic    | 10       | 1.08%   |
| 5.4.0-74-generic    | 9        | 0.97%   |
| 5.4.0-48-lowlatency | 9        | 0.97%   |
| 5.4.0-47-generic    | 9        | 0.97%   |
| 5.4.0-89-generic    | 8        | 0.86%   |
| 5.4.0-77-generic    | 8        | 0.86%   |
| 5.4.0-58-lowlatency | 8        | 0.86%   |
| 5.4.0-31-generic    | 8        | 0.86%   |
| 5.11.0-37-generic   | 8        | 0.86%   |
| 5.8.0-50-generic    | 7        | 0.75%   |
| 5.4.0-88-generic    | 7        | 0.75%   |
| 5.4.0-81-generic    | 7        | 0.75%   |
| 5.4.0-80-generic    | 7        | 0.75%   |
| 5.4.0-73-generic    | 7        | 0.75%   |
| 5.4.0-65-lowlatency | 7        | 0.75%   |
| 5.4.0-56-generic    | 7        | 0.75%   |
| 5.4.0-51-generic    | 7        | 0.75%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 598      | 73.74%  |
| 5.11.0  | 61       | 7.52%   |
| 5.8.0   | 60       | 7.4%    |
| 5.13.0  | 48       | 5.92%   |
| 5.15.0  | 22       | 2.71%   |
| 5.6.0   | 2        | 0.25%   |
| 5.9.16  | 1        | 0.12%   |
| 5.9.14  | 1        | 0.12%   |
| 5.8.5   | 1        | 0.12%   |
| 5.8.1   | 1        | 0.12%   |
| 5.7.17  | 1        | 0.12%   |
| 5.7.1   | 1        | 0.12%   |
| 5.6.6   | 1        | 0.12%   |
| 5.4.64  | 1        | 0.12%   |
| 5.3.0   | 1        | 0.12%   |
| 5.16.0  | 1        | 0.12%   |
| 5.15.1  | 1        | 0.12%   |
| 5.12.2  | 1        | 0.12%   |
| 5.12.17 | 1        | 0.12%   |
| 5.12.12 | 1        | 0.12%   |
| 5.12.10 | 1        | 0.12%   |
| 5.11.16 | 1        | 0.12%   |
| 5.10.27 | 1        | 0.12%   |
| 5.10.13 | 1        | 0.12%   |
| 4.4.0   | 1        | 0.12%   |
| 4.15.0  | 1        | 0.12%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 599      | 74.04%  |
| 5.8     | 62       | 7.66%   |
| 5.11    | 61       | 7.54%   |
| 5.13    | 48       | 5.93%   |
| 5.15    | 23       | 2.84%   |
| 5.6     | 3        | 0.37%   |
| 5.12    | 3        | 0.37%   |
| 5.9     | 2        | 0.25%   |
| 5.7     | 2        | 0.25%   |
| 5.10    | 2        | 0.25%   |
| 5.3     | 1        | 0.12%   |
| 5.16    | 1        | 0.12%   |
| 4.4     | 1        | 0.12%   |
| 4.15    | 1        | 0.12%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 789      | 99.87%  |
| armv7l | 1        | 0.13%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| XFCE       | 762      | 96.46%  |
| GNOME      | 22       | 2.78%   |
| KDE5       | 2        | 0.25%   |
| X-Cinnamon | 1        | 0.13%   |
| MATE       | 1        | 0.13%   |
| LXQt       | 1        | 0.13%   |
| Cinnamon   | 1        | 0.13%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 762      | 96.46%  |
| Tty     | 21       | 2.66%   |
| Web     | 3        | 0.38%   |
| Wayland | 3        | 0.38%   |
| Unknown | 1        | 0.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 421      | 51.85%  |
| LightDM | 239      | 29.43%  |
| TDM     | 133      | 16.38%  |
| GDM     | 10       | 1.23%   |
| GDM3    | 5        | 0.62%   |
| XDM     | 3        | 0.37%   |
| SDDM    | 1        | 0.12%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 252      | 31.82%  |
| de_DE | 94       | 11.87%  |
| fr_FR | 73       | 9.22%   |
| ru_RU | 55       | 6.94%   |
| pt_BR | 40       | 5.05%   |
| en_CA | 35       | 4.42%   |
| en_GB | 34       | 4.29%   |
| it_IT | 29       | 3.66%   |
| C     | 16       | 2.02%   |
| es_ES | 15       | 1.89%   |
| en_AU | 15       | 1.89%   |
| pl_PL | 13       | 1.64%   |
| ja_JP | 13       | 1.64%   |
| nl_NL | 11       | 1.39%   |
| hu_HU | 10       | 1.26%   |
| es_AR | 10       | 1.26%   |
| fr_BE | 6        | 0.76%   |
| de_AT | 6        | 0.76%   |
| fr_CA | 5        | 0.63%   |
| sv_SE | 4        | 0.51%   |
| ro_RO | 4        | 0.51%   |
| fi_FI | 4        | 0.51%   |
| es_MX | 4        | 0.51%   |
| es_CO | 4        | 0.51%   |
| de_CH | 4        | 0.51%   |
| zh_TW | 3        | 0.38%   |
| es_UY | 3        | 0.38%   |
| zh_CN | 2        | 0.25%   |
| sl_SI | 2        | 0.25%   |
| ru_UA | 2        | 0.25%   |
| pt_PT | 2        | 0.25%   |
| fr_CH | 2        | 0.25%   |
| en_ZA | 2        | 0.25%   |
| en_IN | 2        | 0.25%   |
| cs_CZ | 2        | 0.25%   |
| bs_BA | 2        | 0.25%   |
| uk_UA | 1        | 0.13%   |
| th_TH | 1        | 0.13%   |
| nl_BE | 1        | 0.13%   |
| lv_LV | 1        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 570      | 71.52%  |
| EFI  | 227      | 28.48%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 745      | 93.83%  |
| Overlay | 20       | 2.52%   |
| Btrfs   | 12       | 1.51%   |
| Zfs     | 11       | 1.39%   |
| Xfs     | 5        | 0.63%   |
| Ext3    | 1        | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 508      | 64.06%  |
| GPT     | 145      | 18.28%  |
| MBR     | 140      | 17.65%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 615      | 76.49%  |
| Yes       | 189      | 23.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 468      | 58.28%  |
| Yes       | 335      | 41.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| ASUSTek Computer    | 169      | 21.39%  |
| Gigabyte Technology | 117      | 14.81%  |
| Dell                | 89       | 11.27%  |
| Hewlett-Packard     | 76       | 9.62%   |
| ASRock              | 74       | 9.37%   |
| MSI                 | 64       | 8.1%    |
| Lenovo              | 27       | 3.42%   |
| Acer                | 25       | 3.16%   |
| Intel               | 24       | 3.04%   |
| ECS                 | 19       | 2.41%   |
| Medion              | 13       | 1.65%   |
| Fujitsu             | 13       | 1.65%   |
| Unknown             | 11       | 1.39%   |
| Pegatron            | 7        | 0.89%   |
| Foxconn             | 7        | 0.89%   |
| eMachines           | 5        | 0.63%   |
| Packard Bell        | 4        | 0.51%   |
| Fujitsu Siemens     | 4        | 0.51%   |
| Biostar             | 4        | 0.51%   |
| Positivo            | 3        | 0.38%   |
| Apple               | 3        | 0.38%   |
| Shuttle             | 2        | 0.25%   |
| NCR                 | 2        | 0.25%   |
| EVGA                | 2        | 0.25%   |
| BCM                 | 2        | 0.25%   |
| AAEON               | 2        | 0.25%   |
| WinFast             | 1        | 0.13%   |
| Semp Toshiba        | 1        | 0.13%   |
| Seco                | 1        | 0.13%   |
| QTQD                | 1        | 0.13%   |
| Qbex                | 1        | 0.13%   |
| PCWare              | 1        | 0.13%   |
| OEM_MB              | 1        | 0.13%   |
| OEM                 | 1        | 0.13%   |
| Nvidia              | 1        | 0.13%   |
| NEC Computers       | 1        | 0.13%   |
| Itautec             | 1        | 0.13%   |
| Insyde              | 1        | 0.13%   |
| Huanan              | 1        | 0.13%   |
| Google              | 1        | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                   | Desktops | Percent |
|----------------------------------------|----------|---------|
| ASUS All Series                        | 17       | 2.15%   |
| Gigabyte H410M S2H                     | 15       | 1.9%    |
| Unknown                                | 12       | 1.52%   |
| ECS G31T-M9                            | 9        | 1.14%   |
| Dell OptiPlex 7010                     | 8        | 1.01%   |
| Dell OptiPlex 780                      | 5        | 0.63%   |
| Dell OptiPlex 755                      | 5        | 0.63%   |
| Dell OptiPlex 390                      | 5        | 0.63%   |
| ASUS TUF Gaming X570-PLUS              | 5        | 0.63%   |
| MSI MS-7B79                            | 4        | 0.51%   |
| MSI MS-7721                            | 4        | 0.51%   |
| Intel H61                              | 4        | 0.51%   |
| HP Compaq Elite 8300 SFF               | 4        | 0.51%   |
| Gigabyte B450M DS3H                    | 4        | 0.51%   |
| Dell OptiPlex 9020                     | 4        | 0.51%   |
| Dell OptiPlex 760                      | 4        | 0.51%   |
| ASRock N68C-S UCC                      | 4        | 0.51%   |
| MSI MS-7A34                            | 3        | 0.38%   |
| MSI MS-7693                            | 3        | 0.38%   |
| HP Z420 Workstation                    | 3        | 0.38%   |
| HP ProDesk 600 G1 SFF                  | 3        | 0.38%   |
| HP EliteDesk 800 G1 SFF                | 3        | 0.38%   |
| HP Compaq dc7900 Convertible Minitower | 3        | 0.38%   |
| HP Compaq 8100 Elite SFF PC            | 3        | 0.38%   |
| HP Compaq 6200 Pro MT PC               | 3        | 0.38%   |
| Gigabyte H61M-USB3V                    | 3        | 0.38%   |
| Fujitsu ESPRIMO E705                   | 3        | 0.38%   |
| Dell Precision WorkStation T7400       | 3        | 0.38%   |
| Dell OptiPlex 990                      | 3        | 0.38%   |
| Dell OptiPlex 3020                     | 3        | 0.38%   |
| Dell OptiPlex 3010                     | 3        | 0.38%   |
| ASUS TUF Gaming B550M-PLUS             | 3        | 0.38%   |
| ASUS P5K                               | 3        | 0.38%   |
| ASUS M5A78L-M/USB3                     | 3        | 0.38%   |
| ASRock B450M Pro4                      | 3        | 0.38%   |
| Apple MacPro5,1                        | 3        | 0.38%   |
| Pegatron NY802AV-ABA p6110t            | 2        | 0.25%   |
| MSI MS-7C37                            | 2        | 0.25%   |
| MSI MS-7C35                            | 2        | 0.25%   |
| MSI MS-7C02                            | 2        | 0.25%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 50       | 6.33%   |
| HP Compaq           | 34       | 4.3%    |
| ASUS PRIME          | 25       | 3.16%   |
| Lenovo ThinkCentre  | 18       | 2.28%   |
| ASUS All            | 17       | 2.15%   |
| Gigabyte H410M      | 15       | 1.9%    |
| Acer Aspire         | 15       | 1.9%    |
| ASUS TUF            | 14       | 1.77%   |
| Dell Inspiron       | 12       | 1.52%   |
| Unknown             | 12       | 1.52%   |
| Dell Precision      | 11       | 1.39%   |
| Fujitsu ESPRIMO     | 10       | 1.27%   |
| ECS G31T-M9         | 9        | 1.14%   |
| HP ProDesk          | 8        | 1.01%   |
| ASUS ROG            | 6        | 0.76%   |
| ASUS M5A78L-M       | 6        | 0.76%   |
| HP EliteDesk        | 5        | 0.63%   |
| Gigabyte B450M      | 5        | 0.63%   |
| ASRock B450M        | 5        | 0.63%   |
| Acer Veriton        | 5        | 0.63%   |
| Packard Bell IMEDIA | 4        | 0.51%   |
| MSI MS-7B79         | 4        | 0.51%   |
| MSI MS-7721         | 4        | 0.51%   |
| Lenovo ThinkStation | 4        | 0.51%   |
| Intel H61           | 4        | 0.51%   |
| Gigabyte X570       | 4        | 0.51%   |
| Dell Studio         | 4        | 0.51%   |
| ASUS P9X79          | 4        | 0.51%   |
| ASUS P5KPL-AM       | 4        | 0.51%   |
| ASUS P5K            | 4        | 0.51%   |
| ASRock N68C-S       | 4        | 0.51%   |
| MSI MS-7A34         | 3        | 0.38%   |
| MSI MS-7693         | 3        | 0.38%   |
| Lenovo IdeaCentre   | 3        | 0.38%   |
| HP Z420             | 3        | 0.38%   |
| HP ProLiant         | 3        | 0.38%   |
| Gigabyte H61M-USB3V | 3        | 0.38%   |
| ASUS Z170           | 3        | 0.38%   |
| ASUS SABERTOOTH     | 3        | 0.38%   |
| ASUS P8Z77-V        | 3        | 0.38%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Desktops | Percent |
|---------|----------|---------|
| 2013    | 81       | 10.25%  |
| 2009    | 78       | 9.87%   |
| 2011    | 75       | 9.49%   |
| 2012    | 72       | 9.11%   |
| 2010    | 64       | 8.1%    |
| 2018    | 58       | 7.34%   |
| 2014    | 49       | 6.2%    |
| 2019    | 48       | 6.08%   |
| 2020    | 45       | 5.7%    |
| 2008    | 45       | 5.7%    |
| 2017    | 42       | 5.32%   |
| 2015    | 38       | 4.81%   |
| 2007    | 38       | 4.81%   |
| 2016    | 23       | 2.91%   |
| 2006    | 16       | 2.03%   |
| 2021    | 8        | 1.01%   |
| 2005    | 7        | 0.89%   |
| Unknown | 2        | 0.25%   |
| 2022    | 1        | 0.13%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 790      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 769      | 97.34%  |
| Enabled  | 21       | 2.66%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 789      | 99.87%  |
| Yes  | 1        | 0.13%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Desktops | Percent |
|-----------------|----------|---------|
| 3.01-4.0        | 165      | 20.55%  |
| 16.01-24.0      | 165      | 20.55%  |
| 8.01-16.0       | 159      | 19.8%   |
| 4.01-8.0        | 128      | 15.94%  |
| 32.01-64.0      | 71       | 8.84%   |
| 1.01-2.0        | 55       | 6.85%   |
| 64.01-256.0     | 29       | 3.61%   |
| 24.01-32.0      | 14       | 1.74%   |
| 2.01-3.0        | 12       | 1.49%   |
| 0.51-1.0        | 4        | 0.5%    |
| More than 256.0 | 1        | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 402      | 45.89%  |
| 2.01-3.0   | 179      | 20.43%  |
| 0.51-1.0   | 102      | 11.64%  |
| 4.01-8.0   | 91       | 10.39%  |
| 3.01-4.0   | 67       | 7.65%   |
| 8.01-16.0  | 27       | 3.08%   |
| 24.01-32.0 | 4        | 0.46%   |
| 16.01-24.0 | 4        | 0.46%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 316      | 38.73%  |
| 2      | 243      | 29.78%  |
| 3      | 140      | 17.16%  |
| 4      | 59       | 7.23%   |
| 5      | 30       | 3.68%   |
| 6      | 11       | 1.35%   |
| 7      | 7        | 0.86%   |
| 10     | 3        | 0.37%   |
| 0      | 3        | 0.37%   |
| 9      | 2        | 0.25%   |
| 8      | 2        | 0.25%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 455      | 57.23%  |
| No        | 340      | 42.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 784      | 99.24%  |
| No        | 6        | 0.76%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 493      | 61.47%  |
| Yes       | 309      | 38.53%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 644      | 80.5%   |
| Yes       | 156      | 19.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country                | Desktops | Percent |
|------------------------|----------|---------|
| USA                    | 156      | 19.72%  |
| Germany                | 106      | 13.4%   |
| France                 | 72       | 9.1%    |
| Russia                 | 59       | 7.46%   |
| Canada                 | 46       | 5.82%   |
| Brazil                 | 44       | 5.56%   |
| Italy                  | 36       | 4.55%   |
| UK                     | 34       | 4.3%    |
| Netherlands            | 22       | 2.78%   |
| Spain                  | 19       | 2.4%    |
| Australia              | 17       | 2.15%   |
| Japan                  | 15       | 1.9%    |
| Poland                 | 12       | 1.52%   |
| Ukraine                | 11       | 1.39%   |
| Argentina              | 11       | 1.39%   |
| Sweden                 | 10       | 1.26%   |
| Hungary                | 10       | 1.26%   |
| Belgium                | 10       | 1.26%   |
| Romania                | 8        | 1.01%   |
| Austria                | 8        | 1.01%   |
| Finland                | 7        | 0.88%   |
| Switzerland            | 6        | 0.76%   |
| Mexico                 | 6        | 0.76%   |
| Taiwan                 | 4        | 0.51%   |
| Portugal               | 4        | 0.51%   |
| Indonesia              | 4        | 0.51%   |
| Colombia               | 4        | 0.51%   |
| Uruguay                | 3        | 0.38%   |
| Thailand               | 3        | 0.38%   |
| South Africa           | 3        | 0.38%   |
| Slovenia               | 3        | 0.38%   |
| Greece                 | 3        | 0.38%   |
| Czechia                | 3        | 0.38%   |
| New Zealand            | 2        | 0.25%   |
| Latvia                 | 2        | 0.25%   |
| Israel                 | 2        | 0.25%   |
| Iran                   | 2        | 0.25%   |
| Croatia                | 2        | 0.25%   |
| Bulgaria               | 2        | 0.25%   |
| Bosnia and Herzegovina | 2        | 0.25%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Desktops | Percent |
|-------------------|----------|---------|
| Voronezh          | 24       | 2.89%   |
| Sydney            | 10       | 1.2%    |
| Berlin            | 9        | 1.08%   |
| Vancouver         | 8        | 0.96%   |
| Paris             | 7        | 0.84%   |
| Moscow            | 7        | 0.84%   |
| Sao Paulo         | 6        | 0.72%   |
| Montreal          | 6        | 0.72%   |
| Milan             | 6        | 0.72%   |
| Madrid            | 6        | 0.72%   |
| Hamburg           | 6        | 0.72%   |
| Cologne           | 6        | 0.72%   |
| Budapest          | 6        | 0.72%   |
| Tampere           | 4        | 0.48%   |
| Rome              | 4        | 0.48%   |
| Munich            | 4        | 0.48%   |
| Helmond           | 4        | 0.48%   |
| Hanover           | 4        | 0.48%   |
| Chicago           | 4        | 0.48%   |
| Wuppertal         | 3        | 0.36%   |
| Waterford         | 3        | 0.36%   |
| Warsaw            | 3        | 0.36%   |
| Turin             | 3        | 0.36%   |
| Toronto           | 3        | 0.36%   |
| Suwanee           | 3        | 0.36%   |
| Springfield       | 3        | 0.36%   |
| Seattle           | 3        | 0.36%   |
| Saint Paul        | 3        | 0.36%   |
| Rio de Janeiro    | 3        | 0.36%   |
| Ottawa            | 3        | 0.36%   |
| Kyiv              | 3        | 0.36%   |
| Houston           | 3        | 0.36%   |
| Frankfurt am Main | 3        | 0.36%   |
| Fort St. John     | 3        | 0.36%   |
| Dresden           | 3        | 0.36%   |
| Denver            | 3        | 0.36%   |
| Cheboksary        | 3        | 0.36%   |
| Belo Horizonte    | 3        | 0.36%   |
| Zurich            | 2        | 0.24%   |
| Wrexham           | 2        | 0.24%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| Seagate               | 305      | 504    | 21.94%  |
| WDC                   | 290      | 456    | 20.86%  |
| Samsung Electronics   | 183      | 272    | 13.17%  |
| Hitachi               | 76       | 109    | 5.47%   |
| Kingston              | 74       | 86     | 5.32%   |
| Toshiba               | 73       | 94     | 5.25%   |
| SanDisk               | 50       | 64     | 3.6%    |
| Crucial               | 48       | 63     | 3.45%   |
| A-DATA Technology     | 25       | 30     | 1.8%    |
| Maxtor                | 20       | 27     | 1.44%   |
| Intel                 | 20       | 31     | 1.44%   |
| Unknown               | 15       | 18     | 1.08%   |
| Patriot               | 15       | 18     | 1.08%   |
| PNY                   | 12       | 18     | 0.86%   |
| Intenso               | 12       | 19     | 0.86%   |
| China                 | 12       | 12     | 0.86%   |
| HGST                  | 11       | 14     | 0.79%   |
| OCZ                   | 9        | 14     | 0.65%   |
| Transcend             | 8        | 9      | 0.58%   |
| Phison                | 7        | 8      | 0.5%    |
| Fujitsu               | 7        | 8      | 0.5%    |
| SK hynix              | 5        | 5      | 0.36%   |
| Micron Technology     | 5        | 6      | 0.36%   |
| SPCC                  | 4        | 8      | 0.29%   |
| Silicon Motion        | 4        | 4      | 0.29%   |
| Hewlett-Packard       | 4        | 6      | 0.29%   |
| Corsair               | 4        | 4      | 0.29%   |
| Apacer                | 4        | 4      | 0.29%   |
| Team                  | 3        | 4      | 0.22%   |
| Realtek Semiconductor | 3        | 5      | 0.22%   |
| KIOXIA                | 3        | 5      | 0.22%   |
| KingDian              | 3        | 3      | 0.22%   |
| GOODRAM               | 3        | 4      | 0.22%   |
| ASMT                  | 3        | 3      | 0.22%   |
| XPG                   | 2        | 7      | 0.14%   |
| WD MediaMax           | 2        | 2      | 0.14%   |
| USB3.0                | 2        | 3      | 0.14%   |
| Smartbuy              | 2        | 2      | 0.14%   |
| SABRENT               | 2        | 2      | 0.14%   |
| OCZ-VERTEX3           | 2        | 2      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Desktops | Percent |
|-------------------------------------|----------|---------|
| Kingston SA400S37240G 240GB SSD     | 32       | 1.97%   |
| Seagate ST500DM002-1BD142 500GB     | 22       | 1.35%   |
| Seagate ST1000DM010-2EP102 1TB      | 19       | 1.17%   |
| Samsung SSD 860 EVO 500GB           | 14       | 0.86%   |
| Seagate ST2000DM001-1CH164 2TB      | 13       | 0.8%    |
| Samsung SSD 850 EVO 250GB           | 12       | 0.74%   |
| Seagate ST2000DM008-2FR102 2TB      | 11       | 0.68%   |
| Seagate ST1000DM003-1CH162 1TB      | 10       | 0.62%   |
| Kingston SA400S37480G 480GB SSD     | 10       | 0.62%   |
| Toshiba DT01ACA100 1TB              | 9        | 0.55%   |
| Seagate ST4000DM004-2CV104 4TB      | 9        | 0.55%   |
| Seagate ST31000528AS 1TB            | 9        | 0.55%   |
| Seagate Expansion 1TB               | 9        | 0.55%   |
| Patriot Burst 120GB SSD             | 9        | 0.55%   |
| Hitachi HDS721050CLA362 500GB       | 9        | 0.55%   |
| Crucial CT1000MX500SSD1 1TB         | 9        | 0.55%   |
| Unknown SD/MMC/MS PRO 8GB           | 8        | 0.49%   |
| Seagate ST380815AS 80GB             | 8        | 0.49%   |
| Seagate ST3500418AS 500GB           | 8        | 0.49%   |
| Seagate ST3250310AS 250GB           | 8        | 0.49%   |
| Seagate ST31000524AS 1TB            | 8        | 0.49%   |
| Seagate ST1000DM003-1ER162 1TB      | 8        | 0.49%   |
| Samsung SSD 860 EVO 1TB             | 8        | 0.49%   |
| WDC WD10EZEX-00BN5A0 1TB            | 7        | 0.43%   |
| Samsung NVMe SSD Drive 1TB          | 7        | 0.43%   |
| Samsung HD502HJ 500GB               | 7        | 0.43%   |
| Hitachi HDS721010CLA332 1TB         | 7        | 0.43%   |
| WDC WD20EARX-00PASB0 2TB            | 6        | 0.37%   |
| Toshiba DT01ACA050 500GB            | 6        | 0.37%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 6        | 0.37%   |
| Seagate ST3500413AS 500GB           | 6        | 0.37%   |
| Seagate ST2000DM006-2DM164 2TB      | 6        | 0.37%   |
| Seagate ST2000DM001-9YN164 2TB      | 6        | 0.37%   |
| Seagate ST2000DM001-1ER164 2TB      | 6        | 0.37%   |
| Seagate ST2000DL003-9VT166 2TB      | 6        | 0.37%   |
| Samsung SSD 860 EVO 250GB           | 6        | 0.37%   |
| Samsung HD103SJ 1TB                 | 6        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD    | 6        | 0.37%   |
| Crucial CT500MX500SSD1 500GB        | 6        | 0.37%   |
| WDC WD30EFRX-68EUZN0 3TB            | 5        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 299      | 496    | 35.81%  |
| WDC                 | 265      | 412    | 31.74%  |
| Hitachi             | 76       | 109    | 9.1%    |
| Samsung Electronics | 69       | 90     | 8.26%   |
| Toshiba             | 62       | 80     | 7.43%   |
| Maxtor              | 19       | 26     | 2.28%   |
| HGST                | 11       | 14     | 1.32%   |
| Unknown             | 9        | 11     | 1.08%   |
| Fujitsu             | 7        | 8      | 0.84%   |
| Intenso             | 3        | 4      | 0.36%   |
| ASMT                | 3        | 3      | 0.36%   |
| WD MediaMax         | 2        | 2      | 0.24%   |
| Hewlett-Packard     | 2        | 2      | 0.24%   |
| Apple               | 2        | 3      | 0.24%   |
| USB3.0              | 1        | 2      | 0.12%   |
| SAGE                | 1        | 1      | 0.12%   |
| LaCie               | 1        | 4      | 0.12%   |
| ICY BOX             | 1        | 1      | 0.12%   |
| HPE                 | 1        | 4      | 0.12%   |
| ExcelStor           | 1        | 1      | 0.12%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 97       | 133    | 20.91%  |
| Kingston            | 70       | 81     | 15.09%  |
| SanDisk             | 45       | 58     | 9.7%    |
| Crucial             | 41       | 56     | 8.84%   |
| WDC                 | 29       | 37     | 6.25%   |
| A-DATA Technology   | 21       | 25     | 4.53%   |
| Intel               | 16       | 23     | 3.45%   |
| Patriot             | 15       | 18     | 3.23%   |
| PNY                 | 12       | 18     | 2.59%   |
| China               | 12       | 12     | 2.59%   |
| OCZ                 | 8        | 12     | 1.72%   |
| Transcend           | 7        | 7      | 1.51%   |
| Intenso             | 7        | 9      | 1.51%   |
| Toshiba             | 6        | 9      | 1.29%   |
| Micron Technology   | 5        | 6      | 1.08%   |
| SPCC                | 4        | 8      | 0.86%   |
| SK hynix            | 4        | 4      | 0.86%   |
| Corsair             | 4        | 4      | 0.86%   |
| Apacer              | 4        | 4      | 0.86%   |
| Team                | 3        | 4      | 0.65%   |
| KingDian            | 3        | 3      | 0.65%   |
| GOODRAM             | 3        | 4      | 0.65%   |
| Smartbuy            | 2        | 2      | 0.43%   |
| OCZ-VERTEX3         | 2        | 2      | 0.43%   |
| Mushkin             | 2        | 2      | 0.43%   |
| LITEONIT            | 2        | 2      | 0.43%   |
| LITEON              | 2        | 2      | 0.43%   |
| Lexar               | 2        | 2      | 0.43%   |
| Kingmax             | 2        | 2      | 0.43%   |
| Integral            | 2        | 2      | 0.43%   |
| Hewlett-Packard     | 2        | 4      | 0.43%   |
| Emtec               | 2        | 2      | 0.43%   |
| Wintec              | 1        | 1      | 0.22%   |
| WDC WDS             | 1        | 1      | 0.22%   |
| Verbatim            | 1        | 1      | 0.22%   |
| Vaseky              | 1        | 1      | 0.22%   |
| USB3.0              | 1        | 1      | 0.22%   |
| TO Exter            | 1        | 1      | 0.22%   |
| Super Talent        | 1        | 1      | 0.22%   |
| SUNEAST             | 1        | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 606      | 1273   | 54.2%   |
| SSD     | 396      | 588    | 35.42%  |
| NVMe    | 92       | 132    | 8.23%   |
| Unknown | 18       | 23     | 1.61%   |
| MMC     | 6        | 7      | 0.54%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 763      | 1798   | 82.58%  |
| NVMe | 91       | 131    | 9.85%   |
| SAS  | 64       | 87     | 6.93%   |
| MMC  | 6        | 7      | 0.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 617      | 1072   | 55.74%  |
| 0.51-1.0   | 274      | 425    | 24.75%  |
| 1.01-2.0   | 108      | 182    | 9.76%   |
| 2.01-3.0   | 37       | 64     | 3.34%   |
| 3.01-4.0   | 35       | 64     | 3.16%   |
| 4.01-10.0  | 35       | 53     | 3.16%   |
| 10.01-20.0 | 1        | 1      | 0.09%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 239      | 29.15%  |
| 251-500        | 146      | 17.8%   |
| 501-1000       | 118      | 14.39%  |
| 1001-2000      | 93       | 11.34%  |
| More than 3000 | 73       | 8.9%    |
| 51-100         | 53       | 6.46%   |
| 2001-3000      | 37       | 4.51%   |
| 21-50          | 29       | 3.54%   |
| 1-20           | 26       | 3.17%   |
| Unknown        | 6        | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 244      | 28.54%  |
| 21-50          | 135      | 15.79%  |
| 51-100         | 123      | 14.39%  |
| 101-250        | 121      | 14.15%  |
| 501-1000       | 67       | 7.84%   |
| 251-500        | 65       | 7.6%    |
| 1001-2000      | 46       | 5.38%   |
| More than 3000 | 31       | 3.63%   |
| 2001-3000      | 17       | 1.99%   |
| Unknown        | 6        | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB  | 3        | 3      | 3.33%   |
| Hitachi HDS721050CLA362 500GB    | 3        | 3      | 3.33%   |
| WDC WD4000FYYZ-01UL1B1 4TB       | 2        | 3      | 2.22%   |
| WDC WD1002FAEX-00Z3A0 1TB        | 2        | 2      | 2.22%   |
| Seagate ST3250318AS 250GB        | 2        | 2      | 2.22%   |
| Seagate ST2000DM001-1CH164 2TB   | 2        | 3      | 2.22%   |
| Seagate ST1000DL002-9TT153 1TB   | 2        | 2      | 2.22%   |
| Samsung Electronics HD103SI 1TB  | 2        | 2      | 2.22%   |
| Samsung Electronics HD081GJ 80GB | 2        | 2      | 2.22%   |
| Kingston SA400S37240G 240GB SSD  | 2        | 2      | 2.22%   |
| WDC WD6400AAKS-22A7B2 640GB      | 1        | 1      | 1.11%   |
| WDC WD6400AAKS-22A7B0 640GB      | 1        | 1      | 1.11%   |
| WDC WD5000LPVX-08V0TT5 500GB     | 1        | 1      | 1.11%   |
| WDC WD5000LPCX-00VHAT0 500GB     | 1        | 1      | 1.11%   |
| WDC WD5000BEVT-22ZAT0 500GB      | 1        | 1      | 1.11%   |
| WDC WD5000AAKX-08U6AA0 500GB     | 1        | 1      | 1.11%   |
| WDC WD5000AAKX-08ERMA0 500GB     | 1        | 1      | 1.11%   |
| WDC WD5000AAKS-22V1A0 500GB      | 1        | 1      | 1.11%   |
| WDC WD5000AAKS-00A7B0 500GB      | 1        | 1      | 1.11%   |
| WDC WD400EB-00CPF0 40GB          | 1        | 1      | 1.11%   |
| WDC WD3200BEVT-75ZCT1 320GB      | 1        | 1      | 1.11%   |
| WDC WD3200AVJS-63TBA0 320GB      | 1        | 1      | 1.11%   |
| WDC WD3200AAKS-00L9A0 320GB      | 1        | 1      | 1.11%   |
| WDC WD3200AAJS-60Z0A0 320GB      | 1        | 1      | 1.11%   |
| WDC WD3200AAJS-08L7A0 320GB      | 1        | 1      | 1.11%   |
| WDC WD30EFRX-68EUZN0 3TB         | 1        | 1      | 1.11%   |
| WDC WD20EZRX-00D8PB0 2TB         | 1        | 2      | 1.11%   |
| WDC WD20EFRX-68EUZN0 2TB         | 1        | 1      | 1.11%   |
| WDC WD1600AAJS-00L7A0 160GB      | 1        | 1      | 1.11%   |
| WDC WD10EZRX-00A8LB0 1TB         | 1        | 1      | 1.11%   |
| WDC WD10EZEX-00RKKA0 1TB         | 1        | 1      | 1.11%   |
| WDC WD10EFRX-68PJCN0 1TB         | 1        | 1      | 1.11%   |
| WDC WD10EFRX-68JCSN0 1TB         | 1        | 1      | 1.11%   |
| WDC WD10EAVS-22D7B0 1TB          | 1        | 1      | 1.11%   |
| WDC WD10EADX-22TDHB0 1TB         | 1        | 1      | 1.11%   |
| WDC WD10EADS-22M2B0 1TB          | 1        | 1      | 1.11%   |
| Toshiba MQ01ABF050 500GB         | 1        | 2      | 1.11%   |
| Toshiba MK3265GSXF 320GB         | 1        | 1      | 1.11%   |
| Toshiba MK3263GSX 320GB          | 1        | 1      | 1.11%   |
| Toshiba HDWD110 1TB              | 1        | 1      | 1.11%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 32     | 31.76%  |
| Seagate             | 24       | 27     | 28.24%  |
| Samsung Electronics | 10       | 13     | 11.76%  |
| Hitachi             | 6        | 6      | 7.06%   |
| Toshiba             | 5        | 6      | 5.88%   |
| Kingston            | 3        | 3      | 3.53%   |
| SK hynix            | 2        | 2      | 2.35%   |
| Maxtor              | 2        | 2      | 2.35%   |
| Intel               | 1        | 1      | 1.18%   |
| ICY BOX             | 1        | 1      | 1.18%   |
| HGST                | 1        | 1      | 1.18%   |
| FORESEE             | 1        | 1      | 1.18%   |
| Avant               | 1        | 1      | 1.18%   |
| A-DATA Technology   | 1        | 1      | 1.18%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 27       | 32     | 36%     |
| Seagate             | 24       | 27     | 32%     |
| Samsung Electronics | 9        | 11     | 12%     |
| Hitachi             | 6        | 6      | 8%      |
| Toshiba             | 5        | 6      | 6.67%   |
| Maxtor              | 2        | 2      | 2.67%   |
| ICY BOX             | 1        | 1      | 1.33%   |
| HGST                | 1        | 1      | 1.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 67       | 86     | 87.01%  |
| SSD  | 10       | 11     | 12.99%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                            | Desktops | Drives | Percent |
|----------------------------------|----------|--------|---------|
| Toshiba DT01ACA200 2TB           | 1        | 1      | 33.33%  |
| Seagate ST500DM002-1BC142 500GB  | 1        | 1      | 33.33%  |
| A-DATA Technology SP800 32GB SSD | 1        | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor            | Desktops | Drives | Percent |
|-------------------|----------|--------|---------|
| Toshiba           | 1        | 1      | 33.33%  |
| Seagate           | 1        | 1      | 33.33%  |
| A-DATA Technology | 1        | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 528      | 1403   | 61.18%  |
| Works    | 257      | 520    | 29.78%  |
| Malfunc  | 75       | 97     | 8.69%   |
| Failed   | 3        | 3      | 0.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 537      | 53.86%  |
| AMD                           | 205      | 20.56%  |
| Nvidia                        | 42       | 4.21%   |
| ASMedia Technology            | 36       | 3.61%   |
| Samsung Electronics           | 35       | 3.51%   |
| JMicron Technology            | 31       | 3.11%   |
| Marvell Technology Group      | 26       | 2.61%   |
| VIA Technologies              | 12       | 1.2%    |
| SanDisk                       | 8        | 0.8%    |
| Phison Electronics            | 8        | 0.8%    |
| Micron/Crucial Technology     | 8        | 0.8%    |
| ADATA Technology              | 7        | 0.7%    |
| Silicon Motion                | 5        | 0.5%    |
| LSI Logic / Symbios Logic     | 5        | 0.5%    |
| Toshiba America Info Systems  | 4        | 0.4%    |
| Realtek Semiconductor         | 4        | 0.4%    |
| Kingston Technology Company   | 4        | 0.4%    |
| Broadcom / LSI                | 4        | 0.4%    |
| Silicon Image                 | 3        | 0.3%    |
| Promise Technology            | 2        | 0.2%    |
| KIOXIA                        | 2        | 0.2%    |
| Integrated Technology Express | 2        | 0.2%    |
| Adaptec                       | 2        | 0.2%    |
| Seagate Technology            | 1        | 0.1%    |
| OCZ Technology Group          | 1        | 0.1%    |
| Micron Technology             | 1        | 0.1%    |
| Lite-On Technology            | 1        | 0.1%    |
| Hewlett-Packard               | 1        | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 115      | 8.42%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 56       | 4.1%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 55       | 4.03%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 51       | 3.73%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 51       | 3.73%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 45       | 3.29%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 38       | 2.78%   |
| AMD 400 Series Chipset SATA Controller                                                  | 37       | 2.71%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 36       | 2.64%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 34       | 2.49%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 33       | 2.42%   |
| Intel SATA Controller [RAID mode]                                                       | 32       | 2.34%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 32       | 2.34%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 24       | 1.76%   |
| Nvidia MCP61 SATA Controller                                                            | 22       | 1.61%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 22       | 1.61%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 22       | 1.61%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 21       | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 21       | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 21       | 1.54%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 19       | 1.39%   |
| Nvidia MCP61 IDE                                                                        | 18       | 1.32%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 18       | 1.32%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 16       | 1.17%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 14       | 1.02%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 14       | 1.02%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 13       | 0.95%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 13       | 0.95%   |
| AMD 300 Series Chipset SATA Controller                                                  | 12       | 0.88%   |
| Intel C600/X79 series chipset 6-Port SATA AHCI Controller                               | 11       | 0.81%   |
| Intel 82Q35 Express PT IDER Controller                                                  | 11       | 0.81%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 11       | 0.81%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 11       | 0.81%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 10       | 0.73%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 10       | 0.73%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 9        | 0.66%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 9        | 0.66%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 8        | 0.59%   |
| AMD FCH SATA Controller D                                                               | 8        | 0.59%   |
| AMD FCH IDE Controller                                                                  | 8        | 0.59%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 562      | 54.72%  |
| IDE  | 308      | 29.99%  |
| NVMe | 88       | 8.57%   |
| RAID | 55       | 5.36%   |
| SAS  | 8        | 0.78%   |
| SCSI | 6        | 0.58%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 546      | 69.11%  |
| AMD    | 243      | 30.76%  |
| ARM    | 1        | 0.13%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Intel Core i3-10100 CPU @ 3.60GHz           | 17       | 2.14%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz        | 14       | 1.76%   |
| Intel Core i5-2400 CPU @ 3.10GHz            | 12       | 1.51%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz        | 12       | 1.51%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 11       | 1.38%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 10       | 1.26%   |
| Intel Core i3-4130 CPU @ 3.40GHz            | 10       | 1.26%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 10       | 1.26%   |
| AMD FX-8350 Eight-Core Processor            | 10       | 1.26%   |
| Intel Core i7-3770 CPU @ 3.40GHz            | 9        | 1.13%   |
| Intel Core i7-2600K CPU @ 3.40GHz           | 8        | 1.01%   |
| Intel Core i5-6400 CPU @ 2.70GHz            | 8        | 1.01%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 8        | 1.01%   |
| Intel Core i3-2120 CPU @ 3.30GHz            | 8        | 1.01%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz       | 8        | 1.01%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8        | 1.01%   |
| Intel Pentium Dual-Core CPU E5300 @ 2.60GHz | 7        | 0.88%   |
| Intel Core i5-3570 CPU @ 3.40GHz            | 7        | 0.88%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 7        | 0.88%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 7        | 0.88%   |
| AMD Ryzen 5 3600 6-Core Processor           | 7        | 0.88%   |
| AMD Phenom II X4 955 Processor              | 7        | 0.88%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 6        | 0.75%   |
| Intel Core i5-4460 CPU @ 3.20GHz            | 6        | 0.75%   |
| Intel Core 2 Duo CPU E6550 @ 2.33GHz        | 6        | 0.75%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 6        | 0.75%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz | 5        | 0.63%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 5        | 0.63%   |
| Intel Core i7-3770K CPU @ 3.50GHz           | 5        | 0.63%   |
| Intel Core i7 CPU 860 @ 2.80GHz             | 5        | 0.63%   |
| Intel Core i5-6500 CPU @ 3.20GHz            | 5        | 0.63%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 5        | 0.63%   |
| Intel Core i5-2500K CPU @ 3.30GHz           | 5        | 0.63%   |
| Intel Core i5 CPU 650 @ 3.20GHz             | 5        | 0.63%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 5        | 0.63%   |
| Intel Celeron CPU J1900 @ 1.99GHz           | 5        | 0.63%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 5        | 0.63%   |
| Intel Xeon CPU E5-1620 0 @ 3.60GHz          | 4        | 0.5%    |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz | 4        | 0.5%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 4        | 0.5%    |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 128      | 16.12%  |
| Intel Core i7           | 99       | 12.47%  |
| Intel Core i3           | 71       | 8.94%   |
| Intel Core 2 Duo        | 46       | 5.79%   |
| Intel Xeon              | 42       | 5.29%   |
| AMD Ryzen 5             | 39       | 4.91%   |
| Intel Celeron           | 34       | 4.28%   |
| Intel Pentium Dual-Core | 30       | 3.78%   |
| Intel Pentium           | 28       | 3.53%   |
| AMD FX                  | 28       | 3.53%   |
| Intel Core 2 Quad       | 26       | 3.27%   |
| AMD Ryzen 7             | 26       | 3.27%   |
| AMD Athlon II X2        | 18       | 2.27%   |
| AMD Phenom II X4        | 16       | 2.02%   |
| AMD Athlon 64 X2        | 13       | 1.64%   |
| AMD Ryzen 9             | 12       | 1.51%   |
| AMD Ryzen 3             | 12       | 1.51%   |
| AMD A8                  | 10       | 1.26%   |
| Intel Core 2            | 9        | 1.13%   |
| AMD A10                 | 9        | 1.13%   |
| Intel Pentium Dual      | 7        | 0.88%   |
| Intel Atom              | 7        | 0.88%   |
| Other                   | 6        | 0.76%   |
| Intel Core i9           | 6        | 0.76%   |
| AMD Athlon II X4        | 6        | 0.76%   |
| Intel Pentium D         | 5        | 0.63%   |
| Intel Pentium 4         | 5        | 0.63%   |
| AMD Phenom II X6        | 5        | 0.63%   |
| AMD Phenom              | 5        | 0.63%   |
| AMD E                   | 4        | 0.5%    |
| AMD Athlon II X3        | 4        | 0.5%    |
| AMD Athlon 64           | 4        | 0.5%    |
| AMD Athlon              | 4        | 0.5%    |
| AMD A4                  | 4        | 0.5%    |
| AMD Sempron             | 3        | 0.38%   |
| AMD Ryzen Threadripper  | 3        | 0.38%   |
| AMD E1                  | 3        | 0.38%   |
| AMD A6                  | 3        | 0.38%   |
| Intel Pentium Gold      | 2        | 0.25%   |
| AMD Phenom II X2        | 2        | 0.25%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 345      | 43.51%  |
| 2      | 275      | 34.68%  |
| 6      | 70       | 8.83%   |
| 8      | 46       | 5.8%    |
| 1      | 21       | 2.65%   |
| 12     | 15       | 1.89%   |
| 3      | 9        | 1.13%   |
| 16     | 7        | 0.88%   |
| 10     | 3        | 0.38%   |
| 24     | 1        | 0.13%   |
| 20     | 1        | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 775      | 98.1%   |
| 2      | 15       | 1.9%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 440      | 55.56%  |
| 2      | 352      | 44.44%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 789      | 99.87%  |
| Unknown        | 1        | 0.13%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 94       | 11.63%  |
| 0x1067a    | 70       | 8.66%   |
| 0x306c3    | 65       | 8.04%   |
| 0x206a7    | 64       | 7.92%   |
| 0x306a9    | 52       | 6.44%   |
| 0x010000c8 | 29       | 3.59%   |
| 0x506e3    | 28       | 3.47%   |
| 0x06000852 | 23       | 2.85%   |
| 0x0800820d | 21       | 2.6%    |
| 0x08701021 | 20       | 2.48%   |
| 0xa0653    | 19       | 2.35%   |
| 0x906e9    | 17       | 2.1%    |
| 0x6fb      | 16       | 1.98%   |
| 0x906ea    | 15       | 1.86%   |
| 0x6fd      | 15       | 1.86%   |
| 0x10676    | 14       | 1.73%   |
| 0x106e5    | 13       | 1.61%   |
| 0x08108109 | 12       | 1.49%   |
| 0x206d7    | 10       | 1.24%   |
| 0x06001119 | 9        | 1.11%   |
| 0x106a5    | 8        | 0.99%   |
| 0x010000db | 8        | 0.99%   |
| 0x6f6      | 7        | 0.87%   |
| 0x306f2    | 7        | 0.87%   |
| 0x20655    | 7        | 0.87%   |
| 0x0700010f | 7        | 0.87%   |
| 0x010000c7 | 7        | 0.87%   |
| 0x906ed    | 6        | 0.74%   |
| 0x306e4    | 6        | 0.74%   |
| 0x08701013 | 6        | 0.74%   |
| 0x406c3    | 5        | 0.62%   |
| 0x206c2    | 5        | 0.62%   |
| 0x08001137 | 5        | 0.62%   |
| 0x0600063e | 5        | 0.62%   |
| 0x03000027 | 5        | 0.62%   |
| 0x010000dc | 5        | 0.62%   |
| 0x20652    | 4        | 0.5%    |
| 0x0a201009 | 4        | 0.5%    |
| 0x08001138 | 4        | 0.5%    |
| 0x06003106 | 4        | 0.5%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Penryn           | 89       | 11.22%  |
| Haswell          | 86       | 10.84%  |
| SandyBridge      | 79       | 9.96%   |
| IvyBridge        | 63       | 7.94%   |
| K10              | 59       | 7.44%   |
| KabyLake         | 47       | 5.93%   |
| Core             | 45       | 5.67%   |
| Zen+             | 33       | 4.16%   |
| Zen 2            | 33       | 4.16%   |
| Skylake          | 33       | 4.16%   |
| Piledriver       | 33       | 4.16%   |
| K8 Hammer        | 23       | 2.9%    |
| CometLake        | 23       | 2.9%    |
| Nehalem          | 22       | 2.77%   |
| Zen              | 20       | 2.52%   |
| Westmere         | 17       | 2.14%   |
| Silvermont       | 14       | 1.77%   |
| NetBurst         | 11       | 1.39%   |
| Zen 3            | 10       | 1.26%   |
| Jaguar           | 7        | 0.88%   |
| K10 Llano        | 5        | 0.63%   |
| Goldmont         | 5        | 0.63%   |
| Excavator        | 5        | 0.63%   |
| Bulldozer        | 5        | 0.63%   |
| Bobcat           | 5        | 0.63%   |
| Steamroller      | 4        | 0.5%    |
| Broadwell        | 4        | 0.5%    |
| Bonnell          | 4        | 0.5%    |
| Unknown          | 4        | 0.5%    |
| Puma             | 2        | 0.25%   |
| Icelake          | 1        | 0.13%   |
| Goldmont plus    | 1        | 0.13%   |
| Alderlake Hybrid | 1        | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 327      | 39.11%  |
| Intel                      | 287      | 34.33%  |
| AMD                        | 217      | 25.96%  |
| VIA Technologies           | 2        | 0.24%   |
| Matrox Electronics Systems | 2        | 0.24%   |
| ASPEED Technology          | 1        | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Desktops | Percent |
|------------------------------------------------------------------------------------------|----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 39       | 4.49%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 38       | 4.38%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 35       | 4.03%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 31       | 3.57%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 27       | 3.11%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 26       | 3%      |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 24       | 2.76%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 23       | 2.65%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 18       | 2.07%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                                         | 15       | 1.73%   |
| Nvidia GT218 [GeForce 210]                                                               | 14       | 1.61%   |
| Intel HD Graphics 530                                                                    | 14       | 1.61%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 12       | 1.38%   |
| Nvidia GP108 [GeForce GT 1030]                                                           | 11       | 1.27%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 10       | 1.15%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 10       | 1.15%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 9        | 1.04%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 9        | 1.04%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 9        | 1.04%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 8        | 0.92%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 8        | 0.92%   |
| Intel 82Q35 Express Integrated Graphics Controller                                       | 8        | 0.92%   |
| Nvidia TU117 [GeForce GTX 1650]                                                          | 7        | 0.81%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 7        | 0.81%   |
| Nvidia C61 [GeForce 6150SE nForce 430]                                                   | 7        | 0.81%   |
| AMD RS880 [Radeon HD 4250]                                                               | 7        | 0.81%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7        | 0.81%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 6        | 0.69%   |
| Nvidia G86 [GeForce 8500 GT]                                                             | 6        | 0.69%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 6        | 0.69%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 6        | 0.69%   |
| Nvidia TU106 [GeForce RTX 2060 Rev. A]                                                   | 5        | 0.58%   |
| Nvidia GM206 [GeForce GTX 960]                                                           | 5        | 0.58%   |
| Nvidia C61 [GeForce 7025 / nForce 630a]                                                  | 5        | 0.58%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 5        | 0.58%   |
| AMD Turks XT [Radeon HD 6670/7670]                                                       | 5        | 0.58%   |
| AMD RV710 [Radeon HD 4350/4550]                                                          | 5        | 0.58%   |
| AMD RS880 [Radeon HD 4200]                                                               | 5        | 0.58%   |
| Nvidia TU106 [GeForce RTX 2060 SUPER]                                                    | 4        | 0.46%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 4        | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                     | Desktops | Percent |
|--------------------------|----------|---------|
| 1 x Nvidia               | 307      | 38.42%  |
| 1 x Intel                | 259      | 32.42%  |
| 1 x AMD                  | 191      | 23.9%   |
| 2 x AMD                  | 14       | 1.75%   |
| Intel + Nvidia           | 6        | 0.75%   |
| 2 x Nvidia               | 4        | 0.5%    |
| Intel + AMD              | 4        | 0.5%    |
| AMD + Nvidia             | 4        | 0.5%    |
| Other                    | 3        | 0.38%   |
| 1 x VIA                  | 2        | 0.25%   |
| 1 x Matrox               | 2        | 0.25%   |
| 2 x AMD + 1 x Nvidia     | 1        | 0.13%   |
| Nvidia + ASPEED          | 1        | 0.13%   |
| Intel + AMD + 1 x Nvidia | 1        | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 562      | 70.34%  |
| Proprietary | 209      | 26.16%  |
| Unknown     | 28       | 3.5%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 315      | 39.03%  |
| 0.51-1.0   | 126      | 15.61%  |
| 0.01-0.5   | 118      | 14.62%  |
| 1.01-2.0   | 113      | 14%     |
| 3.01-4.0   | 70       | 8.67%   |
| 7.01-8.0   | 36       | 4.46%   |
| 5.01-6.0   | 12       | 1.49%   |
| 8.01-16.0  | 8        | 0.99%   |
| 2.01-3.0   | 6        | 0.74%   |
| 4.01-5.0   | 2        | 0.25%   |
| 16.01-24.0 | 1        | 0.12%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Desktops | Percent |
|-------------------------|----------|---------|
| Samsung Electronics     | 125      | 15.38%  |
| Dell                    | 92       | 11.32%  |
| Hewlett-Packard         | 62       | 7.63%   |
| Goldstar                | 62       | 7.63%   |
| Acer                    | 58       | 7.13%   |
| AOC                     | 47       | 5.78%   |
| Philips                 | 45       | 5.54%   |
| Ancor Communications    | 30       | 3.69%   |
| BenQ                    | 26       | 3.2%    |
| Unknown                 | 22       | 2.71%   |
| LG Electronics          | 21       | 2.58%   |
| ViewSonic               | 18       | 2.21%   |
| Sony                    | 16       | 1.97%   |
| Fujitsu Siemens         | 16       | 1.97%   |
| Iiyama                  | 13       | 1.6%    |
| HannStar                | 12       | 1.48%   |
| Panasonic               | 11       | 1.35%   |
| NEC Computers           | 9        | 1.11%   |
| Eizo                    | 9        | 1.11%   |
| Medion                  | 8        | 0.98%   |
| Lenovo                  | 8        | 0.98%   |
| Vestel Elektronik       | 5        | 0.62%   |
| ASUSTek Computer        | 5        | 0.62%   |
| Vizio                   | 4        | 0.49%   |
| Idek Iiyama             | 4        | 0.49%   |
| Sharp                   | 3        | 0.37%   |
| ONN                     | 3        | 0.37%   |
| Lenovo Group Limited    | 3        | 0.37%   |
| Haier                   | 3        | 0.37%   |
| Chi Mei Optoelectronics | 3        | 0.37%   |
| AGO                     | 3        | 0.37%   |
| Tech Concepts           | 2        | 0.25%   |
| Packard Bell            | 2        | 0.25%   |
| MStar                   | 2        | 0.25%   |
| IOD                     | 2        | 0.25%   |
| Insignia                | 2        | 0.25%   |
| IBM                     | 2        | 0.25%   |
| HPN                     | 2        | 0.25%   |
| Gateway                 | 2        | 0.25%   |
| DENON                   | 2        | 0.25%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| AOC 24V2W1G5 AOC2402 1920x1080 527x296mm 23.8-inch                     | 15       | 1.75%   |
| Panasonic TV MEIA296 3840x2160 698x392mm 31.5-inch                     | 7        | 0.82%   |
| Goldstar W1943 GSM4BAD 1360x768 406x229mm 18.4-inch                    | 7        | 0.82%   |
| Vestel Elektronik 55UHD_LCD_TV VES3700 3840x2160 1872x1053mm 84.6-inch | 5        | 0.58%   |
| Unknown LCD Monitor SAMSUNG 1920x1080                                  | 5        | 0.58%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch      | 3        | 0.35%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 3        | 0.35%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 3        | 0.35%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                     | 3        | 0.35%   |
| Hewlett-Packard P19A HWP3087 1280x1024 338x270mm 17.0-inch             | 3        | 0.35%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 3        | 0.35%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 3        | 0.35%   |
| Dell 1908FP DEL4026 1280x1024 380x300mm 19.1-inch                      | 3        | 0.35%   |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 520x290mm 23.4-inch  | 3        | 0.35%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch          | 2        | 0.23%   |
| Unknown LCD Monitor SAMSUNG 3840x1080                                  | 2        | 0.23%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch      | 2        | 0.23%   |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch   | 2        | 0.23%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch    | 2        | 0.23%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 380x300mm 19.1-inch   | 2        | 0.23%   |
| Samsung Electronics SMS24A450 SAM083A 1920x1200 518x324mm 24.1-inch    | 2        | 0.23%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch      | 2        | 0.23%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 2        | 0.23%   |
| Samsung Electronics S24D332 SAM0F5E 1920x1080 531x299mm 24.0-inch      | 2        | 0.23%   |
| Samsung Electronics S22D390 SAM0B63 1920x1080 477x268mm 21.5-inch      | 2        | 0.23%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 2        | 0.23%   |
| Samsung Electronics LS32R75 SAM0F92 3840x2160 697x392mm 31.5-inch      | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SyncMaster 1920x1080                   | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SyncMaster 1680x1050                   | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SyncMaster                             | 2        | 0.23%   |
| Samsung Electronics LCD Monitor SAM0A7D 1920x1080 1060x626mm 48.5-inch | 2        | 0.23%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch      | 2        | 0.23%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 2        | 0.23%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 2        | 0.23%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                   | 2        | 0.23%   |
| Philips 221V PHL0888 1920x1080 480x270mm 21.7-inch                     | 2        | 0.23%   |
| Philips 170S PHL0839 1280x1024 338x270mm 17.0-inch                     | 2        | 0.23%   |
| ONN 100002480 ONN0101 1920x1080 474x296mm 22.0-inch                    | 2        | 0.23%   |
| MStar Demo MST0030 1920x1080 1150x650mm 52.0-inch                      | 2        | 0.23%   |
| Medion MD 20144 MED3634 1920x1080 521x293mm 23.5-inch                  | 2        | 0.23%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 335      | 41.88%  |
| 1280x1024 (SXGA)   | 84       | 10.5%   |
| 3840x2160 (4K)     | 44       | 5.5%    |
| 1680x1050 (WSXGA+) | 44       | 5.5%    |
| 1440x900 (WXGA+)   | 42       | 5.25%   |
| 1366x768 (WXGA)    | 42       | 5.25%   |
| Unknown            | 35       | 4.38%   |
| 1920x1200 (WUXGA)  | 32       | 4%      |
| 2560x1440 (QHD)    | 26       | 3.25%   |
| 1600x900 (HD+)     | 24       | 3%      |
| 1360x768           | 19       | 2.38%   |
| 3840x1080          | 11       | 1.38%   |
| 1024x768 (XGA)     | 9        | 1.13%   |
| 1600x1200          | 8        | 1%      |
| 3440x1440          | 5        | 0.63%   |
| 1280x720 (HD)      | 5        | 0.63%   |
| 5120x1440          | 4        | 0.5%    |
| 1920x540           | 4        | 0.5%    |
| 3200x1080          | 3        | 0.38%   |
| 3840x1200          | 2        | 0.25%   |
| 3286x1080          | 2        | 0.25%   |
| 3200x900           | 2        | 0.25%   |
| 2960x1050          | 2        | 0.25%   |
| 2560x1600          | 2        | 0.25%   |
| 2560x1080          | 2        | 0.25%   |
| 6400x1440          | 1        | 0.13%   |
| 5760x2160          | 1        | 0.13%   |
| 5760x1200          | 1        | 0.13%   |
| 5280x2160          | 1        | 0.13%   |
| 4480x1440          | 1        | 0.13%   |
| 3600x1080          | 1        | 0.13%   |
| 3360x1080          | 1        | 0.13%   |
| 3280x1080          | 1        | 0.13%   |
| 3200x1024          | 1        | 0.13%   |
| 2640x768           | 1        | 0.13%   |
| 2288x1287          | 1        | 0.13%   |
| 1280x800 (WXGA)    | 1        | 0.13%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| Unknown | 135      | 17.09%  |
| 23      | 90       | 11.39%  |
| 24      | 80       | 10.13%  |
| 19      | 76       | 9.62%   |
| 21      | 74       | 9.37%   |
| 27      | 59       | 7.47%   |
| 18      | 44       | 5.57%   |
| 17      | 43       | 5.44%   |
| 20      | 33       | 4.18%   |
| 22      | 29       | 3.67%   |
| 31      | 24       | 3.04%   |
| 84      | 13       | 1.65%   |
| 15      | 13       | 1.65%   |
| 72      | 7        | 0.89%   |
| 40      | 7        | 0.89%   |
| 34      | 6        | 0.76%   |
| 32      | 5        | 0.63%   |
| 26      | 5        | 0.63%   |
| 25      | 5        | 0.63%   |
| 54      | 4        | 0.51%   |
| 52      | 4        | 0.51%   |
| 28      | 4        | 0.51%   |
| 14      | 4        | 0.51%   |
| 48      | 3        | 0.38%   |
| 37      | 3        | 0.38%   |
| 46      | 2        | 0.25%   |
| 29      | 2        | 0.25%   |
| 13      | 2        | 0.25%   |
| 12      | 2        | 0.25%   |
| 142     | 1        | 0.13%   |
| 69      | 1        | 0.13%   |
| 65      | 1        | 0.13%   |
| 60      | 1        | 0.13%   |
| 57      | 1        | 0.13%   |
| 49      | 1        | 0.13%   |
| 47      | 1        | 0.13%   |
| 41      | 1        | 0.13%   |
| 39      | 1        | 0.13%   |
| 38      | 1        | 0.13%   |
| 16      | 1        | 0.13%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 222      | 28.61%  |
| 401-500        | 205      | 26.42%  |
| Unknown        | 135      | 17.4%   |
| 301-350        | 54       | 6.96%   |
| 351-400        | 50       | 6.44%   |
| 601-700        | 38       | 4.9%    |
| 1501-2000      | 21       | 2.71%   |
| 1001-1500      | 17       | 2.19%   |
| 801-900        | 12       | 1.55%   |
| 701-800        | 11       | 1.42%   |
| 201-300        | 9        | 1.16%   |
| More than 2000 | 1        | 0.13%   |
| 901-1000       | 1        | 0.13%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 400      | 52.91%  |
| Unknown | 128      | 16.93%  |
| 16/10   | 110      | 14.55%  |
| 5/4     | 83       | 10.98%  |
| 4/3     | 20       | 2.65%   |
| 21/9    | 6        | 0.79%   |
| 6/5     | 3        | 0.4%    |
| 3/2     | 3        | 0.4%    |
| 1.00    | 2        | 0.26%   |
| 1.96    | 1        | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 219      | 28.04%  |
| 151-200        | 135      | 17.29%  |
| Unknown        | 135      | 17.29%  |
| 141-150        | 72       | 9.22%   |
| 301-350        | 61       | 7.81%   |
| 251-300        | 41       | 5.25%   |
| 351-500        | 39       | 4.99%   |
| More than 1000 | 36       | 4.61%   |
| 501-1000       | 17       | 2.18%   |
| 101-110        | 16       | 2.05%   |
| 131-140        | 4        | 0.51%   |
| 81-90          | 2        | 0.26%   |
| 71-80          | 2        | 0.26%   |
| 51-60          | 1        | 0.13%   |
| 91-100         | 1        | 0.13%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 460      | 61.33%  |
| Unknown | 135      | 18%     |
| 101-120 | 96       | 12.8%   |
| 1-50    | 31       | 4.13%   |
| 121-160 | 25       | 3.33%   |
| 161-240 | 3        | 0.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 640      | 80.2%   |
| 2     | 108      | 13.53%  |
| 0     | 42       | 5.26%   |
| 3     | 6        | 0.75%   |
| 4     | 2        | 0.25%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 468      | 41.82%  |
| Intel                             | 300      | 26.81%  |
| Qualcomm Atheros                  | 75       | 6.7%    |
| Broadcom                          | 45       | 4.02%   |
| Nvidia                            | 37       | 3.31%   |
| Ralink Technology                 | 26       | 2.32%   |
| TP-Link                           | 22       | 1.97%   |
| Qualcomm Atheros Communications   | 13       | 1.16%   |
| Ralink                            | 12       | 1.07%   |
| D-Link System                     | 12       | 1.07%   |
| NetGear                           | 11       | 0.98%   |
| Marvell Technology Group          | 9        | 0.8%    |
| D-Link                            | 9        | 0.8%    |
| Huawei Technologies               | 7        | 0.63%   |
| Broadcom Limited                  | 7        | 0.63%   |
| VIA Technologies                  | 6        | 0.54%   |
| Edimax Technology                 | 5        | 0.45%   |
| Belkin Components                 | 5        | 0.45%   |
| ASUSTek Computer                  | 5        | 0.45%   |
| Samsung Electronics               | 4        | 0.36%   |
| Microsoft                         | 4        | 0.36%   |
| MediaTek                          | 4        | 0.36%   |
| Qualcomm                          | 3        | 0.27%   |
| Linksys                           | 3        | 0.27%   |
| AVM                               | 3        | 0.27%   |
| Aquantia                          | 3        | 0.27%   |
| Xiaomi                            | 2        | 0.18%   |
| TRENDnet                          | 2        | 0.18%   |
| IMC Networks                      | 2        | 0.18%   |
| Arduino SA                        | 2        | 0.18%   |
| 3Com                              | 2        | 0.18%   |
| ZyXEL Communications              | 1        | 0.09%   |
| Van Ooijen Technische Informatica | 1        | 0.09%   |
| STMicroelectronics                | 1        | 0.09%   |
| Philips (or NXP)                  | 1        | 0.09%   |
| Mellanox Technologies             | 1        | 0.09%   |
| Manta                             | 1        | 0.09%   |
| LSI                               | 1        | 0.09%   |
| LG Electronics                    | 1        | 0.09%   |
| DisplayLink                       | 1        | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 367      | 30.28%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 46       | 3.8%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31       | 2.56%   |
| Intel I211 Gigabit Network Connection                             | 25       | 2.06%   |
| Intel Ethernet Connection I217-LM                                 | 24       | 1.98%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 22       | 1.82%   |
| Nvidia MCP61 Ethernet                                             | 21       | 1.73%   |
| Intel Ethernet Connection (2) I219-V                              | 20       | 1.65%   |
| Intel Wi-Fi 6 AX200                                               | 19       | 1.57%   |
| Intel 82579V Gigabit Network Connection                           | 19       | 1.57%   |
| Ralink MT7601U Wireless Adapter                                   | 14       | 1.16%   |
| Realtek RTL8125 2.5GbE Controller                                 | 13       | 1.07%   |
| Intel 82574L Gigabit Network Connection                           | 12       | 0.99%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 12       | 0.99%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 11       | 0.91%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11       | 0.91%   |
| Qualcomm Atheros AR9271 802.11n                                   | 11       | 0.91%   |
| Intel Ethernet Connection I217-V                                  | 11       | 0.91%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 9        | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                            | 9        | 0.74%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                           | 9        | 0.74%   |
| Intel Ethernet Connection (2) I218-V                              | 9        | 0.74%   |
| Nvidia MCP77 Ethernet                                             | 8        | 0.66%   |
| Intel Ethernet Connection (7) I219-V                              | 8        | 0.66%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 7        | 0.58%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 7        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                             | 7        | 0.58%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 7        | 0.58%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 6        | 0.5%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter                  | 6        | 0.5%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 6        | 0.5%    |
| Intel Wireless-AC 9260                                            | 6        | 0.5%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 6        | 0.5%    |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                | 6        | 0.5%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 5        | 0.41%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                       | 5        | 0.41%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                        | 5        | 0.41%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5        | 0.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5        | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 84       | 24.93%  |
| Intel                                 | 54       | 16.02%  |
| Qualcomm Atheros                      | 46       | 13.65%  |
| Ralink Technology                     | 26       | 7.72%   |
| TP-Link                               | 22       | 6.53%   |
| Broadcom                              | 17       | 5.04%   |
| Qualcomm Atheros Communications       | 13       | 3.86%   |
| Ralink                                | 12       | 3.56%   |
| NetGear                               | 11       | 3.26%   |
| D-Link                                | 9        | 2.67%   |
| D-Link System                         | 8        | 2.37%   |
| Edimax Technology                     | 5        | 1.48%   |
| Belkin Components                     | 5        | 1.48%   |
| ASUSTek Computer                      | 5        | 1.48%   |
| Microsoft                             | 4        | 1.19%   |
| Linksys                               | 3        | 0.89%   |
| AVM                                   | 3        | 0.89%   |
| TRENDnet                              | 2        | 0.59%   |
| IMC Networks                          | 2        | 0.59%   |
| Broadcom Limited                      | 2        | 0.59%   |
| ZyXEL Communications                  | 1        | 0.3%    |
| Philips (or NXP)                      | 1        | 0.3%    |
| Marvell Technology Group              | 1        | 0.3%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                        | Desktops | Percent |
|------------------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                          | 19       | 5.59%   |
| Ralink MT7601U Wireless Adapter                                              | 14       | 4.12%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                          | 11       | 3.24%   |
| Qualcomm Atheros AR9271 802.11n                                              | 11       | 3.24%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                           | 9        | 2.65%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                       | 9        | 2.65%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                      | 9        | 2.65%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                 | 7        | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                             | 7        | 2.06%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                             | 7        | 2.06%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                             | 6        | 1.76%   |
| Intel Wireless-AC 9260                                                       | 6        | 1.76%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                           | 6        | 1.76%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                  | 5        | 1.47%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                   | 5        | 1.47%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)               | 5        | 1.47%   |
| NetGear A6210                                                                | 5        | 1.47%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                           | 5        | 1.47%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                     | 4        | 1.18%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                              | 4        | 1.18%   |
| Qualcomm Atheros AR93xx Wireless Network Adapter                             | 4        | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)               | 4        | 1.18%   |
| Intel Wireless 3160                                                          | 4        | 1.18%   |
| Intel Cannon Lake PCH CNVi WiFi                                              | 4        | 1.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                     | 3        | 0.88%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                     | 3        | 0.88%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                       | 3        | 0.88%   |
| Realtek RTL8188EE Wireless Network Adapter                                   | 3        | 0.88%   |
| Realtek 802.11n                                                              | 3        | 0.88%   |
| Ralink RT2870/RT3070 Wireless Adapter                                        | 3        | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                   | 3        | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)               | 3        | 0.88%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                             | 3        | 0.88%   |
| Intel Wireless 7260                                                          | 3        | 0.88%   |
| Intel Wireless 3165                                                          | 3        | 0.88%   |
| D-Link DWA-160 802.11abgn Xtreme N Dual Band Adapter(rev.B2) [Ralink RT5572] | 3        | 0.88%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                          | 2        | 0.59%   |
| TP-Link 802.11n NIC                                                          | 2        | 0.59%   |
| TP-Link 802.11ac WLAN Adapter                                                | 2        | 0.59%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                      | 2        | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| Realtek Semiconductor    | 427      | 50.65%  |
| Intel                    | 265      | 31.44%  |
| Nvidia                   | 37       | 4.39%   |
| Qualcomm Atheros         | 35       | 4.15%   |
| Broadcom                 | 29       | 3.44%   |
| Marvell Technology Group | 8        | 0.95%   |
| VIA Technologies         | 6        | 0.71%   |
| Huawei Technologies      | 5        | 0.59%   |
| Broadcom Limited         | 5        | 0.59%   |
| Samsung Electronics      | 4        | 0.47%   |
| MediaTek                 | 4        | 0.47%   |
| D-Link System            | 4        | 0.47%   |
| Qualcomm                 | 3        | 0.36%   |
| Aquantia                 | 3        | 0.36%   |
| Xiaomi                   | 2        | 0.24%   |
| 3Com                     | 2        | 0.24%   |
| Mellanox Technologies    | 1        | 0.12%   |
| LG Electronics           | 1        | 0.12%   |
| DisplayLink              | 1        | 0.12%   |
| Apple                    | 1        | 0.12%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 367      | 42.53%  |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 46       | 5.33%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 31       | 3.59%   |
| Intel I211 Gigabit Network Connection                             | 25       | 2.9%    |
| Intel Ethernet Connection I217-LM                                 | 24       | 2.78%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 22       | 2.55%   |
| Nvidia MCP61 Ethernet                                             | 21       | 2.43%   |
| Intel Ethernet Connection (2) I219-V                              | 20       | 2.32%   |
| Intel 82579V Gigabit Network Connection                           | 19       | 2.2%    |
| Realtek RTL8125 2.5GbE Controller                                 | 13       | 1.51%   |
| Intel 82574L Gigabit Network Connection                           | 12       | 1.39%   |
| Intel 82566DM-2 Gigabit Network Connection                        | 12       | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 11       | 1.27%   |
| Intel Ethernet Connection I217-V                                  | 11       | 1.27%   |
| Intel Ethernet Connection (2) I218-V                              | 9        | 1.04%   |
| Nvidia MCP77 Ethernet                                             | 8        | 0.93%   |
| Intel Ethernet Connection (7) I219-V                              | 8        | 0.93%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7        | 0.81%   |
| Intel Ethernet Connection (2) I219-LM                             | 7        | 0.81%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 6        | 0.7%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 6        | 0.7%    |
| Broadcom NetLink BCM57780 Gigabit Ethernet PCIe                   | 6        | 0.7%    |
| VIA VT6102/VT6103 [Rhine-II]                                      | 5        | 0.58%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 5        | 0.58%   |
| Intel I210 Gigabit Network Connection                             | 5        | 0.58%   |
| Intel 82578DC Gigabit Network Connection                          | 5        | 0.58%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express           | 5        | 0.58%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 4        | 0.46%   |
| Intel 82566DC-2 Gigabit Network Connection                        | 4        | 0.46%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 3        | 0.35%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3        | 0.35%   |
| Qualcomm Redmi Note 8                                             | 3        | 0.35%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 3        | 0.35%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 3        | 0.35%   |
| Nvidia MCP51 Ethernet Controller                                  | 3        | 0.35%   |
| MediaTek N152DL                                                   | 3        | 0.35%   |
| Intel Ethernet Connection (11) I219-V                             | 3        | 0.35%   |
| Intel 82578DM Gigabit Network Connection                          | 3        | 0.35%   |
| Intel 82573L Gigabit Ethernet Controller                          | 3        | 0.35%   |
| Intel 82566DM Gigabit Network Connection                          | 3        | 0.35%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 785      | 71.17%  |
| WiFi     | 309      | 28.01%  |
| Modem    | 7        | 0.63%   |
| Unknown  | 2        | 0.18%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 619      | 75.67%  |
| WiFi     | 199      | 24.33%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 585      | 73.77%  |
| 2     | 173      | 21.82%  |
| 3     | 22       | 2.77%   |
| 0     | 7        | 0.88%   |
| 4     | 4        | 0.5%    |
| 10    | 1        | 0.13%   |
| 5     | 1        | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 664      | 82.79%  |
| Yes  | 138      | 17.21%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 52       | 32.3%   |
| Cambridge Silicon Radio         | 41       | 25.47%  |
| Broadcom                        | 19       | 11.8%   |
| Qualcomm Atheros Communications | 13       | 8.07%   |
| ASUSTek Computer                | 8        | 4.97%   |
| Realtek Semiconductor           | 7        | 4.35%   |
| IMC Networks                    | 5        | 3.11%   |
| Integrated System Solution      | 3        | 1.86%   |
| Apple                           | 3        | 1.86%   |
| Lite-On Technology              | 2        | 1.24%   |
| Edimax Technology               | 2        | 1.24%   |
| TP-Link                         | 1        | 0.62%   |
| Sitecom Europe                  | 1        | 0.62%   |
| Fujitsu                         | 1        | 0.62%   |
| Dell                            | 1        | 0.62%   |
| Conwise Technology              | 1        | 0.62%   |
| Unknown                         | 1        | 0.62%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                     | Desktops | Percent |
|-----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)       | 41       | 25.47%  |
| Intel AX200 Bluetooth                                     | 21       | 13.04%  |
| Intel Bluetooth wireless interface                        | 11       | 6.83%   |
| Broadcom BCM20702A0 Bluetooth 4.0                         | 11       | 6.83%   |
| Intel Wireless-AC 3168 Bluetooth                          | 7        | 4.35%   |
| Qualcomm Atheros  Bluetooth Device                        | 6        | 3.73%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                  | 6        | 3.73%   |
| Qualcomm Atheros AR3011 Bluetooth                         | 5        | 3.11%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)            | 5        | 3.11%   |
| Realtek Bluetooth Radio                                   | 4        | 2.48%   |
| Integrated System Solution Bluetooth Device               | 3        | 1.86%   |
| IMC Networks BCM20702A0                                   | 3        | 1.86%   |
| Broadcom ANYCOM Blue USB-UHE 200/250                      | 3        | 1.86%   |
| ASUS Broadcom BCM20702A0 Bluetooth                        | 3        | 1.86%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                      | 3        | 1.86%   |
| Realtek  Bluetooth 4.2 Adapter                            | 2        | 1.24%   |
| Lite-On Bluetooth Device                                  | 2        | 1.24%   |
| Intel AX201 Bluetooth                                     | 2        | 1.24%   |
| Broadcom BCM2045 Bluetooth                                | 2        | 1.24%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE     | 2        | 1.24%   |
| ASUS BCM20702A0                                           | 2        | 1.24%   |
| TP-Link UB500 Adapter                                     | 1        | 0.62%   |
| Sitecom Europe Sitecom bluetooth2.0 class 2 dongle CN-512 | 1        | 0.62%   |
| Realtek RTL8821A Bluetooth                                | 1        | 0.62%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                    | 1        | 0.62%   |
| Qualcomm Atheros AR9462 Bluetooth                         | 1        | 0.62%   |
| IMC Networks Bluetooth Radio                              | 1        | 0.62%   |
| IMC Networks Bluetooth Device                             | 1        | 0.62%   |
| Fujitsu Bluetooth Device                                  | 1        | 0.62%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter   | 1        | 0.62%   |
| Edimax Bluetooth Adapter                                  | 1        | 0.62%   |
| Dell Wireless 365 Bluetooth                               | 1        | 0.62%   |
| Conwise CW6622                                            | 1        | 0.62%   |
| Broadcom Bluetooth 3.0+HS USB Adapter                     | 1        | 0.62%   |
| Broadcom BCM43142A0 Bluetooth Device                      | 1        | 0.62%   |
| Broadcom BCM20702A0                                       | 1        | 0.62%   |
| ASUS Bluetooth Radio                                      | 1        | 0.62%   |
| Unknown                                                   | 1        | 0.62%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 520      | 41.07%  |
| Nvidia                                          | 298      | 23.54%  |
| AMD                                             | 274      | 21.64%  |
| Creative Labs                                   | 31       | 2.45%   |
| C-Media Electronics                             | 26       | 2.05%   |
| VIA Technologies                                | 13       | 1.03%   |
| Texas Instruments                               | 12       | 0.95%   |
| Logitech                                        | 10       | 0.79%   |
| Yamaha                                          | 8        | 0.63%   |
| Focusrite-Novation                              | 7        | 0.55%   |
| M-Audio                                         | 5        | 0.39%   |
| GN Netcom                                       | 5        | 0.39%   |
| JMTek                                           | 3        | 0.24%   |
| EGO SYStems                                     | 3        | 0.24%   |
| TerraTec Electronic                             | 2        | 0.16%   |
| TEAC                                            | 2        | 0.16%   |
| Sennheiser Communications                       | 2        | 0.16%   |
| SAVITECH                                        | 2        | 0.16%   |
| Samson Technologies                             | 2        | 0.16%   |
| ESI Audiotechnik                                | 2        | 0.16%   |
| Creative Technology                             | 2        | 0.16%   |
| Blue Microphones                                | 2        | 0.16%   |
| Alesis                                          | 2        | 0.16%   |
| AKAI Professional M.I.                          | 2        | 0.16%   |
| ZOOM                                            | 1        | 0.08%   |
| Xilinx                                          | 1        | 0.08%   |
| Unknown                                         | 1        | 0.08%   |
| Thesycon Systemsoftware & Consulting            | 1        | 0.08%   |
| Tenx Technology                                 | 1        | 0.08%   |
| Syntek                                          | 1        | 0.08%   |
| Sony                                            | 1        | 0.08%   |
| Razer USA                                       | 1        | 0.08%   |
| Plantronics                                     | 1        | 0.08%   |
| Pioneer DJ                                      | 1        | 0.08%   |
| Philips (or NXP)                                | 1        | 0.08%   |
| Onkyo                                           | 1        | 0.08%   |
| Microsoft                                       | 1        | 0.08%   |
| Microchip Technology                            | 1        | 0.08%   |
| Line6                                           | 1        | 0.08%   |
| Licensed by Sony Computer Entertainment America | 1        | 0.08%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 73       | 5.04%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 67       | 4.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 59       | 4.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 57       | 3.94%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 49       | 3.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 44       | 3.04%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 36       | 2.49%   |
| AMD Starship/Matisse HD Audio Controller                                   | 36       | 2.49%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 34       | 2.35%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 33       | 2.28%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 32       | 2.21%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 31       | 2.14%   |
| Nvidia GP107GL High Definition Audio Controller                            | 29       | 2%      |
| AMD FCH Azalia Controller                                                  | 29       | 2%      |
| Intel 200 Series PCH HD Audio                                              | 25       | 1.73%   |
| Nvidia High Definition Audio Controller                                    | 24       | 1.66%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 23       | 1.59%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 23       | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 23       | 1.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 23       | 1.59%   |
| Nvidia MCP61 High Definition Audio                                         | 22       | 1.52%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 20       | 1.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 19       | 1.31%   |
| Nvidia GF108 High Definition Audio Controller                              | 16       | 1.1%    |
| Intel Comet Lake PCH-V cAVS                                                | 16       | 1.1%    |
| Intel Cannon Lake PCH cAVS                                                 | 16       | 1.1%    |
| Intel C600/X79 series chipset High Definition Audio Controller             | 16       | 1.1%    |
| Nvidia GF119 HDMI Audio Controller                                         | 15       | 1.04%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 15       | 1.04%   |
| Nvidia GP104 High Definition Audio Controller                              | 13       | 0.9%    |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 12       | 0.83%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 12       | 0.83%   |
| Nvidia GP108 High Definition Audio Controller                              | 11       | 0.76%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 11       | 0.76%   |
| Nvidia GK104 HDMI Audio Controller                                         | 11       | 0.76%   |
| Nvidia GK107 HDMI Audio Controller                                         | 10       | 0.69%   |
| Intel C610/X99 series chipset HD Audio Controller                          | 10       | 0.69%   |
| AMD Kabini HDMI/DP Audio                                                   | 10       | 0.69%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10       | 0.69%   |
| Nvidia TU106 High Definition Audio Controller                              | 9        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 79       | 20.57%  |
| Kingston            | 51       | 13.28%  |
| SK hynix            | 49       | 12.76%  |
| Samsung Electronics | 46       | 11.98%  |
| Crucial             | 38       | 9.9%    |
| Corsair             | 34       | 8.85%   |
| G.Skill             | 23       | 5.99%   |
| Micron Technology   | 17       | 4.43%   |
| Nanya Technology    | 7        | 1.82%   |
| Elpida              | 7        | 1.82%   |
| Transcend           | 6        | 1.56%   |
| Team                | 6        | 1.56%   |
| Patriot             | 3        | 0.78%   |
| A-DATA Technology   | 3        | 0.78%   |
| Unifosa             | 2        | 0.52%   |
| Goodram             | 2        | 0.52%   |
| Walton Chaintech    | 1        | 0.26%   |
| Toshiba             | 1        | 0.26%   |
| Smart               | 1        | 0.26%   |
| Sesame              | 1        | 0.26%   |
| Ramaxel Technology  | 1        | 0.26%   |
| Positivo            | 1        | 0.26%   |
| GeIL                | 1        | 0.26%   |
| CSX                 | 1        | 0.26%   |
| Axiom               | 1        | 0.26%   |
| Apacer              | 1        | 0.26%   |
| 9?02                | 1        | 0.26%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                   | Desktops | Percent |
|---------------------------------------------------------|----------|---------|
| SK hynix RAM HMA82GU6JJR8N-VK 16GB DIMM DDR4 2667MT/s   | 15       | 3.49%   |
| Unknown RAM Module 2GB DIMM SDRAM                       | 9        | 2.09%   |
| Unknown RAM Module 2048MB DIMM SDRAM                    | 6        | 1.4%    |
| Unknown RAM Module 4096MB DIMM 1333MT/s                 | 5        | 1.16%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                 | 5        | 1.16%   |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s     | 5        | 1.16%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s            | 4        | 0.93%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s             | 4        | 0.93%   |
| SK hynix RAM HMT351U6CFR8C-PB 4096MB DIMM DDR3 1800MT/s | 4        | 0.93%   |
| Samsung RAM M378B5173DB0-CK0 4GB DIMM DDR3 1600MT/s     | 4        | 0.93%   |
| Crucial RAM CT51264BA160BJ.C8F 4GB DIMM DDR3 1600MT/s   | 4        | 0.93%   |
| Unknown RAM Module 4096MB DIMM DDR3 1333MT/s            | 3        | 0.7%    |
| Unknown RAM Module 2048MB DIMM DDR 800MT/s              | 3        | 0.7%    |
| SK hynix RAM HYMP112U64CP8-S6 1GB DIMM DDR2 800MT/s     | 3        | 0.7%    |
| SK hynix RAM HMT351U6EFR8C-PB 4GB DIMM DDR3 1800MT/s    | 3        | 0.7%    |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s     | 3        | 0.7%    |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1600MT/s     | 3        | 0.7%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s   | 3        | 0.7%    |
| Unknown RAM Module 8192MB DIMM DDR3 1333MT/s            | 2        | 0.47%   |
| Unknown RAM Module 4096MB DIMM DDR2                     | 2        | 0.47%   |
| Unknown RAM Module 4096MB DIMM DDR 1333MT/s             | 2        | 0.47%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                | 2        | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2 667MT/s             | 2        | 0.47%   |
| Unknown RAM Module 2048MB DIMM DDR2 400MT/s             | 2        | 0.47%   |
| Unknown RAM Module 1024MB DIMM DDR2 400MT/s             | 2        | 0.47%   |
| Unknown RAM Module 1024MB DIMM DDR2                     | 2        | 0.47%   |
| Unknown RAM Module 1024MB DIMM                          | 2        | 0.47%   |
| Transcend RAM TS256MSK64W8N 2GB SODIMM DDR3 1866MT/s    | 2        | 0.47%   |
| SK hynix RAM HMT112U6BFR8C-H9 1GB DIMM DDR3 1333MT/s    | 2        | 0.47%   |
| Samsung RAM M378B5773CH0-CH9 2GB DIMM DDR3 1867MT/s     | 2        | 0.47%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM 1600MT/s          | 2        | 0.47%   |
| Samsung RAM M378B5273DH0-CK0 4096MB DIMM DDR3 2200MT/s  | 2        | 0.47%   |
| Samsung RAM M378B5273DH0-CH9 4GB DIMM DDR3 2133MT/s     | 2        | 0.47%   |
| Samsung RAM M378B1G73DB0-CK0 8GB DIMM DDR3 2133MT/s     | 2        | 0.47%   |
| Samsung RAM M378A1K43CB2-CTD 8GB DIMM DDR4 3200MT/s     | 2        | 0.47%   |
| Samsung RAM M3 78T5663QZ3-CF7 2048MB DIMM SDRAM         | 2        | 0.47%   |
| Patriot RAM PSD34G160081 4096MB DIMM DDR3 1600MT/s      | 2        | 0.47%   |
| Micron RAM 8ATF1G64AZ-2G3H1 8GB DIMM DDR4 2448MT/s      | 2        | 0.47%   |
| Micron RAM 16JTF1G64AZ-1G6E1 8GB DIMM DDR3 1600MT/s     | 2        | 0.47%   |
| Kingston RAM Module 4096MB DIMM DDR3                    | 2        | 0.47%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR3    | 127      | 36.6%   |
| DDR4    | 126      | 36.31%  |
| SDRAM   | 31       | 8.93%   |
| DDR2    | 31       | 8.93%   |
| Unknown | 23       | 6.63%   |
| DDR     | 8        | 2.31%   |
| LPDDR4  | 1        | 0.29%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| DIMM    | 318      | 94.64%  |
| SODIMM  | 17       | 5.06%   |
| FB-DIMM | 1        | 0.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 100      | 26.88%  |
| 4096  | 100      | 26.88%  |
| 2048  | 82       | 22.04%  |
| 16384 | 57       | 15.32%  |
| 1024  | 25       | 6.72%   |
| 32768 | 4        | 1.08%   |
| 512   | 4        | 1.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 68       | 18.04%  |
| 1333    | 51       | 13.53%  |
| 2667    | 34       | 9.02%   |
| 800     | 26       | 6.9%    |
| 2400    | 24       | 6.37%   |
| Unknown | 24       | 6.37%   |
| 2133    | 17       | 4.51%   |
| 3200    | 15       | 3.98%   |
| 3600    | 14       | 3.71%   |
| 1867    | 11       | 2.92%   |
| 1866    | 9        | 2.39%   |
| 2666    | 8        | 2.12%   |
| 667     | 8        | 2.12%   |
| 3000    | 7        | 1.86%   |
| 1800    | 7        | 1.86%   |
| 1066    | 7        | 1.86%   |
| 3800    | 4        | 1.06%   |
| 533     | 4        | 1.06%   |
| 400     | 4        | 1.06%   |
| 2733    | 3        | 0.8%    |
| 49926   | 2        | 0.53%   |
| 3400    | 2        | 0.53%   |
| 3266    | 2        | 0.53%   |
| 2800    | 2        | 0.53%   |
| 2448    | 2        | 0.53%   |
| 2200    | 2        | 0.53%   |
| 2048    | 2        | 0.53%   |
| 1639    | 2        | 0.53%   |
| 4333    | 1        | 0.27%   |
| 3866    | 1        | 0.27%   |
| 3733    | 1        | 0.27%   |
| 3466    | 1        | 0.27%   |
| 3100    | 1        | 0.27%   |
| 2933    | 1        | 0.27%   |
| 2866    | 1        | 0.27%   |
| 2472    | 1        | 0.27%   |
| 2465    | 1        | 0.27%   |
| 2134    | 1        | 0.27%   |
| 2000    | 1        | 0.27%   |
| 1648    | 1        | 0.27%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 25       | 39.06%  |
| Brother Industries  | 16       | 25%     |
| Canon               | 9        | 14.06%  |
| Samsung Electronics | 5        | 7.81%   |
| Zebra               | 4        | 6.25%   |
| Seiko Epson         | 2        | 3.13%   |
| QinHeng Electronics | 1        | 1.56%   |
| Pantum              | 1        | 1.56%   |
| Dymo-CoStar         | 1        | 1.56%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Desktops | Percent |
|-----------------------------------------------------------------------|----------|---------|
| HP LaserJet 400 M401dne                                               | 4        | 6.25%   |
| Zebra ZP 450 Printer                                                  | 3        | 4.69%   |
| Brother HL-5370DW series                                              | 3        | 4.69%   |
| HP OfficeJet Pro 7730 series                                          | 2        | 3.13%   |
| HP LaserJet P1005                                                     | 2        | 3.13%   |
| Brother HL-5340 series                                                | 2        | 3.13%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1        | 1.56%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1        | 1.56%   |
| Seiko Epson L222 Series                                               | 1        | 1.56%   |
| Samsung Xerox Phaser 3117 Laser Printer                               | 1        | 1.56%   |
| Samsung SCX-4200 series                                               | 1        | 1.56%   |
| Samsung ML-2525W Series                                               | 1        | 1.56%   |
| Samsung M2070 Series                                                  | 1        | 1.56%   |
| Samsung M2020 Series                                                  | 1        | 1.56%   |
| QinHeng CH340S                                                        | 1        | 1.56%   |
| Pantum P2000                                                          | 1        | 1.56%   |
| HP OfficeJet Pro 9010 series                                          | 1        | 1.56%   |
| HP Officejet Pro 6230                                                 | 1        | 1.56%   |
| HP LaserJet P2055 series                                              | 1        | 1.56%   |
| HP LaserJet P2015 series                                              | 1        | 1.56%   |
| HP LaserJet P1006                                                     | 1        | 1.56%   |
| HP LaserJet M14-M17                                                   | 1        | 1.56%   |
| HP LaserJet CP 1025                                                   | 1        | 1.56%   |
| HP LaserJet 1320                                                      | 1        | 1.56%   |
| HP LaserJet 1018                                                      | 1        | 1.56%   |
| HP ENVY 4520 series                                                   | 1        | 1.56%   |
| HP Deskjet F4400 series                                               | 1        | 1.56%   |
| HP DeskJet F300 series                                                | 1        | 1.56%   |
| HP DeskJet 5850c                                                      | 1        | 1.56%   |
| HP DeskJet 3700 series                                                | 1        | 1.56%   |
| HP DeskJet 3630 series                                                | 1        | 1.56%   |
| HP Deskjet 3050A                                                      | 1        | 1.56%   |
| HP Color LaserJet CP1215                                              | 1        | 1.56%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 1        | 1.56%   |
| Canon TS3100 series                                                   | 1        | 1.56%   |
| Canon TR8500 series                                                   | 1        | 1.56%   |
| Canon PIXMA MX530 Series                                              | 1        | 1.56%   |
| Canon PIXMA MP190                                                     | 1        | 1.56%   |
| Canon PIXMA MG3600 Series                                             | 1        | 1.56%   |
| Canon MG2400 series                                                   | 1        | 1.56%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 11       | 68.75%  |
| Seiko Epson     | 3        | 18.75%  |
| Hewlett-Packard | 2        | 12.5%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                       | Desktops | Percent |
|-------------------------------------------------------------|----------|---------|
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                      | 3        | 18.75%  |
| Seiko Epson GT-X770 [Perfection V500]                       | 1        | 6.25%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO] | 1        | 6.25%   |
| Seiko Epson GT-7700U [Perfection 1240U]                     | 1        | 6.25%   |
| HP ScanJet 82x0C                                            | 1        | 6.25%   |
| HP ScanJet 5590                                             | 1        | 6.25%   |
| Canon CanoScan N670U/N676U/LiDE 20                          | 1        | 6.25%   |
| Canon CanoScan LiDE 90                                      | 1        | 6.25%   |
| Canon CanoScan LIDE 25                                      | 1        | 6.25%   |
| Canon CanoScan LiDE 220                                     | 1        | 6.25%   |
| Canon CanoScan LiDE 210                                     | 1        | 6.25%   |
| Canon CanoScan LiDE 200                                     | 1        | 6.25%   |
| Canon CanoScan LiDE 120                                     | 1        | 6.25%   |
| Canon CanoScan LiDE 110                                     | 1        | 6.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 44       | 34.38%  |
| Microdia                      | 15       | 11.72%  |
| Microsoft                     | 9        | 7.03%   |
| Generalplus Technology        | 5        | 3.91%   |
| MacroSilicon                  | 4        | 3.13%   |
| Jieli Technology              | 4        | 3.13%   |
| Z-Star Microelectronics       | 3        | 2.34%   |
| Trust                         | 3        | 2.34%   |
| Sunplus Innovation Technology | 3        | 2.34%   |
| Samsung Electronics           | 3        | 2.34%   |
| Cubeternet                    | 3        | 2.34%   |
| ARC International             | 3        | 2.34%   |
| Apple                         | 3        | 2.34%   |
| Realtek Semiconductor         | 2        | 1.56%   |
| Razer USA                     | 2        | 1.56%   |
| Linux Foundation              | 2        | 1.56%   |
| KYE Systems (Mouse Systems)   | 2        | 1.56%   |
| Hewlett-Packard               | 2        | 1.56%   |
| Creative Technology           | 2        | 1.56%   |
| Arkmicro Technologies         | 2        | 1.56%   |
| USB3.0 HD Audio Capture       | 1        | 0.78%   |
| Sunplus IT                    | 1        | 0.78%   |
| PrehKeyTec                    | 1        | 0.78%   |
| Pixart Imaging                | 1        | 0.78%   |
| OPPO Electronics              | 1        | 0.78%   |
| Nintendo                      | 1        | 0.78%   |
| Mimaki Engineering            | 1        | 0.78%   |
| IMC Networks                  | 1        | 0.78%   |
| Huawei Technologies           | 1        | 0.78%   |
| GEMBIRD                       | 1        | 0.78%   |
| Chicony Electronics           | 1        | 0.78%   |
| Aveo Technology               | 1        | 0.78%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                           | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Logitech Webcam C270                            | 12       | 9.38%   |
| Logitech HD Pro Webcam C920                     | 8        | 6.25%   |
| Microdia Webcam Vitade AF                       | 5        | 3.91%   |
| MacroSilicon USB Video                          | 4        | 3.13%   |
| Jieli USB PHY 2.0                               | 4        | 3.13%   |
| Trust USB Camera                                | 3        | 2.34%   |
| Samsung Galaxy series, misc. (MTP mode)         | 3        | 2.34%   |
| Logitech HD Webcam C525                         | 3        | 2.34%   |
| Logitech HD Webcam B910                         | 3        | 2.34%   |
| Logitech C922 Pro Stream Webcam                 | 3        | 2.34%   |
| Generalplus 808 Camera                          | 3        | 2.34%   |
| ARC International Camera                        | 3        | 2.34%   |
| Apple iPhone 5/5C/5S/6/SE                       | 3        | 2.34%   |
| Microsoft LifeCam HD-3000                       | 2        | 1.56%   |
| Microsoft LifeCam Cinema                        | 2        | 1.56%   |
| Microdia USB 2.0 Camera                         | 2        | 1.56%   |
| Microdia Sonix USB 2.0 Camera                   | 2        | 1.56%   |
| Microdia Camera                                 | 2        | 1.56%   |
| Logitech Webcam B500                            | 2        | 1.56%   |
| Logitech QuickCam Pro 9000                      | 2        | 1.56%   |
| Logitech Logitech Webcam C160                   | 2        | 1.56%   |
| Linux Foundation EEM Gadget                     | 2        | 1.56%   |
| Generalplus GENERAL WEBCAM                      | 2        | 1.56%   |
| Cubeternet GL-UPC822 UVC WebCam                 | 2        | 1.56%   |
| Creative VF0610 Live! Cam Socialize HD          | 2        | 1.56%   |
| Arkmicro USB2.0 PC CAMERA                       | 2        | 1.56%   |
| Z-Star Vimicro USB Camera (Altair)              | 1        | 0.78%   |
| Z-Star Venus USB2.0 Camera                      | 1        | 0.78%   |
| Z-Star A4 TECH HD PC Camera                     | 1        | 0.78%   |
| USB3.0 HD Audio Capture USB3.0 HD Video Capture | 1        | 0.78%   |
| Sunplus IT AUKEY PC-LM1 USB Camera              | 1        | 0.78%   |
| Sunplus Full HD webcam                          | 1        | 0.78%   |
| Sunplus Canyon CNS-CWC5 Webcam                  | 1        | 0.78%   |
| Sunplus Aukey-PC-LM1E Camera                    | 1        | 0.78%   |
| Realtek HD webcam                               | 1        | 0.78%   |
| Realtek HD 720P Webcam                          | 1        | 0.78%   |
| Razer USA Razer Kiyo Pro                        | 1        | 0.78%   |
| Razer USA Gaming Webcam [Kiyo]                  | 1        | 0.78%   |
| PrehKeyTec TA-0120-AS                           | 1        | 0.78%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro            | 1        | 0.78%   |

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


| Vendor                    | Desktops | Percent |
|---------------------------|----------|---------|
| OmniKey                   | 2        | 28.57%  |
| Lenovo                    | 1        | 14.29%  |
| Gemalto (was Gemplus)     | 1        | 14.29%  |
| Fujitsu Siemens Computers | 1        | 14.29%  |
| Cherry                    | 1        | 14.29%  |
| Alcor Micro               | 1        | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                            | Desktops | Percent |
|--------------------------------------------------|----------|---------|
| OmniKey CardMan 3021 / 3121                      | 2        | 28.57%  |
| Lenovo Smartcard Keyboard                        | 1        | 14.29%  |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader | 1        | 14.29%  |
| Fujitsu Siemens Computers SmartCard Reader 2A    | 1        | 14.29%  |
| Cherry SmartTerminal XX44                        | 1        | 14.29%  |
| Alcor Micro AU9540 Smartcard Reader              | 1        | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 0     | 696      | 87%     |
| 1     | 83       | 10.38%  |
| 2     | 13       | 1.63%   |
| 4     | 4        | 0.5%    |
| 3     | 3        | 0.38%   |
| 5     | 1        | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 33       | 28.7%   |
| Net/wireless             | 27       | 23.48%  |
| Communication controller | 16       | 13.91%  |
| Unassigned class         | 10       | 8.7%    |
| Sound                    | 8        | 6.96%   |
| Chipcard                 | 6        | 5.22%   |
| Multimedia controller    | 4        | 3.48%   |
| Camera                   | 3        | 2.61%   |
| Net/ethernet             | 2        | 1.74%   |
| Card reader              | 2        | 1.74%   |
| Storage/raid             | 1        | 0.87%   |
| Network                  | 1        | 0.87%   |
| Modem                    | 1        | 0.87%   |
| Dvb card                 | 1        | 0.87%   |

