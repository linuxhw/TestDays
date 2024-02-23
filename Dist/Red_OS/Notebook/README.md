Red OS - Tested Hardware & Statistics (Notebooks)
-------------------------------------------------

A project to collect tested hardware configurations for Red OS.

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

Total: 206

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
| Lenovo        | IdeaPad L340-15API 81LW     | [db2cd07d84](https://linux-hardware.org/?probe=db2cd07d84) | Jan 26, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ca9e77a64e](https://linux-hardware.org/?probe=ca9e77a64e) | Jan 19, 2024 |
| Acer          | Aspire A315-24P             | [abc7a5352b](https://linux-hardware.org/?probe=abc7a5352b) | Jan 14, 2024 |
| Acer          | Aspire A315-24P             | [166d3493a4](https://linux-hardware.org/?probe=166d3493a4) | Jan 14, 2024 |
| Lenovo        | IdeaPad L340-15API 81LW     | [04855eeea8](https://linux-hardware.org/?probe=04855eeea8) | Jan 09, 2024 |
| Acer          | Extensa 215-22              | [c2884d7a5d](https://linux-hardware.org/?probe=c2884d7a5d) | Jan 09, 2024 |
| Lenovo        | ThinkPad T61 6464WM6        | [a0b959c7c4](https://linux-hardware.org/?probe=a0b959c7c4) | Jan 05, 2024 |
| Lenovo        | ThinkPad T61 6464WM6        | [3cf7d0764e](https://linux-hardware.org/?probe=3cf7d0764e) | Jan 05, 2024 |
| Lenovo        | ThinkPad T430 23493V2       | [8cbff5c75a](https://linux-hardware.org/?probe=8cbff5c75a) | Jan 02, 2024 |
| KVADRA        | NAU LE15T                   | [b53fe7cc28](https://linux-hardware.org/?probe=b53fe7cc28) | Jan 02, 2024 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [c71368b0eb](https://linux-hardware.org/?probe=c71368b0eb) | Jan 01, 2024 |
| iRU           | 15ALC                       | [28f7177799](https://linux-hardware.org/?probe=28f7177799) | Dec 22, 2023 |
| Dell          | Precision M4700             | [3048d06ee6](https://linux-hardware.org/?probe=3048d06ee6) | Dec 21, 2023 |
| Lenovo        | V15 G1 IML 82NB             | [90d82dc1a1](https://linux-hardware.org/?probe=90d82dc1a1) | Dec 18, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [c4aead03a2](https://linux-hardware.org/?probe=c4aead03a2) | Dec 13, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | [02763925e5](https://linux-hardware.org/?probe=02763925e5) | Dec 08, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3b62534051](https://linux-hardware.org/?probe=3b62534051) | Nov 29, 2023 |
| Lenovo        | ThinkPad X230 23245C8       | [bf518076d5](https://linux-hardware.org/?probe=bf518076d5) | Nov 29, 2023 |
| Dell          | Vostro 3590                 | [8ca5eb4e42](https://linux-hardware.org/?probe=8ca5eb4e42) | Nov 27, 2023 |
| Lenovo        | ThinkPad T460s 20FAS1TQ0... | [5586688561](https://linux-hardware.org/?probe=5586688561) | Nov 21, 2023 |
| HP            | EliteBook 850 G1            | [7d7599e0d0](https://linux-hardware.org/?probe=7d7599e0d0) | Nov 21, 2023 |
| HUAWEI        | NDZ-WXX9                    | [95caa4b8a1](https://linux-hardware.org/?probe=95caa4b8a1) | Nov 21, 2023 |
| HUAWEI        | NDZ-WXX9                    | [0324427380](https://linux-hardware.org/?probe=0324427380) | Nov 21, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [9dbd54affc](https://linux-hardware.org/?probe=9dbd54affc) | Nov 14, 2023 |
| ASUSTek       | K53SC                       | [e86d8effd9](https://linux-hardware.org/?probe=e86d8effd9) | Nov 11, 2023 |
| Dell          | Precision M4700             | [ab52e67d9d](https://linux-hardware.org/?probe=ab52e67d9d) | Nov 01, 2023 |
| HP            | Pavilion dv6                | [d8a8dfefd7](https://linux-hardware.org/?probe=d8a8dfefd7) | Oct 24, 2023 |
| Dell          | Precision M4700             | [4d590a378f](https://linux-hardware.org/?probe=4d590a378f) | Oct 24, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [41dfd82cb6](https://linux-hardware.org/?probe=41dfd82cb6) | Oct 23, 2023 |
| HP            | Pavilion dv6                | [71c2062cbf](https://linux-hardware.org/?probe=71c2062cbf) | Oct 22, 2023 |
| Graviton      | Unknown                     | [69c721a100](https://linux-hardware.org/?probe=69c721a100) | Oct 10, 2023 |
| HP            | Laptop 15-bw0xx             | [4440996d7b](https://linux-hardware.org/?probe=4440996d7b) | Oct 07, 2023 |
| HP            | Laptop 15-bw0xx             | [7774477854](https://linux-hardware.org/?probe=7774477854) | Oct 07, 2023 |
| HUAWEI        | BDZ-WXX9                    | [a33a848e40](https://linux-hardware.org/?probe=a33a848e40) | Sep 26, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [b85adec006](https://linux-hardware.org/?probe=b85adec006) | Sep 25, 2023 |
| iRU           | 15ALC                       | [c5839fb7da](https://linux-hardware.org/?probe=c5839fb7da) | Sep 17, 2023 |
| iRU           | 15ALC                       | [87679b8dc1](https://linux-hardware.org/?probe=87679b8dc1) | Sep 17, 2023 |
| HP            | ProBook 6570b               | [baf81a81a2](https://linux-hardware.org/?probe=baf81a81a2) | Sep 13, 2023 |
| HP            | ProBook 6570b               | [90aaacf4af](https://linux-hardware.org/?probe=90aaacf4af) | Sep 13, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | [006062545f](https://linux-hardware.org/?probe=006062545f) | Sep 13, 2023 |
| HP            | Laptop 15s-fq2xxx           | [2135954523](https://linux-hardware.org/?probe=2135954523) | Sep 04, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | [7c560dfe57](https://linux-hardware.org/?probe=7c560dfe57) | Aug 31, 2023 |
| ICL           | S1511 G1R                   | [421df1df8d](https://linux-hardware.org/?probe=421df1df8d) | Aug 28, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [a3a1e805b2](https://linux-hardware.org/?probe=a3a1e805b2) | Aug 27, 2023 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [cfe21994b6](https://linux-hardware.org/?probe=cfe21994b6) | Aug 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7d63566e0a](https://linux-hardware.org/?probe=7d63566e0a) | Aug 11, 2023 |
| Dell          | Precision M4700             | [95ac580b0d](https://linux-hardware.org/?probe=95ac580b0d) | Aug 08, 2023 |
| MSI           | Modern 14 C12M              | [aa352b05aa](https://linux-hardware.org/?probe=aa352b05aa) | Aug 03, 2023 |
| Timi          | Redmi Book Pro 15 2022      | [8a2a5c6265](https://linux-hardware.org/?probe=8a2a5c6265) | Jul 30, 2023 |
| Dell          | Vostro 3400                 | [ee71316b5e](https://linux-hardware.org/?probe=ee71316b5e) | Jul 17, 2023 |
| Gigabyte      | G5 ME                       | [eaefa9c2c6](https://linux-hardware.org/?probe=eaefa9c2c6) | Jul 17, 2023 |
| Dell          | Precision M4700             | [7dc84c10b5](https://linux-hardware.org/?probe=7dc84c10b5) | Jul 11, 2023 |
| Dell          | Inspiron 3583               | [3f5ae451c0](https://linux-hardware.org/?probe=3f5ae451c0) | Jul 09, 2023 |
| Timi          | Redmi G 2022                | [30e96afcdd](https://linux-hardware.org/?probe=30e96afcdd) | Jul 08, 2023 |
| Timi          | Redmi G 2022                | [cd2b7e13ce](https://linux-hardware.org/?probe=cd2b7e13ce) | Jul 04, 2023 |
| ICL           | Si1407                      | [c4c9d43042](https://linux-hardware.org/?probe=c4c9d43042) | Jul 04, 2023 |
| Aquarius      | NS483                       | [dd5daf7f12](https://linux-hardware.org/?probe=dd5daf7f12) | Jun 18, 2023 |
| HP            | Laptop 15-bw0xx             | [a161ef52b4](https://linux-hardware.org/?probe=a161ef52b4) | Jun 18, 2023 |
| Lenovo        | G570 20079                  | [4843789a62](https://linux-hardware.org/?probe=4843789a62) | May 30, 2023 |
| Acer          | Aspire A315-58              | [59d36ef46d](https://linux-hardware.org/?probe=59d36ef46d) | May 22, 2023 |
| HP            | EliteBook 8440p             | [3ad250d762](https://linux-hardware.org/?probe=3ad250d762) | May 22, 2023 |
| MSI           | GL62 6QF                    | [6ae5c650f3](https://linux-hardware.org/?probe=6ae5c650f3) | May 14, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [3de097b441](https://linux-hardware.org/?probe=3de097b441) | May 12, 2023 |
| Dell          | Vostro 5391                 | [f5342b41ec](https://linux-hardware.org/?probe=f5342b41ec) | May 06, 2023 |
| Graviton      | N14I-T                      | [e82c8f00d8](https://linux-hardware.org/?probe=e82c8f00d8) | May 05, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a61a9a88bc](https://linux-hardware.org/?probe=a61a9a88bc) | May 02, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | [8f8a912636](https://linux-hardware.org/?probe=8f8a912636) | May 01, 2023 |
| HP            | Laptop 15-bw0xx             | [387eecc18e](https://linux-hardware.org/?probe=387eecc18e) | Apr 27, 2023 |
| HP            | ProBook 440 G8 Notebook ... | [40aaf19667](https://linux-hardware.org/?probe=40aaf19667) | Apr 21, 2023 |
| Unknown       | Unknown                     | [c959a62e36](https://linux-hardware.org/?probe=c959a62e36) | Apr 10, 2023 |
| HONOR         | BMH-WCX9                    | [2082d3c772](https://linux-hardware.org/?probe=2082d3c772) | Apr 08, 2023 |
| Unknown       | Unknown                     | [70ff15284b](https://linux-hardware.org/?probe=70ff15284b) | Apr 07, 2023 |
| Unknown       | Unknown                     | [9a068872f6](https://linux-hardware.org/?probe=9a068872f6) | Apr 06, 2023 |
| HP            | ProBook 4525s               | [164d8993b4](https://linux-hardware.org/?probe=164d8993b4) | Apr 04, 2023 |
| MSI           | Sword 15 A12UE              | [3389b32105](https://linux-hardware.org/?probe=3389b32105) | Apr 01, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [36b3103f3f](https://linux-hardware.org/?probe=36b3103f3f) | Mar 31, 2023 |
| Lenovo        | IdeaPad 1 15ALC7 82R4       | [deb6990c19](https://linux-hardware.org/?probe=deb6990c19) | Mar 27, 2023 |
| HONOR         | NBR-WAX9                    | [ef91ef3645](https://linux-hardware.org/?probe=ef91ef3645) | Mar 27, 2023 |
| MSI           | Modern 15 B12M              | [eded7b36b1](https://linux-hardware.org/?probe=eded7b36b1) | Mar 27, 2023 |
| MSI           | Modern 15 B12M              | [9ee3ca41c8](https://linux-hardware.org/?probe=9ee3ca41c8) | Mar 27, 2023 |
| MSI           | Sword 15 A12UE              | [f4341a491a](https://linux-hardware.org/?probe=f4341a491a) | Mar 21, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [be9b767d92](https://linux-hardware.org/?probe=be9b767d92) | Mar 20, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [b473b68faf](https://linux-hardware.org/?probe=b473b68faf) | Mar 10, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21AJS... | [4a8589fbdf](https://linux-hardware.org/?probe=4a8589fbdf) | Mar 10, 2023 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | [b116afe451](https://linux-hardware.org/?probe=b116afe451) | Feb 27, 2023 |
| Kraftway      | ACCORD                      | [8fe15f2f2b](https://linux-hardware.org/?probe=8fe15f2f2b) | Feb 22, 2023 |
| Lenovo        | B590 20208                  | [10e9491ee4](https://linux-hardware.org/?probe=10e9491ee4) | Feb 17, 2023 |
| Lenovo        | B590 20208                  | [a3b352975c](https://linux-hardware.org/?probe=a3b352975c) | Feb 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [4d9144193f](https://linux-hardware.org/?probe=4d9144193f) | Feb 17, 2023 |
| Lenovo        | ThinkBook 15 G2 ARE 20VG    | [9de0373acc](https://linux-hardware.org/?probe=9de0373acc) | Feb 16, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [09073fcfc8](https://linux-hardware.org/?probe=09073fcfc8) | Feb 10, 2023 |
| HP            | G62                         | [8bc9454fb1](https://linux-hardware.org/?probe=8bc9454fb1) | Feb 10, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [d3b63de821](https://linux-hardware.org/?probe=d3b63de821) | Feb 07, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [a2172caf56](https://linux-hardware.org/?probe=a2172caf56) | Feb 06, 2023 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [77faeb6b52](https://linux-hardware.org/?probe=77faeb6b52) | Feb 06, 2023 |
| HP            | Pavilion 15                 | [eb37d7677c](https://linux-hardware.org/?probe=eb37d7677c) | Feb 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [bb0481d7a8](https://linux-hardware.org/?probe=bb0481d7a8) | Feb 06, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [186aef8e0c](https://linux-hardware.org/?probe=186aef8e0c) | Jan 24, 2023 |
| Lenovo        | V130-15IKB 81HN             | [a74a5b3b7b](https://linux-hardware.org/?probe=a74a5b3b7b) | Jan 20, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8472d89767](https://linux-hardware.org/?probe=8472d89767) | Jan 20, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7d95709d81](https://linux-hardware.org/?probe=7d95709d81) | Jan 19, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | [b6e4100bc6](https://linux-hardware.org/?probe=b6e4100bc6) | Jan 17, 2023 |
| Lenovo        | IdeaPad L340-15API 81LW     | [a05251fd39](https://linux-hardware.org/?probe=a05251fd39) | Dec 29, 2022 |
| 3Logic Gro... | Graviton N15i-K2            | [fe79eba13b](https://linux-hardware.org/?probe=fe79eba13b) | Dec 29, 2022 |
| HP            | Notebook                    | [10dfda9549](https://linux-hardware.org/?probe=10dfda9549) | Dec 24, 2022 |
| Lenovo        | ThinkPad E15 Gen 4 21E60... | [4c1ad2ea2e](https://linux-hardware.org/?probe=4c1ad2ea2e) | Dec 18, 2022 |
| Kraftway      | ACCORD                      | [a199d930ff](https://linux-hardware.org/?probe=a199d930ff) | Dec 18, 2022 |
| Shanghai Z... | ZXE CRB                     | [20ce0a7f23](https://linux-hardware.org/?probe=20ce0a7f23) | Dec 16, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [6cedae9702](https://linux-hardware.org/?probe=6cedae9702) | Dec 10, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [311f47baef](https://linux-hardware.org/?probe=311f47baef) | Dec 09, 2022 |
| HP            | Laptop 15s-eq1xxx           | [79a0f9e73a](https://linux-hardware.org/?probe=79a0f9e73a) | Dec 08, 2022 |
| HP            | Laptop 15s-eq1xxx           | [c1cd524970](https://linux-hardware.org/?probe=c1cd524970) | Dec 08, 2022 |
| Aquarius      | NS685U R11                  | [c0dff8c525](https://linux-hardware.org/?probe=c0dff8c525) | Dec 08, 2022 |
| ICL           | RAYbook Si1512              | [b8c52ae5cb](https://linux-hardware.org/?probe=b8c52ae5cb) | Dec 06, 2022 |
| HP            | Laptop 15s-eq1xxx           | [0cd3371014](https://linux-hardware.org/?probe=0cd3371014) | Dec 05, 2022 |
| MSI           | Sword 15 A12UE              | [32df733b5e](https://linux-hardware.org/?probe=32df733b5e) | Dec 04, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ddb1791ff6](https://linux-hardware.org/?probe=ddb1791ff6) | Nov 28, 2022 |
| Lenovo        | IdeaPad 700-15ISK 80RU      | [d9ae3d1795](https://linux-hardware.org/?probe=d9ae3d1795) | Nov 27, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [ff3d0a1ecf](https://linux-hardware.org/?probe=ff3d0a1ecf) | Nov 24, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [f86569d54b](https://linux-hardware.org/?probe=f86569d54b) | Nov 24, 2022 |
| HUAWEI        | NBD-WXX9                    | [a54f42b51e](https://linux-hardware.org/?probe=a54f42b51e) | Nov 18, 2022 |
| HUAWEI        | NBD-WXX9                    | [faa0deab8f](https://linux-hardware.org/?probe=faa0deab8f) | Nov 18, 2022 |
| Lenovo        | ThinkPad X220 4290RB3       | [37959973aa](https://linux-hardware.org/?probe=37959973aa) | Nov 11, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3fd33e6782](https://linux-hardware.org/?probe=3fd33e6782) | Nov 09, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [dba14315ca](https://linux-hardware.org/?probe=dba14315ca) | Nov 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [d653658a53](https://linux-hardware.org/?probe=d653658a53) | Oct 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [b9ab6b9cf2](https://linux-hardware.org/?probe=b9ab6b9cf2) | Oct 28, 2022 |
| Acer          | Aspire A517-52              | [1ee47a3ab6](https://linux-hardware.org/?probe=1ee47a3ab6) | Oct 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [14537f243b](https://linux-hardware.org/?probe=14537f243b) | Oct 24, 2022 |
| THUNDEROBO... | 911AirD                     | [f471a1c9db](https://linux-hardware.org/?probe=f471a1c9db) | Oct 23, 2022 |
| Acer          | Aspire A517-52              | [7515d53b5d](https://linux-hardware.org/?probe=7515d53b5d) | Oct 21, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [3fc175d4a0](https://linux-hardware.org/?probe=3fc175d4a0) | Oct 20, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [fe184c8f5b](https://linux-hardware.org/?probe=fe184c8f5b) | Oct 19, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [0db79bc085](https://linux-hardware.org/?probe=0db79bc085) | Oct 19, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [1cdde90662](https://linux-hardware.org/?probe=1cdde90662) | Oct 13, 2022 |
| Acer          | Aspire 2920                 | [c588bacc95](https://linux-hardware.org/?probe=c588bacc95) | Oct 08, 2022 |
| Acer          | Aspire 2920                 | [34b41a4e67](https://linux-hardware.org/?probe=34b41a4e67) | Oct 08, 2022 |
| ASUSTek       | X540NV                      | [31e4464fea](https://linux-hardware.org/?probe=31e4464fea) | Oct 07, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [7f8e650618](https://linux-hardware.org/?probe=7f8e650618) | Oct 06, 2022 |
| Acer          | Aspire 2920                 | [538f7a6e26](https://linux-hardware.org/?probe=538f7a6e26) | Oct 05, 2022 |
| HP            | OMEN by Laptop              | [0a8238a876](https://linux-hardware.org/?probe=0a8238a876) | Oct 05, 2022 |
| THUNDEROBO... | 911AirD                     | [69a9650652](https://linux-hardware.org/?probe=69a9650652) | Oct 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [89b48cd98e](https://linux-hardware.org/?probe=89b48cd98e) | Oct 03, 2022 |
| Digma         | EVE 11 C408                 | [b5c7ac8ed3](https://linux-hardware.org/?probe=b5c7ac8ed3) | Sep 30, 2022 |
| THUNDEROBO... | 911AirD                     | [99f1b7e253](https://linux-hardware.org/?probe=99f1b7e253) | Sep 29, 2022 |
| ICL           | RAYbook Si1512              | [0b610b66a9](https://linux-hardware.org/?probe=0b610b66a9) | Sep 20, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [713797403a](https://linux-hardware.org/?probe=713797403a) | Sep 09, 2022 |
| IP3 Techno... | ACN30                       | [af9694cea8](https://linux-hardware.org/?probe=af9694cea8) | Sep 06, 2022 |
| IP3 Techno... | ACN30                       | [03f14a115d](https://linux-hardware.org/?probe=03f14a115d) | Sep 05, 2022 |
| MSI           | FX610                       | [a822818a58](https://linux-hardware.org/?probe=a822818a58) | Sep 03, 2022 |
| IP3 Techno... | ACN30                       | [e25ed534c0](https://linux-hardware.org/?probe=e25ed534c0) | Aug 18, 2022 |
| ICL           | RAYbook Si1512              | [a42c4dc65a](https://linux-hardware.org/?probe=a42c4dc65a) | Aug 09, 2022 |
| Digma         | EVE 15 P417 ES5063EW        | [a584c678b5](https://linux-hardware.org/?probe=a584c678b5) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | [4fd01756b2](https://linux-hardware.org/?probe=4fd01756b2) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | [008b02cc92](https://linux-hardware.org/?probe=008b02cc92) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | [413949a727](https://linux-hardware.org/?probe=413949a727) | Jul 25, 2022 |
| Lenovo        | V15-IWL 81YE                | [3bfcedd5c8](https://linux-hardware.org/?probe=3bfcedd5c8) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [c49282206c](https://linux-hardware.org/?probe=c49282206c) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [d598c4587d](https://linux-hardware.org/?probe=d598c4587d) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [5b1e962751](https://linux-hardware.org/?probe=5b1e962751) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [4e120b3b63](https://linux-hardware.org/?probe=4e120b3b63) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [2d5bedf224](https://linux-hardware.org/?probe=2d5bedf224) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [297ce5144e](https://linux-hardware.org/?probe=297ce5144e) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [84b7cd1115](https://linux-hardware.org/?probe=84b7cd1115) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [a92b6c5d73](https://linux-hardware.org/?probe=a92b6c5d73) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [51ebd271c8](https://linux-hardware.org/?probe=51ebd271c8) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [44ad7f7d47](https://linux-hardware.org/?probe=44ad7f7d47) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [49068a26b5](https://linux-hardware.org/?probe=49068a26b5) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [62ce596bf3](https://linux-hardware.org/?probe=62ce596bf3) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [812db8ad6f](https://linux-hardware.org/?probe=812db8ad6f) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [d4c2b5ffad](https://linux-hardware.org/?probe=d4c2b5ffad) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [4c0179b60e](https://linux-hardware.org/?probe=4c0179b60e) | Jul 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [8601888983](https://linux-hardware.org/?probe=8601888983) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | [1d505390d6](https://linux-hardware.org/?probe=1d505390d6) | Jul 22, 2022 |
| HONOR         | NBR-WAX9                    | [5b3340311a](https://linux-hardware.org/?probe=5b3340311a) | Jul 20, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | [154c254eac](https://linux-hardware.org/?probe=154c254eac) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | [60921a7ff6](https://linux-hardware.org/?probe=60921a7ff6) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | [c24f8b4ba6](https://linux-hardware.org/?probe=c24f8b4ba6) | Jul 19, 2022 |
| HONOR         | NBR-WAX9                    | [fe971bb8c3](https://linux-hardware.org/?probe=fe971bb8c3) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | [2835672840](https://linux-hardware.org/?probe=2835672840) | Jul 07, 2022 |
| Kraftway      | ACCORD                      | [24e49bc011](https://linux-hardware.org/?probe=24e49bc011) | Jun 27, 2022 |
| Kraftway      | ACCORD                      | [39e3c55e89](https://linux-hardware.org/?probe=39e3c55e89) | Jun 27, 2022 |
| Aquarius      | NS685U                      | [ecedc7cbb6](https://linux-hardware.org/?probe=ecedc7cbb6) | Jun 08, 2022 |
| ICL           | Unknown                     | [4dc89fc689](https://linux-hardware.org/?probe=4dc89fc689) | Jun 07, 2022 |
| mtech         | MTL1578                     | [bf25c26ea0](https://linux-hardware.org/?probe=bf25c26ea0) | May 11, 2022 |
| HUAWEI        | BOD-WXX9                    | [e2e025dd4f](https://linux-hardware.org/?probe=e2e025dd4f) | Apr 15, 2022 |
| Acer          | TravelMate P215-53          | [124fdb3b64](https://linux-hardware.org/?probe=124fdb3b64) | Apr 14, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | [be41efbec8](https://linux-hardware.org/?probe=be41efbec8) | Apr 05, 2022 |
| Aquarius      | NS585 R32                   | [582389ca98](https://linux-hardware.org/?probe=582389ca98) | Mar 24, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | [56f9ebba91](https://linux-hardware.org/?probe=56f9ebba91) | Mar 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | [e18b80073c](https://linux-hardware.org/?probe=e18b80073c) | Mar 21, 2022 |
| 3Logic Gro... | APM Graviton A15i-K2        | [e93bcf2f42](https://linux-hardware.org/?probe=e93bcf2f42) | Mar 09, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [227a2658d0](https://linux-hardware.org/?probe=227a2658d0) | Feb 15, 2022 |
| HP            | Laptop 15s-eq1xxx           | [7ed7e139d8](https://linux-hardware.org/?probe=7ed7e139d8) | Dec 20, 2021 |
| HP            | Laptop 15s-eq1xxx           | [55ab1c9ab8](https://linux-hardware.org/?probe=55ab1c9ab8) | Dec 20, 2021 |
| HUAWEI        | NBLK-WAX9X                  | [5bb21d6bf6](https://linux-hardware.org/?probe=5bb21d6bf6) | Dec 13, 2021 |
| ICL           | RAYbook Si1514              | [9ddc61deba](https://linux-hardware.org/?probe=9ddc61deba) | Sep 13, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [4f59992d0f](https://linux-hardware.org/?probe=4f59992d0f) | Sep 11, 2021 |
| HP            | Laptop 15-dw3xxx            | [d8b35044ab](https://linux-hardware.org/?probe=d8b35044ab) | Jul 29, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | [9b2c758081](https://linux-hardware.org/?probe=9b2c758081) | Jun 10, 2021 |
| ASUSTek       | X75VD                       | [95ea9551da](https://linux-hardware.org/?probe=95ea9551da) | Apr 05, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [916d4b225b](https://linux-hardware.org/?probe=916d4b225b) | Mar 30, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | [ebfafc7409](https://linux-hardware.org/?probe=ebfafc7409) | Mar 26, 2021 |
| HUAWEI        | BOHL-WXX9                   | [cf5559d576](https://linux-hardware.org/?probe=cf5559d576) | Mar 26, 2021 |
| HP            | Pavilion g6                 | [1ca79b1950](https://linux-hardware.org/?probe=1ca79b1950) | Mar 26, 2021 |
| Pegatron      | A35                         | [9923a21e8c](https://linux-hardware.org/?probe=9923a21e8c) | Mar 04, 2021 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| Red OS 7.3.1 | 45        | 33.33%  |
| Red OS 7.3   | 45        | 33.33%  |
| Red OS 7.3.2 | 41        | 30.37%  |
| Red OS 8.0   | 3         | 2.22%   |
| Red OS 7.2   | 1         | 0.74%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Red OS | 127       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64    | 25        | 17.61%  |
| 5.15.72-1.el7.3.x86_64  | 23        | 16.2%   |
| 5.15.87-1.el7.3.x86_64  | 14        | 9.86%   |
| 6.1.52-1.el7.3.x86_64   | 13        | 9.15%   |
| 5.15.35-4.el7.3.x86_64  | 10        | 7.04%   |
| 5.10.29-1.el7.x86_64    | 10        | 7.04%   |
| 5.15.35-1.el7.3.x86_64  | 6         | 4.23%   |
| 6.1.20-2.el7.3.x86_64   | 4         | 2.82%   |
| 5.15.35-5.el7.3.x86_64  | 4         | 2.82%   |
| 6.1.44-1.el7.3.x86_64   | 3         | 2.11%   |
| 6.1.38-2.el7.3.x86_64   | 3         | 2.11%   |
| 5.15.78-2.el7.3.x86_64  | 3         | 2.11%   |
| 5.15.125-1.el7.3.x86_64 | 3         | 2.11%   |
| 5.10.1-1.el7.x86_64     | 3         | 2.11%   |
| 6.6.6-1.red80.x86_64    | 2         | 1.41%   |
| 5.15.131-1.el7.3.x86_64 | 2         | 1.41%   |
| 5.15.10-4.el7.x86_64    | 2         | 1.41%   |
| 5.10.29-3.el7.x86_64    | 2         | 1.41%   |
| 5.10.24-2.el7.x86_64    | 2         | 1.41%   |
| 6.1.52-1.red80.x86_64   | 1         | 0.7%    |
| 5.18.1-1.el7.x86_64     | 1         | 0.7%    |
| 5.15.120                | 1         | 0.7%    |
| 5.15.10-3.el7.x86_64    | 1         | 0.7%    |
| 5.15.10-2.el7.x86_64    | 1         | 0.7%    |
| 5.13.15-1.el7.x86_64    | 1         | 0.7%    |
| 5.10.24-1.el7.x86_64    | 1         | 0.7%    |
| 4.19.79-1.el7.x86_64    | 1         | 0.7%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.10  | 29        | 20.57%  |
| 5.15.72  | 23        | 16.31%  |
| 5.15.35  | 19        | 13.48%  |
| 6.1.52   | 14        | 9.93%   |
| 5.15.87  | 14        | 9.93%   |
| 5.10.29  | 12        | 8.51%   |
| 6.1.20   | 4         | 2.84%   |
| 6.1.44   | 3         | 2.13%   |
| 6.1.38   | 3         | 2.13%   |
| 5.15.78  | 3         | 2.13%   |
| 5.15.125 | 3         | 2.13%   |
| 5.10.24  | 3         | 2.13%   |
| 5.10.1   | 3         | 2.13%   |
| 6.6.6    | 2         | 1.42%   |
| 5.15.131 | 2         | 1.42%   |
| 5.18.1   | 1         | 0.71%   |
| 5.15.120 | 1         | 0.71%   |
| 5.13.15  | 1         | 0.71%   |
| 4.19.79  | 1         | 0.71%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 88        | 66.17%  |
| 6.1     | 23        | 17.29%  |
| 5.10    | 17        | 12.78%  |
| 6.6     | 2         | 1.5%    |
| 5.18    | 1         | 0.75%   |
| 5.13    | 1         | 0.75%   |
| 4.19    | 1         | 0.75%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 127       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 110       | 85.27%  |
| Cinnamon   | 13        | 10.08%  |
| X-Cinnamon | 3         | 2.33%   |
| GNOME      | 2         | 1.55%   |
| KDE5       | 1         | 0.78%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 123       | 95.35%  |
| Wayland | 6         | 4.65%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 119       | 91.54%  |
| SDDM    | 5         | 3.85%   |
| LightDM | 3         | 2.31%   |
| Unknown | 3         | 2.31%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 54.2%   |
| ru_RU   | 58        | 44.27%  |
| en_US   | 1         | 0.76%   |
| en_GB   | 1         | 0.76%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 109       | 84.5%   |
| BIOS | 20        | 15.5%   |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 124       | 96.88%  |
| Btrfs   | 2         | 1.56%   |
| Xfs     | 1         | 0.78%   |
| Overlay | 1         | 0.78%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 108       | 84.38%  |
| MBR     | 17        | 13.28%  |
| Unknown | 3         | 2.34%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 116       | 89.92%  |
| Yes       | 13        | 10.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 97        | 74.62%  |
| Yes       | 33        | 25.38%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 46        | 36.22%  |
| Hewlett-Packard                | 18        | 14.17%  |
| ICL                            | 7         | 5.51%   |
| HUAWEI                         | 6         | 4.72%   |
| Acer                           | 6         | 4.72%   |
| MSI                            | 5         | 3.94%   |
| Dell                           | 5         | 3.94%   |
| ASUSTek Computer               | 5         | 3.94%   |
| Aquarius                       | 4         | 3.15%   |
| Kraftway                       | 3         | 2.36%   |
| Digma                          | 3         | 2.36%   |
| iRU                            | 2         | 1.57%   |
| IP3 Technology                 | 2         | 1.57%   |
| HONOR                          | 2         | 1.57%   |
| Graviton                       | 2         | 1.57%   |
| Gigabyte Technology            | 2         | 1.57%   |
| 3Logic Group                   | 2         | 1.57%   |
| Timi                           | 1         | 0.79%   |
| THUNDEROBOT                    | 1         | 0.79%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.79%   |
| Pegatron                       | 1         | 0.79%   |
| mtech                          | 1         | 0.79%   |
| KVADRA                         | 1         | 0.79%   |
| Unknown                        | 1         | 0.79%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE                  | 17        | 13.39%  |
| Lenovo ThinkBook 15 G3 ACL 21A4      | 3         | 2.36%   |
| Kraftway ACCORD                      | 3         | 2.36%   |
| ICL RAYbook Si1512                   | 3         | 2.36%   |
| HP Laptop 15s-eq1xxx                 | 3         | 2.36%   |
| Unknown                              | 3         | 2.36%   |
| Lenovo IdeaPad L340-15API 81LW       | 2         | 1.57%   |
| iRU 15ALC                            | 2         | 1.57%   |
| IP3 ACN30                            | 2         | 1.57%   |
| Acer Aspire A315-24P                 | 2         | 1.57%   |
| Timi Redmi Book Pro 15 2022          | 1         | 0.79%   |
| THUNDEROBOT 911AirD                  | 1         | 0.79%   |
| Shanghai Zhaoxin ZXE CRB             | 1         | 0.79%   |
| Pegatron A35                         | 1         | 0.79%   |
| mtech MTL1578                        | 1         | 0.79%   |
| MSI Sword 15 A12UE                   | 1         | 0.79%   |
| MSI Modern 15 B12M                   | 1         | 0.79%   |
| MSI Modern 14 C12M                   | 1         | 0.79%   |
| MSI GL62 6QF                         | 1         | 0.79%   |
| MSI FX610                            | 1         | 0.79%   |
| Lenovo V15 G2 ALC 82KD               | 1         | 0.79%   |
| Lenovo V15 G1 IML 82NB               | 1         | 0.79%   |
| Lenovo V130-15IKB 81HN               | 1         | 0.79%   |
| Lenovo ThinkPad X230 23245C8         | 1         | 0.79%   |
| Lenovo ThinkPad X220 4290RB3         | 1         | 0.79%   |
| Lenovo ThinkPad T61 6464WM6          | 1         | 0.79%   |
| Lenovo ThinkPad T460s 20FAS1TQ02     | 1         | 0.79%   |
| Lenovo ThinkPad T430 23493V2         | 1         | 0.79%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2DE00 | 1         | 0.79%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2DD00 | 1         | 0.79%   |
| Lenovo ThinkPad E15 Gen 4 21E6009UGP | 1         | 0.79%   |
| Lenovo ThinkPad E15 Gen 4 21E60061RT | 1         | 0.79%   |
| Lenovo ThinkBook 15 G2 ITL 20VE      | 1         | 0.79%   |
| Lenovo ThinkBook 15 G2 ARE 20VG      | 1         | 0.79%   |
| Lenovo ThinkBook 14-IIL 20SL         | 1         | 0.79%   |
| Lenovo IdeaPad L340-15IWL 81LG       | 1         | 0.79%   |
| Lenovo IdeaPad 700-15ISK 80RU        | 1         | 0.79%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7     | 1         | 0.79%   |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 1         | 0.79%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 0.79%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo V15-IWL       | 17        | 13.39%  |
| Lenovo ThinkPad      | 9         | 7.09%   |
| Lenovo IdeaPad       | 9         | 7.09%   |
| Lenovo ThinkBook     | 6         | 4.72%   |
| HP Laptop            | 6         | 4.72%   |
| ICL RAYbook          | 4         | 3.15%   |
| Acer Aspire          | 4         | 3.15%   |
| Kraftway ACCORD      | 3         | 2.36%   |
| HP ProBook           | 3         | 2.36%   |
| HP Pavilion          | 3         | 2.36%   |
| Digma EVE            | 3         | 2.36%   |
| Dell Vostro          | 3         | 2.36%   |
| Unknown              | 3         | 2.36%   |
| MSI Modern           | 2         | 1.57%   |
| Lenovo V15           | 2         | 1.57%   |
| iRU 15ALC            | 2         | 1.57%   |
| IP3 ACN30            | 2         | 1.57%   |
| HP EliteBook         | 2         | 1.57%   |
| Gigabyte G5          | 2         | 1.57%   |
| Aquarius NS685U      | 2         | 1.57%   |
| Timi Redmi           | 1         | 0.79%   |
| THUNDEROBOT 911AirD  | 1         | 0.79%   |
| Shanghai Zhaoxin ZXE | 1         | 0.79%   |
| Pegatron A35         | 1         | 0.79%   |
| mtech MTL1578        | 1         | 0.79%   |
| MSI Sword            | 1         | 0.79%   |
| MSI GL62             | 1         | 0.79%   |
| MSI FX610            | 1         | 0.79%   |
| Lenovo V130-15IKB    | 1         | 0.79%   |
| Lenovo G570          | 1         | 0.79%   |
| Lenovo B590          | 1         | 0.79%   |
| KVADRA NAU           | 1         | 0.79%   |
| ICL Si1407           | 1         | 0.79%   |
| ICL S1511            | 1         | 0.79%   |
| HUAWEI NDZ-WXX9      | 1         | 0.79%   |
| HUAWEI NBLK-WAX9X    | 1         | 0.79%   |
| HUAWEI NBD-WXX9      | 1         | 0.79%   |
| HUAWEI BOHL-WXX9     | 1         | 0.79%   |
| HUAWEI BOD-WXX9      | 1         | 0.79%   |
| HUAWEI BDZ-WXX9      | 1         | 0.79%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 32        | 25.2%   |
| 2021 | 24        | 18.9%   |
| 2022 | 22        | 17.32%  |
| 2020 | 15        | 11.81%  |
| 2012 | 9         | 7.09%   |
| 2010 | 5         | 3.94%   |
| 2011 | 4         | 3.15%   |
| 2017 | 3         | 2.36%   |
| 2023 | 2         | 1.57%   |
| 2018 | 2         | 1.57%   |
| 2016 | 2         | 1.57%   |
| 2008 | 2         | 1.57%   |
| 2007 | 2         | 1.57%   |
| 2015 | 1         | 0.79%   |
| 2014 | 1         | 0.79%   |
| 2013 | 1         | 0.79%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 127       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 127       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 127       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 73        | 57.03%  |
| 16.01-24.0 | 20        | 15.63%  |
| 3.01-4.0   | 17        | 13.28%  |
| 8.01-16.0  | 14        | 10.94%  |
| 32.01-64.0 | 2         | 1.56%   |
| 2.01-3.0   | 2         | 1.56%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 79        | 58.52%  |
| 2.01-3.0  | 33        | 24.44%  |
| 0.51-1.0  | 9         | 6.67%   |
| 3.01-4.0  | 7         | 5.19%   |
| 4.01-8.0  | 5         | 3.7%    |
| 8.01-16.0 | 2         | 1.48%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 112       | 86.15%  |
| 2      | 13        | 10%     |
| 3      | 4         | 3.08%   |
| 4      | 1         | 0.77%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 106       | 82.81%  |
| Yes       | 22        | 17.19%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 94        | 74.02%  |
| No        | 33        | 25.98%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 98.43%  |
| No        | 2         | 1.57%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 109       | 85.83%  |
| No        | 18        | 14.17%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 125       | 98.43%  |
| Ukraine | 1         | 0.79%   |
| Germany | 1         | 0.79%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 32        | 24.24%  |
| Salekhard        | 22        | 16.67%  |
| Murom            | 16        | 12.12%  |
| St Petersburg    | 6         | 4.55%   |
| Perm             | 4         | 3.03%   |
| Yekaterinburg    | 3         | 2.27%   |
| Yakutsk          | 3         | 2.27%   |
| Vladimir         | 3         | 2.27%   |
| Ryazan           | 3         | 2.27%   |
| Novy Urengoy     | 3         | 2.27%   |
| Krasnodar        | 3         | 2.27%   |
| Saransk          | 2         | 1.52%   |
| Orenburg         | 2         | 1.52%   |
| Nizhniy Novgorod | 2         | 1.52%   |
| Kursk            | 2         | 1.52%   |
| Krasnoyarsk      | 2         | 1.52%   |
| Yaroslavl        | 1         | 0.76%   |
| Volzhskiy        | 1         | 0.76%   |
| Vladivostok      | 1         | 0.76%   |
| Ulyanovsk        | 1         | 0.76%   |
| Tver             | 1         | 0.76%   |
| Strezhevoy       | 1         | 0.76%   |
| Sevastopol       | 1         | 0.76%   |
| Saratov          | 1         | 0.76%   |
| Samara           | 1         | 0.76%   |
| Pushkino         | 1         | 0.76%   |
| Omsk             | 1         | 0.76%   |
| Novosibirsk      | 1         | 0.76%   |
| Novokuybyshevsk  | 1         | 0.76%   |
| Nadym            | 1         | 0.76%   |
| Muromskiy        | 1         | 0.76%   |
| Kropp            | 1         | 0.76%   |
| Kotel'niki       | 1         | 0.76%   |
| Kirzhach         | 1         | 0.76%   |
| Khabarovsk       | 1         | 0.76%   |
| Kaluga           | 1         | 0.76%   |
| Giaginskaya      | 1         | 0.76%   |
| Borinskoye       | 1         | 0.76%   |
| Belgorod         | 1         | 0.76%   |
| Balashikha       | 1         | 0.76%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 31        | 47     | 21.38%  |
| WDC                 | 18        | 25     | 12.41%  |
| SK hynix            | 11        | 13     | 7.59%   |
| A-DATA Technology   | 8         | 8      | 5.52%   |
| Seagate             | 7         | 9      | 4.83%   |
| Toshiba             | 5         | 28     | 3.45%   |
| SanDisk             | 5         | 5      | 3.45%   |
| Micron Technology   | 5         | 10     | 3.45%   |
| HGST                | 5         | 5      | 3.45%   |
| Foxline             | 5         | 5      | 3.45%   |
| Unknown             | 4         | 4      | 2.76%   |
| Silicon Motion      | 4         | 4      | 2.76%   |
| Intel               | 4         | 4      | 2.76%   |
| YMTC                | 3         | 3      | 2.07%   |
| Phison              | 3         | 3      | 2.07%   |
| Gigabyte Technology | 3         | 3      | 2.07%   |
| China               | 3         | 7      | 2.07%   |
| UMIS                | 2         | 2      | 1.38%   |
| KIOXIA              | 2         | 2      | 1.38%   |
| Kingston            | 2         | 2      | 1.38%   |
| Crucial             | 2         | 2      | 1.38%   |
| Transcend           | 1         | 1      | 0.69%   |
| Thinkplus           | 1         | 1      | 0.69%   |
| SPCC Sol            | 1         | 1      | 0.69%   |
| Netac               | 1         | 1      | 0.69%   |
| Lenovo              | 1         | 1      | 0.69%   |
| KingSpec            | 1         | 1      | 0.69%   |
| Kimtigo             | 1         | 2      | 0.69%   |
| JMicron Technology  | 1         | 1      | 0.69%   |
| ITHOO               | 1         | 1      | 0.69%   |
| HUAWEI              | 1         | 1      | 0.69%   |
| Hikvision           | 1         | 1      | 0.69%   |
| Apacer              | 1         | 2      | 0.69%   |
| Unknown             | 1         | 1      | 0.69%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB       | 18        | 12.16%  |
| Foxline FLSSD256M80E13TCX5 256GB       | 5         | 3.38%   |
| Silicon Motion Wodposit NVMe SSD 256GB | 4         | 2.7%    |
| Samsung MZALQ512HALU-000L2 512GB       | 3         | 2.03%   |
| YMTC PC005 512GB                       | 2         | 1.35%   |
| WDC WD10SPZX-24Z10 1TB                 | 2         | 1.35%   |
| WDC WD10SPZX-00Z10T0 1TB               | 2         | 1.35%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB   | 2         | 1.35%   |
| Unknown NVMe SSD Drive 512GB           | 2         | 1.35%   |
| Toshiba MQ01ABF050 500GB               | 2         | 1.35%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB | 2         | 1.35%   |
| SK hynix PC711 HFS512GDE9X073N 512GB   | 2         | 1.35%   |
| Seagate ST1000LM035-1RK172 1TB         | 2         | 1.35%   |
| SanDisk NVMe SSD Drive 512GB           | 2         | 1.35%   |
| Samsung MZALQ256HBJD-00BL2 256GB       | 2         | 1.35%   |
| KIOXIA KBG40ZNS256G NVMe 256GB         | 2         | 1.35%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB       | 2         | 1.35%   |
| A-DATA SX6000PNP 512GB                 | 2         | 1.35%   |
| A-DATA SU650 240GB SSD                 | 2         | 1.35%   |
| YMTC PC210-512GB-B                     | 1         | 0.68%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 1         | 0.68%   |
| WDC WDS250G2B0A-00SM50 250GB SSD       | 1         | 0.68%   |
| WDC WD5000BPVT-55HXZT3 500GB           | 1         | 0.68%   |
| WDC WD3200BPVT-24JJ5T0 320GB           | 1         | 0.68%   |
| WDC WD3200BEVT-60ZCT1 320GB            | 1         | 0.68%   |
| WDC WD2500BEVT-22ZCT0 250GB            | 1         | 0.68%   |
| WDC WD10JPVX-22JC3T0 1TB               | 1         | 0.68%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB   | 1         | 0.68%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB   | 1         | 0.68%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB   | 1         | 0.68%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 1         | 0.68%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB   | 1         | 0.68%   |
| Unknown SLD128  128GB                  | 1         | 0.68%   |
| Unknown 58K722  128GB                  | 1         | 0.68%   |
| UMIS RPJTJ512MEE1OWX 512GB             | 1         | 0.68%   |
| UMIS RPJTJ256MGE1QDQ 256GB             | 1         | 0.68%   |
| Transcend TS240GMTS820S 240GB SSD      | 1         | 0.68%   |
| Toshiba MK5075GSX 500GB                | 1         | 0.68%   |
| Toshiba MK5059GSXP 500GB               | 1         | 0.68%   |
| Toshiba KXG60ZNV512G 512GB             | 1         | 0.68%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| WDC                | 9         | 16     | 36%     |
| Seagate            | 7         | 9      | 28%     |
| HGST               | 5         | 5      | 20%     |
| Toshiba            | 3         | 25     | 12%     |
| JMicron Technology | 1         | 1      | 4%      |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 4         | 4      | 15.38%  |
| A-DATA Technology   | 4         | 4      | 15.38%  |
| China               | 3         | 7      | 11.54%  |
| WDC                 | 2         | 2      | 7.69%   |
| SanDisk             | 2         | 2      | 7.69%   |
| Crucial             | 2         | 2      | 7.69%   |
| Transcend           | 1         | 1      | 3.85%   |
| Thinkplus           | 1         | 1      | 3.85%   |
| SPCC Sol            | 1         | 1      | 3.85%   |
| Netac               | 1         | 1      | 3.85%   |
| Micron Technology   | 1         | 1      | 3.85%   |
| Lenovo              | 1         | 1      | 3.85%   |
| Kingston            | 1         | 1      | 3.85%   |
| KingSpec            | 1         | 1      | 3.85%   |
| Apacer              | 1         | 2      | 3.85%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 88        | 114    | 62.41%  |
| SSD     | 25        | 31     | 17.73%  |
| HDD     | 23        | 56     | 16.31%  |
| MMC     | 3         | 3      | 2.13%   |
| Unknown | 2         | 2      | 1.42%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 88        | 114    | 64.23%  |
| SATA | 43        | 84     | 31.39%  |
| SAS  | 3         | 5      | 2.19%   |
| MMC  | 3         | 3      | 2.19%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 34        | 60     | 70.83%  |
| 0.51-1.0   | 13        | 26     | 27.08%  |
| 1.01-2.0   | 1         | 1      | 2.08%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 66        | 50%     |
| 251-500    | 35        | 26.52%  |
| 501-1000   | 13        | 9.85%   |
| 51-100     | 8         | 6.06%   |
| 1001-2000  | 6         | 4.55%   |
| 1-20       | 3         | 2.27%   |
| 21-50      | 1         | 0.76%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 92        | 68.66%  |
| 21-50     | 24        | 17.91%  |
| 101-250   | 6         | 4.48%   |
| 51-100    | 5         | 3.73%   |
| 501-1000  | 4         | 2.99%   |
| 251-500   | 2         | 1.49%   |
| 1001-2000 | 1         | 0.75%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 11.11%  |
| Toshiba MQ01ABF050 500GB            | 1         | 14     | 11.11%  |
| Toshiba MK5075GSX 500GB             | 1         | 8      | 11.11%  |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 11.11%  |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 11.11%  |
| Seagate ST500LT012-1DG142 500GB     | 1         | 1      | 11.11%  |
| Kingston SUV400S37120G 120GB SSD    | 1         | 1      | 11.11%  |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 11.11%  |
| A-DATA Technology SU800 256GB SSD   | 1         | 1      | 11.11%  |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Notebooks | Drives | Percent |
|-------------------|-----------|--------|---------|
| Toshiba           | 2         | 23     | 25%     |
| Seagate           | 2         | 2      | 25%     |
| WDC               | 1         | 1      | 12.5%   |
| Kingston          | 1         | 1      | 12.5%   |
| HGST              | 1         | 1      | 12.5%   |
| A-DATA Technology | 1         | 1      | 12.5%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Toshiba | 2         | 23     | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 27     | 75%     |
| SSD  | 2         | 2      | 25%     |

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
| Works    | 112       | 158    | 84.21%  |
| Detected | 13        | 19     | 9.77%   |
| Malfunc  | 8         | 29     | 6.02%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 85        | 45.21%  |
| Samsung Electronics          | 27        | 14.36%  |
| AMD                          | 17        | 9.04%   |
| SK hynix                     | 11        | 5.85%   |
| Phison Electronics           | 11        | 5.85%   |
| Sandisk                      | 10        | 5.32%   |
| Silicon Motion               | 4         | 2.13%   |
| Micron Technology            | 4         | 2.13%   |
| Yangtze Memory Technologies  | 3         | 1.6%    |
| MAXIO Technology (Hangzhou)  | 3         | 1.6%    |
| ADATA Technology             | 3         | 1.6%    |
| Union Memory (Shenzhen)      | 2         | 1.06%   |
| Toshiba America Info Systems | 2         | 1.06%   |
| KIOXIA                       | 2         | 1.06%   |
| Zhaoxin                      | 1         | 0.53%   |
| ShenZhen TIGO Semiconductor  | 1         | 0.53%   |
| Realtek Semiconductor        | 1         | 0.53%   |
| Kingston Technology Company  | 1         | 0.53%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                  | Notebooks | Percent |
|----------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                      | 30        | 15%     |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                            | 26        | 13%     |
| AMD FCH SATA Controller [AHCI mode]                                                    | 14        | 7%      |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                                    | 9         | 4.5%    |
| Intel Volume Management Device NVMe RAID Controller                                    | 8         | 4%      |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                   | 7         | 3.5%    |
| Intel Tiger Lake-LP SATA Controller                                                    | 7         | 3.5%    |
| Intel Alder Lake-P SATA AHCI Controller                                                | 6         | 3%      |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                       | 6         | 3%      |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                              | 5         | 2.5%    |
| Intel Comet Lake SATA AHCI Controller                                                  | 5         | 2.5%    |
| SK hynix BC511 NVMe SSD                                                                | 4         | 2%      |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                      | 4         | 2%      |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202 (DRAM-less)                               | 3         | 1.5%    |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                                  | 3         | 1.5%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller               | 3         | 1.5%    |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                           | 3         | 1.5%    |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller           | 3         | 1.5%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                      | 3         | 1.5%    |
| ADATA XPG GAMMIXS1 1L, XPG GAMMIX S5, LEGEND 710 / 740, SWORDFISH NVMe SSD (DRAM-less) | 3         | 1.5%    |
| Yangtze Memory PC005 NVMe SSD                                                          | 2         | 1%      |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                   | 2         | 1%      |
| SanDisk WD Black SN770 / PC SN740 256GB / PC SN560 (DRAM-less) NVMe SSD                | 2         | 1%      |
| Phison E16 PCIe4 NVMe Controller                                                       | 2         | 1%      |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                            | 2         | 1%      |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                             | 2         | 1%      |
| Intel Tiger Lake SATA AHCI Controller                                                  | 2         | 1%      |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                     | 2         | 1%      |
| Intel SSD 660P Series                                                                  | 2         | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                          | 2         | 1%      |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                       | 2         | 1%      |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                   | 2         | 1%      |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G/KH-40000/KX-7000 StorX AHCI Controller          | 1         | 0.5%    |
| Yangtze Memory PC210 NVMe SSD                                                          | 1         | 0.5%    |
| Union Memory (Shenzhen) AM630 PCIe 4.0 NVMe SSD 256GB                                  | 1         | 0.5%    |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                                  | 1         | 0.5%    |
| ShenZhen TIGO kimtigo NVMe SSD (DRAM-less)                                             | 1         | 0.5%    |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                                         | 1         | 0.5%    |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                                  | 1         | 0.5%    |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                                  | 1         | 0.5%    |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 95        | 48.22%  |
| NVMe | 88        | 44.67%  |
| RAID | 9         | 4.57%   |
| IDE  | 5         | 2.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 96        | 75.59%  |
| AMD          | 30        | 23.62%  |
| CentaurHauls | 1         | 0.79%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 14.17%  |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 5.51%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 6         | 4.72%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 5         | 3.94%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 3.15%   |
| Intel 12th Gen Core i5-1235U                  | 4         | 3.15%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 3.15%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 4         | 3.15%   |
| Intel 12th Gen Core i5-12500H                 | 3         | 2.36%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 2.36%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 2.36%   |
| AMD Ryzen 3 5400U with Radeon Graphics        | 3         | 2.36%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 3         | 2.36%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.57%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 1.57%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.57%   |
| Intel 12th Gen Core i7-1255U                  | 2         | 1.57%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.57%   |
| AMD Ryzen 5 7520U with Radeon Graphics        | 2         | 1.57%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.57%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.79%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.79%   |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 0.79%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.79%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.79%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.79%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 0.79%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.79%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 0.79%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.79%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.79%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 1         | 0.79%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.79%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 0.79%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 0.79%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 0.79%   |
| Intel Core i3-9300 CPU @ 3.70GHz              | 1         | 0.79%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 0.79%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 0.79%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 0.79%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 46        | 36.22%  |
| Other                          | 30        | 23.62%  |
| AMD Ryzen 5                    | 12        | 9.45%   |
| AMD Ryzen 3                    | 12        | 9.45%   |
| Intel Core i3                  | 11        | 8.66%   |
| Intel Celeron                  | 3         | 2.36%   |
| Intel Pentium                  | 2         | 1.57%   |
| Intel Core i7                  | 2         | 1.57%   |
| Intel Core 2 Duo               | 2         | 1.57%   |
| AMD Ryzen 7                    | 2         | 1.57%   |
| AMD Phenom II                  | 2         | 1.57%   |
| Intel Pentium Gold             | 1         | 0.79%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.79%   |
| AMD A4                         | 1         | 0.79%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 70        | 55.12%  |
| 2      | 33        | 25.98%  |
| 6      | 10        | 7.87%   |
| 10     | 6         | 4.72%   |
| 12     | 5         | 3.94%   |
| 14     | 1         | 0.79%   |
| 8      | 1         | 0.79%   |
| 3      | 1         | 0.79%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 127       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 106       | 83.46%  |
| 1      | 21        | 16.54%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 127       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 24        | 18.6%   |
| 0x806c1    | 15        | 11.63%  |
| 0x806ea    | 12        | 9.3%    |
| 0x906a4    | 7         | 5.43%   |
| 0x08608103 | 7         | 5.43%   |
| 0x906a3    | 6         | 4.65%   |
| 0x306a9    | 6         | 4.65%   |
| 0x206a7    | 5         | 3.88%   |
| 0x08600106 | 5         | 3.88%   |
| 0x0a50000c | 4         | 3.1%    |
| 0x40651    | 3         | 2.33%   |
| 0x08108102 | 3         | 2.33%   |
| Unknown    | 3         | 2.33%   |
| 0x806d1    | 2         | 1.55%   |
| 0x506e3    | 2         | 1.55%   |
| 0x506ca    | 2         | 1.55%   |
| 0x08a00006 | 2         | 1.55%   |
| 0x08108109 | 2         | 1.55%   |
| 0x010000c8 | 2         | 1.55%   |
| 0xa0660    | 1         | 0.78%   |
| 0x906eb    | 1         | 0.78%   |
| 0x906e9    | 1         | 0.78%   |
| 0x706e5    | 1         | 0.78%   |
| 0x6fa      | 1         | 0.78%   |
| 0x506c9    | 1         | 0.78%   |
| 0x406e3    | 1         | 0.78%   |
| 0x406c4    | 1         | 0.78%   |
| 0x20655    | 1         | 0.78%   |
| 0x20652    | 1         | 0.78%   |
| 0x10676    | 1         | 0.78%   |
| 0x0a50000d | 1         | 0.78%   |
| 0x0a404101 | 1         | 0.78%   |
| 0x08600104 | 1         | 0.78%   |
| 0x0810100b | 1         | 0.78%   |
| 0x06006705 | 1         | 0.78%   |
| 0x02000057 | 1         | 0.78%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 39        | 30.71%  |
| TigerLake        | 15        | 11.81%  |
| Alderlake Hybrid | 13        | 10.24%  |
| Unknown          | 11        | 8.66%   |
| Zen 2            | 6         | 4.72%   |
| IvyBridge        | 6         | 4.72%   |
| Zen+             | 5         | 3.94%   |
| SandyBridge      | 5         | 3.94%   |
| Zen 3            | 4         | 3.15%   |
| Skylake          | 3         | 2.36%   |
| IceLake          | 3         | 2.36%   |
| Haswell          | 3         | 2.36%   |
| Goldmont         | 3         | 2.36%   |
| Westmere         | 2         | 1.57%   |
| K10              | 2         | 1.57%   |
| Zen              | 1         | 0.79%   |
| Silvermont       | 1         | 0.79%   |
| Penryn           | 1         | 0.79%   |
| K8 & K10 hybrid  | 1         | 0.79%   |
| Excavator        | 1         | 0.79%   |
| Core             | 1         | 0.79%   |
| CometLake        | 1         | 0.79%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 95        | 62.91%  |
| AMD     | 34        | 22.52%  |
| Nvidia  | 21        | 13.91%  |
| Zhaoxin | 1         | 0.66%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 19        | 12.26%  |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 11        | 7.1%    |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 9         | 5.81%   |
| AMD Lucienne                                                              | 7         | 4.52%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 6         | 3.87%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 6         | 3.87%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 6         | 3.87%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 5         | 3.23%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 5         | 3.23%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 3.23%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 5         | 3.23%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 4         | 2.58%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 2.58%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 3         | 1.94%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 1.94%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                              | 3         | 1.94%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.29%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 2         | 1.29%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 2         | 1.29%   |
| Intel HD Graphics 530                                                     | 2         | 1.29%   |
| Intel HD Graphics 500                                                     | 2         | 1.29%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 1.29%   |
| AMD Mendocino                                                             | 2         | 1.29%   |
| Zhaoxin KX-6000 C-960 GPU                                                 | 1         | 0.65%   |
| Nvidia TU117M [GeForce MX550]                                             | 1         | 0.65%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.65%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 0.65%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.65%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.65%   |
| Nvidia GM108M [GeForce 920MX]                                             | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.65%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.65%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.65%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.65%   |
| Nvidia GF119M [GeForce GT 520MX]                                          | 1         | 0.65%   |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 0.65%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.65%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                         | 1         | 0.65%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 0.65%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 72        | 56.69%  |
| 1 x AMD        | 27        | 21.26%  |
| Intel + Nvidia | 19        | 14.96%  |
| Intel + AMD    | 4         | 3.15%   |
| 2 x AMD        | 2         | 1.57%   |
| 1 x Zhaoxin    | 1         | 0.79%   |
| 1 x Nvidia     | 1         | 0.79%   |
| AMD + Nvidia   | 1         | 0.79%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 114       | 88.37%  |
| Unknown     | 12        | 9.3%    |
| Proprietary | 3         | 2.33%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 81        | 61.83%  |
| 1.01-2.0   | 22        | 16.79%  |
| 0.01-0.5   | 14        | 10.69%  |
| 0.51-1.0   | 8         | 6.11%   |
| 3.01-4.0   | 6         | 4.58%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 57        | 43.51%  |
| LG Display           | 18        | 13.74%  |
| Chimei Innolux       | 15        | 11.45%  |
| Samsung Electronics  | 11        | 8.4%    |
| AU Optronics         | 8         | 6.11%   |
| PANDA                | 5         | 3.82%   |
| Philips              | 3         | 2.29%   |
| NLE                  | 2         | 1.53%   |
| Lenovo               | 2         | 1.53%   |
| Acer                 | 2         | 1.53%   |
| ViewSonic            | 1         | 0.76%   |
| Toshiba              | 1         | 0.76%   |
| TMX                  | 1         | 0.76%   |
| RGT                  | 1         | 0.76%   |
| Iiyama               | 1         | 0.76%   |
| HUAWEI               | 1         | 0.76%   |
| Dell                 | 1         | 0.76%   |
| Ancor Communications | 1         | 0.76%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 19        | 14.39%  |
| BOE LCD Monitor BOE09C5 1920x1080 345x194mm 15.6-inch                   | 9         | 6.82%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch        | 4         | 3.03%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 4         | 3.03%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch            | 3         | 2.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 3         | 2.27%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 2.27%   |
| BOE LCD Monitor BOE0936 1920x1080 344x194mm 15.5-inch                   | 3         | 2.27%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                   | 3         | 2.27%   |
| NLE Newline NLE0032 3840x2160 944x398mm 40.3-inch                       | 2         | 1.52%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 2         | 1.52%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                   | 2         | 1.52%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                    | 2         | 1.52%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.52%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.52%   |
| ViewSonic PJ VSC9B34 1920x1080                                          | 1         | 0.76%   |
| Toshiba LCD Monitor LCD58EB 1280x800 261x163mm 12.1-inch                | 1         | 0.76%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch                 | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC324C 1600x900 310x174mm 14.0-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC3151 1366x768 344x194mm 15.5-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch    | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 1210x680mm 54.6-inch  | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 0.76%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 890x500mm 40.2-inch   | 1         | 0.76%   |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                   | 1         | 0.76%   |
| Philips PHL 275S1 PHL094B 2560x1440 597x336mm 27.0-inch                 | 1         | 0.76%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                    | 1         | 0.76%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 1         | 0.76%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                 | 1         | 0.76%   |
| PANDA LCD Monitor NCP0065 1920x1080 309x174mm 14.0-inch                 | 1         | 0.76%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                 | 1         | 0.76%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                 | 1         | 0.76%   |
| PANDA LC116LF3L03 NCP000A 1920x1080 256x144mm 11.6-inch                 | 1         | 0.76%   |
| LG Display LCD Monitor LGDD302 1366x768 277x156mm 12.5-inch             | 1         | 0.76%   |
| LG Display LCD Monitor LGD0671 1920x1080 382x215mm 17.3-inch            | 1         | 0.76%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 93        | 75.61%  |
| 1366x768 (WXGA)    | 16        | 13.01%  |
| 3840x2160 (4K)     | 3         | 2.44%   |
| 1600x900 (HD+)     | 3         | 2.44%   |
| 1280x800 (WXGA)    | 2         | 1.63%   |
| 3440x1440          | 1         | 0.81%   |
| 3200x2000          | 1         | 0.81%   |
| 2560x1440 (QHD)    | 1         | 0.81%   |
| 2240x1400          | 1         | 0.81%   |
| 1680x1050 (WSXGA+) | 1         | 0.81%   |
| 1280x1024 (SXGA)   | 1         | 0.81%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 93        | 71.54%  |
| 14      | 8         | 6.15%   |
| 13      | 6         | 4.62%   |
| 21      | 3         | 2.31%   |
| 17      | 3         | 2.31%   |
| 12      | 3         | 2.31%   |
| 84      | 2         | 1.54%   |
| 40      | 2         | 1.54%   |
| 24      | 2         | 1.54%   |
| 54      | 1         | 0.77%   |
| 34      | 1         | 0.77%   |
| 27      | 1         | 0.77%   |
| 23      | 1         | 0.77%   |
| 22      | 1         | 0.77%   |
| 19      | 1         | 0.77%   |
| 11      | 1         | 0.77%   |
| Unknown | 1         | 0.77%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 105       | 80.77%  |
| 351-400     | 5         | 3.85%   |
| 201-300     | 5         | 3.85%   |
| 501-600     | 4         | 3.08%   |
| 401-500     | 4         | 3.08%   |
| 1501-2000   | 2         | 1.54%   |
| 901-1000    | 2         | 1.54%   |
| 701-800     | 1         | 0.77%   |
| 1001-1500   | 1         | 0.77%   |
| Unknown     | 1         | 0.77%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 111       | 92.5%   |
| 16/10 | 5         | 4.17%   |
| 21/9  | 3         | 2.5%    |
| 5/4   | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 93        | 71.54%  |
| 81-90          | 13        | 10%     |
| 201-250        | 7         | 5.38%   |
| More than 1000 | 3         | 2.31%   |
| 61-70          | 3         | 2.31%   |
| 121-130        | 3         | 2.31%   |
| 501-1000       | 2         | 1.54%   |
| 71-80          | 1         | 0.77%   |
| 51-60          | 1         | 0.77%   |
| 351-500        | 1         | 0.77%   |
| 301-350        | 1         | 0.77%   |
| 151-200        | 1         | 0.77%   |
| Unknown        | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 92        | 71.88%  |
| 101-120       | 21        | 16.41%  |
| 51-100        | 9         | 7.03%   |
| 161-240       | 3         | 2.34%   |
| More than 240 | 1         | 0.78%   |
| 1-50          | 1         | 0.78%   |
| Unknown       | 1         | 0.78%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 102       | 80.31%  |
| 0     | 13        | 10.24%  |
| 2     | 11        | 8.66%   |
| 3     | 1         | 0.79%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 87        | 43.07%  |
| Intel                 | 64        | 31.68%  |
| Broadcom              | 11        | 5.45%   |
| Xiaomi                | 10        | 4.95%   |
| Qualcomm Atheros      | 9         | 4.46%   |
| MediaTek              | 7         | 3.47%   |
| TP-Link               | 2         | 0.99%   |
| Samsung Electronics   | 2         | 0.99%   |
| Ralink                | 2         | 0.99%   |
| Huawei Technologies   | 2         | 0.99%   |
| Ralink Technology     | 1         | 0.5%    |
| Qualcomm              | 1         | 0.5%    |
| OPPO Electronics      | 1         | 0.5%    |
| OKB SAPR              | 1         | 0.5%    |
| Mercucys              | 1         | 0.5%    |
| Broadcom Limited      | 1         | 0.5%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 46        | 19.09%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter               | 26        | 10.79%  |
| Intel Wireless 7265                                                    | 12        | 4.98%   |
| Intel Alder Lake-P PCH CNVi WiFi                                       | 12        | 4.98%   |
| Intel Wi-Fi 6 AX201                                                    | 11        | 4.56%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 10        | 4.15%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 3.32%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 2.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 2.07%   |
| Intel Wireless 3165                                                    | 4         | 1.66%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                      | 4         | 1.66%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                               | 4         | 1.66%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 1.66%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller            | 3         | 1.24%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter               | 3         | 1.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter               | 3         | 1.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                    | 3         | 1.24%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 1.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter             | 3         | 1.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter          | 3         | 1.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                    | 3         | 1.24%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 0.83%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                             | 2         | 0.83%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                              | 2         | 0.83%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)         | 2         | 0.83%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter                      | 2         | 0.83%   |
| Intel Ethernet Controller I225-V                                       | 2         | 0.83%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 0.83%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 0.83%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                        | 2         | 0.83%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                           | 2         | 0.83%   |
| Broadcom BCM43228 802.11a/b/g/n                                        | 2         | 0.83%   |
| Broadcom BCM43142 802.11b/g/n                                          | 2         | 0.83%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                      | 2         | 0.83%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                                    | 1         | 0.41%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]             | 1         | 0.41%   |
| TP-Link 802.11n NIC                                                    | 1         | 0.41%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter                | 1         | 0.41%   |
| Realtek RTL8723DE Wireless Network Adapter                             | 1         | 0.41%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter                | 1         | 0.41%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 59        | 44.7%   |
| Realtek Semiconductor | 44        | 33.33%  |
| Broadcom              | 10        | 7.58%   |
| Qualcomm Atheros      | 6         | 4.55%   |
| MediaTek              | 5         | 3.79%   |
| TP-Link               | 2         | 1.52%   |
| Ralink                | 2         | 1.52%   |
| Ralink Technology     | 1         | 0.76%   |
| Qualcomm              | 1         | 0.76%   |
| Mercucys              | 1         | 0.76%   |
| Broadcom Limited      | 1         | 0.76%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 26        | 19.4%   |
| Intel Wireless 7265                                            | 12        | 8.96%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 12        | 8.96%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 8.21%   |
| Intel Wireless 3165                                            | 4         | 2.99%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 2.99%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 2.99%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 2.24%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 2.24%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.24%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 2.24%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 3         | 2.24%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 2.24%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 2.24%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 1.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.49%   |
| MediaTek Wi-Fi 6E MT7902 Wireless Network Adapter              | 2         | 1.49%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.49%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 2         | 1.49%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.49%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.49%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.49%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 0.75%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.75%   |
| TP-Link 802.11n NIC                                            | 1         | 0.75%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.75%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.75%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter        | 1         | 0.75%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.75%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.75%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.75%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.75%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.75%   |
| Mercucys 802.11n NIC                                           | 1         | 0.75%   |
| Intel Wireless 8265 / 8275                                     | 1         | 0.75%   |
| Intel Wireless 8260                                            | 1         | 0.75%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 0.75%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.75%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 0.75%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 59        | 56.73%  |
| Intel                 | 24        | 23.08%  |
| Xiaomi                | 10        | 9.62%   |
| Qualcomm Atheros      | 3         | 2.88%   |
| Samsung Electronics   | 2         | 1.92%   |
| MediaTek              | 2         | 1.92%   |
| OPPO Electronics      | 1         | 0.96%   |
| OKB SAPR              | 1         | 0.96%   |
| Huawei Technologies   | 1         | 0.96%   |
| Broadcom              | 1         | 0.96%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                  | Notebooks | Percent |
|------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8211/8411 PCI Express Gigabit Ethernet Controller | 46        | 43.4%   |
| Xiaomi Mi/Redmi series (RNDIS)                                         | 10        | 9.43%   |
| Intel Ethernet Connection (6) I219-V                                   | 8         | 7.55%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                               | 7         | 6.6%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller                  | 5         | 4.72%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                  | 4         | 3.77%   |
| Realtek RTL8152 Fast Ethernet Adapter                                  | 3         | 2.83%   |
| Samsung Galaxy series, misc. (tethering mode)                          | 2         | 1.89%   |
| Intel Ethernet Controller I225-V                                       | 2         | 1.89%   |
| Intel Ethernet Connection (16) I219-V                                  | 2         | 1.89%   |
| Intel Ethernet Connection (16) I219-LM                                 | 2         | 1.89%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                              | 1         | 0.94%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                               | 1         | 0.94%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                             | 1         | 0.94%   |
| OPPO SM8350-IDP _SN:361A1B3C                                           | 1         | 0.94%   |
| OKB SAPR Ethernet controller                                           | 1         | 0.94%   |
| MediaTek moto e22                                                      | 1         | 0.94%   |
| MediaTek File-CD Gadget                                                | 1         | 0.94%   |
| Intel Ethernet Connection I219-LM                                      | 1         | 0.94%   |
| Intel Ethernet Connection I218-LM                                      | 1         | 0.94%   |
| Intel Ethernet Connection (13) I219-V                                  | 1         | 0.94%   |
| Intel 82579V Gigabit Network Connection                                | 1         | 0.94%   |
| Intel 82577LM Gigabit Network Connection                               | 1         | 0.94%   |
| Intel 82566MM Gigabit Network Connection                               | 1         | 0.94%   |
| Huawei STG-LX1                                                         | 1         | 0.94%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express                 | 1         | 0.94%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 125       | 56.56%  |
| Ethernet | 95        | 42.99%  |
| Modem    | 1         | 0.45%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 74        | 56.92%  |
| Ethernet | 56        | 43.08%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 76        | 59.84%  |
| 1     | 48        | 37.8%   |
| 0     | 3         | 2.36%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 119       | 91.54%  |
| Yes  | 11        | 8.46%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 51        | 46.79%  |
| Realtek Semiconductor           | 31        | 28.44%  |
| Broadcom                        | 9         | 8.26%   |
| Qualcomm Atheros Communications | 4         | 3.67%   |
| IMC Networks                    | 4         | 3.67%   |
| Foxconn / Hon Hai               | 3         | 2.75%   |
| Realtek                         | 2         | 1.83%   |
| Ralink                          | 2         | 1.83%   |
| Opticis                         | 1         | 0.92%   |
| Lite-On Technology              | 1         | 0.92%   |
| Hewlett-Packard                 | 1         | 0.92%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 27        | 24.77%  |
| Intel Bluetooth wireless interface             | 18        | 16.51%  |
| Intel AX201 Bluetooth                          | 18        | 16.51%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 11        | 10.09%  |
| Realtek  Bluetooth 4.2 Adapter                 | 4         | 3.67%   |
| Qualcomm Atheros  Bluetooth Device             | 3         | 2.75%   |
| Intel Bluetooth Device                         | 3         | 2.75%   |
| Realtek Bluetooth Radio                        | 2         | 1.83%   |
| Ralink RT3290 Bluetooth                        | 2         | 1.83%   |
| IMC Networks Wireless_Device                   | 2         | 1.83%   |
| IMC Networks Bluetooth Radio                   | 2         | 1.83%   |
| Foxconn / Hon Hai Wireless_Device              | 2         | 1.83%   |
| Qualcomm Atheros AR3011 Bluetooth              | 1         | 0.92%   |
| Opticis Bluetooth Radio                        | 1         | 0.92%   |
| Lite-On Wireless_Device                        | 1         | 0.92%   |
| Intel AX200 Bluetooth                          | 1         | 0.92%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 0.92%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 0.92%   |
| Broadcom HP Portable Valentine                 | 1         | 0.92%   |
| Broadcom HP Portable SoftSailing               | 1         | 0.92%   |
| Broadcom HP Portable Bumble Bee                | 1         | 0.92%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 0.92%   |
| Broadcom BCM20702A0 Bluetooth                  | 1         | 0.92%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 0.92%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR           | 1         | 0.92%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 0.92%   |
| Broadcom BCM2045 Bluetooth                     | 1         | 0.92%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 96        | 69.06%  |
| AMD                    | 31        | 22.3%   |
| Nvidia                 | 8         | 5.76%   |
| Zhaoxin                | 1         | 0.72%   |
| MosArt Semiconductor   | 1         | 0.72%   |
| GN Netcom              | 1         | 0.72%   |
| Generalplus Technology | 1         | 0.72%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP High Definition Audio Controller                                            | 30        | 17.44%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 26        | 15.12%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 9.88%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 8.72%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 13        | 7.56%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 8         | 4.65%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 3.49%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 2.91%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 1.74%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.74%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.74%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.74%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 1.74%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 3         | 1.74%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.16%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.16%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 1.16%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.16%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.16%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.16%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.58%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000/KX-7000 High Definition Audio Controller         | 1         | 0.58%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.58%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.58%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.58%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.58%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.58%   |
| Nvidia Audio device                                                                               | 1         | 0.58%   |
| MosArt Semiconductor MosArt USB Audio Device                                                      | 1         | 0.58%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.58%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.58%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.58%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.58%   |
| GN Netcom Jabra EVOLVE 20 SE MS                                                                   | 1         | 0.58%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.58%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.58%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.58%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.58%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.58%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 52        | 36.88%  |
| SK hynix                                | 25        | 17.73%  |
| Micron Technology                       | 15        | 10.64%  |
| Foxline                                 | 10        | 7.09%   |
| Crucial                                 | 8         | 5.67%   |
| Kingston                                | 6         | 4.26%   |
| Unknown                                 | 4         | 2.84%   |
| Ramaxel Technology                      | 3         | 2.13%   |
| Unknown (ABCD)                          | 2         | 1.42%   |
| Silicon Power Computer & Communications | 2         | 1.42%   |
| Elpida                                  | 2         | 1.42%   |
| A-DATA Technology                       | 2         | 1.42%   |
| Unknown                                 | 2         | 1.42%   |
| Silicon Power                           | 1         | 0.71%   |
| SHARETRONIC                             | 1         | 0.71%   |
| Qumo                                    | 1         | 0.71%   |
| Patriot                                 | 1         | 0.71%   |
| King Tiger                              | 1         | 0.71%   |
| Hikvision                               | 1         | 0.71%   |
| ChangXin Memory                         | 1         | 0.71%   |
| <Invalid>                               | 1         | 0.71%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                               | Notebooks | Percent |
|---------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s               | 17        | 11.41%  |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s               | 5         | 3.36%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s         | 4         | 2.68%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s        | 3         | 2.01%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s            | 3         | 2.01%   |
| Samsung RAM M471A5244CB0-CTD 4096MB SODIMM DDR4 3266MT/s            | 3         | 2.01%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 2.01%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s               | 3         | 2.01%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s               | 3         | 2.01%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s                | 3         | 2.01%   |
| Foxline RAM FL3200D4S22-8G 8GB SODIMM DDR4 3200MT/s                 | 3         | 2.01%   |
| Foxline RAM FL2666D4S19-8G ]. 8GB SODIMM DDR4 2667MT/s              | 3         | 2.01%   |
| Foxline RAM FL2400D4S17S-8G 8GB SODIMM DDR4 2400MT/s                | 3         | 2.01%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                          | 2         | 1.34%   |
| Unknown (ABCD) RAM 123456789012345678 2048MB SODIMM LPDDR4 2400MT/s | 2         | 1.34%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s              | 2         | 1.34%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s        | 2         | 1.34%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 1.34%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s              | 2         | 1.34%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s        | 2         | 1.34%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s              | 2         | 1.34%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 4GB SODIMM LPDDR5 6400MT/s          | 2         | 1.34%   |
| Silicon Power & RAM Module 8GB SODIMM DDR4 3200MT/s                 | 2         | 1.34%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s               | 2         | 1.34%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s               | 2         | 1.34%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                          | 2         | 1.34%   |
| Micron RAM 8ATF2G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s          | 2         | 1.34%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s              | 2         | 1.34%   |
| Crucial RAM CT8G4SFS832A.C8FN 8GB SODIMM DDR4 3200MT/s              | 2         | 1.34%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s                          | 2         | 1.34%   |
| Unknown                                                             | 2         | 1.34%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                           | 1         | 0.67%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                           | 1         | 0.67%   |
| SK hynix RAM HYMP125S64CP8-S6 2048MB SODIMM DDR 975MT/s             | 1         | 0.67%   |
| SK hynix RAM HMT41GS6MFR8C-H9 8GB SODIMM DDR3 1333MT/s              | 1         | 0.67%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s              | 1         | 0.67%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s              | 1         | 0.67%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s             | 1         | 0.67%   |
| SK hynix RAM HMAA1GS6CMR6N-VK 8GB SODIMM DDR4 2667MT/s              | 1         | 0.67%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s              | 1         | 0.67%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 96        | 77.42%  |
| DDR3   | 18        | 14.52%  |
| LPDDR5 | 3         | 2.42%   |
| LPDDR4 | 3         | 2.42%   |
| DDR2   | 3         | 2.42%   |
| LPDDR3 | 1         | 0.81%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 112       | 84.85%  |
| Row Of Chips | 18        | 13.64%  |
| DIMM         | 1         | 0.76%   |
| Chip         | 1         | 0.76%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 74        | 55.22%  |
| 4096  | 36        | 26.87%  |
| 16384 | 13        | 9.7%    |
| 2048  | 8         | 5.97%   |
| 1024  | 3         | 2.24%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 52        | 40%     |
| 2667  | 36        | 27.69%  |
| 1600  | 13        | 10%     |
| 2400  | 9         | 6.92%   |
| 6400  | 3         | 2.31%   |
| 3266  | 3         | 2.31%   |
| 1333  | 3         | 2.31%   |
| 2133  | 2         | 1.54%   |
| 1334  | 2         | 1.54%   |
| 667   | 2         | 1.54%   |
| 3733  | 1         | 0.77%   |
| 2666  | 1         | 0.77%   |
| 1866  | 1         | 0.77%   |
| 1066  | 1         | 0.77%   |
| 975   | 1         | 0.77%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

Zero info for selected period =(

Printer Model
-------------

Printer device models

Zero info for selected period =(

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
| Chicony Electronics                    | 26        | 21.14%  |
| Syntek                                 | 21        | 17.07%  |
| IMC Networks                           | 16        | 13.01%  |
| Bison Electronics                      | 14        | 11.38%  |
| Quanta                                 | 8         | 6.5%    |
| Sunplus Innovation Technology          | 6         | 4.88%   |
| Microdia                               | 5         | 4.07%   |
| Realtek Semiconductor                  | 4         | 3.25%   |
| Luxvisions Innotech Limited            | 4         | 3.25%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.25%   |
| Acer                                   | 3         | 2.44%   |
| USB Camera CS                          | 2         | 1.63%   |
| Suyin                                  | 2         | 1.63%   |
| SunplusIT                              | 2         | 1.63%   |
| Sonix Technology                       | 2         | 1.63%   |
| Primax Electronics                     | 1         | 0.81%   |
| GEMBIRD                                | 1         | 0.81%   |
| Alcor Micro                            | 1         | 0.81%   |
| Unknown                                | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 20        | 16.26%  |
| Chicony USB camera                                  | 10        | 8.13%   |
| IMC Networks Integrated Camera                      | 6         | 4.88%   |
| Bison Integrated Camera                             | 5         | 4.07%   |
| IMC Networks ov9734_azurewave_camera                | 4         | 3.25%   |
| Chicony Integrated Camera                           | 4         | 3.25%   |
| Bison BisonCam,NB Pro                               | 4         | 3.25%   |
| Sunplus FHD Camera Microphone                       | 3         | 2.44%   |
| IMC Networks HD Camera                              | 3         | 2.44%   |
| USB Camera CS USB Camera CS                         | 2         | 1.63%   |
| Sonix USB 2.0 Camera                                | 2         | 1.63%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.63%   |
| Quanta HP Webcam                                    | 2         | 1.63%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.63%   |
| Microdia Webcam Vitade AF                           | 2         | 1.63%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 1.63%   |
| Chicony USB2.0 Camera                               | 2         | 1.63%   |
| Chicony HD User Facing                              | 2         | 1.63%   |
| Chicony ACER HD User Facing                         | 2         | 1.63%   |
| Bison HD Webcam                                     | 2         | 1.63%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.81%   |
| Suyin HP Truevision HD                              | 1         | 0.81%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.81%   |
| SunplusIT XiaoMi USB 2.0 Webcam                     | 1         | 0.81%   |
| SunplusIT MTD camera                                | 1         | 0.81%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 0.81%   |
| Sunplus BKX Usb FHD Camera                          | 1         | 0.81%   |
| Sunplus Asus Webcam                                 | 1         | 0.81%   |
| Realtek USB Camera                                  | 1         | 0.81%   |
| Realtek HP Truevision HD                            | 1         | 0.81%   |
| Quanta VGA WebCam                                   | 1         | 0.81%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 0.81%   |
| Quanta USB HD Webcam                                | 1         | 0.81%   |
| Quanta HD Camera                                    | 1         | 0.81%   |
| Primax HP HD Webcam [Fixed]                         | 1         | 0.81%   |
| Microdia USB 2.0 Camera                             | 1         | 0.81%   |
| Microdia Integrated_Webcam_HD                       | 1         | 0.81%   |
| Microdia Integrated Webcam                          | 1         | 0.81%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.81%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 9         | 64.29%  |
| Validity Sensors           | 3         | 21.43%  |
| Synaptics                  | 2         | 14.29%  |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                             | Notebooks | Percent |
|---------------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device               | 9         | 64.29%  |
| Synaptics UWP WBDI Device                         | 2         | 14.29%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor | 1         | 7.14%   |
| Validity Sensors VFS495 Fingerprint Reader        | 1         | 7.14%   |
| Validity Sensors VFS451 Fingerprint Reader        | 1         | 7.14%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor | Notebooks | Percent |
|--------|-----------|---------|
| Upek   | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                      | Notebooks | Percent |
|------------------------------------------------------------|-----------|---------|
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode) | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 85        | 65.89%  |
| 1     | 35        | 27.13%  |
| 2     | 9         | 6.98%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 15        | 30%     |
| Graphics card         | 15        | 30%     |
| Fingerprint reader    | 14        | 28%     |
| Bluetooth             | 2         | 4%      |
| Sound                 | 1         | 2%      |
| Net/ethernet          | 1         | 2%      |
| Multimedia controller | 1         | 2%      |
| Chipcard              | 1         | 2%      |

