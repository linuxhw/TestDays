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

Total: 161

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Red OS 7.3.1 | 44        | 41.9%   |
| Red OS 7.3.2 | 40        | 38.1%   |
| Red OS 7.3   | 20        | 19.05%  |
| Red OS 7.2   | 1         | 0.95%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Red OS | 100       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64   | 25        | 22.52%  |
| 5.15.72-1.el7.3.x86_64 | 22        | 19.82%  |
| 5.15.87-1.el7.3.x86_64 | 12        | 10.81%  |
| 5.15.35-4.el7.3.x86_64 | 10        | 9.01%   |
| 5.10.29-1.el7.x86_64   | 10        | 9.01%   |
| 5.15.35-1.el7.3.x86_64 | 6         | 5.41%   |
| 5.15.35-5.el7.3.x86_64 | 4         | 3.6%    |
| 6.1.20-2.el7.3.x86_64  | 3         | 2.7%    |
| 5.15.78-2.el7.3.x86_64 | 3         | 2.7%    |
| 5.10.1-1.el7.x86_64    | 3         | 2.7%    |
| 5.15.10-4.el7.x86_64   | 2         | 1.8%    |
| 5.10.29-3.el7.x86_64   | 2         | 1.8%    |
| 5.10.24-2.el7.x86_64   | 2         | 1.8%    |
| 5.18.1-1.el7.x86_64    | 1         | 0.9%    |
| 5.15.120               | 1         | 0.9%    |
| 5.15.10-3.el7.x86_64   | 1         | 0.9%    |
| 5.15.10-2.el7.x86_64   | 1         | 0.9%    |
| 5.13.15-1.el7.x86_64   | 1         | 0.9%    |
| 5.10.24-1.el7.x86_64   | 1         | 0.9%    |
| 4.19.79-1.el7.x86_64   | 1         | 0.9%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Notebooks | Percent |
|----------|-----------|---------|
| 5.15.10  | 29        | 26.36%  |
| 5.15.72  | 22        | 20%     |
| 5.15.35  | 19        | 17.27%  |
| 5.15.87  | 12        | 10.91%  |
| 5.10.29  | 12        | 10.91%  |
| 6.1.20   | 3         | 2.73%   |
| 5.15.78  | 3         | 2.73%   |
| 5.10.24  | 3         | 2.73%   |
| 5.10.1   | 3         | 2.73%   |
| 5.18.1   | 1         | 0.91%   |
| 5.15.120 | 1         | 0.91%   |
| 5.13.15  | 1         | 0.91%   |
| 4.19.79  | 1         | 0.91%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 81        | 77.88%  |
| 5.10    | 17        | 16.35%  |
| 6.1     | 3         | 2.88%   |
| 5.18    | 1         | 0.96%   |
| 5.13    | 1         | 0.96%   |
| 4.19    | 1         | 0.96%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 100       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 87        | 86.14%  |
| Cinnamon   | 12        | 11.88%  |
| X-Cinnamon | 2         | 1.98%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 96        | 94.12%  |
| Wayland | 6         | 5.88%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 95        | 92.23%  |
| SDDM    | 3         | 2.91%   |
| Unknown | 3         | 2.91%   |
| LightDM | 2         | 1.94%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 68.93%  |
| ru_RU   | 31        | 30.1%   |
| en_US   | 1         | 0.97%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 88        | 86.27%  |
| BIOS | 14        | 13.73%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 98        | 97.03%  |
| Xfs     | 1         | 0.99%   |
| Overlay | 1         | 0.99%   |
| Btrfs   | 1         | 0.99%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 87        | 86.14%  |
| MBR     | 11        | 10.89%  |
| Unknown | 3         | 2.97%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 90        | 89.11%  |
| Yes       | 11        | 10.89%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 76        | 73.79%  |
| Yes       | 27        | 26.21%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 37        | 37%     |
| Hewlett-Packard                | 13        | 13%     |
| ICL                            | 6         | 6%      |
| MSI                            | 5         | 5%      |
| HUAWEI                         | 4         | 4%      |
| Dell                           | 4         | 4%      |
| Aquarius                       | 4         | 4%      |
| Kraftway                       | 3         | 3%      |
| Digma                          | 3         | 3%      |
| ASUSTek Computer               | 3         | 3%      |
| Acer                           | 3         | 3%      |
| IP3 Technology                 | 2         | 2%      |
| HONOR                          | 2         | 2%      |
| Gigabyte Technology            | 2         | 2%      |
| 3Logic Group                   | 2         | 2%      |
| Timi                           | 1         | 1%      |
| THUNDEROBOT                    | 1         | 1%      |
| Shanghai Zhaoxin Semiconductor | 1         | 1%      |
| Pegatron                       | 1         | 1%      |
| mtech                          | 1         | 1%      |
| Graviton                       | 1         | 1%      |
| Unknown                        | 1         | 1%      |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE                  | 17        | 17%     |
| Kraftway ACCORD                      | 3         | 3%      |
| ICL RAYbook Si1512                   | 3         | 3%      |
| HP Laptop 15s-eq1xxx                 | 3         | 3%      |
| Lenovo ThinkBook 15 G3 ACL 21A4      | 2         | 2%      |
| IP3 ACN30                            | 2         | 2%      |
| Unknown                              | 2         | 2%      |
| Timi Redmi Book Pro 15 2022          | 1         | 1%      |
| THUNDEROBOT 911AirD                  | 1         | 1%      |
| Shanghai Zhaoxin ZXE CRB             | 1         | 1%      |
| Pegatron A35                         | 1         | 1%      |
| mtech MTL1578                        | 1         | 1%      |
| MSI Sword 15 A12UE                   | 1         | 1%      |
| MSI Modern 15 B12M                   | 1         | 1%      |
| MSI Modern 14 C12M                   | 1         | 1%      |
| MSI GL62 6QF                         | 1         | 1%      |
| MSI FX610                            | 1         | 1%      |
| Lenovo V130-15IKB 81HN               | 1         | 1%      |
| Lenovo ThinkPad X220 4290RB3         | 1         | 1%      |
| Lenovo ThinkPad T14 Gen 3 21AJS2DE00 | 1         | 1%      |
| Lenovo ThinkPad T14 Gen 3 21AJS2DD00 | 1         | 1%      |
| Lenovo ThinkPad E15 Gen 4 21E6009UGP | 1         | 1%      |
| Lenovo ThinkBook 15 G2 ITL 20VE      | 1         | 1%      |
| Lenovo ThinkBook 15 G2 ARE 20VG      | 1         | 1%      |
| Lenovo ThinkBook 14-IIL 20SL         | 1         | 1%      |
| Lenovo IdeaPad L340-15IWL 81LG       | 1         | 1%      |
| Lenovo IdeaPad L340-15API 81LW       | 1         | 1%      |
| Lenovo IdeaPad 700-15ISK 80RU        | 1         | 1%      |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7     | 1         | 1%      |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 1         | 1%      |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 1%      |
| Lenovo IdeaPad 3 15ITL05 81X8        | 1         | 1%      |
| Lenovo IdeaPad 1 15ALC7 82R4         | 1         | 1%      |
| Lenovo G570 20079                    | 1         | 1%      |
| Lenovo B590 20208                    | 1         | 1%      |
| ICL Si1407                           | 1         | 1%      |
| ICL RAYbook Si1514                   | 1         | 1%      |
| HUAWEI NBLK-WAX9X                    | 1         | 1%      |
| HUAWEI NBD-WXX9                      | 1         | 1%      |
| HUAWEI BOHL-WXX9                     | 1         | 1%      |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo V15-IWL       | 17        | 17%     |
| Lenovo IdeaPad       | 8         | 8%      |
| Lenovo ThinkBook     | 5         | 5%      |
| HP Laptop            | 5         | 5%      |
| Lenovo ThinkPad      | 4         | 4%      |
| ICL RAYbook          | 4         | 4%      |
| Kraftway ACCORD      | 3         | 3%      |
| Digma EVE            | 3         | 3%      |
| MSI Modern           | 2         | 2%      |
| IP3 ACN30            | 2         | 2%      |
| HP ProBook           | 2         | 2%      |
| HP Pavilion          | 2         | 2%      |
| Gigabyte G5          | 2         | 2%      |
| Dell Vostro          | 2         | 2%      |
| Aquarius NS685U      | 2         | 2%      |
| Acer Aspire          | 2         | 2%      |
| Unknown              | 2         | 2%      |
| Timi Redmi           | 1         | 1%      |
| THUNDEROBOT 911AirD  | 1         | 1%      |
| Shanghai Zhaoxin ZXE | 1         | 1%      |
| Pegatron A35         | 1         | 1%      |
| mtech MTL1578        | 1         | 1%      |
| MSI Sword            | 1         | 1%      |
| MSI GL62             | 1         | 1%      |
| MSI FX610            | 1         | 1%      |
| Lenovo V130-15IKB    | 1         | 1%      |
| Lenovo G570          | 1         | 1%      |
| Lenovo B590          | 1         | 1%      |
| ICL Si1407           | 1         | 1%      |
| HUAWEI NBLK-WAX9X    | 1         | 1%      |
| HUAWEI NBD-WXX9      | 1         | 1%      |
| HUAWEI BOHL-WXX9     | 1         | 1%      |
| HUAWEI BOD-WXX9      | 1         | 1%      |
| HONOR NBR-WAX9       | 1         | 1%      |
| HONOR BMH-WCX9       | 1         | 1%      |
| HP OMEN              | 1         | 1%      |
| HP Notebook          | 1         | 1%      |
| HP G62               | 1         | 1%      |
| HP EliteBook         | 1         | 1%      |
| Graviton N14I-T      | 1         | 1%      |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 29        | 29%     |
| 2021 | 22        | 22%     |
| 2022 | 15        | 15%     |
| 2020 | 13        | 13%     |
| 2010 | 5         | 5%      |
| 2012 | 4         | 4%      |
| 2017 | 3         | 3%      |
| 2011 | 3         | 3%      |
| 2018 | 2         | 2%      |
| 2016 | 1         | 1%      |
| 2015 | 1         | 1%      |
| 2013 | 1         | 1%      |
| 2007 | 1         | 1%      |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 100       | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 100       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 100       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 62        | 62%     |
| 3.01-4.0   | 13        | 13%     |
| 16.01-24.0 | 12        | 12%     |
| 8.01-16.0  | 10        | 10%     |
| 2.01-3.0   | 2         | 2%      |
| 32.01-64.0 | 1         | 1%      |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 62        | 59.05%  |
| 2.01-3.0  | 25        | 23.81%  |
| 0.51-1.0  | 9         | 8.57%   |
| 3.01-4.0  | 6         | 5.71%   |
| 4.01-8.0  | 2         | 1.9%    |
| 8.01-16.0 | 1         | 0.95%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 88        | 85.44%  |
| 2      | 10        | 9.71%   |
| 3      | 4         | 3.88%   |
| 4      | 1         | 0.97%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 84        | 83.17%  |
| Yes       | 17        | 16.83%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 68        | 68%     |
| No        | 32        | 32%     |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 99        | 99%     |
| No        | 1         | 1%      |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 86        | 86%     |
| No        | 14        | 14%     |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 99        | 99%     |
| Ukraine | 1         | 1%      |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 25        | 24.04%  |
| Salekhard        | 22        | 21.15%  |
| Murom            | 16        | 15.38%  |
| St Petersburg    | 5         | 4.81%   |
| Ryazan           | 3         | 2.88%   |
| Yekaterinburg    | 2         | 1.92%   |
| Yakutsk          | 2         | 1.92%   |
| Vladimir         | 2         | 1.92%   |
| Perm             | 2         | 1.92%   |
| Novy Urengoy     | 2         | 1.92%   |
| Nizhniy Novgorod | 2         | 1.92%   |
| Kursk            | 2         | 1.92%   |
| Krasnodar        | 2         | 1.92%   |
| Yaroslavl        | 1         | 0.96%   |
| Volzhskiy        | 1         | 0.96%   |
| Ulyanovsk        | 1         | 0.96%   |
| Tver             | 1         | 0.96%   |
| Strezhevoy       | 1         | 0.96%   |
| Sevastopol       | 1         | 0.96%   |
| Saratov          | 1         | 0.96%   |
| Omsk             | 1         | 0.96%   |
| Novosibirsk      | 1         | 0.96%   |
| Muromskiy        | 1         | 0.96%   |
| Krasnoyarsk      | 1         | 0.96%   |
| Kirzhach         | 1         | 0.96%   |
| Khabarovsk       | 1         | 0.96%   |
| Kaluga           | 1         | 0.96%   |
| Borinskoye       | 1         | 0.96%   |
| Belgorod         | 1         | 0.96%   |
| Balashikha       | 1         | 0.96%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 27        | 37     | 23.28%  |
| WDC                 | 15        | 18     | 12.93%  |
| SK hynix            | 9         | 11     | 7.76%   |
| Seagate             | 7         | 8      | 6.03%   |
| A-DATA Technology   | 6         | 6      | 5.17%   |
| Toshiba             | 5         | 18     | 4.31%   |
| Foxline             | 5         | 5      | 4.31%   |
| Silicon Motion      | 4         | 4      | 3.45%   |
| HGST                | 4         | 4      | 3.45%   |
| Phison              | 3         | 3      | 2.59%   |
| Micron Technology   | 3         | 7      | 2.59%   |
| Gigabyte Technology | 3         | 3      | 2.59%   |
| Unknown             | 2         | 2      | 1.72%   |
| UMIS                | 2         | 2      | 1.72%   |
| Kingston            | 2         | 2      | 1.72%   |
| Intel               | 2         | 2      | 1.72%   |
| Crucial             | 2         | 2      | 1.72%   |
| China               | 2         | 3      | 1.72%   |
| YMTC                | 1         | 1      | 0.86%   |
| Transcend           | 1         | 1      | 0.86%   |
| SPCC Sol            | 1         | 1      | 0.86%   |
| SanDisk             | 1         | 1      | 0.86%   |
| Netac               | 1         | 1      | 0.86%   |
| KIOXIA              | 1         | 1      | 0.86%   |
| KingSpec            | 1         | 1      | 0.86%   |
| Kimtigo             | 1         | 2      | 0.86%   |
| JMicron Technology  | 1         | 1      | 0.86%   |
| ITHOO               | 1         | 1      | 0.86%   |
| HUAWEI              | 1         | 1      | 0.86%   |
| Apacer              | 1         | 2      | 0.86%   |
| Unknown             | 1         | 1      | 0.86%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB          | 18        | 15.25%  |
| Foxline FLSSD256M80E13TCX5 256GB          | 5         | 4.24%   |
| Silicon Motion Wodposit NVMe SSD 256GB    | 4         | 3.39%   |
| WDC WD10SPZX-00Z10T0 1TB                  | 2         | 1.69%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB      | 2         | 1.69%   |
| Toshiba MQ01ABF050 500GB                  | 2         | 1.69%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB    | 2         | 1.69%   |
| SK hynix PC711 HFS512GDE9X073N 512GB      | 2         | 1.69%   |
| Seagate ST1000LM035-1RK172 1TB            | 2         | 1.69%   |
| Samsung MZALQ512HALU-000L2 512GB          | 2         | 1.69%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB          | 2         | 1.69%   |
| A-DATA SU650 240GB SSD                    | 2         | 1.69%   |
| YMTC PC210-512GB-B                        | 1         | 0.85%   |
| WDC WDS500G2B0B-00YS70 500GB SSD          | 1         | 0.85%   |
| WDC WDS250G2B0A-00SM50 250GB SSD          | 1         | 0.85%   |
| WDC WD5000BPVT-55HXZT3 500GB              | 1         | 0.85%   |
| WDC WD3200BPVT-24JJ5T0 320GB              | 1         | 0.85%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 0.85%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 0.85%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.85%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 0.85%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB      | 1         | 0.85%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 0.85%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB      | 1         | 0.85%   |
| Unknown SLD128  128GB                     | 1         | 0.85%   |
| Unknown 58K722  128GB                     | 1         | 0.85%   |
| UMIS RPJTJ512MEE1OWX 512GB                | 1         | 0.85%   |
| UMIS RPJTJ256MGE1QDQ 256GB                | 1         | 0.85%   |
| Transcend TS240GMTS820S 240GB SSD         | 1         | 0.85%   |
| Toshiba MK5075GSX 500GB                   | 1         | 0.85%   |
| Toshiba MK5059GSXP 500GB                  | 1         | 0.85%   |
| Toshiba KXG60ZNV512G 512GB                | 1         | 0.85%   |
| Toshiba KXG60ZNV256G 256GB                | 1         | 0.85%   |
| SPCC Sol id State Disk 256GB SSD          | 1         | 0.85%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB    | 1         | 0.85%   |
| SK hynix SKHynix_HFS256GDE9X081N 256GB    | 1         | 0.85%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 0.85%   |
| SK hynix BC711 NVMe 256GB                 | 1         | 0.85%   |
| SK hynix BC511 NVMe 256GB                 | 1         | 0.85%   |
| SK hynix BC511 512GB                      | 1         | 0.85%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor             | Notebooks | Drives | Percent |
|--------------------|-----------|--------|---------|
| WDC                | 7         | 10     | 31.82%  |
| Seagate            | 7         | 8      | 31.82%  |
| HGST               | 4         | 4      | 18.18%  |
| Toshiba            | 3         | 15     | 13.64%  |
| JMicron Technology | 1         | 1      | 4.55%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 4         | 4      | 21.05%  |
| WDC                 | 2         | 2      | 10.53%  |
| Samsung Electronics | 2         | 2      | 10.53%  |
| Crucial             | 2         | 2      | 10.53%  |
| China               | 2         | 3      | 10.53%  |
| Transcend           | 1         | 1      | 5.26%   |
| SPCC Sol            | 1         | 1      | 5.26%   |
| SanDisk             | 1         | 1      | 5.26%   |
| Netac               | 1         | 1      | 5.26%   |
| Kingston            | 1         | 1      | 5.26%   |
| KingSpec            | 1         | 1      | 5.26%   |
| Apacer              | 1         | 2      | 5.26%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 69        | 88     | 61.06%  |
| HDD     | 20        | 38     | 17.7%   |
| SSD     | 19        | 21     | 16.81%  |
| MMC     | 3         | 3      | 2.65%   |
| Unknown | 2         | 2      | 1.77%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 69        | 88     | 62.73%  |
| SATA | 35        | 56     | 31.82%  |
| SAS  | 3         | 5      | 2.73%   |
| MMC  | 3         | 3      | 2.73%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 43     | 72.97%  |
| 0.51-1.0   | 10        | 16     | 27.03%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 56        | 53.85%  |
| 251-500    | 24        | 23.08%  |
| 51-100     | 8         | 7.69%   |
| 1001-2000  | 6         | 5.77%   |
| 501-1000   | 6         | 5.77%   |
| 1-20       | 3         | 2.88%   |
| 21-50      | 1         | 0.96%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB   | Notebooks | Percent |
|-----------|-----------|---------|
| 1-20      | 76        | 72.38%  |
| 21-50     | 16        | 15.24%  |
| 101-250   | 4         | 3.81%   |
| 51-100    | 4         | 3.81%   |
| 251-500   | 2         | 1.9%    |
| 501-1000  | 2         | 1.9%    |
| 1001-2000 | 1         | 0.95%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 11.11%  |
| Toshiba MQ01ABF050 500GB            | 1         | 9      | 11.11%  |
| Toshiba MK5075GSX 500GB             | 1         | 3      | 11.11%  |
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
| Toshiba           | 2         | 13     | 25%     |
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
| Toshiba | 2         | 13     | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 17     | 75%     |
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
| Works    | 91        | 120    | 85.85%  |
| Malfunc  | 8         | 19     | 7.55%   |
| Detected | 7         | 13     | 6.6%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 69        | 46.31%  |
| Samsung Electronics          | 25        | 16.78%  |
| Phison Electronics           | 11        | 7.38%   |
| AMD                          | 11        | 7.38%   |
| SK hynix                     | 9         | 6.04%   |
| SanDisk                      | 6         | 4.03%   |
| Silicon Motion               | 4         | 2.68%   |
| Micron Technology            | 3         | 2.01%   |
| Union Memory (Shenzhen)      | 2         | 1.34%   |
| Toshiba America Info Systems | 2         | 1.34%   |
| Zhaoxin                      | 1         | 0.67%   |
| Yangtze Memory Technologies  | 1         | 0.67%   |
| ShenZhen TIGO Semiconductor  | 1         | 0.67%   |
| Realtek Semiconductor        | 1         | 0.67%   |
| KIOXIA                       | 1         | 0.67%   |
| Kingston Technology Company  | 1         | 0.67%   |
| ADATA Technology             | 1         | 0.67%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 30        | 19.23%  |
| Samsung NVMe SSD Controller 980                                                  | 24        | 15.38%  |
| Phison PS5013 E13 NVMe Controller                                                | 9         | 5.77%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 5.77%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 7         | 4.49%   |
| Intel Tiger Lake-LP SATA Controller                                              | 7         | 4.49%   |
| Intel Volume Management Device NVMe RAID Controller                              | 6         | 3.85%   |
| Silicon Motion SM2263EN/SM2263XT (DRAM-less) NVMe SSD Controllers                | 4         | 2.56%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 2.56%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 2.56%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 1.92%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 1.92%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.28%   |
| SK hynix BC511 NVMe SSD                                                          | 2         | 1.28%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 2         | 1.28%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 2         | 1.28%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 1.28%   |
| Intel SSD 660P Series                                                            | 2         | 1.28%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.28%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 2         | 1.28%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.28%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 1.28%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.28%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G StorX AHCI Controller                     | 1         | 0.64%   |
| Yangtze Memory PC210 NVMe SSD                                                    | 1         | 0.64%   |
| Union Memory (Shenzhen) AM630 PCIe 4.0 NVMe SSD 256GB                            | 1         | 0.64%   |
| Union Memory (Shenzhen) AM620 PCIe 3.0 NVMe SSD 512GB                            | 1         | 0.64%   |
| ShenZhen TIGO kimtigo NVMe SSD (DRAM-less)                                       | 1         | 0.64%   |
| SanDisk PC SN530 NVMe SSD (DRAM-less)                                            | 1         | 0.64%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.64%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                   | 1         | 0.64%   |
| Realtek RTS5765DL NVMe SSD Controller (DRAM-less)                                | 1         | 0.64%   |
| Micron 2450 NVMe SSD [HendrixV] (DRAM-less)                                      | 1         | 0.64%   |
| Micron 2400 NVMe SSD (DRAM-less)                                                 | 1         | 0.64%   |
| Micron 2200S NVMe SSD [Cassandra]                                                | 1         | 0.64%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                       | 1         | 0.64%   |
| Kingston Company NVMe Controller                                                 | 1         | 0.64%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.64%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.64%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 77        | 49.68%  |
| NVMe | 69        | 44.52%  |
| RAID | 7         | 4.52%   |
| IDE  | 2         | 1.29%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 77        | 77%     |
| AMD          | 22        | 22%     |
| CentaurHauls | 1         | 1%      |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 18%     |
| Intel Core i5-8279U CPU @ 2.40GHz             | 6         | 6%      |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 6%      |
| Intel Core i5-8259U CPU @ 2.30GHz             | 5         | 5%      |
| Intel 12th Gen Core i5-1235U                  | 3         | 3%      |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 3         | 3%      |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 3%      |
| AMD Ryzen 3 5400U with Radeon Graphics        | 3         | 3%      |
| AMD Ryzen 3 5300U with Radeon Graphics        | 3         | 3%      |
| AMD Ryzen 3 4300U with Radeon Graphics        | 3         | 3%      |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 2%      |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 2%      |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2%      |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 1%      |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 1%      |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1%      |
| Intel Core i7-3740QM CPU @ 2.70GHz            | 1         | 1%      |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1%      |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1%      |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1%      |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1%      |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1%      |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1%      |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1%      |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1%      |
| Intel Core i3-9300 CPU @ 3.70GHz              | 1         | 1%      |
| Intel Core i3-8145U CPU @ 2.10GHz             | 1         | 1%      |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1%      |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1%      |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1%      |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 1%      |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 1%      |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 1%      |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 1         | 1%      |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 1%      |
| Intel Celeron CPU B815 @ 1.60GHz              | 1         | 1%      |
| Intel 12th Gen Core i7-1270P                  | 1         | 1%      |
| Intel 12th Gen Core i7-12700H                 | 1         | 1%      |
| Intel 12th Gen Core i5-1250P                  | 1         | 1%      |
| Intel 12th Gen Core i5-12500H                 | 1         | 1%      |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 39        | 39%     |
| Other            | 22        | 22%     |
| Intel Core i3    | 9         | 9%      |
| AMD Ryzen 3      | 9         | 9%      |
| AMD Ryzen 5      | 8         | 8%      |
| Intel Celeron    | 3         | 3%      |
| Intel Pentium    | 2         | 2%      |
| Intel Core i7    | 2         | 2%      |
| AMD Ryzen 7      | 2         | 2%      |
| AMD Phenom II    | 2         | 2%      |
| Intel Core 2 Duo | 1         | 1%      |
| AMD A4           | 1         | 1%      |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 63        | 63%     |
| 2      | 20        | 20%     |
| 6      | 8         | 8%      |
| 12     | 3         | 3%      |
| 10     | 3         | 3%      |
| 14     | 1         | 1%      |
| 8      | 1         | 1%      |
| 3      | 1         | 1%      |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 100       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 81        | 81%     |
| 1      | 19        | 19%     |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 100       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 22        | 21.78%  |
| 0x806ea    | 12        | 11.88%  |
| 0x806c1    | 11        | 10.89%  |
| 0x08600106 | 5         | 4.95%   |
| 0x906a4    | 4         | 3.96%   |
| 0x906a3    | 4         | 3.96%   |
| 0x206a7    | 4         | 3.96%   |
| 0x0a50000c | 4         | 3.96%   |
| 0x08608103 | 4         | 3.96%   |
| 0x306a9    | 3         | 2.97%   |
| 0x806d1    | 2         | 1.98%   |
| 0x506e3    | 2         | 1.98%   |
| 0x506ca    | 2         | 1.98%   |
| 0x40651    | 2         | 1.98%   |
| 0x08108102 | 2         | 1.98%   |
| 0x010000c8 | 2         | 1.98%   |
| Unknown    | 2         | 1.98%   |
| 0x906eb    | 1         | 0.99%   |
| 0x906e9    | 1         | 0.99%   |
| 0x706e5    | 1         | 0.99%   |
| 0x6fa      | 1         | 0.99%   |
| 0x506c9    | 1         | 0.99%   |
| 0x406c4    | 1         | 0.99%   |
| 0x20655    | 1         | 0.99%   |
| 0x20652    | 1         | 0.99%   |
| 0x0a50000d | 1         | 0.99%   |
| 0x0a404101 | 1         | 0.99%   |
| 0x08600104 | 1         | 0.99%   |
| 0x08108109 | 1         | 0.99%   |
| 0x0810100b | 1         | 0.99%   |
| 0x06006705 | 1         | 0.99%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 37        | 37%     |
| TigerLake        | 11        | 11%     |
| Alderlake Hybrid | 8         | 8%      |
| Zen 2            | 6         | 6%      |
| Unknown          | 6         | 6%      |
| Zen 3            | 4         | 4%      |
| SandyBridge      | 4         | 4%      |
| Zen+             | 3         | 3%      |
| IvyBridge        | 3         | 3%      |
| Icelake          | 3         | 3%      |
| Goldmont         | 3         | 3%      |
| Westmere         | 2         | 2%      |
| Skylake          | 2         | 2%      |
| K10              | 2         | 2%      |
| Haswell          | 2         | 2%      |
| Zen              | 1         | 1%      |
| Silvermont       | 1         | 1%      |
| Excavator        | 1         | 1%      |
| Core             | 1         | 1%      |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 76        | 63.33%  |
| AMD     | 25        | 20.83%  |
| Nvidia  | 18        | 15%     |
| Zhaoxin | 1         | 0.83%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 19        | 15.45%  |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 11        | 8.94%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 5.69%   |
| AMD Renoir                                                                | 6         | 4.88%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 4         | 3.25%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 4         | 3.25%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.25%   |
| AMD Lucienne                                                              | 4         | 3.25%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 3.25%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 2.44%   |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                               | 3         | 2.44%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 2.44%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 2.44%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                              | 3         | 2.44%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.63%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.63%   |
| Intel HD Graphics 530                                                     | 2         | 1.63%   |
| Intel HD Graphics 500                                                     | 2         | 1.63%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.63%   |
| Zhaoxin ZX-E C-960 GPU                                                    | 1         | 0.81%   |
| Nvidia TU117M [GeForce MX550]                                             | 1         | 0.81%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.81%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 0.81%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.81%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.81%   |
| Nvidia GM108M [GeForce 920MX]                                             | 1         | 0.81%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.81%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.81%   |
| Nvidia GM107GLM [Quadro M1000M]                                           | 1         | 0.81%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.81%   |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 0.81%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.81%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                         | 1         | 0.81%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 1         | 0.81%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.81%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.81%   |
| Intel UHD Graphics 620                                                    | 1         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 0.81%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 0.81%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 0.81%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 57        | 57%     |
| 1 x AMD        | 19        | 19%     |
| Intel + Nvidia | 16        | 16%     |
| Intel + AMD    | 3         | 3%      |
| 2 x AMD        | 2         | 2%      |
| 1 x Zhaoxin    | 1         | 1%      |
| 1 x Nvidia     | 1         | 1%      |
| AMD + Nvidia   | 1         | 1%      |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 89        | 87.25%  |
| Unknown     | 11        | 10.78%  |
| Proprietary | 2         | 1.96%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 63        | 61.17%  |
| 1.01-2.0   | 17        | 16.5%   |
| 0.01-0.5   | 11        | 10.68%  |
| 3.01-4.0   | 6         | 5.83%   |
| 0.51-1.0   | 6         | 5.83%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 46        | 44.23%  |
| LG Display           | 14        | 13.46%  |
| Chimei Innolux       | 10        | 9.62%   |
| Samsung Electronics  | 8         | 7.69%   |
| AU Optronics         | 6         | 5.77%   |
| PANDA                | 5         | 4.81%   |
| Philips              | 2         | 1.92%   |
| NLE                  | 2         | 1.92%   |
| Acer                 | 2         | 1.92%   |
| ViewSonic            | 1         | 0.96%   |
| Toshiba              | 1         | 0.96%   |
| TMX                  | 1         | 0.96%   |
| RGT                  | 1         | 0.96%   |
| Lenovo               | 1         | 0.96%   |
| Iiyama               | 1         | 0.96%   |
| HUAWEI               | 1         | 0.96%   |
| Dell                 | 1         | 0.96%   |
| Ancor Communications | 1         | 0.96%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 17        | 16.19%  |
| BOE LCD Monitor BOE09C5 1920x1080 345x194mm 15.6-inch                   | 9         | 8.57%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch            | 3         | 2.86%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch        | 3         | 2.86%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                   | 3         | 2.86%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 3         | 2.86%   |
| NLE Newline NLE0032 3840x2160 944x398mm 40.3-inch                       | 2         | 1.9%    |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 1.9%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 1.9%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 2         | 1.9%    |
| BOE LCD Monitor BOE0936 1920x1080 344x194mm 15.5-inch                   | 2         | 1.9%    |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                   | 2         | 1.9%    |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                    | 2         | 1.9%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.9%    |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.9%    |
| ViewSonic PJ VSC9B34 1920x1080                                          | 1         | 0.95%   |
| Toshiba LCD Monitor LCD58EB 1280x800 261x163mm 12.1-inch                | 1         | 0.95%   |
| TMX TL156MDMP01-0 TMX1560 3200x2000 336x210mm 15.6-inch                 | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch    | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch    | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch    | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch    | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 1872x1053mm 84.6-inch | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch   | 1         | 0.95%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 890x500mm 40.2-inch   | 1         | 0.95%   |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                   | 1         | 0.95%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                    | 1         | 0.95%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 1         | 0.95%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                 | 1         | 0.95%   |
| PANDA LCD Monitor NCP0065 1920x1080 309x174mm 14.0-inch                 | 1         | 0.95%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                 | 1         | 0.95%   |
| PANDA LCD Monitor NCP002B 1920x1080 309x174mm 14.0-inch                 | 1         | 0.95%   |
| PANDA LC116LF3L03 NCP000A 1920x1080 256x144mm 11.6-inch                 | 1         | 0.95%   |
| LG Display LCD Monitor LGDD302 1366x768 277x156mm 12.5-inch             | 1         | 0.95%   |
| LG Display LCD Monitor LGD0671 1920x1080 382x215mm 17.3-inch            | 1         | 0.95%   |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch            | 1         | 0.95%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 0.95%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch            | 1         | 0.95%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch             | 1         | 0.95%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 74        | 77.08%  |
| 1366x768 (WXGA)    | 12        | 12.5%   |
| 3840x2160 (4K)     | 3         | 3.13%   |
| 3440x1440          | 1         | 1.04%   |
| 3200x2000          | 1         | 1.04%   |
| 2240x1400          | 1         | 1.04%   |
| 1680x1050 (WSXGA+) | 1         | 1.04%   |
| 1600x900 (HD+)     | 1         | 1.04%   |
| 1280x800 (WXGA)    | 1         | 1.04%   |
| 1280x1024 (SXGA)   | 1         | 1.04%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 70        | 67.96%  |
| 14      | 6         | 5.83%   |
| 13      | 6         | 5.83%   |
| 21      | 3         | 2.91%   |
| 17      | 3         | 2.91%   |
| 84      | 2         | 1.94%   |
| 40      | 2         | 1.94%   |
| 24      | 2         | 1.94%   |
| 12      | 2         | 1.94%   |
| 54      | 1         | 0.97%   |
| 34      | 1         | 0.97%   |
| 23      | 1         | 0.97%   |
| 22      | 1         | 0.97%   |
| 19      | 1         | 0.97%   |
| 11      | 1         | 0.97%   |
| Unknown | 1         | 0.97%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 81        | 78.64%  |
| 401-500     | 4         | 3.88%   |
| 351-400     | 4         | 3.88%   |
| 201-300     | 4         | 3.88%   |
| 501-600     | 3         | 2.91%   |
| 1501-2000   | 2         | 1.94%   |
| 901-1000    | 2         | 1.94%   |
| 701-800     | 1         | 0.97%   |
| 1001-1500   | 1         | 0.97%   |
| Unknown     | 1         | 0.97%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 86        | 91.49%  |
| 16/10 | 4         | 4.26%   |
| 21/9  | 3         | 3.19%   |
| 5/4   | 1         | 1.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 70        | 67.96%  |
| 81-90          | 11        | 10.68%  |
| 201-250        | 7         | 6.8%    |
| More than 1000 | 3         | 2.91%   |
| 121-130        | 3         | 2.91%   |
| 61-70          | 2         | 1.94%   |
| 501-1000       | 2         | 1.94%   |
| 71-80          | 1         | 0.97%   |
| 51-60          | 1         | 0.97%   |
| 351-500        | 1         | 0.97%   |
| 151-200        | 1         | 0.97%   |
| Unknown        | 1         | 0.97%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Notebooks | Percent |
|---------------|-----------|---------|
| 121-160       | 72        | 71.29%  |
| 101-120       | 16        | 15.84%  |
| 51-100        | 7         | 6.93%   |
| 161-240       | 3         | 2.97%   |
| More than 240 | 1         | 0.99%   |
| 1-50          | 1         | 0.99%   |
| Unknown       | 1         | 0.99%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 77        | 77%     |
| 0     | 12        | 12%     |
| 2     | 10        | 10%     |
| 3     | 1         | 1%      |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 70        | 46.36%  |
| Intel                 | 47        | 31.13%  |
| Broadcom              | 7         | 4.64%   |
| Qualcomm Atheros      | 6         | 3.97%   |
| Xiaomi                | 5         | 3.31%   |
| MediaTek              | 3         | 1.99%   |
| TP-Link               | 2         | 1.32%   |
| Samsung Electronics   | 2         | 1.32%   |
| Ralink                | 2         | 1.32%   |
| Huawei Technologies   | 2         | 1.32%   |
| Ralink Technology     | 1         | 0.66%   |
| Qualcomm              | 1         | 0.66%   |
| OPPO Electronics      | 1         | 0.66%   |
| OKB SAPR              | 1         | 0.66%   |
| Broadcom Limited      | 1         | 0.66%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 17.58%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25        | 13.74%  |
| Intel Wireless 7265                                               | 12        | 6.59%   |
| Intel Wi-Fi 6 AX201                                               | 8         | 4.4%    |
| Intel Ethernet Connection (6) I219-V                              | 8         | 4.4%    |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 8         | 4.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 2.75%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 2.75%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 2.75%   |
| Intel Wireless 3165                                               | 4         | 2.2%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 2.2%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 1.65%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.65%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.65%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.65%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.1%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 2         | 1.1%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 1.1%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 1.1%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.1%    |
| Intel Ethernet Controller I225-V                                  | 2         | 1.1%    |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 1.1%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 1.1%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.1%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 1.1%    |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.1%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 0.55%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.55%   |
| TP-Link 802.11n NIC                                               | 1         | 0.55%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.55%   |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.55%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.55%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.55%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.55%   |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.55%   |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 0.55%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.55%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.55%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.55%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Intel                 | 45        | 43.27%  |
| Realtek Semiconductor | 41        | 39.42%  |
| Broadcom              | 6         | 5.77%   |
| Qualcomm Atheros      | 3         | 2.88%   |
| TP-Link               | 2         | 1.92%   |
| Ralink                | 2         | 1.92%   |
| MediaTek              | 2         | 1.92%   |
| Ralink Technology     | 1         | 0.96%   |
| Qualcomm              | 1         | 0.96%   |
| Broadcom Limited      | 1         | 0.96%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25        | 23.58%  |
| Intel Wireless 7265                                            | 12        | 11.32%  |
| Intel Wi-Fi 6 AX201                                            | 8         | 7.55%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 8         | 7.55%   |
| Intel Wireless 3165                                            | 4         | 3.77%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 3.77%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 2.83%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 2.83%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 2.83%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 2.83%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 2         | 1.89%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 1.89%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 1.89%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 1.89%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 1.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 1.89%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 1.89%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 0.94%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 0.94%   |
| TP-Link 802.11n NIC                                            | 1         | 0.94%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 0.94%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 0.94%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 0.94%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 0.94%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 0.94%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 0.94%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 0.94%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 0.94%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 0.94%   |
| Intel Wireless 8265 / 8275                                     | 1         | 0.94%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 0.94%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 0.94%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 0.94%   |
| Intel Centrino Ultimate-N 6300                                 | 1         | 0.94%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 0.94%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 0.94%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 42        | 56.76%  |
| Intel                 | 17        | 22.97%  |
| Xiaomi                | 5         | 6.76%   |
| Qualcomm Atheros      | 3         | 4.05%   |
| Samsung Electronics   | 2         | 2.7%    |
| OPPO Electronics      | 1         | 1.35%   |
| OKB SAPR              | 1         | 1.35%   |
| MediaTek              | 1         | 1.35%   |
| Huawei Technologies   | 1         | 1.35%   |
| Broadcom              | 1         | 1.35%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 32        | 42.67%  |
| Intel Ethernet Connection (6) I219-V                              | 8         | 10.67%  |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 5         | 6.67%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 5         | 6.67%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 6.67%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.67%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.67%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 2.67%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 2         | 2.67%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.33%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.33%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.33%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.33%   |
| OPPO SM6375-QRD _SN:F4A23F05                                      | 1         | 1.33%   |
| OKB SAPR Ethernet controller                                      | 1         | 1.33%   |
| MediaTek 100026191                                                | 1         | 1.33%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.33%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.33%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.33%   |
| Huawei WLZ-AN00                                                   | 1         | 1.33%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.33%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 99        | 58.58%  |
| Ethernet | 69        | 40.83%  |
| Modem    | 1         | 0.59%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 60        | 59.41%  |
| Ethernet | 41        | 40.59%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 57        | 57%     |
| 1     | 40        | 40%     |
| 0     | 3         | 3%      |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 95        | 92.23%  |
| Yes  | 8         | 7.77%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 40        | 46.51%  |
| Realtek Semiconductor           | 28        | 32.56%  |
| Broadcom                        | 6         | 6.98%   |
| Realtek                         | 2         | 2.33%   |
| Ralink                          | 2         | 2.33%   |
| IMC Networks                    | 2         | 2.33%   |
| Foxconn / Hon Hai               | 2         | 2.33%   |
| Qualcomm Atheros Communications | 1         | 1.16%   |
| Opticis                         | 1         | 1.16%   |
| Lite-On Technology              | 1         | 1.16%   |
| Hewlett-Packard                 | 1         | 1.16%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 24        | 27.91%  |
| Intel Bluetooth wireless interface             | 17        | 19.77%  |
| Intel AX201 Bluetooth                          | 11        | 12.79%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 9         | 10.47%  |
| Realtek  Bluetooth 4.2 Adapter                 | 4         | 4.65%   |
| Intel Bluetooth Device                         | 3         | 3.49%   |
| Realtek 802.11ac WLAN Adapter                  | 2         | 2.33%   |
| Ralink RT3290 Bluetooth                        | 2         | 2.33%   |
| IMC Networks Bluetooth Radio                   | 2         | 2.33%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 1.16%   |
| Opticis Bluetooth Radio                        | 1         | 1.16%   |
| Lite-On Wireless_Device                        | 1         | 1.16%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 1.16%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 1         | 1.16%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 1.16%   |
| Broadcom HP Portable Valentine                 | 1         | 1.16%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 1.16%   |
| Broadcom BCM20702A0 Bluetooth                  | 1         | 1.16%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR           | 1         | 1.16%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 1.16%   |
| Broadcom BCM2045 Bluetooth                     | 1         | 1.16%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 77        | 69.37%  |
| AMD                    | 23        | 20.72%  |
| Nvidia                 | 8         | 7.21%   |
| Zhaoxin                | 1         | 0.9%    |
| MosArt Semiconductor   | 1         | 0.9%    |
| Generalplus Technology | 1         | 0.9%    |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP High Definition Audio Controller                                            | 30        | 22.22%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 19        | 14.07%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 10.37%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 11        | 8.15%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 8         | 5.93%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 5         | 3.7%    |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.22%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.22%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.48%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.48%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 1.48%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.48%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.48%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.48%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.48%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.48%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.48%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.48%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.74%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller                          | 1         | 0.74%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.74%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]                                     | 1         | 0.74%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.74%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.74%   |
| Nvidia Audio device                                                                               | 1         | 0.74%   |
| MosArt Semiconductor MosArt USB Audio Device                                                      | 1         | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.74%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.74%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.74%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.74%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.74%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.74%   |
| AMD Rembrandt Radeon High Definition Audio Controller                                             | 1         | 0.74%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.74%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.74%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 44        | 40.74%  |
| SK hynix            | 16        | 14.81%  |
| Micron Technology   | 10        | 9.26%   |
| Foxline             | 10        | 9.26%   |
| Crucial             | 7         | 6.48%   |
| Kingston            | 4         | 3.7%    |
| Ramaxel Technology  | 3         | 2.78%   |
| Unknown (ABCD)      | 2         | 1.85%   |
| Unknown             | 2         | 1.85%   |
| Elpida              | 2         | 1.85%   |
| SHARETRONIC         | 1         | 0.93%   |
| Qumo                | 1         | 0.93%   |
| Patriot             | 1         | 0.93%   |
| King Tiger          | 1         | 0.93%   |
| ChangXin Memory     | 1         | 0.93%   |
| A-DATA Technology   | 1         | 0.93%   |
| <Invalid>           | 1         | 0.93%   |
| Unknown             | 1         | 0.93%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 14.91%  |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 3.51%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 3         | 2.63%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 3         | 2.63%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 2.63%   |
| Foxline RAM FL3200D4S22-8G 8192MB SODIMM DDR4 3200MT/s           | 3         | 2.63%   |
| Foxline RAM FL2666D4S19-8G 8192MB SODIMM DDR4 2667MT/s           | 3         | 2.63%   |
| Foxline RAM FL2400D4S17S-8G 8192MB SODIMM DDR4 2400MT/s          | 3         | 2.63%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.75%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.75%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.75%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 1.75%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM 1600MT/s                 | 2         | 1.75%   |
| Samsung RAM M471B5173QH0-YK0 4096MB SODIMM DDR3 1600MT/s         | 2         | 1.75%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.75%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.75%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.75%   |
| Samsung RAM M471A1K43DB1-CWE 8192MB SODIMM DDR4 3200MT/s         | 2         | 1.75%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.75%   |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s           | 2         | 1.75%   |
| Crucial RAM CT8G4SFS832A.C8FN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.75%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.88%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 0.88%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 1         | 0.88%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.88%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.88%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.88%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.88%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.88%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.88%   |
| SK hynix RAM H9JCNNNCP3MLYR-N6E 2GB Row Of Chips 6400MT/s        | 1         | 0.88%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.88%   |
| Samsung RAM P4AAF165WA-BCWDE 8GB SODIMM DDR4 3200MT/s            | 1         | 0.88%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.88%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 0.88%   |
| Samsung RAM M471B2873EH1-CH9 1GB SODIMM DDR3 1333MT/s            | 1         | 0.88%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 1         | 0.88%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.88%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 0.88%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.88%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 77        | 79.38%  |
| DDR3   | 14        | 14.43%  |
| LPDDR4 | 3         | 3.09%   |
| LPDDR5 | 1         | 1.03%   |
| LPDDR3 | 1         | 1.03%   |
| DDR2   | 1         | 1.03%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 88        | 86.27%  |
| Row Of Chips | 13        | 12.75%  |
| DIMM         | 1         | 0.98%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 60        | 58.25%  |
| 4096  | 26        | 25.24%  |
| 16384 | 8         | 7.77%   |
| 2048  | 6         | 5.83%   |
| 1024  | 3         | 2.91%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 38        | 37.62%  |
| 2667  | 32        | 31.68%  |
| 1600  | 10        | 9.9%    |
| 2400  | 8         | 7.92%   |
| 3266  | 2         | 1.98%   |
| 1334  | 2         | 1.98%   |
| 1333  | 2         | 1.98%   |
| 6400  | 1         | 0.99%   |
| 3733  | 1         | 0.99%   |
| 2666  | 1         | 0.99%   |
| 2133  | 1         | 0.99%   |
| 1866  | 1         | 0.99%   |
| 1066  | 1         | 0.99%   |
| 667   | 1         | 0.99%   |

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
| Chicony Electronics                    | 22        | 22.22%  |
| Syntek                                 | 19        | 19.19%  |
| IMC Networks                           | 11        | 11.11%  |
| Bison Electronics                      | 7         | 7.07%   |
| Quanta                                 | 5         | 5.05%   |
| Microdia                               | 5         | 5.05%   |
| Acer                                   | 5         | 5.05%   |
| Sunplus Innovation Technology          | 4         | 4.04%   |
| Luxvisions Innotech Limited            | 4         | 4.04%   |
| Realtek Semiconductor                  | 3         | 3.03%   |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.03%   |
| USB Camera CS                          | 2         | 2.02%   |
| Suyin                                  | 2         | 2.02%   |
| SunplusIT                              | 2         | 2.02%   |
| Sonix Technology                       | 2         | 2.02%   |
| GEMBIRD                                | 1         | 1.01%   |
| Alcor Micro                            | 1         | 1.01%   |
| Unknown                                | 1         | 1.01%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                               | Notebooks | Percent |
|-----------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                            | 18        | 18.18%  |
| Chicony USB camera                                  | 10        | 10.1%   |
| IMC Networks ov9734_azurewave_camera                | 4         | 4.04%   |
| IMC Networks Integrated Camera                      | 4         | 4.04%   |
| Chicony Integrated Camera                           | 3         | 3.03%   |
| Bison Integrated Camera                             | 3         | 3.03%   |
| USB Camera CS USB Camera CS                         | 2         | 2.02%   |
| Sonix USB 2.0 Camera                                | 2         | 2.02%   |
| Quanta HP TrueVision HD Camera                      | 2         | 2.02%   |
| Microdia Webcam Vitade AF                           | 2         | 2.02%   |
| Luxvisions Innotech Limited Integrated Camera       | 2         | 2.02%   |
| Chicony USB2.0 Camera                               | 2         | 2.02%   |
| Chicony HD User Facing                              | 2         | 2.02%   |
| Bison Lenovo Integrated Webcam                      | 2         | 2.02%   |
| Acer Integrated Camera                              | 2         | 2.02%   |
| Acer HD Webcam                                      | 2         | 2.02%   |
| Syntek Lenovo EasyCamera                            | 1         | 1.01%   |
| Suyin HP Truevision HD                              | 1         | 1.01%   |
| Suyin Acer CrystalEye Webcam                        | 1         | 1.01%   |
| SunplusIT XiaoMi USB 2.0 Webcam                     | 1         | 1.01%   |
| SunplusIT HBT Camera                                | 1         | 1.01%   |
| Sunplus Integrated_Webcam_HD                        | 1         | 1.01%   |
| Sunplus BKX Usb FHD Camera                          | 1         | 1.01%   |
| Sunplus Asus Webcam                                 | 1         | 1.01%   |
| Sunplus 1080P Webcam                                | 1         | 1.01%   |
| Realtek Integrated_Webcam_HD                        | 1         | 1.01%   |
| Realtek HP Truevision HD                            | 1         | 1.01%   |
| Realtek 2SF022                                      | 1         | 1.01%   |
| Quanta USB HD Webcam                                | 1         | 1.01%   |
| Quanta HP Webcam                                    | 1         | 1.01%   |
| Quanta HD Camera                                    | 1         | 1.01%   |
| Microdia USB 2.0 Camera                             | 1         | 1.01%   |
| Microdia Integrated_Webcam_HD                       | 1         | 1.01%   |
| Microdia Integrated Webcam                          | 1         | 1.01%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 1         | 1.01%   |
| Luxvisions Innotech Limited HP HD Camera            | 1         | 1.01%   |
| IMC Networks USB2.0 VGA UVC WebCam                  | 1         | 1.01%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 1         | 1.01%   |
| IMC Networks HD Camera                              | 1         | 1.01%   |
| GEMBIRD USB2.0 PC CAMERA                            | 1         | 1.01%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 7         | 70%     |
| Synaptics                  | 2         | 20%     |
| Validity Sensors           | 1         | 10%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                      | Notebooks | Percent |
|--------------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device        | 7         | 70%     |
| Synaptics UWP WBDI Device                  | 2         | 20%     |
| Validity Sensors VFS451 Fingerprint Reader | 1         | 10%     |

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
| 0     | 69        | 67.65%  |
| 1     | 25        | 24.51%  |
| 2     | 8         | 7.84%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Graphics card         | 14        | 35.9%   |
| Net/wireless          | 10        | 25.64%  |
| Fingerprint reader    | 10        | 25.64%  |
| Bluetooth             | 2         | 5.13%   |
| Sound                 | 1         | 2.56%   |
| Net/ethernet          | 1         | 2.56%   |
| Multimedia controller | 1         | 2.56%   |

