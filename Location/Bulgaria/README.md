Linux in Bulgaria - Tested Hardware & Statistics
------------------------------------------------

A project to collect tested hardware configurations for Linux in Bulgaria.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Bulgaria/Desktop/README.md) and [notebooks](/Location/Bulgaria/Notebook/README.md).

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

Total: 1174

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | X540LJ                      | Notebook    | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [ff7adfb82a](https://linux-hardware.org/?probe=ff7adfb82a) | May 05, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | Notebook    | [5cdef8caad](https://linux-hardware.org/?probe=5cdef8caad) | May 04, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [244ed30771](https://linux-hardware.org/?probe=244ed30771) | May 04, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [62f9f79f7c](https://linux-hardware.org/?probe=62f9f79f7c) | May 03, 2022 |
| MSI           | MPG B550 GAMING PLUS        | Desktop     | [afce1937fe](https://linux-hardware.org/?probe=afce1937fe) | May 03, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [c40273d0bc](https://linux-hardware.org/?probe=c40273d0bc) | Apr 29, 2022 |
| Toshiba       | Satellite C650              | Notebook    | [58539bbf0a](https://linux-hardware.org/?probe=58539bbf0a) | Apr 29, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [ab21675303](https://linux-hardware.org/?probe=ab21675303) | Apr 29, 2022 |
| Razer         | Blade 15 Studio Edition ... | Notebook    | [563510a4b7](https://linux-hardware.org/?probe=563510a4b7) | Apr 28, 2022 |
| Lenovo        | B590 20206                  | Notebook    | [80befa3088](https://linux-hardware.org/?probe=80befa3088) | Apr 23, 2022 |
| MSI           | PRO B660-A DDR4             | Desktop     | [ec79dfd8b1](https://linux-hardware.org/?probe=ec79dfd8b1) | Apr 23, 2022 |
| ASUSTek       | K55VD                       | Notebook    | [8c2253380a](https://linux-hardware.org/?probe=8c2253380a) | Apr 23, 2022 |
| Lenovo        | ThinkPad T490 20N20009RI    | Notebook    | [3f5a56d826](https://linux-hardware.org/?probe=3f5a56d826) | Apr 22, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [db53151112](https://linux-hardware.org/?probe=db53151112) | Apr 19, 2022 |
| Lenovo        | ThinkPad E14 20RA002UBM     | Notebook    | [a888d6756a](https://linux-hardware.org/?probe=a888d6756a) | Apr 19, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [86aeb14193](https://linux-hardware.org/?probe=86aeb14193) | Apr 18, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [59bc74a946](https://linux-hardware.org/?probe=59bc74a946) | Apr 18, 2022 |
| Dell          | Precision M6800             | Notebook    | [46a37b9e8e](https://linux-hardware.org/?probe=46a37b9e8e) | Apr 16, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [0ce9091731](https://linux-hardware.org/?probe=0ce9091731) | Apr 16, 2022 |
| ASRock        | H110M-DGS                   | Desktop     | [33d09ef3fd](https://linux-hardware.org/?probe=33d09ef3fd) | Apr 15, 2022 |
| Gigabyte      | X570S AORUS PRO AX          | Desktop     | [157197f213](https://linux-hardware.org/?probe=157197f213) | Apr 13, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [180b0efcf3](https://linux-hardware.org/?probe=180b0efcf3) | Apr 13, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [70644a292c](https://linux-hardware.org/?probe=70644a292c) | Apr 12, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [d08d83ac3a](https://linux-hardware.org/?probe=d08d83ac3a) | Apr 12, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [a28b76d4ba](https://linux-hardware.org/?probe=a28b76d4ba) | Apr 04, 2022 |
| Acer          | Aspire A315-35              | Notebook    | [fc67b2d51e](https://linux-hardware.org/?probe=fc67b2d51e) | Apr 03, 2022 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [8506a077af](https://linux-hardware.org/?probe=8506a077af) | Apr 02, 2022 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [071753c493](https://linux-hardware.org/?probe=071753c493) | Mar 31, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [097d78d0b6](https://linux-hardware.org/?probe=097d78d0b6) | Mar 31, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [5215972642](https://linux-hardware.org/?probe=5215972642) | Mar 31, 2022 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [4153c10d0b](https://linux-hardware.org/?probe=4153c10d0b) | Mar 31, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [e6075f51f5](https://linux-hardware.org/?probe=e6075f51f5) | Mar 30, 2022 |
| HP            | ProBook 455 G7              | Notebook    | [60fa1992d1](https://linux-hardware.org/?probe=60fa1992d1) | Mar 30, 2022 |
| Lenovo        | ThinkPad T61 7661WE7        | Notebook    | [30fce12920](https://linux-hardware.org/?probe=30fce12920) | Mar 27, 2022 |
| Toshiba       | Satellite C855-2G8          | Notebook    | [37b97513a6](https://linux-hardware.org/?probe=37b97513a6) | Mar 26, 2022 |
| Lenovo        | IdeaPad 320S-14IKB 81BN     | Notebook    | [19fbf78cc0](https://linux-hardware.org/?probe=19fbf78cc0) | Mar 23, 2022 |
| HP            | Pavilion g6                 | Notebook    | [141b22c372](https://linux-hardware.org/?probe=141b22c372) | Mar 20, 2022 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [cdbd9842e1](https://linux-hardware.org/?probe=cdbd9842e1) | Mar 20, 2022 |
| Dell          | Precision M4600             | Notebook    | [deec5e6e2b](https://linux-hardware.org/?probe=deec5e6e2b) | Mar 16, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [9bd0fc9e48](https://linux-hardware.org/?probe=9bd0fc9e48) | Mar 14, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [38c8508bc0](https://linux-hardware.org/?probe=38c8508bc0) | Mar 10, 2022 |
| Dell          | Inspiron 7559               | Notebook    | [82005c3638](https://linux-hardware.org/?probe=82005c3638) | Mar 08, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [d772cac60d](https://linux-hardware.org/?probe=d772cac60d) | Mar 07, 2022 |
| Lenovo        | IdeaPad Y580                | Notebook    | [26ea7d1cff](https://linux-hardware.org/?probe=26ea7d1cff) | Mar 06, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [441febf3e4](https://linux-hardware.org/?probe=441febf3e4) | Mar 05, 2022 |
| HP            | Pavilion dv5000 (EZ535UA... | Notebook    | [1ce1458a5f](https://linux-hardware.org/?probe=1ce1458a5f) | Mar 05, 2022 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [5914978461](https://linux-hardware.org/?probe=5914978461) | Mar 04, 2022 |
| HP            | EliteBook 850 G5            | Notebook    | [bf630f003c](https://linux-hardware.org/?probe=bf630f003c) | Mar 04, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | Notebook    | [e604cd4180](https://linux-hardware.org/?probe=e604cd4180) | Mar 03, 2022 |
| HP            | ProBook 450 G2              | Notebook    | [50e3ff9809](https://linux-hardware.org/?probe=50e3ff9809) | Mar 03, 2022 |
| ASRock        | A320M Pro4                  | Desktop     | [43f47c3d8e](https://linux-hardware.org/?probe=43f47c3d8e) | Feb 28, 2022 |
| ASUSTek       | N551VW                      | Notebook    | [b7250e82a1](https://linux-hardware.org/?probe=b7250e82a1) | Feb 27, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [fe75c17f25](https://linux-hardware.org/?probe=fe75c17f25) | Feb 27, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [660240eb93](https://linux-hardware.org/?probe=660240eb93) | Feb 22, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [3a98eace64](https://linux-hardware.org/?probe=3a98eace64) | Feb 21, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [fb6d74d159](https://linux-hardware.org/?probe=fb6d74d159) | Feb 21, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [fde67099dc](https://linux-hardware.org/?probe=fde67099dc) | Feb 20, 2022 |
| ASUSTek       | TUF GAMING B560-PLUS WIF... | Desktop     | [dc3262a408](https://linux-hardware.org/?probe=dc3262a408) | Feb 20, 2022 |
| Dell          | Inspiron 1011               | Notebook    | [092837b70d](https://linux-hardware.org/?probe=092837b70d) | Feb 19, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [d12f767e54](https://linux-hardware.org/?probe=d12f767e54) | Feb 19, 2022 |
| Lenovo        | ThinkCentre M58p 6234A1G    | Desktop     | [1cbf260df6](https://linux-hardware.org/?probe=1cbf260df6) | Feb 18, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [1219fcc9e7](https://linux-hardware.org/?probe=1219fcc9e7) | Feb 18, 2022 |
| ASUSTek       | P5KC                        | Desktop     | [61c7fe5dfd](https://linux-hardware.org/?probe=61c7fe5dfd) | Feb 18, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [2024310fec](https://linux-hardware.org/?probe=2024310fec) | Feb 17, 2022 |
| HP            | 255 G2                      | Notebook    | [f4f4bcc310](https://linux-hardware.org/?probe=f4f4bcc310) | Feb 17, 2022 |
| HP            | 255 G2                      | Notebook    | [2eee7b6928](https://linux-hardware.org/?probe=2eee7b6928) | Feb 17, 2022 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [afe18260fc](https://linux-hardware.org/?probe=afe18260fc) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [c38638517e](https://linux-hardware.org/?probe=c38638517e) | Feb 17, 2022 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [64b2c75dae](https://linux-hardware.org/?probe=64b2c75dae) | Feb 16, 2022 |
| HP            | Pavilion 15                 | Notebook    | [191168c7ae](https://linux-hardware.org/?probe=191168c7ae) | Feb 16, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [88a943ec80](https://linux-hardware.org/?probe=88a943ec80) | Feb 16, 2022 |
| Dell          | Latitude E6330              | Notebook    | [7346afde52](https://linux-hardware.org/?probe=7346afde52) | Feb 14, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [b12c01311a](https://linux-hardware.org/?probe=b12c01311a) | Feb 13, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [1df0e30fbc](https://linux-hardware.org/?probe=1df0e30fbc) | Feb 13, 2022 |
| HP            | Pavilion dm1                | Notebook    | [577f05089d](https://linux-hardware.org/?probe=577f05089d) | Feb 13, 2022 |
| Dell          | Inspiron 5482               | Convertible | [17584ae0e4](https://linux-hardware.org/?probe=17584ae0e4) | Feb 12, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [a032ab36a8](https://linux-hardware.org/?probe=a032ab36a8) | Feb 12, 2022 |
| Lenovo        | ThinkPad X230 2325AJG       | Notebook    | [eccfa3a972](https://linux-hardware.org/?probe=eccfa3a972) | Feb 12, 2022 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [0ec31586a1](https://linux-hardware.org/?probe=0ec31586a1) | Feb 11, 2022 |
| HP            | Pavilion 15                 | Notebook    | [72991a7822](https://linux-hardware.org/?probe=72991a7822) | Feb 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [565e324069](https://linux-hardware.org/?probe=565e324069) | Feb 09, 2022 |
| HP            | EliteBook 8560p             | Notebook    | [f8a96f73d1](https://linux-hardware.org/?probe=f8a96f73d1) | Feb 09, 2022 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [005f4b4afc](https://linux-hardware.org/?probe=005f4b4afc) | Feb 08, 2022 |
| Gigabyte      | B85M-D3V                    | Desktop     | [d00c78fd08](https://linux-hardware.org/?probe=d00c78fd08) | Feb 08, 2022 |
| Toshiba       | Satellite A200              | Notebook    | [e4acc07d44](https://linux-hardware.org/?probe=e4acc07d44) | Feb 06, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [788939c01d](https://linux-hardware.org/?probe=788939c01d) | Feb 02, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [5d451a6858](https://linux-hardware.org/?probe=5d451a6858) | Jan 31, 2022 |
| ASUSTek       | P8H77-V                     | Desktop     | [467ff5e38f](https://linux-hardware.org/?probe=467ff5e38f) | Jan 31, 2022 |
| Acer          | Aspire E1-531               | Notebook    | [4f7256df40](https://linux-hardware.org/?probe=4f7256df40) | Jan 30, 2022 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [ba372feee9](https://linux-hardware.org/?probe=ba372feee9) | Jan 30, 2022 |
| MSI           | GF63 Thin 10SCXR            | Notebook    | [c4a65986af](https://linux-hardware.org/?probe=c4a65986af) | Jan 29, 2022 |
| Dell          | Inspiron N5010              | Notebook    | [2d5857b9ff](https://linux-hardware.org/?probe=2d5857b9ff) | Jan 27, 2022 |
| Acer          | Aspire E5-575G              | Notebook    | [2c42aa1caf](https://linux-hardware.org/?probe=2c42aa1caf) | Jan 24, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [f2de9fb609](https://linux-hardware.org/?probe=f2de9fb609) | Jan 20, 2022 |
| Fujitsu       | LIFEBOOK S760               | Notebook    | [0fdf944115](https://linux-hardware.org/?probe=0fdf944115) | Jan 20, 2022 |
| ASRock        | FM2A58M-DG3+                | Desktop     | [a6f8ac859d](https://linux-hardware.org/?probe=a6f8ac859d) | Jan 20, 2022 |
| Intel         | X99                         | Desktop     | [f4a0c1aaaa](https://linux-hardware.org/?probe=f4a0c1aaaa) | Jan 20, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [821f3261c2](https://linux-hardware.org/?probe=821f3261c2) | Jan 18, 2022 |
| Lenovo        | ThinkPad T460 20FN003LUK    | Notebook    | [71cab3efa8](https://linux-hardware.org/?probe=71cab3efa8) | Jan 18, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [83ddee52ce](https://linux-hardware.org/?probe=83ddee52ce) | Jan 14, 2022 |
| ASRock        | H110M-DGS                   | Desktop     | [d027268e2b](https://linux-hardware.org/?probe=d027268e2b) | Jan 14, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [5cff653045](https://linux-hardware.org/?probe=5cff653045) | Jan 13, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [a9ed1157c0](https://linux-hardware.org/?probe=a9ed1157c0) | Jan 13, 2022 |
| HP            | Notebook                    | Notebook    | [3467478289](https://linux-hardware.org/?probe=3467478289) | Jan 13, 2022 |
| Dell          | Latitude E4300              | Notebook    | [0d0020f062](https://linux-hardware.org/?probe=0d0020f062) | Jan 12, 2022 |
| Lenovo        | G500 20236                  | Notebook    | [2e7bd2b772](https://linux-hardware.org/?probe=2e7bd2b772) | Jan 12, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [0ce3ba06f9](https://linux-hardware.org/?probe=0ce3ba06f9) | Jan 10, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [f23503b603](https://linux-hardware.org/?probe=f23503b603) | Jan 10, 2022 |
| Gigabyte      | G41M-ES2L                   | Desktop     | [a993fafbf7](https://linux-hardware.org/?probe=a993fafbf7) | Jan 08, 2022 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [f891c69576](https://linux-hardware.org/?probe=f891c69576) | Jan 08, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [881a1adf4c](https://linux-hardware.org/?probe=881a1adf4c) | Jan 07, 2022 |
| Dell          | Vostro 15 3510              | Notebook    | [8520c449b6](https://linux-hardware.org/?probe=8520c449b6) | Jan 06, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [ca928a7784](https://linux-hardware.org/?probe=ca928a7784) | Jan 06, 2022 |
| Lenovo        | ThinkPad X250 20CLS03Y00    | Notebook    | [64d6a48fd3](https://linux-hardware.org/?probe=64d6a48fd3) | Jan 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [7add8fadfa](https://linux-hardware.org/?probe=7add8fadfa) | Jan 04, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e8cfb51ca5](https://linux-hardware.org/?probe=e8cfb51ca5) | Jan 04, 2022 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [6ae5ab676d](https://linux-hardware.org/?probe=6ae5ab676d) | Jan 03, 2022 |
| HP            | 3397                        | Desktop     | [3bd3d85718](https://linux-hardware.org/?probe=3bd3d85718) | Jan 03, 2022 |
| Packard Be... | EasyNote TK87               | Notebook    | [a551958cb8](https://linux-hardware.org/?probe=a551958cb8) | Jan 01, 2022 |
| Dell          | Inspiron 7520               | Notebook    | [28e0273758](https://linux-hardware.org/?probe=28e0273758) | Dec 31, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [50045a522a](https://linux-hardware.org/?probe=50045a522a) | Dec 30, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [7c11e2a10b](https://linux-hardware.org/?probe=7c11e2a10b) | Dec 30, 2021 |
| ASUSTek       | P5E                         | Desktop     | [1d3ece3005](https://linux-hardware.org/?probe=1d3ece3005) | Dec 29, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [82d502845a](https://linux-hardware.org/?probe=82d502845a) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [195bb81f89](https://linux-hardware.org/?probe=195bb81f89) | Dec 28, 2021 |
| Acer          | Aspire 3820                 | Notebook    | [149083ba5f](https://linux-hardware.org/?probe=149083ba5f) | Dec 28, 2021 |
| Dell          | Inspiron 5458               | Notebook    | [58bbd792ef](https://linux-hardware.org/?probe=58bbd792ef) | Dec 27, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [c3cbdf9c8e](https://linux-hardware.org/?probe=c3cbdf9c8e) | Dec 26, 2021 |
| Dell          | Venue 11 Pro 7130 vPro      | Notebook    | [788a656eea](https://linux-hardware.org/?probe=788a656eea) | Dec 26, 2021 |
| Toshiba       | Satellite L50-B             | Notebook    | [7ee7295f4e](https://linux-hardware.org/?probe=7ee7295f4e) | Dec 26, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [4ca65158f1](https://linux-hardware.org/?probe=4ca65158f1) | Dec 26, 2021 |
| Gigabyte      | X570 GAMING X               | Desktop     | [19959c7845](https://linux-hardware.org/?probe=19959c7845) | Dec 26, 2021 |
| HP            | Compaq 6730b (NB021EA#AB... | Notebook    | [25fb717971](https://linux-hardware.org/?probe=25fb717971) | Dec 25, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b8ff289917](https://linux-hardware.org/?probe=b8ff289917) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [df0d434539](https://linux-hardware.org/?probe=df0d434539) | Dec 22, 2021 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [9724b1359d](https://linux-hardware.org/?probe=9724b1359d) | Dec 21, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [ae120235f1](https://linux-hardware.org/?probe=ae120235f1) | Dec 21, 2021 |
| Toshiba       | Equium A60                  | Notebook    | [206f662171](https://linux-hardware.org/?probe=206f662171) | Dec 20, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [183c18d8a8](https://linux-hardware.org/?probe=183c18d8a8) | Dec 19, 2021 |
| Dell          | Inspiron N5010              | Notebook    | [f67c56ba50](https://linux-hardware.org/?probe=f67c56ba50) | Dec 18, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [5633e414a2](https://linux-hardware.org/?probe=5633e414a2) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [65ec484cf7](https://linux-hardware.org/?probe=65ec484cf7) | Dec 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [ab70f6516f](https://linux-hardware.org/?probe=ab70f6516f) | Dec 16, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [74cb9f00a2](https://linux-hardware.org/?probe=74cb9f00a2) | Dec 15, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [9f5ee59afb](https://linux-hardware.org/?probe=9f5ee59afb) | Dec 14, 2021 |
| Dell          | 0427JK A00                  | Desktop     | [785650303f](https://linux-hardware.org/?probe=785650303f) | Dec 13, 2021 |
| HP            | ProBook 4540s               | Notebook    | [da7b06db3f](https://linux-hardware.org/?probe=da7b06db3f) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [2f607ba3fb](https://linux-hardware.org/?probe=2f607ba3fb) | Dec 12, 2021 |
| HP            | 255 G8 Notebook PC          | Notebook    | [5ef3ccbbd8](https://linux-hardware.org/?probe=5ef3ccbbd8) | Dec 12, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [9e861e7f7d](https://linux-hardware.org/?probe=9e861e7f7d) | Dec 11, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [615e44dbe8](https://linux-hardware.org/?probe=615e44dbe8) | Dec 11, 2021 |
| Gigabyte      | Z490 AORUS PRO AX           | Desktop     | [03ba9fdf17](https://linux-hardware.org/?probe=03ba9fdf17) | Dec 11, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [6424339164](https://linux-hardware.org/?probe=6424339164) | Dec 10, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [a5c3366e73](https://linux-hardware.org/?probe=a5c3366e73) | Dec 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [c62460798a](https://linux-hardware.org/?probe=c62460798a) | Dec 09, 2021 |
| Dell          | Vostro 1014                 | Notebook    | [d1be779708](https://linux-hardware.org/?probe=d1be779708) | Dec 08, 2021 |
| Dell          | Latitude 5520               | Notebook    | [4609e387e3](https://linux-hardware.org/?probe=4609e387e3) | Dec 07, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [b9ebbe30d3](https://linux-hardware.org/?probe=b9ebbe30d3) | Dec 05, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [5dde6ac6a6](https://linux-hardware.org/?probe=5dde6ac6a6) | Dec 05, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [b38dd7fc41](https://linux-hardware.org/?probe=b38dd7fc41) | Dec 04, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [efc98eab3c](https://linux-hardware.org/?probe=efc98eab3c) | Dec 04, 2021 |
| ASUSTek       | P5KPL-AM SE                 | Desktop     | [7530a42730](https://linux-hardware.org/?probe=7530a42730) | Dec 03, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [8c0fabf18d](https://linux-hardware.org/?probe=8c0fabf18d) | Nov 30, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [693e2b3171](https://linux-hardware.org/?probe=693e2b3171) | Nov 30, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [c5c0c4aca3](https://linux-hardware.org/?probe=c5c0c4aca3) | Nov 29, 2021 |
| HP            | EliteBook 820 G2            | Notebook    | [5774bcc229](https://linux-hardware.org/?probe=5774bcc229) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [ee56bc0d39](https://linux-hardware.org/?probe=ee56bc0d39) | Nov 28, 2021 |
| Lenovo        | ThinkPad T470p 20J7S0CF0... | Notebook    | [d140375a6d](https://linux-hardware.org/?probe=d140375a6d) | Nov 27, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | Notebook    | [06841abc04](https://linux-hardware.org/?probe=06841abc04) | Nov 27, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [f0dbaf192c](https://linux-hardware.org/?probe=f0dbaf192c) | Nov 25, 2021 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [f0c1e81fb5](https://linux-hardware.org/?probe=f0c1e81fb5) | Nov 25, 2021 |
| Lenovo        | Legion Y740-17IRHg 81UJ     | Notebook    | [0e34595bcc](https://linux-hardware.org/?probe=0e34595bcc) | Nov 24, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [e2de67ba78](https://linux-hardware.org/?probe=e2de67ba78) | Nov 23, 2021 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [bd12b5a969](https://linux-hardware.org/?probe=bd12b5a969) | Nov 21, 2021 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [de3fb571bb](https://linux-hardware.org/?probe=de3fb571bb) | Nov 20, 2021 |
| ASUSTek       | M51BC                       | Desktop     | [dfc2c68c8d](https://linux-hardware.org/?probe=dfc2c68c8d) | Nov 19, 2021 |
| Acer          | Predator G3-605             | Desktop     | [5cb8f7dfa7](https://linux-hardware.org/?probe=5cb8f7dfa7) | Nov 15, 2021 |
| Dell          | Latitude E6430              | Notebook    | [16f005fd2b](https://linux-hardware.org/?probe=16f005fd2b) | Nov 13, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [ad46c0b68f](https://linux-hardware.org/?probe=ad46c0b68f) | Nov 11, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [2aa779c174](https://linux-hardware.org/?probe=2aa779c174) | Nov 10, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [28df5fd3c6](https://linux-hardware.org/?probe=28df5fd3c6) | Nov 06, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [42e799bba3](https://linux-hardware.org/?probe=42e799bba3) | Nov 06, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [a6509cbba9](https://linux-hardware.org/?probe=a6509cbba9) | Nov 03, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [3691e08d6d](https://linux-hardware.org/?probe=3691e08d6d) | Nov 03, 2021 |
| Acer          | Aspire A315-35              | Notebook    | [4ac11dfcbe](https://linux-hardware.org/?probe=4ac11dfcbe) | Nov 03, 2021 |
| Acer          | Aspire E5-571G              | Notebook    | [1c57a8d14c](https://linux-hardware.org/?probe=1c57a8d14c) | Nov 02, 2021 |
| Acer          | Aspire VX5-591G             | Notebook    | [66255ca7b5](https://linux-hardware.org/?probe=66255ca7b5) | Oct 30, 2021 |
| ASUSTek       | N551VW                      | Notebook    | [5d4bce82bd](https://linux-hardware.org/?probe=5d4bce82bd) | Oct 30, 2021 |
| ASRock        | B450M Steel Legend          | Desktop     | [bd63d5e0cb](https://linux-hardware.org/?probe=bd63d5e0cb) | Oct 28, 2021 |
| Fujitsu Si... | ESPRIMO Mobile M9410        | Notebook    | [2cec9ef3cc](https://linux-hardware.org/?probe=2cec9ef3cc) | Oct 27, 2021 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [8cae94b7f8](https://linux-hardware.org/?probe=8cae94b7f8) | Oct 20, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [b37e349828](https://linux-hardware.org/?probe=b37e349828) | Oct 19, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [a92566ee89](https://linux-hardware.org/?probe=a92566ee89) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [6d4dad5754](https://linux-hardware.org/?probe=6d4dad5754) | Oct 18, 2021 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [82c79fb7be](https://linux-hardware.org/?probe=82c79fb7be) | Oct 18, 2021 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [696a85e281](https://linux-hardware.org/?probe=696a85e281) | Oct 18, 2021 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [3ab004eed4](https://linux-hardware.org/?probe=3ab004eed4) | Oct 17, 2021 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [4505c960f2](https://linux-hardware.org/?probe=4505c960f2) | Oct 13, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8430d409b5](https://linux-hardware.org/?probe=8430d409b5) | Oct 11, 2021 |
| ASRock        | H81M-HDS                    | Desktop     | [300c7e725d](https://linux-hardware.org/?probe=300c7e725d) | Oct 10, 2021 |
| HP            | Pavilion dv7                | Notebook    | [dfccb89900](https://linux-hardware.org/?probe=dfccb89900) | Oct 09, 2021 |
| Gigabyte      | H310M S2P                   | Desktop     | [637dbbacba](https://linux-hardware.org/?probe=637dbbacba) | Oct 08, 2021 |
| Acer          | Aspire A515-52G             | Notebook    | [bb5c8d6628](https://linux-hardware.org/?probe=bb5c8d6628) | Oct 01, 2021 |
| HP            | Laptop 15-bw0xx             | Notebook    | [642e96374e](https://linux-hardware.org/?probe=642e96374e) | Oct 01, 2021 |
| HP            | EliteBook 8440p             | Notebook    | [6b1e235a76](https://linux-hardware.org/?probe=6b1e235a76) | Sep 28, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [1121eb673b](https://linux-hardware.org/?probe=1121eb673b) | Sep 27, 2021 |
| Acer          | Extensa 5630                | Notebook    | [3bb0bc9c4d](https://linux-hardware.org/?probe=3bb0bc9c4d) | Sep 25, 2021 |
| Acer          | Extensa 5630                | Notebook    | [e4d747d47d](https://linux-hardware.org/?probe=e4d747d47d) | Sep 24, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [b6a9870be5](https://linux-hardware.org/?probe=b6a9870be5) | Sep 22, 2021 |
| Lenovo        | IdeaPad Creator 5 16ACH6... | Notebook    | [7251798837](https://linux-hardware.org/?probe=7251798837) | Sep 20, 2021 |
| MSI           | GF63 Thin 10SCSR            | Notebook    | [b4b1c2d06c](https://linux-hardware.org/?probe=b4b1c2d06c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | Notebook    | [e6cd50fc3c](https://linux-hardware.org/?probe=e6cd50fc3c) | Sep 19, 2021 |
| HP            | Pavilion 17                 | Notebook    | [7854f1ed77](https://linux-hardware.org/?probe=7854f1ed77) | Sep 18, 2021 |
| MSI           | Modern 15 A4M               | Notebook    | [1b2e6b06a0](https://linux-hardware.org/?probe=1b2e6b06a0) | Sep 14, 2021 |
| MSI           | Modern 15 A4M               | Notebook    | [dabdf47bdf](https://linux-hardware.org/?probe=dabdf47bdf) | Sep 13, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [3be61fa185](https://linux-hardware.org/?probe=3be61fa185) | Sep 11, 2021 |
| Lenovo        | ThinkStation D20 4158E93    | Desktop     | [fde770f309](https://linux-hardware.org/?probe=fde770f309) | Sep 11, 2021 |
| Lenovo        | IdeaPad S540-13IML 81XA     | Notebook    | [59ce224e2b](https://linux-hardware.org/?probe=59ce224e2b) | Sep 10, 2021 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | Notebook    | [dce0b57cdc](https://linux-hardware.org/?probe=dce0b57cdc) | Sep 09, 2021 |
| HP            | EliteBook 850 G2            | Notebook    | [8a29546070](https://linux-hardware.org/?probe=8a29546070) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [64f9cfdbab](https://linux-hardware.org/?probe=64f9cfdbab) | Sep 09, 2021 |
| HP            | 250 G2                      | Notebook    | [4fb0a2eab3](https://linux-hardware.org/?probe=4fb0a2eab3) | Sep 09, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [d54f16f7e3](https://linux-hardware.org/?probe=d54f16f7e3) | Sep 07, 2021 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [a95e304baf](https://linux-hardware.org/?probe=a95e304baf) | Sep 07, 2021 |
| Unknown       | Unknown                     | Desktop     | [a37b749b27](https://linux-hardware.org/?probe=a37b749b27) | Sep 06, 2021 |
| Unknown       | Unknown                     | Desktop     | [92e21fb915](https://linux-hardware.org/?probe=92e21fb915) | Sep 06, 2021 |
| Lenovo        | ThinkPad T540p 20BE0084B... | Notebook    | [45914d6e06](https://linux-hardware.org/?probe=45914d6e06) | Sep 04, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [7c76ac10d8](https://linux-hardware.org/?probe=7c76ac10d8) | Sep 04, 2021 |
| AMI           | Aptio CRB                   | Mini pc     | [d831e8693d](https://linux-hardware.org/?probe=d831e8693d) | Sep 04, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [5162b02b61](https://linux-hardware.org/?probe=5162b02b61) | Sep 04, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [5ffaa68de4](https://linux-hardware.org/?probe=5ffaa68de4) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [52474e968d](https://linux-hardware.org/?probe=52474e968d) | Sep 01, 2021 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [c4e6145a5f](https://linux-hardware.org/?probe=c4e6145a5f) | Sep 01, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [9300181bad](https://linux-hardware.org/?probe=9300181bad) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [ce4010bf4f](https://linux-hardware.org/?probe=ce4010bf4f) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [afa0ef75a7](https://linux-hardware.org/?probe=afa0ef75a7) | Aug 31, 2021 |
| Toshiba       | Satellite A200              | Notebook    | [2f2e0ec5bf](https://linux-hardware.org/?probe=2f2e0ec5bf) | Aug 31, 2021 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [7d634f76ad](https://linux-hardware.org/?probe=7d634f76ad) | Aug 31, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [9eb666fd13](https://linux-hardware.org/?probe=9eb666fd13) | Aug 30, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [47ba00786a](https://linux-hardware.org/?probe=47ba00786a) | Aug 30, 2021 |
| ASRock        | FM2A58M-HD+                 | Desktop     | [8a976ca31c](https://linux-hardware.org/?probe=8a976ca31c) | Aug 29, 2021 |
| Lenovo        | ThinkPad X1 Yoga 4th 20S... | Convertible | [8f10e30326](https://linux-hardware.org/?probe=8f10e30326) | Aug 28, 2021 |
| HP            | 18E4                        | Desktop     | [81c51891c9](https://linux-hardware.org/?probe=81c51891c9) | Aug 27, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [2199b6e642](https://linux-hardware.org/?probe=2199b6e642) | Aug 25, 2021 |
| Lenovo        | IdeaPad Y500 20193          | Notebook    | [5b2d90a434](https://linux-hardware.org/?probe=5b2d90a434) | Aug 21, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [1df5582ca4](https://linux-hardware.org/?probe=1df5582ca4) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [7b393c5790](https://linux-hardware.org/?probe=7b393c5790) | Aug 21, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [394c99adc8](https://linux-hardware.org/?probe=394c99adc8) | Aug 19, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [2e24ad5259](https://linux-hardware.org/?probe=2e24ad5259) | Aug 19, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [8461b48819](https://linux-hardware.org/?probe=8461b48819) | Aug 19, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [257e2c9dd4](https://linux-hardware.org/?probe=257e2c9dd4) | Aug 18, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [59f5bb4379](https://linux-hardware.org/?probe=59f5bb4379) | Aug 18, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [32ad696b97](https://linux-hardware.org/?probe=32ad696b97) | Aug 18, 2021 |
| ASRock        | FM2A68M-DG3+                | Desktop     | [3bfb2e6910](https://linux-hardware.org/?probe=3bfb2e6910) | Aug 17, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [5e2f61d652](https://linux-hardware.org/?probe=5e2f61d652) | Aug 16, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [f7de5020c6](https://linux-hardware.org/?probe=f7de5020c6) | Aug 16, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [2ccb1f7da2](https://linux-hardware.org/?probe=2ccb1f7da2) | Aug 16, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [b2d5f563dc](https://linux-hardware.org/?probe=b2d5f563dc) | Aug 15, 2021 |
| MSI           | A68HM-P33 V2                | Desktop     | [4c3bedddac](https://linux-hardware.org/?probe=4c3bedddac) | Aug 14, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [bb46750dfa](https://linux-hardware.org/?probe=bb46750dfa) | Aug 12, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [b106b91bcb](https://linux-hardware.org/?probe=b106b91bcb) | Aug 10, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [4fce5e2d88](https://linux-hardware.org/?probe=4fce5e2d88) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [2553632d5d](https://linux-hardware.org/?probe=2553632d5d) | Aug 09, 2021 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [c77c7b6360](https://linux-hardware.org/?probe=c77c7b6360) | Aug 09, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [76a1354974](https://linux-hardware.org/?probe=76a1354974) | Aug 06, 2021 |
| ASUSTek       | M4A78 PRO                   | Desktop     | [ef7f570d01](https://linux-hardware.org/?probe=ef7f570d01) | Aug 04, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [a06e67aa18](https://linux-hardware.org/?probe=a06e67aa18) | Aug 04, 2021 |
| MSI           | Modern 14 B4MW              | Notebook    | [42266d54c2](https://linux-hardware.org/?probe=42266d54c2) | Aug 02, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [0c191944fc](https://linux-hardware.org/?probe=0c191944fc) | Aug 02, 2021 |
| ASRock        | H110 Pro BTC+               | Desktop     | [a08f9bd38d](https://linux-hardware.org/?probe=a08f9bd38d) | Aug 02, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [d4bc0c2e33](https://linux-hardware.org/?probe=d4bc0c2e33) | Jul 30, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [f015614a5c](https://linux-hardware.org/?probe=f015614a5c) | Jul 27, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [9d0528280a](https://linux-hardware.org/?probe=9d0528280a) | Jul 26, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [93b4e5b92a](https://linux-hardware.org/?probe=93b4e5b92a) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [95ce6f4407](https://linux-hardware.org/?probe=95ce6f4407) | Jul 26, 2021 |
| HP            | ProBook 6450b               | Notebook    | [79d6b91845](https://linux-hardware.org/?probe=79d6b91845) | Jul 26, 2021 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e30dac258e](https://linux-hardware.org/?probe=e30dac258e) | Jul 26, 2021 |
| Acer          | Aspire A717-72G             | Notebook    | [1d1f8cb836](https://linux-hardware.org/?probe=1d1f8cb836) | Jul 25, 2021 |
| Lenovo        | G50-80 80E5                 | Notebook    | [4c5e0baffe](https://linux-hardware.org/?probe=4c5e0baffe) | Jul 25, 2021 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [c7cf1f5978](https://linux-hardware.org/?probe=c7cf1f5978) | Jul 25, 2021 |
| ASUSTek       | H87-PRO                     | Desktop     | [293b556234](https://linux-hardware.org/?probe=293b556234) | Jul 25, 2021 |
| HP            | ProBook 6450b               | Notebook    | [557056dd22](https://linux-hardware.org/?probe=557056dd22) | Jul 24, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [6c5a4659b1](https://linux-hardware.org/?probe=6c5a4659b1) | Jul 23, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [67512f199f](https://linux-hardware.org/?probe=67512f199f) | Jul 23, 2021 |
| AMI           | Cherry Trail CR             | Notebook    | [712382158a](https://linux-hardware.org/?probe=712382158a) | Jul 23, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [b39264f1fa](https://linux-hardware.org/?probe=b39264f1fa) | Jul 22, 2021 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [6e77984276](https://linux-hardware.org/?probe=6e77984276) | Jul 20, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [5d62f330ba](https://linux-hardware.org/?probe=5d62f330ba) | Jul 18, 2021 |
| Acer          | Aspire V3-571G              | Notebook    | [a26a16fb20](https://linux-hardware.org/?probe=a26a16fb20) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | Notebook    | [c18e377104](https://linux-hardware.org/?probe=c18e377104) | Jul 16, 2021 |
| Dell          | Latitude 12 Rugged Extre... | Notebook    | [baf3a7a407](https://linux-hardware.org/?probe=baf3a7a407) | Jul 16, 2021 |
| HP            | ProBook 6450b               | Notebook    | [f596a27975](https://linux-hardware.org/?probe=f596a27975) | Jul 16, 2021 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [d3f2c6d8d8](https://linux-hardware.org/?probe=d3f2c6d8d8) | Jul 13, 2021 |
| ASUSTek       | P5QD TURBO                  | Desktop     | [5ce964530d](https://linux-hardware.org/?probe=5ce964530d) | Jul 13, 2021 |
| Acer          | Predator G9-792             | Notebook    | [e0f2c7b0c5](https://linux-hardware.org/?probe=e0f2c7b0c5) | Jul 12, 2021 |
| HP            | ProBook 6450b               | Notebook    | [d9d8115d98](https://linux-hardware.org/?probe=d9d8115d98) | Jul 11, 2021 |
| HP            | ProBook 6450b               | Notebook    | [c3bdfd8206](https://linux-hardware.org/?probe=c3bdfd8206) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [720242bd55](https://linux-hardware.org/?probe=720242bd55) | Jul 11, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [0005eb3569](https://linux-hardware.org/?probe=0005eb3569) | Jul 11, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [ba7afba1a6](https://linux-hardware.org/?probe=ba7afba1a6) | Jul 08, 2021 |
| Lenovo        | IdeaPad S145-15IGM 81MX     | Notebook    | [47bac68af2](https://linux-hardware.org/?probe=47bac68af2) | Jul 06, 2021 |
| Lenovo        | ThinkPad P52 20MAS07F04     | Notebook    | [4d35b037dd](https://linux-hardware.org/?probe=4d35b037dd) | Jul 04, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [01f81586c8](https://linux-hardware.org/?probe=01f81586c8) | Jul 01, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | Notebook    | [d3b33778bb](https://linux-hardware.org/?probe=d3b33778bb) | Jul 01, 2021 |
| Lenovo        | ThinkPad X240 20AMS3460B    | Notebook    | [3c45c3cf29](https://linux-hardware.org/?probe=3c45c3cf29) | Jul 01, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [13af782a58](https://linux-hardware.org/?probe=13af782a58) | Jun 29, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [c4be5b9bb3](https://linux-hardware.org/?probe=c4be5b9bb3) | Jun 28, 2021 |
| Gigabyte      | GA-870A-USB3                | Desktop     | [d791d77acc](https://linux-hardware.org/?probe=d791d77acc) | Jun 28, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [e56a7ee3c9](https://linux-hardware.org/?probe=e56a7ee3c9) | Jun 27, 2021 |
| HP            | 1493                        | Desktop     | [cd54c7db25](https://linux-hardware.org/?probe=cd54c7db25) | Jun 26, 2021 |
| HP            | 1493                        | Desktop     | [5b7dd91534](https://linux-hardware.org/?probe=5b7dd91534) | Jun 26, 2021 |
| Dell          | Latitude 5410               | Notebook    | [9b8e7a4fc4](https://linux-hardware.org/?probe=9b8e7a4fc4) | Jun 25, 2021 |
| Samsung       | 300E4Z/300E5Z/300E7Z        | Notebook    | [614eb34061](https://linux-hardware.org/?probe=614eb34061) | Jun 24, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [9b92db3a47](https://linux-hardware.org/?probe=9b92db3a47) | Jun 24, 2021 |
| Acer          | Aspire VN7-592G             | Notebook    | [2b00566646](https://linux-hardware.org/?probe=2b00566646) | Jun 23, 2021 |
| MSI           | MS-N033                     | Notebook    | [3ba725911d](https://linux-hardware.org/?probe=3ba725911d) | Jun 22, 2021 |
| MSI           | MS-N033                     | Notebook    | [db865cd4b0](https://linux-hardware.org/?probe=db865cd4b0) | Jun 22, 2021 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [e7e3e4138d](https://linux-hardware.org/?probe=e7e3e4138d) | Jun 20, 2021 |
| Gigabyte      | GA-M56S-S3                  | Desktop     | [c4f55611e4](https://linux-hardware.org/?probe=c4f55611e4) | Jun 20, 2021 |
| Acer          | Extensa 5630                | Notebook    | [a56495c8ee](https://linux-hardware.org/?probe=a56495c8ee) | Jun 19, 2021 |
| HP            | ProBook 450 G8 Notebook ... | Notebook    | [ddbd903ae7](https://linux-hardware.org/?probe=ddbd903ae7) | Jun 11, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [7dfe00559a](https://linux-hardware.org/?probe=7dfe00559a) | Jun 08, 2021 |
| Gigabyte      | GA-MA74GM-S2H               | Desktop     | [f200ec0bda](https://linux-hardware.org/?probe=f200ec0bda) | Jun 08, 2021 |
| Dell          | Studio 1747                 | Notebook    | [b612af8225](https://linux-hardware.org/?probe=b612af8225) | Jun 06, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [505b82b2de](https://linux-hardware.org/?probe=505b82b2de) | Jun 06, 2021 |
| Fujitsu       | D3162-A1 S26361-D3162-A1    | Desktop     | [9a2b696908](https://linux-hardware.org/?probe=9a2b696908) | Jun 05, 2021 |
| HP            | Pavilion dv5                | Notebook    | [94cfdbc88f](https://linux-hardware.org/?probe=94cfdbc88f) | Jun 03, 2021 |
| Dell          | Latitude 5500               | Notebook    | [4eb777675a](https://linux-hardware.org/?probe=4eb777675a) | Jun 03, 2021 |
| ASUSTek       | TP300LA                     | Notebook    | [1c4ff3ec3c](https://linux-hardware.org/?probe=1c4ff3ec3c) | Jun 02, 2021 |
| ASUSTek       | TP300LA                     | Notebook    | [aa03d405bc](https://linux-hardware.org/?probe=aa03d405bc) | May 31, 2021 |
| Gigabyte      | Z490 AORUS ELITE AC         | Desktop     | [6bc1b9dcc9](https://linux-hardware.org/?probe=6bc1b9dcc9) | May 31, 2021 |
| Dell          | 0K240Y A02                  | Desktop     | [c050f79e2b](https://linux-hardware.org/?probe=c050f79e2b) | May 29, 2021 |
| Dell          | 0K240Y A02                  | Desktop     | [7f510d13fb](https://linux-hardware.org/?probe=7f510d13fb) | May 28, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [660a6b9e20](https://linux-hardware.org/?probe=660a6b9e20) | May 26, 2021 |
| HP            | ProBook 4540s               | Notebook    | [d0705ef193](https://linux-hardware.org/?probe=d0705ef193) | May 23, 2021 |
| HP            | ProBook 4540s               | Notebook    | [08209a81e4](https://linux-hardware.org/?probe=08209a81e4) | May 23, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [eccabc11a1](https://linux-hardware.org/?probe=eccabc11a1) | May 21, 2021 |
| Apple         | MacBookAir7,2               | Notebook    | [2fd0c6a88a](https://linux-hardware.org/?probe=2fd0c6a88a) | May 21, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [60450a65b2](https://linux-hardware.org/?probe=60450a65b2) | May 20, 2021 |
| ASRock        | Z97 Anniversary             | Desktop     | [493f6f8057](https://linux-hardware.org/?probe=493f6f8057) | May 18, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [c6ddc776ea](https://linux-hardware.org/?probe=c6ddc776ea) | May 18, 2021 |
| Dell          | Studio 1535                 | Notebook    | [90762831e7](https://linux-hardware.org/?probe=90762831e7) | May 17, 2021 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [4d5f23e6ba](https://linux-hardware.org/?probe=4d5f23e6ba) | May 17, 2021 |
| Dell          | Studio 1535                 | Notebook    | [9d034e29dc](https://linux-hardware.org/?probe=9d034e29dc) | May 16, 2021 |
| ASRock        | Z97 Anniversary             | Desktop     | [14ea7483bc](https://linux-hardware.org/?probe=14ea7483bc) | May 16, 2021 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [8dac91acc9](https://linux-hardware.org/?probe=8dac91acc9) | May 16, 2021 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [22657f3929](https://linux-hardware.org/?probe=22657f3929) | May 15, 2021 |
| HP            | 3396                        | Desktop     | [ed3fa57f54](https://linux-hardware.org/?probe=ed3fa57f54) | May 15, 2021 |
| ASUSTek       | B150M-A                     | Desktop     | [ecc85d30a9](https://linux-hardware.org/?probe=ecc85d30a9) | May 13, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [133c3509a5](https://linux-hardware.org/?probe=133c3509a5) | May 13, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [75b2ef5126](https://linux-hardware.org/?probe=75b2ef5126) | May 13, 2021 |
| Lenovo        | ThinkPad L450 20DSS00N18    | Notebook    | [85f3722d36](https://linux-hardware.org/?probe=85f3722d36) | May 12, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [cf41b106cb](https://linux-hardware.org/?probe=cf41b106cb) | May 11, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [6ac4eae2c6](https://linux-hardware.org/?probe=6ac4eae2c6) | May 10, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [734a4fbc56](https://linux-hardware.org/?probe=734a4fbc56) | May 09, 2021 |
| Gigabyte      | A320MA-M.2-CF               | Desktop     | [511e08ef09](https://linux-hardware.org/?probe=511e08ef09) | May 09, 2021 |
| Unknown       | Unknown                     | Desktop     | [c42f475a67](https://linux-hardware.org/?probe=c42f475a67) | May 08, 2021 |
| Lenovo        | ThinkPad T61 765912G        | Notebook    | [998d8e53db](https://linux-hardware.org/?probe=998d8e53db) | May 07, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [67bde80034](https://linux-hardware.org/?probe=67bde80034) | May 04, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [80549acbba](https://linux-hardware.org/?probe=80549acbba) | May 03, 2021 |
| ASRock        | X570 Pro4                   | Desktop     | [3ad2c89a0a](https://linux-hardware.org/?probe=3ad2c89a0a) | May 03, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [f2313ee72b](https://linux-hardware.org/?probe=f2313ee72b) | May 03, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [7065f7bb74](https://linux-hardware.org/?probe=7065f7bb74) | May 02, 2021 |
| Acer          | Swift SF114-33              | Notebook    | [59d8b5d3fe](https://linux-hardware.org/?probe=59d8b5d3fe) | May 02, 2021 |
| HP            | Pavilion dv5                | Notebook    | [f75415bbd7](https://linux-hardware.org/?probe=f75415bbd7) | May 01, 2021 |
| ASRock        | X79 Extreme4                | Desktop     | [d3383d57ef](https://linux-hardware.org/?probe=d3383d57ef) | May 01, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [50505c9ede](https://linux-hardware.org/?probe=50505c9ede) | Apr 30, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [b51106e072](https://linux-hardware.org/?probe=b51106e072) | Apr 30, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [3b2545921f](https://linux-hardware.org/?probe=3b2545921f) | Apr 29, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [37b746015a](https://linux-hardware.org/?probe=37b746015a) | Apr 28, 2021 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [03b6a0117c](https://linux-hardware.org/?probe=03b6a0117c) | Apr 26, 2021 |
| ASUSTek       | Amberine M                  | Desktop     | [9eeaeb53fc](https://linux-hardware.org/?probe=9eeaeb53fc) | Apr 26, 2021 |
| HP            | Notebook                    | Notebook    | [3cc10cc5f1](https://linux-hardware.org/?probe=3cc10cc5f1) | Apr 24, 2021 |
| ASRock        | B360M Pro4                  | Desktop     | [b1f9a4880e](https://linux-hardware.org/?probe=b1f9a4880e) | Apr 22, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [8123f6484e](https://linux-hardware.org/?probe=8123f6484e) | Apr 18, 2021 |
| ASUSTek       | K52Je                       | Notebook    | [fb1ce94b02](https://linux-hardware.org/?probe=fb1ce94b02) | Apr 16, 2021 |
| Toshiba       | Satellite U400              | Notebook    | [159d86eda9](https://linux-hardware.org/?probe=159d86eda9) | Apr 16, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [e6cc5fbf7f](https://linux-hardware.org/?probe=e6cc5fbf7f) | Apr 15, 2021 |
| Apple         | Mac-4BC72D62AD45599E Mac... | Mini pc     | [a7b1f80885](https://linux-hardware.org/?probe=a7b1f80885) | Apr 15, 2021 |
| HP            | Pavilion dv5                | Notebook    | [901dd6f4bc](https://linux-hardware.org/?probe=901dd6f4bc) | Apr 14, 2021 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [8c83051b44](https://linux-hardware.org/?probe=8c83051b44) | Apr 12, 2021 |
| ASRock        | Z68 Extreme7 Gen3           | Desktop     | [d8e2ac9e9b](https://linux-hardware.org/?probe=d8e2ac9e9b) | Apr 11, 2021 |
| Dell          | Vostro 3558                 | Notebook    | [025fc515fe](https://linux-hardware.org/?probe=025fc515fe) | Apr 10, 2021 |
| Lenovo        | ThinkPad X250 20CLS1LC13    | Notebook    | [dc8d311227](https://linux-hardware.org/?probe=dc8d311227) | Apr 09, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [81aeaba043](https://linux-hardware.org/?probe=81aeaba043) | Apr 09, 2021 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [891b52b28e](https://linux-hardware.org/?probe=891b52b28e) | Apr 08, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [8a34a292e5](https://linux-hardware.org/?probe=8a34a292e5) | Apr 07, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [bce1022d19](https://linux-hardware.org/?probe=bce1022d19) | Apr 07, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [996a7d6ddd](https://linux-hardware.org/?probe=996a7d6ddd) | Apr 06, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [e2c1bc20ae](https://linux-hardware.org/?probe=e2c1bc20ae) | Apr 06, 2021 |
| ASUSTek       | P5KC                        | Desktop     | [b687d3a64f](https://linux-hardware.org/?probe=b687d3a64f) | Apr 06, 2021 |
| Dell          | Latitude E6330              | Notebook    | [929d29d6a1](https://linux-hardware.org/?probe=929d29d6a1) | Apr 04, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [ba65bedf97](https://linux-hardware.org/?probe=ba65bedf97) | Apr 04, 2021 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [658ec2843e](https://linux-hardware.org/?probe=658ec2843e) | Apr 03, 2021 |
| HP            | 1850                        | Desktop     | [517c6137a3](https://linux-hardware.org/?probe=517c6137a3) | Apr 01, 2021 |
| ASRock        | B550M Pro4                  | Desktop     | [333c645cc4](https://linux-hardware.org/?probe=333c645cc4) | Apr 01, 2021 |
| Dell          | Inspiron MM061              | Notebook    | [b5fd8765a4](https://linux-hardware.org/?probe=b5fd8765a4) | Mar 31, 2021 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [0d90d26719](https://linux-hardware.org/?probe=0d90d26719) | Mar 31, 2021 |
| Packard Be... | EasyNote TK87               | Notebook    | [f7a63e6a25](https://linux-hardware.org/?probe=f7a63e6a25) | Mar 30, 2021 |
| Toshiba       | QOSMIO F50                  | Notebook    | [d9d565847f](https://linux-hardware.org/?probe=d9d565847f) | Mar 29, 2021 |
| HP            | Compaq 6530b (GW688AV#AK... | Notebook    | [4644bc75a5](https://linux-hardware.org/?probe=4644bc75a5) | Mar 29, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [666815417c](https://linux-hardware.org/?probe=666815417c) | Mar 28, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [8cc548dedd](https://linux-hardware.org/?probe=8cc548dedd) | Mar 28, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [cc467b4015](https://linux-hardware.org/?probe=cc467b4015) | Mar 27, 2021 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [129caa2510](https://linux-hardware.org/?probe=129caa2510) | Mar 27, 2021 |
| ASRock        | AB350M Pro4                 | Desktop     | [bd779f8e4e](https://linux-hardware.org/?probe=bd779f8e4e) | Mar 26, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [072483c895](https://linux-hardware.org/?probe=072483c895) | Mar 26, 2021 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [11e59c84c6](https://linux-hardware.org/?probe=11e59c84c6) | Mar 26, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [151e709efd](https://linux-hardware.org/?probe=151e709efd) | Mar 25, 2021 |
| ASUSTek       | E502SA                      | Notebook    | [11a2b81dd1](https://linux-hardware.org/?probe=11a2b81dd1) | Mar 24, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [d2027dc1c2](https://linux-hardware.org/?probe=d2027dc1c2) | Mar 24, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [f6eae97e20](https://linux-hardware.org/?probe=f6eae97e20) | Mar 24, 2021 |
| Acer          | TravelMate 8571             | Notebook    | [a4f34315e7](https://linux-hardware.org/?probe=a4f34315e7) | Mar 23, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [f7c456b329](https://linux-hardware.org/?probe=f7c456b329) | Mar 22, 2021 |
| Toshiba       | PORTEGE R830                | Notebook    | [f4b00c40b9](https://linux-hardware.org/?probe=f4b00c40b9) | Mar 22, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [9e4bff4b7d](https://linux-hardware.org/?probe=9e4bff4b7d) | Mar 21, 2021 |
| Seco          | C40 C                       | Desktop     | [70a92f2d8a](https://linux-hardware.org/?probe=70a92f2d8a) | Mar 19, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [ac215043f1](https://linux-hardware.org/?probe=ac215043f1) | Mar 19, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [2cad1297af](https://linux-hardware.org/?probe=2cad1297af) | Mar 19, 2021 |
| Dell          | Inspiron 7577               | Notebook    | [5318792cf8](https://linux-hardware.org/?probe=5318792cf8) | Mar 19, 2021 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [e5f799a9f1](https://linux-hardware.org/?probe=e5f799a9f1) | Mar 19, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [1b40fb1844](https://linux-hardware.org/?probe=1b40fb1844) | Mar 17, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [d2d43a5a92](https://linux-hardware.org/?probe=d2d43a5a92) | Mar 17, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [ef2bfba994](https://linux-hardware.org/?probe=ef2bfba994) | Mar 17, 2021 |
| ECS           | MCP61M-M3                   | Desktop     | [39fb7fbfdd](https://linux-hardware.org/?probe=39fb7fbfdd) | Mar 17, 2021 |
| ASRock        | B450M-HDV R4.0              | Desktop     | [30047ff89f](https://linux-hardware.org/?probe=30047ff89f) | Mar 17, 2021 |
| ASUSTek       | B85M-G                      | Desktop     | [a100c1ee1d](https://linux-hardware.org/?probe=a100c1ee1d) | Mar 15, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [01681dba78](https://linux-hardware.org/?probe=01681dba78) | Mar 14, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [3fc42af6ee](https://linux-hardware.org/?probe=3fc42af6ee) | Mar 13, 2021 |
| Dell          | 0T10XW A02                  | Desktop     | [3403829400](https://linux-hardware.org/?probe=3403829400) | Mar 13, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [5a3ce75489](https://linux-hardware.org/?probe=5a3ce75489) | Mar 12, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [e2bd9d6df8](https://linux-hardware.org/?probe=e2bd9d6df8) | Mar 11, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [bbd590263a](https://linux-hardware.org/?probe=bbd590263a) | Mar 11, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [5ff3194762](https://linux-hardware.org/?probe=5ff3194762) | Mar 10, 2021 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [c685612dc3](https://linux-hardware.org/?probe=c685612dc3) | Mar 09, 2021 |
| ASRock        | AB350 Pro4                  | Desktop     | [a76ade188b](https://linux-hardware.org/?probe=a76ade188b) | Mar 07, 2021 |
| MSI           | Z270 GAMING PRO CARBON      | Desktop     | [b3a1ae5051](https://linux-hardware.org/?probe=b3a1ae5051) | Mar 06, 2021 |
| Gigabyte      | Z97X-Gaming 3               | Desktop     | [f14a8d2de0](https://linux-hardware.org/?probe=f14a8d2de0) | Mar 05, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [b7a83e1d4a](https://linux-hardware.org/?probe=b7a83e1d4a) | Mar 05, 2021 |
| Lenovo        | Yoga 500-14ISK 80R5         | Notebook    | [871b9656f1](https://linux-hardware.org/?probe=871b9656f1) | Mar 04, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [67054a2b55](https://linux-hardware.org/?probe=67054a2b55) | Mar 04, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [18268633d9](https://linux-hardware.org/?probe=18268633d9) | Mar 03, 2021 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [c4e5bc819d](https://linux-hardware.org/?probe=c4e5bc819d) | Mar 02, 2021 |
| Dell          | XPS 13 9365                 | Convertible | [ee7f196bf2](https://linux-hardware.org/?probe=ee7f196bf2) | Feb 28, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [3145841279](https://linux-hardware.org/?probe=3145841279) | Feb 25, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [835e8cad03](https://linux-hardware.org/?probe=835e8cad03) | Feb 25, 2021 |
| Fujitsu       | CELSIUS H720                | Notebook    | [ebed3a7dfe](https://linux-hardware.org/?probe=ebed3a7dfe) | Feb 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [a95dd47eb7](https://linux-hardware.org/?probe=a95dd47eb7) | Feb 25, 2021 |
| Intel         | X99 V102                    | Desktop     | [e4884fdd22](https://linux-hardware.org/?probe=e4884fdd22) | Feb 25, 2021 |
| ASUSTek       | ROG Strix G531GT_G531GT     | Notebook    | [afb4a1cd76](https://linux-hardware.org/?probe=afb4a1cd76) | Feb 24, 2021 |
| HP            | 3396                        | Desktop     | [dd8601c672](https://linux-hardware.org/?probe=dd8601c672) | Feb 24, 2021 |
| HP            | 3396                        | Desktop     | [5c5fde40cd](https://linux-hardware.org/?probe=5c5fde40cd) | Feb 24, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [53d26490a1](https://linux-hardware.org/?probe=53d26490a1) | Feb 23, 2021 |
| Dell          | Inspiron 3584               | Notebook    | [5db4b64bf0](https://linux-hardware.org/?probe=5db4b64bf0) | Feb 23, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [d5c37bac28](https://linux-hardware.org/?probe=d5c37bac28) | Feb 23, 2021 |
| HP            | 1494                        | Desktop     | [c369d28059](https://linux-hardware.org/?probe=c369d28059) | Feb 23, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [5ad971da58](https://linux-hardware.org/?probe=5ad971da58) | Feb 23, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [544bcae58c](https://linux-hardware.org/?probe=544bcae58c) | Feb 22, 2021 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [698bd7ab9c](https://linux-hardware.org/?probe=698bd7ab9c) | Feb 22, 2021 |
| Gigabyte      | Z490I AORUS ULTRA           | Desktop     | [e5ae830bbf](https://linux-hardware.org/?probe=e5ae830bbf) | Feb 21, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [b9b1df7b2d](https://linux-hardware.org/?probe=b9b1df7b2d) | Feb 21, 2021 |
| ASUSTek       | G752VL                      | Notebook    | [3c853cb10a](https://linux-hardware.org/?probe=3c853cb10a) | Feb 21, 2021 |
| Acer          | Nitro AN515-43              | Notebook    | [31612033c1](https://linux-hardware.org/?probe=31612033c1) | Feb 18, 2021 |
| Acer          | Aspire E5-771G              | Notebook    | [6606087332](https://linux-hardware.org/?probe=6606087332) | Feb 17, 2021 |
| Dell          | 0DFRFW A01                  | Desktop     | [71a10bba93](https://linux-hardware.org/?probe=71a10bba93) | Feb 16, 2021 |
| Toshiba       | TECRA A11                   | Notebook    | [96fc158d33](https://linux-hardware.org/?probe=96fc158d33) | Feb 16, 2021 |
| Dell          | Latitude E6430              | Notebook    | [f858e68811](https://linux-hardware.org/?probe=f858e68811) | Feb 15, 2021 |
| MSI           | MS-7250                     | Desktop     | [e1f266f412](https://linux-hardware.org/?probe=e1f266f412) | Feb 15, 2021 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [0954aa8af0](https://linux-hardware.org/?probe=0954aa8af0) | Feb 15, 2021 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [ee6f13c76b](https://linux-hardware.org/?probe=ee6f13c76b) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [4dd2d0ba4d](https://linux-hardware.org/?probe=4dd2d0ba4d) | Feb 15, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [9d43f3047b](https://linux-hardware.org/?probe=9d43f3047b) | Feb 15, 2021 |
| MSI           | H61M-P31                    | Desktop     | [256f5dc934](https://linux-hardware.org/?probe=256f5dc934) | Feb 14, 2021 |
| ASUSTek       | A8N-E                       | Desktop     | [a35eff4bb9](https://linux-hardware.org/?probe=a35eff4bb9) | Feb 14, 2021 |
| iEi           | B202 V1.0                   | Desktop     | [3dce687709](https://linux-hardware.org/?probe=3dce687709) | Feb 14, 2021 |
| Gigabyte      | H81M-HD3                    | Desktop     | [b6b357f26c](https://linux-hardware.org/?probe=b6b357f26c) | Feb 14, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [476cc70c3f](https://linux-hardware.org/?probe=476cc70c3f) | Feb 13, 2021 |
| ASRock        | 890GX Extreme3              | Desktop     | [1168daa7de](https://linux-hardware.org/?probe=1168daa7de) | Feb 13, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [aa7fb32dfe](https://linux-hardware.org/?probe=aa7fb32dfe) | Feb 13, 2021 |
| ASUSTek       | P5K PRO                     | Desktop     | [dc1822ee72](https://linux-hardware.org/?probe=dc1822ee72) | Feb 13, 2021 |
| ASUSTek       | P5K PRO                     | Desktop     | [8fedc4a9c1](https://linux-hardware.org/?probe=8fedc4a9c1) | Feb 12, 2021 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [2d6363ed19](https://linux-hardware.org/?probe=2d6363ed19) | Feb 10, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [b3a0df6f88](https://linux-hardware.org/?probe=b3a0df6f88) | Feb 10, 2021 |
| Dell          | Vostro 3580                 | Notebook    | [9659cc6044](https://linux-hardware.org/?probe=9659cc6044) | Feb 10, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [12349b18fb](https://linux-hardware.org/?probe=12349b18fb) | Feb 10, 2021 |
| ASUSTek       | GL553VE                     | Notebook    | [32fe0edcd8](https://linux-hardware.org/?probe=32fe0edcd8) | Feb 07, 2021 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [e196e2ba5d](https://linux-hardware.org/?probe=e196e2ba5d) | Feb 07, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [ea03b28712](https://linux-hardware.org/?probe=ea03b28712) | Feb 06, 2021 |
| HP            | ProBook 450 G0              | Notebook    | [a327d5e0ca](https://linux-hardware.org/?probe=a327d5e0ca) | Feb 06, 2021 |
| Lenovo        | ThinkPad T460s 20FAS0SY0... | Notebook    | [26dbb68145](https://linux-hardware.org/?probe=26dbb68145) | Feb 05, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9f77a9eea6](https://linux-hardware.org/?probe=9f77a9eea6) | Feb 04, 2021 |
| ASRock        | X570 Taichi                 | Desktop     | [9b6ea4cda5](https://linux-hardware.org/?probe=9b6ea4cda5) | Feb 04, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [43384d51bb](https://linux-hardware.org/?probe=43384d51bb) | Feb 04, 2021 |
| HP            | ProBook 6460b               | Notebook    | [e531fae869](https://linux-hardware.org/?probe=e531fae869) | Feb 02, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [154f183a32](https://linux-hardware.org/?probe=154f183a32) | Feb 01, 2021 |
| ASRock        | FM2A85X Extreme4            | Desktop     | [2f1725cb23](https://linux-hardware.org/?probe=2f1725cb23) | Jan 30, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [0d28bdf0d4](https://linux-hardware.org/?probe=0d28bdf0d4) | Jan 30, 2021 |
| Apple         | MacBook4,1                  | Notebook    | [566ca9b700](https://linux-hardware.org/?probe=566ca9b700) | Jan 30, 2021 |
| ASUSTek       | PRIME X570-P                | Desktop     | [d566b4292e](https://linux-hardware.org/?probe=d566b4292e) | Jan 30, 2021 |
| Toshiba       | Satellite L655              | Notebook    | [c0670e9519](https://linux-hardware.org/?probe=c0670e9519) | Jan 29, 2021 |
| Lenovo        | ThinkPad T430 2349PS3       | Notebook    | [b7eecfebd0](https://linux-hardware.org/?probe=b7eecfebd0) | Jan 29, 2021 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [5e824ae0f4](https://linux-hardware.org/?probe=5e824ae0f4) | Jan 29, 2021 |
| Lenovo        | ThinkPad T450s 20BWS3MG0... | Notebook    | [c8df50c9cc](https://linux-hardware.org/?probe=c8df50c9cc) | Jan 28, 2021 |
| Dell          | XPS 13 9360                 | Notebook    | [752f448ced](https://linux-hardware.org/?probe=752f448ced) | Jan 25, 2021 |
| ASRock        | H87M Pro4                   | Desktop     | [88e1834599](https://linux-hardware.org/?probe=88e1834599) | Jan 24, 2021 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2fef9954bb](https://linux-hardware.org/?probe=2fef9954bb) | Jan 24, 2021 |
| ASUSTek       | M5A78L-M LX                 | Desktop     | [194dbb8e46](https://linux-hardware.org/?probe=194dbb8e46) | Jan 24, 2021 |
| Gigabyte      | M68M-S2P                    | Desktop     | [bdee5c1907](https://linux-hardware.org/?probe=bdee5c1907) | Jan 23, 2021 |
| ASRock        | H110M-HDV                   | Desktop     | [6eecfdfd4b](https://linux-hardware.org/?probe=6eecfdfd4b) | Jan 21, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [e10b7bc8cf](https://linux-hardware.org/?probe=e10b7bc8cf) | Jan 21, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [9bf6a2ce4c](https://linux-hardware.org/?probe=9bf6a2ce4c) | Jan 18, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [2f0ad65f95](https://linux-hardware.org/?probe=2f0ad65f95) | Jan 16, 2021 |
| MSI           | GP60 2PE                    | Notebook    | [676959ecd5](https://linux-hardware.org/?probe=676959ecd5) | Jan 16, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [82993a1ca3](https://linux-hardware.org/?probe=82993a1ca3) | Jan 15, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [782581f6ad](https://linux-hardware.org/?probe=782581f6ad) | Jan 15, 2021 |
| MiTAC         | E220 6A7                    | Desktop     | [0d75e5ba34](https://linux-hardware.org/?probe=0d75e5ba34) | Jan 14, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [4697da630e](https://linux-hardware.org/?probe=4697da630e) | Jan 13, 2021 |
| HP            | EliteBook 850 G5            | Notebook    | [839dd41ca6](https://linux-hardware.org/?probe=839dd41ca6) | Jan 13, 2021 |
| Acer          | Extensa 5630                | Notebook    | [6ebd228e2a](https://linux-hardware.org/?probe=6ebd228e2a) | Jan 12, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [1c8eedbc0f](https://linux-hardware.org/?probe=1c8eedbc0f) | Jan 11, 2021 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [4bce8eccc2](https://linux-hardware.org/?probe=4bce8eccc2) | Jan 10, 2021 |
| Lenovo        | IdeaPad 320-15IAP 80XR      | Notebook    | [947ae48eec](https://linux-hardware.org/?probe=947ae48eec) | Jan 10, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [20416ee115](https://linux-hardware.org/?probe=20416ee115) | Jan 10, 2021 |
| HP            | EliteBook 1050 G1           | Notebook    | [34b72d5988](https://linux-hardware.org/?probe=34b72d5988) | Jan 10, 2021 |
| Apple         | MacBookPro11,1              | Notebook    | [e8ac486033](https://linux-hardware.org/?probe=e8ac486033) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [9cd4e14d95](https://linux-hardware.org/?probe=9cd4e14d95) | Jan 09, 2021 |
| Lenovo        | V130-15IGM 81HL             | Notebook    | [d0a18fe6bf](https://linux-hardware.org/?probe=d0a18fe6bf) | Jan 09, 2021 |
| Sony          | VPCEA3L1E                   | Notebook    | [5d9e8a1b24](https://linux-hardware.org/?probe=5d9e8a1b24) | Jan 08, 2021 |
| Sony          | VPCEA3L1E                   | Notebook    | [251d4f6677](https://linux-hardware.org/?probe=251d4f6677) | Jan 07, 2021 |
| Dell          | Latitude E5440              | Notebook    | [b207a3f9fc](https://linux-hardware.org/?probe=b207a3f9fc) | Jan 07, 2021 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [67484b4909](https://linux-hardware.org/?probe=67484b4909) | Jan 06, 2021 |
| Dell          | 0K240Y A02                  | Desktop     | [1c948eea28](https://linux-hardware.org/?probe=1c948eea28) | Jan 05, 2021 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [13e7f80b8f](https://linux-hardware.org/?probe=13e7f80b8f) | Jan 03, 2021 |
| Packard Be... | EasyNote TK87               | Notebook    | [c56d5ed89f](https://linux-hardware.org/?probe=c56d5ed89f) | Jan 03, 2021 |
| Gigabyte      | GA-MA78LMT-US2H             | Desktop     | [5232dd577c](https://linux-hardware.org/?probe=5232dd577c) | Jan 03, 2021 |
| Dell          | Latitude E6410              | Notebook    | [0a272a215c](https://linux-hardware.org/?probe=0a272a215c) | Jan 02, 2021 |
| Dell          | Latitude E6410              | Notebook    | [38d452be3e](https://linux-hardware.org/?probe=38d452be3e) | Jan 02, 2021 |
| ASUSTek       | P8H77-V                     | Desktop     | [50edfe4e5e](https://linux-hardware.org/?probe=50edfe4e5e) | Jan 01, 2021 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [05fcb61de6](https://linux-hardware.org/?probe=05fcb61de6) | Dec 29, 2020 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [b1855e2094](https://linux-hardware.org/?probe=b1855e2094) | Dec 29, 2020 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [5d028d0524](https://linux-hardware.org/?probe=5d028d0524) | Dec 29, 2020 |
| Toshiba       | Satellite A300              | Notebook    | [83cb7ff036](https://linux-hardware.org/?probe=83cb7ff036) | Dec 28, 2020 |
| HP            | Laptop 15-da0xxx            | Notebook    | [55bd66c418](https://linux-hardware.org/?probe=55bd66c418) | Dec 27, 2020 |
| HP            | Pavilion x360 Convertibl... | Convertible | [b2e6caf193](https://linux-hardware.org/?probe=b2e6caf193) | Dec 25, 2020 |
| ASUSTek       | P5G41T-M LX                 | Desktop     | [06f63c2119](https://linux-hardware.org/?probe=06f63c2119) | Dec 24, 2020 |
| Lenovo        | MAHOBAY Win8 STD MM DPK ... | Desktop     | [fed52f343a](https://linux-hardware.org/?probe=fed52f343a) | Dec 24, 2020 |
| MiTAC         | E220 6A7                    | Desktop     | [e051bc126d](https://linux-hardware.org/?probe=e051bc126d) | Dec 23, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [27df1aad94](https://linux-hardware.org/?probe=27df1aad94) | Dec 22, 2020 |
| Acer          | Aspire A315-31              | Notebook    | [d04453166b](https://linux-hardware.org/?probe=d04453166b) | Dec 21, 2020 |
| Lenovo        | ThinkPad T500 20567LG       | Notebook    | [9435132c9f](https://linux-hardware.org/?probe=9435132c9f) | Dec 21, 2020 |
| Dell          | 0K240Y A02                  | Desktop     | [d522c503da](https://linux-hardware.org/?probe=d522c503da) | Dec 21, 2020 |
| ASUSTek       | ROG STRIX X299-E GAMING ... | Desktop     | [ad3ac7bcee](https://linux-hardware.org/?probe=ad3ac7bcee) | Dec 19, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [17dc1d498a](https://linux-hardware.org/?probe=17dc1d498a) | Dec 18, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [5505991d80](https://linux-hardware.org/?probe=5505991d80) | Dec 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [e665e888af](https://linux-hardware.org/?probe=e665e888af) | Dec 16, 2020 |
| Unknown       | GSUO H61                    | Desktop     | [3c4c6c8bd0](https://linux-hardware.org/?probe=3c4c6c8bd0) | Dec 14, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [eb181ebb12](https://linux-hardware.org/?probe=eb181ebb12) | Dec 14, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [8e26299b90](https://linux-hardware.org/?probe=8e26299b90) | Dec 13, 2020 |
| Gigabyte      | EP45-DS3L                   | Desktop     | [d0388f0066](https://linux-hardware.org/?probe=d0388f0066) | Dec 12, 2020 |
| Apple         | MacBook4,1                  | Notebook    | [2f0d63f9a3](https://linux-hardware.org/?probe=2f0d63f9a3) | Dec 12, 2020 |
| Toshiba       | Satellite C50-A-19T         | Notebook    | [0236c0854e](https://linux-hardware.org/?probe=0236c0854e) | Dec 12, 2020 |
| Gigabyte      | EQ45M-S2                    | Desktop     | [2c39a254ee](https://linux-hardware.org/?probe=2c39a254ee) | Dec 11, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [d4d7a977db](https://linux-hardware.org/?probe=d4d7a977db) | Dec 07, 2020 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [6502e1050d](https://linux-hardware.org/?probe=6502e1050d) | Dec 05, 2020 |
| Lenovo        | ThinkPad X1 Carbon 5th 2... | Notebook    | [a388c1bf1e](https://linux-hardware.org/?probe=a388c1bf1e) | Dec 05, 2020 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [b7e98a5926](https://linux-hardware.org/?probe=b7e98a5926) | Dec 04, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [ef428fdd17](https://linux-hardware.org/?probe=ef428fdd17) | Dec 03, 2020 |
| ASRock        | FM2A75 Pro4+                | Desktop     | [d12dc95e76](https://linux-hardware.org/?probe=d12dc95e76) | Dec 03, 2020 |
| ASRock        | FM2A75 Pro4+                | Desktop     | [02c7320eaf](https://linux-hardware.org/?probe=02c7320eaf) | Dec 03, 2020 |
| ASRock        | G41M-S3                     | Desktop     | [1f91a14ff2](https://linux-hardware.org/?probe=1f91a14ff2) | Dec 03, 2020 |
| Dell          | Latitude 5591               | Notebook    | [43f7f0c137](https://linux-hardware.org/?probe=43f7f0c137) | Dec 02, 2020 |
| Dell          | Vostro 3580                 | Notebook    | [a3342731b8](https://linux-hardware.org/?probe=a3342731b8) | Dec 01, 2020 |
| Cube          | i16-L                       | Notebook    | [80ab92ec4d](https://linux-hardware.org/?probe=80ab92ec4d) | Dec 01, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | Notebook    | [f5481042a6](https://linux-hardware.org/?probe=f5481042a6) | Nov 30, 2020 |
| Lenovo        | ThinkPad T495 20NKS01W0H    | Notebook    | [911676a550](https://linux-hardware.org/?probe=911676a550) | Nov 30, 2020 |
| ASRock        | X370 Gaming K4              | Desktop     | [7b8b964ce4](https://linux-hardware.org/?probe=7b8b964ce4) | Nov 29, 2020 |
| Lenovo        | ThinkPad X220 4291QT1       | Notebook    | [0b050dca43](https://linux-hardware.org/?probe=0b050dca43) | Nov 29, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [a5669b915e](https://linux-hardware.org/?probe=a5669b915e) | Nov 25, 2020 |
| Dell          | 0K240Y A02                  | Desktop     | [6f8d2322b6](https://linux-hardware.org/?probe=6f8d2322b6) | Nov 25, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [8edf6487f6](https://linux-hardware.org/?probe=8edf6487f6) | Nov 23, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [f0cf2d64a6](https://linux-hardware.org/?probe=f0cf2d64a6) | Nov 23, 2020 |
| Lenovo        | ThinkPad T460s 20FAS2BV0... | Notebook    | [c58bafb526](https://linux-hardware.org/?probe=c58bafb526) | Nov 23, 2020 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [09df23b136](https://linux-hardware.org/?probe=09df23b136) | Nov 20, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [be1f635a9d](https://linux-hardware.org/?probe=be1f635a9d) | Nov 19, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [6e49198d1d](https://linux-hardware.org/?probe=6e49198d1d) | Nov 19, 2020 |
| HP            | EliteBook 850 G7 Noteboo... | Notebook    | [ed63cb31af](https://linux-hardware.org/?probe=ed63cb31af) | Nov 18, 2020 |
| HP            | 2B56                        | All in one  | [3db64c4252](https://linux-hardware.org/?probe=3db64c4252) | Nov 17, 2020 |
| HP            | 2B56                        | All in one  | [1eb0afe0ed](https://linux-hardware.org/?probe=1eb0afe0ed) | Nov 17, 2020 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [a2ac4f643a](https://linux-hardware.org/?probe=a2ac4f643a) | Nov 17, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [ca8ffcb464](https://linux-hardware.org/?probe=ca8ffcb464) | Nov 15, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [f934cc994f](https://linux-hardware.org/?probe=f934cc994f) | Nov 14, 2020 |
| Acer          | Aspire E5-572G              | Notebook    | [aa4817a78d](https://linux-hardware.org/?probe=aa4817a78d) | Nov 12, 2020 |
| Lenovo        | MAHOBAY                     | Desktop     | [7698cbedd0](https://linux-hardware.org/?probe=7698cbedd0) | Nov 12, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [c1df930d7e](https://linux-hardware.org/?probe=c1df930d7e) | Nov 10, 2020 |
| ASUSTek       | G551JM                      | Notebook    | [5bf5531f2d](https://linux-hardware.org/?probe=5bf5531f2d) | Nov 08, 2020 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [1b21b64248](https://linux-hardware.org/?probe=1b21b64248) | Nov 08, 2020 |
| Dell          | Inspiron 5370               | Notebook    | [a7ffc4fdf0](https://linux-hardware.org/?probe=a7ffc4fdf0) | Nov 07, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [9f2d169081](https://linux-hardware.org/?probe=9f2d169081) | Nov 06, 2020 |
| Acer          | Aspire V3-772               | Notebook    | [413786151e](https://linux-hardware.org/?probe=413786151e) | Oct 31, 2020 |
| HP            | ProBook 6470b               | Notebook    | [18f5fab938](https://linux-hardware.org/?probe=18f5fab938) | Oct 31, 2020 |
| ASUSTek       | V222GA                      | All in one  | [6792dcd0de](https://linux-hardware.org/?probe=6792dcd0de) | Oct 30, 2020 |
| iEi           | B202 V1.0                   | Desktop     | [ad705b0098](https://linux-hardware.org/?probe=ad705b0098) | Oct 29, 2020 |
| Dell          | Vostro 3580                 | Notebook    | [a0e40c6f16](https://linux-hardware.org/?probe=a0e40c6f16) | Oct 29, 2020 |
| ASUSTek       | X541NA                      | Notebook    | [a4497b52bb](https://linux-hardware.org/?probe=a4497b52bb) | Oct 28, 2020 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [4643cfe86d](https://linux-hardware.org/?probe=4643cfe86d) | Oct 27, 2020 |
| Lenovo        | ThinkPad qqqqS2E            | Notebook    | [da5ad20c60](https://linux-hardware.org/?probe=da5ad20c60) | Oct 27, 2020 |
| Dell          | Latitude 5480               | Notebook    | [4191db79b7](https://linux-hardware.org/?probe=4191db79b7) | Oct 25, 2020 |
| Toshiba       | Satellite S70-B             | Notebook    | [a6521e505a](https://linux-hardware.org/?probe=a6521e505a) | Oct 25, 2020 |
| Lenovo        | G50-80 80E5                 | Notebook    | [89f32e3856](https://linux-hardware.org/?probe=89f32e3856) | Oct 23, 2020 |
| ASUSTek       | N551VW                      | Notebook    | [76852e9990](https://linux-hardware.org/?probe=76852e9990) | Oct 22, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [74b57e7887](https://linux-hardware.org/?probe=74b57e7887) | Oct 21, 2020 |
| Packard Be... | imedia S2185                | Desktop     | [5fd02031d2](https://linux-hardware.org/?probe=5fd02031d2) | Oct 21, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [a1a02fe851](https://linux-hardware.org/?probe=a1a02fe851) | Oct 18, 2020 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [dd68c7b3f6](https://linux-hardware.org/?probe=dd68c7b3f6) | Oct 18, 2020 |
| Dell          | 0XHGV1 A00                  | Desktop     | [d1f3fe93be](https://linux-hardware.org/?probe=d1f3fe93be) | Oct 16, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [fdc8cb1b11](https://linux-hardware.org/?probe=fdc8cb1b11) | Oct 16, 2020 |
| Lenovo        | Yoga 2 11 20428             | Notebook    | [f5c8360ae3](https://linux-hardware.org/?probe=f5c8360ae3) | Oct 15, 2020 |
| Lenovo        | G50-80 80E5                 | Notebook    | [3f72e0309a](https://linux-hardware.org/?probe=3f72e0309a) | Oct 15, 2020 |
| ASUSTek       | P5GC-MX/1333                | Desktop     | [bfe71baced](https://linux-hardware.org/?probe=bfe71baced) | Oct 14, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [ba66ad5205](https://linux-hardware.org/?probe=ba66ad5205) | Oct 12, 2020 |
| Lenovo        | G570 20079                  | Notebook    | [5e14548b50](https://linux-hardware.org/?probe=5e14548b50) | Oct 12, 2020 |
| HP            | EliteBook 8560p             | Notebook    | [bbae413f9c](https://linux-hardware.org/?probe=bbae413f9c) | Oct 10, 2020 |
| ASUSTek       | K53U                        | Notebook    | [59444922e7](https://linux-hardware.org/?probe=59444922e7) | Oct 10, 2020 |
| ASUSTek       | K53U                        | Notebook    | [5c5b3815f7](https://linux-hardware.org/?probe=5c5b3815f7) | Oct 10, 2020 |
| Lenovo        | IdeaPad Y510P 20217         | Notebook    | [25fb29514f](https://linux-hardware.org/?probe=25fb29514f) | Oct 10, 2020 |
| Gigabyte      | PH67A-D3-B3                 | Desktop     | [61b3d8f426](https://linux-hardware.org/?probe=61b3d8f426) | Oct 09, 2020 |
| ASRock        | AB350M Pro4                 | Desktop     | [b178beac46](https://linux-hardware.org/?probe=b178beac46) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [8677a1b95c](https://linux-hardware.org/?probe=8677a1b95c) | Oct 07, 2020 |
| Lenovo        | ThinkPad W520 4284GN2       | Notebook    | [352bbb87fe](https://linux-hardware.org/?probe=352bbb87fe) | Oct 07, 2020 |
| Acer          | Aspire V3-571G              | Notebook    | [86c3c25832](https://linux-hardware.org/?probe=86c3c25832) | Oct 05, 2020 |
| ASUSTek       | P10S-V Series               | Desktop     | [ab381f976a](https://linux-hardware.org/?probe=ab381f976a) | Oct 04, 2020 |
| HP            | 250 G3                      | Notebook    | [ab75ccc4f8](https://linux-hardware.org/?probe=ab75ccc4f8) | Oct 02, 2020 |
| Dell          | Inspiron 3583               | Notebook    | [419cd76be1](https://linux-hardware.org/?probe=419cd76be1) | Oct 01, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [18199ffdaf](https://linux-hardware.org/?probe=18199ffdaf) | Sep 30, 2020 |
| Gigabyte      | P35-S3G                     | Desktop     | [c55cb88668](https://linux-hardware.org/?probe=c55cb88668) | Sep 30, 2020 |
| Dell          | G7 7588                     | Notebook    | [0d38edaf0c](https://linux-hardware.org/?probe=0d38edaf0c) | Sep 28, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [33020554c0](https://linux-hardware.org/?probe=33020554c0) | Sep 27, 2020 |
| Acer          | EG43M                       | Desktop     | [f70bf9f37f](https://linux-hardware.org/?probe=f70bf9f37f) | Sep 26, 2020 |
| Acer          | EG43M                       | Desktop     | [93fe9368c0](https://linux-hardware.org/?probe=93fe9368c0) | Sep 26, 2020 |
| HP            | EliteBook 8470p             | Notebook    | [e330dd752b](https://linux-hardware.org/?probe=e330dd752b) | Sep 23, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [96d1d6229b](https://linux-hardware.org/?probe=96d1d6229b) | Sep 23, 2020 |
| Acer          | Nitro AN515-44              | Notebook    | [18afb6b15d](https://linux-hardware.org/?probe=18afb6b15d) | Sep 22, 2020 |
| Acer          | Nitro AN515-44              | Notebook    | [c078093e0f](https://linux-hardware.org/?probe=c078093e0f) | Sep 22, 2020 |
| HP            | Compaq tc4400 (RH489ES#A... | Notebook    | [c0305edfae](https://linux-hardware.org/?probe=c0305edfae) | Sep 20, 2020 |
| ASUSTek       | K50C                        | Notebook    | [d4e11f2289](https://linux-hardware.org/?probe=d4e11f2289) | Sep 18, 2020 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [5a7c64ce22](https://linux-hardware.org/?probe=5a7c64ce22) | Sep 15, 2020 |
| ASUSTek       | Berkeley                    | Desktop     | [db3c1d0348](https://linux-hardware.org/?probe=db3c1d0348) | Sep 13, 2020 |
| Intel         | NUC8BEB J72692-309          | Mini pc     | [7ab72b120c](https://linux-hardware.org/?probe=7ab72b120c) | Sep 12, 2020 |
| Acer          | Extensa 5630                | Notebook    | [9040e8e334](https://linux-hardware.org/?probe=9040e8e334) | Sep 12, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [a66f1b519a](https://linux-hardware.org/?probe=a66f1b519a) | Sep 10, 2020 |
| HP            | 250 G3                      | Notebook    | [9367a839a5](https://linux-hardware.org/?probe=9367a839a5) | Sep 09, 2020 |
| ASUSTek       | TUF Z370-PRO GAMING         | Desktop     | [fd2b790572](https://linux-hardware.org/?probe=fd2b790572) | Sep 09, 2020 |
| Shuttle       | FH81                        | Desktop     | [f7d3c868f1](https://linux-hardware.org/?probe=f7d3c868f1) | Sep 07, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c2a66820da](https://linux-hardware.org/?probe=c2a66820da) | Sep 06, 2020 |
| HP            | 255 G2                      | Notebook    | [5d06b6eeff](https://linux-hardware.org/?probe=5d06b6eeff) | Sep 04, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [bc5ee009b9](https://linux-hardware.org/?probe=bc5ee009b9) | Aug 29, 2020 |
| Lenovo        | ThinkPad X250 20CLS2YH00    | Notebook    | [cee4231640](https://linux-hardware.org/?probe=cee4231640) | Aug 29, 2020 |
| Fujitsu       | LIFEBOOK E752               | Notebook    | [9820c3c8bd](https://linux-hardware.org/?probe=9820c3c8bd) | Aug 28, 2020 |
| HP            | 0AA4h                       | Desktop     | [e1d187b146](https://linux-hardware.org/?probe=e1d187b146) | Aug 24, 2020 |
| Dell          | Precision M4800             | Notebook    | [4765bc9ec2](https://linux-hardware.org/?probe=4765bc9ec2) | Aug 19, 2020 |
| Dell          | Precision M4800             | Notebook    | [eee5b97967](https://linux-hardware.org/?probe=eee5b97967) | Aug 19, 2020 |
| HP            | 250 G3                      | Notebook    | [ff5c3ce273](https://linux-hardware.org/?probe=ff5c3ce273) | Aug 19, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [bf7ae9d5bf](https://linux-hardware.org/?probe=bf7ae9d5bf) | Aug 19, 2020 |
| HP            | 250 G3                      | Notebook    | [01f2866b5c](https://linux-hardware.org/?probe=01f2866b5c) | Aug 18, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [1619b6bb6c](https://linux-hardware.org/?probe=1619b6bb6c) | Aug 18, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [65cf550e5a](https://linux-hardware.org/?probe=65cf550e5a) | Aug 16, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [eab5f0ec38](https://linux-hardware.org/?probe=eab5f0ec38) | Aug 10, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [b636cd4fc2](https://linux-hardware.org/?probe=b636cd4fc2) | Aug 10, 2020 |
| Lenovo        | Board                       | Desktop     | [2f13897020](https://linux-hardware.org/?probe=2f13897020) | Aug 06, 2020 |
| HP            | 1632                        | Desktop     | [051549bbcd](https://linux-hardware.org/?probe=051549bbcd) | Aug 03, 2020 |
| HP            | 1496                        | Desktop     | [814a9396ee](https://linux-hardware.org/?probe=814a9396ee) | Aug 01, 2020 |
| ASUSTek       | A8N-VM CSM                  | Desktop     | [d6af935ba5](https://linux-hardware.org/?probe=d6af935ba5) | Jul 30, 2020 |
| ASUSTek       | X99-PRO                     | Desktop     | [ec4e8d2f6b](https://linux-hardware.org/?probe=ec4e8d2f6b) | Jul 30, 2020 |
| ASRock        | ConRoe945PL-GLAN            | Desktop     | [006d3a68b4](https://linux-hardware.org/?probe=006d3a68b4) | Jul 30, 2020 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [18c07b157f](https://linux-hardware.org/?probe=18c07b157f) | Jul 29, 2020 |
| Lenovo        | ThinkPad T495s 20QKS0SD0... | Notebook    | [8051286600](https://linux-hardware.org/?probe=8051286600) | Jul 29, 2020 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [f8c44dc8be](https://linux-hardware.org/?probe=f8c44dc8be) | Jul 29, 2020 |
| Gigabyte      | 990XA-UD3                   | Desktop     | [974c9ebd9c](https://linux-hardware.org/?probe=974c9ebd9c) | Jul 26, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [511636781f](https://linux-hardware.org/?probe=511636781f) | Jul 25, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [06120056c3](https://linux-hardware.org/?probe=06120056c3) | Jul 25, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [2afa9387d5](https://linux-hardware.org/?probe=2afa9387d5) | Jul 25, 2020 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [8ced06cd1f](https://linux-hardware.org/?probe=8ced06cd1f) | Jul 25, 2020 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [e8d593715c](https://linux-hardware.org/?probe=e8d593715c) | Jul 25, 2020 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [7b8022aa05](https://linux-hardware.org/?probe=7b8022aa05) | Jul 23, 2020 |
| Lenovo        | IdeaPad S540-14IML 81NF     | Notebook    | [42fc06b0e4](https://linux-hardware.org/?probe=42fc06b0e4) | Jul 23, 2020 |
| Lenovo        | Board                       | Desktop     | [f25b0e7108](https://linux-hardware.org/?probe=f25b0e7108) | Jul 19, 2020 |
| Foxconn       | 2A8C                        | Desktop     | [1de3848a94](https://linux-hardware.org/?probe=1de3848a94) | Jul 19, 2020 |
| Packard Be... | DOTS E2                     | Notebook    | [223cceb869](https://linux-hardware.org/?probe=223cceb869) | Jul 19, 2020 |
| Packard Be... | DOTS E2                     | Notebook    | [699033745c](https://linux-hardware.org/?probe=699033745c) | Jul 19, 2020 |
| Acer          | E5-575G                     | Notebook    | [9fb1e1bee4](https://linux-hardware.org/?probe=9fb1e1bee4) | Jul 18, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [ee5e7f9151](https://linux-hardware.org/?probe=ee5e7f9151) | Jul 18, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [968247c419](https://linux-hardware.org/?probe=968247c419) | Jul 17, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2298274454](https://linux-hardware.org/?probe=2298274454) | Jul 17, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c1fb882fc5](https://linux-hardware.org/?probe=c1fb882fc5) | Jul 17, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [2f5df8729a](https://linux-hardware.org/?probe=2f5df8729a) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [6801725bae](https://linux-hardware.org/?probe=6801725bae) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [7319f8f1b3](https://linux-hardware.org/?probe=7319f8f1b3) | Jul 17, 2020 |
| HP            | 255 G2                      | Notebook    | [aa15d52271](https://linux-hardware.org/?probe=aa15d52271) | Jul 16, 2020 |
| HP            | 255 G2                      | Notebook    | [d1dea15553](https://linux-hardware.org/?probe=d1dea15553) | Jul 16, 2020 |
| Lenovo        | ThinkPad T15 Gen 1 20S7S... | Notebook    | [498a1fee5c](https://linux-hardware.org/?probe=498a1fee5c) | Jul 14, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [ac0d845ddb](https://linux-hardware.org/?probe=ac0d845ddb) | Jul 13, 2020 |
| ASUSTek       | X510UQR                     | Notebook    | [54f20878cf](https://linux-hardware.org/?probe=54f20878cf) | Jul 12, 2020 |
| MSI           | B350 TOMAHAWK               | Desktop     | [7387ae682a](https://linux-hardware.org/?probe=7387ae682a) | Jul 10, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [4ce82f5616](https://linux-hardware.org/?probe=4ce82f5616) | Jul 09, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [31b8493ac2](https://linux-hardware.org/?probe=31b8493ac2) | Jul 08, 2020 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [46702d58d5](https://linux-hardware.org/?probe=46702d58d5) | Jul 04, 2020 |
| Lenovo        | ThinkPad T590 20N5S2BP00    | Notebook    | [16f6fb2756](https://linux-hardware.org/?probe=16f6fb2756) | Jul 02, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [6a4b08f649](https://linux-hardware.org/?probe=6a4b08f649) | Jul 01, 2020 |
| Fujitsu Si... | AMILO L Series              | Notebook    | [33762202ef](https://linux-hardware.org/?probe=33762202ef) | Jul 01, 2020 |
| MSI           | B150 GAMING M3              | Desktop     | [4e837b8686](https://linux-hardware.org/?probe=4e837b8686) | Jul 01, 2020 |
| Lenovo        | Legion Y530-15ICH-1060 8... | Notebook    | [5aef8629ba](https://linux-hardware.org/?probe=5aef8629ba) | Jun 30, 2020 |
| Intel         | DX58SO2 AAG10925-205        | Desktop     | [2e4066d769](https://linux-hardware.org/?probe=2e4066d769) | Jun 30, 2020 |
| Lenovo        | IdeaPad S340-15IIL 81WL     | Notebook    | [9b54e3f16c](https://linux-hardware.org/?probe=9b54e3f16c) | Jun 30, 2020 |
| ASUSTek       | P8H61-I LX R2.0/RM/SI       | Desktop     | [a5f5e5572b](https://linux-hardware.org/?probe=a5f5e5572b) | Jun 30, 2020 |
| Dell          | Latitude E6410              | Notebook    | [79c1af2581](https://linux-hardware.org/?probe=79c1af2581) | Jun 29, 2020 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [078efbe676](https://linux-hardware.org/?probe=078efbe676) | Jun 29, 2020 |
| ASRock        | 960GM-GS3 FX                | Desktop     | [a79843ff43](https://linux-hardware.org/?probe=a79843ff43) | Jun 27, 2020 |
| Acer          | Swift SF314-57G             | Notebook    | [9bd6123d76](https://linux-hardware.org/?probe=9bd6123d76) | Jun 25, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [5d93931a70](https://linux-hardware.org/?probe=5d93931a70) | Jun 21, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [6d318a0db0](https://linux-hardware.org/?probe=6d318a0db0) | Jun 21, 2020 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [f2f35bedba](https://linux-hardware.org/?probe=f2f35bedba) | Jun 20, 2020 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [5e0e1d5516](https://linux-hardware.org/?probe=5e0e1d5516) | Jun 20, 2020 |
| Toshiba       | Satellite C55-A-1HL         | Notebook    | [c6d6bb3ba1](https://linux-hardware.org/?probe=c6d6bb3ba1) | Jun 18, 2020 |
| Toshiba       | Satellite C55-A-1HL         | Notebook    | [d16857f500](https://linux-hardware.org/?probe=d16857f500) | Jun 17, 2020 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [22ca9e31e5](https://linux-hardware.org/?probe=22ca9e31e5) | Jun 15, 2020 |
| ASRock        | H110M-HDV                   | Desktop     | [9a04c60269](https://linux-hardware.org/?probe=9a04c60269) | Jun 15, 2020 |
| ASUSTek       | X99-PRO                     | Desktop     | [1b58de62cc](https://linux-hardware.org/?probe=1b58de62cc) | Jun 14, 2020 |
| ASUSTek       | X99-PRO                     | Desktop     | [5a279c96a5](https://linux-hardware.org/?probe=5a279c96a5) | Jun 13, 2020 |
| Lenovo        | ThinkPad T470s 20HF004UM... | Notebook    | [7a3bd1d810](https://linux-hardware.org/?probe=7a3bd1d810) | Jun 10, 2020 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [1e9b7bd7d0](https://linux-hardware.org/?probe=1e9b7bd7d0) | Jun 09, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [65f523b6f2](https://linux-hardware.org/?probe=65f523b6f2) | Jun 06, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [c8ddcb0ec8](https://linux-hardware.org/?probe=c8ddcb0ec8) | Jun 06, 2020 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [d23bc12452](https://linux-hardware.org/?probe=d23bc12452) | Jun 04, 2020 |
| ASRock        | 970M Pro3                   | Desktop     | [f40c51e426](https://linux-hardware.org/?probe=f40c51e426) | Jun 03, 2020 |
| Gigabyte      | Z170X-Gaming 7              | Desktop     | [efa59eef1c](https://linux-hardware.org/?probe=efa59eef1c) | Jun 01, 2020 |
| HP            | 250 G3                      | Notebook    | [99be1919b2](https://linux-hardware.org/?probe=99be1919b2) | Jun 01, 2020 |
| Toshiba       | Satellite P300              | Notebook    | [8eb9fa72de](https://linux-hardware.org/?probe=8eb9fa72de) | May 31, 2020 |
| Lenovo        | G505 20240                  | Notebook    | [6860a03dd0](https://linux-hardware.org/?probe=6860a03dd0) | May 31, 2020 |
| HP            | 250 G3                      | Notebook    | [fe55c5cec9](https://linux-hardware.org/?probe=fe55c5cec9) | May 31, 2020 |
| HP            | 250 G3                      | Notebook    | [a4e1d1f904](https://linux-hardware.org/?probe=a4e1d1f904) | May 29, 2020 |
| Lenovo        | ThinkPad T495 20NJ0010BM    | Notebook    | [6974ca5761](https://linux-hardware.org/?probe=6974ca5761) | May 29, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [edcc0b8c05](https://linux-hardware.org/?probe=edcc0b8c05) | May 29, 2020 |
| ASUSTek       | X540LJ                      | Notebook    | [67a3981fe5](https://linux-hardware.org/?probe=67a3981fe5) | May 27, 2020 |
| Lenovo        | Board                       | Desktop     | [9c341d7259](https://linux-hardware.org/?probe=9c341d7259) | May 25, 2020 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [5bd26cbc33](https://linux-hardware.org/?probe=5bd26cbc33) | May 24, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [e2ba0ca3f4](https://linux-hardware.org/?probe=e2ba0ca3f4) | May 22, 2020 |
| ASUSTek       | X705UNR                     | Notebook    | [015957a390](https://linux-hardware.org/?probe=015957a390) | May 22, 2020 |
| ASUSTek       | M2N-MX SE Plus              | Desktop     | [34d65fc5b5](https://linux-hardware.org/?probe=34d65fc5b5) | May 22, 2020 |
| HP            | ProBook 6460b               | Notebook    | [babf988605](https://linux-hardware.org/?probe=babf988605) | May 22, 2020 |
| Lenovo        | IdeaPad 120S-14IAP 81A5     | Notebook    | [29131d3d86](https://linux-hardware.org/?probe=29131d3d86) | May 21, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [a39e33b1f4](https://linux-hardware.org/?probe=a39e33b1f4) | May 20, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [4f773edbaa](https://linux-hardware.org/?probe=4f773edbaa) | May 20, 2020 |
| HP            | 1496                        | Desktop     | [64b345823f](https://linux-hardware.org/?probe=64b345823f) | May 18, 2020 |
| Lenovo        | Board                       | Desktop     | [5d67f4aace](https://linux-hardware.org/?probe=5d67f4aace) | May 16, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [33722345b4](https://linux-hardware.org/?probe=33722345b4) | May 13, 2020 |
| HP            | 255 G2                      | Notebook    | [ad9ef87735](https://linux-hardware.org/?probe=ad9ef87735) | May 13, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [f27a7b8301](https://linux-hardware.org/?probe=f27a7b8301) | May 13, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [88fc8f3bc8](https://linux-hardware.org/?probe=88fc8f3bc8) | May 13, 2020 |
| Gigabyte      | H97-Gaming 3                | Desktop     | [d4a5246eaa](https://linux-hardware.org/?probe=d4a5246eaa) | May 12, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [69d060d290](https://linux-hardware.org/?probe=69d060d290) | May 12, 2020 |
| Acer          | Aspire 5742G                | Notebook    | [2dec87937c](https://linux-hardware.org/?probe=2dec87937c) | May 12, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [715f4fa65b](https://linux-hardware.org/?probe=715f4fa65b) | May 12, 2020 |
| Lenovo        | Y520-15IKBN 80WK            | Notebook    | [96cd96c818](https://linux-hardware.org/?probe=96cd96c818) | May 12, 2020 |
| HP            | ProBook 4710s               | Notebook    | [b2680d0881](https://linux-hardware.org/?probe=b2680d0881) | May 11, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [f6bc1aa4bf](https://linux-hardware.org/?probe=f6bc1aa4bf) | May 11, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [6da190e95d](https://linux-hardware.org/?probe=6da190e95d) | May 10, 2020 |
| HP            | 255 G2                      | Notebook    | [ee5dcad518](https://linux-hardware.org/?probe=ee5dcad518) | May 10, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [050c997025](https://linux-hardware.org/?probe=050c997025) | May 08, 2020 |
| Dell          | Latitude 7490               | Notebook    | [94b949eb90](https://linux-hardware.org/?probe=94b949eb90) | May 08, 2020 |
| Acer          | E5-575G                     | Notebook    | [4de3c815fd](https://linux-hardware.org/?probe=4de3c815fd) | May 08, 2020 |
| HP            | EliteBook 820 G2            | Notebook    | [3b379abf6a](https://linux-hardware.org/?probe=3b379abf6a) | May 07, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [ee2382dc05](https://linux-hardware.org/?probe=ee2382dc05) | May 07, 2020 |
| HP            | EliteBook 840 G1            | Notebook    | [10d3d30341](https://linux-hardware.org/?probe=10d3d30341) | May 07, 2020 |
| HP            | 255 G2                      | Notebook    | [03808f75d6](https://linux-hardware.org/?probe=03808f75d6) | May 06, 2020 |
| HP            | 255 G2                      | Notebook    | [162f37494e](https://linux-hardware.org/?probe=162f37494e) | May 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [22dfb95582](https://linux-hardware.org/?probe=22dfb95582) | May 06, 2020 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [ea793cbae5](https://linux-hardware.org/?probe=ea793cbae5) | May 06, 2020 |
| Dell          | Latitude E4300              | Notebook    | [8b26d2727c](https://linux-hardware.org/?probe=8b26d2727c) | May 06, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [cbcdbbc816](https://linux-hardware.org/?probe=cbcdbbc816) | May 04, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [0e93fcc269](https://linux-hardware.org/?probe=0e93fcc269) | May 04, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [f000e16d13](https://linux-hardware.org/?probe=f000e16d13) | May 04, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [72e18e38ce](https://linux-hardware.org/?probe=72e18e38ce) | May 04, 2020 |
| HP            | Pavilion Notebook           | Notebook    | [35d925dbae](https://linux-hardware.org/?probe=35d925dbae) | May 04, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [02c7c61130](https://linux-hardware.org/?probe=02c7c61130) | May 03, 2020 |
| Dell          | Inspiron 7577               | Notebook    | [d987f6c242](https://linux-hardware.org/?probe=d987f6c242) | May 03, 2020 |
| AMI           | Aptio CRB                   | Mini pc     | [029da6ffcc](https://linux-hardware.org/?probe=029da6ffcc) | May 03, 2020 |
| Toshiba       | Satellite Radius 12 P20W... | Notebook    | [4f272f1c99](https://linux-hardware.org/?probe=4f272f1c99) | May 03, 2020 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [c3b3575e58](https://linux-hardware.org/?probe=c3b3575e58) | May 02, 2020 |
| ASUSTek       | G771JW                      | Notebook    | [77202c9853](https://linux-hardware.org/?probe=77202c9853) | May 02, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [f74dab71c3](https://linux-hardware.org/?probe=f74dab71c3) | May 01, 2020 |
| HP            | ProBook 450 G0              | Notebook    | [7ac5247653](https://linux-hardware.org/?probe=7ac5247653) | May 01, 2020 |
| MSI           | MS-7368                     | Desktop     | [090e6cd15c](https://linux-hardware.org/?probe=090e6cd15c) | May 01, 2020 |
| MSI           | MS-7368                     | Desktop     | [308c2e01f6](https://linux-hardware.org/?probe=308c2e01f6) | Apr 30, 2020 |
| ASUSTek       | M2N68-CM                    | Desktop     | [6f787e35a1](https://linux-hardware.org/?probe=6f787e35a1) | Apr 27, 2020 |
| Acer          | Aspire 3830G                | Notebook    | [1af95987d0](https://linux-hardware.org/?probe=1af95987d0) | Apr 26, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [7dceeca2dd](https://linux-hardware.org/?probe=7dceeca2dd) | Apr 24, 2020 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [2dde18f51f](https://linux-hardware.org/?probe=2dde18f51f) | Apr 24, 2020 |
| ASUSTek       | N551VW                      | Notebook    | [2d93805421](https://linux-hardware.org/?probe=2d93805421) | Apr 23, 2020 |
| ASUSTek       | N551VW                      | Notebook    | [155a39180a](https://linux-hardware.org/?probe=155a39180a) | Apr 23, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [28fa6e8b6e](https://linux-hardware.org/?probe=28fa6e8b6e) | Apr 22, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [73f401be06](https://linux-hardware.org/?probe=73f401be06) | Apr 22, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [d2038f31f4](https://linux-hardware.org/?probe=d2038f31f4) | Apr 21, 2020 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [562403e85f](https://linux-hardware.org/?probe=562403e85f) | Apr 21, 2020 |
| Gigabyte      | P85-D3                      | Desktop     | [5972095107](https://linux-hardware.org/?probe=5972095107) | Apr 21, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [ee479d0e5d](https://linux-hardware.org/?probe=ee479d0e5d) | Apr 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [a78b041d0c](https://linux-hardware.org/?probe=a78b041d0c) | Apr 20, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [fbfdc3b5e3](https://linux-hardware.org/?probe=fbfdc3b5e3) | Apr 20, 2020 |
| Sony          | VPCEB4L1E                   | Notebook    | [f1a3807b60](https://linux-hardware.org/?probe=f1a3807b60) | Apr 20, 2020 |
| Compal        | HEL80I                      | Notebook    | [41fd098e10](https://linux-hardware.org/?probe=41fd098e10) | Apr 20, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [00cedd86e4](https://linux-hardware.org/?probe=00cedd86e4) | Apr 19, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [6b8e555d43](https://linux-hardware.org/?probe=6b8e555d43) | Apr 18, 2020 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [f3b92c302c](https://linux-hardware.org/?probe=f3b92c302c) | Apr 16, 2020 |
| Dell          | Inspiron 3580               | Notebook    | [d1e3e7d629](https://linux-hardware.org/?probe=d1e3e7d629) | Apr 16, 2020 |
| Dell          | Inspiron 3580               | Notebook    | [a9b4abdd56](https://linux-hardware.org/?probe=a9b4abdd56) | Apr 16, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [43f93a43d6](https://linux-hardware.org/?probe=43f93a43d6) | Apr 16, 2020 |
| Dell          | Inspiron N5110              | Notebook    | [20b4b0a6ad](https://linux-hardware.org/?probe=20b4b0a6ad) | Apr 16, 2020 |
| Dell          | 08NPPY A00                  | Desktop     | [895a4ce7cb](https://linux-hardware.org/?probe=895a4ce7cb) | Apr 15, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [3aabad96db](https://linux-hardware.org/?probe=3aabad96db) | Apr 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [23ab66b67b](https://linux-hardware.org/?probe=23ab66b67b) | Apr 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [02d576419f](https://linux-hardware.org/?probe=02d576419f) | Apr 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [28e7706163](https://linux-hardware.org/?probe=28e7706163) | Apr 14, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [5fc32fd27b](https://linux-hardware.org/?probe=5fc32fd27b) | Apr 12, 2020 |
| Shuttle       | FH81                        | Desktop     | [61209bcee3](https://linux-hardware.org/?probe=61209bcee3) | Apr 11, 2020 |
| ASRock        | 890GX Extreme3              | Desktop     | [2f70e1ae2c](https://linux-hardware.org/?probe=2f70e1ae2c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [e727c9003c](https://linux-hardware.org/?probe=e727c9003c) | Apr 10, 2020 |
| Acer          | Aspire E1-570G              | Notebook    | [fe1196d306](https://linux-hardware.org/?probe=fe1196d306) | Apr 09, 2020 |
| Dell          | Inspiron 3521               | Notebook    | [53b2f1863a](https://linux-hardware.org/?probe=53b2f1863a) | Apr 07, 2020 |
| ASRock        | 970 Extreme3                | Desktop     | [679cdbade2](https://linux-hardware.org/?probe=679cdbade2) | Apr 05, 2020 |
| HP            | 0A64h                       | Desktop     | [79aa6d6301](https://linux-hardware.org/?probe=79aa6d6301) | Apr 05, 2020 |
| Acer          | Nitro AN515-43              | Notebook    | [6b0efa548b](https://linux-hardware.org/?probe=6b0efa548b) | Apr 04, 2020 |
| ASUSTek       | P5K                         | Desktop     | [60860911b6](https://linux-hardware.org/?probe=60860911b6) | Apr 03, 2020 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [a7f7938a12](https://linux-hardware.org/?probe=a7f7938a12) | Apr 02, 2020 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [4db785101b](https://linux-hardware.org/?probe=4db785101b) | Apr 01, 2020 |
| HP            | ProBook 4540s               | Notebook    | [e3c52f3d96](https://linux-hardware.org/?probe=e3c52f3d96) | Apr 01, 2020 |
| HP            | ProBook 4540s               | Notebook    | [387bbd9c5b](https://linux-hardware.org/?probe=387bbd9c5b) | Apr 01, 2020 |
| HP            | ProBook 4540s               | Notebook    | [65b1ee39af](https://linux-hardware.org/?probe=65b1ee39af) | Apr 01, 2020 |
| Dell          | 0DR845                      | Desktop     | [c1582b3202](https://linux-hardware.org/?probe=c1582b3202) | Apr 01, 2020 |
| HP            | ProBook 4540s               | Notebook    | [179474f8a7](https://linux-hardware.org/?probe=179474f8a7) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | Notebook    | [cbc70bfce5](https://linux-hardware.org/?probe=cbc70bfce5) | Apr 01, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | Notebook    | [d018206f33](https://linux-hardware.org/?probe=d018206f33) | Mar 31, 2020 |
| HP            | EliteBook 8560w             | Notebook    | [5038965b3b](https://linux-hardware.org/?probe=5038965b3b) | Mar 30, 2020 |
| HP            | ProBook 4540s               | Notebook    | [cdad1b60d2](https://linux-hardware.org/?probe=cdad1b60d2) | Mar 30, 2020 |
| HP            | ProBook 4540s               | Notebook    | [6b9b373a1f](https://linux-hardware.org/?probe=6b9b373a1f) | Mar 30, 2020 |
| Lenovo        | ThinkPad E480 20KN005CBM    | Notebook    | [99865fe49f](https://linux-hardware.org/?probe=99865fe49f) | Mar 29, 2020 |
| ASUSTek       | P5K SE                      | Desktop     | [8492263fc0](https://linux-hardware.org/?probe=8492263fc0) | Mar 29, 2020 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [c7eda36111](https://linux-hardware.org/?probe=c7eda36111) | Mar 28, 2020 |
| Acer          | Predator G3-572             | Notebook    | [9434c59ae1](https://linux-hardware.org/?probe=9434c59ae1) | Mar 28, 2020 |
| Acer          | Predator G3-572             | Notebook    | [11828122f2](https://linux-hardware.org/?probe=11828122f2) | Mar 28, 2020 |
| ASUSTek       | TUF Gaming FX505GM_FX505... | Notebook    | [edf4388f6a](https://linux-hardware.org/?probe=edf4388f6a) | Mar 26, 2020 |
| ASUSTek       | P5K SE                      | Desktop     | [fd766dda01](https://linux-hardware.org/?probe=fd766dda01) | Mar 26, 2020 |
| HP            | 620                         | Notebook    | [633afcbbef](https://linux-hardware.org/?probe=633afcbbef) | Mar 25, 2020 |
| HP            | 620                         | Notebook    | [8487590fa2](https://linux-hardware.org/?probe=8487590fa2) | Mar 25, 2020 |
| ASRock        | G41M-S3                     | Desktop     | [19c0625a28](https://linux-hardware.org/?probe=19c0625a28) | Mar 24, 2020 |
| HP            | 250 G7 Notebook PC          | Notebook    | [c63e1ec4fd](https://linux-hardware.org/?probe=c63e1ec4fd) | Mar 23, 2020 |
| ASUSTek       | M4A3000E                    | Desktop     | [76ec7cf71b](https://linux-hardware.org/?probe=76ec7cf71b) | Mar 23, 2020 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [0d2e81fb9b](https://linux-hardware.org/?probe=0d2e81fb9b) | Mar 20, 2020 |
| ASUSTek       | P5K                         | Desktop     | [64c435a307](https://linux-hardware.org/?probe=64c435a307) | Mar 17, 2020 |
| ASUSTek       | P5K                         | Desktop     | [d532983f25](https://linux-hardware.org/?probe=d532983f25) | Mar 17, 2020 |
| Toshiba       | Satellite L50-C             | Notebook    | [b343a21e42](https://linux-hardware.org/?probe=b343a21e42) | Mar 17, 2020 |
| Lenovo        | ThinkPad T470p 20J6S0A30... | Notebook    | [b02f5ffeeb](https://linux-hardware.org/?probe=b02f5ffeeb) | Mar 17, 2020 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [14544480a5](https://linux-hardware.org/?probe=14544480a5) | Mar 16, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [ccc20cb679](https://linux-hardware.org/?probe=ccc20cb679) | Mar 16, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [7b2e2dc41d](https://linux-hardware.org/?probe=7b2e2dc41d) | Mar 15, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [252c5a9ab3](https://linux-hardware.org/?probe=252c5a9ab3) | Mar 15, 2020 |
| ASUSTek       | GL553VE                     | Notebook    | [810b827dfe](https://linux-hardware.org/?probe=810b827dfe) | Mar 15, 2020 |
| Lenovo        | ThinkPad E480 20KN004TBM    | Notebook    | [13768f8615](https://linux-hardware.org/?probe=13768f8615) | Mar 14, 2020 |
| ASRock        | X470 Taichi Ultimate        | Desktop     | [53d0f3f5fc](https://linux-hardware.org/?probe=53d0f3f5fc) | Mar 13, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [4c0f104328](https://linux-hardware.org/?probe=4c0f104328) | Mar 11, 2020 |
| Lenovo        | ThinkPad X1 Carbon 3rd 2... | Notebook    | [4587e48bf4](https://linux-hardware.org/?probe=4587e48bf4) | Mar 11, 2020 |
| Unknown       | K8NF6G-VSTA                 | Desktop     | [b4f0d62c45](https://linux-hardware.org/?probe=b4f0d62c45) | Mar 08, 2020 |
| Unknown       | K8NF6G-VSTA                 | Desktop     | [08691dfde3](https://linux-hardware.org/?probe=08691dfde3) | Mar 08, 2020 |
| ASRock        | 890FX Deluxe4               | Desktop     | [391c431de9](https://linux-hardware.org/?probe=391c431de9) | Mar 05, 2020 |
| HP            | Unknown                     | Notebook    | [453696ff5e](https://linux-hardware.org/?probe=453696ff5e) | Mar 04, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [5b7e72604e](https://linux-hardware.org/?probe=5b7e72604e) | Mar 04, 2020 |
| Dell          | G3 3579                     | Notebook    | [12a87598d6](https://linux-hardware.org/?probe=12a87598d6) | Mar 02, 2020 |
| ASUSTek       | SABERTOOTH 990FX            | Desktop     | [4c1a03683b](https://linux-hardware.org/?probe=4c1a03683b) | Mar 01, 2020 |
| Intel         | DQ57TM AAE92694-402         | Desktop     | [e82b578dad](https://linux-hardware.org/?probe=e82b578dad) | Feb 28, 2020 |
| ASRock        | H81M-ITX/WiFi               | Desktop     | [a513552c14](https://linux-hardware.org/?probe=a513552c14) | Feb 27, 2020 |
| HP            | Unknown                     | Notebook    | [55a996ba66](https://linux-hardware.org/?probe=55a996ba66) | Feb 26, 2020 |
| HP            | Unknown                     | Notebook    | [f8a7212a74](https://linux-hardware.org/?probe=f8a7212a74) | Feb 26, 2020 |
| Acer          | Aspire 5738                 | Notebook    | [d008370d87](https://linux-hardware.org/?probe=d008370d87) | Feb 24, 2020 |
| Fujitsu       | D3313-F1 S26361-D3313-F1    | Desktop     | [455dbd81e1](https://linux-hardware.org/?probe=455dbd81e1) | Feb 22, 2020 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [b09f7bb137](https://linux-hardware.org/?probe=b09f7bb137) | Feb 22, 2020 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [9c5def065e](https://linux-hardware.org/?probe=9c5def065e) | Feb 22, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [8231b2fe22](https://linux-hardware.org/?probe=8231b2fe22) | Feb 18, 2020 |
| Dell          | Latitude 5401               | Notebook    | [76f6ff2608](https://linux-hardware.org/?probe=76f6ff2608) | Feb 16, 2020 |
| HP            | Pro Tablet 610 G1           | Notebook    | [4df7386234](https://linux-hardware.org/?probe=4df7386234) | Feb 16, 2020 |
| HP            | Pro Tablet 610 G1           | Notebook    | [d8f25b08f2](https://linux-hardware.org/?probe=d8f25b08f2) | Feb 16, 2020 |
| Lenovo        | ThinkPad T560 20FJS1YD00    | Notebook    | [b379bf7743](https://linux-hardware.org/?probe=b379bf7743) | Feb 15, 2020 |
| Acer          | Aspire 5541                 | Notebook    | [6bf6d1c16b](https://linux-hardware.org/?probe=6bf6d1c16b) | Feb 15, 2020 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [60281c26f1](https://linux-hardware.org/?probe=60281c26f1) | Feb 14, 2020 |
| Lenovo        | ThinkBook 13s-IML 20RR      | Notebook    | [3977fb1ddb](https://linux-hardware.org/?probe=3977fb1ddb) | Feb 12, 2020 |
| ASUSTek       | A88XM-E                     | Desktop     | [ea21444fa7](https://linux-hardware.org/?probe=ea21444fa7) | Feb 11, 2020 |
| ASUSTek       | X501A                       | Notebook    | [9e5a342bac](https://linux-hardware.org/?probe=9e5a342bac) | Feb 10, 2020 |
| ASUSTek       | A88XM-E                     | Desktop     | [984a9c83fd](https://linux-hardware.org/?probe=984a9c83fd) | Feb 10, 2020 |
| HP            | 0A64h                       | Desktop     | [23d32db8b9](https://linux-hardware.org/?probe=23d32db8b9) | Feb 10, 2020 |
| HP            | 0A64h                       | Desktop     | [ded9dbdb6b](https://linux-hardware.org/?probe=ded9dbdb6b) | Feb 07, 2020 |
| HP            | 0A64h                       | Desktop     | [eed7c64698](https://linux-hardware.org/?probe=eed7c64698) | Feb 06, 2020 |
| Dell          | Inspiron 3584               | Notebook    | [c080de1bad](https://linux-hardware.org/?probe=c080de1bad) | Feb 03, 2020 |
| Toshiba       | Satellite L40               | Notebook    | [75079b3cba](https://linux-hardware.org/?probe=75079b3cba) | Jan 29, 2020 |
| Dell          | Inspiron 3580               | Notebook    | [b3e528be2c](https://linux-hardware.org/?probe=b3e528be2c) | Jan 29, 2020 |
| Dell          | Inspiron 3580               | Notebook    | [8db2dfbc60](https://linux-hardware.org/?probe=8db2dfbc60) | Jan 29, 2020 |
| ASUSTek       | M2N68-CM                    | Desktop     | [201ca7dd72](https://linux-hardware.org/?probe=201ca7dd72) | Jan 28, 2020 |
| Lenovo        | ThinkPad X220 4291B24       | Notebook    | [ce7dd499a5](https://linux-hardware.org/?probe=ce7dd499a5) | Jan 24, 2020 |
| Toshiba       | Satellite L300              | Notebook    | [f5faa63427](https://linux-hardware.org/?probe=f5faa63427) | Jan 12, 2020 |
| ASUSTek       | K55VM                       | Notebook    | [c1595f145d](https://linux-hardware.org/?probe=c1595f145d) | Jan 11, 2020 |
| ASRock        | AB350M Pro4 R2.0            | Desktop     | [11e945005f](https://linux-hardware.org/?probe=11e945005f) | Jan 08, 2020 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [6056ef2c40](https://linux-hardware.org/?probe=6056ef2c40) | Jan 07, 2020 |
| Dell          | Inspiron 5520               | Notebook    | [601d03392f](https://linux-hardware.org/?probe=601d03392f) | Jan 05, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [3f4d79ea3b](https://linux-hardware.org/?probe=3f4d79ea3b) | Jan 03, 2020 |
| Lenovo        | Yoga S740-14IIL 81RS        | Notebook    | [aa34232c5a](https://linux-hardware.org/?probe=aa34232c5a) | Jan 01, 2020 |
| ASUSTek       | X540NV                      | Notebook    | [6bca5f0ae4](https://linux-hardware.org/?probe=6bca5f0ae4) | Jan 01, 2020 |
| Lenovo        | ThinkPad T420 4236A87       | Notebook    | [353a1db8ac](https://linux-hardware.org/?probe=353a1db8ac) | Dec 31, 2019 |
| TUXEDO        | Unknown                     | Notebook    | [8393427822](https://linux-hardware.org/?probe=8393427822) | Dec 27, 2019 |
| HP            | 530 Notebook PC(KP479AA#... | Notebook    | [3e6684e155](https://linux-hardware.org/?probe=3e6684e155) | Dec 27, 2019 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [b8c562a7e5](https://linux-hardware.org/?probe=b8c562a7e5) | Dec 23, 2019 |
| ASUSTek       | X541NA                      | Notebook    | [f885d0ee5f](https://linux-hardware.org/?probe=f885d0ee5f) | Dec 23, 2019 |
| Dell          | Inspiron 5482               | Notebook    | [85bb9ecf3b](https://linux-hardware.org/?probe=85bb9ecf3b) | Dec 20, 2019 |
| Acer          | Switch SA5-271              | Tablet      | [2d71938fc4](https://linux-hardware.org/?probe=2d71938fc4) | Dec 20, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [274eea3275](https://linux-hardware.org/?probe=274eea3275) | Dec 20, 2019 |
| Lenovo        | B51-30 80LK                 | Notebook    | [32d296fee0](https://linux-hardware.org/?probe=32d296fee0) | Dec 19, 2019 |
| Foxconn       | A55MX                       | Desktop     | [05c6b7995d](https://linux-hardware.org/?probe=05c6b7995d) | Dec 19, 2019 |
| Lenovo        | Board                       | Desktop     | [3eb7eb388c](https://linux-hardware.org/?probe=3eb7eb388c) | Dec 17, 2019 |
| Lenovo        | Board                       | Desktop     | [aaa8d34fff](https://linux-hardware.org/?probe=aaa8d34fff) | Dec 17, 2019 |
| ASUSTek       | H81M-PLUS                   | Desktop     | [6e09a0e0aa](https://linux-hardware.org/?probe=6e09a0e0aa) | Dec 16, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [030c06dbf0](https://linux-hardware.org/?probe=030c06dbf0) | Dec 15, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [893a9b3000](https://linux-hardware.org/?probe=893a9b3000) | Dec 14, 2019 |
| Dell          | Inspiron N5010              | Notebook    | [d5fec65df9](https://linux-hardware.org/?probe=d5fec65df9) | Dec 13, 2019 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [0a74735da6](https://linux-hardware.org/?probe=0a74735da6) | Dec 12, 2019 |
| MSI           | GS65 Stealth Thin 8RE       | Notebook    | [a9a218f5dd](https://linux-hardware.org/?probe=a9a218f5dd) | Dec 06, 2019 |
| Dell          | Studio 1747                 | Notebook    | [e572489472](https://linux-hardware.org/?probe=e572489472) | Dec 05, 2019 |
| Acer          | Aspire E5-572G              | Notebook    | [0c710c33f6](https://linux-hardware.org/?probe=0c710c33f6) | Dec 04, 2019 |
| Fujitsu Si... | AMILO Xi 3650               | Notebook    | [87afd7dd02](https://linux-hardware.org/?probe=87afd7dd02) | Dec 04, 2019 |
| Dell          | Studio 1747                 | Notebook    | [2daf1225e6](https://linux-hardware.org/?probe=2daf1225e6) | Dec 04, 2019 |
| Dell          | Studio 1747                 | Notebook    | [dfba5a95c8](https://linux-hardware.org/?probe=dfba5a95c8) | Dec 04, 2019 |
| Dell          | Studio 1747                 | Notebook    | [57919c3018](https://linux-hardware.org/?probe=57919c3018) | Dec 02, 2019 |
| Dell          | Studio 1747                 | Notebook    | [24d64d118b](https://linux-hardware.org/?probe=24d64d118b) | Dec 02, 2019 |
| HP            | 1850                        | Desktop     | [898f2b7197](https://linux-hardware.org/?probe=898f2b7197) | Dec 01, 2019 |
| ASRock        | B85M Pro4                   | Desktop     | [c6b09d560f](https://linux-hardware.org/?probe=c6b09d560f) | Nov 30, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [ade7b4eb87](https://linux-hardware.org/?probe=ade7b4eb87) | Nov 29, 2019 |
| ASUSTek       | H97-PLUS                    | Desktop     | [5b9bb1aedb](https://linux-hardware.org/?probe=5b9bb1aedb) | Nov 28, 2019 |
| ASUSTek       | H97-PLUS                    | Desktop     | [115ab4a8a7](https://linux-hardware.org/?probe=115ab4a8a7) | Nov 28, 2019 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [781e93ad34](https://linux-hardware.org/?probe=781e93ad34) | Nov 26, 2019 |
| ASRock        | H61M-GS                     | Desktop     | [b0cff72d0c](https://linux-hardware.org/?probe=b0cff72d0c) | Nov 24, 2019 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [9081234810](https://linux-hardware.org/?probe=9081234810) | Nov 22, 2019 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [f61b57f6fc](https://linux-hardware.org/?probe=f61b57f6fc) | Nov 22, 2019 |
| ASUSTek       | X505BP                      | Notebook    | [a881fdcf1b](https://linux-hardware.org/?probe=a881fdcf1b) | Nov 21, 2019 |
| iEi           | B202 V1.0                   | Desktop     | [16699afe19](https://linux-hardware.org/?probe=16699afe19) | Nov 13, 2019 |
| ASRock        | H61M-VG3                    | Desktop     | [6bc9ab22bf](https://linux-hardware.org/?probe=6bc9ab22bf) | Nov 11, 2019 |
| Gigabyte      | W348M                       | Notebook    | [0db51928b9](https://linux-hardware.org/?probe=0db51928b9) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [a2fe589062](https://linux-hardware.org/?probe=a2fe589062) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [d1420261d4](https://linux-hardware.org/?probe=d1420261d4) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [a66fc03cb3](https://linux-hardware.org/?probe=a66fc03cb3) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [cfd1a5ee40](https://linux-hardware.org/?probe=cfd1a5ee40) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [2e5a5d8827](https://linux-hardware.org/?probe=2e5a5d8827) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [616c5e7edb](https://linux-hardware.org/?probe=616c5e7edb) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [d6d7e853e0](https://linux-hardware.org/?probe=d6d7e853e0) | Oct 29, 2019 |
| Fujitsu       | D2990-A2 S26361-D2990-A2    | Desktop     | [a5359e7def](https://linux-hardware.org/?probe=a5359e7def) | Oct 29, 2019 |
| Foxconn       | A6VMX 0A                    | Desktop     | [74249dc009](https://linux-hardware.org/?probe=74249dc009) | Oct 29, 2019 |
| Dell          | Latitude E6410              | Notebook    | [2888ece276](https://linux-hardware.org/?probe=2888ece276) | Oct 27, 2019 |
| Dell          | G7 7588                     | Notebook    | [2479b39b58](https://linux-hardware.org/?probe=2479b39b58) | Oct 27, 2019 |
| iEi           | B202 V1.0                   | Desktop     | [bffdad4a05](https://linux-hardware.org/?probe=bffdad4a05) | Oct 26, 2019 |
| Dell          | Inspiron 3580               | Notebook    | [29ff86014c](https://linux-hardware.org/?probe=29ff86014c) | Oct 22, 2019 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [21d76cde28](https://linux-hardware.org/?probe=21d76cde28) | Oct 22, 2019 |
| ASRock        | H61M-VG3                    | Desktop     | [260918f990](https://linux-hardware.org/?probe=260918f990) | Oct 22, 2019 |
| Dell          | Inspiron 3580               | Notebook    | [8e4e877bc9](https://linux-hardware.org/?probe=8e4e877bc9) | Oct 22, 2019 |
| ASUSTek       | N53SN                       | Notebook    | [b41d353d8b](https://linux-hardware.org/?probe=b41d353d8b) | Oct 18, 2019 |
| Acer          | Aspire C22-865              | All in one  | [c861864ed7](https://linux-hardware.org/?probe=c861864ed7) | Oct 16, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [cc14742c63](https://linux-hardware.org/?probe=cc14742c63) | Oct 16, 2019 |
| Foxconn       | A6VMX 0A                    | Desktop     | [7991685c3a](https://linux-hardware.org/?probe=7991685c3a) | Oct 14, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [592a40c6d4](https://linux-hardware.org/?probe=592a40c6d4) | Oct 13, 2019 |
| Dell          | G3 3579                     | Notebook    | [d04a01d41c](https://linux-hardware.org/?probe=d04a01d41c) | Oct 10, 2019 |
| Dell          | Latitude E6320              | Notebook    | [0c6c848244](https://linux-hardware.org/?probe=0c6c848244) | Oct 09, 2019 |
| Dell          | Latitude E6320              | Notebook    | [8d449a6045](https://linux-hardware.org/?probe=8d449a6045) | Oct 08, 2019 |
| Dell          | Latitude E6320              | Notebook    | [3aa1254598](https://linux-hardware.org/?probe=3aa1254598) | Oct 08, 2019 |
| HP            | ProBook 470 G0              | Notebook    | [d04f4a23f0](https://linux-hardware.org/?probe=d04f4a23f0) | Oct 07, 2019 |
| Dell          | Latitude E6320              | Notebook    | [0bc384b06e](https://linux-hardware.org/?probe=0bc384b06e) | Oct 06, 2019 |
| Dell          | Latitude E6320              | Notebook    | [ebf6e0cd6e](https://linux-hardware.org/?probe=ebf6e0cd6e) | Oct 06, 2019 |
| Dell          | Latitude E6320              | Notebook    | [96b51a42c6](https://linux-hardware.org/?probe=96b51a42c6) | Oct 06, 2019 |
| Dell          | Latitude E6320              | Notebook    | [a21c13f512](https://linux-hardware.org/?probe=a21c13f512) | Oct 06, 2019 |
| Dell          | Latitude E6320              | Notebook    | [59d8f18e3d](https://linux-hardware.org/?probe=59d8f18e3d) | Oct 06, 2019 |
| Dell          | Latitude E6320              | Notebook    | [79c9edf47a](https://linux-hardware.org/?probe=79c9edf47a) | Oct 06, 2019 |
| Dell          | G3 3579                     | Notebook    | [349416fbb3](https://linux-hardware.org/?probe=349416fbb3) | Oct 05, 2019 |
| ASUSTek       | X542UQ                      | Notebook    | [0c0cfccb6f](https://linux-hardware.org/?probe=0c0cfccb6f) | Oct 02, 2019 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [54db2b52da](https://linux-hardware.org/?probe=54db2b52da) | Oct 02, 2019 |
| ASUSTek       | X542UQ                      | Notebook    | [bb0a5f1b8e](https://linux-hardware.org/?probe=bb0a5f1b8e) | Sep 28, 2019 |
| Gigabyte      | H61M-DS2                    | Desktop     | [28b8e9271b](https://linux-hardware.org/?probe=28b8e9271b) | Sep 27, 2019 |
| Gigabyte      | H61M-DS2                    | Desktop     | [ca991da064](https://linux-hardware.org/?probe=ca991da064) | Sep 27, 2019 |
| Gigabyte      | H61M-DS2                    | Desktop     | [3cf419c507](https://linux-hardware.org/?probe=3cf419c507) | Sep 27, 2019 |
| Lenovo        | ThinkPad T530 2429AR7       | Notebook    | [e1a5ba64a3](https://linux-hardware.org/?probe=e1a5ba64a3) | Sep 23, 2019 |
| Fujitsu Si... | D2587-A1 S26361-D2587-A1    | Desktop     | [fbd6f89151](https://linux-hardware.org/?probe=fbd6f89151) | Sep 19, 2019 |
| ASUSTek       | N550JK                      | Notebook    | [3a2e4ab12c](https://linux-hardware.org/?probe=3a2e4ab12c) | Sep 18, 2019 |
| Lenovo        | ThinkPad L590 20Q700AWBM    | Notebook    | [5c664d23d8](https://linux-hardware.org/?probe=5c664d23d8) | Sep 17, 2019 |
| Gigabyte      | H370 AORUS GAMING 3 WIFI... | Desktop     | [ff27a61c6c](https://linux-hardware.org/?probe=ff27a61c6c) | Sep 16, 2019 |
| HP            | Compaq 6715s (GR762ES#AB... | Notebook    | [320661ca9f](https://linux-hardware.org/?probe=320661ca9f) | Sep 16, 2019 |
| Toshiba       | Satellite L855              | Notebook    | [f5d2dffc84](https://linux-hardware.org/?probe=f5d2dffc84) | Sep 13, 2019 |
| ASUSTek       | X542UQ                      | Notebook    | [fca2fc959c](https://linux-hardware.org/?probe=fca2fc959c) | Sep 13, 2019 |
| Notebook      | P17SM-A                     | Notebook    | [6ccaea7ee4](https://linux-hardware.org/?probe=6ccaea7ee4) | Sep 11, 2019 |
| HP            | Pavilion dv6                | Notebook    | [4ddfed675e](https://linux-hardware.org/?probe=4ddfed675e) | Sep 07, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [612c5f53a4](https://linux-hardware.org/?probe=612c5f53a4) | Sep 07, 2019 |
| Lenovo        | ThinkPad T530 2429AR7       | Notebook    | [7a72a89d1b](https://linux-hardware.org/?probe=7a72a89d1b) | Sep 05, 2019 |
| ASUSTek       | V-P8H67E                    | Desktop     | [9f517e5081](https://linux-hardware.org/?probe=9f517e5081) | Aug 31, 2019 |
| ASUSTek       | K55VD                       | Notebook    | [072fcfd6de](https://linux-hardware.org/?probe=072fcfd6de) | Aug 29, 2019 |
| Dell          | Precision M4600             | Notebook    | [9a70878de0](https://linux-hardware.org/?probe=9a70878de0) | Aug 26, 2019 |
| ASRock        | A75M-HVS                    | Desktop     | [c5d625831f](https://linux-hardware.org/?probe=c5d625831f) | Aug 23, 2019 |
| Dell          | Vostro 3559                 | Notebook    | [0ec7ad0379](https://linux-hardware.org/?probe=0ec7ad0379) | Aug 22, 2019 |
| Fujitsu       | CELSIUS H730                | Notebook    | [69d7eea0f3](https://linux-hardware.org/?probe=69d7eea0f3) | Aug 21, 2019 |
| Fujitsu       | CELSIUS H730                | Notebook    | [896ecfb0f1](https://linux-hardware.org/?probe=896ecfb0f1) | Aug 21, 2019 |
| Fujitsu       | CELSIUS H730                | Notebook    | [f94cbdeb8e](https://linux-hardware.org/?probe=f94cbdeb8e) | Aug 21, 2019 |
| Dell          | 0XCR8D A02                  | Desktop     | [ed9cabe6d7](https://linux-hardware.org/?probe=ed9cabe6d7) | Aug 16, 2019 |
| Dell          | Inspiron 5482               | Notebook    | [637995a063](https://linux-hardware.org/?probe=637995a063) | Aug 15, 2019 |
| HP            | Compaq 6830s                | Notebook    | [525e681524](https://linux-hardware.org/?probe=525e681524) | Aug 07, 2019 |
| ASUSTek       | N550JK                      | Notebook    | [8cfc8e44ca](https://linux-hardware.org/?probe=8cfc8e44ca) | Aug 04, 2019 |
| ASUSTek       | M2N-MX                      | Desktop     | [97e0e3e7ce](https://linux-hardware.org/?probe=97e0e3e7ce) | Aug 04, 2019 |
| ASUSTek       | M2N-MX                      | Desktop     | [662d4876ce](https://linux-hardware.org/?probe=662d4876ce) | Aug 04, 2019 |
| Dell          | 0CRH6C A01                  | Desktop     | [1e288a14af](https://linux-hardware.org/?probe=1e288a14af) | Aug 03, 2019 |
| Fujitsu       | LIFEBOOK N532               | Notebook    | [b9a4817612](https://linux-hardware.org/?probe=b9a4817612) | Jul 28, 2019 |
| Fujitsu Si... | D2344-A3 S26361-D2344-A3    | Desktop     | [82e5d349d1](https://linux-hardware.org/?probe=82e5d349d1) | Jul 28, 2019 |
| HP            | 09F8h                       | Desktop     | [c52ee1274d](https://linux-hardware.org/?probe=c52ee1274d) | Jul 27, 2019 |
| Medion        | P7648 MD99980               | Notebook    | [ac77e66d3f](https://linux-hardware.org/?probe=ac77e66d3f) | Jul 24, 2019 |
| Gigabyte      | C1037UN-EU                  | Desktop     | [6790768959](https://linux-hardware.org/?probe=6790768959) | Jul 20, 2019 |
| ASUSTek       | X542UQ                      | Notebook    | [b531eab1de](https://linux-hardware.org/?probe=b531eab1de) | Jul 16, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [06603d3dce](https://linux-hardware.org/?probe=06603d3dce) | Jul 14, 2019 |
| Dell          | Latitude E4300              | Notebook    | [59050a5736](https://linux-hardware.org/?probe=59050a5736) | Jul 10, 2019 |
| Dell          | Inspiron 3551               | Notebook    | [ff1bf9089c](https://linux-hardware.org/?probe=ff1bf9089c) | Jul 08, 2019 |
| Dell          | Inspiron 3551               | Notebook    | [8add5e4718](https://linux-hardware.org/?probe=8add5e4718) | Jul 08, 2019 |
| Acer          | Aspire 5552G                | Notebook    | [e5d4cddd0b](https://linux-hardware.org/?probe=e5d4cddd0b) | Jul 07, 2019 |
| IBM           | ThinkPad T42 2373ZXW        | Notebook    | [1811b66e00](https://linux-hardware.org/?probe=1811b66e00) | Jul 05, 2019 |
| HP            | Pavilion 15                 | Notebook    | [bc7f328871](https://linux-hardware.org/?probe=bc7f328871) | Jul 02, 2019 |
| Pegatron      | A15                         | Notebook    | [754abad872](https://linux-hardware.org/?probe=754abad872) | Jul 01, 2019 |
| Acer          | Aspire A315-31              | Notebook    | [475d99370e](https://linux-hardware.org/?probe=475d99370e) | Jul 01, 2019 |
| IBM           | ThinkPad T42 2373ZXW        | Notebook    | [605b0740b5](https://linux-hardware.org/?probe=605b0740b5) | Jun 24, 2019 |
| ASUSTek       | M4A78T-E                    | Desktop     | [607db49638](https://linux-hardware.org/?probe=607db49638) | Jun 22, 2019 |
| Gigabyte      | Z170-HD3 DDR3-CF            | Desktop     | [d8c3110cba](https://linux-hardware.org/?probe=d8c3110cba) | Jun 22, 2019 |
| Gigabyte      | X99-UD4-CF                  | Desktop     | [dfc4a93cdf](https://linux-hardware.org/?probe=dfc4a93cdf) | Jun 21, 2019 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [b95d164f8c](https://linux-hardware.org/?probe=b95d164f8c) | Jun 19, 2019 |
| IBM           | ThinkPad T42 2373ZXW        | Notebook    | [374a9699db](https://linux-hardware.org/?probe=374a9699db) | Jun 18, 2019 |
| IBM           | ThinkPad T42 2373ZXW        | Notebook    | [ae491db991](https://linux-hardware.org/?probe=ae491db991) | Jun 15, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [7a53859124](https://linux-hardware.org/?probe=7a53859124) | Jun 15, 2019 |
| IBM           | ThinkPad T42 2373ZXW        | Notebook    | [30068f1670](https://linux-hardware.org/?probe=30068f1670) | Jun 09, 2019 |
| Foxconn       | 945 7MD Series              | Desktop     | [1acc3bbabb](https://linux-hardware.org/?probe=1acc3bbabb) | Jun 04, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [306644fa7c](https://linux-hardware.org/?probe=306644fa7c) | Jun 04, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [c6ced8e5a5](https://linux-hardware.org/?probe=c6ced8e5a5) | Jun 02, 2019 |
| Dell          | 0C27VV A03                  | Desktop     | [d78c1d6096](https://linux-hardware.org/?probe=d78c1d6096) | May 27, 2019 |
| Dell          | 0C27VV A03                  | Desktop     | [c8bb3e23f9](https://linux-hardware.org/?probe=c8bb3e23f9) | May 27, 2019 |
| Lenovo        | Unknown                     | Notebook    | [157cdcf284](https://linux-hardware.org/?probe=157cdcf284) | May 26, 2019 |
| ASUSTek       | K73SD                       | Notebook    | [d00a49591e](https://linux-hardware.org/?probe=d00a49591e) | May 22, 2019 |
| Lenovo        | Y520-15IKBM 80YY            | Notebook    | [d814f4eab3](https://linux-hardware.org/?probe=d814f4eab3) | May 21, 2019 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | Desktop     | [9ed71fdbcf](https://linux-hardware.org/?probe=9ed71fdbcf) | May 20, 2019 |
| Acer          | Aspire VN7-592G             | Notebook    | [5423f5da6b](https://linux-hardware.org/?probe=5423f5da6b) | May 19, 2019 |
| Fujitsu       | D2912-A1 S26361-D2912-A1    | Desktop     | [b18be16b85](https://linux-hardware.org/?probe=b18be16b85) | May 17, 2019 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [673c1426f0](https://linux-hardware.org/?probe=673c1426f0) | May 12, 2019 |
| Acer          | Aspire A315-31              | Notebook    | [e19546ffd9](https://linux-hardware.org/?probe=e19546ffd9) | May 12, 2019 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [5fa03a3e8f](https://linux-hardware.org/?probe=5fa03a3e8f) | May 07, 2019 |
| ASUSTek       | M2N-X                       | Desktop     | [aa1ba4b47d](https://linux-hardware.org/?probe=aa1ba4b47d) | May 07, 2019 |
| Dell          | Latitude E6540              | Notebook    | [a12e80fc14](https://linux-hardware.org/?probe=a12e80fc14) | May 04, 2019 |
| HP            | 1906                        | Desktop     | [7ea8acd893](https://linux-hardware.org/?probe=7ea8acd893) | May 01, 2019 |
| Fujitsu       | D3004-A1 S26361-D3004-A1    | Desktop     | [17448d5b73](https://linux-hardware.org/?probe=17448d5b73) | Apr 29, 2019 |
| LG Electro... | FS-2A46HS                   | Notebook    | [c71f72f074](https://linux-hardware.org/?probe=c71f72f074) | Apr 27, 2019 |
| LG Electro... | FS-2A46HS                   | Notebook    | [aafcf2ac24](https://linux-hardware.org/?probe=aafcf2ac24) | Apr 27, 2019 |
| ASUSTek       | N551VW                      | Notebook    | [8bdeeb7120](https://linux-hardware.org/?probe=8bdeeb7120) | Apr 22, 2019 |
| ASUSTek       | N551VW                      | Notebook    | [803ca8464c](https://linux-hardware.org/?probe=803ca8464c) | Apr 22, 2019 |
| ASUSTek       | N551VW                      | Notebook    | [08e00b08aa](https://linux-hardware.org/?probe=08e00b08aa) | Apr 22, 2019 |
| ASUSTek       | N551VW                      | Notebook    | [53875a4cf6](https://linux-hardware.org/?probe=53875a4cf6) | Apr 22, 2019 |
| ASUSTek       | N551VW                      | Notebook    | [e2d43a8c6b](https://linux-hardware.org/?probe=e2d43a8c6b) | Apr 22, 2019 |
| ASUSTek       | N551VW                      | Notebook    | [01575f8e47](https://linux-hardware.org/?probe=01575f8e47) | Apr 22, 2019 |
| Lenovo        | IdeaPad Z580                | Notebook    | [88ec17f6dc](https://linux-hardware.org/?probe=88ec17f6dc) | Apr 18, 2019 |
| HP            | ProBook 6470b               | Notebook    | [6008fdba9d](https://linux-hardware.org/?probe=6008fdba9d) | Apr 17, 2019 |
| ASRock        | B150M Pro4                  | Desktop     | [8227df5ae7](https://linux-hardware.org/?probe=8227df5ae7) | Apr 13, 2019 |
| HP            | EliteBook 8740w             | Notebook    | [adfd8e7463](https://linux-hardware.org/?probe=adfd8e7463) | Apr 12, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [f0021f0fdc](https://linux-hardware.org/?probe=f0021f0fdc) | Apr 12, 2019 |
| Dell          | Inspiron 3737               | Notebook    | [86eb821fa9](https://linux-hardware.org/?probe=86eb821fa9) | Apr 11, 2019 |
| Lenovo        | ThinkPad T400 2768BN3       | Notebook    | [de1581a896](https://linux-hardware.org/?probe=de1581a896) | Apr 11, 2019 |
| Lenovo        | ThinkPad T400 2768BN3       | Notebook    | [092bae147c](https://linux-hardware.org/?probe=092bae147c) | Apr 09, 2019 |
| Lenovo        | ThinkPad T400 2768BN3       | Notebook    | [4e1b1fbf52](https://linux-hardware.org/?probe=4e1b1fbf52) | Apr 09, 2019 |
| Lenovo        | ThinkPad T400 2768BN3       | Notebook    | [51988ce7c2](https://linux-hardware.org/?probe=51988ce7c2) | Apr 09, 2019 |
| Lenovo        | G500 20236                  | Notebook    | [5be2bd43e2](https://linux-hardware.org/?probe=5be2bd43e2) | Apr 07, 2019 |
| Lenovo        | G580                        | Notebook    | [1b00fafcef](https://linux-hardware.org/?probe=1b00fafcef) | Apr 07, 2019 |
| Acer          | Switch SA5-271              | Tablet      | [d6efa0f211](https://linux-hardware.org/?probe=d6efa0f211) | Apr 04, 2019 |
| Acer          | Switch SA5-271              | Tablet      | [16c137508d](https://linux-hardware.org/?probe=16c137508d) | Mar 25, 2019 |
| Dell          | 0K240Y A02                  | Desktop     | [e206f8f36e](https://linux-hardware.org/?probe=e206f8f36e) | Mar 25, 2019 |
| Acer          | TravelMate P645-SG          | Notebook    | [e6ed7a4f8d](https://linux-hardware.org/?probe=e6ed7a4f8d) | Mar 24, 2019 |
| Acer          | TravelMate P645-SG          | Notebook    | [f18f3798b7](https://linux-hardware.org/?probe=f18f3798b7) | Mar 24, 2019 |
| Lenovo        | ThinkPad X220 42903WG       | Notebook    | [edaa665dea](https://linux-hardware.org/?probe=edaa665dea) | Mar 19, 2019 |
| Foxconn       | A6VMX 0A                    | Desktop     | [b63ef41e02](https://linux-hardware.org/?probe=b63ef41e02) | Mar 16, 2019 |
| Lenovo        | ThinkPad T530 2429AR7       | Notebook    | [a74f00993b](https://linux-hardware.org/?probe=a74f00993b) | Mar 12, 2019 |
| Lenovo        | ThinkPad T530 2429AR7       | Notebook    | [b484a879d4](https://linux-hardware.org/?probe=b484a879d4) | Mar 08, 2019 |
| Lenovo        | G580                        | Notebook    | [2f4b4e326a](https://linux-hardware.org/?probe=2f4b4e326a) | Mar 01, 2019 |
| ASUSTek       | K55A                        | Notebook    | [cbd602db5a](https://linux-hardware.org/?probe=cbd602db5a) | Mar 01, 2019 |
| ASUSTek       | K55A                        | Notebook    | [48f636d07e](https://linux-hardware.org/?probe=48f636d07e) | Mar 01, 2019 |
| ASUSTek       | X541UJ                      | Notebook    | [98740161c5](https://linux-hardware.org/?probe=98740161c5) | Feb 26, 2019 |
| ASUSTek       | X541UJ                      | Notebook    | [0dc58e8846](https://linux-hardware.org/?probe=0dc58e8846) | Feb 26, 2019 |
| Dell          | Latitude E7440              | Notebook    | [c0f66137fc](https://linux-hardware.org/?probe=c0f66137fc) | Feb 21, 2019 |
| ASUSTek       | VivoBook 15_ASUS Laptop ... | Notebook    | [713a79e7e2](https://linux-hardware.org/?probe=713a79e7e2) | Feb 15, 2019 |
| Lenovo        | ThinkPad E480 20KN004TBM    | Notebook    | [651cb8fea0](https://linux-hardware.org/?probe=651cb8fea0) | Feb 12, 2019 |
| Wibtek        | H61-M HDMI2                 | Desktop     | [6f082a4f2d](https://linux-hardware.org/?probe=6f082a4f2d) | Feb 12, 2019 |
| Wibtek        | H61-M HDMI2                 | Desktop     | [3a44341e10](https://linux-hardware.org/?probe=3a44341e10) | Feb 12, 2019 |
| Lenovo        | ThinkPad E480 20KN004TBM    | Notebook    | [bccd89a470](https://linux-hardware.org/?probe=bccd89a470) | Feb 12, 2019 |
| Lenovo        | ThinkPad E480 20KN004TBM    | Notebook    | [ff93cba8d7](https://linux-hardware.org/?probe=ff93cba8d7) | Feb 12, 2019 |
| ASUSTek       | P5P43TD                     | Desktop     | [8d55cb4dca](https://linux-hardware.org/?probe=8d55cb4dca) | Feb 10, 2019 |
| Medion        | E1210                       | Notebook    | [5dfe8d16da](https://linux-hardware.org/?probe=5dfe8d16da) | Jan 26, 2019 |
| ASRock        | Z97 Anniversary             | Desktop     | [672985bb0e](https://linux-hardware.org/?probe=672985bb0e) | Jan 26, 2019 |
| Lenovo        | ThinkPad E480 20KN004TBM    | Notebook    | [68a5d67f64](https://linux-hardware.org/?probe=68a5d67f64) | Jan 24, 2019 |
| ASUSTek       | X705UNR                     | Notebook    | [b9e37eb37f](https://linux-hardware.org/?probe=b9e37eb37f) | Jan 20, 2019 |
| ASUSTek       | X705UNR                     | Notebook    | [9c08b9c72b](https://linux-hardware.org/?probe=9c08b9c72b) | Jan 20, 2019 |
| ASUSTek       | X705UNR                     | Notebook    | [45fa0ef0e3](https://linux-hardware.org/?probe=45fa0ef0e3) | Jan 20, 2019 |
| Fujitsu Si... | AMILO Pi 3540               | Notebook    | [7d38422be6](https://linux-hardware.org/?probe=7d38422be6) | Jan 19, 2019 |
| Fujitsu Si... | AMILO Pi 3540               | Notebook    | [9c98fa7c5a](https://linux-hardware.org/?probe=9c98fa7c5a) | Jan 19, 2019 |
| ASUSTek       | GL553VE                     | Notebook    | [1ccc6b1335](https://linux-hardware.org/?probe=1ccc6b1335) | Jan 12, 2019 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [e74d60bf4b](https://linux-hardware.org/?probe=e74d60bf4b) | Jan 08, 2019 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [f5081cb119](https://linux-hardware.org/?probe=f5081cb119) | Jan 08, 2019 |
| Acer          | Extensa X2610G              | Desktop     | [92c3e82d58](https://linux-hardware.org/?probe=92c3e82d58) | Jan 02, 2019 |
| ASUSTek       | GL553VE                     | Notebook    | [0c28acc8c9](https://linux-hardware.org/?probe=0c28acc8c9) | Dec 26, 2018 |
| ASUSTek       | GL553VE                     | Notebook    | [468cd6a626](https://linux-hardware.org/?probe=468cd6a626) | Dec 25, 2018 |
| Lenovo        | ThinkPad E480 20KN004TBM    | Notebook    | [fe2e661d12](https://linux-hardware.org/?probe=fe2e661d12) | Dec 17, 2018 |
| Lenovo        | ThinkPad E480 20KN004TBM    | Notebook    | [38757f20cd](https://linux-hardware.org/?probe=38757f20cd) | Dec 16, 2018 |
| ASRock        | B85M Pro3                   | Desktop     | [70f28e74b9](https://linux-hardware.org/?probe=70f28e74b9) | Dec 10, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | Notebook    | [e54f5af29a](https://linux-hardware.org/?probe=e54f5af29a) | Dec 08, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | Notebook    | [a2dfa7da47](https://linux-hardware.org/?probe=a2dfa7da47) | Dec 08, 2018 |
| Dell          | Precision M4600             | Notebook    | [812a28db21](https://linux-hardware.org/?probe=812a28db21) | Dec 05, 2018 |
| Dell          | Precision M4600             | Notebook    | [8057a5e7af](https://linux-hardware.org/?probe=8057a5e7af) | Dec 05, 2018 |
| Lenovo        | ThinkPad T530 2429AR7       | Notebook    | [2821650e1b](https://linux-hardware.org/?probe=2821650e1b) | Dec 03, 2018 |
| ASRock        | Z370 Pro4                   | Desktop     | [7594332b68](https://linux-hardware.org/?probe=7594332b68) | Dec 02, 2018 |
| ASRock        | Z370 Pro4                   | Desktop     | [900f783b11](https://linux-hardware.org/?probe=900f783b11) | Dec 02, 2018 |
| ASUSTek       | X541NA                      | Notebook    | [bdaeaf5ca2](https://linux-hardware.org/?probe=bdaeaf5ca2) | Nov 30, 2018 |
| Acer          | TravelMate P645-SG          | Notebook    | [b4dc1aeb7a](https://linux-hardware.org/?probe=b4dc1aeb7a) | Nov 25, 2018 |
| ASUSTek       | X541NA                      | Notebook    | [aee08bb40e](https://linux-hardware.org/?probe=aee08bb40e) | Nov 18, 2018 |
| ASRock        | B360M-HDV                   | Desktop     | [fb017cece0](https://linux-hardware.org/?probe=fb017cece0) | Nov 16, 2018 |
| ASRock        | Z77 Extreme3                | Desktop     | [a85b28c3f9](https://linux-hardware.org/?probe=a85b28c3f9) | Nov 15, 2018 |
| HP            | ProBook 4540s               | Notebook    | [06de7c3363](https://linux-hardware.org/?probe=06de7c3363) | Oct 14, 2018 |
| Gigabyte      | H81M-S2V                    | Desktop     | [801b3fb729](https://linux-hardware.org/?probe=801b3fb729) | Jun 27, 2018 |
| Lenovo        | ThinkPad W500 4063E94       | Notebook    | [1501370ab2](https://linux-hardware.org/?probe=1501370ab2) | Jun 23, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | Notebook    | [c3e231dcc8](https://linux-hardware.org/?probe=c3e231dcc8) | Jun 16, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | Notebook    | [44ec001331](https://linux-hardware.org/?probe=44ec001331) | May 17, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | Notebook    | [72551c6b8d](https://linux-hardware.org/?probe=72551c6b8d) | May 06, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | Notebook    | [827bf22ec7](https://linux-hardware.org/?probe=827bf22ec7) | May 06, 2018 |
| Lenovo        | ThinkPad L530 24781Z6       | Notebook    | [2f69425a7c](https://linux-hardware.org/?probe=2f69425a7c) | Apr 30, 2018 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [ee5ac544fa](https://linux-hardware.org/?probe=ee5ac544fa) | Feb 24, 2018 |
| Intel         | DH67GD AAG10206-208         | Desktop     | [fbd1d0b016](https://linux-hardware.org/?probe=fbd1d0b016) | Feb 23, 2018 |
| Lenovo        | G50-45 80E3                 | Notebook    | [cbd88fab14](https://linux-hardware.org/?probe=cbd88fab14) | Feb 18, 2018 |
| HP            | Mini 311-1000               | Notebook    | [82a73faa41](https://linux-hardware.org/?probe=82a73faa41) | Feb 06, 2018 |
| Notebook      | P17SM-A                     | Notebook    | [5231746786](https://linux-hardware.org/?probe=5231746786) | Jan 25, 2018 |
| Acer          | Aspire XC-605               | Desktop     | [cbd8d79578](https://linux-hardware.org/?probe=cbd8d79578) | Jan 19, 2018 |
| Lenovo        | ThinkPad X200 2024A11       | Notebook    | [cebad9ea77](https://linux-hardware.org/?probe=cebad9ea77) | Jan 08, 2018 |
| HP            | Mini 311-1000               | Notebook    | [f0cf0539e0](https://linux-hardware.org/?probe=f0cf0539e0) | Jan 04, 2018 |
| Lenovo        | ThinkPad X200 2024A11       | Notebook    | [751eb89800](https://linux-hardware.org/?probe=751eb89800) | Dec 27, 2017 |
| Toshiba       | Satellite L300              | Notebook    | [62a451c290](https://linux-hardware.org/?probe=62a451c290) | Dec 21, 2017 |
| Foxconn       | A6VMX 0A                    | Desktop     | [8ba0c7f4c3](https://linux-hardware.org/?probe=8ba0c7f4c3) | Dec 21, 2017 |
| HP            | Mini 311-1000               | Notebook    | [262b543716](https://linux-hardware.org/?probe=262b543716) | Dec 16, 2017 |
| HP            | Mini 311-1000               | Notebook    | [6c4a7a03fc](https://linux-hardware.org/?probe=6c4a7a03fc) | Dec 15, 2017 |
| Toshiba       | Satellite PRO R850          | Notebook    | [8f76c37692](https://linux-hardware.org/?probe=8f76c37692) | Dec 11, 2017 |
| HP            | Mini 311-1000               | Notebook    | [e29e6cba94](https://linux-hardware.org/?probe=e29e6cba94) | Dec 01, 2017 |
| HP            | Mini 311-1000               | Notebook    | [53f93e34f5](https://linux-hardware.org/?probe=53f93e34f5) | Nov 30, 2017 |
| ASUSTek       | K53SV                       | Notebook    | [ddd21d12ef](https://linux-hardware.org/?probe=ddd21d12ef) | Nov 28, 2017 |
| Toshiba       | Satellite L300              | Notebook    | [5ff5de6e1c](https://linux-hardware.org/?probe=5ff5de6e1c) | Nov 14, 2017 |
| Lenovo        | G50-45 80E3                 | Notebook    | [150bc63715](https://linux-hardware.org/?probe=150bc63715) | Nov 06, 2017 |
| Intel         | DH67GD AAG10206-208         | Desktop     | [9722b2d773](https://linux-hardware.org/?probe=9722b2d773) | Oct 31, 2017 |
| Intel         | DH67GD AAG10206-208         | Desktop     | [728c8e49b2](https://linux-hardware.org/?probe=728c8e49b2) | Oct 27, 2017 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [8db3dd798e](https://linux-hardware.org/?probe=8db3dd798e) | Sep 05, 2017 |
| ASUSTek       | Maximus IX HERO             | Desktop     | [9f96da724a](https://linux-hardware.org/?probe=9f96da724a) | Sep 05, 2017 |
| Dell          | 0NKW6Y A00                  | Desktop     | [212f6d0514](https://linux-hardware.org/?probe=212f6d0514) | Sep 03, 2017 |
| HP            | Compaq nx7400 (RU430ET#A... | Notebook    | [6d9cfb4cb9](https://linux-hardware.org/?probe=6d9cfb4cb9) | Jul 30, 2017 |
| Intel         | DH67GD AAG10206-208         | Desktop     | [0c3b83b208](https://linux-hardware.org/?probe=0c3b83b208) | Jun 06, 2017 |
| ASUSTek       | M4A78LT-M                   | Desktop     | [0a1b2311b5](https://linux-hardware.org/?probe=0a1b2311b5) | May 28, 2017 |
| ASUSTek       | X540LJ                      | Notebook    | [7cd67a8489](https://linux-hardware.org/?probe=7cd67a8489) | Apr 26, 2017 |
| ASUSTek       | X540LJ                      | Notebook    | [f79d8f68ca](https://linux-hardware.org/?probe=f79d8f68ca) | Apr 26, 2017 |
| Supermicro    | C2SBC-Q                     | Desktop     | [671517f196](https://linux-hardware.org/?probe=671517f196) | Apr 15, 2017 |
| Acer          | Aspire V5-573G              | Notebook    | [fb0bbb47d3](https://linux-hardware.org/?probe=fb0bbb47d3) | Feb 23, 2017 |
| ASRock        | H61M-GS                     | Desktop     | [5625f5be6e](https://linux-hardware.org/?probe=5625f5be6e) | Jan 30, 2017 |
| ASRock        | H61M-GS                     | Desktop     | [f309dd0e46](https://linux-hardware.org/?probe=f309dd0e46) | Jan 24, 2017 |
| ASRock        | H61M-GS                     | Desktop     | [eb755563bf](https://linux-hardware.org/?probe=eb755563bf) | Nov 24, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Ubuntu 20.04       | 106       | 13.84%  |
| Ubuntu 18.04       | 80        | 10.44%  |
| OpenMandriva 4.2   | 28        | 3.66%   |
| ROSA R11           | 18        | 2.35%   |
| Linux Mint 20.1    | 17        | 2.22%   |
| ROSA R10           | 16        | 2.09%   |
| Manjaro            | 15        | 1.96%   |
| Linux Mint 19.3    | 14        | 1.83%   |
| Ubuntu 19.04       | 13        | 1.7%    |
| OpenMandriva 4.3   | 13        | 1.7%    |
| Debian 11          | 13        | 1.7%    |
| Xubuntu 18.04      | 12        | 1.57%   |
| Ubuntu 19.10       | 12        | 1.57%   |
| Linux Mint 20.2    | 12        | 1.57%   |
| Linux Mint 20      | 12        | 1.57%   |
| Kubuntu 20.04      | 12        | 1.57%   |
| KDE neon 20.04     | 12        | 1.57%   |
| Arch               | 12        | 1.57%   |
| Ubuntu 16.04       | 11        | 1.44%   |
| Zorin 15           | 10        | 1.31%   |
| Pop!_OS 20.10      | 10        | 1.31%   |
| Fedora 33          | 10        | 1.31%   |
| ArcoLinux Rolling  | 10        | 1.31%   |
| Xubuntu 20.04      | 9         | 1.17%   |
| Ubuntu 20.10       | 9         | 1.17%   |
| LMDE 4             | 9         | 1.17%   |
| Linux Mint 20.3    | 8         | 1.04%   |
| ROSA R9            | 7         | 0.91%   |
| Pop!_OS 20.04      | 7         | 0.91%   |
| Fedora 34          | 7         | 0.91%   |
| Fedora 31          | 7         | 0.91%   |
| Zorin 16           | 6         | 0.78%   |
| ROSA R11.1         | 6         | 0.78%   |
| Pop!_OS 21.04      | 6         | 0.78%   |
| Fedora 35          | 6         | 0.78%   |
| Ubuntu 21.10       | 5         | 0.65%   |
| ROSA R8.1          | 5         | 0.65%   |
| Pop!_OS 21.10      | 5         | 0.65%   |
| OpenMandriva 4.50  | 5         | 0.65%   |
| Debian 10          | 5         | 0.65%   |
| Arch Rolling       | 5         | 0.65%   |
| Ubuntu 21.04       | 4         | 0.52%   |
| KDE neon 18.04     | 4         | 0.52%   |
| CentOS 7           | 4         | 0.52%   |
| Void Linux Rolling | 3         | 0.39%   |
| Ubuntu 18.10       | 3         | 0.39%   |
| Manjaro 21.2.0     | 3         | 0.39%   |
| Manjaro 20.2       | 3         | 0.39%   |
| Manjaro 20.0.3     | 3         | 0.39%   |
| Kali 2021.4        | 3         | 0.39%   |
| Gentoo 2.6         | 3         | 0.39%   |
| Fedora 32          | 3         | 0.39%   |
| Fedora 29          | 3         | 0.39%   |
| Debian 9           | 3         | 0.39%   |
| Xubuntu 21.10      | 2         | 0.26%   |
| Ubuntu MATE 20.04  | 2         | 0.26%   |
| ROSA R8            | 2         | 0.26%   |
| openSUSE Leap-15.2 | 2         | 0.26%   |
| Manjaro 21.2.5     | 2         | 0.26%   |
| Manjaro 19.0.2     | 2         | 0.26%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 233       | 33.1%   |
| Linux Mint    | 63        | 8.95%   |
| ROSA          | 46        | 6.53%   |
| OpenMandriva  | 46        | 6.53%   |
| Manjaro       | 33        | 4.69%   |
| Fedora        | 31        | 4.4%    |
| Pop!_OS       | 27        | 3.84%   |
| Endless       | 27        | 3.84%   |
| Xubuntu       | 23        | 3.27%   |
| Debian        | 22        | 3.13%   |
| Arch          | 17        | 2.41%   |
| Zorin         | 16        | 2.27%   |
| Kubuntu       | 16        | 2.27%   |
| KDE neon      | 16        | 2.27%   |
| Clear Linux   | 12        | 1.7%    |
| ArcoLinux     | 12        | 1.7%    |
| LMDE          | 9         | 1.28%   |
| Kali          | 9         | 1.28%   |
| openSUSE      | 6         | 0.85%   |
| Lubuntu       | 6         | 0.85%   |
| CentOS        | 6         | 0.85%   |
| Elementary    | 5         | 0.71%   |
| Void Linux    | 3         | 0.43%   |
| Gentoo        | 3         | 0.43%   |
| Ubuntu MATE   | 2         | 0.28%   |
| Novos         | 2         | 0.28%   |
| EndeavourOS   | 2         | 0.28%   |
| Artix         | 2         | 0.28%   |
| Ubuntu Studio | 1         | 0.14%   |
| Ubuntu Budgie | 1         | 0.14%   |
| Slackware     | 1         | 0.14%   |
| RHEL          | 1         | 0.14%   |
| Peppermint    | 1         | 0.14%   |
| Oracle Linux  | 1         | 0.14%   |
| Mageia        | 1         | 0.14%   |
| Deepin        | 1         | 0.14%   |
| BlackPanther  | 1         | 0.14%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                          | Computers | Percent |
|----------------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002         | 28        | 3.31%   |
| 5.4.0-42-generic                 | 17        | 2.01%   |
| 4.15.0-desktop-45.1rosa-x86_64   | 14        | 1.65%   |
| 5.4.0-58-generic                 | 13        | 1.53%   |
| 5.16.7-desktop-1omv4003          | 13        | 1.53%   |
| 5.3.0-40-generic                 | 10        | 1.18%   |
| 5.9.16-1-MANJARO                 | 8         | 0.94%   |
| 5.4.0-48-generic                 | 7         | 0.83%   |
| 5.4.0-40-generic                 | 7         | 0.83%   |
| 5.4.0-29-generic                 | 7         | 0.83%   |
| 5.4.0-26-generic                 | 7         | 0.83%   |
| 5.3.0-42-generic                 | 7         | 0.83%   |
| 5.3.0-28-generic                 | 7         | 0.83%   |
| 5.10.0-8-amd64                   | 7         | 0.83%   |
| 5.0.0-37-generic                 | 7         | 0.83%   |
| 5.8.0-14-generic                 | 6         | 0.71%   |
| 5.4.0-65-generic                 | 6         | 0.71%   |
| 5.4.0-56-generic                 | 6         | 0.71%   |
| 5.3.0-46-generic                 | 6         | 0.71%   |
| 5.11.0-37-generic                | 6         | 0.71%   |
| 5.11.0-27-generic                | 6         | 0.71%   |
| 5.0.0-23-generic                 | 6         | 0.71%   |
| 4.9.20-nrj-desktop-1rosa-x86_64  | 6         | 0.71%   |
| 5.8.0-7642-generic               | 5         | 0.59%   |
| 5.8.0-43-generic                 | 5         | 0.59%   |
| 5.4.0-91-generic                 | 5         | 0.59%   |
| 5.4.0-77-generic                 | 5         | 0.59%   |
| 5.4.0-67-generic                 | 5         | 0.59%   |
| 5.4.0-47-generic                 | 5         | 0.59%   |
| 5.4.0-19-generic                 | 5         | 0.59%   |
| 5.13.0-28-generic                | 5         | 0.59%   |
| 5.0.0-32-generic                 | 5         | 0.59%   |
| 4.9.60-nrj-desktop-1rosa-x86_64  | 5         | 0.59%   |
| 4.18.0-25-generic                | 5         | 0.59%   |
| 4.15.0-20-generic                | 5         | 0.59%   |
| 5.8.0-40-generic                 | 4         | 0.47%   |
| 5.4.0-81-generic                 | 4         | 0.47%   |
| 5.4.0-73-generic                 | 4         | 0.47%   |
| 5.4.0-37-generic                 | 4         | 0.47%   |
| 5.4.0-28-generic                 | 4         | 0.47%   |
| 5.3.0-53-generic                 | 4         | 0.47%   |
| 5.3.0-51-generic                 | 4         | 0.47%   |
| 5.13.0-30-generic                | 4         | 0.47%   |
| 5.13.0-27-generic                | 4         | 0.47%   |
| 5.13.0-22-generic                | 4         | 0.47%   |
| 5.12.4-desktop-1omv4050          | 4         | 0.47%   |
| 5.11.0-44-generic                | 4         | 0.47%   |
| 5.11.0-41-generic                | 4         | 0.47%   |
| 4.9.124-nrj-desktop-1rosa-x86_64 | 4         | 0.47%   |
| 4.19.0-8-amd64                   | 4         | 0.47%   |
| 4.15.0-45-generic                | 4         | 0.47%   |
| 4.15.0-29-generic                | 4         | 0.47%   |
| 5.8.11-1-MANJARO                 | 3         | 0.35%   |
| 5.8.0-63-generic                 | 3         | 0.35%   |
| 5.8.0-59-generic                 | 3         | 0.35%   |
| 5.8.0-53-generic                 | 3         | 0.35%   |
| 5.8.0-33-generic                 | 3         | 0.35%   |
| 5.4.0-90-generic                 | 3         | 0.35%   |
| 5.4.0-7634-generic               | 3         | 0.35%   |
| 5.4.0-74-generic                 | 3         | 0.35%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 152       | 19.26%  |
| 4.15.0  | 78        | 9.89%   |
| 5.8.0   | 52        | 6.59%   |
| 5.3.0   | 49        | 6.21%   |
| 5.11.0  | 38        | 4.82%   |
| 5.0.0   | 37        | 4.69%   |
| 5.10.14 | 29        | 3.68%   |
| 5.13.0  | 26        | 3.3%    |
| 4.18.0  | 23        | 2.92%   |
| 5.10.0  | 16        | 2.03%   |
| 5.16.7  | 13        | 1.65%   |
| 4.19.0  | 12        | 1.52%   |
| 5.9.16  | 11        | 1.39%   |
| 4.9.20  | 9         | 1.14%   |
| 4.9.60  | 6         | 0.76%   |
| 5.8.18  | 5         | 0.63%   |
| 4.9.124 | 5         | 0.63%   |
| 4.4.0   | 5         | 0.63%   |
| 5.8.11  | 4         | 0.51%   |
| 5.6.8   | 4         | 0.51%   |
| 5.6.0   | 4         | 0.51%   |
| 5.15.0  | 4         | 0.51%   |
| 5.12.4  | 4         | 0.51%   |
| 5.11.12 | 4         | 0.51%   |
| 5.7.6   | 3         | 0.38%   |
| 5.3.16  | 3         | 0.38%   |
| 5.17.5  | 3         | 0.38%   |
| 5.16.15 | 3         | 0.38%   |
| 5.16.11 | 3         | 0.38%   |
| 5.15.8  | 3         | 0.38%   |
| 5.12.14 | 3         | 0.38%   |
| 4.9.76  | 3         | 0.38%   |
| 4.1.38  | 3         | 0.38%   |
| 3.10.0  | 3         | 0.38%   |
| 5.9.10  | 2         | 0.25%   |
| 5.8.14  | 2         | 0.25%   |
| 5.7.7   | 2         | 0.25%   |
| 5.7.19  | 2         | 0.25%   |
| 5.5.13  | 2         | 0.25%   |
| 5.4.83  | 2         | 0.25%   |
| 5.4.80  | 2         | 0.25%   |
| 5.4.32  | 2         | 0.25%   |
| 5.4.18  | 2         | 0.25%   |
| 5.3.14  | 2         | 0.25%   |
| 5.3.12  | 2         | 0.25%   |
| 5.16.10 | 2         | 0.25%   |
| 5.15.7  | 2         | 0.25%   |
| 5.15.6  | 2         | 0.25%   |
| 5.15.5  | 2         | 0.25%   |
| 5.14.0  | 2         | 0.25%   |
| 5.13.8  | 2         | 0.25%   |
| 5.13.6  | 2         | 0.25%   |
| 5.11.11 | 2         | 0.25%   |
| 5.10.79 | 2         | 0.25%   |
| 5.10.74 | 2         | 0.25%   |
| 5.10.56 | 2         | 0.25%   |
| 5.10.16 | 2         | 0.25%   |
| 5.1.0   | 2         | 0.25%   |
| 4.9.95  | 2         | 0.25%   |
| 4.9.9   | 2         | 0.25%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 162       | 21.09%  |
| 4.15    | 78        | 10.16%  |
| 5.10    | 67        | 8.72%   |
| 5.8     | 64        | 8.33%   |
| 5.3     | 58        | 7.55%   |
| 5.11    | 49        | 6.38%   |
| 5.0     | 40        | 5.21%   |
| 5.13    | 32        | 4.17%   |
| 5.16    | 29        | 3.78%   |
| 4.9     | 26        | 3.39%   |
| 4.18    | 24        | 3.13%   |
| 5.15    | 21        | 2.73%   |
| 5.9     | 17        | 2.21%   |
| 4.19    | 17        | 2.21%   |
| 5.6     | 16        | 2.08%   |
| 5.7     | 11        | 1.43%   |
| 5.12    | 11        | 1.43%   |
| 5.14    | 8         | 1.04%   |
| 5.5     | 7         | 0.91%   |
| 5.2     | 5         | 0.65%   |
| 5.17    | 5         | 0.65%   |
| 4.4     | 5         | 0.65%   |
| 4.1     | 4         | 0.52%   |
| 5.1     | 3         | 0.39%   |
| 3.10    | 3         | 0.39%   |
| 4.7     | 1         | 0.13%   |
| 4.20    | 1         | 0.13%   |
| 4.13    | 1         | 0.13%   |
| 4.10    | 1         | 0.13%   |
| 3.13    | 1         | 0.13%   |
| Unknown | 1         | 0.13%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 646       | 96.27%  |
| i686   | 25        | 3.73%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| GNOME            | 258       | 35.68%  |
| Unknown          | 118       | 16.32%  |
| KDE5             | 101       | 13.97%  |
| XFCE             | 67        | 9.27%   |
| X-Cinnamon       | 50        | 6.92%   |
| KDE4             | 33        | 4.56%   |
| KDE              | 27        | 3.73%   |
| MATE             | 15        | 2.07%   |
| Cinnamon         | 13        | 1.8%    |
| Unity            | 9         | 1.24%   |
| Pantheon         | 5         | 0.69%   |
| LXQt             | 5         | 0.69%   |
| GNOME Flashback  | 5         | 0.69%   |
| Budgie           | 3         | 0.41%   |
| bspwm            | 3         | 0.41%   |
| xmonad           | 2         | 0.28%   |
| Deepin           | 2         | 0.28%   |
| qtile            | 1         | 0.14%   |
| LXDE             | 1         | 0.14%   |
| lightdm-xsession | 1         | 0.14%   |
| LeftWM           | 1         | 0.14%   |
| i3               | 1         | 0.14%   |
| GNOME Classic    | 1         | 0.14%   |
| awesome          | 1         | 0.14%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 585       | 84.17%  |
| Unknown | 60        | 8.63%   |
| Wayland | 43        | 6.19%   |
| Tty     | 7         | 1.01%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 407       | 58.23%  |
| SDDM    | 107       | 15.31%  |
| GDM     | 57        | 8.15%   |
| LightDM | 47        | 6.72%   |
| KDM     | 32        | 4.58%   |
| TDM     | 30        | 4.29%   |
| GDM3    | 18        | 2.58%   |
| MDM     | 1         | 0.14%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 389       | 55.41%  |
| Unknown | 142       | 20.23%  |
| bg_BG   | 127       | 18.09%  |
| en_GB   | 18        | 2.56%   |
| C       | 11        | 1.57%   |
| ru_RU   | 5         | 0.71%   |
| de_DE   | 5         | 0.71%   |
| POSIX   | 1         | 0.14%   |
| it_IT   | 1         | 0.14%   |
| fr_FR   | 1         | 0.14%   |
| en_DK   | 1         | 0.14%   |
| C.UTF8  | 1         | 0.14%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 409       | 59.45%  |
| EFI  | 279       | 40.55%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 528       | 76.08%  |
| Unknown | 56        | 8.07%   |
| Overlay | 52        | 7.49%   |
| Btrfs   | 31        | 4.47%   |
| Xfs     | 13        | 1.87%   |
| Zfs     | 5         | 0.72%   |
| Ext3    | 3         | 0.43%   |
| Ext2    | 3         | 0.43%   |
| Tmpfs   | 2         | 0.29%   |
| Jfs     | 1         | 0.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 421       | 61.01%  |
| GPT     | 167       | 24.2%   |
| MBR     | 102       | 14.78%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 584       | 85.01%  |
| Yes       | 103       | 14.99%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 475       | 69.55%  |
| Yes       | 208       | 30.45%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 129       | 19.28%  |
| ASUSTek Computer    | 118       | 17.64%  |
| Hewlett-Packard     | 87        | 13%     |
| Dell                | 82        | 12.26%  |
| ASRock              | 52        | 7.77%   |
| Acer                | 44        | 6.58%   |
| Gigabyte Technology | 40        | 5.98%   |
| Toshiba             | 24        | 3.59%   |
| MSI                 | 21        | 3.14%   |
| Fujitsu             | 14        | 2.09%   |
| Intel               | 7         | 1.05%   |
| Fujitsu Siemens     | 6         | 0.9%    |
| Apple               | 6         | 0.9%    |
| Foxconn             | 4         | 0.6%    |
| AMI                 | 4         | 0.6%    |
| Unknown             | 4         | 0.6%    |
| Samsung Electronics | 3         | 0.45%   |
| Packard Bell        | 3         | 0.45%   |
| Wibtek              | 2         | 0.3%    |
| Sony                | 2         | 0.3%    |
| Medion              | 2         | 0.3%    |
| TUXEDO              | 1         | 0.15%   |
| Supermicro          | 1         | 0.15%   |
| Shuttle             | 1         | 0.15%   |
| Seco                | 1         | 0.15%   |
| Razer               | 1         | 0.15%   |
| Pegatron            | 1         | 0.15%   |
| Notebook            | 1         | 0.15%   |
| MiTAC               | 1         | 0.15%   |
| LG Electronics      | 1         | 0.15%   |
| iEi                 | 1         | 0.15%   |
| IBM                 | 1         | 0.15%   |
| HUAWEI              | 1         | 0.15%   |
| ECS                 | 1         | 0.15%   |
| Cube                | 1         | 0.15%   |
| Compal              | 1         | 0.15%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 7         | 1.05%   |
| ASUS All Series                            | 5         | 0.75%   |
| Lenovo H520S 2561                          | 4         | 0.6%    |
| Lenovo G500 20236                          | 4         | 0.6%    |
| HP ProBook 4540s                           | 4         | 0.6%    |
| Dell Latitude E6410                        | 3         | 0.45%   |
| Dell Inspiron N5110                        | 3         | 0.45%   |
| ASUS X541NA                                | 3         | 0.45%   |
| ASUS VivoBook 15_ASUS Laptop X540MA_X540MA | 3         | 0.45%   |
| ASUS N551VW                                | 3         | 0.45%   |
| ASRock Z97 Anniversary                     | 3         | 0.45%   |
| Acer Aspire 5738                           | 3         | 0.45%   |
| Wibtek H61-M HDMI2                         | 2         | 0.3%    |
| Toshiba Satellite L300                     | 2         | 0.3%    |
| Toshiba Satellite C50-A-19T                | 2         | 0.3%    |
| Toshiba Satellite A200                     | 2         | 0.3%    |
| Samsung 300E4Z/300E5Z/300E7Z               | 2         | 0.3%    |
| Lenovo Yoga S740-14IIL 81RS                | 2         | 0.3%    |
| Lenovo Y520-15IKBN 80WK                    | 2         | 0.3%    |
| Lenovo ThinkPad X220 4291IR6               | 2         | 0.3%    |
| Lenovo ThinkPad X1 Carbon 3rd 20BTS1D900   | 2         | 0.3%    |
| Lenovo ThinkPad T460 20FN003LUK            | 2         | 0.3%    |
| Lenovo ThinkPad T420 4236A87               | 2         | 0.3%    |
| Lenovo ThinkPad L590 20Q700AWBM            | 2         | 0.3%    |
| Lenovo ThinkPad E480 20KN005CBM            | 2         | 0.3%    |
| Lenovo ThinkBook 13s-IML 20RR              | 2         | 0.3%    |
| Lenovo Legion Y740-17IRHg 81UJ             | 2         | 0.3%    |
| Lenovo Legion 5 15ARH05 82B5               | 2         | 0.3%    |
| Lenovo IdeaPad Y510P 20217                 | 2         | 0.3%    |
| Lenovo IdeaPad Y500 20193                  | 2         | 0.3%    |
| Lenovo IdeaPad S540-14API 81NH             | 2         | 0.3%    |
| Lenovo H520e 10159                         | 2         | 0.3%    |
| Lenovo G50-80 80E5                         | 2         | 0.3%    |
| HP ProBook 6470b                           | 2         | 0.3%    |
| HP ProBook 450 G8 Notebook PC              | 2         | 0.3%    |
| HP ProBook 450 G0                          | 2         | 0.3%    |
| HP Pavilion Laptop 15-eh0xxx               | 2         | 0.3%    |
| HP Pavilion dv5                            | 2         | 0.3%    |
| HP Pavilion 15                             | 2         | 0.3%    |
| HP Notebook                                | 2         | 0.3%    |
| HP EliteBook 8560p                         | 2         | 0.3%    |
| HP EliteBook 8460p                         | 2         | 0.3%    |
| HP EliteBook 840 G1                        | 2         | 0.3%    |
| HP EliteBook 820 G2                        | 2         | 0.3%    |
| Gigabyte X99-UD4-CF                        | 2         | 0.3%    |
| Gigabyte H370AORUSGAMING3WIFI              | 2         | 0.3%    |
| Gigabyte B450 AORUS M                      | 2         | 0.3%    |
| Fujitsu ESPRIMO P710                       | 2         | 0.3%    |
| Dell Vostro 3580                           | 2         | 0.3%    |
| Dell Studio 1747                           | 2         | 0.3%    |
| Dell Precision Tower 5810                  | 2         | 0.3%    |
| Dell Precision M4600                       | 2         | 0.3%    |
| Dell OptiPlex 780                          | 2         | 0.3%    |
| Dell Latitude E6430                        | 2         | 0.3%    |
| Dell Latitude E6330                        | 2         | 0.3%    |
| Dell Latitude E5430 non-vPro               | 2         | 0.3%    |
| Dell Latitude E4300                        | 2         | 0.3%    |
| Dell Inspiron N5010                        | 2         | 0.3%    |
| Dell Inspiron 7577                         | 2         | 0.3%    |
| Dell Inspiron 5482                         | 2         | 0.3%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                          | Computers | Percent |
|-------------------------------|-----------|---------|
| Lenovo ThinkPad               | 57        | 8.52%   |
| Acer Aspire                   | 30        | 4.48%   |
| Dell Inspiron                 | 25        | 3.74%   |
| Dell Latitude                 | 24        | 3.59%   |
| Lenovo IdeaPad                | 23        | 3.44%   |
| Toshiba Satellite             | 20        | 2.99%   |
| HP ProBook                    | 17        | 2.54%   |
| HP EliteBook                  | 17        | 2.54%   |
| HP Pavilion                   | 16        | 2.39%   |
| HP Compaq                     | 16        | 2.39%   |
| ASUS VivoBook                 | 15        | 2.24%   |
| Fujitsu ESPRIMO               | 8         | 1.2%    |
| Dell OptiPlex                 | 8         | 1.2%    |
| ASUS PRIME                    | 8         | 1.2%    |
| Lenovo ThinkCentre            | 7         | 1.05%   |
| Dell Precision                | 7         | 1.05%   |
| Unknown                       | 7         | 1.05%   |
| Lenovo Legion                 | 6         | 0.9%    |
| Dell Vostro                   | 6         | 0.9%    |
| ASUS ROG                      | 6         | 0.9%    |
| Lenovo Yoga                   | 5         | 0.75%   |
| ASUS All                      | 5         | 0.75%   |
| Lenovo H520S                  | 4         | 0.6%    |
| Lenovo G500                   | 4         | 0.6%    |
| HP 250                        | 4         | 0.6%    |
| Dell XPS                      | 4         | 0.6%    |
| ASUS TUF                      | 4         | 0.6%    |
| MSI GF63                      | 3         | 0.45%   |
| Lenovo ThinkBook              | 3         | 0.45%   |
| HP Laptop                     | 3         | 0.45%   |
| Fujitsu Siemens AMILO         | 3         | 0.45%   |
| Fujitsu LIFEBOOK              | 3         | 0.45%   |
| Dell Studio                   | 3         | 0.45%   |
| ASUS X541NA                   | 3         | 0.45%   |
| ASUS P5K                      | 3         | 0.45%   |
| ASUS N551VW                   | 3         | 0.45%   |
| ASRock Z97                    | 3         | 0.45%   |
| ASRock X570                   | 3         | 0.45%   |
| Acer Predator                 | 3         | 0.45%   |
| Acer Nitro                    | 3         | 0.45%   |
| Wibtek H61-M                  | 2         | 0.3%    |
| Samsung 300E4Z                | 2         | 0.3%    |
| MSI Modern                    | 2         | 0.3%    |
| Lenovo Y520-15IKBN            | 2         | 0.3%    |
| Lenovo ThinkStation           | 2         | 0.3%    |
| Lenovo H520e                  | 2         | 0.3%    |
| Lenovo G50-80                 | 2         | 0.3%    |
| Intel X99                     | 2         | 0.3%    |
| HP Notebook                   | 2         | 0.3%    |
| HP 255                        | 2         | 0.3%    |
| Gigabyte Z490                 | 2         | 0.3%    |
| Gigabyte X99-UD4-CF           | 2         | 0.3%    |
| Gigabyte X570                 | 2         | 0.3%    |
| Gigabyte H370AORUSGAMING3WIFI | 2         | 0.3%    |
| Gigabyte B450                 | 2         | 0.3%    |
| Fujitsu Siemens ESPRIMO       | 2         | 0.3%    |
| Fujitsu CELSIUS               | 2         | 0.3%    |
| Dell G7                       | 2         | 0.3%    |
| Dell G3                       | 2         | 0.3%    |
| ASUS TP300LA                  | 2         | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 63        | 9.42%   |
| 2012 | 63        | 9.42%   |
| 2011 | 61        | 9.12%   |
| 2017 | 57        | 8.52%   |
| 2013 | 56        | 8.37%   |
| 2018 | 48        | 7.17%   |
| 2015 | 48        | 7.17%   |
| 2014 | 45        | 6.73%   |
| 2020 | 42        | 6.28%   |
| 2010 | 40        | 5.98%   |
| 2008 | 36        | 5.38%   |
| 2009 | 28        | 4.19%   |
| 2007 | 26        | 3.89%   |
| 2016 | 24        | 3.59%   |
| 2021 | 14        | 2.09%   |
| 2006 | 12        | 1.79%   |
| 2005 | 3         | 0.45%   |
| 2004 | 2         | 0.3%    |
| 2022 | 1         | 0.15%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 407       | 60.84%  |
| Desktop     | 248       | 37.07%  |
| Mini pc     | 6         | 0.9%    |
| Convertible | 4         | 0.6%    |
| All in one  | 3         | 0.45%   |
| Tablet      | 1         | 0.15%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 642       | 95.54%  |
| Enabled  | 30        | 4.46%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 668       | 99.85%  |
| Yes  | 1         | 0.15%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 4.01-8.0    | 181       | 26.23%  |
| 3.01-4.0    | 155       | 22.46%  |
| 8.01-16.0   | 129       | 18.7%   |
| 16.01-24.0  | 107       | 15.51%  |
| 32.01-64.0  | 47        | 6.81%   |
| 1.01-2.0    | 29        | 4.2%    |
| 2.01-3.0    | 19        | 2.75%   |
| 24.01-32.0  | 13        | 1.88%   |
| 64.01-256.0 | 7         | 1.01%   |
| 0.51-1.0    | 3         | 0.43%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 287       | 36.84%  |
| 2.01-3.0   | 200       | 25.67%  |
| 4.01-8.0   | 101       | 12.97%  |
| 3.01-4.0   | 94        | 12.07%  |
| 0.51-1.0   | 67        | 8.6%    |
| 8.01-16.0  | 22        | 2.82%   |
| 0.01-0.5   | 4         | 0.51%   |
| 16.01-24.0 | 2         | 0.26%   |
| 24.01-32.0 | 1         | 0.13%   |
| Unknown    | 1         | 0.13%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 424       | 61.45%  |
| 2      | 187       | 27.1%   |
| 3      | 41        | 5.94%   |
| 4      | 14        | 2.03%   |
| 5      | 9         | 1.3%    |
| 6      | 5         | 0.72%   |
| 0      | 5         | 0.72%   |
| 7      | 2         | 0.29%   |
| 11     | 1         | 0.14%   |
| 9      | 1         | 0.14%   |
| 8      | 1         | 0.14%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 367       | 54.05%  |
| Yes       | 312       | 45.95%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 612       | 91.21%  |
| No        | 59        | 8.79%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 474       | 70.64%  |
| No        | 197       | 29.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 368       | 53.96%  |
| No        | 314       | 46.04%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country  | Computers | Percent |
|----------|-----------|---------|
| Bulgaria | 669       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Sofia               | 356       | 50.86%  |
| Varna               | 47        | 6.71%   |
| Plovdiv             | 36        | 5.14%   |
| Burgas              | 32        | 4.57%   |
| Stara Zagora        | 18        | 2.57%   |
| Pernik              | 13        | 1.86%   |
| Rousse              | 10        | 1.43%   |
| Pleven              | 10        | 1.43%   |
| Yambol              | 7         | 1%      |
| Asenovgrad          | 7         | 1%      |
| Veliko Tarnovo      | 6         | 0.86%   |
| Dobrich             | 6         | 0.86%   |
| Voysil              | 5         | 0.71%   |
| Sliven              | 5         | 0.71%   |
| Shumen              | 5         | 0.71%   |
| Montana             | 5         | 0.71%   |
| Haskovo             | 5         | 0.71%   |
| Razgrad             | 4         | 0.57%   |
| Pazardzhik          | 4         | 0.57%   |
| Gabrovo             | 4         | 0.57%   |
| Silistra            | 3         | 0.43%   |
| Saedinenie          | 3         | 0.43%   |
| Mezdra              | 3         | 0.43%   |
| Korten              | 3         | 0.43%   |
| Kazanlak            | 3         | 0.43%   |
| Karlovo             | 3         | 0.43%   |
| Blagoevgrad         | 3         | 0.43%   |
| Vratsa              | 2         | 0.29%   |
| Vidin               | 2         | 0.29%   |
| Targovishte         | 2         | 0.29%   |
| Svilengrad          | 2         | 0.29%   |
| Stamboliyski        | 2         | 0.29%   |
| Slatina             | 2         | 0.29%   |
| Sistov              | 2         | 0.29%   |
| Primorsko           | 2         | 0.29%   |
| Polikrayshte        | 2         | 0.29%   |
| Nane                | 2         | 0.29%   |
| Momchilgrad         | 2         | 0.29%   |
| Lyaskovets          | 2         | 0.29%   |
| Kyustendil          | 2         | 0.29%   |
| Kozloduy            | 2         | 0.29%   |
| Knezha              | 2         | 0.29%   |
| Kaspichan           | 2         | 0.29%   |
| Harmanli            | 2         | 0.29%   |
| Dimitrovgrad        | 2         | 0.29%   |
| Chomakovtsi         | 2         | 0.29%   |
| Tvarditsa           | 1         | 0.14%   |
| Troyan Municipality | 1         | 0.14%   |
| Toros               | 1         | 0.14%   |
| Tervel Municipality | 1         | 0.14%   |
| Sunny Beach         | 1         | 0.14%   |
| Starozagorski Bani  | 1         | 0.14%   |
| Smolyan             | 1         | 0.14%   |
| Skutare             | 1         | 0.14%   |
| Sestrino            | 1         | 0.14%   |
| Sarafovo            | 1         | 0.14%   |
| Sandanski           | 1         | 0.14%   |
| Samokov             | 1         | 0.14%   |
| Saint Vlas          | 1         | 0.14%   |
| Ruen                | 1         | 0.14%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Seagate                   | 157       | 223    | 16.44%  |
| WDC                       | 146       | 223    | 15.29%  |
| Samsung Electronics       | 132       | 197    | 13.82%  |
| Toshiba                   | 87        | 121    | 9.11%   |
| Hitachi                   | 57        | 78     | 5.97%   |
| Kingston                  | 54        | 79     | 5.65%   |
| Sandisk                   | 36        | 47     | 3.77%   |
| A-DATA Technology         | 33        | 47     | 3.46%   |
| Intel                     | 32        | 46     | 3.35%   |
| HGST                      | 29        | 43     | 3.04%   |
| Unknown                   | 23        | 33     | 2.41%   |
| Crucial                   | 16        | 25     | 1.68%   |
| Team                      | 14        | 15     | 1.47%   |
| SK Hynix                  | 14        | 16     | 1.47%   |
| China                     | 11        | 11     | 1.15%   |
| SPCC                      | 10        | 12     | 1.05%   |
| Transcend                 | 7         | 8      | 0.73%   |
| Phison                    | 7         | 7      | 0.73%   |
| Patriot                   | 7         | 8      | 0.73%   |
| KingSpec                  | 7         | 8      | 0.73%   |
| Micron Technology         | 6         | 6      | 0.63%   |
| Fujitsu                   | 6         | 10     | 0.63%   |
| Realtek Semiconductor     | 5         | 7      | 0.52%   |
| MAXTOR                    | 5         | 7      | 0.52%   |
| KIOXIA                    | 5         | 6      | 0.52%   |
| LITEON                    | 4         | 5      | 0.42%   |
| Silicon Motion            | 3         | 6      | 0.31%   |
| LITEONIT                  | 3         | 3      | 0.31%   |
| Apple                     | 3         | 5      | 0.31%   |
| XPG                       | 2         | 4      | 0.21%   |
| Union Memory (Shenzhen)   | 2         | 5      | 0.21%   |
| TO Exter                  | 2         | 2      | 0.21%   |
| Teclast                   | 2         | 2      | 0.21%   |
| PNY                       | 2         | 2      | 0.21%   |
| OCZ                       | 2         | 2      | 0.21%   |
| JMicron                   | 2         | 3      | 0.21%   |
| Intenso                   | 2         | 2      | 0.21%   |
| Hewlett-Packard           | 2         | 1      | 0.21%   |
| ExcelStor                 | 2         | 7      | 0.21%   |
| AMD                       | 2         | 4      | 0.21%   |
| Realtek                   | 1         | 1      | 0.1%    |
| OCZ-VERTEX3               | 1         | 1      | 0.1%    |
| Netac                     | 1         | 3      | 0.1%    |
| Micron/Crucial Technology | 1         | 1      | 0.1%    |
| Mass                      | 1         | 1      | 0.1%    |
| Lenovo                    | 1         | 1      | 0.1%    |
| Innodisk                  | 1         | 1      | 0.1%    |
| IBM/Hitachi               | 1         | 2      | 0.1%    |
| HGST HTS                  | 1         | 1      | 0.1%    |
| GOODRAM                   | 1         | 1      | 0.1%    |
| Gigabyte Technology       | 1         | 4      | 0.1%    |
| FORESEE                   | 1         | 1      | 0.1%    |
| ATP                       | 1         | 2      | 0.1%    |
| ASMedia                   | 1         | 1      | 0.1%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Seagate ST1000LM035-1RK172 1TB      | 16        | 1.54%   |
| Seagate ST500DM002-1BD142 500GB     | 14        | 1.34%   |
| Samsung SSD 860 EVO 250GB           | 13        | 1.25%   |
| Kingston SA400S37120G 120GB SSD     | 13        | 1.25%   |
| Toshiba MQ01ABF050 500GB            | 12        | 1.15%   |
| Toshiba MQ01ABD100 1TB              | 12        | 1.15%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 10        | 0.96%   |
| Samsung SSD 850 EVO 250GB           | 10        | 0.96%   |
| Samsung NVMe SSD Drive 512GB        | 10        | 0.96%   |
| HGST HTS721010A9E630 1TB            | 10        | 0.96%   |
| Samsung SSD 860 EVO 500GB           | 8         | 0.77%   |
| Kingston SA400S37480G 480GB SSD     | 8         | 0.77%   |
| WDC WDS240G2G0A-00JH30 240GB SSD    | 7         | 0.67%   |
| Toshiba DT01ACA100 1TB              | 7         | 0.67%   |
| Seagate ST1000DM010-2EP102 1TB      | 7         | 0.67%   |
| Samsung NVMe SSD Drive 500GB        | 7         | 0.67%   |
| Kingston SA400S37240G 240GB SSD     | 7         | 0.67%   |
| HGST HTS541010A9E680 1TB            | 7         | 0.67%   |
| Samsung SSD 850 PRO 256GB           | 6         | 0.58%   |
| Kingston SV300S37A120G 120GB SSD    | 6         | 0.58%   |
| WDC WD10SPZX-21Z10T0 1TB            | 5         | 0.48%   |
| Unknown MMC Card  64GB              | 5         | 0.48%   |
| Toshiba DT01ACA050 500GB            | 5         | 0.48%   |
| Seagate ST2000DM008-2FR102 2TB      | 5         | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB      | 5         | 0.48%   |
| Samsung SSD 970 EVO 250GB           | 5         | 0.48%   |
| Samsung SSD 860 EVO 1TB             | 5         | 0.48%   |
| Samsung SSD 850 EVO 500GB           | 5         | 0.48%   |
| Intel SSDSC2CW120A3 120GB           | 5         | 0.48%   |
| Hitachi HTS547575A9E384 752GB       | 5         | 0.48%   |
| HGST HTS545050A7E680 500GB          | 5         | 0.48%   |
| A-DATA SU650 240GB SSD              | 5         | 0.48%   |
| A-DATA SU650 120GB SSD              | 5         | 0.48%   |
| Unknown MMC Card  32GB              | 4         | 0.38%   |
| Toshiba NVMe SSD Drive 256GB        | 4         | 0.38%   |
| Toshiba DT01ACA200 2TB              | 4         | 0.38%   |
| Seagate ST9750420AS 752GB           | 4         | 0.38%   |
| Seagate ST9500325AS 500GB           | 4         | 0.38%   |
| Sandisk NVMe SSD Drive 512GB        | 4         | 0.38%   |
| Sandisk NVMe SSD Drive 256GB        | 4         | 0.38%   |
| Samsung SSD 970 EVO Plus 500GB      | 4         | 0.38%   |
| Intel NVMe SSD Drive 512GB          | 4         | 0.38%   |
| Hitachi HDS721616PLA380 160GB       | 4         | 0.38%   |
| Hitachi HDS721050CLA362 500GB       | 4         | 0.38%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 3         | 0.29%   |
| WDC WD5000LPVX-22V0TT0 500GB        | 3         | 0.29%   |
| WDC WD2003FZEX-00SRLA0 2TB          | 3         | 0.29%   |
| WDC WD2002FAEX-007BA0 2TB           | 3         | 0.29%   |
| WDC WD10EZEX-22BN5A0 1TB            | 3         | 0.29%   |
| WDC WD10EZEX-00WN4A0 1TB            | 3         | 0.29%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 3         | 0.29%   |
| Toshiba MQ04ABF100 1TB              | 3         | 0.29%   |
| Toshiba MQ01ABD075 752GB            | 3         | 0.29%   |
| SPCC Solid State Disk 512GB         | 3         | 0.29%   |
| SK Hynix NVMe SSD Drive 256GB       | 3         | 0.29%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 3         | 0.29%   |
| Seagate ST4000DM004-2CV104 4TB      | 3         | 0.29%   |
| Seagate ST3500413AS 500GB           | 3         | 0.29%   |
| Seagate ST3250312AS 250GB           | 3         | 0.29%   |
| Seagate ST31000524AS 1TB            | 3         | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 156       | 222    | 33.48%  |
| WDC                 | 128       | 192    | 27.47%  |
| Toshiba             | 70        | 97     | 15.02%  |
| Hitachi             | 57        | 78     | 12.23%  |
| HGST                | 29        | 43     | 6.22%   |
| Samsung Electronics | 7         | 10     | 1.5%    |
| Fujitsu             | 6         | 10     | 1.29%   |
| MAXTOR              | 5         | 7      | 1.07%   |
| ExcelStor           | 2         | 7      | 0.43%   |
| Unknown             | 1         | 2      | 0.21%   |
| JMicron             | 1         | 2      | 0.21%   |
| IBM/Hitachi         | 1         | 2      | 0.21%   |
| HGST HTS            | 1         | 1      | 0.21%   |
| Hewlett-Packard     | 1         | 1      | 0.21%   |
| ASMedia             | 1         | 1      | 0.21%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 79        | 98     | 24.76%  |
| Kingston            | 46        | 63     | 14.42%  |
| A-DATA Technology   | 29        | 41     | 9.09%   |
| SanDisk             | 24        | 29     | 7.52%   |
| WDC                 | 16        | 24     | 5.02%   |
| Intel               | 16        | 22     | 5.02%   |
| Crucial             | 15        | 24     | 4.7%    |
| Team                | 14        | 15     | 4.39%   |
| China               | 11        | 11     | 3.45%   |
| SPCC                | 9         | 11     | 2.82%   |
| Transcend           | 7         | 8      | 2.19%   |
| Patriot             | 7         | 8      | 2.19%   |
| KingSpec            | 6         | 7      | 1.88%   |
| Toshiba             | 5         | 5      | 1.57%   |
| Micron Technology   | 4         | 4      | 1.25%   |
| LITEON              | 4         | 5      | 1.25%   |
| LITEONIT            | 3         | 3      | 0.94%   |
| Apple               | 3         | 5      | 0.94%   |
| TO Exter            | 2         | 2      | 0.63%   |
| Teclast             | 2         | 2      | 0.63%   |
| PNY                 | 2         | 2      | 0.63%   |
| OCZ                 | 2         | 2      | 0.63%   |
| Intenso             | 2         | 2      | 0.63%   |
| AMD                 | 2         | 4      | 0.63%   |
| Unknown             | 1         | 1      | 0.31%   |
| SK Hynix            | 1         | 1      | 0.31%   |
| OCZ-VERTEX3         | 1         | 1      | 0.31%   |
| Netac               | 1         | 3      | 0.31%   |
| JMicron             | 1         | 1      | 0.31%   |
| GOODRAM             | 1         | 1      | 0.31%   |
| Gigabyte Technology | 1         | 4      | 0.31%   |
| FORESEE             | 1         | 1      | 0.31%   |
| ATP                 | 1         | 2      | 0.31%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 410       | 675    | 46.96%  |
| SSD     | 288       | 412    | 32.99%  |
| NVMe    | 150       | 238    | 17.18%  |
| MMC     | 18        | 24     | 2.06%   |
| Unknown | 7         | 8      | 0.8%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 570       | 1070   | 75.1%   |
| NVMe | 149       | 237    | 19.63%  |
| SAS  | 22        | 26     | 2.9%    |
| MMC  | 18        | 24     | 2.37%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 441       | 676    | 62.2%   |
| 0.51-1.0   | 208       | 317    | 29.34%  |
| 1.01-2.0   | 32        | 44     | 4.51%   |
| 3.01-4.0   | 10        | 23     | 1.41%   |
| 2.01-3.0   | 10        | 17     | 1.41%   |
| 4.01-10.0  | 5         | 7      | 0.71%   |
| 10.01-20.0 | 3         | 3      | 0.42%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 194       | 27.06%  |
| 251-500        | 153       | 21.34%  |
| 501-1000       | 109       | 15.2%   |
| 1001-2000      | 68        | 9.48%   |
| 1-20           | 60        | 8.37%   |
| 51-100         | 51        | 7.11%   |
| 21-50          | 34        | 4.74%   |
| More than 3000 | 22        | 3.07%   |
| Unknown        | 16        | 2.23%   |
| 2001-3000      | 10        | 1.39%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 309       | 40.23%  |
| 21-50          | 129       | 16.8%   |
| 101-250        | 97        | 12.63%  |
| 51-100         | 89        | 11.59%  |
| 251-500        | 47        | 6.12%   |
| 501-1000       | 44        | 5.73%   |
| 1001-2000      | 23        | 2.99%   |
| Unknown        | 16        | 2.08%   |
| More than 3000 | 7         | 0.91%   |
| 2001-3000      | 7         | 0.91%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST9500325AS 500GB             | 3         | 3      | 3.95%   |
| WDC WD6000HLHX-01JJPV0 600GB          | 2         | 3      | 2.63%   |
| WDC WD5000AAKX-603CA0 500GB           | 2         | 7      | 2.63%   |
| Toshiba MQ01ABF050 500GB              | 2         | 2      | 2.63%   |
| Seagate ST500DM002-1BD142 500GB       | 2         | 2      | 2.63%   |
| Seagate ST2000DM001-1CH164 2TB        | 2         | 2      | 2.63%   |
| Intel SSDSC2CW120A3 120GB             | 2         | 2      | 2.63%   |
| WDC WDS100T2B0B-00YS70 1TB SSD        | 1         | 1      | 1.32%   |
| WDC WD5000BEVT-75A0RT0 500GB          | 1         | 1      | 1.32%   |
| WDC WD5000AADS-00S9B0 500GB           | 1         | 2      | 1.32%   |
| WDC WD5000AACS-00G8B1 500GB           | 1         | 1      | 1.32%   |
| WDC WD3200BEVT-80A0RT0 320GB          | 1         | 1      | 1.32%   |
| WDC WD3200AAJS-07M0A0 320GB           | 1         | 2      | 1.32%   |
| WDC WD2500JS-00MHB0 250GB             | 1         | 1      | 1.32%   |
| WDC WD15EARS-00S8B1 1TB               | 1         | 1      | 1.32%   |
| WDC WD10EARS-00MVWB0 1TB              | 1         | 1      | 1.32%   |
| Toshiba MQ01ABD100 1TB                | 1         | 1      | 1.32%   |
| Toshiba MK2552GSX 250GB               | 1         | 3      | 1.32%   |
| Toshiba MK1637GSX 160GB               | 1         | 1      | 1.32%   |
| Toshiba DT01ACA300 3TB                | 1         | 1      | 1.32%   |
| Toshiba DT01ACA050 500GB              | 1         | 1      | 1.32%   |
| Seagate ST9500420AS 500GB             | 1         | 2      | 1.32%   |
| Seagate ST94019A 40GB                 | 1         | 1      | 1.32%   |
| Seagate ST500LT012-9WS142 500GB       | 1         | 1      | 1.32%   |
| Seagate ST500LM021-1KJ152 500GB       | 1         | 1      | 1.32%   |
| Seagate ST500LM000-1EJ162 500GB       | 1         | 1      | 1.32%   |
| Seagate ST380215A 80GB                | 1         | 1      | 1.32%   |
| Seagate ST3500830AS 500GB             | 1         | 1      | 1.32%   |
| Seagate ST3320311CS 320GB             | 1         | 1      | 1.32%   |
| Seagate ST31000333AS 1TB              | 1         | 1      | 1.32%   |
| Seagate ST2000DM001-9YN164 2TB        | 1         | 1      | 1.32%   |
| Seagate ST1000LM035-1RK172 1TB        | 1         | 1      | 1.32%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 1         | 1      | 1.32%   |
| Seagate ST1000LM014-1EJ164 1TB        | 1         | 1      | 1.32%   |
| SanDisk SDSSDX480GG25 480GB           | 1         | 1      | 1.32%   |
| Samsung Electronics SSD 970 EVO 250GB | 1         | 1      | 1.32%   |
| Samsung Electronics SSD 960 EVO 250GB | 1         | 2      | 1.32%   |
| Samsung Electronics SSD 870 EVO 1TB   | 1         | 1      | 1.32%   |
| Patriot P200 512GB SSD                | 1         | 1      | 1.32%   |
| MAXTOR 6Y160M0 160GB                  | 1         | 1      | 1.32%   |
| MAXTOR 6L080P0 82GB                   | 1         | 1      | 1.32%   |
| MAXTOR 2F040L0 41GB                   | 1         | 1      | 1.32%   |
| Kingston SV300S37A120G 120GB SSD      | 1         | 1      | 1.32%   |
| Kingston SUV500240G 240GB SSD         | 1         | 1      | 1.32%   |
| Kingston SA400S37480G 480GB SSD       | 1         | 1      | 1.32%   |
| KingSpec P3-256 256GB SSD             | 1         | 1      | 1.32%   |
| KingSpec P3-128 128GB SSD             | 1         | 1      | 1.32%   |
| Intel SSDSC2BW480A4 480GB             | 1         | 2      | 1.32%   |
| Intel SSDSC2BW120A3F 120GB            | 1         | 1      | 1.32%   |
| Hitachi HTS547550A9E384 500GB         | 1         | 1      | 1.32%   |
| Hitachi HTS545050A7E380 500GB         | 1         | 1      | 1.32%   |
| Hitachi HTS543225L9SA00 250GB         | 1         | 2      | 1.32%   |
| Hitachi HTS543225L9A300 250GB         | 1         | 1      | 1.32%   |
| Hitachi HTS541616J9SA00 160GB         | 1         | 1      | 1.32%   |
| Hitachi HDT722525DLA380 250GB         | 1         | 1      | 1.32%   |
| Hitachi HDT721010SLA360 1TB           | 1         | 1      | 1.32%   |
| Hitachi HDS721010CLA330 1TB           | 1         | 1      | 1.32%   |
| Hitachi HDP725050GLA360 500GB         | 1         | 1      | 1.32%   |
| Fujitsu MJA2160BH G2 160GB            | 1         | 2      | 1.32%   |
| ExcelStor Technology J9250S 250GB     | 1         | 2      | 1.32%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 20        | 21     | 26.32%  |
| WDC                 | 13        | 21     | 17.11%  |
| Hitachi             | 9         | 10     | 11.84%  |
| Toshiba             | 7         | 9      | 9.21%   |
| A-DATA Technology   | 6         | 6      | 7.89%   |
| Intel               | 4         | 5      | 5.26%   |
| Samsung Electronics | 3         | 4      | 3.95%   |
| MAXTOR              | 3         | 3      | 3.95%   |
| Kingston            | 3         | 3      | 3.95%   |
| KingSpec            | 2         | 2      | 2.63%   |
| ExcelStor           | 2         | 3      | 2.63%   |
| SanDisk             | 1         | 1      | 1.32%   |
| Patriot             | 1         | 1      | 1.32%   |
| Fujitsu             | 1         | 2      | 1.32%   |
| China               | 1         | 1      | 1.32%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor    | Computers | Drives | Percent |
|-----------|-----------|--------|---------|
| Seagate   | 20        | 21     | 37.04%  |
| WDC       | 12        | 20     | 22.22%  |
| Hitachi   | 9         | 10     | 16.67%  |
| Toshiba   | 7         | 9      | 12.96%  |
| MAXTOR    | 3         | 3      | 5.56%   |
| ExcelStor | 2         | 3      | 3.7%    |
| Fujitsu   | 1         | 2      | 1.85%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 51        | 68     | 70.83%  |
| SSD  | 19        | 21     | 26.39%  |
| NVMe | 2         | 3      | 2.78%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                        | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| WDC WD1600BEKT-75PVMT0 160GB | 1         | 1      | 50%     |
| HGST HTS545050A7E680 500GB   | 1         | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor | Computers | Drives | Percent |
|--------|-----------|--------|---------|
| WDC    | 1         | 1      | 50%     |
| HGST   | 1         | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 435       | 846    | 59.1%   |
| Works    | 232       | 417    | 31.52%  |
| Malfunc  | 67        | 92     | 9.1%    |
| Failed   | 2         | 2      | 0.27%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 508       | 62.56%  |
| AMD                              | 107       | 13.18%  |
| Samsung Electronics              | 64        | 7.88%   |
| Sandisk                          | 17        | 2.09%   |
| JMicron Technology               | 16        | 1.97%   |
| Nvidia                           | 14        | 1.72%   |
| SK Hynix                         | 13        | 1.6%    |
| Toshiba America Info Systems     | 10        | 1.23%   |
| Phison Electronics               | 8         | 0.99%   |
| Marvell Technology Group         | 8         | 0.99%   |
| KIOXIA                           | 8         | 0.99%   |
| Kingston Technology Company      | 8         | 0.99%   |
| Realtek Semiconductor            | 7         | 0.86%   |
| ASMedia Technology               | 6         | 0.74%   |
| ADATA Technology                 | 6         | 0.74%   |
| Silicon Motion                   | 3         | 0.37%   |
| Union Memory (Shenzhen)          | 2         | 0.25%   |
| Micron/Crucial Technology        | 2         | 0.25%   |
| Micron Technology                | 2         | 0.25%   |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |
| Lenovo                           | 1         | 0.12%   |
| Integrated Technology Express    | 1         | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 67        | 6.99%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 45        | 4.69%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 40        | 4.17%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 32        | 3.34%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 30        | 3.13%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 29        | 3.02%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 28        | 2.92%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 23        | 2.4%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 23        | 2.4%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 20        | 2.09%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                   | 18        | 1.88%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 16        | 1.67%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 14        | 1.46%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 14        | 1.46%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 13        | 1.36%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 13        | 1.36%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 13        | 1.36%   |
| Intel SATA Controller [RAID mode]                                                       | 11        | 1.15%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 11        | 1.15%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 11        | 1.15%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 10        | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 10        | 1.04%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 10        | 1.04%   |
| AMD 400 Series Chipset SATA Controller                                                  | 10        | 1.04%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 9         | 0.94%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 9         | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 9         | 0.94%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 9         | 0.94%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 9         | 0.94%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 8         | 0.83%   |
| Samsung NVMe SSD Controller 980                                                         | 8         | 0.83%   |
| Intel SSD 660P Series                                                                   | 8         | 0.83%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 8         | 0.83%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 8         | 0.83%   |
| KIOXIA Non-Volatile memory controller                                                   | 7         | 0.73%   |
| JMicron JMB368 IDE controller                                                           | 7         | 0.73%   |
| AMD FCH IDE Controller                                                                  | 7         | 0.73%   |
| Nvidia MCP61 SATA Controller                                                            | 6         | 0.63%   |
| Nvidia MCP61 IDE                                                                        | 6         | 0.63%   |
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                       | 6         | 0.63%   |
| Intel C610/X99 series chipset 6-Port SATA Controller [AHCI mode]                        | 6         | 0.63%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 6         | 0.63%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [IDE mode]                           | 6         | 0.63%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA IDE Controller                           | 6         | 0.63%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 6         | 0.63%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 6         | 0.63%   |
| SK Hynix Gold P31 SSD                                                                   | 5         | 0.52%   |
| Sandisk WD Blue SN550 NVMe SSD                                                          | 5         | 0.52%   |
| Realtek Realtek Non-Volatile memory controller                                          | 5         | 0.52%   |
| Intel SSD Pro 7600p/760p/E 6100p Series                                                 | 5         | 0.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 5         | 0.52%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 5         | 0.52%   |
| Intel 5 Series/3400 Series Chipset 2 port SATA IDE Controller                           | 5         | 0.52%   |
| Intel 4 Series Chipset PT IDER Controller                                               | 5         | 0.52%   |
| AMD SB600 Non-Raid-5 SATA                                                               | 5         | 0.52%   |
| AMD SB600 IDE                                                                           | 5         | 0.52%   |
| AMD 300 Series Chipset SATA Controller                                                  | 5         | 0.52%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 4         | 0.42%   |
| Sandisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 4         | 0.42%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 0.42%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 491       | 59.52%  |
| NVMe | 154       | 18.67%  |
| IDE  | 135       | 16.36%  |
| RAID | 44        | 5.33%   |
| SAS  | 1         | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 538       | 80.42%  |
| AMD    | 131       | 19.58%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| Intel Core i5-2520M CPU @ 2.50GHz        | 11        | 1.64%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz       | 9         | 1.34%   |
| Intel Core i7-8750H CPU @ 2.20GHz        | 8         | 1.19%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz       | 8         | 1.19%   |
| Intel Core i7-10510U CPU @ 1.80GHz       | 8         | 1.19%   |
| Intel Core i5-3230M CPU @ 2.60GHz        | 7         | 1.04%   |
| Intel Core i7-8565U CPU @ 1.80GHz        | 6         | 0.89%   |
| Intel Core i5-8250U CPU @ 1.60GHz        | 6         | 0.89%   |
| Intel Core i5-5200U CPU @ 2.20GHz        | 6         | 0.89%   |
| Intel Pentium CPU N4200 @ 1.10GHz        | 5         | 0.75%   |
| Intel Pentium CPU 2020M @ 2.40GHz        | 5         | 0.75%   |
| Intel Core i7-9750H CPU @ 2.60GHz        | 5         | 0.75%   |
| Intel Core i7-8550U CPU @ 1.80GHz        | 5         | 0.75%   |
| Intel Core i7-3630QM CPU @ 2.40GHz       | 5         | 0.75%   |
| Intel Core i7-2670QM CPU @ 2.20GHz       | 5         | 0.75%   |
| Intel Core i5-8265U CPU @ 1.60GHz        | 5         | 0.75%   |
| Intel Core i5-3470 CPU @ 3.20GHz         | 5         | 0.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz        | 5         | 0.75%   |
| Intel Celeron N4000 CPU @ 1.10GHz        | 5         | 0.75%   |
| AMD Ryzen 3 3250U with Radeon Graphics   | 5         | 0.75%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz | 4         | 0.6%    |
| Intel Pentium CPU G645 @ 2.90GHz         | 4         | 0.6%    |
| Intel Core i7-7500U CPU @ 2.70GHz        | 4         | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz        | 4         | 0.6%    |
| Intel Core i7-5600U CPU @ 2.60GHz        | 4         | 0.6%    |
| Intel Core i7-5500U CPU @ 2.40GHz        | 4         | 0.6%    |
| Intel Core i5-5300U CPU @ 2.30GHz        | 4         | 0.6%    |
| Intel Core i5-3340M CPU @ 2.70GHz        | 4         | 0.6%    |
| Intel Core i5 CPU M 520 @ 2.40GHz        | 4         | 0.6%    |
| Intel Core i3-5005U CPU @ 2.00GHz        | 4         | 0.6%    |
| Intel Core i3-3110M CPU @ 2.40GHz        | 4         | 0.6%    |
| Intel Core i3 CPU M 370 @ 2.40GHz        | 4         | 0.6%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz    | 4         | 0.6%    |
| Intel Core 2 Duo CPU P8700 @ 2.53GHz     | 4         | 0.6%    |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz     | 4         | 0.6%    |
| AMD Ryzen 5 5600X 6-Core Processor       | 4         | 0.6%    |
| AMD Ryzen 5 1600 Six-Core Processor      | 4         | 0.6%    |
| AMD FX-6300 Six-Core Processor           | 4         | 0.6%    |
| Intel Core i7-4810MQ CPU @ 2.80GHz       | 3         | 0.45%   |
| Intel Core i7-4710HQ CPU @ 2.50GHz       | 3         | 0.45%   |
| Intel Core i7-10750H CPU @ 2.60GHz       | 3         | 0.45%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz       | 3         | 0.45%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz       | 3         | 0.45%   |
| Intel Core i5-4690 CPU @ 3.50GHz         | 3         | 0.45%   |
| Intel Core i5-4590 CPU @ 3.30GHz         | 3         | 0.45%   |
| Intel Core i5-4460 CPU @ 3.20GHz         | 3         | 0.45%   |
| Intel Core i5-4300U CPU @ 1.90GHz        | 3         | 0.45%   |
| Intel Core i5-3570K CPU @ 3.40GHz        | 3         | 0.45%   |
| Intel Core i5-2450M CPU @ 2.50GHz        | 3         | 0.45%   |
| Intel Core i5-2410M CPU @ 2.30GHz        | 3         | 0.45%   |
| Intel Core i5-2400 CPU @ 3.10GHz         | 3         | 0.45%   |
| Intel Core i5 CPU M 560 @ 2.67GHz        | 3         | 0.45%   |
| Intel Core i3-8145U CPU @ 2.10GHz        | 3         | 0.45%   |
| Intel Core i3-6006U CPU @ 2.00GHz        | 3         | 0.45%   |
| Intel Core i3-3120M CPU @ 2.50GHz        | 3         | 0.45%   |
| Intel Core 2 Duo CPU P8400 @ 2.26GHz     | 3         | 0.45%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz     | 3         | 0.45%   |
| Intel Core 2 Duo CPU E4500 @ 2.20GHz     | 3         | 0.45%   |
| Intel Core 2 CPU T7200 @ 2.00GHz         | 3         | 0.45%   |
| Intel Celeron CPU N3050 @ 1.60GHz        | 3         | 0.45%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 147       | 21.91%  |
| Intel Core i7           | 146       | 21.76%  |
| Intel Core i3           | 52        | 7.75%   |
| Intel Core 2 Duo        | 40        | 5.96%   |
| Intel Pentium           | 35        | 5.22%   |
| Intel Celeron           | 32        | 4.77%   |
| AMD Ryzen 5             | 28        | 4.17%   |
| AMD Ryzen 7             | 18        | 2.68%   |
| Intel Xeon              | 12        | 1.79%   |
| Intel Core 2 Quad       | 12        | 1.79%   |
| Other                   | 11        | 1.64%   |
| Intel Pentium Dual-Core | 9         | 1.34%   |
| Intel Atom              | 9         | 1.34%   |
| Intel Pentium Dual      | 8         | 1.19%   |
| AMD Ryzen 3             | 8         | 1.19%   |
| AMD Athlon 64 X2        | 8         | 1.19%   |
| Intel Core 2            | 7         | 1.04%   |
| AMD FX                  | 7         | 1.04%   |
| AMD Ryzen 9             | 6         | 0.89%   |
| AMD Ryzen 7 PRO         | 5         | 0.75%   |
| AMD Athlon 64           | 5         | 0.75%   |
| AMD A8                  | 5         | 0.75%   |
| Intel Pentium Silver    | 4         | 0.6%    |
| AMD E1                  | 4         | 0.6%    |
| AMD Phenom II X4        | 3         | 0.45%   |
| AMD Athlon II X4        | 3         | 0.45%   |
| AMD Athlon II X2        | 3         | 0.45%   |
| AMD A6                  | 3         | 0.45%   |
| Intel Pentium M         | 2         | 0.3%    |
| Intel Pentium Gold      | 2         | 0.3%    |
| Intel Genuine           | 2         | 0.3%    |
| Intel Core i9           | 2         | 0.3%    |
| AMD Sempron             | 2         | 0.3%    |
| AMD Ryzen 5 PRO         | 2         | 0.3%    |
| AMD Phenom II X6        | 2         | 0.3%    |
| AMD Phenom              | 2         | 0.3%    |
| AMD Athlon X4           | 2         | 0.3%    |
| AMD A10                 | 2         | 0.3%    |
| Intel Pentium D         | 1         | 0.15%   |
| Intel Mobile Pentium 4  | 1         | 0.15%   |
| Intel Core m3           | 1         | 0.15%   |
| Intel Core M            | 1         | 0.15%   |
| Intel Core Duo          | 1         | 0.15%   |
| Intel Core 2 Solo       | 1         | 0.15%   |
| Intel Celeron M         | 1         | 0.15%   |
| Intel Celeron Dual-Core | 1         | 0.15%   |
| AMD Turion 64 X2 Mobile | 1         | 0.15%   |
| AMD Turion 64 Mobile    | 1         | 0.15%   |
| AMD Ryzen Embedded      | 1         | 0.15%   |
| AMD Phenom II X3        | 1         | 0.15%   |
| AMD Phenom II X2        | 1         | 0.15%   |
| AMD Phenom II           | 1         | 0.15%   |
| AMD GX                  | 1         | 0.15%   |
| AMD E2                  | 1         | 0.15%   |
| AMD E                   | 1         | 0.15%   |
| AMD C-50                | 1         | 0.15%   |
| AMD Athlon II X3        | 1         | 0.15%   |
| AMD Athlon II Dual-Core | 1         | 0.15%   |
| AMD A4                  | 1         | 0.15%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 320       | 47.62%  |
| 4       | 226       | 33.63%  |
| 6       | 58        | 8.63%   |
| 8       | 26        | 3.87%   |
| 1       | 22        | 3.27%   |
| 3       | 9         | 1.34%   |
| 12      | 7         | 1.04%   |
| Unknown | 2         | 0.3%    |
| 16      | 1         | 0.15%   |
| 14      | 1         | 0.15%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 667       | 99.7%   |
| 2      | 2         | 0.3%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 403       | 59.88%  |
| 1       | 268       | 39.82%  |
| Unknown | 2         | 0.3%    |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 640       | 94.67%  |
| Unknown        | 26        | 3.85%   |
| 32-bit         | 10        | 1.48%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 137       | 19.63%  |
| 0x306a9    | 55        | 7.88%   |
| 0x206a7    | 52        | 7.45%   |
| 0x306c3    | 39        | 5.59%   |
| 0x1067a    | 28        | 4.01%   |
| 0x806ec    | 21        | 3.01%   |
| 0x306d4    | 21        | 3.01%   |
| 0x906ea    | 20        | 2.87%   |
| 0x506e3    | 19        | 2.72%   |
| 0x906e9    | 17        | 2.44%   |
| 0x20655    | 17        | 2.44%   |
| 0x6fd      | 15        | 2.15%   |
| 0x40651    | 15        | 2.15%   |
| 0x406e3    | 14        | 2.01%   |
| 0x806ea    | 12        | 1.72%   |
| 0x10676    | 12        | 1.72%   |
| 0x706a1    | 9         | 1.29%   |
| 0x506c9    | 9         | 1.29%   |
| 0x010000c8 | 9         | 1.29%   |
| 0x6fb      | 8         | 1.15%   |
| 0x08108109 | 8         | 1.15%   |
| 0x08108102 | 7         | 1%      |
| 0x806e9    | 6         | 0.86%   |
| 0x6f6      | 6         | 0.86%   |
| 0x306f2    | 6         | 0.86%   |
| 0xa0652    | 5         | 0.72%   |
| 0x806eb    | 5         | 0.72%   |
| 0x806c1    | 5         | 0.72%   |
| 0x706e5    | 5         | 0.72%   |
| 0x406c3    | 5         | 0.72%   |
| 0x106e5    | 4         | 0.57%   |
| 0x106c2    | 4         | 0.57%   |
| 0x0a201009 | 4         | 0.57%   |
| 0x08600106 | 4         | 0.57%   |
| 0x08600103 | 4         | 0.57%   |
| 0x0800820d | 4         | 0.57%   |
| 0x0700010f | 4         | 0.57%   |
| 0x06000852 | 4         | 0.57%   |
| 0xa0671    | 3         | 0.43%   |
| 0xa0655    | 3         | 0.43%   |
| 0x30678    | 3         | 0.43%   |
| 0x08701013 | 3         | 0.43%   |
| 0x06003106 | 3         | 0.43%   |
| 0x06001119 | 3         | 0.43%   |
| 0x03000027 | 3         | 0.43%   |
| 0x6f2      | 2         | 0.29%   |
| 0x6d8      | 2         | 0.29%   |
| 0x406c4    | 2         | 0.29%   |
| 0x206c2    | 2         | 0.29%   |
| 0x0a50000c | 2         | 0.29%   |
| 0x0a201204 | 2         | 0.29%   |
| 0x08608103 | 2         | 0.29%   |
| 0x08600104 | 2         | 0.29%   |
| 0x08001138 | 2         | 0.29%   |
| 0x06006704 | 2         | 0.29%   |
| 0x010000db | 2         | 0.29%   |
| 0xf64      | 1         | 0.14%   |
| 0x906ed    | 1         | 0.14%   |
| 0x906eb    | 1         | 0.14%   |
| 0x90672    | 1         | 0.14%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 99        | 14.78%  |
| Haswell          | 71        | 10.6%   |
| IvyBridge        | 68        | 10.15%  |
| SandyBridge      | 61        | 9.1%    |
| Penryn           | 47        | 7.01%   |
| Skylake          | 36        | 5.37%   |
| Core             | 34        | 5.07%   |
| Broadwell        | 25        | 3.73%   |
| Zen+             | 24        | 3.58%   |
| Westmere         | 23        | 3.43%   |
| Zen 2            | 21        | 3.13%   |
| K10              | 18        | 2.69%   |
| K8 Hammer        | 16        | 2.39%   |
| Zen 3            | 12        | 1.79%   |
| Silvermont       | 11        | 1.64%   |
| Piledriver       | 11        | 1.64%   |
| Goldmont plus    | 11        | 1.64%   |
| CometLake        | 10        | 1.49%   |
| Zen              | 9         | 1.34%   |
| Goldmont         | 9         | 1.34%   |
| IceLake          | 7         | 1.04%   |
| TigerLake        | 6         | 0.9%    |
| P6               | 5         | 0.75%   |
| Bonnell          | 5         | 0.75%   |
| Unknown          | 5         | 0.75%   |
| Nehalem          | 4         | 0.6%    |
| Jaguar           | 4         | 0.6%    |
| Excavator        | 4         | 0.6%    |
| Steamroller      | 3         | 0.45%   |
| K10 Llano        | 3         | 0.45%   |
| Puma             | 2         | 0.3%    |
| NetBurst         | 2         | 0.3%    |
| Bobcat           | 2         | 0.3%    |
| Bulldozer        | 1         | 0.15%   |
| Alderlake Hybrid | 1         | 0.15%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 411       | 49.16%  |
| Nvidia                           | 242       | 28.95%  |
| AMD                              | 182       | 21.77%  |
| Silicon Integrated Systems [SiS] | 1         | 0.12%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 45        | 5.23%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 44        | 5.11%   |
| Intel HD Graphics 5500                                                                   | 22        | 2.56%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 18        | 2.09%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 18        | 2.09%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 18        | 2.09%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 17        | 1.97%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 17        | 1.97%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 16        | 1.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 16        | 1.86%   |
| Intel HD Graphics 630                                                                    | 15        | 1.74%   |
| AMD Renoir                                                                               | 14        | 1.63%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 13        | 1.51%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 12        | 1.39%   |
| Intel UHD Graphics 620                                                                   | 12        | 1.39%   |
| Intel Core Processor Integrated Graphics Controller                                      | 12        | 1.39%   |
| Intel HD Graphics 530                                                                    | 11        | 1.28%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                                  | 10        | 1.16%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 10        | 1.16%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 9         | 1.05%   |
| Nvidia GM108M [GeForce 840M]                                                             | 8         | 0.93%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 7         | 0.81%   |
| Nvidia GM107M [GeForce GTX 960M]                                                         | 7         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 7         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 7         | 0.81%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 7         | 0.81%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 7         | 0.81%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 7         | 0.81%   |
| Nvidia GT218 [GeForce 210]                                                               | 6         | 0.7%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 6         | 0.7%    |
| Intel HD Graphics 620                                                                    | 6         | 0.7%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 6         | 0.7%    |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 5         | 0.58%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 5         | 0.58%   |
| Nvidia GP104 [GeForce GTX 1070]                                                          | 5         | 0.58%   |
| Nvidia GM108M [GeForce MX130]                                                            | 5         | 0.58%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 5         | 0.58%   |
| Nvidia GF119 [GeForce GT 610]                                                            | 5         | 0.58%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 5         | 0.58%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Integrated Graphics Controller       | 5         | 0.58%   |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller                | 5         | 0.58%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                                  | 5         | 0.58%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                               | 5         | 0.58%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                               | 4         | 0.46%   |
| Nvidia TU117M                                                                            | 4         | 0.46%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 4         | 0.46%   |
| Nvidia GM108M [GeForce 940MX]                                                            | 4         | 0.46%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 4         | 0.46%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 4         | 0.46%   |
| Nvidia GF119 [GeForce GT 620 OEM]                                                        | 4         | 0.46%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 4         | 0.46%   |
| Nvidia GF108M [GeForce GT 540M]                                                          | 4         | 0.46%   |
| Nvidia GF106GLM [Quadro 2000M]                                                           | 4         | 0.46%   |
| Nvidia G96C [GeForce 9500 GT]                                                            | 4         | 0.46%   |
| Intel Mobile 945GSE Express Integrated Graphics Controller                               | 4         | 0.46%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                                   | 4         | 0.46%   |
| Intel HD Graphics 500                                                                    | 4         | 0.46%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 4         | 0.46%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 4         | 0.46%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 4         | 0.46%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 255       | 37.56%  |
| 1 x AMD        | 141       | 20.77%  |
| Intel + Nvidia | 120       | 17.67%  |
| 1 x Nvidia     | 117       | 17.23%  |
| Intel + AMD    | 29        | 4.27%   |
| 2 x AMD        | 10        | 1.47%   |
| AMD + Nvidia   | 6         | 0.88%   |
| 1 x SiS        | 1         | 0.15%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 522       | 76.65%  |
| Proprietary | 131       | 19.24%  |
| Unknown     | 28        | 4.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 333       | 47.57%  |
| 1.01-2.0   | 129       | 18.43%  |
| 0.01-0.5   | 71        | 10.14%  |
| 3.01-4.0   | 66        | 9.43%   |
| 0.51-1.0   | 56        | 8%      |
| 7.01-8.0   | 25        | 3.57%   |
| 5.01-6.0   | 12        | 1.71%   |
| 2.01-3.0   | 4         | 0.57%   |
| 8.01-16.0  | 3         | 0.43%   |
| 16.01-24.0 | 1         | 0.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| LG Display              | 123       | 17.13%  |
| Samsung Electronics     | 73        | 10.17%  |
| AU Optronics            | 72        | 10.03%  |
| Chimei Innolux          | 51        | 7.1%    |
| Dell                    | 49        | 6.82%   |
| BOE                     | 45        | 6.27%   |
| Goldstar                | 34        | 4.74%   |
| Philips                 | 32        | 4.46%   |
| Acer                    | 26        | 3.62%   |
| Ancor Communications    | 20        | 2.79%   |
| Lenovo                  | 19        | 2.65%   |
| Hewlett-Packard         | 17        | 2.37%   |
| Chi Mei Optoelectronics | 15        | 2.09%   |
| BenQ                    | 14        | 1.95%   |
| AOC                     | 11        | 1.53%   |
| LG Philips              | 9         | 1.25%   |
| Fujitsu Siemens         | 7         | 0.97%   |
| Sony                    | 6         | 0.84%   |
| Sharp                   | 6         | 0.84%   |
| Panasonic               | 6         | 0.84%   |
| LG Electronics          | 6         | 0.84%   |
| PANDA                   | 5         | 0.7%    |
| Apple                   | 5         | 0.7%    |
| NEC Computers           | 4         | 0.56%   |
| HannStar                | 4         | 0.56%   |
| Eizo                    | 4         | 0.56%   |
| CPT                     | 4         | 0.56%   |
| ViewSonic               | 3         | 0.42%   |
| Vestel Elektronik       | 3         | 0.42%   |
| Unknown                 | 3         | 0.42%   |
| WST                     | 2         | 0.28%   |
| Vestel                  | 2         | 0.28%   |
| Toshiba                 | 2         | 0.28%   |
| MSI                     | 2         | 0.28%   |
| Lenovo Group Limited    | 2         | 0.28%   |
| InnoLux Display         | 2         | 0.28%   |
| Gigabyte Technology     | 2         | 0.28%   |
| Belinea                 | 2         | 0.28%   |
| ASUSTek Computer        | 2         | 0.28%   |
| ___                     | 1         | 0.14%   |
| WIN                     | 1         | 0.14%   |
| TSL                     | 1         | 0.14%   |
| TAR                     | 1         | 0.14%   |
| SUNNY                   | 1         | 0.14%   |
| Seiko/Epson             | 1         | 0.14%   |
| PRISM+                  | 1         | 0.14%   |
| PEGA                    | 1         | 0.14%   |
| Packard Bell            | 1         | 0.14%   |
| Optoma                  | 1         | 0.14%   |
| NUG                     | 1         | 0.14%   |
| NCS                     | 1         | 0.14%   |
| KTC                     | 1         | 0.14%   |
| IBM                     | 1         | 0.14%   |
| HPN                     | 1         | 0.14%   |
| HKC                     | 1         | 0.14%   |
| Hitachi                 | 1         | 0.14%   |
| eMachines               | 1         | 0.14%   |
| Elo Touch               | 1         | 0.14%   |
| Denver                  | 1         | 0.14%   |
| CSO                     | 1         | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| LG Display LCD Monitor LGD033A 1366x768 344x194mm 15.5-inch              | 12        | 1.62%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 6         | 0.81%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 6         | 0.81%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 5         | 0.67%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 5         | 0.67%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 5         | 0.67%   |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch    | 4         | 0.54%   |
| LG Display LCD Monitor LGD053F 1920x1080 344x194mm 15.5-inch             | 4         | 0.54%   |
| LG Display LCD Monitor LGD046F 1920x1080 344x194mm 15.5-inch             | 4         | 0.54%   |
| BOE LCD Monitor BOE0802 1920x1080 344x193mm 15.5-inch                    | 4         | 0.54%   |
| AU Optronics LCD Monitor AUO70EC 1366x768 344x193mm 15.5-inch            | 4         | 0.54%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch           | 4         | 0.54%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 4         | 0.54%   |
| AU Optronics LCD Monitor AUO21EC 1366x768 344x194mm 15.5-inch            | 4         | 0.54%   |
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x390mm 31.5-inch     | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch     | 3         | 0.4%    |
| Samsung Electronics LCD Monitor SEC3741 1366x768 309x174mm 14.0-inch     | 3         | 0.4%    |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                  | 3         | 0.4%    |
| LG Display LCD Monitor LGD0608 1920x1080 309x174mm 14.0-inch             | 3         | 0.4%    |
| LG Display LCD Monitor LGD0590 1920x1080 344x194mm 15.5-inch             | 3         | 0.4%    |
| LG Display LCD Monitor LGD0395 1366x768 344x194mm 15.5-inch              | 3         | 0.4%    |
| LG Display LCD Monitor LGD038E 1366x768 344x194mm 15.5-inch              | 3         | 0.4%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 3         | 0.4%    |
| LG Display LCD Monitor LGD02D3 1366x768 277x156mm 12.5-inch              | 3         | 0.4%    |
| Hewlett-Packard w1907 HWP26A2 1440x900 408x255mm 18.9-inch               | 3         | 0.4%    |
| Dell P2419H DELD0DA 1920x1080 527x296mm 23.8-inch                        | 3         | 0.4%    |
| Dell P2314H DEL4099 1920x1080 509x286mm 23.0-inch                        | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 3         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14B1 1920x1080 308x173mm 13.9-inch         | 3         | 0.4%    |
| AU Optronics LCD Monitor AUO243D 1920x1080 309x173mm 13.9-inch           | 3         | 0.4%    |
| Acer G257HL ACR0415 1920x1080 553x309mm 24.9-inch                        | 3         | 0.4%    |
| Samsung Electronics SMXL2270HD SAM072B 1920x1080 476x268mm 21.5-inch     | 2         | 0.27%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 520x290mm 23.4-inch        | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC5244 1600x900 360x210mm 16.4-inch     | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC3645 1280x800 331x207mm 15.4-inch     | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SEC324A 1366x768 344x194mm 15.5-inch     | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SAM7017 3840x2160 950x540mm 43.0-inch    | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SAM0F13 3840x2160 1872x1053mm 84.6-inch  | 2         | 0.27%   |
| Samsung Electronics LCD Monitor SAM07C5 1920x1080 890x500mm 40.2-inch    | 2         | 0.27%   |
| Philips 234CL PHLC066 1920x1080 509x286mm 23.0-inch                      | 2         | 0.27%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                  | 2         | 0.27%   |
| NEC Computers EA221WM NEC673D 1680x1050 474x296mm 22.0-inch              | 2         | 0.27%   |
| LG Philips LP154WX4-TLC8 LPL0120 1280x800 331x207mm 15.4-inch            | 2         | 0.27%   |
| LG Display LP156WH2-TLAA LGD0230 1366x768 344x194mm 15.5-inch            | 2         | 0.27%   |
| LG Display LCD Monitor LGD063A 1920x1080 344x194mm 15.5-inch             | 2         | 0.27%   |
| LG Display LCD Monitor LGD05EC 1920x1080 309x174mm 14.0-inch             | 2         | 0.27%   |
| LG Display LCD Monitor LGD05E9 1920x1080 294x165mm 13.3-inch             | 2         | 0.27%   |
| LG Display LCD Monitor LGD05E0 1920x1080 382x215mm 17.3-inch             | 2         | 0.27%   |
| LG Display LCD Monitor LGD05D0 1920x1080 344x194mm 15.5-inch             | 2         | 0.27%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch             | 2         | 0.27%   |
| LG Display LCD Monitor LGD04E8 1920x1080 380x210mm 17.1-inch             | 2         | 0.27%   |
| LG Display LCD Monitor LGD04B9 1920x1080 344x194mm 15.5-inch             | 2         | 0.27%   |
| LG Display LCD Monitor LGD048A 1920x1080 276x156mm 12.5-inch             | 2         | 0.27%   |
| LG Display LCD Monitor LGD0469 1920x1080 382x215mm 17.3-inch             | 2         | 0.27%   |
| LG Display LCD Monitor LGD0437 1920x1080 276x156mm 12.5-inch             | 2         | 0.27%   |
| LG Display LCD Monitor LGD03AB 1366x768 344x194mm 15.5-inch              | 2         | 0.27%   |
| LG Display LCD Monitor LGD033E 1366x768 309x174mm 14.0-inch              | 2         | 0.27%   |
| LG Display LCD Monitor LGD0306 1600x900 310x174mm 14.0-inch              | 2         | 0.27%   |
| LG Display LCD Monitor LGD02EC 1366x768 293x165mm 13.2-inch              | 2         | 0.27%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch              | 2         | 0.27%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 308       | 44.25%  |
| 1366x768 (WXGA)    | 133       | 19.11%  |
| 1680x1050 (WSXGA+) | 33        | 4.74%   |
| 1280x1024 (SXGA)   | 32        | 4.6%    |
| 1600x900 (HD+)     | 28        | 4.02%   |
| 3840x2160 (4K)     | 26        | 3.74%   |
| 2560x1440 (QHD)    | 26        | 3.74%   |
| 1280x800 (WXGA)    | 24        | 3.45%   |
| 1440x900 (WXGA+)   | 16        | 2.3%    |
| 1920x1200 (WUXGA)  | 12        | 1.72%   |
| Unknown            | 12        | 1.72%   |
| 3840x1080          | 4         | 0.57%   |
| 1024x768 (XGA)     | 4         | 0.57%   |
| 1024x600           | 4         | 0.57%   |
| 3840x1200          | 3         | 0.43%   |
| 3440x1440          | 3         | 0.43%   |
| 2560x1600          | 3         | 0.43%   |
| 2560x1080          | 3         | 0.43%   |
| 1600x1200          | 3         | 0.43%   |
| 1360x768           | 3         | 0.43%   |
| 1400x1050          | 2         | 0.29%   |
| 1280x720 (HD)      | 2         | 0.29%   |
| 6784x2160          | 1         | 0.14%   |
| 6400x1080          | 1         | 0.14%   |
| 5120x1080          | 1         | 0.14%   |
| 4240x1440          | 1         | 0.14%   |
| 3600x1200          | 1         | 0.14%   |
| 3200x1800 (QHD+)   | 1         | 0.14%   |
| 3200x1080          | 1         | 0.14%   |
| 2160x1440          | 1         | 0.14%   |
| 2048x1152          | 1         | 0.14%   |
| 1921x1080          | 1         | 0.14%   |
| 1920x540           | 1         | 0.14%   |
| 1820x1023          | 1         | 0.14%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 231       | 32.17%  |
| 13      | 53        | 7.38%   |
| 24      | 47        | 6.55%   |
| 17      | 44        | 6.13%   |
| 21      | 43        | 5.99%   |
| 23      | 41        | 5.71%   |
| 14      | 41        | 5.71%   |
| Unknown | 39        | 5.43%   |
| 27      | 29        | 4.04%   |
| 19      | 23        | 3.2%    |
| 12      | 20        | 2.79%   |
| 22      | 19        | 2.65%   |
| 20      | 14        | 1.95%   |
| 84      | 10        | 1.39%   |
| 18      | 10        | 1.39%   |
| 31      | 9         | 1.25%   |
| 54      | 6         | 0.84%   |
| 34      | 6         | 0.84%   |
| 10      | 6         | 0.84%   |
| 25      | 5         | 0.7%    |
| 40      | 4         | 0.56%   |
| 11      | 4         | 0.56%   |
| 72      | 3         | 0.42%   |
| 26      | 2         | 0.28%   |
| 16      | 2         | 0.28%   |
| 75      | 1         | 0.14%   |
| 65      | 1         | 0.14%   |
| 52      | 1         | 0.14%   |
| 37      | 1         | 0.14%   |
| 33      | 1         | 0.14%   |
| 32      | 1         | 0.14%   |
| 28      | 1         | 0.14%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 314       | 43.85%  |
| 501-600     | 116       | 16.2%   |
| 401-500     | 95        | 13.27%  |
| 201-300     | 52        | 7.26%   |
| 351-400     | 49        | 6.84%   |
| Unknown     | 39        | 5.45%   |
| 601-700     | 16        | 2.23%   |
| 1501-2000   | 14        | 1.96%   |
| 701-800     | 8         | 1.12%   |
| 1001-1500   | 8         | 1.12%   |
| 801-900     | 5         | 0.7%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 479       | 73.24%  |
| 16/10   | 89        | 13.61%  |
| Unknown | 35        | 5.35%   |
| 5/4     | 29        | 4.43%   |
| 4/3     | 11        | 1.68%   |
| 21/9    | 6         | 0.92%   |
| 3/2     | 3         | 0.46%   |
| 6/5     | 1         | 0.15%   |
| 32/9    | 1         | 0.15%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 230       | 32.39%  |
| 201-250        | 118       | 16.62%  |
| 81-90          | 75        | 10.56%  |
| 151-200        | 48        | 6.76%   |
| Unknown        | 39        | 5.49%   |
| 301-350        | 31        | 4.37%   |
| 121-130        | 24        | 3.38%   |
| 141-150        | 23        | 3.24%   |
| More than 1000 | 22        | 3.1%    |
| 71-80          | 21        | 2.96%   |
| 251-300        | 21        | 2.96%   |
| 61-70          | 18        | 2.54%   |
| 351-500        | 18        | 2.54%   |
| 41-50          | 6         | 0.85%   |
| 501-1000       | 5         | 0.7%    |
| 51-60          | 4         | 0.56%   |
| 131-140        | 4         | 0.56%   |
| 111-120        | 2         | 0.28%   |
| 91-100         | 1         | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 230       | 33%     |
| 121-160       | 197       | 28.26%  |
| 101-120       | 182       | 26.11%  |
| Unknown       | 39        | 5.6%    |
| 161-240       | 28        | 4.02%   |
| 1-50          | 15        | 2.15%   |
| More than 240 | 6         | 0.86%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 554       | 80.41%  |
| 2     | 97        | 14.08%  |
| 0     | 31        | 4.5%    |
| 3     | 6         | 0.87%   |
| 4     | 1         | 0.15%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Realtek Semiconductor                 | 355       | 34.77%  |
| Intel                                 | 338       | 33.1%   |
| Qualcomm Atheros                      | 121       | 11.85%  |
| Broadcom                              | 50        | 4.9%    |
| Broadcom Limited                      | 22        | 2.15%   |
| Ralink                                | 17        | 1.67%   |
| Nvidia                                | 14        | 1.37%   |
| TP-Link                               | 11        | 1.08%   |
| Ralink Technology                     | 11        | 1.08%   |
| Qualcomm Atheros Communications       | 11        | 1.08%   |
| Marvell Technology Group              | 11        | 1.08%   |
| Sierra Wireless                       | 9         | 0.88%   |
| Ericsson Business Mobile Networks     | 8         | 0.78%   |
| Huawei Technologies                   | 4         | 0.39%   |
| Hewlett-Packard                       | 4         | 0.39%   |
| Dell                                  | 4         | 0.39%   |
| Xiaomi                                | 3         | 0.29%   |
| Sundance Technology Inc / IC Plus     | 3         | 0.29%   |
| D-Link                                | 3         | 0.29%   |
| AMD                                   | 3         | 0.29%   |
| Microsoft                             | 2         | 0.2%    |
| MediaTek                              | 2         | 0.2%    |
| Davicom Semiconductor                 | 2         | 0.2%    |
| Toshiba                               | 1         | 0.1%    |
| NetGear                               | 1         | 0.1%    |
| Motorola PCS                          | 1         | 0.1%    |
| Micro Star International              | 1         | 0.1%    |
| JMicron Technology                    | 1         | 0.1%    |
| ICS Advent                            | 1         | 0.1%    |
| Gemtek                                | 1         | 0.1%    |
| DisplayLink                           | 1         | 0.1%    |
| Cypress Semiconductor                 | 1         | 0.1%    |
| Chelsio Communications                | 1         | 0.1%    |
| ASIX Electronics                      | 1         | 0.1%    |
| Aquantia                              | 1         | 0.1%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.1%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 236       | 19.93%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 56        | 4.73%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 39        | 3.29%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 23        | 1.94%   |
| Intel Wireless 8265 / 8275                                        | 21        | 1.77%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 21        | 1.77%   |
| Intel Wireless 7265                                               | 19        | 1.6%    |
| Intel Wireless 7260                                               | 19        | 1.6%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 18        | 1.52%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 16        | 1.35%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 15        | 1.27%   |
| Intel Wi-Fi 6 AX200                                               | 14        | 1.18%   |
| Intel Wireless 3160                                               | 12        | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 12        | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 11        | 0.93%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.93%   |
| Intel Ethernet Connection (2) I219-V                              | 11        | 0.93%   |
| Qualcomm Atheros AR9271 802.11n                                   | 10        | 0.84%   |
| Intel I211 Gigabit Network Connection                             | 10        | 0.84%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 10        | 0.84%   |
| Intel 82579V Gigabit Network Connection                           | 10        | 0.84%   |
| Broadcom BCM43142 802.11b/g/n                                     | 10        | 0.84%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 9         | 0.76%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 9         | 0.76%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 9         | 0.76%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 0.76%   |
| Intel WiFi Link 5100                                              | 9         | 0.76%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 9         | 0.76%   |
| Intel Centrino Ultimate-N 6300                                    | 9         | 0.76%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 9         | 0.76%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 8         | 0.68%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 8         | 0.68%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 8         | 0.68%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 8         | 0.68%   |
| Intel 82577LM Gigabit Network Connection                          | 8         | 0.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 7         | 0.59%   |
| Intel Wireless-AC 9260                                            | 7         | 0.59%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection             | 7         | 0.59%   |
| Intel Ethernet Connection I218-LM                                 | 7         | 0.59%   |
| Sierra Wireless EM7345 4G LTE                                     | 6         | 0.51%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 0.51%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 6         | 0.51%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 6         | 0.51%   |
| Nvidia MCP61 Ethernet                                             | 6         | 0.51%   |
| Intel Wireless 8260                                               | 6         | 0.51%   |
| Intel Wi-Fi 6 AX201                                               | 6         | 0.51%   |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection           | 6         | 0.51%   |
| Intel Ethernet Connection (7) I219-V                              | 6         | 0.51%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                              | 6         | 0.51%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 6         | 0.51%   |
| Intel Centrino Wireless-N 2230                                    | 6         | 0.51%   |
| Intel 82567LM Gigabit Network Connection                          | 6         | 0.51%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 6         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 5         | 0.42%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)    | 5         | 0.42%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 5         | 0.42%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 5         | 0.42%   |
| Intel Ethernet Controller I225-V                                  | 5         | 0.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                      | 4         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 249       | 49.9%   |
| Qualcomm Atheros                      | 84        | 16.83%  |
| Realtek Semiconductor                 | 65        | 13.03%  |
| Broadcom                              | 32        | 6.41%   |
| Ralink                                | 17        | 3.41%   |
| Ralink Technology                     | 11        | 2.2%    |
| Qualcomm Atheros Communications       | 11        | 2.2%    |
| TP-Link                               | 9         | 1.8%    |
| Broadcom Limited                      | 8         | 1.6%    |
| Sierra Wireless                       | 3         | 0.6%    |
| Microsoft                             | 2         | 0.4%    |
| NetGear                               | 1         | 0.2%    |
| Micro Star International              | 1         | 0.2%    |
| MEDIATEK                              | 1         | 0.2%    |
| Hewlett-Packard                       | 1         | 0.2%    |
| Gemtek                                | 1         | 0.2%    |
| Dell                                  | 1         | 0.2%    |
| D-Link                                | 1         | 0.2%    |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1         | 0.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 23        | 4.59%   |
| Intel Wireless 8265 / 8275                                     | 21        | 4.19%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 21        | 4.19%   |
| Intel Wireless 7265                                            | 19        | 3.79%   |
| Intel Wireless 7260                                            | 19        | 3.79%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 16        | 3.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 15        | 2.99%   |
| Intel Wi-Fi 6 AX200                                            | 14        | 2.79%   |
| Intel Wireless 3160                                            | 12        | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 11        | 2.2%    |
| Qualcomm Atheros AR9271 802.11n                                | 10        | 2%      |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 2%      |
| Broadcom BCM43142 802.11b/g/n                                  | 10        | 2%      |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 9         | 1.8%    |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 9         | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 9         | 1.8%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 9         | 1.8%    |
| Intel WiFi Link 5100                                           | 9         | 1.8%    |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 9         | 1.8%    |
| Intel Centrino Ultimate-N 6300                                 | 9         | 1.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 9         | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 8         | 1.6%    |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 8         | 1.6%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 8         | 1.6%    |
| Intel Wireless-AC 9260                                         | 7         | 1.4%    |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 7         | 1.4%    |
| Intel Wireless 8260                                            | 6         | 1.2%    |
| Intel Wi-Fi 6 AX201                                            | 6         | 1.2%    |
| Intel PRO/Wireless 5100 AGN [Shiloh] Network Connection        | 6         | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 6         | 1.2%    |
| Intel Centrino Wireless-N 2230                                 | 6         | 1.2%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 6         | 1.2%    |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 5         | 1%      |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 5         | 1%      |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                   | 4         | 0.8%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 4         | 0.8%    |
| Realtek RTL8187B Wireless Adapter                              | 4         | 0.8%    |
| Ralink RT2870/RT3070 Wireless Adapter                          | 4         | 0.8%    |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 4         | 0.8%    |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 4         | 0.8%    |
| Intel Wireless 3165                                            | 4         | 0.8%    |
| Intel Centrino Advanced-N 6200                                 | 4         | 0.8%    |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter     | 4         | 0.8%    |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 4         | 0.8%    |
| Sierra Wireless EM7455                                         | 3         | 0.6%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 0.6%    |
| Realtek RTL8187 Wireless Adapter                               | 3         | 0.6%    |
| Ralink RT2501/RT2573 Wireless Adapter                          | 3         | 0.6%    |
| Ralink MT7601U Wireless Adapter                                | 3         | 0.6%    |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                      | 3         | 0.6%    |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection  | 3         | 0.6%    |
| Intel Centrino Wireless-N 1030 [Rainbow Peak]                  | 3         | 0.6%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                          | 2         | 0.4%    |
| TP-Link Archer T4U ver.3                                       | 2         | 0.4%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 0.4%    |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 2         | 0.4%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 2         | 0.4%    |
| Realtek RTL8811AU 802.11a/b/g/n/ac WLAN Adapter                | 2         | 0.4%    |
| Realtek RTL8723AE PCIe Wireless Network Adapter                | 2         | 0.4%    |
| Realtek RTL8188EE Wireless Network Adapter                     | 2         | 0.4%    |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 322       | 49.61%  |
| Intel                             | 190       | 29.28%  |
| Qualcomm Atheros                  | 48        | 7.4%    |
| Broadcom                          | 21        | 3.24%   |
| Nvidia                            | 14        | 2.16%   |
| Broadcom Limited                  | 14        | 2.16%   |
| Marvell Technology Group          | 11        | 1.69%   |
| Sierra Wireless                   | 6         | 0.92%   |
| Xiaomi                            | 3         | 0.46%   |
| Sundance Technology Inc / IC Plus | 3         | 0.46%   |
| Huawei Technologies               | 3         | 0.46%   |
| TP-Link                           | 2         | 0.31%   |
| Davicom Semiconductor             | 2         | 0.31%   |
| D-Link                            | 2         | 0.31%   |
| Motorola PCS                      | 1         | 0.15%   |
| JMicron Technology                | 1         | 0.15%   |
| ICS Advent                        | 1         | 0.15%   |
| DisplayLink                       | 1         | 0.15%   |
| Cypress Semiconductor             | 1         | 0.15%   |
| Chelsio Communications            | 1         | 0.15%   |
| ASIX Electronics                  | 1         | 0.15%   |
| Aquantia                          | 1         | 0.15%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 236       | 35.7%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 56        | 8.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 39        | 5.9%    |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                          | 18        | 2.72%   |
| Intel Ethernet Connection I217-LM                                              | 12        | 1.82%   |
| Intel Ethernet Connection (3) I218-LM                                          | 11        | 1.66%   |
| Intel Ethernet Connection (2) I219-V                                           | 11        | 1.66%   |
| Intel I211 Gigabit Network Connection                                          | 10        | 1.51%   |
| Intel 82579V Gigabit Network Connection                                        | 10        | 1.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 8         | 1.21%   |
| Intel 82577LM Gigabit Network Connection                                       | 8         | 1.21%   |
| Realtek RTL8125 2.5GbE Controller                                              | 7         | 1.06%   |
| Intel Ethernet Connection I218-LM                                              | 7         | 1.06%   |
| Sierra Wireless EM7345 4G LTE                                                  | 6         | 0.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 6         | 0.91%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 6         | 0.91%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 6         | 0.91%   |
| Nvidia MCP61 Ethernet                                                          | 6         | 0.91%   |
| Intel Ethernet Connection (7) I219-V                                           | 6         | 0.91%   |
| Intel Ethernet Connection (6) I219-V                                           | 6         | 0.91%   |
| Intel Ethernet Connection (2) I218-V                                           | 6         | 0.91%   |
| Intel 82567LM Gigabit Network Connection                                       | 6         | 0.91%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller                      | 5         | 0.76%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 5         | 0.76%   |
| Intel Ethernet Controller I225-V                                               | 5         | 0.76%   |
| Intel Ethernet Connection I219-LM                                              | 4         | 0.61%   |
| Intel 82567LM-3 Gigabit Network Connection                                     | 4         | 0.61%   |
| Intel 82566DM-2 Gigabit Network Connection                                     | 4         | 0.61%   |
| Broadcom NetXtreme BCM5761 Gigabit Ethernet PCIe                               | 4         | 0.61%   |
| Broadcom NetLink BCM5784M Gigabit Ethernet PCIe                                | 4         | 0.61%   |
| Broadcom Limited NetLink BCM57780 Gigabit Ethernet PCIe                        | 4         | 0.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 3         | 0.45%   |
| Sundance Inc / IC Plus IC Plus IP100A Integrated 10/100 Ethernet MAC + PHY     | 3         | 0.45%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                                      | 3         | 0.45%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller                      | 3         | 0.45%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                                  | 3         | 0.45%   |
| Qualcomm Atheros AR8152 v1.1 Fast Ethernet                                     | 3         | 0.45%   |
| Marvell Group 88E8040T PCI-E Fast Ethernet Controller                          | 3         | 0.45%   |
| Intel Ethernet Connection I217-V                                               | 3         | 0.45%   |
| Intel Ethernet Connection (7) I219-LM                                          | 3         | 0.45%   |
| Intel Ethernet Connection (4) I219-V                                           | 3         | 0.45%   |
| Intel Ethernet Connection (10) I219-V                                          | 3         | 0.45%   |
| Intel 82578DM Gigabit Network Connection                                       | 3         | 0.45%   |
| Broadcom Limited NetXtreme BCM5755 Gigabit Ethernet PCI Express                | 3         | 0.45%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]                | 2         | 0.3%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 2         | 0.3%    |
| Realtek Killer E2600 Gigabit Ethernet Controller                               | 2         | 0.3%    |
| Nvidia MCP65 Ethernet                                                          | 2         | 0.3%    |
| Nvidia MCP55 Ethernet                                                          | 2         | 0.3%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 2         | 0.3%    |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller                        | 2         | 0.3%    |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                        | 2         | 0.3%    |
| Intel Ethernet Connection I219-V                                               | 2         | 0.3%    |
| Intel Ethernet Connection (6) I219-LM                                          | 2         | 0.3%    |
| Intel Ethernet Connection (5) I219-LM                                          | 2         | 0.3%    |
| Intel Ethernet Connection (4) I219-LM                                          | 2         | 0.3%    |
| Intel 82574L Gigabit Network Connection                                        | 2         | 0.3%    |
| Intel 82567LF Gigabit Network Connection                                       | 2         | 0.3%    |
| Intel 82566MM Gigabit Network Connection                                       | 2         | 0.3%    |
| Huawei JNY-LX1                                                                 | 2         | 0.3%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 612       | 55.23%  |
| WiFi     | 474       | 42.78%  |
| Modem    | 22        | 1.99%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 418       | 50.79%  |
| WiFi     | 405       | 49.21%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 394       | 58.63%  |
| 1     | 261       | 38.84%  |
| 3     | 10        | 1.49%   |
| 0     | 5         | 0.74%   |
| 5     | 1         | 0.15%   |
| 4     | 1         | 0.15%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 665       | 98.81%  |
| Yes  | 8         | 1.19%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 168       | 44.56%  |
| Qualcomm Atheros Communications | 28        | 7.43%   |
| Cambridge Silicon Radio         | 28        | 7.43%   |
| Broadcom                        | 25        | 6.63%   |
| Realtek Semiconductor           | 23        | 6.1%    |
| IMC Networks                    | 17        | 4.51%   |
| Lite-On Technology              | 14        | 3.71%   |
| Foxconn / Hon Hai               | 12        | 3.18%   |
| Dell                            | 11        | 2.92%   |
| Toshiba                         | 10        | 2.65%   |
| Hewlett-Packard                 | 10        | 2.65%   |
| Ralink                          | 8         | 2.12%   |
| Apple                           | 6         | 1.59%   |
| Integrated System Solution      | 5         | 1.33%   |
| Foxconn International           | 4         | 1.06%   |
| ASUSTek Computer                | 4         | 1.06%   |
| Ralink Technology               | 2         | 0.53%   |
| Realtek                         | 1         | 0.27%   |
| MediaTek                        | 1         | 0.27%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 76        | 20.16%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 32        | 8.49%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 28        | 7.43%   |
| Intel AX201 Bluetooth                                                               | 24        | 6.37%   |
| Realtek Bluetooth Radio                                                             | 18        | 4.77%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 18        | 4.77%   |
| Intel AX200 Bluetooth                                                               | 14        | 3.71%   |
| IMC Networks Bluetooth Radio                                                        | 12        | 3.18%   |
| Ralink RT3290 Bluetooth                                                             | 8         | 2.12%   |
| Lite-On Bluetooth Device                                                            | 8         | 2.12%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 7         | 1.86%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 6         | 1.59%   |
| Intel Bluetooth Device                                                              | 6         | 1.59%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 6         | 1.59%   |
| Toshiba Integrated Bluetooth HCI                                                    | 5         | 1.33%   |
| IMC Networks Bluetooth Device                                                       | 5         | 1.33%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 5         | 1.33%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 5         | 1.33%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 5         | 1.33%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 4         | 1.06%   |
| Foxconn International BCM43142A0 Bluetooth module                                   | 4         | 1.06%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 4         | 1.06%   |
| Apple Bluetooth Host Controller                                                     | 4         | 1.06%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 3         | 0.8%    |
| Integrated System Solution Bluetooth Device                                         | 3         | 0.8%    |
| Dell DW375 Bluetooth Module                                                         | 3         | 0.8%    |
| Dell BCM20702A0 Bluetooth Module                                                    | 3         | 0.8%    |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 3         | 0.8%    |
| Broadcom BCM2045 Bluetooth                                                          | 3         | 0.8%    |
| Toshiba Integrated Bluetooth (Taiyo Yuden)                                          | 2         | 0.53%   |
| Realtek RTL8723B Bluetooth                                                          | 2         | 0.53%   |
| Qualcomm Atheros Bluetooth USB Host Controller                                      | 2         | 0.53%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 0.53%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 2         | 0.53%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 0.53%   |
| Integrated System Solution KY-BT100 Bluetooth Adapter                               | 2         | 0.53%   |
| Dell Wireless 365 Bluetooth                                                         | 2         | 0.53%   |
| Broadcom HP Portable SoftSailing                                                    | 2         | 0.53%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 2         | 0.53%   |
| Broadcom BCM43142A0 Bluetooth 4.0                                                   | 2         | 0.53%   |
| Broadcom BCM2045B (BDC-2.1) [Bluetooth Controller]                                  | 2         | 0.53%   |
| Toshiba RT Bluetooth Radio                                                          | 1         | 0.27%   |
| Toshiba Bluetooth Device                                                            | 1         | 0.27%   |
| Toshiba Askey Bluetooth Module                                                      | 1         | 0.27%   |
| Realtek RTL8821A Bluetooth                                                          | 1         | 0.27%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 1         | 0.27%   |
| Realtek 802.11n WLAN Adapter                                                        | 1         | 0.27%   |
| Realtek Bluetooth Radio                                                             | 1         | 0.27%   |
| Ralink Motorola BC4 Bluetooth 3.0+HS Adapter                                        | 1         | 0.27%   |
| Ralink CSR BS8510                                                                   | 1         | 0.27%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 0.27%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 0.27%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 0.27%   |
| MediaTek Wireless_Device                                                            | 1         | 0.27%   |
| Intel AX210 Bluetooth                                                               | 1         | 0.27%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 0.27%   |
| Foxconn / Hon Hai Broadcom Bluetooth 2.1 Device                                     | 1         | 0.27%   |
| Dell Wireless 370 Bluetooth Mini-card                                               | 1         | 0.27%   |
| Dell Wireless 355 Bluetooth                                                         | 1         | 0.27%   |
| Dell BCM2046 Bluetooth Device                                                       | 1         | 0.27%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 521       | 56.14%  |
| AMD                                  | 172       | 18.53%  |
| Nvidia                               | 154       | 16.59%  |
| C-Media Electronics                  | 17        | 1.83%   |
| Creative Labs                        | 9         | 0.97%   |
| GN Netcom                            | 7         | 0.75%   |
| Logitech                             | 5         | 0.54%   |
| Texas Instruments                    | 4         | 0.43%   |
| Razer USA                            | 4         | 0.43%   |
| Plantronics                          | 4         | 0.43%   |
| Creative Technology                  | 4         | 0.43%   |
| Generalplus Technology               | 3         | 0.32%   |
| ASUSTek Computer                     | 3         | 0.32%   |
| Thesycon Systemsoftware & Consulting | 2         | 0.22%   |
| Tenx Technology                      | 2         | 0.22%   |
| Lenovo                               | 2         | 0.22%   |
| BEHRINGER International              | 2         | 0.22%   |
| VIA Technologies                     | 1         | 0.11%   |
| SteelSeries ApS                      | 1         | 0.11%   |
| Silicon Integrated Systems [SiS]     | 1         | 0.11%   |
| Sennheiser Communications            | 1         | 0.11%   |
| Samson Technologies                  | 1         | 0.11%   |
| Realtek Semiconductor                | 1         | 0.11%   |
| NAD Electronics                      | 1         | 0.11%   |
| M-Audio                              | 1         | 0.11%   |
| JMTek                                | 1         | 0.11%   |
| FiiO Electronics Technology          | 1         | 0.11%   |
| Evolution Electronics                | 1         | 0.11%   |
| ESS Technology                       | 1         | 0.11%   |
| Corsair                              | 1         | 0.11%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 62        | 5.65%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 61        | 5.56%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 41        | 3.73%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 40        | 3.64%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 38        | 3.46%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 37        | 3.37%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 33        | 3.01%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 25        | 2.28%   |
| Intel Cannon Lake PCH cAVS                                                                        | 25        | 2.28%   |
| Intel Broadwell-U Audio Controller                                                                | 25        | 2.28%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 25        | 2.28%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 24        | 2.19%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 22        | 2%      |
| Intel Haswell-ULT HD Audio Controller                                                             | 20        | 1.82%   |
| Intel 8 Series HD Audio Controller                                                                | 20        | 1.82%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 20        | 1.82%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 18        | 1.64%   |
| AMD FCH Azalia Controller                                                                         | 18        | 1.64%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 17        | 1.55%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 16        | 1.46%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 16        | 1.46%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 15        | 1.37%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 15        | 1.37%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 14        | 1.28%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 13        | 1.18%   |
| Intel CM238 HD Audio Controller                                                                   | 13        | 1.18%   |
| Intel 200 Series PCH HD Audio                                                                     | 12        | 1.09%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 12        | 1.09%   |
| Nvidia GF119 HDMI Audio Controller                                                                | 11        | 1%      |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 11        | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 11        | 1%      |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 10        | 0.91%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 10        | 0.91%   |
| Nvidia High Definition Audio Controller                                                           | 9         | 0.82%   |
| Nvidia GP104 High Definition Audio Controller                                                     | 9         | 0.82%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 9         | 0.82%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 9         | 0.82%   |
| Intel Comet Lake PCH cAVS                                                                         | 8         | 0.73%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                                         | 8         | 0.73%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 8         | 0.73%   |
| Nvidia TU116 High Definition Audio Controller                                                     | 7         | 0.64%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 7         | 0.64%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 7         | 0.64%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 7         | 0.64%   |
| Intel C610/X99 series chipset HD Audio Controller                                                 | 7         | 0.64%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 7         | 0.64%   |
| AMD Kabini HDMI/DP Audio                                                                          | 7         | 0.64%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 7         | 0.64%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 6         | 0.55%   |
| Nvidia MCP61 High Definition Audio                                                                | 6         | 0.55%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 6         | 0.55%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 6         | 0.55%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                                               | 6         | 0.55%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 5         | 0.46%   |
| Nvidia GA104 High Definition Audio Controller                                                     | 5         | 0.46%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 5         | 0.46%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 5         | 0.46%   |
| AMD Redwood HDMI Audio [Radeon HD 5000 Series]                                                    | 5         | 0.46%   |
| AMD Navi 10 HDMI Audio                                                                            | 5         | 0.46%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 5         | 0.46%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 82        | 20.65%  |
| SK Hynix            | 72        | 18.14%  |
| Kingston            | 55        | 13.85%  |
| Unknown             | 45        | 11.34%  |
| Micron Technology   | 31        | 7.81%   |
| Corsair             | 22        | 5.54%   |
| A-DATA Technology   | 19        | 4.79%   |
| Ramaxel Technology  | 15        | 3.78%   |
| Nanya Technology    | 9         | 2.27%   |
| Transcend           | 7         | 1.76%   |
| Crucial             | 7         | 1.76%   |
| Elpida              | 6         | 1.51%   |
| G.Skill             | 5         | 1.26%   |
| Team                | 4         | 1.01%   |
| Apacer              | 3         | 0.76%   |
| Silicon Power       | 2         | 0.5%    |
| pqi                 | 2         | 0.5%    |
| GOODRAM             | 2         | 0.5%    |
| atermiter           | 2         | 0.5%    |
| Unknown (ABCD)      | 1         | 0.25%   |
| Thermaltake         | 1         | 0.25%   |
| Qimonda             | 1         | 0.25%   |
| HBS                 | 1         | 0.25%   |
| CSX                 | 1         | 0.25%   |
| ASint Technology    | 1         | 0.25%   |
| A Force             | 1         | 0.25%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| SK Hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s     | 7         | 1.62%   |
| SK Hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s     | 5         | 1.16%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s      | 5         | 1.16%   |
| SK Hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 4         | 0.93%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1600MT/s      | 4         | 0.93%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s      | 4         | 0.93%   |
| Ramaxel RAM RMT3160ED58E9W1600 4GB SODIMM DDR3 1600MT/s    | 4         | 0.93%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                | 3         | 0.7%    |
| SK Hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 3         | 0.7%    |
| SK Hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s     | 3         | 0.7%    |
| SK Hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s     | 3         | 0.7%    |
| SK Hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 3         | 0.7%    |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s      | 3         | 0.7%    |
| Samsung RAM M471B5273CH0-CH9 4096MB SODIMM DDR3 1334MT/s   | 3         | 0.7%    |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s      | 3         | 0.7%    |
| Samsung RAM M471B5173DB0-YK0 4096MB SODIMM DDR3 1600MT/s   | 3         | 0.7%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s      | 3         | 0.7%    |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s     | 3         | 0.7%    |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s      | 3         | 0.7%    |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s      | 3         | 0.7%    |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s  | 3         | 0.7%    |
| Micron RAM 8JTF51264AZ-1G6E1 4GB DIMM DDR3 1600MT/s        | 3         | 0.7%    |
| Micron RAM 8ATF1G64HZ-2G6E1 8192MB SODIMM DDR4 2667MT/s    | 3         | 0.7%    |
| Elpida RAM EBJ41UF8BCS0-DJ-F 4096MB SODIMM DDR3 1334MT/s   | 3         | 0.7%    |
| Unknown RAM Module 4GB DIMM 1333MT/s                       | 2         | 0.46%   |
| Unknown RAM Module 4096MB DIMM SDRAM                       | 2         | 0.46%   |
| Unknown RAM Module 2GB DIMM 800MT/s                        | 2         | 0.46%   |
| Unknown RAM Module 2048MB DIMM SDRAM                       | 2         | 0.46%   |
| Unknown RAM Module 1024MB SODIMM DDR                       | 2         | 0.46%   |
| Transcend RAM JM2666HSG-8G 8GB SODIMM DDR4 2667MT/s        | 2         | 0.46%   |
| SK Hynix RAM Module 4GB SODIMM DDR3 1600MT/s               | 2         | 0.46%   |
| SK Hynix RAM Module 4096MB DIMM DDR3 1066MT/s              | 2         | 0.46%   |
| SK Hynix RAM HMT451S6CFR6A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 0.46%   |
| SK Hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s     | 2         | 0.46%   |
| SK Hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 0.46%   |
| SK Hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s     | 2         | 0.46%   |
| SK Hynix RAM HMT351S6BFR8C-H9 4096MB SODIMM DDR3 1333MT/s  | 2         | 0.46%   |
| SK Hynix RAM HMT125S6BFR8C-H9 2048MB SODIMM DDR3 1333MT/s  | 2         | 0.46%   |
| SK Hynix RAM HMA851U6AFR6N-UH 4GB DIMM DDR4 2400MT/s       | 2         | 0.46%   |
| SK Hynix RAM HMA82GS6DJR8N-XN 16384MB SODIMM DDR4 3200MT/s | 2         | 0.46%   |
| SK Hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 2         | 0.46%   |
| SK Hynix RAM HMA81GS6DJR8N-VK 8GB SODIMM DDR4 2667MT/s     | 2         | 0.46%   |
| SK Hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s     | 2         | 0.46%   |
| Samsung RAM Module 16384MB SODIMM DDR4 2667MT/s            | 2         | 0.46%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s      | 2         | 0.46%   |
| Samsung RAM M471B5674-M0-YK0 4096MB Chip DDR3 1600MT/s     | 2         | 0.46%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s      | 2         | 0.46%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s      | 2         | 0.46%   |
| Samsung RAM M471B1G73EB0-YK0 8192MB SODIMM DDR3 1600MT/s   | 2         | 0.46%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s      | 2         | 0.46%   |
| Samsung RAM M471A1G43DB0-CPB 8GB SODIMM DDR4 2400MT/s      | 2         | 0.46%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s        | 2         | 0.46%   |
| Ramaxel RAM RMSA3260MH78HAF-2666 8GB SODIMM DDR4 2667MT/s  | 2         | 0.46%   |
| Nanya RAM NT2GC64B88B0NS-CG 2GB SODIMM DDR3 1334MT/s       | 2         | 0.46%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s       | 2         | 0.46%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s       | 2         | 0.46%   |
| Kingston RAM KHX3200C16D4/8GX 8GB DIMM DDR4 3533MT/s       | 2         | 0.46%   |
| Kingston RAM KHX3000C15/16GX 16384MB DIMM DDR4 3333MT/s    | 2         | 0.46%   |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s          | 2         | 0.46%   |
| Kingston RAM KHX2133C14D4/4G 4096MB DIMM DDR4 2933MT/s     | 2         | 0.46%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 146       | 44.24%  |
| DDR4    | 124       | 37.58%  |
| DDR2    | 20        | 6.06%   |
| SDRAM   | 13        | 3.94%   |
| Unknown | 13        | 3.94%   |
| LPDDR3  | 5         | 1.52%   |
| DDR     | 4         | 1.21%   |
| LPDDR4  | 3         | 0.91%   |
| DRAM    | 2         | 0.61%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 191       | 58.59%  |
| DIMM         | 124       | 38.04%  |
| Row Of Chips | 6         | 1.84%   |
| Chip         | 4         | 1.23%   |
| RIMM         | 1         | 0.31%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size    | Computers | Percent |
|---------|-----------|---------|
| 4096    | 130       | 36.52%  |
| 8192    | 106       | 29.78%  |
| 2048    | 51        | 14.33%  |
| 16384   | 40        | 11.24%  |
| 1024    | 16        | 4.49%   |
| 32768   | 8         | 2.25%   |
| 512     | 3         | 0.84%   |
| 256     | 1         | 0.28%   |
| Unknown | 1         | 0.28%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 93        | 25.62%  |
| 2667    | 54        | 14.88%  |
| 1333    | 34        | 9.37%   |
| 3200    | 28        | 7.71%   |
| 2400    | 24        | 6.61%   |
| 1334    | 19        | 5.23%   |
| 800     | 15        | 4.13%   |
| 2133    | 14        | 3.86%   |
| Unknown | 14        | 3.86%   |
| 3600    | 7         | 1.93%   |
| 667     | 7         | 1.93%   |
| 1867    | 6         | 1.65%   |
| 3266    | 4         | 1.1%    |
| 3466    | 3         | 0.83%   |
| 3000    | 3         | 0.83%   |
| 2933    | 3         | 0.83%   |
| 1067    | 3         | 0.83%   |
| 1066    | 3         | 0.83%   |
| 333     | 3         | 0.83%   |
| 4199    | 2         | 0.55%   |
| 3800    | 2         | 0.55%   |
| 3533    | 2         | 0.55%   |
| 3333    | 2         | 0.55%   |
| 2800    | 2         | 0.55%   |
| 1866    | 2         | 0.55%   |
| 1800    | 2         | 0.55%   |
| 57535   | 1         | 0.28%   |
| 4267    | 1         | 0.28%   |
| 3733    | 1         | 0.28%   |
| 3467    | 1         | 0.28%   |
| 2666    | 1         | 0.28%   |
| 2481    | 1         | 0.28%   |
| 2048    | 1         | 0.28%   |
| 2000    | 1         | 0.28%   |
| 1639    | 1         | 0.28%   |
| 975     | 1         | 0.28%   |
| 533     | 1         | 0.28%   |
| 400     | 1         | 0.28%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 6         | 35.29%  |
| Brother Industries  | 4         | 23.53%  |
| Samsung Electronics | 3         | 17.65%  |
| Xerox               | 1         | 5.88%   |
| Kyocera             | 1         | 5.88%   |
| Canon               | 1         | 5.88%   |
| ATEN International  | 1         | 5.88%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                    | Computers | Percent |
|------------------------------------------|-----------|---------|
| HP LaserJet 1020                         | 2         | 11.76%  |
| Xerox Phaser 3020                        | 1         | 5.88%   |
| Samsung ML-2010P Mono Laser Printer      | 1         | 5.88%   |
| Samsung M332x 382x 402x Series           | 1         | 5.88%   |
| Samsung M267x 287x Series                | 1         | 5.88%   |
| Kyocera ECOSYS P2040dn                   | 1         | 5.88%   |
| HP LaserJet Professional P1566           | 1         | 5.88%   |
| HP LaserJet P1102                        | 1         | 5.88%   |
| HP LaserJet 4350                         | 1         | 5.88%   |
| HP DeskJet 4530 series                   | 1         | 5.88%   |
| Canon PIXMA MP240                        | 1         | 5.88%   |
| Brother Printer                          | 1         | 5.88%   |
| Brother MFC-B7715DW series               | 1         | 5.88%   |
| Brother DCP-T300                         | 1         | 5.88%   |
| Brother DCP-7055 scanner/printer         | 1         | 5.88%   |
| ATEN International UC-1284B Printer Port | 1         | 5.88%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Canon          | 2         | 66.67%  |
| Mustek Systems | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Mustek Systems SNAPSCAN e22        | 1         | 33.33%  |
| Canon CanoScan N670U/N676U/LiDE 20 | 1         | 33.33%  |
| Canon CanoScan LiDE 110            | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 103       | 25.81%  |
| IMC Networks                           | 48        | 12.03%  |
| Microdia                               | 39        | 9.77%   |
| Realtek Semiconductor                  | 35        | 8.77%   |
| Acer                                   | 31        | 7.77%   |
| Sunplus Innovation Technology          | 21        | 5.26%   |
| Suyin                                  | 12        | 3.01%   |
| Quanta                                 | 12        | 3.01%   |
| Logitech                               | 11        | 2.76%   |
| Cheng Uei Precision Industry (Foxlink) | 11        | 2.76%   |
| Lite-On Technology                     | 10        | 2.51%   |
| Syntek                                 | 9         | 2.26%   |
| Z-Star Microelectronics                | 8         | 2.01%   |
| Microsoft                              | 6         | 1.5%    |
| Alcor Micro                            | 6         | 1.5%    |
| Silicon Motion                         | 5         | 1.25%   |
| Luxvisions Innotech Limited            | 4         | 1%      |
| Ricoh                                  | 2         | 0.5%    |
| Lenovo                                 | 2         | 0.5%    |
| Importek                               | 2         | 0.5%    |
| Hewlett-Packard                        | 2         | 0.5%    |
| Creative Technology                    | 2         | 0.5%    |
| Alpha Imaging Technology               | 2         | 0.5%    |
| Unknown                                | 1         | 0.25%   |
| Sunplus Technology                     | 1         | 0.25%   |
| Sonix Technology                       | 1         | 0.25%   |
| Samsung Electronics                    | 1         | 0.25%   |
| Razer USA                              | 1         | 0.25%   |
| Primax Electronics                     | 1         | 0.25%   |
| Pixart Imaging                         | 1         | 0.25%   |
| Google                                 | 1         | 0.25%   |
| Genesys Logic                          | 1         | 0.25%   |
| Generalplus Technology                 | 1         | 0.25%   |
| GEMBIRD                                | 1         | 0.25%   |
| DJJHFA1BIF5CB0                         | 1         | 0.25%   |
| Divio                                  | 1         | 0.25%   |
| Aveo Technology                        | 1         | 0.25%   |
| Arkmicro Technologies                  | 1         | 0.25%   |
| Apple                                  | 1         | 0.25%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 VGA UVC WebCam                                       | 19        | 4.76%   |
| Chicony Integrated Camera                                                | 19        | 4.76%   |
| IMC Networks Integrated Camera                                           | 16        | 4.01%   |
| Chicony HD WebCam                                                        | 13        | 3.26%   |
| Realtek Integrated_Webcam_HD                                             | 9         | 2.26%   |
| Microdia Integrated_Webcam_HD                                            | 9         | 2.26%   |
| Realtek Lenovo EasyCamera                                                | 7         | 1.75%   |
| Acer SunplusIT Integrated Camera                                         | 7         | 1.75%   |
| Acer Integrated Camera                                                   | 7         | 1.75%   |
| Sunplus Integrated_Webcam_HD                                             | 6         | 1.5%    |
| Chicony USB 2.0 Camera                                                   | 6         | 1.5%    |
| Chicony Lenovo Integrated Camera (0.3MP)                                 | 5         | 1.25%   |
| Chicony HD WebCam (Asus N-series)                                        | 5         | 1.25%   |
| Acer Lenovo EasyCamera                                                   | 5         | 1.25%   |
| Quanta HD Webcam                                                         | 4         | 1%      |
| Microdia Laptop_Integrated_Webcam_HD                                     | 4         | 1%      |
| Microdia Integrated Webcam                                               | 4         | 1%      |
| Logitech Webcam C270                                                     | 4         | 1%      |
| Lite-On Integrated Camera                                                | 4         | 1%      |
| Chicony USB2.0 VGA UVC WebCam                                            | 4         | 1%      |
| Chicony TOSHIBA Web Camera - HD                                          | 4         | 1%      |
| Chicony Lenovo EasyCamera                                                | 4         | 1%      |
| Z-Star Venus USB2.0 Camera                                               | 3         | 0.75%   |
| Z-Star A4 TECH HD PC Camera                                              | 3         | 0.75%   |
| Syntek Integrated Camera                                                 | 3         | 0.75%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                                 | 3         | 0.75%   |
| Sunplus Laptop Integrated Webcam HD                                      | 3         | 0.75%   |
| Sunplus HP HD Webcam [Fixed]                                             | 3         | 0.75%   |
| Realtek EasyCamera                                                       | 3         | 0.75%   |
| Quanta HP TrueVision HD Camera                                           | 3         | 0.75%   |
| Microsoft LifeCam HD-3000                                                | 3         | 0.75%   |
| Microdia Dell Integrated HD Webcam                                       | 3         | 0.75%   |
| Microdia Camera                                                          | 3         | 0.75%   |
| IMC Networks UVC VGA Webcam                                              | 3         | 0.75%   |
| Chicony Integrated HP HD Webcam                                          | 3         | 0.75%   |
| Chicony HP Webcam [2 MP Macro]                                           | 3         | 0.75%   |
| Chicony HP HD Webcam [Fixed]                                             | 3         | 0.75%   |
| Chicony HP HD Webcam                                                     | 3         | 0.75%   |
| Chicony FJ Camera                                                        | 3         | 0.75%   |
| Cheng Uei Precision Industry (Foxlink) HP EliteBook integrated HD Webcam | 3         | 0.75%   |
| Alcor Micro Acer Integrated Webcam                                       | 3         | 0.75%   |
| Syntek Lenovo EasyCamera                                                 | 2         | 0.5%    |
| Suyin HP TrueVision HD Integrated Webcam                                 | 2         | 0.5%    |
| Suyin Asus Integrated Webcam                                             | 2         | 0.5%    |
| Sunplus HD WebCam                                                        | 2         | 0.5%    |
| Sunplus Dell HD Webcam                                                   | 2         | 0.5%    |
| Silicon Motion WebCam SC-0311139N                                        | 2         | 0.5%    |
| Realtek USB2.0 HD UVC WebCam                                             | 2         | 0.5%    |
| Realtek USB Camera                                                       | 2         | 0.5%    |
| Realtek Integrated Webcam HD                                             | 2         | 0.5%    |
| Realtek HP Truevision HD                                                 | 2         | 0.5%    |
| Microdia Laptop_Integrated_Webcam_2M                                     | 2         | 0.5%    |
| Microdia Integrated_Webcam_2M                                            | 2         | 0.5%    |
| Microdia Dell Laptop Integrated Webcam HD                                | 2         | 0.5%    |
| Luxvisions Innotech Limited HP Wide Vision HD Camera                     | 2         | 0.5%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera                      | 2         | 0.5%    |
| Logitech Webcam C170                                                     | 2         | 0.5%    |
| Lite-On TOSHIBA Web Camera - HD                                          | 2         | 0.5%    |
| Lite-On HP HD Webcam                                                     | 2         | 0.5%    |
| IMC Networks VGA UVC WebCam                                              | 2         | 0.5%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 35        | 42.68%  |
| Synaptics                  | 18        | 21.95%  |
| AuthenTec                  | 10        | 12.2%   |
| Shenzhen Goodix Technology | 6         | 7.32%   |
| Elan Microelectronics      | 5         | 6.1%    |
| Upek                       | 4         | 4.88%   |
| LighTuning Technology      | 3         | 3.66%   |
| STMicroelectronics         | 1         | 1.22%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS 5011 fingerprint sensor                               | 9         | 10.98%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 9         | 10.98%  |
| Shenzhen Goodix Fingerprint Reader                                         | 5         | 6.1%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 4         | 4.88%   |
| Validity Sensors Synaptics WBDI                                            | 4         | 4.88%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 4         | 4.88%   |
| AuthenTec AES2810                                                          | 4         | 4.88%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 3.66%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 3         | 3.66%   |
| Elan ELAN:ARM-M4                                                           | 3         | 3.66%   |
| AuthenTec Fingerprint Sensor                                               | 3         | 3.66%   |
| Unknown                                                                    | 3         | 3.66%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 2.44%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 2         | 2.44%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 2         | 2.44%   |
| Validity Sensors VFS491                                                    | 2         | 2.44%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 2.44%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 2.44%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 2.44%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 2         | 2.44%   |
| Elan ELAN:Fingerprint                                                      | 2         | 2.44%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 2         | 2.44%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 1         | 1.22%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 1.22%   |
| STMicroelectronics Fingerprint Reader                                      | 1         | 1.22%   |
| Shenzhen Goodix  Fingerprint Device                                        | 1         | 1.22%   |
| LighTuning Fingerprint Reader                                              | 1         | 1.22%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 1.22%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 1         | 1.22%   |
| AuthenTec AES1600                                                          | 1         | 1.22%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Broadcom              | 17        | 34%     |
| Alcor Micro           | 16        | 32%     |
| O2 Micro              | 5         | 10%     |
| Lenovo                | 4         | 8%      |
| Upek                  | 2         | 4%      |
| SCM Microsystems      | 2         | 4%      |
| OmniKey               | 2         | 4%      |
| Advanced Card Systems | 2         | 4%      |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 16        | 32%     |
| Broadcom BCM5880 Secure Applications Processor                               | 8         | 16%     |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 5         | 10%     |
| Lenovo Integrated Smart Card Reader                                          | 4         | 8%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 6%      |
| Broadcom 58200                                                               | 3         | 6%      |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 2         | 4%      |
| SCM Microsystems SCR3340 - ExpressCard54 Smart Card Reader                   | 2         | 4%      |
| OmniKey CardMan 3021 / 3121                                                  | 2         | 4%      |
| Broadcom 5880                                                                | 2         | 4%      |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 1         | 2%      |
| Advanced Card Systems ACR39U                                                 | 1         | 2%      |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 1         | 2%      |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 470       | 68.61%  |
| 1     | 167       | 24.38%  |
| 2     | 44        | 6.42%   |
| 3     | 3         | 0.44%   |
| 4     | 1         | 0.15%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 82        | 32.28%  |
| Graphics card            | 50        | 19.69%  |
| Chipcard                 | 41        | 16.14%  |
| Net/wireless             | 17        | 6.69%   |
| Multimedia controller    | 13        | 5.12%   |
| Bluetooth                | 11        | 4.33%   |
| Unassigned class         | 7         | 2.76%   |
| Communication controller | 7         | 2.76%   |
| Storage                  | 6         | 2.36%   |
| Card reader              | 4         | 1.57%   |
| Camera                   | 4         | 1.57%   |
| Net/ethernet             | 3         | 1.18%   |
| Firewire controller      | 3         | 1.18%   |
| Sound                    | 2         | 0.79%   |
| Modem                    | 2         | 0.79%   |
| Storage/ata              | 1         | 0.39%   |
| Flash memory             | 1         | 0.39%   |

