Nobara - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Nobara.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Nobara/Desktop/README.md) and [notebooks](/Dist/Nobara/Notebook/README.md).

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

Total: 567

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ROG Zephyrus Duo 16 GX65... | Notebook    | [b54238dc33](https://linux-hardware.org/?probe=b54238dc33) | May 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [62d194e85e](https://linux-hardware.org/?probe=62d194e85e) | May 01, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [e2acacabb3](https://linux-hardware.org/?probe=e2acacabb3) | Apr 30, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [8aa973e0f5](https://linux-hardware.org/?probe=8aa973e0f5) | Apr 30, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [9419686ec7](https://linux-hardware.org/?probe=9419686ec7) | Apr 30, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [1f61fda034](https://linux-hardware.org/?probe=1f61fda034) | Apr 30, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [b2616ea409](https://linux-hardware.org/?probe=b2616ea409) | Apr 28, 2023 |
| HP            | Unknown                     | Notebook    | [bba45b8ff0](https://linux-hardware.org/?probe=bba45b8ff0) | Apr 27, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [169e095fab](https://linux-hardware.org/?probe=169e095fab) | Apr 27, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c80b811f3e](https://linux-hardware.org/?probe=c80b811f3e) | Apr 27, 2023 |
| ASRock        | B550M Phantom Gaming 4      | Desktop     | [072b88204c](https://linux-hardware.org/?probe=072b88204c) | Apr 26, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [f02e8339e9](https://linux-hardware.org/?probe=f02e8339e9) | Apr 25, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [8de5e39740](https://linux-hardware.org/?probe=8de5e39740) | Apr 25, 2023 |
| MSI           | MAG Z690 TOMAHAWK WIFI D... | Desktop     | [e4064abe78](https://linux-hardware.org/?probe=e4064abe78) | Apr 24, 2023 |
| Lenovo        | ThinkPad Edge E540 20C6C... | Notebook    | [fc22fb4921](https://linux-hardware.org/?probe=fc22fb4921) | Apr 23, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [e3dc4788e7](https://linux-hardware.org/?probe=e3dc4788e7) | Apr 22, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [8db6f88fd3](https://linux-hardware.org/?probe=8db6f88fd3) | Apr 22, 2023 |
| ASUSTek       | TUF Gaming A520M-PLUS       | Desktop     | [28631c09aa](https://linux-hardware.org/?probe=28631c09aa) | Apr 22, 2023 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [2727f5c463](https://linux-hardware.org/?probe=2727f5c463) | Apr 21, 2023 |
| Micro Elec... | MG-VCP2-17A3070T            | Notebook    | [edf0d6d941](https://linux-hardware.org/?probe=edf0d6d941) | Apr 21, 2023 |
| Apple         | MacBookPro8,3               | Notebook    | [4004491274](https://linux-hardware.org/?probe=4004491274) | Apr 21, 2023 |
| Fujitsu       | LIFEBOOK A557               | Notebook    | [712657fa81](https://linux-hardware.org/?probe=712657fa81) | Apr 20, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [47831c9091](https://linux-hardware.org/?probe=47831c9091) | Apr 18, 2023 |
| Gigabyte      | B150M-D3H-CF                | Desktop     | [c248c05349](https://linux-hardware.org/?probe=c248c05349) | Apr 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14ABR8 82X... | Convertible | [28d52a565b](https://linux-hardware.org/?probe=28d52a565b) | Apr 18, 2023 |
| MSI           | Z87M GAMING                 | Desktop     | [9552ef2174](https://linux-hardware.org/?probe=9552ef2174) | Apr 17, 2023 |
| HP            | 18E7                        | Desktop     | [ef0b00cf80](https://linux-hardware.org/?probe=ef0b00cf80) | Apr 17, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [d40208e7f6](https://linux-hardware.org/?probe=d40208e7f6) | Apr 17, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [7371569bbf](https://linux-hardware.org/?probe=7371569bbf) | Apr 15, 2023 |
| Supermicro    | X10SAE                      | Server      | [4b0cfec9a7](https://linux-hardware.org/?probe=4b0cfec9a7) | Apr 15, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [d1084f0d90](https://linux-hardware.org/?probe=d1084f0d90) | Apr 15, 2023 |
| ASUSTek       | A68HM-K                     | Desktop     | [6419c7fb77](https://linux-hardware.org/?probe=6419c7fb77) | Apr 15, 2023 |
| Protectli     | FW6 Ver                     | Desktop     | [26db4eab1f](https://linux-hardware.org/?probe=26db4eab1f) | Apr 15, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [d49b1775be](https://linux-hardware.org/?probe=d49b1775be) | Apr 14, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [1c8d776510](https://linux-hardware.org/?probe=1c8d776510) | Apr 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [2f29d1d7b8](https://linux-hardware.org/?probe=2f29d1d7b8) | Apr 13, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [06e6f2f745](https://linux-hardware.org/?probe=06e6f2f745) | Apr 13, 2023 |
| Microsoft     | Surface Pro 7               | Tablet      | [222d699e31](https://linux-hardware.org/?probe=222d699e31) | Apr 13, 2023 |
| Dell          | Vostro 7590                 | Notebook    | [f759d8ab72](https://linux-hardware.org/?probe=f759d8ab72) | Apr 13, 2023 |
| Dell          | 0KWVT8 A00                  | Desktop     | [4cea64e81b](https://linux-hardware.org/?probe=4cea64e81b) | Apr 13, 2023 |
| GEO           | GeoBook 120                 | Notebook    | [2e51a1bab5](https://linux-hardware.org/?probe=2e51a1bab5) | Apr 12, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [406c02acb0](https://linux-hardware.org/?probe=406c02acb0) | Apr 12, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [7b4e6e07cf](https://linux-hardware.org/?probe=7b4e6e07cf) | Apr 12, 2023 |
| Unknown       | ACB20                       | Notebook    | [16543ac693](https://linux-hardware.org/?probe=16543ac693) | Apr 12, 2023 |
| Unknown       | ACB20                       | Notebook    | [4c0422096b](https://linux-hardware.org/?probe=4c0422096b) | Apr 12, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8abf9b082b](https://linux-hardware.org/?probe=8abf9b082b) | Apr 12, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [3e3a141713](https://linux-hardware.org/?probe=3e3a141713) | Apr 11, 2023 |
| HP            | 805F                        | Desktop     | [07bd1b4df7](https://linux-hardware.org/?probe=07bd1b4df7) | Apr 11, 2023 |
| HP            | 805F                        | Desktop     | [7863ff02eb](https://linux-hardware.org/?probe=7863ff02eb) | Apr 11, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [eb03b75c27](https://linux-hardware.org/?probe=eb03b75c27) | Apr 11, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [b35b8e1503](https://linux-hardware.org/?probe=b35b8e1503) | Apr 09, 2023 |
| Gigabyte      | G1.Sniper B5-CF             | Desktop     | [e0913458ee](https://linux-hardware.org/?probe=e0913458ee) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [5a044a37f7](https://linux-hardware.org/?probe=5a044a37f7) | Apr 07, 2023 |
| Gigabyte      | B650 AORUS PRO AX           | Desktop     | [81a8d7a1fc](https://linux-hardware.org/?probe=81a8d7a1fc) | Apr 07, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [c599e701fc](https://linux-hardware.org/?probe=c599e701fc) | Apr 06, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7aec6da94d](https://linux-hardware.org/?probe=7aec6da94d) | Apr 05, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [aa3b0a7d6f](https://linux-hardware.org/?probe=aa3b0a7d6f) | Apr 04, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [731bd99503](https://linux-hardware.org/?probe=731bd99503) | Apr 03, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [e97e71fc7a](https://linux-hardware.org/?probe=e97e71fc7a) | Apr 02, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [f96e01d74d](https://linux-hardware.org/?probe=f96e01d74d) | Apr 01, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [539137fb36](https://linux-hardware.org/?probe=539137fb36) | Apr 01, 2023 |
| Unknown       | ACB20                       | Notebook    | [6e70bacda5](https://linux-hardware.org/?probe=6e70bacda5) | Apr 01, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [4434a1266b](https://linux-hardware.org/?probe=4434a1266b) | Mar 31, 2023 |
| ASUSTek       | B85M-G R2.0                 | Desktop     | [fbef2fe274](https://linux-hardware.org/?probe=fbef2fe274) | Mar 31, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [d79127e48c](https://linux-hardware.org/?probe=d79127e48c) | Mar 31, 2023 |
| Intel         | X79                         | Desktop     | [c06125262b](https://linux-hardware.org/?probe=c06125262b) | Mar 31, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [f0540604bc](https://linux-hardware.org/?probe=f0540604bc) | Mar 30, 2023 |
| MSI           | MPG B550I GAMING EDGE WI... | Desktop     | [1c575e8cb6](https://linux-hardware.org/?probe=1c575e8cb6) | Mar 30, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [e4d56ca8c8](https://linux-hardware.org/?probe=e4d56ca8c8) | Mar 28, 2023 |
| ASUSTek       | M3N78 PRO                   | Desktop     | [0f9abe9400](https://linux-hardware.org/?probe=0f9abe9400) | Mar 28, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [5242d56a0f](https://linux-hardware.org/?probe=5242d56a0f) | Mar 27, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [ebb59fa31d](https://linux-hardware.org/?probe=ebb59fa31d) | Mar 27, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [b084807397](https://linux-hardware.org/?probe=b084807397) | Mar 26, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [bc38c5ed22](https://linux-hardware.org/?probe=bc38c5ed22) | Mar 26, 2023 |
| Gigabyte      | AERO 15 XD                  | Notebook    | [51fd5b8510](https://linux-hardware.org/?probe=51fd5b8510) | Mar 25, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [6601de8aae](https://linux-hardware.org/?probe=6601de8aae) | Mar 25, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [8e1cd2ea46](https://linux-hardware.org/?probe=8e1cd2ea46) | Mar 24, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [9240540b33](https://linux-hardware.org/?probe=9240540b33) | Mar 24, 2023 |
| Gigabyte      | GA-970A-DS3                 | Desktop     | [82a69c4ec6](https://linux-hardware.org/?probe=82a69c4ec6) | Mar 23, 2023 |
| Intel         | powered classmate PC        | Notebook    | [0d64280b6d](https://linux-hardware.org/?probe=0d64280b6d) | Mar 22, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [95687a223c](https://linux-hardware.org/?probe=95687a223c) | Mar 22, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [70a7fd895e](https://linux-hardware.org/?probe=70a7fd895e) | Mar 22, 2023 |
| Lenovo        | Unknown                     | Notebook    | [121f022799](https://linux-hardware.org/?probe=121f022799) | Mar 21, 2023 |
| Acer          | Extensa 2510G               | Notebook    | [1ac79f58a4](https://linux-hardware.org/?probe=1ac79f58a4) | Mar 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [0912041935](https://linux-hardware.org/?probe=0912041935) | Mar 21, 2023 |
| Lenovo        | IP 5-14ALC05 82LM           | Notebook    | [5bacaa401a](https://linux-hardware.org/?probe=5bacaa401a) | Mar 21, 2023 |
| Dell          | 0XR1GT A00                  | Desktop     | [61e1c5eff9](https://linux-hardware.org/?probe=61e1c5eff9) | Mar 21, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [ca34d8e7d4](https://linux-hardware.org/?probe=ca34d8e7d4) | Mar 20, 2023 |
| Acidanther... | Mac-7BA5B2D9E42DDD94 iMa... | All in one  | [eba8868f8b](https://linux-hardware.org/?probe=eba8868f8b) | Mar 20, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [7891e82ac4](https://linux-hardware.org/?probe=7891e82ac4) | Mar 17, 2023 |
| Acer          | Nitro AN515-52              | Notebook    | [6ad4034797](https://linux-hardware.org/?probe=6ad4034797) | Mar 17, 2023 |
| Lenovo        | IdeaPad Gaming 3 15IHU6 ... | Notebook    | [7e6ae6ba16](https://linux-hardware.org/?probe=7e6ae6ba16) | Mar 17, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [2530e262d2](https://linux-hardware.org/?probe=2530e262d2) | Mar 17, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [8c4023bd5d](https://linux-hardware.org/?probe=8c4023bd5d) | Mar 16, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [ab9d7b857f](https://linux-hardware.org/?probe=ab9d7b857f) | Mar 16, 2023 |
| Lenovo        | 30FD SDK0J40697 WIN 3305... | Mini pc     | [7659c07b7c](https://linux-hardware.org/?probe=7659c07b7c) | Mar 16, 2023 |
| ASUSTek       | X580VD                      | Notebook    | [26b62abfc9](https://linux-hardware.org/?probe=26b62abfc9) | Mar 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [ab4a88037a](https://linux-hardware.org/?probe=ab4a88037a) | Mar 16, 2023 |
| ASUSTek       | ROG STRIX B650E-E GAMING... | Desktop     | [37bf97e9b3](https://linux-hardware.org/?probe=37bf97e9b3) | Mar 16, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [23e21d1440](https://linux-hardware.org/?probe=23e21d1440) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [34ad3eb730](https://linux-hardware.org/?probe=34ad3eb730) | Mar 15, 2023 |
| Gigabyte      | Z77P-D3                     | Desktop     | [06c53ecdec](https://linux-hardware.org/?probe=06c53ecdec) | Mar 15, 2023 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [7637d41bf3](https://linux-hardware.org/?probe=7637d41bf3) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [e17dae3447](https://linux-hardware.org/?probe=e17dae3447) | Mar 14, 2023 |
| Intel         | DB85FL AAG89861-203         | Desktop     | [f1004a32e1](https://linux-hardware.org/?probe=f1004a32e1) | Mar 14, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [727390b14d](https://linux-hardware.org/?probe=727390b14d) | Mar 14, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [0eefdece9c](https://linux-hardware.org/?probe=0eefdece9c) | Mar 13, 2023 |
| Gigabyte      | Z390 AORUS ULTRA-CF         | Desktop     | [7320131972](https://linux-hardware.org/?probe=7320131972) | Mar 13, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [01bfc3e026](https://linux-hardware.org/?probe=01bfc3e026) | Mar 13, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [e41f3ed4ab](https://linux-hardware.org/?probe=e41f3ed4ab) | Mar 13, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [1ad75bea9c](https://linux-hardware.org/?probe=1ad75bea9c) | Mar 12, 2023 |
| ASRock        | X670E Steel Legend          | Desktop     | [3ec784f6be](https://linux-hardware.org/?probe=3ec784f6be) | Mar 11, 2023 |
| ONE-NETBOO... | ONEXPLAYER 2 ARP23 Ver.1... | Notebook    | [9b021e4844](https://linux-hardware.org/?probe=9b021e4844) | Mar 11, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [126b4a73a2](https://linux-hardware.org/?probe=126b4a73a2) | Mar 11, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [7ba7da9138](https://linux-hardware.org/?probe=7ba7da9138) | Mar 10, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [46b213149e](https://linux-hardware.org/?probe=46b213149e) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [ed7724b921](https://linux-hardware.org/?probe=ed7724b921) | Mar 10, 2023 |
| Dell          | Vostro 3400                 | Notebook    | [6605d9e257](https://linux-hardware.org/?probe=6605d9e257) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [87eec74772](https://linux-hardware.org/?probe=87eec74772) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [38599c9b97](https://linux-hardware.org/?probe=38599c9b97) | Mar 10, 2023 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [0c14a418fb](https://linux-hardware.org/?probe=0c14a418fb) | Mar 10, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [aa31db4d3f](https://linux-hardware.org/?probe=aa31db4d3f) | Mar 09, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [796b1ad7cb](https://linux-hardware.org/?probe=796b1ad7cb) | Mar 09, 2023 |
| ASUSTek       | ROG STRIX X470-F GAMING     | Desktop     | [3629efc5a5](https://linux-hardware.org/?probe=3629efc5a5) | Mar 08, 2023 |
| HP            | ZBook 17                    | Notebook    | [e3fb994c04](https://linux-hardware.org/?probe=e3fb994c04) | Mar 08, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [15cd198548](https://linux-hardware.org/?probe=15cd198548) | Mar 07, 2023 |
| Dell          | 0773VG A01                  | Desktop     | [d954bdd915](https://linux-hardware.org/?probe=d954bdd915) | Mar 07, 2023 |
| ASRock        | H310M-HDV                   | Desktop     | [316510fe69](https://linux-hardware.org/?probe=316510fe69) | Mar 07, 2023 |
| Acer          | Aspire X1400                | Desktop     | [195337bbc6](https://linux-hardware.org/?probe=195337bbc6) | Mar 07, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ebf75e7be8](https://linux-hardware.org/?probe=ebf75e7be8) | Mar 06, 2023 |
| Acer          | Aspire A515-51              | Notebook    | [ef186545cb](https://linux-hardware.org/?probe=ef186545cb) | Mar 06, 2023 |
| ASUSTek       | PRIME B560M-A AC            | Desktop     | [21db48a23b](https://linux-hardware.org/?probe=21db48a23b) | Mar 06, 2023 |
| HP            | ZBook 17 G2                 | Notebook    | [6efd61c4e0](https://linux-hardware.org/?probe=6efd61c4e0) | Mar 05, 2023 |
| Dell          | Latitude 7390               | Notebook    | [892100e074](https://linux-hardware.org/?probe=892100e074) | Mar 05, 2023 |
| Acer          | Aspire VX5-591G             | Notebook    | [e5e134cc80](https://linux-hardware.org/?probe=e5e134cc80) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [4eb7bea837](https://linux-hardware.org/?probe=4eb7bea837) | Mar 04, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [1d24df340b](https://linux-hardware.org/?probe=1d24df340b) | Mar 04, 2023 |
| Apple         | Mac-F4238CC8 PVT            | All in one  | [82994d7312](https://linux-hardware.org/?probe=82994d7312) | Mar 04, 2023 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [582bc638e0](https://linux-hardware.org/?probe=582bc638e0) | Mar 03, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [25d1509478](https://linux-hardware.org/?probe=25d1509478) | Mar 03, 2023 |
| MSI           | GP65 Leopard 9SF            | Notebook    | [45f56a0c5b](https://linux-hardware.org/?probe=45f56a0c5b) | Mar 03, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [950e36afc7](https://linux-hardware.org/?probe=950e36afc7) | Mar 03, 2023 |
| Schenker      | XMG NEO (M19, RTX 2070)     | Notebook    | [c45dbeb188](https://linux-hardware.org/?probe=c45dbeb188) | Mar 02, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [ea8be773a9](https://linux-hardware.org/?probe=ea8be773a9) | Mar 01, 2023 |
| MSI           | P65 Creator 8RD             | Notebook    | [2b97507181](https://linux-hardware.org/?probe=2b97507181) | Mar 01, 2023 |
| ASUSTek       | GL752VW                     | Notebook    | [a3e7201f2e](https://linux-hardware.org/?probe=a3e7201f2e) | Mar 01, 2023 |
| Dell          | Inspiron 3542               | Notebook    | [686db926da](https://linux-hardware.org/?probe=686db926da) | Mar 01, 2023 |
| MSI           | Summit E14Evo A12M          | Notebook    | [ad389112d3](https://linux-hardware.org/?probe=ad389112d3) | Mar 01, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [d0813971b9](https://linux-hardware.org/?probe=d0813971b9) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [c2e600e445](https://linux-hardware.org/?probe=c2e600e445) | Feb 28, 2023 |
| Lenovo        | IdeaPad 330-15ICH 81FK      | Notebook    | [08f2d1cca5](https://linux-hardware.org/?probe=08f2d1cca5) | Feb 28, 2023 |
| ASRock        | B660M-ITX/ac                | Desktop     | [1efc15e2cc](https://linux-hardware.org/?probe=1efc15e2cc) | Feb 28, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [9c49a1748b](https://linux-hardware.org/?probe=9c49a1748b) | Feb 28, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [15318beac5](https://linux-hardware.org/?probe=15318beac5) | Feb 27, 2023 |
| MSI           | Z170A-G45 GAMING            | Desktop     | [a5496030e7](https://linux-hardware.org/?probe=a5496030e7) | Feb 27, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E EXTR... | Desktop     | [659ff1672e](https://linux-hardware.org/?probe=659ff1672e) | Feb 26, 2023 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [92f1f7d3b5](https://linux-hardware.org/?probe=92f1f7d3b5) | Feb 26, 2023 |
| Lenovo        | IdeaPad 5 15ITL05 82FG      | Notebook    | [5d17500c5d](https://linux-hardware.org/?probe=5d17500c5d) | Feb 25, 2023 |
| MSI           | GF63 Thin 10SC              | Notebook    | [824f4eafd0](https://linux-hardware.org/?probe=824f4eafd0) | Feb 25, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING ... | Desktop     | [101d8d4577](https://linux-hardware.org/?probe=101d8d4577) | Feb 25, 2023 |
| Gigabyte      | AERO 15 Classic-SA          | Notebook    | [bc6078dda0](https://linux-hardware.org/?probe=bc6078dda0) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [92879d708d](https://linux-hardware.org/?probe=92879d708d) | Feb 24, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [8a698df80f](https://linux-hardware.org/?probe=8a698df80f) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [012415eb50](https://linux-hardware.org/?probe=012415eb50) | Feb 24, 2023 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [e1c3e1611f](https://linux-hardware.org/?probe=e1c3e1611f) | Feb 24, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [802ba906a0](https://linux-hardware.org/?probe=802ba906a0) | Feb 23, 2023 |
| Sony          | SVF1521N6EW                 | Notebook    | [41e45075c4](https://linux-hardware.org/?probe=41e45075c4) | Feb 22, 2023 |
| ASUSTek       | H97M-E                      | Desktop     | [b2ef9d5ede](https://linux-hardware.org/?probe=b2ef9d5ede) | Feb 21, 2023 |
| MSI           | B450 GAMING PRO CARBON M... | Desktop     | [fb4420dbc4](https://linux-hardware.org/?probe=fb4420dbc4) | Feb 20, 2023 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [737c043ed7](https://linux-hardware.org/?probe=737c043ed7) | Feb 20, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [2752a9660a](https://linux-hardware.org/?probe=2752a9660a) | Feb 19, 2023 |
| Dell          | G3 3590                     | Notebook    | [1a4fd9ed07](https://linux-hardware.org/?probe=1a4fd9ed07) | Feb 18, 2023 |
| MSI           | PRO B660M-A WIFI DDR4       | Desktop     | [a62c4f0fcd](https://linux-hardware.org/?probe=a62c4f0fcd) | Feb 18, 2023 |
| HP            | ENVY 15                     | Notebook    | [bcdc62a706](https://linux-hardware.org/?probe=bcdc62a706) | Feb 18, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [e81d0741bb](https://linux-hardware.org/?probe=e81d0741bb) | Feb 17, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [dd63e968bd](https://linux-hardware.org/?probe=dd63e968bd) | Feb 17, 2023 |
| HP            | EliteBook Revolve 810 G1    | Notebook    | [a32189e068](https://linux-hardware.org/?probe=a32189e068) | Feb 16, 2023 |
| ASUSTek       | PRIME B450M-A II            | Desktop     | [e486b2bb46](https://linux-hardware.org/?probe=e486b2bb46) | Feb 15, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [486f7258a6](https://linux-hardware.org/?probe=486f7258a6) | Feb 14, 2023 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [dc91c0e32b](https://linux-hardware.org/?probe=dc91c0e32b) | Feb 14, 2023 |
| Dell          | 0KWVT8 A02                  | Desktop     | [c3d08b4f2e](https://linux-hardware.org/?probe=c3d08b4f2e) | Feb 13, 2023 |
| Dell          | Inspiron 5555               | Notebook    | [395077145c](https://linux-hardware.org/?probe=395077145c) | Feb 13, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [a54bcd6d70](https://linux-hardware.org/?probe=a54bcd6d70) | Feb 13, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [b25d844a19](https://linux-hardware.org/?probe=b25d844a19) | Feb 12, 2023 |
| ASRock        | B650M PG Riptide            | Desktop     | [bf986cc448](https://linux-hardware.org/?probe=bf986cc448) | Feb 12, 2023 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [28e98cf31f](https://linux-hardware.org/?probe=28e98cf31f) | Feb 12, 2023 |
| HP            | 17E2                        | Mini pc     | [e99d3c0a69](https://linux-hardware.org/?probe=e99d3c0a69) | Feb 12, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [74d6af0f75](https://linux-hardware.org/?probe=74d6af0f75) | Feb 11, 2023 |
| HP            | 17E2                        | Mini pc     | [ff80271dce](https://linux-hardware.org/?probe=ff80271dce) | Feb 11, 2023 |
| HP            | EliteBook x360 1030 G2      | Convertible | [9b95bc446b](https://linux-hardware.org/?probe=9b95bc446b) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G512LI_G512LI     | Notebook    | [6c8760114a](https://linux-hardware.org/?probe=6c8760114a) | Feb 11, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [c4eb0b2a62](https://linux-hardware.org/?probe=c4eb0b2a62) | Feb 11, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [caca2e6be1](https://linux-hardware.org/?probe=caca2e6be1) | Feb 11, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [9de8235ca5](https://linux-hardware.org/?probe=9de8235ca5) | Feb 10, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [afefa761d5](https://linux-hardware.org/?probe=afefa761d5) | Feb 09, 2023 |
| MSI           | B450M BAZOOKA MAX WIFI      | Desktop     | [fdaab67fe9](https://linux-hardware.org/?probe=fdaab67fe9) | Feb 09, 2023 |
| Acer          | TravelMate P256-M           | Notebook    | [add8ce8459](https://linux-hardware.org/?probe=add8ce8459) | Feb 06, 2023 |
| ASUSTek       | M5A78L-M PLUS/USB3          | Desktop     | [eece150870](https://linux-hardware.org/?probe=eece150870) | Feb 05, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [464b35f82b](https://linux-hardware.org/?probe=464b35f82b) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [20086250d5](https://linux-hardware.org/?probe=20086250d5) | Feb 05, 2023 |
| ASUSTek       | TUF Gaming B460-PLUS        | Desktop     | [9905642762](https://linux-hardware.org/?probe=9905642762) | Feb 05, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20S4... | Notebook    | [4ff2fc81bc](https://linux-hardware.org/?probe=4ff2fc81bc) | Feb 04, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [cbac9c37ba](https://linux-hardware.org/?probe=cbac9c37ba) | Feb 04, 2023 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [0b1fbca173](https://linux-hardware.org/?probe=0b1fbca173) | Feb 03, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [8ae0d42e1a](https://linux-hardware.org/?probe=8ae0d42e1a) | Feb 03, 2023 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [513dd8e40b](https://linux-hardware.org/?probe=513dd8e40b) | Feb 03, 2023 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [5a7a0cf485](https://linux-hardware.org/?probe=5a7a0cf485) | Feb 03, 2023 |
| Gigabyte      | B360M AORUS Gaming 3-CF     | Desktop     | [7645e16594](https://linux-hardware.org/?probe=7645e16594) | Feb 03, 2023 |
| HP            | 834F                        | Desktop     | [394eb5f9cc](https://linux-hardware.org/?probe=394eb5f9cc) | Feb 02, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [c1862b275d](https://linux-hardware.org/?probe=c1862b275d) | Feb 01, 2023 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1aa5d63f0c](https://linux-hardware.org/?probe=1aa5d63f0c) | Feb 01, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7f985597d7](https://linux-hardware.org/?probe=7f985597d7) | Jan 30, 2023 |
| HP            | ZBook 15u G3                | Notebook    | [7a35a6d886](https://linux-hardware.org/?probe=7a35a6d886) | Jan 30, 2023 |
| HP            | 8054                        | Desktop     | [36f5306e37](https://linux-hardware.org/?probe=36f5306e37) | Jan 30, 2023 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [87502e1eb2](https://linux-hardware.org/?probe=87502e1eb2) | Jan 29, 2023 |
| Lenovo        | ThinkPad T460 20FMS79000    | Notebook    | [2b397905e1](https://linux-hardware.org/?probe=2b397905e1) | Jan 29, 2023 |
| Samsung       | R520/R522/R620              | Notebook    | [8c5c4fecfe](https://linux-hardware.org/?probe=8c5c4fecfe) | Jan 28, 2023 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [1605fbe62a](https://linux-hardware.org/?probe=1605fbe62a) | Jan 28, 2023 |
| ASUSTek       | ROG Maximus XI HERO         | Desktop     | [95f5d0904e](https://linux-hardware.org/?probe=95f5d0904e) | Jan 26, 2023 |
| Notebook      | NP5x_NP6x_NP7xHP            | Notebook    | [3b7c64dc34](https://linux-hardware.org/?probe=3b7c64dc34) | Jan 26, 2023 |
| Monster       | ABRA A7 V12.1               | Notebook    | [1882db09fe](https://linux-hardware.org/?probe=1882db09fe) | Jan 25, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [c69db4d96f](https://linux-hardware.org/?probe=c69db4d96f) | Jan 24, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [5a5a26c29e](https://linux-hardware.org/?probe=5a5a26c29e) | Jan 24, 2023 |
| Positivo      | N1240                       | Notebook    | [e938a6c0b0](https://linux-hardware.org/?probe=e938a6c0b0) | Jan 24, 2023 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [8cb10f3212](https://linux-hardware.org/?probe=8cb10f3212) | Jan 23, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bc070879ba](https://linux-hardware.org/?probe=bc070879ba) | Jan 22, 2023 |
| MSI           | B450 GAMING PLUS            | Desktop     | [bc95b86800](https://linux-hardware.org/?probe=bc95b86800) | Jan 22, 2023 |
| Gigabyte      | Z77-D3H                     | Desktop     | [9035a00600](https://linux-hardware.org/?probe=9035a00600) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [3eb7e4f3cf](https://linux-hardware.org/?probe=3eb7e4f3cf) | Jan 22, 2023 |
| Medion        | GUARDIAN X10                | Notebook    | [4807ed03d5](https://linux-hardware.org/?probe=4807ed03d5) | Jan 22, 2023 |
| MSI           | MPG Z390M GAMING EDGE AC    | Desktop     | [085d30a350](https://linux-hardware.org/?probe=085d30a350) | Jan 21, 2023 |
| MSI           | Z490-A PRO                  | Desktop     | [0a3fe4cb00](https://linux-hardware.org/?probe=0a3fe4cb00) | Jan 21, 2023 |
| Apple         | MacBook5,1                  | Notebook    | [9732bb65cd](https://linux-hardware.org/?probe=9732bb65cd) | Jan 20, 2023 |
| ASUSTek       | ROG Strix G713RM_G713RM     | Notebook    | [844d97dd92](https://linux-hardware.org/?probe=844d97dd92) | Jan 20, 2023 |
| ASUSTek       | ROG STRIX Z490-F GAMING     | Desktop     | [9a70fa222c](https://linux-hardware.org/?probe=9a70fa222c) | Jan 19, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [87f11d2b18](https://linux-hardware.org/?probe=87f11d2b18) | Jan 19, 2023 |
| Gigabyte      | B450 AORUS M                | Desktop     | [4d52b408c2](https://linux-hardware.org/?probe=4d52b408c2) | Jan 19, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [9a0b1c62f5](https://linux-hardware.org/?probe=9a0b1c62f5) | Jan 18, 2023 |
| MSI           | GF615M-P33                  | Desktop     | [bf838ee958](https://linux-hardware.org/?probe=bf838ee958) | Jan 18, 2023 |
| Acer          | Swift SFX14-51G             | Notebook    | [f0137b1f08](https://linux-hardware.org/?probe=f0137b1f08) | Jan 17, 2023 |
| ASUSTek       | PRIME Z370-A                | Desktop     | [f215410f54](https://linux-hardware.org/?probe=f215410f54) | Jan 17, 2023 |
| ASUSTek       | Z97-A                       | Desktop     | [c1b01960be](https://linux-hardware.org/?probe=c1b01960be) | Jan 17, 2023 |
| MSI           | Katana GF76 11UD            | Notebook    | [dcc8c2a63b](https://linux-hardware.org/?probe=dcc8c2a63b) | Jan 17, 2023 |
| Lenovo        | Legion 5 17ACH6H 82JY       | Notebook    | [b49ce7a30a](https://linux-hardware.org/?probe=b49ce7a30a) | Jan 15, 2023 |
| Lenovo        | ThinkPad P51 20HJS02H00     | Notebook    | [ab26ff36b1](https://linux-hardware.org/?probe=ab26ff36b1) | Jan 14, 2023 |
| ASRock        | B450 Gaming-ITX/ac          | Desktop     | [aade436557](https://linux-hardware.org/?probe=aade436557) | Jan 14, 2023 |
| ASUSTek       | ROG STRIX B650E-I GAMING... | Desktop     | [5b50555e06](https://linux-hardware.org/?probe=5b50555e06) | Jan 13, 2023 |
| ASUSTek       | P9X79 DELUXE                | Desktop     | [d73373e8e9](https://linux-hardware.org/?probe=d73373e8e9) | Jan 13, 2023 |
| AZW           | S3                          | Mini pc     | [0e94de97c8](https://linux-hardware.org/?probe=0e94de97c8) | Jan 12, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [73da880450](https://linux-hardware.org/?probe=73da880450) | Jan 12, 2023 |
| Medion        | GUARDIAN X10                | Notebook    | [ef011d0700](https://linux-hardware.org/?probe=ef011d0700) | Jan 10, 2023 |
| HP            | Pavilion 15                 | Notebook    | [e60b327d4c](https://linux-hardware.org/?probe=e60b327d4c) | Jan 10, 2023 |
| ASUSTek       | ROG Zephyrus G14 GA402RK... | Notebook    | [899e519abe](https://linux-hardware.org/?probe=899e519abe) | Jan 10, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [9f368d248b](https://linux-hardware.org/?probe=9f368d248b) | Jan 10, 2023 |
| ASUSTek       | ROG Flow X13 GV301QE_GV3... | Notebook    | [d679fb0fd0](https://linux-hardware.org/?probe=d679fb0fd0) | Jan 10, 2023 |
| MSI           | GT680R/GX680R/GT683R/GT6... | Notebook    | [0b23cb61e0](https://linux-hardware.org/?probe=0b23cb61e0) | Jan 09, 2023 |
| HP            | 8054                        | Desktop     | [d4398dee29](https://linux-hardware.org/?probe=d4398dee29) | Jan 08, 2023 |
| MSI           | MAG B560M MORTAR WIFI       | Desktop     | [33f6781ba8](https://linux-hardware.org/?probe=33f6781ba8) | Jan 08, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [c74a6daaaa](https://linux-hardware.org/?probe=c74a6daaaa) | Jan 07, 2023 |
| ASRock        | X470 Master SLI             | Desktop     | [c138f9159c](https://linux-hardware.org/?probe=c138f9159c) | Jan 07, 2023 |
| HP            | 1497                        | Desktop     | [71550a0f21](https://linux-hardware.org/?probe=71550a0f21) | Jan 07, 2023 |
| ASRock        | H77M-ITX                    | Desktop     | [fb6cbfce9a](https://linux-hardware.org/?probe=fb6cbfce9a) | Jan 06, 2023 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [406b407b64](https://linux-hardware.org/?probe=406b407b64) | Jan 06, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [61b7c0cda0](https://linux-hardware.org/?probe=61b7c0cda0) | Jan 06, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [569f5cd751](https://linux-hardware.org/?probe=569f5cd751) | Jan 06, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [3978c4253f](https://linux-hardware.org/?probe=3978c4253f) | Jan 06, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [8c219aafe4](https://linux-hardware.org/?probe=8c219aafe4) | Jan 05, 2023 |
| ASUSTek       | G20AJ                       | Desktop     | [9be7e0b11f](https://linux-hardware.org/?probe=9be7e0b11f) | Jan 05, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [b6bf9d074f](https://linux-hardware.org/?probe=b6bf9d074f) | Jan 05, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [11d17c68b8](https://linux-hardware.org/?probe=11d17c68b8) | Jan 05, 2023 |
| HP            | EliteBook 840 G1            | Notebook    | [6f4cc6e4c7](https://linux-hardware.org/?probe=6f4cc6e4c7) | Jan 05, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [7655f77ada](https://linux-hardware.org/?probe=7655f77ada) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [6c40dc7dd6](https://linux-hardware.org/?probe=6c40dc7dd6) | Jan 03, 2023 |
| ASRock        | X570 Phantom Gaming-ITX/... | Notebook    | [f097aa1c92](https://linux-hardware.org/?probe=f097aa1c92) | Jan 03, 2023 |
| Apple         | MacBookPro8,1               | Notebook    | [97f93aa235](https://linux-hardware.org/?probe=97f93aa235) | Dec 31, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [6d047b6620](https://linux-hardware.org/?probe=6d047b6620) | Dec 30, 2022 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [26e56628ec](https://linux-hardware.org/?probe=26e56628ec) | Dec 30, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [dc7201711c](https://linux-hardware.org/?probe=dc7201711c) | Dec 30, 2022 |
| Lenovo        | 3181 SEK0T35577 IOT 4247... | Mini pc     | [fa1b60ae23](https://linux-hardware.org/?probe=fa1b60ae23) | Dec 29, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [4ca2070d42](https://linux-hardware.org/?probe=4ca2070d42) | Dec 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop N760... | Notebook    | [7ef5d874e9](https://linux-hardware.org/?probe=7ef5d874e9) | Dec 28, 2022 |
| HP            | ENVY Notebook               | Notebook    | [8c7d592182](https://linux-hardware.org/?probe=8c7d592182) | Dec 26, 2022 |
| ASUSTek       | PRIME Z270-P                | Desktop     | [b9e4ff3fea](https://linux-hardware.org/?probe=b9e4ff3fea) | Dec 25, 2022 |
| HP            | 1589                        | Desktop     | [4769414712](https://linux-hardware.org/?probe=4769414712) | Dec 24, 2022 |
| HP            | Pavilion Laptop 14-ec0xx... | Notebook    | [978bb114dc](https://linux-hardware.org/?probe=978bb114dc) | Dec 23, 2022 |
| Dell          | G15 5510                    | Notebook    | [86d0642973](https://linux-hardware.org/?probe=86d0642973) | Dec 20, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [353cbeb5c8](https://linux-hardware.org/?probe=353cbeb5c8) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [03da9468fc](https://linux-hardware.org/?probe=03da9468fc) | Dec 19, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [2a1a679e03](https://linux-hardware.org/?probe=2a1a679e03) | Dec 18, 2022 |
| Apple         | MacBookPro11,1              | Notebook    | [d3517edb25](https://linux-hardware.org/?probe=d3517edb25) | Dec 17, 2022 |
| Acer          | Aspire E5-551G              | Notebook    | [56f5130537](https://linux-hardware.org/?probe=56f5130537) | Dec 17, 2022 |
| Biostar       | X470GTN                     | Desktop     | [7c067277b2](https://linux-hardware.org/?probe=7c067277b2) | Dec 17, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [3bc811ef2a](https://linux-hardware.org/?probe=3bc811ef2a) | Dec 17, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [0a2731119d](https://linux-hardware.org/?probe=0a2731119d) | Dec 16, 2022 |
| HP            | 2ABD A01                    | Desktop     | [c5c5c07485](https://linux-hardware.org/?probe=c5c5c07485) | Dec 16, 2022 |
| HP            | 2ABD A01                    | Desktop     | [c992b15fbe](https://linux-hardware.org/?probe=c992b15fbe) | Dec 16, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [6f9a9428b6](https://linux-hardware.org/?probe=6f9a9428b6) | Dec 16, 2022 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [fc8f4624a4](https://linux-hardware.org/?probe=fc8f4624a4) | Dec 16, 2022 |
| ASRock        | H310M-HDV/M.2               | Desktop     | [76dff63f5c](https://linux-hardware.org/?probe=76dff63f5c) | Dec 15, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [28c00eabe8](https://linux-hardware.org/?probe=28c00eabe8) | Dec 14, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [4378eff64f](https://linux-hardware.org/?probe=4378eff64f) | Dec 13, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [6177c6a156](https://linux-hardware.org/?probe=6177c6a156) | Dec 13, 2022 |
| MSI           | MAG B660 TOMAHAWK WIFI      | Desktop     | [1beb5ff3c4](https://linux-hardware.org/?probe=1beb5ff3c4) | Dec 13, 2022 |
| ASUSTek       | ROG STRIX B660-F GAMING ... | Desktop     | [3f57fa2c71](https://linux-hardware.org/?probe=3f57fa2c71) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [52f0fae7e4](https://linux-hardware.org/?probe=52f0fae7e4) | Dec 12, 2022 |
| HP            | EliteBook 8570p             | Notebook    | [be0c42b073](https://linux-hardware.org/?probe=be0c42b073) | Dec 12, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81DE      | Notebook    | [52a8f66027](https://linux-hardware.org/?probe=52a8f66027) | Dec 10, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [febce6b929](https://linux-hardware.org/?probe=febce6b929) | Dec 09, 2022 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [94b281cfa1](https://linux-hardware.org/?probe=94b281cfa1) | Dec 09, 2022 |
| Gigabyte      | H81M-H                      | Desktop     | [02ba14a443](https://linux-hardware.org/?probe=02ba14a443) | Dec 09, 2022 |
| Dell          | 0215PR A02                  | Desktop     | [b9d16b98d2](https://linux-hardware.org/?probe=b9d16b98d2) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [4fd43d5aff](https://linux-hardware.org/?probe=4fd43d5aff) | Dec 09, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [9cc2be8747](https://linux-hardware.org/?probe=9cc2be8747) | Dec 09, 2022 |
| Acer          | Aspire E1-532               | Notebook    | [13e9fa6c58](https://linux-hardware.org/?probe=13e9fa6c58) | Dec 09, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [af4d483414](https://linux-hardware.org/?probe=af4d483414) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [d7b2726838](https://linux-hardware.org/?probe=d7b2726838) | Dec 08, 2022 |
| Dynabook      | PORTEGE X30L-K              | Notebook    | [75a8aa38fc](https://linux-hardware.org/?probe=75a8aa38fc) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [c9cc6de1c4](https://linux-hardware.org/?probe=c9cc6de1c4) | Dec 08, 2022 |
| ASUSTek       | STRIX Z270H GAMING          | Desktop     | [8973296b3b](https://linux-hardware.org/?probe=8973296b3b) | Dec 08, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [f5bd8a0e5b](https://linux-hardware.org/?probe=f5bd8a0e5b) | Dec 07, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [07bf98d8f7](https://linux-hardware.org/?probe=07bf98d8f7) | Dec 07, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [a742429421](https://linux-hardware.org/?probe=a742429421) | Dec 06, 2022 |
| HP            | Laptop 14-cm1xxx            | Notebook    | [6fbbd3608f](https://linux-hardware.org/?probe=6fbbd3608f) | Dec 06, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [e23dd27dc9](https://linux-hardware.org/?probe=e23dd27dc9) | Dec 06, 2022 |
| ASUSTek       | ROG Zephyrus M15 GU502LV... | Notebook    | [5ce6793478](https://linux-hardware.org/?probe=5ce6793478) | Dec 06, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f2025f3847](https://linux-hardware.org/?probe=f2025f3847) | Dec 04, 2022 |
| ASUSTek       | M5A88-M                     | Desktop     | [69ed3a0345](https://linux-hardware.org/?probe=69ed3a0345) | Dec 02, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [1775ec9d4b](https://linux-hardware.org/?probe=1775ec9d4b) | Dec 01, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [097d1c062e](https://linux-hardware.org/?probe=097d1c062e) | Dec 01, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [655e907d62](https://linux-hardware.org/?probe=655e907d62) | Dec 01, 2022 |
| Intel         | X79G V2.x                   | Desktop     | [6b229554fc](https://linux-hardware.org/?probe=6b229554fc) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [ef85b8ab38](https://linux-hardware.org/?probe=ef85b8ab38) | Nov 28, 2022 |
| Valve         | Jupiter                     | Notebook    | [622315486c](https://linux-hardware.org/?probe=622315486c) | Nov 28, 2022 |
| Lenovo        | V14-IIL 82C4                | Notebook    | [407b574c57](https://linux-hardware.org/?probe=407b574c57) | Nov 28, 2022 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [ae30b95cd8](https://linux-hardware.org/?probe=ae30b95cd8) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [91fa73480c](https://linux-hardware.org/?probe=91fa73480c) | Nov 26, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [93576caa19](https://linux-hardware.org/?probe=93576caa19) | Nov 26, 2022 |
| Lenovo        | ThinkPad T460 20FMS07000    | Notebook    | [eded61b721](https://linux-hardware.org/?probe=eded61b721) | Nov 25, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [be2f8c9fd3](https://linux-hardware.org/?probe=be2f8c9fd3) | Nov 24, 2022 |
| HP            | ProBook 445 14 inch G9 N... | Notebook    | [a20535bd66](https://linux-hardware.org/?probe=a20535bd66) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [9324629428](https://linux-hardware.org/?probe=9324629428) | Nov 24, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Notebook    | [22a1c81a68](https://linux-hardware.org/?probe=22a1c81a68) | Nov 24, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [afea73cc2a](https://linux-hardware.org/?probe=afea73cc2a) | Nov 22, 2022 |
| Coradir       | Coradir/ES10IS5             | Notebook    | [a1fb1953ad](https://linux-hardware.org/?probe=a1fb1953ad) | Nov 22, 2022 |
| Lenovo        | G580 20150                  | Notebook    | [6e28c07a6c](https://linux-hardware.org/?probe=6e28c07a6c) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [56c9fb93ce](https://linux-hardware.org/?probe=56c9fb93ce) | Nov 22, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1ec2520541](https://linux-hardware.org/?probe=1ec2520541) | Nov 22, 2022 |
| ASUSTek       | ROG STRIX X570-F GAMING     | Desktop     | [0fd2d81cad](https://linux-hardware.org/?probe=0fd2d81cad) | Nov 22, 2022 |
| OEM           | SHARKBAY JHS695             | Desktop     | [03c915bbd9](https://linux-hardware.org/?probe=03c915bbd9) | Nov 22, 2022 |
| MSI           | GF615M-P33                  | Desktop     | [7a6be335c4](https://linux-hardware.org/?probe=7a6be335c4) | Nov 22, 2022 |
| ASRock        | B550 Extreme4               | Desktop     | [7fba8e38dc](https://linux-hardware.org/?probe=7fba8e38dc) | Nov 20, 2022 |
| Lenovo        | ThinkPad X240 20AMA0LTAU    | Notebook    | [54ce03d1f1](https://linux-hardware.org/?probe=54ce03d1f1) | Nov 20, 2022 |
| HP            | Unknown                     | Notebook    | [9b1181bc4b](https://linux-hardware.org/?probe=9b1181bc4b) | Nov 19, 2022 |
| Gigabyte      | H310M M.2 x.x               | Desktop     | [87406f0722](https://linux-hardware.org/?probe=87406f0722) | Nov 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [93ad560f52](https://linux-hardware.org/?probe=93ad560f52) | Nov 17, 2022 |
| Alienware     | 0PGRP5 A01                  | Desktop     | [2ff9360669](https://linux-hardware.org/?probe=2ff9360669) | Nov 17, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [750d7eb0d7](https://linux-hardware.org/?probe=750d7eb0d7) | Nov 16, 2022 |
| Dell          | Studio 1737                 | Notebook    | [883ac54ca7](https://linux-hardware.org/?probe=883ac54ca7) | Nov 15, 2022 |
| ZOTAC         | ZBOX-CI320NANO series Re... | Mini pc     | [ab1c46c857](https://linux-hardware.org/?probe=ab1c46c857) | Nov 15, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [3ee89779cd](https://linux-hardware.org/?probe=3ee89779cd) | Nov 15, 2022 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [4d4d5aa456](https://linux-hardware.org/?probe=4d4d5aa456) | Nov 15, 2022 |
| Lenovo        | G50-30 80G0                 | Notebook    | [978fdef2f8](https://linux-hardware.org/?probe=978fdef2f8) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [b33f7744b5](https://linux-hardware.org/?probe=b33f7744b5) | Nov 13, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [9d7853c05b](https://linux-hardware.org/?probe=9d7853c05b) | Nov 13, 2022 |
| Fujitsu       | D3062-A1 S26361-D3062-A1    | Desktop     | [d4240ae5c7](https://linux-hardware.org/?probe=d4240ae5c7) | Nov 12, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [a8023a34a0](https://linux-hardware.org/?probe=a8023a34a0) | Nov 11, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [51d6598b74](https://linux-hardware.org/?probe=51d6598b74) | Nov 11, 2022 |
| ASUSTek       | A68HM-K                     | Desktop     | [70daf967f2](https://linux-hardware.org/?probe=70daf967f2) | Nov 10, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [a49a1465d3](https://linux-hardware.org/?probe=a49a1465d3) | Nov 10, 2022 |
| HP            | OMEN Laptop 15-ek0xxx       | Notebook    | [3d53644c05](https://linux-hardware.org/?probe=3d53644c05) | Nov 08, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [c6460ff904](https://linux-hardware.org/?probe=c6460ff904) | Nov 07, 2022 |
| Dell          | Studio 1737                 | Notebook    | [d286ea1b6c](https://linux-hardware.org/?probe=d286ea1b6c) | Nov 07, 2022 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [5e151ea22f](https://linux-hardware.org/?probe=5e151ea22f) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [f90e6e931c](https://linux-hardware.org/?probe=f90e6e931c) | Nov 07, 2022 |
| Intel         | D33217GKE G76540-207        | Desktop     | [a154fd19a0](https://linux-hardware.org/?probe=a154fd19a0) | Nov 07, 2022 |
| ASUSTek       | TUF Gaming Z490-PLUS        | Desktop     | [4239b9f4a9](https://linux-hardware.org/?probe=4239b9f4a9) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [05529fe361](https://linux-hardware.org/?probe=05529fe361) | Nov 06, 2022 |
| Dell          | 042P49 A02                  | Desktop     | [55d7ddf0c8](https://linux-hardware.org/?probe=55d7ddf0c8) | Nov 06, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [677dcff84a](https://linux-hardware.org/?probe=677dcff84a) | Nov 06, 2022 |
| MSI           | MPG X570S EDGE MAX WIFI     | Desktop     | [049bac8501](https://linux-hardware.org/?probe=049bac8501) | Nov 06, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [5ca257fd77](https://linux-hardware.org/?probe=5ca257fd77) | Nov 06, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [bd9e0be4e8](https://linux-hardware.org/?probe=bd9e0be4e8) | Nov 03, 2022 |
| ASUSTek       | GL753VD                     | Notebook    | [97e2ee4ee1](https://linux-hardware.org/?probe=97e2ee4ee1) | Nov 01, 2022 |
| HP            | Unknown                     | Notebook    | [1ca885060e](https://linux-hardware.org/?probe=1ca885060e) | Nov 01, 2022 |
| ECS           | H61H2-CM                    | Desktop     | [792ce0e34e](https://linux-hardware.org/?probe=792ce0e34e) | Oct 31, 2022 |
| Acer          | Nitro AN515-42              | Notebook    | [3a00ca53c8](https://linux-hardware.org/?probe=3a00ca53c8) | Oct 31, 2022 |
| Lenovo        | IdeaPad C340-14API 81N6     | Notebook    | [d322bb2739](https://linux-hardware.org/?probe=d322bb2739) | Oct 30, 2022 |
| Apple         | MacBookPro13,3              | Notebook    | [b028075707](https://linux-hardware.org/?probe=b028075707) | Oct 30, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop X50... | Notebook    | [4fdbc3c415](https://linux-hardware.org/?probe=4fdbc3c415) | Oct 30, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [5ab5790e5f](https://linux-hardware.org/?probe=5ab5790e5f) | Oct 29, 2022 |
| ASRock        | Z77 Pro4                    | Desktop     | [74cc7f147b](https://linux-hardware.org/?probe=74cc7f147b) | Oct 29, 2022 |
| HP            | 8653 A                      | Desktop     | [bc1f3b445b](https://linux-hardware.org/?probe=bc1f3b445b) | Oct 28, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [967f52e510](https://linux-hardware.org/?probe=967f52e510) | Oct 28, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [50a8c356f0](https://linux-hardware.org/?probe=50a8c356f0) | Oct 28, 2022 |
| Dell          | 09KPNV A00                  | Desktop     | [c25493f420](https://linux-hardware.org/?probe=c25493f420) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [7e31b6af67](https://linux-hardware.org/?probe=7e31b6af67) | Oct 27, 2022 |
| Gigabyte      | 970A-DS3P                   | Desktop     | [6823943242](https://linux-hardware.org/?probe=6823943242) | Oct 27, 2022 |
| Intel         | B75                         | Desktop     | [eb7c27f1e5](https://linux-hardware.org/?probe=eb7c27f1e5) | Oct 26, 2022 |
| HP            | 3029h                       | Desktop     | [c278953154](https://linux-hardware.org/?probe=c278953154) | Oct 25, 2022 |
| ASUSTek       | GL502VMK                    | Notebook    | [9a18ff1b13](https://linux-hardware.org/?probe=9a18ff1b13) | Oct 25, 2022 |
| Gigabyte      | Z590I VISION D              | Desktop     | [be4c6573cd](https://linux-hardware.org/?probe=be4c6573cd) | Oct 25, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [c0b3f0d88e](https://linux-hardware.org/?probe=c0b3f0d88e) | Oct 24, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [8bfeff52e6](https://linux-hardware.org/?probe=8bfeff52e6) | Oct 24, 2022 |
| ASUSTek       | S550CB                      | Notebook    | [a81f0ecac8](https://linux-hardware.org/?probe=a81f0ecac8) | Oct 24, 2022 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [7e40be1c82](https://linux-hardware.org/?probe=7e40be1c82) | Oct 23, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [3912d818bd](https://linux-hardware.org/?probe=3912d818bd) | Oct 23, 2022 |
| HP            | OMEN Notebook PC 15         | Notebook    | [1d5ebc92c4](https://linux-hardware.org/?probe=1d5ebc92c4) | Oct 23, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [f79eb0cbb0](https://linux-hardware.org/?probe=f79eb0cbb0) | Oct 23, 2022 |
| ASUSTek       | TUF Gaming X570-PRO WIFI... | Desktop     | [c3b1784ecc](https://linux-hardware.org/?probe=c3b1784ecc) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [eaecfdf473](https://linux-hardware.org/?probe=eaecfdf473) | Oct 21, 2022 |
| Lenovo        | Legion 5 Pro 16IAH7H 82R... | Notebook    | [c044987599](https://linux-hardware.org/?probe=c044987599) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [b6fd429ceb](https://linux-hardware.org/?probe=b6fd429ceb) | Oct 20, 2022 |
| HP            | EliteBook 850 G2            | Notebook    | [f33baf66a9](https://linux-hardware.org/?probe=f33baf66a9) | Oct 20, 2022 |
| ASUSTek       | TUF Gaming FX504GD_FX80G... | Notebook    | [e5a34da4a2](https://linux-hardware.org/?probe=e5a34da4a2) | Oct 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [c901f6927c](https://linux-hardware.org/?probe=c901f6927c) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [829326a8e5](https://linux-hardware.org/?probe=829326a8e5) | Oct 18, 2022 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [697ccec46b](https://linux-hardware.org/?probe=697ccec46b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [dfeb98414b](https://linux-hardware.org/?probe=dfeb98414b) | Oct 18, 2022 |
| HP            | EliteBook 850 G1            | Notebook    | [7f8c9d778c](https://linux-hardware.org/?probe=7f8c9d778c) | Oct 18, 2022 |
| MSI           | MPG Z390 GAMING PLUS        | Desktop     | [624be3f0f3](https://linux-hardware.org/?probe=624be3f0f3) | Oct 17, 2022 |
| ASUSTek       | TUF Gaming B450M-PLUS II    | Desktop     | [cb63aa5619](https://linux-hardware.org/?probe=cb63aa5619) | Oct 17, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a4919afa07](https://linux-hardware.org/?probe=a4919afa07) | Oct 16, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [7961a3ca3e](https://linux-hardware.org/?probe=7961a3ca3e) | Oct 14, 2022 |
| MSI           | Z87 XPOWER                  | Desktop     | [5e73f5004a](https://linux-hardware.org/?probe=5e73f5004a) | Oct 13, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [0a89e9b77e](https://linux-hardware.org/?probe=0a89e9b77e) | Oct 13, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [5f013faf39](https://linux-hardware.org/?probe=5f013faf39) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [89f43e5484](https://linux-hardware.org/?probe=89f43e5484) | Oct 12, 2022 |
| Toshiba       | Satellite L650              | Notebook    | [43f57daebb](https://linux-hardware.org/?probe=43f57daebb) | Oct 12, 2022 |
| MSI           | Pulse GL76 12UEK            | Notebook    | [6a2be4d08c](https://linux-hardware.org/?probe=6a2be4d08c) | Oct 12, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [f8895e9483](https://linux-hardware.org/?probe=f8895e9483) | Oct 11, 2022 |
| MSI           | MPG Z390 GAMING PRO CARB... | Desktop     | [a920c57a3e](https://linux-hardware.org/?probe=a920c57a3e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [2aa595867e](https://linux-hardware.org/?probe=2aa595867e) | Oct 11, 2022 |
| Dell          | Vostro 15 5510              | Notebook    | [bd224480a9](https://linux-hardware.org/?probe=bd224480a9) | Oct 10, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [49baafbc65](https://linux-hardware.org/?probe=49baafbc65) | Oct 10, 2022 |
| HP            | 2000                        | Notebook    | [3341a26d0c](https://linux-hardware.org/?probe=3341a26d0c) | Oct 10, 2022 |
| ASUSTek       | GL503VD                     | Notebook    | [1405b367c2](https://linux-hardware.org/?probe=1405b367c2) | Oct 09, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [94ccd99c78](https://linux-hardware.org/?probe=94ccd99c78) | Oct 09, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [2a1088b211](https://linux-hardware.org/?probe=2a1088b211) | Oct 08, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [faef78b510](https://linux-hardware.org/?probe=faef78b510) | Oct 08, 2022 |
| HP            | Laptop 15-dw0xxx            | Notebook    | [3427421197](https://linux-hardware.org/?probe=3427421197) | Oct 08, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [05dfea29df](https://linux-hardware.org/?probe=05dfea29df) | Oct 07, 2022 |
| ASUSTek       | SABERTOOTH 990FX R2.0       | Desktop     | [24471f06da](https://linux-hardware.org/?probe=24471f06da) | Oct 07, 2022 |
| ASUSTek       | ASUS TUF Gaming A17 FA70... | Notebook    | [2d464da9c8](https://linux-hardware.org/?probe=2d464da9c8) | Oct 07, 2022 |
| HP            | ZBook 17 G6                 | Notebook    | [c215e9e17e](https://linux-hardware.org/?probe=c215e9e17e) | Oct 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [db48ac269b](https://linux-hardware.org/?probe=db48ac269b) | Oct 07, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [cc955e89b7](https://linux-hardware.org/?probe=cc955e89b7) | Oct 07, 2022 |
| Lenovo        | IdeaPad 320-15IKB 80YH      | Notebook    | [9ccbc0ed3c](https://linux-hardware.org/?probe=9ccbc0ed3c) | Oct 07, 2022 |
| HP            | 1998                        | Desktop     | [f2b9957fdd](https://linux-hardware.org/?probe=f2b9957fdd) | Oct 06, 2022 |
| KELYX ARGE... | KL9120                      | Notebook    | [faa5f13391](https://linux-hardware.org/?probe=faa5f13391) | Oct 06, 2022 |
| Positivo      | N1250                       | Notebook    | [9845103c14](https://linux-hardware.org/?probe=9845103c14) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [b161553abb](https://linux-hardware.org/?probe=b161553abb) | Oct 05, 2022 |
| ASRock        | B450M Steel Legend          | Desktop     | [4f4352de45](https://linux-hardware.org/?probe=4f4352de45) | Oct 04, 2022 |
| HP            | 2000                        | Notebook    | [e6f8f7196d](https://linux-hardware.org/?probe=e6f8f7196d) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [3ec3f59233](https://linux-hardware.org/?probe=3ec3f59233) | Oct 03, 2022 |
| ASUSTek       | TUF Gaming FX505DV_FX505... | Notebook    | [5ed7136249](https://linux-hardware.org/?probe=5ed7136249) | Oct 03, 2022 |
| HP            | 240 G7 Notebook PC          | Notebook    | [05b4e2117b](https://linux-hardware.org/?probe=05b4e2117b) | Oct 03, 2022 |
| ASUSTek       | H61M-K                      | Desktop     | [e0408b49e7](https://linux-hardware.org/?probe=e0408b49e7) | Oct 02, 2022 |
| MSI           | B350 PC MATE                | Desktop     | [a4c73b484e](https://linux-hardware.org/?probe=a4c73b484e) | Oct 02, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [3cc1e139dc](https://linux-hardware.org/?probe=3cc1e139dc) | Oct 02, 2022 |
| Toshiba       | Satellite L850              | Notebook    | [0e57d064b0](https://linux-hardware.org/?probe=0e57d064b0) | Oct 02, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [05e921b4aa](https://linux-hardware.org/?probe=05e921b4aa) | Oct 02, 2022 |
| EVOO          | EG-LP10                     | Notebook    | [32c1a174d1](https://linux-hardware.org/?probe=32c1a174d1) | Oct 01, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [4d2e449699](https://linux-hardware.org/?probe=4d2e449699) | Sep 30, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [47c190b6e9](https://linux-hardware.org/?probe=47c190b6e9) | Sep 30, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [062910424d](https://linux-hardware.org/?probe=062910424d) | Sep 30, 2022 |
| Acer          | Aspire VX5-591G             | Notebook    | [b321f4561b](https://linux-hardware.org/?probe=b321f4561b) | Sep 29, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [0360123f76](https://linux-hardware.org/?probe=0360123f76) | Sep 29, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [a205e0ea70](https://linux-hardware.org/?probe=a205e0ea70) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [9426d21070](https://linux-hardware.org/?probe=9426d21070) | Sep 29, 2022 |
| Gigabyte      | H270-Gaming 3               | Desktop     | [830af9c53e](https://linux-hardware.org/?probe=830af9c53e) | Sep 29, 2022 |
| Lenovo        | G580 20157                  | Notebook    | [2b34d591ab](https://linux-hardware.org/?probe=2b34d591ab) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [a423006d4c](https://linux-hardware.org/?probe=a423006d4c) | Sep 29, 2022 |
| Apple         | MacBookAir4,2               | Notebook    | [5dba6cf7fd](https://linux-hardware.org/?probe=5dba6cf7fd) | Sep 29, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [365d74f8e4](https://linux-hardware.org/?probe=365d74f8e4) | Sep 28, 2022 |
| Intel         | B75                         | Desktop     | [af5aef869c](https://linux-hardware.org/?probe=af5aef869c) | Sep 28, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [6d35107941](https://linux-hardware.org/?probe=6d35107941) | Sep 28, 2022 |
| Apple         | MacBookPro8,3               | Notebook    | [74927fc7d2](https://linux-hardware.org/?probe=74927fc7d2) | Sep 27, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [cfd24b9e0a](https://linux-hardware.org/?probe=cfd24b9e0a) | Sep 27, 2022 |
| MSI           | MAG X570 TOMAHAWK WIFI      | Desktop     | [6bfc8d43ef](https://linux-hardware.org/?probe=6bfc8d43ef) | Sep 27, 2022 |
| Lenovo        | IdeaPad 310-15IAP 80TT      | Notebook    | [65f896ddab](https://linux-hardware.org/?probe=65f896ddab) | Sep 27, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [d51c90a7a8](https://linux-hardware.org/?probe=d51c90a7a8) | Sep 27, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f61a736922](https://linux-hardware.org/?probe=f61a736922) | Sep 26, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [1ecfe379e7](https://linux-hardware.org/?probe=1ecfe379e7) | Sep 26, 2022 |
| ASUSTek       | PRIME H410M-A               | Desktop     | [dafae8d45b](https://linux-hardware.org/?probe=dafae8d45b) | Sep 26, 2022 |
| Lenovo        | 3136 SDK0J40697 WIN 3305... | Mini pc     | [d31088804f](https://linux-hardware.org/?probe=d31088804f) | Sep 24, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [015cd37f26](https://linux-hardware.org/?probe=015cd37f26) | Sep 24, 2022 |
| Dell          | Latitude 7275               | Tablet      | [49ee35636b](https://linux-hardware.org/?probe=49ee35636b) | Sep 24, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [c461ec42d6](https://linux-hardware.org/?probe=c461ec42d6) | Sep 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d72e6b3865](https://linux-hardware.org/?probe=d72e6b3865) | Sep 23, 2022 |
| Gateway       | NE56R                       | Notebook    | [f603edd045](https://linux-hardware.org/?probe=f603edd045) | Sep 23, 2022 |
| Toshiba       | TECRA A50-A                 | Notebook    | [6ef2538a5a](https://linux-hardware.org/?probe=6ef2538a5a) | Sep 23, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [605e97df5c](https://linux-hardware.org/?probe=605e97df5c) | Sep 22, 2022 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [94e6332c62](https://linux-hardware.org/?probe=94e6332c62) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [2e36489a4b](https://linux-hardware.org/?probe=2e36489a4b) | Sep 22, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [71c630ea03](https://linux-hardware.org/?probe=71c630ea03) | Sep 22, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401II... | Notebook    | [8705683c6f](https://linux-hardware.org/?probe=8705683c6f) | Sep 22, 2022 |
| ASUSTek       | PRIME H310M-E R2.0          | Desktop     | [7299d75966](https://linux-hardware.org/?probe=7299d75966) | Sep 22, 2022 |
| HP            | 8594                        | Desktop     | [281774ad4a](https://linux-hardware.org/?probe=281774ad4a) | Sep 21, 2022 |
| Gigabyte      | EP45-UD3L                   | Desktop     | [2b90168b71](https://linux-hardware.org/?probe=2b90168b71) | Sep 21, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [3c8fefe578](https://linux-hardware.org/?probe=3c8fefe578) | Sep 20, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [1975320cad](https://linux-hardware.org/?probe=1975320cad) | Sep 20, 2022 |
| Alienware     | Area-51m R2 A00             | Notebook    | [0ebdec6dd0](https://linux-hardware.org/?probe=0ebdec6dd0) | Sep 20, 2022 |
| ASUSTek       | N56VZ                       | Notebook    | [ce162c52c0](https://linux-hardware.org/?probe=ce162c52c0) | Sep 19, 2022 |
| Dell          | 0G785M A00                  | Desktop     | [8b8c41b401](https://linux-hardware.org/?probe=8b8c41b401) | Sep 19, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [1f60a4d202](https://linux-hardware.org/?probe=1f60a4d202) | Sep 19, 2022 |
| Lenovo        | IdeaPadFlex 10 20324        | Notebook    | [4e7f3b7bac](https://linux-hardware.org/?probe=4e7f3b7bac) | Sep 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [cabf88c8be](https://linux-hardware.org/?probe=cabf88c8be) | Sep 19, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [854a0d4410](https://linux-hardware.org/?probe=854a0d4410) | Sep 19, 2022 |
| Dell          | Precision M6400             | Notebook    | [67924c5333](https://linux-hardware.org/?probe=67924c5333) | Sep 19, 2022 |
| Dell          | Precision M6400             | Notebook    | [27a55639e4](https://linux-hardware.org/?probe=27a55639e4) | Sep 19, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [e0e49d51d0](https://linux-hardware.org/?probe=e0e49d51d0) | Sep 18, 2022 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [7b95813c96](https://linux-hardware.org/?probe=7b95813c96) | Sep 18, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [812ea842dc](https://linux-hardware.org/?probe=812ea842dc) | Sep 18, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [004d0a2b9d](https://linux-hardware.org/?probe=004d0a2b9d) | Sep 17, 2022 |
| Unknown       | T3 MRD                      | Desktop     | [b10823b50f](https://linux-hardware.org/?probe=b10823b50f) | Sep 17, 2022 |
| Biostar       | H410MH S2                   | Desktop     | [832dd81851](https://linux-hardware.org/?probe=832dd81851) | Sep 17, 2022 |
| Lenovo        | ThinkPad P1 20MD0020US      | Notebook    | [a701fed148](https://linux-hardware.org/?probe=a701fed148) | Sep 16, 2022 |
| Lenovo        | MAHOBAY NOK                 | Desktop     | [cce010fd53](https://linux-hardware.org/?probe=cce010fd53) | Sep 16, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5ffc7d13ac](https://linux-hardware.org/?probe=5ffc7d13ac) | Sep 16, 2022 |
| Dell          | G5 5505                     | Notebook    | [25755e8605](https://linux-hardware.org/?probe=25755e8605) | Sep 16, 2022 |
| HP            | 15                          | Notebook    | [79aa0d618f](https://linux-hardware.org/?probe=79aa0d618f) | Sep 14, 2022 |
| Acer          | Aspire A315-42              | Notebook    | [820c1e2ac6](https://linux-hardware.org/?probe=820c1e2ac6) | Sep 11, 2022 |
| Dell          | Precision 3510              | Notebook    | [4337a8e018](https://linux-hardware.org/?probe=4337a8e018) | Sep 11, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [d9e9ec9afa](https://linux-hardware.org/?probe=d9e9ec9afa) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming B550M-PLUS WI... | Desktop     | [1cdd7cda15](https://linux-hardware.org/?probe=1cdd7cda15) | Sep 09, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [6eae76b5d0](https://linux-hardware.org/?probe=6eae76b5d0) | Sep 01, 2022 |
| ASRock        | FM2A55M-HD+                 | Desktop     | [2f96c73efb](https://linux-hardware.org/?probe=2f96c73efb) | Sep 01, 2022 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0ca693e2dd](https://linux-hardware.org/?probe=0ca693e2dd) | Aug 31, 2022 |
| Gigabyte      | H110M-H-CF                  | Desktop     | [86fc2bf58f](https://linux-hardware.org/?probe=86fc2bf58f) | Aug 31, 2022 |
| Alienware     | 01NYPT A00                  | Desktop     | [cd95b79270](https://linux-hardware.org/?probe=cd95b79270) | Aug 29, 2022 |
| AZW           | SER                         | Mini pc     | [92460ed2a6](https://linux-hardware.org/?probe=92460ed2a6) | Aug 29, 2022 |
| ASUSTek       | TP500LA                     | Notebook    | [de395dddd8](https://linux-hardware.org/?probe=de395dddd8) | Aug 28, 2022 |
| ASRock        | B560 Steel Legend           | Desktop     | [c64907de8d](https://linux-hardware.org/?probe=c64907de8d) | Aug 27, 2022 |
| ASUSTek       | P8Z68-V PRO                 | Desktop     | [37ae937f4d](https://linux-hardware.org/?probe=37ae937f4d) | Aug 26, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [663509c999](https://linux-hardware.org/?probe=663509c999) | Aug 24, 2022 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [2b7d1d59a1](https://linux-hardware.org/?probe=2b7d1d59a1) | Aug 24, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [928ce75df1](https://linux-hardware.org/?probe=928ce75df1) | Aug 24, 2022 |
| ASRock        | H61M-VG3                    | Desktop     | [a3cd7ba2c1](https://linux-hardware.org/?probe=a3cd7ba2c1) | Aug 22, 2022 |
| Dell          | G15 5511                    | Notebook    | [44fa9bf084](https://linux-hardware.org/?probe=44fa9bf084) | Aug 21, 2022 |
| ASUSTek       | B85M-E                      | Desktop     | [0b5044dacf](https://linux-hardware.org/?probe=0b5044dacf) | Aug 19, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [a2b6c2ae17](https://linux-hardware.org/?probe=a2b6c2ae17) | Aug 19, 2022 |
| Notebook      | P7xxDM2(-G)                 | Notebook    | [f074899985](https://linux-hardware.org/?probe=f074899985) | Aug 17, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [315da58d24](https://linux-hardware.org/?probe=315da58d24) | Aug 16, 2022 |
| ASRock        | X470 Master SLI             | Desktop     | [ce62975b20](https://linux-hardware.org/?probe=ce62975b20) | Aug 15, 2022 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [b2bbce2845](https://linux-hardware.org/?probe=b2bbce2845) | Aug 15, 2022 |
| ASRock        | Z97 Extreme6                | Desktop     | [31d7973a9d](https://linux-hardware.org/?probe=31d7973a9d) | Aug 14, 2022 |
| ASRock        | 760GM-HDV                   | Desktop     | [beabb7dd99](https://linux-hardware.org/?probe=beabb7dd99) | Aug 14, 2022 |
| Apple         | MacBookPro14,2              | Notebook    | [c66d476513](https://linux-hardware.org/?probe=c66d476513) | Aug 13, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [df2cc1a299](https://linux-hardware.org/?probe=df2cc1a299) | Aug 12, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [27cd96982f](https://linux-hardware.org/?probe=27cd96982f) | Aug 10, 2022 |
| HP            | 8906 SMVB                   | Desktop     | [8f30392f49](https://linux-hardware.org/?probe=8f30392f49) | Aug 10, 2022 |
| HP            | 8054                        | Desktop     | [469b765fe0](https://linux-hardware.org/?probe=469b765fe0) | Aug 10, 2022 |
| ASUSTek       | G20AJ                       | Desktop     | [613f8a0c36](https://linux-hardware.org/?probe=613f8a0c36) | Aug 08, 2022 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [f65ba77de3](https://linux-hardware.org/?probe=f65ba77de3) | Aug 07, 2022 |
| Lenovo        | IdeaPad Y700-15ISK 80NV     | Notebook    | [6beddf67f5](https://linux-hardware.org/?probe=6beddf67f5) | Aug 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [7a60eede9a](https://linux-hardware.org/?probe=7a60eede9a) | Aug 04, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [e142cf5c91](https://linux-hardware.org/?probe=e142cf5c91) | Aug 04, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [7c4355417f](https://linux-hardware.org/?probe=7c4355417f) | Aug 03, 2022 |
| ASUSTek       | Q504UAK                     | Convertible | [5f2025770d](https://linux-hardware.org/?probe=5f2025770d) | Aug 03, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [f034a02e69](https://linux-hardware.org/?probe=f034a02e69) | Aug 01, 2022 |
| Razer         | Blade                       | Notebook    | [cc3ce45956](https://linux-hardware.org/?probe=cc3ce45956) | Jul 31, 2022 |
| HP            | ZBook 15 G2                 | Notebook    | [3aa2fda09a](https://linux-hardware.org/?probe=3aa2fda09a) | Jul 26, 2022 |
| MSI           | 970 GAMING                  | Desktop     | [bf2a870952](https://linux-hardware.org/?probe=bf2a870952) | Jul 23, 2022 |
| Dell          | 0J8H4R A01                  | Desktop     | [3d7d06475c](https://linux-hardware.org/?probe=3d7d06475c) | Jul 23, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [7d6b6d93d3](https://linux-hardware.org/?probe=7d6b6d93d3) | Jul 21, 2022 |
| eMachines     | EL1870                      | Desktop     | [58e76fb684](https://linux-hardware.org/?probe=58e76fb684) | Jul 19, 2022 |
| MSI           | X570-A PRO                  | Desktop     | [c9683ea265](https://linux-hardware.org/?probe=c9683ea265) | Jul 19, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Nobara/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name      | Computers | Percent |
|-----------|-----------|---------|
| Nobara 36 | 249       | 59%     |
| Nobara 37 | 173       | 41%     |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Nobara | 415       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                       | Computers | Percent |
|-------------------------------|-----------|---------|
| 6.0.10-201.fc36.x86_64        | 37        | 8.31%   |
| 6.0.14-201.fsync.fc36.x86_64  | 32        | 7.19%   |
| 6.1.14-201.fsync.fc37.x86_64  | 25        | 5.62%   |
| 5.19.14-201.fsync.fc36.x86_64 | 24        | 5.39%   |
| 6.1.11-201.fsync.fc37.x86_64  | 19        | 4.27%   |
| 6.2.6-201.fsync.fc37.x86_64   | 17        | 3.82%   |
| 6.1.9-200.fsync.fc37.x86_64   | 17        | 3.82%   |
| 6.1.4-203.fsync.fc37.x86_64   | 16        | 3.6%    |
| 5.19.9-201.fsync.fc36.x86_64  | 16        | 3.6%    |
| 5.19.7-204.fsync.fc36.x86_64  | 15        | 3.37%   |
| 6.2.10-200.fsync.fc37.x86_64  | 13        | 2.92%   |
| 6.0.7-201.fsync.fc36.x86_64   | 12        | 2.7%    |
| 5.19.16-201.fsync.fc36.x86_64 | 12        | 2.7%    |
| 6.2.8-200.fsync.fc37.x86_64   | 11        | 2.47%   |
| 6.0.5-201.fsync.fc36.x86_64   | 11        | 2.47%   |
| 6.0.16-301.fsync.fc37.x86_64  | 11        | 2.47%   |
| 5.18.13-201.fsync.fc36.x86_64 | 11        | 2.47%   |
| 6.1.6-203.fsync.fc37.x86_64   | 10        | 2.25%   |
| 6.2.11-201.fsync.fc37.x86_64  | 9         | 2.02%   |
| 6.1.8-202.fsync.fc37.x86_64   | 9         | 2.02%   |
| 6.0.9-201.fc36.x86_64         | 9         | 2.02%   |
| 5.19.12-201.fsync.fc36.x86_64 | 8         | 1.8%    |
| 5.19.10-201.fsync.fc36.x86_64 | 8         | 1.8%    |
| 6.2.11-202.fsync.fc37.x86_64  | 7         | 1.57%   |
| 5.19.4-201.fsync.fc36.x86_64  | 7         | 1.57%   |
| 5.18.16-201.fsync.fc36.x86_64 | 7         | 1.57%   |
| 5.19.15-202.fsync.fc36.x86_64 | 6         | 1.35%   |
| 5.19.11-201.fsync.fc36.x86_64 | 6         | 1.35%   |
| 5.18.17-201.fsync.fc36.x86_64 | 6         | 1.35%   |
| 6.2.12-200.fsync.fc37.x86_64  | 4         | 0.9%    |
| 6.1.6-201.fsync.fc37.x86_64   | 4         | 0.9%    |
| 6.0.9-202.fc36.x86_64         | 4         | 0.9%    |
| 6.0.8-201.fsync.fc36.x86_64   | 4         | 0.9%    |
| 6.0.7-202.fsync.fc36.x86_64   | 4         | 0.9%    |
| 5.19.8-201.fsync.fc36.x86_64  | 4         | 0.9%    |
| 5.18.19-201.fsync.fc36.x86_64 | 4         | 0.9%    |
| 6.1.8-201.fsync.fc37.x86_64   | 3         | 0.67%   |
| 5.18.11-201.fsync.fc36.x86_64 | 3         | 0.67%   |
| 6.1.6-202.fsync.fc37.x86_64   | 2         | 0.45%   |
| 6.0.18-301.fsync.fc37.x86_64  | 2         | 0.45%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0.10  | 37        | 8.31%   |
| 6.0.14  | 32        | 7.19%   |
| 6.1.14  | 25        | 5.62%   |
| 5.19.14 | 24        | 5.39%   |
| 6.1.11  | 19        | 4.27%   |
| 6.2.6   | 17        | 3.82%   |
| 6.1.9   | 17        | 3.82%   |
| 5.19.7  | 17        | 3.82%   |
| 6.2.11  | 16        | 3.6%    |
| 6.1.6   | 16        | 3.6%    |
| 6.1.4   | 16        | 3.6%    |
| 6.0.7   | 16        | 3.6%    |
| 5.19.9  | 16        | 3.6%    |
| 6.2.10  | 13        | 2.92%   |
| 6.1.8   | 13        | 2.92%   |
| 6.0.9   | 13        | 2.92%   |
| 5.19.16 | 12        | 2.7%    |
| 6.2.8   | 11        | 2.47%   |
| 6.0.5   | 11        | 2.47%   |
| 6.0.16  | 11        | 2.47%   |
| 5.18.13 | 11        | 2.47%   |
| 5.19.12 | 8         | 1.8%    |
| 5.19.10 | 8         | 1.8%    |
| 5.19.4  | 7         | 1.57%   |
| 5.18.16 | 7         | 1.57%   |
| 5.19.15 | 6         | 1.35%   |
| 5.19.11 | 6         | 1.35%   |
| 5.18.17 | 6         | 1.35%   |
| 6.2.12  | 4         | 0.9%    |
| 6.0.8   | 4         | 0.9%    |
| 5.19.8  | 4         | 0.9%    |
| 5.18.19 | 4         | 0.9%    |
| 5.19.13 | 3         | 0.67%   |
| 5.18.11 | 3         | 0.67%   |
| 6.0.18  | 2         | 0.45%   |
| 6.0.15  | 2         | 0.45%   |
| 5.18.18 | 2         | 0.45%   |
| 6.2.0   | 1         | 0.22%   |
| 6.1.12  | 1         | 0.22%   |
| 6.0.2   | 1         | 0.22%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.0     | 126       | 28.83%  |
| 5.19    | 112       | 25.63%  |
| 6.1     | 106       | 24.26%  |
| 6.2     | 59        | 13.5%   |
| 5.18    | 34        | 7.78%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 415       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| GNOME         | 306       | 73.38%  |
| KDE5          | 104       | 24.94%  |
| Unknown       | 4         | 0.96%   |
| GNOME Classic | 2         | 0.48%   |
| X-Cinnamon    | 1         | 0.24%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Wayland | 319       | 75.24%  |
| X11     | 99        | 23.35%  |
| Unknown | 4         | 0.94%   |
| Tty     | 2         | 0.47%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 343       | 81.67%  |
| GDM     | 48        | 11.43%  |
| SDDM    | 25        | 5.95%   |
| LightDM | 4         | 0.95%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 225       | 53.96%  |
| en_GB   | 33        | 7.91%   |
| de_DE   | 16        | 3.84%   |
| es_ES   | 15        | 3.6%    |
| ru_RU   | 10        | 2.4%    |
| es_MX   | 10        | 2.4%    |
| es_AR   | 10        | 2.4%    |
| en_CA   | 10        | 2.4%    |
| pt_BR   | 9         | 2.16%   |
| it_IT   | 8         | 1.92%   |
| pl_PL   | 7         | 1.68%   |
| fr_FR   | 7         | 1.68%   |
| de_AT   | 5         | 1.2%    |
| nl_NL   | 4         | 0.96%   |
| es_CO   | 4         | 0.96%   |
| en_NZ   | 4         | 0.96%   |
| en_IN   | 4         | 0.96%   |
| en_AU   | 4         | 0.96%   |
| pt_PT   | 3         | 0.72%   |
| Unknown | 3         | 0.72%   |
| tr_TR   | 2         | 0.48%   |
| sv_SE   | 2         | 0.48%   |
| fi_FI   | 2         | 0.48%   |
| en_PH   | 2         | 0.48%   |
| ar_SA   | 2         | 0.48%   |
| zh_TW   | 1         | 0.24%   |
| sk_SK   | 1         | 0.24%   |
| nb_NO   | 1         | 0.24%   |
| hu_HU   | 1         | 0.24%   |
| hr_HR   | 1         | 0.24%   |
| es_US   | 1         | 0.24%   |
| es_GT   | 1         | 0.24%   |
| es_EC   | 1         | 0.24%   |
| es_CR   | 1         | 0.24%   |
| es_CL   | 1         | 0.24%   |
| en_ZA   | 1         | 0.24%   |
| en_IL   | 1         | 0.24%   |
| en_IE   | 1         | 0.24%   |
| da_DK   | 1         | 0.24%   |
| cs_CZ   | 1         | 0.24%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 334       | 80.1%   |
| BIOS | 83        | 19.9%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 285       | 68.18%  |
| Ext4  | 131       | 31.34%  |
| Xfs   | 2         | 0.48%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 340       | 80.76%  |
| GPT     | 73        | 17.34%  |
| MBR     | 8         | 1.9%    |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 394       | 94.71%  |
| Yes       | 22        | 5.29%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 372       | 89.64%  |
| Yes       | 43        | 10.36%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 105       | 25.3%   |
| MSI                 | 55        | 13.25%  |
| Lenovo              | 48        | 11.57%  |
| Hewlett-Packard     | 45        | 10.84%  |
| Gigabyte Technology | 36        | 8.67%   |
| Dell                | 29        | 6.99%   |
| ASRock              | 21        | 5.06%   |
| Acer                | 15        | 3.61%   |
| Apple               | 13        | 3.13%   |
| Intel               | 6         | 1.45%   |
| Toshiba             | 3         | 0.72%   |
| Alienware           | 3         | 0.72%   |
| Positivo            | 2         | 0.48%   |
| Notebook            | 2         | 0.48%   |
| Fujitsu             | 2         | 0.48%   |
| Biostar             | 2         | 0.48%   |
| AZW                 | 2         | 0.48%   |
| Unknown             | 2         | 0.48%   |
| ZOTAC               | 1         | 0.24%   |
| Valve               | 1         | 0.24%   |
| Supermicro          | 1         | 0.24%   |
| Sony                | 1         | 0.24%   |
| Schenker            | 1         | 0.24%   |
| Samsung Electronics | 1         | 0.24%   |
| Razer               | 1         | 0.24%   |
| Protectli           | 1         | 0.24%   |
| ONE-NETBOOK         | 1         | 0.24%   |
| OEM                 | 1         | 0.24%   |
| Monster             | 1         | 0.24%   |
| Microsoft           | 1         | 0.24%   |
| Micro Electronics   | 1         | 0.24%   |
| Medion              | 1         | 0.24%   |
| HUAWEI              | 1         | 0.24%   |
| GEO                 | 1         | 0.24%   |
| Gateway             | 1         | 0.24%   |
| EVOO                | 1         | 0.24%   |
| eMachines           | 1         | 0.24%   |
| ECS                 | 1         | 0.24%   |
| Dynabook            | 1         | 0.24%   |
| Coradir             | 1         | 0.24%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                | Computers | Percent |
|-------------------------------------|-----------|---------|
| Unknown                             | 6         | 1.45%   |
| MSI MS-7C91                         | 5         | 1.2%    |
| MSI MS-7B86                         | 5         | 1.2%    |
| MSI MS-7C02                         | 4         | 0.96%   |
| MSI MS-7C37                         | 3         | 0.72%   |
| MSI MS-7B79                         | 3         | 0.72%   |
| Dell XPS 8700                       | 3         | 0.72%   |
| ASUS PRIME A320M-K                  | 3         | 0.72%   |
| MSI MS-7D25                         | 2         | 0.48%   |
| MSI MS-7C56                         | 2         | 0.48%   |
| MSI MS-7693                         | 2         | 0.48%   |
| Lenovo Legion 5 15ARH05 82B5        | 2         | 0.48%   |
| Lenovo IdeaPad Y700-15ISK 80NV      | 2         | 0.48%   |
| Lenovo IdeaPad Gaming 3 15ACH6 82K2 | 2         | 0.48%   |
| Lenovo IdeaPad C340-14API 81N6      | 2         | 0.48%   |
| Intel X79                           | 2         | 0.48%   |
| HP ZBook 15u G3                     | 2         | 0.48%   |
| HP Pavilion Gaming Laptop 15-ec1xxx | 2         | 0.48%   |
| HP EliteBook x360 1030 G2           | 2         | 0.48%   |
| Gigabyte Z590I VISION D             | 2         | 0.48%   |
| Gigabyte X570 AORUS ELITE WIFI      | 2         | 0.48%   |
| Gigabyte B550 AORUS ELITE V2        | 2         | 0.48%   |
| Gigabyte B450M DS3H                 | 2         | 0.48%   |
| Dell Vostro 3400                    | 2         | 0.48%   |
| Dell OptiPlex 390                   | 2         | 0.48%   |
| Dell Inspiron 3542                  | 2         | 0.48%   |
| ASUS TUF Gaming B550M-PLUS          | 2         | 0.48%   |
| ASUS TUF Gaming B550-PLUS           | 2         | 0.48%   |
| ASUS TUF Gaming B460-PLUS           | 2         | 0.48%   |
| ASUS ROG STRIX B550-F GAMING        | 2         | 0.48%   |
| ASUS ROG CROSSHAIR VIII HERO        | 2         | 0.48%   |
| ASUS PRIME X370-PRO                 | 2         | 0.48%   |
| ASUS PRIME B450M-A                  | 2         | 0.48%   |
| ASUS All Series                     | 2         | 0.48%   |
| ASUS A68HM-K                        | 2         | 0.48%   |
| ASRock X670E Steel Legend           | 2         | 0.48%   |
| Acer Nitro AN515-52                 | 2         | 0.48%   |
| Acer Aspire VX5-591G                | 2         | 0.48%   |
| ZOTAC ZBOX-CI320NANO series         | 1         | 0.24%   |
| Valve Jupiter                       | 1         | 0.24%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| ASUS ROG           | 28        | 6.75%   |
| ASUS PRIME         | 19        | 4.58%   |
| ASUS TUF           | 16        | 3.86%   |
| Lenovo IdeaPad     | 15        | 3.61%   |
| Lenovo ThinkPad    | 10        | 2.41%   |
| HP EliteBook       | 8         | 1.93%   |
| ASUS VivoBook      | 8         | 1.93%   |
| Lenovo Legion      | 7         | 1.69%   |
| HP Pavilion        | 7         | 1.69%   |
| Acer Aspire        | 7         | 1.69%   |
| Unknown            | 6         | 1.45%   |
| MSI MS-7C91        | 5         | 1.2%    |
| MSI MS-7B86        | 5         | 1.2%    |
| HP ZBook           | 5         | 1.2%    |
| Dell Precision     | 5         | 1.2%    |
| Dell OptiPlex      | 5         | 1.2%    |
| MSI MS-7C02        | 4         | 0.96%   |
| Lenovo ThinkCentre | 4         | 0.96%   |
| HP ENVY            | 4         | 0.96%   |
| Gigabyte X570      | 4         | 0.96%   |
| Dell Vostro        | 4         | 0.96%   |
| Dell Inspiron      | 4         | 0.96%   |
| ASUS ASUS          | 4         | 0.96%   |
| Acer Nitro         | 4         | 0.96%   |
| MSI MS-7C37        | 3         | 0.72%   |
| MSI MS-7B79        | 3         | 0.72%   |
| HP EliteDesk       | 3         | 0.72%   |
| Dell XPS           | 3         | 0.72%   |
| Toshiba Satellite  | 2         | 0.48%   |
| MSI MS-7D25        | 2         | 0.48%   |
| MSI MS-7C56        | 2         | 0.48%   |
| MSI MS-7693        | 2         | 0.48%   |
| Lenovo IdeaPadFlex | 2         | 0.48%   |
| Lenovo G580        | 2         | 0.48%   |
| Intel X79          | 2         | 0.48%   |
| HP ProDesk         | 2         | 0.48%   |
| HP OMEN            | 2         | 0.48%   |
| HP Laptop          | 2         | 0.48%   |
| HP Compaq          | 2         | 0.48%   |
| Gigabyte Z590I     | 2         | 0.48%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 57        | 13.73%  |
| 2020 | 57        | 13.73%  |
| 2019 | 56        | 13.49%  |
| 2018 | 41        | 9.88%   |
| 2022 | 36        | 8.67%   |
| 2013 | 31        | 7.47%   |
| 2014 | 27        | 6.51%   |
| 2017 | 26        | 6.27%   |
| 2012 | 24        | 5.78%   |
| 2016 | 19        | 4.58%   |
| 2011 | 13        | 3.13%   |
| 2015 | 10        | 2.41%   |
| 2010 | 7         | 1.69%   |
| 2009 | 5         | 1.2%    |
| 2008 | 4         | 0.96%   |
| 2023 | 1         | 0.24%   |
| 2007 | 1         | 0.24%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Desktop     | 210       | 50.6%   |
| Notebook    | 183       | 44.1%   |
| Mini pc     | 8         | 1.93%   |
| Convertible | 6         | 1.45%   |
| All in one  | 5         | 1.2%    |
| Tablet      | 2         | 0.48%   |
| Server      | 1         | 0.24%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 415       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 415       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 126       | 30.36%  |
| 32.01-64.0  | 88        | 21.2%   |
| 4.01-8.0    | 68        | 16.39%  |
| 8.01-16.0   | 68        | 16.39%  |
| 3.01-4.0    | 34        | 8.19%   |
| 24.01-32.0  | 19        | 4.58%   |
| 64.01-256.0 | 10        | 2.41%   |
| 1.01-2.0    | 2         | 0.48%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 198       | 45.73%  |
| 3.01-4.0   | 102       | 23.56%  |
| 2.01-3.0   | 78        | 18.01%  |
| 8.01-16.0  | 40        | 9.24%   |
| 1.01-2.0   | 12        | 2.77%   |
| 16.01-24.0 | 2         | 0.46%   |
| 24.01-32.0 | 1         | 0.23%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 199       | 47.38%  |
| 2      | 114       | 27.14%  |
| 3      | 60        | 14.29%  |
| 4      | 22        | 5.24%   |
| 5      | 16        | 3.81%   |
| 6      | 4         | 0.95%   |
| 7      | 3         | 0.71%   |
| 10     | 2         | 0.48%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 334       | 80.1%   |
| Yes       | 83        | 19.9%   |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 373       | 89.66%  |
| No        | 43        | 10.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 323       | 77.64%  |
| No        | 93        | 22.36%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 291       | 69.95%  |
| No        | 125       | 30.05%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 131       | 31.57%  |
| Germany      | 27        | 6.51%   |
| UK           | 20        | 4.82%   |
| Spain        | 15        | 3.61%   |
| Canada       | 14        | 3.37%   |
| Argentina    | 14        | 3.37%   |
| Brazil       | 13        | 3.13%   |
| Russia       | 12        | 2.89%   |
| Poland       | 12        | 2.89%   |
| Italy        | 12        | 2.89%   |
| France       | 11        | 2.65%   |
| Mexico       | 10        | 2.41%   |
| Sweden       | 6         | 1.45%   |
| Netherlands  | 6         | 1.45%   |
| India        | 6         | 1.45%   |
| Colombia     | 6         | 1.45%   |
| Austria      | 6         | 1.45%   |
| Portugal     | 5         | 1.2%    |
| Philippines  | 5         | 1.2%    |
| Chile        | 5         | 1.2%    |
| Australia    | 5         | 1.2%    |
| New Zealand  | 4         | 0.96%   |
| Hungary      | 4         | 0.96%   |
| Turkey       | 3         | 0.72%   |
| Serbia       | 3         | 0.72%   |
| Saudi Arabia | 3         | 0.72%   |
| Romania      | 3         | 0.72%   |
| Norway       | 3         | 0.72%   |
| Indonesia    | 3         | 0.72%   |
| Finland      | 3         | 0.72%   |
| Czechia      | 3         | 0.72%   |
| Croatia      | 3         | 0.72%   |
| Vietnam      | 2         | 0.48%   |
| Venezuela    | 2         | 0.48%   |
| South Africa | 2         | 0.48%   |
| Estonia      | 2         | 0.48%   |
| Egypt        | 2         | 0.48%   |
| Belgium      | 2         | 0.48%   |
| Ukraine      | 1         | 0.24%   |
| Taiwan       | 1         | 0.24%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City          | Computers | Percent |
|---------------|-----------|---------|
| London        | 4         | 0.93%   |
| Guadalajara   | 4         | 0.93%   |
| Buenos Aires  | 4         | 0.93%   |
| Wroclaw       | 3         | 0.7%    |
| Vienna        | 3         | 0.7%    |
| Rome          | 3         | 0.7%    |
| Perm          | 3         | 0.7%    |
| Madrid        | 3         | 0.7%    |
| Denver        | 3         | 0.7%    |
| Boynton Beach | 3         | 0.7%    |
| Auckland      | 3         | 0.7%    |
| Atlanta       | 3         | 0.7%    |
| Wasilla       | 2         | 0.47%   |
| Warsaw        | 2         | 0.47%   |
| Villa Nueva   | 2         | 0.47%   |
| Victoria      | 2         | 0.47%   |
| Valladolid    | 2         | 0.47%   |
| Tucson        | 2         | 0.47%   |
| Stockholm     | 2         | 0.47%   |
| Springfield   | 2         | 0.47%   |
| Schmalkalden  | 2         | 0.47%   |
| Sao Paulo     | 2         | 0.47%   |
| San Jose      | 2         | 0.47%   |
| San Diego     | 2         | 0.47%   |
| San Antonio   | 2         | 0.47%   |
| Salem         | 2         | 0.47%   |
| Rotterdam     | 2         | 0.47%   |
| Riyadh        | 2         | 0.47%   |
| Poznan        | 2         | 0.47%   |
| Plano         | 2         | 0.47%   |
| Philadelphia  | 2         | 0.47%   |
| Pereira       | 2         | 0.47%   |
| Panama City   | 2         | 0.47%   |
| Ochsenfurt    | 2         | 0.47%   |
| Nuremberg     | 2         | 0.47%   |
| Novosibirsk   | 2         | 0.47%   |
| Mumbai        | 2         | 0.47%   |
| Moscow        | 2         | 0.47%   |
| Milano        | 2         | 0.47%   |
| Milan         | 2         | 0.47%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 127       | 194    | 17.57%  |
| WDC                         | 94        | 137    | 13%     |
| Seagate                     | 75        | 97     | 10.37%  |
| Kingston                    | 53        | 58     | 7.33%   |
| SanDisk                     | 49        | 53     | 6.78%   |
| Toshiba                     | 43        | 50     | 5.95%   |
| Crucial                     | 40        | 52     | 5.53%   |
| Intel                       | 22        | 29     | 3.04%   |
| Micron/Crucial Technology   | 18        | 25     | 2.49%   |
| SK hynix                    | 17        | 18     | 2.35%   |
| Phison Electronics          | 17        | 18     | 2.35%   |
| Micron Technology           | 16        | 16     | 2.21%   |
| Unknown                     | 10        | 12     | 1.38%   |
| PNY                         | 10        | 15     | 1.38%   |
| Hitachi                     | 10        | 14     | 1.38%   |
| China                       | 8         | 8      | 1.11%   |
| Apple                       | 8         | 9      | 1.11%   |
| SPCC                        | 7         | 8      | 0.97%   |
| Phison                      | 7         | 8      | 0.97%   |
| Silicon Motion              | 6         | 6      | 0.83%   |
| KIOXIA                      | 6         | 6      | 0.83%   |
| HGST                        | 6         | 6      | 0.83%   |
| Team                        | 5         | 5      | 0.69%   |
| Kingston Technology Company | 5         | 5      | 0.69%   |
| ADATA Technology            | 5         | 5      | 0.69%   |
| A-DATA Technology           | 4         | 4      | 0.55%   |
| Realtek Semiconductor       | 3         | 3      | 0.41%   |
| Unknown                     | 3         | 4      | 0.41%   |
| USB3.0                      | 2         | 2      | 0.28%   |
| Transcend                   | 2         | 2      | 0.28%   |
| Mushkin                     | 2         | 2      | 0.28%   |
| LITEON                      | 2         | 2      | 0.28%   |
| KIOXIA-EXCERIA              | 2         | 2      | 0.28%   |
| KingFast                    | 2         | 2      | 0.28%   |
| HS-SSD-C100                 | 2         | 2      | 0.28%   |
| Drevo                       | 2         | 2      | 0.28%   |
| Apacer                      | 2         | 2      | 0.28%   |
| XSTAR                       | 1         | 1      | 0.14%   |
| XPG                         | 1         | 1      | 0.14%   |
| Verbatim                    | 1         | 1      | 0.14%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                                  | Computers | Percent |
|--------------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB      | 23        | 2.79%   |
| Kingston SA400S37240G 240GB SSD                        | 19        | 2.3%    |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                    | 14        | 1.7%    |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB     | 11        | 1.33%   |
| Sandisk WD Blue SN550 NVMe SSD 1024GB                  | 10        | 1.21%   |
| Samsung SSD 860 EVO 500GB                              | 9         | 1.09%   |
| Phison E12 NVMe Controller 512GB                       | 9         | 1.09%   |
| Crucial CT1000MX500SSD1 1TB                            | 9         | 1.09%   |
| Seagate ST2000DM008-2FR102 2TB                         | 8         | 0.97%   |
| Samsung SSD 850 EVO 500GB                              | 8         | 0.97%   |
| Toshiba DT01ACA100 1TB                                 | 7         | 0.85%   |
| Samsung SSD 850 EVO 250GB                              | 7         | 0.85%   |
| Intel SSD 660P Series 512GB                            | 7         | 0.85%   |
| Samsung SSD 980 1TB                                    | 6         | 0.73%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB    | 6         | 0.73%   |
| Toshiba MQ04ABF100 1TB                                 | 5         | 0.61%   |
| Toshiba HDWD110 1TB                                    | 5         | 0.61%   |
| Seagate ST2000DM001-1ER164 2TB                         | 5         | 0.61%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 512GB       | 5         | 0.61%   |
| Phison PS5013 E13 NVMe Controller 500GB                | 5         | 0.61%   |
| Crucial CT1000BX500SSD1 1TB                            | 5         | 0.61%   |
| WDC WD10JPCX-24UE4T0 1TB                               | 4         | 0.48%   |
| WDC WD10EZEX-08WN4A0 1TB                               | 4         | 0.48%   |
| WDC WD10EZEX-00BN5A0 1TB                               | 4         | 0.48%   |
| Toshiba DT01ACA200 2TB                                 | 4         | 0.48%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1024GB | 4         | 0.48%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                     | 4         | 0.48%   |
| Seagate ST1000DM003-1ER162 1TB                         | 4         | 0.48%   |
| Samsung SSD 980 500GB                                  | 4         | 0.48%   |
| Samsung SSD 970 EVO Plus 500GB                         | 4         | 0.48%   |
| Samsung SSD 860 EVO 1TB                                | 4         | 0.48%   |
| Samsung NVMe SSD Controller SM951/PM951 256GB          | 4         | 0.48%   |
| PNY CS900 500GB SSD                                    | 4         | 0.48%   |
| Kingston SA400S37480G 480GB SSD                        | 4         | 0.48%   |
| Kingston SA400S37120G 120GB SSD                        | 4         | 0.48%   |
| Intel SSDPEKNU512GZ 512GB                              | 4         | 0.48%   |
| Crucial CT500MX500SSD1 500GB                           | 4         | 0.48%   |
| Crucial CT2000MX500SSD1 2TB                            | 4         | 0.48%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                       | 3         | 0.36%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                         | 3         | 0.36%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 74        | 94     | 33.64%  |
| WDC                 | 73        | 106    | 33.18%  |
| Toshiba             | 36        | 42     | 16.36%  |
| Hitachi             | 10        | 14     | 4.55%   |
| Samsung Electronics | 8         | 14     | 3.64%   |
| HGST                | 6         | 6      | 2.73%   |
| Apple               | 5         | 5      | 2.27%   |
| USB3.0              | 1         | 1      | 0.45%   |
| Unknown             | 1         | 1      | 0.45%   |
| SABRENT             | 1         | 2      | 0.45%   |
| Maxtor              | 1         | 1      | 0.45%   |
| JMicron Technology  | 1         | 1      | 0.45%   |
| HGST HTS            | 1         | 1      | 0.45%   |
| Hewlett-Packard     | 1         | 1      | 0.45%   |
| Fujitsu             | 1         | 1      | 0.45%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 60        | 75     | 22.99%  |
| Kingston            | 40        | 44     | 15.33%  |
| Crucial             | 38        | 50     | 14.56%  |
| WDC                 | 20        | 22     | 7.66%   |
| SanDisk             | 18        | 18     | 6.9%    |
| PNY                 | 10        | 15     | 3.83%   |
| China               | 8         | 8      | 3.07%   |
| SPCC                | 7         | 8      | 2.68%   |
| Micron Technology   | 6         | 6      | 2.3%    |
| Team                | 4         | 4      | 1.53%   |
| SK hynix            | 4         | 4      | 1.53%   |
| Intel               | 4         | 4      | 1.53%   |
| A-DATA Technology   | 4         | 4      | 1.53%   |
| Transcend           | 2         | 2      | 0.77%   |
| Toshiba             | 2         | 2      | 0.77%   |
| Seagate             | 2         | 2      | 0.77%   |
| Mushkin             | 2         | 2      | 0.77%   |
| LITEON              | 2         | 2      | 0.77%   |
| KIOXIA-EXCERIA      | 2         | 2      | 0.77%   |
| KingFast            | 2         | 2      | 0.77%   |
| Drevo               | 2         | 2      | 0.77%   |
| Apple               | 2         | 2      | 0.77%   |
| Apacer              | 2         | 2      | 0.77%   |
| XSTAR               | 1         | 1      | 0.38%   |
| Verbatim            | 1         | 1      | 0.38%   |
| USB3.0              | 1         | 1      | 0.38%   |
| SuperSSpeed         | 1         | 1      | 0.38%   |
| Ramsta              | 1         | 1      | 0.38%   |
| PNY CS90            | 1         | 1      | 0.38%   |
| Patriot             | 1         | 1      | 0.38%   |
| ORTIAL              | 1         | 1      | 0.38%   |
| OCZ                 | 1         | 1      | 0.38%   |
| Neo                 | 1         | 1      | 0.38%   |
| MyDigitalSSD        | 1         | 1      | 0.38%   |
| LITEONIT            | 1         | 1      | 0.38%   |
| Lexar               | 1         | 1      | 0.38%   |
| Hypertec            | 1         | 1      | 0.38%   |
| Foxline             | 1         | 1      | 0.38%   |
| Emtec               | 1         | 1      | 0.38%   |
| Corsair             | 1         | 1      | 0.38%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| SSD     | 219       | 301    | 34.49%  |
| NVMe    | 214       | 305    | 33.7%   |
| HDD     | 184       | 290    | 28.98%  |
| Unknown | 11        | 14     | 1.73%   |
| MMC     | 7         | 7      | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 297       | 577    | 55%     |
| NVMe | 213       | 304    | 39.44%  |
| SAS  | 23        | 29     | 4.26%   |
| MMC  | 7         | 7      | 1.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 200       | 279    | 45.66%  |
| 0.51-1.0   | 144       | 189    | 32.88%  |
| 1.01-2.0   | 55        | 77     | 12.56%  |
| 3.01-4.0   | 15        | 17     | 3.42%   |
| 4.01-10.0  | 13        | 17     | 2.97%   |
| 2.01-3.0   | 7         | 7      | 1.6%    |
| 10.01-20.0 | 4         | 5      | 0.91%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 88        | 20.75%  |
| 501-1000       | 86        | 20.28%  |
| 251-500        | 84        | 19.81%  |
| 1001-2000      | 74        | 17.45%  |
| More than 3000 | 34        | 8.02%   |
| 2001-3000      | 21        | 4.95%   |
| 21-50          | 12        | 2.83%   |
| Unknown        | 12        | 2.83%   |
| 51-100         | 11        | 2.59%   |
| 1-20           | 2         | 0.47%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 21-50          | 113       | 26.1%   |
| 1-20           | 83        | 19.17%  |
| 101-250        | 64        | 14.78%  |
| 51-100         | 50        | 11.55%  |
| 251-500        | 47        | 10.85%  |
| 501-1000       | 30        | 6.93%   |
| 1001-2000      | 16        | 3.7%    |
| Unknown        | 12        | 2.77%   |
| More than 3000 | 10        | 2.31%   |
| 2001-3000      | 8         | 1.85%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                          | Computers | Drives | Percent |
|------------------------------------------------|-----------|--------|---------|
| WDC WD5000BEVT-75ZAT0 500GB                    | 2         | 2      | 13.33%  |
| WDC WD20EURS-63S48Y0 2TB                       | 1         | 1      | 6.67%   |
| WDC WD10EZEX-08M2NA0 1TB                       | 1         | 1      | 6.67%   |
| WDC WD10EACS-00D6B0 1TB                        | 1         | 1      | 6.67%   |
| SK hynix HFS128G39TND-N210A 128GB SSD          | 1         | 1      | 6.67%   |
| Seagate ST500DM002-1BD142 500GB                | 1         | 1      | 6.67%   |
| Seagate ST2000DX002-2DV164 2TB                 | 1         | 1      | 6.67%   |
| Seagate ST1000DM003-9YN162 1TB                 | 1         | 1      | 6.67%   |
| Samsung Electronics SSD 970 EVO 1TB            | 1         | 1      | 6.67%   |
| Samsung Electronics HD161GJ 160GB              | 1         | 1      | 6.67%   |
| Ramsta SSD S800 240GB                          | 1         | 1      | 6.67%   |
| Micron Technology MTFDDAK256MAM-1K12 256GB SSD | 1         | 1      | 6.67%   |
| Hitachi HTS54323 320GB                         | 1         | 1      | 6.67%   |
| HGST HTS721010A9E630 1TB                       | 1         | 1      | 6.67%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 33.33%  |
| Seagate             | 3         | 3      | 20%     |
| Samsung Electronics | 2         | 2      | 13.33%  |
| SK hynix            | 1         | 1      | 6.67%   |
| Ramsta              | 1         | 1      | 6.67%   |
| Micron Technology   | 1         | 1      | 6.67%   |
| Hitachi             | 1         | 1      | 6.67%   |
| HGST                | 1         | 1      | 6.67%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 5         | 5      | 45.45%  |
| Seagate             | 3         | 3      | 27.27%  |
| Samsung Electronics | 1         | 1      | 9.09%   |
| Hitachi             | 1         | 1      | 9.09%   |
| HGST                | 1         | 1      | 9.09%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 11        | 11     | 73.33%  |
| SSD  | 3         | 3      | 20%     |
| NVMe | 1         | 1      | 6.67%   |

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
| Detected | 348       | 748    | 79.27%  |
| Works    | 77        | 153    | 17.54%  |
| Malfunc  | 13        | 15     | 2.96%   |
| Limited  | 1         | 1      | 0.23%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 224       | 35.39%  |
| AMD                            | 144       | 22.75%  |
| Samsung Electronics            | 80        | 12.64%  |
| SanDisk                        | 38        | 6%      |
| Phison Electronics             | 24        | 3.79%   |
| Micron/Crucial Technology      | 20        | 3.16%   |
| Kingston Technology Company    | 19        | 3%      |
| ASMedia Technology             | 17        | 2.69%   |
| SK hynix                       | 13        | 2.05%   |
| Micron Technology              | 10        | 1.58%   |
| Silicon Motion                 | 6         | 0.95%   |
| Nvidia                         | 6         | 0.95%   |
| KIOXIA                         | 6         | 0.95%   |
| ADATA Technology               | 5         | 0.79%   |
| Toshiba America Info Systems   | 4         | 0.63%   |
| Realtek Semiconductor          | 4         | 0.63%   |
| Marvell Technology Group       | 4         | 0.63%   |
| JMicron Technology             | 2         | 0.32%   |
| Union Memory (Shenzhen)        | 1         | 0.16%   |
| Solid State Storage Technology | 1         | 0.16%   |
| Silicon Image                  | 1         | 0.16%   |
| Shenzhen Longsys Electronics   | 1         | 0.16%   |
| MAXIO Technology (Hangzhou)    | 1         | 0.16%   |
| Broadcom / LSI                 | 1         | 0.16%   |
| Apple                          | 1         | 0.16%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 95        | 13.46%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 36        | 5.1%    |
| AMD 400 Series Chipset SATA Controller                                         | 31        | 4.39%   |
| AMD 500 Series Chipset SATA Controller                                         | 23        | 3.26%   |
| Samsung NVMe SSD Controller 980                                                | 21        | 2.97%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 19        | 2.69%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 16        | 2.27%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 16        | 2.27%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 14        | 1.98%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 14        | 1.98%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 13        | 1.84%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 12        | 1.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 12        | 1.7%    |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 11        | 1.56%   |
| Intel Volume Management Device NVMe RAID Controller                            | 11        | 1.56%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 10        | 1.42%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 10        | 1.42%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 10        | 1.42%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 10        | 1.42%   |
| Phison E12 NVMe Controller                                                     | 9         | 1.27%   |
| Micron NVMe Storage Controller                                                 | 9         | 1.27%   |
| Intel SSD 660P Series                                                          | 9         | 1.27%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 9         | 1.27%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 9         | 1.27%   |
| Intel Alder Lake-S PCH SATA Controller [AHCI Mode]                             | 9         | 1.27%   |
| Kingston Company A2000 NVMe SSD                                                | 8         | 1.13%   |
| Intel SATA Controller [RAID mode]                                              | 8         | 1.13%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 1.13%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 8         | 1.13%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 7         | 0.99%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 7         | 0.99%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 7         | 0.99%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 7         | 0.99%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 0.85%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 5         | 0.71%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 5         | 0.71%   |
| SanDisk WD Blue SN570 NVMe SSD 1TB                                             | 5         | 0.71%   |
| Phison PS5013 E13 NVMe Controller                                              | 5         | 0.71%   |
| Phison E16 PCIe4 NVMe Controller                                               | 5         | 0.71%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 5         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 332       | 55.15%  |
| NVMe | 213       | 35.38%  |
| RAID | 33        | 5.48%   |
| IDE  | 22        | 3.65%   |
| SAS  | 2         | 0.33%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 242       | 58.31%  |
| AMD    | 173       | 41.69%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor           | 10        | 2.4%    |
| AMD Ryzen 7 3700X 8-Core Processor          | 8         | 1.92%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 8         | 1.92%   |
| AMD Ryzen 5 5600X 6-Core Processor          | 7         | 1.68%   |
| AMD Ryzen 9 5900X 12-Core Processor         | 6         | 1.44%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz          | 5         | 1.2%    |
| Intel Core i7-10750H CPU @ 2.60GHz          | 5         | 1.2%    |
| Intel Core i5-10300H CPU @ 2.50GHz          | 5         | 1.2%    |
| AMD Ryzen 7 5800H with Radeon Graphics      | 5         | 1.2%    |
| AMD Ryzen 5 4600H with Radeon Graphics      | 5         | 1.2%    |
| AMD FX-8350 Eight-Core Processor            | 5         | 1.2%    |
| Intel Core i9-9900K CPU @ 3.60GHz           | 4         | 0.96%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 4         | 0.96%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz          | 4         | 0.96%   |
| Intel Core i7-4790 CPU @ 3.60GHz            | 4         | 0.96%   |
| Intel Core i7-4770 CPU @ 3.40GHz            | 4         | 0.96%   |
| Intel Core i5-9400F CPU @ 2.90GHz           | 4         | 0.96%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 4         | 0.96%   |
| Intel Core i5-7200U CPU @ 2.50GHz           | 4         | 0.96%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 4         | 0.96%   |
| Intel 12th Gen Core i5-12600K               | 4         | 0.96%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz     | 4         | 0.96%   |
| AMD Ryzen 9 5950X 16-Core Processor         | 4         | 0.96%   |
| AMD Ryzen 7 5800X 8-Core Processor          | 4         | 0.96%   |
| AMD Ryzen 7 5700X 8-Core Processor          | 4         | 0.96%   |
| AMD Ryzen 5 5600G with Radeon Graphics      | 4         | 0.96%   |
| AMD Ryzen 5 5500U with Radeon Graphics      | 4         | 0.96%   |
| Intel Core i7-6500U CPU @ 2.50GHz           | 3         | 0.72%   |
| Intel Core i5-3470 CPU @ 3.20GHz            | 3         | 0.72%   |
| Intel Core i5-3210M CPU @ 2.50GHz           | 3         | 0.72%   |
| Intel Core i5-10400F CPU @ 2.90GHz          | 3         | 0.72%   |
| Intel Core i3-4030U CPU @ 1.90GHz           | 3         | 0.72%   |
| Intel 12th Gen Core i7-12700H               | 3         | 0.72%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 3         | 0.72%   |
| AMD Ryzen 9 7950X 16-Core Processor         | 3         | 0.72%   |
| AMD Ryzen 9 3900X 12-Core Processor         | 3         | 0.72%   |
| AMD Ryzen 7 5700U with Radeon Graphics      | 3         | 0.72%   |
| AMD Ryzen 7 5700G with Radeon Graphics      | 3         | 0.72%   |
| AMD Ryzen 5 3600X 6-Core Processor          | 3         | 0.72%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics | 3         | 0.72%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 77        | 18.51%  |
| Intel Core i5           | 73        | 17.55%  |
| AMD Ryzen 5             | 67        | 16.11%  |
| AMD Ryzen 7             | 45        | 10.82%  |
| Other                   | 34        | 8.17%   |
| AMD Ryzen 9             | 25        | 6.01%   |
| Intel Core i3           | 21        | 5.05%   |
| AMD FX                  | 12        | 2.88%   |
| Intel Celeron           | 10        | 2.4%    |
| Intel Xeon              | 9         | 2.16%   |
| Intel Core 2 Duo        | 6         | 1.44%   |
| Intel Pentium           | 5         | 1.2%    |
| AMD Ryzen 3             | 5         | 1.2%    |
| Intel Core i9           | 4         | 0.96%   |
| AMD A10                 | 4         | 0.96%   |
| Intel Atom              | 2         | 0.48%   |
| AMD Phenom II X6        | 2         | 0.48%   |
| AMD A6                  | 2         | 0.48%   |
| Intel Pentium Dual-Core | 1         | 0.24%   |
| Intel Core m7           | 1         | 0.24%   |
| Intel Core 2 Extreme    | 1         | 0.24%   |
| AMD Ryzen 3 PRO         | 1         | 0.24%   |
| AMD PRO A10             | 1         | 0.24%   |
| AMD Phenom II X4        | 1         | 0.24%   |
| AMD Phenom              | 1         | 0.24%   |
| AMD G                   | 1         | 0.24%   |
| AMD E                   | 1         | 0.24%   |
| AMD Athlon X4           | 1         | 0.24%   |
| AMD Athlon II X2        | 1         | 0.24%   |
| AMD Athlon Dual Core    | 1         | 0.24%   |
| AMD A4                  | 1         | 0.24%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 122       | 29.4%   |
| 6      | 97        | 23.37%  |
| 2      | 91        | 21.93%  |
| 8      | 65        | 15.66%  |
| 12     | 15        | 3.61%   |
| 16     | 10        | 2.41%   |
| 10     | 6         | 1.45%   |
| 3      | 4         | 0.96%   |
| 14     | 3         | 0.72%   |
| 1      | 2         | 0.48%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 414       | 99.76%  |
| 2      | 1         | 0.24%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 344       | 82.69%  |
| 1      | 72        | 17.31%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 415       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 44        | 10.45%  |
| 0x08701021 | 23        | 5.46%   |
| 0x306c3    | 20        | 4.75%   |
| 0x306a9    | 19        | 4.51%   |
| 0x0a50000c | 17        | 4.04%   |
| 0x206a7    | 16        | 3.8%    |
| 0x906ea    | 15        | 3.56%   |
| 0x40651    | 13        | 3.09%   |
| 0xa0652    | 12        | 2.85%   |
| 0x906e9    | 12        | 2.85%   |
| 0x08108109 | 12        | 2.85%   |
| 0x506e3    | 9         | 2.14%   |
| 0x0800820d | 9         | 2.14%   |
| 0x906a3    | 8         | 1.9%    |
| 0x806c1    | 8         | 1.9%    |
| 0x0a50000d | 8         | 1.9%    |
| 0x06000822 | 8         | 1.9%    |
| 0x806e9    | 7         | 1.66%   |
| 0x0a601203 | 7         | 1.66%   |
| 0x0a201016 | 7         | 1.66%   |
| 0x08608103 | 7         | 1.66%   |
| 0xa0655    | 6         | 1.43%   |
| 0x90672    | 6         | 1.43%   |
| 0x0a20120a | 6         | 1.43%   |
| 0x906ed    | 5         | 1.19%   |
| 0x806d1    | 5         | 1.19%   |
| 0x406e3    | 5         | 1.19%   |
| 0x0a201205 | 5         | 1.19%   |
| 0x0a201204 | 5         | 1.19%   |
| 0x08001138 | 5         | 1.19%   |
| 0xa0653    | 4         | 0.95%   |
| 0x906ec    | 4         | 0.95%   |
| 0x206d7    | 4         | 0.95%   |
| 0x1067a    | 4         | 0.95%   |
| 0x08600106 | 4         | 0.95%   |
| 0x08600104 | 4         | 0.95%   |
| 0x06003106 | 4         | 0.95%   |
| 0x806ea    | 3         | 0.71%   |
| 0x30678    | 3         | 0.71%   |
| 0x10676    | 3         | 0.71%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 57        | 13.7%   |
| Zen 3            | 53        | 12.74%  |
| Haswell          | 42        | 10.1%   |
| Zen 2            | 36        | 8.65%   |
| Zen+             | 26        | 6.25%   |
| CometLake        | 24        | 5.77%   |
| SandyBridge      | 22        | 5.29%   |
| Unknown          | 22        | 5.29%   |
| IvyBridge        | 21        | 5.05%   |
| Skylake          | 17        | 4.09%   |
| Alderlake Hybrid | 17        | 4.09%   |
| Piledriver       | 12        | 2.88%   |
| Icelake          | 10        | 2.4%    |
| Zen              | 8         | 1.92%   |
| TigerLake        | 8         | 1.92%   |
| Penryn           | 7         | 1.68%   |
| Silvermont       | 5         | 1.2%    |
| K10              | 5         | 1.2%    |
| Steamroller      | 4         | 0.96%   |
| Goldmont plus    | 3         | 0.72%   |
| Excavator        | 3         | 0.72%   |
| Broadwell        | 3         | 0.72%   |
| Westmere         | 2         | 0.48%   |
| Bobcat           | 2         | 0.48%   |
| Puma             | 1         | 0.24%   |
| Nehalem          | 1         | 0.24%   |
| K8 Hammer        | 1         | 0.24%   |
| Goldmont         | 1         | 0.24%   |
| Core             | 1         | 0.24%   |
| Bulldozer        | 1         | 0.24%   |
| Bonnell          | 1         | 0.24%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Nvidia | 197       | 36.96%  |
| AMD    | 174       | 32.65%  |
| Intel  | 162       | 30.39%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 20        | 3.65%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 17        | 3.1%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 16        | 2.92%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 14        | 2.55%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 14        | 2.55%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 13        | 2.37%   |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 11        | 2.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 10        | 1.82%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 10        | 1.82%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 9         | 1.64%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                  | 9         | 1.64%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 8         | 1.46%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 8         | 1.46%   |
| Intel HD Graphics 620                                                       | 8         | 1.46%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 8         | 1.46%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 8         | 1.46%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 7         | 1.28%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 7         | 1.28%   |
| Intel HD Graphics 530                                                       | 7         | 1.28%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 7         | 1.28%   |
| AMD Renoir                                                                  | 7         | 1.28%   |
| AMD Raphael                                                                 | 7         | 1.28%   |
| AMD Lucienne                                                                | 7         | 1.28%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 6         | 1.09%   |
| Intel HD Graphics 630                                                       | 6         | 1.09%   |
| Intel Alder Lake-P Integrated Graphics Controller                           | 6         | 1.09%   |
| AMD Rembrandt [Radeon 680M]                                                 | 6         | 1.09%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]         | 6         | 1.09%   |
| Nvidia TU117M                                                               | 5         | 0.91%   |
| Nvidia GP104 [GeForce GTX 1080]                                             | 5         | 0.91%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 5         | 0.91%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5         | 0.91%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 5         | 0.91%   |
| Nvidia TU117 [GeForce GTX 1650]                                             | 4         | 0.73%   |
| Nvidia TU106 [GeForce RTX 2070]                                             | 4         | 0.73%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                          | 4         | 0.73%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 4         | 0.73%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4         | 0.73%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4         | 0.73%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 4         | 0.73%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 124       | 29.81%  |
| 1 x Nvidia         | 102       | 24.52%  |
| 1 x Intel          | 74        | 17.79%  |
| Intel + Nvidia     | 65        | 15.63%  |
| AMD + Nvidia       | 27        | 6.49%   |
| Intel + AMD        | 11        | 2.64%   |
| 2 x AMD            | 10        | 2.4%    |
| 2 x Nvidia         | 2         | 0.48%   |
| Intel + 2 x Nvidia | 1         | 0.24%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 261       | 62.29%  |
| Proprietary | 150       | 35.8%   |
| Unknown     | 8         | 1.91%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 182       | 43.23%  |
| 7.01-8.0   | 53        | 12.59%  |
| 0.01-0.5   | 45        | 10.69%  |
| 1.01-2.0   | 40        | 9.5%    |
| 3.01-4.0   | 32        | 7.6%    |
| 8.01-16.0  | 31        | 7.36%   |
| 0.51-1.0   | 20        | 4.75%   |
| 5.01-6.0   | 10        | 2.38%   |
| 16.01-24.0 | 5         | 1.19%   |
| 2.01-3.0   | 3         | 0.71%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 63        | 13.18%  |
| AU Optronics            | 48        | 10.04%  |
| BOE                     | 34        | 7.11%   |
| Goldstar                | 33        | 6.9%    |
| LG Display              | 26        | 5.44%   |
| Chimei Innolux          | 25        | 5.23%   |
| Acer                    | 22        | 4.6%    |
| Dell                    | 21        | 4.39%   |
| BenQ                    | 18        | 3.77%   |
| ASUSTek Computer        | 15        | 3.14%   |
| Ancor Communications    | 14        | 2.93%   |
| Hewlett-Packard         | 13        | 2.72%   |
| AOC                     | 13        | 2.72%   |
| PANDA                   | 12        | 2.51%   |
| Apple                   | 11        | 2.3%    |
| MSI                     | 10        | 2.09%   |
| Vizio                   | 9         | 1.88%   |
| ViewSonic               | 9         | 1.88%   |
| Sony                    | 8         | 1.67%   |
| Sharp                   | 7         | 1.46%   |
| Lenovo                  | 7         | 1.46%   |
| Philips                 | 6         | 1.26%   |
| InfoVision              | 5         | 1.05%   |
| Toshiba                 | 4         | 0.84%   |
| Sceptre Tech            | 4         | 0.84%   |
| Gigabyte Technology     | 4         | 0.84%   |
| Unknown                 | 3         | 0.63%   |
| Insignia                | 2         | 0.42%   |
| Iiyama                  | 2         | 0.42%   |
| HUAWEI                  | 2         | 0.42%   |
| Eizo                    | 2         | 0.42%   |
| Chi Mei Optoelectronics | 2         | 0.42%   |
| ___                     | 1         | 0.21%   |
| Valve                   | 1         | 0.21%   |
| Sun                     | 1         | 0.21%   |
| SNC                     | 1         | 0.21%   |
| SFX                     | 1         | 0.21%   |
| Ruijiang                | 1         | 0.21%   |
| PRI                     | 1         | 0.21%   |
| Pixio                   | 1         | 0.21%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch                | 4         | 0.81%   |
| Samsung Electronics LCD Monitor SDC5344 1920x1080 344x194mm 15.5-inch  | 3         | 0.6%    |
| MSI G27C5 MSI3CA9 1920x1080 598x336mm 27.0-inch                        | 3         | 0.6%    |
| LG Display LCD Monitor LGD05D8 1920x1080 344x194mm 15.5-inch           | 3         | 0.6%    |
| Goldstar ULTRAGEAR GSM7766 2560x1440 697x392mm 31.5-inch               | 3         | 0.6%    |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch              | 3         | 0.6%    |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch       | 3         | 0.6%    |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch       | 3         | 0.6%    |
| BenQ GL2460 BNQ78CE 1920x1080 531x299mm 24.0-inch                      | 3         | 0.6%    |
| AU Optronics LCD Monitor AUO40EC 1366x768 344x193mm 15.5-inch          | 3         | 0.6%    |
| Ancor Communications ROG PG279Q ACI27EC 2560x1440 598x336mm 27.0-inch  | 3         | 0.6%    |
| Vizio V405-H9 VIZ1039 3840x2160 878x485mm 39.5-inch                    | 2         | 0.4%    |
| Vizio D43-D2 VIZ1004 1920x1080 477x268mm 21.5-inch                     | 2         | 0.4%    |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch              | 2         | 0.4%    |
| Toshiba TV TSB0108 1360x768 576x324mm 26.0-inch                        | 2         | 0.4%    |
| Samsung Electronics SyncMaster SAM03E5 1680x1050 474x296mm 22.0-inch   | 2         | 0.4%    |
| Samsung Electronics LCD Monitor SAM0A7A 1920x1080 1060x626mm 48.5-inch | 2         | 0.4%    |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch      | 2         | 0.4%    |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch      | 2         | 0.4%    |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                | 2         | 0.4%    |
| MSI G32C4 MSI3DA6 1920x1080 698x393mm 31.5-inch                        | 2         | 0.4%    |
| LG Display LCD Monitor LGD04A7 1920x1080 344x194mm 15.5-inch           | 2         | 0.4%    |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch           | 2         | 0.4%    |
| Lenovo LEN LT2252pwA LEN0A0C 1680x1050 474x296mm 22.0-inch             | 2         | 0.4%    |
| InfoVision LCD Monitor IVO0535 1920x1080 294x165mm 13.3-inch           | 2         | 0.4%    |
| Goldstar ULTRAGEAR GSM5BD3 2560x1440 697x392mm 31.5-inch               | 2         | 0.4%    |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch                | 2         | 0.4%    |
| Gigabyte Technology M27Q GBT270D 2560x1440 596x335mm 26.9-inch         | 2         | 0.4%    |
| Eizo EV2335W ENC2293 1920x1080 510x287mm 23.0-inch                     | 2         | 0.4%    |
| Dell U2717D DEL40EB 2560x1440 597x336mm 27.0-inch                      | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 0.4%    |
| Chimei Innolux LCD Monitor CMN14C4 1366x768 309x173mm 13.9-inch        | 2         | 0.4%    |
| BOE LCD Monitor BOE0998 1920x1080 344x194mm 15.5-inch                  | 2         | 0.4%    |
| AU Optronics LCD Monitor AUOC199 2560x1600 344x215mm 16.0-inch         | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO978F 1920x1080 382x215mm 17.3-inch         | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch          | 2         | 0.4%    |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 2         | 0.4%    |
| ASUSTek Computer VP28U AUS28B1 3840x2160 621x341mm 27.9-inch           | 2         | 0.4%    |
| ASUSTek Computer VP249 AUS24AF 1920x1080 527x296mm 23.8-inch           | 2         | 0.4%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 214       | 47.14%  |
| 2560x1440 (QHD)    | 52        | 11.45%  |
| 3840x2160 (4K)     | 49        | 10.79%  |
| 1366x768 (WXGA)    | 45        | 9.91%   |
| 1680x1050 (WSXGA+) | 12        | 2.64%   |
| 1440x900 (WXGA+)   | 9         | 1.98%   |
| 3440x1440          | 8         | 1.76%   |
| 1920x1200 (WUXGA)  | 8         | 1.76%   |
| 2560x1080          | 6         | 1.32%   |
| 1600x900 (HD+)     | 6         | 1.32%   |
| 1360x768           | 6         | 1.32%   |
| 2560x1600          | 5         | 1.1%    |
| 1920x540           | 5         | 1.1%    |
| 2880x1800          | 4         | 0.88%   |
| 2240x1400          | 3         | 0.66%   |
| 1280x800 (WXGA)    | 3         | 0.66%   |
| 1280x1024 (SXGA)   | 3         | 0.66%   |
| 2288x1287          | 2         | 0.44%   |
| 800x1280           | 1         | 0.22%   |
| 5760x1080          | 1         | 0.22%   |
| 3840x2560          | 1         | 0.22%   |
| 3840x2400          | 1         | 0.22%   |
| 3840x1600          | 1         | 0.22%   |
| 3840x1100          | 1         | 0.22%   |
| 3840x1080          | 1         | 0.22%   |
| 3200x1800 (QHD+)   | 1         | 0.22%   |
| 2736x1824          | 1         | 0.22%   |
| 2520x1680          | 1         | 0.22%   |
| 2048x1152          | 1         | 0.22%   |
| 1600x2560          | 1         | 0.22%   |
| 1600x1200          | 1         | 0.22%   |
| Unknown            | 1         | 0.22%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 108       | 22.45%  |
| 27      | 61        | 12.68%  |
| 24      | 35        | 7.28%   |
| 31      | 31        | 6.44%   |
| 23      | 31        | 6.44%   |
| 21      | 25        | 5.2%    |
| 13      | 23        | 4.78%   |
| 17      | 22        | 4.57%   |
| 14      | 20        | 4.16%   |
| 34      | 11        | 2.29%   |
| 84      | 9         | 1.87%   |
| 20      | 9         | 1.87%   |
| Unknown | 8         | 1.66%   |
| 22      | 7         | 1.46%   |
| 72      | 6         | 1.25%   |
| 48      | 6         | 1.25%   |
| 19      | 6         | 1.25%   |
| 16      | 6         | 1.25%   |
| 26      | 5         | 1.04%   |
| 18      | 5         | 1.04%   |
| 42      | 4         | 0.83%   |
| 52      | 3         | 0.62%   |
| 49      | 3         | 0.62%   |
| 40      | 3         | 0.62%   |
| 32      | 3         | 0.62%   |
| 12      | 3         | 0.62%   |
| 142     | 2         | 0.42%   |
| 69      | 2         | 0.42%   |
| 55      | 2         | 0.42%   |
| 38      | 2         | 0.42%   |
| 37      | 2         | 0.42%   |
| 33      | 2         | 0.42%   |
| 29      | 2         | 0.42%   |
| 28      | 2         | 0.42%   |
| 86      | 1         | 0.21%   |
| 75      | 1         | 0.21%   |
| 60      | 1         | 0.21%   |
| 58      | 1         | 0.21%   |
| 57      | 1         | 0.21%   |
| 54      | 1         | 0.21%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 146       | 31.26%  |
| 501-600        | 115       | 24.63%  |
| 401-500        | 52        | 11.13%  |
| 601-700        | 41        | 8.78%   |
| 351-400        | 19        | 4.07%   |
| 201-300        | 18        | 3.85%   |
| 1501-2000      | 18        | 3.85%   |
| 1001-1500      | 18        | 3.85%   |
| 701-800        | 16        | 3.43%   |
| 801-900        | 8         | 1.71%   |
| Unknown        | 8         | 1.71%   |
| 901-1000       | 4         | 0.86%   |
| More than 2000 | 2         | 0.43%   |
| 101-200        | 1         | 0.21%   |
| 1-100          | 1         | 0.21%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 325       | 79.66%  |
| 16/10   | 48        | 11.76%  |
| 21/9    | 15        | 3.68%   |
| 5/4     | 3         | 0.74%   |
| 4/3     | 3         | 0.74%   |
| 32/9    | 3         | 0.74%   |
| 3/2     | 3         | 0.74%   |
| 1.00    | 2         | 0.49%   |
| Unknown | 2         | 0.49%   |
| 3.40    | 1         | 0.25%   |
| 1.96    | 1         | 0.25%   |
| 0.67    | 1         | 0.25%   |
| 0.62    | 1         | 0.25%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 109       | 22.9%   |
| 201-250        | 79        | 16.6%   |
| 301-350        | 66        | 13.87%  |
| 351-500        | 47        | 9.87%   |
| More than 1000 | 35        | 7.35%   |
| 81-90          | 33        | 6.93%   |
| 151-200        | 26        | 5.46%   |
| 121-130        | 17        | 3.57%   |
| 501-1000       | 14        | 2.94%   |
| 251-300        | 12        | 2.52%   |
| 71-80          | 9         | 1.89%   |
| Unknown        | 8         | 1.68%   |
| 141-150        | 6         | 1.26%   |
| 111-120        | 6         | 1.26%   |
| 61-70          | 2         | 0.42%   |
| 51-60          | 2         | 0.42%   |
| 1-40           | 2         | 0.42%   |
| 131-140        | 2         | 0.42%   |
| 41-50          | 1         | 0.21%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 161       | 35.23%  |
| 121-160       | 116       | 25.38%  |
| 101-120       | 101       | 22.1%   |
| 161-240       | 30        | 6.56%   |
| 1-50          | 29        | 6.35%   |
| More than 240 | 12        | 2.63%   |
| Unknown       | 8         | 1.75%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 304       | 73.08%  |
| 2     | 82        | 19.71%  |
| 0     | 15        | 3.61%   |
| 3     | 14        | 3.37%   |
| 4     | 1         | 0.24%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 252       | 38.71%  |
| Intel                           | 217       | 33.33%  |
| Qualcomm Atheros                | 43        | 6.61%   |
| Broadcom                        | 33        | 5.07%   |
| MediaTek                        | 24        | 3.69%   |
| TP-Link                         | 14        | 2.15%   |
| Microsoft                       | 8         | 1.23%   |
| Ralink Technology               | 6         | 0.92%   |
| Broadcom Limited                | 5         | 0.77%   |
| Samsung Electronics             | 4         | 0.61%   |
| ASIX Electronics                | 4         | 0.61%   |
| Ralink                          | 3         | 0.46%   |
| Nvidia                          | 3         | 0.46%   |
| Motorola PCS                    | 3         | 0.46%   |
| Xiaomi                          | 2         | 0.31%   |
| Qualcomm Atheros Communications | 2         | 0.31%   |
| Qualcomm                        | 2         | 0.31%   |
| Marvell Technology Group        | 2         | 0.31%   |
| Hewlett-Packard                 | 2         | 0.31%   |
| ASUSTek Computer                | 2         | 0.31%   |
| Aquantia                        | 2         | 0.31%   |
| ZTE WCDMA Technologies MSM      | 1         | 0.15%   |
| Wacom                           | 1         | 0.15%   |
| T & A Mobile Phones             | 1         | 0.15%   |
| Sierra Wireless                 | 1         | 0.15%   |
| Panasonic (Matsushita)          | 1         | 0.15%   |
| Padix (Rockfire)                | 1         | 0.15%   |
| Oculus VR                       | 1         | 0.15%   |
| NetGear                         | 1         | 0.15%   |
| Loupedeck                       | 1         | 0.15%   |
| Linksys                         | 1         | 0.15%   |
| Lenovo                          | 1         | 0.15%   |
| JMicron Technology              | 1         | 0.15%   |
| ICS Advent                      | 1         | 0.15%   |
| Holtek Semiconductor            | 1         | 0.15%   |
| Google                          | 1         | 0.15%   |
| D-Link System                   | 1         | 0.15%   |
| D-Link                          | 1         | 0.15%   |
| Afatech                         | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 190       | 25.37%  |
| Intel Wi-Fi 6 AX200                                               | 37        | 4.94%   |
| Realtek RTL8125 2.5GbE Controller                                 | 32        | 4.27%   |
| Intel I211 Gigabit Network Connection                             | 22        | 2.94%   |
| Intel Ethernet Controller I225-V                                  | 17        | 2.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 14        | 1.87%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 13        | 1.74%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 11        | 1.47%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.34%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 10        | 1.34%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 1.34%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 9         | 1.2%    |
| Intel Wireless 7260                                               | 9         | 1.2%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 1.07%   |
| Intel Wireless 8265 / 8275                                        | 8         | 1.07%   |
| Intel Wireless 8260                                               | 8         | 1.07%   |
| Intel Wireless 7265                                               | 8         | 1.07%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 1.07%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 7         | 0.93%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 0.93%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 7         | 0.93%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter                | 7         | 0.93%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 6         | 0.8%    |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 6         | 0.8%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 6         | 0.8%    |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 6         | 0.8%    |
| Intel Wireless-AC 9260                                            | 6         | 0.8%    |
| Intel Ethernet Connection I217-LM                                 | 6         | 0.8%    |
| Intel Alder Lake-S PCH CNVi WiFi                                  | 6         | 0.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 5         | 0.67%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 0.67%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 5         | 0.67%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 5         | 0.67%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 5         | 0.67%   |
| Broadcom BCM43142 802.11b/g/n                                     | 5         | 0.67%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 4         | 0.53%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter          | 4         | 0.53%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.53%   |
| Microsoft Xbox 360 Wireless Adapter                               | 4         | 0.53%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 4         | 0.53%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 161       | 47.63%  |
| Realtek Semiconductor           | 53        | 15.68%  |
| Qualcomm Atheros                | 29        | 8.58%   |
| Broadcom                        | 27        | 7.99%   |
| MediaTek                        | 24        | 7.1%    |
| TP-Link                         | 13        | 3.85%   |
| Microsoft                       | 8         | 2.37%   |
| Ralink Technology               | 6         | 1.78%   |
| Ralink                          | 3         | 0.89%   |
| Broadcom Limited                | 3         | 0.89%   |
| Qualcomm Atheros Communications | 2         | 0.59%   |
| ASUSTek Computer                | 2         | 0.59%   |
| Wacom                           | 1         | 0.3%    |
| Sierra Wireless                 | 1         | 0.3%    |
| Panasonic (Matsushita)          | 1         | 0.3%    |
| NetGear                         | 1         | 0.3%    |
| Linksys                         | 1         | 0.3%    |
| D-Link System                   | 1         | 0.3%    |
| D-Link                          | 1         | 0.3%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 37        | 10.91%  |
| Intel Cannon Lake PCH CNVi WiFi                               | 14        | 4.13%   |
| Intel Comet Lake PCH CNVi WiFi                                | 13        | 3.83%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 11        | 3.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 10        | 2.95%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 10        | 2.95%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 9         | 2.65%   |
| Intel Wireless 7260                                           | 9         | 2.65%   |
| Intel Wireless 8265 / 8275                                    | 8         | 2.36%   |
| Intel Wireless 8260                                           | 8         | 2.36%   |
| Intel Wireless 7265                                           | 8         | 2.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 7         | 2.06%   |
| Intel Wi-Fi 6 AX201                                           | 7         | 2.06%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 7         | 2.06%   |
| Broadcom BCM4360 802.11ac Wireless Network Adapter            | 7         | 2.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 6         | 1.77%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 6         | 1.77%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 6         | 1.77%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter | 6         | 1.77%   |
| Intel Wireless-AC 9260                                        | 6         | 1.77%   |
| Intel Alder Lake-S PCH CNVi WiFi                              | 6         | 1.77%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 5         | 1.47%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                       | 5         | 1.47%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]              | 5         | 1.47%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 5         | 1.47%   |
| Broadcom BCM43142 802.11b/g/n                                 | 5         | 1.47%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 4         | 1.18%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter      | 4         | 1.18%   |
| Microsoft Xbox 360 Wireless Adapter                           | 4         | 1.18%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 4         | 1.18%   |
| TP-Link 802.11ac NIC                                          | 3         | 0.88%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 3         | 0.88%   |
| Microsoft Wireless XBox Controller Dongle                     | 3         | 0.88%   |
| Intel Wireless 3160                                           | 3         | 0.88%   |
| Broadcom BCM43602 802.11ac Wireless LAN SoC                   | 3         | 0.88%   |
| Broadcom BCM4331 802.11a/b/g/n                                | 3         | 0.88%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 3         | 0.88%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                   | 2         | 0.59%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 2         | 0.59%   |
| TP-Link Archer T2U PLUS [RTL8821AU]                           | 2         | 0.59%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Realtek Semiconductor      | 232       | 59.03%  |
| Intel                      | 103       | 26.21%  |
| Qualcomm Atheros           | 16        | 4.07%   |
| Broadcom                   | 11        | 2.8%    |
| ASIX Electronics           | 4         | 1.02%   |
| Nvidia                     | 3         | 0.76%   |
| Motorola PCS               | 3         | 0.76%   |
| Xiaomi                     | 2         | 0.51%   |
| Samsung Electronics        | 2         | 0.51%   |
| Qualcomm                   | 2         | 0.51%   |
| Marvell Technology Group   | 2         | 0.51%   |
| Hewlett-Packard            | 2         | 0.51%   |
| Broadcom Limited           | 2         | 0.51%   |
| Aquantia                   | 2         | 0.51%   |
| ZTE WCDMA Technologies MSM | 1         | 0.25%   |
| TP-Link                    | 1         | 0.25%   |
| T & A Mobile Phones        | 1         | 0.25%   |
| Lenovo                     | 1         | 0.25%   |
| JMicron Technology         | 1         | 0.25%   |
| ICS Advent                 | 1         | 0.25%   |
| Google                     | 1         | 0.25%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 190       | 47.15%  |
| Realtek RTL8125 2.5GbE Controller                                 | 32        | 7.94%   |
| Intel I211 Gigabit Network Connection                             | 22        | 5.46%   |
| Intel Ethernet Controller I225-V                                  | 17        | 4.22%   |
| Intel Ethernet Connection (7) I219-V                              | 10        | 2.48%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 8         | 1.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 8         | 1.99%   |
| Intel Ethernet Connection I217-LM                                 | 6         | 1.49%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 5         | 1.24%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 0.99%   |
| Intel Ethernet Connection I217-V                                  | 4         | 0.99%   |
| Intel Ethernet Connection (7) I219-LM                             | 4         | 0.99%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.99%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 3         | 0.74%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 3         | 0.74%   |
| Motorola PCS motorola razr 2022                                   | 3         | 0.74%   |
| Intel I210 Gigabit Network Connection                             | 3         | 0.74%   |
| Intel Ethernet Connection I218-LM                                 | 3         | 0.74%   |
| Intel Ethernet Connection (2) I219-V                              | 3         | 0.74%   |
| Intel Ethernet Connection (2) I218-V                              | 3         | 0.74%   |
| Intel Ethernet Connection (14) I219-V                             | 3         | 0.74%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.74%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.74%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.5%    |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 2         | 0.5%    |
| Qualcomm Atheros AR8162 Fast Ethernet                             | 2         | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 2         | 0.5%    |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.5%    |
| Intel Ethernet Connection (17) I219-V                             | 2         | 0.5%    |
| Intel Ethernet Connection (12) I219-V                             | 2         | 0.5%    |
| HP lt4120 Snapdragon X5 LTE                                       | 2         | 0.5%    |
| ZTE WCDMA MSM ZTE BLADE A530                                      | 1         | 0.25%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.25%   |
| Xiaomi Mi/Redmi series (RNDIS + ADB)                              | 1         | 0.25%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.25%   |
| T & A Mobile Phones A509DL                                        | 1         | 0.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.25%   |
| Realtek RTL8150 Fast Ethernet Adapter                             | 1         | 0.25%   |
| Realtek Killer E3000 2.5GbE Controller                            | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 374       | 53.43%  |
| WiFi     | 319       | 45.57%  |
| Modem    | 4         | 0.57%   |
| Unknown  | 3         | 0.43%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 230       | 51.8%   |
| WiFi     | 214       | 48.2%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 226       | 54.46%  |
| 1     | 175       | 42.17%  |
| 3     | 10        | 2.41%   |
| 0     | 3         | 0.72%   |
| 6     | 1         | 0.24%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 289       | 69.14%  |
| Yes  | 129       | 30.86%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 154       | 52.38%  |
| Realtek Semiconductor           | 22        | 7.48%   |
| Cambridge Silicon Radio         | 21        | 7.14%   |
| Qualcomm Atheros Communications | 13        | 4.42%   |
| Foxconn / Hon Hai               | 12        | 4.08%   |
| Broadcom                        | 12        | 4.08%   |
| IMC Networks                    | 11        | 3.74%   |
| Apple                           | 11        | 3.74%   |
| Lite-On Technology              | 10        | 3.4%    |
| MediaTek                        | 7         | 2.38%   |
| TP-Link                         | 5         | 1.7%    |
| ASUSTek Computer                | 4         | 1.36%   |
| Edimax Technology               | 3         | 1.02%   |
| Toshiba                         | 1         | 0.34%   |
| Realtek                         | 1         | 0.34%   |
| Ralink                          | 1         | 0.34%   |
| Integrated System Solution      | 1         | 0.34%   |
| Foxconn International           | 1         | 0.34%   |
| Dynex                           | 1         | 0.34%   |
| Dell                            | 1         | 0.34%   |
| Actions                         | 1         | 0.34%   |
| Unknown                         | 1         | 0.34%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                      | 43        | 14.63%  |
| Intel AX200 Bluetooth                                   | 38        | 12.93%  |
| Intel AX201 Bluetooth                                   | 27        | 9.18%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)     | 21        | 7.14%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)          | 19        | 6.46%   |
| Realtek Bluetooth Radio                                 | 18        | 6.12%   |
| Intel AX210 Bluetooth                                   | 9         | 3.06%   |
| MediaTek Wireless_Device                                | 7         | 2.38%   |
| Foxconn / Hon Hai Wireless_Device                       | 7         | 2.38%   |
| Intel Bluetooth Device                                  | 6         | 2.04%   |
| Apple Bluetooth Host Controller                         | 6         | 2.04%   |
| TP-Link UB500 Adapter                                   | 5         | 1.7%    |
| Qualcomm Atheros  Bluetooth Device                      | 5         | 1.7%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                | 5         | 1.7%    |
| Intel Wireless-AC 3168 Bluetooth                        | 5         | 1.7%    |
| IMC Networks Wireless_Device                            | 5         | 1.7%    |
| IMC Networks Bluetooth Radio                            | 5         | 1.7%    |
| Broadcom BCM20702A0 Bluetooth 4.0                       | 4         | 1.36%   |
| ASUS ASUS USB-BT500                                     | 4         | 1.36%   |
| Realtek  Bluetooth 4.2 Adapter                          | 3         | 1.02%   |
| Qualcomm Atheros Bluetooth USB Host Controller          | 3         | 1.02%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter | 3         | 1.02%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                   | 2         | 0.68%   |
| Lite-On Wireless_Device                                 | 2         | 0.68%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth              | 2         | 0.68%   |
| Lite-On Bluetooth Device                                | 2         | 0.68%   |
| Lite-On Atheros AR3012 Bluetooth                        | 2         | 0.68%   |
| Foxconn / Hon Hai Broadcom BCM20702 Bluetooth           | 2         | 0.68%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                    | 2         | 0.68%   |
| Apple Bluetooth USB Host Controller                     | 2         | 0.68%   |
| Toshiba Askey Bluetooth Module                          | 1         | 0.34%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                 | 1         | 0.34%   |
| Realtek 802.11ac WLAN Adapter                           | 1         | 0.34%   |
| Ralink RT3290 Bluetooth                                 | 1         | 0.34%   |
| Qualcomm Atheros Bluetooth (AR3011)                     | 1         | 0.34%   |
| Qualcomm Atheros AR9462 Bluetooth                       | 1         | 0.34%   |
| Qualcomm Atheros AR3011 Bluetooth                       | 1         | 0.34%   |
| Lite-On Bluetooth Radio                                 | 1         | 0.34%   |
| Lite-On BCM43142A0                                      | 1         | 0.34%   |
| Intel Centrino Bluetooth Wireless Transceiver           | 1         | 0.34%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 236       | 32.15%  |
| AMD                        | 211       | 28.75%  |
| Nvidia                     | 161       | 21.93%  |
| C-Media Electronics        | 21        | 2.86%   |
| Logitech                   | 15        | 2.04%   |
| SteelSeries ApS            | 7         | 0.95%   |
| Razer USA                  | 7         | 0.95%   |
| Kingston Technology        | 6         | 0.82%   |
| ASUSTek Computer           | 6         | 0.82%   |
| Plantronics                | 5         | 0.68%   |
| Creative Labs              | 5         | 0.68%   |
| Samson Technologies        | 4         | 0.54%   |
| JMTek                      | 4         | 0.54%   |
| Sony                       | 3         | 0.41%   |
| Focusrite-Novation         | 3         | 0.41%   |
| Creative Technology        | 3         | 0.41%   |
| Corsair                    | 3         | 0.41%   |
| Blue Microphones           | 3         | 0.41%   |
| TTGK Technology            | 2         | 0.27%   |
| Texas Instruments          | 2         | 0.27%   |
| SAVITECH                   | 2         | 0.27%   |
| Realtek Semiconductor      | 2         | 0.27%   |
| Generalplus Technology     | 2         | 0.27%   |
| Audio-Technica             | 2         | 0.27%   |
| Asahi Kasei Microsystems   | 2         | 0.27%   |
| Tenx Technology            | 1         | 0.14%   |
| Samsung Electronics        | 1         | 0.14%   |
| ROCCAT                     | 1         | 0.14%   |
| PreSonus Audio Electronics | 1         | 0.14%   |
| Positive Grid              | 1         | 0.14%   |
| Micro Star International   | 1         | 0.14%   |
| MCS                        | 1         | 0.14%   |
| Mark of the Unicorn        | 1         | 0.14%   |
| Lenovo                     | 1         | 0.14%   |
| Hewlett-Packard            | 1         | 0.14%   |
| GN Netcom                  | 1         | 0.14%   |
| Giga-Byte Technology       | 1         | 0.14%   |
| Elgato Systems             | 1         | 0.14%   |
| Cambridge Silicon Radio    | 1         | 0.14%   |
| BEHRINGER International    | 1         | 0.14%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 66        | 7.43%   |
| AMD Starship/Matisse HD Audio Controller                                   | 54        | 6.08%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 39        | 4.39%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 32        | 3.6%    |
| Intel Cannon Lake PCH cAVS                                                 | 27        | 3.04%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 21        | 2.36%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 21        | 2.36%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 20        | 2.25%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 18        | 2.03%   |
| Nvidia TU106 High Definition Audio Controller                              | 17        | 1.91%   |
| Intel Sunrise Point-LP HD Audio                                            | 17        | 1.91%   |
| Intel Comet Lake PCH cAVS                                                  | 17        | 1.91%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 17        | 1.91%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 17        | 1.91%   |
| Nvidia GA104 High Definition Audio Controller                              | 16        | 1.8%    |
| Intel 8 Series HD Audio Controller                                         | 15        | 1.69%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 15        | 1.69%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 14        | 1.58%   |
| Intel Haswell-ULT HD Audio Controller                                      | 14        | 1.58%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 14        | 1.58%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 14        | 1.58%   |
| Nvidia GP104 High Definition Audio Controller                              | 13        | 1.46%   |
| Nvidia GA106 High Definition Audio Controller                              | 12        | 1.35%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 11        | 1.24%   |
| AMD Navi 10 HDMI Audio                                                     | 11        | 1.24%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 10        | 1.13%   |
| Nvidia TU104 HD Audio Controller                                           | 9         | 1.01%   |
| Nvidia GP107GL High Definition Audio Controller                            | 9         | 1.01%   |
| Nvidia TU116 High Definition Audio Controller                              | 8         | 0.9%    |
| Nvidia GA102 High Definition Audio Controller                              | 8         | 0.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 8         | 0.9%    |
| Intel Alder Lake-S HD Audio Controller                                     | 8         | 0.9%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 8         | 0.9%    |
| AMD FCH Azalia Controller                                                  | 8         | 0.9%    |
| Nvidia GP106 High Definition Audio Controller                              | 7         | 0.79%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 7         | 0.79%   |
| Intel CM238 HD Audio Controller                                            | 7         | 0.79%   |
| Intel 200 Series PCH HD Audio                                              | 6         | 0.68%   |
| C-Media Electronics USB Audio Device                                       | 6         | 0.68%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 6         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 27        | 26.21%  |
| SK hynix            | 13        | 12.62%  |
| Micron Technology   | 13        | 12.62%  |
| Kingston            | 11        | 10.68%  |
| Corsair             | 11        | 10.68%  |
| G.Skill             | 7         | 6.8%    |
| Team                | 5         | 4.85%   |
| Unknown             | 4         | 3.88%   |
| Crucial             | 4         | 3.88%   |
| Unknown (ABCD)      | 2         | 1.94%   |
| Transcend           | 1         | 0.97%   |
| Ramaxel Technology  | 1         | 0.97%   |
| Nanya Technology    | 1         | 0.97%   |
| Hewlett-Packard     | 1         | 0.97%   |
| Elpida              | 1         | 0.97%   |
| Asgard              | 1         | 0.97%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.7%    |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 2         | 1.8%    |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 1.8%    |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 2         | 1.8%    |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.8%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.8%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.8%    |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.8%    |
| Samsung RAM M425R2GA3BB0-CQKOL 16GB SODIMM DDR5 4800MT/s         | 2         | 1.8%    |
| Micron RAM MTC8C1084S1SC48BA1 16GB SODIMM DDR5 4800MT/s          | 2         | 1.8%    |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 2         | 1.8%    |
| Kingston RAM KHX2666C16/8G 8GB DIMM DDR4 3466MT/s                | 2         | 1.8%    |
| G.Skill RAM F4-3600C16-8GTZNC 8GB DIMM DDR4 3800MT/s             | 2         | 1.8%    |
| G.Skill RAM F4-3200C16-8GVKB 8GB DIMM DDR4 3866MT/s              | 2         | 1.8%    |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 2         | 1.8%    |
| Unknown RAM Module 8GB DIMM 1333MT/s                             | 1         | 0.9%    |
| Unknown RAM 2400 C15 Series 16384MB DIMM DDR4 2133MT/s           | 1         | 0.9%    |
| Transcend RAM JM2666HSH-4G 4GB SODIMM DDR4 2667MT/s              | 1         | 0.9%    |
| Team RAM TEAMGROUP-UD4-3600 8GB DIMM DDR4 3600MT/s               | 1         | 0.9%    |
| Team RAM TEAMGROUP-UD4-3600 16GB DIMM DDR4 3733MT/s              | 1         | 0.9%    |
| Team RAM TEAMGROUP-UD4-3200 8GB DIMM DDR4 3800MT/s               | 1         | 0.9%    |
| Team RAM TEAMGROUP-UD3 8192MB DIMM DDR3 1600MT/s                 | 1         | 0.9%    |
| Team RAM TEAMGROUP-SD4-3200 16GB SODIMM DDR4 3200MT/s            | 1         | 0.9%    |
| SK hynix RAM Module 2GB SODIMM DDR3 1333MT/s                     | 1         | 0.9%    |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.9%    |
| SK hynix RAM HMT351S6EFR8A-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.9%    |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.9%    |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 1         | 0.9%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.9%    |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.9%    |
| SK hynix RAM HMA425S6AFR6N-UH 2GB SODIMM DDR4 2400MT/s           | 1         | 0.9%    |
| Samsung RAM Module 4GB SODIMM DDR3 1333MT/s                      | 1         | 0.9%    |
| Samsung RAM M474A2K43BB1-CPB 16GB SODIMM DDR4 2133MT/s           | 1         | 0.9%    |
| Samsung RAM M471B5674EB0-YK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 0.9%    |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 1         | 0.9%    |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.9%    |
| Samsung RAM M471A5143EB0-CPB 4GB SODIMM DDR4 2133MT/s            | 1         | 0.9%    |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 58        | 66.67%  |
| DDR3    | 17        | 19.54%  |
| LPDDR4  | 4         | 4.6%    |
| DDR5    | 4         | 4.6%    |
| Unknown | 2         | 2.3%    |
| SDRAM   | 1         | 1.15%   |
| DDR2    | 1         | 1.15%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 43        | 48.31%  |
| DIMM         | 40        | 44.94%  |
| Row Of Chips | 6         | 6.74%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 48        | 51.61%  |
| 4096  | 15        | 16.13%  |
| 16384 | 13        | 13.98%  |
| 32768 | 9         | 9.68%   |
| 2048  | 7         | 7.53%   |
| 1024  | 1         | 1.08%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 22        | 23.16%  |
| 1600  | 12        | 12.63%  |
| 2667  | 10        | 10.53%  |
| 3600  | 7         | 7.37%   |
| 2400  | 7         | 7.37%   |
| 1333  | 4         | 4.21%   |
| 4800  | 3         | 3.16%   |
| 3800  | 3         | 3.16%   |
| 3466  | 3         | 3.16%   |
| 3266  | 3         | 3.16%   |
| 3866  | 2         | 2.11%   |
| 3733  | 2         | 2.11%   |
| 2933  | 2         | 2.11%   |
| 2133  | 2         | 2.11%   |
| 1066  | 2         | 2.11%   |
| 6400  | 1         | 1.05%   |
| 5600  | 1         | 1.05%   |
| 4267  | 1         | 1.05%   |
| 4266  | 1         | 1.05%   |
| 3933  | 1         | 1.05%   |
| 3400  | 1         | 1.05%   |
| 3334  | 1         | 1.05%   |
| 3000  | 1         | 1.05%   |
| 2800  | 1         | 1.05%   |
| 975   | 1         | 1.05%   |
| 800   | 1         | 1.05%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 3         | 50%     |
| Canon               | 2         | 33.33%  |
| Samsung Electronics | 1         | 16.67%  |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                      | Computers | Percent |
|----------------------------|-----------|---------|
| Samsung Composite Device   | 1         | 16.67%  |
| Canon TR4500 series        | 1         | 16.67%  |
| Canon PIXMA MX370 Series   | 1         | 16.67%  |
| Brother MFC-L2710DN series | 1         | 16.67%  |
| Brother MFC-J460DW         | 1         | 16.67%  |
| Brother HL-L2370DW series  | 1         | 16.67%  |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model            | Computers | Percent |
|------------------|-----------|---------|
| HP ScanJet 2400c | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 40        | 18.52%  |
| IMC Networks                           | 26        | 12.04%  |
| Logitech                               | 21        | 9.72%   |
| Apple                                  | 17        | 7.87%   |
| Sunplus Innovation Technology          | 10        | 4.63%   |
| Realtek Semiconductor                  | 10        | 4.63%   |
| Cheng Uei Precision Industry (Foxlink) | 10        | 4.63%   |
| Quanta                                 | 9         | 4.17%   |
| Microdia                               | 9         | 4.17%   |
| Syntek                                 | 8         | 3.7%    |
| Acer                                   | 8         | 3.7%    |
| Bison Electronics                      | 6         | 2.78%   |
| Sonix Technology                       | 5         | 2.31%   |
| Suyin                                  | 4         | 1.85%   |
| Luxvisions Innotech Limited            | 4         | 1.85%   |
| Lite-On Technology                     | 4         | 1.85%   |
| SunplusIT                              | 3         | 1.39%   |
| Microsoft                              | 3         | 1.39%   |
| Samsung Electronics                    | 2         | 0.93%   |
| Hewlett-Packard                        | 2         | 0.93%   |
| Z-Star Microelectronics                | 1         | 0.46%   |
| YGTek                                  | 1         | 0.46%   |
| Tobii Technology AB                    | 1         | 0.46%   |
| Silicon Motion                         | 1         | 0.46%   |
| Razer USA                              | 1         | 0.46%   |
| Owon                                   | 1         | 0.46%   |
| Lenovo                                 | 1         | 0.46%   |
| Intel                                  | 1         | 0.46%   |
| Importek                               | 1         | 0.46%   |
| Goodong Industry                       | 1         | 0.46%   |
| Generalplus Technology                 | 1         | 0.46%   |
| EVGA                                   | 1         | 0.46%   |
| Cubeternet                             | 1         | 0.46%   |
| ARC International                      | 1         | 0.46%   |
| ANYKA                                  | 1         | 0.46%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                   | 13        | 5.94%   |
| Chicony Integrated Camera                           | 9         | 4.11%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                     | 8         | 3.65%   |
| Syntek Integrated Camera                            | 6         | 2.74%   |
| Logitech C922 Pro Stream Webcam                     | 6         | 2.74%   |
| IMC Networks Integrated Camera                      | 6         | 2.74%   |
| Chicony HD WebCam                                   | 6         | 2.74%   |
| Sunplus Integrated_Webcam_HD                        | 5         | 2.28%   |
| Microdia Integrated_Webcam_HD                       | 4         | 1.83%   |
| Logitech Webcam C270                                | 4         | 1.83%   |
| Logitech HD Pro Webcam C920                         | 4         | 1.83%   |
| Sonix USB2.0 HD UVC WebCam                          | 3         | 1.37%   |
| Realtek USB Camera                                  | 3         | 1.37%   |
| Realtek Integrated_Webcam_HD                        | 3         | 1.37%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 3         | 1.37%   |
| Chicony USB 2.0 Camera                              | 3         | 1.37%   |
| Chicony HP Truevision HD                            | 3         | 1.37%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Camera | 3         | 1.37%   |
| Bison HD Webcam                                     | 3         | 1.37%   |
| Apple FaceTime HD Camera (Built-in)                 | 3         | 1.37%   |
| Apple Built-in iSight                               | 3         | 1.37%   |
| Acer Integrated Camera                              | 3         | 1.37%   |
| Sunplus HD WebCam                                   | 2         | 0.91%   |
| Sonix USB2.0 FHD UVC WebCam                         | 2         | 0.91%   |
| Samsung Galaxy series, misc. (MTP mode)             | 2         | 0.91%   |
| Quanta HD Webcam                                    | 2         | 0.91%   |
| Quanta HD User Facing                               | 2         | 0.91%   |
| Microsoft LifeCam Cinema                            | 2         | 0.91%   |
| Microdia Integrated Camera                          | 2         | 0.91%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 2         | 0.91%   |
| Logitech StreamCam                                  | 2         | 0.91%   |
| Logitech QuickCam Pro 9000                          | 2         | 0.91%   |
| Lite-On HP HD Webcam                                | 2         | 0.91%   |
| Lite-On HP HD Camera                                | 2         | 0.91%   |
| Chicony USB2.0 HD UVC WebCam                        | 2         | 0.91%   |
| Chicony USB2.0 Camera                               | 2         | 0.91%   |
| Chicony EasyCamera                                  | 2         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP Webcam    | 2         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP IR Camera | 2         | 0.91%   |
| Cheng Uei Precision Industry (Foxlink) HP HD Webcam | 2         | 0.91%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 12        | 38.71%  |
| Synaptics                          | 8         | 25.81%  |
| Elan Microelectronics              | 5         | 16.13%  |
| Shenzhen Goodix Technology         | 4         | 12.9%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 6.45%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                           | Computers | Percent |
|-----------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                      | 6         | 19.35%  |
| Shenzhen Goodix  Fingerprint Device                             | 3         | 9.68%   |
| Elan ELAN:Fingerprint                                           | 3         | 9.68%   |
| Validity Sensors VFS 5011 fingerprint sensor                    | 2         | 6.45%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor     | 2         | 6.45%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader               | 2         | 6.45%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device | 2         | 6.45%   |
| Elan ELAN:ARM-M4                                                | 2         | 6.45%   |
| Validity Sensors Synaptics WBDI                                 | 1         | 3.23%   |
| Validity Sensors Swipe Fingerprint Sensor                       | 1         | 3.23%   |
| Synaptics WBDI Device                                           | 1         | 3.23%   |
| Synaptics UWP WBDI Device                                       | 1         | 3.23%   |
| Synaptics UWP WBDI                                              | 1         | 3.23%   |
| Synaptics  WBDI                                                 | 1         | 3.23%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint      | 1         | 3.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                | 1         | 3.23%   |
| Shenzhen Goodix Fingerprint Reader                              | 1         | 3.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 57.14%  |
| Broadcom              | 2         | 28.57%  |
| Realtek Semiconductor | 1         | 14.29%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 57.14%  |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 14.29%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 14.29%  |
| Broadcom 5880                                                                | 1         | 14.29%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 313       | 74.17%  |
| 1     | 88        | 20.85%  |
| 2     | 19        | 4.5%    |
| 3     | 2         | 0.47%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Net/wireless             | 36        | 27.48%  |
| Graphics card            | 36        | 27.48%  |
| Fingerprint reader       | 31        | 23.66%  |
| Multimedia controller    | 18        | 13.74%  |
| Unassigned class         | 2         | 1.53%   |
| Communication controller | 2         | 1.53%   |
| Bluetooth                | 2         | 1.53%   |
| Sound                    | 1         | 0.76%   |
| Modem                    | 1         | 0.76%   |
| Chipcard                 | 1         | 0.76%   |
| Camera                   | 1         | 0.76%   |

