Garuda Linux - Tested Hardware & Statistics (Desktops)
------------------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

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

Total: 358

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Gigabyte      | B450M K-CF                  | [c58dd08065](https://linux-hardware.org/?probe=c58dd08065) | Jan 31, 2024 |
| ASRock        | B550M-ITX/ac                | [5996127f6c](https://linux-hardware.org/?probe=5996127f6c) | Jan 31, 2024 |
| ASUSTek       | PRIME Z590-A                | [907099b1e7](https://linux-hardware.org/?probe=907099b1e7) | Jan 29, 2024 |
| Gigabyte      | X570S AERO G                | [f485006061](https://linux-hardware.org/?probe=f485006061) | Jan 28, 2024 |
| Gigabyte      | B450M S2H                   | [5f1537cd10](https://linux-hardware.org/?probe=5f1537cd10) | Jan 19, 2024 |
| Dell          | 0D24M8 A00                  | [521b297c38](https://linux-hardware.org/?probe=521b297c38) | Jan 19, 2024 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | [d4da037a11](https://linux-hardware.org/?probe=d4da037a11) | Jan 17, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [52d8f5119e](https://linux-hardware.org/?probe=52d8f5119e) | Jan 15, 2024 |
| ASRock        | X470 Taichi                 | [85ada6019c](https://linux-hardware.org/?probe=85ada6019c) | Jan 15, 2024 |
| MSI           | B350M MORTAR                | [0462bdbc4d](https://linux-hardware.org/?probe=0462bdbc4d) | Jan 14, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [f618c2c6b8](https://linux-hardware.org/?probe=f618c2c6b8) | Jan 10, 2024 |
| ASUSTek       | TUF Gaming B550-PLUS        | [af4d83b40f](https://linux-hardware.org/?probe=af4d83b40f) | Jan 10, 2024 |
| ASUSTek       | PRIME B350-PLUS             | [9e7c6246dc](https://linux-hardware.org/?probe=9e7c6246dc) | Jan 05, 2024 |
| Gigabyte      | AX370-Gaming 3-CF           | [e984790c53](https://linux-hardware.org/?probe=e984790c53) | Jan 04, 2024 |
| ASRock        | X470 Taichi                 | [93ce6b9074](https://linux-hardware.org/?probe=93ce6b9074) | Jan 02, 2024 |
| Gigabyte      | Z370P D3-CF                 | [4c2ef0d59a](https://linux-hardware.org/?probe=4c2ef0d59a) | Dec 30, 2023 |
| NZXT          | N7 B550                     | [2ce2b46a02](https://linux-hardware.org/?probe=2ce2b46a02) | Dec 27, 2023 |
| Intel         | X99-P4 V5.0                 | [875d756d73](https://linux-hardware.org/?probe=875d756d73) | Dec 26, 2023 |
| Gigabyte      | B450 AORUS ELITE            | [c3b34cdeb4](https://linux-hardware.org/?probe=c3b34cdeb4) | Dec 26, 2023 |
| Gigabyte      | Z370P D3-CF                 | [7fcdc0004a](https://linux-hardware.org/?probe=7fcdc0004a) | Dec 25, 2023 |
| HC Technol... | HCAR5000-MI                 | [16f9dec3e0](https://linux-hardware.org/?probe=16f9dec3e0) | Dec 20, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | [67c84a4903](https://linux-hardware.org/?probe=67c84a4903) | Dec 19, 2023 |
| HP            | 2B18                        | [7015a76fe4](https://linux-hardware.org/?probe=7015a76fe4) | Dec 15, 2023 |
| MSI           | H310M PRO-M2 PLUS           | [60461068e8](https://linux-hardware.org/?probe=60461068e8) | Dec 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [241c795a70](https://linux-hardware.org/?probe=241c795a70) | Dec 10, 2023 |
| ASUSTek       | TUF B450M-PLUS GAMING       | [d46afc319c](https://linux-hardware.org/?probe=d46afc319c) | Nov 30, 2023 |
| AZW           | MINI S 10                   | [f71053bf5c](https://linux-hardware.org/?probe=f71053bf5c) | Nov 30, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | [7077c34a71](https://linux-hardware.org/?probe=7077c34a71) | Nov 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [77db088b52](https://linux-hardware.org/?probe=77db088b52) | Nov 26, 2023 |
| Acer          | Predator PO3-620            | [a052f2ee36](https://linux-hardware.org/?probe=a052f2ee36) | Nov 25, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [c8ae454aca](https://linux-hardware.org/?probe=c8ae454aca) | Nov 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [89c0fabbb5](https://linux-hardware.org/?probe=89c0fabbb5) | Nov 17, 2023 |
| MSI           | Z370 PC PRO                 | [e9e98d1041](https://linux-hardware.org/?probe=e9e98d1041) | Nov 14, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [17acb71f9d](https://linux-hardware.org/?probe=17acb71f9d) | Nov 05, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [4a6383e886](https://linux-hardware.org/?probe=4a6383e886) | Nov 04, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [b84c515650](https://linux-hardware.org/?probe=b84c515650) | Nov 02, 2023 |
| ASRock        | X670E Steel Legend          | [d802042506](https://linux-hardware.org/?probe=d802042506) | Oct 31, 2023 |
| ASRock        | H77 Pro4-M                  | [83aeda3c64](https://linux-hardware.org/?probe=83aeda3c64) | Oct 30, 2023 |
| MSI           | PRO Z690-A WIFI DDR4        | [bf5f9098d7](https://linux-hardware.org/?probe=bf5f9098d7) | Oct 28, 2023 |
| Intel         | H55                         | [f8788bcc72](https://linux-hardware.org/?probe=f8788bcc72) | Oct 27, 2023 |
| ASUSTek       | PRIME B350-PLUS             | [92c4516951](https://linux-hardware.org/?probe=92c4516951) | Oct 27, 2023 |
| HP            | 3397                        | [50b7d4272d](https://linux-hardware.org/?probe=50b7d4272d) | Oct 26, 2023 |
| Dell          | 0WN7Y6 A01                  | [4b2be75f68](https://linux-hardware.org/?probe=4b2be75f68) | Oct 24, 2023 |
| Dell          | 0WN7Y6 A01                  | [4323d57b2f](https://linux-hardware.org/?probe=4323d57b2f) | Oct 23, 2023 |
| MSI           | MPG B650 EDGE WIFI          | [73fdacf30c](https://linux-hardware.org/?probe=73fdacf30c) | Oct 18, 2023 |
| MSI           | MPG B650 EDGE WIFI          | [5902fdf35f](https://linux-hardware.org/?probe=5902fdf35f) | Oct 18, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [04d307e685](https://linux-hardware.org/?probe=04d307e685) | Oct 16, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [e30927f66e](https://linux-hardware.org/?probe=e30927f66e) | Oct 12, 2023 |
| HP            | 8053                        | [52151555cb](https://linux-hardware.org/?probe=52151555cb) | Oct 11, 2023 |
| HP            | 8053                        | [d1ce4588e7](https://linux-hardware.org/?probe=d1ce4588e7) | Oct 11, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [49d0e884bb](https://linux-hardware.org/?probe=49d0e884bb) | Oct 08, 2023 |
| ASUSTek       | PRIME X470-PRO              | [61fef3256c](https://linux-hardware.org/?probe=61fef3256c) | Oct 07, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [3d613c96a8](https://linux-hardware.org/?probe=3d613c96a8) | Oct 06, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | [8bc96db254](https://linux-hardware.org/?probe=8bc96db254) | Oct 06, 2023 |
| Intel         | X99                         | [61579851ef](https://linux-hardware.org/?probe=61579851ef) | Oct 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [9410b590b4](https://linux-hardware.org/?probe=9410b590b4) | Oct 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [2a6facae05](https://linux-hardware.org/?probe=2a6facae05) | Oct 05, 2023 |
| Intel         | X99                         | [67ec0ac8d0](https://linux-hardware.org/?probe=67ec0ac8d0) | Oct 02, 2023 |
| Unknown       | TB-5000                     | [9c67baa34f](https://linux-hardware.org/?probe=9c67baa34f) | Sep 29, 2023 |
| Gigabyte      | B550 AORUS PRO AC           | [ecef286c2a](https://linux-hardware.org/?probe=ecef286c2a) | Sep 26, 2023 |
| HP            | 1998                        | [60208f6be9](https://linux-hardware.org/?probe=60208f6be9) | Sep 22, 2023 |
| Gigabyte      | Z790 UD AX                  | [5995975e04](https://linux-hardware.org/?probe=5995975e04) | Sep 16, 2023 |
| Gigabyte      | 970A-DS3P                   | [fa347b6b46](https://linux-hardware.org/?probe=fa347b6b46) | Sep 15, 2023 |
| Dell          | 0GY6Y8 A02                  | [623cd3e438](https://linux-hardware.org/?probe=623cd3e438) | Sep 14, 2023 |
| Gigabyte      | AX370-Gaming 3-CF           | [b037f9322d](https://linux-hardware.org/?probe=b037f9322d) | Sep 10, 2023 |
| ASUSTek       | M51BC                       | [647634e7fb](https://linux-hardware.org/?probe=647634e7fb) | Sep 10, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS WIF... | [5330a96ef6](https://linux-hardware.org/?probe=5330a96ef6) | Sep 07, 2023 |
| Gigabyte      | X570 AORUS MASTER           | [fde9e1a454](https://linux-hardware.org/?probe=fde9e1a454) | Aug 20, 2023 |
| ASUSTek       | M51BC                       | [4a81412fdd](https://linux-hardware.org/?probe=4a81412fdd) | Aug 20, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | [9c90e63339](https://linux-hardware.org/?probe=9c90e63339) | Aug 17, 2023 |
| ASUSTek       | ROG STRIX X570-I GAMING     | [f0b1f6f364](https://linux-hardware.org/?probe=f0b1f6f364) | Aug 17, 2023 |
| ASUSTek       | PRIME H410M-E               | [a9d7216b70](https://linux-hardware.org/?probe=a9d7216b70) | Aug 15, 2023 |
| Gigabyte      | GA-MA770T-UD3               | [4dc7a0831b](https://linux-hardware.org/?probe=4dc7a0831b) | Aug 14, 2023 |
| Dell          | 0KV62T A00                  | [369b0195cc](https://linux-hardware.org/?probe=369b0195cc) | Aug 14, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [ef08441bc9](https://linux-hardware.org/?probe=ef08441bc9) | Aug 13, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | [b0f8b16669](https://linux-hardware.org/?probe=b0f8b16669) | Aug 13, 2023 |
| ASRock        | B450M-HDV R4.0              | [6855901c02](https://linux-hardware.org/?probe=6855901c02) | Aug 12, 2023 |
| HP            | 8433 11                     | [de06cea570](https://linux-hardware.org/?probe=de06cea570) | Aug 10, 2023 |
| HP            | 8433 11                     | [4275d43a74](https://linux-hardware.org/?probe=4275d43a74) | Aug 10, 2023 |
| Gigabyte      | B560 DS3H AC-Y1             | [af88e64084](https://linux-hardware.org/?probe=af88e64084) | Aug 04, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [88e9cc22bf](https://linux-hardware.org/?probe=88e9cc22bf) | Aug 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | [52319a8cef](https://linux-hardware.org/?probe=52319a8cef) | Aug 03, 2023 |
| MSI           | B450 TOMAHAWK               | [6b736ced64](https://linux-hardware.org/?probe=6b736ced64) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | [a5467c396a](https://linux-hardware.org/?probe=a5467c396a) | Jul 28, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [3a59ab6dd1](https://linux-hardware.org/?probe=3a59ab6dd1) | Jul 26, 2023 |
| HP            | 18E7                        | [1638b42b8b](https://linux-hardware.org/?probe=1638b42b8b) | Jul 23, 2023 |
| HP            | 18E7                        | [909788f739](https://linux-hardware.org/?probe=909788f739) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | [9ce9a989dd](https://linux-hardware.org/?probe=9ce9a989dd) | Jul 23, 2023 |
| Biostar       | B350GT3                     | [41d95e4e81](https://linux-hardware.org/?probe=41d95e4e81) | Jul 22, 2023 |
| Alienware     | 07W25T A00                  | [24dade96af](https://linux-hardware.org/?probe=24dade96af) | Jul 21, 2023 |
| Shenzhen M... | HX90G                       | [f42afac191](https://linux-hardware.org/?probe=f42afac191) | Jul 15, 2023 |
| ASUSTek       | PRIME Z690-P D4             | [b91bb21dfc](https://linux-hardware.org/?probe=b91bb21dfc) | Jul 10, 2023 |
| HP            | 8053                        | [4241a715e6](https://linux-hardware.org/?probe=4241a715e6) | Jul 09, 2023 |
| ASRock        | B450M-HDV R4.0              | [f24ba1fb9c](https://linux-hardware.org/?probe=f24ba1fb9c) | Jul 09, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [54611e82ec](https://linux-hardware.org/?probe=54611e82ec) | Jul 06, 2023 |
| Gigabyte      | Z490 GAMING X               | [5e8900dde2](https://linux-hardware.org/?probe=5e8900dde2) | Jul 02, 2023 |
| Gigabyte      | Z490 GAMING X               | [b819a1fb21](https://linux-hardware.org/?probe=b819a1fb21) | Jul 02, 2023 |
| ASRock        | X470 Taichi                 | [529873f796](https://linux-hardware.org/?probe=529873f796) | Jul 02, 2023 |
| HP            | 1998                        | [cee46b5772](https://linux-hardware.org/?probe=cee46b5772) | Jul 01, 2023 |
| Shenzhen M... | HX90G                       | [d1d0bb38d0](https://linux-hardware.org/?probe=d1d0bb38d0) | Jun 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [2278cd4d03](https://linux-hardware.org/?probe=2278cd4d03) | Jun 17, 2023 |
| Biostar       | B350GT3                     | [13b1026096](https://linux-hardware.org/?probe=13b1026096) | Jun 13, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | [933978a1ae](https://linux-hardware.org/?probe=933978a1ae) | Jun 07, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [21b7236d20](https://linux-hardware.org/?probe=21b7236d20) | Jun 03, 2023 |
| Lenovo        | ThinkCentre M58p 6137AU8    | [bd80dea70f](https://linux-hardware.org/?probe=bd80dea70f) | May 29, 2023 |
| ASUSTek       | Rampage V EDITION 10        | [a7fbdc21bc](https://linux-hardware.org/?probe=a7fbdc21bc) | May 26, 2023 |
| Win elemen... | M600                        | [4c5d685663](https://linux-hardware.org/?probe=4c5d685663) | May 21, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | [262bc7c88f](https://linux-hardware.org/?probe=262bc7c88f) | May 21, 2023 |
| Win elemen... | M600                        | [84de4a3207](https://linux-hardware.org/?probe=84de4a3207) | May 20, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | [194f7f96e5](https://linux-hardware.org/?probe=194f7f96e5) | May 13, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [fda523de2a](https://linux-hardware.org/?probe=fda523de2a) | May 11, 2023 |
| ASUSTek       | Z170 PRO GAMING             | [3b4eb54186](https://linux-hardware.org/?probe=3b4eb54186) | May 08, 2023 |
| Intel         | DH67CL AAG10212-210         | [3f2fa70636](https://linux-hardware.org/?probe=3f2fa70636) | May 06, 2023 |
| MSI           | MAG B550 TOMAHAWK           | [7a5a0f75aa](https://linux-hardware.org/?probe=7a5a0f75aa) | May 01, 2023 |
| Intel         | DH67CL AAG10212-210         | [7d6b0027b3](https://linux-hardware.org/?probe=7d6b0027b3) | Apr 30, 2023 |
| ASRock        | A320M-HD                    | [43b57e5088](https://linux-hardware.org/?probe=43b57e5088) | Apr 28, 2023 |
| Intel         | DH67CL AAG10212-210         | [cb87589d9f](https://linux-hardware.org/?probe=cb87589d9f) | Apr 28, 2023 |
| Shenzhen M... | F7BFC                       | [bb189b2507](https://linux-hardware.org/?probe=bb189b2507) | Apr 22, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [d9fd347989](https://linux-hardware.org/?probe=d9fd347989) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | [d5adb940b4](https://linux-hardware.org/?probe=d5adb940b4) | Apr 19, 2023 |
| Intel         | DH67CL AAG10212-210         | [8519b4cda2](https://linux-hardware.org/?probe=8519b4cda2) | Apr 15, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | [424d545740](https://linux-hardware.org/?probe=424d545740) | Apr 14, 2023 |
| Acer          | Veriton K8-680G V:1.0       | [9ab3fc183a](https://linux-hardware.org/?probe=9ab3fc183a) | Apr 13, 2023 |
| Win elemen... | M600                        | [7723a03558](https://linux-hardware.org/?probe=7723a03558) | Apr 10, 2023 |
| Win elemen... | M600                        | [e20927ec15](https://linux-hardware.org/?probe=e20927ec15) | Apr 10, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | [e2521c6d93](https://linux-hardware.org/?probe=e2521c6d93) | Apr 09, 2023 |
| HP            | 8053                        | [9897b3e51f](https://linux-hardware.org/?probe=9897b3e51f) | Apr 04, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | [7a2bce56b1](https://linux-hardware.org/?probe=7a2bce56b1) | Mar 26, 2023 |
| HP            | 8053                        | [82eb90837f](https://linux-hardware.org/?probe=82eb90837f) | Mar 21, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [40372e4af3](https://linux-hardware.org/?probe=40372e4af3) | Mar 19, 2023 |
| MSI           | B450-A PRO MAX              | [15f0543609](https://linux-hardware.org/?probe=15f0543609) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [9d10f13efc](https://linux-hardware.org/?probe=9d10f13efc) | Mar 18, 2023 |
| HP            | 8053                        | [273a6c822b](https://linux-hardware.org/?probe=273a6c822b) | Mar 12, 2023 |
| HP            | 8053                        | [be27383efc](https://linux-hardware.org/?probe=be27383efc) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | [51b92fb276](https://linux-hardware.org/?probe=51b92fb276) | Mar 11, 2023 |
| Dell          | 0VYXHD A00                  | [d7618c5b6c](https://linux-hardware.org/?probe=d7618c5b6c) | Mar 08, 2023 |
| ASUSTek       | BT6130                      | [3549cfad14](https://linux-hardware.org/?probe=3549cfad14) | Feb 27, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | [575a7f4897](https://linux-hardware.org/?probe=575a7f4897) | Feb 26, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | [466f8533fb](https://linux-hardware.org/?probe=466f8533fb) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [fad109dc98](https://linux-hardware.org/?probe=fad109dc98) | Feb 25, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | [a53235325f](https://linux-hardware.org/?probe=a53235325f) | Feb 23, 2023 |
| MSI           | MPG X570 GAMING PLUS        | [bd6a746c89](https://linux-hardware.org/?probe=bd6a746c89) | Feb 20, 2023 |
| MSI           | B450-A PRO                  | [014bf5276e](https://linux-hardware.org/?probe=014bf5276e) | Feb 17, 2023 |
| ASUSTek       | BT6130                      | [db3b191eb2](https://linux-hardware.org/?probe=db3b191eb2) | Feb 13, 2023 |
| ASRock        | A520M-ITX/ac                | [a6e401a1d3](https://linux-hardware.org/?probe=a6e401a1d3) | Feb 09, 2023 |
| Intel         | X79M-S                      | [91ab5e33ed](https://linux-hardware.org/?probe=91ab5e33ed) | Feb 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | [d6d4c6c38c](https://linux-hardware.org/?probe=d6d4c6c38c) | Jan 31, 2023 |
| ASUSTek       | PRIME Z490-A                | [91dbb8d045](https://linux-hardware.org/?probe=91dbb8d045) | Jan 26, 2023 |
| Intel         | X79M-S                      | [ccad523936](https://linux-hardware.org/?probe=ccad523936) | Jan 22, 2023 |
| ASUSTek       | PRIME A320M-A               | [918dbdb148](https://linux-hardware.org/?probe=918dbdb148) | Jan 22, 2023 |
| ASUSTek       | Rampage IV GENE             | [64553c4fd7](https://linux-hardware.org/?probe=64553c4fd7) | Jan 17, 2023 |
| MSI           | B450M PRO-VDH MAX           | [87e7a60bfa](https://linux-hardware.org/?probe=87e7a60bfa) | Jan 15, 2023 |
| ASUSTek       | CM6850                      | [7eac1c6a7a](https://linux-hardware.org/?probe=7eac1c6a7a) | Jan 13, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | [5e29a1afb7](https://linux-hardware.org/?probe=5e29a1afb7) | Jan 10, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | [8daa546122](https://linux-hardware.org/?probe=8daa546122) | Jan 09, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [919b259ea2](https://linux-hardware.org/?probe=919b259ea2) | Jan 09, 2023 |
| ASUSTek       | PRIME X570-P                | [95c21fc90e](https://linux-hardware.org/?probe=95c21fc90e) | Jan 09, 2023 |
| Gigabyte      | GA-78LMT-USB3               | [d759bb7551](https://linux-hardware.org/?probe=d759bb7551) | Jan 08, 2023 |
| MSI           | H61M-E22/W8                 | [92280cb6ae](https://linux-hardware.org/?probe=92280cb6ae) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| Intel         | X79M-S                      | [3b38d8023e](https://linux-hardware.org/?probe=3b38d8023e) | Jan 03, 2023 |
| Dell          | 0VHWTR A02                  | [0d9d6203e1](https://linux-hardware.org/?probe=0d9d6203e1) | Jan 03, 2023 |
| Intel         | X79M-S                      | [5c97a3976d](https://linux-hardware.org/?probe=5c97a3976d) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | [a294963db9](https://linux-hardware.org/?probe=a294963db9) | Jan 01, 2023 |
| Lenovo        | Win8 Pro DPK TPG            | [9561e51689](https://linux-hardware.org/?probe=9561e51689) | Dec 31, 2022 |
| Intel         | H61                         | [39f3cddffb](https://linux-hardware.org/?probe=39f3cddffb) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | [ee98173357](https://linux-hardware.org/?probe=ee98173357) | Dec 27, 2022 |
| ASRock        | X570 Taichi                 | [e48882ad67](https://linux-hardware.org/?probe=e48882ad67) | Dec 22, 2022 |
| ASUSTek       | PRIME Z390-P                | [1a9f9ac05f](https://linux-hardware.org/?probe=1a9f9ac05f) | Dec 22, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [7ce8a10de4](https://linux-hardware.org/?probe=7ce8a10de4) | Dec 21, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | [a4c1397ad3](https://linux-hardware.org/?probe=a4c1397ad3) | Dec 21, 2022 |
| BESSTAR Te... | B550                        | [d9fbac807d](https://linux-hardware.org/?probe=d9fbac807d) | Dec 10, 2022 |
| ASRock        | Z77 Pro3                    | [a2e7958d4a](https://linux-hardware.org/?probe=a2e7958d4a) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | [3184df2bf6](https://linux-hardware.org/?probe=3184df2bf6) | Dec 07, 2022 |
| Gigabyte      | 990FXA-UD3                  | [54d896b9ed](https://linux-hardware.org/?probe=54d896b9ed) | Dec 06, 2022 |
| MSI           | H510I PRO WIFI              | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| Dell          | 0K3CM7 A00                  | [27109cda18](https://linux-hardware.org/?probe=27109cda18) | Nov 20, 2022 |
| Dell          | 0K3CM7 A00                  | [6dbdd86e08](https://linux-hardware.org/?probe=6dbdd86e08) | Nov 20, 2022 |
| HP            | 8767 A                      | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| Gigabyte      | 990FXA-UD3                  | [985fb6d758](https://linux-hardware.org/?probe=985fb6d758) | Nov 16, 2022 |
| Dell          | 0K3CM7 A00                  | [3c426cb32b](https://linux-hardware.org/?probe=3c426cb32b) | Nov 14, 2022 |
| ASRock        | X470 Taichi                 | [7cd5f4c280](https://linux-hardware.org/?probe=7cd5f4c280) | Nov 05, 2022 |
| ASRock        | X470 Taichi                 | [d808be6d90](https://linux-hardware.org/?probe=d808be6d90) | Oct 31, 2022 |
| HP            | 2B2C                        | [6f90b1e25e](https://linux-hardware.org/?probe=6f90b1e25e) | Oct 26, 2022 |
| ASUSTek       | PRIME X570-P                | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| Acer          | Aspire TC-780               | [fd6c66dac7](https://linux-hardware.org/?probe=fd6c66dac7) | Oct 22, 2022 |
| ASUSTek       | PRIME X570-P                | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| ASUSTek       | PRIME X570-P                | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASRock        | A320M-HDV R4.0              | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| Gigabyte      | F2A88XM-HD3                 | [44e355eb93](https://linux-hardware.org/?probe=44e355eb93) | Aug 30, 2022 |
| ASRock        | X470 Taichi                 | [7bc56eb3d4](https://linux-hardware.org/?probe=7bc56eb3d4) | Aug 25, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [57f1970999](https://linux-hardware.org/?probe=57f1970999) | Aug 20, 2022 |
| ASUSTek       | PRIME X570-P                | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| MSI           | A68HM-E33 V2                | [762f08a697](https://linux-hardware.org/?probe=762f08a697) | Aug 13, 2022 |
| ASRock        | A520M-HDV                   | [f23bdacb56](https://linux-hardware.org/?probe=f23bdacb56) | Aug 11, 2022 |
| ASUSTek       | Maximus IX FORMULA          | [2212732244](https://linux-hardware.org/?probe=2212732244) | Aug 01, 2022 |
| MSI           | B450M PRO-VDH MAX           | [941092ee95](https://linux-hardware.org/?probe=941092ee95) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | [dfe6047aa7](https://linux-hardware.org/?probe=dfe6047aa7) | Jul 21, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | [f9996d6494](https://linux-hardware.org/?probe=f9996d6494) | Jul 21, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | [dde2246ae8](https://linux-hardware.org/?probe=dde2246ae8) | Jul 01, 2022 |
| ASRock        | Z87M Extreme4               | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| Gigabyte      | Z77X-UD3H                   | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| MSI           | B550-A PRO                  | [a7a76f04f9](https://linux-hardware.org/?probe=a7a76f04f9) | Jun 19, 2022 |
| MSI           | B450M MORTAR MAX            | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| T-bao         | MINI PC V1.0                | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| ASRock        | Z87M Extreme4               | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| ASRock        | X470 Taichi                 | [114aa0b977](https://linux-hardware.org/?probe=114aa0b977) | May 22, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| ASRock        | X470 Taichi                 | [bd151331c1](https://linux-hardware.org/?probe=bd151331c1) | May 04, 2022 |
| Dell          | 0WR7PY A01                  | [66c6e57421](https://linux-hardware.org/?probe=66c6e57421) | Apr 23, 2022 |
| ASRock        | B550M Pro4                  | [b82721163b](https://linux-hardware.org/?probe=b82721163b) | Apr 22, 2022 |
| ASRock        | X99X Killer                 | [c6d6bddd17](https://linux-hardware.org/?probe=c6d6bddd17) | Apr 18, 2022 |
| ASUSTek       | Z97-P                       | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| ASRock        | X99X Killer                 | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| ASRock        | X470 Taichi                 | [ba87ebf29f](https://linux-hardware.org/?probe=ba87ebf29f) | Apr 08, 2022 |
| ASUSTek       | P8B75-M                     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| HP            | 8433 11                     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| MSI           | B450-A PRO MAX              | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| Gigabyte      | B550 GAMING X V2            | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| ASRock        | X470 Taichi                 | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| MSI           | MAG B550 TOMAHAWK           | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| ASRock        | X470 Taichi                 | [df78a2fff6](https://linux-hardware.org/?probe=df78a2fff6) | Feb 14, 2022 |
| HP            | 8767 A                      | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP            | 8767 A                      | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| ASRock        | B450M Pro4                  | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| Lenovo        | 31900058 STD                | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| ASRock        | X470 Taichi                 | [e4beeac4a1](https://linux-hardware.org/?probe=e4beeac4a1) | Feb 06, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| ASRock        | X470 Taichi                 | [aa0e21b159](https://linux-hardware.org/?probe=aa0e21b159) | Jan 27, 2022 |
| Gigabyte      | B85-HD3                     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| ASRock        | 970M Pro3                   | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus X CODE          | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI           | Z270 GAMING M5              | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | [8a1167daea](https://linux-hardware.org/?probe=8a1167daea) | Jan 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [1a4570a458](https://linux-hardware.org/?probe=1a4570a458) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| Gigabyte      | B460M DS3H                  | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| Gigabyte      | B550 AORUS PRO AC           | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [9e73346fb8](https://linux-hardware.org/?probe=9e73346fb8) | Dec 15, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | [196b460373](https://linux-hardware.org/?probe=196b460373) | Dec 13, 2021 |
| ASRock        | H77M-ITX                    | [5e98a2fce2](https://linux-hardware.org/?probe=5e98a2fce2) | Dec 11, 2021 |
| ASRock        | B450M Pro4                  | [e4fb1e4fe4](https://linux-hardware.org/?probe=e4fb1e4fe4) | Dec 09, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | [731c890641](https://linux-hardware.org/?probe=731c890641) | Dec 08, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [f0df07c0e4](https://linux-hardware.org/?probe=f0df07c0e4) | Dec 06, 2021 |
| Acer          | Aspire TC-895 V:1.0         | [c743459a71](https://linux-hardware.org/?probe=c743459a71) | Dec 04, 2021 |
| ASUSTek       | H87M-E                      | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek       | H87M-E                      | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | [f031548aac](https://linux-hardware.org/?probe=f031548aac) | Dec 01, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | [48f73af82d](https://linux-hardware.org/?probe=48f73af82d) | Nov 30, 2021 |
| ASRock        | X470 Taichi                 | [0b1d816eff](https://linux-hardware.org/?probe=0b1d816eff) | Nov 28, 2021 |
| ASUSTek       | Rampage IV EXTREME          | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASRock        | X470 Taichi                 | [86f08832c0](https://linux-hardware.org/?probe=86f08832c0) | Oct 31, 2021 |
| ASUSTek       | P8B75-M                     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| MSI           | Z77A-G43                    | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI           | B460M PRO-VDH WIFI          | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| MSI           | B450M-A PRO MAX             | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| ASRock        | X470 Taichi                 | [ff6b763448](https://linux-hardware.org/?probe=ff6b763448) | Oct 16, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| ASUSTek       | PRIME B450M-K               | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| MSI           | H310M PRO-VDH PLUS          | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| Alienware     | 0TYR0X A00                  | [5ea23ebfb2](https://linux-hardware.org/?probe=5ea23ebfb2) | Aug 19, 2021 |
| ASRock        | X399 Professional Gaming    | [bb53a385c3](https://linux-hardware.org/?probe=bb53a385c3) | Aug 19, 2021 |
| Medion        | H110H4-EM2                  | [f4e01958e5](https://linux-hardware.org/?probe=f4e01958e5) | Aug 10, 2021 |
| ASRock        | X470 Taichi                 | [a919fef17f](https://linux-hardware.org/?probe=a919fef17f) | Aug 07, 2021 |
| MSI           | Z97 MPOWER                  | [dee7d3af4a](https://linux-hardware.org/?probe=dee7d3af4a) | Aug 06, 2021 |
| MSI           | Z97 MPOWER                  | [f30e5a3a86](https://linux-hardware.org/?probe=f30e5a3a86) | Aug 06, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [826edd51bc](https://linux-hardware.org/?probe=826edd51bc) | Jul 07, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [aa05cca9b7](https://linux-hardware.org/?probe=aa05cca9b7) | Jun 30, 2021 |
| Biostar       | H310MHP                     | [0d3f648f3e](https://linux-hardware.org/?probe=0d3f648f3e) | Jun 30, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [fb3d7de63c](https://linux-hardware.org/?probe=fb3d7de63c) | Jun 26, 2021 |
| MSI           | A320M-HDV R4.0              | [486775a989](https://linux-hardware.org/?probe=486775a989) | Jun 23, 2021 |
| MSI           | A320M-HDV R4.0              | [4629f86f56](https://linux-hardware.org/?probe=4629f86f56) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | [69dea4e3cf](https://linux-hardware.org/?probe=69dea4e3cf) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | [2fd89c951e](https://linux-hardware.org/?probe=2fd89c951e) | Jun 22, 2021 |
| MSI           | X370 GAMING PRO CARBON      | [9ead1e1bb5](https://linux-hardware.org/?probe=9ead1e1bb5) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [8144c83b50](https://linux-hardware.org/?probe=8144c83b50) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [376c0ff95d](https://linux-hardware.org/?probe=376c0ff95d) | Jun 15, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | [34801a2f74](https://linux-hardware.org/?probe=34801a2f74) | Jun 12, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [51e1e33185](https://linux-hardware.org/?probe=51e1e33185) | May 20, 2021 |
| MSI           | B350M GAMING PRO            | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| Dell          | 0D28YY A02                  | [14edf3bd00](https://linux-hardware.org/?probe=14edf3bd00) | May 16, 2021 |
| Gigabyte      | A320M-S2H-CF                | [066f815622](https://linux-hardware.org/?probe=066f815622) | May 12, 2021 |
| HP            | 844C                        | [29f7cf64ce](https://linux-hardware.org/?probe=29f7cf64ce) | May 06, 2021 |
| HP            | 844C                        | [0534f06ec4](https://linux-hardware.org/?probe=0534f06ec4) | May 06, 2021 |
| ASUSTek       | PRIME Z590-A                | [cb3058760e](https://linux-hardware.org/?probe=cb3058760e) | May 04, 2021 |
| Gigabyte      | P67A-UD3-B3                 | [08ea956bfa](https://linux-hardware.org/?probe=08ea956bfa) | Apr 24, 2021 |
| MSI           | Z87 MPOWER                  | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASRock        | AB350M-HDV                  | [23502edac5](https://linux-hardware.org/?probe=23502edac5) | Apr 01, 2021 |
| ASRock        | AB350M-HDV                  | [13b2fdddc0](https://linux-hardware.org/?probe=13b2fdddc0) | Apr 01, 2021 |
| Dell          | 07KY25 A01                  | [8c4f2f9922](https://linux-hardware.org/?probe=8c4f2f9922) | Mar 31, 2021 |
| Dell          | 07KY25 A01                  | [1b9efb1b29](https://linux-hardware.org/?probe=1b9efb1b29) | Mar 24, 2021 |
| Gigabyte      | B450 AORUS M                | [097a0d616c](https://linux-hardware.org/?probe=097a0d616c) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | [22054ffd75](https://linux-hardware.org/?probe=22054ffd75) | Mar 18, 2021 |
| HP            | 2AF7                        | [e0639ea4a5](https://linux-hardware.org/?probe=e0639ea4a5) | Mar 11, 2021 |
| HP            | 2AF7                        | [fb8d76722c](https://linux-hardware.org/?probe=fb8d76722c) | Mar 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [c1f22a7521](https://linux-hardware.org/?probe=c1f22a7521) | Mar 05, 2021 |
| Gigabyte      | GA-MA790FXT-UD5P            | [404dab2464](https://linux-hardware.org/?probe=404dab2464) | Feb 27, 2021 |
| ASRock        | FM2A88X Extreme6+           | [13f9fc2ef3](https://linux-hardware.org/?probe=13f9fc2ef3) | Feb 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [2e19f3b1af](https://linux-hardware.org/?probe=2e19f3b1af) | Feb 18, 2021 |
| Dell          | 0C2KJT A00                  | [f821a0035b](https://linux-hardware.org/?probe=f821a0035b) | Feb 12, 2021 |
| ASUSTek       | PRIME B360M-K               | [b73941c431](https://linux-hardware.org/?probe=b73941c431) | Feb 08, 2021 |
| HP            | 1825                        | [3b6b80db46](https://linux-hardware.org/?probe=3b6b80db46) | Jan 31, 2021 |
| HP            | 1825                        | [1df894dea4](https://linux-hardware.org/?probe=1df894dea4) | Jan 31, 2021 |
| ASRock        | X470 Master SLI             | [36eaf717e9](https://linux-hardware.org/?probe=36eaf717e9) | Jan 26, 2021 |
| ASRock        | X470 Master SLI             | [b1be9375c0](https://linux-hardware.org/?probe=b1be9375c0) | Jan 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [7332b50f98](https://linux-hardware.org/?probe=7332b50f98) | Jan 24, 2021 |
| ASUSTek       | PRIME H270-PLUS             | [3f895b585b](https://linux-hardware.org/?probe=3f895b585b) | Jan 22, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [61976e9745](https://linux-hardware.org/?probe=61976e9745) | Jan 18, 2021 |
| MSI           | X399 SLI PLUS               | [e392838a54](https://linux-hardware.org/?probe=e392838a54) | Jan 10, 2021 |
| ASUSTek       | CM5671                      | [069344a54e](https://linux-hardware.org/?probe=069344a54e) | Jan 07, 2021 |
| MSI           | B85-G43 GAMING              | [8fe013f04a](https://linux-hardware.org/?probe=8fe013f04a) | Jan 04, 2021 |
| ASRock        | G41M-VS3                    | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| Pegatron      | 2AC2A                       | [436a2ca3ce](https://linux-hardware.org/?probe=436a2ca3ce) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | [2df3b195c6](https://linux-hardware.org/?probe=2df3b195c6) | Dec 25, 2020 |
| ASUSTek       | PRIME Z370-P                | [35365be0e8](https://linux-hardware.org/?probe=35365be0e8) | Dec 19, 2020 |
| MSI           | Z390-A PRO                  | [ea7a52fdac](https://linux-hardware.org/?probe=ea7a52fdac) | Dec 16, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [62a5c95d51](https://linux-hardware.org/?probe=62a5c95d51) | Dec 14, 2020 |
| HP            | 8643 SMVB                   | [dccfba36f1](https://linux-hardware.org/?probe=dccfba36f1) | Dec 06, 2020 |
| Gigabyte      | B450 AORUS ELITE            | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| MSI           | Z390-A PRO                  | [05e3eb32c9](https://linux-hardware.org/?probe=05e3eb32c9) | Dec 03, 2020 |
| MSI           | Z390-A PRO                  | [dc6ea9bfb8](https://linux-hardware.org/?probe=dc6ea9bfb8) | Nov 29, 2020 |
| ASUSTek       | M5A97 LE R2.0               | [d4b3f84c86](https://linux-hardware.org/?probe=d4b3f84c86) | Nov 28, 2020 |
| Gigabyte      | B450 AORUS M                | [a3d68dc126](https://linux-hardware.org/?probe=a3d68dc126) | Nov 19, 2020 |
| Gigabyte      | B450 AORUS M                | [d9faeae0d4](https://linux-hardware.org/?probe=d9faeae0d4) | Nov 19, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [11c79940a4](https://linux-hardware.org/?probe=11c79940a4) | Nov 19, 2020 |
| HP            | 18E7                        | [f84cbfd465](https://linux-hardware.org/?probe=f84cbfd465) | Nov 10, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [79608bd849](https://linux-hardware.org/?probe=79608bd849) | Nov 06, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [e80ddac12f](https://linux-hardware.org/?probe=e80ddac12f) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | [876b039494](https://linux-hardware.org/?probe=876b039494) | Nov 01, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | [4e573bc6ff](https://linux-hardware.org/?probe=4e573bc6ff) | Oct 28, 2020 |
| MSI           | MPG B550 GAMING EDGE WIF... | [4b9d2b77cb](https://linux-hardware.org/?probe=4b9d2b77cb) | Oct 26, 2020 |
| ASUSTek       | PRIME X399-A                | [b7772d9ff8](https://linux-hardware.org/?probe=b7772d9ff8) | Oct 13, 2020 |
| Dell          | 0R6JMP A00                  | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| OEM           | Unknown                     | [2e7a212437](https://linux-hardware.org/?probe=2e7a212437) | Sep 26, 2020 |
| Lenovo        | ThinkCentre M91p 7033CG1    | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | [7b8babe846](https://linux-hardware.org/?probe=7b8babe846) | Aug 27, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | [73462df387](https://linux-hardware.org/?probe=73462df387) | Aug 07, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Desktops | Percent |
|----------------------|----------|---------|
| Garuda Linux Soaring | 136      | 56.43%  |
| Garuda Linux         | 54       | 22.41%  |
| Garuda Linux Rolling | 51       | 21.16%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Garuda Linux | 236      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 6.6.8-zen1-1-zen   | 6        | 2.14%   |
| 5.17.1-zen1-1-zen  | 6        | 2.14%   |
| 6.6.7-zen1-1-zen   | 4        | 1.42%   |
| 6.5.9-zen2-1-zen   | 4        | 1.42%   |
| 6.4.10-zen2-1-zen  | 4        | 1.42%   |
| 6.2.10-zen1-1-zen  | 4        | 1.42%   |
| 6.1.12-zen1-1-zen  | 4        | 1.42%   |
| 6.1.1-zen1-1-zen   | 4        | 1.42%   |
| 5.15.7-zen1-1-zen  | 4        | 1.42%   |
| 5.10.4-107-tkg-bmq | 4        | 1.42%   |
| 6.7.0-zen3-1-zen   | 3        | 1.07%   |
| 6.5.5-zen1-1-zen   | 3        | 1.07%   |
| 6.5.4-zen2-1-zen   | 3        | 1.07%   |
| 6.5.2-zen1-1-zen   | 3        | 1.07%   |
| 6.4.6-zen1-1-zen   | 3        | 1.07%   |
| 6.4.12-zen1-1-zen  | 3        | 1.07%   |
| 6.3.2-zen1-1-zen   | 3        | 1.07%   |
| 6.1.8-zen1-1-zen   | 3        | 1.07%   |
| 6.0.2-zen1-1-zen   | 3        | 1.07%   |
| 6.0.12-zen1-1-zen  | 3        | 1.07%   |
| 6.0.11-zen1-1-zen  | 3        | 1.07%   |
| 5.9.1-zen2-1-zen   | 3        | 1.07%   |
| 5.18.12-zen1-1-zen | 3        | 1.07%   |
| 5.18.1-zen1-1-zen  | 3        | 1.07%   |
| 5.16.4-zen1-1-zen  | 3        | 1.07%   |
| 5.15.2-zen1-1-zen  | 3        | 1.07%   |
| 5.15.13-zen1-1-zen | 3        | 1.07%   |
| 5.11.16-zen1-1-zen | 3        | 1.07%   |
| 6.6.3-zen1-1-zen   | 2        | 0.71%   |
| 6.5.7-zen2-1-zen   | 2        | 0.71%   |
| 6.4.9-zen1-1-zen   | 2        | 0.71%   |
| 6.4.3-zen1-1-zen   | 2        | 0.71%   |
| 6.3.6-zen1-1-zen   | 2        | 0.71%   |
| 6.2.7-zen1-1-zen   | 2        | 0.71%   |
| 6.2.2-zen2-1-zen   | 2        | 0.71%   |
| 6.2.13-zen-1-zen   | 2        | 0.71%   |
| 6.2.12-zen1-1-zen  | 2        | 0.71%   |
| 6.2.11-zen1-1-zen  | 2        | 0.71%   |
| 6.1.4-zen2-1-zen   | 2        | 0.71%   |
| 6.1.3-zen1-1-zen   | 2        | 0.71%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.6.8   | 7        | 2.49%   |
| 5.17.1  | 7        | 2.49%   |
| 6.5.5   | 5        | 1.78%   |
| 6.4.10  | 5        | 1.78%   |
| 6.6.7   | 4        | 1.42%   |
| 6.5.9   | 4        | 1.42%   |
| 6.2.10  | 4        | 1.42%   |
| 6.1.12  | 4        | 1.42%   |
| 6.1.1   | 4        | 1.42%   |
| 5.15.7  | 4        | 1.42%   |
| 5.10.4  | 4        | 1.42%   |
| 6.7.0   | 3        | 1.07%   |
| 6.5.4   | 3        | 1.07%   |
| 6.5.2   | 3        | 1.07%   |
| 6.4.6   | 3        | 1.07%   |
| 6.4.3   | 3        | 1.07%   |
| 6.4.12  | 3        | 1.07%   |
| 6.3.2   | 3        | 1.07%   |
| 6.2.2   | 3        | 1.07%   |
| 6.1.8   | 3        | 1.07%   |
| 6.1.4   | 3        | 1.07%   |
| 6.0.2   | 3        | 1.07%   |
| 6.0.12  | 3        | 1.07%   |
| 6.0.11  | 3        | 1.07%   |
| 5.9.1   | 3        | 1.07%   |
| 5.18.12 | 3        | 1.07%   |
| 5.18.1  | 3        | 1.07%   |
| 5.17.5  | 3        | 1.07%   |
| 5.16.4  | 3        | 1.07%   |
| 5.15.2  | 3        | 1.07%   |
| 5.15.13 | 3        | 1.07%   |
| 5.12.13 | 3        | 1.07%   |
| 5.11.16 | 3        | 1.07%   |
| 6.6.3   | 2        | 0.71%   |
| 6.6.2   | 2        | 0.71%   |
| 6.5.7   | 2        | 0.71%   |
| 6.4.9   | 2        | 0.71%   |
| 6.4.2   | 2        | 0.71%   |
| 6.3.6   | 2        | 0.71%   |
| 6.2.7   | 2        | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 29       | 10.78%  |
| 6.4     | 24       | 8.92%   |
| 6.6     | 22       | 8.18%   |
| 5.15    | 20       | 7.43%   |
| 6.5     | 18       | 6.69%   |
| 6.0     | 16       | 5.95%   |
| 5.16    | 16       | 5.95%   |
| 5.10    | 16       | 5.95%   |
| 6.2     | 15       | 5.58%   |
| 5.18    | 14       | 5.2%    |
| 5.17    | 11       | 4.09%   |
| 5.12    | 10       | 3.72%   |
| 5.11    | 10       | 3.72%   |
| 6.3     | 9        | 3.35%   |
| 5.9     | 9        | 3.35%   |
| 5.19    | 8        | 2.97%   |
| 5.13    | 7        | 2.6%    |
| 5.14    | 6        | 2.23%   |
| 5.8     | 5        | 1.86%   |
| 6.7     | 4        | 1.49%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 236      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 166      | 68.6%   |
| GNOME      | 27       | 11.16%  |
| KDE        | 19       | 7.85%   |
| XFCE       | 13       | 5.37%   |
| X-Cinnamon | 4        | 1.65%   |
| LXQt       | 3        | 1.24%   |
| sway       | 2        | 0.83%   |
| Deepin     | 2        | 0.83%   |
| Unknown    | 2        | 0.83%   |
| MATE       | 1        | 0.41%   |
| i3         | 1        | 0.41%   |
| Hyprland   | 1        | 0.41%   |
| Cinnamon   | 1        | 0.41%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 199      | 82.92%  |
| Wayland | 32       | 13.33%  |
| Tty     | 6        | 2.5%    |
| Unknown | 3        | 1.25%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 102      | 42.68%  |
| Unknown | 99       | 41.42%  |
| LightDM | 24       | 10.04%  |
| GDM     | 11       | 4.6%    |
| GREETD  | 3        | 1.26%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 112      | 47.26%  |
| de_DE | 22       | 9.28%   |
| en_GB | 21       | 8.86%   |
| en_CA | 11       | 4.64%   |
| es_ES | 9        | 3.8%    |
| it_IT | 8        | 3.38%   |
| fr_FR | 5        | 2.11%   |
| en_AU | 5        | 2.11%   |
| pt_BR | 4        | 1.69%   |
| nl_NL | 4        | 1.69%   |
| ru_RU | 3        | 1.27%   |
| en_IN | 3        | 1.27%   |
| sk_SK | 2        | 0.84%   |
| pl_PL | 2        | 0.84%   |
| hu_HU | 2        | 0.84%   |
| fr_BE | 2        | 0.84%   |
| en_ZA | 2        | 0.84%   |
| da_DK | 2        | 0.84%   |
| sv_SE | 1        | 0.42%   |
| sl_SI | 1        | 0.42%   |
| nl_BE | 1        | 0.42%   |
| nb_NO | 1        | 0.42%   |
| ja_JP | 1        | 0.42%   |
| iu_CA | 1        | 0.42%   |
| es_VE | 1        | 0.42%   |
| es_MX | 1        | 0.42%   |
| es_CL | 1        | 0.42%   |
| es_AR | 1        | 0.42%   |
| en_SG | 1        | 0.42%   |
| en_IE | 1        | 0.42%   |
| en_DK | 1        | 0.42%   |
| en_DE | 1        | 0.42%   |
| el_GR | 1        | 0.42%   |
| de_CH | 1        | 0.42%   |
| de_AT | 1        | 0.42%   |
| cs_CZ | 1        | 0.42%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 134      | 56.54%  |
| BIOS | 103      | 43.46%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 229      | 97.03%  |
| Tmpfs   | 3        | 1.27%   |
| Overlay | 2        | 0.85%   |
| Ext4    | 2        | 0.85%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 134      | 56.3%   |
| Unknown | 98       | 41.18%  |
| MBR     | 6        | 2.52%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 191      | 79.58%  |
| Yes       | 49       | 20.42%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 158      | 65.56%  |
| Yes       | 83       | 34.44%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 71       | 30.08%  |
| Gigabyte Technology                  | 40       | 16.95%  |
| MSI                                  | 38       | 16.1%   |
| ASRock                               | 24       | 10.17%  |
| Hewlett-Packard                      | 15       | 6.36%   |
| Dell                                 | 12       | 5.08%   |
| Lenovo                               | 8        | 3.39%   |
| Intel                                | 6        | 2.54%   |
| Acer                                 | 4        | 1.69%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.85%   |
| Pegatron                             | 2        | 0.85%   |
| Biostar                              | 2        | 0.85%   |
| Alienware                            | 2        | 0.85%   |
| Win element                          | 1        | 0.42%   |
| T-bao                                | 1        | 0.42%   |
| OEM                                  | 1        | 0.42%   |
| NZXT                                 | 1        | 0.42%   |
| Medion                               | 1        | 0.42%   |
| HC Technology.                       | 1        | 0.42%   |
| Fujitsu                              | 1        | 0.42%   |
| BESSTAR Tech                         | 1        | 0.42%   |
| AZW                                  | 1        | 0.42%   |
| Unknown                              | 1        | 0.42%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS TUF Gaming X570-PLUS                  | 8        | 3.39%   |
| MSI MS-7C91                                | 3        | 1.27%   |
| MSI MS-7B86                                | 3        | 1.27%   |
| ASUS All Series                            | 3        | 1.27%   |
| MSI MS-7D75                                | 2        | 0.85%   |
| MSI MS-7C37                                | 2        | 0.85%   |
| MSI MS-7C02                                | 2        | 0.85%   |
| HP ProDesk 600 G1 SFF                      | 2        | 0.85%   |
| HP Pavilion Gaming Desktop 690-00xx        | 2        | 0.85%   |
| HP EliteDesk 800 G1 SFF                    | 2        | 0.85%   |
| Gigabyte X570 AORUS PRO WIFI               | 2        | 0.85%   |
| Gigabyte B550 AORUS PRO AC                 | 2        | 0.85%   |
| Gigabyte B450 AORUS ELITE                  | 2        | 0.85%   |
| Gigabyte AB350-Gaming 3                    | 2        | 0.85%   |
| Dell OptiPlex 7010                         | 2        | 0.85%   |
| Dell Inspiron 3668                         | 2        | 0.85%   |
| ASUS TUF Gaming B550-PLUS WIFI II          | 2        | 0.85%   |
| ASUS TUF Gaming B550-PLUS                  | 2        | 0.85%   |
| ASUS ROG STRIX X570-E GAMING               | 2        | 0.85%   |
| ASUS ROG STRIX B550-F GAMING               | 2        | 0.85%   |
| ASUS PRIME Z590-A                          | 2        | 0.85%   |
| ASUS PRIME X570-P                          | 2        | 0.85%   |
| ASRock B450M-HDV R4.0                      | 2        | 0.85%   |
| Unknown                                    | 2        | 0.85%   |
| Win element M600                           | 1        | 0.42%   |
| T-bao MINI PC                              | 1        | 0.42%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.42%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.42%   |
| Pegatron p7-1030                           | 1        | 0.42%   |
| Pegatron h9-1301es                         | 1        | 0.42%   |
| NZXT N7 B550                               | 1        | 0.42%   |
| MSI MS-7E10                                | 1        | 0.42%   |
| MSI MS-7D96                                | 1        | 0.42%   |
| MSI MS-7D25                                | 1        | 0.42%   |
| MSI MS-7D16                                | 1        | 0.42%   |
| MSI MS-7C90                                | 1        | 0.42%   |
| MSI MS-7C83                                | 1        | 0.42%   |
| MSI MS-7C56                                | 1        | 0.42%   |
| MSI MS-7C52                                | 1        | 0.42%   |
| MSI MS-7C09                                | 1        | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS TUF                                   | 17       | 7.2%    |
| ASUS ROG                                   | 17       | 7.2%    |
| ASUS PRIME                                 | 17       | 7.2%    |
| Dell OptiPlex                              | 6        | 2.54%   |
| Lenovo ThinkCentre                         | 5        | 2.12%   |
| Gigabyte X570                              | 5        | 2.12%   |
| Dell Inspiron                              | 5        | 2.12%   |
| HP Pavilion                                | 4        | 1.69%   |
| HP EliteDesk                               | 4        | 1.69%   |
| Gigabyte B550                              | 4        | 1.69%   |
| Gigabyte B450                              | 4        | 1.69%   |
| MSI MS-7C91                                | 3        | 1.27%   |
| MSI MS-7B86                                | 3        | 1.27%   |
| ASUS All                                   | 3        | 1.27%   |
| MSI MS-7D75                                | 2        | 0.85%   |
| MSI MS-7C37                                | 2        | 0.85%   |
| MSI MS-7C02                                | 2        | 0.85%   |
| HP ProDesk                                 | 2        | 0.85%   |
| Gigabyte B450M                             | 2        | 0.85%   |
| Gigabyte AB350-Gaming                      | 2        | 0.85%   |
| ASUS Rampage                               | 2        | 0.85%   |
| ASUS Maximus                               | 2        | 0.85%   |
| ASRock X470                                | 2        | 0.85%   |
| ASRock B450M-HDV                           | 2        | 0.85%   |
| Alienware Aurora                           | 2        | 0.85%   |
| Acer Aspire                                | 2        | 0.85%   |
| Unknown                                    | 2        | 0.85%   |
| Win element M600                           | 1        | 0.42%   |
| T-bao MINI                                 | 1        | 0.42%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.42%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.42%   |
| Pegatron p7-1030                           | 1        | 0.42%   |
| Pegatron h9-1301es                         | 1        | 0.42%   |
| NZXT N7                                    | 1        | 0.42%   |
| MSI MS-7E10                                | 1        | 0.42%   |
| MSI MS-7D96                                | 1        | 0.42%   |
| MSI MS-7D25                                | 1        | 0.42%   |
| MSI MS-7D16                                | 1        | 0.42%   |
| MSI MS-7C90                                | 1        | 0.42%   |
| MSI MS-7C83                                | 1        | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 35       | 14.83%  |
| 2018 | 33       | 13.98%  |
| 2020 | 30       | 12.71%  |
| 2017 | 23       | 9.75%   |
| 2022 | 20       | 8.47%   |
| 2021 | 20       | 8.47%   |
| 2013 | 17       | 7.2%    |
| 2014 | 15       | 6.36%   |
| 2012 | 14       | 5.93%   |
| 2016 | 7        | 2.97%   |
| 2011 | 7        | 2.97%   |
| 2015 | 4        | 1.69%   |
| 2010 | 4        | 1.69%   |
| 2023 | 3        | 1.27%   |
| 2009 | 3        | 1.27%   |
| 2008 | 1        | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 236      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 236      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 236      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 80       | 33.47%  |
| 16.01-24.0  | 70       | 29.29%  |
| 8.01-16.0   | 32       | 13.39%  |
| 4.01-8.0    | 19       | 7.95%   |
| 64.01-256.0 | 18       | 7.53%   |
| 24.01-32.0  | 15       | 6.28%   |
| 3.01-4.0    | 5        | 2.09%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 105      | 41.18%  |
| 3.01-4.0    | 49       | 19.22%  |
| 8.01-16.0   | 38       | 14.9%   |
| 2.01-3.0    | 37       | 14.51%  |
| 1.01-2.0    | 13       | 5.1%    |
| 16.01-24.0  | 11       | 4.31%   |
| 32.01-64.0  | 1        | 0.39%   |
| 64.01-256.0 | 1        | 0.39%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 69       | 28.4%   |
| 3      | 56       | 23.05%  |
| 1      | 44       | 18.11%  |
| 4      | 33       | 13.58%  |
| 5      | 22       | 9.05%   |
| 6      | 9        | 3.7%    |
| 9      | 5        | 2.06%   |
| 7      | 2        | 0.82%   |
| 18     | 1        | 0.41%   |
| 14     | 1        | 0.41%   |
| 11     | 1        | 0.41%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 176      | 74.26%  |
| Yes       | 61       | 25.74%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 233      | 98.73%  |
| No        | 3        | 1.27%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 137      | 56.61%  |
| No        | 105      | 43.39%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 122      | 50.62%  |
| No        | 119      | 49.38%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 63       | 26.69%  |
| Germany      | 31       | 13.14%  |
| Italy        | 14       | 5.93%   |
| Canada       | 14       | 5.93%   |
| UK           | 10       | 4.24%   |
| Spain        | 9        | 3.81%   |
| Brazil       | 7        | 2.97%   |
| Sweden       | 6        | 2.54%   |
| Netherlands  | 6        | 2.54%   |
| France       | 6        | 2.54%   |
| Australia    | 5        | 2.12%   |
| Russia       | 4        | 1.69%   |
| Poland       | 4        | 1.69%   |
| India        | 4        | 1.69%   |
| Belgium      | 4        | 1.69%   |
| Romania      | 3        | 1.27%   |
| Norway       | 3        | 1.27%   |
| Denmark      | 3        | 1.27%   |
| Austria      | 3        | 1.27%   |
| South Africa | 2        | 0.85%   |
| Slovakia     | 2        | 0.85%   |
| Puerto Rico  | 2        | 0.85%   |
| Philippines  | 2        | 0.85%   |
| Mexico       | 2        | 0.85%   |
| Latvia       | 2        | 0.85%   |
| Japan        | 2        | 0.85%   |
| Hungary      | 2        | 0.85%   |
| Greece       | 2        | 0.85%   |
| Chile        | 2        | 0.85%   |
| Venezuela    | 1        | 0.42%   |
| Ukraine      | 1        | 0.42%   |
| Turkey       | 1        | 0.42%   |
| Taiwan       | 1        | 0.42%   |
| Switzerland  | 1        | 0.42%   |
| Slovenia     | 1        | 0.42%   |
| Singapore    | 1        | 0.42%   |
| Serbia       | 1        | 0.42%   |
| Portugal     | 1        | 0.42%   |
| Lithuania    | 1        | 0.42%   |
| Israel       | 1        | 0.42%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Sydney                  | 3        | 1.23%   |
| Milan                   | 3        | 1.23%   |
| Dallas                  | 3        | 1.23%   |
| Berlin                  | 3        | 1.23%   |
| Wasmes                  | 2        | 0.82%   |
| Stockholm               | 2        | 0.82%   |
| St Louis                | 2        | 0.82%   |
| Sao Paulo               | 2        | 0.82%   |
| Santa Cruz de Tenerife  | 2        | 0.82%   |
| Saint Joseph            | 2        | 0.82%   |
| Riga                    | 2        | 0.82%   |
| Oklahoma City           | 2        | 0.82%   |
| Montreal                | 2        | 0.82%   |
| Melbourne               | 2        | 0.82%   |
| Mannheim                | 2        | 0.82%   |
| London                  | 2        | 0.82%   |
| Kingsport               | 2        | 0.82%   |
| Gaildorf                | 2        | 0.82%   |
| Fort St. John           | 2        | 0.82%   |
| Colfax                  | 2        | 0.82%   |
| Charlotte               | 2        | 0.82%   |
| Algeciras               | 2        | 0.82%   |
| Złotoryja              | 1        | 0.41%   |
| Zwickau                 | 1        | 0.41%   |
| York                    | 1        | 0.41%   |
| Wuppertal               | 1        | 0.41%   |
| Wil                     | 1        | 0.41%   |
| Wichita                 | 1        | 0.41%   |
| Weiterstadt             | 1        | 0.41%   |
| Weilen unter den Rinnen | 1        | 0.41%   |
| Waxahachie              | 1        | 0.41%   |
| Warsaw                  | 1        | 0.41%   |
| Voronezh                | 1        | 0.41%   |
| Volzhskiy               | 1        | 0.41%   |
| Vilnius                 | 1        | 0.41%   |
| Victoria                | 1        | 0.41%   |
| Veszprém               | 1        | 0.41%   |
| Veauche                 | 1        | 0.41%   |
| Västerås              | 1        | 0.41%   |
| Valenciennes            | 1        | 0.41%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 98       | 162    | 16.81%  |
| Samsung Electronics         | 91       | 195    | 15.61%  |
| Seagate                     | 89       | 142    | 15.27%  |
| Toshiba                     | 40       | 58     | 6.86%   |
| Kingston                    | 35       | 52     | 6%      |
| SanDisk                     | 33       | 43     | 5.66%   |
| Crucial                     | 31       | 39     | 5.32%   |
| Hitachi                     | 12       | 13     | 2.06%   |
| Micron/Crucial Technology   | 11       | 15     | 1.89%   |
| Silicon Motion              | 9        | 9      | 1.54%   |
| Intel                       | 8        | 11     | 1.37%   |
| Phison Electronics          | 7        | 9      | 1.2%    |
| Phison                      | 7        | 8      | 1.2%    |
| China                       | 7        | 10     | 1.2%    |
| MAXIO Technology (Hangzhou) | 6        | 6      | 1.03%   |
| Kingston Technology Company | 6        | 6      | 1.03%   |
| A-DATA Technology           | 6        | 9      | 1.03%   |
| PNY                         | 5        | 5      | 0.86%   |
| ADATA Technology            | 5        | 6      | 0.86%   |
| Unknown                     | 4        | 4      | 0.69%   |
| Team                        | 4        | 5      | 0.69%   |
| SPCC                        | 4        | 5      | 0.69%   |
| Realtek Semiconductor       | 4        | 6      | 0.69%   |
| OCZ                         | 4        | 4      | 0.69%   |
| HGST                        | 4        | 10     | 0.69%   |
| XPG                         | 3        | 4      | 0.51%   |
| Transcend                   | 3        | 3      | 0.51%   |
| SK hynix                    | 3        | 5      | 0.51%   |
| Micron Technology           | 3        | 3      | 0.51%   |
| Intenso                     | 3        | 4      | 0.51%   |
| Emtec                       | 3        | 5      | 0.51%   |
| TO Exter                    | 2        | 2      | 0.34%   |
| Patriot                     | 2        | 4      | 0.34%   |
| LITEONIT                    | 2        | 2      | 0.34%   |
| Hewlett-Packard             | 2        | 2      | 0.34%   |
| WD MediaMax                 | 1        | 1      | 0.17%   |
| USB30                       | 1        | 2      | 0.17%   |
| T-FORCE                     | 1        | 1      | 0.17%   |
| SSK                         | 1        | 1      | 0.17%   |
| SABRENT                     | 1        | 2      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                           | Desktops | Percent |
|-----------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB               | 17       | 2.44%   |
| Seagate ST2000DM008-2FR102 2TB                                  | 10       | 1.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB              | 10       | 1.44%   |
| Samsung SSD 850 EVO 250GB                                       | 9        | 1.29%   |
| Samsung SSD 860 EVO 500GB                                       | 8        | 1.15%   |
| Crucial CT1000MX500SSD1 1TB                                     | 8        | 1.15%   |
| Toshiba DT01ACA100 1TB                                          | 6        | 0.86%   |
| Seagate ST4000DM004-2CV104 4TB                                  | 6        | 0.86%   |
| Seagate ST1000DM010-2EP102 1TB                                  | 6        | 0.86%   |
| Samsung NVMe SSD Drive 1TB                                      | 6        | 0.86%   |
| WDC WD10EZEX-08WN4A0 1TB                                        | 5        | 0.72%   |
| Toshiba HDWD110 1TB                                             | 5        | 0.72%   |
| Samsung SSD 980 1TB                                             | 5        | 0.72%   |
| Samsung SSD 970 EVO Plus 500GB                                  | 5        | 0.72%   |
| Samsung SSD 850 EVO 500GB                                       | 5        | 0.72%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                             | 5        | 0.72%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 512GB              | 5        | 0.72%   |
| Kingston SA400S37480G 480GB SSD                                 | 5        | 0.72%   |
| Crucial CT500MX500SSD1 500GB                                    | 5        | 0.72%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                        | 4        | 0.57%   |
| WDC WD10EZEX-60WN4A0 1TB                                        | 4        | 0.57%   |
| Toshiba DT01ACA050 500GB                                        | 4        | 0.57%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 128GB           | 4        | 0.57%   |
| Seagate ST2000DM006-2DM164 2TB                                  | 4        | 0.57%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                            | 4        | 0.57%   |
| SanDisk SSD PLUS 1000GB                                         | 4        | 0.57%   |
| Samsung SSD 860 QVO 1TB                                         | 4        | 0.57%   |
| Samsung SSD 860 EVO 250GB                                       | 4        | 0.57%   |
| Samsung SSD 860 EVO 1TB                                         | 4        | 0.57%   |
| Samsung NVMe SSD Drive 500GB                                    | 4        | 0.57%   |
| Micron/Crucial P1 NVMe PCIe SSD 1TB                             | 4        | 0.57%   |
| Kingston SA400S37240G 240GB SSD                                 | 4        | 0.57%   |
| Kingston SA400S37120G 120GB SSD                                 | 4        | 0.57%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 2TB | 4        | 0.57%   |
| WDC WD60EZAZ-00SF3B0 6TB                                        | 3        | 0.43%   |
| WDC WD40EFZX-68AWUN0 4TB                                        | 3        | 0.43%   |
| WDC WD20EARX-00PASB0 2TB                                        | 3        | 0.43%   |
| WDC WD10EARS-00Y5B1 1TB                                         | 3        | 0.43%   |
| WDC WD10EALX-009BA0 1TB                                         | 3        | 0.43%   |
| Toshiba DT01ACA300 3TB                                          | 3        | 0.43%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 86       | 135    | 36.29%  |
| WDC                 | 85       | 146    | 35.86%  |
| Toshiba             | 33       | 44     | 13.92%  |
| Hitachi             | 12       | 13     | 5.06%   |
| Samsung Electronics | 5        | 5      | 2.11%   |
| HGST                | 4        | 10     | 1.69%   |
| Intenso             | 3        | 4      | 1.27%   |
| Unknown             | 2        | 2      | 0.84%   |
| TO Exter            | 2        | 2      | 0.84%   |
| SSK                 | 1        | 1      | 0.42%   |
| LaCie               | 1        | 1      | 0.42%   |
| Inateck             | 1        | 1      | 0.42%   |
| Hewlett-Packard     | 1        | 1      | 0.42%   |
| ASMedia             | 1        | 2      | 0.42%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 45       | 77     | 24.19%  |
| Crucial             | 27       | 33     | 14.52%  |
| Kingston            | 26       | 34     | 13.98%  |
| SanDisk             | 14       | 20     | 7.53%   |
| WDC                 | 10       | 10     | 5.38%   |
| Toshiba             | 7        | 13     | 3.76%   |
| China               | 7        | 10     | 3.76%   |
| A-DATA Technology   | 6        | 9      | 3.23%   |
| Team                | 4        | 5      | 2.15%   |
| SPCC                | 4        | 5      | 2.15%   |
| PNY                 | 4        | 4      | 2.15%   |
| OCZ                 | 4        | 4      | 2.15%   |
| Transcend           | 3        | 3      | 1.61%   |
| Emtec               | 3        | 5      | 1.61%   |
| SK hynix            | 2        | 4      | 1.08%   |
| LITEONIT            | 2        | 2      | 1.08%   |
| USB30               | 1        | 2      | 0.54%   |
| Unknown             | 1        | 1      | 0.54%   |
| T-FORCE             | 1        | 1      | 0.54%   |
| SABRENT             | 1        | 2      | 0.54%   |
| Qumo                | 1        | 1      | 0.54%   |
| Plextor             | 1        | 1      | 0.54%   |
| Patriot             | 1        | 3      | 0.54%   |
| Neo                 | 1        | 1      | 0.54%   |
| Mushkin             | 1        | 1      | 0.54%   |
| Micron Technology   | 1        | 1      | 0.54%   |
| LITEON              | 1        | 1      | 0.54%   |
| Lexar               | 1        | 1      | 0.54%   |
| Intel               | 1        | 1      | 0.54%   |
| HS-SSD-C100         | 1        | 1      | 0.54%   |
| GOODRAM             | 1        | 1      | 0.54%   |
| Fanxiang            | 1        | 1      | 0.54%   |
| DEXP                | 1        | 1      | 0.54%   |
| ADATA SU            | 1        | 1      | 0.54%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 171      | 367    | 37.34%  |
| NVMe    | 137      | 260    | 29.91%  |
| SSD     | 137      | 260    | 29.91%  |
| Unknown | 13       | 13     | 2.84%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 205      | 592    | 55.11%  |
| NVMe | 137      | 260    | 36.83%  |
| SAS  | 30       | 48     | 8.06%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 134      | 255    | 36.02%  |
| 0.51-1.0   | 120      | 178    | 32.26%  |
| 1.01-2.0   | 65       | 109    | 17.47%  |
| 3.01-4.0   | 19       | 35     | 5.11%   |
| 2.01-3.0   | 16       | 27     | 4.3%    |
| 4.01-10.0  | 16       | 20     | 4.3%    |
| 10.01-20.0 | 2        | 3      | 0.54%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 135      | 56.72%  |
| 1001-2000      | 37       | 15.55%  |
| 2001-3000      | 30       | 12.61%  |
| 501-1000       | 16       | 6.72%   |
| 251-500        | 10       | 4.2%    |
| Unknown        | 6        | 2.52%   |
| 101-250        | 2        | 0.84%   |
| 1-20           | 2        | 0.84%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 45       | 18%     |
| 101-250        | 39       | 15.6%   |
| 251-500        | 38       | 15.2%   |
| 501-1000       | 35       | 14%     |
| 1001-2000      | 34       | 13.6%   |
| 2001-3000      | 27       | 10.8%   |
| 51-100         | 19       | 7.6%    |
| Unknown        | 6        | 2.4%    |
| 21-50          | 4        | 1.6%    |
| 1-20           | 3        | 1.2%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                         | Desktops | Drives | Percent |
|---------------------------------------------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB                                      | 2        | 2      | 3.77%   |
| Toshiba DT01ACA050 500GB                                      | 2        | 2      | 3.77%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 2TB       | 2        | 3      | 3.77%   |
| Intenso USB 3.0 device 1TB                                    | 2        | 2      | 3.77%   |
| WDC WD6400AAKS-65A7B0 640GB                                   | 1        | 1      | 1.89%   |
| WDC WD5000AAKX-60U6AA0 500GB                                  | 1        | 1      | 1.89%   |
| WDC WD5000AAKX-003CA0 500GB                                   | 1        | 2      | 1.89%   |
| WDC WD5000AAKS-00E4A0 500GB                                   | 1        | 1      | 1.89%   |
| WDC WD40EZRZ-00WN9B0 4TB                                      | 1        | 1      | 1.89%   |
| WDC WD30EZRX-00DC0B0 3TB                                      | 1        | 1      | 1.89%   |
| WDC WD30EFRX-68EUZN0 3TB                                      | 1        | 2      | 1.89%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                      | 1        | 1      | 1.89%   |
| WDC WD20EARX-00PASB0 2TB                                      | 1        | 1      | 1.89%   |
| WDC WD2002FAEX-007BA0 2TB                                     | 1        | 1      | 1.89%   |
| WDC WD15EADS-22P8B0 1TB                                       | 1        | 2      | 1.89%   |
| WDC WD10EZRX-00L4HB0 1TB                                      | 1        | 1      | 1.89%   |
| WDC WD10EZEX-75WN4A1 1TB                                      | 1        | 1      | 1.89%   |
| WDC WD10EZEX-60ZF5A0 1TB                                      | 1        | 1      | 1.89%   |
| WDC WD10EARS-00Y5B1 1TB                                       | 1        | 1      | 1.89%   |
| WDC WD10EALX-009BA0 1TB                                       | 1        | 1      | 1.89%   |
| WDC WD10EADS-22M2B0 1TB                                       | 1        | 1      | 1.89%   |
| WDC WD10EADS-00M2B0 1TB                                       | 1        | 1      | 1.89%   |
| Transcend TS1TSSD230S 1TB                                     | 1        | 1      | 1.89%   |
| Toshiba DT01ACA100 1TB                                        | 1        | 1      | 1.89%   |
| Seagate ST9250827AS 250GB                                     | 1        | 1      | 1.89%   |
| Seagate ST4000DM004-2CV104 4TB                                | 1        | 1      | 1.89%   |
| Seagate ST3000DM003-1F216N 3TB                                | 1        | 1      | 1.89%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                            | 1        | 1      | 1.89%   |
| Seagate ST2000DX002-2DV164 2TB                                | 1        | 2      | 1.89%   |
| Seagate ST2000DM006-2DM164 2TB                                | 1        | 1      | 1.89%   |
| Seagate ST2000DL003-9VT166 2TB                                | 1        | 1      | 1.89%   |
| SanDisk SD6SF1M128G1022I 128GB SSD                            | 1        | 1      | 1.89%   |
| Samsung Electronics SSD 980 1TB                               | 1        | 8      | 1.89%   |
| Samsung Electronics SSD 960 EVO 250GB                         | 1        | 5      | 1.89%   |
| Samsung Electronics SSD 870 EVO 1TB                           | 1        | 1      | 1.89%   |
| Samsung Electronics SSD 850 PRO 512GB                         | 1        | 2      | 1.89%   |
| Samsung Electronics NVMe SSD Controller SM981/PM981/PM983 1TB | 1        | 1      | 1.89%   |
| OCZ TRION100 480GB SSD                                        | 1        | 1      | 1.89%   |
| Micron/Crucial Technology P2 NVMe PCIe SSD 1TB                | 1        | 1      | 1.89%   |
| Kingston SV300S37A120G 120GB SSD                              | 1        | 1      | 1.89%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                    | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| WDC                       | 18       | 23     | 37.5%   |
| Seagate                   | 7        | 8      | 14.58%  |
| Toshiba                   | 3        | 3      | 6.25%   |
| Samsung Electronics       | 3        | 17     | 6.25%   |
| Hitachi                   | 3        | 3      | 6.25%   |
| Realtek Semiconductor     | 2        | 3      | 4.17%   |
| Kingston                  | 2        | 2      | 4.17%   |
| Intenso                   | 2        | 2      | 4.17%   |
| Transcend                 | 1        | 1      | 2.08%   |
| SanDisk                   | 1        | 1      | 2.08%   |
| OCZ                       | 1        | 1      | 2.08%   |
| Micron/Crucial Technology | 1        | 1      | 2.08%   |
| HGST                      | 1        | 7      | 2.08%   |
| Hewlett-Packard           | 1        | 1      | 2.08%   |
| Crucial                   | 1        | 1      | 2.08%   |
| A-DATA Technology         | 1        | 1      | 2.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 18       | 23     | 52.94%  |
| Seagate | 7        | 8      | 20.59%  |
| Toshiba | 3        | 3      | 8.82%   |
| Hitachi | 3        | 3      | 8.82%   |
| Intenso | 2        | 2      | 5.88%   |
| HGST    | 1        | 7      | 2.94%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 28       | 46     | 65.12%  |
| SSD  | 9        | 10     | 20.93%  |
| NVMe | 6        | 19     | 13.95%  |

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
| Detected | 133      | 420    | 45.24%  |
| Works    | 122      | 405    | 41.5%   |
| Malfunc  | 39       | 75     | 13.27%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 132      | 31.58%  |
| Intel                        | 102      | 24.4%   |
| Samsung Electronics          | 55       | 13.16%  |
| SanDisk                      | 24       | 5.74%   |
| Kingston Technology Company  | 18       | 4.31%   |
| Phison Electronics           | 15       | 3.59%   |
| ASMedia Technology           | 14       | 3.35%   |
| Micron/Crucial Technology    | 13       | 3.11%   |
| Silicon Motion               | 10       | 2.39%   |
| ADATA Technology             | 7        | 1.67%   |
| MAXIO Technology (Hangzhou)  | 6        | 1.44%   |
| Realtek Semiconductor        | 5        | 1.2%    |
| Marvell Technology Group     | 5        | 1.2%    |
| Seagate Technology           | 2        | 0.48%   |
| Micron Technology            | 2        | 0.48%   |
| JMicron Technology           | 2        | 0.48%   |
| Union Memory (Shenzhen)      | 1        | 0.24%   |
| Toshiba America Info Systems | 1        | 0.24%   |
| SK hynix                     | 1        | 0.24%   |
| Shenzhen Longsys Electronics | 1        | 0.24%   |
| LSI Logic / Symbios Logic    | 1        | 0.24%   |
| Broadcom / LSI               | 1        | 0.24%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 73       | 14.54%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 39       | 7.77%   |
| AMD 400 Series Chipset SATA Controller                                         | 29       | 5.78%   |
| AMD 500 Series Chipset SATA Controller                                         | 27       | 5.38%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 16       | 3.19%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 14       | 2.79%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12       | 2.39%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 11       | 2.19%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 9        | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9        | 1.79%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 9        | 1.79%   |
| AMD 600 Series Chipset SATA Controller                                         | 9        | 1.79%   |
| Phison E12 NVMe Controller                                                     | 8        | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 8        | 1.59%   |
| AMD 300 Series Chipset SATA Controller                                         | 8        | 1.59%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers              | 7        | 1.39%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 7        | 1.39%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7        | 1.39%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 7        | 1.39%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 6        | 1.2%    |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 6        | 1.2%    |
| Intel SATA Controller [RAID mode]                                              | 6        | 1.2%    |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6        | 1.2%    |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                    | 6        | 1.2%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 5        | 1%      |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 5        | 1%      |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                       | 5        | 1%      |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 5        | 1%      |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 5        | 1%      |
| AMD FCH SATA Controller D                                                      | 5        | 1%      |
| Phison E16 PCIe4 NVMe Controller                                               | 4        | 0.8%    |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                      | 4        | 0.8%    |
| Silicon Motion SM2262/SM2262EN SSD Controller                                  | 3        | 0.6%    |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                     | 3        | 0.6%    |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                    | 3        | 0.6%    |
| Samsung NVMe SSD Controller S4LV008[Pascal]                                    | 3        | 0.6%    |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                              | 3        | 0.6%    |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller               | 3        | 0.6%    |
| Kingston Company NV2 NVMe SSD E21T (DRAM-less)                                 | 3        | 0.6%    |
| Kingston Company NV1 NVMe SSD SM2263XT (DRAM-less)                             | 3        | 0.6%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 217      | 56.07%  |
| NVMe | 138      | 35.66%  |
| IDE  | 18       | 4.65%   |
| RAID | 13       | 3.36%   |
| SAS  | 1        | 0.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 134      | 56.78%  |
| Intel  | 102      | 43.22%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 7 3700X 8-Core Processor          | 9        | 3.8%    |
| AMD Ryzen 9 3900X 12-Core Processor         | 8        | 3.38%   |
| AMD Ryzen 5 3600 6-Core Processor           | 8        | 3.38%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 6        | 2.53%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 2.53%   |
| Intel 12th Gen Core i5-12600K               | 5        | 2.11%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 5        | 2.11%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 5        | 2.11%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 1.69%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 1.69%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 4        | 1.69%   |
| AMD Ryzen 7 3800X 8-Core Processor          | 4        | 1.69%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4        | 1.69%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 1.69%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 4        | 1.69%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 4        | 1.69%   |
| AMD FX-8350 Eight-Core Processor            | 4        | 1.69%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 1.27%   |
| AMD Ryzen 9 7900X 12-Core Processor         | 3        | 1.27%   |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 1.27%   |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 1.27%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 1.27%   |
| Intel Core i7-8700K CPU @ 3.70GHz           | 2        | 0.84%   |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 0.84%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.84%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 0.84%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.84%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.84%   |
| Intel Core i3-9100F CPU @ 3.60GHz           | 2        | 0.84%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 0.84%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.84%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.84%   |
| Intel 11th Gen Core i5-11600KF @ 3.90GHz    | 2        | 0.84%   |
| AMD Ryzen 9 6900HX with Radeon Graphics     | 2        | 0.84%   |
| AMD Ryzen 7 7700 8-Core Processor           | 2        | 0.84%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 0.84%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 2        | 0.84%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 0.84%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1        | 0.42%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.42%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 7             | 42       | 17.8%   |
| AMD Ryzen 5             | 42       | 17.8%   |
| Intel Core i5           | 30       | 12.71%  |
| Intel Core i7           | 27       | 11.44%  |
| AMD Ryzen 9             | 23       | 9.75%   |
| Intel Core i3           | 17       | 7.2%    |
| Other                   | 13       | 5.51%   |
| AMD FX                  | 8        | 3.39%   |
| Intel Xeon              | 7        | 2.97%   |
| AMD Ryzen 3             | 6        | 2.54%   |
| AMD Ryzen Threadripper  | 3        | 1.27%   |
| Intel Core i9           | 2        | 0.85%   |
| Intel Celeron           | 2        | 0.85%   |
| AMD Phenom II X6        | 2        | 0.85%   |
| AMD A10                 | 2        | 0.85%   |
| Intel Pentium Dual-Core | 1        | 0.42%   |
| Intel Pentium           | 1        | 0.42%   |
| Intel Core 2 Quad       | 1        | 0.42%   |
| Intel Core 2 Duo        | 1        | 0.42%   |
| AMD Phenom II X4        | 1        | 0.42%   |
| AMD Phenom II X2        | 1        | 0.42%   |
| AMD Athlon X4           | 1        | 0.42%   |
| AMD Athlon              | 1        | 0.42%   |
| AMD A8                  | 1        | 0.42%   |
| AMD A4                  | 1        | 0.42%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 68       | 28.81%  |
| 8      | 56       | 23.73%  |
| 6      | 53       | 22.46%  |
| 2      | 25       | 10.59%  |
| 12     | 16       | 6.78%   |
| 16     | 7        | 2.97%   |
| 10     | 6        | 2.54%   |
| 24     | 2        | 0.85%   |
| 20     | 1        | 0.42%   |
| 14     | 1        | 0.42%   |
| 3      | 1        | 0.42%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 234      | 99.15%  |
| 2      | 2        | 0.85%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 189      | 80.08%  |
| 1      | 47       | 19.92%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 236      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 123      | 51.25%  |
| 0x08701021 | 11       | 4.58%   |
| 0x0800820d | 10       | 4.17%   |
| 0x306c3    | 7        | 2.92%   |
| 0x0a601203 | 7        | 2.92%   |
| 0x0a50000d | 6        | 2.5%    |
| 0x0a20120a | 6        | 2.5%    |
| 0x306a9    | 5        | 2.08%   |
| 0x206a7    | 5        | 2.08%   |
| 0x0a50000c | 4        | 1.67%   |
| 0xa0653    | 3        | 1.25%   |
| 0x906ea    | 3        | 1.25%   |
| 0x506e3    | 3        | 1.25%   |
| 0x0a201025 | 3        | 1.25%   |
| 0x0a201009 | 3        | 1.25%   |
| 0x08108109 | 3        | 1.25%   |
| 0x08001137 | 3        | 1.25%   |
| 0x906ed    | 2        | 0.83%   |
| 0x906e9    | 2        | 0.83%   |
| 0x90672    | 2        | 0.83%   |
| 0x0a404102 | 2        | 0.83%   |
| 0x0a201204 | 2        | 0.83%   |
| 0x0a201016 | 2        | 0.83%   |
| 0x08701013 | 2        | 0.83%   |
| 0x0810100b | 2        | 0.83%   |
| 0x08001138 | 2        | 0.83%   |
| 0x06000852 | 2        | 0.83%   |
| 0x010000dc | 2        | 0.83%   |
| 0xa0655    | 1        | 0.42%   |
| 0x906ec    | 1        | 0.42%   |
| 0x906eb    | 1        | 0.42%   |
| 0x90675    | 1        | 0.42%   |
| 0x306e4    | 1        | 0.42%   |
| 0x106a5    | 1        | 0.42%   |
| 0x1067a    | 1        | 0.42%   |
| 0x0a601201 | 1        | 0.42%   |
| 0x0a50000b | 1        | 0.42%   |
| 0x08701030 | 1        | 0.42%   |
| 0x08101016 | 1        | 0.42%   |
| 0x06003106 | 1        | 0.42%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 39       | 16.46%  |
| Zen 2            | 32       | 13.5%   |
| Zen+             | 24       | 10.13%  |
| KabyLake         | 22       | 9.28%   |
| Haswell          | 19       | 8.02%   |
| Unknown          | 17       | 7.17%   |
| IvyBridge        | 15       | 6.33%   |
| Zen              | 12       | 5.06%   |
| SandyBridge      | 11       | 4.64%   |
| Piledriver       | 9        | 3.8%    |
| CometLake        | 9        | 3.8%    |
| Alderlake Hybrid | 6        | 2.53%   |
| Skylake          | 5        | 2.11%   |
| K10              | 4        | 1.69%   |
| Steamroller      | 3        | 1.27%   |
| Penryn           | 3        | 1.27%   |
| Nehalem          | 2        | 0.84%   |
| Broadwell        | 2        | 0.84%   |
| Westmere         | 1        | 0.42%   |
| Jaguar           | 1        | 0.42%   |
| Icelake          | 1        | 0.42%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 119      | 44.91%  |
| Nvidia | 99       | 37.36%  |
| Intel  | 47       | 17.74%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 17       | 6.12%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 16       | 5.76%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 12       | 4.32%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 3.96%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 2.88%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 8        | 2.88%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 8        | 2.88%   |
| AMD Raphael                                                                 | 7        | 2.52%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 2.16%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 5        | 1.8%    |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 5        | 1.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.44%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.44%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.44%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 1.44%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.44%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 4        | 1.44%   |
| Intel HD Graphics 630                                                       | 4        | 1.44%   |
| Intel AlderLake-S GT1                                                       | 4        | 1.44%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.44%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX/7900M]                              | 4        | 1.44%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 1.44%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 3        | 1.08%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.08%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 1.08%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 3        | 1.08%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.08%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 3        | 1.08%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.08%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 3        | 1.08%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 1.08%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 3        | 1.08%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.08%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 3        | 1.08%   |
| AMD Navi 24 [Radeon RX 6400/6500 XT/6500M]                                  | 3        | 1.08%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 1.08%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.72%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 0.72%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 2        | 0.72%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 0.72%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 99       | 41.25%  |
| 1 x Nvidia     | 82       | 34.17%  |
| 1 x Intel      | 29       | 12.08%  |
| AMD + Nvidia   | 9        | 3.75%   |
| 2 x AMD        | 8        | 3.33%   |
| 2 x Nvidia     | 4        | 1.67%   |
| Intel + Nvidia | 4        | 1.67%   |
| Intel + AMD    | 4        | 1.67%   |
| 2 x Intel      | 1        | 0.42%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 153      | 64.02%  |
| Proprietary | 85       | 35.56%  |
| Unknown     | 1        | 0.42%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 86       | 35.68%  |
| 7.01-8.0   | 41       | 17.01%  |
| 8.01-16.0  | 33       | 13.69%  |
| 3.01-4.0   | 26       | 10.79%  |
| 1.01-2.0   | 21       | 8.71%   |
| 5.01-6.0   | 9        | 3.73%   |
| 0.01-0.5   | 9        | 3.73%   |
| 0.51-1.0   | 7        | 2.9%    |
| 16.01-24.0 | 6        | 2.49%   |
| 2.01-3.0   | 3        | 1.24%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 43       | 13.74%  |
| Dell                 | 33       | 10.54%  |
| Acer                 | 29       | 9.27%   |
| Goldstar             | 27       | 8.63%   |
| AOC                  | 25       | 7.99%   |
| Hewlett-Packard      | 17       | 5.43%   |
| BenQ                 | 14       | 4.47%   |
| Ancor Communications | 12       | 3.83%   |
| ASUSTek Computer     | 10       | 3.19%   |
| Philips              | 9        | 2.88%   |
| ViewSonic            | 7        | 2.24%   |
| Unknown              | 7        | 2.24%   |
| Gigabyte Technology  | 7        | 2.24%   |
| MSI                  | 6        | 1.92%   |
| NEC Computers        | 5        | 1.6%    |
| Iiyama               | 5        | 1.6%    |
| Sony                 | 3        | 0.96%   |
| Mi                   | 3        | 0.96%   |
| Lenovo               | 3        | 0.96%   |
| HUAWEI               | 3        | 0.96%   |
| Vizio                | 2        | 0.64%   |
| Toshiba              | 2        | 0.64%   |
| Sceptre Tech         | 2        | 0.64%   |
| LG Electronics       | 2        | 0.64%   |
| Insignia             | 2        | 0.64%   |
| HKC                  | 2        | 0.64%   |
| Fujitsu Siemens      | 2        | 0.64%   |
| ___                  | 1        | 0.32%   |
| Xiaomi               | 1        | 0.32%   |
| VIZ                  | 1        | 0.32%   |
| Viotek               | 1        | 0.32%   |
| Vestel               | 1        | 0.32%   |
| Sceptre              | 1        | 0.32%   |
| SAC                  | 1        | 0.32%   |
| RTK                  | 1        | 0.32%   |
| Plain Tree Systems   | 1        | 0.32%   |
| Panasonic            | 1        | 0.32%   |
| Optoma               | 1        | 0.32%   |
| ONN                  | 1        | 0.32%   |
| MiTAC                | 1        | 0.32%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 4        | 1.19%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3        | 0.89%   |
| Goldstar TV SSCR2 GSMC0C8 3840x2160                                    | 3        | 0.89%   |
| AOC 27B1 AOC2701 1920x1080 598x336mm 27.0-inch                         | 3        | 0.89%   |
| ViewSonic VX3258 SERIES VSCDE35 2560x1440 697x392mm 31.5-inch          | 2        | 0.59%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch      | 2        | 0.59%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 2        | 0.59%   |
| MSI G273 MSI3CA7 1920x1080 590x330mm 26.6-inch                         | 2        | 0.59%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                   | 2        | 0.59%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 2        | 0.59%   |
| Gigabyte Technology G27Q GBT2709 2560x1440 598x336mm 27.0-inch         | 2        | 0.59%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                      | 2        | 0.59%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                     | 2        | 0.59%   |
| Dell SE2719HR DELF115 1920x1080 598x336mm 27.0-inch                    | 2        | 0.59%   |
| Dell D3218HN DEL200B 1920x1080 698x393mm 31.5-inch                     | 2        | 0.59%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2        | 0.59%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2        | 0.59%   |
| AOC 2590G4 AOC2590 1920x1080 544x303mm 24.5-inch                       | 2        | 0.59%   |
| AOC 2460G4 AOC0001 1920x1080 530x300mm 24.0-inch                       | 2        | 0.59%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 0.59%   |
| Acer XB271HU ACR0490 2560x1440 600x340mm 27.2-inch                     | 2        | 0.59%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2        | 0.59%   |
| Acer ED322Q ACR0574 1920x1080 521x293mm 23.5-inch                      | 2        | 0.59%   |
| ___ LCDTV16 ___9000 1360x768                                           | 1        | 0.3%    |
| Xiaomi Mi TV XMD009A 2880x1800 600x340mm 27.2-inch                     | 1        | 0.3%    |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1        | 0.3%    |
| Vizio E320-A0 VIZ0095 1366x768 697x392mm 31.5-inch                     | 1        | 0.3%    |
| VIZ LCD Monitor D40f-J09 1920x1080                                     | 1        | 0.3%    |
| Viotek VIOTEKGN27C2 VTK0027 1920x1080 598x336mm 27.0-inch              | 1        | 0.3%    |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1        | 0.3%    |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch          | 1        | 0.3%    |
| ViewSonic VX2270 SERIES VSCE02C 1920x1080 476x267mm 21.5-inch          | 1        | 0.3%    |
| ViewSonic VG2719-2K VSC1935 2560x1440 600x340mm 27.2-inch              | 1        | 0.3%    |
| ViewSonic VA2415 SERIES VSCBC3C 1920x1080 521x293mm 23.5-inch          | 1        | 0.3%    |
| Vestel LCD Monitor 24W_LCD_TV 1920x1080                                | 1        | 0.3%    |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1        | 0.3%    |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1        | 0.3%    |
| Unknown LCD Monitor SAMSUNG                                            | 1        | 0.3%    |
| Unknown LCD Monitor RJT HDMI                                           | 1        | 0.3%    |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 132      | 44.59%  |
| 3840x2160 (4K)     | 38       | 12.84%  |
| 2560x1440 (QHD)    | 27       | 9.12%   |
| 3440x1440          | 14       | 4.73%   |
| 1680x1050 (WSXGA+) | 12       | 4.05%   |
| Unknown            | 10       | 3.38%   |
| 1920x1200 (WUXGA)  | 9        | 3.04%   |
| 1366x768 (WXGA)    | 9        | 3.04%   |
| 2560x1080          | 7        | 2.36%   |
| 1440x900 (WXGA+)   | 7        | 2.36%   |
| 1280x1024 (SXGA)   | 6        | 2.03%   |
| 3840x1080          | 5        | 1.69%   |
| 1600x900 (HD+)     | 4        | 1.35%   |
| 7680x2160          | 2        | 0.68%   |
| 3840x1200          | 2        | 0.68%   |
| 1360x768           | 2        | 0.68%   |
| 9600x2160          | 1        | 0.34%   |
| 4480x1440          | 1        | 0.34%   |
| 3360x1050          | 1        | 0.34%   |
| 2880x1440          | 1        | 0.34%   |
| 2560x1600          | 1        | 0.34%   |
| 2288x1287          | 1        | 0.34%   |
| 2048x1152          | 1        | 0.34%   |
| 1920x540           | 1        | 0.34%   |
| 1400x1050          | 1        | 0.34%   |
| 1280x720 (HD)      | 1        | 0.34%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 55       | 18.33%  |
| 24      | 40       | 13.33%  |
| Unknown | 39       | 13%     |
| 23      | 30       | 10%     |
| 31      | 22       | 7.33%   |
| 21      | 22       | 7.33%   |
| 34      | 15       | 5%      |
| 22      | 13       | 4.33%   |
| 20      | 7        | 2.33%   |
| 19      | 7        | 2.33%   |
| 18      | 6        | 2%      |
| 72      | 5        | 1.67%   |
| 25      | 5        | 1.67%   |
| 26      | 4        | 1.33%   |
| 74      | 2        | 0.67%   |
| 65      | 2        | 0.67%   |
| 49      | 2        | 0.67%   |
| 48      | 2        | 0.67%   |
| 43      | 2        | 0.67%   |
| 40      | 2        | 0.67%   |
| 32      | 2        | 0.67%   |
| 29      | 2        | 0.67%   |
| 28      | 2        | 0.67%   |
| 17      | 2        | 0.67%   |
| 142     | 1        | 0.33%   |
| 84      | 1        | 0.33%   |
| 58      | 1        | 0.33%   |
| 54      | 1        | 0.33%   |
| 50      | 1        | 0.33%   |
| 47      | 1        | 0.33%   |
| 46      | 1        | 0.33%   |
| 35      | 1        | 0.33%   |
| 33      | 1        | 0.33%   |
| 16      | 1        | 0.33%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 114      | 40%     |
| 401-500        | 49       | 17.19%  |
| Unknown        | 39       | 13.68%  |
| 601-700        | 33       | 11.58%  |
| 701-800        | 18       | 6.32%   |
| 1001-1500      | 12       | 4.21%   |
| 1501-2000      | 8        | 2.81%   |
| 351-400        | 5        | 1.75%   |
| 801-900        | 3        | 1.05%   |
| 301-350        | 2        | 0.7%    |
| More than 2000 | 1        | 0.35%   |
| 901-1000       | 1        | 0.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 169      | 64.26%  |
| Unknown | 34       | 12.93%  |
| 16/10   | 31       | 11.79%  |
| 21/9    | 17       | 6.46%   |
| 5/4     | 6        | 2.28%   |
| 32/9    | 3        | 1.14%   |
| 3.20    | 1        | 0.38%   |
| 2.00    | 1        | 0.38%   |
| 1.00    | 1        | 0.38%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 79       | 27.43%  |
| 301-350        | 58       | 20.14%  |
| 351-500        | 43       | 14.93%  |
| Unknown        | 39       | 13.54%  |
| 151-200        | 20       | 6.94%   |
| 251-300        | 18       | 6.25%   |
| More than 1000 | 16       | 5.56%   |
| 501-1000       | 8        | 2.78%   |
| 141-150        | 6        | 2.08%   |
| 121-130        | 1        | 0.35%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 151      | 56.77%  |
| 101-120 | 48       | 18.05%  |
| Unknown | 39       | 14.66%  |
| 121-160 | 14       | 5.26%   |
| 1-50    | 12       | 4.51%   |
| 161-240 | 2        | 0.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 147      | 60.74%  |
| 2     | 70       | 28.93%  |
| 3     | 19       | 7.85%   |
| 0     | 4        | 1.65%   |
| 4     | 2        | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 161      | 44.23%  |
| Intel                           | 117      | 32.14%  |
| MediaTek                        | 19       | 5.22%   |
| Qualcomm Atheros                | 14       | 3.85%   |
| Broadcom                        | 6        | 1.65%   |
| Ralink Technology               | 5        | 1.37%   |
| NetGear                         | 5        | 1.37%   |
| TP-Link                         | 4        | 1.1%    |
| Microsoft                       | 4        | 1.1%    |
| Linksys                         | 4        | 1.1%    |
| Samsung Electronics             | 3        | 0.82%   |
| DisplayLink                     | 3        | 0.82%   |
| Aquantia                        | 3        | 0.82%   |
| Ralink                          | 2        | 0.55%   |
| D-Link                          | 2        | 0.55%   |
| AVM                             | 2        | 0.55%   |
| Xiaomi                          | 1        | 0.27%   |
| Sitecom Europe                  | 1        | 0.27%   |
| Qualcomm Atheros Communications | 1        | 0.27%   |
| Qualcomm                        | 1        | 0.27%   |
| InterBiometrics                 | 1        | 0.27%   |
| Holtek Semiconductor            | 1        | 0.27%   |
| Belkin Components               | 1        | 0.27%   |
| ASIX Electronics                | 1        | 0.27%   |
| Alteon Networks                 | 1        | 0.27%   |
| Accton Technology               | 1        | 0.27%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 116      | 27.42%  |
| Realtek RTL8125 2.5GbE Controller                                              | 32       | 7.57%   |
| Intel I211 Gigabit Network Connection                                          | 26       | 6.15%   |
| Intel Wi-Fi 6 AX200                                                            | 21       | 4.96%   |
| Intel Ethernet Controller I225-V                                               | 20       | 4.73%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                       | 10       | 2.36%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]                      | 9        | 2.13%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                               | 9        | 2.13%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                        | 8        | 1.89%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter                  | 7        | 1.65%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                                        | 7        | 1.65%   |
| Intel Ethernet Connection I217-LM                                              | 7        | 1.65%   |
| Intel Ethernet Connection (2) I219-V                                           | 7        | 1.65%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7        | 1.65%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4        | 0.95%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4        | 0.95%   |
| Microsoft Xbox Wireless Adapter for Windows                                    | 4        | 0.95%   |
| Ralink RT2870/RT3070 Wireless Adapter                                          | 3        | 0.71%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3        | 0.71%   |
| NetGear A6210                                                                  | 3        | 0.71%   |
| Intel Wireless 7265                                                            | 3        | 0.71%   |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 0.71%   |
| Intel Comet Lake PCH CNVi WiFi                                                 | 3        | 0.71%   |
| Intel 82579V Gigabit Network Connection                                        | 3        | 0.71%   |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 0.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                             | 2        | 0.47%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                | 2        | 0.47%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                        | 2        | 0.47%   |
| Realtek Killer E2600 GbE Controller                                            | 2        | 0.47%   |
| Realtek 802.11ac NIC                                                           | 2        | 0.47%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                     | 2        | 0.47%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2        | 0.47%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                  | 2        | 0.47%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U]            | 2        | 0.47%   |
| Intel Tiger Lake PCH CNVi WiFi                                                 | 2        | 0.47%   |
| Intel Ethernet Connection (2) I218-V                                           | 2        | 0.47%   |
| AVM FRITZ!WLAN AC 860                                                          | 2        | 0.47%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 0.47%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.24%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                    | 1        | 0.24%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 63       | 42.57%  |
| Realtek Semiconductor           | 27       | 18.24%  |
| MediaTek                        | 16       | 10.81%  |
| Qualcomm Atheros                | 7        | 4.73%   |
| Ralink Technology               | 5        | 3.38%   |
| NetGear                         | 5        | 3.38%   |
| TP-Link                         | 4        | 2.7%    |
| Microsoft                       | 4        | 2.7%    |
| Linksys                         | 4        | 2.7%    |
| Broadcom                        | 4        | 2.7%    |
| Ralink                          | 2        | 1.35%   |
| D-Link                          | 2        | 1.35%   |
| AVM                             | 2        | 1.35%   |
| Sitecom Europe                  | 1        | 0.68%   |
| Qualcomm Atheros Communications | 1        | 0.68%   |
| Accton Technology               | 1        | 0.68%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 21       | 14.19%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 10       | 6.76%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]           | 9        | 6.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 9        | 6.08%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]             | 8        | 5.41%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 7        | 4.73%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 7        | 4.73%   |
| Microsoft Xbox Wireless Adapter for Windows                         | 4        | 2.7%    |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3        | 2.03%   |
| NetGear A6210                                                       | 3        | 2.03%   |
| Intel Wireless 7265                                                 | 3        | 2.03%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 3        | 2.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 2        | 1.35%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 1.35%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 1.35%   |
| Realtek 802.11ac NIC                                                | 2        | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 2        | 1.35%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 2        | 1.35%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2        | 1.35%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 2        | 1.35%   |
| AVM FRITZ!WLAN AC 860                                               | 2        | 1.35%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1        | 0.68%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.68%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 1        | 0.68%   |
| TP-Link 802.11ac NIC                                                | 1        | 0.68%   |
| Sitecom Europe WLA-5000 802.11abgn [Ralink RT3572]                  | 1        | 0.68%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1        | 0.68%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                 | 1        | 0.68%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 0.68%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 0.68%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                              | 1        | 0.68%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 1        | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1        | 0.68%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 0.68%   |
| Realtek 802.11n WLAN Adapter                                        | 1        | 0.68%   |
| Ralink Wireless Adapter Canyon CN-WF511                             | 1        | 0.68%   |
| Ralink RT2501/RT2573 Wireless Adapter                               | 1        | 0.68%   |
| Ralink MT7601U Wireless Adapter                                     | 1        | 0.68%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter              | 1        | 0.68%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter          | 1        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 155      | 58.94%  |
| Intel                 | 81       | 30.8%   |
| Qualcomm Atheros      | 8        | 3.04%   |
| Samsung Electronics   | 3        | 1.14%   |
| MediaTek              | 3        | 1.14%   |
| DisplayLink           | 3        | 1.14%   |
| Aquantia              | 3        | 1.14%   |
| Broadcom              | 2        | 0.76%   |
| Xiaomi                | 1        | 0.38%   |
| Qualcomm              | 1        | 0.38%   |
| Belkin Components     | 1        | 0.38%   |
| ASIX Electronics      | 1        | 0.38%   |
| Alteon Networks       | 1        | 0.38%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Desktops | Percent |
|--------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller         | 116      | 42.49%  |
| Realtek RTL8125 2.5GbE Controller                                              | 32       | 11.72%  |
| Intel I211 Gigabit Network Connection                                          | 26       | 9.52%   |
| Intel Ethernet Controller I225-V                                               | 20       | 7.33%   |
| Intel Ethernet Connection I217-LM                                              | 7        | 2.56%   |
| Intel Ethernet Connection (2) I219-V                                           | 7        | 2.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 7        | 2.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 4        | 1.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 4        | 1.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3        | 1.1%    |
| Intel Ethernet Connection (7) I219-V                                           | 3        | 1.1%    |
| Intel 82579V Gigabit Network Connection                                        | 3        | 1.1%    |
| Samsung Galaxy series, misc. (tethering mode)                                  | 2        | 0.73%   |
| Realtek Killer E2600 GbE Controller                                            | 2        | 0.73%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 2        | 0.73%   |
| Intel Ethernet Connection (2) I218-V                                           | 2        | 0.73%   |
| Aquantia AQtion AQC107 NBase-T/IEEE 802.3an Ethernet Controller [Atlantic 10G] | 2        | 0.73%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 1        | 0.37%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)                    | 1        | 0.37%   |
| Realtek USB 10/100/1G/2.5G LAN                                                 | 1        | 0.37%   |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 1        | 0.37%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 1        | 0.37%   |
| Realtek Killer E3000 2.5GbE Controller                                         | 1        | 0.37%   |
| Qualcomm VOS_5G                                                                | 1        | 0.37%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller                      | 1        | 0.37%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                                     | 1        | 0.37%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1        | 0.37%   |
| MediaTek moto e22                                                              | 1        | 0.37%   |
| MediaTek FM350-GL                                                              | 1        | 0.37%   |
| MediaTek File-CD Gadget                                                        | 1        | 0.37%   |
| Intel Ethernet Controller I226-V                                               | 1        | 0.37%   |
| Intel Ethernet Controller I225-LM                                              | 1        | 0.37%   |
| Intel Ethernet Connection I217-V                                               | 1        | 0.37%   |
| Intel Ethernet Connection (5) I219-LM                                          | 1        | 0.37%   |
| Intel Ethernet Connection (2) I219-LM                                          | 1        | 0.37%   |
| Intel Ethernet Connection (14) I219-LM                                         | 1        | 0.37%   |
| Intel 82580 Gigabit Network Connection                                         | 1        | 0.37%   |
| Intel 82576 Gigabit Network Connection                                         | 1        | 0.37%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 1        | 0.37%   |
| DisplayLink USB3 to HDMI                                                       | 1        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 233      | 62.8%   |
| WiFi     | 136      | 36.66%  |
| Modem    | 1        | 0.27%   |
| Unknown  | 1        | 0.27%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 181      | 72.69%  |
| WiFi     | 68       | 27.31%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 125      | 52.3%   |
| 2     | 92       | 38.49%  |
| 3     | 17       | 7.11%   |
| 6     | 2        | 0.84%   |
| 0     | 2        | 0.84%   |
| 4     | 1        | 0.42%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 179      | 75.53%  |
| Yes  | 58       | 24.47%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 55       | 44.35%  |
| Cambridge Silicon Radio         | 19       | 15.32%  |
| Realtek Semiconductor           | 15       | 12.1%   |
| MediaTek                        | 11       | 8.87%   |
| ASUSTek Computer                | 8        | 6.45%   |
| Qualcomm Atheros Communications | 5        | 4.03%   |
| IMC Networks                    | 4        | 3.23%   |
| Broadcom                        | 4        | 3.23%   |
| Foxconn / Hon Hai               | 1        | 0.81%   |
| Edimax Technology               | 1        | 0.81%   |
| Dynex                           | 1        | 0.81%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 19       | 15.32%  |
| Intel AX200 Bluetooth                                    | 17       | 13.71%  |
| Realtek Bluetooth Radio                                  | 11       | 8.87%   |
| MediaTek Wireless_Device                                 | 11       | 8.87%   |
| Intel Wireless-AC 3168 Bluetooth                         | 9        | 7.26%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 8        | 6.45%   |
| Intel AX210 Bluetooth                                    | 7        | 5.65%   |
| Intel AX201 Bluetooth                                    | 6        | 4.84%   |
| Realtek  Bluetooth 4.2 Adapter                           | 4        | 3.23%   |
| Qualcomm Atheros  Bluetooth Device                       | 4        | 3.23%   |
| Intel Bluetooth wireless interface                       | 4        | 3.23%   |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 3        | 2.42%   |
| ASUS ASUS USB-BT500                                      | 3        | 2.42%   |
| Intel Bluetooth Device                                   | 2        | 1.61%   |
| IMC Networks Wireless_Device                             | 2        | 1.61%   |
| IMC Networks Bluetooth Radio                             | 2        | 1.61%   |
| ASUS Bluetooth Radio                                     | 2        | 1.61%   |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 0.81%   |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.81%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 0.81%   |
| Foxconn / Hon Hai Wireless_Device                        | 1        | 0.81%   |
| Edimax Bluetooth Adapter                                 | 1        | 0.81%   |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.81%   |
| Broadcom BCM43142A0 Bluetooth Device                     | 1        | 0.81%   |
| ASUS Qualcomm Bluetooth 4.1                              | 1        | 0.81%   |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 0.81%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 1        | 0.81%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 155      | 33.19%  |
| Intel                    | 102      | 21.84%  |
| Nvidia                   | 100      | 21.41%  |
| C-Media Electronics      | 22       | 4.71%   |
| Logitech                 | 12       | 2.57%   |
| Kingston Technology      | 7        | 1.5%    |
| Blue Microphones         | 5        | 1.07%   |
| Texas Instruments        | 4        | 0.86%   |
| Sony                     | 4        | 0.86%   |
| JMTek                    | 4        | 0.86%   |
| Trust                    | 3        | 0.64%   |
| Generalplus Technology   | 3        | 0.64%   |
| Focusrite-Novation       | 3        | 0.64%   |
| Creative Technology      | 3        | 0.64%   |
| Yamaha                   | 2        | 0.43%   |
| RODE Microphones         | 2        | 0.43%   |
| Razer USA                | 2        | 0.43%   |
| Micro Star International | 2        | 0.43%   |
| DSEA A/S                 | 2        | 0.43%   |
| Digidesign               | 2        | 0.43%   |
| Creative Labs            | 2        | 0.43%   |
| ASUSTek Computer         | 2        | 0.43%   |
| XMOS                     | 1        | 0.21%   |
| Tenx Technology          | 1        | 0.21%   |
| SteelSeries ApS          | 1        | 0.21%   |
| Samson Technologies      | 1        | 0.21%   |
| ROCCAT                   | 1        | 0.21%   |
| Realtek Semiconductor    | 1        | 0.21%   |
| Plantronics              | 1        | 0.21%   |
| M-Audio                  | 1        | 0.21%   |
| KORG                     | 1        | 0.21%   |
| Huawei Technologies      | 1        | 0.21%   |
| Hewlett-Packard          | 1        | 0.21%   |
| Harman International     | 1        | 0.21%   |
| FIFINE Microphones       | 1        | 0.21%   |
| EVGA                     | 1        | 0.21%   |
| DigiTech                 | 1        | 0.21%   |
| Corsair                  | 1        | 0.21%   |
| Comtrue                  | 1        | 0.21%   |
| Cambridge Audio          | 1        | 0.21%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 57       | 9.66%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 33       | 5.59%   |
| AMD Family 17h/19h HD Audio Controller                                     | 33       | 5.59%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 23       | 3.9%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 20       | 3.39%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 2.37%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14       | 2.37%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14       | 2.37%   |
| Nvidia GP104 High Definition Audio Controller                              | 12       | 2.03%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 2.03%   |
| Intel 200 Series PCH HD Audio                                              | 12       | 2.03%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 12       | 2.03%   |
| AMD Navi 10 HDMI Audio                                                     | 12       | 2.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11       | 1.86%   |
| Nvidia GA104 High Definition Audio Controller                              | 10       | 1.69%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 9        | 1.53%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 1.53%   |
| Nvidia TU104 HD Audio Controller                                           | 7        | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 1.19%   |
| Nvidia GA102 High Definition Audio Controller                              | 7        | 1.19%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 1.19%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 1.19%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 7        | 1.19%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 7        | 1.19%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 1.02%   |
| C-Media Electronics USB Audio Device                                       | 6        | 1.02%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 1.02%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 0.85%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 0.85%   |
| Nvidia GM206 High Definition Audio Controller                              | 5        | 0.85%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 0.85%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 5        | 0.85%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 0.85%   |
| Blue Microphones Yeti Stereo Microphone                                    | 5        | 0.85%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 5        | 0.85%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 0.85%   |
| Nvidia High Definition Audio Controller                                    | 4        | 0.68%   |
| Nvidia GK106 HDMI Audio Controller                                         | 4        | 0.68%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 4        | 0.68%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| G.Skill                                 | 34       | 22.22%  |
| Corsair                                 | 26       | 16.99%  |
| Kingston                                | 18       | 11.76%  |
| Samsung Electronics                     | 13       | 8.5%    |
| Crucial                                 | 13       | 8.5%    |
| SK hynix                                | 9        | 5.88%   |
| Unknown                                 | 8        | 5.23%   |
| Patriot                                 | 8        | 5.23%   |
| Patriot Memory (PDP Systems)            | 4        | 2.61%   |
| A-DATA Technology                       | 4        | 2.61%   |
| Team                                    | 3        | 1.96%   |
| Micron Technology                       | 3        | 1.96%   |
| Unknown                                 | 3        | 1.96%   |
| ASint Technology                        | 2        | 1.31%   |
| Silicon Power Computer & Communications | 1        | 0.65%   |
| Ramaxel Technology                      | 1        | 0.65%   |
| KLEVV                                   | 1        | 0.65%   |
| Hewlett-Packard                         | 1        | 0.65%   |
| Apacer                                  | 1        | 0.65%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                     | 6        | 3.59%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s                    | 5        | 2.99%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s                      | 3        | 1.8%    |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s                   | 3        | 1.8%    |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s                    | 3        | 1.8%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                    | 3        | 1.8%    |
| Unknown                                                                  | 3        | 1.8%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                                     | 2        | 1.2%    |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                     | 2        | 1.2%    |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                     | 2        | 1.2%    |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                      | 2        | 1.2%    |
| Patriot RAM 2666 C16 Series 8GB DIMM DDR4 2933MT/s                       | 2        | 1.2%    |
| Patriot Memory (PDP Systems) RAM 3600 C18 Series 16GB DIMM DDR4 3600MT/s | 2        | 1.2%    |
| G.Skill RAM F4-3600C19-8GVRB 8192MB DIMM DDR4 3666MT/s                   | 2        | 1.2%    |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s                    | 2        | 1.2%    |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s                       | 2        | 1.2%    |
| Corsair RAM CMK32GX4M4B3200C16 8GB DIMM DDR4 3600MT/s                    | 2        | 1.2%    |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                                | 1        | 0.6%    |
| Unknown RAM Module 8GB DIMM                                              | 1        | 0.6%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                                     | 1        | 0.6%    |
| Unknown RAM Module 4GB DIMM 1066MT/s                                     | 1        | 0.6%    |
| Unknown RAM Module 4GB DIMM                                              | 1        | 0.6%    |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                                | 1        | 0.6%    |
| Unknown RAM Module 1GB DIMM 1066MT/s                                     | 1        | 0.6%    |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s                       | 1        | 0.6%    |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                    | 1        | 0.6%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s                      | 1        | 0.6%    |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3733MT/s                      | 1        | 0.6%    |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s                       | 1        | 0.6%    |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s                     | 1        | 0.6%    |
| SK hynix RAM HMT42GR7MFR4A-PB 16GB DIMM DDR3 1600MT/s                    | 1        | 0.6%    |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s                     | 1        | 0.6%    |
| SK hynix RAM HMT325U7CFR8C-PB 2GB DIMM DDR3 1600MT/s                     | 1        | 0.6%    |
| SK hynix RAM HMAA2GU6CJR8N-XN 16GB DIMM DDR4 3200MT/s                    | 1        | 0.6%    |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s                     | 1        | 0.6%    |
| Silicon Power & RAM Module 16GB DIMM DDR4 3200MT/s                       | 1        | 0.6%    |
| Silicon Power & RAM Module 16GB DIMM DDR4 2667MT/s                       | 1        | 0.6%    |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                                | 1        | 0.6%    |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                                | 1        | 0.6%    |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                               | 1        | 0.6%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 97       | 70.8%   |
| DDR3    | 22       | 16.06%  |
| DDR5    | 11       | 8.03%   |
| Unknown | 5        | 3.65%   |
| DRAM    | 1        | 0.73%   |
| DDR2    | 1        | 0.73%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 129      | 94.16%  |
| SODIMM | 8        | 5.84%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 74       | 48.37%  |
| 16384 | 41       | 26.8%   |
| 4096  | 20       | 13.07%  |
| 32768 | 14       | 9.15%   |
| 2048  | 3        | 1.96%   |
| 1024  | 1        | 0.65%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 3600    | 28       | 18.3%   |
| 3200    | 23       | 15.03%  |
| 1600    | 13       | 8.5%    |
| 2400    | 8        | 5.23%   |
| 3666    | 7        | 4.58%   |
| 2933    | 7        | 4.58%   |
| 4800    | 5        | 3.27%   |
| 3533    | 5        | 3.27%   |
| 2667    | 5        | 3.27%   |
| 1333    | 5        | 3.27%   |
| 3733    | 4        | 2.61%   |
| 2666    | 4        | 2.61%   |
| 1800    | 4        | 2.61%   |
| 3000    | 3        | 1.96%   |
| 2133    | 3        | 1.96%   |
| 5600    | 2        | 1.31%   |
| 3866    | 2        | 1.31%   |
| 3800    | 2        | 1.31%   |
| 3466    | 2        | 1.31%   |
| 6400    | 1        | 0.65%   |
| 6000    | 1        | 0.65%   |
| 5808    | 1        | 0.65%   |
| 5200    | 1        | 0.65%   |
| 4266    | 1        | 0.65%   |
| 4200    | 1        | 0.65%   |
| 4000    | 1        | 0.65%   |
| 3534    | 1        | 0.65%   |
| 3400    | 1        | 0.65%   |
| 3151    | 1        | 0.65%   |
| 2800    | 1        | 0.65%   |
| 2200    | 1        | 0.65%   |
| 2000    | 1        | 0.65%   |
| 1867    | 1        | 0.65%   |
| 1866    | 1        | 0.65%   |
| 1648    | 1        | 0.65%   |
| 1200    | 1        | 0.65%   |
| 1067    | 1        | 0.65%   |
| 1066    | 1        | 0.65%   |
| 800     | 1        | 0.65%   |
| Unknown | 1        | 0.65%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 3        | 30%     |
| Brother Industries  | 3        | 30%     |
| Dymo-CoStar         | 2        | 20%     |
| Samsung Electronics | 1        | 10%     |
| Fuji Xerox          | 1        | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Desktops | Percent |
|----------------------------------|----------|---------|
| Dymo-CoStar LabelWriter 450      | 2        | 20%     |
| Brother HL-5370DW series         | 2        | 20%     |
| Samsung M267x 287x Series        | 1        | 10%     |
| HP OfficeJet Pro 8020 series     | 1        | 10%     |
| HP DeskJet Plus 4100 series      | 1        | 10%     |
| HP Deskjet 2050 J510             | 1        | 10%     |
| Fuji Xerox DocuPrint CM315/318 z | 1        | 10%     |
| Brother MFC Composite Device     | 1        | 10%     |

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


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 23       | 45.1%   |
| Sunplus Innovation Technology | 6        | 11.76%  |
| Microsoft                     | 6        | 11.76%  |
| Jieli Technology              | 3        | 5.88%   |
| Realtek Semiconductor         | 2        | 3.92%   |
| Generalplus Technology        | 2        | 3.92%   |
| Creative Technology           | 2        | 3.92%   |
| Z-Star Microelectronics       | 1        | 1.96%   |
| Trust                         | 1        | 1.96%   |
| Razer USA                     | 1        | 1.96%   |
| Microdia                      | 1        | 1.96%   |
| MacroSilicon                  | 1        | 1.96%   |
| ezcap                         | 1        | 1.96%   |
| Unknown                       | 1        | 1.96%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 5        | 9.8%    |
| Logitech BRIO Ultra HD Webcam              | 4        | 7.84%   |
| Logitech Webcam C930e                      | 3        | 5.88%   |
| Jieli USB PHY 2.0                          | 3        | 5.88%   |
| Sunplus FHD Camera                         | 2        | 3.92%   |
| Realtek Full HD webcam                     | 2        | 3.92%   |
| Microsoft LifeCam HD-5000                  | 2        | 3.92%   |
| Microsoft LifeCam HD-3000                  | 2        | 3.92%   |
| Logitech HD Webcam C910                    | 2        | 3.92%   |
| Logitech HD Pro Webcam C920                | 2        | 3.92%   |
| Logitech C922 Pro Stream Webcam            | 2        | 3.92%   |
| Generalplus GENERAL WEBCAM                 | 2        | 3.92%   |
| Z-Star A4 TECH USB2.0 PC Camera J          | 1        | 1.96%   |
| Trust USB Camera                           | 1        | 1.96%   |
| Sunplus USB Camera                         | 1        | 1.96%   |
| Sunplus USB 2.0 Camera                     | 1        | 1.96%   |
| Sunplus HD 720P webcam                     | 1        | 1.96%   |
| Sunplus Full HD webcam                     | 1        | 1.96%   |
| Razer USA Razer Kiyo Pro                   | 1        | 1.96%   |
| Microsoft Xbox NUI Camera                  | 1        | 1.96%   |
| Microsoft LifeCam VX-2000                  | 1        | 1.96%   |
| Microdia Integrated Camera                 | 1        | 1.96%   |
| MacroSilicon USB3. 0 capture               | 1        | 1.96%   |
| Logitech Webcam C925e                      | 1        | 1.96%   |
| Logitech Webcam C310                       | 1        | 1.96%   |
| Logitech HD Webcam C510                    | 1        | 1.96%   |
| Logitech C920 PRO HD Webcam                | 1        | 1.96%   |
| Logitech Brio 500                          | 1        | 1.96%   |
| ezcap ezcap Live Gamer RAW                 | 1        | 1.96%   |
| Creative Live! Cam Sync 1080p V2           | 1        | 1.96%   |
| Creative Live! Cam Chat HD [VF0700/VF0790] | 1        | 1.96%   |
| Unknown                                    | 1        | 1.96%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor    | Desktops | Percent |
|-----------|----------|---------|
| Synaptics | 1        | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                        | Desktops | Percent |
|----------------------------------------------|----------|---------|
| Synaptics  WBDI Fingerprint Reader - USB 052 | 1        | 100%    |

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
| 0     | 129      | 53.53%  |
| 1     | 99       | 41.08%  |
| 2     | 11       | 4.56%   |
| 3     | 2        | 0.83%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 94       | 74.02%  |
| Net/wireless             | 14       | 11.02%  |
| Graphics card            | 10       | 7.87%   |
| Unassigned class         | 4        | 3.15%   |
| Net/ethernet             | 3        | 2.36%   |
| Multimedia controller    | 1        | 0.79%   |
| Fingerprint reader       | 1        | 0.79%   |

