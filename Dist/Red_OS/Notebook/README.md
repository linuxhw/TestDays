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

Total: 150

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Red OS 7.3.1 | 44        | 44.9%   |
| Red OS 7.3.2 | 33        | 33.67%  |
| Red OS 7.3   | 20        | 20.41%  |
| Red OS 7.2   | 1         | 1.02%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Red OS | 93        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64   | 25        | 24.04%  |
| 5.15.72-1.el7.3.x86_64 | 20        | 19.23%  |
| 5.15.87-1.el7.3.x86_64 | 10        | 9.62%   |
| 5.15.35-4.el7.3.x86_64 | 10        | 9.62%   |
| 5.10.29-1.el7.x86_64   | 10        | 9.62%   |
| 5.15.35-1.el7.3.x86_64 | 6         | 5.77%   |
| 5.15.35-5.el7.3.x86_64 | 4         | 3.85%   |
| 5.15.78-2.el7.3.x86_64 | 3         | 2.88%   |
| 5.10.1-1.el7.x86_64    | 3         | 2.88%   |
| 5.15.10-4.el7.x86_64   | 2         | 1.92%   |
| 5.10.29-3.el7.x86_64   | 2         | 1.92%   |
| 5.10.24-2.el7.x86_64   | 2         | 1.92%   |
| 6.1.20-2.el7.3.x86_64  | 1         | 0.96%   |
| 5.18.1-1.el7.x86_64    | 1         | 0.96%   |
| 5.15.10-3.el7.x86_64   | 1         | 0.96%   |
| 5.15.10-2.el7.x86_64   | 1         | 0.96%   |
| 5.13.15-1.el7.x86_64   | 1         | 0.96%   |
| 5.10.24-1.el7.x86_64   | 1         | 0.96%   |
| 4.19.79-1.el7.x86_64   | 1         | 0.96%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.10 | 29        | 28.16%  |
| 5.15.72 | 20        | 19.42%  |
| 5.15.35 | 19        | 18.45%  |
| 5.10.29 | 12        | 11.65%  |
| 5.15.87 | 10        | 9.71%   |
| 5.15.78 | 3         | 2.91%   |
| 5.10.24 | 3         | 2.91%   |
| 5.10.1  | 3         | 2.91%   |
| 6.1.20  | 1         | 0.97%   |
| 5.18.1  | 1         | 0.97%   |
| 5.13.15 | 1         | 0.97%   |
| 4.19.79 | 1         | 0.97%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 76        | 78.35%  |
| 5.10    | 17        | 17.53%  |
| 6.1     | 1         | 1.03%   |
| 5.18    | 1         | 1.03%   |
| 5.13    | 1         | 1.03%   |
| 4.19    | 1         | 1.03%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 93        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 81        | 86.17%  |
| Cinnamon   | 12        | 12.77%  |
| X-Cinnamon | 1         | 1.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 89        | 93.68%  |
| Wayland | 6         | 6.32%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 89        | 93.68%  |
| SDDM    | 3         | 3.16%   |
| Unknown | 3         | 3.16%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 71        | 73.96%  |
| ru_RU   | 24        | 25%     |
| en_US   | 1         | 1.04%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 81        | 85.26%  |
| BIOS | 14        | 14.74%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 92        | 97.87%  |
| Overlay | 1         | 1.06%   |
| Btrfs   | 1         | 1.06%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 80        | 85.11%  |
| MBR     | 11        | 11.7%   |
| Unknown | 3         | 3.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 84        | 89.36%  |
| Yes       | 10        | 10.64%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 75%     |
| Yes       | 24        | 25%     |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 37        | 39.78%  |
| Hewlett-Packard                | 13        | 13.98%  |
| ICL                            | 5         | 5.38%   |
| MSI                            | 4         | 4.3%    |
| HUAWEI                         | 4         | 4.3%    |
| Aquarius                       | 4         | 4.3%    |
| Kraftway                       | 3         | 3.23%   |
| Digma                          | 3         | 3.23%   |
| ASUSTek Computer               | 3         | 3.23%   |
| Acer                           | 3         | 3.23%   |
| IP3 Technology                 | 2         | 2.15%   |
| HONOR                          | 2         | 2.15%   |
| 3Logic Group                   | 2         | 2.15%   |
| THUNDEROBOT                    | 1         | 1.08%   |
| Shanghai Zhaoxin Semiconductor | 1         | 1.08%   |
| Pegatron                       | 1         | 1.08%   |
| mtech                          | 1         | 1.08%   |
| Graviton                       | 1         | 1.08%   |
| Gigabyte Technology            | 1         | 1.08%   |
| Dell                           | 1         | 1.08%   |
| Unknown                        | 1         | 1.08%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE                  | 17        | 18.28%  |
| Kraftway ACCORD                      | 3         | 3.23%   |
| ICL RAYbook Si1512                   | 3         | 3.23%   |
| HP Laptop 15s-eq1xxx                 | 3         | 3.23%   |
| Lenovo ThinkBook 15 G3 ACL 21A4      | 2         | 2.15%   |
| IP3 ACN30                            | 2         | 2.15%   |
| Unknown                              | 2         | 2.15%   |
| THUNDEROBOT 911AirD                  | 1         | 1.08%   |
| Shanghai Zhaoxin ZXE CRB             | 1         | 1.08%   |
| Pegatron A35                         | 1         | 1.08%   |
| mtech MTL1578                        | 1         | 1.08%   |
| MSI Sword 15 A12UE                   | 1         | 1.08%   |
| MSI Modern 15 B12M                   | 1         | 1.08%   |
| MSI GL62 6QF                         | 1         | 1.08%   |
| MSI FX610                            | 1         | 1.08%   |
| Lenovo V130-15IKB 81HN               | 1         | 1.08%   |
| Lenovo ThinkPad X220 4290RB3         | 1         | 1.08%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2DE00 | 1         | 1.08%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2DD00 | 1         | 1.08%   |
| Lenovo ThinkPad E15 Gen 4 21E6009UGP | 1         | 1.08%   |
| Lenovo ThinkBook 15 G2 ITL 20VE      | 1         | 1.08%   |
| Lenovo ThinkBook 15 G2 ARE 20VG      | 1         | 1.08%   |
| Lenovo ThinkBook 14-IIL 20SL         | 1         | 1.08%   |
| Lenovo IdeaPad L340-15IWL 81LG       | 1         | 1.08%   |
| Lenovo IdeaPad L340-15API 81LW       | 1         | 1.08%   |
| Lenovo IdeaPad 700-15ISK 80RU        | 1         | 1.08%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7     | 1         | 1.08%   |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 1         | 1.08%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 1.08%   |
| Lenovo IdeaPad 3 15ITL05 81X8        | 1         | 1.08%   |
| Lenovo IdeaPad 1 15ALC7 82R4         | 1         | 1.08%   |
| Lenovo G570 20079                    | 1         | 1.08%   |
| Lenovo B590 20208                    | 1         | 1.08%   |
| ICL RAYbook Si1514                   | 1         | 1.08%   |
| HUAWEI NBLK-WAX9X                    | 1         | 1.08%   |
| HUAWEI NBD-WXX9                      | 1         | 1.08%   |
| HUAWEI BOHL-WXX9                     | 1         | 1.08%   |
| HUAWEI BOD-WXX9                      | 1         | 1.08%   |
| HONOR NBR-WAX9                       | 1         | 1.08%   |
| HONOR BMH-WCX9                       | 1         | 1.08%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                 | Notebooks | Percent |
|----------------------|-----------|---------|
| Lenovo V15-IWL       | 17        | 18.28%  |
| Lenovo IdeaPad       | 8         | 8.6%    |
| Lenovo ThinkBook     | 5         | 5.38%   |
| HP Laptop            | 5         | 5.38%   |
| Lenovo ThinkPad      | 4         | 4.3%    |
| ICL RAYbook          | 4         | 4.3%    |
| Kraftway ACCORD      | 3         | 3.23%   |
| Digma EVE            | 3         | 3.23%   |
| IP3 ACN30            | 2         | 2.15%   |
| HP ProBook           | 2         | 2.15%   |
| HP Pavilion          | 2         | 2.15%   |
| Aquarius NS685U      | 2         | 2.15%   |
| Acer Aspire          | 2         | 2.15%   |
| Unknown              | 2         | 2.15%   |
| THUNDEROBOT 911AirD  | 1         | 1.08%   |
| Shanghai Zhaoxin ZXE | 1         | 1.08%   |
| Pegatron A35         | 1         | 1.08%   |
| mtech MTL1578        | 1         | 1.08%   |
| MSI Sword            | 1         | 1.08%   |
| MSI Modern           | 1         | 1.08%   |
| MSI GL62             | 1         | 1.08%   |
| MSI FX610            | 1         | 1.08%   |
| Lenovo V130-15IKB    | 1         | 1.08%   |
| Lenovo G570          | 1         | 1.08%   |
| Lenovo B590          | 1         | 1.08%   |
| HUAWEI NBLK-WAX9X    | 1         | 1.08%   |
| HUAWEI NBD-WXX9      | 1         | 1.08%   |
| HUAWEI BOHL-WXX9     | 1         | 1.08%   |
| HUAWEI BOD-WXX9      | 1         | 1.08%   |
| HONOR NBR-WAX9       | 1         | 1.08%   |
| HONOR BMH-WCX9       | 1         | 1.08%   |
| HP OMEN              | 1         | 1.08%   |
| HP Notebook          | 1         | 1.08%   |
| HP G62               | 1         | 1.08%   |
| HP EliteBook         | 1         | 1.08%   |
| Graviton N14I-T      | 1         | 1.08%   |
| Gigabyte G5          | 1         | 1.08%   |
| Dell Vostro          | 1         | 1.08%   |
| ASUS X75VD           | 1         | 1.08%   |
| ASUS X540NV          | 1         | 1.08%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 28        | 30.11%  |
| 2021 | 22        | 23.66%  |
| 2020 | 13        | 13.98%  |
| 2022 | 11        | 11.83%  |
| 2010 | 4         | 4.3%    |
| 2017 | 3         | 3.23%   |
| 2012 | 3         | 3.23%   |
| 2011 | 3         | 3.23%   |
| 2018 | 2         | 2.15%   |
| 2016 | 1         | 1.08%   |
| 2015 | 1         | 1.08%   |
| 2013 | 1         | 1.08%   |
| 2007 | 1         | 1.08%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 93        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 93        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 93        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 61        | 65.59%  |
| 3.01-4.0   | 12        | 12.9%   |
| 16.01-24.0 | 9         | 9.68%   |
| 8.01-16.0  | 9         | 9.68%   |
| 2.01-3.0   | 2         | 2.15%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 57        | 58.16%  |
| 2.01-3.0 | 24        | 24.49%  |
| 0.51-1.0 | 9         | 9.18%   |
| 3.01-4.0 | 6         | 6.12%   |
| 4.01-8.0 | 2         | 2.04%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 83        | 86.46%  |
| 2      | 8         | 8.33%   |
| 3      | 4         | 4.17%   |
| 4      | 1         | 1.04%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 78        | 82.98%  |
| Yes       | 16        | 17.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 61        | 65.59%  |
| No        | 32        | 34.41%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 98.92%  |
| No        | 1         | 1.08%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 87.1%   |
| No        | 12        | 12.9%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 92        | 98.92%  |
| Ukraine | 1         | 1.08%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Moscow           | 23        | 23.71%  |
| Salekhard        | 21        | 21.65%  |
| Murom            | 14        | 14.43%  |
| St Petersburg    | 3         | 3.09%   |
| Ryazan           | 3         | 3.09%   |
| Yekaterinburg    | 2         | 2.06%   |
| Yakutsk          | 2         | 2.06%   |
| Vladimir         | 2         | 2.06%   |
| Perm             | 2         | 2.06%   |
| Novy Urengoy     | 2         | 2.06%   |
| Nizhniy Novgorod | 2         | 2.06%   |
| Kursk            | 2         | 2.06%   |
| Krasnodar        | 2         | 2.06%   |
| Yaroslavl        | 1         | 1.03%   |
| Volzhskiy        | 1         | 1.03%   |
| Ulyanovsk        | 1         | 1.03%   |
| Tver             | 1         | 1.03%   |
| Strezhevoy       | 1         | 1.03%   |
| Sevastopol       | 1         | 1.03%   |
| Saratov          | 1         | 1.03%   |
| Omsk             | 1         | 1.03%   |
| Novosibirsk      | 1         | 1.03%   |
| Muromskiy        | 1         | 1.03%   |
| Krasnoyarsk      | 1         | 1.03%   |
| Kirzhach         | 1         | 1.03%   |
| Khabarovsk       | 1         | 1.03%   |
| Kaluga           | 1         | 1.03%   |
| Borinskoye       | 1         | 1.03%   |
| Belgorod         | 1         | 1.03%   |
| Balashikha       | 1         | 1.03%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 26        | 35     | 24.3%   |
| WDC                 | 14        | 16     | 13.08%  |
| SK hynix            | 7         | 9      | 6.54%   |
| Seagate             | 6         | 7      | 5.61%   |
| Toshiba             | 5         | 16     | 4.67%   |
| Foxline             | 5         | 5      | 4.67%   |
| A-DATA Technology   | 5         | 5      | 4.67%   |
| Silicon Motion      | 4         | 4      | 3.74%   |
| HGST                | 4         | 4      | 3.74%   |
| Phison              | 3         | 3      | 2.8%    |
| Unknown             | 2         | 2      | 1.87%   |
| UMIS                | 2         | 2      | 1.87%   |
| Micron Technology   | 2         | 6      | 1.87%   |
| Kingston            | 2         | 2      | 1.87%   |
| Intel               | 2         | 2      | 1.87%   |
| Gigabyte Technology | 2         | 2      | 1.87%   |
| Crucial             | 2         | 2      | 1.87%   |
| YMTC                | 1         | 1      | 0.93%   |
| Transcend           | 1         | 1      | 0.93%   |
| SPCC Sol            | 1         | 1      | 0.93%   |
| SanDisk             | 1         | 1      | 0.93%   |
| Netac               | 1         | 1      | 0.93%   |
| KIOXIA              | 1         | 1      | 0.93%   |
| KingSpec            | 1         | 1      | 0.93%   |
| Kimtigo             | 1         | 2      | 0.93%   |
| JMicron Technology  | 1         | 1      | 0.93%   |
| ITHOO               | 1         | 1      | 0.93%   |
| HUAWEI              | 1         | 1      | 0.93%   |
| China               | 1         | 1      | 0.93%   |
| Apacer              | 1         | 2      | 0.93%   |
| Unknown             | 1         | 1      | 0.93%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB          | 18        | 16.51%  |
| Foxline FLSSD256M80E13TCX5 256GB          | 5         | 4.59%   |
| Silicon Motion Wodposit NVMe SSD 256GB    | 4         | 3.67%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB      | 2         | 1.83%   |
| Toshiba MQ01ABF050 500GB                  | 2         | 1.83%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB    | 2         | 1.83%   |
| SK hynix PC711 HFS512GDE9X073N 512GB      | 2         | 1.83%   |
| Samsung MZALQ512HALU-000L2 512GB          | 2         | 1.83%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB          | 2         | 1.83%   |
| A-DATA SU650 240GB SSD                    | 2         | 1.83%   |
| YMTC PC210-512GB-B                        | 1         | 0.92%   |
| WDC WDS500G2B0B-00YS70 500GB SSD          | 1         | 0.92%   |
| WDC WDS250G2B0A-00SM50 250GB SSD          | 1         | 0.92%   |
| WDC WD5000BPVT-55HXZT3 500GB              | 1         | 0.92%   |
| WDC WD3200BPVT-24JJ5T0 320GB              | 1         | 0.92%   |
| WDC WD2500BEVT-22ZCT0 250GB               | 1         | 0.92%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 0.92%   |
| WDC WD10SPZX-00Z10T0 1TB                  | 1         | 0.92%   |
| WDC WD10JPVX-22JC3T0 1TB                  | 1         | 0.92%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 0.92%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB      | 1         | 0.92%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 0.92%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB      | 1         | 0.92%   |
| Unknown SLD128  128GB                     | 1         | 0.92%   |
| Unknown 58K722  128GB                     | 1         | 0.92%   |
| UMIS RPJTJ512MEE1OWX 512GB                | 1         | 0.92%   |
| UMIS RPJTJ256MGE1QDQ 256GB                | 1         | 0.92%   |
| Transcend TS240GMTS820S 240GB SSD         | 1         | 0.92%   |
| Toshiba MK5075GSX 500GB                   | 1         | 0.92%   |
| Toshiba MK5059GSXP 500GB                  | 1         | 0.92%   |
| Toshiba KXG60ZNV512G 512GB                | 1         | 0.92%   |
| Toshiba KXG60ZNV256G 256GB                | 1         | 0.92%   |
| SPCC Sol id State Disk 256GB SSD          | 1         | 0.92%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB    | 1         | 0.92%   |
| SK hynix SKHynix_HFS256GDE9X081N 256GB    | 1         | 0.92%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 0.92%   |
| SK hynix BC511 256GB                      | 1         | 0.92%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 0.92%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 0.92%   |
| Seagate ST500LM030-1RK17D 500GB           | 1         | 0.92%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 6         | 8      | 31.58%  |
| Seagate | 6         | 7      | 31.58%  |
| HGST    | 4         | 4      | 21.05%  |
| Toshiba | 3         | 13     | 15.79%  |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 4         | 4      | 22.22%  |
| WDC                 | 2         | 2      | 11.11%  |
| Samsung Electronics | 2         | 2      | 11.11%  |
| Crucial             | 2         | 2      | 11.11%  |
| Transcend           | 1         | 1      | 5.56%   |
| SPCC Sol            | 1         | 1      | 5.56%   |
| SanDisk             | 1         | 1      | 5.56%   |
| Netac               | 1         | 1      | 5.56%   |
| Kingston            | 1         | 1      | 5.56%   |
| KingSpec            | 1         | 1      | 5.56%   |
| China               | 1         | 1      | 5.56%   |
| Apacer              | 1         | 2      | 5.56%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 63        | 82     | 60.58%  |
| SSD     | 18        | 19     | 17.31%  |
| HDD     | 18        | 32     | 17.31%  |
| MMC     | 3         | 3      | 2.88%   |
| Unknown | 2         | 2      | 1.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 63        | 81     | 61.76%  |
| SATA | 33        | 49     | 32.35%  |
| SAS  | 3         | 5      | 2.94%   |
| MMC  | 3         | 3      | 2.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 27        | 41     | 77.14%  |
| 0.51-1.0   | 8         | 10     | 22.86%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 53        | 54.64%  |
| 251-500    | 22        | 22.68%  |
| 51-100     | 8         | 8.25%   |
| 501-1000   | 6         | 6.19%   |
| 1001-2000  | 4         | 4.12%   |
| 1-20       | 3         | 3.09%   |
| 21-50      | 1         | 1.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 72        | 73.47%  |
| 21-50    | 15        | 15.31%  |
| 101-250  | 4         | 4.08%   |
| 51-100   | 3         | 3.06%   |
| 251-500  | 2         | 2.04%   |
| 501-1000 | 2         | 2.04%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 11.11%  |
| Toshiba MQ01ABF050 500GB            | 1         | 8      | 11.11%  |
| Toshiba MK5075GSX 500GB             | 1         | 2      | 11.11%  |
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
| Toshiba           | 2         | 11     | 25%     |
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
| Toshiba | 2         | 11     | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 15     | 75%     |
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
| Works    | 84        | 108    | 84.85%  |
| Malfunc  | 8         | 17     | 8.08%   |
| Detected | 7         | 13     | 7.07%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 64        | 46.38%  |
| Samsung Electronics          | 24        | 17.39%  |
| AMD                          | 11        | 7.97%   |
| Phison Electronics           | 10        | 7.25%   |
| SK hynix                     | 7         | 5.07%   |
| SanDisk                      | 6         | 4.35%   |
| Silicon Motion               | 4         | 2.9%    |
| Union Memory (Shenzhen)      | 2         | 1.45%   |
| Toshiba America Info Systems | 2         | 1.45%   |
| Micron Technology            | 2         | 1.45%   |
| Zhaoxin                      | 1         | 0.72%   |
| Yangtze Memory Technologies  | 1         | 0.72%   |
| ShenZhen TIGO Semiconductor  | 1         | 0.72%   |
| Realtek Semiconductor        | 1         | 0.72%   |
| KIOXIA                       | 1         | 0.72%   |
| Kingston Technology Company  | 1         | 0.72%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 29        | 20.14%  |
| Samsung NVMe SSD Controller 980                                                  | 24        | 16.67%  |
| Phison PS5013 E13 NVMe Controller                                                | 9         | 6.25%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 9         | 6.25%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                             | 6         | 4.17%   |
| Intel Tiger Lake-LP SATA Controller                                              | 6         | 4.17%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 4         | 2.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 2.78%   |
| Intel Volume Management Device NVMe RAID Controller                              | 4         | 2.78%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 2.78%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 3         | 2.08%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 2.08%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 1.39%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.39%   |
| Intel Tiger Lake SATA AHCI Controller                                            | 2         | 1.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 2         | 1.39%   |
| Intel SSD 660P Series                                                            | 2         | 1.39%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.39%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.39%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 2         | 1.39%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 2         | 1.39%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G StorX AHCI Controller                     | 1         | 0.69%   |
| Yangtze Memory Non-Volatile memory controller                                    | 1         | 0.69%   |
| SK hynix BC511 NVMe SSD                                                          | 1         | 0.69%   |
| ShenZhen TIGO Non-Volatile memory controller                                     | 1         | 0.69%   |
| SanDisk PC SN530 NVMe SSD                                                        | 1         | 0.69%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.69%   |
| Realtek NVMe Controller                                                          | 1         | 0.69%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.69%   |
| Micron 2450 NVMe SSD (DRAM-less)                                                 | 1         | 0.69%   |
| Micron 2200S NVMe SSD                                                            | 1         | 0.69%   |
| KIOXIA NVMe SSD Controller BG4                                                   | 1         | 0.69%   |
| Kingston Company NVMe Controller                                                 | 1         | 0.69%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.69%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.69%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.69%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 1         | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.69%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.69%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                   | 1         | 0.69%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 74        | 51.75%  |
| NVMe | 63        | 44.06%  |
| RAID | 4         | 2.8%    |
| IDE  | 2         | 1.4%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 71        | 76.34%  |
| AMD          | 21        | 22.58%  |
| CentaurHauls | 1         | 1.08%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Notebooks | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 19.35%  |
| Intel Core i5-8279U CPU @ 2.40GHz             | 6         | 6.45%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 6         | 6.45%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 5         | 5.38%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 3.23%   |
| AMD Ryzen 3 5400U with Radeon Graphics        | 3         | 3.23%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 3         | 3.23%   |
| AMD Ryzen 3 4300U with Radeon Graphics        | 3         | 3.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 2.15%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 2         | 2.15%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 2.15%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 2.15%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 1.08%   |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 1.08%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 1         | 1.08%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 1         | 1.08%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 1.08%   |
| Intel Core i5-6300HQ CPU @ 2.30GHz            | 1         | 1.08%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 1         | 1.08%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 1.08%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 1.08%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 1         | 1.08%   |
| Intel Core i5 CPU M 520 @ 2.40GHz             | 1         | 1.08%   |
| Intel Core i3-9300 CPU @ 3.70GHz              | 1         | 1.08%   |
| Intel Core i3-7020U CPU @ 2.30GHz             | 1         | 1.08%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 1         | 1.08%   |
| Intel Core i3-3110M CPU @ 2.40GHz             | 1         | 1.08%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 1         | 1.08%   |
| Intel Core i3-2310M CPU @ 2.10GHz             | 1         | 1.08%   |
| Intel Core i3-10110U CPU @ 2.10GHz            | 1         | 1.08%   |
| Intel Core i3 CPU M 330 @ 2.13GHz             | 1         | 1.08%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz          | 1         | 1.08%   |
| Intel Celeron CPU B815 @ 1.60GHz              | 1         | 1.08%   |
| Intel 12th Gen Core i7-1270P                  | 1         | 1.08%   |
| Intel 12th Gen Core i7-12700H                 | 1         | 1.08%   |
| Intel 12th Gen Core i5-1250P                  | 1         | 1.08%   |
| Intel 12th Gen Core i5-1235U                  | 1         | 1.08%   |
| Intel 12th Gen Core i3-1215U                  | 1         | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 1         | 1.08%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 1         | 1.08%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 39        | 41.94%  |
| Other            | 18        | 19.35%  |
| AMD Ryzen 3      | 9         | 9.68%   |
| Intel Core i3    | 8         | 8.6%    |
| AMD Ryzen 5      | 8         | 8.6%    |
| Intel Celeron    | 3         | 3.23%   |
| Intel Pentium    | 2         | 2.15%   |
| AMD Phenom II    | 2         | 2.15%   |
| Intel Core i7    | 1         | 1.08%   |
| Intel Core 2 Duo | 1         | 1.08%   |
| AMD Ryzen 7      | 1         | 1.08%   |
| AMD A4           | 1         | 1.08%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 62        | 66.67%  |
| 2      | 18        | 19.35%  |
| 6      | 8         | 8.6%    |
| 12     | 2         | 2.15%   |
| 14     | 1         | 1.08%   |
| 10     | 1         | 1.08%   |
| 3      | 1         | 1.08%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 93        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 74        | 79.57%  |
| 1      | 19        | 20.43%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 93        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 21        | 22.34%  |
| 0x806ea    | 12        | 12.77%  |
| 0x806c1    | 10        | 10.64%  |
| 0x08600106 | 5         | 5.32%   |
| 0x206a7    | 4         | 4.26%   |
| 0x0a50000c | 4         | 4.26%   |
| 0x08608103 | 4         | 4.26%   |
| 0x906a3    | 3         | 3.19%   |
| 0x906a4    | 2         | 2.13%   |
| 0x806d1    | 2         | 2.13%   |
| 0x506e3    | 2         | 2.13%   |
| 0x506ca    | 2         | 2.13%   |
| 0x40651    | 2         | 2.13%   |
| 0x306a9    | 2         | 2.13%   |
| 0x08108102 | 2         | 2.13%   |
| 0x010000c8 | 2         | 2.13%   |
| Unknown    | 2         | 2.13%   |
| 0x906eb    | 1         | 1.06%   |
| 0x906e9    | 1         | 1.06%   |
| 0x706e5    | 1         | 1.06%   |
| 0x6fa      | 1         | 1.06%   |
| 0x506c9    | 1         | 1.06%   |
| 0x406c4    | 1         | 1.06%   |
| 0x20655    | 1         | 1.06%   |
| 0x20652    | 1         | 1.06%   |
| 0x0a50000d | 1         | 1.06%   |
| 0x08600104 | 1         | 1.06%   |
| 0x08108109 | 1         | 1.06%   |
| 0x0810100b | 1         | 1.06%   |
| 0x06006705 | 1         | 1.06%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 36        | 38.71%  |
| TigerLake        | 10        | 10.75%  |
| Zen 2            | 6         | 6.45%   |
| Alderlake Hybrid | 5         | 5.38%   |
| Unknown          | 5         | 5.38%   |
| Zen 3            | 4         | 4.3%    |
| SandyBridge      | 4         | 4.3%    |
| Zen+             | 3         | 3.23%   |
| IceLake          | 3         | 3.23%   |
| Goldmont         | 3         | 3.23%   |
| Westmere         | 2         | 2.15%   |
| Skylake          | 2         | 2.15%   |
| K10              | 2         | 2.15%   |
| IvyBridge        | 2         | 2.15%   |
| Haswell          | 2         | 2.15%   |
| Zen              | 1         | 1.08%   |
| Silvermont       | 1         | 1.08%   |
| Excavator        | 1         | 1.08%   |
| Core             | 1         | 1.08%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 70        | 63.06%  |
| AMD     | 24        | 21.62%  |
| Nvidia  | 16        | 14.41%  |
| Zhaoxin | 1         | 0.9%    |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                     | Notebooks | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 18        | 15.79%  |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                          | 11        | 9.65%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 7         | 6.14%   |
| AMD Renoir                                                                | 6         | 5.26%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 3.51%   |
| AMD Lucienne                                                              | 4         | 3.51%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 4         | 3.51%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 3         | 2.63%   |
| Intel CometLake-U GT2 [UHD Graphics]                                      | 3         | 2.63%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 3         | 2.63%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 2.63%   |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                              | 3         | 2.63%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.75%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.75%   |
| Intel HD Graphics 530                                                     | 2         | 1.75%   |
| Intel HD Graphics 500                                                     | 2         | 1.75%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 2         | 1.75%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 2         | 1.75%   |
| Zhaoxin ZX-E C-960 GPU                                                    | 1         | 0.88%   |
| Nvidia TU117M [GeForce MX550]                                             | 1         | 0.88%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.88%   |
| Nvidia GP108M [GeForce MX250]                                             | 1         | 0.88%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                   | 1         | 0.88%   |
| Nvidia GM108M [GeForce MX110]                                             | 1         | 0.88%   |
| Nvidia GM108M [GeForce 920MX]                                             | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 960M]                                          | 1         | 0.88%   |
| Nvidia GM107M [GeForce GTX 950M]                                          | 1         | 0.88%   |
| Nvidia GK208M [GeForce GT 740M]                                           | 1         | 0.88%   |
| Nvidia GF119M [GeForce 610M]                                              | 1         | 0.88%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]      | 1         | 0.88%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                         | 1         | 0.88%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                   | 1         | 0.88%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                           | 1         | 0.88%   |
| Intel UHD Graphics 620                                                    | 1         | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)       | 1         | 0.88%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)         | 1         | 0.88%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                    | 1         | 0.88%   |
| Intel HD Graphics 630                                                     | 1         | 0.88%   |
| Intel HD Graphics 620                                                     | 1         | 0.88%   |
| Intel Core Processor Integrated Graphics Controller                       | 1         | 0.88%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 53        | 56.99%  |
| 1 x AMD        | 18        | 19.35%  |
| Intel + Nvidia | 14        | 15.05%  |
| Intel + AMD    | 3         | 3.23%   |
| 2 x AMD        | 2         | 2.15%   |
| 1 x Zhaoxin    | 1         | 1.08%   |
| 1 x Nvidia     | 1         | 1.08%   |
| AMD + Nvidia   | 1         | 1.08%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 85        | 89.47%  |
| Unknown     | 8         | 8.42%   |
| Proprietary | 2         | 2.11%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 60.42%  |
| 1.01-2.0   | 15        | 15.63%  |
| 0.01-0.5   | 11        | 11.46%  |
| 3.01-4.0   | 6         | 6.25%   |
| 0.51-1.0   | 6         | 6.25%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 46        | 46.46%  |
| LG Display           | 13        | 13.13%  |
| Chimei Innolux       | 10        | 10.1%   |
| Samsung Electronics  | 8         | 8.08%   |
| AU Optronics         | 5         | 5.05%   |
| PANDA                | 4         | 4.04%   |
| Philips              | 2         | 2.02%   |
| NLE                  | 2         | 2.02%   |
| Acer                 | 2         | 2.02%   |
| ViewSonic            | 1         | 1.01%   |
| Toshiba              | 1         | 1.01%   |
| RGT                  | 1         | 1.01%   |
| Lenovo               | 1         | 1.01%   |
| Iiyama               | 1         | 1.01%   |
| HUAWEI               | 1         | 1.01%   |
| Ancor Communications | 1         | 1.01%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 17        | 17.17%  |
| BOE LCD Monitor BOE09C5 1920x1080 345x194mm 15.6-inch                   | 9         | 9.09%   |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch            | 3         | 3.03%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch        | 3         | 3.03%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                   | 3         | 3.03%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 3         | 3.03%   |
| NLE Newline NLE0032 3840x2160 944x398mm 40.3-inch                       | 2         | 2.02%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 2         | 2.02%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 2.02%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 2         | 2.02%   |
| BOE LCD Monitor BOE0936 1920x1080 344x194mm 15.5-inch                   | 2         | 2.02%   |
| BOE LCD Monitor BOE0900 1920x1080 344x194mm 15.5-inch                   | 2         | 2.02%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                    | 2         | 2.02%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch          | 2         | 2.02%   |
| ViewSonic PJ VSC9B34 1920x1080                                          | 1         | 1.01%   |
| Toshiba LCD Monitor LCD58EB 1280x800 261x163mm 12.1-inch                | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch    | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch    | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch    | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch    | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 1872x1053mm 84.6-inch | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1872x1053mm 84.6-inch | 1         | 1.01%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 1210x680mm 54.6-inch  | 1         | 1.01%   |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                   | 1         | 1.01%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                    | 1         | 1.01%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 1         | 1.01%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                 | 1         | 1.01%   |
| PANDA LM116LF3L02 NCP000A 1920x1080 256x144mm 11.6-inch                 | 1         | 1.01%   |
| PANDA LCD Monitor NCP0065 1920x1080 309x174mm 14.0-inch                 | 1         | 1.01%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                 | 1         | 1.01%   |
| LG Display LCD Monitor LGDD302 1366x768 277x156mm 12.5-inch             | 1         | 1.01%   |
| LG Display LCD Monitor LGD0671 1920x1080 382x215mm 17.3-inch            | 1         | 1.01%   |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch            | 1         | 1.01%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 1.01%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch            | 1         | 1.01%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch             | 1         | 1.01%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch             | 1         | 1.01%   |
| LG Display LCD Monitor LGD0212 1366x768 309x174mm 14.0-inch             | 1         | 1.01%   |
| Lenovo LEN LI2264d LEN65C5 1920x1080 476x268mm 21.5-inch                | 1         | 1.01%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Notebooks | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 71        | 77.17%  |
| 1366x768 (WXGA)    | 12        | 13.04%  |
| 3840x2160 (4K)     | 3         | 3.26%   |
| 3440x1440          | 1         | 1.09%   |
| 2240x1400          | 1         | 1.09%   |
| 1680x1050 (WSXGA+) | 1         | 1.09%   |
| 1600x900 (HD+)     | 1         | 1.09%   |
| 1280x800 (WXGA)    | 1         | 1.09%   |
| 1280x1024 (SXGA)   | 1         | 1.09%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 67        | 68.37%  |
| 13      | 6         | 6.12%   |
| 14      | 5         | 5.1%    |
| 21      | 3         | 3.06%   |
| 17      | 3         | 3.06%   |
| 84      | 2         | 2.04%   |
| 40      | 2         | 2.04%   |
| 24      | 2         | 2.04%   |
| 12      | 2         | 2.04%   |
| 54      | 1         | 1.02%   |
| 34      | 1         | 1.02%   |
| 22      | 1         | 1.02%   |
| 19      | 1         | 1.02%   |
| 11      | 1         | 1.02%   |
| Unknown | 1         | 1.02%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 77        | 78.57%  |
| 401-500     | 4         | 4.08%   |
| 351-400     | 4         | 4.08%   |
| 201-300     | 4         | 4.08%   |
| 501-600     | 2         | 2.04%   |
| 1501-2000   | 2         | 2.04%   |
| 901-1000    | 2         | 2.04%   |
| 701-800     | 1         | 1.02%   |
| 1001-1500   | 1         | 1.02%   |
| Unknown     | 1         | 1.02%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 83        | 92.22%  |
| 21/9  | 3         | 3.33%   |
| 16/10 | 3         | 3.33%   |
| 5/4   | 1         | 1.11%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 67        | 68.37%  |
| 81-90          | 10        | 10.2%   |
| 201-250        | 6         | 6.12%   |
| More than 1000 | 3         | 3.06%   |
| 121-130        | 3         | 3.06%   |
| 61-70          | 2         | 2.04%   |
| 501-1000       | 2         | 2.04%   |
| 71-80          | 1         | 1.02%   |
| 51-60          | 1         | 1.02%   |
| 351-500        | 1         | 1.02%   |
| 151-200        | 1         | 1.02%   |
| Unknown        | 1         | 1.02%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 69        | 71.88%  |
| 101-120 | 16        | 16.67%  |
| 51-100  | 6         | 6.25%   |
| 161-240 | 3         | 3.13%   |
| 1-50    | 1         | 1.04%   |
| Unknown | 1         | 1.04%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 74        | 79.57%  |
| 2     | 10        | 10.75%  |
| 0     | 9         | 9.68%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 65        | 47.45%  |
| Intel                 | 41        | 29.93%  |
| Broadcom              | 7         | 5.11%   |
| Qualcomm Atheros      | 6         | 4.38%   |
| Xiaomi                | 3         | 2.19%   |
| MediaTek              | 3         | 2.19%   |
| TP-Link               | 2         | 1.46%   |
| Samsung Electronics   | 2         | 1.46%   |
| Ralink                | 2         | 1.46%   |
| Ralink Technology     | 1         | 0.73%   |
| Qualcomm              | 1         | 0.73%   |
| OPPO Electronics      | 1         | 0.73%   |
| OKB SAPR              | 1         | 0.73%   |
| Huawei Technologies   | 1         | 0.73%   |
| Broadcom Limited      | 1         | 0.73%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 17.96%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25        | 14.97%  |
| Intel Wireless 7265                                               | 11        | 6.59%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 4.79%   |
| Intel Wi-Fi 6 AX201                                               | 7         | 4.19%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 2.99%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 2.4%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 2.4%    |
| Intel Wireless 3165                                               | 4         | 2.4%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 2.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 1.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 1.8%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 1.8%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 1.8%    |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 3         | 1.8%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.2%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 1.2%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 1.2%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.2%    |
| Intel Ethernet Controller I225-V                                  | 2         | 1.2%    |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 1.2%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 1.2%    |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 2         | 1.2%    |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.2%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 0.6%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.6%    |
| TP-Link 802.11n NIC                                               | 1         | 0.6%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 0.6%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.6%    |
| Realtek RTL8723DE Wireless Network Adapter                        | 1         | 0.6%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.6%    |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.6%    |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.6%    |
| Qualcomm QCNFA765 Wireless Network Adapter                        | 1         | 0.6%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.6%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.6%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.6%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.6%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 40        | 41.24%  |
| Intel                 | 39        | 40.21%  |
| Broadcom              | 6         | 6.19%   |
| Qualcomm Atheros      | 3         | 3.09%   |
| TP-Link               | 2         | 2.06%   |
| Ralink                | 2         | 2.06%   |
| MediaTek              | 2         | 2.06%   |
| Ralink Technology     | 1         | 1.03%   |
| Qualcomm              | 1         | 1.03%   |
| Broadcom Limited      | 1         | 1.03%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25        | 25.25%  |
| Intel Wireless 7265                                            | 11        | 11.11%  |
| Intel Wi-Fi 6 AX201                                            | 7         | 7.07%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 5.05%   |
| Intel Wireless 3165                                            | 4         | 4.04%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 4.04%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 3.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 3.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 3.03%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 3.03%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 2.02%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 2.02%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 2.02%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 2.02%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 2         | 2.02%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 2.02%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 1.01%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.01%   |
| TP-Link 802.11n NIC                                            | 1         | 1.01%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 1.01%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 1.01%   |
| Realtek RTL8723DE Wireless Network Adapter                     | 1         | 1.01%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.01%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.01%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.01%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.01%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.01%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.01%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.01%   |
| Intel Wireless 8265 / 8275                                     | 1         | 1.01%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.01%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.01%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.01%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter     | 1         | 1.01%   |
| Broadcom BCM4312 802.11b/g LP-PHY                              | 1         | 1.01%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 38        | 57.58%  |
| Intel                 | 16        | 24.24%  |
| Xiaomi                | 3         | 4.55%   |
| Qualcomm Atheros      | 3         | 4.55%   |
| Samsung Electronics   | 2         | 3.03%   |
| OPPO Electronics      | 1         | 1.52%   |
| OKB SAPR              | 1         | 1.52%   |
| MediaTek              | 1         | 1.52%   |
| Broadcom              | 1         | 1.52%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 30        | 44.78%  |
| Intel Ethernet Connection (6) I219-V                              | 8         | 11.94%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 4         | 5.97%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 5.97%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 3         | 4.48%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 2.99%   |
| Intel Ethernet Controller I225-V                                  | 2         | 2.99%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 2.99%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.49%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 1.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.49%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 1         | 1.49%   |
| OPPO CPH2411                                                      | 1         | 1.49%   |
| OKB SAPR Ethernet controller                                      | 1         | 1.49%   |
| MediaTek WP15                                                     | 1         | 1.49%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.49%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.49%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.49%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 1.49%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.49%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 92        | 59.74%  |
| Ethernet | 61        | 39.61%  |
| Modem    | 1         | 0.65%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 57        | 61.96%  |
| Ethernet | 35        | 38.04%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 53        | 56.99%  |
| 1     | 37        | 39.78%  |
| 0     | 3         | 3.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 88        | 91.67%  |
| Yes  | 8         | 8.33%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 36        | 44.44%  |
| Realtek Semiconductor           | 28        | 34.57%  |
| Broadcom                        | 6         | 7.41%   |
| Realtek                         | 2         | 2.47%   |
| Ralink                          | 2         | 2.47%   |
| IMC Networks                    | 2         | 2.47%   |
| Foxconn / Hon Hai               | 2         | 2.47%   |
| Qualcomm Atheros Communications | 1         | 1.23%   |
| Lite-On Technology              | 1         | 1.23%   |
| Hewlett-Packard                 | 1         | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 24        | 29.63%  |
| Intel Bluetooth wireless interface             | 17        | 20.99%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 8         | 9.88%   |
| Intel AX201 Bluetooth                          | 8         | 9.88%   |
| Realtek  Bluetooth 4.2 Adapter                 | 4         | 4.94%   |
| Intel Bluetooth Device                         | 3         | 3.7%    |
| Realtek Bluetooth Radio                        | 2         | 2.47%   |
| Ralink RT3290 Bluetooth                        | 2         | 2.47%   |
| IMC Networks Bluetooth Radio                   | 2         | 2.47%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 1.23%   |
| Lite-On Wireless_Device                        | 1         | 1.23%   |
| HP Broadcom 2070 Bluetooth Combo               | 1         | 1.23%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter   | 1         | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device             | 1         | 1.23%   |
| Broadcom HP Portable Valentine                 | 1         | 1.23%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 1.23%   |
| Broadcom BCM20702A0 Bluetooth                  | 1         | 1.23%   |
| Broadcom BCM2070 Bluetooth 2.1 + EDR           | 1         | 1.23%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 1.23%   |
| Broadcom BCM2045 Bluetooth                     | 1         | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                 | Notebooks | Percent |
|------------------------|-----------|---------|
| Intel                  | 71        | 68.93%  |
| AMD                    | 22        | 21.36%  |
| Nvidia                 | 7         | 6.8%    |
| Zhaoxin                | 1         | 0.97%   |
| MosArt Semiconductor   | 1         | 0.97%   |
| Generalplus Technology | 1         | 0.97%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP High Definition Audio Controller                                            | 29        | 23.02%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 18        | 14.29%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 14        | 11.11%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 10        | 7.94%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 3.97%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 3.17%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 2.38%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 2.38%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.38%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.59%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.59%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 2         | 1.59%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.59%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.59%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 2         | 1.59%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 2         | 1.59%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 2         | 1.59%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 2         | 1.59%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 2         | 1.59%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.79%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller                          | 1         | 0.79%   |
| Nvidia High Definition Audio Controller                                                           | 1         | 0.79%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.79%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.79%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.79%   |
| Nvidia Audio device                                                                               | 1         | 0.79%   |
| MosArt Semiconductor MosArt USB Audio Device                                                      | 1         | 0.79%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.79%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.79%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.79%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.79%   |
| Generalplus Technology USB Audio Device                                                           | 1         | 0.79%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.79%   |
| AMD High Definition Audio Controller                                                              | 1         | 0.79%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                                                  | 1         | 0.79%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 40        | 40.4%   |
| SK hynix            | 14        | 14.14%  |
| Foxline             | 10        | 10.1%   |
| Micron Technology   | 9         | 9.09%   |
| Crucial             | 6         | 6.06%   |
| Kingston            | 4         | 4.04%   |
| Ramaxel Technology  | 3         | 3.03%   |
| Unknown (ABCD)      | 2         | 2.02%   |
| Unknown             | 2         | 2.02%   |
| Elpida              | 2         | 2.02%   |
| SHARETRONIC         | 1         | 1.01%   |
| Qumo                | 1         | 1.01%   |
| Patriot             | 1         | 1.01%   |
| King Tiger          | 1         | 1.01%   |
| ChangXin Memory     | 1         | 1.01%   |
| <Invalid>           | 1         | 1.01%   |
| Unknown             | 1         | 1.01%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 16.19%  |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 3.81%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 3         | 2.86%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 2.86%   |
| Foxline RAM FL3200D4S22-8G 8192MB SODIMM DDR4 3200MT/s           | 3         | 2.86%   |
| Foxline RAM FL2666D4S19-8G 8192MB SODIMM DDR4 2667MT/s           | 3         | 2.86%   |
| Foxline RAM FL2400D4S17S-8G 8192MB SODIMM DDR4 2400MT/s          | 3         | 2.86%   |
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 2         | 1.9%    |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 2         | 1.9%    |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 1.9%    |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 1.9%    |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 2         | 1.9%    |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.9%    |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 2         | 1.9%    |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 1.9%    |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.9%    |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.9%    |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 2         | 1.9%    |
| Crucial RAM CT8G4SFS832A.M8FR 8GB SODIMM DDR4 3200MT/s           | 2         | 1.9%    |
| Crucial RAM CT8G4SFS832A.C8FN 8GB SODIMM DDR4 3200MT/s           | 2         | 1.9%    |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.95%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 0.95%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.95%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 0.95%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.95%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.95%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 0.95%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 0.95%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 0.95%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 0.95%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 0.95%   |
| Samsung RAM M471B2873EH1-CH9 1GB SODIMM DDR3 1333MT/s            | 1         | 0.95%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.95%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 0.95%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.95%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 0.95%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 0.95%   |
| Samsung RAM K4E6E3 4EC-EGCG 4GB Row Of Chips LPDDR3 2133MT/s     | 1         | 0.95%   |
| Samsung RAM K4A8G165WB-BCRC 4GB SODIMM DDR4 2400MT/s             | 1         | 0.95%   |
| Ramaxel RAM RMSA3310MJ86H9F-3200 4GB SODIMM DDR4 3200MT/s        | 1         | 0.95%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 72        | 80%     |
| DDR3   | 13        | 14.44%  |
| LPDDR4 | 3         | 3.33%   |
| LPDDR3 | 1         | 1.11%   |
| DDR2   | 1         | 1.11%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 82        | 86.32%  |
| Row Of Chips | 12        | 12.63%  |
| DIMM         | 1         | 1.05%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 54        | 56.25%  |
| 4096  | 25        | 26.04%  |
| 16384 | 8         | 8.33%   |
| 2048  | 6         | 6.25%   |
| 1024  | 3         | 3.13%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 3200  | 34        | 36.17%  |
| 2667  | 31        | 32.98%  |
| 1600  | 9         | 9.57%   |
| 2400  | 8         | 8.51%   |
| 3266  | 2         | 2.13%   |
| 1334  | 2         | 2.13%   |
| 1333  | 2         | 2.13%   |
| 3733  | 1         | 1.06%   |
| 2666  | 1         | 1.06%   |
| 2133  | 1         | 1.06%   |
| 1866  | 1         | 1.06%   |
| 1066  | 1         | 1.06%   |
| 667   | 1         | 1.06%   |

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
| Chicony Electronics                    | 21        | 23.08%  |
| Syntek                                 | 19        | 20.88%  |
| IMC Networks                           | 11        | 12.09%  |
| Acer                                   | 7         | 7.69%   |
| Quanta                                 | 5         | 5.49%   |
| Luxvisions Innotech Limited            | 4         | 4.4%    |
| Sunplus Innovation Technology          | 3         | 3.3%    |
| Realtek Semiconductor                  | 3         | 3.3%    |
| Microdia                               | 3         | 3.3%    |
| Cheng Uei Precision Industry (Foxlink) | 3         | 3.3%    |
| Bison Electronics                      | 3         | 3.3%    |
| USB Camera CS                          | 2         | 2.2%    |
| Suyin                                  | 2         | 2.2%    |
| Sonix Technology                       | 2         | 2.2%    |
| SunplusIT                              | 1         | 1.1%    |
| Alcor Micro                            | 1         | 1.1%    |
| Unknown                                | 1         | 1.1%    |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                         | Notebooks | Percent |
|---------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                      | 18        | 19.78%  |
| Chicony USB camera                                            | 10        | 10.99%  |
| IMC Networks ov9734_azurewave_camera                          | 4         | 4.4%    |
| IMC Networks Integrated Camera                                | 4         | 4.4%    |
| Chicony Integrated Camera                                     | 3         | 3.3%    |
| Acer Integrated Camera                                        | 3         | 3.3%    |
| USB Camera CS USB Camera CS                                   | 2         | 2.2%    |
| Sonix USB 2.0 Camera                                          | 2         | 2.2%    |
| Quanta HP TrueVision HD Camera                                | 2         | 2.2%    |
| Microdia Webcam Vitade AF                                     | 2         | 2.2%    |
| Luxvisions Innotech Limited Integrated Camera                 | 2         | 2.2%    |
| Chicony HD User Facing                                        | 2         | 2.2%    |
| Bison Integrated Camera                                       | 2         | 2.2%    |
| Syntek Lenovo EasyCamera                                      | 1         | 1.1%    |
| Suyin HP Truevision HD                                        | 1         | 1.1%    |
| Suyin Acer CrystalEye Webcam                                  | 1         | 1.1%    |
| SunplusIT MTD camera                                          | 1         | 1.1%    |
| Sunplus FHD Camera Microphone                                 | 1         | 1.1%    |
| Sunplus BKX Usb FHD Camera                                    | 1         | 1.1%    |
| Sunplus Asus Webcam                                           | 1         | 1.1%    |
| Realtek Integrated_Webcam_HD                                  | 1         | 1.1%    |
| Realtek HP Truevision HD                                      | 1         | 1.1%    |
| Realtek 2SF022                                                | 1         | 1.1%    |
| Quanta USB HD Webcam                                          | 1         | 1.1%    |
| Quanta HP Webcam                                              | 1         | 1.1%    |
| Quanta HD Camera                                              | 1         | 1.1%    |
| Microdia REDRAGON Live Camera Audio                           | 1         | 1.1%    |
| Luxvisions Innotech Limited HP TrueVision HD Camera           | 1         | 1.1%    |
| Luxvisions Innotech Limited HP HD Camera                      | 1         | 1.1%    |
| IMC Networks USB2.0 VGA UVC WebCam                            | 1         | 1.1%    |
| IMC Networks USB2.0 HD UVC WebCam                             | 1         | 1.1%    |
| IMC Networks HD Camera                                        | 1         | 1.1%    |
| Chicony USB2.0 Camera                                         | 1         | 1.1%    |
| Chicony Lenovo Integrated Camera (0.3MP)                      | 1         | 1.1%    |
| Chicony Integrated Camera (1280x720@30)                       | 1         | 1.1%    |
| Chicony HP Webcam-50                                          | 1         | 1.1%    |
| Chicony HP Webcam [2 MP Macro]                                | 1         | 1.1%    |
| Chicony HP TrueVision HD Camera                               | 1         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) Webcam                 | 1         | 1.1%    |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam | 1         | 1.1%    |

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
| 0     | 65        | 68.42%  |
| 1     | 23        | 24.21%  |
| 2     | 7         | 7.37%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Net/wireless          | 10        | 28.57%  |
| Graphics card         | 10        | 28.57%  |
| Fingerprint reader    | 10        | 28.57%  |
| Bluetooth             | 2         | 5.71%   |
| Sound                 | 1         | 2.86%   |
| Net/ethernet          | 1         | 2.86%   |
| Multimedia controller | 1         | 2.86%   |

