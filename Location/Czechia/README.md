Linux in Czechia - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Czechia.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Czechia/Desktop/README.md) and [notebooks](/Location/Czechia/Notebook/README.md).

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

Total: 3564

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | X75VBP                      | Notebook    | [45dd9e0bea](https://linux-hardware.org/?probe=45dd9e0bea) | May 09, 2024 |
| ASUSTek       | ASUS EXPERTBOOK L2502CYA... | Notebook    | [03df260579](https://linux-hardware.org/?probe=03df260579) | May 09, 2024 |
| Sony          | VGN-Z51MG_B                 | Notebook    | [6e5ed9d5f6](https://linux-hardware.org/?probe=6e5ed9d5f6) | May 08, 2024 |
| ASUSTek       | ROG STRIX Z490-G GAMING     | Desktop     | [3514a63f05](https://linux-hardware.org/?probe=3514a63f05) | May 08, 2024 |
| Hetrix        | Unknown                     | Notebook    | [72a5c6fffe](https://linux-hardware.org/?probe=72a5c6fffe) | May 08, 2024 |
| Lenovo        | ThinkPad Edge E330 3354D... | Notebook    | [4f7e381c6f](https://linux-hardware.org/?probe=4f7e381c6f) | May 07, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [9122522638](https://linux-hardware.org/?probe=9122522638) | May 07, 2024 |
| Lenovo        | IdeaPad 310-15ISK 80SM      | Notebook    | [3064d4fb1f](https://linux-hardware.org/?probe=3064d4fb1f) | May 07, 2024 |
| Lenovo        | ThinkPad T430s 2355CL4      | Notebook    | [b90ab4a6e2](https://linux-hardware.org/?probe=b90ab4a6e2) | May 07, 2024 |
| Dell          | 00CV7F A00                  | Desktop     | [83dce373d6](https://linux-hardware.org/?probe=83dce373d6) | May 06, 2024 |
| ASUSTek       | ROG Strix G731GV_G731GV     | Notebook    | [00ceb2ea16](https://linux-hardware.org/?probe=00ceb2ea16) | May 06, 2024 |
| TUXEDO        | Sirius 16 Gen1              | Notebook    | [b093c73dcb](https://linux-hardware.org/?probe=b093c73dcb) | May 04, 2024 |
| Hardkernel    | ODROID-H3                   | Desktop     | [e9ea8670f9](https://linux-hardware.org/?probe=e9ea8670f9) | May 04, 2024 |
| Lenovo        | U310                        | Notebook    | [0ce2072c15](https://linux-hardware.org/?probe=0ce2072c15) | May 04, 2024 |
| Dell          | 00CV7F A00                  | Desktop     | [0e00dd8ed3](https://linux-hardware.org/?probe=0e00dd8ed3) | May 03, 2024 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [026737408a](https://linux-hardware.org/?probe=026737408a) | May 03, 2024 |
| Gigabyte      | B450 AORUS M                | Desktop     | [931e4419fa](https://linux-hardware.org/?probe=931e4419fa) | May 03, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [2480bab346](https://linux-hardware.org/?probe=2480bab346) | May 02, 2024 |
| HP            | ProBook 4510s               | Notebook    | [a6f89b6485](https://linux-hardware.org/?probe=a6f89b6485) | May 02, 2024 |
| Gigabyte      | Q87M-D2H                    | Desktop     | [f163dcd97e](https://linux-hardware.org/?probe=f163dcd97e) | May 02, 2024 |
| Gigabyte      | Z390 AORUS PRO WIFI-CF      | Desktop     | [1902c0eeab](https://linux-hardware.org/?probe=1902c0eeab) | May 02, 2024 |
| Lenovo        | U310                        | Notebook    | [48cb164f2f](https://linux-hardware.org/?probe=48cb164f2f) | May 01, 2024 |
| Lenovo        | ThinkPad SL510 2847Q7G      | Notebook    | [c2f435ff58](https://linux-hardware.org/?probe=c2f435ff58) | May 01, 2024 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [59903b4ade](https://linux-hardware.org/?probe=59903b4ade) | Apr 30, 2024 |
| ASUSTek       | UX430UNR                    | Notebook    | [5712b06d98](https://linux-hardware.org/?probe=5712b06d98) | Apr 30, 2024 |
| ASUSTek       | UX430UNR                    | Notebook    | [a032f50d3f](https://linux-hardware.org/?probe=a032f50d3f) | Apr 30, 2024 |
| Lenovo        | ThinkPad X250 20CLS75800    | Notebook    | [7626333cd6](https://linux-hardware.org/?probe=7626333cd6) | Apr 29, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [4060d6bdbe](https://linux-hardware.org/?probe=4060d6bdbe) | Apr 29, 2024 |
| Lenovo        | ThinkBook 16 G4+ IAP 21C... | Notebook    | [885d49a692](https://linux-hardware.org/?probe=885d49a692) | Apr 29, 2024 |
| ASUSTek       | Pro A620M-C                 | Desktop     | [124b68b5bf](https://linux-hardware.org/?probe=124b68b5bf) | Apr 29, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [74c797eef3](https://linux-hardware.org/?probe=74c797eef3) | Apr 29, 2024 |
| Minix         | Z64 V1.2                    | Notebook    | [7c0143f3e4](https://linux-hardware.org/?probe=7c0143f3e4) | Apr 28, 2024 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [29c763baa8](https://linux-hardware.org/?probe=29c763baa8) | Apr 27, 2024 |
| Lenovo        | YB1-X91L                    | Tablet      | [1d5955bbb4](https://linux-hardware.org/?probe=1d5955bbb4) | Apr 26, 2024 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [e74da3b338](https://linux-hardware.org/?probe=e74da3b338) | Apr 24, 2024 |
| HP            | 8433 11                     | Desktop     | [ab3e30a8ee](https://linux-hardware.org/?probe=ab3e30a8ee) | Apr 24, 2024 |
| Lenovo        | ThinkPad T420 4180D81       | Notebook    | [586b69e749](https://linux-hardware.org/?probe=586b69e749) | Apr 23, 2024 |
| Unknown       | HU-MNPC05                   | Mini pc     | [a3339b59ad](https://linux-hardware.org/?probe=a3339b59ad) | Apr 23, 2024 |
| Dell          | Precision 7510              | Notebook    | [23916f1909](https://linux-hardware.org/?probe=23916f1909) | Apr 22, 2024 |
| HP            | ProBook 650 G1              | Notebook    | [09883eb0c7](https://linux-hardware.org/?probe=09883eb0c7) | Apr 22, 2024 |
| HP            | Pavilion 15                 | Notebook    | [a0d3bcb2a0](https://linux-hardware.org/?probe=a0d3bcb2a0) | Apr 22, 2024 |
| HP            | 802F                        | Desktop     | [8a38f4d001](https://linux-hardware.org/?probe=8a38f4d001) | Apr 21, 2024 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [c5eedce567](https://linux-hardware.org/?probe=c5eedce567) | Apr 21, 2024 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [739dd7b39e](https://linux-hardware.org/?probe=739dd7b39e) | Apr 21, 2024 |
| Lenovo        | ThinkPad E590 20NB0018MC    | Notebook    | [6b065854a6](https://linux-hardware.org/?probe=6b065854a6) | Apr 21, 2024 |
| HP            | 802F                        | Desktop     | [cb7a0fabc8](https://linux-hardware.org/?probe=cb7a0fabc8) | Apr 21, 2024 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [5b3e452e53](https://linux-hardware.org/?probe=5b3e452e53) | Apr 20, 2024 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [75a61ca2af](https://linux-hardware.org/?probe=75a61ca2af) | Apr 20, 2024 |
| ASUSTek       | TUF Gaming B650M-E WIFI     | Desktop     | [6190a14941](https://linux-hardware.org/?probe=6190a14941) | Apr 19, 2024 |
| Dell          | 0Y2MRG A00                  | Desktop     | [6abe6d21fc](https://linux-hardware.org/?probe=6abe6d21fc) | Apr 19, 2024 |
| MSI           | Z270 GAMING PLUS            | Desktop     | [4e997cc9d3](https://linux-hardware.org/?probe=4e997cc9d3) | Apr 18, 2024 |
| MSI           | Modern 15 B12M              | Notebook    | [b1786f8a58](https://linux-hardware.org/?probe=b1786f8a58) | Apr 17, 2024 |
| Acer          | Swift SFG14-41              | Notebook    | [6fc0fc2e0c](https://linux-hardware.org/?probe=6fc0fc2e0c) | Apr 16, 2024 |
| Dell          | 0Y2MRG A00                  | Desktop     | [693ad9a009](https://linux-hardware.org/?probe=693ad9a009) | Apr 16, 2024 |
| Acer          | Aspire E1-531               | Notebook    | [7d6a4b8c41](https://linux-hardware.org/?probe=7d6a4b8c41) | Apr 15, 2024 |
| Unknown       | RK3588 OPi 5 Plus           | Soc         | [c74a284aaf](https://linux-hardware.org/?probe=c74a284aaf) | Apr 15, 2024 |
| Acer          | Aspire E1-531               | Notebook    | [d38bfe837e](https://linux-hardware.org/?probe=d38bfe837e) | Apr 15, 2024 |
| HP            | OMEN Laptop 15-en1001np ... | Notebook    | [a9e386b4a8](https://linux-hardware.org/?probe=a9e386b4a8) | Apr 15, 2024 |
| Lenovo        | Yoga 530-14ARR 81H9         | Convertible | [6bc6df98ec](https://linux-hardware.org/?probe=6bc6df98ec) | Apr 15, 2024 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [4fb5756438](https://linux-hardware.org/?probe=4fb5756438) | Apr 14, 2024 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [09d6d5fc6e](https://linux-hardware.org/?probe=09d6d5fc6e) | Apr 14, 2024 |
| Dell          | Latitude E6420              | Notebook    | [713c9b9514](https://linux-hardware.org/?probe=713c9b9514) | Apr 13, 2024 |
| Gigabyte      | A520M H                     | Desktop     | [cdb5335b20](https://linux-hardware.org/?probe=cdb5335b20) | Apr 13, 2024 |
| HP            | Pavilion 15                 | Notebook    | [ba8c469ac5](https://linux-hardware.org/?probe=ba8c469ac5) | Apr 13, 2024 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [00f8d60e91](https://linux-hardware.org/?probe=00f8d60e91) | Apr 12, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [47a86e797f](https://linux-hardware.org/?probe=47a86e797f) | Apr 11, 2024 |
| MSI           | MEG Z590 UNIFY              | Desktop     | [88f634c670](https://linux-hardware.org/?probe=88f634c670) | Apr 11, 2024 |
| MSI           | MEG Z590 UNIFY              | Desktop     | [2336b3cd38](https://linux-hardware.org/?probe=2336b3cd38) | Apr 11, 2024 |
| Lenovo        | ThinkPad T480 20L6S29D0W    | Notebook    | [7d55e2a84d](https://linux-hardware.org/?probe=7d55e2a84d) | Apr 11, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [e324b97ac4](https://linux-hardware.org/?probe=e324b97ac4) | Apr 10, 2024 |
| Dell          | Precision 3561              | Notebook    | [6bc6a2a9d9](https://linux-hardware.org/?probe=6bc6a2a9d9) | Apr 09, 2024 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [e54693d43a](https://linux-hardware.org/?probe=e54693d43a) | Apr 08, 2024 |
| ASUSTek       | H81M-R 2016-11-08           | Desktop     | [7ecfc5dbec](https://linux-hardware.org/?probe=7ecfc5dbec) | Apr 07, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [f5ade4bf16](https://linux-hardware.org/?probe=f5ade4bf16) | Apr 07, 2024 |
| Lenovo        | ThinkPad X270 20HN0015GE    | Notebook    | [3446428450](https://linux-hardware.org/?probe=3446428450) | Apr 07, 2024 |
| MSI           | Z97 GAMING 5                | Desktop     | [52f07d74f3](https://linux-hardware.org/?probe=52f07d74f3) | Apr 07, 2024 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [8fa8b6b410](https://linux-hardware.org/?probe=8fa8b6b410) | Apr 06, 2024 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [b2e584528d](https://linux-hardware.org/?probe=b2e584528d) | Apr 06, 2024 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [a4b339c03e](https://linux-hardware.org/?probe=a4b339c03e) | Apr 05, 2024 |
| HP            | EliteBook 840 G4            | Notebook    | [fe41dd5efb](https://linux-hardware.org/?probe=fe41dd5efb) | Apr 05, 2024 |
| Dell          | Latitude 5430               | Notebook    | [2dcc20f886](https://linux-hardware.org/?probe=2dcc20f886) | Apr 05, 2024 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [77e3ddbb44](https://linux-hardware.org/?probe=77e3ddbb44) | Apr 04, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4eb39c2cf0](https://linux-hardware.org/?probe=4eb39c2cf0) | Apr 03, 2024 |
| ASUSTek       | X99-E                       | Desktop     | [f9f01b1a69](https://linux-hardware.org/?probe=f9f01b1a69) | Apr 03, 2024 |
| ASUSTek       | X99-E                       | Desktop     | [e87752dc61](https://linux-hardware.org/?probe=e87752dc61) | Apr 03, 2024 |
| Lenovo        | ThinkPad E15 Gen 3 20YG0... | Notebook    | [effac14d53](https://linux-hardware.org/?probe=effac14d53) | Apr 02, 2024 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [d7142dfd4d](https://linux-hardware.org/?probe=d7142dfd4d) | Apr 01, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [1d0e019001](https://linux-hardware.org/?probe=1d0e019001) | Apr 01, 2024 |
| ASUSTek       | PRIME A320I-K               | Desktop     | [463d13b7df](https://linux-hardware.org/?probe=463d13b7df) | Apr 01, 2024 |
| MSI           | Z370 PC PRO                 | Desktop     | [5d7f434e4e](https://linux-hardware.org/?probe=5d7f434e4e) | Mar 31, 2024 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [971bc94dfd](https://linux-hardware.org/?probe=971bc94dfd) | Mar 31, 2024 |
| Lenovo        | Legion Pro 5 16ARX8 82WM    | Notebook    | [18e0911b3a](https://linux-hardware.org/?probe=18e0911b3a) | Mar 31, 2024 |
| ASUSTek       | P8P67                       | Desktop     | [6ab2d189e5](https://linux-hardware.org/?probe=6ab2d189e5) | Mar 28, 2024 |
| ASUSTek       | P8P67                       | Desktop     | [eae7373113](https://linux-hardware.org/?probe=eae7373113) | Mar 28, 2024 |
| Pegatron      | 2ADC                        | Desktop     | [9f9c35e7b5](https://linux-hardware.org/?probe=9f9c35e7b5) | Mar 27, 2024 |
| Lenovo        | ThinkCentre Edge91 1895B... | Desktop     | [991944129e](https://linux-hardware.org/?probe=991944129e) | Mar 26, 2024 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [d15637af96](https://linux-hardware.org/?probe=d15637af96) | Mar 25, 2024 |
| Lenovo        | ThinkPad X270 20HMS40900    | Notebook    | [573dd9915e](https://linux-hardware.org/?probe=573dd9915e) | Mar 24, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [98053d03fb](https://linux-hardware.org/?probe=98053d03fb) | Mar 23, 2024 |
| ASRock        | AB350 Pro4                  | Desktop     | [6a4491e402](https://linux-hardware.org/?probe=6a4491e402) | Mar 23, 2024 |
| Panasonic     | CF-NX2LDHTS                 | Notebook    | [0b94846d30](https://linux-hardware.org/?probe=0b94846d30) | Mar 23, 2024 |
| Panasonic     | CF-NX2LDHTS                 | Notebook    | [49f6028a20](https://linux-hardware.org/?probe=49f6028a20) | Mar 23, 2024 |
| Intel         | NUC11PABi3 M68269-400       | Mini pc     | [ffb06dd581](https://linux-hardware.org/?probe=ffb06dd581) | Mar 23, 2024 |
| ASUSTek       | N56JN                       | Notebook    | [2bc4f9eba7](https://linux-hardware.org/?probe=2bc4f9eba7) | Mar 22, 2024 |
| Acer          | Aspire 5830TG               | Notebook    | [5190665de2](https://linux-hardware.org/?probe=5190665de2) | Mar 22, 2024 |
| Dell          | Latitude E6230              | Notebook    | [78a94f507a](https://linux-hardware.org/?probe=78a94f507a) | Mar 21, 2024 |
| HP            | Pavilion Plus Laptop 14-... | Notebook    | [c4aa0ba90f](https://linux-hardware.org/?probe=c4aa0ba90f) | Mar 21, 2024 |
| Google        | Astronaut                   | Notebook    | [b2e117a773](https://linux-hardware.org/?probe=b2e117a773) | Mar 21, 2024 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [5a3211374f](https://linux-hardware.org/?probe=5a3211374f) | Mar 20, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [9df4721239](https://linux-hardware.org/?probe=9df4721239) | Mar 20, 2024 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [105dbc74d2](https://linux-hardware.org/?probe=105dbc74d2) | Mar 18, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [f28ca01e47](https://linux-hardware.org/?probe=f28ca01e47) | Mar 18, 2024 |
| Dell          | Latitude E6230              | Notebook    | [67bc6aae53](https://linux-hardware.org/?probe=67bc6aae53) | Mar 18, 2024 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [030fe7cb7a](https://linux-hardware.org/?probe=030fe7cb7a) | Mar 17, 2024 |
| Lenovo        | ThinkPad X270 20HMS40900    | Notebook    | [b7babbc9ca](https://linux-hardware.org/?probe=b7babbc9ca) | Mar 17, 2024 |
| Gigabyte      | A620M GAMING X AX           | Desktop     | [95dabe0b93](https://linux-hardware.org/?probe=95dabe0b93) | Mar 17, 2024 |
| Gigabyte      | B450M S2H                   | Desktop     | [c1dbd5edb2](https://linux-hardware.org/?probe=c1dbd5edb2) | Mar 17, 2024 |
| Gigabyte      | A620M GAMING X AX           | Desktop     | [ac8a1cf30d](https://linux-hardware.org/?probe=ac8a1cf30d) | Mar 16, 2024 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [fb730fc344](https://linux-hardware.org/?probe=fb730fc344) | Mar 16, 2024 |
| Dell          | Latitude E6540              | Notebook    | [bbc5613ffc](https://linux-hardware.org/?probe=bbc5613ffc) | Mar 15, 2024 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [8f589013b1](https://linux-hardware.org/?probe=8f589013b1) | Mar 15, 2024 |
| MSI           | B450-A PRO                  | Desktop     | [fbea84b6b4](https://linux-hardware.org/?probe=fbea84b6b4) | Mar 15, 2024 |
| ASUSTek       | VivoBook_ASUSLaptop K360... | Notebook    | [5bad97c6ec](https://linux-hardware.org/?probe=5bad97c6ec) | Mar 15, 2024 |
| UMAX          | 13Wr                        | Notebook    | [88c71ba263](https://linux-hardware.org/?probe=88c71ba263) | Mar 14, 2024 |
| ASUSTek       | Zenbook 15 UM3504DA_UM35... | Notebook    | [b33165a798](https://linux-hardware.org/?probe=b33165a798) | Mar 13, 2024 |
| HP            | EliteBook 1050 G1           | Notebook    | [a0431bb3bc](https://linux-hardware.org/?probe=a0431bb3bc) | Mar 13, 2024 |
| Lenovo        | ThinkPad T430s 2355CL4      | Notebook    | [e680816d8a](https://linux-hardware.org/?probe=e680816d8a) | Mar 13, 2024 |
| Gigabyte      | Z97X-UD7 TH-CF              | Desktop     | [3f20fe5386](https://linux-hardware.org/?probe=3f20fe5386) | Mar 13, 2024 |
| Lenovo        | B71-80 80RJ                 | Notebook    | [7aa5c86b22](https://linux-hardware.org/?probe=7aa5c86b22) | Mar 12, 2024 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [77f28d5d35](https://linux-hardware.org/?probe=77f28d5d35) | Mar 12, 2024 |
| Google        | Cyan                        | Notebook    | [0cc944571a](https://linux-hardware.org/?probe=0cc944571a) | Mar 12, 2024 |
| MSI           | Z370 PC PRO                 | Desktop     | [a731101036](https://linux-hardware.org/?probe=a731101036) | Mar 11, 2024 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [4c224edb1a](https://linux-hardware.org/?probe=4c224edb1a) | Mar 11, 2024 |
| Lenovo        | ThinkPad L390 Yoga 20NT0... | Convertible | [f18cdf7cd0](https://linux-hardware.org/?probe=f18cdf7cd0) | Mar 11, 2024 |
| HP            | Pavilion 15                 | Notebook    | [b2596c60dd](https://linux-hardware.org/?probe=b2596c60dd) | Mar 10, 2024 |
| Acer          | Aspire 5830TG               | Notebook    | [e09799794f](https://linux-hardware.org/?probe=e09799794f) | Mar 10, 2024 |
| MSI           | GF615M-P33                  | Desktop     | [e90ec20e06](https://linux-hardware.org/?probe=e90ec20e06) | Mar 09, 2024 |
| Dell          | 0PJDGF A02                  | Desktop     | [6b66f42f95](https://linux-hardware.org/?probe=6b66f42f95) | Mar 08, 2024 |
| MSI           | B450 TOMAHAWK               | Desktop     | [40d64c8f25](https://linux-hardware.org/?probe=40d64c8f25) | Mar 08, 2024 |
| ASUSTek       | ROG Strix G814JV_G814JV     | Notebook    | [10e971349c](https://linux-hardware.org/?probe=10e971349c) | Mar 08, 2024 |
| Dell          | Inspiron 15-5578            | Notebook    | [1989ba3a95](https://linux-hardware.org/?probe=1989ba3a95) | Mar 07, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [6f0e97edef](https://linux-hardware.org/?probe=6f0e97edef) | Mar 07, 2024 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | Notebook    | [d8a1f42773](https://linux-hardware.org/?probe=d8a1f42773) | Mar 07, 2024 |
| HP            | ZBook Studio 15.6 Inch G... | Notebook    | [ecbd50f245](https://linux-hardware.org/?probe=ecbd50f245) | Mar 07, 2024 |
| HP            | 2129                        | Desktop     | [c06e16031f](https://linux-hardware.org/?probe=c06e16031f) | Mar 07, 2024 |
| Dell          | Latitude 5500               | Notebook    | [8c248216ac](https://linux-hardware.org/?probe=8c248216ac) | Mar 07, 2024 |
| Supermicro    | X9SRE/X9SRE-3F/X9SRi/X9S... | Server      | [e377adda5e](https://linux-hardware.org/?probe=e377adda5e) | Mar 07, 2024 |
| HP            | 2129                        | Desktop     | [5f2414ecf8](https://linux-hardware.org/?probe=5f2414ecf8) | Mar 07, 2024 |
| ASUSTek       | N55SF                       | Notebook    | [9579229ce6](https://linux-hardware.org/?probe=9579229ce6) | Mar 06, 2024 |
| Unknown       | Unknown                     | Desktop     | [b272a2d828](https://linux-hardware.org/?probe=b272a2d828) | Mar 05, 2024 |
| HP            | ProLiant ML310e Gen8 v2     | Desktop     | [3b6afc68c7](https://linux-hardware.org/?probe=3b6afc68c7) | Mar 05, 2024 |
| Lenovo        | ThinkPad T480 20L6S37W04    | Notebook    | [1278612ad9](https://linux-hardware.org/?probe=1278612ad9) | Mar 05, 2024 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [746fafeef2](https://linux-hardware.org/?probe=746fafeef2) | Mar 05, 2024 |
| Lenovo        | ThinkPad L14 Gen 4 21H50... | Notebook    | [6b1f0885d9](https://linux-hardware.org/?probe=6b1f0885d9) | Mar 04, 2024 |
| HP            | 8434 11                     | Desktop     | [842df97252](https://linux-hardware.org/?probe=842df97252) | Mar 03, 2024 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [230157b598](https://linux-hardware.org/?probe=230157b598) | Mar 03, 2024 |
| Gigabyte      | G41MT-S2PT                  | Desktop     | [740b57ea8c](https://linux-hardware.org/?probe=740b57ea8c) | Mar 03, 2024 |
| ASUSTek       | Zenbook UX425QA_UM425QA     | Notebook    | [21975edff4](https://linux-hardware.org/?probe=21975edff4) | Mar 03, 2024 |
| Acer          | Aspire V3-572P              | Notebook    | [bfdf32c8e1](https://linux-hardware.org/?probe=bfdf32c8e1) | Mar 02, 2024 |
| ASUSTek       | K53SV                       | Notebook    | [1043b72dee](https://linux-hardware.org/?probe=1043b72dee) | Feb 29, 2024 |
| ASUSTek       | PRIME B250M-A               | Desktop     | [9755250230](https://linux-hardware.org/?probe=9755250230) | Feb 27, 2024 |
| Gigabyte      | B550M DS3H AC               | Desktop     | [86575e9e0c](https://linux-hardware.org/?probe=86575e9e0c) | Feb 26, 2024 |
| MSI           | Z97 GAMING 5                | Desktop     | [6ff44e118d](https://linux-hardware.org/?probe=6ff44e118d) | Feb 25, 2024 |
| Dell          | Latitude 5431               | Notebook    | [03544a6699](https://linux-hardware.org/?probe=03544a6699) | Feb 23, 2024 |
| HP            | 1496                        | Desktop     | [1cc3bd19db](https://linux-hardware.org/?probe=1cc3bd19db) | Feb 23, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [3ee0f278e6](https://linux-hardware.org/?probe=3ee0f278e6) | Feb 22, 2024 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [9a1eb808e3](https://linux-hardware.org/?probe=9a1eb808e3) | Feb 22, 2024 |
| Valve         | Galileo                     | Notebook    | [f4c12237df](https://linux-hardware.org/?probe=f4c12237df) | Feb 22, 2024 |
| HP            | Pavilion x360 Convertibl... | Convertible | [8ea3715087](https://linux-hardware.org/?probe=8ea3715087) | Feb 22, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | Notebook    | [044616ab5e](https://linux-hardware.org/?probe=044616ab5e) | Feb 21, 2024 |
| HP            | 255 G8 Notebook PC          | Notebook    | [3185694845](https://linux-hardware.org/?probe=3185694845) | Feb 21, 2024 |
| HP            | EliteBook 840 G6            | Notebook    | [eacc26c850](https://linux-hardware.org/?probe=eacc26c850) | Feb 20, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | Notebook    | [a6ee663daa](https://linux-hardware.org/?probe=a6ee663daa) | Feb 18, 2024 |
| HP            | Compaq 610                  | Notebook    | [e32de41ce7](https://linux-hardware.org/?probe=e32de41ce7) | Feb 18, 2024 |
| Dell          | Latitude E6540              | Notebook    | [b3d3fd2a6e](https://linux-hardware.org/?probe=b3d3fd2a6e) | Feb 18, 2024 |
| Lenovo        | Legion Slim 5 14APH8 82Y... | Notebook    | [2399729951](https://linux-hardware.org/?probe=2399729951) | Feb 16, 2024 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [176496db32](https://linux-hardware.org/?probe=176496db32) | Feb 16, 2024 |
| HP            | EliteBook 850 G4            | Notebook    | [d380866ad3](https://linux-hardware.org/?probe=d380866ad3) | Feb 15, 2024 |
| Dell          | Latitude 7490               | Notebook    | [65ce0de8b5](https://linux-hardware.org/?probe=65ce0de8b5) | Feb 15, 2024 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [9c0e3d1a1a](https://linux-hardware.org/?probe=9c0e3d1a1a) | Feb 14, 2024 |
| HP            | EliteBook 8470p             | Notebook    | [e0dbe8fe33](https://linux-hardware.org/?probe=e0dbe8fe33) | Feb 13, 2024 |
| Lenovo        | ThinkPad Edge E535 3260E... | Notebook    | [96f9c6c61c](https://linux-hardware.org/?probe=96f9c6c61c) | Feb 13, 2024 |
| HP            | 2215                        | Desktop     | [0baf673b54](https://linux-hardware.org/?probe=0baf673b54) | Feb 12, 2024 |
| Valve         | Jupiter                     | Notebook    | [71c7cf074b](https://linux-hardware.org/?probe=71c7cf074b) | Feb 12, 2024 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [9f43349b7d](https://linux-hardware.org/?probe=9f43349b7d) | Feb 10, 2024 |
| Dell          | Latitude D620               | Notebook    | [933222fc00](https://linux-hardware.org/?probe=933222fc00) | Feb 10, 2024 |
| Acer          | Aspire A515-41G             | Notebook    | [11ede91daf](https://linux-hardware.org/?probe=11ede91daf) | Feb 09, 2024 |
| TUXEDO        | InfinityBook S Gen8         | Notebook    | [8dddfa59a5](https://linux-hardware.org/?probe=8dddfa59a5) | Feb 09, 2024 |
| ASUSTek       | M5A99FX PRO R2.0            | Desktop     | [894a9128d0](https://linux-hardware.org/?probe=894a9128d0) | Feb 07, 2024 |
| Dell          | Latitude 5411               | Notebook    | [2872c72934](https://linux-hardware.org/?probe=2872c72934) | Feb 06, 2024 |
| Gigabyte      | AX370-Gaming K7 se3         | Desktop     | [ab6aee51a0](https://linux-hardware.org/?probe=ab6aee51a0) | Feb 03, 2024 |
| Lenovo        | Y50-70 20378                | Notebook    | [67951a8bdd](https://linux-hardware.org/?probe=67951a8bdd) | Feb 03, 2024 |
| Gigabyte      | AX370-Gaming K7 se3         | Desktop     | [e2f3e78a6a](https://linux-hardware.org/?probe=e2f3e78a6a) | Feb 03, 2024 |
| Lenovo        | ThinkPad X230 2325SW9       | Notebook    | [e8681e8668](https://linux-hardware.org/?probe=e8681e8668) | Feb 03, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [a64852fe4a](https://linux-hardware.org/?probe=a64852fe4a) | Feb 02, 2024 |
| Dell          | Inspiron 7577               | Notebook    | [0155afe6f3](https://linux-hardware.org/?probe=0155afe6f3) | Feb 02, 2024 |
| Dell          | Inspiron 7566               | Notebook    | [e8f24dd8cf](https://linux-hardware.org/?probe=e8f24dd8cf) | Jan 31, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [a3277bc7da](https://linux-hardware.org/?probe=a3277bc7da) | Jan 31, 2024 |
| HP            | 802F                        | Desktop     | [7d597a977d](https://linux-hardware.org/?probe=7d597a977d) | Jan 30, 2024 |
| Acer          | Nitro AN515-42              | Notebook    | [9e4c4acd0d](https://linux-hardware.org/?probe=9e4c4acd0d) | Jan 30, 2024 |
| ASUSTek       | UX550VD                     | Notebook    | [3b742650db](https://linux-hardware.org/?probe=3b742650db) | Jan 29, 2024 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [148a4486f3](https://linux-hardware.org/?probe=148a4486f3) | Jan 29, 2024 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [856669283d](https://linux-hardware.org/?probe=856669283d) | Jan 29, 2024 |
| HP            | ZBook Power 15.6 inch G1... | Notebook    | [6304caec55](https://linux-hardware.org/?probe=6304caec55) | Jan 29, 2024 |
| MSI           | 880GMS-E35                  | Desktop     | [0216fb4b4f](https://linux-hardware.org/?probe=0216fb4b4f) | Jan 28, 2024 |
| Samsung       | 300V3A                      | Notebook    | [53e3665790](https://linux-hardware.org/?probe=53e3665790) | Jan 27, 2024 |
| ASRock        | B450 Gaming K4              | Desktop     | [9cee6b0a5b](https://linux-hardware.org/?probe=9cee6b0a5b) | Jan 27, 2024 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [4b4af4b9b4](https://linux-hardware.org/?probe=4b4af4b9b4) | Jan 26, 2024 |
| Dell          | XPS 9320                    | Notebook    | [ed6a1f51f5](https://linux-hardware.org/?probe=ed6a1f51f5) | Jan 26, 2024 |
| HP            | 2000                        | Notebook    | [f1e38c4df2](https://linux-hardware.org/?probe=f1e38c4df2) | Jan 25, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [9ad67b6f8d](https://linux-hardware.org/?probe=9ad67b6f8d) | Jan 23, 2024 |
| HP            | EliteBook 840 G2            | Notebook    | [04f0c2393d](https://linux-hardware.org/?probe=04f0c2393d) | Jan 23, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [61f8c8c9e0](https://linux-hardware.org/?probe=61f8c8c9e0) | Jan 22, 2024 |
| HP            | 89D8 SMVB                   | Desktop     | [3c8308af97](https://linux-hardware.org/?probe=3c8308af97) | Jan 22, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [79cf6e6101](https://linux-hardware.org/?probe=79cf6e6101) | Jan 22, 2024 |
| Dell          | Latitude 5440               | Notebook    | [4ac53b51b3](https://linux-hardware.org/?probe=4ac53b51b3) | Jan 22, 2024 |
| Lenovo        | Legion 5 15ACH6 82JW        | Notebook    | [5a444c3b35](https://linux-hardware.org/?probe=5a444c3b35) | Jan 22, 2024 |
| ASUSTek       | P7P55D                      | Desktop     | [8d8fab9b27](https://linux-hardware.org/?probe=8d8fab9b27) | Jan 21, 2024 |
| ASUSTek       | ROG STRIX B560-I GAMING ... | Desktop     | [d248b6e5a9](https://linux-hardware.org/?probe=d248b6e5a9) | Jan 21, 2024 |
| Lenovo        | G550 20023                  | Notebook    | [577e991c77](https://linux-hardware.org/?probe=577e991c77) | Jan 21, 2024 |
| Lenovo        | MAHOBAY                     | Desktop     | [77a68d33db](https://linux-hardware.org/?probe=77a68d33db) | Jan 20, 2024 |
| Dell          | Latitude E6420              | Notebook    | [b0d535026a](https://linux-hardware.org/?probe=b0d535026a) | Jan 19, 2024 |
| ASUSTek       | TUF Gaming X670E-PLUS WI... | Desktop     | [008c387c2b](https://linux-hardware.org/?probe=008c387c2b) | Jan 19, 2024 |
| Lenovo        | 100e 2nd Gen 81M8           | Notebook    | [a4aa40979a](https://linux-hardware.org/?probe=a4aa40979a) | Jan 18, 2024 |
| HP            | 530 Notebook PC(GU324AA#... | Notebook    | [785d324acb](https://linux-hardware.org/?probe=785d324acb) | Jan 18, 2024 |
| Dell          | Latitude 5591               | Notebook    | [b91323a39b](https://linux-hardware.org/?probe=b91323a39b) | Jan 17, 2024 |
| Acer          | Swift SFX14-41G             | Notebook    | [e3c95c6c18](https://linux-hardware.org/?probe=e3c95c6c18) | Jan 17, 2024 |
| Gigabyte      | EP35-DS3                    | Desktop     | [18f8b43855](https://linux-hardware.org/?probe=18f8b43855) | Jan 16, 2024 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [8e6afbe7c9](https://linux-hardware.org/?probe=8e6afbe7c9) | Jan 16, 2024 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [ae035d3e35](https://linux-hardware.org/?probe=ae035d3e35) | Jan 16, 2024 |
| ASUSTek       | P7P55D-E                    | Desktop     | [bb8785aa08](https://linux-hardware.org/?probe=bb8785aa08) | Jan 15, 2024 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [09e866e5e9](https://linux-hardware.org/?probe=09e866e5e9) | Jan 15, 2024 |
| HP            | Laptop 15-db0xxx            | Notebook    | [cb2cda915a](https://linux-hardware.org/?probe=cb2cda915a) | Jan 15, 2024 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [60e35c48cf](https://linux-hardware.org/?probe=60e35c48cf) | Jan 14, 2024 |
| ASUSTek       | TUF Gaming B560-PLUS WIF... | Desktop     | [0d4e6f7e0b](https://linux-hardware.org/?probe=0d4e6f7e0b) | Jan 13, 2024 |
| HP            | 802F                        | Desktop     | [c1c2cf68cf](https://linux-hardware.org/?probe=c1c2cf68cf) | Jan 13, 2024 |
| HP            | EliteBook 735 G5            | Notebook    | [53b86640e5](https://linux-hardware.org/?probe=53b86640e5) | Jan 12, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [696f5dd9e3](https://linux-hardware.org/?probe=696f5dd9e3) | Jan 12, 2024 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [2714705590](https://linux-hardware.org/?probe=2714705590) | Jan 12, 2024 |
| HP            | EliteBook 735 G5            | Notebook    | [c0282ee6a5](https://linux-hardware.org/?probe=c0282ee6a5) | Jan 11, 2024 |
| Lenovo        | B50-30 20382                | Notebook    | [0ca9774d55](https://linux-hardware.org/?probe=0ca9774d55) | Jan 11, 2024 |
| Lenovo        | B50-30 20382                | Notebook    | [a2ee63de30](https://linux-hardware.org/?probe=a2ee63de30) | Jan 11, 2024 |
| Acer          | Predator PH16-71            | Notebook    | [a2cae97378](https://linux-hardware.org/?probe=a2cae97378) | Jan 11, 2024 |
| Dell          | Inspiron 3793               | Notebook    | [60ded5e8e7](https://linux-hardware.org/?probe=60ded5e8e7) | Jan 11, 2024 |
| HP            | 198E                        | Desktop     | [15f15e41f1](https://linux-hardware.org/?probe=15f15e41f1) | Jan 11, 2024 |
| ASUSTek       | H81T R2.0                   | Desktop     | [23cc8eb053](https://linux-hardware.org/?probe=23cc8eb053) | Jan 10, 2024 |
| Dell          | Latitude 5440               | Notebook    | [61e99860d0](https://linux-hardware.org/?probe=61e99860d0) | Jan 10, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [10676b8682](https://linux-hardware.org/?probe=10676b8682) | Jan 10, 2024 |
| Lenovo        | ThinkPad S1 Yoga 12 20DK... | Notebook    | [2bb251ffbb](https://linux-hardware.org/?probe=2bb251ffbb) | Jan 09, 2024 |
| HP            | Compaq 610                  | Notebook    | [da1dd5ace4](https://linux-hardware.org/?probe=da1dd5ace4) | Jan 08, 2024 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [88c9ecb793](https://linux-hardware.org/?probe=88c9ecb793) | Jan 08, 2024 |
| Lenovo        | Y50-70 20378                | Notebook    | [1bd4e00b2a](https://linux-hardware.org/?probe=1bd4e00b2a) | Jan 08, 2024 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [b3dbded413](https://linux-hardware.org/?probe=b3dbded413) | Jan 07, 2024 |
| Gigabyte      | B650 GAMING X               | Desktop     | [33c147e1f3](https://linux-hardware.org/?probe=33c147e1f3) | Jan 07, 2024 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [6eaa268ce1](https://linux-hardware.org/?probe=6eaa268ce1) | Jan 07, 2024 |
| HP            | 250 G3                      | Notebook    | [259acacdb3](https://linux-hardware.org/?probe=259acacdb3) | Jan 06, 2024 |
| Google        | Teemo                       | Desktop     | [c763bd20f9](https://linux-hardware.org/?probe=c763bd20f9) | Jan 06, 2024 |
| Acer          | Nitro AN515-44              | Notebook    | [4116ba8fb4](https://linux-hardware.org/?probe=4116ba8fb4) | Jan 05, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [345ae1cb3d](https://linux-hardware.org/?probe=345ae1cb3d) | Jan 05, 2024 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [280d389295](https://linux-hardware.org/?probe=280d389295) | Jan 05, 2024 |
| Acer          | Extensa 5230                | Notebook    | [2c36e88ef4](https://linux-hardware.org/?probe=2c36e88ef4) | Jan 03, 2024 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [5e72d133f1](https://linux-hardware.org/?probe=5e72d133f1) | Jan 02, 2024 |
| Lenovo        | ThinkPad L15 Gen 4 21H70... | Notebook    | [5983998e46](https://linux-hardware.org/?probe=5983998e46) | Jan 02, 2024 |
| Apple         | MacBookPro9,2               | Notebook    | [7f113211a4](https://linux-hardware.org/?probe=7f113211a4) | Dec 31, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [3185001cb4](https://linux-hardware.org/?probe=3185001cb4) | Dec 30, 2023 |
| HP            | Compaq 610                  | Notebook    | [d0849e0580](https://linux-hardware.org/?probe=d0849e0580) | Dec 30, 2023 |
| Intel         | Thurley                     | Desktop     | [2ad7d27607](https://linux-hardware.org/?probe=2ad7d27607) | Dec 29, 2023 |
| Acer          | Aspire XC-330               | Desktop     | [1b2d301d07](https://linux-hardware.org/?probe=1b2d301d07) | Dec 29, 2023 |
| Dell          | XPS 13 9380                 | Notebook    | [1148fbe6b6](https://linux-hardware.org/?probe=1148fbe6b6) | Dec 29, 2023 |
| HP            | 2000                        | Notebook    | [eac2251c15](https://linux-hardware.org/?probe=eac2251c15) | Dec 28, 2023 |
| MSI           | MS-7390                     | Desktop     | [ca9f0bde00](https://linux-hardware.org/?probe=ca9f0bde00) | Dec 28, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [f2e13b11bd](https://linux-hardware.org/?probe=f2e13b11bd) | Dec 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [d23b5553ca](https://linux-hardware.org/?probe=d23b5553ca) | Dec 27, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [87efb02531](https://linux-hardware.org/?probe=87efb02531) | Dec 27, 2023 |
| Dell          | Latitude 5591               | Notebook    | [99b2702a06](https://linux-hardware.org/?probe=99b2702a06) | Dec 27, 2023 |
| Valve         | Jupiter                     | Notebook    | [eeac675274](https://linux-hardware.org/?probe=eeac675274) | Dec 27, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [f91e53f3e0](https://linux-hardware.org/?probe=f91e53f3e0) | Dec 26, 2023 |
| HP            | 2000                        | Notebook    | [057698e1aa](https://linux-hardware.org/?probe=057698e1aa) | Dec 26, 2023 |
| Lenovo        | Yoga Pro 9 16IRP8 83BY      | Notebook    | [b08bd5ba2c](https://linux-hardware.org/?probe=b08bd5ba2c) | Dec 25, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [9e99d63708](https://linux-hardware.org/?probe=9e99d63708) | Dec 25, 2023 |
| Lenovo        | 3098 0B98417 PRO            | Desktop     | [770682ab90](https://linux-hardware.org/?probe=770682ab90) | Dec 24, 2023 |
| Lenovo        | ThinkPad P14s Gen 4 21K5... | Notebook    | [d7b7e34741](https://linux-hardware.org/?probe=d7b7e34741) | Dec 24, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [a79885417a](https://linux-hardware.org/?probe=a79885417a) | Dec 23, 2023 |
| HP            | ProBook 4540s               | Notebook    | [fbed208acc](https://linux-hardware.org/?probe=fbed208acc) | Dec 23, 2023 |
| Lenovo        | ThinkPad X270 20HMS25R00    | Notebook    | [91820391fd](https://linux-hardware.org/?probe=91820391fd) | Dec 23, 2023 |
| ASUSTek       | P8H61 EVO                   | Desktop     | [a123efbb84](https://linux-hardware.org/?probe=a123efbb84) | Dec 22, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [2f52e3fdc9](https://linux-hardware.org/?probe=2f52e3fdc9) | Dec 22, 2023 |
| HP            | ProBook 4540s               | Notebook    | [27155e8350](https://linux-hardware.org/?probe=27155e8350) | Dec 22, 2023 |
| Dell          | Latitude 7490               | Notebook    | [d0ea360540](https://linux-hardware.org/?probe=d0ea360540) | Dec 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [ef2e756e7b](https://linux-hardware.org/?probe=ef2e756e7b) | Dec 21, 2023 |
| Lenovo        | 318E SDK0J40697 WIN 3305... | Desktop     | [191d4913cd](https://linux-hardware.org/?probe=191d4913cd) | Dec 21, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [fc2beada0a](https://linux-hardware.org/?probe=fc2beada0a) | Dec 21, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a7044c8c2a](https://linux-hardware.org/?probe=a7044c8c2a) | Dec 19, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [35272a3d20](https://linux-hardware.org/?probe=35272a3d20) | Dec 19, 2023 |
| Dell          | Precision M2800             | Notebook    | [8800042fb5](https://linux-hardware.org/?probe=8800042fb5) | Dec 19, 2023 |
| HP            | EliteBook 840 G6            | Notebook    | [42706222be](https://linux-hardware.org/?probe=42706222be) | Dec 19, 2023 |
| MSI           | Z87-G45 GAMING              | Desktop     | [e728e078f2](https://linux-hardware.org/?probe=e728e078f2) | Dec 18, 2023 |
| Sony          | VGN-FW455J                  | Notebook    | [f16255f9d1](https://linux-hardware.org/?probe=f16255f9d1) | Dec 17, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [4c8c4e1c68](https://linux-hardware.org/?probe=4c8c4e1c68) | Dec 17, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [a155267edc](https://linux-hardware.org/?probe=a155267edc) | Dec 17, 2023 |
| Dell          | Latitude 7490               | Notebook    | [a5431ec5e0](https://linux-hardware.org/?probe=a5431ec5e0) | Dec 15, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [9e63ff66cb](https://linux-hardware.org/?probe=9e63ff66cb) | Dec 15, 2023 |
| Acer          | Aspire A515-57G             | Notebook    | [638a0b8c0c](https://linux-hardware.org/?probe=638a0b8c0c) | Dec 15, 2023 |
| HP            | 09CCh                       | Desktop     | [e966e2bb97](https://linux-hardware.org/?probe=e966e2bb97) | Dec 15, 2023 |
| HP            | ZBook 15u G6                | Notebook    | [4467debb1c](https://linux-hardware.org/?probe=4467debb1c) | Dec 15, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [8939c99ccb](https://linux-hardware.org/?probe=8939c99ccb) | Dec 15, 2023 |
| ASUSTek       | X550CA                      | Notebook    | [fe7ad66674](https://linux-hardware.org/?probe=fe7ad66674) | Dec 13, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [25b995fdda](https://linux-hardware.org/?probe=25b995fdda) | Dec 12, 2023 |
| ASUSTek       | ROG STRIX X670E-F GAMING... | Desktop     | [52ffec69ce](https://linux-hardware.org/?probe=52ffec69ce) | Dec 12, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [785864b944](https://linux-hardware.org/?probe=785864b944) | Dec 11, 2023 |
| ASUSTek       | M4N68T-M-LE-V2              | Desktop     | [a00282d994](https://linux-hardware.org/?probe=a00282d994) | Dec 11, 2023 |
| Gigabyte      | Z270-Gaming K3 2017-06-1... | Desktop     | [5292573e8d](https://linux-hardware.org/?probe=5292573e8d) | Dec 11, 2023 |
| HP            | 09CCh                       | Desktop     | [3ef7653874](https://linux-hardware.org/?probe=3ef7653874) | Dec 10, 2023 |
| HP            | 2000                        | Notebook    | [40929a84a0](https://linux-hardware.org/?probe=40929a84a0) | Dec 10, 2023 |
| HP            | Laptop 15-fc0xxx            | Notebook    | [e55319a16a](https://linux-hardware.org/?probe=e55319a16a) | Dec 09, 2023 |
| HP            | 212B                        | Desktop     | [9a48a7f9bc](https://linux-hardware.org/?probe=9a48a7f9bc) | Dec 09, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [ba71538aed](https://linux-hardware.org/?probe=ba71538aed) | Dec 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [70f37dae85](https://linux-hardware.org/?probe=70f37dae85) | Dec 08, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [01f7b97e5d](https://linux-hardware.org/?probe=01f7b97e5d) | Dec 08, 2023 |
| Dell          | Latitude 5591               | Notebook    | [1961ebb904](https://linux-hardware.org/?probe=1961ebb904) | Dec 07, 2023 |
| Dell          | Latitude 5591               | Notebook    | [b9f6d020e8](https://linux-hardware.org/?probe=b9f6d020e8) | Dec 07, 2023 |
| Dell          | Precision 3550              | Notebook    | [da173d0ccc](https://linux-hardware.org/?probe=da173d0ccc) | Dec 07, 2023 |
| Valve         | Jupiter                     | Notebook    | [93bf1ceeec](https://linux-hardware.org/?probe=93bf1ceeec) | Dec 05, 2023 |
| Lenovo        | IdeaPad Duet 5 12IAU7 82... | Tablet      | [a9c38d3c16](https://linux-hardware.org/?probe=a9c38d3c16) | Dec 04, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [9b92fedd68](https://linux-hardware.org/?probe=9b92fedd68) | Dec 03, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [debba6a511](https://linux-hardware.org/?probe=debba6a511) | Dec 03, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [e4f6d008cc](https://linux-hardware.org/?probe=e4f6d008cc) | Dec 03, 2023 |
| MSI           | B360-A PRO                  | Desktop     | [7df9fbb107](https://linux-hardware.org/?probe=7df9fbb107) | Dec 03, 2023 |
| MSI           | B360-A PRO                  | Desktop     | [f9da2a7d45](https://linux-hardware.org/?probe=f9da2a7d45) | Dec 03, 2023 |
| Sony          | VPCS13S9E                   | Notebook    | [0cd7cfa9de](https://linux-hardware.org/?probe=0cd7cfa9de) | Dec 02, 2023 |
| Dynabook      | PORTEGE X50-G               | Notebook    | [65a2f2f3d5](https://linux-hardware.org/?probe=65a2f2f3d5) | Dec 01, 2023 |
| Lenovo        | ThinkPad T430 2349AK2       | Notebook    | [53a55a0da2](https://linux-hardware.org/?probe=53a55a0da2) | Dec 01, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [17577fa161](https://linux-hardware.org/?probe=17577fa161) | Dec 01, 2023 |
| Dell          | Latitude E6420              | Notebook    | [ebd186f423](https://linux-hardware.org/?probe=ebd186f423) | Dec 01, 2023 |
| Lenovo        | G700 20251                  | Notebook    | [e4e63d5300](https://linux-hardware.org/?probe=e4e63d5300) | Nov 30, 2023 |
| Lenovo        | Win8 STD MM DPK IPG         | Desktop     | [59610f075c](https://linux-hardware.org/?probe=59610f075c) | Nov 30, 2023 |
| Lenovo        | Win8 STD MM DPK IPG         | Desktop     | [1959f30d83](https://linux-hardware.org/?probe=1959f30d83) | Nov 30, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [86519a17c4](https://linux-hardware.org/?probe=86519a17c4) | Nov 30, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [cc47b08289](https://linux-hardware.org/?probe=cc47b08289) | Nov 30, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [cfeac0b40f](https://linux-hardware.org/?probe=cfeac0b40f) | Nov 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [71cf2f0a79](https://linux-hardware.org/?probe=71cf2f0a79) | Nov 29, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [685ce27fae](https://linux-hardware.org/?probe=685ce27fae) | Nov 29, 2023 |
| Acer          | Nitro AN515-58              | Notebook    | [c4a56c14f5](https://linux-hardware.org/?probe=c4a56c14f5) | Nov 29, 2023 |
| Fujitsu       | LIFEBOOK A3511              | Notebook    | [d1dc329e65](https://linux-hardware.org/?probe=d1dc329e65) | Nov 29, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [d0c3893980](https://linux-hardware.org/?probe=d0c3893980) | Nov 29, 2023 |
| Dell          | Latitude E6540              | Notebook    | [ae3c1282c2](https://linux-hardware.org/?probe=ae3c1282c2) | Nov 29, 2023 |
| Dell          | 0KV62T A00                  | Desktop     | [7c57d31cc7](https://linux-hardware.org/?probe=7c57d31cc7) | Nov 28, 2023 |
| UMAX          | VisionBook 14Wr Plus        | Notebook    | [a0d4963838](https://linux-hardware.org/?probe=a0d4963838) | Nov 28, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [8ef4fb91ac](https://linux-hardware.org/?probe=8ef4fb91ac) | Nov 27, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [cb6d17a69a](https://linux-hardware.org/?probe=cb6d17a69a) | Nov 26, 2023 |
| ASUSTek       | PN64                        | Mini pc     | [a39cb80b48](https://linux-hardware.org/?probe=a39cb80b48) | Nov 26, 2023 |
| UMAX          | VisionBook-N12R             | Notebook    | [e77e8d6999](https://linux-hardware.org/?probe=e77e8d6999) | Nov 26, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [bebbc2f6c4](https://linux-hardware.org/?probe=bebbc2f6c4) | Nov 25, 2023 |
| Dell          | Latitude 5511               | Notebook    | [254abd404f](https://linux-hardware.org/?probe=254abd404f) | Nov 25, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [320763e400](https://linux-hardware.org/?probe=320763e400) | Nov 25, 2023 |
| HP            | Compaq 6730b (NB027EA#AK... | Notebook    | [3b3bf03eee](https://linux-hardware.org/?probe=3b3bf03eee) | Nov 25, 2023 |
| Lenovo        | ThinkPad E450 20DC008DMC    | Notebook    | [56fc21d585](https://linux-hardware.org/?probe=56fc21d585) | Nov 23, 2023 |
| Lenovo        | IdeaPadFlex 5 15ITL05 82... | Convertible | [3c0651cb41](https://linux-hardware.org/?probe=3c0651cb41) | Nov 23, 2023 |
| ASUSTek       | K54LY                       | Notebook    | [4ebc53e69c](https://linux-hardware.org/?probe=4ebc53e69c) | Nov 23, 2023 |
| Lenovo        | ThinkPad X260 20F5S9GM01    | Notebook    | [9c8590e300](https://linux-hardware.org/?probe=9c8590e300) | Nov 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [0337023dbe](https://linux-hardware.org/?probe=0337023dbe) | Nov 22, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b305b3da28](https://linux-hardware.org/?probe=b305b3da28) | Nov 22, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [336fe65e03](https://linux-hardware.org/?probe=336fe65e03) | Nov 22, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [af566d6f0c](https://linux-hardware.org/?probe=af566d6f0c) | Nov 22, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [47105264f8](https://linux-hardware.org/?probe=47105264f8) | Nov 22, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [748ea9f21b](https://linux-hardware.org/?probe=748ea9f21b) | Nov 21, 2023 |
| Dell          | Latitude E6430              | Notebook    | [dc02cb2409](https://linux-hardware.org/?probe=dc02cb2409) | Nov 20, 2023 |
| HP            | ProLiant DL380e Gen8        | Server      | [221dcda3ae](https://linux-hardware.org/?probe=221dcda3ae) | Nov 19, 2023 |
| UMAX          | VisionBook-N12R             | Notebook    | [89e41854be](https://linux-hardware.org/?probe=89e41854be) | Nov 19, 2023 |
| UMAX          | VisionBook 9Wi Pro          | Tablet      | [816a26352f](https://linux-hardware.org/?probe=816a26352f) | Nov 19, 2023 |
| Lenovo        | ThinkPad X201 3680DE3       | Notebook    | [38290dc3e7](https://linux-hardware.org/?probe=38290dc3e7) | Nov 17, 2023 |
| Lenovo        | IdeaPad Y580 20132          | Notebook    | [ca7747546b](https://linux-hardware.org/?probe=ca7747546b) | Nov 17, 2023 |
| Dell          | Inspiron 7577               | Notebook    | [62e08b2285](https://linux-hardware.org/?probe=62e08b2285) | Nov 15, 2023 |
| Acer          | Aspire A315-34              | Notebook    | [8179414a49](https://linux-hardware.org/?probe=8179414a49) | Nov 14, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ITL5 8... | Notebook    | [2204427cc1](https://linux-hardware.org/?probe=2204427cc1) | Nov 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [46cfd3f6bf](https://linux-hardware.org/?probe=46cfd3f6bf) | Nov 13, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [001dd47e7d](https://linux-hardware.org/?probe=001dd47e7d) | Nov 12, 2023 |
| Acer          | Aspire E1-531               | Notebook    | [41e1f90785](https://linux-hardware.org/?probe=41e1f90785) | Nov 11, 2023 |
| Sony          | VPCEB4J0E                   | Notebook    | [c1e2a1a0da](https://linux-hardware.org/?probe=c1e2a1a0da) | Nov 11, 2023 |
| Acer          | Nitro AN515-55              | Notebook    | [65a7263504](https://linux-hardware.org/?probe=65a7263504) | Nov 09, 2023 |
| HP            | 83E2                        | Mini pc     | [565701f119](https://linux-hardware.org/?probe=565701f119) | Nov 09, 2023 |
| Lenovo        | ThinkPad L390 20NRCTO1WW    | Notebook    | [47557dd574](https://linux-hardware.org/?probe=47557dd574) | Nov 09, 2023 |
| Lenovo        | ThinkPad X1 Tablet Gen 2... | Tablet      | [154324f43d](https://linux-hardware.org/?probe=154324f43d) | Nov 08, 2023 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [41fd02095e](https://linux-hardware.org/?probe=41fd02095e) | Nov 07, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [ef019ff242](https://linux-hardware.org/?probe=ef019ff242) | Nov 06, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [2710dfedf4](https://linux-hardware.org/?probe=2710dfedf4) | Nov 05, 2023 |
| Dell          | Latitude E7440              | Notebook    | [5a151e929f](https://linux-hardware.org/?probe=5a151e929f) | Nov 05, 2023 |
| Lenovo        | ThinkPad W541 20EGS0QG1Z    | Notebook    | [ae8881b2b2](https://linux-hardware.org/?probe=ae8881b2b2) | Nov 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [5832913981](https://linux-hardware.org/?probe=5832913981) | Nov 04, 2023 |
| Lenovo        | ThinkPad W541 20EGS0QG1Z    | Notebook    | [a3d91609e9](https://linux-hardware.org/?probe=a3d91609e9) | Nov 04, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [4f6d5932fa](https://linux-hardware.org/?probe=4f6d5932fa) | Nov 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 4 21K4S... | Notebook    | [60187ba0be](https://linux-hardware.org/?probe=60187ba0be) | Nov 04, 2023 |
| Rockchip      | Orange Pi 5 Plus            | Soc         | [9c30c8c8b4](https://linux-hardware.org/?probe=9c30c8c8b4) | Nov 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS        | Desktop     | [99b1ce4372](https://linux-hardware.org/?probe=99b1ce4372) | Nov 02, 2023 |
| Intel         | NUC7JYB J67969-403          | Mini pc     | [a7afcdcef2](https://linux-hardware.org/?probe=a7afcdcef2) | Nov 02, 2023 |
| HP            | EliteBook 840 G5            | Notebook    | [a42017f05d](https://linux-hardware.org/?probe=a42017f05d) | Nov 02, 2023 |
| MSI           | IONA                        | Desktop     | [579757d1cf](https://linux-hardware.org/?probe=579757d1cf) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [1fd433ec1e](https://linux-hardware.org/?probe=1fd433ec1e) | Nov 02, 2023 |
| Dell          | Latitude 5480               | Notebook    | [567a2774f8](https://linux-hardware.org/?probe=567a2774f8) | Nov 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [b1be043dc0](https://linux-hardware.org/?probe=b1be043dc0) | Oct 31, 2023 |
| Gigabyte      | GA-970A-UD3                 | Desktop     | [98b1bd5970](https://linux-hardware.org/?probe=98b1bd5970) | Oct 31, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [15573e8d54](https://linux-hardware.org/?probe=15573e8d54) | Oct 30, 2023 |
| HP            | 250 G3                      | Notebook    | [784033212e](https://linux-hardware.org/?probe=784033212e) | Oct 29, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [a718d2e0ba](https://linux-hardware.org/?probe=a718d2e0ba) | Oct 28, 2023 |
| Dell          | 06X1TJ A00                  | Desktop     | [c2bc73c67b](https://linux-hardware.org/?probe=c2bc73c67b) | Oct 28, 2023 |
| Radxa         | ROCK 5B (DT)                | Soc         | [b1c2a699a9](https://linux-hardware.org/?probe=b1c2a699a9) | Oct 28, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [c866e0068b](https://linux-hardware.org/?probe=c866e0068b) | Oct 28, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [10af2377c2](https://linux-hardware.org/?probe=10af2377c2) | Oct 28, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [e08a8fa43b](https://linux-hardware.org/?probe=e08a8fa43b) | Oct 28, 2023 |
| ASUSTek       | ROG Strix G513QC_G513QC     | Notebook    | [bdf8012e05](https://linux-hardware.org/?probe=bdf8012e05) | Oct 27, 2023 |
| Dell          | Inspiron 5737               | Notebook    | [6ed0863a43](https://linux-hardware.org/?probe=6ed0863a43) | Oct 27, 2023 |
| ASUSTek       | X550CL                      | Notebook    | [a95ddd6798](https://linux-hardware.org/?probe=a95ddd6798) | Oct 26, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [3279dc82a1](https://linux-hardware.org/?probe=3279dc82a1) | Oct 26, 2023 |
| HP            | 250 G3                      | Notebook    | [43fbeb0886](https://linux-hardware.org/?probe=43fbeb0886) | Oct 26, 2023 |
| ASRock        | J4125-ITX                   | Desktop     | [b124e800d6](https://linux-hardware.org/?probe=b124e800d6) | Oct 25, 2023 |
| ASUSTek       | PRIME B650M-A WIFI          | Desktop     | [d22fc67d1d](https://linux-hardware.org/?probe=d22fc67d1d) | Oct 25, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ARH7 82S... | Notebook    | [819d596b2e](https://linux-hardware.org/?probe=819d596b2e) | Oct 24, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [a6d732c859](https://linux-hardware.org/?probe=a6d732c859) | Oct 24, 2023 |
| Gigabyte      | EX38-DS5                    | Desktop     | [79e9d5669a](https://linux-hardware.org/?probe=79e9d5669a) | Oct 23, 2023 |
| MSI           | IONA                        | Desktop     | [e444708510](https://linux-hardware.org/?probe=e444708510) | Oct 22, 2023 |
| Lenovo        | Unknown                     | Notebook    | [21cf9c327a](https://linux-hardware.org/?probe=21cf9c327a) | Oct 22, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [8f65236e52](https://linux-hardware.org/?probe=8f65236e52) | Oct 22, 2023 |
| Dell          | System Vostro 3750          | Notebook    | [33345af29b](https://linux-hardware.org/?probe=33345af29b) | Oct 22, 2023 |
| Dell          | Vostro 3560                 | Notebook    | [a523689a60](https://linux-hardware.org/?probe=a523689a60) | Oct 21, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [e19b58f8be](https://linux-hardware.org/?probe=e19b58f8be) | Oct 21, 2023 |
| Acer          | Aspire R3-131T              | Notebook    | [f8d2d274e1](https://linux-hardware.org/?probe=f8d2d274e1) | Oct 21, 2023 |
| Gigabyte      | Z77M-D3H                    | Desktop     | [0dcc624a0d](https://linux-hardware.org/?probe=0dcc624a0d) | Oct 21, 2023 |
| Lenovo        | ThinkPad E14 Gen 5 21JK0... | Notebook    | [f35c9d006e](https://linux-hardware.org/?probe=f35c9d006e) | Oct 20, 2023 |
| Lenovo        | Legion 5 Pro 16ITH6H 82J... | Notebook    | [79a2d6de1a](https://linux-hardware.org/?probe=79a2d6de1a) | Oct 19, 2023 |
| Dell          | XPS 13 9310                 | Notebook    | [3a6514e61a](https://linux-hardware.org/?probe=3a6514e61a) | Oct 19, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [dd8ebeda53](https://linux-hardware.org/?probe=dd8ebeda53) | Oct 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 4 21E30... | Notebook    | [52e7bc3407](https://linux-hardware.org/?probe=52e7bc3407) | Oct 18, 2023 |
| Lenovo        | Yoga Slim 7 Pro 16ARH7 8... | Notebook    | [6193aa3ed1](https://linux-hardware.org/?probe=6193aa3ed1) | Oct 17, 2023 |
| ASUSTek       | PRIME H410M-R               | Desktop     | [aa10d84f78](https://linux-hardware.org/?probe=aa10d84f78) | Oct 17, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [f53079d2c1](https://linux-hardware.org/?probe=f53079d2c1) | Oct 16, 2023 |
| HP            | ZBook Firefly 14 inch G1... | Notebook    | [dcb416db8f](https://linux-hardware.org/?probe=dcb416db8f) | Oct 16, 2023 |
| ASUSTek       | Zephyrus M GM501GS          | Notebook    | [ba4661ac35](https://linux-hardware.org/?probe=ba4661ac35) | Oct 15, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [51e04c2a8a](https://linux-hardware.org/?probe=51e04c2a8a) | Oct 15, 2023 |
| HP            | Pavilion dv7                | Notebook    | [feb4113e4e](https://linux-hardware.org/?probe=feb4113e4e) | Oct 15, 2023 |
| HP            | Pavilion dv7                | Notebook    | [6bb631736f](https://linux-hardware.org/?probe=6bb631736f) | Oct 15, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [70c2a81f9f](https://linux-hardware.org/?probe=70c2a81f9f) | Oct 14, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b2250f3c59](https://linux-hardware.org/?probe=b2250f3c59) | Oct 14, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [17b0ef31ee](https://linux-hardware.org/?probe=17b0ef31ee) | Oct 13, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9972c1fc42](https://linux-hardware.org/?probe=9972c1fc42) | Oct 11, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [b16ee3559a](https://linux-hardware.org/?probe=b16ee3559a) | Oct 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [e38dfab96d](https://linux-hardware.org/?probe=e38dfab96d) | Oct 11, 2023 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [41d5ccfd3f](https://linux-hardware.org/?probe=41d5ccfd3f) | Oct 11, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [7d1fea3001](https://linux-hardware.org/?probe=7d1fea3001) | Oct 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [749e1a7e28](https://linux-hardware.org/?probe=749e1a7e28) | Oct 09, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | Desktop     | [3e075f72d8](https://linux-hardware.org/?probe=3e075f72d8) | Oct 09, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [b82e5d0718](https://linux-hardware.org/?probe=b82e5d0718) | Oct 07, 2023 |
| UMAX          | N14R                        | Notebook    | [4ac10723f5](https://linux-hardware.org/?probe=4ac10723f5) | Oct 07, 2023 |
| UMAX          | N14R                        | Notebook    | [9852750745](https://linux-hardware.org/?probe=9852750745) | Oct 07, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [299eee42c7](https://linux-hardware.org/?probe=299eee42c7) | Oct 07, 2023 |
| Dell          | Latitude 5431               | Notebook    | [a85fc8f829](https://linux-hardware.org/?probe=a85fc8f829) | Oct 06, 2023 |
| HP            | EliteBook x360 1030 G4      | Convertible | [3c7f490b86](https://linux-hardware.org/?probe=3c7f490b86) | Oct 06, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [3b423be827](https://linux-hardware.org/?probe=3b423be827) | Oct 06, 2023 |
| HP            | EliteBook 655 15.6 inch ... | Notebook    | [7b888eeb58](https://linux-hardware.org/?probe=7b888eeb58) | Oct 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [3b55566de3](https://linux-hardware.org/?probe=3b55566de3) | Oct 05, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [59c0b6ce9c](https://linux-hardware.org/?probe=59c0b6ce9c) | Oct 04, 2023 |
| Samsung       | 550XBE/350XBE               | Notebook    | [442ef4b7be](https://linux-hardware.org/?probe=442ef4b7be) | Oct 04, 2023 |
| MSI           | Z370 PC PRO                 | Desktop     | [ec51b8fd0c](https://linux-hardware.org/?probe=ec51b8fd0c) | Oct 02, 2023 |
| ASUSTek       | A88XM-A/USB                 | Desktop     | [5a154d10af](https://linux-hardware.org/?probe=5a154d10af) | Oct 01, 2023 |
| Dell          | Latitude E6420              | Notebook    | [55c45fb7cb](https://linux-hardware.org/?probe=55c45fb7cb) | Oct 01, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [4575deef12](https://linux-hardware.org/?probe=4575deef12) | Sep 30, 2023 |
| Lenovo        | ThinkPad T440 20B7S1K400    | Notebook    | [fd03530876](https://linux-hardware.org/?probe=fd03530876) | Sep 30, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [2d1ada9dbe](https://linux-hardware.org/?probe=2d1ada9dbe) | Sep 30, 2023 |
| Sony          | VPCEB4J0E                   | Notebook    | [05864978df](https://linux-hardware.org/?probe=05864978df) | Sep 29, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [1b6440f722](https://linux-hardware.org/?probe=1b6440f722) | Sep 29, 2023 |
| Dell          | Precision 7710              | Notebook    | [89731f9b0e](https://linux-hardware.org/?probe=89731f9b0e) | Sep 29, 2023 |
| Dell          | Inspiron 5515               | Notebook    | [5889ba673d](https://linux-hardware.org/?probe=5889ba673d) | Sep 27, 2023 |
| Sony          | VPCEB4J0E                   | Notebook    | [354e2be55e](https://linux-hardware.org/?probe=354e2be55e) | Sep 27, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [a1fa543905](https://linux-hardware.org/?probe=a1fa543905) | Sep 27, 2023 |
| MSI           | X299 RAIDER 2018-10-08      | Desktop     | [8bccf1be8d](https://linux-hardware.org/?probe=8bccf1be8d) | Sep 26, 2023 |
| Acer          | Swift SF14-71T              | Notebook    | [10b657bd75](https://linux-hardware.org/?probe=10b657bd75) | Sep 25, 2023 |
| Dell          | Precision 7720              | Notebook    | [8cae4c9a31](https://linux-hardware.org/?probe=8cae4c9a31) | Sep 25, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [336d5fe8c8](https://linux-hardware.org/?probe=336d5fe8c8) | Sep 25, 2023 |
| Dell          | Latitude 7400               | Notebook    | [f537b79d15](https://linux-hardware.org/?probe=f537b79d15) | Sep 24, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [fa3021d826](https://linux-hardware.org/?probe=fa3021d826) | Sep 23, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [a6ff891fa1](https://linux-hardware.org/?probe=a6ff891fa1) | Sep 23, 2023 |
| MSI           | B450M MORTAR MAX            | Desktop     | [3b9bbcebb0](https://linux-hardware.org/?probe=3b9bbcebb0) | Sep 23, 2023 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [b58de0bed0](https://linux-hardware.org/?probe=b58de0bed0) | Sep 21, 2023 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [81d1af1a96](https://linux-hardware.org/?probe=81d1af1a96) | Sep 20, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [4bb581fb16](https://linux-hardware.org/?probe=4bb581fb16) | Sep 19, 2023 |
| Acer          | Aspire ES1-420              | Notebook    | [db308e1798](https://linux-hardware.org/?probe=db308e1798) | Sep 19, 2023 |
| Lenovo        | ThinkPad T480 20L6SCYF0P    | Notebook    | [c406bf7b56](https://linux-hardware.org/?probe=c406bf7b56) | Sep 18, 2023 |
| HP            | 158B                        | Desktop     | [d56ff45f03](https://linux-hardware.org/?probe=d56ff45f03) | Sep 17, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [c323f31788](https://linux-hardware.org/?probe=c323f31788) | Sep 17, 2023 |
| Lenovo        | NOK                         | Desktop     | [ead85a1003](https://linux-hardware.org/?probe=ead85a1003) | Sep 16, 2023 |
| ASUSTek       | Zenbook UX5401ZAS_UX5401... | Notebook    | [bc597f4c0c](https://linux-hardware.org/?probe=bc597f4c0c) | Sep 14, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [8f3c4bff98](https://linux-hardware.org/?probe=8f3c4bff98) | Sep 13, 2023 |
| Dell          | G3 3500                     | Notebook    | [293bbfe2d6](https://linux-hardware.org/?probe=293bbfe2d6) | Sep 12, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [ff31b68cf3](https://linux-hardware.org/?probe=ff31b68cf3) | Sep 12, 2023 |
| Gigabyte      | Z790 UD                     | Desktop     | [bcfc38f6da](https://linux-hardware.org/?probe=bcfc38f6da) | Sep 11, 2023 |
| Lenovo        | IdeaPad 3 15ARE05 81W4      | Notebook    | [53139247c9](https://linux-hardware.org/?probe=53139247c9) | Sep 10, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [1b79da7f45](https://linux-hardware.org/?probe=1b79da7f45) | Sep 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [a9caf49f0e](https://linux-hardware.org/?probe=a9caf49f0e) | Sep 09, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [2a7d4dfb14](https://linux-hardware.org/?probe=2a7d4dfb14) | Sep 09, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [db1e55d494](https://linux-hardware.org/?probe=db1e55d494) | Sep 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [e3152ede03](https://linux-hardware.org/?probe=e3152ede03) | Sep 08, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [04b9d6891a](https://linux-hardware.org/?probe=04b9d6891a) | Sep 08, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [62735c1cd9](https://linux-hardware.org/?probe=62735c1cd9) | Sep 07, 2023 |
| Lenovo        | 32E4 SDK0T76538 WIN 3556... | Mini pc     | [ac035f8420](https://linux-hardware.org/?probe=ac035f8420) | Sep 07, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [40b17904fa](https://linux-hardware.org/?probe=40b17904fa) | Sep 06, 2023 |
| Dell          | Latitude 7400               | Notebook    | [e1ea4eb614](https://linux-hardware.org/?probe=e1ea4eb614) | Sep 05, 2023 |
| HP            | EliteBook 845 14 inch G9... | Notebook    | [30bf3f1f45](https://linux-hardware.org/?probe=30bf3f1f45) | Sep 05, 2023 |
| UMAX          | 13Wr                        | Notebook    | [574937c731](https://linux-hardware.org/?probe=574937c731) | Sep 02, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [61a10ef907](https://linux-hardware.org/?probe=61a10ef907) | Sep 02, 2023 |
| HP            | Unknown                     | Notebook    | [3809d7ad85](https://linux-hardware.org/?probe=3809d7ad85) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [864a10779f](https://linux-hardware.org/?probe=864a10779f) | Sep 01, 2023 |
| HP            | 3032h                       | Desktop     | [7dfc9fa7a0](https://linux-hardware.org/?probe=7dfc9fa7a0) | Sep 01, 2023 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [8cc90dd6b0](https://linux-hardware.org/?probe=8cc90dd6b0) | Sep 01, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [628d865373](https://linux-hardware.org/?probe=628d865373) | Aug 31, 2023 |
| UMAX          | VisionBook 15Wg Plus        | Notebook    | [e5a1a106cb](https://linux-hardware.org/?probe=e5a1a106cb) | Aug 31, 2023 |
| ASUSTek       | ROG Strix G814JI_G814JI     | Notebook    | [96d825f112](https://linux-hardware.org/?probe=96d825f112) | Aug 31, 2023 |
| Lenovo        | ThinkPad L450 20DSS0LR00    | Notebook    | [a85743e60e](https://linux-hardware.org/?probe=a85743e60e) | Aug 31, 2023 |
| Fujitsu       | D2679-B1 S26361-D2679-Bx... | Desktop     | [81ae698cf8](https://linux-hardware.org/?probe=81ae698cf8) | Aug 31, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [80bebab849](https://linux-hardware.org/?probe=80bebab849) | Aug 31, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [362ee070d7](https://linux-hardware.org/?probe=362ee070d7) | Aug 30, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [3240f39404](https://linux-hardware.org/?probe=3240f39404) | Aug 30, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [14fce9ff7f](https://linux-hardware.org/?probe=14fce9ff7f) | Aug 30, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [ba9dd7a62d](https://linux-hardware.org/?probe=ba9dd7a62d) | Aug 29, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IAH7 ... | Notebook    | [d6bca74de6](https://linux-hardware.org/?probe=d6bca74de6) | Aug 29, 2023 |
| Fujitsu       | LIFEBOOK U9312              | Notebook    | [891b276812](https://linux-hardware.org/?probe=891b276812) | Aug 28, 2023 |
| ASUSTek       | K53E                        | Notebook    | [fa5eab9e81](https://linux-hardware.org/?probe=fa5eab9e81) | Aug 28, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [e3ca221ba9](https://linux-hardware.org/?probe=e3ca221ba9) | Aug 28, 2023 |
| Acer          | Aspire E1-532               | Notebook    | [037143c4fd](https://linux-hardware.org/?probe=037143c4fd) | Aug 27, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [0557e95830](https://linux-hardware.org/?probe=0557e95830) | Aug 27, 2023 |
| HP            | ProBook x360 435 G7         | Convertible | [127d78aea0](https://linux-hardware.org/?probe=127d78aea0) | Aug 26, 2023 |
| Google        | Robo                        | Notebook    | [dfa74d0961](https://linux-hardware.org/?probe=dfa74d0961) | Aug 26, 2023 |
| HP            | 802F                        | Desktop     | [6759058353](https://linux-hardware.org/?probe=6759058353) | Aug 25, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [c288ff6b78](https://linux-hardware.org/?probe=c288ff6b78) | Aug 25, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ae2d6ab9fd](https://linux-hardware.org/?probe=ae2d6ab9fd) | Aug 25, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [7fcd619af1](https://linux-hardware.org/?probe=7fcd619af1) | Aug 25, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [6cf9db7da7](https://linux-hardware.org/?probe=6cf9db7da7) | Aug 24, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [b84eb0a6fa](https://linux-hardware.org/?probe=b84eb0a6fa) | Aug 24, 2023 |
| HP            | ZBook 14 G2                 | Notebook    | [fcbebfc95a](https://linux-hardware.org/?probe=fcbebfc95a) | Aug 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [904e60e2d7](https://linux-hardware.org/?probe=904e60e2d7) | Aug 23, 2023 |
| Lenovo        | 313C SDK0J40697 WIN 3305... | Desktop     | [536f3c29b6](https://linux-hardware.org/?probe=536f3c29b6) | Aug 23, 2023 |
| ASRock        | TRX40 Creator               | Desktop     | [6c3b3d9727](https://linux-hardware.org/?probe=6c3b3d9727) | Aug 23, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [98669adc64](https://linux-hardware.org/?probe=98669adc64) | Aug 23, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [e751db6fd4](https://linux-hardware.org/?probe=e751db6fd4) | Aug 22, 2023 |
| Lenovo        | 3190 SDK0J40697 WIN 3305... | Mini pc     | [4945bd0d6d](https://linux-hardware.org/?probe=4945bd0d6d) | Aug 22, 2023 |
| Valve         | Jupiter                     | Notebook    | [57038f50cd](https://linux-hardware.org/?probe=57038f50cd) | Aug 20, 2023 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [681310709d](https://linux-hardware.org/?probe=681310709d) | Aug 19, 2023 |
| ECS           | 7AT-3LB                     | Desktop     | [fe545a2a23](https://linux-hardware.org/?probe=fe545a2a23) | Aug 19, 2023 |
| Intel         | NUC10i7FNB M38062-307       | Mini pc     | [9c749716e8](https://linux-hardware.org/?probe=9c749716e8) | Aug 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [722707e986](https://linux-hardware.org/?probe=722707e986) | Aug 18, 2023 |
| Gigabyte      | B450M H                     | Desktop     | [73867661a3](https://linux-hardware.org/?probe=73867661a3) | Aug 18, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [b8e5fd59d3](https://linux-hardware.org/?probe=b8e5fd59d3) | Aug 18, 2023 |
| MSI           | B250M MORTAR                | Desktop     | [fc97ccab18](https://linux-hardware.org/?probe=fc97ccab18) | Aug 17, 2023 |
| Dell          | Latitude 7440               | Notebook    | [aef57d5421](https://linux-hardware.org/?probe=aef57d5421) | Aug 17, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [e5618417ed](https://linux-hardware.org/?probe=e5618417ed) | Aug 16, 2023 |
| Lenovo        | IdeaPad Slim 5 14ABR8 82... | Notebook    | [1fcc89106f](https://linux-hardware.org/?probe=1fcc89106f) | Aug 15, 2023 |
| HP            | Laptop 17-cp0xxx            | Notebook    | [620d12291b](https://linux-hardware.org/?probe=620d12291b) | Aug 15, 2023 |
| HP            | 09CCh                       | Desktop     | [947fb1edcb](https://linux-hardware.org/?probe=947fb1edcb) | Aug 15, 2023 |
| Lenovo        | ThinkPad X250 20CM001RMC    | Notebook    | [618a7e3e29](https://linux-hardware.org/?probe=618a7e3e29) | Aug 14, 2023 |
| Dell          | XPS 13 7390                 | Notebook    | [f4e6886bd8](https://linux-hardware.org/?probe=f4e6886bd8) | Aug 13, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [4775c7e602](https://linux-hardware.org/?probe=4775c7e602) | Aug 13, 2023 |
| AMD           | A690G M2+                   | Desktop     | [4179510c0b](https://linux-hardware.org/?probe=4179510c0b) | Aug 13, 2023 |
| HP            | 09CCh                       | Desktop     | [15bfdf7213](https://linux-hardware.org/?probe=15bfdf7213) | Aug 12, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [475b07d2dc](https://linux-hardware.org/?probe=475b07d2dc) | Aug 12, 2023 |
| HP            | 250 G3                      | Notebook    | [6ba303bc6b](https://linux-hardware.org/?probe=6ba303bc6b) | Aug 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ffa9b97bf7](https://linux-hardware.org/?probe=ffa9b97bf7) | Aug 10, 2023 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [82dde7d058](https://linux-hardware.org/?probe=82dde7d058) | Aug 10, 2023 |
| HP            | ZBook Studio 16 inch G9 ... | Notebook    | [e1462f1e3a](https://linux-hardware.org/?probe=e1462f1e3a) | Aug 10, 2023 |
| Lenovo        | IdeaPad 5 14ABA7 82SE       | Notebook    | [6415840d5b](https://linux-hardware.org/?probe=6415840d5b) | Aug 09, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [bd9f67ee72](https://linux-hardware.org/?probe=bd9f67ee72) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | Notebook    | [30d8fefda4](https://linux-hardware.org/?probe=30d8fefda4) | Aug 07, 2023 |
| Acer          | Swift SF514-53T             | Notebook    | [f1cef350fb](https://linux-hardware.org/?probe=f1cef350fb) | Aug 07, 2023 |
| Lenovo        | IdeaPad 510-15ISK 80SR      | Notebook    | [b69ff09aa4](https://linux-hardware.org/?probe=b69ff09aa4) | Aug 05, 2023 |
| ASUSTek       | ROG STRIX B450-E GAMING     | Desktop     | [401fdc46ef](https://linux-hardware.org/?probe=401fdc46ef) | Aug 05, 2023 |
| Dell          | Latitude E6420              | Notebook    | [3636e69adb](https://linux-hardware.org/?probe=3636e69adb) | Aug 05, 2023 |
| Acer          | Aspire E5-572G              | Notebook    | [846dce7b1b](https://linux-hardware.org/?probe=846dce7b1b) | Aug 05, 2023 |
| Dell          | Latitude E5500              | Notebook    | [95ddcb321c](https://linux-hardware.org/?probe=95ddcb321c) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [12ee4ed8f6](https://linux-hardware.org/?probe=12ee4ed8f6) | Aug 05, 2023 |
| Acer          | Swift SF514-54GT            | Notebook    | [5a2ed78e49](https://linux-hardware.org/?probe=5a2ed78e49) | Aug 05, 2023 |
| Dell          | Latitude 7400               | Notebook    | [48e2858e56](https://linux-hardware.org/?probe=48e2858e56) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L50000MC    | Notebook    | [341698801e](https://linux-hardware.org/?probe=341698801e) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [195716ccf3](https://linux-hardware.org/?probe=195716ccf3) | Aug 04, 2023 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [6495cadf19](https://linux-hardware.org/?probe=6495cadf19) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [5a9a057759](https://linux-hardware.org/?probe=5a9a057759) | Aug 04, 2023 |
| Dell          | Latitude 7440               | Notebook    | [367f14eae6](https://linux-hardware.org/?probe=367f14eae6) | Aug 04, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [1317097350](https://linux-hardware.org/?probe=1317097350) | Aug 03, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [e5be227d11](https://linux-hardware.org/?probe=e5be227d11) | Aug 03, 2023 |
| Dell          | 0CRH6C A02                  | Desktop     | [141928d8e2](https://linux-hardware.org/?probe=141928d8e2) | Aug 02, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [2d1e78ec7e](https://linux-hardware.org/?probe=2d1e78ec7e) | Aug 02, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [589f0a8599](https://linux-hardware.org/?probe=589f0a8599) | Aug 01, 2023 |
| Acer          | Aspire 1810TZ               | Notebook    | [8cbec4eb45](https://linux-hardware.org/?probe=8cbec4eb45) | Jul 31, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [5ce91f2c11](https://linux-hardware.org/?probe=5ce91f2c11) | Jul 30, 2023 |
| Lenovo        | V15 G3 IAP 82TT             | Notebook    | [6ec734b217](https://linux-hardware.org/?probe=6ec734b217) | Jul 30, 2023 |
| Acer          | Aspire 5742                 | Notebook    | [37be5a1c80](https://linux-hardware.org/?probe=37be5a1c80) | Jul 30, 2023 |
| ASRock        | 4CoreDual-SATA2             | Desktop     | [44438ab71e](https://linux-hardware.org/?probe=44438ab71e) | Jul 30, 2023 |
| HP            | 843B                        | Desktop     | [c570a7c5f2](https://linux-hardware.org/?probe=c570a7c5f2) | Jul 29, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [a7b390cdf4](https://linux-hardware.org/?probe=a7b390cdf4) | Jul 29, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [4baa3fe63b](https://linux-hardware.org/?probe=4baa3fe63b) | Jul 29, 2023 |
| Lenovo        | Yoga 7 14ARP8 82YM          | Convertible | [254354d9aa](https://linux-hardware.org/?probe=254354d9aa) | Jul 29, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [d500093891](https://linux-hardware.org/?probe=d500093891) | Jul 28, 2023 |
| Google        | Edgar                       | Notebook    | [7e19b1e507](https://linux-hardware.org/?probe=7e19b1e507) | Jul 28, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [f5497a92cf](https://linux-hardware.org/?probe=f5497a92cf) | Jul 28, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fd41467554](https://linux-hardware.org/?probe=fd41467554) | Jul 28, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [ccfe4b2234](https://linux-hardware.org/?probe=ccfe4b2234) | Jul 27, 2023 |
| Acer          | Aspire A315-24P             | Notebook    | [6799c4be4a](https://linux-hardware.org/?probe=6799c4be4a) | Jul 27, 2023 |
| Toshiba       | Satellite A135              | Notebook    | [91f5602ed7](https://linux-hardware.org/?probe=91f5602ed7) | Jul 26, 2023 |
| HP            | 8169                        | Desktop     | [f2885ba2de](https://linux-hardware.org/?probe=f2885ba2de) | Jul 26, 2023 |
| Lenovo        | ThinkBook 15 G4 IAP 21DJ    | Notebook    | [74adf4cb3d](https://linux-hardware.org/?probe=74adf4cb3d) | Jul 26, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [9f384d336d](https://linux-hardware.org/?probe=9f384d336d) | Jul 23, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [8e3dbf7ff9](https://linux-hardware.org/?probe=8e3dbf7ff9) | Jul 23, 2023 |
| Dell          | Latitude E7440              | Notebook    | [ffa2aad2b5](https://linux-hardware.org/?probe=ffa2aad2b5) | Jul 21, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [2c2c4bdcf2](https://linux-hardware.org/?probe=2c2c4bdcf2) | Jul 21, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [4f00ba88de](https://linux-hardware.org/?probe=4f00ba88de) | Jul 21, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [6a048ba2cc](https://linux-hardware.org/?probe=6a048ba2cc) | Jul 21, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [0d5bd8b2f2](https://linux-hardware.org/?probe=0d5bd8b2f2) | Jul 20, 2023 |
| AMI           | Intel                       | Convertible | [896ed95f63](https://linux-hardware.org/?probe=896ed95f63) | Jul 19, 2023 |
| MSI           | IONA                        | Desktop     | [7b8b6c38e1](https://linux-hardware.org/?probe=7b8b6c38e1) | Jul 18, 2023 |
| Dell          | 02YYK5 A01                  | Desktop     | [4ad55cf9da](https://linux-hardware.org/?probe=4ad55cf9da) | Jul 16, 2023 |
| Lenovo        | B5400 80B6QB0               | Notebook    | [7108435241](https://linux-hardware.org/?probe=7108435241) | Jul 15, 2023 |
| ASUSTek       | J1800I-A                    | Desktop     | [ce7f031b0a](https://linux-hardware.org/?probe=ce7f031b0a) | Jul 14, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [cf9bdab1ee](https://linux-hardware.org/?probe=cf9bdab1ee) | Jul 13, 2023 |
| Lenovo        | IdeaPad S130-11IGM 81J1     | Notebook    | [f742573138](https://linux-hardware.org/?probe=f742573138) | Jul 12, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [b3770db2e8](https://linux-hardware.org/?probe=b3770db2e8) | Jul 12, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [d7d8d93ac1](https://linux-hardware.org/?probe=d7d8d93ac1) | Jul 10, 2023 |
| ASUSTek       | P7P55D DELUXE               | Desktop     | [ecba1dae0a](https://linux-hardware.org/?probe=ecba1dae0a) | Jul 09, 2023 |
| Notebook      | NP5x_NP6x_NP7xRNJ_RNH       | Notebook    | [7663e77bff](https://linux-hardware.org/?probe=7663e77bff) | Jul 09, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [003c30f690](https://linux-hardware.org/?probe=003c30f690) | Jul 09, 2023 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [76a4853c56](https://linux-hardware.org/?probe=76a4853c56) | Jul 08, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [624fca7465](https://linux-hardware.org/?probe=624fca7465) | Jul 07, 2023 |
| Lenovo        | ThinkPad T14s Gen 2i 20W... | Notebook    | [d09af80a65](https://linux-hardware.org/?probe=d09af80a65) | Jul 07, 2023 |
| ASUSTek       | ASUS EXPERTBOOK B2502CBA... | Notebook    | [397adc6b70](https://linux-hardware.org/?probe=397adc6b70) | Jul 06, 2023 |
| Lenovo        | ThinkPad E570 20H50074MC    | Notebook    | [029e84bf8a](https://linux-hardware.org/?probe=029e84bf8a) | Jul 06, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [ef4d169d77](https://linux-hardware.org/?probe=ef4d169d77) | Jul 05, 2023 |
| ASUSTek       | TUF B450-PRO GAMING         | Desktop     | [33e4bac631](https://linux-hardware.org/?probe=33e4bac631) | Jul 05, 2023 |
| Dell          | 08NPPY A00                  | Desktop     | [b0432f19ba](https://linux-hardware.org/?probe=b0432f19ba) | Jul 05, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [bedadd4478](https://linux-hardware.org/?probe=bedadd4478) | Jul 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1e57d7c40d](https://linux-hardware.org/?probe=1e57d7c40d) | Jul 05, 2023 |
| HP            | EliteBook 8770w             | Notebook    | [8f298fa9aa](https://linux-hardware.org/?probe=8f298fa9aa) | Jul 04, 2023 |
| Lenovo        | ThinkPad T14 Gen 2a 20XL... | Notebook    | [73e054c849](https://linux-hardware.org/?probe=73e054c849) | Jul 04, 2023 |
| Lenovo        | ThinkPad P1 Gen 4i 20Y4S... | Notebook    | [5d2bd9c3ce](https://linux-hardware.org/?probe=5d2bd9c3ce) | Jul 04, 2023 |
| Dell          | 05XGC8 A01                  | Desktop     | [eada4fe260](https://linux-hardware.org/?probe=eada4fe260) | Jul 02, 2023 |
| AMI           | Intel                       | Notebook    | [65aafdb0b0](https://linux-hardware.org/?probe=65aafdb0b0) | Jul 02, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [7beeaf657d](https://linux-hardware.org/?probe=7beeaf657d) | Jul 02, 2023 |
| Dell          | 0T656F A02                  | Desktop     | [e9b879f3ff](https://linux-hardware.org/?probe=e9b879f3ff) | Jul 02, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [7bdc183ddc](https://linux-hardware.org/?probe=7bdc183ddc) | Jul 02, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [05394ee8a5](https://linux-hardware.org/?probe=05394ee8a5) | Jul 02, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [37a73c8939](https://linux-hardware.org/?probe=37a73c8939) | Jul 01, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [c5820f8068](https://linux-hardware.org/?probe=c5820f8068) | Jul 01, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [f22f547276](https://linux-hardware.org/?probe=f22f547276) | Jul 01, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [07ab83bef1](https://linux-hardware.org/?probe=07ab83bef1) | Jun 30, 2023 |
| MSI           | G41M-P33 Combo              | Desktop     | [fcf9a0fd47](https://linux-hardware.org/?probe=fcf9a0fd47) | Jun 30, 2023 |
| UMAX          | VisionBook-N12R             | Notebook    | [6144190349](https://linux-hardware.org/?probe=6144190349) | Jun 30, 2023 |
| Acer          | NC-A515-51G-59DM            | Notebook    | [a521f2cc60](https://linux-hardware.org/?probe=a521f2cc60) | Jun 29, 2023 |
| ASUSTek       | H87M-E                      | Desktop     | [7e7af2948c](https://linux-hardware.org/?probe=7e7af2948c) | Jun 29, 2023 |
| Gigabyte      | H410M H V3                  | Desktop     | [5496b9130e](https://linux-hardware.org/?probe=5496b9130e) | Jun 29, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [607da926f3](https://linux-hardware.org/?probe=607da926f3) | Jun 28, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [8112f38f33](https://linux-hardware.org/?probe=8112f38f33) | Jun 27, 2023 |
| Lenovo        | ThinkCentre M58p 3285A1G    | Desktop     | [d5e4ce2efa](https://linux-hardware.org/?probe=d5e4ce2efa) | Jun 25, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [223911e8f0](https://linux-hardware.org/?probe=223911e8f0) | Jun 25, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [234a73d6b0](https://linux-hardware.org/?probe=234a73d6b0) | Jun 23, 2023 |
| MSI           | A320M GAMING PRO            | Desktop     | [70b7839ea8](https://linux-hardware.org/?probe=70b7839ea8) | Jun 23, 2023 |
| Lenovo        | G570 20079                  | Notebook    | [5879c3e9ad](https://linux-hardware.org/?probe=5879c3e9ad) | Jun 22, 2023 |
| ASUSTek       | GL552VX                     | Notebook    | [348e36123f](https://linux-hardware.org/?probe=348e36123f) | Jun 22, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [51b4c8d9ef](https://linux-hardware.org/?probe=51b4c8d9ef) | Jun 22, 2023 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [61ba243843](https://linux-hardware.org/?probe=61ba243843) | Jun 21, 2023 |
| Lenovo        | 01GR176                     | Server      | [6d28cbec97](https://linux-hardware.org/?probe=6d28cbec97) | Jun 21, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [9e0ba5032b](https://linux-hardware.org/?probe=9e0ba5032b) | Jun 21, 2023 |
| Lenovo        | 310C SDK0J40697 WIN 3305... | Mini pc     | [0aa3b8d433](https://linux-hardware.org/?probe=0aa3b8d433) | Jun 21, 2023 |
| ASRock        | X570 Extreme4               | Desktop     | [3ff2c9e4cc](https://linux-hardware.org/?probe=3ff2c9e4cc) | Jun 21, 2023 |
| Shuttle       | FX21V10                     | Desktop     | [d77f55da92](https://linux-hardware.org/?probe=d77f55da92) | Jun 19, 2023 |
| Shuttle       | FX21V10                     | Desktop     | [71a0effa3a](https://linux-hardware.org/?probe=71a0effa3a) | Jun 19, 2023 |
| Acer          | Aspire ES1-420              | Notebook    | [76aab864d4](https://linux-hardware.org/?probe=76aab864d4) | Jun 19, 2023 |
| Dell          | Latitude E6540              | Notebook    | [3721b0046f](https://linux-hardware.org/?probe=3721b0046f) | Jun 19, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [0806a6be0a](https://linux-hardware.org/?probe=0806a6be0a) | Jun 19, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [0054d0c92e](https://linux-hardware.org/?probe=0054d0c92e) | Jun 18, 2023 |
| ASUSTek       | A55BM-E                     | Desktop     | [98b3d14b06](https://linux-hardware.org/?probe=98b3d14b06) | Jun 17, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d9e1222bc3](https://linux-hardware.org/?probe=d9e1222bc3) | Jun 17, 2023 |
| Gigabyte      | H61M-S2PV                   | Desktop     | [706eeef80f](https://linux-hardware.org/?probe=706eeef80f) | Jun 15, 2023 |
| Dell          | Latitude 5420               | Notebook    | [d3327c76f1](https://linux-hardware.org/?probe=d3327c76f1) | Jun 15, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [17c4d68066](https://linux-hardware.org/?probe=17c4d68066) | Jun 14, 2023 |
| Acer          | Aspire ES1-420              | Notebook    | [5c3a2078ca](https://linux-hardware.org/?probe=5c3a2078ca) | Jun 14, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [c74f83bbea](https://linux-hardware.org/?probe=c74f83bbea) | Jun 13, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [77ce1af9f8](https://linux-hardware.org/?probe=77ce1af9f8) | Jun 13, 2023 |
| MSI           | IONA                        | Desktop     | [86535af79b](https://linux-hardware.org/?probe=86535af79b) | Jun 13, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [4d019c4a6f](https://linux-hardware.org/?probe=4d019c4a6f) | Jun 13, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [edf817eef9](https://linux-hardware.org/?probe=edf817eef9) | Jun 12, 2023 |
| Lenovo        | ThinkPad X1 Nano Gen 2 2... | Notebook    | [5c98700539](https://linux-hardware.org/?probe=5c98700539) | Jun 12, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [f6e70e460f](https://linux-hardware.org/?probe=f6e70e460f) | Jun 11, 2023 |
| Dell          | Latitude 5420               | Notebook    | [956a995580](https://linux-hardware.org/?probe=956a995580) | Jun 09, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [09ba95bf3b](https://linux-hardware.org/?probe=09ba95bf3b) | Jun 08, 2023 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [a2c63b86b0](https://linux-hardware.org/?probe=a2c63b86b0) | Jun 08, 2023 |
| ASUSTek       | PN51-E1                     | Mini pc     | [0f41ab04b6](https://linux-hardware.org/?probe=0f41ab04b6) | Jun 07, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [9d0aa12b81](https://linux-hardware.org/?probe=9d0aa12b81) | Jun 06, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [92d0de412b](https://linux-hardware.org/?probe=92d0de412b) | Jun 06, 2023 |
| Dell          | Latitude 7400               | Notebook    | [9968377d89](https://linux-hardware.org/?probe=9968377d89) | Jun 06, 2023 |
| MSI           | H110M ECO                   | Desktop     | [4215fc5993](https://linux-hardware.org/?probe=4215fc5993) | Jun 05, 2023 |
| Acer          | Nitro AN515-44              | Notebook    | [d7a2c59432](https://linux-hardware.org/?probe=d7a2c59432) | Jun 05, 2023 |
| Gigabyte      | B360M HD3                   | Desktop     | [fcb1b60578](https://linux-hardware.org/?probe=fcb1b60578) | Jun 04, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [84f237f434](https://linux-hardware.org/?probe=84f237f434) | Jun 04, 2023 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [e64369d2ec](https://linux-hardware.org/?probe=e64369d2ec) | Jun 03, 2023 |
| Gigabyte      | H67MA-USB3-B3               | Desktop     | [1908e7e6f5](https://linux-hardware.org/?probe=1908e7e6f5) | Jun 03, 2023 |
| Lenovo        | ThinkPad T420 4236WQD       | Notebook    | [69a63f31e1](https://linux-hardware.org/?probe=69a63f31e1) | Jun 03, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [7ae3c54a4c](https://linux-hardware.org/?probe=7ae3c54a4c) | Jun 03, 2023 |
| Timi          | A35S                        | Notebook    | [c9ce47a446](https://linux-hardware.org/?probe=c9ce47a446) | Jun 01, 2023 |
| HP            | 158A                        | Desktop     | [39d4ab7307](https://linux-hardware.org/?probe=39d4ab7307) | May 31, 2023 |
| ASRock        | B550M Steel Legend          | Desktop     | [ab97cb7f09](https://linux-hardware.org/?probe=ab97cb7f09) | May 30, 2023 |
| Intel         | NUC11TNBi5 M11904-404       | Mini pc     | [b706fad8dc](https://linux-hardware.org/?probe=b706fad8dc) | May 30, 2023 |
| Gigabyte      | X399 AORUS PRO-CF           | Desktop     | [b00cd1c84e](https://linux-hardware.org/?probe=b00cd1c84e) | May 30, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [b3966a1d81](https://linux-hardware.org/?probe=b3966a1d81) | May 30, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [ad3464fd76](https://linux-hardware.org/?probe=ad3464fd76) | May 30, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [643710864a](https://linux-hardware.org/?probe=643710864a) | May 30, 2023 |
| Lenovo        | ThinkPad T480 20L6S42000    | Notebook    | [ea6330526c](https://linux-hardware.org/?probe=ea6330526c) | May 29, 2023 |
| Gigabyte      | Z690 UD                     | Desktop     | [feab206ef4](https://linux-hardware.org/?probe=feab206ef4) | May 29, 2023 |
| ASRock        | X670E Taichi Carrara        | Desktop     | [7b001db11a](https://linux-hardware.org/?probe=7b001db11a) | May 29, 2023 |
| Acer          | Aspire 7540                 | Notebook    | [82fcb3124c](https://linux-hardware.org/?probe=82fcb3124c) | May 28, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [56fca4583d](https://linux-hardware.org/?probe=56fca4583d) | May 28, 2023 |
| Lenovo        | ThinkPad P51 20HJS01Q04     | Notebook    | [520eb0074c](https://linux-hardware.org/?probe=520eb0074c) | May 26, 2023 |
| Lenovo        | ThinkPad T490 20N3S5DQ02    | Notebook    | [bb00a96df8](https://linux-hardware.org/?probe=bb00a96df8) | May 25, 2023 |
| Unknown       | Unknown                     | Notebook    | [cfaffcaa0a](https://linux-hardware.org/?probe=cfaffcaa0a) | May 25, 2023 |
| Dell          | G15 5511                    | Notebook    | [3876065a3e](https://linux-hardware.org/?probe=3876065a3e) | May 24, 2023 |
| ASUSTek       | ASUS BR1100FKA BR1100FKA... | Convertible | [84b7538837](https://linux-hardware.org/?probe=84b7538837) | May 23, 2023 |
| Dell          | G5 5587                     | Notebook    | [18faf1497f](https://linux-hardware.org/?probe=18faf1497f) | May 23, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AH0... | Notebook    | [2fffd70abb](https://linux-hardware.org/?probe=2fffd70abb) | May 23, 2023 |
| HP            | 1495                        | Desktop     | [200cab3da9](https://linux-hardware.org/?probe=200cab3da9) | May 23, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [7e8b42ab5f](https://linux-hardware.org/?probe=7e8b42ab5f) | May 22, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [6e87c1ac87](https://linux-hardware.org/?probe=6e87c1ac87) | May 21, 2023 |
| Acer          | TravelMate Spin P414RN-4... | Convertible | [cb8bc926b8](https://linux-hardware.org/?probe=cb8bc926b8) | May 21, 2023 |
| HP            | 2B5E                        | Desktop     | [a221629f4d](https://linux-hardware.org/?probe=a221629f4d) | May 21, 2023 |
| Dell          | G15 5511                    | Notebook    | [ad4c2a0521](https://linux-hardware.org/?probe=ad4c2a0521) | May 21, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0f8329fecb](https://linux-hardware.org/?probe=0f8329fecb) | May 20, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [5da7add39a](https://linux-hardware.org/?probe=5da7add39a) | May 20, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [09ae9aca26](https://linux-hardware.org/?probe=09ae9aca26) | May 19, 2023 |
| Acer          | TravelMate Spin P414RN-4... | Convertible | [69d4abb6e4](https://linux-hardware.org/?probe=69d4abb6e4) | May 18, 2023 |
| HP            | ZBook Fury 16 G9 Mobile ... | Notebook    | [a74f787d52](https://linux-hardware.org/?probe=a74f787d52) | May 18, 2023 |
| ASUSTek       | PRIME B660M-A WIFI D4       | Desktop     | [c3626b71ae](https://linux-hardware.org/?probe=c3626b71ae) | May 18, 2023 |
| Lenovo        | 36C8 SDK0J40700 WIN 3258... | Desktop     | [166ec29ce0](https://linux-hardware.org/?probe=166ec29ce0) | May 18, 2023 |
| HP            | ProBook 4540s               | Notebook    | [1ea4f5cce0](https://linux-hardware.org/?probe=1ea4f5cce0) | May 18, 2023 |
| MSI           | MAG B760M MORTAR WIFI       | Desktop     | [f7c208d0f0](https://linux-hardware.org/?probe=f7c208d0f0) | May 16, 2023 |
| Dell          | Latitude 5521               | Notebook    | [9f671f21c1](https://linux-hardware.org/?probe=9f671f21c1) | May 16, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X160... | Notebook    | [b4e8e5504e](https://linux-hardware.org/?probe=b4e8e5504e) | May 15, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [1effa68567](https://linux-hardware.org/?probe=1effa68567) | May 15, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [c12ae2e393](https://linux-hardware.org/?probe=c12ae2e393) | May 15, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [14aeaeafe8](https://linux-hardware.org/?probe=14aeaeafe8) | May 15, 2023 |
| Lenovo        | NOK                         | Desktop     | [9c6f0bae8f](https://linux-hardware.org/?probe=9c6f0bae8f) | May 14, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [53f535546a](https://linux-hardware.org/?probe=53f535546a) | May 12, 2023 |
| Dell          | Latitude 7400               | Notebook    | [14de9baf53](https://linux-hardware.org/?probe=14de9baf53) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [5248735c71](https://linux-hardware.org/?probe=5248735c71) | May 12, 2023 |
| Dell          | Vostro 5620                 | Notebook    | [daa5b232fc](https://linux-hardware.org/?probe=daa5b232fc) | May 12, 2023 |
| eMachines     | E620                        | Notebook    | [827a81facc](https://linux-hardware.org/?probe=827a81facc) | May 11, 2023 |
| TUXEDO        | Polaris 15 AMD Gen1         | Notebook    | [81e75bd6e7](https://linux-hardware.org/?probe=81e75bd6e7) | May 11, 2023 |
| Lenovo        | IdeaPad Duet 3 10IGL5 82... | Tablet      | [e63410f299](https://linux-hardware.org/?probe=e63410f299) | May 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [c941da38cd](https://linux-hardware.org/?probe=c941da38cd) | May 08, 2023 |
| MSI           | H81M-P33                    | Desktop     | [b5c0679341](https://linux-hardware.org/?probe=b5c0679341) | May 08, 2023 |
| Dell          | Latitude E7450              | Notebook    | [0eff8f87c6](https://linux-hardware.org/?probe=0eff8f87c6) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [953d03df07](https://linux-hardware.org/?probe=953d03df07) | May 08, 2023 |
| Fujitsu Si... | LIFEBOOK S6420              | Notebook    | [ee52ca7ce5](https://linux-hardware.org/?probe=ee52ca7ce5) | May 08, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b979325eea](https://linux-hardware.org/?probe=b979325eea) | May 07, 2023 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [701907636a](https://linux-hardware.org/?probe=701907636a) | May 06, 2023 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [288e495c16](https://linux-hardware.org/?probe=288e495c16) | May 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [61a2726a1d](https://linux-hardware.org/?probe=61a2726a1d) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [0767486bb6](https://linux-hardware.org/?probe=0767486bb6) | May 04, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IV... | Notebook    | [3c6e20e260](https://linux-hardware.org/?probe=3c6e20e260) | May 04, 2023 |
| Valve         | Jupiter                     | Notebook    | [1f41754528](https://linux-hardware.org/?probe=1f41754528) | May 03, 2023 |
| Apple         | MacBookAir3,1               | Notebook    | [97d802a5d6](https://linux-hardware.org/?probe=97d802a5d6) | May 03, 2023 |
| Lenovo        | ThinkPad W541 20EGS0B010    | Notebook    | [3f87bce0eb](https://linux-hardware.org/?probe=3f87bce0eb) | May 01, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [ab48e66c38](https://linux-hardware.org/?probe=ab48e66c38) | May 01, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [1fb0ca13ff](https://linux-hardware.org/?probe=1fb0ca13ff) | May 01, 2023 |
| Gigabyte      | B660M DS3H DDR4             | Desktop     | [0e035d415e](https://linux-hardware.org/?probe=0e035d415e) | May 01, 2023 |
| Acer          | Extensa 5620                | Notebook    | [415396fa78](https://linux-hardware.org/?probe=415396fa78) | Apr 30, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [e0367e684f](https://linux-hardware.org/?probe=e0367e684f) | Apr 28, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [fed0a1a719](https://linux-hardware.org/?probe=fed0a1a719) | Apr 28, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e2c8068a7d](https://linux-hardware.org/?probe=e2c8068a7d) | Apr 28, 2023 |
| Lenovo        | NOK                         | Desktop     | [cf3db26781](https://linux-hardware.org/?probe=cf3db26781) | Apr 28, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [92be2563a8](https://linux-hardware.org/?probe=92be2563a8) | Apr 28, 2023 |
| Acer          | Aspire E1-572G              | Notebook    | [6c35501215](https://linux-hardware.org/?probe=6c35501215) | Apr 27, 2023 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [486535a4d3](https://linux-hardware.org/?probe=486535a4d3) | Apr 27, 2023 |
| TUXEDO        | Polaris AMD Gen3 (CZN)      | Notebook    | [ca568572da](https://linux-hardware.org/?probe=ca568572da) | Apr 26, 2023 |
| Dell          | Inspiron 3793               | Notebook    | [f9d337a0a1](https://linux-hardware.org/?probe=f9d337a0a1) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | Notebook    | [fa228f68e4](https://linux-hardware.org/?probe=fa228f68e4) | Apr 26, 2023 |
| ASUSTek       | G750JS                      | Notebook    | [33bc801258](https://linux-hardware.org/?probe=33bc801258) | Apr 26, 2023 |
| HP            | ProBook 4540s               | Notebook    | [ac831756d0](https://linux-hardware.org/?probe=ac831756d0) | Apr 26, 2023 |
| Valve         | Jupiter                     | Notebook    | [9b44e9bc2c](https://linux-hardware.org/?probe=9b44e9bc2c) | Apr 25, 2023 |
| Valve         | Jupiter                     | Notebook    | [7c7421ffeb](https://linux-hardware.org/?probe=7c7421ffeb) | Apr 25, 2023 |
| Dell          | System XPS L502X            | Notebook    | [4fd4992d0f](https://linux-hardware.org/?probe=4fd4992d0f) | Apr 24, 2023 |
| HP            | ProBook 4540s               | Notebook    | [db866a1036](https://linux-hardware.org/?probe=db866a1036) | Apr 24, 2023 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [68d1859c93](https://linux-hardware.org/?probe=68d1859c93) | Apr 23, 2023 |
| ASUSTek       | ROG STRIX B450-I GAMING     | Desktop     | [1cc955413f](https://linux-hardware.org/?probe=1cc955413f) | Apr 23, 2023 |
| Pegatron      | 2AB5                        | Desktop     | [5f771d8ee5](https://linux-hardware.org/?probe=5f771d8ee5) | Apr 23, 2023 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [db069c8b89](https://linux-hardware.org/?probe=db069c8b89) | Apr 21, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [91f538e2ab](https://linux-hardware.org/?probe=91f538e2ab) | Apr 21, 2023 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [085b87dc27](https://linux-hardware.org/?probe=085b87dc27) | Apr 21, 2023 |
| UMAX          | VisionBook 14Wa Pro         | Notebook    | [525241657b](https://linux-hardware.org/?probe=525241657b) | Apr 20, 2023 |
| UMAX          | VisionBook 14Wa Pro         | Notebook    | [07e2728dfe](https://linux-hardware.org/?probe=07e2728dfe) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [42ca23ca64](https://linux-hardware.org/?probe=42ca23ca64) | Apr 20, 2023 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [e315ba7088](https://linux-hardware.org/?probe=e315ba7088) | Apr 20, 2023 |
| Lenovo        | ThinkPad P52 20MAS5KM00     | Notebook    | [06ab19cc37](https://linux-hardware.org/?probe=06ab19cc37) | Apr 20, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [ec0b554256](https://linux-hardware.org/?probe=ec0b554256) | Apr 19, 2023 |
| HP            | Laptop 15-db1xxx            | Notebook    | [f158ac4161](https://linux-hardware.org/?probe=f158ac4161) | Apr 17, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [980c6d63d6](https://linux-hardware.org/?probe=980c6d63d6) | Apr 16, 2023 |
| Acer          | Aspire ES1-731G             | Notebook    | [1ef0f89c83](https://linux-hardware.org/?probe=1ef0f89c83) | Apr 15, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [b6615d2b7b](https://linux-hardware.org/?probe=b6615d2b7b) | Apr 15, 2023 |
| UMAX          | VisionBook 15Wg Plus        | Notebook    | [59d15de09e](https://linux-hardware.org/?probe=59d15de09e) | Apr 15, 2023 |
| Gigabyte      | AX370-Gaming K7 se3         | Desktop     | [5439790362](https://linux-hardware.org/?probe=5439790362) | Apr 15, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [429e68a4ac](https://linux-hardware.org/?probe=429e68a4ac) | Apr 14, 2023 |
| ASUSTek       | TUF Gaming X670E-PLUS       | Desktop     | [9518f3e6d8](https://linux-hardware.org/?probe=9518f3e6d8) | Apr 13, 2023 |
| HP            | ProBook 450 G6              | Notebook    | [3364cf411c](https://linux-hardware.org/?probe=3364cf411c) | Apr 13, 2023 |
| Acer          | Aspire one                  | Notebook    | [481024a7cb](https://linux-hardware.org/?probe=481024a7cb) | Apr 12, 2023 |
| Gigabyte      | AX370-Gaming K7 se3         | Desktop     | [ef5cbba147](https://linux-hardware.org/?probe=ef5cbba147) | Apr 12, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [9a592d3392](https://linux-hardware.org/?probe=9a592d3392) | Apr 11, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [8a78c5b08f](https://linux-hardware.org/?probe=8a78c5b08f) | Apr 11, 2023 |
| Lenovo        | Dory CRB                    | Desktop     | [cab4258e1b](https://linux-hardware.org/?probe=cab4258e1b) | Apr 11, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fff8cbca92](https://linux-hardware.org/?probe=fff8cbca92) | Apr 10, 2023 |
| Lenovo        | ThinkCentre M90p 5536W67    | Desktop     | [f67448dd99](https://linux-hardware.org/?probe=f67448dd99) | Apr 09, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA401IH... | Notebook    | [bf531c6e34](https://linux-hardware.org/?probe=bf531c6e34) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [2652354b7a](https://linux-hardware.org/?probe=2652354b7a) | Apr 09, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [e5393f2dd6](https://linux-hardware.org/?probe=e5393f2dd6) | Apr 07, 2023 |
| Dell          | 0J3C2F A00                  | Desktop     | [e2c3600e8b](https://linux-hardware.org/?probe=e2c3600e8b) | Apr 07, 2023 |
| MSI           | J1800I                      | Desktop     | [983e4f18d4](https://linux-hardware.org/?probe=983e4f18d4) | Apr 06, 2023 |
| MSI           | B150 PC MATE                | Desktop     | [da2d2d3d5c](https://linux-hardware.org/?probe=da2d2d3d5c) | Apr 05, 2023 |
| ASRock        | Z87 Killer                  | Desktop     | [ec627dea03](https://linux-hardware.org/?probe=ec627dea03) | Apr 05, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [3a1b0cca6b](https://linux-hardware.org/?probe=3a1b0cca6b) | Apr 04, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [b1168b92c0](https://linux-hardware.org/?probe=b1168b92c0) | Apr 03, 2023 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Notebook    | [f013c5ca48](https://linux-hardware.org/?probe=f013c5ca48) | Apr 03, 2023 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [5499373552](https://linux-hardware.org/?probe=5499373552) | Apr 03, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [70ed012fb4](https://linux-hardware.org/?probe=70ed012fb4) | Apr 03, 2023 |
| Notebook      | NJ50GU                      | Notebook    | [91e860cd94](https://linux-hardware.org/?probe=91e860cd94) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [e3078a63c3](https://linux-hardware.org/?probe=e3078a63c3) | Apr 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [1c8c26f5c0](https://linux-hardware.org/?probe=1c8c26f5c0) | Apr 02, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [022324033e](https://linux-hardware.org/?probe=022324033e) | Apr 02, 2023 |
| HP            | 250 G3                      | Notebook    | [2030ba57b9](https://linux-hardware.org/?probe=2030ba57b9) | Apr 02, 2023 |
| Pegatron      | 2ACF                        | Desktop     | [c015b7fd50](https://linux-hardware.org/?probe=c015b7fd50) | Apr 01, 2023 |
| Dell          | Latitude 5511               | Notebook    | [86b4fcff61](https://linux-hardware.org/?probe=86b4fcff61) | Apr 01, 2023 |
| Lenovo        | ThinkPad T420s 4173R44      | Notebook    | [84e9a5f3d9](https://linux-hardware.org/?probe=84e9a5f3d9) | Apr 01, 2023 |
| UMAX          | VisionBook 14Wa Plus        | Notebook    | [ea8016c4a5](https://linux-hardware.org/?probe=ea8016c4a5) | Apr 01, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [0014e52bf3](https://linux-hardware.org/?probe=0014e52bf3) | Mar 31, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [2b23ce3fed](https://linux-hardware.org/?probe=2b23ce3fed) | Mar 31, 2023 |
| ASUSTek       | Zenbook UN5401QAB_UN5401... | Convertible | [448d1a491c](https://linux-hardware.org/?probe=448d1a491c) | Mar 31, 2023 |
| Lenovo        | ThinkPad T14s Gen 2a 20X... | Notebook    | [0ffc78eac6](https://linux-hardware.org/?probe=0ffc78eac6) | Mar 30, 2023 |
| ASUSTek       | F7L                         | Notebook    | [8d6f90f843](https://linux-hardware.org/?probe=8d6f90f843) | Mar 29, 2023 |
| ASUSTek       | F7L                         | Notebook    | [cdc5ab3b8a](https://linux-hardware.org/?probe=cdc5ab3b8a) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [6599d32d74](https://linux-hardware.org/?probe=6599d32d74) | Mar 29, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [64bef0aff5](https://linux-hardware.org/?probe=64bef0aff5) | Mar 29, 2023 |
| ASUSTek       | PN41-S1                     | Mini pc     | [95da0c6b8a](https://linux-hardware.org/?probe=95da0c6b8a) | Mar 28, 2023 |
| Lenovo        | ThinkPad T580 20LAS4L216    | Notebook    | [9c3464baf9](https://linux-hardware.org/?probe=9c3464baf9) | Mar 27, 2023 |
| HP            | 250 G6 Notebook PC          | Notebook    | [eb82e949b2](https://linux-hardware.org/?probe=eb82e949b2) | Mar 27, 2023 |
| MSI           | B250M PRO-VDH 2018-05-07    | Desktop     | [6f7e481d06](https://linux-hardware.org/?probe=6f7e481d06) | Mar 27, 2023 |
| ASRock        | Z87 Killer                  | Desktop     | [53ec55f5ae](https://linux-hardware.org/?probe=53ec55f5ae) | Mar 27, 2023 |
| Shenzhen M... | HX90G                       | Desktop     | [b6bd6cab94](https://linux-hardware.org/?probe=b6bd6cab94) | Mar 26, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [51276a5f00](https://linux-hardware.org/?probe=51276a5f00) | Mar 25, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [df8f872445](https://linux-hardware.org/?probe=df8f872445) | Mar 25, 2023 |
| Lenovo        | G780                        | Notebook    | [1ad87e5add](https://linux-hardware.org/?probe=1ad87e5add) | Mar 23, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [aa102c68bf](https://linux-hardware.org/?probe=aa102c68bf) | Mar 23, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [47992266f4](https://linux-hardware.org/?probe=47992266f4) | Mar 22, 2023 |
| HP            | ProBook 450 G2              | Notebook    | [dc56e35adc](https://linux-hardware.org/?probe=dc56e35adc) | Mar 22, 2023 |
| Lenovo        | ThinkPad T440 20B7S3N304    | Notebook    | [af39e826be](https://linux-hardware.org/?probe=af39e826be) | Mar 22, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [de7c628210](https://linux-hardware.org/?probe=de7c628210) | Mar 22, 2023 |
| Gigabyte      | GA-990FX-GAMING             | Desktop     | [7f1e3cf271](https://linux-hardware.org/?probe=7f1e3cf271) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [9b2ff390f6](https://linux-hardware.org/?probe=9b2ff390f6) | Mar 20, 2023 |
| Dell          | Latitude 5590               | Notebook    | [49922a3223](https://linux-hardware.org/?probe=49922a3223) | Mar 19, 2023 |
| Acer          | TravelMate 2490             | Notebook    | [5a21a61bef](https://linux-hardware.org/?probe=5a21a61bef) | Mar 19, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [b637fa75c8](https://linux-hardware.org/?probe=b637fa75c8) | Mar 18, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [3332cb54e5](https://linux-hardware.org/?probe=3332cb54e5) | Mar 18, 2023 |
| Acer          | TravelMate 7750ZG           | Notebook    | [5108cfe57c](https://linux-hardware.org/?probe=5108cfe57c) | Mar 16, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [5bf235f5d3](https://linux-hardware.org/?probe=5bf235f5d3) | Mar 16, 2023 |
| Dell          | Inspiron 5767               | Notebook    | [b7c8484508](https://linux-hardware.org/?probe=b7c8484508) | Mar 14, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [31c28e071b](https://linux-hardware.org/?probe=31c28e071b) | Mar 13, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [7f3525f6ef](https://linux-hardware.org/?probe=7f3525f6ef) | Mar 12, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [e82b110a76](https://linux-hardware.org/?probe=e82b110a76) | Mar 12, 2023 |
| HP            | 09CCh                       | Desktop     | [e122b11e42](https://linux-hardware.org/?probe=e122b11e42) | Mar 12, 2023 |
| Dell          | Inspiron 5748               | Notebook    | [ef020a54d0](https://linux-hardware.org/?probe=ef020a54d0) | Mar 12, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [e51e1c905c](https://linux-hardware.org/?probe=e51e1c905c) | Mar 11, 2023 |
| Lenovo        | ThinkPad Edge E330 3354A... | Notebook    | [b343b9ea49](https://linux-hardware.org/?probe=b343b9ea49) | Mar 11, 2023 |
| HP            | 09CCh                       | Desktop     | [9421be2c59](https://linux-hardware.org/?probe=9421be2c59) | Mar 11, 2023 |
| ASUSTek       | K54LY                       | Notebook    | [a846675d7f](https://linux-hardware.org/?probe=a846675d7f) | Mar 09, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | Notebook    | [fda0cb7297](https://linux-hardware.org/?probe=fda0cb7297) | Mar 08, 2023 |
| Dell          | Latitude E6420              | Notebook    | [c3384b7787](https://linux-hardware.org/?probe=c3384b7787) | Mar 07, 2023 |
| Lenovo        | ThinkPad L440 20ASS29900    | Notebook    | [707155405b](https://linux-hardware.org/?probe=707155405b) | Mar 07, 2023 |
| MSI           | Modern 15 A5M               | Notebook    | [e88ffa7e1d](https://linux-hardware.org/?probe=e88ffa7e1d) | Mar 07, 2023 |
| HP            | ProBook 455 G7              | Notebook    | [0faa2cd96c](https://linux-hardware.org/?probe=0faa2cd96c) | Mar 06, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [70d063d399](https://linux-hardware.org/?probe=70d063d399) | Mar 05, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [ba97297cf9](https://linux-hardware.org/?probe=ba97297cf9) | Mar 04, 2023 |
| ASUSTek       | ROG Strix G531GT            | Notebook    | [810e15295b](https://linux-hardware.org/?probe=810e15295b) | Mar 03, 2023 |
| Dell          | Latitude 5421               | Notebook    | [16d34b8b56](https://linux-hardware.org/?probe=16d34b8b56) | Mar 03, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [739984c8cf](https://linux-hardware.org/?probe=739984c8cf) | Mar 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS0... | Notebook    | [e73235d592](https://linux-hardware.org/?probe=e73235d592) | Mar 03, 2023 |
| ASRock        | Z170 Extreme4               | Desktop     | [428377b153](https://linux-hardware.org/?probe=428377b153) | Mar 03, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [2c6ad91981](https://linux-hardware.org/?probe=2c6ad91981) | Mar 02, 2023 |
| Lenovo        | IdeaPad 3 14IGL05 81WH      | Notebook    | [ceb6fb20b2](https://linux-hardware.org/?probe=ceb6fb20b2) | Mar 02, 2023 |
| ASUSTek       | 1016P                       | Notebook    | [29798857a5](https://linux-hardware.org/?probe=29798857a5) | Mar 02, 2023 |
| ASUSTek       | X555LA                      | Notebook    | [5dbbffb04e](https://linux-hardware.org/?probe=5dbbffb04e) | Mar 02, 2023 |
| Foxconn       | 2ABF                        | Desktop     | [9e63190b6f](https://linux-hardware.org/?probe=9e63190b6f) | Mar 01, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [10f864cbb0](https://linux-hardware.org/?probe=10f864cbb0) | Mar 01, 2023 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [8c36af11ab](https://linux-hardware.org/?probe=8c36af11ab) | Mar 01, 2023 |
| ASUSTek       | AM1I-A                      | Desktop     | [b5fe605f8b](https://linux-hardware.org/?probe=b5fe605f8b) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [2071bc50ce](https://linux-hardware.org/?probe=2071bc50ce) | Feb 27, 2023 |
| Gigabyte      | Z77X-UD5H                   | Desktop     | [472c035387](https://linux-hardware.org/?probe=472c035387) | Feb 27, 2023 |
| Dell          | 0MH651                      | Desktop     | [7921e9f8bc](https://linux-hardware.org/?probe=7921e9f8bc) | Feb 27, 2023 |
| UMAX          | VisionBook-N12R             | Notebook    | [2477ae9a0e](https://linux-hardware.org/?probe=2477ae9a0e) | Feb 27, 2023 |
| Lenovo        | Yoga 510-14AST 80S9         | Convertible | [0ea2a54b39](https://linux-hardware.org/?probe=0ea2a54b39) | Feb 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [9b2a57b7d2](https://linux-hardware.org/?probe=9b2a57b7d2) | Feb 26, 2023 |
| Standard      | Unknown                     | Notebook    | [9d002e0593](https://linux-hardware.org/?probe=9d002e0593) | Feb 26, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [f2671a0f62](https://linux-hardware.org/?probe=f2671a0f62) | Feb 25, 2023 |
| ASUSTek       | ZenBook UX425EA_UX425EA     | Notebook    | [f0fa613cd2](https://linux-hardware.org/?probe=f0fa613cd2) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20T1... | Notebook    | [1c1e5c991f](https://linux-hardware.org/?probe=1c1e5c991f) | Feb 25, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [8bfeed43ef](https://linux-hardware.org/?probe=8bfeed43ef) | Feb 24, 2023 |
| MSI           | C847MS-E33                  | Desktop     | [698d950f05](https://linux-hardware.org/?probe=698d950f05) | Feb 24, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [6829c25808](https://linux-hardware.org/?probe=6829c25808) | Feb 23, 2023 |
| Lenovo        | ThinkPad L15 Gen1 20U700... | Notebook    | [ca9a037662](https://linux-hardware.org/?probe=ca9a037662) | Feb 23, 2023 |
| Dell          | Latitude 5420               | Notebook    | [231c7534d3](https://linux-hardware.org/?probe=231c7534d3) | Feb 21, 2023 |
| Dell          | 02YYK5 A00                  | Desktop     | [cff33d0b1e](https://linux-hardware.org/?probe=cff33d0b1e) | Feb 20, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [503fe663b4](https://linux-hardware.org/?probe=503fe663b4) | Feb 20, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [3dd7359a43](https://linux-hardware.org/?probe=3dd7359a43) | Feb 20, 2023 |
| HP            | Laptop 15-rb0xx             | Notebook    | [53ef54922c](https://linux-hardware.org/?probe=53ef54922c) | Feb 20, 2023 |
| Dell          | Inspiron N5110              | Notebook    | [4a77848908](https://linux-hardware.org/?probe=4a77848908) | Feb 20, 2023 |
| Toshiba       | Satellite L50D-B            | Notebook    | [689c37d3b7](https://linux-hardware.org/?probe=689c37d3b7) | Feb 19, 2023 |
| Dell          | Vostro1710                  | Notebook    | [91b1af7ed6](https://linux-hardware.org/?probe=91b1af7ed6) | Feb 19, 2023 |
| Standard      | Unknown                     | Notebook    | [149bdc4e40](https://linux-hardware.org/?probe=149bdc4e40) | Feb 19, 2023 |
| ASUSTek       | PRIME H570M-PLUS            | Desktop     | [4fac3ddf27](https://linux-hardware.org/?probe=4fac3ddf27) | Feb 19, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [e2facdc650](https://linux-hardware.org/?probe=e2facdc650) | Feb 19, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [82db23bd7f](https://linux-hardware.org/?probe=82db23bd7f) | Feb 19, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [4c3c50a992](https://linux-hardware.org/?probe=4c3c50a992) | Feb 18, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e6391763b2](https://linux-hardware.org/?probe=e6391763b2) | Feb 17, 2023 |
| HP            | Laptop 17-cn0xxx            | Notebook    | [0e2199617b](https://linux-hardware.org/?probe=0e2199617b) | Feb 17, 2023 |
| ASRock        | B550M-HDV                   | Desktop     | [755006e226](https://linux-hardware.org/?probe=755006e226) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [6c8bdf1f73](https://linux-hardware.org/?probe=6c8bdf1f73) | Feb 17, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [89f9d45c66](https://linux-hardware.org/?probe=89f9d45c66) | Feb 17, 2023 |
| Lenovo        | ThinkPad X270 20HN0015GE    | Notebook    | [f546833d76](https://linux-hardware.org/?probe=f546833d76) | Feb 17, 2023 |
| Lenovo        | ThinkPad X250 20CM001XMC    | Notebook    | [1026c10fa9](https://linux-hardware.org/?probe=1026c10fa9) | Feb 16, 2023 |
| Dell          | 03NVJ6 A00                  | Desktop     | [d118fe4ba2](https://linux-hardware.org/?probe=d118fe4ba2) | Feb 16, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [0255141f61](https://linux-hardware.org/?probe=0255141f61) | Feb 15, 2023 |
| HP            | ProBook 470 G4              | Notebook    | [8730091665](https://linux-hardware.org/?probe=8730091665) | Feb 15, 2023 |
| HP            | Pavilion g6                 | Notebook    | [8a53743bd0](https://linux-hardware.org/?probe=8a53743bd0) | Feb 15, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [849a50c7fd](https://linux-hardware.org/?probe=849a50c7fd) | Feb 15, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [bc69f33fa2](https://linux-hardware.org/?probe=bc69f33fa2) | Feb 15, 2023 |
| Acer          | Swift SF314-42              | Notebook    | [938edcc32a](https://linux-hardware.org/?probe=938edcc32a) | Feb 15, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [ef3ee2ebf2](https://linux-hardware.org/?probe=ef3ee2ebf2) | Feb 14, 2023 |
| ASUSTek       | Maximus VII HERO            | Desktop     | [cdd9011e76](https://linux-hardware.org/?probe=cdd9011e76) | Feb 13, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [de30205f54](https://linux-hardware.org/?probe=de30205f54) | Feb 12, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [65b3bb622e](https://linux-hardware.org/?probe=65b3bb622e) | Feb 12, 2023 |
| Lenovo        | IdeaPad U330p 20267         | Notebook    | [19700ab1bd](https://linux-hardware.org/?probe=19700ab1bd) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [934ca9b130](https://linux-hardware.org/?probe=934ca9b130) | Feb 12, 2023 |
| MSI           | 2A9Ch                       | Desktop     | [1a76baff0f](https://linux-hardware.org/?probe=1a76baff0f) | Feb 12, 2023 |
| ASUSTek       | Z97-PRO GAMER               | Desktop     | [19547b9a43](https://linux-hardware.org/?probe=19547b9a43) | Feb 12, 2023 |
| MSI           | GX700                       | Notebook    | [11154709fd](https://linux-hardware.org/?probe=11154709fd) | Feb 11, 2023 |
| Pegatron      | 2AB6                        | Desktop     | [1f727ee133](https://linux-hardware.org/?probe=1f727ee133) | Feb 11, 2023 |
| Acer          | Aspire 5742G                | Notebook    | [1315dbeb6c](https://linux-hardware.org/?probe=1315dbeb6c) | Feb 11, 2023 |
| Fujitsu       | D3041-A1 S26361-D3041-A1    | Desktop     | [2b4f9e9f21](https://linux-hardware.org/?probe=2b4f9e9f21) | Feb 11, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [e8fdc1676a](https://linux-hardware.org/?probe=e8fdc1676a) | Feb 10, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [16d6cdad97](https://linux-hardware.org/?probe=16d6cdad97) | Feb 09, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [26f7ad82d9](https://linux-hardware.org/?probe=26f7ad82d9) | Feb 08, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [d54546bce9](https://linux-hardware.org/?probe=d54546bce9) | Feb 08, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [731d910d0c](https://linux-hardware.org/?probe=731d910d0c) | Feb 08, 2023 |
| ASUSTek       | TUF B450M-PRO GAMING        | Desktop     | [d7157a7862](https://linux-hardware.org/?probe=d7157a7862) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [c0aab06a5c](https://linux-hardware.org/?probe=c0aab06a5c) | Feb 07, 2023 |
| HP            | Compaq 6510b (KV178EC#AB... | Notebook    | [830072137a](https://linux-hardware.org/?probe=830072137a) | Feb 07, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [8cb1801046](https://linux-hardware.org/?probe=8cb1801046) | Feb 07, 2023 |
| Intel         | NUC5PPYB H76558-109         | Mini pc     | [a3384bd952](https://linux-hardware.org/?probe=a3384bd952) | Feb 06, 2023 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [6490f4cb92](https://linux-hardware.org/?probe=6490f4cb92) | Feb 05, 2023 |
| MSI           | GE620/GE620DX/FX620DX/FX... | Notebook    | [e9082b6ebf](https://linux-hardware.org/?probe=e9082b6ebf) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [4214ad8f29](https://linux-hardware.org/?probe=4214ad8f29) | Feb 04, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [330da24dc9](https://linux-hardware.org/?probe=330da24dc9) | Feb 04, 2023 |
| HP            | ProBook 4530s               | Notebook    | [9ff88cbe9a](https://linux-hardware.org/?probe=9ff88cbe9a) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [922ee5ede0](https://linux-hardware.org/?probe=922ee5ede0) | Feb 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [91ab5e33ed](https://linux-hardware.org/?probe=91ab5e33ed) | Feb 03, 2023 |
| Lenovo        | ThinkPad P1 Gen 3 20TJS2... | Notebook    | [0b73c3afe8](https://linux-hardware.org/?probe=0b73c3afe8) | Feb 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| HP            | Stream Notebook PC 14       | Notebook    | [69628da41b](https://linux-hardware.org/?probe=69628da41b) | Feb 03, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [3bcca39276](https://linux-hardware.org/?probe=3bcca39276) | Feb 02, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [1651e1e5af](https://linux-hardware.org/?probe=1651e1e5af) | Feb 02, 2023 |
| Intel         | NUC7i5BNB J31144-310        | Mini pc     | [87fe173b18](https://linux-hardware.org/?probe=87fe173b18) | Feb 02, 2023 |
| ASUSTek       | G10DK                       | Desktop     | [80e1fa4ed8](https://linux-hardware.org/?probe=80e1fa4ed8) | Feb 01, 2023 |
| ASUSTek       | GL702VT                     | Notebook    | [83abe24c59](https://linux-hardware.org/?probe=83abe24c59) | Feb 01, 2023 |
| Lenovo        | ThinkPad E520 1143JYG       | Notebook    | [87735dd3b0](https://linux-hardware.org/?probe=87735dd3b0) | Feb 01, 2023 |
| HP            | Laptop 15-bw0xx             | Notebook    | [b7fce61d74](https://linux-hardware.org/?probe=b7fce61d74) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [63dfd6ca48](https://linux-hardware.org/?probe=63dfd6ca48) | Jan 30, 2023 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [36caf406ce](https://linux-hardware.org/?probe=36caf406ce) | Jan 29, 2023 |
| Lenovo        | ThinkPad T580 20LA0025MX    | Notebook    | [c5e4274143](https://linux-hardware.org/?probe=c5e4274143) | Jan 29, 2023 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [6444a93633](https://linux-hardware.org/?probe=6444a93633) | Jan 29, 2023 |
| ASUSTek       | V241DA                      | All in one  | [72df681f16](https://linux-hardware.org/?probe=72df681f16) | Jan 28, 2023 |
| ASUSTek       | X200MA                      | Notebook    | [1c1f2d4d5b](https://linux-hardware.org/?probe=1c1f2d4d5b) | Jan 28, 2023 |
| Timi          | A35S                        | Notebook    | [b6611f9b22](https://linux-hardware.org/?probe=b6611f9b22) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [ec9bed5b5d](https://linux-hardware.org/?probe=ec9bed5b5d) | Jan 28, 2023 |
| HP            | Pavilion dv6500             | Notebook    | [e225ce26a1](https://linux-hardware.org/?probe=e225ce26a1) | Jan 28, 2023 |
| ASUSTek       | UX31E                       | Notebook    | [d87ac57c19](https://linux-hardware.org/?probe=d87ac57c19) | Jan 27, 2023 |
| Lenovo        | MAHOBAY 31900003 STD        | All in one  | [d75e472005](https://linux-hardware.org/?probe=d75e472005) | Jan 26, 2023 |
| UMAX          | VisionBook 10Wr Tab         | Convertible | [6d747e3841](https://linux-hardware.org/?probe=6d747e3841) | Jan 26, 2023 |
| HP            | EliteBook 8460p             | Notebook    | [bb83f545f7](https://linux-hardware.org/?probe=bb83f545f7) | Jan 24, 2023 |
| Dell          | Latitude 5530               | Notebook    | [b365359e5f](https://linux-hardware.org/?probe=b365359e5f) | Jan 24, 2023 |
| Dell          | Precision 3530              | Notebook    | [f0fa541c85](https://linux-hardware.org/?probe=f0fa541c85) | Jan 24, 2023 |
| HP            | 8750                        | Desktop     | [e8b02ffbb5](https://linux-hardware.org/?probe=e8b02ffbb5) | Jan 23, 2023 |
| Intel         | X79M-S                      | Desktop     | [ccad523936](https://linux-hardware.org/?probe=ccad523936) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| ASUSTek       | UX303LN                     | Notebook    | [60f8946cdf](https://linux-hardware.org/?probe=60f8946cdf) | Jan 21, 2023 |
| Lenovo        | Yoga 700-14ISK 80QD         | Notebook    | [4e07ace043](https://linux-hardware.org/?probe=4e07ace043) | Jan 21, 2023 |
| ASUSTek       | UX303LN                     | Notebook    | [846e3df466](https://linux-hardware.org/?probe=846e3df466) | Jan 21, 2023 |
| ASUSTek       | H81M-C                      | Desktop     | [ec12d33bd7](https://linux-hardware.org/?probe=ec12d33bd7) | Jan 21, 2023 |
| Lenovo        | Yoga 7 14ACN6 82N7          | Convertible | [5a32ba3cd1](https://linux-hardware.org/?probe=5a32ba3cd1) | Jan 21, 2023 |
| HP            | EliteBook 8570p             | Notebook    | [66c806fbfe](https://linux-hardware.org/?probe=66c806fbfe) | Jan 21, 2023 |
| ASUSTek       | X555LF                      | Notebook    | [7220c25a3b](https://linux-hardware.org/?probe=7220c25a3b) | Jan 20, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d77bf1f32b](https://linux-hardware.org/?probe=d77bf1f32b) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | Notebook    | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Czechia/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 249       | 9.43%   |
| Ubuntu 22.04                 | 161       | 6.1%    |
| Ubuntu 18.04                 | 152       | 5.76%   |
| OpenMandriva 4.2             | 118       | 4.47%   |
| OpenMandriva 4.3             | 72        | 2.73%   |
| OpenMandriva 4.50            | 66        | 2.5%    |
| Arch Rolling                 | 52        | 1.97%   |
| Debian 11                    | 43        | 1.63%   |
| Fedora 39                    | 41        | 1.55%   |
| Ubuntu 21.10                 | 39        | 1.48%   |
| Fedora 38                    | 37        | 1.4%    |
| Zorin 16                     | 36        | 1.36%   |
| Pop!_OS 22.04                | 36        | 1.36%   |
| Ubuntu 20.10                 | 35        | 1.33%   |
| Fedora 34                    | 35        | 1.33%   |
| Linux Mint 21.1              | 34        | 1.29%   |
| openSUSE Tumbleweed-XXXXXXXX | 32        | 1.21%   |
| OpenMandriva 23.01           | 31        | 1.17%   |
| Debian 12                    | 29        | 1.1%    |
| Ubuntu 19.10                 | 28        | 1.06%   |
| Linux Mint 20.1              | 28        | 1.06%   |
| Ubuntu 21.04                 | 27        | 1.02%   |
| OpenMandriva 23.03           | 27        | 1.02%   |
| Linux Mint 20                | 27        | 1.02%   |
| Fedora 35                    | 27        | 1.02%   |
| Arch                         | 27        | 1.02%   |
| Linux Mint 20.2              | 25        | 0.95%   |
| Fedora 32                    | 25        | 0.95%   |
| Zorin 15                     | 24        | 0.91%   |
| Ubuntu 19.04                 | 24        | 0.91%   |
| OpenMandriva 23.08           | 24        | 0.91%   |
| Linux Mint 21.2              | 24        | 0.91%   |
| Linux Mint 20.3              | 24        | 0.91%   |
| Ubuntu 22.10                 | 23        | 0.87%   |
| Linux Mint 19.3              | 23        | 0.87%   |
| Fedora 33                    | 23        | 0.87%   |
| Fedora 37                    | 22        | 0.83%   |
| Ubuntu 23.10                 | 20        | 0.76%   |
| Manjaro                      | 20        | 0.76%   |
| Fedora 36                    | 20        | 0.76%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 743       | 30.06%  |
| OpenMandriva  | 353       | 14.28%  |
| Fedora        | 243       | 9.83%   |
| Linux Mint    | 214       | 8.66%   |
| Debian        | 101       | 4.09%   |
| Arch          | 79        | 3.2%    |
| Zorin         | 69        | 2.79%   |
| Pop!_OS       | 65        | 2.63%   |
| Manjaro       | 65        | 2.63%   |
| Kubuntu       | 54        | 2.18%   |
| Xubuntu       | 51        | 2.06%   |
| Gentoo        | 47        | 1.9%    |
| ROSA          | 45        | 1.82%   |
| openSUSE      | 38        | 1.54%   |
| KDE neon      | 28        | 1.13%   |
| Lubuntu       | 22        | 0.89%   |
| Kali          | 22        | 0.89%   |
| ArcoLinux     | 21        | 0.85%   |
| Elementary    | 17        | 0.69%   |
| RHEL          | 15        | 0.61%   |
| Ubuntu MATE   | 14        | 0.57%   |
| Endless       | 14        | 0.57%   |
| EndeavourOS   | 13        | 0.53%   |
| SteamOS       | 11        | 0.44%   |
| Ubuntu Unity  | 10        | 0.4%    |
| Void Linux    | 9         | 0.36%   |
| NixOS         | 9         | 0.36%   |
| CentOS        | 9         | 0.36%   |
| Parrot        | 7         | 0.28%   |
| LMDE          | 7         | 0.28%   |
| ACI           | 5         | 0.2%    |
| Ubuntu Budgie | 4         | 0.16%   |
| Rocky Linux   | 4         | 0.16%   |
| Nobara        | 4         | 0.16%   |
| MX            | 4         | 0.16%   |
| BlackPanther  | 4         | 0.16%   |
| TUXEDO OS     | 3         | 0.12%   |
| Neptune OS    | 3         | 0.12%   |
| LinuxFX       | 3         | 0.12%   |
| Garuda Linux  | 3         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 116       | 4.01%   |
| 5.16.7-desktop-1omv4003  | 70        | 2.42%   |
| 5.14.7-desktop-1omv4050  | 55        | 1.9%    |
| 5.4.0-42-generic         | 34        | 1.18%   |
| 6.2.6-desktop-1omv2390   | 28        | 0.97%   |
| 6.1.1-desktop-1omv2290   | 28        | 0.97%   |
| 5.4.0-58-generic         | 23        | 0.8%    |
| 5.15.0-56-generic        | 23        | 0.8%    |
| 5.4.0-52-generic         | 22        | 0.76%   |
| 5.15.0-46-generic        | 21        | 0.73%   |
| 6.4.11-desktop-1omv2390  | 20        | 0.69%   |
| 5.4.0-26-generic         | 20        | 0.69%   |
| 5.15.0-58-generic        | 18        | 0.62%   |
| 6.6.2-desktop-1omv2390   | 17        | 0.59%   |
| 5.15.0-52-generic        | 16        | 0.55%   |
| 5.11.0-27-generic        | 16        | 0.55%   |
| 5.3.0-40-generic         | 15        | 0.52%   |
| 5.0.0-37-generic         | 15        | 0.52%   |
| 6.2.0-26-generic         | 14        | 0.48%   |
| 5.13.0-30-generic        | 14        | 0.48%   |
| 5.4.0-48-generic         | 12        | 0.42%   |
| 5.4.0-40-generic         | 12        | 0.42%   |
| 5.3.0-28-generic         | 12        | 0.42%   |
| 5.15.0-48-generic        | 12        | 0.42%   |
| 5.4.0-65-generic         | 11        | 0.38%   |
| 5.15.0-41-generic        | 11        | 0.38%   |
| 6.2.0-39-generic         | 10        | 0.35%   |
| 5.4.0-29-generic         | 10        | 0.35%   |
| 5.11.0-37-generic        | 10        | 0.35%   |
| 5.8.0-53-generic         | 9         | 0.31%   |
| 5.4.0-91-generic         | 9         | 0.31%   |
| 5.4.0-37-generic         | 9         | 0.31%   |
| 5.19.0-32-generic        | 9         | 0.31%   |
| 5.15.0-78-generic        | 9         | 0.31%   |
| 5.10.0-8-amd64           | 9         | 0.31%   |
| 4.15.0-43-generic        | 9         | 0.31%   |
| 6.2.0-33-generic         | 8         | 0.28%   |
| 6.1.0-13-amd64           | 8         | 0.28%   |
| 5.8.0-59-generic         | 8         | 0.28%   |
| 5.8.0-50-generic         | 8         | 0.28%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 320       | 11.74%  |
| 5.15.0  | 219       | 8.04%   |
| 5.10.14 | 116       | 4.26%   |
| 4.15.0  | 112       | 4.11%   |
| 5.8.0   | 101       | 3.71%   |
| 5.11.0  | 96        | 3.52%   |
| 5.13.0  | 94        | 3.45%   |
| 5.3.0   | 92        | 3.38%   |
| 5.19.0  | 73        | 2.68%   |
| 5.16.7  | 71        | 2.61%   |
| 5.0.0   | 71        | 2.61%   |
| 6.2.0   | 67        | 2.46%   |
| 6.5.0   | 65        | 2.39%   |
| 4.18.0  | 57        | 2.09%   |
| 5.14.7  | 56        | 2.06%   |
| 5.10.0  | 44        | 1.61%   |
| 6.1.0   | 42        | 1.54%   |
| 6.2.6   | 34        | 1.25%   |
| 6.1.1   | 34        | 1.25%   |
| 6.6.2   | 21        | 0.77%   |
| 6.4.11  | 21        | 0.77%   |
| 4.19.0  | 17        | 0.62%   |
| 6.7.9   | 12        | 0.44%   |
| 6.5.6   | 12        | 0.44%   |
| 6.0.0   | 12        | 0.44%   |
| 3.10.0  | 11        | 0.4%    |
| 6.3.5   | 9         | 0.33%   |
| 5.14.0  | 9         | 0.33%   |
| 4.9.20  | 9         | 0.33%   |
| 6.0.12  | 8         | 0.29%   |
| 5.16.11 | 8         | 0.29%   |
| 5.11.12 | 8         | 0.29%   |
| 6.6.9   | 7         | 0.26%   |
| 6.2.9   | 7         | 0.26%   |
| 5.17.0  | 7         | 0.26%   |
| 5.15.12 | 7         | 0.26%   |
| 6.8.0   | 6         | 0.22%   |
| 6.7.6   | 6         | 0.22%   |
| 6.6.8   | 6         | 0.22%   |
| 6.5.5   | 6         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.4      | 344       | 12.76%  |
| 5.15     | 274       | 10.16%  |
| 5.10     | 204       | 7.57%   |
| 5.8      | 134       | 4.97%   |
| 6.2      | 132       | 4.9%    |
| 5.11     | 130       | 4.82%   |
| 6.1      | 126       | 4.67%   |
| 4.15     | 114       | 4.23%   |
| 5.13     | 112       | 4.15%   |
| 5.3      | 103       | 3.82%   |
| 6.5      | 102       | 3.78%   |
| 5.16     | 102       | 3.78%   |
| 5.19     | 97        | 3.6%    |
| 5.14     | 86        | 3.19%   |
| 5.0      | 78        | 2.89%   |
| 6.6      | 68        | 2.52%   |
| 4.18     | 60        | 2.23%   |
| 6.4      | 53        | 1.97%   |
| 6.0      | 39        | 1.45%   |
| 6.7      | 36        | 1.34%   |
| 5.17     | 34        | 1.26%   |
| 6.3      | 32        | 1.19%   |
| 6.8      | 31        | 1.15%   |
| 5.9      | 25        | 0.93%   |
| 5.18     | 24        | 0.89%   |
| 5.6      | 23        | 0.85%   |
| 4.19     | 22        | 0.82%   |
| 5.12     | 21        | 0.78%   |
| 4.9      | 20        | 0.74%   |
| 5.7      | 14        | 0.52%   |
| 3.10     | 12        | 0.45%   |
| 5.5      | 11        | 0.41%   |
| 4.4      | 6         | 0.22%   |
| 4.13     | 6         | 0.22%   |
| 5.1      | 4         | 0.15%   |
| 5.2      | 3         | 0.11%   |
| 4.17     | 3         | 0.11%   |
| 4.14     | 3         | 0.11%   |
| 4.1      | 2         | 0.07%   |
| 5.10.164 | 1         | 0.04%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 2336      | 96.53%  |
| i686    | 64        | 2.64%   |
| aarch64 | 16        | 0.66%   |
| armv7l  | 2         | 0.08%   |
| mips    | 1         | 0.04%   |
| armv8l  | 1         | 0.04%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 1002      | 39.87%  |
| KDE5              | 586       | 23.32%  |
| Unknown           | 290       | 11.54%  |
| XFCE              | 184       | 7.32%   |
| X-Cinnamon        | 142       | 5.65%   |
| MATE              | 62        | 2.47%   |
| KDE               | 47        | 1.87%   |
| Cinnamon          | 36        | 1.43%   |
| LXQt              | 32        | 1.27%   |
| Pantheon          | 17        | 0.68%   |
| KDE4              | 13        | 0.52%   |
| LXDE              | 12        | 0.48%   |
| GNOME Flashback   | 12        | 0.48%   |
| Unity             | 11        | 0.44%   |
| KDE6              | 11        | 0.44%   |
| i3                | 9         | 0.36%   |
| Hyprland          | 8         | 0.32%   |
| Budgie            | 7         | 0.28%   |
| openbox           | 6         | 0.24%   |
| sway              | 5         | 0.2%    |
| awesome           | 4         | 0.16%   |
| qtile             | 3         | 0.12%   |
| Deepin            | 2         | 0.08%   |
| Yaru:ubuntu:GNOME | 1         | 0.04%   |
| XSession          | 1         | 0.04%   |
| xinitrc           | 1         | 0.04%   |
| xinit-compat      | 1         | 0.04%   |
| icewm             | 1         | 0.04%   |
| GNUstep           | 1         | 0.04%   |
| GNOME Classic     | 1         | 0.04%   |
| Enlightenment     | 1         | 0.04%   |
| DWM               | 1         | 0.04%   |
| custom            | 1         | 0.04%   |
| Core              | 1         | 0.04%   |
| bspwm             | 1         | 0.04%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 1763      | 70.58%  |
| Wayland | 530       | 21.22%  |
| Unknown | 151       | 6.04%   |
| Tty     | 54        | 2.16%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1084      | 43.24%  |
| SDDM    | 568       | 22.66%  |
| GDM3    | 282       | 11.25%  |
| GDM     | 244       | 9.73%   |
| LightDM | 228       | 9.09%   |
| TDM     | 72        | 2.87%   |
| KDM     | 12        | 0.48%   |
| SLiM    | 6         | 0.24%   |
| XDM     | 5         | 0.2%    |
| LXDM    | 3         | 0.12%   |
| SLIMSKI | 1         | 0.04%   |
| Ly      | 1         | 0.04%   |
| GREETD  | 1         | 0.04%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| cs_CZ   | 1268      | 51.32%  |
| en_US   | 773       | 31.28%  |
| Unknown | 233       | 9.43%   |
| en_GB   | 61        | 2.47%   |
| C       | 46        | 1.86%   |
| ru_RU   | 27        | 1.09%   |
| sk_SK   | 12        | 0.49%   |
| pl_PL   | 9         | 0.36%   |
| POSIX   | 6         | 0.24%   |
| de_DE   | 5         | 0.2%    |
| uk_UA   | 4         | 0.16%   |
| C.UTF8  | 4         | 0.16%   |
| it_IT   | 3         | 0.12%   |
| fr_FR   | 3         | 0.12%   |
| pt_PT   | 2         | 0.08%   |
| en_CA   | 2         | 0.08%   |
| tr_TR   | 1         | 0.04%   |
| ro_RO   | 1         | 0.04%   |
| pt_BR   | 1         | 0.04%   |
| nb_NO   | 1         | 0.04%   |
| hu_HU   | 1         | 0.04%   |
| fi_FI   | 1         | 0.04%   |
| es_ES   | 1         | 0.04%   |
| en_NG   | 1         | 0.04%   |
| en_AU   | 1         | 0.04%   |
| en_150  | 1         | 0.04%   |
| el_GR   | 1         | 0.04%   |
| de_CH   | 1         | 0.04%   |
| bg_BG   | 1         | 0.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 1275      | 51.43%  |
| EFI  | 1204      | 48.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 1624      | 65.04%  |
| Overlay  | 343       | 13.74%  |
| Btrfs    | 287       | 11.49%  |
| Tmpfs    | 80        | 3.2%    |
| Unknown  | 64        | 2.56%   |
| Xfs      | 59        | 2.36%   |
| Zfs      | 20        | 0.8%    |
| F2fs     | 5         | 0.2%    |
| Ext2     | 5         | 0.2%    |
| Ext3     | 4         | 0.16%   |
| Reiserfs | 2         | 0.08%   |
| Aufs     | 2         | 0.08%   |
| Jfs      | 1         | 0.04%   |
| Bcachefs | 1         | 0.04%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 1092      | 44.17%  |
| GPT     | 1008      | 40.78%  |
| MBR     | 372       | 15.05%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 2123      | 86.69%  |
| Yes       | 326       | 13.31%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1657      | 67.11%  |
| Yes       | 812       | 32.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 505       | 20.88%  |
| Lenovo                  | 462       | 19.1%   |
| Hewlett-Packard         | 377       | 15.58%  |
| Dell                    | 260       | 10.75%  |
| Gigabyte Technology     | 163       | 6.74%   |
| Acer                    | 154       | 6.37%   |
| MSI                     | 145       | 5.99%   |
| ASRock                  | 58        | 2.4%    |
| Intel                   | 33        | 1.36%   |
| UMAX                    | 28        | 1.16%   |
| Fujitsu                 | 20        | 0.83%   |
| Sony                    | 18        | 0.74%   |
| Toshiba                 | 17        | 0.7%    |
| Raspberry Pi Foundation | 14        | 0.58%   |
| Unknown                 | 13        | 0.54%   |
| Valve                   | 10        | 0.41%   |
| Google                  | 10        | 0.41%   |
| Apple                   | 10        | 0.41%   |
| Pegatron                | 9         | 0.37%   |
| TUXEDO                  | 8         | 0.33%   |
| Fujitsu Siemens         | 8         | 0.33%   |
| Supermicro              | 7         | 0.29%   |
| HUAWEI                  | 7         | 0.29%   |
| AMI                     | 6         | 0.25%   |
| Packard Bell            | 5         | 0.21%   |
| Timi                    | 4         | 0.17%   |
| Microsoft               | 4         | 0.17%   |
| ZOTAC                   | 3         | 0.12%   |
| Samsung Electronics     | 3         | 0.12%   |
| Notebook                | 3         | 0.12%   |
| Foxconn                 | 3         | 0.12%   |
| Dynabook                | 3         | 0.12%   |
| Minix                   | 2         | 0.08%   |
| Insyde                  | 2         | 0.08%   |
| IBM                     | 2         | 0.08%   |
| Clientron               | 2         | 0.08%   |
| Chuwi                   | 2         | 0.08%   |
| Biostar                 | 2         | 0.08%   |
| ASRockRack              | 2         | 0.08%   |
| Alienware               | 2         | 0.08%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| ASUS UX31E                        | 127       | 5.25%   |
| Unknown                           | 19        | 0.79%   |
| ASUS All Series                   | 15        | 0.62%   |
| MSI MS-7C91                       | 11        | 0.45%   |
| Valve Jupiter                     | 9         | 0.37%   |
| MSI MS-7C02                       | 9         | 0.37%   |
| Dell Latitude E6420               | 8         | 0.33%   |
| MSI MS-7A34                       | 7         | 0.29%   |
| MSI MS-7693                       | 7         | 0.29%   |
| HP ProBook 455 G7                 | 7         | 0.29%   |
| HP ProLiant DL380e Gen8           | 6         | 0.25%   |
| HP ProBook 4540s                  | 6         | 0.25%   |
| HP EliteBook 845 G8 Notebook PC   | 6         | 0.25%   |
| HP EliteBook 840 G6               | 6         | 0.25%   |
| RPi Raspberry Pi                  | 5         | 0.21%   |
| MSI MS-7592                       | 5         | 0.21%   |
| Lenovo ThinkPad E14 20RA001LMC    | 5         | 0.21%   |
| Lenovo IdeaPad S145-15AST 81N3    | 5         | 0.21%   |
| HP ProBook 4530s                  | 5         | 0.21%   |
| HP ProBook 450 G5                 | 5         | 0.21%   |
| HP Pavilion dv7                   | 5         | 0.21%   |
| HP EliteBook 840 G3               | 5         | 0.21%   |
| Dell XPS 15 9560                  | 5         | 0.21%   |
| Dell Latitude E6400               | 5         | 0.21%   |
| Dell Latitude 5401                | 5         | 0.21%   |
| ASUS P5G41T-M LX                  | 5         | 0.21%   |
| HP Victus by Laptop 16-e0xxx      | 4         | 0.17%   |
| HP ProDesk 405 G6 Desktop Mini PC | 4         | 0.17%   |
| HP ProBook 4510s                  | 4         | 0.17%   |
| HP Notebook                       | 4         | 0.17%   |
| HP EliteBook 8470p                | 4         | 0.17%   |
| HP Compaq 8200 Elite SFF PC       | 4         | 0.17%   |
| HP 250 G6 Notebook PC             | 4         | 0.17%   |
| HP 250 G3                         | 4         | 0.17%   |
| Dell XPS 15 7590                  | 4         | 0.17%   |
| Dell Precision M6500              | 4         | 0.17%   |
| Dell Latitude E7440               | 4         | 0.17%   |
| Dell Latitude E5470               | 4         | 0.17%   |
| Dell Latitude 7490                | 4         | 0.17%   |
| Dell Latitude 5480                | 4         | 0.17%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 214       | 8.85%   |
| ASUS UX31E         | 127       | 5.25%   |
| Dell Latitude      | 111       | 4.59%   |
| Acer Aspire        | 90        | 3.72%   |
| Lenovo IdeaPad     | 86        | 3.56%   |
| HP EliteBook       | 81        | 3.35%   |
| HP ProBook         | 68        | 2.81%   |
| HP Compaq          | 40        | 1.65%   |
| ASUS ROG           | 40        | 1.65%   |
| HP Pavilion        | 39        | 1.61%   |
| ASUS PRIME         | 36        | 1.49%   |
| Dell Precision     | 31        | 1.28%   |
| Dell Inspiron      | 31        | 1.28%   |
| Lenovo Yoga        | 30        | 1.24%   |
| Dell XPS           | 30        | 1.24%   |
| ASUS TUF           | 30        | 1.24%   |
| Dell OptiPlex      | 28        | 1.16%   |
| Lenovo ThinkCentre | 22        | 0.91%   |
| ASUS Zenbook       | 21        | 0.87%   |
| Lenovo Legion      | 20        | 0.83%   |
| HP ZBook           | 20        | 0.83%   |
| Unknown            | 19        | 0.79%   |
| UMAX VisionBook    | 18        | 0.74%   |
| HP Laptop          | 18        | 0.74%   |
| ASUS VivoBook      | 18        | 0.74%   |
| Toshiba Satellite  | 16        | 0.66%   |
| ASUS All           | 15        | 0.62%   |
| Acer Extensa       | 15        | 0.62%   |
| RPi Raspberry      | 14        | 0.58%   |
| Acer TravelMate    | 14        | 0.58%   |
| Acer Swift         | 14        | 0.58%   |
| HP ENVY            | 13        | 0.54%   |
| Dell Vostro        | 13        | 0.54%   |
| HP ProDesk         | 12        | 0.5%    |
| HP 250             | 12        | 0.5%    |
| Fujitsu LIFEBOOK   | 12        | 0.5%    |
| ASUS ASUS          | 12        | 0.5%    |
| MSI MS-7C91        | 11        | 0.45%   |
| Lenovo ThinkBook   | 11        | 0.45%   |
| Valve Jupiter      | 9         | 0.37%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2011    | 273       | 11.29%  |
| 2020    | 236       | 9.76%   |
| 2018    | 203       | 8.39%   |
| 2019    | 189       | 7.81%   |
| 2021    | 187       | 7.73%   |
| 2017    | 163       | 6.74%   |
| 2012    | 158       | 6.53%   |
| 2014    | 136       | 5.62%   |
| 2013    | 125       | 5.17%   |
| 2015    | 110       | 4.55%   |
| 2008    | 104       | 4.3%    |
| 2016    | 98        | 4.05%   |
| 2022    | 93        | 3.84%   |
| 2010    | 86        | 3.56%   |
| 2009    | 80        | 3.31%   |
| 2007    | 68        | 2.81%   |
| 2023    | 44        | 1.82%   |
| 2006    | 28        | 1.16%   |
| Unknown | 20        | 0.83%   |
| 2005    | 9         | 0.37%   |
| 2024    | 4         | 0.17%   |
| 2004    | 4         | 0.17%   |
| 2000    | 1         | 0.04%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 1475      | 60.98%  |
| Desktop        | 765       | 31.62%  |
| Convertible    | 67        | 2.77%   |
| Mini pc        | 38        | 1.57%   |
| Tablet         | 21        | 0.87%   |
| System on chip | 18        | 0.74%   |
| Server         | 18        | 0.74%   |
| All in one     | 16        | 0.66%   |
| Phone          | 1         | 0.04%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 2214      | 90.63%  |
| Enabled  | 229       | 9.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2409      | 99.59%  |
| Yes  | 10        | 0.41%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 3.01-4.0        | 571       | 23.15%  |
| 4.01-8.0        | 453       | 18.36%  |
| 8.01-16.0       | 435       | 17.63%  |
| 16.01-24.0      | 424       | 17.19%  |
| 32.01-64.0      | 280       | 11.35%  |
| 1.01-2.0        | 116       | 4.7%    |
| 64.01-256.0     | 69        | 2.8%    |
| 24.01-32.0      | 54        | 2.19%   |
| 2.01-3.0        | 40        | 1.62%   |
| 0.51-1.0        | 19        | 0.77%   |
| More than 256.0 | 3         | 0.12%   |
| 0.01-0.5        | 3         | 0.12%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB     | Computers | Percent |
|-------------|-----------|---------|
| 1.01-2.0    | 923       | 34.21%  |
| 2.01-3.0    | 584       | 21.65%  |
| 4.01-8.0    | 446       | 16.53%  |
| 3.01-4.0    | 345       | 12.79%  |
| 8.01-16.0   | 160       | 5.93%   |
| 0.51-1.0    | 156       | 5.78%   |
| 0.01-0.5    | 38        | 1.41%   |
| 16.01-24.0  | 29        | 1.07%   |
| 32.01-64.0  | 9         | 0.33%   |
| 24.01-32.0  | 6         | 0.22%   |
| 64.01-256.0 | 1         | 0.04%   |
| Unknown     | 1         | 0.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 1612      | 64.38%  |
| 2      | 540       | 21.57%  |
| 3      | 168       | 6.71%   |
| 4      | 73        | 2.92%   |
| 5      | 44        | 1.76%   |
| 0      | 29        | 1.16%   |
| 6      | 20        | 0.8%    |
| 7      | 13        | 0.52%   |
| 8      | 4         | 0.16%   |
| 9      | 1         | 0.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 1623      | 66.65%  |
| Yes       | 812       | 33.35%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 2094      | 86.1%   |
| No        | 338       | 13.9%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1815      | 74.63%  |
| No        | 617       | 25.37%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1444      | 58.96%  |
| No        | 1005      | 41.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Czechia | 2419      | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Prague               | 954       | 37.68%  |
| Brno                 | 198       | 7.82%   |
| Ostrava              | 73        | 2.88%   |
| Pilsen               | 55        | 2.17%   |
| Liberec              | 38        | 1.5%    |
| Olomouc              | 35        | 1.38%   |
| Pardubice            | 34        | 1.34%   |
| Hradec Králové     | 33        | 1.3%    |
| České Budějovice  | 27        | 1.07%   |
| Brdo                 | 22        | 0.87%   |
| Zlín                | 21        | 0.83%   |
| Havířov            | 18        | 0.71%   |
| Znojmo               | 16        | 0.63%   |
| Most                 | 14        | 0.55%   |
| Chomutov             | 14        | 0.55%   |
| Opava                | 12        | 0.47%   |
| Mladá Boleslav      | 12        | 0.47%   |
| Kladno               | 12        | 0.47%   |
| Jihlava              | 12        | 0.47%   |
| Frýdek-Místek      | 12        | 0.47%   |
| Ústí nad Labem     | 11        | 0.43%   |
| Šlapanice           | 11        | 0.43%   |
| Tábor               | 9         | 0.36%   |
| Přerov              | 9         | 0.36%   |
| Uherské Hradiště  | 8         | 0.32%   |
| Roznov pod Radhostem | 8         | 0.32%   |
| Příbram            | 8         | 0.32%   |
| Litoměřice         | 8         | 0.32%   |
| Kralupy nad Vltavou  | 8         | 0.32%   |
| Karlovy Vary         | 8         | 0.32%   |
| Český Těšín     | 8         | 0.32%   |
| Třebíč            | 7         | 0.28%   |
| Teplice              | 7         | 0.28%   |
| Prelouc              | 7         | 0.28%   |
| Praha 10             | 7         | 0.28%   |
| Jedovnice            | 7         | 0.28%   |
| Horice               | 7         | 0.28%   |
| Česká Lípa        | 7         | 0.28%   |
| Celakovice           | 7         | 0.28%   |
| As                   | 7         | 0.28%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 563       | 802    | 16.51%  |
| WDC                         | 508       | 832    | 14.9%   |
| Seagate                     | 465       | 712    | 13.64%  |
| SanDisk                     | 253       | 280    | 7.42%   |
| Kingston                    | 236       | 295    | 6.92%   |
| Toshiba                     | 184       | 227    | 5.4%    |
| Unknown                     | 139       | 200    | 4.08%   |
| SK hynix                    | 106       | 123    | 3.11%   |
| Intel                       | 96        | 118    | 2.82%   |
| Hitachi                     | 93        | 108    | 2.73%   |
| A-DATA Technology           | 87        | 103    | 2.55%   |
| Crucial                     | 84        | 101    | 2.46%   |
| Micron Technology           | 76        | 101    | 2.23%   |
| Patriot                     | 61        | 74     | 1.79%   |
| HGST                        | 56        | 69     | 1.64%   |
| Apacer                      | 32        | 43     | 0.94%   |
| KIOXIA                      | 29        | 43     | 0.85%   |
| Transcend                   | 21        | 31     | 0.62%   |
| Verbatim                    | 18        | 19     | 0.53%   |
| Phison                      | 16        | 28     | 0.47%   |
| Gigabyte Technology         | 16        | 28     | 0.47%   |
| Unknown                     | 16        | 18     | 0.47%   |
| Phison Electronics          | 14        | 17     | 0.41%   |
| Kingston Technology Company | 13        | 14     | 0.38%   |
| Silicon Motion              | 12        | 14     | 0.35%   |
| OCZ                         | 12        | 35     | 0.35%   |
| LITEONIT                    | 12        | 15     | 0.35%   |
| Micron/Crucial Technology   | 10        | 11     | 0.29%   |
| Fujitsu                     | 10        | 11     | 0.29%   |
| China                       | 10        | 11     | 0.29%   |
| Maxtor                      | 9         | 13     | 0.26%   |
| LITEON                      | 9         | 10     | 0.26%   |
| GOODRAM                     | 9         | 12     | 0.26%   |
| XPG                         | 8         | 15     | 0.23%   |
| Apple                       | 8         | 13     | 0.23%   |
| Realtek Semiconductor       | 7         | 16     | 0.21%   |
| UMAX                        | 6         | 6      | 0.18%   |
| JMicron Technology          | 6         | 7      | 0.18%   |
| Corsair                     | 5         | 5      | 0.15%   |
| ASMedia                     | 5         | 7      | 0.15%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                              | Computers | Percent |
|----------------------------------------------------|-----------|---------|
| SanDisk SSD U100 256GB                             | 127       | 3.38%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB  | 38        | 1.01%   |
| Kingston SA400S37240G 240GB SSD                    | 34        | 0.9%    |
| Samsung SSD 860 EVO 500GB                          | 29        | 0.77%   |
| Kingston SA400S37480G 480GB SSD                    | 29        | 0.77%   |
| Unknown MMC Card  64GB                             | 27        | 0.72%   |
| Unknown MMC Card  32GB                             | 25        | 0.67%   |
| Samsung NVMe SSD Drive 512GB                       | 24        | 0.64%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                   | 23        | 0.61%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                   | 22        | 0.59%   |
| Seagate ST1000LM035-1RK172 1TB                     | 22        | 0.59%   |
| Samsung SSD 850 EVO 250GB                          | 22        | 0.59%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB | 22        | 0.59%   |
| Kingston SA400S37120G 120GB SSD                    | 22        | 0.59%   |
| Seagate ST2000DM008-2FR102 2TB                     | 19        | 0.51%   |
| Samsung SSD 980 1TB                                | 17        | 0.45%   |
| HGST HTS721010A9E630 1TB                           | 17        | 0.45%   |
| Samsung NVMe SSD Drive 500GB                       | 16        | 0.43%   |
| Unknown                                            | 16        | 0.43%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                 | 15        | 0.4%    |
| Seagate ST1000DM010-2EP102 1TB                     | 15        | 0.4%    |
| Samsung SSD 860 EVO 1TB                            | 15        | 0.4%    |
| Seagate ST3500418AS 500GB                          | 14        | 0.37%   |
| Kingston SV300S37A120G 120GB SSD                   | 14        | 0.37%   |
| Toshiba NVMe SSD Drive 256GB                       | 13        | 0.35%   |
| Patriot Burst 480GB SSD                            | 13        | 0.35%   |
| Kingston SKC3000D2048G 2TB                         | 13        | 0.35%   |
| A-DATA SU650 120GB SSD                             | 13        | 0.35%   |
| WDC WD10EZEX-08M2NA0 1TB                           | 12        | 0.32%   |
| Unknown MMC Card  128GB                            | 12        | 0.32%   |
| Toshiba MQ01ABD100 1TB                             | 12        | 0.32%   |
| Seagate ST500LT012-1DG142 500GB                    | 12        | 0.32%   |
| Seagate ST500DM002-1BD142 500GB                    | 12        | 0.32%   |
| SanDisk NVMe SSD Drive 512GB                       | 12        | 0.32%   |
| Samsung PM963 2.5" NVMe PCIe SSD 256GB             | 12        | 0.32%   |
| Patriot Burst 120GB SSD                            | 12        | 0.32%   |
| WDC WD30EFRX-68EUZN0 3TB                           | 11        | 0.29%   |
| WDC WD10EZEX-08WN4A0 1TB                           | 11        | 0.29%   |
| Unknown MMC Card  16GB                             | 11        | 0.29%   |
| Seagate ST4000DM004-2CV104 4TB                     | 11        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 453       | 686    | 37.97%  |
| WDC                 | 385       | 644    | 32.27%  |
| Toshiba             | 114       | 130    | 9.56%   |
| Hitachi             | 93        | 108    | 7.8%    |
| HGST                | 56        | 69     | 4.69%   |
| Samsung Electronics | 53        | 82     | 4.44%   |
| Fujitsu             | 10        | 11     | 0.84%   |
| Maxtor              | 9         | 13     | 0.75%   |
| Unknown             | 4         | 4      | 0.34%   |
| JMicron Technology  | 3         | 3      | 0.25%   |
| ASMedia             | 3         | 4      | 0.25%   |
| pqi                 | 2         | 2      | 0.17%   |
| Apple               | 2         | 7      | 0.17%   |
| TO Exter            | 1         | 2      | 0.08%   |
| SABRENT             | 1         | 1      | 0.08%   |
| IBM/Hitachi         | 1         | 1      | 0.08%   |
| Hewlett-Packard     | 1         | 2      | 0.08%   |
| External            | 1         | 1      | 0.08%   |
| ASUSTOR             | 1         | 1      | 0.08%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 221       | 285    | 18.92%  |
| Kingston            | 177       | 220    | 15.15%  |
| SanDisk             | 176       | 184    | 15.07%  |
| WDC                 | 94        | 125    | 8.05%   |
| A-DATA Technology   | 80        | 94     | 6.85%   |
| Crucial             | 72        | 89     | 6.16%   |
| Patriot             | 58        | 71     | 4.97%   |
| Intel               | 45        | 56     | 3.85%   |
| Apacer              | 28        | 37     | 2.4%    |
| Micron Technology   | 27        | 40     | 2.31%   |
| Transcend           | 20        | 28     | 1.71%   |
| Verbatim            | 17        | 18     | 1.46%   |
| SK hynix            | 17        | 18     | 1.46%   |
| Toshiba             | 15        | 19     | 1.28%   |
| LITEONIT            | 12        | 15     | 1.03%   |
| OCZ                 | 10        | 17     | 0.86%   |
| China               | 10        | 11     | 0.86%   |
| GOODRAM             | 8         | 11     | 0.68%   |
| LITEON              | 7         | 8      | 0.6%    |
| Gigabyte Technology | 7         | 14     | 0.6%    |
| UMAX                | 6         | 6      | 0.51%   |
| Seagate             | 6         | 8      | 0.51%   |
| Apple               | 5         | 5      | 0.43%   |
| Team                | 3         | 3      | 0.26%   |
| SPCC                | 3         | 3      | 0.26%   |
| HPE                 | 3         | 3      | 0.26%   |
| Hewlett-Packard     | 3         | 3      | 0.26%   |
| Unknown             | 3         | 3      | 0.26%   |
| Unknown             | 2         | 8      | 0.17%   |
| KingSpec            | 2         | 3      | 0.17%   |
| HS-SSD-C100         | 2         | 2      | 0.17%   |
| FORESEE             | 2         | 2      | 0.17%   |
| ASMT                | 2         | 2      | 0.17%   |
| ADATA SU            | 2         | 2      | 0.17%   |
| WDC WDS1            | 1         | 1      | 0.09%   |
| USB3.0              | 1         | 1      | 0.09%   |
| UMIS                | 1         | 1      | 0.09%   |
| TCSUNBOW            | 1         | 1      | 0.09%   |
| T-CREATE            | 1         | 1      | 0.09%   |
| StoreJet            | 1         | 1      | 0.09%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 1045      | 1436   | 33.88%  |
| HDD     | 1015      | 1771   | 32.91%  |
| NVMe    | 853       | 1244   | 27.66%  |
| MMC     | 151       | 206    | 4.9%    |
| Unknown | 20        | 34     | 0.65%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1695      | 3116   | 60.58%  |
| NVMe | 852       | 1239   | 30.45%  |
| MMC  | 151       | 206    | 5.4%    |
| SAS  | 100       | 130    | 3.57%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 1355      | 2006   | 63.11%  |
| 0.51-1.0   | 525       | 736    | 24.45%  |
| 1.01-2.0   | 127       | 236    | 5.92%   |
| 3.01-4.0   | 52        | 75     | 2.42%   |
| 2.01-3.0   | 36        | 57     | 1.68%   |
| 4.01-10.0  | 33        | 66     | 1.54%   |
| 10.01-20.0 | 19        | 31     | 0.88%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 628       | 24.51%  |
| 251-500        | 538       | 21%     |
| 1-20           | 346       | 13.51%  |
| 501-1000       | 334       | 13.04%  |
| 1001-2000      | 177       | 6.91%   |
| 51-100         | 167       | 6.52%   |
| More than 3000 | 114       | 4.45%   |
| Unknown        | 103       | 4.02%   |
| 21-50          | 95        | 3.71%   |
| 2001-3000      | 59        | 2.3%    |
| 0              | 1         | 0.04%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 1095      | 41.24%  |
| 21-50          | 359       | 13.52%  |
| 101-250        | 333       | 12.54%  |
| 51-100         | 260       | 9.79%   |
| 251-500        | 212       | 7.98%   |
| 501-1000       | 139       | 5.24%   |
| Unknown        | 103       | 3.88%   |
| 1001-2000      | 71        | 2.67%   |
| More than 3000 | 52        | 1.96%   |
| 2001-3000      | 30        | 1.13%   |
| 0              | 1         | 0.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| SanDisk SSD U100 256GB                | 127       | 128    | 38.25%  |
| HGST HTS725050A7E630 500GB            | 4         | 5      | 1.2%    |
| WDC WDS240G2G0A-00JH30 240GB SSD      | 3         | 3      | 0.9%    |
| SK hynix BC711 HFM512GD3JX013N 512GB  | 3         | 4      | 0.9%    |
| WDC WD60EFRX-68L0BN1 6TB              | 2         | 3      | 0.6%    |
| Toshiba MQ01ABD075 752GB              | 2         | 2      | 0.6%    |
| Toshiba MK1234GSX 118GB               | 2         | 2      | 0.6%    |
| Seagate ST9500420AS 500GB             | 2         | 3      | 0.6%    |
| Seagate ST500LT012-9WS142 500GB       | 2         | 4      | 0.6%    |
| Seagate ST500LT0 12-1DG142 500GB      | 2         | 2      | 0.6%    |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 0.6%    |
| Seagate ST3250410AS 250GB             | 2         | 4      | 0.6%    |
| Seagate ST3160318AS 160GB             | 2         | 2      | 0.6%    |
| Seagate ST2000DM008-2FR102 2TB        | 2         | 3      | 0.6%    |
| Seagate ST1000LX015-1U7172 1TB        | 2         | 2      | 0.6%    |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 2         | 2      | 0.6%    |
| Micron Technology 1100 SATA 256GB SSD | 2         | 2      | 0.6%    |
| Kingston SV300S37A120G 120GB SSD      | 2         | 2      | 0.6%    |
| Hitachi HTS541610J9SA00 100GB         | 2         | 2      | 0.6%    |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.6%    |
| HGST HTS545050A7E380 500GB            | 2         | 2      | 0.6%    |
| WDC WDS120G2G0B-00EPW0 120GB SSD      | 1         | 1      | 0.3%    |
| WDC WDS120G2G0A-00JH30 120GB SSD      | 1         | 1      | 0.3%    |
| WDC WDS100T2B0A-00SM50 1TB SSD        | 1         | 1      | 0.3%    |
| WDC WD800BB-00JHA0 80GB               | 1         | 1      | 0.3%    |
| WDC WD7500BPVT-22HXZT3 752GB          | 1         | 1      | 0.3%    |
| WDC WD7500BPKT-75PK4T0 752GB          | 1         | 1      | 0.3%    |
| WDC WD7500AADS-00M2B0 752GB           | 1         | 1      | 0.3%    |
| WDC WD6400BPVT-60HXZT1 640GB          | 1         | 1      | 0.3%    |
| WDC WD6400AAKS-22A7B2 640GB           | 1         | 1      | 0.3%    |
| WDC WD5003ABYX-50WERA1 500GB          | 1         | 1      | 0.3%    |
| WDC WD5000AZRX-00A8LB0 500GB          | 1         | 1      | 0.3%    |
| WDC WD5000AAKX-75U6AA0 500GB          | 1         | 1      | 0.3%    |
| WDC WD5000AAKS-00V0A0 500GB           | 1         | 1      | 0.3%    |
| WDC WD3200BEVT-60ZCT1 320GB           | 1         | 1      | 0.3%    |
| WDC WD3200AAKS-00L9A0 320GB           | 1         | 1      | 0.3%    |
| WDC WD30EFRX-68EUZN0 3TB              | 1         | 1      | 0.3%    |
| WDC WD2502ABYS-02B7A0 256GB           | 1         | 1      | 0.3%    |
| WDC WD2500BPVT-22JJ5T0 250GB          | 1         | 1      | 0.3%    |
| WDC WD2500BEVS-22UST0 250GB           | 1         | 1      | 0.3%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                | Computers | Drives | Percent |
|-----------------------|-----------|--------|---------|
| SanDisk               | 129       | 130    | 39.57%  |
| Seagate               | 51        | 68     | 15.64%  |
| WDC                   | 41        | 51     | 12.58%  |
| Hitachi               | 20        | 20     | 6.13%   |
| Samsung Electronics   | 19        | 24     | 5.83%   |
| Toshiba               | 16        | 19     | 4.91%   |
| HGST                  | 11        | 12     | 3.37%   |
| Kingston              | 7         | 7      | 2.15%   |
| SK hynix              | 6         | 7      | 1.84%   |
| Micron Technology     | 4         | 4      | 1.23%   |
| Intel                 | 4         | 4      | 1.23%   |
| Crucial               | 3         | 3      | 0.92%   |
| A-DATA Technology     | 3         | 5      | 0.92%   |
| SPCC                  | 1         | 1      | 0.31%   |
| SATAFIRM              | 1         | 1      | 0.31%   |
| Realtek Semiconductor | 1         | 4      | 0.31%   |
| Patriot               | 1         | 1      | 0.31%   |
| OCZ                   | 1         | 1      | 0.31%   |
| Neo                   | 1         | 1      | 0.31%   |
| Maxtor                | 1         | 1      | 0.31%   |
| LITEONIT              | 1         | 2      | 0.31%   |
| IBM/Hitachi           | 1         | 1      | 0.31%   |
| HS-SSD-C100           | 1         | 1      | 0.31%   |
| Gigabyte Technology   | 1         | 1      | 0.31%   |
| Fujitsu               | 1         | 1      | 0.31%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 51        | 68     | 35.66%  |
| WDC                 | 34        | 43     | 23.78%  |
| Hitachi             | 20        | 20     | 13.99%  |
| Toshiba             | 16        | 19     | 11.19%  |
| HGST                | 11        | 12     | 7.69%   |
| Samsung Electronics | 8         | 10     | 5.59%   |
| Maxtor              | 1         | 1      | 0.7%    |
| IBM/Hitachi         | 1         | 1      | 0.7%    |
| Fujitsu             | 1         | 1      | 0.7%    |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 169       | 173    | 52.65%  |
| HDD  | 137       | 175    | 42.68%  |
| NVMe | 15        | 22     | 4.67%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                     | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate ST3500418AS 500GB | 2         | 4      | 40%     |
| Unknown 00000  16GB       | 1         | 1      | 20%     |
| Intel SSDSC2BW240H6 240GB | 1         | 1      | 20%     |
| Intel SSDSC2BW120H6 120GB | 1         | 1      | 20%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 2         | 4      | 40%     |
| Intel   | 2         | 2      | 40%     |
| Unknown | 1         | 1      | 20%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 1308      | 2595   | 50.1%   |
| Works    | 983       | 1719   | 37.65%  |
| Malfunc  | 315       | 370    | 12.06%  |
| Failed   | 5         | 7      | 0.19%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Intel                                   | 1530      | 49.9%   |
| AMD                                     | 474       | 15.46%  |
| Samsung Electronics                     | 322       | 10.5%   |
| SanDisk                                 | 118       | 3.85%   |
| SK hynix                                | 84        | 2.74%   |
| Kingston Technology Company             | 78        | 2.54%   |
| Toshiba America Info Systems            | 55        | 1.79%   |
| Micron Technology                       | 49        | 1.6%    |
| Phison Electronics                      | 41        | 1.34%   |
| JMicron Technology                      | 38        | 1.24%   |
| ASMedia Technology                      | 36        | 1.17%   |
| Nvidia                                  | 31        | 1.01%   |
| KIOXIA                                  | 31        | 1.01%   |
| Marvell Technology Group                | 29        | 0.95%   |
| Micron/Crucial Technology               | 20        | 0.65%   |
| ADATA Technology                        | 20        | 0.65%   |
| Silicon Motion                          | 18        | 0.59%   |
| VIA Technologies                        | 11        | 0.36%   |
| Seagate Technology                      | 8         | 0.26%   |
| Realtek Semiconductor                   | 8         | 0.26%   |
| Hewlett-Packard                         | 6         | 0.2%    |
| Broadcom / LSI                          | 6         | 0.2%    |
| Union Memory (Shenzhen)                 | 5         | 0.16%   |
| MAXIO Technology (Hangzhou)             | 5         | 0.16%   |
| Solid State Storage Technology          | 4         | 0.13%   |
| Silicon Image                           | 4         | 0.13%   |
| LSI Logic / Symbios Logic               | 4         | 0.13%   |
| Lite-On Technology                      | 4         | 0.13%   |
| Lenovo                                  | 4         | 0.13%   |
| Silicon Integrated Systems [SiS]        | 3         | 0.1%    |
| Hosin Global Electronics                | 3         | 0.1%    |
| Adaptec                                 | 3         | 0.1%    |
| OCZ Technology Group                    | 2         | 0.07%   |
| Integrated Technology Express           | 2         | 0.07%   |
| Western Digital                         | 1         | 0.03%   |
| Solidigm                                | 1         | 0.03%   |
| Shenzhen Unionmemory Information System | 1         | 0.03%   |
| Promise Technology                      | 1         | 0.03%   |
| O2 Micro                                | 1         | 0.03%   |
| INNOGRIT                                | 1         | 0.03%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 299       | 8.44%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 198       | 5.59%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 141       | 3.98%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 104       | 2.94%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 92        | 2.6%    |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 90        | 2.54%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                    | 88        | 2.48%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 69        | 1.95%   |
| AMD 400 Series Chipset SATA Controller                                         | 65        | 1.84%   |
| Intel Volume Management Device NVMe RAID Controller                            | 63        | 1.78%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 55        | 1.55%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 47        | 1.33%   |
| AMD 500 Series Chipset SATA Controller                                         | 47        | 1.33%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 46        | 1.3%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 45        | 1.27%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 45        | 1.27%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 44        | 1.24%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 41        | 1.16%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 40        | 1.13%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 40        | 1.13%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 39        | 1.1%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 37        | 1.04%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 34        | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 33        | 0.93%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 33        | 0.93%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                  | 33        | 0.93%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 32        | 0.9%    |
| Intel Atom Processor E3800 Series SATA AHCI Controller                         | 32        | 0.9%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 31        | 0.88%   |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD           | 30        | 0.85%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                           | 29        | 0.82%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                      | 29        | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 29        | 0.82%   |
| Kingston Company KC3000/FURY Renegade NVMe SSD E18                             | 26        | 0.73%   |
| Intel SATA Controller [RAID mode]                                              | 26        | 0.73%   |
| Intel Comet Lake SATA AHCI Controller                                          | 26        | 0.73%   |
| JMicron JMB363 SATA/IDE Controller                                             | 25        | 0.71%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 25        | 0.71%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 24        | 0.68%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                            | 23        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1687      | 54.77%  |
| NVMe | 860       | 27.92%  |
| IDE  | 329       | 10.68%  |
| RAID | 188       | 6.1%    |
| SAS  | 11        | 0.36%   |
| SCSI | 5         | 0.16%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor   | Computers | Percent |
|----------|-----------|---------|
| Intel    | 1766      | 73.01%  |
| AMD      | 633       | 26.17%  |
| ARM      | 18        | 0.74%   |
| QUALCOMM | 1         | 0.04%   |
| MIPS     | 1         | 0.04%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-2677M CPU @ 1.80GHz             | 127       | 5.22%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 26        | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 22        | 0.9%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 21        | 0.86%   |
| AMD Ryzen 5 3600 6-Core Processor             | 21        | 0.86%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 20        | 0.82%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 19        | 0.78%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 18        | 0.74%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 18        | 0.74%   |
| AMD Ryzen 7 4700U with Radeon Graphics        | 18        | 0.74%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 17        | 0.7%    |
| AMD Ryzen 7 5800H with Radeon Graphics        | 16        | 0.66%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 15        | 0.62%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 15        | 0.62%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 15        | 0.62%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 15        | 0.62%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 15        | 0.62%   |
| Intel Core i7-8650U CPU @ 1.90GHz             | 14        | 0.58%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 14        | 0.58%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 14        | 0.58%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 14        | 0.58%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 14        | 0.58%   |
| ARM Processor                                 | 14        | 0.58%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 14        | 0.58%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 13        | 0.53%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 13        | 0.53%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 13        | 0.53%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 12        | 0.49%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 12        | 0.49%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 12        | 0.49%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 11        | 0.45%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 11        | 0.45%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 11        | 0.45%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 11        | 0.45%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 11        | 0.45%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 10        | 0.41%   |
| Intel Celeron N4100 CPU @ 1.10GHz             | 10        | 0.41%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 10        | 0.41%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 10        | 0.41%   |
| AMD Custom APU 0405                           | 10        | 0.41%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 503       | 20.71%  |
| Intel Core i5           | 436       | 17.95%  |
| AMD Ryzen 5             | 183       | 7.53%   |
| Other                   | 182       | 7.49%   |
| Intel Celeron           | 140       | 5.76%   |
| Intel Core 2 Duo        | 124       | 5.1%    |
| Intel Core i3           | 118       | 4.86%   |
| AMD Ryzen 7             | 115       | 4.73%   |
| Intel Pentium           | 73        | 3.01%   |
| Intel Xeon              | 49        | 2.02%   |
| Intel Atom              | 43        | 1.77%   |
| AMD Ryzen 7 PRO         | 38        | 1.56%   |
| AMD FX                  | 38        | 1.56%   |
| AMD Ryzen 9             | 31        | 1.28%   |
| Intel Pentium Dual-Core | 27        | 1.11%   |
| AMD Ryzen 3             | 24        | 0.99%   |
| AMD A4                  | 20        | 0.82%   |
| AMD A8                  | 18        | 0.74%   |
| AMD Ryzen 5 PRO         | 16        | 0.66%   |
| AMD A6                  | 16        | 0.66%   |
| Intel Core 2            | 15        | 0.62%   |
| AMD Athlon 64 X2        | 13        | 0.54%   |
| Intel Pentium Silver    | 12        | 0.49%   |
| Intel Pentium Dual      | 12        | 0.49%   |
| Intel Core 2 Quad       | 11        | 0.45%   |
| Intel Core i9           | 10        | 0.41%   |
| AMD Phenom II X4        | 10        | 0.41%   |
| AMD A10                 | 10        | 0.41%   |
| Intel Genuine           | 9         | 0.37%   |
| AMD Athlon II X2        | 9         | 0.37%   |
| AMD Athlon              | 9         | 0.37%   |
| Intel Celeron M         | 8         | 0.33%   |
| AMD E1                  | 7         | 0.29%   |
| Intel Pentium Gold      | 6         | 0.25%   |
| Intel Pentium 4         | 5         | 0.21%   |
| Intel Celeron Dual-Core | 5         | 0.21%   |
| AMD Sempron             | 5         | 0.21%   |
| Intel Pentium M         | 4         | 0.16%   |
| Intel Pentium D         | 4         | 0.16%   |
| AMD Turion II           | 4         | 0.16%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1004      | 41.3%   |
| 4       | 771       | 31.72%  |
| 6       | 285       | 11.72%  |
| 8       | 187       | 7.69%   |
| 1       | 65        | 2.67%   |
| 12      | 46        | 1.89%   |
| 14      | 17        | 0.7%    |
| 10      | 15        | 0.62%   |
| 16      | 14        | 0.58%   |
| 3       | 14        | 0.58%   |
| 24      | 5         | 0.21%   |
| Unknown | 4         | 0.16%   |
| 20      | 2         | 0.08%   |
| 32      | 1         | 0.04%   |
| 28      | 1         | 0.04%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 2400      | 99.21%  |
| 2       | 18        | 0.74%   |
| Unknown | 1         | 0.04%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1598      | 65.92%  |
| 1       | 821       | 33.87%  |
| Unknown | 4         | 0.17%   |
| 4       | 1         | 0.04%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 2357      | 97.12%  |
| Unknown        | 39        | 1.61%   |
| 32-bit         | 27        | 1.11%   |
| 64-bit         | 4         | 0.16%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 741       | 29.35%  |
| 0x206a7    | 220       | 8.71%   |
| 0x306c3    | 84        | 3.33%   |
| 0x1067a    | 78        | 3.09%   |
| 0x306a9    | 74        | 2.93%   |
| 0x906ea    | 51        | 2.02%   |
| 0x806ec    | 51        | 2.02%   |
| 0x806ea    | 48        | 1.9%    |
| 0x806c1    | 42        | 1.66%   |
| 0x0a50000c | 40        | 1.58%   |
| 0x406e3    | 39        | 1.54%   |
| 0x08600106 | 37        | 1.47%   |
| 0x806e9    | 35        | 1.39%   |
| 0x506e3    | 35        | 1.39%   |
| 0x40651    | 34        | 1.35%   |
| 0x6fd      | 32        | 1.27%   |
| 0x906e9    | 31        | 1.23%   |
| 0x08701021 | 27        | 1.07%   |
| 0x306d4    | 26        | 1.03%   |
| 0x30678    | 24        | 0.95%   |
| 0x10676    | 22        | 0.87%   |
| 0x6fb      | 21        | 0.83%   |
| 0x406c4    | 20        | 0.79%   |
| 0x010000c8 | 20        | 0.79%   |
| 0x20655    | 19        | 0.75%   |
| 0x06000852 | 19        | 0.75%   |
| 0x706a1    | 18        | 0.71%   |
| 0x0800820d | 18        | 0.71%   |
| 0xa0652    | 17        | 0.67%   |
| 0x08608103 | 17        | 0.67%   |
| 0x706a8    | 16        | 0.63%   |
| 0x506c9    | 16        | 0.63%   |
| 0x08600104 | 16        | 0.63%   |
| 0x906ed    | 15        | 0.59%   |
| 0x706e5    | 15        | 0.59%   |
| 0x08108102 | 15        | 0.59%   |
| 0x0a50000d | 14        | 0.55%   |
| 0x06006705 | 14        | 0.55%   |
| 0x406c3    | 13        | 0.51%   |
| 0x08701013 | 13        | 0.51%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 348       | 14.36%  |
| SandyBridge      | 283       | 11.68%  |
| Haswell          | 172       | 7.1%    |
| Zen 2            | 139       | 5.74%   |
| Penryn           | 129       | 5.32%   |
| IvyBridge        | 123       | 5.08%   |
| Zen 3            | 113       | 4.66%   |
| Unknown          | 113       | 4.66%   |
| Skylake          | 104       | 4.29%   |
| Core             | 87        | 3.59%   |
| Silvermont       | 83        | 3.43%   |
| TigerLake        | 64        | 2.64%   |
| Zen+             | 55        | 2.27%   |
| Goldmont plus    | 50        | 2.06%   |
| Alderlake Hybrid | 50        | 2.06%   |
| Zen              | 49        | 2.02%   |
| Piledriver       | 48        | 1.98%   |
| Westmere         | 47        | 1.94%   |
| CometLake        | 46        | 1.9%    |
| K10              | 41        | 1.69%   |
| Broadwell        | 40        | 1.65%   |
| K8 Hammer        | 30        | 1.24%   |
| Excavator        | 30        | 1.24%   |
| IceLake          | 29        | 1.2%    |
| Goldmont         | 20        | 0.83%   |
| Bonnell          | 19        | 0.78%   |
| Nehalem          | 17        | 0.7%    |
| Steamroller      | 14        | 0.58%   |
| P6               | 14        | 0.58%   |
| Puma             | 13        | 0.54%   |
| NetBurst         | 11        | 0.45%   |
| Bobcat           | 11        | 0.45%   |
| Jaguar           | 10        | 0.41%   |
| Tremont          | 7         | 0.29%   |
| K10 Llano        | 6         | 0.25%   |
| Bulldozer        | 4         | 0.17%   |
| K8 & K10 hybrid  | 3         | 0.12%   |
| K6               | 1         | 0.04%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 1414      | 49.77%  |
| Nvidia                           | 716       | 25.2%   |
| AMD                              | 684       | 24.08%  |
| Matrox Electronics Systems       | 17        | 0.6%    |
| ASPEED Technology                | 5         | 0.18%   |
| VIA Technologies                 | 2         | 0.07%   |
| Silicon Integrated Systems [SiS] | 2         | 0.07%   |
| ATI Technologies                 | 1         | 0.04%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 240       | 8.13%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]                            | 79        | 2.68%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 78        | 2.64%   |
| Intel UHD Graphics 620                                                                   | 69        | 2.34%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 53        | 1.8%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 53        | 1.8%    |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 51        | 1.73%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 49        | 1.66%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 49        | 1.66%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 44        | 1.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 44        | 1.49%   |
| Intel HD Graphics 620                                                                    | 43        | 1.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 42        | 1.42%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 42        | 1.42%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 42        | 1.42%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 41        | 1.39%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 40        | 1.36%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 38        | 1.29%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 36        | 1.22%   |
| Intel HD Graphics 630                                                                    | 33        | 1.12%   |
| Intel HD Graphics 5500                                                                   | 32        | 1.08%   |
| Intel HD Graphics 530                                                                    | 29        | 0.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 27        | 0.91%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                                | 25        | 0.85%   |
| AMD Lucienne                                                                             | 25        | 0.85%   |
| Intel Core Processor Integrated Graphics Controller                                      | 23        | 0.78%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 23        | 0.78%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 22        | 0.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 22        | 0.75%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 21        | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 21        | 0.71%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 21        | 0.71%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 21        | 0.71%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 21        | 0.71%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 21        | 0.71%   |
| Intel HD Graphics 500                                                                    | 18        | 0.61%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 18        | 0.61%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 16        | 0.54%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 16        | 0.54%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 16        | 0.54%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 1027      | 42.18%  |
| 1 x AMD        | 517       | 21.23%  |
| 1 x Nvidia     | 366       | 15.03%  |
| Intel + Nvidia | 297       | 12.2%   |
| Intel + AMD    | 70        | 2.87%   |
| 2 x AMD        | 49        | 2.01%   |
| AMD + Nvidia   | 46        | 1.89%   |
| Other          | 21        | 0.86%   |
| 1 x Matrox     | 15        | 0.62%   |
| 2 x Intel      | 10        | 0.41%   |
| 1 x ASPEED     | 5         | 0.21%   |
| 2 x Nvidia     | 4         | 0.16%   |
| 3 x Nvidia     | 2         | 0.08%   |
| 1 x VIA        | 2         | 0.08%   |
| 1 x SiS        | 2         | 0.08%   |
| AMD + Matrox   | 2         | 0.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1998      | 81.38%  |
| Proprietary | 359       | 14.62%  |
| Unknown     | 98        | 3.99%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1472      | 58.88%  |
| 0.01-0.5   | 301       | 12.04%  |
| 1.01-2.0   | 262       | 10.48%  |
| 0.51-1.0   | 156       | 6.24%   |
| 3.01-4.0   | 138       | 5.52%   |
| 7.01-8.0   | 72        | 2.88%   |
| 5.01-6.0   | 45        | 1.8%    |
| 8.01-16.0  | 25        | 1%      |
| 2.01-3.0   | 22        | 0.88%   |
| 16.01-24.0 | 5         | 0.2%    |
| 4.01-5.0   | 2         | 0.08%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 351       | 12.46%  |
| Samsung Electronics     | 313       | 11.11%  |
| LG Display              | 234       | 8.31%   |
| Chimei Innolux          | 199       | 7.06%   |
| BOE                     | 198       | 7.03%   |
| Dell                    | 183       | 6.5%    |
| CPT                     | 129       | 4.58%   |
| Goldstar                | 115       | 4.08%   |
| BenQ                    | 105       | 3.73%   |
| Acer                    | 97        | 3.44%   |
| Philips                 | 92        | 3.27%   |
| Hewlett-Packard         | 88        | 3.12%   |
| Eizo                    | 85        | 3.02%   |
| AOC                     | 73        | 2.59%   |
| Lenovo                  | 65        | 2.31%   |
| Ancor Communications    | 51        | 1.81%   |
| Sharp                   | 48        | 1.7%    |
| Iiyama                  | 37        | 1.31%   |
| Chi Mei Optoelectronics | 35        | 1.24%   |
| PANDA                   | 32        | 1.14%   |
| ASUSTek Computer        | 21        | 0.75%   |
| InfoVision              | 20        | 0.71%   |
| CSO                     | 20        | 0.71%   |
| Sony                    | 19        | 0.67%   |
| LG Philips              | 18        | 0.64%   |
| Fujitsu Siemens         | 17        | 0.6%    |
| Panasonic               | 14        | 0.5%    |
| NEC Computers           | 13        | 0.46%   |
| Apple                   | 10        | 0.35%   |
| ViewSonic               | 9         | 0.32%   |
| Unknown                 | 9         | 0.32%   |
| MSI                     | 9         | 0.32%   |
| Vestel Elektronik       | 8         | 0.28%   |
| Valve                   | 7         | 0.25%   |
| Quanta Display          | 6         | 0.21%   |
| LG Electronics          | 6         | 0.21%   |
| HannStar                | 6         | 0.21%   |
| Toshiba                 | 4         | 0.14%   |
| Lenovo Group Limited    | 4         | 0.14%   |
| Hitachi                 | 4         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| CPT LCD Monitor COR17DB 1600x900 293x164mm 13.2-inch                     | 127       | 4.33%   |
| Eizo EV3285 ENC2979 3840x2160 698x393mm 31.5-inch                        | 57        | 1.94%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x174mm 14.0-inch           | 15        | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 15        | 0.51%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 14        | 0.48%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                        | 14        | 0.48%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 14        | 0.48%   |
| AOC Q3279WG5B AOC3279 2560x1440 725x428mm 33.1-inch                      | 13        | 0.44%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                  | 12        | 0.41%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 12        | 0.41%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 10        | 0.34%   |
| Vestel Elektronik 22W_LCD_TV VES3700 1920x540                            | 8         | 0.27%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch     | 8         | 0.27%   |
| Panasonic TV MEIA296 1920x1080 698x392mm 31.5-inch                       | 8         | 0.27%   |
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 8         | 0.27%   |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 8         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 8         | 0.27%   |
| AU Optronics LCD Monitor AUO34ED 1920x1080 344x193mm 15.5-inch           | 8         | 0.27%   |
| Sharp LCD Monitor SHP1453 1920x1080 346x194mm 15.6-inch                  | 7         | 0.24%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 7         | 0.24%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 7         | 0.24%   |
| Philips PHL 273V7 PHLC156 1920x1080 598x336mm 27.0-inch                  | 7         | 0.24%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 7         | 0.24%   |
| Lenovo LCD Monitor LEN40BA 1920x1080 344x194mm 15.5-inch                 | 7         | 0.24%   |
| Dell P2419H DELD0D9 1920x1080 527x296mm 23.8-inch                        | 7         | 0.24%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 7         | 0.24%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                    | 7         | 0.24%   |
| BenQ GW2470 BNQ78D9 1920x1080 527x296mm 23.8-inch                        | 7         | 0.24%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 7         | 0.24%   |
| Valve ANX7530 U VLV3001 800x1280 100x150mm 7.1-inch                      | 6         | 0.2%    |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch     | 6         | 0.2%    |
| LG Display LCD Monitor LGD046F 1920x1080 340x190mm 15.3-inch             | 6         | 0.2%    |
| LG Display LCD Monitor LGD02F1 1366x768 344x194mm 15.5-inch              | 6         | 0.2%    |
| Dell U2412M DELA07B 1920x1200 518x324mm 24.1-inch                        | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch         | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14D5 1920x1080 309x173mm 13.9-inch         | 6         | 0.2%    |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch         | 6         | 0.2%    |
| BOE LCD Monitor BOE07BB 1920x1080 309x173mm 13.9-inch                    | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO2E8D 1920x1080 344x194mm 15.5-inch           | 6         | 0.2%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 6         | 0.2%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 1185      | 44.7%   |
| 1366x768 (WXGA)    | 318       | 12%     |
| 1600x900 (HD+)     | 213       | 8.03%   |
| 3840x2160 (4K)     | 193       | 7.28%   |
| 2560x1440 (QHD)    | 140       | 5.28%   |
| 1920x1200 (WUXGA)  | 99        | 3.73%   |
| 1280x1024 (SXGA)   | 90        | 3.39%   |
| 1680x1050 (WSXGA+) | 85        | 3.21%   |
| 1280x800 (WXGA)    | 67        | 2.53%   |
| 1440x900 (WXGA+)   | 39        | 1.47%   |
| 2560x1600          | 27        | 1.02%   |
| 3440x1440          | 17        | 0.64%   |
| Unknown            | 17        | 0.64%   |
| 2560x1080          | 14        | 0.53%   |
| 2880x1800          | 13        | 0.49%   |
| 1600x1200          | 11        | 0.41%   |
| 1024x768 (XGA)     | 11        | 0.41%   |
| 3840x1080          | 10        | 0.38%   |
| 1360x768           | 10        | 0.38%   |
| 1024x600           | 9         | 0.34%   |
| 800x1280           | 7         | 0.26%   |
| 2288x1287          | 6         | 0.23%   |
| 1920x540           | 6         | 0.23%   |
| 1280x720 (HD)      | 6         | 0.23%   |
| 2160x1350          | 5         | 0.19%   |
| 3840x2400          | 4         | 0.15%   |
| 2160x1440          | 4         | 0.15%   |
| 1400x1050          | 4         | 0.15%   |
| 3456x2160          | 3         | 0.11%   |
| 3000x2000          | 3         | 0.11%   |
| 2880x1620          | 3         | 0.11%   |
| 2736x1824          | 3         | 0.11%   |
| 6400x2160          | 2         | 0.08%   |
| 3840x1600          | 2         | 0.08%   |
| 3840x1200          | 2         | 0.08%   |
| 3200x1800 (QHD+)   | 2         | 0.08%   |
| 1280x768           | 2         | 0.08%   |
| 9600x2160          | 1         | 0.04%   |
| 8320x2160          | 1         | 0.04%   |
| 7680x2160          | 1         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 633       | 22.36%  |
| 13      | 355       | 12.54%  |
| 24      | 287       | 10.14%  |
| 14      | 225       | 7.95%   |
| 27      | 206       | 7.28%   |
| 23      | 156       | 5.51%   |
| 21      | 133       | 4.7%    |
| 17      | 131       | 4.63%   |
| 31      | 109       | 3.85%   |
| 19      | 81        | 2.86%   |
| Unknown | 79        | 2.79%   |
| 22      | 55        | 1.94%   |
| 12      | 45        | 1.59%   |
| 11      | 39        | 1.38%   |
| 16      | 37        | 1.31%   |
| 20      | 36        | 1.27%   |
| 34      | 26        | 0.92%   |
| 18      | 24        | 0.85%   |
| 84      | 23        | 0.81%   |
| 33      | 14        | 0.49%   |
| 26      | 13        | 0.46%   |
| 32      | 12        | 0.42%   |
| 25      | 12        | 0.42%   |
| 40      | 11        | 0.39%   |
| 10      | 11        | 0.39%   |
| 54      | 10        | 0.35%   |
| 72      | 9         | 0.32%   |
| 7       | 7         | 0.25%   |
| 65      | 5         | 0.18%   |
| 52      | 5         | 0.18%   |
| 28      | 5         | 0.18%   |
| 47      | 4         | 0.14%   |
| 46      | 4         | 0.14%   |
| 43      | 4         | 0.14%   |
| 39      | 4         | 0.14%   |
| 142     | 3         | 0.11%   |
| 49      | 3         | 0.11%   |
| 48      | 3         | 0.11%   |
| 29      | 3         | 0.11%   |
| 38      | 2         | 0.07%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 1020      | 37%     |
| 501-600        | 594       | 21.55%  |
| 201-300        | 328       | 11.9%   |
| 401-500        | 261       | 9.47%   |
| 351-400        | 186       | 6.75%   |
| 601-700        | 133       | 4.82%   |
| Unknown        | 79        | 2.87%   |
| 701-800        | 51        | 1.85%   |
| 1001-1500      | 39        | 1.41%   |
| 1501-2000      | 32        | 1.16%   |
| 801-900        | 20        | 0.73%   |
| 1-100          | 7         | 0.25%   |
| More than 2000 | 3         | 0.11%   |
| 901-1000       | 3         | 0.11%   |
| 101-200        | 1         | 0.04%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1829      | 74.47%  |
| 16/10   | 369       | 15.02%  |
| 5/4     | 96        | 3.91%   |
| Unknown | 66        | 2.69%   |
| 4/3     | 30        | 1.22%   |
| 21/9    | 28        | 1.14%   |
| 3/2     | 21        | 0.86%   |
| 0.67    | 6         | 0.24%   |
| 32/9    | 4         | 0.16%   |
| 1.00    | 3         | 0.12%   |
| 3.20    | 2         | 0.08%   |
| 3.73    | 1         | 0.04%   |
| 0.62    | 1         | 0.04%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 628       | 22.41%  |
| 201-250        | 480       | 17.13%  |
| 81-90          | 354       | 12.63%  |
| 71-80          | 227       | 8.1%    |
| 301-350        | 219       | 7.82%   |
| 351-500        | 165       | 5.89%   |
| 151-200        | 146       | 5.21%   |
| 251-300        | 117       | 4.18%   |
| 121-130        | 82        | 2.93%   |
| Unknown        | 79        | 2.82%   |
| More than 1000 | 60        | 2.14%   |
| 141-150        | 50        | 1.78%   |
| 61-70          | 40        | 1.43%   |
| 51-60          | 39        | 1.39%   |
| 501-1000       | 36        | 1.28%   |
| 111-120        | 34        | 1.21%   |
| 131-140        | 17        | 0.61%   |
| 41-50          | 12        | 0.43%   |
| 91-100         | 10        | 0.36%   |
| 1-40           | 7         | 0.25%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 894       | 33.76%  |
| 51-100        | 883       | 33.35%  |
| 101-120       | 522       | 19.71%  |
| 161-240       | 185       | 6.99%   |
| Unknown       | 79        | 2.98%   |
| 1-50          | 45        | 1.7%    |
| More than 240 | 40        | 1.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1820      | 72.92%  |
| 2     | 494       | 19.79%  |
| 0     | 110       | 4.41%   |
| 3     | 67        | 2.68%   |
| 4     | 5         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1185      | 32.67%  |
| Intel                                  | 1148      | 31.65%  |
| Qualcomm Atheros                       | 472       | 13.01%  |
| Broadcom                               | 161       | 4.44%   |
| Samsung Electronics                    | 133       | 3.67%   |
| MediaTek                               | 73        | 2.01%   |
| Broadcom Limited                       | 59        | 1.63%   |
| Marvell Technology Group               | 43        | 1.19%   |
| TP-Link                                | 34        | 0.94%   |
| Lenovo                                 | 28        | 0.77%   |
| Ralink Technology                      | 26        | 0.72%   |
| Qualcomm Atheros Communications        | 23        | 0.63%   |
| Ralink                                 | 22        | 0.61%   |
| Nvidia                                 | 22        | 0.61%   |
| ASIX Electronics                       | 19        | 0.52%   |
| DisplayLink                            | 17        | 0.47%   |
| Dell                                   | 17        | 0.47%   |
| Sierra Wireless                        | 16        | 0.44%   |
| Qualcomm                               | 11        | 0.3%    |
| ASUSTek Computer                       | 9         | 0.25%   |
| Xiaomi                                 | 7         | 0.19%   |
| D-Link                                 | 7         | 0.19%   |
| VIA Technologies                       | 6         | 0.17%   |
| Microsoft                              | 6         | 0.17%   |
| QLogic                                 | 5         | 0.14%   |
| Hewlett-Packard                        | 5         | 0.14%   |
| Ericsson Business Mobile Networks      | 5         | 0.14%   |
| Attansic Technology                    | 5         | 0.14%   |
| ZyDAS                                  | 3         | 0.08%   |
| Sony Ericsson Mobile Communications AB | 3         | 0.08%   |
| OnePlus Technology (Shenzhen)          | 3         | 0.08%   |
| Mellanox Technologies                  | 3         | 0.08%   |
| Huawei Technologies                    | 3         | 0.08%   |
| FIBOCOM                                | 3         | 0.08%   |
| Edimax Technology                      | 3         | 0.08%   |
| Spreadtrum Communications              | 2         | 0.06%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.06%   |
| NetGear                                | 2         | 0.06%   |
| Microchip Technology                   | 2         | 0.06%   |
| IBM                                    | 2         | 0.06%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 820       | 19.34%  |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 157       | 3.7%    |
| Samsung Galaxy series, misc. (tethering mode)                          | 129       | 3.04%   |
| Intel Wi-Fi 6 AX200                                                    | 119       | 2.81%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 114       | 2.69%   |
| Intel Wireless 8265 / 8275                                             | 89        | 2.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 86        | 2.03%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 82        | 1.93%   |
| Realtek RTL8125 2.5GbE Controller                                      | 58        | 1.37%   |
| Intel Wireless 7260                                                    | 52        | 1.23%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 51        | 1.2%    |
| Intel Wi-Fi 6 AX201                                                    | 50        | 1.18%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 45        | 1.06%   |
| Intel Wireless 7265                                                    | 44        | 1.04%   |
| Intel Wireless 8260                                                    | 43        | 1.01%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 41        | 0.97%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 41        | 0.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter             | 40        | 0.94%   |
| Intel Ethernet Connection I217-LM                                      | 39        | 0.92%   |
| Intel I211 Gigabit Network Connection                                  | 38        | 0.9%    |
| Intel Ethernet Connection (4) I219-LM                                  | 36        | 0.85%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 36        | 0.85%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 36        | 0.85%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 35        | 0.83%   |
| Intel Wireless 3165                                                    | 35        | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                        | 34        | 0.8%    |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                        | 33        | 0.78%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 32        | 0.75%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter             | 31        | 0.73%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 27        | 0.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 26        | 0.61%   |
| Intel Ethernet Controller I225-V                                       | 24        | 0.57%   |
| Intel Ethernet Connection (2) I219-V                                   | 24        | 0.57%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 23        | 0.54%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 23        | 0.54%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 22        | 0.52%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 21        | 0.5%    |
| Qualcomm Atheros AR9271 802.11n                                        | 20        | 0.47%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter          | 20        | 0.47%   |
| Intel Comet Lake PCH CNVi WiFi                                         | 20        | 0.47%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 913       | 48.13%  |
| Qualcomm Atheros                | 376       | 19.82%  |
| Realtek Semiconductor           | 236       | 12.44%  |
| Broadcom                        | 96        | 5.06%   |
| MediaTek                        | 67        | 3.53%   |
| TP-Link                         | 32        | 1.69%   |
| Broadcom Limited                | 30        | 1.58%   |
| Ralink Technology               | 26        | 1.37%   |
| Qualcomm Atheros Communications | 23        | 1.21%   |
| Ralink                          | 22        | 1.16%   |
| Sierra Wireless                 | 16        | 0.84%   |
| Dell                            | 11        | 0.58%   |
| Qualcomm                        | 8         | 0.42%   |
| ASUSTek Computer                | 8         | 0.42%   |
| Microsoft                       | 6         | 0.32%   |
| D-Link                          | 6         | 0.32%   |
| ZyDAS                           | 3         | 0.16%   |
| FIBOCOM                         | 3         | 0.16%   |
| Edimax Technology               | 3         | 0.16%   |
| NetGear                         | 2         | 0.11%   |
| Marvell Technology Group        | 2         | 0.11%   |
| Hewlett-Packard                 | 2         | 0.11%   |
| ZyXEL Communications            | 1         | 0.05%   |
| Texas Instruments               | 1         | 0.05%   |
| Mercucys                        | 1         | 0.05%   |
| Intersil                        | 1         | 0.05%   |
| Fujitsu Siemens Computers       | 1         | 0.05%   |
| D-Link System                   | 1         | 0.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 157       | 8.26%   |
| Intel Wi-Fi 6 AX200                                            | 119       | 6.26%   |
| Intel Wireless 8265 / 8275                                     | 89        | 4.68%   |
| Intel Wireless 7260                                            | 52        | 2.74%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 51        | 2.68%   |
| Intel Wi-Fi 6 AX201                                            | 50        | 2.63%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 45        | 2.37%   |
| Intel Wireless 7265                                            | 44        | 2.31%   |
| Intel Wireless 8260                                            | 43        | 2.26%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 41        | 2.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 41        | 2.16%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 40        | 2.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 36        | 1.89%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 36        | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 35        | 1.84%   |
| Intel Wireless 3165                                            | 35        | 1.84%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 34        | 1.79%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 33        | 1.74%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 32        | 1.68%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 31        | 1.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 27        | 1.42%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 26        | 1.37%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 23        | 1.21%   |
| Qualcomm Atheros AR9271 802.11n                                | 20        | 1.05%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 20        | 1.05%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 20        | 1.05%   |
| Intel WiFi Link 5100                                           | 19        | 1%      |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 19        | 1%      |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 18        | 0.95%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 18        | 0.95%   |
| Intel Wireless 3160                                            | 17        | 0.89%   |
| Intel Wi-Fi 6E(802.11ax) AX210/AX1675* 2x2 [Typhoon Peak]      | 17        | 0.89%   |
| Intel Gemini Lake PCH CNVi WiFi                                | 17        | 0.89%   |
| Broadcom BCM43142 802.11b/g/n                                  | 17        | 0.89%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 15        | 0.79%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 13        | 0.68%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 13        | 0.68%   |
| Ralink MT7601U Wireless Adapter                                | 13        | 0.68%   |
| Intel Centrino Wireless-N 2230                                 | 13        | 0.68%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 13        | 0.68%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 1078      | 48.17%  |
| Intel                                  | 589       | 26.32%  |
| Qualcomm Atheros                       | 137       | 6.12%   |
| Samsung Electronics                    | 133       | 5.94%   |
| Broadcom                               | 77        | 3.44%   |
| Marvell Technology Group               | 42        | 1.88%   |
| Broadcom Limited                       | 29        | 1.3%    |
| Lenovo                                 | 28        | 1.25%   |
| Nvidia                                 | 22        | 0.98%   |
| ASIX Electronics                       | 19        | 0.85%   |
| DisplayLink                            | 17        | 0.76%   |
| Xiaomi                                 | 7         | 0.31%   |
| MediaTek                               | 6         | 0.27%   |
| VIA Technologies                       | 5         | 0.22%   |
| QLogic                                 | 5         | 0.22%   |
| Attansic Technology                    | 5         | 0.22%   |
| Qualcomm                               | 3         | 0.13%   |
| Mellanox Technologies                  | 3         | 0.13%   |
| TP-Link                                | 2         | 0.09%   |
| Spreadtrum Communications              | 2         | 0.09%   |
| Sony Ericsson Mobile Communications AB | 2         | 0.09%   |
| Silicon Integrated Systems [SiS]       | 2         | 0.09%   |
| Microchip Technology                   | 2         | 0.09%   |
| IBM                                    | 2         | 0.09%   |
| Huawei Technologies                    | 2         | 0.09%   |
| Google                                 | 2         | 0.09%   |
| Aquantia                               | 2         | 0.09%   |
| American Megatrends                    | 2         | 0.09%   |
| Sundance Technology Inc / IC Plus      | 1         | 0.04%   |
| Motorola PCS                           | 1         | 0.04%   |
| MosChip Semiconductor                  | 1         | 0.04%   |
| JMicron Technology                     | 1         | 0.04%   |
| ICS Advent                             | 1         | 0.04%   |
| Hewlett-Packard                        | 1         | 0.04%   |
| Foxconn / Hon Hai                      | 1         | 0.04%   |
| Emulex                                 | 1         | 0.04%   |
| D-Link System                          | 1         | 0.04%   |
| D-Link                                 | 1         | 0.04%   |
| Chelsio Communications                 | 1         | 0.04%   |
| ASUSTek Computer                       | 1         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 820       | 35.56%  |
| Samsung Galaxy series, misc. (tethering mode)                          | 129       | 5.59%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 114       | 4.94%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 86        | 3.73%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 82        | 3.56%   |
| Realtek RTL8125 2.5GbE Controller                                      | 58        | 2.52%   |
| Intel Ethernet Connection I217-LM                                      | 39        | 1.69%   |
| Intel I211 Gigabit Network Connection                                  | 38        | 1.65%   |
| Intel Ethernet Connection (4) I219-LM                                  | 36        | 1.56%   |
| Intel Ethernet Controller I225-V                                       | 24        | 1.04%   |
| Intel Ethernet Connection (2) I219-V                                   | 24        | 1.04%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 23        | 1%      |
| Qualcomm Atheros AR8131 Gigabit Ethernet                               | 22        | 0.95%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 21        | 0.91%   |
| Intel Ethernet Connection I219-LM                                      | 19        | 0.82%   |
| Intel 82567LM Gigabit Network Connection                               | 19        | 0.82%   |
| Intel Ethernet Connection (4) I219-V                                   | 18        | 0.78%   |
| Intel Ethernet Connection I218-LM                                      | 17        | 0.74%   |
| Intel Ethernet Connection (7) I219-LM                                  | 16        | 0.69%   |
| ASIX AX88179 Gigabit Ethernet                                          | 16        | 0.69%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 15        | 0.65%   |
| Intel Ethernet Connection (6) I219-V                                   | 15        | 0.65%   |
| Intel Ethernet Connection (7) I219-V                                   | 14        | 0.61%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 13        | 0.56%   |
| Lenovo ThinkPad TBT 3 Dock                                             | 13        | 0.56%   |
| Intel Ethernet Connection (3) I218-LM                                  | 13        | 0.56%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 13        | 0.56%   |
| Intel Ethernet Connection (2) I219-LM                                  | 11        | 0.48%   |
| Intel 82579V Gigabit Network Connection                                | 11        | 0.48%   |
| Intel 82566DM-2 Gigabit Network Connection                             | 11        | 0.48%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 11        | 0.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 10        | 0.43%   |
| Intel Ethernet Connection (6) I219-LM                                  | 10        | 0.43%   |
| Intel Ethernet Connection (2) I218-V                                   | 10        | 0.43%   |
| Intel Ethernet Connection (10) I219-LM                                 | 10        | 0.43%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 9         | 0.39%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller              | 9         | 0.39%   |
| Intel I210 Gigabit Network Connection                                  | 9         | 0.39%   |
| Intel Ethernet Connection I217-V                                       | 9         | 0.39%   |
| Intel Ethernet Connection (11) I219-LM                                 | 9         | 0.39%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 2089      | 53.06%  |
| WiFi     | 1815      | 46.1%   |
| Modem    | 28        | 0.71%   |
| Unknown  | 5         | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 1307      | 51.91%  |
| Ethernet | 1211      | 48.09%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 1246      | 51.28%  |
| 1     | 1072      | 44.12%  |
| 0     | 56        | 2.3%    |
| 3     | 38        | 1.56%   |
| 4     | 8         | 0.33%   |
| 8     | 4         | 0.16%   |
| 5     | 3         | 0.12%   |
| 10    | 1         | 0.04%   |
| 9     | 1         | 0.04%   |
| 6     | 1         | 0.04%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 2126      | 86.42%  |
| Yes  | 334       | 13.58%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 697       | 47.77%  |
| Realtek Semiconductor           | 148       | 10.14%  |
| IMC Networks                    | 90        | 6.17%   |
| Qualcomm Atheros Communications | 86        | 5.89%   |
| Broadcom                        | 73        | 5%      |
| Foxconn / Hon Hai               | 72        | 4.93%   |
| Cambridge Silicon Radio         | 71        | 4.87%   |
| Lite-On Technology              | 49        | 3.36%   |
| ASUSTek Computer                | 44        | 3.02%   |
| Hewlett-Packard                 | 31        | 2.12%   |
| Dell                            | 20        | 1.37%   |
| Ralink                          | 12        | 0.82%   |
| MediaTek                        | 12        | 0.82%   |
| Apple                           | 9         | 0.62%   |
| Alps Electric                   | 6         | 0.41%   |
| TP-Link                         | 5         | 0.34%   |
| Integrated System Solution      | 5         | 0.34%   |
| Toshiba                         | 4         | 0.27%   |
| Realtek                         | 4         | 0.27%   |
| USI                             | 3         | 0.21%   |
| Foxconn International           | 3         | 0.21%   |
| Ralink Technology               | 2         | 0.14%   |
| Mobile Action Technology        | 2         | 0.14%   |
| Micro Star International        | 2         | 0.14%   |
| Marvell Semiconductor           | 2         | 0.14%   |
| Creative Technology             | 2         | 0.14%   |
| Fujitsu Siemens Computers       | 1         | 0.07%   |
| Belkin Components               | 1         | 0.07%   |
| Askey Computer                  | 1         | 0.07%   |
| Actions                         | 1         | 0.07%   |
| Unknown                         | 1         | 0.07%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 148       | 10.14%  |
| Intel AX201 Bluetooth                               | 123       | 8.43%   |
| Intel Bluetooth Device                              | 118       | 8.09%   |
| Intel AX200 Bluetooth                               | 115       | 7.88%   |
| Realtek Bluetooth Radio                             | 111       | 7.61%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 91        | 6.24%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 71        | 4.87%   |
| Qualcomm Atheros  Bluetooth Device                  | 35        | 2.4%    |
| Intel AX211 Bluetooth                               | 34        | 2.33%   |
| IMC Networks Bluetooth Radio                        | 24        | 1.64%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 24        | 1.64%   |
| IMC Networks Wireless_Device                        | 21        | 1.44%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 19        | 1.3%    |
| IMC Networks Bluetooth Device                       | 19        | 1.3%    |
| Intel Wireless-AC 3168 Bluetooth                    | 18        | 1.23%   |
| Realtek 802.11ac WLAN Adapter                       | 17        | 1.17%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 16        | 1.1%    |
| Qualcomm Atheros AR3011 Bluetooth                   | 16        | 1.1%    |
| Foxconn / Hon Hai Wireless_Device                   | 16        | 1.1%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 16        | 1.1%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 15        | 1.03%   |
| Intel AX210 Bluetooth                               | 15        | 1.03%   |
| HP Broadcom 2070 Bluetooth Combo                    | 15        | 1.03%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 15        | 1.03%   |
| Foxconn / Hon Hai Bluetooth Device                  | 13        | 0.89%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 13        | 0.89%   |
| Ralink RT3290 Bluetooth                             | 12        | 0.82%   |
| Broadcom BCM2045 Bluetooth                          | 12        | 0.82%   |
| Lite-On Atheros AR3012 Bluetooth                    | 11        | 0.75%   |
| Broadcom BCM2045B (BDC-2.1)                         | 11        | 0.75%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 10        | 0.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 10        | 0.69%   |
| Dell DW375 Bluetooth Module                         | 10        | 0.69%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 10        | 0.69%   |
| ASUS ASUS USB-BT500                                 | 10        | 0.69%   |
| Broadcom HP Portable SoftSailing                    | 9         | 0.62%   |
| MediaTek Wireless_Device                            | 8         | 0.55%   |
| ASUS BT-183 Bluetooth 2.0+EDR adapter               | 8         | 0.55%   |
| Lite-On Bluetooth Device                            | 7         | 0.48%   |
| Realtek  Bluetooth 4.2 Adapter                      | 6         | 0.41%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 1684      | 51.96%  |
| AMD                                  | 729       | 22.49%  |
| Nvidia                               | 481       | 14.84%  |
| C-Media Electronics                  | 56        | 1.73%   |
| Lenovo                               | 37        | 1.14%   |
| Realtek Semiconductor                | 28        | 0.86%   |
| GN Netcom                            | 20        | 0.62%   |
| Logitech                             | 18        | 0.56%   |
| Creative Labs                        | 17        | 0.52%   |
| JMTek                                | 14        | 0.43%   |
| Creative Technology                  | 14        | 0.43%   |
| VIA Technologies                     | 13        | 0.4%    |
| Kingston Technology                  | 11        | 0.34%   |
| Hewlett-Packard                      | 11        | 0.34%   |
| Razer USA                            | 6         | 0.19%   |
| Plantronics                          | 6         | 0.19%   |
| Trust                                | 5         | 0.15%   |
| GYROCOM C&C                          | 5         | 0.15%   |
| Focusrite-Novation                   | 5         | 0.15%   |
| DSEA A/S                             | 5         | 0.15%   |
| Dell                                 | 5         | 0.15%   |
| Texas Instruments                    | 4         | 0.12%   |
| Micro Star International             | 4         | 0.12%   |
| BEHRINGER International              | 4         | 0.12%   |
| ASUSTek Computer                     | 4         | 0.12%   |
| SteelSeries ApS                      | 3         | 0.09%   |
| Silicon Integrated Systems [SiS]     | 3         | 0.09%   |
| M-Audio                              | 3         | 0.09%   |
| Yamaha                               | 2         | 0.06%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.06%   |
| Samson Technologies                  | 2         | 0.06%   |
| RODE Microphones                     | 2         | 0.06%   |
| Harman                               | 2         | 0.06%   |
| DigiTech                             | 2         | 0.06%   |
| Conexant Systems                     | 2         | 0.06%   |
| Cambridge Silicon Radio              | 2         | 0.06%   |
| ASRock                               | 2         | 0.06%   |
| Yealink Network Technology           | 1         | 0.03%   |
| Toshiba                              | 1         | 0.03%   |
| Tenx Technology                      | 1         | 0.03%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 269       | 6.95%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 256       | 6.61%   |
| Intel Sunrise Point-LP HD Audio                                            | 168       | 4.34%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 156       | 4.03%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 126       | 3.25%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 98        | 2.53%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 88        | 2.27%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 87        | 2.25%   |
| AMD Starship/Matisse HD Audio Controller                                   | 86        | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 81        | 2.09%   |
| Intel Cannon Lake PCH cAVS                                                 | 80        | 2.07%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 76        | 1.96%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 64        | 1.65%   |
| AMD FCH Azalia Controller                                                  | 64        | 1.65%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 54        | 1.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 52        | 1.34%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 52        | 1.34%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 51        | 1.32%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 50        | 1.29%   |
| Intel Haswell-ULT HD Audio Controller                                      | 49        | 1.27%   |
| Intel 8 Series HD Audio Controller                                         | 49        | 1.27%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 49        | 1.27%   |
| Nvidia GP107GL High Definition Audio Controller                            | 45        | 1.16%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 45        | 1.16%   |
| Nvidia GP106 High Definition Audio Controller                              | 42        | 1.08%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 42        | 1.08%   |
| Intel Comet Lake PCH-LP cAVS                                               | 41        | 1.06%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 40        | 1.03%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 40        | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 39        | 1.01%   |
| Nvidia GF108 High Definition Audio Controller                              | 38        | 0.98%   |
| Intel Broadwell-U Audio Controller                                         | 37        | 0.96%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 36        | 0.93%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller | 33        | 0.85%   |
| Intel 200 Series PCH HD Audio                                              | 33        | 0.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 29        | 0.75%   |
| Nvidia GA106 High Definition Audio Controller                              | 29        | 0.75%   |
| Intel Comet Lake PCH cAVS                                                  | 29        | 0.75%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 29        | 0.75%   |
| AMD Kabini HDMI/DP Audio                                                   | 28        | 0.72%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 318       | 19.86%  |
| Kingston                     | 292       | 18.24%  |
| SK hynix                     | 255       | 15.93%  |
| Micron Technology            | 168       | 10.49%  |
| Elpida                       | 147       | 9.18%   |
| Unknown                      | 139       | 8.68%   |
| Crucial                      | 65        | 4.06%   |
| Corsair                      | 43        | 2.69%   |
| Ramaxel Technology           | 32        | 2%      |
| Patriot                      | 30        | 1.87%   |
| A-DATA Technology            | 27        | 1.69%   |
| Unknown (ABCD)               | 20        | 1.25%   |
| G.Skill                      | 14        | 0.87%   |
| Nanya Technology             | 12        | 0.75%   |
| Transcend                    | 6         | 0.37%   |
| Unknown                      | 4         | 0.25%   |
| Apacer                       | 3         | 0.19%   |
| GOODRAM                      | 2         | 0.12%   |
| fef5                         | 2         | 0.12%   |
| Unknown (AB)                 | 1         | 0.06%   |
| Toshiba                      | 1         | 0.06%   |
| Team                         | 1         | 0.06%   |
| TakeMS                       | 1         | 0.06%   |
| Silicon Power                | 1         | 0.06%   |
| SHARETRONIC                  | 1         | 0.06%   |
| RZX                          | 1         | 0.06%   |
| ProMos/Mosel Vitelic         | 1         | 0.06%   |
| PDPSystems                   | 1         | 0.06%   |
| Patriot Memory (PDP Systems) | 1         | 0.06%   |
| Patriot Memory               | 1         | 0.06%   |
| OnBoard                      | 1         | 0.06%   |
| Nayna                        | 1         | 0.06%   |
| Kingmax                      | 1         | 0.06%   |
| Kimtigo                      | 1         | 0.06%   |
| H                            | 1         | 0.06%   |
| GSkill                       | 1         | 0.06%   |
| Golden Empire                | 1         | 0.06%   |
| Gigabyte Technology          | 1         | 0.06%   |
| ASint Technology             | 1         | 0.06%   |
| AMD                          | 1         | 0.06%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Elpida RAM Module 2GB SODIMM DDR3 1333MT/s                       | 126       | 7.37%   |
| Samsung RAM M471A1G44AB0-CWE 8192MB SODIMM DDR4 3200MT/s         | 20        | 1.17%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 17        | 0.99%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 15        | 0.88%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 12        | 0.7%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 12        | 0.7%    |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3733MT/s             | 11        | 0.64%   |
| Samsung RAM M471A2G44AM0-CWE 16GB SODIMM DDR4 3200MT/s           | 10        | 0.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.59%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 10        | 0.59%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 9         | 0.53%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 9         | 0.53%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 9         | 0.53%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 9         | 0.53%   |
| SK hynix RAM Module 8GB SODIMM DDR4 3200MT/s                     | 8         | 0.47%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 8         | 0.47%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 8         | 0.47%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 8         | 0.47%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 8         | 0.47%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 8         | 0.47%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 8         | 0.47%   |
| SK hynix RAM HMA82GS6JJR8N-VK 16GB SODIMM DDR4 2667MT/s          | 7         | 0.41%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 7         | 0.41%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s            | 7         | 0.41%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 6         | 0.35%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.35%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.35%   |
| Kingston RAM KHX3200C16D4/16GX 16GB DIMM DDR4 3600MT/s           | 6         | 0.35%   |
| Kingston RAM KHX1600C9S3L/8G 8192MB SODIMM DDR3 1600MT/s         | 6         | 0.35%   |
| Kingston RAM KF3200C16D4/8GX 8192MB DIMM DDR4 3600MT/s           | 6         | 0.35%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 5         | 0.29%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 5         | 0.29%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 5         | 0.29%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 5         | 0.29%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.29%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 5         | 0.29%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 5         | 0.29%   |
| Samsung RAM Module 16GB SODIMM DDR4 2667MT/s                     | 5         | 0.29%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 5         | 0.29%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 5         | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 625       | 44.71%  |
| DDR3    | 485       | 34.69%  |
| LPDDR4  | 70        | 5.01%   |
| DDR2    | 63        | 4.51%   |
| Unknown | 40        | 2.86%   |
| SDRAM   | 31        | 2.22%   |
| DDR5    | 28        | 2%      |
| LPDDR3  | 25        | 1.79%   |
| LPDDR5  | 20        | 1.43%   |
| DDR     | 8         | 0.57%   |
| DRAM    | 3         | 0.21%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 877       | 62.73%  |
| DIMM         | 407       | 29.11%  |
| Row Of Chips | 96        | 6.87%   |
| Chip         | 12        | 0.86%   |
| Unknown      | 4         | 0.29%   |
| RIMM         | 2         | 0.14%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 519       | 34.35%  |
| 4096  | 322       | 21.31%  |
| 2048  | 281       | 18.6%   |
| 16384 | 259       | 17.14%  |
| 32768 | 76        | 5.03%   |
| 1024  | 46        | 3.04%   |
| 512   | 4         | 0.26%   |
| 256   | 2         | 0.13%   |
| 6144  | 1         | 0.07%   |
| 3072  | 1         | 0.07%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 255       | 16.83%  |
| 1600    | 229       | 15.12%  |
| 1333    | 207       | 13.66%  |
| 2667    | 169       | 11.16%  |
| 2400    | 109       | 7.19%   |
| 2133    | 74        | 4.88%   |
| 1334    | 40        | 2.64%   |
| 800     | 39        | 2.57%   |
| 3600    | 38        | 2.51%   |
| 667     | 29        | 1.91%   |
| 4267    | 25        | 1.65%   |
| Unknown | 24        | 1.58%   |
| 1867    | 20        | 1.32%   |
| 6400    | 19        | 1.25%   |
| 3733    | 18        | 1.19%   |
| 1067    | 17        | 1.12%   |
| 4800    | 13        | 0.86%   |
| 3266    | 13        | 0.86%   |
| 2666    | 11        | 0.73%   |
| 3400    | 10        | 0.66%   |
| 2048    | 10        | 0.66%   |
| 1866    | 10        | 0.66%   |
| 5600    | 9         | 0.59%   |
| 4266    | 9         | 0.59%   |
| 3000    | 9         | 0.59%   |
| 3800    | 8         | 0.53%   |
| 3466    | 8         | 0.53%   |
| 3933    | 7         | 0.46%   |
| 1800    | 7         | 0.46%   |
| 1066    | 7         | 0.46%   |
| 4199    | 6         | 0.4%    |
| 533     | 6         | 0.4%    |
| 4000    | 5         | 0.33%   |
| 2933    | 5         | 0.33%   |
| 975     | 5         | 0.33%   |
| 400     | 5         | 0.33%   |
| 8400    | 4         | 0.26%   |
| 2800    | 4         | 0.26%   |
| 6000    | 3         | 0.2%    |
| 3334    | 3         | 0.2%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Canon               | 12        | 26.09%  |
| Hewlett-Packard     | 10        | 21.74%  |
| Brother Industries  | 7         | 15.22%  |
| Samsung Electronics | 6         | 13.04%  |
| QinHeng Electronics | 4         | 8.7%    |
| Xerox               | 2         | 4.35%   |
| Seiko Epson         | 1         | 2.17%   |
| Prolific Technology | 1         | 2.17%   |
| Pantum              | 1         | 2.17%   |
| Minolta             | 1         | 2.17%   |
| ICS Advent          | 1         | 2.17%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                   | Computers | Percent |
|-----------------------------------------|-----------|---------|
| QinHeng CH340S                          | 4         | 8.51%   |
| HP DeskJet 2600 series                  | 3         | 6.38%   |
| Samsung M2070 Series                    | 2         | 4.26%   |
| HP LaserJet P2014                       | 2         | 4.26%   |
| Xerox Phaser 3260                       | 1         | 2.13%   |
| Xerox B215                              | 1         | 2.13%   |
| Seiko Epson L365 Series                 | 1         | 2.13%   |
| Samsung Xerox Phaser 3117 Laser Printer | 1         | 2.13%   |
| Samsung M267x 287x Series               | 1         | 2.13%   |
| Samsung M2020 Series                    | 1         | 2.13%   |
| Samsung C460 Series                     | 1         | 2.13%   |
| Prolific PL2305 Parallel Port           | 1         | 2.13%   |
| Pantum P2000                            | 1         | 2.13%   |
| Minolta PagePro 1300W                   | 1         | 2.13%   |
| ICS Advent Parallel Adapter             | 1         | 2.13%   |
| HP Officejet 4500 G510g-m               | 1         | 2.13%   |
| HP Neverstop Laser 100x                 | 1         | 2.13%   |
| HP LaserJet Professional P 1102w        | 1         | 2.13%   |
| HP LaserJet 1018                        | 1         | 2.13%   |
| HP Deskjet 3050 J610 series             | 1         | 2.13%   |
| Canon TS6300 series                     | 1         | 2.13%   |
| Canon PIXMA MX920 Series                | 1         | 2.13%   |
| Canon PIXMA MX720 Series                | 1         | 2.13%   |
| Canon PIXMA MP280                       | 1         | 2.13%   |
| Canon PIXMA MG5600 Series               | 1         | 2.13%   |
| Canon PIXMA MG3500 Series               | 1         | 2.13%   |
| Canon PIXMA MG2500 Series               | 1         | 2.13%   |
| Canon MF645C                            | 1         | 2.13%   |
| Canon MF4100 series                     | 1         | 2.13%   |
| Canon LiDE 300                          | 1         | 2.13%   |
| Canon LBP3010/LBP3018/LBP3050           | 1         | 2.13%   |
| Canon iP7200 series                     | 1         | 2.13%   |
| Canon G2020 series                      | 1         | 2.13%   |
| Brother MFC-J3930DW                     | 1         | 2.13%   |
| Brother HL-3040CN series                | 1         | 2.13%   |
| Brother HL-2030 Laser Printer           | 1         | 2.13%   |
| Brother HL-1430 Laser Printer           | 1         | 2.13%   |
| Brother DCP-L2510D series               | 1         | 2.13%   |
| Brother DCP-J105                        | 1         | 2.13%   |
| Brother DCP-1610W                       | 1         | 2.13%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 8         | 72.73%  |
| Seiko Epson     | 1         | 9.09%   |
| Mustek Systems  | 1         | 9.09%   |
| Hewlett-Packard | 1         | 9.09%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Canon CanoScan LIDE 25                | 2         | 18.18%  |
| Canon CanoScan LiDE 210               | 2         | 18.18%  |
| Seiko Epson GT-F700 [Perfection V350] | 1         | 9.09%   |
| Mustek Systems BearPaw 1200 CU Plus   | 1         | 9.09%   |
| HP ScanJet 2200c                      | 1         | 9.09%   |
| Canon CanoScan LiDE 90                | 1         | 9.09%   |
| Canon CanoScan LiDE 200               | 1         | 9.09%   |
| Canon CanoScan LiDE 120               | 1         | 9.09%   |
| Canon CanoScan LiDE 100               | 1         | 9.09%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 343       | 24.61%  |
| Realtek Semiconductor                  | 127       | 9.11%   |
| IMC Networks                           | 122       | 8.75%   |
| Microdia                               | 112       | 8.03%   |
| Bison Electronics                      | 85        | 6.1%    |
| Sunplus Innovation Technology          | 81        | 5.81%   |
| Quanta                                 | 60        | 4.3%    |
| Cheng Uei Precision Industry (Foxlink) | 56        | 4.02%   |
| Lite-On Technology                     | 50        | 3.59%   |
| Acer                                   | 42        | 3.01%   |
| Syntek                                 | 38        | 2.73%   |
| Suyin                                  | 36        | 2.58%   |
| Logitech                               | 35        | 2.51%   |
| Luxvisions Innotech Limited            | 21        | 1.51%   |
| Apple                                  | 21        | 1.51%   |
| KYE Systems (Mouse Systems)            | 15        | 1.08%   |
| Samsung Electronics                    | 13        | 0.93%   |
| Ricoh                                  | 13        | 0.93%   |
| Lenovo                                 | 13        | 0.93%   |
| Alcor Micro                            | 13        | 0.93%   |
| Microsoft                              | 11        | 0.79%   |
| Z-Star Microelectronics                | 9         | 0.65%   |
| Sonix Technology                       | 8         | 0.57%   |
| Creative Technology                    | 8         | 0.57%   |
| Primax Electronics                     | 6         | 0.43%   |
| icSpring                               | 5         | 0.36%   |
| GEMBIRD                                | 5         | 0.36%   |
| Hopewin Electronic Material            | 4         | 0.29%   |
| Silicon Motion                         | 3         | 0.22%   |
| MacroSilicon                           | 3         | 0.22%   |
| Generalplus Technology                 | 3         | 0.22%   |
| Shinetech                              | 2         | 0.14%   |
| Pixart Imaging                         | 2         | 0.14%   |
| Intel                                  | 2         | 0.14%   |
| Hewlett-Packard                        | 2         | 0.14%   |
| Genesys Logic                          | 2         | 0.14%   |
| YGTek                                  | 1         | 0.07%   |
| WaveRider Communications               | 1         | 0.07%   |
| vivo                                   | 1         | 0.07%   |
| Unknown                                | 1         | 0.07%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 87        | 6.17%   |
| IMC Networks Integrated Camera                      | 53        | 3.76%   |
| Microdia Integrated_Webcam_HD                       | 45        | 3.19%   |
| Realtek Integrated_Webcam_HD                        | 41        | 2.91%   |
| Chicony HD WebCam                                   | 34        | 2.41%   |
| Chicony HP HD Camera                                | 33        | 2.34%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 30        | 2.13%   |
| Bison Integrated Camera                             | 28        | 1.99%   |
| Lite-On HP HD Camera                                | 23        | 1.63%   |
| Syntek Integrated Camera                            | 21        | 1.49%   |
| Realtek USB Camera                                  | 19        | 1.35%   |
| Sunplus Integrated_Webcam_HD                        | 18        | 1.28%   |
| Chicony Integrated Camera (1280x720@30)             | 17        | 1.21%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 16        | 1.14%   |
| Acer Integrated Camera                              | 14        | 0.99%   |
| Samsung Galaxy series, misc. (MTP mode)             | 13        | 0.92%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 13        | 0.92%   |
| Bison SunplusIT Integrated Camera                   | 13        | 0.92%   |
| Suyin Acer/HP Integrated Webcam [CN0314]            | 12        | 0.85%   |
| Quanta HP HD Camera                                 | 12        | 0.85%   |
| Microdia Integrated Webcam                          | 12        | 0.85%   |
| Lite-On Integrated Camera                           | 12        | 0.85%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 12        | 0.85%   |
| Bison Lenovo EasyCamera                             | 12        | 0.85%   |
| Quanta HD User Facing                               | 11        | 0.78%   |
| Sunplus HD WebCam                                   | 10        | 0.71%   |
| Chicony USB2.0 VGA UVC WebCam                       | 10        | 0.71%   |
| Chicony Lenovo EasyCamera                           | 10        | 0.71%   |
| Syntek Lenovo EasyCamera                            | 9         | 0.64%   |
| Realtek Integrated Webcam HD                        | 9         | 0.64%   |
| Quanta HP Wide Vision HD Camera                     | 9         | 0.64%   |
| Chicony HP HD Webcam                                | 9         | 0.64%   |
| Bison EasyCamera                                    | 9         | 0.64%   |
| Sunplus Asus Webcam                                 | 8         | 0.57%   |
| Realtek Lenovo EasyCamera                           | 8         | 0.57%   |
| Microdia Sonix USB 2.0 Camera                       | 8         | 0.57%   |
| Logitech Webcam C270                                | 8         | 0.57%   |
| Lenovo Integrated Webcam                            | 8         | 0.57%   |
| Chicony FJ Camera                                   | 8         | 0.57%   |
| Acer Lenovo EasyCamera                              | 8         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 129       | 36.44%  |
| Validity Sensors                   | 112       | 31.64%  |
| Shenzhen Goodix Technology         | 39        | 11.02%  |
| AuthenTec                          | 29        | 8.19%   |
| Upek                               | 16        | 4.52%   |
| Elan Microelectronics              | 16        | 4.52%   |
| LighTuning Technology              | 7         | 1.98%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.56%   |
| Dell                               | 2         | 0.56%   |
| STMicroelectronics                 | 1         | 0.28%   |
| Microsoft                          | 1         | 0.28%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 31        | 8.76%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 30        | 8.47%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 21        | 5.93%   |
| Shenzhen Goodix  FingerPrint Device                                        | 19        | 5.37%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 18        | 5.08%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 18        | 5.08%   |
| Synaptics Fingerprint reader [HP G6]                                       | 17        | 4.8%    |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 15        | 4.24%   |
| Shenzhen Goodix Fingerprint Reader                                         | 13        | 3.67%   |
| Validity Sensors VFS491                                                    | 12        | 3.39%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 12        | 3.39%   |
| AuthenTec AES2810                                                          | 12        | 3.39%   |
| Validity Sensors Synaptics WBDI                                            | 11        | 3.11%   |
| Elan ELAN:Fingerprint                                                      | 11        | 3.11%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 2.82%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 9         | 2.54%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 7         | 1.98%   |
| Shenzhen Goodix FingerPrint                                                | 7         | 1.98%   |
| AuthenTec AES1600                                                          | 7         | 1.98%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 6         | 1.69%   |
| Synaptics UWP WBDI                                                         | 6         | 1.69%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 6         | 1.69%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 1.41%   |
| Synaptics WBDI                                                             | 5         | 1.41%   |
| Synaptics  WBDI                                                            | 5         | 1.41%   |
| Elan ELAN:ARM-M4                                                           | 5         | 1.41%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 3         | 0.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 3         | 0.85%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 3         | 0.85%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 0.85%   |
| Validity Sensors Fingerprint scanner                                       | 3         | 0.85%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 3         | 0.85%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.56%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 2         | 0.56%   |
| Synaptics UWP WBDI Device                                                  | 2         | 0.56%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.56%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 1         | 0.28%   |
| Upek TCS5B Fingerprint sensor                                              | 1         | 0.28%   |
| Synaptics WBDI Fingerprint Reader USB 102                                  | 1         | 0.28%   |
| Synaptics WBDI Device                                                      | 1         | 0.28%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 83        | 51.23%  |
| Alcor Micro               | 48        | 29.63%  |
| O2 Micro                  | 11        | 6.79%   |
| Lenovo                    | 6         | 3.7%    |
| Upek                      | 4         | 2.47%   |
| SCM Microsystems          | 2         | 1.23%   |
| Realtek Semiconductor     | 2         | 1.23%   |
| Aladdin Knowledge Systems | 2         | 1.23%   |
| Purism, SPC               | 1         | 0.62%   |
| OmniKey                   | 1         | 0.62%   |
| Gemalto (was Gemplus)     | 1         | 0.62%   |
| Fujitsu Siemens Computers | 1         | 0.62%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 48        | 29.63%  |
| Broadcom 58200                                                               | 28        | 17.28%  |
| Broadcom BCM5880 Secure Applications Processor                               | 21        | 12.96%  |
| Broadcom 5880                                                                | 20        | 12.35%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 14        | 8.64%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 9         | 5.56%   |
| Lenovo Integrated Smart Card Reader                                          | 6         | 3.7%    |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 2.47%   |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 1.23%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 2         | 1.23%   |
| O2 Micro Oz776 SmartCard Reader                                              | 2         | 1.23%   |
| Aladdin Knowledge Systems Token JC                                           | 2         | 1.23%   |
| Purism, SPC Librem Key                                                       | 1         | 0.62%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.62%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 0.62%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.62%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1648      | 66.94%  |
| 1     | 620       | 25.18%  |
| 2     | 157       | 6.38%   |
| 3     | 27        | 1.1%    |
| 4     | 6         | 0.24%   |
| 5     | 3         | 0.12%   |
| 6     | 1         | 0.04%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 346       | 34.02%  |
| Graphics card            | 215       | 21.14%  |
| Chipcard                 | 138       | 13.57%  |
| Net/wireless             | 75        | 7.37%   |
| Multimedia controller    | 55        | 5.41%   |
| Camera                   | 29        | 2.85%   |
| Communication controller | 28        | 2.75%   |
| Bluetooth                | 27        | 2.65%   |
| Storage                  | 25        | 2.46%   |
| Unassigned class         | 17        | 1.67%   |
| Card reader              | 16        | 1.57%   |
| Sound                    | 11        | 1.08%   |
| Net/ethernet             | 10        | 0.98%   |
| Flash memory             | 7         | 0.69%   |
| Modem                    | 6         | 0.59%   |
| Network                  | 4         | 0.39%   |
| Storage/raid             | 2         | 0.2%    |
| Storage/ata              | 2         | 0.2%    |
| Dvb card                 | 2         | 0.2%    |
| Tv card                  | 1         | 0.1%    |
| Storage/ide              | 1         | 0.1%    |

