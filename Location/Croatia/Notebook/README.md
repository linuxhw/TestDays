Linux in Croatia - Tested Hardware & Statistics (Notebooks)
-----------------------------------------------------------

A project to collect tested hardware configurations for Linux in Croatia.

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

Total: 728

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| HP            | Laptop 15-fc0xxx            | [28e81fb884](https://linux-hardware.org/?probe=28e81fb884) | Jan 03, 2026 |
| HP            | ProBook 655 G1              | [428ad9e1da](https://linux-hardware.org/?probe=428ad9e1da) | Jan 02, 2026 |
| HP            | ProBook 655 G1              | [9d4441d7ff](https://linux-hardware.org/?probe=9d4441d7ff) | Jan 02, 2026 |
| Toshiba       | TECRA S11                   | [5631c19be6](https://linux-hardware.org/?probe=5631c19be6) | Dec 23, 2025 |
| Lenovo        | G500 20236                  | [464de92bda](https://linux-hardware.org/?probe=464de92bda) | Dec 21, 2025 |
| MSI           | GF65 Thin 9SEXR             | [a3bb634520](https://linux-hardware.org/?probe=a3bb634520) | Dec 17, 2025 |
| ASUSTek       | ASUS Vivobook 16 Flip TP... | [c60cbcb548](https://linux-hardware.org/?probe=c60cbcb548) | Dec 14, 2025 |
| Acer          | Aspire ES1-521              | [bdebb56fa9](https://linux-hardware.org/?probe=bdebb56fa9) | Dec 09, 2025 |
| Lenovo        | ThinkPad T480s 20L8S3P80... | [121d47e6e7](https://linux-hardware.org/?probe=121d47e6e7) | Dec 04, 2025 |
| HP            | Laptop 15-fc0xxx            | [e5f5a808d2](https://linux-hardware.org/?probe=e5f5a808d2) | Dec 03, 2025 |
| ASUSTek       | ROG Flow X13 GV301QC_GV3... | [547bd6281f](https://linux-hardware.org/?probe=547bd6281f) | Nov 25, 2025 |
| Dell          | Latitude E5550              | [688c316fc7](https://linux-hardware.org/?probe=688c316fc7) | Nov 22, 2025 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [f8720bcde3](https://linux-hardware.org/?probe=f8720bcde3) | Nov 16, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | [9bf2d8b88d](https://linux-hardware.org/?probe=9bf2d8b88d) | Nov 15, 2025 |
| Dell          | G15 5530                    | [bdca3b23a6](https://linux-hardware.org/?probe=bdca3b23a6) | Nov 08, 2025 |
| HP            | Laptop 15-fc0xxx            | [17c5b06ce7](https://linux-hardware.org/?probe=17c5b06ce7) | Nov 04, 2025 |
| HP            | Laptop 15-fc0xxx            | [96a1529b22](https://linux-hardware.org/?probe=96a1529b22) | Nov 03, 2025 |
| Acer          | Aspire A517-51G             | [cb291106fe](https://linux-hardware.org/?probe=cb291106fe) | Nov 01, 2025 |
| Dell          | G15 5530                    | [88a391c4d8](https://linux-hardware.org/?probe=88a391c4d8) | Oct 26, 2025 |
| ASUSTek       | Vivobook Go E1504GA_E150... | [2f67add42c](https://linux-hardware.org/?probe=2f67add42c) | Oct 22, 2025 |
| Acer          | Aspire E5-771G              | [aba0e77630](https://linux-hardware.org/?probe=aba0e77630) | Oct 21, 2025 |
| ASUSTek       | Vivobook Go E1504GA_E150... | [c0f5c9b6f0](https://linux-hardware.org/?probe=c0f5c9b6f0) | Oct 20, 2025 |
| Unknown       | ECOBOOK                     | [b788d5ae83](https://linux-hardware.org/?probe=b788d5ae83) | Oct 20, 2025 |
| Acer          | Aspire E5-771G              | [b30a98d526](https://linux-hardware.org/?probe=b30a98d526) | Oct 16, 2025 |
| HP            | Laptop 15-fc0xxx            | [2ce6a5ea90](https://linux-hardware.org/?probe=2ce6a5ea90) | Oct 09, 2025 |
| Timi          | TM1701                      | [616de6383b](https://linux-hardware.org/?probe=616de6383b) | Sep 25, 2025 |
| Unknown       | Unknown                     | [3c9e8fc339](https://linux-hardware.org/?probe=3c9e8fc339) | Sep 22, 2025 |
| Unknown       | Unknown                     | [a8e6ab6d44](https://linux-hardware.org/?probe=a8e6ab6d44) | Sep 22, 2025 |
| Acer          | Aspire A15-41M              | [02b7426e3c](https://linux-hardware.org/?probe=02b7426e3c) | Sep 18, 2025 |
| HP            | Laptop 15-fc0xxx            | [e76d1fb91b](https://linux-hardware.org/?probe=e76d1fb91b) | Sep 09, 2025 |
| ASUSTek       | K55A                        | [d5b5b40327](https://linux-hardware.org/?probe=d5b5b40327) | Aug 27, 2025 |
| Acer          | Predator PT516-52s          | [5e1d51a39a](https://linux-hardware.org/?probe=5e1d51a39a) | Aug 19, 2025 |
| Framework     | Laptop 13 (AMD Ryzen 704... | [fc6ce730ce](https://linux-hardware.org/?probe=fc6ce730ce) | Aug 15, 2025 |
| Lenovo        | ThinkPad T480 20L6S69B00    | [719b9e8ea8](https://linux-hardware.org/?probe=719b9e8ea8) | Aug 13, 2025 |
| Lenovo        | IdeaPad 1 15AMN7 82VG       | [831a1ebf42](https://linux-hardware.org/?probe=831a1ebf42) | Aug 13, 2025 |
| Sony          | VPCEH23FD                   | [0aad348b94](https://linux-hardware.org/?probe=0aad348b94) | Aug 11, 2025 |
| HP            | ENVY dv7                    | [fed54497a7](https://linux-hardware.org/?probe=fed54497a7) | Aug 08, 2025 |
| Lenovo        | LOQ 15IRX9 83DV             | [9300462356](https://linux-hardware.org/?probe=9300462356) | Aug 06, 2025 |
| ASUSTek       | ASUS Zenbook 14 UX3405MA... | [1eaebda75c](https://linux-hardware.org/?probe=1eaebda75c) | Jul 30, 2025 |
| Dell          | OptiPlex 9020               | [4b5d8462c2](https://linux-hardware.org/?probe=4b5d8462c2) | Jul 20, 2025 |
| Dell          | Inspiron 3542               | [ee61709e71](https://linux-hardware.org/?probe=ee61709e71) | Jul 13, 2025 |
| Dell          | OptiPlex 9020               | [57e5af17b8](https://linux-hardware.org/?probe=57e5af17b8) | Jul 08, 2025 |
| Dell          | OptiPlex 9020               | [84688234aa](https://linux-hardware.org/?probe=84688234aa) | Jul 08, 2025 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | [2d1183d668](https://linux-hardware.org/?probe=2d1183d668) | Jul 05, 2025 |
| Lenovo        | ThinkBook 16 G7+ IAH 21T... | [e568a33b01](https://linux-hardware.org/?probe=e568a33b01) | Jul 05, 2025 |
| Lenovo        | ThinkBook 16 G7+ IAH 21T... | [581b9195fd](https://linux-hardware.org/?probe=581b9195fd) | Jul 01, 2025 |
| Dell          | Inspiron 3542               | [0d62a30868](https://linux-hardware.org/?probe=0d62a30868) | Jun 29, 2025 |
| ASUSTek       | X540LJ                      | [5cd896f0ab](https://linux-hardware.org/?probe=5cd896f0ab) | Jun 24, 2025 |
| Acer          | Aspire V5-552G              | [526f0fa238](https://linux-hardware.org/?probe=526f0fa238) | Jun 21, 2025 |
| Lenovo        | ThinkPad T450s 20BWS0FU0... | [e9d9c9770c](https://linux-hardware.org/?probe=e9d9c9770c) | Jun 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop K660... | [a8898ab757](https://linux-hardware.org/?probe=a8898ab757) | Jun 10, 2025 |
| HP            | Laptop 15-fc0xxx            | [942b0df642](https://linux-hardware.org/?probe=942b0df642) | Jun 01, 2025 |
| HP            | Laptop 15-fc0xxx            | [002b313a0c](https://linux-hardware.org/?probe=002b313a0c) | May 29, 2025 |
| Toshiba       | Satellite C855-1TV          | [a3b81b03d0](https://linux-hardware.org/?probe=a3b81b03d0) | May 17, 2025 |
| ASUSTek       | ROG Strix G713RM_G713RM     | [db7d498538](https://linux-hardware.org/?probe=db7d498538) | May 16, 2025 |
| TUXEDO        | InfinityBook Pro AMD Gen... | [358fb97668](https://linux-hardware.org/?probe=358fb97668) | May 03, 2025 |
| ASUSTek       | ASUS Zenbook 14 UM3406HA... | [eb54d35bf2](https://linux-hardware.org/?probe=eb54d35bf2) | May 01, 2025 |
| ASUSTek       | ASUS Zenbook 14 UM3406HA... | [1f32cf1a98](https://linux-hardware.org/?probe=1f32cf1a98) | May 01, 2025 |
| HP            | ZBook Ultra G1a 14 inch ... | [cb519eccae](https://linux-hardware.org/?probe=cb519eccae) | Apr 30, 2025 |
| TUXEDO        | InfinityBook Pro AMD Gen... | [6f88c8bbd7](https://linux-hardware.org/?probe=6f88c8bbd7) | Apr 30, 2025 |
| Lenovo        | ThinkPad R61 8932AFG        | [c632fab9cd](https://linux-hardware.org/?probe=c632fab9cd) | Apr 25, 2025 |
| TUXEDO        | InfinityBook Pro AMD Gen... | [611ac358ed](https://linux-hardware.org/?probe=611ac358ed) | Apr 25, 2025 |
| Acer          | Aspire 3810TZ               | [5908d969c4](https://linux-hardware.org/?probe=5908d969c4) | Apr 23, 2025 |
| Dell          | Vostro 15 3510              | [909b7d2338](https://linux-hardware.org/?probe=909b7d2338) | Apr 22, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [74eb28f103](https://linux-hardware.org/?probe=74eb28f103) | Apr 18, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [d5848bec92](https://linux-hardware.org/?probe=d5848bec92) | Apr 17, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [61f7a508c0](https://linux-hardware.org/?probe=61f7a508c0) | Apr 14, 2025 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [094fd397ef](https://linux-hardware.org/?probe=094fd397ef) | Apr 13, 2025 |
| Lenovo        | ThinkBook 16 G7 ARP 21MW    | [cae33b591e](https://linux-hardware.org/?probe=cae33b591e) | Apr 11, 2025 |
| Acer          | Swift SF314-43              | [b022cb2226](https://linux-hardware.org/?probe=b022cb2226) | Apr 11, 2025 |
| ASUSTek       | PRIME B560M-A               | [1a0de9c56d](https://linux-hardware.org/?probe=1a0de9c56d) | Apr 09, 2025 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [0a8c9e7f90](https://linux-hardware.org/?probe=0a8c9e7f90) | Apr 09, 2025 |
| HP            | EliteBook 8470p             | [b9b0897548](https://linux-hardware.org/?probe=b9b0897548) | Apr 07, 2025 |
| Dell          | Vostro 15 3510              | [9206bf9f56](https://linux-hardware.org/?probe=9206bf9f56) | Apr 05, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | [f380989589](https://linux-hardware.org/?probe=f380989589) | Mar 29, 2025 |
| Acer          | Aspire A315-59              | [92a3c2a7ac](https://linux-hardware.org/?probe=92a3c2a7ac) | Mar 27, 2025 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [605e61f244](https://linux-hardware.org/?probe=605e61f244) | Mar 22, 2025 |
| Lenovo        | IdeaPad 100-15IBY 80MJ      | [d828c40581](https://linux-hardware.org/?probe=d828c40581) | Mar 22, 2025 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [5d9bda93a0](https://linux-hardware.org/?probe=5d9bda93a0) | Mar 16, 2025 |
| HP            | OMEN Laptop 15-ek0xxx       | [456198d342](https://linux-hardware.org/?probe=456198d342) | Mar 15, 2025 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [c699c95bf9](https://linux-hardware.org/?probe=c699c95bf9) | Mar 11, 2025 |
| Lenovo        | ThinkBook 16 G7 IML 21MS    | [ace6a8b8c9](https://linux-hardware.org/?probe=ace6a8b8c9) | Mar 10, 2025 |
| MSI           | Katana GF66 12UDO           | [4221ffde63](https://linux-hardware.org/?probe=4221ffde63) | Mar 08, 2025 |
| HP            | ProBook 460 16 inch G11 ... | [32403e5558](https://linux-hardware.org/?probe=32403e5558) | Feb 26, 2025 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | [2ae126e7a3](https://linux-hardware.org/?probe=2ae126e7a3) | Feb 19, 2025 |
| Lenovo        | Legion 5 15IMH6 82NL        | [627d3a0243](https://linux-hardware.org/?probe=627d3a0243) | Feb 16, 2025 |
| HP            | ProBook 460 16 inch G11 ... | [d1951d78ea](https://linux-hardware.org/?probe=d1951d78ea) | Feb 14, 2025 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | [b9c98d07c9](https://linux-hardware.org/?probe=b9c98d07c9) | Feb 11, 2025 |
| HUAWEI        | BOHK-WAX9X                  | [03ab3d58cb](https://linux-hardware.org/?probe=03ab3d58cb) | Feb 10, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | [0c7a85df31](https://linux-hardware.org/?probe=0c7a85df31) | Feb 07, 2025 |
| Lenovo        | ThinkPad SL510 28476LG      | [ff2ac07aef](https://linux-hardware.org/?probe=ff2ac07aef) | Feb 06, 2025 |
| Lenovo        | ThinkPad Edge E125 30352... | [3c0f91ef83](https://linux-hardware.org/?probe=3c0f91ef83) | Feb 06, 2025 |
| HP            | Compaq 8510w                | [4f070686c1](https://linux-hardware.org/?probe=4f070686c1) | Feb 06, 2025 |
| ASUSTek       | VivoBook_ASUSLaptop X150... | [11a7f61b8e](https://linux-hardware.org/?probe=11a7f61b8e) | Feb 06, 2025 |
| HP            | EliteBook 840 G6            | [ccc1e250a7](https://linux-hardware.org/?probe=ccc1e250a7) | Feb 04, 2025 |
| Lenovo        | ThinkPad E16 Gen 2 21M50... | [3a144b039c](https://linux-hardware.org/?probe=3a144b039c) | Feb 02, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [5036c74dce](https://linux-hardware.org/?probe=5036c74dce) | Feb 01, 2025 |
| TUXEDO        | InfinityBook Pro AMD Gen... | [d2c650b264](https://linux-hardware.org/?probe=d2c650b264) | Jan 28, 2025 |
| Gigabyte      | G5 KF5                      | [942f8a4126](https://linux-hardware.org/?probe=942f8a4126) | Jan 27, 2025 |
| Lenovo        | ThinkPad T580 20LAS5BQ00    | [c3993d3bc3](https://linux-hardware.org/?probe=c3993d3bc3) | Jan 25, 2025 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [8f3d9a7482](https://linux-hardware.org/?probe=8f3d9a7482) | Jan 24, 2025 |
| Toshiba       | Satellite L655              | [ad37b67f87](https://linux-hardware.org/?probe=ad37b67f87) | Jan 24, 2025 |
| HP            | ZBook 17                    | [fb0cd98066](https://linux-hardware.org/?probe=fb0cd98066) | Jan 24, 2025 |
| ASUSTek       | ZenBook Pro 15 UX550GDX_... | [1463c39f38](https://linux-hardware.org/?probe=1463c39f38) | Jan 17, 2025 |
| ASUSTek       | ASUS Vivobook S 16 M5606... | [d0fe08663c](https://linux-hardware.org/?probe=d0fe08663c) | Jan 14, 2025 |
| Lenovo        | ThinkPad T480 20L6S7SG02    | [09b32b0543](https://linux-hardware.org/?probe=09b32b0543) | Jan 13, 2025 |
| Tactus        | GeoBook 140                 | [3f98d02202](https://linux-hardware.org/?probe=3f98d02202) | Jan 12, 2025 |
| Tactus        | GeoBook 140                 | [ac69ce3b3b](https://linux-hardware.org/?probe=ac69ce3b3b) | Jan 11, 2025 |
| HP            | EliteBook 850 G7 Noteboo... | [f6e6f6add7](https://linux-hardware.org/?probe=f6e6f6add7) | Jan 10, 2025 |
| HP            | ProBook 650 G4              | [60151c3e89](https://linux-hardware.org/?probe=60151c3e89) | Jan 10, 2025 |
| HP            | ProBook 650 G4              | [960f70006c](https://linux-hardware.org/?probe=960f70006c) | Jan 10, 2025 |
| ASUSTek       | ROG Zephyrus G14 GA402XV... | [54bbb73376](https://linux-hardware.org/?probe=54bbb73376) | Jan 08, 2025 |
| Lenovo        | ThinkPad P17 Gen 1 20SQS... | [4fc43ed5a9](https://linux-hardware.org/?probe=4fc43ed5a9) | Jan 04, 2025 |
| Lenovo        | G585 20137                  | [cfbfe12819](https://linux-hardware.org/?probe=cfbfe12819) | Dec 30, 2024 |
| MSI           | Katana GF76 12UEOK          | [a3467015fd](https://linux-hardware.org/?probe=a3467015fd) | Dec 26, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [edc19c7235](https://linux-hardware.org/?probe=edc19c7235) | Dec 15, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [d557fc1733](https://linux-hardware.org/?probe=d557fc1733) | Dec 14, 2024 |
| Lenovo        | ThinkPad X395 20NL000HMH    | [2d86c3a6a1](https://linux-hardware.org/?probe=2d86c3a6a1) | Dec 14, 2024 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [8fd0a47047](https://linux-hardware.org/?probe=8fd0a47047) | Dec 13, 2024 |
| Dell          | Inspiron 3501               | [6d66838249](https://linux-hardware.org/?probe=6d66838249) | Dec 13, 2024 |
| HP            | EliteBook 2170p             | [39de9fd95f](https://linux-hardware.org/?probe=39de9fd95f) | Dec 04, 2024 |
| Schenker      | XMG EVO (M24)               | [605df9f69c](https://linux-hardware.org/?probe=605df9f69c) | Nov 22, 2024 |
| Schenker      | XMG EVO (M24)               | [dd1c282bdb](https://linux-hardware.org/?probe=dd1c282bdb) | Nov 22, 2024 |
| Lenovo        | 3000 N200 0769BLG           | [d58726bb7b](https://linux-hardware.org/?probe=d58726bb7b) | Nov 18, 2024 |
| Lenovo        | 3000 N200 0769BLG           | [60ef264f93](https://linux-hardware.org/?probe=60ef264f93) | Nov 16, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [e88d7b46ce](https://linux-hardware.org/?probe=e88d7b46ce) | Nov 12, 2024 |
| MSI           | GP66 Leopard 10UG           | [5ab759967a](https://linux-hardware.org/?probe=5ab759967a) | Nov 08, 2024 |
| Acer          | Aspire E5-571G              | [77228343b8](https://linux-hardware.org/?probe=77228343b8) | Nov 04, 2024 |
| Acer          | Aspire E5-571G              | [c3f4b3765a](https://linux-hardware.org/?probe=c3f4b3765a) | Nov 04, 2024 |
| HP            | 620                         | [62a5cced4d](https://linux-hardware.org/?probe=62a5cced4d) | Nov 03, 2024 |
| Acer          | Aspire A515-57              | [6ea530d4cf](https://linux-hardware.org/?probe=6ea530d4cf) | Oct 29, 2024 |
| Lenovo        | IdeaPad 3 17IAU7 82RL       | [2de5d8141c](https://linux-hardware.org/?probe=2de5d8141c) | Oct 29, 2024 |
| HP            | Laptop 15s-fq2xxx           | [b784a172f1](https://linux-hardware.org/?probe=b784a172f1) | Oct 29, 2024 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | [b832baec89](https://linux-hardware.org/?probe=b832baec89) | Oct 29, 2024 |
| Apple         | MacBookAir5,2               | [7b9ad509e7](https://linux-hardware.org/?probe=7b9ad509e7) | Oct 21, 2024 |
| Acer          | Aspire E1-522               | [5e76308cf8](https://linux-hardware.org/?probe=5e76308cf8) | Oct 21, 2024 |
| ASUSTek       | X556UQ                      | [046fdf8e88](https://linux-hardware.org/?probe=046fdf8e88) | Oct 19, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [fab35a6539](https://linux-hardware.org/?probe=fab35a6539) | Oct 19, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [b6c163527d](https://linux-hardware.org/?probe=b6c163527d) | Oct 17, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X521... | [a3e77b53eb](https://linux-hardware.org/?probe=a3e77b53eb) | Oct 16, 2024 |
| Lenovo        | ThinkPad T460 20FN003LGE    | [2ab3d1b003](https://linux-hardware.org/?probe=2ab3d1b003) | Oct 13, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [bb1321ebd2](https://linux-hardware.org/?probe=bb1321ebd2) | Oct 05, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [3f906c01d2](https://linux-hardware.org/?probe=3f906c01d2) | Oct 05, 2024 |
| eMachines     | E725 V1.03                  | [4a9590683e](https://linux-hardware.org/?probe=4a9590683e) | Oct 03, 2024 |
| ASUSTek       | E402SA                      | [05b9b51859](https://linux-hardware.org/?probe=05b9b51859) | Sep 28, 2024 |
| Acer          | Aspire A515-57              | [5bb85acaa8](https://linux-hardware.org/?probe=5bb85acaa8) | Sep 25, 2024 |
| HP            | EliteBook 640 14 inch G1... | [1a56c410de](https://linux-hardware.org/?probe=1a56c410de) | Sep 24, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [b2bda3297a](https://linux-hardware.org/?probe=b2bda3297a) | Sep 09, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [97578fa017](https://linux-hardware.org/?probe=97578fa017) | Sep 09, 2024 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [7ab4f22e0a](https://linux-hardware.org/?probe=7ab4f22e0a) | Sep 08, 2024 |
| ASUSTek       | TUF Gaming FX705GD_FX705... | [b200161c65](https://linux-hardware.org/?probe=b200161c65) | Sep 08, 2024 |
| Toshiba       | Satellite C850-1GD          | [e88a301000](https://linux-hardware.org/?probe=e88a301000) | Sep 06, 2024 |
| Toshiba       | Satellite C850-1GD          | [c3fdc37622](https://linux-hardware.org/?probe=c3fdc37622) | Sep 04, 2024 |
| HP            | Pavilion Gaming Laptop 1... | [95c264530c](https://linux-hardware.org/?probe=95c264530c) | Aug 29, 2024 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [8a2e220edd](https://linux-hardware.org/?probe=8a2e220edd) | Aug 26, 2024 |
| HP            | Compaq 6730s                | [5477f5c6aa](https://linux-hardware.org/?probe=5477f5c6aa) | Aug 20, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [30973be0c7](https://linux-hardware.org/?probe=30973be0c7) | Aug 19, 2024 |
| Lenovo        | ThinkBook 16 G6 IRL 21KH    | [6d5345fe36](https://linux-hardware.org/?probe=6d5345fe36) | Aug 19, 2024 |
| Lenovo        | Legion 5 15IMH05 82AU       | [a44c4ca6c4](https://linux-hardware.org/?probe=a44c4ca6c4) | Jul 26, 2024 |
| Acer          | Aspire 3810TZ               | [8a845f0a93](https://linux-hardware.org/?probe=8a845f0a93) | Jul 13, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [6e6ba41a40](https://linux-hardware.org/?probe=6e6ba41a40) | Jul 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [e9fa4e7bea](https://linux-hardware.org/?probe=e9fa4e7bea) | Jul 09, 2024 |
| Acer          | Swift SFG14-42              | [3623aaf512](https://linux-hardware.org/?probe=3623aaf512) | Jul 05, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [7ede8c3d44](https://linux-hardware.org/?probe=7ede8c3d44) | Jul 04, 2024 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | [553f4c84c7](https://linux-hardware.org/?probe=553f4c84c7) | Jul 02, 2024 |
| Lenovo        | IdeaPad Slim 3 15IAH8 83... | [c9e7579303](https://linux-hardware.org/?probe=c9e7579303) | Jul 01, 2024 |
| MSI           | GP66 Leopard 10UG           | [c50af3b6c8](https://linux-hardware.org/?probe=c50af3b6c8) | Jun 22, 2024 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [f0905083d1](https://linux-hardware.org/?probe=f0905083d1) | Jun 22, 2024 |
| HP            | Laptop 15-fc0xxx            | [ec2b1ed18c](https://linux-hardware.org/?probe=ec2b1ed18c) | Jun 14, 2024 |
| HP            | Laptop 15-fc0xxx            | [368a216085](https://linux-hardware.org/?probe=368a216085) | Jun 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | [faaa0aa78d](https://linux-hardware.org/?probe=faaa0aa78d) | Jun 08, 2024 |
| HP            | ProBook 640 G8 Notebook ... | [6469f59ede](https://linux-hardware.org/?probe=6469f59ede) | Jun 01, 2024 |
| HP            | Compaq 8710w (GC124EA#AB... | [fbc21ef970](https://linux-hardware.org/?probe=fbc21ef970) | May 31, 2024 |
| HP            | Compaq 8710w (GC124EA#AB... | [93d744065c](https://linux-hardware.org/?probe=93d744065c) | May 30, 2024 |
| Lenovo        | ThinkPad E16 Gen 1 21JN0... | [0bd725fafa](https://linux-hardware.org/?probe=0bd725fafa) | May 30, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | [da180bf1b1](https://linux-hardware.org/?probe=da180bf1b1) | May 27, 2024 |
| Dell          | Vostro 15 3510              | [6b8a338778](https://linux-hardware.org/?probe=6b8a338778) | May 15, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [ed064c4025](https://linux-hardware.org/?probe=ed064c4025) | May 08, 2024 |
| Lenovo        | Yoga 2 13 20344             | [5b40331b05](https://linux-hardware.org/?probe=5b40331b05) | May 03, 2024 |
| Lenovo        | Yoga 2 13 20344             | [440bf944f3](https://linux-hardware.org/?probe=440bf944f3) | May 03, 2024 |
| HP            | OMEN by Laptop 15-dc0xxx    | [23c1b45346](https://linux-hardware.org/?probe=23c1b45346) | May 02, 2024 |
| Tactus        | GeoBook 140                 | [aa4d027e01](https://linux-hardware.org/?probe=aa4d027e01) | Apr 19, 2024 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [f7ab9249b4](https://linux-hardware.org/?probe=f7ab9249b4) | Apr 11, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [1d9ef42930](https://linux-hardware.org/?probe=1d9ef42930) | Apr 11, 2024 |
| Dell          | Inspiron 3521               | [ee70d25db0](https://linux-hardware.org/?probe=ee70d25db0) | Apr 04, 2024 |
| Tactus        | GeoBook 140                 | [9e26c5ce44](https://linux-hardware.org/?probe=9e26c5ce44) | Apr 02, 2024 |
| HP            | Notebook                    | [af4830976e](https://linux-hardware.org/?probe=af4830976e) | Apr 01, 2024 |
| Dell          | Inspiron 3542               | [f1a4abd6dc](https://linux-hardware.org/?probe=f1a4abd6dc) | Mar 31, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | [000b3bdea6](https://linux-hardware.org/?probe=000b3bdea6) | Mar 29, 2024 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | [d3533da3cc](https://linux-hardware.org/?probe=d3533da3cc) | Mar 25, 2024 |
| HP            | ZBook 17                    | [02d8d9dcf1](https://linux-hardware.org/?probe=02d8d9dcf1) | Mar 23, 2024 |
| Acer          | Aspire A515-47              | [e23d4b05d8](https://linux-hardware.org/?probe=e23d4b05d8) | Mar 19, 2024 |
| HP            | ZBook Firefly 14 inch G8... | [74a0af3ace](https://linux-hardware.org/?probe=74a0af3ace) | Mar 19, 2024 |
| HP            | ProBook 470 G3              | [7acbeb9e50](https://linux-hardware.org/?probe=7acbeb9e50) | Mar 12, 2024 |
| Dell          | System XPS L702X            | [09313dcc56](https://linux-hardware.org/?probe=09313dcc56) | Mar 11, 2024 |
| HP            | Pavilion Power Laptop 15... | [67978c3e25](https://linux-hardware.org/?probe=67978c3e25) | Mar 10, 2024 |
| HP            | ZBook 17                    | [9535fdaf2b](https://linux-hardware.org/?probe=9535fdaf2b) | Mar 10, 2024 |
| HP            | Laptop 17-bs0xx             | [019d8a8d68](https://linux-hardware.org/?probe=019d8a8d68) | Mar 01, 2024 |
| Lenovo        | ThinkPad T530 2429AL0       | [6040b9b7e2](https://linux-hardware.org/?probe=6040b9b7e2) | Feb 24, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | [8173a2268e](https://linux-hardware.org/?probe=8173a2268e) | Feb 24, 2024 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | [d91a07c2e1](https://linux-hardware.org/?probe=d91a07c2e1) | Feb 22, 2024 |
| Lenovo        | ThinkPad T16 Gen 1 21CHC... | [4e64450aa5](https://linux-hardware.org/?probe=4e64450aa5) | Feb 21, 2024 |
| Dell          | Latitude D530               | [0885268edd](https://linux-hardware.org/?probe=0885268edd) | Feb 20, 2024 |
| Dell          | Latitude D530               | [e4d1a73b6e](https://linux-hardware.org/?probe=e4d1a73b6e) | Feb 20, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | [1982f26149](https://linux-hardware.org/?probe=1982f26149) | Feb 12, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop M650... | [d83aac3c35](https://linux-hardware.org/?probe=d83aac3c35) | Feb 11, 2024 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | [f1ffdd8987](https://linux-hardware.org/?probe=f1ffdd8987) | Feb 11, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [d916f30fdc](https://linux-hardware.org/?probe=d916f30fdc) | Feb 10, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | [5c94c6fba5](https://linux-hardware.org/?probe=5c94c6fba5) | Feb 07, 2024 |
| Acer          | Swift SFG14-42              | [15da646623](https://linux-hardware.org/?probe=15da646623) | Jan 11, 2024 |
| HP            | ZBook Fury 17.3 inch G8 ... | [7013d64a90](https://linux-hardware.org/?probe=7013d64a90) | Jan 09, 2024 |
| Dell          | Inspiron 3521               | [2b8bf09bd1](https://linux-hardware.org/?probe=2b8bf09bd1) | Jan 08, 2024 |
| Dell          | Inspiron 3521               | [2a29a6c24b](https://linux-hardware.org/?probe=2a29a6c24b) | Jan 08, 2024 |
| Apple         | MacBookAir7,2               | [810f81c66e](https://linux-hardware.org/?probe=810f81c66e) | Jan 06, 2024 |
| Dynabook      | Satellite Pro C40-G-109     | [0247395541](https://linux-hardware.org/?probe=0247395541) | Jan 05, 2024 |
| Unknown       | Apple MacBook Air (13-in... | [834855dcac](https://linux-hardware.org/?probe=834855dcac) | Jan 01, 2024 |
| HP            | Pavilion dv7                | [4b1ea284d3](https://linux-hardware.org/?probe=4b1ea284d3) | Dec 28, 2023 |
| Acer          | Nitro AN515-55              | [656732b40e](https://linux-hardware.org/?probe=656732b40e) | Dec 12, 2023 |
| Acer          | Nitro AN515-55              | [367489ed4f](https://linux-hardware.org/?probe=367489ed4f) | Dec 10, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | [0137a4a556](https://linux-hardware.org/?probe=0137a4a556) | Nov 23, 2023 |
| eMachines     | E725 V1.03                  | [bd5b32a320](https://linux-hardware.org/?probe=bd5b32a320) | Nov 20, 2023 |
| eMachines     | E725 V1.03                  | [bd29f2ff41](https://linux-hardware.org/?probe=bd29f2ff41) | Nov 19, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [9b2d42ff24](https://linux-hardware.org/?probe=9b2d42ff24) | Nov 15, 2023 |
| HP            | ZBook Fury 17.3 inch G8 ... | [f5413c3dd5](https://linux-hardware.org/?probe=f5413c3dd5) | Nov 15, 2023 |
| Apple         | MacBookPro12,1              | [982139b13a](https://linux-hardware.org/?probe=982139b13a) | Nov 11, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [4fd542edf2](https://linux-hardware.org/?probe=4fd542edf2) | Nov 11, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | [4bfe797838](https://linux-hardware.org/?probe=4bfe797838) | Nov 05, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M150... | [4b04b9ef25](https://linux-hardware.org/?probe=4b04b9ef25) | Nov 02, 2023 |
| Acer          | AOD270                      | [83c4a5920f](https://linux-hardware.org/?probe=83c4a5920f) | Oct 29, 2023 |
| Lenovo        | ThinkPad T450s 20BWS58K0... | [11b2f76301](https://linux-hardware.org/?probe=11b2f76301) | Oct 29, 2023 |
| HP            | Presario CQ57               | [f35a975672](https://linux-hardware.org/?probe=f35a975672) | Oct 29, 2023 |
| HP            | ZBook Firefly 14 inch G8... | [bd82dd57be](https://linux-hardware.org/?probe=bd82dd57be) | Oct 27, 2023 |
| Apple         | MacBookAir5,2               | [deeaf6af5b](https://linux-hardware.org/?probe=deeaf6af5b) | Oct 19, 2023 |
| ASUSTek       | TUF Gaming FX505GE_FX505... | [c8f55c449a](https://linux-hardware.org/?probe=c8f55c449a) | Oct 19, 2023 |
| HP            | Laptop 15-fd0xxx            | [0e6cc9fc48](https://linux-hardware.org/?probe=0e6cc9fc48) | Oct 16, 2023 |
| ASUSTek       | Zenbook UM3402YAR_UM3402... | [6c49286a6c](https://linux-hardware.org/?probe=6c49286a6c) | Oct 14, 2023 |
| Dell          | Inspiron 5570               | [7975260826](https://linux-hardware.org/?probe=7975260826) | Sep 29, 2023 |
| Dell          | Latitude 5431               | [d9ea685862](https://linux-hardware.org/?probe=d9ea685862) | Sep 27, 2023 |
| Dell          | Vostro 3500                 | [fac9ee2e6e](https://linux-hardware.org/?probe=fac9ee2e6e) | Sep 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [0e32901b18](https://linux-hardware.org/?probe=0e32901b18) | Sep 27, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [c8ee0a00a5](https://linux-hardware.org/?probe=c8ee0a00a5) | Sep 06, 2023 |
| Apple         | MacBookPro11,4              | [c833e40c97](https://linux-hardware.org/?probe=c833e40c97) | Sep 01, 2023 |
| Acer          | Predator PH517-51           | [294343383a](https://linux-hardware.org/?probe=294343383a) | Aug 30, 2023 |
| Acer          | Predator PH517-51           | [adba295596](https://linux-hardware.org/?probe=adba295596) | Aug 30, 2023 |
| Acer          | Nitro AN515-44              | [caaf599d6a](https://linux-hardware.org/?probe=caaf599d6a) | Aug 29, 2023 |
| Acer          | Nitro AN515-44              | [f91274084a](https://linux-hardware.org/?probe=f91274084a) | Aug 29, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [4bc3ed94ce](https://linux-hardware.org/?probe=4bc3ed94ce) | Aug 28, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [8acc158836](https://linux-hardware.org/?probe=8acc158836) | Aug 27, 2023 |
| HUAWEI        | NBLB-WAX9N                  | [1f6e4f9676](https://linux-hardware.org/?probe=1f6e4f9676) | Aug 21, 2023 |
| Lenovo        | ThinkPad T495s 20QJ001MG... | [3ac30cf2d0](https://linux-hardware.org/?probe=3ac30cf2d0) | Aug 16, 2023 |
| HP            | EliteBook 840 14 inch G1... | [73b7fc1fc9](https://linux-hardware.org/?probe=73b7fc1fc9) | Aug 11, 2023 |
| Acer          | Aspire 5736Z                | [de1addc70b](https://linux-hardware.org/?probe=de1addc70b) | Aug 03, 2023 |
| ASUSTek       | X540NA                      | [c7724d9c7c](https://linux-hardware.org/?probe=c7724d9c7c) | Aug 02, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | [8b7ca3c460](https://linux-hardware.org/?probe=8b7ca3c460) | Jul 21, 2023 |
| Dell          | Latitude 5520               | [070380568b](https://linux-hardware.org/?probe=070380568b) | Jul 21, 2023 |
| Dell          | Inspiron 3542               | [043258de54](https://linux-hardware.org/?probe=043258de54) | Jul 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [567736ec02](https://linux-hardware.org/?probe=567736ec02) | Jul 14, 2023 |
| Acer          | Swift SF314-58G             | [795625662c](https://linux-hardware.org/?probe=795625662c) | Jul 12, 2023 |
| Acer          | Swift SF314-58G             | [c01b74af46](https://linux-hardware.org/?probe=c01b74af46) | Jul 12, 2023 |
| Dell          | OptiPlex 9020               | [3384a64b67](https://linux-hardware.org/?probe=3384a64b67) | Jul 10, 2023 |
| Timi          | TM1701                      | [5dee3c6b81](https://linux-hardware.org/?probe=5dee3c6b81) | Jul 01, 2023 |
| Apple         | MacBookAir5,2               | [8f6d75c75e](https://linux-hardware.org/?probe=8f6d75c75e) | Jun 22, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [c1472b1c25](https://linux-hardware.org/?probe=c1472b1c25) | Jun 18, 2023 |
| Apple         | MacBookAir5,2               | [18e80281cc](https://linux-hardware.org/?probe=18e80281cc) | Jun 10, 2023 |
| Apple         | MacBookAir5,2               | [f7bd03dbb9](https://linux-hardware.org/?probe=f7bd03dbb9) | Jun 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [bf403bb6d8](https://linux-hardware.org/?probe=bf403bb6d8) | Jun 06, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [2667cb67a3](https://linux-hardware.org/?probe=2667cb67a3) | May 30, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W4... | [0568aa067a](https://linux-hardware.org/?probe=0568aa067a) | May 30, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [c8e0efc288](https://linux-hardware.org/?probe=c8e0efc288) | May 29, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [da399dc7cc](https://linux-hardware.org/?probe=da399dc7cc) | May 29, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [72f5c85f7f](https://linux-hardware.org/?probe=72f5c85f7f) | May 26, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | [913f21a49c](https://linux-hardware.org/?probe=913f21a49c) | May 25, 2023 |
| Acer          | Aspire A515-57              | [3272ba5e49](https://linux-hardware.org/?probe=3272ba5e49) | May 19, 2023 |
| Tactus        | GeoBook 140                 | [534c32884a](https://linux-hardware.org/?probe=534c32884a) | May 19, 2023 |
| Schenker      | VISION (E22)                | [582ac3cbf5](https://linux-hardware.org/?probe=582ac3cbf5) | May 13, 2023 |
| Acer          | Aspire E5-553G              | [cd65f81693](https://linux-hardware.org/?probe=cd65f81693) | May 11, 2023 |
| Acer          | Aspire A315-23              | [2c96614c16](https://linux-hardware.org/?probe=2c96614c16) | May 11, 2023 |
| Acer          | Aspire E5-553G              | [5312325c90](https://linux-hardware.org/?probe=5312325c90) | May 10, 2023 |
| Lenovo        | ThinkPad T530 2394CE2       | [d232fefed2](https://linux-hardware.org/?probe=d232fefed2) | May 09, 2023 |
| Acer          | Predator PH315-53           | [efb597952f](https://linux-hardware.org/?probe=efb597952f) | May 07, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [1c98821416](https://linux-hardware.org/?probe=1c98821416) | May 03, 2023 |
| Acer          | TravelMate 5730             | [e74d115d0d](https://linux-hardware.org/?probe=e74d115d0d) | Apr 29, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [5cb9fe1ae9](https://linux-hardware.org/?probe=5cb9fe1ae9) | Apr 28, 2023 |
| ASUSTek       | Zenbook UM5302TA_UM5302T... | [3669ef1de9](https://linux-hardware.org/?probe=3669ef1de9) | Apr 28, 2023 |
| Lenovo        | 3000 N200 0769A97           | [a293f4f1f7](https://linux-hardware.org/?probe=a293f4f1f7) | Apr 26, 2023 |
| TUXEDO        | Pulse 15 Gen1               | [0db2c54b2a](https://linux-hardware.org/?probe=0db2c54b2a) | Apr 24, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | [b3c9b78fec](https://linux-hardware.org/?probe=b3c9b78fec) | Apr 13, 2023 |
| HP            | Pavilion Gaming Laptop 1... | [bba5f185af](https://linux-hardware.org/?probe=bba5f185af) | Apr 13, 2023 |
| Lenovo        | ThinkPad T530 2394BF7       | [5161d2f521](https://linux-hardware.org/?probe=5161d2f521) | Apr 11, 2023 |
| Acer          | Nitro AN515-55              | [64f96c6fde](https://linux-hardware.org/?probe=64f96c6fde) | Apr 07, 2023 |
| Lenovo        | V15-ADA 82C7                | [917714b1be](https://linux-hardware.org/?probe=917714b1be) | Apr 06, 2023 |
| Lenovo        | V15-ADA 82C7                | [ad148ede52](https://linux-hardware.org/?probe=ad148ede52) | Apr 06, 2023 |
| Dell          | Latitude 5530               | [802248e232](https://linux-hardware.org/?probe=802248e232) | Apr 03, 2023 |
| Dell          | Latitude 5530               | [e4688e2ef8](https://linux-hardware.org/?probe=e4688e2ef8) | Apr 01, 2023 |
| ASUSTek       | N551JM                      | [b8e3d627b5](https://linux-hardware.org/?probe=b8e3d627b5) | Mar 27, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [2b0f3e8867](https://linux-hardware.org/?probe=2b0f3e8867) | Mar 25, 2023 |
| Fujitsu Si... | AMILO Pro Edition V3505     | [8bb2484825](https://linux-hardware.org/?probe=8bb2484825) | Mar 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | [4c7add7cd1](https://linux-hardware.org/?probe=4c7add7cd1) | Mar 21, 2023 |
| Tactus        | GeoBook 140                 | [5efd6f0674](https://linux-hardware.org/?probe=5efd6f0674) | Mar 20, 2023 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | [55dc5e3ef4](https://linux-hardware.org/?probe=55dc5e3ef4) | Mar 19, 2023 |
| HP            | EliteBook 8730w             | [a012fe4bd2](https://linux-hardware.org/?probe=a012fe4bd2) | Mar 10, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | [b349a8eedd](https://linux-hardware.org/?probe=b349a8eedd) | Mar 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | [314cad4a2f](https://linux-hardware.org/?probe=314cad4a2f) | Mar 07, 2023 |
| Dell          | OptiPlex 9020               | [dda13d9c8e](https://linux-hardware.org/?probe=dda13d9c8e) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | [8e02418ca7](https://linux-hardware.org/?probe=8e02418ca7) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | [5510fed545](https://linux-hardware.org/?probe=5510fed545) | Mar 04, 2023 |
| Acer          | Swift SF314-43              | [4f2c05c854](https://linux-hardware.org/?probe=4f2c05c854) | Feb 28, 2023 |
| Valve         | Jupiter                     | [e2f06dcb4a](https://linux-hardware.org/?probe=e2f06dcb4a) | Feb 24, 2023 |
| Dell          | System XPS L702X            | [81f9738975](https://linux-hardware.org/?probe=81f9738975) | Feb 16, 2023 |
| Unknown       | Apple MacBook Pro (13-in... | [1d5a0bc43f](https://linux-hardware.org/?probe=1d5a0bc43f) | Feb 14, 2023 |
| Lenovo        | ThinkPad T540p 20BFA183A... | [2705e3d0c5](https://linux-hardware.org/?probe=2705e3d0c5) | Feb 12, 2023 |
| Acer          | Nitro AN515-55              | [b4b0bee06c](https://linux-hardware.org/?probe=b4b0bee06c) | Feb 08, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [9f76193ccc](https://linux-hardware.org/?probe=9f76193ccc) | Jan 29, 2023 |
| HP            | EliteBook 855 G7 Noteboo... | [34882391f3](https://linux-hardware.org/?probe=34882391f3) | Jan 25, 2023 |
| HP            | Laptop 15-bs1xx             | [76689345ef](https://linux-hardware.org/?probe=76689345ef) | Jan 19, 2023 |
| Toshiba       | Satellite P200              | [478f5dc5cb](https://linux-hardware.org/?probe=478f5dc5cb) | Jan 18, 2023 |
| HP            | Laptop 15s-eq2xxx           | [29ff669f2c](https://linux-hardware.org/?probe=29ff669f2c) | Jan 14, 2023 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ef10fbe492](https://linux-hardware.org/?probe=ef10fbe492) | Jan 09, 2023 |
| Dell          | Inspiron 15-3567            | [5aaaf24b85](https://linux-hardware.org/?probe=5aaaf24b85) | Jan 09, 2023 |
| Samsung       | SBB-DA                      | [a4c6b4f454](https://linux-hardware.org/?probe=a4c6b4f454) | Jan 07, 2023 |
| Acer          | Nitro AN515-55              | [800f20e309](https://linux-hardware.org/?probe=800f20e309) | Jan 07, 2023 |
| ASUSTek       | N551JM                      | [f6de50a76b](https://linux-hardware.org/?probe=f6de50a76b) | Jan 04, 2023 |
| HP            | OMEN by Laptop              | [e703dd0215](https://linux-hardware.org/?probe=e703dd0215) | Jan 04, 2023 |
| ASUSTek       | N551JM                      | [3ba1d0e689](https://linux-hardware.org/?probe=3ba1d0e689) | Jan 03, 2023 |
| Acer          | Aspire A715-41G             | [92f3c92191](https://linux-hardware.org/?probe=92f3c92191) | Dec 29, 2022 |
| Acer          | Swift SF314-41              | [2923c4c0fc](https://linux-hardware.org/?probe=2923c4c0fc) | Dec 28, 2022 |
| Dell          | Inspiron N5110              | [9b8756cdd0](https://linux-hardware.org/?probe=9b8756cdd0) | Dec 17, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | [b2b93008c3](https://linux-hardware.org/?probe=b2b93008c3) | Dec 17, 2022 |
| HP            | Laptop 15-db1xxx            | [3dcbd61f9e](https://linux-hardware.org/?probe=3dcbd61f9e) | Dec 12, 2022 |
| Dell          | Inspiron N5110              | [9815b67f0b](https://linux-hardware.org/?probe=9815b67f0b) | Dec 06, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [d632edc927](https://linux-hardware.org/?probe=d632edc927) | Dec 05, 2022 |
| Lenovo        | Legion Y540-15IRH-PG0 81... | [412bffea3b](https://linux-hardware.org/?probe=412bffea3b) | Dec 05, 2022 |
| ASUSTek       | X550LB                      | [466592b744](https://linux-hardware.org/?probe=466592b744) | Nov 20, 2022 |
| ASUSTek       | X550LB                      | [3ca5ee2f7a](https://linux-hardware.org/?probe=3ca5ee2f7a) | Nov 20, 2022 |
| Apple         | MacBookPro12,1              | [9e16721568](https://linux-hardware.org/?probe=9e16721568) | Nov 17, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [311c90573c](https://linux-hardware.org/?probe=311c90573c) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [1198a061e1](https://linux-hardware.org/?probe=1198a061e1) | Nov 12, 2022 |
| HP            | EliteBook 855 G7 Noteboo... | [de85ac10f6](https://linux-hardware.org/?probe=de85ac10f6) | Nov 09, 2022 |
| ASUSTek       | Zenbook UX5401EA_UX5401E... | [84bf8d9578](https://linux-hardware.org/?probe=84bf8d9578) | Nov 05, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | [9b61195a2a](https://linux-hardware.org/?probe=9b61195a2a) | Nov 01, 2022 |
| Dell          | Studio 1735                 | [8f070a2831](https://linux-hardware.org/?probe=8f070a2831) | Oct 30, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [24b035a7a4](https://linux-hardware.org/?probe=24b035a7a4) | Oct 25, 2022 |
| Dell          | Studio 1735                 | [21959a7db7](https://linux-hardware.org/?probe=21959a7db7) | Oct 24, 2022 |
| ASUSTek       | K53U                        | [d178c463df](https://linux-hardware.org/?probe=d178c463df) | Oct 24, 2022 |
| Dell          | Studio 1735                 | [4385640990](https://linux-hardware.org/?probe=4385640990) | Oct 23, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| Acer          | Swift SF314-54              | [04fed978ae](https://linux-hardware.org/?probe=04fed978ae) | Oct 18, 2022 |
| Lenovo        | ThinkPad T470s 20HGS1R90... | [e3eba59f05](https://linux-hardware.org/?probe=e3eba59f05) | Oct 17, 2022 |
| Acer          | Aspire A317-53              | [dadf436fd1](https://linux-hardware.org/?probe=dadf436fd1) | Oct 10, 2022 |
| HP            | EliteBook 8730w             | [e7545a94b2](https://linux-hardware.org/?probe=e7545a94b2) | Oct 09, 2022 |
| HP            | EliteBook 8730w             | [b938a96086](https://linux-hardware.org/?probe=b938a96086) | Oct 09, 2022 |
| Pretech       | EVE 1801 3G ES1049EG        | [3f2cdff8d4](https://linux-hardware.org/?probe=3f2cdff8d4) | Oct 05, 2022 |
| Toshiba       | Encore                      | [a11bf538ec](https://linux-hardware.org/?probe=a11bf538ec) | Oct 05, 2022 |
| ASUSTek       | N56VZ                       | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| HP            | EliteBook 8560p             | [4a9e29fab2](https://linux-hardware.org/?probe=4a9e29fab2) | Sep 18, 2022 |
| Lenovo        | Unknown                     | [64dc493d4d](https://linux-hardware.org/?probe=64dc493d4d) | Sep 17, 2022 |
| Lenovo        | Unknown                     | [581356206a](https://linux-hardware.org/?probe=581356206a) | Sep 17, 2022 |
| Dell          | Latitude 5420               | [511ef8a105](https://linux-hardware.org/?probe=511ef8a105) | Sep 08, 2022 |
| Dell          | Latitude 5420               | [48db2c3954](https://linux-hardware.org/?probe=48db2c3954) | Sep 08, 2022 |
| Toshiba       | Satellite P200              | [583489891f](https://linux-hardware.org/?probe=583489891f) | Sep 06, 2022 |
| HP            | Pavilion dv9700             | [9543920c45](https://linux-hardware.org/?probe=9543920c45) | Sep 04, 2022 |
| HP            | Pavilion dv9700             | [b6d4d6bca2](https://linux-hardware.org/?probe=b6d4d6bca2) | Sep 04, 2022 |
| Acer          | Swift SF314-41              | [1394aca8b2](https://linux-hardware.org/?probe=1394aca8b2) | Sep 03, 2022 |
| HP            | Pavilion Notebook           | [0e4eab04c0](https://linux-hardware.org/?probe=0e4eab04c0) | Aug 27, 2022 |
| HP            | Pavilion Notebook           | [65e832cb2f](https://linux-hardware.org/?probe=65e832cb2f) | Aug 27, 2022 |
| Dell          | Latitude 5290 2-in-1        | [bafc4d3392](https://linux-hardware.org/?probe=bafc4d3392) | Aug 20, 2022 |
| Dell          | Latitude E7240              | [1f20b0f54b](https://linux-hardware.org/?probe=1f20b0f54b) | Aug 08, 2022 |
| Acer          | Aspire A515-56G             | [3df2b6b19b](https://linux-hardware.org/?probe=3df2b6b19b) | Aug 05, 2022 |
| ASUSTek       | S551LB                      | [8660a06086](https://linux-hardware.org/?probe=8660a06086) | Jul 27, 2022 |
| Lenovo        | ThinkPad T580 20LAS27000    | [a78a8e806f](https://linux-hardware.org/?probe=a78a8e806f) | Jul 21, 2022 |
| Dell          | XPS 15 9500                 | [6886cd26f5](https://linux-hardware.org/?probe=6886cd26f5) | Jul 20, 2022 |
| HP            | 250 G8 Notebook PC          | [17cdd0291e](https://linux-hardware.org/?probe=17cdd0291e) | Jul 12, 2022 |
| Lenovo        | G50-30 80G0                 | [4de601fe45](https://linux-hardware.org/?probe=4de601fe45) | Jul 12, 2022 |
| ASUSTek       | X75A1                       | [4bd18943fb](https://linux-hardware.org/?probe=4bd18943fb) | Jul 09, 2022 |
| ASUSTek       | X75A1                       | [3da162d001](https://linux-hardware.org/?probe=3da162d001) | Jul 09, 2022 |
| Dell          | Inspiron 3537               | [36305f7936](https://linux-hardware.org/?probe=36305f7936) | Jul 09, 2022 |
| Lenovo        | ThinkPad T480s 20L8S2330... | [4718003bb5](https://linux-hardware.org/?probe=4718003bb5) | Jul 09, 2022 |
| Lenovo        | Z50-70 20354                | [6d9101e2d2](https://linux-hardware.org/?probe=6d9101e2d2) | Jul 08, 2022 |
| Dell          | XPS 15 9500                 | [36c7cff92d](https://linux-hardware.org/?probe=36c7cff92d) | Jul 07, 2022 |
| HP            | EliteBook 850 G8 Noteboo... | [445bedc2c9](https://linux-hardware.org/?probe=445bedc2c9) | Jul 06, 2022 |
| Dell          | Inspiron 3537               | [bfe2aed3aa](https://linux-hardware.org/?probe=bfe2aed3aa) | Jul 05, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20T80... | [4d4cd5bae0](https://linux-hardware.org/?probe=4d4cd5bae0) | Jul 05, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [82ca4386ae](https://linux-hardware.org/?probe=82ca4386ae) | Jun 30, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [42462e221b](https://linux-hardware.org/?probe=42462e221b) | Jun 29, 2022 |
| Chuwi         | GemiBook Pro                | [160062e69a](https://linux-hardware.org/?probe=160062e69a) | Jun 25, 2022 |
| Gigabyte      | G5 KC                       | [5ef620811f](https://linux-hardware.org/?probe=5ef620811f) | Jun 25, 2022 |
| Acer          | Aspire A315-23              | [45c9b081c5](https://linux-hardware.org/?probe=45c9b081c5) | Jun 24, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [96c4f21509](https://linux-hardware.org/?probe=96c4f21509) | Jun 21, 2022 |
| Acer          | Aspire E5-771G              | [dac3ae2eba](https://linux-hardware.org/?probe=dac3ae2eba) | Jun 21, 2022 |
| Chuwi         | GemiBook Pro                | [ba5ab976e2](https://linux-hardware.org/?probe=ba5ab976e2) | Jun 16, 2022 |
| Chuwi         | GemiBook Pro                | [d2b608c230](https://linux-hardware.org/?probe=d2b608c230) | Jun 16, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [1f92039342](https://linux-hardware.org/?probe=1f92039342) | Jun 02, 2022 |
| Dell          | Vostro 3500                 | [9dff398fa9](https://linux-hardware.org/?probe=9dff398fa9) | May 24, 2022 |
| Lenovo        | G40-30 80FY                 | [4280810a31](https://linux-hardware.org/?probe=4280810a31) | May 20, 2022 |
| eMachines     | E525                        | [2c397d4229](https://linux-hardware.org/?probe=2c397d4229) | May 19, 2022 |
| eMachines     | E525                        | [7a1e439150](https://linux-hardware.org/?probe=7a1e439150) | May 19, 2022 |
| HP            | ProBook 470 G1              | [cb4ef48c3d](https://linux-hardware.org/?probe=cb4ef48c3d) | May 10, 2022 |
| HP            | ProBook 470 G1              | [a20a5df1ad](https://linux-hardware.org/?probe=a20a5df1ad) | May 06, 2022 |
| Lenovo        | G50-30 80G0                 | [3d1c0ef2f0](https://linux-hardware.org/?probe=3d1c0ef2f0) | May 05, 2022 |
| HP            | Laptop 15-dw0xxx            | [8d561055ba](https://linux-hardware.org/?probe=8d561055ba) | May 04, 2022 |
| HP            | Pavilion 17                 | [3958b61eff](https://linux-hardware.org/?probe=3958b61eff) | May 02, 2022 |
| ASUSTek       | X540UA                      | [af0ed39935](https://linux-hardware.org/?probe=af0ed39935) | May 01, 2022 |
| Lenovo        | G50-30 80G0                 | [bc333fe437](https://linux-hardware.org/?probe=bc333fe437) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [67d1865b69](https://linux-hardware.org/?probe=67d1865b69) | Apr 30, 2022 |
| HP            | Pavilion Gaming Laptop 1... | [57a8a5bfcd](https://linux-hardware.org/?probe=57a8a5bfcd) | Apr 30, 2022 |
| HP            | Pavilion 17                 | [6de5e5677f](https://linux-hardware.org/?probe=6de5e5677f) | Apr 29, 2022 |
| Razer         | Blade                       | [c5ef4943c4](https://linux-hardware.org/?probe=c5ef4943c4) | Apr 27, 2022 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | [1a7a85a6ca](https://linux-hardware.org/?probe=1a7a85a6ca) | Apr 21, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [84978cfba3](https://linux-hardware.org/?probe=84978cfba3) | Apr 17, 2022 |
| Acer          | Swift SF114-32              | [e970f67c93](https://linux-hardware.org/?probe=e970f67c93) | Apr 13, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QC... | [bae30f6939](https://linux-hardware.org/?probe=bae30f6939) | Apr 11, 2022 |
| Dell          | OptiPlex 9020               | [6d0445b848](https://linux-hardware.org/?probe=6d0445b848) | Apr 09, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [d7d4ac2b9a](https://linux-hardware.org/?probe=d7d4ac2b9a) | Apr 04, 2022 |
| ASUSTek       | ZenBook UX434DA_UM433DA     | [f9ab989993](https://linux-hardware.org/?probe=f9ab989993) | Apr 02, 2022 |
| Acer          | Swift SF314-43              | [752a6415ff](https://linux-hardware.org/?probe=752a6415ff) | Apr 02, 2022 |
| ASUSTek       | X71Sr                       | [0e6ffbc190](https://linux-hardware.org/?probe=0e6ffbc190) | Apr 01, 2022 |
| eMachines     | E725 V1.03                  | [12ea923e2b](https://linux-hardware.org/?probe=12ea923e2b) | Mar 18, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [8a6bb86ea0](https://linux-hardware.org/?probe=8a6bb86ea0) | Mar 17, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [271852ad10](https://linux-hardware.org/?probe=271852ad10) | Mar 17, 2022 |
| Acer          | Swift SF314-43              | [6415b33b34](https://linux-hardware.org/?probe=6415b33b34) | Mar 17, 2022 |
| ASUSTek       | G75VX                       | [2b94fd73ea](https://linux-hardware.org/?probe=2b94fd73ea) | Mar 14, 2022 |
| Lenovo        | ThinkPad T410 2522DK2       | [9990e887c2](https://linux-hardware.org/?probe=9990e887c2) | Mar 13, 2022 |
| HP            | ProBook 4530s               | [061de41ec5](https://linux-hardware.org/?probe=061de41ec5) | Mar 13, 2022 |
| Toshiba       | Satellite C850-1GD          | [79b2741217](https://linux-hardware.org/?probe=79b2741217) | Mar 12, 2022 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | [6ba21bc191](https://linux-hardware.org/?probe=6ba21bc191) | Mar 05, 2022 |
| Apple         | MacBookAir7,2               | [34da56b567](https://linux-hardware.org/?probe=34da56b567) | Mar 01, 2022 |
| Acer          | Aspire A515-51G             | [28a9d8d6a4](https://linux-hardware.org/?probe=28a9d8d6a4) | Feb 25, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a93fdb0cc8](https://linux-hardware.org/?probe=a93fdb0cc8) | Feb 25, 2022 |
| Chuwi         | GemiBook Pro                | [37c0889ae6](https://linux-hardware.org/?probe=37c0889ae6) | Feb 25, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [57a0f33a96](https://linux-hardware.org/?probe=57a0f33a96) | Feb 23, 2022 |
| HP            | 2140                        | [ad18e8d0b3](https://linux-hardware.org/?probe=ad18e8d0b3) | Feb 22, 2022 |
| HP            | 2140                        | [e0757f087f](https://linux-hardware.org/?probe=e0757f087f) | Feb 22, 2022 |
| eMachines     | E725 V1.03                  | [0f12be73fa](https://linux-hardware.org/?probe=0f12be73fa) | Feb 21, 2022 |
| Apple         | MacBookAir5,2               | [dc8f1e8a38](https://linux-hardware.org/?probe=dc8f1e8a38) | Feb 20, 2022 |
| Acer          | Aspire E1-532G              | [2ec2b8bf53](https://linux-hardware.org/?probe=2ec2b8bf53) | Feb 20, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [7f55b1fa12](https://linux-hardware.org/?probe=7f55b1fa12) | Feb 17, 2022 |
| Dell          | XPS 13 9310                 | [64cfd66662](https://linux-hardware.org/?probe=64cfd66662) | Feb 11, 2022 |
| Acer          | Aspire 7739G                | [f8150dd53e](https://linux-hardware.org/?probe=f8150dd53e) | Feb 10, 2022 |
| Apple         | MacBookPro11,4              | [c843bc46b3](https://linux-hardware.org/?probe=c843bc46b3) | Feb 07, 2022 |
| HP            | ZBook 17 G2                 | [4210faf0d2](https://linux-hardware.org/?probe=4210faf0d2) | Jan 29, 2022 |
| Samsung       | 300E4A/300E5A/300E7A/343... | [5310be8910](https://linux-hardware.org/?probe=5310be8910) | Jan 23, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1400CEA... | [4c77e8f334](https://linux-hardware.org/?probe=4c77e8f334) | Jan 23, 2022 |
| Acer          | Aspire F5-573G              | [cb60b63849](https://linux-hardware.org/?probe=cb60b63849) | Jan 23, 2022 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | [4b3b067330](https://linux-hardware.org/?probe=4b3b067330) | Jan 21, 2022 |
| Lenovo        | ThinkBook 15p 20V3          | [45b3c5b85a](https://linux-hardware.org/?probe=45b3c5b85a) | Jan 16, 2022 |
| Acer          | Aspire A315-21              | [91548d30f5](https://linux-hardware.org/?probe=91548d30f5) | Jan 06, 2022 |
| HP            | EliteBook 2170p             | [4598e643d1](https://linux-hardware.org/?probe=4598e643d1) | Jan 05, 2022 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [0a37cdb124](https://linux-hardware.org/?probe=0a37cdb124) | Jan 02, 2022 |
| Lenovo        | B590 20208                  | [967a9b3a38](https://linux-hardware.org/?probe=967a9b3a38) | Dec 27, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [d9c0087822](https://linux-hardware.org/?probe=d9c0087822) | Dec 26, 2021 |
| Apple         | MacBookAir3,2               | [9f3a7c27d9](https://linux-hardware.org/?probe=9f3a7c27d9) | Dec 24, 2021 |
| Acer          | Aspire 5250                 | [b4a48e5350](https://linux-hardware.org/?probe=b4a48e5350) | Dec 15, 2021 |
| Dell          | XPS 13 9310                 | [86eb1ce765](https://linux-hardware.org/?probe=86eb1ce765) | Dec 15, 2021 |
| Acer          | Aspire A515-55              | [f258cd6bb3](https://linux-hardware.org/?probe=f258cd6bb3) | Dec 12, 2021 |
| Acer          | Aspire A314-22              | [655c34690e](https://linux-hardware.org/?probe=655c34690e) | Dec 12, 2021 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | [eb77365d4e](https://linux-hardware.org/?probe=eb77365d4e) | Dec 11, 2021 |
| Lenovo        | IdeaPad 510S-13IKB 80V0     | [fe88e1083a](https://linux-hardware.org/?probe=fe88e1083a) | Dec 11, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [dac924cd16](https://linux-hardware.org/?probe=dac924cd16) | Dec 04, 2021 |
| Acer          | Aspire E1-522               | [3111a073e8](https://linux-hardware.org/?probe=3111a073e8) | Dec 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [422733b9df](https://linux-hardware.org/?probe=422733b9df) | Dec 02, 2021 |
| Lenovo        | B50-70 20384                | [d75361564f](https://linux-hardware.org/?probe=d75361564f) | Dec 02, 2021 |
| Lenovo        | ThinkPad T450s 20BWS2US0... | [0e099c0bdd](https://linux-hardware.org/?probe=0e099c0bdd) | Dec 02, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [416712d76f](https://linux-hardware.org/?probe=416712d76f) | Nov 30, 2021 |
| Lenovo        | ThinkPad T440p 20AWS1HK0... | [c4e34dbb1c](https://linux-hardware.org/?probe=c4e34dbb1c) | Nov 30, 2021 |
| Dell          | XPS 13 9310                 | [ec7596ddfa](https://linux-hardware.org/?probe=ec7596ddfa) | Nov 26, 2021 |
| Acer          | Aspire 6930G                | [323825e995](https://linux-hardware.org/?probe=323825e995) | Nov 24, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [659ed4999d](https://linux-hardware.org/?probe=659ed4999d) | Nov 24, 2021 |
| Dell          | Vostro 3500                 | [b0b04002be](https://linux-hardware.org/?probe=b0b04002be) | Nov 24, 2021 |
| HP            | EliteBook 2530p             | [08f1548a45](https://linux-hardware.org/?probe=08f1548a45) | Nov 23, 2021 |
| Dell          | Vostro 5568                 | [515899572d](https://linux-hardware.org/?probe=515899572d) | Nov 22, 2021 |
| Dell          | Vostro 5568                 | [9ae3647f81](https://linux-hardware.org/?probe=9ae3647f81) | Nov 22, 2021 |
| Dell          | Inspiron 5570               | [bde1fd1da2](https://linux-hardware.org/?probe=bde1fd1da2) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [8a1a3f0661](https://linux-hardware.org/?probe=8a1a3f0661) | Nov 20, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [eace5e1302](https://linux-hardware.org/?probe=eace5e1302) | Nov 19, 2021 |
| Dell          | Inspiron 5570               | [9c7eba9b77](https://linux-hardware.org/?probe=9c7eba9b77) | Nov 19, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | [3a3f503917](https://linux-hardware.org/?probe=3a3f503917) | Nov 14, 2021 |
| HP            | Pavilion Laptop 14-bf1xx    | [93e710085b](https://linux-hardware.org/?probe=93e710085b) | Nov 12, 2021 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | [aa49529b6c](https://linux-hardware.org/?probe=aa49529b6c) | Nov 09, 2021 |
| Lenovo        | Legion 5 17ACH6 82K0        | [3af4c85553](https://linux-hardware.org/?probe=3af4c85553) | Nov 04, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | [df4871ce19](https://linux-hardware.org/?probe=df4871ce19) | Nov 04, 2021 |
| ASUSTek       | X751NV                      | [ecf08805fe](https://linux-hardware.org/?probe=ecf08805fe) | Nov 03, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [c7f7df5e24](https://linux-hardware.org/?probe=c7f7df5e24) | Nov 01, 2021 |
| Dell          | Inspiron N5110              | [532a1d3d01](https://linux-hardware.org/?probe=532a1d3d01) | Oct 29, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [2d80988ddc](https://linux-hardware.org/?probe=2d80988ddc) | Oct 22, 2021 |
| SHENZHEN X... | ST106                       | [afbb6f50c8](https://linux-hardware.org/?probe=afbb6f50c8) | Oct 11, 2021 |
| SHENZHEN X... | ST106                       | [5ca1710273](https://linux-hardware.org/?probe=5ca1710273) | Oct 11, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [e570cc15cd](https://linux-hardware.org/?probe=e570cc15cd) | Oct 06, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [d5199453f5](https://linux-hardware.org/?probe=d5199453f5) | Oct 04, 2021 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | [068d8ff3b0](https://linux-hardware.org/?probe=068d8ff3b0) | Oct 04, 2021 |
| Toshiba       | Satellite P200              | [df46118ac3](https://linux-hardware.org/?probe=df46118ac3) | Oct 02, 2021 |
| Acer          | Aspire A315-21              | [1b6bb85e6b](https://linux-hardware.org/?probe=1b6bb85e6b) | Sep 30, 2021 |
| Acer          | Aspire A315-21              | [aa5e0ddd18](https://linux-hardware.org/?probe=aa5e0ddd18) | Sep 30, 2021 |
| HP            | ProBook 4740s               | [77b2eed991](https://linux-hardware.org/?probe=77b2eed991) | Sep 22, 2021 |
| Acer          | Aspire 5250                 | [be1b633020](https://linux-hardware.org/?probe=be1b633020) | Sep 14, 2021 |
| HUAWEI        | WRTB-WXX9                   | [1570fd5033](https://linux-hardware.org/?probe=1570fd5033) | Sep 09, 2021 |
| HP            | Pavilion Gaming Laptop 1... | [104bd9a2a0](https://linux-hardware.org/?probe=104bd9a2a0) | Sep 09, 2021 |
| Lenovo        | ThinkPad E590 20NB006MSC    | [73c87242b9](https://linux-hardware.org/?probe=73c87242b9) | Sep 09, 2021 |
| HP            | OMEN by Laptop              | [aa6b5ca915](https://linux-hardware.org/?probe=aa6b5ca915) | Sep 08, 2021 |
| HP            | OMEN by Laptop              | [8b503ffd8a](https://linux-hardware.org/?probe=8b503ffd8a) | Sep 07, 2021 |
| Dell          | Latitude 5580               | [944d9e820d](https://linux-hardware.org/?probe=944d9e820d) | Sep 01, 2021 |
| Acer          | Aspire F5-571G              | [d3d0e83199](https://linux-hardware.org/?probe=d3d0e83199) | Aug 30, 2021 |
| Lenovo        | IdeaPad 110-17IKB 80VK      | [44e5a5c02e](https://linux-hardware.org/?probe=44e5a5c02e) | Aug 26, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [06981db89b](https://linux-hardware.org/?probe=06981db89b) | Aug 20, 2021 |
| Acer          | Aspire A315-34              | [a33d74d8e4](https://linux-hardware.org/?probe=a33d74d8e4) | Aug 19, 2021 |
| Acer          | Aspire A315-34              | [19982a455b](https://linux-hardware.org/?probe=19982a455b) | Aug 18, 2021 |
| Acer          | Aspire E5-575G              | [3c4fba3670](https://linux-hardware.org/?probe=3c4fba3670) | Aug 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [f9bd04ed57](https://linux-hardware.org/?probe=f9bd04ed57) | Aug 14, 2021 |
| HP            | 2000                        | [73e2b73533](https://linux-hardware.org/?probe=73e2b73533) | Aug 09, 2021 |
| HP            | EliteBook 850 G8 Noteboo... | [a319e4cbd9](https://linux-hardware.org/?probe=a319e4cbd9) | Aug 06, 2021 |
| Acer          | Nitro AN515-52              | [7d693f5628](https://linux-hardware.org/?probe=7d693f5628) | Aug 04, 2021 |
| Acer          | Nitro AN515-52              | [75944f340e](https://linux-hardware.org/?probe=75944f340e) | Aug 04, 2021 |
| Lenovo        | ThinkPad T430 2349AK2       | [c51aebd74f](https://linux-hardware.org/?probe=c51aebd74f) | Aug 04, 2021 |
| Dell          | Inspiron N5110              | [0283581712](https://linux-hardware.org/?probe=0283581712) | Jul 31, 2021 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [8297a49138](https://linux-hardware.org/?probe=8297a49138) | Jul 28, 2021 |
| Acer          | Aspire E5-774G              | [f60a7a3f63](https://linux-hardware.org/?probe=f60a7a3f63) | Jul 28, 2021 |
| HP            | Laptop 15s-eq2xxx           | [4759f3249f](https://linux-hardware.org/?probe=4759f3249f) | Jul 28, 2021 |
| Lenovo        | ThinkPad X260 20F5S0JF00    | [98cbf345d9](https://linux-hardware.org/?probe=98cbf345d9) | Jul 25, 2021 |
| HP            | 2000                        | [0187fe7c8a](https://linux-hardware.org/?probe=0187fe7c8a) | Jul 25, 2021 |
| ASUSTek       | X540SAA                     | [34bb1d000b](https://linux-hardware.org/?probe=34bb1d000b) | Jul 24, 2021 |
| Lenovo        | Z50-70 20354                | [66ea173cb5](https://linux-hardware.org/?probe=66ea173cb5) | Jul 21, 2021 |
| Acer          | Aspire 6930G                | [45694711ff](https://linux-hardware.org/?probe=45694711ff) | Jul 20, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [1cd948b8e0](https://linux-hardware.org/?probe=1cd948b8e0) | Jul 19, 2021 |
| Acer          | Aspire 6930G                | [0e4d09c44c](https://linux-hardware.org/?probe=0e4d09c44c) | Jul 15, 2021 |
| Acer          | Aspire E5-571G              | [6c3da4947f](https://linux-hardware.org/?probe=6c3da4947f) | Jul 02, 2021 |
| Acer          | Aspire E5-571G              | [5497b79433](https://linux-hardware.org/?probe=5497b79433) | Jul 02, 2021 |
| HP            | EliteBook 830 G5            | [e43bc569f4](https://linux-hardware.org/?probe=e43bc569f4) | Jul 01, 2021 |
| Acer          | Aspire A315-34              | [2e6400b3fb](https://linux-hardware.org/?probe=2e6400b3fb) | Jun 30, 2021 |
| System76      | Oryx Pro                    | [fd3cc0ad52](https://linux-hardware.org/?probe=fd3cc0ad52) | Jun 30, 2021 |
| HP            | EliteBook 850 G6            | [e38bee4588](https://linux-hardware.org/?probe=e38bee4588) | Jun 24, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [b6ea706618](https://linux-hardware.org/?probe=b6ea706618) | Jun 22, 2021 |
| ASUSTek       | ROG Strix G513IH_G513IH     | [0c5f910d8b](https://linux-hardware.org/?probe=0c5f910d8b) | Jun 21, 2021 |
| HP            | 255 G7 Notebook PC          | [79627ead32](https://linux-hardware.org/?probe=79627ead32) | Jun 14, 2021 |
| Lenovo        | ThinkPad E580 20KS005ASC    | [5b707f47c0](https://linux-hardware.org/?probe=5b707f47c0) | Jun 11, 2021 |
| Lenovo        | G40-30 80FY                 | [b2fe748178](https://linux-hardware.org/?probe=b2fe748178) | Jun 08, 2021 |
| Toshiba       | Satellite L750              | [e0c6618369](https://linux-hardware.org/?probe=e0c6618369) | Jun 07, 2021 |
| Lenovo        | ThinkPad P53 20QNZ4RBUS     | [3f5925d0f5](https://linux-hardware.org/?probe=3f5925d0f5) | Jun 07, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [7d816dafe7](https://linux-hardware.org/?probe=7d816dafe7) | Jun 01, 2021 |
| Lenovo        | ThinkPad P1 20MES1T700      | [be5bc5605b](https://linux-hardware.org/?probe=be5bc5605b) | Jun 01, 2021 |
| Lenovo        | G40-30 80FY                 | [eb9aaa55ea](https://linux-hardware.org/?probe=eb9aaa55ea) | May 30, 2021 |
| Lenovo        | V340-17IWL 81RG             | [2ec41d1cf8](https://linux-hardware.org/?probe=2ec41d1cf8) | May 26, 2021 |
| Lenovo        | G40-30 80FY                 | [0c3e0e8293](https://linux-hardware.org/?probe=0c3e0e8293) | May 26, 2021 |
| HP            | 255 G7 Notebook PC          | [bfb71f53ec](https://linux-hardware.org/?probe=bfb71f53ec) | May 03, 2021 |
| Acer          | Aspire F5-571G              | [5bb52c52af](https://linux-hardware.org/?probe=5bb52c52af) | Apr 30, 2021 |
| Acer          | Aspire A315-34              | [6ab7b315e3](https://linux-hardware.org/?probe=6ab7b315e3) | Apr 24, 2021 |
| Acer          | Aspire A315-34              | [7e0d6ec835](https://linux-hardware.org/?probe=7e0d6ec835) | Apr 24, 2021 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [470c00d1c5](https://linux-hardware.org/?probe=470c00d1c5) | Apr 23, 2021 |
| Lenovo        | Z50-70 20354                | [fbc2a66e2b](https://linux-hardware.org/?probe=fbc2a66e2b) | Apr 22, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [eabbb41fea](https://linux-hardware.org/?probe=eabbb41fea) | Apr 20, 2021 |
| Lenovo        | ThinkBook 15-IIL 20SM       | [86927ce44d](https://linux-hardware.org/?probe=86927ce44d) | Apr 20, 2021 |
| Lenovo        | ThinkPad T490s 20NXCTO1W... | [92fe8bf812](https://linux-hardware.org/?probe=92fe8bf812) | Apr 20, 2021 |
| HP            | Compaq 6710b (KL509AV)      | [735870e390](https://linux-hardware.org/?probe=735870e390) | Apr 16, 2021 |
| HP            | EliteBook 850 G6            | [7dbeb6844a](https://linux-hardware.org/?probe=7dbeb6844a) | Apr 16, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [24cd2670f3](https://linux-hardware.org/?probe=24cd2670f3) | Apr 15, 2021 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [60ef5cf4f2](https://linux-hardware.org/?probe=60ef5cf4f2) | Apr 15, 2021 |
| HP            | Compaq 6710b (KL509AV)      | [565cd80547](https://linux-hardware.org/?probe=565cd80547) | Apr 15, 2021 |
| Acer          | Aspire A315-21              | [78550034b4](https://linux-hardware.org/?probe=78550034b4) | Apr 14, 2021 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [43b989fae1](https://linux-hardware.org/?probe=43b989fae1) | Apr 06, 2021 |
| Lenovo        | ThinkPad T460 20FMS0X022    | [02ce254082](https://linux-hardware.org/?probe=02ce254082) | Apr 06, 2021 |
| Lenovo        | Legion Y530-15ICH 81FV      | [2d68f9ad7f](https://linux-hardware.org/?probe=2d68f9ad7f) | Mar 31, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [be7b667e75](https://linux-hardware.org/?probe=be7b667e75) | Mar 27, 2021 |
| HP            | ZBook 17 G2                 | [45e4f9d242](https://linux-hardware.org/?probe=45e4f9d242) | Mar 24, 2021 |
| HP            | 250 G7 Notebook PC          | [ba238dbe29](https://linux-hardware.org/?probe=ba238dbe29) | Mar 21, 2021 |
| Dell          | Inspiron 5551               | [3b91b6e49f](https://linux-hardware.org/?probe=3b91b6e49f) | Mar 20, 2021 |
| Acer          | Aspire F5-573G              | [8f0d10afce](https://linux-hardware.org/?probe=8f0d10afce) | Feb 24, 2021 |
| HP            | ProBook 455 G7              | [ffdabc425b](https://linux-hardware.org/?probe=ffdabc425b) | Feb 16, 2021 |
| Dell          | XPS 13 9380                 | [69f9ebe58b](https://linux-hardware.org/?probe=69f9ebe58b) | Feb 11, 2021 |
| Acer          | Aspire ES1-532G             | [f01b666f99](https://linux-hardware.org/?probe=f01b666f99) | Feb 09, 2021 |
| Acer          | Aspire A315-41              | [d0648fe1f7](https://linux-hardware.org/?probe=d0648fe1f7) | Feb 07, 2021 |
| HP            | 250 G5 Notebook PC          | [a541bcd390](https://linux-hardware.org/?probe=a541bcd390) | Feb 02, 2021 |
| ASUSTek       | F5N                         | [5a1b1f9f7a](https://linux-hardware.org/?probe=5a1b1f9f7a) | Jan 26, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [17f2fe84cb](https://linux-hardware.org/?probe=17f2fe84cb) | Jan 14, 2021 |
| Dell          | Latitude E6430              | [939c4dbad4](https://linux-hardware.org/?probe=939c4dbad4) | Jan 10, 2021 |
| ASUSTek       | TUF Gaming FX505DY_FX505... | [1f95699c20](https://linux-hardware.org/?probe=1f95699c20) | Jan 09, 2021 |
| Lenovo        | ThinkPad T61 6458AU9        | [5350b0523f](https://linux-hardware.org/?probe=5350b0523f) | Jan 08, 2021 |
| Lenovo        | G710 20252                  | [9b176fb8e5](https://linux-hardware.org/?probe=9b176fb8e5) | Jan 04, 2021 |
| Lenovo        | G710 20252                  | [db68ccb5de](https://linux-hardware.org/?probe=db68ccb5de) | Jan 04, 2021 |
| Dell          | Vostro 3578                 | [a2e6574ba4](https://linux-hardware.org/?probe=a2e6574ba4) | Dec 30, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [bb46f7172f](https://linux-hardware.org/?probe=bb46f7172f) | Dec 27, 2020 |
| TUXEDO        | Pulse 15 Gen1               | [f6ef9c50ed](https://linux-hardware.org/?probe=f6ef9c50ed) | Dec 23, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [d886327463](https://linux-hardware.org/?probe=d886327463) | Dec 22, 2020 |
| Acer          | Aspire A315-21              | [4c807db430](https://linux-hardware.org/?probe=4c807db430) | Dec 19, 2020 |
| Dell          | Inspiron N5110              | [fb469bd0dc](https://linux-hardware.org/?probe=fb469bd0dc) | Dec 17, 2020 |
| Acer          | Aspire 7739G                | [9d81c58373](https://linux-hardware.org/?probe=9d81c58373) | Dec 12, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [9b07c5b4a5](https://linux-hardware.org/?probe=9b07c5b4a5) | Dec 06, 2020 |
| HP            | EliteBook 8560p             | [3cc104d803](https://linux-hardware.org/?probe=3cc104d803) | Dec 05, 2020 |
| Lenovo        | ThinkPad W540 20BHS04K00    | [c429b95a44](https://linux-hardware.org/?probe=c429b95a44) | Dec 03, 2020 |
| HP            | 2000                        | [27fed77b24](https://linux-hardware.org/?probe=27fed77b24) | Dec 02, 2020 |
| HP            | 255 G7 Notebook PC          | [82adf2d707](https://linux-hardware.org/?probe=82adf2d707) | Dec 01, 2020 |
| Acer          | Aspire ES1-732              | [243f8b5015](https://linux-hardware.org/?probe=243f8b5015) | Nov 29, 2020 |
| Lenovo        | ThinkPad E14 Gen 2 20T60... | [24fe3f5f2f](https://linux-hardware.org/?probe=24fe3f5f2f) | Nov 25, 2020 |
| HP            | ProBook 450 G7              | [49c3ecb298](https://linux-hardware.org/?probe=49c3ecb298) | Nov 24, 2020 |
| Acer          | Aspire ES1-732              | [9a62fb8fe7](https://linux-hardware.org/?probe=9a62fb8fe7) | Nov 21, 2020 |
| HP            | ProBook 640 G1              | [eed4ff0229](https://linux-hardware.org/?probe=eed4ff0229) | Nov 19, 2020 |
| Lenovo        | IdeaPad 520-15IKB 81BF      | [9c165b5f59](https://linux-hardware.org/?probe=9c165b5f59) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | [50ddfd361b](https://linux-hardware.org/?probe=50ddfd361b) | Nov 11, 2020 |
| HUAWEI        | KLVL-WXX9                   | [7e3892e9b1](https://linux-hardware.org/?probe=7e3892e9b1) | Nov 09, 2020 |
| Acer          | Aspire E5-771G              | [9d967e969d](https://linux-hardware.org/?probe=9d967e969d) | Nov 01, 2020 |
| Acer          | Aspire V5-531               | [8eb2cc2336](https://linux-hardware.org/?probe=8eb2cc2336) | Nov 01, 2020 |
| Lenovo        | Legion Y530-15ICH 81FV      | [e6cd5153b1](https://linux-hardware.org/?probe=e6cd5153b1) | Oct 31, 2020 |
| HP            | ProBook 450 G7              | [c3c04c52ab](https://linux-hardware.org/?probe=c3c04c52ab) | Oct 26, 2020 |
| HP            | Laptop 15-bs0xx             | [57db732909](https://linux-hardware.org/?probe=57db732909) | Oct 25, 2020 |
| Lenovo        | ThinkPad L15 Gen 1 20U70... | [8d0c1b4422](https://linux-hardware.org/?probe=8d0c1b4422) | Oct 22, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [38c87efbca](https://linux-hardware.org/?probe=38c87efbca) | Oct 16, 2020 |
| Dell          | XPS 15 7590                 | [65c065a968](https://linux-hardware.org/?probe=65c065a968) | Oct 09, 2020 |
| HP            | EliteBook 850 G5            | [0d11552658](https://linux-hardware.org/?probe=0d11552658) | Oct 07, 2020 |
| Toshiba       | Satellite C55-A-1M7         | [174d6c4c6d](https://linux-hardware.org/?probe=174d6c4c6d) | Oct 06, 2020 |
| Dell          | Vostro 3578                 | [7904981ea3](https://linux-hardware.org/?probe=7904981ea3) | Oct 05, 2020 |
| Dell          | XPS 15 9570                 | [dacb39a2ba](https://linux-hardware.org/?probe=dacb39a2ba) | Sep 30, 2020 |
| HP            | ProBook 450 G7              | [b4807eff1e](https://linux-hardware.org/?probe=b4807eff1e) | Sep 28, 2020 |
| HP            | ProBook 450 G7              | [9cc971b2e7](https://linux-hardware.org/?probe=9cc971b2e7) | Sep 28, 2020 |
| HP            | 255 G7 Notebook PC          | [062f436dfa](https://linux-hardware.org/?probe=062f436dfa) | Sep 27, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [181e06ec2e](https://linux-hardware.org/?probe=181e06ec2e) | Sep 26, 2020 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [d7391de736](https://linux-hardware.org/?probe=d7391de736) | Sep 21, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [ea8e216968](https://linux-hardware.org/?probe=ea8e216968) | Sep 20, 2020 |
| Fujitsu Si... | ESPRIMO Mobile V5535        | [d93882e0b2](https://linux-hardware.org/?probe=d93882e0b2) | Sep 20, 2020 |
| HP            | EliteBook 850 G6            | [fa0ec4aeae](https://linux-hardware.org/?probe=fa0ec4aeae) | Sep 17, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | [eeb54854f8](https://linux-hardware.org/?probe=eeb54854f8) | Sep 12, 2020 |
| HP            | Compaq nc6220 (PY732ES#A... | [a8d6bb1865](https://linux-hardware.org/?probe=a8d6bb1865) | Sep 12, 2020 |
| Dell          | Latitude 7390               | [b8019896d0](https://linux-hardware.org/?probe=b8019896d0) | Sep 10, 2020 |
| HP            | ProBook 430 G3              | [b80f12df10](https://linux-hardware.org/?probe=b80f12df10) | Sep 07, 2020 |
| HP            | EliteBook 850 G6            | [4458c2267f](https://linux-hardware.org/?probe=4458c2267f) | Aug 17, 2020 |
| HP            | ProBook 430 G3              | [e28ccfa01e](https://linux-hardware.org/?probe=e28ccfa01e) | Aug 11, 2020 |
| HP            | 255 G7 Notebook PC          | [9bf9387073](https://linux-hardware.org/?probe=9bf9387073) | Aug 05, 2020 |
| ASUSTek       | GL752VW                     | [26fc584896](https://linux-hardware.org/?probe=26fc584896) | Aug 02, 2020 |
| Samsung       | 300E4C/300E5C/300E7C        | [c670b35249](https://linux-hardware.org/?probe=c670b35249) | Jul 29, 2020 |
| Lenovo        | Y50-70 20378                | [842efe3170](https://linux-hardware.org/?probe=842efe3170) | Jul 28, 2020 |
| Dell          | XPS 13 9360                 | [743f8b4f98](https://linux-hardware.org/?probe=743f8b4f98) | Jul 25, 2020 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [34213d655c](https://linux-hardware.org/?probe=34213d655c) | Jul 24, 2020 |
| Dell          | Precision 5530              | [30c2f2561e](https://linux-hardware.org/?probe=30c2f2561e) | Jul 20, 2020 |
| ASUSTek       | X751NV                      | [f94768a5e6](https://linux-hardware.org/?probe=f94768a5e6) | Jul 15, 2020 |
| HP            | Compaq 6820s                | [f5b6aa7190](https://linux-hardware.org/?probe=f5b6aa7190) | Jul 15, 2020 |
| HP            | EliteBook 8470p             | [ce78055795](https://linux-hardware.org/?probe=ce78055795) | Jul 14, 2020 |
| Notebook      | MAM2080                     | [7464ed3c9d](https://linux-hardware.org/?probe=7464ed3c9d) | Jun 23, 2020 |
| ASUSTek       | X751NV                      | [08c5775f88](https://linux-hardware.org/?probe=08c5775f88) | Jun 22, 2020 |
| Notebook      | MAM2080                     | [7321ecab2d](https://linux-hardware.org/?probe=7321ecab2d) | Jun 21, 2020 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | [c0c727bcb0](https://linux-hardware.org/?probe=c0c727bcb0) | Jun 18, 2020 |
| ASUSTek       | X540UA                      | [7f0afeb60e](https://linux-hardware.org/?probe=7f0afeb60e) | Jun 16, 2020 |
| HP            | 255 G7 Notebook PC          | [639b8bd2bc](https://linux-hardware.org/?probe=639b8bd2bc) | Jun 14, 2020 |
| Acer          | Aspire 7720                 | [77e3ae41d8](https://linux-hardware.org/?probe=77e3ae41d8) | Jun 10, 2020 |
| Acer          | Swift SF314-52              | [fa00080df2](https://linux-hardware.org/?probe=fa00080df2) | Jun 06, 2020 |
| Lenovo        | G710 20252                  | [eff12f397f](https://linux-hardware.org/?probe=eff12f397f) | Jun 06, 2020 |
| Lenovo        | G500 20236                  | [689825038f](https://linux-hardware.org/?probe=689825038f) | May 25, 2020 |
| Toshiba       | Satellite L50-B             | [3ae92d178c](https://linux-hardware.org/?probe=3ae92d178c) | May 21, 2020 |
| HP            | Pavilion Gaming Laptop 1... | [9e3950795e](https://linux-hardware.org/?probe=9e3950795e) | May 17, 2020 |
| Toshiba       | Satellite L50-B             | [0a7ccd88d0](https://linux-hardware.org/?probe=0a7ccd88d0) | May 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | [951378d6d8](https://linux-hardware.org/?probe=951378d6d8) | May 15, 2020 |
| ASUSTek       | N56VZ                       | [69ee412460](https://linux-hardware.org/?probe=69ee412460) | May 14, 2020 |
| Acer          | Aspire ES1-571              | [77ee42e92e](https://linux-hardware.org/?probe=77ee42e92e) | May 12, 2020 |
| eMachines     | G725                        | [7edfa3ee85](https://linux-hardware.org/?probe=7edfa3ee85) | May 04, 2020 |
| Acer          | Aspire A315-51              | [c5c02e1984](https://linux-hardware.org/?probe=c5c02e1984) | May 03, 2020 |
| Acer          | Aspire A315-51              | [5f8f6e1f17](https://linux-hardware.org/?probe=5f8f6e1f17) | May 02, 2020 |
| Acer          | Swift SF314-52              | [72ece5cb6b](https://linux-hardware.org/?probe=72ece5cb6b) | Apr 23, 2020 |
| Lenovo        | B590 627439G                | [59e71f4410](https://linux-hardware.org/?probe=59e71f4410) | Apr 16, 2020 |
| Dell          | Vostro 3584                 | [37bd21052a](https://linux-hardware.org/?probe=37bd21052a) | Apr 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [ca750eb568](https://linux-hardware.org/?probe=ca750eb568) | Apr 14, 2020 |
| ASUSTek       | N56VZ                       | [249176d47f](https://linux-hardware.org/?probe=249176d47f) | Apr 01, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X705... | [72c0b81b89](https://linux-hardware.org/?probe=72c0b81b89) | Mar 27, 2020 |
| Lenovo        | G710 20252                  | [1a2c3269a9](https://linux-hardware.org/?probe=1a2c3269a9) | Mar 25, 2020 |
| Medion        | P6618                       | [cd6a2e684b](https://linux-hardware.org/?probe=cd6a2e684b) | Mar 20, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [958514b01d](https://linux-hardware.org/?probe=958514b01d) | Mar 06, 2020 |
| HP            | Presario CQ57               | [09b5945399](https://linux-hardware.org/?probe=09b5945399) | Mar 02, 2020 |
| HP            | Pavilion g6                 | [5965dbf803](https://linux-hardware.org/?probe=5965dbf803) | Feb 08, 2020 |
| HP            | EliteBook 850 G6            | [ed2e18e22a](https://linux-hardware.org/?probe=ed2e18e22a) | Jan 31, 2020 |
| Acer          | Aspire A315-21              | [fc460d19de](https://linux-hardware.org/?probe=fc460d19de) | Jan 29, 2020 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | [ad283e347b](https://linux-hardware.org/?probe=ad283e347b) | Jan 28, 2020 |
| Acer          | Aspire A315-21              | [fe5311a7e7](https://linux-hardware.org/?probe=fe5311a7e7) | Jan 28, 2020 |
| HP            | Laptop 17-ca0xxx            | [0af8fff870](https://linux-hardware.org/?probe=0af8fff870) | Jan 06, 2020 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | [cd7fe65e36](https://linux-hardware.org/?probe=cd7fe65e36) | Jan 02, 2020 |
| Acer          | Aspire A715-72G             | [d8301b28b6](https://linux-hardware.org/?probe=d8301b28b6) | Dec 31, 2019 |
| HP            | ProBook 4730s               | [a56d8d1c28](https://linux-hardware.org/?probe=a56d8d1c28) | Dec 26, 2019 |
| HP            | ProBook 4730s               | [fc266328ed](https://linux-hardware.org/?probe=fc266328ed) | Dec 26, 2019 |
| HP            | ProBook 4730s               | [581fd252a9](https://linux-hardware.org/?probe=581fd252a9) | Dec 26, 2019 |
| Lenovo        | ThinkPad T440 20B7S14N0U    | [059788b6b9](https://linux-hardware.org/?probe=059788b6b9) | Dec 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [1bb0047e0e](https://linux-hardware.org/?probe=1bb0047e0e) | Dec 03, 2019 |
| HP            | OMEN by Laptop 17-cb0xxx    | [c3973966c4](https://linux-hardware.org/?probe=c3973966c4) | Nov 21, 2019 |
| Lenovo        | Y520-15IKBN 80WK            | [518b6e5e9c](https://linux-hardware.org/?probe=518b6e5e9c) | Nov 21, 2019 |
| HP            | Laptop 17-ca0xxx            | [dfc4334b0c](https://linux-hardware.org/?probe=dfc4334b0c) | Nov 15, 2019 |
| HP            | Laptop 17-ca0xxx            | [6334709a9e](https://linux-hardware.org/?probe=6334709a9e) | Nov 15, 2019 |
| HP            | EliteBook 850 G6            | [d1a89b5c7b](https://linux-hardware.org/?probe=d1a89b5c7b) | Nov 13, 2019 |
| Toshiba       | Satellite A300              | [9bd874bab4](https://linux-hardware.org/?probe=9bd874bab4) | Nov 05, 2019 |
| Acer          | Aspire A715-72G             | [ae95cd5f3d](https://linux-hardware.org/?probe=ae95cd5f3d) | Oct 12, 2019 |
| Acer          | Aspire A715-72G             | [38c98d0bfa](https://linux-hardware.org/?probe=38c98d0bfa) | Oct 12, 2019 |
| ASUSTek       | G750JZ                      | [f6f8595b70](https://linux-hardware.org/?probe=f6f8595b70) | Sep 14, 2019 |
| Acer          | Aspire A315-21              | [b29e405bdc](https://linux-hardware.org/?probe=b29e405bdc) | Sep 13, 2019 |
| Acer          | Aspire A515-51G             | [458c9ffc20](https://linux-hardware.org/?probe=458c9ffc20) | Sep 02, 2019 |
| Dell          | G3 3779                     | [46c53c54c1](https://linux-hardware.org/?probe=46c53c54c1) | Aug 28, 2019 |
| Lenovo        | ThinkPad X240 20AMS30A01    | [a808bddfca](https://linux-hardware.org/?probe=a808bddfca) | Aug 22, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [57c89febd9](https://linux-hardware.org/?probe=57c89febd9) | Jul 22, 2019 |
| Dell          | Vostro 3480                 | [142a1d632e](https://linux-hardware.org/?probe=142a1d632e) | Jul 12, 2019 |
| Dell          | Vostro 3480                 | [5c7cd324e3](https://linux-hardware.org/?probe=5c7cd324e3) | Jul 12, 2019 |
| HP            | Laptop 17-ca0xxx            | [542c9cbc52](https://linux-hardware.org/?probe=542c9cbc52) | Jun 23, 2019 |
| Acer          | Aspire A515-51G             | [43a15b2717](https://linux-hardware.org/?probe=43a15b2717) | Jun 22, 2019 |
| Acer          | Extensa 5630                | [ac0c824624](https://linux-hardware.org/?probe=ac0c824624) | Jun 16, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [edcc2f0a4e](https://linux-hardware.org/?probe=edcc2f0a4e) | Jun 06, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8195d1d516](https://linux-hardware.org/?probe=8195d1d516) | Jun 06, 2019 |
| Dell          | Latitude E6440              | [6c61ba4580](https://linux-hardware.org/?probe=6c61ba4580) | Jun 04, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [6ce5e7dbb1](https://linux-hardware.org/?probe=6ce5e7dbb1) | May 24, 2019 |
| HP            | 250 G6 Notebook PC          | [da7e75ebe8](https://linux-hardware.org/?probe=da7e75ebe8) | May 19, 2019 |
| Lenovo        | G50-45 80E3                 | [d78a5346f7](https://linux-hardware.org/?probe=d78a5346f7) | May 13, 2019 |
| HP            | Laptop 17-ca0xxx            | [6465c1b176](https://linux-hardware.org/?probe=6465c1b176) | May 11, 2019 |
| HP            | Laptop 17-ca0xxx            | [93859ddac7](https://linux-hardware.org/?probe=93859ddac7) | May 05, 2019 |
| HP            | Notebook                    | [75f8121579](https://linux-hardware.org/?probe=75f8121579) | May 03, 2019 |
| HP            | Notebook                    | [55d7e86f13](https://linux-hardware.org/?probe=55d7e86f13) | May 03, 2019 |
| HP            | Notebook                    | [17fa8aef52](https://linux-hardware.org/?probe=17fa8aef52) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | [09c192ce30](https://linux-hardware.org/?probe=09c192ce30) | May 03, 2019 |
| HP            | Laptop 17-ca0xxx            | [f4deeacc7c](https://linux-hardware.org/?probe=f4deeacc7c) | May 03, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [5d410980c0](https://linux-hardware.org/?probe=5d410980c0) | May 01, 2019 |
| Toshiba       | Satellite A300              | [89f0da0254](https://linux-hardware.org/?probe=89f0da0254) | Apr 30, 2019 |
| ASUSTek       | X550JX                      | [341ce6f2fb](https://linux-hardware.org/?probe=341ce6f2fb) | Apr 14, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [3b3d563f34](https://linux-hardware.org/?probe=3b3d563f34) | Apr 12, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | [8046c09d71](https://linux-hardware.org/?probe=8046c09d71) | Apr 03, 2019 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | [54f04aad99](https://linux-hardware.org/?probe=54f04aad99) | Mar 22, 2019 |
| HP            | Unknown                     | [37702d4223](https://linux-hardware.org/?probe=37702d4223) | Feb 22, 2019 |
| ASUSTek       | VivoBook_ASUSLaptop X570... | [01e34dc2d8](https://linux-hardware.org/?probe=01e34dc2d8) | Feb 19, 2019 |
| ASUSTek       | X540UA                      | [42572b9771](https://linux-hardware.org/?probe=42572b9771) | Jan 05, 2019 |
| ASUSTek       | X540UA                      | [867a1fdda8](https://linux-hardware.org/?probe=867a1fdda8) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | [ae2b9d2b8f](https://linux-hardware.org/?probe=ae2b9d2b8f) | Dec 14, 2018 |
| ASUSTek       | X540UA                      | [567e365e34](https://linux-hardware.org/?probe=567e365e34) | Dec 14, 2018 |
| Acer          | Aspire 5715Z                | [abecd9bff0](https://linux-hardware.org/?probe=abecd9bff0) | Nov 30, 2018 |
| Acer          | Aspire 5715Z                | [fd1d18122b](https://linux-hardware.org/?probe=fd1d18122b) | Nov 30, 2018 |
| HP            | 2000                        | [b24b2b9082](https://linux-hardware.org/?probe=b24b2b9082) | Nov 26, 2018 |
| HP            | ProBook 450 G4              | [415307639f](https://linux-hardware.org/?probe=415307639f) | Nov 21, 2018 |
| HP            | EliteBook 2540p             | [88e983ac45](https://linux-hardware.org/?probe=88e983ac45) | Oct 28, 2018 |
| ASUSTek       | X705UDR                     | [0a1cf851c7](https://linux-hardware.org/?probe=0a1cf851c7) | Jun 20, 2018 |
| Samsung       | N150/N210/N220              | [bab6da27ab](https://linux-hardware.org/?probe=bab6da27ab) | Apr 30, 2017 |
| Dell          | Vostro 1700                 | [6167c4bd5d](https://linux-hardware.org/?probe=6167c4bd5d) | Mar 17, 2017 |
| Dell          | Inspiron 3737               | [fba4632269](https://linux-hardware.org/?probe=fba4632269) | Dec 22, 2016 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Croatia/Notebook/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Notebooks | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 49        | 8.93%   |
| Ubuntu 22.04                 | 36        | 6.56%   |
| Ubuntu 18.04                 | 18        | 3.28%   |
| Ubuntu 24.04                 | 15        | 2.73%   |
| Arch Rolling                 | 15        | 2.73%   |
| Debian 11                    | 12        | 2.19%   |
| Pop!_OS 22.04                | 11        | 2%      |
| Fedora 41                    | 10        | 1.82%   |
| Debian 12                    | 10        | 1.82%   |
| Zorin 16                     | 8         | 1.46%   |
| OpenMandriva 25.90           | 8         | 1.46%   |
| Fedora 40                    | 8         | 1.46%   |
| Fedora 39                    | 8         | 1.46%   |
| Zorin 17                     | 7         | 1.28%   |
| Pop!_OS 21.04                | 7         | 1.28%   |
| OpenMandriva 4.3             | 7         | 1.28%   |
| OpenMandriva 25.06           | 7         | 1.28%   |
| OpenMandriva 24.12           | 7         | 1.28%   |
| Fedora 36                    | 7         | 1.28%   |
| Pop!_OS 20.04                | 6         | 1.09%   |
| Fedora 38                    | 6         | 1.09%   |
| Ubuntu 19.04                 | 5         | 0.91%   |
| OpenMandriva 25.01           | 5         | 0.91%   |
| Linux Mint 21.1              | 5         | 0.91%   |
| Linux Mint 20.3              | 5         | 0.91%   |
| KDE neon 22.04               | 5         | 0.91%   |
| Fedora 35                    | 5         | 0.91%   |
| Ubuntu 21.04                 | 4         | 0.73%   |
| Pop!_OS 20.10                | 4         | 0.73%   |
| openSUSE Tumbleweed-XXXXXXXX | 4         | 0.73%   |
| OpenMandriva 4.2             | 4         | 0.73%   |
| Manjaro                      | 4         | 0.73%   |
| Linux Mint 20.2              | 4         | 0.73%   |
| KDE neon 20.04               | 4         | 0.73%   |
| Endless 3.7.8                | 4         | 0.73%   |
| ArcoLinux Rolling            | 4         | 0.73%   |
| Arch                         | 4         | 0.73%   |
| Zorin 18                     | 3         | 0.55%   |
| Zorin 15                     | 3         | 0.55%   |
| Ubuntu 25.10                 | 3         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| Ubuntu             | 135       | 27.05%  |
| OpenMandriva       | 54        | 10.82%  |
| Fedora             | 46        | 9.22%   |
| Pop!_OS            | 30        | 6.01%   |
| Linux Mint         | 29        | 5.81%   |
| Debian             | 26        | 5.21%   |
| Endless            | 22        | 4.41%   |
| Zorin              | 21        | 4.21%   |
| Manjaro            | 19        | 3.81%   |
| Arch               | 18        | 3.61%   |
| Kubuntu            | 17        | 3.41%   |
| ROSA               | 9         | 1.8%    |
| KDE neon           | 9         | 1.8%    |
| openSUSE           | 6         | 1.2%    |
| Kali               | 5         | 1%      |
| Bazzite            | 5         | 1%      |
| ArcoLinux          | 5         | 1%      |
| Elementary         | 4         | 0.8%    |
| Xubuntu            | 3         | 0.6%    |
| MX                 | 3         | 0.6%    |
| EndeavourOS        | 3         | 0.6%    |
| CentOS             | 3         | 0.6%    |
| Ubuntu MATE        | 2         | 0.4%    |
| Q4OS               | 2         | 0.4%    |
| Nobara             | 2         | 0.4%    |
| LMDE               | 2         | 0.4%    |
| Gentoo             | 2         | 0.4%    |
| Garuda Linux       | 2         | 0.4%    |
| CachyOS            | 2         | 0.4%    |
| Xero               | 1         | 0.2%    |
| Ubuntu Unity       | 1         | 0.2%    |
| Ubuntu Budgie      | 1         | 0.2%    |
| SteamOS            | 1         | 0.2%    |
| Rocky Linux        | 1         | 0.2%    |
| Parrot             | 1         | 0.2%    |
| NixOS              | 1         | 0.2%    |
| Lubuntu            | 1         | 0.2%    |
| LinuxFX            | 1         | 0.2%    |
| Fedora-asahi-remix | 1         | 0.2%    |
| BlackPanther       | 1         | 0.2%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Notebooks | Percent |
|--------------------------|-----------|---------|
| 6.14.2-desktop-3omv2590  | 16        | 2.7%    |
| 5.16.7-desktop-1omv4003  | 7         | 1.18%   |
| 6.8.0-51-generic         | 6         | 1.01%   |
| 5.8.0-14-generic         | 6         | 1.01%   |
| 5.11.0-38-generic        | 6         | 1.01%   |
| 6.8.0-47-generic         | 5         | 0.84%   |
| 6.8.0-41-generic         | 5         | 0.84%   |
| 6.12.9-desktop-1omv2490  | 5         | 0.84%   |
| 6.12.1-desktop-1omv2490  | 5         | 0.84%   |
| 5.4.0-42-generic         | 5         | 0.84%   |
| 5.11.0-7620-generic      | 5         | 0.84%   |
| 6.5.0-28-generic         | 4         | 0.68%   |
| 6.5.0-26-generic         | 4         | 0.68%   |
| 5.3.0-28-generic         | 4         | 0.68%   |
| 5.13.0-30-generic        | 4         | 0.68%   |
| 5.10.14-desktop-1omv4002 | 4         | 0.68%   |
| 6.4.11-desktop-1omv2390  | 3         | 0.51%   |
| 6.2.6-76060206-generic   | 3         | 0.51%   |
| 6.2.0-26-generic         | 3         | 0.51%   |
| 6.1.1-desktop-1omv2290   | 3         | 0.51%   |
| 5.8.16-2-MANJARO         | 3         | 0.51%   |
| 5.8.0-7630-generic       | 3         | 0.51%   |
| 5.8.0-59-generic         | 3         | 0.51%   |
| 5.8.0-43-generic         | 3         | 0.51%   |
| 5.4.0-52-generic         | 3         | 0.51%   |
| 5.4.0-48-generic         | 3         | 0.51%   |
| 5.4.0-47-generic         | 3         | 0.51%   |
| 5.4.0-37-generic         | 3         | 0.51%   |
| 5.4.0-29-generic         | 3         | 0.51%   |
| 5.4.0-19-generic         | 3         | 0.51%   |
| 5.19.0-38-generic        | 3         | 0.51%   |
| 5.15.0-71-generic        | 3         | 0.51%   |
| 5.15.0-58-generic        | 3         | 0.51%   |
| 5.15.0-56-generic        | 3         | 0.51%   |
| 5.15.0-47-generic        | 3         | 0.51%   |
| 5.15.0-40-generic        | 3         | 0.51%   |
| 5.13.0-7620-generic      | 3         | 0.51%   |
| 5.13.0-52-generic        | 3         | 0.51%   |
| 5.11.0-41-generic        | 3         | 0.51%   |
| 5.11.0-40-generic        | 3         | 0.51%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4.0   | 52        | 9.12%   |
| 5.15.0  | 36        | 6.32%   |
| 5.11.0  | 32        | 5.61%   |
| 6.8.0   | 24        | 4.21%   |
| 5.8.0   | 20        | 3.51%   |
| 5.13.0  | 18        | 3.16%   |
| 6.14.2  | 17        | 2.98%   |
| 4.15.0  | 16        | 2.81%   |
| 5.19.0  | 14        | 2.46%   |
| 6.14.0  | 13        | 2.28%   |
| 6.1.0   | 13        | 2.28%   |
| 6.5.0   | 12        | 2.11%   |
| 5.10.0  | 12        | 2.11%   |
| 5.3.0   | 11        | 1.93%   |
| 4.18.0  | 11        | 1.93%   |
| 6.2.0   | 10        | 1.75%   |
| 5.0.0   | 10        | 1.75%   |
| 5.16.7  | 8         | 1.4%    |
| 6.12.9  | 6         | 1.05%   |
| 6.12.1  | 6         | 1.05%   |
| 6.11.0  | 6         | 1.05%   |
| 6.1.1   | 5         | 0.88%   |
| 5.14.0  | 5         | 0.88%   |
| 6.4.11  | 4         | 0.7%    |
| 6.2.6   | 4         | 0.7%    |
| 5.9.16  | 4         | 0.7%    |
| 5.10.14 | 4         | 0.7%    |
| 6.9.3   | 3         | 0.53%   |
| 6.17.0  | 3         | 0.53%   |
| 6.13.7  | 3         | 0.53%   |
| 6.10.6  | 3         | 0.53%   |
| 6.0.0   | 3         | 0.53%   |
| 5.8.16  | 3         | 0.53%   |
| 4.9.60  | 3         | 0.53%   |
| 4.19.0  | 3         | 0.53%   |
| 6.9.7   | 2         | 0.35%   |
| 6.8.7   | 2         | 0.35%   |
| 6.7.3   | 2         | 0.35%   |
| 6.6.9   | 2         | 0.35%   |
| 6.6.2   | 2         | 0.35%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.4     | 55        | 9.84%   |
| 5.15    | 45        | 8.05%   |
| 5.11    | 39        | 6.98%   |
| 6.14    | 31        | 5.55%   |
| 6.8     | 29        | 5.19%   |
| 6.12    | 24        | 4.29%   |
| 5.8     | 24        | 4.29%   |
| 6.1     | 23        | 4.11%   |
| 6.2     | 21        | 3.76%   |
| 5.13    | 21        | 3.76%   |
| 5.10    | 21        | 3.76%   |
| 5.19    | 19        | 3.4%    |
| 6.5     | 18        | 3.22%   |
| 4.15    | 16        | 2.86%   |
| 6.11    | 13        | 2.33%   |
| 5.16    | 13        | 2.33%   |
| 5.3     | 12        | 2.15%   |
| 6.6     | 11        | 1.97%   |
| 5.0     | 11        | 1.97%   |
| 4.18    | 11        | 1.97%   |
| 6.9     | 8         | 1.43%   |
| 6.17    | 8         | 1.43%   |
| 5.9     | 8         | 1.43%   |
| 6.13    | 7         | 1.25%   |
| 5.14    | 7         | 1.25%   |
| 6.7     | 6         | 1.07%   |
| 6.4     | 6         | 1.07%   |
| 6.0     | 6         | 1.07%   |
| 5.18    | 5         | 0.89%   |
| 5.17    | 5         | 0.89%   |
| 4.9     | 5         | 0.89%   |
| 6.10    | 4         | 0.72%   |
| 5.6     | 4         | 0.72%   |
| 6.16    | 3         | 0.54%   |
| 4.19    | 3         | 0.54%   |
| 6.3     | 2         | 0.36%   |
| 6.15    | 2         | 0.36%   |
| 5.5     | 2         | 0.36%   |
| 5.12    | 2         | 0.36%   |
| 6.18    | 1         | 0.18%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| x86_64  | 471       | 97.92%  |
| i686    | 8         | 1.66%   |
| aarch64 | 2         | 0.42%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| GNOME           | 237       | 46.93%  |
| KDE5            | 77        | 15.25%  |
| KDE6            | 47        | 9.31%   |
| Unknown         | 42        | 8.32%   |
| XFCE            | 25        | 4.95%   |
| X-Cinnamon      | 23        | 4.55%   |
| LXQt            | 7         | 1.39%   |
| KDE             | 7         | 1.39%   |
| Cinnamon        | 7         | 1.39%   |
| MATE            | 6         | 1.19%   |
| KDE4            | 6         | 1.19%   |
| GNOME Flashback | 5         | 0.99%   |
| Pantheon        | 4         | 0.79%   |
| DWM             | 3         | 0.59%   |
| Budgie          | 2         | 0.4%    |
| Unity           | 1         | 0.2%    |
| Trinity         | 1         | 0.2%    |
| LXDE            | 1         | 0.2%    |
| i3              | 1         | 0.2%    |
| GNUstep         | 1         | 0.2%    |
| Endless:GNOME   | 1         | 0.2%    |
| bspwm           | 1         | 0.2%    |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 317       | 61.79%  |
| Wayland | 162       | 31.58%  |
| Unknown | 27        | 5.26%   |
| Tty     | 7         | 1.36%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 196       | 39.52%  |
| SDDM    | 99        | 19.96%  |
| GDM3    | 74        | 14.92%  |
| GDM     | 68        | 13.71%  |
| LightDM | 44        | 8.87%   |
| TDM     | 11        | 2.22%   |
| KDM     | 3         | 0.6%    |
| Ly      | 1         | 0.2%    |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| en_US   | 306       | 62.2%   |
| hr_HR   | 92        | 18.7%   |
| Unknown | 42        | 8.54%   |
| en_GB   | 30        | 6.1%    |
| C       | 8         | 1.63%   |
| de_DE   | 7         | 1.42%   |
| POSIX   | 1         | 0.2%    |
| pl_PL   | 1         | 0.2%    |
| nl_BE   | 1         | 0.2%    |
| hr_BA   | 1         | 0.2%    |
| fr_FR   | 1         | 0.2%    |
| en_DE   | 1         | 0.2%    |
| en_150  | 1         | 0.2%    |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 289       | 58.38%  |
| BIOS | 206       | 41.62%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 341       | 68.61%  |
| Btrfs   | 69        | 13.88%  |
| Overlay | 28        | 5.63%   |
| Tmpfs   | 24        | 4.83%   |
| Unknown | 16        | 3.22%   |
| Xfs     | 11        | 2.21%   |
| Zfs     | 6         | 1.21%   |
| Jfs     | 1         | 0.2%    |
| Ext2    | 1         | 0.2%    |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 248       | 50.41%  |
| Unknown | 201       | 40.85%  |
| MBR     | 43        | 8.74%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 446       | 90.84%  |
| Yes       | 45        | 9.16%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 380       | 77.55%  |
| Yes       | 110       | 22.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Notebooks | Percent |
|-------------------------|-----------|---------|
| Lenovo                  | 122       | 25.36%  |
| Hewlett-Packard         | 98        | 20.37%  |
| ASUSTek Computer        | 77        | 16.01%  |
| Acer                    | 71        | 14.76%  |
| Dell                    | 46        | 9.56%   |
| Toshiba                 | 10        | 2.08%   |
| Apple                   | 7         | 1.46%   |
| TUXEDO                  | 6         | 1.25%   |
| Tactus                  | 5         | 1.04%   |
| Samsung Electronics     | 4         | 0.83%   |
| MSI                     | 4         | 0.83%   |
| HUAWEI                  | 4         | 0.83%   |
| Unknown                 | 4         | 0.83%   |
| Fujitsu Siemens         | 3         | 0.62%   |
| eMachines               | 3         | 0.62%   |
| Timi                    | 2         | 0.42%   |
| Schenker                | 2         | 0.42%   |
| Gigabyte Technology     | 2         | 0.42%   |
| Valve                   | 1         | 0.21%   |
| System76                | 1         | 0.21%   |
| Sony                    | 1         | 0.21%   |
| SHENZHEN X&F TECHNOLOGY | 1         | 0.21%   |
| Razer                   | 1         | 0.21%   |
| Pretech                 | 1         | 0.21%   |
| Notebook                | 1         | 0.21%   |
| Medion                  | 1         | 0.21%   |
| Framework               | 1         | 0.21%   |
| Dynabook                | 1         | 0.21%   |
| Chuwi                   | 1         | 0.21%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                    | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| HP Laptop 15-fc0xxx                     | 9         | 1.87%   |
| Unknown                                 | 6         | 1.25%   |
| Tactus GeoBook 140                      | 5         | 1.04%   |
| TUXEDO InfinityBook Pro AMD Gen9        | 4         | 0.83%   |
| Acer Aspire A315-21                     | 4         | 0.83%   |
| Lenovo Legion 5 15ARH05 82B5            | 3         | 0.62%   |
| Lenovo G710 20252                       | 3         | 0.62%   |
| Dell Inspiron 3542                      | 3         | 0.62%   |
| ASUS ASUS Vivobook S 16 M5606WA_M5606WA | 3         | 0.62%   |
| Acer Swift SF314-43                     | 3         | 0.62%   |
| Acer Aspire E5-771G                     | 3         | 0.62%   |
| Acer Aspire A515-51G                    | 3         | 0.62%   |
| TUXEDO Pulse 15 Gen1                    | 2         | 0.42%   |
| Timi TM1701                             | 2         | 0.42%   |
| Lenovo Z50-70 20354                     | 2         | 0.42%   |
| Lenovo ThinkBook 16p Gen 2 20YM         | 2         | 0.42%   |
| Lenovo ThinkBook 16 G6 IRL 21KH         | 2         | 0.42%   |
| Lenovo ThinkBook 15-IIL 20SM            | 2         | 0.42%   |
| Lenovo ThinkBook 15 G2 ITL 20VE         | 2         | 0.42%   |
| Lenovo Legion 5 Pro 16ACH6H 82JQ        | 2         | 0.42%   |
| Lenovo G500 20236                       | 2         | 0.42%   |
| Lenovo G40-30 80FY                      | 2         | 0.42%   |
| HP ProBook 450 G7                       | 2         | 0.42%   |
| HP Presario CQ57                        | 2         | 0.42%   |
| HP OMEN by Laptop                       | 2         | 0.42%   |
| HP Notebook                             | 2         | 0.42%   |
| HP Laptop 15s-eq2xxx                    | 2         | 0.42%   |
| HP EliteBook 8560p                      | 2         | 0.42%   |
| HP EliteBook 850 G6                     | 2         | 0.42%   |
| HP EliteBook 8470p                      | 2         | 0.42%   |
| HP EliteBook 845 G8 Notebook PC         | 2         | 0.42%   |
| HP 2000                                 | 2         | 0.42%   |
| Fujitsu Siemens ESPRIMO Mobile V5535    | 2         | 0.42%   |
| Dell XPS 13 9310                        | 2         | 0.42%   |
| Dell Vostro 3500                        | 2         | 0.42%   |
| Dell Inspiron N5110                     | 2         | 0.42%   |
| Dell Inspiron 5570                      | 2         | 0.42%   |
| ASUS ZenBook UX431DA_UM431DA            | 2         | 0.42%   |
| ASUS X751NV                             | 2         | 0.42%   |
| ASUS VivoBook_ASUSLaptop X705FD_N705FD  | 2         | 0.42%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 56        | 11.64%  |
| Acer Aspire         | 52        | 10.81%  |
| ASUS VivoBook       | 22        | 4.57%   |
| HP EliteBook        | 21        | 4.37%   |
| HP Laptop           | 19        | 3.95%   |
| HP ProBook          | 15        | 3.12%   |
| Lenovo IdeaPad      | 14        | 2.91%   |
| Lenovo ThinkBook    | 13        | 2.7%    |
| Dell Inspiron       | 13        | 2.7%    |
| Lenovo Legion       | 12        | 2.49%   |
| HP Pavilion         | 12        | 2.49%   |
| Dell Latitude       | 12        | 2.49%   |
| ASUS ASUS           | 10        | 2.08%   |
| ASUS Zenbook        | 9         | 1.87%   |
| Acer Swift          | 9         | 1.87%   |
| Toshiba Satellite   | 8         | 1.66%   |
| Dell Vostro         | 8         | 1.66%   |
| ASUS ROG            | 8         | 1.66%   |
| Dell XPS            | 7         | 1.46%   |
| HP Compaq           | 6         | 1.25%   |
| Unknown             | 6         | 1.25%   |
| Tactus GeoBook      | 5         | 1.04%   |
| HP ZBook            | 5         | 1.04%   |
| HP OMEN             | 5         | 1.04%   |
| TUXEDO InfinityBook | 4         | 0.83%   |
| HP 250              | 4         | 0.83%   |
| ASUS TUF            | 4         | 0.83%   |
| Acer Nitro          | 4         | 0.83%   |
| Lenovo Yoga         | 3         | 0.62%   |
| Lenovo G710         | 3         | 0.62%   |
| Acer Predator       | 3         | 0.62%   |
| TUXEDO Pulse        | 2         | 0.42%   |
| Timi TM1701         | 2         | 0.42%   |
| MSI Katana          | 2         | 0.42%   |
| Lenovo Z50-70       | 2         | 0.42%   |
| Lenovo G500         | 2         | 0.42%   |
| Lenovo G40-30       | 2         | 0.42%   |
| Lenovo B590         | 2         | 0.42%   |
| Lenovo 3000         | 2         | 0.42%   |
| HP Presario         | 2         | 0.42%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Notebooks | Percent |
|---------|-----------|---------|
| 2021    | 53        | 11.02%  |
| 2018    | 49        | 10.19%  |
| 2019    | 46        | 9.56%   |
| 2020    | 45        | 9.36%   |
| 2017    | 34        | 7.07%   |
| 2014    | 29        | 6.03%   |
| 2012    | 27        | 5.61%   |
| 2013    | 26        | 5.41%   |
| 2022    | 23        | 4.78%   |
| 2016    | 23        | 4.78%   |
| 2023    | 22        | 4.57%   |
| 2011    | 22        | 4.57%   |
| 2024    | 17        | 3.53%   |
| 2008    | 14        | 2.91%   |
| 2015    | 12        | 2.49%   |
| 2007    | 12        | 2.49%   |
| 2010    | 9         | 1.87%   |
| 2009    | 8         | 1.66%   |
| 2006    | 5         | 1.04%   |
| 2025    | 3         | 0.62%   |
| Unknown | 2         | 0.42%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 481       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 438       | 90.31%  |
| Enabled  | 47        | 9.69%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 481       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 127       | 25.97%  |
| 8.01-16.0   | 108       | 22.09%  |
| 16.01-24.0  | 84        | 17.18%  |
| 3.01-4.0    | 79        | 16.16%  |
| 32.01-64.0  | 48        | 9.82%   |
| 24.01-32.0  | 19        | 3.89%   |
| 1.01-2.0    | 13        | 2.66%   |
| 2.01-3.0    | 6         | 1.23%   |
| 64.01-256.0 | 5         | 1.02%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 158       | 28.73%  |
| 2.01-3.0   | 136       | 24.73%  |
| 4.01-8.0   | 115       | 20.91%  |
| 3.01-4.0   | 73        | 13.27%  |
| 8.01-16.0  | 37        | 6.73%   |
| 0.51-1.0   | 22        | 4%      |
| 16.01-24.0 | 6         | 1.09%   |
| 0.01-0.5   | 2         | 0.36%   |
| 24.01-32.0 | 1         | 0.18%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 377       | 75.86%  |
| 2      | 97        | 19.52%  |
| 3      | 13        | 2.62%   |
| 4      | 4         | 0.8%    |
| 0      | 4         | 0.8%    |
| 6      | 1         | 0.2%    |
| 5      | 1         | 0.2%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 360       | 74.23%  |
| Yes       | 125       | 25.77%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 382       | 78.76%  |
| No        | 103       | 21.24%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 460       | 95.44%  |
| No        | 22        | 4.56%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 414       | 84.66%  |
| No        | 75        | 15.34%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Croatia | 481       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City               | Notebooks | Percent |
|--------------------|-----------|---------|
| Zagreb             | 303       | 55.29%  |
| Split              | 32        | 5.84%   |
| Rijeka             | 21        | 3.83%   |
| Varaždin          | 11        | 2.01%   |
| Osijek             | 9         | 1.64%   |
| Pula               | 8         | 1.46%   |
| Zadar              | 6         | 1.09%   |
| Velika Gorica      | 6         | 1.09%   |
| Čakovec           | 6         | 1.09%   |
| Bjelovar           | 6         | 1.09%   |
| Zaprešić         | 5         | 0.91%   |
| Đakovo            | 4         | 0.73%   |
| Samobor            | 4         | 0.73%   |
| Koprivnica         | 4         | 0.73%   |
| Kastav             | 4         | 0.73%   |
| Virovitica         | 3         | 0.55%   |
| Vinkovci           | 3         | 0.55%   |
| Sisak              | 3         | 0.55%   |
| Šibenik           | 3         | 0.55%   |
| Prigorje Brdovecko | 3         | 0.55%   |
| Petrinja           | 3         | 0.55%   |
| Karlovac           | 3         | 0.55%   |
| Jesenice           | 3         | 0.55%   |
| Zminj              | 2         | 0.36%   |
| Udbinja            | 2         | 0.36%   |
| Sesvete            | 2         | 0.36%   |
| Rovinj             | 2         | 0.36%   |
| Pitomaca           | 2         | 0.36%   |
| Omiš              | 2         | 0.36%   |
| Novska             | 2         | 0.36%   |
| Našice            | 2         | 0.36%   |
| Krizevci           | 2         | 0.36%   |
| Komiža            | 2         | 0.36%   |
| Dugo Selo          | 2         | 0.36%   |
| Cres               | 2         | 0.36%   |
| Cavle              | 2         | 0.36%   |
| Buzin              | 2         | 0.36%   |
| Biograd na Moru    | 2         | 0.36%   |
| Zabok              | 1         | 0.18%   |
| Vukovar            | 1         | 0.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Notebooks | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 94        | 118    | 15.85%  |
| WDC                         | 55        | 68     | 9.27%   |
| Sandisk                     | 52        | 64     | 8.77%   |
| Kingston                    | 47        | 61     | 7.93%   |
| SK hynix                    | 45        | 62     | 7.59%   |
| Seagate                     | 43        | 71     | 7.25%   |
| Micron Technology           | 39        | 47     | 6.58%   |
| Toshiba                     | 38        | 51     | 6.41%   |
| Intel                       | 25        | 32     | 4.22%   |
| Unknown                     | 15        | 15     | 2.53%   |
| Crucial                     | 15        | 20     | 2.53%   |
| Hitachi                     | 13        | 13     | 2.19%   |
| HGST                        | 11        | 11     | 1.85%   |
| Apple                       | 9         | 18     | 1.52%   |
| A-DATA Technology           | 9         | 9      | 1.52%   |
| Patriot                     | 8         | 9      | 1.35%   |
| Netac                       | 5         | 5      | 0.84%   |
| Kingston Technology Company | 5         | 5      | 0.84%   |
| Fujitsu                     | 5         | 7      | 0.84%   |
| China                       | 5         | 5      | 0.84%   |
| LITEON                      | 4         | 5      | 0.67%   |
| UMIS                        | 3         | 3      | 0.51%   |
| Silicon Motion              | 3         | 4      | 0.51%   |
| Phison Electronics          | 3         | 3      | 0.51%   |
| Micron/Crucial Technology   | 3         | 4      | 0.51%   |
| Transcend                   | 2         | 3      | 0.34%   |
| Phison                      | 2         | 2      | 0.34%   |
| Lenovo                      | 2         | 3      | 0.34%   |
| KIOXIA                      | 2         | 2      | 0.34%   |
| KingFast                    | 2         | 4      | 0.34%   |
| JMicron Technology          | 2         | 2      | 0.34%   |
| Intenso                     | 2         | 3      | 0.34%   |
| Gigabyte Technology         | 2         | 2      | 0.34%   |
| Emtec                       | 2         | 2      | 0.34%   |
| Vi550                       | 1         | 1      | 0.17%   |
| Verbatim                    | 1         | 1      | 0.17%   |
| Union Memory                | 1         | 1      | 0.17%   |
| StoreJet                    | 1         | 1      | 0.17%   |
| SSSTC                       | 1         | 1      | 0.17%   |
| SSK                         | 1         | 1      | 0.17%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                              | Notebooks | Percent |
|----------------------------------------------------|-----------|---------|
| Toshiba MQ01ABD100 1TB                             | 9         | 1.48%   |
| Samsung NVMe SSD Drive 512GB                       | 8         | 1.31%   |
| Kingston SA400S37240G 240GB SSD                    | 8         | 1.31%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 7         | 1.15%   |
| Sandisk WD PC SN5000S SDEPNSJ-1T00-1006 1TB        | 6         | 0.99%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB              | 6         | 0.99%   |
| SanDisk NVMe SSD Drive 512GB                       | 6         | 0.99%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD                | 6         | 0.99%   |
| Kingston SA400S37120G 120GB SSD                    | 6         | 0.99%   |
| Seagate ST1000LM035-1RK172 1TB                     | 5         | 0.82%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 5         | 0.82%   |
| Samsung MZALQ512HALU-000L2 512GB                   | 5         | 0.82%   |
| Netac SSD 128GB                                    | 5         | 0.82%   |
| Kingston SA400S37480G 480GB SSD                    | 5         | 0.82%   |
| HGST HTS721010A9E630 1TB                           | 5         | 0.82%   |
| Unknown MMC Card  32GB                             | 4         | 0.66%   |
| Seagate ST500LT012-1DG142 500GB                    | 4         | 0.66%   |
| SanDisk NVMe SSD Drive 1TB                         | 4         | 0.66%   |
| Samsung SSD 990 EVO 2TB                            | 4         | 0.66%   |
| Micron MTFDKBA1T0QFM-1BD1AABGB 1024GB              | 4         | 0.66%   |
| Micron 2450_MTFDKBA512TFK 512GB                    | 4         | 0.66%   |
| Micron 2400_MTFDKBA1T0QFM 1TB                      | 4         | 0.66%   |
| Crucial CT240BX500SSD1 240GB                       | 4         | 0.66%   |
| A-DATA SU630 240GB SSD                             | 4         | 0.66%   |
| WDC WD10SPZX-21Z10T0 1TB                           | 3         | 0.49%   |
| WDC PC SN730 SDBPNTY-1T00-1101 1TB                 | 3         | 0.49%   |
| Toshiba MQ04ABF100 1TB                             | 3         | 0.49%   |
| Toshiba MQ01ABF050 500GB                           | 3         | 0.49%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB             | 3         | 0.49%   |
| SK hynix NVMe SSD Drive 256GB                      | 3         | 0.49%   |
| Seagate ST9500325AS 500GB                          | 3         | 0.49%   |
| Seagate ST2000LM007-1R8174 2TB                     | 3         | 0.49%   |
| Seagate ST1000LM048-2E7172 1TB                     | 3         | 0.49%   |
| Samsung SSD 850 EVO 250GB                          | 3         | 0.49%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 3         | 0.49%   |
| Intel SSDPEKNW512G8H 512GB                         | 3         | 0.49%   |
| Intel NVMe SSD Drive 256GB                         | 3         | 0.49%   |
| Hitachi HTS545050A7E380 500GB                      | 3         | 0.49%   |
| WDC WD5000LPCX-60VHAT0 500GB                       | 2         | 0.33%   |
| WDC WD5000LPCX-24C6HT0 500GB                       | 2         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 42        | 59     | 30.66%  |
| WDC                 | 33        | 38     | 24.09%  |
| Toshiba             | 27        | 30     | 19.71%  |
| Hitachi             | 13        | 13     | 9.49%   |
| HGST                | 11        | 11     | 8.03%   |
| Fujitsu             | 5         | 7      | 3.65%   |
| Unknown             | 2         | 2      | 1.46%   |
| SSK                 | 1         | 1      | 0.73%   |
| Samsung Electronics | 1         | 2      | 0.73%   |
| JMicron Technology  | 1         | 1      | 0.73%   |
| Intenso             | 1         | 2      | 0.73%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 35        | 45     | 20%     |
| Samsung Electronics | 28        | 36     | 16%     |
| SanDisk             | 15        | 19     | 8.57%   |
| Crucial             | 12        | 17     | 6.86%   |
| Micron Technology   | 10        | 11     | 5.71%   |
| WDC                 | 9         | 12     | 5.14%   |
| SK hynix            | 9         | 16     | 5.14%   |
| A-DATA Technology   | 9         | 9      | 5.14%   |
| Patriot             | 8         | 9      | 4.57%   |
| Intel               | 7         | 8      | 4%      |
| Apple               | 7         | 12     | 4%      |
| Netac               | 5         | 5      | 2.86%   |
| China               | 4         | 4      | 2.29%   |
| LITEON              | 3         | 4      | 1.71%   |
| Toshiba             | 2         | 4      | 1.14%   |
| Emtec               | 2         | 2      | 1.14%   |
| Vi550               | 1         | 1      | 0.57%   |
| Transcend           | 1         | 2      | 0.57%   |
| StoreJet            | 1         | 1      | 0.57%   |
| SPCC                | 1         | 2      | 0.57%   |
| Phison              | 1         | 1      | 0.57%   |
| OCZ                 | 1         | 1      | 0.57%   |
| JMicron Technology  | 1         | 1      | 0.57%   |
| Intenso             | 1         | 1      | 0.57%   |
| Gigabyte Technology | 1         | 1      | 0.57%   |
| AMD                 | 1         | 3      | 0.57%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 247       | 332    | 44.03%  |
| SSD     | 159       | 227    | 28.34%  |
| HDD     | 133       | 166    | 23.71%  |
| MMC     | 12        | 12     | 2.14%   |
| Unknown | 10        | 22     | 1.78%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 258       | 378    | 47.96%  |
| NVMe | 247       | 331    | 45.91%  |
| SAS  | 21        | 38     | 3.9%    |
| MMC  | 12        | 12     | 2.23%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 192       | 272    | 66.67%  |
| 0.51-1.0   | 82        | 103    | 28.47%  |
| 1.01-2.0   | 14        | 18     | 4.86%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 101-250        | 135       | 26.42%  |
| 251-500        | 134       | 26.22%  |
| 501-1000       | 90        | 17.61%  |
| 1001-2000      | 48        | 9.39%   |
| 1-20           | 27        | 5.28%   |
| 51-100         | 22        | 4.31%   |
| Unknown        | 19        | 3.72%   |
| More than 3000 | 16        | 3.13%   |
| 21-50          | 14        | 2.74%   |
| 2001-3000      | 6         | 1.17%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 181       | 33.39%  |
| 21-50          | 107       | 19.74%  |
| 101-250        | 67        | 12.36%  |
| 51-100         | 66        | 12.18%  |
| 251-500        | 53        | 9.78%   |
| 501-1000       | 34        | 6.27%   |
| Unknown        | 19        | 3.51%   |
| 1001-2000      | 9         | 1.66%   |
| More than 3000 | 3         | 0.55%   |
| 2001-3000      | 2         | 0.37%   |
| 0              | 1         | 0.18%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                | Notebooks | Drives | Percent |
|--------------------------------------|-----------|--------|---------|
| HGST HTS721010A9E630 1TB             | 3         | 3      | 8.57%   |
| Hitachi HTS545050A7E380 500GB        | 2         | 2      | 5.71%   |
| WDC WDS240G2G0B-00EPW0 240GB SSD     | 1         | 1      | 2.86%   |
| WDC WD600VE-75HDT0 64GB              | 1         | 1      | 2.86%   |
| WDC WD10JPCX-24UE4T0 1TB             | 1         | 1      | 2.86%   |
| Toshiba MQ01ABD100 1TB               | 1         | 1      | 2.86%   |
| Toshiba MK6459GSXP 640GB             | 1         | 1      | 2.86%   |
| Toshiba MK3265GSX 320GB              | 1         | 1      | 2.86%   |
| Toshiba MK2555GSX 250GB              | 1         | 1      | 2.86%   |
| Toshiba MK2552GSX 250GB              | 1         | 1      | 2.86%   |
| Toshiba HDWJ105 500GB                | 1         | 1      | 2.86%   |
| SPCC Solid State Disk 120GB          | 1         | 2      | 2.86%   |
| SK hynix SH920 2.5 7MM 256GB SSD     | 1         | 2      | 2.86%   |
| SK hynix SC210 2.5 7MM 256GB SSD     | 1         | 1      | 2.86%   |
| Seagate ST9500420AS 500GB            | 1         | 2      | 2.86%   |
| Seagate ST9500325AS 500GB            | 1         | 1      | 2.86%   |
| Seagate ST9250827AS 250GB            | 1         | 1      | 2.86%   |
| Seagate ST500DM002-1BD142 500GB      | 1         | 2      | 2.86%   |
| Seagate ST2000LM007-1R8174 2TB       | 1         | 1      | 2.86%   |
| Seagate ST1000LM035-1RK172 1TB       | 1         | 1      | 2.86%   |
| Seagate ST1000LM024 HN-M101MBB 1TB   | 1         | 1      | 2.86%   |
| SanDisk SDSSDXPS960G 960GB           | 1         | 1      | 2.86%   |
| SanDisk SD6PP4M-256G-1006 256GB SSD  | 1         | 1      | 2.86%   |
| LITEON LMH-256V2M-11 MSATA 256GB SSD | 1         | 1      | 2.86%   |
| Intel SSDSC2KW512G8 512GB            | 1         | 1      | 2.86%   |
| Hitachi HTS723232A7A364 320GB        | 1         | 1      | 2.86%   |
| Hitachi HTS542512K9SA00 120GB        | 1         | 1      | 2.86%   |
| HGST HTS545050A7E380 500GB           | 1         | 1      | 2.86%   |
| HGST HTS541010A9E680 1TB             | 1         | 1      | 2.86%   |
| Crucial CT1024M550SSD1 1TB           | 1         | 1      | 2.86%   |
| China SSD 256GB                      | 1         | 1      | 2.86%   |
| A-DATA Technology SU630 240GB SSD    | 1         | 1      | 2.86%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Seagate           | 7         | 9      | 20.59%  |
| Toshiba           | 6         | 6      | 17.65%  |
| HGST              | 5         | 5      | 14.71%  |
| Hitachi           | 4         | 4      | 11.76%  |
| WDC               | 3         | 3      | 8.82%   |
| SK hynix          | 2         | 3      | 5.88%   |
| SPCC              | 1         | 2      | 2.94%   |
| SanDisk           | 1         | 2      | 2.94%   |
| LITEON            | 1         | 1      | 2.94%   |
| Intel             | 1         | 1      | 2.94%   |
| Crucial           | 1         | 1      | 2.94%   |
| China             | 1         | 1      | 2.94%   |
| A-DATA Technology | 1         | 1      | 2.94%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 7         | 9      | 29.17%  |
| Toshiba | 6         | 6      | 25%     |
| HGST    | 5         | 5      | 20.83%  |
| Hitachi | 4         | 4      | 16.67%  |
| WDC     | 2         | 2      | 8.33%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 23        | 26     | 71.88%  |
| SSD  | 9         | 13     | 28.13%  |

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


| Status   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 254       | 401    | 49.61%  |
| Works    | 227       | 319    | 44.34%  |
| Malfunc  | 31        | 39     | 6.05%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 299       | 48.94%  |
| Samsung Electronics                     | 71        | 11.62%  |
| AMD                                     | 61        | 9.98%   |
| SanDisk                                 | 51        | 8.35%   |
| SK hynix                                | 36        | 5.89%   |
| Micron Technology                       | 29        | 4.75%   |
| Kingston Technology Company             | 16        | 2.62%   |
| Toshiba America Info Systems            | 12        | 1.96%   |
| Phison Electronics                      | 6         | 0.98%   |
| Micron/Crucial Technology               | 4         | 0.65%   |
| Union Memory (Shenzhen)                 | 3         | 0.49%   |
| Silicon Motion                          | 3         | 0.49%   |
| Lite-On Technology                      | 3         | 0.49%   |
| Silicon Integrated Systems [SiS]        | 2         | 0.33%   |
| Nvidia                                  | 2         | 0.33%   |
| Lenovo                                  | 2         | 0.33%   |
| KIOXIA                                  | 2         | 0.33%   |
| VIA Technologies                        | 1         | 0.16%   |
| Solidigm                                | 1         | 0.16%   |
| Solid State Storage Technology          | 1         | 0.16%   |
| Shenzhen Unionmemory Information System | 1         | 0.16%   |
| Seagate Technology                      | 1         | 0.16%   |
| Realtek Semiconductor                   | 1         | 0.16%   |
| Marvell Technology Group                | 1         | 0.16%   |
| JMicron Technology                      | 1         | 0.16%   |
| ADATA Technology                        | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                              | 56        | 8.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 40        | 6.09%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 25        | 3.81%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                    | 24        | 3.65%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                      | 23        | 3.5%    |
| Intel Volume Management Device NVMe RAID Controller                              | 22        | 3.35%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 21        | 3.2%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]   | 17        | 2.59%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                | 16        | 2.44%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 15        | 2.28%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 15        | 2.28%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]            | 14        | 2.13%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 14        | 2.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                   | 14        | 2.13%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                 | 12        | 1.83%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                           | 12        | 1.83%   |
| SanDisk Ultra 3D / WD PC SN530, IX SN530, Blue SN550 NVMe SSD (DRAM-less)        | 11        | 1.67%   |
| Intel Tiger Lake-LP SATA Controller                                              | 11        | 1.67%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 10        | 1.52%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                               | 9         | 1.37%   |
| Sandisk WD PC SN5000S M.2 2280 NVMe SSD (DRAM-less)                              | 8         | 1.22%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                             | 8         | 1.22%   |
| SK hynix BC501 NVMe Solid State Drive                                            | 7         | 1.07%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD             | 7         | 1.07%   |
| Samsung NVMe SSD Controller PM9C1a (DRAM-less)                                   | 7         | 1.07%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 7         | 1.07%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 6         | 0.91%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 6         | 0.91%   |
| Intel SSD 670p Series [Keystone Harbor]                                          | 6         | 0.91%   |
| Intel SSD 660P Series                                                            | 6         | 0.91%   |
| Intel Comet Lake SATA AHCI Controller                                            | 6         | 0.91%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 5         | 0.76%   |
| Toshiba America Info Systems BG3 x2 NVMe SSD Controller (DRAM-less)              | 5         | 0.76%   |
| SK hynix BC511 NVMe SSD                                                          | 5         | 0.76%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 5         | 0.76%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 5         | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                           | 5         | 0.76%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 5         | 0.76%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                     | 4         | 0.61%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                   | 4         | 0.61%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 316       | 50.16%  |
| NVMe | 246       | 39.05%  |
| RAID | 37        | 5.87%   |
| IDE  | 31        | 4.92%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 355       | 73.8%   |
| AMD     | 124       | 25.78%  |
| Unknown | 2         | 0.42%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 15        | 3.12%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 13        | 2.7%    |
| Intel Core i7-8550U CPU @ 1.80GHz             | 12        | 2.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 8         | 1.66%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 8         | 1.66%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 8         | 1.66%   |
| AMD Ryzen 5 7520U with Radeon Graphics        | 8         | 1.66%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 8         | 1.66%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 7         | 1.46%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 7         | 1.46%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 1.46%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 7         | 1.46%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 6         | 1.25%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 6         | 1.25%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 5         | 1.04%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 5         | 1.04%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 5         | 1.04%   |
| Intel 12th Gen Core i7-12700H                 | 5         | 1.04%   |
| AMD Ryzen 7 8845HS w/ Radeon 780M Graphics    | 5         | 1.04%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 5         | 1.04%   |
| Intel Pentium CPU 2020M @ 2.40GHz             | 4         | 0.83%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 4         | 0.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 4         | 0.83%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 4         | 0.83%   |
| Intel Core i5-10300H CPU @ 2.50GHz            | 4         | 0.83%   |
| Intel 12th Gen Core i5-1235U                  | 4         | 0.83%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 4         | 0.83%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 4         | 0.83%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 3         | 0.62%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 3         | 0.62%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 3         | 0.62%   |
| Intel Pentium 3556U @ 1.70GHz                 | 3         | 0.62%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 3         | 0.62%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 3         | 0.62%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 3         | 0.62%   |
| Intel Core i3-5005U CPU @ 2.00GHz             | 3         | 0.62%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 3         | 0.62%   |
| Intel Core i3 CPU M 370 @ 2.40GHz             | 3         | 0.62%   |
| Intel Core 2 Duo CPU T7500 @ 2.20GHz          | 3         | 0.62%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 3         | 0.62%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 110       | 22.87%  |
| Intel Core i7           | 65        | 13.51%  |
| Other                   | 63        | 13.1%   |
| AMD Ryzen 7             | 38        | 7.9%    |
| AMD Ryzen 5             | 36        | 7.48%   |
| Intel Core i3           | 31        | 6.44%   |
| Intel Core 2 Duo        | 26        | 5.41%   |
| Intel Pentium           | 20        | 4.16%   |
| Intel Celeron           | 19        | 3.95%   |
| AMD Ryzen 3             | 9         | 1.87%   |
| AMD Ryzen 9             | 6         | 1.25%   |
| Intel Pentium Dual-Core | 5         | 1.04%   |
| Intel Core              | 5         | 1.04%   |
| Intel Atom              | 5         | 1.04%   |
| AMD E                   | 5         | 1.04%   |
| AMD A6                  | 5         | 1.04%   |
| Intel Pentium Dual      | 4         | 0.83%   |
| Intel Core i9           | 4         | 0.83%   |
| AMD Ryzen 5 PRO         | 4         | 0.83%   |
| Intel Pentium Silver    | 3         | 0.62%   |
| AMD Ryzen 7 PRO         | 3         | 0.62%   |
| AMD E1                  | 3         | 0.62%   |
| AMD A8                  | 3         | 0.62%   |
| Intel Pentium M         | 2         | 0.42%   |
| Intel Genuine           | 2         | 0.42%   |
| Intel Celeron M         | 1         | 0.21%   |
| AMD Turion 64 X2 Mobile | 1         | 0.21%   |
| AMD Athlon              | 1         | 0.21%   |
| AMD A4                  | 1         | 0.21%   |
| AMD A10                 | 1         | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 197       | 40.96%  |
| 4       | 152       | 31.6%   |
| 8       | 52        | 10.81%  |
| 6       | 41        | 8.52%   |
| 14      | 12        | 2.49%   |
| 10      | 12        | 2.49%   |
| 16      | 5         | 1.04%   |
| 12      | 5         | 1.04%   |
| 1       | 4         | 0.83%   |
| Unknown | 1         | 0.21%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 1       | 480       | 99.79%  |
| Unknown | 1         | 0.21%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Notebooks | Percent |
|---------|-----------|---------|
| 2       | 364       | 75.68%  |
| 1       | 116       | 24.12%  |
| Unknown | 1         | 0.21%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 467       | 96.69%  |
| Unknown        | 9         | 1.86%   |
| 32-bit         | 5         | 1.04%   |
| 64-bit         | 2         | 0.41%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 224       | 44.36%  |
| 0x806ea    | 17        | 3.37%   |
| 0x306a9    | 17        | 3.37%   |
| 0x306c3    | 16        | 3.17%   |
| 0x806e9    | 15        | 2.97%   |
| 0x906ea    | 13        | 2.57%   |
| 0x40651    | 13        | 2.57%   |
| 0x806ec    | 12        | 2.38%   |
| 0x0a50000c | 11        | 2.18%   |
| 0x806c1    | 10        | 1.98%   |
| 0x6fd      | 9         | 1.78%   |
| 0x206a7    | 8         | 1.58%   |
| 0x08108109 | 8         | 1.58%   |
| 0xa0652    | 7         | 1.39%   |
| 0x1067a    | 7         | 1.39%   |
| 0x08608103 | 6         | 1.19%   |
| 0x306d4    | 5         | 0.99%   |
| 0x10676    | 5         | 0.99%   |
| 0x08600106 | 5         | 0.99%   |
| 0x08600103 | 5         | 0.99%   |
| 0x06006705 | 5         | 0.99%   |
| 0x406e3    | 4         | 0.79%   |
| 0x30678    | 4         | 0.79%   |
| 0x0a50000d | 4         | 0.79%   |
| 0x0810100b | 4         | 0.79%   |
| 0x906e9    | 3         | 0.59%   |
| 0x906a3    | 3         | 0.59%   |
| 0x706e5    | 3         | 0.59%   |
| 0x706a1    | 3         | 0.59%   |
| 0x6fb      | 3         | 0.59%   |
| 0x506c9    | 3         | 0.59%   |
| 0x20655    | 3         | 0.59%   |
| 0x08108102 | 3         | 0.59%   |
| 0x05000119 | 3         | 0.59%   |
| 0xb06a2    | 2         | 0.4%    |
| 0x906ed    | 2         | 0.4%    |
| 0x906a4    | 2         | 0.4%    |
| 0x806eb    | 2         | 0.4%    |
| 0x706a8    | 2         | 0.4%    |
| 0x6e8      | 2         | 0.4%    |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name               | Notebooks | Percent |
|--------------------|-----------|---------|
| KabyLake           | 96        | 19.96%  |
| Unknown            | 61        | 12.68%  |
| Haswell            | 39        | 8.11%   |
| IvyBridge          | 26        | 5.41%   |
| TigerLake          | 23        | 4.78%   |
| Zen 3              | 19        | 3.95%   |
| Alderlake Hybrid   | 19        | 3.95%   |
| Penryn             | 18        | 3.74%   |
| Core               | 18        | 3.74%   |
| Zen+               | 16        | 3.33%   |
| Zen 2              | 16        | 3.33%   |
| Silvermont         | 13        | 2.7%    |
| CometLake          | 13        | 2.7%    |
| Broadwell          | 13        | 2.7%    |
| Skylake            | 12        | 2.49%   |
| SandyBridge        | 12        | 2.49%   |
| Goldmont plus      | 12        | 2.49%   |
| Icelake            | 8         | 1.66%   |
| Excavator          | 7         | 1.46%   |
| Bobcat             | 7         | 1.46%   |
| Westmere           | 6         | 1.25%   |
| Zen                | 4         | 0.83%   |
| P6                 | 4         | 0.83%   |
| Goldmont           | 4         | 0.83%   |
| Meteorlake Hybrid  | 3         | 0.62%   |
| Puma               | 2         | 0.42%   |
| Piledriver         | 2         | 0.42%   |
| Jaguar             | 2         | 0.42%   |
| Bonnell            | 2         | 0.42%   |
| Tremont            | 1         | 0.21%   |
| Steamroller        | 1         | 0.21%   |
| K8 Hammer          | 1         | 0.21%   |
| ArrowLake-H Hybrid | 1         | 0.21%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 317       | 50.72%  |
| AMD                              | 154       | 24.64%  |
| Nvidia                           | 151       | 24.16%  |
| Silicon Integrated Systems [SiS] | 2         | 0.32%   |
| VIA Technologies                 | 1         | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 31        | 4.86%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 24        | 3.76%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 22        | 3.45%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 21        | 3.29%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 2.82%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 17        | 2.66%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 16        | 2.51%   |
| AMD Renoir [Radeon Vega Series / Radeon Vega Mobile Series]                              | 14        | 2.19%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 14        | 2.19%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 13        | 2.04%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 13        | 2.04%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 12        | 1.88%   |
| AMD Lucienne                                                                             | 12        | 1.88%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 11        | 1.72%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 11        | 1.72%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 10        | 1.57%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 10        | 1.57%   |
| AMD Mendocino [Radeon 610M]                                                              | 10        | 1.57%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 9         | 1.41%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 9         | 1.41%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 9         | 1.41%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 9         | 1.41%   |
| Intel Raptor Lake-P [Iris Xe Graphics]                                                   | 8         | 1.25%   |
| AMD Rembrandt [Radeon 680M]                                                              | 8         | 1.25%   |
| Nvidia GM108M [GeForce 840M]                                                             | 7         | 1.1%    |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 7         | 1.1%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 7         | 1.1%    |
| AMD Sun XT [Radeon HD 8670A/8670M/8690M / R5 M330 / M430 / Radeon 520 Mobile]            | 7         | 1.1%    |
| AMD HawkPoint1                                                                           | 7         | 1.1%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 6         | 0.94%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 6         | 0.94%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 6         | 0.94%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 6         | 0.94%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 5         | 0.78%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 5         | 0.78%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 5         | 0.78%   |
| Nvidia AD107M [GeForce RTX 4050 Max-Q / Mobile]                                          | 5         | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 5         | 0.78%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 5         | 0.78%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 5         | 0.78%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 184       | 38.17%  |
| 1 x AMD        | 106       | 21.99%  |
| Intel + Nvidia | 103       | 21.37%  |
| 1 x Nvidia     | 29        | 6.02%   |
| Intel + AMD    | 23        | 4.77%   |
| AMD + Nvidia   | 19        | 3.94%   |
| 2 x Intel      | 7         | 1.45%   |
| 2 x AMD        | 6         | 1.24%   |
| Other          | 2         | 0.41%   |
| 1 x SiS        | 2         | 0.41%   |
| 1 x VIA        | 1         | 0.21%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 396       | 81.15%  |
| Proprietary | 62        | 12.7%   |
| Unknown     | 30        | 6.15%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 298       | 60.08%  |
| 0.01-0.5   | 74        | 14.92%  |
| 1.01-2.0   | 58        | 11.69%  |
| 3.01-4.0   | 38        | 7.66%   |
| 0.51-1.0   | 17        | 3.43%   |
| 7.01-8.0   | 6         | 1.21%   |
| 5.01-6.0   | 4         | 0.81%   |
| 2.01-3.0   | 1         | 0.2%    |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 102       | 17.65%  |
| BOE                     | 81        | 14.01%  |
| Chimei Innolux          | 75        | 12.98%  |
| LG Display              | 73        | 12.63%  |
| Samsung Electronics     | 68        | 11.76%  |
| Dell                    | 42        | 7.27%   |
| Lenovo                  | 16        | 2.77%   |
| AOC                     | 12        | 2.08%   |
| Sharp                   | 11        | 1.9%    |
| PANDA                   | 10        | 1.73%   |
| CSO                     | 8         | 1.38%   |
| Goldstar                | 7         | 1.21%   |
| Apple                   | 7         | 1.21%   |
| LG Philips              | 5         | 0.87%   |
| Chi Mei Optoelectronics | 5         | 0.87%   |
| Philips                 | 4         | 0.69%   |
| InfoVision              | 4         | 0.69%   |
| Hewlett-Packard         | 4         | 0.69%   |
| Acer                    | 4         | 0.69%   |
| TMX                     | 3         | 0.52%   |
| Quanta Display          | 3         | 0.52%   |
| ASUSTek Computer        | 3         | 0.52%   |
| Mi                      | 2         | 0.35%   |
| IBM                     | 2         | 0.35%   |
| Grundig                 | 2         | 0.35%   |
| Gigabyte Technology     | 2         | 0.35%   |
| BenQ                    | 2         | 0.35%   |
| ZTR                     | 1         | 0.17%   |
| ViewSonic               | 1         | 0.17%   |
| Valve                   | 1         | 0.17%   |
| Sony                    | 1         | 0.17%   |
| Panasonic               | 1         | 0.17%   |
| NCS                     | 1         | 0.17%   |
| MStar                   | 1         | 0.17%   |
| MSI                     | 1         | 0.17%   |
| InnoLux Display         | 1         | 0.17%   |
| Iiyama                  | 1         | 0.17%   |
| HJW                     | 1         | 0.17%   |
| Hitachi                 | 1         | 0.17%   |
| Fujitsu Siemens         | 1         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 7         | 1.18%   |
| Chimei Innolux LCD Monitor CMN155F 1920x1080 344x193mm 15.5-inch      | 6         | 1.01%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 6         | 1.01%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch        | 6         | 1.01%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 6         | 1.01%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 5         | 0.84%   |
| Samsung Electronics LCD Monitor SDC4178 3200x2000 344x215mm 16.0-inch | 4         | 0.67%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 4         | 0.67%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 4         | 0.67%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch              | 4         | 0.67%   |
| Dell U2713HM DEL407F 1920x1080 597x336mm 27.0-inch                    | 4         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch      | 4         | 0.67%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 4         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 4         | 0.67%   |
| BOE LCD Monitor BOE0C8E 2560x1600 329x206mm 15.3-inch                 | 4         | 0.67%   |
| BOE LCD Monitor BOE06BA 1920x1080 344x193mm 15.5-inch                 | 4         | 0.67%   |
| AOC 27G2G4 AOC2702 1920x1080 598x336mm 27.0-inch                      | 4         | 0.67%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.5%    |
| LG Display LCD Monitor LGD069A 1920x1080 340x190mm 15.3-inch          | 3         | 0.5%    |
| LG Display LCD Monitor LGD04E8 1920x1080 382x215mm 17.3-inch          | 3         | 0.5%    |
| LG Display LCD Monitor LGD034D 1366x768 344x194mm 15.5-inch           | 3         | 0.5%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 3         | 0.5%    |
| Dell SE2717H/HX DELD0A1 1920x1080 598x336mm 27.0-inch                 | 3         | 0.5%    |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                 | 3         | 0.5%    |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch         | 3         | 0.5%    |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch        | 3         | 0.5%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 2         | 0.34%   |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 2         | 0.34%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch               | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch  | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3848 1920x1200 367x230mm 17.1-inch | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SEC304C 1366x768 353x198mm 15.9-inch  | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4752 1366x768 344x194mm 15.5-inch  | 2         | 0.34%   |
| Samsung Electronics LCD Monitor SDC4180 2880x1620 344x194mm 15.5-inch | 2         | 0.34%   |
| Quanta Display LCD Monitor QDS002D 1400x1050 285x214mm 14.0-inch      | 2         | 0.34%   |
| LG Philips LCD Monitor LPLA002 1440x900 367x230mm 17.1-inch           | 2         | 0.34%   |
| LG Display LCD Monitor LGD064C 1920x1080 344x194mm 15.5-inch          | 2         | 0.34%   |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch          | 2         | 0.34%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 260       | 47.88%  |
| 1366x768 (WXGA)    | 85        | 15.65%  |
| 1600x900 (HD+)     | 30        | 5.52%   |
| 2560x1440 (QHD)    | 28        | 5.16%   |
| 3840x2160 (4K)     | 26        | 4.79%   |
| 1920x1200 (WUXGA)  | 20        | 3.68%   |
| 2880x1800          | 12        | 2.21%   |
| 2560x1600          | 12        | 2.21%   |
| 1440x900 (WXGA+)   | 12        | 2.21%   |
| 1280x800 (WXGA)    | 10        | 1.84%   |
| 1680x1050 (WSXGA+) | 8         | 1.47%   |
| 3440x1440          | 7         | 1.29%   |
| 3200x2000          | 7         | 1.29%   |
| 1280x1024 (SXGA)   | 4         | 0.74%   |
| 2880x1620          | 3         | 0.55%   |
| 2160x1440          | 3         | 0.55%   |
| 3840x2400          | 2         | 0.37%   |
| 1400x1050          | 2         | 0.37%   |
| 1024x600           | 2         | 0.37%   |
| 800x1280           | 1         | 0.18%   |
| 3840x1080          | 1         | 0.18%   |
| 2880x1920          | 1         | 0.18%   |
| 2560x1080          | 1         | 0.18%   |
| 1920x1280          | 1         | 0.18%   |
| 1280x960           | 1         | 0.18%   |
| 1280x720 (HD)      | 1         | 0.18%   |
| 1024x768 (XGA)     | 1         | 0.18%   |
| 1024x576           | 1         | 0.18%   |
| Unknown            | 1         | 0.18%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 250       | 43.03%  |
| 17      | 61        | 10.5%   |
| 14      | 56        | 9.64%   |
| 13      | 52        | 8.95%   |
| 27      | 34        | 5.85%   |
| 24      | 26        | 4.48%   |
| 16      | 22        | 3.79%   |
| 31      | 12        | 2.07%   |
| 23      | 12        | 2.07%   |
| 21      | 10        | 1.72%   |
| 34      | 7         | 1.2%    |
| 12      | 7         | 1.2%    |
| 54      | 6         | 1.03%   |
| Unknown | 4         | 0.69%   |
| 10      | 3         | 0.52%   |
| 25      | 2         | 0.34%   |
| 20      | 2         | 0.34%   |
| 11      | 2         | 0.34%   |
| 84      | 1         | 0.17%   |
| 72      | 1         | 0.17%   |
| 63      | 1         | 0.17%   |
| 55      | 1         | 0.17%   |
| 52      | 1         | 0.17%   |
| 49      | 1         | 0.17%   |
| 40      | 1         | 0.17%   |
| 38      | 1         | 0.17%   |
| 26      | 1         | 0.17%   |
| 22      | 1         | 0.17%   |
| 19      | 1         | 0.17%   |
| 18      | 1         | 0.17%   |
| 7       | 1         | 0.17%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 347       | 60.56%  |
| 501-600     | 66        | 11.52%  |
| 351-400     | 66        | 11.52%  |
| 201-300     | 37        | 6.46%   |
| 601-700     | 16        | 2.79%   |
| 401-500     | 15        | 2.62%   |
| 1001-1500   | 10        | 1.75%   |
| 701-800     | 7         | 1.22%   |
| Unknown     | 4         | 0.7%    |
| 801-900     | 2         | 0.35%   |
| 1501-2000   | 2         | 0.35%   |
| 1-100       | 1         | 0.17%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 392       | 78.87%  |
| 16/10   | 82        | 16.5%   |
| 21/9    | 7         | 1.41%   |
| 3/2     | 6         | 1.21%   |
| 4/3     | 4         | 0.8%    |
| 5/4     | 3         | 0.6%    |
| Unknown | 2         | 0.4%    |
| 0.67    | 1         | 0.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 249       | 42.78%  |
| 81-90          | 92        | 15.81%  |
| 121-130        | 50        | 8.59%   |
| 201-250        | 39        | 6.7%    |
| 301-350        | 35        | 6.01%   |
| 111-120        | 22        | 3.78%   |
| 351-500        | 18        | 3.09%   |
| 71-80          | 15        | 2.58%   |
| More than 1000 | 12        | 2.06%   |
| 251-300        | 9         | 1.55%   |
| 131-140        | 9         | 1.55%   |
| 151-200        | 7         | 1.2%    |
| 61-70          | 6         | 1.03%   |
| 91-100         | 4         | 0.69%   |
| Unknown        | 4         | 0.69%   |
| 41-50          | 3         | 0.52%   |
| 141-150        | 3         | 0.52%   |
| 51-60          | 2         | 0.34%   |
| 501-1000       | 2         | 0.34%   |
| 1-40           | 1         | 0.17%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 261       | 46.19%  |
| 101-120       | 131       | 23.19%  |
| 51-100        | 93        | 16.46%  |
| 161-240       | 47        | 8.32%   |
| More than 240 | 18        | 3.19%   |
| 1-50          | 11        | 1.95%   |
| Unknown       | 4         | 0.71%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 374       | 74.35%  |
| 2     | 98        | 19.48%  |
| 3     | 15        | 2.98%   |
| 0     | 14        | 2.78%   |
| 4     | 2         | 0.4%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 282       | 35.79%  |
| Intel                                  | 247       | 31.35%  |
| Qualcomm Atheros                       | 95        | 12.06%  |
| MediaTek                               | 43        | 5.46%   |
| Broadcom                               | 35        | 4.44%   |
| Broadcom Limited                       | 11        | 1.4%    |
| TP-Link                                | 7         | 0.89%   |
| Samsung Electronics                    | 7         | 0.89%   |
| Suzhou Motorcomm Electronic Technology | 5         | 0.63%   |
| Marvell Technology Group               | 5         | 0.63%   |
| Lenovo                                 | 5         | 0.63%   |
| ASIX Electronics                       | 5         | 0.63%   |
| Xiaomi                                 | 4         | 0.51%   |
| Shenzhen Goodix Technology             | 4         | 0.51%   |
| Ralink                                 | 4         | 0.51%   |
| Ralink Technology                      | 3         | 0.38%   |
| Qualcomm                               | 3         | 0.38%   |
| Motorola PCS                           | 3         | 0.38%   |
| D-Link                                 | 3         | 0.38%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.25%   |
| Qualcomm Atheros Communications        | 2         | 0.25%   |
| Ericsson Business Mobile Networks      | 2         | 0.25%   |
| Dell                                   | 2         | 0.25%   |
| VIA Technologies                       | 1         | 0.13%   |
| Ovislink                               | 1         | 0.13%   |
| Nvidia                                 | 1         | 0.13%   |
| Huawei Technologies                    | 1         | 0.13%   |
| HTC (High Tech Computer)               | 1         | 0.13%   |
| Hewlett-Packard                        | 1         | 0.13%   |
| Fibocom                                | 1         | 0.13%   |
| DisplayLink                            | 1         | 0.13%   |
| ASUSTek Computer                       | 1         | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller  | 174       | 19.08%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 32        | 3.51%   |
| Intel Wireless 8265 / 8275                                              | 27        | 2.96%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 24        | 2.63%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 2.63%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 23        | 2.52%   |
| Intel Wi-Fi 6 AX200                                                     | 23        | 2.52%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 1.86%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 17        | 1.86%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 17        | 1.86%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 1.75%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 1.75%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 1.54%   |
| Intel Ethernet Connection (4) I219-V                                    | 13        | 1.43%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 13        | 1.43%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 1.32%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 10        | 1.1%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 1.1%    |
| Intel Wireless 7265                                                     | 10        | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 10        | 1.1%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 0.99%   |
| Intel Wireless 7260                                                     | 8         | 0.88%   |
| Intel Wireless 3165                                                     | 8         | 0.88%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 0.88%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 0.77%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 0.77%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 7         | 0.77%   |
| Intel Ethernet Connection I217-LM                                       | 7         | 0.77%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 6         | 0.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 0.66%   |
| Intel Wireless 3160                                                     | 6         | 0.66%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 6         | 0.66%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 0.66%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller          | 5         | 0.55%   |
| Samsung Galaxy series, misc. (tethering mode)                           | 5         | 0.55%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 0.55%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 5         | 0.55%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 5         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 232       | 48.54%  |
| Qualcomm Atheros                | 81        | 16.95%  |
| Realtek Semiconductor           | 69        | 14.44%  |
| MediaTek                        | 39        | 8.16%   |
| Broadcom                        | 25        | 5.23%   |
| TP-Link                         | 7         | 1.46%   |
| Broadcom Limited                | 5         | 1.05%   |
| Ralink                          | 4         | 0.84%   |
| Ralink Technology               | 3         | 0.63%   |
| Qualcomm                        | 3         | 0.63%   |
| D-Link                          | 3         | 0.63%   |
| Qualcomm Atheros Communications | 2         | 0.42%   |
| Dell                            | 2         | 0.42%   |
| Ovislink                        | 1         | 0.21%   |
| Fibocom                         | 1         | 0.21%   |
| ASUSTek Computer                | 1         | 0.21%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                              | 27        | 5.63%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 24        | 5%      |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 24        | 5%      |
| Intel Wi-Fi 6 AX200                                                     | 23        | 4.79%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 17        | 3.54%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]    | 17        | 3.54%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 16        | 3.33%   |
| Intel Wi-Fi 6 AX201                                                     | 16        | 3.33%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter           | 15        | 3.13%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 14        | 2.92%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 12        | 2.5%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller             | 10        | 2.08%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 10        | 2.08%   |
| Intel Wireless 7265                                                     | 10        | 2.08%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 9         | 1.88%   |
| Intel Wireless 7260                                                     | 8         | 1.67%   |
| Intel Wireless 3165                                                     | 8         | 1.67%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 8         | 1.67%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 8         | 1.67%   |
| Broadcom BCM43142 802.11b/g/n                                           | 8         | 1.67%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 1.46%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 7         | 1.46%   |
| Intel Raptor Lake PCH CNVi WiFi                                         | 7         | 1.46%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 6         | 1.25%   |
| Intel Wireless 3160                                                     | 6         | 1.25%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]               | 6         | 1.25%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 6         | 1.25%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 5         | 1.04%   |
| MediaTek MT7902 802.11ax PCIe Wireless Network Adapter [Filogic 310]    | 5         | 1.04%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                 | 5         | 1.04%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection                 | 5         | 1.04%   |
| Intel Centrino Advanced-N 6235                                          | 5         | 1.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 5         | 1.04%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]      | 4         | 0.83%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 4         | 0.83%   |
| Intel Wireless 8260                                                     | 4         | 0.83%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 4         | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 4         | 0.83%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 4         | 0.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 0.83%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 239       | 57.31%  |
| Intel                                  | 91        | 21.82%  |
| Qualcomm Atheros                       | 26        | 6.24%   |
| Broadcom                               | 10        | 2.4%    |
| Samsung Electronics                    | 7         | 1.68%   |
| Broadcom Limited                       | 6         | 1.44%   |
| Suzhou Motorcomm Electronic Technology | 5         | 1.2%    |
| Marvell Technology Group               | 5         | 1.2%    |
| Lenovo                                 | 5         | 1.2%    |
| ASIX Electronics                       | 5         | 1.2%    |
| Xiaomi                                 | 4         | 0.96%   |
| MediaTek                               | 4         | 0.96%   |
| Motorola PCS                           | 3         | 0.72%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.48%   |
| VIA Technologies                       | 1         | 0.24%   |
| Nvidia                                 | 1         | 0.24%   |
| Huawei Technologies                    | 1         | 0.24%   |
| HTC (High Tech Computer)               | 1         | 0.24%   |
| DisplayLink                            | 1         | 0.24%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 174       | 41.23%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 32        | 7.58%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 23        | 5.45%   |
| Intel Ethernet Connection (4) I219-V                                   | 13        | 3.08%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 10        | 2.37%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 8         | 1.9%    |
| Intel Ethernet Connection I217-LM                                      | 7         | 1.66%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                 | 6         | 1.42%   |
| Suzhou Motorcomm Electronic YT6801 Gigabit Ethernet Controller         | 5         | 1.18%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 5         | 1.18%   |
| Realtek Killer E2600 GbE Controller                                    | 4         | 0.95%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 4         | 0.95%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 4         | 0.95%   |
| Intel Ethernet Connection (4) I219-LM                                  | 4         | 0.95%   |
| Intel Ethernet Connection (13) I219-V                                  | 4         | 0.95%   |
| ASIX AX88179 Gigabit Ethernet                                          | 4         | 0.95%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 3         | 0.71%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 0.71%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 3         | 0.71%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                  | 3         | 0.71%   |
| Motorola PCS motorola one 5G ace                                       | 3         | 0.71%   |
| Intel Ethernet Connection I218-LM                                      | 3         | 0.71%   |
| Intel Ethernet Connection (3) I218-LM                                  | 3         | 0.71%   |
| Intel Ethernet Connection (23) I219-V                                  | 3         | 0.71%   |
| Intel Ethernet Connection (16) I219-V                                  | 3         | 0.71%   |
| Intel Ethernet Connection (13) I219-LM                                 | 3         | 0.71%   |
| Intel 82577LM Gigabit Network Connection                               | 3         | 0.71%   |
| Intel 82567LM Gigabit Network Connection                               | 3         | 0.71%   |
| Silicon Integrated Systems [SiS] 191 Gigabit Ethernet Adapter          | 2         | 0.47%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)            | 2         | 0.47%   |
| Realtek RTL8125 2.5GbE Controller                                      | 2         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 2         | 0.47%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.47%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                | 2         | 0.47%   |
| Marvell Group 88E8055 PCI-E Gigabit Ethernet Controller                | 2         | 0.47%   |
| Lenovo USB-C Dock Ethernet                                             | 2         | 0.47%   |
| Intel Ethernet Connection I219-V                                       | 2         | 0.47%   |
| Intel Ethernet Connection I219-LM                                      | 2         | 0.47%   |
| Intel Ethernet Connection (6) I219-V                                   | 2         | 0.47%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.47%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 460       | 54.05%  |
| Ethernet | 381       | 44.77%  |
| Modem    | 8         | 0.94%   |
| Unknown  | 2         | 0.24%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 390       | 76.62%  |
| Ethernet | 119       | 23.38%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 343       | 71.31%  |
| 1     | 134       | 27.86%  |
| 0     | 3         | 0.62%   |
| 3     | 1         | 0.21%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 457       | 94.03%  |
| Yes  | 29        | 5.97%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 194       | 46.75%  |
| Realtek Semiconductor           | 47        | 11.33%  |
| Lite-On Technology              | 32        | 7.71%   |
| IMC Networks                    | 31        | 7.47%   |
| Qualcomm Atheros Communications | 28        | 6.75%   |
| Foxconn / Hon Hai               | 26        | 6.27%   |
| Broadcom                        | 18        | 4.34%   |
| Hewlett-Packard                 | 7         | 1.69%   |
| Apple                           | 7         | 1.69%   |
| Cambridge Silicon Radio         | 6         | 1.45%   |
| Toshiba                         | 5         | 1.2%    |
| MediaTek                        | 3         | 0.72%   |
| Foxconn International           | 3         | 0.72%   |
| Realtek                         | 2         | 0.48%   |
| Dell                            | 2         | 0.48%   |
| USI                             | 1         | 0.24%   |
| Ralink Technology               | 1         | 0.24%   |
| Ralink                          | 1         | 0.24%   |
| Chicony Electronics             | 1         | 0.24%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 61        | 14.7%   |
| Intel AX201 Bluetooth                               | 46        | 11.08%  |
| Realtek Bluetooth Radio                             | 42        | 10.12%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 26        | 6.27%   |
| Intel AX200 Bluetooth                               | 23        | 5.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 16        | 3.86%   |
| IMC Networks Wireless_Device                        | 15        | 3.61%   |
| Intel Bluetooth Device                              | 14        | 3.37%   |
| Foxconn / Hon Hai Wireless_Device                   | 13        | 3.13%   |
| IMC Networks Bluetooth Radio                        | 11        | 2.65%   |
| Qualcomm Atheros  Bluetooth Device                  | 9         | 2.17%   |
| Intel Wireless-AC 3168 Bluetooth                    | 8         | 1.93%   |
| Foxconn / Hon Hai Bluetooth Device                  | 8         | 1.93%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 7         | 1.69%   |
| Lite-On Bluetooth Device                            | 6         | 1.45%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 6         | 1.45%   |
| Lite-On Wireless_Device                             | 5         | 1.2%    |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 5         | 1.2%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.2%    |
| Intel AX210 Bluetooth                               | 5         | 1.2%    |
| Realtek  Bluetooth 4.2 Adapter                      | 4         | 0.96%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 4         | 0.96%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 4         | 0.96%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 4         | 0.96%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 4         | 0.96%   |
| Broadcom BCM2045 Bluetooth                          | 4         | 0.96%   |
| MediaTek Wireless_Device                            | 3         | 0.72%   |
| IMC Networks Bluetooth Device                       | 3         | 0.72%   |
| Foxconn International BCM43142A0 Bluetooth module   | 3         | 0.72%   |
| Apple Bluetooth USB Host Controller                 | 3         | 0.72%   |
| Realtek Bluetooth Radio                             | 2         | 0.48%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 2         | 0.48%   |
| Lite-On Atheros Bluetooth                           | 2         | 0.48%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.48%   |
| Broadcom HP Portable SoftSailing                    | 2         | 0.48%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 2         | 0.48%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.48%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 2         | 0.48%   |
| Apple Bluetooth Host Controller                     | 2         | 0.48%   |
| USI Bluetooth Device                                | 1         | 0.24%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                           | Notebooks | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 349       | 56.38%  |
| AMD                              | 134       | 21.65%  |
| Nvidia                           | 75        | 12.12%  |
| Logitech                         | 11        | 1.78%   |
| Lenovo                           | 8         | 1.29%   |
| JMTek                            | 8         | 1.29%   |
| C-Media Electronics              | 7         | 1.13%   |
| Samsung Electronics              | 3         | 0.48%   |
| Hewlett-Packard                  | 3         | 0.48%   |
| Trust                            | 2         | 0.32%   |
| Texas Instruments                | 2         | 0.32%   |
| Sony                             | 2         | 0.32%   |
| Silicon Integrated Systems [SiS] | 2         | 0.32%   |
| ZOOM                             | 1         | 0.16%   |
| YZ Technology                    | 1         | 0.16%   |
| VIA Technologies                 | 1         | 0.16%   |
| SteelSeries ApS                  | 1         | 0.16%   |
| Samson Technologies              | 1         | 0.16%   |
| Realtek Semiconductor            | 1         | 0.16%   |
| Plantronics                      | 1         | 0.16%   |
| Pioneer DJ                       | 1         | 0.16%   |
| M-Audio                          | 1         | 0.16%   |
| GN Netcom                        | 1         | 0.16%   |
| Dell                             | 1         | 0.16%   |
| BEHRINGER International          | 1         | 0.16%   |
| Audient                          | 1         | 0.16%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD Ryzen HD Audio Controller                                                                     | 101       | 13.05%  |
| Intel Sunrise Point-LP HD Audio                                                                   | 58        | 7.49%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                                       | 36        | 4.65%   |
| AMD Radeon High Definition Audio Controller                                                       | 33        | 4.26%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 28        | 3.62%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 23        | 2.97%   |
| Intel Cannon Lake PCH cAVS                                                                        | 23        | 2.97%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 21        | 2.71%   |
| Intel 8 Series HD Audio Controller                                                                | 21        | 2.71%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 19        | 2.45%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 18        | 2.33%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 17        | 2.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 16        | 2.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 15        | 1.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 14        | 1.81%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 13        | 1.68%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 13        | 1.68%   |
| Intel Comet Lake PCH cAVS                                                                         | 13        | 1.68%   |
| Intel Broadwell-U Audio Controller                                                                | 13        | 1.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 12        | 1.55%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 12        | 1.55%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 12        | 1.55%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 1.29%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 9         | 1.16%   |
| Intel Raptor Lake-P/U/H cAVS                                                                      | 9         | 1.16%   |
| AMD FCH Azalia Controller                                                                         | 9         | 1.16%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 8         | 1.03%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 7         | 0.9%    |
| Nvidia AD107 High Definition Audio Controller                                                     | 6         | 0.78%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.78%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 6         | 0.78%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 6         | 0.78%   |
| AMD High Definition Audio Controller                                                              | 6         | 0.78%   |
| Nvidia GA107 High Definition Audio Controller                                                     | 5         | 0.65%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.65%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 5         | 0.65%   |
| AMD Kabini HDMI/DP Audio                                                                          | 5         | 0.65%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 4         | 0.52%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 4         | 0.52%   |
| JMTek USB PnP Audio Device                                                                        | 4         | 0.52%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 104       | 30.68%  |
| SK hynix            | 74        | 21.83%  |
| Micron Technology   | 50        | 14.75%  |
| Kingston            | 42        | 12.39%  |
| Crucial             | 24        | 7.08%   |
| Unknown             | 12        | 3.54%   |
| Ramaxel Technology  | 8         | 2.36%   |
| Elpida              | 4         | 1.18%   |
| A-DATA Technology   | 4         | 1.18%   |
| Unknown (ABCD)      | 3         | 0.88%   |
| Corsair             | 3         | 0.88%   |
| Patriot             | 2         | 0.59%   |
| Nanya Technology    | 2         | 0.59%   |
| Transcend           | 1         | 0.29%   |
| Silicon Power       | 1         | 0.29%   |
| Qimonda             | 1         | 0.29%   |
| G.Skill             | 1         | 0.29%   |
| Avant               | 1         | 0.29%   |
| 48spaces            | 1         | 0.29%   |
| Unknown             | 1         | 0.29%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GiB SODIMM DDR4 3200MT/s           | 9         | 2.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 6         | 1.64%   |
| Samsung RAM K3LKCKC0BM-MGCP 8GB LPDDR5 5500MT/s                  | 6         | 1.64%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.37%   |
| SK hynix RAM HMT451S6AFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 1.37%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 4         | 1.1%    |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 4         | 1.1%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 4         | 1.1%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 4         | 1.1%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 8400MT/s            | 4         | 1.1%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 4         | 1.1%    |
| Crucial RAM CT32G56C46S5.M16D1 32GB SODIMM DDR5 5600MT/s         | 4         | 1.1%    |
| Crucial RAM CT102464BF160B.C16 8GB SODIMM DDR3 1600MT/s          | 4         | 1.1%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 3         | 0.82%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 0.82%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 3         | 0.82%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 0.82%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s          | 3         | 0.82%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.82%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 3         | 0.82%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 3         | 0.82%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 0.82%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 3         | 0.82%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.82%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 3         | 0.82%   |
| Unknown RAM Module 4GB Row Of Chips LPDDR4 4267MT/s              | 2         | 0.55%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.55%   |
| SK hynix RAM HMT125S6TFR8C-H9 2GB SODIMM DDR3 1334MT/s           | 2         | 0.55%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 2         | 0.55%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.55%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 2         | 0.55%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 2         | 0.55%   |
| SK hynix RAM H58G66AK6BX070N 8GB LPDDR5 5500MT/s                 | 2         | 0.55%   |
| Samsung RAM Module 8192MB SODIMM DDR4 2667MT/s                   | 2         | 0.55%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 2         | 0.55%   |
| Samsung RAM M471B5773CHS-CH9 2GB SODIMM DDR3 4199MT/s            | 2         | 0.55%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 2400MT/s            | 2         | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 2         | 0.55%   |
| Samsung RAM M471A2G44BM0-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 0.55%   |
| Samsung RAM M471A2G44AM0-CWE 16GB Row Of Chips DDR4 3200MT/s     | 2         | 0.55%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Notebooks | Percent |
|---------|-----------|---------|
| DDR4    | 132       | 46.32%  |
| DDR3    | 72        | 25.26%  |
| DDR5    | 21        | 7.37%   |
| LPDDR5  | 18        | 6.32%   |
| DDR2    | 14        | 4.91%   |
| LPDDR4  | 13        | 4.56%   |
| LPDDR3  | 9         | 3.16%   |
| SDRAM   | 5         | 1.75%   |
| Unknown | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 245       | 86.57%  |
| Row Of Chips | 26        | 9.19%   |
| Unknown      | 9         | 3.18%   |
| DIMM         | 2         | 0.71%   |
| Chip         | 1         | 0.35%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 136       | 44.44%  |
| 4096  | 70        | 22.88%  |
| 16384 | 51        | 16.67%  |
| 2048  | 25        | 8.17%   |
| 32768 | 16        | 5.23%   |
| 1024  | 7         | 2.29%   |
| 512   | 1         | 0.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 70        | 22.88%  |
| 1600    | 56        | 18.3%   |
| 2667    | 55        | 17.97%  |
| 5600    | 14        | 4.58%   |
| 2400    | 14        | 4.58%   |
| 2133    | 11        | 3.59%   |
| 667     | 10        | 3.27%   |
| 5500    | 9         | 2.94%   |
| 4800    | 7         | 2.29%   |
| 8400    | 5         | 1.63%   |
| 1334    | 5         | 1.63%   |
| 1067    | 5         | 1.63%   |
| 6400    | 4         | 1.31%   |
| 4267    | 4         | 1.31%   |
| 4266    | 4         | 1.31%   |
| 3266    | 4         | 1.31%   |
| 1066    | 4         | 1.31%   |
| 4199    | 3         | 0.98%   |
| 1333    | 3         | 0.98%   |
| 7500    | 2         | 0.65%   |
| 2048    | 2         | 0.65%   |
| 1867    | 2         | 0.65%   |
| 975     | 2         | 0.65%   |
| 800     | 2         | 0.65%   |
| Unknown | 2         | 0.65%   |
| 12800   | 1         | 0.33%   |
| 8000    | 1         | 0.33%   |
| 7467    | 1         | 0.33%   |
| 3000    | 1         | 0.33%   |
| 2933    | 1         | 0.33%   |
| 1800    | 1         | 0.33%   |
| 533     | 1         | 0.33%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 60%     |
| Canon               | 3         | 30%     |
| Samsung Electronics | 1         | 10%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                           | Notebooks | Percent |
|---------------------------------|-----------|---------|
| HP LaserJet M203-M206           | 2         | 20%     |
| Samsung Composite Device        | 1         | 10%     |
| HP LaserJet P1005               | 1         | 10%     |
| HP LaserJet 400 colorMFP M475dw | 1         | 10%     |
| HP LaserJet 3050                | 1         | 10%     |
| HP Deskjet 1050 J410            | 1         | 10%     |
| Canon PIXMA iP4300 Printer      | 1         | 10%     |
| Canon LBP6670 UFR II            | 1         | 10%     |
| Canon G3030 series              | 1         | 10%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Notebooks | Percent |
|--------------------|-----------|---------|
| Seiko Epson        | 2         | 66.67%  |
| Ultima Electronics | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                            | Notebooks | Percent |
|--------------------------------------------------|-----------|---------|
| Seiko Epson GT-X900 [Perfection V700/V750 Photo] | 2         | 66.67%  |
| Ultima Artec Ultima 2000                         | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 113       | 25.45%  |
| IMC Networks                           | 55        | 12.39%  |
| Quanta                                 | 52        | 11.71%  |
| Bison Electronics                      | 29        | 6.53%   |
| Realtek Semiconductor                  | 28        | 6.31%   |
| Microdia                               | 20        | 4.5%    |
| Luxvisions Innotech Limited            | 19        | 4.28%   |
| Sunplus Innovation Technology          | 17        | 3.83%   |
| Suyin                                  | 14        | 3.15%   |
| Syntek                                 | 12        | 2.7%    |
| Lite-On Technology                     | 12        | 2.7%    |
| Sonix Technology                       | 10        | 2.25%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 2.25%   |
| Logitech                               | 9         | 2.03%   |
| Shinetech                              | 7         | 1.58%   |
| SunplusIT                              | 5         | 1.13%   |
| kingcome                               | 5         | 1.13%   |
| Apple                                  | 5         | 1.13%   |
| Silicon Motion                         | 3         | 0.68%   |
| Samsung Electronics                    | 2         | 0.45%   |
| Primax Electronics                     | 2         | 0.45%   |
| Jieli Technology                       | 2         | 0.45%   |
| Anker                                  | 2         | 0.45%   |
| Unknown                                | 2         | 0.45%   |
| Z-Star Microelectronics                | 1         | 0.23%   |
| Xiaomi                                 | 1         | 0.23%   |
| Ricoh                                  | 1         | 0.23%   |
| Lenovo                                 | 1         | 0.23%   |
| Goertek Electronics                    | 1         | 0.23%   |
| Genesys Logic                          | 1         | 0.23%   |
| Framework                              | 1         | 0.23%   |
| Cubeternet                             | 1         | 0.23%   |
| AVerMedia Technologies                 | 1         | 0.23%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 23        | 5.17%   |
| IMC Networks Integrated Camera                      | 19        | 4.27%   |
| Chicony HD WebCam                                   | 19        | 4.27%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 16        | 3.6%    |
| IMC Networks USB2.0 VGA UVC WebCam                  | 13        | 2.92%   |
| Quanta HD Webcam                                    | 10        | 2.25%   |
| Microdia Integrated_Webcam_HD                       | 10        | 2.25%   |
| Quanta VGA WebCam                                   | 9         | 2.02%   |
| Bison Integrated Camera                             | 9         | 2.02%   |
| Quanta HD User Facing                               | 8         | 1.8%    |
| Realtek Integrated_Webcam_HD                        | 7         | 1.57%   |
| Luxvisions Innotech Limited Integrated RGB Camera   | 7         | 1.57%   |
| Lite-On HP HD Camera                                | 7         | 1.57%   |
| Syntek Integrated Camera                            | 6         | 1.35%   |
| Sonix USB2.0 FHD UVC WebCam                         | 6         | 1.35%   |
| Quanta HP True Vision HD Camera                     | 6         | 1.35%   |
| Quanta HP HD Camera                                 | 6         | 1.35%   |
| SunplusIT SPCA2650 AV Camera                        | 5         | 1.12%   |
| Shinetech USB2.0 FHD UVC WebCam                     | 5         | 1.12%   |
| Quanta HP TrueVision HD Camera                      | 5         | 1.12%   |
| kingcome FHD WebCam                                 | 5         | 1.12%   |
| Chicony HP HD Camera                                | 5         | 1.12%   |
| Bison Lenovo EasyCamera                             | 5         | 1.12%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 4         | 0.9%    |
| Sunplus Integrated_Webcam_HD                        | 4         | 0.9%    |
| Sonix USB2.0 HD UVC WebCam                          | 4         | 0.9%    |
| Logitech Logitech Webcam C925e                      | 4         | 0.9%    |
| Chicony USB2.0 VGA UVC WebCam                       | 4         | 0.9%    |
| Chicony HP Wide Vision HD Camera                    | 4         | 0.9%    |
| Chicony HP Webcam                                   | 4         | 0.9%    |
| Bison Integrated RGB Camera                         | 4         | 0.9%    |
| Syntek Lenovo EasyCamera                            | 3         | 0.67%   |
| Suyin WebCam                                        | 3         | 0.67%   |
| Sunplus HD WebCam                                   | 3         | 0.67%   |
| Sunplus Asus Webcam                                 | 3         | 0.67%   |
| Realtek Lenovo EasyCamera                           | 3         | 0.67%   |
| Realtek Integrated Webcam                           | 3         | 0.67%   |
| Luxvisions Innotech Limited Integrated Camera       | 3         | 0.67%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 3         | 0.67%   |
| Lite-On Integrated Camera                           | 3         | 0.67%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Notebooks | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 36        | 36%     |
| Validity Sensors                   | 22        | 22%     |
| Shenzhen Goodix Technology         | 13        | 13%     |
| AuthenTec                          | 10        | 10%     |
| Elan Microelectronics              | 7         | 7%      |
| Upek                               | 5         | 5%      |
| LighTuning Technology              | 5         | 5%      |
| STMicroelectronics                 | 1         | 1%      |
| Realtek USB2.0 Finger Print Bridge | 1         | 1%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 10        | 10%     |
| Validity Sensors VFS495 Fingerprint Reader                                 | 8         | 8%      |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 8         | 8%      |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 7         | 7%      |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 7         | 7%      |
| Elan ELAN:Fingerprint                                                      | 7         | 7%      |
| AuthenTec AES2501 Fingerprint Sensor                                       | 6         | 6%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 5         | 5%      |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 5         | 5%      |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 4%      |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 3%      |
| Synaptics UWP WBDI Device                                                  | 3         | 3%      |
| Shenzhen Goodix FingerPrint                                                | 3         | 3%      |
| AuthenTec AES2810                                                          | 3         | 3%      |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2%      |
| Validity Sensors VFS491                                                    | 2         | 2%      |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 2%      |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 2%      |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 2         | 2%      |
| Synaptics Fingerprint reader [HP G6]                                       | 2         | 2%      |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 1%      |
| Validity Sensors Synaptics WBDI                                            | 1         | 1%      |
| Validity Sensors Fingerprint scanner                                       | 1         | 1%      |
| Synaptics WBDI                                                             | 1         | 1%      |
| Synaptics TouchPad                                                         | 1         | 1%      |
| Synaptics  WBDI                                                            | 1         | 1%      |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1%      |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 1         | 1%      |
| AuthenTec Fingerprint Sensor                                               | 1         | 1%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 14        | 51.85%  |
| Broadcom              | 6         | 22.22%  |
| Lenovo                | 4         | 14.81%  |
| Upek                  | 1         | 3.7%    |
| Realtek Semiconductor | 1         | 3.7%    |
| O2 Micro              | 1         | 3.7%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 14        | 51.85%  |
| Lenovo Integrated Smart Card Reader                                          | 4         | 14.81%  |
| Broadcom BCM58200 ControlVault 3 (FingerPrint sensor + Contacted SmartCard)  | 2         | 7.41%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 3.7%    |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 3.7%    |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 3.7%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 3.7%    |
| Broadcom BCM5880 Secure Applications Processor                               | 1         | 3.7%    |
| Broadcom 5880                                                                | 1         | 3.7%    |
| Broadcom 58200                                                               | 1         | 3.7%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 297       | 59.52%  |
| 1     | 159       | 31.86%  |
| 2     | 37        | 7.41%   |
| 3     | 5         | 1%      |
| 4     | 1         | 0.2%    |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Notebooks | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 98        | 40.16%  |
| Graphics card            | 52        | 21.31%  |
| Net/wireless             | 26        | 10.66%  |
| Chipcard                 | 23        | 9.43%   |
| Multimedia controller    | 15        | 6.15%   |
| Camera                   | 8         | 3.28%   |
| Net/ethernet             | 6         | 2.46%   |
| Communication controller | 5         | 2.05%   |
| Card reader              | 3         | 1.23%   |
| Storage                  | 2         | 0.82%   |
| Bluetooth                | 2         | 0.82%   |
| Storage/ide              | 1         | 0.41%   |
| Sound                    | 1         | 0.41%   |
| Modem                    | 1         | 0.41%   |
| Flash memory             | 1         | 0.41%   |

