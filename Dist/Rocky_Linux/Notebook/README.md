Rocky Linux - Tested Hardware & Statistics (Notebooks)
------------------------------------------------------

A project to collect tested hardware configurations for Rocky Linux.

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

Total: 189

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | Yoga 3 14 80JH              | [2d09f57ab7](https://linux-hardware.org/?probe=2d09f57ab7) | Dec 28, 2025 |
| Lenovo        | Yoga 3 14 80JH              | [1c16f9f2be](https://linux-hardware.org/?probe=1c16f9f2be) | Dec 27, 2025 |
| Dell          | Latitude E6520              | [59616d69c9](https://linux-hardware.org/?probe=59616d69c9) | Nov 30, 2025 |
| Dell          | Precision 7530              | [62924ae961](https://linux-hardware.org/?probe=62924ae961) | Oct 19, 2025 |
| HP            | 240 14 inch G9 Notebook ... | [3067d71c0b](https://linux-hardware.org/?probe=3067d71c0b) | Oct 10, 2025 |
| Alienware     | x17 R2                      | [97e66ac9fb](https://linux-hardware.org/?probe=97e66ac9fb) | Oct 06, 2025 |
| Alienware     | x17 R2                      | [b6643056e0](https://linux-hardware.org/?probe=b6643056e0) | Oct 06, 2025 |
| Alienware     | 15                          | [868250a4a2](https://linux-hardware.org/?probe=868250a4a2) | Sep 06, 2025 |
| Firebat Co... | T7-6R                       | [815887f435](https://linux-hardware.org/?probe=815887f435) | Jul 27, 2025 |
| HP            | Laptop 17-by4xxx            | [4da04e13c6](https://linux-hardware.org/?probe=4da04e13c6) | Jul 24, 2025 |
| Lenovo        | Legion Y530-15ICH 81FV      | [5fa14744c3](https://linux-hardware.org/?probe=5fa14744c3) | Jul 22, 2025 |
| Lenovo        | Legion Y530-15ICH 81FV      | [474e20f580](https://linux-hardware.org/?probe=474e20f580) | Jul 21, 2025 |
| ASUSTek       | Zenbook UX8402ZE_UX8402Z... | [130c6ff12e](https://linux-hardware.org/?probe=130c6ff12e) | Jul 11, 2025 |
| Lenovo        | ThinkPad P15v Gen 3 21D8... | [c1e9d5c7d8](https://linux-hardware.org/?probe=c1e9d5c7d8) | Jul 07, 2025 |
| Dell          | Latitude 3301               | [4541cebc9d](https://linux-hardware.org/?probe=4541cebc9d) | Jul 01, 2025 |
| Gigabyte      | AORUS 15P XD                | [63590fc9c8](https://linux-hardware.org/?probe=63590fc9c8) | Jul 01, 2025 |
| Acer          | Aspire E5-575G              | [81b2140c9d](https://linux-hardware.org/?probe=81b2140c9d) | Jun 30, 2025 |
| Dell          | Studio 1558                 | [66a4a67d6c](https://linux-hardware.org/?probe=66a4a67d6c) | Jun 10, 2025 |
| Unknown       | Unknown                     | [332c87f466](https://linux-hardware.org/?probe=332c87f466) | May 21, 2025 |
| Acer          | Aspire A315-53              | [0ab9fe74f5](https://linux-hardware.org/?probe=0ab9fe74f5) | May 12, 2025 |
| HP            | OMEN by Laptop 15-dc1xxx    | [c421211645](https://linux-hardware.org/?probe=c421211645) | May 06, 2025 |
| ILLEGEAR      | RAVEN SE                    | [bdad2d59e1](https://linux-hardware.org/?probe=bdad2d59e1) | Apr 16, 2025 |
| ILLEGEAR      | RAVEN SE                    | [549e09f72b](https://linux-hardware.org/?probe=549e09f72b) | Apr 16, 2025 |
| Lenovo        | ThinkPad P53 20QNS00X00     | [16cb5658ad](https://linux-hardware.org/?probe=16cb5658ad) | Mar 22, 2025 |
| Lenovo        | ThinkPad E14 20RBS20600     | [d5bbe466be](https://linux-hardware.org/?probe=d5bbe466be) | Mar 06, 2025 |
| HP            | Elite Dragonfly 13.5 inc... | [2c06deff42](https://linux-hardware.org/?probe=2c06deff42) | Feb 28, 2025 |
| ASUSTek       | ROG Strix G513QY_G513QY     | [71ad0951c4](https://linux-hardware.org/?probe=71ad0951c4) | Feb 26, 2025 |
| Sony          | VPCF237FJ                   | [31b310e23f](https://linux-hardware.org/?probe=31b310e23f) | Feb 15, 2025 |
| Dell          | Latitude E5430 non-vPro     | [6f0f74ee85](https://linux-hardware.org/?probe=6f0f74ee85) | Jan 29, 2025 |
| Dell          | Latitude E5430 non-vPro     | [354ea1c6e1](https://linux-hardware.org/?probe=354ea1c6e1) | Jan 29, 2025 |
| PC Special... | PA70Hx                      | [502e06c35e](https://linux-hardware.org/?probe=502e06c35e) | Jan 23, 2025 |
| Dell          | Inspiron 5559               | [d2264f823c](https://linux-hardware.org/?probe=d2264f823c) | Jan 20, 2025 |
| HP            | ProBook 450 G3              | [9225385627](https://linux-hardware.org/?probe=9225385627) | Jan 15, 2025 |
| Lenovo        | ThinkPad T460 20FMS0K624    | [206e2a5d2b](https://linux-hardware.org/?probe=206e2a5d2b) | Jan 14, 2025 |
| PC Special... | PA70Hx                      | [d44a3116ed](https://linux-hardware.org/?probe=d44a3116ed) | Dec 21, 2024 |
| HP            | OMEN by Laptop              | [1990440c77](https://linux-hardware.org/?probe=1990440c77) | Dec 17, 2024 |
| HP            | OMEN by Laptop              | [655aeac73d](https://linux-hardware.org/?probe=655aeac73d) | Dec 16, 2024 |
| ASUSTek       | ProArt Studiobook H7604J... | [a099000019](https://linux-hardware.org/?probe=a099000019) | Dec 15, 2024 |
| PC Special... | PA70Hx                      | [4923c61977](https://linux-hardware.org/?probe=4923c61977) | Dec 07, 2024 |
| Dell          | Vostro 15 3515              | [c220d225cc](https://linux-hardware.org/?probe=c220d225cc) | Dec 03, 2024 |
| Lenovo        | Legion Pro 7 16IRX9H 83D... | [0ee441425f](https://linux-hardware.org/?probe=0ee441425f) | Nov 30, 2024 |
| Lenovo        | Legion Pro 7 16IRX9H 83D... | [e1fffcf363](https://linux-hardware.org/?probe=e1fffcf363) | Nov 29, 2024 |
| HP            | ProBook 440 14 inch G9 N... | [ae8591ed7e](https://linux-hardware.org/?probe=ae8591ed7e) | Nov 29, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [4a80bcfae8](https://linux-hardware.org/?probe=4a80bcfae8) | Nov 20, 2024 |
| ASUSTek       | GL552VW                     | [77e30dc8de](https://linux-hardware.org/?probe=77e30dc8de) | Nov 19, 2024 |
| Gigabyte      | AORUS 7A K1                 | [9b3907c59e](https://linux-hardware.org/?probe=9b3907c59e) | Nov 19, 2024 |
| Dell          | XPS 14 9440                 | [30755e72e7](https://linux-hardware.org/?probe=30755e72e7) | Nov 19, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [1f4cfc38ad](https://linux-hardware.org/?probe=1f4cfc38ad) | Nov 18, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | [75f0fcdc2f](https://linux-hardware.org/?probe=75f0fcdc2f) | Nov 18, 2024 |
| ASUSTek       | GL552VW                     | [257a158847](https://linux-hardware.org/?probe=257a158847) | Nov 18, 2024 |
| Fujitsu       | LIFEBOOK S710               | [c989615c93](https://linux-hardware.org/?probe=c989615c93) | Nov 02, 2024 |
| Lenovo        | V15 G4 IRU 83A1             | [d40ad835b1](https://linux-hardware.org/?probe=d40ad835b1) | Oct 27, 2024 |
| Lenovo        | ThinkPad E14 20RA007TUE     | [6314a52501](https://linux-hardware.org/?probe=6314a52501) | Oct 24, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop X409... | [e9e3c256d2](https://linux-hardware.org/?probe=e9e3c256d2) | Oct 19, 2024 |
| Acer          | Aspire E5-523               | [a248ae3561](https://linux-hardware.org/?probe=a248ae3561) | Oct 14, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [d6687a8b24](https://linux-hardware.org/?probe=d6687a8b24) | Oct 01, 2024 |
| HP            | ProBook 450 G4              | [74d843a3ff](https://linux-hardware.org/?probe=74d843a3ff) | Oct 01, 2024 |
| Dell          | Precision 7530              | [9298200755](https://linux-hardware.org/?probe=9298200755) | Sep 30, 2024 |
| HP            | ProBook 450 G4              | [15151ed93a](https://linux-hardware.org/?probe=15151ed93a) | Sep 28, 2024 |
| Dell          | Latitude E6520              | [fb6b6c04d3](https://linux-hardware.org/?probe=fb6b6c04d3) | Sep 19, 2024 |
| Dell          | Latitude E6520              | [b9cef5fd04](https://linux-hardware.org/?probe=b9cef5fd04) | Sep 18, 2024 |
| Dell          | Latitude E6420              | [de841c2a57](https://linux-hardware.org/?probe=de841c2a57) | Sep 18, 2024 |
| Lenovo        | V15 G4 IRU 83A1             | [3efaeaaf18](https://linux-hardware.org/?probe=3efaeaaf18) | Sep 11, 2024 |
| TUXEDO        | InfinityBook S 15/17 Gen... | [ee2af793b2](https://linux-hardware.org/?probe=ee2af793b2) | Aug 26, 2024 |
| Lenovo        | ThinkPad E595 20NF0000GE    | [2dae2b7b29](https://linux-hardware.org/?probe=2dae2b7b29) | Aug 23, 2024 |
| HP            | EliteBook 8540w             | [37bf22daf9](https://linux-hardware.org/?probe=37bf22daf9) | Aug 16, 2024 |
| HP            | EliteBook 8540w             | [e96ce0732d](https://linux-hardware.org/?probe=e96ce0732d) | Aug 16, 2024 |
| Dell          | Latitude E6420              | [368fe1e67b](https://linux-hardware.org/?probe=368fe1e67b) | Aug 14, 2024 |
| Dell          | Precision 7740              | [eb89b3c012](https://linux-hardware.org/?probe=eb89b3c012) | Aug 13, 2024 |
| Dell          | Latitude E6420              | [c941a3c642](https://linux-hardware.org/?probe=c941a3c642) | Jul 28, 2024 |
| Toshiba       | Satellite L50-A-1D6         | [50e343f5c7](https://linux-hardware.org/?probe=50e343f5c7) | Jul 28, 2024 |
| Lenovo        | LOQ 15APH8 82XT             | [38cee88852](https://linux-hardware.org/?probe=38cee88852) | Jul 19, 2024 |
| Lenovo        | ThinkPad P14s Gen 3 21AK... | [562d547bfd](https://linux-hardware.org/?probe=562d547bfd) | Jul 16, 2024 |
| Apple         | MacBookPro12,1              | [196be66fdf](https://linux-hardware.org/?probe=196be66fdf) | Jul 14, 2024 |
| Dell          | Precision 7680              | [21073beb0d](https://linux-hardware.org/?probe=21073beb0d) | Jul 11, 2024 |
| Dell          | Precision 5550              | [812ad94331](https://linux-hardware.org/?probe=812ad94331) | Jul 02, 2024 |
| Lenovo        | V15 G4 IRU 83A1             | [8ca3fda9c6](https://linux-hardware.org/?probe=8ca3fda9c6) | Jun 26, 2024 |
| Lenovo        | V15 G4 IRU 83A1             | [2bea01f435](https://linux-hardware.org/?probe=2bea01f435) | Jun 26, 2024 |
| Lenovo        | ThinkPad P16v Gen 2 21KY... | [ae0c2aed2b](https://linux-hardware.org/?probe=ae0c2aed2b) | Jun 23, 2024 |
| Dell          | Latitude E5430 non-vPro     | [a4b4b5230e](https://linux-hardware.org/?probe=a4b4b5230e) | Jun 20, 2024 |
| Dell          | Precision 5540              | [659a2d12da](https://linux-hardware.org/?probe=659a2d12da) | May 19, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8640... | [ef4790d668](https://linux-hardware.org/?probe=ef4790d668) | May 18, 2024 |
| ASUSTek       | K55A                        | [8cbb519933](https://linux-hardware.org/?probe=8cbb519933) | May 17, 2024 |
| Lenovo        | ThinkPad T480s 20L8S8640... | [6a7aeed3b0](https://linux-hardware.org/?probe=6a7aeed3b0) | May 17, 2024 |
| HP            | Laptop 15-dy2xxx            | [8f9e16592c](https://linux-hardware.org/?probe=8f9e16592c) | Apr 16, 2024 |
| HP            | EliteBook 840 14 inch G9... | [3eb7bba175](https://linux-hardware.org/?probe=3eb7bba175) | Apr 04, 2024 |
| HP            | EliteBook 840 14 inch G9... | [fd37aa8001](https://linux-hardware.org/?probe=fd37aa8001) | Feb 27, 2024 |
| Unknown       | Unknown                     | [2d74d756b3](https://linux-hardware.org/?probe=2d74d756b3) | Jan 10, 2024 |
| Unknown       | DS16                        | [1951d37c43](https://linux-hardware.org/?probe=1951d37c43) | Jan 10, 2024 |
| Dell          | Inspiron 3501               | [7c421031f6](https://linux-hardware.org/?probe=7c421031f6) | Jan 04, 2024 |
| Lenovo        | G450 2949                   | [c8c0737175](https://linux-hardware.org/?probe=c8c0737175) | Dec 20, 2023 |
| Lenovo        | ThinkPad T430u 86147MG      | [0463c0adc2](https://linux-hardware.org/?probe=0463c0adc2) | Dec 17, 2023 |
| Dell          | Precision 5520              | [b3ea29b5a2](https://linux-hardware.org/?probe=b3ea29b5a2) | Dec 14, 2023 |
| Positivo      | Q464C                       | [47071c986c](https://linux-hardware.org/?probe=47071c986c) | Dec 11, 2023 |
| Dell          | Vostro 3420                 | [95a9c16f88](https://linux-hardware.org/?probe=95a9c16f88) | Nov 28, 2023 |
| Lenovo        | Slim 7 ProX 14ARH7 82V2     | [f36053c77c](https://linux-hardware.org/?probe=f36053c77c) | Nov 13, 2023 |
| Lenovo        | G450 2949                   | [3f631dfb6e](https://linux-hardware.org/?probe=3f631dfb6e) | Nov 04, 2023 |
| Dell          | Latitude 7490               | [4859e397e4](https://linux-hardware.org/?probe=4859e397e4) | Nov 02, 2023 |
| HP            | EliteBook 645 14 inch G1... | [eb5712ae31](https://linux-hardware.org/?probe=eb5712ae31) | Oct 28, 2023 |
| Lenovo        | IdeaPad 1 14IGL7 82V6       | [407b6f9273](https://linux-hardware.org/?probe=407b6f9273) | Oct 15, 2023 |
| HP            | EliteBook 840 G5            | [0baddc9010](https://linux-hardware.org/?probe=0baddc9010) | Oct 11, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [a607943a45](https://linux-hardware.org/?probe=a607943a45) | Oct 03, 2023 |
| HP            | EliteBook 840 G5            | [6615883de3](https://linux-hardware.org/?probe=6615883de3) | Oct 03, 2023 |
| HP            | Laptop 15s-fq1xxx           | [08fb652352](https://linux-hardware.org/?probe=08fb652352) | Sep 29, 2023 |
| Clevo         | P170EM                      | [ee87854652](https://linux-hardware.org/?probe=ee87854652) | Sep 14, 2023 |
| Apple         | MacBookPro11,4              | [ac1293fbf6](https://linux-hardware.org/?probe=ac1293fbf6) | Sep 02, 2023 |
| Apple         | MacBookPro11,4              | [1273e75666](https://linux-hardware.org/?probe=1273e75666) | Sep 02, 2023 |
| Dell          | XPS 15 9500                 | [88b6546b70](https://linux-hardware.org/?probe=88b6546b70) | Sep 01, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | [9faf6d1836](https://linux-hardware.org/?probe=9faf6d1836) | Aug 30, 2023 |
| Dell          | XPS 13 9310                 | [40802d54a7](https://linux-hardware.org/?probe=40802d54a7) | Aug 27, 2023 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | [62ca959d73](https://linux-hardware.org/?probe=62ca959d73) | Aug 21, 2023 |
| Lenovo        | ThinkPad P15s Gen 1 20T4... | [ceb8407c9a](https://linux-hardware.org/?probe=ceb8407c9a) | Aug 21, 2023 |
| HP            | Laptop 15-fc0xxx            | [fb346f4b46](https://linux-hardware.org/?probe=fb346f4b46) | Aug 15, 2023 |
| Lenovo        | ThinkPad T430 2347FF9       | [30354c1f38](https://linux-hardware.org/?probe=30354c1f38) | Jul 31, 2023 |
| HP            | ZBook 15u G5                | [1b0bb754bc](https://linux-hardware.org/?probe=1b0bb754bc) | Jul 28, 2023 |
| HP            | ZBook 15u G5                | [54684f905d](https://linux-hardware.org/?probe=54684f905d) | Jul 28, 2023 |
| Lenovo        | ThinkPad X270 20HMS79Q00    | [6a9d34223b](https://linux-hardware.org/?probe=6a9d34223b) | Jul 04, 2023 |
| ASUSTek       | G752VM                      | [b518236bd7](https://linux-hardware.org/?probe=b518236bd7) | Jun 21, 2023 |
| HP            | EliteBook 1040 14 inch G... | [47b86a7e60](https://linux-hardware.org/?probe=47b86a7e60) | Jun 14, 2023 |
| ASUSTek       | UX430UNR                    | [00ab711e0a](https://linux-hardware.org/?probe=00ab711e0a) | Jun 02, 2023 |
| HP            | ProBook 645 G1              | [f82952db4b](https://linux-hardware.org/?probe=f82952db4b) | May 14, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX517Z... | [30d9e5ca7d](https://linux-hardware.org/?probe=30d9e5ca7d) | May 11, 2023 |
| Beelink       | BT3 PRO                     | [fb99607da3](https://linux-hardware.org/?probe=fb99607da3) | May 08, 2023 |
| Acer          | Aspire E5-573G              | [5cff94f71e](https://linux-hardware.org/?probe=5cff94f71e) | May 07, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y30... | [43e6345cb8](https://linux-hardware.org/?probe=43e6345cb8) | May 03, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | [18306b3af6](https://linux-hardware.org/?probe=18306b3af6) | Apr 23, 2023 |
| HUAWEI        | KLVD-WXX9                   | [ae500cf4af](https://linux-hardware.org/?probe=ae500cf4af) | Apr 22, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | [40f92632ab](https://linux-hardware.org/?probe=40f92632ab) | Mar 16, 2023 |
| HP            | EliteBook 840 G5            | [8e02418ca7](https://linux-hardware.org/?probe=8e02418ca7) | Mar 05, 2023 |
| HP            | EliteBook 840 G5            | [5510fed545](https://linux-hardware.org/?probe=5510fed545) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G713RW_G713RW     | [5368c6d0a2](https://linux-hardware.org/?probe=5368c6d0a2) | Feb 23, 2023 |
| Lenovo        | ThinkPad T480 20L6S8B500    | [b4cbe5bf11](https://linux-hardware.org/?probe=b4cbe5bf11) | Feb 16, 2023 |
| Lenovo        | IdeaPad S210 Touch 20257    | [d132553080](https://linux-hardware.org/?probe=d132553080) | Feb 13, 2023 |
| Dell          | Latitude 5420               | [60cc86374d](https://linux-hardware.org/?probe=60cc86374d) | Feb 12, 2023 |
| Dell          | Latitude 5420               | [63a576e744](https://linux-hardware.org/?probe=63a576e744) | Feb 12, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [e07858d71e](https://linux-hardware.org/?probe=e07858d71e) | Feb 03, 2023 |
| Positivo      | Mobile                      | [966b4e2454](https://linux-hardware.org/?probe=966b4e2454) | Feb 02, 2023 |
| Dell          | Inspiron 15-3573            | [b735bbde51](https://linux-hardware.org/?probe=b735bbde51) | Jan 29, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TH00... | [06f87714b0](https://linux-hardware.org/?probe=06f87714b0) | Jan 26, 2023 |
| Dell          | Precision M6800             | [bcd98b78c4](https://linux-hardware.org/?probe=bcd98b78c4) | Jan 19, 2023 |
| Dell          | Latitude 5420               | [cb511c0f82](https://linux-hardware.org/?probe=cb511c0f82) | Jan 18, 2023 |
| HP            | Laptop 15-dy2xxx            | [ff9464407f](https://linux-hardware.org/?probe=ff9464407f) | Jan 15, 2023 |
| HUAWEI        | KLVD-WXX9                   | [71d684a605](https://linux-hardware.org/?probe=71d684a605) | Jan 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | [d6cac381fd](https://linux-hardware.org/?probe=d6cac381fd) | Jan 09, 2023 |
| HUAWEI        | KLVD-WXX9                   | [e662d0e58a](https://linux-hardware.org/?probe=e662d0e58a) | Jan 07, 2023 |
| Dell          | XPS 17 9720                 | [ae26f02480](https://linux-hardware.org/?probe=ae26f02480) | Jan 03, 2023 |
| HP            | EliteBook 845 14 inch G9... | [65c34944ec](https://linux-hardware.org/?probe=65c34944ec) | Jan 03, 2023 |
| HP            | EliteBook 2560p             | [89c0ffe36d](https://linux-hardware.org/?probe=89c0ffe36d) | Dec 29, 2022 |
| Dell          | Inspiron 14 5425            | [42f45d59d2](https://linux-hardware.org/?probe=42f45d59d2) | Dec 29, 2022 |
| HP            | ProBook 640 G3              | [03eba7b664](https://linux-hardware.org/?probe=03eba7b664) | Dec 15, 2022 |
| Lenovo        | ThinkPad T14s Gen 3 21BR... | [ede2606ad1](https://linux-hardware.org/?probe=ede2606ad1) | Dec 15, 2022 |
| Dell          | Vostro 3500                 | [db276a4d2e](https://linux-hardware.org/?probe=db276a4d2e) | Nov 28, 2022 |
| Lenovo        | ThinkPad P1 Gen 3 20THCT... | [4c47d0ef97](https://linux-hardware.org/?probe=4c47d0ef97) | Nov 05, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | [cda3087aaf](https://linux-hardware.org/?probe=cda3087aaf) | Oct 23, 2022 |
| HP            | Pavilion g6                 | [11d25577b3](https://linux-hardware.org/?probe=11d25577b3) | Oct 08, 2022 |
| BANGHO        | BES G1529                   | [ce0db88361](https://linux-hardware.org/?probe=ce0db88361) | Sep 20, 2022 |
| Dell          | XPS 15 7590                 | [a191bd2a9f](https://linux-hardware.org/?probe=a191bd2a9f) | Sep 18, 2022 |
| Dell          | Latitude 5430               | [617563f7a7](https://linux-hardware.org/?probe=617563f7a7) | Sep 14, 2022 |
| HP            | ZBook 15u G6                | [af658eb920](https://linux-hardware.org/?probe=af658eb920) | Sep 06, 2022 |
| HP            | ZBook 15 G2                 | [34f32c0d0d](https://linux-hardware.org/?probe=34f32c0d0d) | Jul 27, 2022 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | [ce5ca74472](https://linux-hardware.org/?probe=ce5ca74472) | Jul 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon 34483... | [fa20ff88e1](https://linux-hardware.org/?probe=fa20ff88e1) | Jun 19, 2022 |
| Dell          | Latitude 3420               | [b10330b427](https://linux-hardware.org/?probe=b10330b427) | Jun 15, 2022 |
| HP            | EliteBook 840 G7 Noteboo... | [b586e45245](https://linux-hardware.org/?probe=b586e45245) | Apr 25, 2022 |
| Dell          | Latitude 5500               | [3d87bc42c6](https://linux-hardware.org/?probe=3d87bc42c6) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [f78b6db0bd](https://linux-hardware.org/?probe=f78b6db0bd) | Mar 08, 2022 |
| Dell          | Latitude 5500               | [fc0c5280d7](https://linux-hardware.org/?probe=fc0c5280d7) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [351e05ccc8](https://linux-hardware.org/?probe=351e05ccc8) | Mar 08, 2022 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | [dc09f11788](https://linux-hardware.org/?probe=dc09f11788) | Mar 08, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | [2ab4cacc1e](https://linux-hardware.org/?probe=2ab4cacc1e) | Jan 26, 2022 |
| Lenovo        | Legion Y7000 2020H 81Y7     | [787aec5f1c](https://linux-hardware.org/?probe=787aec5f1c) | Jan 26, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | [7225108b91](https://linux-hardware.org/?probe=7225108b91) | Jan 10, 2022 |
| HP            | ZBook 15 G3                 | [89809f906e](https://linux-hardware.org/?probe=89809f906e) | Jan 10, 2022 |
| Lenovo        | Legion 5 15ARH05H 82B1      | [90821cb3a5](https://linux-hardware.org/?probe=90821cb3a5) | Jan 03, 2022 |
| Lenovo        | IdeaPad 500S-14ISK 80Q3     | [6ea0cdba08](https://linux-hardware.org/?probe=6ea0cdba08) | Nov 27, 2021 |
| Lenovo        | ThinkPad W540 20BGCTO1WW    | [25055cdc26](https://linux-hardware.org/?probe=25055cdc26) | Nov 23, 2021 |
| HP            | Laptop 17-ca1xxx            | [61fe4e654d](https://linux-hardware.org/?probe=61fe4e654d) | Nov 09, 2021 |
| Toshiba       | TECRA W50-A                 | [abee9f36ad](https://linux-hardware.org/?probe=abee9f36ad) | Nov 05, 2021 |
| Lenovo        | ThinkPad T420 42365H1       | [3430adab89](https://linux-hardware.org/?probe=3430adab89) | Aug 25, 2021 |
| Lenovo        | ThinkPad T420 42365H1       | [6a306e2253](https://linux-hardware.org/?probe=6a306e2253) | Aug 16, 2021 |
| Lenovo        | ThinkPad W500 406132G       | [e79080e90d](https://linux-hardware.org/?probe=e79080e90d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [860ec3c89d](https://linux-hardware.org/?probe=860ec3c89d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Y410P 20216         | [b2df1c0e6d](https://linux-hardware.org/?probe=b2df1c0e6d) | Aug 08, 2021 |
| Lenovo        | IdeaPad Y410P 20216         | [3fc207c5b9](https://linux-hardware.org/?probe=3fc207c5b9) | Aug 07, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [09738de946](https://linux-hardware.org/?probe=09738de946) | Jul 04, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | [741cab87e1](https://linux-hardware.org/?probe=741cab87e1) | Jun 29, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | [60fe7f2653](https://linux-hardware.org/?probe=60fe7f2653) | Jun 13, 2021 |
| Toshiba       | Satellite E45-B             | [84683df1f0](https://linux-hardware.org/?probe=84683df1f0) | Jun 12, 2021 |
| Acer          | Aspire VN7-591G             | [bc9e6c4910](https://linux-hardware.org/?probe=bc9e6c4910) | May 10, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| Rocky Linux 9.4  | 26        | 17.57%  |
| Rocky Linux 9.1  | 22        | 14.86%  |
| Rocky Linux 9.5  | 17        | 11.49%  |
| Rocky Linux 9.2  | 14        | 9.46%   |
| Rocky Linux 8.5  | 11        | 7.43%   |
| Rocky Linux 9.0  | 9         | 6.08%   |
| Rocky Linux 10.0 | 9         | 6.08%   |
| Rocky Linux 9.3  | 8         | 5.41%   |
| Rocky Linux 8.4  | 8         | 5.41%   |
| Rocky Linux 8.8  | 7         | 4.73%   |
| Rocky Linux 8.10 | 5         | 3.38%   |
| Rocky Linux 9.6  | 4         | 2.7%    |
| Rocky Linux 8.7  | 3         | 2.03%   |
| Rocky Linux 8.9  | 2         | 1.35%   |
| Rocky Linux 8.6  | 1         | 0.68%   |
| Rocky Linux 8.3  | 1         | 0.68%   |
| Rocky Linux 10.1 | 1         | 0.68%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name        | Notebooks | Percent |
|-------------|-----------|---------|
| Rocky Linux | 145       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                          | Notebooks | Percent |
|----------------------------------|-----------|---------|
| 5.14.0-162.6.1.el9_1.0.1.x86_64  | 9         | 5.73%   |
| 5.14.0-427.13.1.el9_4.x86_64     | 6         | 3.82%   |
| 5.14.0-284.25.1.el9_2.x86_64     | 5         | 3.18%   |
| 5.14.0-70.22.1.el9_0.x86_64      | 4         | 2.55%   |
| 5.14.0-427.42.1.el9_4.x86_64     | 4         | 2.55%   |
| 5.14.0-362.8.1.el9_3.x86_64      | 4         | 2.55%   |
| 5.14.0-284.30.1.el9_2.x86_64     | 4         | 2.55%   |
| 5.14.0-284.18.1.el9_2.x86_64     | 4         | 2.55%   |
| 5.14.0-162.23.1.el9_1.x86_64     | 4         | 2.55%   |
| 5.14.0-162.12.1.el9_1.0.2.x86_64 | 4         | 2.55%   |
| 5.14.0-503.40.1.el9_5.x86_64     | 3         | 1.91%   |
| 5.14.0-503.21.1.el9_5.x86_64     | 3         | 1.91%   |
| 5.14.0-503.19.1.el9_5.x86_64     | 3         | 1.91%   |
| 5.14.0-427.37.1.el9_4.x86_64     | 3         | 1.91%   |
| 5.14.0-427.31.1.el9_4.x86_64     | 3         | 1.91%   |
| 5.14.0-162.18.1.el9_1.x86_64     | 3         | 1.91%   |
| 4.18.0-477.27.1.el8_8.x86_64     | 3         | 1.91%   |
| 4.18.0-348.7.1.el8_5.x86_64      | 3         | 1.91%   |
| 6.12.0-55.21.1.el10_0.x86_64     | 2         | 1.27%   |
| 6.12.0-55.18.1.el10_0.x86_64     | 2         | 1.27%   |
| 6.1.64-2.el9.x86_64              | 2         | 1.27%   |
| 5.14.0-70.26.1.el9_0.x86_64      | 2         | 1.27%   |
| 5.14.0-570.18.1.el9_6.x86_64     | 2         | 1.27%   |
| 5.14.0-503.16.1.el9_5.x86_64     | 2         | 1.27%   |
| 5.14.0-503.15.1.el9_5.x86_64     | 2         | 1.27%   |
| 5.14.0-427.40.1.el9_4.x86_64     | 2         | 1.27%   |
| 5.14.0-427.35.1.el9_4.x86_64     | 2         | 1.27%   |
| 5.14.0-427.24.1.el9_4.x86_64     | 2         | 1.27%   |
| 5.14.0-427.20.1.el9_4.0.1.x86_64 | 2         | 1.27%   |
| 5.14.0-162.6.1.el9_1.x86_64      | 2         | 1.27%   |
| 4.18.0-553.8.1.el8_10.x86_64     | 2         | 1.27%   |
| 4.18.0-513.9.1.el8_9.x86_64      | 2         | 1.27%   |
| 4.18.0-477.13.1.el8_8.x86_64     | 2         | 1.27%   |
| 4.18.0-425.3.1.el8.x86_64        | 2         | 1.27%   |
| 4.18.0-348.20.1.el8_5.x86_64     | 2         | 1.27%   |
| 4.18.0-348.12.2.el8_5.x86_64     | 2         | 1.27%   |
| 4.18.0-305.el8.x86_64            | 2         | 1.27%   |
| 4.18.0-305.3.1.el8_4.x86_64      | 2         | 1.27%   |
| 4.18.0-305.25.1.el8_4.x86_64     | 2         | 1.27%   |
| 4.18.0-305.10.2.el8_4.x86_64     | 2         | 1.27%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14.0  | 95        | 64.63%  |
| 4.18.0  | 32        | 21.77%  |
| 6.12.0  | 10        | 6.8%    |
| 6.1.64  | 2         | 1.36%   |
| 6.8.3   | 1         | 0.68%   |
| 6.4.12  | 1         | 0.68%   |
| 6.2.12  | 1         | 0.68%   |
| 6.2.10  | 1         | 0.68%   |
| 6.10.4  | 1         | 0.68%   |
| 5.4.157 | 1         | 0.68%   |
| 5.16.15 | 1         | 0.68%   |
| 5.10.89 | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.14    | 95        | 64.63%  |
| 4.18    | 32        | 21.77%  |
| 6.12    | 10        | 6.8%    |
| 6.2     | 2         | 1.36%   |
| 6.1     | 2         | 1.36%   |
| 6.8     | 1         | 0.68%   |
| 6.4     | 1         | 0.68%   |
| 6.10    | 1         | 0.68%   |
| 5.4     | 1         | 0.68%   |
| 5.16    | 1         | 0.68%   |
| 5.10    | 1         | 0.68%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 145       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Notebooks | Percent |
|---------------|-----------|---------|
| GNOME         | 94        | 64.83%  |
| KDE5          | 22        | 15.17%  |
| MATE          | 8         | 5.52%   |
| XFCE          | 5         | 3.45%   |
| X-Cinnamon    | 5         | 3.45%   |
| Unknown       | 4         | 2.76%   |
| KDE6          | 3         | 2.07%   |
| GNOME Classic | 3         | 2.07%   |
| Cinnamon      | 1         | 0.69%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Wayland | 98        | 66.67%  |
| X11     | 45        | 30.61%  |
| Tty     | 2         | 1.36%   |
| Web     | 1         | 0.68%   |
| Unknown | 1         | 0.68%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 48.97%  |
| GDM     | 49        | 33.79%  |
| SDDM    | 13        | 8.97%   |
| LightDM | 12        | 8.28%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Notebooks | Percent |
|-------|-----------|---------|
| en_US | 94        | 64.83%  |
| en_GB | 6         | 4.14%   |
| de_DE | 5         | 3.45%   |
| it_IT | 4         | 2.76%   |
| ru_RU | 3         | 2.07%   |
| pt_BR | 3         | 2.07%   |
| fr_FR | 3         | 2.07%   |
| en_CA | 3         | 2.07%   |
| en_AU | 3         | 2.07%   |
| C     | 3         | 2.07%   |
| es_ES | 2         | 1.38%   |
| en_ZA | 2         | 1.38%   |
| en_IE | 2         | 1.38%   |
| cs_CZ | 2         | 1.38%   |
| ca_ES | 2         | 1.38%   |
| zh_TW | 1         | 0.69%   |
| zh_CN | 1         | 0.69%   |
| pt_PT | 1         | 0.69%   |
| pl_PL | 1         | 0.69%   |
| ja_JP | 1         | 0.69%   |
| fr_CA | 1         | 0.69%   |
| es_CR | 1         | 0.69%   |
| en_NZ | 1         | 0.69%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 110       | 75.34%  |
| BIOS | 36        | 24.66%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Notebooks | Percent |
|-------|-----------|---------|
| Xfs   | 125       | 86.21%  |
| Ext4  | 16        | 11.03%  |
| Tmpfs | 3         | 2.07%   |
| Ext3  | 1         | 0.69%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 68        | 46.9%   |
| Unknown | 68        | 46.9%   |
| MBR     | 9         | 6.21%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 131       | 90.34%  |
| Yes       | 14        | 9.66%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 118       | 81.38%  |
| Yes       | 27        | 18.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Notebooks | Percent |
|---------------------|-----------|---------|
| Lenovo              | 44        | 30.34%  |
| Dell                | 31        | 21.38%  |
| Hewlett-Packard     | 28        | 19.31%  |
| ASUSTek Computer    | 13        | 8.97%   |
| Acer                | 5         | 3.45%   |
| Toshiba             | 3         | 2.07%   |
| Unknown             | 3         | 2.07%   |
| Positivo            | 2         | 1.38%   |
| Gigabyte Technology | 2         | 1.38%   |
| Apple               | 2         | 1.38%   |
| Alienware           | 2         | 1.38%   |
| TUXEDO              | 1         | 0.69%   |
| Sony                | 1         | 0.69%   |
| PC Specialist       | 1         | 0.69%   |
| ILLEGEAR            | 1         | 0.69%   |
| HUAWEI              | 1         | 0.69%   |
| Fujitsu             | 1         | 0.69%   |
| Firebat Computer    | 1         | 0.69%   |
| Clevo               | 1         | 0.69%   |
| Beelink             | 1         | 0.69%   |
| BANGHO              | 1         | 0.69%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Notebooks | Percent |
|------------------------------------------|-----------|---------|
| Unknown                                  | 3         | 2.07%   |
| HP Laptop 15-dy2xxx                      | 2         | 1.38%   |
| HP EliteBook 840 G5                      | 2         | 1.38%   |
| Dell Precision 7530                      | 2         | 1.38%   |
| Dell Latitude E6520                      | 2         | 1.38%   |
| TUXEDO InfinityBook S 15/17 Gen7         | 1         | 0.69%   |
| Toshiba TECRA W50-A                      | 1         | 0.69%   |
| Toshiba Satellite L50-A-1D6              | 1         | 0.69%   |
| Toshiba Satellite E45-B                  | 1         | 0.69%   |
| Sony VPCF237FJ                           | 1         | 0.69%   |
| Positivo Q464C                           | 1         | 0.69%   |
| Positivo Mobile                          | 1         | 0.69%   |
| PC Specialist PA70Hx                     | 1         | 0.69%   |
| Lenovo Yoga 3 14 80JH                    | 1         | 0.69%   |
| Lenovo V15 G4 IRU 83A1                   | 1         | 0.69%   |
| Lenovo ThinkPad X270 20HMS79Q00          | 1         | 0.69%   |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1V900 | 1         | 0.69%   |
| Lenovo ThinkPad X1 Carbon 344835U        | 1         | 0.69%   |
| Lenovo ThinkPad W540 20BGCTO1WW          | 1         | 0.69%   |
| Lenovo ThinkPad W500 406132G             | 1         | 0.69%   |
| Lenovo ThinkPad T480s 20L8S86400         | 1         | 0.69%   |
| Lenovo ThinkPad T480 20L6S8B500          | 1         | 0.69%   |
| Lenovo ThinkPad T460 20FMS0K624          | 1         | 0.69%   |
| Lenovo ThinkPad T430u 86147MG            | 1         | 0.69%   |
| Lenovo ThinkPad T430 2347FF9             | 1         | 0.69%   |
| Lenovo ThinkPad T420 42365H1             | 1         | 0.69%   |
| Lenovo ThinkPad T14s Gen 3 21BR000QUS    | 1         | 0.69%   |
| Lenovo ThinkPad T14s Gen 2a 20XF006XCK   | 1         | 0.69%   |
| Lenovo ThinkPad T14 Gen 3 21AH00HXGE     | 1         | 0.69%   |
| Lenovo ThinkPad P53 20QNS00X00           | 1         | 0.69%   |
| Lenovo ThinkPad P16v Gen 2 21KYS0LG00    | 1         | 0.69%   |
| Lenovo ThinkPad P15v Gen 3 21D8003QGE    | 1         | 0.69%   |
| Lenovo ThinkPad P15s Gen 1 20T4CTO1WW    | 1         | 0.69%   |
| Lenovo ThinkPad P14s Gen 3 21AK0043US    | 1         | 0.69%   |
| Lenovo ThinkPad P1 Gen 4i 20Y3000FHV     | 1         | 0.69%   |
| Lenovo ThinkPad P1 Gen 3 20THCTO1WW      | 1         | 0.69%   |
| Lenovo ThinkPad P1 Gen 3 20TH004CUK      | 1         | 0.69%   |
| Lenovo ThinkPad E595 20NF0000GE          | 1         | 0.69%   |
| Lenovo ThinkPad E14 Gen 4 21E300ESPB     | 1         | 0.69%   |
| Lenovo ThinkPad E14 20RBS20600           | 1         | 0.69%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo ThinkPad      | 26        | 17.93%  |
| Dell Latitude        | 10        | 6.9%    |
| Lenovo IdeaPad       | 9         | 6.21%   |
| HP EliteBook         | 8         | 5.52%   |
| Dell Precision       | 8         | 5.52%   |
| HP Laptop            | 6         | 4.14%   |
| HP ProBook           | 5         | 3.45%   |
| Dell XPS             | 5         | 3.45%   |
| Acer Aspire          | 5         | 3.45%   |
| Lenovo Legion        | 4         | 2.76%   |
| HP ZBook             | 4         | 2.76%   |
| Dell Inspiron        | 4         | 2.76%   |
| Dell Vostro          | 3         | 2.07%   |
| ASUS ASUS            | 3         | 2.07%   |
| Unknown              | 3         | 2.07%   |
| Toshiba Satellite    | 2         | 1.38%   |
| HP OMEN              | 2         | 1.38%   |
| Gigabyte AORUS       | 2         | 1.38%   |
| ASUS VivoBook        | 2         | 1.38%   |
| ASUS ROG             | 2         | 1.38%   |
| TUXEDO InfinityBook  | 1         | 0.69%   |
| Toshiba TECRA        | 1         | 0.69%   |
| Sony VPCF237FJ       | 1         | 0.69%   |
| Positivo Q464C       | 1         | 0.69%   |
| Positivo Mobile      | 1         | 0.69%   |
| PC Specialist PA70Hx | 1         | 0.69%   |
| Lenovo Yoga          | 1         | 0.69%   |
| Lenovo V15           | 1         | 0.69%   |
| Lenovo Slim          | 1         | 0.69%   |
| Lenovo LOQ           | 1         | 0.69%   |
| Lenovo G450          | 1         | 0.69%   |
| ILLEGEAR RAVEN       | 1         | 0.69%   |
| HUAWEI KLVD-WXX9     | 1         | 0.69%   |
| HP Pavilion          | 1         | 0.69%   |
| HP Elite             | 1         | 0.69%   |
| HP 240               | 1         | 0.69%   |
| Fujitsu LIFEBOOK     | 1         | 0.69%   |
| Firebat T7-6R        | 1         | 0.69%   |
| Dell Studio          | 1         | 0.69%   |
| Clevo P170EM         | 1         | 0.69%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2022 | 19        | 13.1%   |
| 2020 | 17        | 11.72%  |
| 2019 | 17        | 11.72%  |
| 2021 | 13        | 8.97%   |
| 2018 | 12        | 8.28%   |
| 2017 | 9         | 6.21%   |
| 2015 | 9         | 6.21%   |
| 2023 | 8         | 5.52%   |
| 2014 | 7         | 4.83%   |
| 2012 | 7         | 4.83%   |
| 2011 | 7         | 4.83%   |
| 2016 | 6         | 4.14%   |
| 2010 | 5         | 3.45%   |
| 2013 | 4         | 2.76%   |
| 2024 | 3         | 2.07%   |
| 2009 | 2         | 1.38%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 145       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 121       | 82.88%  |
| Enabled  | 25        | 17.12%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 145       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Notebooks | Percent |
|-------------|-----------|---------|
| 8.01-16.0   | 44        | 30.34%  |
| 4.01-8.0    | 40        | 27.59%  |
| 32.01-64.0  | 27        | 18.62%  |
| 64.01-256.0 | 9         | 6.21%   |
| 16.01-24.0  | 9         | 6.21%   |
| 3.01-4.0    | 8         | 5.52%   |
| 24.01-32.0  | 8         | 5.52%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 51        | 32.48%  |
| 2.01-3.0   | 37        | 23.57%  |
| 3.01-4.0   | 33        | 21.02%  |
| 1.01-2.0   | 16        | 10.19%  |
| 8.01-16.0  | 15        | 9.55%   |
| 0.51-1.0   | 3         | 1.91%   |
| 24.01-32.0 | 1         | 0.64%   |
| 16.01-24.0 | 1         | 0.64%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 109       | 74.66%  |
| 2      | 24        | 16.44%  |
| 3      | 9         | 6.16%   |
| 4      | 3         | 2.05%   |
| 0      | 1         | 0.68%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 120       | 82.76%  |
| Yes       | 25        | 17.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 124       | 84.35%  |
| No        | 23        | 15.65%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 134       | 92.41%  |
| No        | 11        | 7.59%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 126       | 86.9%   |
| No        | 19        | 13.1%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Notebooks | Percent |
|--------------|-----------|---------|
| USA          | 44        | 30.34%  |
| Germany      | 7         | 4.83%   |
| UK           | 6         | 4.14%   |
| Italy        | 6         | 4.14%   |
| Russia       | 5         | 3.45%   |
| Spain        | 4         | 2.76%   |
| South Africa | 4         | 2.76%   |
| Poland       | 4         | 2.76%   |
| France       | 4         | 2.76%   |
| Czechia      | 4         | 2.76%   |
| Canada       | 4         | 2.76%   |
| Brazil       | 4         | 2.76%   |
| Australia    | 3         | 2.07%   |
| Turkey       | 2         | 1.38%   |
| Sweden       | 2         | 1.38%   |
| Portugal     | 2         | 1.38%   |
| Pakistan     | 2         | 1.38%   |
| Netherlands  | 2         | 1.38%   |
| Malaysia     | 2         | 1.38%   |
| Ireland      | 2         | 1.38%   |
| Indonesia    | 2         | 1.38%   |
| Hungary      | 2         | 1.38%   |
| China        | 2         | 1.38%   |
| Belgium      | 2         | 1.38%   |
| Argentina    | 2         | 1.38%   |
| Venezuela    | 1         | 0.69%   |
| Uzbekistan   | 1         | 0.69%   |
| UAE          | 1         | 0.69%   |
| Taiwan       | 1         | 0.69%   |
| Slovakia     | 1         | 0.69%   |
| Saudi Arabia | 1         | 0.69%   |
| Romania      | 1         | 0.69%   |
| Norway       | 1         | 0.69%   |
| New Zealand  | 1         | 0.69%   |
| Namibia      | 1         | 0.69%   |
| Myanmar      | 1         | 0.69%   |
| Mexico       | 1         | 0.69%   |
| Kenya        | 1         | 0.69%   |
| Kazakhstan   | 1         | 0.69%   |
| Japan        | 1         | 0.69%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City           | Notebooks | Percent |
|----------------|-----------|---------|
| Rancho Cordova | 3         | 2.01%   |
| Prague         | 3         | 2.01%   |
| Philadelphia   | 2         | 1.34%   |
| Moscow         | 2         | 1.34%   |
| Melun          | 2         | 1.34%   |
| Lisbon         | 2         | 1.34%   |
| Enschede       | 2         | 1.34%   |
| Budapest       | 2         | 1.34%   |
| Boise          | 2         | 1.34%   |
| Bekasi         | 2         | 1.34%   |
| Barcelona      | 2         | 1.34%   |
| Albuquerque    | 2         | 1.34%   |
| Žilina        | 1         | 0.67%   |
| Yangon         | 1         | 0.67%   |
| Xi'an          | 1         | 0.67%   |
| Woking         | 1         | 0.67%   |
| Windhoek       | 1         | 0.67%   |
| Weymouth       | 1         | 0.67%   |
| Westerville    | 1         | 0.67%   |
| Watertown      | 1         | 0.67%   |
| Walnut Creek   | 1         | 0.67%   |
| Viggiù        | 1         | 0.67%   |
| Vienna         | 1         | 0.67%   |
| Valongo        | 1         | 0.67%   |
| Valencia       | 1         | 0.67%   |
| Troisdorf      | 1         | 0.67%   |
| Tricesimo      | 1         | 0.67%   |
| Tours          | 1         | 0.67%   |
| Torrington     | 1         | 0.67%   |
| Toronto        | 1         | 0.67%   |
| Tel Aviv       | 1         | 0.67%   |
| Taoyuan City   | 1         | 0.67%   |
| Syracuse       | 1         | 0.67%   |
| Svalöv        | 1         | 0.67%   |
| Springfield    | 1         | 0.67%   |
| Spokane        | 1         | 0.67%   |
| Split          | 1         | 0.67%   |
| Sofia          | 1         | 0.67%   |
| Smolensk       | 1         | 0.67%   |
| Shanghai       | 1         | 0.67%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Notebooks | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 38        | 44     | 20.54%  |
| Micron Technology            | 16        | 19     | 8.65%   |
| Sandisk                      | 15        | 18     | 8.11%   |
| Toshiba                      | 11        | 12     | 5.95%   |
| WDC                          | 10        | 10     | 5.41%   |
| Seagate                      | 10        | 13     | 5.41%   |
| SK hynix                     | 8         | 13     | 4.32%   |
| Kingston                     | 8         | 10     | 4.32%   |
| Unknown                      | 7         | 7      | 3.78%   |
| Intel                        | 7         | 7      | 3.78%   |
| Crucial                      | 6         | 7      | 3.24%   |
| Micron/Crucial Technology    | 5         | 6      | 2.7%    |
| KIOXIA                       | 3         | 3      | 1.62%   |
| Union Memory (Shenzhen)      | 2         | 4      | 1.08%   |
| Shenzhen Longsys Electronics | 2         | 5      | 1.08%   |
| Phison Electronics           | 2         | 2      | 1.08%   |
| LITEON                       | 2         | 2      | 1.08%   |
| Lexar                        | 2         | 2      | 1.08%   |
| Dogfish                      | 2         | 2      | 1.08%   |
| A-DATA Technology            | 2         | 2      | 1.08%   |
| Unknown                      | 2         | 2      | 1.08%   |
| Yangtze Memory Technologies  | 1         | 1      | 0.54%   |
| Union Memory                 | 1         | 1      | 0.54%   |
| UMIS                         | 1         | 1      | 0.54%   |
| TO Exter                     | 1         | 1      | 0.54%   |
| StoreJet                     | 1         | 1      | 0.54%   |
| SSK                          | 1         | 1      | 0.54%   |
| Rogueware                    | 1         | 1      | 0.54%   |
| Realtek Semiconductor        | 1         | 1      | 0.54%   |
| PNY                          | 1         | 2      | 0.54%   |
| Phison                       | 1         | 2      | 0.54%   |
| Patriot                      | 1         | 1      | 0.54%   |
| MKNSSDRW                     | 1         | 1      | 0.54%   |
| LITEONIT                     | 1         | 1      | 0.54%   |
| JMicron Technology           | 1         | 1      | 0.54%   |
| INDMEM                       | 1         | 1      | 0.54%   |
| HS-SSD-C100                  | 1         | 1      | 0.54%   |
| Hitachi                      | 1         | 1      | 0.54%   |
| HGST HTS                     | 1         | 1      | 0.54%   |
| HGST                         | 1         | 1      | 0.54%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                | Notebooks | Percent |
|------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB    | 7         | 3.61%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB   | 5         | 2.58%   |
| Micron/Crucial P2 NVMe PCIe SSD 2TB                  | 4         | 2.06%   |
| Unknown MMC Card  64GB                               | 3         | 1.55%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 500GB     | 3         | 1.55%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 1024GB | 3         | 1.55%   |
| Toshiba MQ01ABD100 1TB                               | 2         | 1.03%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                   | 2         | 1.03%   |
| Samsung SSD 870 EVO 1TB                              | 2         | 1.03%   |
| Samsung MZALQ512HALU-000L1 512GB                     | 2         | 1.03%   |
| Lexar 512GB SSD                                      | 2         | 1.03%   |
| Kingston SV300S37A120G 120GB SSD                     | 2         | 1.03%   |
| Kingston SA400S37240G 240GB SSD                      | 2         | 1.03%   |
| Crucial CT500MX500SSD1 500GB                         | 2         | 1.03%   |
| Crucial CT1000MX500SSD1 1TB                          | 2         | 1.03%   |
| Unknown                                              | 2         | 1.03%   |
| Yangtze Memory ZHITAI Ti600 2TB                      | 1         | 0.52%   |
| WDC WDS480G2G0A-00JH30 480GB SSD                     | 1         | 0.52%   |
| WDC WDBNCE0010PNC 1TB SSD                            | 1         | 0.52%   |
| WDC WD5000LPCX-24C6HT0 500GB                         | 1         | 0.52%   |
| WDC WD5000BPVT-00A1YT0 500GB                         | 1         | 0.52%   |
| WDC WD40 EFRX-68N32N0 4TB                            | 1         | 0.52%   |
| WDC WD1600BEVT-08A23T1 160GB                         | 1         | 0.52%   |
| WDC WD10SPCX-24HWST1 1TB                             | 1         | 0.52%   |
| WDC WD10JPVX-60JC3T1 1TB                             | 1         | 0.52%   |
| WDC WD10JPVX-22JC3T0 1TB                             | 1         | 0.52%   |
| WDC WD Blue SA510 M.2 2280 1000GB                    | 1         | 0.52%   |
| Unknown SD/MMC/MS PRO 2GB                            | 1         | 0.52%   |
| Unknown S0J38Y  64GB                                 | 1         | 0.52%   |
| Unknown MMC Card  16GB                               | 1         | 0.52%   |
| Unknown MMC Card  128GB                              | 1         | 0.52%   |
| Union Memory UMIS RPJTJ128MEE1MWX 128GB              | 1         | 0.52%   |
| Union Memory (Shenzhen) UMIS RPJTJ512MKP1QDY 512GB   | 1         | 0.52%   |
| Union Memory (Shenzhen) NVMe SSD Drive 128GB         | 1         | 0.52%   |
| UMIS RPFTJ128PDD2EWX 128GB                           | 1         | 0.52%   |
| Toshiba XG4 NVMe SSD Controller 256GB                | 1         | 0.52%   |
| Toshiba THNSNJ512GACU 512GB SSD                      | 1         | 0.52%   |
| Toshiba THNSNJ128G8NU 128GB SSD                      | 1         | 0.52%   |
| Toshiba NVMe SSD Drive 512GB                         | 1         | 0.52%   |
| Toshiba MQ02ABF050H 500GB                            | 1         | 0.52%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor   | Notebooks | Drives | Percent |
|----------|-----------|--------|---------|
| Seagate  | 10        | 13     | 33.33%  |
| WDC      | 7         | 7      | 23.33%  |
| Toshiba  | 5         | 5      | 16.67%  |
| Unknown  | 1         | 1      | 3.33%   |
| TO Exter | 1         | 1      | 3.33%   |
| StoreJet | 1         | 1      | 3.33%   |
| Hitachi  | 1         | 1      | 3.33%   |
| HGST HTS | 1         | 1      | 3.33%   |
| HGST     | 1         | 1      | 3.33%   |
| Fujitsu  | 1         | 1      | 3.33%   |
| ASMT     | 1         | 1      | 3.33%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 12     | 21.15%  |
| Kingston            | 6         | 8      | 11.54%  |
| Crucial             | 6         | 7      | 11.54%  |
| SanDisk             | 5         | 6      | 9.62%   |
| WDC                 | 3         | 3      | 5.77%   |
| Micron Technology   | 3         | 3      | 5.77%   |
| Toshiba             | 2         | 2      | 3.85%   |
| LITEON              | 2         | 2      | 3.85%   |
| Dogfish             | 2         | 2      | 3.85%   |
| Unknown             | 2         | 2      | 3.85%   |
| Rogueware           | 1         | 1      | 1.92%   |
| PNY                 | 1         | 2      | 1.92%   |
| Patriot             | 1         | 1      | 1.92%   |
| LITEONIT            | 1         | 1      | 1.92%   |
| Lexar               | 1         | 1      | 1.92%   |
| Intel               | 1         | 1      | 1.92%   |
| INDMEM              | 1         | 1      | 1.92%   |
| EAGET               | 1         | 1      | 1.92%   |
| Apple               | 1         | 1      | 1.92%   |
| A-DATA Technology   | 1         | 1      | 1.92%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 86        | 116    | 50.89%  |
| SSD     | 46        | 58     | 27.22%  |
| HDD     | 27        | 33     | 15.98%  |
| MMC     | 6         | 6      | 3.55%   |
| Unknown | 4         | 4      | 2.37%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 86        | 115    | 51.5%   |
| SATA | 64        | 84     | 38.32%  |
| SAS  | 11        | 12     | 6.59%   |
| MMC  | 6         | 6      | 3.59%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 40        | 51     | 54.05%  |
| 0.51-1.0   | 25        | 30     | 33.78%  |
| 1.01-2.0   | 6         | 6      | 8.11%   |
| 3.01-4.0   | 2         | 3      | 2.7%    |
| 4.01-10.0  | 1         | 1      | 1.35%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Notebooks | Percent |
|----------------|-----------|---------|
| 251-500        | 44        | 30.14%  |
| 101-250        | 40        | 27.4%   |
| 501-1000       | 25        | 17.12%  |
| 1001-2000      | 11        | 7.53%   |
| More than 3000 | 6         | 4.11%   |
| 1-20           | 6         | 4.11%   |
| 51-100         | 6         | 4.11%   |
| 2001-3000      | 5         | 3.42%   |
| 21-50          | 2         | 1.37%   |
| Unknown        | 1         | 0.68%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Notebooks | Percent |
|----------------|-----------|---------|
| 1-20           | 51        | 34.23%  |
| 21-50          | 36        | 24.16%  |
| 101-250        | 24        | 16.11%  |
| 51-100         | 19        | 12.75%  |
| 251-500        | 8         | 5.37%   |
| 1001-2000      | 6         | 4.03%   |
| More than 3000 | 2         | 1.34%   |
| 501-1000       | 2         | 1.34%   |
| Unknown        | 1         | 0.67%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                                     | Notebooks | Drives | Percent |
|-----------------------------------------------------------|-----------|--------|---------|
| WDC WD40 EFRX-68N32N0 4TB                                 | 1         | 1      | 20%     |
| Toshiba MQ01ABF050 500GB                                  | 1         | 1      | 20%     |
| Seagate ST9250410AS 250GB                                 | 1         | 1      | 20%     |
| Samsung Electronics SSD 850 EVO 1TB                       | 1         | 1      | 20%     |
| Realtek Semiconductor RTS5763DL NVMe SSD Controller 512GB | 1         | 1      | 20%     |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Notebooks | Drives | Percent |
|-----------------------|-----------|--------|---------|
| WDC                   | 1         | 1      | 20%     |
| Toshiba               | 1         | 1      | 20%     |
| Seagate               | 1         | 1      | 20%     |
| Samsung Electronics   | 1         | 1      | 20%     |
| Realtek Semiconductor | 1         | 1      | 20%     |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 1         | 1      | 33.33%  |
| Toshiba | 1         | 1      | 33.33%  |
| Seagate | 1         | 1      | 33.33%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 3         | 3      | 60%     |
| NVMe | 1         | 1      | 20%     |
| SSD  | 1         | 1      | 20%     |

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
| Detected | 80        | 121    | 52.63%  |
| Works    | 67        | 91     | 44.08%  |
| Malfunc  | 5         | 5      | 3.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 87        | 47.54%  |
| Samsung Electronics                     | 29        | 15.85%  |
| Micron Technology                       | 13        | 7.1%    |
| SanDisk                                 | 10        | 5.46%   |
| AMD                                     | 9         | 4.92%   |
| SK hynix                                | 8         | 4.37%   |
| Micron/Crucial Technology               | 5         | 2.73%   |
| Toshiba America Info Systems            | 4         | 2.19%   |
| Shenzhen Longsys Electronics            | 3         | 1.64%   |
| Phison Electronics                      | 3         | 1.64%   |
| KIOXIA                                  | 3         | 1.64%   |
| Union Memory (Shenzhen)                 | 2         | 1.09%   |
| Realtek Semiconductor                   | 2         | 1.09%   |
| Kingston Technology Company             | 2         | 1.09%   |
| Yangtze Memory Technologies             | 1         | 0.55%   |
| Shenzhen Unionmemory Information System | 1         | 0.55%   |
| ADATA Technology                        | 1         | 0.55%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Notebooks | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 10        | 5.13%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 10        | 5.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 5.13%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 4.62%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 8         | 4.1%    |
| Intel Volume Management Device NVMe RAID Controller                            | 8         | 4.1%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 6         | 3.08%   |
| Micron 3400 NVMe SSD [Hendrix]                                                 | 6         | 3.08%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 6         | 3.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 6         | 3.08%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 5         | 2.56%   |
| Micron/Crucial P2 [Nick P2] / P3 / P3 Plus NVMe PCIe SSD (DRAM-less)           | 4         | 2.05%   |
| Intel Tiger Lake-LP SATA Controller                                            | 4         | 2.05%   |
| SK hynix Platinum P41/PC801 NVMe Solid State Drive                             | 3         | 1.54%   |
| SanDisk WD SN560/SN740/SN770/SN5000 NVMe SSD                                   | 3         | 1.54%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 3         | 1.54%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 3         | 1.54%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 3         | 1.54%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 3         | 1.54%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 3         | 1.54%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 3         | 1.54%   |
| Intel Alder Lake-P SATA AHCI Controller                                        | 3         | 1.54%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 3         | 1.54%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 1.03%   |
| SK hynix PC611 NVMe Solid State Drive                                          | 2         | 1.03%   |
| Shenzhen Longsys Lexar NM790 / Patriot Viper VP4300 Lite NVMe SSD (DRAM-less)  | 2         | 1.03%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                    | 2         | 1.03%   |
| Micron 2400 NVMe SSD (DRAM-less)                                               | 2         | 1.03%   |
| Micron 2210 NVMe SSD [Cobain]                                                  | 2         | 1.03%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 2         | 1.03%   |
| Intel SSD 670p Series [Keystone Harbor]                                        | 2         | 1.03%   |
| Intel SSD 660P Series                                                          | 2         | 1.03%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                  | 2         | 1.03%   |
| Intel Comet Lake SATA AHCI Controller                                          | 2         | 1.03%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 2         | 1.03%   |
| Intel 8 Series Chipset Family 4-port SATA Controller 1 [IDE mode] - Mobile     | 2         | 1.03%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 2         | 1.03%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 1.03%   |
| Yangtze Memory ZHITAI TiPlus7100                                               | 1         | 0.51%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 128GB                          | 1         | 0.51%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| NVMe | 86        | 46.74%  |
| SATA | 73        | 39.67%  |
| RAID | 19        | 10.33%  |
| IDE  | 6         | 3.26%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 125       | 86.21%  |
| AMD    | 20        | 13.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-9750H CPU @ 2.60GHz             | 4         | 2.76%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 2.76%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 2.76%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 2.07%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 3         | 2.07%   |
| Intel Core i5-8350U CPU @ 1.70GHz             | 3         | 2.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 3         | 2.07%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 3         | 2.07%   |
| Intel 12th Gen Core i7-1260P                  | 3         | 2.07%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.38%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 2         | 1.38%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 2         | 1.38%   |
| Intel Core i7-5500U CPU @ 2.40GHz             | 2         | 1.38%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz            | 2         | 1.38%   |
| Intel Core i7-10610U CPU @ 1.80GHz            | 2         | 1.38%   |
| Intel Core i5-2540M CPU @ 2.60GHz             | 2         | 1.38%   |
| Intel 12th Gen Core i7-1265U                  | 2         | 1.38%   |
| Intel 12th Gen Core i7-1255U                  | 2         | 1.38%   |
| Intel 12th Gen Core i5-1235U                  | 2         | 1.38%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 2         | 1.38%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 1.38%   |
| AMD Ryzen 9 5900HX with Radeon Graphics       | 2         | 1.38%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 2         | 1.38%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 2         | 1.38%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.69%   |
| Intel Pentium Gold 8505                       | 1         | 0.69%   |
| Intel Pentium Dual-Core CPU T4500 @ 2.30GHz   | 1         | 0.69%   |
| Intel Pentium CPU 4417U @ 2.30GHz             | 1         | 0.69%   |
| Intel Core Ultra 9 185H                       | 1         | 0.69%   |
| Intel Core Ultra 7 155H                       | 1         | 0.69%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.69%   |
| Intel Core i9-14900HX                         | 1         | 0.69%   |
| Intel Core i7-8850H CPU @ 2.60GHz             | 1         | 0.69%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.69%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 1         | 0.69%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 1         | 0.69%   |
| Intel Core i7-7600U CPU @ 2.80GHz             | 1         | 0.69%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.69%   |
| Intel Core i7-5600U CPU @ 2.60GHz             | 1         | 0.69%   |
| Intel Core i7-4910MQ CPU @ 2.90GHz            | 1         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Notebooks | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 48        | 33.1%   |
| Other                   | 33        | 22.76%  |
| Intel Core i5           | 29        | 20%     |
| AMD Ryzen 7             | 6         | 4.14%   |
| Intel Celeron           | 4         | 2.76%   |
| AMD Ryzen 5             | 4         | 2.76%   |
| AMD Ryzen 9             | 3         | 2.07%   |
| Intel Core i9           | 2         | 1.38%   |
| Intel Core i3           | 2         | 1.38%   |
| Intel Core              | 2         | 1.38%   |
| Intel Atom              | 2         | 1.38%   |
| AMD Ryzen 5 PRO         | 2         | 1.38%   |
| Intel Pentium Silver    | 1         | 0.69%   |
| Intel Pentium Gold      | 1         | 0.69%   |
| Intel Pentium Dual-Core | 1         | 0.69%   |
| Intel Pentium           | 1         | 0.69%   |
| Intel Core 2 Duo        | 1         | 0.69%   |
| AMD Ryzen 3             | 1         | 0.69%   |
| AMD A8                  | 1         | 0.69%   |
| AMD A10                 | 1         | 0.69%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 55        | 37.93%  |
| 2      | 38        | 26.21%  |
| 6      | 17        | 11.72%  |
| 8      | 12        | 8.28%   |
| 10     | 8         | 5.52%   |
| 14     | 4         | 2.76%   |
| 12     | 4         | 2.76%   |
| 24     | 2         | 1.38%   |
| 16     | 2         | 1.38%   |
| 20     | 1         | 0.69%   |
| 5      | 1         | 0.69%   |
| 1      | 1         | 0.69%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 145       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 127       | 86.99%  |
| 1      | 19        | 13.01%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 145       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 68        | 46.58%  |
| 0x806c1    | 8         | 5.48%   |
| 0x306c3    | 7         | 4.79%   |
| 0x806ea    | 6         | 4.11%   |
| 0xa0652    | 5         | 3.42%   |
| 0x806ec    | 5         | 3.42%   |
| 0x306a9    | 4         | 2.74%   |
| 0x506e3    | 3         | 2.05%   |
| 0x906a4    | 2         | 1.37%   |
| 0x906a3    | 2         | 1.37%   |
| 0x806e9    | 2         | 1.37%   |
| 0x306d4    | 2         | 1.37%   |
| 0x206a7    | 2         | 1.37%   |
| 0x0a50000d | 2         | 1.37%   |
| 0x0a50000c | 2         | 1.37%   |
| 0x08600104 | 2         | 1.37%   |
| 0x08108102 | 2         | 1.37%   |
| 0x906ea    | 1         | 0.68%   |
| 0x906c0    | 1         | 0.68%   |
| 0x806d1    | 1         | 0.68%   |
| 0x706e5    | 1         | 0.68%   |
| 0x706a8    | 1         | 0.68%   |
| 0x706a1    | 1         | 0.68%   |
| 0x406e3    | 1         | 0.68%   |
| 0x406c4    | 1         | 0.68%   |
| 0x40661    | 1         | 0.68%   |
| 0x40651    | 1         | 0.68%   |
| 0x20655    | 1         | 0.68%   |
| 0x1067a    | 1         | 0.68%   |
| 0x10676    | 1         | 0.68%   |
| 0x0a704103 | 1         | 0.68%   |
| 0x0a50000b | 1         | 0.68%   |
| 0x0a404102 | 1         | 0.68%   |
| 0x0a404101 | 1         | 0.68%   |
| 0x08a00006 | 1         | 0.68%   |
| 0x06006705 | 1         | 0.68%   |
| 0x06006704 | 1         | 0.68%   |
| 0x06001119 | 1         | 0.68%   |
| 0x06001116 | 1         | 0.68%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name              | Notebooks | Percent |
|-------------------|-----------|---------|
| KabyLake          | 31        | 21.23%  |
| Alderlake Hybrid  | 17        | 11.64%  |
| Haswell           | 11        | 7.53%   |
| TigerLake         | 10        | 6.85%   |
| Unknown           | 10        | 6.85%   |
| Skylake           | 9         | 6.16%   |
| IvyBridge         | 7         | 4.79%   |
| CometLake         | 7         | 4.79%   |
| Zen 3             | 6         | 4.11%   |
| SandyBridge       | 6         | 4.11%   |
| IceLake           | 4         | 2.74%   |
| Broadwell         | 4         | 2.74%   |
| Zen+              | 3         | 2.05%   |
| Zen 2             | 3         | 2.05%   |
| Westmere          | 3         | 2.05%   |
| Goldmont plus     | 3         | 2.05%   |
| Silvermont        | 2         | 1.37%   |
| Piledriver        | 2         | 1.37%   |
| Penryn            | 2         | 1.37%   |
| Meteorlake Hybrid | 2         | 1.37%   |
| Excavator         | 2         | 1.37%   |
| Tremont           | 1         | 0.68%   |
| Nehalem           | 1         | 0.68%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Intel  | 116       | 56.04%  |
| Nvidia | 65        | 31.4%   |
| AMD    | 26        | 12.56%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 8         | 3.83%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 8         | 3.83%   |
| Intel Kaby Lake-R GT2 [UHD Graphics 620]                                                 | 7         | 3.35%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 7         | 3.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 7         | 3.35%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 7         | 3.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 7         | 3.35%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 5         | 2.39%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 5         | 2.39%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 4         | 1.91%   |
| Intel Skylake-U GT2 [HD Graphics 520]                                                    | 4         | 1.91%   |
| Intel Kaby Lake-U GT2 [HD Graphics 620]                                                  | 4         | 1.91%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 4         | 1.91%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 4         | 1.91%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 3         | 1.44%   |
| Nvidia TU117GLM [Quadro T1000 Mobile]                                                    | 3         | 1.44%   |
| Nvidia TU106M [GeForce RTX 2060 Mobile]                                                  | 3         | 1.44%   |
| Nvidia GK106GLM [Quadro K2100M]                                                          | 3         | 1.44%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                                          | 3         | 1.44%   |
| Intel Skylake-H GT2 [HD Graphics 530]                                                    | 3         | 1.44%   |
| Intel Raptor Lake-S UHD Graphics                                                         | 3         | 1.44%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.44%   |
| Intel Broadwell-U GT2 [HD Graphics 5500]                                                 | 3         | 1.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 1.44%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 2         | 0.96%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 2         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 2         | 0.96%   |
| Nvidia GM108M [GeForce 940M]                                                             | 2         | 0.96%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 2         | 0.96%   |
| Nvidia GF119M [NVS 4200M]                                                                | 2         | 0.96%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 2         | 0.96%   |
| Nvidia GA107GLM [RTX A2000 Mobile]                                                       | 2         | 0.96%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 0.96%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 2         | 0.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.96%   |
| Intel Meteor Lake-P [Intel Arc Graphics]                                                 | 2         | 0.96%   |
| Intel Kaby Lake-H GT2 [HD Graphics 630]                                                  | 2         | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.96%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 2         | 0.96%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 61        | 41.78%  |
| Intel + Nvidia | 49        | 33.56%  |
| 1 x AMD        | 11        | 7.53%   |
| 1 x Nvidia     | 10        | 6.85%   |
| AMD + Nvidia   | 7         | 4.79%   |
| Intel + AMD    | 6         | 4.11%   |
| 2 x AMD        | 2         | 1.37%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 128       | 88.28%  |
| Proprietary | 14        | 9.66%   |
| Unknown     | 3         | 2.07%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 88        | 59.86%  |
| 3.01-4.0   | 21        | 14.29%  |
| 1.01-2.0   | 13        | 8.84%   |
| 0.01-0.5   | 11        | 7.48%   |
| 0.51-1.0   | 6         | 4.08%   |
| 7.01-8.0   | 4         | 2.72%   |
| 5.01-6.0   | 3         | 2.04%   |
| 8.01-16.0  | 1         | 0.68%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Notebooks | Percent |
|-------------------------|-----------|---------|
| LG Display              | 31        | 15.9%   |
| BOE                     | 29        | 14.87%  |
| AU Optronics            | 29        | 14.87%  |
| Chimei Innolux          | 20        | 10.26%  |
| Samsung Electronics     | 16        | 8.21%   |
| Goldstar                | 11        | 5.64%   |
| Sharp                   | 9         | 4.62%   |
| Dell                    | 9         | 4.62%   |
| Philips                 | 7         | 3.59%   |
| InfoVision              | 4         | 2.05%   |
| Lenovo                  | 3         | 1.54%   |
| AOC                     | 3         | 1.54%   |
| PANDA                   | 2         | 1.03%   |
| Hewlett-Packard         | 2         | 1.03%   |
| CSO                     | 2         | 1.03%   |
| Chi Mei Optoelectronics | 2         | 1.03%   |
| Apple                   | 2         | 1.03%   |
| Unknown (XXX)           | 1         | 0.51%   |
| Toshiba                 | 1         | 0.51%   |
| Sony                    | 1         | 0.51%   |
| Skyworth                | 1         | 0.51%   |
| RTK                     | 1         | 0.51%   |
| Panasonic               | 1         | 0.51%   |
| Iiyama                  | 1         | 0.51%   |
| HJW                     | 1         | 0.51%   |
| Gigabyte Technology     | 1         | 0.51%   |
| CSW                     | 1         | 0.51%   |
| BOE Technology Group    | 1         | 0.51%   |
| BenQ                    | 1         | 0.51%   |
| ASUSTek Computer        | 1         | 0.51%   |
| Acer                    | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch        | 3         | 1.5%    |
| AU Optronics LCD Monitor AUO203D 1920x1080 309x174mm 14.0-inch        | 3         | 1.5%    |
| Sharp LCD Monitor SHP14BA 1920x1080 344x194mm 15.5-inch               | 2         | 1%      |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 2         | 1%      |
| LG Display LCD Monitor LGD02DF 1600x900 310x174mm 14.0-inch           | 2         | 1%      |
| BOE LCD Monitor BOE08D5 1920x1080 344x194mm 15.5-inch                 | 2         | 1%      |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1%      |
| AU Optronics LCD Monitor AUO23ED 1920x1080 344x193mm 15.5-inch        | 2         | 1%      |
| Unknown (XXX) HDMI XXX0029 1920x1080 1152x648mm 52.0-inch             | 1         | 0.5%    |
| Toshiba TV TSB0206 1920x1080                                          | 1         | 0.5%    |
| Sony LCD Monitor MS_003C 1366x768 309x173mm 13.9-inch                 | 1         | 0.5%    |
| Skyworth 238DA23F-B SKY0238 1920x1080 527x296mm 23.8-inch             | 1         | 0.5%    |
| Sharp LQ156M1JW25 SHP152C 1920x1080 344x194mm 15.5-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP158A 1920x1200 312x195mm 14.5-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP1517 3840x2400 366x229mm 17.0-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP14FA 3840x2400 288x180mm 13.4-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP14D1 1920x1200 336x210mm 15.6-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP14D0 3840x2400 336x210mm 15.6-inch               | 1         | 0.5%    |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch               | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0564 1360x768 410x230mm 18.5-inch   | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5448 1920x1080 344x194mm 15.5-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC4149 1366x768 292x174mm 13.4-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC5441 1366x768 344x193mm 15.5-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 293x165mm 13.2-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4178 3200x2000 344x215mm 16.0-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC416D 2880x1800 312x195mm 14.5-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC4141 1366x768 344x194mm 15.5-inch  | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SDC3752 1920x1080 344x194mm 15.5-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SAM723F 3840x2160 700x390mm 31.5-inch | 1         | 0.5%    |
| Samsung Electronics LCD Monitor Odyssey G5                            | 1         | 0.5%    |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.5%    |
| Samsung Electronics C49J89x SAM0F21 3840x1080 1196x336mm 48.9-inch    | 1         | 0.5%    |
| Samsung Electronics C27F398 SAM0D44 1920x1080 598x336mm 27.0-inch     | 1         | 0.5%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 1         | 0.5%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.5%    |
| RTK LCD Monitor RTK1D1A 1920x1080 1020x570mm 46.0-inch                | 1         | 0.5%    |
| Philips PHL 499P9 PHL092A 3840x1080 1193x336mm 48.8-inch              | 1         | 0.5%    |
| Philips PHL 272S4L PHL08E4 2560x1440 597x336mm 27.0-inch              | 1         | 0.5%    |
| Philips PHL 271S7Q PHL090A 1920x1080 598x336mm 27.0-inch              | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 87        | 48.88%  |
| 1366x768 (WXGA)    | 25        | 14.04%  |
| 1920x1200 (WUXGA)  | 11        | 6.18%   |
| 2560x1440 (QHD)    | 9         | 5.06%   |
| 1600x900 (HD+)     | 8         | 4.49%   |
| 3840x2400          | 5         | 2.81%   |
| 3840x2160 (4K)     | 5         | 2.81%   |
| 3440x1440          | 4         | 2.25%   |
| 2560x1080          | 4         | 2.25%   |
| 3840x1080          | 2         | 1.12%   |
| 2880x1800          | 2         | 1.12%   |
| 2560x1600          | 2         | 1.12%   |
| 1680x1050 (WSXGA+) | 2         | 1.12%   |
| Unknown            | 2         | 1.12%   |
| 3200x2000          | 1         | 0.56%   |
| 3072x1920          | 1         | 0.56%   |
| 2880x864           | 1         | 0.56%   |
| 2240x1400          | 1         | 0.56%   |
| 2160x1440          | 1         | 0.56%   |
| 1920x550           | 1         | 0.56%   |
| 1920x1280          | 1         | 0.56%   |
| 1400x1050          | 1         | 0.56%   |
| 1360x768           | 1         | 0.56%   |
| 1280x1024 (SXGA)   | 1         | 0.56%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 64        | 33.33%  |
| 14      | 36        | 18.75%  |
| 13      | 17        | 8.85%   |
| 17      | 12        | 6.25%   |
| 27      | 10        | 5.21%   |
| 24      | 7         | 3.65%   |
| 16      | 7         | 3.65%   |
| 21      | 6         | 3.13%   |
| 34      | 5         | 2.6%    |
| 31      | 4         | 2.08%   |
| 23      | 4         | 2.08%   |
| 18      | 3         | 1.56%   |
| Unknown | 3         | 1.56%   |
| 40      | 2         | 1.04%   |
| 74      | 1         | 0.52%   |
| 65      | 1         | 0.52%   |
| 63      | 1         | 0.52%   |
| 52      | 1         | 0.52%   |
| 49      | 1         | 0.52%   |
| 48      | 1         | 0.52%   |
| 46      | 1         | 0.52%   |
| 43      | 1         | 0.52%   |
| 35      | 1         | 0.52%   |
| 22      | 1         | 0.52%   |
| 19      | 1         | 0.52%   |
| 12      | 1         | 0.52%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 116       | 60.73%  |
| 501-600     | 19        | 9.95%   |
| 351-400     | 14        | 7.33%   |
| 401-500     | 11        | 5.76%   |
| 201-300     | 8         | 4.19%   |
| 1001-1500   | 6         | 3.14%   |
| 701-800     | 5         | 2.62%   |
| 601-700     | 4         | 2.09%   |
| 801-900     | 3         | 1.57%   |
| Unknown     | 3         | 1.57%   |
| 1501-2000   | 1         | 0.52%   |
| 901-1000    | 1         | 0.52%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Notebooks | Percent |
|---------|-----------|---------|
| 16/9    | 125       | 75.3%   |
| 16/10   | 25        | 15.06%  |
| 21/9    | 6         | 3.61%   |
| 32/9    | 3         | 1.81%   |
| 3/2     | 3         | 1.81%   |
| 5/4     | 1         | 0.6%    |
| 4/3     | 1         | 0.6%    |
| 3.33    | 1         | 0.6%    |
| Unknown | 1         | 0.6%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 63        | 32.98%  |
| 81-90          | 47        | 24.61%  |
| 201-250        | 15        | 7.85%   |
| 121-130        | 12        | 6.28%   |
| 351-500        | 10        | 5.24%   |
| 301-350        | 10        | 5.24%   |
| 111-120        | 8         | 4.19%   |
| 501-1000       | 6         | 3.14%   |
| More than 1000 | 4         | 2.09%   |
| 71-80          | 3         | 1.57%   |
| 141-150        | 3         | 1.57%   |
| 91-100         | 3         | 1.57%   |
| Unknown        | 3         | 1.57%   |
| 151-200        | 2         | 1.05%   |
| 61-70          | 1         | 0.52%   |
| 251-300        | 1         | 0.52%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 84        | 44.21%  |
| 101-120       | 41        | 21.58%  |
| 51-100        | 31        | 16.32%  |
| 161-240       | 18        | 9.47%   |
| More than 240 | 8         | 4.21%   |
| 1-50          | 5         | 2.63%   |
| Unknown       | 3         | 1.58%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 99        | 66.89%  |
| 2     | 41        | 27.7%   |
| 3     | 5         | 3.38%   |
| 0     | 2         | 1.35%   |
| 4     | 1         | 0.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 103       | 43.64%  |
| Realtek Semiconductor           | 80        | 33.9%   |
| Qualcomm Atheros                | 13        | 5.51%   |
| MediaTek                        | 6         | 2.54%   |
| Broadcom                        | 6         | 2.54%   |
| Lenovo                          | 5         | 2.12%   |
| ASIX Electronics                | 5         | 2.12%   |
| TP-Link                         | 3         | 1.27%   |
| Dell                            | 2         | 0.85%   |
| XREAL                           | 1         | 0.42%   |
| Shenzhen Goodix Technology      | 1         | 0.42%   |
| Ralink                          | 1         | 0.42%   |
| Qualcomm Atheros Communications | 1         | 0.42%   |
| QNAP System                     | 1         | 0.42%   |
| JMicron Technology              | 1         | 0.42%   |
| Google                          | 1         | 0.42%   |
| DisplayLink                     | 1         | 0.42%   |
| D-Link System                   | 1         | 0.42%   |
| D-Link                          | 1         | 0.42%   |
| Broadcom Limited                | 1         | 0.42%   |
| ASUSTek Computer                | 1         | 0.42%   |
| AboCom Systems                  | 1         | 0.42%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 51        | 17.35%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 17        | 5.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 12        | 4.08%   |
| Intel Wireless 8265 / 8275                                             | 10        | 3.4%    |
| Intel Wi-Fi 6 AX200                                                    | 9         | 3.06%   |
| Intel Wi-Fi 6 AX201                                                    | 7         | 2.38%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 6         | 2.04%   |
| Intel Wireless 7265                                                    | 6         | 2.04%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 6         | 2.04%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 2.04%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 5         | 1.7%    |
| Intel Wireless 8260                                                    | 5         | 1.7%    |
| Intel Wireless 7260                                                    | 5         | 1.7%    |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 1.7%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 5         | 1.7%    |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 1.7%    |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 1.36%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 1.36%   |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]   | 4         | 1.36%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 1.36%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 1.36%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1.02%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 3         | 1.02%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 3         | 1.02%   |
| Intel Wireless 3160                                                    | 3         | 1.02%   |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 3         | 1.02%   |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 1.02%   |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 1.02%   |
| Intel Ethernet Connection (16) I219-V                                  | 3         | 1.02%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 3         | 1.02%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 2         | 0.68%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 2         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 2         | 0.68%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 0.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 2         | 0.68%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 2         | 0.68%   |
| Intel Meteor Lake PCH CNVi WiFi                                        | 2         | 0.68%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                        | 2         | 0.68%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 0.68%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 0.68%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 93        | 65.03%  |
| Realtek Semiconductor           | 18        | 12.59%  |
| Qualcomm Atheros                | 12        | 8.39%   |
| MediaTek                        | 5         | 3.5%    |
| Broadcom                        | 4         | 2.8%    |
| TP-Link                         | 3         | 2.1%    |
| Dell                            | 2         | 1.4%    |
| Ralink                          | 1         | 0.7%    |
| Qualcomm Atheros Communications | 1         | 0.7%    |
| D-Link System                   | 1         | 0.7%    |
| Broadcom Limited                | 1         | 0.7%    |
| ASUSTek Computer                | 1         | 0.7%    |
| AboCom Systems                  | 1         | 0.7%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                         | Notebooks | Percent |
|-------------------------------------------------------------------------------|-----------|---------|
| Intel Wireless 8265 / 8275                                                    | 10        | 6.99%   |
| Intel Wi-Fi 6 AX200                                                           | 9         | 6.29%   |
| Intel Wi-Fi 6 AX201                                                           | 7         | 4.9%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                   | 6         | 4.2%    |
| Intel Wireless 7265                                                           | 6         | 4.2%    |
| Intel Comet Lake PCH CNVi WiFi                                                | 6         | 4.2%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                    | 5         | 3.5%    |
| Intel Wireless 8260                                                           | 5         | 3.5%    |
| Intel Wireless 7260                                                           | 5         | 3.5%    |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                  | 5         | 3.5%    |
| Intel Alder Lake-P PCH CNVi WiFi                                              | 5         | 3.5%    |
| MediaTek MT7921 802.11ax PCIe Wireless Network Adapter [Filogic 330]          | 4         | 2.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                             | 4         | 2.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                      | 3         | 2.1%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                    | 3         | 2.1%    |
| Intel Wireless 3160                                                           | 3         | 2.1%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                       | 3         | 2.1%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                      | 3         | 2.1%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                    | 2         | 1.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                      | 2         | 1.4%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                               | 2         | 1.4%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                    | 2         | 1.4%    |
| Intel Meteor Lake PCH CNVi WiFi                                               | 2         | 1.4%    |
| Intel Ice Lake-LP PCH CNVi WiFi                                               | 2         | 1.4%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                                 | 2         | 1.4%    |
| Intel Centrino Ultimate-N 6300                                                | 2         | 1.4%    |
| Intel Centrino Advanced-N 6200                                                | 2         | 1.4%    |
| Intel Cannon Lake PCH CNVi WiFi                                               | 2         | 1.4%    |
| Intel 700 Series Chipset CNVi WiFi                                            | 2         | 1.4%    |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                                   | 2         | 1.4%    |
| Broadcom BCM43228 802.11a/b/g/n                                               | 2         | 1.4%    |
| TP-Link Archer T9UH v1 [Realtek RTL8814AU]                                    | 1         | 0.7%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller [1T1R]            | 1         | 0.7%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                       | 1         | 0.7%    |
| Realtek RTL8723DE Wireless Network Adapter                                    | 1         | 0.7%    |
| Realtek RTL8191SEvB Wireless LAN Controller                                   | 1         | 0.7%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                           | 1         | 0.7%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                                     | 1         | 0.7%    |
| Qualcomm Atheros TP-Link TL-WN322G v3 / TL-WN422G v2 802.11g [Atheros AR9271] | 1         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                              | 1         | 0.7%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 73        | 51.77%  |
| Intel                 | 45        | 31.91%  |
| Lenovo                | 5         | 3.55%   |
| ASIX Electronics      | 5         | 3.55%   |
| Qualcomm Atheros      | 3         | 2.13%   |
| Broadcom              | 3         | 2.13%   |
| XREAL                 | 1         | 0.71%   |
| QNAP System           | 1         | 0.71%   |
| MediaTek              | 1         | 0.71%   |
| JMicron Technology    | 1         | 0.71%   |
| Google                | 1         | 0.71%   |
| DisplayLink           | 1         | 0.71%   |
| D-Link                | 1         | 0.71%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 51        | 34%     |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 17        | 11.33%  |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 7         | 4.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 6         | 4%      |
| Intel Ethernet Connection (4) I219-LM                                  | 5         | 3.33%   |
| ASIX AX88179 Gigabit Ethernet                                          | 5         | 3.33%   |
| Realtek RTL8125 2.5GbE Controller                                      | 4         | 2.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 4         | 2.67%   |
| Intel Ethernet Connection I217-LM                                      | 4         | 2.67%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 3         | 2%      |
| Intel Ethernet Connection (7) I219-LM                                  | 3         | 2%      |
| Intel Ethernet Connection (4) I219-V                                   | 3         | 2%      |
| Intel Ethernet Connection (16) I219-V                                  | 3         | 2%      |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2         | 1.33%   |
| Intel Ethernet Connection (6) I219-LM                                  | 2         | 1.33%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                               | 2         | 1.33%   |
| XREAL Beam                                                             | 1         | 0.67%   |
| Realtek USB 10/100/1G/2.5 LAN                                          | 1         | 0.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 1         | 0.67%   |
| Realtek Killer E3000 2.5GbE Controller                                 | 1         | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 1         | 0.67%   |
| QNAP System QNAP QNA-UC5G1T USB to 5GbE Adapter                        | 1         | 0.67%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 1         | 0.67%   |
| Lenovo ThinkPad Dock Ethernet [Realtek RTL8153B]                       | 1         | 0.67%   |
| Lenovo Lenovo USB-C to LAN                                             | 1         | 0.67%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                 | 1         | 0.67%   |
| Intel Ethernet Controller I219-LM                                      | 1         | 0.67%   |
| Intel Ethernet controller                                              | 1         | 0.67%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.67%   |
| Intel Ethernet Connection I217-V                                       | 1         | 0.67%   |
| Intel Ethernet Connection (7) I219-V                                   | 1         | 0.67%   |
| Intel Ethernet Connection (3) I218-LM                                  | 1         | 0.67%   |
| Intel Ethernet Connection (2) I219-LM                                  | 1         | 0.67%   |
| Intel Ethernet Connection (18) I219-LM                                 | 1         | 0.67%   |
| Intel Ethernet Connection (13) I219-LM                                 | 1         | 0.67%   |
| Intel Ethernet Connection (10) I219-LM                                 | 1         | 0.67%   |
| Intel 82567LM Gigabit Network Connection                               | 1         | 0.67%   |
| Google Pixel 9a                                                        | 1         | 0.67%   |
| DisplayLink Dell Universal Dock D6000                                  | 1         | 0.67%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 133       | 51.75%  |
| Ethernet | 123       | 47.86%  |
| Modem    | 1         | 0.39%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 101       | 63.52%  |
| Ethernet | 58        | 36.48%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 101       | 69.66%  |
| 1     | 42        | 28.97%  |
| 3     | 1         | 0.69%   |
| 0     | 1         | 0.69%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 102       | 69.86%  |
| Yes  | 44        | 30.14%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 85        | 66.41%  |
| Realtek Semiconductor           | 16        | 12.5%   |
| Qualcomm Atheros Communications | 6         | 4.69%   |
| Foxconn / Hon Hai               | 4         | 3.13%   |
| Lite-On Technology              | 3         | 2.34%   |
| Dell                            | 3         | 2.34%   |
| Broadcom                        | 3         | 2.34%   |
| IMC Networks                    | 2         | 1.56%   |
| Hewlett-Packard                 | 2         | 1.56%   |
| Apple                           | 2         | 1.56%   |
| Ralink                          | 1         | 0.78%   |
| Askey Computer                  | 1         | 0.78%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Notebooks | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 28        | 21.88%  |
| Intel AX201 Bluetooth                                                               | 16        | 12.5%   |
| Realtek Bluetooth Radio                                                             | 13        | 10.16%  |
| Intel Bluetooth Device                                                              | 13        | 10.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 9         | 7.03%   |
| Intel AX200 Bluetooth                                                               | 9         | 7.03%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 4         | 3.13%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 2.34%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 3         | 2.34%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 3         | 2.34%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 1.56%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 1.56%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 2         | 1.56%   |
| IMC Networks Wireless_Device                                                        | 2         | 1.56%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 2         | 1.56%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 2         | 1.56%   |
| Dell DW375 Bluetooth Module                                                         | 2         | 1.56%   |
| Apple Bluetooth Host Controller                                                     | 2         | 1.56%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.78%   |
| Ralink RT3290 Bluetooth                                                             | 1         | 0.78%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 1         | 0.78%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.78%   |
| Foxconn / Hon Hai MediaTek MT7921 Bluetooth                                         | 1         | 0.78%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.78%   |
| Dell Broadcom BCM20702A0 Bluetooth                                                  | 1         | 0.78%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 0.78%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 1         | 0.78%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 1         | 0.78%   |
| Askey Bluetooth Device                                                              | 1         | 0.78%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 123       | 56.94%  |
| Nvidia                | 41        | 18.98%  |
| AMD                   | 21        | 9.72%   |
| Logitech              | 5         | 2.31%   |
| Lenovo                | 3         | 1.39%   |
| Hewlett-Packard       | 3         | 1.39%   |
| GN Netcom             | 3         | 1.39%   |
| C-Media Electronics   | 3         | 1.39%   |
| Texas Instruments     | 2         | 0.93%   |
| Plantronics           | 2         | 0.93%   |
| Conexant Systems      | 2         | 0.93%   |
| VIA Technologies      | 1         | 0.46%   |
| Tenx Technology       | 1         | 0.46%   |
| Saitek                | 1         | 0.46%   |
| Realtek Semiconductor | 1         | 0.46%   |
| JMTek                 | 1         | 0.46%   |
| Huawei Technologies   | 1         | 0.46%   |
| Creative Technology   | 1         | 0.46%   |
| ASUSTek Computer      | 1         | 0.46%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 17        | 6.91%   |
| Intel Sunrise Point-LP HD Audio                                            | 16        | 6.5%    |
| AMD Ryzen HD Audio Controller                                              | 16        | 6.5%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 10        | 4.07%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 10        | 4.07%   |
| Intel Cannon Lake PCH cAVS                                                 | 9         | 3.66%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 7         | 2.85%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 2.85%   |
| AMD Renoir/Cezanne HDMI/DP Audio Controller                                | 7         | 2.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 6         | 2.44%   |
| Intel Comet Lake PCH cAVS                                                  | 6         | 2.44%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 6         | 2.44%   |
| Nvidia TU106 High Definition Audio Controller                              | 4         | 1.63%   |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.63%   |
| Nvidia GF119 HDMI Audio Controller                                         | 4         | 1.63%   |
| Nvidia GA104 High Definition Audio Controller                              | 4         | 1.63%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 4         | 1.63%   |
| Intel Comet Lake PCH-LP cAVS                                               | 4         | 1.63%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 4         | 1.63%   |
| Intel Broadwell-U Audio Controller                                         | 4         | 1.63%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 4         | 1.63%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.63%   |
| Nvidia GK106 HDMI Audio Controller                                         | 3         | 1.22%   |
| Intel Raptor Lake High Definition Audio Controller                         | 3         | 1.22%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.22%   |
| Intel CM238 HD Audio Controller                                            | 3         | 1.22%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 3         | 1.22%   |
| Hewlett-Packard USB Audio                                                  | 3         | 1.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.22%   |
| Texas Instruments PCM2902 Audio Codec                                      | 2         | 0.81%   |
| Plantronics Blackwire 3220 Series                                          | 2         | 0.81%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.81%   |
| Nvidia GA107 High Definition Audio Controller                              | 2         | 0.81%   |
| Nvidia AD104 High Definition Audio Controller                              | 2         | 0.81%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.81%   |
| Intel Meteor Lake-P HD Audio Controller                                    | 2         | 0.81%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 2         | 0.81%   |
| AMD Trinity HDMI Audio Controller                                          | 2         | 0.81%   |
| AMD Radeon High Definition Audio Controller                                | 2         | 0.81%   |
| AMD High Definition Audio Controller                                       | 2         | 0.81%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 26        | 31.71%  |
| SK hynix            | 24        | 29.27%  |
| Micron Technology   | 7         | 8.54%   |
| Crucial             | 6         | 7.32%   |
| Kingston            | 5         | 6.1%    |
| Ramaxel Technology  | 2         | 2.44%   |
| Unknown (ABCD)      | 1         | 1.22%   |
| Unknown (0x0080)    | 1         | 1.22%   |
| Unknown             | 1         | 1.22%   |
| Smart               | 1         | 1.22%   |
| PNY                 | 1         | 1.22%   |
| Magnum Tech         | 1         | 1.22%   |
| Lexar Co Limited    | 1         | 1.22%   |
| Lexar               | 1         | 1.22%   |
| G.Skill             | 1         | 1.22%   |
| A-DATA Technology   | 1         | 1.22%   |
| 8CFD000080AD        | 1         | 1.22%   |
| Unknown             | 1         | 1.22%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 3         | 3.53%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 3.53%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1066MT/s                     | 2         | 2.35%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 2         | 2.35%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 2         | 2.35%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 2         | 2.35%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 1         | 1.18%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 1         | 1.18%   |
| Unknown (0x0080) RAM Module 16GB SODIMM DDR4 2667MT/s            | 1         | 1.18%   |
| Smart RAM SH564128FH8NZQNSCG 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 1         | 1.18%   |
| SK hynix RAM Module 8GB SODIMM DDR3 1600MT/s                     | 1         | 1.18%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1867MT/s                     | 1         | 1.18%   |
| SK hynix RAM Module 4GB Row Of Chips LPDDR5 6400MT/s             | 1         | 1.18%   |
| SK hynix RAM Module 4GB Row Of Chips DDR4 2400MT/s               | 1         | 1.18%   |
| SK hynix RAM Module 32GB SODIMM DDR4 3200MT/s                    | 1         | 1.18%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM 1334MT/s                | 1         | 1.18%   |
| SK hynix RAM HMCG88AGBSA095N 32GB SODIMM DDR5 5600MT/s           | 1         | 1.18%   |
| SK hynix RAM HMCG78MEBSA092N 16GB SODIMM DDR5 4800MT/s           | 1         | 1.18%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| SK hynix RAM HMAA4GS6MJR8N-VK 32GB SODIMM DDR4 2667MT/s          | 1         | 1.18%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.18%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 1.18%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 1         | 1.18%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.18%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.18%   |
| SK hynix RAM H9JCNNNFA5MLYR-N6E 8GB Row Of Chips LPDDR5 6400MT/s | 1         | 1.18%   |
| SK hynix RAM H9HCNNNCPMMLXR-NEE 8GB SODIMM LPDDR4 4266MT/s       | 1         | 1.18%   |
| Samsung RAM Module 8GB SODIMM DDR4 2133MT/s                      | 1         | 1.18%   |
| Samsung RAM Module 16GB SODIMM DDR5 4800MT/s                     | 1         | 1.18%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 1         | 1.18%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s         | 1         | 1.18%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.18%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 1.18%   |
| Samsung RAM M471A2K43EB1-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.18%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 42        | 56%     |
| DDR3   | 18        | 24%     |
| LPDDR5 | 6         | 8%      |
| DDR5   | 6         | 8%      |
| LPDDR4 | 2         | 2.67%   |
| LPDDR3 | 1         | 1.33%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name            | Notebooks | Percent |
|-----------------|-----------|---------|
| SODIMM          | 65        | 85.53%  |
| Row Of Chips    | 9         | 11.84%  |
| Proprietary Car | 1         | 1.32%   |
| Unknown         | 1         | 1.32%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 32        | 39.02%  |
| 16384 | 22        | 26.83%  |
| 4096  | 20        | 24.39%  |
| 32768 | 6         | 7.32%   |
| 65536 | 1         | 1.22%   |
| 2048  | 1         | 1.22%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Notebooks | Percent |
|---------|-----------|---------|
| 3200    | 20        | 25.64%  |
| 2667    | 18        | 23.08%  |
| 1600    | 11        | 14.1%   |
| 6400    | 4         | 5.13%   |
| 2400    | 4         | 5.13%   |
| 1334    | 4         | 5.13%   |
| 5600    | 3         | 3.85%   |
| 4800    | 3         | 3.85%   |
| 2133    | 3         | 3.85%   |
| 1066    | 2         | 2.56%   |
| 7467    | 1         | 1.28%   |
| 5500    | 1         | 1.28%   |
| 4266    | 1         | 1.28%   |
| 3266    | 1         | 1.28%   |
| 1867    | 1         | 1.28%   |
| Unknown | 1         | 1.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model               | Notebooks | Percent |
|---------------------|-----------|---------|
| Canon iP8700 series | 1         | 100%    |

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


| Vendor                                 | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 31        | 25%     |
| IMC Networks                           | 18        | 14.52%  |
| Microdia                               | 15        | 12.1%   |
| Realtek Semiconductor                  | 12        | 9.68%   |
| Bison Electronics                      | 8         | 6.45%   |
| Sunplus Innovation Technology          | 6         | 4.84%   |
| Luxvisions Innotech Limited            | 6         | 4.84%   |
| Quanta                                 | 5         | 4.03%   |
| Syntek                                 | 4         | 3.23%   |
| Logitech                               | 4         | 3.23%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 2.42%   |
| Ricoh                                  | 2         | 1.61%   |
| Suyin                                  | 1         | 0.81%   |
| Sonix Technology                       | 1         | 0.81%   |
| Silicon Motion                         | 1         | 0.81%   |
| Shinetech                              | 1         | 0.81%   |
| Razer USA                              | 1         | 0.81%   |
| Lite-On Technology                     | 1         | 0.81%   |
| Lenovo                                 | 1         | 0.81%   |
| Intel                                  | 1         | 0.81%   |
| icSpring                               | 1         | 0.81%   |
| Apple                                  | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 12        | 9.6%    |
| Microdia Integrated_Webcam_HD                       | 10        | 8%      |
| IMC Networks Integrated Camera                      | 9         | 7.2%    |
| Realtek Integrated_Webcam_HD                        | 6         | 4.8%    |
| IMC Networks USB2.0 HD UVC WebCam                   | 5         | 4%      |
| Chicony HP HD Camera                                | 5         | 4%      |
| Chicony HD Webcam                                   | 5         | 4%      |
| Bison Integrated Camera                             | 4         | 3.2%    |
| Realtek Integrated Webcam_HD                        | 3         | 2.4%    |
| Syntek Lenovo EasyCamera                            | 2         | 1.6%    |
| Syntek Integrated Camera                            | 2         | 1.6%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 1.6%    |
| Luxvisions Innotech Limited HP HD Camera            | 2         | 1.6%    |
| Bison Integrated RGB Camera                         | 2         | 1.6%    |
| Suyin HP TrueVision HD Integrated Webcam            | 1         | 0.8%    |
| Sunplus Lenovo EasyCamera                           | 1         | 0.8%    |
| Sunplus Laptop_Integrated_Webcam_HD                 | 1         | 0.8%    |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.8%    |
| Sunplus Integrated_Webcam_FHD                       | 1         | 0.8%    |
| Sunplus Integrated Camera                           | 1         | 0.8%    |
| Sunplus Asus Webcam                                 | 1         | 0.8%    |
| Sonix USB2.0 HD UVC WebCam                          | 1         | 0.8%    |
| Silicon Motion Lenovo EasyCamera                    | 1         | 0.8%    |
| Shinetech USB2.0 FHD UVC WebCam                     | 1         | 0.8%    |
| Ricoh USB2.0 Camera                                 | 1         | 0.8%    |
| Ricoh Laptop_Integrated_Webcam_FHD                  | 1         | 0.8%    |
| Realtek USB2.0 HD UVC WebCam                        | 1         | 0.8%    |
| Realtek HD WebCam                                   | 1         | 0.8%    |
| Realtek EasyCamera                                  | 1         | 0.8%    |
| Razer USA Gaming Webcam [Kiyo]                      | 1         | 0.8%    |
| Quanta VGA WebCam                                   | 1         | 0.8%    |
| Quanta HP Wide Vision HD Camera                     | 1         | 0.8%    |
| Quanta HP Webcam                                    | 1         | 0.8%    |
| Quanta HP TrueVision HD Camera                      | 1         | 0.8%    |
| Quanta HP 5MP Camera                                | 1         | 0.8%    |
| Microdia Webcam Vitade AF                           | 1         | 0.8%    |
| Microdia Laptop_Integrated_Webcam_E4HD              | 1         | 0.8%    |
| Microdia Laptop_Integrated_Webcam_2M                | 1         | 0.8%    |
| Microdia Integrated_Webcam_FHD                      | 1         | 0.8%    |
| Microdia Integrated Webcam HD                       | 1         | 0.8%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Synaptics                  | 12        | 36.36%  |
| Validity Sensors           | 11        | 33.33%  |
| Shenzhen Goodix Technology | 5         | 15.15%  |
| Upek                       | 2         | 6.06%   |
| LighTuning Technology      | 1         | 3.03%   |
| Elan Microelectronics      | 1         | 3.03%   |
| AuthenTec                  | 1         | 3.03%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 4         | 12.12%  |
| Validity Sensors VFS495 Fingerprint Reader                                 | 3         | 9.09%   |
| Synaptics UWP WBDI Device                                                  | 3         | 9.09%   |
| Shenzhen Goodix FingerPrint                                                | 3         | 9.09%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 6.06%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 6.06%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 2         | 6.06%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 2         | 6.06%   |
| Shenzhen Goodix  Fingerprint Device                                        | 2         | 6.06%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 3.03%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 3.03%   |
| Validity Sensors VFS Fingerprint sensor                                    | 1         | 3.03%   |
| Validity Sensors Synaptics WBDI                                            | 1         | 3.03%   |
| Synaptics WBDI Device                                                      | 1         | 3.03%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 1         | 3.03%   |
| Synaptics Fingerprint reader [HP G6]                                       | 1         | 3.03%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 3.03%   |
| Elan ELAN:Fingerprint                                                      | 1         | 3.03%   |
| AuthenTec AES2810                                                          | 1         | 3.03%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor      | Notebooks | Percent |
|-------------|-----------|---------|
| Broadcom    | 10        | 66.67%  |
| Alcor Micro | 4         | 26.67%  |
| O2 Micro    | 1         | 6.67%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 26.67%  |
| Broadcom 5880                                                                | 3         | 20%     |
| Broadcom 58200                                                               | 3         | 20%     |
| Broadcom BCM5880 Secure Applications Processor                               | 2         | 13.33%  |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 6.67%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 6.67%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 70        | 47.62%  |
| 1     | 54        | 36.73%  |
| 2     | 16        | 10.88%  |
| 3     | 6         | 4.08%   |
| 4     | 1         | 0.68%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 33        | 31.43%  |
| Graphics card         | 19        | 18.1%   |
| Net/wireless          | 13        | 12.38%  |
| Multimedia controller | 11        | 10.48%  |
| Chipcard              | 9         | 8.57%   |
| Firewire controller   | 7         | 6.67%   |
| Storage               | 4         | 3.81%   |
| Net/ethernet          | 4         | 3.81%   |
| Unassigned class      | 1         | 0.95%   |
| Sound                 | 1         | 0.95%   |
| Dvb card              | 1         | 0.95%   |
| Card reader           | 1         | 0.95%   |
| Bluetooth             | 1         | 0.95%   |

