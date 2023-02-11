Debian - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Debian.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Debian/Desktop/README.md) and [notebooks](/Dist/Debian/Notebook/README.md).

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

Total: 12021

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Apple         | MacBookAir7,2               | Notebook    | [352c998936](https://linux-hardware.org/?probe=352c998936) | Feb 01, 2023 |
| Toshiba       | Satellite P775              | Notebook    | [c03f7668ac](https://linux-hardware.org/?probe=c03f7668ac) | Feb 01, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | Notebook    | [ac78478b3b](https://linux-hardware.org/?probe=ac78478b3b) | Feb 01, 2023 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [2f0a18ba6b](https://linux-hardware.org/?probe=2f0a18ba6b) | Feb 01, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [01e8662b39](https://linux-hardware.org/?probe=01e8662b39) | Feb 01, 2023 |
| Gigabyte      | X299 AORUS Gaming 3-CF      | Desktop     | [775a993b3a](https://linux-hardware.org/?probe=775a993b3a) | Feb 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [142f5fcb2d](https://linux-hardware.org/?probe=142f5fcb2d) | Feb 01, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [81b19ff917](https://linux-hardware.org/?probe=81b19ff917) | Feb 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [f2b211ff3a](https://linux-hardware.org/?probe=f2b211ff3a) | Feb 01, 2023 |
| Gigabyte      | Z690M DS3H DDR4             | Desktop     | [8f858cb9b9](https://linux-hardware.org/?probe=8f858cb9b9) | Jan 31, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [6e8d45f76b](https://linux-hardware.org/?probe=6e8d45f76b) | Jan 31, 2023 |
| MSI           | 870A-G54                    | Desktop     | [0aaa012de5](https://linux-hardware.org/?probe=0aaa012de5) | Jan 31, 2023 |
| HP            | Notebook                    | Notebook    | [3cea0a0519](https://linux-hardware.org/?probe=3cea0a0519) | Jan 31, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [daa9bd48c8](https://linux-hardware.org/?probe=daa9bd48c8) | Jan 31, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [7e25d19fae](https://linux-hardware.org/?probe=7e25d19fae) | Jan 31, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a2c87504d6](https://linux-hardware.org/?probe=a2c87504d6) | Jan 31, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [1c798340db](https://linux-hardware.org/?probe=1c798340db) | Jan 31, 2023 |
| ASRock        | G31M-VS2                    | Desktop     | [e12dd528ea](https://linux-hardware.org/?probe=e12dd528ea) | Jan 31, 2023 |
| MSI           | H81M-E34                    | Desktop     | [19b8f90522](https://linux-hardware.org/?probe=19b8f90522) | Jan 31, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d8f44aeb4c](https://linux-hardware.org/?probe=d8f44aeb4c) | Jan 31, 2023 |
| ASUSTek       | PRIME B250-A                | Desktop     | [c686d3d123](https://linux-hardware.org/?probe=c686d3d123) | Jan 31, 2023 |
| ASRock        | X570 Pro4                   | Desktop     | [37999411ed](https://linux-hardware.org/?probe=37999411ed) | Jan 31, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [35948f3b5e](https://linux-hardware.org/?probe=35948f3b5e) | Jan 31, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [011c3940f9](https://linux-hardware.org/?probe=011c3940f9) | Jan 31, 2023 |
| Dell          | Inspiron 5485 2n1           | Convertible | [e335e7282d](https://linux-hardware.org/?probe=e335e7282d) | Jan 30, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [3f17be7a85](https://linux-hardware.org/?probe=3f17be7a85) | Jan 30, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [ed57a59e39](https://linux-hardware.org/?probe=ed57a59e39) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [b6a73bd22e](https://linux-hardware.org/?probe=b6a73bd22e) | Jan 30, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [3ecd91770e](https://linux-hardware.org/?probe=3ecd91770e) | Jan 30, 2023 |
| ASUSTek       | H61M-A/BR                   | Desktop     | [0ae96c2bbc](https://linux-hardware.org/?probe=0ae96c2bbc) | Jan 30, 2023 |
| NetGear       | ReadyDATA 5200              | Desktop     | [74a68eba33](https://linux-hardware.org/?probe=74a68eba33) | Jan 30, 2023 |
| ASUSTek       | P8H61-MX                    | Desktop     | [f13f4da766](https://linux-hardware.org/?probe=f13f4da766) | Jan 30, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [79e7fde988](https://linux-hardware.org/?probe=79e7fde988) | Jan 30, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [d86a1c4fb2](https://linux-hardware.org/?probe=d86a1c4fb2) | Jan 30, 2023 |
| MSI           | GE60 0NC/GE60 0ND           | Notebook    | [a7ef98ea02](https://linux-hardware.org/?probe=a7ef98ea02) | Jan 30, 2023 |
| HP            | 0A64h                       | Desktop     | [da7b36ad47](https://linux-hardware.org/?probe=da7b36ad47) | Jan 30, 2023 |
| Acer          | Aspire 5552                 | Notebook    | [f1168775a7](https://linux-hardware.org/?probe=f1168775a7) | Jan 30, 2023 |
| Sony          | PCG-Z1VA(UC)                | Notebook    | [db4f48132e](https://linux-hardware.org/?probe=db4f48132e) | Jan 29, 2023 |
| Dell          | 02YRK5 A02                  | Desktop     | [d6faeebd74](https://linux-hardware.org/?probe=d6faeebd74) | Jan 29, 2023 |
| Gigabyte      | Z270X-Ultra Gaming-CF       | Desktop     | [55c3e9597c](https://linux-hardware.org/?probe=55c3e9597c) | Jan 29, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [933e5a5b96](https://linux-hardware.org/?probe=933e5a5b96) | Jan 29, 2023 |
| ASUSTek       | ROG Maximus XIII HERO       | Desktop     | [6b634c85e8](https://linux-hardware.org/?probe=6b634c85e8) | Jan 29, 2023 |
| ASUSTek       | P8H67                       | Desktop     | [c6163491b5](https://linux-hardware.org/?probe=c6163491b5) | Jan 29, 2023 |
| Medion        | TJ4125                      | Desktop     | [5fb5d01ae9](https://linux-hardware.org/?probe=5fb5d01ae9) | Jan 29, 2023 |
| Gigabyte      | 8IPE1000-G/L                | Desktop     | [6f83e8b57d](https://linux-hardware.org/?probe=6f83e8b57d) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [7017fcf775](https://linux-hardware.org/?probe=7017fcf775) | Jan 29, 2023 |
| Lenovo        | S21e-20 80M4                | Notebook    | [9afa780018](https://linux-hardware.org/?probe=9afa780018) | Jan 29, 2023 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [eb551b5ec0](https://linux-hardware.org/?probe=eb551b5ec0) | Jan 29, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [e91c24c3f9](https://linux-hardware.org/?probe=e91c24c3f9) | Jan 29, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [351106d7e5](https://linux-hardware.org/?probe=351106d7e5) | Jan 29, 2023 |
| Lenovo        | ThinkPad X220 42915CG       | Notebook    | [d058eeaad5](https://linux-hardware.org/?probe=d058eeaad5) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | Desktop     | [8227150e0d](https://linux-hardware.org/?probe=8227150e0d) | Jan 29, 2023 |
| Apple         | Mac-F2238BAE iMac11,3       | All in one  | [03171e1e33](https://linux-hardware.org/?probe=03171e1e33) | Jan 29, 2023 |
| Gigabyte      | M61PME-S2                   | Desktop     | [813f01976d](https://linux-hardware.org/?probe=813f01976d) | Jan 29, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [eaed78d213](https://linux-hardware.org/?probe=eaed78d213) | Jan 28, 2023 |
| Dell          | 0F8098                      | Desktop     | [d6066c739e](https://linux-hardware.org/?probe=d6066c739e) | Jan 28, 2023 |
| HP            | ZBook 17 G3                 | Notebook    | [a1b5cdf1db](https://linux-hardware.org/?probe=a1b5cdf1db) | Jan 28, 2023 |
| Gigabyte      | Z97M-DS3H                   | Desktop     | [e9fc2c87df](https://linux-hardware.org/?probe=e9fc2c87df) | Jan 28, 2023 |
| ASRock        | B550 Pro4                   | Desktop     | [5fa28ba14d](https://linux-hardware.org/?probe=5fa28ba14d) | Jan 28, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a88e343a83](https://linux-hardware.org/?probe=a88e343a83) | Jan 28, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [6e55ab69b8](https://linux-hardware.org/?probe=6e55ab69b8) | Jan 28, 2023 |
| Dell          | 05MW5F A00                  | Mini pc     | [dd56d67fef](https://linux-hardware.org/?probe=dd56d67fef) | Jan 28, 2023 |
| ASUSTek       | UX410UAR                    | Notebook    | [e9ac16c8ef](https://linux-hardware.org/?probe=e9ac16c8ef) | Jan 28, 2023 |
| HP            | 1998                        | Desktop     | [81da484cc4](https://linux-hardware.org/?probe=81da484cc4) | Jan 28, 2023 |
| Dell          | Inspiron 3581               | Notebook    | [8c8db10ac2](https://linux-hardware.org/?probe=8c8db10ac2) | Jan 28, 2023 |
| HP            | ProBook 430 G6              | Notebook    | [24fd7df5b6](https://linux-hardware.org/?probe=24fd7df5b6) | Jan 28, 2023 |
| HP            | EliteBook 640 14 inch G9... | Notebook    | [bbdf827cef](https://linux-hardware.org/?probe=bbdf827cef) | Jan 27, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [0b05244a15](https://linux-hardware.org/?probe=0b05244a15) | Jan 27, 2023 |
| Dell          | Latitude E7440              | Notebook    | [9ba078f6ab](https://linux-hardware.org/?probe=9ba078f6ab) | Jan 27, 2023 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [8ef4f014f2](https://linux-hardware.org/?probe=8ef4f014f2) | Jan 27, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [c83903fdc8](https://linux-hardware.org/?probe=c83903fdc8) | Jan 27, 2023 |
| Lenovo        | B570e HuronRiver Platfor... | Notebook    | [376c580dcb](https://linux-hardware.org/?probe=376c580dcb) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [d3adeb692c](https://linux-hardware.org/?probe=d3adeb692c) | Jan 27, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [4a83dc2dc2](https://linux-hardware.org/?probe=4a83dc2dc2) | Jan 27, 2023 |
| MSI           | B365M PRO-VDH               | Desktop     | [d5bbfc18d5](https://linux-hardware.org/?probe=d5bbfc18d5) | Jan 27, 2023 |
| Lenovo        | ThinkPad E560 20EVCTO1WW    | Notebook    | [46b1227255](https://linux-hardware.org/?probe=46b1227255) | Jan 27, 2023 |
| Supermicro    | M11SDV-8C-LN4F              | Server      | [e01e49f162](https://linux-hardware.org/?probe=e01e49f162) | Jan 27, 2023 |
| MSI           | Creator 17 B11UE            | Notebook    | [fcf56cfe4d](https://linux-hardware.org/?probe=fcf56cfe4d) | Jan 27, 2023 |
| Dell          | Latitude 5420               | Notebook    | [379a2dc9ab](https://linux-hardware.org/?probe=379a2dc9ab) | Jan 26, 2023 |
| Dell          | Latitude 5420               | Notebook    | [eec8ef8ddb](https://linux-hardware.org/?probe=eec8ef8ddb) | Jan 26, 2023 |
| Lenovo        | ThinkPad T440 20B7S0JC0P    | Notebook    | [1a36af70e8](https://linux-hardware.org/?probe=1a36af70e8) | Jan 26, 2023 |
| Google        | Careena                     | Notebook    | [75ca1a25dd](https://linux-hardware.org/?probe=75ca1a25dd) | Jan 26, 2023 |
| AZW           | MINI S                      | Desktop     | [ce5e6b1504](https://linux-hardware.org/?probe=ce5e6b1504) | Jan 26, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [d632bd0c9f](https://linux-hardware.org/?probe=d632bd0c9f) | Jan 26, 2023 |
| ASUSTek       | Pro WS X570-ACE             | Desktop     | [0093f9df93](https://linux-hardware.org/?probe=0093f9df93) | Jan 26, 2023 |
| HP            | 805D                        | Desktop     | [b1996094a9](https://linux-hardware.org/?probe=b1996094a9) | Jan 26, 2023 |
| Inventec      | D CLASS A02                 | Desktop     | [2e70086887](https://linux-hardware.org/?probe=2e70086887) | Jan 25, 2023 |
| ASUSTek       | P8H61-M LX2                 | Desktop     | [dee0143024](https://linux-hardware.org/?probe=dee0143024) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [a780c8d844](https://linux-hardware.org/?probe=a780c8d844) | Jan 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [e6a1506275](https://linux-hardware.org/?probe=e6a1506275) | Jan 25, 2023 |
| Apple         | MacBookPro10,1              | Notebook    | [4643f751cf](https://linux-hardware.org/?probe=4643f751cf) | Jan 25, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [3b96eac8a9](https://linux-hardware.org/?probe=3b96eac8a9) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [90d383c54e](https://linux-hardware.org/?probe=90d383c54e) | Jan 25, 2023 |
| ASUSTek       | H110M-R                     | Desktop     | [e4b50b33a2](https://linux-hardware.org/?probe=e4b50b33a2) | Jan 25, 2023 |
| MSI           | H110M PRO-VD                | Desktop     | [e0eefbde94](https://linux-hardware.org/?probe=e0eefbde94) | Jan 25, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [e2d354b9c5](https://linux-hardware.org/?probe=e2d354b9c5) | Jan 25, 2023 |
| Panasonic     | FZ55-2                      | Notebook    | [dd9ddb12b6](https://linux-hardware.org/?probe=dd9ddb12b6) | Jan 25, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [cc41fa5174](https://linux-hardware.org/?probe=cc41fa5174) | Jan 25, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [8780aceeec](https://linux-hardware.org/?probe=8780aceeec) | Jan 25, 2023 |
| Dell          | Vostro 5470                 | Notebook    | [bfd4198155](https://linux-hardware.org/?probe=bfd4198155) | Jan 25, 2023 |
| Samsung       | R710                        | Notebook    | [17a3e2ddd9](https://linux-hardware.org/?probe=17a3e2ddd9) | Jan 25, 2023 |
| Dell          | 0K3CM7 A00                  | Desktop     | [d3cc219bf7](https://linux-hardware.org/?probe=d3cc219bf7) | Jan 24, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [0bde1ca99a](https://linux-hardware.org/?probe=0bde1ca99a) | Jan 24, 2023 |
| MSI           | H97 PC Mate                 | Desktop     | [d00ec3c042](https://linux-hardware.org/?probe=d00ec3c042) | Jan 24, 2023 |
| Packard Be... | EasyNote MH36               | Notebook    | [07ba548a55](https://linux-hardware.org/?probe=07ba548a55) | Jan 24, 2023 |
| BESSTAR Te... | Cherry Trail CR             | Mini pc     | [9ac0bac56e](https://linux-hardware.org/?probe=9ac0bac56e) | Jan 24, 2023 |
| ECS           | G31T-M9                     | Desktop     | [59747c81ca](https://linux-hardware.org/?probe=59747c81ca) | Jan 24, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [fe1a2d7fc6](https://linux-hardware.org/?probe=fe1a2d7fc6) | Jan 24, 2023 |
| HP            | 82B4                        | Desktop     | [29e2d03c1a](https://linux-hardware.org/?probe=29e2d03c1a) | Jan 24, 2023 |
| HP            | 82B4                        | Desktop     | [3df98736a1](https://linux-hardware.org/?probe=3df98736a1) | Jan 24, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [bf21a44322](https://linux-hardware.org/?probe=bf21a44322) | Jan 23, 2023 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [fd6d2ec3c2](https://linux-hardware.org/?probe=fd6d2ec3c2) | Jan 23, 2023 |
| Samsung       | 300E4A/300E5A/300E7A        | Notebook    | [c8ec385a88](https://linux-hardware.org/?probe=c8ec385a88) | Jan 23, 2023 |
| ASRock        | 990FX Killer                | Desktop     | [b6bd3a3bdb](https://linux-hardware.org/?probe=b6bd3a3bdb) | Jan 23, 2023 |
| MSI           | 870A-G54                    | Desktop     | [b1baf04990](https://linux-hardware.org/?probe=b1baf04990) | Jan 23, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [5648fbf4a0](https://linux-hardware.org/?probe=5648fbf4a0) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X415... | Notebook    | [62ac206f7e](https://linux-hardware.org/?probe=62ac206f7e) | Jan 23, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [3f3b6c888d](https://linux-hardware.org/?probe=3f3b6c888d) | Jan 23, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [69164f2a61](https://linux-hardware.org/?probe=69164f2a61) | Jan 23, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7f0c7e0be](https://linux-hardware.org/?probe=e7f0c7e0be) | Jan 23, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E510... | Notebook    | [5c7625e3f8](https://linux-hardware.org/?probe=5c7625e3f8) | Jan 23, 2023 |
| Supermicro    | X9DRD-iF                    | Server      | [c088868f62](https://linux-hardware.org/?probe=c088868f62) | Jan 22, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [ff727a3560](https://linux-hardware.org/?probe=ff727a3560) | Jan 22, 2023 |
| Fujitsu       | LIFEBOOK S751               | Notebook    | [df0676ac87](https://linux-hardware.org/?probe=df0676ac87) | Jan 22, 2023 |
| ASUSTek       | PRIME X399-A                | Desktop     | [4687e8d062](https://linux-hardware.org/?probe=4687e8d062) | Jan 22, 2023 |
| Intel         | JSL MRD                     | Desktop     | [39dc5a7f96](https://linux-hardware.org/?probe=39dc5a7f96) | Jan 22, 2023 |
| Lenovo        | ThinkCentre M57e 7066W57    | Desktop     | [3ddcdbb616](https://linux-hardware.org/?probe=3ddcdbb616) | Jan 22, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop K350... | Notebook    | [ae270718a7](https://linux-hardware.org/?probe=ae270718a7) | Jan 22, 2023 |
| MSI           | B350 TOMAHAWK               | Desktop     | [91ef58d8a0](https://linux-hardware.org/?probe=91ef58d8a0) | Jan 22, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7afed6351](https://linux-hardware.org/?probe=e7afed6351) | Jan 22, 2023 |
| Dell          | G3 3579                     | Notebook    | [63298dcee9](https://linux-hardware.org/?probe=63298dcee9) | Jan 22, 2023 |
| Danew         | Dbook 131                   | Notebook    | [08911c133e](https://linux-hardware.org/?probe=08911c133e) | Jan 22, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [0c65146f4c](https://linux-hardware.org/?probe=0c65146f4c) | Jan 21, 2023 |
| Dell          | 0KRC95 A02                  | Desktop     | [ef532b60e6](https://linux-hardware.org/?probe=ef532b60e6) | Jan 21, 2023 |
| Clevo         | W150ER                      | Notebook    | [ba5d06437c](https://linux-hardware.org/?probe=ba5d06437c) | Jan 21, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [68847eb1e6](https://linux-hardware.org/?probe=68847eb1e6) | Jan 21, 2023 |
| Biostar       | H310MHP                     | Desktop     | [21de314a44](https://linux-hardware.org/?probe=21de314a44) | Jan 21, 2023 |
| ASUSTek       | H170I-PLUS D3               | Desktop     | [b8d373b07e](https://linux-hardware.org/?probe=b8d373b07e) | Jan 21, 2023 |
| ASRock        | H61M-VG3                    | Desktop     | [c9d6e1cbb1](https://linux-hardware.org/?probe=c9d6e1cbb1) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [4b9d2e6e26](https://linux-hardware.org/?probe=4b9d2e6e26) | Jan 21, 2023 |
| Lenovo        | Yoga Slim 7 ProX 14ARH7 ... | Notebook    | [15dde971f3](https://linux-hardware.org/?probe=15dde971f3) | Jan 21, 2023 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [f5bb76ae13](https://linux-hardware.org/?probe=f5bb76ae13) | Jan 21, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [e7f94d5172](https://linux-hardware.org/?probe=e7f94d5172) | Jan 21, 2023 |
| ASUSTek       | TUF Gaming B450M-PRO S      | Desktop     | [046504c970](https://linux-hardware.org/?probe=046504c970) | Jan 21, 2023 |
| DFI           | CR101-CST                   | Desktop     | [604ce5b10f](https://linux-hardware.org/?probe=604ce5b10f) | Jan 21, 2023 |
| Google        | Phaser                      | Notebook    | [557e69c5f1](https://linux-hardware.org/?probe=557e69c5f1) | Jan 21, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [82b95a8f4e](https://linux-hardware.org/?probe=82b95a8f4e) | Jan 21, 2023 |
| Dell          | 00TD00 A00                  | All in one  | [8d09088848](https://linux-hardware.org/?probe=8d09088848) | Jan 21, 2023 |
| HP            | EliteBook Folio 9480m       | Notebook    | [cf1b67c224](https://linux-hardware.org/?probe=cf1b67c224) | Jan 21, 2023 |
| HP            | EliteBook 840 G3            | Notebook    | [06f6499264](https://linux-hardware.org/?probe=06f6499264) | Jan 21, 2023 |
| ASUSTek       | P5QL PRO                    | Desktop     | [9f700f7e19](https://linux-hardware.org/?probe=9f700f7e19) | Jan 21, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [4af2ea2f7f](https://linux-hardware.org/?probe=4af2ea2f7f) | Jan 20, 2023 |
| Dell          | 0VC8RJ X02                  | Desktop     | [313ea92e9c](https://linux-hardware.org/?probe=313ea92e9c) | Jan 20, 2023 |
| Gigabyte      | H410M H V2                  | Desktop     | [5767b63675](https://linux-hardware.org/?probe=5767b63675) | Jan 20, 2023 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [27e484698b](https://linux-hardware.org/?probe=27e484698b) | Jan 20, 2023 |
| Dell          | Latitude 5501               | Notebook    | [d31f972a20](https://linux-hardware.org/?probe=d31f972a20) | Jan 20, 2023 |
| Lenovo        | G505 20240                  | Notebook    | [c591d80181](https://linux-hardware.org/?probe=c591d80181) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [28e6aeb27a](https://linux-hardware.org/?probe=28e6aeb27a) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [beec5d3864](https://linux-hardware.org/?probe=beec5d3864) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [6ff84d12be](https://linux-hardware.org/?probe=6ff84d12be) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [002a38370c](https://linux-hardware.org/?probe=002a38370c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [bbfb85788c](https://linux-hardware.org/?probe=bbfb85788c) | Jan 20, 2023 |
| Gigabyte      | P85-D3                      | Desktop     | [9d6c73b1c1](https://linux-hardware.org/?probe=9d6c73b1c1) | Jan 20, 2023 |
| HP            | 3397                        | Desktop     | [39391f23c4](https://linux-hardware.org/?probe=39391f23c4) | Jan 20, 2023 |
| HP            | 3397                        | Desktop     | [7b05c1fdf9](https://linux-hardware.org/?probe=7b05c1fdf9) | Jan 20, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [b2c0017481](https://linux-hardware.org/?probe=b2c0017481) | Jan 20, 2023 |
| AZW           | SEi                         | Desktop     | [257b104c3a](https://linux-hardware.org/?probe=257b104c3a) | Jan 20, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [d77bf1f32b](https://linux-hardware.org/?probe=d77bf1f32b) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [f7cac38f4a](https://linux-hardware.org/?probe=f7cac38f4a) | Jan 20, 2023 |
| AZW           | SEi                         | Desktop     | [481932390b](https://linux-hardware.org/?probe=481932390b) | Jan 20, 2023 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [b9f1f115ba](https://linux-hardware.org/?probe=b9f1f115ba) | Jan 20, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [3447d19b00](https://linux-hardware.org/?probe=3447d19b00) | Jan 20, 2023 |
| UMAX          | VisionBook 12Wr             | Notebook    | [0707d617f7](https://linux-hardware.org/?probe=0707d617f7) | Jan 20, 2023 |
| Lenovo        | ThinkPad T490s 20NYS3SX0... | Notebook    | [3e08ab25c6](https://linux-hardware.org/?probe=3e08ab25c6) | Jan 20, 2023 |
| Dell          | Latitude E6540              | Notebook    | [34c018d211](https://linux-hardware.org/?probe=34c018d211) | Jan 20, 2023 |
| Gigabyte      | Z690I A ULTRA LITE D4       | Desktop     | [abcfca9ea7](https://linux-hardware.org/?probe=abcfca9ea7) | Jan 20, 2023 |
| TI            | OMAP3 BeagleBoard xM        | Soc         | [c081cbef0c](https://linux-hardware.org/?probe=c081cbef0c) | Jan 20, 2023 |
| Lenovo        | 7033EW4                     | Desktop     | [fd4303de2e](https://linux-hardware.org/?probe=fd4303de2e) | Jan 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop E410... | Notebook    | [80cb1c8239](https://linux-hardware.org/?probe=80cb1c8239) | Jan 19, 2023 |
| Lenovo        | IdeaPad 330S-15ARR 81FB     | Notebook    | [7ecc4d20c3](https://linux-hardware.org/?probe=7ecc4d20c3) | Jan 19, 2023 |
| Lenovo        | ThinkPad E470 20H1004SMX    | Notebook    | [0d8528f0d2](https://linux-hardware.org/?probe=0d8528f0d2) | Jan 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0efa802a32](https://linux-hardware.org/?probe=0efa802a32) | Jan 19, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [606ba17221](https://linux-hardware.org/?probe=606ba17221) | Jan 19, 2023 |
| Gigabyte      | H81M-S2V                    | Desktop     | [76be7bde5d](https://linux-hardware.org/?probe=76be7bde5d) | Jan 19, 2023 |
| ASUSTek       | P6T                         | Desktop     | [ac42d5a147](https://linux-hardware.org/?probe=ac42d5a147) | Jan 19, 2023 |
| Gigabyte      | B85M-D3V                    | Desktop     | [285dc35475](https://linux-hardware.org/?probe=285dc35475) | Jan 19, 2023 |
| Insyde        | Braswell                    | Notebook    | [18526fdbe2](https://linux-hardware.org/?probe=18526fdbe2) | Jan 19, 2023 |
| ASUSTek       | P5AD2-E-Premium             | Desktop     | [285c0f23f1](https://linux-hardware.org/?probe=285c0f23f1) | Jan 19, 2023 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [20749dc72f](https://linux-hardware.org/?probe=20749dc72f) | Jan 19, 2023 |
| HP            | Pavilion Laptop 14-dv1xx... | Notebook    | [db998abdae](https://linux-hardware.org/?probe=db998abdae) | Jan 19, 2023 |
| Fanless Mi... | Rev JSL1                    | Mini pc     | [18d521cc55](https://linux-hardware.org/?probe=18d521cc55) | Jan 19, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b6ab71a056](https://linux-hardware.org/?probe=b6ab71a056) | Jan 19, 2023 |
| ASUSTek       | ROG STRIX B650-A GAMING ... | Desktop     | [e3d0558aee](https://linux-hardware.org/?probe=e3d0558aee) | Jan 19, 2023 |
| HP            | 894F                        | Mini pc     | [a671f44480](https://linux-hardware.org/?probe=a671f44480) | Jan 19, 2023 |
| Lenovo        | IdeaPad 5 14IIL05 81YH      | Notebook    | [368ed9c856](https://linux-hardware.org/?probe=368ed9c856) | Jan 18, 2023 |
| ASUSTek       | P8H61-M                     | Desktop     | [1ffe9344ff](https://linux-hardware.org/?probe=1ffe9344ff) | Jan 18, 2023 |
| Novatech      | NL40_50CU                   | Notebook    | [395dab7c43](https://linux-hardware.org/?probe=395dab7c43) | Jan 18, 2023 |
| HP            | Compaq 6910p                | Notebook    | [61d820a040](https://linux-hardware.org/?probe=61d820a040) | Jan 18, 2023 |
| Medion        | TJ4125                      | Desktop     | [b4f48c3140](https://linux-hardware.org/?probe=b4f48c3140) | Jan 18, 2023 |
| Lenovo        | 7033EW4                     | Desktop     | [df0d8cd728](https://linux-hardware.org/?probe=df0d8cd728) | Jan 18, 2023 |
| Lenovo        | Legion Y540-15IRH 81SX      | Notebook    | [7b62e27d7a](https://linux-hardware.org/?probe=7b62e27d7a) | Jan 18, 2023 |
| Lenovo        | ThinkPad T15 Gen 2i 20W5... | Notebook    | [393e6cd6d2](https://linux-hardware.org/?probe=393e6cd6d2) | Jan 18, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [84479cfc00](https://linux-hardware.org/?probe=84479cfc00) | Jan 18, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W1... | Notebook    | [6dab459ed2](https://linux-hardware.org/?probe=6dab459ed2) | Jan 18, 2023 |
| HP            | EliteBook 820 G4            | Notebook    | [430b938694](https://linux-hardware.org/?probe=430b938694) | Jan 18, 2023 |
| HP            | EliteBook 2170p             | Notebook    | [46705d578e](https://linux-hardware.org/?probe=46705d578e) | Jan 18, 2023 |
| HP            | EliteBook 840 G4            | Notebook    | [952c81c314](https://linux-hardware.org/?probe=952c81c314) | Jan 18, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [e0431daa9c](https://linux-hardware.org/?probe=e0431daa9c) | Jan 18, 2023 |
| Dell          | Latitude 5500               | Notebook    | [e0ae9cb026](https://linux-hardware.org/?probe=e0ae9cb026) | Jan 17, 2023 |
| ASRock        | A300M-STX                   | Desktop     | [4d726dcf9b](https://linux-hardware.org/?probe=4d726dcf9b) | Jan 17, 2023 |
| Huanan        | B75 V10.1 376               | Desktop     | [2703c87348](https://linux-hardware.org/?probe=2703c87348) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [99e10e5d0f](https://linux-hardware.org/?probe=99e10e5d0f) | Jan 17, 2023 |
| Lenovo        | ThinkPad X61 Tablet 7767... | Notebook    | [624f47d1e3](https://linux-hardware.org/?probe=624f47d1e3) | Jan 17, 2023 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [f9f926e910](https://linux-hardware.org/?probe=f9f926e910) | Jan 17, 2023 |
| MSI           | H81M-E34                    | Desktop     | [db4a6791a0](https://linux-hardware.org/?probe=db4a6791a0) | Jan 17, 2023 |
| ASUSTek       | P5G41T-M LE                 | Desktop     | [31b369770d](https://linux-hardware.org/?probe=31b369770d) | Jan 17, 2023 |
| Foxconn       | nT-A3000 series FAB         | Desktop     | [0bdefb0a4f](https://linux-hardware.org/?probe=0bdefb0a4f) | Jan 17, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a35e962cca](https://linux-hardware.org/?probe=a35e962cca) | Jan 17, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [7688ac4ec1](https://linux-hardware.org/?probe=7688ac4ec1) | Jan 17, 2023 |
| HP            | Compaq 6730b (GW687AV)      | Notebook    | [e967b291d5](https://linux-hardware.org/?probe=e967b291d5) | Jan 17, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [43c4f532aa](https://linux-hardware.org/?probe=43c4f532aa) | Jan 17, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [a279a876f3](https://linux-hardware.org/?probe=a279a876f3) | Jan 17, 2023 |
| ASUSTek       | M2N-SLI DELUXE              | Desktop     | [d31aea19b2](https://linux-hardware.org/?probe=d31aea19b2) | Jan 16, 2023 |
| Lenovo        | IdeaPad 3 14ARE05 81W3      | Notebook    | [804fe39b80](https://linux-hardware.org/?probe=804fe39b80) | Jan 16, 2023 |
| Intel         | DH67BL AAG10189-206         | Desktop     | [23e07704eb](https://linux-hardware.org/?probe=23e07704eb) | Jan 16, 2023 |
| Positivo      | CHT14B                      | Notebook    | [ab4518f121](https://linux-hardware.org/?probe=ab4518f121) | Jan 16, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [020e19b05d](https://linux-hardware.org/?probe=020e19b05d) | Jan 16, 2023 |
| Lenovo        | ThinkPad T490s 20NX0076M... | Notebook    | [4c896e2c0e](https://linux-hardware.org/?probe=4c896e2c0e) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [6746dfae39](https://linux-hardware.org/?probe=6746dfae39) | Jan 16, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [976f23d99e](https://linux-hardware.org/?probe=976f23d99e) | Jan 16, 2023 |
| Radxa         | ROCK 5B                     | Soc         | [e187058616](https://linux-hardware.org/?probe=e187058616) | Jan 16, 2023 |
| Dell          | Inspiron 5502               | Notebook    | [9403074843](https://linux-hardware.org/?probe=9403074843) | Jan 16, 2023 |
| Intel         | JSL MRD                     | Desktop     | [edbaf7bb5d](https://linux-hardware.org/?probe=edbaf7bb5d) | Jan 16, 2023 |
| Lenovo        | 370A SDK0J40697 WIN 3305... | Desktop     | [deb2b560bc](https://linux-hardware.org/?probe=deb2b560bc) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [47d090108d](https://linux-hardware.org/?probe=47d090108d) | Jan 16, 2023 |
| ASRock        | J3455-ITX                   | Desktop     | [457c7ea5a4](https://linux-hardware.org/?probe=457c7ea5a4) | Jan 16, 2023 |
| Intel         | DH77EB AAG39073-304         | Desktop     | [cb3c4b1eb4](https://linux-hardware.org/?probe=cb3c4b1eb4) | Jan 16, 2023 |
| HP            | 8643 SMVB                   | Desktop     | [4572999070](https://linux-hardware.org/?probe=4572999070) | Jan 16, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [219091b4e0](https://linux-hardware.org/?probe=219091b4e0) | Jan 15, 2023 |
| Lenovo        | IdeaPad 510-15IKB 80SV      | Notebook    | [a09ace045e](https://linux-hardware.org/?probe=a09ace045e) | Jan 15, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [3b4a530695](https://linux-hardware.org/?probe=3b4a530695) | Jan 15, 2023 |
| Apple         | MacBookAir5,1               | Notebook    | [f316bddcf2](https://linux-hardware.org/?probe=f316bddcf2) | Jan 15, 2023 |
| Acer          | Swift SF314-510G            | Notebook    | [b929f53536](https://linux-hardware.org/?probe=b929f53536) | Jan 15, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [5426686264](https://linux-hardware.org/?probe=5426686264) | Jan 15, 2023 |
| MSI           | MS-B1711                    | Desktop     | [730b1e7f90](https://linux-hardware.org/?probe=730b1e7f90) | Jan 15, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [0ec206a07d](https://linux-hardware.org/?probe=0ec206a07d) | Jan 15, 2023 |
| HP            | EliteBook 8570w             | Notebook    | [53eb92efda](https://linux-hardware.org/?probe=53eb92efda) | Jan 15, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [202535bce7](https://linux-hardware.org/?probe=202535bce7) | Jan 15, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [ab5933911d](https://linux-hardware.org/?probe=ab5933911d) | Jan 15, 2023 |
| Lenovo        | ThinkPad T470 20HES0MV00    | Notebook    | [7e3b019181](https://linux-hardware.org/?probe=7e3b019181) | Jan 14, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7d44980bca](https://linux-hardware.org/?probe=7d44980bca) | Jan 14, 2023 |
| Lenovo        | ThinkPad W520 4284W2U       | Notebook    | [576a509224](https://linux-hardware.org/?probe=576a509224) | Jan 14, 2023 |
| Dell          | 00TD00 A00                  | All in one  | [d63c9ca908](https://linux-hardware.org/?probe=d63c9ca908) | Jan 14, 2023 |
| Dell          | 00TD00 A00                  | All in one  | [80db2b0301](https://linux-hardware.org/?probe=80db2b0301) | Jan 14, 2023 |
| HP            | Laptop 14s-dk0xxx           | Notebook    | [6efb68b8da](https://linux-hardware.org/?probe=6efb68b8da) | Jan 14, 2023 |
| Lenovo        | IdeaPad 110S-11IBR 80WG     | Notebook    | [0899d995dd](https://linux-hardware.org/?probe=0899d995dd) | Jan 14, 2023 |
| ASUSTek       | TUF Gaming B460M-PLUS       | Desktop     | [d1e2f08907](https://linux-hardware.org/?probe=d1e2f08907) | Jan 14, 2023 |
| Radxa         | ROCK Pi 4B                  | Soc         | [0533348a3f](https://linux-hardware.org/?probe=0533348a3f) | Jan 14, 2023 |
| Apple         | MacBookPro12,1              | Notebook    | [1402c185c7](https://linux-hardware.org/?probe=1402c185c7) | Jan 14, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [f862a7e702](https://linux-hardware.org/?probe=f862a7e702) | Jan 14, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [df889b6674](https://linux-hardware.org/?probe=df889b6674) | Jan 14, 2023 |
| HONOR         | HLYL-WXX9                   | Notebook    | [e5b02d94cd](https://linux-hardware.org/?probe=e5b02d94cd) | Jan 14, 2023 |
| Dell          | Inspiron 11 - 3147          | Notebook    | [7193100d05](https://linux-hardware.org/?probe=7193100d05) | Jan 14, 2023 |
| HP            | Pavilion g6                 | Notebook    | [7672e1178a](https://linux-hardware.org/?probe=7672e1178a) | Jan 14, 2023 |
| Panasonic     | CFSZ6-2                     | Notebook    | [7a9f534294](https://linux-hardware.org/?probe=7a9f534294) | Jan 13, 2023 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [8a79dd9e27](https://linux-hardware.org/?probe=8a79dd9e27) | Jan 13, 2023 |
| ASRock        | H110M-HDV R3.0              | Desktop     | [bed628ce8a](https://linux-hardware.org/?probe=bed628ce8a) | Jan 13, 2023 |
| Lenovo        | ThinkCentre M58p 6234A1U    | Desktop     | [63d74a9021](https://linux-hardware.org/?probe=63d74a9021) | Jan 13, 2023 |
| MSI           | PRO X670-P WIFI             | Desktop     | [8cffa1360f](https://linux-hardware.org/?probe=8cffa1360f) | Jan 13, 2023 |
| ASRock        | 970M Pro3                   | Desktop     | [ed62a9383e](https://linux-hardware.org/?probe=ed62a9383e) | Jan 13, 2023 |
| Unknown       | Unknown                     | Notebook    | [ce69bfd81b](https://linux-hardware.org/?probe=ce69bfd81b) | Jan 13, 2023 |
| Medion        | TJ4125                      | Desktop     | [700f862aa6](https://linux-hardware.org/?probe=700f862aa6) | Jan 13, 2023 |
| HC            | HCAR357-MI V1.0             | Desktop     | [516f1ed052](https://linux-hardware.org/?probe=516f1ed052) | Jan 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [810b866ee4](https://linux-hardware.org/?probe=810b866ee4) | Jan 13, 2023 |
| HP            | ProBook 445 G7              | Notebook    | [baf20b6914](https://linux-hardware.org/?probe=baf20b6914) | Jan 13, 2023 |
| Lenovo        | ThinkPad L390 Yoga 20NTC... | Convertible | [03e4d52b2d](https://linux-hardware.org/?probe=03e4d52b2d) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | Desktop     | [56ee8713e8](https://linux-hardware.org/?probe=56ee8713e8) | Jan 13, 2023 |
| Vestel        | 14MB24A                     | Desktop     | [02c99c8c38](https://linux-hardware.org/?probe=02c99c8c38) | Jan 13, 2023 |
| ASUSTek       | Q325UA                      | Convertible | [1862534df3](https://linux-hardware.org/?probe=1862534df3) | Jan 13, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [efeae454c8](https://linux-hardware.org/?probe=efeae454c8) | Jan 13, 2023 |
| ASUSTek       | PRIME Z790-P                | Desktop     | [a4fb531cc9](https://linux-hardware.org/?probe=a4fb531cc9) | Jan 13, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [07a70b62af](https://linux-hardware.org/?probe=07a70b62af) | Jan 13, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [d7c612580f](https://linux-hardware.org/?probe=d7c612580f) | Jan 13, 2023 |
| ASUSTek       | X450LD                      | Notebook    | [859eb05149](https://linux-hardware.org/?probe=859eb05149) | Jan 13, 2023 |
| Dell          | Latitude 3320               | Notebook    | [f10d2a0741](https://linux-hardware.org/?probe=f10d2a0741) | Jan 13, 2023 |
| Dell          | Latitude 3320               | Notebook    | [613d7d50eb](https://linux-hardware.org/?probe=613d7d50eb) | Jan 13, 2023 |
| AZW           | Green G3                    | Desktop     | [be99013601](https://linux-hardware.org/?probe=be99013601) | Jan 13, 2023 |
| Chuwi         | UBook Pro                   | Tablet      | [b756ec6728](https://linux-hardware.org/?probe=b756ec6728) | Jan 12, 2023 |
| HP            | 21EF                        | Desktop     | [0d5e3a9354](https://linux-hardware.org/?probe=0d5e3a9354) | Jan 12, 2023 |
| HP            | 21EF                        | Desktop     | [cdeab03273](https://linux-hardware.org/?probe=cdeab03273) | Jan 12, 2023 |
| HP            | Compaq 6735b                | Notebook    | [01878ee027](https://linux-hardware.org/?probe=01878ee027) | Jan 12, 2023 |
| Dell          | Inspiron 3521               | Notebook    | [694d5be301](https://linux-hardware.org/?probe=694d5be301) | Jan 12, 2023 |
| ASUSTek       | P5G41T-M LX V2              | Desktop     | [36a8e226c5](https://linux-hardware.org/?probe=36a8e226c5) | Jan 12, 2023 |
| ASUSTek       | PRIME Z690M-PLUS D4         | Desktop     | [4687ae7d43](https://linux-hardware.org/?probe=4687ae7d43) | Jan 12, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [bb85f0bdc7](https://linux-hardware.org/?probe=bb85f0bdc7) | Jan 12, 2023 |
| Lenovo        | ThinkPad T460 20FMA0APAR    | Notebook    | [d4691b9969](https://linux-hardware.org/?probe=d4691b9969) | Jan 12, 2023 |
| Lenovo        | IdeaPad Z570 HuronRiver ... | Notebook    | [2316d5dc8b](https://linux-hardware.org/?probe=2316d5dc8b) | Jan 12, 2023 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | Notebook    | [856d91c1ca](https://linux-hardware.org/?probe=856d91c1ca) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [d93218978e](https://linux-hardware.org/?probe=d93218978e) | Jan 12, 2023 |
| MSI           | B350 PC MATE                | Desktop     | [f235ff785b](https://linux-hardware.org/?probe=f235ff785b) | Jan 12, 2023 |
| Dell          | 0KM5PX A06                  | Server      | [63b5c2f7fb](https://linux-hardware.org/?probe=63b5c2f7fb) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [25bd789598](https://linux-hardware.org/?probe=25bd789598) | Jan 12, 2023 |
| ASUSTek       | ROG STRIX Z390-E GAMING     | Desktop     | [c040acffcf](https://linux-hardware.org/?probe=c040acffcf) | Jan 12, 2023 |
| Gateway       | M-6854m                     | Notebook    | [76f293b62b](https://linux-hardware.org/?probe=76f293b62b) | Jan 12, 2023 |
| Dell          | Precision M4400             | Notebook    | [27da7825fb](https://linux-hardware.org/?probe=27da7825fb) | Jan 12, 2023 |
| AMI           | Aptio CRB                   | Mini pc     | [32acfb0bee](https://linux-hardware.org/?probe=32acfb0bee) | Jan 12, 2023 |
| Dell          | Inspiron 3421               | Notebook    | [055d61383e](https://linux-hardware.org/?probe=055d61383e) | Jan 12, 2023 |
| Microsoft     | Surface Pro 3               | Tablet      | [0001dd4164](https://linux-hardware.org/?probe=0001dd4164) | Jan 12, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [ba153350d8](https://linux-hardware.org/?probe=ba153350d8) | Jan 11, 2023 |
| ASRock        | X300-ITX                    | Desktop     | [9e74676ba4](https://linux-hardware.org/?probe=9e74676ba4) | Jan 11, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [b60a38ae60](https://linux-hardware.org/?probe=b60a38ae60) | Jan 11, 2023 |
| Gigabyte      | X570 GAMING X               | Desktop     | [204a5e8a8e](https://linux-hardware.org/?probe=204a5e8a8e) | Jan 11, 2023 |
| Acer          | Swift SF314-56              | Notebook    | [46aebbe972](https://linux-hardware.org/?probe=46aebbe972) | Jan 11, 2023 |
| ASRockRack    | X470D4U2/1N1                | Desktop     | [ee2147214c](https://linux-hardware.org/?probe=ee2147214c) | Jan 11, 2023 |
| HP            | ProLiant DL360p Gen8        | Server      | [9a698e2879](https://linux-hardware.org/?probe=9a698e2879) | Jan 11, 2023 |
| Lenovo        | V110-15ISK 80TL             | Notebook    | [c00918a4c8](https://linux-hardware.org/?probe=c00918a4c8) | Jan 11, 2023 |
| SLIMBOOK      | PRO                         | Notebook    | [551a4bd378](https://linux-hardware.org/?probe=551a4bd378) | Jan 11, 2023 |
| HP            | ProBook 430 G5              | Notebook    | [6403930d67](https://linux-hardware.org/?probe=6403930d67) | Jan 11, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [6c67fc3995](https://linux-hardware.org/?probe=6c67fc3995) | Jan 11, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [54793acf7e](https://linux-hardware.org/?probe=54793acf7e) | Jan 11, 2023 |
| Intel         | NUC8BEB J72692-308          | Mini pc     | [18ca1dbf8f](https://linux-hardware.org/?probe=18ca1dbf8f) | Jan 10, 2023 |
| Aquarius      | NS585                       | Notebook    | [6fbcdf4d2f](https://linux-hardware.org/?probe=6fbcdf4d2f) | Jan 10, 2023 |
| Medion        | TJ4125                      | Desktop     | [a82000e2e9](https://linux-hardware.org/?probe=a82000e2e9) | Jan 10, 2023 |
| HP            | Mini 110-1000               | Notebook    | [05c4656700](https://linux-hardware.org/?probe=05c4656700) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [81a8002b99](https://linux-hardware.org/?probe=81a8002b99) | Jan 10, 2023 |
| SmbiosType... | SmbiosType1_SystemProduc... | Notebook    | [8367c27d81](https://linux-hardware.org/?probe=8367c27d81) | Jan 10, 2023 |
| Gigabyte      | H61M-DS2                    | Desktop     | [69ceed18f7](https://linux-hardware.org/?probe=69ceed18f7) | Jan 10, 2023 |
| Aquarius      | NS585                       | Notebook    | [2d37eb6524](https://linux-hardware.org/?probe=2d37eb6524) | Jan 10, 2023 |
| Gigabyte      | H510M H                     | Desktop     | [286d590fda](https://linux-hardware.org/?probe=286d590fda) | Jan 10, 2023 |
| MPMAN         | CONVERTER 102               | Notebook    | [cc1eb56fbc](https://linux-hardware.org/?probe=cc1eb56fbc) | Jan 10, 2023 |
| HP            | 15                          | Notebook    | [f6b287dae1](https://linux-hardware.org/?probe=f6b287dae1) | Jan 10, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [8ea20821c8](https://linux-hardware.org/?probe=8ea20821c8) | Jan 10, 2023 |
| HP            | Compaq nx9420 (ES444ET#A... | Notebook    | [8d0b4a504d](https://linux-hardware.org/?probe=8d0b4a504d) | Jan 09, 2023 |
| Acer          | Aspire A515-54G             | Notebook    | [dea6736468](https://linux-hardware.org/?probe=dea6736468) | Jan 09, 2023 |
| Lenovo        | 1059 SDK0T76538 WIN 3556... | Desktop     | [a2660dcbfb](https://linux-hardware.org/?probe=a2660dcbfb) | Jan 09, 2023 |
| Lenovo        | Yoga 520-14IKB 81C8         | Convertible | [d665a7f0ff](https://linux-hardware.org/?probe=d665a7f0ff) | Jan 09, 2023 |
| ASUSTek       | M2N-E                       | Desktop     | [2a7342c2cb](https://linux-hardware.org/?probe=2a7342c2cb) | Jan 09, 2023 |
| ASUSTek       | P8H61-MX R2.0               | Desktop     | [d5c81ffaec](https://linux-hardware.org/?probe=d5c81ffaec) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [e336a260d6](https://linux-hardware.org/?probe=e336a260d6) | Jan 09, 2023 |
| Techvision    | TVI7309X B0                 | Desktop     | [43cc06ef1d](https://linux-hardware.org/?probe=43cc06ef1d) | Jan 09, 2023 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [e85e91a7f2](https://linux-hardware.org/?probe=e85e91a7f2) | Jan 09, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [395c417f92](https://linux-hardware.org/?probe=395c417f92) | Jan 09, 2023 |
| Intel         | NUC11ATBC4 M53051-303       | Mini pc     | [fcc9b4bbcc](https://linux-hardware.org/?probe=fcc9b4bbcc) | Jan 09, 2023 |
| ASRockRack    | X470D4U                     | Desktop     | [0e51eb7caa](https://linux-hardware.org/?probe=0e51eb7caa) | Jan 09, 2023 |
| Dell          | 0HD5W2 A01                  | Desktop     | [a14e62fdf8](https://linux-hardware.org/?probe=a14e62fdf8) | Jan 09, 2023 |
| Acer          | Predator G3-710             | Desktop     | [d47ca88192](https://linux-hardware.org/?probe=d47ca88192) | Jan 09, 2023 |
| HP            | 8053                        | Desktop     | [b377deb121](https://linux-hardware.org/?probe=b377deb121) | Jan 09, 2023 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [92205d303f](https://linux-hardware.org/?probe=92205d303f) | Jan 08, 2023 |
| Gigabyte      | B365M DS3H                  | Desktop     | [0e302b3507](https://linux-hardware.org/?probe=0e302b3507) | Jan 08, 2023 |
| Acer          | Aspire one 1-131            | Notebook    | [06c3411258](https://linux-hardware.org/?probe=06c3411258) | Jan 08, 2023 |
| HP            | ZBook 15 G3                 | Notebook    | [648dcae4c6](https://linux-hardware.org/?probe=648dcae4c6) | Jan 08, 2023 |
| Tactus        | GeoFlex 110                 | Convertible | [7aed5d93ba](https://linux-hardware.org/?probe=7aed5d93ba) | Jan 08, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [76c7287e2e](https://linux-hardware.org/?probe=76c7287e2e) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [2b8206db29](https://linux-hardware.org/?probe=2b8206db29) | Jan 08, 2023 |
| Gigabyte      | X570S I AORUS PRO AX        | Desktop     | [68fe02a04c](https://linux-hardware.org/?probe=68fe02a04c) | Jan 08, 2023 |
| ASUSTek       | K53U                        | Notebook    | [63849b1b5a](https://linux-hardware.org/?probe=63849b1b5a) | Jan 08, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [a4e777ea7d](https://linux-hardware.org/?probe=a4e777ea7d) | Jan 08, 2023 |
| Digma         | Pro Fortis M DN15P3-8CXN... | Notebook    | [077fd44029](https://linux-hardware.org/?probe=077fd44029) | Jan 08, 2023 |
| Hardkernel    | Odroid XU4                  | Soc         | [2188a4a04e](https://linux-hardware.org/?probe=2188a4a04e) | Jan 07, 2023 |
| Lenovo        | ThinkPad T480s 20L8S2SX1... | Notebook    | [3c35917c78](https://linux-hardware.org/?probe=3c35917c78) | Jan 07, 2023 |
| Rockchip      | Orange Pi 5                 | Soc         | [84fc096e00](https://linux-hardware.org/?probe=84fc096e00) | Jan 07, 2023 |
| ASUSTek       | TUF Gaming B450-PLUS II     | Desktop     | [0f0b86d738](https://linux-hardware.org/?probe=0f0b86d738) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [e546680389](https://linux-hardware.org/?probe=e546680389) | Jan 07, 2023 |
| ASUSTek       | X441NA                      | Notebook    | [d556eedbbf](https://linux-hardware.org/?probe=d556eedbbf) | Jan 07, 2023 |
| Acer          | Aspire 7745G                | Notebook    | [9119962d1f](https://linux-hardware.org/?probe=9119962d1f) | Jan 07, 2023 |
| Gigabyte      | G5 GE                       | Notebook    | [d6a4584809](https://linux-hardware.org/?probe=d6a4584809) | Jan 07, 2023 |
| ASRock        | Q1900-ITX                   | Desktop     | [ac7df499e8](https://linux-hardware.org/?probe=ac7df499e8) | Jan 07, 2023 |
| Dell          | Latitude 2110               | Notebook    | [9910f8985b](https://linux-hardware.org/?probe=9910f8985b) | Jan 07, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [dcca84c5eb](https://linux-hardware.org/?probe=dcca84c5eb) | Jan 07, 2023 |
| HP            | Elite x2 1011 G1 Tablet     | Notebook    | [28c9b60939](https://linux-hardware.org/?probe=28c9b60939) | Jan 07, 2023 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [fa91397209](https://linux-hardware.org/?probe=fa91397209) | Jan 07, 2023 |
| Hardkernel    | Odroid XU4                  | Soc         | [5c688c4595](https://linux-hardware.org/?probe=5c688c4595) | Jan 06, 2023 |
| Lenovo        | IdeaPad 130-15IKB 81H7      | Notebook    | [9776545fc4](https://linux-hardware.org/?probe=9776545fc4) | Jan 06, 2023 |
| Toshiba       | Satellite C55Dt-A           | Notebook    | [f3cfb5dbb5](https://linux-hardware.org/?probe=f3cfb5dbb5) | Jan 06, 2023 |
| Lenovo        | IdeaPad 320-15IKB 80YE      | Notebook    | [9b0a8d487e](https://linux-hardware.org/?probe=9b0a8d487e) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [4ceeb719c2](https://linux-hardware.org/?probe=4ceeb719c2) | Jan 06, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d930da3de0](https://linux-hardware.org/?probe=d930da3de0) | Jan 06, 2023 |
| HP            | ProLiant DL360 Gen9         | Server      | [a456485950](https://linux-hardware.org/?probe=a456485950) | Jan 06, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [d069cbd46b](https://linux-hardware.org/?probe=d069cbd46b) | Jan 06, 2023 |
| &#er &&       | Aspire 5100                 | Notebook    | [26da9e8ee1](https://linux-hardware.org/?probe=26da9e8ee1) | Jan 06, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [b329d8f40f](https://linux-hardware.org/?probe=b329d8f40f) | Jan 06, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [1608711aa0](https://linux-hardware.org/?probe=1608711aa0) | Jan 06, 2023 |
| MSI           | Z97 GAMING 5                | Desktop     | [1edff66d1a](https://linux-hardware.org/?probe=1edff66d1a) | Jan 06, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [999663daee](https://linux-hardware.org/?probe=999663daee) | Jan 06, 2023 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [982de9c98d](https://linux-hardware.org/?probe=982de9c98d) | Jan 06, 2023 |
| Google        | Stout                       | Notebook    | [5ef816b9a6](https://linux-hardware.org/?probe=5ef816b9a6) | Jan 05, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [3245d27cb7](https://linux-hardware.org/?probe=3245d27cb7) | Jan 05, 2023 |
| HP            | EliteBook 840 Aero G8 No... | Notebook    | [b9f4ca82d2](https://linux-hardware.org/?probe=b9f4ca82d2) | Jan 05, 2023 |
| Acer          | Extensa 2540                | Notebook    | [4442f2c14a](https://linux-hardware.org/?probe=4442f2c14a) | Jan 05, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [a84ac79f2b](https://linux-hardware.org/?probe=a84ac79f2b) | Jan 05, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [6ea90d7af5](https://linux-hardware.org/?probe=6ea90d7af5) | Jan 05, 2023 |
| Dell          | 01XK1W A00                  | Desktop     | [bb487db79f](https://linux-hardware.org/?probe=bb487db79f) | Jan 05, 2023 |
| Acer          | Extensa 2540                | Notebook    | [ec8b49d7b0](https://linux-hardware.org/?probe=ec8b49d7b0) | Jan 04, 2023 |
| ASUSTek       | ROG STRIX B350-F GAMING     | Desktop     | [b063be9f2e](https://linux-hardware.org/?probe=b063be9f2e) | Jan 04, 2023 |
| ASUSTek       | PRIME B650M-A AX            | Desktop     | [872a58377f](https://linux-hardware.org/?probe=872a58377f) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [0042419ccb](https://linux-hardware.org/?probe=0042419ccb) | Jan 04, 2023 |
| Dell          | Inspiron 15-3567            | Notebook    | [82e42c0d42](https://linux-hardware.org/?probe=82e42c0d42) | Jan 04, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [8f519746c2](https://linux-hardware.org/?probe=8f519746c2) | Jan 04, 2023 |
| ELSKY         | M219FN-6C                   | Desktop     | [95862529f8](https://linux-hardware.org/?probe=95862529f8) | Jan 04, 2023 |
| Lenovo        | ThinkPad T430s 2356BQ5      | Notebook    | [fdf6545b20](https://linux-hardware.org/?probe=fdf6545b20) | Jan 04, 2023 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [420373dca1](https://linux-hardware.org/?probe=420373dca1) | Jan 04, 2023 |
| HP            | ENVY x360 Convertible 15... | Convertible | [01edd482a1](https://linux-hardware.org/?probe=01edd482a1) | Jan 04, 2023 |
| Lenovo        | 310B SDK0J40697 WIN 3305... | Desktop     | [b1771ee07c](https://linux-hardware.org/?probe=b1771ee07c) | Jan 03, 2023 |
| MSI           | MS-7519                     | Desktop     | [3239304aa0](https://linux-hardware.org/?probe=3239304aa0) | Jan 03, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [b876c5797a](https://linux-hardware.org/?probe=b876c5797a) | Jan 03, 2023 |
| Pegatron      | Maureen                     | Desktop     | [071cde04e9](https://linux-hardware.org/?probe=071cde04e9) | Jan 03, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [258412ac0a](https://linux-hardware.org/?probe=258412ac0a) | Jan 03, 2023 |
| ASUSTek       | F5SL                        | Notebook    | [67882c0f69](https://linux-hardware.org/?probe=67882c0f69) | Jan 02, 2023 |
| ASUSTek       | F5SL                        | Notebook    | [42ef1fbf40](https://linux-hardware.org/?probe=42ef1fbf40) | Jan 02, 2023 |
| Acer          | Aspire V3-574G              | Notebook    | [a889bba557](https://linux-hardware.org/?probe=a889bba557) | Jan 02, 2023 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [4a37b87ecf](https://linux-hardware.org/?probe=4a37b87ecf) | Jan 02, 2023 |
| Acer          | Aspire ES1-711              | Notebook    | [735e062168](https://linux-hardware.org/?probe=735e062168) | Jan 02, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [90603e4ab3](https://linux-hardware.org/?probe=90603e4ab3) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [70c50fe035](https://linux-hardware.org/?probe=70c50fe035) | Jan 02, 2023 |
| MSI           | GE75 Raider 8SG             | Notebook    | [b6fa9be350](https://linux-hardware.org/?probe=b6fa9be350) | Jan 02, 2023 |
| Lenovo        | 31A7 SDK0J40697 WIN 3305... | Mini pc     | [efa2748c95](https://linux-hardware.org/?probe=efa2748c95) | Jan 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [b54f3aab7b](https://linux-hardware.org/?probe=b54f3aab7b) | Jan 02, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [42e877ed10](https://linux-hardware.org/?probe=42e877ed10) | Jan 02, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X740... | Notebook    | [8d4934bc09](https://linux-hardware.org/?probe=8d4934bc09) | Jan 02, 2023 |
| Lenovo        | ThinkPad T480 20L6S29E0D    | Notebook    | [a1f966e5e8](https://linux-hardware.org/?probe=a1f966e5e8) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [08fb8de608](https://linux-hardware.org/?probe=08fb8de608) | Jan 02, 2023 |
| Lenovo        | ThinkPad T430u 33519LC      | Notebook    | [87af3fa7f0](https://linux-hardware.org/?probe=87af3fa7f0) | Jan 02, 2023 |
| ASUSTek       | ZenBook UX333FN_U3300FN     | Notebook    | [750a40a3cc](https://linux-hardware.org/?probe=750a40a3cc) | Jan 02, 2023 |
| ASUSTek       | T100TA                      | Notebook    | [2c33e446d4](https://linux-hardware.org/?probe=2c33e446d4) | Jan 02, 2023 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [3f68b8438c](https://linux-hardware.org/?probe=3f68b8438c) | Jan 02, 2023 |
| Lenovo        | IdeaPad 100-15IBD 80QQ      | Notebook    | [bca75efbe5](https://linux-hardware.org/?probe=bca75efbe5) | Jan 02, 2023 |
| HP            | Stream Laptop 14-cb1xxx     | Notebook    | [2396307897](https://linux-hardware.org/?probe=2396307897) | Jan 02, 2023 |
| ASUSTek       | TUF Gaming B550M-PLUS       | Desktop     | [c96c7d74fe](https://linux-hardware.org/?probe=c96c7d74fe) | Jan 02, 2023 |
| Gigabyte      | AX370-Gaming K5-CF          | Desktop     | [8b0b477726](https://linux-hardware.org/?probe=8b0b477726) | Jan 02, 2023 |
| ASUSTek       | ROG Strix G513RM_G513RM     | Notebook    | [13df46e700](https://linux-hardware.org/?probe=13df46e700) | Jan 02, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [7c72451666](https://linux-hardware.org/?probe=7c72451666) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming FX505DT_TUF50... | Notebook    | [f9db70d551](https://linux-hardware.org/?probe=f9db70d551) | Jan 01, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [8726e38f02](https://linux-hardware.org/?probe=8726e38f02) | Jan 01, 2023 |
| Lenovo        | G565 20071                  | Notebook    | [e974b446ae](https://linux-hardware.org/?probe=e974b446ae) | Jan 01, 2023 |
| Panasonic     | CF-54-2                     | Notebook    | [dfe3d2e06b](https://linux-hardware.org/?probe=dfe3d2e06b) | Jan 01, 2023 |
| Dell          | 0PV3YR A05                  | Server      | [073d682146](https://linux-hardware.org/?probe=073d682146) | Jan 01, 2023 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [d88df3fcee](https://linux-hardware.org/?probe=d88df3fcee) | Jan 01, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7474151c7e](https://linux-hardware.org/?probe=7474151c7e) | Jan 01, 2023 |
| Dell          | Inspiron 5566               | Notebook    | [9eadf42d31](https://linux-hardware.org/?probe=9eadf42d31) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [b1dc879a16](https://linux-hardware.org/?probe=b1dc879a16) | Jan 01, 2023 |
| ASUSTek       | TUF Z390-PRO GAMING         | Desktop     | [de65f4b654](https://linux-hardware.org/?probe=de65f4b654) | Dec 31, 2022 |
| Google        | Teemo                       | Desktop     | [6f6671a40e](https://linux-hardware.org/?probe=6f6671a40e) | Dec 31, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [500ce7ae28](https://linux-hardware.org/?probe=500ce7ae28) | Dec 31, 2022 |
| ASUSTek       | ZenBook UX425UAZ_UM425UA... | Notebook    | [8d33275e7b](https://linux-hardware.org/?probe=8d33275e7b) | Dec 31, 2022 |
| Google        | Teemo                       | Desktop     | [e3c39f29da](https://linux-hardware.org/?probe=e3c39f29da) | Dec 31, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [fb22f9430c](https://linux-hardware.org/?probe=fb22f9430c) | Dec 31, 2022 |
| ASRock        | A320M-DGS                   | Desktop     | [a9df519d4f](https://linux-hardware.org/?probe=a9df519d4f) | Dec 31, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3710331d81](https://linux-hardware.org/?probe=3710331d81) | Dec 31, 2022 |
| Lenovo        | IdeaPad Y560                | Notebook    | [c9d3a1d0a3](https://linux-hardware.org/?probe=c9d3a1d0a3) | Dec 31, 2022 |
| Acer          | Aspire A514-54              | Notebook    | [5775c77a91](https://linux-hardware.org/?probe=5775c77a91) | Dec 31, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [b1220a23ad](https://linux-hardware.org/?probe=b1220a23ad) | Dec 31, 2022 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [31343e35f0](https://linux-hardware.org/?probe=31343e35f0) | Dec 31, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [dff8a56537](https://linux-hardware.org/?probe=dff8a56537) | Dec 30, 2022 |
| HP            | Compaq 6710b (KE207ES#AB... | Notebook    | [d7d0be3872](https://linux-hardware.org/?probe=d7d0be3872) | Dec 30, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [4f45d532ac](https://linux-hardware.org/?probe=4f45d532ac) | Dec 30, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [4ea88219d8](https://linux-hardware.org/?probe=4ea88219d8) | Dec 30, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [c8a80649d2](https://linux-hardware.org/?probe=c8a80649d2) | Dec 30, 2022 |
| Supermicro    | X11SRA-RF                   | Server      | [2887a82948](https://linux-hardware.org/?probe=2887a82948) | Dec 30, 2022 |
| Supermicro    | X11SRA-RF                   | Server      | [e5f0b1d802](https://linux-hardware.org/?probe=e5f0b1d802) | Dec 30, 2022 |
| Supermicro    | X11SRA-RF                   | Server      | [cd84ddc342](https://linux-hardware.org/?probe=cd84ddc342) | Dec 30, 2022 |
| Lenovo        | ThinkStation C20 4263BA7    | Desktop     | [7b55955e2a](https://linux-hardware.org/?probe=7b55955e2a) | Dec 30, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a295f18c9f](https://linux-hardware.org/?probe=a295f18c9f) | Dec 30, 2022 |
| HP            | 255 G3                      | Notebook    | [89d6bd459c](https://linux-hardware.org/?probe=89d6bd459c) | Dec 30, 2022 |
| Toshiba       | Satellite L775-12V          | Notebook    | [2c601f6366](https://linux-hardware.org/?probe=2c601f6366) | Dec 29, 2022 |
| HP            | 339A                        | Desktop     | [8e0b785427](https://linux-hardware.org/?probe=8e0b785427) | Dec 29, 2022 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [c38ca6386e](https://linux-hardware.org/?probe=c38ca6386e) | Dec 29, 2022 |
| Lenovo        | ThinkPad T470p 20J7S1JT0... | Notebook    | [4b7bbb186f](https://linux-hardware.org/?probe=4b7bbb186f) | Dec 29, 2022 |
| Supermicro    | H8SCM                       | Server      | [9ee42dcf6f](https://linux-hardware.org/?probe=9ee42dcf6f) | Dec 29, 2022 |
| MACHCREATO... | AB                          | Notebook    | [52a6beb872](https://linux-hardware.org/?probe=52a6beb872) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | Notebook    | [5bf3ff5c0e](https://linux-hardware.org/?probe=5bf3ff5c0e) | Dec 29, 2022 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7S... | Notebook    | [4f63c4474c](https://linux-hardware.org/?probe=4f63c4474c) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [50149bf9e3](https://linux-hardware.org/?probe=50149bf9e3) | Dec 29, 2022 |
| Gigabyte      | H61M-DS2                    | Desktop     | [b0a40a3ac0](https://linux-hardware.org/?probe=b0a40a3ac0) | Dec 29, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [716ba7f970](https://linux-hardware.org/?probe=716ba7f970) | Dec 29, 2022 |
| HP            | EliteBook Folio 1040 G3     | Notebook    | [6aad572cd5](https://linux-hardware.org/?probe=6aad572cd5) | Dec 29, 2022 |
| HP            | ZBook 15 G6                 | Notebook    | [af1655497e](https://linux-hardware.org/?probe=af1655497e) | Dec 29, 2022 |
| Unknown       | Unknown                     | Desktop     | [34b6109940](https://linux-hardware.org/?probe=34b6109940) | Dec 29, 2022 |
| HP            | ProBook 6570b               | Notebook    | [46fd918b7c](https://linux-hardware.org/?probe=46fd918b7c) | Dec 29, 2022 |
| HP            | Pavilion g7                 | Notebook    | [444363b7ec](https://linux-hardware.org/?probe=444363b7ec) | Dec 29, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [4239e2fa3c](https://linux-hardware.org/?probe=4239e2fa3c) | Dec 29, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [7881f027ea](https://linux-hardware.org/?probe=7881f027ea) | Dec 29, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [c1e5e82fbb](https://linux-hardware.org/?probe=c1e5e82fbb) | Dec 29, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [457c2ae4ae](https://linux-hardware.org/?probe=457c2ae4ae) | Dec 28, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [fdfd0f21c7](https://linux-hardware.org/?probe=fdfd0f21c7) | Dec 28, 2022 |
| Dell          | Inspiron 3583               | Notebook    | [41c7a16579](https://linux-hardware.org/?probe=41c7a16579) | Dec 28, 2022 |
| Toshiba       | Satellite L455D             | Notebook    | [35c085aa82](https://linux-hardware.org/?probe=35c085aa82) | Dec 28, 2022 |
| Dell          | Vostro 3400                 | Notebook    | [27f58a8ad1](https://linux-hardware.org/?probe=27f58a8ad1) | Dec 28, 2022 |
| HP            | ProLiant ML30 Gen9          | Desktop     | [174e7e831b](https://linux-hardware.org/?probe=174e7e831b) | Dec 28, 2022 |
| Acer          | Aspire ES1-531              | Notebook    | [c29088a63f](https://linux-hardware.org/?probe=c29088a63f) | Dec 28, 2022 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [422238387a](https://linux-hardware.org/?probe=422238387a) | Dec 28, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [7c60cc0210](https://linux-hardware.org/?probe=7c60cc0210) | Dec 28, 2022 |
| Lenovo        | ThinkPad X1 Yoga 2nd 20J... | Convertible | [72f770277e](https://linux-hardware.org/?probe=72f770277e) | Dec 28, 2022 |
| HP            | ProBook 6470b               | Notebook    | [055705b3f2](https://linux-hardware.org/?probe=055705b3f2) | Dec 28, 2022 |
| HP            | 158A                        | Desktop     | [c80bfd7c30](https://linux-hardware.org/?probe=c80bfd7c30) | Dec 28, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [ec0ad4d293](https://linux-hardware.org/?probe=ec0ad4d293) | Dec 28, 2022 |
| ASRock        | X470 Gaming-ITX/ac          | Desktop     | [c4d1d971d1](https://linux-hardware.org/?probe=c4d1d971d1) | Dec 28, 2022 |
| Apple         | Mac-F42786A9 DVT            | All in one  | [2ceb80faeb](https://linux-hardware.org/?probe=2ceb80faeb) | Dec 28, 2022 |
| Lenovo        | 0B98401 WIN                 | Desktop     | [0f71bbaf67](https://linux-hardware.org/?probe=0f71bbaf67) | Dec 28, 2022 |
| ASUSTek       | A4110                       | All in one  | [fa417dc5c7](https://linux-hardware.org/?probe=fa417dc5c7) | Dec 28, 2022 |
| ASRock        | J3455-ITX                   | Desktop     | [6e628aeb01](https://linux-hardware.org/?probe=6e628aeb01) | Dec 28, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [10dce91da1](https://linux-hardware.org/?probe=10dce91da1) | Dec 27, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [321cc72064](https://linux-hardware.org/?probe=321cc72064) | Dec 27, 2022 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [48f161dfc8](https://linux-hardware.org/?probe=48f161dfc8) | Dec 27, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [d174ffb318](https://linux-hardware.org/?probe=d174ffb318) | Dec 27, 2022 |
| MSI           | GE62 2QC                    | Notebook    | [dbd69d70ac](https://linux-hardware.org/?probe=dbd69d70ac) | Dec 27, 2022 |
| Dell          | 0M017G A00                  | Desktop     | [5c41315695](https://linux-hardware.org/?probe=5c41315695) | Dec 27, 2022 |
| Intel         | NUC10i7FNB K61360-303       | Mini pc     | [042fb842d2](https://linux-hardware.org/?probe=042fb842d2) | Dec 27, 2022 |
| Panasonic     | FZ55-2                      | Notebook    | [1699b7c3b2](https://linux-hardware.org/?probe=1699b7c3b2) | Dec 27, 2022 |
| ASUSTek       | VivoBook_ASUS Laptop E40... | Notebook    | [78c6c15502](https://linux-hardware.org/?probe=78c6c15502) | Dec 27, 2022 |
| Raspberry ... | Raspberry Pi Compute Mod... | Soc         | [06cba3f478](https://linux-hardware.org/?probe=06cba3f478) | Dec 27, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [210f0c0375](https://linux-hardware.org/?probe=210f0c0375) | Dec 27, 2022 |
| Gigabyte      | 990FXA-UD3 R5               | Desktop     | [734c3742b1](https://linux-hardware.org/?probe=734c3742b1) | Dec 27, 2022 |
| Gigabyte      | 990FXA-UD3 R5               | Desktop     | [bb6dddc780](https://linux-hardware.org/?probe=bb6dddc780) | Dec 27, 2022 |
| ASRock        | Brazos                      | Desktop     | [f5183b395b](https://linux-hardware.org/?probe=f5183b395b) | Dec 27, 2022 |
| Notebook      | L14xMU                      | Notebook    | [7644bc65e2](https://linux-hardware.org/?probe=7644bc65e2) | Dec 27, 2022 |
| Dell          | Inspiron 1012               | Notebook    | [3dd6b8a416](https://linux-hardware.org/?probe=3dd6b8a416) | Dec 26, 2022 |
| Dell          | 02YRK5 A02                  | Desktop     | [56dc5ff1b9](https://linux-hardware.org/?probe=56dc5ff1b9) | Dec 26, 2022 |
| Exo           | Smart Serie M               | Notebook    | [942ee3b035](https://linux-hardware.org/?probe=942ee3b035) | Dec 26, 2022 |
| Lenovo        | ThinkPad E560 20EV002FUS    | Notebook    | [3bb1c5cc47](https://linux-hardware.org/?probe=3bb1c5cc47) | Dec 26, 2022 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [29a54c4976](https://linux-hardware.org/?probe=29a54c4976) | Dec 26, 2022 |
| Gigabyte      | B660M GAMING DDR4           | Desktop     | [2618b85414](https://linux-hardware.org/?probe=2618b85414) | Dec 26, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [6ad649ad46](https://linux-hardware.org/?probe=6ad649ad46) | Dec 26, 2022 |
| Gigabyte      | B360M H                     | Desktop     | [2f0d1b1c8d](https://linux-hardware.org/?probe=2f0d1b1c8d) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [d90a9cdcd3](https://linux-hardware.org/?probe=d90a9cdcd3) | Dec 26, 2022 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [fc0eac877c](https://linux-hardware.org/?probe=fc0eac877c) | Dec 26, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [67fee9ab39](https://linux-hardware.org/?probe=67fee9ab39) | Dec 26, 2022 |
| Acer          | Aspire ES1-533              | Notebook    | [3b5fa6d85a](https://linux-hardware.org/?probe=3b5fa6d85a) | Dec 26, 2022 |
| ASUSTek       | M3A32-MVP DELUXE            | Desktop     | [0fa5809533](https://linux-hardware.org/?probe=0fa5809533) | Dec 26, 2022 |
| Matrox Ele... | 4GPMOBIL 7449-03-0          | Desktop     | [c02a37a124](https://linux-hardware.org/?probe=c02a37a124) | Dec 26, 2022 |
| Lenovo        | ThinkPad X250 20CLS1UB00    | Notebook    | [fc8b2899fa](https://linux-hardware.org/?probe=fc8b2899fa) | Dec 25, 2022 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [a0996d42bd](https://linux-hardware.org/?probe=a0996d42bd) | Dec 25, 2022 |
| HP            | 470 G8 Notebook PC          | Notebook    | [6d77c48324](https://linux-hardware.org/?probe=6d77c48324) | Dec 25, 2022 |
| Lenovo        | ThinkStation D30 42234T7    | Desktop     | [6ac63aca4f](https://linux-hardware.org/?probe=6ac63aca4f) | Dec 25, 2022 |
| Fujitsu       | D3221-A1 S26361-D3221-A1    | Desktop     | [8855d29d69](https://linux-hardware.org/?probe=8855d29d69) | Dec 25, 2022 |
| Dell          | Inspiron 7506 2n1           | Convertible | [b5eaa2b6aa](https://linux-hardware.org/?probe=b5eaa2b6aa) | Dec 25, 2022 |
| Unknown       | Unknown                     | Soc         | [95c95c980d](https://linux-hardware.org/?probe=95c95c980d) | Dec 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [5977afc830](https://linux-hardware.org/?probe=5977afc830) | Dec 25, 2022 |
| ASUSTek       | G751JT                      | Notebook    | [16e989ff99](https://linux-hardware.org/?probe=16e989ff99) | Dec 25, 2022 |
| Dell          | Latitude E6520              | Notebook    | [33a51c934d](https://linux-hardware.org/?probe=33a51c934d) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [ea09a6daa8](https://linux-hardware.org/?probe=ea09a6daa8) | Dec 25, 2022 |
| Dell          | 00TD00 A00                  | All in one  | [84beba0484](https://linux-hardware.org/?probe=84beba0484) | Dec 25, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [45737153e4](https://linux-hardware.org/?probe=45737153e4) | Dec 25, 2022 |
| HP            | Laptop 15-bw0xx             | Notebook    | [42221f61fb](https://linux-hardware.org/?probe=42221f61fb) | Dec 25, 2022 |
| Unknown       | Apple MacBook Pro (14-in... | Notebook    | [8a5b919c91](https://linux-hardware.org/?probe=8a5b919c91) | Dec 24, 2022 |
| Medion        | E122X                       | Notebook    | [6e4e34bcc3](https://linux-hardware.org/?probe=6e4e34bcc3) | Dec 24, 2022 |
| Medion        | E122X                       | Notebook    | [bf41c45a7d](https://linux-hardware.org/?probe=bf41c45a7d) | Dec 24, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [096d4fc8c2](https://linux-hardware.org/?probe=096d4fc8c2) | Dec 24, 2022 |
| ASUSTek       | ROG Maximus Z690 EXTREME    | Desktop     | [4d19273307](https://linux-hardware.org/?probe=4d19273307) | Dec 24, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [f7af4b1164](https://linux-hardware.org/?probe=f7af4b1164) | Dec 24, 2022 |
| HP            | ProLiant MicroServer        | Desktop     | [b95892f2dc](https://linux-hardware.org/?probe=b95892f2dc) | Dec 24, 2022 |
| ASUSTek       | WS C422 DC                  | Desktop     | [7be7c81575](https://linux-hardware.org/?probe=7be7c81575) | Dec 24, 2022 |
| Supermicro    | X11SRA-RF                   | Server      | [efdf519660](https://linux-hardware.org/?probe=efdf519660) | Dec 24, 2022 |
| ASUSTek       | WS C422 DC                  | Desktop     | [526414fd8f](https://linux-hardware.org/?probe=526414fd8f) | Dec 24, 2022 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [c5f2f2db53](https://linux-hardware.org/?probe=c5f2f2db53) | Dec 24, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [39f35288d4](https://linux-hardware.org/?probe=39f35288d4) | Dec 24, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | Notebook    | [6ac6e552a8](https://linux-hardware.org/?probe=6ac6e552a8) | Dec 24, 2022 |
| Dell          | Inspiron 5570               | Notebook    | [1c7e7f8dd2](https://linux-hardware.org/?probe=1c7e7f8dd2) | Dec 24, 2022 |
| ASRock        | B450 Pro4                   | Desktop     | [70ff83271a](https://linux-hardware.org/?probe=70ff83271a) | Dec 24, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [df787f1286](https://linux-hardware.org/?probe=df787f1286) | Dec 24, 2022 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [0a2ed74cfd](https://linux-hardware.org/?probe=0a2ed74cfd) | Dec 23, 2022 |
| Dell          | Latitude E7440              | Notebook    | [baae52327d](https://linux-hardware.org/?probe=baae52327d) | Dec 23, 2022 |
| Dell          | Latitude E7440              | Notebook    | [bc5d48b831](https://linux-hardware.org/?probe=bc5d48b831) | Dec 23, 2022 |
| Dell          | Latitude E7440              | Notebook    | [fde483d476](https://linux-hardware.org/?probe=fde483d476) | Dec 23, 2022 |
| HP            | 876C SMVB                   | Desktop     | [988b03aae5](https://linux-hardware.org/?probe=988b03aae5) | Dec 23, 2022 |
| Dell          | Latitude E7440              | Notebook    | [a746012ffd](https://linux-hardware.org/?probe=a746012ffd) | Dec 23, 2022 |
| Lenovo        | ThinkPad T16 Gen 1 21BWS... | Notebook    | [9e5c4705fa](https://linux-hardware.org/?probe=9e5c4705fa) | Dec 23, 2022 |
| Dell          | Latitude D630               | Notebook    | [8175d003ce](https://linux-hardware.org/?probe=8175d003ce) | Dec 23, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [a54a0884ce](https://linux-hardware.org/?probe=a54a0884ce) | Dec 23, 2022 |
| Google        | Reks                        | Notebook    | [ecee690e6e](https://linux-hardware.org/?probe=ecee690e6e) | Dec 23, 2022 |
| Toshiba       | Satellite L10W-B-101        | Notebook    | [54d5cca493](https://linux-hardware.org/?probe=54d5cca493) | Dec 23, 2022 |
| Google        | Reks                        | Notebook    | [58b1b4cac1](https://linux-hardware.org/?probe=58b1b4cac1) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [297651d437](https://linux-hardware.org/?probe=297651d437) | Dec 23, 2022 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [79b015dcea](https://linux-hardware.org/?probe=79b015dcea) | Dec 23, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [d5625e9592](https://linux-hardware.org/?probe=d5625e9592) | Dec 23, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [958ee9d145](https://linux-hardware.org/?probe=958ee9d145) | Dec 23, 2022 |
| Dell          | G3 3590                     | Notebook    | [d75d9e6663](https://linux-hardware.org/?probe=d75d9e6663) | Dec 23, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [5f75bb423d](https://linux-hardware.org/?probe=5f75bb423d) | Dec 23, 2022 |
| Acer          | Aspire 4750                 | Notebook    | [3256c282db](https://linux-hardware.org/?probe=3256c282db) | Dec 23, 2022 |
| Lenovo        | ThinkBook 14s Yoga G2 IA... | Convertible | [3ea5c420b1](https://linux-hardware.org/?probe=3ea5c420b1) | Dec 23, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [5bedf1557b](https://linux-hardware.org/?probe=5bedf1557b) | Dec 23, 2022 |
| Dell          | Inspiron 5490               | Notebook    | [1c424b5f55](https://linux-hardware.org/?probe=1c424b5f55) | Dec 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [f9c4fecaf4](https://linux-hardware.org/?probe=f9c4fecaf4) | Dec 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [3832db2827](https://linux-hardware.org/?probe=3832db2827) | Dec 23, 2022 |
| Toshiba       | Satellite C55Dt-A           | Notebook    | [67294324c5](https://linux-hardware.org/?probe=67294324c5) | Dec 22, 2022 |
| HP            | EliteBook x360 1040 G8 N... | Convertible | [7794581d04](https://linux-hardware.org/?probe=7794581d04) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [c6d28912f0](https://linux-hardware.org/?probe=c6d28912f0) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [1a14f26bd3](https://linux-hardware.org/?probe=1a14f26bd3) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [db77bb7a3f](https://linux-hardware.org/?probe=db77bb7a3f) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [d2278ed94d](https://linux-hardware.org/?probe=d2278ed94d) | Dec 22, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [09ba8ccf48](https://linux-hardware.org/?probe=09ba8ccf48) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [f4e79df709](https://linux-hardware.org/?probe=f4e79df709) | Dec 22, 2022 |
| Apple         | MacBookAir7,1               | Notebook    | [2c3febf6fa](https://linux-hardware.org/?probe=2c3febf6fa) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [cddffa9123](https://linux-hardware.org/?probe=cddffa9123) | Dec 22, 2022 |
| Dell          | Latitude E7440              | Notebook    | [5f911806c8](https://linux-hardware.org/?probe=5f911806c8) | Dec 22, 2022 |
| Lenovo        | ThinkPad X260 20F5005NAU    | Notebook    | [844f589d20](https://linux-hardware.org/?probe=844f589d20) | Dec 22, 2022 |
| Dell          | Latitude D630               | Notebook    | [e1106d8868](https://linux-hardware.org/?probe=e1106d8868) | Dec 22, 2022 |
| ASRock        | X300M-STX                   | Desktop     | [3d90b10b72](https://linux-hardware.org/?probe=3d90b10b72) | Dec 22, 2022 |
| Packard Be... | DOT S                       | Notebook    | [c26f1d77e6](https://linux-hardware.org/?probe=c26f1d77e6) | Dec 22, 2022 |
| HP            | Stream Notebook PC 13       | Notebook    | [b049c64ff7](https://linux-hardware.org/?probe=b049c64ff7) | Dec 22, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3a87279be6](https://linux-hardware.org/?probe=3a87279be6) | Dec 22, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [5f132c928b](https://linux-hardware.org/?probe=5f132c928b) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [ba82bee4c7](https://linux-hardware.org/?probe=ba82bee4c7) | Dec 22, 2022 |
| Raspberry ... | Raspberry Pi 400 Rev 1.0    | Soc         | [a2a2f20ef4](https://linux-hardware.org/?probe=a2a2f20ef4) | Dec 22, 2022 |
| Dell          | G3 3590                     | Notebook    | [8038491eb0](https://linux-hardware.org/?probe=8038491eb0) | Dec 22, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [fe4ef75450](https://linux-hardware.org/?probe=fe4ef75450) | Dec 21, 2022 |
| Lenovo        | IdeaPad 5 15IAL7 82SF       | Notebook    | [16cae3015a](https://linux-hardware.org/?probe=16cae3015a) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [b4e828bef3](https://linux-hardware.org/?probe=b4e828bef3) | Dec 21, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B7402FEA... | Convertible | [0cb3ccf545](https://linux-hardware.org/?probe=0cb3ccf545) | Dec 21, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [28013105ef](https://linux-hardware.org/?probe=28013105ef) | Dec 21, 2022 |
| Dell          | Vostro 3583                 | Notebook    | [cf3c6eb18b](https://linux-hardware.org/?probe=cf3c6eb18b) | Dec 21, 2022 |
| Apple         | MacBookAir7,2               | Notebook    | [056d76bae8](https://linux-hardware.org/?probe=056d76bae8) | Dec 21, 2022 |
| Sony          | SVE1112M1EB                 | Notebook    | [74e100e63b](https://linux-hardware.org/?probe=74e100e63b) | Dec 21, 2022 |
| HP            | ZBook Power 15.6 inch G8... | Notebook    | [6b202d6cc2](https://linux-hardware.org/?probe=6b202d6cc2) | Dec 21, 2022 |
| Lenovo        | Legion 5 15ARH05 82B5       | Notebook    | [9438c80c85](https://linux-hardware.org/?probe=9438c80c85) | Dec 21, 2022 |
| Dell          | 0020HJ A01                  | Server      | [e266254c60](https://linux-hardware.org/?probe=e266254c60) | Dec 21, 2022 |
| HP            | ProLiant DL360e Gen8        | Server      | [5477e8f714](https://linux-hardware.org/?probe=5477e8f714) | Dec 21, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [428c861575](https://linux-hardware.org/?probe=428c861575) | Dec 21, 2022 |
| HP            | ProLiant MicroServer Gen... | Desktop     | [57182d09ed](https://linux-hardware.org/?probe=57182d09ed) | Dec 21, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [449e38a14d](https://linux-hardware.org/?probe=449e38a14d) | Dec 21, 2022 |
| Intel         | DQ77CP AAG67261-300         | Desktop     | [908f619aa7](https://linux-hardware.org/?probe=908f619aa7) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [363c106fa2](https://linux-hardware.org/?probe=363c106fa2) | Dec 21, 2022 |
| Dell          | G3 3590                     | Notebook    | [8272655600](https://linux-hardware.org/?probe=8272655600) | Dec 21, 2022 |
| Gigabyte      | M68MT-S2P                   | Desktop     | [ed29442d39](https://linux-hardware.org/?probe=ed29442d39) | Dec 21, 2022 |
| Supermicro    | X10DRH-iT                   | Server      | [1215ed7cbf](https://linux-hardware.org/?probe=1215ed7cbf) | Dec 21, 2022 |
| Inventec      | Dell Wyse Thin Client De... | Mini pc     | [3007d5dd93](https://linux-hardware.org/?probe=3007d5dd93) | Dec 21, 2022 |
| Fujitsu       | D3222-A1 S26361-D3222-A1    | Desktop     | [c4719bd0ac](https://linux-hardware.org/?probe=c4719bd0ac) | Dec 21, 2022 |
| Unknown       | Unknown                     | Soc         | [764115860e](https://linux-hardware.org/?probe=764115860e) | Dec 21, 2022 |
| MSI           | MS-7318                     | Desktop     | [4622016059](https://linux-hardware.org/?probe=4622016059) | Dec 21, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [827c7f9bd3](https://linux-hardware.org/?probe=827c7f9bd3) | Dec 21, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [cd4fa20e66](https://linux-hardware.org/?probe=cd4fa20e66) | Dec 20, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [60b20a8efa](https://linux-hardware.org/?probe=60b20a8efa) | Dec 20, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [e676fe186f](https://linux-hardware.org/?probe=e676fe186f) | Dec 20, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a2c8bb966e](https://linux-hardware.org/?probe=a2c8bb966e) | Dec 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M760... | Notebook    | [658e730bd3](https://linux-hardware.org/?probe=658e730bd3) | Dec 20, 2022 |
| Intel         | DG35EC AAE29266-205         | Desktop     | [3cee3ad865](https://linux-hardware.org/?probe=3cee3ad865) | Dec 20, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [1e53c20bdd](https://linux-hardware.org/?probe=1e53c20bdd) | Dec 20, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [68731f4d29](https://linux-hardware.org/?probe=68731f4d29) | Dec 20, 2022 |
| Dell          | 0MN1TX A00                  | Desktop     | [f2ae430663](https://linux-hardware.org/?probe=f2ae430663) | Dec 20, 2022 |
| ASUSTek       | T100TA                      | Notebook    | [1dc546e14a](https://linux-hardware.org/?probe=1dc546e14a) | Dec 20, 2022 |
| Gigabyte      | P75-D3P                     | Desktop     | [ff2420e759](https://linux-hardware.org/?probe=ff2420e759) | Dec 19, 2022 |
| Lenovo        | ThinkPad T490 20N2CTO1WW    | Notebook    | [2aeb8fd0cd](https://linux-hardware.org/?probe=2aeb8fd0cd) | Dec 19, 2022 |
| Dell          | 09KPNV A01                  | Desktop     | [a4c5e58eec](https://linux-hardware.org/?probe=a4c5e58eec) | Dec 19, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [a79b17ea96](https://linux-hardware.org/?probe=a79b17ea96) | Dec 19, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [6bfb0295df](https://linux-hardware.org/?probe=6bfb0295df) | Dec 19, 2022 |
| ASRock        | N68-GS3 UCC                 | Desktop     | [19dad9b5b2](https://linux-hardware.org/?probe=19dad9b5b2) | Dec 19, 2022 |
| Gigabyte      | G41MT-ES2L                  | Desktop     | [d23b58b5da](https://linux-hardware.org/?probe=d23b58b5da) | Dec 19, 2022 |
| MSI           | A320M-A PRO MAX             | Desktop     | [30aec905c0](https://linux-hardware.org/?probe=30aec905c0) | Dec 19, 2022 |
| GIFA Indus... | TM-J3355-2G2L               | Desktop     | [526697a9d0](https://linux-hardware.org/?probe=526697a9d0) | Dec 19, 2022 |
| HP            | 255 G8 Notebook PC          | Notebook    | [08800ce691](https://linux-hardware.org/?probe=08800ce691) | Dec 19, 2022 |
| Apple         | Mac-F221BEC8                | Desktop     | [493ddb6998](https://linux-hardware.org/?probe=493ddb6998) | Dec 19, 2022 |
| IceWhale T... | ZimaBoard 216 ZMB           | Desktop     | [647bf0e2a7](https://linux-hardware.org/?probe=647bf0e2a7) | Dec 19, 2022 |
| ASUSTek       | 900SD                       | Notebook    | [43d2c88062](https://linux-hardware.org/?probe=43d2c88062) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [956aaecbb9](https://linux-hardware.org/?probe=956aaecbb9) | Dec 18, 2022 |
| Dell          | Inspiron 3501               | Notebook    | [d5ceb48450](https://linux-hardware.org/?probe=d5ceb48450) | Dec 18, 2022 |
| HP            | ENVY Laptop 13-ad1xx        | Notebook    | [756263bf48](https://linux-hardware.org/?probe=756263bf48) | Dec 18, 2022 |
| EUROCOM       | SCORPIUS 3D                 | Notebook    | [4fdf299276](https://linux-hardware.org/?probe=4fdf299276) | Dec 18, 2022 |
| Dell          | 0UY894 A02                  | Desktop     | [904ee2bb12](https://linux-hardware.org/?probe=904ee2bb12) | Dec 18, 2022 |
| Dell          | 06JWJY A00                  | Desktop     | [89ac693c2c](https://linux-hardware.org/?probe=89ac693c2c) | Dec 18, 2022 |
| ASUSTek       | M51BC                       | Desktop     | [78a6f49d22](https://linux-hardware.org/?probe=78a6f49d22) | Dec 18, 2022 |
| Acer          | TravelMate P253             | Notebook    | [97d650e93f](https://linux-hardware.org/?probe=97d650e93f) | Dec 18, 2022 |
| Dell          | Latitude E6530              | Notebook    | [198a9bc936](https://linux-hardware.org/?probe=198a9bc936) | Dec 18, 2022 |
| HP            | Pavilion g7                 | Notebook    | [9829a799a0](https://linux-hardware.org/?probe=9829a799a0) | Dec 18, 2022 |
| Lenovo        | ThinkPad T470 20HES3JR02    | Notebook    | [f9e4638f19](https://linux-hardware.org/?probe=f9e4638f19) | Dec 18, 2022 |
| Dell          | Inspiron N5110              | Notebook    | [9e4f7a69c9](https://linux-hardware.org/?probe=9e4f7a69c9) | Dec 18, 2022 |
| Unknown       | Unknown                     | Other       | [78a211835b](https://linux-hardware.org/?probe=78a211835b) | Dec 18, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [a80a6922d4](https://linux-hardware.org/?probe=a80a6922d4) | Dec 18, 2022 |
| Dell          | Latitude E4310              | Notebook    | [ace267f47c](https://linux-hardware.org/?probe=ace267f47c) | Dec 18, 2022 |
| ASUSTek       | ROG Maximus Z690 FORMULA    | Desktop     | [0886e650a3](https://linux-hardware.org/?probe=0886e650a3) | Dec 18, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [937a672cb0](https://linux-hardware.org/?probe=937a672cb0) | Dec 17, 2022 |
| Gigabyte      | X570S AERO G                | Desktop     | [1ec932aa3a](https://linux-hardware.org/?probe=1ec932aa3a) | Dec 17, 2022 |
| ASUSTek       | P8H67-M                     | Desktop     | [cf6fc033d6](https://linux-hardware.org/?probe=cf6fc033d6) | Dec 17, 2022 |
| Intel         | NUC8BEB J72693-303          | Mini pc     | [b882d3e249](https://linux-hardware.org/?probe=b882d3e249) | Dec 17, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [ed5d3570ef](https://linux-hardware.org/?probe=ed5d3570ef) | Dec 17, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [1e2531fdf1](https://linux-hardware.org/?probe=1e2531fdf1) | Dec 17, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | Notebook    | [218654b079](https://linux-hardware.org/?probe=218654b079) | Dec 17, 2022 |
| Dell          | Inspiron 14 5425            | Notebook    | [e7d96ccda5](https://linux-hardware.org/?probe=e7d96ccda5) | Dec 17, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [96ae6bc093](https://linux-hardware.org/?probe=96ae6bc093) | Dec 17, 2022 |
| HP            | Notebook                    | Notebook    | [844d855f78](https://linux-hardware.org/?probe=844d855f78) | Dec 17, 2022 |
| Unknown       | Unknown                     | Notebook    | [208016df07](https://linux-hardware.org/?probe=208016df07) | Dec 17, 2022 |
| Dell          | 0V8F20 A01                  | Desktop     | [d9e3649f12](https://linux-hardware.org/?probe=d9e3649f12) | Dec 16, 2022 |
| Unknown       | Unknown                     | Soc         | [4d5a73e0e6](https://linux-hardware.org/?probe=4d5a73e0e6) | Dec 16, 2022 |
| Acer          | TravelMate P253             | Notebook    | [80188fd5bf](https://linux-hardware.org/?probe=80188fd5bf) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [abfa3437b3](https://linux-hardware.org/?probe=abfa3437b3) | Dec 16, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [7b3f9b5af0](https://linux-hardware.org/?probe=7b3f9b5af0) | Dec 16, 2022 |
| Dell          | 0M5DCD A00                  | Desktop     | [f58cc5bcba](https://linux-hardware.org/?probe=f58cc5bcba) | Dec 16, 2022 |
| Dell          | Inspiron 7590               | Notebook    | [e8fb837cf5](https://linux-hardware.org/?probe=e8fb837cf5) | Dec 16, 2022 |
| ASUSTek       | PRIME B560M-A               | Desktop     | [f43049fe6d](https://linux-hardware.org/?probe=f43049fe6d) | Dec 16, 2022 |
| HP            | 876C SMVB                   | Desktop     | [e214378eea](https://linux-hardware.org/?probe=e214378eea) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [5cc0ff812b](https://linux-hardware.org/?probe=5cc0ff812b) | Dec 16, 2022 |
| Lenovo        | ThinkPad X230 23255NG       | Notebook    | [062a6ed428](https://linux-hardware.org/?probe=062a6ed428) | Dec 16, 2022 |
| Google        | Laser14                     | Notebook    | [b07a01ffe4](https://linux-hardware.org/?probe=b07a01ffe4) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [db670caadd](https://linux-hardware.org/?probe=db670caadd) | Dec 16, 2022 |
| ASUSTek       | Z170-DELUXE                 | Desktop     | [3a524796f6](https://linux-hardware.org/?probe=3a524796f6) | Dec 16, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [4676cf2979](https://linux-hardware.org/?probe=4676cf2979) | Dec 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [138cbfa0ba](https://linux-hardware.org/?probe=138cbfa0ba) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [d5cf351351](https://linux-hardware.org/?probe=d5cf351351) | Dec 16, 2022 |
| MSI           | AM1I                        | Desktop     | [0ebd00e848](https://linux-hardware.org/?probe=0ebd00e848) | Dec 16, 2022 |
| Lenovo        | ThinkPad X1 Extreme Gen ... | Notebook    | [e2056deb8a](https://linux-hardware.org/?probe=e2056deb8a) | Dec 16, 2022 |
| MSI           | AM1I                        | Desktop     | [97dfa5ebf8](https://linux-hardware.org/?probe=97dfa5ebf8) | Dec 16, 2022 |
| Intel         | powered classmate PC        | Notebook    | [e0401225a2](https://linux-hardware.org/?probe=e0401225a2) | Dec 15, 2022 |
| HP            | 829E                        | Mini pc     | [dccdfac601](https://linux-hardware.org/?probe=dccdfac601) | Dec 15, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [713a2bcaf4](https://linux-hardware.org/?probe=713a2bcaf4) | Dec 15, 2022 |
| HP            | 876C SMVB                   | Desktop     | [c704265799](https://linux-hardware.org/?probe=c704265799) | Dec 15, 2022 |
| HP            | 876C SMVB                   | Desktop     | [3a6fdcc184](https://linux-hardware.org/?probe=3a6fdcc184) | Dec 15, 2022 |
| Lenovo        | ThinkPad E490 20N8CTO1WW    | Notebook    | [13ee187e45](https://linux-hardware.org/?probe=13ee187e45) | Dec 15, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 8... | Notebook    | [bec79890c8](https://linux-hardware.org/?probe=bec79890c8) | Dec 15, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [3c6c7c5eb5](https://linux-hardware.org/?probe=3c6c7c5eb5) | Dec 15, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [b184d02286](https://linux-hardware.org/?probe=b184d02286) | Dec 15, 2022 |
| Unknown       | T3 MRD                      | Notebook    | [909e1a1604](https://linux-hardware.org/?probe=909e1a1604) | Dec 15, 2022 |
| Google        | Cyan                        | Notebook    | [2b9f20b7da](https://linux-hardware.org/?probe=2b9f20b7da) | Dec 15, 2022 |
| Lenovo        | ThinkPad T430 2349I62       | Notebook    | [f7590c1a07](https://linux-hardware.org/?probe=f7590c1a07) | Dec 15, 2022 |
| Dell          | Latitude 3490               | Notebook    | [af008f69f1](https://linux-hardware.org/?probe=af008f69f1) | Dec 14, 2022 |
| Fujitsu       | D3313-G1 S26361-D3313-G1    | Desktop     | [4651fa0db3](https://linux-hardware.org/?probe=4651fa0db3) | Dec 14, 2022 |
| Acer          | Aspire 5738                 | Notebook    | [c0c4581310](https://linux-hardware.org/?probe=c0c4581310) | Dec 14, 2022 |
| Apple         | MacBook6,1                  | Notebook    | [f19d464a26](https://linux-hardware.org/?probe=f19d464a26) | Dec 14, 2022 |
| ASUSTek       | M3N                         | Notebook    | [4e9f8e4c01](https://linux-hardware.org/?probe=4e9f8e4c01) | Dec 14, 2022 |
| ASRockRack    | X470D4U2-2T                 | Desktop     | [47c18717db](https://linux-hardware.org/?probe=47c18717db) | Dec 14, 2022 |
| ASRock        | B550M Steel Legend          | Desktop     | [516d6f7f12](https://linux-hardware.org/?probe=516d6f7f12) | Dec 14, 2022 |
| Dell          | 0N185P A02                  | Desktop     | [32d47ba775](https://linux-hardware.org/?probe=32d47ba775) | Dec 14, 2022 |
| Dell          | 0N185P A02                  | Desktop     | [ee28e5efa8](https://linux-hardware.org/?probe=ee28e5efa8) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [9e8ad3aefd](https://linux-hardware.org/?probe=9e8ad3aefd) | Dec 14, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [eadca468de](https://linux-hardware.org/?probe=eadca468de) | Dec 14, 2022 |
| Dell          | 0H8367                      | Desktop     | [7fff4bfffc](https://linux-hardware.org/?probe=7fff4bfffc) | Dec 14, 2022 |
| Gigabyte      | GA-MA785GMT-UD2H            | Desktop     | [bdbf3d8792](https://linux-hardware.org/?probe=bdbf3d8792) | Dec 14, 2022 |
| ASUSTek       | P8H61-M LX3 R2.0            | Desktop     | [049fef0294](https://linux-hardware.org/?probe=049fef0294) | Dec 14, 2022 |
| Pro-B         | INSYS                       | Desktop     | [40650eefcc](https://linux-hardware.org/?probe=40650eefcc) | Dec 14, 2022 |
| Gigabyte      | Z87M-D3H                    | Desktop     | [88c6ca8956](https://linux-hardware.org/?probe=88c6ca8956) | Dec 14, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [2afff07992](https://linux-hardware.org/?probe=2afff07992) | Dec 14, 2022 |
| ASUSTek       | X302LA                      | Notebook    | [8404a0b0c6](https://linux-hardware.org/?probe=8404a0b0c6) | Dec 14, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YHS... | Notebook    | [14f87b8695](https://linux-hardware.org/?probe=14f87b8695) | Dec 13, 2022 |
| MSI           | MS-7318                     | Desktop     | [420ae8857b](https://linux-hardware.org/?probe=420ae8857b) | Dec 13, 2022 |
| Lenovo        | Aptio CRB SDK0E50510 WIN    | Mini pc     | [ce2a33caff](https://linux-hardware.org/?probe=ce2a33caff) | Dec 13, 2022 |
| ASUSTek       | A88XM-A                     | Desktop     | [64176404e2](https://linux-hardware.org/?probe=64176404e2) | Dec 13, 2022 |
| ASUSTek       | M3N                         | Notebook    | [ff772de294](https://linux-hardware.org/?probe=ff772de294) | Dec 13, 2022 |
| Dell          | Latitude 5520               | Notebook    | [7e5d86eaaf](https://linux-hardware.org/?probe=7e5d86eaaf) | Dec 13, 2022 |
| ASUSTek       | G75VW                       | Notebook    | [8d2a0ec4e4](https://linux-hardware.org/?probe=8d2a0ec4e4) | Dec 13, 2022 |
| Exo           | Smart Serie M               | Notebook    | [7fcf3d09bb](https://linux-hardware.org/?probe=7fcf3d09bb) | Dec 13, 2022 |
| MSI           | MS-B1591                    | Desktop     | [33cb107fb9](https://linux-hardware.org/?probe=33cb107fb9) | Dec 13, 2022 |
| ASUSTek       | P7H55-M SI                  | Desktop     | [973e367765](https://linux-hardware.org/?probe=973e367765) | Dec 13, 2022 |
| AZW           | SEi                         | Desktop     | [1ae245a379](https://linux-hardware.org/?probe=1ae245a379) | Dec 13, 2022 |
| AZW           | SEi                         | Desktop     | [18219c432d](https://linux-hardware.org/?probe=18219c432d) | Dec 13, 2022 |
| NetGear       | ReadyDATA 5200              | Desktop     | [2db45cfb13](https://linux-hardware.org/?probe=2db45cfb13) | Dec 13, 2022 |
| HUAWEI        | BOHK-WAX9X                  | Notebook    | [49fad98b7b](https://linux-hardware.org/?probe=49fad98b7b) | Dec 12, 2022 |
| Google        | Terra                       | Notebook    | [765deab389](https://linux-hardware.org/?probe=765deab389) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [95dc27194a](https://linux-hardware.org/?probe=95dc27194a) | Dec 12, 2022 |
| MSI           | GP73 Leopard 8RD            | Notebook    | [548de8bdae](https://linux-hardware.org/?probe=548de8bdae) | Dec 12, 2022 |
| Acer          | Aspire A515-56              | Notebook    | [5437de2b1b](https://linux-hardware.org/?probe=5437de2b1b) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [dc916ac78c](https://linux-hardware.org/?probe=dc916ac78c) | Dec 12, 2022 |
| Lenovo        | Yoga Slim 7 ProX 14IAH7 ... | Notebook    | [2bfcc16f6b](https://linux-hardware.org/?probe=2bfcc16f6b) | Dec 12, 2022 |
| Google        | Enguarde                    | Notebook    | [60cce42479](https://linux-hardware.org/?probe=60cce42479) | Dec 12, 2022 |
| Lenovo        | ThinkPad R61e 7650DHU       | Notebook    | [138f60e67c](https://linux-hardware.org/?probe=138f60e67c) | Dec 12, 2022 |
| Intel         | NUC6CAYB J23203-410         | Mini pc     | [e9c5ef16cd](https://linux-hardware.org/?probe=e9c5ef16cd) | Dec 12, 2022 |
| HP            | EliteBook 8460p             | Notebook    | [99c965b83f](https://linux-hardware.org/?probe=99c965b83f) | Dec 12, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [22ce155034](https://linux-hardware.org/?probe=22ce155034) | Dec 12, 2022 |
| Dell          | Latitude 5411               | Notebook    | [af806502e8](https://linux-hardware.org/?probe=af806502e8) | Dec 12, 2022 |
| Fujitsu       | D3417-B1 S26361-D3417-B1    | Desktop     | [fd77b80943](https://linux-hardware.org/?probe=fd77b80943) | Dec 12, 2022 |
| Acer          | Nitro AN515-51              | Notebook    | [918c340b04](https://linux-hardware.org/?probe=918c340b04) | Dec 12, 2022 |
| ASUSTek       | STRIX H270F GAMING          | Desktop     | [3b9b8bb589](https://linux-hardware.org/?probe=3b9b8bb589) | Dec 12, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [d1b0bc1c03](https://linux-hardware.org/?probe=d1b0bc1c03) | Dec 12, 2022 |
| Lenovo        | ThinkPad T470 20HES6HC00    | Notebook    | [ca9d609d9d](https://linux-hardware.org/?probe=ca9d609d9d) | Dec 12, 2022 |
| HP            | Laptop 15-db1xxx            | Notebook    | [3dcbd61f9e](https://linux-hardware.org/?probe=3dcbd61f9e) | Dec 12, 2022 |
| HP            | 1850                        | Desktop     | [af4f26481a](https://linux-hardware.org/?probe=af4f26481a) | Dec 11, 2022 |
| HP            | 1850                        | Desktop     | [28b194e897](https://linux-hardware.org/?probe=28b194e897) | Dec 11, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [cd7399049b](https://linux-hardware.org/?probe=cd7399049b) | Dec 11, 2022 |
| Intel         | Kabylake Platform           | Notebook    | [b5c2316016](https://linux-hardware.org/?probe=b5c2316016) | Dec 11, 2022 |
| Lenovo        | G770 20089                  | Notebook    | [f6f1441538](https://linux-hardware.org/?probe=f6f1441538) | Dec 11, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [11202d4caa](https://linux-hardware.org/?probe=11202d4caa) | Dec 11, 2022 |
| Gigabyte      | A320M-H-CF                  | Desktop     | [7d4b5e1c20](https://linux-hardware.org/?probe=7d4b5e1c20) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [754e028997](https://linux-hardware.org/?probe=754e028997) | Dec 11, 2022 |
| Lenovo        | G50-45 80E3                 | Notebook    | [fb2f97325d](https://linux-hardware.org/?probe=fb2f97325d) | Dec 11, 2022 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [822e79aa3e](https://linux-hardware.org/?probe=822e79aa3e) | Dec 11, 2022 |
| Dell          | Latitude 5480               | Notebook    | [01c96ca524](https://linux-hardware.org/?probe=01c96ca524) | Dec 11, 2022 |
| Dell          | Inspiron 13-5368            | Notebook    | [b4ea41e00f](https://linux-hardware.org/?probe=b4ea41e00f) | Dec 11, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING ... | Desktop     | [e3cecbe4be](https://linux-hardware.org/?probe=e3cecbe4be) | Dec 11, 2022 |
| Lenovo        | ThinkPad X270 20HMS16200    | Notebook    | [89e7835b90](https://linux-hardware.org/?probe=89e7835b90) | Dec 11, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3282a529f0](https://linux-hardware.org/?probe=3282a529f0) | Dec 11, 2022 |
| ASUSTek       | CM6330_CM6630_CM6730_CM6... | Desktop     | [32e7431c24](https://linux-hardware.org/?probe=32e7431c24) | Dec 11, 2022 |
| Supermicro    | C7SIM-Q                     | Desktop     | [76cf2b62db](https://linux-hardware.org/?probe=76cf2b62db) | Dec 11, 2022 |
| Notebook      | NJ50_70CU                   | Notebook    | [f77f39af95](https://linux-hardware.org/?probe=f77f39af95) | Dec 11, 2022 |
| ASUSTek       | ZenBook Pro Duo UX581GV_... | Notebook    | [4686ea3469](https://linux-hardware.org/?probe=4686ea3469) | Dec 11, 2022 |
| ASRock        | X370 Killer SLI/ac          | Desktop     | [83fc85f9e5](https://linux-hardware.org/?probe=83fc85f9e5) | Dec 10, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [400a0b555d](https://linux-hardware.org/?probe=400a0b555d) | Dec 10, 2022 |
| Dell          | Latitude E7240              | Notebook    | [e0aca47e1b](https://linux-hardware.org/?probe=e0aca47e1b) | Dec 10, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [b489057ccc](https://linux-hardware.org/?probe=b489057ccc) | Dec 10, 2022 |
| HP            | 1998                        | Desktop     | [b5e04c4f4c](https://linux-hardware.org/?probe=b5e04c4f4c) | Dec 10, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [5f72ad2758](https://linux-hardware.org/?probe=5f72ad2758) | Dec 10, 2022 |
| Google        | Peppy                       | Notebook    | [59f9af1c52](https://linux-hardware.org/?probe=59f9af1c52) | Dec 10, 2022 |
| HP            | 876C SMVB                   | Desktop     | [d6211ccceb](https://linux-hardware.org/?probe=d6211ccceb) | Dec 10, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [9a14eb6994](https://linux-hardware.org/?probe=9a14eb6994) | Dec 10, 2022 |
| ASUSTek       | ROG STRIX X570-I GAMING     | Desktop     | [7c41dddf3f](https://linux-hardware.org/?probe=7c41dddf3f) | Dec 10, 2022 |
| Toshiba       | TECRA A11                   | Notebook    | [766f95a2dd](https://linux-hardware.org/?probe=766f95a2dd) | Dec 10, 2022 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [89e8d0f23e](https://linux-hardware.org/?probe=89e8d0f23e) | Dec 10, 2022 |
| Xunlong       | Orange Pi PC                | Soc         | [ab1dd22124](https://linux-hardware.org/?probe=ab1dd22124) | Dec 10, 2022 |
| HP            | 339A                        | Desktop     | [ca1d494630](https://linux-hardware.org/?probe=ca1d494630) | Dec 10, 2022 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [dfceb62f5d](https://linux-hardware.org/?probe=dfceb62f5d) | Dec 09, 2022 |
| Lenovo        | ThinkPad 13 20J10046US      | Notebook    | [170accb6cc](https://linux-hardware.org/?probe=170accb6cc) | Dec 09, 2022 |
| CSL-Comput... | Mini PC AMD HX90            | Mini pc     | [31a77d0d59](https://linux-hardware.org/?probe=31a77d0d59) | Dec 09, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [a80714c4ec](https://linux-hardware.org/?probe=a80714c4ec) | Dec 09, 2022 |
| HP            | Elite x2 1013 G3            | Tablet      | [e8d1866113](https://linux-hardware.org/?probe=e8d1866113) | Dec 09, 2022 |
| Lenovo        | Yoga 7 14IAL7 82QE          | Convertible | [297991e0a2](https://linux-hardware.org/?probe=297991e0a2) | Dec 09, 2022 |
| ASRock        | X570 Pro4                   | Desktop     | [347fc5c7ec](https://linux-hardware.org/?probe=347fc5c7ec) | Dec 09, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [c09429d3ad](https://linux-hardware.org/?probe=c09429d3ad) | Dec 09, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [bb3d3b636f](https://linux-hardware.org/?probe=bb3d3b636f) | Dec 09, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [070127f3e8](https://linux-hardware.org/?probe=070127f3e8) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [b2aa17a680](https://linux-hardware.org/?probe=b2aa17a680) | Dec 09, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [416ad70d66](https://linux-hardware.org/?probe=416ad70d66) | Dec 08, 2022 |
| HP            | EliteBook 830 G8 Noteboo... | Notebook    | [5d96a0484a](https://linux-hardware.org/?probe=5d96a0484a) | Dec 08, 2022 |
| Supermicro    | X11SSZ-TLN4F                | Server      | [c37f8cd97a](https://linux-hardware.org/?probe=c37f8cd97a) | Dec 08, 2022 |
| HUAWEI        | KLVL-WXXW                   | Notebook    | [adea8bc8d8](https://linux-hardware.org/?probe=adea8bc8d8) | Dec 08, 2022 |
| Toshiba       | Satellite C850-1LJ          | Notebook    | [4af2ab112f](https://linux-hardware.org/?probe=4af2ab112f) | Dec 08, 2022 |
| Acer          | Veriton N2620G              | Desktop     | [2c4bd5a093](https://linux-hardware.org/?probe=2c4bd5a093) | Dec 08, 2022 |
| Dell          | 0VHWTR A02                  | Desktop     | [5b85a90055](https://linux-hardware.org/?probe=5b85a90055) | Dec 08, 2022 |
| ASUSTek       | N750JV                      | Notebook    | [e06c6025f3](https://linux-hardware.org/?probe=e06c6025f3) | Dec 08, 2022 |
| Lenovo        | ThinkPad T61 889502U        | Notebook    | [b9d0a07e47](https://linux-hardware.org/?probe=b9d0a07e47) | Dec 08, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [6d3946c1de](https://linux-hardware.org/?probe=6d3946c1de) | Dec 08, 2022 |
| Lenovo        | ThinkPad 13 2nd Gen 20J1... | Notebook    | [09de0ec660](https://linux-hardware.org/?probe=09de0ec660) | Dec 08, 2022 |
| Lenovo        | ThinkPad T60 1953PKK        | Notebook    | [fc308e2f1c](https://linux-hardware.org/?probe=fc308e2f1c) | Dec 08, 2022 |
| Lenovo        | ThinkPad X201 Tablet 309... | Notebook    | [e13e889312](https://linux-hardware.org/?probe=e13e889312) | Dec 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [b0f77fed1f](https://linux-hardware.org/?probe=b0f77fed1f) | Dec 08, 2022 |
| ASRock        | H470M-HVS                   | Desktop     | [2f4b3b1185](https://linux-hardware.org/?probe=2f4b3b1185) | Dec 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 3 21AHC... | Notebook    | [e56fd20ec9](https://linux-hardware.org/?probe=e56fd20ec9) | Dec 08, 2022 |
| HP            | ProLiant DL380 Gen9         | Server      | [d368f224c8](https://linux-hardware.org/?probe=d368f224c8) | Dec 08, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [9cf6cede24](https://linux-hardware.org/?probe=9cf6cede24) | Dec 08, 2022 |
| Supermicro    | X10SLH-F/X10SLM+-F          | Server      | [8617185fdc](https://linux-hardware.org/?probe=8617185fdc) | Dec 08, 2022 |
| Unknown       | Unknown                     | Desktop     | [3a5aa82738](https://linux-hardware.org/?probe=3a5aa82738) | Dec 07, 2022 |
| Unknown       | Unknown                     | Soc         | [3eae2be077](https://linux-hardware.org/?probe=3eae2be077) | Dec 07, 2022 |
| Dell          | 0RM5DR A00                  | Desktop     | [cd67b584bb](https://linux-hardware.org/?probe=cd67b584bb) | Dec 07, 2022 |
| ASUSTek       | ProArt Z690-CREATOR WIFI    | Desktop     | [611fd80398](https://linux-hardware.org/?probe=611fd80398) | Dec 07, 2022 |
| Unknown       | Unknown                     | Desktop     | [4d8d2c3a47](https://linux-hardware.org/?probe=4d8d2c3a47) | Dec 07, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [5e5a1fd920](https://linux-hardware.org/?probe=5e5a1fd920) | Dec 07, 2022 |
| ASUSTek       | STRIX Z270F GAMING          | Desktop     | [7766e8d043](https://linux-hardware.org/?probe=7766e8d043) | Dec 07, 2022 |
| Lenovo        | ThinkPad E495 20NES0J800    | Notebook    | [17182155b5](https://linux-hardware.org/?probe=17182155b5) | Dec 07, 2022 |
| Lenovo        | ThinkPad X230 2320CTO       | Notebook    | [b74f2893d0](https://linux-hardware.org/?probe=b74f2893d0) | Dec 07, 2022 |
| Panasonic     | CFMX4-1                     | Notebook    | [c25c16fc1a](https://linux-hardware.org/?probe=c25c16fc1a) | Dec 06, 2022 |
| Dell          | Latitude 5310               | Notebook    | [06d96a49a1](https://linux-hardware.org/?probe=06d96a49a1) | Dec 06, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [eb1b8bc98a](https://linux-hardware.org/?probe=eb1b8bc98a) | Dec 06, 2022 |
| ASUSTek       | PRIME B450M-K II            | Desktop     | [2a7f909902](https://linux-hardware.org/?probe=2a7f909902) | Dec 06, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [e2be1fe149](https://linux-hardware.org/?probe=e2be1fe149) | Dec 06, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | Notebook    | [4e43c26029](https://linux-hardware.org/?probe=4e43c26029) | Dec 06, 2022 |
| ASRock        | B75M R2.0                   | Desktop     | [93dc9d7b3e](https://linux-hardware.org/?probe=93dc9d7b3e) | Dec 06, 2022 |
| Dell          | Latitude 5411               | Notebook    | [62e5941721](https://linux-hardware.org/?probe=62e5941721) | Dec 06, 2022 |
| Dell          | Latitude 5411               | Notebook    | [e0815067bd](https://linux-hardware.org/?probe=e0815067bd) | Dec 06, 2022 |
| Dell          | Latitude 5310               | Notebook    | [f3801600ff](https://linux-hardware.org/?probe=f3801600ff) | Dec 06, 2022 |
| HP            | EliteBook 2570p             | Notebook    | [fc7d866c16](https://linux-hardware.org/?probe=fc7d866c16) | Dec 06, 2022 |
| Dell          | 0XHGV1 A00                  | Desktop     | [9b9778c525](https://linux-hardware.org/?probe=9b9778c525) | Dec 06, 2022 |
| ASUSTek       | P5K                         | Desktop     | [8e3fef0d6b](https://linux-hardware.org/?probe=8e3fef0d6b) | Dec 06, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X4S... | Notebook    | [03aba4d315](https://linux-hardware.org/?probe=03aba4d315) | Dec 06, 2022 |
| Lenovo        | ThinkPad X230 2325SDE       | Notebook    | [4dc49eeb10](https://linux-hardware.org/?probe=4dc49eeb10) | Dec 06, 2022 |
| ASUSTek       | CM1530                      | Desktop     | [3990cff263](https://linux-hardware.org/?probe=3990cff263) | Dec 06, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [0e42e5cbeb](https://linux-hardware.org/?probe=0e42e5cbeb) | Dec 06, 2022 |
| Dell          | 01XK1W A00                  | Desktop     | [e2ec28bd7c](https://linux-hardware.org/?probe=e2ec28bd7c) | Dec 06, 2022 |
| Lenovo        | ThinkPad L470 W10DG 20JV... | Notebook    | [5b72cdbdb8](https://linux-hardware.org/?probe=5b72cdbdb8) | Dec 05, 2022 |
| MSI           | H110M PRO-VD                | Desktop     | [64c80c03cf](https://linux-hardware.org/?probe=64c80c03cf) | Dec 05, 2022 |
| ASUSTek       | X756UQK                     | Notebook    | [b473216b84](https://linux-hardware.org/?probe=b473216b84) | Dec 05, 2022 |
| Gigabyte      | Z97-HD3                     | Desktop     | [9b7999b50d](https://linux-hardware.org/?probe=9b7999b50d) | Dec 05, 2022 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [b7b2f976e8](https://linux-hardware.org/?probe=b7b2f976e8) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [3027fc2c2f](https://linux-hardware.org/?probe=3027fc2c2f) | Dec 05, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [a07d55ca40](https://linux-hardware.org/?probe=a07d55ca40) | Dec 05, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [f8e6206ba6](https://linux-hardware.org/?probe=f8e6206ba6) | Dec 05, 2022 |
| ASUSTek       | PU403UA                     | Notebook    | [20007b4296](https://linux-hardware.org/?probe=20007b4296) | Dec 05, 2022 |
| Acer          | Aspire A315-23G             | Notebook    | [41e6f6a3fa](https://linux-hardware.org/?probe=41e6f6a3fa) | Dec 05, 2022 |
| GMKtec        | NucBox5                     | Notebook    | [cdfbbcc5b2](https://linux-hardware.org/?probe=cdfbbcc5b2) | Dec 04, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [267ffa24d1](https://linux-hardware.org/?probe=267ffa24d1) | Dec 04, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [f5be4eb37d](https://linux-hardware.org/?probe=f5be4eb37d) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [4d38cbb41a](https://linux-hardware.org/?probe=4d38cbb41a) | Dec 04, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING     | Desktop     | [7428311d73](https://linux-hardware.org/?probe=7428311d73) | Dec 04, 2022 |
| Toshiba       | dynabook R63/P              | Notebook    | [f51571b62c](https://linux-hardware.org/?probe=f51571b62c) | Dec 04, 2022 |
| Intel         | NUC7i5BNB J31144-304        | Mini pc     | [cc6834a359](https://linux-hardware.org/?probe=cc6834a359) | Dec 04, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [b53efc176f](https://linux-hardware.org/?probe=b53efc176f) | Dec 04, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [9ee4df50e7](https://linux-hardware.org/?probe=9ee4df50e7) | Dec 04, 2022 |
| ASUSTek       | LEUCITE3                    | Desktop     | [4f28bb5933](https://linux-hardware.org/?probe=4f28bb5933) | Dec 04, 2022 |
| HP            | 339A                        | Desktop     | [91ed08d2a9](https://linux-hardware.org/?probe=91ed08d2a9) | Dec 04, 2022 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b475911aaf](https://linux-hardware.org/?probe=b475911aaf) | Dec 03, 2022 |
| Unknown       | Unknown                     | Soc         | [6fd63c60ab](https://linux-hardware.org/?probe=6fd63c60ab) | Dec 03, 2022 |
| Dell          | Inspiron 15-5578            | Notebook    | [61f5950e07](https://linux-hardware.org/?probe=61f5950e07) | Dec 03, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [9053b5cb8a](https://linux-hardware.org/?probe=9053b5cb8a) | Dec 03, 2022 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [91d50f0379](https://linux-hardware.org/?probe=91d50f0379) | Dec 03, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [c7cf7a1604](https://linux-hardware.org/?probe=c7cf7a1604) | Dec 03, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [67c278b32e](https://linux-hardware.org/?probe=67c278b32e) | Dec 03, 2022 |
| ASUSTek       | S500CA                      | Notebook    | [7145280e9e](https://linux-hardware.org/?probe=7145280e9e) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | Desktop     | [dc890ad363](https://linux-hardware.org/?probe=dc890ad363) | Dec 03, 2022 |
| MSI           | B450M BAZOOKA PLUS          | Desktop     | [a087ddb18f](https://linux-hardware.org/?probe=a087ddb18f) | Dec 03, 2022 |
| Acer          | Aspire A315-21              | Notebook    | [91eb1913d7](https://linux-hardware.org/?probe=91eb1913d7) | Dec 03, 2022 |
| Unknown       | Unknown                     | Notebook    | [40917baf56](https://linux-hardware.org/?probe=40917baf56) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [61e955b5a6](https://linux-hardware.org/?probe=61e955b5a6) | Dec 03, 2022 |
| ASUSTek       | ROG STRIX X670E-E GAMING... | Desktop     | [dc9c0686e7](https://linux-hardware.org/?probe=dc9c0686e7) | Dec 03, 2022 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [28ab0eb248](https://linux-hardware.org/?probe=28ab0eb248) | Dec 03, 2022 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [c300b0a438](https://linux-hardware.org/?probe=c300b0a438) | Dec 03, 2022 |
| Lenovo        | XiaoXinPro 16ACH 2021 82... | Notebook    | [2085f260e1](https://linux-hardware.org/?probe=2085f260e1) | Dec 03, 2022 |
| Lenovo        | ThinkPad X280 20KE0015BR    | Notebook    | [4c65d4e572](https://linux-hardware.org/?probe=4c65d4e572) | Dec 03, 2022 |
| Dell          | 0GY6Y8 A01                  | Desktop     | [f86e02dee0](https://linux-hardware.org/?probe=f86e02dee0) | Dec 03, 2022 |
| ASUSTek       | Z170I PRO GAMING            | Desktop     | [bf8f5e2683](https://linux-hardware.org/?probe=bf8f5e2683) | Dec 03, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21E3C... | Notebook    | [c99bd4ef76](https://linux-hardware.org/?probe=c99bd4ef76) | Dec 03, 2022 |
| Tactus        | GeoFlex 110                 | Convertible | [dfe1b939d2](https://linux-hardware.org/?probe=dfe1b939d2) | Dec 02, 2022 |
| Intel         | DP45SG AAE27733-401         | Desktop     | [bc19b3f6a3](https://linux-hardware.org/?probe=bc19b3f6a3) | Dec 02, 2022 |
| Dell          | Inspiron 5566               | Notebook    | [54e06d37fc](https://linux-hardware.org/?probe=54e06d37fc) | Dec 02, 2022 |
| ASUSTek       | N750JV                      | Notebook    | [0fc50d63c4](https://linux-hardware.org/?probe=0fc50d63c4) | Dec 02, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [93c4564635](https://linux-hardware.org/?probe=93c4564635) | Dec 02, 2022 |
| Dell          | Latitude 5591               | Notebook    | [f5735acca7](https://linux-hardware.org/?probe=f5735acca7) | Dec 02, 2022 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [4dc73d8f69](https://linux-hardware.org/?probe=4dc73d8f69) | Dec 02, 2022 |
| HP            | Unknown                     | Notebook    | [741029c3af](https://linux-hardware.org/?probe=741029c3af) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | Desktop     | [5476b73cb7](https://linux-hardware.org/?probe=5476b73cb7) | Dec 02, 2022 |
| Aquarius      | NS585                       | Notebook    | [bbd3bd3ca6](https://linux-hardware.org/?probe=bbd3bd3ca6) | Dec 02, 2022 |
| Lenovo        | 3753 SDK0T76479 WIN 3423... | Desktop     | [6d07106192](https://linux-hardware.org/?probe=6d07106192) | Dec 02, 2022 |
| Aquarius      | NS585                       | Notebook    | [50222418e5](https://linux-hardware.org/?probe=50222418e5) | Dec 02, 2022 |
| Aquarius      | NS585                       | Notebook    | [d55d40681f](https://linux-hardware.org/?probe=d55d40681f) | Dec 02, 2022 |
| Aquarius      | NS585                       | Notebook    | [9013a1cce6](https://linux-hardware.org/?probe=9013a1cce6) | Dec 02, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [767ac17f22](https://linux-hardware.org/?probe=767ac17f22) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [38ce706249](https://linux-hardware.org/?probe=38ce706249) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [546f2b82c9](https://linux-hardware.org/?probe=546f2b82c9) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G731GU_G731GU     | Notebook    | [000d536e95](https://linux-hardware.org/?probe=000d536e95) | Dec 02, 2022 |
| HP            | 620                         | Notebook    | [6be09298b6](https://linux-hardware.org/?probe=6be09298b6) | Dec 01, 2022 |
| Lenovo        | ThinkPad T440p 20AN0079M... | Notebook    | [79261239c1](https://linux-hardware.org/?probe=79261239c1) | Dec 01, 2022 |
| MSI           | MAG B550 TOMAHAWK MAX WI... | Desktop     | [51cf6d10e7](https://linux-hardware.org/?probe=51cf6d10e7) | Dec 01, 2022 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [e03c6b53ed](https://linux-hardware.org/?probe=e03c6b53ed) | Dec 01, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21EES... | Notebook    | [674157de54](https://linux-hardware.org/?probe=674157de54) | Dec 01, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [cccf492c06](https://linux-hardware.org/?probe=cccf492c06) | Dec 01, 2022 |
| Intel         | NUC11PABi5 K90634-305       | Mini pc     | [4c7e1d5bc4](https://linux-hardware.org/?probe=4c7e1d5bc4) | Dec 01, 2022 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [becc2328fd](https://linux-hardware.org/?probe=becc2328fd) | Dec 01, 2022 |
| ASUSTek       | P5B                         | Desktop     | [44f13beada](https://linux-hardware.org/?probe=44f13beada) | Dec 01, 2022 |
| Gigabyte      | F2A88XM-D3H                 | Desktop     | [f5a5a30379](https://linux-hardware.org/?probe=f5a5a30379) | Dec 01, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [3131016a26](https://linux-hardware.org/?probe=3131016a26) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | Notebook    | [73c388fb61](https://linux-hardware.org/?probe=73c388fb61) | Dec 01, 2022 |
| MSI           | GL65 Leopard 10SDR          | Notebook    | [6d44ef56c9](https://linux-hardware.org/?probe=6d44ef56c9) | Dec 01, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [0f27e558f3](https://linux-hardware.org/?probe=0f27e558f3) | Dec 01, 2022 |
| Raspberry ... | Raspberry Pi 3 Model B P... | Soc         | [5fa6ceed90](https://linux-hardware.org/?probe=5fa6ceed90) | Dec 01, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [f0dba35258](https://linux-hardware.org/?probe=f0dba35258) | Dec 01, 2022 |
| sunxi         | FriendlyARM NanoPi NEO 2    | Soc         | [f1e2cbe354](https://linux-hardware.org/?probe=f1e2cbe354) | Nov 30, 2022 |
| Gigabyte      | Z390 M GAMING-CF            | Desktop     | [baa969bf8b](https://linux-hardware.org/?probe=baa969bf8b) | Nov 30, 2022 |
| HP            | Pavilion dv5                | Notebook    | [0fc7017b0c](https://linux-hardware.org/?probe=0fc7017b0c) | Nov 30, 2022 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [183243daeb](https://linux-hardware.org/?probe=183243daeb) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | Desktop     | [edadb85201](https://linux-hardware.org/?probe=edadb85201) | Nov 30, 2022 |
| Pegatron      | BYT-X1                      | Desktop     | [b248df8671](https://linux-hardware.org/?probe=b248df8671) | Nov 30, 2022 |
| Dell          | 0Y2G81 A01                  | Server      | [7ce42afb90](https://linux-hardware.org/?probe=7ce42afb90) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z490-A GAMING     | Desktop     | [dc5ec6eb84](https://linux-hardware.org/?probe=dc5ec6eb84) | Nov 30, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [6b21f343c3](https://linux-hardware.org/?probe=6b21f343c3) | Nov 30, 2022 |
| Notebook      | RIM2520                     | Notebook    | [5f66abbb8b](https://linux-hardware.org/?probe=5f66abbb8b) | Nov 30, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [952c3681c0](https://linux-hardware.org/?probe=952c3681c0) | Nov 30, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [3e3ccd1471](https://linux-hardware.org/?probe=3e3ccd1471) | Nov 30, 2022 |
| Lenovo        | ThinkPad L13 Yoga Gen 2 ... | Convertible | [00232e7345](https://linux-hardware.org/?probe=00232e7345) | Nov 29, 2022 |
| MSI           | B560M-A PRO                 | Desktop     | [81bf84e7e5](https://linux-hardware.org/?probe=81bf84e7e5) | Nov 29, 2022 |
| HP            | Elite x2 1011 G1 Tablet     | Notebook    | [1a00258de3](https://linux-hardware.org/?probe=1a00258de3) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [e0187bc636](https://linux-hardware.org/?probe=e0187bc636) | Nov 29, 2022 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [9dd6019148](https://linux-hardware.org/?probe=9dd6019148) | Nov 29, 2022 |
| BESSTAR Te... | UM700                       | Desktop     | [a97334be81](https://linux-hardware.org/?probe=a97334be81) | Nov 29, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [eae94e440a](https://linux-hardware.org/?probe=eae94e440a) | Nov 29, 2022 |
| Apple         | MacBookAir6,2               | Notebook    | [99eb1cfce0](https://linux-hardware.org/?probe=99eb1cfce0) | Nov 29, 2022 |
| ASUSTek       | P5KPL-CM                    | Desktop     | [a20e18af73](https://linux-hardware.org/?probe=a20e18af73) | Nov 29, 2022 |
| Dell          | Latitude 7490               | Notebook    | [8934413cf0](https://linux-hardware.org/?probe=8934413cf0) | Nov 29, 2022 |
| ASRock        | H510M-HDV                   | Desktop     | [03a1675c85](https://linux-hardware.org/?probe=03a1675c85) | Nov 29, 2022 |
| Lenovo        | V310-14IKB 80T2             | Notebook    | [b7c976ef9c](https://linux-hardware.org/?probe=b7c976ef9c) | Nov 29, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [9c45563fb6](https://linux-hardware.org/?probe=9c45563fb6) | Nov 29, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [a95de3b373](https://linux-hardware.org/?probe=a95de3b373) | Nov 29, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [9c87ab493e](https://linux-hardware.org/?probe=9c87ab493e) | Nov 29, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [262228b1fb](https://linux-hardware.org/?probe=262228b1fb) | Nov 29, 2022 |
| ASUSTek       | ZenBook UX325EA_UX325EA     | Notebook    | [1e52ea39e4](https://linux-hardware.org/?probe=1e52ea39e4) | Nov 28, 2022 |
| Gigabyte      | F2A55M-HD2                  | Desktop     | [8b3da34947](https://linux-hardware.org/?probe=8b3da34947) | Nov 28, 2022 |
| Lenovo        | ThinkPad X301 2776LEG       | Notebook    | [ebaea0c805](https://linux-hardware.org/?probe=ebaea0c805) | Nov 28, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [8d0514a0df](https://linux-hardware.org/?probe=8d0514a0df) | Nov 28, 2022 |
| Dell          | Precision M6400             | Notebook    | [05f69c6917](https://linux-hardware.org/?probe=05f69c6917) | Nov 28, 2022 |
| HP            | ProBook 450 G5              | Notebook    | [e94fd64204](https://linux-hardware.org/?probe=e94fd64204) | Nov 28, 2022 |
| ASUSTek       | PN52                        | Mini pc     | [1e84d5c704](https://linux-hardware.org/?probe=1e84d5c704) | Nov 28, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [edc0678b85](https://linux-hardware.org/?probe=edc0678b85) | Nov 28, 2022 |
| ECS           | H61H2-M13                   | Desktop     | [88988d4d0d](https://linux-hardware.org/?probe=88988d4d0d) | Nov 28, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [076eeadd80](https://linux-hardware.org/?probe=076eeadd80) | Nov 28, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [f149afb5d1](https://linux-hardware.org/?probe=f149afb5d1) | Nov 28, 2022 |
| HP            | 212B                        | Desktop     | [53471968c2](https://linux-hardware.org/?probe=53471968c2) | Nov 28, 2022 |
| ASUSTek       | N61Vg                       | Notebook    | [b5cc07b253](https://linux-hardware.org/?probe=b5cc07b253) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BUS03J00    | Notebook    | [8423f90db0](https://linux-hardware.org/?probe=8423f90db0) | Nov 27, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [e0e0efb9be](https://linux-hardware.org/?probe=e0e0efb9be) | Nov 27, 2022 |
| Lenovo        | ThinkPad T520 4243F53       | Notebook    | [8f9e96442a](https://linux-hardware.org/?probe=8f9e96442a) | Nov 27, 2022 |
| Tactus        | GeoBook 140                 | Notebook    | [e3f4d734da](https://linux-hardware.org/?probe=e3f4d734da) | Nov 27, 2022 |
| ASUSTek       | VivoBook S15 X510UF         | Notebook    | [7bd68a8bb1](https://linux-hardware.org/?probe=7bd68a8bb1) | Nov 27, 2022 |
| HP            | Compaq nx9110 (DU432EA#A... | Notebook    | [1b54092e14](https://linux-hardware.org/?probe=1b54092e14) | Nov 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [32bfa52fc1](https://linux-hardware.org/?probe=32bfa52fc1) | Nov 27, 2022 |
| Lenovo        | ThinkPad T450 20BV0001US    | Notebook    | [3d1b8f282a](https://linux-hardware.org/?probe=3d1b8f282a) | Nov 27, 2022 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [f1ef96a2e6](https://linux-hardware.org/?probe=f1ef96a2e6) | Nov 26, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [8b47bbf475](https://linux-hardware.org/?probe=8b47bbf475) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [c58c83e367](https://linux-hardware.org/?probe=c58c83e367) | Nov 26, 2022 |
| Dell          | 0D24M8 A00                  | Desktop     | [85b508d6d3](https://linux-hardware.org/?probe=85b508d6d3) | Nov 26, 2022 |
| HP            | Laptop 15-da3xxx            | Notebook    | [335fce26dd](https://linux-hardware.org/?probe=335fce26dd) | Nov 26, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [8c389cf5d6](https://linux-hardware.org/?probe=8c389cf5d6) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [2902b75068](https://linux-hardware.org/?probe=2902b75068) | Nov 26, 2022 |
| HP            | Laptop 15s-du3xxx           | Notebook    | [973662f8d5](https://linux-hardware.org/?probe=973662f8d5) | Nov 26, 2022 |
| Lenovo        | ThinkPad T495 20NJS0L100    | Notebook    | [1e9e7f34df](https://linux-hardware.org/?probe=1e9e7f34df) | Nov 26, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [bede773ce4](https://linux-hardware.org/?probe=bede773ce4) | Nov 26, 2022 |
| Dell          | 05XGC8 A00                  | Desktop     | [6ea1a60122](https://linux-hardware.org/?probe=6ea1a60122) | Nov 26, 2022 |
| ASUSTek       | A6R                         | Notebook    | [68f38deab1](https://linux-hardware.org/?probe=68f38deab1) | Nov 26, 2022 |
| Dell          | Latitude E7240              | Notebook    | [634ebb2a88](https://linux-hardware.org/?probe=634ebb2a88) | Nov 25, 2022 |
| HP            | Pavilion TS Sleekbook 14    | Notebook    | [26440cddbb](https://linux-hardware.org/?probe=26440cddbb) | Nov 25, 2022 |
| MSI           | Creator 15M A9SD            | Notebook    | [a15ef33296](https://linux-hardware.org/?probe=a15ef33296) | Nov 25, 2022 |
| Lenovo        | ThinkPad E14 20RBS3LE00     | Notebook    | [83203a04f2](https://linux-hardware.org/?probe=83203a04f2) | Nov 25, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [2dfd7f3926](https://linux-hardware.org/?probe=2dfd7f3926) | Nov 25, 2022 |
| Lenovo        | ThinkPad E470 20H2S00700    | Notebook    | [f82ee02c50](https://linux-hardware.org/?probe=f82ee02c50) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [9e69bdbaff](https://linux-hardware.org/?probe=9e69bdbaff) | Nov 25, 2022 |
| Fujitsu       | LIFEBOOK E756               | Notebook    | [16acde36ab](https://linux-hardware.org/?probe=16acde36ab) | Nov 25, 2022 |
| Dell          | 0PV3YR A05                  | Server      | [618ea5fb0e](https://linux-hardware.org/?probe=618ea5fb0e) | Nov 25, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [68e1087fde](https://linux-hardware.org/?probe=68e1087fde) | Nov 25, 2022 |
| Apple         | Mac-00BE6ED71E35EB86 iMa... | All in one  | [165626e7d0](https://linux-hardware.org/?probe=165626e7d0) | Nov 25, 2022 |
| HP            | 255 G7 Notebook PC          | Notebook    | [f5a6bcf0fb](https://linux-hardware.org/?probe=f5a6bcf0fb) | Nov 24, 2022 |
| ASUSTek       | X551CAP                     | Notebook    | [f40e3110d0](https://linux-hardware.org/?probe=f40e3110d0) | Nov 24, 2022 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Debian/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| Debian 11                       | 5319      | 62.09%  |
| Debian 10                       | 1745      | 20.37%  |
| Debian Testing                  | 644       | 7.52%   |
| Debian 9                        | 320       | 3.74%   |
| Debian Unstable                 | 262       | 3.06%   |
| Debian                          | 171       | 2%      |
| Debian 11-updates               | 46        | 0.54%   |
| Debian 8                        | 38        | 0.44%   |
| Debian Testing/unstable         | 5         | 0.06%   |
| Debian Sid                      | 4         | 0.05%   |
| Debian 7                        | 4         | 0.05%   |
| Debian Testing-proposed-updates | 3         | 0.04%   |
| Debian 21                       | 2         | 0.02%   |
| Debian 99                       | 1         | 0.01%   |
| Debian 6                        | 1         | 0.01%   |
| Debian 16                       | 1         | 0.01%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Debian | 8330      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version         | Computers | Percent |
|-----------------|-----------|---------|
| 5.10.0-8-amd64  | 978       | 10.3%   |
| 5.10.0-7-amd64  | 691       | 7.28%   |
| 5.10.0-10-amd64 | 574       | 6.04%   |
| 5.10.0-16-amd64 | 370       | 3.9%    |
| 5.10.0-9-amd64  | 324       | 3.41%   |
| 5.10.0-19-amd64 | 285       | 3%      |
| 5.10.0-18-amd64 | 277       | 2.92%   |
| 5.10.0-13-amd64 | 261       | 2.75%   |
| 5.10.0-20-amd64 | 219       | 2.31%   |
| 5.10.0-11-amd64 | 194       | 2.04%   |
| 4.19.0-6-amd64  | 145       | 1.53%   |
| 4.19.0-9-amd64  | 143       | 1.51%   |
| 5.10.0-2-amd64  | 140       | 1.47%   |
| 5.10.0-14-amd64 | 140       | 1.47%   |
| 4.19.0-13-amd64 | 125       | 1.32%   |
| 5.10.0-17-amd64 | 124       | 1.31%   |
| 4.19.0-8-amd64  | 120       | 1.26%   |
| 4.19.0-16-amd64 | 109       | 1.15%   |
| 4.19.0-14-amd64 | 104       | 1.1%    |
| 5.15.0-2-amd64  | 95        | 1%      |
| 4.19.0-17-amd64 | 94        | 0.99%   |
| 5.10.0-15-amd64 | 92        | 0.97%   |
| 4.19.0-12-amd64 | 88        | 0.93%   |
| 4.19.0-10-amd64 | 87        | 0.92%   |
| 5.10.0-12-amd64 | 73        | 0.77%   |
| 4.9.0-8-amd64   | 70        | 0.74%   |
| 5.10.0-6-amd64  | 66        | 0.69%   |
| 5.6.0-2-amd64   | 53        | 0.56%   |
| 5.18.0-2-amd64  | 52        | 0.55%   |
| 6.0.0-6-amd64   | 48        | 0.51%   |
| 4.19.0-5-amd64  | 48        | 0.51%   |
| 5.4.0-4-amd64   | 45        | 0.47%   |
| 5.7.0-1-amd64   | 44        | 0.46%   |
| 5.10.0-3-amd64  | 44        | 0.46%   |
| 5.17.0-1-amd64  | 42        | 0.44%   |
| 5.19.0-2-amd64  | 41        | 0.43%   |
| 5.19.0-1-amd64  | 40        | 0.42%   |
| 4.19.0-11-amd64 | 40        | 0.42%   |
| 5.18.0-4-amd64  | 37        | 0.39%   |
| 6.0.0-2-amd64   | 36        | 0.38%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10.0  | 4799      | 54.21%  |
| 4.19.0  | 1232      | 13.92%  |
| 4.9.0   | 241       | 2.72%   |
| 5.18.0  | 196       | 2.21%   |
| 6.0.0   | 193       | 2.18%   |
| 5.15.0  | 159       | 1.8%    |
| 5.9.0   | 150       | 1.69%   |
| 5.16.0  | 128       | 1.45%   |
| 5.7.0   | 121       | 1.37%   |
| 5.8.0   | 120       | 1.36%   |
| 5.4.0   | 118       | 1.33%   |
| 5.19.0  | 113       | 1.28%   |
| 5.6.0   | 100       | 1.13%   |
| 5.14.0  | 91        | 1.03%   |
| 5.17.0  | 71        | 0.8%    |
| 5.13.19 | 52        | 0.59%   |
| 5.3.0   | 39        | 0.44%   |
| 5.5.0   | 32        | 0.36%   |
| 6.1.0   | 28        | 0.32%   |
| 5.11.22 | 27        | 0.3%    |
| 5.2.0   | 21        | 0.24%   |
| 4.18.0  | 21        | 0.24%   |
| 5.15.32 | 19        | 0.21%   |
| 5.15.74 | 18        | 0.2%    |
| 5.15.39 | 18        | 0.2%    |
| 3.16.0  | 18        | 0.2%    |
| 5.15.35 | 17        | 0.19%   |
| 5.15.30 | 16        | 0.18%   |
| 5.4.106 | 15        | 0.17%   |
| 5.15.76 | 15        | 0.17%   |
| 5.10.92 | 15        | 0.17%   |
| 5.15.53 | 14        | 0.16%   |
| 4.15.18 | 14        | 0.16%   |
| 5.15.61 | 12        | 0.14%   |
| 5.4.78  | 11        | 0.12%   |
| 5.13.0  | 11        | 0.12%   |
| 5.4.65  | 9         | 0.1%    |
| 5.12.0  | 9         | 0.1%    |
| 5.10.63 | 8         | 0.09%   |
| 4.17.0  | 8         | 0.09%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.10    | 4901      | 55.61%  |
| 4.19    | 1248      | 14.16%  |
| 5.15    | 339       | 3.85%   |
| 4.9     | 251       | 2.85%   |
| 5.4     | 218       | 2.47%   |
| 5.18    | 209       | 2.37%   |
| 6.0     | 206       | 2.34%   |
| 5.9     | 159       | 1.8%    |
| 5.16    | 138       | 1.57%   |
| 5.8     | 132       | 1.5%    |
| 5.19    | 131       | 1.49%   |
| 5.7     | 129       | 1.46%   |
| 5.6     | 110       | 1.25%   |
| 5.14    | 101       | 1.15%   |
| 5.17    | 86        | 0.98%   |
| 5.13    | 76        | 0.86%   |
| 5.3     | 64        | 0.73%   |
| 5.11    | 50        | 0.57%   |
| 5.5     | 38        | 0.43%   |
| 6.1     | 30        | 0.34%   |
| 5.2     | 26        | 0.3%    |
| 4.18    | 22        | 0.25%   |
| 4.15    | 19        | 0.22%   |
| 3.16    | 18        | 0.2%    |
| 5.12    | 16        | 0.18%   |
| 5.0     | 13        | 0.15%   |
| 4.4     | 12        | 0.14%   |
| 5       | 11        | 0.12%   |
| 4.17    | 8         | 0.09%   |
| 4.1     | 7         | 0.08%   |
| 5.1     | 6         | 0.07%   |
| 4.14    | 6         | 0.07%   |
| 3.10    | 4         | 0.05%   |
| 4.8     | 3         | 0.03%   |
| 4.20    | 3         | 0.03%   |
| 4.16    | 3         | 0.03%   |
| 4.13    | 3         | 0.03%   |
| 4.10    | 2         | 0.02%   |
| 3.18    | 2         | 0.02%   |
| 5.4.104 | 1         | 0.01%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 7806      | 93.69%  |
| i686    | 284       | 3.41%   |
| aarch64 | 174       | 2.09%   |
| armv7l  | 49        | 0.59%   |
| riscv64 | 7         | 0.08%   |
| ppc64   | 6         | 0.07%   |
| i586    | 2         | 0.02%   |
| sh4a    | 1         | 0.01%   |
| ppc64le | 1         | 0.01%   |
| mips64  | 1         | 0.01%   |
| armv6l  | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| Unknown           | 2762      | 32.4%   |
| GNOME             | 1882      | 22.07%  |
| XFCE              | 1052      | 12.34%  |
| KDE5              | 968       | 11.35%  |
| MATE              | 354       | 4.15%   |
| X-Cinnamon        | 276       | 3.24%   |
| LXDE              | 250       | 2.93%   |
| Cinnamon          | 243       | 2.85%   |
| KDE               | 207       | 2.43%   |
| LXQt              | 125       | 1.47%   |
| i3                | 122       | 1.43%   |
| GNOME Flashback   | 52        | 0.61%   |
| Openbox           | 49        | 0.57%   |
| lightdm-xsession  | 42        | 0.49%   |
| Budgie            | 24        | 0.28%   |
| trinity           | 23        | 0.27%   |
| GNOME Classic     | 20        | 0.23%   |
| awesome           | 9         | 0.11%   |
| fluxbox           | 8         | 0.09%   |
| sway              | 7         | 0.08%   |
| KDE4              | 6         | 0.07%   |
| Enlightenment     | 5         | 0.06%   |
| ICEWM             | 4         | 0.05%   |
| DWM               | 4         | 0.05%   |
| bspwm             | 4         | 0.05%   |
| x-session-manager | 3         | 0.04%   |
| default           | 3         | 0.04%   |
| Cutefish          | 3         | 0.04%   |
| xmonad            | 2         | 0.02%   |
| Unity             | 2         | 0.02%   |
| Phosh:GNOME       | 2         | 0.02%   |
| GNUstep           | 2         | 0.02%   |
| fvwm              | 2         | 0.02%   |
| wmaker-common     | 1         | 0.01%   |
| UKUI              | 1         | 0.01%   |
| matchbox          | 1         | 0.01%   |
| jwm               | 1         | 0.01%   |
| i3-with-shmlog    | 1         | 0.01%   |
| i3-gaps           | 1         | 0.01%   |
| e16-session       | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 4516      | 53.22%  |
| Unknown     | 1892      | 22.3%   |
| Wayland     | 1239      | 14.6%   |
| Tty         | 834       | 9.83%   |
| Web         | 2         | 0.02%   |
| Unspecified | 2         | 0.02%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3952      | 46.38%  |
| GDM     | 1365      | 16.02%  |
| LightDM | 1263      | 14.82%  |
| SDDM    | 939       | 11.02%  |
| TDM     | 597       | 7.01%   |
| GDM3    | 304       | 3.57%   |
| XDM     | 36        | 0.42%   |
| SLiM    | 28        | 0.33%   |
| NODM    | 16        | 0.19%   |
| KDM     | 12        | 0.14%   |
| LXDM    | 6         | 0.07%   |
| WDM     | 2         | 0.02%   |
| Ly      | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 2660      | 31.42%  |
| Unknown | 1388      | 16.39%  |
| ru_RU   | 1031      | 12.18%  |
| de_DE   | 485       | 5.73%   |
| fr_FR   | 409       | 4.83%   |
| en_GB   | 401       | 4.74%   |
| pt_BR   | 262       | 3.09%   |
| es_ES   | 231       | 2.73%   |
| it_IT   | 204       | 2.41%   |
| pl_PL   | 121       | 1.43%   |
| C       | 120       | 1.42%   |
| en_CA   | 107       | 1.26%   |
| en_AU   | 105       | 1.24%   |
| zh_CN   | 57        | 0.67%   |
| es_MX   | 56        | 0.66%   |
| en_IN   | 54        | 0.64%   |
| en_IE   | 46        | 0.54%   |
| es_AR   | 43        | 0.51%   |
| hu_HU   | 42        | 0.5%    |
| es_VE   | 36        | 0.43%   |
| es_CL   | 35        | 0.41%   |
| de_CH   | 31        | 0.37%   |
| ja_JP   | 30        | 0.35%   |
| pt_PT   | 28        | 0.33%   |
| de_AT   | 28        | 0.33%   |
| nl_NL   | 25        | 0.3%    |
| cs_CZ   | 24        | 0.28%   |
| en_NZ   | 22        | 0.26%   |
| en_ZA   | 21        | 0.25%   |
| sv_SE   | 19        | 0.22%   |
| fi_FI   | 17        | 0.2%    |
| ru_UA   | 15        | 0.18%   |
| es_CO   | 15        | 0.18%   |
| nl_BE   | 14        | 0.17%   |
| fr_BE   | 13        | 0.15%   |
| uk_UA   | 12        | 0.14%   |
| ko_KR   | 12        | 0.14%   |
| fr_CH   | 12        | 0.14%   |
| en_SG   | 12        | 0.14%   |
| tr_TR   | 11        | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 4377      | 51.9%   |
| BIOS | 4057      | 48.1%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type       | Computers | Percent |
|------------|-----------|---------|
| Ext4       | 5859      | 69.77%  |
| Overlay    | 1774      | 21.12%  |
| Btrfs      | 290       | 3.45%   |
| Unknown    | 168       | 2%      |
| Zfs        | 105       | 1.25%   |
| Xfs        | 102       | 1.21%   |
| Ext3       | 27        | 0.32%   |
| Ext2       | 24        | 0.29%   |
| Tmpfs      | 15        | 0.18%   |
| Rootfs     | 14        | 0.17%   |
| Aufs       | 7         | 0.08%   |
| F2fs       | 6         | 0.07%   |
| XXXXXXX    | 2         | 0.02%   |
| Ubifs      | 2         | 0.02%   |
| Jfs        | 2         | 0.02%   |
| Fuse.sshfs | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 4640      | 54.66%  |
| MBR     | 2173      | 25.6%   |
| Unknown | 1676      | 19.74%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6869      | 81.49%  |
| Yes       | 1560      | 18.51%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 5931      | 70.36%  |
| Yes       | 2498      | 29.64%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1316      | 15.8%   |
| Lenovo                  | 1227      | 14.73%  |
| Hewlett-Packard         | 897       | 10.77%  |
| Dell                    | 884       | 10.61%  |
| Apple                   | 653       | 7.84%   |
| Gigabyte Technology     | 557       | 6.69%   |
| MSI                     | 404       | 4.85%   |
| ASRock                  | 336       | 4.03%   |
| Acer                    | 300       | 3.6%    |
| Intel                   | 184       | 2.21%   |
| Google                  | 142       | 1.7%    |
| Raspberry Pi Foundation | 115       | 1.38%   |
| Unknown                 | 106       | 1.27%   |
| Supermicro              | 81        | 0.97%   |
| Toshiba                 | 71        | 0.85%   |
| Samsung Electronics     | 69        | 0.83%   |
| Fujitsu                 | 51        | 0.61%   |
| ECS                     | 49        | 0.59%   |
| Aquarius                | 46        | 0.55%   |
| Sony                    | 39        | 0.47%   |
| HUAWEI                  | 39        | 0.47%   |
| Foxconn                 | 37        | 0.44%   |
| Positivo                | 25        | 0.3%    |
| Notebook                | 24        | 0.29%   |
| ASRockRack              | 23        | 0.28%   |
| Medion                  | 22        | 0.26%   |
| AZW                     | 21        | 0.25%   |
| Pegatron                | 20        | 0.24%   |
| IBM                     | 20        | 0.24%   |
| Biostar                 | 20        | 0.24%   |
| Fujitsu Siemens         | 17        | 0.2%    |
| Alienware               | 17        | 0.2%    |
| Microsoft               | 15        | 0.18%   |
| Panasonic               | 14        | 0.17%   |
| Packard Bell            | 14        | 0.17%   |
| sunxi                   | 13        | 0.16%   |
| Hardkernel              | 13        | 0.16%   |
| Pine Microsystems       | 12        | 0.14%   |
| AMI                     | 12        | 0.14%   |
| Huanan                  | 11        | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                      | Computers | Percent |
|-------------------------------------------|-----------|---------|
| Apple MacBook5,2                          | 306       | 3.67%   |
| Unknown                                   | 134       | 1.61%   |
| ASUS All Series                           | 115       | 1.38%   |
| Lenovo ThinkPad L13 Yoga Gen 2 20VK0019US | 114       | 1.37%   |
| Apple MacBookAir7,1                       | 77        | 0.92%   |
| Apple MacBookAir7,2                       | 76        | 0.91%   |
| Google Enguarde                           | 74        | 0.89%   |
| Apple MacBook2,1                          | 56        | 0.67%   |
| ASUS S20 K29                              | 55        | 0.66%   |
| Aquarius NS585                            | 44        | 0.53%   |
| MSI MS-7996                               | 37        | 0.44%   |
| RPi Raspberry Pi 4 Model B Rev 1.4        | 25        | 0.3%    |
| Lenovo ThinkPad E475 20H40006US           | 24        | 0.29%   |
| Google Terra                              | 23        | 0.28%   |
| Apple MacBook4,1                          | 23        | 0.28%   |
| Supermicro Super Server                   | 22        | 0.26%   |
| MSI MS-7817                               | 22        | 0.26%   |
| HP Notebook                               | 22        | 0.26%   |
| ECS G31T-M9                               | 21        | 0.25%   |
| RPi Raspberry Pi 3 Model B Rev 1.2        | 20        | 0.24%   |
| ASRock H470M-HVS                          | 20        | 0.24%   |
| Dell OptiPlex 7010                        | 19        | 0.23%   |
| ASUS PRIME H510M-A                        | 19        | 0.23%   |
| RPi Raspberry Pi 4 Model B Rev 1.2        | 17        | 0.2%    |
| Gigabyte H81M-S2V                         | 17        | 0.2%    |
| RPi Raspberry Pi 4 Model B Rev 1.1        | 16        | 0.19%   |
| Lenovo ThinkPad 13 2nd Gen 20J10046US     | 16        | 0.19%   |
| HP Pavilion g6                            | 16        | 0.19%   |
| Gigabyte H410M S2H                        | 16        | 0.19%   |
| Gigabyte B450M DS3H                       | 16        | 0.19%   |
| ECS H61H2-M13                             | 16        | 0.19%   |
| Acer Aspire A315-23                       | 16        | 0.19%   |
| ASUS P8H61-M LX3 R2.0                     | 15        | 0.18%   |
| ASUS 1005HA                               | 15        | 0.18%   |
| ASUS TUF Gaming X570-PLUS                 | 13        | 0.16%   |
| ASUS PRIME A320M-K                        | 13        | 0.16%   |
| ASRock B450M Pro4                         | 13        | 0.16%   |
| MSI MS-7C56                               | 12        | 0.14%   |
| Dell Latitude E7440                       | 12        | 0.14%   |
| ASUS PRIME B450M-A                        | 12        | 0.14%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 759       | 9.11%   |
| Apple MacBook5     | 307       | 3.69%   |
| Dell Latitude      | 238       | 2.86%   |
| Dell Inspiron      | 221       | 2.65%   |
| Acer Aspire        | 193       | 2.32%   |
| ASUS PRIME         | 172       | 2.06%   |
| Lenovo IdeaPad     | 170       | 2.04%   |
| Apple MacBookAir7  | 153       | 1.84%   |
| HP EliteBook       | 134       | 1.61%   |
| Unknown            | 134       | 1.61%   |
| Dell OptiPlex      | 116       | 1.39%   |
| RPi Raspberry      | 115       | 1.38%   |
| ASUS All           | 115       | 1.38%   |
| HP Pavilion        | 112       | 1.34%   |
| HP Compaq          | 92        | 1.1%    |
| ASUS ROG           | 86        | 1.03%   |
| HP Laptop          | 85        | 1.02%   |
| HP ProBook         | 81        | 0.97%   |
| Dell Precision     | 81        | 0.97%   |
| Dell XPS           | 78        | 0.94%   |
| Google Enguarde    | 74        | 0.89%   |
| Dell Vostro        | 66        | 0.79%   |
| ASUS TUF           | 63        | 0.76%   |
| Lenovo ThinkCentre | 61        | 0.73%   |
| ASUS VivoBook      | 57        | 0.68%   |
| Apple MacBook2     | 56        | 0.67%   |
| ASUS S20           | 55        | 0.66%   |
| Toshiba Satellite  | 54        | 0.65%   |
| HP ProLiant        | 44        | 0.53%   |
| Dell PowerEdge     | 44        | 0.53%   |
| Aquarius NS585     | 44        | 0.53%   |
| MSI MS-7996        | 37        | 0.44%   |
| Gigabyte B450M     | 34        | 0.41%   |
| ASUS P8H61-M       | 34        | 0.41%   |
| Lenovo Yoga        | 31        | 0.37%   |
| ASUS Zenbook       | 30        | 0.36%   |
| HP 250             | 29        | 0.35%   |
| HP ENVY            | 28        | 0.34%   |
| Lenovo Legion      | 27        | 0.32%   |
| HP ZBook           | 25        | 0.3%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2020    | 904       | 10.85%  |
| 2019    | 742       | 8.91%   |
| 2018    | 677       | 8.13%   |
| 2009    | 616       | 7.39%   |
| 2012    | 603       | 7.24%   |
| 2021    | 597       | 7.17%   |
| 2011    | 517       | 6.21%   |
| 2017    | 500       | 6%      |
| 2013    | 495       | 5.94%   |
| 2015    | 473       | 5.68%   |
| 2016    | 433       | 5.2%    |
| 2014    | 383       | 4.6%    |
| 2010    | 323       | 3.88%   |
| 2008    | 264       | 3.17%   |
| 2022    | 226       | 2.71%   |
| 2007    | 213       | 2.56%   |
| Unknown | 207       | 2.48%   |
| 2006    | 70        | 0.84%   |
| 2005    | 44        | 0.53%   |
| 2004    | 19        | 0.23%   |
| 2003    | 16        | 0.19%   |
| 2002    | 3         | 0.04%   |
| 2001    | 3         | 0.04%   |
| 2000    | 2         | 0.02%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4279      | 51.37%  |
| Desktop        | 3176      | 38.13%  |
| Convertible    | 244       | 2.93%   |
| System on chip | 190       | 2.28%   |
| Mini pc        | 163       | 1.96%   |
| Server         | 157       | 1.88%   |
| All in one     | 67        | 0.8%    |
| Tablet         | 43        | 0.52%   |
| Phone          | 9         | 0.11%   |
| Other          | 2         | 0.02%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 7933      | 94.76%  |
| Enabled  | 439       | 5.24%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 8167      | 98.03%  |
| Yes  | 164       | 1.97%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1788      | 21.25%  |
| 16.01-24.0      | 1552      | 18.45%  |
| 3.01-4.0        | 1473      | 17.51%  |
| 8.01-16.0       | 1263      | 15.01%  |
| 32.01-64.0      | 740       | 8.79%   |
| 1.01-2.0        | 727       | 8.64%   |
| 64.01-256.0     | 340       | 4.04%   |
| 2.01-3.0        | 166       | 1.97%   |
| 0.51-1.0        | 147       | 1.75%   |
| 24.01-32.0      | 133       | 1.58%   |
| 0.01-0.5        | 43        | 0.51%   |
| More than 256.0 | 26        | 0.31%   |
| Unknown         | 15        | 0.18%   |
| 0               | 1         | 0.01%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB         | Computers | Percent |
|-----------------|-----------|---------|
| 1.01-2.0        | 2833      | 31.65%  |
| 2.01-3.0        | 1625      | 18.16%  |
| 0.51-1.0        | 1393      | 15.56%  |
| 4.01-8.0        | 1178      | 13.16%  |
| 3.01-4.0        | 890       | 9.94%   |
| 8.01-16.0       | 415       | 4.64%   |
| 0.01-0.5        | 372       | 4.16%   |
| 16.01-24.0      | 113       | 1.26%   |
| 32.01-64.0      | 52        | 0.58%   |
| 24.01-32.0      | 37        | 0.41%   |
| Unknown         | 23        | 0.26%   |
| 64.01-256.0     | 17        | 0.19%   |
| More than 256.0 | 1         | 0.01%   |
| 0               | 1         | 0.01%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 5415      | 63.67%  |
| 2       | 1737      | 20.42%  |
| 3       | 566       | 6.65%   |
| 4       | 328       | 3.86%   |
| 5       | 159       | 1.87%   |
| 6       | 79        | 0.93%   |
| 0       | 62        | 0.73%   |
| 7       | 54        | 0.63%   |
| 8       | 37        | 0.44%   |
| 9       | 20        | 0.24%   |
| 10      | 13        | 0.15%   |
| 14      | 6         | 0.07%   |
| 11      | 6         | 0.07%   |
| 13      | 5         | 0.06%   |
| 12      | 5         | 0.06%   |
| Unknown | 3         | 0.04%   |
| 28      | 2         | 0.02%   |
| 16      | 2         | 0.02%   |
| 46      | 1         | 0.01%   |
| 27      | 1         | 0.01%   |
| 26      | 1         | 0.01%   |
| 21      | 1         | 0.01%   |
| 18      | 1         | 0.01%   |
| 17      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 5578      | 66.57%  |
| Yes       | 2801      | 33.43%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 7234      | 86.66%  |
| No        | 1114      | 13.34%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5652      | 67.58%  |
| No        | 2712      | 32.42%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4623      | 55.08%  |
| No        | 3771      | 44.92%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 1894      | 22.63%  |
| Russia       | 1187      | 14.18%  |
| Germany      | 782       | 9.34%   |
| France       | 542       | 6.48%   |
| Brazil       | 401       | 4.79%   |
| Spain        | 336       | 4.01%   |
| Italy        | 302       | 3.61%   |
| UK           | 234       | 2.8%    |
| Poland       | 194       | 2.32%   |
| Canada       | 172       | 2.05%   |
| Switzerland  | 139       | 1.66%   |
| Netherlands  | 133       | 1.59%   |
| Australia    | 132       | 1.58%   |
| China        | 102       | 1.22%   |
| Mexico       | 91        | 1.09%   |
| Ukraine      | 89        | 1.06%   |
| India        | 81        | 0.97%   |
| Sweden       | 76        | 0.91%   |
| Hungary      | 74        | 0.88%   |
| Argentina    | 72        | 0.86%   |
| Austria      | 70        | 0.84%   |
| Belgium      | 67        | 0.8%    |
| Portugal     | 65        | 0.78%   |
| Finland      | 56        | 0.67%   |
| Czechia      | 56        | 0.67%   |
| Turkey       | 50        | 0.6%    |
| Norway       | 46        | 0.55%   |
| Japan        | 44        | 0.53%   |
| Chile        | 44        | 0.53%   |
| Romania      | 43        | 0.51%   |
| Venezuela    | 42        | 0.5%    |
| Greece       | 37        | 0.44%   |
| Ireland      | 35        | 0.42%   |
| Bulgaria     | 35        | 0.42%   |
| New Zealand  | 31        | 0.37%   |
| Denmark      | 30        | 0.36%   |
| South Africa | 29        | 0.35%   |
| Colombia     | 29        | 0.35%   |
| Indonesia    | 28        | 0.33%   |
| Belarus      | 25        | 0.3%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Voronezh          | 703       | 7.99%   |
| Bangor            | 701       | 7.97%   |
| Dover-Foxcroft    | 305       | 3.47%   |
| Moscow            | 122       | 1.39%   |
| St Petersburg     | 108       | 1.23%   |
| Paris             | 87        | 0.99%   |
| Berlin            | 72        | 0.82%   |
| Sao Paulo         | 65        | 0.74%   |
| Madrid            | 54        | 0.61%   |
| Seville           | 53        | 0.6%    |
| Vienna            | 51        | 0.58%   |
| Zurich            | 50        | 0.57%   |
| Warsaw            | 46        | 0.52%   |
| Munich            | 43        | 0.49%   |
| Amsterdam         | 43        | 0.49%   |
| Milan             | 42        | 0.48%   |
| Hamburg           | 35        | 0.4%    |
| Sydney            | 34        | 0.39%   |
| Barcelona         | 34        | 0.39%   |
| Budapest          | 32        | 0.36%   |
| Perm              | 31        | 0.35%   |
| Frankfurt am Main | 29        | 0.33%   |
| Toronto           | 28        | 0.32%   |
| London            | 28        | 0.32%   |
| Rio de Janeiro    | 26        | 0.3%    |
| Prague            | 26        | 0.3%    |
| Melbourne         | 26        | 0.3%    |
| Helsinki          | 26        | 0.3%    |
| Falkenstein       | 26        | 0.3%    |
| Brisbane          | 26        | 0.3%    |
| Kyiv              | 23        | 0.26%   |
| San Jose          | 22        | 0.25%   |
| Dublin            | 22        | 0.25%   |
| Cologne           | 22        | 0.25%   |
| Yekaterinburg     | 21        | 0.24%   |
| Rome              | 21        | 0.24%   |
| Athens            | 21        | 0.24%   |
| New York          | 20        | 0.23%   |
| Brasília         | 20        | 0.23%   |
| Lisbon            | 19        | 0.22%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 1791      | 2668   | 15.13%  |
| WDC                 | 1741      | 2843   | 14.71%  |
| Seagate             | 1621      | 2704   | 13.69%  |
| Toshiba             | 818       | 1206   | 6.91%   |
| Kingston            | 707       | 907    | 5.97%   |
| Unknown             | 631       | 838    | 5.33%   |
| Crucial             | 534       | 689    | 4.51%   |
| SanDisk             | 470       | 598    | 3.97%   |
| Hitachi             | 364       | 509    | 3.07%   |
| Intel               | 270       | 363    | 2.28%   |
| Fujitsu             | 261       | 272    | 2.2%    |
| SK hynix            | 243       | 309    | 2.05%   |
| A-DATA Technology   | 216       | 337    | 1.82%   |
| Apple               | 205       | 255    | 1.73%   |
| HGST                | 198       | 316    | 1.67%   |
| Micron Technology   | 141       | 154    | 1.19%   |
| China               | 93        | 109    | 0.79%   |
| SPCC                | 69        | 79     | 0.58%   |
| Transcend           | 68        | 77     | 0.57%   |
| Phison              | 67        | 95     | 0.57%   |
| KIOXIA              | 63        | 76     | 0.53%   |
| Unknown             | 58        | 61     | 0.49%   |
| OCZ                 | 57        | 70     | 0.48%   |
| Intenso             | 50        | 66     | 0.42%   |
| PNY                 | 49        | 66     | 0.41%   |
| Corsair             | 46        | 64     | 0.39%   |
| Patriot             | 45        | 54     | 0.38%   |
| Hewlett-Packard     | 45        | 74     | 0.38%   |
| Maxtor              | 43        | 56     | 0.36%   |
| LITEON              | 42        | 49     | 0.35%   |
| JMicron Technology  | 36        | 37     | 0.3%    |
| Silicon Motion      | 35        | 41     | 0.3%    |
| Netac               | 34        | 97     | 0.29%   |
| SABRENT             | 29        | 31     | 0.24%   |
| GOODRAM             | 29        | 44     | 0.24%   |
| Gigabyte Technology | 29        | 35     | 0.24%   |
| ASMT                | 22        | 32     | 0.19%   |
| XPG                 | 21        | 31     | 0.18%   |
| Team                | 21        | 35     | 0.18%   |
| LITEONIT            | 21        | 26     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Fujitsu MHZ2160BH FFS G1 160GB     | 202       | 1.54%   |
| Kingston SA400S37240G 240GB SSD    | 156       | 1.19%   |
| Samsung MZVLB512HBJQ-000L7 512GB   | 131       | 1%      |
| Seagate ST500DM002-1BD142 500GB    | 102       | 0.78%   |
| Kingston SA400S37120G 120GB SSD    | 100       | 0.76%   |
| Crucial CT480BX500SSD1 480GB       | 82        | 0.63%   |
| Samsung SSD 860 EVO 500GB          | 79        | 0.6%    |
| Seagate ST1000DM010-2EP102 1TB     | 78        | 0.6%    |
| Apple SSD AP0128H 121GB            | 77        | 0.59%   |
| Samsung SSD 860 EVO 1TB            | 75        | 0.57%   |
| Kingston SV300S37A120G 120GB SSD   | 74        | 0.57%   |
| Apple SSD SM0128G 121GB            | 74        | 0.57%   |
| Samsung SSD 850 EVO 250GB          | 73        | 0.56%   |
| Kingston SA400S37480G 480GB SSD    | 72        | 0.55%   |
| Seagate ST1000LM035-1RK172 1TB     | 71        | 0.54%   |
| Samsung SSD 860 EVO 250GB          | 71        | 0.54%   |
| Toshiba DT01ACA050 500GB           | 68        | 0.52%   |
| Crucial CT500MX500SSD1 500GB       | 66        | 0.5%    |
| Unknown MMC Card  32GB             | 62        | 0.47%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 62        | 0.47%   |
| Samsung SSD 970 EVO Plus 1TB       | 61        | 0.47%   |
| Unknown                            | 58        | 0.44%   |
| Crucial CT1000MX500SSD1 1TB        | 55        | 0.42%   |
| Samsung SSD 970 EVO Plus 500GB     | 53        | 0.4%    |
| Crucial CT240BX500SSD1 240GB       | 52        | 0.4%    |
| Samsung SSD 850 EVO 500GB          | 51        | 0.39%   |
| A-DATA SU800 512GB SSD             | 51        | 0.39%   |
| Toshiba DT01ACA100 1TB             | 48        | 0.37%   |
| Toshiba MK1655GSXF 160GB           | 47        | 0.36%   |
| HGST HTS721010A9E630 1TB           | 47        | 0.36%   |
| Toshiba MQ01ABD100 1TB             | 45        | 0.34%   |
| WDC WD10EZEX-08WN4A0 1TB           | 44        | 0.34%   |
| Toshiba HDWD110 1TB                | 44        | 0.34%   |
| Toshiba MK1653GSX 160GB            | 43        | 0.33%   |
| Unknown MMC Card  64GB             | 40        | 0.31%   |
| Unknown AGND3R  16GB               | 40        | 0.31%   |
| Seagate ST2000DM008-2FR102 2TB     | 40        | 0.31%   |
| Seagate ST1000DM003-1CH162 1TB     | 39        | 0.3%    |
| WDC WD5000AAKX-60U6AA0 500GB       | 38        | 0.29%   |
| Seagate ST1000DM003-1ER162 1TB     | 38        | 0.29%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1579      | 2625   | 32.96%  |
| WDC                 | 1341      | 2262   | 28%     |
| Toshiba             | 655       | 998    | 13.67%  |
| Hitachi             | 363       | 507    | 7.58%   |
| Fujitsu             | 261       | 272    | 5.45%   |
| HGST                | 198       | 316    | 4.13%   |
| Samsung Electronics | 170       | 225    | 3.55%   |
| Maxtor              | 42        | 49     | 0.88%   |
| Unknown             | 36        | 50     | 0.75%   |
| SABRENT             | 29        | 31     | 0.61%   |
| Apple               | 19        | 23     | 0.4%    |
| ASMT                | 14        | 23     | 0.29%   |
| Hewlett-Packard     | 9         | 23     | 0.19%   |
| Intenso             | 8         | 10     | 0.17%   |
| IBM/Hitachi         | 6         | 7      | 0.13%   |
| ASMedia             | 6         | 6      | 0.13%   |
| HPE                 | 5         | 10     | 0.1%    |
| USB3.0              | 4         | 4      | 0.08%   |
| JMicron Technology  | 4         | 5      | 0.08%   |
| SILICONMOTION       | 2         | 2      | 0.04%   |
| QNAP                | 2         | 3      | 0.04%   |
| Pear 2TB            | 2         | 2      | 0.04%   |
| NETAPP              | 2         | 6      | 0.04%   |
| IET                 | 2         | 2      | 0.04%   |
| IBM-ESXS            | 2         | 4      | 0.04%   |
| USB 3.0             | 1         | 2      | 0.02%   |
| Unknown (CF)        | 1         | 1      | 0.02%   |
| TrueNAS             | 1         | 1      | 0.02%   |
| Synology            | 1         | 1      | 0.02%   |
| StoreJet            | 1         | 1      | 0.02%   |
| SAGE                | 1         | 1      | 0.02%   |
| RSH-319             | 1         | 1      | 0.02%   |
| Quantum             | 1         | 1      | 0.02%   |
| pqi                 | 1         | 1      | 0.02%   |
| PHD 3.0             | 1         | 1      | 0.02%   |
| NAS                 | 1         | 10     | 0.02%   |
| Maxone              | 1         | 1      | 0.02%   |
| MaxDigital          | 1         | 4      | 0.02%   |
| MARSHAL             | 1         | 1      | 0.02%   |
| Magnetic Data       | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 865       | 1201   | 21.71%  |
| Kingston            | 604       | 778    | 15.16%  |
| Crucial             | 485       | 623    | 12.17%  |
| SanDisk             | 348       | 447    | 8.73%   |
| WDC                 | 187       | 232    | 4.69%   |
| A-DATA Technology   | 164       | 263    | 4.12%   |
| Intel               | 112       | 146    | 2.81%   |
| Apple               | 101       | 109    | 2.53%   |
| China               | 92        | 108    | 2.31%   |
| Micron Technology   | 68        | 75     | 1.71%   |
| Toshiba             | 63        | 81     | 1.58%   |
| Transcend           | 62        | 71     | 1.56%   |
| SPCC                | 57        | 63     | 1.43%   |
| OCZ                 | 57        | 70     | 1.43%   |
| SK hynix            | 55        | 68     | 1.38%   |
| PNY                 | 38        | 50     | 0.95%   |
| Intenso             | 38        | 49     | 0.95%   |
| Patriot             | 37        | 43     | 0.93%   |
| Netac               | 34        | 97     | 0.85%   |
| LITEON              | 33        | 39     | 0.83%   |
| GOODRAM             | 24        | 33     | 0.6%    |
| LITEONIT            | 21        | 26     | 0.53%   |
| Corsair             | 21        | 26     | 0.53%   |
| KingDian            | 19        | 20     | 0.48%   |
| Team                | 18        | 31     | 0.45%   |
| Plextor             | 18        | 24     | 0.45%   |
| Seagate             | 16        | 19     | 0.4%    |
| JMicron Technology  | 16        | 16     | 0.4%    |
| Hewlett-Packard     | 16        | 21     | 0.4%    |
| Gigabyte Technology | 14        | 16     | 0.35%   |
| Unknown             | 13        | 16     | 0.33%   |
| Apacer              | 13        | 13     | 0.33%   |
| Unknown             | 13        | 14     | 0.33%   |
| LDLC                | 12        | 12     | 0.3%    |
| KingSpec            | 10        | 11     | 0.25%   |
| Mushkin             | 9         | 10     | 0.23%   |
| Lexar               | 8         | 11     | 0.2%    |
| Hajaan              | 8         | 11     | 0.2%    |
| Dogfish             | 7         | 10     | 0.18%   |
| ASMT                | 7         | 7      | 0.18%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 4034      | 7520   | 37.9%   |
| SSD     | 3507      | 5212   | 32.95%  |
| NVMe    | 2339      | 3332   | 21.98%  |
| MMC     | 633       | 816    | 5.95%   |
| Unknown | 130       | 196    | 1.22%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 6136      | 12153  | 64.36%  |
| NVMe | 2335      | 3319   | 24.49%  |
| MMC  | 633       | 816    | 6.64%   |
| SAS  | 430       | 788    | 4.51%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB  | Computers | Drives  | Percent |
|-------------|-----------|---------|---------|
| 0.01-0.5    | 4766      | 7050    | 59.78%  |
| 0.51-1.0    | 1970      | 3035    | 24.71%  |
| 1.01-2.0    | 540       | 967     | 6.77%   |
| 3.01-4.0    | 275       | 615     | 3.45%   |
| 4.01-10.0   | 227       | 589     | 2.85%   |
| 2.01-3.0    | 143       | 264     | 1.79%   |
| 10.01-20.0  | 48        | 204     | 0.6%    |
| 20.01-50.0  | 2         | 4       | 0.03%   |
| 50.01-100.0 | 1         | 4       | 0.01%   |
| 0           | 1         | Unknown | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 1931      | 22.4%   |
| 251-500        | 1568      | 18.19%  |
| Unknown        | 1513      | 17.55%  |
| 501-1000       | 1057      | 12.26%  |
| 51-100         | 559       | 6.49%   |
| 1001-2000      | 558       | 6.47%   |
| More than 3000 | 462       | 5.36%   |
| 1-20           | 407       | 4.72%   |
| 21-50          | 341       | 3.96%   |
| 2001-3000      | 223       | 2.59%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 2918      | 32.96%  |
| Unknown        | 1513      | 17.09%  |
| 101-250        | 991       | 11.19%  |
| 21-50          | 941       | 10.63%  |
| 51-100         | 782       | 8.83%   |
| 251-500        | 630       | 7.12%   |
| 501-1000       | 466       | 5.26%   |
| 1001-2000      | 278       | 3.14%   |
| More than 3000 | 199       | 2.25%   |
| 2001-3000      | 112       | 1.27%   |
| 0              | 23        | 0.26%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB     | 25        | 29     | 2.02%   |
| Kingston SV300S37A120G 120GB SSD    | 21        | 21     | 1.7%    |
| WDC WD5000AAKX-60U6AA0 500GB        | 20        | 23     | 1.62%   |
| Fujitsu MHZ2160BH FFS G1 160GB      | 20        | 20     | 1.62%   |
| Seagate ST1000LM024 HN-M101MBB 1TB  | 13        | 16     | 1.05%   |
| Seagate ST9500325AS 500GB           | 12        | 14     | 0.97%   |
| Hitachi HDS721050CLA362 500GB       | 10        | 10     | 0.81%   |
| Toshiba MK1653GSX 160GB             | 9         | 9      | 0.73%   |
| Seagate ST31500341AS 1TB            | 9         | 15     | 0.73%   |
| WDC WD5000AAKX-08U6AA0 500GB        | 8         | 8      | 0.65%   |
| Toshiba MK1655GSXF 160GB            | 8         | 8      | 0.65%   |
| Seagate ST9500420AS 500GB           | 8         | 8      | 0.65%   |
| Seagate ST3500418AS 500GB           | 8         | 12     | 0.65%   |
| Seagate ST1000LM035-1RK172 1TB      | 8         | 8      | 0.65%   |
| Seagate ST1000DM003-9YN162 1TB      | 8         | 9      | 0.65%   |
| Toshiba MQ01ABD100 1TB              | 7         | 7      | 0.57%   |
| Seagate ST500LT012-9WS142 500GB     | 7         | 8      | 0.57%   |
| Seagate ST3250318AS 249GB           | 7         | 8      | 0.57%   |
| Seagate ST31000528AS 1TB            | 7         | 7      | 0.57%   |
| Seagate ST1000DM003-1CH162 1TB      | 7         | 7      | 0.57%   |
| HGST HTS725050A7E630 500GB          | 7         | 8      | 0.57%   |
| WDC WD5000AAKX-001CA0 500GB         | 6         | 8      | 0.49%   |
| Toshiba DT01ACA100 1TB              | 6         | 7      | 0.49%   |
| Seagate ST500LM021-1KJ152 500GB     | 6         | 6      | 0.49%   |
| Seagate ST3160815AS 160GB           | 6         | 8      | 0.49%   |
| Hitachi HTS545050B9A300 500GB       | 6         | 6      | 0.49%   |
| Hitachi HTS543216L9SA02 160GB       | 6         | 6      | 0.49%   |
| Hitachi HDS721050DLE630 500GB       | 6         | 11     | 0.49%   |
| WDC WDS120G2G0A-00JH30 120GB SSD    | 5         | 5      | 0.4%    |
| WDC WD20EFRX-68EUZN0 2TB            | 5         | 16     | 0.4%    |
| WDC WD10EARS-00Y5B1 1TB             | 5         | 5      | 0.4%    |
| WDC WD10EADS-00M2B0 1TB             | 5         | 5      | 0.4%    |
| Toshiba DT01ACA050 500GB            | 5         | 6      | 0.4%    |
| Seagate ST3320613AS 320GB           | 5         | 5      | 0.4%    |
| Seagate ST31000524AS 1TB            | 5         | 5      | 0.4%    |
| Seagate ST250DM000-1BD141 250GB     | 5         | 5      | 0.4%    |
| Samsung Electronics SSD 850 EVO 1TB | 5         | 6      | 0.4%    |
| Samsung Electronics HD103UJ 1TB     | 5         | 6      | 0.4%    |
| Kingston SA400S37240G 240GB SSD     | 5         | 5      | 0.4%    |
| Hitachi HTS547575A9E384 752GB       | 5         | 5      | 0.4%    |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 320       | 419    | 26.78%  |
| WDC                 | 261       | 341    | 21.84%  |
| Hitachi             | 120       | 150    | 10.04%  |
| Samsung Electronics | 88        | 98     | 7.36%   |
| Toshiba             | 79        | 89     | 6.61%   |
| Kingston            | 52        | 58     | 4.35%   |
| Intel               | 35        | 45     | 2.93%   |
| Fujitsu             | 35        | 36     | 2.93%   |
| HGST                | 30        | 32     | 2.51%   |
| Crucial             | 24        | 29     | 2.01%   |
| A-DATA Technology   | 22        | 30     | 1.84%   |
| SK hynix            | 21        | 26     | 1.76%   |
| SanDisk             | 17        | 22     | 1.42%   |
| Micron Technology   | 16        | 16     | 1.34%   |
| Maxtor              | 14        | 15     | 1.17%   |
| OCZ                 | 6         | 7      | 0.5%    |
| LITEONIT            | 5         | 6      | 0.42%   |
| KingDian            | 5         | 5      | 0.42%   |
| China               | 5         | 5      | 0.42%   |
| LITEON              | 4         | 4      | 0.33%   |
| Corsair             | 4         | 4      | 0.33%   |
| Unknown             | 2         | 2      | 0.17%   |
| Plextor             | 2         | 3      | 0.17%   |
| IBM/Hitachi         | 2         | 2      | 0.17%   |
| Hewlett-Packard     | 2         | 3      | 0.17%   |
| Apple               | 2         | 2      | 0.17%   |
| Apacer              | 2         | 2      | 0.17%   |
| Unknown             | 2         | 2      | 0.17%   |
| Zheino              | 1         | 1      | 0.08%   |
| USB3.0              | 1         | 1      | 0.08%   |
| Teclast             | 1         | 1      | 0.08%   |
| Team                | 1         | 1      | 0.08%   |
| SSSTC               | 1         | 1      | 0.08%   |
| ShiJi               | 1         | 1      | 0.08%   |
| PNY                 | 1         | 1      | 0.08%   |
| Netac               | 1         | 1      | 0.08%   |
| Lenovo              | 1         | 1      | 0.08%   |
| KingSpec            | 1         | 1      | 0.08%   |
| JMicron Technology  | 1         | 1      | 0.08%   |
| IBM                 | 1         | 1      | 0.08%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 320       | 419    | 35.16%  |
| WDC                 | 252       | 331    | 27.69%  |
| Hitachi             | 120       | 150    | 13.19%  |
| Toshiba             | 76        | 86     | 8.35%   |
| Samsung Electronics | 52        | 57     | 5.71%   |
| Fujitsu             | 35        | 36     | 3.85%   |
| HGST                | 30        | 32     | 3.3%    |
| Maxtor              | 14        | 15     | 1.54%   |
| IBM/Hitachi         | 2         | 2      | 0.22%   |
| Hewlett-Packard     | 2         | 3      | 0.22%   |
| USB3.0              | 1         | 1      | 0.11%   |
| Unknown             | 1         | 1      | 0.11%   |
| JMicron Technology  | 1         | 1      | 0.11%   |
| IBM                 | 1         | 1      | 0.11%   |
| ASMT                | 1         | 2      | 0.11%   |
| ASMedia             | 1         | 1      | 0.11%   |
| Apple               | 1         | 1      | 0.11%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 855       | 1139   | 75%     |
| SSD  | 250       | 292    | 21.93%  |
| NVMe | 35        | 41     | 3.07%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB                  | 2         | 3      | 8%      |
| Samsung Electronics MZ7LN512HAJQ-00000 512GB SSD | 2         | 5      | 8%      |
| WDC WD5000BEVT-35A0RT0 500GB                     | 1         | 1      | 4%      |
| WDC WD4001FFSX-68JNUN0 4TB                       | 1         | 1      | 4%      |
| WDC WD30EZRS-00J99B0 3TB                         | 1         | 1      | 4%      |
| Toshiba MK6465GSX 640GB                          | 1         | 1      | 4%      |
| Seagate ST500LT012-1DG142 500GB                  | 1         | 1      | 4%      |
| Seagate ST500LM000-1EJ162 500GB                  | 1         | 1      | 4%      |
| Seagate ST500DM005 HD502HJ 500GB                 | 1         | 1      | 4%      |
| Seagate ST3500830AS 500GB                        | 1         | 1      | 4%      |
| Seagate ST3500630A 500GB                         | 1         | 1      | 4%      |
| Samsung Electronics SSD 980 1TB                  | 1         | 1      | 4%      |
| Samsung Electronics MZVLB512HAJQ-000H1 512GB     | 1         | 1      | 4%      |
| Samsung Electronics MZMPC032HBCD-000H1 32GB SSD  | 1         | 1      | 4%      |
| Samsung Electronics HE103SJ 1TB                  | 1         | 2      | 4%      |
| Samsung Electronics HD253GJ 250GB                | 1         | 1      | 4%      |
| Samsung Electronics HD103SJ 1TB                  | 1         | 1      | 4%      |
| KingDian S400 120GB SSD                          | 1         | 1      | 4%      |
| Hitachi HTS545050A7E380 500GB                    | 1         | 2      | 4%      |
| HGST HUH728080ALN600 8TB                         | 1         | 1      | 4%      |
| HGST HDN724040ALE640 4TB                         | 1         | 1      | 4%      |
| Hewlett-Packard SSD S700 500GB                   | 1         | 2      | 4%      |
| Crucial CT1000P1SSD8 1TB                         | 1         | 1      | 4%      |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 8         | 12     | 32%     |
| Seagate             | 7         | 8      | 28%     |
| WDC                 | 3         | 3      | 12%     |
| HGST                | 2         | 2      | 8%      |
| Toshiba             | 1         | 1      | 4%      |
| KingDian            | 1         | 1      | 4%      |
| Hitachi             | 1         | 2      | 4%      |
| Hewlett-Packard     | 1         | 2      | 4%      |
| Crucial             | 1         | 1      | 4%      |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 5685      | 10719  | 61.24%  |
| Detected | 2467      | 4851   | 26.58%  |
| Malfunc  | 1104      | 1472   | 11.89%  |
| Failed   | 25        | 32     | 0.27%   |
| Limited  | 2         | 2      | 0.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5096      | 51.04%  |
| AMD                              | 1394      | 13.96%  |
| Samsung Electronics              | 964       | 9.65%   |
| Nvidia                           | 416       | 4.17%   |
| SanDisk                          | 354       | 3.55%   |
| SK hynix                         | 175       | 1.75%   |
| ASMedia Technology               | 174       | 1.74%   |
| Phison Electronics               | 143       | 1.43%   |
| Marvell Technology Group         | 135       | 1.35%   |
| Kingston Technology Company      | 115       | 1.15%   |
| Toshiba America Info Systems     | 111       | 1.11%   |
| JMicron Technology               | 93        | 0.93%   |
| Apple                            | 86        | 0.86%   |
| LSI Logic / Symbios Logic        | 82        | 0.82%   |
| Silicon Motion                   | 76        | 0.76%   |
| Micron Technology                | 74        | 0.74%   |
| Micron/Crucial Technology        | 73        | 0.73%   |
| ADATA Technology                 | 71        | 0.71%   |
| KIOXIA                           | 68        | 0.68%   |
| Broadcom / LSI                   | 46        | 0.46%   |
| VIA Technologies                 | 39        | 0.39%   |
| Silicon Image                    | 21        | 0.21%   |
| Solid State Storage Technology   | 19        | 0.19%   |
| Hewlett-Packard                  | 19        | 0.19%   |
| Adaptec                          | 18        | 0.18%   |
| Seagate Technology               | 15        | 0.15%   |
| Realtek Semiconductor            | 15        | 0.15%   |
| Silicon Integrated Systems [SiS] | 14        | 0.14%   |
| Lite-On Technology               | 13        | 0.13%   |
| Union Memory (Shenzhen)          | 12        | 0.12%   |
| MAXIO Technology (Hangzhou)      | 7         | 0.07%   |
| Shenzhen Longsys Electronics     | 6         | 0.06%   |
| Lenovo                           | 5         | 0.05%   |
| Integrated Technology Express    | 4         | 0.04%   |
| IBM                              | 4         | 0.04%   |
| 3ware                            | 4         | 0.04%   |
| Unknown                          | 4         | 0.04%   |
| Biwin Storage Technology         | 3         | 0.03%   |
| ULi Electronics                  | 2         | 0.02%   |
| OCZ Technology Group             | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 938       | 8.09%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 548       | 4.73%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 390       | 3.37%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 366       | 3.16%   |
| Nvidia MCP79 AHCI Controller                                                   | 321       | 2.77%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 300       | 2.59%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 211       | 1.82%   |
| AMD 400 Series Chipset SATA Controller                                         | 208       | 1.79%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 204       | 1.76%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 197       | 1.7%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 194       | 1.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 182       | 1.57%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 181       | 1.56%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 178       | 1.54%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 166       | 1.43%   |
| Intel Volume Management Device NVMe RAID Controller                            | 155       | 1.34%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 151       | 1.3%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 150       | 1.29%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 141       | 1.22%   |
| Intel Comet Lake SATA AHCI Controller                                          | 135       | 1.16%   |
| Samsung NVMe SSD Controller 980                                                | 133       | 1.15%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 131       | 1.13%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 122       | 1.05%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 114       | 0.98%   |
| AMD 500 Series Chipset SATA Controller                                         | 104       | 0.9%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 102       | 0.88%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 100       | 0.86%   |
| Intel 82801GBM/GHM (ICH7-M Family) SATA Controller [AHCI mode]                 | 99        | 0.85%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 98        | 0.85%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 94        | 0.81%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 91        | 0.79%   |
| Samsung Electronics SATA controller                                            | 90        | 0.78%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 87        | 0.75%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 85        | 0.73%   |
| Intel SATA Controller [RAID mode]                                              | 84        | 0.72%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 83        | 0.72%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 83        | 0.72%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 80        | 0.69%   |
| Apple S1X NVMe Controller                                                      | 79        | 0.68%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 78        | 0.67%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5878      | 57.74%  |
| NVMe | 2349      | 23.07%  |
| IDE  | 1231      | 12.09%  |
| RAID | 596       | 5.85%   |
| SAS  | 90        | 0.88%   |
| SCSI | 36        | 0.35%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 6416      | 77.01%  |
| AMD                   | 1665      | 19.99%  |
| ARM                   | 214       | 2.57%   |
| CentaurHauls          | 9         | 0.11%   |
| Unknown               | 7         | 0.08%   |
| CHRP IBM,8233-E8B     | 4         | 0.05%   |
| sifive,bullet0        | 3         | 0.04%   |
| Phytium               | 3         | 0.04%   |
| sifive,u74-mc         | 2         | 0.02%   |
| Qualcomm              | 2         | 0.02%   |
| CHRP IBM,9131-52A     | 2         | 0.02%   |
| PowerNV FP5466G2      | 1         | 0.01%   |
| Marvell Semiconductor | 1         | 0.01%   |
| HISILICON             | 1         | 0.01%   |
| AppliedMicro          | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core 2 Duo CPU P7450 @ 2.13GHz          | 308       | 3.69%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 190       | 2.28%   |
| ARM Processor                                 | 156       | 1.87%   |
| Intel Core i5-5250U CPU @ 1.60GHz             | 147       | 1.76%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 92        | 1.1%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 85        | 1.02%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 79        | 0.95%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 76        | 0.91%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 73        | 0.87%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 65        | 0.78%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 65        | 0.78%   |
| Intel Core i5-9400 CPU @ 2.90GHz              | 63        | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 61        | 0.73%   |
| Intel Core 2 CPU T7200 @ 2.00GHz              | 61        | 0.73%   |
| AMD Ryzen 5 3600 6-Core Processor             | 57        | 0.68%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 56        | 0.67%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 55        | 0.66%   |
| Intel Celeron CPU N3060 @ 1.60GHz             | 52        | 0.62%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 49        | 0.59%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 47        | 0.56%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 47        | 0.56%   |
| Intel Core i3-9100 CPU @ 3.60GHz              | 47        | 0.56%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 41        | 0.49%   |
| Intel Pentium CPU G3420 @ 3.20GHz             | 37        | 0.44%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 37        | 0.44%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 37        | 0.44%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 36        | 0.43%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 35        | 0.42%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 32        | 0.38%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 32        | 0.38%   |
| Intel Atom CPU N270 @ 1.60GHz                 | 32        | 0.38%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 31        | 0.37%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 30        | 0.36%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 30        | 0.36%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 30        | 0.36%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 30        | 0.36%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 29        | 0.35%   |
| Intel Core 2 Duo CPU E7500 @ 2.93GHz          | 29        | 0.35%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 29        | 0.35%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 28        | 0.34%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 1673      | 20.07%  |
| Intel Core i7           | 1211      | 14.53%  |
| Other                   | 735       | 8.82%   |
| Intel Core 2 Duo        | 623       | 7.47%   |
| Intel Core i3           | 603       | 7.23%   |
| Intel Celeron           | 528       | 6.33%   |
| AMD Ryzen 5             | 404       | 4.85%   |
| Intel Xeon              | 322       | 3.86%   |
| AMD Ryzen 7             | 281       | 3.37%   |
| Intel Pentium           | 268       | 3.22%   |
| Intel Atom              | 186       | 2.23%   |
| AMD Ryzen 9             | 111       | 1.33%   |
| AMD FX                  | 109       | 1.31%   |
| Intel Core 2            | 98        | 1.18%   |
| Intel Pentium Dual-Core | 88        | 1.06%   |
| AMD Ryzen 3             | 75        | 0.9%    |
| Intel Core 2 Quad       | 59        | 0.71%   |
| AMD Ryzen 7 PRO         | 48        | 0.58%   |
| AMD A8                  | 42        | 0.5%    |
| AMD A6                  | 39        | 0.47%   |
| Intel Core i9           | 37        | 0.44%   |
| AMD A10                 | 37        | 0.44%   |
| Intel Pentium Dual      | 34        | 0.41%   |
| Intel Pentium 4         | 33        | 0.4%    |
| AMD Ryzen Threadripper  | 32        | 0.38%   |
| AMD Athlon              | 32        | 0.38%   |
| AMD A4                  | 32        | 0.38%   |
| Intel Pentium M         | 31        | 0.37%   |
| AMD Athlon II X2        | 31        | 0.37%   |
| AMD Athlon 64 X2        | 31        | 0.37%   |
| AMD Ryzen 5 PRO         | 29        | 0.35%   |
| AMD Phenom II X4        | 29        | 0.35%   |
| Intel Pentium Gold      | 27        | 0.32%   |
| Intel Genuine           | 27        | 0.32%   |
| AMD E1                  | 21        | 0.25%   |
| AMD E                   | 21        | 0.25%   |
| Intel Pentium Silver    | 19        | 0.23%   |
| ARM Allwinner           | 19        | 0.23%   |
| AMD Phenom II X6        | 16        | 0.19%   |
| AMD GX                  | 15        | 0.18%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3547      | 42.51%  |
| 4       | 2852      | 34.18%  |
| 6       | 720       | 8.63%   |
| 8       | 534       | 6.4%    |
| 1       | 306       | 3.67%   |
| 12      | 119       | 1.43%   |
| 16      | 93        | 1.11%   |
| 10      | 39        | 0.47%   |
| 3       | 39        | 0.47%   |
| 14      | 19        | 0.23%   |
| Unknown | 18        | 0.22%   |
| 32      | 17        | 0.2%    |
| 24      | 14        | 0.17%   |
| 20      | 11        | 0.13%   |
| 44      | 3         | 0.04%   |
| 28      | 3         | 0.04%   |
| 18      | 3         | 0.04%   |
| 64      | 2         | 0.02%   |
| 48      | 2         | 0.02%   |
| 80      | 1         | 0.01%   |
| 56      | 1         | 0.01%   |
| 22      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 8166      | 97.96%  |
| 2       | 146       | 1.75%   |
| Unknown | 18        | 0.22%   |
| 4       | 4         | 0.05%   |
| 3       | 2         | 0.02%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 5000      | 59.95%  |
| 1       | 3316      | 39.76%  |
| Unknown | 18        | 0.22%   |
| 4       | 6         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7951      | 95.31%  |
| Unknown        | 224       | 2.69%   |
| 32-bit         | 148       | 1.77%   |
| 64-bit         | 19        | 0.23%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1976      | 23.15%  |
| 0x1067a    | 565       | 6.62%   |
| 0x206a7    | 369       | 4.32%   |
| 0x306a9    | 366       | 4.29%   |
| 0x306c3    | 353       | 4.13%   |
| 0x806c1    | 295       | 3.46%   |
| 0x306d4    | 253       | 2.96%   |
| 0x906ea    | 200       | 2.34%   |
| 0x806ec    | 195       | 2.28%   |
| 0x506e3    | 164       | 1.92%   |
| 0x806e9    | 155       | 1.82%   |
| 0x806ea    | 141       | 1.65%   |
| 0x30678    | 137       | 1.6%    |
| 0x40651    | 120       | 1.41%   |
| 0x406e3    | 111       | 1.3%    |
| 0x08701021 | 110       | 1.29%   |
| 0x906e9    | 109       | 1.28%   |
| 0x08108109 | 102       | 1.19%   |
| 0x406c4    | 86        | 1.01%   |
| 0xa0653    | 81        | 0.95%   |
| 0x6f6      | 78        | 0.91%   |
| 0x20655    | 75        | 0.88%   |
| 0x08600106 | 71        | 0.83%   |
| 0x0a50000c | 69        | 0.81%   |
| 0x906eb    | 67        | 0.78%   |
| 0x10676    | 65        | 0.76%   |
| 0x6fd      | 63        | 0.74%   |
| 0xa0652    | 62        | 0.73%   |
| 0x706a8    | 59        | 0.69%   |
| 0x0800820d | 55        | 0.64%   |
| 0xa0655    | 53        | 0.62%   |
| 0x506c9    | 52        | 0.61%   |
| 0x08108102 | 51        | 0.6%    |
| 0x706e5    | 48        | 0.56%   |
| 0x0a201016 | 46        | 0.54%   |
| 0x206d7    | 44        | 0.52%   |
| 0x106c2    | 43        | 0.5%    |
| 0x08608103 | 43        | 0.5%    |
| 0x906ed    | 42        | 0.49%   |
| 0x010000c8 | 40        | 0.47%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1226      | 14.7%   |
| Penryn           | 711       | 8.52%   |
| Haswell          | 659       | 7.9%    |
| SandyBridge      | 537       | 6.44%   |
| IvyBridge        | 518       | 6.21%   |
| Skylake          | 400       | 4.8%    |
| Unknown          | 392       | 4.7%    |
| TigerLake        | 339       | 4.06%   |
| Zen 2            | 326       | 3.91%   |
| Silvermont       | 319       | 3.82%   |
| Broadwell        | 312       | 3.74%   |
| Zen+             | 279       | 3.34%   |
| Core             | 253       | 3.03%   |
| CometLake        | 238       | 2.85%   |
| Zen 3            | 197       | 2.36%   |
| Westmere         | 191       | 2.29%   |
| Zen              | 152       | 1.82%   |
| K10              | 136       | 1.63%   |
| Piledriver       | 115       | 1.38%   |
| Goldmont plus    | 107       | 1.28%   |
| Bonnell          | 107       | 1.28%   |
| Excavator        | 104       | 1.25%   |
| IceLake          | 84        | 1.01%   |
| Goldmont         | 76        | 0.91%   |
| Nehalem          | 72        | 0.86%   |
| K8 Hammer        | 69        | 0.83%   |
| P6               | 66        | 0.79%   |
| NetBurst         | 56        | 0.67%   |
| Bobcat           | 50        | 0.6%    |
| Alderlake Hybrid | 50        | 0.6%    |
| Steamroller      | 38        | 0.46%   |
| Jaguar           | 35        | 0.42%   |
| Puma             | 32        | 0.38%   |
| Bulldozer        | 31        | 0.37%   |
| Tremont          | 30        | 0.36%   |
| K10 Llano        | 21        | 0.25%   |
| K8 & K10 hybrid  | 7         | 0.08%   |
| K6               | 6         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4828      | 52.45%  |
| Nvidia                           | 2366      | 25.7%   |
| AMD                              | 1767      | 19.2%   |
| Matrox Electronics Systems       | 122       | 1.33%   |
| ASPEED Technology                | 93        | 1.01%   |
| VIA Technologies                 | 11        | 0.12%   |
| Silicon Integrated Systems [SiS] | 8         | 0.09%   |
| Zhaoxin                          | 2         | 0.02%   |
| S3 Graphics                      | 2         | 0.02%   |
| Silicon Motion                   | 1         | 0.01%   |
| Neomagic                         | 1         | 0.01%   |
| Loongson Technology              | 1         | 0.01%   |
| Huawei Technologies              | 1         | 0.01%   |
| Cirrus Logic                     | 1         | 0.01%   |
| ATI Technologies                 | 1         | 0.01%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 355       | 3.72%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 318       | 3.34%   |
| Nvidia C79 [GeForce 9400M G]                                                             | 306       | 3.21%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 270       | 2.83%   |
| Intel UHD Graphics 620                                                                   | 196       | 2.06%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 189       | 1.98%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 183       | 1.92%   |
| Intel HD Graphics 620                                                                    | 176       | 1.85%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 172       | 1.8%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 172       | 1.8%    |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 157       | 1.65%   |
| Intel HD Graphics 6000                                                                   | 155       | 1.63%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 151       | 1.58%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 145       | 1.52%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 142       | 1.49%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 136       | 1.43%   |
| AMD Renoir                                                                               | 133       | 1.4%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 128       | 1.34%   |
| Intel HD Graphics 5500                                                                   | 118       | 1.24%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 115       | 1.21%   |
| Intel HD Graphics 530                                                                    | 105       | 1.1%    |
| Intel Core Processor Integrated Graphics Controller                                      | 101       | 1.06%   |
| Intel HD Graphics 630                                                                    | 96        | 1.01%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 96        | 1.01%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 94        | 0.99%   |
| ASPEED Technology ASPEED Graphics Family                                                 | 93        | 0.98%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 92        | 0.97%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 88        | 0.92%   |
| Intel CometLake-S GT2 [UHD Graphics 630]                                                 | 86        | 0.9%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 84        | 0.88%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 82        | 0.86%   |
| Intel Mobile 945GM/GMS, 943/940GML Express Integrated Graphics Controller                | 79        | 0.83%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 79        | 0.83%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 73        | 0.77%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 72        | 0.76%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 72        | 0.76%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 68        | 0.71%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 68        | 0.71%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 67        | 0.7%    |
| Intel 82G33/G31 Express Integrated Graphics Controller                                   | 64        | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name                              | Computers | Percent |
|-----------------------------------|-----------|---------|
| 1 x Intel                         | 3847      | 45.93%  |
| 1 x Nvidia                        | 1520      | 18.15%  |
| 1 x AMD                           | 1429      | 17.06%  |
| Intel + Nvidia                    | 735       | 8.78%   |
| Other                             | 252       | 3.01%   |
| Intel + AMD                       | 161       | 1.92%   |
| 1 x Matrox                        | 115       | 1.37%   |
| 2 x AMD                           | 89        | 1.06%   |
| AMD + Nvidia                      | 77        | 0.92%   |
| 1 x ASPEED                        | 75        | 0.9%    |
| 2 x Nvidia                        | 14        | 0.17%   |
| 1 x VIA                           | 11        | 0.13%   |
| Nvidia + ASPEED                   | 10        | 0.12%   |
| 1 x SiS                           | 8         | 0.1%    |
| AMD + ASPEED                      | 6         | 0.07%   |
| Nvidia + Matrox                   | 5         | 0.06%   |
| Intel + 2 x Nvidia                | 5         | 0.06%   |
| 2 x Intel                         | 3         | 0.04%   |
| 1 x Zhaoxin                       | 2         | 0.02%   |
| 1 x S3 Graphics                   | 2         | 0.02%   |
| AMD + Matrox                      | 2         | 0.02%   |
| 3 x AMD                           | 1         | 0.01%   |
| 2 x Nvidia + 1 x ASPEED           | 1         | 0.01%   |
| 2 x Loongson Technology           | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia + 1 x ASPEED | 1         | 0.01%   |
| 1 x Silicon Motion                | 1         | 0.01%   |
| Nvidia + Huawei Technologies      | 1         | 0.01%   |
| 1 x Neomagic                      | 1         | 0.01%   |
| 1 x Cirrus Logic                  | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6131      | 72.99%  |
| Unknown     | 1373      | 16.35%  |
| Proprietary | 896       | 10.67%  |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| Unknown        | 5867      | 69.34%  |
| 0.01-0.5       | 900       | 10.64%  |
| 1.01-2.0       | 562       | 6.64%   |
| 0.51-1.0       | 382       | 4.51%   |
| 3.01-4.0       | 327       | 3.86%   |
| 7.01-8.0       | 206       | 2.43%   |
| 5.01-6.0       | 116       | 1.37%   |
| 2.01-3.0       | 43        | 0.51%   |
| 8.01-16.0      | 43        | 0.51%   |
| 16.01-24.0     | 11        | 0.13%   |
| 4.01-5.0       | 2         | 0.02%   |
| More than 64.0 | 1         | 0.01%   |
| 24.01-32.0     | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 975       | 12.4%   |
| Samsung Electronics     | 844       | 10.73%  |
| BOE                     | 644       | 8.19%   |
| Apple                   | 625       | 7.95%   |
| LG Display              | 589       | 7.49%   |
| Chimei Innolux          | 541       | 6.88%   |
| Dell                    | 476       | 6.05%   |
| Goldstar                | 377       | 4.79%   |
| Hewlett-Packard         | 240       | 3.05%   |
| BenQ                    | 215       | 2.73%   |
| Acer                    | 211       | 2.68%   |
| Philips                 | 185       | 2.35%   |
| AOC                     | 178       | 2.26%   |
| Lenovo                  | 161       | 2.05%   |
| Ancor Communications    | 152       | 1.93%   |
| Iiyama                  | 107       | 1.36%   |
| Sharp                   | 101       | 1.28%   |
| ViewSonic               | 89        | 1.13%   |
| Chi Mei Optoelectronics | 82        | 1.04%   |
| Unknown                 | 77        | 0.98%   |
| InfoVision              | 76        | 0.97%   |
| Eizo                    | 53        | 0.67%   |
| PANDA                   | 52        | 0.66%   |
| ASUSTek Computer        | 48        | 0.61%   |
| Sony                    | 42        | 0.53%   |
| HannStar                | 40        | 0.51%   |
| NEC Computers           | 37        | 0.47%   |
| LG Electronics          | 36        | 0.46%   |
| LG Philips              | 29        | 0.37%   |
| CSO                     | 26        | 0.33%   |
| Fujitsu Siemens         | 18        | 0.23%   |
| Panasonic               | 17        | 0.22%   |
| MSI                     | 17        | 0.22%   |
| Medion                  | 16        | 0.2%    |
| Vizio                   | 15        | 0.19%   |
| Vestel Elektronik       | 15        | 0.19%   |
| CPT                     | 15        | 0.19%   |
| Toshiba                 | 13        | 0.17%   |
| RTK                     | 11        | 0.14%   |
| Hitachi                 | 11        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Apple Color LCD APP9C5B 1280x800 286x179mm 13.3-inch                  | 200       | 2.46%   |
| Apple LCD Monitor APP9C5F 1280x800 286x179mm 13.3-inch                | 152       | 1.87%   |
| AU Optronics LCD Monitor AUO592D 1920x1080 293x165mm 13.2-inch        | 112       | 1.38%   |
| BOE LCD Monitor BOE0609 1366x768 256x144mm 11.6-inch                  | 52        | 0.64%   |
| AU Optronics LCD Monitor AUO235C 1366x768 256x144mm 11.6-inch         | 43        | 0.53%   |
| Apple Color LCD APP9CDF 1440x900 286x179mm 13.3-inch                  | 43        | 0.53%   |
| Unknown LCD Monitor FFFF 2288x1287 2550x2550mm 142.0-inch             | 41        | 0.51%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 41        | 0.51%   |
| Apple Color LCD APP9CF3 1366x768 260x140mm 11.6-inch                  | 41        | 0.51%   |
| Goldstar LG ULTRAWIDE GSM59F1 2560x1080 670x280mm 28.6-inch           | 37        | 0.46%   |
| Apple Color LCD APP9CF2 1366x768 256x144mm 11.6-inch                  | 37        | 0.46%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch      | 36        | 0.44%   |
| BOE LCD Monitor BOE06B3 1366x768 309x173mm 13.9-inch                  | 29        | 0.36%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 27        | 0.33%   |
| Apple Color LCD APP9CF0 1440x900 290x180mm 13.4-inch                  | 27        | 0.33%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch         | 26        | 0.32%   |
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch       | 24        | 0.3%    |
| Chimei Innolux LCD Monitor CMN1132 1366x768 256x144mm 11.6-inch       | 24        | 0.3%    |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 22        | 0.27%   |
| HannStar HSD100IFW1 HSD03E9 1024x600 220x129mm 10.0-inch              | 22        | 0.27%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 21        | 0.26%   |
| Apple Color LCD APP9C5C 1280x800 286x179mm 13.3-inch                  | 21        | 0.26%   |
| ViewSonic VG730m VSC951E 1280x1024 338x270mm 17.0-inch                | 18        | 0.22%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch         | 18        | 0.22%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 17        | 0.21%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch        | 17        | 0.21%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 16        | 0.2%    |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 16        | 0.2%    |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch        | 16        | 0.2%    |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch     | 15        | 0.18%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch           | 15        | 0.18%   |
| Chimei Innolux LCD Monitor CMN14C9 1920x1080 309x173mm 13.9-inch      | 15        | 0.18%   |
| BOE LCD Monitor BOE0687 1920x1080 344x193mm 15.5-inch                 | 15        | 0.18%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch         | 15        | 0.18%   |
| AU Optronics LCD Monitor AUO2E3C 1366x768 309x173mm 13.9-inch         | 15        | 0.18%   |
| Vestel Elektronik 50FHD_LCD_TV VES3700 1920x1080 1280x720mm 57.8-inch | 14        | 0.17%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch     | 14        | 0.17%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 14        | 0.17%   |
| Apple Color LCD APP9C5E 1280x800 286x178mm 13.3-inch                  | 14        | 0.17%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 13        | 0.16%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3054      | 40.4%   |
| 1366x768 (WXGA)    | 1344      | 17.78%  |
| 1280x800 (WXGA)    | 518       | 6.85%   |
| 3840x2160 (4K)     | 408       | 5.4%    |
| 2560x1440 (QHD)    | 309       | 4.09%   |
| 1280x1024 (SXGA)   | 303       | 4.01%   |
| 1600x900 (HD+)     | 261       | 3.45%   |
| 1920x1200 (WUXGA)  | 216       | 2.86%   |
| 1440x900 (WXGA+)   | 208       | 2.75%   |
| 1680x1050 (WSXGA+) | 184       | 2.43%   |
| Unknown            | 91        | 1.2%    |
| 2560x1080          | 73        | 0.97%   |
| 1024x600           | 66        | 0.87%   |
| 3440x1440          | 55        | 0.73%   |
| 1024x768 (XGA)     | 53        | 0.7%    |
| 1360x768           | 51        | 0.67%   |
| 2288x1287          | 43        | 0.57%   |
| 2560x1600          | 42        | 0.56%   |
| 3840x1080          | 37        | 0.49%   |
| 1600x1200          | 35        | 0.46%   |
| 1920x540           | 19        | 0.25%   |
| 3840x2400          | 17        | 0.22%   |
| 2880x1800          | 17        | 0.22%   |
| 2160x1440          | 11        | 0.15%   |
| 3200x1800 (QHD+)   | 9         | 0.12%   |
| 1280x720 (HD)      | 9         | 0.12%   |
| 1400x1050          | 8         | 0.11%   |
| 4480x1440          | 7         | 0.09%   |
| 2736x1824          | 7         | 0.09%   |
| 3840x1600          | 6         | 0.08%   |
| 3200x1080          | 6         | 0.08%   |
| 1920x1280          | 6         | 0.08%   |
| 5760x1080          | 5         | 0.07%   |
| 2048x1152          | 5         | 0.07%   |
| 7680x2160          | 4         | 0.05%   |
| 5760x2160          | 4         | 0.05%   |
| 3840x1100          | 3         | 0.04%   |
| 3360x1050          | 3         | 0.04%   |
| 2256x1504          | 3         | 0.04%   |
| 2240x1400          | 3         | 0.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 1515      | 19.34%  |
| 13      | 1236      | 15.78%  |
| 14      | 629       | 8.03%   |
| 24      | 583       | 7.44%   |
| 27      | 497       | 6.35%   |
| 23      | 465       | 5.94%   |
| 17      | 389       | 4.97%   |
| 21      | 385       | 4.92%   |
| Unknown | 300       | 3.83%   |
| 11      | 278       | 3.55%   |
| 19      | 227       | 2.9%    |
| 12      | 193       | 2.46%   |
| 18      | 147       | 1.88%   |
| 22      | 122       | 1.56%   |
| 31      | 117       | 1.49%   |
| 20      | 103       | 1.32%   |
| 34      | 102       | 1.3%    |
| 10      | 70        | 0.89%   |
| 84      | 48        | 0.61%   |
| 25      | 48        | 0.61%   |
| 142     | 41        | 0.52%   |
| 72      | 38        | 0.49%   |
| 16      | 32        | 0.41%   |
| 54      | 29        | 0.37%   |
| 32      | 29        | 0.37%   |
| 40      | 28        | 0.36%   |
| 26      | 21        | 0.27%   |
| 29      | 19        | 0.24%   |
| 52      | 14        | 0.18%   |
| 28      | 14        | 0.18%   |
| 48      | 11        | 0.14%   |
| 46      | 9         | 0.11%   |
| 43      | 8         | 0.1%    |
| 8       | 8         | 0.1%    |
| 65      | 7         | 0.09%   |
| 49      | 7         | 0.09%   |
| 39      | 7         | 0.09%   |
| 33      | 7         | 0.09%   |
| 37      | 6         | 0.08%   |
| 55      | 5         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 2616      | 33.97%  |
| 501-600        | 1443      | 18.74%  |
| 201-300        | 1412      | 18.34%  |
| 401-500        | 831       | 10.79%  |
| 351-400        | 444       | 5.77%   |
| Unknown        | 300       | 3.9%    |
| 601-700        | 218       | 2.83%   |
| 701-800        | 138       | 1.79%   |
| 1001-1500      | 97        | 1.26%   |
| 1501-2000      | 88        | 1.14%   |
| 801-900        | 49        | 0.64%   |
| More than 2000 | 41        | 0.53%   |
| 901-1000       | 13        | 0.17%   |
| 101-200        | 11        | 0.14%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5009      | 70.25%  |
| 16/10   | 1207      | 16.93%  |
| 5/4     | 281       | 3.94%   |
| Unknown | 243       | 3.41%   |
| 21/9    | 121       | 1.7%    |
| 4/3     | 120       | 1.68%   |
| 3/2     | 63        | 0.88%   |
| 1.00    | 43        | 0.6%    |
| 6/5     | 13        | 0.18%   |
| 32/9    | 13        | 0.18%   |
| 2.65    | 5         | 0.07%   |
| 3.40    | 3         | 0.04%   |
| 3.20    | 2         | 0.03%   |
| 2.00    | 2         | 0.03%   |
| 1.96    | 2         | 0.03%   |
| 3.73    | 1         | 0.01%   |
| 0.62    | 1         | 0.01%   |
| 0.56    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 1502      | 19.35%  |
| 81-90          | 1428      | 18.4%   |
| 201-250        | 1215      | 15.66%  |
| 301-350        | 511       | 6.58%   |
| 151-200        | 443       | 5.71%   |
| 71-80          | 439       | 5.66%   |
| Unknown        | 300       | 3.87%   |
| 351-500        | 282       | 3.63%   |
| 51-60          | 281       | 3.62%   |
| 251-300        | 260       | 3.35%   |
| 141-150        | 254       | 3.27%   |
| 121-130        | 212       | 2.73%   |
| More than 1000 | 200       | 2.58%   |
| 61-70          | 179       | 2.31%   |
| 501-1000       | 83        | 1.07%   |
| 41-50          | 70        | 0.9%    |
| 131-140        | 42        | 0.54%   |
| 111-120        | 27        | 0.35%   |
| 91-100         | 22        | 0.28%   |
| 1-40           | 11        | 0.14%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2319      | 30.74%  |
| 121-160       | 2100      | 27.84%  |
| 101-120       | 2022      | 26.81%  |
| 161-240       | 512       | 6.79%   |
| Unknown       | 301       | 3.99%   |
| 1-50          | 179       | 2.37%   |
| More than 240 | 110       | 1.46%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 5766      | 67.85%  |
| 0     | 1495      | 17.59%  |
| 2     | 1105      | 13%     |
| 3     | 126       | 1.48%   |
| 4     | 5         | 0.06%   |
| 5     | 1         | 0.01%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3984      | 33.06%  |
| Intel                             | 3807      | 31.59%  |
| Qualcomm Atheros                  | 1223      | 10.15%  |
| Broadcom                          | 868       | 7.2%    |
| Nvidia                            | 398       | 3.3%    |
| Broadcom Limited                  | 297       | 2.46%   |
| Marvell Technology Group          | 188       | 1.56%   |
| Ralink Technology                 | 104       | 0.86%   |
| Ralink                            | 95        | 0.79%   |
| TP-Link                           | 89        | 0.74%   |
| MediaTek                          | 85        | 0.71%   |
| ASIX Electronics                  | 70        | 0.58%   |
| Samsung Electronics               | 50        | 0.41%   |
| Dell                              | 37        | 0.31%   |
| Lenovo                            | 35        | 0.29%   |
| Microchip Technology              | 32        | 0.27%   |
| Huawei Technologies               | 31        | 0.26%   |
| Sierra Wireless                   | 30        | 0.25%   |
| Qualcomm Atheros Communications   | 27        | 0.22%   |
| JMicron Technology                | 27        | 0.22%   |
| D-Link System                     | 26        | 0.22%   |
| Aquantia                          | 25        | 0.21%   |
| Qualcomm                          | 23        | 0.19%   |
| Ericsson Business Mobile Networks | 23        | 0.19%   |
| Mellanox Technologies             | 22        | 0.18%   |
| DisplayLink                       | 22        | 0.18%   |
| Xiaomi                            | 21        | 0.17%   |
| Microsoft                         | 21        | 0.17%   |
| ASUSTek Computer                  | 19        | 0.16%   |
| NetGear                           | 17        | 0.14%   |
| Hewlett-Packard                   | 17        | 0.14%   |
| VIA Technologies                  | 16        | 0.13%   |
| D-Link                            | 16        | 0.13%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.12%   |
| IBM                               | 13        | 0.11%   |
| Fibocom                           | 13        | 0.11%   |
| Edimax Technology                 | 12        | 0.1%    |
| Dresden Elektronik                | 12        | 0.1%    |
| American Megatrends               | 10        | 0.08%   |
| 3Com                              | 10        | 0.08%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2831      | 20.07%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 430       | 3.05%   |
| Nvidia MCP79 Ethernet                                             | 322       | 2.28%   |
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller            | 317       | 2.25%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 275       | 1.95%   |
| Intel Wi-Fi 6 AX201                                               | 274       | 1.94%   |
| Intel Wi-Fi 6 AX200                                               | 270       | 1.91%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 219       | 1.55%   |
| Intel Wireless 8265 / 8275                                        | 211       | 1.5%    |
| Intel Wireless 7260                                               | 208       | 1.47%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 207       | 1.47%   |
| Intel Wireless 7265                                               | 185       | 1.31%   |
| Intel I211 Gigabit Network Connection                             | 182       | 1.29%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter        | 163       | 1.16%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 151       | 1.07%   |
| Intel Ethernet Connection (13) I219-V                             | 141       | 1%      |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 131       | 0.93%   |
| Realtek RTL8125 2.5GbE Controller                                 | 130       | 0.92%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 127       | 0.9%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 125       | 0.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 123       | 0.87%   |
| Intel Wireless 8260                                               | 117       | 0.83%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 115       | 0.82%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 113       | 0.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 113       | 0.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 102       | 0.72%   |
| Intel Wireless 3165                                               | 102       | 0.72%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 99        | 0.7%    |
| Intel I210 Gigabit Network Connection                             | 99        | 0.7%    |
| Intel Ethernet Connection (2) I219-V                              | 93        | 0.66%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 85        | 0.6%    |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 81        | 0.57%   |
| Intel 82579V Gigabit Network Connection                           | 81        | 0.57%   |
| Intel Wireless-AC 9260                                            | 80        | 0.57%   |
| Intel Ethernet Connection I217-LM                                 | 80        | 0.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 73        | 0.52%   |
| Intel 82574L Gigabit Network Connection                           | 72        | 0.51%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 64        | 0.45%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 63        | 0.45%   |
| Intel Ethernet Connection (4) I219-V                              | 63        | 0.45%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2689      | 45.78%  |
| Qualcomm Atheros                      | 991       | 16.87%  |
| Realtek Semiconductor                 | 766       | 13.04%  |
| Broadcom                              | 611       | 10.4%   |
| Broadcom Limited                      | 228       | 3.88%   |
| Ralink Technology                     | 104       | 1.77%   |
| Ralink                                | 95        | 1.62%   |
| MediaTek                              | 78        | 1.33%   |
| TP-Link                               | 65        | 1.11%   |
| Sierra Wireless                       | 30        | 0.51%   |
| Qualcomm Atheros Communications       | 27        | 0.46%   |
| Dell                                  | 19        | 0.32%   |
| ASUSTek Computer                      | 19        | 0.32%   |
| NetGear                               | 17        | 0.29%   |
| D-Link System                         | 15        | 0.26%   |
| D-Link                                | 14        | 0.24%   |
| Microsoft                             | 13        | 0.22%   |
| Marvell Technology Group              | 12        | 0.2%    |
| Fibocom                               | 12        | 0.2%    |
| Edimax Technology                     | 12        | 0.2%    |
| Belkin Components                     | 9         | 0.15%   |
| Qualcomm                              | 8         | 0.14%   |
| IMC Networks                          | 5         | 0.09%   |
| Gemtek                                | 5         | 0.09%   |
| Wilocity                              | 4         | 0.07%   |
| Linksys                               | 3         | 0.05%   |
| Hewlett-Packard                       | 3         | 0.05%   |
| Ericsson Business Mobile Networks     | 3         | 0.05%   |
| Micro Star International              | 2         | 0.03%   |
| AVM                                   | 2         | 0.03%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 2         | 0.03%   |
| 3Com                                  | 2         | 0.03%   |
| ZyXEL Communications                  | 1         | 0.02%   |
| Z-Com                                 | 1         | 0.02%   |
| TRENDnet                              | 1         | 0.02%   |
| Sitecom Europe                        | 1         | 0.02%   |
| Quectel Wireless Solutions            | 1         | 0.02%   |
| PLANEX                                | 1         | 0.02%   |
| Fiberline                             | 1         | 0.02%   |
| Cinterion                             | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM4322 802.11a/b/g/n Wireless LAN Controller                                | 317       | 5.37%   |
| Intel Wi-Fi 6 AX201                                                                   | 274       | 4.64%   |
| Intel Wi-Fi 6 AX200                                                                   | 270       | 4.57%   |
| Intel Wireless 8265 / 8275                                                            | 211       | 3.57%   |
| Intel Wireless 7260                                                                   | 208       | 3.52%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter                            | 207       | 3.51%   |
| Intel Wireless 7265                                                                   | 185       | 3.13%   |
| Broadcom Limited BCM4360 802.11ac Wireless Network Adapter                            | 163       | 2.76%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)                        | 151       | 2.56%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                                      | 131       | 2.22%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter                            | 127       | 2.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                                     | 125       | 2.12%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                              | 123       | 2.08%   |
| Intel Wireless 8260                                                                   | 117       | 1.98%   |
| Intel Cannon Lake PCH CNVi WiFi                                                       | 115       | 1.95%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                                          | 113       | 1.91%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                              | 113       | 1.91%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                              | 102       | 1.73%   |
| Intel Wireless 3165                                                                   | 102       | 1.73%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter                            | 99        | 1.68%   |
| Intel Comet Lake PCH CNVi WiFi                                                        | 85        | 1.44%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                                      | 81        | 1.37%   |
| Intel Wireless-AC 9260                                                                | 80        | 1.36%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                                       | 73        | 1.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                                   | 60        | 1.02%   |
| Qualcomm Atheros AR5418 Wireless Network Adapter [AR5008E 802.11(a)bgn] (PCI-Express) | 59        | 1%      |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                                | 55        | 0.93%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                                      | 54        | 0.91%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter                         | 48        | 0.81%   |
| Intel Alder Lake-P PCH CNVi WiFi                                                      | 48        | 0.81%   |
| Broadcom BCM43142 802.11b/g/n                                                         | 45        | 0.76%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                                       | 44        | 0.75%   |
| Intel Wireless 3160                                                                   | 44        | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                                 | 43        | 0.73%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express)               | 42        | 0.71%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)                        | 40        | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                                       | 40        | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                                            | 39        | 0.66%   |
| Intel Centrino Ultimate-N 6300                                                        | 39        | 0.66%   |
| Ralink MT7601U Wireless Adapter                                                       | 38        | 0.64%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 3682      | 47.42%  |
| Intel                             | 2216      | 28.54%  |
| Nvidia                            | 398       | 5.13%   |
| Qualcomm Atheros                  | 346       | 4.46%   |
| Broadcom                          | 310       | 3.99%   |
| Marvell Technology Group          | 177       | 2.28%   |
| Broadcom Limited                  | 72        | 0.93%   |
| ASIX Electronics                  | 70        | 0.9%    |
| Samsung Electronics               | 50        | 0.64%   |
| Lenovo                            | 35        | 0.45%   |
| Microchip Technology              | 31        | 0.4%    |
| JMicron Technology                | 27        | 0.35%   |
| Aquantia                          | 25        | 0.32%   |
| TP-Link                           | 24        | 0.31%   |
| Huawei Technologies               | 23        | 0.3%    |
| DisplayLink                       | 22        | 0.28%   |
| Xiaomi                            | 21        | 0.27%   |
| Mellanox Technologies             | 20        | 0.26%   |
| VIA Technologies                  | 16        | 0.21%   |
| Silicon Integrated Systems [SiS]  | 14        | 0.18%   |
| Qualcomm                          | 13        | 0.17%   |
| IBM                               | 13        | 0.17%   |
| D-Link System                     | 11        | 0.14%   |
| American Megatrends               | 10        | 0.13%   |
| ICS Advent                        | 9         | 0.12%   |
| Microsoft                         | 8         | 0.1%    |
| Cypress Semiconductor             | 8         | 0.1%    |
| 3Com                              | 8         | 0.1%    |
| Motorola PCS                      | 7         | 0.09%   |
| Standard Microsystems             | 6         | 0.08%   |
| OPPO Electronics                  | 6         | 0.08%   |
| MediaTek                          | 6         | 0.08%   |
| Hewlett-Packard                   | 6         | 0.08%   |
| Attansic Technology               | 6         | 0.08%   |
| Apple                             | 6         | 0.08%   |
| Sundance Technology Inc / IC Plus | 5         | 0.06%   |
| NetXen Incorporated               | 4         | 0.05%   |
| Google                            | 4         | 0.05%   |
| ZTE WCDMA Technologies MSM        | 3         | 0.04%   |
| Spreadtrum Communications         | 3         | 0.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2831      | 35.37%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 430       | 5.37%   |
| Nvidia MCP79 Ethernet                                             | 322       | 4.02%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 275       | 3.44%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 219       | 2.74%   |
| Intel I211 Gigabit Network Connection                             | 182       | 2.27%   |
| Intel Ethernet Connection (13) I219-V                             | 141       | 1.76%   |
| Realtek RTL8125 2.5GbE Controller                                 | 130       | 1.62%   |
| Intel I210 Gigabit Network Connection                             | 99        | 1.24%   |
| Intel Ethernet Connection (2) I219-V                              | 93        | 1.16%   |
| Intel 82579V Gigabit Network Connection                           | 81        | 1.01%   |
| Intel Ethernet Connection I217-LM                                 | 80        | 1%      |
| Intel 82574L Gigabit Network Connection                           | 72        | 0.9%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller           | 64        | 0.8%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 63        | 0.79%   |
| Intel Ethernet Connection (4) I219-V                              | 63        | 0.79%   |
| Intel Ethernet Controller I225-V                                  | 62        | 0.77%   |
| Intel Ethernet Connection (4) I219-LM                             | 58        | 0.72%   |
| Intel Ethernet Connection (6) I219-V                              | 57        | 0.71%   |
| Intel Ethernet Connection I219-LM                                 | 56        | 0.7%    |
| Intel Ethernet Connection I218-LM                                 | 55        | 0.69%   |
| Intel Ethernet Connection (7) I219-V                              | 55        | 0.69%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 51        | 0.64%   |
| Intel Ethernet Connection (3) I218-LM                             | 50        | 0.62%   |
| ASIX AX88179 Gigabit Ethernet                                     | 50        | 0.62%   |
| Intel I350 Gigabit Network Connection                             | 49        | 0.61%   |
| Intel Ethernet Connection (2) I219-LM                             | 48        | 0.6%    |
| Intel Ethernet Connection I217-V                                  | 44        | 0.55%   |
| Intel Ethernet Connection (14) I219-V                             | 43        | 0.54%   |
| Nvidia MCP61 Ethernet                                             | 42        | 0.52%   |
| Intel 82577LM Gigabit Network Connection                          | 41        | 0.51%   |
| Intel Ethernet Connection (10) I219-V                             | 40        | 0.5%    |
| Intel Ethernet Connection (2) I218-V                              | 39        | 0.49%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 36        | 0.45%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 34        | 0.42%   |
| Intel 82567LM Gigabit Network Connection                          | 33        | 0.41%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 32        | 0.4%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 30        | 0.37%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 30        | 0.37%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 30        | 0.37%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 7229      | 55.36%  |
| WiFi     | 5638      | 43.18%  |
| Modem    | 173       | 1.32%   |
| Unknown  | 18        | 0.14%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 4344      | 51.81%  |
| WiFi     | 4040      | 48.19%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4339      | 51.93%  |
| 1     | 3333      | 39.89%  |
| 0     | 318       | 3.81%   |
| 3     | 219       | 2.62%   |
| 4     | 86        | 1.03%   |
| 6     | 23        | 0.28%   |
| 5     | 16        | 0.19%   |
| 8     | 10        | 0.12%   |
| 20    | 2         | 0.02%   |
| 10    | 2         | 0.02%   |
| 7     | 2         | 0.02%   |
| 21    | 1         | 0.01%   |
| 14    | 1         | 0.01%   |
| 13    | 1         | 0.01%   |
| 12    | 1         | 0.01%   |
| 9     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used    | Computers | Percent |
|---------|-----------|---------|
| No      | 7160      | 84.91%  |
| Yes     | 1271      | 15.07%  |
| Unknown | 1         | 0.01%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 2159      | 46.13%  |
| Apple                           | 636       | 13.59%  |
| Realtek Semiconductor           | 372       | 7.95%   |
| Qualcomm Atheros Communications | 363       | 7.76%   |
| Broadcom                        | 227       | 4.85%   |
| Cambridge Silicon Radio         | 223       | 4.76%   |
| IMC Networks                    | 151       | 3.23%   |
| Lite-On Technology              | 130       | 2.78%   |
| Foxconn / Hon Hai               | 89        | 1.9%    |
| ASUSTek Computer                | 84        | 1.79%   |
| Dell                            | 58        | 1.24%   |
| Hewlett-Packard                 | 42        | 0.9%    |
| Toshiba                         | 23        | 0.49%   |
| Realtek                         | 23        | 0.49%   |
| MediaTek                        | 20        | 0.43%   |
| Ralink                          | 19        | 0.41%   |
| Foxconn International           | 9         | 0.19%   |
| Alps Electric                   | 6         | 0.13%   |
| TP-Link                         | 5         | 0.11%   |
| Ralink Technology               | 5         | 0.11%   |
| Edimax Technology               | 4         | 0.09%   |
| Belkin Components               | 4         | 0.09%   |
| Taiyo Yuden                     | 3         | 0.06%   |
| Marvell Semiconductor           | 3         | 0.06%   |
| Integrated System Solution      | 3         | 0.06%   |
| USI                             | 2         | 0.04%   |
| Unknown                         | 2         | 0.04%   |
| Qcom                            | 2         | 0.04%   |
| Micro Star International        | 2         | 0.04%   |
| Fujitsu                         | 2         | 0.04%   |
| Sitecom Europe                  | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Microsoft                       | 1         | 0.02%   |
| Kensington                      | 1         | 0.02%   |
| Dynex                           | 1         | 0.02%   |
| Com One                         | 1         | 0.02%   |
| Chicony Electronics             | 1         | 0.02%   |
| Askey Computer                  | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 822       | 17.55%  |
| Intel Bluetooth Device                              | 498       | 10.63%  |
| Apple Built-in Bluetooth 2.0+EDR HCI                | 322       | 6.87%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 306       | 6.53%   |
| Intel AX200 Bluetooth                               | 259       | 5.53%   |
| Realtek Bluetooth Radio                             | 232       | 4.95%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 223       | 4.76%   |
| Qualcomm Atheros  Bluetooth Device                  | 201       | 4.29%   |
| Apple Bluetooth USB Host Controller                 | 180       | 3.84%   |
| Realtek  Bluetooth 4.2 Adapter                      | 92        | 1.96%   |
| Lite-On Bluetooth Device                            | 83        | 1.77%   |
| Intel Wireless-AC 3168 Bluetooth                    | 79        | 1.69%   |
| Apple Bluetooth HCI MacBookPro (HID mode)           | 79        | 1.69%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 75        | 1.6%    |
| Intel Centrino Bluetooth Wireless Transceiver       | 50        | 1.07%   |
| IMC Networks Bluetooth Radio                        | 47        | 1%      |
| Intel AX210 Bluetooth                               | 45        | 0.96%   |
| IMC Networks Bluetooth Device                       | 45        | 0.96%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 44        | 0.94%   |
| Apple Bluetooth Host Controller                     | 41        | 0.88%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 38        | 0.81%   |
| Broadcom BCM2045B (BDC-2.1)                         | 38        | 0.81%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 36        | 0.77%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]          | 34        | 0.73%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 33        | 0.7%    |
| Foxconn / Hon Hai Bluetooth Device                  | 30        | 0.64%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter    | 29        | 0.62%   |
| Realtek Bluetooth Radio                             | 23        | 0.49%   |
| Foxconn / Hon Hai Wireless_Device                   | 22        | 0.47%   |
| IMC Networks Wireless_Device                        | 21        | 0.45%   |
| Dell DW375 Bluetooth Module                         | 21        | 0.45%   |
| ASUS Broadcom BCM20702A0 Bluetooth                  | 21        | 0.45%   |
| Realtek RTL8723B Bluetooth                          | 19        | 0.41%   |
| Ralink RT3290 Bluetooth                             | 19        | 0.41%   |
| MediaTek Wireless_Device                            | 19        | 0.41%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 18        | 0.38%   |
| Lite-On Atheros AR3012 Bluetooth                    | 18        | 0.38%   |
| HP Broadcom 2070 Bluetooth Combo                    | 18        | 0.38%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]       | 17        | 0.36%   |
| Dell BCM20702A0 Bluetooth Module                    | 15        | 0.32%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 5680      | 54.99%  |
| AMD                              | 1881      | 18.21%  |
| Nvidia                           | 1812      | 17.54%  |
| C-Media Electronics              | 145       | 1.4%    |
| Logitech                         | 80        | 0.77%   |
| Creative Labs                    | 53        | 0.51%   |
| Texas Instruments                | 43        | 0.42%   |
| Realtek Semiconductor            | 34        | 0.33%   |
| Lenovo                           | 33        | 0.32%   |
| Plantronics                      | 32        | 0.31%   |
| GN Netcom                        | 32        | 0.31%   |
| ASUSTek Computer                 | 32        | 0.31%   |
| Generalplus Technology           | 31        | 0.3%    |
| JMTek                            | 24        | 0.23%   |
| Creative Technology              | 24        | 0.23%   |
| Focusrite-Novation               | 23        | 0.22%   |
| Kingston Technology              | 20        | 0.19%   |
| VIA Technologies                 | 18        | 0.17%   |
| Hewlett-Packard                  | 15        | 0.15%   |
| Dell                             | 15        | 0.15%   |
| Silicon Integrated Systems [SiS] | 14        | 0.14%   |
| BEHRINGER International          | 13        | 0.13%   |
| RODE Microphones                 | 12        | 0.12%   |
| Razer USA                        | 12        | 0.12%   |
| Micro Star International         | 12        | 0.12%   |
| Microsoft                        | 11        | 0.11%   |
| SteelSeries ApS                  | 10        | 0.1%    |
| Sennheiser Communications        | 10        | 0.1%    |
| GYROCOM C&C                      | 10        | 0.1%    |
| Corsair                          | 8         | 0.08%   |
| Blue Microphones                 | 8         | 0.08%   |
| Yamaha                           | 7         | 0.07%   |
| M-Audio                          | 7         | 0.07%   |
| KTMicro                          | 6         | 0.06%   |
| Cambridge Silicon Radio          | 6         | 0.06%   |
| XMOS                             | 5         | 0.05%   |
| Tenx Technology                  | 5         | 0.05%   |
| Samson Technologies              | 5         | 0.05%   |
| Unknown                          | 4         | 0.04%   |
| SAVITECH                         | 4         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                                                   | 575       | 4.71%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 548       | 4.49%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 470       | 3.85%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 461       | 3.77%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 377       | 3.09%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 342       | 2.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 337       | 2.76%   |
| Nvidia MCP79 High Definition Audio                                                                | 324       | 2.65%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 303       | 2.48%   |
| Intel Broadwell-U Audio Controller                                                                | 288       | 2.36%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 283       | 2.32%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 268       | 2.19%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 253       | 2.07%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 251       | 2.05%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 248       | 2.03%   |
| Intel Cannon Lake PCH cAVS                                                                        | 236       | 1.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 206       | 1.69%   |
| Intel 200 Series PCH HD Audio                                                                     | 183       | 1.5%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 176       | 1.44%   |
| AMD FCH Azalia Controller                                                                         | 176       | 1.44%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 170       | 1.39%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 168       | 1.38%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 159       | 1.3%    |
| Intel 8 Series HD Audio Controller                                                                | 159       | 1.3%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 151       | 1.24%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                                               | 150       | 1.23%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 142       | 1.16%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 142       | 1.16%   |
| Intel Comet Lake PCH cAVS                                                                         | 141       | 1.15%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 133       | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 128       | 1.05%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 122       | 1%      |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 120       | 0.98%   |
| AMD Kabini HDMI/DP Audio                                                                          | 116       | 0.95%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 106       | 0.87%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 99        | 0.81%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 94        | 0.77%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 85        | 0.7%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 81        | 0.66%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]                           | 81        | 0.66%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 1621      | 21.16%  |
| SK hynix            | 1499      | 19.57%  |
| Kingston            | 900       | 11.75%  |
| Unknown             | 797       | 10.41%  |
| Micron Technology   | 593       | 7.74%   |
| Crucial             | 589       | 7.69%   |
| Corsair             | 304       | 3.97%   |
| G.Skill             | 215       | 2.81%   |
| Elpida              | 145       | 1.89%   |
| A-DATA Technology   | 131       | 1.71%   |
| Ramaxel Technology  | 102       | 1.33%   |
| Patriot             | 83        | 1.08%   |
| Unknown             | 75        | 0.98%   |
| Unknown (ABCD)      | 70        | 0.91%   |
| Nanya Technology    | 69        | 0.9%    |
| Smart               | 43        | 0.56%   |
| Team                | 42        | 0.55%   |
| Transcend           | 37        | 0.48%   |
| GOODRAM             | 31        | 0.4%    |
| AMD                 | 25        | 0.33%   |
| Hikvision           | 21        | 0.27%   |
| Apacer              | 16        | 0.21%   |
| Hewlett-Packard     | 15        | 0.2%    |
| Teikon              | 13        | 0.17%   |
| Qimonda             | 11        | 0.14%   |
| Silicon Power       | 10        | 0.13%   |
| 48spaces            | 10        | 0.13%   |
| PNY                 | 9         | 0.12%   |
| Timetec             | 7         | 0.09%   |
| GeIL                | 7         | 0.09%   |
| Smart Brazil        | 6         | 0.08%   |
| Goldkey             | 6         | 0.08%   |
| Avant               | 6         | 0.08%   |
| ASint Technology    | 6         | 0.08%   |
| Wilk                | 5         | 0.07%   |
| Unifosa             | 4         | 0.05%   |
| Toshiba             | 4         | 0.05%   |
| Neo Forza           | 4         | 0.05%   |
| Kllisre             | 4         | 0.05%   |
| Infineon            | 4         | 0.05%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM Module 1GB SODIMM DDR2 800MT/s                      | 257       | 3.13%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 154       | 1.87%   |
| Unknown                                                          | 75        | 0.91%   |
| SK hynix RAM Module 1GB SODIMM DDR2 667MT/s                      | 68        | 0.83%   |
| Samsung RAM M471B5674QH0-YK0 2GB SODIMM DDR3 1600MT/s            | 67        | 0.82%   |
| Samsung RAM Module 2GB SODIMM DDR3 1600MT/s                      | 63        | 0.77%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8192MB SODIMM DDR4 2667MT/s        | 44        | 0.54%   |
| Crucial RAM CT8G4SFRA266.C8FD1 8GB SODIMM DDR4 2667MT/s          | 44        | 0.54%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 43        | 0.52%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 41        | 0.5%    |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 39        | 0.47%   |
| Elpida RAM Module 4GB SODIMM DDR3 1600MT/s                       | 39        | 0.47%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 38        | 0.46%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 38        | 0.46%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 37        | 0.45%   |
| Kingston RAM 99U5584-010.A00LF 4GB DIMM DDR3 1866MT/s            | 36        | 0.44%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 34        | 0.41%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 34        | 0.41%   |
| Unknown (ABCD) RAM 123456789012345678 4GB DIMM DDR4 2400MT/s     | 33        | 0.4%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 33        | 0.4%    |
| SK hynix RAM HMT451S6BFR8A-PB 4096MB SODIMM DDR3 1600MT/s        | 31        | 0.38%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 31        | 0.38%   |
| Crucial RAM CT8G4DFRA266.M16FG 8GB DIMM DDR4 2666MT/s            | 31        | 0.38%   |
| SK hynix RAM Module 4GB SODIMM DDR3 1600MT/s                     | 30        | 0.36%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 30        | 0.36%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 30        | 0.36%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 29        | 0.35%   |
| Samsung RAM Module 1GB SODIMM DDR2 800MT/s                       | 29        | 0.35%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 27        | 0.33%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.33%   |
| Crucial RAM CT4G4DFS8213.C8FAR2 4GB DIMM DDR4 2133MT/s           | 27        | 0.33%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 26        | 0.32%   |
| Samsung RAM Module 4GB SODIMM DDR3 1600MT/s                      | 25        | 0.3%    |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 25        | 0.3%    |
| Crucial RAM CT8G4SFS824A.M8FE 8GB SODIMM DDR4 2667MT/s           | 25        | 0.3%    |
| SK hynix RAM Module 2GB SODIMM DDR2 800MT/s                      | 24        | 0.29%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 24        | 0.29%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 24        | 0.29%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 24        | 0.29%   |
| Crucial RAM CT8G4DFRA266.C8FN 8GB DIMM DDR4 2866MT/s             | 24        | 0.29%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind         | Computers | Percent |
|--------------|-----------|---------|
| DDR4         | 2862      | 42.25%  |
| DDR3         | 2305      | 34.03%  |
| DDR2         | 697       | 10.29%  |
| Unknown      | 220       | 3.25%   |
| SDRAM        | 219       | 3.23%   |
| LPDDR4       | 185       | 2.73%   |
| LPDDR3       | 154       | 2.27%   |
| DDR          | 71        | 1.05%   |
| DDR5         | 30        | 0.44%   |
| DRAM         | 15        | 0.22%   |
| LPDDR5       | 14        | 0.21%   |
| RAM          | 1         | 0.01%   |
| DDR2 FB-DIMM | 1         | 0.01%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 3726      | 55.23%  |
| DIMM         | 2621      | 38.85%  |
| Row Of Chips | 291       | 4.31%   |
| Unknown      | 58        | 0.86%   |
| Chip         | 34        | 0.5%    |
| FB-DIMM      | 12        | 0.18%   |
| RIMM         | 4         | 0.06%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 2368      | 32.31%  |
| 4096  | 1849      | 25.23%  |
| 2048  | 1121      | 15.3%   |
| 16384 | 953       | 13%     |
| 1024  | 678       | 9.25%   |
| 32768 | 250       | 3.41%   |
| 512   | 72        | 0.98%   |
| 256   | 22        | 0.3%    |
| 65536 | 7         | 0.1%    |
| 1536  | 4         | 0.05%   |
| 128   | 4         | 0.05%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 1549      | 21.32%  |
| 2667    | 936       | 12.89%  |
| 3200    | 927       | 12.76%  |
| 1333    | 520       | 7.16%   |
| 800     | 483       | 6.65%   |
| 2400    | 473       | 6.51%   |
| 2133    | 355       | 4.89%   |
| 667     | 262       | 3.61%   |
| Unknown | 203       | 2.79%   |
| 1334    | 173       | 2.38%   |
| 3600    | 146       | 2.01%   |
| 1867    | 107       | 1.47%   |
| 2666    | 90        | 1.24%   |
| 1067    | 87        | 1.2%    |
| 1866    | 86        | 1.18%   |
| 1066    | 73        | 1%      |
| 4267    | 63        | 0.87%   |
| 3400    | 50        | 0.69%   |
| 3266    | 50        | 0.69%   |
| 2933    | 48        | 0.66%   |
| 3000    | 46        | 0.63%   |
| 533     | 40        | 0.55%   |
| 3733    | 33        | 0.45%   |
| 3466    | 32        | 0.44%   |
| 4199    | 31        | 0.43%   |
| 400     | 29        | 0.4%    |
| 2866    | 27        | 0.37%   |
| 2048    | 27        | 0.37%   |
| 4800    | 25        | 0.34%   |
| 1800    | 22        | 0.3%    |
| 975     | 19        | 0.26%   |
| 8400    | 16        | 0.22%   |
| 3800    | 16        | 0.22%   |
| 333     | 16        | 0.22%   |
| 6400    | 15        | 0.21%   |
| 3866    | 14        | 0.19%   |
| 266     | 13        | 0.18%   |
| 4266    | 12        | 0.17%   |
| 3100    | 9         | 0.12%   |
| 2800    | 9         | 0.12%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor                 | Computers | Percent |
|------------------------|-----------|---------|
| Hewlett-Packard        | 57        | 32.76%  |
| Brother Industries     | 31        | 17.82%  |
| Canon                  | 21        | 12.07%  |
| Samsung Electronics    | 12        | 6.9%    |
| Seiko Epson            | 10        | 5.75%   |
| Xerox                  | 8         | 4.6%    |
| Prolific Technology    | 5         | 2.87%   |
| Dymo-CoStar            | 5         | 2.87%   |
| Kyocera                | 4         | 2.3%    |
| Zebra                  | 3         | 1.72%   |
| Pantum                 | 3         | 1.72%   |
| STMicroelectronics     | 2         | 1.15%   |
| Lexmark International  | 2         | 1.15%   |
| Datamax-O'Neil         | 2         | 1.15%   |
| Xiaomi                 | 1         | 0.57%   |
| Ricoh                  | 1         | 0.57%   |
| QinHeng Electronics    | 1         | 0.57%   |
| Panasonic (Matsushita) | 1         | 0.57%   |
| Oki Data               | 1         | 0.57%   |
| Konica Minolta         | 1         | 0.57%   |
| GODEX INTERNATIONAL    | 1         | 0.57%   |
| Dell                   | 1         | 0.57%   |
| Apple                  | 1         | 0.57%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Xerox B205                                                            | 7         | 3.98%   |
| HP LaserJet 1020                                                      | 7         | 3.98%   |
| Prolific PL2305 Parallel Port                                         | 5         | 2.84%   |
| HP LaserJet 1200                                                      | 4         | 2.27%   |
| HP LaserJet M101-M106                                                 | 3         | 1.7%    |
| HP DeskJet 2130 series                                                | 3         | 1.7%    |
| Brother HL-52x0 series                                                | 3         | 1.7%    |
| STMicroelectronics LED badge -- mini LED display -- 11x44             | 2         | 1.14%   |
| Samsung ML-216x Series Laser Printer                                  | 2         | 1.14%   |
| Samsung ML-1660 Series                                                | 2         | 1.14%   |
| Pantum P2500W series                                                  | 2         | 1.14%   |
| Lexmark International CS417dn                                         | 2         | 1.14%   |
| HP LaserJet Pro M404-M405                                             | 2         | 1.14%   |
| HP LaserJet P1005                                                     | 2         | 1.14%   |
| HP LaserJet M14-M17                                                   | 2         | 1.14%   |
| HP LaserJet 400 M401n                                                 | 2         | 1.14%   |
| HP ENVY Photo 6200 series                                             | 2         | 1.14%   |
| HP ENVY 4520 series                                                   | 2         | 1.14%   |
| HP DeskJet Plus 4100 series                                           | 2         | 1.14%   |
| HP DeskJet 2600 series                                                | 2         | 1.14%   |
| Dymo-CoStar LabelWriter 450                                           | 2         | 1.14%   |
| Dymo-CoStar DYMO LabelWriter 450 Turbo                                | 2         | 1.14%   |
| Datamax-O'Neil Datamax E-4304                                         | 2         | 1.14%   |
| Canon PIXMA MX920 Series                                              | 2         | 1.14%   |
| Canon PIXMA MG3600 Series                                             | 2         | 1.14%   |
| Canon MF4410                                                          | 2         | 1.14%   |
| Canon LiDE 400                                                        | 2         | 1.14%   |
| Canon G3010 series                                                    | 2         | 1.14%   |
| Brother Printer                                                       | 2         | 1.14%   |
| Zebra ZTC ZP 500 (ZPL)                                                | 1         | 0.57%   |
| Zebra ZTC ZD420-203dpi ZPL                                            | 1         | 0.57%   |
| Zebra ZTC S4M-200dpi ZPL                                              | 1         | 0.57%   |
| Xiaomi MiMouse 2                                                      | 1         | 0.57%   |
| Xerox Phaser 3250                                                     | 1         | 0.57%   |
| Seiko Epson XP-200 Series                                             | 1         | 0.57%   |
| Seiko Epson XP-15000 Series                                           | 1         | 0.57%   |
| Seiko Epson Printer                                                   | 1         | 0.57%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 1         | 0.57%   |
| Seiko Epson L396 Series                                               | 1         | 0.57%   |
| Seiko Epson L210 Series                                               | 1         | 0.57%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 29        | 56.86%  |
| Seiko Epson        | 11        | 21.57%  |
| Hewlett-Packard    | 6         | 11.76%  |
| Mustek Systems     | 2         | 3.92%   |
| AGFA-Gevaert NV    | 2         | 3.92%   |
| Ultima Electronics | 1         | 1.96%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 8         | 15.69%  |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 5         | 9.8%    |
| Canon CanoScan LiDE 220                                                               | 4         | 7.84%   |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 3.92%   |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 3.92%   |
| Canon CanoScan LIDE 25                                                                | 2         | 3.92%   |
| Canon CanoScan LiDE 210                                                               | 2         | 3.92%   |
| Canon CanoScan LiDE 120                                                               | 2         | 3.92%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                                                    | 2         | 3.92%   |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 1.96%   |
| Seiko Epson GT-F650 [GT-S600/Perfection V10/V100]                                     | 1         | 1.96%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 1         | 1.96%   |
| Seiko Epson GT-9800F [Perfection 3200]                                                | 1         | 1.96%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 1.96%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 1.96%   |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO]                         | 1         | 1.96%   |
| Seiko Epson GT-8300UF [Perfection 1660 PHOTO]                                         | 1         | 1.96%   |
| Seiko Epson GT-8200U/GT-8200UF [Perfection 1650/1650 PHOTO]                           | 1         | 1.96%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 1         | 1.96%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 1.96%   |
| Mustek Systems BearPaw 2448 TA Pro                                                    | 1         | 1.96%   |
| HP ScanJet Pro 2500 f1                                                                | 1         | 1.96%   |
| HP ScanJet 82x0C                                                                      | 1         | 1.96%   |
| HP ScanJet 7650                                                                       | 1         | 1.96%   |
| HP ScanJet 3970c                                                                      | 1         | 1.96%   |
| HP Scanjet 300                                                                        | 1         | 1.96%   |
| HP Scanjet 200                                                                        | 1         | 1.96%   |
| Canon CanoScan LiDE 50/LiDE 35/LiDE 40                                                | 1         | 1.96%   |
| Canon CanoScan 9000F Mark II                                                          | 1         | 1.96%   |
| Canon CanoScan 8800F                                                                  | 1         | 1.96%   |
| Canon CanoScan 5600F                                                                  | 1         | 1.96%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 921       | 21.87%  |
| Acer                                   | 450       | 10.68%  |
| IMC Networks                           | 399       | 9.47%   |
| Microdia                               | 327       | 7.76%   |
| Realtek Semiconductor                  | 297       | 7.05%   |
| Logitech                               | 271       | 6.43%   |
| Quanta                                 | 256       | 6.08%   |
| Sunplus Innovation Technology          | 196       | 4.65%   |
| Cheng Uei Precision Industry (Foxlink) | 111       | 2.64%   |
| Suyin                                  | 110       | 2.61%   |
| Apple                                  | 100       | 2.37%   |
| Lite-On Technology                     | 88        | 2.09%   |
| Syntek                                 | 84        | 1.99%   |
| Luxvisions Innotech Limited            | 62        | 1.47%   |
| Alcor Micro                            | 49        | 1.16%   |
| Silicon Motion                         | 48        | 1.14%   |
| Samsung Electronics                    | 36        | 0.85%   |
| Microsoft                              | 34        | 0.81%   |
| Z-Star Microelectronics                | 33        | 0.78%   |
| Ricoh                                  | 30        | 0.71%   |
| Lenovo                                 | 30        | 0.71%   |
| Generalplus Technology                 | 21        | 0.5%    |
| Primax Electronics                     | 17        | 0.4%    |
| Creative Technology                    | 15        | 0.36%   |
| Sonix Technology                       | 13        | 0.31%   |
| Genesys Logic                          | 13        | 0.31%   |
| ARC International                      | 12        | 0.28%   |
| GEMBIRD                                | 11        | 0.26%   |
| KYE Systems (Mouse Systems)            | 10        | 0.24%   |
| Jieli Technology                       | 10        | 0.24%   |
| ALi                                    | 10        | 0.24%   |
| Unknown                                | 9         | 0.21%   |
| Importek                               | 9         | 0.21%   |
| SunplusIT                              | 7         | 0.17%   |
| MacroSilicon                           | 7         | 0.17%   |
| icSpring                               | 7         | 0.17%   |
| Intel                                  | 6         | 0.14%   |
| Cubeternet                             | 6         | 0.14%   |
| OmniVision Technologies                | 5         | 0.12%   |
| Hewlett-Packard                        | 5         | 0.12%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 266       | 6.21%   |
| Acer Integrated Camera                              | 168       | 3.93%   |
| IMC Networks Integrated Camera                      | 135       | 3.15%   |
| Microdia Integrated_Webcam_HD                       | 134       | 3.13%   |
| Realtek Integrated_Webcam_HD                        | 111       | 2.59%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 85        | 1.99%   |
| Chicony HD WebCam                                   | 77        | 1.8%    |
| Acer Integrated 5M Camera                           | 73        | 1.71%   |
| Logitech Webcam C270                                | 70        | 1.64%   |
| Quanta Chromebook HD Camera                         | 68        | 1.59%   |
| Sunplus Integrated_Webcam_HD                        | 65        | 1.52%   |
| Acer BisonCam, NB Pro                               | 60        | 1.4%    |
| Syntek Integrated Camera                            | 46        | 1.07%   |
| Chicony HP HD Camera                                | 44        | 1.03%   |
| Chicony Integrated 5M Camera                        | 43        | 1%      |
| Chicony USB2.0 HD UVC WebCam                        | 41        | 0.96%   |
| Logitech HD Pro Webcam C920                         | 39        | 0.91%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 39        | 0.91%   |
| Quanta HP TrueVision HD Camera                      | 36        | 0.84%   |
| Samsung Galaxy A5 (MTP)                             | 35        | 0.82%   |
| Lite-On Integrated Camera                           | 34        | 0.79%   |
| Microdia Integrated Webcam                          | 33        | 0.77%   |
| Acer Lenovo EasyCamera                              | 33        | 0.77%   |
| Apple iPhone 5/5C/5S/6/SE                           | 31        | 0.72%   |
| Apple Built-in iSight                               | 31        | 0.72%   |
| Acer SunplusIT Integrated Camera                    | 30        | 0.7%    |
| Chicony Integrated Camera (1280x720@30)             | 29        | 0.68%   |
| Chicony EasyCamera                                  | 26        | 0.61%   |
| Realtek USB Camera                                  | 25        | 0.58%   |
| Quanta HP HD Camera                                 | 25        | 0.58%   |
| Quanta HD User Facing                               | 25        | 0.58%   |
| Microdia USB 2.0 Camera                             | 25        | 0.58%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 25        | 0.58%   |
| Logitech C922 Pro Stream Webcam                     | 25        | 0.58%   |
| Chicony HP TrueVision HD Camera                     | 24        | 0.56%   |
| Apple FaceTime HD Camera (Built-in)                 | 24        | 0.56%   |
| Quanta VGA WebCam                                   | 23        | 0.54%   |
| Sunplus HD WebCam                                   | 21        | 0.49%   |
| Chicony HD User Facing                              | 21        | 0.49%   |
| Lite-On HP HD Camera                                | 20        | 0.47%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Synaptics                          | 367       | 41.38%  |
| Validity Sensors                   | 246       | 27.73%  |
| Shenzhen Goodix Technology         | 104       | 11.72%  |
| AuthenTec                          | 44        | 4.96%   |
| Upek                               | 42        | 4.74%   |
| Elan Microelectronics              | 40        | 4.51%   |
| LighTuning Technology              | 22        | 2.48%   |
| STMicroelectronics                 | 15        | 1.69%   |
| Samsung Electronics                | 4         | 0.45%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.23%   |
| Microsoft                          | 1         | 0.11%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 217       | 24.46%  |
| Shenzhen Goodix  Fingerprint Device                                        | 56        | 6.31%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 55        | 6.2%    |
| Unknown                                                                    | 51        | 5.75%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 47        | 5.3%    |
| Validity Sensors VFS495 Fingerprint Reader                                 | 43        | 4.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 4.28%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 30        | 3.38%   |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 3.38%   |
| Elan ELAN:Fingerprint                                                      | 24        | 2.71%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 21        | 2.37%   |
| Validity Sensors Synaptics WBDI                                            | 20        | 2.25%   |
| Shenzhen Goodix FingerPrint                                                | 18        | 2.03%   |
| AuthenTec AES2810                                                          | 18        | 2.03%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 17        | 1.92%   |
| Synaptics  WBDI                                                            | 16        | 1.8%    |
| Elan ELAN:ARM-M4                                                           | 15        | 1.69%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 14        | 1.58%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 14        | 1.58%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 14        | 1.58%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.58%   |
| STMicroelectronics Fingerprint Reader                                      | 13        | 1.47%   |
| Validity Sensors VFS491                                                    | 11        | 1.24%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 10        | 1.13%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 1.01%   |
| Validity Sensors VFS Fingerprint sensor                                    | 9         | 1.01%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 9         | 1.01%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 6         | 0.68%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 5         | 0.56%   |
| Validity Sensors Fingerprint scanner                                       | 5         | 0.56%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 4         | 0.45%   |
| Upek TCS5B Fingerprint sensor                                              | 4         | 0.45%   |
| AuthenTec Fingerprint Sensor                                               | 4         | 0.45%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 4         | 0.45%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 3         | 0.34%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 3         | 0.34%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 2         | 0.23%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 2         | 0.23%   |
| STMicroelectronics TouchChipÂ Fingerprint Reader                          | 2         | 0.23%   |
| Realtek USB2.0 Finger Print Bridge FocalTech Fingerprint Device            | 2         | 0.23%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 139       | 34.84%  |
| Broadcom                   | 138       | 34.59%  |
| Lenovo                     | 27        | 6.77%   |
| Upek                       | 26        | 6.52%   |
| O2 Micro                   | 24        | 6.02%   |
| Gemalto (was Gemplus)      | 8         | 2.01%   |
| SCM Microsystems           | 6         | 1.5%    |
| Clay Logic                 | 6         | 1.5%    |
| Yubico.com                 | 4         | 1%      |
| Cherry                     | 4         | 1%      |
| Aladdin Knowledge Systems  | 4         | 1%      |
| Advanced Card Systems      | 3         | 0.75%   |
| Reiner SCT Kartensysteme   | 2         | 0.5%    |
| Chicony Electronics        | 2         | 0.5%    |
| Realtek Semiconductor      | 1         | 0.25%   |
| OmniKey                    | 1         | 0.25%   |
| Hewlett-Packard            | 1         | 0.25%   |
| Feitian Technologies       | 1         | 0.25%   |
| C3PO                       | 1         | 0.25%   |
| Athena Smartcard Solutions | 1         | 0.25%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 136       | 34.09%  |
| Broadcom BCM5880 Secure Applications Processor                               | 44        | 11.03%  |
| Broadcom 58200                                                               | 38        | 9.52%   |
| Broadcom 5880                                                                | 34        | 8.52%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 26        | 6.52%   |
| Lenovo Integrated Smart Card Reader                                          | 26        | 6.52%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 21        | 5.26%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 5.01%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 1.25%   |
| Aladdin Knowledge Systems Token JC                                           | 4         | 1%      |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 3         | 0.75%   |
| SCM Microsystems SCR331-LC1 / SCR3310 SmartCard Reader                       | 3         | 0.75%   |
| O2 Micro Oz776 SmartCard Reader                                              | 3         | 0.75%   |
| Clay Logic Nitrokey Start                                                    | 3         | 0.75%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.75%   |
| Alcor Micro Watchdata W 1981                                                 | 3         | 0.75%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.5%    |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 2         | 0.5%    |
| Chicony Electronics HP Skylab USB Smartcard Keyboard                         | 2         | 0.5%    |
| Cherry SmartCard Reader Keyboard KC 1000 SC                                  | 2         | 0.5%    |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.5%    |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 2         | 0.5%    |
| Yubico.com Yubikey 4/5 CCID                                                  | 1         | 0.25%   |
| SCM Microsystems uTrust FIDO2 Security Key                                   | 1         | 0.25%   |
| SCM Microsystems uTrust 3512 SAM slot Token                                  | 1         | 0.25%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.25%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 1         | 0.25%   |
| OmniKey CardMan 4321                                                         | 1         | 0.25%   |
| Lenovo Smartcard Keyboard                                                    | 1         | 0.25%   |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 1         | 0.25%   |
| Gemalto (was Gemplus) GemPC Key SmartCard Reader                             | 1         | 0.25%   |
| Feitian Technologies SCR301                                                  | 1         | 0.25%   |
| Cherry SmartTerminal XX1X                                                    | 1         | 0.25%   |
| Cherry Cherry GmbH CHERRY SECURE BOARD 1.0                                   | 1         | 0.25%   |
| C3PO LTC31v2                                                                 | 1         | 0.25%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 0.25%   |
| Advanced Card Systems ACR39U                                                 | 1         | 0.25%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5139      | 60.7%   |
| 1     | 2629      | 31.05%  |
| 2     | 553       | 6.53%   |
| 3     | 112       | 1.32%   |
| 4     | 20        | 0.24%   |
| 5     | 8         | 0.09%   |
| 6     | 3         | 0.04%   |
| 7     | 2         | 0.02%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 1529      | 38.56%  |
| Fingerprint reader       | 883       | 22.27%  |
| Chipcard                 | 348       | 8.78%   |
| Net/wireless             | 323       | 8.15%   |
| Multimedia controller    | 283       | 7.14%   |
| Communication controller | 151       | 3.81%   |
| Unassigned class         | 89        | 2.24%   |
| Bluetooth                | 72        | 1.82%   |
| Camera                   | 62        | 1.56%   |
| Card reader              | 50        | 1.26%   |
| Sound                    | 43        | 1.08%   |
| Storage                  | 37        | 0.93%   |
| Net/ethernet             | 35        | 0.88%   |
| Network                  | 18        | 0.45%   |
| Modem                    | 10        | 0.25%   |
| Storage/raid             | 8         | 0.2%    |
| Storage/ide              | 6         | 0.15%   |
| Flash memory             | 5         | 0.13%   |
| Tv card                  | 4         | 0.1%    |
| Dvb card                 | 4         | 0.1%    |
| Firewire controller      | 3         | 0.08%   |
| Wireless                 | 1         | 0.03%   |
| Storage/ata              | 1         | 0.03%   |

