Red OS - Tested Hardware & Statistics
-------------------------------------

A project to collect tested hardware configurations for Red OS.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Red_OS/Desktop/README.md) and [notebooks](/Dist/Red_OS/Notebook/README.md).

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

Total: 188

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | A520M DS3H                  | Desktop     | [8fe13e2165](https://linux-hardware.org/?probe=8fe13e2165) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [562f466f8d](https://linux-hardware.org/?probe=562f466f8d) | Nov 02, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [38b68c6946](https://linux-hardware.org/?probe=38b68c6946) | Nov 02, 2022 |
| ASRock        | H510M-HVS R2.0              | Desktop     | [b68271c648](https://linux-hardware.org/?probe=b68271c648) | Nov 02, 2022 |
| Gigabyte      | B450M H                     | Desktop     | [06bbc75ef0](https://linux-hardware.org/?probe=06bbc75ef0) | Nov 01, 2022 |
| MSI           | 0A90                        | Desktop     | [47fa407c02](https://linux-hardware.org/?probe=47fa407c02) | Nov 01, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [d653658a53](https://linux-hardware.org/?probe=d653658a53) | Oct 28, 2022 |
| Gigabyte      | B560M H                     | Desktop     | [00766db60b](https://linux-hardware.org/?probe=00766db60b) | Oct 28, 2022 |
| MSI           | 0A90                        | Desktop     | [a15ab9db5e](https://linux-hardware.org/?probe=a15ab9db5e) | Oct 28, 2022 |
| Gigabyte      | GA-880GM-D2H                | Desktop     | [cacdacb3ad](https://linux-hardware.org/?probe=cacdacb3ad) | Oct 28, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [b9ab6b9cf2](https://linux-hardware.org/?probe=b9ab6b9cf2) | Oct 28, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [9c429fe90c](https://linux-hardware.org/?probe=9c429fe90c) | Oct 27, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [1ee47a3ab6](https://linux-hardware.org/?probe=1ee47a3ab6) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [92dbe47379](https://linux-hardware.org/?probe=92dbe47379) | Oct 25, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [247782b262](https://linux-hardware.org/?probe=247782b262) | Oct 25, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [14537f243b](https://linux-hardware.org/?probe=14537f243b) | Oct 24, 2022 |
| THUNDEROBO... | 911AirD                     | Notebook    | [f471a1c9db](https://linux-hardware.org/?probe=f471a1c9db) | Oct 23, 2022 |
| Lenovo        | 3708 NOK                    | Desktop     | [f48f731517](https://linux-hardware.org/?probe=f48f731517) | Oct 21, 2022 |
| Intel         | S2600WFT H48104-854         | Server      | [4887ba4bfa](https://linux-hardware.org/?probe=4887ba4bfa) | Oct 21, 2022 |
| Acer          | Aspire A517-52              | Notebook    | [7515d53b5d](https://linux-hardware.org/?probe=7515d53b5d) | Oct 21, 2022 |
| Gigabyte      | B360HD3                     | Desktop     | [bbbdee0883](https://linux-hardware.org/?probe=bbbdee0883) | Oct 21, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [71c9391b8b](https://linux-hardware.org/?probe=71c9391b8b) | Oct 21, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [3fc175d4a0](https://linux-hardware.org/?probe=3fc175d4a0) | Oct 20, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [39838b7f39](https://linux-hardware.org/?probe=39838b7f39) | Oct 20, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [fe184c8f5b](https://linux-hardware.org/?probe=fe184c8f5b) | Oct 19, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [0db79bc085](https://linux-hardware.org/?probe=0db79bc085) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [e75a8830af](https://linux-hardware.org/?probe=e75a8830af) | Oct 19, 2022 |
| Gigabyte      | H510M S2H                   | Desktop     | [b8303261ad](https://linux-hardware.org/?probe=b8303261ad) | Oct 18, 2022 |
| HP            | 83EB                        | All in one  | [1011557c31](https://linux-hardware.org/?probe=1011557c31) | Oct 18, 2022 |
| HP            | 83EB                        | All in one  | [f81210f730](https://linux-hardware.org/?probe=f81210f730) | Oct 18, 2022 |
| Intel         | S2600WFT H48104-854         | Server      | [7fa3948164](https://linux-hardware.org/?probe=7fa3948164) | Oct 17, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [c6958291bd](https://linux-hardware.org/?probe=c6958291bd) | Oct 14, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [1cdde90662](https://linux-hardware.org/?probe=1cdde90662) | Oct 13, 2022 |
| HP            | 1495                        | Desktop     | [b1523ff4a6](https://linux-hardware.org/?probe=b1523ff4a6) | Oct 13, 2022 |
| YADRO         | VEGMAN Motherboard MBDX8... | Server      | [97b57f8628](https://linux-hardware.org/?probe=97b57f8628) | Oct 13, 2022 |
| YADRO         | VEGMAN Motherboard MBDX8... | Server      | [f74f853f54](https://linux-hardware.org/?probe=f74f853f54) | Oct 12, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [087d1975e1](https://linux-hardware.org/?probe=087d1975e1) | Oct 12, 2022 |
| ASUSTek       | B150M-C                     | Desktop     | [1d936352ea](https://linux-hardware.org/?probe=1d936352ea) | Oct 10, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [e799b41d70](https://linux-hardware.org/?probe=e799b41d70) | Oct 09, 2022 |
| Acer          | Aspire 2920                 | Notebook    | [c588bacc95](https://linux-hardware.org/?probe=c588bacc95) | Oct 08, 2022 |
| Acer          | Aspire 2920                 | Notebook    | [34b41a4e67](https://linux-hardware.org/?probe=34b41a4e67) | Oct 08, 2022 |
| MSI           | H55M-E33                    | Desktop     | [95423ecdbe](https://linux-hardware.org/?probe=95423ecdbe) | Oct 07, 2022 |
| ASUSTek       | X540NV                      | Notebook    | [31e4464fea](https://linux-hardware.org/?probe=31e4464fea) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [9fd01561ce](https://linux-hardware.org/?probe=9fd01561ce) | Oct 07, 2022 |
| ASRock        | B460M Pro4                  | Desktop     | [4c0bb83f01](https://linux-hardware.org/?probe=4c0bb83f01) | Oct 07, 2022 |
| MSI           | H55M-E33                    | Desktop     | [7af53a4dee](https://linux-hardware.org/?probe=7af53a4dee) | Oct 06, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [7f8e650618](https://linux-hardware.org/?probe=7f8e650618) | Oct 06, 2022 |
| Acer          | Aspire 2920                 | Notebook    | [538f7a6e26](https://linux-hardware.org/?probe=538f7a6e26) | Oct 05, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [0a8238a876](https://linux-hardware.org/?probe=0a8238a876) | Oct 05, 2022 |
| Lenovo        | 3188 SDK0J40697 WIN 3305... | Desktop     | [b90de94f3d](https://linux-hardware.org/?probe=b90de94f3d) | Oct 05, 2022 |
| THUNDEROBO... | 911AirD                     | Notebook    | [69a9650652](https://linux-hardware.org/?probe=69a9650652) | Oct 03, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [89b48cd98e](https://linux-hardware.org/?probe=89b48cd98e) | Oct 03, 2022 |
| Lenovo        | 32E4 NOK                    | Mini pc     | [f49f7ba847](https://linux-hardware.org/?probe=f49f7ba847) | Oct 03, 2022 |
| Digma         | EVE 11 C408                 | Notebook    | [b5c7ac8ed3](https://linux-hardware.org/?probe=b5c7ac8ed3) | Sep 30, 2022 |
| ASRock        | B360M-HDV                   | Desktop     | [fad5a877f5](https://linux-hardware.org/?probe=fad5a877f5) | Sep 30, 2022 |
| THUNDEROBO... | 911AirD                     | Notebook    | [99f1b7e253](https://linux-hardware.org/?probe=99f1b7e253) | Sep 29, 2022 |
| RDW           | MB-B450M V.1                | Desktop     | [8c3a565d43](https://linux-hardware.org/?probe=8c3a565d43) | Sep 26, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [1748378749](https://linux-hardware.org/?probe=1748378749) | Sep 22, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [3888b56318](https://linux-hardware.org/?probe=3888b56318) | Sep 22, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [66a228f8c5](https://linux-hardware.org/?probe=66a228f8c5) | Sep 21, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [0b610b66a9](https://linux-hardware.org/?probe=0b610b66a9) | Sep 20, 2022 |
| Gigabyte      | H110M-S2-CF                 | Desktop     | [fd03d25b78](https://linux-hardware.org/?probe=fd03d25b78) | Sep 15, 2022 |
| ECS           | H510H6-M7                   | Desktop     | [1275257180](https://linux-hardware.org/?probe=1275257180) | Sep 14, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [713797403a](https://linux-hardware.org/?probe=713797403a) | Sep 09, 2022 |
| IP3 Techno... | ACN30                       | Notebook    | [af9694cea8](https://linux-hardware.org/?probe=af9694cea8) | Sep 06, 2022 |
| IP3 Techno... | ACN30                       | Notebook    | [03f14a115d](https://linux-hardware.org/?probe=03f14a115d) | Sep 05, 2022 |
| Unknown       | Unknown                     | Desktop     | [40c1fd4544](https://linux-hardware.org/?probe=40c1fd4544) | Sep 05, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [04b62ac6e3](https://linux-hardware.org/?probe=04b62ac6e3) | Sep 04, 2022 |
| Gigabyte      | B450 AORUS PRO-CF           | Desktop     | [a60315c259](https://linux-hardware.org/?probe=a60315c259) | Sep 04, 2022 |
| MSI           | FX610                       | Notebook    | [a822818a58](https://linux-hardware.org/?probe=a822818a58) | Sep 03, 2022 |
| ASRock        | N68-VS3 FX                  | Desktop     | [b4c043c208](https://linux-hardware.org/?probe=b4c043c208) | Sep 01, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [3b519201e2](https://linux-hardware.org/?probe=3b519201e2) | Aug 22, 2022 |
| Gigabyte      | X58-USB3                    | Desktop     | [5119bcb630](https://linux-hardware.org/?probe=5119bcb630) | Aug 19, 2022 |
| IP3 Techno... | ACN30                       | Notebook    | [e25ed534c0](https://linux-hardware.org/?probe=e25ed534c0) | Aug 18, 2022 |
| ICL           | RAYbook Si1512              | Notebook    | [a42c4dc65a](https://linux-hardware.org/?probe=a42c4dc65a) | Aug 09, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [c02a953cda](https://linux-hardware.org/?probe=c02a953cda) | Aug 01, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [14f73b6a3a](https://linux-hardware.org/?probe=14f73b6a3a) | Aug 01, 2022 |
| Digma         | EVE 15 P417 ES5063EW        | Notebook    | [a584c678b5](https://linux-hardware.org/?probe=a584c678b5) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | Notebook    | [4fd01756b2](https://linux-hardware.org/?probe=4fd01756b2) | Jul 27, 2022 |
| Digma         | EVE 15 C407 ES5054EW        | Notebook    | [008b02cc92](https://linux-hardware.org/?probe=008b02cc92) | Jul 26, 2022 |
| Dell          | 040DDP A00                  | Desktop     | [5375c9c059](https://linux-hardware.org/?probe=5375c9c059) | Jul 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [413949a727](https://linux-hardware.org/?probe=413949a727) | Jul 25, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [3bfcedd5c8](https://linux-hardware.org/?probe=3bfcedd5c8) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [c49282206c](https://linux-hardware.org/?probe=c49282206c) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [d598c4587d](https://linux-hardware.org/?probe=d598c4587d) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [7cc031e93b](https://linux-hardware.org/?probe=7cc031e93b) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [946610c122](https://linux-hardware.org/?probe=946610c122) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [5b1e962751](https://linux-hardware.org/?probe=5b1e962751) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [4e120b3b63](https://linux-hardware.org/?probe=4e120b3b63) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [fbff39be7e](https://linux-hardware.org/?probe=fbff39be7e) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [2d5bedf224](https://linux-hardware.org/?probe=2d5bedf224) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [297ce5144e](https://linux-hardware.org/?probe=297ce5144e) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [84b7cd1115](https://linux-hardware.org/?probe=84b7cd1115) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [a92b6c5d73](https://linux-hardware.org/?probe=a92b6c5d73) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [51ebd271c8](https://linux-hardware.org/?probe=51ebd271c8) | Jul 22, 2022 |
| DEPO Compu... | DPH310T                     | Desktop     | [0076bf5efc](https://linux-hardware.org/?probe=0076bf5efc) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [44ad7f7d47](https://linux-hardware.org/?probe=44ad7f7d47) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [49068a26b5](https://linux-hardware.org/?probe=49068a26b5) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [62ce596bf3](https://linux-hardware.org/?probe=62ce596bf3) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [812db8ad6f](https://linux-hardware.org/?probe=812db8ad6f) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [d4c2b5ffad](https://linux-hardware.org/?probe=d4c2b5ffad) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [4c0179b60e](https://linux-hardware.org/?probe=4c0179b60e) | Jul 22, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [8601888983](https://linux-hardware.org/?probe=8601888983) | Jul 22, 2022 |
| Lenovo        | V15-IWL 81YE                | Notebook    | [1d505390d6](https://linux-hardware.org/?probe=1d505390d6) | Jul 22, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [5b3340311a](https://linux-hardware.org/?probe=5b3340311a) | Jul 20, 2022 |
| Lenovo        | IdeaPad L340-15API 81LW     | Notebook    | [154c254eac](https://linux-hardware.org/?probe=154c254eac) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | Notebook    | [60921a7ff6](https://linux-hardware.org/?probe=60921a7ff6) | Jul 19, 2022 |
| Gigabyte      | G5 GD                       | Notebook    | [c24f8b4ba6](https://linux-hardware.org/?probe=c24f8b4ba6) | Jul 19, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [4f1a1bfb2d](https://linux-hardware.org/?probe=4f1a1bfb2d) | Jul 19, 2022 |
| Gigabyte      | 970A-D3                     | Desktop     | [f2ae77cc0c](https://linux-hardware.org/?probe=f2ae77cc0c) | Jul 17, 2022 |
| HONOR         | NBR-WAX9                    | Notebook    | [fe971bb8c3](https://linux-hardware.org/?probe=fe971bb8c3) | Jul 08, 2022 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [2835672840](https://linux-hardware.org/?probe=2835672840) | Jul 07, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [24e49bc011](https://linux-hardware.org/?probe=24e49bc011) | Jun 27, 2022 |
| Kraftway      | ACCORD                      | Notebook    | [39e3c55e89](https://linux-hardware.org/?probe=39e3c55e89) | Jun 27, 2022 |
| ASUSTek       | M2N68-AM Plus               | Desktop     | [d85cded80a](https://linux-hardware.org/?probe=d85cded80a) | Jun 20, 2022 |
| Aquarius      | NS685U                      | Notebook    | [ecedc7cbb6](https://linux-hardware.org/?probe=ecedc7cbb6) | Jun 08, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [28e8a1e19c](https://linux-hardware.org/?probe=28e8a1e19c) | Jun 07, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [df5b1991e1](https://linux-hardware.org/?probe=df5b1991e1) | Jun 07, 2022 |
| ICL           | Unknown                     | Notebook    | [4dc89fc689](https://linux-hardware.org/?probe=4dc89fc689) | Jun 07, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [8ea7efbf2e](https://linux-hardware.org/?probe=8ea7efbf2e) | Jun 07, 2022 |
| iRU           | v1.0                        | Mini pc     | [845212ce42](https://linux-hardware.org/?probe=845212ce42) | Jun 02, 2022 |
| iRU           | v1.0                        | Mini pc     | [15b125fb9e](https://linux-hardware.org/?probe=15b125fb9e) | May 31, 2022 |
| iRU           | v1.0                        | Mini pc     | [991e061d78](https://linux-hardware.org/?probe=991e061d78) | May 31, 2022 |
| MSI           | A520M PRO                   | Desktop     | [3eb8006c14](https://linux-hardware.org/?probe=3eb8006c14) | May 26, 2022 |
| MSI           | A520M PRO                   | Desktop     | [9766bbe4c0](https://linux-hardware.org/?probe=9766bbe4c0) | May 25, 2022 |
| ASRock        | B365M Pro4-F                | Desktop     | [b3b2ee08af](https://linux-hardware.org/?probe=b3b2ee08af) | May 23, 2022 |
| MSI           | H510TI-S01                  | Desktop     | [efe42ef07a](https://linux-hardware.org/?probe=efe42ef07a) | May 19, 2022 |
| ASUSTek       | V241IC-R                    | All in one  | [48add8dc01](https://linux-hardware.org/?probe=48add8dc01) | May 19, 2022 |
| Gigabyte      | B365M H                     | Desktop     | [e405d209d4](https://linux-hardware.org/?probe=e405d209d4) | May 11, 2022 |
| mtech         | MTL1578                     | Notebook    | [bf25c26ea0](https://linux-hardware.org/?probe=bf25c26ea0) | May 11, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [66bb3248d5](https://linux-hardware.org/?probe=66bb3248d5) | May 11, 2022 |
| Digma         | CITI 10 C402T CS1044EW      | Tablet      | [eefe92e281](https://linux-hardware.org/?probe=eefe92e281) | May 04, 2022 |
| ASRock        | B560 Pro4                   | Desktop     | [1c3459c038](https://linux-hardware.org/?probe=1c3459c038) | Apr 19, 2022 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [e2e025dd4f](https://linux-hardware.org/?probe=e2e025dd4f) | Apr 15, 2022 |
| Acer          | TravelMate P215-53          | Notebook    | [124fdb3b64](https://linux-hardware.org/?probe=124fdb3b64) | Apr 14, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [be41efbec8](https://linux-hardware.org/?probe=be41efbec8) | Apr 05, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [d648ac5ab2](https://linux-hardware.org/?probe=d648ac5ab2) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [7b4861c8af](https://linux-hardware.org/?probe=7b4861c8af) | Apr 01, 2022 |
| Gigabyte      | H410M H V3                  | Desktop     | [9d86d8119a](https://linux-hardware.org/?probe=9d86d8119a) | Apr 01, 2022 |
| Gigabyte      | B75M-D2V                    | Desktop     | [b8ff95c0f1](https://linux-hardware.org/?probe=b8ff95c0f1) | Mar 30, 2022 |
| Aquarius      | NS585 R32                   | Notebook    | [582389ca98](https://linux-hardware.org/?probe=582389ca98) | Mar 24, 2022 |
| Lenovo        | 312D SDK0J40697 WIN 3305... | Mini pc     | [e76e5359b7](https://linux-hardware.org/?probe=e76e5359b7) | Mar 23, 2022 |
| Lenovo        | IdeaPad L340-15IWL 81LG     | Notebook    | [56f9ebba91](https://linux-hardware.org/?probe=56f9ebba91) | Mar 22, 2022 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [e18b80073c](https://linux-hardware.org/?probe=e18b80073c) | Mar 21, 2022 |
| 3Logic Gro... | APM Graviton A15i-K2        | Notebook    | [e93bcf2f42](https://linux-hardware.org/?probe=e93bcf2f42) | Mar 09, 2022 |
| ASUSTek       | H110-PLUS                   | Desktop     | [5074891336](https://linux-hardware.org/?probe=5074891336) | Mar 09, 2022 |
| Aquarius      | AQH410T                     | Desktop     | [f02c2d0259](https://linux-hardware.org/?probe=f02c2d0259) | Mar 02, 2022 |
| Aquarius      | AQB560M                     | All in one  | [4d3df118f0](https://linux-hardware.org/?probe=4d3df118f0) | Mar 01, 2022 |
| Aquarius      | AQB560M                     | Desktop     | [091fa6d697](https://linux-hardware.org/?probe=091fa6d697) | Mar 01, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [bf51c93832](https://linux-hardware.org/?probe=bf51c93832) | Feb 22, 2022 |
| Lenovo        | 316E SDK0J40697 WIN 3305... | Mini pc     | [a831ba5c10](https://linux-hardware.org/?probe=a831ba5c10) | Feb 22, 2022 |
| Gigabyte      | B560M DS3H                  | Desktop     | [9db1aef186](https://linux-hardware.org/?probe=9db1aef186) | Feb 18, 2022 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [227a2658d0](https://linux-hardware.org/?probe=227a2658d0) | Feb 15, 2022 |
| ASUSTek       | PRIME H510M-K               | Desktop     | [c1f9ad0faf](https://linux-hardware.org/?probe=c1f9ad0faf) | Feb 01, 2022 |
| Gigabyte      | B75M-D3V                    | Desktop     | [14d2075383](https://linux-hardware.org/?probe=14d2075383) | Jan 31, 2022 |
| ASUSTek       | PRIME H510T2/CSM            | Desktop     | [38ddf02b60](https://linux-hardware.org/?probe=38ddf02b60) | Jan 31, 2022 |
| Gigabyte      | B365M DS3H                  | Desktop     | [36db0c9260](https://linux-hardware.org/?probe=36db0c9260) | Jan 17, 2022 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [7ed7e139d8](https://linux-hardware.org/?probe=7ed7e139d8) | Dec 20, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [55ab1c9ab8](https://linux-hardware.org/?probe=55ab1c9ab8) | Dec 20, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [5bb21d6bf6](https://linux-hardware.org/?probe=5bb21d6bf6) | Dec 13, 2021 |
| Aquarius      | AQB560M                     | Desktop     | [ff20437ae0](https://linux-hardware.org/?probe=ff20437ae0) | Nov 25, 2021 |
| Aquarius      | AQB560M                     | Desktop     | [4656a05904](https://linux-hardware.org/?probe=4656a05904) | Nov 22, 2021 |
| Gigabyte      | B75M-D2V                    | Desktop     | [ef54320d4b](https://linux-hardware.org/?probe=ef54320d4b) | Oct 19, 2021 |
| Gigabyte      | B560M DS3H                  | Desktop     | [5a071f96dd](https://linux-hardware.org/?probe=5a071f96dd) | Oct 19, 2021 |
| ICL           | RAYbook Si1514              | Notebook    | [9ddc61deba](https://linux-hardware.org/?probe=9ddc61deba) | Sep 13, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [4f59992d0f](https://linux-hardware.org/?probe=4f59992d0f) | Sep 11, 2021 |
| ASRock        | H470M-HDV                   | Desktop     | [ba7bdac2dd](https://linux-hardware.org/?probe=ba7bdac2dd) | Sep 04, 2021 |
| Gigabyte      | H110M-M2-CF                 | Desktop     | [54a20af366](https://linux-hardware.org/?probe=54a20af366) | Aug 27, 2021 |
| HP            | Laptop 15-dw3xxx            | Notebook    | [d8b35044ab](https://linux-hardware.org/?probe=d8b35044ab) | Jul 29, 2021 |
| Lenovo        | IdeaPad 5 15ARE05 81YQ      | Notebook    | [9b2c758081](https://linux-hardware.org/?probe=9b2c758081) | Jun 10, 2021 |
| ASUSTek       | H110-PLUS                   | Desktop     | [11e1a45e67](https://linux-hardware.org/?probe=11e1a45e67) | Jun 03, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [7b4a0634ef](https://linux-hardware.org/?probe=7b4a0634ef) | Apr 26, 2021 |
| ASUSTek       | H110M-PLUS                  | Desktop     | [b779fb9e40](https://linux-hardware.org/?probe=b779fb9e40) | Apr 09, 2021 |
| ASUSTek       | P8H61-I LX R2.0             | Desktop     | [6e0321d64f](https://linux-hardware.org/?probe=6e0321d64f) | Apr 08, 2021 |
| ASUSTek       | X75VD                       | Notebook    | [95ea9551da](https://linux-hardware.org/?probe=95ea9551da) | Apr 05, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [916d4b225b](https://linux-hardware.org/?probe=916d4b225b) | Mar 30, 2021 |
| ASUSTek       | TUF Gaming FX705DT_FX705... | Notebook    | [ebfafc7409](https://linux-hardware.org/?probe=ebfafc7409) | Mar 26, 2021 |
| HUAWEI        | BOHL-WXX9                   | Notebook    | [cf5559d576](https://linux-hardware.org/?probe=cf5559d576) | Mar 26, 2021 |
| Gigabyte      | B365M DS3H                  | Desktop     | [d151197565](https://linux-hardware.org/?probe=d151197565) | Mar 26, 2021 |
| HP            | Pavilion g6                 | Notebook    | [1ca79b1950](https://linux-hardware.org/?probe=1ca79b1950) | Mar 26, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [a61243addd](https://linux-hardware.org/?probe=a61243addd) | Mar 26, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [30e7a27178](https://linux-hardware.org/?probe=30e7a27178) | Mar 22, 2021 |
| ASUSTek       | H110M-K                     | Desktop     | [da0a735a9f](https://linux-hardware.org/?probe=da0a735a9f) | Mar 18, 2021 |
| Pegatron      | A35                         | Notebook    | [9923a21e8c](https://linux-hardware.org/?probe=9923a21e8c) | Mar 04, 2021 |
| ASUSTek       | H81M-K                      | Desktop     | [5898a71c25](https://linux-hardware.org/?probe=5898a71c25) | Nov 03, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [12f125beba](https://linux-hardware.org/?probe=12f125beba) | Jan 16, 2020 |
| Gigabyte      | B360M DS3H                  | Desktop     | [c88331017f](https://linux-hardware.org/?probe=c88331017f) | Jan 16, 2020 |
| ASUSTek       | H81M-K                      | Desktop     | [24adf26804](https://linux-hardware.org/?probe=24adf26804) | Jan 13, 2020 |

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Red OS 7.3.1 | 88        | 61.97%  |
| Red OS 7.3   | 45        | 31.69%  |
| Red OS 7.2   | 5         | 3.52%   |
| Red OS 7.3.2 | 4         | 2.82%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| Red OS | 135       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                | Computers | Percent |
|------------------------|-----------|---------|
| 5.15.10-1.el7.x86_64   | 43        | 28.67%  |
| 5.10.29-1.el7.x86_64   | 23        | 15.33%  |
| 5.15.35-5.el7.3.x86_64 | 19        | 12.67%  |
| 5.15.35-4.el7.3.x86_64 | 18        | 12%     |
| 5.15.35-1.el7.3.x86_64 | 16        | 10.67%  |
| 5.15.10-2.el7.x86_64   | 5         | 3.33%   |
| 5.15.10-3.el7.x86_64   | 4         | 2.67%   |
| 5.10.1-1.el7.x86_64    | 4         | 2.67%   |
| 5.10.24-2.el7.x86_64   | 3         | 2%      |
| 4.19.79-1.el7.x86_64   | 3         | 2%      |
| 5.18.1-1.el7.x86_64    | 2         | 1.33%   |
| 5.15.10-4.el7.x86_64   | 2         | 1.33%   |
| 5.15.72-1.el7.3.x86_64 | 1         | 0.67%   |
| 5.14.9-1.el7.x86_64    | 1         | 0.67%   |
| 5.13.15-1.el7.x86_64   | 1         | 0.67%   |
| 5.10.29-3.el7.x86_64   | 1         | 0.67%   |
| 5.10.24-3.el7.x86_64   | 1         | 0.67%   |
| 5.10.24-1.el7.x86_64   | 1         | 0.67%   |
| 4.19.56-2.el7.x86_64   | 1         | 0.67%   |
| 4.19.204-1.el7.x86_64  | 1         | 0.67%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version  | Computers | Percent |
|----------|-----------|---------|
| 5.15.10  | 54        | 36.99%  |
| 5.15.35  | 49        | 33.56%  |
| 5.10.29  | 24        | 16.44%  |
| 5.10.24  | 5         | 3.42%   |
| 5.10.1   | 4         | 2.74%   |
| 4.19.79  | 3         | 2.05%   |
| 5.18.1   | 2         | 1.37%   |
| 5.15.72  | 1         | 0.68%   |
| 5.14.9   | 1         | 0.68%   |
| 5.13.15  | 1         | 0.68%   |
| 4.19.56  | 1         | 0.68%   |
| 4.19.204 | 1         | 0.68%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 101       | 71.13%  |
| 5.10    | 32        | 22.54%  |
| 4.19    | 5         | 3.52%   |
| 5.18    | 2         | 1.41%   |
| 5.14    | 1         | 0.7%    |
| 5.13    | 1         | 0.7%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 135       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| MATE       | 111       | 78.72%  |
| Cinnamon   | 27        | 19.15%  |
| X-Cinnamon | 2         | 1.42%   |
| Unknown    | 1         | 0.71%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 126       | 91.3%   |
| Wayland | 11        | 7.97%   |
| Unknown | 1         | 0.72%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| GDM     | 128       | 94.12%  |
| SDDM    | 5         | 3.68%   |
| Unknown | 3         | 2.21%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 130       | 95.59%  |
| ru_RU   | 5         | 3.68%   |
| en_US   | 1         | 0.74%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 106       | 76.81%  |
| BIOS | 32        | 23.19%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 132       | 97.06%  |
| Btrfs   | 3         | 2.21%   |
| Unknown | 1         | 0.74%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 108       | 78.83%  |
| MBR     | 26        | 18.98%  |
| Unknown | 3         | 2.19%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 122       | 89.05%  |
| Yes       | 15        | 10.95%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 106       | 77.37%  |
| Yes       | 31        | 22.63%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo              | 32        | 23.7%   |
| Gigabyte Technology | 26        | 19.26%  |
| ASUSTek Computer    | 15        | 11.11%  |
| ASRock              | 9         | 6.67%   |
| Hewlett-Packard     | 7         | 5.19%   |
| Aquarius            | 7         | 5.19%   |
| MSI                 | 6         | 4.44%   |
| ICL                 | 4         | 2.96%   |
| Digma               | 4         | 2.96%   |
| DEPO Computers      | 4         | 2.96%   |
| HUAWEI              | 3         | 2.22%   |
| Acer                | 3         | 2.22%   |
| IP3 Technology      | 2         | 1.48%   |
| YADRO               | 1         | 0.74%   |
| THUNDEROBOT         | 1         | 0.74%   |
| RDW                 | 1         | 0.74%   |
| Pegatron            | 1         | 0.74%   |
| mtech               | 1         | 0.74%   |
| Kraftway            | 1         | 0.74%   |
| iRU                 | 1         | 0.74%   |
| Intel               | 1         | 0.74%   |
| HONOR               | 1         | 0.74%   |
| ECS                 | 1         | 0.74%   |
| Dell                | 1         | 0.74%   |
| 3Logic Group        | 1         | 0.74%   |
| Unknown             | 1         | 0.74%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Lenovo V15-IWL 81YE                      | 17        | 12.59%  |
| Gigabyte B365M DS3H                      | 4         | 2.96%   |
| DEPO Computers DPH310T                   | 4         | 2.96%   |
| MSI MS-7D14                              | 2         | 1.48%   |
| Lenovo ThinkBook 15 G3 ACL 21A4          | 2         | 1.48%   |
| IP3 ACN30                                | 2         | 1.48%   |
| ICL RAYbook Si1512                       | 2         | 1.48%   |
| Gigabyte H110M-S2                        | 2         | 1.48%   |
| Gigabyte B560M DS3H                      | 2         | 1.48%   |
| Gigabyte B550 AORUS ELITE V2             | 2         | 1.48%   |
| ASUS PC                                  | 2         | 1.48%   |
| Unknown                                  | 2         | 1.48%   |
| YADRO VEGMAN S220 Server                 | 1         | 0.74%   |
| THUNDEROBOT 911AirD                      | 1         | 0.74%   |
| RDW RDW-MB-B450M V.1                     | 1         | 0.74%   |
| Pegatron A35                             | 1         | 0.74%   |
| mtech MTL1578                            | 1         | 0.74%   |
| MSI MS-7D35                              | 1         | 0.74%   |
| MSI MS-7636                              | 1         | 0.74%   |
| MSI FX610                                | 1         | 0.74%   |
| MSI Compaq dx2300 Microtower             | 1         | 0.74%   |
| Lenovo V50s-07IMB 11EF0011RU             | 1         | 0.74%   |
| Lenovo ThinkCentre M75q Gen 2 11JNS02N00 | 1         | 0.74%   |
| Lenovo ThinkCentre M720q 10T8S08X00      | 1         | 0.74%   |
| Lenovo ThinkCentre M720q 10T7S18500      | 1         | 0.74%   |
| Lenovo ThinkCentre M720q 10T7004KRU      | 1         | 0.74%   |
| Lenovo ThinkCentre M70q 11DT003QRU       | 1         | 0.74%   |
| Lenovo ThinkBook 14-IIL 20SL             | 1         | 0.74%   |
| Lenovo IdeaPad L340-15IWL 81LG           | 1         | 0.74%   |
| Lenovo IdeaPad L340-15API 81LW           | 1         | 0.74%   |
| Lenovo IdeaPad 5 Pro 14ACN6 82L7         | 1         | 0.74%   |
| Lenovo IdeaPad 5 15ARE05 81YQ            | 1         | 0.74%   |
| Lenovo IdeaPad 3 15ITL05 81X8            | 1         | 0.74%   |
| Lenovo IdeaCentre 3 07ADA05 90MV0059RS   | 1         | 0.74%   |
| Kraftway ACCORD                          | 1         | 0.74%   |
| iRU P11AP                                | 1         | 0.74%   |
| Intel S2600WFT                           | 1         | 0.74%   |
| ICL RAYbook Si1514                       | 1         | 0.74%   |
| HUAWEI NBLK-WAX9X                        | 1         | 0.74%   |
| HUAWEI BOHL-WXX9                         | 1         | 0.74%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo V15-IWL         | 17        | 12.59%  |
| Lenovo ThinkCentre     | 5         | 3.7%    |
| Lenovo IdeaPad         | 5         | 3.7%    |
| Gigabyte B365M         | 5         | 3.7%    |
| DEPO Computers DPH310T | 4         | 2.96%   |
| Lenovo ThinkBook       | 3         | 2.22%   |
| ICL RAYbook            | 3         | 2.22%   |
| Gigabyte B560M         | 3         | 2.22%   |
| Digma EVE              | 3         | 2.22%   |
| MSI MS-7D14            | 2         | 1.48%   |
| IP3 ACN30              | 2         | 1.48%   |
| HP Laptop              | 2         | 1.48%   |
| Gigabyte H110M-S2      | 2         | 1.48%   |
| Gigabyte B550          | 2         | 1.48%   |
| ASUS PRIME             | 2         | 1.48%   |
| ASUS PC                | 2         | 1.48%   |
| Aquarius Pro           | 2         | 1.48%   |
| Acer Aspire            | 2         | 1.48%   |
| Unknown                | 2         | 1.48%   |
| YADRO VEGMAN           | 1         | 0.74%   |
| THUNDEROBOT 911AirD    | 1         | 0.74%   |
| RDW RDW-MB-B450M       | 1         | 0.74%   |
| Pegatron A35           | 1         | 0.74%   |
| mtech MTL1578          | 1         | 0.74%   |
| MSI MS-7D35            | 1         | 0.74%   |
| MSI MS-7636            | 1         | 0.74%   |
| MSI FX610              | 1         | 0.74%   |
| MSI Compaq             | 1         | 0.74%   |
| Lenovo V50s-07IMB      | 1         | 0.74%   |
| Lenovo IdeaCentre      | 1         | 0.74%   |
| Kraftway ACCORD        | 1         | 0.74%   |
| iRU P11AP              | 1         | 0.74%   |
| Intel S2600WFT         | 1         | 0.74%   |
| HUAWEI NBLK-WAX9X      | 1         | 0.74%   |
| HUAWEI BOHL-WXX9       | 1         | 0.74%   |
| HUAWEI BOD-WXX9        | 1         | 0.74%   |
| HONOR NBR-WAX9         | 1         | 0.74%   |
| HP Z400                | 1         | 0.74%   |
| HP ProOne              | 1         | 0.74%   |
| HP Pavilion            | 1         | 0.74%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2019 | 37        | 27.41%  |
| 2021 | 36        | 26.67%  |
| 2020 | 21        | 15.56%  |
| 2022 | 8         | 5.93%   |
| 2016 | 6         | 4.44%   |
| 2012 | 6         | 4.44%   |
| 2018 | 5         | 3.7%    |
| 2010 | 4         | 2.96%   |
| 2011 | 3         | 2.22%   |
| 2017 | 2         | 1.48%   |
| 2009 | 2         | 1.48%   |
| 2007 | 2         | 1.48%   |
| 2015 | 1         | 0.74%   |
| 2014 | 1         | 0.74%   |
| 2013 | 1         | 0.74%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name       | Computers | Percent |
|------------|-----------|---------|
| Desktop    | 66        | 48.89%  |
| Notebook   | 57        | 42.22%  |
| Mini pc    | 6         | 4.44%   |
| All in one | 3         | 2.22%   |
| Server     | 2         | 1.48%   |
| Tablet     | 1         | 0.74%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 135       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 135       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 69        | 51.11%  |
| 16.01-24.0      | 25        | 18.52%  |
| 8.01-16.0       | 17        | 12.59%  |
| 3.01-4.0        | 15        | 11.11%  |
| More than 256.0 | 2         | 1.48%   |
| 32.01-64.0      | 2         | 1.48%   |
| 24.01-32.0      | 2         | 1.48%   |
| 2.01-3.0        | 1         | 0.74%   |
| 1.01-2.0        | 1         | 0.74%   |
| Unknown         | 1         | 0.74%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 70        | 48.95%  |
| 2.01-3.0  | 20        | 13.99%  |
| 0.51-1.0  | 19        | 13.29%  |
| 3.01-4.0  | 18        | 12.59%  |
| 4.01-8.0  | 13        | 9.09%   |
| 8.01-16.0 | 2         | 1.4%    |
| Unknown   | 1         | 0.7%    |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 99        | 71.74%  |
| 2      | 27        | 19.57%  |
| 3      | 5         | 3.62%   |
| 4      | 3         | 2.17%   |
| 12     | 1         | 0.72%   |
| 7      | 1         | 0.72%   |
| 5      | 1         | 0.72%   |
| 0      | 1         | 0.72%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 104       | 77.04%  |
| Yes       | 31        | 22.96%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 106       | 78.52%  |
| No        | 29        | 21.48%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 58.39%  |
| No        | 57        | 41.61%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 71        | 52.59%  |
| Yes       | 64        | 47.41%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Russia  | 134       | 99.26%  |
| Ukraine | 1         | 0.74%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Murom            | 30        | 22.06%  |
| Salekhard        | 29        | 21.32%  |
| Moscow           | 24        | 17.65%  |
| Yekaterinburg    | 5         | 3.68%   |
| Ryazan           | 3         | 2.21%   |
| Kursk            | 3         | 2.21%   |
| Krasnodar        | 3         | 2.21%   |
| Kaluga           | 3         | 2.21%   |
| Vladimir         | 2         | 1.47%   |
| Ulyanovsk        | 2         | 1.47%   |
| St Petersburg    | 2         | 1.47%   |
| Novy Urengoy     | 2         | 1.47%   |
| Novosibirsk      | 2         | 1.47%   |
| Krasnoyarsk      | 2         | 1.47%   |
| Khabarovsk       | 2         | 1.47%   |
| Balashikha       | 2         | 1.47%   |
| Yaroslavl        | 1         | 0.74%   |
| Tomsk            | 1         | 0.74%   |
| Surgut           | 1         | 0.74%   |
| Stavropol        | 1         | 0.74%   |
| Sevastopol       | 1         | 0.74%   |
| Saratov          | 1         | 0.74%   |
| Rostov-on-Don    | 1         | 0.74%   |
| Perm             | 1         | 0.74%   |
| Penza            | 1         | 0.74%   |
| Nizhniy Novgorod | 1         | 0.74%   |
| Labytnangi       | 1         | 0.74%   |
| Kovrov           | 1         | 0.74%   |
| Korsakov         | 1         | 0.74%   |
| Kol'chugino      | 1         | 0.74%   |
| Kirov            | 1         | 0.74%   |
| Kholmsk          | 1         | 0.74%   |
| Bryansk          | 1         | 0.74%   |
| Belgorod         | 1         | 0.74%   |
| Arzamas          | 1         | 0.74%   |
| Arkhangelsk      | 1         | 0.74%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                       | Computers | Drives | Percent |
|------------------------------|-----------|--------|---------|
| Samsung Electronics          | 32        | 42     | 18.08%  |
| Seagate                      | 25        | 38     | 14.12%  |
| WDC                          | 23        | 27     | 12.99%  |
| Toshiba                      | 13        | 15     | 7.34%   |
| A-DATA Technology            | 13        | 13     | 7.34%   |
| Kingston                     | 9         | 9      | 5.08%   |
| Foxline                      | 6         | 6      | 3.39%   |
| Apacer                       | 5         | 5      | 2.82%   |
| SK hynix                     | 4         | 4      | 2.26%   |
| SanDisk                      | 4         | 5      | 2.26%   |
| Phison                       | 3         | 3      | 1.69%   |
| Patriot                      | 3         | 3      | 1.69%   |
| Crucial                      | 3         | 5      | 1.69%   |
| Unknown                      | 3         | 4      | 1.69%   |
| Unknown                      | 2         | 2      | 1.13%   |
| Transcend                    | 2         | 2      | 1.13%   |
| Silicon Motion               | 2         | 2      | 1.13%   |
| Micron Technology            | 2         | 4      | 1.13%   |
| KIOXIA-EXCERIA               | 2         | 2      | 1.13%   |
| Hitachi                      | 2         | 2      | 1.13%   |
| HGST                         | 2         | 2      | 1.13%   |
| XPG                          | 1         | 1      | 0.56%   |
| UMIS                         | 1         | 1      | 0.56%   |
| Smartbuy                     | 1         | 1      | 0.56%   |
| Shenzhen Longsys Electronics | 1         | 1      | 0.56%   |
| LIO-ORG                      | 1         | 1      | 0.56%   |
| Lenovo                       | 1         | 8      | 0.56%   |
| KingSpec                     | 1         | 1      | 0.56%   |
| Kimtigo                      | 1         | 2      | 0.56%   |
| JMicron Technology           | 1         | 1      | 0.56%   |
| ITHOO                        | 1         | 1      | 0.56%   |
| Intel                        | 1         | 7      | 0.56%   |
| GOODRAM                      | 1         | 1      | 0.56%   |
| Gigabyte Technology          | 1         | 1      | 0.56%   |
| ExeGate                      | 1         | 1      | 0.56%   |
| Corsair                      | 1         | 1      | 0.56%   |
| China                        | 1         | 1      | 0.56%   |
| AMD                          | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Samsung MZALQ256HAJD-000L2 256GB       | 17        | 9.24%   |
| Seagate ST1000LM049-2GH172 1TB         | 5         | 2.72%   |
| Seagate ST1000DM010-2EP102 1TB         | 4         | 2.17%   |
| Apacer AS2280P4 256GB                  | 4         | 2.17%   |
| Toshiba HDWD110 1TB                    | 3         | 1.63%   |
| Seagate ST1000DM010-2DM162 1TB         | 3         | 1.63%   |
| SanDisk SD8SBAT256G1122 256GB SSD      | 3         | 1.63%   |
| Samsung SSD 860 EVO 250GB              | 3         | 1.63%   |
| Kingston SA400S37240G 240GB SSD        | 3         | 1.63%   |
| Foxline FLSSD256M80E13TCX5 256GB       | 3         | 1.63%   |
| Unknown                                | 3         | 1.63%   |
| WDC PC SN530 SDBPNPZ-512G-1114 512GB   | 2         | 1.09%   |
| Toshiba HDWD105 500GB                  | 2         | 1.09%   |
| SK hynix SKHynix_HFM256GD3HX015N 256GB | 2         | 1.09%   |
| Silicon Motion Wodposit NVMe SSD 256GB | 2         | 1.09%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 1.09%   |
| Seagate ST1000DM003-1SB10C 1TB         | 2         | 1.09%   |
| KIOXIA-EXCERIA SATA SSD 480GB          | 2         | 1.09%   |
| Kingston OM8PCP3512F-A02 512GB         | 2         | 1.09%   |
| Foxline FLSSD240X5SE 240GB             | 2         | 1.09%   |
| Crucial CT240BX500SSD1 240GB           | 2         | 1.09%   |
| A-DATA SU800 256GB SSD                 | 2         | 1.09%   |
| A-DATA SU650 240GB SSD                 | 2         | 1.09%   |
| A-DATA SU630 960GB SSD                 | 2         | 1.09%   |
| XPG GAMMIX S70 BLADE 2TB               | 1         | 0.54%   |
| WDC WDS500G2B0B-00YS70 500GB SSD       | 1         | 0.54%   |
| WDC WDS240G2G0A-00JH30 240GB SSD       | 1         | 0.54%   |
| WDC WD5000BPVT-55HXZT3 500GB           | 1         | 0.54%   |
| WDC WD5000AAKX-75U6AA0 500GB           | 1         | 0.54%   |
| WDC WD40PURZ-85TTDY0 4TB               | 1         | 0.54%   |
| WDC WD3200AAKX-001CA0 320GB            | 1         | 0.54%   |
| WDC WD30EFRX-68EUZN0 3TB               | 1         | 0.54%   |
| WDC WD20EFRX-68EUZN0 2TB               | 1         | 0.54%   |
| WDC WD20EARX-00PASB0 2TB               | 1         | 0.54%   |
| WDC WD15EARS-19MVWB0 1TB               | 1         | 0.54%   |
| WDC WD10SPZX-24Z10 1TB                 | 1         | 0.54%   |
| WDC WD10SPZX-22Z10T1 1TB               | 1         | 0.54%   |
| WDC WD10SPZX-00Z10T0 1TB               | 1         | 0.54%   |
| WDC WD10EZEX-22MFCA0 1TB               | 1         | 0.54%   |
| WDC WD10EZEX-00BBHA0 1TB               | 1         | 0.54%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 25        | 38     | 43.86%  |
| WDC                 | 14        | 18     | 24.56%  |
| Toshiba             | 10        | 12     | 17.54%  |
| Samsung Electronics | 2         | 3      | 3.51%   |
| Hitachi             | 2         | 2      | 3.51%   |
| HGST                | 2         | 2      | 3.51%   |
| LIO-ORG             | 1         | 1      | 1.75%   |
| Lenovo              | 1         | 8      | 1.75%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| A-DATA Technology   | 9         | 9      | 19.15%  |
| Samsung Electronics | 6         | 10     | 12.77%  |
| Kingston            | 5         | 5      | 10.64%  |
| SanDisk             | 4         | 5      | 8.51%   |
| Foxline             | 3         | 3      | 6.38%   |
| Crucial             | 3         | 5      | 6.38%   |
| WDC                 | 2         | 2      | 4.26%   |
| Transcend           | 2         | 2      | 4.26%   |
| Patriot             | 2         | 2      | 4.26%   |
| KIOXIA-EXCERIA      | 2         | 2      | 4.26%   |
| Toshiba             | 1         | 1      | 2.13%   |
| Smartbuy            | 1         | 1      | 2.13%   |
| Micron Technology   | 1         | 1      | 2.13%   |
| KingSpec            | 1         | 1      | 2.13%   |
| Intel               | 1         | 7      | 2.13%   |
| GOODRAM             | 1         | 1      | 2.13%   |
| ExeGate             | 1         | 1      | 2.13%   |
| China               | 1         | 1      | 2.13%   |
| Apacer              | 1         | 1      | 2.13%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 65        | 75     | 38.46%  |
| HDD     | 52        | 84     | 30.77%  |
| SSD     | 46        | 60     | 27.22%  |
| MMC     | 5         | 6      | 2.96%   |
| Unknown | 1         | 1      | 0.59%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 82        | 144    | 53.25%  |
| NVMe | 65        | 74     | 42.21%  |
| MMC  | 5         | 6      | 3.25%   |
| SAS  | 2         | 2      | 1.3%    |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 53        | 66     | 52.48%  |
| 0.51-1.0   | 38        | 54     | 37.62%  |
| 1.01-2.0   | 6         | 14     | 5.94%   |
| 3.01-4.0   | 2         | 6      | 1.98%   |
| 2.01-3.0   | 1         | 1      | 0.99%   |
| 4.01-10.0  | 1         | 3      | 0.99%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 61        | 44.2%   |
| 251-500        | 25        | 18.12%  |
| 501-1000       | 25        | 18.12%  |
| 51-100         | 10        | 7.25%   |
| 1001-2000      | 7         | 5.07%   |
| 21-50          | 3         | 2.17%   |
| 2001-3000      | 3         | 2.17%   |
| More than 3000 | 2         | 1.45%   |
| 1-20           | 1         | 0.72%   |
| Unknown        | 1         | 0.72%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 94        | 66.2%   |
| 21-50          | 15        | 10.56%  |
| 501-1000       | 9         | 6.34%   |
| 51-100         | 8         | 5.63%   |
| 101-250        | 7         | 4.93%   |
| 251-500        | 5         | 3.52%   |
| 1001-2000      | 2         | 1.41%   |
| More than 3000 | 1         | 0.7%    |
| Unknown        | 1         | 0.7%    |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                               | Computers | Drives | Percent |
|-------------------------------------|-----------|--------|---------|
| WDC WDS240G2G0A-00JH30 240GB SSD    | 1         | 1      | 8.33%   |
| WDC WD3200AAKX-001CA0 320GB         | 1         | 1      | 8.33%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 1      | 8.33%   |
| WDC WD10EARS-00Y5B1 1TB             | 1         | 1      | 8.33%   |
| Toshiba MQ01ABF050 500GB            | 1         | 3      | 8.33%   |
| Toshiba MK5059GSXP 500GB            | 1         | 1      | 8.33%   |
| Seagate ST750LM022 HN-M750MBB 752GB | 1         | 1      | 8.33%   |
| Seagate ST3250823AS 250GB           | 1         | 1      | 8.33%   |
| Seagate ST1000DM010-2EP102 1TB      | 1         | 4      | 8.33%   |
| Hitachi HDS5C1050CLA382 500GB       | 1         | 1      | 8.33%   |
| HGST HTS721010A9E630 1TB            | 1         | 1      | 8.33%   |
| A-DATA Technology SU800 256GB SSD   | 1         | 1      | 8.33%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor            | Computers | Drives | Percent |
|-------------------|-----------|--------|---------|
| WDC               | 4         | 4      | 33.33%  |
| Seagate           | 3         | 6      | 25%     |
| Toshiba           | 2         | 4      | 16.67%  |
| Hitachi           | 1         | 1      | 8.33%   |
| HGST              | 1         | 1      | 8.33%   |
| A-DATA Technology | 1         | 1      | 8.33%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 3         | 3      | 30%     |
| Seagate | 3         | 6      | 30%     |
| Toshiba | 2         | 4      | 20%     |
| Hitachi | 1         | 1      | 10%     |
| HGST    | 1         | 1      | 10%     |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 9         | 15     | 81.82%  |
| SSD  | 2         | 2      | 18.18%  |

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
| Works    | 123       | 195    | 86.01%  |
| Malfunc  | 11        | 17     | 7.69%   |
| Detected | 9         | 14     | 6.29%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Intel                        | 107       | 54.59%  |
| Samsung Electronics          | 25        | 12.76%  |
| AMD                          | 18        | 9.18%   |
| Phison Electronics           | 12        | 6.12%   |
| SanDisk                      | 7         | 3.57%   |
| SK hynix                     | 4         | 2.04%   |
| Kingston Technology Company  | 4         | 2.04%   |
| Silicon Motion               | 3         | 1.53%   |
| Realtek Semiconductor        | 3         | 1.53%   |
| Toshiba America Info Systems | 2         | 1.02%   |
| Nvidia                       | 2         | 1.02%   |
| ADATA Technology             | 2         | 1.02%   |
| Union Memory (Shenzhen)      | 1         | 0.51%   |
| Shenzhen Longsys Electronics | 1         | 0.51%   |
| Micron Technology            | 1         | 0.51%   |
| MAXIO Technology (Hangzhou)  | 1         | 0.51%   |
| LSI Logic / Symbios Logic    | 1         | 0.51%   |
| JMicron Technology           | 1         | 0.51%   |
| Unknown                      | 1         | 0.51%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP SATA Controller [AHCI Mode]                              | 25        | 11.68%  |
| Samsung NVMe SSD Controller 980                                                | 23        | 10.75%  |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 19        | 8.88%   |
| Phison PS5013 E13 NVMe Controller                                              | 10        | 4.67%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 10        | 4.67%   |
| AMD FCH SATA Controller [AHCI mode]                                            | 9         | 4.21%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 8         | 3.74%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 8         | 3.74%   |
| Intel Tiger Lake-LP SATA Controller                                            | 5         | 2.34%   |
| AMD 500 Series Chipset SATA Controller                                         | 5         | 2.34%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 4         | 1.87%   |
| Kingston Company Company Non-Volatile memory controller                        | 4         | 1.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller       | 4         | 1.87%   |
| AMD 400 Series Chipset SATA Controller                                         | 4         | 1.87%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 3         | 1.4%    |
| Realtek Realtek Non-Volatile memory controller                                 | 3         | 1.4%    |
| Intel Volume Management Device NVMe RAID Controller                            | 3         | 1.4%    |
| Intel Comet Lake SATA AHCI Controller                                          | 3         | 1.4%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 3         | 1.4%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                           | 2         | 0.93%   |
| SK hynix Gold P31 SSD                                                          | 2         | 0.93%   |
| SanDisk Non-Volatile memory controller                                         | 2         | 0.93%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 2         | 0.93%   |
| Phison E16 PCIe4 NVMe Controller                                               | 2         | 0.93%   |
| Nvidia MCP61 SATA Controller                                                   | 2         | 0.93%   |
| Nvidia MCP61 IDE                                                               | 2         | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 2         | 0.93%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 2         | 0.93%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 2         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 2         | 0.93%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 2         | 0.93%   |
| ADATA A Non-Volatile memory controller                                         | 2         | 0.93%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                         | 1         | 0.47%   |
| SK hynix BC511                                                                 | 1         | 0.47%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 1         | 0.47%   |
| Shenzhen Longsys Electronics Non-Volatile memory controller                    | 1         | 0.47%   |
| SanDisk PC SN520 NVMe SSD                                                      | 1         | 0.47%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 1         | 0.47%   |
| Micron Non-Volatile memory controller                                          | 1         | 0.47%   |
| MAXIO (Hangzhou) NVMe SSD Controller MAP1202                                   | 1         | 0.47%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 117       | 58.79%  |
| NVMe | 65        | 32.66%  |
| IDE  | 10        | 5.03%   |
| RAID | 6         | 3.02%   |
| SAS  | 1         | 0.5%    |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 108       | 80%     |
| AMD    | 27        | 20%     |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8265U CPU @ 1.60GHz             | 18        | 13.33%  |
| Intel Core i5-9400 CPU @ 2.90GHz              | 10        | 7.41%   |
| Intel Core i3-10100 CPU @ 3.60GHz             | 10        | 7.41%   |
| Intel Core i5-8279U CPU @ 2.40GHz             | 5         | 3.7%    |
| Intel Core i5-3470 CPU @ 3.20GHz              | 3         | 2.22%   |
| Intel Celeron CPU N3350 @ 1.10GHz             | 3         | 2.22%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 3         | 2.22%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 2.22%   |
| Intel Pentium CPU G4500 @ 3.50GHz             | 2         | 1.48%   |
| Intel Core i5-8259U CPU @ 2.30GHz             | 2         | 1.48%   |
| Intel Core i5-10500 CPU @ 3.10GHz             | 2         | 1.48%   |
| Intel Core i5-10400 CPU @ 2.90GHz             | 2         | 1.48%   |
| Intel Core i3-8100T CPU @ 3.10GHz             | 2         | 1.48%   |
| Intel Core i3-6100 CPU @ 3.70GHz              | 2         | 1.48%   |
| Intel Celeron J4125 CPU @ 2.00GHz             | 2         | 1.48%   |
| AMD Ryzen 7 PRO 4750G with Radeon Graphics    | 2         | 1.48%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 2         | 1.48%   |
| AMD Ryzen 3 5400U with Radeon Graphics        | 2         | 1.48%   |
| AMD Ryzen 3 5300U with Radeon Graphics        | 2         | 1.48%   |
| AMD FX-4100 Quad-Core Processor               | 2         | 1.48%   |
| Intel Xeon Silver 4214 CPU @ 2.20GHz          | 1         | 0.74%   |
| Intel Xeon Gold 5220 CPU @ 2.20GHz            | 1         | 0.74%   |
| Intel Xeon CPU W3670 @ 3.20GHz                | 1         | 0.74%   |
| Intel Pentium Gold G6400 CPU @ 4.00GHz        | 1         | 0.74%   |
| Intel Pentium Gold G5400 CPU @ 3.70GHz        | 1         | 0.74%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.74%   |
| Intel Pentium CPU J3710 @ 1.60GHz             | 1         | 0.74%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.74%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 1         | 0.74%   |
| Intel Core i7-2600 CPU @ 3.40GHz              | 1         | 0.74%   |
| Intel Core i7-10700 CPU @ 2.90GHz             | 1         | 0.74%   |
| Intel Core i7 CPU 950 @ 3.07GHz               | 1         | 0.74%   |
| Intel Core i5-9400F CPU @ 2.90GHz             | 1         | 0.74%   |
| Intel Core i5-8500T CPU @ 2.10GHz             | 1         | 0.74%   |
| Intel Core i5-8400T CPU @ 1.70GHz             | 1         | 0.74%   |
| Intel Core i5-7300HQ CPU @ 2.50GHz            | 1         | 0.74%   |
| Intel Core i5-6500 CPU @ 3.20GHz              | 1         | 0.74%   |
| Intel Core i5-4590 CPU @ 3.30GHz              | 1         | 0.74%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 1         | 0.74%   |
| Intel Core i5-2450M CPU @ 2.50GHz             | 1         | 0.74%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model              | Computers | Percent |
|--------------------|-----------|---------|
| Intel Core i5      | 54        | 40%     |
| Intel Core i3      | 22        | 16.3%   |
| AMD Ryzen 5        | 10        | 7.41%   |
| Other              | 9         | 6.67%   |
| Intel Celeron      | 7         | 5.19%   |
| Intel Pentium      | 6         | 4.44%   |
| AMD Ryzen 3        | 6         | 4.44%   |
| Intel Core i7      | 3         | 2.22%   |
| AMD FX             | 3         | 2.22%   |
| Intel Pentium Gold | 2         | 1.48%   |
| AMD Ryzen 7 PRO    | 2         | 1.48%   |
| AMD Ryzen 7        | 2         | 1.48%   |
| Intel Xeon Silver  | 1         | 0.74%   |
| Intel Xeon Gold    | 1         | 0.74%   |
| Intel Xeon         | 1         | 0.74%   |
| Intel Core 2 Duo   | 1         | 0.74%   |
| Intel Core 2       | 1         | 0.74%   |
| AMD Ryzen 5 PRO    | 1         | 0.74%   |
| AMD Ryzen 3 PRO    | 1         | 0.74%   |
| AMD Phenom II      | 1         | 0.74%   |
| AMD Athlon II X2   | 1         | 0.74%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 71        | 52.59%  |
| 6      | 30        | 22.22%  |
| 2      | 26        | 19.26%  |
| 8      | 4         | 2.96%   |
| 3      | 2         | 1.48%   |
| 36     | 1         | 0.74%   |
| 24     | 1         | 0.74%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 133       | 98.52%  |
| 2      | 2         | 1.48%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 91        | 67.41%  |
| 1      | 44        | 32.59%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 134       | 99.26%  |
| Unknown        | 1         | 0.74%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| 0xa0653    | 19        | 13.87%  |
| 0x806ec    | 19        | 13.87%  |
| 0x906ed    | 8         | 5.84%   |
| 0x806ea    | 7         | 5.11%   |
| 0x506e3    | 7         | 5.11%   |
| 0x906ea    | 6         | 4.38%   |
| 0x806c1    | 6         | 4.38%   |
| 0x08600106 | 5         | 3.65%   |
| 0x906eb    | 4         | 2.92%   |
| 0x306a9    | 4         | 2.92%   |
| 0x0a50000c | 4         | 2.92%   |
| 0x206a7    | 3         | 2.19%   |
| 0x0a50000d | 3         | 2.19%   |
| 0x08108109 | 3         | 2.19%   |
| 0x906e9    | 2         | 1.46%   |
| 0x806d1    | 2         | 1.46%   |
| 0x706a8    | 2         | 1.46%   |
| 0x506ca    | 2         | 1.46%   |
| 0x506c9    | 2         | 1.46%   |
| 0x50657    | 2         | 1.46%   |
| 0x306c3    | 2         | 1.46%   |
| 0x08608103 | 2         | 1.46%   |
| 0x08108102 | 2         | 1.46%   |
| 0x0600063e | 2         | 1.46%   |
| 0xa0671    | 1         | 0.73%   |
| 0xa0655    | 1         | 0.73%   |
| 0xa0654    | 1         | 0.73%   |
| 0x706e5    | 1         | 0.73%   |
| 0x6fa      | 1         | 0.73%   |
| 0x6f6      | 1         | 0.73%   |
| 0x406e3    | 1         | 0.73%   |
| 0x406c4    | 1         | 0.73%   |
| 0x206c2    | 1         | 0.73%   |
| 0x20652    | 1         | 0.73%   |
| 0x106a5    | 1         | 0.73%   |
| 0x0a201016 | 1         | 0.73%   |
| 0x08701021 | 1         | 0.73%   |
| 0x08600104 | 1         | 0.73%   |
| 0x08101016 | 1         | 0.73%   |
| 0x06000852 | 1         | 0.73%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KabyLake      | 46        | 34.07%  |
| CometLake     | 21        | 15.56%  |
| Skylake       | 10        | 7.41%   |
| Zen 3         | 7         | 5.19%   |
| Zen 2         | 7         | 5.19%   |
| TigerLake     | 6         | 4.44%   |
| Zen+          | 5         | 3.7%    |
| IvyBridge     | 4         | 2.96%   |
| Goldmont      | 4         | 2.96%   |
| SandyBridge   | 3         | 2.22%   |
| IceLake       | 3         | 2.22%   |
| Unknown       | 3         | 2.22%   |
| Westmere      | 2         | 1.48%   |
| K10           | 2         | 1.48%   |
| Haswell       | 2         | 1.48%   |
| Goldmont plus | 2         | 1.48%   |
| Core          | 2         | 1.48%   |
| Bulldozer     | 2         | 1.48%   |
| Zen           | 1         | 0.74%   |
| Silvermont    | 1         | 0.74%   |
| Piledriver    | 1         | 0.74%   |
| Nehalem       | 1         | 0.74%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor            | Computers | Percent |
|-------------------|-----------|---------|
| Intel             | 98        | 67.12%  |
| AMD               | 28        | 19.18%  |
| Nvidia            | 18        | 12.33%  |
| ASPEED Technology | 2         | 1.37%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                  | 18        | 12.08%  |
| Intel CometLake-S GT2 [UHD Graphics 630]                                    | 17        | 11.41%  |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                   | 16        | 10.74%  |
| Intel CoffeeLake-U GT3e [Iris Plus Graphics 655]                            | 7         | 4.7%    |
| AMD Renoir                                                                  | 6         | 4.03%   |
| AMD Cezanne                                                                 | 6         | 4.03%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 5         | 3.36%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 4         | 2.68%   |
| Intel HD Graphics 530                                                       | 4         | 2.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 3         | 2.01%   |
| Intel HD Graphics 500                                                       | 3         | 2.01%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 3         | 2.01%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 2         | 1.34%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 2         | 1.34%   |
| Intel Tiger Lake UHD Graphics                                               | 2         | 1.34%   |
| Intel GeminiLake [UHD Graphics 600]                                         | 2         | 1.34%   |
| Intel CometLake-S GT1 [UHD Graphics 610]                                    | 2         | 1.34%   |
| ASPEED Technology ASPEED Graphics Family                                    | 2         | 1.34%   |
| AMD Lucienne                                                                | 2         | 1.34%   |
| Nvidia TU116 [GeForce GTX 1650]                                             | 1         | 0.67%   |
| Nvidia TU104 [GeForce RTX 2060]                                             | 1         | 0.67%   |
| Nvidia NV43 [GeForce 6600 GT]                                               | 1         | 0.67%   |
| Nvidia GP108 [GeForce GT 1030]                                              | 1         | 0.67%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 1         | 0.67%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                         | 1         | 0.67%   |
| Nvidia GM108M [GeForce MX110]                                               | 1         | 0.67%   |
| Nvidia GM108M [GeForce 920MX]                                               | 1         | 0.67%   |
| Nvidia GK208B [GeForce GT 710]                                              | 1         | 0.67%   |
| Nvidia GK104 [GeForce GTX 760]                                              | 1         | 0.67%   |
| Nvidia GF119M [GeForce 610M]                                                | 1         | 0.67%   |
| Nvidia GF114 [GeForce GTX 560 Ti]                                           | 1         | 0.67%   |
| Nvidia GF108M [GeForce GT 620M/630M/635M/640M LE]                           | 1         | 0.67%   |
| Nvidia GF108 [GeForce GT 620]                                               | 1         | 0.67%   |
| Nvidia GA107M [GeForce RTX 3050 Mobile]                                     | 1         | 0.67%   |
| Nvidia G94GL [Quadro FX 1800]                                               | 1         | 0.67%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 1         | 0.67%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 1         | 0.67%   |
| Intel RocketLake-S GT1 [UHD Graphics 730]                                   | 1         | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)         | 1         | 0.67%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)           | 1         | 0.67%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 88        | 65.19%  |
| 1 x AMD        | 24        | 17.78%  |
| 1 x Nvidia     | 9         | 6.67%   |
| Intel + Nvidia | 8         | 5.93%   |
| 2 x AMD        | 2         | 1.48%   |
| 1 x ASPEED     | 2         | 1.48%   |
| Intel + AMD    | 1         | 0.74%   |
| AMD + Nvidia   | 1         | 0.74%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 116       | 84.67%  |
| Unknown     | 17        | 12.41%  |
| Proprietary | 4         | 2.92%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 97        | 70.8%   |
| 1.01-2.0   | 16        | 11.68%  |
| 0.01-0.5   | 9         | 6.57%   |
| 3.01-4.0   | 7         | 5.11%   |
| 0.51-1.0   | 7         | 5.11%   |
| 2.01-3.0   | 1         | 0.73%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| BOE                  | 31        | 23.31%  |
| Samsung Electronics  | 14        | 10.53%  |
| Philips              | 14        | 10.53%  |
| ViewSonic            | 11        | 8.27%   |
| Acer                 | 8         | 6.02%   |
| Chimei Innolux       | 7         | 5.26%   |
| BenQ                 | 7         | 5.26%   |
| LG Display           | 6         | 4.51%   |
| AU Optronics         | 4         | 3.01%   |
| AOC                  | 4         | 3.01%   |
| PANDA                | 3         | 2.26%   |
| Ancor Communications | 3         | 2.26%   |
| SGT                  | 2         | 1.5%    |
| HUAWEI               | 2         | 1.5%    |
| Hewlett-Packard      | 2         | 1.5%    |
| Goldstar             | 2         | 1.5%    |
| Dell                 | 2         | 1.5%    |
| XSP                  | 1         | 0.75%   |
| WYT                  | 1         | 0.75%   |
| Toshiba              | 1         | 0.75%   |
| Sony                 | 1         | 0.75%   |
| RGT                  | 1         | 0.75%   |
| Lenovo               | 1         | 0.75%   |
| ITE                  | 1         | 0.75%   |
| Iiyama               | 1         | 0.75%   |
| DOY                  | 1         | 0.75%   |
| CHR                  | 1         | 0.75%   |
| ASUSTek Computer     | 1         | 0.75%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                   | 17        | 12.59%  |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch                 | 6         | 4.44%   |
| BOE LCD Monitor BOE09C5 1920x1080 341x192mm 15.4-inch                   | 5         | 3.7%    |
| ViewSonic VA2719-2K VSC6B34 2560x1440 597x336mm 27.0-inch               | 4         | 2.96%   |
| Philips PHL 240V5 PHLC10A 1920x1080 530x300mm 24.0-inch                 | 3         | 2.22%   |
| Chimei Innolux LCD Monitor CMN151E 1920x1080 344x193mm 15.5-inch        | 3         | 2.22%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                   | 3         | 2.22%   |
| ViewSonic VA2465 SERIES VSCB730 1920x1080 521x293mm 23.5-inch           | 2         | 1.48%   |
| ViewSonic VA2407 Series VSC8C31 1920x1080 521x293mm 23.5-inch           | 2         | 1.48%   |
| SGT XY238 SGT2386 1920x1080 530x290mm 23.8-inch                         | 2         | 1.48%   |
| Samsung Electronics S24B300 SAM08B3 1920x1080 521x293mm 23.5-inch       | 2         | 1.48%   |
| Samsung Electronics C27R50x SAM0F9D 1920x1080 598x336mm 27.0-inch       | 2         | 1.48%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch        | 2         | 1.48%   |
| BOE LCD Monitor BOE0877 1920x1080 309x173mm 13.9-inch                   | 2         | 1.48%   |
| BenQ FP93E BNQ76D6 1280x1024 376x301mm 19.0-inch                        | 2         | 1.48%   |
| AU Optronics LCD Monitor AUO28ED 1920x1080 344x193mm 15.5-inch          | 2         | 1.48%   |
| AOC 2470W AOC2470 1920x1080 521x293mm 23.5-inch                         | 2         | 1.48%   |
| XSP Digital XSP2380 1920x1080 520x310mm 23.8-inch                       | 1         | 0.74%   |
| WYT MNT-ANALOG WYT0323 1280x1024 330x270mm 16.8-inch                    | 1         | 0.74%   |
| ViewSonic VX510 VSC6419 1024x768 304x228mm 15.0-inch                    | 1         | 0.74%   |
| ViewSonic VX2250 SERIES VSCCB25 1920x1080 477x268mm 21.5-inch           | 1         | 0.74%   |
| ViewSonic PJ VSC9B34 1920x1080                                          | 1         | 0.74%   |
| Toshiba LCD Monitor LCD58EB 1280x800 261x163mm 12.1-inch                | 1         | 0.74%   |
| Sony SDM-S73 SNY2770 1280x1024 359x287mm 18.1-inch                      | 1         | 0.74%   |
| Samsung Electronics SA300/SA350 SAM0795 1920x1080 521x293mm 23.5-inch   | 1         | 0.74%   |
| Samsung Electronics S24F350 SAM0D21 1920x1080 521x293mm 23.5-inch       | 1         | 0.74%   |
| Samsung Electronics S24D300 SAM0B42 1920x1080 531x299mm 24.0-inch       | 1         | 0.74%   |
| Samsung Electronics S24B300 SAM08B4 1920x1080 521x293mm 23.5-inch       | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC5541 1366x768 344x193mm 15.5-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC315A 1366x768 344x194mm 15.5-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SEC314F 1600x900 382x215mm 17.3-inch    | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM71B4 3840x2160 1872x1053mm 84.6-inch | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM7085 1920x1200 698x392mm 31.5-inch   | 1         | 0.74%   |
| Samsung Electronics LCD Monitor SAM7016 3840x2160 950x540mm 43.0-inch   | 1         | 0.74%   |
| Samsung Electronics LC32G5xT SAM7088 2560x1440 698x393mm 31.5-inch      | 1         | 0.74%   |
| RGT LCD Monitor RGT1352 1920x1080 480x270mm 21.7-inch                   | 1         | 0.74%   |
| Philips PHL 246V5 PHLC0C5 1920x1080 531x299mm 24.0-inch                 | 1         | 0.74%   |
| Philips PHL 241B8Q PHL0929 1920x1080 527x296mm 23.8-inch                | 1         | 0.74%   |
| Philips LCD Monitor PHLC081 1920x1080 480x270mm 21.7-inch               | 1         | 0.74%   |
| Philips 227E4Q PHLC0A9 1920x1080 477x268mm 21.5-inch                    | 1         | 0.74%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution        | Computers | Percent |
|-------------------|-----------|---------|
| 1920x1080 (FHD)   | 96        | 76.8%   |
| 2560x1440 (QHD)   | 6         | 4.8%    |
| 1280x1024 (SXGA)  | 5         | 4%      |
| 1366x768 (WXGA)   | 4         | 3.2%    |
| 3840x2160 (4K)    | 3         | 2.4%    |
| 1600x900 (HD+)    | 3         | 2.4%    |
| 1920x1200 (WUXGA) | 2         | 1.6%    |
| 3440x1440         | 1         | 0.8%    |
| 2240x1400         | 1         | 0.8%    |
| 1600x1200         | 1         | 0.8%    |
| 1440x900 (WXGA+)  | 1         | 0.8%    |
| 1280x800 (WXGA)   | 1         | 0.8%    |
| 1024x768 (XGA)    | 1         | 0.8%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 46        | 34.85%  |
| 24      | 19        | 14.39%  |
| 23      | 18        | 13.64%  |
| 21      | 12        | 9.09%   |
| 27      | 10        | 7.58%   |
| 19      | 4         | 3.03%   |
| 20      | 3         | 2.27%   |
| 17      | 3         | 2.27%   |
| 13      | 3         | 2.27%   |
| 84      | 2         | 1.52%   |
| 31      | 2         | 1.52%   |
| 14      | 2         | 1.52%   |
| 34      | 1         | 0.76%   |
| 32      | 1         | 0.76%   |
| 25      | 1         | 0.76%   |
| 18      | 1         | 0.76%   |
| 16      | 1         | 0.76%   |
| 12      | 1         | 0.76%   |
| 11      | 1         | 0.76%   |
| Unknown | 1         | 0.76%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 40.94%  |
| 501-600     | 43        | 33.86%  |
| 401-500     | 16        | 12.6%   |
| 351-400     | 7         | 5.51%   |
| 701-800     | 2         | 1.57%   |
| 601-700     | 2         | 1.57%   |
| 201-300     | 2         | 1.57%   |
| 1501-2000   | 2         | 1.57%   |
| Unknown     | 1         | 0.79%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 107       | 88.43%  |
| 16/10 | 6         | 4.96%   |
| 5/4   | 4         | 3.31%   |
| 4/3   | 2         | 1.65%   |
| 6/5   | 1         | 0.83%   |
| 21/9  | 1         | 0.83%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 46        | 35.38%  |
| 201-250        | 43        | 33.08%  |
| 301-350        | 10        | 7.69%   |
| 151-200        | 10        | 7.69%   |
| 81-90          | 5         | 3.85%   |
| 351-500        | 4         | 3.08%   |
| 251-300        | 3         | 2.31%   |
| 121-130        | 3         | 2.31%   |
| More than 1000 | 2         | 1.54%   |
| 61-70          | 1         | 0.77%   |
| 51-60          | 1         | 0.77%   |
| 131-140        | 1         | 0.77%   |
| Unknown        | 1         | 0.77%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 121-160 | 48        | 39.34%  |
| 51-100  | 48        | 39.34%  |
| 101-120 | 23        | 18.85%  |
| 161-240 | 2         | 1.64%   |
| Unknown | 1         | 0.82%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 106       | 76.81%  |
| 0     | 19        | 13.77%  |
| 2     | 13        | 9.42%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 97        | 56.73%  |
| Intel                 | 44        | 25.73%  |
| TP-Link               | 5         | 2.92%   |
| Qualcomm Atheros      | 5         | 2.92%   |
| MediaTek              | 4         | 2.34%   |
| Broadcom              | 4         | 2.34%   |
| Samsung Electronics   | 3         | 1.75%   |
| Nvidia                | 2         | 1.17%   |
| Xiaomi                | 1         | 0.58%   |
| Ralink Technology     | 1         | 0.58%   |
| Ralink                | 1         | 0.58%   |
| OKB SAPR              | 1         | 0.58%   |
| Mercucys              | 1         | 0.58%   |
| Mellanox Technologies | 1         | 0.58%   |
| Edimax Technology     | 1         | 0.58%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 30.73%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 26        | 12.68%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter               | 7         | 3.41%   |
| Intel Ethernet Controller I225-V                                  | 7         | 3.41%   |
| Intel Wireless 7265                                               | 6         | 2.93%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 2.93%   |
| Intel Wireless 3165                                               | 5         | 2.44%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 4         | 1.95%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 1.95%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                        | 3         | 1.46%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.46%   |
| Intel Ethernet Connection (14) I219-V                             | 3         | 1.46%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 2         | 0.98%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.98%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.98%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 0.98%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.98%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.98%   |
| Nvidia MCP61 Ethernet                                             | 2         | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 2         | 0.98%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.98%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.98%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 2         | 0.98%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.49%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.49%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                            | 1         | 0.49%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]        | 1         | 0.49%   |
| TP-Link 802.11n NIC                                               | 1         | 0.49%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.49%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                   | 1         | 0.49%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.49%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.49%   |
| Realtek 802.11n WLAN Adapter                                      | 1         | 0.49%   |
| Realtek 802.11ac NIC                                              | 1         | 0.49%   |
| Ralink MT7601U Wireless Adapter                                   | 1         | 0.49%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                         | 1         | 0.49%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 1         | 0.49%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.49%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.49%   |
| OKB SAPR Ethernet controller                                      | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 44        | 52.38%  |
| Intel                 | 25        | 29.76%  |
| TP-Link               | 4         | 4.76%   |
| Qualcomm Atheros      | 3         | 3.57%   |
| MediaTek              | 2         | 2.38%   |
| Broadcom              | 2         | 2.38%   |
| Ralink Technology     | 1         | 1.19%   |
| Ralink                | 1         | 1.19%   |
| Mercucys              | 1         | 1.19%   |
| Edimax Technology     | 1         | 1.19%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 26        | 30.23%  |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 7         | 8.14%   |
| Intel Wireless 7265                                           | 6         | 6.98%   |
| Intel Wireless 3165                                           | 5         | 5.81%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 4         | 4.65%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 3         | 3.49%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 3.49%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 2         | 2.33%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 2.33%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 2.33%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 2         | 2.33%   |
| Intel Wireless 8265 / 8275                                    | 2         | 2.33%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                      | 2         | 2.33%   |
| TP-Link Archer T3U [Realtek RTL8812BU]                        | 1         | 1.16%   |
| TP-Link AC600 wireless Realtek RTL8811AU [Archer T2U Nano]    | 1         | 1.16%   |
| TP-Link 802.11n NIC                                           | 1         | 1.16%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1         | 1.16%   |
| Realtek 802.11n WLAN Adapter                                  | 1         | 1.16%   |
| Realtek 802.11ac NIC                                          | 1         | 1.16%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 1.16%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 1         | 1.16%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 1         | 1.16%   |
| Mercucys 802.11n NIC                                          | 1         | 1.16%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 1         | 1.16%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection         | 1         | 1.16%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 1         | 1.16%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth               | 1         | 1.16%   |
| Intel Comet Lake PCH-LP CNVi WiFi                             | 1         | 1.16%   |
| Intel Comet Lake PCH CNVi WiFi                                | 1         | 1.16%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 1         | 1.16%   |
| Edimax AC1200 MU-MIMO USB2.0 Adapter                          | 1         | 1.16%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter            | 1         | 1.16%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter           | 1         | 1.16%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 67        | 58.26%  |
| Intel                 | 33        | 28.7%   |
| Samsung Electronics   | 3         | 2.61%   |
| Qualcomm Atheros      | 2         | 1.74%   |
| Nvidia                | 2         | 1.74%   |
| MediaTek              | 2         | 1.74%   |
| Broadcom              | 2         | 1.74%   |
| Xiaomi                | 1         | 0.87%   |
| TP-Link               | 1         | 0.87%   |
| OKB SAPR              | 1         | 0.87%   |
| Mellanox Technologies | 1         | 0.87%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 63        | 52.94%  |
| Intel Ethernet Controller I225-V                                  | 7         | 5.88%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 5.04%   |
| Intel Ethernet Connection (7) I219-V                              | 4         | 3.36%   |
| Intel Ethernet Connection (14) I219-V                             | 3         | 2.52%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 1.68%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 2         | 1.68%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.68%   |
| Nvidia MCP61 Ethernet                                             | 2         | 1.68%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.68%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 1         | 0.84%   |
| TP-Link USB 10/100 LAN                                            | 1         | 0.84%   |
| Samsung GT-I9070 (network tethering, USB debugging enabled)       | 1         | 0.84%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 1         | 0.84%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 1         | 0.84%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.84%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 1         | 0.84%   |
| OKB SAPR Ethernet controller                                      | 1         | 0.84%   |
| Mellanox MT27800 Family [ConnectX-5]                              | 1         | 0.84%   |
| MediaTek TECNO Pouvoir 3 Air                                      | 1         | 0.84%   |
| MediaTek moto e(7) power                                          | 1         | 0.84%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.84%   |
| Intel I211 Gigabit Network Connection                             | 1         | 0.84%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.84%   |
| Intel Ethernet Controller X710 for 10GbE SFP+                     | 1         | 0.84%   |
| Intel Ethernet Controller I225-LM                                 | 1         | 0.84%   |
| Intel Ethernet Connection X722 for 10GbE SFP+                     | 1         | 0.84%   |
| Intel Ethernet Connection X722 for 10GBASE-T                      | 1         | 0.84%   |
| Intel Ethernet Connection (7) I219-LM                             | 1         | 0.84%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.84%   |
| Intel Ethernet Connection (12) I219-V                             | 1         | 0.84%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.84%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 1         | 0.84%   |
| Intel 82574L Gigabit Network Connection                           | 1         | 0.84%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 1         | 0.84%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 1         | 0.84%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 106       | 56.99%  |
| WiFi     | 80        | 43.01%  |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 91        | 66.42%  |
| WiFi     | 46        | 33.58%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 83        | 61.48%  |
| 2     | 46        | 34.07%  |
| 0     | 4         | 2.96%   |
| 7     | 1         | 0.74%   |
| 4     | 1         | 0.74%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 133       | 97.79%  |
| Yes  | 3         | 2.21%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Realtek Semiconductor           | 29        | 45.31%  |
| Intel                           | 22        | 34.38%  |
| IMC Networks                    | 3         | 4.69%   |
| Broadcom                        | 3         | 4.69%   |
| Realtek                         | 2         | 3.13%   |
| TP-Link                         | 1         | 1.56%   |
| Ralink                          | 1         | 1.56%   |
| Qualcomm Atheros Communications | 1         | 1.56%   |
| Lite-On Technology              | 1         | 1.56%   |
| Foxconn / Hon Hai               | 1         | 1.56%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                            | Computers | Percent |
|--------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                          | 28        | 43.75%  |
| Intel Bluetooth wireless interface               | 13        | 20.31%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)   | 5         | 7.81%   |
| Intel AX201 Bluetooth                            | 4         | 6.25%   |
| Realtek Bluetooth Radio                          | 2         | 3.13%   |
| IMC Networks Bluetooth Radio                     | 2         | 3.13%   |
| TP-Link TPuLink UB500 Adapter                    | 1         | 1.56%   |
| Realtek  Bluetooth 4.2 Adapter                   | 1         | 1.56%   |
| Ralink RT3290 Bluetooth                          | 1         | 1.56%   |
| Qualcomm Atheros  Bluetooth Device               | 1         | 1.56%   |
| Lite-On Wireless_Device                          | 1         | 1.56%   |
| IMC Networks Bluetooth Device                    | 1         | 1.56%   |
| Foxconn / Hon Hai Wireless_Device                | 1         | 1.56%   |
| Broadcom HP Portable Valentine                   | 1         | 1.56%   |
| Broadcom BCM92046DG-CL1ROM Bluetooth 2.1 Adapter | 1         | 1.56%   |
| Broadcom BCM2045 Bluetooth                       | 1         | 1.56%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor               | Computers | Percent |
|----------------------|-----------|---------|
| Intel                | 106       | 68.39%  |
| AMD                  | 29        | 18.71%  |
| Nvidia               | 14        | 9.03%   |
| C-Media Electronics  | 2         | 1.29%   |
| Texas Instruments    | 1         | 0.65%   |
| Razer USA            | 1         | 0.65%   |
| MosArt Semiconductor | 1         | 0.65%   |
| Lenovo               | 1         | 0.65%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Cannon Point-LP High Definition Audio Controller                     | 25        | 13.97%  |
| AMD Family 17h/19h HD Audio Controller                                     | 20        | 11.17%  |
| Intel Audio device                                                         | 16        | 8.94%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 14        | 7.82%   |
| Intel 200 Series PCH HD Audio                                              | 10        | 5.59%   |
| Intel Cannon Lake PCH cAVS                                                 | 8         | 4.47%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 8         | 4.47%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 3.35%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 5         | 2.79%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 5         | 2.79%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 4         | 2.23%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.68%   |
| Intel Comet Lake PCH-V cAVS                                                | 3         | 1.68%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 3         | 1.68%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 2         | 1.12%   |
| Nvidia MCP61 High Definition Audio                                         | 2         | 1.12%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 1.12%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 2         | 1.12%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 1.12%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 1.12%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 2         | 1.12%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 2         | 1.12%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 2         | 1.12%   |
| AMD Starship/Matisse HD Audio Controller                                   | 2         | 1.12%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                               | 2         | 1.12%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 2         | 1.12%   |
| Texas Instruments PCM2902 Audio Codec                                      | 1         | 0.56%   |
| Razer USA Kraken Tournament Edition                                        | 1         | 0.56%   |
| Nvidia TU116 High Definition Audio Controller                              | 1         | 0.56%   |
| Nvidia TU104 HD Audio Controller                                           | 1         | 0.56%   |
| Nvidia GP108 High Definition Audio Controller                              | 1         | 0.56%   |
| Nvidia GP107GL High Definition Audio Controller                            | 1         | 0.56%   |
| Nvidia GP106 High Definition Audio Controller                              | 1         | 0.56%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 1         | 0.56%   |
| Nvidia GK104 HDMI Audio Controller                                         | 1         | 0.56%   |
| Nvidia GF114 HDMI Audio Controller                                         | 1         | 0.56%   |
| Nvidia Audio device                                                        | 1         | 0.56%   |
| MosArt Semiconductor MosArt USB Audio Device                               | 1         | 0.56%   |
| Lenovo ThinkCentre TIO27 for USB-audio                                     | 1         | 0.56%   |
| Intel Sunrise Point-LP HD Audio                                            | 1         | 0.56%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Samsung Electronics | 34        | 23.94%  |
| Crucial             | 17        | 11.97%  |
| Foxline             | 13        | 9.15%   |
| Kingston            | 12        | 8.45%   |
| SK hynix            | 11        | 7.75%   |
| Unknown             | 9         | 6.34%   |
| Ramaxel Technology  | 7         | 4.93%   |
| Unknown (ABCD)      | 5         | 3.52%   |
| Micron Technology   | 5         | 3.52%   |
| AMD                 | 5         | 3.52%   |
| Patriot             | 4         | 2.82%   |
| Elpida              | 3         | 2.11%   |
| Unknown             | 3         | 2.11%   |
| Qumo                | 2         | 1.41%   |
| Corsair             | 2         | 1.41%   |
| Apacer              | 2         | 1.41%   |
| A-DATA Technology   | 2         | 1.41%   |
| Unknown (BA8A)      | 1         | 0.7%    |
| Neo Forza           | 1         | 0.7%    |
| King Tiger          | 1         | 0.7%    |
| Good Wealth         | 1         | 0.7%    |
| Golden Empire       | 1         | 0.7%    |
| ChangXin Memory     | 1         | 0.7%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 17        | 11.64%  |
| Foxline RAM FL2666D4S19-8G 8GB SODIMM DDR4 2667MT/s              | 5         | 3.42%   |
| Foxline RAM FL2666D4U19-8G 8GB DIMM DDR4 2667MT/s                | 4         | 2.74%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 2.05%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB Row Of Chips DDR4 3200MT/s     | 3         | 2.05%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 3         | 2.05%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s        | 3         | 2.05%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 3         | 2.05%   |
| AMD RAM R748G2606U2S 8GB DIMM DDR4 3200MT/s                      | 3         | 2.05%   |
| Unknown                                                          | 3         | 2.05%   |
| Unknown RAM Module 8GB DIMM DDR4 2667MT/s                        | 2         | 1.37%   |
| Unknown (ABCD) RAM 123456789012345678 8GB DIMM DDR4 2400MT/s     | 2         | 1.37%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB Row Of Chips DDR4 2667MT/s     | 2         | 1.37%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 2         | 1.37%   |
| Patriot RAM PSD48G266681 8GB DIMM DDR4 2934MT/s                  | 2         | 1.37%   |
| Kingston RAM KHX2666C16/16G 16384MB DIMM DDR4 3200MT/s           | 2         | 1.37%   |
| Foxline RAM FL3200D4S22-8G 8GB SODIMM DDR4 3200MT/s              | 2         | 1.37%   |
| Crucial RAM CT4G4DFS8213.C8FBD2 4GB DIMM DDR4 2800MT/s           | 2         | 1.37%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.68%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM SDRAM                                | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR3 1066MT/s                        | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.68%   |
| Unknown RAM Module 2GB DIMM 400MT/s                              | 1         | 0.68%   |
| Unknown RAM Module 1GB DIMM SDRAM                                | 1         | 0.68%   |
| Unknown RAM Module 1GB DIMM DDR2 667MT/s                         | 1         | 0.68%   |
| Unknown (BA8A) RAM Module 8GB SODIMM DDR4 2667MT/s               | 1         | 0.68%   |
| SK hynix RAM HMT451U6MFR8C-PB 4GB DIMM DDR3 1800MT/s             | 1         | 0.68%   |
| SK hynix RAM HMT451U6AFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 0.68%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.68%   |
| SK hynix RAM HMT125U7TFR8C-H9 2GB DIMM DDR3 1333MT/s             | 1         | 0.68%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB Row Of Chips DDR4 3200MT/s     | 1         | 0.68%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.68%   |
| Samsung RAM Module 8GB SODIMM DDR4 2667MT/s                      | 1         | 0.68%   |
| Samsung RAM M471B5773DH0-CK0 2048MB SODIMM DDR3 1600MT/s         | 1         | 0.68%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 1         | 0.68%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.68%   |
| Samsung RAM M471A5244BB0-CRC 4GB SODIMM DDR4 2667MT/s            | 1         | 0.68%   |
| Samsung RAM M471A2K43DB1-CTD 16GB SODIMM DDR4 2667MT/s           | 1         | 0.68%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 0.68%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 105       | 81.4%   |
| DDR3    | 12        | 9.3%    |
| LPDDR4  | 5         | 3.88%   |
| DDR2    | 3         | 2.33%   |
| Unknown | 3         | 2.33%   |
| SDRAM   | 1         | 0.78%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 68        | 51.52%  |
| DIMM         | 57        | 43.18%  |
| Row Of Chips | 7         | 5.3%    |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 79        | 56.43%  |
| 4096  | 32        | 22.86%  |
| 16384 | 11        | 7.86%   |
| 2048  | 10        | 7.14%   |
| 32768 | 4         | 2.86%   |
| 1024  | 3         | 2.14%   |
| 65536 | 1         | 0.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 2667    | 52        | 38.81%  |
| 3200    | 30        | 22.39%  |
| 2400    | 11        | 8.21%   |
| 1333    | 6         | 4.48%   |
| 2133    | 4         | 2.99%   |
| 1600    | 4         | 2.99%   |
| 2933    | 3         | 2.24%   |
| 2666    | 3         | 2.24%   |
| 3466    | 2         | 1.49%   |
| 2934    | 2         | 1.49%   |
| 2800    | 2         | 1.49%   |
| 667     | 2         | 1.49%   |
| 3400    | 1         | 0.75%   |
| 3266    | 1         | 0.75%   |
| 3000    | 1         | 0.75%   |
| 2866    | 1         | 0.75%   |
| 2733    | 1         | 0.75%   |
| 1866    | 1         | 0.75%   |
| 1800    | 1         | 0.75%   |
| 1334    | 1         | 0.75%   |
| 1066    | 1         | 0.75%   |
| 800     | 1         | 0.75%   |
| 400     | 1         | 0.75%   |
| 333     | 1         | 0.75%   |
| Unknown | 1         | 0.75%   |

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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                  | Computers | Percent |
|------------------------|-----------|---------|
| Canon CanoScan LIDE 25 | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Syntek                                 | 19        | 25.68%  |
| Chicony Electronics                    | 13        | 17.57%  |
| IMC Networks                           | 9         | 12.16%  |
| Alcor Micro                            | 6         | 8.11%   |
| SunplusIT                              | 4         | 5.41%   |
| Acer                                   | 4         | 5.41%   |
| Quanta                                 | 3         | 4.05%   |
| USB Camera CS                          | 2         | 2.7%    |
| Sunplus Innovation Technology          | 2         | 2.7%    |
| Logitech                               | 2         | 2.7%    |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.7%    |
| Suyin                                  | 1         | 1.35%   |
| Realtek Semiconductor                  | 1         | 1.35%   |
| Microdia                               | 1         | 1.35%   |
| Luxvisions Innotech Limited            | 1         | 1.35%   |
| Creative Technology                    | 1         | 1.35%   |
| Arkmicro Technologies                  | 1         | 1.35%   |
| Apple                                  | 1         | 1.35%   |
| AlcorMicroCorp                         | 1         | 1.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Syntek Integrated Camera                                                   | 18        | 24.32%  |
| Chicony USB camera                                                         | 7         | 9.46%   |
| SunplusIT 5M-A2SP Webcam                                                   | 3         | 4.05%   |
| IMC Networks Integrated Camera                                             | 3         | 4.05%   |
| Alcor Micro USB 2.0 PC Camera                                              | 3         | 4.05%   |
| Acer Integrated Camera                                                     | 3         | 4.05%   |
| USB Camera CS USB Camera CS                                                | 2         | 2.7%    |
| Logitech HD Webcam C615                                                    | 2         | 2.7%    |
| IMC Networks USB2.0 HD UVC WebCam                                          | 2         | 2.7%    |
| IMC Networks ov9734_azurewave_camera                                       | 2         | 2.7%    |
| Chicony HD User Facing                                                     | 2         | 2.7%    |
| Syntek Integrated RGB Camera                                               | 1         | 1.35%   |
| Suyin Acer CrystalEye Webcam                                               | 1         | 1.35%   |
| SunplusIT USB camera                                                       | 1         | 1.35%   |
| Sunplus BKX Usb FHD Camera                                                 | 1         | 1.35%   |
| Sunplus Asus Webcam                                                        | 1         | 1.35%   |
| Realtek 1080p Camera                                                       | 1         | 1.35%   |
| Quanta USB HD Webcam                                                       | 1         | 1.35%   |
| Quanta HP 2.0MP High Definition Webcam                                     | 1         | 1.35%   |
| Quanta HD Camera                                                           | 1         | 1.35%   |
| Microdia USB Live camera                                                   | 1         | 1.35%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera                        | 1         | 1.35%   |
| IMC Networks USB2.0 VGA UVC WebCam                                         | 1         | 1.35%   |
| IMC Networks HD Camera                                                     | 1         | 1.35%   |
| Creative VF0530 Live! Cam Chat IM                                          | 1         | 1.35%   |
| Chicony USB2.0 Camera                                                      | 1         | 1.35%   |
| Chicony Integrated Camera                                                  | 1         | 1.35%   |
| Chicony HP Webcam-50                                                       | 1         | 1.35%   |
| Chicony HP TrueVision HD Camera                                            | 1         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) USB2.0 UVC 1.3M Webcam              | 1         | 1.35%   |
| Cheng Uei Precision Industry (Foxlink) HP Wide Vision HD integrated webcam | 1         | 1.35%   |
| Arkmicro USB2.0 PC CAMERA                                                  | 1         | 1.35%   |
| Apple iPhone 5/5C/5S/6/SE                                                  | 1         | 1.35%   |
| AlcorMicroCorp SHUNCCM                                                     | 1         | 1.35%   |
| Alcor Micro USB2.0 Camera                                                  | 1         | 1.35%   |
| Alcor Micro USB FHD Camera                                                 | 1         | 1.35%   |
| Alcor Micro USB 2.0 WebCamera                                              | 1         | 1.35%   |
| Acer BisonCam, NB Pro                                                      | 1         | 1.35%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Shenzhen Goodix Technology | 5         | 100%    |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device | 5         | 100%    |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor       | Computers | Percent |
|--------------|-----------|---------|
| Aladdin R.D. | 1         | 100%    |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                | Computers | Percent |
|----------------------|-----------|---------|
| Aladdin R.D. JaCarta | 1         | 100%    |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 105       | 75.54%  |
| 1     | 29        | 20.86%  |
| 2     | 3         | 2.16%   |
| 4     | 1         | 0.72%   |
| 3     | 1         | 0.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Graphics card            | 18        | 46.15%  |
| Net/wireless             | 7         | 17.95%  |
| Fingerprint reader       | 5         | 12.82%  |
| Unassigned class         | 3         | 7.69%   |
| Communication controller | 2         | 5.13%   |
| Net/ethernet             | 1         | 2.56%   |
| Multimedia controller    | 1         | 2.56%   |
| Chipcard                 | 1         | 2.56%   |
| Bluetooth                | 1         | 2.56%   |

