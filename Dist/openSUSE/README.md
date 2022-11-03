openSUSE - Tested Hardware & Statistics
---------------------------------------

A project to collect tested hardware configurations for openSUSE.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE/Desktop/README.md) and [notebooks](/Dist/openSUSE/Notebook/README.md).

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

Total: 2278

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Gigabyte      | X570 GAMING X               | Desktop     | [b3613b84ad](https://linux-hardware.org/?probe=b3613b84ad) | Nov 02, 2022 |
| ASUSTek       | F2A55-M LK                  | Desktop     | [40cedc7d2c](https://linux-hardware.org/?probe=40cedc7d2c) | Nov 02, 2022 |
| HP            | 829B                        | All in one  | [23122cba32](https://linux-hardware.org/?probe=23122cba32) | Nov 01, 2022 |
| Dell          | 0C522T A01                  | Desktop     | [efee8139b0](https://linux-hardware.org/?probe=efee8139b0) | Nov 01, 2022 |
| HP            | Notebook                    | Notebook    | [27d097b522](https://linux-hardware.org/?probe=27d097b522) | Nov 01, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [0131299a9e](https://linux-hardware.org/?probe=0131299a9e) | Nov 01, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [4833a609c3](https://linux-hardware.org/?probe=4833a609c3) | Oct 31, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [d7e9fb65d0](https://linux-hardware.org/?probe=d7e9fb65d0) | Oct 30, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [56dd93206a](https://linux-hardware.org/?probe=56dd93206a) | Oct 29, 2022 |
| Acer          | Extensa 215-54              | Notebook    | [0fe46d7655](https://linux-hardware.org/?probe=0fe46d7655) | Oct 29, 2022 |
| Dell          | Vostro 3580                 | Notebook    | [74a79dbdb6](https://linux-hardware.org/?probe=74a79dbdb6) | Oct 29, 2022 |
| Samsung       | 930QDB                      | Convertible | [453d856b8d](https://linux-hardware.org/?probe=453d856b8d) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [6314ec0dd1](https://linux-hardware.org/?probe=6314ec0dd1) | Oct 28, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [dcd40f9f78](https://linux-hardware.org/?probe=dcd40f9f78) | Oct 28, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [033cc83715](https://linux-hardware.org/?probe=033cc83715) | Oct 28, 2022 |
| Dell          | Latitude E6430              | Notebook    | [cb4eb1f556](https://linux-hardware.org/?probe=cb4eb1f556) | Oct 28, 2022 |
| Lenovo        | Unknown                     | Notebook    | [6a3e704d70](https://linux-hardware.org/?probe=6a3e704d70) | Oct 27, 2022 |
| Radxa         | Zero                        | Soc         | [e35d41a9a6](https://linux-hardware.org/?probe=e35d41a9a6) | Oct 27, 2022 |
| Dell          | Latitude 9420               | Notebook    | [a601281b46](https://linux-hardware.org/?probe=a601281b46) | Oct 27, 2022 |
| MSI           | X58 Pro                     | Desktop     | [6c449246c8](https://linux-hardware.org/?probe=6c449246c8) | Oct 27, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [a943d9879c](https://linux-hardware.org/?probe=a943d9879c) | Oct 26, 2022 |
| Dell          | 0X2MKR A00                  | All in one  | [5fa9b60268](https://linux-hardware.org/?probe=5fa9b60268) | Oct 26, 2022 |
| ASUSTek       | ASUS EXPERTBOOK L1500CDA... | Notebook    | [3d86f7ccac](https://linux-hardware.org/?probe=3d86f7ccac) | Oct 25, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS WI... | Desktop     | [9e63ba2bf9](https://linux-hardware.org/?probe=9e63ba2bf9) | Oct 23, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [3a60ac01f4](https://linux-hardware.org/?probe=3a60ac01f4) | Oct 23, 2022 |
| MSI           | X58 Pro                     | Desktop     | [96db21189e](https://linux-hardware.org/?probe=96db21189e) | Oct 22, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [94f3d7aa9d](https://linux-hardware.org/?probe=94f3d7aa9d) | Oct 22, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [fbc271b648](https://linux-hardware.org/?probe=fbc271b648) | Oct 22, 2022 |
| Lenovo        | 3111 NOK                    | Desktop     | [185e1ca963](https://linux-hardware.org/?probe=185e1ca963) | Oct 21, 2022 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [4c699ac628](https://linux-hardware.org/?probe=4c699ac628) | Oct 21, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [5e59c8933b](https://linux-hardware.org/?probe=5e59c8933b) | Oct 20, 2022 |
| HP            | ZBook 17                    | Notebook    | [6dc9848327](https://linux-hardware.org/?probe=6dc9848327) | Oct 20, 2022 |
| Sony          | VPCEL3S1R                   | Notebook    | [5c37559c2d](https://linux-hardware.org/?probe=5c37559c2d) | Oct 20, 2022 |
| Fujitsu Si... | D2399 S26361-D2399          | Desktop     | [77a5931c66](https://linux-hardware.org/?probe=77a5931c66) | Oct 20, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [46b9d8c126](https://linux-hardware.org/?probe=46b9d8c126) | Oct 19, 2022 |
| HP            | ZBook 15 G3                 | Notebook    | [a078a2f2ae](https://linux-hardware.org/?probe=a078a2f2ae) | Oct 19, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [a66d2944a8](https://linux-hardware.org/?probe=a66d2944a8) | Oct 18, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [e4769fb9e0](https://linux-hardware.org/?probe=e4769fb9e0) | Oct 18, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [76bb60e5ee](https://linux-hardware.org/?probe=76bb60e5ee) | Oct 17, 2022 |
| MSI           | GE70 2PE                    | Notebook    | [ff621f681e](https://linux-hardware.org/?probe=ff621f681e) | Oct 17, 2022 |
| Dell          | Inspiron 7577               | Notebook    | [8b1714d48d](https://linux-hardware.org/?probe=8b1714d48d) | Oct 17, 2022 |
| MSI           | H170I PRO AC                | Desktop     | [ea4ecf6238](https://linux-hardware.org/?probe=ea4ecf6238) | Oct 17, 2022 |
| MSI           | A75MA-G55                   | Desktop     | [79c4c3b21f](https://linux-hardware.org/?probe=79c4c3b21f) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [f1e08df02d](https://linux-hardware.org/?probe=f1e08df02d) | Oct 16, 2022 |
| Lenovo        | ThinkPad P15s Gen 2i 20W... | Notebook    | [2dd0b46420](https://linux-hardware.org/?probe=2dd0b46420) | Oct 16, 2022 |
| Lenovo        | ThinkPad T14 Gen 2a 20XK... | Notebook    | [b11fa8e1dd](https://linux-hardware.org/?probe=b11fa8e1dd) | Oct 16, 2022 |
| Gigabyte      | X79-UP4                     | Desktop     | [6ccc41cf96](https://linux-hardware.org/?probe=6ccc41cf96) | Oct 15, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [a29fae2a74](https://linux-hardware.org/?probe=a29fae2a74) | Oct 14, 2022 |
| MSI           | Prestige 14 A11SCS          | Notebook    | [e552920463](https://linux-hardware.org/?probe=e552920463) | Oct 13, 2022 |
| ASUSTek       | ZenBook UX425IA_UM425IA     | Notebook    | [61eb97192e](https://linux-hardware.org/?probe=61eb97192e) | Oct 12, 2022 |
| Toshiba       | Satellite P55t-A            | Notebook    | [60d52e85a0](https://linux-hardware.org/?probe=60d52e85a0) | Oct 12, 2022 |
| ASUSTek       | H81M-K                      | Desktop     | [31fbbb40a0](https://linux-hardware.org/?probe=31fbbb40a0) | Oct 11, 2022 |
| Lenovo        | ThinkPad T430 2347DS3       | Notebook    | [970542656e](https://linux-hardware.org/?probe=970542656e) | Oct 11, 2022 |
| ASUSTek       | PRIME H610M-A D4            | Desktop     | [52997332e0](https://linux-hardware.org/?probe=52997332e0) | Oct 11, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [50b8cde0ed](https://linux-hardware.org/?probe=50b8cde0ed) | Oct 10, 2022 |
| Intel         | (R) Education Tablet        | Notebook    | [9d1756d283](https://linux-hardware.org/?probe=9d1756d283) | Oct 09, 2022 |
| Gateway       | NV54 Series                 | Notebook    | [88b57ed4e4](https://linux-hardware.org/?probe=88b57ed4e4) | Oct 09, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [7d71e688f4](https://linux-hardware.org/?probe=7d71e688f4) | Oct 08, 2022 |
| ASUSTek       | F3Sv                        | Notebook    | [042104bbc2](https://linux-hardware.org/?probe=042104bbc2) | Oct 08, 2022 |
| ASUSTek       | PRIME Z690-P WIFI D4        | Desktop     | [b8f7c25d91](https://linux-hardware.org/?probe=b8f7c25d91) | Oct 07, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [79268bac9b](https://linux-hardware.org/?probe=79268bac9b) | Oct 06, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [9ef16d569e](https://linux-hardware.org/?probe=9ef16d569e) | Oct 06, 2022 |
| Toshiba       | Satellite L350              | Notebook    | [cf2e5dae86](https://linux-hardware.org/?probe=cf2e5dae86) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c12ce7288b](https://linux-hardware.org/?probe=c12ce7288b) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c3306965d6](https://linux-hardware.org/?probe=c3306965d6) | Oct 05, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [b07d3b7b7f](https://linux-hardware.org/?probe=b07d3b7b7f) | Oct 05, 2022 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [33a0cb05e8](https://linux-hardware.org/?probe=33a0cb05e8) | Oct 04, 2022 |
| Acer          | S50-54                      | Notebook    | [7680195105](https://linux-hardware.org/?probe=7680195105) | Oct 04, 2022 |
| Dell          | Latitude 3340               | Notebook    | [100b89b0a9](https://linux-hardware.org/?probe=100b89b0a9) | Oct 04, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [daec61299a](https://linux-hardware.org/?probe=daec61299a) | Oct 03, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [79f922d367](https://linux-hardware.org/?probe=79f922d367) | Oct 02, 2022 |
| Acer          | S50-54                      | Notebook    | [a7ff4f9792](https://linux-hardware.org/?probe=a7ff4f9792) | Oct 02, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [59c14fb5c0](https://linux-hardware.org/?probe=59c14fb5c0) | Oct 02, 2022 |
| MSI           | X370 XPOWER GAMING TITAN... | Desktop     | [9121550ca1](https://linux-hardware.org/?probe=9121550ca1) | Oct 02, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [6e3b616977](https://linux-hardware.org/?probe=6e3b616977) | Oct 02, 2022 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [921b395e9c](https://linux-hardware.org/?probe=921b395e9c) | Oct 02, 2022 |
| Dell          | 0N4YC8 A00                  | Desktop     | [bf657c61f5](https://linux-hardware.org/?probe=bf657c61f5) | Oct 02, 2022 |
| ASUSTek       | M5A97 R2.0                  | Desktop     | [2c82f3311d](https://linux-hardware.org/?probe=2c82f3311d) | Sep 28, 2022 |
| Dell          | Latitude E5250              | Notebook    | [6116460e52](https://linux-hardware.org/?probe=6116460e52) | Sep 27, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d6d9af3173](https://linux-hardware.org/?probe=d6d9af3173) | Sep 26, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [ff70118578](https://linux-hardware.org/?probe=ff70118578) | Sep 26, 2022 |
| Lenovo        | ThinkPad E14 Gen 4 21EB0... | Notebook    | [6c0c9c0037](https://linux-hardware.org/?probe=6c0c9c0037) | Sep 25, 2022 |
| ASRock        | Z170 Extreme4               | Desktop     | [e0ae893d39](https://linux-hardware.org/?probe=e0ae893d39) | Sep 25, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | Notebook    | [911a73323d](https://linux-hardware.org/?probe=911a73323d) | Sep 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a2b3fd8ea8](https://linux-hardware.org/?probe=a2b3fd8ea8) | Sep 24, 2022 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fd63352b24](https://linux-hardware.org/?probe=fd63352b24) | Sep 24, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1bec04d42d](https://linux-hardware.org/?probe=1bec04d42d) | Sep 21, 2022 |
| Timi          | A35S                        | Notebook    | [a57a688f31](https://linux-hardware.org/?probe=a57a688f31) | Sep 21, 2022 |
| Dell          | Latitude 7400               | Notebook    | [466bd310ef](https://linux-hardware.org/?probe=466bd310ef) | Sep 21, 2022 |
| ASUSTek       | WS C422 PRO_SE              | Desktop     | [e278a4ab5e](https://linux-hardware.org/?probe=e278a4ab5e) | Sep 21, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [ed6f75ec9f](https://linux-hardware.org/?probe=ed6f75ec9f) | Sep 20, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [af2eb79f4c](https://linux-hardware.org/?probe=af2eb79f4c) | Sep 20, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [5b0c60618f](https://linux-hardware.org/?probe=5b0c60618f) | Sep 20, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [a7f0e24464](https://linux-hardware.org/?probe=a7f0e24464) | Sep 20, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [7f7ef47d4b](https://linux-hardware.org/?probe=7f7ef47d4b) | Sep 20, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [167d69530f](https://linux-hardware.org/?probe=167d69530f) | Sep 19, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [d3b972d870](https://linux-hardware.org/?probe=d3b972d870) | Sep 19, 2022 |
| Acer          | Predator PH315-52           | Notebook    | [959330d9c1](https://linux-hardware.org/?probe=959330d9c1) | Sep 19, 2022 |
| MSI           | MAG Z590 TORPEDO            | Desktop     | [2daced0309](https://linux-hardware.org/?probe=2daced0309) | Sep 17, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [43bc9e36cd](https://linux-hardware.org/?probe=43bc9e36cd) | Sep 17, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [42f1c1aee1](https://linux-hardware.org/?probe=42f1c1aee1) | Sep 17, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [1d4585c98a](https://linux-hardware.org/?probe=1d4585c98a) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [e85965bc82](https://linux-hardware.org/?probe=e85965bc82) | Sep 16, 2022 |
| BESSTAR Te... | F6BFC                       | Desktop     | [0278cf2e45](https://linux-hardware.org/?probe=0278cf2e45) | Sep 16, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [a4dad191d2](https://linux-hardware.org/?probe=a4dad191d2) | Sep 15, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [889c55b24d](https://linux-hardware.org/?probe=889c55b24d) | Sep 15, 2022 |
| HP            | EliteBook 8470p             | Notebook    | [337ccff161](https://linux-hardware.org/?probe=337ccff161) | Sep 15, 2022 |
| ASUSTek       | X55CR                       | Notebook    | [43b77d436c](https://linux-hardware.org/?probe=43b77d436c) | Sep 14, 2022 |
| ASRock        | B450 Steel Legend           | Desktop     | [f9c010c1a9](https://linux-hardware.org/?probe=f9c010c1a9) | Sep 14, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [c0e411a96d](https://linux-hardware.org/?probe=c0e411a96d) | Sep 13, 2022 |
| MSI           | X58 Pro                     | Desktop     | [60406c82e8](https://linux-hardware.org/?probe=60406c82e8) | Sep 12, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [6d70631176](https://linux-hardware.org/?probe=6d70631176) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [a30032ef92](https://linux-hardware.org/?probe=a30032ef92) | Sep 11, 2022 |
| Apple         | MacBookPro8,2               | Notebook    | [0645f03606](https://linux-hardware.org/?probe=0645f03606) | Sep 11, 2022 |
| Gigabyte      | Z77-DS3H                    | Desktop     | [7532844cd7](https://linux-hardware.org/?probe=7532844cd7) | Sep 11, 2022 |
| Lenovo        | ThinkPad W510 4391W3V       | Notebook    | [cae551826b](https://linux-hardware.org/?probe=cae551826b) | Sep 10, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [706514d122](https://linux-hardware.org/?probe=706514d122) | Sep 10, 2022 |
| ASUSTek       | V161GAR                     | All in one  | [668d4ac33b](https://linux-hardware.org/?probe=668d4ac33b) | Sep 09, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [921b9580f4](https://linux-hardware.org/?probe=921b9580f4) | Sep 09, 2022 |
| MSI           | Modern 14 B5M               | Notebook    | [b11b5bcba5](https://linux-hardware.org/?probe=b11b5bcba5) | Sep 09, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [ea53dc8c02](https://linux-hardware.org/?probe=ea53dc8c02) | Sep 07, 2022 |
| MSI           | P67A-C45                    | Desktop     | [4221289e11](https://linux-hardware.org/?probe=4221289e11) | Sep 07, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [492849d42d](https://linux-hardware.org/?probe=492849d42d) | Sep 07, 2022 |
| Dell          | Precision 5530              | Notebook    | [d588e96ddc](https://linux-hardware.org/?probe=d588e96ddc) | Sep 07, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [068c169aa0](https://linux-hardware.org/?probe=068c169aa0) | Sep 07, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [f0ce37ab5a](https://linux-hardware.org/?probe=f0ce37ab5a) | Sep 06, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [6e0984d7ff](https://linux-hardware.org/?probe=6e0984d7ff) | Sep 06, 2022 |
| Biostar       | H77MU3                      | Desktop     | [20ba4d44ed](https://linux-hardware.org/?probe=20ba4d44ed) | Sep 05, 2022 |
| HP            | 250 G8 Notebook PC          | Notebook    | [312e65fd07](https://linux-hardware.org/?probe=312e65fd07) | Sep 05, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [8c4261ac4f](https://linux-hardware.org/?probe=8c4261ac4f) | Sep 04, 2022 |
| ASUSTek       | Maximus VIII RANGER         | Desktop     | [b298d162b1](https://linux-hardware.org/?probe=b298d162b1) | Sep 04, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [f79c38f9ff](https://linux-hardware.org/?probe=f79c38f9ff) | Sep 02, 2022 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ede97805ec](https://linux-hardware.org/?probe=ede97805ec) | Sep 02, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [3772ec2911](https://linux-hardware.org/?probe=3772ec2911) | Sep 02, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20S1S... | Notebook    | [e5ae0e72ca](https://linux-hardware.org/?probe=e5ae0e72ca) | Sep 02, 2022 |
| Samsung       | 550XBE/350XBE               | Notebook    | [0104e26464](https://linux-hardware.org/?probe=0104e26464) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| HP            | ENVY x360 2-in-1 Laptop ... | Convertible | [2615743a16](https://linux-hardware.org/?probe=2615743a16) | Sep 02, 2022 |
| ASUSTek       | Z97-PRO                     | Desktop     | [60865c8ded](https://linux-hardware.org/?probe=60865c8ded) | Sep 02, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [68170e253f](https://linux-hardware.org/?probe=68170e253f) | Sep 01, 2022 |
| Notebook      | N24_25JU                    | Notebook    | [50f570f3d9](https://linux-hardware.org/?probe=50f570f3d9) | Aug 31, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [bec76a1474](https://linux-hardware.org/?probe=bec76a1474) | Aug 30, 2022 |
| HP            | ZBook 17                    | Notebook    | [98e643f5af](https://linux-hardware.org/?probe=98e643f5af) | Aug 30, 2022 |
| ASRock        | B85 Pro4                    | Desktop     | [db3bc987b6](https://linux-hardware.org/?probe=db3bc987b6) | Aug 29, 2022 |
| Positivo      | W942SW_SW1                  | Notebook    | [62dcad10f0](https://linux-hardware.org/?probe=62dcad10f0) | Aug 29, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [e27f786190](https://linux-hardware.org/?probe=e27f786190) | Aug 28, 2022 |
| MSI           | P67A-C45                    | Desktop     | [5ffb676e01](https://linux-hardware.org/?probe=5ffb676e01) | Aug 27, 2022 |
| Google        | Eldrid                      | Notebook    | [6a0c6eb1de](https://linux-hardware.org/?probe=6a0c6eb1de) | Aug 27, 2022 |
| Lenovo        | ThinkPad T460s 20F9004NU... | Notebook    | [04f9f63255](https://linux-hardware.org/?probe=04f9f63255) | Aug 26, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [38a4407789](https://linux-hardware.org/?probe=38a4407789) | Aug 25, 2022 |
| Eluktronic... | MAX-17                      | Notebook    | [0a454665e0](https://linux-hardware.org/?probe=0a454665e0) | Aug 25, 2022 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [8021bbb58b](https://linux-hardware.org/?probe=8021bbb58b) | Aug 24, 2022 |
| HP            | 802F                        | Desktop     | [2c52215323](https://linux-hardware.org/?probe=2c52215323) | Aug 23, 2022 |
| HP            | 802F                        | Desktop     | [e181d03426](https://linux-hardware.org/?probe=e181d03426) | Aug 23, 2022 |
| Lenovo        | ThinkPad X1 Yoga Gen 5 2... | Convertible | [57727c2af7](https://linux-hardware.org/?probe=57727c2af7) | Aug 23, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [a9f2cced08](https://linux-hardware.org/?probe=a9f2cced08) | Aug 22, 2022 |
| ASRock        | Z97 Pro3                    | Desktop     | [9590ddbb06](https://linux-hardware.org/?probe=9590ddbb06) | Aug 22, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [c956ba84ed](https://linux-hardware.org/?probe=c956ba84ed) | Aug 22, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [68fa656563](https://linux-hardware.org/?probe=68fa656563) | Aug 21, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [a80c24ae6b](https://linux-hardware.org/?probe=a80c24ae6b) | Aug 21, 2022 |
| Intel         | NUC7i5DNB J57626-509        | Mini pc     | [20a816d976](https://linux-hardware.org/?probe=20a816d976) | Aug 21, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [a69a02f102](https://linux-hardware.org/?probe=a69a02f102) | Aug 20, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [b0579e2127](https://linux-hardware.org/?probe=b0579e2127) | Aug 19, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [8620d444d4](https://linux-hardware.org/?probe=8620d444d4) | Aug 19, 2022 |
| Gigabyte      | H81M-S2H                    | Desktop     | [5893f7215e](https://linux-hardware.org/?probe=5893f7215e) | Aug 19, 2022 |
| Dell          | XPS 15 9530                 | Notebook    | [9e6a3e80b4](https://linux-hardware.org/?probe=9e6a3e80b4) | Aug 19, 2022 |
| Lenovo        | Z51-70 80K6                 | Notebook    | [f10fe1f561](https://linux-hardware.org/?probe=f10fe1f561) | Aug 18, 2022 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [7b66b20b9f](https://linux-hardware.org/?probe=7b66b20b9f) | Aug 17, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [0e2658915d](https://linux-hardware.org/?probe=0e2658915d) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | Notebook    | [88ad38d9f7](https://linux-hardware.org/?probe=88ad38d9f7) | Aug 17, 2022 |
| Lenovo        | ThinkPad T450 20BUS0EW1F    | Notebook    | [73b611ea50](https://linux-hardware.org/?probe=73b611ea50) | Aug 17, 2022 |
| Dell          | 0F6X5P A00                  | Desktop     | [1ef086a230](https://linux-hardware.org/?probe=1ef086a230) | Aug 16, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a05b95b836](https://linux-hardware.org/?probe=a05b95b836) | Aug 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [aea2bfde6a](https://linux-hardware.org/?probe=aea2bfde6a) | Aug 15, 2022 |
| ASUSTek       | M3A78-EM                    | Desktop     | [d9fa82e283](https://linux-hardware.org/?probe=d9fa82e283) | Aug 15, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [fd64b105a4](https://linux-hardware.org/?probe=fd64b105a4) | Aug 14, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [73f2db9159](https://linux-hardware.org/?probe=73f2db9159) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [b3df3a51e0](https://linux-hardware.org/?probe=b3df3a51e0) | Aug 14, 2022 |
| ASUSTek       | ZenBook UX431DA_UM431DA     | Notebook    | [2043908eed](https://linux-hardware.org/?probe=2043908eed) | Aug 14, 2022 |
| Dell          | Latitude E6430              | Notebook    | [91a44f9b39](https://linux-hardware.org/?probe=91a44f9b39) | Aug 13, 2022 |
| Dell          | Latitude E6430              | Notebook    | [864ad41c22](https://linux-hardware.org/?probe=864ad41c22) | Aug 13, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [b1498c810e](https://linux-hardware.org/?probe=b1498c810e) | Aug 12, 2022 |
| ASRock        | X570 Steel Legend WiFi a... | Desktop     | [36a169c447](https://linux-hardware.org/?probe=36a169c447) | Aug 11, 2022 |
| ASRock        | X570 Steel Legend           | Desktop     | [42f35776a6](https://linux-hardware.org/?probe=42f35776a6) | Aug 10, 2022 |
| HP            | Laptop 17-by1xxx            | Notebook    | [1be4a11102](https://linux-hardware.org/?probe=1be4a11102) | Aug 09, 2022 |
| ASUSTek       | H81M-CS/BR                  | Desktop     | [8c2dc32c37](https://linux-hardware.org/?probe=8c2dc32c37) | Aug 09, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [119cdc7bf8](https://linux-hardware.org/?probe=119cdc7bf8) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [0aada24b1e](https://linux-hardware.org/?probe=0aada24b1e) | Aug 07, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [054c0beb4f](https://linux-hardware.org/?probe=054c0beb4f) | Aug 07, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| Valve         | Jupiter                     | Notebook    | [37f87e94fc](https://linux-hardware.org/?probe=37f87e94fc) | Aug 07, 2022 |
| Lenovo        | ThinkBook 14 G3 ACL 21A2    | Notebook    | [6880ac8488](https://linux-hardware.org/?probe=6880ac8488) | Aug 06, 2022 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [ec98a546e1](https://linux-hardware.org/?probe=ec98a546e1) | Aug 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [904bd1db44](https://linux-hardware.org/?probe=904bd1db44) | Aug 06, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [169fcf7943](https://linux-hardware.org/?probe=169fcf7943) | Aug 05, 2022 |
| Acer          | Aspire A515-45              | Notebook    | [ddd717c7e6](https://linux-hardware.org/?probe=ddd717c7e6) | Aug 05, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [1498e07a4b](https://linux-hardware.org/?probe=1498e07a4b) | Aug 04, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [99f7986364](https://linux-hardware.org/?probe=99f7986364) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [fbe4f4d2ce](https://linux-hardware.org/?probe=fbe4f4d2ce) | Aug 02, 2022 |
| Apple         | Mac-7BA5B2DFE22DDD8C Mac... | Mini pc     | [eeccdc2b7f](https://linux-hardware.org/?probe=eeccdc2b7f) | Aug 02, 2022 |
| Gigabyte      | B550M DS3H                  | Desktop     | [15bb5d1160](https://linux-hardware.org/?probe=15bb5d1160) | Aug 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [2e2f0ef440](https://linux-hardware.org/?probe=2e2f0ef440) | Jul 31, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [80007c0939](https://linux-hardware.org/?probe=80007c0939) | Jul 31, 2022 |
| Dell          | 052RF2 A01                  | Server      | [abe955b96f](https://linux-hardware.org/?probe=abe955b96f) | Jul 31, 2022 |
| Dell          | 052RF2 A01                  | Server      | [8ffda4cfe7](https://linux-hardware.org/?probe=8ffda4cfe7) | Jul 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon 6th 2... | Notebook    | [ae030e58fb](https://linux-hardware.org/?probe=ae030e58fb) | Jul 31, 2022 |
| Dell          | Inspiron 13-7359            | Notebook    | [24fa962b0b](https://linux-hardware.org/?probe=24fa962b0b) | Jul 28, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [ab6b15eef4](https://linux-hardware.org/?probe=ab6b15eef4) | Jul 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Lenovo        | ThinkPad W510 431965U       | Notebook    | [8ba9959c19](https://linux-hardware.org/?probe=8ba9959c19) | Jul 27, 2022 |
| Gigabyte      | X570 AORUS ULTRA            | Desktop     | [af32973765](https://linux-hardware.org/?probe=af32973765) | Jul 26, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [56c2008bb6](https://linux-hardware.org/?probe=56c2008bb6) | Jul 25, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [7f2dde6f76](https://linux-hardware.org/?probe=7f2dde6f76) | Jul 25, 2022 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [b874a0aa8e](https://linux-hardware.org/?probe=b874a0aa8e) | Jul 25, 2022 |
| Unknown       | Unknown                     | Notebook    | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [df5bd62f9a](https://linux-hardware.org/?probe=df5bd62f9a) | Jul 23, 2022 |
| HP            | 8715                        | Mini pc     | [75c873bb8e](https://linux-hardware.org/?probe=75c873bb8e) | Jul 23, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [7cb795f428](https://linux-hardware.org/?probe=7cb795f428) | Jul 22, 2022 |
| Biostar       | B450MH                      | Desktop     | [f69c4e3a03](https://linux-hardware.org/?probe=f69c4e3a03) | Jul 21, 2022 |
| Biostar       | B450MH                      | Desktop     | [79084ef4c9](https://linux-hardware.org/?probe=79084ef4c9) | Jul 21, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [5a6d4e8ba4](https://linux-hardware.org/?probe=5a6d4e8ba4) | Jul 21, 2022 |
| HP            | 158B                        | Desktop     | [017875f5a5](https://linux-hardware.org/?probe=017875f5a5) | Jul 21, 2022 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [7b128b9e7a](https://linux-hardware.org/?probe=7b128b9e7a) | Jul 19, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f2cda5634e](https://linux-hardware.org/?probe=f2cda5634e) | Jul 18, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [03d7fde009](https://linux-hardware.org/?probe=03d7fde009) | Jul 18, 2022 |
| Lenovo        | ThinkPad Edge 0328A11       | Notebook    | [4305889043](https://linux-hardware.org/?probe=4305889043) | Jul 17, 2022 |
| ASUSTek       | T101HA                      | Tablet      | [084f1e11d2](https://linux-hardware.org/?probe=084f1e11d2) | Jul 17, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [5ac3a7aa95](https://linux-hardware.org/?probe=5ac3a7aa95) | Jul 17, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [0f1dd0317a](https://linux-hardware.org/?probe=0f1dd0317a) | Jul 17, 2022 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [8b5480a55e](https://linux-hardware.org/?probe=8b5480a55e) | Jul 16, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [b6d23c8307](https://linux-hardware.org/?probe=b6d23c8307) | Jul 16, 2022 |
| HP            | Pavilion g6                 | Notebook    | [556c813157](https://linux-hardware.org/?probe=556c813157) | Jul 16, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9c06bd996b](https://linux-hardware.org/?probe=9c06bd996b) | Jul 15, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9e71693839](https://linux-hardware.org/?probe=9e71693839) | Jul 15, 2022 |
| ASUSTek       | Zenbook UX3402ZA_UX3402Z... | Convertible | [95b0d6d487](https://linux-hardware.org/?probe=95b0d6d487) | Jul 14, 2022 |
| HP            | 829E                        | Mini pc     | [27c2c68afb](https://linux-hardware.org/?probe=27c2c68afb) | Jul 13, 2022 |
| Jumper        | EZbook                      | Notebook    | [2515427610](https://linux-hardware.org/?probe=2515427610) | Jul 12, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ef6695e9f9](https://linux-hardware.org/?probe=ef6695e9f9) | Jul 12, 2022 |
| Acidanther... | Mac-27AD2F918AE68F61 Mac... | Desktop     | [fdae528732](https://linux-hardware.org/?probe=fdae528732) | Jul 12, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [ddd990405d](https://linux-hardware.org/?probe=ddd990405d) | Jul 11, 2022 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [e7b17323df](https://linux-hardware.org/?probe=e7b17323df) | Jul 10, 2022 |
| ASUSTek       | P5Q3                        | Desktop     | [5fb3e2b502](https://linux-hardware.org/?probe=5fb3e2b502) | Jul 10, 2022 |
| Lenovo        | ThinkPad X1 Yoga 3rd 20L... | Convertible | [c29a7cd884](https://linux-hardware.org/?probe=c29a7cd884) | Jul 09, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [d8f1865db2](https://linux-hardware.org/?probe=d8f1865db2) | Jul 08, 2022 |
| Lenovo        | ThinkPad T14 Gen 1 20UD0... | Notebook    | [42cc0cf38e](https://linux-hardware.org/?probe=42cc0cf38e) | Jul 07, 2022 |
| ASUSTek       | PRIME B550-PLUS             | Desktop     | [3a20826dbb](https://linux-hardware.org/?probe=3a20826dbb) | Jul 06, 2022 |
| Purism        | Librem 15 v3                | Notebook    | [1e39d0bba8](https://linux-hardware.org/?probe=1e39d0bba8) | Jul 06, 2022 |
| Dell          | XPS 15 9570                 | Notebook    | [2311c99a80](https://linux-hardware.org/?probe=2311c99a80) | Jul 06, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [e7c2f09e51](https://linux-hardware.org/?probe=e7c2f09e51) | Jul 05, 2022 |
| Dell          | Inspiron 7306 2n1           | Convertible | [6512ee623f](https://linux-hardware.org/?probe=6512ee623f) | Jul 05, 2022 |
| Multilaser    | PC150                       | Notebook    | [b6fcf6d507](https://linux-hardware.org/?probe=b6fcf6d507) | Jul 04, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [6cbbc0b707](https://linux-hardware.org/?probe=6cbbc0b707) | Jul 03, 2022 |
| Lenovo        | K14 Gen 1 21CUS02600        | Notebook    | [80fbf3aee4](https://linux-hardware.org/?probe=80fbf3aee4) | Jul 02, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [9de0586493](https://linux-hardware.org/?probe=9de0586493) | Jul 01, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [153a698b74](https://linux-hardware.org/?probe=153a698b74) | Jul 01, 2022 |
| TUXEDO        | Pulse 15 Gen1               | Notebook    | [8c7b7c1b45](https://linux-hardware.org/?probe=8c7b7c1b45) | Jul 01, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [97dfd06a92](https://linux-hardware.org/?probe=97dfd06a92) | Jul 01, 2022 |
| HP            | 829E                        | Mini pc     | [91fee1441e](https://linux-hardware.org/?probe=91fee1441e) | Jul 01, 2022 |
| Lenovo        | 312D NOK                    | Mini pc     | [e46c1314b2](https://linux-hardware.org/?probe=e46c1314b2) | Jul 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [bec2a7697f](https://linux-hardware.org/?probe=bec2a7697f) | Jun 30, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [bde570c9f5](https://linux-hardware.org/?probe=bde570c9f5) | Jun 30, 2022 |
| HP            | ENVY TS 17                  | Notebook    | [7b5d021513](https://linux-hardware.org/?probe=7b5d021513) | Jun 29, 2022 |
| Framework     | Laptop                      | Notebook    | [d4cd42f3af](https://linux-hardware.org/?probe=d4cd42f3af) | Jun 28, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [a9ddf668c4](https://linux-hardware.org/?probe=a9ddf668c4) | Jun 28, 2022 |
| EVGA          | X299 FTW K                  | Desktop     | [2fac0d5ea2](https://linux-hardware.org/?probe=2fac0d5ea2) | Jun 28, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [2818c11c12](https://linux-hardware.org/?probe=2818c11c12) | Jun 28, 2022 |
| Dell          | 0J3C2F A03                  | Desktop     | [6f5f6a7417](https://linux-hardware.org/?probe=6f5f6a7417) | Jun 26, 2022 |
| Dell          | 0YNVJG A02                  | Desktop     | [e272328867](https://linux-hardware.org/?probe=e272328867) | Jun 26, 2022 |
| MSI           | Z87-G41 PC Mate             | Desktop     | [c73501602b](https://linux-hardware.org/?probe=c73501602b) | Jun 26, 2022 |
| HP            | ProBook x360 435 G8 Note... | Convertible | [8d5e06f168](https://linux-hardware.org/?probe=8d5e06f168) | Jun 26, 2022 |
| Dell          | 0YNVJG A02                  | Desktop     | [9a39e5ea0d](https://linux-hardware.org/?probe=9a39e5ea0d) | Jun 26, 2022 |
| Lenovo        | Yoga 9 14ITL5 82BG          | Convertible | [78a37e2d4c](https://linux-hardware.org/?probe=78a37e2d4c) | Jun 25, 2022 |
| ASUSTek       | ASUS EXPERTBOOK B1500CEA... | Notebook    | [f1b7197958](https://linux-hardware.org/?probe=f1b7197958) | Jun 25, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X321... | Notebook    | [d2925f529c](https://linux-hardware.org/?probe=d2925f529c) | Jun 25, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [a00111330b](https://linux-hardware.org/?probe=a00111330b) | Jun 24, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [c3c9ce7e40](https://linux-hardware.org/?probe=c3c9ce7e40) | Jun 23, 2022 |
| MSI           | PRO B660M-A DDR4            | Desktop     | [1d719d4b2d](https://linux-hardware.org/?probe=1d719d4b2d) | Jun 23, 2022 |
| HP            | Pavilion Laptop 14-bf0xx    | Notebook    | [9a2d492e07](https://linux-hardware.org/?probe=9a2d492e07) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [d98df1e3c5](https://linux-hardware.org/?probe=d98df1e3c5) | Jun 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [8adbb8b56a](https://linux-hardware.org/?probe=8adbb8b56a) | Jun 22, 2022 |
| Apple         | MacBook5,1                  | Notebook    | [28147965c3](https://linux-hardware.org/?probe=28147965c3) | Jun 21, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [520f9b42b8](https://linux-hardware.org/?probe=520f9b42b8) | Jun 20, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [ff63b72fd2](https://linux-hardware.org/?probe=ff63b72fd2) | Jun 19, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [3bc36209d6](https://linux-hardware.org/?probe=3bc36209d6) | Jun 19, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [b9c65b6182](https://linux-hardware.org/?probe=b9c65b6182) | Jun 18, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [f51215fa91](https://linux-hardware.org/?probe=f51215fa91) | Jun 18, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3b177fe0af](https://linux-hardware.org/?probe=3b177fe0af) | Jun 17, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [83733f81bd](https://linux-hardware.org/?probe=83733f81bd) | Jun 17, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [3ec9bac70f](https://linux-hardware.org/?probe=3ec9bac70f) | Jun 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [cc0719c813](https://linux-hardware.org/?probe=cc0719c813) | Jun 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [52276b3971](https://linux-hardware.org/?probe=52276b3971) | Jun 16, 2022 |
| Clevo         | P7xxTM(1)                   | Notebook    | [48afb16c13](https://linux-hardware.org/?probe=48afb16c13) | Jun 16, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [74770880f9](https://linux-hardware.org/?probe=74770880f9) | Jun 15, 2022 |
| Apple         | MacBook7,1                  | Notebook    | [f14133e69e](https://linux-hardware.org/?probe=f14133e69e) | Jun 14, 2022 |
| Dell          | Inspiron 5400 2n1           | Convertible | [1908660d1a](https://linux-hardware.org/?probe=1908660d1a) | Jun 13, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [bde09cf3b5](https://linux-hardware.org/?probe=bde09cf3b5) | Jun 13, 2022 |
| MSI           | Raider GE76 12UH            | Notebook    | [c29e79e22d](https://linux-hardware.org/?probe=c29e79e22d) | Jun 12, 2022 |
| MSI           | Raider GE76 12UH            | Notebook    | [02e4c63249](https://linux-hardware.org/?probe=02e4c63249) | Jun 12, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [a1069bbb9d](https://linux-hardware.org/?probe=a1069bbb9d) | Jun 12, 2022 |
| HP            | ZBook Fury 15.6 inch G8 ... | Notebook    | [fd45495f2a](https://linux-hardware.org/?probe=fd45495f2a) | Jun 12, 2022 |
| HP            | 2129                        | Desktop     | [1e716f8086](https://linux-hardware.org/?probe=1e716f8086) | Jun 12, 2022 |
| HP            | 2129                        | Desktop     | [ad6f94da2e](https://linux-hardware.org/?probe=ad6f94da2e) | Jun 11, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [bca7de0216](https://linux-hardware.org/?probe=bca7de0216) | Jun 11, 2022 |
| HP            | Mini 210-1000               | Notebook    | [8746b5b684](https://linux-hardware.org/?probe=8746b5b684) | Jun 10, 2022 |
| MSI           | Z87-G45 GAMING              | Desktop     | [53877eebd1](https://linux-hardware.org/?probe=53877eebd1) | Jun 10, 2022 |
| HP            | 87C3                        | Desktop     | [1383f85e70](https://linux-hardware.org/?probe=1383f85e70) | Jun 09, 2022 |
| HP            | Mini 210-1000               | Notebook    | [65b65f1319](https://linux-hardware.org/?probe=65b65f1319) | Jun 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [06e496124a](https://linux-hardware.org/?probe=06e496124a) | Jun 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [fd421da52b](https://linux-hardware.org/?probe=fd421da52b) | Jun 08, 2022 |
| Samsung       | 935XDB                      | Notebook    | [497a2424e0](https://linux-hardware.org/?probe=497a2424e0) | Jun 07, 2022 |
| Samsung       | 935XDB                      | Notebook    | [3cde44fcf1](https://linux-hardware.org/?probe=3cde44fcf1) | Jun 07, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [0970e891ee](https://linux-hardware.org/?probe=0970e891ee) | Jun 07, 2022 |
| Apple         | MacBookPro5,5               | Notebook    | [3b33a1b625](https://linux-hardware.org/?probe=3b33a1b625) | Jun 07, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [325cde32e5](https://linux-hardware.org/?probe=325cde32e5) | Jun 06, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [6abee365c1](https://linux-hardware.org/?probe=6abee365c1) | Jun 06, 2022 |
| Lenovo        | ThinkPad X1 Yoga 4th 20Q... | Convertible | [8f496dbb19](https://linux-hardware.org/?probe=8f496dbb19) | Jun 06, 2022 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [5a7eff8826](https://linux-hardware.org/?probe=5a7eff8826) | Jun 06, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [b4b4831c86](https://linux-hardware.org/?probe=b4b4831c86) | Jun 05, 2022 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [fab0ffc01e](https://linux-hardware.org/?probe=fab0ffc01e) | Jun 03, 2022 |
| Gigabyte      | B450 AORUS PRO WIFI-CF      | Desktop     | [c50bbae3e1](https://linux-hardware.org/?probe=c50bbae3e1) | Jun 02, 2022 |
| Dell          | 0YNVJG A02                  | Desktop     | [9b84f171eb](https://linux-hardware.org/?probe=9b84f171eb) | Jun 01, 2022 |
| ASUSTek       | G771JW                      | Notebook    | [b6c03572a0](https://linux-hardware.org/?probe=b6c03572a0) | May 31, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [aae8744a5c](https://linux-hardware.org/?probe=aae8744a5c) | May 31, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0020802901](https://linux-hardware.org/?probe=0020802901) | May 30, 2022 |
| ASUSTek       | ROG Strix G513QY_G513QY     | Notebook    | [50927f5cae](https://linux-hardware.org/?probe=50927f5cae) | May 30, 2022 |
| ASUSTek       | ROG STRIX Z690-A GAMING ... | Desktop     | [11882c80d6](https://linux-hardware.org/?probe=11882c80d6) | May 30, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [7fe5175e37](https://linux-hardware.org/?probe=7fe5175e37) | May 30, 2022 |
| HP            | 212B                        | Desktop     | [f651b20f02](https://linux-hardware.org/?probe=f651b20f02) | May 30, 2022 |
| Dell          | Latitude 7320               | Notebook    | [63c6f252ab](https://linux-hardware.org/?probe=63c6f252ab) | May 30, 2022 |
| Lenovo        | Yoga 910-13IKB 80VF         | Convertible | [7167a72758](https://linux-hardware.org/?probe=7167a72758) | May 30, 2022 |
| Gigabyte      | X570 AORUS MASTER           | Desktop     | [91508b9375](https://linux-hardware.org/?probe=91508b9375) | May 29, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [e2e854cde1](https://linux-hardware.org/?probe=e2e854cde1) | May 28, 2022 |
| MSI           | PRO Z690-A DDR4             | Desktop     | [b9f38d3572](https://linux-hardware.org/?probe=b9f38d3572) | May 28, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [640f9226a1](https://linux-hardware.org/?probe=640f9226a1) | May 26, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [ea24b77e94](https://linux-hardware.org/?probe=ea24b77e94) | May 25, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [66b453536a](https://linux-hardware.org/?probe=66b453536a) | May 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [8dcce6eadb](https://linux-hardware.org/?probe=8dcce6eadb) | May 24, 2022 |
| HP            | EliteBook 855 G8 Noteboo... | Notebook    | [86242183ee](https://linux-hardware.org/?probe=86242183ee) | May 24, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [401023c3b3](https://linux-hardware.org/?probe=401023c3b3) | May 24, 2022 |
| Lenovo        | ThinkBook 16p Gen 2 20YM    | Notebook    | [f2c3a907b7](https://linux-hardware.org/?probe=f2c3a907b7) | May 24, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [0fe6809527](https://linux-hardware.org/?probe=0fe6809527) | May 20, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [54f43d3430](https://linux-hardware.org/?probe=54f43d3430) | May 20, 2022 |
| HP            | 8591                        | Desktop     | [60c5d4f8ca](https://linux-hardware.org/?probe=60c5d4f8ca) | May 19, 2022 |
| HP            | EliteBook 840 G4            | Notebook    | [2864dc6f0a](https://linux-hardware.org/?probe=2864dc6f0a) | May 19, 2022 |
| HP            | 2820h                       | Desktop     | [af311c3a41](https://linux-hardware.org/?probe=af311c3a41) | May 18, 2022 |
| Dell          | Latitude 5430 Rugged        | Notebook    | [c32e65738e](https://linux-hardware.org/?probe=c32e65738e) | May 18, 2022 |
| HP            | 8591                        | Desktop     | [fd05ae27e7](https://linux-hardware.org/?probe=fd05ae27e7) | May 18, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [d1575ec23a](https://linux-hardware.org/?probe=d1575ec23a) | May 17, 2022 |
| HP            | 250 G3                      | Notebook    | [73dbcb9953](https://linux-hardware.org/?probe=73dbcb9953) | May 17, 2022 |
| HP            | 250 G3                      | Notebook    | [a12d6710cf](https://linux-hardware.org/?probe=a12d6710cf) | May 16, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [0f70996b58](https://linux-hardware.org/?probe=0f70996b58) | May 15, 2022 |
| HP            | 81B7 1001                   | All in one  | [d99babe70f](https://linux-hardware.org/?probe=d99babe70f) | May 15, 2022 |
| Dell          | 03V7GF A00                  | Desktop     | [1be2673e23](https://linux-hardware.org/?probe=1be2673e23) | May 14, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [e01bfd360d](https://linux-hardware.org/?probe=e01bfd360d) | May 14, 2022 |
| Lenovo        | ThinkPad T470 W10DG 20JN... | Notebook    | [5fad688f56](https://linux-hardware.org/?probe=5fad688f56) | May 14, 2022 |
| Apple         | Mac-942B59F58194171B iMa... | All in one  | [b31c3ee2d6](https://linux-hardware.org/?probe=b31c3ee2d6) | May 14, 2022 |
| Lenovo        | ThinkPad T470 20HES1RB06    | Notebook    | [0d115ce977](https://linux-hardware.org/?probe=0d115ce977) | May 14, 2022 |
| Notebook      | NB50TJ1_TK1                 | Notebook    | [8789da25ba](https://linux-hardware.org/?probe=8789da25ba) | May 14, 2022 |
| Gigabyte      | B450M DS3H V2               | Desktop     | [3e9f067939](https://linux-hardware.org/?probe=3e9f067939) | May 13, 2022 |
| Lenovo        | Yoga C640-13IML 81UE        | Convertible | [07e54c3c41](https://linux-hardware.org/?probe=07e54c3c41) | May 12, 2022 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [2e8f888ca3](https://linux-hardware.org/?probe=2e8f888ca3) | May 11, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [4142d08db8](https://linux-hardware.org/?probe=4142d08db8) | May 11, 2022 |
| ASUSTek       | ASUS BR1100CKA BR1100CKA... | Notebook    | [74d92cc46f](https://linux-hardware.org/?probe=74d92cc46f) | May 11, 2022 |
| LG Electro... | 15Z995-U.ARS5U1             | Notebook    | [4efbc907db](https://linux-hardware.org/?probe=4efbc907db) | May 11, 2022 |
| Positivo      | DA18HV1 POSITIVO            | Desktop     | [9d5e3583e2](https://linux-hardware.org/?probe=9d5e3583e2) | May 11, 2022 |
| Gigabyte      | B560 HD3                    | Desktop     | [34fd3f60c4](https://linux-hardware.org/?probe=34fd3f60c4) | May 11, 2022 |
| Dell          | 0XNJ2Y A00                  | Desktop     | [52e1e36724](https://linux-hardware.org/?probe=52e1e36724) | May 11, 2022 |
| HP            | ENVY Laptop 13-ba1xxx       | Notebook    | [2591f59c80](https://linux-hardware.org/?probe=2591f59c80) | May 11, 2022 |
| EVGA          | 132-YW-E178-FTW 1           | Desktop     | [f9b1fe2224](https://linux-hardware.org/?probe=f9b1fe2224) | May 10, 2022 |
| ASUSTek       | TUF Gaming B560M-PLUS       | Desktop     | [2091818d85](https://linux-hardware.org/?probe=2091818d85) | May 10, 2022 |
| Sony          | VPCF23S1E                   | Notebook    | [5eb4b61ffb](https://linux-hardware.org/?probe=5eb4b61ffb) | May 10, 2022 |
| Lenovo        | ThinkPad E15 Gen 3 20YGC... | Notebook    | [b1d92dcb4e](https://linux-hardware.org/?probe=b1d92dcb4e) | May 10, 2022 |
| HP            | Notebook                    | Notebook    | [afe98a811e](https://linux-hardware.org/?probe=afe98a811e) | May 10, 2022 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [d2b0694da5](https://linux-hardware.org/?probe=d2b0694da5) | May 10, 2022 |
| Gigabyte      | X99P-SLI-CF                 | Desktop     | [0bec73d852](https://linux-hardware.org/?probe=0bec73d852) | May 10, 2022 |
| Dell          | Latitude 7490               | Notebook    | [0069680215](https://linux-hardware.org/?probe=0069680215) | May 10, 2022 |
| Monster       | HUMA H4 V3.1                | Notebook    | [38372af132](https://linux-hardware.org/?probe=38372af132) | May 10, 2022 |
| Lenovo        | ThinkPad E555 20DH000WGE    | Notebook    | [75920152df](https://linux-hardware.org/?probe=75920152df) | May 10, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [feafca0464](https://linux-hardware.org/?probe=feafca0464) | May 10, 2022 |
| Clevo         | P7xxTM(1)                   | Notebook    | [fdebb20557](https://linux-hardware.org/?probe=fdebb20557) | May 10, 2022 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [fe92976577](https://linux-hardware.org/?probe=fe92976577) | May 10, 2022 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [730c246f44](https://linux-hardware.org/?probe=730c246f44) | May 10, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ace8669bdd](https://linux-hardware.org/?probe=ace8669bdd) | May 10, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [99078d316d](https://linux-hardware.org/?probe=99078d316d) | May 10, 2022 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [f60ba0abd7](https://linux-hardware.org/?probe=f60ba0abd7) | May 10, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [9a7b248f26](https://linux-hardware.org/?probe=9a7b248f26) | May 10, 2022 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [bf8ea76f0a](https://linux-hardware.org/?probe=bf8ea76f0a) | May 10, 2022 |
| HP            | EliteBook 820 G3            | Notebook    | [015ede2e58](https://linux-hardware.org/?probe=015ede2e58) | May 09, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | Notebook    | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| Clevo         | W55xEU                      | Notebook    | [7bdef594e1](https://linux-hardware.org/?probe=7bdef594e1) | May 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [a3c1257116](https://linux-hardware.org/?probe=a3c1257116) | May 09, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [8caf6e2b66](https://linux-hardware.org/?probe=8caf6e2b66) | May 09, 2022 |
| ASRock        | AB350 Pro4                  | Desktop     | [fdc78a778b](https://linux-hardware.org/?probe=fdc78a778b) | May 09, 2022 |
| Gigabyte      | Z87X-D3H-CF                 | Desktop     | [4242d236c5](https://linux-hardware.org/?probe=4242d236c5) | May 09, 2022 |
| ASRock        | H97 Pro4                    | Desktop     | [cc42e8d5e5](https://linux-hardware.org/?probe=cc42e8d5e5) | May 09, 2022 |
| HP            | Pavilion dv6                | Notebook    | [165c15d078](https://linux-hardware.org/?probe=165c15d078) | May 09, 2022 |
| ASRock        | A88M-G                      | Desktop     | [d67df6ff7d](https://linux-hardware.org/?probe=d67df6ff7d) | May 09, 2022 |
| MSI           | B450M MORTAR TITANIUM       | Desktop     | [56c5f8cad8](https://linux-hardware.org/?probe=56c5f8cad8) | May 09, 2022 |
| HP            | ZHAN 66 Pro 14 G4 Notebo... | Notebook    | [f0b122c199](https://linux-hardware.org/?probe=f0b122c199) | May 09, 2022 |
| Gigabyte      | Z390 AORUS MASTER-CF        | Desktop     | [b438c97dca](https://linux-hardware.org/?probe=b438c97dca) | May 09, 2022 |
| TUXEDO        | InfinityBook S 15 Gen6      | Notebook    | [cc53668d3f](https://linux-hardware.org/?probe=cc53668d3f) | May 09, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [bdfe0722a7](https://linux-hardware.org/?probe=bdfe0722a7) | May 09, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [de90425a28](https://linux-hardware.org/?probe=de90425a28) | May 09, 2022 |
| ASUSTek       | P8B75-V                     | Desktop     | [b4ecefaba5](https://linux-hardware.org/?probe=b4ecefaba5) | May 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [27b384c114](https://linux-hardware.org/?probe=27b384c114) | May 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [d427368abd](https://linux-hardware.org/?probe=d427368abd) | May 08, 2022 |
| HP            | Pavilion 13 x360 PC         | Notebook    | [78b977ea42](https://linux-hardware.org/?probe=78b977ea42) | May 07, 2022 |
| Samsung       | 550XDA                      | Notebook    | [a616d83a41](https://linux-hardware.org/?probe=a616d83a41) | May 07, 2022 |
| Gigabyte      | X58A-UD3R                   | Desktop     | [0c05fbff9c](https://linux-hardware.org/?probe=0c05fbff9c) | May 07, 2022 |
| Apple         | MacBookPro9,2               | Notebook    | [e281a8eee2](https://linux-hardware.org/?probe=e281a8eee2) | May 06, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [622ff28b28](https://linux-hardware.org/?probe=622ff28b28) | May 05, 2022 |
| ASUSTek       | X540LJ                      | Notebook    | [74341c3077](https://linux-hardware.org/?probe=74341c3077) | May 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [220979cd04](https://linux-hardware.org/?probe=220979cd04) | May 05, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [c275c52e93](https://linux-hardware.org/?probe=c275c52e93) | May 04, 2022 |
| HP            | EliteBook 2560p             | Notebook    | [799038a9eb](https://linux-hardware.org/?probe=799038a9eb) | May 04, 2022 |
| Gigabyte      | B550 AORUS PRO V2           | Desktop     | [699a7ea54b](https://linux-hardware.org/?probe=699a7ea54b) | May 04, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [e5a11e0fdd](https://linux-hardware.org/?probe=e5a11e0fdd) | May 04, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [34dcc7bc0c](https://linux-hardware.org/?probe=34dcc7bc0c) | May 04, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [aea37c880d](https://linux-hardware.org/?probe=aea37c880d) | May 04, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [899a0e8999](https://linux-hardware.org/?probe=899a0e8999) | May 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS0VV0C     | Notebook    | [4ce87e4da1](https://linux-hardware.org/?probe=4ce87e4da1) | May 04, 2022 |
| ASRock        | Z390 Extreme4               | Desktop     | [344c43c31a](https://linux-hardware.org/?probe=344c43c31a) | May 04, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [584ec1055a](https://linux-hardware.org/?probe=584ec1055a) | May 03, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [2e4fdc00b2](https://linux-hardware.org/?probe=2e4fdc00b2) | May 03, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [10eb959775](https://linux-hardware.org/?probe=10eb959775) | Apr 30, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [89def966af](https://linux-hardware.org/?probe=89def966af) | Apr 30, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [9b128bc47e](https://linux-hardware.org/?probe=9b128bc47e) | Apr 30, 2022 |
| PCWare        | IPX4105G Pro                | Desktop     | [073d789fc4](https://linux-hardware.org/?probe=073d789fc4) | Apr 29, 2022 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [e168087bf0](https://linux-hardware.org/?probe=e168087bf0) | Apr 28, 2022 |
| Fujitsu       | LIFEBOOK S762               | Notebook    | [c258235d05](https://linux-hardware.org/?probe=c258235d05) | Apr 28, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [0b88a7422d](https://linux-hardware.org/?probe=0b88a7422d) | Apr 28, 2022 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [c07e06f794](https://linux-hardware.org/?probe=c07e06f794) | Apr 27, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [127862c3f7](https://linux-hardware.org/?probe=127862c3f7) | Apr 27, 2022 |
| ASUSTek       | Z170-A                      | Desktop     | [e2461ef9a7](https://linux-hardware.org/?probe=e2461ef9a7) | Apr 27, 2022 |
| Acer          | Aspire 3810TZ               | Notebook    | [cba19ea352](https://linux-hardware.org/?probe=cba19ea352) | Apr 27, 2022 |
| Lenovo        | IdeaPad 330-15IKB 81FE      | Notebook    | [593ee8ccf3](https://linux-hardware.org/?probe=593ee8ccf3) | Apr 27, 2022 |
| Lenovo        | ThinkPad X201 Tablet 083... | Notebook    | [e3ece9d899](https://linux-hardware.org/?probe=e3ece9d899) | Apr 26, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [981d5e03b3](https://linux-hardware.org/?probe=981d5e03b3) | Apr 25, 2022 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [0b3a1039fb](https://linux-hardware.org/?probe=0b3a1039fb) | Apr 25, 2022 |
| Acer          | TravelMate Spin P614RN-5... | Convertible | [5850b85224](https://linux-hardware.org/?probe=5850b85224) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [44c8507975](https://linux-hardware.org/?probe=44c8507975) | Apr 24, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [19ef63f944](https://linux-hardware.org/?probe=19ef63f944) | Apr 24, 2022 |
| Lenovo        | Yoga 730-15IKB 81CU         | Convertible | [26727e92e4](https://linux-hardware.org/?probe=26727e92e4) | Apr 22, 2022 |
| Dell          | 0X9M3X A01                  | Desktop     | [29a508398a](https://linux-hardware.org/?probe=29a508398a) | Apr 22, 2022 |
| Acer          | Veriton M2631 V:1.0         | Desktop     | [4f27720e96](https://linux-hardware.org/?probe=4f27720e96) | Apr 21, 2022 |
| Acer          | Extensa 2519                | Notebook    | [ae1a90a282](https://linux-hardware.org/?probe=ae1a90a282) | Apr 21, 2022 |
| HP            | Notebook                    | Notebook    | [65e86d0311](https://linux-hardware.org/?probe=65e86d0311) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [4521315d14](https://linux-hardware.org/?probe=4521315d14) | Apr 21, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [fff2447e5a](https://linux-hardware.org/?probe=fff2447e5a) | Apr 21, 2022 |
| Lenovo        | ThinkPad L420 7829BH2       | Notebook    | [726f69890c](https://linux-hardware.org/?probe=726f69890c) | Apr 17, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [f4151908bf](https://linux-hardware.org/?probe=f4151908bf) | Apr 17, 2022 |
| ASRock        | H110M-DVS R2.0              | Desktop     | [aa88339957](https://linux-hardware.org/?probe=aa88339957) | Apr 16, 2022 |
| Lenovo        | SHARKBAY 0B98401 WIN        | Desktop     | [90486ad164](https://linux-hardware.org/?probe=90486ad164) | Apr 15, 2022 |
| HP            | 17E2                        | Mini pc     | [a7bb99026f](https://linux-hardware.org/?probe=a7bb99026f) | Apr 15, 2022 |
| Lenovo        | ThinkPad X13 Gen 1 20UGS... | Notebook    | [80572def69](https://linux-hardware.org/?probe=80572def69) | Apr 14, 2022 |
| Lenovo        | IdeaPad 320-15ABR 80XS      | Notebook    | [b80dc08588](https://linux-hardware.org/?probe=b80dc08588) | Apr 14, 2022 |
| MSI           | MAG B550M MORTAR WIFI       | Desktop     | [191880e24b](https://linux-hardware.org/?probe=191880e24b) | Apr 14, 2022 |
| Dell          | System Inspiron N7110       | Notebook    | [aa67c47f23](https://linux-hardware.org/?probe=aa67c47f23) | Apr 13, 2022 |
| Intel         | D54250WYK H13922-303        | Desktop     | [8619f35452](https://linux-hardware.org/?probe=8619f35452) | Apr 13, 2022 |
| Dell          | Precision 5530              | Notebook    | [3c4cc67cc4](https://linux-hardware.org/?probe=3c4cc67cc4) | Apr 13, 2022 |
| HP            | OMEN by Laptop              | Notebook    | [3775d7e528](https://linux-hardware.org/?probe=3775d7e528) | Apr 13, 2022 |
| ASRock        | H170M Pro4                  | Desktop     | [a8bd162bf1](https://linux-hardware.org/?probe=a8bd162bf1) | Apr 13, 2022 |
| MSI           | B450M PRO-M2 MAX            | Desktop     | [0fc2a352ab](https://linux-hardware.org/?probe=0fc2a352ab) | Apr 13, 2022 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [27cda229cc](https://linux-hardware.org/?probe=27cda229cc) | Apr 12, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [34fa61f6bd](https://linux-hardware.org/?probe=34fa61f6bd) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [a5837a7f35](https://linux-hardware.org/?probe=a5837a7f35) | Apr 11, 2022 |
| MSI           | Modern 15 A4M               | Notebook    | [085aa2eabf](https://linux-hardware.org/?probe=085aa2eabf) | Apr 10, 2022 |
| Lenovo        | ThinkPad T460 20FMS25902    | Notebook    | [8645c57fcc](https://linux-hardware.org/?probe=8645c57fcc) | Apr 09, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [00d95f7a3a](https://linux-hardware.org/?probe=00d95f7a3a) | Apr 09, 2022 |
| Toshiba       | Satellite C55Dt-B           | Notebook    | [7e54067e6a](https://linux-hardware.org/?probe=7e54067e6a) | Apr 08, 2022 |
| Toshiba       | Satellite C55Dt-B           | Notebook    | [c40867ec67](https://linux-hardware.org/?probe=c40867ec67) | Apr 08, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [9a2939bd71](https://linux-hardware.org/?probe=9a2939bd71) | Apr 08, 2022 |
| Lenovo        | ThinkPad T460 20FMS25902    | Notebook    | [ff290845fe](https://linux-hardware.org/?probe=ff290845fe) | Apr 08, 2022 |
| ASUSTek       | N551JW                      | Notebook    | [3ddfbf37e2](https://linux-hardware.org/?probe=3ddfbf37e2) | Apr 08, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X435... | Notebook    | [d49b3ef408](https://linux-hardware.org/?probe=d49b3ef408) | Apr 08, 2022 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [a00c0b503b](https://linux-hardware.org/?probe=a00c0b503b) | Apr 06, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [652cd5fc07](https://linux-hardware.org/?probe=652cd5fc07) | Apr 06, 2022 |
| MSI           | B350M MORTAR ARCTIC         | Desktop     | [cf7f6c5ed4](https://linux-hardware.org/?probe=cf7f6c5ed4) | Apr 05, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [191c569aa7](https://linux-hardware.org/?probe=191c569aa7) | Apr 05, 2022 |
| HP            | 0A9Ch                       | Desktop     | [5a415a150f](https://linux-hardware.org/?probe=5a415a150f) | Apr 05, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [eec98977a3](https://linux-hardware.org/?probe=eec98977a3) | Apr 05, 2022 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [065554d2ad](https://linux-hardware.org/?probe=065554d2ad) | Apr 04, 2022 |
| Acer          | TravelMate P215-41-G2       | Notebook    | [4e35add210](https://linux-hardware.org/?probe=4e35add210) | Apr 04, 2022 |
| Shuttle       | FS35V4                      | Desktop     | [bfe34cde0c](https://linux-hardware.org/?probe=bfe34cde0c) | Apr 04, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [c1419a6f3c](https://linux-hardware.org/?probe=c1419a6f3c) | Apr 03, 2022 |
| Gigabyte      | GA-880GM-UD2H               | Desktop     | [0fd3382ba7](https://linux-hardware.org/?probe=0fd3382ba7) | Apr 02, 2022 |
| Supermicro    | X9DRi-LN4+/X9DR3-LN4+       | Desktop     | [eedbf6a10e](https://linux-hardware.org/?probe=eedbf6a10e) | Apr 02, 2022 |
| Itautec       | SM 3330 SM-3330 Padrao 0... | Desktop     | [47e5e82b88](https://linux-hardware.org/?probe=47e5e82b88) | Apr 01, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [ff7f2845b0](https://linux-hardware.org/?probe=ff7f2845b0) | Apr 01, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [6eb9c66f7d](https://linux-hardware.org/?probe=6eb9c66f7d) | Mar 31, 2022 |
| Gigabyte      | GA-770T-USB3                | Desktop     | [787cb334c2](https://linux-hardware.org/?probe=787cb334c2) | Mar 28, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [6fffff17df](https://linux-hardware.org/?probe=6fffff17df) | Mar 27, 2022 |
| Dell          | Precision 5540              | Notebook    | [26060f12a6](https://linux-hardware.org/?probe=26060f12a6) | Mar 27, 2022 |
| Lenovo        | ThinkPad E550 20DF0030US    | Notebook    | [8392d5c3fe](https://linux-hardware.org/?probe=8392d5c3fe) | Mar 27, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [4599ef9d23](https://linux-hardware.org/?probe=4599ef9d23) | Mar 26, 2022 |
| Gigabyte      | B550M AORUS ELITE           | Desktop     | [c1e113a82d](https://linux-hardware.org/?probe=c1e113a82d) | Mar 26, 2022 |
| Gigabyte      | X570 GAMING X               | Desktop     | [5c424251c8](https://linux-hardware.org/?probe=5c424251c8) | Mar 24, 2022 |
| Foxconn       | 2ADA                        | Desktop     | [b9aec6129a](https://linux-hardware.org/?probe=b9aec6129a) | Mar 23, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [4345817b16](https://linux-hardware.org/?probe=4345817b16) | Mar 23, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [3429bc98ac](https://linux-hardware.org/?probe=3429bc98ac) | Mar 22, 2022 |
| Colorful T... | A320M-K PRO YV14            | Desktop     | [94393a4d0a](https://linux-hardware.org/?probe=94393a4d0a) | Mar 22, 2022 |
| Pegatron      | 2AB6                        | Desktop     | [9e862658aa](https://linux-hardware.org/?probe=9e862658aa) | Mar 22, 2022 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [adce0625d3](https://linux-hardware.org/?probe=adce0625d3) | Mar 20, 2022 |
| Acer          | Swift SF314-43              | Notebook    | [b632c4a0c5](https://linux-hardware.org/?probe=b632c4a0c5) | Mar 20, 2022 |
| Acer          | Aspire E1-571               | Notebook    | [ef43a1dac3](https://linux-hardware.org/?probe=ef43a1dac3) | Mar 20, 2022 |
| Dell          | XPS 15 9560                 | Notebook    | [73734bbce5](https://linux-hardware.org/?probe=73734bbce5) | Mar 19, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QM... | Notebook    | [16b2681039](https://linux-hardware.org/?probe=16b2681039) | Mar 19, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [161ca16bc2](https://linux-hardware.org/?probe=161ca16bc2) | Mar 19, 2022 |
| ASUSTek       | ZenBook UX325SA_UM325SA     | Notebook    | [05c0be34be](https://linux-hardware.org/?probe=05c0be34be) | Mar 18, 2022 |
| Gigabyte      | B75M-D3H                    | Desktop     | [53ca03e8ec](https://linux-hardware.org/?probe=53ca03e8ec) | Mar 17, 2022 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [651e0fb5eb](https://linux-hardware.org/?probe=651e0fb5eb) | Mar 16, 2022 |
| ASRock        | Z370 Gaming K6              | Desktop     | [90bedd5ff6](https://linux-hardware.org/?probe=90bedd5ff6) | Mar 14, 2022 |
| Gigabyte      | W480 VISION D               | Desktop     | [2e45a56117](https://linux-hardware.org/?probe=2e45a56117) | Mar 14, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [704438d05e](https://linux-hardware.org/?probe=704438d05e) | Mar 13, 2022 |
| Acer          | Aspire A315-41              | Notebook    | [571547ee1d](https://linux-hardware.org/?probe=571547ee1d) | Mar 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [7ce09d403d](https://linux-hardware.org/?probe=7ce09d403d) | Mar 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [0d9c88498d](https://linux-hardware.org/?probe=0d9c88498d) | Mar 13, 2022 |
| MSI           | MEG X570 UNIFY              | Desktop     | [ec1783840e](https://linux-hardware.org/?probe=ec1783840e) | Mar 13, 2022 |
| Dell          | Latitude E7470              | Notebook    | [31b0bbe97f](https://linux-hardware.org/?probe=31b0bbe97f) | Mar 13, 2022 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | Desktop     | [ef67eef250](https://linux-hardware.org/?probe=ef67eef250) | Mar 13, 2022 |
| Microsoft     | Surface Book                | Tablet      | [00d499f50c](https://linux-hardware.org/?probe=00d499f50c) | Mar 13, 2022 |
| Lenovo        | Yoga 310-11IAP 80U2         | Convertible | [8ec8e7be46](https://linux-hardware.org/?probe=8ec8e7be46) | Mar 12, 2022 |
| ASRock        | H61M-S1 PLUS                | Desktop     | [56c15fcbf6](https://linux-hardware.org/?probe=56c15fcbf6) | Mar 12, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [2e7a87521b](https://linux-hardware.org/?probe=2e7a87521b) | Mar 12, 2022 |
| BESSTAR Te... | HM90                        | Desktop     | [a610ee6ad5](https://linux-hardware.org/?probe=a610ee6ad5) | Mar 12, 2022 |
| Dell          | Latitude 7480               | Notebook    | [cbff798f89](https://linux-hardware.org/?probe=cbff798f89) | Mar 11, 2022 |
| Dell          | Latitude 7480               | Notebook    | [02e748e3ac](https://linux-hardware.org/?probe=02e748e3ac) | Mar 11, 2022 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [c9b7431269](https://linux-hardware.org/?probe=c9b7431269) | Mar 10, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [f118a17b6e](https://linux-hardware.org/?probe=f118a17b6e) | Mar 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [dc2ae12852](https://linux-hardware.org/?probe=dc2ae12852) | Mar 07, 2022 |
| Unknown       | Unknown                     | Notebook    | [1b5e705cf1](https://linux-hardware.org/?probe=1b5e705cf1) | Mar 07, 2022 |
| Lenovo        | Yoga Slim 7 15IIL05 82AA    | Notebook    | [1eaa06bf11](https://linux-hardware.org/?probe=1eaa06bf11) | Mar 06, 2022 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [5a570f493c](https://linux-hardware.org/?probe=5a570f493c) | Mar 06, 2022 |
| Acer          | Swift SF314-59              | Notebook    | [d549055064](https://linux-hardware.org/?probe=d549055064) | Mar 05, 2022 |
| Gigabyte      | F2A68HM-DS2                 | Desktop     | [455f94f1d3](https://linux-hardware.org/?probe=455f94f1d3) | Mar 04, 2022 |
| Lenovo        | ThinkPad E580 20KS001RGE    | Notebook    | [4ccce94591](https://linux-hardware.org/?probe=4ccce94591) | Mar 03, 2022 |
| HP            | 2129                        | Desktop     | [a6b5f98b78](https://linux-hardware.org/?probe=a6b5f98b78) | Mar 02, 2022 |
| Gigabyte      | B550 AORUS PRO              | Desktop     | [37d07ec6df](https://linux-hardware.org/?probe=37d07ec6df) | Mar 02, 2022 |
| Dell          | 0M858N A01                  | Desktop     | [02b86c4d66](https://linux-hardware.org/?probe=02b86c4d66) | Mar 01, 2022 |
| HP            | 0B4Ch D                     | Desktop     | [dc25902f7e](https://linux-hardware.org/?probe=dc25902f7e) | Feb 28, 2022 |
| Dell          | XPS 15 9550                 | Notebook    | [f4a068f57c](https://linux-hardware.org/?probe=f4a068f57c) | Feb 27, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [fb656318f6](https://linux-hardware.org/?probe=fb656318f6) | Feb 27, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [2e3931f1fb](https://linux-hardware.org/?probe=2e3931f1fb) | Feb 26, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UH... | Notebook    | [f904e185fb](https://linux-hardware.org/?probe=f904e185fb) | Feb 25, 2022 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [b6dc38eb16](https://linux-hardware.org/?probe=b6dc38eb16) | Feb 25, 2022 |
| ASUSTek       | 1101HA                      | Notebook    | [f8f8968f19](https://linux-hardware.org/?probe=f8f8968f19) | Feb 22, 2022 |
| HP            | EliteBook 835 G8 Noteboo... | Notebook    | [4a18cd9a94](https://linux-hardware.org/?probe=4a18cd9a94) | Feb 22, 2022 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [cd61ef5a5d](https://linux-hardware.org/?probe=cd61ef5a5d) | Feb 20, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [100666467c](https://linux-hardware.org/?probe=100666467c) | Feb 20, 2022 |
| Lenovo        | ThinkPad L14 Gen 1 20U6S... | Notebook    | [450f779085](https://linux-hardware.org/?probe=450f779085) | Feb 20, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [362c220f2d](https://linux-hardware.org/?probe=362c220f2d) | Feb 20, 2022 |
| Gigabyte      | MKLP3AP-00                  | Mini pc     | [686b1350c9](https://linux-hardware.org/?probe=686b1350c9) | Feb 19, 2022 |
| Lenovo        | Yoga Slim 7 Pro 14ACH5 O... | Notebook    | [24ec19a092](https://linux-hardware.org/?probe=24ec19a092) | Feb 17, 2022 |
| MSI           | CX600                       | Notebook    | [bbd815a6e9](https://linux-hardware.org/?probe=bbd815a6e9) | Feb 17, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [983c62bf72](https://linux-hardware.org/?probe=983c62bf72) | Feb 17, 2022 |
| Teclast       | F5                          | Convertible | [ab28d730e6](https://linux-hardware.org/?probe=ab28d730e6) | Feb 15, 2022 |
| MSI           | A55M-P33                    | Desktop     | [31c0a9c67c](https://linux-hardware.org/?probe=31c0a9c67c) | Feb 15, 2022 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [47ff2c9673](https://linux-hardware.org/?probe=47ff2c9673) | Feb 15, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [e202260efb](https://linux-hardware.org/?probe=e202260efb) | Feb 14, 2022 |
| Dell          | Latitude E6410              | Notebook    | [787eacd33c](https://linux-hardware.org/?probe=787eacd33c) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [91d1953478](https://linux-hardware.org/?probe=91d1953478) | Feb 13, 2022 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [119cc6c1b1](https://linux-hardware.org/?probe=119cc6c1b1) | Feb 13, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [33abf3e568](https://linux-hardware.org/?probe=33abf3e568) | Feb 11, 2022 |
| Dell          | XPS 15 9510                 | Notebook    | [8c571a917d](https://linux-hardware.org/?probe=8c571a917d) | Feb 10, 2022 |
| Lenovo        | ThinkPad E590 20NB0012MX    | Notebook    | [92a33a8f31](https://linux-hardware.org/?probe=92a33a8f31) | Feb 10, 2022 |
| HP            | ENVY x360 Convertible 15... | Convertible | [c2729fb959](https://linux-hardware.org/?probe=c2729fb959) | Feb 10, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [95b53bcaf7](https://linux-hardware.org/?probe=95b53bcaf7) | Feb 08, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [70122a3cd0](https://linux-hardware.org/?probe=70122a3cd0) | Feb 07, 2022 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [34a6010fb2](https://linux-hardware.org/?probe=34a6010fb2) | Feb 07, 2022 |
| TUXEDO        | Stellaris Intel Gen3 (TG... | Notebook    | [8337edfc91](https://linux-hardware.org/?probe=8337edfc91) | Feb 07, 2022 |
| Gigabyte      | B550 VISION D-P             | Desktop     | [e995276798](https://linux-hardware.org/?probe=e995276798) | Feb 07, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [b3ff58ce92](https://linux-hardware.org/?probe=b3ff58ce92) | Feb 06, 2022 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [29ea90b598](https://linux-hardware.org/?probe=29ea90b598) | Feb 06, 2022 |
| Dell          | XPS 17 9710                 | Notebook    | [1b0a32e129](https://linux-hardware.org/?probe=1b0a32e129) | Feb 06, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [af586bb69e](https://linux-hardware.org/?probe=af586bb69e) | Feb 05, 2022 |
| Acer          | Nitro AN515-52              | Notebook    | [51a06ffad3](https://linux-hardware.org/?probe=51a06ffad3) | Feb 05, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [2f03547791](https://linux-hardware.org/?probe=2f03547791) | Feb 05, 2022 |
| Acer          | Aspire VN7-792G             | Notebook    | [20e910e73b](https://linux-hardware.org/?probe=20e910e73b) | Feb 05, 2022 |
| ASUSTek       | ZenBook S UX391UA           | Notebook    | [a19b0282f2](https://linux-hardware.org/?probe=a19b0282f2) | Feb 04, 2022 |
| HP            | 2B4B                        | Desktop     | [4205ceb454](https://linux-hardware.org/?probe=4205ceb454) | Feb 01, 2022 |
| Lenovo        | IdeaPad 3 14IML05 81WA      | Notebook    | [340ecf86ab](https://linux-hardware.org/?probe=340ecf86ab) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [1615c253fc](https://linux-hardware.org/?probe=1615c253fc) | Feb 01, 2022 |
| Apple         | MacBookPro8,1               | Notebook    | [0591806d5c](https://linux-hardware.org/?probe=0591806d5c) | Jan 31, 2022 |
| Corporativ... | MB40II5                     | Notebook    | [ba6bc223c3](https://linux-hardware.org/?probe=ba6bc223c3) | Jan 31, 2022 |
| HUAWEI        | KPL-W0X                     | Notebook    | [af71ad30ed](https://linux-hardware.org/?probe=af71ad30ed) | Jan 30, 2022 |
| HP            | Laptop 17-ca0xxx            | Notebook    | [373b062fd0](https://linux-hardware.org/?probe=373b062fd0) | Jan 30, 2022 |
| Corporativ... | MB40II5                     | Notebook    | [3c62692a0f](https://linux-hardware.org/?probe=3c62692a0f) | Jan 30, 2022 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [9cc991a921](https://linux-hardware.org/?probe=9cc991a921) | Jan 29, 2022 |
| Gigabyte      | Z87X-UD3H-CF                | Desktop     | [533df9d207](https://linux-hardware.org/?probe=533df9d207) | Jan 28, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [6423454dd8](https://linux-hardware.org/?probe=6423454dd8) | Jan 28, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [093d240f55](https://linux-hardware.org/?probe=093d240f55) | Jan 28, 2022 |
| HP            | Compaq 6830s                | Notebook    | [f82216de53](https://linux-hardware.org/?probe=f82216de53) | Jan 26, 2022 |
| HP            | Compaq 6830s                | Notebook    | [fe7ef8a290](https://linux-hardware.org/?probe=fe7ef8a290) | Jan 26, 2022 |
| Intel         | NUC8i7HVB J68196-504        | Mini pc     | [50b28ab929](https://linux-hardware.org/?probe=50b28ab929) | Jan 26, 2022 |
| MSI           | Pulse GL66 11UDK            | Notebook    | [06d5ba6ef3](https://linux-hardware.org/?probe=06d5ba6ef3) | Jan 26, 2022 |
| HP            | ProBook x360 435 G7         | Convertible | [cf7b776431](https://linux-hardware.org/?probe=cf7b776431) | Jan 24, 2022 |
| Getac         | V200-G2                     | Notebook    | [6d9b456d5f](https://linux-hardware.org/?probe=6d9b456d5f) | Jan 24, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [c07dc3a8ee](https://linux-hardware.org/?probe=c07dc3a8ee) | Jan 24, 2022 |
| ASUSTek       | SABERTOOTH 55i              | Desktop     | [5c67654acf](https://linux-hardware.org/?probe=5c67654acf) | Jan 23, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [7dbefa64bc](https://linux-hardware.org/?probe=7dbefa64bc) | Jan 23, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [394132a26d](https://linux-hardware.org/?probe=394132a26d) | Jan 22, 2022 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [3060acc083](https://linux-hardware.org/?probe=3060acc083) | Jan 22, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [170a3c500e](https://linux-hardware.org/?probe=170a3c500e) | Jan 21, 2022 |
| HUAWEI        | HKD-WXX                     | Notebook    | [a8eefb04f1](https://linux-hardware.org/?probe=a8eefb04f1) | Jan 21, 2022 |
| Lenovo        | IdeaPad S145-15IWL 81MV     | Notebook    | [d195d57aa4](https://linux-hardware.org/?probe=d195d57aa4) | Jan 21, 2022 |
| Sony          | VPCYB15AB                   | Notebook    | [1d7c8aa76a](https://linux-hardware.org/?probe=1d7c8aa76a) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [07b8344de7](https://linux-hardware.org/?probe=07b8344de7) | Jan 21, 2022 |
| Notebook      | PCx0Dx                      | Notebook    | [3bdae5c5ac](https://linux-hardware.org/?probe=3bdae5c5ac) | Jan 21, 2022 |
| Gigabyte      | B450 AORUS M                | Desktop     | [76ac118b42](https://linux-hardware.org/?probe=76ac118b42) | Jan 20, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [a30f5fabcd](https://linux-hardware.org/?probe=a30f5fabcd) | Jan 18, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [ea01dd4007](https://linux-hardware.org/?probe=ea01dd4007) | Jan 18, 2022 |
| Gigabyte      | G31M-S2C                    | Desktop     | [88d5bd947a](https://linux-hardware.org/?probe=88d5bd947a) | Jan 17, 2022 |
| ASRock        | B450M Pro4-F                | Desktop     | [f55512e3bc](https://linux-hardware.org/?probe=f55512e3bc) | Jan 17, 2022 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [31b2f44066](https://linux-hardware.org/?probe=31b2f44066) | Jan 17, 2022 |
| ASUSTek       | H81M-R                      | Desktop     | [cf10bab7ad](https://linux-hardware.org/?probe=cf10bab7ad) | Jan 17, 2022 |
| MSI           | P67A-C45                    | Desktop     | [953176b34f](https://linux-hardware.org/?probe=953176b34f) | Jan 17, 2022 |
| HP            | 18E5                        | Desktop     | [a06f3d3373](https://linux-hardware.org/?probe=a06f3d3373) | Jan 16, 2022 |
| Biostar       | H77MU3                      | Desktop     | [da779dbb31](https://linux-hardware.org/?probe=da779dbb31) | Jan 15, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [abf3b9c5c8](https://linux-hardware.org/?probe=abf3b9c5c8) | Jan 14, 2022 |
| ASUSTek       | H97M-E                      | Desktop     | [54fb155ee1](https://linux-hardware.org/?probe=54fb155ee1) | Jan 14, 2022 |
| Lenovo        | 3141 SDK0J40700 WIN 3258... | Desktop     | [6976b6ebbd](https://linux-hardware.org/?probe=6976b6ebbd) | Jan 14, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [6b15f755b0](https://linux-hardware.org/?probe=6b15f755b0) | Jan 12, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [894589da9f](https://linux-hardware.org/?probe=894589da9f) | Jan 11, 2022 |
| Toshiba       | Satellite C660D             | Notebook    | [99d2f2253d](https://linux-hardware.org/?probe=99d2f2253d) | Jan 11, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [cda49a0b67](https://linux-hardware.org/?probe=cda49a0b67) | Jan 10, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [4c9489e27a](https://linux-hardware.org/?probe=4c9489e27a) | Jan 10, 2022 |
| HP            | ProBook x360 11 G5 EE       | Convertible | [2000988c8b](https://linux-hardware.org/?probe=2000988c8b) | Jan 10, 2022 |
| HP            | ENVY 15                     | Notebook    | [30b86e16bf](https://linux-hardware.org/?probe=30b86e16bf) | Jan 10, 2022 |
| Razer         | Blade 15 Base Model (Mid... | Notebook    | [af7d37f35c](https://linux-hardware.org/?probe=af7d37f35c) | Jan 10, 2022 |
| HP            | 2B29                        | Desktop     | [cfb166f99c](https://linux-hardware.org/?probe=cfb166f99c) | Jan 10, 2022 |
| ASUSTek       | M5A99X EVO R2.0             | Desktop     | [980348cf8f](https://linux-hardware.org/?probe=980348cf8f) | Jan 09, 2022 |
| Dell          | Latitude XT2                | Notebook    | [65adc4cb22](https://linux-hardware.org/?probe=65adc4cb22) | Jan 09, 2022 |
| ASUSTek       | Z97-K                       | Desktop     | [87ffc81034](https://linux-hardware.org/?probe=87ffc81034) | Jan 08, 2022 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [85fc03c636](https://linux-hardware.org/?probe=85fc03c636) | Jan 08, 2022 |
| Chuwi         | Hi10 X                      | Tablet      | [5d8b5e0c8e](https://linux-hardware.org/?probe=5d8b5e0c8e) | Jan 07, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [4a33da1bc1](https://linux-hardware.org/?probe=4a33da1bc1) | Jan 06, 2022 |
| Notebook      | NL5xRU                      | Notebook    | [39b60e131a](https://linux-hardware.org/?probe=39b60e131a) | Jan 05, 2022 |
| Dell          | XPS 13 9343                 | Notebook    | [c7bf784225](https://linux-hardware.org/?probe=c7bf784225) | Jan 04, 2022 |
| Lenovo        | Yoga Slim 7 14ITL05 82A3    | Notebook    | [896b348390](https://linux-hardware.org/?probe=896b348390) | Jan 03, 2022 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [bfd3b013ad](https://linux-hardware.org/?probe=bfd3b013ad) | Jan 02, 2022 |
| MSI           | C847IS-P33                  | Desktop     | [1ea085e13d](https://linux-hardware.org/?probe=1ea085e13d) | Jan 02, 2022 |
| Toshiba       | AS 1301                     | Notebook    | [8617f80de9](https://linux-hardware.org/?probe=8617f80de9) | Jan 01, 2022 |
| TUXEDO        | Unknown                     | Notebook    | [6a29278e3f](https://linux-hardware.org/?probe=6a29278e3f) | Dec 31, 2021 |
| Dell          | 0RY007                      | Desktop     | [d51d13fdd1](https://linux-hardware.org/?probe=d51d13fdd1) | Dec 31, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [b29f429221](https://linux-hardware.org/?probe=b29f429221) | Dec 30, 2021 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [559c6e472e](https://linux-hardware.org/?probe=559c6e472e) | Dec 30, 2021 |
| Fujitsu       | LIFEBOOK E746               | Notebook    | [86da0c348f](https://linux-hardware.org/?probe=86da0c348f) | Dec 30, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [e9cf5c0353](https://linux-hardware.org/?probe=e9cf5c0353) | Dec 29, 2021 |
| Dell          | XPS 15 9510                 | Notebook    | [5f594735cc](https://linux-hardware.org/?probe=5f594735cc) | Dec 28, 2021 |
| Chuwi         | Hi10 X                      | Tablet      | [c152f8c702](https://linux-hardware.org/?probe=c152f8c702) | Dec 27, 2021 |
| Dell          | Studio 1737                 | Notebook    | [6b5362714f](https://linux-hardware.org/?probe=6b5362714f) | Dec 27, 2021 |
| MSI           | B450 GAMING PLUS MAX        | Desktop     | [5f62a9d831](https://linux-hardware.org/?probe=5f62a9d831) | Dec 26, 2021 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [81f1473127](https://linux-hardware.org/?probe=81f1473127) | Dec 26, 2021 |
| ASUSTek       | TUF Gaming FX705DY_FX705... | Notebook    | [e62e9c50d0](https://linux-hardware.org/?probe=e62e9c50d0) | Dec 26, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [a1b975a4e1](https://linux-hardware.org/?probe=a1b975a4e1) | Dec 26, 2021 |
| Notebook      | NL5xRU                      | Notebook    | [f74478e98e](https://linux-hardware.org/?probe=f74478e98e) | Dec 25, 2021 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [c2d30af3ce](https://linux-hardware.org/?probe=c2d30af3ce) | Dec 25, 2021 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [586e536e6c](https://linux-hardware.org/?probe=586e536e6c) | Dec 25, 2021 |
| Lenovo        | ThinkPad L512 44444WG       | Notebook    | [113b39ddbc](https://linux-hardware.org/?probe=113b39ddbc) | Dec 25, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [8b94542162](https://linux-hardware.org/?probe=8b94542162) | Dec 22, 2021 |
| Pegatron      | 2AE4                        | Desktop     | [491f8d7813](https://linux-hardware.org/?probe=491f8d7813) | Dec 21, 2021 |
| Gigabyte      | B460M DS3H AC               | Desktop     | [7bde1c408f](https://linux-hardware.org/?probe=7bde1c408f) | Dec 21, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [b2108dd133](https://linux-hardware.org/?probe=b2108dd133) | Dec 21, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [6f6aeab7c1](https://linux-hardware.org/?probe=6f6aeab7c1) | Dec 20, 2021 |
| Dell          | Inspiron N4030              | Notebook    | [f5b5166d80](https://linux-hardware.org/?probe=f5b5166d80) | Dec 20, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [1f86ef0f23](https://linux-hardware.org/?probe=1f86ef0f23) | Dec 19, 2021 |
| ASUSTek       | PRIME A320M-E               | Desktop     | [c008e360e7](https://linux-hardware.org/?probe=c008e360e7) | Dec 19, 2021 |
| MSI           | A55M-P33                    | Desktop     | [de87849301](https://linux-hardware.org/?probe=de87849301) | Dec 18, 2021 |
| ASUSTek       | P9X79 PRO                   | Desktop     | [ca4a106ccf](https://linux-hardware.org/?probe=ca4a106ccf) | Dec 18, 2021 |
| HP            | Pavilion dv6                | Notebook    | [bb01b911cd](https://linux-hardware.org/?probe=bb01b911cd) | Dec 17, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [1ff9d84c5f](https://linux-hardware.org/?probe=1ff9d84c5f) | Dec 17, 2021 |
| Google        | Pantheon                    | Notebook    | [8b1d8783ad](https://linux-hardware.org/?probe=8b1d8783ad) | Dec 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [8f1556eb30](https://linux-hardware.org/?probe=8f1556eb30) | Dec 17, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FD00... | Convertible | [b5a9d168a5](https://linux-hardware.org/?probe=b5a9d168a5) | Dec 17, 2021 |
| Lenovo        | ThinkPad E15 20RD0015UK     | Notebook    | [0fca0b679f](https://linux-hardware.org/?probe=0fca0b679f) | Dec 16, 2021 |
| Acer          | Aspire E1-571               | Notebook    | [27923678bd](https://linux-hardware.org/?probe=27923678bd) | Dec 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [a5ddb2410e](https://linux-hardware.org/?probe=a5ddb2410e) | Dec 16, 2021 |
| ASUSTek       | P8Z77-V LX                  | Desktop     | [e744dbe03d](https://linux-hardware.org/?probe=e744dbe03d) | Dec 15, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [85e65dae6a](https://linux-hardware.org/?probe=85e65dae6a) | Dec 15, 2021 |
| MSI           | FM2-A55M-E33                | Desktop     | [3ff4885854](https://linux-hardware.org/?probe=3ff4885854) | Dec 15, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [452044c67e](https://linux-hardware.org/?probe=452044c67e) | Dec 15, 2021 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [4dc9e683af](https://linux-hardware.org/?probe=4dc9e683af) | Dec 15, 2021 |
| Biostar       | X370GT5                     | Desktop     | [40849a76de](https://linux-hardware.org/?probe=40849a76de) | Dec 14, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [3ad9c4f3dc](https://linux-hardware.org/?probe=3ad9c4f3dc) | Dec 14, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [696d4a24cd](https://linux-hardware.org/?probe=696d4a24cd) | Dec 13, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [3d396a7f28](https://linux-hardware.org/?probe=3d396a7f28) | Dec 13, 2021 |
| HP            | Elite Dragonfly             | Convertible | [d25e8dec93](https://linux-hardware.org/?probe=d25e8dec93) | Dec 13, 2021 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [68bef1611d](https://linux-hardware.org/?probe=68bef1611d) | Dec 13, 2021 |
| ASUSTek       | P8Z68-V                     | Desktop     | [8febc9ddd7](https://linux-hardware.org/?probe=8febc9ddd7) | Dec 13, 2021 |
| HP            | ENVY x360 Convertible 15... | Convertible | [e2ed0c9dfd](https://linux-hardware.org/?probe=e2ed0c9dfd) | Dec 13, 2021 |
| Lenovo        | ThinkPad T14 Gen 1 20UES... | Notebook    | [ecc22ad350](https://linux-hardware.org/?probe=ecc22ad350) | Dec 12, 2021 |
| Dell          | Inspiron 15 3510            | Notebook    | [7d97420d98](https://linux-hardware.org/?probe=7d97420d98) | Dec 11, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [176194b06f](https://linux-hardware.org/?probe=176194b06f) | Dec 10, 2021 |
| Google        | Kip                         | Notebook    | [0e5291c891](https://linux-hardware.org/?probe=0e5291c891) | Dec 09, 2021 |
| Google        | Kip                         | Notebook    | [9bbfc62162](https://linux-hardware.org/?probe=9bbfc62162) | Dec 09, 2021 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [25179417ad](https://linux-hardware.org/?probe=25179417ad) | Dec 09, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [543d2dfef7](https://linux-hardware.org/?probe=543d2dfef7) | Dec 07, 2021 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [ff8706d7ac](https://linux-hardware.org/?probe=ff8706d7ac) | Dec 07, 2021 |
| HP            | 0A9Ch                       | Desktop     | [9bbd755279](https://linux-hardware.org/?probe=9bbd755279) | Dec 07, 2021 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | Notebook    | [4d4c80773b](https://linux-hardware.org/?probe=4d4c80773b) | Dec 07, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [dab30215a2](https://linux-hardware.org/?probe=dab30215a2) | Dec 05, 2021 |
| HP            | 2B4B                        | Desktop     | [efc81a48f3](https://linux-hardware.org/?probe=efc81a48f3) | Dec 05, 2021 |
| ASUSTek       | TUF Gaming B550M-ZAKU       | Desktop     | [7bb538c6f0](https://linux-hardware.org/?probe=7bb538c6f0) | Dec 05, 2021 |
| Acer          | Aspire A315-21              | Notebook    | [b6e4b7efdc](https://linux-hardware.org/?probe=b6e4b7efdc) | Dec 04, 2021 |
| Lenovo        | ThinkPad E495 20NE001GGE    | Notebook    | [31e9125d85](https://linux-hardware.org/?probe=31e9125d85) | Dec 03, 2021 |
| Lenovo        | ThinkPad E495 20NE001GGE    | Notebook    | [3b230e73b3](https://linux-hardware.org/?probe=3b230e73b3) | Dec 03, 2021 |
| Lenovo        | IdeaPad 5 14ARE05 81YM      | Notebook    | [7b1d555cc3](https://linux-hardware.org/?probe=7b1d555cc3) | Dec 03, 2021 |
| Lenovo        | B41-80 80LG                 | Notebook    | [96e84134f0](https://linux-hardware.org/?probe=96e84134f0) | Dec 03, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [00a3ad4abc](https://linux-hardware.org/?probe=00a3ad4abc) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [c68a7d50dc](https://linux-hardware.org/?probe=c68a7d50dc) | Dec 02, 2021 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [49055ba417](https://linux-hardware.org/?probe=49055ba417) | Dec 01, 2021 |
| Dell          | Vostro 5471                 | Notebook    | [3da13c5e1b](https://linux-hardware.org/?probe=3da13c5e1b) | Nov 30, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [8e84498214](https://linux-hardware.org/?probe=8e84498214) | Nov 30, 2021 |
| HP            | OMEN by Laptop              | Notebook    | [4dec490a3f](https://linux-hardware.org/?probe=4dec490a3f) | Nov 29, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [e4f4713ac2](https://linux-hardware.org/?probe=e4f4713ac2) | Nov 29, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [65ba69012d](https://linux-hardware.org/?probe=65ba69012d) | Nov 28, 2021 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [34898be259](https://linux-hardware.org/?probe=34898be259) | Nov 28, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [403ada1042](https://linux-hardware.org/?probe=403ada1042) | Nov 28, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [b58c73a493](https://linux-hardware.org/?probe=b58c73a493) | Nov 28, 2021 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [f6ab5c54f6](https://linux-hardware.org/?probe=f6ab5c54f6) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [a74aec830e](https://linux-hardware.org/?probe=a74aec830e) | Nov 27, 2021 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [b316c12d03](https://linux-hardware.org/?probe=b316c12d03) | Nov 27, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | Notebook    | [aef7318ff6](https://linux-hardware.org/?probe=aef7318ff6) | Nov 27, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [af530bb7c7](https://linux-hardware.org/?probe=af530bb7c7) | Nov 27, 2021 |
| Lenovo        | Yoga 14sARH 2021 82LB       | Notebook    | [27a4935e65](https://linux-hardware.org/?probe=27a4935e65) | Nov 26, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [9ae82b251b](https://linux-hardware.org/?probe=9ae82b251b) | Nov 26, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [d49a3f3160](https://linux-hardware.org/?probe=d49a3f3160) | Nov 26, 2021 |
| Dell          | 0RW199                      | Desktop     | [f00caa69eb](https://linux-hardware.org/?probe=f00caa69eb) | Nov 26, 2021 |
| Dell          | Precision M4800             | Notebook    | [c81b76f119](https://linux-hardware.org/?probe=c81b76f119) | Nov 25, 2021 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | Notebook    | [4eb53d4335](https://linux-hardware.org/?probe=4eb53d4335) | Nov 25, 2021 |
| Toshiba       | Satellite C660              | Notebook    | [995eaf8345](https://linux-hardware.org/?probe=995eaf8345) | Nov 25, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [a2761e06a4](https://linux-hardware.org/?probe=a2761e06a4) | Nov 24, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [5bfec76970](https://linux-hardware.org/?probe=5bfec76970) | Nov 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [a6b3b8877b](https://linux-hardware.org/?probe=a6b3b8877b) | Nov 24, 2021 |
| ASUSTek       | PRIME X570-PRO              | Desktop     | [7546b1e030](https://linux-hardware.org/?probe=7546b1e030) | Nov 24, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [5ee25c6894](https://linux-hardware.org/?probe=5ee25c6894) | Nov 23, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [7995f7e3a8](https://linux-hardware.org/?probe=7995f7e3a8) | Nov 23, 2021 |
| HP            | EliteBook 8460p             | Notebook    | [8278dcbd86](https://linux-hardware.org/?probe=8278dcbd86) | Nov 23, 2021 |
| ASUSTek       | K30BF_M32BF_A_F_K31BF_6     | Desktop     | [c31b46e5b5](https://linux-hardware.org/?probe=c31b46e5b5) | Nov 22, 2021 |
| MSI           | MEG X570 UNIFY              | Desktop     | [1cc474712f](https://linux-hardware.org/?probe=1cc474712f) | Nov 22, 2021 |
| Lenovo        | IdeaPad 320-15IKB 80XL      | Notebook    | [933eda02dc](https://linux-hardware.org/?probe=933eda02dc) | Nov 21, 2021 |
| Lenovo        | G50-45 80E3                 | Notebook    | [43f110e082](https://linux-hardware.org/?probe=43f110e082) | Nov 20, 2021 |
| Intel         | NUC8BEB J72693-304          | Mini pc     | [8d8d873287](https://linux-hardware.org/?probe=8d8d873287) | Nov 20, 2021 |
| ASRock        | J5040-ITX                   | Desktop     | [0c072ca601](https://linux-hardware.org/?probe=0c072ca601) | Nov 19, 2021 |
| Chuwi         | Hi10 X                      | Tablet      | [50dfc9f261](https://linux-hardware.org/?probe=50dfc9f261) | Nov 19, 2021 |
| HP            | ZBook Fury 15 G7 Mobile ... | Notebook    | [4f96b5ad58](https://linux-hardware.org/?probe=4f96b5ad58) | Nov 19, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [6d345c2500](https://linux-hardware.org/?probe=6d345c2500) | Nov 18, 2021 |
| Lenovo        | ThinkPad E495 20NES01600    | Notebook    | [aacc57f134](https://linux-hardware.org/?probe=aacc57f134) | Nov 17, 2021 |
| Fujitsu       | LIFEBOOK E782               | Notebook    | [f2e77fa439](https://linux-hardware.org/?probe=f2e77fa439) | Nov 17, 2021 |
| Dell          | 03015M A09                  | Server      | [c685a0033b](https://linux-hardware.org/?probe=c685a0033b) | Nov 17, 2021 |
| ASRock        | H370M Pro4                  | Desktop     | [63042f539f](https://linux-hardware.org/?probe=63042f539f) | Nov 17, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [6444d420e3](https://linux-hardware.org/?probe=6444d420e3) | Nov 16, 2021 |
| MSI           | H510I PRO WIFI              | Desktop     | [d50547de1f](https://linux-hardware.org/?probe=d50547de1f) | Nov 15, 2021 |
| Lenovo        | IdeaPad 3 17ADA05 81W2      | Notebook    | [ce05c5de33](https://linux-hardware.org/?probe=ce05c5de33) | Nov 15, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [2c7f2bbe1e](https://linux-hardware.org/?probe=2c7f2bbe1e) | Nov 14, 2021 |
| ASRock        | N68C-GS4 FX                 | Desktop     | [c863f2ca43](https://linux-hardware.org/?probe=c863f2ca43) | Nov 14, 2021 |
| Fujitsu       | D3220-A1 S26361-D3220-A1    | Desktop     | [7d1fd58f75](https://linux-hardware.org/?probe=7d1fd58f75) | Nov 14, 2021 |
| HP            | Pavilion dv6                | Notebook    | [30c1df8961](https://linux-hardware.org/?probe=30c1df8961) | Nov 13, 2021 |
| Samsung       | 550XDA                      | Notebook    | [69fe372895](https://linux-hardware.org/?probe=69fe372895) | Nov 12, 2021 |
| Samsung       | 550XDA                      | Notebook    | [61a4dbe6b6](https://linux-hardware.org/?probe=61a4dbe6b6) | Nov 12, 2021 |
| HP            | 844C                        | Desktop     | [2d709598d7](https://linux-hardware.org/?probe=2d709598d7) | Nov 12, 2021 |
| Gigabyte      | B85M-HD3                    | Desktop     | [f042aedbd9](https://linux-hardware.org/?probe=f042aedbd9) | Nov 12, 2021 |
| Dell          | 0W844P A02                  | Server      | [a8902b24dd](https://linux-hardware.org/?probe=a8902b24dd) | Nov 12, 2021 |
| Dell          | Latitude E5440              | Notebook    | [310f365903](https://linux-hardware.org/?probe=310f365903) | Nov 10, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [10991ab539](https://linux-hardware.org/?probe=10991ab539) | Nov 10, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [3f52dc0680](https://linux-hardware.org/?probe=3f52dc0680) | Nov 09, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [ec97cd08d4](https://linux-hardware.org/?probe=ec97cd08d4) | Nov 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [be3123eae1](https://linux-hardware.org/?probe=be3123eae1) | Nov 09, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [cf717529eb](https://linux-hardware.org/?probe=cf717529eb) | Nov 09, 2021 |
| Lenovo        | IdeaPad 330-15IKB 81DC      | Notebook    | [9a632ea5d1](https://linux-hardware.org/?probe=9a632ea5d1) | Nov 08, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [90fbcc38c3](https://linux-hardware.org/?probe=90fbcc38c3) | Nov 08, 2021 |
| Acer          | Spin SP313-51N              | Convertible | [7f5392b700](https://linux-hardware.org/?probe=7f5392b700) | Nov 08, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [b05955d022](https://linux-hardware.org/?probe=b05955d022) | Nov 06, 2021 |
| MSI           | X570-A PRO                  | Desktop     | [377a49cece](https://linux-hardware.org/?probe=377a49cece) | Nov 06, 2021 |
| Dell          | G3 3590                     | Notebook    | [aa237dfc61](https://linux-hardware.org/?probe=aa237dfc61) | Nov 06, 2021 |
| MSI           | B150M MORTAR                | Desktop     | [58d8ce0102](https://linux-hardware.org/?probe=58d8ce0102) | Nov 05, 2021 |
| Biostar       | H77MU3                      | Desktop     | [620dd98d14](https://linux-hardware.org/?probe=620dd98d14) | Nov 05, 2021 |
| ASUSTek       | Z9PA-D8 Series              | Server      | [30831977d2](https://linux-hardware.org/?probe=30831977d2) | Nov 04, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [72e74c86fb](https://linux-hardware.org/?probe=72e74c86fb) | Nov 04, 2021 |
| ASUSTek       | H87M-PLUS                   | Desktop     | [bbb4e58192](https://linux-hardware.org/?probe=bbb4e58192) | Nov 04, 2021 |
| ASRock        | X570 Steel Legend           | Desktop     | [f761a8dfa1](https://linux-hardware.org/?probe=f761a8dfa1) | Nov 03, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [276bfdb97e](https://linux-hardware.org/?probe=276bfdb97e) | Nov 03, 2021 |
| Acer          | Aspire 5820TG               | Notebook    | [d8ae1a4109](https://linux-hardware.org/?probe=d8ae1a4109) | Nov 03, 2021 |
| Acer          | Aspire 5820TG               | Notebook    | [c79617751e](https://linux-hardware.org/?probe=c79617751e) | Nov 03, 2021 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [18ac20be04](https://linux-hardware.org/?probe=18ac20be04) | Nov 03, 2021 |
| Dell          | Precision 7530              | Notebook    | [6a1961e13d](https://linux-hardware.org/?probe=6a1961e13d) | Nov 03, 2021 |
| Lenovo        | ThinkPad Edge E430 3254T... | Notebook    | [f9fbde199a](https://linux-hardware.org/?probe=f9fbde199a) | Nov 02, 2021 |
| Dell          | 0KP561                      | Desktop     | [e0c7723977](https://linux-hardware.org/?probe=e0c7723977) | Nov 02, 2021 |
| Dell          | 0KP561                      | Desktop     | [904f09d033](https://linux-hardware.org/?probe=904f09d033) | Nov 02, 2021 |
| MSI           | X58 Pro                     | Desktop     | [e37a1a6dd3](https://linux-hardware.org/?probe=e37a1a6dd3) | Nov 01, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [7599b9831d](https://linux-hardware.org/?probe=7599b9831d) | Nov 01, 2021 |
| Dell          | 0M859N A00                  | Desktop     | [aadca45789](https://linux-hardware.org/?probe=aadca45789) | Nov 01, 2021 |
| ASUSTek       | TUF X299 MARK 2             | Desktop     | [eacc1e3f66](https://linux-hardware.org/?probe=eacc1e3f66) | Nov 01, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [e04a41fc30](https://linux-hardware.org/?probe=e04a41fc30) | Oct 31, 2021 |
| HP            | ZBook 14 G2                 | Notebook    | [ffb40f821b](https://linux-hardware.org/?probe=ffb40f821b) | Oct 30, 2021 |
| ASUSTek       | SABERTOOTH X79              | Desktop     | [0c14ffd402](https://linux-hardware.org/?probe=0c14ffd402) | Oct 30, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [d4c089bc2f](https://linux-hardware.org/?probe=d4c089bc2f) | Oct 30, 2021 |
| ASUSTek       | X751LK                      | Notebook    | [b2cda34b7e](https://linux-hardware.org/?probe=b2cda34b7e) | Oct 30, 2021 |
| ZOTAC         | ZBOX-MA320                  | Mini pc     | [514267f2d8](https://linux-hardware.org/?probe=514267f2d8) | Oct 29, 2021 |
| IP3 Tech      | rev1.0                      | All in one  | [9032726ea4](https://linux-hardware.org/?probe=9032726ea4) | Oct 28, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [66fa4360dd](https://linux-hardware.org/?probe=66fa4360dd) | Oct 27, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | Notebook    | [65eac6abc6](https://linux-hardware.org/?probe=65eac6abc6) | Oct 27, 2021 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [2b89909a49](https://linux-hardware.org/?probe=2b89909a49) | Oct 25, 2021 |
| ASUSTek       | PRIME Z390-A                | Desktop     | [382b33add2](https://linux-hardware.org/?probe=382b33add2) | Oct 25, 2021 |
| Acer          | Aspire E1-772G              | Notebook    | [2ffccc532e](https://linux-hardware.org/?probe=2ffccc532e) | Oct 24, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b6be115eec](https://linux-hardware.org/?probe=b6be115eec) | Oct 23, 2021 |
| Acer          | Aspire 5560                 | Notebook    | [39fd26f895](https://linux-hardware.org/?probe=39fd26f895) | Oct 22, 2021 |
| Dell          | 0KP561                      | Desktop     | [08bbb7d29e](https://linux-hardware.org/?probe=08bbb7d29e) | Oct 22, 2021 |
| ASUSTek       | Maximus VIII HERO           | Desktop     | [9d090ad177](https://linux-hardware.org/?probe=9d090ad177) | Oct 22, 2021 |
| Dell          | Latitude 7420               | Notebook    | [a4ff2480e6](https://linux-hardware.org/?probe=a4ff2480e6) | Oct 22, 2021 |
| TUXEDO        | Aura 15 Gen1                | Notebook    | [627c62ae00](https://linux-hardware.org/?probe=627c62ae00) | Oct 21, 2021 |
| HP            | ProBook 650 G1              | Notebook    | [20be8bd8e7](https://linux-hardware.org/?probe=20be8bd8e7) | Oct 21, 2021 |
| Lenovo        | IdeaPad S340-15IML 81NA     | Notebook    | [849c03d63c](https://linux-hardware.org/?probe=849c03d63c) | Oct 21, 2021 |
| Acer          | Swift SF314-43              | Notebook    | [ef2da9ecca](https://linux-hardware.org/?probe=ef2da9ecca) | Oct 21, 2021 |
| Fujitsu       | D2619 S26361-D2619-A14 W... | Server      | [43c0756ba6](https://linux-hardware.org/?probe=43c0756ba6) | Oct 19, 2021 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [d9a12dc22c](https://linux-hardware.org/?probe=d9a12dc22c) | Oct 19, 2021 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [34a55551e2](https://linux-hardware.org/?probe=34a55551e2) | Oct 19, 2021 |
| ASUSTek       | Q324UAK                     | Convertible | [a8334894c5](https://linux-hardware.org/?probe=a8334894c5) | Oct 19, 2021 |
| ASUSTek       | P8Z77-M PRO                 | Desktop     | [c3c2bded72](https://linux-hardware.org/?probe=c3c2bded72) | Oct 18, 2021 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [d111902eac](https://linux-hardware.org/?probe=d111902eac) | Oct 18, 2021 |
| Medion        | E6436 MD61150               | Notebook    | [1edd4700fd](https://linux-hardware.org/?probe=1edd4700fd) | Oct 17, 2021 |
| Medion        | E6436 MD61150               | Notebook    | [2eaa34b93e](https://linux-hardware.org/?probe=2eaa34b93e) | Oct 17, 2021 |
| Lenovo        | Larne CRB 31900058 WIN 2... | All in one  | [fb267ca5ae](https://linux-hardware.org/?probe=fb267ca5ae) | Oct 17, 2021 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [fc4da04b79](https://linux-hardware.org/?probe=fc4da04b79) | Oct 16, 2021 |
| Fujitsu Si... | D2119 S26361-D2119          | Server      | [872ae76863](https://linux-hardware.org/?probe=872ae76863) | Oct 14, 2021 |
| Lenovo        | ThinkPad E15 20RD0015UK     | Notebook    | [d1cdbd537e](https://linux-hardware.org/?probe=d1cdbd537e) | Oct 13, 2021 |
| HP            | Laptop 17-ca1xxx            | Notebook    | [ae1811a242](https://linux-hardware.org/?probe=ae1811a242) | Oct 13, 2021 |
| HP            | ZHAN 66 Pro A 14 G3         | Notebook    | [d3fdfb0745](https://linux-hardware.org/?probe=d3fdfb0745) | Oct 13, 2021 |
| Lenovo        | ThinkPad T490s 20NYS1XK0... | Notebook    | [d3700d8667](https://linux-hardware.org/?probe=d3700d8667) | Oct 13, 2021 |
| Lenovo        | ThinkPad L15 Gen 1 20U4S... | Notebook    | [3bb6121afa](https://linux-hardware.org/?probe=3bb6121afa) | Oct 13, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [10b4482e0f](https://linux-hardware.org/?probe=10b4482e0f) | Oct 12, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [50c28abba1](https://linux-hardware.org/?probe=50c28abba1) | Oct 11, 2021 |
| Lenovo        | ThinkPad X13 Yoga Gen 1 ... | Convertible | [f7a8acd7c5](https://linux-hardware.org/?probe=f7a8acd7c5) | Oct 11, 2021 |
| Lenovo        | IdeaPadFlex 5 14ALC05 82... | Convertible | [c37f278d59](https://linux-hardware.org/?probe=c37f278d59) | Oct 11, 2021 |
| ASUSTek       | X550CL                      | Notebook    | [15e808f714](https://linux-hardware.org/?probe=15e808f714) | Oct 10, 2021 |
| Lenovo        | ThinkPad E560 20EV000NIV    | Notebook    | [4bb69f9fcc](https://linux-hardware.org/?probe=4bb69f9fcc) | Oct 10, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [778b409af2](https://linux-hardware.org/?probe=778b409af2) | Oct 09, 2021 |
| Apple         | Mac-F42C88C8 Proto1         | Desktop     | [26e5760e58](https://linux-hardware.org/?probe=26e5760e58) | Oct 08, 2021 |
| HP            | 87D6 SMVB                   | Desktop     | [6db404b73c](https://linux-hardware.org/?probe=6db404b73c) | Oct 08, 2021 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [eb4d7c93c0](https://linux-hardware.org/?probe=eb4d7c93c0) | Oct 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [4206d52561](https://linux-hardware.org/?probe=4206d52561) | Oct 07, 2021 |
| Lenovo        | ThinkPad L14 Gen 1 20U50... | Notebook    | [8e94483caf](https://linux-hardware.org/?probe=8e94483caf) | Oct 07, 2021 |
| Dell          | 0PC5F7 A03                  | Desktop     | [ff4e1fdb3a](https://linux-hardware.org/?probe=ff4e1fdb3a) | Oct 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon Gen 9... | Notebook    | [f3c6229102](https://linux-hardware.org/?probe=f3c6229102) | Oct 06, 2021 |
| Acer          | Nitro AN515-45              | Notebook    | [c439170645](https://linux-hardware.org/?probe=c439170645) | Oct 05, 2021 |
| HP            | 8591                        | Desktop     | [2de119b3d7](https://linux-hardware.org/?probe=2de119b3d7) | Oct 05, 2021 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [a9f8d1f512](https://linux-hardware.org/?probe=a9f8d1f512) | Oct 05, 2021 |
| HP            | Elite Dragonfly             | Convertible | [48cabedb1e](https://linux-hardware.org/?probe=48cabedb1e) | Oct 04, 2021 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | Desktop     | [ce4776505f](https://linux-hardware.org/?probe=ce4776505f) | Oct 03, 2021 |
| HP            | G61                         | Notebook    | [98ef6e48b5](https://linux-hardware.org/?probe=98ef6e48b5) | Oct 03, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [556c37ba9b](https://linux-hardware.org/?probe=556c37ba9b) | Oct 03, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [4d966dec54](https://linux-hardware.org/?probe=4d966dec54) | Oct 03, 2021 |
| ASRock        | M3A770DE                    | Desktop     | [de6577e71a](https://linux-hardware.org/?probe=de6577e71a) | Oct 03, 2021 |
| Lenovo        | 312A SDK0J40697 WIN 3305... | Desktop     | [0e54f43704](https://linux-hardware.org/?probe=0e54f43704) | Oct 02, 2021 |
| Google        | Pantheon                    | Notebook    | [72ded95fab](https://linux-hardware.org/?probe=72ded95fab) | Oct 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [ad69186227](https://linux-hardware.org/?probe=ad69186227) | Oct 02, 2021 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [f0b874d4f2](https://linux-hardware.org/?probe=f0b874d4f2) | Oct 02, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [3cec37b610](https://linux-hardware.org/?probe=3cec37b610) | Oct 02, 2021 |
| Lenovo        | ThinkPad E14 Gen 3 20Y7C... | Notebook    | [eabcfa676f](https://linux-hardware.org/?probe=eabcfa676f) | Oct 02, 2021 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [540dca7da7](https://linux-hardware.org/?probe=540dca7da7) | Oct 02, 2021 |
| ASUSTek       | PRIME B460M-K               | Desktop     | [33a2f5f274](https://linux-hardware.org/?probe=33a2f5f274) | Oct 02, 2021 |
| Lenovo        | ThinkPad W530 24475HU       | Notebook    | [b8973b3b0a](https://linux-hardware.org/?probe=b8973b3b0a) | Oct 02, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [3147ae8c58](https://linux-hardware.org/?probe=3147ae8c58) | Oct 01, 2021 |
| Lenovo        | ThinkPad T550 20CJS1VD01    | Notebook    | [390b9a8a74](https://linux-hardware.org/?probe=390b9a8a74) | Oct 01, 2021 |
| HP            | EliteBook Folio 9470m       | Notebook    | [101371762b](https://linux-hardware.org/?probe=101371762b) | Oct 01, 2021 |
| MSI           | GP63 Leopard 8RD            | Notebook    | [21189bb3e0](https://linux-hardware.org/?probe=21189bb3e0) | Oct 01, 2021 |
| ASRock        | H110M-G/M.2                 | Desktop     | [fa98bc9cc1](https://linux-hardware.org/?probe=fa98bc9cc1) | Oct 01, 2021 |
| HP            | 8591                        | Desktop     | [16548ed5fc](https://linux-hardware.org/?probe=16548ed5fc) | Sep 30, 2021 |
| HP            | 8591                        | Desktop     | [187edb6508](https://linux-hardware.org/?probe=187edb6508) | Sep 30, 2021 |
| Chuwi         | UBook X                     | Convertible | [b227e694f7](https://linux-hardware.org/?probe=b227e694f7) | Sep 29, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [7024087dbd](https://linux-hardware.org/?probe=7024087dbd) | Sep 26, 2021 |
| HUAWEI        | KPL-W0X                     | Notebook    | [b1c787f5e6](https://linux-hardware.org/?probe=b1c787f5e6) | Sep 26, 2021 |
| Dell          | XPS 13 9310                 | Notebook    | [39d644c56a](https://linux-hardware.org/?probe=39d644c56a) | Sep 26, 2021 |
| Lenovo        | ThinkPad L420 7827AW9       | Notebook    | [6c7308609b](https://linux-hardware.org/?probe=6c7308609b) | Sep 26, 2021 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [22d4ba7e2e](https://linux-hardware.org/?probe=22d4ba7e2e) | Sep 25, 2021 |
| Dell          | Inspiron N4010              | Notebook    | [82ad91793d](https://linux-hardware.org/?probe=82ad91793d) | Sep 25, 2021 |
| ASUSTek       | M4A78T-E                    | Desktop     | [01ec64f498](https://linux-hardware.org/?probe=01ec64f498) | Sep 24, 2021 |
| ASUSTek       | M4A89GTD-PRO/USB3           | Desktop     | [fca13979bf](https://linux-hardware.org/?probe=fca13979bf) | Sep 22, 2021 |
| Lenovo        | 364A SDK0J40700 WIN 3258... | Desktop     | [db9ccd461b](https://linux-hardware.org/?probe=db9ccd461b) | Sep 22, 2021 |
| Timi          | A35S                        | Notebook    | [c10b3fac0b](https://linux-hardware.org/?probe=c10b3fac0b) | Sep 22, 2021 |
| Lenovo        | Yoga 710-11IKB 80V6         | Notebook    | [59490b03a0](https://linux-hardware.org/?probe=59490b03a0) | Sep 21, 2021 |
| Samsung       | DT_DM500T8A SAMSUNG_SW_R... | Desktop     | [23cf6f38e8](https://linux-hardware.org/?probe=23cf6f38e8) | Sep 21, 2021 |
| Dell          | Precision M6700             | Notebook    | [0d8cf3bf1c](https://linux-hardware.org/?probe=0d8cf3bf1c) | Sep 21, 2021 |
| VS Company    | G31T-M                      | Desktop     | [ed8bb8c0d1](https://linux-hardware.org/?probe=ed8bb8c0d1) | Sep 21, 2021 |
| ASUSTek       | TUF Gaming FA706IU_FA706... | Notebook    | [9e88464633](https://linux-hardware.org/?probe=9e88464633) | Sep 20, 2021 |
| ASUSTek       | AM1M-A/BR                   | Desktop     | [c586c22b15](https://linux-hardware.org/?probe=c586c22b15) | Sep 20, 2021 |
| Dell          | Inspiron 7506 2n1           | Convertible | [d48766cb68](https://linux-hardware.org/?probe=d48766cb68) | Sep 19, 2021 |
| Google        | Pantheon                    | Notebook    | [eaa5a17c4b](https://linux-hardware.org/?probe=eaa5a17c4b) | Sep 19, 2021 |
| Medion        | S15449                      | Notebook    | [8f1110e14a](https://linux-hardware.org/?probe=8f1110e14a) | Sep 18, 2021 |
| HP            | ZBook 17                    | Notebook    | [df2e227740](https://linux-hardware.org/?probe=df2e227740) | Sep 18, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | Notebook    | [8ff619f5f3](https://linux-hardware.org/?probe=8ff619f5f3) | Sep 17, 2021 |
| HP            | OMEN Laptop 15-en1014AX     | Notebook    | [57dc237470](https://linux-hardware.org/?probe=57dc237470) | Sep 17, 2021 |
| HP            | EliteBook 840 G7 Noteboo... | Notebook    | [385fd35a7e](https://linux-hardware.org/?probe=385fd35a7e) | Sep 16, 2021 |
| MSI           | X370 SLI PLUS               | Desktop     | [783d480732](https://linux-hardware.org/?probe=783d480732) | Sep 16, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [84d5715b05](https://linux-hardware.org/?probe=84d5715b05) | Sep 16, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [2a08044752](https://linux-hardware.org/?probe=2a08044752) | Sep 16, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [8e3c2042fa](https://linux-hardware.org/?probe=8e3c2042fa) | Sep 16, 2021 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | Notebook    | [47d1d04589](https://linux-hardware.org/?probe=47d1d04589) | Sep 16, 2021 |
| MSI           | CX61 0OC/CX61 0OD/CX61 0... | Notebook    | [5f33450a0d](https://linux-hardware.org/?probe=5f33450a0d) | Sep 16, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [65615a3aaa](https://linux-hardware.org/?probe=65615a3aaa) | Sep 16, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [66385493ae](https://linux-hardware.org/?probe=66385493ae) | Sep 15, 2021 |
| Alienware     | 0PGRP5 A02                  | Desktop     | [158a015f26](https://linux-hardware.org/?probe=158a015f26) | Sep 15, 2021 |
| MSI           | Modern 15 A4M               | Notebook    | [1b2e6b06a0](https://linux-hardware.org/?probe=1b2e6b06a0) | Sep 14, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [1e2e03c85c](https://linux-hardware.org/?probe=1e2e03c85c) | Sep 14, 2021 |
| MSI           | Modern 15 A4M               | Notebook    | [dabdf47bdf](https://linux-hardware.org/?probe=dabdf47bdf) | Sep 13, 2021 |
| MSI           | X370 GAMING PRO             | Desktop     | [629a45e23d](https://linux-hardware.org/?probe=629a45e23d) | Sep 12, 2021 |
| Medion        | S15449                      | Notebook    | [03b29809eb](https://linux-hardware.org/?probe=03b29809eb) | Sep 11, 2021 |
| MSI           | GE72 7RD                    | Notebook    | [d02699b3f9](https://linux-hardware.org/?probe=d02699b3f9) | Sep 11, 2021 |
| Gigabyte      | B450M GAMING                | Desktop     | [e5b03fa6d6](https://linux-hardware.org/?probe=e5b03fa6d6) | Sep 10, 2021 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [db9571e8ce](https://linux-hardware.org/?probe=db9571e8ce) | Sep 09, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [522f36731e](https://linux-hardware.org/?probe=522f36731e) | Sep 07, 2021 |
| Dell          | Precision M3800             | Notebook    | [5dba4d3bce](https://linux-hardware.org/?probe=5dba4d3bce) | Sep 07, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [9a46145cf4](https://linux-hardware.org/?probe=9a46145cf4) | Sep 06, 2021 |
| MSI           | Z590-A PRO                  | Desktop     | [d4adebf878](https://linux-hardware.org/?probe=d4adebf878) | Sep 06, 2021 |
| HP            | 8056                        | Desktop     | [3cab8505c4](https://linux-hardware.org/?probe=3cab8505c4) | Sep 06, 2021 |
| Intel         | DG41WV AAE90316-104         | Desktop     | [27c162218f](https://linux-hardware.org/?probe=27c162218f) | Sep 05, 2021 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [d181845f45](https://linux-hardware.org/?probe=d181845f45) | Sep 05, 2021 |
| Lenovo        | ThinkPad X270 20HN0016GE    | Notebook    | [cecb5eb453](https://linux-hardware.org/?probe=cecb5eb453) | Sep 05, 2021 |
| Samsung       | 355V4C/356V4C/3445VC/354... | Notebook    | [3eb77262b0](https://linux-hardware.org/?probe=3eb77262b0) | Sep 04, 2021 |
| Acer          | Aspire A517-52G             | Notebook    | [2d3edcffdd](https://linux-hardware.org/?probe=2d3edcffdd) | Sep 04, 2021 |
| ASUSTek       | P8Z68 DELUXE/GEN3           | Desktop     | [b0339d1206](https://linux-hardware.org/?probe=b0339d1206) | Sep 04, 2021 |
| Lenovo        | ThinkPad T14s Gen 1 20UJ... | Notebook    | [82785cc5a8](https://linux-hardware.org/?probe=82785cc5a8) | Sep 03, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop TP41... | Convertible | [acc6c11a97](https://linux-hardware.org/?probe=acc6c11a97) | Sep 01, 2021 |
| MSI           | B450M MORTAR MAX            | Desktop     | [8518bcca24](https://linux-hardware.org/?probe=8518bcca24) | Sep 01, 2021 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [2786ebe5cc](https://linux-hardware.org/?probe=2786ebe5cc) | Aug 31, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [3f330b3732](https://linux-hardware.org/?probe=3f330b3732) | Aug 31, 2021 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [cf52a3a23b](https://linux-hardware.org/?probe=cf52a3a23b) | Aug 31, 2021 |
| Dell          | Inspiron 3593               | Notebook    | [5f9f37c33b](https://linux-hardware.org/?probe=5f9f37c33b) | Aug 30, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [be3b65a81d](https://linux-hardware.org/?probe=be3b65a81d) | Aug 29, 2021 |
| Medion        | S15449                      | Notebook    | [a0c8d15a30](https://linux-hardware.org/?probe=a0c8d15a30) | Aug 28, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [44d0412dd3](https://linux-hardware.org/?probe=44d0412dd3) | Aug 27, 2021 |
| Samsung       | 600B4B/600B5B               | Notebook    | [200275bbd6](https://linux-hardware.org/?probe=200275bbd6) | Aug 27, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [a13b05f65f](https://linux-hardware.org/?probe=a13b05f65f) | Aug 27, 2021 |
| Dell          | Precision M6700             | Notebook    | [191db00b83](https://linux-hardware.org/?probe=191db00b83) | Aug 26, 2021 |
| Lenovo        | V330-15IKB 81AX             | Notebook    | [4b5a1af4dd](https://linux-hardware.org/?probe=4b5a1af4dd) | Aug 26, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [62c96ffa5b](https://linux-hardware.org/?probe=62c96ffa5b) | Aug 25, 2021 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [516b9ff2ed](https://linux-hardware.org/?probe=516b9ff2ed) | Aug 25, 2021 |
| Supermicro    | X10DAI                      | Desktop     | [078ab4c114](https://linux-hardware.org/?probe=078ab4c114) | Aug 24, 2021 |
| Lenovo        | G500 20236                  | Notebook    | [73a5085a79](https://linux-hardware.org/?probe=73a5085a79) | Aug 24, 2021 |
| Dell          | Latitude 5480               | Notebook    | [a2110d9601](https://linux-hardware.org/?probe=a2110d9601) | Aug 24, 2021 |
| Foxconn       | 2ADA                        | Desktop     | [4a2ace789c](https://linux-hardware.org/?probe=4a2ace789c) | Aug 24, 2021 |
| Lenovo        | Yoga 3 Pro-1370 80HE        | Notebook    | [e59555689c](https://linux-hardware.org/?probe=e59555689c) | Aug 23, 2021 |
| Medion        | S15449                      | Notebook    | [adf11d6583](https://linux-hardware.org/?probe=adf11d6583) | Aug 22, 2021 |
| Lenovo        | ThinkPad L420 7827AW9       | Notebook    | [d18b84f4e1](https://linux-hardware.org/?probe=d18b84f4e1) | Aug 22, 2021 |
| Lenovo        | ThinkPad L420 7827AW9       | Notebook    | [7e1de8f6ba](https://linux-hardware.org/?probe=7e1de8f6ba) | Aug 22, 2021 |
| Lenovo        | ThinkPad Yoga 260 20FES0... | Convertible | [4300a083b1](https://linux-hardware.org/?probe=4300a083b1) | Aug 22, 2021 |
| Hardkernel    | ODROID-H2                   | Desktop     | [98bc091671](https://linux-hardware.org/?probe=98bc091671) | Aug 22, 2021 |
| HP            | Laptop 15s-eq1xxx           | Notebook    | [90446b95e6](https://linux-hardware.org/?probe=90446b95e6) | Aug 21, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [18d79e5a84](https://linux-hardware.org/?probe=18d79e5a84) | Aug 21, 2021 |
| Dell          | Latitude 5480               | Notebook    | [64e1f3e16c](https://linux-hardware.org/?probe=64e1f3e16c) | Aug 19, 2021 |
| Lenovo        | ThinkPad T61 8895W9U        | Notebook    | [424c5f3e75](https://linux-hardware.org/?probe=424c5f3e75) | Aug 19, 2021 |
| MSI           | MAG B460 TORPEDO            | Desktop     | [593ba86c4f](https://linux-hardware.org/?probe=593ba86c4f) | Aug 18, 2021 |
| Gigabyte      | H81M-S2H                    | Desktop     | [63a305ffc3](https://linux-hardware.org/?probe=63a305ffc3) | Aug 18, 2021 |
| Gigabyte      | B85-HD3-A                   | Desktop     | [91b0fe5452](https://linux-hardware.org/?probe=91b0fe5452) | Aug 17, 2021 |
| ASUSTek       | A88X-PLUS                   | Desktop     | [5a126bf926](https://linux-hardware.org/?probe=5a126bf926) | Aug 17, 2021 |
| ASUSTek       | ROG Zephyrus G14 GA401QM... | Notebook    | [4e946ccb36](https://linux-hardware.org/?probe=4e946ccb36) | Aug 15, 2021 |
| HP            | ProBook 450 G6              | Notebook    | [c206f3c985](https://linux-hardware.org/?probe=c206f3c985) | Aug 13, 2021 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [8d58a29d27](https://linux-hardware.org/?probe=8d58a29d27) | Aug 12, 2021 |
| Raspberry ... | Raspberry Pi 4 Model B R... | Soc         | [d7c235a5d9](https://linux-hardware.org/?probe=d7c235a5d9) | Aug 12, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [c68ce33d52](https://linux-hardware.org/?probe=c68ce33d52) | Aug 11, 2021 |
| HP            | 212B                        | Desktop     | [c9d708e504](https://linux-hardware.org/?probe=c9d708e504) | Aug 11, 2021 |
| Dell          | Inspiron 3521               | Notebook    | [9a422a10d3](https://linux-hardware.org/?probe=9a422a10d3) | Aug 11, 2021 |
| Lenovo        | SKYBAY SDK0J40705 WIN 34... | Desktop     | [034630b7f9](https://linux-hardware.org/?probe=034630b7f9) | Aug 11, 2021 |
| Dell          | Inspiron 7460               | Notebook    | [f954aa3826](https://linux-hardware.org/?probe=f954aa3826) | Aug 10, 2021 |
| Samsung       | 600B4B/600B5B               | Notebook    | [0a650b495e](https://linux-hardware.org/?probe=0a650b495e) | Aug 09, 2021 |
| Gigabyte      | Z370M D3H-CF                | Desktop     | [ce1da3d925](https://linux-hardware.org/?probe=ce1da3d925) | Aug 09, 2021 |
| Lenovo        | ThinkPad T460 20FMS75800    | Notebook    | [1a1c3f469d](https://linux-hardware.org/?probe=1a1c3f469d) | Aug 07, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [5953bc46ad](https://linux-hardware.org/?probe=5953bc46ad) | Aug 06, 2021 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [fafaeed466](https://linux-hardware.org/?probe=fafaeed466) | Aug 06, 2021 |
| HP            | 8591                        | Desktop     | [0f34dfc82c](https://linux-hardware.org/?probe=0f34dfc82c) | Aug 06, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [77e5c1027c](https://linux-hardware.org/?probe=77e5c1027c) | Aug 06, 2021 |
| ASUSTek       | ROG STRIX Z390-H GAMING     | Desktop     | [ffee1e0026](https://linux-hardware.org/?probe=ffee1e0026) | Aug 03, 2021 |
| Dell          | Inspiron 5770               | Notebook    | [0061c42395](https://linux-hardware.org/?probe=0061c42395) | Aug 02, 2021 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [2637dbf19f](https://linux-hardware.org/?probe=2637dbf19f) | Aug 02, 2021 |
| ASRock        | Z68 Extreme4 Gen3           | Desktop     | [a740a5cb42](https://linux-hardware.org/?probe=a740a5cb42) | Aug 01, 2021 |
| Lenovo        | ThinkPad P50 20EN0005GE     | Notebook    | [25a6865386](https://linux-hardware.org/?probe=25a6865386) | Aug 01, 2021 |
| ASUSTek       | 970 PRO GAMING/AURA         | Desktop     | [34f2f2b2a6](https://linux-hardware.org/?probe=34f2f2b2a6) | Aug 01, 2021 |
| ASUSTek       | PRIME H310M-A               | Desktop     | [a22aa3c48c](https://linux-hardware.org/?probe=a22aa3c48c) | Aug 01, 2021 |
| MSI           | B85M-E45                    | Desktop     | [0e20d4cea9](https://linux-hardware.org/?probe=0e20d4cea9) | Jul 30, 2021 |
| Lenovo        | ThinkPad SL510 2847CSG      | Notebook    | [505d87d58a](https://linux-hardware.org/?probe=505d87d58a) | Jul 30, 2021 |
| Lenovo        | ThinkPad SL510 2847CSG      | Notebook    | [09c0faf429](https://linux-hardware.org/?probe=09c0faf429) | Jul 30, 2021 |
| HP            | ZBook 15 G6                 | Notebook    | [617fd327a3](https://linux-hardware.org/?probe=617fd327a3) | Jul 28, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [3c2fc847b2](https://linux-hardware.org/?probe=3c2fc847b2) | Jul 28, 2021 |
| ASUSTek       | P8P67 DELUXE                | Desktop     | [fef6712b2e](https://linux-hardware.org/?probe=fef6712b2e) | Jul 27, 2021 |
| ASRock        | B560M Pro4/ac               | Desktop     | [84b1cb28d8](https://linux-hardware.org/?probe=84b1cb28d8) | Jul 25, 2021 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [748f864d48](https://linux-hardware.org/?probe=748f864d48) | Jul 25, 2021 |
| Lenovo        | IdeaPad Z510 20287          | Notebook    | [818166936a](https://linux-hardware.org/?probe=818166936a) | Jul 24, 2021 |
| Lenovo        | IdeaPad S145-15API 81V7     | Notebook    | [2640930f28](https://linux-hardware.org/?probe=2640930f28) | Jul 23, 2021 |
| Gigabyte      | B250M-DS3H-CF               | Desktop     | [acbcbe74d7](https://linux-hardware.org/?probe=acbcbe74d7) | Jul 22, 2021 |
| HP            | Stream Notebook PC 11       | Notebook    | [a612aa5d15](https://linux-hardware.org/?probe=a612aa5d15) | Jul 20, 2021 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [7cd3b13d49](https://linux-hardware.org/?probe=7cd3b13d49) | Jul 20, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [2803a67fa3](https://linux-hardware.org/?probe=2803a67fa3) | Jul 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [61ac3fb728](https://linux-hardware.org/?probe=61ac3fb728) | Jul 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [52642a99c5](https://linux-hardware.org/?probe=52642a99c5) | Jul 19, 2021 |
| Gigabyte      | AB350M-DS3H-CF              | Desktop     | [9552e2989b](https://linux-hardware.org/?probe=9552e2989b) | Jul 19, 2021 |
| Gigabyte      | Z68XP-UD4                   | Desktop     | [ed60f1e7f0](https://linux-hardware.org/?probe=ed60f1e7f0) | Jul 18, 2021 |
| Pegatron      | 2AE4                        | Desktop     | [6ccb7429e8](https://linux-hardware.org/?probe=6ccb7429e8) | Jul 18, 2021 |
| Dell          | Inspiron 3442               | Notebook    | [8814bd2240](https://linux-hardware.org/?probe=8814bd2240) | Jul 18, 2021 |
| Avell High... | A62 LIV                     | Notebook    | [a1398c199a](https://linux-hardware.org/?probe=a1398c199a) | Jul 17, 2021 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/openSUSE/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| openSUSE Tumbleweed-XXXXXXXX | 942       | 61.05%  |
| openSUSE Leap-15.2           | 211       | 13.67%  |
| openSUSE Leap-15.3           | 126       | 8.17%   |
| openSUSE Leap-15.1           | 122       | 7.91%   |
| openSUSE Leap-15.4           | 61        | 3.95%   |
| openSUSE Leap-15.0           | 48        | 3.11%   |
| openSUSE Microos-XXXXXXXX    | 14        | 0.91%   |
| openSUSE 13.2                | 5         | 0.32%   |
| openSUSE Leap-42.2           | 3         | 0.19%   |
| openSUSE                     | 3         | 0.19%   |
| openSUSE Leap-42.3           | 2         | 0.13%   |
| openSUSE Leap-15.5           | 2         | 0.13%   |
| openSUSE 42.3                | 2         | 0.13%   |
| openSUSE Leap-42.1           | 1         | 0.06%   |
| openSUSE 13.1                | 1         | 0.06%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name     | Computers | Percent |
|----------|-----------|---------|
| openSUSE | 1493      | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                      | Computers | Percent |
|------------------------------|-----------|---------|
| 5.17.4-1-default             | 49        | 2.74%   |
| 4.12.14-lp151.28.44-default  | 43        | 2.41%   |
| 5.6.0-1-default              | 31        | 1.74%   |
| 5.19.2-1-default             | 24        | 1.34%   |
| 4.18.15-1-default            | 23        | 1.29%   |
| 5.3.18-lp152.63-default      | 22        | 1.23%   |
| 5.14.21-150400.22-default    | 22        | 1.23%   |
| 5.16.11-1-default            | 20        | 1.12%   |
| 5.14.14-1-default            | 20        | 1.12%   |
| 5.6.2-1-default              | 19        | 1.06%   |
| 5.17.1-1-default             | 19        | 1.06%   |
| 5.3.18-lp152.57-default      | 18        | 1.01%   |
| 5.3.18-59.37-default         | 18        | 1.01%   |
| 5.17.9-1-default             | 18        | 1.01%   |
| 5.11.6-1-default             | 18        | 1.01%   |
| 5.8.4-1-default              | 17        | 0.95%   |
| 5.3.18-lp152.41-default      | 17        | 0.95%   |
| 5.19.8-1-default             | 17        | 0.95%   |
| 5.10.7-1-default             | 17        | 0.95%   |
| 5.3.18-lp152.36-default      | 16        | 0.9%    |
| 5.18.6-1-default             | 16        | 0.9%    |
| 5.14.21-150400.24.21-default | 16        | 0.9%    |
| 5.10.16-1-default            | 15        | 0.84%   |
| 6.0.3-1-default              | 14        | 0.78%   |
| 5.6.12-1-default             | 14        | 0.78%   |
| 5.3.18-lp152.50-default      | 14        | 0.78%   |
| 5.13.8-1-default             | 14        | 0.78%   |
| 4.12.14-lp151.28.48-default  | 14        | 0.78%   |
| 5.3.18-59.27-default         | 13        | 0.73%   |
| 5.3.18-59.19-default         | 13        | 0.73%   |
| 5.14.6-1-default             | 13        | 0.73%   |
| 5.8.10-1-default             | 12        | 0.67%   |
| 5.3.18-lp152.66-default      | 12        | 0.67%   |
| 5.15.12-1-default            | 12        | 0.67%   |
| 5.14.21-150400.24.18-default | 12        | 0.67%   |
| 5.12.9-1-default             | 12        | 0.67%   |
| 5.8.0-1-default              | 11        | 0.62%   |
| 5.3.18-lp152.47-default      | 11        | 0.62%   |
| 5.15.8-1-default             | 11        | 0.62%   |
| 5.15.5-1-default             | 11        | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3.18  | 307       | 17.83%  |
| 4.12.14 | 157       | 9.12%   |
| 5.14.21 | 60        | 3.48%   |
| 5.17.4  | 49        | 2.85%   |
| 5.6.0   | 33        | 1.92%   |
| 5.14.14 | 30        | 1.74%   |
| 5.19.2  | 24        | 1.39%   |
| 4.18.15 | 23        | 1.34%   |
| 5.6.2   | 21        | 1.22%   |
| 5.17.1  | 20        | 1.16%   |
| 5.16.11 | 20        | 1.16%   |
| 5.12.4  | 19        | 1.1%    |
| 5.11.6  | 19        | 1.1%    |
| 5.8.4   | 18        | 1.05%   |
| 5.17.9  | 18        | 1.05%   |
| 5.14.6  | 18        | 1.05%   |
| 5.10.7  | 18        | 1.05%   |
| 5.19.8  | 17        | 0.99%   |
| 5.18.6  | 16        | 0.93%   |
| 6.0.3   | 15        | 0.87%   |
| 5.12.9  | 15        | 0.87%   |
| 5.12.0  | 15        | 0.87%   |
| 5.10.16 | 15        | 0.87%   |
| 5.9.1   | 14        | 0.81%   |
| 5.6.12  | 14        | 0.81%   |
| 5.13.8  | 14        | 0.81%   |
| 5.18.9  | 13        | 0.75%   |
| 5.8.10  | 12        | 0.7%    |
| 5.8.0   | 12        | 0.7%    |
| 5.16.0  | 12        | 0.7%    |
| 5.15.12 | 12        | 0.7%    |
| 5.3.12  | 11        | 0.64%   |
| 5.15.8  | 11        | 0.64%   |
| 5.15.5  | 11        | 0.64%   |
| 5.14.2  | 11        | 0.64%   |
| 5.9.14  | 10        | 0.58%   |
| 5.18.11 | 10        | 0.58%   |
| 5.15.3  | 10        | 0.58%   |
| 5.14.11 | 10        | 0.58%   |
| 5.12.13 | 10        | 0.58%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.3     | 328       | 19.5%   |
| 4.12    | 157       | 9.33%   |
| 5.14    | 147       | 8.74%   |
| 5.17    | 112       | 6.66%   |
| 5.6     | 82        | 4.88%   |
| 5.16    | 77        | 4.58%   |
| 5.18    | 73        | 4.34%   |
| 5.12    | 72        | 4.28%   |
| 5.8     | 70        | 4.16%   |
| 5.10    | 68        | 4.04%   |
| 5.19    | 66        | 3.92%   |
| 5.11    | 59        | 3.51%   |
| 5.15    | 58        | 3.45%   |
| 5.13    | 49        | 2.91%   |
| 5.9     | 40        | 2.38%   |
| 5.7     | 36        | 2.14%   |
| 6.0     | 33        | 1.96%   |
| 5.5     | 33        | 1.96%   |
| 4.18    | 27        | 1.61%   |
| 5.4     | 21        | 1.25%   |
| 5.0     | 14        | 0.83%   |
| 5.2     | 13        | 0.77%   |
| 4.17    | 11        | 0.65%   |
| 4.4     | 9         | 0.54%   |
| 5.1     | 5         | 0.3%    |
| 4.20    | 5         | 0.3%    |
| 4.3     | 4         | 0.24%   |
| 3.16    | 4         | 0.24%   |
| 4.19    | 3         | 0.18%   |
| 4.16    | 2         | 0.12%   |
| 6.1     | 1         | 0.06%   |
| 4.7     | 1         | 0.06%   |
| 4.1     | 1         | 0.06%   |
| 3.12    | 1         | 0.06%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 1475      | 98.73%  |
| i686    | 13        | 0.87%   |
| aarch64 | 6         | 0.4%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| KDE5          | 785       | 50.71%  |
| GNOME         | 252       | 16.28%  |
| KDE           | 211       | 13.63%  |
| Unknown       | 129       | 8.33%   |
| XFCE          | 79        | 5.1%    |
| MATE          | 18        | 1.16%   |
| X-Cinnamon    | 16        | 1.03%   |
| Cinnamon      | 10        | 0.65%   |
| KDE4          | 9         | 0.58%   |
| LXQt          | 7         | 0.45%   |
| ICEWM         | 5         | 0.32%   |
| Budgie        | 5         | 0.32%   |
| LXDE          | 4         | 0.26%   |
| WindowMaker   | 2         | 0.13%   |
| Pantheon      | 2         | 0.13%   |
| i3            | 2         | 0.13%   |
| GNOME Classic | 2         | 0.13%   |
| Deepin        | 2         | 0.13%   |
| sway          | 1         | 0.06%   |
| plasma5       | 1         | 0.06%   |
| openbox       | 1         | 0.06%   |
| Herbstluftwm  | 1         | 0.06%   |
| fvwm2         | 1         | 0.06%   |
| default       | 1         | 0.06%   |
| custom        | 1         | 0.06%   |
| awesome       | 1         | 0.06%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| X11         | 1245      | 80.9%   |
| Wayland     | 224       | 14.55%  |
| Unknown     | 39        | 2.53%   |
| Tty         | 29        | 1.88%   |
| Unspecified | 2         | 0.13%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 561       | 36.59%  |
| LightDM | 539       | 35.16%  |
| SDDM    | 328       | 21.4%   |
| XDM     | 96        | 6.26%   |
| GDM     | 9         | 0.59%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 496       | 32.15%  |
| de_DE   | 190       | 12.31%  |
| Unknown | 176       | 11.41%  |
| POSIX   | 145       | 9.4%    |
| en_GB   | 106       | 6.87%   |
| pt_BR   | 61        | 3.95%   |
| ru_RU   | 60        | 3.89%   |
| es_ES   | 47        | 3.05%   |
| fr_FR   | 35        | 2.27%   |
| it_IT   | 29        | 1.88%   |
| pl_PL   | 23        | 1.49%   |
| nl_NL   | 19        | 1.23%   |
| pt_PT   | 18        | 1.17%   |
| zh_CN   | 10        | 0.65%   |
| cs_CZ   | 9         | 0.58%   |
| hu_HU   | 8         | 0.52%   |
| fi_FI   | 8         | 0.52%   |
| es_MX   | 6         | 0.39%   |
| es_AR   | 6         | 0.39%   |
| C       | 6         | 0.39%   |
| sv_SE   | 5         | 0.32%   |
| en_IN   | 5         | 0.32%   |
| tr_TR   | 4         | 0.26%   |
| nn_NO   | 4         | 0.26%   |
| nl_BE   | 4         | 0.26%   |
| nb_NO   | 4         | 0.26%   |
| en_IE   | 4         | 0.26%   |
| en_DE   | 4         | 0.26%   |
| en_AU   | 4         | 0.26%   |
| hr_HR   | 3         | 0.19%   |
| cv_RU   | 3         | 0.19%   |
| bg_BG   | 3         | 0.19%   |
| sk_SK   | 2         | 0.13%   |
| ru_UA   | 2         | 0.13%   |
| ja_JP   | 2         | 0.13%   |
| en_PH   | 2         | 0.13%   |
| en_NL   | 2         | 0.13%   |
| en_FI   | 2         | 0.13%   |
| en_CH   | 2         | 0.13%   |
| en_CA   | 2         | 0.13%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 968       | 64.19%  |
| BIOS | 540       | 35.81%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Btrfs    | 1020      | 67.5%   |
| Ext4     | 341       | 22.57%  |
| Xfs      | 69        | 4.57%   |
| Unknown  | 61        | 4.04%   |
| Overlay  | 13        | 0.86%   |
| Tmpfs    | 2         | 0.13%   |
| Ext3     | 2         | 0.13%   |
| Reiserfs | 1         | 0.07%   |
| F2fs     | 1         | 0.07%   |
| Ext2     | 1         | 0.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 861       | 56.57%  |
| Unknown | 503       | 33.05%  |
| MBR     | 158       | 10.38%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1262      | 82.81%  |
| Yes       | 262       | 17.19%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 1074      | 70.8%   |
| Yes       | 443       | 29.2%   |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 238       | 15.94%  |
| Lenovo                  | 229       | 15.34%  |
| Hewlett-Packard         | 215       | 14.4%   |
| Dell                    | 181       | 12.12%  |
| Gigabyte Technology     | 121       | 8.1%    |
| MSI                     | 113       | 7.57%   |
| ASRock                  | 71        | 4.76%   |
| Acer                    | 62        | 4.15%   |
| Apple                   | 34        | 2.28%   |
| Toshiba                 | 19        | 1.27%   |
| Fujitsu                 | 19        | 1.27%   |
| TUXEDO                  | 15        | 1%      |
| Intel                   | 13        | 0.87%   |
| Sony                    | 11        | 0.74%   |
| Samsung Electronics     | 11        | 0.74%   |
| HUAWEI                  | 11        | 0.74%   |
| Supermicro              | 8         | 0.54%   |
| Biostar                 | 8         | 0.54%   |
| Pegatron                | 6         | 0.4%    |
| Medion                  | 6         | 0.4%    |
| Fujitsu Siemens         | 6         | 0.4%    |
| Notebook                | 5         | 0.33%   |
| Foxconn                 | 5         | 0.33%   |
| Alienware               | 5         | 0.33%   |
| Unknown                 | 5         | 0.33%   |
| Raspberry Pi Foundation | 4         | 0.27%   |
| Positivo                | 4         | 0.27%   |
| Microsoft               | 3         | 0.2%    |
| LG Electronics          | 3         | 0.2%    |
| Google                  | 3         | 0.2%    |
| Clevo                   | 3         | 0.2%    |
| Avell High Performance  | 3         | 0.2%    |
| Timi                    | 2         | 0.13%   |
| Shuttle                 | 2         | 0.13%   |
| Razer                   | 2         | 0.13%   |
| Getac                   | 2         | 0.13%   |
| Gateway                 | 2         | 0.13%   |
| EVGA                    | 2         | 0.13%   |
| Chuwi                   | 2         | 0.13%   |
| BESSTAR Tech            | 2         | 0.13%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                            | Computers | Percent |
|---------------------------------|-----------|---------|
| ASUS All Series                 | 19        | 1.27%   |
| Unknown                         | 10        | 0.67%   |
| MSI MS-7B86                     | 7         | 0.47%   |
| Dell OptiPlex 9020              | 7         | 0.47%   |
| MSI MS-7B89                     | 6         | 0.4%    |
| HP Notebook                     | 6         | 0.4%    |
| Dell Precision 5530             | 6         | 0.4%    |
| ASRock B450M Pro4               | 6         | 0.4%    |
| MSI MS-7C37                     | 5         | 0.33%   |
| HP Pavilion dv6                 | 5         | 0.33%   |
| Gigabyte B450M DS3H             | 5         | 0.33%   |
| Gigabyte 970A-DS3P              | 5         | 0.33%   |
| Dell Latitude 7490              | 5         | 0.33%   |
| ASUS TUF Gaming X570-PLUS       | 5         | 0.33%   |
| MSI MS-7C02                     | 4         | 0.27%   |
| MSI MS-7B79                     | 4         | 0.27%   |
| MSI MS-7A34                     | 4         | 0.27%   |
| HP Pavilion g6                  | 4         | 0.27%   |
| HP Pavilion dv7                 | 4         | 0.27%   |
| HP Laptop 17-ca0xxx             | 4         | 0.27%   |
| Gigabyte X570 AORUS MASTER      | 4         | 0.27%   |
| Gigabyte B450 AORUS M           | 4         | 0.27%   |
| Dell XPS 15 9560                | 4         | 0.27%   |
| ASUS M5A78L-M/USB3              | 4         | 0.27%   |
| Apple MacBookPro9,2             | 4         | 0.27%   |
| TUXEDO Pulse 15 Gen1            | 3         | 0.2%    |
| MSI MS-7A33                     | 3         | 0.2%    |
| Lenovo ThinkBook 14 G3 ACL 21A2 | 3         | 0.2%    |
| Lenovo IdeaPad 5 14ARE05 81YM   | 3         | 0.2%    |
| HP Z840 Workstation             | 3         | 0.2%    |
| HP Z620 Workstation             | 3         | 0.2%    |
| HP ProLiant MicroServer         | 3         | 0.2%    |
| HP Laptop 15-bs0xx              | 3         | 0.2%    |
| HP Compaq Presario CQ40         | 3         | 0.2%    |
| Dell XPS 8700                   | 3         | 0.2%    |
| Dell XPS 15 9510                | 3         | 0.2%    |
| Dell Latitude E7470             | 3         | 0.2%    |
| Dell Latitude E6430             | 3         | 0.2%    |
| Dell Inspiron 5584              | 3         | 0.2%    |
| ASUS ROG STRIX X570-E GAMING    | 3         | 0.2%    |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo ThinkPad    | 129       | 8.64%   |
| Dell Inspiron      | 42        | 2.81%   |
| Dell Latitude      | 39        | 2.61%   |
| Acer Aspire        | 38        | 2.55%   |
| Lenovo IdeaPad     | 33        | 2.21%   |
| HP Pavilion        | 32        | 2.14%   |
| HP EliteBook       | 31        | 2.08%   |
| ASUS ROG           | 28        | 1.88%   |
| ASUS PRIME         | 28        | 1.88%   |
| ASUS TUF           | 27        | 1.81%   |
| Dell XPS           | 25        | 1.67%   |
| Dell OptiPlex      | 25        | 1.67%   |
| Dell Precision     | 21        | 1.41%   |
| ASUS All           | 19        | 1.27%   |
| Toshiba Satellite  | 18        | 1.21%   |
| HP Laptop          | 18        | 1.21%   |
| Lenovo Yoga        | 17        | 1.14%   |
| HP ProBook         | 17        | 1.14%   |
| HP ZBook           | 15        | 1%      |
| HP ENVY            | 15        | 1%      |
| Lenovo ThinkCentre | 14        | 0.94%   |
| HP Compaq          | 13        | 0.87%   |
| ASUS VivoBook      | 13        | 0.87%   |
| Gigabyte X570      | 12        | 0.8%    |
| Dell PowerEdge     | 11        | 0.74%   |
| Unknown            | 10        | 0.67%   |
| Fujitsu LIFEBOOK   | 9         | 0.6%    |
| HP OMEN            | 8         | 0.54%   |
| ASRock B450M       | 8         | 0.54%   |
| MSI MS-7B86        | 7         | 0.47%   |
| Gigabyte B550      | 7         | 0.47%   |
| Gigabyte B450M     | 7         | 0.47%   |
| Gigabyte B450      | 7         | 0.47%   |
| Dell Vostro        | 7         | 0.47%   |
| ASUS M5A78L-M      | 7         | 0.47%   |
| Acer Swift         | 7         | 0.47%   |
| MSI MS-7B89        | 6         | 0.4%    |
| HP Notebook        | 6         | 0.4%    |
| Fujitsu ESPRIMO    | 6         | 0.4%    |
| ASUS ZenBook       | 6         | 0.4%    |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 173       | 11.59%  |
| 2018 | 164       | 10.98%  |
| 2019 | 162       | 10.85%  |
| 2017 | 129       | 8.64%   |
| 2021 | 114       | 7.64%   |
| 2012 | 110       | 7.37%   |
| 2013 | 107       | 7.17%   |
| 2015 | 91        | 6.1%    |
| 2011 | 85        | 5.69%   |
| 2014 | 83        | 5.56%   |
| 2016 | 79        | 5.29%   |
| 2010 | 64        | 4.29%   |
| 2009 | 47        | 3.15%   |
| 2008 | 38        | 2.55%   |
| 2022 | 18        | 1.21%   |
| 2007 | 16        | 1.07%   |
| 2006 | 7         | 0.47%   |
| 2005 | 3         | 0.2%    |
| 2004 | 2         | 0.13%   |
| 2000 | 1         | 0.07%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 748       | 50.1%   |
| Desktop        | 623       | 41.73%  |
| Convertible    | 50        | 3.35%   |
| Mini pc        | 22        | 1.47%   |
| Server         | 20        | 1.34%   |
| All in one     | 18        | 1.21%   |
| Tablet         | 6         | 0.4%    |
| System on chip | 5         | 0.33%   |
| Firewall       | 1         | 0.07%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 1309      | 86.46%  |
| Enabled  | 205       | 13.54%  |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1488      | 99.67%  |
| Yes  | 5         | 0.33%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 16.01-24.0      | 394       | 26.09%  |
| 4.01-8.0        | 328       | 21.72%  |
| 8.01-16.0       | 300       | 19.87%  |
| 32.01-64.0      | 206       | 13.64%  |
| 3.01-4.0        | 135       | 8.94%   |
| 64.01-256.0     | 62        | 4.11%   |
| 24.01-32.0      | 34        | 2.25%   |
| 1.01-2.0        | 22        | 1.46%   |
| 2.01-3.0        | 11        | 0.73%   |
| Unknown         | 10        | 0.66%   |
| 0.51-1.0        | 6         | 0.4%    |
| More than 256.0 | 1         | 0.07%   |
| 0.01-0.5        | 1         | 0.07%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 2.01-3.0   | 407       | 25.02%  |
| 4.01-8.0   | 387       | 23.79%  |
| 1.01-2.0   | 363       | 22.31%  |
| 3.01-4.0   | 262       | 16.1%   |
| 8.01-16.0  | 103       | 6.33%   |
| 0.51-1.0   | 60        | 3.69%   |
| 16.01-24.0 | 15        | 0.92%   |
| 0.01-0.5   | 13        | 0.8%    |
| Unknown    | 10        | 0.61%   |
| 24.01-32.0 | 6         | 0.37%   |
| 32.01-64.0 | 1         | 0.06%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 733       | 47.81%  |
| 2       | 431       | 28.11%  |
| 3       | 167       | 10.89%  |
| 4       | 93        | 6.07%   |
| 5       | 51        | 3.33%   |
| 6       | 30        | 1.96%   |
| 7       | 14        | 0.91%   |
| 8       | 3         | 0.2%    |
| 0       | 3         | 0.2%    |
| 13      | 2         | 0.13%   |
| 10      | 2         | 0.13%   |
| 35      | 1         | 0.07%   |
| 16      | 1         | 0.07%   |
| 9       | 1         | 0.07%   |
| Unknown | 1         | 0.07%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 938       | 62.45%  |
| Yes       | 564       | 37.55%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1324      | 88.62%  |
| No        | 170       | 11.38%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 1086      | 72.45%  |
| No        | 413       | 27.55%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 925       | 61.22%  |
| No        | 586       | 38.78%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country     | Computers | Percent |
|-------------|-----------|---------|
| Germany     | 268       | 17.89%  |
| USA         | 265       | 17.69%  |
| Brazil      | 89        | 5.94%   |
| Russia      | 76        | 5.07%   |
| France      | 55        | 3.67%   |
| UK          | 53        | 3.54%   |
| Italy       | 50        | 3.34%   |
| Netherlands | 49        | 3.27%   |
| Spain       | 39        | 2.6%    |
| Switzerland | 37        | 2.47%   |
| Poland      | 31        | 2.07%   |
| Canada      | 30        | 2%      |
| India       | 27        | 1.8%    |
| Sweden      | 26        | 1.74%   |
| Austria     | 24        | 1.6%    |
| Mexico      | 22        | 1.47%   |
| Belgium     | 22        | 1.47%   |
| China       | 20        | 1.34%   |
| Australia   | 20        | 1.34%   |
| Czechia     | 19        | 1.27%   |
| Norway      | 16        | 1.07%   |
| Hungary     | 16        | 1.07%   |
| Portugal    | 15        | 1%      |
| Finland     | 15        | 1%      |
| Ukraine     | 14        | 0.93%   |
| Romania     | 12        | 0.8%    |
| Turkey      | 11        | 0.73%   |
| Serbia      | 10        | 0.67%   |
| Bulgaria    | 10        | 0.67%   |
| Greece      | 9         | 0.6%    |
| Chile       | 8         | 0.53%   |
| Belarus     | 8         | 0.53%   |
| Argentina   | 8         | 0.53%   |
| Peru        | 7         | 0.47%   |
| Croatia     | 7         | 0.47%   |
| Luxembourg  | 6         | 0.4%    |
| Japan       | 6         | 0.4%    |
| Israel      | 6         | 0.4%    |
| Indonesia   | 6         | 0.4%    |
| Thailand    | 5         | 0.33%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                      | Computers | Percent |
|---------------------------|-----------|---------|
| Moscow                    | 23        | 1.46%   |
| Berlin                    | 22        | 1.4%    |
| Vienna                    | 15        | 0.95%   |
| Rio de Janeiro            | 12        | 0.76%   |
| Paris                     | 12        | 0.76%   |
| Munich                    | 12        | 0.76%   |
| Zurich                    | 11        | 0.7%    |
| Sao Paulo                 | 10        | 0.63%   |
| Littleton                 | 10        | 0.63%   |
| Prague                    | 9         | 0.57%   |
| Neuchatel                 | 9         | 0.57%   |
| Frankfurt am Main         | 9         | 0.57%   |
| Budapest                  | 9         | 0.57%   |
| Amsterdam                 | 9         | 0.57%   |
| Rome                      | 8         | 0.51%   |
| Riverton                  | 8         | 0.51%   |
| Madrid                    | 8         | 0.51%   |
| Los Angeles               | 8         | 0.51%   |
| Warsaw                    | 7         | 0.44%   |
| Sydney                    | 7         | 0.44%   |
| St Petersburg             | 7         | 0.44%   |
| Montreal                  | 7         | 0.44%   |
| Milan                     | 7         | 0.44%   |
| Hamburg                   | 7         | 0.44%   |
| Gothenburg                | 7         | 0.44%   |
| Bengaluru                 | 7         | 0.44%   |
| Belgrade                  | 7         | 0.44%   |
| Sofia                     | 6         | 0.38%   |
| Schrobenhausen            | 6         | 0.38%   |
| Houston                   | 6         | 0.38%   |
| Halle                     | 6         | 0.38%   |
| The Hague                 | 5         | 0.32%   |
| Santiago                  | 5         | 0.32%   |
| San Jose                  | 5         | 0.32%   |
| Minsk                     | 5         | 0.32%   |
| Lisbon                    | 5         | 0.32%   |
| Leipzig                   | 5         | 0.32%   |
| Haßfurt                  | 5         | 0.32%   |
| Essen                     | 5         | 0.32%   |
| Buchholz in der Nordheide | 5         | 0.32%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                    | Computers | Drives | Percent |
|---------------------------|-----------|--------|---------|
| Samsung Electronics       | 502       | 772    | 20.14%  |
| Seagate                   | 382       | 692    | 15.33%  |
| WDC                       | 377       | 636    | 15.13%  |
| Toshiba                   | 160       | 208    | 6.42%   |
| Kingston                  | 134       | 174    | 5.38%   |
| SanDisk                   | 116       | 142    | 4.65%   |
| Crucial                   | 103       | 136    | 4.13%   |
| Intel                     | 69        | 84     | 2.77%   |
| SK hynix                  | 62        | 86     | 2.49%   |
| Unknown                   | 60        | 88     | 2.41%   |
| Hitachi                   | 51        | 62     | 2.05%   |
| HGST                      | 46        | 63     | 1.85%   |
| A-DATA Technology         | 34        | 46     | 1.36%   |
| Micron Technology         | 28        | 37     | 1.12%   |
| Phison                    | 23        | 31     | 0.92%   |
| PNY                       | 22        | 29     | 0.88%   |
| Intenso                   | 16        | 20     | 0.64%   |
| SPCC                      | 15        | 19     | 0.6%    |
| Silicon Motion            | 15        | 16     | 0.6%    |
| Apple                     | 15        | 18     | 0.6%    |
| KIOXIA                    | 14        | 14     | 0.56%   |
| Fujitsu                   | 12        | 14     | 0.48%   |
| LITEON                    | 11        | 12     | 0.44%   |
| Hewlett-Packard           | 11        | 15     | 0.44%   |
| Corsair                   | 11        | 12     | 0.44%   |
| China                     | 11        | 12     | 0.44%   |
| Transcend                 | 9         | 10     | 0.36%   |
| OCZ                       | 8         | 13     | 0.32%   |
| GOODRAM                   | 8         | 8      | 0.32%   |
| XPG                       | 7         | 9      | 0.28%   |
| Team                      | 6         | 6      | 0.24%   |
| Micron/Crucial Technology | 6         | 11     | 0.24%   |
| Maxtor                    | 6         | 6      | 0.24%   |
| LITEONIT                  | 6         | 6      | 0.24%   |
| JMicron Technology        | 6         | 6      | 0.24%   |
| SABRENT                   | 5         | 6      | 0.2%    |
| Plextor                   | 5         | 6      | 0.2%    |
| Phison Electronics        | 5         | 9      | 0.2%    |
| Mushkin                   | 5         | 8      | 0.2%    |
| Gigabyte Technology       | 5         | 10     | 0.2%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                              | Computers | Percent |
|------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB          | 40        | 1.41%   |
| Samsung SSD 850 EVO 250GB          | 30        | 1.06%   |
| Samsung SSD 860 EVO 1TB            | 24        | 0.84%   |
| Seagate ST1000LM024 HN-M101MBB 1TB | 21        | 0.74%   |
| Seagate ST2000DM008-2FR102 2TB     | 19        | 0.67%   |
| HGST HTS721010A9E630 1TB           | 19        | 0.67%   |
| Samsung SSD 970 EVO Plus 1TB       | 18        | 0.63%   |
| Seagate ST1000LM035-1RK172 1TB     | 17        | 0.6%    |
| Samsung SSD 850 EVO 500GB          | 17        | 0.6%    |
| Kingston SA400S37240G 240GB SSD    | 17        | 0.6%    |
| Crucial CT500MX500SSD1 500GB       | 16        | 0.56%   |
| Samsung SSD 970 EVO 500GB          | 15        | 0.53%   |
| WDC WDS500G2B0A-00SM50 500GB SSD   | 14        | 0.49%   |
| Samsung SSD 970 EVO Plus 500GB     | 14        | 0.49%   |
| Samsung SSD 860 EVO 250GB          | 14        | 0.49%   |
| Samsung NVMe SSD Drive 1TB         | 14        | 0.49%   |
| Kingston SA400S37120G 120GB SSD    | 14        | 0.49%   |
| Unknown SD/MMC/MS PRO 1TB          | 13        | 0.46%   |
| Seagate ST2000DM001-1ER164 2TB     | 13        | 0.46%   |
| Seagate ST1000DM010-2EP102 1TB     | 13        | 0.46%   |
| Samsung SSD 860 QVO 1TB            | 13        | 0.46%   |
| Samsung SSD 840 EVO 250GB          | 13        | 0.46%   |
| Samsung NVMe SSD Drive 500GB       | 13        | 0.46%   |
| Toshiba MQ04ABF100 1TB             | 12        | 0.42%   |
| Seagate ST500DM002-1BD142 500GB    | 12        | 0.42%   |
| Seagate ST3500418AS 500GB          | 12        | 0.42%   |
| Seagate ST1000DM003-1CH162 1TB     | 12        | 0.42%   |
| Samsung SSD 850 PRO 256GB          | 12        | 0.42%   |
| Samsung NVMe SSD Drive 512GB       | 12        | 0.42%   |
| Crucial CT240BX500SSD1 240GB       | 12        | 0.42%   |
| WDC WD10EZEX-08WN4A0 1TB           | 11        | 0.39%   |
| Toshiba DT01ACA100 1TB             | 11        | 0.39%   |
| Kingston SA400S37480G 480GB SSD    | 11        | 0.39%   |
| Toshiba MQ01ABD100 1TB             | 10        | 0.35%   |
| Toshiba DT01ACA200 2TB             | 10        | 0.35%   |
| Seagate Expansion Desk 8TB         | 10        | 0.35%   |
| Samsung SSD 970 EVO 1TB            | 10        | 0.35%   |
| Kingston SV300S37A120G 120GB SSD   | 10        | 0.35%   |
| Crucial CT1000MX500SSD1 1TB        | 10        | 0.35%   |
| Seagate ST2000LM015-2E8174 2TB     | 9         | 0.32%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 376       | 675    | 37.6%   |
| WDC                 | 295       | 499    | 29.5%   |
| Toshiba             | 115       | 152    | 11.5%   |
| Samsung Electronics | 54        | 81     | 5.4%    |
| Hitachi             | 51        | 62     | 5.1%    |
| HGST                | 46        | 63     | 4.6%    |
| Unknown             | 14        | 15     | 1.4%    |
| Fujitsu             | 12        | 14     | 1.2%    |
| SABRENT             | 5         | 6      | 0.5%    |
| Maxtor              | 5         | 5      | 0.5%    |
| Hewlett-Packard     | 5         | 8      | 0.5%    |
| Apple               | 5         | 7      | 0.5%    |
| WD MediaMax         | 2         | 2      | 0.2%    |
| JMicron Technology  | 2         | 2      | 0.2%    |
| Intenso             | 2         | 6      | 0.2%    |
| USB3.0              | 1         | 1      | 0.1%    |
| USB                 | 1         | 1      | 0.1%    |
| UD0401              | 1         | 1      | 0.1%    |
| Synology            | 1         | 1      | 0.1%    |
| MaxDigital          | 1         | 1      | 0.1%    |
| Magnetic Data       | 1         | 2      | 0.1%    |
| Inateck             | 1         | 1      | 0.1%    |
| IBM-207x            | 1         | 8      | 0.1%    |
| DELLBOSS            | 1         | 1      | 0.1%    |
| ASMT                | 1         | 2      | 0.1%    |
| ASMedia             | 1         | 1      | 0.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 262       | 383    | 29.87%  |
| Kingston            | 99        | 131    | 11.29%  |
| Crucial             | 91        | 121    | 10.38%  |
| SanDisk             | 90        | 107    | 10.26%  |
| WDC                 | 59        | 74     | 6.73%   |
| A-DATA Technology   | 24        | 31     | 2.74%   |
| Intel               | 21        | 25     | 2.39%   |
| Toshiba             | 17        | 21     | 1.94%   |
| PNY                 | 17        | 20     | 1.94%   |
| SK hynix            | 16        | 25     | 1.82%   |
| Micron Technology   | 14        | 22     | 1.6%    |
| Intenso             | 12        | 12     | 1.37%   |
| LITEON              | 11        | 12     | 1.25%   |
| China               | 11        | 12     | 1.25%   |
| SPCC                | 10        | 14     | 1.14%   |
| OCZ                 | 8         | 13     | 0.91%   |
| Apple               | 8         | 9      | 0.91%   |
| GOODRAM             | 7         | 7      | 0.8%    |
| Corsair             | 7         | 7      | 0.8%    |
| Transcend           | 6         | 7      | 0.68%   |
| Seagate             | 6         | 6      | 0.68%   |
| LITEONIT            | 6         | 6      | 0.68%   |
| Team                | 5         | 5      | 0.57%   |
| Plextor             | 4         | 5      | 0.46%   |
| Patriot             | 4         | 4      | 0.46%   |
| Mushkin             | 4         | 6      | 0.46%   |
| KingSpec            | 4         | 9      | 0.46%   |
| TO Exter            | 3         | 3      | 0.34%   |
| Hewlett-Packard     | 3         | 4      | 0.34%   |
| Biostar             | 3         | 5      | 0.34%   |
| Smart               | 2         | 2      | 0.23%   |
| Pioneer             | 2         | 6      | 0.23%   |
| MyDigitalSSD        | 2         | 2      | 0.23%   |
| Gigabyte Technology | 2         | 4      | 0.23%   |
| GALAX               | 2         | 2      | 0.23%   |
| ASMT                | 2         | 2      | 0.23%   |
| Advantech           | 2         | 2      | 0.23%   |
| Unknown             | 2         | 2      | 0.23%   |
| XrayDisk            | 1         | 1      | 0.11%   |
| WDC WDS2            | 1         | 1      | 0.11%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 793       | 1617   | 36.43%  |
| SSD     | 748       | 1162   | 34.36%  |
| NVMe    | 570       | 817    | 26.18%  |
| MMC     | 45        | 64     | 2.07%   |
| Unknown | 21        | 30     | 0.96%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 1149      | 2676   | 61.91%  |
| NVMe | 570       | 813    | 30.71%  |
| SAS  | 92        | 137    | 4.96%   |
| MMC  | 45        | 64     | 2.42%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 841       | 1374   | 49.88%  |
| 0.51-1.0   | 495       | 809    | 29.36%  |
| 1.01-2.0   | 189       | 331    | 11.21%  |
| 3.01-4.0   | 59        | 97     | 3.5%    |
| 2.01-3.0   | 57        | 83     | 3.38%   |
| 4.01-10.0  | 41        | 76     | 2.43%   |
| 10.01-20.0 | 4         | 9      | 0.24%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 449       | 28.87%  |
| 1001-2000      | 339       | 21.8%   |
| 501-1000       | 224       | 14.41%  |
| 2001-3000      | 205       | 13.18%  |
| 251-500        | 155       | 9.97%   |
| 101-250        | 95        | 6.11%   |
| Unknown        | 38        | 2.44%   |
| 51-100         | 23        | 1.48%   |
| 1-20           | 16        | 1.03%   |
| 21-50          | 11        | 0.71%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 308       | 19.01%  |
| 251-500        | 292       | 18.02%  |
| 501-1000       | 228       | 14.07%  |
| 1001-2000      | 211       | 13.02%  |
| 51-100         | 211       | 13.02%  |
| More than 3000 | 98        | 6.05%   |
| 1-20           | 90        | 5.56%   |
| 2001-3000      | 79        | 4.88%   |
| 21-50          | 65        | 4.01%   |
| Unknown        | 38        | 2.35%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 5         | 7      | 2.23%   |
| Seagate ST3500418AS 500GB             | 4         | 4      | 1.79%   |
| Samsung Electronics SSD 840 EVO 120GB | 4         | 5      | 1.79%   |
| HGST HTS725050A7E630 500GB            | 4         | 4      | 1.79%   |
| Seagate ST2000DM001-1ER164 2TB        | 3         | 3      | 1.34%   |
| Seagate ST2000DM001-1CH164 2TB        | 3         | 4      | 1.34%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 3         | 3      | 1.34%   |
| Seagate ST1000DM003-1SB102 1TB        | 3         | 3      | 1.34%   |
| Samsung Electronics HD501LJ 500GB     | 3         | 4      | 1.34%   |
| WDC WD20EZRX-00DC0B0 2TB              | 2         | 3      | 0.89%   |
| Toshiba MQ01ABD100 1TB                | 2         | 2      | 0.89%   |
| Toshiba MK5055GSX 500GB               | 2         | 3      | 0.89%   |
| Seagate ST9500325AS 500GB             | 2         | 2      | 0.89%   |
| Seagate ST500LM000-1EJ162 500GB       | 2         | 2      | 0.89%   |
| Seagate ST31000528AS 1TB              | 2         | 5      | 0.89%   |
| Seagate ST1000LM035-1RK172 1TB        | 2         | 2      | 0.89%   |
| SanDisk SD8SN8U-256G-1006 256GB SSD   | 2         | 2      | 0.89%   |
| Samsung Electronics HN-M500MBB 500GB  | 2         | 2      | 0.89%   |
| Samsung Electronics HD322HJ 320GB     | 2         | 2      | 0.89%   |
| Samsung Electronics HD103SJ 1TB       | 2         | 3      | 0.89%   |
| Kingston SV300S37A120G 120GB SSD      | 2         | 3      | 0.89%   |
| Kingston SMS200S3240G 240GB SSD       | 2         | 2      | 0.89%   |
| Kingston SHFS37A120G 120GB SSD        | 2         | 2      | 0.89%   |
| Hitachi HTS547575A9E384 752GB         | 2         | 2      | 0.89%   |
| Hitachi HTS545050A7E380 500GB         | 2         | 2      | 0.89%   |
| HGST HTS721010A9E630 1TB              | 2         | 2      | 0.89%   |
| Crucial CT1000P1SSD8 1TB              | 2         | 2      | 0.89%   |
| XrayDisk SSD 256GB                    | 1         | 1      | 0.45%   |
| XPG GAMMIX S41 512GB                  | 1         | 1      | 0.45%   |
| WDC WDS480G2G0A-00JH30 480GB SSD      | 1         | 1      | 0.45%   |
| WDC WD800AAJS-75M0A0 80GB             | 1         | 1      | 0.45%   |
| WDC WD7500AAKS-00RBA0 752GB           | 1         | 1      | 0.45%   |
| WDC WD6400BEVT-22A0RT0 640GB          | 1         | 1      | 0.45%   |
| WDC WD6400AAKS-22A7B2 640GB           | 1         | 1      | 0.45%   |
| WDC WD6400AAKS-22A7B0 640GB           | 1         | 1      | 0.45%   |
| WDC WD6400AACS-00G8B1 640GB           | 1         | 1      | 0.45%   |
| WDC WD5000LPVX-00V0TT0 500GB          | 1         | 1      | 0.45%   |
| WDC WD5000BPVT-22HXZT3 500GB          | 1         | 1      | 0.45%   |
| WDC WD5000AVDS-63U7B1 500GB           | 1         | 1      | 0.45%   |
| WDC WD5000AAKX-221CA1 500GB           | 1         | 1      | 0.45%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 71     | 26.03%  |
| WDC                 | 34        | 40     | 15.53%  |
| Samsung Electronics | 30        | 37     | 13.7%   |
| Toshiba             | 22        | 31     | 10.05%  |
| Kingston            | 10        | 14     | 4.57%   |
| Hitachi             | 10        | 11     | 4.57%   |
| Crucial             | 8         | 9      | 3.65%   |
| HGST                | 7         | 7      | 3.2%    |
| SanDisk             | 6         | 6      | 2.74%   |
| Intel               | 5         | 6      | 2.28%   |
| Maxtor              | 3         | 3      | 1.37%   |
| SK hynix            | 2         | 2      | 0.91%   |
| OCZ                 | 2         | 2      | 0.91%   |
| LITEONIT            | 2         | 2      | 0.91%   |
| Fujitsu             | 2         | 2      | 0.91%   |
| Corsair             | 2         | 2      | 0.91%   |
| XrayDisk            | 1         | 1      | 0.46%   |
| XPG                 | 1         | 1      | 0.46%   |
| WD MediaMax         | 1         | 1      | 0.46%   |
| Transcend           | 1         | 1      | 0.46%   |
| SuperTalent         | 1         | 1      | 0.46%   |
| SSSTC               | 1         | 1      | 0.46%   |
| SPCC                | 1         | 1      | 0.46%   |
| Phison              | 1         | 1      | 0.46%   |
| Patriot             | 1         | 1      | 0.46%   |
| Micron Technology   | 1         | 1      | 0.46%   |
| LEQIXIANG           | 1         | 1      | 0.46%   |
| KingFast            | 1         | 1      | 0.46%   |
| Intenso             | 1         | 1      | 0.46%   |
| Hewlett-Packard     | 1         | 1      | 0.46%   |
| GOODRAM             | 1         | 1      | 0.46%   |
| Apple               | 1         | 1      | 0.46%   |
| A-DATA Technology   | 1         | 2      | 0.46%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 57        | 71     | 37.5%   |
| WDC                 | 33        | 39     | 21.71%  |
| Toshiba             | 21        | 30     | 13.82%  |
| Samsung Electronics | 16        | 22     | 10.53%  |
| Hitachi             | 10        | 11     | 6.58%   |
| HGST                | 7         | 7      | 4.61%   |
| Maxtor              | 3         | 3      | 1.97%   |
| Fujitsu             | 2         | 2      | 1.32%   |
| WD MediaMax         | 1         | 1      | 0.66%   |
| Hewlett-Packard     | 1         | 1      | 0.66%   |
| Apple               | 1         | 1      | 0.66%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 137       | 188    | 67.82%  |
| SSD  | 55        | 65     | 27.23%  |
| NVMe | 10        | 10     | 4.95%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD20EADS-00R6B0 2TB           | 1         | 1      | 33.33%  |
| Samsung Electronics HD502HJ 500GB | 1         | 3      | 33.33%  |
| Hitachi HDS721025CLA382 250GB     | 1         | 1      | 33.33%  |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 1         | 1      | 33.33%  |
| Samsung Electronics | 1         | 3      | 33.33%  |
| Hitachi             | 1         | 1      | 33.33%  |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 941       | 2003   | 55.09%  |
| Detected | 569       | 1419   | 33.31%  |
| Malfunc  | 195       | 263    | 11.42%  |
| Failed   | 3         | 5      | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 905       | 44.06%  |
| AMD                              | 408       | 19.86%  |
| Samsung Electronics              | 226       | 11%     |
| SanDisk                          | 78        | 3.8%    |
| ASMedia Technology               | 52        | 2.53%   |
| SK hynix                         | 46        | 2.24%   |
| Phison Electronics               | 41        | 2%      |
| Kingston Technology Company      | 38        | 1.85%   |
| Toshiba America Info Systems     | 33        | 1.61%   |
| Marvell Technology Group         | 27        | 1.31%   |
| JMicron Technology               | 23        | 1.12%   |
| Silicon Motion                   | 21        | 1.02%   |
| Nvidia                           | 21        | 1.02%   |
| Micron/Crucial Technology        | 17        | 0.83%   |
| Micron Technology                | 15        | 0.73%   |
| LSI Logic / Symbios Logic        | 14        | 0.68%   |
| ADATA Technology                 | 13        | 0.63%   |
| KIOXIA                           | 11        | 0.54%   |
| Broadcom / LSI                   | 11        | 0.54%   |
| Realtek Semiconductor            | 7         | 0.34%   |
| Silicon Image                    | 5         | 0.24%   |
| VIA Technologies                 | 4         | 0.19%   |
| Union Memory (Shenzhen)          | 4         | 0.19%   |
| Seagate Technology               | 4         | 0.19%   |
| Adaptec                          | 4         | 0.19%   |
| Solid State Storage Technology   | 3         | 0.15%   |
| Shenzhen Longsys Electronics     | 3         | 0.15%   |
| Lite-On Technology               | 3         | 0.15%   |
| Lenovo                           | 3         | 0.15%   |
| Yangtze Memory Technologies      | 2         | 0.1%    |
| Promise Technology               | 2         | 0.1%    |
| MAXIO Technology (Hangzhou)      | 2         | 0.1%    |
| Apple                            | 2         | 0.1%    |
| Tekram Technology                | 1         | 0.05%   |
| Silicon Integrated Systems [SiS] | 1         | 0.05%   |
| Hewlett-Packard                  | 1         | 0.05%   |
| Biwin Storage Technology         | 1         | 0.05%   |
| ATTO Technology                  | 1         | 0.05%   |
| 3ware                            | 1         | 0.05%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 282       | 11.95%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 131       | 5.55%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 83        | 3.52%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 77        | 3.26%   |
| AMD 400 Series Chipset SATA Controller                                         | 66        | 2.8%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 61        | 2.59%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 53        | 2.25%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 48        | 2.03%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 47        | 1.99%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 45        | 1.91%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 39        | 1.65%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 37        | 1.57%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 32        | 1.36%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 32        | 1.36%   |
| AMD 500 Series Chipset SATA Controller                                         | 32        | 1.36%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 30        | 1.27%   |
| Samsung NVMe SSD Controller 980                                                | 29        | 1.23%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 29        | 1.23%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 29        | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 28        | 1.19%   |
| Intel Volume Management Device NVMe RAID Controller                            | 28        | 1.19%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 27        | 1.14%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 27        | 1.14%   |
| Phison E12 NVMe Controller                                                     | 26        | 1.1%    |
| Intel SSD 660P Series                                                          | 25        | 1.06%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 24        | 1.02%   |
| AMD 300 Series Chipset SATA Controller                                         | 24        | 1.02%   |
| SK hynix Gold P31 SSD                                                          | 22        | 0.93%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 22        | 0.93%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 22        | 0.93%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 20        | 0.85%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 19        | 0.81%   |
| Intel Comet Lake SATA AHCI Controller                                          | 19        | 0.81%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 19        | 0.81%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 18        | 0.76%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 16        | 0.68%   |
| AMD X370 Series Chipset SATA Controller                                        | 16        | 0.68%   |
| Micron Non-Volatile memory controller                                          | 15        | 0.64%   |
| JMicron JMB363 SATA/IDE Controller                                             | 15        | 0.64%   |
| Intel SATA Controller [RAID mode]                                              | 15        | 0.64%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 1167      | 57.32%  |
| NVMe | 565       | 27.75%  |
| IDE  | 167       | 8.2%    |
| RAID | 115       | 5.65%   |
| SAS  | 11        | 0.54%   |
| SCSI | 11        | 0.54%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 998       | 66.85%  |
| AMD    | 489       | 32.75%  |
| ARM    | 6         | 0.4%    |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 5 3600 6-Core Processor             | 20        | 1.34%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 18        | 1.2%    |
| Intel Core i5-8265U CPU @ 1.60GHz             | 16        | 1.07%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 15        | 1%      |
| Intel Core i5-6200U CPU @ 2.30GHz             | 15        | 1%      |
| AMD Ryzen 7 3700X 8-Core Processor            | 15        | 1%      |
| Intel Core i7-8550U CPU @ 1.80GHz             | 14        | 0.94%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 14        | 0.94%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 14        | 0.94%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 14        | 0.94%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 14        | 0.94%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 14        | 0.94%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 13        | 0.87%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 13        | 0.87%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 13        | 0.87%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 12        | 0.8%    |
| Intel Core i7-8565U CPU @ 1.80GHz             | 11        | 0.74%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 11        | 0.74%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 11        | 0.74%   |
| AMD FX-8350 Eight-Core Processor              | 11        | 0.74%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 10        | 0.67%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 10        | 0.67%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 10        | 0.67%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 10        | 0.67%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 9         | 0.6%    |
| Intel Core i7-6500U CPU @ 2.50GHz             | 9         | 0.6%    |
| Intel Core i5-3320M CPU @ 2.60GHz             | 9         | 0.6%    |
| AMD Ryzen 7 4700U with Radeon Graphics        | 9         | 0.6%    |
| AMD Ryzen 5 5600X 6-Core Processor            | 9         | 0.6%    |
| Intel Core i7-4790 CPU @ 3.60GHz              | 8         | 0.53%   |
| Intel Core i7-4770 CPU @ 3.40GHz              | 8         | 0.53%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 8         | 0.53%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 8         | 0.53%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 8         | 0.53%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 8         | 0.53%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 8         | 0.53%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 8         | 0.53%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 8         | 0.53%   |
| AMD Ryzen 3 2200G with Radeon Vega Graphics   | 8         | 0.53%   |
| Intel Core i9-9900K CPU @ 3.60GHz             | 7         | 0.47%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 330       | 22.07%  |
| Intel Core i5           | 310       | 20.74%  |
| AMD Ryzen 5             | 135       | 9.03%   |
| AMD Ryzen 7             | 106       | 7.09%   |
| Other                   | 84        | 5.62%   |
| Intel Core i3           | 70        | 4.68%   |
| Intel Xeon              | 55        | 3.68%   |
| Intel Core 2 Duo        | 42        | 2.81%   |
| AMD Ryzen 9             | 42        | 2.81%   |
| Intel Celeron           | 34        | 2.27%   |
| AMD FX                  | 34        | 2.27%   |
| Intel Pentium           | 20        | 1.34%   |
| AMD Ryzen 3             | 20        | 1.34%   |
| Intel Core i9           | 14        | 0.94%   |
| AMD Ryzen 7 PRO         | 14        | 0.94%   |
| AMD Phenom II X4        | 14        | 0.94%   |
| AMD A8                  | 13        | 0.87%   |
| Intel Pentium Dual-Core | 12        | 0.8%    |
| Intel Atom              | 12        | 0.8%    |
| AMD A10                 | 11        | 0.74%   |
| AMD Athlon              | 10        | 0.67%   |
| AMD Ryzen 5 PRO         | 9         | 0.6%    |
| AMD A6                  | 9         | 0.6%    |
| AMD Phenom II X6        | 8         | 0.54%   |
| Intel Core 2 Quad       | 7         | 0.47%   |
| AMD Athlon II X2        | 7         | 0.47%   |
| Intel Pentium Silver    | 6         | 0.4%    |
| Intel Core 2            | 5         | 0.33%   |
| AMD Ryzen Threadripper  | 5         | 0.33%   |
| AMD Opteron             | 5         | 0.33%   |
| AMD A4                  | 5         | 0.33%   |
| AMD E2                  | 4         | 0.27%   |
| Intel Genuine           | 3         | 0.2%    |
| AMD E                   | 3         | 0.2%    |
| Intel Pentium Dual      | 2         | 0.13%   |
| Intel Core M            | 2         | 0.13%   |
| AMD Turion II Neo       | 2         | 0.13%   |
| AMD Ryzen 3 PRO         | 2         | 0.13%   |
| AMD EPYC                | 2         | 0.13%   |
| AMD Athlon X2           | 2         | 0.13%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 4       | 561       | 37.47%  |
| 2       | 481       | 32.13%  |
| 6       | 187       | 12.49%  |
| 8       | 160       | 10.69%  |
| 12      | 28        | 1.87%   |
| 16      | 20        | 1.34%   |
| 1       | 20        | 1.34%   |
| 3       | 11        | 0.73%   |
| 10      | 7         | 0.47%   |
| 32      | 4         | 0.27%   |
| Unknown | 4         | 0.27%   |
| 40      | 3         | 0.2%    |
| 24      | 3         | 0.2%    |
| 20      | 2         | 0.13%   |
| 14      | 2         | 0.13%   |
| 64      | 1         | 0.07%   |
| 48      | 1         | 0.07%   |
| 44      | 1         | 0.07%   |
| 18      | 1         | 0.07%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 1462      | 97.86%  |
| 2       | 25        | 1.67%   |
| 4       | 4         | 0.27%   |
| Unknown | 3         | 0.2%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 1108      | 74.01%  |
| 1       | 384       | 25.65%  |
| Unknown | 4         | 0.27%   |
| 8       | 1         | 0.07%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 1436      | 95.8%   |
| Unknown        | 55        | 3.67%   |
| 32-bit         | 7         | 0.47%   |
| 64-bit         | 1         | 0.07%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 137       | 9%      |
| 0x306c3    | 89        | 5.84%   |
| 0x206a7    | 85        | 5.58%   |
| 0x306a9    | 83        | 5.45%   |
| 0x506e3    | 52        | 3.41%   |
| 0x906ea    | 47        | 3.09%   |
| 0x806c1    | 45        | 2.95%   |
| 0x406e3    | 43        | 2.82%   |
| 0x08701021 | 41        | 2.69%   |
| 0x806ec    | 39        | 2.56%   |
| 0x806ea    | 37        | 2.43%   |
| 0x906e9    | 35        | 2.3%    |
| 0x806e9    | 34        | 2.23%   |
| 0x0a50000c | 34        | 2.23%   |
| 0x1067a    | 33        | 2.17%   |
| 0x0800820d | 32        | 2.1%    |
| 0x306d4    | 30        | 1.97%   |
| 0x40651    | 29        | 1.9%    |
| 0x08600106 | 26        | 1.71%   |
| 0x08108109 | 26        | 1.71%   |
| 0x06000852 | 26        | 1.71%   |
| 0x20655    | 20        | 1.31%   |
| 0x010000c8 | 20        | 1.31%   |
| 0x08701013 | 17        | 1.12%   |
| 0x08001138 | 17        | 1.12%   |
| 0x0a201009 | 16        | 1.05%   |
| 0x08600104 | 15        | 0.98%   |
| 0x08108102 | 15        | 0.98%   |
| 0x08608103 | 13        | 0.85%   |
| 0x06001119 | 13        | 0.85%   |
| 0x08001137 | 12        | 0.79%   |
| 0x806eb    | 11        | 0.72%   |
| 0x706a1    | 11        | 0.72%   |
| 0x6fd      | 11        | 0.72%   |
| 0x0810100b | 11        | 0.72%   |
| 0x06006705 | 11        | 0.72%   |
| 0x706a8    | 10        | 0.66%   |
| 0x306f2    | 10        | 0.66%   |
| 0xa0653    | 9         | 0.59%   |
| 0x706e5    | 9         | 0.59%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 240       | 16.04%  |
| Haswell          | 145       | 9.69%   |
| Zen 2            | 115       | 7.69%   |
| Skylake          | 108       | 7.22%   |
| IvyBridge        | 100       | 6.68%   |
| SandyBridge      | 93        | 6.22%   |
| Zen+             | 79        | 5.28%   |
| Zen 3            | 71        | 4.75%   |
| Zen              | 60        | 4.01%   |
| Penryn           | 49        | 3.28%   |
| TigerLake        | 45        | 3.01%   |
| Piledriver       | 42        | 2.81%   |
| K10              | 40        | 2.67%   |
| Broadwell        | 35        | 2.34%   |
| Westmere         | 32        | 2.14%   |
| Core             | 26        | 1.74%   |
| Unknown          | 26        | 1.74%   |
| CometLake        | 25        | 1.67%   |
| IceLake          | 23        | 1.54%   |
| Goldmont plus    | 21        | 1.4%    |
| Nehalem          | 19        | 1.27%   |
| Excavator        | 19        | 1.27%   |
| Silvermont       | 11        | 0.74%   |
| Alderlake Hybrid | 9         | 0.6%    |
| Bobcat           | 8         | 0.53%   |
| Steamroller      | 7         | 0.47%   |
| Bulldozer        | 7         | 0.47%   |
| Bonnell          | 7         | 0.47%   |
| K10 Llano        | 6         | 0.4%    |
| Jaguar           | 6         | 0.4%    |
| Puma             | 5         | 0.33%   |
| Goldmont         | 5         | 0.33%   |
| K8 Hammer        | 4         | 0.27%   |
| P6               | 3         | 0.2%    |
| K8 & K10 hybrid  | 3         | 0.2%    |
| Tremont          | 1         | 0.07%   |
| NetBurst         | 1         | 0.07%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 731       | 41.77%  |
| AMD                        | 514       | 29.37%  |
| Nvidia                     | 487       | 27.83%  |
| Matrox Electronics Systems | 12        | 0.69%   |
| ASPEED Technology          | 3         | 0.17%   |
| S3 Graphics                | 2         | 0.11%   |
| VIA Technologies           | 1         | 0.06%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller             | 60        | 3.32%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                               | 57        | 3.15%   |
| Intel 3rd Gen Core processor Graphics Controller                                      | 52        | 2.88%   |
| AMD Renoir                                                                            | 52        | 2.88%   |
| Intel Skylake GT2 [HD Graphics 520]                                                   | 45        | 2.49%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                             | 42        | 2.32%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                  | 41        | 2.27%   |
| Intel UHD Graphics 620                                                                | 39        | 2.16%   |
| AMD Cezanne                                                                           | 37        | 2.05%   |
| Intel HD Graphics 620                                                                 | 36        | 1.99%   |
| Intel Haswell-ULT Integrated Graphics Controller                                      | 33        | 1.83%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                             | 33        | 1.83%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                            | 32        | 1.77%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                           | 32        | 1.77%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller           | 31        | 1.71%   |
| Intel HD Graphics 530                                                                 | 31        | 1.71%   |
| Intel HD Graphics 630                                                                 | 30        | 1.66%   |
| Intel HD Graphics 5500                                                                | 24        | 1.33%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                               | 22        | 1.22%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                  | 21        | 1.16%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                      | 21        | 1.16%   |
| Intel Core Processor Integrated Graphics Controller                                   | 19        | 1.05%   |
| AMD Lucienne                                                                          | 17        | 0.94%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                    | 16        | 0.88%   |
| Intel GeminiLake [UHD Graphics 600]                                                   | 15        | 0.83%   |
| Intel CoffeeLake-S GT2 [UHD Graphics 630]                                             | 14        | 0.77%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                               | 13        | 0.72%   |
| Nvidia GK208B [GeForce GT 710]                                                        | 13        | 0.72%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                      | 13        | 0.72%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                              | 13        | 0.72%   |
| AMD Baffin [Radeon RX 460/560D / Pro 450/455/460/555/555X/560/560X]                   | 13        | 0.72%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                            | 12        | 0.66%   |
| Nvidia GP104 [GeForce GTX 1070]                                                       | 11        | 0.61%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                          | 11        | 0.61%   |
| Nvidia GP104 [GeForce GTX 1080]                                                       | 10        | 0.55%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile] | 10        | 0.55%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                            | 9         | 0.5%    |
| Nvidia GM107M [GeForce GTX 960M]                                                      | 9         | 0.5%    |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                     | 9         | 0.5%    |
| AMD Baffin [Radeon RX 550 640SP / RX 560/560X]                                        | 9         | 0.5%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x Intel          | 503       | 33.56%  |
| 1 x AMD            | 419       | 27.95%  |
| 1 x Nvidia         | 273       | 18.21%  |
| Intel + Nvidia     | 172       | 11.47%  |
| Intel + AMD        | 36        | 2.4%    |
| AMD + Nvidia       | 31        | 2.07%   |
| 2 x AMD            | 29        | 1.93%   |
| 1 x Matrox         | 10        | 0.67%   |
| Other              | 8         | 0.53%   |
| 2 x Nvidia         | 6         | 0.4%    |
| 2 x Intel          | 3         | 0.2%    |
| Nvidia + ASPEED    | 3         | 0.2%    |
| 1 x S3 Graphics    | 2         | 0.13%   |
| 1 x VIA            | 1         | 0.07%   |
| Nvidia + Matrox    | 1         | 0.07%   |
| Intel + 2 x Nvidia | 1         | 0.07%   |
| AMD + Matrox       | 1         | 0.07%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 1193      | 78.8%   |
| Proprietary | 288       | 19.02%  |
| Unknown     | 33        | 2.18%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 697       | 45.7%   |
| 1.01-2.0   | 202       | 13.25%  |
| 0.01-0.5   | 185       | 12.13%  |
| 3.01-4.0   | 130       | 8.52%   |
| 0.51-1.0   | 114       | 7.48%   |
| 7.01-8.0   | 107       | 7.02%   |
| 5.01-6.0   | 43        | 2.82%   |
| 8.01-16.0  | 29        | 1.9%    |
| 2.01-3.0   | 11        | 0.72%   |
| 16.01-24.0 | 6         | 0.39%   |
| 4.01-5.0   | 1         | 0.07%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 216       | 12.39%  |
| AU Optronics            | 187       | 10.73%  |
| LG Display              | 142       | 8.15%   |
| Dell                    | 135       | 7.75%   |
| Chimei Innolux          | 130       | 7.46%   |
| BOE                     | 116       | 6.66%   |
| Goldstar                | 104       | 5.97%   |
| Hewlett-Packard         | 74        | 4.25%   |
| Ancor Communications    | 61        | 3.5%    |
| BenQ                    | 58        | 3.33%   |
| Acer                    | 58        | 3.33%   |
| AOC                     | 44        | 2.52%   |
| Lenovo                  | 39        | 2.24%   |
| Philips                 | 37        | 2.12%   |
| Sharp                   | 33        | 1.89%   |
| Apple                   | 30        | 1.72%   |
| Iiyama                  | 19        | 1.09%   |
| ASUSTek Computer        | 18        | 1.03%   |
| ViewSonic               | 15        | 0.86%   |
| PANDA                   | 15        | 0.86%   |
| Fujitsu Siemens         | 14        | 0.8%    |
| Unknown                 | 13        | 0.75%   |
| InfoVision              | 13        | 0.75%   |
| Chi Mei Optoelectronics | 12        | 0.69%   |
| LG Electronics          | 11        | 0.63%   |
| Eizo                    | 9         | 0.52%   |
| Vizio                   | 8         | 0.46%   |
| Sony                    | 8         | 0.46%   |
| Sceptre Tech            | 7         | 0.4%    |
| LG Philips              | 7         | 0.4%    |
| Panasonic               | 6         | 0.34%   |
| NEC Computers           | 5         | 0.29%   |
| CSO                     | 5         | 0.29%   |
| Pixio                   | 4         | 0.23%   |
| Medion                  | 4         | 0.23%   |
| HannStar                | 4         | 0.23%   |
| CPT                     | 4         | 0.23%   |
| Toshiba                 | 3         | 0.17%   |
| TMX                     | 3         | 0.17%   |
| MSI                     | 3         | 0.17%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                | Computers | Percent |
|----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch     | 9         | 0.49%   |
| BenQ GW2760HS BNQ78CA 1920x1080 598x336mm 27.0-inch                  | 9         | 0.49%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch         | 8         | 0.43%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch       | 8         | 0.43%   |
| BenQ GW2270 BNQ78DB 1920x1080 480x270mm 21.7-inch                    | 7         | 0.38%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch    | 6         | 0.33%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch             | 6         | 0.33%   |
| Goldstar LG HDR 4K GSM7707 3840x2160 600x340mm 27.2-inch             | 6         | 0.33%   |
| Goldstar HDR WFHD GSM7714 2560x1080 798x334mm 34.1-inch              | 6         | 0.33%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch               | 6         | 0.33%   |
| Fujitsu Siemens P19-2 FUS0552 1280x1024 376x301mm 19.0-inch          | 6         | 0.33%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch     | 6         | 0.33%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch       | 6         | 0.33%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 520x290mm 23.4-inch    | 5         | 0.27%   |
| PANDA LCD Monitor NCP002D 1920x1080 344x194mm 15.5-inch              | 5         | 0.27%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch          | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN1735 1920x1080 382x215mm 17.3-inch     | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN15D5 1920x1080 344x193mm 15.5-inch     | 5         | 0.27%   |
| Chimei Innolux LCD Monitor CMN14C3 1366x768 309x173mm 13.9-inch      | 5         | 0.27%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO61ED 1920x1080 344x194mm 15.5-inch       | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch       | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch       | 5         | 0.27%   |
| AU Optronics LCD Monitor AUO109D 1920x1080 381x214mm 17.2-inch       | 5         | 0.27%   |
| Sharp LCD Monitor SHP148D 3840x2160 344x194mm 15.5-inch              | 4         | 0.22%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 344x194mm 15.5-inch | 4         | 0.22%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch | 4         | 0.22%   |
| Samsung Electronics C32F391 SAM0D35 1920x1080 698x393mm 31.5-inch    | 4         | 0.22%   |
| Philips PHL 243V7 PHLC155 1920x1080 530x300mm 24.0-inch              | 4         | 0.22%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch         | 4         | 0.22%   |
| LG Display LCD Monitor LGD02D8 1366x768 277x156mm 12.5-inch          | 4         | 0.22%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch              | 4         | 0.22%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch            | 4         | 0.22%   |
| Goldstar Ultra HD GSM5B09 3840x2160 600x340mm 27.2-inch              | 4         | 0.22%   |
| Goldstar FULL HD GSM5ABB 1920x1080 480x270mm 21.7-inch               | 4         | 0.22%   |
| Dell U2713HM DEL4080 2560x1440 597x336mm 27.0-inch                   | 4         | 0.22%   |
| Dell U2415 DELA0B8 1920x1200 518x324mm 24.1-inch                     | 4         | 0.22%   |
| Dell U2410 DELF017 1920x1200 518x324mm 24.1-inch                     | 4         | 0.22%   |
| Dell P2219H DELA114 1920x1080 476x267mm 21.5-inch                    | 4         | 0.22%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch     | 4         | 0.22%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 808       | 48.21%  |
| 1366x768 (WXGA)    | 200       | 11.93%  |
| 2560x1440 (QHD)    | 119       | 7.1%    |
| 3840x2160 (4K)     | 110       | 6.56%   |
| 1600x900 (HD+)     | 63        | 3.76%   |
| 1920x1200 (WUXGA)  | 47        | 2.8%    |
| 1680x1050 (WSXGA+) | 44        | 2.63%   |
| 1280x1024 (SXGA)   | 44        | 2.63%   |
| 1440x900 (WXGA+)   | 31        | 1.85%   |
| 1280x800 (WXGA)    | 31        | 1.85%   |
| 2560x1080          | 27        | 1.61%   |
| Unknown            | 25        | 1.49%   |
| 3440x1440          | 21        | 1.25%   |
| 3840x1080          | 14        | 0.84%   |
| 1024x768 (XGA)     | 13        | 0.78%   |
| 2560x1600          | 8         | 0.48%   |
| 3200x1800 (QHD+)   | 6         | 0.36%   |
| 2880x1800          | 6         | 0.36%   |
| 1360x768           | 6         | 0.36%   |
| 3840x1200          | 4         | 0.24%   |
| 2160x1440          | 4         | 0.24%   |
| 1024x600           | 4         | 0.24%   |
| 3840x2400          | 3         | 0.18%   |
| 1600x1200          | 3         | 0.18%   |
| 1280x720 (HD)      | 3         | 0.18%   |
| 3456x2160          | 2         | 0.12%   |
| 2048x1536          | 2         | 0.12%   |
| 1400x1050          | 2         | 0.12%   |
| 1280x960           | 2         | 0.12%   |
| 8960x2160          | 1         | 0.06%   |
| 800x1280           | 1         | 0.06%   |
| 7680x1440          | 1         | 0.06%   |
| 7280x2160          | 1         | 0.06%   |
| 6520x1440          | 1         | 0.06%   |
| 640x480            | 1         | 0.06%   |
| 5760x2160          | 1         | 0.06%   |
| 5520x1080          | 1         | 0.06%   |
| 4480x1440          | 1         | 0.06%   |
| 3840x2560          | 1         | 0.06%   |
| 3840x1600          | 1         | 0.06%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 380       | 21.8%   |
| 27      | 187       | 10.73%  |
| 24      | 145       | 8.32%   |
| 14      | 143       | 8.2%    |
| 13      | 130       | 7.46%   |
| 21      | 118       | 6.77%   |
| 23      | 106       | 6.08%   |
| 17      | 92        | 5.28%   |
| Unknown | 73        | 4.19%   |
| 19      | 47        | 2.7%    |
| 31      | 39        | 2.24%   |
| 12      | 39        | 2.24%   |
| 34      | 34        | 1.95%   |
| 22      | 30        | 1.72%   |
| 18      | 26        | 1.49%   |
| 20      | 19        | 1.09%   |
| 32      | 16        | 0.92%   |
| 11      | 13        | 0.75%   |
| 25      | 12        | 0.69%   |
| 26      | 11        | 0.63%   |
| 84      | 10        | 0.57%   |
| 72      | 9         | 0.52%   |
| 29      | 8         | 0.46%   |
| 16      | 8         | 0.46%   |
| 54      | 7         | 0.4%    |
| 40      | 4         | 0.23%   |
| 28      | 4         | 0.23%   |
| 10      | 4         | 0.23%   |
| 74      | 3         | 0.17%   |
| 52      | 3         | 0.17%   |
| 49      | 3         | 0.17%   |
| 42      | 3         | 0.17%   |
| 60      | 2         | 0.11%   |
| 37      | 2         | 0.11%   |
| 35      | 2         | 0.11%   |
| 33      | 2         | 0.11%   |
| 142     | 1         | 0.06%   |
| 69      | 1         | 0.06%   |
| 48      | 1         | 0.06%   |
| 47      | 1         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 583       | 34.09%  |
| 501-600        | 411       | 24.04%  |
| 401-500        | 209       | 12.22%  |
| 201-300        | 126       | 7.37%   |
| 351-400        | 124       | 7.25%   |
| 601-700        | 76        | 4.44%   |
| Unknown        | 73        | 4.27%   |
| 701-800        | 51        | 2.98%   |
| 1501-2000      | 23        | 1.35%   |
| 1001-1500      | 19        | 1.11%   |
| 801-900        | 9         | 0.53%   |
| 901-1000       | 3         | 0.18%   |
| 101-200        | 2         | 0.12%   |
| More than 2000 | 1         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 1182      | 76.11%  |
| 16/10   | 176       | 11.33%  |
| Unknown | 63        | 4.06%   |
| 21/9    | 39        | 2.51%   |
| 5/4     | 38        | 2.45%   |
| 4/3     | 29        | 1.87%   |
| 3/2     | 15        | 0.97%   |
| 6/5     | 4         | 0.26%   |
| 2.65    | 3         | 0.19%   |
| 32/9    | 1         | 0.06%   |
| 3.20    | 1         | 0.06%   |
| 1.00    | 1         | 0.06%   |
| 0.62    | 1         | 0.06%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 381       | 22.07%  |
| 201-250        | 311       | 18.02%  |
| 81-90          | 216       | 12.51%  |
| 301-350        | 192       | 11.12%  |
| 351-500        | 98        | 5.68%   |
| 151-200        | 98        | 5.68%   |
| Unknown        | 73        | 4.23%   |
| 121-130        | 71        | 4.11%   |
| 251-300        | 70        | 4.06%   |
| 71-80          | 59        | 3.42%   |
| More than 1000 | 39        | 2.26%   |
| 61-70          | 35        | 2.03%   |
| 141-150        | 33        | 1.91%   |
| 501-1000       | 14        | 0.81%   |
| 51-60          | 13        | 0.75%   |
| 131-140        | 9         | 0.52%   |
| 41-50          | 5         | 0.29%   |
| 91-100         | 5         | 0.29%   |
| 111-120        | 3         | 0.17%   |
| 1-40           | 1         | 0.06%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 569       | 34.07%  |
| 121-160       | 459       | 27.49%  |
| 101-120       | 395       | 23.65%  |
| 161-240       | 104       | 6.23%   |
| Unknown       | 73        | 4.37%   |
| More than 240 | 41        | 2.46%   |
| 1-50          | 29        | 1.74%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 1148      | 74.84%  |
| 2     | 309       | 20.14%  |
| 0     | 43        | 2.8%    |
| 3     | 31        | 2.02%   |
| 4     | 3         | 0.2%    |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 817       | 36.74%  |
| Intel                             | 788       | 35.43%  |
| Qualcomm Atheros                  | 198       | 8.9%    |
| Broadcom                          | 118       | 5.31%   |
| MediaTek                          | 32        | 1.44%   |
| TP-Link                           | 23        | 1.03%   |
| Broadcom Limited                  | 22        | 0.99%   |
| Ralink Technology                 | 20        | 0.9%    |
| Ralink                            | 20        | 0.9%    |
| ASIX Electronics                  | 18        | 0.81%   |
| Nvidia                            | 17        | 0.76%   |
| Marvell Technology Group          | 16        | 0.72%   |
| Sierra Wireless                   | 8         | 0.36%   |
| DisplayLink                       | 8         | 0.36%   |
| Edimax Technology                 | 6         | 0.27%   |
| D-Link                            | 6         | 0.27%   |
| Aquantia                          | 6         | 0.27%   |
| Samsung Electronics               | 5         | 0.22%   |
| Microsoft                         | 5         | 0.22%   |
| Lenovo                            | 5         | 0.22%   |
| Hewlett-Packard                   | 5         | 0.22%   |
| Ericsson Business Mobile Networks | 5         | 0.22%   |
| Qualcomm Atheros Communications   | 4         | 0.18%   |
| NetGear                           | 4         | 0.18%   |
| Dell                              | 4         | 0.18%   |
| Motorola PCS                      | 3         | 0.13%   |
| Microchip Technology              | 3         | 0.13%   |
| Linksys                           | 3         | 0.13%   |
| ICS Advent                        | 3         | 0.13%   |
| D-Link System                     | 3         | 0.13%   |
| Cypress Semiconductor             | 3         | 0.13%   |
| AVM                               | 3         | 0.13%   |
| Xiaomi                            | 2         | 0.09%   |
| VIA Technologies                  | 2         | 0.09%   |
| Texas Instruments                 | 2         | 0.09%   |
| NetXen Incorporated               | 2         | 0.09%   |
| JMicron Technology                | 2         | 0.09%   |
| HMD Global                        | 2         | 0.09%   |
| Atmel                             | 2         | 0.09%   |
| ASUSTek Computer                  | 2         | 0.09%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 601       | 22.59%  |
| Intel Wi-Fi 6 AX200                                               | 109       | 4.1%    |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 63        | 2.37%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 60        | 2.25%   |
| Intel I211 Gigabit Network Connection                             | 59        | 2.22%   |
| Intel Wireless 8265 / 8275                                        | 54        | 2.03%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 44        | 1.65%   |
| Intel Wireless 7260                                               | 43        | 1.62%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 40        | 1.5%    |
| Intel Wireless 8260                                               | 39        | 1.47%   |
| Realtek RTL8125 2.5GbE Controller                                 | 36        | 1.35%   |
| Intel Wi-Fi 6 AX201                                               | 35        | 1.32%   |
| Intel Wireless-AC 9260                                            | 33        | 1.24%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 31        | 1.16%   |
| Intel Wireless 7265                                               | 31        | 1.16%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 29        | 1.09%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 1.09%   |
| Intel Ethernet Connection (2) I219-V                              | 29        | 1.09%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                      | 27        | 1.01%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 26        | 0.98%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 24        | 0.9%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 23        | 0.86%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 0.75%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 19        | 0.71%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                   | 18        | 0.68%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 17        | 0.64%   |
| Intel I210 Gigabit Network Connection                             | 17        | 0.64%   |
| Intel Ethernet Connection I217-V                                  | 17        | 0.64%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 17        | 0.64%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 17        | 0.64%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter               | 17        | 0.64%   |
| ASIX AX88179 Gigabit Ethernet                                     | 16        | 0.6%    |
| Intel Centrino Ultimate-N 6300                                    | 14        | 0.53%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                          | 14        | 0.53%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 13        | 0.49%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)    | 13        | 0.49%   |
| Intel Wireless 3160                                               | 13        | 0.49%   |
| Intel Ethernet Controller I225-V                                  | 13        | 0.49%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.49%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 583       | 51.19%  |
| Realtek Semiconductor           | 178       | 15.63%  |
| Qualcomm Atheros                | 151       | 13.26%  |
| Broadcom                        | 76        | 6.67%   |
| MediaTek                        | 27        | 2.37%   |
| Ralink Technology               | 20        | 1.76%   |
| Ralink                          | 20        | 1.76%   |
| TP-Link                         | 15        | 1.32%   |
| Broadcom Limited                | 14        | 1.23%   |
| Sierra Wireless                 | 8         | 0.7%    |
| Edimax Technology               | 6         | 0.53%   |
| D-Link                          | 6         | 0.53%   |
| Qualcomm Atheros Communications | 4         | 0.35%   |
| NetGear                         | 4         | 0.35%   |
| Microsoft                       | 4         | 0.35%   |
| Linksys                         | 3         | 0.26%   |
| AVM                             | 3         | 0.26%   |
| Marvell Technology Group        | 2         | 0.18%   |
| Dell                            | 2         | 0.18%   |
| D-Link System                   | 2         | 0.18%   |
| ASUSTek Computer                | 2         | 0.18%   |
| ZyXEL Communications            | 1         | 0.09%   |
| Xiaomi                          | 1         | 0.09%   |
| Realtek                         | 1         | 0.09%   |
| Qualcomm                        | 1         | 0.09%   |
| Intersil                        | 1         | 0.09%   |
| IMC Networks                    | 1         | 0.09%   |
| Hewlett-Packard                 | 1         | 0.09%   |
| BUFFALO                         | 1         | 0.09%   |
| Belkin Components               | 1         | 0.09%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 109       | 9.5%    |
| Intel Wireless 8265 / 8275                                     | 54        | 4.71%   |
| Intel Wireless 7260                                            | 43        | 3.75%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 40        | 3.49%   |
| Intel Wireless 8260                                            | 39        | 3.4%    |
| Intel Wi-Fi 6 AX201                                            | 35        | 3.05%   |
| Intel Wireless-AC 9260                                         | 33        | 2.88%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 31        | 2.7%    |
| Intel Wireless 7265                                            | 31        | 2.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 29        | 2.53%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 27        | 2.35%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 26        | 2.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 24        | 2.09%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 23        | 2.01%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 19        | 1.66%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 18        | 1.57%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 17        | 1.48%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 17        | 1.48%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 17        | 1.48%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 17        | 1.48%   |
| Intel Centrino Ultimate-N 6300                                 | 14        | 1.22%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                       | 14        | 1.22%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 13        | 1.13%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 13        | 1.13%   |
| Intel Wireless 3160                                            | 13        | 1.13%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 11        | 0.96%   |
| Intel Wireless 3165                                            | 11        | 0.96%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11        | 0.96%   |
| Intel Centrino Advanced-N 6235                                 | 11        | 0.96%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 10        | 0.87%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 10        | 0.87%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 10        | 0.87%   |
| Broadcom BCM43142 802.11b/g/n                                  | 10        | 0.87%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 9         | 0.78%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 8         | 0.7%    |
| Ralink MT7601U Wireless Adapter                                | 8         | 0.7%    |
| Broadcom BCM43224 802.11a/b/g/n                                | 8         | 0.7%    |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                | 7         | 0.61%   |
| Broadcom BCM4331 802.11a/b/g/n                                 | 7         | 0.61%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 6         | 0.52%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Realtek Semiconductor                  | 749       | 51.55%  |
| Intel                                  | 454       | 31.25%  |
| Qualcomm Atheros                       | 64        | 4.4%    |
| Broadcom                               | 59        | 4.06%   |
| ASIX Electronics                       | 18        | 1.24%   |
| Nvidia                                 | 17        | 1.17%   |
| Marvell Technology Group               | 14        | 0.96%   |
| TP-Link                                | 8         | 0.55%   |
| DisplayLink                            | 8         | 0.55%   |
| Broadcom Limited                       | 8         | 0.55%   |
| Aquantia                               | 6         | 0.41%   |
| Samsung Electronics                    | 5         | 0.34%   |
| MediaTek                               | 5         | 0.34%   |
| Lenovo                                 | 5         | 0.34%   |
| Motorola PCS                           | 3         | 0.21%   |
| ICS Advent                             | 3         | 0.21%   |
| Cypress Semiconductor                  | 3         | 0.21%   |
| VIA Technologies                       | 2         | 0.14%   |
| NetXen Incorporated                    | 2         | 0.14%   |
| JMicron Technology                     | 2         | 0.14%   |
| HMD Global                             | 2         | 0.14%   |
| Xiaomi                                 | 1         | 0.07%   |
| Sony Ericsson Mobile Communications AB | 1         | 0.07%   |
| Solarflare Communications              | 1         | 0.07%   |
| Silicon Integrated Systems [SiS]       | 1         | 0.07%   |
| OnePlus                                | 1         | 0.07%   |
| MosChip Semiconductor                  | 1         | 0.07%   |
| Microsoft                              | 1         | 0.07%   |
| Microchip Technology                   | 1         | 0.07%   |
| IBM                                    | 1         | 0.07%   |
| Hewlett-Packard                        | 1         | 0.07%   |
| Google                                 | 1         | 0.07%   |
| Emulex                                 | 1         | 0.07%   |
| D-Link System                          | 1         | 0.07%   |
| Chelsio Communications                 | 1         | 0.07%   |
| ADMtek                                 | 1         | 0.07%   |
| 3Com                                   | 1         | 0.07%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 601       | 40.39%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 63        | 4.23%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 60        | 4.03%   |
| Intel I211 Gigabit Network Connection                             | 59        | 3.97%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 44        | 2.96%   |
| Realtek RTL8125 2.5GbE Controller                                 | 36        | 2.42%   |
| Intel Ethernet Connection I217-LM                                 | 29        | 1.95%   |
| Intel Ethernet Connection (2) I219-V                              | 29        | 1.95%   |
| Intel Ethernet Connection (4) I219-LM                             | 20        | 1.34%   |
| Intel I210 Gigabit Network Connection                             | 17        | 1.14%   |
| Intel Ethernet Connection I217-V                                  | 17        | 1.14%   |
| ASIX AX88179 Gigabit Ethernet                                     | 16        | 1.08%   |
| Intel Ethernet Controller I225-V                                  | 13        | 0.87%   |
| Intel Ethernet Connection I219-LM                                 | 13        | 0.87%   |
| Intel Ethernet Connection (2) I219-LM                             | 13        | 0.87%   |
| Intel Ethernet Connection (7) I219-V                              | 12        | 0.81%   |
| Intel Ethernet Connection (4) I219-V                              | 12        | 0.81%   |
| Intel 82574L Gigabit Network Connection                           | 12        | 0.81%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 11        | 0.74%   |
| Intel Ethernet Connection I219-V                                  | 11        | 0.74%   |
| Intel Ethernet Connection I218-LM                                 | 11        | 0.74%   |
| Intel Ethernet Connection (3) I218-LM                             | 11        | 0.74%   |
| Intel Ethernet Connection (2) I218-V                              | 11        | 0.74%   |
| Intel 82579V Gigabit Network Connection                           | 11        | 0.74%   |
| Intel 82577LM Gigabit Network Connection                          | 11        | 0.74%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 10        | 0.67%   |
| Intel Ethernet Connection (7) I219-LM                             | 8         | 0.54%   |
| Intel Ethernet Connection (10) I219-V                             | 8         | 0.54%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 7         | 0.47%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 7         | 0.47%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 7         | 0.47%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 7         | 0.47%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 7         | 0.47%   |
| Nvidia MCP79 Ethernet                                             | 7         | 0.47%   |
| Intel Ethernet Connection (6) I219-V                              | 6         | 0.4%    |
| Intel Ethernet Connection (2) I218-LM                             | 6         | 0.4%    |
| Intel 82567LM-3 Gigabit Network Connection                        | 6         | 0.4%    |
| Broadcom NetXtreme II BCM5709 Gigabit Ethernet                    | 6         | 0.4%    |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 6         | 0.4%    |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 5         | 0.34%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 1323      | 54.42%  |
| WiFi     | 1084      | 44.59%  |
| Modem    | 17        | 0.7%    |
| Unknown  | 7         | 0.29%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 805       | 50.34%  |
| Ethernet | 793       | 49.59%  |
| Unknown  | 1         | 0.06%   |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 813       | 54.34%  |
| 1     | 587       | 39.24%  |
| 3     | 56        | 3.74%   |
| 0     | 18        | 1.2%    |
| 4     | 16        | 1.07%   |
| 5     | 4         | 0.27%   |
| 8     | 1         | 0.07%   |
| 6     | 1         | 0.07%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 1279      | 83.76%  |
| Yes  | 248       | 16.24%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 467       | 49.84%  |
| Realtek Semiconductor           | 87        | 9.28%   |
| Cambridge Silicon Radio         | 78        | 8.32%   |
| Qualcomm Atheros Communications | 64        | 6.83%   |
| Broadcom                        | 46        | 4.91%   |
| Lite-On Technology              | 36        | 3.84%   |
| Apple                           | 34        | 3.63%   |
| IMC Networks                    | 29        | 3.09%   |
| Foxconn / Hon Hai               | 25        | 2.67%   |
| ASUSTek Computer                | 18        | 1.92%   |
| Dell                            | 9         | 0.96%   |
| Hewlett-Packard                 | 8         | 0.85%   |
| Realtek                         | 6         | 0.64%   |
| Toshiba                         | 5         | 0.53%   |
| MediaTek                        | 4         | 0.43%   |
| Unknown                         | 3         | 0.32%   |
| Belkin Components               | 3         | 0.32%   |
| Marvell Semiconductor           | 2         | 0.21%   |
| HTC (High Tech Computer)        | 2         | 0.21%   |
| Foxconn International           | 2         | 0.21%   |
| USI                             | 1         | 0.11%   |
| TP-Link                         | 1         | 0.11%   |
| SINO WEALTH                     | 1         | 0.11%   |
| Ralink Technology               | 1         | 0.11%   |
| Ralink                          | 1         | 0.11%   |
| Qcom                            | 1         | 0.11%   |
| Mobile Action Technology        | 1         | 0.11%   |
| Integrated System Solution      | 1         | 0.11%   |
| Alps Electric                   | 1         | 0.11%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 169       | 18%     |
| Intel AX200 Bluetooth                                                               | 103       | 10.97%  |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 78        | 8.31%   |
| Intel AX201 Bluetooth                                                               | 64        | 6.82%   |
| Realtek Bluetooth Radio                                                             | 53        | 5.64%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 46        | 4.9%    |
| Qualcomm Atheros  Bluetooth Device                                                  | 32        | 3.41%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 32        | 3.41%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 24        | 2.56%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 22        | 2.34%   |
| Apple Bluetooth Host Controller                                                     | 17        | 1.81%   |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 16        | 1.7%    |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 14        | 1.49%   |
| IMC Networks Bluetooth Radio                                                        | 12        | 1.28%   |
| Broadcom BCM2045B (BDC-2.1)                                                         | 11        | 1.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 10        | 1.06%   |
| Intel AX210 Bluetooth                                                               | 10        | 1.06%   |
| Apple Bluetooth USB Host Controller                                                 | 9         | 0.96%   |
| IMC Networks Wireless_Device                                                        | 8         | 0.85%   |
| Lite-On Wireless_Device                                                             | 7         | 0.75%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 7         | 0.75%   |
| Realtek Bluetooth Radio                                                             | 6         | 0.64%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 6         | 0.64%   |
| Lite-On Bluetooth Device                                                            | 6         | 0.64%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 6         | 0.64%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 5         | 0.53%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 5         | 0.53%   |
| IMC Networks Bluetooth Device                                                       | 5         | 0.53%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 5         | 0.53%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 5         | 0.53%   |
| Realtek RTL8821A Bluetooth                                                          | 4         | 0.43%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 4         | 0.43%   |
| MediaTek Wireless_Device                                                            | 4         | 0.43%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 4         | 0.43%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 4         | 0.43%   |
| Foxconn / Hon Hai BCM20702A0                                                        | 4         | 0.43%   |
| Broadcom BCM20702 Bluetooth 4.0 [ThinkPad]                                          | 4         | 0.43%   |
| ASUS Bluetooth Adapter                                                              | 4         | 0.43%   |
| ASUS ASUS USB-BT500                                                                 | 4         | 0.43%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 4         | 0.43%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 947       | 44.84%  |
| AMD                         | 559       | 26.47%  |
| Nvidia                      | 313       | 14.82%  |
| C-Media Electronics         | 43        | 2.04%   |
| Creative Labs               | 24        | 1.14%   |
| Logitech                    | 20        | 0.95%   |
| Texas Instruments           | 17        | 0.8%    |
| Realtek Semiconductor       | 12        | 0.57%   |
| Creative Technology         | 11        | 0.52%   |
| JMTek                       | 9         | 0.43%   |
| GN Netcom                   | 8         | 0.38%   |
| Generalplus Technology      | 8         | 0.38%   |
| Sennheiser Communications   | 6         | 0.28%   |
| Razer USA                   | 6         | 0.28%   |
| Kingston Technology         | 6         | 0.28%   |
| Yamaha                      | 5         | 0.24%   |
| RODE Microphones            | 5         | 0.24%   |
| Plantronics                 | 5         | 0.24%   |
| M-Audio                     | 5         | 0.24%   |
| Lenovo                      | 5         | 0.24%   |
| Hewlett-Packard             | 5         | 0.24%   |
| Corsair                     | 5         | 0.24%   |
| BEHRINGER International     | 5         | 0.24%   |
| ASUSTek Computer            | 5         | 0.24%   |
| SteelSeries ApS             | 4         | 0.19%   |
| Samson Technologies         | 4         | 0.19%   |
| Focusrite-Novation          | 4         | 0.19%   |
| VIA Technologies            | 3         | 0.14%   |
| SAVITECH                    | 3         | 0.14%   |
| FiiO Electronics Technology | 3         | 0.14%   |
| Dell                        | 3         | 0.14%   |
| Apple                       | 3         | 0.14%   |
| ZOOM                        | 2         | 0.09%   |
| Fry's Electronics           | 2         | 0.09%   |
| ESS Technology              | 2         | 0.09%   |
| Conexant Systems            | 2         | 0.09%   |
| Blue Microphones            | 2         | 0.09%   |
| XMOS                        | 1         | 0.05%   |
| TerraTec Electronic         | 1         | 0.05%   |
| Tdlasunnic                  | 1         | 0.05%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 172       | 6.57%   |
| Intel Sunrise Point-LP HD Audio                                            | 125       | 4.78%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 102       | 3.9%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 92        | 3.52%   |
| AMD Starship/Matisse HD Audio Controller                                   | 86        | 3.29%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 84        | 3.21%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 83        | 3.17%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 72        | 2.75%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 71        | 2.71%   |
| Intel Cannon Lake PCH cAVS                                                 | 58        | 2.22%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 58        | 2.22%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 58        | 2.22%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 58        | 2.22%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 57        | 2.18%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 45        | 1.72%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 37        | 1.41%   |
| AMD FCH Azalia Controller                                                  | 37        | 1.41%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 33        | 1.26%   |
| Intel 8 Series HD Audio Controller                                         | 33        | 1.26%   |
| Intel Haswell-ULT HD Audio Controller                                      | 32        | 1.22%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 32        | 1.22%   |
| Intel Broadwell-U Audio Controller                                         | 31        | 1.19%   |
| Nvidia GP107GL High Definition Audio Controller                            | 30        | 1.15%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 30        | 1.15%   |
| AMD Navi 10 HDMI Audio                                                     | 29        | 1.11%   |
| Intel 200 Series PCH HD Audio                                              | 28        | 1.07%   |
| Nvidia GP104 High Definition Audio Controller                              | 26        | 0.99%   |
| AMD Oland/Hainan/Cape Verde/Pitcairn HDMI Audio [Radeon HD 7000 Series]    | 24        | 0.92%   |
| Intel Comet Lake PCH-LP cAVS                                               | 23        | 0.88%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 21        | 0.8%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 21        | 0.8%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 21        | 0.8%    |
| Intel CM238 HD Audio Controller                                            | 20        | 0.76%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 20        | 0.76%   |
| Nvidia TU116 High Definition Audio Controller                              | 19        | 0.73%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 19        | 0.73%   |
| AMD Kabini HDMI/DP Audio                                                   | 17        | 0.65%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 16        | 0.61%   |
| Intel Comet Lake PCH cAVS                                                  | 16        | 0.61%   |
| Nvidia GK107 HDMI Audio Controller                                         | 15        | 0.57%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor                                  | Computers | Percent |
|-----------------------------------------|-----------|---------|
| Samsung Electronics                     | 278       | 22.29%  |
| SK hynix                                | 197       | 15.8%   |
| Kingston                                | 159       | 12.75%  |
| Micron Technology                       | 128       | 10.26%  |
| Unknown                                 | 104       | 8.34%   |
| Crucial                                 | 89        | 7.14%   |
| Corsair                                 | 74        | 5.93%   |
| G.Skill                                 | 67        | 5.37%   |
| A-DATA Technology                       | 18        | 1.44%   |
| Ramaxel Technology                      | 17        | 1.36%   |
| Elpida                                  | 16        | 1.28%   |
| Patriot                                 | 14        | 1.12%   |
| Unknown (ABCD)                          | 10        | 0.8%    |
| Nanya Technology                        | 10        | 0.8%    |
| Smart                                   | 8         | 0.64%   |
| Avant                                   | 6         | 0.48%   |
| Transcend                               | 5         | 0.4%    |
| Team                                    | 5         | 0.4%    |
| Goodram                                 | 4         | 0.32%   |
| AMD                                     | 3         | 0.24%   |
| Teikon                                  | 2         | 0.16%   |
| Lexar                                   | 2         | 0.16%   |
| ASint Technology                        | 2         | 0.16%   |
| Unknown                                 | 2         | 0.16%   |
| Unknown (0x02BA)                        | 1         | 0.08%   |
| Unknown (07FB)                          | 1         | 0.08%   |
| Unknown (000004B30000)                  | 1         | 0.08%   |
| Unifosa                                 | 1         | 0.08%   |
| Toshiba                                 | 1         | 0.08%   |
| TakeMS                                  | 1         | 0.08%   |
| Super Talent                            | 1         | 0.08%   |
| Smart Modular                           | 1         | 0.08%   |
| Smart Brazil                            | 1         | 0.08%   |
| Silicon Power Computer & Communications | 1         | 0.08%   |
| Silicon Power                           | 1         | 0.08%   |
| SanDisk                                 | 1         | 0.08%   |
| Qimonda                                 | 1         | 0.08%   |
| Princeton                               | 1         | 0.08%   |
| pqi                                     | 1         | 0.08%   |
| PNY                                     | 1         | 0.08%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 15        | 1.13%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 14        | 1.05%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 14        | 1.05%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 11        | 0.83%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 10        | 0.75%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 10        | 0.75%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 8         | 0.6%    |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 7         | 0.53%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8192MB SODIMM DDR4 2667MT/s        | 7         | 0.53%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 7         | 0.53%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 7         | 0.53%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 7         | 0.53%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 7         | 0.53%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3200MT/s            | 7         | 0.53%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 6         | 0.45%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s           | 6         | 0.45%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 6         | 0.45%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 6         | 0.45%   |
| Samsung RAM M471B1G73EB0-YK0 8GB SODIMM DDR3 1600MT/s            | 6         | 0.45%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 6         | 0.45%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 6         | 0.45%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.45%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB SODIMM DDR4 3200MT/s             | 6         | 0.45%   |
| G.Skill RAM F4-3000C16-8GISB 8GB DIMM DDR4 3200MT/s              | 6         | 0.45%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 5         | 0.38%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 5         | 0.38%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 5         | 0.38%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 5         | 0.38%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s           | 5         | 0.38%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 5         | 0.38%   |
| Samsung RAM M471B5273CH0-CH9 4GB SODIMM DDR3 1334MT/s            | 5         | 0.38%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 5         | 0.38%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.38%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 5         | 0.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 5         | 0.38%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 5         | 0.38%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 2400MT/s            | 5         | 0.38%   |
| Micron RAM 16JSF51264HZ-1G4D1 4096MB SODIMM DDR3 1334MT/s        | 5         | 0.38%   |
| Kingston RAM KHX2400C15/8G 8GB DIMM DDR4 3400MT/s                | 5         | 0.38%   |
| Corsair RAM CMK32GX4M2B3200C16 16GB DIMM DDR4 3400MT/s           | 5         | 0.38%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 551       | 51.93%  |
| DDR3    | 336       | 31.67%  |
| DDR2    | 40        | 3.77%   |
| LPDDR4  | 39        | 3.68%   |
| Unknown | 35        | 3.3%    |
| LPDDR3  | 30        | 2.83%   |
| SDRAM   | 19        | 1.79%   |
| DDR     | 6         | 0.57%   |
| LPDDR5  | 2         | 0.19%   |
| DRAM    | 2         | 0.19%   |
| DDR5    | 1         | 0.09%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 566       | 53.15%  |
| DIMM         | 416       | 39.06%  |
| Row Of Chips | 68        | 6.38%   |
| Chip         | 11        | 1.03%   |
| RIMM         | 2         | 0.19%   |
| FB-DIMM      | 2         | 0.19%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 464       | 39.9%   |
| 4096  | 338       | 29.06%  |
| 16384 | 172       | 14.79%  |
| 2048  | 114       | 9.8%    |
| 32768 | 41        | 3.53%   |
| 1024  | 31        | 2.67%   |
| 512   | 2         | 0.17%   |
| 128   | 1         | 0.09%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 223       | 19.21%  |
| 2667    | 178       | 15.33%  |
| 3200    | 168       | 14.47%  |
| 2400    | 93        | 8.01%   |
| 1333    | 86        | 7.41%   |
| 2133    | 77        | 6.63%   |
| 3600    | 39        | 3.36%   |
| 1334    | 35        | 3.01%   |
| 800     | 23        | 1.98%   |
| 1867    | 22        | 1.89%   |
| 667     | 22        | 1.89%   |
| 4267    | 16        | 1.38%   |
| 3266    | 15        | 1.29%   |
| 1067    | 12        | 1.03%   |
| Unknown | 12        | 1.03%   |
| 3400    | 11        | 0.95%   |
| 2666    | 11        | 0.95%   |
| 3466    | 10        | 0.86%   |
| 1066    | 10        | 0.86%   |
| 3800    | 8         | 0.69%   |
| 1866    | 8         | 0.69%   |
| 4266    | 7         | 0.6%    |
| 3000    | 6         | 0.52%   |
| 2933    | 6         | 0.52%   |
| 2048    | 6         | 0.52%   |
| 8400    | 5         | 0.43%   |
| 2800    | 5         | 0.43%   |
| 975     | 5         | 0.43%   |
| 4199    | 4         | 0.34%   |
| 3666    | 4         | 0.34%   |
| 3866    | 3         | 0.26%   |
| 3733    | 3         | 0.26%   |
| 533     | 3         | 0.26%   |
| 333     | 3         | 0.26%   |
| 3334    | 2         | 0.17%   |
| 3151    | 2         | 0.17%   |
| 3007    | 2         | 0.17%   |
| 1800    | 2         | 0.17%   |
| 400     | 2         | 0.17%   |
| 49926   | 1         | 0.09%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 20        | 42.55%  |
| Samsung Electronics | 8         | 17.02%  |
| Brother Industries  | 7         | 14.89%  |
| Seiko Epson         | 5         | 10.64%  |
| Canon               | 3         | 6.38%   |
| Prolific Technology | 2         | 4.26%   |
| Pantum              | 1         | 2.13%   |
| Kyocera             | 1         | 2.13%   |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                           | Computers | Percent |
|-------------------------------------------------|-----------|---------|
| Seiko Epson ET-2710 Series                      | 2         | 4.17%   |
| Samsung M262x/M282x Xpress Series Laser Printer | 2         | 4.17%   |
| Prolific PL2305 Parallel Port                   | 2         | 4.17%   |
| HP Officejet 4500 G510g-m                       | 2         | 4.17%   |
| Seiko Epson XP-243 245 247 Series               | 1         | 2.08%   |
| Seiko Epson XP-230 Series                       | 1         | 2.08%   |
| Seiko Epson L3160 Series                        | 1         | 2.08%   |
| Seiko Epson L1300 Series                        | 1         | 2.08%   |
| Samsung SCX-4200 series                         | 1         | 2.08%   |
| Samsung SCX-3400 Series                         | 1         | 2.08%   |
| Samsung ML-191x/ML-252x Laser Printer           | 1         | 2.08%   |
| Samsung ML-1865                                 | 1         | 2.08%   |
| Samsung M267x 287x Series                       | 1         | 2.08%   |
| Samsung M2020 Series                            | 1         | 2.08%   |
| Pantum P2500W-series                            | 1         | 2.08%   |
| Kyocera FS-1030D printer                        | 1         | 2.08%   |
| HP Smart Tank Plus 550 series                   | 1         | 2.08%   |
| HP Smart Install                                | 1         | 2.08%   |
| HP OfficeJet 5200 series                        | 1         | 2.08%   |
| HP Officejet 4620 series                        | 1         | 2.08%   |
| HP LaserJet Professional P 1102w                | 1         | 2.08%   |
| HP LaserJet P1102                               | 1         | 2.08%   |
| HP LaserJet 1320                                | 1         | 2.08%   |
| HP LaserJet 1020                                | 1         | 2.08%   |
| HP LaserJet 1018                                | 1         | 2.08%   |
| HP ENVY 4520 series                             | 1         | 2.08%   |
| HP ENVY 4500 series                             | 1         | 2.08%   |
| HP Deskjet Ink Advant K209a-z                   | 1         | 2.08%   |
| HP DeskJet 6940 series                          | 1         | 2.08%   |
| HP DeskJet 5940                                 | 1         | 2.08%   |
| HP DeskJet 3630 series                          | 1         | 2.08%   |
| HP DeskJet 2700 series                          | 1         | 2.08%   |
| HP DeskJet 2620 All-in-One Printer              | 1         | 2.08%   |
| HP Color LaserJet CP1215                        | 1         | 2.08%   |
| Canon TR7500 series                             | 1         | 2.08%   |
| Canon G3020 series                              | 1         | 2.08%   |
| Canon CanoScan LiDE 300                         | 1         | 2.08%   |
| Brother Printer                                 | 1         | 2.08%   |
| Brother MFC-J485DW                              | 1         | 2.08%   |
| Brother MFC-7360N                               | 1         | 2.08%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Canon           | 6         | 42.86%  |
| Seiko Epson     | 3         | 21.43%  |
| Hewlett-Packard | 2         | 14.29%  |
| AGFA-Gevaert NV | 2         | 14.29%  |
| Mustek Systems  | 1         | 7.14%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 210                             | 3         | 21.43%  |
| Seiko Epson Scanner                                 | 1         | 7.14%   |
| Seiko Epson GT-X770 [Perfection V500]               | 1         | 7.14%   |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO] | 1         | 7.14%   |
| Mustek Systems ScanExpress A3 USB                   | 1         | 7.14%   |
| HP ScanJet 5300c/5370c                              | 1         | 7.14%   |
| HP ScanJet 3970c                                    | 1         | 7.14%   |
| Canon CanoScan N670U/N676U/LiDE 20                  | 1         | 7.14%   |
| Canon CanoScan N1240U/LiDE 30                       | 1         | 7.14%   |
| Canon CanoScan LiDE 110                             | 1         | 7.14%   |
| AGFA-Gevaert NV SnapScan e20                        | 1         | 7.14%   |
| AGFA-Gevaert NV SnapScan 1212U (?)                  | 1         | 7.14%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 213       | 24.37%  |
| IMC Networks                           | 83        | 9.5%    |
| Logitech                               | 80        | 9.15%   |
| Microdia                               | 77        | 8.81%   |
| Acer                                   | 68        | 7.78%   |
| Realtek Semiconductor                  | 65        | 7.44%   |
| Sunplus Innovation Technology          | 46        | 5.26%   |
| Quanta                                 | 40        | 4.58%   |
| Cheng Uei Precision Industry (Foxlink) | 29        | 3.32%   |
| Apple                                  | 24        | 2.75%   |
| Lite-On Technology                     | 18        | 2.06%   |
| Luxvisions Innotech Limited            | 17        | 1.95%   |
| Suyin                                  | 15        | 1.72%   |
| Syntek                                 | 14        | 1.6%    |
| Microsoft                              | 9         | 1.03%   |
| Silicon Motion                         | 8         | 0.92%   |
| Lenovo                                 | 6         | 0.69%   |
| Samsung Electronics                    | 5         | 0.57%   |
| Alcor Micro                            | 5         | 0.57%   |
| Ricoh                                  | 4         | 0.46%   |
| Z-Star Microelectronics                | 3         | 0.34%   |
| Sonix Technology                       | 3         | 0.34%   |
| Primax Electronics                     | 3         | 0.34%   |
| Hewlett-Packard                        | 3         | 0.34%   |
| Generalplus Technology                 | 3         | 0.34%   |
| Unknown                                | 2         | 0.23%   |
| Trust                                  | 2         | 0.23%   |
| LG Electronics                         | 2         | 0.23%   |
| Cubeternet                             | 2         | 0.23%   |
| Creative Technology                    | 2         | 0.23%   |
| Arkmicro Technologies                  | 2         | 0.23%   |
| ARC International                      | 2         | 0.23%   |
| Y Media                                | 1         | 0.11%   |
| Unknown (3730304231393931305153)       | 1         | 0.11%   |
| Tobii Technology AB                    | 1         | 0.11%   |
| Sweex                                  | 1         | 0.11%   |
| SunplusIT                              | 1         | 0.11%   |
| SJ-180517-N                            | 1         | 0.11%   |
| Philips (or NXP)                       | 1         | 0.11%   |
| Mimaki Engineering                     | 1         | 0.11%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                           | 53        | 6%      |
| IMC Networks Integrated Camera                      | 34        | 3.85%   |
| Microdia Integrated_Webcam_HD                       | 33        | 3.74%   |
| Logitech Webcam C270                                | 25        | 2.83%   |
| IMC Networks USB2.0 HD UVC WebCam                   | 24        | 2.72%   |
| Realtek Integrated_Webcam_HD                        | 22        | 2.49%   |
| Chicony HD Webcam                                   | 21        | 2.38%   |
| Acer Integrated Camera                              | 19        | 2.15%   |
| Chicony HP HD Camera                                | 16        | 1.81%   |
| Sunplus Integrated_Webcam_HD                        | 15        | 1.7%    |
| Apple Built-in iSight                               | 11        | 1.25%   |
| Realtek Integrated Webcam HD                        | 9         | 1.02%   |
| Chicony Integrated Camera (1280x720@30)             | 9         | 1.02%   |
| Chicony HP HD Webcam                                | 9         | 1.02%   |
| Syntek Integrated Camera                            | 8         | 0.91%   |
| Logitech HD Pro Webcam C920                         | 8         | 0.91%   |
| Chicony USB2.0 Camera                               | 8         | 0.91%   |
| Acer HD Webcam                                      | 8         | 0.91%   |
| Acer BisonCam, NB Pro                               | 8         | 0.91%   |
| Quanta HP HD Camera                                 | 7         | 0.79%   |
| Quanta HD User Facing                               | 7         | 0.79%   |
| Microdia Integrated Webcam                          | 7         | 0.79%   |
| Lite-On Integrated Camera                           | 7         | 0.79%   |
| Realtek USB Camera                                  | 6         | 0.68%   |
| Logitech HD Webcam C615                             | 6         | 0.68%   |
| Logitech C922 Pro Stream Webcam                     | 6         | 0.68%   |
| Chicony USB 2.0 Camera                              | 6         | 0.68%   |
| Chicony TOSHIBA Web Camera - HD                     | 6         | 0.68%   |
| Chicony HP Truevision HD                            | 6         | 0.68%   |
| Chicony HD User Facing                              | 6         | 0.68%   |
| Apple FaceTime HD Camera                            | 6         | 0.68%   |
| Acer EasyCamera                                     | 6         | 0.68%   |
| Samsung Galaxy series, misc. (MTP mode)             | 5         | 0.57%   |
| Realtek USB2.0 HD UVC WebCam                        | 5         | 0.57%   |
| Quanta VGA WebCam                                   | 5         | 0.57%   |
| Microdia USB 2.0 Camera                             | 5         | 0.57%   |
| Microdia Sonix USB 2.0 Camera                       | 5         | 0.57%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera | 5         | 0.57%   |
| Luxvisions Innotech Limited HP HD Camera            | 5         | 0.57%   |
| Logitech Webcam C310                                | 5         | 0.57%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 75        | 40.32%  |
| Synaptics                  | 67        | 36.02%  |
| Shenzhen Goodix Technology | 21        | 11.29%  |
| Upek                       | 9         | 4.84%   |
| Elan Microelectronics      | 6         | 3.23%   |
| AuthenTec                  | 6         | 3.23%   |
| LighTuning Technology      | 2         | 1.08%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Validity Sensors VFS495 Fingerprint Reader                                 | 21        | 11.29%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 21        | 11.29%  |
| Unknown                                                                    | 20        | 10.75%  |
| Shenzhen Goodix  FingerPrint Device                                        | 14        | 7.53%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 10        | 5.38%   |
| Validity Sensors Synaptics WBDI                                            | 10        | 5.38%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 9         | 4.84%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 9         | 4.84%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 6         | 3.23%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint                 | 6         | 3.23%   |
| Shenzhen Goodix Fingerprint Reader                                         | 6         | 3.23%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 5         | 2.69%   |
| Validity Sensors Fingerprint scanner                                       | 4         | 2.15%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 4         | 2.15%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 4         | 2.15%   |
| Validity Sensors VFS491                                                    | 3         | 1.61%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 3         | 1.61%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 3         | 1.61%   |
| Synaptics WBDI Device                                                      | 3         | 1.61%   |
| Synaptics  WBDI                                                            | 3         | 1.61%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 2         | 1.08%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 1.08%   |
| LighTuning EgisTec_ES603                                                   | 2         | 1.08%   |
| Elan fingerprint sensor [FeinTech FPS00200]                                | 2         | 1.08%   |
| Elan ELAN:Fingerprint                                                      | 2         | 1.08%   |
| Elan ELAN:ARM-M4                                                           | 2         | 1.08%   |
| AuthenTec AES2550 Fingerprint Sensor                                       | 2         | 1.08%   |
| AuthenTec AES1600                                                          | 2         | 1.08%   |
| Validity Sensors VFS7552 Touch Fingerprint Sensor                          | 1         | 0.54%   |
| Validity Sensors VFS300 Fingerprint Reader                                 | 1         | 0.54%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 0.54%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 0.54%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 1         | 0.54%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 0.54%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Alcor Micro                | 32        | 40.51%  |
| Broadcom                   | 26        | 32.91%  |
| Gemalto (was Gemplus)      | 6         | 7.59%   |
| Upek                       | 4         | 5.06%   |
| O2 Micro                   | 3         | 3.8%    |
| Hewlett-Packard            | 3         | 3.8%    |
| Yubico.com                 | 1         | 1.27%   |
| Watchdata                  | 1         | 1.27%   |
| Lenovo                     | 1         | 1.27%   |
| Clay Logic                 | 1         | 1.27%   |
| Athena Smartcard Solutions | 1         | 1.27%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 30        | 37.97%  |
| Broadcom 5880                                                                | 11        | 13.92%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 7         | 8.86%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 6.33%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 4         | 5.06%   |
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 5.06%   |
| Broadcom 58200                                                               | 4         | 5.06%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 3         | 3.8%    |
| Hewlett-Packard SC Keyboard - Apollo (Liteon)                                | 3         | 3.8%    |
| Yubico.com Yubikey 4/5 U2F+CCID                                              | 1         | 1.27%   |
| Watchdata USB Key                                                            | 1         | 1.27%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 1.27%   |
| Gemalto (was Gemplus) Prox SU USB PC Link Reader                             | 1         | 1.27%   |
| Clay Logic Nitrokey HSM                                                      | 1         | 1.27%   |
| Athena Smartcard Solutions ASEDrive CCID                                     | 1         | 1.27%   |
| Alcor Micro Watchdata W 1981                                                 | 1         | 1.27%   |
| Alcor Micro EMV Smartcard Reader                                             | 1         | 1.27%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 1083      | 70.19%  |
| 1     | 362       | 23.46%  |
| 2     | 82        | 5.31%   |
| 3     | 14        | 0.91%   |
| 5     | 1         | 0.06%   |
| 4     | 1         | 0.06%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 185       | 33.76%  |
| Graphics card            | 110       | 20.07%  |
| Chipcard                 | 69        | 12.59%  |
| Net/wireless             | 56        | 10.22%  |
| Multimedia controller    | 24        | 4.38%   |
| Sound                    | 22        | 4.01%   |
| Camera                   | 18        | 3.28%   |
| Unassigned class         | 16        | 2.92%   |
| Communication controller | 13        | 2.37%   |
| Card reader              | 9         | 1.64%   |
| Storage                  | 7         | 1.28%   |
| Network                  | 5         | 0.91%   |
| Bluetooth                | 5         | 0.91%   |
| Net/ethernet             | 4         | 0.73%   |
| Firewire controller      | 3         | 0.55%   |
| Modem                    | 1         | 0.18%   |
| Flash memory             | 1         | 0.18%   |

