Linux in Greece - Tested Hardware & Statistics (Desktops)
---------------------------------------------------------

A project to collect tested hardware configurations for Linux in Greece.

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

Total: 895

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Dell          | 0D28YY A01                  | [21e722f277](https://linux-hardware.org/?probe=21e722f277) | Feb 02, 2024 |
| ASRock        | X370 Gaming X               | [54fa92de97](https://linux-hardware.org/?probe=54fa92de97) | Feb 01, 2024 |
| Gigabyte      | B365M DS3H                  | [bb6bab84d0](https://linux-hardware.org/?probe=bb6bab84d0) | Jan 31, 2024 |
| Gigabyte      | B365M DS3H                  | [8a8a84c18b](https://linux-hardware.org/?probe=8a8a84c18b) | Jan 31, 2024 |
| MSI           | MS-7345                     | [3453f85c21](https://linux-hardware.org/?probe=3453f85c21) | Jan 30, 2024 |
| ASUSTek       | P5K                         | [2596e1adb2](https://linux-hardware.org/?probe=2596e1adb2) | Jan 29, 2024 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | [37e7442cca](https://linux-hardware.org/?probe=37e7442cca) | Jan 27, 2024 |
| ASRock        | A320M-HDV R4.0              | [64c2e7a1f3](https://linux-hardware.org/?probe=64c2e7a1f3) | Jan 24, 2024 |
| Dell          | 0D28YY A00                  | [8d8d8005b1](https://linux-hardware.org/?probe=8d8d8005b1) | Jan 23, 2024 |
| ASRock        | B450M Pro4                  | [440bc94322](https://linux-hardware.org/?probe=440bc94322) | Jan 19, 2024 |
| ASUSTek       | M4A89GTD-PRO/USB3           | [c69281db28](https://linux-hardware.org/?probe=c69281db28) | Jan 15, 2024 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [fda5ec8f8d](https://linux-hardware.org/?probe=fda5ec8f8d) | Jan 10, 2024 |
| MSI           | 2A78h                       | [dfa343a5d1](https://linux-hardware.org/?probe=dfa343a5d1) | Jan 08, 2024 |
| ASRock        | X370 Gaming X               | [b780de408a](https://linux-hardware.org/?probe=b780de408a) | Jan 05, 2024 |
| MSI           | Z170A PC MATE               | [9a11a14058](https://linux-hardware.org/?probe=9a11a14058) | Jan 04, 2024 |
| AZW           | MINI S 10                   | [3a1b0c6d91](https://linux-hardware.org/?probe=3a1b0c6d91) | Jan 02, 2024 |
| Gigabyte      | Z490 AORUS ELITE AC         | [4faca6dad4](https://linux-hardware.org/?probe=4faca6dad4) | Dec 31, 2023 |
| Dell          | 0PU052                      | [7da56e0b33](https://linux-hardware.org/?probe=7da56e0b33) | Dec 29, 2023 |
| Dell          | 0X7841                      | [3757ec7f5f](https://linux-hardware.org/?probe=3757ec7f5f) | Dec 22, 2023 |
| ASUSTek       | P7H55-M LE                  | [d15476594e](https://linux-hardware.org/?probe=d15476594e) | Dec 22, 2023 |
| ASRock        | G41C-GS                     | [cea8e45a31](https://linux-hardware.org/?probe=cea8e45a31) | Dec 17, 2023 |
| ASRock        | X370 Gaming X               | [3cba3acfa9](https://linux-hardware.org/?probe=3cba3acfa9) | Dec 10, 2023 |
| Lenovo        | ThinkCentre M81 0267A38     | [a9f041fc10](https://linux-hardware.org/?probe=a9f041fc10) | Dec 05, 2023 |
| ASUSTek       | PRIME B450M-A               | [23937a8b80](https://linux-hardware.org/?probe=23937a8b80) | Dec 04, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [4d788fb96c](https://linux-hardware.org/?probe=4d788fb96c) | Dec 04, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | [980caec27f](https://linux-hardware.org/?probe=980caec27f) | Dec 03, 2023 |
| Dell          | 0PU052                      | [4a653cc26a](https://linux-hardware.org/?probe=4a653cc26a) | Dec 02, 2023 |
| Dell          | 0WK833                      | [f363206bab](https://linux-hardware.org/?probe=f363206bab) | Nov 30, 2023 |
| Gigabyte      | H270-HD3-CF                 | [b18e30be2d](https://linux-hardware.org/?probe=b18e30be2d) | Nov 30, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [85217c44b9](https://linux-hardware.org/?probe=85217c44b9) | Nov 27, 2023 |
| Gigabyte      | P55-US3L                    | [fdb0f32546](https://linux-hardware.org/?probe=fdb0f32546) | Nov 26, 2023 |
| Gigabyte      | GA-MA74GMT-S2               | [440e7b6c7c](https://linux-hardware.org/?probe=440e7b6c7c) | Nov 23, 2023 |
| HC Technol... | HCAR5000-MI                 | [718e30ca5e](https://linux-hardware.org/?probe=718e30ca5e) | Nov 22, 2023 |
| ASUSTek       | PRIME B450M-A II            | [eda4b1d020](https://linux-hardware.org/?probe=eda4b1d020) | Nov 21, 2023 |
| ASRock        | A320M-DVS R4.0              | [34d3fcf76b](https://linux-hardware.org/?probe=34d3fcf76b) | Nov 18, 2023 |
| Lenovo        | NOK                         | [1126fee720](https://linux-hardware.org/?probe=1126fee720) | Nov 16, 2023 |
| ASRock        | 970M Pro3                   | [fe2966d899](https://linux-hardware.org/?probe=fe2966d899) | Nov 13, 2023 |
| ASRock        | QC5000-ITX/PH               | [983df9a44c](https://linux-hardware.org/?probe=983df9a44c) | Nov 13, 2023 |
| Gigabyte      | GA-880GMA-USB3              | [3c0f8e3cdd](https://linux-hardware.org/?probe=3c0f8e3cdd) | Nov 13, 2023 |
| Dell          | 0HY9JP A02                  | [d3d9b9a9ba](https://linux-hardware.org/?probe=d3d9b9a9ba) | Nov 12, 2023 |
| Gigabyte      | B460M D3H                   | [45ff3557a5](https://linux-hardware.org/?probe=45ff3557a5) | Nov 11, 2023 |
| HP            | 339A                        | [7be77c764f](https://linux-hardware.org/?probe=7be77c764f) | Nov 09, 2023 |
| ASUSTek       | P8Z68-V PRO GEN3            | [14438106c9](https://linux-hardware.org/?probe=14438106c9) | Nov 09, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [d8ceb3854c](https://linux-hardware.org/?probe=d8ceb3854c) | Nov 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | [fc0052213d](https://linux-hardware.org/?probe=fc0052213d) | Nov 02, 2023 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [aec8690672](https://linux-hardware.org/?probe=aec8690672) | Nov 02, 2023 |
| Gigabyte      | 965P-S3                     | [ae3a4e206c](https://linux-hardware.org/?probe=ae3a4e206c) | Oct 26, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [9a65857d3c](https://linux-hardware.org/?probe=9a65857d3c) | Oct 23, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [001c668695](https://linux-hardware.org/?probe=001c668695) | Oct 23, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [91318c1cf1](https://linux-hardware.org/?probe=91318c1cf1) | Oct 21, 2023 |
| ASUSTek       | PRIME X670E-PRO WIFI        | [62ae73f967](https://linux-hardware.org/?probe=62ae73f967) | Oct 21, 2023 |
| ASRock        | H170 Pro4S                  | [e3960f114d](https://linux-hardware.org/?probe=e3960f114d) | Oct 18, 2023 |
| Dell          | 09KPNV A00                  | [13db34ae64](https://linux-hardware.org/?probe=13db34ae64) | Oct 16, 2023 |
| Gigabyte      | A520M DS3H                  | [e79f4b834d](https://linux-hardware.org/?probe=e79f4b834d) | Oct 13, 2023 |
| ASUSTek       | M5A78L-M LX3                | [88f08528f7](https://linux-hardware.org/?probe=88f08528f7) | Oct 13, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [1cf16b0a10](https://linux-hardware.org/?probe=1cf16b0a10) | Oct 12, 2023 |
| HP            | 212B                        | [7bd2a09958](https://linux-hardware.org/?probe=7bd2a09958) | Oct 11, 2023 |
| HP            | 198E                        | [2fa031a84b](https://linux-hardware.org/?probe=2fa031a84b) | Oct 10, 2023 |
| ASUSTek       | P5Q3                        | [5d51aca6b2](https://linux-hardware.org/?probe=5d51aca6b2) | Oct 08, 2023 |
| ASUSTek       | P5Q3                        | [9beb6f3b26](https://linux-hardware.org/?probe=9beb6f3b26) | Oct 08, 2023 |
| Gigabyte      | G31M-ES2L                   | [7912f11c78](https://linux-hardware.org/?probe=7912f11c78) | Oct 08, 2023 |
| Gigabyte      | B450M DS3H-CF               | [3473652871](https://linux-hardware.org/?probe=3473652871) | Sep 29, 2023 |
| ASRock        | X370 Gaming X               | [ee8f74ab5e](https://linux-hardware.org/?probe=ee8f74ab5e) | Sep 27, 2023 |
| Gigabyte      | MZGLKBP-00                  | [678c17756d](https://linux-hardware.org/?probe=678c17756d) | Sep 23, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [0f28c5cddd](https://linux-hardware.org/?probe=0f28c5cddd) | Sep 20, 2023 |
| Unknown       | Unknown                     | [e4dc880c6f](https://linux-hardware.org/?probe=e4dc880c6f) | Sep 20, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [0d52c010c8](https://linux-hardware.org/?probe=0d52c010c8) | Sep 20, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | [31c6babc26](https://linux-hardware.org/?probe=31c6babc26) | Sep 16, 2023 |
| ASUSTek       | PRIME B660-PLUS D4          | [b4c93a8e2e](https://linux-hardware.org/?probe=b4c93a8e2e) | Sep 12, 2023 |
| Foxconn       | G41MXE/G41MXE-K             | [6e5224fa1d](https://linux-hardware.org/?probe=6e5224fa1d) | Sep 09, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | [bb02ef5cc7](https://linux-hardware.org/?probe=bb02ef5cc7) | Sep 08, 2023 |
| Gigabyte      | MZGLKBP-00                  | [e6c5ae208f](https://linux-hardware.org/?probe=e6c5ae208f) | Sep 02, 2023 |
| MSI           | B450 TOMAHAWK               | [0cfb9de0cf](https://linux-hardware.org/?probe=0cfb9de0cf) | Sep 01, 2023 |
| Gigabyte      | H110M-H-CF                  | [faf094d2ca](https://linux-hardware.org/?probe=faf094d2ca) | Aug 31, 2023 |
| MSI           | 2A78h                       | [78b5a663f2](https://linux-hardware.org/?probe=78b5a663f2) | Aug 31, 2023 |
| Gigabyte      | MZGLKBP-00                  | [2ed0efb0a0](https://linux-hardware.org/?probe=2ed0efb0a0) | Aug 31, 2023 |
| ASRock        | X370 Gaming X               | [d9efc054ab](https://linux-hardware.org/?probe=d9efc054ab) | Aug 28, 2023 |
| MSI           | X470 GAMING PRO CARBON      | [a89271bc7d](https://linux-hardware.org/?probe=a89271bc7d) | Aug 22, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [63d06430e4](https://linux-hardware.org/?probe=63d06430e4) | Aug 18, 2023 |
| ASUSTek       | PRIME Z390-P                | [c8ed9b0cb2](https://linux-hardware.org/?probe=c8ed9b0cb2) | Aug 16, 2023 |
| HP            | 339A                        | [2ecbd957da](https://linux-hardware.org/?probe=2ecbd957da) | Aug 11, 2023 |
| HP            | 339A                        | [782fefbccd](https://linux-hardware.org/?probe=782fefbccd) | Aug 01, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | [88dd1326f2](https://linux-hardware.org/?probe=88dd1326f2) | Jul 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [719e8b9ad3](https://linux-hardware.org/?probe=719e8b9ad3) | Jul 22, 2023 |
| HP            | ProLiant MicroServer Gen... | [a9214c4672](https://linux-hardware.org/?probe=a9214c4672) | Jul 21, 2023 |
| Gigabyte      | Z77X-D3H                    | [8464b9ef50](https://linux-hardware.org/?probe=8464b9ef50) | Jul 17, 2023 |
| MSI           | MAG B460 TOMAHAWK           | [a9f169ce16](https://linux-hardware.org/?probe=a9f169ce16) | Jul 05, 2023 |
| Gigabyte      | B150M-DS3H-CF               | [1a3056376b](https://linux-hardware.org/?probe=1a3056376b) | Jul 02, 2023 |
| Gigabyte      | B150M-DS3H-CF               | [648742f6d3](https://linux-hardware.org/?probe=648742f6d3) | Jul 02, 2023 |
| ASUSTek       | A88XM-E                     | [4557637b8a](https://linux-hardware.org/?probe=4557637b8a) | Jun 26, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [5b780b9ebd](https://linux-hardware.org/?probe=5b780b9ebd) | Jun 24, 2023 |
| Gigabyte      | EP45C-DS3R                  | [655d9d950d](https://linux-hardware.org/?probe=655d9d950d) | Jun 24, 2023 |
| ASRock        | B450 Gaming K4              | [98c46aeea5](https://linux-hardware.org/?probe=98c46aeea5) | Jun 17, 2023 |
| Gigabyte      | Z490I AORUS ULTRA           | [c5cea5f197](https://linux-hardware.org/?probe=c5cea5f197) | Jun 16, 2023 |
| MSI           | MS-7176                     | [952dc4b788](https://linux-hardware.org/?probe=952dc4b788) | Jun 16, 2023 |
| Lenovo        | SHARKBAY 0B98401 PRO        | [ab92fe4791](https://linux-hardware.org/?probe=ab92fe4791) | Jun 13, 2023 |
| Dell          | 0K83V0 A00                  | [fc7fa0850a](https://linux-hardware.org/?probe=fc7fa0850a) | Jun 08, 2023 |
| ASUSTek       | PRIME H610M-E D4            | [827f6ecac2](https://linux-hardware.org/?probe=827f6ecac2) | Jun 07, 2023 |
| ASRock        | Z790 Taichi Carrara         | [bdea2092aa](https://linux-hardware.org/?probe=bdea2092aa) | Jun 06, 2023 |
| ASRock        | X370 Gaming X               | [558e181232](https://linux-hardware.org/?probe=558e181232) | Jun 05, 2023 |
| Unknown       | Intel X79                   | [0e2e65a79e](https://linux-hardware.org/?probe=0e2e65a79e) | Jun 04, 2023 |
| Fujitsu       | D3402-A1 S26361-D3402-A1    | [0ae3ea958a](https://linux-hardware.org/?probe=0ae3ea958a) | May 29, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [bb842bc2d8](https://linux-hardware.org/?probe=bb842bc2d8) | May 28, 2023 |
| MSI           | B450M PRO-VDH MAX           | [cf10c1fb13](https://linux-hardware.org/?probe=cf10c1fb13) | May 21, 2023 |
| Gigabyte      | A320M-H-CF                  | [1c178d1658](https://linux-hardware.org/?probe=1c178d1658) | May 21, 2023 |
| Gigabyte      | Z790 GAMING X AX            | [09f9f2e231](https://linux-hardware.org/?probe=09f9f2e231) | May 17, 2023 |
| Gigabyte      | A320M-H-CF                  | [c8250719d9](https://linux-hardware.org/?probe=c8250719d9) | May 16, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [4ef8752290](https://linux-hardware.org/?probe=4ef8752290) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [b5c9664f50](https://linux-hardware.org/?probe=b5c9664f50) | May 15, 2023 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [bcb5863b0a](https://linux-hardware.org/?probe=bcb5863b0a) | May 09, 2023 |
| ASUSTek       | B85M-GAMER                  | [2f0a5430a3](https://linux-hardware.org/?probe=2f0a5430a3) | May 09, 2023 |
| ASRock        | X370 Gaming X               | [229861cf59](https://linux-hardware.org/?probe=229861cf59) | May 09, 2023 |
| Gigabyte      | Z690 AERO G                 | [7673380766](https://linux-hardware.org/?probe=7673380766) | May 07, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | [00794346db](https://linux-hardware.org/?probe=00794346db) | May 06, 2023 |
| ASRock        | G41C-GS                     | [03076cae9a](https://linux-hardware.org/?probe=03076cae9a) | May 06, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [60c407b4e4](https://linux-hardware.org/?probe=60c407b4e4) | May 05, 2023 |
| ASUSTek       | P5KPL-AM/PS                 | [a5c1634444](https://linux-hardware.org/?probe=a5c1634444) | May 05, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [169cbbf5a9](https://linux-hardware.org/?probe=169cbbf5a9) | May 03, 2023 |
| HP            | 8054                        | [81a57b4a2f](https://linux-hardware.org/?probe=81a57b4a2f) | Apr 29, 2023 |
| ASRock        | A320M-DVS R4.0              | [7e7da68aa3](https://linux-hardware.org/?probe=7e7da68aa3) | Apr 28, 2023 |
| Gigabyte      | EX58-EXTREME                | [3b263c29fc](https://linux-hardware.org/?probe=3b263c29fc) | Apr 26, 2023 |
| Lenovo        | MAHOBAY                     | [ef2dfc5068](https://linux-hardware.org/?probe=ef2dfc5068) | Apr 25, 2023 |
| MSI           | H81M PRO-VD                 | [00ade274cb](https://linux-hardware.org/?probe=00ade274cb) | Apr 24, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | [e4064abe78](https://linux-hardware.org/?probe=e4064abe78) | Apr 24, 2023 |
| MSI           | MS-7235                     | [efaeac524b](https://linux-hardware.org/?probe=efaeac524b) | Apr 18, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [4abccb30eb](https://linux-hardware.org/?probe=4abccb30eb) | Apr 18, 2023 |
| Dell          | 0K83V0 A00                  | [9e0514e439](https://linux-hardware.org/?probe=9e0514e439) | Apr 17, 2023 |
| HP            | 3048h                       | [c771c0b0a7](https://linux-hardware.org/?probe=c771c0b0a7) | Apr 15, 2023 |
| Gigabyte      | H97M-D3H                    | [e48eeac368](https://linux-hardware.org/?probe=e48eeac368) | Apr 14, 2023 |
| Gigabyte      | Z68P-DS3                    | [6026c92eaa](https://linux-hardware.org/?probe=6026c92eaa) | Apr 11, 2023 |
| Gigabyte      | B450 AORUS PRO-CF           | [4a0aa9f6d0](https://linux-hardware.org/?probe=4a0aa9f6d0) | Apr 06, 2023 |
| ASUSTek       | H110M-C                     | [5995f1c96e](https://linux-hardware.org/?probe=5995f1c96e) | Apr 03, 2023 |
| ASUSTek       | H110M-C                     | [b9f944ed6e](https://linux-hardware.org/?probe=b9f944ed6e) | Apr 03, 2023 |
| ASUSTek       | M5A97 R2.0                  | [fe4d7e3bd0](https://linux-hardware.org/?probe=fe4d7e3bd0) | Apr 02, 2023 |
| MSI           | H81M-P33                    | [e2442d5cac](https://linux-hardware.org/?probe=e2442d5cac) | Mar 31, 2023 |
| ASUSTek       | P5KPL-AM/PS                 | [02d9269abc](https://linux-hardware.org/?probe=02d9269abc) | Mar 25, 2023 |
| Dell          | 040DDP A01                  | [0d62bf0ea8](https://linux-hardware.org/?probe=0d62bf0ea8) | Mar 24, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [49bc505f3e](https://linux-hardware.org/?probe=49bc505f3e) | Mar 22, 2023 |
| Gigabyte      | Z690 AERO G                 | [5e8f9cafe8](https://linux-hardware.org/?probe=5e8f9cafe8) | Mar 20, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [e0a2f725e3](https://linux-hardware.org/?probe=e0a2f725e3) | Mar 19, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | [a77ff93d75](https://linux-hardware.org/?probe=a77ff93d75) | Mar 19, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [338ab5a12e](https://linux-hardware.org/?probe=338ab5a12e) | Mar 17, 2023 |
| HP            | 805A                        | [5401e12606](https://linux-hardware.org/?probe=5401e12606) | Mar 14, 2023 |
| HP            | 3397                        | [0b74e11cdd](https://linux-hardware.org/?probe=0b74e11cdd) | Mar 12, 2023 |
| MSI           | MS-7369                     | [7900c0d288](https://linux-hardware.org/?probe=7900c0d288) | Mar 11, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [d49d17f980](https://linux-hardware.org/?probe=d49d17f980) | Mar 10, 2023 |
| ASUSTek       | P5QPL-AM                    | [52b68672fc](https://linux-hardware.org/?probe=52b68672fc) | Mar 03, 2023 |
| MSI           | MS-7250                     | [5127fbfef5](https://linux-hardware.org/?probe=5127fbfef5) | Mar 02, 2023 |
| Gigabyte      | H87M-D3H                    | [3c50af5218](https://linux-hardware.org/?probe=3c50af5218) | Feb 27, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [82fd276e35](https://linux-hardware.org/?probe=82fd276e35) | Feb 19, 2023 |
| Gigabyte      | X570 AORUS ELITE            | [f8f6e2baea](https://linux-hardware.org/?probe=f8f6e2baea) | Feb 19, 2023 |
| Foxconn       | 2ABF                        | [2573ae3149](https://linux-hardware.org/?probe=2573ae3149) | Feb 13, 2023 |
| Gigabyte      | B550M AORUS ELITE           | [f6ed3beac1](https://linux-hardware.org/?probe=f6ed3beac1) | Feb 12, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | [f61d527ad8](https://linux-hardware.org/?probe=f61d527ad8) | Feb 12, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [fdcac99f8d](https://linux-hardware.org/?probe=fdcac99f8d) | Feb 09, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [cdfbd3e72a](https://linux-hardware.org/?probe=cdfbd3e72a) | Feb 09, 2023 |
| HP            | 09F8h                       | [19339c9512](https://linux-hardware.org/?probe=19339c9512) | Feb 02, 2023 |
| MSI           | H510M-A PRO                 | [609fc1e9bb](https://linux-hardware.org/?probe=609fc1e9bb) | Jan 31, 2023 |
| MSI           | 760GM-P23                   | [34fab6626e](https://linux-hardware.org/?probe=34fab6626e) | Jan 29, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e6fedcdbb0](https://linux-hardware.org/?probe=e6fedcdbb0) | Jan 29, 2023 |
| Gigabyte      | H81M-S2PV                   | [4910cfdfcd](https://linux-hardware.org/?probe=4910cfdfcd) | Jan 26, 2023 |
| Dell          | 0Y2K8N A00                  | [7f135346af](https://linux-hardware.org/?probe=7f135346af) | Jan 24, 2023 |
| MSI           | B350 TOMAHAWK ARCTIC        | [10f14c4cbd](https://linux-hardware.org/?probe=10f14c4cbd) | Jan 23, 2023 |
| Gigabyte      | A320M-S2H-CF                | [eb59dcb924](https://linux-hardware.org/?probe=eb59dcb924) | Jan 22, 2023 |
| ASUSTek       | H61M-E                      | [eec3fddef5](https://linux-hardware.org/?probe=eec3fddef5) | Jan 22, 2023 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [f6b68c1767](https://linux-hardware.org/?probe=f6b68c1767) | Jan 19, 2023 |
| DFI           | LP UT X58                   | [e4545a522c](https://linux-hardware.org/?probe=e4545a522c) | Jan 18, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | [d95820725a](https://linux-hardware.org/?probe=d95820725a) | Jan 15, 2023 |
| Gigabyte      | P55-US3L                    | [49e7dc9b0b](https://linux-hardware.org/?probe=49e7dc9b0b) | Jan 12, 2023 |
| Dell          | 0X9M3X A01                  | [0dd66e3ec4](https://linux-hardware.org/?probe=0dd66e3ec4) | Jan 12, 2023 |
| ASUSTek       | H61M-E                      | [38691cf2cc](https://linux-hardware.org/?probe=38691cf2cc) | Jan 11, 2023 |
| ECS           | G31T-M7                     | [161442b256](https://linux-hardware.org/?probe=161442b256) | Jan 10, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [f0aa7955bf](https://linux-hardware.org/?probe=f0aa7955bf) | Jan 08, 2023 |
| ASUSTek       | ROG STRIX X670E-A GAMING... | [dc86d08ec3](https://linux-hardware.org/?probe=dc86d08ec3) | Jan 08, 2023 |
| MSI           | MS-7176                     | [809a107ec7](https://linux-hardware.org/?probe=809a107ec7) | Jan 08, 2023 |
| Gigabyte      | P55-USB3                    | [7c741c709a](https://linux-hardware.org/?probe=7c741c709a) | Jan 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | [6da268e22f](https://linux-hardware.org/?probe=6da268e22f) | Jan 03, 2023 |
| ASRock        | A320M-HDV R4.0              | [d7e15d4cb9](https://linux-hardware.org/?probe=d7e15d4cb9) | Jan 01, 2023 |
| Gigabyte      | B365M DS3H                  | [0dc3c192fd](https://linux-hardware.org/?probe=0dc3c192fd) | Dec 28, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [71bccea2dc](https://linux-hardware.org/?probe=71bccea2dc) | Dec 28, 2022 |
| ASUSTek       | M5A97 R2.0                  | [be1ace7f20](https://linux-hardware.org/?probe=be1ace7f20) | Dec 26, 2022 |
| ASRock        | X570 Taichi                 | [e48882ad67](https://linux-hardware.org/?probe=e48882ad67) | Dec 22, 2022 |
| Dell          | 0J1C3P A00                  | [b65b20a073](https://linux-hardware.org/?probe=b65b20a073) | Dec 22, 2022 |
| ASUSTek       | M3A78-EM                    | [b1fb2ae232](https://linux-hardware.org/?probe=b1fb2ae232) | Dec 22, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [07dc9b96c1](https://linux-hardware.org/?probe=07dc9b96c1) | Dec 21, 2022 |
| Dell          | 0Y2K8N A00                  | [840fbab6e4](https://linux-hardware.org/?probe=840fbab6e4) | Dec 20, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | [c168fe495f](https://linux-hardware.org/?probe=c168fe495f) | Dec 19, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [c0b006673c](https://linux-hardware.org/?probe=c0b006673c) | Dec 18, 2022 |
| Gigabyte      | Z170-HD3P-CF                | [27fdfb657e](https://linux-hardware.org/?probe=27fdfb657e) | Dec 09, 2022 |
| ASUSTek       | H170 PRO GAMING             | [130d5ec0ea](https://linux-hardware.org/?probe=130d5ec0ea) | Dec 09, 2022 |
| MSI           | X470 GAMING PRO CARBON      | [947534b3be](https://linux-hardware.org/?probe=947534b3be) | Dec 09, 2022 |
| Gigabyte      | GA-MA78GM-UD2H              | [415844c745](https://linux-hardware.org/?probe=415844c745) | Dec 08, 2022 |
| Gigabyte      | Z690 AERO G                 | [1bd5929c16](https://linux-hardware.org/?probe=1bd5929c16) | Dec 07, 2022 |
| MSI           | K9A2 Platinum               | [3ce727deb7](https://linux-hardware.org/?probe=3ce727deb7) | Dec 06, 2022 |
| MSI           | MAG B460 TOMAHAWK           | [9289635a09](https://linux-hardware.org/?probe=9289635a09) | Dec 04, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [b43b3227de](https://linux-hardware.org/?probe=b43b3227de) | Dec 04, 2022 |
| ASUSTek       | SABERTOOTH Z97 MARK 2       | [5326fede0a](https://linux-hardware.org/?probe=5326fede0a) | Dec 04, 2022 |
| MSI           | K9A2 Platinum               | [79c823558a](https://linux-hardware.org/?probe=79c823558a) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [dd1874248c](https://linux-hardware.org/?probe=dd1874248c) | Dec 02, 2022 |
| ASUSTek       | ROG STRIX X470-F GAMING     | [eaf129dcfe](https://linux-hardware.org/?probe=eaf129dcfe) | Dec 02, 2022 |
| Gigabyte      | B450 AORUS M                | [d20243efed](https://linux-hardware.org/?probe=d20243efed) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [dee60b9f35](https://linux-hardware.org/?probe=dee60b9f35) | Nov 28, 2022 |
| MSI           | B450M PRO-VDH MAX           | [1651962e5a](https://linux-hardware.org/?probe=1651962e5a) | Nov 28, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [fa5d6f5ca6](https://linux-hardware.org/?probe=fa5d6f5ca6) | Nov 28, 2022 |
| ASRock        | A88M-G                      | [323199813d](https://linux-hardware.org/?probe=323199813d) | Nov 27, 2022 |
| Lenovo        | ThinkCentre M58 6258AP4     | [54d4e3a0ae](https://linux-hardware.org/?probe=54d4e3a0ae) | Nov 26, 2022 |
| Gigabyte      | A320M-S2H-CF                | [452417fa68](https://linux-hardware.org/?probe=452417fa68) | Nov 21, 2022 |
| Gigabyte      | Z370 AORUS Ultra Gaming-... | [34e6521bc8](https://linux-hardware.org/?probe=34e6521bc8) | Nov 21, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [a1b9357fc6](https://linux-hardware.org/?probe=a1b9357fc6) | Nov 20, 2022 |
| ASUSTek       | P8H67-M PRO                 | [55bd7957b4](https://linux-hardware.org/?probe=55bd7957b4) | Nov 20, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [4e04b1a51f](https://linux-hardware.org/?probe=4e04b1a51f) | Nov 19, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | [c7fe31050b](https://linux-hardware.org/?probe=c7fe31050b) | Nov 19, 2022 |
| MSI           | H81M-P33                    | [a535339292](https://linux-hardware.org/?probe=a535339292) | Nov 17, 2022 |
| MSI           | H81M-P33                    | [246d594268](https://linux-hardware.org/?probe=246d594268) | Nov 16, 2022 |
| Acer          | Veriton N4630G              | [f4566a57a9](https://linux-hardware.org/?probe=f4566a57a9) | Nov 16, 2022 |
| HP            | 1495                        | [e29c423a17](https://linux-hardware.org/?probe=e29c423a17) | Nov 15, 2022 |
| ASUSTek       | ProArt B550-CREATOR         | [459c5879e6](https://linux-hardware.org/?probe=459c5879e6) | Nov 15, 2022 |
| Gigabyte      | Z690 AERO G                 | [311a20e88f](https://linux-hardware.org/?probe=311a20e88f) | Nov 13, 2022 |
| Fujitsu Si... | MS-7304VP-A13               | [69b1471202](https://linux-hardware.org/?probe=69b1471202) | Nov 12, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [f49624457d](https://linux-hardware.org/?probe=f49624457d) | Nov 09, 2022 |
| ASRock        | B450 Gaming K4              | [7eca97a8ef](https://linux-hardware.org/?probe=7eca97a8ef) | Nov 08, 2022 |
| Gigabyte      | B450M DS3H-CF               | [605c859789](https://linux-hardware.org/?probe=605c859789) | Nov 06, 2022 |
| ASUSTek       | PRIME B365-PLUS             | [6dd41b1571](https://linux-hardware.org/?probe=6dd41b1571) | Nov 06, 2022 |
| MSI           | Z270 GAMING PRO CARBON      | [07e637210f](https://linux-hardware.org/?probe=07e637210f) | Nov 06, 2022 |
| ASUSTek       | M5A97 R2.0                  | [fecd8f06dd](https://linux-hardware.org/?probe=fecd8f06dd) | Nov 02, 2022 |
| HP            | 18E7                        | [c0d5c58895](https://linux-hardware.org/?probe=c0d5c58895) | Nov 02, 2022 |
| Lenovo        | ThinkCentre M55E 898578G    | [d025c115d8](https://linux-hardware.org/?probe=d025c115d8) | Nov 01, 2022 |
| ASUSTek       | H110M-D                     | [248b9533a3](https://linux-hardware.org/?probe=248b9533a3) | Nov 01, 2022 |
| MSI           | MS-7309                     | [a6b1a7d329](https://linux-hardware.org/?probe=a6b1a7d329) | Oct 31, 2022 |
| MSI           | MS-7309                     | [3c519589ad](https://linux-hardware.org/?probe=3c519589ad) | Oct 30, 2022 |
| Dell          | 0C27VV A01                  | [ed46beadef](https://linux-hardware.org/?probe=ed46beadef) | Oct 30, 2022 |
| Gigabyte      | Z390 AORUS PRO-CF           | [05b5af2e63](https://linux-hardware.org/?probe=05b5af2e63) | Oct 29, 2022 |
| ASRock        | FM2A88X-ITX+                | [00b65eaa83](https://linux-hardware.org/?probe=00b65eaa83) | Oct 29, 2022 |
| Gigabyte      | GA-MA790FX-DQ6              | [8ba31a020c](https://linux-hardware.org/?probe=8ba31a020c) | Oct 28, 2022 |
| Dell          | 0KRC95 A02                  | [8afc3da46d](https://linux-hardware.org/?probe=8afc3da46d) | Oct 28, 2022 |
| ASUSTek       | PRIME B450M-A               | [19c3c8e1f6](https://linux-hardware.org/?probe=19c3c8e1f6) | Oct 23, 2022 |
| ASUSTek       | PRIME B550M-A               | [d135b32e8b](https://linux-hardware.org/?probe=d135b32e8b) | Oct 21, 2022 |
| HP            | 339A                        | [bea86a9671](https://linux-hardware.org/?probe=bea86a9671) | Oct 19, 2022 |
| Gigabyte      | P55-USB3                    | [6f441865a9](https://linux-hardware.org/?probe=6f441865a9) | Oct 19, 2022 |
| Dell          | 0C27VV A01                  | [23c855f88b](https://linux-hardware.org/?probe=23c855f88b) | Oct 17, 2022 |
| Dell          | 0C27VV A01                  | [ebe65ec5fa](https://linux-hardware.org/?probe=ebe65ec5fa) | Oct 17, 2022 |
| MSI           | B550M PRO-VDH               | [c4e09cdf87](https://linux-hardware.org/?probe=c4e09cdf87) | Oct 09, 2022 |
| Gigabyte      | P55M-UD2                    | [e9627c4c34](https://linux-hardware.org/?probe=e9627c4c34) | Oct 07, 2022 |
| Gigabyte      | P55-USB3                    | [adf7389f06](https://linux-hardware.org/?probe=adf7389f06) | Sep 30, 2022 |
| NU591         | 1.0                         | [6be5a78c90](https://linux-hardware.org/?probe=6be5a78c90) | Sep 27, 2022 |
| MSI           | MPG B550 GAMING PLUS        | [59c4a7e761](https://linux-hardware.org/?probe=59c4a7e761) | Sep 23, 2022 |
| MSI           | H310M PRO-VH                | [c11e067cb5](https://linux-hardware.org/?probe=c11e067cb5) | Sep 22, 2022 |
| ASRock        | H81M-GL                     | [fe7e5bbc9c](https://linux-hardware.org/?probe=fe7e5bbc9c) | Sep 21, 2022 |
| NU591         | 1.0                         | [6e29ae977f](https://linux-hardware.org/?probe=6e29ae977f) | Sep 21, 2022 |
| ASUSTek       | PRIME X570-P                | [a1f237c86a](https://linux-hardware.org/?probe=a1f237c86a) | Sep 20, 2022 |
| Gigabyte      | H97M-D3H                    | [57db36ecc9](https://linux-hardware.org/?probe=57db36ecc9) | Sep 19, 2022 |
| ASUSTek       | H81M-K                      | [fe48912653](https://linux-hardware.org/?probe=fe48912653) | Sep 15, 2022 |
| MSI           | MAG B460 TOMAHAWK           | [29eaefa02d](https://linux-hardware.org/?probe=29eaefa02d) | Sep 06, 2022 |
| MSI           | MAG B460 TOMAHAWK           | [4ca1a490f8](https://linux-hardware.org/?probe=4ca1a490f8) | Sep 05, 2022 |
| Dell          | 0KWVT8 A03                  | [bd0c518002](https://linux-hardware.org/?probe=bd0c518002) | Sep 03, 2022 |
| ASUSTek       | M4A785TD-V EVO              | [ba1027940d](https://linux-hardware.org/?probe=ba1027940d) | Sep 03, 2022 |
| Gigabyte      | G31M-S2C                    | [61a4780992](https://linux-hardware.org/?probe=61a4780992) | Aug 30, 2022 |
| Gigabyte      | G31M-S2C                    | [8beed8e261](https://linux-hardware.org/?probe=8beed8e261) | Aug 30, 2022 |
| HP            | 339A                        | [961ac650aa](https://linux-hardware.org/?probe=961ac650aa) | Aug 24, 2022 |
| ASRock        | H310CM-DVS                  | [17f6682bf3](https://linux-hardware.org/?probe=17f6682bf3) | Aug 20, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | [0b9e6d6ad9](https://linux-hardware.org/?probe=0b9e6d6ad9) | Aug 19, 2022 |
| Gigabyte      | B550 AORUS ELITE AX         | [49943f84c8](https://linux-hardware.org/?probe=49943f84c8) | Aug 18, 2022 |
| ASUSTek       | ProArt B660-CREATOR D4      | [f9f180ac3a](https://linux-hardware.org/?probe=f9f180ac3a) | Aug 18, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | [3ab7d6393c](https://linux-hardware.org/?probe=3ab7d6393c) | Aug 17, 2022 |
| ASUSTek       | P5K SE                      | [59168fc3cb](https://linux-hardware.org/?probe=59168fc3cb) | Aug 14, 2022 |
| ASRock        | J4125B-ITX                  | [6e4ca6823f](https://linux-hardware.org/?probe=6e4ca6823f) | Aug 14, 2022 |
| ASRock        | J4125B-ITX                  | [81a8491905](https://linux-hardware.org/?probe=81a8491905) | Aug 14, 2022 |
| Gigabyte      | B85-HD3                     | [1498e07a4b](https://linux-hardware.org/?probe=1498e07a4b) | Aug 04, 2022 |
| MSI           | H110M PRO-VH                | [8bdd8d91db](https://linux-hardware.org/?probe=8bdd8d91db) | Aug 04, 2022 |
| ASUSTek       | PRIME B250-PLUS             | [dcc08c0fa5](https://linux-hardware.org/?probe=dcc08c0fa5) | Aug 03, 2022 |
| Gigabyte      | B550 AORUS ELITE AX         | [eee9c60bec](https://linux-hardware.org/?probe=eee9c60bec) | Jul 29, 2022 |
| MSI           | H110M PRO-VH                | [2058561297](https://linux-hardware.org/?probe=2058561297) | Jul 28, 2022 |
| Gigabyte      | Z97X-UD5H                   | [9b3bb82b80](https://linux-hardware.org/?probe=9b3bb82b80) | Jul 28, 2022 |
| MSI           | B450 TOMAHAWK MAX           | [8b520883ad](https://linux-hardware.org/?probe=8b520883ad) | Jul 27, 2022 |
| Gigabyte      | Z68P-DS3                    | [a296eed968](https://linux-hardware.org/?probe=a296eed968) | Jul 27, 2022 |
| Gigabyte      | Z68P-DS3                    | [24ad5aed74](https://linux-hardware.org/?probe=24ad5aed74) | Jul 27, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [52ca04ad6b](https://linux-hardware.org/?probe=52ca04ad6b) | Jul 20, 2022 |
| ASUSTek       | H81M-K                      | [1d2991137d](https://linux-hardware.org/?probe=1d2991137d) | Jul 15, 2022 |
| ASUSTek       | M5A97 R2.0                  | [8bdaa5b844](https://linux-hardware.org/?probe=8bdaa5b844) | Jul 13, 2022 |
| ASUSTek       | P5Q3                        | [5fb3e2b502](https://linux-hardware.org/?probe=5fb3e2b502) | Jul 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [987d9aa4d3](https://linux-hardware.org/?probe=987d9aa4d3) | Jul 01, 2022 |
| ASUSTek       | H81M-K                      | [08ed20d4da](https://linux-hardware.org/?probe=08ed20d4da) | Jul 01, 2022 |
| MSI           | MPG X570 GAMING PRO CARB... | [c6c59e12b6](https://linux-hardware.org/?probe=c6c59e12b6) | Jun 25, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [eb61c79793](https://linux-hardware.org/?probe=eb61c79793) | Jun 21, 2022 |
| Gigabyte      | 965P-S3                     | [0beb9ce480](https://linux-hardware.org/?probe=0beb9ce480) | Jun 19, 2022 |
| ASRock        | X370 Gaming-ITX/ac          | [292cc4bcab](https://linux-hardware.org/?probe=292cc4bcab) | Jun 17, 2022 |
| Gigabyte      | X570S UD                    | [98f8907a6b](https://linux-hardware.org/?probe=98f8907a6b) | Jun 14, 2022 |
| Gigabyte      | H510M H                     | [75fd209e13](https://linux-hardware.org/?probe=75fd209e13) | Jun 14, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | [70254d6e4d](https://linux-hardware.org/?probe=70254d6e4d) | Jun 08, 2022 |
| Lenovo        | 3140 NOK                    | [03619a223f](https://linux-hardware.org/?probe=03619a223f) | Jun 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [51e3142bae](https://linux-hardware.org/?probe=51e3142bae) | Jun 02, 2022 |
| ASUSTek       | H81M-K                      | [22fb59a94a](https://linux-hardware.org/?probe=22fb59a94a) | May 19, 2022 |
| ASUSTek       | P8H61 PRO                   | [87a148ac90](https://linux-hardware.org/?probe=87a148ac90) | May 18, 2022 |
| ASUSTek       | H61M-E                      | [1dc25cb237](https://linux-hardware.org/?probe=1dc25cb237) | May 17, 2022 |
| Gigabyte      | X58A-UD3R                   | [0e9a009c11](https://linux-hardware.org/?probe=0e9a009c11) | May 13, 2022 |
| Gigabyte      | X58A-UD3R                   | [ed659a9633](https://linux-hardware.org/?probe=ed659a9633) | May 13, 2022 |
| AOpen         | i67QMx-DV R1.00BC1 55MP6... | [151db99970](https://linux-hardware.org/?probe=151db99970) | May 11, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [5d59ce5dd7](https://linux-hardware.org/?probe=5d59ce5dd7) | May 11, 2022 |
| ASUSTek       | Z97-PRO GAMER               | [173fac4f5b](https://linux-hardware.org/?probe=173fac4f5b) | May 11, 2022 |
| HP            | 3031h                       | [4a57ff5761](https://linux-hardware.org/?probe=4a57ff5761) | May 10, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | [8caf6e2b66](https://linux-hardware.org/?probe=8caf6e2b66) | May 09, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | [4242d236c5](https://linux-hardware.org/?probe=4242d236c5) | May 09, 2022 |
| ASUSTek       | Z170-A                      | [bdfe0722a7](https://linux-hardware.org/?probe=bdfe0722a7) | May 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | [4fe934e84d](https://linux-hardware.org/?probe=4fe934e84d) | May 06, 2022 |
| ASRock        | AB350 Gaming-ITX/ac         | [9967806049](https://linux-hardware.org/?probe=9967806049) | May 02, 2022 |
| MSI           | B550-A PRO                  | [d2903d25c5](https://linux-hardware.org/?probe=d2903d25c5) | Apr 30, 2022 |
| Gigabyte      | B450 AORUS M                | [de4ae72708](https://linux-hardware.org/?probe=de4ae72708) | Apr 28, 2022 |
| Lenovo        | MAHOBAY 0B98401 PRO         | [c6bf48bfb3](https://linux-hardware.org/?probe=c6bf48bfb3) | Apr 27, 2022 |
| ASUSTek       | P5P43TD                     | [8c7c0bd289](https://linux-hardware.org/?probe=8c7c0bd289) | Apr 21, 2022 |
| ASUSTek       | TUF Z390-PLUS GAMING        | [dddd6b6edd](https://linux-hardware.org/?probe=dddd6b6edd) | Apr 18, 2022 |
| Dell          | 04PT3G A00                  | [a10754ebca](https://linux-hardware.org/?probe=a10754ebca) | Apr 14, 2022 |
| ASRock        | H97 Pro4                    | [0ad016db29](https://linux-hardware.org/?probe=0ad016db29) | Apr 13, 2022 |
| Gigabyte      | Z68MA-D2H-B3                | [5c247da651](https://linux-hardware.org/?probe=5c247da651) | Apr 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [761e954b86](https://linux-hardware.org/?probe=761e954b86) | Apr 07, 2022 |
| ASRock        | X399 Phantom Gaming 6       | [111167cacb](https://linux-hardware.org/?probe=111167cacb) | Apr 07, 2022 |
| Lenovo        | SHARKBAY SDK0J40705 WIN     | [374819f582](https://linux-hardware.org/?probe=374819f582) | Apr 04, 2022 |
| Gigabyte      | Z270-Gaming K3              | [492c2c7bf4](https://linux-hardware.org/?probe=492c2c7bf4) | Apr 03, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | [8d251b1b2a](https://linux-hardware.org/?probe=8d251b1b2a) | Apr 03, 2022 |
| Gigabyte      | Z270-Gaming K3              | [97969b1325](https://linux-hardware.org/?probe=97969b1325) | Apr 03, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [348af6c202](https://linux-hardware.org/?probe=348af6c202) | Apr 02, 2022 |
| ASUSTek       | PRIME X570-P                | [e237e56d72](https://linux-hardware.org/?probe=e237e56d72) | Apr 02, 2022 |
| ASUSTek       | P8Z77-V PRO                 | [3ac2dfc728](https://linux-hardware.org/?probe=3ac2dfc728) | Apr 01, 2022 |
| ASRock        | B75M R2.0                   | [ee7a1d8721](https://linux-hardware.org/?probe=ee7a1d8721) | Mar 30, 2022 |
| ASRock        | M3N78D FX                   | [66bb134c6c](https://linux-hardware.org/?probe=66bb134c6c) | Mar 29, 2022 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [6335525127](https://linux-hardware.org/?probe=6335525127) | Mar 28, 2022 |
| ASRock        | N68-GS4 FX R2.0             | [d01df98d83](https://linux-hardware.org/?probe=d01df98d83) | Mar 28, 2022 |
| ASRock        | M3N78D FX                   | [3ebcef4241](https://linux-hardware.org/?probe=3ebcef4241) | Mar 28, 2022 |
| Gigabyte      | B450 AORUS M                | [789a97d437](https://linux-hardware.org/?probe=789a97d437) | Mar 20, 2022 |
| ASUSTek       | H81M-K                      | [9055c398c9](https://linux-hardware.org/?probe=9055c398c9) | Mar 18, 2022 |
| Gigabyte      | AB350M-Gaming 3-CF          | [4fa05350b7](https://linux-hardware.org/?probe=4fa05350b7) | Mar 17, 2022 |
| MSI           | B550-A PRO                  | [44e9c813e9](https://linux-hardware.org/?probe=44e9c813e9) | Mar 14, 2022 |
| HP            | 1850                        | [7e0b4230d4](https://linux-hardware.org/?probe=7e0b4230d4) | Mar 11, 2022 |
| MSI           | MS-7091                     | [6ff1d651e4](https://linux-hardware.org/?probe=6ff1d651e4) | Mar 11, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | [772e020316](https://linux-hardware.org/?probe=772e020316) | Mar 09, 2022 |
| ASUSTek       | P5GC-MX/MEDION/SI           | [2a7edc452e](https://linux-hardware.org/?probe=2a7edc452e) | Mar 09, 2022 |
| Gigabyte      | F2A85XM-D3H                 | [cf20f6e233](https://linux-hardware.org/?probe=cf20f6e233) | Mar 09, 2022 |
| MSI           | MS-7091                     | [71aaa6a920](https://linux-hardware.org/?probe=71aaa6a920) | Mar 09, 2022 |
| MSI           | MS-7091                     | [b08ddd1115](https://linux-hardware.org/?probe=b08ddd1115) | Mar 09, 2022 |
| Gigabyte      | X58A-UD3R                   | [f56996aab6](https://linux-hardware.org/?probe=f56996aab6) | Mar 07, 2022 |
| HP            | 3048h                       | [cb9a7b7f4f](https://linux-hardware.org/?probe=cb9a7b7f4f) | Mar 05, 2022 |
| Gigabyte      | X58A-UD3R                   | [3cc5bac970](https://linux-hardware.org/?probe=3cc5bac970) | Mar 02, 2022 |
| ASUSTek       | PRIME B350M-A               | [299a727e8a](https://linux-hardware.org/?probe=299a727e8a) | Mar 02, 2022 |
| ASUSTek       | H81M-K                      | [2789dc5384](https://linux-hardware.org/?probe=2789dc5384) | Mar 02, 2022 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [3f6b2ab46e](https://linux-hardware.org/?probe=3f6b2ab46e) | Mar 01, 2022 |
| Gigabyte      | H410M S2H V3                | [e5da146c8e](https://linux-hardware.org/?probe=e5da146c8e) | Feb 27, 2022 |
| Dell          | 0N185P A01                  | [996f9f7805](https://linux-hardware.org/?probe=996f9f7805) | Feb 24, 2022 |
| Gigabyte      | MZBSWMP-00                  | [fc444df804](https://linux-hardware.org/?probe=fc444df804) | Feb 20, 2022 |
| Gigabyte      | H61M-S2PV                   | [9e10ad29c3](https://linux-hardware.org/?probe=9e10ad29c3) | Feb 19, 2022 |
| Gigabyte      | X58A-UD3R                   | [87774dacdd](https://linux-hardware.org/?probe=87774dacdd) | Feb 15, 2022 |
| Gigabyte      | X58A-UD3R                   | [3cf4dc7f97](https://linux-hardware.org/?probe=3cf4dc7f97) | Feb 15, 2022 |
| MSI           | MS-7176                     | [b54631ff57](https://linux-hardware.org/?probe=b54631ff57) | Feb 14, 2022 |
| Gigabyte      | B250M-DS3H-CF               | [57de891506](https://linux-hardware.org/?probe=57de891506) | Feb 12, 2022 |
| Gigabyte      | Z87N-WIFI                   | [e86fa9ee02](https://linux-hardware.org/?probe=e86fa9ee02) | Feb 09, 2022 |
| Gigabyte      | Z87N-WIFI                   | [1b6aa0ce08](https://linux-hardware.org/?probe=1b6aa0ce08) | Feb 09, 2022 |
| ASUSTek       | PRIME B350-PLUS             | [df711c6514](https://linux-hardware.org/?probe=df711c6514) | Feb 03, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | [4dc312f4f3](https://linux-hardware.org/?probe=4dc312f4f3) | Feb 02, 2022 |
| Lenovo        | SDK0E50510 WIN              | [f317005b0a](https://linux-hardware.org/?probe=f317005b0a) | Feb 02, 2022 |
| Lenovo        | NOK                         | [8905840b45](https://linux-hardware.org/?probe=8905840b45) | Feb 02, 2022 |
| ASUSTek       | H110M-D                     | [3dbf1d9544](https://linux-hardware.org/?probe=3dbf1d9544) | Jan 31, 2022 |
| HP            | 8434 11                     | [76a7851e7f](https://linux-hardware.org/?probe=76a7851e7f) | Jan 28, 2022 |
| VIA Techno... | VT8366-8233/5               | [e285c87c48](https://linux-hardware.org/?probe=e285c87c48) | Jan 27, 2022 |
| VIA Techno... | VT8366-8233/5               | [54ce61fa7e](https://linux-hardware.org/?probe=54ce61fa7e) | Jan 25, 2022 |
| MSI           | A88XM-E45                   | [6a25ca99d2](https://linux-hardware.org/?probe=6a25ca99d2) | Jan 24, 2022 |
| Gigabyte      | H410M H V3                  | [f6b7e2e2e6](https://linux-hardware.org/?probe=f6b7e2e2e6) | Jan 24, 2022 |
| Lenovo        | 314F NO DPK                 | [07bd238c48](https://linux-hardware.org/?probe=07bd238c48) | Jan 24, 2022 |
| ASRock        | A300M-STX                   | [13de9d767d](https://linux-hardware.org/?probe=13de9d767d) | Jan 21, 2022 |
| MSI           | H310M PRO-VH                | [68c71dac17](https://linux-hardware.org/?probe=68c71dac17) | Jan 21, 2022 |
| ASRock        | G41C-VS                     | [4dbb4b7fad](https://linux-hardware.org/?probe=4dbb4b7fad) | Jan 21, 2022 |
| Albatron      | PM73V                       | [7bd3956f1f](https://linux-hardware.org/?probe=7bd3956f1f) | Jan 21, 2022 |
| ASUSTek       | H81M-K                      | [e5d70436b2](https://linux-hardware.org/?probe=e5d70436b2) | Jan 21, 2022 |
| HP            | 8455                        | [fbf272366c](https://linux-hardware.org/?probe=fbf272366c) | Jan 20, 2022 |
| ASUSTek       | H110M-D                     | [b105d56395](https://linux-hardware.org/?probe=b105d56395) | Jan 19, 2022 |
| ASUSTek       | P5LD2                       | [00ec990ce2](https://linux-hardware.org/?probe=00ec990ce2) | Jan 19, 2022 |
| Dell          | 0KP561                      | [1b772786e5](https://linux-hardware.org/?probe=1b772786e5) | Jan 19, 2022 |
| Dell          | 0FH884                      | [5ffacf9f99](https://linux-hardware.org/?probe=5ffacf9f99) | Jan 19, 2022 |
| Dell          | 0UG982                      | [c85c923e97](https://linux-hardware.org/?probe=c85c923e97) | Jan 19, 2022 |
| Dell          | 0X7841                      | [40600195c8](https://linux-hardware.org/?probe=40600195c8) | Jan 19, 2022 |
| Lenovo        | SDK0E50510 WIN              | [597677191c](https://linux-hardware.org/?probe=597677191c) | Jan 19, 2022 |
| Dell          | 0UG982                      | [686f3558d2](https://linux-hardware.org/?probe=686f3558d2) | Jan 19, 2022 |
| Lenovo        | 314F NO DPK                 | [f4f3386726](https://linux-hardware.org/?probe=f4f3386726) | Jan 19, 2022 |
| Dell          | 0FH884                      | [f6e9bda3a9](https://linux-hardware.org/?probe=f6e9bda3a9) | Jan 19, 2022 |
| Lenovo        | 314F NO DPK                 | [b9153e0c28](https://linux-hardware.org/?probe=b9153e0c28) | Jan 19, 2022 |
| HP            | 18E7                        | [b68364ed90](https://linux-hardware.org/?probe=b68364ed90) | Jan 19, 2022 |
| Dell          | 0HY9JP A02                  | [8314cd9ba6](https://linux-hardware.org/?probe=8314cd9ba6) | Jan 19, 2022 |
| Dell          | 0UG982                      | [38c30e280b](https://linux-hardware.org/?probe=38c30e280b) | Jan 19, 2022 |
| Gigabyte      | H81M-S2PV                   | [f2d5dba7ff](https://linux-hardware.org/?probe=f2d5dba7ff) | Jan 19, 2022 |
| Dell          | 0FH884                      | [083697081f](https://linux-hardware.org/?probe=083697081f) | Jan 19, 2022 |
| MSI           | H310M PRO-VH                | [844791ed3e](https://linux-hardware.org/?probe=844791ed3e) | Jan 19, 2022 |
| ASRock        | B550M Steel Legend          | [0601abdfa6](https://linux-hardware.org/?probe=0601abdfa6) | Jan 18, 2022 |
| HP            | 18E7                        | [9fedcb7ff7](https://linux-hardware.org/?probe=9fedcb7ff7) | Jan 18, 2022 |
| HP            | 18E7                        | [48871270a2](https://linux-hardware.org/?probe=48871270a2) | Jan 18, 2022 |
| HP            | 18E7                        | [ca38c856e1](https://linux-hardware.org/?probe=ca38c856e1) | Jan 18, 2022 |
| HP            | 18E7                        | [a4df88b38f](https://linux-hardware.org/?probe=a4df88b38f) | Jan 18, 2022 |
| HP            | 18E7                        | [a745b9add0](https://linux-hardware.org/?probe=a745b9add0) | Jan 18, 2022 |
| HP            | 18E7                        | [b69abe6fd4](https://linux-hardware.org/?probe=b69abe6fd4) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | [9753f9164a](https://linux-hardware.org/?probe=9753f9164a) | Jan 18, 2022 |
| Lenovo        | ThinkCentre M58 7373W43     | [2d7a6e6cb6](https://linux-hardware.org/?probe=2d7a6e6cb6) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | [51484889f9](https://linux-hardware.org/?probe=51484889f9) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | [4ca462c89a](https://linux-hardware.org/?probe=4ca462c89a) | Jan 18, 2022 |
| Dell          | 0HY9JP A02                  | [c4c9f4b0a9](https://linux-hardware.org/?probe=c4c9f4b0a9) | Jan 18, 2022 |
| HP            | 8434 11                     | [4a128d2bb2](https://linux-hardware.org/?probe=4a128d2bb2) | Jan 18, 2022 |
| HP            | 18E7                        | [97d4bc7367](https://linux-hardware.org/?probe=97d4bc7367) | Jan 18, 2022 |
| Lenovo        | NOK                         | [7ae2819a6f](https://linux-hardware.org/?probe=7ae2819a6f) | Jan 18, 2022 |
| HP            | 18E7                        | [e86d0cc284](https://linux-hardware.org/?probe=e86d0cc284) | Jan 18, 2022 |
| Lenovo        | SDK0E50510 WIN              | [022f56a960](https://linux-hardware.org/?probe=022f56a960) | Jan 18, 2022 |
| HP            | 18E7                        | [0d2a09f683](https://linux-hardware.org/?probe=0d2a09f683) | Jan 18, 2022 |
| HP            | 8455                        | [639182896b](https://linux-hardware.org/?probe=639182896b) | Jan 18, 2022 |
| ASUSTek       | H81M-C                      | [f4bb742149](https://linux-hardware.org/?probe=f4bb742149) | Jan 17, 2022 |
| ASUSTek       | P5LD2                       | [b972c7929f](https://linux-hardware.org/?probe=b972c7929f) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [9a6c2f82f1](https://linux-hardware.org/?probe=9a6c2f82f1) | Jan 17, 2022 |
| Dell          | 0UG982                      | [684478b2fb](https://linux-hardware.org/?probe=684478b2fb) | Jan 17, 2022 |
| Gigabyte      | H410M H V3                  | [13b01fb40a](https://linux-hardware.org/?probe=13b01fb40a) | Jan 17, 2022 |
| ASUSTek       | PRIME H310M-D R2.0          | [385f76b996](https://linux-hardware.org/?probe=385f76b996) | Jan 17, 2022 |
| Gigabyte      | X58A-UD3R                   | [dc02dbb307](https://linux-hardware.org/?probe=dc02dbb307) | Jan 16, 2022 |
| ASUSTek       | H81M-C                      | [f21bf32c9a](https://linux-hardware.org/?probe=f21bf32c9a) | Jan 15, 2022 |
| ASUSTek       | H81M-K                      | [f1858e63f4](https://linux-hardware.org/?probe=f1858e63f4) | Jan 14, 2022 |
| Gigabyte      | P55-USB3                    | [07d50b5a0a](https://linux-hardware.org/?probe=07d50b5a0a) | Jan 14, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [32b2cea437](https://linux-hardware.org/?probe=32b2cea437) | Jan 10, 2022 |
| Gigabyte      | A320M-H-CF                  | [c09f135f63](https://linux-hardware.org/?probe=c09f135f63) | Jan 09, 2022 |
| ASUSTek       | PRIME B350M-A               | [7887040435](https://linux-hardware.org/?probe=7887040435) | Jan 05, 2022 |
| ASRock        | H97M Pro4                   | [92a6f429b5](https://linux-hardware.org/?probe=92a6f429b5) | Jan 05, 2022 |
| ASUSTek       | ROG STRIX B550-E GAMING     | [f5f5eadcd4](https://linux-hardware.org/?probe=f5f5eadcd4) | Jan 04, 2022 |
| ECS           | G31T-M7                     | [8cd5d79924](https://linux-hardware.org/?probe=8cd5d79924) | Dec 31, 2021 |
| ECS           | G31T-M7                     | [9ebfb53472](https://linux-hardware.org/?probe=9ebfb53472) | Dec 31, 2021 |
| ASRock        | B75M R2.0                   | [8e4a08a77a](https://linux-hardware.org/?probe=8e4a08a77a) | Dec 26, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [68ea35c97d](https://linux-hardware.org/?probe=68ea35c97d) | Dec 25, 2021 |
| Foxconn       | 2ABF                        | [fdc6aac853](https://linux-hardware.org/?probe=fdc6aac853) | Dec 25, 2021 |
| Gigabyte      | H170M-D3H DDR3-CF           | [537cb36279](https://linux-hardware.org/?probe=537cb36279) | Dec 25, 2021 |
| MSI           | H81M PRO-VD                 | [b0c70d78fd](https://linux-hardware.org/?probe=b0c70d78fd) | Dec 22, 2021 |
| Gigabyte      | Z390 GAMING X-CF            | [8962cfd1c6](https://linux-hardware.org/?probe=8962cfd1c6) | Dec 19, 2021 |
| Dell          | 0MN1TX A01                  | [312bd0bfd8](https://linux-hardware.org/?probe=312bd0bfd8) | Dec 18, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [a2ee48eeb1](https://linux-hardware.org/?probe=a2ee48eeb1) | Dec 16, 2021 |
| Gigabyte      | B75M-D3H                    | [495d348f1e](https://linux-hardware.org/?probe=495d348f1e) | Dec 15, 2021 |
| Gigabyte      | 970A-DS3P                   | [da23db2916](https://linux-hardware.org/?probe=da23db2916) | Dec 13, 2021 |
| ASUSTek       | P8P67 LE                    | [b86c41a0a9](https://linux-hardware.org/?probe=b86c41a0a9) | Dec 13, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [ac3e0f0271](https://linux-hardware.org/?probe=ac3e0f0271) | Dec 11, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | [1876329ada](https://linux-hardware.org/?probe=1876329ada) | Dec 10, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c97b5a008f](https://linux-hardware.org/?probe=c97b5a008f) | Dec 09, 2021 |
| MSI           | MAG B550M BAZOOKA           | [11f31cc288](https://linux-hardware.org/?probe=11f31cc288) | Dec 08, 2021 |
| Gigabyte      | Z97P-D3                     | [abc89c9b78](https://linux-hardware.org/?probe=abc89c9b78) | Dec 07, 2021 |
| Gateway       | DT55                        | [efc935f11c](https://linux-hardware.org/?probe=efc935f11c) | Dec 06, 2021 |
| Gigabyte      | G31M-S2C                    | [75933dd4ba](https://linux-hardware.org/?probe=75933dd4ba) | Dec 06, 2021 |
| Dell          | 0WK833                      | [59fed7d754](https://linux-hardware.org/?probe=59fed7d754) | Nov 30, 2021 |
| ASUSTek       | P5QPL-AM                    | [6e37f9cd8a](https://linux-hardware.org/?probe=6e37f9cd8a) | Nov 29, 2021 |
| Gigabyte      | B450M DS3H-CF               | [999b38ba1f](https://linux-hardware.org/?probe=999b38ba1f) | Nov 28, 2021 |
| Dell          | 042P49 A02                  | [f6d9c481bd](https://linux-hardware.org/?probe=f6d9c481bd) | Nov 27, 2021 |
| Gigabyte      | P35-S3G                     | [f8b94398df](https://linux-hardware.org/?probe=f8b94398df) | Nov 27, 2021 |
| ASRock        | B450 Gaming K4              | [ba4141a214](https://linux-hardware.org/?probe=ba4141a214) | Nov 26, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [b6396cac2d](https://linux-hardware.org/?probe=b6396cac2d) | Nov 25, 2021 |
| Gigabyte      | B450M DS3H-CF               | [2c14d4d6ad](https://linux-hardware.org/?probe=2c14d4d6ad) | Nov 23, 2021 |
| ASRock        | B75M R2.0                   | [000f6b6f44](https://linux-hardware.org/?probe=000f6b6f44) | Nov 20, 2021 |
| HP            | 304Bh                       | [d6f490c0ea](https://linux-hardware.org/?probe=d6f490c0ea) | Nov 19, 2021 |
| Dell          | 0Y2K8N A00                  | [db79ad16d3](https://linux-hardware.org/?probe=db79ad16d3) | Nov 16, 2021 |
| MSI           | B350 TOMAHAWK ARCTIC        | [9cc745f754](https://linux-hardware.org/?probe=9cc745f754) | Nov 16, 2021 |
| Gigabyte      | 945P-S3                     | [770408fd3d](https://linux-hardware.org/?probe=770408fd3d) | Nov 14, 2021 |
| Gigabyte      | 945P-S3                     | [2cf9966c22](https://linux-hardware.org/?probe=2cf9966c22) | Nov 14, 2021 |
| Gigabyte      | G41M-Combo                  | [7a3d3a2f06](https://linux-hardware.org/?probe=7a3d3a2f06) | Nov 12, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [867958b2cc](https://linux-hardware.org/?probe=867958b2cc) | Nov 11, 2021 |
| Dell          | 0DXJD9 A00                  | [e9abfeb7a2](https://linux-hardware.org/?probe=e9abfeb7a2) | Nov 11, 2021 |
| HP            | 339A                        | [702ccff1e4](https://linux-hardware.org/?probe=702ccff1e4) | Nov 09, 2021 |
| MSI           | B150M MORTAR                | [58d8ce0102](https://linux-hardware.org/?probe=58d8ce0102) | Nov 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [d1dcf79c72](https://linux-hardware.org/?probe=d1dcf79c72) | Nov 05, 2021 |
| ASUSTek       | Z170-A                      | [02cc756dd4](https://linux-hardware.org/?probe=02cc756dd4) | Oct 26, 2021 |
| Lenovo        | ThinkCentre M71e 3167A46    | [afc98aba09](https://linux-hardware.org/?probe=afc98aba09) | Oct 20, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [c76a2534a0](https://linux-hardware.org/?probe=c76a2534a0) | Oct 19, 2021 |
| HP            | 8717                        | [23f7ea44ce](https://linux-hardware.org/?probe=23f7ea44ce) | Oct 18, 2021 |
| HP            | 1496                        | [f438fdb757](https://linux-hardware.org/?probe=f438fdb757) | Oct 17, 2021 |
| MSI           | H110I PRO                   | [0aeac6b99e](https://linux-hardware.org/?probe=0aeac6b99e) | Oct 16, 2021 |
| HP            | 1495                        | [e7c0f59f92](https://linux-hardware.org/?probe=e7c0f59f92) | Oct 15, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [a671b6ab07](https://linux-hardware.org/?probe=a671b6ab07) | Oct 11, 2021 |
| HP            | 1496                        | [f6ad468908](https://linux-hardware.org/?probe=f6ad468908) | Oct 10, 2021 |
| MSI           | H110I PRO                   | [33e1bf9b6c](https://linux-hardware.org/?probe=33e1bf9b6c) | Oct 09, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [13ee121adc](https://linux-hardware.org/?probe=13ee121adc) | Oct 07, 2021 |
| MSI           | B150M MORTAR                | [fd3b108340](https://linux-hardware.org/?probe=fd3b108340) | Oct 07, 2021 |
| HP            | 1496                        | [3f369a5dd6](https://linux-hardware.org/?probe=3f369a5dd6) | Oct 06, 2021 |
| ASUSTek       | PRIME H310-PLUS R2.0        | [c627fc3c07](https://linux-hardware.org/?probe=c627fc3c07) | Oct 04, 2021 |
| MSI           | B150M MORTAR                | [224b713b5c](https://linux-hardware.org/?probe=224b713b5c) | Oct 03, 2021 |
| Gigabyte      | B250M-DS3H-CF               | [62558ba69c](https://linux-hardware.org/?probe=62558ba69c) | Sep 29, 2021 |
| ASRock        | X570 Phantom Gaming 4       | [68b6365968](https://linux-hardware.org/?probe=68b6365968) | Sep 28, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [1c1bca9399](https://linux-hardware.org/?probe=1c1bca9399) | Sep 28, 2021 |
| ASRock        | M3A790GXH/128M              | [818ec10ec8](https://linux-hardware.org/?probe=818ec10ec8) | Sep 24, 2021 |
| ASUSTek       | ROG STRIX X399-E GAMING     | [b04783b7e1](https://linux-hardware.org/?probe=b04783b7e1) | Sep 20, 2021 |
| Apple         | Mac-F4208DC8 PVT            | [ad193a0b9c](https://linux-hardware.org/?probe=ad193a0b9c) | Sep 16, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [d45a82c3c9](https://linux-hardware.org/?probe=d45a82c3c9) | Sep 06, 2021 |
| Foxconn       | 2ABF                        | [171462cc36](https://linux-hardware.org/?probe=171462cc36) | Aug 29, 2021 |
| MSI           | 970A SLI Krait Edition      | [862999e242](https://linux-hardware.org/?probe=862999e242) | Aug 27, 2021 |
| Gigabyte      | Z77-DS3H                    | [540c64bf79](https://linux-hardware.org/?probe=540c64bf79) | Aug 26, 2021 |
| Gigabyte      | F2A88XM-HD3P                | [dee9503ed0](https://linux-hardware.org/?probe=dee9503ed0) | Aug 24, 2021 |
| Pegatron      | 2A72h                       | [57575daae2](https://linux-hardware.org/?probe=57575daae2) | Aug 19, 2021 |
| Gigabyte      | GA-870A-UD3                 | [d436538e39](https://linux-hardware.org/?probe=d436538e39) | Aug 13, 2021 |
| Gigabyte      | X570 AORUS ULTRA            | [b937ce5e88](https://linux-hardware.org/?probe=b937ce5e88) | Aug 10, 2021 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [a2c47444e8](https://linux-hardware.org/?probe=a2c47444e8) | Aug 09, 2021 |
| ASUSTek       | M5A78L-M/USB3               | [b5f6eb1dc0](https://linux-hardware.org/?probe=b5f6eb1dc0) | Aug 09, 2021 |
| MSI           | 970A SLI Krait Edition      | [08cf0272da](https://linux-hardware.org/?probe=08cf0272da) | Aug 05, 2021 |
| Gigabyte      | P35C-DS3R                   | [e8ffe8991b](https://linux-hardware.org/?probe=e8ffe8991b) | Jul 27, 2021 |
| MSI           | H81M PRO-VD                 | [190d4540e9](https://linux-hardware.org/?probe=190d4540e9) | Jul 20, 2021 |
| Gigabyte      | GA-790XT-USB3               | [72f5d673d9](https://linux-hardware.org/?probe=72f5d673d9) | Jul 11, 2021 |
| ASRock        | X370 Gaming X               | [df5a9e402e](https://linux-hardware.org/?probe=df5a9e402e) | Jul 07, 2021 |
| Gigabyte      | P35-DS3                     | [1756b98ff7](https://linux-hardware.org/?probe=1756b98ff7) | Jul 04, 2021 |
| ASRock        | B450 Gaming K4              | [ed31fd442f](https://linux-hardware.org/?probe=ed31fd442f) | Jul 01, 2021 |
| ASRock        | B450 Gaming K4              | [479f6c752d](https://linux-hardware.org/?probe=479f6c752d) | Jul 01, 2021 |
| Gigabyte      | Z68XP-UD3P                  | [259e2a4ac0](https://linux-hardware.org/?probe=259e2a4ac0) | Jun 24, 2021 |
| HP            | 339A                        | [88af8ec05f](https://linux-hardware.org/?probe=88af8ec05f) | Jun 16, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [2989252679](https://linux-hardware.org/?probe=2989252679) | Jun 12, 2021 |
| MSI           | H97 GAMING 3                | [831ff65864](https://linux-hardware.org/?probe=831ff65864) | Jun 07, 2021 |
| Dell          | 0Y7WYT A00                  | [e7b9652dbd](https://linux-hardware.org/?probe=e7b9652dbd) | Jun 07, 2021 |
| MSI           | H97 GAMING 3                | [33dcfeee7b](https://linux-hardware.org/?probe=33dcfeee7b) | Jun 07, 2021 |
| HP            | 304Bh                       | [4f331fec6f](https://linux-hardware.org/?probe=4f331fec6f) | Jun 04, 2021 |
| HP            | 304Bh                       | [a41a097984](https://linux-hardware.org/?probe=a41a097984) | Jun 04, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [6018f18645](https://linux-hardware.org/?probe=6018f18645) | Jun 02, 2021 |
| Gigabyte      | GA-MA785GT-UD3H             | [03b8f35b44](https://linux-hardware.org/?probe=03b8f35b44) | Jun 02, 2021 |
| MSI           | B365M PRO-VH                | [9a3529c8ae](https://linux-hardware.org/?probe=9a3529c8ae) | May 29, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | [e5a1aba629](https://linux-hardware.org/?probe=e5a1aba629) | May 26, 2021 |
| ASUSTek       | PRIME H310M-R R2.0          | [dd9596a6b0](https://linux-hardware.org/?probe=dd9596a6b0) | May 25, 2021 |
| Gigabyte      | A320M-H-CF                  | [79e354be47](https://linux-hardware.org/?probe=79e354be47) | May 24, 2021 |
| ASUSTek       | A8V Deluxe                  | [e739f2f0ba](https://linux-hardware.org/?probe=e739f2f0ba) | May 24, 2021 |
| MSI           | B350M GAMING PRO            | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| ASRock        | Z370 Professional Gaming... | [2c915c81d9](https://linux-hardware.org/?probe=2c915c81d9) | May 18, 2021 |
| ASUSTek       | Z170-K                      | [8f3fc4eeda](https://linux-hardware.org/?probe=8f3fc4eeda) | May 15, 2021 |
| ASUSTek       | H170 PRO GAMING             | [b1375145c3](https://linux-hardware.org/?probe=b1375145c3) | May 10, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [46242d579f](https://linux-hardware.org/?probe=46242d579f) | May 09, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [0b6b9eab78](https://linux-hardware.org/?probe=0b6b9eab78) | May 07, 2021 |
| ASRock        | 880GM-LE FX                 | [256c66503a](https://linux-hardware.org/?probe=256c66503a) | May 06, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [70bb3aecd9](https://linux-hardware.org/?probe=70bb3aecd9) | May 05, 2021 |
| ASUSTek       | P5LD2-Deluxe                | [193ecc62cf](https://linux-hardware.org/?probe=193ecc62cf) | May 03, 2021 |
| QDI           | P4I865A                     | [a3df896b35](https://linux-hardware.org/?probe=a3df896b35) | May 03, 2021 |
| ASUSTek       | P5Q DELUXE                  | [34b91a88a8](https://linux-hardware.org/?probe=34b91a88a8) | Apr 28, 2021 |
| MSI           | MS-7235                     | [3d8c008ca3](https://linux-hardware.org/?probe=3d8c008ca3) | Apr 27, 2021 |
| HP            | 1494                        | [775b59a599](https://linux-hardware.org/?probe=775b59a599) | Apr 20, 2021 |
| MSI           | H81M PRO-VD                 | [4c7c9824db](https://linux-hardware.org/?probe=4c7c9824db) | Apr 19, 2021 |
| ASRock        | A320M-DVS R4.0              | [0a7e8b0fab](https://linux-hardware.org/?probe=0a7e8b0fab) | Apr 19, 2021 |
| MSI           | 970A SLI Krait Edition      | [8695142550](https://linux-hardware.org/?probe=8695142550) | Apr 13, 2021 |
| ASUSTek       | PRIME X370-PRO              | [fd3c6d01f7](https://linux-hardware.org/?probe=fd3c6d01f7) | Apr 11, 2021 |
| Gigabyte      | B550 VISION D               | [3246784665](https://linux-hardware.org/?probe=3246784665) | Apr 09, 2021 |
| Gigabyte      | P41T-D3                     | [2f9a494265](https://linux-hardware.org/?probe=2f9a494265) | Apr 09, 2021 |
| ASRock        | J3355B-ITX                  | [8f3bd77b70](https://linux-hardware.org/?probe=8f3bd77b70) | Apr 06, 2021 |
| ASUSTek       | P5Q DELUXE                  | [2d30481374](https://linux-hardware.org/?probe=2d30481374) | Apr 01, 2021 |
| ASUSTek       | M5A78L-M LX                 | [63df5a92c1](https://linux-hardware.org/?probe=63df5a92c1) | Apr 01, 2021 |
| ASUSTek       | M5A78L-M LX                 | [9312919fed](https://linux-hardware.org/?probe=9312919fed) | Apr 01, 2021 |
| Lenovo        | ThinkCentre M71e 3157H2U    | [6e0ad0f342](https://linux-hardware.org/?probe=6e0ad0f342) | Mar 31, 2021 |
| Gigabyte      | F2A88XM-HD3P                | [5bedab76df](https://linux-hardware.org/?probe=5bedab76df) | Mar 25, 2021 |
| Gigabyte      | B550 VISION D               | [5916c313e7](https://linux-hardware.org/?probe=5916c313e7) | Mar 25, 2021 |
| Gigabyte      | F2A88XM-HD3P                | [aab9ef0b36](https://linux-hardware.org/?probe=aab9ef0b36) | Mar 24, 2021 |
| HP            | 0984h                       | [20a29fe8b0](https://linux-hardware.org/?probe=20a29fe8b0) | Mar 20, 2021 |
| HP            | 18E4                        | [b5eec7a501](https://linux-hardware.org/?probe=b5eec7a501) | Mar 17, 2021 |
| ASRock        | Z97 Extreme4                | [6378d46f22](https://linux-hardware.org/?probe=6378d46f22) | Mar 17, 2021 |
| MSI           | Z97-G45 GAMING              | [5843e7b038](https://linux-hardware.org/?probe=5843e7b038) | Mar 14, 2021 |
| MSI           | Z97-G45 GAMING              | [fc76eddc08](https://linux-hardware.org/?probe=fc76eddc08) | Mar 14, 2021 |
| Gigabyte      | G31M-S2L                    | [9ff279ae01](https://linux-hardware.org/?probe=9ff279ae01) | Mar 11, 2021 |
| Gigabyte      | B75-D3V                     | [f4b8176eb4](https://linux-hardware.org/?probe=f4b8176eb4) | Mar 09, 2021 |
| Gigabyte      | G31M-S2L                    | [78933b8238](https://linux-hardware.org/?probe=78933b8238) | Mar 07, 2021 |
| MSI           | H81M PRO-VD                 | [efa82d3df7](https://linux-hardware.org/?probe=efa82d3df7) | Mar 02, 2021 |
| Gigabyte      | 8I915PL-G                   | [e9ed9c7fdf](https://linux-hardware.org/?probe=e9ed9c7fdf) | Feb 27, 2021 |
| Gigabyte      | G31M-S2L                    | [c0301ac11d](https://linux-hardware.org/?probe=c0301ac11d) | Feb 26, 2021 |
| ASUSTek       | P6T                         | [c2d58a2c68](https://linux-hardware.org/?probe=c2d58a2c68) | Feb 25, 2021 |
| MSI           | MS-7176                     | [f04765b1b9](https://linux-hardware.org/?probe=f04765b1b9) | Feb 24, 2021 |
| MSI           | MS-7176                     | [760a593d35](https://linux-hardware.org/?probe=760a593d35) | Feb 24, 2021 |
| ASUSTek       | Z170-A                      | [ec035af0d0](https://linux-hardware.org/?probe=ec035af0d0) | Feb 21, 2021 |
| Gigabyte      | G31M-S2L                    | [563f422327](https://linux-hardware.org/?probe=563f422327) | Feb 21, 2021 |
| Gigabyte      | Z97X-UD5H                   | [74869ab078](https://linux-hardware.org/?probe=74869ab078) | Feb 21, 2021 |
| Gigabyte      | G31M-S2L                    | [38e7b43029](https://linux-hardware.org/?probe=38e7b43029) | Feb 21, 2021 |
| Gigabyte      | G31M-S2L                    | [aac0643552](https://linux-hardware.org/?probe=aac0643552) | Feb 21, 2021 |
| Intel         | DP55WB AAE64798-204         | [6e9ac2a13d](https://linux-hardware.org/?probe=6e9ac2a13d) | Feb 20, 2021 |
| ASUSTek       | P8P67 LE                    | [492632cd6f](https://linux-hardware.org/?probe=492632cd6f) | Feb 19, 2021 |
| ASUSTek       | P8P67 LE                    | [2dae363129](https://linux-hardware.org/?probe=2dae363129) | Feb 19, 2021 |
| ABIT          | FP-IN9 SLI                  | [91f5f66c7c](https://linux-hardware.org/?probe=91f5f66c7c) | Feb 17, 2021 |
| Gigabyte      | GA-MA770T-UD3               | [209ecb3837](https://linux-hardware.org/?probe=209ecb3837) | Feb 16, 2021 |
| Gigabyte      | G31M-S2L                    | [6c898a20f1](https://linux-hardware.org/?probe=6c898a20f1) | Feb 15, 2021 |
| ASUSTek       | Rampage III GENE            | [3994b32fbb](https://linux-hardware.org/?probe=3994b32fbb) | Feb 14, 2021 |
| Gigabyte      | H61MA-D2V                   | [35291823d8](https://linux-hardware.org/?probe=35291823d8) | Feb 14, 2021 |
| Gigabyte      | Z370 HD3-CF                 | [de94ccbf1a](https://linux-hardware.org/?probe=de94ccbf1a) | Feb 14, 2021 |
| ASUSTek       | P8H77-V                     | [71b1c108c4](https://linux-hardware.org/?probe=71b1c108c4) | Feb 14, 2021 |
| ASRock        | B450 Gaming K4              | [2dd140ff3e](https://linux-hardware.org/?probe=2dd140ff3e) | Feb 14, 2021 |
| MSI           | B450 TOMAHAWK MAX           | [dfc223f07c](https://linux-hardware.org/?probe=dfc223f07c) | Feb 14, 2021 |
| MSI           | X470 GAMING PRO CARBON      | [e0ef54344d](https://linux-hardware.org/?probe=e0ef54344d) | Feb 14, 2021 |
| ASUSTek       | P5Q                         | [a9bc15b309](https://linux-hardware.org/?probe=a9bc15b309) | Feb 13, 2021 |
| ASUSTek       | P7P55D-E DELUXE             | [b0857a93ff](https://linux-hardware.org/?probe=b0857a93ff) | Feb 13, 2021 |
| Gigabyte      | GA-MA790XT-UD4P             | [0ebedefc78](https://linux-hardware.org/?probe=0ebedefc78) | Feb 13, 2021 |
| Gigabyte      | GA-MA770T-UD3               | [2ed0ae9569](https://linux-hardware.org/?probe=2ed0ae9569) | Feb 09, 2021 |
| Gigabyte      | H77M-D3H                    | [0a56b88fc8](https://linux-hardware.org/?probe=0a56b88fc8) | Feb 08, 2021 |
| Gigabyte      | B365M DS3H                  | [6b7db83192](https://linux-hardware.org/?probe=6b7db83192) | Feb 06, 2021 |
| Gigabyte      | B365M DS3H                  | [543b5a7398](https://linux-hardware.org/?probe=543b5a7398) | Feb 06, 2021 |
| ASUSTek       | Z97-A                       | [fc8c462cc7](https://linux-hardware.org/?probe=fc8c462cc7) | Feb 04, 2021 |
| Gigabyte      | GA-790XT-USB3               | [d14e71b6b4](https://linux-hardware.org/?probe=d14e71b6b4) | Feb 03, 2021 |
| HP            | 1494                        | [d3fbad0c50](https://linux-hardware.org/?probe=d3fbad0c50) | Feb 01, 2021 |
| Foxconn       | P43A01                      | [6ebcadfb23](https://linux-hardware.org/?probe=6ebcadfb23) | Jan 31, 2021 |
| ASUSTek       | Rampage III GENE            | [32605971fb](https://linux-hardware.org/?probe=32605971fb) | Jan 28, 2021 |
| ASUSTek       | Rampage III GENE            | [1ac6133a40](https://linux-hardware.org/?probe=1ac6133a40) | Jan 28, 2021 |
| Dell          | 06FW8P A01                  | [392c18a8d2](https://linux-hardware.org/?probe=392c18a8d2) | Jan 28, 2021 |
| Gigabyte      | G41M-Combo                  | [a85f6c4759](https://linux-hardware.org/?probe=a85f6c4759) | Jan 27, 2021 |
| Dell          | 0DFRFW A01                  | [7bcce8c99f](https://linux-hardware.org/?probe=7bcce8c99f) | Jan 22, 2021 |
| Gigabyte      | GA-890GPA-UD3H              | [ef38db344e](https://linux-hardware.org/?probe=ef38db344e) | Jan 20, 2021 |
| ASUSTek       | P8H61-M LX R2.0             | [0c61498134](https://linux-hardware.org/?probe=0c61498134) | Jan 19, 2021 |
| Lenovo        | ThinkCentre M55 880894G     | [3b766a7c24](https://linux-hardware.org/?probe=3b766a7c24) | Jan 17, 2021 |
| ASUSTek       | X99-DELUXE                  | [ca2c414b09](https://linux-hardware.org/?probe=ca2c414b09) | Jan 13, 2021 |
| HP            | 3648h                       | [21e48412d9](https://linux-hardware.org/?probe=21e48412d9) | Jan 12, 2021 |
| Gigabyte      | GA-790XT-USB3               | [637d6c6ea6](https://linux-hardware.org/?probe=637d6c6ea6) | Jan 11, 2021 |
| ASUSTek       | PRIME X570-P                | [9a71b52057](https://linux-hardware.org/?probe=9a71b52057) | Jan 11, 2021 |
| ASUSTek       | P5KPL-AM SE                 | [6164e26717](https://linux-hardware.org/?probe=6164e26717) | Jan 09, 2021 |
| ASUSTek       | PRIME X570-P                | [a2113ca536](https://linux-hardware.org/?probe=a2113ca536) | Jan 08, 2021 |
| ASRock        | A320M Pro4                  | [df605a19b9](https://linux-hardware.org/?probe=df605a19b9) | Jan 07, 2021 |
| ASRock        | 970M Pro3                   | [7e9042951e](https://linux-hardware.org/?probe=7e9042951e) | Jan 06, 2021 |
| ASUSTek       | P5G41C-M LX                 | [d6f76d5ca0](https://linux-hardware.org/?probe=d6f76d5ca0) | Jan 05, 2021 |
| ASRock        | J3455-ITX                   | [45519ff99d](https://linux-hardware.org/?probe=45519ff99d) | Jan 04, 2021 |
| ASUSTek       | H81M-K                      | [8708f0aa1a](https://linux-hardware.org/?probe=8708f0aa1a) | Jan 04, 2021 |
| ASUSTek       | P5E3 Deluxe                 | [6f3605f8a7](https://linux-hardware.org/?probe=6f3605f8a7) | Jan 04, 2021 |
| ASUSTek       | P5E3 Deluxe                 | [5939021d4c](https://linux-hardware.org/?probe=5939021d4c) | Jan 03, 2021 |
| ASRock        | J3455B-ITX                  | [188b19422f](https://linux-hardware.org/?probe=188b19422f) | Dec 28, 2020 |
| Dell          | 0WR7PY A03                  | [e9d1c14615](https://linux-hardware.org/?probe=e9d1c14615) | Dec 27, 2020 |
| ASRock        | J3455-ITX                   | [e530bd21e8](https://linux-hardware.org/?probe=e530bd21e8) | Dec 23, 2020 |
| Gigabyte      | Z490 AORUS ELITE AC         | [71036e26bf](https://linux-hardware.org/?probe=71036e26bf) | Dec 19, 2020 |
| Gigabyte      | Z490 AORUS ELITE AC         | [c58e872c12](https://linux-hardware.org/?probe=c58e872c12) | Dec 19, 2020 |
| ASRock        | B450 Gaming K4              | [6fcb38f3dc](https://linux-hardware.org/?probe=6fcb38f3dc) | Dec 15, 2020 |
| ASUSTek       | P8H61-M LX R2.0             | [de42fe0cb3](https://linux-hardware.org/?probe=de42fe0cb3) | Dec 14, 2020 |
| ECS           | GF7050VT-M5                 | [c29ca24015](https://linux-hardware.org/?probe=c29ca24015) | Dec 12, 2020 |
| ECS           | GF7050VT-M5                 | [657f63e3cb](https://linux-hardware.org/?probe=657f63e3cb) | Dec 12, 2020 |
| ASUSTek       | M4N78 PRO                   | [f25cf52f68](https://linux-hardware.org/?probe=f25cf52f68) | Dec 11, 2020 |
| Gigabyte      | G41M-Combo                  | [5866279b5d](https://linux-hardware.org/?probe=5866279b5d) | Dec 10, 2020 |
| Gigabyte      | 8IPE1000                    | [af54151e80](https://linux-hardware.org/?probe=af54151e80) | Dec 09, 2020 |
| HP            | 158B                        | [3a87a2e567](https://linux-hardware.org/?probe=3a87a2e567) | Dec 09, 2020 |
| ASUSTek       | P5G41T-M LX                 | [584da25316](https://linux-hardware.org/?probe=584da25316) | Dec 02, 2020 |
| ASUSTek       | P5G41T-M LX                 | [24658bc507](https://linux-hardware.org/?probe=24658bc507) | Dec 01, 2020 |
| Gigabyte      | F2A78M-DS2                  | [32f996990f](https://linux-hardware.org/?probe=32f996990f) | Dec 01, 2020 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [a56d5a585c](https://linux-hardware.org/?probe=a56d5a585c) | Nov 30, 2020 |
| Lenovo        | 36EE SDK0J40700 WIN 3258... | [2810240912](https://linux-hardware.org/?probe=2810240912) | Nov 30, 2020 |
| HP            | 1998                        | [33515aa889](https://linux-hardware.org/?probe=33515aa889) | Nov 29, 2020 |
| ASUSTek       | P5QL-ASUS-SE                | [e2e1a617e3](https://linux-hardware.org/?probe=e2e1a617e3) | Nov 29, 2020 |
| ASUSTek       | M2A74-AM SE                 | [c95d6e0e82](https://linux-hardware.org/?probe=c95d6e0e82) | Nov 24, 2020 |
| ASRock        | X470 Gaming-ITX/ac          | [75644ed3b7](https://linux-hardware.org/?probe=75644ed3b7) | Nov 23, 2020 |
| Foxconn       | G31MVP FAB:1.0              | [1dc63b8e97](https://linux-hardware.org/?probe=1dc63b8e97) | Nov 23, 2020 |
| ASUSTek       | M2A74-AM SE                 | [08ba3f8354](https://linux-hardware.org/?probe=08ba3f8354) | Nov 22, 2020 |
| Foxconn       | G31MVP FAB:1.0              | [a1d0d6fdb7](https://linux-hardware.org/?probe=a1d0d6fdb7) | Nov 22, 2020 |
| ASRock        | ConRoeXFire-eSATA2          | [4818c2eae0](https://linux-hardware.org/?probe=4818c2eae0) | Nov 22, 2020 |
| ASRock        | ConRoeXFire-eSATA2          | [b0cee03629](https://linux-hardware.org/?probe=b0cee03629) | Nov 22, 2020 |
| Gigabyte      | GA-78LMT-S2                 | [6f38a56098](https://linux-hardware.org/?probe=6f38a56098) | Nov 20, 2020 |
| ASUSTek       | PRIME X370-PRO              | [c893b56f4b](https://linux-hardware.org/?probe=c893b56f4b) | Nov 19, 2020 |
| Gigabyte      | B450M DS3H-CF               | [e191bfb512](https://linux-hardware.org/?probe=e191bfb512) | Nov 19, 2020 |
| ASUSTek       | H81M-K                      | [44bf08a027](https://linux-hardware.org/?probe=44bf08a027) | Nov 19, 2020 |
| HP            | 158B                        | [048fb23518](https://linux-hardware.org/?probe=048fb23518) | Nov 19, 2020 |
| Gigabyte      | 990FXA-UD3 R5               | [42a67a5d5e](https://linux-hardware.org/?probe=42a67a5d5e) | Nov 18, 2020 |
| Gigabyte      | P35-DS3L                    | [2385da6b14](https://linux-hardware.org/?probe=2385da6b14) | Nov 18, 2020 |
| ASRock        | B450 Gaming K4              | [f900377694](https://linux-hardware.org/?probe=f900377694) | Nov 18, 2020 |
| Gigabyte      | A320M-S2H-CF                | [4a734aa939](https://linux-hardware.org/?probe=4a734aa939) | Nov 17, 2020 |
| MSI           | B365M PRO-VH                | [9edabdaf62](https://linux-hardware.org/?probe=9edabdaf62) | Nov 15, 2020 |
| ASUSTek       | PRIME X370-A                | [a4aae311b7](https://linux-hardware.org/?probe=a4aae311b7) | Nov 09, 2020 |
| ASUSTek       | PRIME A320M-K               | [6ed5d0f8ea](https://linux-hardware.org/?probe=6ed5d0f8ea) | Nov 07, 2020 |
| HP            | 3397                        | [583e0c49c2](https://linux-hardware.org/?probe=583e0c49c2) | Nov 05, 2020 |
| ASUSTek       | K5130                       | [893f38d333](https://linux-hardware.org/?probe=893f38d333) | Nov 04, 2020 |
| Gigabyte      | AM1M-S2H                    | [b087bebc1e](https://linux-hardware.org/?probe=b087bebc1e) | Nov 03, 2020 |
| HP            | 1998                        | [053d3aaa45](https://linux-hardware.org/?probe=053d3aaa45) | Nov 02, 2020 |
| ASUSTek       | M4A87TD EVO                 | [a104997cae](https://linux-hardware.org/?probe=a104997cae) | Oct 30, 2020 |
| ASUSTek       | M2V-MX SE                   | [ced2dcbac9](https://linux-hardware.org/?probe=ced2dcbac9) | Oct 29, 2020 |
| ASUSTek       | M2V-MX SE                   | [f34d071ba0](https://linux-hardware.org/?probe=f34d071ba0) | Oct 29, 2020 |
| Lenovo        | ThinkCentre M58 6258WCY     | [a1896b3549](https://linux-hardware.org/?probe=a1896b3549) | Oct 26, 2020 |
| ASUSTek       | M4A87TD EVO                 | [08fdefffc8](https://linux-hardware.org/?probe=08fdefffc8) | Oct 24, 2020 |
| Dell          | 0V6XGW A00                  | [1518ff90f9](https://linux-hardware.org/?probe=1518ff90f9) | Oct 24, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [0f6b6ecd03](https://linux-hardware.org/?probe=0f6b6ecd03) | Oct 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [f6626ce773](https://linux-hardware.org/?probe=f6626ce773) | Oct 19, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [a921662ed8](https://linux-hardware.org/?probe=a921662ed8) | Oct 17, 2020 |
| ASUSTek       | ROG STRIX X570-F GAMING     | [456f1d4b3b](https://linux-hardware.org/?probe=456f1d4b3b) | Oct 16, 2020 |
| ASUSTek       | Rampage Formula             | [d015efaedd](https://linux-hardware.org/?probe=d015efaedd) | Oct 15, 2020 |
| MSI           | X470 GAMING PRO CARBON      | [5752a1dbb8](https://linux-hardware.org/?probe=5752a1dbb8) | Oct 14, 2020 |
| ASRock        | X370 Gaming X               | [1d2919768b](https://linux-hardware.org/?probe=1d2919768b) | Oct 13, 2020 |
| Gigabyte      | AX370-Gaming K7             | [65de3956e6](https://linux-hardware.org/?probe=65de3956e6) | Oct 12, 2020 |
| MSI           | B450M MORTAR MAX            | [03d4495b89](https://linux-hardware.org/?probe=03d4495b89) | Oct 10, 2020 |
| MSI           | B450M PRO-VDH MAX           | [1f401d3ab8](https://linux-hardware.org/?probe=1f401d3ab8) | Oct 04, 2020 |
| ASUSTek       | PRIME B450-PLUS             | [76406749f2](https://linux-hardware.org/?probe=76406749f2) | Oct 04, 2020 |
| ASUSTek       | Rampage Formula             | [aa6626f3b5](https://linux-hardware.org/?probe=aa6626f3b5) | Oct 04, 2020 |
| ASUSTek       | Crosshair IV Extreme        | [7a1cab9b57](https://linux-hardware.org/?probe=7a1cab9b57) | Oct 04, 2020 |
| MSI           | B450M PRO-VDH MAX           | [b88c0fed86](https://linux-hardware.org/?probe=b88c0fed86) | Oct 03, 2020 |
| Intel         | DH61HO AAG62445-102         | [df12d4ae9a](https://linux-hardware.org/?probe=df12d4ae9a) | Sep 30, 2020 |
| MSI           | H81M PRO-VD                 | [65d6038c79](https://linux-hardware.org/?probe=65d6038c79) | Sep 29, 2020 |
| MSI           | 970A SLI Krait Edition      | [000ee6620d](https://linux-hardware.org/?probe=000ee6620d) | Sep 26, 2020 |
| Intel         | DG31PR AAD97573-302         | [0362c81208](https://linux-hardware.org/?probe=0362c81208) | Sep 11, 2020 |
| MSI           | B150M MORTAR                | [3a6d780eff](https://linux-hardware.org/?probe=3a6d780eff) | Sep 11, 2020 |
| HP            | 1495                        | [02bb1f1448](https://linux-hardware.org/?probe=02bb1f1448) | Sep 11, 2020 |
| Lenovo        | ThinkCentre M58p 6209AP7    | [82306363c8](https://linux-hardware.org/?probe=82306363c8) | Sep 10, 2020 |
| Fujitsu Si... | 8P965UBH-RH-FS              | [8469018851](https://linux-hardware.org/?probe=8469018851) | Sep 09, 2020 |
| Fujitsu Si... | 8P965UBH-RH-FS              | [d3e1b20591](https://linux-hardware.org/?probe=d3e1b20591) | Sep 09, 2020 |
| Foxconn       | 2ABF                        | [dcdd010420](https://linux-hardware.org/?probe=dcdd010420) | Sep 08, 2020 |
| ASRock        | H81M-GL                     | [adca51da19](https://linux-hardware.org/?probe=adca51da19) | Sep 04, 2020 |
| Gigabyte      | 970A-DS3P                   | [ec5f49b3b8](https://linux-hardware.org/?probe=ec5f49b3b8) | Sep 03, 2020 |
| Gigabyte      | M68M-S2P                    | [acbf11a591](https://linux-hardware.org/?probe=acbf11a591) | Sep 02, 2020 |
| Gigabyte      | G31M-S2L                    | [ff5ef4f17a](https://linux-hardware.org/?probe=ff5ef4f17a) | Aug 31, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [9f0b4888f9](https://linux-hardware.org/?probe=9f0b4888f9) | Aug 22, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [23932dee06](https://linux-hardware.org/?probe=23932dee06) | Aug 08, 2020 |
| Apple         | Mac-F4208DC8 PVT            | [b2bb2e091d](https://linux-hardware.org/?probe=b2bb2e091d) | Aug 08, 2020 |
| Lenovo        | ThinkCentre M58p 7220W21    | [aa37671480](https://linux-hardware.org/?probe=aa37671480) | Aug 05, 2020 |
| Gigabyte      | GA-78LMT-S2                 | [ce7d3839c2](https://linux-hardware.org/?probe=ce7d3839c2) | Aug 04, 2020 |
| Gigabyte      | GA-MA78LM-S2                | [6b6a4fb2a4](https://linux-hardware.org/?probe=6b6a4fb2a4) | Jul 27, 2020 |
| ASRock        | B450M-HDV R4.0              | [ab12b8b821](https://linux-hardware.org/?probe=ab12b8b821) | Jul 21, 2020 |
| ASRock        | A300M-STX                   | [a026a886dc](https://linux-hardware.org/?probe=a026a886dc) | Jul 18, 2020 |
| ASRock        | A300M-STX                   | [41dd1d4d2f](https://linux-hardware.org/?probe=41dd1d4d2f) | Jul 18, 2020 |
| Gigabyte      | H67MA-USB3-B3               | [9807c6ea02](https://linux-hardware.org/?probe=9807c6ea02) | Jul 18, 2020 |
| HP            | 339A                        | [1c3706f5bb](https://linux-hardware.org/?probe=1c3706f5bb) | Jul 17, 2020 |
| ASUSTek       | X99-DELUXE                  | [6bcb4b0e88](https://linux-hardware.org/?probe=6bcb4b0e88) | Jul 13, 2020 |
| ASUSTek       | PRIME X370-PRO              | [bb4aee1ce5](https://linux-hardware.org/?probe=bb4aee1ce5) | Jul 09, 2020 |
| Dell          | 040DDP A01                  | [f45d9ec3af](https://linux-hardware.org/?probe=f45d9ec3af) | Jul 09, 2020 |
| ASRock        | B450M-HDV                   | [a74dc966e4](https://linux-hardware.org/?probe=a74dc966e4) | Jul 08, 2020 |
| Dell          | 0Y5FXV A00                  | [9e489ee5d4](https://linux-hardware.org/?probe=9e489ee5d4) | Jul 08, 2020 |
| MSI           | AM1I                        | [27e3770f9f](https://linux-hardware.org/?probe=27e3770f9f) | Jul 08, 2020 |
| ASUSTek       | PRIME X370-PRO              | [f0a928112b](https://linux-hardware.org/?probe=f0a928112b) | Jul 07, 2020 |
| ASUSTek       | PRIME X370-PRO              | [3fa02437d2](https://linux-hardware.org/?probe=3fa02437d2) | Jul 07, 2020 |
| Gigabyte      | Z68P-DS3                    | [0488222130](https://linux-hardware.org/?probe=0488222130) | Jul 05, 2020 |
| Gigabyte      | 990XA-UD3                   | [eadf2910c1](https://linux-hardware.org/?probe=eadf2910c1) | Jun 26, 2020 |
| Gigabyte      | B250M-DS3H-CF               | [ad9f19123a](https://linux-hardware.org/?probe=ad9f19123a) | Jun 24, 2020 |
| Gigabyte      | B360M D2V                   | [d5c81912f3](https://linux-hardware.org/?probe=d5c81912f3) | Jun 22, 2020 |
| ASUSTek       | P10S-I Series               | [9ef15f5d63](https://linux-hardware.org/?probe=9ef15f5d63) | Jun 21, 2020 |
| ASUSTek       | P10S-I Series               | [a732fadebf](https://linux-hardware.org/?probe=a732fadebf) | Jun 21, 2020 |
| HP            | 18E4                        | [de1ec6cf05](https://linux-hardware.org/?probe=de1ec6cf05) | Jun 18, 2020 |
| ASUSTek       | ROG Maximus X HERO          | [5eec140218](https://linux-hardware.org/?probe=5eec140218) | Jun 18, 2020 |
| Dell          | 0HD5W2 A00                  | [5c2c44732b](https://linux-hardware.org/?probe=5c2c44732b) | Jun 17, 2020 |
| Gigabyte      | 990XA-UD3                   | [750c6c3f47](https://linux-hardware.org/?probe=750c6c3f47) | Jun 15, 2020 |
| HP            | 1495                        | [b5eb32227c](https://linux-hardware.org/?probe=b5eb32227c) | Jun 14, 2020 |
| Gigabyte      | B75M-D3H                    | [a798cb0891](https://linux-hardware.org/?probe=a798cb0891) | Jun 12, 2020 |
| Intel         | DN2820FYK H24582-202        | [58e20d2f89](https://linux-hardware.org/?probe=58e20d2f89) | Jun 08, 2020 |
| ASRock        | B450M Pro4                  | [45a4b1598d](https://linux-hardware.org/?probe=45a4b1598d) | Jun 07, 2020 |
| ASUSTek       | PRIME X470-PRO              | [b43ad5a6b1](https://linux-hardware.org/?probe=b43ad5a6b1) | Jun 07, 2020 |
| Gigabyte      | Z170-HD3P-CF                | [a594975388](https://linux-hardware.org/?probe=a594975388) | Jun 06, 2020 |
| ASUSTek       | H97M-E                      | [62134f37df](https://linux-hardware.org/?probe=62134f37df) | Jun 06, 2020 |
| Gigabyte      | B450 AORUS M                | [cd81341297](https://linux-hardware.org/?probe=cd81341297) | Jun 03, 2020 |
| Gigabyte      | B450 AORUS M                | [71b460bd76](https://linux-hardware.org/?probe=71b460bd76) | Jun 02, 2020 |
| MSI           | B450M MORTAR MAX            | [99a79f4889](https://linux-hardware.org/?probe=99a79f4889) | May 30, 2020 |
| Dell          | 040DDP A01                  | [da5657c3c9](https://linux-hardware.org/?probe=da5657c3c9) | May 28, 2020 |
| MSI           | B450M MORTAR MAX            | [14e6ced790](https://linux-hardware.org/?probe=14e6ced790) | May 27, 2020 |
| Lenovo        | ThinkCentre M71e 3167A46    | [dc3403470e](https://linux-hardware.org/?probe=dc3403470e) | May 27, 2020 |
| Dell          | 0HD5W2 A00                  | [33cbff4154](https://linux-hardware.org/?probe=33cbff4154) | May 23, 2020 |
| Dell          | 0HD5W2 A00                  | [ed61c260f3](https://linux-hardware.org/?probe=ed61c260f3) | May 23, 2020 |
| HP            | 304Ah                       | [1634c5ba40](https://linux-hardware.org/?probe=1634c5ba40) | May 23, 2020 |
| ASRock        | H81M-GL                     | [40f0375a69](https://linux-hardware.org/?probe=40f0375a69) | May 23, 2020 |
| Gigabyte      | 8I865G775-G                 | [f7d448edb4](https://linux-hardware.org/?probe=f7d448edb4) | May 18, 2020 |
| HP            | 1998                        | [9ccf5438f1](https://linux-hardware.org/?probe=9ccf5438f1) | May 16, 2020 |
| HP            | 1998                        | [62c2c8d350](https://linux-hardware.org/?probe=62c2c8d350) | May 16, 2020 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [9f89d95532](https://linux-hardware.org/?probe=9f89d95532) | May 16, 2020 |
| Gigabyte      | GA-78LMT-USB3 x.x           | [d9884d1dfd](https://linux-hardware.org/?probe=d9884d1dfd) | May 14, 2020 |
| ASUSTek       | M3A78-T                     | [3d44016f99](https://linux-hardware.org/?probe=3d44016f99) | May 14, 2020 |
| ASUSTek       | H110M-D                     | [65825e0bec](https://linux-hardware.org/?probe=65825e0bec) | May 13, 2020 |
| Gigabyte      | G31M-ES2L                   | [86a0177aac](https://linux-hardware.org/?probe=86a0177aac) | May 11, 2020 |
| Gigabyte      | G31M-ES2L                   | [8bca8a21eb](https://linux-hardware.org/?probe=8bca8a21eb) | May 11, 2020 |
| ASRock        | B75M R2.0                   | [efd3354b61](https://linux-hardware.org/?probe=efd3354b61) | May 10, 2020 |
| Gigabyte      | Z170-HD3P-CF                | [3cef46e3b5](https://linux-hardware.org/?probe=3cef46e3b5) | May 10, 2020 |
| Gigabyte      | Z170-HD3P-CF                | [425ab8fa42](https://linux-hardware.org/?probe=425ab8fa42) | May 10, 2020 |
| Gigabyte      | Z170-HD3P-CF                | [326dfdd03c](https://linux-hardware.org/?probe=326dfdd03c) | May 09, 2020 |
| Gigabyte      | GA-970A-UD3                 | [567162aae3](https://linux-hardware.org/?probe=567162aae3) | May 09, 2020 |
| ASUSTek       | P5E-VM DO                   | [6b9367fb7d](https://linux-hardware.org/?probe=6b9367fb7d) | May 07, 2020 |
| Gigabyte      | A320M-S2H-CF                | [929c938534](https://linux-hardware.org/?probe=929c938534) | May 07, 2020 |
| ASUSTek       | P5G41T-M LX2/GB/LPT         | [419ece7416](https://linux-hardware.org/?probe=419ece7416) | May 06, 2020 |
| ASRock        | X370 Gaming X               | [061da7844f](https://linux-hardware.org/?probe=061da7844f) | May 05, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [097d9e6627](https://linux-hardware.org/?probe=097d9e6627) | May 03, 2020 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | [0b92e38d49](https://linux-hardware.org/?probe=0b92e38d49) | May 03, 2020 |
| ASUSTek       | M4A87TD EVO                 | [a260c9daa7](https://linux-hardware.org/?probe=a260c9daa7) | May 01, 2020 |
| ASUSTek       | M4A87TD EVO                 | [206baf206d](https://linux-hardware.org/?probe=206baf206d) | May 01, 2020 |
| Dell          | 0PC5F7 A01                  | [541846e7d7](https://linux-hardware.org/?probe=541846e7d7) | May 01, 2020 |
| ASUSTek       | A7N8X-X                     | [e975d79594](https://linux-hardware.org/?probe=e975d79594) | May 01, 2020 |
| ASUSTek       | A7N8X-X                     | [75dea3bce3](https://linux-hardware.org/?probe=75dea3bce3) | May 01, 2020 |
| ASRock        | M3A785GXH/128M              | [2c2e4ffd37](https://linux-hardware.org/?probe=2c2e4ffd37) | May 01, 2020 |
| Gigabyte      | GA-MA78LM-S2                | [81517bd66d](https://linux-hardware.org/?probe=81517bd66d) | May 01, 2020 |
| ASUSTek       | P5K SE/EPU                  | [ae1bdb128c](https://linux-hardware.org/?probe=ae1bdb128c) | Apr 30, 2020 |
| ASUSTek       | P5K SE/EPU                  | [c59ce96e89](https://linux-hardware.org/?probe=c59ce96e89) | Apr 30, 2020 |
| ASUSTek       | A8V-MX                      | [48bf426b83](https://linux-hardware.org/?probe=48bf426b83) | Apr 30, 2020 |
| Gigabyte      | GA-MA78LM-S2                | [b4516c2c86](https://linux-hardware.org/?probe=b4516c2c86) | Apr 28, 2020 |
| Gigabyte      | GA-MA78LM-S2                | [222a066411](https://linux-hardware.org/?probe=222a066411) | Apr 24, 2020 |
| ASRock        | G31M-S                      | [68a7deee55](https://linux-hardware.org/?probe=68a7deee55) | Apr 24, 2020 |
| Dell          | 0WF810                      | [1b9697ff31](https://linux-hardware.org/?probe=1b9697ff31) | Apr 23, 2020 |
| ASUSTek       | A8V-MX                      | [b881fd6abb](https://linux-hardware.org/?probe=b881fd6abb) | Apr 23, 2020 |
| Dell          | 0W2563                      | [d83c8ddedf](https://linux-hardware.org/?probe=d83c8ddedf) | Apr 22, 2020 |
| Dell          | 0W2563                      | [696b47564f](https://linux-hardware.org/?probe=696b47564f) | Apr 22, 2020 |
| Gigabyte      | G31M-S2L                    | [0b48cefe24](https://linux-hardware.org/?probe=0b48cefe24) | Apr 22, 2020 |
| ASUSTek       | M4A87TD EVO                 | [b039afa67d](https://linux-hardware.org/?probe=b039afa67d) | Apr 20, 2020 |
| ASUSTek       | M4A87TD EVO                 | [1696d2d9ce](https://linux-hardware.org/?probe=1696d2d9ce) | Apr 20, 2020 |
| Gigabyte      | B75M-D3H                    | [9b01bf2a08](https://linux-hardware.org/?probe=9b01bf2a08) | Apr 20, 2020 |
| Gigabyte      | B75M-D3H                    | [ee54fa2ed4](https://linux-hardware.org/?probe=ee54fa2ed4) | Apr 20, 2020 |
| ASRock        | B450M Pro4                  | [e08a09dd83](https://linux-hardware.org/?probe=e08a09dd83) | Apr 20, 2020 |
| ASUSTek       | M3N78-EM                    | [9c8c19f179](https://linux-hardware.org/?probe=9c8c19f179) | Apr 18, 2020 |
| ZOTAC         | AMD HUDSON-M1               | [e312729536](https://linux-hardware.org/?probe=e312729536) | Apr 17, 2020 |
| ZOTAC         | AMD HUDSON-M1               | [de7fd27b31](https://linux-hardware.org/?probe=de7fd27b31) | Apr 17, 2020 |
| ASUSTek       | M2A-VM                      | [88101e3d2f](https://linux-hardware.org/?probe=88101e3d2f) | Apr 16, 2020 |
| ASRock        | A320M-HDV R3.0              | [6095aae488](https://linux-hardware.org/?probe=6095aae488) | Apr 14, 2020 |
| ASRock        | A320M-HDV R3.0              | [41f0f05e33](https://linux-hardware.org/?probe=41f0f05e33) | Apr 13, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [eb57124022](https://linux-hardware.org/?probe=eb57124022) | Apr 13, 2020 |
| Dell          | 0HD5W2 A00                  | [63ce7e4135](https://linux-hardware.org/?probe=63ce7e4135) | Apr 12, 2020 |
| Dell          | 0F5C5X A00                  | [ee0a362506](https://linux-hardware.org/?probe=ee0a362506) | Apr 06, 2020 |
| Lenovo        | ThinkCentre M81 0385AW4     | [943d4d3c19](https://linux-hardware.org/?probe=943d4d3c19) | Apr 04, 2020 |
| Gigabyte      | 946GMX-S2                   | [9b4c3e822f](https://linux-hardware.org/?probe=9b4c3e822f) | Mar 29, 2020 |
| HP            | 3397                        | [f72e7a317a](https://linux-hardware.org/?probe=f72e7a317a) | Mar 28, 2020 |
| ASUSTek       | ROG STRIX B350-F GAMING     | [55f19a4f35](https://linux-hardware.org/?probe=55f19a4f35) | Mar 26, 2020 |
| ASUSTek       | P6T                         | [dbf0c0687f](https://linux-hardware.org/?probe=dbf0c0687f) | Mar 15, 2020 |
| ASUSTek       | P5G41T-M LX                 | [ef194ecc3b](https://linux-hardware.org/?probe=ef194ecc3b) | Mar 03, 2020 |
| ASUSTek       | P5G41T-M LX                 | [2e61fd9e0b](https://linux-hardware.org/?probe=2e61fd9e0b) | Mar 03, 2020 |
| IBM           | 819421G                     | [60a7f83f19](https://linux-hardware.org/?probe=60a7f83f19) | Mar 03, 2020 |
| HP            | 3397                        | [e342a631c6](https://linux-hardware.org/?probe=e342a631c6) | Mar 02, 2020 |
| Dell          | 0HD5W2 A00                  | [7a0b3876ca](https://linux-hardware.org/?probe=7a0b3876ca) | Feb 26, 2020 |
| Dell          | 0HD5W2 A00                  | [5e4dcd1b24](https://linux-hardware.org/?probe=5e4dcd1b24) | Feb 26, 2020 |
| ASRock        | H97 Pro4                    | [06a946b189](https://linux-hardware.org/?probe=06a946b189) | Feb 24, 2020 |
| Gigabyte      | H61M-S2PV                   | [f8b4191082](https://linux-hardware.org/?probe=f8b4191082) | Feb 23, 2020 |
| ASUSTek       | B85M-G                      | [542abc0408](https://linux-hardware.org/?probe=542abc0408) | Feb 18, 2020 |
| ASUSTek       | B85M-G                      | [612bf8e23e](https://linux-hardware.org/?probe=612bf8e23e) | Feb 17, 2020 |
| Gigabyte      | A320M-S2H-CF                | [3995d0575b](https://linux-hardware.org/?probe=3995d0575b) | Feb 13, 2020 |
| ASRock        | X370 Gaming X               | [05ae411d1f](https://linux-hardware.org/?probe=05ae411d1f) | Feb 10, 2020 |
| ASUSTek       | PRIME X470-PRO              | [da709d9bae](https://linux-hardware.org/?probe=da709d9bae) | Feb 09, 2020 |
| ASUSTek       | P5KPL-C/1600                | [3054120eee](https://linux-hardware.org/?probe=3054120eee) | Feb 06, 2020 |
| ASUSTek       | P5KPL-C/1600                | [733547325a](https://linux-hardware.org/?probe=733547325a) | Feb 06, 2020 |
| Gigabyte      | 965P-S3                     | [9a3a48c621](https://linux-hardware.org/?probe=9a3a48c621) | Feb 01, 2020 |
| ASUSTek       | P5QL-ASUS-SE                | [6fc14bf3ff](https://linux-hardware.org/?probe=6fc14bf3ff) | Jan 26, 2020 |
| ASUSTek       | PRIME X470-PRO              | [eec3f4a665](https://linux-hardware.org/?probe=eec3f4a665) | Jan 19, 2020 |
| AOpen         | i945GMm-HL 918EM10I4F0      | [8b319cd8a8](https://linux-hardware.org/?probe=8b319cd8a8) | Jan 18, 2020 |
| Gigabyte      | GA-78LMT-S2                 | [ae993b5ad5](https://linux-hardware.org/?probe=ae993b5ad5) | Jan 13, 2020 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | [56d01c2d20](https://linux-hardware.org/?probe=56d01c2d20) | Jan 12, 2020 |
| AMD           | 970A-UD3                    | [d1e093d616](https://linux-hardware.org/?probe=d1e093d616) | Jan 02, 2020 |
| MSI           | B150M BAZOOKA               | [3c0ca553e1](https://linux-hardware.org/?probe=3c0ca553e1) | Dec 30, 2019 |
| ASRock        | X370 Gaming X               | [035469bb6f](https://linux-hardware.org/?probe=035469bb6f) | Dec 29, 2019 |
| ASRock        | X370 Gaming X               | [5e8a739106](https://linux-hardware.org/?probe=5e8a739106) | Dec 26, 2019 |
| ASUSTek       | M2A-MX                      | [487090e1b2](https://linux-hardware.org/?probe=487090e1b2) | Dec 17, 2019 |
| MSI           | B150M BAZOOKA               | [3afe42946d](https://linux-hardware.org/?probe=3afe42946d) | Dec 12, 2019 |
| HP            | 158B                        | [7a65e2f97f](https://linux-hardware.org/?probe=7a65e2f97f) | Dec 11, 2019 |
| ASUSTek       | AT3N7A-I                    | [d4897620b7](https://linux-hardware.org/?probe=d4897620b7) | Nov 22, 2019 |
| ASUSTek       | AT3N7A-I                    | [68e4b5b760](https://linux-hardware.org/?probe=68e4b5b760) | Nov 22, 2019 |
| MSI           | B450 TOMAHAWK               | [5ac9ac64f7](https://linux-hardware.org/?probe=5ac9ac64f7) | Nov 05, 2019 |
| Gigabyte      | H57M-USB3                   | [6929a58c82](https://linux-hardware.org/?probe=6929a58c82) | Oct 26, 2019 |
| Gigabyte      | H57M-USB3                   | [2b6c5d66f8](https://linux-hardware.org/?probe=2b6c5d66f8) | Oct 26, 2019 |
| Gigabyte      | nVidia-nForce2              | [38f4bb47c3](https://linux-hardware.org/?probe=38f4bb47c3) | Oct 26, 2019 |
| ASUSTek       | M3A78 PRO                   | [b6fa3d93af](https://linux-hardware.org/?probe=b6fa3d93af) | Oct 24, 2019 |
| HP            | 3032h                       | [670f34074b](https://linux-hardware.org/?probe=670f34074b) | Oct 13, 2019 |
| HP            | 3032h                       | [61a5b05c99](https://linux-hardware.org/?probe=61a5b05c99) | Oct 06, 2019 |
| Fujitsu Si... | D2824-A1 S26361-D2824-A1    | [44c4d203a8](https://linux-hardware.org/?probe=44c4d203a8) | Oct 05, 2019 |
| Gigabyte      | GA-990FXA-UD3               | [7a646cb519](https://linux-hardware.org/?probe=7a646cb519) | Sep 20, 2019 |
| ASRock        | ConRoe1333-DVI/H            | [b7a267e0d3](https://linux-hardware.org/?probe=b7a267e0d3) | Sep 14, 2019 |
| ASUSTek       | P5N32-E SLI                 | [16ac788014](https://linux-hardware.org/?probe=16ac788014) | Sep 11, 2019 |
| ASRock        | H97M Pro4                   | [168644ddd0](https://linux-hardware.org/?probe=168644ddd0) | Sep 04, 2019 |
| ASUSTek       | M2A-VM                      | [fd2fe6e6aa](https://linux-hardware.org/?probe=fd2fe6e6aa) | Aug 31, 2019 |
| Gigabyte      | Z68P-DS3                    | [d266d501ce](https://linux-hardware.org/?probe=d266d501ce) | Aug 27, 2019 |
| MSI           | 760GMA-P34                  | [e1cae3d6ee](https://linux-hardware.org/?probe=e1cae3d6ee) | Aug 24, 2019 |
| Gigabyte      | Z68P-DS3                    | [bd54ee5e91](https://linux-hardware.org/?probe=bd54ee5e91) | Aug 20, 2019 |
| Gigabyte      | Z170-HD3P-CF                | [2b457352c9](https://linux-hardware.org/?probe=2b457352c9) | Aug 17, 2019 |
| Gigabyte      | Z97X-Gaming 5               | [5a16d7bc77](https://linux-hardware.org/?probe=5a16d7bc77) | Aug 14, 2019 |
| MSI           | MS-7309                     | [11d0376265](https://linux-hardware.org/?probe=11d0376265) | Jul 23, 2019 |
| Gigabyte      | Z68P-DS3                    | [cdabcf84b6](https://linux-hardware.org/?probe=cdabcf84b6) | Jul 23, 2019 |
| ASRock        | 4Core1600P35-WiFi           | [878d54b863](https://linux-hardware.org/?probe=878d54b863) | Jul 21, 2019 |
| ASRock        | 4Core1600P35-WiFi           | [d3d4f6ec9a](https://linux-hardware.org/?probe=d3d4f6ec9a) | Jul 21, 2019 |
| ASUSTek       | P6T                         | [42cc2f59e6](https://linux-hardware.org/?probe=42cc2f59e6) | Jul 17, 2019 |
| ASUSTek       | P6T                         | [6d2ab78f42](https://linux-hardware.org/?probe=6d2ab78f42) | Jul 16, 2019 |
| MSI           | H61M-P21                    | [cbe52d9e29](https://linux-hardware.org/?probe=cbe52d9e29) | Jul 02, 2019 |
| ASUSTek       | P8Z77-V LE PLUS             | [9ec349ffc5](https://linux-hardware.org/?probe=9ec349ffc5) | Jun 02, 2019 |
| Gigabyte      | H110M-S2PV-CF               | [7afdd3951c](https://linux-hardware.org/?probe=7afdd3951c) | Jun 01, 2019 |
| ASUSTek       | M3A78 PRO                   | [f2dffd30f5](https://linux-hardware.org/?probe=f2dffd30f5) | May 26, 2019 |
| ASUSTek       | STRIKER II NSE              | [13d6ead175](https://linux-hardware.org/?probe=13d6ead175) | May 22, 2019 |
| ASRock        | H97M Pro4                   | [410a594809](https://linux-hardware.org/?probe=410a594809) | May 21, 2019 |
| Gigabyte      | H61M-S2PV                   | [b823e3b7d6](https://linux-hardware.org/?probe=b823e3b7d6) | May 16, 2019 |
| HP            | 3032h                       | [68675fa918](https://linux-hardware.org/?probe=68675fa918) | May 16, 2019 |
| Unknown       | Unknown                     | [03322637f9](https://linux-hardware.org/?probe=03322637f9) | May 07, 2019 |
| Dell          | 0GXM1W A02                  | [1845f7e294](https://linux-hardware.org/?probe=1845f7e294) | May 05, 2019 |
| ASRock        | 970 Extreme4                | [6d8f048eff](https://linux-hardware.org/?probe=6d8f048eff) | Apr 29, 2019 |
| Pegatron      | Maureen                     | [ef835695b4](https://linux-hardware.org/?probe=ef835695b4) | Apr 25, 2019 |
| Dell          | 0F8096                      | [16ed8f93ee](https://linux-hardware.org/?probe=16ed8f93ee) | Apr 21, 2019 |
| Gigabyte      | GA-890GPA-UD3H              | [6881cfb846](https://linux-hardware.org/?probe=6881cfb846) | Apr 20, 2019 |
| Gigabyte      | H61M-S2PV                   | [6ef1bc0546](https://linux-hardware.org/?probe=6ef1bc0546) | Apr 19, 2019 |
| HP            | 3032h                       | [b9ec07b051](https://linux-hardware.org/?probe=b9ec07b051) | Apr 18, 2019 |
| Dell          | 0WMJ54 A01                  | [427e22d196](https://linux-hardware.org/?probe=427e22d196) | Apr 17, 2019 |
| Gigabyte      | G41M-ES2L                   | [20df40c66d](https://linux-hardware.org/?probe=20df40c66d) | Apr 11, 2019 |
| Intel         | DQ67EP AAG12529-308         | [93a39661ec](https://linux-hardware.org/?probe=93a39661ec) | Apr 10, 2019 |
| Gigabyte      | X48-DS5                     | [79a097bf6f](https://linux-hardware.org/?probe=79a097bf6f) | Apr 07, 2019 |
| Gigabyte      | H170-HD3-CF                 | [648c433823](https://linux-hardware.org/?probe=648c433823) | Apr 04, 2019 |
| ASUSTek       | M2N-SLI DELUXE              | [2a14e96053](https://linux-hardware.org/?probe=2a14e96053) | Mar 30, 2019 |
| ASUSTek       | M2N-SLI DELUXE              | [cba4a3e3be](https://linux-hardware.org/?probe=cba4a3e3be) | Mar 30, 2019 |
| ASUSTek       | P5QL-E                      | [d4c43a54e2](https://linux-hardware.org/?probe=d4c43a54e2) | Mar 29, 2019 |
| ASUSTek       | A88XM-A                     | [0f01674bb9](https://linux-hardware.org/?probe=0f01674bb9) | Mar 28, 2019 |
| ASUSTek       | P5QL-E                      | [feee6b6b4b](https://linux-hardware.org/?probe=feee6b6b4b) | Mar 26, 2019 |
| ASUSTek       | P5QL-E                      | [4fc067190a](https://linux-hardware.org/?probe=4fc067190a) | Mar 26, 2019 |
| Gigabyte      | B85M-D3H                    | [a660f1deba](https://linux-hardware.org/?probe=a660f1deba) | Mar 23, 2019 |
| Dell          | 0YXT71 A02                  | [bd2634142d](https://linux-hardware.org/?probe=bd2634142d) | Mar 21, 2019 |
| ASUSTek       | Rampage III GENE            | [a3dc9e143a](https://linux-hardware.org/?probe=a3dc9e143a) | Mar 17, 2019 |
| Intel         | D875PBZ AAC26680-303        | [399fe679ce](https://linux-hardware.org/?probe=399fe679ce) | Mar 16, 2019 |
| Gigabyte      | B75-D3V                     | [e8b0d211d6](https://linux-hardware.org/?probe=e8b0d211d6) | Mar 08, 2019 |
| Gigabyte      | G41M-ES2L                   | [f494cc6bb9](https://linux-hardware.org/?probe=f494cc6bb9) | Mar 03, 2019 |
| ASRock        | FM2A68M-HD+                 | [f1426dc86a](https://linux-hardware.org/?probe=f1426dc86a) | Feb 19, 2019 |
| Gigabyte      | Z97X-Gaming 5               | [bd5ed31e84](https://linux-hardware.org/?probe=bd5ed31e84) | Feb 10, 2019 |
| Gigabyte      | G33M-DS2R                   | [a60a6e48c0](https://linux-hardware.org/?probe=a60a6e48c0) | Feb 09, 2019 |
| MSI           | MS-7329                     | [0e8628d300](https://linux-hardware.org/?probe=0e8628d300) | Jan 15, 2019 |
| Gigabyte      | G33M-DS2R                   | [b559521683](https://linux-hardware.org/?probe=b559521683) | Jan 11, 2019 |
| ASRock        | G31M-GS                     | [bf12881f79](https://linux-hardware.org/?probe=bf12881f79) | Jan 07, 2019 |
| ASRock        | X470 Master SLI             | [061e4b9d1e](https://linux-hardware.org/?probe=061e4b9d1e) | Jan 01, 2019 |
| ASRock        | X470 Master SLI             | [3c27217608](https://linux-hardware.org/?probe=3c27217608) | Jan 01, 2019 |
| ASRock        | B450 Gaming K4              | [1a8e50aa1b](https://linux-hardware.org/?probe=1a8e50aa1b) | Dec 01, 2018 |
| ASRock        | B450 Gaming K4              | [8dc4fad051](https://linux-hardware.org/?probe=8dc4fad051) | Dec 01, 2018 |
| MSI           | B350 GAMING PRO CARBON      | [123db2c68f](https://linux-hardware.org/?probe=123db2c68f) | Nov 27, 2018 |
| ASRock        | H97M Pro4                   | [2e4984a12a](https://linux-hardware.org/?probe=2e4984a12a) | Nov 27, 2018 |
| Gigabyte      | Z370 HD3P-CF                | [6474c9c0b3](https://linux-hardware.org/?probe=6474c9c0b3) | Nov 13, 2018 |
| Gigabyte      | Z370 HD3P-CF                | [6995918cdc](https://linux-hardware.org/?probe=6995918cdc) | Nov 06, 2018 |
| Gigabyte      | 965P-DQ6                    | [781abca00d](https://linux-hardware.org/?probe=781abca00d) | Oct 29, 2018 |
| MSI           | B150M MORTAR                | [889ed60d6d](https://linux-hardware.org/?probe=889ed60d6d) | Oct 11, 2018 |
| ASUSTek       | H81M-K                      | [5bb8093b50](https://linux-hardware.org/?probe=5bb8093b50) | May 30, 2018 |
| ASUSTek       | M3A79-T DELUXE              | [409b3d680a](https://linux-hardware.org/?probe=409b3d680a) | Dec 15, 2017 |
| ASUSTek       | Rampage III GENE            | [e674cb2a2f](https://linux-hardware.org/?probe=e674cb2a2f) | Dec 07, 2017 |
| Intel         | DG965WH AAD41692-304        | [fcb3be90ef](https://linux-hardware.org/?probe=fcb3be90ef) | Apr 22, 2017 |
| ASUSTek       | Rampage III GENE            | [4863310b3c](https://linux-hardware.org/?probe=4863310b3c) | Mar 09, 2017 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Greece/Desktop/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| Ubuntu 20.04                 | 74       | 11.54%  |
| Ubuntu 18.04                 | 59       | 9.2%    |
| Ubuntu 22.04                 | 34       | 5.3%    |
| OpenMandriva 4.2             | 23       | 3.59%   |
| Ubuntu MATE 20.04            | 18       | 2.81%   |
| Arch Rolling                 | 16       | 2.5%    |
| Ubuntu MATE 18.04            | 14       | 2.18%   |
| Pop!_OS 22.04                | 14       | 2.18%   |
| Zorin 16                     | 13       | 2.03%   |
| Manjaro                      | 10       | 1.56%   |
| Linux Mint 21.1              | 10       | 1.56%   |
| Linux Mint 20.3              | 10       | 1.56%   |
| KDE neon 20.04               | 10       | 1.56%   |
| openSUSE Tumbleweed-XXXXXXXX | 9        | 1.4%    |
| Zorin 15                     | 8        | 1.25%   |
| Ubuntu 19.10                 | 8        | 1.25%   |
| OpenMandriva 4.3             | 8        | 1.25%   |
| Arch                         | 8        | 1.25%   |
| Ubuntu 19.04                 | 7        | 1.09%   |
| OpenMandriva 23.03           | 7        | 1.09%   |
| Kubuntu 20.04                | 7        | 1.09%   |
| Debian 12                    | 7        | 1.09%   |
| Debian 11                    | 7        | 1.09%   |
| ArcoLinux Rolling            | 7        | 1.09%   |
| Xubuntu 18.04                | 6        | 0.94%   |
| Ubuntu 22.10                 | 6        | 0.94%   |
| Ubuntu 21.10                 | 6        | 0.94%   |
| Pop!_OS 20.04                | 6        | 0.94%   |
| Linux Mint 19.3              | 6        | 0.94%   |
| Fedora 36                    | 6        | 0.94%   |
| Ubuntu 23.04                 | 5        | 0.78%   |
| Ubuntu 21.04                 | 5        | 0.78%   |
| OpenMandriva 23.08           | 5        | 0.78%   |
| Linux Mint 21.2              | 5        | 0.78%   |
| Ubuntu Unity 16.04           | 4        | 0.62%   |
| ROSA R10                     | 4        | 0.62%   |
| Pop!_OS 21.10                | 4        | 0.62%   |
| OpenMandriva 23.01           | 4        | 0.62%   |
| Linux Mint 21                | 4        | 0.62%   |
| Linux Mint 20.2              | 4        | 0.62%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Ubuntu           | 195      | 32.39%  |
| OpenMandriva     | 53       | 8.8%    |
| Linux Mint       | 46       | 7.64%   |
| Ubuntu MATE      | 33       | 5.48%   |
| Pop!_OS          | 27       | 4.49%   |
| Fedora           | 27       | 4.49%   |
| Zorin            | 24       | 3.99%   |
| Arch             | 24       | 3.99%   |
| Manjaro          | 23       | 3.82%   |
| Debian           | 19       | 3.16%   |
| KDE neon         | 14       | 2.33%   |
| Xubuntu          | 13       | 2.16%   |
| Kubuntu          | 13       | 2.16%   |
| ROSA             | 11       | 1.83%   |
| openSUSE         | 10       | 1.66%   |
| ArcoLinux        | 8        | 1.33%   |
| Ubuntu Unity     | 7        | 1.16%   |
| Gentoo           | 7        | 1.16%   |
| Lubuntu          | 5        | 0.83%   |
| Elementary       | 5        | 0.83%   |
| BlackPanther     | 4        | 0.66%   |
| Void Linux       | 3        | 0.5%    |
| LMDE             | 3        | 0.5%    |
| Endless          | 3        | 0.5%    |
| Artix            | 3        | 0.5%    |
| Xero             | 2        | 0.33%   |
| Reborn OS        | 2        | 0.33%   |
| Peppermint       | 2        | 0.33%   |
| org.kde.Platform | 2        | 0.33%   |
| Garuda Linux     | 2        | 0.33%   |
| ALT Linux        | 2        | 0.33%   |
| Ubuntu Budgie    | 1        | 0.17%   |
| Solus            | 1        | 0.17%   |
| PureOS           | 1        | 0.17%   |
| Nobara           | 1        | 0.17%   |
| MX               | 1        | 0.17%   |
| Mageia           | 1        | 0.17%   |
| EndeavourOS      | 1        | 0.17%   |
| CentOS           | 1        | 0.17%   |
| BigLinux         | 1        | 0.17%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                         | Desktops | Percent |
|---------------------------------|----------|---------|
| 5.10.14-desktop-1omv4002        | 23       | 3.19%   |
| 4.15.0-163-generic              | 14       | 1.94%   |
| 5.4.0-94-generic                | 12       | 1.67%   |
| 5.15.0-52-generic               | 11       | 1.53%   |
| 5.16.7-desktop-1omv4003         | 8        | 1.11%   |
| 6.2.6-desktop-1omv2390          | 7        | 0.97%   |
| 5.4.0-54-generic                | 7        | 0.97%   |
| 5.4.0-40-generic                | 7        | 0.97%   |
| 5.15.0-56-generic               | 7        | 0.97%   |
| 5.4.0-91-generic                | 6        | 0.83%   |
| 5.4.0-42-generic                | 6        | 0.83%   |
| 5.4.0-29-generic                | 6        | 0.83%   |
| 5.15.0-58-generic               | 6        | 0.83%   |
| 5.11.0-40-generic               | 6        | 0.83%   |
| 5.4.0-59-generic                | 5        | 0.69%   |
| 5.4.0-58-generic                | 5        | 0.69%   |
| 5.4.0-53-generic                | 5        | 0.69%   |
| 5.4.0-52-generic                | 5        | 0.69%   |
| 5.3.0-46-generic                | 5        | 0.69%   |
| 5.19.0-35-generic               | 5        | 0.69%   |
| 4.15.0-45-generic               | 5        | 0.69%   |
| 6.4.11-desktop-1omv2390         | 4        | 0.56%   |
| 6.1.1-desktop-1omv2290          | 4        | 0.56%   |
| 6.0.6-76060006-generic          | 4        | 0.56%   |
| 5.8.0-43-generic                | 4        | 0.56%   |
| 5.4.0-65-generic                | 4        | 0.56%   |
| 5.4.0-48-generic                | 4        | 0.56%   |
| 5.4.0-47-generic                | 4        | 0.56%   |
| 5.19.0-41-generic               | 4        | 0.56%   |
| 5.15.0-91-generic               | 4        | 0.56%   |
| 5.15.0-60-generic               | 4        | 0.56%   |
| 5.15.0-53-generic               | 4        | 0.56%   |
| 5.0.0-25-generic                | 4        | 0.56%   |
| 4.9.60-nrj-desktop-1rosa-x86_64 | 4        | 0.56%   |
| 4.18.16-desktop-1bP             | 4        | 0.56%   |
| 4.18.0-25-generic               | 4        | 0.56%   |
| 4.18.0-17-generic               | 4        | 0.56%   |
| 4.15.0-96-generic               | 4        | 0.56%   |
| 4.15.0-47-generic               | 4        | 0.56%   |
| 6.6.2-desktop-1omv2390          | 3        | 0.42%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4.0   | 114      | 16.94%  |
| 5.15.0  | 66       | 9.81%   |
| 4.15.0  | 61       | 9.06%   |
| 5.11.0  | 28       | 4.16%   |
| 5.3.0   | 26       | 3.86%   |
| 5.10.14 | 23       | 3.42%   |
| 5.8.0   | 22       | 3.27%   |
| 5.13.0  | 22       | 3.27%   |
| 5.19.0  | 21       | 3.12%   |
| 4.18.0  | 17       | 2.53%   |
| 5.0.0   | 15       | 2.23%   |
| 6.2.6   | 9        | 1.34%   |
| 6.2.0   | 9        | 1.34%   |
| 5.10.0  | 9        | 1.34%   |
| 5.16.7  | 8        | 1.19%   |
| 6.4.11  | 5        | 0.74%   |
| 6.1.0   | 5        | 0.74%   |
| 5.18.12 | 5        | 0.74%   |
| 6.6.0   | 4        | 0.59%   |
| 6.5.0   | 4        | 0.59%   |
| 6.1.1   | 4        | 0.59%   |
| 6.0.6   | 4        | 0.59%   |
| 4.9.60  | 4        | 0.59%   |
| 4.18.16 | 4        | 0.59%   |
| 6.6.2   | 3        | 0.45%   |
| 5.17.5  | 3        | 0.45%   |
| 5.17.4  | 3        | 0.45%   |
| 5.14.21 | 3        | 0.45%   |
| 5.14.14 | 3        | 0.45%   |
| 5.12.4  | 3        | 0.45%   |
| 4.19.0  | 3        | 0.45%   |
| 6.5.6   | 2        | 0.3%    |
| 6.5.5   | 2        | 0.3%    |
| 6.3.2   | 2        | 0.3%    |
| 6.1.3   | 2        | 0.3%    |
| 6.1.12  | 2        | 0.3%    |
| 6.0.8   | 2        | 0.3%    |
| 6.0.2   | 2        | 0.3%    |
| 6.0.12  | 2        | 0.3%    |
| 5.9.11  | 2        | 0.3%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Desktops | Percent |
|---------|----------|---------|
| 5.4     | 123      | 18.5%   |
| 5.15    | 84       | 12.63%  |
| 4.15    | 61       | 9.17%   |
| 5.10    | 48       | 7.22%   |
| 5.11    | 34       | 5.11%   |
| 5.8     | 28       | 4.21%   |
| 5.3     | 26       | 3.91%   |
| 5.19    | 25       | 3.76%   |
| 5.13    | 24       | 3.61%   |
| 6.2     | 22       | 3.31%   |
| 4.18    | 22       | 3.31%   |
| 5.0     | 18       | 2.71%   |
| 6.1     | 17       | 2.56%   |
| 6.0     | 15       | 2.26%   |
| 5.16    | 14       | 2.11%   |
| 6.5     | 13       | 1.95%   |
| 5.14    | 12       | 1.8%    |
| 6.4     | 11       | 1.65%   |
| 6.6     | 10       | 1.5%    |
| 5.17    | 10       | 1.5%    |
| 5.18    | 9        | 1.35%   |
| 5.9     | 6        | 0.9%    |
| 5.6     | 6        | 0.9%    |
| 5.7     | 5        | 0.75%   |
| 4.9     | 5        | 0.75%   |
| 5.12    | 4        | 0.6%    |
| 4.19    | 4        | 0.6%    |
| 6.3     | 3        | 0.45%   |
| 4.4     | 2        | 0.3%    |
| 6.7     | 1        | 0.15%   |
| 5.1     | 1        | 0.15%   |
| 4.14    | 1        | 0.15%   |
| 4.10    | 1        | 0.15%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| x86_64 | 565      | 96.75%  |
| i686   | 19       | 3.25%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Desktops | Percent |
|-----------------|----------|---------|
| GNOME           | 239      | 39.24%  |
| KDE5            | 114      | 18.72%  |
| Unknown         | 70       | 11.49%  |
| XFCE            | 50       | 8.21%   |
| X-Cinnamon      | 39       | 6.4%    |
| MATE            | 38       | 6.24%   |
| KDE             | 19       | 3.12%   |
| Unity           | 7        | 1.15%   |
| LXQt            | 6        | 0.99%   |
| KDE4            | 6        | 0.99%   |
| i3              | 5        | 0.82%   |
| Pantheon        | 4        | 0.66%   |
| Budgie          | 3        | 0.49%   |
| LXDE            | 2        | 0.33%   |
| Deepin          | 2        | 0.33%   |
| Cinnamon        | 2        | 0.33%   |
| Openbox         | 1        | 0.16%   |
| herbstluftwm    | 1        | 0.16%   |
| GNOME Flashback | 1        | 0.16%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| X11     | 472      | 78.8%   |
| Wayland | 73       | 12.19%  |
| Unknown | 42       | 7.01%   |
| Tty     | 12       | 2%      |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 300      | 49.26%  |
| SDDM    | 103      | 16.91%  |
| GDM3    | 77       | 12.64%  |
| LightDM | 73       | 11.99%  |
| GDM     | 38       | 6.24%   |
| TDM     | 8        | 1.31%   |
| KDM     | 6        | 0.99%   |
| LXDM    | 2        | 0.33%   |
| XDM     | 1        | 0.16%   |
| SLiM    | 1        | 0.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang       | Desktops | Percent |
|------------|----------|---------|
| en_US      | 328      | 54.67%  |
| el_GR      | 171      | 28.5%   |
| Unknown    | 67       | 11.17%  |
| en_GB      | 10       | 1.67%   |
| C          | 8        | 1.33%   |
| de_DE      | 5        | 0.83%   |
| ru_RU      | 4        | 0.67%   |
| el_GR@euro | 2        | 0.33%   |
| unm_US     | 1        | 0.17%   |
| POSIX      | 1        | 0.17%   |
| es_ES      | 1        | 0.17%   |
| en_IE      | 1        | 0.17%   |
| en_AU      | 1        | 0.17%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Desktops | Percent |
|------|----------|---------|
| BIOS | 387      | 64.29%  |
| EFI  | 215      | 35.71%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Ext4    | 427      | 70.46%  |
| Overlay | 79       | 13.04%  |
| Btrfs   | 48       | 7.92%   |
| Tmpfs   | 18       | 2.97%   |
| Unknown | 14       | 2.31%   |
| Xfs     | 10       | 1.65%   |
| Zfs     | 5        | 0.83%   |
| Ext3    | 2        | 0.33%   |
| Ext2    | 2        | 0.33%   |
| F2fs    | 1        | 0.17%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Desktops | Percent |
|---------|----------|---------|
| Unknown | 330      | 54.91%  |
| GPT     | 185      | 30.78%  |
| MBR     | 86       | 14.31%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 479      | 79.97%  |
| Yes       | 120      | 20.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Desktops | Percent |
|-----------|----------|---------|
| No        | 330      | 55.28%  |
| Yes       | 267      | 44.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Gigabyte Technology | 157      | 26.88%  |
| ASUSTek Computer    | 148      | 25.34%  |
| ASRock              | 62       | 10.62%  |
| MSI                 | 58       | 9.93%   |
| Dell                | 48       | 8.22%   |
| Hewlett-Packard     | 44       | 7.53%   |
| Lenovo              | 27       | 4.62%   |
| Intel               | 7        | 1.2%    |
| Foxconn             | 5        | 0.86%   |
| Fujitsu Siemens     | 3        | 0.51%   |
| ECS                 | 3        | 0.51%   |
| Unknown             | 3        | 0.51%   |
| Pegatron            | 2        | 0.34%   |
| AOpen               | 2        | 0.34%   |
| ZOTAC               | 1        | 0.17%   |
| VIA Technologies    | 1        | 0.17%   |
| QDI                 | 1        | 0.17%   |
| NU591               | 1        | 0.17%   |
| IBM                 | 1        | 0.17%   |
| HC Technology.      | 1        | 0.17%   |
| Gateway             | 1        | 0.17%   |
| Fujitsu             | 1        | 0.17%   |
| DFI                 | 1        | 0.17%   |
| AZW                 | 1        | 0.17%   |
| Apple               | 1        | 0.17%   |
| AMD                 | 1        | 0.17%   |
| Albatron            | 1        | 0.17%   |
| Acer                | 1        | 0.17%   |
| ABIT                | 1        | 0.17%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                         | Desktops | Percent |
|------------------------------|----------|---------|
| ASUS All Series              | 14       | 2.4%    |
| HP ProDesk 600 G1 SFF        | 7        | 1.2%    |
| ASRock B450 Gaming K4        | 6        | 1.03%   |
| MSI MS-7C02                  | 5        | 0.86%   |
| Dell OptiPlex GX520          | 5        | 0.86%   |
| Dell OptiPlex 7010           | 5        | 0.86%   |
| ASUS ROG STRIX B350-F GAMING | 5        | 0.86%   |
| HP Compaq Pro 6300 SFF       | 4        | 0.68%   |
| HP Compaq 8200 Elite SFF PC  | 4        | 0.68%   |
| Gigabyte H61M-S2PV           | 4        | 0.68%   |
| Gigabyte B550 AORUS ELITE V2 | 4        | 0.68%   |
| Gigabyte B450M DS3H          | 4        | 0.68%   |
| Gigabyte B450 AORUS M        | 4        | 0.68%   |
| Gigabyte A320M-S2H           | 4        | 0.68%   |
| Dell OptiPlex 790            | 4        | 0.68%   |
| MSI MS-7C56                  | 3        | 0.51%   |
| MSI MS-7A38                  | 3        | 0.51%   |
| Gigabyte Z170-HD3P           | 3        | 0.51%   |
| Gigabyte G41M-Combo          | 3        | 0.51%   |
| Gigabyte G31M-S2L            | 3        | 0.51%   |
| Gigabyte G31M-ES2L           | 3        | 0.51%   |
| Gigabyte B75M-D3H            | 3        | 0.51%   |
| Gigabyte B250M-DS3H          | 3        | 0.51%   |
| Dell OptiPlex GX620          | 3        | 0.51%   |
| Dell OptiPlex 745            | 3        | 0.51%   |
| Dell OptiPlex 7040           | 3        | 0.51%   |
| Dell OptiPlex 3020           | 3        | 0.51%   |
| ASUS Z170-A                  | 3        | 0.51%   |
| ASUS TUF Gaming X570-PLUS    | 3        | 0.51%   |
| ASUS PRIME X570-P            | 3        | 0.51%   |
| ASUS P6T                     | 3        | 0.51%   |
| ASUS H110M-D                 | 3        | 0.51%   |
| ASRock B450M Pro4            | 3        | 0.51%   |
| Unknown                      | 3        | 0.51%   |
| MSI MS-7C95                  | 2        | 0.34%   |
| MSI MS-7C81                  | 2        | 0.34%   |
| MSI MS-7C31                  | 2        | 0.34%   |
| MSI MS-7B78                  | 2        | 0.34%   |
| MSI MS-7996                  | 2        | 0.34%   |
| MSI MS-7972                  | 2        | 0.34%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                | Desktops | Percent |
|---------------------|----------|---------|
| Dell OptiPlex       | 34       | 5.82%   |
| ASUS PRIME          | 25       | 4.28%   |
| Lenovo ThinkCentre  | 24       | 4.11%   |
| HP Compaq           | 23       | 3.94%   |
| ASUS ROG            | 17       | 2.91%   |
| ASUS All            | 14       | 2.4%    |
| HP ProDesk          | 9        | 1.54%   |
| Dell Precision      | 8        | 1.37%   |
| Gigabyte B550       | 7        | 1.2%    |
| Gigabyte B450       | 6        | 1.03%   |
| ASRock B450         | 6        | 1.03%   |
| MSI MS-7C02         | 5        | 0.86%   |
| HP EliteDesk        | 5        | 0.86%   |
| ASUS TUF            | 5        | 0.86%   |
| Gigabyte Z370       | 4        | 0.68%   |
| Gigabyte H61M-S2PV  | 4        | 0.68%   |
| Gigabyte B450M      | 4        | 0.68%   |
| Gigabyte A320M-S2H  | 4        | 0.68%   |
| MSI MS-7C56         | 3        | 0.51%   |
| MSI MS-7A38         | 3        | 0.51%   |
| Gigabyte Z170-HD3P  | 3        | 0.51%   |
| Gigabyte X570       | 3        | 0.51%   |
| Gigabyte G41M-Combo | 3        | 0.51%   |
| Gigabyte G31M-S2L   | 3        | 0.51%   |
| Gigabyte G31M-ES2L  | 3        | 0.51%   |
| Gigabyte B75M-D3H   | 3        | 0.51%   |
| Gigabyte B250M-DS3H | 3        | 0.51%   |
| ASUS Z170-A         | 3        | 0.51%   |
| ASUS P6T            | 3        | 0.51%   |
| ASUS P5Q            | 3        | 0.51%   |
| ASUS P5K            | 3        | 0.51%   |
| ASUS P5G41T-M       | 3        | 0.51%   |
| ASUS M5A78L-M       | 3        | 0.51%   |
| ASUS H110M-D        | 3        | 0.51%   |
| ASRock B450M        | 3        | 0.51%   |
| ASRock A320M-HDV    | 3        | 0.51%   |
| Unknown             | 3        | 0.51%   |
| MSI MS-7C95         | 2        | 0.34%   |
| MSI MS-7C81         | 2        | 0.34%   |
| MSI MS-7C31         | 2        | 0.34%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Desktops | Percent |
|------|----------|---------|
| 2018 | 55       | 9.42%   |
| 2009 | 49       | 8.39%   |
| 2013 | 47       | 8.05%   |
| 2008 | 44       | 7.53%   |
| 2012 | 43       | 7.36%   |
| 2014 | 40       | 6.85%   |
| 2019 | 37       | 6.34%   |
| 2011 | 37       | 6.34%   |
| 2017 | 33       | 5.65%   |
| 2015 | 33       | 5.65%   |
| 2007 | 31       | 5.31%   |
| 2020 | 28       | 4.79%   |
| 2010 | 23       | 3.94%   |
| 2016 | 21       | 3.6%    |
| 2005 | 15       | 2.57%   |
| 2021 | 14       | 2.4%    |
| 2006 | 14       | 2.4%    |
| 2022 | 9        | 1.54%   |
| 2003 | 5        | 0.86%   |
| 2023 | 3        | 0.51%   |
| 2004 | 3        | 0.51%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name    | Desktops | Percent |
|---------|----------|---------|
| Desktop | 584      | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Desktops | Percent |
|----------|----------|---------|
| Disabled | 578      | 98.63%  |
| Enabled  | 8        | 1.37%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 584      | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Desktops | Percent |
|-------------|----------|---------|
| 16.01-24.0  | 129      | 21.5%   |
| 8.01-16.0   | 126      | 21%     |
| 3.01-4.0    | 124      | 20.67%  |
| 4.01-8.0    | 94       | 15.67%  |
| 32.01-64.0  | 53       | 8.83%   |
| 1.01-2.0    | 37       | 6.17%   |
| 2.01-3.0    | 17       | 2.83%   |
| 64.01-256.0 | 10       | 1.67%   |
| 24.01-32.0  | 8        | 1.33%   |
| 0.51-1.0    | 2        | 0.33%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Desktops | Percent |
|------------|----------|---------|
| 1.01-2.0   | 241      | 37.31%  |
| 2.01-3.0   | 138      | 21.36%  |
| 4.01-8.0   | 82       | 12.69%  |
| 3.01-4.0   | 73       | 11.3%   |
| 0.51-1.0   | 57       | 8.82%   |
| 8.01-16.0  | 34       | 5.26%   |
| 0.01-0.5   | 15       | 2.32%   |
| 16.01-24.0 | 5        | 0.77%   |
| 32.01-64.0 | 1        | 0.15%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Desktops | Percent |
|--------|----------|---------|
| 1      | 226      | 37.17%  |
| 2      | 174      | 28.62%  |
| 3      | 94       | 15.46%  |
| 4      | 57       | 9.38%   |
| 5      | 27       | 4.44%   |
| 6      | 15       | 2.47%   |
| 7      | 6        | 0.99%   |
| 0      | 4        | 0.66%   |
| 18     | 1        | 0.16%   |
| 14     | 1        | 0.16%   |
| 13     | 1        | 0.16%   |
| 12     | 1        | 0.16%   |
| 8      | 1        | 0.16%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 319      | 53.98%  |
| No        | 272      | 46.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| Yes       | 580      | 99.32%  |
| No        | 4        | 0.68%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 389      | 65.27%  |
| Yes       | 207      | 34.73%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Desktops | Percent |
|-----------|----------|---------|
| No        | 478      | 80.88%  |
| Yes       | 113      | 19.12%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Desktops | Percent |
|---------|----------|---------|
| Greece  | 584      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City         | Desktops | Percent |
|--------------|----------|---------|
| Athens       | 297      | 46.99%  |
| Thessaloniki | 94       | 14.87%  |
| Heraklion    | 17       | 2.69%   |
| Pátrai      | 16       | 2.53%   |
| Volos        | 10       | 1.58%   |
| Larissa      | 9        | 1.42%   |
| Ioannina     | 9        | 1.42%   |
| Piraeus      | 6        | 0.95%   |
| Lamia        | 6        | 0.95%   |
| Kavala       | 6        | 0.95%   |
| Kalamata     | 6        | 0.95%   |
| Kozani       | 5        | 0.79%   |
| Katerini     | 5        | 0.79%   |
| Karditsa     | 5        | 0.79%   |
| Chalcis      | 5        | 0.79%   |
| Veroia       | 4        | 0.63%   |
| Samos        | 4        | 0.63%   |
| Rhodes       | 4        | 0.63%   |
| Glyfada      | 4        | 0.63%   |
| Chania       | 4        | 0.63%   |
| Xanthi       | 3        | 0.47%   |
| Serres       | 3        | 0.47%   |
| Rethymno     | 3        | 0.47%   |
| Mytilene     | 3        | 0.47%   |
| Komotini     | 3        | 0.47%   |
| Kallithea    | 3        | 0.47%   |
| Chalandri    | 3        | 0.47%   |
| Arta         | 3        | 0.47%   |
| Aigaleo      | 3        | 0.47%   |
| Acharnes     | 3        | 0.47%   |
| Zakynthos    | 2        | 0.32%   |
| PГЎtrai    | 2        | 0.32%   |
| Old Faliron  | 2        | 0.32%   |
| Nea Peramos  | 2        | 0.32%   |
| Nafplion     | 2        | 0.32%   |
| Marousi      | 2        | 0.32%   |
| Magoula      | 2        | 0.32%   |
| Kifissia     | 2        | 0.32%   |
| Ithaki       | 2        | 0.32%   |
| Gerakas      | 2        | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Desktops | Drives | Percent |
|-----------------------------|----------|--------|---------|
| WDC                         | 253      | 457    | 22.96%  |
| Seagate                     | 175      | 291    | 15.88%  |
| Samsung Electronics         | 156      | 279    | 14.16%  |
| Toshiba                     | 73       | 107    | 6.62%   |
| Kingston                    | 72       | 92     | 6.53%   |
| Patriot                     | 54       | 73     | 4.9%    |
| Sandisk                     | 53       | 82     | 4.81%   |
| Crucial                     | 26       | 44     | 2.36%   |
| Hitachi                     | 25       | 29     | 2.27%   |
| Intenso                     | 24       | 31     | 2.18%   |
| Intel                       | 15       | 17     | 1.36%   |
| Maxtor                      | 14       | 16     | 1.27%   |
| A-DATA Technology           | 12       | 20     | 1.09%   |
| OCZ                         | 11       | 14     | 1%      |
| Team                        | 10       | 11     | 0.91%   |
| PNY                         | 10       | 10     | 0.91%   |
| HGST                        | 9        | 19     | 0.82%   |
| SPCC                        | 7        | 8      | 0.64%   |
| Phison Electronics          | 7        | 10     | 0.64%   |
| Phison                      | 6        | 9      | 0.54%   |
| Corsair                     | 6        | 6      | 0.54%   |
| China                       | 6        | 6      | 0.54%   |
| XPG                         | 5        | 7      | 0.45%   |
| Silicon Motion              | 5        | 5      | 0.45%   |
| Leven                       | 5        | 6      | 0.45%   |
| JMicron Technology          | 5        | 24     | 0.45%   |
| SK hynix                    | 4        | 5      | 0.36%   |
| Kingston Technology Company | 4        | 6      | 0.36%   |
| Unknown                     | 3        | 8      | 0.27%   |
| Micron/Crucial Technology   | 3        | 3      | 0.27%   |
| LITEONIT                    | 3        | 3      | 0.27%   |
| Gigabyte Technology         | 3        | 5      | 0.27%   |
| Emtec                       | 3        | 3      | 0.27%   |
| ADATA Technology            | 3        | 4      | 0.27%   |
| Verbatim                    | 2        | 3      | 0.18%   |
| Transcend                   | 2        | 2      | 0.18%   |
| Realtek Semiconductor       | 2        | 3      | 0.18%   |
| Platinet                    | 2        | 2      | 0.18%   |
| Mushkin                     | 2        | 2      | 0.18%   |
| Min Yi U                    | 2        | 4      | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                             | Desktops | Percent |
|---------------------------------------------------|----------|---------|
| Samsung SSD 860 EVO 250GB                         | 21       | 1.63%   |
| Seagate ST500DM002-1BD142 500GB                   | 18       | 1.4%    |
| Toshiba DT01ACA100 1TB                            | 17       | 1.32%   |
| Patriot Burst 240GB SSD                           | 17       | 1.32%   |
| Samsung SSD 860 EVO 500GB                         | 16       | 1.24%   |
| Samsung SSD 850 EVO 250GB                         | 16       | 1.24%   |
| Seagate ST1000DM010-2EP102 1TB                    | 15       | 1.17%   |
| Toshiba DT01ACA050 500GB                          | 13       | 1.01%   |
| Patriot Burst 120GB SSD                           | 13       | 1.01%   |
| WDC WD10EZEX-08WN4A0 1TB                          | 12       | 0.93%   |
| Kingston SA400S37120G 120GB SSD                   | 10       | 0.78%   |
| Samsung SSD 850 EVO 500GB                         | 9        | 0.7%    |
| Kingston SA400S37240G 240GB SSD                   | 9        | 0.7%    |
| WDC WDS240G2G0A-00JH30 240GB SSD                  | 8        | 0.62%   |
| Toshiba DT01ACA200 2TB                            | 8        | 0.62%   |
| Samsung NVMe SSD Drive 500GB                      | 8        | 0.62%   |
| Kingston SV300S37A120G 120GB SSD                  | 8        | 0.62%   |
| Seagate ST3500418AS 500GB                         | 7        | 0.54%   |
| Patriot Burst 480GB SSD                           | 7        | 0.54%   |
| WDC WD5000AAKX-08U6AA0 500GB                      | 6        | 0.47%   |
| Seagate ST3250410AS 250GB                         | 6        | 0.47%   |
| Samsung SSD 870 EVO 500GB                         | 6        | 0.47%   |
| Samsung SSD 850 EVO 120GB                         | 6        | 0.47%   |
| Samsung SSD 840 Series 120GB                      | 6        | 0.47%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB | 6        | 0.47%   |
| Kingston SA400S37480G 480GB SSD                   | 6        | 0.47%   |
| Crucial CT250MX500SSD1 250GB                      | 6        | 0.47%   |
| WDC WD5000AAKX-00ERMA0 500GB                      | 5        | 0.39%   |
| WDC WD10EZEX-00BN5A0 1TB                          | 5        | 0.39%   |
| Toshiba HDWD110 1TB                               | 5        | 0.39%   |
| Seagate ST3500630AS 500GB                         | 5        | 0.39%   |
| Seagate ST3500320AS 500GB                         | 5        | 0.39%   |
| Seagate ST3160815AS 160GB                         | 5        | 0.39%   |
| Seagate ST31000524AS 1TB                          | 5        | 0.39%   |
| SanDisk SDSSDA120G 120GB                          | 5        | 0.39%   |
| Samsung SSD 970 EVO Plus 500GB                    | 5        | 0.39%   |
| Samsung NVMe SSD Drive 1TB                        | 5        | 0.39%   |
| PNY CS900 120GB SSD                               | 5        | 0.39%   |
| Intel SSDSA2BW120G3H 120GB                        | 5        | 0.39%   |
| WDC WD5000AAKX-60U6AA0 500GB                      | 4        | 0.31%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 233      | 406    | 42.99%  |
| Seagate             | 174      | 289    | 32.1%   |
| Toshiba             | 61       | 83     | 11.25%  |
| Hitachi             | 25       | 29     | 4.61%   |
| Maxtor              | 14       | 16     | 2.58%   |
| Samsung Electronics | 13       | 19     | 2.4%    |
| HGST                | 9        | 19     | 1.66%   |
| JMicron Technology  | 4        | 20     | 0.74%   |
| Min Yi U            | 2        | 4      | 0.37%   |
| Intenso             | 2        | 2      | 0.37%   |
| Quantum             | 1        | 1      | 0.18%   |
| Inateck             | 1        | 1      | 0.18%   |
| Hewlett-Packard     | 1        | 1      | 0.18%   |
| Fujitsu             | 1        | 1      | 0.18%   |
| Apple               | 1        | 1      | 0.18%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| Samsung Electronics | 105      | 150    | 23.03%  |
| Kingston            | 58       | 75     | 12.72%  |
| Patriot             | 53       | 72     | 11.62%  |
| SanDisk             | 45       | 71     | 9.87%   |
| WDC                 | 29       | 47     | 6.36%   |
| Crucial             | 26       | 44     | 5.7%    |
| Intenso             | 19       | 26     | 4.17%   |
| Intel               | 14       | 16     | 3.07%   |
| Toshiba             | 11       | 21     | 2.41%   |
| A-DATA Technology   | 11       | 19     | 2.41%   |
| Team                | 10       | 11     | 2.19%   |
| PNY                 | 10       | 10     | 2.19%   |
| OCZ                 | 10       | 13     | 2.19%   |
| SPCC                | 7        | 8      | 1.54%   |
| China               | 6        | 6      | 1.32%   |
| Leven               | 5        | 6      | 1.1%    |
| Corsair             | 5        | 5      | 1.1%    |
| LITEONIT            | 3        | 3      | 0.66%   |
| Gigabyte Technology | 3        | 5      | 0.66%   |
| Emtec               | 3        | 3      | 0.66%   |
| Verbatim            | 2        | 3      | 0.44%   |
| Platinet            | 2        | 2      | 0.44%   |
| Mushkin             | 2        | 2      | 0.44%   |
| GOODRAM             | 2        | 3      | 0.44%   |
| Unknown             | 2        | 2      | 0.44%   |
| Unknown             | 1        | 4      | 0.22%   |
| Transcend           | 1        | 1      | 0.22%   |
| TEAM T25            | 1        | 1      | 0.22%   |
| SK hynix            | 1        | 1      | 0.22%   |
| Seagate             | 1        | 1      | 0.22%   |
| Plextor             | 1        | 1      | 0.22%   |
| Micron Technology   | 1        | 1      | 0.22%   |
| LITEON              | 1        | 1      | 0.22%   |
| Lite-On             | 1        | 2      | 0.22%   |
| InnoLite            | 1        | 1      | 0.22%   |
| Drevo               | 1        | 1      | 0.22%   |
| Apacer              | 1        | 1      | 0.22%   |
| AGI                 | 1        | 1      | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| HDD     | 419      | 892    | 46.09%  |
| SSD     | 364      | 640    | 40.04%  |
| NVMe    | 120      | 205    | 13.2%   |
| Unknown | 6        | 11     | 0.66%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Desktops | Drives | Percent |
|------|----------|--------|---------|
| SATA | 553      | 1485   | 78.77%  |
| NVMe | 120      | 205    | 17.09%  |
| SAS  | 29       | 58     | 4.13%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Desktops | Drives | Percent |
|------------|----------|--------|---------|
| 0.01-0.5   | 477      | 966    | 59.4%   |
| 0.51-1.0   | 198      | 348    | 24.66%  |
| 1.01-2.0   | 68       | 114    | 8.47%   |
| 3.01-4.0   | 24       | 37     | 2.99%   |
| 2.01-3.0   | 21       | 36     | 2.62%   |
| 4.01-10.0  | 13       | 28     | 1.62%   |
| 10.01-20.0 | 2        | 3      | 0.25%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Desktops | Percent |
|----------------|----------|---------|
| 101-250        | 155      | 24.68%  |
| 251-500        | 100      | 15.92%  |
| 1001-2000      | 71       | 11.31%  |
| 501-1000       | 70       | 11.15%  |
| More than 3000 | 51       | 8.12%   |
| 1-20           | 51       | 8.12%   |
| Unknown        | 42       | 6.69%   |
| 51-100         | 39       | 6.21%   |
| 2001-3000      | 28       | 4.46%   |
| 21-50          | 21       | 3.34%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Desktops | Percent |
|----------------|----------|---------|
| 1-20           | 210      | 32.31%  |
| 21-50          | 88       | 13.54%  |
| 51-100         | 67       | 10.31%  |
| 101-250        | 60       | 9.23%   |
| 251-500        | 59       | 9.08%   |
| 501-1000       | 53       | 8.15%   |
| Unknown        | 42       | 6.46%   |
| 1001-2000      | 36       | 5.54%   |
| More than 3000 | 24       | 3.69%   |
| 2001-3000      | 11       | 1.69%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Desktops | Drives | Percent |
|-------------------------------------|----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 2        | 3      | 2.5%    |
| Seagate ST3500320AS 500GB           | 2        | 2      | 2.5%    |
| Seagate ST3250318AS 250GB           | 2        | 2      | 2.5%    |
| WDC WD800JD-23LSA0 80GB             | 1        | 1      | 1.25%   |
| WDC WD800JB-00JJC0 80GB             | 1        | 2      | 1.25%   |
| WDC WD6400AAKS-65A7B0 640GB         | 1        | 1      | 1.25%   |
| WDC WD5000LPVT-00FMCT0 500GB        | 1        | 1      | 1.25%   |
| WDC WD5000AAVS-22G9B1 500GB         | 1        | 1      | 1.25%   |
| WDC WD5000AAKX-60U6AA0 500GB        | 1        | 1      | 1.25%   |
| WDC WD5000AAKX-603CA0 500GB         | 1        | 1      | 1.25%   |
| WDC WD5000AAKB-00H8A0 500GB         | 1        | 1      | 1.25%   |
| WDC WD40EFRX-68WT0N0 4TB            | 1        | 1      | 1.25%   |
| WDC WD40EFRX-68N32N0 4TB            | 1        | 1      | 1.25%   |
| WDC WD3200BPVT-22ZEST0 320GB        | 1        | 1      | 1.25%   |
| WDC WD3200BEVT-00A0RT0 320GB        | 1        | 1      | 1.25%   |
| WDC WD30EZRZ-00GXCB0 3TB            | 1        | 1      | 1.25%   |
| WDC WD2500YS-01SHB1 256GB           | 1        | 2      | 1.25%   |
| WDC WD2500AAKX-083CA1 250GB         | 1        | 1      | 1.25%   |
| WDC WD20PURX-64P6ZY0 2TB            | 1        | 1      | 1.25%   |
| WDC WD20EZRX-22D8PB0 2TB            | 1        | 1      | 1.25%   |
| WDC WD20EARS-00MVWB0 2TB            | 1        | 1      | 1.25%   |
| WDC WD2002FAEX-007BA0 2TB           | 1        | 2      | 1.25%   |
| WDC WD1600AAJS-22L7A0 160GB         | 1        | 1      | 1.25%   |
| WDC WD1200JD-00HBB0 120GB           | 1        | 2      | 1.25%   |
| WDC WD10JPVX-22JC3T0 1TB            | 1        | 1      | 1.25%   |
| WDC WD10EZEX-60WN4A1 1TB            | 1        | 3      | 1.25%   |
| WDC WD10EZEX-60WN4A0 1TB            | 1        | 1      | 1.25%   |
| WDC WD10EALX-009BA0 1TB             | 1        | 1      | 1.25%   |
| WDC WD10EADS-00M2B0 1TB             | 1        | 1      | 1.25%   |
| WDC WD1002FAEX-00Z3A0 1TB           | 1        | 1      | 1.25%   |
| WDC WD Green 2.5 240GB SSD          | 1        | 1      | 1.25%   |
| Toshiba MK5055GSX 500GB             | 1        | 1      | 1.25%   |
| Toshiba MK3263GSX 320GB             | 1        | 1      | 1.25%   |
| Toshiba MK1665GSX H 160GB           | 1        | 1      | 1.25%   |
| Toshiba DT01ACA100 1TB              | 1        | 2      | 1.25%   |
| Toshiba DT01ACA050 500GB            | 1        | 1      | 1.25%   |
| Seagate ST9100824AS 100GB           | 1        | 1      | 1.25%   |
| Seagate ST500LT012-1DG142 500GB     | 1        | 1      | 1.25%   |
| Seagate ST500LM021-1KJ152 500GB     | 1        | 1      | 1.25%   |
| Seagate ST500LM012 HN-M500MBB 500GB | 1        | 1      | 1.25%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 23       | 34     | 31.08%  |
| Seagate             | 20       | 22     | 27.03%  |
| Toshiba             | 5        | 6      | 6.76%   |
| Hitachi             | 4        | 4      | 5.41%   |
| Samsung Electronics | 3        | 3      | 4.05%   |
| Maxtor              | 3        | 3      | 4.05%   |
| Corsair             | 3        | 3      | 4.05%   |
| SanDisk             | 2        | 2      | 2.7%    |
| Patriot             | 2        | 2      | 2.7%    |
| Intel               | 2        | 2      | 2.7%    |
| HGST                | 2        | 8      | 2.7%    |
| Micron Technology   | 1        | 1      | 1.35%   |
| Kingston            | 1        | 1      | 1.35%   |
| Intenso             | 1        | 1      | 1.35%   |
| China               | 1        | 1      | 1.35%   |
| A-DATA Technology   | 1        | 1      | 1.35%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Desktops | Drives | Percent |
|---------------------|----------|--------|---------|
| WDC                 | 22       | 33     | 38.6%   |
| Seagate             | 20       | 22     | 35.09%  |
| Toshiba             | 5        | 6      | 8.77%   |
| Hitachi             | 4        | 4      | 7.02%   |
| Maxtor              | 3        | 3      | 5.26%   |
| HGST                | 2        | 8      | 3.51%   |
| Samsung Electronics | 1        | 1      | 1.75%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Desktops | Drives | Percent |
|------|----------|--------|---------|
| HDD  | 50       | 77     | 75.76%  |
| SSD  | 15       | 16     | 22.73%  |
| NVMe | 1        | 1      | 1.52%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                     | Desktops | Drives | Percent |
|---------------------------|----------|--------|---------|
| Seagate ST3500418AS 500GB | 1        | 1      | 50%     |
| Mushkin MKNSSDCR120GB-7   | 1        | 1      | 50%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor  | Desktops | Drives | Percent |
|---------|----------|--------|---------|
| Seagate | 1        | 1      | 50%     |
| Mushkin | 1        | 1      | 50%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Desktops | Drives | Percent |
|----------|----------|--------|---------|
| Detected | 386      | 1102   | 59.11%  |
| Works    | 203      | 550    | 31.09%  |
| Malfunc  | 62       | 94     | 9.49%   |
| Failed   | 2        | 2      | 0.31%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Intel                         | 369      | 45.39%  |
| AMD                           | 191      | 23.49%  |
| Samsung Electronics           | 57       | 7.01%   |
| JMicron Technology            | 41       | 5.04%   |
| Marvell Technology Group      | 23       | 2.83%   |
| Nvidia                        | 20       | 2.46%   |
| ASMedia Technology            | 19       | 2.34%   |
| Kingston Technology Company   | 18       | 2.21%   |
| Phison Electronics            | 14       | 1.72%   |
| SanDisk                       | 12       | 1.48%   |
| ADATA Technology              | 8        | 0.98%   |
| VIA Technologies              | 7        | 0.86%   |
| Silicon Motion                | 7        | 0.86%   |
| Silicon Image                 | 5        | 0.62%   |
| SK hynix                      | 3        | 0.37%   |
| Realtek Semiconductor         | 3        | 0.37%   |
| Micron/Crucial Technology     | 3        | 0.37%   |
| Broadcom / LSI                | 3        | 0.37%   |
| Toshiba America Info Systems  | 2        | 0.25%   |
| KIOXIA                        | 2        | 0.25%   |
| Seagate Technology            | 1        | 0.12%   |
| Promise Technology            | 1        | 0.12%   |
| OCZ Technology Group          | 1        | 0.12%   |
| LSI Logic / Symbios Logic     | 1        | 0.12%   |
| Integrated Technology Express | 1        | 0.12%   |
| INNOGRIT                      | 1        | 0.12%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Desktops | Percent |
|-----------------------------------------------------------------------------------------|----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 110      | 10.12%  |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 54       | 4.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 46       | 4.23%   |
| AMD 400 Series Chipset SATA Controller                                                  | 44       | 4.05%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 41       | 3.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 38       | 3.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 36       | 3.31%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller           | 29       | 2.67%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 28       | 2.58%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 28       | 2.58%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 26       | 2.39%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]            | 22       | 2.02%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 19       | 1.75%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 19       | 1.75%   |
| AMD 500 Series Chipset SATA Controller                                                  | 19       | 1.75%   |
| ASMedia ASM1061/ASM1062 Serial ATA Controller                                           | 18       | 1.66%   |
| Intel SATA Controller [RAID mode]                                                       | 15       | 1.38%   |
| AMD 300 Series Chipset SATA Controller                                                  | 15       | 1.38%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 14       | 1.29%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 12       | 1.1%    |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 12       | 1.1%    |
| Intel 4 Series Chipset PT IDER Controller                                               | 12       | 1.1%    |
| AMD FCH SATA Controller D                                                               | 12       | 1.1%    |
| JMicron JMB368 IDE controller                                                           | 11       | 1.01%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 11       | 1.01%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 11       | 1.01%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                              | 10       | 0.92%   |
| Intel 82801I (ICH9 Family) 2 port SATA Controller [IDE mode]                            | 10       | 0.92%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 9        | 0.83%   |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 9        | 0.83%   |
| Intel 82801JD/DO (ICH10 Family) SATA AHCI Controller                                    | 9        | 0.83%   |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 8        | 0.74%   |
| Intel 82801HR/HO/HH (ICH8R/DO/DH) 2 port SATA Controller [IDE mode]                     | 8        | 0.74%   |
| Intel 82801H (ICH8 Family) 4 port SATA Controller [IDE mode]                            | 8        | 0.74%   |
| ADATA XPG SX8200 Pro PCIe Gen3x4 M.2 2280 Solid State Drive                             | 8        | 0.74%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                       | 7        | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 7        | 0.64%   |
| Marvell Group 88SE6111/6121 SATA II / PATA Controller                                   | 7        | 0.64%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                                      | 7        | 0.64%   |
| Intel 82801IR/IO/IH (ICH9R/DO/DH) 4 port SATA Controller [IDE mode]                     | 7        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Desktops | Percent |
|------|----------|---------|
| SATA | 428      | 53.04%  |
| IDE  | 220      | 27.26%  |
| NVMe | 124      | 15.37%  |
| RAID | 30       | 3.72%   |
| SAS  | 4        | 0.5%    |
| SCSI | 1        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Desktops | Percent |
|--------|----------|---------|
| Intel  | 375      | 64.21%  |
| AMD    | 209      | 35.79%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Desktops | Percent |
|-----------------------------------------------|----------|---------|
| AMD Ryzen 5 2600 Six-Core Processor           | 12       | 2.04%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 11       | 1.87%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 10       | 1.7%    |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 9        | 1.53%   |
| AMD FX-6300 Six-Core Processor                | 9        | 1.53%   |
| Intel Pentium 4 CPU 3.00GHz                   | 8        | 1.36%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 8        | 1.36%   |
| Intel Core i3-3220 CPU @ 3.30GHz              | 8        | 1.36%   |
| Intel Pentium 4 CPU 3.20GHz                   | 7        | 1.19%   |
| Intel Core i5-4460 CPU @ 3.20GHz              | 7        | 1.19%   |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 7        | 1.19%   |
| AMD Ryzen 5 3600 6-Core Processor             | 7        | 1.19%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 6        | 1.02%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 6        | 1.02%   |
| Intel Core 2 Duo CPU E8500 @ 3.16GHz          | 6        | 1.02%   |
| Intel Celeron CPU G1840 @ 2.80GHz             | 6        | 1.02%   |
| AMD Ryzen 5 5600G with Radeon Graphics        | 6        | 1.02%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 6        | 1.02%   |
| AMD Phenom II X4 965 Processor                | 6        | 1.02%   |
| Intel Pentium Dual-Core CPU E5200 @ 2.50GHz   | 5        | 0.85%   |
| Intel Core i3-2120 CPU @ 3.30GHz              | 5        | 0.85%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 5        | 0.85%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 5        | 0.85%   |
| AMD Ryzen 9 5900X 12-Core Processor           | 5        | 0.85%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 5        | 0.85%   |
| AMD Ryzen 5 2600X Six-Core Processor          | 5        | 0.85%   |
| AMD Ryzen 5 2400G with Radeon Vega Graphics   | 5        | 0.85%   |
| AMD Athlon 64 X2 Dual Core Processor 4200+    | 5        | 0.85%   |
| AMD A8-7600 Radeon R7, 10 Compute Cores 4C+6G | 5        | 0.85%   |
| Intel Pentium D CPU 2.80GHz                   | 4        | 0.68%   |
| Intel Pentium CPU G3240 @ 3.10GHz             | 4        | 0.68%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 4        | 0.68%   |
| Intel Core i7 CPU 920 @ 2.67GHz               | 4        | 0.68%   |
| Intel Core i5-6600 CPU @ 3.30GHz              | 4        | 0.68%   |
| Intel Core i5-4690K CPU @ 3.50GHz             | 4        | 0.68%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 4        | 0.68%   |
| Intel Core i5-3570 CPU @ 3.40GHz              | 4        | 0.68%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 4        | 0.68%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 4        | 0.68%   |
| Intel Core i3-8100 CPU @ 3.60GHz              | 4        | 0.68%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Desktops | Percent |
|-------------------------|----------|---------|
| Intel Core i5           | 87       | 14.87%  |
| AMD Ryzen 5             | 63       | 10.77%  |
| Intel Core i7           | 50       | 8.55%   |
| Intel Core i3           | 50       | 8.55%   |
| Intel Core 2 Duo        | 33       | 5.64%   |
| AMD Ryzen 7             | 31       | 5.3%    |
| Intel Core 2 Quad       | 28       | 4.79%   |
| Intel Pentium           | 21       | 3.59%   |
| Intel Celeron           | 21       | 3.59%   |
| AMD FX                  | 21       | 3.59%   |
| Intel Pentium 4         | 20       | 3.42%   |
| Intel Xeon              | 17       | 2.91%   |
| AMD Ryzen 9             | 17       | 2.91%   |
| AMD Athlon 64 X2        | 15       | 2.56%   |
| Other                   | 12       | 2.05%   |
| Intel Pentium Dual-Core | 12       | 2.05%   |
| AMD Ryzen 3             | 11       | 1.88%   |
| AMD Phenom II X4        | 11       | 1.88%   |
| Intel Core 2            | 10       | 1.71%   |
| AMD A8                  | 7        | 1.2%    |
| Intel Pentium D         | 6        | 1.03%   |
| AMD Phenom II X6        | 4        | 0.68%   |
| AMD Phenom              | 4        | 0.68%   |
| AMD A10                 | 3        | 0.51%   |
| Intel Pentium Gold      | 2        | 0.34%   |
| Intel Pentium Dual      | 2        | 0.34%   |
| Intel Genuine           | 2        | 0.34%   |
| Intel Core i9           | 2        | 0.34%   |
| AMD Ryzen Threadripper  | 2        | 0.34%   |
| AMD Athlon XP           | 2        | 0.34%   |
| AMD Athlon II X4        | 2        | 0.34%   |
| AMD Athlon II X2        | 2        | 0.34%   |
| AMD Athlon 64           | 2        | 0.34%   |
| AMD Athlon              | 2        | 0.34%   |
| Intel Pentium Silver    | 1        | 0.17%   |
| Intel Atom              | 1        | 0.17%   |
| AMD Sempron             | 1        | 0.17%   |
| AMD Phenom II X2        | 1        | 0.17%   |
| AMD E                   | 1        | 0.17%   |
| AMD Dual Core Opteron   | 1        | 0.17%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 4      | 216      | 36.92%  |
| 2      | 184      | 31.45%  |
| 6      | 72       | 12.31%  |
| 8      | 43       | 7.35%   |
| 1      | 30       | 5.13%   |
| 12     | 15       | 2.56%   |
| 3      | 12       | 2.05%   |
| 16     | 10       | 1.71%   |
| 24     | 1        | 0.17%   |
| 14     | 1        | 0.17%   |
| 10     | 1        | 0.17%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 579      | 99.14%  |
| 2      | 5        | 0.86%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Desktops | Percent |
|--------|----------|---------|
| 1      | 297      | 50.86%  |
| 2      | 286      | 48.97%  |
| 4      | 1        | 0.17%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Desktops | Percent |
|----------------|----------|---------|
| 32-bit, 64-bit | 571      | 97.61%  |
| 32-bit         | 9        | 1.54%   |
| Unknown        | 5        | 0.85%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 157      | 25.86%  |
| 0x306c3    | 53       | 8.73%   |
| 0x306a9    | 28       | 4.61%   |
| 0x1067a    | 28       | 4.61%   |
| 0x206a7    | 26       | 4.28%   |
| 0x0800820d | 17       | 2.8%    |
| 0x506e3    | 15       | 2.47%   |
| 0x06000852 | 13       | 2.14%   |
| 0x906e9    | 12       | 1.98%   |
| 0x10676    | 11       | 1.81%   |
| 0x08701021 | 10       | 1.65%   |
| 0x906ed    | 9        | 1.48%   |
| 0xf43      | 8        | 1.32%   |
| 0x6f6      | 8        | 1.32%   |
| 0x06003106 | 8        | 1.32%   |
| 0xa0653    | 7        | 1.15%   |
| 0x906eb    | 7        | 1.15%   |
| 0x906ea    | 7        | 1.15%   |
| 0x6fd      | 7        | 1.15%   |
| 0x106e5    | 7        | 1.15%   |
| 0x10677    | 7        | 1.15%   |
| 0x08108109 | 7        | 1.15%   |
| 0x08101016 | 7        | 1.15%   |
| 0x010000c8 | 7        | 1.15%   |
| 0xf41      | 6        | 0.99%   |
| 0x6fb      | 6        | 0.99%   |
| 0x106a5    | 5        | 0.82%   |
| 0x08701013 | 5        | 0.82%   |
| 0x0810100b | 5        | 0.82%   |
| 0x0800820b | 5        | 0.82%   |
| 0x08001138 | 5        | 0.82%   |
| 0xf29      | 4        | 0.66%   |
| 0x0a50000d | 4        | 0.66%   |
| 0x0a20120a | 4        | 0.66%   |
| 0x0a201016 | 4        | 0.66%   |
| 0x08001129 | 4        | 0.66%   |
| 0xf47      | 3        | 0.49%   |
| 0x6f2      | 3        | 0.49%   |
| 0x506c9    | 3        | 0.49%   |
| 0x306f2    | 3        | 0.49%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Desktops | Percent |
|------------------|----------|---------|
| Haswell          | 63       | 10.73%  |
| Penryn           | 61       | 10.39%  |
| KabyLake         | 44       | 7.5%    |
| Zen+             | 42       | 7.16%   |
| IvyBridge        | 37       | 6.3%    |
| SandyBridge      | 35       | 5.96%   |
| Core             | 35       | 5.96%   |
| Zen 3            | 34       | 5.79%   |
| Zen              | 27       | 4.6%    |
| NetBurst         | 27       | 4.6%    |
| K10              | 26       | 4.43%   |
| Skylake          | 23       | 3.92%   |
| Piledriver       | 22       | 3.75%   |
| K8 Hammer        | 19       | 3.24%   |
| Zen 2            | 18       | 3.07%   |
| Nehalem          | 15       | 2.56%   |
| CometLake        | 12       | 2.04%   |
| Steamroller      | 10       | 1.7%    |
| Unknown          | 9        | 1.53%   |
| Alderlake Hybrid | 5        | 0.85%   |
| Westmere         | 4        | 0.68%   |
| Silvermont       | 3        | 0.51%   |
| K6               | 3        | 0.51%   |
| Jaguar           | 3        | 0.51%   |
| Goldmont         | 3        | 0.51%   |
| Goldmont plus    | 2        | 0.34%   |
| Gracemont        | 1        | 0.17%   |
| Excavator        | 1        | 0.17%   |
| Bulldozer        | 1        | 0.17%   |
| Bonnell          | 1        | 0.17%   |
| Bobcat           | 1        | 0.17%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                     | Desktops | Percent |
|----------------------------|----------|---------|
| Nvidia                     | 238      | 38.83%  |
| AMD                        | 203      | 33.12%  |
| Intel                      | 170      | 27.73%  |
| Matrox Electronics Systems | 1        | 0.16%   |
| Conexant Systems           | 1        | 0.16%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Desktops | Percent |
|-----------------------------------------------------------------------------|----------|---------|
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 30       | 4.71%   |
| Nvidia GK208B [GeForce GT 710]                                              | 25       | 3.92%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 22       | 3.45%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 21       | 3.3%    |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 16       | 2.51%   |
| Intel 4 Series Chipset Integrated Graphics Controller                       | 16       | 2.51%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 14       | 2.2%    |
| Nvidia GT218 [GeForce 210]                                                  | 13       | 2.04%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 12       | 1.88%   |
| Intel HD Graphics 530                                                       | 11       | 1.73%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 11       | 1.73%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                         | 10       | 1.57%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 10       | 1.57%   |
| Intel 82945G/GZ Integrated Graphics Controller                              | 10       | 1.57%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 10       | 1.57%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 9        | 1.41%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 8        | 1.26%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 7        | 1.1%    |
| Nvidia GK208B [GeForce GT 730]                                              | 7        | 1.1%    |
| Intel HD Graphics 630                                                       | 7        | 1.1%    |
| Intel 4th Generation Core Processor Family Integrated Graphics Controller   | 7        | 1.1%    |
| AMD Kaveri [Radeon R7 Graphics]                                             | 7        | 1.1%    |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                            | 7        | 1.1%    |
| AMD Turks PRO [Radeon HD 6570/7570/8550 / R5 230]                           | 6        | 0.94%   |
| AMD Oland PRO [Radeon R7 240/340 / Radeon 520]                              | 6        | 0.94%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 6        | 0.94%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                  | 6        | 0.94%   |
| AMD Curacao PRO [Radeon R7 370 / R9 270/370 OEM]                            | 6        | 0.94%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                          | 6        | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050]                                             | 5        | 0.78%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 5        | 0.78%   |
| Nvidia GM206 [GeForce GTX 960]                                              | 5        | 0.78%   |
| Nvidia GF119 [GeForce GT 610]                                               | 5        | 0.78%   |
| Nvidia GF108 [GeForce GT 730]                                               | 5        | 0.78%   |
| Nvidia G96C [GeForce 9400 GT]                                               | 5        | 0.78%   |
| Intel IvyBridge GT2 [HD Graphics 4000]                                      | 5        | 0.78%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 5        | 0.78%   |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                              | 5        | 0.78%   |
| Nvidia TU116 [GeForce GTX 1660 SUPER]                                       | 4        | 0.63%   |
| Nvidia G86 [GeForce 8500 GT]                                                | 4        | 0.63%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                           | Desktops | Percent |
|--------------------------------|----------|---------|
| 1 x Nvidia                     | 226      | 38.24%  |
| 1 x AMD                        | 184      | 31.13%  |
| 1 x Intel                      | 149      | 25.21%  |
| 2 x AMD                        | 11       | 1.86%   |
| Intel + Nvidia                 | 6        | 1.02%   |
| Intel + AMD                    | 4        | 0.68%   |
| AMD + Nvidia                   | 3        | 0.51%   |
| Other                          | 2        | 0.34%   |
| 2 x Nvidia                     | 2        | 0.34%   |
| 2 x Intel                      | 2        | 0.34%   |
| 2 x AMD + 1 x Conexant Systems | 1        | 0.17%   |
| 1 x Matrox                     | 1        | 0.17%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Desktops | Percent |
|-------------|----------|---------|
| Free        | 443      | 74.45%  |
| Proprietary | 132      | 22.18%  |
| Unknown     | 20       | 3.36%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Desktops | Percent |
|------------|----------|---------|
| Unknown    | 226      | 37.11%  |
| 1.01-2.0   | 116      | 19.05%  |
| 0.01-0.5   | 80       | 13.14%  |
| 0.51-1.0   | 69       | 11.33%  |
| 3.01-4.0   | 49       | 8.05%   |
| 7.01-8.0   | 36       | 5.91%   |
| 5.01-6.0   | 19       | 3.12%   |
| 8.01-16.0  | 8        | 1.31%   |
| 2.01-3.0   | 5        | 0.82%   |
| 16.01-24.0 | 1        | 0.16%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Desktops | Percent |
|----------------------|----------|---------|
| Goldstar             | 142      | 22.54%  |
| Samsung Electronics  | 118      | 18.73%  |
| Dell                 | 59       | 9.37%   |
| Philips              | 40       | 6.35%   |
| Hewlett-Packard      | 29       | 4.6%    |
| LG Electronics       | 26       | 4.13%   |
| ViewSonic            | 20       | 3.17%   |
| BenQ                 | 20       | 3.17%   |
| AOC                  | 20       | 3.17%   |
| Ancor Communications | 16       | 2.54%   |
| Eizo                 | 12       | 1.9%    |
| Sony                 | 11       | 1.75%   |
| NEC Computers        | 9        | 1.43%   |
| Iiyama               | 8        | 1.27%   |
| Acer                 | 8        | 1.27%   |
| Vestel Elektronik    | 7        | 1.11%   |
| Unknown              | 7        | 1.11%   |
| Mi                   | 6        | 0.95%   |
| Fujitsu Siemens      | 6        | 0.95%   |
| Belinea              | 6        | 0.95%   |
| ASUSTek Computer     | 6        | 0.95%   |
| Medion               | 4        | 0.63%   |
| JRY                  | 4        | 0.63%   |
| Lenovo               | 3        | 0.48%   |
| Unknown              | 3        | 0.48%   |
| Sharp                | 2        | 0.32%   |
| RTK                  | 2        | 0.32%   |
| NCS                  | 2        | 0.32%   |
| LLL                  | 2        | 0.32%   |
| IBM                  | 2        | 0.32%   |
| Hitachi              | 2        | 0.32%   |
| Gigabyte Technology  | 2        | 0.32%   |
| FUS                  | 2        | 0.32%   |
| DAO                  | 2        | 0.32%   |
| YM                   | 1        | 0.16%   |
| Toshiba              | 1        | 0.16%   |
| SKY                  | 1        | 0.16%   |
| SAC                  | 1        | 0.16%   |
| PER                  | 1        | 0.16%   |
| OUT                  | 1        | 0.16%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Vestel Elektronik 32FHD_LCD_TV VES3700 1920x1080 700x400mm 31.7-inch   | 7        | 1.06%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 7        | 1.06%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 6        | 0.91%   |
| ViewSonic VA703-4SERIES VSC6A1E 1280x1024 340x270mm 17.1-inch          | 5        | 0.76%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 5        | 0.76%   |
| Samsung Electronics T24E390 SAM0C20 1920x1080 521x293mm 23.5-inch      | 4        | 0.6%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch      | 4        | 0.6%    |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                    | 4        | 0.6%    |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 4        | 0.6%    |
| Goldstar MONITOR GSM59C6 1920x1080 509x286mm 23.0-inch                 | 4        | 0.6%    |
| Goldstar IPS FULLHD GSM5AB6 1920x1080 480x270mm 21.7-inch              | 4        | 0.6%    |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                 | 4        | 0.6%    |
| Ancor Communications ASUS VS247 ACI249A 1920x1080 521x293mm 23.5-inch  | 4        | 0.6%    |
| Samsung Electronics T23B350 SAM093B 1920x1080 510x287mm 23.0-inch      | 3        | 0.45%   |
| Samsung Electronics S22F350 SAM0D1A 1920x1080 477x268mm 21.5-inch      | 3        | 0.45%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 3        | 0.45%   |
| LG Electronics LCD Monitor LG FULL HD 1920x1080                        | 3        | 0.45%   |
| Goldstar W2234 GSM56B8 1680x1050 474x296mm 22.0-inch                   | 3        | 0.45%   |
| Goldstar M208WA GSM4E62 1680x1050 430x270mm 20.0-inch                  | 3        | 0.45%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch                 | 3        | 0.45%   |
| Goldstar 20M35 GSM4EED 1600x900 433x236mm 19.4-inch                    | 3        | 0.45%   |
| Dell S2715H DEL40BB 1920x1080 598x336mm 27.0-inch                      | 3        | 0.45%   |
| BenQ GW2480 BNQ78E7 1920x1080 527x296mm 23.8-inch                      | 3        | 0.45%   |
| Unknown                                                                | 3        | 0.45%   |
| Sony TV SNYEE01 1920x1080                                              | 2        | 0.3%    |
| Samsung Electronics SyncMaster SAM05C7 1920x1080 521x293mm 23.5-inch   | 2        | 0.3%    |
| Samsung Electronics SyncMaster SAM0522 1600x900 443x249mm 20.0-inch    | 2        | 0.3%    |
| Samsung Electronics SyncMaster SAM03C2 1680x1050 459x296mm 21.5-inch   | 2        | 0.3%    |
| Samsung Electronics SyncMaster SAM0218 1280x1024 376x301mm 19.0-inch   | 2        | 0.3%    |
| Samsung Electronics SyncMaster SAM0193 1280x1024 376x301mm 19.0-inch   | 2        | 0.3%    |
| Samsung Electronics S27F350 SAM0D22 1920x1080 598x336mm 27.0-inch      | 2        | 0.3%    |
| Samsung Electronics S27E390 SAM0C1C 1920x1080 598x336mm 27.0-inch      | 2        | 0.3%    |
| Samsung Electronics S24E650 SAM0CB8 1920x1080 521x293mm 23.5-inch      | 2        | 0.3%    |
| Samsung Electronics S24A31x SAM7114 1920x1080 527x296mm 23.8-inch      | 2        | 0.3%    |
| Samsung Electronics LCD Monitor SAM0C39 1920x1080 885x498mm 40.0-inch  | 2        | 0.3%    |
| Samsung Electronics LCD Monitor SAM0C26 1920x1080 1209x680mm 54.6-inch | 2        | 0.3%    |
| Samsung Electronics LCD Monitor SAM0B30 1920x1080 885x498mm 40.0-inch  | 2        | 0.3%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2        | 0.3%    |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch                | 2        | 0.3%    |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch                | 2        | 0.3%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Desktops | Percent |
|--------------------|----------|---------|
| 1920x1080 (FHD)    | 277      | 45.94%  |
| 1280x1024 (SXGA)   | 76       | 12.6%   |
| 1680x1050 (WSXGA+) | 43       | 7.13%   |
| 3840x2160 (4K)     | 42       | 6.97%   |
| 2560x1440 (QHD)    | 31       | 5.14%   |
| 1440x900 (WXGA+)   | 19       | 3.15%   |
| 1366x768 (WXGA)    | 18       | 2.99%   |
| 1920x1200 (WUXGA)  | 16       | 2.65%   |
| 1600x900 (HD+)     | 14       | 2.32%   |
| Unknown            | 11       | 1.82%   |
| 1360x768           | 10       | 1.66%   |
| 2560x1080          | 9        | 1.49%   |
| 3840x1080          | 6        | 1%      |
| 3440x1440          | 6        | 1%      |
| 1024x768 (XGA)     | 6        | 1%      |
| 1600x1200          | 5        | 0.83%   |
| 2048x1152          | 2        | 0.33%   |
| 1920x540           | 2        | 0.33%   |
| 5120x1440          | 1        | 0.17%   |
| 4864x2160          | 1        | 0.17%   |
| 4480x1080          | 1        | 0.17%   |
| 3600x1080          | 1        | 0.17%   |
| 3200x1080          | 1        | 0.17%   |
| 3000x1920          | 1        | 0.17%   |
| 2960x1050          | 1        | 0.17%   |
| 2560x1600          | 1        | 0.17%   |
| 2288x1287          | 1        | 0.17%   |
| 1280x768           | 1        | 0.17%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Desktops | Percent |
|---------|----------|---------|
| 23      | 91       | 14.47%  |
| 21      | 78       | 12.4%   |
| 27      | 68       | 10.81%  |
| Unknown | 67       | 10.65%  |
| 24      | 62       | 9.86%   |
| 19      | 53       | 8.43%   |
| 17      | 36       | 5.72%   |
| 20      | 25       | 3.97%   |
| 18      | 25       | 3.97%   |
| 31      | 24       | 3.82%   |
| 22      | 20       | 3.18%   |
| 34      | 15       | 2.38%   |
| 84      | 9        | 1.43%   |
| 15      | 7        | 1.11%   |
| 72      | 6        | 0.95%   |
| 40      | 5        | 0.79%   |
| 54      | 4        | 0.64%   |
| 32      | 4        | 0.64%   |
| 60      | 3        | 0.48%   |
| 42      | 3        | 0.48%   |
| 33      | 3        | 0.48%   |
| 25      | 3        | 0.48%   |
| 28      | 2        | 0.32%   |
| 16      | 2        | 0.32%   |
| 12      | 2        | 0.32%   |
| 142     | 1        | 0.16%   |
| 65      | 1        | 0.16%   |
| 55      | 1        | 0.16%   |
| 49      | 1        | 0.16%   |
| 48      | 1        | 0.16%   |
| 46      | 1        | 0.16%   |
| 44      | 1        | 0.16%   |
| 39      | 1        | 0.16%   |
| 36      | 1        | 0.16%   |
| 29      | 1        | 0.16%   |
| 26      | 1        | 0.16%   |
| 14      | 1        | 0.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Desktops | Percent |
|----------------|----------|---------|
| 501-600        | 199      | 32.62%  |
| 401-500        | 169      | 27.7%   |
| Unknown        | 67       | 10.98%  |
| 301-350        | 44       | 7.21%   |
| 351-400        | 37       | 6.07%   |
| 601-700        | 30       | 4.92%   |
| 701-800        | 23       | 3.77%   |
| 1501-2000      | 15       | 2.46%   |
| 1001-1500      | 12       | 1.97%   |
| 801-900        | 6        | 0.98%   |
| 901-1000       | 4        | 0.66%   |
| 201-300        | 3        | 0.49%   |
| More than 2000 | 1        | 0.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Desktops | Percent |
|---------|----------|---------|
| 16/9    | 337      | 58.2%   |
| 16/10   | 72       | 12.44%  |
| 5/4     | 63       | 10.88%  |
| Unknown | 60       | 10.36%  |
| 4/3     | 16       | 2.76%   |
| 21/9    | 14       | 2.42%   |
| 6/5     | 9        | 1.55%   |
| 3/2     | 5        | 0.86%   |
| 32/9    | 2        | 0.35%   |
| 1.00    | 1        | 0.17%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Desktops | Percent |
|----------------|----------|---------|
| 201-250        | 207      | 33.71%  |
| 151-200        | 90       | 14.66%  |
| 301-350        | 69       | 11.24%  |
| Unknown        | 67       | 10.91%  |
| 141-150        | 55       | 8.96%   |
| 351-500        | 47       | 7.65%   |
| 251-300        | 28       | 4.56%   |
| More than 1000 | 25       | 4.07%   |
| 501-1000       | 14       | 2.28%   |
| 101-110        | 8        | 1.3%    |
| 71-80          | 2        | 0.33%   |
| 131-140        | 1        | 0.16%   |
| 111-120        | 1        | 0.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Desktops | Percent |
|---------|----------|---------|
| 51-100  | 363      | 62.69%  |
| 101-120 | 99       | 17.1%   |
| Unknown | 67       | 11.57%  |
| 1-50    | 25       | 4.32%   |
| 121-160 | 18       | 3.11%   |
| 161-240 | 7        | 1.21%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 475      | 79.7%   |
| 2     | 83       | 13.93%  |
| 0     | 27       | 4.53%   |
| 3     | 10       | 1.68%   |
| 4     | 1        | 0.17%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 353      | 45.14%  |
| Intel                                 | 196      | 25.06%  |
| Qualcomm Atheros                      | 53       | 6.78%   |
| TP-Link                               | 33       | 4.22%   |
| Ralink Technology                     | 26       | 3.32%   |
| Broadcom                              | 23       | 2.94%   |
| Nvidia                                | 16       | 2.05%   |
| Marvell Technology Group              | 15       | 1.92%   |
| MediaTek                              | 8        | 1.02%   |
| Ralink                                | 7        | 0.9%    |
| VIA Technologies                      | 6        | 0.77%   |
| Qualcomm Atheros Communications       | 6        | 0.77%   |
| D-Link                                | 5        | 0.64%   |
| Microsoft                             | 4        | 0.51%   |
| Broadcom Limited                      | 4        | 0.51%   |
| Xiaomi                                | 3        | 0.38%   |
| ASUSTek Computer                      | 3        | 0.38%   |
| NetGear                               | 2        | 0.26%   |
| Motorola                              | 2        | 0.26%   |
| D-Link System                         | 2        | 0.26%   |
| Belkin Components                     | 2        | 0.26%   |
| ZyDAS                                 | 1        | 0.13%   |
| Sundance Technology Inc / IC Plus     | 1        | 0.13%   |
| Philips (or NXP)                      | 1        | 0.13%   |
| PCTel                                 | 1        | 0.13%   |
| Ovislink                              | 1        | 0.13%   |
| Micro Star International              | 1        | 0.13%   |
| IBM                                   | 1        | 0.13%   |
| Huawei Technologies                   | 1        | 0.13%   |
| Fujitsu Siemens Computers             | 1        | 0.13%   |
| Dresden Elektronik                    | 1        | 0.13%   |
| ASIX Electronics                      | 1        | 0.13%   |
| Aquantia                              | 1        | 0.13%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.13%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 285      | 33.02%  |
| Intel I211 Gigabit Network Connection                                  | 41       | 4.75%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 32       | 3.71%   |
| Realtek RTL8125 2.5GbE Controller                                      | 23       | 2.67%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 15       | 1.74%   |
| Intel Ethernet Connection (2) I219-V                                   | 15       | 1.74%   |
| Intel Wi-Fi 6 AX200                                                    | 14       | 1.62%   |
| Intel Ethernet Connection I217-LM                                      | 14       | 1.62%   |
| Ralink RT2870/RT3070 Wireless Adapter                                  | 12       | 1.39%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 12       | 1.39%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                           | 10       | 1.16%   |
| Intel Ethernet Connection (2) I218-V                                   | 10       | 1.16%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 9        | 1.04%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 9        | 1.04%   |
| Intel Ethernet Controller I225-V                                       | 8        | 0.93%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 8        | 0.93%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                            | 7        | 0.81%   |
| Realtek 802.11ac NIC                                                   | 7        | 0.81%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 7        | 0.81%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 7        | 0.81%   |
| Intel Ethernet Connection I217-V                                       | 7        | 0.81%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6        | 0.7%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6        | 0.7%    |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter             | 6        | 0.7%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                | 6        | 0.7%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                 | 5        | 0.58%   |
| Ralink RT5370 Wireless Adapter                                         | 5        | 0.58%   |
| Qualcomm Atheros AR9271 802.11n                                        | 5        | 0.58%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                       | 5        | 0.58%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5        | 0.58%   |
| Nvidia MCP61 Ethernet                                                  | 5        | 0.58%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 5        | 0.58%   |
| Intel Ethernet Connection (2) I219-LM                                  | 5        | 0.58%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                | 4        | 0.46%   |
| Realtek RTL8187 Wireless Adapter                                       | 4        | 0.46%   |
| Ralink MT7601U Wireless Adapter                                        | 4        | 0.46%   |
| Ralink RT2561/RT61 802.11g PCI                                         | 4        | 0.46%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 4        | 0.46%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                       | 4        | 0.46%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4        | 0.46%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Desktops | Percent |
|---------------------------------------|----------|---------|
| Realtek Semiconductor                 | 58       | 25.55%  |
| Intel                                 | 42       | 18.5%   |
| TP-Link                               | 33       | 14.54%  |
| Ralink Technology                     | 26       | 11.45%  |
| Qualcomm Atheros                      | 21       | 9.25%   |
| Ralink                                | 7        | 3.08%   |
| Qualcomm Atheros Communications       | 6        | 2.64%   |
| MediaTek                              | 6        | 2.64%   |
| Broadcom                              | 6        | 2.64%   |
| D-Link                                | 5        | 2.2%    |
| Microsoft                             | 4        | 1.76%   |
| ASUSTek Computer                      | 3        | 1.32%   |
| NetGear                               | 2        | 0.88%   |
| Belkin Components                     | 2        | 0.88%   |
| ZyDAS                                 | 1        | 0.44%   |
| Philips (or NXP)                      | 1        | 0.44%   |
| Ovislink                              | 1        | 0.44%   |
| Micro Star International              | 1        | 0.44%   |
| Fujitsu Siemens Computers             | 1        | 0.44%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 1        | 0.44%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                                         | Desktops | Percent |
|-----------------------------------------------------------------------------------------------|----------|---------|
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                                           | 15       | 6.49%   |
| Intel Wi-Fi 6 AX200                                                                           | 14       | 6.06%   |
| Ralink RT2870/RT3070 Wireless Adapter                                                         | 12       | 5.19%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                                                  | 10       | 4.33%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                                                   | 7        | 3.03%   |
| Realtek 802.11ac NIC                                                                          | 7        | 3.03%   |
| Qualcomm Atheros AR5212/5213/2414 Wireless Network Adapter                                    | 6        | 2.6%    |
| Intel Wi-Fi 5(802.11ac) Wireless-AC 9x6x [Thunder Peak]                                       | 6        | 2.6%    |
| Realtek RTL8192CU 802.11n WLAN Adapter                                                        | 5        | 2.16%   |
| Ralink RT5370 Wireless Adapter                                                                | 5        | 2.16%   |
| Qualcomm Atheros AR9271 802.11n                                                               | 5        | 2.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                              | 5        | 2.16%   |
| Realtek RTL8188CUS 802.11n WLAN Adapter                                                       | 4        | 1.73%   |
| Realtek RTL8187 Wireless Adapter                                                              | 4        | 1.73%   |
| Ralink MT7601U Wireless Adapter                                                               | 4        | 1.73%   |
| Ralink RT2561/RT61 802.11g PCI                                                                | 4        | 1.73%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                                              | 4        | 1.73%   |
| Broadcom BCM4360 802.11ac Dual Band Wireless Network Adapter                                  | 4        | 1.73%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                                                           | 3        | 1.3%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]                                    | 3        | 1.3%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                                                    | 3        | 1.3%    |
| Realtek Realtek 8812AU/8821AU 802.11ac WLAN Adapter [USB Wireless Dual-Band Adapter 2.4/5Ghz] | 3        | 1.3%    |
| Intel PRO/Wireless 2200BG [Calexico2] Network Connection                                      | 3        | 1.3%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                              | 3        | 1.3%    |
| Intel Comet Lake PCH CNVi WiFi                                                                | 3        | 1.3%    |
| Intel Alder Lake-S PCH CNVi WiFi                                                              | 3        | 1.3%    |
| TP-Link TL-WN822N Version 4 RTL8192EU                                                         | 2        | 0.87%   |
| TP-Link 802.11n NIC                                                                           | 2        | 0.87%   |
| TP-Link 802.11ac NIC                                                                          | 2        | 0.87%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller                                   | 2        | 0.87%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                               | 2        | 0.87%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                                       | 2        | 0.87%   |
| Realtek RTL8192EU 802.11b/g/n WLAN Adapter                                                    | 2        | 0.87%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                                               | 2        | 0.87%   |
| Realtek RTL8188SU 802.11n WLAN Adapter                                                        | 2        | 0.87%   |
| Ralink RT5372 Wireless Adapter                                                                | 2        | 0.87%   |
| Ralink RT3072 Wireless Adapter                                                                | 2        | 0.87%   |
| Ralink RT2790 Wireless 802.11n 1T/2R PCIe                                                     | 2        | 0.87%   |
| Microsoft Xbox Wireless Adapter for Windows                                                   | 2        | 0.87%   |
| Microsoft Xbox 360 Wireless Adapter                                                           | 2        | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Desktops | Percent |
|-----------------------------------|----------|---------|
| Realtek Semiconductor             | 334      | 54.4%   |
| Intel                             | 178      | 28.99%  |
| Qualcomm Atheros                  | 34       | 5.54%   |
| Broadcom                          | 17       | 2.77%   |
| Nvidia                            | 16       | 2.61%   |
| Marvell Technology Group          | 15       | 2.44%   |
| VIA Technologies                  | 5        | 0.81%   |
| Broadcom Limited                  | 4        | 0.65%   |
| Xiaomi                            | 3        | 0.49%   |
| MediaTek                          | 2        | 0.33%   |
| D-Link System                     | 2        | 0.33%   |
| Sundance Technology Inc / IC Plus | 1        | 0.16%   |
| Huawei Technologies               | 1        | 0.16%   |
| ASIX Electronics                  | 1        | 0.16%   |
| Aquantia                          | 1        | 0.16%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Desktops | Percent |
|------------------------------------------------------------------------|----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 285      | 45.53%  |
| Intel I211 Gigabit Network Connection                                  | 41       | 6.55%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 32       | 5.11%   |
| Realtek RTL8125 2.5GbE Controller                                      | 23       | 3.67%   |
| Intel Ethernet Connection (2) I219-V                                   | 15       | 2.4%    |
| Intel Ethernet Connection I217-LM                                      | 14       | 2.24%   |
| Intel 82567LM-3 Gigabit Network Connection                             | 12       | 1.92%   |
| Intel Ethernet Connection (2) I218-V                                   | 10       | 1.6%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                        | 9        | 1.44%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                  | 9        | 1.44%   |
| Intel Ethernet Controller I225-V                                       | 8        | 1.28%   |
| Broadcom NetXtreme BCM5751 Gigabit Ethernet PCI Express                | 8        | 1.28%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet         | 7        | 1.12%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller                | 7        | 1.12%   |
| Intel Ethernet Connection I217-V                                       | 7        | 1.12%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 6        | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                          | 6        | 0.96%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 5        | 0.8%    |
| Nvidia MCP61 Ethernet                                                  | 5        | 0.8%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                | 5        | 0.8%    |
| Intel Ethernet Connection (2) I219-LM                                  | 5        | 0.8%    |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                          | 4        | 0.64%   |
| Intel Ethernet Connection (7) I219-LM                                  | 4        | 0.64%   |
| VIA VT6102/VT6103 [Rhine-II]                                           | 3        | 0.48%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller              | 3        | 0.48%   |
| Nvidia MCP77 Ethernet                                                  | 3        | 0.48%   |
| Nvidia MCP55 Ethernet                                                  | 3        | 0.48%   |
| Marvell Group 88E8001 Gigabit Ethernet Controller                      | 3        | 0.48%   |
| Intel Ethernet Connection (7) I219-V                                   | 3        | 0.48%   |
| Intel 82578DM Gigabit Network Connection                               | 3        | 0.48%   |
| Broadcom NetXtreme BCM5754 Gigabit Ethernet PCI Express                | 3        | 0.48%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 2        | 0.32%   |
| VIA VT6105/VT6106S [Rhine-III]                                         | 2        | 0.32%   |
| Realtek RTL-8110SC/8169SC Gigabit Ethernet                             | 2        | 0.32%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 2        | 0.32%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller              | 2        | 0.32%   |
| Qualcomm Atheros Attansic L2 Fast Ethernet                             | 2        | 0.32%   |
| Nvidia MCP73 Ethernet                                                  | 2        | 0.32%   |
| Nvidia MCP51 Ethernet Controller                                       | 2        | 0.32%   |
| MediaTek File-CD Gadget                                                | 2        | 0.32%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 580      | 73.14%  |
| WiFi     | 207      | 26.1%   |
| Modem    | 5        | 0.63%   |
| Unknown  | 1        | 0.13%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Desktops | Percent |
|----------|----------|---------|
| Ethernet | 474      | 78.48%  |
| WiFi     | 130      | 21.52%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Desktops | Percent |
|-------|----------|---------|
| 1     | 453      | 77.44%  |
| 2     | 109      | 18.63%  |
| 3     | 16       | 2.74%   |
| 0     | 5        | 0.85%   |
| 4     | 2        | 0.34%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Desktops | Percent |
|------|----------|---------|
| No   | 442      | 73.18%  |
| Yes  | 162      | 26.82%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Desktops | Percent |
|---------------------------------|----------|---------|
| Cambridge Silicon Radio         | 43       | 36.13%  |
| Intel                           | 38       | 31.93%  |
| Broadcom                        | 8        | 6.72%   |
| ASUSTek Computer                | 7        | 5.88%   |
| Realtek Semiconductor           | 6        | 5.04%   |
| TP-Link                         | 2        | 1.68%   |
| Qualcomm Atheros Communications | 2        | 1.68%   |
| Mobile Action Technology        | 2        | 1.68%   |
| Micro Star International        | 2        | 1.68%   |
| MediaTek                        | 1        | 0.84%   |
| Integrated System Solution      | 1        | 0.84%   |
| IMC Networks                    | 1        | 0.84%   |
| Hewlett-Packard                 | 1        | 0.84%   |
| Foxconn / Hon Hai               | 1        | 0.84%   |
| Edimax Technology               | 1        | 0.84%   |
| Belkin Components               | 1        | 0.84%   |
| Actions                         | 1        | 0.84%   |
| Unknown                         | 1        | 0.84%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                 | Desktops | Percent |
|-------------------------------------------------------|----------|---------|
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)   | 43       | 36.13%  |
| Intel AX200 Bluetooth                                 | 13       | 10.92%  |
| Intel Wireless-AC 9260 Bluetooth Adapter              | 7        | 5.88%   |
| Realtek Bluetooth Radio                               | 6        | 5.04%   |
| Intel AX201 Bluetooth                                 | 5        | 4.2%    |
| Intel Wireless-AC 3168 Bluetooth                      | 3        | 2.52%   |
| Intel Bluetooth wireless interface                    | 3        | 2.52%   |
| Broadcom BCM20702A0 Bluetooth 4.0                     | 3        | 2.52%   |
| TP-Link UB500 Adapter                                 | 2        | 1.68%   |
| Qualcomm Atheros  Bluetooth Device                    | 2        | 1.68%   |
| Intel Centrino Bluetooth Wireless Transceiver         | 2        | 1.68%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)        | 2        | 1.68%   |
| Intel AX210 Bluetooth                                 | 2        | 1.68%   |
| ASUS Broadcom BCM20702A0 Bluetooth                    | 2        | 1.68%   |
| ASUS Broadcom BCM20702 Single-Chip Bluetooth 4.0 + LE | 2        | 1.68%   |
| ASUS Bluetooth Radio                                  | 2        | 1.68%   |
| Mobile Action MA-730/MA-730G Bluetooth Adapter        | 1        | 0.84%   |
| Mobile Action MA-700 Bluetooth Adapter                | 1        | 0.84%   |
| Micro Star International Bluetooth EDR Device         | 1        | 0.84%   |
| Micro Star International Bluetooth Device             | 1        | 0.84%   |
| MediaTek Wireless_Device                              | 1        | 0.84%   |
| Intel Bluetooth Device                                | 1        | 0.84%   |
| Integrated System Solution Bluetooth Device           | 1        | 0.84%   |
| IMC Networks Bluetooth Device                         | 1        | 0.84%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]         | 1        | 0.84%   |
| Foxconn / Hon Hai Wireless_Device                     | 1        | 0.84%   |
| Edimax Bluetooth Adapter                              | 1        | 0.84%   |
| Broadcom Bluetooth 3.0 Device                         | 1        | 0.84%   |
| Broadcom BCM92045B3 ROM                               | 1        | 0.84%   |
| Broadcom BCM43142 Bluetooth 4.0                       | 1        | 0.84%   |
| Broadcom BCM2045 Bluetooth                            | 1        | 0.84%   |
| Broadcom BCM2035 Bluetooth dongle                     | 1        | 0.84%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter | 1        | 0.84%   |
| ASUS Bluetooth Adapter                                | 1        | 0.84%   |
| Actions general adapter                               | 1        | 0.84%   |
| Unknown                                               | 1        | 0.84%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                                          | Desktops | Percent |
|-------------------------------------------------|----------|---------|
| Intel                                           | 357      | 37.3%   |
| AMD                                             | 259      | 27.06%  |
| Nvidia                                          | 209      | 21.84%  |
| C-Media Electronics                             | 27       | 2.82%   |
| Creative Labs                                   | 14       | 1.46%   |
| Razer USA                                       | 7        | 0.73%   |
| Logitech                                        | 7        | 0.73%   |
| Creative Technology                             | 7        | 0.73%   |
| Focusrite-Novation                              | 5        | 0.52%   |
| Kingston Technology                             | 4        | 0.42%   |
| GN Netcom                                       | 4        | 0.42%   |
| Barco Display Systems                           | 4        | 0.42%   |
| VIA Technologies                                | 3        | 0.31%   |
| Texas Instruments                               | 3        | 0.31%   |
| Cooler Master                                   | 3        | 0.31%   |
| BEHRINGER International                         | 3        | 0.31%   |
| Yamaha                                          | 2        | 0.21%   |
| Nordic Semiconductor ASA                        | 2        | 0.21%   |
| Native Instruments                              | 2        | 0.21%   |
| JMTek                                           | 2        | 0.21%   |
| Hewlett-Packard                                 | 2        | 0.21%   |
| Ensoniq                                         | 2        | 0.21%   |
| Edifier Technology                              | 2        | 0.21%   |
| Dell                                            | 2        | 0.21%   |
| AudioQuest                                      | 2        | 0.21%   |
| ASUSTek Computer                                | 2        | 0.21%   |
| Altec Lansing Technologies                      | 2        | 0.21%   |
| Trust                                           | 1        | 0.1%    |
| Tenx Technology                                 | 1        | 0.1%    |
| SteelSeries ApS                                 | 1        | 0.1%    |
| Shenzhen Riitek Technology                      | 1        | 0.1%    |
| RODE Microphones                                | 1        | 0.1%    |
| Plantronics                                     | 1        | 0.1%    |
| Numark                                          | 1        | 0.1%    |
| Mark of the Unicorn                             | 1        | 0.1%    |
| M-Audio                                         | 1        | 0.1%    |
| Licensed by Sony Computer Entertainment America | 1        | 0.1%    |
| Guillemot                                       | 1        | 0.1%    |
| Giga-Byte Technology                            | 1        | 0.1%    |
| Generalplus Technology                          | 1        | 0.1%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Desktops | Percent |
|----------------------------------------------------------------------------|----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                               | 51       | 4.52%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 47       | 4.17%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 45       | 3.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 43       | 3.81%   |
| AMD Family 17h/19h HD Audio Controller                                     | 42       | 3.72%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 40       | 3.55%   |
| AMD Starship/Matisse HD Audio Controller                                   | 37       | 3.28%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 34       | 3.01%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 33       | 2.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 31       | 2.75%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 26       | 2.3%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 23       | 2.04%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 22       | 1.95%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 21       | 1.86%   |
| Nvidia GP107GL High Definition Audio Controller                            | 20       | 1.77%   |
| Intel 200 Series PCH HD Audio                                              | 20       | 1.77%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 20       | 1.77%   |
| Nvidia High Definition Audio Controller                                    | 18       | 1.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 16       | 1.42%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 15       | 1.33%   |
| Intel 9 Series Chipset Family HD Audio Controller                          | 14       | 1.24%   |
| AMD FCH Azalia Controller                                                  | 14       | 1.24%   |
| Nvidia GF108 High Definition Audio Controller                              | 13       | 1.15%   |
| Intel Cannon Lake PCH cAVS                                                 | 13       | 1.15%   |
| Intel 82801JD/DO (ICH10 Family) HD Audio Controller                        | 13       | 1.15%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13       | 1.15%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 13       | 1.15%   |
| Nvidia TU116 High Definition Audio Controller                              | 11       | 0.98%   |
| Nvidia GP106 High Definition Audio Controller                              | 10       | 0.89%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 10       | 0.89%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 10       | 0.89%   |
| Nvidia GP108 High Definition Audio Controller                              | 9        | 0.8%    |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 8        | 0.71%   |
| Nvidia GP104 High Definition Audio Controller                              | 8        | 0.71%   |
| Nvidia GF119 HDMI Audio Controller                                         | 8        | 0.71%   |
| Intel 82801G (ICH7 Family) AC'97 Audio Controller                          | 8        | 0.71%   |
| AMD Turks HDMI Audio [Radeon HD 6500/6600 / 6700M Series]                  | 8        | 0.71%   |
| AMD Navi 10 HDMI Audio                                                     | 8        | 0.71%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 8        | 0.71%   |
| Nvidia GM206 High Definition Audio Controller                              | 7        | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Unknown             | 73       | 23.4%   |
| Kingston            | 58       | 18.59%  |
| G.Skill             | 45       | 14.42%  |
| Corsair             | 42       | 13.46%  |
| Samsung Electronics | 21       | 6.73%   |
| Crucial             | 21       | 6.73%   |
| SK hynix            | 14       | 4.49%   |
| Micron Technology   | 8        | 2.56%   |
| Team                | 5        | 1.6%    |
| Transcend           | 3        | 0.96%   |
| Patriot             | 3        | 0.96%   |
| Nanya Technology    | 3        | 0.96%   |
| Unknown             | 3        | 0.96%   |
| Apacer              | 2        | 0.64%   |
| Veineda             | 1        | 0.32%   |
| Silicon Power       | 1        | 0.32%   |
| Ramaxel Technology  | 1        | 0.32%   |
| Qimonda             | 1        | 0.32%   |
| Lexar               | 1        | 0.32%   |
| H                   | 1        | 0.32%   |
| GOODRAM             | 1        | 0.32%   |
| Goldkey             | 1        | 0.32%   |
| GeIL                | 1        | 0.32%   |
| Elpida              | 1        | 0.32%   |
| Avant               | 1        | 0.32%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                  | Desktops | Percent |
|--------------------------------------------------------|----------|---------|
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s    | 12       | 3.42%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                   | 5        | 1.42%   |
| Unknown RAM Module 2GB DIMM 800MT/s                    | 5        | 1.42%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                   | 5        | 1.42%   |
| Unknown RAM Module 1024MB DIMM SDRAM                   | 5        | 1.42%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s            | 4        | 1.14%   |
| Unknown RAM Module 2048MB DIMM DDR 533MT/s             | 4        | 1.14%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s | 4        | 1.14%   |
| Corsair RAM CMZ8GX3M2A1600C9 4GB DIMM DDR3 1800MT/s    | 4        | 1.14%   |
| Unknown RAM Module 512MB DIMM SDRAM                    | 3        | 0.85%   |
| Unknown RAM Module 2048MB DIMM SDRAM                   | 3        | 0.85%   |
| Unknown RAM Module 1GB DIMM SDRAM                      | 3        | 0.85%   |
| Unknown RAM Module 1024MB DIMM DDR2 800MT/s            | 3        | 0.85%   |
| Unknown RAM Module 1024MB DIMM 800MT/s                 | 3        | 0.85%   |
| G.Skill RAM F4-3200C16-8GTZR 8GB DIMM DDR4 3200MT/s    | 3        | 0.85%   |
| G.Skill RAM F4-3200C16-16GVK 16GB DIMM DDR4 3600MT/s   | 3        | 0.85%   |
| G.Skill RAM F4-3200C14-8GFX 8GB DIMM DDR4 3733MT/s     | 3        | 0.85%   |
| Corsair RAM CMZ4GX3M1A1600C9 4GB DIMM DDR3 1600MT/s    | 3        | 0.85%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s  | 3        | 0.85%   |
| Corsair RAM CMK16GX4M2A2400C16 8GB DIMM DDR4 2933MT/s  | 3        | 0.85%   |
| Unknown                                                | 3        | 0.85%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                | 2        | 0.57%   |
| Unknown RAM Module 2GB DIMM 400MT/s                    | 2        | 0.57%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                 | 2        | 0.57%   |
| Unknown RAM Module 1GB DIMM                            | 2        | 0.57%   |
| Unknown RAM Module 1024MB DIMM DDR 533MT/s             | 2        | 0.57%   |
| Unknown RAM 4400 C19 Series 8GB DIMM DDR4 2133MT/s     | 2        | 0.57%   |
| Samsung RAM M378B5773DH0-CH9 2GB DIMM DDR3 1333MT/s    | 2        | 0.57%   |
| Samsung RAM M378B5673FH0-CH9 2GB DIMM DDR3 1600MT/s    | 2        | 0.57%   |
| Samsung RAM M378B5173EB0-YK0 4GB DIMM DDR3 1600MT/s    | 2        | 0.57%   |
| Kingston RAM Module 2048MB DIMM DDR2 667MT/s           | 2        | 0.57%   |
| Kingston RAM KHX2933C15D4/8GX 8GB DIMM DDR4 2933MT/s   | 2        | 0.57%   |
| Kingston RAM KHX2666C16/16G 16GB DIMM DDR4 3200MT/s    | 2        | 0.57%   |
| Kingston RAM KHX2133C14D4/8G 8GB DIMM DDR4 2667MT/s    | 2        | 0.57%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s    | 2        | 0.57%   |
| Kingston RAM KHX1600C9D3/4GX 4GB DIMM DDR3 1600MT/s    | 2        | 0.57%   |
| Kingston RAM KF3600C16D4/16GX 16GB DIMM DDR4 3800MT/s  | 2        | 0.57%   |
| G.Skill RAM F4-2666C19-8GIS 8GB DIMM DDR4 3200MT/s     | 2        | 0.57%   |
| Crucial RAM CT8G4DFS8266.M8FD 8GB DIMM DDR4 3600MT/s   | 2        | 0.57%   |
| Crucial RAM CT4G4DFS824A.C8FHP 4GB DIMM DDR4 2400MT/s  | 2        | 0.57%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Desktops | Percent |
|---------|----------|---------|
| DDR4    | 108      | 38.85%  |
| DDR3    | 76       | 27.34%  |
| Unknown | 33       | 11.87%  |
| SDRAM   | 21       | 7.55%   |
| DDR2    | 19       | 6.83%   |
| DDR     | 15       | 5.4%    |
| DDR5    | 5        | 1.8%    |
| DRAM    | 1        | 0.36%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name   | Desktops | Percent |
|--------|----------|---------|
| DIMM   | 261      | 97.75%  |
| SODIMM | 6        | 2.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Desktops | Percent |
|-------|----------|---------|
| 8192  | 106      | 35.45%  |
| 2048  | 65       | 21.74%  |
| 4096  | 63       | 21.07%  |
| 1024  | 28       | 9.36%   |
| 16384 | 25       | 8.36%   |
| 32768 | 7        | 2.34%   |
| 512   | 5        | 1.67%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Desktops | Percent |
|---------|----------|---------|
| 1600    | 43       | 13.87%  |
| 1333    | 33       | 10.65%  |
| 800     | 23       | 7.42%   |
| 3200    | 21       | 6.77%   |
| 3600    | 18       | 5.81%   |
| 2400    | 15       | 4.84%   |
| 3866    | 12       | 3.87%   |
| 667     | 12       | 3.87%   |
| Unknown | 12       | 3.87%   |
| 2667    | 10       | 3.23%   |
| 2933    | 9        | 2.9%    |
| 2133    | 9        | 2.9%    |
| 1066    | 8        | 2.58%   |
| 533     | 7        | 2.26%   |
| 3000    | 6        | 1.94%   |
| 1800    | 6        | 1.94%   |
| 3733    | 5        | 1.61%   |
| 1866    | 5        | 1.61%   |
| 3800    | 4        | 1.29%   |
| 3400    | 4        | 1.29%   |
| 1867    | 4        | 1.29%   |
| 400     | 4        | 1.29%   |
| 3007    | 3        | 0.97%   |
| 2800    | 3        | 0.97%   |
| 2733    | 3        | 0.97%   |
| 2666    | 3        | 0.97%   |
| 2048    | 3        | 0.97%   |
| 333     | 3        | 0.97%   |
| 49926   | 2        | 0.65%   |
| 4266    | 2        | 0.65%   |
| 3666    | 2        | 0.65%   |
| 12800   | 1        | 0.32%   |
| 6000    | 1        | 0.32%   |
| 5808    | 1        | 0.32%   |
| 5200    | 1        | 0.32%   |
| 4802    | 1        | 0.32%   |
| 4000    | 1        | 0.32%   |
| 3534    | 1        | 0.32%   |
| 3500    | 1        | 0.32%   |
| 3466    | 1        | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Desktops | Percent |
|---------------------|----------|---------|
| Hewlett-Packard     | 28       | 62.22%  |
| Canon               | 8        | 17.78%  |
| Samsung Electronics | 5        | 11.11%  |
| Seiko Epson         | 2        | 4.44%   |
| Ricoh               | 1        | 2.22%   |
| QinHeng Electronics | 1        | 2.22%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                        | Desktops | Percent |
|------------------------------|----------|---------|
| HP DeskJet 3830 series       | 3        | 6.67%   |
| Canon TS3100 series          | 3        | 6.67%   |
| Seiko Epson L310 Series      | 2        | 4.44%   |
| Samsung M2020 Series         | 2        | 4.44%   |
| Samsung SCX-3400 Series      | 1        | 2.22%   |
| Samsung M267x 287x Series    | 1        | 2.22%   |
| Samsung M2070 Series         | 1        | 2.22%   |
| Ricoh SP 112SU               | 1        | 2.22%   |
| QinHeng CH340S               | 1        | 2.22%   |
| HP Smart Tank 580-590 series | 1        | 2.22%   |
| HP Smart Tank 510 series     | 1        | 2.22%   |
| HP Officejet Pro L7400       | 1        | 2.22%   |
| HP OfficeJet Pro 8020 series | 1        | 2.22%   |
| HP Officejet J4500 series    | 1        | 2.22%   |
| HP Officejet 4500 G510g-m    | 1        | 2.22%   |
| HP LaserJet P1102            | 1        | 2.22%   |
| HP LaserJet P1005            | 1        | 2.22%   |
| HP LaserJet 1020             | 1        | 2.22%   |
| HP LaserJet 1018             | 1        | 2.22%   |
| HP LaserJet 1010             | 1        | 2.22%   |
| HP DeskJet F300 series       | 1        | 2.22%   |
| HP DeskJet F2492 All-in-One  | 1        | 2.22%   |
| HP DeskJet D2300             | 1        | 2.22%   |
| HP DeskJet 930c              | 1        | 2.22%   |
| HP DeskJet 840c              | 1        | 2.22%   |
| HP DeskJet 4670 series       | 1        | 2.22%   |
| HP DeskJet 4530 series       | 1        | 2.22%   |
| HP DeskJet 4100 series       | 1        | 2.22%   |
| HP DeskJet 3700 series       | 1        | 2.22%   |
| HP Deskjet 2640 series       | 1        | 2.22%   |
| HP DeskJet 2600 series       | 1        | 2.22%   |
| HP Deskjet 2510 series       | 1        | 2.22%   |
| HP DeskJet 2300 series       | 1        | 2.22%   |
| HP Deskjet 2050 J510         | 1        | 2.22%   |
| Canon TR4500 series          | 1        | 2.22%   |
| Canon PIXMA MX390 Series     | 1        | 2.22%   |
| Canon PIXMA MX320 series     | 1        | 2.22%   |
| Canon PIXMA MG5600 Series    | 1        | 2.22%   |
| Canon LiDE 400               | 1        | 2.22%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Desktops | Percent |
|-----------------|----------|---------|
| Canon           | 4        | 57.14%  |
| Hewlett-Packard | 2        | 28.57%  |
| Seiko Epson     | 1        | 14.29%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                       | Desktops | Percent |
|---------------------------------------------|----------|---------|
| Seiko Epson GT-X800 [Perfection 4990 PHOTO] | 1        | 14.29%  |
| HP Scanjet G2710                            | 1        | 14.29%  |
| HP ScanJet 4370                             | 1        | 14.29%  |
| Canon CanoScan LiDE 220                     | 1        | 14.29%  |
| Canon CanoScan LiDE 110                     | 1        | 14.29%  |
| Canon CanoScan LiDE 100                     | 1        | 14.29%  |
| Canon CanoScan 1220U                        | 1        | 14.29%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                        | Desktops | Percent |
|-------------------------------|----------|---------|
| Logitech                      | 45       | 32.61%  |
| Microsoft                     | 17       | 12.32%  |
| Microdia                      | 14       | 10.14%  |
| Generalplus Technology        | 9        | 6.52%   |
| Creative Technology           | 7        | 5.07%   |
| Z-Star Microelectronics       | 4        | 2.9%    |
| Sunplus Innovation Technology | 4        | 2.9%    |
| Philips (or NXP)              | 4        | 2.9%    |
| Aveo Technology               | 4        | 2.9%    |
| Arkmicro Technologies         | 4        | 2.9%    |
| Alcor Micro                   | 3        | 2.17%   |
| Realtek Semiconductor         | 2        | 1.45%   |
| Razer USA                     | 2        | 1.45%   |
| Jieli Technology              | 2        | 1.45%   |
| Genesys Logic                 | 2        | 1.45%   |
| Cubeternet                    | 2        | 1.45%   |
| Chicony Electronics           | 2        | 1.45%   |
| Xiongmai                      | 1        | 0.72%   |
| webcamvendor                  | 1        | 0.72%   |
| Trust                         | 1        | 0.72%   |
| Sweex                         | 1        | 0.72%   |
| Samsung Electronics           | 1        | 0.72%   |
| Pixart Imaging                | 1        | 0.72%   |
| Nokia Mobile Phones           | 1        | 0.72%   |
| MacroSilicon                  | 1        | 0.72%   |
| Lite-On Technology            | 1        | 0.72%   |
| IMC Networks                  | 1        | 0.72%   |
| Guillemot                     | 1        | 0.72%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                    | Desktops | Percent |
|------------------------------------------|----------|---------|
| Logitech Webcam C270                     | 18       | 12.95%  |
| Microsoft LifeCam HD-3000                | 6        | 4.32%   |
| Microdia USB 2.0 Camera                  | 5        | 3.6%    |
| Microdia Camera                          | 5        | 3.6%    |
| Generalplus 808 Camera                   | 5        | 3.6%    |
| Logitech Webcam C310                     | 4        | 2.88%   |
| Logitech Webcam C300                     | 4        | 2.88%   |
| Generalplus GENERAL WEBCAM               | 4        | 2.88%   |
| Creative Live! Cam Sync 1080p V2         | 4        | 2.88%   |
| Aveo USB2.0 Camera                       | 4        | 2.88%   |
| Arkmicro USB2.0 PC CAMERA                | 4        | 2.88%   |
| Z-Star Venus USB2.0 Camera               | 3        | 2.16%   |
| Philips (or NXP) SPC 520/525NC PC Camera | 3        | 2.16%   |
| Logitech Webcam C170                     | 3        | 2.16%   |
| Alcor Micro USB 2.0 PC Camera            | 3        | 2.16%   |
| Sunplus HD 720P webcam                   | 2        | 1.44%   |
| Sunplus Full HD webcam                   | 2        | 1.44%   |
| Realtek HD 720P Webcam                   | 2        | 1.44%   |
| Razer USA Gaming Webcam [Kiyo]           | 2        | 1.44%   |
| Microsoft LifeCam VX-800                 | 2        | 1.44%   |
| Microsoft LifeCam VX-500 [1357]          | 2        | 1.44%   |
| Microsoft LifeCam Cinema                 | 2        | 1.44%   |
| Microdia Sonix USB 2.0 Camera            | 2        | 1.44%   |
| Logitech Webcam C110                     | 2        | 1.44%   |
| Logitech HD Webcam C910                  | 2        | 1.44%   |
| Logitech HD Webcam C615                  | 2        | 1.44%   |
| Logitech HD Pro Webcam C920              | 2        | 1.44%   |
| Logitech C922 Pro Stream Webcam          | 2        | 1.44%   |
| Jieli USB PHY 2.0                        | 2        | 1.44%   |
| Cubeternet USB2.0 Camera                 | 2        | 1.44%   |
| Creative Live! Cam Sync 1080p            | 2        | 1.44%   |
| Z-Star Vega USB 2.0 Camera               | 1        | 0.72%   |
| Xiongmai web camera                      | 1        | 0.72%   |
| webcamvendor webcamproduct               | 1        | 0.72%   |
| Trust USB Camera                         | 1        | 0.72%   |
| Sweex WC060 Series HD Webcam             | 1        | 0.72%   |
| Samsung Galaxy series, misc. (MTP mode)  | 1        | 0.72%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro     | 1        | 0.72%   |
| Philips (or NXP) Webcam SPC530NC         | 1        | 0.72%   |
| Nokia Mobile Phones Lumia 640 Phone      | 1        | 0.72%   |

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
| 0     | 503      | 84.82%  |
| 1     | 79       | 13.32%  |
| 2     | 8        | 1.35%   |
| 3     | 2        | 0.34%   |
| 4     | 1        | 0.17%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Desktops | Percent |
|--------------------------|----------|---------|
| Graphics card            | 36       | 36%     |
| Net/wireless             | 28       | 28%     |
| Communication controller | 10       | 10%     |
| Multimedia controller    | 6        | 6%      |
| Sound                    | 4        | 4%      |
| Dvb card                 | 4        | 4%      |
| Unassigned class         | 3        | 3%      |
| Network                  | 2        | 2%      |
| Modem                    | 2        | 2%      |
| Storage/raid             | 1        | 1%      |
| Net/ethernet             | 1        | 1%      |
| Firewire controller      | 1        | 1%      |
| Card reader              | 1        | 1%      |
| Camera                   | 1        | 1%      |

