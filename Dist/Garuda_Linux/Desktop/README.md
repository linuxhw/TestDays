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

Total: 325

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Garuda Linux Soaring | 123      | 56.42%  |
| Garuda Linux         | 54       | 24.77%  |
| Garuda Linux Rolling | 41       | 18.81%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Desktops | Percent |
|--------------|----------|---------|
| Garuda Linux | 213      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Desktops | Percent |
|--------------------|----------|---------|
| 5.17.1-zen1-1-zen  | 6        | 2.36%   |
| 6.4.10-zen2-1-zen  | 4        | 1.57%   |
| 6.2.10-zen1-1-zen  | 4        | 1.57%   |
| 6.1.12-zen1-1-zen  | 4        | 1.57%   |
| 6.1.1-zen1-1-zen   | 4        | 1.57%   |
| 5.15.7-zen1-1-zen  | 4        | 1.57%   |
| 5.10.4-107-tkg-bmq | 4        | 1.57%   |
| 6.5.9-zen2-1-zen   | 3        | 1.18%   |
| 6.5.5-zen1-1-zen   | 3        | 1.18%   |
| 6.5.4-zen2-1-zen   | 3        | 1.18%   |
| 6.5.2-zen1-1-zen   | 3        | 1.18%   |
| 6.4.6-zen1-1-zen   | 3        | 1.18%   |
| 6.4.12-zen1-1-zen  | 3        | 1.18%   |
| 6.3.2-zen1-1-zen   | 3        | 1.18%   |
| 6.1.8-zen1-1-zen   | 3        | 1.18%   |
| 6.0.2-zen1-1-zen   | 3        | 1.18%   |
| 6.0.12-zen1-1-zen  | 3        | 1.18%   |
| 6.0.11-zen1-1-zen  | 3        | 1.18%   |
| 5.9.1-zen2-1-zen   | 3        | 1.18%   |
| 5.18.12-zen1-1-zen | 3        | 1.18%   |
| 5.18.1-zen1-1-zen  | 3        | 1.18%   |
| 5.16.4-zen1-1-zen  | 3        | 1.18%   |
| 5.15.2-zen1-1-zen  | 3        | 1.18%   |
| 5.15.13-zen1-1-zen | 3        | 1.18%   |
| 5.11.16-zen1-1-zen | 3        | 1.18%   |
| 6.5.7-zen2-1-zen   | 2        | 0.79%   |
| 6.4.9-zen1-1-zen   | 2        | 0.79%   |
| 6.4.3-zen1-1-zen   | 2        | 0.79%   |
| 6.3.6-zen1-1-zen   | 2        | 0.79%   |
| 6.2.7-zen1-1-zen   | 2        | 0.79%   |
| 6.2.2-zen2-1-zen   | 2        | 0.79%   |
| 6.2.13-zen-1-zen   | 2        | 0.79%   |
| 6.2.12-zen1-1-zen  | 2        | 0.79%   |
| 6.2.11-zen1-1-zen  | 2        | 0.79%   |
| 6.1.4-zen2-1-zen   | 2        | 0.79%   |
| 6.1.3-zen1-1-zen   | 2        | 0.79%   |
| 6.0.8-zen1-1-zen   | 2        | 0.79%   |
| 5.9.11-zen2-1-zen  | 2        | 0.79%   |
| 5.9.10-zen1-1-zen  | 2        | 0.79%   |
| 5.8.14-zen1-1-zen  | 2        | 0.79%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.17.1  | 7        | 2.76%   |
| 6.5.5   | 5        | 1.97%   |
| 6.4.10  | 5        | 1.97%   |
| 6.2.10  | 4        | 1.57%   |
| 6.1.12  | 4        | 1.57%   |
| 6.1.1   | 4        | 1.57%   |
| 5.15.7  | 4        | 1.57%   |
| 5.10.4  | 4        | 1.57%   |
| 6.5.9   | 3        | 1.18%   |
| 6.5.4   | 3        | 1.18%   |
| 6.5.2   | 3        | 1.18%   |
| 6.4.6   | 3        | 1.18%   |
| 6.4.3   | 3        | 1.18%   |
| 6.4.12  | 3        | 1.18%   |
| 6.3.2   | 3        | 1.18%   |
| 6.2.2   | 3        | 1.18%   |
| 6.1.8   | 3        | 1.18%   |
| 6.1.4   | 3        | 1.18%   |
| 6.0.2   | 3        | 1.18%   |
| 6.0.12  | 3        | 1.18%   |
| 6.0.11  | 3        | 1.18%   |
| 5.9.1   | 3        | 1.18%   |
| 5.18.12 | 3        | 1.18%   |
| 5.18.1  | 3        | 1.18%   |
| 5.17.5  | 3        | 1.18%   |
| 5.16.4  | 3        | 1.18%   |
| 5.15.2  | 3        | 1.18%   |
| 5.15.13 | 3        | 1.18%   |
| 5.12.13 | 3        | 1.18%   |
| 5.11.16 | 3        | 1.18%   |
| 6.5.7   | 2        | 0.79%   |
| 6.4.9   | 2        | 0.79%   |
| 6.4.2   | 2        | 0.79%   |
| 6.3.6   | 2        | 0.79%   |
| 6.2.7   | 2        | 0.79%   |
| 6.2.13  | 2        | 0.79%   |
| 6.2.12  | 2        | 0.79%   |
| 6.2.11  | 2        | 0.79%   |
| 6.1.3   | 2        | 0.79%   |
| 6.0.8   | 2        | 0.79%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 6.1     | 29       | 11.98%  |
| 6.4     | 24       | 9.92%   |
| 5.15    | 20       | 8.26%   |
| 6.5     | 17       | 7.02%   |
| 5.16    | 16       | 6.61%   |
| 5.10    | 16       | 6.61%   |
| 6.2     | 15       | 6.2%    |
| 6.0     | 15       | 6.2%    |
| 5.18    | 14       | 5.79%   |
| 5.17    | 11       | 4.55%   |
| 5.12    | 10       | 4.13%   |
| 5.11    | 10       | 4.13%   |
| 6.3     | 9        | 3.72%   |
| 5.9     | 9        | 3.72%   |
| 5.19    | 8        | 3.31%   |
| 5.13    | 7        | 2.89%   |
| 5.14    | 6        | 2.48%   |
| 5.8     | 5        | 2.07%   |
| 6.6     | 1        | 0.41%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 213      | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Desktops | Percent |
|------------|----------|---------|
| KDE5       | 149      | 68.04%  |
| GNOME      | 24       | 10.96%  |
| KDE        | 19       | 8.68%   |
| XFCE       | 11       | 5.02%   |
| X-Cinnamon | 4        | 1.83%   |
| LXQt       | 3        | 1.37%   |
| sway       | 2        | 0.91%   |
| Unknown    | 2        | 0.91%   |
| MATE       | 1        | 0.46%   |
| i3         | 1        | 0.46%   |
| Hyprland   | 1        | 0.46%   |
| Deepin     | 1        | 0.46%   |
| Cinnamon   | 1        | 0.46%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 186      | 85.71%  |
| Wayland | 22       | 10.14%  |
| Tty     | 6        | 2.76%   |
| Unknown | 3        | 1.38%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| SDDM    | 92       | 42.59%  |
| Unknown | 89       | 41.2%   |
| LightDM | 21       | 9.72%   |
| GDM     | 11       | 5.09%   |
| GREETD  | 3        | 1.39%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Desktops | Percent |
|-------|----------|---------|
| en_US | 106      | 49.53%  |
| en_GB | 20       | 9.35%   |
| de_DE | 19       | 8.88%   |
| en_CA | 10       | 4.67%   |
| it_IT | 7        | 3.27%   |
| es_ES | 7        | 3.27%   |
| pt_BR | 4        | 1.87%   |
| en_AU | 4        | 1.87%   |
| ru_RU | 3        | 1.4%    |
| nl_NL | 3        | 1.4%    |
| sk_SK | 2        | 0.93%   |
| pl_PL | 2        | 0.93%   |
| fr_FR | 2        | 0.93%   |
| fr_BE | 2        | 0.93%   |
| en_IN | 2        | 0.93%   |
| da_DK | 2        | 0.93%   |
| sv_SE | 1        | 0.47%   |
| nl_BE | 1        | 0.47%   |
| nb_NO | 1        | 0.47%   |
| ja_JP | 1        | 0.47%   |
| iu_CA | 1        | 0.47%   |
| hu_HU | 1        | 0.47%   |
| es_VE | 1        | 0.47%   |
| es_MX | 1        | 0.47%   |
| es_CL | 1        | 0.47%   |
| es_AR | 1        | 0.47%   |
| en_ZA | 1        | 0.47%   |
| en_SG | 1        | 0.47%   |
| en_IE | 1        | 0.47%   |
| en_DK | 1        | 0.47%   |
| en_DE | 1        | 0.47%   |
| el_GR | 1        | 0.47%   |
| de_CH | 1        | 0.47%   |
| de_AT | 1        | 0.47%   |
| cs_CZ | 1        | 0.47%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| EFI  | 123      | 57.48%  |
| BIOS | 91       | 42.52%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Btrfs   | 207      | 97.18%  |
| Tmpfs   | 2        | 0.94%   |
| Overlay | 2        | 0.94%   |
| Ext4    | 2        | 0.94%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| GPT     | 121      | 56.28%  |
| Unknown | 88       | 40.93%  |
| MBR     | 6        | 2.79%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 172      | 79.26%  |
| Yes       | 45       | 20.74%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 144      | 66.06%  |
| Yes       | 74       | 33.94%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Desktops | Percent |
|--------------------------------------|----------|---------|
| ASUSTek Computer                     | 64       | 30.05%  |
| MSI                                  | 35       | 16.43%  |
| Gigabyte Technology                  | 35       | 16.43%  |
| ASRock                               | 23       | 10.8%   |
| Hewlett-Packard                      | 14       | 6.57%   |
| Dell                                 | 11       | 5.16%   |
| Lenovo                               | 8        | 3.76%   |
| Intel                                | 5        | 2.35%   |
| Acer                                 | 3        | 1.41%   |
| Shenzhen Meigao Electronic Equipment | 2        | 0.94%   |
| Pegatron                             | 2        | 0.94%   |
| Biostar                              | 2        | 0.94%   |
| Alienware                            | 2        | 0.94%   |
| Win element                          | 1        | 0.47%   |
| T-bao                                | 1        | 0.47%   |
| OEM                                  | 1        | 0.47%   |
| Medion                               | 1        | 0.47%   |
| Fujitsu                              | 1        | 0.47%   |
| BESSTAR Tech                         | 1        | 0.47%   |
| Unknown                              | 1        | 0.47%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS TUF Gaming X570-PLUS                  | 7        | 3.29%   |
| MSI MS-7C91                                | 3        | 1.41%   |
| MSI MS-7B86                                | 3        | 1.41%   |
| ASUS All Series                            | 3        | 1.41%   |
| MSI MS-7D75                                | 2        | 0.94%   |
| MSI MS-7C37                                | 2        | 0.94%   |
| MSI MS-7C02                                | 2        | 0.94%   |
| HP ProDesk 600 G1 SFF                      | 2        | 0.94%   |
| HP Pavilion Gaming Desktop 690-00xx        | 2        | 0.94%   |
| HP EliteDesk 800 G1 SFF                    | 2        | 0.94%   |
| Gigabyte X570 AORUS PRO WIFI               | 2        | 0.94%   |
| Gigabyte B550 AORUS PRO AC                 | 2        | 0.94%   |
| Gigabyte AB350-Gaming 3                    | 2        | 0.94%   |
| Dell OptiPlex 7010                         | 2        | 0.94%   |
| Dell Inspiron 3668                         | 2        | 0.94%   |
| ASUS TUF Gaming B550-PLUS WIFI II          | 2        | 0.94%   |
| ASUS ROG STRIX X570-E GAMING               | 2        | 0.94%   |
| ASUS ROG STRIX B550-F GAMING               | 2        | 0.94%   |
| ASUS PRIME X570-P                          | 2        | 0.94%   |
| ASRock B450M-HDV R4.0                      | 2        | 0.94%   |
| Unknown                                    | 2        | 0.94%   |
| Win element M600                           | 1        | 0.47%   |
| T-bao MINI PC                              | 1        | 0.47%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.47%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.47%   |
| Pegatron p7-1030                           | 1        | 0.47%   |
| Pegatron h9-1301es                         | 1        | 0.47%   |
| MSI MS-7E10                                | 1        | 0.47%   |
| MSI MS-7D96                                | 1        | 0.47%   |
| MSI MS-7D25                                | 1        | 0.47%   |
| MSI MS-7D16                                | 1        | 0.47%   |
| MSI MS-7C90                                | 1        | 0.47%   |
| MSI MS-7C83                                | 1        | 0.47%   |
| MSI MS-7C56                                | 1        | 0.47%   |
| MSI MS-7C52                                | 1        | 0.47%   |
| MSI MS-7C09                                | 1        | 0.47%   |
| MSI MS-7B98                                | 1        | 0.47%   |
| MSI MS-7B93                                | 1        | 0.47%   |
| MSI MS-7B89                                | 1        | 0.47%   |
| MSI MS-7B09                                | 1        | 0.47%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                                       | Desktops | Percent |
|--------------------------------------------|----------|---------|
| ASUS PRIME                                 | 16       | 7.51%   |
| ASUS ROG                                   | 15       | 7.04%   |
| ASUS TUF                                   | 14       | 6.57%   |
| Lenovo ThinkCentre                         | 5        | 2.35%   |
| Gigabyte X570                              | 5        | 2.35%   |
| Dell OptiPlex                              | 5        | 2.35%   |
| Dell Inspiron                              | 5        | 2.35%   |
| HP Pavilion                                | 4        | 1.88%   |
| HP EliteDesk                               | 4        | 1.88%   |
| Gigabyte B550                              | 4        | 1.88%   |
| MSI MS-7C91                                | 3        | 1.41%   |
| MSI MS-7B86                                | 3        | 1.41%   |
| Gigabyte B450                              | 3        | 1.41%   |
| ASUS All                                   | 3        | 1.41%   |
| MSI MS-7D75                                | 2        | 0.94%   |
| MSI MS-7C37                                | 2        | 0.94%   |
| MSI MS-7C02                                | 2        | 0.94%   |
| HP ProDesk                                 | 2        | 0.94%   |
| Gigabyte AB350-Gaming                      | 2        | 0.94%   |
| ASUS Rampage                               | 2        | 0.94%   |
| ASUS Maximus                               | 2        | 0.94%   |
| ASRock X470                                | 2        | 0.94%   |
| ASRock B450M-HDV                           | 2        | 0.94%   |
| Alienware Aurora                           | 2        | 0.94%   |
| Acer Aspire                                | 2        | 0.94%   |
| Unknown                                    | 2        | 0.94%   |
| Win element M600                           | 1        | 0.47%   |
| T-bao MINI                                 | 1        | 0.47%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1        | 0.47%   |
| Shenzhen Meigao Electronic Equipment HX90G | 1        | 0.47%   |
| Pegatron p7-1030                           | 1        | 0.47%   |
| Pegatron h9-1301es                         | 1        | 0.47%   |
| MSI MS-7E10                                | 1        | 0.47%   |
| MSI MS-7D96                                | 1        | 0.47%   |
| MSI MS-7D25                                | 1        | 0.47%   |
| MSI MS-7D16                                | 1        | 0.47%   |
| MSI MS-7C90                                | 1        | 0.47%   |
| MSI MS-7C83                                | 1        | 0.47%   |
| MSI MS-7C56                                | 1        | 0.47%   |
| MSI MS-7C52                                | 1        | 0.47%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2019 | 34       | 15.96%  |
| 2018 | 29       | 13.62%  |
| 2020 | 26       | 12.21%  |
| 2021 | 19       | 8.92%   |
| 2017 | 17       | 7.98%   |
| 2013 | 17       | 7.98%   |
| 2022 | 16       | 7.51%   |
| 2014 | 14       | 6.57%   |
| 2012 | 13       | 6.1%    |
| 2016 | 7        | 3.29%   |
| 2011 | 7        | 3.29%   |
| 2015 | 5        | 2.35%   |
| 2010 | 4        | 1.88%   |
| 2009 | 3        | 1.41%   |
| 2023 | 1        | 0.47%   |
| 2008 | 1        | 0.47%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 213      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 213      | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 213      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 32.01-64.0  | 72       | 33.33%  |
| 16.01-24.0  | 60       | 27.78%  |
| 8.01-16.0   | 30       | 13.89%  |
| 4.01-8.0    | 18       | 8.33%   |
| 64.01-256.0 | 17       | 7.87%   |
| 24.01-32.0  | 14       | 6.48%   |
| 3.01-4.0    | 5        | 2.31%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB     | Desktops | Percent |
|-------------|----------|---------|
| 4.01-8.0    | 94       | 40.69%  |
| 3.01-4.0    | 46       | 19.91%  |
| 2.01-3.0    | 34       | 14.72%  |
| 8.01-16.0   | 34       | 14.72%  |
| 1.01-2.0    | 12       | 5.19%   |
| 16.01-24.0  | 9        | 3.9%    |
| 32.01-64.0  | 1        | 0.43%   |
| 64.01-256.0 | 1        | 0.43%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 2      | 61       | 27.73%  |
| 3      | 55       | 25%     |
| 1      | 37       | 16.82%  |
| 4      | 31       | 14.09%  |
| 5      | 19       | 8.64%   |
| 6      | 8        | 3.64%   |
| 9      | 4        | 1.82%   |
| 7      | 2        | 0.91%   |
| 18     | 1        | 0.45%   |
| 14     | 1        | 0.45%   |
| 11     | 1        | 0.45%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 154      | 71.96%  |
| Yes       | 60       | 28.04%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 210      | 98.59%  |
| No        | 3        | 1.41%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 123      | 56.16%  |
| No        | 96       | 43.84%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 109      | 50.23%  |
| No        | 108      | 49.77%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Desktops | Percent |
|--------------|----------|---------|
| USA          | 60       | 28.17%  |
| Germany      | 28       | 13.15%  |
| Italy        | 13       | 6.1%    |
| Canada       | 11       | 5.16%   |
| UK           | 9        | 4.23%   |
| Spain        | 7        | 3.29%   |
| Brazil       | 7        | 3.29%   |
| Sweden       | 6        | 2.82%   |
| Netherlands  | 5        | 2.35%   |
| Russia       | 4        | 1.88%   |
| Poland       | 4        | 1.88%   |
| Belgium      | 4        | 1.88%   |
| Australia    | 4        | 1.88%   |
| Romania      | 3        | 1.41%   |
| Norway       | 3        | 1.41%   |
| India        | 3        | 1.41%   |
| France       | 3        | 1.41%   |
| Denmark      | 3        | 1.41%   |
| Austria      | 3        | 1.41%   |
| Slovakia     | 2        | 0.94%   |
| Puerto Rico  | 2        | 0.94%   |
| Philippines  | 2        | 0.94%   |
| Latvia       | 2        | 0.94%   |
| Japan        | 2        | 0.94%   |
| Greece       | 2        | 0.94%   |
| Chile        | 2        | 0.94%   |
| Venezuela    | 1        | 0.47%   |
| Ukraine      | 1        | 0.47%   |
| Turkey       | 1        | 0.47%   |
| Taiwan       | 1        | 0.47%   |
| Switzerland  | 1        | 0.47%   |
| South Africa | 1        | 0.47%   |
| Singapore    | 1        | 0.47%   |
| Serbia       | 1        | 0.47%   |
| Portugal     | 1        | 0.47%   |
| Mexico       | 1        | 0.47%   |
| Lithuania    | 1        | 0.47%   |
| Israel       | 1        | 0.47%   |
| Ireland      | 1        | 0.47%   |
| Iceland      | 1        | 0.47%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                    | Desktops | Percent |
|-------------------------|----------|---------|
| Milan                   | 3        | 1.36%   |
| Dallas                  | 3        | 1.36%   |
| Berlin                  | 3        | 1.36%   |
| Wasmes                  | 2        | 0.91%   |
| Sydney                  | 2        | 0.91%   |
| Stockholm               | 2        | 0.91%   |
| St Louis                | 2        | 0.91%   |
| Sao Paulo               | 2        | 0.91%   |
| Santa Cruz de Tenerife  | 2        | 0.91%   |
| Saint Joseph            | 2        | 0.91%   |
| Riga                    | 2        | 0.91%   |
| Oklahoma City           | 2        | 0.91%   |
| Melbourne               | 2        | 0.91%   |
| Mannheim                | 2        | 0.91%   |
| Kingsport               | 2        | 0.91%   |
| Gaildorf                | 2        | 0.91%   |
| Fort St. John           | 2        | 0.91%   |
| Colfax                  | 2        | 0.91%   |
| Charlotte               | 2        | 0.91%   |
| Algeciras               | 2        | 0.91%   |
| Złotoryja              | 1        | 0.45%   |
| Zwickau                 | 1        | 0.45%   |
| York                    | 1        | 0.45%   |
| Wuppertal               | 1        | 0.45%   |
| Wil                     | 1        | 0.45%   |
| Wichita                 | 1        | 0.45%   |
| Weiterstadt             | 1        | 0.45%   |
| Weilen unter den Rinnen | 1        | 0.45%   |
| Waxahachie              | 1        | 0.45%   |
| Warsaw                  | 1        | 0.45%   |
| Voronezh                | 1        | 0.45%   |
| Volzhskiy               | 1        | 0.45%   |
| Vilnius                 | 1        | 0.45%   |
| Victoria                | 1        | 0.45%   |
| Västerås              | 1        | 0.45%   |
| Valence                 | 1        | 0.45%   |
| Urbandale               | 1        | 0.45%   |
| Ullerslev               | 1        | 0.45%   |
| Udine                   | 1        | 0.45%   |
| Trecastelli             | 1        | 0.45%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 90       | 150    | 17.01%  |
| Samsung Electronics         | 86       | 181    | 16.26%  |
| Seagate                     | 82       | 133    | 15.5%   |
| Toshiba                     | 36       | 51     | 6.81%   |
| Kingston                    | 32       | 47     | 6.05%   |
| SanDisk                     | 30       | 40     | 5.67%   |
| Crucial                     | 26       | 33     | 4.91%   |
| Hitachi                     | 12       | 13     | 2.27%   |
| Micron/Crucial Technology   | 10       | 14     | 1.89%   |
| Silicon Motion              | 9        | 9      | 1.7%    |
| Phison                      | 7        | 8      | 1.32%   |
| Intel                       | 7        | 10     | 1.32%   |
| A-DATA Technology           | 6        | 9      | 1.13%   |
| PNY                         | 5        | 5      | 0.95%   |
| China                       | 5        | 8      | 0.95%   |
| Unknown                     | 4        | 4      | 0.76%   |
| SPCC                        | 4        | 5      | 0.76%   |
| Phison Electronics          | 4        | 6      | 0.76%   |
| OCZ                         | 4        | 4      | 0.76%   |
| HGST                        | 4        | 10     | 0.76%   |
| ADATA Technology            | 4        | 5      | 0.76%   |
| XPG                         | 3        | 4      | 0.57%   |
| Team                        | 3        | 4      | 0.57%   |
| SK hynix                    | 3        | 5      | 0.57%   |
| Realtek Semiconductor       | 3        | 5      | 0.57%   |
| Kingston Technology Company | 3        | 3      | 0.57%   |
| Intenso                     | 3        | 4      | 0.57%   |
| Emtec                       | 3        | 5      | 0.57%   |
| Transcend                   | 2        | 2      | 0.38%   |
| TO Exter                    | 2        | 2      | 0.38%   |
| Patriot                     | 2        | 3      | 0.38%   |
| Micron Technology           | 2        | 2      | 0.38%   |
| MAXIO Technology (Hangzhou) | 2        | 2      | 0.38%   |
| LITEONIT                    | 2        | 2      | 0.38%   |
| Hewlett-Packard             | 2        | 2      | 0.38%   |
| WD MediaMax                 | 1        | 1      | 0.19%   |
| USB30                       | 1        | 2      | 0.19%   |
| T-FORCE                     | 1        | 1      | 0.19%   |
| SSK                         | 1        | 1      | 0.19%   |
| SABRENT                     | 1        | 2      | 0.19%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB                 | 14       | 2.21%   |
| Samsung SSD 850 EVO 250GB                                         | 9        | 1.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB                | 9        | 1.42%   |
| Seagate ST2000DM008-2FR102 2TB                                    | 8        | 1.26%   |
| Samsung SSD 860 EVO 500GB                                         | 8        | 1.26%   |
| Crucial CT1000MX500SSD1 1TB                                       | 8        | 1.26%   |
| Seagate ST1000DM010-2EP102 1TB                                    | 6        | 0.95%   |
| Samsung NVMe SSD Drive 1TB                                        | 6        | 0.95%   |
| Toshiba HDWD110 1TB                                               | 5        | 0.79%   |
| Toshiba DT01ACA100 1TB                                            | 5        | 0.79%   |
| Samsung SSD 980 1TB                                               | 5        | 0.79%   |
| Samsung SSD 970 EVO Plus 500GB                                    | 5        | 0.79%   |
| Samsung SSD 850 EVO 500GB                                         | 5        | 0.79%   |
| WDC WD10EZEX-60WN4A0 1TB                                          | 4        | 0.63%   |
| WDC WD10EZEX-08WN4A0 1TB                                          | 4        | 0.63%   |
| Toshiba DT01ACA050 500GB                                          | 4        | 0.63%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 256GB             | 4        | 0.63%   |
| Seagate ST4000DM004-2CV104 4TB                                    | 4        | 0.63%   |
| Sandisk WD Blue SN550 NVMe SSD 1TB                                | 4        | 0.63%   |
| SanDisk SSD PLUS 1000GB                                           | 4        | 0.63%   |
| Samsung SSD 860 QVO 1TB                                           | 4        | 0.63%   |
| Samsung SSD 860 EVO 250GB                                         | 4        | 0.63%   |
| Samsung SSD 860 EVO 1TB                                           | 4        | 0.63%   |
| Samsung NVMe SSD Drive 500GB                                      | 4        | 0.63%   |
| Micron/Crucial P2 NVMe PCIe SSD 500GB                             | 4        | 0.63%   |
| Micron/Crucial P1 NVMe PCIe SSD 1TB                               | 4        | 0.63%   |
| Kingston SA400S37480G 480GB SSD                                   | 4        | 0.63%   |
| Kingston SA400S37240G 240GB SSD                                   | 4        | 0.63%   |
| Kingston SA400S37120G 120GB SSD                                   | 4        | 0.63%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive 512GB | 4        | 0.63%   |
| WDC WD60EZAZ-00SF3B0 6TB                                          | 3        | 0.47%   |
| WDC WD40EFZX-68AWUN0 4TB                                          | 3        | 0.47%   |
| WDC WD20EZRZ-00Z5HB0 2TB                                          | 3        | 0.47%   |
| WDC WD20EARX-00PASB0 2TB                                          | 3        | 0.47%   |
| WDC WD10EALX-009BA0 1TB                                           | 3        | 0.47%   |
| Toshiba DT01ACA300 3TB                                            | 3        | 0.47%   |
| Toshiba DT01ACA200 2TB                                            | 3        | 0.47%   |
| Seagate ST3320820AS 320GB                                         | 3        | 0.47%   |
| Seagate ST3000DM001-1ER166 3TB                                    | 3        | 0.47%   |
| Seagate ST2000DM006-2DM164 2TB                                    | 3        | 0.47%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Seagate             | 79       | 126    | 36.24%  |
| WDC                 | 78       | 135    | 35.78%  |
| Toshiba             | 31       | 41     | 14.22%  |
| Hitachi             | 12       | 13     | 5.5%    |
| Samsung Electronics | 5        | 5      | 2.29%   |
| HGST                | 4        | 10     | 1.83%   |
| Intenso             | 3        | 4      | 1.38%   |
| Unknown             | 2        | 2      | 0.92%   |
| SSK                 | 1        | 1      | 0.46%   |
| LaCie               | 1        | 1      | 0.46%   |
| Hewlett-Packard     | 1        | 1      | 0.46%   |
| ASMedia             | 1        | 2      | 0.46%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 42       | 72     | 24.71%  |
| Kingston            | 23       | 31     | 13.53%  |
| Crucial             | 22       | 27     | 12.94%  |
| SanDisk             | 14       | 20     | 8.24%   |
| WDC                 | 9        | 9      | 5.29%   |
| A-DATA Technology   | 6        | 9      | 3.53%   |
| Toshiba             | 5        | 9      | 2.94%   |
| China               | 5        | 8      | 2.94%   |
| SPCC                | 4        | 5      | 2.35%   |
| PNY                 | 4        | 4      | 2.35%   |
| OCZ                 | 4        | 4      | 2.35%   |
| Team                | 3        | 4      | 1.76%   |
| Emtec               | 3        | 5      | 1.76%   |
| Transcend           | 2        | 2      | 1.18%   |
| TO Exter            | 2        | 2      | 1.18%   |
| SK hynix            | 2        | 4      | 1.18%   |
| LITEONIT            | 2        | 2      | 1.18%   |
| USB30               | 1        | 2      | 0.59%   |
| Unknown             | 1        | 1      | 0.59%   |
| T-FORCE             | 1        | 1      | 0.59%   |
| SABRENT             | 1        | 2      | 0.59%   |
| Qumo                | 1        | 1      | 0.59%   |
| Plextor             | 1        | 1      | 0.59%   |
| Patriot             | 1        | 2      | 0.59%   |
| Neo                 | 1        | 1      | 0.59%   |
| Mushkin             | 1        | 1      | 0.59%   |
| Micron Technology   | 1        | 1      | 0.59%   |
| LITEON              | 1        | 1      | 0.59%   |
| Lexar               | 1        | 1      | 0.59%   |
| Inateck             | 1        | 1      | 0.59%   |
| HS-SSD-C100         | 1        | 1      | 0.59%   |
| GOODRAM             | 1        | 1      | 0.59%   |
| Fanxiang            | 1        | 1      | 0.59%   |
| DEXP                | 1        | 1      | 0.59%   |
| ADATA SU            | 1        | 1      | 0.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 157      | 341    | 37.65%  |
| SSD     | 126      | 238    | 30.22%  |
| NVMe    | 121      | 232    | 29.02%  |
| Unknown | 13       | 13     | 3.12%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 188      | 544    | 55.46%  |
| NVMe | 121      | 232    | 35.69%  |
| SAS  | 30       | 48     | 8.85%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 123      | 236    | 36.39%  |
| 0.51-1.0   | 105      | 160    | 31.07%  |
| 1.01-2.0   | 61       | 101    | 18.05%  |
| 2.01-3.0   | 17       | 28     | 5.03%   |
| 3.01-4.0   | 16       | 29     | 4.73%   |
| 4.01-10.0  | 14       | 22     | 4.14%   |
| 10.01-20.0 | 2        | 3      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 120      | 55.81%  |
| 1001-2000      | 34       | 15.81%  |
| 2001-3000      | 26       | 12.09%  |
| 501-1000       | 15       | 6.98%   |
| 251-500        | 10       | 4.65%   |
| Unknown        | 6        | 2.79%   |
| 101-250        | 2        | 0.93%   |
| 1-20           | 2        | 0.93%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| More than 3000 | 41       | 18.14%  |
| 501-1000       | 34       | 15.04%  |
| 251-500        | 33       | 14.6%   |
| 101-250        | 33       | 14.6%   |
| 1001-2000      | 32       | 14.16%  |
| 2001-3000      | 25       | 11.06%  |
| 51-100         | 15       | 6.64%   |
| Unknown        | 6        | 2.65%   |
| 21-50          | 4        | 1.77%   |
| 1-20           | 3        | 1.33%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                   | Desktops | Drives | Percent |
|---------------------------------------------------------|----------|--------|---------|
| WDC WD20EARS-00MVWB0 2TB                                | 2        | 2      | 4.55%   |
| Toshiba DT01ACA050 500GB                                | 2        | 2      | 4.55%   |
| Intenso USB 3.0 device 5TB                              | 2        | 2      | 4.55%   |
| WDC WD6400AAKS-65A7B0 640GB                             | 1        | 1      | 2.27%   |
| WDC WD5000AAKX-60U6AA0 500GB                            | 1        | 1      | 2.27%   |
| WDC WD5000AAKX-003CA0 500GB                             | 1        | 2      | 2.27%   |
| WDC WD5000AAKS-00E4A0 500GB                             | 1        | 1      | 2.27%   |
| WDC WD30EZRX-00DC0B0 3TB                                | 1        | 1      | 2.27%   |
| WDC WD30EFRX-68EUZN0 3TB                                | 1        | 2      | 2.27%   |
| WDC WD20EARX-00PASB0 2TB                                | 1        | 1      | 2.27%   |
| WDC WD2002FAEX-007BA0 2TB                               | 1        | 1      | 2.27%   |
| WDC WD15EADS-22P8B0 1TB                                 | 1        | 2      | 2.27%   |
| WDC WD10EZRX-00L4HB0 1TB                                | 1        | 1      | 2.27%   |
| WDC WD10EZEX-60ZF5A0 1TB                                | 1        | 1      | 2.27%   |
| WDC WD10EARS-00Y5B1 1TB                                 | 1        | 1      | 2.27%   |
| WDC WD10EALX-009BA0 1TB                                 | 1        | 1      | 2.27%   |
| WDC WD10EADS-22M2B0 1TB                                 | 1        | 1      | 2.27%   |
| WDC WD10EADS-00M2B0 1TB                                 | 1        | 1      | 2.27%   |
| Toshiba DT01ACA100 1TB                                  | 1        | 1      | 2.27%   |
| Seagate ST9250827AS 250GB                               | 1        | 1      | 2.27%   |
| Seagate ST4000DM004-2CV104 4TB                          | 1        | 1      | 2.27%   |
| Seagate ST3000DM003-1F216N 3TB                          | 1        | 1      | 2.27%   |
| Seagate ST2000LM003 HN-M201RAD 2TB                      | 1        | 1      | 2.27%   |
| Seagate ST2000DX002-2DV164 2TB                          | 1        | 2      | 2.27%   |
| Seagate ST2000DL003-9VT166 2TB                          | 1        | 1      | 2.27%   |
| SanDisk SD6SF1M128G1022I 128GB SSD                      | 1        | 1      | 2.27%   |
| Samsung Electronics SSD 980 1TB                         | 1        | 7      | 2.27%   |
| Samsung Electronics SSD 960 EVO 250GB                   | 1        | 5      | 2.27%   |
| Samsung Electronics SSD 850 PRO 512GB                   | 1        | 2      | 2.27%   |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 1TB | 1        | 2      | 2.27%   |
| OCZ TRION100 480GB SSD                                  | 1        | 1      | 2.27%   |
| Kingston SV300S37A120G 120GB SSD                        | 1        | 1      | 2.27%   |
| Kingston SH103S3240G 240GB SSD                          | 1        | 1      | 2.27%   |
| Hitachi HTS543216L9A300 160GB                           | 1        | 1      | 2.27%   |
| Hitachi HDT721032SLA360 320GB                           | 1        | 1      | 2.27%   |
| Hitachi HDS722020ALA330 2TB                             | 1        | 1      | 2.27%   |
| HGST HTS725050A7E635 OPAL 500GB                         | 1        | 3      | 2.27%   |
| HGST HTS725050A7E630 500GB                              | 1        | 4      | 2.27%   |
| Hewlett-Packard SSD EX900 500GB                         | 1        | 1      | 2.27%   |
| Crucial CT960M500SSD1 960GB                             | 1        | 1      | 2.27%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Desktops | Drives | Percent |
|-----------------------|----------|--------|---------|
| WDC                   | 15       | 20     | 37.5%   |
| Seagate               | 6        | 7      | 15%     |
| Toshiba               | 3        | 3      | 7.5%    |
| Hitachi               | 3        | 3      | 7.5%    |
| Samsung Electronics   | 2        | 14     | 5%      |
| Kingston              | 2        | 2      | 5%      |
| Intenso               | 2        | 2      | 5%      |
| SanDisk               | 1        | 1      | 2.5%    |
| Realtek Semiconductor | 1        | 2      | 2.5%    |
| OCZ                   | 1        | 1      | 2.5%    |
| HGST                  | 1        | 7      | 2.5%    |
| Hewlett-Packard       | 1        | 1      | 2.5%    |
| Crucial               | 1        | 1      | 2.5%    |
| A-DATA Technology     | 1        | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| WDC     | 15       | 20     | 50%     |
| Seagate | 6        | 7      | 20%     |
| Toshiba | 3        | 3      | 10%     |
| Hitachi | 3        | 3      | 10%     |
| Intenso | 2        | 2      | 6.67%   |
| HGST    | 1        | 7      | 3.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 25       | 42     | 71.43%  |
| SSD  | 7        | 8      | 20%     |
| NVMe | 3        | 15     | 8.57%   |

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
| Detected | 122      | 393    | 46.21%  |
| Works    | 110      | 366    | 41.67%  |
| Malfunc  | 32       | 65     | 12.12%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Desktops | Percent |
|------------------------------|----------|---------|
| AMD                          | 117      | 31.37%  |
| Intel                        | 94       | 25.2%   |
| Samsung Electronics          | 52       | 13.94%  |
| SanDisk                      | 21       | 5.63%   |
| Kingston Technology Company  | 14       | 3.75%   |
| ASMedia Technology           | 13       | 3.49%   |
| Phison Electronics           | 12       | 3.22%   |
| Micron/Crucial Technology    | 12       | 3.22%   |
| Silicon Motion               | 10       | 2.68%   |
| ADATA Technology             | 6        | 1.61%   |
| Marvell Technology Group     | 5        | 1.34%   |
| Realtek Semiconductor        | 4        | 1.07%   |
| Seagate Technology           | 2        | 0.54%   |
| MAXIO Technology (Hangzhou)  | 2        | 0.54%   |
| JMicron Technology           | 2        | 0.54%   |
| Union Memory (Shenzhen)      | 1        | 0.27%   |
| Toshiba America Info Systems | 1        | 0.27%   |
| SK hynix                     | 1        | 0.27%   |
| Shenzhen Longsys Electronics | 1        | 0.27%   |
| Micron Technology            | 1        | 0.27%   |
| LSI Logic / Symbios Logic    | 1        | 0.27%   |
| Broadcom / LSI               | 1        | 0.27%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 73       | 16.22%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 36       | 8%      |
| AMD 500 Series Chipset SATA Controller                                                  | 24       | 5.33%   |
| AMD 400 Series Chipset SATA Controller                                                  | 24       | 5.33%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 16       | 3.56%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 13       | 2.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 11       | 2.44%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9        | 2%      |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 9        | 2%      |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8        | 1.78%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 8        | 1.78%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 7        | 1.56%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                               | 7        | 1.56%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 7        | 1.56%   |
| Phison E12 NVMe Controller                                                              | 7        | 1.56%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 7        | 1.56%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 7        | 1.56%   |
| AMD 300 Series Chipset SATA Controller                                                  | 7        | 1.56%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                                      | 6        | 1.33%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 6        | 1.33%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6        | 1.33%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 5        | 1.11%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 5        | 1.11%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)                    | 5        | 1.11%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 5        | 1.11%   |
| AMD FCH SATA Controller D                                                               | 5        | 1.11%   |
| Micron/Crucial P1 NVMe PCIe SSD[Frampton]                                               | 4        | 0.89%   |
| Intel SATA Controller [RAID mode]                                                       | 4        | 0.89%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                                    | 4        | 0.89%   |
| Silicon Motion SM2262/SM2262EN SSD Controller                                           | 3        | 0.67%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3        | 0.67%   |
| SanDisk Extreme Pro / WD Black 2018/SN750/PC SN720 NVMe SSD                             | 3        | 0.67%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                       | 3        | 0.67%   |
| Phison E16 PCIe4 NVMe Controller                                                        | 3        | 0.67%   |
| Marvell Group 88SE9215 PCIe 2.0 x1 4-port SATA 6 Gb/s Controller                        | 3        | 0.67%   |
| Kingston Company NV1 NVMe SSD SM2263XT                                                  | 3        | 0.67%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 3        | 0.67%   |
| Intel SSD 660P Series                                                                   | 3        | 0.67%   |
| Intel PROSet/Wireless WiFi Software extension                                           | 3        | 0.67%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 3        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 194      | 55.91%  |
| NVMe | 122      | 35.16%  |
| IDE  | 18       | 5.19%   |
| RAID | 12       | 3.46%   |
| SAS  | 1        | 0.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 119      | 55.87%  |
| Intel  | 94       | 44.13%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| AMD Ryzen 9 3900X 12-Core Processor         | 8        | 3.74%   |
| AMD Ryzen 7 3700X 8-Core Processor          | 8        | 3.74%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 6        | 2.8%    |
| AMD Ryzen 5 5600X 6-Core Processor          | 6        | 2.8%    |
| AMD Ryzen 5 3600 6-Core Processor           | 6        | 2.8%    |
| Intel 12th Gen Core i5-12600K               | 5        | 2.34%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 5        | 2.34%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4        | 1.87%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 4        | 1.87%   |
| AMD Ryzen 7 5800X3D 8-Core Processor        | 4        | 1.87%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 4        | 1.87%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics | 4        | 1.87%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 3        | 1.4%    |
| AMD Ryzen 9 7900X 12-Core Processor         | 3        | 1.4%    |
| AMD Ryzen 7 3800X 8-Core Processor          | 3        | 1.4%    |
| AMD Ryzen 7 2700X Eight-Core Processor      | 3        | 1.4%    |
| AMD Ryzen 7 2700 Eight-Core Processor       | 3        | 1.4%    |
| AMD Ryzen 5 2600 Six-Core Processor         | 3        | 1.4%    |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3        | 1.4%    |
| AMD FX-8350 Eight-Core Processor            | 3        | 1.4%    |
| Intel Core i7-7700K CPU @ 4.20GHz           | 2        | 0.93%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 2        | 0.93%   |
| Intel Core i5-9600K CPU @ 3.70GHz           | 2        | 0.93%   |
| Intel Core i5-4590 CPU @ 3.30GHz            | 2        | 0.93%   |
| Intel Core i5-4570 CPU @ 3.20GHz            | 2        | 0.93%   |
| Intel Core i3-7100 CPU @ 3.90GHz            | 2        | 0.93%   |
| Intel Core i3-3220 CPU @ 3.30GHz            | 2        | 0.93%   |
| Intel Core i3-2100 CPU @ 3.10GHz            | 2        | 0.93%   |
| AMD Ryzen 9 6900HX with Radeon Graphics     | 2        | 0.93%   |
| AMD Ryzen 7 7700 8-Core Processor           | 2        | 0.93%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 2        | 0.93%   |
| AMD Ryzen 5 2600X Six-Core Processor        | 2        | 0.93%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics | 2        | 0.93%   |
| AMD Ryzen 5 1600X Six-Core Processor        | 2        | 0.93%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2        | 0.93%   |
| Intel Xeon CPU W3550 @ 3.07GHz              | 1        | 0.47%   |
| Intel Xeon CPU E5-2690 0 @ 2.90GHz          | 1        | 0.47%   |
| Intel Xeon CPU E5-2680 v2 @ 2.80GHz         | 1        | 0.47%   |
| Intel Xeon CPU E5-2650 v4 @ 2.20GHz         | 1        | 0.47%   |
| Intel Xeon CPU E5-1680 v2 @ 3.00GHz         | 1        | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| AMD Ryzen 7             | 38       | 17.84%  |
| AMD Ryzen 5             | 34       | 15.96%  |
| Intel Core i5           | 29       | 13.62%  |
| Intel Core i7           | 24       | 11.27%  |
| AMD Ryzen 9             | 22       | 10.33%  |
| Intel Core i3           | 16       | 7.51%   |
| Other                   | 11       | 5.16%   |
| AMD FX                  | 7        | 3.29%   |
| Intel Xeon              | 6        | 2.82%   |
| AMD Ryzen 3             | 6        | 2.82%   |
| AMD Ryzen Threadripper  | 3        | 1.41%   |
| Intel Core i9           | 2        | 0.94%   |
| Intel Celeron           | 2        | 0.94%   |
| AMD Phenom II X6        | 2        | 0.94%   |
| AMD A10                 | 2        | 0.94%   |
| Intel Pentium Dual-Core | 1        | 0.47%   |
| Intel Pentium           | 1        | 0.47%   |
| Intel Core 2 Quad       | 1        | 0.47%   |
| Intel Core 2 Duo        | 1        | 0.47%   |
| AMD Phenom II X4        | 1        | 0.47%   |
| AMD Phenom II X2        | 1        | 0.47%   |
| AMD Athlon X4           | 1        | 0.47%   |
| AMD Athlon              | 1        | 0.47%   |
| AMD A8                  | 1        | 0.47%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 63       | 29.58%  |
| 8      | 51       | 23.94%  |
| 6      | 42       | 19.72%  |
| 2      | 25       | 11.74%  |
| 12     | 14       | 6.57%   |
| 16     | 7        | 3.29%   |
| 10     | 6        | 2.82%   |
| 24     | 2        | 0.94%   |
| 20     | 1        | 0.47%   |
| 14     | 1        | 0.47%   |
| 3      | 1        | 0.47%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 211      | 99.06%  |
| 2      | 2        | 0.94%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 2      | 170      | 79.81%  |
| 1      | 43       | 20.19%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 213      | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 106      | 48.85%  |
| 0x08701021 | 11       | 5.07%   |
| 0x0800820d | 8        | 3.69%   |
| 0x306c3    | 7        | 3.23%   |
| 0x0a601203 | 6        | 2.76%   |
| 0x0a20120a | 6        | 2.76%   |
| 0x306a9    | 5        | 2.3%    |
| 0x206a7    | 5        | 2.3%    |
| 0x0a50000d | 4        | 1.84%   |
| 0x0a50000c | 4        | 1.84%   |
| 0xa0653    | 3        | 1.38%   |
| 0x906ea    | 3        | 1.38%   |
| 0x506e3    | 3        | 1.38%   |
| 0x0a201025 | 3        | 1.38%   |
| 0x0a201009 | 3        | 1.38%   |
| 0x08108109 | 3        | 1.38%   |
| 0x08001137 | 3        | 1.38%   |
| 0x906ed    | 2        | 0.92%   |
| 0x906e9    | 2        | 0.92%   |
| 0x90672    | 2        | 0.92%   |
| 0x0a404102 | 2        | 0.92%   |
| 0x0a201204 | 2        | 0.92%   |
| 0x0a201016 | 2        | 0.92%   |
| 0x0810100b | 2        | 0.92%   |
| 0x08001138 | 2        | 0.92%   |
| 0x06000852 | 2        | 0.92%   |
| 0x010000dc | 2        | 0.92%   |
| 0xa0655    | 1        | 0.46%   |
| 0x906ec    | 1        | 0.46%   |
| 0x906eb    | 1        | 0.46%   |
| 0x90675    | 1        | 0.46%   |
| 0x306e4    | 1        | 0.46%   |
| 0x106a5    | 1        | 0.46%   |
| 0x1067a    | 1        | 0.46%   |
| 0x0a601201 | 1        | 0.46%   |
| 0x0a50000b | 1        | 0.46%   |
| 0x08701030 | 1        | 0.46%   |
| 0x08701013 | 1        | 0.46%   |
| 0x08101016 | 1        | 0.46%   |
| 0x06003106 | 1        | 0.46%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Zen 3            | 35       | 16.36%  |
| Zen 2            | 27       | 12.62%  |
| Zen+             | 21       | 9.81%   |
| KabyLake         | 18       | 8.41%   |
| Haswell          | 18       | 8.41%   |
| IvyBridge        | 15       | 7.01%   |
| Unknown          | 14       | 6.54%   |
| Zen              | 12       | 5.61%   |
| SandyBridge      | 11       | 5.14%   |
| Piledriver       | 8        | 3.74%   |
| CometLake        | 8        | 3.74%   |
| Alderlake Hybrid | 6        | 2.8%    |
| Skylake          | 5        | 2.34%   |
| K10              | 4        | 1.87%   |
| Steamroller      | 3        | 1.4%    |
| Penryn           | 3        | 1.4%    |
| Nehalem          | 2        | 0.93%   |
| Broadwell        | 2        | 0.93%   |
| Westmere         | 1        | 0.47%   |
| Icelake          | 1        | 0.47%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| AMD    | 106      | 44.17%  |
| Nvidia | 90       | 37.5%   |
| Intel  | 44       | 18.33%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 15       | 5.95%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 14       | 5.56%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 11       | 4.37%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 11       | 4.37%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 8        | 3.17%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 7        | 2.78%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 7        | 2.78%   |
| AMD Raphael                                                                 | 6        | 2.38%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 6        | 2.38%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 5        | 1.98%   |
| Nvidia TU104 [GeForce RTX 2080 Rev. A]                                      | 4        | 1.59%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4        | 1.59%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 4        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 4        | 1.59%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4        | 1.59%   |
| Nvidia GK208B [GeForce GT 710]                                              | 4        | 1.59%   |
| Nvidia GA104 [GeForce RTX 3060 Ti Lite Hash Rate]                           | 4        | 1.59%   |
| Intel AlderLake-S GT1                                                       | 4        | 1.59%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 4        | 1.59%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 4        | 1.59%   |
| Nvidia GT218 [GeForce 210]                                                  | 3        | 1.19%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 3        | 1.19%   |
| Nvidia GP102 [GeForce GTX 1080 Ti]                                          | 3        | 1.19%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 3        | 1.19%   |
| Nvidia GK106 [GeForce GTX 660]                                              | 3        | 1.19%   |
| Nvidia GA102 [GeForce RTX 3080]                                             | 3        | 1.19%   |
| Intel HD Graphics 630                                                       | 3        | 1.19%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 3        | 1.19%   |
| AMD Polaris 20 XL [Radeon RX 580 2048SP]                                    | 3        | 1.19%   |
| AMD Navi 31 [Radeon RX 7900 XT/7900 XTX]                                    | 3        | 1.19%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 3        | 1.19%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 2        | 0.79%   |
| Nvidia TU116 [GeForce GTX 1650 SUPER]                                       | 2        | 0.79%   |
| Nvidia TU102 [GeForce RTX 2080 Ti Rev. A]                                   | 2        | 0.79%   |
| Nvidia GP104 [GeForce GTX 1070 Ti]                                          | 2        | 0.79%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 2        | 0.79%   |
| Nvidia GM204 [GeForce GTX 980]                                              | 2        | 0.79%   |
| Nvidia GK208 [GeForce GT 635]                                               | 2        | 0.79%   |
| Nvidia GA106 [GeForce RTX 3060 Lite Hash Rate]                              | 2        | 0.79%   |
| Nvidia GA102 [GeForce RTX 3090]                                             | 2        | 0.79%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Desktops | Percent |
|----------------|----------|---------|
| 1 x AMD        | 87       | 40.09%  |
| 1 x Nvidia     | 75       | 34.56%  |
| 1 x Intel      | 27       | 12.44%  |
| 2 x AMD        | 8        | 3.69%   |
| AMD + Nvidia   | 8        | 3.69%   |
| Intel + Nvidia | 4        | 1.84%   |
| Intel + AMD    | 4        | 1.84%   |
| 2 x Nvidia     | 3        | 1.38%   |
| 2 x Intel      | 1        | 0.46%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 137      | 63.43%  |
| Proprietary | 78       | 36.11%  |
| Unknown     | 1        | 0.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 77       | 35.32%  |
| 7.01-8.0   | 37       | 16.97%  |
| 8.01-16.0  | 30       | 13.76%  |
| 3.01-4.0   | 25       | 11.47%  |
| 1.01-2.0   | 19       | 8.72%   |
| 5.01-6.0   | 9        | 4.13%   |
| 0.51-1.0   | 7        | 3.21%   |
| 0.01-0.5   | 7        | 3.21%   |
| 16.01-24.0 | 5        | 2.29%   |
| 2.01-3.0   | 2        | 0.92%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Samsung Electronics  | 43       | 15.3%   |
| Dell                 | 27       | 9.61%   |
| Goldstar             | 25       | 8.9%    |
| Acer                 | 25       | 8.9%    |
| AOC                  | 21       | 7.47%   |
| Hewlett-Packard      | 16       | 5.69%   |
| BenQ                 | 13       | 4.63%   |
| Ancor Communications | 12       | 4.27%   |
| ASUSTek Computer     | 9        | 3.2%    |
| Unknown              | 7        | 2.49%   |
| Philips              | 7        | 2.49%   |
| ViewSonic            | 6        | 2.14%   |
| MSI                  | 6        | 2.14%   |
| NEC Computers        | 5        | 1.78%   |
| Iiyama               | 5        | 1.78%   |
| Gigabyte Technology  | 5        | 1.78%   |
| Sony                 | 3        | 1.07%   |
| Lenovo               | 3        | 1.07%   |
| Vizio                | 2        | 0.71%   |
| Toshiba              | 2        | 0.71%   |
| Mi                   | 2        | 0.71%   |
| LG Electronics       | 2        | 0.71%   |
| Insignia             | 2        | 0.71%   |
| ___                  | 1        | 0.36%   |
| Xiaomi               | 1        | 0.36%   |
| VIZ                  | 1        | 0.36%   |
| Viotek               | 1        | 0.36%   |
| Vestel               | 1        | 0.36%   |
| Sceptre Tech         | 1        | 0.36%   |
| Sceptre              | 1        | 0.36%   |
| SAC                  | 1        | 0.36%   |
| RTK                  | 1        | 0.36%   |
| Plain Tree Systems   | 1        | 0.36%   |
| Panasonic            | 1        | 0.36%   |
| Optoma               | 1        | 0.36%   |
| ONN                  | 1        | 0.36%   |
| MiTAC                | 1        | 0.36%   |
| Microstep            | 1        | 0.36%   |
| LTM                  | 1        | 0.36%   |
| Lenovo Group Limited | 1        | 0.36%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 4        | 1.32%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 3        | 0.99%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                 | 3        | 0.99%   |
| ViewSonic VX3258 series VSCDE35 2560x1440 700x390mm 31.5-inch          | 2        | 0.66%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch      | 2        | 0.66%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch               | 2        | 0.66%   |
| MSI G273 MSI3CA7 1920x1080 590x330mm 26.6-inch                         | 2        | 0.66%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 800x340mm 34.2-inch            | 2        | 0.66%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                     | 2        | 0.66%   |
| Dell SE2719HR DELF115 1920x1080 600x340mm 27.2-inch                    | 2        | 0.66%   |
| Dell D3218HN DEL200B 1920x1080 698x393mm 31.5-inch                     | 2        | 0.66%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                        | 2        | 0.66%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                     | 2        | 0.66%   |
| AOC 27G1G4 AOC2701 1920x1080 598x336mm 27.0-inch                       | 2        | 0.66%   |
| AOC 2460G4 AOC0001 1920x1080 530x300mm 24.0-inch                       | 2        | 0.66%   |
| Ancor Communications ASUS PB287Q ACI28A3 3840x2160 621x341mm 27.9-inch | 2        | 0.66%   |
| Acer X223W ACR0009 1680x1050 473x296mm 22.0-inch                       | 2        | 0.66%   |
| Acer ED322Q ACR0574 1920x1080 521x293mm 23.5-inch                      | 2        | 0.66%   |
| ___ LCD TV ___9000 1360x768                                            | 1        | 0.33%   |
| Xiaomi DPF90435 XMD009A 2224x1668 341x192mm 15.4-inch                  | 1        | 0.33%   |
| Vizio P502ui-B1E VIZ1013 3840x2160 1095x616mm 49.5-inch                | 1        | 0.33%   |
| Vizio D320-B1 VIZ0095 1360x768 697x392mm 31.5-inch                     | 1        | 0.33%   |
| VIZ LCD Monitor D40f-J09 1920x1080                                     | 1        | 0.33%   |
| Viotek VIOTEKGN27C2 VTK0027 1920x1080 598x336mm 27.0-inch              | 1        | 0.33%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch             | 1        | 0.33%   |
| ViewSonic VX2703 SERIES VSCF62B 1920x1080 597x336mm 27.0-inch          | 1        | 0.33%   |
| ViewSonic VX2270 SERIES VSCE02C 1920x1080 476x267mm 21.5-inch          | 1        | 0.33%   |
| ViewSonic VA2415 SERIES VSCBC3C 1920x1080 521x293mm 23.5-inch          | 1        | 0.33%   |
| Vestel LCD Monitor 24W_LCD_TV 1920x1080                                | 1        | 0.33%   |
| Unknown LCD Monitor XXX AAA 1366x768                                   | 1        | 0.33%   |
| Unknown LCD Monitor SAMSUNG 3840x2160                                  | 1        | 0.33%   |
| Unknown LCD Monitor SAMSUNG                                            | 1        | 0.33%   |
| Unknown LCD Monitor RJT HDMI                                           | 1        | 0.33%   |
| Unknown LCD Monitor LHC 32-QHD-144-C 4480x1440                         | 1        | 0.33%   |
| Unknown LCD Monitor Hitachi/HINT W240D DVI                             | 1        | 0.33%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 1        | 0.33%   |
| Toshiba TV TSB0105 1920x1080 708x398mm 32.0-inch                       | 1        | 0.33%   |
| Toshiba TSB-TV TSB0206 1360x768 930x520mm 41.9-inch                    | 1        | 0.33%   |
| Sony TV SNY4B03 1920x1080 710x400mm 32.1-inch                          | 1        | 0.33%   |
| Sony TV SNY1802 1920x1080                                              | 1        | 0.33%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 119      | 44.4%   |
| 3840x2160 (4K)     | 36       | 13.43%  |
| 2560x1440 (QHD)    | 21       | 7.84%   |
| 3440x1440          | 12       | 4.48%   |
| Unknown            | 10       | 3.73%   |
| 1680x1050 (WSXGA+) | 9        | 3.36%   |
| 1366x768 (WXGA)    | 9        | 3.36%   |
| 1920x1200 (WUXGA)  | 8        | 2.99%   |
| 2560x1080          | 7        | 2.61%   |
| 1440x900 (WXGA+)   | 7        | 2.61%   |
| 1280x1024 (SXGA)   | 6        | 2.24%   |
| 3840x1080          | 5        | 1.87%   |
| 1600x900 (HD+)     | 4        | 1.49%   |
| 7680x2160          | 2        | 0.75%   |
| 3840x1200          | 2        | 0.75%   |
| 1360x768           | 2        | 0.75%   |
| 9600x2160          | 1        | 0.37%   |
| 4480x1440          | 1        | 0.37%   |
| 3360x1050          | 1        | 0.37%   |
| 2560x1600          | 1        | 0.37%   |
| 2288x1287          | 1        | 0.37%   |
| 2048x1152          | 1        | 0.37%   |
| 1920x540           | 1        | 0.37%   |
| 1400x1050          | 1        | 0.37%   |
| 1280x720 (HD)      | 1        | 0.37%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 27      | 52       | 19.12%  |
| Unknown | 38       | 13.97%  |
| 24      | 37       | 13.6%   |
| 23      | 26       | 9.56%   |
| 21      | 21       | 7.72%   |
| 31      | 17       | 6.25%   |
| 34      | 13       | 4.78%   |
| 22      | 9        | 3.31%   |
| 20      | 7        | 2.57%   |
| 19      | 7        | 2.57%   |
| 18      | 6        | 2.21%   |
| 72      | 5        | 1.84%   |
| 25      | 4        | 1.47%   |
| 26      | 3        | 1.1%    |
| 74      | 2        | 0.74%   |
| 49      | 2        | 0.74%   |
| 48      | 2        | 0.74%   |
| 43      | 2        | 0.74%   |
| 40      | 2        | 0.74%   |
| 29      | 2        | 0.74%   |
| 28      | 2        | 0.74%   |
| 17      | 2        | 0.74%   |
| 142     | 1        | 0.37%   |
| 84      | 1        | 0.37%   |
| 58      | 1        | 0.37%   |
| 54      | 1        | 0.37%   |
| 50      | 1        | 0.37%   |
| 47      | 1        | 0.37%   |
| 46      | 1        | 0.37%   |
| 35      | 1        | 0.37%   |
| 33      | 1        | 0.37%   |
| 32      | 1        | 0.37%   |
| 16      | 1        | 0.37%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 103      | 39.92%  |
| 401-500        | 44       | 17.05%  |
| Unknown        | 38       | 14.73%  |
| 601-700        | 28       | 10.85%  |
| 701-800        | 15       | 5.81%   |
| 1001-1500      | 10       | 3.88%   |
| 1501-2000      | 8        | 3.1%    |
| 351-400        | 5        | 1.94%   |
| 801-900        | 3        | 1.16%   |
| 301-350        | 2        | 0.78%   |
| More than 2000 | 1        | 0.39%   |
| 901-1000       | 1        | 0.39%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 150      | 63.56%  |
| Unknown | 34       | 14.41%  |
| 16/10   | 26       | 11.02%  |
| 21/9    | 15       | 6.36%   |
| 5/4     | 6        | 2.54%   |
| 32/9    | 3        | 1.27%   |
| 3.20    | 1        | 0.42%   |
| 1.00    | 1        | 0.42%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 70       | 26.82%  |
| 301-350        | 55       | 21.07%  |
| Unknown        | 38       | 14.56%  |
| 351-500        | 35       | 13.41%  |
| 151-200        | 19       | 7.28%   |
| 251-300        | 15       | 5.75%   |
| More than 1000 | 14       | 5.36%   |
| 501-1000       | 8        | 3.07%   |
| 141-150        | 6        | 2.3%    |
| 121-130        | 1        | 0.38%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 134      | 55.83%  |
| 101-120 | 42       | 17.5%   |
| Unknown | 38       | 15.83%  |
| 121-160 | 12       | 5%      |
| 1-50    | 10       | 4.17%   |
| 161-240 | 4        | 1.67%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 135      | 61.64%  |
| 2     | 60       | 27.4%   |
| 3     | 18       | 8.22%   |
| 0     | 4        | 1.83%   |
| 4     | 2        | 0.91%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Realtek Semiconductor           | 142      | 43.56%  |
| Intel                           | 103      | 31.6%   |
| MediaTek                        | 17       | 5.21%   |
| Qualcomm Atheros                | 13       | 3.99%   |
| Broadcom                        | 6        | 1.84%   |
| Ralink Technology               | 5        | 1.53%   |
| NetGear                         | 5        | 1.53%   |
| TP-Link                         | 4        | 1.23%   |
| Microsoft                       | 4        | 1.23%   |
| Linksys                         | 4        | 1.23%   |
| Samsung Electronics             | 3        | 0.92%   |
| Aquantia                        | 3        | 0.92%   |
| Ralink                          | 2        | 0.61%   |
| DisplayLink                     | 2        | 0.61%   |
| D-Link                          | 2        | 0.61%   |
| AVM                             | 2        | 0.61%   |
| Xiaomi                          | 1        | 0.31%   |
| Sitecom Europe                  | 1        | 0.31%   |
| Qualcomm Atheros Communications | 1        | 0.31%   |
| InterBiometrics                 | 1        | 0.31%   |
| Holtek Semiconductor            | 1        | 0.31%   |
| Belkin Components               | 1        | 0.31%   |
| ASIX Electronics                | 1        | 0.31%   |
| Alteon Networks                 | 1        | 0.31%   |
| Accton Technology               | 1        | 0.31%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller   | 104      | 27.44%  |
| Realtek RTL8125 2.5GbE Controller                                   | 30       | 7.92%   |
| Intel I211 Gigabit Network Connection                               | 25       | 6.6%    |
| Intel Wi-Fi 6 AX200                                                 | 18       | 4.75%   |
| Intel Ethernet Controller I225-V                                    | 17       | 4.49%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 9        | 2.37%   |
| Intel Wireless-AC 9260                                              | 8        | 2.11%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 8        | 2.11%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 7        | 1.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 7        | 1.85%   |
| Intel Ethernet Connection I217-LM                                   | 7        | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)               | 7        | 1.85%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 6        | 1.58%   |
| Intel Ethernet Connection (2) I219-V                                | 5        | 1.32%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller               | 3        | 0.79%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3        | 0.79%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller           | 3        | 0.79%   |
| NetGear A6210                                                       | 3        | 0.79%   |
| Intel Wireless 7265                                                 | 3        | 0.79%   |
| Intel Ethernet Connection (7) I219-V                                | 3        | 0.79%   |
| Intel 82579V Gigabit Network Connection                             | 3        | 0.79%   |
| Samsung Galaxy series, misc. (tethering mode)                       | 2        | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 0.53%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                            | 2        | 0.53%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 2        | 0.53%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                            | 2        | 0.53%   |
| Microsoft Xbox Wireless Adapter for Windows                         | 2        | 0.53%   |
| Microsoft Wireless XBox Controller Dongle                           | 2        | 0.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 2        | 0.53%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2        | 0.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 2        | 0.53%   |
| Intel Ethernet Connection (2) I218-V                                | 2        | 0.53%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 2        | 0.53%   |
| AVM FRITZ!WLAN AC 860                                               | 2        | 0.53%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion]   | 2        | 0.53%   |
| Xiaomi Mi/Redmi series (RNDIS)                                      | 1        | 0.26%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1        | 0.26%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.26%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                          | 1        | 0.26%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 54       | 40.3%   |
| Realtek Semiconductor           | 24       | 17.91%  |
| MediaTek                        | 15       | 11.19%  |
| Qualcomm Atheros                | 6        | 4.48%   |
| Ralink Technology               | 5        | 3.73%   |
| NetGear                         | 5        | 3.73%   |
| TP-Link                         | 4        | 2.99%   |
| Microsoft                       | 4        | 2.99%   |
| Linksys                         | 4        | 2.99%   |
| Broadcom                        | 4        | 2.99%   |
| Ralink                          | 2        | 1.49%   |
| D-Link                          | 2        | 1.49%   |
| AVM                             | 2        | 1.49%   |
| Sitecom Europe                  | 1        | 0.75%   |
| Qualcomm Atheros Communications | 1        | 0.75%   |
| Accton Technology               | 1        | 0.75%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                               | Desktops | Percent |
|---------------------------------------------------------------------|----------|---------|
| Intel Wi-Fi 6 AX200                                                 | 18       | 13.43%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter            | 9        | 6.72%   |
| Intel Wireless-AC 9260                                              | 8        | 5.97%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                    | 8        | 5.97%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                             | 7        | 5.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                              | 7        | 5.22%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter       | 6        | 4.48%   |
| Ralink RT2870/RT3070 Wireless Adapter                               | 3        | 2.24%   |
| NetGear A6210                                                       | 3        | 2.24%   |
| Intel Wireless 7265                                                 | 3        | 2.24%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                     | 2        | 1.49%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter             | 2        | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter          | 2        | 1.49%   |
| Microsoft Xbox Wireless Adapter for Windows                         | 2        | 1.49%   |
| Microsoft Wireless XBox Controller Dongle                           | 2        | 1.49%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter       | 2        | 1.49%   |
| Linksys AE6000 802.11a/b/g/n/ac Wireless Adapter [MediaTek MT7610U] | 2        | 1.49%   |
| Intel Tiger Lake PCH CNVi WiFi                                      | 2        | 1.49%   |
| Intel Comet Lake PCH CNVi WiFi                                      | 2        | 1.49%   |
| AVM FRITZ!WLAN AC 860                                               | 2        | 1.49%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                         | 1        | 0.75%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                        | 1        | 0.75%   |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                          | 1        | 0.75%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]          | 1        | 0.75%   |
| Sitecom Europe WLA-5000 802.11abgn [Ralink RT3572]                  | 1        | 0.75%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                  | 1        | 0.75%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter            | 1        | 0.75%   |
| Realtek RTL8814AU 802.11a/b/g/n/ac Wireless Adapter                 | 1        | 0.75%   |
| Realtek RTL8192CE PCIe Wireless Network Adapter                     | 1        | 0.75%   |
| Realtek RTL8191SU 802.11n WLAN Adapter                              | 1        | 0.75%   |
| Realtek RTL8188RU 802.11n WLAN Adapter                              | 1        | 0.75%   |
| Realtek RTL8188FTV 802.11b/g/n 1T1R 2.4G WLAN Adapter               | 1        | 0.75%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                 | 1        | 0.75%   |
| Realtek RTL8188EE Wireless Network Adapter                          | 1        | 0.75%   |
| Realtek 802.11n WLAN Adapter                                        | 1        | 0.75%   |
| Realtek 802.11ac NIC                                                | 1        | 0.75%   |
| Ralink Wireless Adapter Canyon CN-WF511                             | 1        | 0.75%   |
| Ralink RT2501/RT2573 Wireless Adapter                               | 1        | 0.75%   |
| Ralink MT7601U Wireless Adapter                                     | 1        | 0.75%   |
| Ralink RT5390R 802.11bgn PCIe Wireless Network Adapter              | 1        | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Desktops | Percent |
|-----------------------|----------|---------|
| Realtek Semiconductor | 137      | 58.55%  |
| Intel                 | 73       | 31.2%   |
| Qualcomm Atheros      | 8        | 3.42%   |
| Samsung Electronics   | 3        | 1.28%   |
| Aquantia              | 3        | 1.28%   |
| MediaTek              | 2        | 0.85%   |
| DisplayLink           | 2        | 0.85%   |
| Broadcom              | 2        | 0.85%   |
| Xiaomi                | 1        | 0.43%   |
| Belkin Components     | 1        | 0.43%   |
| ASIX Electronics      | 1        | 0.43%   |
| Alteon Networks       | 1        | 0.43%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Desktops | Percent |
|-------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 104      | 42.8%   |
| Realtek RTL8125 2.5GbE Controller                                 | 30       | 12.35%  |
| Intel I211 Gigabit Network Connection                             | 25       | 10.29%  |
| Intel Ethernet Controller I225-V                                  | 17       | 7%      |
| Intel Ethernet Connection I217-LM                                 | 7        | 2.88%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 7        | 2.88%   |
| Intel Ethernet Connection (2) I219-V                              | 5        | 2.06%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 3        | 1.23%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3        | 1.23%   |
| Intel Ethernet Connection (7) I219-V                              | 3        | 1.23%   |
| Intel 82579V Gigabit Network Connection                           | 3        | 1.23%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2        | 0.82%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2        | 0.82%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2        | 0.82%   |
| Intel Ethernet Connection (2) I218-V                              | 2        | 0.82%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2        | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1        | 0.41%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1        | 0.41%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1        | 0.41%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1        | 0.41%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1        | 0.41%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1        | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 1        | 0.41%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1        | 0.41%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 1        | 0.41%   |
| MediaTek Wiko U316AT                                              | 1        | 0.41%   |
| MediaTek RMX3085                                                  | 1        | 0.41%   |
| Intel Ethernet Controller I225-LM                                 | 1        | 0.41%   |
| Intel Ethernet Connection I217-V                                  | 1        | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 1        | 0.41%   |
| Intel Ethernet Connection (14) I219-LM                            | 1        | 0.41%   |
| Intel 82580 Gigabit Network Connection                            | 1        | 0.41%   |
| Intel 82576 Gigabit Network Connection                            | 1        | 0.41%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 1        | 0.41%   |
| DisplayLink USB-C Dual-4K Dock                                    | 1        | 0.41%   |
| DisplayLink ThinkPad USB 3.0 Dock                                 | 1        | 0.41%   |
| Broadcom NetXtreme BCM5755 Gigabit Ethernet PCI Express           | 1        | 0.41%   |
| Broadcom NetLink BCM57788 Gigabit Ethernet PCIe                   | 1        | 0.41%   |
| Belkin Components F5D5050 100Mbps Ethernet                        | 1        | 0.41%   |
| ASIX AX88179 Gigabit Ethernet                                     | 1        | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 210      | 62.87%  |
| WiFi     | 122      | 36.53%  |
| Modem    | 1        | 0.3%    |
| Unknown  | 1        | 0.3%    |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 161      | 72.2%   |
| WiFi     | 62       | 27.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 115      | 53.24%  |
| 2     | 80       | 37.04%  |
| 3     | 16       | 7.41%   |
| 6     | 2        | 0.93%   |
| 0     | 2        | 0.93%   |
| 4     | 1        | 0.46%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 162      | 75.7%   |
| Yes  | 52       | 24.3%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Intel                           | 47       | 42.34%  |
| Cambridge Silicon Radio         | 18       | 16.22%  |
| Realtek Semiconductor           | 13       | 11.71%  |
| MediaTek                        | 11       | 9.91%   |
| ASUSTek Computer                | 7        | 6.31%   |
| Qualcomm Atheros Communications | 5        | 4.5%    |
| IMC Networks                    | 4        | 3.6%    |
| Broadcom                        | 4        | 3.6%    |
| Edimax Technology               | 1        | 0.9%    |
| Dynex                           | 1        | 0.9%    |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                    | Desktops | Percent |
|----------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)      | 18       | 16.22%  |
| Intel AX200 Bluetooth                                    | 15       | 13.51%  |
| MediaTek Wireless_Device                                 | 11       | 9.91%   |
| Realtek Bluetooth Radio                                  | 9        | 8.11%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                 | 8        | 7.21%   |
| Intel Wireless-AC 3168 Bluetooth                         | 8        | 7.21%   |
| Intel AX210 Bluetooth                                    | 5        | 4.5%    |
| Realtek  Bluetooth 4.2 Adapter                           | 4        | 3.6%    |
| Qualcomm Atheros  Bluetooth Device                       | 4        | 3.6%    |
| Intel AX201 Bluetooth                                    | 4        | 3.6%    |
| Intel Bluetooth wireless interface                       | 3        | 2.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                        | 3        | 2.7%    |
| Intel Bluetooth Device                                   | 2        | 1.8%    |
| IMC Networks Wireless_Device                             | 2        | 1.8%    |
| IMC Networks Bluetooth Radio                             | 2        | 1.8%    |
| ASUS Bluetooth Radio                                     | 2        | 1.8%    |
| ASUS ASUS USB-BT500                                      | 2        | 1.8%    |
| Qualcomm Atheros AR3011 Bluetooth                        | 1        | 0.9%    |
| Intel Centrino Bluetooth Wireless Transceiver            | 1        | 0.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)           | 1        | 0.9%    |
| Edimax Bluetooth Adapter                                 | 1        | 0.9%    |
| Dynex Bluetooth 4.0 Adapter [Broadcom, 1.12, BCM20702A0] | 1        | 0.9%    |
| Broadcom BCM43142A0 Bluetooth Device                     | 1        | 0.9%    |
| ASUS Qualcomm Bluetooth 4.1                              | 1        | 0.9%    |
| ASUS Broadcom BCM20702A0 Bluetooth                       | 1        | 0.9%    |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE    | 1        | 0.9%    |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Desktops | Percent |
|--------------------------|----------|---------|
| AMD                      | 138      | 32.7%   |
| Intel                    | 94       | 22.27%  |
| Nvidia                   | 91       | 21.56%  |
| C-Media Electronics      | 18       | 4.27%   |
| Logitech                 | 12       | 2.84%   |
| Kingston Technology      | 6        | 1.42%   |
| Blue Microphones         | 5        | 1.18%   |
| Texas Instruments        | 4        | 0.95%   |
| Sony                     | 4        | 0.95%   |
| JMTek                    | 4        | 0.95%   |
| Trust                    | 3        | 0.71%   |
| Focusrite-Novation       | 3        | 0.71%   |
| Creative Technology      | 3        | 0.71%   |
| Yamaha                   | 2        | 0.47%   |
| Razer USA                | 2        | 0.47%   |
| Micro Star International | 2        | 0.47%   |
| Generalplus Technology   | 2        | 0.47%   |
| DSEA A/S                 | 2        | 0.47%   |
| Digidesign               | 2        | 0.47%   |
| Creative Labs            | 2        | 0.47%   |
| XMOS                     | 1        | 0.24%   |
| Tenx Technology          | 1        | 0.24%   |
| SteelSeries ApS          | 1        | 0.24%   |
| Samson Technologies      | 1        | 0.24%   |
| RODE Microphones         | 1        | 0.24%   |
| ROCCAT                   | 1        | 0.24%   |
| Plantronics              | 1        | 0.24%   |
| M-Audio                  | 1        | 0.24%   |
| KORG                     | 1        | 0.24%   |
| Hewlett-Packard          | 1        | 0.24%   |
| Harman International     | 1        | 0.24%   |
| FIFINE Microphones       | 1        | 0.24%   |
| EVGA                     | 1        | 0.24%   |
| DigiTech                 | 1        | 0.24%   |
| Comtrue                  | 1        | 0.24%   |
| Cambridge Audio          | 1        | 0.24%   |
| Audio-Technica           | 1        | 0.24%   |
| ASUSTek Computer         | 1        | 0.24%   |
| Astro Gaming             | 1        | 0.24%   |
| Arturia                  | 1        | 0.24%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD Starship/Matisse HD Audio Controller                                   | 51       | 9.57%   |
| AMD Family 17h/19h HD Audio Controller                                     | 30       | 5.63%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 29       | 5.44%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 20       | 3.75%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 18       | 3.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14       | 2.63%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 14       | 2.63%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 12       | 2.25%   |
| Nvidia GP104 High Definition Audio Controller                              | 11       | 2.06%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 11       | 2.06%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 11       | 2.06%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 11       | 2.06%   |
| AMD Navi 10 HDMI Audio                                                     | 11       | 2.06%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 9        | 1.69%   |
| Nvidia GA104 High Definition Audio Controller                              | 8        | 1.5%    |
| Intel 200 Series PCH HD Audio                                              | 8        | 1.5%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 8        | 1.5%    |
| Nvidia GP107GL High Definition Audio Controller                            | 7        | 1.31%   |
| Nvidia GA102 High Definition Audio Controller                              | 7        | 1.31%   |
| Intel Cannon Lake PCH cAVS                                                 | 7        | 1.31%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 7        | 1.31%   |
| Nvidia TU104 HD Audio Controller                                           | 6        | 1.13%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 6        | 1.13%   |
| C-Media Electronics USB Audio Device                                       | 6        | 1.13%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6        | 1.13%   |
| Nvidia TU116 High Definition Audio Controller                              | 5        | 0.94%   |
| Nvidia GP106 High Definition Audio Controller                              | 5        | 0.94%   |
| Nvidia GM204 High Definition Audio Controller                              | 5        | 0.94%   |
| Intel Alder Lake-S HD Audio Controller                                     | 5        | 0.94%   |
| C-Media Electronics Audio Adapter (Unitek Y-247A)                          | 5        | 0.94%   |
| Blue Microphones Yeti Stereo Microphone                                    | 5        | 0.94%   |
| AMD Vega 10 HDMI Audio [Radeon Vega 56/64]                                 | 5        | 0.94%   |
| AMD Navi 31 HDMI/DP Audio                                                  | 5        | 0.94%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 5        | 0.94%   |
| Nvidia High Definition Audio Controller                                    | 4        | 0.75%   |
| Nvidia GM206 High Definition Audio Controller                              | 4        | 0.75%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 4        | 0.75%   |
| Nvidia GK106 HDMI Audio Controller                                         | 4        | 0.75%   |
| Intel Comet Lake PCH-V cAVS                                                | 4        | 0.75%   |
| Texas Instruments PCM2902 Audio Codec                                      | 3        | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Desktops | Percent |
|-----------------------------------------|----------|---------|
| G.Skill                                 | 31       | 22.46%  |
| Corsair                                 | 21       | 15.22%  |
| Kingston                                | 18       | 13.04%  |
| Samsung Electronics                     | 11       | 7.97%   |
| Crucial                                 | 11       | 7.97%   |
| SK hynix                                | 9        | 6.52%   |
| Unknown                                 | 8        | 5.8%    |
| Patriot                                 | 8        | 5.8%    |
| Patriot Memory (PDP Systems)            | 4        | 2.9%    |
| A-DATA Technology                       | 4        | 2.9%    |
| Team                                    | 3        | 2.17%   |
| Unknown                                 | 3        | 2.17%   |
| Micron Technology                       | 2        | 1.45%   |
| Silicon Power Computer & Communications | 1        | 0.72%   |
| Ramaxel Technology                      | 1        | 0.72%   |
| Hewlett-Packard                         | 1        | 0.72%   |
| ASint Technology                        | 1        | 0.72%   |
| Apacer                                  | 1        | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Desktops | Percent |
|--------------------------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s                     | 6        | 3.95%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s                    | 4        | 2.63%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s                      | 3        | 1.97%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s                      | 3        | 1.97%   |
| Unknown                                                                  | 3        | 1.97%   |
| Unknown RAM Module 8GB DIMM 1333MT/s                                     | 2        | 1.32%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                     | 2        | 1.32%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                     | 2        | 1.32%   |
| Samsung RAM M378B5173EB0-CK0 4GB DIMM DDR3 1600MT/s                      | 2        | 1.32%   |
| Patriot RAM 2666 C16 Series 16GB DIMM DDR4 2800MT/s                      | 2        | 1.32%   |
| Patriot Memory (PDP Systems) RAM 3600 C18 Series 32GB DIMM DDR4 3600MT/s | 2        | 1.32%   |
| G.Skill RAM F4-3600C16-16GVKC 16GB DIMM DDR4 3866MT/s                    | 2        | 1.32%   |
| G.Skill RAM F4-3200C16-8GIS 8GB DIMM DDR4 3200MT/s                       | 2        | 1.32%   |
| Corsair RAM CMK32GX4M4B3200C16 8GB DIMM DDR4 3600MT/s                    | 2        | 1.32%   |
| Corsair RAM CMK16GX4M2D3600C18 8GB DIMM DDR4 3600MT/s                    | 2        | 1.32%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s                    | 2        | 1.32%   |
| Unknown RAM Module 8GB DIMM DDR3 1333MT/s                                | 1        | 0.66%   |
| Unknown RAM Module 8GB DIMM                                              | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                                     | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM 1066MT/s                                     | 1        | 0.66%   |
| Unknown RAM Module 4GB DIMM                                              | 1        | 0.66%   |
| Unknown RAM Module 2GB DIMM DDR2 1067MT/s                                | 1        | 0.66%   |
| Unknown RAM Module 1GB DIMM 1066MT/s                                     | 1        | 0.66%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s                       | 1        | 0.66%   |
| Unknown RAM 3000 C16 Series 8192MB DIMM DDR4 2133MT/s                    | 1        | 0.66%   |
| Team RAM TEAMGROUP-UD4-3200 8192MB DIMM DDR4 3733MT/s                    | 1        | 0.66%   |
| Team RAM TEAMGROUP-UD4-3200 16GB DIMM DDR4 3800MT/s                      | 1        | 0.66%   |
| Team RAM TEAMGROUP-UD4-3000 8GB DIMM DDR4 3200MT/s                       | 1        | 0.66%   |
| SK hynix RAM HMT451U6BFR8A-PB 4GB DIMM DDR3 1600MT/s                     | 1        | 0.66%   |
| SK hynix RAM HMT42GR7MFR4A-PB 16GB DIMM DDR3 1600MT/s                    | 1        | 0.66%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s                     | 1        | 0.66%   |
| SK hynix RAM HMT325U7CFR8C-PB 2GB DIMM DDR3 1600MT/s                     | 1        | 0.66%   |
| SK hynix RAM HMAA2GU6CJR8N-XN 16GB DIMM DDR4 3200MT/s                    | 1        | 0.66%   |
| SK hynix RAM HMA81GU6CJR8N-VK 8GB DIMM DDR4 2667MT/s                     | 1        | 0.66%   |
| Silicon Power & RAM Module 16GB DIMM DDR4 3200MT/s                       | 1        | 0.66%   |
| Silicon Power & RAM Module 16GB DIMM DDR4 2667MT/s                       | 1        | 0.66%   |
| Samsung RAM Module 8GB DIMM DDR4 2666MT/s                                | 1        | 0.66%   |
| Samsung RAM Module 8GB DIMM DDR4 2133MT/s                                | 1        | 0.66%   |
| Samsung RAM Module 16GB DIMM DDR4 3200MT/s                               | 1        | 0.66%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                    | 1        | 0.66%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 87       | 69.6%   |
| DDR3    | 22       | 17.6%   |
| DDR5    | 10       | 8%      |
| Unknown | 5        | 4%      |
| DDR2    | 1        | 0.8%    |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 119      | 95.2%   |
| SODIMM | 6        | 4.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 65       | 46.43%  |
| 16384 | 37       | 26.43%  |
| 4096  | 20       | 14.29%  |
| 32768 | 14       | 10%     |
| 2048  | 3        | 2.14%   |
| 1024  | 1        | 0.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Desktops | Percent |
|-------|----------|---------|
| 3600  | 25       | 17.86%  |
| 3200  | 20       | 14.29%  |
| 1600  | 13       | 9.29%   |
| 2400  | 7        | 5%      |
| 3666  | 5        | 3.57%   |
| 2667  | 5        | 3.57%   |
| 1333  | 5        | 3.57%   |
| 4800  | 4        | 2.86%   |
| 3533  | 4        | 2.86%   |
| 2933  | 4        | 2.86%   |
| 2666  | 4        | 2.86%   |
| 1800  | 4        | 2.86%   |
| 3733  | 3        | 2.14%   |
| 3000  | 3        | 2.14%   |
| 2800  | 3        | 2.14%   |
| 5600  | 2        | 1.43%   |
| 3866  | 2        | 1.43%   |
| 3800  | 2        | 1.43%   |
| 3466  | 2        | 1.43%   |
| 2133  | 2        | 1.43%   |
| 6400  | 1        | 0.71%   |
| 6000  | 1        | 0.71%   |
| 5808  | 1        | 0.71%   |
| 5200  | 1        | 0.71%   |
| 4266  | 1        | 0.71%   |
| 4200  | 1        | 0.71%   |
| 4000  | 1        | 0.71%   |
| 3534  | 1        | 0.71%   |
| 3400  | 1        | 0.71%   |
| 3266  | 1        | 0.71%   |
| 3151  | 1        | 0.71%   |
| 2200  | 1        | 0.71%   |
| 2000  | 1        | 0.71%   |
| 1867  | 1        | 0.71%   |
| 1866  | 1        | 0.71%   |
| 1648  | 1        | 0.71%   |
| 1200  | 1        | 0.71%   |
| 1067  | 1        | 0.71%   |
| 1066  | 1        | 0.71%   |
| 800   | 1        | 0.71%   |

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
| Logitech                      | 22       | 47.83%  |
| Microsoft                     | 6        | 13.04%  |
| Sunplus Innovation Technology | 4        | 8.7%    |
| Jieli Technology              | 3        | 6.52%   |
| Realtek Semiconductor         | 2        | 4.35%   |
| Generalplus Technology        | 2        | 4.35%   |
| Z-Star Microelectronics       | 1        | 2.17%   |
| Trust                         | 1        | 2.17%   |
| Razer USA                     | 1        | 2.17%   |
| Microdia                      | 1        | 2.17%   |
| MacroSilicon                  | 1        | 2.17%   |
| Creative Technology           | 1        | 2.17%   |
| Unknown                       | 1        | 2.17%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                      | Desktops | Percent |
|--------------------------------------------|----------|---------|
| Logitech Webcam C270                       | 4        | 8.7%    |
| Logitech BRIO Ultra HD Webcam              | 4        | 8.7%    |
| Logitech Webcam C930e                      | 3        | 6.52%   |
| Jieli USB PHY 2.0                          | 3        | 6.52%   |
| Sunplus AUSDOM FHD Camera                  | 2        | 4.35%   |
| Realtek Full HD webcam                     | 2        | 4.35%   |
| Microsoft LifeCam HD-5000                  | 2        | 4.35%   |
| Microsoft LifeCam HD-3000                  | 2        | 4.35%   |
| Logitech HD Webcam C910                    | 2        | 4.35%   |
| Logitech HD Pro Webcam C920                | 2        | 4.35%   |
| Logitech C922 Pro Stream Webcam            | 2        | 4.35%   |
| Z-Star A4 TECH USB2.0 PC Camera J          | 1        | 2.17%   |
| Trust Trust USB Camera                     | 1        | 2.17%   |
| Sunplus USB 2.0 Camera                     | 1        | 2.17%   |
| Sunplus Aukey-PC-LM1E Camera               | 1        | 2.17%   |
| Razer USA Razer Kiyo Pro                   | 1        | 2.17%   |
| Microsoft Xbox NUI Camera                  | 1        | 2.17%   |
| Microsoft LifeCam VX-2000                  | 1        | 2.17%   |
| Microdia Integrated Camera                 | 1        | 2.17%   |
| MacroSilicon USB Video                     | 1        | 2.17%   |
| Logitech Webcam C925e                      | 1        | 2.17%   |
| Logitech Webcam C310                       | 1        | 2.17%   |
| Logitech HD Webcam C510                    | 1        | 2.17%   |
| Logitech C920 PRO HD Webcam                | 1        | 2.17%   |
| Logitech Brio 500                          | 1        | 2.17%   |
| Generalplus WEB CAM                        | 1        | 2.17%   |
| Generalplus GENERAL WEBCAM                 | 1        | 2.17%   |
| Creative Live! Cam Chat HD [VF0700/VF0790] | 1        | 2.17%   |
| Unknown                                    | 1        | 2.17%   |

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
| 0     | 114      | 52.29%  |
| 1     | 92       | 42.2%   |
| 2     | 10       | 4.59%   |
| 3     | 2        | 0.92%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Communication controller | 87       | 73.73%  |
| Net/wireless             | 13       | 11.02%  |
| Graphics card            | 10       | 8.47%   |
| Unassigned class         | 3        | 2.54%   |
| Net/ethernet             | 3        | 2.54%   |
| Multimedia controller    | 1        | 0.85%   |
| Fingerprint reader       | 1        | 0.85%   |

