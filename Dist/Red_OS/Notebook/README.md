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

Total: 173

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Red OS 7.3.1 | 44        | 38.6%   |
| Red OS 7.3.2 | 41        | 35.96%  |
| Red OS 7.3   | 28        | 24.56%  |
| Red OS 7.2   | 1         | 0.88%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Red OS | 109       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                 | Notebooks | Percent |
|-------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64    | 25        | 20.83%  |
| 5.15.72-1.el7.3.x86_64  | 23        | 19.17%  |
| 5.15.87-1.el7.3.x86_64  | 13        | 10.83%  |
| 5.15.35-4.el7.3.x86_64  | 10        | 8.33%   |
| 5.10.29-1.el7.x86_64    | 10        | 8.33%   |
| 5.15.35-1.el7.3.x86_64  | 6         | 5%      |
| 6.1.20-2.el7.3.x86_64   | 4         | 3.33%   |
| 5.15.35-5.el7.3.x86_64  | 4         | 3.33%   |
| 5.15.78-2.el7.3.x86_64  | 3         | 2.5%    |
| 5.15.125-1.el7.3.x86_64 | 3         | 2.5%    |
| 5.10.1-1.el7.x86_64     | 3         | 2.5%    |
| 6.1.38-2.el7.3.x86_64   | 2         | 1.67%   |
| 5.15.10-4.el7.x86_64    | 2         | 1.67%   |
| 5.10.29-3.el7.x86_64    | 2         | 1.67%   |
| 5.10.24-2.el7.x86_64    | 2         | 1.67%   |
| 6.1.44-1.el7.3.x86_64   | 1         | 0.83%   |
| 5.18.1-1.el7.x86_64     | 1         | 0.83%   |
| 5.15.120                | 1         | 0.83%   |
| 5.15.10-3.el7.x86_64    | 1         | 0.83%   |
| 5.15.10-2.el7.x86_64    | 1         | 0.83%   |
| 5.13.15-1.el7.x86_64    | 1         | 0.83%   |
| 5.10.24-1.el7.x86_64    | 1         | 0.83%   |
| 4.19.79-1.el7.x86_64    | 1         | 0.83%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.10  | 29        | 24.37%  |
| 5.15.72  | 23        | 19.33%  |
| 5.15.35  | 19        | 15.97%  |
| 5.15.87  | 13        | 10.92%  |
| 5.10.29  | 12        | 10.08%  |
| 6.1.20   | 4         | 3.36%   |
| 5.15.78  | 3         | 2.52%   |
| 5.15.125 | 3         | 2.52%   |
| 5.10.24  | 3         | 2.52%   |
| 5.10.1   | 3         | 2.52%   |
| 6.1.38   | 2         | 1.68%   |
| 6.1.44   | 1         | 0.84%   |
| 5.18.1   | 1         | 0.84%   |
| 5.15.120 | 1         | 0.84%   |
| 5.13.15  | 1         | 0.84%   |
| 4.19.79  | 1         | 0.84%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 86        | 76.11%  |
| 5.10    | 17        | 15.04%  |
| 6.1     | 7         | 6.19%   |
| 5.18    | 1         | 0.88%   |
| 5.13    | 1         | 0.88%   |
| 4.19    | 1         | 0.88%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 109       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 95        | 86.36%  |
| Cinnamon   | 12        | 10.91%  |
| X-Cinnamon | 3         | 2.73%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 105       | 94.59%  |
| Wayland | 6         | 5.41%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 103       | 91.96%  |
| SDDM    | 4         | 3.57%   |
| Unknown | 3         | 2.68%   |
| LightDM | 2         | 1.79%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 63.39%  |
| ru_RU   | 40        | 35.71%  |
| en_US   | 1         | 0.89%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 96        | 86.49%  |
| BIOS | 15        | 13.51%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 106       | 96.36%  |
| Btrfs   | 2         | 1.82%   |
| Xfs     | 1         | 0.91%   |
| Overlay | 1         | 0.91%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 95        | 86.36%  |
| MBR     | 12        | 10.91%  |
| Unknown | 3         | 2.73%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 99        | 90%     |
| Yes       | 11        | 10%     |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 83        | 74.11%  |
| Yes       | 29        | 25.89%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 39        | 35.78%  |
| Hewlett-Packard                | 16        | 14.68%  |
| ICL                            | 7         | 6.42%   |
| MSI                            | 5         | 4.59%   |
| HUAWEI                         | 5         | 4.59%   |
| Dell                           | 4         | 3.67%   |
| ASUSTek Computer               | 4         | 3.67%   |
| Aquarius                       | 4         | 3.67%   |
| Kraftway                       | 3         | 2.75%   |
| Digma                          | 3         | 2.75%   |
| Acer                           | 3         | 2.75%   |
| IP3 Technology                 | 2         | 1.83%   |
| HONOR                          | 2         | 1.83%   |
| Gigabyte Technology            | 2         | 1.83%   |
| 3Logic Group                   | 2         | 1.83%   |
| Timi                           | 1         | 0.92%   |
| THUNDEROBOT                    | 1         | 0.92%   |
| Shanghai Zhaoxin Semiconductor | 1         | 0.92%   |
| Pegatron                       | 1         | 0.92%   |
| mtech                          | 1         | 0.92%   |
| iRU                            | 1         | 0.92%   |
| Graviton                       | 1         | 0.92%   |
| Unknown                        | 1         | 0.92%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE                  | 17        | 15.6%   |
| Lenovo ThinkBook 15 G3 ACL 21A4      | 3         | 2.75%   |
| Kraftway ACCORD                      | 3         | 2.75%   |
| ICL RAYbook Si1512                   | 3         | 2.75%   |
| HP Laptop 15s-eq1xxx                 | 3         | 2.75%   |
| IP3 ACN30                            | 2         | 1.83%   |
| Unknown                              | 2         | 1.83%   |
| Timi Redmi Book Pro 15 2022          | 1         | 0.92%   |
| THUNDEROBOT 911AirD                  | 1         | 0.92%   |
| Shanghai Zhaoxin ZXE CRB             | 1         | 0.92%   |
| Pegatron A35                         | 1         | 0.92%   |
| mtech MTL1578                        | 1         | 0.92%   |
| MSI Sword 15 A12UE                   | 1         | 0.92%   |
| MSI Modern 15 B12M                   | 1         | 0.92%   |
| MSI Modern 14 C12M                   | 1         | 0.92%   |
| MSI GL62 6QF                         | 1         | 0.92%   |
| MSI FX610                            | 1         | 0.92%   |
| Lenovo V130-15IKB 81HN               | 1         | 0.92%   |
| Lenovo ThinkPad X220 4290RB3         | 1         | 0.92%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2DE00 | 1         | 0.92%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2DD00 | 1         | 0.92%   |
| Lenovo ThinkPad E15 Gen 4 21E6009UGP | 1         | 0.92%   |
| Lenovo ThinkPad E15 Gen 4 21E60061RT | 1         | 0.92%   |
| Lenovo ThinkBook 15 G2 ITL 20VE      | 1         | 0.92%   |
| Lenovo ThinkBook 15 G2 ARE 20VG      | 1         | 0.92%   |
| Lenovo ThinkBook 14-IIL 20SL         | 1         | 0.92%   |
| Lenovo IdeaPad L340-15IWL 81LG       | 1         | 0.92%   |
| Lenovo IdeaPad L340-15API 81LW       | 1         | 0.92%   |
| Lenovo IdeaPad 700-15ISK 80RU        | 1         | 0.92%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7     | 1         | 0.92%   |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 1         | 0.92%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 0.92%   |
| Lenovo IdeaPad 3 15ITL05 81X8        | 1         | 0.92%   |
| Lenovo IdeaPad 1 15ALC7 82R4         | 1         | 0.92%   |
| Lenovo G570 20079                    | 1         | 0.92%   |
| Lenovo B590 20208                    | 1         | 0.92%   |
| iRU 15ALC                            | 1         | 0.92%   |
| ICL Si1407                           | 1         | 0.92%   |
| ICL S1511 G1R                        | 1         | 0.92%   |
| ICL RAYbook Si1514                   | 1         | 0.92%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo V15-IWL       | 17        | 15.6%   |
| Lenovo IdeaPad       | 8         | 7.34%   |
| Lenovo ThinkBook     | 6         | 5.5%    |
| HP Laptop            | 6         | 5.5%    |
| Lenovo ThinkPad      | 5         | 4.59%   |
| ICL RAYbook          | 4         | 3.67%   |
| Kraftway ACCORD      | 3         | 2.75%   |
| HP ProBook           | 3         | 2.75%   |
| Digma EVE            | 3         | 2.75%   |
| MSI Modern           | 2         | 1.83%   |
| IP3 ACN30            | 2         | 1.83%   |
| HP Pavilion          | 2         | 1.83%   |
| Gigabyte G5          | 2         | 1.83%   |
| Dell Vostro          | 2         | 1.83%   |
| Aquarius NS685U      | 2         | 1.83%   |
| Acer Aspire          | 2         | 1.83%   |
| Unknown              | 2         | 1.83%   |
| Timi Redmi           | 1         | 0.92%   |
| THUNDEROBOT 911AirD  | 1         | 0.92%   |
| Shanghai Zhaoxin ZXE | 1         | 0.92%   |
| Pegatron A35         | 1         | 0.92%   |
| mtech MTL1578        | 1         | 0.92%   |
| MSI Sword            | 1         | 0.92%   |
| MSI GL62             | 1         | 0.92%   |
| MSI FX610            | 1         | 0.92%   |
| Lenovo V130-15IKB    | 1         | 0.92%   |
| Lenovo G570          | 1         | 0.92%   |
| Lenovo B590          | 1         | 0.92%   |
| iRU 15ALC            | 1         | 0.92%   |
| ICL Si1407           | 1         | 0.92%   |
| ICL S1511            | 1         | 0.92%   |
| HUAWEI NBLK-WAX9X    | 1         | 0.92%   |
| HUAWEI NBD-WXX9      | 1         | 0.92%   |
| HUAWEI BOHL-WXX9     | 1         | 0.92%   |
| HUAWEI BOD-WXX9      | 1         | 0.92%   |
| HUAWEI BDZ-WXX9      | 1         | 0.92%   |
| HONOR NBR-WAX9       | 1         | 0.92%   |
| HONOR BMH-WCX9       | 1         | 0.92%   |
| HP OMEN              | 1         | 0.92%   |
| HP Notebook          | 1         | 0.92%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 30        | 27.52%  |
| 2021 | 22        | 20.18%  |
| 2022 | 18        | 16.51%  |
| 2020 | 14        | 12.84%  |
| 2012 | 8         | 7.34%   |
| 2010 | 5         | 4.59%   |
| 2017 | 3         | 2.75%   |
| 2011 | 3         | 2.75%   |
| 2018 | 2         | 1.83%   |
| 2016 | 1         | 0.92%   |
| 2015 | 1         | 0.92%   |
| 2013 | 1         | 0.92%   |
| 2007 | 1         | 0.92%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 109       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 109       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 109       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 66        | 60.55%  |
| 16.01-24.0 | 15        | 13.76%  |
| 3.01-4.0   | 14        | 12.84%  |
| 8.01-16.0  | 11        | 10.09%  |
| 2.01-3.0   | 2         | 1.83%   |
| 32.01-64.0 | 1         | 0.92%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 68        | 59.65%  |
| 2.01-3.0  | 26        | 22.81%  |
| 0.51-1.0  | 9         | 7.89%   |
| 3.01-4.0  | 6         | 5.26%   |
| 4.01-8.0  | 3         | 2.63%   |
| 8.01-16.0 | 2         | 1.75%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 96        | 85.71%  |
| 2      | 11        | 9.82%   |
| 3      | 4         | 3.57%   |
| 4      | 1         | 0.89%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 92        | 83.64%  |
| Yes       | 18        | 16.36%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 77        | 70.64%  |
| No        | 32        | 29.36%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 108       | 99.08%  |
| No        | 1         | 0.92%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 95        | 87.16%  |
| No        | 14        | 12.84%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 108       | 99.08%  |
| Ukraine | 1         | 0.92%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 27        | 23.89%  |
| Salekhard        | 22        | 19.47%  |
| Murom            | 16        | 14.16%  |
| St Petersburg    | 5         | 4.42%   |
| Perm             | 4         | 3.54%   |
| Yakutsk          | 3         | 2.65%   |
| Vladimir         | 3         | 2.65%   |
| Ryazan           | 3         | 2.65%   |
| Krasnodar        | 3         | 2.65%   |
| Yekaterinburg    | 2         | 1.77%   |
| Novy Urengoy     | 2         | 1.77%   |
| Nizhniy Novgorod | 2         | 1.77%   |
| Kursk            | 2         | 1.77%   |
| Yaroslavl        | 1         | 0.88%   |
| Volzhskiy        | 1         | 0.88%   |
| Vladivostok      | 1         | 0.88%   |
| Ulyanovsk        | 1         | 0.88%   |
| Tver             | 1         | 0.88%   |
| Strezhevoy       | 1         | 0.88%   |
| Sevastopol       | 1         | 0.88%   |
| Saratov          | 1         | 0.88%   |
| Omsk             | 1         | 0.88%   |
| Novosibirsk      | 1         | 0.88%   |
| Novokuybyshevsk  | 1         | 0.88%   |
| Muromskiy        | 1         | 0.88%   |
| Krasnoyarsk      | 1         | 0.88%   |
| Kirzhach         | 1         | 0.88%   |
| Khabarovsk       | 1         | 0.88%   |
| Kaluga           | 1         | 0.88%   |
| Borinskoye       | 1         | 0.88%   |
| Belgorod         | 1         | 0.88%   |
| Balashikha       | 1         | 0.88%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 28        | 40     | 22.4%   |
| WDC                 | 16        | 19     | 12.8%   |
| SK hynix            | 10        | 12     | 8%      |
| Seagate             | 7         | 8      | 5.6%    |
| A-DATA Technology   | 7         | 7      | 5.6%    |
| Toshiba             | 5         | 20     | 4%      |
| Micron Technology   | 5         | 9      | 4%      |
| Foxline             | 5         | 5      | 4%      |
| Silicon Motion      | 4         | 4      | 3.2%    |
| HGST                | 4         | 4      | 3.2%    |
| Unknown             | 3         | 3      | 2.4%    |
| Phison              | 3         | 3      | 2.4%    |
| Intel               | 3         | 3      | 2.4%    |
| Gigabyte Technology | 3         | 3      | 2.4%    |
| YMTC                | 2         | 2      | 1.6%    |
| UMIS                | 2         | 2      | 1.6%    |
| Kingston            | 2         | 2      | 1.6%    |
| Crucial             | 2         | 2      | 1.6%    |
| China               | 2         | 3      | 1.6%    |
| Transcend           | 1         | 1      | 0.8%    |
| SPCC Sol            | 1         | 1      | 0.8%    |
| SanDisk             | 1         | 1      | 0.8%    |
| Netac               | 1         | 1      | 0.8%    |
| KIOXIA              | 1         | 1      | 0.8%    |
| KingSpec            | 1         | 1      | 0.8%    |
| Kimtigo             | 1         | 2      | 0.8%    |
| JMicron Technology  | 1         | 1      | 0.8%    |
| ITHOO               | 1         | 1      | 0.8%    |
| HUAWEI              | 1         | 1      | 0.8%    |
| Apacer              | 1         | 2      | 0.8%    |
| Unknown             | 1         | 1      | 0.8%    |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Notebooks | Percent |
|----------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB       | 18        | 14.06%  |
| Foxline FLSSD256M80E13TCX5 256GB       | 5         | 3.91%   |
| Silicon Motion Wodposit NVMe SSD 256GB | 4         | 3.13%   |
| WDC WD10SPZX-00Z10T0 1TB               | 2         | 1.56%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB   | 2         | 1.56%   |
| Toshiba MQ01ABF050 500GB               | 2         | 1.56%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB | 2         | 1.56%   |
| SK hynix PC711 HFS512GDE9X073N 512GB   | 2         | 1.56%   |
| Seagate ST1000LM035-1RK172 1TB         | 2         | 1.56%   |
| Samsung MZALQ512HALU-000L2 512GB       | 2         | 1.56%   |
| Samsung MZALQ256HBJD-00BL2 256GB       | 2         | 1.56%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB       | 2         | 1.56%   |
| A-DATA SU650 240GB SSD                 | 2         | 1.56%   |
| YMTC PC210-512GB-B                     | 1         | 0.78%   |
| YMTC PC005 512GB                       | 1         | 0.78%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 1         | 0.78%   |
| WDC WDS250G2B0A-00SM50 250GB SSD       | 1         | 0.78%   |
| WDC WD5000BPVT-55HXZT3 500GB           | 1         | 0.78%   |
| WDC WD3200BPVT-24JJ5T0 320GB           | 1         | 0.78%   |
| WDC WD2500BEVT-22ZCT0 250GB            | 1         | 0.78%   |
| WDC WD10SPZX-24Z10 1TB                 | 1         | 0.78%   |
| WDC WD10JPVX-22JC3T0 1TB               | 1         | 0.78%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB   | 1         | 0.78%   |
| WDC PC SN530 SDBPNPZ-512G-1006 512GB   | 1         | 0.78%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB   | 1         | 0.78%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB   | 1         | 0.78%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB   | 1         | 0.78%   |
| Unknown SLD128  128GB                  | 1         | 0.78%   |
| Unknown NVMe SSD Drive 512GB           | 1         | 0.78%   |
| Unknown 58K722  128GB                  | 1         | 0.78%   |
| UMIS RPJTJ512MEE1OWX 512GB             | 1         | 0.78%   |
| UMIS RPJTJ256MGE1QDQ 256GB             | 1         | 0.78%   |
| Transcend TS240GMTS820S 240GB SSD      | 1         | 0.78%   |
| Toshiba MK5075GSX 500GB                | 1         | 0.78%   |
| Toshiba MK5059GSXP 500GB               | 1         | 0.78%   |
| Toshiba KXG60ZNV512G 512GB             | 1         | 0.78%   |
| Toshiba KXG60ZNV256G 256GB             | 1         | 0.78%   |
| SPCC Sol id State Disk 128GB SSD       | 1         | 0.78%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB | 1         | 0.78%   |
| SK hynix SKHynix_HFS256GDE9X081N 256GB | 1         | 0.78%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 7         | 10     | 33.33%  |
| Seagate | 7         | 8      | 33.33%  |
| HGST    | 4         | 4      | 19.05%  |
| Toshiba | 3         | 17     | 14.29%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 4         | 4      | 19.05%  |
| WDC                 | 2         | 2      | 9.52%   |
| Samsung Electronics | 2         | 2      | 9.52%   |
| Crucial             | 2         | 2      | 9.52%   |
| China               | 2         | 3      | 9.52%   |
| Transcend           | 1         | 1      | 4.76%   |
| SPCC Sol            | 1         | 1      | 4.76%   |
| SanDisk             | 1         | 1      | 4.76%   |
| Netac               | 1         | 1      | 4.76%   |
| Micron Technology   | 1         | 1      | 4.76%   |
| Kingston            | 1         | 1      | 4.76%   |
| KingSpec            | 1         | 1      | 4.76%   |
| JMicron Technology  | 1         | 1      | 4.76%   |
| Apacer              | 1         | 2      | 4.76%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 77        | 98     | 62.6%   |
| SSD     | 21        | 23     | 17.07%  |
| HDD     | 20        | 39     | 16.26%  |
| MMC     | 3         | 3      | 2.44%   |
| Unknown | 2         | 2      | 1.63%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 77        | 98     | 64.71%  |
| SATA | 36        | 59     | 30.25%  |
| SAS  | 3         | 5      | 2.52%   |
| MMC  | 3         | 3      | 2.52%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 28        | 46     | 70%     |
| 0.51-1.0   | 11        | 14     | 27.5%   |
| 1.01-2.0   | 1         | 2      | 2.5%    |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 57        | 50.44%  |
| 251-500    | 28        | 24.78%  |
| 501-1000   | 10        | 8.85%   |
| 51-100     | 8         | 7.08%   |
| 1001-2000  | 6         | 5.31%   |
| 1-20       | 3         | 2.65%   |
| 21-50      | 1         | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 82        | 71.93%  |
| 21-50     | 18        | 15.79%  |
| 101-250   | 4         | 3.51%   |
| 51-100    | 4         | 3.51%   |
| 501-1000  | 3         | 2.63%   |
| 251-500   | 2         | 1.75%   |
| 1001-2000 | 1         | 0.88%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 11.11%  |
| Toshiba MQ01ABF050 500GB            | 1         | 10     | 11.11%  |
| Toshiba MK5075GSX 500GB             | 1         | 4      | 11.11%  |
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
| Toshiba           | 2         | 15     | 25%     |
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
| Toshiba | 2         | 15     | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 19     | 75%     |
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
| Works    | 99        | 130    | 86.09%  |
| Detected | 8         | 14     | 6.96%   |
| Malfunc  | 8         | 21     | 6.96%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 75        | 45.73%  |
| Samsung Electronics          | 26        | 15.85%  |
| AMD                          | 13        | 7.93%   |
| Phison Electronics           | 11        | 6.71%   |
| SK hynix                     | 10        | 6.1%    |
| SanDisk                      | 7         | 4.27%   |
| Silicon Motion               | 4         | 2.44%   |
| Micron Technology            | 4         | 2.44%   |
| Yangtze Memory Technologies  | 2         | 1.22%   |
| Union Memory (Shenzhen)      | 2         | 1.22%   |
| Toshiba America Info Systems | 2         | 1.22%   |
| ADATA Technology             | 2         | 1.22%   |
| Zhaoxin                      | 1         | 0.61%   |
| ShenZhen TIGO Semiconductor  | 1         | 0.61%   |
| Realtek Semiconductor        | 1         | 0.61%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.61%   |
| KIOXIA                       | 1         | 0.61%   |
| Kingston Technology Company  | 1         | 0.61%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                        | Notebooks | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                            | 30        | 17.34%  |
| Samsung NVMe SSD Controller 980                                              | 25        | 14.45%  |
| AMD FCH SATA Controller [AHCI mode]                                          | 11        | 6.36%   |
| Phison PS5013 E13 NVMe Controller                                            | 9         | 5.2%    |
| Intel Volume Management Device NVMe RAID Controller                          | 8         | 4.62%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                         | 7         | 4.05%   |
| Intel Tiger Lake-LP SATA Controller                                          | 7         | 4.05%   |
| SanDisk WD Blue SN550 NVMe SSD                                               | 5         | 2.89%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]             | 5         | 2.89%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers            | 4         | 2.31%   |
| Intel Alder Lake-P SATA AHCI Controller                                      | 4         | 2.31%   |
| SK hynix BC511 NVMe SSD                                                      | 3         | 1.73%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                        | 3         | 1.73%   |
| Intel Comet Lake SATA AHCI Controller                                        | 3         | 1.73%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller     | 3         | 1.73%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                         | 2         | 1.16%   |
| Phison E16 PCIe4 NVMe Controller                                             | 2         | 1.16%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                  | 2         | 1.16%   |
| Intel Tiger Lake SATA AHCI Controller                                        | 2         | 1.16%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                           | 2         | 1.16%   |
| Intel SSD 660P Series                                                        | 2         | 1.16%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                 | 2         | 1.16%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller | 2         | 1.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                            | 2         | 1.16%   |
| ADATA ADATA XPG GAMMIXS1 1L Media (256 GB SSD)                               | 2         | 1.16%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G StorX AHCI Controller                 | 1         | 0.58%   |
| Yangtze Memory PC210 NVMe SSD                                                | 1         | 0.58%   |
| Yangtze Memory PC005 NVMe SSD                                                | 1         | 0.58%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 NVMe SSD 256GB                        | 1         | 0.58%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                        | 1         | 0.58%   |
| ShenZhen TIGO kimtigo NVMe SSD (DRAM-less)                                   | 1         | 0.58%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                        | 1         | 0.58%   |
| SanDisk PC SN520 NVMe SSD                                                    | 1         | 0.58%   |
| Samsung NVMe SSD Controller PM9B1                                            | 1         | 0.58%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                               | 1         | 0.58%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                            | 1         | 0.58%   |
| Micron 2400 NVMe SSD (DRAM-less)                                             | 1         | 0.58%   |
| Micron 2200S NVMe SSD [Cassandra]                                            | 1         | 0.58%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                 | 1         | 0.58%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                   | 1         | 0.58%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 83        | 48.54%  |
| NVMe | 77        | 45.03%  |
| RAID | 9         | 5.26%   |
| IDE  | 2         | 1.17%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 84        | 77.06%  |
| AMD          | 24        | 22.02%  |
| CentaurHauls | 1         | 0.92%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 16.51%  |
| Intel Core i5-8279U CPU @ 2.40GHz             | 6         | 5.5%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 5.5%    |
| Intel Core i5-8259U CPU @ 2.30GHz             | 5         | 4.59%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 3         | 2.75%   |
| Intel 12th Gen Core i5-1235U                  | 3         | 2.75%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 2.75%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 2.75%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 2.75%   |
| AMD Ryzen 3 5400U with Radeon Graphics        | 3         | 2.75%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 3         | 2.75%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 3         | 2.75%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 2         | 1.83%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 1.83%   |
| Intel 12th Gen Core i7-1255U                  | 2         | 1.83%   |
| Intel 12th Gen Core i5-12500H                 | 2         | 1.83%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.83%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.83%   |
| Intel Pentium Gold 7505 @ 2.00GHz             | 1         | 0.92%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.92%   |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 0.92%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 0.92%   |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 0.92%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 0.92%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 0.92%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 0.92%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 0.92%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.92%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 0.92%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 0.92%   |
| Intel Core i3-9300 CPU @ 3.70GHz              | 1         | 0.92%   |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 0.92%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 0.92%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 0.92%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 0.92%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 0.92%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 0.92%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 0.92%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 1         | 0.92%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 0.92%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Notebooks | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 41        | 37.61%  |
| Other              | 26        | 23.85%  |
| AMD Ryzen 5        | 10        | 9.17%   |
| Intel Core i3      | 9         | 8.26%   |
| AMD Ryzen 3        | 9         | 8.26%   |
| Intel Celeron      | 3         | 2.75%   |
| Intel Pentium      | 2         | 1.83%   |
| Intel Core i7      | 2         | 1.83%   |
| AMD Ryzen 7        | 2         | 1.83%   |
| AMD Phenom II      | 2         | 1.83%   |
| Intel Pentium Gold | 1         | 0.92%   |
| Intel Core 2 Duo   | 1         | 0.92%   |
| AMD A4             | 1         | 0.92%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 65        | 59.63%  |
| 2      | 22        | 20.18%  |
| 6      | 10        | 9.17%   |
| 10     | 5         | 4.59%   |
| 12     | 4         | 3.67%   |
| 14     | 1         | 0.92%   |
| 8      | 1         | 0.92%   |
| 3      | 1         | 0.92%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 109       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 90        | 82.57%  |
| 1      | 19        | 17.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 109       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 22        | 20%     |
| 0x806c1    | 13        | 11.82%  |
| 0x806ea    | 12        | 10.91%  |
| 0x906a4    | 6         | 5.45%   |
| 0x08608103 | 6         | 5.45%   |
| 0x906a3    | 5         | 4.55%   |
| 0x08600106 | 5         | 4.55%   |
| 0x306a9    | 4         | 3.64%   |
| 0x206a7    | 4         | 3.64%   |
| 0x0a50000c | 4         | 3.64%   |
| 0x806d1    | 2         | 1.82%   |
| 0x506e3    | 2         | 1.82%   |
| 0x506ca    | 2         | 1.82%   |
| 0x40651    | 2         | 1.82%   |
| 0x08108102 | 2         | 1.82%   |
| 0x010000c8 | 2         | 1.82%   |
| Unknown    | 2         | 1.82%   |
| 0xa0660    | 1         | 0.91%   |
| 0x906eb    | 1         | 0.91%   |
| 0x906e9    | 1         | 0.91%   |
| 0x706e5    | 1         | 0.91%   |
| 0x6fa      | 1         | 0.91%   |
| 0x506c9    | 1         | 0.91%   |
| 0x406c4    | 1         | 0.91%   |
| 0x20655    | 1         | 0.91%   |
| 0x20652    | 1         | 0.91%   |
| 0x0a50000d | 1         | 0.91%   |
| 0x0a404101 | 1         | 0.91%   |
| 0x08600104 | 1         | 0.91%   |
| 0x08108109 | 1         | 0.91%   |
| 0x0810100b | 1         | 0.91%   |
| 0x06006705 | 1         | 0.91%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 33.94%  |
| TigerLake        | 13        | 11.93%  |
| Alderlake Hybrid | 11        | 10.09%  |
| Unknown          | 8         | 7.34%   |
| Zen 2            | 6         | 5.5%    |
| Zen 3            | 4         | 3.67%   |
| SandyBridge      | 4         | 3.67%   |
| IvyBridge        | 4         | 3.67%   |
| Zen+             | 3         | 2.75%   |
| Icelake          | 3         | 2.75%   |
| Goldmont         | 3         | 2.75%   |
| Westmere         | 2         | 1.83%   |
| Skylake          | 2         | 1.83%   |
| K10              | 2         | 1.83%   |
| Haswell          | 2         | 1.83%   |
| Zen              | 1         | 0.92%   |
| Silvermont       | 1         | 0.92%   |
| Excavator        | 1         | 0.92%   |
| Core             | 1         | 0.92%   |
| CometLake        | 1         | 0.92%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 83        | 63.85%  |
| AMD     | 27        | 20.77%  |
| Nvidia  | 19        | 14.62%  |
| Zhaoxin | 1         | 0.77%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 19        | 14.29%  |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 11        | 8.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 8         | 6.02%   |
| AMD Renoir                                                                | 6         | 4.51%   |
| AMD Lucienne                                                              | 6         | 4.51%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 5         | 3.76%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 5         | 3.76%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 4         | 3.01%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 3.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.01%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 3.01%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 2.26%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 2.26%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                              | 3         | 2.26%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.5%    |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 2         | 1.5%    |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.5%    |
| Intel HD Graphics 530                                                     | 2         | 1.5%    |
| Intel HD Graphics 500                                                     | 2         | 1.5%    |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.5%    |
| Zhaoxin ZX-E C-960 GPU                                                    | 1         | 0.75%   |
| Nvidia TU117M [GeForce MX550]                                             | 1         | 0.75%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.75%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.75%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.75%   |
| Nvidia GM108M [GeForce 920MX]                                             | 1         | 0.75%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.75%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.75%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.75%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.75%   |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 0.75%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.75%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                         | 1         | 0.75%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 0.75%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.75%   |
| Intel UHD Graphics 620                                                    | 1         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 0.75%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 0.75%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 63        | 57.8%   |
| 1 x AMD        | 21        | 19.27%  |
| Intel + Nvidia | 17        | 15.6%   |
| Intel + AMD    | 3         | 2.75%   |
| 2 x AMD        | 2         | 1.83%   |
| 1 x Zhaoxin    | 1         | 0.92%   |
| 1 x Nvidia     | 1         | 0.92%   |
| AMD + Nvidia   | 1         | 0.92%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 97        | 87.39%  |
| Unknown     | 11        | 9.91%   |
| Proprietary | 3         | 2.7%    |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 62.5%   |
| 1.01-2.0   | 18        | 16.07%  |
| 0.01-0.5   | 12        | 10.71%  |
| 3.01-4.0   | 6         | 5.36%   |
| 0.51-1.0   | 6         | 5.36%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 49        | 42.98%  |
| LG Display           | 15        | 13.16%  |
| Chimei Innolux       | 14        | 12.28%  |
| Samsung Electronics  | 8         | 7.02%   |
| AU Optronics         | 7         | 6.14%   |
| PANDA                | 5         | 4.39%   |
| Philips              | 3         | 2.63%   |
| NLE                  | 2         | 1.75%   |
| Acer                 | 2         | 1.75%   |
| ViewSonic            | 1         | 0.88%   |
| Toshiba              | 1         | 0.88%   |
| TMX                  | 1         | 0.88%   |
| RGT                  | 1         | 0.88%   |
| Lenovo               | 1         | 0.88%   |
| Iiyama               | 1         | 0.88%   |
| HUAWEI               | 1         | 0.88%   |
| Dell                 | 1         | 0.88%   |
| Ancor Communications | 1         | 0.88%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Notebooks | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 17        | 14.78%  |
| BOE LCD Monitor BOE09C5 1920x1080 341x192mm 15.4-inch                 | 9         | 7.83%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch      | 4         | 3.48%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch          | 3         | 2.61%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 2.61%   |
| BOE LCD Monitor BOE0936 1920x1080 344x194mm 15.5-inch                 | 3         | 2.61%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                 | 3         | 2.61%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 3         | 2.61%   |
| NLE Newline NLE0032 3840x2160 944x398mm 40.3-inch                     | 2         | 1.74%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 1.74%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 2         | 1.74%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                 | 2         | 1.74%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                  | 2         | 1.74%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.74%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch        | 2         | 1.74%   |
| ViewSonic PJ VSC9B34 1920x1080                                        | 1         | 0.87%   |
| Toshiba LCD Monitor LCD58EB 1280x800 261x163mm 12.1-inch              | 1         | 0.87%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch               | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch  | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 950x540mm 43.0-inch | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch | 1         | 0.87%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 890x500mm 40.2-inch | 1         | 0.87%   |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                 | 1         | 0.87%   |
| Philips PHL 275S1 PHL094B 2560x1440 597x336mm 27.0-inch               | 1         | 0.87%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                  | 1         | 0.87%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                   | 1         | 0.87%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch               | 1         | 0.87%   |
| PANDA LM116LF3L02 NCP000A 1920x1080 256x144mm 11.6-inch               | 1         | 0.87%   |
| PANDA LCD Monitor NCP0065 1920x1080 309x174mm 14.0-inch               | 1         | 0.87%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch               | 1         | 0.87%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch               | 1         | 0.87%   |
| LG Display LCD Monitor LGDD302 1366x768 277x156mm 12.5-inch           | 1         | 0.87%   |
| LG Display LCD Monitor LGD0671 1920x1080 382x215mm 17.3-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch          | 1         | 0.87%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch          | 1         | 0.87%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 82        | 77.36%  |
| 1366x768 (WXGA)    | 12        | 11.32%  |
| 3840x2160 (4K)     | 3         | 2.83%   |
| 1600x900 (HD+)     | 2         | 1.89%   |
| 3440x1440          | 1         | 0.94%   |
| 3200x2000          | 1         | 0.94%   |
| 2560x1440 (QHD)    | 1         | 0.94%   |
| 2240x1400          | 1         | 0.94%   |
| 1680x1050 (WSXGA+) | 1         | 0.94%   |
| 1280x800 (WXGA)    | 1         | 0.94%   |
| 1280x1024 (SXGA)   | 1         | 0.94%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 79        | 69.91%  |
| 14      | 6         | 5.31%   |
| 13      | 6         | 5.31%   |
| 21      | 3         | 2.65%   |
| 17      | 3         | 2.65%   |
| 84      | 2         | 1.77%   |
| 40      | 2         | 1.77%   |
| 24      | 2         | 1.77%   |
| 12      | 2         | 1.77%   |
| 54      | 1         | 0.88%   |
| 34      | 1         | 0.88%   |
| 27      | 1         | 0.88%   |
| 23      | 1         | 0.88%   |
| 22      | 1         | 0.88%   |
| 19      | 1         | 0.88%   |
| 11      | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 90        | 79.65%  |
| 501-600     | 4         | 3.54%   |
| 401-500     | 4         | 3.54%   |
| 351-400     | 4         | 3.54%   |
| 201-300     | 4         | 3.54%   |
| 1501-2000   | 2         | 1.77%   |
| 901-1000    | 2         | 1.77%   |
| 701-800     | 1         | 0.88%   |
| 1001-1500   | 1         | 0.88%   |
| Unknown     | 1         | 0.88%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 95        | 92.23%  |
| 16/10 | 4         | 3.88%   |
| 21/9  | 3         | 2.91%   |
| 5/4   | 1         | 0.97%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 79        | 69.91%  |
| 81-90          | 11        | 9.73%   |
| 201-250        | 7         | 6.19%   |
| More than 1000 | 3         | 2.65%   |
| 121-130        | 3         | 2.65%   |
| 61-70          | 2         | 1.77%   |
| 501-1000       | 2         | 1.77%   |
| 71-80          | 1         | 0.88%   |
| 51-60          | 1         | 0.88%   |
| 351-500        | 1         | 0.88%   |
| 301-350        | 1         | 0.88%   |
| 151-200        | 1         | 0.88%   |
| Unknown        | 1         | 0.88%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 80        | 72.07%  |
| 101-120       | 18        | 16.22%  |
| 51-100        | 7         | 6.31%   |
| 161-240       | 3         | 2.7%    |
| More than 240 | 1         | 0.9%    |
| 1-50          | 1         | 0.9%    |
| Unknown       | 1         | 0.9%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 85        | 77.98%  |
| 0     | 12        | 11.01%  |
| 2     | 11        | 10.09%  |
| 3     | 1         | 0.92%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 77        | 45.83%  |
| Intel                 | 53        | 31.55%  |
| Broadcom              | 8         | 4.76%   |
| Xiaomi                | 6         | 3.57%   |
| Qualcomm Atheros      | 6         | 3.57%   |
| MediaTek              | 5         | 2.98%   |
| TP-Link               | 2         | 1.19%   |
| Samsung Electronics   | 2         | 1.19%   |
| Ralink                | 2         | 1.19%   |
| Huawei Technologies   | 2         | 1.19%   |
| Ralink Technology     | 1         | 0.6%    |
| Qualcomm              | 1         | 0.6%    |
| OPPO Electronics      | 1         | 0.6%    |
| OKB SAPR              | 1         | 0.6%    |
| Broadcom Limited      | 1         | 0.6%    |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 18.23%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 26        | 12.81%  |
| Intel Wireless 7265                                               | 12        | 5.91%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 10        | 4.93%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 4.43%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 3.94%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 2.96%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 2.46%   |
| Intel Wireless 3165                                               | 4         | 1.97%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 1.97%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 3         | 1.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 1.48%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.48%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.48%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 1.48%   |
| Realtek 802.11n WLAN Adapter                                      | 3         | 1.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 3         | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.99%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 0.99%   |
| Intel Ethernet Controller I225-V                                  | 2         | 0.99%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 0.99%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 0.99%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 0.99%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.99%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                             | 1         | 0.49%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.49%   |
| TP-Link 802.11n NIC                                               | 1         | 0.49%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.49%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.49%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.49%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.49%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 0.49%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 50        | 44.25%  |
| Realtek Semiconductor | 43        | 38.05%  |
| Broadcom              | 7         | 6.19%   |
| Qualcomm Atheros      | 3         | 2.65%   |
| MediaTek              | 3         | 2.65%   |
| TP-Link               | 2         | 1.77%   |
| Ralink                | 2         | 1.77%   |
| Ralink Technology     | 1         | 0.88%   |
| Qualcomm              | 1         | 0.88%   |
| Broadcom Limited      | 1         | 0.88%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 26        | 22.61%  |
| Intel Wireless 7265                                            | 12        | 10.43%  |
| Intel Alder Lake-P PCH CNVi WiFi                               | 10        | 8.7%    |
| Intel Wi-Fi 6 AX201                                            | 9         | 7.83%   |
| Intel Wireless 3165                                            | 4         | 3.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 3.48%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 3         | 2.61%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 2.61%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.61%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 2.61%   |
| Realtek 802.11n WLAN Adapter                                   | 3         | 2.61%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 2.61%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 3         | 2.61%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 2.61%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.74%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.74%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.74%   |
| TP-Link TL-WN821N Version 5 RTL8192EU                          | 1         | 0.87%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.87%   |
| TP-Link 802.11n NIC                                            | 1         | 0.87%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.87%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.87%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.87%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.87%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.87%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 0.87%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.87%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.87%   |
| Intel Wireless 8265 / 8275                                     | 1         | 0.87%   |
| Intel Wi-Fi 6 AX200                                            | 1         | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.87%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 0.87%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 0.87%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.87%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 0.87%   |
| Broadcom BCM43228 802.11a/b/g/n                                | 1         | 0.87%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 0.87%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 49        | 57.65%  |
| Intel                 | 19        | 22.35%  |
| Xiaomi                | 6         | 7.06%   |
| Qualcomm Atheros      | 3         | 3.53%   |
| Samsung Electronics   | 2         | 2.35%   |
| MediaTek              | 2         | 2.35%   |
| OPPO Electronics      | 1         | 1.18%   |
| OKB SAPR              | 1         | 1.18%   |
| Huawei Technologies   | 1         | 1.18%   |
| Broadcom              | 1         | 1.18%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 37        | 42.53%  |
| Intel Ethernet Connection (6) I219-V                              | 8         | 9.2%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 6         | 6.9%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 6.9%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 5.75%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 3         | 3.45%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.3%    |
| Intel Ethernet Controller I225-V                                  | 2         | 2.3%    |
| Intel Ethernet Connection (16) I219-V                             | 2         | 2.3%    |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 2.3%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.3%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.15%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.15%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.15%   |
| OPPO 8                                                            | 1         | 1.15%   |
| OKB SAPR Ethernet controller                                      | 1         | 1.15%   |
| MediaTek Infinix SMART 6 HD                                       | 1         | 1.15%   |
| MediaTek Infinix HOT 11S NFC                                      | 1         | 1.15%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.15%   |
| Intel 82579V Gigabit Network Connection                           | 1         | 1.15%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.15%   |
| Huawei JKM-LX1                                                    | 1         | 1.15%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.15%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 108       | 57.75%  |
| Ethernet | 78        | 41.71%  |
| Modem    | 1         | 0.53%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 63        | 56.76%  |
| Ethernet | 48        | 43.24%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 64        | 58.72%  |
| 1     | 42        | 38.53%  |
| 0     | 3         | 2.75%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 102       | 91.07%  |
| Yes  | 10        | 8.93%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 45        | 47.37%  |
| Realtek Semiconductor           | 30        | 31.58%  |
| Broadcom                        | 7         | 7.37%   |
| Foxconn / Hon Hai               | 3         | 3.16%   |
| Realtek                         | 2         | 2.11%   |
| Ralink                          | 2         | 2.11%   |
| IMC Networks                    | 2         | 2.11%   |
| Qualcomm Atheros Communications | 1         | 1.05%   |
| Opticis                         | 1         | 1.05%   |
| Lite-On Technology              | 1         | 1.05%   |
| Hewlett-Packard                 | 1         | 1.05%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 26        | 27.37%  |
| Intel Bluetooth wireless interface             | 17        | 17.89%  |
| Intel AX201 Bluetooth                          | 14        | 14.74%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 10        | 10.53%  |
| Realtek  Bluetooth 4.2 Adapter                 | 4         | 4.21%   |
| Intel Bluetooth Device                         | 3         | 3.16%   |
| Realtek Bluetooth Radio                        | 2         | 2.11%   |
| Ralink RT3290 Bluetooth                        | 2         | 2.11%   |
| IMC Networks Bluetooth Radio                   | 2         | 2.11%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 2         | 2.11%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 1.05%   |
| Opticis Bluetooth Radio                        | 1         | 1.05%   |
| Lite-On Wireless_Device                        | 1         | 1.05%   |
| Intel AX200 Bluetooth                          | 1         | 1.05%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 1.05%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 1.05%   |
| Broadcom HP Portable Valentine                 | 1         | 1.05%   |
| Broadcom HP Portable SoftSailing               | 1         | 1.05%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 1.05%   |
| Broadcom BCM20702A0 Bluetooth                  | 1         | 1.05%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR           | 1         | 1.05%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 1.05%   |
| Broadcom BCM2045 Bluetooth                     | 1         | 1.05%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 84        | 69.42%  |
| AMD                    | 25        | 20.66%  |
| Nvidia                 | 8         | 6.61%   |
| Zhaoxin                | 1         | 0.83%   |
| MosArt Semiconductor   | 1         | 0.83%   |
| GN Netcom              | 1         | 0.83%   |
| Generalplus Technology | 1         | 0.83%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP High Definition Audio Controller                                            | 30        | 20.41%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 21        | 14.29%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 16        | 10.88%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 13        | 8.84%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 11        | 7.48%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 6         | 4.08%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 4         | 2.72%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 2.04%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.04%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.36%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.36%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 1.36%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.36%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.36%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.36%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.36%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.36%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.68%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller                          | 1         | 0.68%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.68%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.68%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.68%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.68%   |
| Nvidia Audio device                                                                               | 1         | 0.68%   |
| MosArt Semiconductor MosArt USB Audio Device                                                      | 1         | 0.68%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.68%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.68%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.68%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.68%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.68%   |
| GN Netcom Jabra EVOLVE 20 MS                                                                      | 1         | 0.68%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.68%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.68%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 0.68%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.68%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.68%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                                  | Notebooks | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 47        | 39.17%  |
| SK hynix                                | 20        | 16.67%  |
| Micron Technology                       | 13        | 10.83%  |
| Foxline                                 | 10        | 8.33%   |
| Crucial                                 | 7         | 5.83%   |
| Kingston                                | 4         | 3.33%   |
| Ramaxel Technology                      | 3         | 2.5%    |
| Unknown (ABCD)                          | 2         | 1.67%   |
| Unknown                                 | 2         | 1.67%   |
| Elpida                                  | 2         | 1.67%   |
| A-DATA Technology                       | 2         | 1.67%   |
| Silicon Power Computer & Communications | 1         | 0.83%   |
| SHARETRONIC                             | 1         | 0.83%   |
| Qumo                                    | 1         | 0.83%   |
| Patriot                                 | 1         | 0.83%   |
| King Tiger                              | 1         | 0.83%   |
| ChangXin Memory                         | 1         | 0.83%   |
| <Invalid>                               | 1         | 0.83%   |
| Unknown                                 | 1         | 0.83%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 13.49%  |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 3.17%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 3         | 2.38%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 3         | 2.38%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.38%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 3         | 2.38%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 2.38%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 2.38%   |
| Foxline RAM FL3200D4S22-8G 8192MB SODIMM DDR4 3200MT/s           | 3         | 2.38%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 3         | 2.38%   |
| Foxline RAM FL2400D4S17S-8G 8GB SODIMM DDR4 2400MT/s             | 3         | 2.38%   |
| Unknown (ABCD) RAM 123456789012345678 1GB SODIMM LPDDR4 2400MT/s | 2         | 1.59%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.59%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.59%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.59%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 1.59%   |
| Samsung RAM M471B5773DH0-CH9 2048MB SODIMM DDR3 1600MT/s         | 2         | 1.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.59%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.59%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.59%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.59%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s           | 2         | 1.59%   |
| Crucial RAM CT8G4SFS832A.C8FN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.59%   |
| A-DATA RAM Module 8GB SODIMM DDR4 3200MT/s                       | 2         | 1.59%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.79%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 0.79%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.79%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.79%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.79%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.79%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.79%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.79%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.79%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8192MB SODIMM DDR4 3200MT/s        | 1         | 0.79%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.79%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips LPDDR5 6400MT/s | 1         | 0.79%   |
| Silicon Power & RAM Module 8GB SODIMM DDR4 3200MT/s              | 1         | 0.79%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.79%   |
| Samsung RAM P4AAF165WA-BCWDE 8GB SODIMM DDR4 3200MT/s            | 1         | 0.79%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.79%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 85        | 80.19%  |
| DDR3   | 15        | 14.15%  |
| LPDDR4 | 3         | 2.83%   |
| LPDDR5 | 1         | 0.94%   |
| LPDDR3 | 1         | 0.94%   |
| DDR2   | 1         | 0.94%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 96        | 85.71%  |
| Row Of Chips | 15        | 13.39%  |
| DIMM         | 1         | 0.89%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 67        | 59.82%  |
| 4096  | 28        | 25%     |
| 16384 | 8         | 7.14%   |
| 2048  | 6         | 5.36%   |
| 1024  | 3         | 2.68%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 46        | 41.82%  |
| 2667  | 32        | 29.09%  |
| 1600  | 11        | 10%     |
| 2400  | 8         | 7.27%   |
| 3266  | 2         | 1.82%   |
| 1334  | 2         | 1.82%   |
| 1333  | 2         | 1.82%   |
| 6400  | 1         | 0.91%   |
| 3733  | 1         | 0.91%   |
| 2666  | 1         | 0.91%   |
| 2133  | 1         | 0.91%   |
| 1866  | 1         | 0.91%   |
| 1066  | 1         | 0.91%   |
| 667   | 1         | 0.91%   |

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
| Chicony Electronics                    | 22        | 20.37%  |
| Syntek                                 | 20        | 18.52%  |
| IMC Networks                           | 13        | 12.04%  |
| Bison Electronics                      | 9         | 8.33%   |
| Quanta                                 | 6         | 5.56%   |
| Acer                                   | 6         | 5.56%   |
| Microdia                               | 5         | 4.63%   |
| Sunplus Innovation Technology          | 4         | 3.7%    |
| Luxvisions Innotech Limited            | 4         | 3.7%    |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.7%    |
| Realtek Semiconductor                  | 3         | 2.78%   |
| USB Camera CS                          | 2         | 1.85%   |
| Suyin                                  | 2         | 1.85%   |
| SunplusIT                              | 2         | 1.85%   |
| Sonix Technology                       | 2         | 1.85%   |
| Primax Electronics                     | 1         | 0.93%   |
| GEMBIRD                                | 1         | 0.93%   |
| Alcor Micro                            | 1         | 0.93%   |
| Unknown                                | 1         | 0.93%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 19        | 17.59%  |
| Chicony USB camera                                  | 10        | 9.26%   |
| IMC Networks ov9734_azurewave_camera                | 4         | 3.7%    |
| IMC Networks Integrated Camera                      | 4         | 3.7%    |
| Bison Integrated Camera                             | 4         | 3.7%    |
| Chicony Integrated Camera                           | 3         | 2.78%   |
| Acer BisonCam,NB Pro                                | 3         | 2.78%   |
| USB Camera CS USB Camera CS                         | 2         | 1.85%   |
| Sunplus Integrated_Webcam_HD                        | 2         | 1.85%   |
| Sonix USB 2.0 Camera                                | 2         | 1.85%   |
| Quanta HP TrueVision HD Camera                      | 2         | 1.85%   |
| Microdia Webcam Vitade AF                           | 2         | 1.85%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 1.85%   |
| IMC Networks HD Camera                              | 2         | 1.85%   |
| Chicony USB2.0 Camera                               | 2         | 1.85%   |
| Chicony HD User Facing                              | 2         | 1.85%   |
| Bison Lenovo Integrated Webcam                      | 2         | 1.85%   |
| Bison HD Webcam                                     | 2         | 1.85%   |
| Acer Integrated Camera                              | 2         | 1.85%   |
| Syntek Lenovo EasyCamera                            | 1         | 0.93%   |
| Suyin HP Truevision HD                              | 1         | 0.93%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 0.93%   |
| SunplusIT XiaoMi USB 2.0 Webcam                     | 1         | 0.93%   |
| SunplusIT MTD camera                                | 1         | 0.93%   |
| Sunplus BKX Usb FHD Camera                          | 1         | 0.93%   |
| Sunplus Asus Webcam                                 | 1         | 0.93%   |
| Realtek Integrated_Webcam_HD                        | 1         | 0.93%   |
| Realtek HP Truevision HD                            | 1         | 0.93%   |
| Realtek 2SF022                                      | 1         | 0.93%   |
| Quanta USB2.0 HD UVC WebCam                         | 1         | 0.93%   |
| Quanta USB HD Webcam                                | 1         | 0.93%   |
| Quanta HP Webcam                                    | 1         | 0.93%   |
| Quanta HD Camera                                    | 1         | 0.93%   |
| Primax HP HD Webcam [Fixed]                         | 1         | 0.93%   |
| Microdia USB 2.0 Camera                             | 1         | 0.93%   |
| Microdia Integrated_Webcam_HD                       | 1         | 0.93%   |
| Microdia Integrated Webcam                          | 1         | 0.93%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 0.93%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 0.93%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 0.93%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 8         | 72.73%  |
| Synaptics                  | 2         | 18.18%  |
| Validity Sensors           | 1         | 9.09%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device        | 8         | 72.73%  |
| Synaptics UWP WBDI Device                  | 2         | 18.18%  |
| Validity Sensors VFS451 Fingerprint Reader | 1         | 9.09%   |

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


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 0     | 76        | 68.47%  |
| 1     | 27        | 24.32%  |
| 2     | 8         | 7.21%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 14        | 34.15%  |
| Net/wireless          | 11        | 26.83%  |
| Fingerprint reader    | 11        | 26.83%  |
| Bluetooth             | 2         | 4.88%   |
| Sound                 | 1         | 2.44%   |
| Net/ethernet          | 1         | 2.44%   |
| Multimedia controller | 1         | 2.44%   |

