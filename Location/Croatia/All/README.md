Linux in Croatia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Croatia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Croatia/Desktop/README.md) and [notebooks](/Location/Croatia/Notebook/README.md).

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

Total: 1135

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-fc0xxx            | Notebook    | [28e81fb884](https://linux-hardware.org/?probe=28e81fb884) | Jan 03, 2026 |
| Unknown       | Unknown                     | Tablet      | [16dfa0f029](https://linux-hardware.org/?probe=16dfa0f029) | Jan 03, 2026 |
| HP            | ProBook 655 G1              | Notebook    | [428ad9e1da](https://linux-hardware.org/?probe=428ad9e1da) | Jan 02, 2026 |
| HP            | ProBook 655 G1              | Notebook    | [9d4441d7ff](https://linux-hardware.org/?probe=9d4441d7ff) | Jan 02, 2026 |
| ASUSTek       | PRIME Z890-P                | Desktop     | [c534bd7c2a](https://linux-hardware.org/?probe=c534bd7c2a) | Dec 27, 2025 |
| Toshiba       | TECRA S11                   | Notebook    | [5631c19be6](https://linux-hardware.org/?probe=5631c19be6) | Dec 23, 2025 |
| Lenovo        | G500 20236                  | Notebook    | [464de92bda](https://linux-hardware.org/?probe=464de92bda) | Dec 21, 2025 |
| MSI           | B450-A PRO MAX              | Desktop     | [4e0a622a8d](https://linux-hardware.org/?probe=4e0a622a8d) | Dec 20, 2025 |
| MSI           | GF65 Thin 9SEXR             | Notebook    | [a3bb634520](https://linux-hardware.org/?probe=a3bb634520) | Dec 17, 2025 |
| ASUSTek       | ASUS Vivobook 16 Flip TP... | Notebook    | [c60cbcb548](https://linux-hardware.org/?probe=c60cbcb548) | Dec 14, 2025 |
| RUNING        | X79 VB1.0                   | Desktop     | [3ec9d4080d](https://linux-hardware.org/?probe=3ec9d4080d) | Dec 12, 2025 |
| Acer          | Aspire ES1-521              | Notebook    | [bdebb56fa9](https://linux-hardware.org/?probe=bdebb56fa9) | Dec 09, 2025 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [679d7bdb80](https://linux-hardware.org/?probe=679d7bdb80) | Dec 08, 2025 |
| ASRock        | B650M-HDV/M.2               | Desktop     | [240a18463d](https://linux-hardware.org/?probe=240a18463d) | Dec 05, 2025 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [76bcf66e25](https://linux-hardware.org/?probe=76bcf66e25) | Dec 05, 2025 |
| Lenovo        | ThinkPad T480s 20L8S3P80... | Notebook    | [121d47e6e7](https://linux-hardware.org/?probe=121d47e6e7) | Dec 04, 2025 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [e5f5a808d2](https://linux-hardware.org/?probe=e5f5a808d2) | Dec 03, 2025 |
| ASRock        | H610M-HDV/M.2               | Desktop     | [61c2456b61](https://linux-hardware.org/?probe=61c2456b61) | Nov 28, 2025 |
| ASUSTek       | ROG Flow X13 GV301QC_GV3... | Notebook    | [547bd6281f](https://linux-hardware.org/?probe=547bd6281f) | Nov 25, 2025 |
| HP            | 18E7                        | Desktop     | [7fa8cd3ff6](https://linux-hardware.org/?probe=7fa8cd3ff6) | Nov 24, 2025 |
| HP            | 18E7                        | Desktop     | [6380da5baa](https://linux-hardware.org/?probe=6380da5baa) | Nov 24, 2025 |
| Dell          | Latitude E5550              | Notebook    | [688c316fc7](https://linux-hardware.org/?probe=688c316fc7) | Nov 22, 2025 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [f8720bcde3](https://linux-hardware.org/?probe=f8720bcde3) | Nov 16, 2025 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [59759f1ca8](https://linux-hardware.org/?probe=59759f1ca8) | Nov 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [9bf2d8b88d](https://linux-hardware.org/?probe=9bf2d8b88d) | Nov 15, 2025 |
| Gigabyte      | H77M-D3H                    | Desktop     | [5835eaf267](https://linux-hardware.org/?probe=5835eaf267) | Nov 14, 2025 |
| Gigabyte      | H77M-D3H                    | Desktop     | [79fa61f75c](https://linux-hardware.org/?probe=79fa61f75c) | Nov 14, 2025 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [da42036c62](https://linux-hardware.org/?probe=da42036c62) | Nov 11, 2025 |
| Dell          | G15 5530                    | Notebook    | [bdca3b23a6](https://linux-hardware.org/?probe=bdca3b23a6) | Nov 08, 2025 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [17c5b06ce7](https://linux-hardware.org/?probe=17c5b06ce7) | Nov 04, 2025 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [96a1529b22](https://linux-hardware.org/?probe=96a1529b22) | Nov 03, 2025 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [9abaa367d7](https://linux-hardware.org/?probe=9abaa367d7) | Nov 02, 2025 |
| Shenzhen M... | AHBNB OEM                   | Desktop     | [6b8c6e82a4](https://linux-hardware.org/?probe=6b8c6e82a4) | Nov 02, 2025 |
| Acer          | Aspire A517-51G             | Notebook    | [cb291106fe](https://linux-hardware.org/?probe=cb291106fe) | Nov 01, 2025 |
| GEEKOM        | A8                          | Desktop     | [1c879653f0](https://linux-hardware.org/?probe=1c879653f0) | Nov 01, 2025 |
| Dell          | G15 5530                    | Notebook    | [88a391c4d8](https://linux-hardware.org/?probe=88a391c4d8) | Oct 26, 2025 |
| ASUSTek       | Vivobook Go E1504GA_E150... | Notebook    | [2f67add42c](https://linux-hardware.org/?probe=2f67add42c) | Oct 22, 2025 |
| Acer          | Aspire E5-771G              | Notebook    | [aba0e77630](https://linux-hardware.org/?probe=aba0e77630) | Oct 21, 2025 |
| ASUSTek       | Vivobook Go E1504GA_E150... | Notebook    | [c0f5c9b6f0](https://linux-hardware.org/?probe=c0f5c9b6f0) | Oct 20, 2025 |
| Unknown       | ECOBOOK                     | Notebook    | [b788d5ae83](https://linux-hardware.org/?probe=b788d5ae83) | Oct 20, 2025 |
| Acer          | Aspire E5-771G              | Notebook    | [b30a98d526](https://linux-hardware.org/?probe=b30a98d526) | Oct 16, 2025 |
| Gigabyte      | 970A-UD3P                   | Desktop     | [86ea95eba1](https://linux-hardware.org/?probe=86ea95eba1) | Oct 12, 2025 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [2ce6a5ea90](https://linux-hardware.org/?probe=2ce6a5ea90) | Oct 09, 2025 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [486fbc4bb6](https://linux-hardware.org/?probe=486fbc4bb6) | Oct 01, 2025 |
| Timi          | TM1701                      | Notebook    | [616de6383b](https://linux-hardware.org/?probe=616de6383b) | Sep 25, 2025 |
| Unknown       | Unknown                     | Notebook    | [3c9e8fc339](https://linux-hardware.org/?probe=3c9e8fc339) | Sep 22, 2025 |
| Unknown       | Unknown                     | Notebook    | [a8e6ab6d44](https://linux-hardware.org/?probe=a8e6ab6d44) | Sep 22, 2025 |
| Lenovo        | Legion Go 8APU1 83E1        | Tablet      | [c488f32b5e](https://linux-hardware.org/?probe=c488f32b5e) | Sep 21, 2025 |
| Acer          | Aspire A15-41M              | Notebook    | [02b7426e3c](https://linux-hardware.org/?probe=02b7426e3c) | Sep 18, 2025 |
| GARAGE        | 775i65G                     | Desktop     | [5ff35e7037](https://linux-hardware.org/?probe=5ff35e7037) | Sep 17, 2025 |
| Lenovo        | 3141 SDK0J40697 WIN 3305... | Desktop     | [cf1ccb412f](https://linux-hardware.org/?probe=cf1ccb412f) | Sep 12, 2025 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [e76d1fb91b](https://linux-hardware.org/?probe=e76d1fb91b) | Sep 09, 2025 |
| ASUSTek       | K55A                        | Notebook    | [d5b5b40327](https://linux-hardware.org/?probe=d5b5b40327) | Aug 27, 2025 |
| ASRock        | B450M Pro4                  | Desktop     | [b524e7fcfe](https://linux-hardware.org/?probe=b524e7fcfe) | Aug 25, 2025 |
| Acer          | Predator PT516-52s          | Notebook    | [5e1d51a39a](https://linux-hardware.org/?probe=5e1d51a39a) | Aug 19, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | Notebook    | [fc6ce730ce](https://linux-hardware.org/?probe=fc6ce730ce) | Aug 15, 2025 |
| Lenovo        | ThinkPad T480 20L6S69B00    | Notebook    | [719b9e8ea8](https://linux-hardware.org/?probe=719b9e8ea8) | Aug 13, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | Notebook    | [831a1ebf42](https://linux-hardware.org/?probe=831a1ebf42) | Aug 13, 2025 |
| Sony          | VPCEH23FD                   | Notebook    | [0aad348b94](https://linux-hardware.org/?probe=0aad348b94) | Aug 11, 2025 |
| HP            | ENVY dv7                    | Notebook    | [fed54497a7](https://linux-hardware.org/?probe=fed54497a7) | Aug 08, 2025 |
| Lenovo        | LOQ 15IRX9 83DV             | Notebook    | [9300462356](https://linux-hardware.org/?probe=9300462356) | Aug 06, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | Notebook    | [1eaebda75c](https://linux-hardware.org/?probe=1eaebda75c) | Jul 30, 2025 |
| MSI           | H61M-P20                    | Desktop     | [f77e708e7b](https://linux-hardware.org/?probe=f77e708e7b) | Jul 29, 2025 |
| Dell          | OptiPlex 9020               | Notebook    | [4b5d8462c2](https://linux-hardware.org/?probe=4b5d8462c2) | Jul 20, 2025 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [8c401a9e1b](https://linux-hardware.org/?probe=8c401a9e1b) | Jul 20, 2025 |
| Dell          | Inspiron 3542               | Notebook    | [ee61709e71](https://linux-hardware.org/?probe=ee61709e71) | Jul 13, 2025 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [f83db78e6c](https://linux-hardware.org/?probe=f83db78e6c) | Jul 10, 2025 |
| Dell          | OptiPlex 9020               | Notebook    | [57e5af17b8](https://linux-hardware.org/?probe=57e5af17b8) | Jul 08, 2025 |
| Dell          | OptiPlex 9020               | Notebook    | [84688234aa](https://linux-hardware.org/?probe=84688234aa) | Jul 08, 2025 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [2d1183d668](https://linux-hardware.org/?probe=2d1183d668) | Jul 05, 2025 |
| Lenovo        | ThinkBook 16 G7+ IAH 21T... | Notebook    | [e568a33b01](https://linux-hardware.org/?probe=e568a33b01) | Jul 05, 2025 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [f6c7ce8af4](https://linux-hardware.org/?probe=f6c7ce8af4) | Jul 02, 2025 |
| Lenovo        | ThinkBook 16 G7+ IAH 21T... | Notebook    | [581b9195fd](https://linux-hardware.org/?probe=581b9195fd) | Jul 01, 2025 |
| Dell          | Inspiron 3542               | Notebook    | [0d62a30868](https://linux-hardware.org/?probe=0d62a30868) | Jun 29, 2025 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [5b6c034818](https://linux-hardware.org/?probe=5b6c034818) | Jun 25, 2025 |
| ASUSTek       | X540LJ                      | Notebook    | [5cd896f0ab](https://linux-hardware.org/?probe=5cd896f0ab) | Jun 24, 2025 |
| Acer          | Aspire V5-552G              | Notebook    | [526f0fa238](https://linux-hardware.org/?probe=526f0fa238) | Jun 21, 2025 |
| ASUSTek       | PRIME B840M-A WIFI          | Desktop     | [f6514e8750](https://linux-hardware.org/?probe=f6514e8750) | Jun 19, 2025 |
| Gigabyte      | Z370 AORUS Gaming K3-CF     | Desktop     | [1be7f7ed63](https://linux-hardware.org/?probe=1be7f7ed63) | Jun 17, 2025 |
| Lenovo        | ThinkPad T450s 20BWS0FU0... | Notebook    | [e9d9c9770c](https://linux-hardware.org/?probe=e9d9c9770c) | Jun 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | Notebook    | [a8898ab757](https://linux-hardware.org/?probe=a8898ab757) | Jun 10, 2025 |
| ASUSTek       | Z170-A                      | Desktop     | [ab7acfc669](https://linux-hardware.org/?probe=ab7acfc669) | Jun 06, 2025 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [942b0df642](https://linux-hardware.org/?probe=942b0df642) | Jun 01, 2025 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [5a0112d369](https://linux-hardware.org/?probe=5a0112d369) | Jun 01, 2025 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [f64017876b](https://linux-hardware.org/?probe=f64017876b) | May 30, 2025 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [002b313a0c](https://linux-hardware.org/?probe=002b313a0c) | May 29, 2025 |
| MSI           | X79A-GD45 Plus              | Desktop     | [cf9f503e11](https://linux-hardware.org/?probe=cf9f503e11) | May 29, 2025 |
| ASUSTek       | PRIME B840M-A WIFI          | Desktop     | [a79556481f](https://linux-hardware.org/?probe=a79556481f) | May 27, 2025 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [53cf53c8dc](https://linux-hardware.org/?probe=53cf53c8dc) | May 23, 2025 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [96808f6802](https://linux-hardware.org/?probe=96808f6802) | May 22, 2025 |
| Toshiba       | Satellite C855-1TV          | Notebook    | [a3b81b03d0](https://linux-hardware.org/?probe=a3b81b03d0) | May 17, 2025 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [db7d498538](https://linux-hardware.org/?probe=db7d498538) | May 16, 2025 |
| Gigabyte      | B450 GAMING X               | Desktop     | [b2d0d0f17a](https://linux-hardware.org/?probe=b2d0d0f17a) | May 15, 2025 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [47eed7059c](https://linux-hardware.org/?probe=47eed7059c) | May 10, 2025 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [277381e0f4](https://linux-hardware.org/?probe=277381e0f4) | May 09, 2025 |
| TUXEDO        | InfinityBook Pro AMD Gen... | Notebook    | [358fb97668](https://linux-hardware.org/?probe=358fb97668) | May 03, 2025 |
| ASRock        | B650M Pro RS                | Desktop     | [929c1e925a](https://linux-hardware.org/?probe=929c1e925a) | May 02, 2025 |
| ASUSTek       | ASUS Zenbook 14 UM3406HA... | Notebook    | [eb54d35bf2](https://linux-hardware.org/?probe=eb54d35bf2) | May 01, 2025 |
| ASUSTek       | ASUS Zenbook 14 UM3406HA... | Notebook    | [1f32cf1a98](https://linux-hardware.org/?probe=1f32cf1a98) | May 01, 2025 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [96b21224c6](https://linux-hardware.org/?probe=96b21224c6) | May 01, 2025 |
| Lenovo        | ThinkPad X390 Yoga 20NQS... | Convertible | [58ad017c58](https://linux-hardware.org/?probe=58ad017c58) | May 01, 2025 |
| HP            | ZBook Ultra G1a 14 inch ... | Notebook    | [cb519eccae](https://linux-hardware.org/?probe=cb519eccae) | Apr 30, 2025 |
| TUXEDO        | InfinityBook Pro AMD Gen... | Notebook    | [6f88c8bbd7](https://linux-hardware.org/?probe=6f88c8bbd7) | Apr 30, 2025 |
| Lenovo        | ThinkPad R61 8932AFG        | Notebook    | [c632fab9cd](https://linux-hardware.org/?probe=c632fab9cd) | Apr 25, 2025 |
| TUXEDO        | InfinityBook Pro AMD Gen... | Notebook    | [611ac358ed](https://linux-hardware.org/?probe=611ac358ed) | Apr 25, 2025 |
| MSI           | PRO B650-A WIFI             | Desktop     | [905fc52a67](https://linux-hardware.org/?probe=905fc52a67) | Apr 23, 2025 |
| Gigabyte      | B650M D3HP                  | Desktop     | [c4215927cd](https://linux-hardware.org/?probe=c4215927cd) | Apr 23, 2025 |
| Acer          | Aspire 3810TZ               | Notebook    | [5908d969c4](https://linux-hardware.org/?probe=5908d969c4) | Apr 23, 2025 |
| Dell          | Vostro 15 3510              | Notebook    | [909b7d2338](https://linux-hardware.org/?probe=909b7d2338) | Apr 22, 2025 |
| Gigabyte      | AB350M-Gaming 3-CF          | Desktop     | [c91410327a](https://linux-hardware.org/?probe=c91410327a) | Apr 18, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | Notebook    | [74eb28f103](https://linux-hardware.org/?probe=74eb28f103) | Apr 18, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | Notebook    | [d5848bec92](https://linux-hardware.org/?probe=d5848bec92) | Apr 17, 2025 |
| ASUSTek       | B75M-A                      | Desktop     | [c517058f1f](https://linux-hardware.org/?probe=c517058f1f) | Apr 14, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | Notebook    | [61f7a508c0](https://linux-hardware.org/?probe=61f7a508c0) | Apr 14, 2025 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [094fd397ef](https://linux-hardware.org/?probe=094fd397ef) | Apr 13, 2025 |
| Lenovo        | ThinkBook 16 G7 ARP 21MW    | Notebook    | [cae33b591e](https://linux-hardware.org/?probe=cae33b591e) | Apr 11, 2025 |
| Acer          | Swift SF314-43              | Notebook    | [b022cb2226](https://linux-hardware.org/?probe=b022cb2226) | Apr 11, 2025 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c34096a43d](https://linux-hardware.org/?probe=c34096a43d) | Apr 10, 2025 |
| ASUSTek       | PRIME B560M-A               | Notebook    | [1a0de9c56d](https://linux-hardware.org/?probe=1a0de9c56d) | Apr 09, 2025 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [0a8c9e7f90](https://linux-hardware.org/?probe=0a8c9e7f90) | Apr 09, 2025 |
| HP            | EliteBook 8470p             | Notebook    | [b9b0897548](https://linux-hardware.org/?probe=b9b0897548) | Apr 07, 2025 |
| Dell          | Vostro 15 3510              | Notebook    | [9206bf9f56](https://linux-hardware.org/?probe=9206bf9f56) | Apr 05, 2025 |
| Gigabyte      | B550M DS3H                  | Desktop     | [714b80920c](https://linux-hardware.org/?probe=714b80920c) | Apr 05, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [23a7e30d1b](https://linux-hardware.org/?probe=23a7e30d1b) | Mar 30, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [f380989589](https://linux-hardware.org/?probe=f380989589) | Mar 29, 2025 |
| Acer          | Aspire A315-59              | Notebook    | [92a3c2a7ac](https://linux-hardware.org/?probe=92a3c2a7ac) | Mar 27, 2025 |
| ASRock        | B650M-HDV/M.2               | Desktop     | [a55911ac71](https://linux-hardware.org/?probe=a55911ac71) | Mar 26, 2025 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [605e61f244](https://linux-hardware.org/?probe=605e61f244) | Mar 22, 2025 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | Notebook    | [d828c40581](https://linux-hardware.org/?probe=d828c40581) | Mar 22, 2025 |
| ASRock        | B560 Steel Legend           | Desktop     | [23fb9edc5a](https://linux-hardware.org/?probe=23fb9edc5a) | Mar 21, 2025 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [5d9bda93a0](https://linux-hardware.org/?probe=5d9bda93a0) | Mar 16, 2025 |
| ASUSTek       | P5KC                        | Desktop     | [d576625cd4](https://linux-hardware.org/?probe=d576625cd4) | Mar 16, 2025 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [456198d342](https://linux-hardware.org/?probe=456198d342) | Mar 15, 2025 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [a768ed4646](https://linux-hardware.org/?probe=a768ed4646) | Mar 15, 2025 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [a970826785](https://linux-hardware.org/?probe=a970826785) | Mar 15, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [c699c95bf9](https://linux-hardware.org/?probe=c699c95bf9) | Mar 11, 2025 |
| Lenovo        | ThinkBook 16 G7 IML 21MS    | Notebook    | [ace6a8b8c9](https://linux-hardware.org/?probe=ace6a8b8c9) | Mar 10, 2025 |
| MSI           | Katana GF66 12UDO           | Notebook    | [4221ffde63](https://linux-hardware.org/?probe=4221ffde63) | Mar 08, 2025 |
| Gigabyte      | B550M DS3H                  | Desktop     | [b99f2487da](https://linux-hardware.org/?probe=b99f2487da) | Mar 02, 2025 |
| GARAGE        | 775i65G                     | Desktop     | [0d16cd7346](https://linux-hardware.org/?probe=0d16cd7346) | Mar 02, 2025 |
| HP            | ProBook 460 16 inch G11 ... | Notebook    | [32403e5558](https://linux-hardware.org/?probe=32403e5558) | Feb 26, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [2ae126e7a3](https://linux-hardware.org/?probe=2ae126e7a3) | Feb 19, 2025 |
| Lenovo        | Legion 5 15IMH6 82NL        | Notebook    | [627d3a0243](https://linux-hardware.org/?probe=627d3a0243) | Feb 16, 2025 |
| HP            | ProBook 460 16 inch G11 ... | Notebook    | [d1951d78ea](https://linux-hardware.org/?probe=d1951d78ea) | Feb 14, 2025 |
| HP            | 8055                        | Desktop     | [7ef369214e](https://linux-hardware.org/?probe=7ef369214e) | Feb 14, 2025 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [b9c98d07c9](https://linux-hardware.org/?probe=b9c98d07c9) | Feb 11, 2025 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [03ab3d58cb](https://linux-hardware.org/?probe=03ab3d58cb) | Feb 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [0c7a85df31](https://linux-hardware.org/?probe=0c7a85df31) | Feb 07, 2025 |
| Lenovo        | ThinkPad SL510 28476LG      | Notebook    | [ff2ac07aef](https://linux-hardware.org/?probe=ff2ac07aef) | Feb 06, 2025 |
| Lenovo        | ThinkPad Edge E125 30352... | Notebook    | [3c0f91ef83](https://linux-hardware.org/?probe=3c0f91ef83) | Feb 06, 2025 |
| HP            | Compaq 8510w                | Notebook    | [4f070686c1](https://linux-hardware.org/?probe=4f070686c1) | Feb 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | Notebook    | [11a7f61b8e](https://linux-hardware.org/?probe=11a7f61b8e) | Feb 06, 2025 |
| HP            | EliteBook 840 G6            | Notebook    | [ccc1e250a7](https://linux-hardware.org/?probe=ccc1e250a7) | Feb 04, 2025 |
| Lenovo        | ThinkPad E16 Gen 2 21M50... | Notebook    | [3a144b039c](https://linux-hardware.org/?probe=3a144b039c) | Feb 02, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | Notebook    | [5036c74dce](https://linux-hardware.org/?probe=5036c74dce) | Feb 01, 2025 |
| ASRock        | 880G Extreme3               | Desktop     | [533616e811](https://linux-hardware.org/?probe=533616e811) | Jan 29, 2025 |
| Fujitsu       | D3501-A1 S26361-D3501-A1    | Desktop     | [70479fdb19](https://linux-hardware.org/?probe=70479fdb19) | Jan 29, 2025 |
| TUXEDO        | InfinityBook Pro AMD Gen... | Notebook    | [d2c650b264](https://linux-hardware.org/?probe=d2c650b264) | Jan 28, 2025 |
| ASRock        | 880G Extreme3               | Desktop     | [d37def4689](https://linux-hardware.org/?probe=d37def4689) | Jan 27, 2025 |
| Gigabyte      | G5 KF5                      | Notebook    | [942f8a4126](https://linux-hardware.org/?probe=942f8a4126) | Jan 27, 2025 |
| Lenovo        | ThinkPad T580 20LAS5BQ00    | Notebook    | [c3993d3bc3](https://linux-hardware.org/?probe=c3993d3bc3) | Jan 25, 2025 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [8f3d9a7482](https://linux-hardware.org/?probe=8f3d9a7482) | Jan 24, 2025 |
| Toshiba       | Satellite L655              | Notebook    | [ad37b67f87](https://linux-hardware.org/?probe=ad37b67f87) | Jan 24, 2025 |
| HP            | ZBook 17                    | Notebook    | [fb0cd98066](https://linux-hardware.org/?probe=fb0cd98066) | Jan 24, 2025 |
| ASUSTek       | Z97M-PLUS                   | Desktop     | [dfd173b83d](https://linux-hardware.org/?probe=dfd173b83d) | Jan 21, 2025 |
| Gigabyte      | MFLP7IP-00                  | Desktop     | [744d15cd68](https://linux-hardware.org/?probe=744d15cd68) | Jan 19, 2025 |
| BESSTAR Te... | UM350                       | Desktop     | [4a64dc33c3](https://linux-hardware.org/?probe=4a64dc33c3) | Jan 18, 2025 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [975a1199f7](https://linux-hardware.org/?probe=975a1199f7) | Jan 17, 2025 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | Notebook    | [1463c39f38](https://linux-hardware.org/?probe=1463c39f38) | Jan 17, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | Notebook    | [d0fe08663c](https://linux-hardware.org/?probe=d0fe08663c) | Jan 14, 2025 |
| Lenovo        | ThinkPad T480 20L6S7SG02    | Notebook    | [09b32b0543](https://linux-hardware.org/?probe=09b32b0543) | Jan 13, 2025 |
| Tactus        | GeoBook 140                 | Notebook    | [3f98d02202](https://linux-hardware.org/?probe=3f98d02202) | Jan 12, 2025 |
| ASRock        | A320M-HDV                   | Desktop     | [01c2e4a226](https://linux-hardware.org/?probe=01c2e4a226) | Jan 12, 2025 |
| Tactus        | GeoBook 140                 | Notebook    | [ac69ce3b3b](https://linux-hardware.org/?probe=ac69ce3b3b) | Jan 11, 2025 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [f6e6f6add7](https://linux-hardware.org/?probe=f6e6f6add7) | Jan 10, 2025 |
| HP            | ProBook 650 G4              | Notebook    | [60151c3e89](https://linux-hardware.org/?probe=60151c3e89) | Jan 10, 2025 |
| HP            | ProBook 650 G4              | Notebook    | [960f70006c](https://linux-hardware.org/?probe=960f70006c) | Jan 10, 2025 |
| Gigabyte      | Z370 AORUS Gaming 7         | Desktop     | [47ce7960b6](https://linux-hardware.org/?probe=47ce7960b6) | Jan 09, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | Notebook    | [54bbb73376](https://linux-hardware.org/?probe=54bbb73376) | Jan 08, 2025 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [605d405a35](https://linux-hardware.org/?probe=605d405a35) | Jan 07, 2025 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | Notebook    | [4fc43ed5a9](https://linux-hardware.org/?probe=4fc43ed5a9) | Jan 04, 2025 |
| ASRock        | H510M-HDV/M.2 SE            | Desktop     | [cd15dad76b](https://linux-hardware.org/?probe=cd15dad76b) | Jan 02, 2025 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [b71ec4b1e6](https://linux-hardware.org/?probe=b71ec4b1e6) | Dec 31, 2024 |
| HP            | 1495                        | Desktop     | [f9588cf3eb](https://linux-hardware.org/?probe=f9588cf3eb) | Dec 30, 2024 |
| Lenovo        | G585 20137                  | Notebook    | [cfbfe12819](https://linux-hardware.org/?probe=cfbfe12819) | Dec 30, 2024 |
| MSI           | Katana GF76 12UEOK          | Notebook    | [a3467015fd](https://linux-hardware.org/?probe=a3467015fd) | Dec 26, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [01c866bd0e](https://linux-hardware.org/?probe=01c866bd0e) | Dec 21, 2024 |
| ASRock        | B650M PG Lightning          | Desktop     | [93343b543c](https://linux-hardware.org/?probe=93343b543c) | Dec 16, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [edc19c7235](https://linux-hardware.org/?probe=edc19c7235) | Dec 15, 2024 |
| Gigabyte      | H97M-HD3                    | Desktop     | [0e0965bc17](https://linux-hardware.org/?probe=0e0965bc17) | Dec 15, 2024 |
| HP            | EliteBook x360 830 G6       | Convertible | [0b88dbaf17](https://linux-hardware.org/?probe=0b88dbaf17) | Dec 15, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [d557fc1733](https://linux-hardware.org/?probe=d557fc1733) | Dec 14, 2024 |
| Gigabyte      | Z390 GAMING X-CF            | Desktop     | [c43094abf1](https://linux-hardware.org/?probe=c43094abf1) | Dec 14, 2024 |
| Lenovo        | ThinkPad X395 20NL000HMH    | Notebook    | [2d86c3a6a1](https://linux-hardware.org/?probe=2d86c3a6a1) | Dec 14, 2024 |
| ASRock        | B250M-HDV                   | Desktop     | [feade65edb](https://linux-hardware.org/?probe=feade65edb) | Dec 13, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [8fd0a47047](https://linux-hardware.org/?probe=8fd0a47047) | Dec 13, 2024 |
| Dell          | Inspiron 3501               | Notebook    | [6d66838249](https://linux-hardware.org/?probe=6d66838249) | Dec 13, 2024 |
| ASRock        | B650M PG Lightning          | Desktop     | [4370a5ccdf](https://linux-hardware.org/?probe=4370a5ccdf) | Dec 11, 2024 |
| HP            | EliteBook 2170p             | Notebook    | [39de9fd95f](https://linux-hardware.org/?probe=39de9fd95f) | Dec 04, 2024 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [c2162b5ffe](https://linux-hardware.org/?probe=c2162b5ffe) | Nov 30, 2024 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [1997f45737](https://linux-hardware.org/?probe=1997f45737) | Nov 28, 2024 |
| HP            | 81C5 MVB                    | Desktop     | [18206773c5](https://linux-hardware.org/?probe=18206773c5) | Nov 24, 2024 |
| Lenovo        | ThinkPad X13 Yoga Gen 2 ... | Convertible | [c2f43e33c0](https://linux-hardware.org/?probe=c2f43e33c0) | Nov 23, 2024 |
| Schenker      | XMG EVO (M24)               | Notebook    | [605df9f69c](https://linux-hardware.org/?probe=605df9f69c) | Nov 22, 2024 |
| Schenker      | XMG EVO (M24)               | Notebook    | [dd1c282bdb](https://linux-hardware.org/?probe=dd1c282bdb) | Nov 22, 2024 |
| Lenovo        | 3000 N200 0769BLG           | Notebook    | [d58726bb7b](https://linux-hardware.org/?probe=d58726bb7b) | Nov 18, 2024 |
| Lenovo        | 3000 N200 0769BLG           | Notebook    | [60ef264f93](https://linux-hardware.org/?probe=60ef264f93) | Nov 16, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [e88d7b46ce](https://linux-hardware.org/?probe=e88d7b46ce) | Nov 12, 2024 |
| MSI           | GP66 Leopard 10UG           | Notebook    | [5ab759967a](https://linux-hardware.org/?probe=5ab759967a) | Nov 08, 2024 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [efffc4e893](https://linux-hardware.org/?probe=efffc4e893) | Nov 05, 2024 |
| Acer          | Aspire E5-571G              | Notebook    | [77228343b8](https://linux-hardware.org/?probe=77228343b8) | Nov 04, 2024 |
| Acer          | Aspire E5-571G              | Notebook    | [c3f4b3765a](https://linux-hardware.org/?probe=c3f4b3765a) | Nov 04, 2024 |
| HP            | 620                         | Notebook    | [62a5cced4d](https://linux-hardware.org/?probe=62a5cced4d) | Nov 03, 2024 |
| HP            | 3048h                       | Desktop     | [8984b9b0ff](https://linux-hardware.org/?probe=8984b9b0ff) | Oct 31, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [6ea530d4cf](https://linux-hardware.org/?probe=6ea530d4cf) | Oct 29, 2024 |
| Lenovo        | IdeaPad 3 17IAU7 82RL       | Notebook    | [2de5d8141c](https://linux-hardware.org/?probe=2de5d8141c) | Oct 29, 2024 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [b784a172f1](https://linux-hardware.org/?probe=b784a172f1) | Oct 29, 2024 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [b832baec89](https://linux-hardware.org/?probe=b832baec89) | Oct 29, 2024 |
| HP            | 1495                        | Desktop     | [2fd3ea9199](https://linux-hardware.org/?probe=2fd3ea9199) | Oct 25, 2024 |
| ASRock        | H510M-HDV/M.2 SE            | Desktop     | [632d66a3f3](https://linux-hardware.org/?probe=632d66a3f3) | Oct 23, 2024 |
| Apple         | MacBookAir5,2               | Notebook    | [7b9ad509e7](https://linux-hardware.org/?probe=7b9ad509e7) | Oct 21, 2024 |
| Acer          | Aspire E1-522               | Notebook    | [5e76308cf8](https://linux-hardware.org/?probe=5e76308cf8) | Oct 21, 2024 |
| ASUSTek       | X556UQ                      | Notebook    | [046fdf8e88](https://linux-hardware.org/?probe=046fdf8e88) | Oct 19, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [abab79db3c](https://linux-hardware.org/?probe=abab79db3c) | Oct 19, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [fab35a6539](https://linux-hardware.org/?probe=fab35a6539) | Oct 19, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [b6c163527d](https://linux-hardware.org/?probe=b6c163527d) | Oct 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | Notebook    | [a3e77b53eb](https://linux-hardware.org/?probe=a3e77b53eb) | Oct 16, 2024 |
| ASRock        | A620M-HDV/M.2               | Desktop     | [2f77fd05f6](https://linux-hardware.org/?probe=2f77fd05f6) | Oct 15, 2024 |
| Lenovo        | ThinkPad T460 20FN003LGE    | Notebook    | [2ab3d1b003](https://linux-hardware.org/?probe=2ab3d1b003) | Oct 13, 2024 |
| Apple         | Mac-F2268DAE                | All in one  | [9834ff54d1](https://linux-hardware.org/?probe=9834ff54d1) | Oct 11, 2024 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [fae42cf78a](https://linux-hardware.org/?probe=fae42cf78a) | Oct 08, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [bb1321ebd2](https://linux-hardware.org/?probe=bb1321ebd2) | Oct 05, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [3f906c01d2](https://linux-hardware.org/?probe=3f906c01d2) | Oct 05, 2024 |
| eMachines     | E725 V1.03                  | Notebook    | [4a9590683e](https://linux-hardware.org/?probe=4a9590683e) | Oct 03, 2024 |
| EMC           | 110-335-541B-04 FFF         | Desktop     | [a45ce6a612](https://linux-hardware.org/?probe=a45ce6a612) | Oct 01, 2024 |
| ASUSTek       | E402SA                      | Notebook    | [05b9b51859](https://linux-hardware.org/?probe=05b9b51859) | Sep 28, 2024 |
| Acer          | Aspire A515-57              | Notebook    | [5bb85acaa8](https://linux-hardware.org/?probe=5bb85acaa8) | Sep 25, 2024 |
| HP            | EliteBook 640 14 inch G1... | Notebook    | [1a56c410de](https://linux-hardware.org/?probe=1a56c410de) | Sep 24, 2024 |
| Gigabyte      | A620M S2H                   | Desktop     | [125f5a8d74](https://linux-hardware.org/?probe=125f5a8d74) | Sep 10, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [b2bda3297a](https://linux-hardware.org/?probe=b2bda3297a) | Sep 09, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [97578fa017](https://linux-hardware.org/?probe=97578fa017) | Sep 09, 2024 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [7ab4f22e0a](https://linux-hardware.org/?probe=7ab4f22e0a) | Sep 08, 2024 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | Notebook    | [b200161c65](https://linux-hardware.org/?probe=b200161c65) | Sep 08, 2024 |
| Toshiba       | Satellite C850-1GD          | Notebook    | [e88a301000](https://linux-hardware.org/?probe=e88a301000) | Sep 06, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [1e5012faa8](https://linux-hardware.org/?probe=1e5012faa8) | Sep 05, 2024 |
| Toshiba       | Satellite C850-1GD          | Notebook    | [c3fdc37622](https://linux-hardware.org/?probe=c3fdc37622) | Sep 04, 2024 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [03c509b9db](https://linux-hardware.org/?probe=03c509b9db) | Sep 02, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [95c264530c](https://linux-hardware.org/?probe=95c264530c) | Aug 29, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [8a2e220edd](https://linux-hardware.org/?probe=8a2e220edd) | Aug 26, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [18c81a5d40](https://linux-hardware.org/?probe=18c81a5d40) | Aug 24, 2024 |
| HP            | Compaq 6730s                | Notebook    | [5477f5c6aa](https://linux-hardware.org/?probe=5477f5c6aa) | Aug 20, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [30973be0c7](https://linux-hardware.org/?probe=30973be0c7) | Aug 19, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | Notebook    | [6d5345fe36](https://linux-hardware.org/?probe=6d5345fe36) | Aug 19, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6ef48298ce](https://linux-hardware.org/?probe=6ef48298ce) | Aug 13, 2024 |
| ASRock        | H510M-HDV/M.2 SE            | Desktop     | [b2182890a9](https://linux-hardware.org/?probe=b2182890a9) | Aug 09, 2024 |
| ASUSTek       | ASUS EXPERTBOOK B3302FEA... | Convertible | [231e53d96d](https://linux-hardware.org/?probe=231e53d96d) | Aug 05, 2024 |
| ASRock        | H97 Anniversary             | Desktop     | [ec56437f32](https://linux-hardware.org/?probe=ec56437f32) | Jul 31, 2024 |
| ASRock        | B560 Steel Legend           | Desktop     | [d3002dc7c2](https://linux-hardware.org/?probe=d3002dc7c2) | Jul 29, 2024 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [a44c4ca6c4](https://linux-hardware.org/?probe=a44c4ca6c4) | Jul 26, 2024 |
| MAXSUN        | MS-TZZ B560M                | Desktop     | [cca7e1333d](https://linux-hardware.org/?probe=cca7e1333d) | Jul 23, 2024 |
| HP            | 18E4                        | Desktop     | [bcfb2d82b4](https://linux-hardware.org/?probe=bcfb2d82b4) | Jul 20, 2024 |
| Acer          | Aspire 3810TZ               | Notebook    | [8a845f0a93](https://linux-hardware.org/?probe=8a845f0a93) | Jul 13, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [6e6ba41a40](https://linux-hardware.org/?probe=6e6ba41a40) | Jul 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [e9fa4e7bea](https://linux-hardware.org/?probe=e9fa4e7bea) | Jul 09, 2024 |
| Acer          | Swift SFG14-42              | Notebook    | [3623aaf512](https://linux-hardware.org/?probe=3623aaf512) | Jul 05, 2024 |
| ASRock        | B650 PG Lightning           | Desktop     | [69f46fe2a1](https://linux-hardware.org/?probe=69f46fe2a1) | Jul 04, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [7ede8c3d44](https://linux-hardware.org/?probe=7ede8c3d44) | Jul 04, 2024 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [553f4c84c7](https://linux-hardware.org/?probe=553f4c84c7) | Jul 02, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | Notebook    | [c9e7579303](https://linux-hardware.org/?probe=c9e7579303) | Jul 01, 2024 |
| MSI           | GP66 Leopard 10UG           | Notebook    | [c50af3b6c8](https://linux-hardware.org/?probe=c50af3b6c8) | Jun 22, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [f0905083d1](https://linux-hardware.org/?probe=f0905083d1) | Jun 22, 2024 |
| Intel         | NUC7i3BNB J22859-306        | Mini pc     | [7f28a9e3de](https://linux-hardware.org/?probe=7f28a9e3de) | Jun 20, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [ec2b1ed18c](https://linux-hardware.org/?probe=ec2b1ed18c) | Jun 14, 2024 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [368a216085](https://linux-hardware.org/?probe=368a216085) | Jun 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [faaa0aa78d](https://linux-hardware.org/?probe=faaa0aa78d) | Jun 08, 2024 |
| ASRock        | H510M-HDV/M.2 SE            | Desktop     | [8211ffc9b9](https://linux-hardware.org/?probe=8211ffc9b9) | Jun 07, 2024 |
| Fujitsu       | LIFEBOOK U9312X             | Convertible | [174505ba3a](https://linux-hardware.org/?probe=174505ba3a) | Jun 03, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [15dd095045](https://linux-hardware.org/?probe=15dd095045) | Jun 01, 2024 |
| HP            | ProBook 640 G8 Notebook ... | Notebook    | [6469f59ede](https://linux-hardware.org/?probe=6469f59ede) | Jun 01, 2024 |
| HP            | Compaq 8710w (GC124EA#AB... | Notebook    | [fbc21ef970](https://linux-hardware.org/?probe=fbc21ef970) | May 31, 2024 |
| HP            | Compaq 8710w (GC124EA#AB... | Notebook    | [93d744065c](https://linux-hardware.org/?probe=93d744065c) | May 30, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | Notebook    | [0bd725fafa](https://linux-hardware.org/?probe=0bd725fafa) | May 30, 2024 |
| Shenzhen M... | F7BSC                       | Mini pc     | [8867eaebbd](https://linux-hardware.org/?probe=8867eaebbd) | May 29, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [da180bf1b1](https://linux-hardware.org/?probe=da180bf1b1) | May 27, 2024 |
| ASUSTek       | M5A78L LE                   | Desktop     | [5afe282618](https://linux-hardware.org/?probe=5afe282618) | May 27, 2024 |
| Gigabyte      | B760 GAMING X DDR4          | Desktop     | [740702872c](https://linux-hardware.org/?probe=740702872c) | May 27, 2024 |
| Dell          | Vostro 15 3510              | Notebook    | [6b8a338778](https://linux-hardware.org/?probe=6b8a338778) | May 15, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [34390c3261](https://linux-hardware.org/?probe=34390c3261) | May 12, 2024 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3d5dfb554e](https://linux-hardware.org/?probe=3d5dfb554e) | May 12, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [ed064c4025](https://linux-hardware.org/?probe=ed064c4025) | May 08, 2024 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [5b40331b05](https://linux-hardware.org/?probe=5b40331b05) | May 03, 2024 |
| Lenovo        | Yoga 2 13 20344             | Notebook    | [440bf944f3](https://linux-hardware.org/?probe=440bf944f3) | May 03, 2024 |
| HP            | OMEN by Laptop 15-dc0xxx    | Notebook    | [23c1b45346](https://linux-hardware.org/?probe=23c1b45346) | May 02, 2024 |
| Lenovo        | IdeaPadFlex 5 14ITL05 82... | Convertible | [fcd6ae5579](https://linux-hardware.org/?probe=fcd6ae5579) | May 02, 2024 |
| HP            | 1496                        | Desktop     | [64f726b9c5](https://linux-hardware.org/?probe=64f726b9c5) | Apr 30, 2024 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [886328abc3](https://linux-hardware.org/?probe=886328abc3) | Apr 25, 2024 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [0b8cd1192f](https://linux-hardware.org/?probe=0b8cd1192f) | Apr 24, 2024 |
| HP            | 8876 11                     | Desktop     | [b15b96ee62](https://linux-hardware.org/?probe=b15b96ee62) | Apr 23, 2024 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [3ac4d133b8](https://linux-hardware.org/?probe=3ac4d133b8) | Apr 23, 2024 |
| Tactus        | GeoBook 140                 | Notebook    | [aa4d027e01](https://linux-hardware.org/?probe=aa4d027e01) | Apr 19, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [f7ab9249b4](https://linux-hardware.org/?probe=f7ab9249b4) | Apr 11, 2024 |
| Dell          | 06JWJY A01                  | Desktop     | [824cb2807f](https://linux-hardware.org/?probe=824cb2807f) | Apr 11, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [1d9ef42930](https://linux-hardware.org/?probe=1d9ef42930) | Apr 11, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [ee70d25db0](https://linux-hardware.org/?probe=ee70d25db0) | Apr 04, 2024 |
| HP            | 1495                        | Desktop     | [7bb71cc6c8](https://linux-hardware.org/?probe=7bb71cc6c8) | Apr 03, 2024 |
| HP            | 1495                        | Desktop     | [369904b953](https://linux-hardware.org/?probe=369904b953) | Apr 03, 2024 |
| Tactus        | GeoBook 140                 | Notebook    | [9e26c5ce44](https://linux-hardware.org/?probe=9e26c5ce44) | Apr 02, 2024 |
| HP            | Notebook                    | Notebook    | [af4830976e](https://linux-hardware.org/?probe=af4830976e) | Apr 01, 2024 |
| Dell          | Inspiron 3542               | Notebook    | [f1a4abd6dc](https://linux-hardware.org/?probe=f1a4abd6dc) | Mar 31, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [000b3bdea6](https://linux-hardware.org/?probe=000b3bdea6) | Mar 29, 2024 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [d3533da3cc](https://linux-hardware.org/?probe=d3533da3cc) | Mar 25, 2024 |
| Gigabyte      | Z790 AORUS PRO X            | Desktop     | [74e95f0015](https://linux-hardware.org/?probe=74e95f0015) | Mar 24, 2024 |
| HP            | ZBook 17                    | Notebook    | [02d8d9dcf1](https://linux-hardware.org/?probe=02d8d9dcf1) | Mar 23, 2024 |
| HP            | 83EF                        | Desktop     | [34c1c23a84](https://linux-hardware.org/?probe=34c1c23a84) | Mar 23, 2024 |
| Acer          | Aspire A515-47              | Notebook    | [e23d4b05d8](https://linux-hardware.org/?probe=e23d4b05d8) | Mar 19, 2024 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [74a0af3ace](https://linux-hardware.org/?probe=74a0af3ace) | Mar 19, 2024 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [fac66be915](https://linux-hardware.org/?probe=fac66be915) | Mar 19, 2024 |
| HP            | ProBook 470 G3              | Notebook    | [7acbeb9e50](https://linux-hardware.org/?probe=7acbeb9e50) | Mar 12, 2024 |
| Dell          | System XPS L702X            | Notebook    | [09313dcc56](https://linux-hardware.org/?probe=09313dcc56) | Mar 11, 2024 |
| HP            | Pavilion Power Laptop 15... | Notebook    | [67978c3e25](https://linux-hardware.org/?probe=67978c3e25) | Mar 10, 2024 |
| HP            | ZBook 17                    | Notebook    | [9535fdaf2b](https://linux-hardware.org/?probe=9535fdaf2b) | Mar 10, 2024 |
| HP            | Laptop 17-bs0xx             | Notebook    | [019d8a8d68](https://linux-hardware.org/?probe=019d8a8d68) | Mar 01, 2024 |
| HP            | ProLiant DL165 G7           | Server      | [8850a77792](https://linux-hardware.org/?probe=8850a77792) | Feb 27, 2024 |
| Lenovo        | ThinkPad T530 2429AL0       | Notebook    | [6040b9b7e2](https://linux-hardware.org/?probe=6040b9b7e2) | Feb 24, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [8173a2268e](https://linux-hardware.org/?probe=8173a2268e) | Feb 24, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [d91a07c2e1](https://linux-hardware.org/?probe=d91a07c2e1) | Feb 22, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | Notebook    | [4e64450aa5](https://linux-hardware.org/?probe=4e64450aa5) | Feb 21, 2024 |
| Dell          | Latitude D530               | Notebook    | [0885268edd](https://linux-hardware.org/?probe=0885268edd) | Feb 20, 2024 |
| Dell          | Latitude D530               | Notebook    | [e4d1a73b6e](https://linux-hardware.org/?probe=e4d1a73b6e) | Feb 20, 2024 |
| Gigabyte      | B650M DS3H                  | Desktop     | [91f2211c0c](https://linux-hardware.org/?probe=91f2211c0c) | Feb 14, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [1982f26149](https://linux-hardware.org/?probe=1982f26149) | Feb 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | Notebook    | [d83aac3c35](https://linux-hardware.org/?probe=d83aac3c35) | Feb 11, 2024 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | Notebook    | [f1ffdd8987](https://linux-hardware.org/?probe=f1ffdd8987) | Feb 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | Notebook    | [d916f30fdc](https://linux-hardware.org/?probe=d916f30fdc) | Feb 10, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [5c94c6fba5](https://linux-hardware.org/?probe=5c94c6fba5) | Feb 07, 2024 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [bf2ce0efeb](https://linux-hardware.org/?probe=bf2ce0efeb) | Jan 15, 2024 |
| Acer          | Swift SFG14-42              | Notebook    | [15da646623](https://linux-hardware.org/?probe=15da646623) | Jan 11, 2024 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [80799f979c](https://linux-hardware.org/?probe=80799f979c) | Jan 10, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [7013d64a90](https://linux-hardware.org/?probe=7013d64a90) | Jan 09, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [2b8bf09bd1](https://linux-hardware.org/?probe=2b8bf09bd1) | Jan 08, 2024 |
| Dell          | Inspiron 3521               | Notebook    | [2a29a6c24b](https://linux-hardware.org/?probe=2a29a6c24b) | Jan 08, 2024 |
| Apple         | MacBookAir7,2               | Notebook    | [810f81c66e](https://linux-hardware.org/?probe=810f81c66e) | Jan 06, 2024 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [ff9686f03c](https://linux-hardware.org/?probe=ff9686f03c) | Jan 06, 2024 |
| Dynabook      | Satellite Pro C40-G-109     | Notebook    | [0247395541](https://linux-hardware.org/?probe=0247395541) | Jan 05, 2024 |
| Unknown       | Apple MacBook Air (13-in... | Notebook    | [834855dcac](https://linux-hardware.org/?probe=834855dcac) | Jan 01, 2024 |
| HP            | Pavilion dv7                | Notebook    | [4b1ea284d3](https://linux-hardware.org/?probe=4b1ea284d3) | Dec 28, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [7a9ff71d9b](https://linux-hardware.org/?probe=7a9ff71d9b) | Dec 28, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [58bbd67a73](https://linux-hardware.org/?probe=58bbd67a73) | Dec 23, 2023 |
| Acer          | Aspire A3SP14-31PT          | Convertible | [d9850a7566](https://linux-hardware.org/?probe=d9850a7566) | Dec 23, 2023 |
| Gigabyte      | Z790 GAMING X AX            | Desktop     | [155e0f1c37](https://linux-hardware.org/?probe=155e0f1c37) | Dec 22, 2023 |
| Dell          | 0R790T A00                  | Desktop     | [8a72b2a4ce](https://linux-hardware.org/?probe=8a72b2a4ce) | Dec 13, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [656732b40e](https://linux-hardware.org/?probe=656732b40e) | Dec 12, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [367489ed4f](https://linux-hardware.org/?probe=367489ed4f) | Dec 10, 2023 |
| eMachines     | ET1850                      | Desktop     | [b433ca3cfa](https://linux-hardware.org/?probe=b433ca3cfa) | Dec 02, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0137a4a556](https://linux-hardware.org/?probe=0137a4a556) | Nov 23, 2023 |
| eMachines     | E725 V1.03                  | Notebook    | [bd5b32a320](https://linux-hardware.org/?probe=bd5b32a320) | Nov 20, 2023 |
| eMachines     | E725 V1.03                  | Notebook    | [bd29f2ff41](https://linux-hardware.org/?probe=bd29f2ff41) | Nov 19, 2023 |
| MSI           | PRO B650M-A WIFI            | Desktop     | [2a9ba6fc77](https://linux-hardware.org/?probe=2a9ba6fc77) | Nov 17, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [9b2d42ff24](https://linux-hardware.org/?probe=9b2d42ff24) | Nov 15, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | Notebook    | [f5413c3dd5](https://linux-hardware.org/?probe=f5413c3dd5) | Nov 15, 2023 |
| HP            | 18E4                        | Desktop     | [fb73ea4228](https://linux-hardware.org/?probe=fb73ea4228) | Nov 12, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [982139b13a](https://linux-hardware.org/?probe=982139b13a) | Nov 11, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [4fd542edf2](https://linux-hardware.org/?probe=4fd542edf2) | Nov 11, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c019f410aa](https://linux-hardware.org/?probe=c019f410aa) | Nov 08, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [4bfe797838](https://linux-hardware.org/?probe=4bfe797838) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | Notebook    | [4b04b9ef25](https://linux-hardware.org/?probe=4b04b9ef25) | Nov 02, 2023 |
| Acer          | AOD270                      | Notebook    | [83c4a5920f](https://linux-hardware.org/?probe=83c4a5920f) | Oct 29, 2023 |
| Lenovo        | ThinkPad T450s 20BWS58K0... | Notebook    | [11b2f76301](https://linux-hardware.org/?probe=11b2f76301) | Oct 29, 2023 |
| HP            | Presario CQ57               | Notebook    | [f35a975672](https://linux-hardware.org/?probe=f35a975672) | Oct 29, 2023 |
| HP            | ZBook Firefly 14 inch G8... | Notebook    | [bd82dd57be](https://linux-hardware.org/?probe=bd82dd57be) | Oct 27, 2023 |
| Intel         | NUC7i7BNB J31145-303        | Mini pc     | [8b6a0fb21d](https://linux-hardware.org/?probe=8b6a0fb21d) | Oct 25, 2023 |
| ASRock        | B650E PG Riptide WiFi       | Desktop     | [24304767eb](https://linux-hardware.org/?probe=24304767eb) | Oct 21, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [deeaf6af5b](https://linux-hardware.org/?probe=deeaf6af5b) | Oct 19, 2023 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [0bdf442d3d](https://linux-hardware.org/?probe=0bdf442d3d) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | Notebook    | [c8f55c449a](https://linux-hardware.org/?probe=c8f55c449a) | Oct 19, 2023 |
| HP            | Laptop 15-fd0xxx            | Notebook    | [0e6cc9fc48](https://linux-hardware.org/?probe=0e6cc9fc48) | Oct 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | Notebook    | [6c49286a6c](https://linux-hardware.org/?probe=6c49286a6c) | Oct 14, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [bf88efbfff](https://linux-hardware.org/?probe=bf88efbfff) | Oct 05, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [e0158c541c](https://linux-hardware.org/?probe=e0158c541c) | Sep 29, 2023 |
| Dell          | Inspiron 5570               | Notebook    | [7975260826](https://linux-hardware.org/?probe=7975260826) | Sep 29, 2023 |
| Dell          | Latitude 5431               | Notebook    | [d9ea685862](https://linux-hardware.org/?probe=d9ea685862) | Sep 27, 2023 |
| Dell          | Vostro 3500                 | Notebook    | [fac9ee2e6e](https://linux-hardware.org/?probe=fac9ee2e6e) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [0e32901b18](https://linux-hardware.org/?probe=0e32901b18) | Sep 27, 2023 |
| Gigabyte      | X570S UD                    | Desktop     | [88653e2f06](https://linux-hardware.org/?probe=88653e2f06) | Sep 24, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [5a6ff779bd](https://linux-hardware.org/?probe=5a6ff779bd) | Sep 19, 2023 |
| MSI           | MPG B760I EDGE WIFI DDR4    | Desktop     | [bd389fb2a0](https://linux-hardware.org/?probe=bd389fb2a0) | Sep 15, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [c8ee0a00a5](https://linux-hardware.org/?probe=c8ee0a00a5) | Sep 06, 2023 |
| Lenovo        | ThinkCentre A58 77057FG     | Desktop     | [b96c23b77b](https://linux-hardware.org/?probe=b96c23b77b) | Sep 04, 2023 |
| Apple         | MacBookPro11,4              | Notebook    | [c833e40c97](https://linux-hardware.org/?probe=c833e40c97) | Sep 01, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [ba837274bd](https://linux-hardware.org/?probe=ba837274bd) | Sep 01, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [294343383a](https://linux-hardware.org/?probe=294343383a) | Aug 30, 2023 |
| Acer          | Predator PH517-51           | Notebook    | [adba295596](https://linux-hardware.org/?probe=adba295596) | Aug 30, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [caaf599d6a](https://linux-hardware.org/?probe=caaf599d6a) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [f91274084a](https://linux-hardware.org/?probe=f91274084a) | Aug 29, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4bc3ed94ce](https://linux-hardware.org/?probe=4bc3ed94ce) | Aug 28, 2023 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [2fa0bbc7ec](https://linux-hardware.org/?probe=2fa0bbc7ec) | Aug 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [8acc158836](https://linux-hardware.org/?probe=8acc158836) | Aug 27, 2023 |
| ASRock        | B560 Steel Legend           | Desktop     | [b2e8cd4ed2](https://linux-hardware.org/?probe=b2e8cd4ed2) | Aug 26, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [1f6e4f9676](https://linux-hardware.org/?probe=1f6e4f9676) | Aug 21, 2023 |
| Lenovo        | ThinkPad T495s 20QJ001MG... | Notebook    | [3ac30cf2d0](https://linux-hardware.org/?probe=3ac30cf2d0) | Aug 16, 2023 |
| HP            | EliteBook 840 14 inch G1... | Notebook    | [73b7fc1fc9](https://linux-hardware.org/?probe=73b7fc1fc9) | Aug 11, 2023 |
| ASUSTek       | TUF Gaming B660-PLUS WIF... | Desktop     | [ee8f18e185](https://linux-hardware.org/?probe=ee8f18e185) | Aug 07, 2023 |
| Acer          | Aspire 5736Z                | Notebook    | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [c7724d9c7c](https://linux-hardware.org/?probe=c7724d9c7c) | Aug 02, 2023 |
| HP            | 2B47                        | Desktop     | [06373794be](https://linux-hardware.org/?probe=06373794be) | Aug 01, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [8b7ca3c460](https://linux-hardware.org/?probe=8b7ca3c460) | Jul 21, 2023 |
| Dell          | Latitude 5520               | Notebook    | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [043258de54](https://linux-hardware.org/?probe=043258de54) | Jul 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [567736ec02](https://linux-hardware.org/?probe=567736ec02) | Jul 14, 2023 |
| Acer          | Swift SF314-58G             | Notebook    | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | Notebook    | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| Dell          | OptiPlex 9020               | Notebook    | [3384a64b67](https://linux-hardware.org/?probe=3384a64b67) | Jul 10, 2023 |
| Timi          | TM1701                      | Notebook    | [5dee3c6b81](https://linux-hardware.org/?probe=5dee3c6b81) | Jul 01, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [8f6d75c75e](https://linux-hardware.org/?probe=8f6d75c75e) | Jun 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [c1472b1c25](https://linux-hardware.org/?probe=c1472b1c25) | Jun 18, 2023 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [289d9fe165](https://linux-hardware.org/?probe=289d9fe165) | Jun 14, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [18e80281cc](https://linux-hardware.org/?probe=18e80281cc) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | Notebook    | [f7bd03dbb9](https://linux-hardware.org/?probe=f7bd03dbb9) | Jun 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [bf403bb6d8](https://linux-hardware.org/?probe=bf403bb6d8) | Jun 06, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | Notebook    | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [c8e0efc288](https://linux-hardware.org/?probe=c8e0efc288) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | Notebook    | [da399dc7cc](https://linux-hardware.org/?probe=da399dc7cc) | May 29, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a36e1c1d5](https://linux-hardware.org/?probe=2a36e1c1d5) | May 26, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [913f21a49c](https://linux-hardware.org/?probe=913f21a49c) | May 25, 2023 |
| Acer          | Aspire A515-57              | Notebook    | [3272ba5e49](https://linux-hardware.org/?probe=3272ba5e49) | May 19, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| Schenker      | VISION (E22)                | Notebook    | [582ac3cbf5](https://linux-hardware.org/?probe=582ac3cbf5) | May 13, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [cd65f81693](https://linux-hardware.org/?probe=cd65f81693) | May 11, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [45c02c8b1b](https://linux-hardware.org/?probe=45c02c8b1b) | May 11, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [5312325c90](https://linux-hardware.org/?probe=5312325c90) | May 10, 2023 |
| Lenovo        | ThinkPad T530 2394CE2       | Notebook    | [d232fefed2](https://linux-hardware.org/?probe=d232fefed2) | May 09, 2023 |
| HPE           | ProLiant ML30 Gen10 Plus    | Desktop     | [3a75fa5c03](https://linux-hardware.org/?probe=3a75fa5c03) | May 07, 2023 |
| Acer          | Predator PH315-53           | Notebook    | [efb597952f](https://linux-hardware.org/?probe=efb597952f) | May 07, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1c98821416](https://linux-hardware.org/?probe=1c98821416) | May 03, 2023 |
| Acer          | TravelMate 5730             | Notebook    | [e74d115d0d](https://linux-hardware.org/?probe=e74d115d0d) | Apr 29, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [5cb9fe1ae9](https://linux-hardware.org/?probe=5cb9fe1ae9) | Apr 28, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | Notebook    | [3669ef1de9](https://linux-hardware.org/?probe=3669ef1de9) | Apr 28, 2023 |
| Lenovo        | 3000 N200 0769A97           | Notebook    | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [0db2c54b2a](https://linux-hardware.org/?probe=0db2c54b2a) | Apr 24, 2023 |
| ASUSTek       | GRYPHON Z87                 | Desktop     | [045a79a6e4](https://linux-hardware.org/?probe=045a79a6e4) | Apr 18, 2023 |
| Lenovo        | 30C0 SDK0J40705 WIN 3425... | Desktop     | [490a059818](https://linux-hardware.org/?probe=490a059818) | Apr 13, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [b3c9b78fec](https://linux-hardware.org/?probe=b3c9b78fec) | Apr 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [bba5f185af](https://linux-hardware.org/?probe=bba5f185af) | Apr 13, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | Notebook    | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [64f96c6fde](https://linux-hardware.org/?probe=64f96c6fde) | Apr 07, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [917714b1be](https://linux-hardware.org/?probe=917714b1be) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [ad148ede52](https://linux-hardware.org/?probe=ad148ede52) | Apr 06, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [171e39cdb6](https://linux-hardware.org/?probe=171e39cdb6) | Apr 05, 2023 |
| Dell          | Latitude 5530               | Notebook    | [802248e232](https://linux-hardware.org/?probe=802248e232) | Apr 03, 2023 |
| Intel         | NUC11PABi3 M68269-400       | Mini pc     | [7c7fdc5950](https://linux-hardware.org/?probe=7c7fdc5950) | Apr 02, 2023 |
| Dell          | Latitude 5530               | Notebook    | [e4688e2ef8](https://linux-hardware.org/?probe=e4688e2ef8) | Apr 01, 2023 |
| HP            | 82DC 1100                   | All in one  | [4c1c2f908b](https://linux-hardware.org/?probe=4c1c2f908b) | Mar 30, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [b8e3d627b5](https://linux-hardware.org/?probe=b8e3d627b5) | Mar 27, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [2b0f3e8867](https://linux-hardware.org/?probe=2b0f3e8867) | Mar 25, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | Notebook    | [8bb2484825](https://linux-hardware.org/?probe=8bb2484825) | Mar 25, 2023 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [bdfe7a3498](https://linux-hardware.org/?probe=bdfe7a3498) | Mar 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [4c7add7cd1](https://linux-hardware.org/?probe=4c7add7cd1) | Mar 21, 2023 |
| Tactus        | GeoBook 140                 | Notebook    | [5efd6f0674](https://linux-hardware.org/?probe=5efd6f0674) | Mar 20, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| Supermicro    | X8DTU                       | Server      | [6012de6351](https://linux-hardware.org/?probe=6012de6351) | Mar 10, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [2409dc15b4](https://linux-hardware.org/?probe=2409dc15b4) | Mar 10, 2023 |
| HP            | EliteBook 8730w             | Notebook    | [a012fe4bd2](https://linux-hardware.org/?probe=a012fe4bd2) | Mar 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b349a8eedd](https://linux-hardware.org/?probe=b349a8eedd) | Mar 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| ASRock        | H97 Pro4                    | Desktop     | [9ef8ff0b68](https://linux-hardware.org/?probe=9ef8ff0b68) | Mar 06, 2023 |
| Dell          | OptiPlex 9020               | Notebook    | [dda13d9c8e](https://linux-hardware.org/?probe=dda13d9c8e) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [8e02418ca7](https://linux-hardware.org/?probe=8e02418ca7) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [5510fed545](https://linux-hardware.org/?probe=5510fed545) | Mar 04, 2023 |
| Acer          | Swift SF314-43              | Notebook    | [4f2c05c854](https://linux-hardware.org/?probe=4f2c05c854) | Feb 28, 2023 |
| Valve         | Jupiter                     | Notebook    | [e2f06dcb4a](https://linux-hardware.org/?probe=e2f06dcb4a) | Feb 24, 2023 |
| Dell          | System XPS L702X            | Notebook    | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | Notebook    | [1d5a0bc43f](https://linux-hardware.org/?probe=1d5a0bc43f) | Feb 14, 2023 |
| Lenovo        | ThinkPad T540p 20BFA183A... | Notebook    | [2705e3d0c5](https://linux-hardware.org/?probe=2705e3d0c5) | Feb 12, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [e574477cb6](https://linux-hardware.org/?probe=e574477cb6) | Feb 07, 2023 |
| MSI           | 0A90                        | Desktop     | [9210981559](https://linux-hardware.org/?probe=9210981559) | Feb 06, 2023 |
| MSI           | 0A90                        | Desktop     | [aedd414dbf](https://linux-hardware.org/?probe=aedd414dbf) | Feb 06, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [9f76193ccc](https://linux-hardware.org/?probe=9f76193ccc) | Jan 29, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [34882391f3](https://linux-hardware.org/?probe=34882391f3) | Jan 25, 2023 |
| HP            | Laptop 15-bs1xx             | Notebook    | [76689345ef](https://linux-hardware.org/?probe=76689345ef) | Jan 19, 2023 |
| Toshiba       | Satellite P200              | Notebook    | [478f5dc5cb](https://linux-hardware.org/?probe=478f5dc5cb) | Jan 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [29ff669f2c](https://linux-hardware.org/?probe=29ff669f2c) | Jan 14, 2023 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [2b04043ef0](https://linux-hardware.org/?probe=2b04043ef0) | Jan 10, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ef10fbe492](https://linux-hardware.org/?probe=ef10fbe492) | Jan 09, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| Samsung       | SBB-DA                      | Notebook    | [a4c6b4f454](https://linux-hardware.org/?probe=a4c6b4f454) | Jan 07, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [800f20e309](https://linux-hardware.org/?probe=800f20e309) | Jan 07, 2023 |
| Lenovo        | MIIX 320-10ICR 80XF         | Tablet      | [066ab1d6a3](https://linux-hardware.org/?probe=066ab1d6a3) | Jan 04, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [f6de50a76b](https://linux-hardware.org/?probe=f6de50a76b) | Jan 04, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [e703dd0215](https://linux-hardware.org/?probe=e703dd0215) | Jan 04, 2023 |
| ASUSTek       | N551JM                      | Notebook    | [3ba1d0e689](https://linux-hardware.org/?probe=3ba1d0e689) | Jan 03, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [d88df3fcee](https://linux-hardware.org/?probe=d88df3fcee) | Jan 01, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [92f3c92191](https://linux-hardware.org/?probe=92f3c92191) | Dec 29, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [2923c4c0fc](https://linux-hardware.org/?probe=2923c4c0fc) | Dec 28, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9b8756cdd0](https://linux-hardware.org/?probe=9b8756cdd0) | Dec 17, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [b2b93008c3](https://linux-hardware.org/?probe=b2b93008c3) | Dec 17, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [516d6f7f12](https://linux-hardware.org/?probe=516d6f7f12) | Dec 14, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [3dcbd61f9e](https://linux-hardware.org/?probe=3dcbd61f9e) | Dec 12, 2022 |
| Lenovo        | HASWELLREFRESHDT 3190005... | All in one  | [b73060ce38](https://linux-hardware.org/?probe=b73060ce38) | Dec 10, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [15d7102174](https://linux-hardware.org/?probe=15d7102174) | Dec 08, 2022 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [52525a1058](https://linux-hardware.org/?probe=52525a1058) | Dec 08, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9815b67f0b](https://linux-hardware.org/?probe=9815b67f0b) | Dec 06, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [d632edc927](https://linux-hardware.org/?probe=d632edc927) | Dec 05, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | Notebook    | [412bffea3b](https://linux-hardware.org/?probe=412bffea3b) | Dec 05, 2022 |
| ASRock        | K10N78D                     | Desktop     | [b5e2e7a024](https://linux-hardware.org/?probe=b5e2e7a024) | Dec 02, 2022 |
| ASRock        | B550M-ITX/ac                | Desktop     | [31f70fbb3e](https://linux-hardware.org/?probe=31f70fbb3e) | Nov 27, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [e904ef7a24](https://linux-hardware.org/?probe=e904ef7a24) | Nov 26, 2022 |
| ASUSTek       | X550LB                      | Notebook    | [466592b744](https://linux-hardware.org/?probe=466592b744) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | Notebook    | [3ca5ee2f7a](https://linux-hardware.org/?probe=3ca5ee2f7a) | Nov 20, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [9e16721568](https://linux-hardware.org/?probe=9e16721568) | Nov 17, 2022 |
| HP            | 1998                        | Desktop     | [f9746a4ae0](https://linux-hardware.org/?probe=f9746a4ae0) | Nov 15, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [311c90573c](https://linux-hardware.org/?probe=311c90573c) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [1198a061e1](https://linux-hardware.org/?probe=1198a061e1) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | Notebook    | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | Notebook    | [84bf8d9578](https://linux-hardware.org/?probe=84bf8d9578) | Nov 05, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [01381d41de](https://linux-hardware.org/?probe=01381d41de) | Nov 03, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [b3cac9f8b8](https://linux-hardware.org/?probe=b3cac9f8b8) | Nov 02, 2022 |
| Intel         | NUC5i5MYBE H47797-202       | Mini pc     | [41a93c4dfa](https://linux-hardware.org/?probe=41a93c4dfa) | Nov 02, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [499932f589](https://linux-hardware.org/?probe=499932f589) | Nov 01, 2022 |
| Dell          | Studio 1735                 | Notebook    | [8f070a2831](https://linux-hardware.org/?probe=8f070a2831) | Oct 30, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [24b035a7a4](https://linux-hardware.org/?probe=24b035a7a4) | Oct 25, 2022 |
| Dell          | Studio 1735                 | Notebook    | [21959a7db7](https://linux-hardware.org/?probe=21959a7db7) | Oct 24, 2022 |
| ASUSTek       | K53U                        | Notebook    | [d178c463df](https://linux-hardware.org/?probe=d178c463df) | Oct 24, 2022 |
| Dell          | Studio 1735                 | Notebook    | [4385640990](https://linux-hardware.org/?probe=4385640990) | Oct 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [04fed978ae](https://linux-hardware.org/?probe=04fed978ae) | Oct 18, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | Notebook    | [e3eba59f05](https://linux-hardware.org/?probe=e3eba59f05) | Oct 17, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [c6f57791dc](https://linux-hardware.org/?probe=c6f57791dc) | Oct 12, 2022 |
| Acer          | Aspire A317-53              | Notebook    | [dadf436fd1](https://linux-hardware.org/?probe=dadf436fd1) | Oct 10, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [e7545a94b2](https://linux-hardware.org/?probe=e7545a94b2) | Oct 09, 2022 |
| HP            | EliteBook 8730w             | Notebook    | [b938a96086](https://linux-hardware.org/?probe=b938a96086) | Oct 09, 2022 |
| ASUSTek       | M5A78L LE                   | Desktop     | [69023fe30e](https://linux-hardware.org/?probe=69023fe30e) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | Notebook    | [3f2cdff8d4](https://linux-hardware.org/?probe=3f2cdff8d4) | Oct 05, 2022 |
| Toshiba       | Encore                      | Notebook    | [a11bf538ec](https://linux-hardware.org/?probe=a11bf538ec) | Oct 05, 2022 |
| Lenovo        | 0x30F617AA NOK              | Desktop     | [bb13b87bd5](https://linux-hardware.org/?probe=bb13b87bd5) | Oct 01, 2022 |
| ASRock        | A320M-DVS R4.0              | Desktop     | [0dca3e500c](https://linux-hardware.org/?probe=0dca3e500c) | Sep 22, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Lenovo        | Unknown                     | Notebook    | [64dc493d4d](https://linux-hardware.org/?probe=64dc493d4d) | Sep 17, 2022 |
| Lenovo        | Unknown                     | Notebook    | [581356206a](https://linux-hardware.org/?probe=581356206a) | Sep 17, 2022 |
| Dell          | Latitude 5420               | Notebook    | [511ef8a105](https://linux-hardware.org/?probe=511ef8a105) | Sep 08, 2022 |
| Dell          | Latitude 5420               | Notebook    | [48db2c3954](https://linux-hardware.org/?probe=48db2c3954) | Sep 08, 2022 |
| Toshiba       | Satellite P200              | Notebook    | [583489891f](https://linux-hardware.org/?probe=583489891f) | Sep 06, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [9543920c45](https://linux-hardware.org/?probe=9543920c45) | Sep 04, 2022 |
| HP            | Pavilion dv9700             | Notebook    | [b6d4d6bca2](https://linux-hardware.org/?probe=b6d4d6bca2) | Sep 04, 2022 |
| Acer          | Swift SF314-41              | Notebook    | [1394aca8b2](https://linux-hardware.org/?probe=1394aca8b2) | Sep 03, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [60865c8ded](https://linux-hardware.org/?probe=60865c8ded) | Sep 02, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [0e4eab04c0](https://linux-hardware.org/?probe=0e4eab04c0) | Aug 27, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [65e832cb2f](https://linux-hardware.org/?probe=65e832cb2f) | Aug 27, 2022 |
| Dell          | Latitude 5290 2-in-1        | Notebook    | [bafc4d3392](https://linux-hardware.org/?probe=bafc4d3392) | Aug 20, 2022 |
| Dell          | Latitude E7240              | Notebook    | [1f20b0f54b](https://linux-hardware.org/?probe=1f20b0f54b) | Aug 08, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [5ddb15f201](https://linux-hardware.org/?probe=5ddb15f201) | Aug 07, 2022 |
| Acer          | Aspire A515-56G             | Notebook    | [3df2b6b19b](https://linux-hardware.org/?probe=3df2b6b19b) | Aug 05, 2022 |
| HP            | 1825                        | Desktop     | [4a21a02ae4](https://linux-hardware.org/?probe=4a21a02ae4) | Jul 29, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [3c665fb25f](https://linux-hardware.org/?probe=3c665fb25f) | Jul 28, 2022 |
| ASUSTek       | S551LB                      | Notebook    | [8660a06086](https://linux-hardware.org/?probe=8660a06086) | Jul 27, 2022 |
| Lenovo        | ThinkPad T580 20LAS27000    | Notebook    | [a78a8e806f](https://linux-hardware.org/?probe=a78a8e806f) | Jul 21, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [6886cd26f5](https://linux-hardware.org/?probe=6886cd26f5) | Jul 20, 2022 |
| Gigabyte      | Z97-D3H-CF                  | Desktop     | [55f956b817](https://linux-hardware.org/?probe=55f956b817) | Jul 14, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [17cdd0291e](https://linux-hardware.org/?probe=17cdd0291e) | Jul 12, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [4de601fe45](https://linux-hardware.org/?probe=4de601fe45) | Jul 12, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [4bd18943fb](https://linux-hardware.org/?probe=4bd18943fb) | Jul 09, 2022 |
| ASUSTek       | X75A1                       | Notebook    | [3da162d001](https://linux-hardware.org/?probe=3da162d001) | Jul 09, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [36305f7936](https://linux-hardware.org/?probe=36305f7936) | Jul 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2330... | Notebook    | [4718003bb5](https://linux-hardware.org/?probe=4718003bb5) | Jul 09, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [6d9101e2d2](https://linux-hardware.org/?probe=6d9101e2d2) | Jul 08, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [36c7cff92d](https://linux-hardware.org/?probe=36c7cff92d) | Jul 07, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [445bedc2c9](https://linux-hardware.org/?probe=445bedc2c9) | Jul 06, 2022 |
| ASRock        | K10N78D                     | Desktop     | [650465a972](https://linux-hardware.org/?probe=650465a972) | Jul 06, 2022 |
| Dell          | Inspiron 3537               | Notebook    | [bfe2aed3aa](https://linux-hardware.org/?probe=bfe2aed3aa) | Jul 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | Notebook    | [4d4cd5bae0](https://linux-hardware.org/?probe=4d4cd5bae0) | Jul 05, 2022 |
| WinFast       | NF-MCP55 FAB1.0             | Desktop     | [bb066cc2da](https://linux-hardware.org/?probe=bb066cc2da) | Jul 03, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82ca4386ae](https://linux-hardware.org/?probe=82ca4386ae) | Jun 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [42462e221b](https://linux-hardware.org/?probe=42462e221b) | Jun 29, 2022 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c73501602b](https://linux-hardware.org/?probe=c73501602b) | Jun 26, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [160062e69a](https://linux-hardware.org/?probe=160062e69a) | Jun 25, 2022 |
| Gigabyte      | G5 KC                       | Notebook    | [5ef620811f](https://linux-hardware.org/?probe=5ef620811f) | Jun 25, 2022 |
| Acer          | Aspire A315-23              | Notebook    | [45c9b081c5](https://linux-hardware.org/?probe=45c9b081c5) | Jun 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [96c4f21509](https://linux-hardware.org/?probe=96c4f21509) | Jun 21, 2022 |
| Acer          | Aspire E5-771G              | Notebook    | [dac3ae2eba](https://linux-hardware.org/?probe=dac3ae2eba) | Jun 21, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [ba5ab976e2](https://linux-hardware.org/?probe=ba5ab976e2) | Jun 16, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [d2b608c230](https://linux-hardware.org/?probe=d2b608c230) | Jun 16, 2022 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [0d4266a0f3](https://linux-hardware.org/?probe=0d4266a0f3) | Jun 15, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [1f92039342](https://linux-hardware.org/?probe=1f92039342) | Jun 02, 2022 |
| Supermicro    | C7Z270-CG-M                 | Server      | [dbbe7457ff](https://linux-hardware.org/?probe=dbbe7457ff) | May 31, 2022 |
| Supermicro    | C7Z270-CG-M                 | Server      | [a9c593dd0b](https://linux-hardware.org/?probe=a9c593dd0b) | May 31, 2022 |
| ASUSTek       | B250 MINING EXPERT          | Desktop     | [987ef7b2e7](https://linux-hardware.org/?probe=987ef7b2e7) | May 26, 2022 |
| Dell          | Vostro 3500                 | Notebook    | [9dff398fa9](https://linux-hardware.org/?probe=9dff398fa9) | May 24, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [7b393b3933](https://linux-hardware.org/?probe=7b393b3933) | May 24, 2022 |
| Lenovo        | G40-30 80FY                 | Notebook    | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| eMachines     | E525                        | Notebook    | [2c397d4229](https://linux-hardware.org/?probe=2c397d4229) | May 19, 2022 |
| eMachines     | E525                        | Notebook    | [7a1e439150](https://linux-hardware.org/?probe=7a1e439150) | May 19, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [2953148fae](https://linux-hardware.org/?probe=2953148fae) | May 16, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| Dell          | 0J37VM A01                  | Desktop     | [a5363ae511](https://linux-hardware.org/?probe=a5363ae511) | May 09, 2022 |
| ASUSTek       | PRIME H510M-A               | Desktop     | [1e2ee4a2fb](https://linux-hardware.org/?probe=1e2ee4a2fb) | May 09, 2022 |
| ASRock        | Z87 Extreme4                | Desktop     | [db3a8bef92](https://linux-hardware.org/?probe=db3a8bef92) | May 09, 2022 |
| Lenovo        | 3746 No DPK                 | All in one  | [910612b856](https://linux-hardware.org/?probe=910612b856) | May 07, 2022 |
| ASRock        | H470M-HDV                   | Desktop     | [14d8e1d537](https://linux-hardware.org/?probe=14d8e1d537) | May 06, 2022 |
| HP            | ProBook 470 G1              | Notebook    | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [3d1c0ef2f0](https://linux-hardware.org/?probe=3d1c0ef2f0) | May 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [220979cd04](https://linux-hardware.org/?probe=220979cd04) | May 05, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [8d561055ba](https://linux-hardware.org/?probe=8d561055ba) | May 04, 2022 |
| HP            | Pavilion 17                 | Notebook    | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X540UA                      | Notebook    | [af0ed39935](https://linux-hardware.org/?probe=af0ed39935) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [bc333fe437](https://linux-hardware.org/?probe=bc333fe437) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [67d1865b69](https://linux-hardware.org/?probe=67d1865b69) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [57a8a5bfcd](https://linux-hardware.org/?probe=57a8a5bfcd) | Apr 30, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [dc8419dcb3](https://linux-hardware.org/?probe=dc8419dcb3) | Apr 29, 2022 |
| HP            | Pavilion 17                 | Notebook    | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Intel         | H61M-S2PV                   | Desktop     | [caa602b556](https://linux-hardware.org/?probe=caa602b556) | Apr 28, 2022 |
| Gigabyte      | P31-ES3G                    | Desktop     | [c3df637d15](https://linux-hardware.org/?probe=c3df637d15) | Apr 27, 2022 |
| Razer         | Blade                       | Notebook    | [c5ef4943c4](https://linux-hardware.org/?probe=c5ef4943c4) | Apr 27, 2022 |
| Fujitsu Si... | D2151-A1 S26361-D2151-A1    | Desktop     | [4db68ede02](https://linux-hardware.org/?probe=4db68ede02) | Apr 27, 2022 |
| ASRock        | H61M-DGS                    | Desktop     | [c8019d43f7](https://linux-hardware.org/?probe=c8019d43f7) | Apr 25, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [e937f129bf](https://linux-hardware.org/?probe=e937f129bf) | Apr 25, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | Notebook    | [1a7a85a6ca](https://linux-hardware.org/?probe=1a7a85a6ca) | Apr 21, 2022 |
| Pegatron      | 2AC3                        | Desktop     | [771e8a4439](https://linux-hardware.org/?probe=771e8a4439) | Apr 18, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [84978cfba3](https://linux-hardware.org/?probe=84978cfba3) | Apr 17, 2022 |
| Acer          | Swift SF114-32              | Notebook    | [e970f67c93](https://linux-hardware.org/?probe=e970f67c93) | Apr 13, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [82d8b5968f](https://linux-hardware.org/?probe=82d8b5968f) | Apr 12, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | Notebook    | [bae30f6939](https://linux-hardware.org/?probe=bae30f6939) | Apr 11, 2022 |
| Dell          | OptiPlex 9020               | Notebook    | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [d7d4ac2b9a](https://linux-hardware.org/?probe=d7d4ac2b9a) | Apr 04, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [73cf5373cf](https://linux-hardware.org/?probe=73cf5373cf) | Apr 03, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f76380fdae](https://linux-hardware.org/?probe=f76380fdae) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | Notebook    | [f9ab989993](https://linux-hardware.org/?probe=f9ab989993) | Apr 02, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [752a6415ff](https://linux-hardware.org/?probe=752a6415ff) | Apr 02, 2022 |
| ASUSTek       | X71Sr                       | Notebook    | [0e6ffbc190](https://linux-hardware.org/?probe=0e6ffbc190) | Apr 01, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [f63c898bc3](https://linux-hardware.org/?probe=f63c898bc3) | Mar 18, 2022 |
| eMachines     | E725 V1.03                  | Notebook    | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| ASUSTek       | P8H61 PRO                   | Desktop     | [60dc2b7bd7](https://linux-hardware.org/?probe=60dc2b7bd7) | Mar 18, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [9352c21f95](https://linux-hardware.org/?probe=9352c21f95) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [8a6bb86ea0](https://linux-hardware.org/?probe=8a6bb86ea0) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [271852ad10](https://linux-hardware.org/?probe=271852ad10) | Mar 17, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [6415b33b34](https://linux-hardware.org/?probe=6415b33b34) | Mar 17, 2022 |
| ASUSTek       | G75VX                       | Notebook    | [2b94fd73ea](https://linux-hardware.org/?probe=2b94fd73ea) | Mar 14, 2022 |
| Lenovo        | ThinkPad T410 2522DK2       | Notebook    | [9990e887c2](https://linux-hardware.org/?probe=9990e887c2) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [561a945c5a](https://linux-hardware.org/?probe=561a945c5a) | Mar 13, 2022 |
| HP            | ProBook 4530s               | Notebook    | [061de41ec5](https://linux-hardware.org/?probe=061de41ec5) | Mar 13, 2022 |
| Toshiba       | Satellite C850-1GD          | Notebook    | [79b2741217](https://linux-hardware.org/?probe=79b2741217) | Mar 12, 2022 |
| ASRock        | B360 Gaming K4              | Desktop     | [ae6cb3bea9](https://linux-hardware.org/?probe=ae6cb3bea9) | Mar 11, 2022 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [ed3d7239af](https://linux-hardware.org/?probe=ed3d7239af) | Mar 09, 2022 |
| ASUSTek       | Z170-P                      | Desktop     | [fac84edcf2](https://linux-hardware.org/?probe=fac84edcf2) | Mar 08, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [83df7fb05a](https://linux-hardware.org/?probe=83df7fb05a) | Mar 07, 2022 |
| Gigabyte      | X48T-DQ6                    | Desktop     | [593cb60512](https://linux-hardware.org/?probe=593cb60512) | Mar 06, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [49093d0be0](https://linux-hardware.org/?probe=49093d0be0) | Mar 05, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [d0ee45a4b1](https://linux-hardware.org/?probe=d0ee45a4b1) | Feb 26, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [28a9d8d6a4](https://linux-hardware.org/?probe=28a9d8d6a4) | Feb 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [a93fdb0cc8](https://linux-hardware.org/?probe=a93fdb0cc8) | Feb 25, 2022 |
| Chuwi         | GemiBook Pro                | Notebook    | [37c0889ae6](https://linux-hardware.org/?probe=37c0889ae6) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [57a0f33a96](https://linux-hardware.org/?probe=57a0f33a96) | Feb 23, 2022 |
| HP            | 2140                        | Notebook    | [ad18e8d0b3](https://linux-hardware.org/?probe=ad18e8d0b3) | Feb 22, 2022 |
| HP            | 2140                        | Notebook    | [e0757f087f](https://linux-hardware.org/?probe=e0757f087f) | Feb 22, 2022 |
| eMachines     | E725 V1.03                  | Notebook    | [0f12be73fa](https://linux-hardware.org/?probe=0f12be73fa) | Feb 21, 2022 |
| Apple         | MacBookAir5,2               | Notebook    | [dc8f1e8a38](https://linux-hardware.org/?probe=dc8f1e8a38) | Feb 20, 2022 |
| Acer          | Aspire E1-532G              | Notebook    | [2ec2b8bf53](https://linux-hardware.org/?probe=2ec2b8bf53) | Feb 20, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [7f55b1fa12](https://linux-hardware.org/?probe=7f55b1fa12) | Feb 17, 2022 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [731457f46c](https://linux-hardware.org/?probe=731457f46c) | Feb 13, 2022 |
| ECS           | A75F2-M2                    | Desktop     | [0c4ea60fd5](https://linux-hardware.org/?probe=0c4ea60fd5) | Feb 12, 2022 |
| Dell          | XPS 13 9310                 | Notebook    | [64cfd66662](https://linux-hardware.org/?probe=64cfd66662) | Feb 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [980b14c09a](https://linux-hardware.org/?probe=980b14c09a) | Feb 11, 2022 |
| Acer          | Aspire 7739G                | Notebook    | [f8150dd53e](https://linux-hardware.org/?probe=f8150dd53e) | Feb 10, 2022 |
| HP            | 82DC 1100                   | All in one  | [e3a85b9aaf](https://linux-hardware.org/?probe=e3a85b9aaf) | Feb 09, 2022 |
| Gigabyte      | B85M-DS3H                   | Desktop     | [98d6451ac1](https://linux-hardware.org/?probe=98d6451ac1) | Feb 07, 2022 |
| Apple         | MacBookPro11,4              | Notebook    | [c843bc46b3](https://linux-hardware.org/?probe=c843bc46b3) | Feb 07, 2022 |
| ASRock        | Z97M Pro4                   | Desktop     | [a496090845](https://linux-hardware.org/?probe=a496090845) | Feb 01, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Foxconn       | 2A8Ch                       | Desktop     | [276caa5169](https://linux-hardware.org/?probe=276caa5169) | Jan 23, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | Notebook    | [5310be8910](https://linux-hardware.org/?probe=5310be8910) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | Notebook    | [4c77e8f334](https://linux-hardware.org/?probe=4c77e8f334) | Jan 23, 2022 |
| Acer          | Aspire F5-573G              | Notebook    | [cb60b63849](https://linux-hardware.org/?probe=cb60b63849) | Jan 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [4b3b067330](https://linux-hardware.org/?probe=4b3b067330) | Jan 21, 2022 |
| ASRock        | Z590 Pro4                   | Desktop     | [a89877d9de](https://linux-hardware.org/?probe=a89877d9de) | Jan 16, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | Notebook    | [45b3c5b85a](https://linux-hardware.org/?probe=45b3c5b85a) | Jan 16, 2022 |
| ASRock        | Z590 Pro4                   | Desktop     | [7a2453280a](https://linux-hardware.org/?probe=7a2453280a) | Jan 14, 2022 |
| ECS           | H61H2-M2                    | Desktop     | [21704ab656](https://linux-hardware.org/?probe=21704ab656) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | Desktop     | [47b4da86e2](https://linux-hardware.org/?probe=47b4da86e2) | Jan 10, 2022 |
| ASUSTek       | X750LB                      | Desktop     | [f1f247b586](https://linux-hardware.org/?probe=f1f247b586) | Jan 09, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [91548d30f5](https://linux-hardware.org/?probe=91548d30f5) | Jan 06, 2022 |
| HP            | EliteBook 2170p             | Notebook    | [4598e643d1](https://linux-hardware.org/?probe=4598e643d1) | Jan 05, 2022 |
| Lenovo        | 371C No DPK                 | All in one  | [6c4714d241](https://linux-hardware.org/?probe=6c4714d241) | Jan 04, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | Notebook    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| MSI           | H81M-P33                    | Desktop     | [0fb1d25a7d](https://linux-hardware.org/?probe=0fb1d25a7d) | Dec 30, 2021 |
| Gigabyte      | 965P-DS3                    | Desktop     | [467762be06](https://linux-hardware.org/?probe=467762be06) | Dec 29, 2021 |
| ECS           | H61H2-M2                    | Desktop     | [6f3d8856df](https://linux-hardware.org/?probe=6f3d8856df) | Dec 29, 2021 |
| Lenovo        | B590 20208                  | Notebook    | [967a9b3a38](https://linux-hardware.org/?probe=967a9b3a38) | Dec 27, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [d9c0087822](https://linux-hardware.org/?probe=d9c0087822) | Dec 26, 2021 |
| Apple         | MacBookAir3,2               | Notebook    | [9f3a7c27d9](https://linux-hardware.org/?probe=9f3a7c27d9) | Dec 24, 2021 |
| ASRock        | 870 Extreme3                | Desktop     | [d202f241ee](https://linux-hardware.org/?probe=d202f241ee) | Dec 23, 2021 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [13c79f41a6](https://linux-hardware.org/?probe=13c79f41a6) | Dec 18, 2021 |
| Intel         | DH61CR AAG14064-204         | Desktop     | [dbc555c5ad](https://linux-hardware.org/?probe=dbc555c5ad) | Dec 16, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [86eb1ce765](https://linux-hardware.org/?probe=86eb1ce765) | Dec 15, 2021 |
| Acer          | Aspire A515-55              | Notebook    | [f258cd6bb3](https://linux-hardware.org/?probe=f258cd6bb3) | Dec 12, 2021 |
| Acer          | Aspire A314-22              | Notebook    | [655c34690e](https://linux-hardware.org/?probe=655c34690e) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [eb77365d4e](https://linux-hardware.org/?probe=eb77365d4e) | Dec 11, 2021 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | Notebook    | [fe88e1083a](https://linux-hardware.org/?probe=fe88e1083a) | Dec 11, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [594becb8c9](https://linux-hardware.org/?probe=594becb8c9) | Dec 06, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [1a03b6e5c7](https://linux-hardware.org/?probe=1a03b6e5c7) | Dec 05, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [bdf4260678](https://linux-hardware.org/?probe=bdf4260678) | Dec 05, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d9019c420c](https://linux-hardware.org/?probe=d9019c420c) | Dec 04, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [dac924cd16](https://linux-hardware.org/?probe=dac924cd16) | Dec 04, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [3111a073e8](https://linux-hardware.org/?probe=3111a073e8) | Dec 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [422733b9df](https://linux-hardware.org/?probe=422733b9df) | Dec 02, 2021 |
| Lenovo        | B50-70 20384                | Notebook    | [d75361564f](https://linux-hardware.org/?probe=d75361564f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | Notebook    | [0e099c0bdd](https://linux-hardware.org/?probe=0e099c0bdd) | Dec 02, 2021 |
| Dell          | 0GDG8Y A00                  | Desktop     | [d0cf0cc443](https://linux-hardware.org/?probe=d0cf0cc443) | Dec 01, 2021 |
| Foxconn       | 2A8Ch                       | Desktop     | [1eff06a331](https://linux-hardware.org/?probe=1eff06a331) | Nov 30, 2021 |
| Foxconn       | 2A8Ch                       | Desktop     | [1f650ebd72](https://linux-hardware.org/?probe=1f650ebd72) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | Notebook    | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | Notebook    | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [b153db375f](https://linux-hardware.org/?probe=b153db375f) | Nov 29, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [ec7596ddfa](https://linux-hardware.org/?probe=ec7596ddfa) | Nov 26, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [323825e995](https://linux-hardware.org/?probe=323825e995) | Nov 24, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [659ed4999d](https://linux-hardware.org/?probe=659ed4999d) | Nov 24, 2021 |
| Dell          | Vostro 3500                 | Notebook    | [b0b04002be](https://linux-hardware.org/?probe=b0b04002be) | Nov 24, 2021 |
| HP            | EliteBook 2530p             | Notebook    | [08f1548a45](https://linux-hardware.org/?probe=08f1548a45) | Nov 23, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [515899572d](https://linux-hardware.org/?probe=515899572d) | Nov 22, 2021 |
| Dell          | Vostro 5568                 | Notebook    | [9ae3647f81](https://linux-hardware.org/?probe=9ae3647f81) | Nov 22, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [bde1fd1da2](https://linux-hardware.org/?probe=bde1fd1da2) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [8a1a3f0661](https://linux-hardware.org/?probe=8a1a3f0661) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [eace5e1302](https://linux-hardware.org/?probe=eace5e1302) | Nov 19, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [9c7eba9b77](https://linux-hardware.org/?probe=9c7eba9b77) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| Gigabyte      | GB-BRR7H-4800               | Desktop     | [c77e499435](https://linux-hardware.org/?probe=c77e499435) | Nov 13, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | Notebook    | [93e710085b](https://linux-hardware.org/?probe=93e710085b) | Nov 12, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [aa49529b6c](https://linux-hardware.org/?probe=aa49529b6c) | Nov 09, 2021 |
| Lenovo        | Legion 5 17ACH6 82K0        | Notebook    | [3af4c85553](https://linux-hardware.org/?probe=3af4c85553) | Nov 04, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [df4871ce19](https://linux-hardware.org/?probe=df4871ce19) | Nov 04, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [d59cc9fead](https://linux-hardware.org/?probe=d59cc9fead) | Nov 04, 2021 |
| ASUSTek       | X751NV                      | Notebook    | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [903ec63ceb](https://linux-hardware.org/?probe=903ec63ceb) | Nov 02, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [c7f7df5e24](https://linux-hardware.org/?probe=c7f7df5e24) | Nov 01, 2021 |
| MSI           | P55-CD53                    | Desktop     | [860bde5935](https://linux-hardware.org/?probe=860bde5935) | Oct 31, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [532a1d3d01](https://linux-hardware.org/?probe=532a1d3d01) | Oct 29, 2021 |
| MSI           | P55-CD53                    | Desktop     | [12bf811a5c](https://linux-hardware.org/?probe=12bf811a5c) | Oct 24, 2021 |
| MSI           | P55-CD53                    | Desktop     | [c1c364dbc1](https://linux-hardware.org/?probe=c1c364dbc1) | Oct 24, 2021 |
| ASUSTek       | M5A78L LE                   | Desktop     | [adf114d66e](https://linux-hardware.org/?probe=adf114d66e) | Oct 23, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [2d80988ddc](https://linux-hardware.org/?probe=2d80988ddc) | Oct 22, 2021 |
| Pegatron      | 2A73h                       | Desktop     | [dc24d5d19f](https://linux-hardware.org/?probe=dc24d5d19f) | Oct 16, 2021 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [d891006b52](https://linux-hardware.org/?probe=d891006b52) | Oct 14, 2021 |
| ASUSTek       | B85M-E                      | Desktop     | [d98b27a03c](https://linux-hardware.org/?probe=d98b27a03c) | Oct 11, 2021 |
| SHENZHEN X... | ST106                       | Notebook    | [afbb6f50c8](https://linux-hardware.org/?probe=afbb6f50c8) | Oct 11, 2021 |
| SHENZHEN X... | ST106                       | Notebook    | [5ca1710273](https://linux-hardware.org/?probe=5ca1710273) | Oct 11, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [d5199453f5](https://linux-hardware.org/?probe=d5199453f5) | Oct 04, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [068d8ff3b0](https://linux-hardware.org/?probe=068d8ff3b0) | Oct 04, 2021 |
| ASUSTek       | A58M-K                      | Desktop     | [2ca6ce79db](https://linux-hardware.org/?probe=2ca6ce79db) | Oct 03, 2021 |
| Toshiba       | Satellite P200              | Notebook    | [df46118ac3](https://linux-hardware.org/?probe=df46118ac3) | Oct 02, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [1b6bb85e6b](https://linux-hardware.org/?probe=1b6bb85e6b) | Sep 30, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [aa5e0ddd18](https://linux-hardware.org/?probe=aa5e0ddd18) | Sep 30, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [e5508ac7ab](https://linux-hardware.org/?probe=e5508ac7ab) | Sep 27, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| HP            | ProBook 4740s               | Notebook    | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| Acer          | Aspire 5250                 | Notebook    | [be1b633020](https://linux-hardware.org/?probe=be1b633020) | Sep 14, 2021 |
| Lenovo        | 371C No DPK                 | All in one  | [cd0d01d653](https://linux-hardware.org/?probe=cd0d01d653) | Sep 11, 2021 |
| Apple         | Mac-AA95B1DDAB278B95 iMa... | All in one  | [8803020fce](https://linux-hardware.org/?probe=8803020fce) | Sep 11, 2021 |
| Lenovo        | IdeaPadFlex 5 14ARE05 81... | Convertible | [1172b42b6b](https://linux-hardware.org/?probe=1172b42b6b) | Sep 10, 2021 |
| HUAWEI        | WRTB-WXX9                   | Notebook    | [1570fd5033](https://linux-hardware.org/?probe=1570fd5033) | Sep 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [104bd9a2a0](https://linux-hardware.org/?probe=104bd9a2a0) | Sep 09, 2021 |
| Lenovo        | ThinkPad E590 20NB006MSC    | Notebook    | [73c87242b9](https://linux-hardware.org/?probe=73c87242b9) | Sep 09, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [aa6b5ca915](https://linux-hardware.org/?probe=aa6b5ca915) | Sep 08, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [8b503ffd8a](https://linux-hardware.org/?probe=8b503ffd8a) | Sep 07, 2021 |
| Dell          | Latitude 5580               | Notebook    | [944d9e820d](https://linux-hardware.org/?probe=944d9e820d) | Sep 01, 2021 |
| Acer          | Aspire F5-571G              | Notebook    | [d3d0e83199](https://linux-hardware.org/?probe=d3d0e83199) | Aug 30, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | Notebook    | [44e5a5c02e](https://linux-hardware.org/?probe=44e5a5c02e) | Aug 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [06981db89b](https://linux-hardware.org/?probe=06981db89b) | Aug 20, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [a33d74d8e4](https://linux-hardware.org/?probe=a33d74d8e4) | Aug 19, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [19982a455b](https://linux-hardware.org/?probe=19982a455b) | Aug 18, 2021 |
| Acer          | Aspire E5-575G              | Notebook    | [3c4fba3670](https://linux-hardware.org/?probe=3c4fba3670) | Aug 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [f9bd04ed57](https://linux-hardware.org/?probe=f9bd04ed57) | Aug 14, 2021 |
| MSI           | A320M PRO-VH PLUS           | Desktop     | [149504315f](https://linux-hardware.org/?probe=149504315f) | Aug 10, 2021 |
| HP            | 2000                        | Notebook    | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [a319e4cbd9](https://linux-hardware.org/?probe=a319e4cbd9) | Aug 06, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [7d693f5628](https://linux-hardware.org/?probe=7d693f5628) | Aug 04, 2021 |
| Acer          | Nitro AN515-52              | Notebook    | [75944f340e](https://linux-hardware.org/?probe=75944f340e) | Aug 04, 2021 |
| Lenovo        | ThinkPad T430 2349AK2       | Notebook    | [c51aebd74f](https://linux-hardware.org/?probe=c51aebd74f) | Aug 04, 2021 |
| Gigabyte      | X399 AORUS XTREME-CF        | Desktop     | [3a2fd430f6](https://linux-hardware.org/?probe=3a2fd430f6) | Aug 03, 2021 |
| Dell          | Inspiron N5110              | Notebook    | [0283581712](https://linux-hardware.org/?probe=0283581712) | Jul 31, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [f15116c26a](https://linux-hardware.org/?probe=f15116c26a) | Jul 30, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [8297a49138](https://linux-hardware.org/?probe=8297a49138) | Jul 28, 2021 |
| Acer          | Aspire E5-774G              | Notebook    | [f60a7a3f63](https://linux-hardware.org/?probe=f60a7a3f63) | Jul 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [4759f3249f](https://linux-hardware.org/?probe=4759f3249f) | Jul 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | Notebook    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| HP            | 2000                        | Notebook    | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| ASUSTek       | X540SAA                     | Notebook    | [34bb1d000b](https://linux-hardware.org/?probe=34bb1d000b) | Jul 24, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [66ea173cb5](https://linux-hardware.org/?probe=66ea173cb5) | Jul 21, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [9a9f7c5e69](https://linux-hardware.org/?probe=9a9f7c5e69) | Jul 20, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [45694711ff](https://linux-hardware.org/?probe=45694711ff) | Jul 20, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Acer          | Aspire 6930G                | Notebook    | [0e4d09c44c](https://linux-hardware.org/?probe=0e4d09c44c) | Jul 15, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [6c3da4947f](https://linux-hardware.org/?probe=6c3da4947f) | Jul 02, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [5497b79433](https://linux-hardware.org/?probe=5497b79433) | Jul 02, 2021 |
| HP            | EliteBook 830 G5            | Notebook    | [e43bc569f4](https://linux-hardware.org/?probe=e43bc569f4) | Jul 01, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [2e6400b3fb](https://linux-hardware.org/?probe=2e6400b3fb) | Jun 30, 2021 |
| System76      | Oryx Pro                    | Notebook    | [fd3cc0ad52](https://linux-hardware.org/?probe=fd3cc0ad52) | Jun 30, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [e38bee4588](https://linux-hardware.org/?probe=e38bee4588) | Jun 24, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [b6ea706618](https://linux-hardware.org/?probe=b6ea706618) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | Notebook    | [0c5f910d8b](https://linux-hardware.org/?probe=0c5f910d8b) | Jun 21, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [79627ead32](https://linux-hardware.org/?probe=79627ead32) | Jun 14, 2021 |
| Lenovo        | ThinkPad E580 20KS005ASC    | Notebook    | [5b707f47c0](https://linux-hardware.org/?probe=5b707f47c0) | Jun 11, 2021 |
| Gigabyte      | GA-990XA-UD3                | Desktop     | [af31bae015](https://linux-hardware.org/?probe=af31bae015) | Jun 10, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [b2fe748178](https://linux-hardware.org/?probe=b2fe748178) | Jun 08, 2021 |
| Toshiba       | Satellite L750              | Notebook    | [e0c6618369](https://linux-hardware.org/?probe=e0c6618369) | Jun 07, 2021 |
| Lenovo        | ThinkPad P53 20QNZ4RBUS     | Notebook    | [3f5925d0f5](https://linux-hardware.org/?probe=3f5925d0f5) | Jun 07, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [83b3cc659a](https://linux-hardware.org/?probe=83b3cc659a) | Jun 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7d816dafe7](https://linux-hardware.org/?probe=7d816dafe7) | Jun 01, 2021 |
| Lenovo        | ThinkPad P1 20MES1T700      | Notebook    | [be5bc5605b](https://linux-hardware.org/?probe=be5bc5605b) | Jun 01, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [eb9aaa55ea](https://linux-hardware.org/?probe=eb9aaa55ea) | May 30, 2021 |
| Lenovo        | V340-17IWL 81RG             | Notebook    | [2ec41d1cf8](https://linux-hardware.org/?probe=2ec41d1cf8) | May 26, 2021 |
| Lenovo        | G40-30 80FY                 | Notebook    | [0c3e0e8293](https://linux-hardware.org/?probe=0c3e0e8293) | May 26, 2021 |
| Dell          | 06CV2N A01                  | Desktop     | [35a0afd617](https://linux-hardware.org/?probe=35a0afd617) | May 25, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [eb4e8e4cc2](https://linux-hardware.org/?probe=eb4e8e4cc2) | May 25, 2021 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [657fe689d6](https://linux-hardware.org/?probe=657fe689d6) | May 19, 2021 |
| HP            | 255 G7 Notebook PC          | Notebook    | [bfb71f53ec](https://linux-hardware.org/?probe=bfb71f53ec) | May 03, 2021 |
| Lenovo        | CRESCENTBAY 31900058 WIN... | All in one  | [84248bb07c](https://linux-hardware.org/?probe=84248bb07c) | May 03, 2021 |
| Acer          | Aspire F5-571G              | Notebook    | [5bb52c52af](https://linux-hardware.org/?probe=5bb52c52af) | Apr 30, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [2cd9e43be0](https://linux-hardware.org/?probe=2cd9e43be0) | Apr 27, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [6ab7b315e3](https://linux-hardware.org/?probe=6ab7b315e3) | Apr 24, 2021 |
| Acer          | Aspire A315-34              | Notebook    | [7e0d6ec835](https://linux-hardware.org/?probe=7e0d6ec835) | Apr 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [470c00d1c5](https://linux-hardware.org/?probe=470c00d1c5) | Apr 23, 2021 |
| Lenovo        | Z50-70 20354                | Notebook    | [fbc2a66e2b](https://linux-hardware.org/?probe=fbc2a66e2b) | Apr 22, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [eabbb41fea](https://linux-hardware.org/?probe=eabbb41fea) | Apr 20, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | Notebook    | [86927ce44d](https://linux-hardware.org/?probe=86927ce44d) | Apr 20, 2021 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | Notebook    | [92fe8bf812](https://linux-hardware.org/?probe=92fe8bf812) | Apr 20, 2021 |
| ASRock        | P45DE                       | Desktop     | [2f6b602e36](https://linux-hardware.org/?probe=2f6b602e36) | Apr 18, 2021 |
| HP            | Compaq 6710b (KL509AV)      | Notebook    | [735870e390](https://linux-hardware.org/?probe=735870e390) | Apr 16, 2021 |
| HP            | EliteBook 850 G6            | Notebook    | [7dbeb6844a](https://linux-hardware.org/?probe=7dbeb6844a) | Apr 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [24cd2670f3](https://linux-hardware.org/?probe=24cd2670f3) | Apr 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [60ef5cf4f2](https://linux-hardware.org/?probe=60ef5cf4f2) | Apr 15, 2021 |
| HP            | Compaq 6710b (KL509AV)      | Notebook    | [565cd80547](https://linux-hardware.org/?probe=565cd80547) | Apr 15, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [78550034b4](https://linux-hardware.org/?probe=78550034b4) | Apr 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [43b989fae1](https://linux-hardware.org/?probe=43b989fae1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T460 20FMS0X022    | Notebook    | [02ce254082](https://linux-hardware.org/?probe=02ce254082) | Apr 06, 2021 |
| ASRock        | Z370 Pro4                   | Desktop     | [7ad77d82ba](https://linux-hardware.org/?probe=7ad77d82ba) | Apr 03, 2021 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [b776bc7947](https://linux-hardware.org/?probe=b776bc7947) | Mar 31, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [be7b667e75](https://linux-hardware.org/?probe=be7b667e75) | Mar 27, 2021 |
| HP            | ZBook 17 G2                 | Notebook    | [45e4f9d242](https://linux-hardware.org/?probe=45e4f9d242) | Mar 24, 2021 |
| HP            | 250 G7 Notebook PC          | Notebook    | [ba238dbe29](https://linux-hardware.org/?probe=ba238dbe29) | Mar 21, 2021 |
| Dell          | Inspiron 5551               | Notebook    | [3b91b6e49f](https://linux-hardware.org/?probe=3b91b6e49f) | Mar 20, 2021 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [6e5e0c9ef4](https://linux-hardware.org/?probe=6e5e0c9ef4) | Mar 19, 2021 |
| MSI           | Z390-A PRO                  | Desktop     | [12566ee726](https://linux-hardware.org/?probe=12566ee726) | Mar 10, 2021 |
| Gigabyte      | G1.Sniper Z87               | Desktop     | [c9a3501b03](https://linux-hardware.org/?probe=c9a3501b03) | Mar 02, 2021 |
| ASRock        | FM2A75M-DGS                 | Desktop     | [72c1ab0b9b](https://linux-hardware.org/?probe=72c1ab0b9b) | Mar 01, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [24a672b8ac](https://linux-hardware.org/?probe=24a672b8ac) | Feb 25, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [8f0d10afce](https://linux-hardware.org/?probe=8f0d10afce) | Feb 24, 2021 |
| HP            | ProBook 455 G7              | Notebook    | [ffdabc425b](https://linux-hardware.org/?probe=ffdabc425b) | Feb 16, 2021 |
| ASRock        | Z87 Extreme4                | Desktop     | [081e14044d](https://linux-hardware.org/?probe=081e14044d) | Feb 13, 2021 |
| Dell          | XPS 13 9380                 | Notebook    | [69f9ebe58b](https://linux-hardware.org/?probe=69f9ebe58b) | Feb 11, 2021 |
| Acer          | Aspire ES1-532G             | Notebook    | [f01b666f99](https://linux-hardware.org/?probe=f01b666f99) | Feb 09, 2021 |
| Dell          | 0NNGP2 A00                  | Desktop     | [9be58392b6](https://linux-hardware.org/?probe=9be58392b6) | Feb 08, 2021 |
| Acer          | Aspire A315-41              | Notebook    | [d0648fe1f7](https://linux-hardware.org/?probe=d0648fe1f7) | Feb 07, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [3062914f46](https://linux-hardware.org/?probe=3062914f46) | Feb 07, 2021 |
| Dell          | 0J37VM A01                  | Desktop     | [34e1267a80](https://linux-hardware.org/?probe=34e1267a80) | Feb 07, 2021 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [eee7c1f592](https://linux-hardware.org/?probe=eee7c1f592) | Feb 03, 2021 |
| HP            | 250 G5 Notebook PC          | Notebook    | [a541bcd390](https://linux-hardware.org/?probe=a541bcd390) | Feb 02, 2021 |
| ASRock        | ConRoe1333-D667             | Desktop     | [54121172b8](https://linux-hardware.org/?probe=54121172b8) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | Desktop     | [28cb4726bb](https://linux-hardware.org/?probe=28cb4726bb) | Jan 31, 2021 |
| Gigabyte      | B450 GAMING X               | Desktop     | [0b4b751863](https://linux-hardware.org/?probe=0b4b751863) | Jan 31, 2021 |
| ASUSTek       | F5N                         | Notebook    | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| ASRock        | X570M Pro4                  | Desktop     | [9cd91004ab](https://linux-hardware.org/?probe=9cd91004ab) | Jan 24, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [9afb5c207a](https://linux-hardware.org/?probe=9afb5c207a) | Jan 23, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [482bc5334f](https://linux-hardware.org/?probe=482bc5334f) | Jan 22, 2021 |
| MSI           | B450 TOMAHAWK               | Desktop     | [943284255a](https://linux-hardware.org/?probe=943284255a) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [df34a7d718](https://linux-hardware.org/?probe=df34a7d718) | Jan 20, 2021 |
| Gigabyte      | F2A78M-DS2                  | Desktop     | [0d8e905a30](https://linux-hardware.org/?probe=0d8e905a30) | Jan 16, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [17f2fe84cb](https://linux-hardware.org/?probe=17f2fe84cb) | Jan 14, 2021 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [9b72f3a82b](https://linux-hardware.org/?probe=9b72f3a82b) | Jan 11, 2021 |
| Dell          | Latitude E6430              | Notebook    | [939c4dbad4](https://linux-hardware.org/?probe=939c4dbad4) | Jan 10, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | Notebook    | [1f95699c20](https://linux-hardware.org/?probe=1f95699c20) | Jan 09, 2021 |
| Lenovo        | ThinkPad T61 6458AU9        | Notebook    | [5350b0523f](https://linux-hardware.org/?probe=5350b0523f) | Jan 08, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [9b176fb8e5](https://linux-hardware.org/?probe=9b176fb8e5) | Jan 04, 2021 |
| Lenovo        | G710 20252                  | Notebook    | [db68ccb5de](https://linux-hardware.org/?probe=db68ccb5de) | Jan 04, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [e2fa1223c4](https://linux-hardware.org/?probe=e2fa1223c4) | Jan 03, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [db7dfe41a5](https://linux-hardware.org/?probe=db7dfe41a5) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | Desktop     | [2ca3b4e129](https://linux-hardware.org/?probe=2ca3b4e129) | Jan 03, 2021 |
| MSI           | P67A-GD53/2.0               | Desktop     | [638a245f5f](https://linux-hardware.org/?probe=638a245f5f) | Jan 03, 2021 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [15160d8a87](https://linux-hardware.org/?probe=15160d8a87) | Jan 02, 2021 |
| Dell          | Vostro 3578                 | Notebook    | [a2e6574ba4](https://linux-hardware.org/?probe=a2e6574ba4) | Dec 30, 2020 |
| HP            | 18EA                        | Desktop     | [67e2e927b6](https://linux-hardware.org/?probe=67e2e927b6) | Dec 27, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [bb46f7172f](https://linux-hardware.org/?probe=bb46f7172f) | Dec 27, 2020 |
| Gigabyte      | GA-MA770-UD3                | Desktop     | [120e788567](https://linux-hardware.org/?probe=120e788567) | Dec 24, 2020 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [f6ef9c50ed](https://linux-hardware.org/?probe=f6ef9c50ed) | Dec 23, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [03b737b966](https://linux-hardware.org/?probe=03b737b966) | Dec 23, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [d886327463](https://linux-hardware.org/?probe=d886327463) | Dec 22, 2020 |
| ASRock        | Z370 Pro4                   | Desktop     | [e6df8b78b5](https://linux-hardware.org/?probe=e6df8b78b5) | Dec 21, 2020 |
| Acer          | Aspire A315-21              | Notebook    | [4c807db430](https://linux-hardware.org/?probe=4c807db430) | Dec 19, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [fb469bd0dc](https://linux-hardware.org/?probe=fb469bd0dc) | Dec 17, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [4e7620198d](https://linux-hardware.org/?probe=4e7620198d) | Dec 15, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [0a6542f4b3](https://linux-hardware.org/?probe=0a6542f4b3) | Dec 12, 2020 |
| Acer          | Aspire 7739G                | Notebook    | [9d81c58373](https://linux-hardware.org/?probe=9d81c58373) | Dec 12, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [9b07c5b4a5](https://linux-hardware.org/?probe=9b07c5b4a5) | Dec 06, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [3cc104d803](https://linux-hardware.org/?probe=3cc104d803) | Dec 05, 2020 |
| Lenovo        | ThinkPad W540 20BHS04K00    | Notebook    | [c429b95a44](https://linux-hardware.org/?probe=c429b95a44) | Dec 03, 2020 |
| HP            | 2000                        | Notebook    | [27fed77b24](https://linux-hardware.org/?probe=27fed77b24) | Dec 02, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [82adf2d707](https://linux-hardware.org/?probe=82adf2d707) | Dec 01, 2020 |
| Acer          | Aspire ES1-732              | Notebook    | [243f8b5015](https://linux-hardware.org/?probe=243f8b5015) | Nov 29, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | Notebook    | [24fe3f5f2f](https://linux-hardware.org/?probe=24fe3f5f2f) | Nov 25, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [49c3ecb298](https://linux-hardware.org/?probe=49c3ecb298) | Nov 24, 2020 |
| Acer          | Aspire ES1-732              | Notebook    | [9a62fb8fe7](https://linux-hardware.org/?probe=9a62fb8fe7) | Nov 21, 2020 |
| HP            | ProBook 640 G1              | Notebook    | [eed4ff0229](https://linux-hardware.org/?probe=eed4ff0229) | Nov 19, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | Notebook    | [9c165b5f59](https://linux-hardware.org/?probe=9c165b5f59) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [50ddfd361b](https://linux-hardware.org/?probe=50ddfd361b) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [7e3892e9b1](https://linux-hardware.org/?probe=7e3892e9b1) | Nov 09, 2020 |
| Acer          | Aspire E5-771G              | Notebook    | [9d967e969d](https://linux-hardware.org/?probe=9d967e969d) | Nov 01, 2020 |
| ASRock        | N68-S3 UCC                  | Desktop     | [b75cfae4a3](https://linux-hardware.org/?probe=b75cfae4a3) | Nov 01, 2020 |
| Acer          | Aspire V5-531               | Notebook    | [8eb2cc2336](https://linux-hardware.org/?probe=8eb2cc2336) | Nov 01, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | Notebook    | [e6cd5153b1](https://linux-hardware.org/?probe=e6cd5153b1) | Oct 31, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [c3c04c52ab](https://linux-hardware.org/?probe=c3c04c52ab) | Oct 26, 2020 |
| HP            | Laptop 15-bs0xx             | Notebook    | [57db732909](https://linux-hardware.org/?probe=57db732909) | Oct 25, 2020 |
| Nvidia        | Tegra                       | Soc         | [ef24e8c128](https://linux-hardware.org/?probe=ef24e8c128) | Oct 23, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | Notebook    | [8d0c1b4422](https://linux-hardware.org/?probe=8d0c1b4422) | Oct 22, 2020 |
| Nvidia        | Tegra                       | Soc         | [d3a4ce2fd2](https://linux-hardware.org/?probe=d3a4ce2fd2) | Oct 22, 2020 |
| Nvidia        | Tegra                       | Soc         | [d3bdc7437e](https://linux-hardware.org/?probe=d3bdc7437e) | Oct 22, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [36db0ea3d4](https://linux-hardware.org/?probe=36db0ea3d4) | Oct 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [38c87efbca](https://linux-hardware.org/?probe=38c87efbca) | Oct 16, 2020 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [ff7ecd0641](https://linux-hardware.org/?probe=ff7ecd0641) | Oct 15, 2020 |
| Dell          | XPS 15 7590                 | Notebook    | [65c065a968](https://linux-hardware.org/?probe=65c065a968) | Oct 09, 2020 |
| HP            | EliteBook 850 G5            | Notebook    | [0d11552658](https://linux-hardware.org/?probe=0d11552658) | Oct 07, 2020 |
| Pegatron      | 2A94h                       | Desktop     | [668c4bbb8b](https://linux-hardware.org/?probe=668c4bbb8b) | Oct 06, 2020 |
| Toshiba       | Satellite C55-A-1M7         | Notebook    | [174d6c4c6d](https://linux-hardware.org/?probe=174d6c4c6d) | Oct 06, 2020 |
| Dell          | Vostro 3578                 | Notebook    | [7904981ea3](https://linux-hardware.org/?probe=7904981ea3) | Oct 05, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [b098cfc85e](https://linux-hardware.org/?probe=b098cfc85e) | Sep 30, 2020 |
| Dell          | XPS 15 9570                 | Notebook    | [dacb39a2ba](https://linux-hardware.org/?probe=dacb39a2ba) | Sep 30, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [df11954c4f](https://linux-hardware.org/?probe=df11954c4f) | Sep 28, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [b4807eff1e](https://linux-hardware.org/?probe=b4807eff1e) | Sep 28, 2020 |
| HP            | ProBook 450 G7              | Notebook    | [9cc971b2e7](https://linux-hardware.org/?probe=9cc971b2e7) | Sep 28, 2020 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [8220732bda](https://linux-hardware.org/?probe=8220732bda) | Sep 28, 2020 |
| ASUSTek       | M5A78L LE                   | Desktop     | [7f4940b41c](https://linux-hardware.org/?probe=7f4940b41c) | Sep 28, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [062f436dfa](https://linux-hardware.org/?probe=062f436dfa) | Sep 27, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [181e06ec2e](https://linux-hardware.org/?probe=181e06ec2e) | Sep 26, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [d7391de736](https://linux-hardware.org/?probe=d7391de736) | Sep 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [ea8e216968](https://linux-hardware.org/?probe=ea8e216968) | Sep 20, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | Notebook    | [d93882e0b2](https://linux-hardware.org/?probe=d93882e0b2) | Sep 20, 2020 |
| ASRock        | N68-S3 UCC                  | Desktop     | [42ed26b195](https://linux-hardware.org/?probe=42ed26b195) | Sep 19, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [fa0ec4aeae](https://linux-hardware.org/?probe=fa0ec4aeae) | Sep 17, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | Notebook    | [eeb54854f8](https://linux-hardware.org/?probe=eeb54854f8) | Sep 12, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | Notebook    | [a8d6bb1865](https://linux-hardware.org/?probe=a8d6bb1865) | Sep 12, 2020 |
| Dell          | Latitude 7390               | Notebook    | [b8019896d0](https://linux-hardware.org/?probe=b8019896d0) | Sep 10, 2020 |
| ASUSTek       | M4A77                       | Desktop     | [d076f8fe03](https://linux-hardware.org/?probe=d076f8fe03) | Sep 08, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [b80f12df10](https://linux-hardware.org/?probe=b80f12df10) | Sep 07, 2020 |
| ASRock        | Z87E-ITX                    | Desktop     | [d1095a7a24](https://linux-hardware.org/?probe=d1095a7a24) | Sep 05, 2020 |
| ASRock        | N68-S3 UCC                  | Desktop     | [a2d99d11fc](https://linux-hardware.org/?probe=a2d99d11fc) | Aug 30, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [1c2eaa2346](https://linux-hardware.org/?probe=1c2eaa2346) | Aug 23, 2020 |
| HP            | 2129                        | Desktop     | [d1eda00971](https://linux-hardware.org/?probe=d1eda00971) | Aug 20, 2020 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [1b2d8402af](https://linux-hardware.org/?probe=1b2d8402af) | Aug 17, 2020 |
| HP            | EliteBook 850 G6            | Notebook    | [4458c2267f](https://linux-hardware.org/?probe=4458c2267f) | Aug 17, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [3a826b3414](https://linux-hardware.org/?probe=3a826b3414) | Aug 13, 2020 |
| HP            | ProBook 430 G3              | Notebook    | [e28ccfa01e](https://linux-hardware.org/?probe=e28ccfa01e) | Aug 11, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [9bf9387073](https://linux-hardware.org/?probe=9bf9387073) | Aug 05, 2020 |
| ASUSTek       | GL752VW                     | Notebook    | [26fc584896](https://linux-hardware.org/?probe=26fc584896) | Aug 02, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [c670b35249](https://linux-hardware.org/?probe=c670b35249) | Jul 29, 2020 |
| Lenovo        | Y50-70 20378                | Notebook    | [842efe3170](https://linux-hardware.org/?probe=842efe3170) | Jul 28, 2020 |
| Dell          | XPS 13 9360                 | Notebook    | [743f8b4f98](https://linux-hardware.org/?probe=743f8b4f98) | Jul 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [34213d655c](https://linux-hardware.org/?probe=34213d655c) | Jul 24, 2020 |
| Lenovo        | IdeaCentre Stick 300-01I... | Stick pc    | [28b902c9b7](https://linux-hardware.org/?probe=28b902c9b7) | Jul 21, 2020 |
| Dell          | Precision 5530              | Notebook    | [30c2f2561e](https://linux-hardware.org/?probe=30c2f2561e) | Jul 20, 2020 |
| ASUSTek       | X751NV                      | Notebook    | [f94768a5e6](https://linux-hardware.org/?probe=f94768a5e6) | Jul 15, 2020 |
| HP            | Compaq 6820s                | Notebook    | [f5b6aa7190](https://linux-hardware.org/?probe=f5b6aa7190) | Jul 15, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [ce78055795](https://linux-hardware.org/?probe=ce78055795) | Jul 14, 2020 |
| Gigabyte      | G41M-Combo                  | Desktop     | [2f3657530f](https://linux-hardware.org/?probe=2f3657530f) | Jun 29, 2020 |
| ASUSTek       | B85M-E                      | Desktop     | [e46352dec8](https://linux-hardware.org/?probe=e46352dec8) | Jun 28, 2020 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [ac52acb928](https://linux-hardware.org/?probe=ac52acb928) | Jun 24, 2020 |
| Notebook      | MAM2080                     | Notebook    | [7464ed3c9d](https://linux-hardware.org/?probe=7464ed3c9d) | Jun 23, 2020 |
| ASUSTek       | X751NV                      | Notebook    | [08c5775f88](https://linux-hardware.org/?probe=08c5775f88) | Jun 22, 2020 |
| Notebook      | MAM2080                     | Notebook    | [7321ecab2d](https://linux-hardware.org/?probe=7321ecab2d) | Jun 21, 2020 |
| ASRock        | H97M Pro4                   | Desktop     | [31f3732dc9](https://linux-hardware.org/?probe=31f3732dc9) | Jun 19, 2020 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | Notebook    | [c0c727bcb0](https://linux-hardware.org/?probe=c0c727bcb0) | Jun 18, 2020 |
| ASUSTek       | X540UA                      | Notebook    | [7f0afeb60e](https://linux-hardware.org/?probe=7f0afeb60e) | Jun 16, 2020 |
| HP            | 255 G7 Notebook PC          | Notebook    | [639b8bd2bc](https://linux-hardware.org/?probe=639b8bd2bc) | Jun 14, 2020 |
| Acer          | Aspire 7720                 | Notebook    | [77e3ae41d8](https://linux-hardware.org/?probe=77e3ae41d8) | Jun 10, 2020 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [2c0b3072ac](https://linux-hardware.org/?probe=2c0b3072ac) | Jun 09, 2020 |
| Acer          | Swift SF314-52              | Notebook    | [fa00080df2](https://linux-hardware.org/?probe=fa00080df2) | Jun 06, 2020 |
| Lenovo        | G710 20252                  | Notebook    | [eff12f397f](https://linux-hardware.org/?probe=eff12f397f) | Jun 06, 2020 |
| Gigabyte      | G31MX-S2                    | Desktop     | [7da6752573](https://linux-hardware.org/?probe=7da6752573) | May 31, 2020 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [d77566be76](https://linux-hardware.org/?probe=d77566be76) | May 31, 2020 |
| Gigabyte      | G31MX-S2                    | Desktop     | [5472c53dca](https://linux-hardware.org/?probe=5472c53dca) | May 31, 2020 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [06f88752e5](https://linux-hardware.org/?probe=06f88752e5) | May 31, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [15cf043276](https://linux-hardware.org/?probe=15cf043276) | May 31, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [89935abc60](https://linux-hardware.org/?probe=89935abc60) | May 31, 2020 |
| AMI           | Cherry Trail CR             | Mini pc     | [bbb1f5819f](https://linux-hardware.org/?probe=bbb1f5819f) | May 31, 2020 |
| ASRock        | H81M-DGS R2.0               | Desktop     | [26a9c7f62c](https://linux-hardware.org/?probe=26a9c7f62c) | May 30, 2020 |
| Lenovo        | G500 20236                  | Notebook    | [689825038f](https://linux-hardware.org/?probe=689825038f) | May 25, 2020 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [e3042f4583](https://linux-hardware.org/?probe=e3042f4583) | May 24, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [3ae92d178c](https://linux-hardware.org/?probe=3ae92d178c) | May 21, 2020 |
| ASUSTek       | P8H77-V LE                  | Desktop     | [e6f20d976d](https://linux-hardware.org/?probe=e6f20d976d) | May 17, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [9e3950795e](https://linux-hardware.org/?probe=9e3950795e) | May 17, 2020 |
| Toshiba       | Satellite L50-B             | Notebook    | [0a7ccd88d0](https://linux-hardware.org/?probe=0a7ccd88d0) | May 15, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Croatia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 72        | 8.33%   |
| Ubuntu 22.04                 | 46        | 5.32%   |
| Ubuntu 18.04                 | 33        | 3.82%   |
| Debian 11                    | 22        | 2.55%   |
| Arch Rolling                 | 21        | 2.43%   |
| Ubuntu 24.04                 | 19        | 2.2%    |
| Debian 12                    | 16        | 1.85%   |
| OpenMandriva 4.3             | 14        | 1.62%   |
| OpenMandriva 24.12           | 14        | 1.62%   |
| Zorin 16                     | 13        | 1.5%    |
| Pop!_OS 22.04                | 13        | 1.5%    |
| OpenMandriva 25.90           | 12        | 1.39%   |
| Fedora 40                    | 12        | 1.39%   |
| Manjaro                      | 11        | 1.27%   |
| Linux Mint 20.3              | 11        | 1.27%   |
| Linux Mint 20.2              | 11        | 1.27%   |
| Fedora 41                    | 11        | 1.27%   |
| Fedora 39                    | 11        | 1.27%   |
| ArcoLinux Rolling            | 11        | 1.27%   |
| openSUSE Tumbleweed-XXXXXXXX | 10        | 1.16%   |
| Fedora 38                    | 10        | 1.16%   |
| Zorin 17                     | 9         | 1.04%   |
| Ubuntu 18.10                 | 9         | 1.04%   |
| Pop!_OS 21.04                | 9         | 1.04%   |
| OpenMandriva 6.0             | 8         | 0.93%   |
| Linux Mint 21.1              | 8         | 0.93%   |
| Ubuntu 21.04                 | 7         | 0.81%   |
| Pop!_OS 20.04                | 7         | 0.81%   |
| OpenMandriva 4.2             | 7         | 0.81%   |
| OpenMandriva 25.06           | 7         | 0.81%   |
| OpenMandriva 23.08           | 7         | 0.81%   |
| Fedora 36                    | 7         | 0.81%   |
| Ubuntu 24.10                 | 6         | 0.69%   |
| Ubuntu 19.10                 | 6         | 0.69%   |
| Pop!_OS 21.10                | 6         | 0.69%   |
| Pop!_OS 20.10                | 6         | 0.69%   |
| OpenMandriva 5.0             | 6         | 0.69%   |
| KDE neon 22.04               | 6         | 0.69%   |
| KDE neon 20.04               | 6         | 0.69%   |
| EndeavourOS Rolling          | 6         | 0.69%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu             | 207       | 26.07%  |
| OpenMandriva       | 97        | 12.22%  |
| Fedora             | 67        | 8.44%   |
| Linux Mint         | 59        | 7.43%   |
| Debian             | 47        | 5.92%   |
| Pop!_OS            | 41        | 5.16%   |
| Manjaro            | 31        | 3.9%    |
| Zorin              | 30        | 3.78%   |
| Arch               | 25        | 3.15%   |
| Endless            | 24        | 3.02%   |
| Kubuntu            | 20        | 2.52%   |
| openSUSE           | 15        | 1.89%   |
| KDE neon           | 13        | 1.64%   |
| ArcoLinux          | 12        | 1.51%   |
| ROSA               | 10        | 1.26%   |
| Bazzite            | 8         | 1.01%   |
| Ubuntu MATE        | 7         | 0.88%   |
| Elementary         | 7         | 0.88%   |
| Xubuntu            | 6         | 0.76%   |
| LMDE               | 6         | 0.76%   |
| Kali               | 6         | 0.76%   |
| EndeavourOS        | 6         | 0.76%   |
| MX                 | 5         | 0.63%   |
| Ubuntu Budgie      | 4         | 0.5%    |
| Nobara             | 4         | 0.5%    |
| Gentoo             | 4         | 0.5%    |
| Garuda Linux       | 4         | 0.5%    |
| Ubuntu Unity       | 3         | 0.38%   |
| CentOS             | 3         | 0.38%   |
| CachyOS            | 3         | 0.38%   |
| Rocky Linux        | 2         | 0.25%   |
| Raspbian           | 2         | 0.25%   |
| Q4OS               | 2         | 0.25%   |
| Lubuntu            | 2         | 0.25%   |
| LinuxFX            | 2         | 0.25%   |
| Xero               | 1         | 0.13%   |
| SteamOS            | 1         | 0.13%   |
| Parrot             | 1         | 0.13%   |
| NixOS              | 1         | 0.13%   |
| Fedora-asahi-remix | 1         | 0.13%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 6.14.2-desktop-3omv2590  | 25        | 2.68%   |
| 5.16.7-desktop-1omv4003  | 14        | 1.5%    |
| 6.12.1-desktop-1omv2490  | 9         | 0.96%   |
| 6.8.0-51-generic         | 8         | 0.86%   |
| 5.4.0-42-generic         | 8         | 0.86%   |
| 5.11.0-38-generic        | 8         | 0.86%   |
| 6.6.2-desktop-1omv2390   | 7         | 0.75%   |
| 6.4.11-desktop-1omv2390  | 7         | 0.75%   |
| 5.10.14-desktop-1omv4002 | 7         | 0.75%   |
| 6.8.0-47-generic         | 6         | 0.64%   |
| 6.12.9-desktop-1omv2490  | 6         | 0.64%   |
| 5.8.0-14-generic         | 6         | 0.64%   |
| 5.4.0-58-generic         | 6         | 0.64%   |
| 5.3.0-28-generic         | 6         | 0.64%   |
| 5.11.0-7620-generic      | 6         | 0.64%   |
| 6.8.0-41-generic         | 5         | 0.54%   |
| 5.4.0-91-generic         | 5         | 0.54%   |
| 5.4.0-48-generic         | 5         | 0.54%   |
| 5.4.0-37-generic         | 5         | 0.54%   |
| 5.11.0-41-generic        | 5         | 0.54%   |
| 6.5.0-28-generic         | 4         | 0.43%   |
| 6.5.0-26-generic         | 4         | 0.43%   |
| 6.12.6-desktop-1omv2490  | 4         | 0.43%   |
| 5.8.0-59-generic         | 4         | 0.43%   |
| 5.8.0-48-generic         | 4         | 0.43%   |
| 5.4.0-52-generic         | 4         | 0.43%   |
| 5.3.0-26-generic         | 4         | 0.43%   |
| 5.15.0-58-generic        | 4         | 0.43%   |
| 5.15.0-56-generic        | 4         | 0.43%   |
| 5.13.0-30-generic        | 4         | 0.43%   |
| 5.11.0-40-generic        | 4         | 0.43%   |
| 4.18.0-10-generic        | 4         | 0.43%   |
| 6.8.0-45-generic         | 3         | 0.32%   |
| 6.2.9-300.fc38.x86_64    | 3         | 0.32%   |
| 6.2.6-desktop-1omv2390   | 3         | 0.32%   |
| 6.2.6-76060206-generic   | 3         | 0.32%   |
| 6.2.0-39-generic         | 3         | 0.32%   |
| 6.2.0-26-generic         | 3         | 0.32%   |
| 6.14.0-29-generic        | 3         | 0.32%   |
| 6.14.0-15-generic        | 3         | 0.32%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 89        | 9.97%   |
| 5.15.0  | 51        | 5.71%   |
| 5.11.0  | 48        | 5.38%   |
| 6.8.0   | 36        | 4.03%   |
| 6.14.2  | 26        | 2.91%   |
| 5.8.0   | 26        | 2.91%   |
| 4.15.0  | 26        | 2.91%   |
| 5.3.0   | 24        | 2.69%   |
| 5.13.0  | 24        | 2.69%   |
| 6.1.0   | 20        | 2.24%   |
| 5.10.0  | 20        | 2.24%   |
| 4.18.0  | 20        | 2.24%   |
| 6.14.0  | 17        | 1.9%    |
| 5.19.0  | 17        | 1.9%    |
| 6.5.0   | 15        | 1.68%   |
| 5.16.7  | 15        | 1.68%   |
| 5.0.0   | 14        | 1.57%   |
| 6.2.0   | 13        | 1.46%   |
| 6.11.0  | 11        | 1.23%   |
| 6.12.1  | 10        | 1.12%   |
| 6.4.11  | 8         | 0.9%    |
| 6.6.2   | 7         | 0.78%   |
| 6.2.6   | 7         | 0.78%   |
| 6.12.9  | 7         | 0.78%   |
| 5.10.14 | 7         | 0.78%   |
| 4.19.0  | 6         | 0.67%   |
| 6.17.7  | 5         | 0.56%   |
| 6.12.6  | 5         | 0.56%   |
| 6.1.1   | 5         | 0.56%   |
| 5.14.0  | 5         | 0.56%   |
| 6.17.8  | 4         | 0.45%   |
| 6.10.6  | 4         | 0.45%   |
| 5.9.16  | 4         | 0.45%   |
| 5.16.11 | 4         | 0.45%   |
| 5.12.4  | 4         | 0.45%   |
| 6.9.3   | 3         | 0.34%   |
| 6.8.7   | 3         | 0.34%   |
| 6.5.9   | 3         | 0.34%   |
| 6.2.9   | 3         | 0.34%   |
| 6.17.0  | 3         | 0.34%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 96        | 10.91%  |
| 5.15    | 68        | 7.73%   |
| 5.11    | 56        | 6.36%   |
| 6.14    | 50        | 5.68%   |
| 6.8     | 47        | 5.34%   |
| 6.12    | 38        | 4.32%   |
| 5.10    | 37        | 4.2%    |
| 6.1     | 33        | 3.75%   |
| 6.2     | 31        | 3.52%   |
| 5.8     | 30        | 3.41%   |
| 5.3     | 28        | 3.18%   |
| 5.13    | 27        | 3.07%   |
| 4.15    | 26        | 2.95%   |
| 6.5     | 25        | 2.84%   |
| 5.19    | 25        | 2.84%   |
| 5.16    | 23        | 2.61%   |
| 6.6     | 21        | 2.39%   |
| 6.11    | 21        | 2.39%   |
| 4.18    | 20        | 2.27%   |
| 5.0     | 15        | 1.7%    |
| 6.17    | 14        | 1.59%   |
| 6.4     | 12        | 1.36%   |
| 6.13    | 11        | 1.25%   |
| 6.10    | 11        | 1.25%   |
| 6.0     | 11        | 1.25%   |
| 6.9     | 10        | 1.14%   |
| 6.7     | 9         | 1.02%   |
| 5.9     | 9         | 1.02%   |
| 5.14    | 9         | 1.02%   |
| 5.18    | 8         | 0.91%   |
| 5.17    | 8         | 0.91%   |
| 4.9     | 6         | 0.68%   |
| 4.19    | 6         | 0.68%   |
| 6.16    | 5         | 0.57%   |
| 5.6     | 5         | 0.57%   |
| 5.12    | 5         | 0.57%   |
| 6.3     | 4         | 0.45%   |
| 6.15    | 4         | 0.45%   |
| 5.7     | 3         | 0.34%   |
| 5.5     | 2         | 0.23%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 752       | 97.79%  |
| i686    | 10        | 1.3%    |
| aarch64 | 5         | 0.65%   |
| armv7l  | 2         | 0.26%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 343       | 42.66%  |
| KDE5            | 129       | 16.04%  |
| KDE6            | 76        | 9.45%   |
| Unknown         | 76        | 9.45%   |
| X-Cinnamon      | 50        | 6.22%   |
| XFCE            | 36        | 4.48%   |
| MATE            | 14        | 1.74%   |
| KDE             | 13        | 1.62%   |
| Cinnamon        | 13        | 1.62%   |
| LXQt            | 10        | 1.24%   |
| Pantheon        | 6         | 0.75%   |
| KDE4            | 6         | 0.75%   |
| GNOME Flashback | 5         | 0.62%   |
| Budgie          | 5         | 0.62%   |
| LXDE            | 4         | 0.5%    |
| DWM             | 4         | 0.5%    |
| Unity           | 3         | 0.37%   |
| Openbox         | 2         | 0.25%   |
| i3              | 2         | 0.25%   |
| ubuntu          | 1         | 0.12%   |
| Trinity         | 1         | 0.12%   |
| GNUstep         | 1         | 0.12%   |
| Endless:GNOME   | 1         | 0.12%   |
| dk              | 1         | 0.12%   |
| Deepin          | 1         | 0.12%   |
| bspwm           | 1         | 0.12%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 519       | 64.07%  |
| Wayland | 232       | 28.64%  |
| Unknown | 40        | 4.94%   |
| Tty     | 19        | 2.35%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 326       | 41.06%  |
| SDDM    | 169       | 21.28%  |
| GDM3    | 103       | 12.97%  |
| GDM     | 94        | 11.84%  |
| LightDM | 83        | 10.45%  |
| TDM     | 15        | 1.89%   |
| KDM     | 3         | 0.38%   |
| Ly      | 1         | 0.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 481       | 61.12%  |
| hr_HR   | 150       | 19.06%  |
| Unknown | 69        | 8.77%   |
| en_GB   | 52        | 6.61%   |
| C       | 14        | 1.78%   |
| de_DE   | 8         | 1.02%   |
| en_CA   | 2         | 0.25%   |
| ru_RU   | 1         | 0.13%   |
| POSIX   | 1         | 0.13%   |
| pl_PL   | 1         | 0.13%   |
| nl_BE   | 1         | 0.13%   |
| nb_NO   | 1         | 0.13%   |
| it_IT   | 1         | 0.13%   |
| hr_BA   | 1         | 0.13%   |
| fr_FR   | 1         | 0.13%   |
| en_DE   | 1         | 0.13%   |
| en_150  | 1         | 0.13%   |
| bs_BA   | 1         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 442       | 56.23%  |
| BIOS | 344       | 43.77%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 543       | 68.39%  |
| Btrfs   | 115       | 14.48%  |
| Overlay | 58        | 7.3%    |
| Tmpfs   | 32        | 4.03%   |
| Unknown | 21        | 2.64%   |
| Xfs     | 13        | 1.64%   |
| Zfs     | 10        | 1.26%   |
| Jfs     | 1         | 0.13%   |
| Ext2    | 1         | 0.13%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 384       | 48.98%  |
| Unknown | 330       | 42.09%  |
| MBR     | 70        | 8.93%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 684       | 86.8%   |
| Yes       | 104       | 13.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 572       | 72.87%  |
| Yes       | 213       | 27.13%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| Lenovo                               | 143       | 18.6%   |
| ASUSTek Computer                     | 133       | 17.3%   |
| Hewlett-Packard                      | 121       | 15.73%  |
| Acer                                 | 73        | 9.49%   |
| ASRock                               | 56        | 7.28%   |
| Dell                                 | 53        | 6.89%   |
| Gigabyte Technology                  | 52        | 6.76%   |
| MSI                                  | 25        | 3.25%   |
| Apple                                | 14        | 1.82%   |
| Intel                                | 11        | 1.43%   |
| Toshiba                              | 10        | 1.3%    |
| TUXEDO                               | 6         | 0.78%   |
| Unknown                              | 6         | 0.78%   |
| Tactus                               | 5         | 0.65%   |
| Pegatron                             | 5         | 0.65%   |
| Samsung Electronics                  | 4         | 0.52%   |
| Raspberry Pi Foundation              | 4         | 0.52%   |
| HUAWEI                               | 4         | 0.52%   |
| Fujitsu Siemens                      | 4         | 0.52%   |
| eMachines                            | 4         | 0.52%   |
| ECS                                  | 3         | 0.39%   |
| Timi                                 | 2         | 0.26%   |
| Supermicro                           | 2         | 0.26%   |
| Shenzhen Meigao Electronic Equipment | 2         | 0.26%   |
| Schenker                             | 2         | 0.26%   |
| Fujitsu                              | 2         | 0.26%   |
| WinFast                              | 1         | 0.13%   |
| Valve                                | 1         | 0.13%   |
| System76                             | 1         | 0.13%   |
| Sony                                 | 1         | 0.13%   |
| SHENZHEN X&F TECHNOLOGY              | 1         | 0.13%   |
| RUNING                               | 1         | 0.13%   |
| Razer                                | 1         | 0.13%   |
| Pretech                              | 1         | 0.13%   |
| Nvidia                               | 1         | 0.13%   |
| Notebook                             | 1         | 0.13%   |
| Medion                               | 1         | 0.13%   |
| MAXSUN                               | 1         | 0.13%   |
| HPE                                  | 1         | 0.13%   |
| GEEKOM                               | 1         | 0.13%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                              | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| HP Laptop 15-fc0xxx                               | 9         | 1.17%   |
| Unknown                                           | 8         | 1.04%   |
| ASUS All Series                                   | 6         | 0.78%   |
| Tactus GeoBook 140                                | 5         | 0.65%   |
| ASRock B450M-HDV R4.0                             | 5         | 0.65%   |
| TUXEDO InfinityBook Pro AMD Gen9                  | 4         | 0.52%   |
| Acer Aspire A315-21                               | 4         | 0.52%   |
| Lenovo Legion 5 15ARH05 82B5                      | 3         | 0.39%   |
| Lenovo G710 20252                                 | 3         | 0.39%   |
| Gigabyte B550M DS3H                               | 3         | 0.39%   |
| Dell Inspiron 3542                                | 3         | 0.39%   |
| ASUS PRIME A320M-K                                | 3         | 0.39%   |
| ASUS ASUS Vivobook S 16 M5606WA_M5606WA           | 3         | 0.39%   |
| Acer Swift SF314-43                               | 3         | 0.39%   |
| Acer Aspire E5-771G                               | 3         | 0.39%   |
| Acer Aspire A515-51G                              | 3         | 0.39%   |
| TUXEDO Pulse 15 Gen1                              | 2         | 0.26%   |
| Timi TM1701                                       | 2         | 0.26%   |
| Shenzhen Meigao Electronic Equipment Venus series | 2         | 0.26%   |
| RPi Raspberry Pi 4 Model B Rev 1.1                | 2         | 0.26%   |
| MSI MS-7C02                                       | 2         | 0.26%   |
| MSI MS-7850                                       | 2         | 0.26%   |
| Lenovo Z50-70 20354                               | 2         | 0.26%   |
| Lenovo ThinkPad X380 Yoga 20LJS59W00              | 2         | 0.26%   |
| Lenovo ThinkBook 16p Gen 2 20YM                   | 2         | 0.26%   |
| Lenovo ThinkBook 16 G6 IRL 21KH                   | 2         | 0.26%   |
| Lenovo ThinkBook 15-IIL 20SM                      | 2         | 0.26%   |
| Lenovo ThinkBook 15 G2 ITL 20VE                   | 2         | 0.26%   |
| Lenovo Legion Go 8APU1 83E1                       | 2         | 0.26%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ                  | 2         | 0.26%   |
| Lenovo G500 20236                                 | 2         | 0.26%   |
| Lenovo G40-30 80FY                                | 2         | 0.26%   |
| Intel DH61CR AAG14064-204                         | 2         | 0.26%   |
| HP ProDesk 600 G1 SFF                             | 2         | 0.26%   |
| HP ProBook 450 G7                                 | 2         | 0.26%   |
| HP Presario CQ57                                  | 2         | 0.26%   |
| HP OMEN by Laptop                                 | 2         | 0.26%   |
| HP Notebook                                       | 2         | 0.26%   |
| HP Laptop 15s-eq2xxx                              | 2         | 0.26%   |
| HP EliteBook 8560p                                | 2         | 0.26%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 60        | 7.8%    |
| Acer Aspire         | 53        | 6.89%   |
| HP EliteBook        | 22        | 2.86%   |
| ASUS VivoBook       | 22        | 2.86%   |
| HP Laptop           | 19        | 2.47%   |
| HP ProBook          | 15        | 1.95%   |
| ASUS PRIME          | 15        | 1.95%   |
| Lenovo Legion       | 14        | 1.82%   |
| Lenovo IdeaPad      | 14        | 1.82%   |
| Lenovo ThinkBook    | 13        | 1.69%   |
| Dell Inspiron       | 13        | 1.69%   |
| ASUS ROG            | 13        | 1.69%   |
| HP Pavilion         | 12        | 1.56%   |
| Dell Latitude       | 12        | 1.56%   |
| ASUS TUF            | 12        | 1.56%   |
| HP Compaq           | 11        | 1.43%   |
| Dell Vostro         | 11        | 1.43%   |
| ASUS ASUS           | 11        | 1.43%   |
| ASUS ZenBook        | 9         | 1.17%   |
| Acer Swift          | 9         | 1.17%   |
| Toshiba Satellite   | 8         | 1.04%   |
| Unknown             | 8         | 1.04%   |
| Dell XPS            | 7         | 0.91%   |
| HP OMEN             | 6         | 0.78%   |
| ASUS All            | 6         | 0.78%   |
| Tactus GeoBook      | 5         | 0.65%   |
| Lenovo Yoga         | 5         | 0.65%   |
| HP ZBook            | 5         | 0.65%   |
| Gigabyte B450       | 5         | 0.65%   |
| ASRock B450M-HDV    | 5         | 0.65%   |
| TUXEDO InfinityBook | 4         | 0.52%   |
| RPi Raspberry       | 4         | 0.52%   |
| HP ProDesk          | 4         | 0.52%   |
| HP 250              | 4         | 0.52%   |
| Acer Nitro          | 4         | 0.52%   |
| Lenovo ThinkCentre  | 3         | 0.39%   |
| Lenovo IdeaCentre   | 3         | 0.39%   |
| Lenovo G710         | 3         | 0.39%   |
| HP EliteDesk        | 3         | 0.39%   |
| Gigabyte Z390       | 3         | 0.39%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 78        | 10.14%  |
| 2020    | 73        | 9.49%   |
| 2021    | 71        | 9.23%   |
| 2019    | 62        | 8.06%   |
| 2017    | 59        | 7.67%   |
| 2013    | 47        | 6.11%   |
| 2012    | 47        | 6.11%   |
| 2014    | 42        | 5.46%   |
| 2011    | 39        | 5.07%   |
| 2023    | 37        | 4.81%   |
| 2022    | 36        | 4.68%   |
| 2016    | 30        | 3.9%    |
| 2015    | 25        | 3.25%   |
| 2024    | 23        | 2.99%   |
| 2008    | 22        | 2.86%   |
| 2009    | 20        | 2.6%    |
| 2010    | 19        | 2.47%   |
| 2007    | 19        | 2.47%   |
| 2006    | 7         | 0.91%   |
| Unknown | 6         | 0.78%   |
| 2025    | 4         | 0.52%   |
| 2005    | 3         | 0.39%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 481       | 62.55%  |
| Desktop        | 242       | 31.47%  |
| Convertible    | 13        | 1.69%   |
| All in one     | 10        | 1.3%    |
| Mini pc        | 9         | 1.17%   |
| System on chip | 5         | 0.65%   |
| Tablet         | 4         | 0.52%   |
| Server         | 4         | 0.52%   |
| Stick pc       | 1         | 0.13%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 715       | 92.26%  |
| Enabled  | 60        | 7.74%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 769       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 170       | 21.74%  |
| 4.01-8.0    | 166       | 21.23%  |
| 16.01-24.0  | 152       | 19.44%  |
| 3.01-4.0    | 111       | 14.19%  |
| 32.01-64.0  | 97        | 12.4%   |
| 24.01-32.0  | 33        | 4.22%   |
| 1.01-2.0    | 24        | 3.07%   |
| 64.01-256.0 | 22        | 2.81%   |
| 2.01-3.0    | 7         | 0.9%    |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 257       | 29.68%  |
| 2.01-3.0   | 218       | 25.17%  |
| 4.01-8.0   | 173       | 19.98%  |
| 3.01-4.0   | 113       | 13.05%  |
| 8.01-16.0  | 53        | 6.12%   |
| 0.51-1.0   | 34        | 3.93%   |
| 16.01-24.0 | 11        | 1.27%   |
| 0.01-0.5   | 4         | 0.46%   |
| 24.01-32.0 | 3         | 0.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 497       | 62.36%  |
| 2       | 177       | 22.21%  |
| 3       | 57        | 7.15%   |
| 4       | 30        | 3.76%   |
| 5       | 15        | 1.88%   |
| 0       | 7         | 0.88%   |
| 6       | 6         | 0.75%   |
| 10      | 2         | 0.25%   |
| 8       | 2         | 0.25%   |
| 7       | 2         | 0.25%   |
| 14      | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 542       | 69.94%  |
| Yes       | 233       | 30.06%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 653       | 84.48%  |
| No        | 120       | 15.52%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 581       | 74.97%  |
| No        | 194       | 25.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 512       | 65.64%  |
| No        | 268       | 34.36%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Croatia | 769       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Computers | Percent |
|--------------------|-----------|---------|
| Zagreb             | 456       | 52.78%  |
| Split              | 53        | 6.13%   |
| Rijeka             | 43        | 4.98%   |
| Osijek             | 20        | 2.31%   |
| Varaždin          | 17        | 1.97%   |
| Pula               | 12        | 1.39%   |
| Velika Gorica      | 10        | 1.16%   |
| Koprivnica         | 10        | 1.16%   |
| Bjelovar           | 10        | 1.16%   |
| Samobor            | 9         | 1.04%   |
| Zaprešić         | 8         | 0.93%   |
| Zadar              | 8         | 0.93%   |
| Čakovec           | 8         | 0.93%   |
| Virovitica         | 6         | 0.69%   |
| Đakovo            | 5         | 0.58%   |
| Sisak              | 5         | 0.58%   |
| Karlovac           | 5         | 0.58%   |
| Pitomaca           | 4         | 0.46%   |
| Kastav             | 4         | 0.46%   |
| Jesenice           | 4         | 0.46%   |
| Vinkovci           | 3         | 0.35%   |
| Slavonski Brod     | 3         | 0.35%   |
| Slatina            | 3         | 0.35%   |
| Šibenik           | 3         | 0.35%   |
| Sesvete            | 3         | 0.35%   |
| Prigorje Brdovecko | 3         | 0.35%   |
| Petrinja           | 3         | 0.35%   |
| Omiš              | 3         | 0.35%   |
| Krizevci           | 3         | 0.35%   |
| GJurgevac          | 3         | 0.35%   |
| Zminj              | 2         | 0.23%   |
| Vodice             | 2         | 0.23%   |
| Visnjevac          | 2         | 0.23%   |
| Umag               | 2         | 0.23%   |
| Udbinja            | 2         | 0.23%   |
| Supetar            | 2         | 0.23%   |
| Rovinj             | 2         | 0.23%   |
| Postira            | 2         | 0.23%   |
| Novska             | 2         | 0.23%   |
| Našice            | 2         | 0.23%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 164       | 228    | 14.39%  |
| WDC                          | 160       | 241    | 14.04%  |
| Kingston                     | 97        | 140    | 8.51%   |
| Seagate                      | 93        | 152    | 8.16%   |
| Toshiba                      | 83        | 123    | 7.28%   |
| Sandisk                      | 74        | 91     | 6.49%   |
| Crucial                      | 54        | 76     | 4.74%   |
| SK hynix                     | 49        | 66     | 4.3%    |
| Micron Technology            | 47        | 55     | 4.12%   |
| Intel                        | 39        | 49     | 3.42%   |
| Unknown                      | 30        | 39     | 2.63%   |
| A-DATA Technology            | 25        | 29     | 2.19%   |
| Hitachi                      | 21        | 25     | 1.84%   |
| Patriot                      | 18        | 22     | 1.58%   |
| Kingston Technology Company  | 18        | 22     | 1.58%   |
| HGST                         | 12        | 12     | 1.05%   |
| Apple                        | 11        | 20     | 0.96%   |
| Micron/Crucial Technology    | 8         | 9      | 0.7%    |
| China                        | 8         | 9      | 0.7%    |
| Transcend                    | 7         | 12     | 0.61%   |
| Silicon Motion               | 7         | 9      | 0.61%   |
| Netac                        | 7         | 7      | 0.61%   |
| SPCC                         | 5         | 6      | 0.44%   |
| Phison Electronics           | 5         | 6      | 0.44%   |
| Phison                       | 5         | 5      | 0.44%   |
| Fujitsu                      | 5         | 7      | 0.44%   |
| LITEON                       | 4         | 5      | 0.35%   |
| KIOXIA                       | 4         | 4      | 0.35%   |
| Gigabyte Technology          | 4         | 4      | 0.35%   |
| ADATA Technology             | 4         | 4      | 0.35%   |
| UMIS                         | 3         | 3      | 0.26%   |
| OCZ                          | 3         | 4      | 0.26%   |
| JMicron Technology           | 3         | 3      | 0.26%   |
| Intenso                      | 3         | 4      | 0.26%   |
| Corsair                      | 3         | 3      | 0.26%   |
| Vi550                        | 2         | 2      | 0.18%   |
| Verbatim                     | 2         | 2      | 0.18%   |
| StoreJet                     | 2         | 2      | 0.18%   |
| Shenzhen Longsys Electronics | 2         | 2      | 0.18%   |
| Realtek Semiconductor        | 2         | 4      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                    | 16        | 1.29%   |
| Kingston SA400S37120G 120GB SSD                    | 14        | 1.13%   |
| Toshiba MQ01ABD100 1TB                             | 13        | 1.05%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 13        | 1.05%   |
| Kingston SA400S37480G 480GB SSD                    | 12        | 0.97%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 11        | 0.89%   |
| Samsung NVMe SSD Drive 512GB                       | 9         | 0.73%   |
| Crucial CT240BX500SSD1 240GB                       | 8         | 0.65%   |
| Toshiba HDWD130 3TB                                | 7         | 0.57%   |
| Toshiba HDWD110 1TB                                | 7         | 0.57%   |
| Toshiba DT01ACA100 1TB                             | 7         | 0.57%   |
| Samsung SSD 850 EVO 250GB                          | 7         | 0.57%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                | 7         | 0.57%   |
| A-DATA SU630 240GB SSD                             | 7         | 0.57%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 6         | 0.49%   |
| Seagate ST1000DM010-2EP102 1TB                     | 6         | 0.49%   |
| Sandisk WD PC SN5000S SDEPNSJ-1T00-1006 1TB        | 6         | 0.49%   |
| SanDisk NVMe SSD Drive 512GB                       | 6         | 0.49%   |
| Samsung MZALQ512HALU-000L2 512GB                   | 6         | 0.49%   |
| HGST HTS721010A9E630 1TB                           | 6         | 0.49%   |
| WDC WD10EZEX-08M2NA0 1TB                           | 5         | 0.4%    |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                 | 5         | 0.4%    |
| Unknown MMC Card  32GB                             | 5         | 0.4%    |
| Seagate ST500LT012-1DG142 500GB                    | 5         | 0.4%    |
| Seagate ST1000LM035-1RK172 1TB                     | 5         | 0.4%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 5         | 0.4%    |
| Patriot Burst 240GB SSD                            | 5         | 0.4%    |
| Netac SSD 128GB                                    | 5         | 0.4%    |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                | 5         | 0.4%    |
| Kingston Company SNV3S1000G 1TB                    | 5         | 0.4%    |
| Kingston SV300S37A120G 120GB SSD                   | 5         | 0.4%    |
| Crucial CT1000BX500SSD1 1TB                        | 5         | 0.4%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 4         | 0.32%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 4         | 0.32%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 4         | 0.32%   |
| Unknown MMC Card  128GB                            | 4         | 0.32%   |
| Toshiba DT01ACA200 2TB                             | 4         | 0.32%   |
| Seagate ST2000DM008-2FR102 2TB                     | 4         | 0.32%   |
| SanDisk NVMe SSD Drive 1TB                         | 4         | 0.32%   |
| Samsung SSD 990 EVO 2TB                            | 4         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 130       | 195    | 36.72%  |
| Seagate             | 89        | 136    | 25.14%  |
| Toshiba             | 71        | 101    | 20.06%  |
| Hitachi             | 21        | 25     | 5.93%   |
| HGST                | 12        | 12     | 3.39%   |
| Samsung Electronics | 10        | 13     | 2.82%   |
| Fujitsu             | 5         | 7      | 1.41%   |
| Unknown             | 4         | 4      | 1.13%   |
| Maxtor              | 2         | 2      | 0.56%   |
| External            | 2         | 2      | 0.56%   |
| TO Exter            | 1         | 1      | 0.28%   |
| SSK                 | 1         | 1      | 0.28%   |
| Min Yi U            | 1         | 1      | 0.28%   |
| JMicron Technology  | 1         | 1      | 0.28%   |
| Intenso             | 1         | 2      | 0.28%   |
| HPE                 | 1         | 2      | 0.28%   |
| HGST HTS            | 1         | 1      | 0.28%   |
| ASMedia             | 1         | 1      | 0.28%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 76        | 102    | 21.11%  |
| Samsung Electronics | 57        | 79     | 15.83%  |
| Crucial             | 42        | 58     | 11.67%  |
| A-DATA Technology   | 23        | 26     | 6.39%   |
| SanDisk             | 21        | 29     | 5.83%   |
| Intel               | 19        | 23     | 5.28%   |
| Patriot             | 17        | 21     | 4.72%   |
| WDC                 | 16        | 19     | 4.44%   |
| Micron Technology   | 12        | 13     | 3.33%   |
| SK hynix            | 9         | 16     | 2.5%    |
| Apple               | 8         | 13     | 2.22%   |
| Netac               | 7         | 7      | 1.94%   |
| China               | 7         | 8      | 1.94%   |
| SPCC                | 5         | 6      | 1.39%   |
| Transcend           | 4         | 5      | 1.11%   |
| OCZ                 | 3         | 4      | 0.83%   |
| LITEON              | 3         | 4      | 0.83%   |
| Gigabyte Technology | 3         | 3      | 0.83%   |
| Vi550               | 2         | 2      | 0.56%   |
| Toshiba             | 2         | 4      | 0.56%   |
| StoreJet            | 2         | 2      | 0.56%   |
| Seagate             | 2         | 3      | 0.56%   |
| Mushkin             | 2         | 3      | 0.56%   |
| KingSpec            | 2         | 2      | 0.56%   |
| Intenso             | 2         | 2      | 0.56%   |
| Emtec               | 2         | 2      | 0.56%   |
| AMD                 | 2         | 5      | 0.56%   |
| Verbatim            | 1         | 1      | 0.28%   |
| Ramaxel Technology  | 1         | 1      | 0.28%   |
| PNY                 | 1         | 1      | 0.28%   |
| Phison              | 1         | 1      | 0.28%   |
| Kingmax             | 1         | 1      | 0.28%   |
| KingDian            | 1         | 1      | 0.28%   |
| JMicron Technology  | 1         | 1      | 0.28%   |
| INNOVATION IT       | 1         | 1      | 0.28%   |
| GOODRAM             | 1         | 1      | 0.28%   |
| Corsair             | 1         | 1      | 0.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 363       | 525    | 36.05%  |
| SSD     | 308       | 471    | 30.59%  |
| HDD     | 297       | 507    | 29.49%  |
| MMC     | 24        | 27     | 2.38%   |
| Unknown | 15        | 34     | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 481       | 948    | 53.09%  |
| NVMe | 363       | 524    | 40.07%  |
| SAS  | 38        | 65     | 4.19%   |
| MMC  | 24        | 27     | 2.65%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 355       | 570    | 56.8%   |
| 0.51-1.0   | 170       | 242    | 27.2%   |
| 1.01-2.0   | 54        | 86     | 8.64%   |
| 3.01-4.0   | 19        | 31     | 3.04%   |
| 2.01-3.0   | 19        | 36     | 3.04%   |
| 10.01-20.0 | 5         | 9      | 0.8%    |
| 4.01-10.0  | 3         | 4      | 0.48%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 192       | 23.36%  |
| 251-500        | 190       | 23.11%  |
| 501-1000       | 134       | 16.3%   |
| 1001-2000      | 93        | 11.31%  |
| More than 3000 | 56        | 6.81%   |
| 1-20           | 50        | 6.08%   |
| 51-100         | 37        | 4.5%    |
| Unknown        | 31        | 3.77%   |
| 21-50          | 20        | 2.43%   |
| 2001-3000      | 19        | 2.31%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 296       | 34.34%  |
| 21-50          | 151       | 17.52%  |
| 101-250        | 91        | 10.56%  |
| 51-100         | 87        | 10.09%  |
| 251-500        | 80        | 9.28%   |
| 501-1000       | 61        | 7.08%   |
| 1001-2000      | 32        | 3.71%   |
| Unknown        | 31        | 3.6%    |
| More than 3000 | 17        | 1.97%   |
| 2001-3000      | 14        | 1.62%   |
| 0              | 2         | 0.23%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                              | Computers | Drives | Percent |
|------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB           | 3         | 3      | 3.9%    |
| Seagate ST9500420AS 500GB          | 2         | 3      | 2.6%    |
| Seagate ST31500341AS 1TB           | 2         | 3      | 2.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB | 2         | 4      | 2.6%    |
| Hitachi HTS545050A7E380 500GB      | 2         | 2      | 2.6%    |
| Crucial CT120BX500SSD1 120GB       | 2         | 4      | 2.6%    |
| WDC WDS240G2G0B-00EPW0 240GB SSD   | 1         | 1      | 1.3%    |
| WDC WD6400AAKS-07A7B0 640GB        | 1         | 1      | 1.3%    |
| WDC WD600VE-75HDT0 64GB            | 1         | 1      | 1.3%    |
| WDC WD5003ABYX-88 LEN 500GB        | 1         | 1      | 1.3%    |
| WDC WD5000AAKX-221CA1 500GB        | 1         | 1      | 1.3%    |
| WDC WD5000AAKS-00UU3A0 500GB       | 1         | 1      | 1.3%    |
| WDC WD3200BEKT-08PVMT1 320GB       | 1         | 1      | 1.3%    |
| WDC WD3200AAKS-00L9A0 320GB        | 1         | 1      | 1.3%    |
| WDC WD2500AAKX-75U6AA0 250GB       | 1         | 1      | 1.3%    |
| WDC WD20PURX-64P6ZY0 2TB           | 1         | 1      | 1.3%    |
| WDC WD2003FYYS-05T9B0 2TB          | 1         | 1      | 1.3%    |
| WDC WD15EARS-00S8B1 1TB            | 1         | 1      | 1.3%    |
| WDC WD10JPCX-24UE4T0 1TB           | 1         | 1      | 1.3%    |
| WDC WD10EZRZ-00HTKB0 1TB           | 1         | 1      | 1.3%    |
| WDC WD10EZEX-08M2NA0 1TB           | 1         | 1      | 1.3%    |
| WDC WD10EZEX-00MFCA0 1TB           | 1         | 1      | 1.3%    |
| WDC WD1001FALS-00J7B0 1TB          | 1         | 1      | 1.3%    |
| WDC WD Green 2.5 240GB             | 1         | 1      | 1.3%    |
| Transcend TS480GSSD220S 480GB      | 1         | 1      | 1.3%    |
| Toshiba MQ01ABD100 1TB             | 1         | 1      | 1.3%    |
| Toshiba MK6459GSXP 640GB           | 1         | 1      | 1.3%    |
| Toshiba MK3265GSX 320GB            | 1         | 1      | 1.3%    |
| Toshiba MK2555GSX 250GB            | 1         | 1      | 1.3%    |
| Toshiba MK2552GSX 250GB            | 1         | 1      | 1.3%    |
| Toshiba HDWJ105 500GB              | 1         | 1      | 1.3%    |
| Toshiba DT01ACA100 1TB             | 1         | 1      | 1.3%    |
| SPCC Solid State Disk 128GB        | 1         | 1      | 1.3%    |
| SPCC Solid State Disk 120GB        | 1         | 2      | 1.3%    |
| SK hynix SH920 2.5 7MM 256GB SSD   | 1         | 2      | 1.3%    |
| SK hynix SC210 2.5 7MM 256GB SSD   | 1         | 1      | 1.3%    |
| Seagate ST9500325AS 500GB          | 1         | 1      | 1.3%    |
| Seagate ST9250827AS 250GB          | 1         | 1      | 1.3%    |
| Seagate ST500DM002-1BD142 500GB    | 1         | 2      | 1.3%    |
| Seagate ST3250410AS 250GB          | 1         | 2      | 1.3%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 18        | 18     | 24%     |
| Seagate             | 15        | 22     | 20%     |
| Toshiba             | 7         | 7      | 9.33%   |
| Hitachi             | 5         | 5      | 6.67%   |
| HGST                | 5         | 5      | 6.67%   |
| Intel               | 4         | 5      | 5.33%   |
| Crucial             | 4         | 6      | 5.33%   |
| Samsung Electronics | 3         | 3      | 4%      |
| SPCC                | 2         | 3      | 2.67%   |
| SK hynix            | 2         | 3      | 2.67%   |
| SanDisk             | 2         | 3      | 2.67%   |
| Kingston            | 2         | 2      | 2.67%   |
| China               | 2         | 2      | 2.67%   |
| A-DATA Technology   | 2         | 2      | 2.67%   |
| Transcend           | 1         | 1      | 1.33%   |
| LITEON              | 1         | 1      | 1.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 16        | 16     | 32.65%  |
| Seagate             | 15        | 22     | 30.61%  |
| Toshiba             | 7         | 7      | 14.29%  |
| Hitachi             | 5         | 5      | 10.2%   |
| HGST                | 5         | 5      | 10.2%   |
| Samsung Electronics | 1         | 1      | 2.04%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 46        | 56     | 64.79%  |
| SSD  | 23        | 30     | 32.39%  |
| NVMe | 2         | 2      | 2.82%   |

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


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 409       | 811    | 48.92%  |
| Works    | 361       | 665    | 43.18%  |
| Malfunc  | 66        | 88     | 7.89%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 457       | 44.11%  |
| AMD                                     | 159       | 15.35%  |
| Samsung Electronics                     | 111       | 10.71%  |
| SanDisk                                 | 69        | 6.66%   |
| Kingston Technology Company             | 43        | 4.15%   |
| SK hynix                                | 40        | 3.86%   |
| Micron Technology                       | 35        | 3.38%   |
| Micron/Crucial Technology               | 18        | 1.74%   |
| Phison Electronics                      | 14        | 1.35%   |
| Toshiba America Info Systems            | 13        | 1.25%   |
| ASMedia Technology                      | 8         | 0.77%   |
| Silicon Motion                          | 7         | 0.68%   |
| JMicron Technology                      | 7         | 0.68%   |
| ADATA Technology                        | 7         | 0.68%   |
| Nvidia                                  | 6         | 0.58%   |
| Marvell Technology Group                | 6         | 0.58%   |
| KIOXIA                                  | 4         | 0.39%   |
| Union Memory (Shenzhen)                 | 3         | 0.29%   |
| Lite-On Technology                      | 3         | 0.29%   |
| VIA Technologies                        | 2         | 0.19%   |
| Transcend                               | 2         | 0.19%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.19%   |
| Shenzhen Longsys Electronics            | 2         | 0.19%   |
| Seagate Technology                      | 2         | 0.19%   |
| Realtek Semiconductor                   | 2         | 0.19%   |
| MAXIO Technology (Hangzhou)             | 2         | 0.19%   |
| Lenovo                                  | 2         | 0.19%   |
| Broadcom / LSI                          | 2         | 0.19%   |
| Adaptec                                 | 2         | 0.19%   |
| Solidigm                                | 1         | 0.1%    |
| Solid State Storage Technology          | 1         | 0.1%    |
| Silicon Image                           | 1         | 0.1%    |
| Shenzhen Unionmemory Information System | 1         | 0.1%    |
| LSI Logic / Symbios Logic               | 1         | 0.1%    |
| Biwin Storage Technology                | 1         | 0.1%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 96        | 8.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 43        | 3.65%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 38        | 3.23%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 37        | 3.14%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 33        | 2.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 26        | 2.21%   |
| Intel Volume Management Device NVMe RAID Controller                            | 25        | 2.12%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 24        | 2.04%   |
| AMD 400 Series Chipset SATA Controller                                         | 19        | 1.61%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 16        | 1.36%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)      | 16        | 1.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 16        | 1.36%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 16        | 1.36%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 15        | 1.27%   |
| AMD 500 Series Chipset SATA Controller                                         | 15        | 1.27%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 14        | 1.19%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 14        | 1.19%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 14        | 1.19%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 14        | 1.19%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 14        | 1.19%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 13        | 1.1%    |
| AMD 600 Series Chipset SATA Controller                                         | 13        | 1.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 12        | 1.02%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 12        | 1.02%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 12        | 1.02%   |
| Intel Tiger Lake-LP SATA Controller                                            | 12        | 1.02%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 12        | 1.02%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 12        | 1.02%   |
| AMD A320 Chipset SATA Controller [AHCI mode]                                   | 11        | 0.93%   |
| Sandisk WD PC SN5000S M.2 2280 NVMe SSD (DRAM-less)                            | 10        | 0.85%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 10        | 0.85%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 10        | 0.85%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 10        | 0.85%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 10        | 0.85%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 0.76%   |
| Intel Comet Lake SATA AHCI Controller                                          | 9         | 0.76%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 9         | 0.76%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                      | 9         | 0.76%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 9         | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 9         | 0.76%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 535       | 51.29%  |
| NVMe | 363       | 34.8%   |
| IDE  | 89        | 8.53%   |
| RAID | 55        | 5.27%   |
| SAS  | 1         | 0.1%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Computers | Percent |
|---------|-----------|---------|
| Intel   | 528       | 68.66%  |
| AMD     | 234       | 30.43%  |
| ARM     | 5         | 0.65%   |
| Unknown | 2         | 0.26%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 17        | 2.2%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 13        | 1.68%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 1.68%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 9         | 1.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 9         | 1.17%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 1.04%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.04%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 8         | 1.04%   |
| AMD Ryzen 5 7520U with Radeon Graphics        | 8         | 1.04%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 1.04%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 0.91%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 7         | 0.91%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 6         | 0.78%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 0.78%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 0.78%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 0.78%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 6         | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 0.65%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 5         | 0.65%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 5         | 0.65%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 0.65%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 0.65%   |
| AMD Ryzen 7 8845HS w/ Radeon 780M Graphics    | 5         | 0.65%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 0.65%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 4         | 0.52%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 4         | 0.52%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.52%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.52%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 4         | 0.52%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 4         | 0.52%   |
| Intel 12th Gen Core i5-1235U                  | 4         | 0.52%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 4         | 0.52%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 4         | 0.52%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 4         | 0.52%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.52%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 4         | 0.52%   |
| AMD Ryzen 5 3550H with Radeon Vega Mobile Gfx | 4         | 0.52%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 4         | 0.52%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.39%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 3         | 0.39%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 166       | 21.5%   |
| Intel Core i7           | 92        | 11.92%  |
| Other                   | 89        | 11.53%  |
| AMD Ryzen 5             | 64        | 8.29%   |
| AMD Ryzen 7             | 63        | 8.16%   |
| Intel Core i3           | 53        | 6.87%   |
| Intel Core 2 Duo        | 35        | 4.53%   |
| Intel Pentium           | 25        | 3.24%   |
| Intel Celeron           | 21        | 2.72%   |
| AMD Ryzen 9             | 20        | 2.59%   |
| AMD Ryzen 3             | 15        | 1.94%   |
| Intel Xeon              | 10        | 1.3%    |
| Intel Atom              | 9         | 1.17%   |
| Intel Pentium Dual-Core | 8         | 1.04%   |
| AMD FX                  | 8         | 1.04%   |
| Intel Core i9           | 7         | 0.91%   |
| Intel Pentium Dual      | 6         | 0.78%   |
| Intel Core              | 6         | 0.78%   |
| AMD E                   | 6         | 0.78%   |
| AMD A6                  | 6         | 0.78%   |
| AMD Ryzen 5 PRO         | 5         | 0.65%   |
| AMD A8                  | 5         | 0.65%   |
| AMD Ryzen 7 PRO         | 4         | 0.52%   |
| AMD Phenom II X4        | 4         | 0.52%   |
| AMD Athlon II X4        | 4         | 0.52%   |
| Intel Pentium Silver    | 3         | 0.39%   |
| Intel Pentium 4         | 3         | 0.39%   |
| Intel Core 2 Quad       | 3         | 0.39%   |
| Intel Core 2            | 3         | 0.39%   |
| AMD E1                  | 3         | 0.39%   |
| AMD Athlon X4           | 3         | 0.39%   |
| AMD Athlon 64 X2        | 3         | 0.39%   |
| Intel Pentium M         | 2         | 0.26%   |
| Intel Genuine           | 2         | 0.26%   |
| ARM BCM                 | 2         | 0.26%   |
| AMD Athlon              | 2         | 0.26%   |
| Intel Xeon Bronze       | 1         | 0.13%   |
| Intel Celeron M         | 1         | 0.13%   |
| AMD Turion 64 X2 Mobile | 1         | 0.13%   |
| AMD Ryzen Threadripper  | 1         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 265       | 34.33%  |
| 2       | 251       | 32.51%  |
| 8       | 95        | 12.31%  |
| 6       | 85        | 11.01%  |
| 14      | 15        | 1.94%   |
| 12      | 15        | 1.94%   |
| 10      | 15        | 1.94%   |
| 16      | 11        | 1.42%   |
| 1       | 10        | 1.3%    |
| 24      | 3         | 0.39%   |
| 3       | 3         | 0.39%   |
| 20      | 2         | 0.26%   |
| 18      | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 765       | 99.48%  |
| 2       | 3         | 0.39%   |
| Unknown | 1         | 0.13%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 534       | 69.35%  |
| 1       | 235       | 30.52%  |
| Unknown | 1         | 0.13%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 750       | 97.28%  |
| Unknown        | 14        | 1.82%   |
| 32-bit         | 5         | 0.65%   |
| 64-bit         | 2         | 0.26%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 362       | 45.08%  |
| 0x306c3    | 38        | 4.73%   |
| 0x306a9    | 21        | 2.62%   |
| 0x206a7    | 21        | 2.62%   |
| 0x906ea    | 18        | 2.24%   |
| 0x806ea    | 17        | 2.12%   |
| 0x806e9    | 17        | 2.12%   |
| 0x40651    | 14        | 1.74%   |
| 0x1067a    | 14        | 1.74%   |
| 0x0a50000c | 13        | 1.62%   |
| 0x806ec    | 12        | 1.49%   |
| 0x6fd      | 12        | 1.49%   |
| 0x806c1    | 11        | 1.37%   |
| 0x906e9    | 10        | 1.25%   |
| 0x08600106 | 9         | 1.12%   |
| 0x08108109 | 9         | 1.12%   |
| 0xa0652    | 7         | 0.87%   |
| 0x0800820d | 7         | 0.87%   |
| 0x306d4    | 6         | 0.75%   |
| 0x08608103 | 6         | 0.75%   |
| 0x08600103 | 6         | 0.75%   |
| 0x0810100b | 6         | 0.75%   |
| 0xa0653    | 5         | 0.62%   |
| 0x906ed    | 5         | 0.62%   |
| 0x6fb      | 5         | 0.62%   |
| 0x506e3    | 5         | 0.62%   |
| 0x30678    | 5         | 0.62%   |
| 0x10676    | 5         | 0.62%   |
| 0x0a50000d | 5         | 0.62%   |
| 0x06006705 | 5         | 0.62%   |
| 0x506c9    | 4         | 0.5%    |
| 0x406e3    | 4         | 0.5%    |
| 0x406c4    | 4         | 0.5%    |
| 0x20655    | 4         | 0.5%    |
| 0x0a601203 | 4         | 0.5%    |
| 0x08108102 | 4         | 0.5%    |
| 0x010000db | 4         | 0.5%    |
| 0x010000c8 | 4         | 0.5%    |
| 0xa0671    | 3         | 0.37%   |
| 0x906a3    | 3         | 0.37%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| KabyLake           | 126       | 16.34%  |
| Unknown            | 93        | 12.06%  |
| Haswell            | 75        | 9.73%   |
| Zen 3              | 37        | 4.8%    |
| IvyBridge          | 36        | 4.67%   |
| Zen 2              | 34        | 4.41%   |
| SandyBridge        | 30        | 3.89%   |
| Zen+               | 29        | 3.76%   |
| Penryn             | 29        | 3.76%   |
| TigerLake          | 27        | 3.5%    |
| Core               | 27        | 3.5%    |
| Alderlake Hybrid   | 27        | 3.5%    |
| Skylake            | 24        | 3.11%   |
| CometLake          | 21        | 2.72%   |
| Silvermont         | 17        | 2.2%    |
| Zen                | 16        | 2.08%   |
| Icelake            | 14        | 1.82%   |
| Broadwell          | 14        | 1.82%   |
| Piledriver         | 13        | 1.69%   |
| Goldmont plus      | 12        | 1.56%   |
| K10                | 10        | 1.3%    |
| Westmere           | 9         | 1.17%   |
| Excavator          | 8         | 1.04%   |
| Bobcat             | 8         | 1.04%   |
| K8 Hammer          | 5         | 0.65%   |
| Goldmont           | 5         | 0.65%   |
| P6                 | 4         | 0.52%   |
| NetBurst           | 3         | 0.39%   |
| Meteorlake Hybrid  | 3         | 0.39%   |
| Bulldozer          | 3         | 0.39%   |
| Puma               | 2         | 0.26%   |
| Nehalem            | 2         | 0.26%   |
| Jaguar             | 2         | 0.26%   |
| Bonnell            | 2         | 0.26%   |
| Tremont            | 1         | 0.13%   |
| Steamroller        | 1         | 0.13%   |
| Lunarlake Hybrid   | 1         | 0.13%   |
| ArrowLake-H Hybrid | 1         | 0.13%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 407       | 43.25%  |
| AMD                              | 272       | 28.91%  |
| Nvidia                           | 253       | 26.89%  |
| Matrox Electronics Systems       | 5         | 0.53%   |
| Silicon Integrated Systems [SiS] | 2         | 0.21%   |
| VIA Technologies                 | 1         | 0.11%   |
| ATI Technologies                 | 1         | 0.11%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 34        | 3.54%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 25        | 2.6%    |
| Intel 3rd Gen Core processor Graphics Controller                                         | 25        | 2.6%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 24        | 2.5%    |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 20        | 2.08%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 19        | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 19        | 1.98%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 1.87%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 17        | 1.77%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 17        | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 15        | 1.56%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 14        | 1.46%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 1.35%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 13        | 1.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 1.35%   |
| AMD Lucienne                                                                             | 13        | 1.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 12        | 1.25%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 1.14%   |
| AMD Raphael                                                                              | 11        | 1.14%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 1.04%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 10        | 1.04%   |
| AMD Mendocino [Radeon 610M]                                                              | 10        | 1.04%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 9         | 0.94%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 9         | 0.94%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 9         | 0.94%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 9         | 0.94%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 8         | 0.83%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 8         | 0.83%   |
| AMD Rembrandt [Radeon 680M]                                                              | 8         | 0.83%   |
| AMD HawkPoint1                                                                           | 8         | 0.83%   |
| Nvidia GM108M [GeForce 840M]                                                             | 7         | 0.73%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 0.73%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 7         | 0.73%   |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 0.73%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 7         | 0.73%   |
| AMD Phoenix1                                                                             | 7         | 0.73%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.62%   |
| Intel Skylake-S GT2 [HD Graphics 530]                                                    | 6         | 0.62%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 6         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 257       | 33.03%  |
| 1 x AMD         | 208       | 26.74%  |
| 1 x Nvidia      | 116       | 14.91%  |
| Intel + Nvidia  | 111       | 14.27%  |
| Intel + AMD     | 28        | 3.6%    |
| AMD + Nvidia    | 25        | 3.21%   |
| 2 x AMD         | 11        | 1.41%   |
| Other           | 7         | 0.9%    |
| 2 x Intel       | 7         | 0.9%    |
| 1 x Matrox      | 4         | 0.51%   |
| 1 x SiS         | 2         | 0.26%   |
| 1 x VIA         | 1         | 0.13%   |
| Nvidia + Matrox | 1         | 0.13%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 608       | 77.45%  |
| Proprietary | 128       | 16.31%  |
| Unknown     | 49        | 6.24%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 433       | 54.6%   |
| 1.01-2.0   | 95        | 11.98%  |
| 0.01-0.5   | 92        | 11.6%   |
| 3.01-4.0   | 53        | 6.68%   |
| 0.51-1.0   | 52        | 6.56%   |
| 7.01-8.0   | 37        | 4.67%   |
| 8.01-16.0  | 13        | 1.64%   |
| 5.01-6.0   | 11        | 1.39%   |
| 2.01-3.0   | 7         | 0.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 126       | 14.03%  |
| AU Optronics            | 104       | 11.58%  |
| Dell                    | 89        | 9.91%   |
| BOE                     | 84        | 9.35%   |
| Chimei Innolux          | 78        | 8.69%   |
| LG Display              | 76        | 8.46%   |
| AOC                     | 47        | 5.23%   |
| Goldstar                | 33        | 3.67%   |
| Acer                    | 30        | 3.34%   |
| Philips                 | 27        | 3.01%   |
| Lenovo                  | 23        | 2.56%   |
| Hewlett-Packard         | 14        | 1.56%   |
| Ancor Communications    | 13        | 1.45%   |
| Sharp                   | 12        | 1.34%   |
| ASUSTek Computer        | 12        | 1.34%   |
| PANDA                   | 10        | 1.11%   |
| Apple                   | 10        | 1.11%   |
| CSO                     | 8         | 0.89%   |
| BenQ                    | 8         | 0.89%   |
| InfoVision              | 6         | 0.67%   |
| Sony                    | 5         | 0.56%   |
| LG Philips              | 5         | 0.56%   |
| Chi Mei Optoelectronics | 5         | 0.56%   |
| Mi                      | 4         | 0.45%   |
| Grundig                 | 4         | 0.45%   |
| Gigabyte Technology     | 4         | 0.45%   |
| Unknown                 | 3         | 0.33%   |
| TMX                     | 3         | 0.33%   |
| Quanta Display          | 3         | 0.33%   |
| LG Electronics          | 3         | 0.33%   |
| Hitachi                 | 3         | 0.33%   |
| Fujitsu Siemens         | 3         | 0.33%   |
| Denver                  | 3         | 0.33%   |
| ViewSonic               | 2         | 0.22%   |
| Unknown (XXX)           | 2         | 0.22%   |
| Panasonic               | 2         | 0.22%   |
| InnoLux Display         | 2         | 0.22%   |
| Iiyama                  | 2         | 0.22%   |
| IBM                     | 2         | 0.22%   |
| Huion                   | 2         | 0.22%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 8         | 0.86%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 8         | 0.86%   |
| Chimei Innolux LCD Monitor CMN155F 1920x1080 344x193mm 15.5-inch      | 6         | 0.64%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 6         | 0.64%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 6         | 0.64%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 6         | 0.64%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.53%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 5         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4178 3200x2000 344x215mm 16.0-inch | 4         | 0.43%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.43%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 4         | 0.43%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 0.43%   |
| Grundig WUXGA GRU4448 1360x768                                        | 4         | 0.43%   |
| Dell U2713HM DEL407F 1920x1080 597x336mm 27.0-inch                    | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 4         | 0.43%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.43%   |
| BOE LCD Monitor BOE0C8E 2560x1600 329x206mm 15.3-inch                 | 4         | 0.43%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                 | 4         | 0.43%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                   | 4         | 0.43%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.32%   |
| LG Display LCD Monitor LGD069A 1920x1080 340x190mm 15.3-inch          | 3         | 0.32%   |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 3         | 0.32%   |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 3         | 0.32%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.32%   |
| Denver PGM340 LHC3400 3440x1440 790x330mm 33.7-inch                   | 3         | 0.32%   |
| Dell U2312HM DEL4072 1920x1080 510x287mm 23.0-inch                    | 3         | 0.32%   |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                 | 3         | 0.32%   |
| Dell P2417H DELA0DB 1920x1080 527x296mm 23.8-inch                     | 3         | 0.32%   |
| Dell P2414H DELA09B 1920x1080 527x297mm 23.8-inch                     | 3         | 0.32%   |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 0.32%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 3         | 0.32%   |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.32%   |
| AOC 24G2W1G3 AOC2402 1920x1080 527x296mm 23.8-inch                    | 3         | 0.32%   |
| Unknown (XXX) Beyo TV XXX9615 3840x2160 1210x680mm 54.6-inch          | 2         | 0.21%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.21%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.21%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.21%   |
| Samsung Electronics U32J59x SAM0F33 3840x2160 697x392mm 31.5-inch     | 2         | 0.21%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 404       | 47.25%  |
| 1366x768 (WXGA)    | 89        | 10.41%  |
| 2560x1440 (QHD)    | 61        | 7.13%   |
| 3840x2160 (4K)     | 58        | 6.78%   |
| 1600x900 (HD+)     | 35        | 4.09%   |
| 1920x1200 (WUXGA)  | 34        | 3.98%   |
| 1680x1050 (WSXGA+) | 24        | 2.81%   |
| 1440x900 (WXGA+)   | 19        | 2.22%   |
| 1280x1024 (SXGA)   | 19        | 2.22%   |
| 3440x1440          | 18        | 2.11%   |
| 2560x1600          | 13        | 1.52%   |
| 2880x1800          | 12        | 1.4%    |
| Unknown            | 12        | 1.4%    |
| 1280x800 (WXGA)    | 10        | 1.17%   |
| 3200x2000          | 7         | 0.82%   |
| 3840x1080          | 6         | 0.7%    |
| 2560x1080          | 6         | 0.7%    |
| 1360x768           | 4         | 0.47%   |
| 2880x1620          | 3         | 0.35%   |
| 2160x1440          | 3         | 0.35%   |
| 5760x1080          | 2         | 0.23%   |
| 3840x2400          | 2         | 0.23%   |
| 2048x1152          | 2         | 0.23%   |
| 1400x1050          | 2         | 0.23%   |
| 1024x600           | 2         | 0.23%   |
| 800x1280           | 1         | 0.12%   |
| 4480x1440          | 1         | 0.12%   |
| 2880x1920          | 1         | 0.12%   |
| 1920x1280          | 1         | 0.12%   |
| 1280x960           | 1         | 0.12%   |
| 1280x720 (HD)      | 1         | 0.12%   |
| 1024x768 (XGA)     | 1         | 0.12%   |
| 1024x576           | 1         | 0.12%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 253       | 28.08%  |
| 27      | 87        | 9.66%   |
| 17      | 71        | 7.88%   |
| 24      | 70        | 7.77%   |
| 14      | 61        | 6.77%   |
| 13      | 61        | 6.77%   |
| 23      | 52        | 5.77%   |
| 21      | 45        | 4.99%   |
| Unknown | 26        | 2.89%   |
| 31      | 25        | 2.77%   |
| 16      | 22        | 2.44%   |
| 34      | 19        | 2.11%   |
| 22      | 13        | 1.44%   |
| 19      | 13        | 1.44%   |
| 54      | 11        | 1.22%   |
| 20      | 10        | 1.11%   |
| 12      | 7         | 0.78%   |
| 18      | 6         | 0.67%   |
| 84      | 5         | 0.55%   |
| 72      | 4         | 0.44%   |
| 33      | 4         | 0.44%   |
| 26      | 4         | 0.44%   |
| 25      | 4         | 0.44%   |
| 10      | 3         | 0.33%   |
| 65      | 2         | 0.22%   |
| 63      | 2         | 0.22%   |
| 55      | 2         | 0.22%   |
| 49      | 2         | 0.22%   |
| 35      | 2         | 0.22%   |
| 11      | 2         | 0.22%   |
| 8       | 2         | 0.22%   |
| 64      | 1         | 0.11%   |
| 60      | 1         | 0.11%   |
| 58      | 1         | 0.11%   |
| 52      | 1         | 0.11%   |
| 46      | 1         | 0.11%   |
| 43      | 1         | 0.11%   |
| 40      | 1         | 0.11%   |
| 39      | 1         | 0.11%   |
| 38      | 1         | 0.11%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 363       | 41.16%  |
| 501-600     | 192       | 21.77%  |
| 401-500     | 79        | 8.96%   |
| 351-400     | 74        | 8.39%   |
| 201-300     | 46        | 5.22%   |
| 601-700     | 36        | 4.08%   |
| Unknown     | 26        | 2.95%   |
| 701-800     | 24        | 2.72%   |
| 1001-1500   | 24        | 2.72%   |
| 1501-2000   | 9         | 1.02%   |
| 801-900     | 4         | 0.45%   |
| 101-200     | 2         | 0.23%   |
| 901-1000    | 2         | 0.23%   |
| 1-100       | 1         | 0.11%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 591       | 74.72%  |
| 16/10   | 124       | 15.68%  |
| 21/9    | 22        | 2.78%   |
| Unknown | 21        | 2.65%   |
| 5/4     | 17        | 2.15%   |
| 3/2     | 7         | 0.88%   |
| 4/3     | 5         | 0.63%   |
| 0.63    | 2         | 0.25%   |
| 32/9    | 1         | 0.13%   |
| 0.67    | 1         | 0.13%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 253       | 28.24%  |
| 201-250        | 132       | 14.73%  |
| 81-90          | 97        | 10.83%  |
| 301-350        | 91        | 10.16%  |
| 121-130        | 52        | 5.8%    |
| 351-500        | 50        | 5.58%   |
| 151-200        | 37        | 4.13%   |
| 251-300        | 35        | 3.91%   |
| More than 1000 | 31        | 3.46%   |
| Unknown        | 26        | 2.9%    |
| 71-80          | 23        | 2.57%   |
| 111-120        | 22        | 2.46%   |
| 141-150        | 14        | 1.56%   |
| 131-140        | 9         | 1%      |
| 61-70          | 6         | 0.67%   |
| 501-1000       | 6         | 0.67%   |
| 91-100         | 4         | 0.45%   |
| 41-50          | 3         | 0.33%   |
| 1-40           | 3         | 0.33%   |
| 51-60          | 2         | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 281       | 32.52%  |
| 51-100        | 252       | 29.17%  |
| 101-120       | 202       | 23.38%  |
| 161-240       | 59        | 6.83%   |
| Unknown       | 26        | 3.01%   |
| 1-50          | 24        | 2.78%   |
| More than 240 | 20        | 2.31%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 593       | 74.22%  |
| 2     | 153       | 19.15%  |
| 0     | 28        | 3.5%    |
| 3     | 22        | 2.75%   |
| 4     | 3         | 0.38%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 456       | 38.22%  |
| Intel                                  | 351       | 29.42%  |
| Qualcomm Atheros                       | 112       | 9.39%   |
| MediaTek                               | 56        | 4.69%   |
| Broadcom                               | 53        | 4.44%   |
| TP-Link                                | 21        | 1.76%   |
| Broadcom Limited                       | 14        | 1.17%   |
| Samsung Electronics                    | 11        | 0.92%   |
| ASIX Electronics                       | 10        | 0.84%   |
| Ralink Technology                      | 9         | 0.75%   |
| Ralink                                 | 9         | 0.75%   |
| D-Link                                 | 9         | 0.75%   |
| Marvell Technology Group               | 8         | 0.67%   |
| Qualcomm Atheros Communications        | 7         | 0.59%   |
| Xiaomi                                 | 6         | 0.5%    |
| Lenovo                                 | 6         | 0.5%    |
| Suzhou Motorcomm Electronic Technology | 5         | 0.42%   |
| Nvidia                                 | 5         | 0.42%   |
| Shenzhen Goodix Technology             | 4         | 0.34%   |
| Fibocom                                | 4         | 0.34%   |
| Qualcomm                               | 3         | 0.25%   |
| Motorola PCS                           | 3         | 0.25%   |
| VIA Technologies                       | 2         | 0.17%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.17%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.17%   |
| NetGear                                | 2         | 0.17%   |
| Microsoft                              | 2         | 0.17%   |
| Linksys                                | 2         | 0.17%   |
| Huawei Technologies                    | 2         | 0.17%   |
| Ericsson Business Mobile Networks      | 2         | 0.17%   |
| Dell                                   | 2         | 0.17%   |
| ASUSTek Computer                       | 2         | 0.17%   |
| T & A Mobile Phones                    | 1         | 0.08%   |
| Smart Link                             | 1         | 0.08%   |
| Ovislink                               | 1         | 0.08%   |
| Nokia Mobile Phones                    | 1         | 0.08%   |
| ICS Advent                             | 1         | 0.08%   |
| HTC (High Tech Computer)               | 1         | 0.08%   |
| Hewlett-Packard                        | 1         | 0.08%   |
| Edimax Technology                      | 1         | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 298       | 21.94%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 36        | 2.65%   |
| Intel Wireless 8265 / 8275                                              | 33        | 2.43%   |
| Intel Wi-Fi 6 AX200                                                     | 33        | 2.43%   |
| Realtek RTL8125 2.5GbE Controller                                       | 29        | 2.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 26        | 1.91%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 25        | 1.84%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 25        | 1.84%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 1.77%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 1.47%   |
| Intel Wi-Fi 6 AX201                                                     | 20        | 1.47%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 18        | 1.33%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.25%   |
| Intel Ethernet Connection (4) I219-V                                    | 17        | 1.25%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.03%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 14        | 1.03%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 13        | 0.96%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 13        | 0.96%   |
| Intel Wireless 3165                                                     | 12        | 0.88%   |
| Intel Ethernet Connection I217-LM                                       | 12        | 0.88%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 0.88%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 0.81%   |
| Intel Wireless 7265                                                     | 11        | 0.81%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 10        | 0.74%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 9         | 0.66%   |
| Intel Ethernet Connection (2) I219-V                                    | 9         | 0.66%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 0.66%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 8         | 0.59%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 0.59%   |
| Intel Wireless 7260                                                     | 8         | 0.59%   |
| Intel Ethernet Controller I225-V                                        | 8         | 0.59%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 0.59%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 0.59%   |
| ASIX AX88179 Gigabit Ethernet                                           | 8         | 0.59%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 0.52%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.52%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 7         | 0.52%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 7         | 0.52%   |
| Intel Ethernet Connection (7) I219-V                                    | 7         | 0.52%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 270       | 44.12%  |
| Realtek Semiconductor           | 91        | 14.87%  |
| Qualcomm Atheros                | 89        | 14.54%  |
| MediaTek                        | 47        | 7.68%   |
| Broadcom                        | 35        | 5.72%   |
| TP-Link                         | 20        | 3.27%   |
| Ralink Technology               | 9         | 1.47%   |
| Ralink                          | 9         | 1.47%   |
| D-Link                          | 9         | 1.47%   |
| Qualcomm Atheros Communications | 7         | 1.14%   |
| Broadcom Limited                | 7         | 1.14%   |
| Fibocom                         | 4         | 0.65%   |
| Qualcomm                        | 3         | 0.49%   |
| NetGear                         | 2         | 0.33%   |
| Microsoft                       | 2         | 0.33%   |
| Linksys                         | 2         | 0.33%   |
| Dell                            | 2         | 0.33%   |
| ASUSTek Computer                | 2         | 0.33%   |
| Ovislink                        | 1         | 0.16%   |
| Edimax Technology               | 1         | 0.16%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 33        | 5.36%   |
| Intel Wi-Fi 6 AX200                                                     | 33        | 5.36%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 25        | 4.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 3.9%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 20        | 3.25%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 20        | 3.25%   |
| Intel Wi-Fi 6 AX201                                                     | 20        | 3.25%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 18        | 2.92%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 2.76%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 13        | 2.11%   |
| Intel Wireless 3165                                                     | 12        | 1.95%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 1.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 11        | 1.79%   |
| Intel Wireless 7265                                                     | 11        | 1.79%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 10        | 1.62%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 9         | 1.46%   |
| Broadcom BCM43142 802.11b/g/n                                           | 9         | 1.46%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 1.3%    |
| Intel Wireless 7260                                                     | 8         | 1.3%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.3%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 1.3%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 7         | 1.14%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.14%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 7         | 1.14%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 7         | 1.14%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 6         | 0.97%   |
| Ralink MT7601U Wireless Adapter                                         | 6         | 0.97%   |
| Qualcomm Atheros AR9271 802.11n                                         | 6         | 0.97%   |
| Intel Wireless 3160                                                     | 6         | 0.97%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 6         | 0.97%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.97%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 5         | 0.81%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 0.81%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 0.81%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 5         | 0.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 0.81%   |
| TP-Link 802.11ac NIC                                                    | 4         | 0.65%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]      | 4         | 0.65%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 4         | 0.65%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 402       | 56.22%  |
| Intel                                  | 173       | 24.2%   |
| Qualcomm Atheros                       | 35        | 4.9%    |
| Broadcom                               | 21        | 2.94%   |
| Samsung Electronics                    | 11        | 1.54%   |
| ASIX Electronics                       | 10        | 1.4%    |
| MediaTek                               | 8         | 1.12%   |
| Marvell Technology Group               | 8         | 1.12%   |
| Broadcom Limited                       | 7         | 0.98%   |
| Xiaomi                                 | 6         | 0.84%   |
| Lenovo                                 | 6         | 0.84%   |
| Suzhou Motorcomm Electronic Technology | 5         | 0.7%    |
| Nvidia                                 | 5         | 0.7%    |
| Motorola PCS                           | 3         | 0.42%   |
| VIA Technologies                       | 2         | 0.28%   |
| Sundance Technology Inc / IC Plus      | 2         | 0.28%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.28%   |
| Huawei Technologies                    | 2         | 0.28%   |
| TP-Link                                | 1         | 0.14%   |
| T & A Mobile Phones                    | 1         | 0.14%   |
| ICS Advent                             | 1         | 0.14%   |
| HTC (High Tech Computer)               | 1         | 0.14%   |
| DisplayLink                            | 1         | 0.14%   |
| D-Link System                          | 1         | 0.14%   |
| Aquantia                               | 1         | 0.14%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 298       | 40.88%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 36        | 4.94%   |
| Realtek RTL8125 2.5GbE Controller                                      | 29        | 3.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 26        | 3.57%   |
| Intel Ethernet Connection (4) I219-V                                   | 17        | 2.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 13        | 1.78%   |
| Intel Ethernet Connection I217-LM                                      | 12        | 1.65%   |
| Intel Ethernet Connection (2) I219-V                                   | 9         | 1.23%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 9         | 1.23%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 8         | 1.1%    |
| Intel Ethernet Controller I225-V                                       | 8         | 1.1%    |
| ASIX AX88179 Gigabit Ethernet                                          | 8         | 1.1%    |
| Intel Ethernet Connection (7) I219-V                                   | 7         | 0.96%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 6         | 0.82%   |
| Intel Ethernet Connection (2) I218-V                                   | 6         | 0.82%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 5         | 0.69%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 5         | 0.69%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 5         | 0.69%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 5         | 0.69%   |
| Intel Ethernet Connection I217-V                                       | 5         | 0.69%   |
| Intel Ethernet Connection (13) I219-V                                  | 5         | 0.69%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                      | 5         | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 4         | 0.55%   |
| Realtek Killer E2600 GbE Controller                                    | 4         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 0.55%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 0.55%   |
| Intel I211 Gigabit Network Connection                                  | 4         | 0.55%   |
| Intel I210 Gigabit Network Connection                                  | 4         | 0.55%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 0.55%   |
| Intel Ethernet Connection (3) I218-LM                                  | 4         | 0.55%   |
| Intel Ethernet Connection (14) I219-V                                  | 4         | 0.55%   |
| Intel 82579V Gigabit Network Connection                                | 4         | 0.55%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 3         | 0.41%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 0.41%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 3         | 0.41%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 0.41%   |
| Motorola PCS motorola one 5G ace                                       | 3         | 0.41%   |
| Intel Ethernet Connection I219-V                                       | 3         | 0.41%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.41%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 652       | 52.33%  |
| WiFi     | 581       | 46.63%  |
| Modem    | 10        | 0.8%    |
| Unknown  | 3         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 473       | 59.35%  |
| Ethernet | 324       | 40.65%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 430       | 55.77%  |
| 1     | 318       | 41.25%  |
| 0     | 15        | 1.95%   |
| 4     | 4         | 0.52%   |
| 3     | 3         | 0.39%   |
| 13    | 1         | 0.13%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 726       | 93.68%  |
| Yes  | 49        | 6.32%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 233       | 45.33%  |
| Realtek Semiconductor           | 60        | 11.67%  |
| IMC Networks                    | 35        | 6.81%   |
| Lite-On Technology              | 32        | 6.23%   |
| Foxconn / Hon Hai               | 32        | 6.23%   |
| Qualcomm Atheros Communications | 30        | 5.84%   |
| Broadcom                        | 22        | 4.28%   |
| Cambridge Silicon Radio         | 18        | 3.5%    |
| Apple                           | 15        | 2.92%   |
| MediaTek                        | 7         | 1.36%   |
| Hewlett-Packard                 | 7         | 1.36%   |
| Toshiba                         | 5         | 0.97%   |
| TP-Link                         | 3         | 0.58%   |
| Foxconn International           | 3         | 0.58%   |
| Realtek                         | 2         | 0.39%   |
| Integrated System Solution      | 2         | 0.39%   |
| Dell                            | 2         | 0.39%   |
| ASUSTek Computer                | 2         | 0.39%   |
| USI                             | 1         | 0.19%   |
| Ralink Technology               | 1         | 0.19%   |
| Ralink                          | 1         | 0.19%   |
| Chicony Electronics             | 1         | 0.19%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 72        | 14.01%  |
| Realtek Bluetooth Radio                             | 52        | 10.12%  |
| Intel AX201 Bluetooth                               | 51        | 9.92%   |
| Intel AX200 Bluetooth                               | 33        | 6.42%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 28        | 5.45%   |
| Intel Bluetooth Device                              | 19        | 3.7%    |
| IMC Networks Wireless_Device                        | 18        | 3.5%    |
| Foxconn / Hon Hai Wireless_Device                   | 18        | 3.5%    |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 18        | 3.5%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 3.11%   |
| Intel Wireless-AC 3168 Bluetooth                    | 12        | 2.33%   |
| IMC Networks Bluetooth Radio                        | 11        | 2.14%   |
| Qualcomm Atheros  Bluetooth Device                  | 10        | 1.95%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 1.36%   |
| MediaTek Wireless_Device                            | 7         | 1.36%   |
| Lite-On Bluetooth Device                            | 6         | 1.17%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 6         | 1.17%   |
| Intel AX210 Bluetooth                               | 6         | 1.17%   |
| Apple Bluetooth USB Host Controller                 | 6         | 1.17%   |
| Lite-On Wireless_Device                             | 5         | 0.97%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 0.97%   |
| Broadcom BCM2045 Bluetooth                          | 5         | 0.97%   |
| Apple Bluetooth Host Controller                     | 5         | 0.97%   |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 0.78%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.78%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.78%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.78%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 0.78%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 4         | 0.78%   |
| TP-Link TP-T@- UB500 Adapter                        | 3         | 0.58%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 3         | 0.58%   |
| IMC Networks Bluetooth Device                       | 3         | 0.58%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.58%   |
| Broadcom HP Portable Bumble Bee                     | 3         | 0.58%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.39%   |
| Realtek Bluetooth Radio                             | 2         | 0.39%   |
| Lite-On Atheros Bluetooth                           | 2         | 0.39%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.39%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 512       | 46.67%  |
| AMD                                  | 285       | 25.98%  |
| Nvidia                               | 171       | 15.59%  |
| Logitech                             | 21        | 1.91%   |
| C-Media Electronics                  | 20        | 1.82%   |
| Lenovo                               | 9         | 0.82%   |
| JMTek                                | 9         | 0.82%   |
| Hewlett-Packard                      | 4         | 0.36%   |
| VIA Technologies                     | 3         | 0.27%   |
| Trust                                | 3         | 0.27%   |
| Sony                                 | 3         | 0.27%   |
| Samsung Electronics                  | 3         | 0.27%   |
| Creative Labs                        | 3         | 0.27%   |
| Yamaha                               | 2         | 0.18%   |
| Texas Instruments                    | 2         | 0.18%   |
| Tenx Technology                      | 2         | 0.18%   |
| Silicon Integrated Systems [SiS]     | 2         | 0.18%   |
| Microsoft                            | 2         | 0.18%   |
| Generalplus Technology               | 2         | 0.18%   |
| Creative Technology                  | 2         | 0.18%   |
| ASUSTek Computer                     | 2         | 0.18%   |
| Unknown                              | 2         | 0.18%   |
| ZOOM                                 | 1         | 0.09%   |
| YZ Technology                        | 1         | 0.09%   |
| XMOS                                 | 1         | 0.09%   |
| Xilinx                               | 1         | 0.09%   |
| Walmart                              | 1         | 0.09%   |
| Thesycon Systemsoftware & Consulting | 1         | 0.09%   |
| SteelSeries ApS                      | 1         | 0.09%   |
| SAVITECH                             | 1         | 0.09%   |
| Samson Technologies                  | 1         | 0.09%   |
| Realtek Semiconductor                | 1         | 0.09%   |
| Razer USA                            | 1         | 0.09%   |
| PreSonus Audio Electronics           | 1         | 0.09%   |
| Plantronics                          | 1         | 0.09%   |
| Pioneer DJ                           | 1         | 0.09%   |
| Nordic Semiconductor ASA             | 1         | 0.09%   |
| Native Instruments                   | 1         | 0.09%   |
| MV-SILICON                           | 1         | 0.09%   |
| Micro Star International             | 1         | 0.09%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                              | 138       | 10.26%  |
| Intel Sunrise Point-LP HD Audio                                            | 64        | 4.76%   |
| AMD Radeon High Definition Audio Controller                                | 47        | 3.49%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 46        | 3.42%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 38        | 2.83%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 36        | 2.68%   |
| Intel Cannon Lake PCH cAVS                                                 | 32        | 2.38%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 31        | 2.3%    |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 28        | 2.08%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 27        | 2.01%   |
| AMD Starship/Matisse HD Audio Controller                                   | 26        | 1.93%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 25        | 1.86%   |
| Intel Haswell-ULT HD Audio Controller                                      | 24        | 1.78%   |
| Intel 8 Series HD Audio Controller                                         | 24        | 1.78%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 22        | 1.64%   |
| Nvidia GP107GL High Definition Audio Controller                            | 21        | 1.56%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 21        | 1.56%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 18        | 1.34%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 16        | 1.19%   |
| Nvidia GP106 High Definition Audio Controller                              | 16        | 1.19%   |
| Intel Comet Lake PCH cAVS                                                  | 16        | 1.19%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 16        | 1.19%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 15        | 1.12%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 14        | 1.04%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 14        | 1.04%   |
| Intel Broadwell-U Audio Controller                                         | 14        | 1.04%   |
| AMD FCH Azalia Controller                                                  | 14        | 1.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 14        | 1.04%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 13        | 0.97%   |
| Intel 200 Series PCH HD Audio                                              | 13        | 0.97%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 13        | 0.97%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 13        | 0.97%   |
| Nvidia GA106 High Definition Audio Controller                              | 12        | 0.89%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 12        | 0.89%   |
| Nvidia TU116 High Definition Audio Controller                              | 11        | 0.82%   |
| Nvidia GA104 High Definition Audio Controller                              | 10        | 0.74%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 10        | 0.74%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 10        | 0.74%   |
| Intel Raptor Lake-P/U/H cAVS                                               | 9         | 0.67%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 9         | 0.67%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Samsung Electronics            | 120       | 22.73%  |
| SK hynix                       | 93        | 17.61%  |
| Kingston                       | 93        | 17.61%  |
| Micron Technology              | 58        | 10.98%  |
| Crucial                        | 33        | 6.25%   |
| Unknown                        | 27        | 5.11%   |
| Corsair                        | 27        | 5.11%   |
| G.Skill                        | 24        | 4.55%   |
| Ramaxel Technology             | 9         | 1.7%    |
| Elpida                         | 7         | 1.33%   |
| A-DATA Technology              | 7         | 1.33%   |
| Transcend                      | 5         | 0.95%   |
| Patriot                        | 5         | 0.95%   |
| Unknown (ABCD)                 | 3         | 0.57%   |
| Silicon Power                  | 2         | 0.38%   |
| Nanya Technology               | 2         | 0.38%   |
| Kingmax                        | 2         | 0.38%   |
| Avant                          | 2         | 0.38%   |
| Unknown                        | 2         | 0.38%   |
| Unknown (0x0B45)               | 1         | 0.19%   |
| Team                           | 1         | 0.19%   |
| Qimonda                        | 1         | 0.19%   |
| Mushkin                        | 1         | 0.19%   |
| MKF_SMBIOS_TYPE17_MANUFACTURER | 1         | 0.19%   |
| Apacer                         | 1         | 0.19%   |
| 48spaces                       | 1         | 0.19%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 9         | 1.59%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 1.06%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.06%   |
| Samsung RAM K3LKCKC0BM-MGCP 8GB LPDDR5 5500MT/s                  | 6         | 1.06%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.88%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 5         | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 0.71%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 4         | 0.71%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 4         | 0.71%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 0.71%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 0.71%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 4         | 0.71%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 0.71%   |
| Crucial RAM CT32G56C46S5.M16D1 32GB SODIMM DDR5 5600MT/s         | 4         | 0.71%   |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 0.71%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 4         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.53%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.53%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.53%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.53%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 0.53%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.53%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.53%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.53%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.53%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.53%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.53%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 3         | 0.53%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1867MT/s              | 3         | 0.53%   |
| Kingston RAM KF3200C16D4/8GX 8GiB DIMM DDR4 3600MT/s             | 3         | 0.53%   |
| Kingston RAM KF3200C16D4/16GX 16GB DIMM DDR4 3733MT/s            | 3         | 0.53%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 3         | 0.53%   |
| Corsair RAM CMW32GX4M2C3200C16 16GB DIMM DDR4 3400MT/s           | 3         | 0.53%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.35%   |
| Unknown RAM Module 4096MB DIMM 667MT/s                           | 2         | 0.35%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.35%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.35%   |
| SK hynix RAM Module 2GB DIMM DDR3 1066MT/s                       | 2         | 0.35%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s             | 2         | 0.35%   |
| SK hynix RAM HMT125S6TFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 2         | 0.35%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 216       | 48.11%  |
| DDR3    | 119       | 26.5%   |
| DDR5    | 35        | 7.8%    |
| LPDDR5  | 20        | 4.45%   |
| DDR2    | 18        | 4.01%   |
| LPDDR4  | 15        | 3.34%   |
| SDRAM   | 10        | 2.23%   |
| LPDDR3  | 9         | 2%      |
| Unknown | 6         | 1.34%   |
| DDR     | 1         | 0.22%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 270       | 60.67%  |
| DIMM         | 133       | 29.89%  |
| Row Of Chips | 32        | 7.19%   |
| Unknown      | 9         | 2.02%   |
| Chip         | 1         | 0.22%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 200       | 41.67%  |
| 4096  | 107       | 22.29%  |
| 16384 | 95        | 19.79%  |
| 2048  | 42        | 8.75%   |
| 32768 | 23        | 4.79%   |
| 1024  | 10        | 2.08%   |
| 512   | 2         | 0.42%   |
| 49152 | 1         | 0.21%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 87        | 18.28%  |
| 1600    | 82        | 17.23%  |
| 2667    | 68        | 14.29%  |
| 2400    | 25        | 5.25%   |
| 2133    | 19        | 3.99%   |
| 1333    | 19        | 3.99%   |
| 5600    | 16        | 3.36%   |
| 3600    | 14        | 2.94%   |
| 667     | 12        | 2.52%   |
| 5500    | 9         | 1.89%   |
| 3733    | 8         | 1.68%   |
| 6000    | 7         | 1.47%   |
| 4800    | 7         | 1.47%   |
| 8400    | 6         | 1.26%   |
| 4267    | 6         | 1.26%   |
| 3400    | 6         | 1.26%   |
| 1067    | 6         | 1.26%   |
| 6400    | 5         | 1.05%   |
| 1334    | 5         | 1.05%   |
| 1066    | 5         | 1.05%   |
| 800     | 5         | 1.05%   |
| 7500    | 4         | 0.84%   |
| 4266    | 4         | 0.84%   |
| 3266    | 4         | 0.84%   |
| 1800    | 4         | 0.84%   |
| 4199    | 3         | 0.63%   |
| 4000    | 3         | 0.63%   |
| 3800    | 3         | 0.63%   |
| 1867    | 3         | 0.63%   |
| 1866    | 3         | 0.63%   |
| 3000    | 2         | 0.42%   |
| 2933    | 2         | 0.42%   |
| 2800    | 2         | 0.42%   |
| 2048    | 2         | 0.42%   |
| 975     | 2         | 0.42%   |
| 533     | 2         | 0.42%   |
| Unknown | 2         | 0.42%   |
| 12800   | 1         | 0.21%   |
| 8000    | 1         | 0.21%   |
| 7467    | 1         | 0.21%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Hewlett-Packard              | 15        | 48.39%  |
| Canon                        | 6         | 19.35%  |
| Brother Industries           | 3         | 9.68%   |
| Prolific Technology          | 2         | 6.45%   |
| Wincor Nixdorf International | 1         | 3.23%   |
| Seiko Epson                  | 1         | 3.23%   |
| Samsung Electronics          | 1         | 3.23%   |
| QinHeng Electronics          | 1         | 3.23%   |
| Pantum                       | 1         | 3.23%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Prolific PL2305 Parallel Port                   | 2         | 6.45%   |
| HP LaserJet M203-M206                           | 2         | 6.45%   |
| HP LaserJet M14-M17                             | 2         | 6.45%   |
| HP DeskJet 3630 series                          | 2         | 6.45%   |
| Brother HL-1110 series                          | 2         | 6.45%   |
| Wincor Nixdorf International POS Printer, TH230 | 1         | 3.23%   |
| Seiko Epson L3050 Series                        | 1         | 3.23%   |
| Samsung Composite Device                        | 1         | 3.23%   |
| QinHeng CH340S                                  | 1         | 3.23%   |
| Pantum P2000                                    | 1         | 3.23%   |
| HP LaserJet P1102                               | 1         | 3.23%   |
| HP LaserJet P1005                               | 1         | 3.23%   |
| HP LaserJet 400 colorMFP M475dw                 | 1         | 3.23%   |
| HP LaserJet 3050                                | 1         | 3.23%   |
| HP Ink Tank Wireless 410 series                 | 1         | 3.23%   |
| HP HP LaserJet M101-M106                        | 1         | 3.23%   |
| HP DeskJet 2700 series                          | 1         | 3.23%   |
| HP DeskJet 2130 series                          | 1         | 3.23%   |
| HP Deskjet 1050 J410                            | 1         | 3.23%   |
| Canon PIXMA MG2500 Series                       | 1         | 3.23%   |
| Canon PIXMA iP4300 Printer                      | 1         | 3.23%   |
| Canon PIXMA iP1800 Printer                      | 1         | 3.23%   |
| Canon LiDE 400                                  | 1         | 3.23%   |
| Canon LBP6670 UFR II                            | 1         | 3.23%   |
| Canon G3030 series                              | 1         | 3.23%   |
| Brother HL-52x0 series                          | 1         | 3.23%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 40%     |
| Canon              | 2         | 40%     |
| Ultima Electronics | 1         | 20%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 2         | 40%     |
| Ultima Artec Ultima 2000                         | 1         | 20%     |
| Canon CanoScan N1240U/LiDE 30                    | 1         | 20%     |
| Canon CanoScan LiDE 220                          | 1         | 20%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 120       | 23.67%  |
| IMC Networks                           | 58        | 11.44%  |
| Quanta                                 | 52        | 10.26%  |
| Realtek Semiconductor                  | 33        | 6.51%   |
| Bison Electronics                      | 32        | 6.31%   |
| Logitech                               | 26        | 5.13%   |
| Microdia                               | 25        | 4.93%   |
| Sunplus Innovation Technology          | 21        | 4.14%   |
| Luxvisions Innotech Limited            | 20        | 3.94%   |
| Syntek                                 | 15        | 2.96%   |
| Suyin                                  | 14        | 2.76%   |
| Lite-On Technology                     | 12        | 2.37%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 2.17%   |
| Sonix Technology                       | 10        | 1.97%   |
| Apple                                  | 10        | 1.97%   |
| Shinetech                              | 7         | 1.38%   |
| SunplusIT                              | 5         | 0.99%   |
| kingcome                               | 5         | 0.99%   |
| Silicon Motion                         | 3         | 0.59%   |
| Samsung Electronics                    | 3         | 0.59%   |
| Anker                                  | 3         | 0.59%   |
| Primax Electronics                     | 2         | 0.39%   |
| Jieli Technology                       | 2         | 0.39%   |
| Genesys Logic                          | 2         | 0.39%   |
| Unknown                                | 2         | 0.39%   |
| Z-Star Microelectronics                | 1         | 0.2%    |
| Xiaomi                                 | 1         | 0.2%    |
| USB CAMERA                             | 1         | 0.2%    |
| Trust                                  | 1         | 0.2%    |
| Ricoh                                  | 1         | 0.2%    |
| Lenovo                                 | 1         | 0.2%    |
| Goertek Electronics                    | 1         | 0.2%    |
| GenesysLogic Technology                | 1         | 0.2%    |
| GEMBIRD                                | 1         | 0.2%    |
| Framework                              | 1         | 0.2%    |
| Cubeternet                             | 1         | 0.2%    |
| Creative Technology                    | 1         | 0.2%    |
| AVerMedia Technologies                 | 1         | 0.2%    |
| Alcor Micro                            | 1         | 0.2%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                         | 24        | 4.72%   |
| IMC Networks Integrated Camera                    | 21        | 4.13%   |
| Chicony HD WebCam                                 | 19        | 3.73%   |
| IMC Networks USB2.0 HD UVC WebCam                 | 17        | 3.34%   |
| IMC Networks USB2.0 VGA UVC WebCam                | 13        | 2.55%   |
| Quanta HD Webcam                                  | 10        | 1.96%   |
| Microdia Integrated_Webcam_HD                     | 10        | 1.96%   |
| Bison Integrated Camera                           | 10        | 1.96%   |
| Syntek Integrated Camera                          | 9         | 1.77%   |
| Quanta VGA WebCam                                 | 9         | 1.77%   |
| Quanta HD User Facing                             | 8         | 1.57%   |
| Realtek Integrated_Webcam_HD                      | 7         | 1.38%   |
| Luxvisions Innotech Limited Integrated RGB Camera | 7         | 1.38%   |
| Lite-On HP HD Camera                              | 7         | 1.38%   |
| Sonix USB2.0 FHD UVC WebCam                       | 6         | 1.18%   |
| Quanta HP True Vision HD Camera                   | 6         | 1.18%   |
| Quanta HP HD Camera                               | 6         | 1.18%   |
| Logitech Webcam C270                              | 6         | 1.18%   |
| Chicony HP HD Camera                              | 6         | 1.18%   |
| Apple FaceTime HD Camera (Built-in)               | 6         | 1.18%   |
| SunplusIT SPCA2650 AV Camera                      | 5         | 0.98%   |
| Shinetech USB2.0 FHD UVC WebCam                   | 5         | 0.98%   |
| Quanta HP TrueVision HD Camera                    | 5         | 0.98%   |
| Logitech Logitech Webcam C925e                    | 5         | 0.98%   |
| kingcome FHD WebCam                               | 5         | 0.98%   |
| Bison Lenovo EasyCamera                           | 5         | 0.98%   |
| Suyin Acer/HP Integrated Webcam [CN0314]          | 4         | 0.79%   |
| Sunplus Integrated_Webcam_HD                      | 4         | 0.79%   |
| Sunplus Full HD webcam                            | 4         | 0.79%   |
| Sonix USB2.0 HD UVC WebCam                        | 4         | 0.79%   |
| Luxvisions Innotech Limited Integrated Camera     | 4         | 0.79%   |
| Chicony USB2.0 VGA UVC WebCam                     | 4         | 0.79%   |
| Chicony HP Wide Vision HD Camera                  | 4         | 0.79%   |
| Chicony HP Webcam                                 | 4         | 0.79%   |
| Bison Integrated RGB Camera                       | 4         | 0.79%   |
| Syntek Lenovo EasyCamera                          | 3         | 0.59%   |
| Suyin WebCam                                      | 3         | 0.59%   |
| Sunplus HD WebCam                                 | 3         | 0.59%   |
| Sunplus Asus Webcam                               | 3         | 0.59%   |
| Samsung Galaxy series, misc. (MTP mode)           | 3         | 0.59%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 41        | 37.27%  |
| Validity Sensors                   | 25        | 22.73%  |
| Shenzhen Goodix Technology         | 14        | 12.73%  |
| AuthenTec                          | 10        | 9.09%   |
| Elan Microelectronics              | 8         | 7.27%   |
| Upek                               | 5         | 4.55%   |
| LighTuning Technology              | 5         | 4.55%   |
| STMicroelectronics                 | 1         | 0.91%   |
| Realtek USB2.0 Finger Print Bridge | 1         | 0.91%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 9.09%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 7.27%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 8         | 7.27%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 7.27%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 6.36%   |
| Elan ELAN:Fingerprint                                                      | 7         | 6.36%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 5.45%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 4.55%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 4.55%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 3.64%   |
| Synaptics UWP WBDI Device                                                  | 4         | 3.64%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 3.64%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 2.73%   |
| Synaptics WBDI                                                             | 3         | 2.73%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 2.73%   |
| AuthenTec AES2810                                                          | 3         | 2.73%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 1.82%   |
| Validity Sensors VFS491                                                    | 2         | 1.82%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 1.82%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 1.82%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 1.82%   |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 1.82%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.91%   |
| Validity Sensors Fingerprint scanner                                       | 1         | 0.91%   |
| Synaptics UWP WBDI                                                         | 1         | 0.91%   |
| Synaptics TouchPad                                                         | 1         | 0.91%   |
| Synaptics  WBDI                                                            | 1         | 0.91%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 0.91%   |
| Shenzhen Goodix Fingerprint Reader                                         | 1         | 0.91%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 0.91%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 1         | 0.91%   |
| AuthenTec Fingerprint Sensor                                               | 1         | 0.91%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 18        | 47.37%  |
| Broadcom                   | 6         | 15.79%  |
| Lenovo                     | 4         | 10.53%  |
| Gemalto (was Gemplus)      | 3         | 7.89%   |
| Aladdin Knowledge Systems  | 2         | 5.26%   |
| Upek                       | 1         | 2.63%   |
| Realtek Semiconductor      | 1         | 2.63%   |
| O2 Micro                   | 1         | 2.63%   |
| MagTek                     | 1         | 2.63%   |
| Athena Smartcard Solutions | 1         | 2.63%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 18        | 47.37%  |
| Lenovo Integrated Smart Card Reader                                          | 4         | 10.53%  |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 2         | 5.26%   |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 2         | 5.26%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 5.26%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 2.63%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 2.63%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 2.63%   |
| MagTek ZCS100                                                                | 1         | 2.63%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 2.63%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 2.63%   |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 2.63%   |
| Broadcom 5880                                                                | 1         | 2.63%   |
| Broadcom 58200                                                               | 1         | 2.63%   |
| Athena Smartcard Solutions ASEDrive V3C                                      | 1         | 2.63%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 535       | 67.64%  |
| 1     | 202       | 25.54%  |
| 2     | 46        | 5.82%   |
| 3     | 7         | 0.88%   |
| 4     | 1         | 0.13%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 106       | 34.75%  |
| Graphics card            | 67        | 21.97%  |
| Net/wireless             | 39        | 12.79%  |
| Chipcard                 | 30        | 9.84%   |
| Multimedia controller    | 16        | 5.25%   |
| Communication controller | 10        | 3.28%   |
| Camera                   | 8         | 2.62%   |
| Net/ethernet             | 6         | 1.97%   |
| Bluetooth                | 6         | 1.97%   |
| Unassigned class         | 4         | 1.31%   |
| Card reader              | 3         | 0.98%   |
| Storage                  | 2         | 0.66%   |
| Sound                    | 2         | 0.66%   |
| Modem                    | 2         | 0.66%   |
| Storage/raid             | 1         | 0.33%   |
| Storage/ide              | 1         | 0.33%   |
| Network                  | 1         | 0.33%   |
| Flash memory             | 1         | 0.33%   |

