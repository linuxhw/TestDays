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

Total: 196

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Red OS 7.3.1 | 44        | 34.38%  |
| Red OS 7.3.2 | 41        | 32.03%  |
| Red OS 7.3   | 40        | 31.25%  |
| Red OS 8.0   | 2         | 1.56%   |
| Red OS 7.2   | 1         | 0.78%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Red OS | 120       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64    | 25        | 18.52%  |
| 5.15.72-1.el7.3.x86_64  | 23        | 17.04%  |
| 5.15.87-1.el7.3.x86_64  | 13        | 9.63%   |
| 5.15.35-4.el7.3.x86_64  | 10        | 7.41%   |
| 5.10.29-1.el7.x86_64    | 10        | 7.41%   |
| 6.1.52-1.el7.3.x86_64   | 9         | 6.67%   |
| 5.15.35-1.el7.3.x86_64  | 6         | 4.44%   |
| 6.1.20-2.el7.3.x86_64   | 4         | 2.96%   |
| 5.15.35-5.el7.3.x86_64  | 4         | 2.96%   |
| 6.1.44-1.el7.3.x86_64   | 3         | 2.22%   |
| 5.15.78-2.el7.3.x86_64  | 3         | 2.22%   |
| 5.15.125-1.el7.3.x86_64 | 3         | 2.22%   |
| 5.10.1-1.el7.x86_64     | 3         | 2.22%   |
| 6.1.38-2.el7.3.x86_64   | 2         | 1.48%   |
| 5.15.131-1.el7.3.x86_64 | 2         | 1.48%   |
| 5.15.10-4.el7.x86_64    | 2         | 1.48%   |
| 5.10.29-3.el7.x86_64    | 2         | 1.48%   |
| 5.10.24-2.el7.x86_64    | 2         | 1.48%   |
| 6.6.6-1.red80.x86_64    | 1         | 0.74%   |
| 6.1.52-1.red80.x86_64   | 1         | 0.74%   |
| 5.18.1-1.el7.x86_64     | 1         | 0.74%   |
| 5.15.120                | 1         | 0.74%   |
| 5.15.10-3.el7.x86_64    | 1         | 0.74%   |
| 5.15.10-2.el7.x86_64    | 1         | 0.74%   |
| 5.13.15-1.el7.x86_64    | 1         | 0.74%   |
| 5.10.24-1.el7.x86_64    | 1         | 0.74%   |
| 4.19.79-1.el7.x86_64    | 1         | 0.74%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.10  | 29        | 21.64%  |
| 5.15.72  | 23        | 17.16%  |
| 5.15.35  | 19        | 14.18%  |
| 5.15.87  | 13        | 9.7%    |
| 5.10.29  | 12        | 8.96%   |
| 6.1.52   | 10        | 7.46%   |
| 6.1.20   | 4         | 2.99%   |
| 6.1.44   | 3         | 2.24%   |
| 5.15.78  | 3         | 2.24%   |
| 5.15.125 | 3         | 2.24%   |
| 5.10.24  | 3         | 2.24%   |
| 5.10.1   | 3         | 2.24%   |
| 6.1.38   | 2         | 1.49%   |
| 5.15.131 | 2         | 1.49%   |
| 6.6.6    | 1         | 0.75%   |
| 5.18.1   | 1         | 0.75%   |
| 5.15.120 | 1         | 0.75%   |
| 5.13.15  | 1         | 0.75%   |
| 4.19.79  | 1         | 0.75%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 87        | 69.05%  |
| 6.1     | 18        | 14.29%  |
| 5.10    | 17        | 13.49%  |
| 6.6     | 1         | 0.79%   |
| 5.18    | 1         | 0.79%   |
| 5.13    | 1         | 0.79%   |
| 4.19    | 1         | 0.79%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 120       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 104       | 85.25%  |
| Cinnamon   | 13        | 10.66%  |
| X-Cinnamon | 3         | 2.46%   |
| GNOME      | 2         | 1.64%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 116       | 95.08%  |
| Wayland | 6         | 4.92%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 114       | 92.68%  |
| SDDM    | 4         | 3.25%   |
| Unknown | 3         | 2.44%   |
| LightDM | 2         | 1.63%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 57.26%  |
| ru_RU   | 52        | 41.94%  |
| en_US   | 1         | 0.81%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 103       | 84.43%  |
| BIOS | 19        | 15.57%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 117       | 96.69%  |
| Btrfs   | 2         | 1.65%   |
| Xfs     | 1         | 0.83%   |
| Overlay | 1         | 0.83%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 102       | 84.3%   |
| MBR     | 16        | 13.22%  |
| Unknown | 3         | 2.48%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 109       | 89.34%  |
| Yes       | 13        | 10.66%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 92        | 74.8%   |
| Yes       | 31        | 25.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 43        | 35.83%  |
| Hewlett-Packard                | 18        | 15%     |
| ICL                            | 7         | 5.83%   |
| HUAWEI                         | 6         | 5%      |
| MSI                            | 5         | 4.17%   |
| Dell                           | 5         | 4.17%   |
| ASUSTek Computer               | 5         | 4.17%   |
| Aquarius                       | 4         | 3.33%   |
| Kraftway                       | 3         | 2.5%    |
| Digma                          | 3         | 2.5%    |
| Acer                           | 3         | 2.5%    |
| iRU                            | 2         | 1.67%   |
| IP3 Technology                 | 2         | 1.67%   |
| HONOR                          | 2         | 1.67%   |
| Graviton                       | 2         | 1.67%   |
| Gigabyte Technology            | 2         | 1.67%   |
| 3Logic Group                   | 2         | 1.67%   |
| Timi                           | 1         | 0.83%   |
| THUNDEROBOT                    | 1         | 0.83%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.83%   |
| Pegatron                       | 1         | 0.83%   |
| mtech                          | 1         | 0.83%   |
| Unknown                        | 1         | 0.83%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE                  | 17        | 14.17%  |
| Lenovo ThinkBook 15 G3 ACL 21A4      | 3         | 2.5%    |
| Kraftway ACCORD                      | 3         | 2.5%    |
| ICL RAYbook Si1512                   | 3         | 2.5%    |
| HP Laptop 15s-eq1xxx                 | 3         | 2.5%    |
| Unknown                              | 3         | 2.5%    |
| iRU 15ALC                            | 2         | 1.67%   |
| IP3 ACN30                            | 2         | 1.67%   |
| Timi Redmi Book Pro 15 2022          | 1         | 0.83%   |
| THUNDEROBOT 911AirD                  | 1         | 0.83%   |
| Shanghai Zhaoxin ZXE CRB             | 1         | 0.83%   |
| Pegatron A35                         | 1         | 0.83%   |
| mtech MTL1578                        | 1         | 0.83%   |
| MSI Sword 15 A12UE                   | 1         | 0.83%   |
| MSI Modern 15 B12M                   | 1         | 0.83%   |
| MSI Modern 14 C12M                   | 1         | 0.83%   |
| MSI GL62 6QF                         | 1         | 0.83%   |
| MSI FX610                            | 1         | 0.83%   |
| Lenovo V15 G2 ALC 82KD               | 1         | 0.83%   |
| Lenovo V15 G1 IML 82NB               | 1         | 0.83%   |
| Lenovo V130-15IKB 81HN               | 1         | 0.83%   |
| Lenovo ThinkPad X230 23245C8         | 1         | 0.83%   |
| Lenovo ThinkPad X220 4290RB3         | 1         | 0.83%   |
| Lenovo ThinkPad T460s 20FAS1TQ02     | 1         | 0.83%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2DE00 | 1         | 0.83%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2DD00 | 1         | 0.83%   |
| Lenovo ThinkPad E15 Gen 4 21E6009UGP | 1         | 0.83%   |
| Lenovo ThinkPad E15 Gen 4 21E60061RT | 1         | 0.83%   |
| Lenovo ThinkBook 15 G2 ITL 20VE      | 1         | 0.83%   |
| Lenovo ThinkBook 15 G2 ARE 20VG      | 1         | 0.83%   |
| Lenovo ThinkBook 14-IIL 20SL         | 1         | 0.83%   |
| Lenovo IdeaPad L340-15IWL 81LG       | 1         | 0.83%   |
| Lenovo IdeaPad L340-15API 81LW       | 1         | 0.83%   |
| Lenovo IdeaPad 700-15ISK 80RU        | 1         | 0.83%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7     | 1         | 0.83%   |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 1         | 0.83%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 0.83%   |
| Lenovo IdeaPad 3 15ITL05 81X8        | 1         | 0.83%   |
| Lenovo IdeaPad 1 15ALC7 82R4         | 1         | 0.83%   |
| Lenovo G570 20079                    | 1         | 0.83%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo V15-IWL       | 17        | 14.17%  |
| Lenovo IdeaPad       | 8         | 6.67%   |
| Lenovo ThinkPad      | 7         | 5.83%   |
| Lenovo ThinkBook     | 6         | 5%      |
| HP Laptop            | 6         | 5%      |
| ICL RAYbook          | 4         | 3.33%   |
| Kraftway ACCORD      | 3         | 2.5%    |
| HP ProBook           | 3         | 2.5%    |
| HP Pavilion          | 3         | 2.5%    |
| Digma EVE            | 3         | 2.5%    |
| Dell Vostro          | 3         | 2.5%    |
| Unknown              | 3         | 2.5%    |
| MSI Modern           | 2         | 1.67%   |
| Lenovo V15           | 2         | 1.67%   |
| iRU 15ALC            | 2         | 1.67%   |
| IP3 ACN30            | 2         | 1.67%   |
| HP EliteBook         | 2         | 1.67%   |
| Gigabyte G5          | 2         | 1.67%   |
| Aquarius NS685U      | 2         | 1.67%   |
| Acer Aspire          | 2         | 1.67%   |
| Timi Redmi           | 1         | 0.83%   |
| THUNDEROBOT 911AirD  | 1         | 0.83%   |
| Shanghai Zhaoxin ZXE | 1         | 0.83%   |
| Pegatron A35         | 1         | 0.83%   |
| mtech MTL1578        | 1         | 0.83%   |
| MSI Sword            | 1         | 0.83%   |
| MSI GL62             | 1         | 0.83%   |
| MSI FX610            | 1         | 0.83%   |
| Lenovo V130-15IKB    | 1         | 0.83%   |
| Lenovo G570          | 1         | 0.83%   |
| Lenovo B590          | 1         | 0.83%   |
| ICL Si1407           | 1         | 0.83%   |
| ICL S1511            | 1         | 0.83%   |
| HUAWEI NDZ-WXX9      | 1         | 0.83%   |
| HUAWEI NBLK-WAX9X    | 1         | 0.83%   |
| HUAWEI NBD-WXX9      | 1         | 0.83%   |
| HUAWEI BOHL-WXX9     | 1         | 0.83%   |
| HUAWEI BOD-WXX9      | 1         | 0.83%   |
| HUAWEI BDZ-WXX9      | 1         | 0.83%   |
| HONOR NBR-WAX9       | 1         | 0.83%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 31        | 25.83%  |
| 2021 | 24        | 20%     |
| 2022 | 20        | 16.67%  |
| 2020 | 14        | 11.67%  |
| 2012 | 9         | 7.5%    |
| 2010 | 5         | 4.17%   |
| 2011 | 4         | 3.33%   |
| 2017 | 3         | 2.5%    |
| 2018 | 2         | 1.67%   |
| 2016 | 2         | 1.67%   |
| 2023 | 1         | 0.83%   |
| 2015 | 1         | 0.83%   |
| 2014 | 1         | 0.83%   |
| 2013 | 1         | 0.83%   |
| 2008 | 1         | 0.83%   |
| 2007 | 1         | 0.83%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 120       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 120       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 120       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 69        | 57.5%   |
| 16.01-24.0 | 19        | 15.83%  |
| 3.01-4.0   | 16        | 13.33%  |
| 8.01-16.0  | 13        | 10.83%  |
| 2.01-3.0   | 2         | 1.67%   |
| 32.01-64.0 | 1         | 0.83%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 76        | 59.38%  |
| 2.01-3.0  | 30        | 23.44%  |
| 0.51-1.0  | 9         | 7.03%   |
| 3.01-4.0  | 7         | 5.47%   |
| 4.01-8.0  | 4         | 3.13%   |
| 8.01-16.0 | 2         | 1.56%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 106       | 86.18%  |
| 2      | 12        | 9.76%   |
| 3      | 4         | 3.25%   |
| 4      | 1         | 0.81%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 101       | 83.47%  |
| Yes       | 20        | 16.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 87        | 72.5%   |
| No        | 33        | 27.5%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 118       | 98.33%  |
| No        | 2         | 1.67%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 105       | 87.5%   |
| No        | 15        | 12.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 119       | 99.17%  |
| Ukraine | 1         | 0.83%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 31        | 24.8%   |
| Salekhard        | 22        | 17.6%   |
| Murom            | 16        | 12.8%   |
| St Petersburg    | 5         | 4%      |
| Perm             | 4         | 3.2%    |
| Yekaterinburg    | 3         | 2.4%    |
| Yakutsk          | 3         | 2.4%    |
| Vladimir         | 3         | 2.4%    |
| Ryazan           | 3         | 2.4%    |
| Novy Urengoy     | 3         | 2.4%    |
| Krasnodar        | 3         | 2.4%    |
| Nizhniy Novgorod | 2         | 1.6%    |
| Kursk            | 2         | 1.6%    |
| Krasnoyarsk      | 2         | 1.6%    |
| Yaroslavl        | 1         | 0.8%    |
| Volzhskiy        | 1         | 0.8%    |
| Vladivostok      | 1         | 0.8%    |
| Ulyanovsk        | 1         | 0.8%    |
| Tver             | 1         | 0.8%    |
| Strezhevoy       | 1         | 0.8%    |
| Sevastopol       | 1         | 0.8%    |
| Saratov          | 1         | 0.8%    |
| Saransk          | 1         | 0.8%    |
| Samara           | 1         | 0.8%    |
| Pushkino         | 1         | 0.8%    |
| Omsk             | 1         | 0.8%    |
| Novosibirsk      | 1         | 0.8%    |
| Novokuybyshevsk  | 1         | 0.8%    |
| Nadym            | 1         | 0.8%    |
| Muromskiy        | 1         | 0.8%    |
| Kirzhach         | 1         | 0.8%    |
| Khabarovsk       | 1         | 0.8%    |
| Kaluga           | 1         | 0.8%    |
| Giaginskaya      | 1         | 0.8%    |
| Borinskoye       | 1         | 0.8%    |
| Belgorod         | 1         | 0.8%    |
| Balashikha       | 1         | 0.8%    |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 30        | 45     | 21.9%   |
| WDC                 | 17        | 24     | 12.41%  |
| SK hynix            | 10        | 12     | 7.3%    |
| Seagate             | 7         | 9      | 5.11%   |
| A-DATA Technology   | 7         | 7      | 5.11%   |
| Toshiba             | 5         | 26     | 3.65%   |
| Micron Technology   | 5         | 10     | 3.65%   |
| HGST                | 5         | 5      | 3.65%   |
| Foxline             | 5         | 5      | 3.65%   |
| Unknown             | 4         | 4      | 2.92%   |
| Silicon Motion      | 4         | 4      | 2.92%   |
| Intel               | 4         | 4      | 2.92%   |
| YMTC                | 3         | 3      | 2.19%   |
| Phison              | 3         | 3      | 2.19%   |
| Gigabyte Technology | 3         | 3      | 2.19%   |
| UMIS                | 2         | 2      | 1.46%   |
| SanDisk             | 2         | 2      | 1.46%   |
| KIOXIA              | 2         | 2      | 1.46%   |
| Kingston            | 2         | 2      | 1.46%   |
| Crucial             | 2         | 2      | 1.46%   |
| China               | 2         | 6      | 1.46%   |
| Transcend           | 1         | 1      | 0.73%   |
| Thinkplus           | 1         | 1      | 0.73%   |
| SPCC Sol            | 1         | 1      | 0.73%   |
| Netac               | 1         | 1      | 0.73%   |
| Lenovo              | 1         | 1      | 0.73%   |
| KingSpec            | 1         | 1      | 0.73%   |
| Kimtigo             | 1         | 2      | 0.73%   |
| JMicron Technology  | 1         | 1      | 0.73%   |
| ITHOO               | 1         | 1      | 0.73%   |
| HUAWEI              | 1         | 1      | 0.73%   |
| Hikvision           | 1         | 1      | 0.73%   |
| Apacer              | 1         | 2      | 0.73%   |
| Unknown             | 1         | 1      | 0.73%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB       | 18        | 12.86%  |
| Foxline FLSSD256M80E13TCX5 256GB       | 5         | 3.57%   |
| Silicon Motion Wodposit NVMe SSD 256GB | 4         | 2.86%   |
| Samsung MZALQ512HALU-000L2 512GB       | 3         | 2.14%   |
| YMTC PC005 512GB                       | 2         | 1.43%   |
| WDC WD10SPZX-00Z10T0 1TB               | 2         | 1.43%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB   | 2         | 1.43%   |
| Unknown NVMe SSD Drive 512GB           | 2         | 1.43%   |
| Toshiba MQ01ABF050 500GB               | 2         | 1.43%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB | 2         | 1.43%   |
| SK hynix PC711 HFS512GDE9X073N 512GB   | 2         | 1.43%   |
| Seagate ST1000LM035-1RK172 1TB         | 2         | 1.43%   |
| Samsung MZALQ256HBJD-00BL2 256GB       | 2         | 1.43%   |
| KIOXIA KBG40ZNS256G NVMe 256GB         | 2         | 1.43%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB       | 2         | 1.43%   |
| A-DATA SU650 240GB SSD                 | 2         | 1.43%   |
| YMTC PC210-512GB-B                     | 1         | 0.71%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 1         | 0.71%   |
| WDC WDS250G2B0A-00SM50 250GB SSD       | 1         | 0.71%   |
| WDC WD5000BPVT-55HXZT3 500GB           | 1         | 0.71%   |
| WDC WD3200BPVT-24JJ5T0 320GB           | 1         | 0.71%   |
| WDC WD3200BEVT-60ZCT1 320GB            | 1         | 0.71%   |
| WDC WD2500BEVT-22ZCT0 250GB            | 1         | 0.71%   |
| WDC WD10SPZX-24Z10 1TB                 | 1         | 0.71%   |
| WDC WD10JPVX-22JC3T0 1TB               | 1         | 0.71%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB   | 1         | 0.71%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB   | 1         | 0.71%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB   | 1         | 0.71%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 1         | 0.71%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB   | 1         | 0.71%   |
| Unknown SLD128  128GB                  | 1         | 0.71%   |
| Unknown 58K722  128GB                  | 1         | 0.71%   |
| UMIS RPJTJ512MEE1OWX 512GB             | 1         | 0.71%   |
| UMIS RPJTJ256MGE1QDQ 256GB             | 1         | 0.71%   |
| Transcend TS240GMTS820S 240GB SSD      | 1         | 0.71%   |
| Toshiba MK5075GSX 500GB                | 1         | 0.71%   |
| Toshiba MK5059GSXP 500GB               | 1         | 0.71%   |
| Toshiba KXG60ZNV512G 512GB             | 1         | 0.71%   |
| Toshiba KXG60ZNV256G 256GB             | 1         | 0.71%   |
| Thinkplus SSD ST600 M.2 512G           | 1         | 0.71%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 8         | 15     | 34.78%  |
| Seagate | 7         | 9      | 30.43%  |
| HGST    | 5         | 5      | 21.74%  |
| Toshiba | 3         | 23     | 13.04%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 4         | 4      | 16.67%  |
| Samsung Electronics | 3         | 3      | 12.5%   |
| WDC                 | 2         | 2      | 8.33%   |
| Crucial             | 2         | 2      | 8.33%   |
| China               | 2         | 6      | 8.33%   |
| Transcend           | 1         | 1      | 4.17%   |
| Thinkplus           | 1         | 1      | 4.17%   |
| SPCC Sol            | 1         | 1      | 4.17%   |
| SanDisk             | 1         | 1      | 4.17%   |
| Netac               | 1         | 1      | 4.17%   |
| Micron Technology   | 1         | 1      | 4.17%   |
| Lenovo              | 1         | 1      | 4.17%   |
| Kingston            | 1         | 1      | 4.17%   |
| KingSpec            | 1         | 1      | 4.17%   |
| JMicron Technology  | 1         | 1      | 4.17%   |
| Apacer              | 1         | 2      | 4.17%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 84        | 109    | 62.69%  |
| SSD     | 23        | 29     | 17.16%  |
| HDD     | 22        | 52     | 16.42%  |
| MMC     | 3         | 3      | 2.24%   |
| Unknown | 2         | 2      | 1.49%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 84        | 109    | 64.62%  |
| SATA | 40        | 78     | 30.77%  |
| SAS  | 3         | 5      | 2.31%   |
| MMC  | 3         | 3      | 2.31%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 30        | 54     | 68.18%  |
| 0.51-1.0   | 12        | 25     | 27.27%  |
| 1.01-2.0   | 2         | 2      | 4.55%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 64        | 51.2%   |
| 251-500    | 31        | 24.8%   |
| 501-1000   | 12        | 9.6%    |
| 51-100     | 8         | 6.4%    |
| 1001-2000  | 6         | 4.8%    |
| 1-20       | 3         | 2.4%    |
| 21-50      | 1         | 0.8%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 88        | 69.29%  |
| 21-50     | 23        | 18.11%  |
| 101-250   | 5         | 3.94%   |
| 501-1000  | 4         | 3.15%   |
| 51-100    | 4         | 3.15%   |
| 251-500   | 2         | 1.57%   |
| 1001-2000 | 1         | 0.79%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 11.11%  |
| Toshiba MQ01ABF050 500GB            | 1         | 13     | 11.11%  |
| Toshiba MK5075GSX 500GB             | 1         | 7      | 11.11%  |
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
| Toshiba           | 2         | 21     | 25%     |
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
| Toshiba | 2         | 21     | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 25     | 75%     |
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
| Works    | 107       | 151    | 84.92%  |
| Detected | 11        | 17     | 8.73%   |
| Malfunc  | 8         | 27     | 6.35%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 82        | 45.81%  |
| Samsung Electronics          | 27        | 15.08%  |
| AMD                          | 15        | 8.38%   |
| Phison Electronics           | 11        | 6.15%   |
| SK hynix                     | 10        | 5.59%   |
| SanDisk                      | 8         | 4.47%   |
| Silicon Motion               | 4         | 2.23%   |
| Micron Technology            | 4         | 2.23%   |
| Yangtze Memory Technologies  | 3         | 1.68%   |
| MAXIO Technology (Hangzhou)  | 3         | 1.68%   |
| Union Memory (Shenzhen)      | 2         | 1.12%   |
| Toshiba America Info Systems | 2         | 1.12%   |
| KIOXIA                       | 2         | 1.12%   |
| ADATA Technology             | 2         | 1.12%   |
| Zhaoxin                      | 1         | 0.56%   |
| ShenZhen TIGO Semiconductor  | 1         | 0.56%   |
| Realtek Semiconductor        | 1         | 0.56%   |
| Kingston Technology Company  | 1         | 0.56%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 30        | 15.87%  |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                  | 26        | 13.76%  |
| AMD FCH SATA Controller [AHCI mode]                                          | 12        | 6.35%   |
| Phison PS5013-E13 PCIe3 NVMe Controller (DRAM-less)                          | 9         | 4.76%   |
| Intel Volume Management Device NVMe RAID Controller                          | 8         | 4.23%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 7         | 3.7%    |
| Intel Tiger Lake-LP SATA Controller                                          | 7         | 3.7%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 6         | 3.17%   |
| SanDisk Ultra 3D / WD Blue SN550 NVMe SSD                                    | 5         | 2.65%   |
| Intel Comet Lake SATA AHCI Controller                                        | 5         | 2.65%   |
| Intel Alder Lake-P SATA AHCI Controller                                      | 5         | 2.65%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers            | 4         | 2.12%   |
| SK hynix BC511 NVMe SSD                                                      | 3         | 1.59%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                 | 3         | 1.59%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 3         | 1.59%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 3         | 1.59%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 3         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 3         | 1.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 3         | 1.59%   |
| Yangtze Memory PC005 NVMe SSD                                                | 2         | 1.06%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 2         | 1.06%   |
| Phison E16 PCIe4 NVMe Controller                                             | 2         | 1.06%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 2         | 1.06%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 2         | 1.06%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 2         | 1.06%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 1.06%   |
| Intel SSD 660P Series                                                        | 2         | 1.06%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                         | 2         | 1.06%   |
| ADATA ADATA XPG GAMMIXS1 1L Media (256 GB SSD)                               | 2         | 1.06%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G/KH-40000 StorX AHCI Controller        | 1         | 0.53%   |
| Yangtze Memory PC210 NVMe SSD                                                | 1         | 0.53%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 NVMe SSD 256GB                        | 1         | 0.53%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                        | 1         | 0.53%   |
| ShenZhen TIGO kimtigo NVMe SSD (DRAM-less)                                   | 1         | 0.53%   |
| Sandisk WD PC SN740 NVMe SSD 512GB (DRAM-less)                               | 1         | 0.53%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                        | 1         | 0.53%   |
| SanDisk PC SN520 x2 M.2 2242 NVMe SSD                                        | 1         | 0.53%   |
| Samsung NVMe SSD Controller PM9B1 (DRAM-less)                                | 1         | 0.53%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 1         | 0.53%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                            | 1         | 0.53%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 91        | 48.66%  |
| NVMe | 84        | 44.92%  |
| RAID | 9         | 4.81%   |
| IDE  | 3         | 1.6%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 93        | 77.5%   |
| AMD          | 26        | 21.67%  |
| CentaurHauls | 1         | 0.83%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 15%     |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 5.83%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 6         | 5%      |
| Intel Core i5-8259U CPU @ 2.30GHz             | 5         | 4.17%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 4         | 3.33%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 4         | 3.33%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 4         | 3.33%   |
| Intel 12th Gen Core i5-12500H                 | 3         | 2.5%    |
| Intel 12th Gen Core i5-1235U                  | 3         | 2.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 2.5%    |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 2.5%    |
| AMD Ryzen 3 5400U with Radeon Graphics        | 3         | 2.5%    |
| AMD Ryzen 3 4300U with Radeon Graphics        | 3         | 2.5%    |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.67%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 2         | 1.67%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.67%   |
| Intel 12th Gen Core i7-1255U                  | 2         | 1.67%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.67%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.67%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.83%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.83%   |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 0.83%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.83%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.83%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.83%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 0.83%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 1         | 0.83%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 0.83%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 1         | 0.83%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.83%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.83%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 1         | 0.83%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 0.83%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 0.83%   |
| Intel Core i3-9300 CPU @ 3.70GHz              | 1         | 0.83%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 0.83%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 0.83%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 0.83%   |
| Intel Core i3-3120M CPU @ 2.50GHz             | 1         | 0.83%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 0.83%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 45        | 37.5%   |
| Other                          | 29        | 24.17%  |
| Intel Core i3                  | 11        | 9.17%   |
| AMD Ryzen 5                    | 10        | 8.33%   |
| AMD Ryzen 3                    | 10        | 8.33%   |
| Intel Celeron                  | 3         | 2.5%    |
| Intel Pentium                  | 2         | 1.67%   |
| Intel Core i7                  | 2         | 1.67%   |
| AMD Ryzen 7                    | 2         | 1.67%   |
| AMD Phenom II                  | 2         | 1.67%   |
| Intel Pentium Gold             | 1         | 0.83%   |
| Intel Core 2 Duo               | 1         | 0.83%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.83%   |
| AMD A4                         | 1         | 0.83%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 68        | 56.67%  |
| 2      | 29        | 24.17%  |
| 6      | 10        | 8.33%   |
| 12     | 5         | 4.17%   |
| 10     | 5         | 4.17%   |
| 14     | 1         | 0.83%   |
| 8      | 1         | 0.83%   |
| 3      | 1         | 0.83%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 120       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 100       | 83.33%  |
| 1      | 20        | 16.67%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 120       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 24        | 19.67%  |
| 0x806c1    | 15        | 12.3%   |
| 0x806ea    | 12        | 9.84%   |
| 0x08608103 | 7         | 5.74%   |
| 0x906a4    | 6         | 4.92%   |
| 0x906a3    | 6         | 4.92%   |
| 0x306a9    | 5         | 4.1%    |
| 0x206a7    | 5         | 4.1%    |
| 0x08600106 | 5         | 4.1%    |
| 0x0a50000c | 4         | 3.28%   |
| 0x40651    | 3         | 2.46%   |
| Unknown    | 3         | 2.46%   |
| 0x806d1    | 2         | 1.64%   |
| 0x506e3    | 2         | 1.64%   |
| 0x506ca    | 2         | 1.64%   |
| 0x08108102 | 2         | 1.64%   |
| 0x010000c8 | 2         | 1.64%   |
| 0xa0660    | 1         | 0.82%   |
| 0x906eb    | 1         | 0.82%   |
| 0x906e9    | 1         | 0.82%   |
| 0x706e5    | 1         | 0.82%   |
| 0x6fa      | 1         | 0.82%   |
| 0x506c9    | 1         | 0.82%   |
| 0x406e3    | 1         | 0.82%   |
| 0x406c4    | 1         | 0.82%   |
| 0x20655    | 1         | 0.82%   |
| 0x20652    | 1         | 0.82%   |
| 0x0a50000d | 1         | 0.82%   |
| 0x0a404101 | 1         | 0.82%   |
| 0x08600104 | 1         | 0.82%   |
| 0x08108109 | 1         | 0.82%   |
| 0x0810100b | 1         | 0.82%   |
| 0x06006705 | 1         | 0.82%   |
| 0x02000057 | 1         | 0.82%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 39        | 32.5%   |
| TigerLake        | 15        | 12.5%   |
| Alderlake Hybrid | 12        | 10%     |
| Unknown          | 9         | 7.5%    |
| Zen 2            | 6         | 5%      |
| SandyBridge      | 5         | 4.17%   |
| IvyBridge        | 5         | 4.17%   |
| Zen 3            | 4         | 3.33%   |
| Zen+             | 3         | 2.5%    |
| Skylake          | 3         | 2.5%    |
| IceLake          | 3         | 2.5%    |
| Haswell          | 3         | 2.5%    |
| Goldmont         | 3         | 2.5%    |
| Westmere         | 2         | 1.67%   |
| K10              | 2         | 1.67%   |
| Zen              | 1         | 0.83%   |
| Silvermont       | 1         | 0.83%   |
| K8 & K10 hybrid  | 1         | 0.83%   |
| Excavator        | 1         | 0.83%   |
| Core             | 1         | 0.83%   |
| CometLake        | 1         | 0.83%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 92        | 63.89%  |
| AMD     | 30        | 20.83%  |
| Nvidia  | 21        | 14.58%  |
| Zhaoxin | 1         | 0.69%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 19        | 12.93%  |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 11        | 7.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 9         | 6.12%   |
| AMD Lucienne                                                              | 7         | 4.76%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 6         | 4.08%   |
| AMD Renoir [Radeon RX Vega 6 (Ryzen 4000/5000 Mobile Series)]             | 6         | 4.08%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 5         | 3.4%    |
| Intel 3rd Gen Core processor Graphics Controller                          | 5         | 3.4%    |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 5         | 3.4%    |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 4         | 2.72%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 4         | 2.72%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 2.72%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 3         | 2.04%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 3         | 2.04%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 2.04%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                              | 3         | 2.04%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.36%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.36%   |
| Intel HD Graphics 530                                                     | 2         | 1.36%   |
| Intel HD Graphics 500                                                     | 2         | 1.36%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 2         | 1.36%   |
| Zhaoxin ZX-E C-960 GPU                                                    | 1         | 0.68%   |
| Nvidia TU117M [GeForce MX550]                                             | 1         | 0.68%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.68%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.68%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.68%   |
| Nvidia GM108M [GeForce 920MX]                                             | 1         | 0.68%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.68%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.68%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.68%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.68%   |
| Nvidia GF119M [GeForce GT 520MX]                                          | 1         | 0.68%   |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 0.68%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.68%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                         | 1         | 0.68%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 0.68%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.68%   |
| Intel UHD Graphics 620                                                    | 1         | 0.68%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 1         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 69        | 57.5%   |
| 1 x AMD        | 23        | 19.17%  |
| Intel + Nvidia | 19        | 15.83%  |
| Intel + AMD    | 4         | 3.33%   |
| 2 x AMD        | 2         | 1.67%   |
| 1 x Zhaoxin    | 1         | 0.83%   |
| 1 x Nvidia     | 1         | 0.83%   |
| AMD + Nvidia   | 1         | 0.83%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 107       | 87.7%   |
| Unknown     | 12        | 9.84%   |
| Proprietary | 3         | 2.46%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 77        | 62.6%   |
| 1.01-2.0   | 20        | 16.26%  |
| 0.01-0.5   | 12        | 9.76%   |
| 0.51-1.0   | 8         | 6.5%    |
| 3.01-4.0   | 6         | 4.88%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 53        | 42.74%  |
| LG Display           | 18        | 14.52%  |
| Chimei Innolux       | 15        | 12.1%   |
| Samsung Electronics  | 10        | 8.06%   |
| AU Optronics         | 7         | 5.65%   |
| PANDA                | 5         | 4.03%   |
| Philips              | 3         | 2.42%   |
| NLE                  | 2         | 1.61%   |
| Acer                 | 2         | 1.61%   |
| ViewSonic            | 1         | 0.81%   |
| Toshiba              | 1         | 0.81%   |
| TMX                  | 1         | 0.81%   |
| RGT                  | 1         | 0.81%   |
| Lenovo               | 1         | 0.81%   |
| Iiyama               | 1         | 0.81%   |
| HUAWEI               | 1         | 0.81%   |
| Dell                 | 1         | 0.81%   |
| Ancor Communications | 1         | 0.81%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 18        | 14.4%   |
| BOE LCD Monitor BOE09C5 1920x1080 345x194mm 15.6-inch                   | 9         | 7.2%    |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch        | 4         | 3.2%    |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 4         | 3.2%    |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch            | 3         | 2.4%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 3         | 2.4%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 3         | 2.4%    |
| BOE LCD Monitor BOE0936 1920x1080 344x194mm 15.5-inch                   | 3         | 2.4%    |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                   | 3         | 2.4%    |
| NLE Newline NLE0032 3840x2160 944x398mm 40.3-inch                       | 2         | 1.6%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 2         | 1.6%    |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                   | 2         | 1.6%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                    | 2         | 1.6%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.6%    |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.6%    |
| ViewSonic PJ VSC9B34 1920x1080                                          | 1         | 0.8%    |
| Toshiba LCD Monitor LCD58EB 1280x800 261x163mm 12.1-inch                | 1         | 0.8%    |
| TMX LCD Monitor TMX1560 1920x1080 344x194mm 15.5-inch                   | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC3151 1366x768 344x194mm 15.5-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SDC4851 1366x768 344x194mm 15.5-inch    | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 1872x1053mm 84.6-inch | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch   | 1         | 0.8%    |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 890x500mm 40.2-inch   | 1         | 0.8%    |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                   | 1         | 0.8%    |
| Philips PHL 275S1 PHL094B 2560x1440 597x336mm 27.0-inch                 | 1         | 0.8%    |
| Philips 227E4Q PHLC0A9 1920x1080 480x270mm 21.7-inch                    | 1         | 0.8%    |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 1         | 0.8%    |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                 | 1         | 0.8%    |
| PANDA LCD Monitor NCP0065 1920x1080 309x174mm 14.0-inch                 | 1         | 0.8%    |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                 | 1         | 0.8%    |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                 | 1         | 0.8%    |
| PANDA LC116LF3L03 NCP000A 1920x1080 256x144mm 11.6-inch                 | 1         | 0.8%    |
| LG Display LCD Monitor LGDD302 1366x768 277x156mm 12.5-inch             | 1         | 0.8%    |
| LG Display LCD Monitor LGD0671 1920x1080 382x215mm 17.3-inch            | 1         | 0.8%    |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch            | 1         | 0.8%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 88        | 75.86%  |
| 1366x768 (WXGA)    | 16        | 13.79%  |
| 3840x2160 (4K)     | 3         | 2.59%   |
| 1600x900 (HD+)     | 2         | 1.72%   |
| 3440x1440          | 1         | 0.86%   |
| 3200x2000          | 1         | 0.86%   |
| 2560x1440 (QHD)    | 1         | 0.86%   |
| 2240x1400          | 1         | 0.86%   |
| 1680x1050 (WSXGA+) | 1         | 0.86%   |
| 1280x800 (WXGA)    | 1         | 0.86%   |
| 1280x1024 (SXGA)   | 1         | 0.86%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 86        | 69.92%  |
| 14      | 8         | 6.5%    |
| 13      | 6         | 4.88%   |
| 21      | 3         | 2.44%   |
| 17      | 3         | 2.44%   |
| 12      | 3         | 2.44%   |
| 84      | 2         | 1.63%   |
| 40      | 2         | 1.63%   |
| 24      | 2         | 1.63%   |
| 54      | 1         | 0.81%   |
| 34      | 1         | 0.81%   |
| 27      | 1         | 0.81%   |
| 23      | 1         | 0.81%   |
| 22      | 1         | 0.81%   |
| 19      | 1         | 0.81%   |
| 11      | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 99        | 80.49%  |
| 201-300     | 5         | 4.07%   |
| 501-600     | 4         | 3.25%   |
| 401-500     | 4         | 3.25%   |
| 351-400     | 4         | 3.25%   |
| 1501-2000   | 2         | 1.63%   |
| 901-1000    | 2         | 1.63%   |
| 701-800     | 1         | 0.81%   |
| 1001-1500   | 1         | 0.81%   |
| Unknown     | 1         | 0.81%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 105       | 92.92%  |
| 16/10 | 4         | 3.54%   |
| 21/9  | 3         | 2.65%   |
| 5/4   | 1         | 0.88%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 86        | 69.92%  |
| 81-90          | 13        | 10.57%  |
| 201-250        | 7         | 5.69%   |
| More than 1000 | 3         | 2.44%   |
| 61-70          | 3         | 2.44%   |
| 121-130        | 3         | 2.44%   |
| 501-1000       | 2         | 1.63%   |
| 71-80          | 1         | 0.81%   |
| 51-60          | 1         | 0.81%   |
| 351-500        | 1         | 0.81%   |
| 301-350        | 1         | 0.81%   |
| 151-200        | 1         | 0.81%   |
| Unknown        | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 87        | 71.9%   |
| 101-120       | 21        | 17.36%  |
| 51-100        | 7         | 5.79%   |
| 161-240       | 3         | 2.48%   |
| More than 240 | 1         | 0.83%   |
| 1-50          | 1         | 0.83%   |
| Unknown       | 1         | 0.83%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 95        | 79.17%  |
| 0     | 13        | 10.83%  |
| 2     | 11        | 9.17%   |
| 3     | 1         | 0.83%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 84        | 44.68%  |
| Intel                 | 60        | 31.91%  |
| Broadcom              | 11        | 5.85%   |
| Qualcomm Atheros      | 8         | 4.26%   |
| Xiaomi                | 7         | 3.72%   |
| MediaTek              | 5         | 2.66%   |
| TP-Link               | 2         | 1.06%   |
| Samsung Electronics   | 2         | 1.06%   |
| Ralink                | 2         | 1.06%   |
| Huawei Technologies   | 2         | 1.06%   |
| Ralink Technology     | 1         | 0.53%   |
| Qualcomm              | 1         | 0.53%   |
| OPPO Electronics      | 1         | 0.53%   |
| OKB SAPR              | 1         | 0.53%   |
| Broadcom Limited      | 1         | 0.53%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 19.03%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 26        | 11.5%   |
| Intel Wireless 7265                                               | 12        | 5.31%   |
| Intel Wi-Fi 6 AX201                                               | 11        | 4.87%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 11        | 4.87%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 3.54%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7         | 3.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 3.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 2.21%   |
| Intel Wireless 3165                                               | 4         | 1.77%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 4         | 1.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.77%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 3         | 1.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 1.33%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.33%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.33%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.33%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 1.33%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.33%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.88%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 0.88%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.88%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.88%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 2         | 0.88%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.88%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 0.88%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 0.88%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.88%   |
| Broadcom BCM43228 802.11a/b/g/n                                   | 2         | 0.88%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.88%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                 | 2         | 0.88%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1         | 0.44%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.44%   |
| TP-Link 802.11n NIC                                               | 1         | 0.44%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.44%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.44%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter           | 1         | 0.44%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.44%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 56        | 44.8%   |
| Realtek Semiconductor | 44        | 35.2%   |
| Broadcom              | 10        | 8%      |
| Qualcomm Atheros      | 5         | 4%      |
| MediaTek              | 3         | 2.4%    |
| TP-Link               | 2         | 1.6%    |
| Ralink                | 2         | 1.6%    |
| Ralink Technology     | 1         | 0.8%    |
| Qualcomm              | 1         | 0.8%    |
| Broadcom Limited      | 1         | 0.8%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 26        | 20.47%  |
| Intel Wireless 7265                                            | 12        | 9.45%   |
| Intel Wi-Fi 6 AX201                                            | 11        | 8.66%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 11        | 8.66%   |
| Intel Wireless 3165                                            | 4         | 3.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 4         | 3.15%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 3.15%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 2.36%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 2.36%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.36%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 2.36%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 2.36%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 2.36%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 1.57%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.57%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 1.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 2         | 1.57%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.57%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 2         | 1.57%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.57%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 2         | 1.57%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                          | 1         | 0.79%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.79%   |
| TP-Link 802.11n NIC                                            | 1         | 0.79%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.79%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.79%   |
| Realtek RTL8188ETV Wireless LAN 802.11n Network Adapter        | 1         | 0.79%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.79%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.79%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.79%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.79%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.79%   |
| Intel Wireless 8265 / 8275                                     | 1         | 0.79%   |
| Intel Wireless 8260                                            | 1         | 0.79%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 0.79%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.79%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 0.79%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 0.79%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.79%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 1         | 0.79%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 56        | 58.33%  |
| Intel                 | 22        | 22.92%  |
| Xiaomi                | 7         | 7.29%   |
| Qualcomm Atheros      | 3         | 3.13%   |
| Samsung Electronics   | 2         | 2.08%   |
| MediaTek              | 2         | 2.08%   |
| OPPO Electronics      | 1         | 1.04%   |
| OKB SAPR              | 1         | 1.04%   |
| Huawei Technologies   | 1         | 1.04%   |
| Broadcom              | 1         | 1.04%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 43        | 43.88%  |
| Intel Ethernet Connection (6) I219-V                              | 8         | 8.16%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 7         | 7.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 7         | 7.14%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.1%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 3.06%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 3         | 3.06%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.04%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.04%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 2.04%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 2.04%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.02%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.02%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.02%   |
| OPPO SM8350-IDP _SN:27BAACC8                                      | 1         | 1.02%   |
| OKB SAPR Ethernet controller                                      | 1         | 1.02%   |
| MediaTek moto e22                                                 | 1         | 1.02%   |
| MediaTek M40Air_EEA                                               | 1         | 1.02%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection I218-LM                                 | 1         | 1.02%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.02%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.02%   |
| Huawei MAR-LX1M                                                   | 1         | 1.02%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.02%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 118       | 57%     |
| Ethernet | 88        | 42.51%  |
| Modem    | 1         | 0.48%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 70        | 57.38%  |
| Ethernet | 52        | 42.62%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 72        | 60%     |
| 1     | 45        | 37.5%   |
| 0     | 3         | 2.5%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 113       | 91.87%  |
| Yes  | 10        | 8.13%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 50        | 47.62%  |
| Realtek Semiconductor           | 31        | 29.52%  |
| Broadcom                        | 9         | 8.57%   |
| Qualcomm Atheros Communications | 3         | 2.86%   |
| Foxconn / Hon Hai               | 3         | 2.86%   |
| Realtek                         | 2         | 1.9%    |
| Ralink                          | 2         | 1.9%    |
| IMC Networks                    | 2         | 1.9%    |
| Opticis                         | 1         | 0.95%   |
| Lite-On Technology              | 1         | 0.95%   |
| Hewlett-Packard                 | 1         | 0.95%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 27        | 25.71%  |
| Intel Bluetooth Device                         | 20        | 19.05%  |
| Intel Bluetooth wireless interface             | 18        | 17.14%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 11        | 10.48%  |
| Realtek  Bluetooth 4.2 Adapter                 | 4         | 3.81%   |
| Realtek Bluetooth Radio                        | 2         | 1.9%    |
| Ralink RT3290 Bluetooth                        | 2         | 1.9%    |
| Qualcomm Atheros  Bluetooth Device             | 2         | 1.9%    |
| IMC Networks Bluetooth Radio                   | 2         | 1.9%    |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 2         | 1.9%    |
| Qualcomm Atheros AR3011 Bluetooth              | 1         | 0.95%   |
| Opticis Bluetooth Radio                        | 1         | 0.95%   |
| Lite-On Wireless_Device                        | 1         | 0.95%   |
| Intel AX200 Bluetooth                          | 1         | 0.95%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 0.95%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 0.95%   |
| Broadcom HP Portable Valentine                 | 1         | 0.95%   |
| Broadcom HP Portable SoftSailing               | 1         | 0.95%   |
| Broadcom HP Portable Bumble Bee                | 1         | 0.95%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 0.95%   |
| Broadcom BCM20702A0 Bluetooth                  | 1         | 0.95%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]     | 1         | 0.95%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR           | 1         | 0.95%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 0.95%   |
| Broadcom BCM2045 Bluetooth                     | 1         | 0.95%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 93        | 70.45%  |
| AMD                    | 27        | 20.45%  |
| Nvidia                 | 8         | 6.06%   |
| Zhaoxin                | 1         | 0.76%   |
| MosArt Semiconductor   | 1         | 0.76%   |
| GN Netcom              | 1         | 0.76%   |
| Generalplus Technology | 1         | 0.76%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP High Definition Audio Controller                                            | 30        | 18.63%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 22        | 13.66%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 17        | 10.56%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 15        | 9.32%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 12        | 7.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 7         | 4.35%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 6         | 3.73%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 3         | 1.86%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 3         | 1.86%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.86%   |
| Intel 8 Series HD Audio Controller                                                                | 3         | 1.86%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 3         | 1.86%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 3         | 1.86%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 1.86%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.24%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.24%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.24%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.24%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.24%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.62%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G/KH-40000 High Definition Audio Controller                 | 1         | 0.62%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.62%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.62%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.62%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.62%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.62%   |
| Nvidia Audio device                                                                               | 1         | 0.62%   |
| MosArt Semiconductor MosArt USB Audio Device                                                      | 1         | 0.62%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.62%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.62%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.62%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.62%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.62%   |
| GN Netcom Jabra EVOLVE 20 SE MS                                                                   | 1         | 0.62%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.62%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 1         | 0.62%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.62%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 0.62%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.62%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.62%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 50        | 37.88%  |
| SK hynix                                | 22        | 16.67%  |
| Micron Technology                       | 15        | 11.36%  |
| Foxline                                 | 10        | 7.58%   |
| Crucial                                 | 7         | 5.3%    |
| Kingston                                | 5         | 3.79%   |
| Unknown                                 | 3         | 2.27%   |
| Ramaxel Technology                      | 3         | 2.27%   |
| Unknown (ABCD)                          | 2         | 1.52%   |
| Silicon Power Computer & Communications | 2         | 1.52%   |
| Elpida                                  | 2         | 1.52%   |
| A-DATA Technology                       | 2         | 1.52%   |
| Silicon Power                           | 1         | 0.76%   |
| SHARETRONIC                             | 1         | 0.76%   |
| Qumo                                    | 1         | 0.76%   |
| Patriot                                 | 1         | 0.76%   |
| King Tiger                              | 1         | 0.76%   |
| Hikvision                               | 1         | 0.76%   |
| ChangXin Memory                         | 1         | 0.76%   |
| <Invalid>                               | 1         | 0.76%   |
| Unknown                                 | 1         | 0.76%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 12.14%  |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 5         | 3.57%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 4         | 2.86%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 3         | 2.14%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.14%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.14%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 2.14%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 2.14%   |
| Foxline RAM FL3200D4S22-8G 8GB SODIMM DDR4 3200MT/s              | 3         | 2.14%   |
| Foxline RAM FL2666D4S19-8G ]. 8GB SODIMM DDR4 2667MT/s           | 3         | 2.14%   |
| Foxline RAM FL2400D4S17S-8G 8GB SODIMM DDR4 2400MT/s             | 3         | 2.14%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.43%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 2         | 1.43%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.43%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.43%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.43%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 1.43%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.43%   |
| Silicon Power & RAM Module 8GB SODIMM DDR4 3200MT/s              | 2         | 1.43%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 2         | 1.43%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.43%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.43%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.43%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.43%   |
| Micron RAM 8ATF2G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 2         | 1.43%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s           | 2         | 1.43%   |
| Crucial RAM CT8G4SFS832A.C8FN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.43%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.43%   |
| Unknown RAM Module 4GB Chip DDR4 2133MT/s                        | 1         | 0.71%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.71%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 0.71%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM DDR2 975MT/s            | 1         | 0.71%   |
| SK hynix RAM HMT41GS6MFR8C-H9 8GB SODIMM DDR3 1333MT/s           | 1         | 0.71%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.71%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.71%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.71%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.71%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.71%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 0.71%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 92        | 79.31%  |
| DDR3   | 17        | 14.66%  |
| LPDDR4 | 3         | 2.59%   |
| DDR2   | 2         | 1.72%   |
| LPDDR5 | 1         | 0.86%   |
| LPDDR3 | 1         | 0.86%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 105       | 84%     |
| Row Of Chips | 18        | 14.4%   |
| DIMM         | 1         | 0.8%    |
| Chip         | 1         | 0.8%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 73        | 58.4%   |
| 4096  | 32        | 25.6%   |
| 16384 | 10        | 8%      |
| 2048  | 7         | 5.6%    |
| 1024  | 3         | 2.4%    |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 51        | 42.15%  |
| 2667  | 34        | 28.1%   |
| 1600  | 12        | 9.92%   |
| 2400  | 8         | 6.61%   |
| 1333  | 3         | 2.48%   |
| 3266  | 2         | 1.65%   |
| 2133  | 2         | 1.65%   |
| 1334  | 2         | 1.65%   |
| 6400  | 1         | 0.83%   |
| 3733  | 1         | 0.83%   |
| 2666  | 1         | 0.83%   |
| 1866  | 1         | 0.83%   |
| 1066  | 1         | 0.83%   |
| 975   | 1         | 0.83%   |
| 667   | 1         | 0.83%   |

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
| Chicony Electronics                    | 24        | 20.34%  |
| Syntek                                 | 20        | 16.95%  |
| IMC Networks                           | 16        | 13.56%  |
| Bison Electronics                      | 14        | 11.86%  |
| Quanta                                 | 7         | 5.93%   |
| Sunplus Innovation Technology          | 5         | 4.24%   |
| Microdia                               | 5         | 4.24%   |
| Realtek Semiconductor                  | 4         | 3.39%   |
| Luxvisions Innotech Limited            | 4         | 3.39%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.39%   |
| Acer                                   | 3         | 2.54%   |
| USB Camera CS                          | 2         | 1.69%   |
| Suyin                                  | 2         | 1.69%   |
| SunplusIT                              | 2         | 1.69%   |
| Sonix Technology                       | 2         | 1.69%   |
| Primax Electronics                     | 1         | 0.85%   |
| GEMBIRD                                | 1         | 0.85%   |
| Alcor Micro                            | 1         | 0.85%   |
| Unknown                                | 1         | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 19        | 16.1%   |
| Chicony USB camera                                  | 10        | 8.47%   |
| IMC Networks Integrated Camera                      | 6         | 5.08%   |
| Bison Integrated Camera                             | 6         | 5.08%   |
| IMC Networks ov9734_azurewave_camera                | 4         | 3.39%   |
| Chicony Integrated Camera                           | 4         | 3.39%   |
| Sunplus Integrated_Webcam_HD                        | 3         | 2.54%   |
| IMC Networks HD Camera                              | 3         | 2.54%   |
| USB Camera CS USB Camera CS                         | 2         | 1.69%   |
| Sonix USB 2.0 Camera                                | 2         | 1.69%   |
| Realtek Integrated_Webcam_HD                        | 2         | 1.69%   |
| Quanta HP Webcam                                    | 2         | 1.69%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.69%   |
| Microdia Webcam Vitade AF                           | 2         | 1.69%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 1.69%   |
| Chicony USB2.0 Camera                               | 2         | 1.69%   |
| Chicony HD User Facing                              | 2         | 1.69%   |
| Bison HD Webcam                                     | 2         | 1.69%   |
| Bison BisonCam,NB Pro                               | 2         | 1.69%   |
| Acer BisonCam,NB Pro                                | 2         | 1.69%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.85%   |
| Suyin HP Truevision HD                              | 1         | 0.85%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.85%   |
| SunplusIT XiaoMi USB 2.0 Webcam                     | 1         | 0.85%   |
| SunplusIT MTD camera                                | 1         | 0.85%   |
| Sunplus BKX Usb FHD Camera                          | 1         | 0.85%   |
| Sunplus ASUS USB2.0 Webcam                          | 1         | 0.85%   |
| Realtek USB Camera                                  | 1         | 0.85%   |
| Realtek HP Truevision HD                            | 1         | 0.85%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 0.85%   |
| Quanta USB HD Webcam                                | 1         | 0.85%   |
| Quanta HD Camera                                    | 1         | 0.85%   |
| Primax HP HD Webcam [Fixed]                         | 1         | 0.85%   |
| Microdia USB Camera                                 | 1         | 0.85%   |
| Microdia Integrated_Webcam_HD                       | 1         | 0.85%   |
| Microdia Integrated Webcam                          | 1         | 0.85%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.85%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 0.85%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 0.85%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 0.85%   |

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
| 0     | 81        | 66.39%  |
| 1     | 32        | 26.23%  |
| 2     | 9         | 7.38%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 15        | 31.91%  |
| Fingerprint reader    | 14        | 29.79%  |
| Net/wireless          | 12        | 25.53%  |
| Bluetooth             | 2         | 4.26%   |
| Sound                 | 1         | 2.13%   |
| Net/ethernet          | 1         | 2.13%   |
| Multimedia controller | 1         | 2.13%   |
| Chipcard              | 1         | 2.13%   |

