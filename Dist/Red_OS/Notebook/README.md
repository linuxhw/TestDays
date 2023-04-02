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

Total: 131

| Vendor        | Model                       | Probe                                                      | Date         |
|---------------|-----------------------------|------------------------------------------------------------|--------------|
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
| Red OS 7.3.1 | 44        | 51.16%  |
| Red OS 7.3.2 | 23        | 26.74%  |
| Red OS 7.3   | 19        | 22.09%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| Red OS | 81        | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Notebooks | Percent |
|------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64   | 25        | 27.47%  |
| 5.15.72-1.el7.3.x86_64 | 15        | 16.48%  |
| 5.15.35-4.el7.3.x86_64 | 10        | 10.99%  |
| 5.10.29-1.el7.x86_64   | 9         | 9.89%   |
| 5.15.35-1.el7.3.x86_64 | 6         | 6.59%   |
| 5.15.87-1.el7.3.x86_64 | 5         | 5.49%   |
| 5.15.35-5.el7.3.x86_64 | 4         | 4.4%    |
| 5.15.78-2.el7.3.x86_64 | 3         | 3.3%    |
| 5.10.1-1.el7.x86_64    | 3         | 3.3%    |
| 5.15.10-4.el7.x86_64   | 2         | 2.2%    |
| 5.10.29-3.el7.x86_64   | 2         | 2.2%    |
| 5.10.24-2.el7.x86_64   | 2         | 2.2%    |
| 5.18.1-1.el7.x86_64    | 1         | 1.1%    |
| 5.15.10-3.el7.x86_64   | 1         | 1.1%    |
| 5.15.10-2.el7.x86_64   | 1         | 1.1%    |
| 5.13.15-1.el7.x86_64   | 1         | 1.1%    |
| 5.10.24-1.el7.x86_64   | 1         | 1.1%    |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15.10 | 29        | 32.22%  |
| 5.15.35 | 19        | 21.11%  |
| 5.15.72 | 15        | 16.67%  |
| 5.10.29 | 11        | 12.22%  |
| 5.15.87 | 5         | 5.56%   |
| 5.15.78 | 3         | 3.33%   |
| 5.10.24 | 3         | 3.33%   |
| 5.10.1  | 3         | 3.33%   |
| 5.18.1  | 1         | 1.11%   |
| 5.13.15 | 1         | 1.11%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Notebooks | Percent |
|---------|-----------|---------|
| 5.15    | 66        | 78.57%  |
| 5.10    | 16        | 19.05%  |
| 5.18    | 1         | 1.19%   |
| 5.13    | 1         | 1.19%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Notebooks | Percent |
|--------|-----------|---------|
| x86_64 | 81        | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Notebooks | Percent |
|------------|-----------|---------|
| MATE       | 70        | 85.37%  |
| Cinnamon   | 11        | 13.41%  |
| X-Cinnamon | 1         | 1.22%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| X11     | 77        | 92.77%  |
| Wayland | 6         | 7.23%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Notebooks | Percent |
|---------|-----------|---------|
| GDM     | 78        | 93.98%  |
| SDDM    | 3         | 3.61%   |
| Unknown | 2         | 2.41%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Notebooks | Percent |
|---------|-----------|---------|
| Unknown | 70        | 83.33%  |
| ru_RU   | 13        | 15.48%  |
| en_US   | 1         | 1.19%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Notebooks | Percent |
|------|-----------|---------|
| EFI  | 72        | 86.75%  |
| BIOS | 11        | 13.25%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| Ext4    | 80        | 97.56%  |
| Overlay | 1         | 1.22%   |
| Btrfs   | 1         | 1.22%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Notebooks | Percent |
|---------|-----------|---------|
| GPT     | 72        | 87.8%   |
| MBR     | 8         | 9.76%   |
| Unknown | 2         | 2.44%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 72        | 87.8%   |
| Yes       | 10        | 12.2%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 60        | 71.43%  |
| Yes       | 24        | 28.57%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                           | Notebooks | Percent |
|--------------------------------|-----------|---------|
| Lenovo                         | 35        | 43.21%  |
| Hewlett-Packard                | 9         | 11.11%  |
| ICL                            | 5         | 6.17%   |
| HUAWEI                         | 4         | 4.94%   |
| MSI                            | 3         | 3.7%    |
| Kraftway                       | 3         | 3.7%    |
| Digma                          | 3         | 3.7%    |
| ASUSTek Computer               | 3         | 3.7%    |
| Aquarius                       | 3         | 3.7%    |
| Acer                           | 3         | 3.7%    |
| IP3 Technology                 | 2         | 2.47%   |
| 3Logic Group                   | 2         | 2.47%   |
| THUNDEROBOT                    | 1         | 1.23%   |
| Shanghai Zhaoxin Semiconductor | 1         | 1.23%   |
| Pegatron                       | 1         | 1.23%   |
| mtech                          | 1         | 1.23%   |
| HONOR                          | 1         | 1.23%   |
| Gigabyte Technology            | 1         | 1.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                 | Notebooks | Percent |
|--------------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE                  | 17        | 20.99%  |
| Kraftway ACCORD                      | 3         | 3.7%    |
| ICL RAYbook Si1512                   | 3         | 3.7%    |
| HP Laptop 15s-eq1xxx                 | 3         | 3.7%    |
| Lenovo ThinkBook 15 G3 ACL 21A4      | 2         | 2.47%   |
| IP3 ACN30                            | 2         | 2.47%   |
| THUNDEROBOT 911AirD                  | 1         | 1.23%   |
| Shanghai Zhaoxin ZXE CRB             | 1         | 1.23%   |
| Pegatron A35                         | 1         | 1.23%   |
| mtech MTL1578                        | 1         | 1.23%   |
| MSI Sword 15 A12UE                   | 1         | 1.23%   |
| MSI Modern 15 B12M                   | 1         | 1.23%   |
| MSI FX610                            | 1         | 1.23%   |
| Lenovo V130-15IKB 81HN               | 1         | 1.23%   |
| Lenovo ThinkPad X220 4290RB3         | 1         | 1.23%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2DE00 | 1         | 1.23%   |
| Lenovo ThinkPad T14 Gen 3 21AJS2DD00 | 1         | 1.23%   |
| Lenovo ThinkPad E15 Gen 4 21E6009UGP | 1         | 1.23%   |
| Lenovo ThinkBook 15 G2 ARE 20VG      | 1         | 1.23%   |
| Lenovo ThinkBook 14-IIL 20SL         | 1         | 1.23%   |
| Lenovo IdeaPad L340-15IWL 81LG       | 1         | 1.23%   |
| Lenovo IdeaPad L340-15API 81LW       | 1         | 1.23%   |
| Lenovo IdeaPad 700-15ISK 80RU        | 1         | 1.23%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7     | 1         | 1.23%   |
| Lenovo IdeaPad 5 15ARE05 81YQ        | 1         | 1.23%   |
| Lenovo IdeaPad 330-15ARR 81D2        | 1         | 1.23%   |
| Lenovo IdeaPad 3 15ITL05 81X8        | 1         | 1.23%   |
| Lenovo IdeaPad 1 15ALC7 82R4         | 1         | 1.23%   |
| Lenovo B590 20208                    | 1         | 1.23%   |
| ICL RAYbook Si1514                   | 1         | 1.23%   |
| HUAWEI NBLK-WAX9X                    | 1         | 1.23%   |
| HUAWEI NBD-WXX9                      | 1         | 1.23%   |
| HUAWEI BOHL-WXX9                     | 1         | 1.23%   |
| HUAWEI BOD-WXX9                      | 1         | 1.23%   |
| HONOR NBR-WAX9                       | 1         | 1.23%   |
| HP Pavilion g6                       | 1         | 1.23%   |
| HP Pavilion 15                       | 1         | 1.23%   |
| HP OMEN by Laptop                    | 1         | 1.23%   |
| HP Notebook                          | 1         | 1.23%   |
| HP Laptop 15-dw3xxx                  | 1         | 1.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Notebooks | Percent |
|-----------------------|-----------|---------|
| Lenovo V15-IWL        | 17        | 20.99%  |
| Lenovo IdeaPad        | 8         | 9.88%   |
| Lenovo ThinkPad       | 4         | 4.94%   |
| Lenovo ThinkBook      | 4         | 4.94%   |
| ICL RAYbook           | 4         | 4.94%   |
| HP Laptop             | 4         | 4.94%   |
| Kraftway ACCORD       | 3         | 3.7%    |
| Digma EVE             | 3         | 3.7%    |
| IP3 ACN30             | 2         | 2.47%   |
| HP Pavilion           | 2         | 2.47%   |
| Aquarius NS685U       | 2         | 2.47%   |
| Acer Aspire           | 2         | 2.47%   |
| THUNDEROBOT 911AirD   | 1         | 1.23%   |
| Shanghai Zhaoxin ZXE  | 1         | 1.23%   |
| Pegatron A35          | 1         | 1.23%   |
| mtech MTL1578         | 1         | 1.23%   |
| MSI Sword             | 1         | 1.23%   |
| MSI Modern            | 1         | 1.23%   |
| MSI FX610             | 1         | 1.23%   |
| Lenovo V130-15IKB     | 1         | 1.23%   |
| Lenovo B590           | 1         | 1.23%   |
| HUAWEI NBLK-WAX9X     | 1         | 1.23%   |
| HUAWEI NBD-WXX9       | 1         | 1.23%   |
| HUAWEI BOHL-WXX9      | 1         | 1.23%   |
| HUAWEI BOD-WXX9       | 1         | 1.23%   |
| HONOR NBR-WAX9        | 1         | 1.23%   |
| HP OMEN               | 1         | 1.23%   |
| HP Notebook           | 1         | 1.23%   |
| HP G62                | 1         | 1.23%   |
| Gigabyte G5           | 1         | 1.23%   |
| ASUS X75VD            | 1         | 1.23%   |
| ASUS X540NV           | 1         | 1.23%   |
| ASUS TUF              | 1         | 1.23%   |
| Aquarius NS585        | 1         | 1.23%   |
| Acer TravelMate       | 1         | 1.23%   |
| 3Logic Group Graviton | 1         | 1.23%   |
| 3Logic Group APM      | 1         | 1.23%   |
| Unknown               | 1         | 1.23%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Notebooks | Percent |
|------|-----------|---------|
| 2019 | 26        | 32.1%   |
| 2021 | 21        | 25.93%  |
| 2020 | 11        | 13.58%  |
| 2022 | 9         | 11.11%  |
| 2012 | 3         | 3.7%    |
| 2018 | 2         | 2.47%   |
| 2017 | 2         | 2.47%   |
| 2011 | 2         | 2.47%   |
| 2010 | 2         | 2.47%   |
| 2015 | 1         | 1.23%   |
| 2013 | 1         | 1.23%   |
| 2007 | 1         | 1.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name     | Notebooks | Percent |
|----------|-----------|---------|
| Notebook | 81        | 100%    |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Notebooks | Percent |
|----------|-----------|---------|
| Disabled | 81        | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 81        | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 55        | 67.9%   |
| 3.01-4.0   | 10        | 12.35%  |
| 16.01-24.0 | 7         | 8.64%   |
| 8.01-16.0  | 7         | 8.64%   |
| 2.01-3.0   | 2         | 2.47%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1.01-2.0 | 51        | 60%     |
| 2.01-3.0 | 18        | 21.18%  |
| 0.51-1.0 | 8         | 9.41%   |
| 3.01-4.0 | 6         | 7.06%   |
| 4.01-8.0 | 2         | 2.35%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 72        | 86.75%  |
| 2      | 7         | 8.43%   |
| 3      | 4         | 4.82%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| No        | 69        | 84.15%  |
| Yes       | 13        | 15.85%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 52        | 64.2%   |
| No        | 29        | 35.8%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 98.77%  |
| No        | 1         | 1.23%   |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Notebooks | Percent |
|-----------|-----------|---------|
| Yes       | 70        | 86.42%  |
| No        | 11        | 13.58%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Notebooks | Percent |
|---------|-----------|---------|
| Russia  | 80        | 98.77%  |
| Ukraine | 1         | 1.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Notebooks | Percent |
|------------------|-----------|---------|
| Salekhard        | 21        | 24.71%  |
| Moscow           | 16        | 18.82%  |
| Murom            | 14        | 16.47%  |
| Ryazan           | 3         | 3.53%   |
| Yekaterinburg    | 2         | 2.35%   |
| Vladimir         | 2         | 2.35%   |
| Perm             | 2         | 2.35%   |
| Novy Urengoy     | 2         | 2.35%   |
| Kursk            | 2         | 2.35%   |
| Krasnodar        | 2         | 2.35%   |
| Yaroslavl        | 1         | 1.18%   |
| Yakutsk          | 1         | 1.18%   |
| Ulyanovsk        | 1         | 1.18%   |
| Tver             | 1         | 1.18%   |
| Strezhevoy       | 1         | 1.18%   |
| St Petersburg    | 1         | 1.18%   |
| Sevastopol       | 1         | 1.18%   |
| Saratov          | 1         | 1.18%   |
| Omsk             | 1         | 1.18%   |
| Novosibirsk      | 1         | 1.18%   |
| Nizhniy Novgorod | 1         | 1.18%   |
| Muromskiy        | 1         | 1.18%   |
| Krasnoyarsk      | 1         | 1.18%   |
| Konstantinovo    | 1         | 1.18%   |
| Kol'chugino      | 1         | 1.18%   |
| Khabarovsk       | 1         | 1.18%   |
| Kaluga           | 1         | 1.18%   |
| Belgorod         | 1         | 1.18%   |
| Balashikha       | 1         | 1.18%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 32     | 25.81%  |
| WDC                 | 11        | 13     | 11.83%  |
| SK hynix            | 7         | 9      | 7.53%   |
| Toshiba             | 5         | 14     | 5.38%   |
| Seagate             | 5         | 5      | 5.38%   |
| Foxline             | 5         | 5      | 5.38%   |
| A-DATA Technology   | 5         | 5      | 5.38%   |
| HGST                | 4         | 4      | 4.3%    |
| Phison              | 3         | 3      | 3.23%   |
| Unknown             | 2         | 2      | 2.15%   |
| UMIS                | 2         | 2      | 2.15%   |
| Silicon Motion      | 2         | 2      | 2.15%   |
| Micron Technology   | 2         | 5      | 2.15%   |
| Kingston            | 2         | 2      | 2.15%   |
| Gigabyte Technology | 2         | 2      | 2.15%   |
| Transcend           | 1         | 1      | 1.08%   |
| SPCC Sol            | 1         | 1      | 1.08%   |
| SanDisk             | 1         | 1      | 1.08%   |
| KingSpec            | 1         | 1      | 1.08%   |
| Kimtigo             | 1         | 2      | 1.08%   |
| JMicron Technology  | 1         | 1      | 1.08%   |
| ITHOO               | 1         | 1      | 1.08%   |
| Intel               | 1         | 1      | 1.08%   |
| Crucial             | 1         | 1      | 1.08%   |
| China               | 1         | 1      | 1.08%   |
| Apacer              | 1         | 2      | 1.08%   |
| Unknown             | 1         | 1      | 1.08%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                     | Notebooks | Percent |
|-------------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB          | 18        | 18.95%  |
| Foxline FLSSD256M80E13TCX5 256GB          | 5         | 5.26%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB      | 2         | 2.11%   |
| Toshiba MQ01ABF050 500GB                  | 2         | 2.11%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB    | 2         | 2.11%   |
| SK hynix PC711 HFS512GDE9X073N 512GB      | 2         | 2.11%   |
| Silicon Motion Wodposit NVMe SSD 256GB    | 2         | 2.11%   |
| Gigabyte GP-GSM2NE3256GNTD 256GB          | 2         | 2.11%   |
| A-DATA SU650 240GB SSD                    | 2         | 2.11%   |
| WDC WDS500G2B0B-00YS70 500GB SSD          | 1         | 1.05%   |
| WDC WDS250G2B0A-00SM50 250GB SSD          | 1         | 1.05%   |
| WDC WD5000BPVT-55HXZT3 500GB              | 1         | 1.05%   |
| WDC WD10SPZX-24Z10 1TB                    | 1         | 1.05%   |
| WDC WD10SPZX-00Z10T0 1TB                  | 1         | 1.05%   |
| WDC PC SN530 SDBPNPZ-512G-1027 512GB      | 1         | 1.05%   |
| WDC PC SN530 SDBPNPZ-256G-1006 256GB      | 1         | 1.05%   |
| WDC PC SN530 SDBPMPZ-512G-1101 512GB      | 1         | 1.05%   |
| WDC PC SN520 SDAPMUW-512G-1101 512GB      | 1         | 1.05%   |
| Unknown SLD128  128GB                     | 1         | 1.05%   |
| Unknown 58K722  128GB                     | 1         | 1.05%   |
| UMIS RPJTJ512MEE1OWX 512GB                | 1         | 1.05%   |
| UMIS RPJTJ256MGE1QDQ 256GB                | 1         | 1.05%   |
| Transcend TS240GMTS820S 240GB SSD         | 1         | 1.05%   |
| Toshiba MK5075GSX 500GB                   | 1         | 1.05%   |
| Toshiba MK5059GSXP 500GB                  | 1         | 1.05%   |
| Toshiba KXG60ZNV512G 512GB                | 1         | 1.05%   |
| Toshiba KXG60ZNV256G 256GB                | 1         | 1.05%   |
| SPCC Sol id State Disk 1TB SSD            | 1         | 1.05%   |
| SK hynix SKHynix_HFS512GDE9X081N 512GB    | 1         | 1.05%   |
| SK hynix SKHynix_HFS256GDE9X081N 256GB    | 1         | 1.05%   |
| SK hynix SKHynix_HFM256GDHTNI-87A0B 256GB | 1         | 1.05%   |
| SK hynix BC511 512GB                      | 1         | 1.05%   |
| Seagate ST750LM022 HN-M750MBB 752GB       | 1         | 1.05%   |
| Seagate ST500LT012-1DG142 500GB           | 1         | 1.05%   |
| Seagate ST320LM0 01 HN-M320MBB 320GB      | 1         | 1.05%   |
| Seagate ST1000LM035-1RK172 1TB            | 1         | 1.05%   |
| Seagate ST1000LM024 HN-M101MBB 1TB        | 1         | 1.05%   |
| SanDisk SD8SBAT256G1122 256GB SSD         | 1         | 1.05%   |
| Samsung SSD 860 EVO M.2 250GB             | 1         | 1.05%   |
| Samsung MZVLQ256HAJD-000H1 256GB          | 1         | 1.05%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor  | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 5         | 5      | 33.33%  |
| HGST    | 4         | 4      | 26.67%  |
| WDC     | 3         | 5      | 20%     |
| Toshiba | 3         | 11     | 20%     |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Notebooks | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 4         | 4      | 25%     |
| WDC                 | 2         | 2      | 12.5%   |
| Transcend           | 1         | 1      | 6.25%   |
| SPCC Sol            | 1         | 1      | 6.25%   |
| SanDisk             | 1         | 1      | 6.25%   |
| Samsung Electronics | 1         | 1      | 6.25%   |
| Kingston            | 1         | 1      | 6.25%   |
| KingSpec            | 1         | 1      | 6.25%   |
| JMicron Technology  | 1         | 1      | 6.25%   |
| Crucial             | 1         | 1      | 6.25%   |
| China               | 1         | 1      | 6.25%   |
| Apacer              | 1         | 2      | 6.25%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Notebooks | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 57        | 73     | 62.64%  |
| SSD     | 16        | 17     | 17.58%  |
| HDD     | 14        | 25     | 15.38%  |
| MMC     | 3         | 3      | 3.3%    |
| Unknown | 1         | 1      | 1.1%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| NVMe | 57        | 73     | 63.33%  |
| SATA | 27        | 39     | 30%     |
| SAS  | 3         | 4      | 3.33%   |
| MMC  | 3         | 3      | 3.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Notebooks | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 22        | 32     | 73.33%  |
| 0.51-1.0   | 8         | 10     | 26.67%  |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| 101-250    | 47        | 55.95%  |
| 251-500    | 16        | 19.05%  |
| 51-100     | 8         | 9.52%   |
| 501-1000   | 5         | 5.95%   |
| 1001-2000  | 4         | 4.76%   |
| 1-20       | 3         | 3.57%   |
| 21-50      | 1         | 1.19%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB  | Notebooks | Percent |
|----------|-----------|---------|
| 1-20     | 64        | 75.29%  |
| 21-50    | 11        | 12.94%  |
| 101-250  | 4         | 4.71%   |
| 251-500  | 2         | 2.35%   |
| 501-1000 | 2         | 2.35%   |
| 51-100   | 2         | 2.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Notebooks | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 11.11%  |
| Toshiba MQ01ABF050 500GB            | 1         | 7      | 11.11%  |
| Toshiba MK5075GSX 500GB             | 1         | 1      | 11.11%  |
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
| Toshiba           | 2         | 9      | 25%     |
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
| Toshiba | 2         | 9      | 33.33%  |
| Seagate | 2         | 2      | 33.33%  |
| WDC     | 1         | 1      | 16.67%  |
| HGST    | 1         | 1      | 16.67%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Notebooks | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 6         | 13     | 75%     |
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
| Works    | 73        | 94     | 83.91%  |
| Malfunc  | 8         | 15     | 9.2%    |
| Detected | 6         | 10     | 6.9%    |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Notebooks | Percent |
|------------------------------|-----------|---------|
| Intel                        | 58        | 46.4%   |
| Samsung Electronics          | 23        | 18.4%   |
| Phison Electronics           | 10        | 8%      |
| AMD                          | 9         | 7.2%    |
| SK hynix                     | 7         | 5.6%    |
| SanDisk                      | 6         | 4.8%    |
| Union Memory (Shenzhen)      | 2         | 1.6%    |
| Toshiba America Info Systems | 2         | 1.6%    |
| Silicon Motion               | 2         | 1.6%    |
| Micron Technology            | 2         | 1.6%    |
| Zhaoxin                      | 1         | 0.8%    |
| ShenZhen TIGO Semiconductor  | 1         | 0.8%    |
| Realtek Semiconductor        | 1         | 0.8%    |
| Kingston Technology Company  | 1         | 0.8%    |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                            | Notebooks | Percent |
|----------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                                | 29        | 22.31%  |
| Samsung NVMe SSD Controller 980                                                  | 23        | 17.69%  |
| Phison PS5013 E13 NVMe Controller                                                | 9         | 6.92%   |
| AMD FCH SATA Controller [AHCI mode]                                              | 8         | 6.15%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                   | 6         | 4.62%   |
| Intel Tiger Lake-LP SATA Controller                                              | 5         | 3.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                   | 4         | 3.08%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                 | 4         | 3.08%   |
| Intel Volume Management Device NVMe RAID Controller                              | 3         | 2.31%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller         | 3         | 2.31%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                           | 2         | 1.54%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                             | 2         | 1.54%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                  | 2         | 1.54%   |
| Micron NVMe Storage Controller                                                   | 2         | 1.54%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                            | 2         | 1.54%   |
| Intel Comet Lake SATA AHCI Controller                                            | 2         | 1.54%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                     | 2         | 1.54%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                             | 2         | 1.54%   |
| Zhaoxin ZX-100/ZX-200/KX-6000/KX-6000G StorX AHCI Controller                     | 1         | 0.77%   |
| SK hynix BC511                                                                   | 1         | 0.77%   |
| ShenZhen TIGO Non-Volatile memory controller                                     | 1         | 0.77%   |
| SanDisk PC SN520 NVMe SSD                                                        | 1         | 0.77%   |
| SanDisk NVMe Controller                                                          | 1         | 0.77%   |
| Realtek NVMe Controller                                                          | 1         | 0.77%   |
| Phison E16 PCIe4 NVMe Controller                                                 | 1         | 0.77%   |
| Kingston Company NVMe Controller                                                 | 1         | 0.77%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                               | 1         | 0.77%   |
| Intel SSD 660P Series                                                            | 1         | 0.77%   |
| Intel Ice Lake-LP SATA Controller [AHCI mode]                                    | 1         | 0.77%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                       | 1         | 0.77%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller | 1         | 0.77%   |
| Intel Alder Lake-P SATA AHCI Controller                                          | 1         | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                    | 1         | 0.77%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                 | 1         | 0.77%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller     | 1         | 0.77%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                   | 1         | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                | 1         | 0.77%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                             | 1         | 0.77%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Notebooks | Percent |
|------|-----------|---------|
| SATA | 67        | 51.94%  |
| NVMe | 57        | 44.19%  |
| RAID | 3         | 2.33%   |
| IDE  | 2         | 1.55%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor       | Notebooks | Percent |
|--------------|-----------|---------|
| Intel        | 63        | 77.78%  |
| AMD          | 17        | 20.99%  |
| CentaurHauls | 1         | 1.23%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz              | 18        | 22.22%  |
| Intel Core i5-8279U CPU @ 2.40GHz              | 6         | 7.41%   |
| Intel Core i5-8259U CPU @ 2.30GHz              | 5         | 6.17%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz        | 3         | 3.7%    |
| AMD Ryzen 5 4500U with Radeon Graphics         | 3         | 3.7%    |
| AMD Ryzen 3 5300U with Radeon Graphics         | 3         | 3.7%    |
| AMD Ryzen 3 4300U with Radeon Graphics         | 3         | 3.7%    |
| Intel Celeron CPU N3350 @ 1.10GHz              | 2         | 2.47%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz        | 2         | 2.47%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx  | 2         | 2.47%   |
| AMD Ryzen 3 5400U with Radeon Graphics         | 2         | 2.47%   |
| Intel Pentium CPU N4200 @ 1.10GHz              | 1         | 1.23%   |
| Intel Pentium CPU J3710 @ 1.60GHz              | 1         | 1.23%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz             | 1         | 1.23%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz             | 1         | 1.23%   |
| Intel Core i5-4200U CPU @ 1.60GHz              | 1         | 1.23%   |
| Intel Core i5-3210M CPU @ 2.50GHz              | 1         | 1.23%   |
| Intel Core i5-2450M CPU @ 2.50GHz              | 1         | 1.23%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz             | 1         | 1.23%   |
| Intel Core i5-10210U CPU @ 1.60GHz             | 1         | 1.23%   |
| Intel Core i3-9300 CPU @ 3.70GHz               | 1         | 1.23%   |
| Intel Core i3-7020U CPU @ 2.30GHz              | 1         | 1.23%   |
| Intel Core i3-4005U CPU @ 1.70GHz              | 1         | 1.23%   |
| Intel Core i3-3110M CPU @ 2.40GHz              | 1         | 1.23%   |
| Intel Core i3-2350M CPU @ 2.30GHz              | 1         | 1.23%   |
| Intel Core i3-2310M CPU @ 2.10GHz              | 1         | 1.23%   |
| Intel Core i3-10110U CPU @ 2.10GHz             | 1         | 1.23%   |
| Intel Core i3 CPU M 330 @ 2.13GHz              | 1         | 1.23%   |
| Intel Core 2 Duo CPU T7300 @ 2.00GHz           | 1         | 1.23%   |
| Intel 12th Gen Core i7-1270P                   | 1         | 1.23%   |
| Intel 12th Gen Core i7-12700H                  | 1         | 1.23%   |
| Intel 12th Gen Core i5-1250P                   | 1         | 1.23%   |
| Intel 12th Gen Core i5-1235U                   | 1         | 1.23%   |
| Intel 12th Gen Core i3-1215U                   | 1         | 1.23%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz        | 1         | 1.23%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz        | 1         | 1.23%   |
| Intel 11th Gen Core i5-11260H @ 2.60GHz        | 1         | 1.23%   |
| Intel 11th Gen Core i3-1125G4 @ 2.00GHz        | 1         | 1.23%   |
| CentaurHauls ZHAOXIN KaiXian KX-6640MA@2.2+GHz | 1         | 1.23%   |
| AMD Ryzen 7 3750H with Radeon Vega Mobile Gfx  | 1         | 1.23%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model            | Notebooks | Percent |
|------------------|-----------|---------|
| Intel Core i5    | 35        | 43.21%  |
| Other            | 15        | 18.52%  |
| Intel Core i3    | 8         | 9.88%   |
| AMD Ryzen 3      | 8         | 9.88%   |
| AMD Ryzen 5      | 7         | 8.64%   |
| Intel Pentium    | 2         | 2.47%   |
| Intel Celeron    | 2         | 2.47%   |
| Intel Core i7    | 1         | 1.23%   |
| Intel Core 2 Duo | 1         | 1.23%   |
| AMD Ryzen 7      | 1         | 1.23%   |
| AMD Phenom II    | 1         | 1.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 4      | 54        | 66.67%  |
| 2      | 15        | 18.52%  |
| 6      | 7         | 8.64%   |
| 12     | 2         | 2.47%   |
| 14     | 1         | 1.23%   |
| 10     | 1         | 1.23%   |
| 3      | 1         | 1.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 1      | 81        | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Notebooks | Percent |
|--------|-----------|---------|
| 2      | 66        | 81.48%  |
| 1      | 15        | 18.52%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Notebooks | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 81        | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Notebooks | Percent |
|------------|-----------|---------|
| 0x806ec    | 20        | 24.39%  |
| 0x806ea    | 11        | 13.41%  |
| 0x806c1    | 7         | 8.54%   |
| 0x08600106 | 5         | 6.1%    |
| 0x906a3    | 3         | 3.66%   |
| 0x206a7    | 3         | 3.66%   |
| 0x0a50000c | 3         | 3.66%   |
| 0x08608103 | 3         | 3.66%   |
| 0x906a4    | 2         | 2.44%   |
| 0x806d1    | 2         | 2.44%   |
| 0x506ca    | 2         | 2.44%   |
| 0x40651    | 2         | 2.44%   |
| 0x306a9    | 2         | 2.44%   |
| 0x08108102 | 2         | 2.44%   |
| Unknown    | 2         | 2.44%   |
| 0x906eb    | 1         | 1.22%   |
| 0x906e9    | 1         | 1.22%   |
| 0x706e5    | 1         | 1.22%   |
| 0x6fa      | 1         | 1.22%   |
| 0x506e3    | 1         | 1.22%   |
| 0x506c9    | 1         | 1.22%   |
| 0x406c4    | 1         | 1.22%   |
| 0x20652    | 1         | 1.22%   |
| 0x0a50000d | 1         | 1.22%   |
| 0x08600104 | 1         | 1.22%   |
| 0x08108109 | 1         | 1.22%   |
| 0x0810100b | 1         | 1.22%   |
| 0x010000c8 | 1         | 1.22%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Notebooks | Percent |
|------------------|-----------|---------|
| KabyLake         | 34        | 41.98%  |
| TigerLake        | 7         | 8.64%   |
| Zen 2            | 6         | 7.41%   |
| Alderlake Hybrid | 5         | 6.17%   |
| Unknown          | 4         | 4.94%   |
| Zen+             | 3         | 3.7%    |
| Zen 3            | 3         | 3.7%    |
| SandyBridge      | 3         | 3.7%    |
| Icelake          | 3         | 3.7%    |
| Goldmont         | 3         | 3.7%    |
| IvyBridge        | 2         | 2.47%   |
| Haswell          | 2         | 2.47%   |
| Zen              | 1         | 1.23%   |
| Westmere         | 1         | 1.23%   |
| Skylake          | 1         | 1.23%   |
| Silvermont       | 1         | 1.23%   |
| K10              | 1         | 1.23%   |
| Core             | 1         | 1.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor  | Notebooks | Percent |
|---------|-----------|---------|
| Intel   | 63        | 64.95%  |
| AMD     | 20        | 20.62%  |
| Nvidia  | 13        | 13.4%   |
| Zhaoxin | 1         | 1.03%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Notebooks | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 18        | 18%     |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                                         | 11        | 11%     |
| AMD Renoir                                                                               | 6         | 6%      |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 4         | 4%      |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                                | 3         | 3%      |
| Intel Alder Lake-P Integrated Graphics Controller                                        | 3         | 3%      |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 3         | 3%      |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 3         | 3%      |
| AMD Lucienne                                                                             | 3         | 3%      |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 3         | 3%      |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 2         | 2%      |
| Intel TigerLake-H GT1 [UHD Graphics]                                                     | 2         | 2%      |
| Intel HD Graphics 500                                                                    | 2         | 2%      |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 2         | 2%      |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 2         | 2%      |
| Intel 3rd Gen Core processor Graphics Controller                                         | 2         | 2%      |
| AMD Park [Mobility Radeon HD 5430/5450/5470]                                             | 2         | 2%      |
| Zhaoxin ZX-E C-960 GPU                                                                   | 1         | 1%      |
| Nvidia TU117M [GeForce MX550]                                                            | 1         | 1%      |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 1         | 1%      |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 1%      |
| Nvidia GM108M [GeForce 920MX]                                                            | 1         | 1%      |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 1%      |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 1%      |
| Nvidia GF119M [GeForce 610M]                                                             | 1         | 1%      |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 1         | 1%      |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                                        | 1         | 1%      |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                                  | 1         | 1%      |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                                          | 1         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 1         | 1%      |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 1         | 1%      |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 1         | 1%      |
| Intel HD Graphics 630                                                                    | 1         | 1%      |
| Intel HD Graphics 620                                                                    | 1         | 1%      |
| Intel HD Graphics 530                                                                    | 1         | 1%      |
| Intel Core Processor Integrated Graphics Controller                                      | 1         | 1%      |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                                | 1         | 1%      |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 1         | 1%      |
| Intel Apollo Lake [HD Graphics 505]                                                      | 1         | 1%      |
| Intel Alder Lake-UP3 GT2 [Iris Xe Graphics]                                              | 1         | 1%      |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Notebooks | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 48        | 59.26%  |
| 1 x AMD        | 14        | 17.28%  |
| Intel + Nvidia | 12        | 14.81%  |
| Intel + AMD    | 3         | 3.7%    |
| 2 x AMD        | 2         | 2.47%   |
| 1 x Zhaoxin    | 1         | 1.23%   |
| AMD + Nvidia   | 1         | 1.23%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Notebooks | Percent |
|-------------|-----------|---------|
| Free        | 74        | 89.16%  |
| Unknown     | 7         | 8.43%   |
| Proprietary | 2         | 2.41%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Notebooks | Percent |
|------------|-----------|---------|
| Unknown    | 52        | 61.9%   |
| 1.01-2.0   | 13        | 15.48%  |
| 0.01-0.5   | 7         | 8.33%   |
| 3.01-4.0   | 6         | 7.14%   |
| 0.51-1.0   | 6         | 7.14%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| BOE                  | 40        | 45.98%  |
| LG Display           | 11        | 12.64%  |
| Chimei Innolux       | 9         | 10.34%  |
| Samsung Electronics  | 8         | 9.2%    |
| AU Optronics         | 5         | 5.75%   |
| PANDA                | 3         | 3.45%   |
| Philips              | 2         | 2.3%    |
| NLE                  | 2         | 2.3%    |
| ViewSonic            | 1         | 1.15%   |
| Toshiba              | 1         | 1.15%   |
| RGT                  | 1         | 1.15%   |
| Iiyama               | 1         | 1.15%   |
| HUAWEI               | 1         | 1.15%   |
| Ancor Communications | 1         | 1.15%   |
| Acer                 | 1         | 1.15%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Notebooks | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 17        | 19.54%  |
| BOE LCD Monitor BOE09C5 1920x1080 345x195mm 15.6-inch                   | 9         | 10.34%  |
| LG Display LCD Monitor LGD062E 1920x1080 344x194mm 15.5-inch            | 3         | 3.45%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch        | 3         | 3.45%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                   | 3         | 3.45%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 3         | 3.45%   |
| NLE Newline NLE0032 3840x2160 944x398mm 40.3-inch                       | 2         | 2.3%    |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 2.3%    |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch        | 2         | 2.3%    |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch          | 2         | 2.3%    |
| ViewSonic PJ VSC9B34 1920x1080                                          | 1         | 1.15%   |
| Toshiba LCD Monitor LCD58EB 1280x800 261x163mm 12.1-inch                | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch    | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch    | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch    | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SDC4E51 1366x768 344x194mm 15.5-inch    | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 1872x1053mm 84.6-inch | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 1020x570mm 46.0-inch  | 1         | 1.15%   |
| Samsung Electronics LCD Monitor SAM090B 1920x1080 890x500mm 40.2-inch   | 1         | 1.15%   |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                   | 1         | 1.15%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                    | 1         | 1.15%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                     | 1         | 1.15%   |
| PANDA LM156LF1L03 NCP001C 1920x1080 344x194mm 15.5-inch                 | 1         | 1.15%   |
| PANDA LCD Monitor NCP0040 1920x1080 344x194mm 15.5-inch                 | 1         | 1.15%   |
| PANDA LC116LF3L03 NCP000A 1920x1080 256x144mm 11.6-inch                 | 1         | 1.15%   |
| LG Display LCD Monitor LGDD302 1366x768 277x156mm 12.5-inch             | 1         | 1.15%   |
| LG Display LCD Monitor LGD0671 1920x1080 382x215mm 17.3-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD063B 1920x1080 382x215mm 17.3-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD0573 1920x1080 344x194mm 15.5-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD0532 1920x1080 344x194mm 15.5-inch            | 1         | 1.15%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch             | 1         | 1.15%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch             | 1         | 1.15%   |
| LG Display LCD Monitor LGD02AC 1366x768 344x194mm 15.5-inch             | 1         | 1.15%   |
| Iiyama PL2493H IVM6148 1920x1080 527x296mm 23.8-inch                    | 1         | 1.15%   |
| HUAWEI ZQE-CBA HWV6A25 3440x1440 797x334mm 34.0-inch                    | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch        | 1         | 1.15%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch        | 1         | 1.15%   |
| BOE NV156FHM-N61 BOE07D0 1920x1080 344x193mm 15.5-inch                  | 1         | 1.15%   |
| BOE LCD Monitor BOE097A 1920x1080 309x174mm 14.0-inch                   | 1         | 1.15%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution       | Notebooks | Percent |
|------------------|-----------|---------|
| 1920x1080 (FHD)  | 64        | 79.01%  |
| 1366x768 (WXGA)  | 9         | 11.11%  |
| 3840x2160 (4K)   | 3         | 3.7%    |
| 3440x1440        | 1         | 1.23%   |
| 2240x1400        | 1         | 1.23%   |
| 1600x900 (HD+)   | 1         | 1.23%   |
| 1280x800 (WXGA)  | 1         | 1.23%   |
| 1280x1024 (SXGA) | 1         | 1.23%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Notebooks | Percent |
|---------|-----------|---------|
| 15      | 62        | 72.09%  |
| 13      | 4         | 4.65%   |
| 17      | 3         | 3.49%   |
| 84      | 2         | 2.33%   |
| 40      | 2         | 2.33%   |
| 24      | 2         | 2.33%   |
| 21      | 2         | 2.33%   |
| 14      | 2         | 2.33%   |
| 12      | 2         | 2.33%   |
| 54      | 1         | 1.16%   |
| 34      | 1         | 1.16%   |
| 19      | 1         | 1.16%   |
| 11      | 1         | 1.16%   |
| Unknown | 1         | 1.16%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Notebooks | Percent |
|-------------|-----------|---------|
| 301-350     | 68        | 79.07%  |
| 351-400     | 4         | 4.65%   |
| 201-300     | 3         | 3.49%   |
| 501-600     | 2         | 2.33%   |
| 401-500     | 2         | 2.33%   |
| 1501-2000   | 2         | 2.33%   |
| 901-1000    | 2         | 2.33%   |
| 701-800     | 1         | 1.16%   |
| 1001-1500   | 1         | 1.16%   |
| Unknown     | 1         | 1.16%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Notebooks | Percent |
|-------|-----------|---------|
| 16/9  | 73        | 92.41%  |
| 21/9  | 3         | 3.8%    |
| 16/10 | 2         | 2.53%   |
| 5/4   | 1         | 1.27%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Notebooks | Percent |
|----------------|-----------|---------|
| 101-110        | 62        | 72.09%  |
| 81-90          | 6         | 6.98%   |
| 201-250        | 4         | 4.65%   |
| More than 1000 | 3         | 3.49%   |
| 121-130        | 3         | 3.49%   |
| 61-70          | 2         | 2.33%   |
| 501-1000       | 2         | 2.33%   |
| 51-60          | 1         | 1.16%   |
| 351-500        | 1         | 1.16%   |
| 151-200        | 1         | 1.16%   |
| Unknown        | 1         | 1.16%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Notebooks | Percent |
|---------|-----------|---------|
| 121-160 | 63        | 75%     |
| 101-120 | 12        | 14.29%  |
| 51-100  | 5         | 5.95%   |
| 161-240 | 2         | 2.38%   |
| 1-50    | 1         | 1.19%   |
| Unknown | 1         | 1.19%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 1     | 66        | 81.48%  |
| 2     | 8         | 9.88%   |
| 0     | 7         | 8.64%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 60        | 52.17%  |
| Intel                 | 34        | 29.57%  |
| Qualcomm Atheros      | 4         | 3.48%   |
| Broadcom              | 4         | 3.48%   |
| MediaTek              | 3         | 2.61%   |
| TP-Link               | 2         | 1.74%   |
| Samsung Electronics   | 2         | 1.74%   |
| Ralink                | 2         | 1.74%   |
| Xiaomi                | 1         | 0.87%   |
| Ralink Technology     | 1         | 0.87%   |
| OPPO Electronics      | 1         | 0.87%   |
| OKB SAPR              | 1         | 0.87%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 25        | 17.48%  |
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 17.48%  |
| Intel Wireless 7265                                               | 10        | 6.99%   |
| Intel Ethernet Connection (6) I219-V                              | 8         | 5.59%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 5         | 3.5%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 2.8%    |
| Intel Wi-Fi 6 AX201                                               | 4         | 2.8%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 4         | 2.8%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 3         | 2.1%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 3         | 2.1%    |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 3         | 2.1%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 2.1%    |
| Intel Wireless 3165                                               | 3         | 2.1%    |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.4%    |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 2         | 1.4%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 2         | 1.4%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 1.4%    |
| Intel Ethernet Controller I225-V                                  | 2         | 1.4%    |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 1.4%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                   | 2         | 1.4%    |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 1.4%    |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.7%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 0.7%    |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.7%    |
| TP-Link 802.11n NIC                                               | 1         | 0.7%    |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller       | 1         | 0.7%    |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter           | 1         | 0.7%    |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                        | 1         | 0.7%    |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.7%    |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.7%    |
| Ralink RT5370 Wireless Adapter                                    | 1         | 0.7%    |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 1         | 0.7%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.7%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 1         | 0.7%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.7%    |
| OPPO RMX3263                                                      | 1         | 0.7%    |
| OKB SAPR Ethernet controller                                      | 1         | 0.7%    |
| MediaTek KINGKONG_MINI                                            | 1         | 0.7%    |
| Intel Wireless 8265 / 8275                                        | 1         | 0.7%    |
| Intel Tiger Lake PCH CNVi WiFi                                    | 1         | 0.7%    |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 39        | 45.88%  |
| Intel                 | 33        | 38.82%  |
| Qualcomm Atheros      | 3         | 3.53%   |
| Broadcom              | 3         | 3.53%   |
| TP-Link               | 2         | 2.35%   |
| Ralink                | 2         | 2.35%   |
| MediaTek              | 2         | 2.35%   |
| Ralink Technology     | 1         | 1.18%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Notebooks | Percent |
|----------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 25        | 28.74%  |
| Intel Wireless 7265                                            | 10        | 11.49%  |
| Intel Alder Lake-P PCH CNVi WiFi                               | 5         | 5.75%   |
| Intel Wi-Fi 6 AX201                                            | 4         | 4.6%    |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 4         | 4.6%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 3         | 3.45%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 3         | 3.45%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 3         | 3.45%   |
| Intel Wireless 3165                                            | 3         | 3.45%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 2         | 2.3%    |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 2         | 2.3%    |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 2         | 2.3%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 2         | 2.3%    |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 2.3%    |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 1.15%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]     | 1         | 1.15%   |
| TP-Link 802.11n NIC                                            | 1         | 1.15%   |
| Realtek RTL8852BE PCIe 802.11ax Wireless Network Controller    | 1         | 1.15%   |
| Realtek RTL8812AU 802.11a/b/g/n/ac 2T2R DB WLAN Adapter        | 1         | 1.15%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.15%   |
| Realtek 802.11n WLAN Adapter                                   | 1         | 1.15%   |
| Ralink RT5370 Wireless Adapter                                 | 1         | 1.15%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 1         | 1.15%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.15%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 1         | 1.15%   |
| Intel Wireless 8265 / 8275                                     | 1         | 1.15%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 1         | 1.15%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection          | 1         | 1.15%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 1         | 1.15%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 1         | 1.15%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 1         | 1.15%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Notebooks | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 33        | 58.93%  |
| Intel                 | 15        | 26.79%  |
| Samsung Electronics   | 2         | 3.57%   |
| Xiaomi                | 1         | 1.79%   |
| Qualcomm Atheros      | 1         | 1.79%   |
| OPPO Electronics      | 1         | 1.79%   |
| OKB SAPR              | 1         | 1.79%   |
| MediaTek              | 1         | 1.79%   |
| Broadcom              | 1         | 1.79%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Notebooks | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 25        | 44.64%  |
| Intel Ethernet Connection (6) I219-V                              | 8         | 14.29%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 4         | 7.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 3         | 5.36%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 3.57%   |
| Intel Ethernet Controller I225-V                                  | 2         | 3.57%   |
| Intel Ethernet Connection (16) I219-LM                            | 2         | 3.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 1.79%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 1.79%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 1.79%   |
| OPPO RMX3263                                                      | 1         | 1.79%   |
| OKB SAPR Ethernet controller                                      | 1         | 1.79%   |
| MediaTek KINGKONG_MINI                                            | 1         | 1.79%   |
| Intel Ethernet Connection (16) I219-V                             | 1         | 1.79%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 1.79%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 1.79%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 1.79%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 80        | 60.61%  |
| Ethernet | 52        | 39.39%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Notebooks | Percent |
|----------|-----------|---------|
| WiFi     | 52        | 64.2%   |
| Ethernet | 29        | 35.8%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Notebooks | Percent |
|-------|-----------|---------|
| 2     | 45        | 55.56%  |
| 1     | 33        | 40.74%  |
| 0     | 3         | 3.7%    |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Notebooks | Percent |
|------|-----------|---------|
| No   | 76        | 91.57%  |
| Yes  | 7         | 8.43%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Notebooks | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 30        | 42.86%  |
| Realtek Semiconductor           | 27        | 38.57%  |
| Broadcom                        | 4         | 5.71%   |
| Realtek                         | 2         | 2.86%   |
| Ralink                          | 2         | 2.86%   |
| IMC Networks                    | 2         | 2.86%   |
| Qualcomm Atheros Communications | 1         | 1.43%   |
| Lite-On Technology              | 1         | 1.43%   |
| Foxconn / Hon Hai               | 1         | 1.43%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                          | Notebooks | Percent |
|------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                        | 24        | 34.29%  |
| Intel Bluetooth wireless interface             | 15        | 21.43%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP) | 6         | 8.57%   |
| Intel AX201 Bluetooth                          | 6         | 8.57%   |
| Realtek  Bluetooth 4.2 Adapter                 | 3         | 4.29%   |
| Intel Bluetooth Device                         | 3         | 4.29%   |
| Realtek Bluetooth Radio                        | 2         | 2.86%   |
| Ralink RT3290 Bluetooth                        | 2         | 2.86%   |
| IMC Networks Bluetooth Radio                   | 2         | 2.86%   |
| Qualcomm Atheros  Bluetooth Device             | 1         | 1.43%   |
| Lite-On Wireless_Device                        | 1         | 1.43%   |
| Foxconn / Hon Hai Wireless_Device              | 1         | 1.43%   |
| Broadcom HP Portable Valentine                 | 1         | 1.43%   |
| Broadcom BCM43142A0 Bluetooth 4.0              | 1         | 1.43%   |
| Broadcom BCM2045B (BDC-2.1)                    | 1         | 1.43%   |
| Broadcom BCM2045 Bluetooth                     | 1         | 1.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Notebooks | Percent |
|----------------------|-----------|---------|
| Intel                | 63        | 70.79%  |
| AMD                  | 18        | 20.22%  |
| Nvidia               | 6         | 6.74%   |
| Zhaoxin              | 1         | 1.12%   |
| MosArt Semiconductor | 1         | 1.12%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Notebooks | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP High Definition Audio Controller                                            | 29        | 26.85%  |
| AMD Family 17h/19h HD Audio Controller                                                            | 16        | 14.81%  |
| AMD Renoir Radeon High Definition Audio Controller                                                | 12        | 11.11%  |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 7         | 6.48%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                                           | 5         | 4.63%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 4         | 3.7%    |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 2.78%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 3         | 2.78%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 2         | 1.85%   |
| Intel Tiger Lake-H HD Audio Controller                                                            | 2         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 2         | 1.85%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 2         | 1.85%   |
| Intel 8 Series HD Audio Controller                                                                | 2         | 1.85%   |
| Zhaoxin ZX-E High Definition Audio Controller                                                     | 1         | 0.93%   |
| Zhaoxin ZX-100/KX-5000/KX-6000/KX-6000G High Definition Audio Controller                          | 1         | 0.93%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 1         | 0.93%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Nvidia GA106 High Definition Audio Controller                                                     | 1         | 0.93%   |
| Nvidia Audio device                                                                               | 1         | 0.93%   |
| MosArt Semiconductor MosArt USB Audio Device                                                      | 1         | 0.93%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 1         | 0.93%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 1         | 0.93%   |
| Intel CM238 HD Audio Controller                                                                   | 1         | 0.93%   |
| Intel Cannon Lake PCH cAVS                                                                        | 1         | 0.93%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 1         | 0.93%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 1         | 0.93%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 1         | 0.93%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 1         | 0.93%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 1         | 0.93%   |
| AMD SBx00 Azalia (Intel HDA)                                                                      | 1         | 0.93%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 1         | 0.93%   |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                                            | 1         | 0.93%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Notebooks | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 35        | 40.7%   |
| SK hynix            | 12        | 13.95%  |
| Foxline             | 10        | 11.63%  |
| Micron Technology   | 7         | 8.14%   |
| Crucial             | 5         | 5.81%   |
| Ramaxel Technology  | 3         | 3.49%   |
| Unknown (ABCD)      | 2         | 2.33%   |
| Unknown             | 2         | 2.33%   |
| Kingston            | 2         | 2.33%   |
| Elpida              | 2         | 2.33%   |
| SHARETRONIC         | 1         | 1.16%   |
| Qumo                | 1         | 1.16%   |
| King Tiger          | 1         | 1.16%   |
| ChangXin Memory     | 1         | 1.16%   |
| <Invalid>           | 1         | 1.16%   |
| Unknown             | 1         | 1.16%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Notebooks | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 18.89%  |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 4         | 4.44%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 3         | 3.33%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 3.33%   |
| Foxline RAM FL3200D4S22-8G 8GB SODIMM DDR4 3200MT/s              | 3         | 3.33%   |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 3         | 3.33%   |
| Foxline RAM FL2400D4S17S-8G 8192MB SODIMM DDR4 2400MT/s          | 3         | 3.33%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 2.22%   |
| SK hynix RAM HMA851S6CJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 2         | 2.22%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 2.22%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 2.22%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 2         | 2.22%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 2.22%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.11%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 1.11%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 1.11%   |
| SK hynix RAM HMAB2GS6CMR6N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 1.11%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 1.11%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 1.11%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.11%   |
| SHARETRONIC RAM Module 4GB SODIMM DDR3 1600MT/s                  | 1         | 1.11%   |
| Samsung RAM M471B5773DH0-CK0 2GB SODIMM DDR3 1600MT/s            | 1         | 1.11%   |
| Samsung RAM M471B5773DH0-CH9 2GB SODIMM DDR3 1600MT/s            | 1         | 1.11%   |
| Samsung RAM M471B5673FH0-CH9 2GB SODIMM DDR3 1334MT/s            | 1         | 1.11%   |
| Samsung RAM M471B2873EH1-CH9 1GB SODIMM DDR3 1333MT/s            | 1         | 1.11%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 1         | 1.11%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.11%   |
| Samsung RAM M471A5244BB0-CWE 4GB SODIMM DDR4 3200MT/s            | 1         | 1.11%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 1.11%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 1.11%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.11%   |
| Samsung RAM M471A1G44BB0-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.11%   |
| Ramaxel RAM RMSA3310MJ86H9F-3200 4096MB SODIMM DDR4 3200MT/s     | 1         | 1.11%   |
| Ramaxel RAM RMSA3300ME78HBF-2666 16GB SODIMM DDR4 2667MT/s       | 1         | 1.11%   |
| Ramaxel RAM RMSA3270ME86H9F-2666 4GB SODIMM DDR4 2667MT/s        | 1         | 1.11%   |
| Qumo RAM QUM4S-8G3200P22 8GB SODIMM DDR4 3200MT/s                | 1         | 1.11%   |
| Micron RAM 8ATF1G64HZ-3G2R1 8GB SODIMM DDR4 3200MT/s             | 1         | 1.11%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 1         | 1.11%   |
| Micron RAM 4ATF51264HZ-3G2J1 4GB SODIMM DDR4 3200MT/s            | 1         | 1.11%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s       | 1         | 1.11%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind   | Notebooks | Percent |
|--------|-----------|---------|
| DDR4   | 65        | 82.28%  |
| DDR3   | 10        | 12.66%  |
| LPDDR4 | 3         | 3.8%    |
| DDR2   | 1         | 1.27%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Notebooks | Percent |
|--------------|-----------|---------|
| SODIMM       | 73        | 87.95%  |
| Row Of Chips | 9         | 10.84%  |
| DIMM         | 1         | 1.2%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Notebooks | Percent |
|-------|-----------|---------|
| 8192  | 49        | 59.04%  |
| 4096  | 22        | 26.51%  |
| 2048  | 5         | 6.02%   |
| 16384 | 4         | 4.82%   |
| 1024  | 3         | 3.61%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed | Notebooks | Percent |
|-------|-----------|---------|
| 2667  | 31        | 37.8%   |
| 3200  | 28        | 34.15%  |
| 2400  | 7         | 8.54%   |
| 1600  | 6         | 7.32%   |
| 3266  | 2         | 2.44%   |
| 1334  | 2         | 2.44%   |
| 3733  | 1         | 1.22%   |
| 2666  | 1         | 1.22%   |
| 1866  | 1         | 1.22%   |
| 1333  | 1         | 1.22%   |
| 1066  | 1         | 1.22%   |
| 667   | 1         | 1.22%   |

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
| Syntek                                 | 19        | 23.75%  |
| Chicony Electronics                    | 19        | 23.75%  |
| IMC Networks                           | 9         | 11.25%  |
| Acer                                   | 7         | 8.75%   |
| Quanta                                 | 4         | 5%      |
| Luxvisions Innotech Limited            | 3         | 3.75%   |
| USB Camera CS                          | 2         | 2.5%    |
| Suyin                                  | 2         | 2.5%    |
| Sunplus Innovation Technology          | 2         | 2.5%    |
| Sonix Technology                       | 2         | 2.5%    |
| Realtek Semiconductor                  | 2         | 2.5%    |
| Microdia                               | 2         | 2.5%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.5%    |
| Bison Electronics                      | 2         | 2.5%    |
| SunplusIT                              | 1         | 1.25%   |
| Alcor Micro                            | 1         | 1.25%   |
| Unknown                                | 1         | 1.25%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Notebooks | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 18        | 22.5%   |
| Chicony USB camera                                                         | 9         | 11.25%  |
| IMC Networks ov9734_azurewave_camera                                       | 3         | 3.75%   |
| IMC Networks Integrated Camera                                             | 3         | 3.75%   |
| Chicony Integrated Camera                                                  | 3         | 3.75%   |
| Acer Integrated Camera                                                     | 3         | 3.75%   |
| USB Camera CS USB Camera CS                                                | 2         | 2.5%    |
| Sonix USB 2.0 Camera                                                       | 2         | 2.5%    |
| Quanta HP TrueVision HD Camera                                             | 2         | 2.5%    |
| Luxvisions Innotech Limited Integrated Camera                              | 2         | 2.5%    |
| Chicony HD User Facing                                                     | 2         | 2.5%    |
| Bison Integrated Camera                                                    | 2         | 2.5%    |
| Syntek Lenovo EasyCamera                                                   | 1         | 1.25%   |
| Suyin HP Truevision HD                                                     | 1         | 1.25%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 1.25%   |
| SunplusIT USB camera                                                       | 1         | 1.25%   |
| Sunplus BKX Usb FHD Camera                                                 | 1         | 1.25%   |
| Sunplus Asus Webcam                                                        | 1         | 1.25%   |
| Realtek USB2.0-Camera                                                      | 1         | 1.25%   |
| Realtek HP Truevision HD                                                   | 1         | 1.25%   |
| Quanta USB HD Webcam                                                       | 1         | 1.25%   |
| Quanta HD Camera                                                           | 1         | 1.25%   |
| Microdia Webcam Vitade AF                                                  | 1         | 1.25%   |
| Microdia USB 2.0 Camera                                                    | 1         | 1.25%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.25%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.25%   |
| IMC Networks USB2.0 HD UVC WebCam                                          | 1         | 1.25%   |
| IMC Networks HD Camera                                                     | 1         | 1.25%   |
| Chicony USB2.0 Camera                                                      | 1         | 1.25%   |
| Chicony Lenovo Integrated Camera (0.3MP)                                   | 1         | 1.25%   |
| Chicony Integrated Camera (1280x720@30)                                    | 1         | 1.25%   |
| Chicony HP Webcam-50                                                       | 1         | 1.25%   |
| Chicony HP TrueVision HD Camera                                            | 1         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam              | 1         | 1.25%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 1.25%   |
| Alcor Micro USB 2.0 Camera                                                 | 1         | 1.25%   |
| Acer Lenovo Integrated Webcam                                              | 1         | 1.25%   |
| Acer HD Webcam                                                             | 1         | 1.25%   |
| Acer EasyCamera                                                            | 1         | 1.25%   |
| Acer BisonCam, NB Pro                                                      | 1         | 1.25%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Notebooks | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 6         | 75%     |
| Synaptics                  | 2         | 25%     |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Notebooks | Percent |
|-------------------------------------|-----------|---------|
| Shenzhen Goodix  Fingerprint Device | 6         | 75%     |
| Synaptics UWP WBDI Device           | 2         | 25%     |

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
| 0     | 58        | 69.88%  |
| 1     | 18        | 21.69%  |
| 2     | 7         | 8.43%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type               | Notebooks | Percent |
|--------------------|-----------|---------|
| Net/wireless       | 9         | 30%     |
| Graphics card      | 9         | 30%     |
| Fingerprint reader | 8         | 26.67%  |
| Bluetooth          | 2         | 6.67%   |
| Sound              | 1         | 3.33%   |
| Net/ethernet       | 1         | 3.33%   |

