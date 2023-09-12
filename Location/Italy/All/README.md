Linux in Italy - Tested Hardware & Statistics
---------------------------------------------

A project to collect tested hardware configurations for Linux in Italy.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Italy/Desktop/README.md) and [notebooks](/Location/Italy/Notebook/README.md).

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

Total: 11474

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | 775Dual-VSTA                | Desktop     | [05af667eb0](https://linux-hardware.org/?probe=05af667eb0) | Sep 07, 2023 |
| Apple         | Mac-8ED6AF5B48C039E1 Mac... | Mini pc     | [adc9ee1464](https://linux-hardware.org/?probe=adc9ee1464) | Sep 07, 2023 |
| ASUSTek       | SABERTOOTH P67              | Desktop     | [002bdcd34d](https://linux-hardware.org/?probe=002bdcd34d) | Sep 07, 2023 |
| Clevo         | M1100M                      | Notebook    | [399b796d9f](https://linux-hardware.org/?probe=399b796d9f) | Sep 06, 2023 |
| Dell          | 00P8G1 A00                  | All in one  | [3ce904c03e](https://linux-hardware.org/?probe=3ce904c03e) | Sep 06, 2023 |
| Lenovo        | ThinkPad E14 Gen 2 20TA0... | Notebook    | [0468bc91fc](https://linux-hardware.org/?probe=0468bc91fc) | Sep 06, 2023 |
| ASRock        | Z97M OC Formula             | Desktop     | [1f2c20e8cf](https://linux-hardware.org/?probe=1f2c20e8cf) | Sep 06, 2023 |
| ASUSTek       | X555QG                      | Notebook    | [8cf63afc0f](https://linux-hardware.org/?probe=8cf63afc0f) | Sep 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [7fd153d869](https://linux-hardware.org/?probe=7fd153d869) | Sep 06, 2023 |
| Unknown       | Unknown                     | Desktop     | [6508e8eeb8](https://linux-hardware.org/?probe=6508e8eeb8) | Sep 06, 2023 |
| TUXEDO        | Unknown                     | Notebook    | [1e6c412d84](https://linux-hardware.org/?probe=1e6c412d84) | Sep 06, 2023 |
| HP            | Notebook                    | Notebook    | [ad9bafda30](https://linux-hardware.org/?probe=ad9bafda30) | Sep 06, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [03f6b3b62b](https://linux-hardware.org/?probe=03f6b3b62b) | Sep 06, 2023 |
| Sony          | SVE1712C5E                  | Notebook    | [a5c77b2450](https://linux-hardware.org/?probe=a5c77b2450) | Sep 06, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [0fdeca1313](https://linux-hardware.org/?probe=0fdeca1313) | Sep 06, 2023 |
| Sony          | SVE1712C5E                  | Notebook    | [f864c8e44a](https://linux-hardware.org/?probe=f864c8e44a) | Sep 05, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f7c65dc902](https://linux-hardware.org/?probe=f7c65dc902) | Sep 05, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [c404211007](https://linux-hardware.org/?probe=c404211007) | Sep 05, 2023 |
| Notebook      | N9x0TC                      | Notebook    | [ea9c38200b](https://linux-hardware.org/?probe=ea9c38200b) | Sep 05, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [7619d8e5e8](https://linux-hardware.org/?probe=7619d8e5e8) | Sep 05, 2023 |
| Dell          | 0PTTT9 A01                  | Desktop     | [2c7accd18e](https://linux-hardware.org/?probe=2c7accd18e) | Sep 05, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [4196acbe15](https://linux-hardware.org/?probe=4196acbe15) | Sep 05, 2023 |
| Toshiba       | Satellite C850-1DZ          | Notebook    | [cf916c2f33](https://linux-hardware.org/?probe=cf916c2f33) | Sep 05, 2023 |
| MSI           | Boston                      | Desktop     | [5e1b8aa70b](https://linux-hardware.org/?probe=5e1b8aa70b) | Sep 04, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [a9321ea88e](https://linux-hardware.org/?probe=a9321ea88e) | Sep 04, 2023 |
| MSI           | Boston                      | Desktop     | [5ad763345c](https://linux-hardware.org/?probe=5ad763345c) | Sep 04, 2023 |
| ASUSTek       | K52JB                       | Notebook    | [7944dc4ca2](https://linux-hardware.org/?probe=7944dc4ca2) | Sep 04, 2023 |
| HP            | Laptop 15s-eq2xxx           | Notebook    | [522dd175b1](https://linux-hardware.org/?probe=522dd175b1) | Sep 04, 2023 |
| HUAWEI        | MateBook HZ-W09             | Tablet      | [1e12adec6b](https://linux-hardware.org/?probe=1e12adec6b) | Sep 04, 2023 |
| Intel         | DG41RQ AAE54511-203         | Desktop     | [46aeab1365](https://linux-hardware.org/?probe=46aeab1365) | Sep 04, 2023 |
| Dell          | 0773VG A00                  | Desktop     | [426a2f4142](https://linux-hardware.org/?probe=426a2f4142) | Sep 04, 2023 |
| AZW           | MINI S 10                   | Desktop     | [54967a6b36](https://linux-hardware.org/?probe=54967a6b36) | Sep 04, 2023 |
| Raspberry ... | Raspberry Pi                | Soc         | [34410efd6c](https://linux-hardware.org/?probe=34410efd6c) | Sep 04, 2023 |
| ASRock        | Z790 Taichi Carrara         | Desktop     | [80f9f3915b](https://linux-hardware.org/?probe=80f9f3915b) | Sep 04, 2023 |
| HP            | Notebook                    | Notebook    | [9be8a6b0e7](https://linux-hardware.org/?probe=9be8a6b0e7) | Sep 03, 2023 |
| HP            | Notebook                    | Notebook    | [d038b7106e](https://linux-hardware.org/?probe=d038b7106e) | Sep 03, 2023 |
| HP            | 1825                        | Desktop     | [ea5da3d446](https://linux-hardware.org/?probe=ea5da3d446) | Sep 03, 2023 |
| HP            | 240 G8 Notebook PC          | Notebook    | [092ae0b34d](https://linux-hardware.org/?probe=092ae0b34d) | Sep 03, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [399abaa799](https://linux-hardware.org/?probe=399abaa799) | Sep 02, 2023 |
| Microtech     | ebookPro                    | Notebook    | [ce14e0ffeb](https://linux-hardware.org/?probe=ce14e0ffeb) | Sep 02, 2023 |
| Apple         | Mac-942B5BF58194151B        | All in one  | [e7b6359ed9](https://linux-hardware.org/?probe=e7b6359ed9) | Sep 02, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [5590e2e8d6](https://linux-hardware.org/?probe=5590e2e8d6) | Sep 02, 2023 |
| HP            | Compaq Presario CQ61        | Notebook    | [0cd9e98276](https://linux-hardware.org/?probe=0cd9e98276) | Sep 02, 2023 |
| Chuwi         | LapBook Pro                 | Notebook    | [4dd222efaa](https://linux-hardware.org/?probe=4dd222efaa) | Sep 01, 2023 |
| Lenovo        | YB1-X91L                    | Convertible | [af7d9b26da](https://linux-hardware.org/?probe=af7d9b26da) | Sep 01, 2023 |
| Shenzhen M... | F6BFC                       | Desktop     | [4b8aead223](https://linux-hardware.org/?probe=4b8aead223) | Sep 01, 2023 |
| Intel         | DP67DE AAG10217-300         | Desktop     | [4d0db0b964](https://linux-hardware.org/?probe=4d0db0b964) | Sep 01, 2023 |
| HP            | 89B5 A                      | Desktop     | [3b6a46c308](https://linux-hardware.org/?probe=3b6a46c308) | Sep 01, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [7940f23184](https://linux-hardware.org/?probe=7940f23184) | Sep 01, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [1cb91dff9e](https://linux-hardware.org/?probe=1cb91dff9e) | Sep 01, 2023 |
| HP            | 1632                        | Desktop     | [a36b07aeda](https://linux-hardware.org/?probe=a36b07aeda) | Sep 01, 2023 |
| ASUSTek       | P5Q SE                      | Desktop     | [288078e39e](https://linux-hardware.org/?probe=288078e39e) | Sep 01, 2023 |
| Intel         | X79M-S                      | Desktop     | [a6952c68e4](https://linux-hardware.org/?probe=a6952c68e4) | Sep 01, 2023 |
| Acer          | Extensa 5635Z               | Notebook    | [da70c2acd8](https://linux-hardware.org/?probe=da70c2acd8) | Sep 01, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [b52faa8776](https://linux-hardware.org/?probe=b52faa8776) | Sep 01, 2023 |
| Gigabyte      | M5NM1AI-GB                  | Desktop     | [2b2efe00dd](https://linux-hardware.org/?probe=2b2efe00dd) | Sep 01, 2023 |
| HP            | EliteBook 6930p             | Notebook    | [f40d8bbc73](https://linux-hardware.org/?probe=f40d8bbc73) | Sep 01, 2023 |
| HP            | 1632                        | Desktop     | [13de11f1ff](https://linux-hardware.org/?probe=13de11f1ff) | Sep 01, 2023 |
| ASUSTek       | S301LP                      | Notebook    | [d33b635602](https://linux-hardware.org/?probe=d33b635602) | Aug 31, 2023 |
| Apple         | Mac-F2238AC8                | All in one  | [b5cdfbd338](https://linux-hardware.org/?probe=b5cdfbd338) | Aug 31, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [a45654cfd8](https://linux-hardware.org/?probe=a45654cfd8) | Aug 31, 2023 |
| ASUSTek       | M4A87TD EVO                 | Desktop     | [32a123fc5d](https://linux-hardware.org/?probe=32a123fc5d) | Aug 31, 2023 |
| Notebook      | N9x0TC                      | Notebook    | [f37b35c8dc](https://linux-hardware.org/?probe=f37b35c8dc) | Aug 31, 2023 |
| ASUSTek       | M4A88TD-V EVO/USB3          | Desktop     | [578f5e581e](https://linux-hardware.org/?probe=578f5e581e) | Aug 31, 2023 |
| HP            | EliteBook 840 14 inch G9... | Notebook    | [ec33c11aa1](https://linux-hardware.org/?probe=ec33c11aa1) | Aug 31, 2023 |
| MSI           | A88X-G41 PC Mate            | Desktop     | [13724b9cc2](https://linux-hardware.org/?probe=13724b9cc2) | Aug 31, 2023 |
| MSI           | A320M PRO-E                 | Desktop     | [92c4032614](https://linux-hardware.org/?probe=92c4032614) | Aug 31, 2023 |
| Lenovo        | ThinkPad T470s 20HGS0PA0... | Notebook    | [89caf6d252](https://linux-hardware.org/?probe=89caf6d252) | Aug 31, 2023 |
| ASUSTek       | GL753VD                     | Notebook    | [649fb869a6](https://linux-hardware.org/?probe=649fb869a6) | Aug 31, 2023 |
| ASRock        | Q1900B-ITX                  | Desktop     | [875427cd72](https://linux-hardware.org/?probe=875427cd72) | Aug 31, 2023 |
| Lenovo        | V15 G4 AMN 82YU             | Notebook    | [23242fe856](https://linux-hardware.org/?probe=23242fe856) | Aug 31, 2023 |
| ASUSTek       | P8B75-M                     | Desktop     | [4f8c86072b](https://linux-hardware.org/?probe=4f8c86072b) | Aug 31, 2023 |
| Acer          | Aspire 1700                 | Notebook    | [a76fb24570](https://linux-hardware.org/?probe=a76fb24570) | Aug 31, 2023 |
| Gigabyte      | X570S AERO G                | Desktop     | [f367356391](https://linux-hardware.org/?probe=f367356391) | Aug 30, 2023 |
| Lenovo        | ThinkPad T470 20HES0ET0R    | Notebook    | [65d003a7a0](https://linux-hardware.org/?probe=65d003a7a0) | Aug 30, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [92552fa038](https://linux-hardware.org/?probe=92552fa038) | Aug 30, 2023 |
| HP            | 82B4                        | Desktop     | [28155e6336](https://linux-hardware.org/?probe=28155e6336) | Aug 30, 2023 |
| ASUSTek       | A8N32-SLI-Deluxe            | Desktop     | [26c288c533](https://linux-hardware.org/?probe=26c288c533) | Aug 30, 2023 |
| Dell          | Inspiron 7548               | Notebook    | [6b6a2e7632](https://linux-hardware.org/?probe=6b6a2e7632) | Aug 30, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [4ac0615cbb](https://linux-hardware.org/?probe=4ac0615cbb) | Aug 30, 2023 |
| Acer          | Swift SF314-52              | Notebook    | [4f6b648f42](https://linux-hardware.org/?probe=4f6b648f42) | Aug 30, 2023 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [f040a85f2f](https://linux-hardware.org/?probe=f040a85f2f) | Aug 30, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [73ca89b4fa](https://linux-hardware.org/?probe=73ca89b4fa) | Aug 30, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [98262b8471](https://linux-hardware.org/?probe=98262b8471) | Aug 30, 2023 |
| Toshiba       | Satellite P850              | Notebook    | [a129c031fa](https://linux-hardware.org/?probe=a129c031fa) | Aug 29, 2023 |
| Dell          | Venue 11 Pro 5130           | Notebook    | [38c58406bc](https://linux-hardware.org/?probe=38c58406bc) | Aug 29, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [4bdfa8b9ea](https://linux-hardware.org/?probe=4bdfa8b9ea) | Aug 29, 2023 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [1fd98a124f](https://linux-hardware.org/?probe=1fd98a124f) | Aug 29, 2023 |
| ASRock        | X570 Phantom Gaming 4       | Desktop     | [7674d12aa5](https://linux-hardware.org/?probe=7674d12aa5) | Aug 28, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [f520b2dd72](https://linux-hardware.org/?probe=f520b2dd72) | Aug 28, 2023 |
| Intel         | NUC6CAYB J23203-409         | Mini pc     | [2e7cb45969](https://linux-hardware.org/?probe=2e7cb45969) | Aug 28, 2023 |
| HP            | 21D0                        | Desktop     | [8978dfd3bf](https://linux-hardware.org/?probe=8978dfd3bf) | Aug 28, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [4b78bfab47](https://linux-hardware.org/?probe=4b78bfab47) | Aug 28, 2023 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [d0453c59f5](https://linux-hardware.org/?probe=d0453c59f5) | Aug 28, 2023 |
| ASUSTek       | ROG STRIX Z390-F GAMING     | Desktop     | [17136ed242](https://linux-hardware.org/?probe=17136ed242) | Aug 28, 2023 |
| Gigabyte      | H410M S2H V3                | Desktop     | [c772f3df30](https://linux-hardware.org/?probe=c772f3df30) | Aug 28, 2023 |
| HP            | Spectre x360 Convertible    | Convertible | [b483fa27b9](https://linux-hardware.org/?probe=b483fa27b9) | Aug 28, 2023 |
| ASUSTek       | PRIME B450M-A               | Desktop     | [b4411a9169](https://linux-hardware.org/?probe=b4411a9169) | Aug 27, 2023 |
| ASRock        | Z490M-ITX/ac                | Desktop     | [d3a4f92f62](https://linux-hardware.org/?probe=d3a4f92f62) | Aug 27, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [ded7284a37](https://linux-hardware.org/?probe=ded7284a37) | Aug 27, 2023 |
| Gigabyte      | B650 AORUS ELITE AX         | Desktop     | [b7020427e0](https://linux-hardware.org/?probe=b7020427e0) | Aug 27, 2023 |
| ASUSTek       | PRIME X370-PRO              | Desktop     | [95d23ba555](https://linux-hardware.org/?probe=95d23ba555) | Aug 27, 2023 |
| MSI           | H310M PRO-VD PLUS           | Desktop     | [2a25ad0be2](https://linux-hardware.org/?probe=2a25ad0be2) | Aug 27, 2023 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [6c54b2881a](https://linux-hardware.org/?probe=6c54b2881a) | Aug 27, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [8c616e6421](https://linux-hardware.org/?probe=8c616e6421) | Aug 27, 2023 |
| HP            | 470 G8 Notebook PC          | Notebook    | [b725ab24df](https://linux-hardware.org/?probe=b725ab24df) | Aug 27, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [69a4a078cd](https://linux-hardware.org/?probe=69a4a078cd) | Aug 27, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [ab8f75bb84](https://linux-hardware.org/?probe=ab8f75bb84) | Aug 27, 2023 |
| Lenovo        | Legion 5 15ACH6A 82NW       | Notebook    | [2ee2c8dd6c](https://linux-hardware.org/?probe=2ee2c8dd6c) | Aug 26, 2023 |
| ASUSTek       | T100HAN                     | Notebook    | [73c5eff054](https://linux-hardware.org/?probe=73c5eff054) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [caf8dd1fc3](https://linux-hardware.org/?probe=caf8dd1fc3) | Aug 26, 2023 |
| Lenovo        | ThinkBook 15 G3 ACL 21A4    | Notebook    | [3cce8305bb](https://linux-hardware.org/?probe=3cce8305bb) | Aug 26, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [9cf3912874](https://linux-hardware.org/?probe=9cf3912874) | Aug 26, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [8d36dd0fbb](https://linux-hardware.org/?probe=8d36dd0fbb) | Aug 25, 2023 |
| HP            | Compaq Presario CQ60        | Notebook    | [b407522eb0](https://linux-hardware.org/?probe=b407522eb0) | Aug 25, 2023 |
| HP            | 21F5 0A                     | Desktop     | [812718f3e7](https://linux-hardware.org/?probe=812718f3e7) | Aug 25, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [3eea0be3b4](https://linux-hardware.org/?probe=3eea0be3b4) | Aug 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X350... | Notebook    | [53ba2f91cd](https://linux-hardware.org/?probe=53ba2f91cd) | Aug 24, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [fbe986e246](https://linux-hardware.org/?probe=fbe986e246) | Aug 24, 2023 |
| Pegatron      | EVANS                       | Desktop     | [1b32c5d271](https://linux-hardware.org/?probe=1b32c5d271) | Aug 24, 2023 |
| Lenovo        | 3141 SDK0J40697 WIN 3305... | Desktop     | [088ba21947](https://linux-hardware.org/?probe=088ba21947) | Aug 24, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [5c956051fb](https://linux-hardware.org/?probe=5c956051fb) | Aug 24, 2023 |
| HP            | ENVY 15                     | Notebook    | [6367186102](https://linux-hardware.org/?probe=6367186102) | Aug 24, 2023 |
| Lenovo        | ThinkPad T430 2347DS4       | Notebook    | [cbaaad3882](https://linux-hardware.org/?probe=cbaaad3882) | Aug 24, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [b7ab89701b](https://linux-hardware.org/?probe=b7ab89701b) | Aug 24, 2023 |
| HP            | EliteBook 830 G7 Noteboo... | Notebook    | [e71571b95d](https://linux-hardware.org/?probe=e71571b95d) | Aug 24, 2023 |
| MSI           | MAG Z390M MORTAR            | Desktop     | [91de6baf4d](https://linux-hardware.org/?probe=91de6baf4d) | Aug 24, 2023 |
| Pegatron      | 2AD5                        | Desktop     | [fcb0ac31fe](https://linux-hardware.org/?probe=fcb0ac31fe) | Aug 23, 2023 |
| Apple         | Mac-35C5E08120C7EEAF Mac... | Mini pc     | [0eb0410780](https://linux-hardware.org/?probe=0eb0410780) | Aug 23, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [94195a7c07](https://linux-hardware.org/?probe=94195a7c07) | Aug 23, 2023 |
| HP            | 250 G4                      | Notebook    | [1eb6dc4c12](https://linux-hardware.org/?probe=1eb6dc4c12) | Aug 23, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [a8fb075a9a](https://linux-hardware.org/?probe=a8fb075a9a) | Aug 23, 2023 |
| Acer          | TravelMate 7730G            | Notebook    | [e286f4c997](https://linux-hardware.org/?probe=e286f4c997) | Aug 23, 2023 |
| Acer          | Predator G3610              | Desktop     | [04153b05c7](https://linux-hardware.org/?probe=04153b05c7) | Aug 22, 2023 |
| Dell          | Vostro 5471                 | Notebook    | [342ccb8530](https://linux-hardware.org/?probe=342ccb8530) | Aug 22, 2023 |
| ASUSTek       | PRIME B550M-A               | Desktop     | [df5037fab5](https://linux-hardware.org/?probe=df5037fab5) | Aug 22, 2023 |
| Lenovo        | ThinkPad E15 Gen 2 20TD0... | Notebook    | [f56ee94116](https://linux-hardware.org/?probe=f56ee94116) | Aug 22, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [530e70e1ab](https://linux-hardware.org/?probe=530e70e1ab) | Aug 22, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [6651fbd434](https://linux-hardware.org/?probe=6651fbd434) | Aug 22, 2023 |
| Acer          | Predator PO3-630            | Desktop     | [b7c9c3e0c4](https://linux-hardware.org/?probe=b7c9c3e0c4) | Aug 22, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [285b51551c](https://linux-hardware.org/?probe=285b51551c) | Aug 22, 2023 |
| HP            | Pavilion dv6                | Notebook    | [10badbd20d](https://linux-hardware.org/?probe=10badbd20d) | Aug 22, 2023 |
| Acer          | Aspire A315-23              | Notebook    | [9b3a3cd47b](https://linux-hardware.org/?probe=9b3a3cd47b) | Aug 22, 2023 |
| HP            | 530                         | Notebook    | [2b631777d9](https://linux-hardware.org/?probe=2b631777d9) | Aug 22, 2023 |
| Lenovo        | ThinkPad X380 Yoga 20LJS... | Convertible | [33442fefbf](https://linux-hardware.org/?probe=33442fefbf) | Aug 21, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [165cab2421](https://linux-hardware.org/?probe=165cab2421) | Aug 21, 2023 |
| Lenovo        | ThinkPad T14 Gen 2i 20W0... | Notebook    | [0baece8878](https://linux-hardware.org/?probe=0baece8878) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [6112b46746](https://linux-hardware.org/?probe=6112b46746) | Aug 21, 2023 |
| HP            | 3048h                       | Desktop     | [959637abde](https://linux-hardware.org/?probe=959637abde) | Aug 21, 2023 |
| ASUSTek       | ROG Strix G713IE_G713IE     | Notebook    | [22443858cb](https://linux-hardware.org/?probe=22443858cb) | Aug 21, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [6cee16ebd6](https://linux-hardware.org/?probe=6cee16ebd6) | Aug 21, 2023 |
| Lenovo        | IdeaPad 5 Pro 14ACN6 82L... | Notebook    | [359cd5a655](https://linux-hardware.org/?probe=359cd5a655) | Aug 21, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [b883100fd3](https://linux-hardware.org/?probe=b883100fd3) | Aug 21, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [b6f1a58560](https://linux-hardware.org/?probe=b6f1a58560) | Aug 20, 2023 |
| Lenovo        | ThinkPad X230 2325H50       | Notebook    | [65dd59e7d2](https://linux-hardware.org/?probe=65dd59e7d2) | Aug 20, 2023 |
| ASUSTek       | P8H61-M LE/USB3             | Desktop     | [49289df595](https://linux-hardware.org/?probe=49289df595) | Aug 20, 2023 |
| HP            | 2B52                        | Desktop     | [ed7526d18f](https://linux-hardware.org/?probe=ed7526d18f) | Aug 20, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [04efd4ddec](https://linux-hardware.org/?probe=04efd4ddec) | Aug 20, 2023 |
| Acer          | Nitro AN515-56              | Notebook    | [45264bf6e6](https://linux-hardware.org/?probe=45264bf6e6) | Aug 20, 2023 |
| ASRock        | 970 Extreme4                | Desktop     | [4cec633c85](https://linux-hardware.org/?probe=4cec633c85) | Aug 20, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [05507d2151](https://linux-hardware.org/?probe=05507d2151) | Aug 20, 2023 |
| ASUSTek       | CM6870                      | Desktop     | [b91ffcb2be](https://linux-hardware.org/?probe=b91ffcb2be) | Aug 20, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [8e91f085b4](https://linux-hardware.org/?probe=8e91f085b4) | Aug 20, 2023 |
| ASUSTek       | X540NA                      | Notebook    | [2f3758945b](https://linux-hardware.org/?probe=2f3758945b) | Aug 20, 2023 |
| HP            | Pavilion 15                 | Notebook    | [63e1b9e62c](https://linux-hardware.org/?probe=63e1b9e62c) | Aug 20, 2023 |
| Gigabyte      | B75M-D2V                    | Desktop     | [8c805fa379](https://linux-hardware.org/?probe=8c805fa379) | Aug 20, 2023 |
| Lenovo        | ThinkPad T470 20JNS08H00    | Notebook    | [01a44fbb3b](https://linux-hardware.org/?probe=01a44fbb3b) | Aug 20, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [96fb68dc70](https://linux-hardware.org/?probe=96fb68dc70) | Aug 20, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [e33524b456](https://linux-hardware.org/?probe=e33524b456) | Aug 20, 2023 |
| HP            | ProBook x360 435 G7         | Convertible | [c10d5b11d1](https://linux-hardware.org/?probe=c10d5b11d1) | Aug 19, 2023 |
| HP            | ProBook 440 G8 Notebook ... | Notebook    | [66c64c5da8](https://linux-hardware.org/?probe=66c64c5da8) | Aug 19, 2023 |
| ASUSTek       | ROG STRIX B550-I GAMING     | Desktop     | [825225e1c4](https://linux-hardware.org/?probe=825225e1c4) | Aug 19, 2023 |
| HP            | Stream Laptop 14-ax0XX      | Notebook    | [c19ed9405c](https://linux-hardware.org/?probe=c19ed9405c) | Aug 19, 2023 |
| Toshiba       | Satellite P850              | Notebook    | [8d00e88e1c](https://linux-hardware.org/?probe=8d00e88e1c) | Aug 19, 2023 |
| Dell          | 0P03DX A04                  | Desktop     | [be211c5305](https://linux-hardware.org/?probe=be211c5305) | Aug 18, 2023 |
| HP            | 8245 001                    | All in one  | [f95bcca474](https://linux-hardware.org/?probe=f95bcca474) | Aug 18, 2023 |
| Intel         | NUC11TNBv7 K87766-404       | Mini pc     | [a991f1ebf3](https://linux-hardware.org/?probe=a991f1ebf3) | Aug 18, 2023 |
| HP            | 250 G4 Notebook PC          | Notebook    | [ea6fdc81ab](https://linux-hardware.org/?probe=ea6fdc81ab) | Aug 18, 2023 |
| PC Special... | Ionico 16                   | Notebook    | [da33e8f1c1](https://linux-hardware.org/?probe=da33e8f1c1) | Aug 18, 2023 |
| Lenovo        | IdeaPadFlex 5 14IIL05 81... | Convertible | [f1441ed73a](https://linux-hardware.org/?probe=f1441ed73a) | Aug 18, 2023 |
| Notebook      | NS50MU                      | Notebook    | [37abf5de2d](https://linux-hardware.org/?probe=37abf5de2d) | Aug 17, 2023 |
| Intel         | X79M-S                      | Desktop     | [d79895d82c](https://linux-hardware.org/?probe=d79895d82c) | Aug 17, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [0438f450f4](https://linux-hardware.org/?probe=0438f450f4) | Aug 17, 2023 |
| MSI           | Z87 MPOWER MAX              | Desktop     | [6bda9908df](https://linux-hardware.org/?probe=6bda9908df) | Aug 16, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [d3926b324c](https://linux-hardware.org/?probe=d3926b324c) | Aug 16, 2023 |
| Dell          | Latitude 5414               | Notebook    | [74b8020613](https://linux-hardware.org/?probe=74b8020613) | Aug 16, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [f9ce7b0ef5](https://linux-hardware.org/?probe=f9ce7b0ef5) | Aug 15, 2023 |
| Samsung       | RC530/RC730                 | Notebook    | [86f3ddda0c](https://linux-hardware.org/?probe=86f3ddda0c) | Aug 15, 2023 |
| MSI           | Z170A GAMING M9 ACK         | Desktop     | [1ff9bff198](https://linux-hardware.org/?probe=1ff9bff198) | Aug 15, 2023 |
| Dell          | Inspiron 7590               | Notebook    | [4438df6adb](https://linux-hardware.org/?probe=4438df6adb) | Aug 15, 2023 |
| Pegatron      | Benicia                     | Desktop     | [0ab394fa9e](https://linux-hardware.org/?probe=0ab394fa9e) | Aug 15, 2023 |
| HP            | 15                          | Notebook    | [9b9e2459a8](https://linux-hardware.org/?probe=9b9e2459a8) | Aug 15, 2023 |
| ASUSTek       | TUF Gaming Z790-PLUS WIF... | Desktop     | [780b9a9e3a](https://linux-hardware.org/?probe=780b9a9e3a) | Aug 15, 2023 |
| HP            | ENVY 15                     | Notebook    | [caa5e1d37a](https://linux-hardware.org/?probe=caa5e1d37a) | Aug 14, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [bf753b0310](https://linux-hardware.org/?probe=bf753b0310) | Aug 14, 2023 |
| SLIMBOOK      | PROX-AMD5                   | Notebook    | [6c7c115335](https://linux-hardware.org/?probe=6c7c115335) | Aug 14, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [0be611b499](https://linux-hardware.org/?probe=0be611b499) | Aug 14, 2023 |
| ASUSTek       | X553MA                      | Notebook    | [b2ee5cedbe](https://linux-hardware.org/?probe=b2ee5cedbe) | Aug 14, 2023 |
| Unknown       | V00                         | Mini pc     | [a043004a53](https://linux-hardware.org/?probe=a043004a53) | Aug 14, 2023 |
| ASUSTek       | N53SV                       | Notebook    | [8643d609f2](https://linux-hardware.org/?probe=8643d609f2) | Aug 14, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [a4a49de960](https://linux-hardware.org/?probe=a4a49de960) | Aug 13, 2023 |
| HP            | 8055                        | Desktop     | [a4c4208546](https://linux-hardware.org/?probe=a4c4208546) | Aug 13, 2023 |
| HP            | 3031h                       | Desktop     | [2f9084013a](https://linux-hardware.org/?probe=2f9084013a) | Aug 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [246c60a344](https://linux-hardware.org/?probe=246c60a344) | Aug 13, 2023 |
| Dell          | Inspiron 5584               | Notebook    | [9fb83333a5](https://linux-hardware.org/?probe=9fb83333a5) | Aug 13, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [b232e62577](https://linux-hardware.org/?probe=b232e62577) | Aug 13, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [ca2c61168c](https://linux-hardware.org/?probe=ca2c61168c) | Aug 13, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [64a738d034](https://linux-hardware.org/?probe=64a738d034) | Aug 13, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [bb650e1dd2](https://linux-hardware.org/?probe=bb650e1dd2) | Aug 12, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [fb024a9374](https://linux-hardware.org/?probe=fb024a9374) | Aug 12, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [398f85e94a](https://linux-hardware.org/?probe=398f85e94a) | Aug 12, 2023 |
| ASUSTek       | PRIME A520M-E               | Desktop     | [92f4e14369](https://linux-hardware.org/?probe=92f4e14369) | Aug 11, 2023 |
| MSI           | Boston                      | Desktop     | [62ad275a7d](https://linux-hardware.org/?probe=62ad275a7d) | Aug 11, 2023 |
| MSI           | Boston                      | Desktop     | [a34a89c083](https://linux-hardware.org/?probe=a34a89c083) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [d4b93affe2](https://linux-hardware.org/?probe=d4b93affe2) | Aug 11, 2023 |
| MSI           | MAG B650M MORTAR WIFI       | Desktop     | [7a8e32eb89](https://linux-hardware.org/?probe=7a8e32eb89) | Aug 11, 2023 |
| Gigabyte      | B250-HD3P-CF                | Desktop     | [b347883be2](https://linux-hardware.org/?probe=b347883be2) | Aug 11, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [b21e9793a5](https://linux-hardware.org/?probe=b21e9793a5) | Aug 11, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [8c449cd820](https://linux-hardware.org/?probe=8c449cd820) | Aug 11, 2023 |
| Fujitsu Si... | G31T-M2 V3.02               | Desktop     | [1c32da7aed](https://linux-hardware.org/?probe=1c32da7aed) | Aug 10, 2023 |
| Dell          | XPS 15 9575                 | Convertible | [48f1354795](https://linux-hardware.org/?probe=48f1354795) | Aug 10, 2023 |
| Dell          | Latitude 5300               | Notebook    | [661051063f](https://linux-hardware.org/?probe=661051063f) | Aug 10, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [9627b6d632](https://linux-hardware.org/?probe=9627b6d632) | Aug 10, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [099d1ac0de](https://linux-hardware.org/?probe=099d1ac0de) | Aug 10, 2023 |
| Dell          | 0JP3NX A01                  | Desktop     | [a9c4812d66](https://linux-hardware.org/?probe=a9c4812d66) | Aug 09, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [51fa860c87](https://linux-hardware.org/?probe=51fa860c87) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | Notebook    | [abf7479cb8](https://linux-hardware.org/?probe=abf7479cb8) | Aug 09, 2023 |
| Acer          | Aspire V3-112P              | Notebook    | [e6305472c5](https://linux-hardware.org/?probe=e6305472c5) | Aug 09, 2023 |
| Lenovo        | ThinkPad X240 20AL00C6UK    | Notebook    | [d33c586eab](https://linux-hardware.org/?probe=d33c586eab) | Aug 09, 2023 |
| Unknown       | Unknown                     | Notebook    | [5f186cbc4d](https://linux-hardware.org/?probe=5f186cbc4d) | Aug 09, 2023 |
| ASUSTek       | M5A97 PLUS                  | Desktop     | [0c755e3349](https://linux-hardware.org/?probe=0c755e3349) | Aug 09, 2023 |
| HP            | EliteBook 8470p             | Notebook    | [16acf13ed8](https://linux-hardware.org/?probe=16acf13ed8) | Aug 09, 2023 |
| HP            | 255 G5                      | Notebook    | [d4adfe0ead](https://linux-hardware.org/?probe=d4adfe0ead) | Aug 09, 2023 |
| ASUSTek       | X510URR                     | Notebook    | [f3ee04187f](https://linux-hardware.org/?probe=f3ee04187f) | Aug 09, 2023 |
| Dell          | Inspiron 5584               | Notebook    | [33e964d1d6](https://linux-hardware.org/?probe=33e964d1d6) | Aug 09, 2023 |
| ASUSTek       | ET2011A 0405                | All in one  | [a236196a29](https://linux-hardware.org/?probe=a236196a29) | Aug 08, 2023 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [6abad99081](https://linux-hardware.org/?probe=6abad99081) | Aug 08, 2023 |
| Dell          | XPS L521X                   | Notebook    | [5aec7ef034](https://linux-hardware.org/?probe=5aec7ef034) | Aug 08, 2023 |
| Intel         | X79M-S                      | Desktop     | [8250cad3d6](https://linux-hardware.org/?probe=8250cad3d6) | Aug 08, 2023 |
| Gigabyte      | Z370P D3-CF                 | Desktop     | [ed5ccc8efb](https://linux-hardware.org/?probe=ed5ccc8efb) | Aug 08, 2023 |
| Dell          | Latitude 7440               | Notebook    | [0cfa45fbd8](https://linux-hardware.org/?probe=0cfa45fbd8) | Aug 08, 2023 |
| Dell          | Latitude 7440               | Notebook    | [e476a3e532](https://linux-hardware.org/?probe=e476a3e532) | Aug 08, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [3cd08fb125](https://linux-hardware.org/?probe=3cd08fb125) | Aug 08, 2023 |
| MSI           | Z170A GAMING M9 ACK         | Desktop     | [8839aa58c4](https://linux-hardware.org/?probe=8839aa58c4) | Aug 08, 2023 |
| AZW           | U59                         | Desktop     | [d7b7b7641b](https://linux-hardware.org/?probe=d7b7b7641b) | Aug 07, 2023 |
| Dell          | Inspiron 7391 2n1           | Convertible | [c7a3dd2647](https://linux-hardware.org/?probe=c7a3dd2647) | Aug 07, 2023 |
| Dell          | Inspiron 7391 2n1           | Convertible | [ed6fdbd235](https://linux-hardware.org/?probe=ed6fdbd235) | Aug 07, 2023 |
| Timi          | A7S                         | Notebook    | [34a354df5a](https://linux-hardware.org/?probe=34a354df5a) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [ce02da2586](https://linux-hardware.org/?probe=ce02da2586) | Aug 07, 2023 |
| MSI           | B450 TOMAHAWK MAX           | Desktop     | [31c3da5150](https://linux-hardware.org/?probe=31c3da5150) | Aug 07, 2023 |
| HP            | EliteBook 850 G8 Noteboo... | Notebook    | [aabc0a8aee](https://linux-hardware.org/?probe=aabc0a8aee) | Aug 07, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [4dec7b692a](https://linux-hardware.org/?probe=4dec7b692a) | Aug 07, 2023 |
| ASUSTek       | P5GDC                       | Desktop     | [82fefe395d](https://linux-hardware.org/?probe=82fefe395d) | Aug 06, 2023 |
| ASUSTek       | X405UA                      | Notebook    | [97acf73dea](https://linux-hardware.org/?probe=97acf73dea) | Aug 06, 2023 |
| Dell          | Latitude E5540              | Notebook    | [928c427cbc](https://linux-hardware.org/?probe=928c427cbc) | Aug 06, 2023 |
| MSI           | PRO H610M-B DDR4            | Desktop     | [1b3c788790](https://linux-hardware.org/?probe=1b3c788790) | Aug 06, 2023 |
| Dell          | Precision 7730              | Notebook    | [1ed1a60e50](https://linux-hardware.org/?probe=1ed1a60e50) | Aug 06, 2023 |
| Pegatron      | IPMMB-MQ1                   | Desktop     | [70c450c395](https://linux-hardware.org/?probe=70c450c395) | Aug 06, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [88f7813621](https://linux-hardware.org/?probe=88f7813621) | Aug 06, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [5b67a1f9cf](https://linux-hardware.org/?probe=5b67a1f9cf) | Aug 06, 2023 |
| Dell          | Inspiron 5584               | Notebook    | [7a4e005f77](https://linux-hardware.org/?probe=7a4e005f77) | Aug 06, 2023 |
| Dell          | Latitude E6230              | Notebook    | [cc78868322](https://linux-hardware.org/?probe=cc78868322) | Aug 05, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [6d78d72399](https://linux-hardware.org/?probe=6d78d72399) | Aug 05, 2023 |
| ASUSTek       | Z97-K                       | Desktop     | [5ca4ca286b](https://linux-hardware.org/?probe=5ca4ca286b) | Aug 05, 2023 |
| Mediacom      | SmartBook 130 FullHD - M... | Notebook    | [3aa51361ae](https://linux-hardware.org/?probe=3aa51361ae) | Aug 05, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [1a1d48f2a6](https://linux-hardware.org/?probe=1a1d48f2a6) | Aug 05, 2023 |
| Acer          | Veriton M2632G V:1.0        | Desktop     | [b66051af86](https://linux-hardware.org/?probe=b66051af86) | Aug 04, 2023 |
| Pegatron      | 2A94h                       | Desktop     | [9d5490fb82](https://linux-hardware.org/?probe=9d5490fb82) | Aug 04, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [e21469f818](https://linux-hardware.org/?probe=e21469f818) | Aug 04, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [6fd7ffb05b](https://linux-hardware.org/?probe=6fd7ffb05b) | Aug 04, 2023 |
| ASUSTek       | H81M-K                      | Desktop     | [d946977ec8](https://linux-hardware.org/?probe=d946977ec8) | Aug 04, 2023 |
| SANTECH       | NL5xNU                      | Notebook    | [68d1f62251](https://linux-hardware.org/?probe=68d1f62251) | Aug 04, 2023 |
| HP            | Notebook                    | Notebook    | [9b9a2bd44a](https://linux-hardware.org/?probe=9b9a2bd44a) | Aug 04, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [e0b5eb8809](https://linux-hardware.org/?probe=e0b5eb8809) | Aug 04, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | Notebook    | [6bc628f4e6](https://linux-hardware.org/?probe=6bc628f4e6) | Aug 03, 2023 |
| Dell          | Latitude 5530               | Notebook    | [dd85033508](https://linux-hardware.org/?probe=dd85033508) | Aug 03, 2023 |
| PC Special... | Lafite Pro III 17           | Notebook    | [702cdf4138](https://linux-hardware.org/?probe=702cdf4138) | Aug 03, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [89c0c5c135](https://linux-hardware.org/?probe=89c0c5c135) | Aug 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [020699b05e](https://linux-hardware.org/?probe=020699b05e) | Aug 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [ccc5e0b3ab](https://linux-hardware.org/?probe=ccc5e0b3ab) | Aug 03, 2023 |
| Raspberry ... | Raspberry Pi 3 Model B R... | Soc         | [34a566342b](https://linux-hardware.org/?probe=34a566342b) | Aug 03, 2023 |
| MSI           | PRO Z790-P WIFI             | Desktop     | [8f3eaca764](https://linux-hardware.org/?probe=8f3eaca764) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [986cf08dc9](https://linux-hardware.org/?probe=986cf08dc9) | Aug 03, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS WIF... | Desktop     | [da8d764a97](https://linux-hardware.org/?probe=da8d764a97) | Aug 03, 2023 |
| Timi          | A7S                         | Notebook    | [7de693ff63](https://linux-hardware.org/?probe=7de693ff63) | Aug 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [5a4d94f325](https://linux-hardware.org/?probe=5a4d94f325) | Aug 02, 2023 |
| HP            | ENVY 17                     | Notebook    | [ef244ad969](https://linux-hardware.org/?probe=ef244ad969) | Aug 02, 2023 |
| ASRock        | Z170 Gaming K4              | Desktop     | [2c10cb0378](https://linux-hardware.org/?probe=2c10cb0378) | Aug 02, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [7241233996](https://linux-hardware.org/?probe=7241233996) | Aug 02, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [d0e963d600](https://linux-hardware.org/?probe=d0e963d600) | Aug 02, 2023 |
| Dell          | Precision 3571              | Notebook    | [efa0df50dc](https://linux-hardware.org/?probe=efa0df50dc) | Aug 02, 2023 |
| Lenovo        | ThinkPad T480s 20L8002WM... | Notebook    | [6cfc0b2281](https://linux-hardware.org/?probe=6cfc0b2281) | Aug 01, 2023 |
| ASRock        | B365M-HDV                   | Desktop     | [994853ef26](https://linux-hardware.org/?probe=994853ef26) | Aug 01, 2023 |
| Intel         | X79                         | Desktop     | [051316466a](https://linux-hardware.org/?probe=051316466a) | Aug 01, 2023 |
| Dell          | Latitude E5470              | Notebook    | [3be826cec4](https://linux-hardware.org/?probe=3be826cec4) | Aug 01, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [603bee8812](https://linux-hardware.org/?probe=603bee8812) | Aug 01, 2023 |
| ASUSTek       | Z87-A                       | Desktop     | [64bc1caf41](https://linux-hardware.org/?probe=64bc1caf41) | Aug 01, 2023 |
| Lenovo        | Yoga Pro 7 14ARP8 83AU      | Notebook    | [37be164783](https://linux-hardware.org/?probe=37be164783) | Aug 01, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [19f4cb0c69](https://linux-hardware.org/?probe=19f4cb0c69) | Jul 31, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [18924cfab7](https://linux-hardware.org/?probe=18924cfab7) | Jul 31, 2023 |
| Gigabyte      | B85M-D3H                    | Desktop     | [9ddb5c2ea3](https://linux-hardware.org/?probe=9ddb5c2ea3) | Jul 31, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [d590bcd619](https://linux-hardware.org/?probe=d590bcd619) | Jul 31, 2023 |
| TUXEDO        | InfinityBook Pro Gen7 (M... | Notebook    | [00c9fab30f](https://linux-hardware.org/?probe=00c9fab30f) | Jul 31, 2023 |
| ASUSTek       | ZenBook UX363EA_UX363EA     | Convertible | [be9923f6d2](https://linux-hardware.org/?probe=be9923f6d2) | Jul 30, 2023 |
| ASUSTek       | P552LA                      | Notebook    | [d84e6d9683](https://linux-hardware.org/?probe=d84e6d9683) | Jul 30, 2023 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [2672322c34](https://linux-hardware.org/?probe=2672322c34) | Jul 30, 2023 |
| ASUSTek       | Z170-PRO                    | Desktop     | [ac4682042f](https://linux-hardware.org/?probe=ac4682042f) | Jul 30, 2023 |
| Intel         | NUC11TNBv7 K87766-404       | Mini pc     | [9a5567fb0b](https://linux-hardware.org/?probe=9a5567fb0b) | Jul 30, 2023 |
| SiComputer    | NL40_50CU                   | Notebook    | [95afbe5674](https://linux-hardware.org/?probe=95afbe5674) | Jul 30, 2023 |
| Gigabyte      | GA-MA78GM-S2H               | Desktop     | [37e282ff80](https://linux-hardware.org/?probe=37e282ff80) | Jul 30, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [472c0bf0b0](https://linux-hardware.org/?probe=472c0bf0b0) | Jul 29, 2023 |
| Dell          | XPS 13 9350                 | Notebook    | [2da43364f8](https://linux-hardware.org/?probe=2da43364f8) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [df29d1164c](https://linux-hardware.org/?probe=df29d1164c) | Jul 29, 2023 |
| HP            | Pavilion 15                 | Notebook    | [804d28484b](https://linux-hardware.org/?probe=804d28484b) | Jul 29, 2023 |
| Beelink       | Gemini X                    | Notebook    | [2846d152be](https://linux-hardware.org/?probe=2846d152be) | Jul 29, 2023 |
| HP            | 3048h                       | Desktop     | [cd83e4a73a](https://linux-hardware.org/?probe=cd83e4a73a) | Jul 29, 2023 |
| HP            | 3048h                       | Desktop     | [56918c8bad](https://linux-hardware.org/?probe=56918c8bad) | Jul 29, 2023 |
| ASRock        | A620M-HDV/M.2+              | Desktop     | [ea91ff9db6](https://linux-hardware.org/?probe=ea91ff9db6) | Jul 28, 2023 |
| Dell          | System XPS L702X            | Notebook    | [5e9f83aa10](https://linux-hardware.org/?probe=5e9f83aa10) | Jul 28, 2023 |
| Dell          | Latitude 5290 2-in-1        | Tablet      | [83a69f246c](https://linux-hardware.org/?probe=83a69f246c) | Jul 28, 2023 |
| MSI           | PRO Z690-A                  | Desktop     | [f1a5d69727](https://linux-hardware.org/?probe=f1a5d69727) | Jul 28, 2023 |
| Apple         | Mac-42FD25EABCABB274 iMa... | All in one  | [7e89496549](https://linux-hardware.org/?probe=7e89496549) | Jul 27, 2023 |
| MSI           | MS-B1831                    | Desktop     | [35f0e625f1](https://linux-hardware.org/?probe=35f0e625f1) | Jul 27, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [d32fa8840b](https://linux-hardware.org/?probe=d32fa8840b) | Jul 27, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [613164e308](https://linux-hardware.org/?probe=613164e308) | Jul 27, 2023 |
| Lenovo        | ThinkBook 15 G2 ITL 20VE    | Notebook    | [6546d49225](https://linux-hardware.org/?probe=6546d49225) | Jul 27, 2023 |
| ASUSTek       | LEUCITE3                    | Desktop     | [bb2046286f](https://linux-hardware.org/?probe=bb2046286f) | Jul 26, 2023 |
| ASUSTek       | LEUCITE3                    | Desktop     | [6ced09890f](https://linux-hardware.org/?probe=6ced09890f) | Jul 26, 2023 |
| ASUSTek       | P6X58D PREMIUM              | Desktop     | [0a84eeb8e2](https://linux-hardware.org/?probe=0a84eeb8e2) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [87d69792fb](https://linux-hardware.org/?probe=87d69792fb) | Jul 26, 2023 |
| HP            | Pavilion Laptop 15-cw0xx... | Notebook    | [83097985a2](https://linux-hardware.org/?probe=83097985a2) | Jul 26, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [7de233f9bd](https://linux-hardware.org/?probe=7de233f9bd) | Jul 26, 2023 |
| ASUSTek       | P50IJ                       | Notebook    | [d8aff1255a](https://linux-hardware.org/?probe=d8aff1255a) | Jul 25, 2023 |
| Fujitsu Si... | LIFEBOOK S6410              | Notebook    | [47d5775197](https://linux-hardware.org/?probe=47d5775197) | Jul 25, 2023 |
| HP            | 871C                        | All in one  | [4ebf5aee4d](https://linux-hardware.org/?probe=4ebf5aee4d) | Jul 25, 2023 |
| Acer          | TravelMate B113             | Notebook    | [b6fdce48b3](https://linux-hardware.org/?probe=b6fdce48b3) | Jul 25, 2023 |
| ASUSTek       | ROG Flow X13 GV301RC_GV3... | Convertible | [676bfc8484](https://linux-hardware.org/?probe=676bfc8484) | Jul 25, 2023 |
| Lenovo        | Yoga 520-14IKB 80X8         | Convertible | [22c5b2df49](https://linux-hardware.org/?probe=22c5b2df49) | Jul 25, 2023 |
| Phoenix Co... | PSB514 A11                  | Desktop     | [9791c84b0d](https://linux-hardware.org/?probe=9791c84b0d) | Jul 25, 2023 |
| Lenovo        | ThinkPad E15 20RD0011IX     | Notebook    | [c7a1caa230](https://linux-hardware.org/?probe=c7a1caa230) | Jul 25, 2023 |
| SANTECH       | NHx0DB,DE                   | Notebook    | [80aa11a7e8](https://linux-hardware.org/?probe=80aa11a7e8) | Jul 25, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [f347019f85](https://linux-hardware.org/?probe=f347019f85) | Jul 24, 2023 |
| Intel         | NUC11TNBv7 K87766-404       | Mini pc     | [48ac49a195](https://linux-hardware.org/?probe=48ac49a195) | Jul 24, 2023 |
| Dell          | Latitude 5420               | Notebook    | [c286ff883f](https://linux-hardware.org/?probe=c286ff883f) | Jul 24, 2023 |
| Phoenix Co... | PSB514 A11                  | Desktop     | [8e271c334d](https://linux-hardware.org/?probe=8e271c334d) | Jul 24, 2023 |
| HP            | 250 G3                      | Notebook    | [5580b343bd](https://linux-hardware.org/?probe=5580b343bd) | Jul 24, 2023 |
| SLIMBOOK      | Executive                   | Notebook    | [2def302827](https://linux-hardware.org/?probe=2def302827) | Jul 24, 2023 |
| SLIMBOOK      | Executive                   | Notebook    | [2f0b072622](https://linux-hardware.org/?probe=2f0b072622) | Jul 24, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [84c7ea08c6](https://linux-hardware.org/?probe=84c7ea08c6) | Jul 24, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [86035a17da](https://linux-hardware.org/?probe=86035a17da) | Jul 24, 2023 |
| Intel         | X79                         | Desktop     | [8037a9fc0e](https://linux-hardware.org/?probe=8037a9fc0e) | Jul 24, 2023 |
| Timi          | A7S                         | Notebook    | [d0bcd36416](https://linux-hardware.org/?probe=d0bcd36416) | Jul 24, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [5d16b13584](https://linux-hardware.org/?probe=5d16b13584) | Jul 24, 2023 |
| Gigabyte      | X570 AORUS ELITE            | Desktop     | [ae4343c245](https://linux-hardware.org/?probe=ae4343c245) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [04982390e0](https://linux-hardware.org/?probe=04982390e0) | Jul 23, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [b13bb2310f](https://linux-hardware.org/?probe=b13bb2310f) | Jul 23, 2023 |
| HP            | ProBook 635 Aero G8 Note... | Notebook    | [ff5392a180](https://linux-hardware.org/?probe=ff5392a180) | Jul 23, 2023 |
| Microtech     | ebookPro                    | Notebook    | [4427543f1a](https://linux-hardware.org/?probe=4427543f1a) | Jul 23, 2023 |
| HP            | 250 G1                      | Notebook    | [deab96c404](https://linux-hardware.org/?probe=deab96c404) | Jul 23, 2023 |
| ASUSTek       | CG8480                      | Desktop     | [2b839ca54f](https://linux-hardware.org/?probe=2b839ca54f) | Jul 23, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f2dfaee237](https://linux-hardware.org/?probe=f2dfaee237) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [9ce9a989dd](https://linux-hardware.org/?probe=9ce9a989dd) | Jul 23, 2023 |
| MSI           | MPG X570 GAMING EDGE WIF... | Desktop     | [0e830a2330](https://linux-hardware.org/?probe=0e830a2330) | Jul 23, 2023 |
| ASRock        | B250M Pro4                  | Desktop     | [23d73ededd](https://linux-hardware.org/?probe=23d73ededd) | Jul 23, 2023 |
| MSI           | B450 TOMAHAWK               | Desktop     | [bda4392623](https://linux-hardware.org/?probe=bda4392623) | Jul 22, 2023 |
| HP            | Pavilion x2 Detachable      | Tablet      | [3ed87bb81b](https://linux-hardware.org/?probe=3ed87bb81b) | Jul 22, 2023 |
| Lenovo        | IdeaPad 530S-14ARR 81H1     | Notebook    | [ea078c7fb9](https://linux-hardware.org/?probe=ea078c7fb9) | Jul 22, 2023 |
| Intel         | NUC11TNBv7 K87766-404       | Mini pc     | [723915cfda](https://linux-hardware.org/?probe=723915cfda) | Jul 22, 2023 |
| Apple         | Mac-27ADBB7B4CEE8E61 iMa... | All in one  | [931df813b1](https://linux-hardware.org/?probe=931df813b1) | Jul 22, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | Desktop     | [625e829a7e](https://linux-hardware.org/?probe=625e829a7e) | Jul 22, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [02903e0210](https://linux-hardware.org/?probe=02903e0210) | Jul 22, 2023 |
| MSI           | GL63 8SD                    | Notebook    | [7705e15f5e](https://linux-hardware.org/?probe=7705e15f5e) | Jul 21, 2023 |
| Dell          | XPS 9315                    | Notebook    | [f97422b64b](https://linux-hardware.org/?probe=f97422b64b) | Jul 21, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [38856f8131](https://linux-hardware.org/?probe=38856f8131) | Jul 21, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [977443386e](https://linux-hardware.org/?probe=977443386e) | Jul 21, 2023 |
| ASRock        | 960GC-GS FX                 | Desktop     | [187cbf1010](https://linux-hardware.org/?probe=187cbf1010) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [32ec9929c9](https://linux-hardware.org/?probe=32ec9929c9) | Jul 21, 2023 |
| Lenovo        | IdeaPad S540-14API 81NH     | Notebook    | [a1f316c8c9](https://linux-hardware.org/?probe=a1f316c8c9) | Jul 20, 2023 |
| HP            | ProBook 450 15.6 inch G9... | Notebook    | [e99bf7a4be](https://linux-hardware.org/?probe=e99bf7a4be) | Jul 20, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [89340a2cf7](https://linux-hardware.org/?probe=89340a2cf7) | Jul 19, 2023 |
| Lenovo        | ThinkPad T430 2349IF8       | Notebook    | [56e1ff54a3](https://linux-hardware.org/?probe=56e1ff54a3) | Jul 19, 2023 |
| Acer          | MCP7A                       | Desktop     | [06afe36113](https://linux-hardware.org/?probe=06afe36113) | Jul 18, 2023 |
| Dell          | 0WMJ54 A01                  | Desktop     | [032a11c2a5](https://linux-hardware.org/?probe=032a11c2a5) | Jul 18, 2023 |
| Lenovo        | ThinkPad E15 20RDS1G700     | Notebook    | [6ad3194fd9](https://linux-hardware.org/?probe=6ad3194fd9) | Jul 18, 2023 |
| HP            | 18E7                        | Desktop     | [bddd22fb18](https://linux-hardware.org/?probe=bddd22fb18) | Jul 18, 2023 |
| AMI           | Intel                       | Desktop     | [fb562a8b94](https://linux-hardware.org/?probe=fb562a8b94) | Jul 18, 2023 |
| AMI           | Intel                       | Desktop     | [52cb51f3c6](https://linux-hardware.org/?probe=52cb51f3c6) | Jul 18, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4c8b8b5a8a](https://linux-hardware.org/?probe=4c8b8b5a8a) | Jul 18, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [c75f0b8a63](https://linux-hardware.org/?probe=c75f0b8a63) | Jul 17, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [c7d69d227a](https://linux-hardware.org/?probe=c7d69d227a) | Jul 17, 2023 |
| MSI           | Creator 17 A10SE            | Notebook    | [775c65db16](https://linux-hardware.org/?probe=775c65db16) | Jul 17, 2023 |
| HP            | 3048h                       | Desktop     | [ad7b0d8c8d](https://linux-hardware.org/?probe=ad7b0d8c8d) | Jul 17, 2023 |
| HUAWEI        | KLVC-WXX9                   | Notebook    | [0427f16143](https://linux-hardware.org/?probe=0427f16143) | Jul 17, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [7f25599ad8](https://linux-hardware.org/?probe=7f25599ad8) | Jul 17, 2023 |
| Unknown       | Unknown                     | Notebook    | [2bda9f913a](https://linux-hardware.org/?probe=2bda9f913a) | Jul 17, 2023 |
| HP            | ProBook 455 15.6 inch G9... | Notebook    | [8c94595be0](https://linux-hardware.org/?probe=8c94595be0) | Jul 17, 2023 |
| Olivetti      | Olipad Graphos W811         | Notebook    | [d303fe2826](https://linux-hardware.org/?probe=d303fe2826) | Jul 17, 2023 |
| Toshiba       | TECRA A10                   | Notebook    | [0740ca470e](https://linux-hardware.org/?probe=0740ca470e) | Jul 16, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [65afe9f74b](https://linux-hardware.org/?probe=65afe9f74b) | Jul 16, 2023 |
| Apple         | MacBookPro5,4               | Notebook    | [91f38d0ab5](https://linux-hardware.org/?probe=91f38d0ab5) | Jul 16, 2023 |
| Unknown       | Unknown                     | Soc         | [99bfa94ff7](https://linux-hardware.org/?probe=99bfa94ff7) | Jul 16, 2023 |
| ASUSTek       | K53SJ                       | Notebook    | [eb5e64c657](https://linux-hardware.org/?probe=eb5e64c657) | Jul 16, 2023 |
| Teclast       | F7 Plus                     | Notebook    | [1c317224d2](https://linux-hardware.org/?probe=1c317224d2) | Jul 16, 2023 |
| HP            | Pavilion Laptop 15-eh1xx... | Notebook    | [52870865a4](https://linux-hardware.org/?probe=52870865a4) | Jul 15, 2023 |
| HP            | 250 G8 Notebook PC          | Notebook    | [60809c13e6](https://linux-hardware.org/?probe=60809c13e6) | Jul 15, 2023 |
| Lenovo        | ThinkPad T450 20BUS0S902    | Notebook    | [34329ab49c](https://linux-hardware.org/?probe=34329ab49c) | Jul 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [6087b16809](https://linux-hardware.org/?probe=6087b16809) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [97e2731292](https://linux-hardware.org/?probe=97e2731292) | Jul 15, 2023 |
| Gigabyte      | B550 AORUS ELITE AX V2      | Desktop     | [dd63c138ad](https://linux-hardware.org/?probe=dd63c138ad) | Jul 15, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [bd2e85e3ce](https://linux-hardware.org/?probe=bd2e85e3ce) | Jul 15, 2023 |
| Dell          | Inspiron 16 5625            | Notebook    | [fab0c2fb26](https://linux-hardware.org/?probe=fab0c2fb26) | Jul 15, 2023 |
| Notebook      | PCX0DX                      | Notebook    | [4b7f45adc4](https://linux-hardware.org/?probe=4b7f45adc4) | Jul 15, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [31ae047fcf](https://linux-hardware.org/?probe=31ae047fcf) | Jul 14, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [8df4f1a098](https://linux-hardware.org/?probe=8df4f1a098) | Jul 14, 2023 |
| MSI           | B450M-A PRO MAX             | Desktop     | [9ec51bc7eb](https://linux-hardware.org/?probe=9ec51bc7eb) | Jul 14, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [a945d4d417](https://linux-hardware.org/?probe=a945d4d417) | Jul 14, 2023 |
| ASUSTek       | PN53-G                      | Mini pc     | [1c568b626c](https://linux-hardware.org/?probe=1c568b626c) | Jul 14, 2023 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [0498e27f41](https://linux-hardware.org/?probe=0498e27f41) | Jul 14, 2023 |
| HP            | Laptop 15s-fq2xxx           | Notebook    | [25bd8ff761](https://linux-hardware.org/?probe=25bd8ff761) | Jul 14, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [9868eab45f](https://linux-hardware.org/?probe=9868eab45f) | Jul 14, 2023 |
| Acer          | Aspire TC-380               | Desktop     | [94f5f10ff2](https://linux-hardware.org/?probe=94f5f10ff2) | Jul 14, 2023 |
| HP            | ENVY 15                     | Notebook    | [d69bc2702c](https://linux-hardware.org/?probe=d69bc2702c) | Jul 14, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [78977dd4de](https://linux-hardware.org/?probe=78977dd4de) | Jul 13, 2023 |
| MSI           | H510I PRO WIFI              | Desktop     | [23fef6418b](https://linux-hardware.org/?probe=23fef6418b) | Jul 13, 2023 |
| Dell          | Latitude 5501               | Notebook    | [b10b0e72f0](https://linux-hardware.org/?probe=b10b0e72f0) | Jul 13, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [6c08fefa24](https://linux-hardware.org/?probe=6c08fefa24) | Jul 13, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | Notebook    | [be2db3ecfa](https://linux-hardware.org/?probe=be2db3ecfa) | Jul 13, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [d2dd2ac514](https://linux-hardware.org/?probe=d2dd2ac514) | Jul 13, 2023 |
| Lenovo        | IdeaPad Creator 5 15IMH0... | Notebook    | [56093a48aa](https://linux-hardware.org/?probe=56093a48aa) | Jul 13, 2023 |
| ASUSTek       | K8V-X                       | Desktop     | [7562568efe](https://linux-hardware.org/?probe=7562568efe) | Jul 13, 2023 |
| ASUSTek       | PRIME B450-PLUS             | Desktop     | [cd3de89b97](https://linux-hardware.org/?probe=cd3de89b97) | Jul 12, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [b9b5f89f0c](https://linux-hardware.org/?probe=b9b5f89f0c) | Jul 12, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [10d3da2824](https://linux-hardware.org/?probe=10d3da2824) | Jul 12, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [bc78a01502](https://linux-hardware.org/?probe=bc78a01502) | Jul 12, 2023 |
| ASUSTek       | X550LD                      | Notebook    | [c01febb128](https://linux-hardware.org/?probe=c01febb128) | Jul 12, 2023 |
| HP            | ProLiant DL580 G7           | Server      | [cf5953ed12](https://linux-hardware.org/?probe=cf5953ed12) | Jul 12, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [a4f7584ee4](https://linux-hardware.org/?probe=a4f7584ee4) | Jul 12, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [40281279ab](https://linux-hardware.org/?probe=40281279ab) | Jul 12, 2023 |
| ASUSTek       | PRIME H610M-R D4            | Desktop     | [f7e7c29964](https://linux-hardware.org/?probe=f7e7c29964) | Jul 12, 2023 |
| Acer          | EG31M R01-B1                | Desktop     | [dbc5e1d5db](https://linux-hardware.org/?probe=dbc5e1d5db) | Jul 11, 2023 |
| Acer          | EG31M R01-B1                | Desktop     | [12f533494b](https://linux-hardware.org/?probe=12f533494b) | Jul 11, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [4347661295](https://linux-hardware.org/?probe=4347661295) | Jul 11, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [aac3e629d3](https://linux-hardware.org/?probe=aac3e629d3) | Jul 11, 2023 |
| Apple         | Mac-F22C86C8                | Mini pc     | [e9a45b4e27](https://linux-hardware.org/?probe=e9a45b4e27) | Jul 11, 2023 |
| HP            | 89D8 SMVB                   | Desktop     | [68ee3dff51](https://linux-hardware.org/?probe=68ee3dff51) | Jul 11, 2023 |
| Acer          | Aspire A715-71G             | Notebook    | [cd76343b6e](https://linux-hardware.org/?probe=cd76343b6e) | Jul 11, 2023 |
| MSI           | A320M-A PRO                 | Desktop     | [1a540134de](https://linux-hardware.org/?probe=1a540134de) | Jul 11, 2023 |
| HP            | 255 15.6 inch G9 Noteboo... | Notebook    | [59b334f01a](https://linux-hardware.org/?probe=59b334f01a) | Jul 10, 2023 |
| Panasonic     | CF-C1BD06EFG                | Notebook    | [3b5ab4416a](https://linux-hardware.org/?probe=3b5ab4416a) | Jul 10, 2023 |
| ASRock        | A75 Extreme6                | Desktop     | [1c0eb1b3ea](https://linux-hardware.org/?probe=1c0eb1b3ea) | Jul 10, 2023 |
| HUAWEI        | HLYL-WXX9                   | Notebook    | [480ee8d732](https://linux-hardware.org/?probe=480ee8d732) | Jul 10, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [71329b9909](https://linux-hardware.org/?probe=71329b9909) | Jul 10, 2023 |
| ASUSTek       | P8H61-M LX3 PLUS R2.0       | Desktop     | [b7d5b7b224](https://linux-hardware.org/?probe=b7d5b7b224) | Jul 10, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [29c15fc4d2](https://linux-hardware.org/?probe=29c15fc4d2) | Jul 10, 2023 |
| Lenovo        | V15-IGL 82C3                | Notebook    | [9f920e8a7e](https://linux-hardware.org/?probe=9f920e8a7e) | Jul 10, 2023 |
| Dell          | Latitude E6440              | Notebook    | [6265e6109a](https://linux-hardware.org/?probe=6265e6109a) | Jul 09, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [483109bdd9](https://linux-hardware.org/?probe=483109bdd9) | Jul 09, 2023 |
| Lenovo        | IdeaPad Pro 5 16ARP8 83A... | Notebook    | [acdb08441f](https://linux-hardware.org/?probe=acdb08441f) | Jul 09, 2023 |
| HUAWEI        | HN-WX9X                     | Notebook    | [c01a765f59](https://linux-hardware.org/?probe=c01a765f59) | Jul 09, 2023 |
| MSI           | PRO B650-P WIFI             | Desktop     | [7d98a62bcc](https://linux-hardware.org/?probe=7d98a62bcc) | Jul 09, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [10cf2c3aa5](https://linux-hardware.org/?probe=10cf2c3aa5) | Jul 09, 2023 |
| HP            | Notebook                    | Notebook    | [40226d935a](https://linux-hardware.org/?probe=40226d935a) | Jul 09, 2023 |
| ASUSTek       | ROG STRIX Z790-I GAMING ... | Desktop     | [a1b896bd04](https://linux-hardware.org/?probe=a1b896bd04) | Jul 09, 2023 |
| Notebook      | P7xxTM1                     | Notebook    | [81c163ed4a](https://linux-hardware.org/?probe=81c163ed4a) | Jul 09, 2023 |
| Acer          | Aspire V3-371               | Notebook    | [b4f20e8bc3](https://linux-hardware.org/?probe=b4f20e8bc3) | Jul 08, 2023 |
| HP            | 82A1                        | Desktop     | [2db1718d8f](https://linux-hardware.org/?probe=2db1718d8f) | Jul 08, 2023 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [018447554a](https://linux-hardware.org/?probe=018447554a) | Jul 08, 2023 |
| Shenzhen M... | F7BAA                       | Desktop     | [aa3a981cb3](https://linux-hardware.org/?probe=aa3a981cb3) | Jul 08, 2023 |
| Acer          | TravelMate 5335             | Notebook    | [7422cf6091](https://linux-hardware.org/?probe=7422cf6091) | Jul 08, 2023 |
| Acer          | Chapala                     | Notebook    | [6ea600326f](https://linux-hardware.org/?probe=6ea600326f) | Jul 08, 2023 |
| HP            | 82A1                        | Desktop     | [1bab189e8d](https://linux-hardware.org/?probe=1bab189e8d) | Jul 08, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [62fac1de1c](https://linux-hardware.org/?probe=62fac1de1c) | Jul 08, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [7fde9afaf1](https://linux-hardware.org/?probe=7fde9afaf1) | Jul 08, 2023 |
| Dell          | Inspiron 7720               | Notebook    | [dde4874147](https://linux-hardware.org/?probe=dde4874147) | Jul 08, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [6a739102d0](https://linux-hardware.org/?probe=6a739102d0) | Jul 08, 2023 |
| Acer          | Aspire E1-570G              | Notebook    | [f1d3e3070e](https://linux-hardware.org/?probe=f1d3e3070e) | Jul 07, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [9c6ce21357](https://linux-hardware.org/?probe=9c6ce21357) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [f2203ae88e](https://linux-hardware.org/?probe=f2203ae88e) | Jul 07, 2023 |
| Gigabyte      | H170-HD3-CF                 | Desktop     | [e2adf09ecf](https://linux-hardware.org/?probe=e2adf09ecf) | Jul 07, 2023 |
| Olidata       | Stainer 8050                | Notebook    | [beb3c029a6](https://linux-hardware.org/?probe=beb3c029a6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [ab21b766b6](https://linux-hardware.org/?probe=ab21b766b6) | Jul 07, 2023 |
| Acer          | Aspire A515-47              | Notebook    | [5bba6eb442](https://linux-hardware.org/?probe=5bba6eb442) | Jul 07, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [dbb5eb75b8](https://linux-hardware.org/?probe=dbb5eb75b8) | Jul 07, 2023 |
| HP            | OMEN by Laptop 16-c0xxx     | Notebook    | [e484073491](https://linux-hardware.org/?probe=e484073491) | Jul 07, 2023 |
| Acer          | Aspire E1-570G              | Notebook    | [276cdeb14d](https://linux-hardware.org/?probe=276cdeb14d) | Jul 07, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [e134f78b10](https://linux-hardware.org/?probe=e134f78b10) | Jul 07, 2023 |
| Acer          | Aspire TC-885 V:1.1         | Desktop     | [a2dc9efa21](https://linux-hardware.org/?probe=a2dc9efa21) | Jul 06, 2023 |
| HP            | 82FE 11                     | Desktop     | [fcac934bde](https://linux-hardware.org/?probe=fcac934bde) | Jul 06, 2023 |
| ASRock        | H510M-HDV R2.0              | Desktop     | [2cb98a7961](https://linux-hardware.org/?probe=2cb98a7961) | Jul 06, 2023 |
| Dell          | Precision M6800             | Notebook    | [4b8d02d04a](https://linux-hardware.org/?probe=4b8d02d04a) | Jul 06, 2023 |
| Dell          | Precision M6800             | Notebook    | [239c3ea2b9](https://linux-hardware.org/?probe=239c3ea2b9) | Jul 06, 2023 |
| Gigabyte      | Z390 AORUS PRO-CF           | Desktop     | [79bd04036c](https://linux-hardware.org/?probe=79bd04036c) | Jul 05, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [d6153317bf](https://linux-hardware.org/?probe=d6153317bf) | Jul 05, 2023 |
| Toshiba       | Satellite L750              | Notebook    | [037db5066a](https://linux-hardware.org/?probe=037db5066a) | Jul 05, 2023 |
| Dell          | Latitude 7440               | Notebook    | [2efee1eb6c](https://linux-hardware.org/?probe=2efee1eb6c) | Jul 05, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [44140c28bb](https://linux-hardware.org/?probe=44140c28bb) | Jul 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [a4b93f17c2](https://linux-hardware.org/?probe=a4b93f17c2) | Jul 05, 2023 |
| Sony          | VGN-NS21M_W                 | Notebook    | [36b9bc971f](https://linux-hardware.org/?probe=36b9bc971f) | Jul 05, 2023 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [5699e37170](https://linux-hardware.org/?probe=5699e37170) | Jul 04, 2023 |
| MSI           | Creator 15M A9SD            | Notebook    | [84c85a8969](https://linux-hardware.org/?probe=84c85a8969) | Jul 04, 2023 |
| ADLINK Tec... | ABX-5600 A1                 | Desktop     | [db376a9857](https://linux-hardware.org/?probe=db376a9857) | Jul 04, 2023 |
| HP            | Laptop 15-db0xxx            | Notebook    | [71de589577](https://linux-hardware.org/?probe=71de589577) | Jul 04, 2023 |
| Packard Be... | EasyNote MH36               | Notebook    | [87873c1e0e](https://linux-hardware.org/?probe=87873c1e0e) | Jul 03, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [1a3814f9d9](https://linux-hardware.org/?probe=1a3814f9d9) | Jul 03, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [78bdc20fe8](https://linux-hardware.org/?probe=78bdc20fe8) | Jul 03, 2023 |
| ADLINK Tec... | ABX-5600 A1                 | Desktop     | [46dbe425b5](https://linux-hardware.org/?probe=46dbe425b5) | Jul 03, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [8ad2509708](https://linux-hardware.org/?probe=8ad2509708) | Jul 03, 2023 |
| Toshiba       | Satellite C660              | Notebook    | [3e88dd8cd6](https://linux-hardware.org/?probe=3e88dd8cd6) | Jul 03, 2023 |
| MSI           | Z170A KRAIT GAMING          | Desktop     | [4bede9ff31](https://linux-hardware.org/?probe=4bede9ff31) | Jul 03, 2023 |
| Dell          | XPS 15 7590                 | Notebook    | [de620c05a9](https://linux-hardware.org/?probe=de620c05a9) | Jul 03, 2023 |
| MSI           | Katana GF66 12UC            | Notebook    | [b241427d10](https://linux-hardware.org/?probe=b241427d10) | Jul 03, 2023 |
| Microsoft     | Surface Pro                 | Tablet      | [08fb6b76ce](https://linux-hardware.org/?probe=08fb6b76ce) | Jul 03, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [9ebec4e811](https://linux-hardware.org/?probe=9ebec4e811) | Jul 03, 2023 |
| ASUSTek       | ROG CROSSHAIR VIII DARK ... | Desktop     | [349ff94e9f](https://linux-hardware.org/?probe=349ff94e9f) | Jul 02, 2023 |
| Jumper        | EZbook                      | Notebook    | [735e20e770](https://linux-hardware.org/?probe=735e20e770) | Jul 02, 2023 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [f341618e19](https://linux-hardware.org/?probe=f341618e19) | Jul 02, 2023 |
| ASRock        | B450 Pro4                   | Desktop     | [304cab93f1](https://linux-hardware.org/?probe=304cab93f1) | Jul 02, 2023 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [2ac145f096](https://linux-hardware.org/?probe=2ac145f096) | Jul 02, 2023 |
| HP            | Pavilion dv6                | Notebook    | [0840377177](https://linux-hardware.org/?probe=0840377177) | Jul 02, 2023 |
| Cincoze       | DX-1000.01.001              | Desktop     | [696453bbab](https://linux-hardware.org/?probe=696453bbab) | Jul 02, 2023 |
| Dell          | Latitude E6420              | Notebook    | [aae88e9000](https://linux-hardware.org/?probe=aae88e9000) | Jul 01, 2023 |
| MSI           | Boston                      | Desktop     | [39a458d562](https://linux-hardware.org/?probe=39a458d562) | Jul 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [1b8105097a](https://linux-hardware.org/?probe=1b8105097a) | Jul 01, 2023 |
| Acer          | Aspire A315-55G             | Notebook    | [caddb7bcf7](https://linux-hardware.org/?probe=caddb7bcf7) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [fb7e164f62](https://linux-hardware.org/?probe=fb7e164f62) | Jul 01, 2023 |
| ASUSTek       | PRIME Z590-P                | Desktop     | [2774be84e6](https://linux-hardware.org/?probe=2774be84e6) | Jul 01, 2023 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [cf9a80fbbc](https://linux-hardware.org/?probe=cf9a80fbbc) | Jul 01, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [97ebc05877](https://linux-hardware.org/?probe=97ebc05877) | Jul 01, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [ec3012e08e](https://linux-hardware.org/?probe=ec3012e08e) | Jul 01, 2023 |
| Unknown       | Unknown                     | Desktop     | [53eedfaac9](https://linux-hardware.org/?probe=53eedfaac9) | Jul 01, 2023 |
| Gigabyte      | Z490 VISION D               | Desktop     | [06d9033522](https://linux-hardware.org/?probe=06d9033522) | Jul 01, 2023 |
| Apple         | MacBookPro14,3              | Notebook    | [4a51b35cb8](https://linux-hardware.org/?probe=4a51b35cb8) | Jul 01, 2023 |
| Acer          | Aspire V5-123               | Notebook    | [8507833f22](https://linux-hardware.org/?probe=8507833f22) | Jul 01, 2023 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [d42cdc8551](https://linux-hardware.org/?probe=d42cdc8551) | Jun 30, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [39a8ee4269](https://linux-hardware.org/?probe=39a8ee4269) | Jun 30, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [7ddc95bb2f](https://linux-hardware.org/?probe=7ddc95bb2f) | Jun 30, 2023 |
| Dell          | Vostro 2520                 | Notebook    | [48d04d8282](https://linux-hardware.org/?probe=48d04d8282) | Jun 30, 2023 |
| Dell          | Latitude 5521               | Notebook    | [3a8f3794aa](https://linux-hardware.org/?probe=3a8f3794aa) | Jun 29, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b6c2bcb025](https://linux-hardware.org/?probe=b6c2bcb025) | Jun 29, 2023 |
| Lenovo        | Legion 5 Pro 16ARH7H 82R... | Notebook    | [b52c0ac96a](https://linux-hardware.org/?probe=b52c0ac96a) | Jun 29, 2023 |
| HP            | Stream Laptop 14-cb1XX      | Notebook    | [1db11a4fa9](https://linux-hardware.org/?probe=1db11a4fa9) | Jun 29, 2023 |
| Fujitsu       | D3400-A1 S26361-D3400-A1    | Desktop     | [4ad54ee28d](https://linux-hardware.org/?probe=4ad54ee28d) | Jun 29, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [3c4acbf380](https://linux-hardware.org/?probe=3c4acbf380) | Jun 28, 2023 |
| Lenovo        | IdeaPad 5 15ALC05 82LN      | Notebook    | [7017964456](https://linux-hardware.org/?probe=7017964456) | Jun 28, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [b4fcb0d0c0](https://linux-hardware.org/?probe=b4fcb0d0c0) | Jun 28, 2023 |
| ASUSTek       | F2A85-M PRO                 | Desktop     | [a7617c12c5](https://linux-hardware.org/?probe=a7617c12c5) | Jun 28, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [8ae62960d8](https://linux-hardware.org/?probe=8ae62960d8) | Jun 28, 2023 |
| Dell          | Latitude 7440               | Notebook    | [24f85667ac](https://linux-hardware.org/?probe=24f85667ac) | Jun 28, 2023 |
| Dell          | 0XJ5V0 A03                  | Desktop     | [a1595a590c](https://linux-hardware.org/?probe=a1595a590c) | Jun 28, 2023 |
| ASUSTek       | PRIME Z370M-PLUS II         | Desktop     | [1114cf7328](https://linux-hardware.org/?probe=1114cf7328) | Jun 28, 2023 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [0251f7e1ab](https://linux-hardware.org/?probe=0251f7e1ab) | Jun 27, 2023 |
| Acer          | Aspire A315-21              | Notebook    | [4bf524cd80](https://linux-hardware.org/?probe=4bf524cd80) | Jun 27, 2023 |
| MSI           | B250M PRO-VH                | Desktop     | [cb47380993](https://linux-hardware.org/?probe=cb47380993) | Jun 27, 2023 |
| Lenovo        | ThinkPad SL 2746EDG         | Notebook    | [7f0ae1c657](https://linux-hardware.org/?probe=7f0ae1c657) | Jun 27, 2023 |
| Dell          | XPS 15 9500                 | Notebook    | [8ea6d92813](https://linux-hardware.org/?probe=8ea6d92813) | Jun 27, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ACH6 ... | Notebook    | [24d66c058b](https://linux-hardware.org/?probe=24d66c058b) | Jun 27, 2023 |
| HP            | ENVY 15                     | Notebook    | [0d46d829d2](https://linux-hardware.org/?probe=0d46d829d2) | Jun 27, 2023 |
| HP            | ENVY 15                     | Notebook    | [189cf01c37](https://linux-hardware.org/?probe=189cf01c37) | Jun 27, 2023 |
| Lenovo        | ThinkPad T480 20L6S5LF00    | Notebook    | [5a062be874](https://linux-hardware.org/?probe=5a062be874) | Jun 26, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [f664b455eb](https://linux-hardware.org/?probe=f664b455eb) | Jun 26, 2023 |
| ASUSTek       | T102HA                      | Tablet      | [09acdc7c4a](https://linux-hardware.org/?probe=09acdc7c4a) | Jun 26, 2023 |
| ASUSTek       | B85M-G                      | Desktop     | [5a9f85740e](https://linux-hardware.org/?probe=5a9f85740e) | Jun 26, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fe7974bbc9](https://linux-hardware.org/?probe=fe7974bbc9) | Jun 26, 2023 |
| HP            | Pavilion dv6                | Notebook    | [3051c4ac4e](https://linux-hardware.org/?probe=3051c4ac4e) | Jun 26, 2023 |
| ASUSTek       | H110M-K                     | Desktop     | [8a0a603eef](https://linux-hardware.org/?probe=8a0a603eef) | Jun 26, 2023 |
| Acer          | Aspire V3-772               | Notebook    | [12cc9ac9dc](https://linux-hardware.org/?probe=12cc9ac9dc) | Jun 25, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [82fd23bd36](https://linux-hardware.org/?probe=82fd23bd36) | Jun 25, 2023 |
| Google        | Sasuke                      | Notebook    | [d2b46a08a3](https://linux-hardware.org/?probe=d2b46a08a3) | Jun 25, 2023 |
| Toshiba       | Satellite A300              | Notebook    | [6f1d7a6089](https://linux-hardware.org/?probe=6f1d7a6089) | Jun 25, 2023 |
| Lenovo        | ThinkPad E560 20EV000UIX    | Notebook    | [ac6bd9497a](https://linux-hardware.org/?probe=ac6bd9497a) | Jun 25, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [0b8ee3c470](https://linux-hardware.org/?probe=0b8ee3c470) | Jun 25, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [aa75d0dace](https://linux-hardware.org/?probe=aa75d0dace) | Jun 25, 2023 |
| ASUSTek       | PRIME H310M-A R2.0          | Desktop     | [aab1616d0e](https://linux-hardware.org/?probe=aab1616d0e) | Jun 25, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8112b061f0](https://linux-hardware.org/?probe=8112b061f0) | Jun 24, 2023 |
| HP            | 8437                        | Desktop     | [477b6d5623](https://linux-hardware.org/?probe=477b6d5623) | Jun 24, 2023 |
| ASUSTek       | P5SD2-VM                    | Desktop     | [d91441b98b](https://linux-hardware.org/?probe=d91441b98b) | Jun 24, 2023 |
| Microtech     | CoreBook Lite               | Notebook    | [1840bef280](https://linux-hardware.org/?probe=1840bef280) | Jun 24, 2023 |
| Packard Be... | EasyNote TJ65               | Notebook    | [cdc135487b](https://linux-hardware.org/?probe=cdc135487b) | Jun 24, 2023 |
| MSI           | MS-7360                     | Desktop     | [9a0d46b069](https://linux-hardware.org/?probe=9a0d46b069) | Jun 23, 2023 |
| HP            | Presario CQ56               | Notebook    | [5a8991a97b](https://linux-hardware.org/?probe=5a8991a97b) | Jun 23, 2023 |
| HP            | Laptop 15-da0xxx            | Notebook    | [f8d0ce645a](https://linux-hardware.org/?probe=f8d0ce645a) | Jun 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [2fb45a65c8](https://linux-hardware.org/?probe=2fb45a65c8) | Jun 23, 2023 |
| MSI           | B550M PRO-VDH WIFI          | Desktop     | [ae8e0ef85b](https://linux-hardware.org/?probe=ae8e0ef85b) | Jun 23, 2023 |
| HP            | ENVY 15                     | Notebook    | [3918cca1e5](https://linux-hardware.org/?probe=3918cca1e5) | Jun 23, 2023 |
| HP            | Pavilion g6                 | Notebook    | [fa58c1a1fd](https://linux-hardware.org/?probe=fa58c1a1fd) | Jun 22, 2023 |
| Acer          | Aspire 7720G                | Notebook    | [a8e44a5ab1](https://linux-hardware.org/?probe=a8e44a5ab1) | Jun 22, 2023 |
| HP            | Pavilion g6                 | Notebook    | [a58868d782](https://linux-hardware.org/?probe=a58868d782) | Jun 22, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [83d89a8751](https://linux-hardware.org/?probe=83d89a8751) | Jun 22, 2023 |
| HP            | Pavilion Laptop 14-ce2xx... | Notebook    | [419687b31f](https://linux-hardware.org/?probe=419687b31f) | Jun 22, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [6e4fe4f0c8](https://linux-hardware.org/?probe=6e4fe4f0c8) | Jun 22, 2023 |
| IP3 Techno... | ACB19                       | Mini pc     | [db5c45e4f7](https://linux-hardware.org/?probe=db5c45e4f7) | Jun 22, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [223967ea1d](https://linux-hardware.org/?probe=223967ea1d) | Jun 22, 2023 |
| Lenovo        | IdeaPad 3 15IGL05 81WQ      | Notebook    | [44050251e9](https://linux-hardware.org/?probe=44050251e9) | Jun 22, 2023 |
| Sony          | VGN-NS21M_W                 | Notebook    | [6813d6589e](https://linux-hardware.org/?probe=6813d6589e) | Jun 21, 2023 |
| HP            | EliteBook 820 G2            | Notebook    | [d4f506e331](https://linux-hardware.org/?probe=d4f506e331) | Jun 21, 2023 |
| Microsoft     | Surface Go                  | Tablet      | [197d2f4c7c](https://linux-hardware.org/?probe=197d2f4c7c) | Jun 21, 2023 |
| ASUSTek       | K55VD                       | Notebook    | [49f6cc6986](https://linux-hardware.org/?probe=49f6cc6986) | Jun 20, 2023 |
| Intel         | X79                         | Desktop     | [8c50d3b5e8](https://linux-hardware.org/?probe=8c50d3b5e8) | Jun 20, 2023 |
| Lenovo        | ThinkPad SL 2746EDG         | Notebook    | [42ba3d75e5](https://linux-hardware.org/?probe=42ba3d75e5) | Jun 20, 2023 |
| AMI           | Intel                       | Desktop     | [94c1b63cc6](https://linux-hardware.org/?probe=94c1b63cc6) | Jun 20, 2023 |
| HP            | OMEN by Laptop 15-dh0xxx    | Notebook    | [6e2f7d8295](https://linux-hardware.org/?probe=6e2f7d8295) | Jun 20, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [35de204113](https://linux-hardware.org/?probe=35de204113) | Jun 19, 2023 |
| Samsung       | RC420/RC520/RC720           | Notebook    | [406b650f19](https://linux-hardware.org/?probe=406b650f19) | Jun 19, 2023 |
| Apple         | Mac-81E3E92DD6088272 iMa... | All in one  | [0f15219a46](https://linux-hardware.org/?probe=0f15219a46) | Jun 19, 2023 |
| Acer          | Aspire TC-780               | Desktop     | [7412881615](https://linux-hardware.org/?probe=7412881615) | Jun 18, 2023 |
| MSI           | PS63 Modern 8RC             | Notebook    | [f540e88555](https://linux-hardware.org/?probe=f540e88555) | Jun 18, 2023 |
| Dell          | Latitude 5520               | Notebook    | [09da4ee3c4](https://linux-hardware.org/?probe=09da4ee3c4) | Jun 18, 2023 |
| Dell          | Latitude 5520               | Notebook    | [5e70c1929c](https://linux-hardware.org/?probe=5e70c1929c) | Jun 18, 2023 |
| Acer          | Aspire 5600                 | Notebook    | [af924230a1](https://linux-hardware.org/?probe=af924230a1) | Jun 18, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [7d246caf6f](https://linux-hardware.org/?probe=7d246caf6f) | Jun 18, 2023 |
| Lenovo        | IdeaPad 3 15ALC6 82KU       | Notebook    | [46692b99cb](https://linux-hardware.org/?probe=46692b99cb) | Jun 18, 2023 |
| Acer          | Aspire 5738                 | Notebook    | [8247e349fc](https://linux-hardware.org/?probe=8247e349fc) | Jun 17, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [8b346f7874](https://linux-hardware.org/?probe=8b346f7874) | Jun 17, 2023 |
| HUAWEI        | MACH-WX9                    | Notebook    | [4a86028eb3](https://linux-hardware.org/?probe=4a86028eb3) | Jun 17, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [fe3b7abf1d](https://linux-hardware.org/?probe=fe3b7abf1d) | Jun 17, 2023 |
| MSI           | Boston                      | Desktop     | [8bc41737a5](https://linux-hardware.org/?probe=8bc41737a5) | Jun 17, 2023 |
| ASUSTek       | T101HA                      | Tablet      | [834705c660](https://linux-hardware.org/?probe=834705c660) | Jun 17, 2023 |
| HP            | ENVY 15                     | Notebook    | [10a4cb8865](https://linux-hardware.org/?probe=10a4cb8865) | Jun 17, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [23b64edd39](https://linux-hardware.org/?probe=23b64edd39) | Jun 17, 2023 |
| ASUSTek       | P5B-Deluxe                  | Desktop     | [4dae4ff7c6](https://linux-hardware.org/?probe=4dae4ff7c6) | Jun 16, 2023 |
| Dell          | Vostro 3700                 | Notebook    | [dae8f5a0b4](https://linux-hardware.org/?probe=dae8f5a0b4) | Jun 15, 2023 |
| HP            | Laptop 15s-fq0xxx           | Notebook    | [bbc15bef9c](https://linux-hardware.org/?probe=bbc15bef9c) | Jun 15, 2023 |
| Supermicro    | C7X99-OCE                   | Server      | [3d606bb171](https://linux-hardware.org/?probe=3d606bb171) | Jun 15, 2023 |
| Apple         | Mac-031B6874CF7F642A iMa... | All in one  | [f3d2cd0976](https://linux-hardware.org/?probe=f3d2cd0976) | Jun 15, 2023 |
| Acer          | Aspire 1810T                | Notebook    | [1b1d11f461](https://linux-hardware.org/?probe=1b1d11f461) | Jun 14, 2023 |
| Samsung       | N130                        | Notebook    | [3efb763643](https://linux-hardware.org/?probe=3efb763643) | Jun 14, 2023 |
| MSI           | GL73 8RE                    | Notebook    | [e37b06f2b0](https://linux-hardware.org/?probe=e37b06f2b0) | Jun 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [e6ac28ac73](https://linux-hardware.org/?probe=e6ac28ac73) | Jun 14, 2023 |
| Unknown       | Unknown                     | Desktop     | [ca27fe4c19](https://linux-hardware.org/?probe=ca27fe4c19) | Jun 14, 2023 |
| ASUSTek       | P553UA                      | Notebook    | [2543eb4ce8](https://linux-hardware.org/?probe=2543eb4ce8) | Jun 14, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [511317bdbc](https://linux-hardware.org/?probe=511317bdbc) | Jun 14, 2023 |
| Dell          | XPS 15 9560                 | Notebook    | [f3b25c0959](https://linux-hardware.org/?probe=f3b25c0959) | Jun 14, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [11bb40ef32](https://linux-hardware.org/?probe=11bb40ef32) | Jun 13, 2023 |
| HP            | 18E7                        | Desktop     | [1be1b42bb4](https://linux-hardware.org/?probe=1be1b42bb4) | Jun 13, 2023 |
| HP            | 18E7                        | Desktop     | [cbf4019da2](https://linux-hardware.org/?probe=cbf4019da2) | Jun 13, 2023 |
| HP            | Pavilion dv7                | Notebook    | [3c113d457b](https://linux-hardware.org/?probe=3c113d457b) | Jun 13, 2023 |
| Dell          | Latitude E5540              | Notebook    | [029d51e57f](https://linux-hardware.org/?probe=029d51e57f) | Jun 13, 2023 |
| HP            | 250 15.6 inch G9 Noteboo... | Notebook    | [d910ebe7bb](https://linux-hardware.org/?probe=d910ebe7bb) | Jun 13, 2023 |
| Dell          | Latitude E7250              | Notebook    | [cc9fc2bace](https://linux-hardware.org/?probe=cc9fc2bace) | Jun 13, 2023 |
| ASUSTek       | H110M-A                     | Desktop     | [d9cd48b67d](https://linux-hardware.org/?probe=d9cd48b67d) | Jun 12, 2023 |
| Lenovo        | 103D SDK0Q40112 WIN 3305... | Desktop     | [5c2eef3678](https://linux-hardware.org/?probe=5c2eef3678) | Jun 12, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [8e5a09ba99](https://linux-hardware.org/?probe=8e5a09ba99) | Jun 12, 2023 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [373e36422d](https://linux-hardware.org/?probe=373e36422d) | Jun 12, 2023 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [017c7fd564](https://linux-hardware.org/?probe=017c7fd564) | Jun 11, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [b843a66531](https://linux-hardware.org/?probe=b843a66531) | Jun 11, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [e31b33ae5e](https://linux-hardware.org/?probe=e31b33ae5e) | Jun 11, 2023 |
| HP            | ZBook 15 G6                 | Notebook    | [180abd0b90](https://linux-hardware.org/?probe=180abd0b90) | Jun 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [d276b58f38](https://linux-hardware.org/?probe=d276b58f38) | Jun 10, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [98a4edb43d](https://linux-hardware.org/?probe=98a4edb43d) | Jun 10, 2023 |
| Intel         | NUC11ATBC2 M53055-202       | Mini pc     | [81aee70d12](https://linux-hardware.org/?probe=81aee70d12) | Jun 10, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [bdca36306b](https://linux-hardware.org/?probe=bdca36306b) | Jun 10, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [c4063bcf07](https://linux-hardware.org/?probe=c4063bcf07) | Jun 09, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [9016ad81ae](https://linux-hardware.org/?probe=9016ad81ae) | Jun 09, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [f1c10c92b3](https://linux-hardware.org/?probe=f1c10c92b3) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [5648ca2620](https://linux-hardware.org/?probe=5648ca2620) | Jun 09, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [30dbebd931](https://linux-hardware.org/?probe=30dbebd931) | Jun 09, 2023 |
| Onda TLC      | ONDA Oliver                 | Notebook    | [80a06d821b](https://linux-hardware.org/?probe=80a06d821b) | Jun 09, 2023 |
| Raspberry ... | Raspberry Pi 2 Model B R... | Soc         | [5ad9f9e0bf](https://linux-hardware.org/?probe=5ad9f9e0bf) | Jun 09, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [797dea9c96](https://linux-hardware.org/?probe=797dea9c96) | Jun 09, 2023 |
| MSI           | H81I                        | Desktop     | [c7c19346a2](https://linux-hardware.org/?probe=c7c19346a2) | Jun 09, 2023 |
| HP            | 09E0h                       | Desktop     | [b6bb01441c](https://linux-hardware.org/?probe=b6bb01441c) | Jun 09, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [b88712538e](https://linux-hardware.org/?probe=b88712538e) | Jun 09, 2023 |
| HP            | 2B35                        | Desktop     | [5921b94b60](https://linux-hardware.org/?probe=5921b94b60) | Jun 09, 2023 |
| HP            | EliteBook 8440p             | Notebook    | [51bfdec531](https://linux-hardware.org/?probe=51bfdec531) | Jun 09, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [9bcc99d434](https://linux-hardware.org/?probe=9bcc99d434) | Jun 08, 2023 |
| Acer          | Aspire A315-51              | Notebook    | [3013e9caf2](https://linux-hardware.org/?probe=3013e9caf2) | Jun 08, 2023 |
| HP            | G42                         | Notebook    | [fe8d2be276](https://linux-hardware.org/?probe=fe8d2be276) | Jun 08, 2023 |
| HP            | G42                         | Notebook    | [4f33462d46](https://linux-hardware.org/?probe=4f33462d46) | Jun 08, 2023 |
| Lenovo        | ThinkPad X270 W10DG 20K5... | Notebook    | [8a01610ae4](https://linux-hardware.org/?probe=8a01610ae4) | Jun 08, 2023 |
| MSI           | X470 GAMING PLUS            | Desktop     | [eea4cea0e0](https://linux-hardware.org/?probe=eea4cea0e0) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [d6a8e02362](https://linux-hardware.org/?probe=d6a8e02362) | Jun 08, 2023 |
| HP            | 87A4 10100                  | All in one  | [3c67e34a5e](https://linux-hardware.org/?probe=3c67e34a5e) | Jun 08, 2023 |
| ASUSTek       | X580VN                      | Notebook    | [8c1cf3f164](https://linux-hardware.org/?probe=8c1cf3f164) | Jun 08, 2023 |
| HUAWEI        | HKD-WXX                     | Notebook    | [fdb80f6e89](https://linux-hardware.org/?probe=fdb80f6e89) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [35c7fcb130](https://linux-hardware.org/?probe=35c7fcb130) | Jun 08, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [f4e1a7a712](https://linux-hardware.org/?probe=f4e1a7a712) | Jun 08, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | Desktop     | [d5d7ffe9df](https://linux-hardware.org/?probe=d5d7ffe9df) | Jun 08, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [82d0019a0b](https://linux-hardware.org/?probe=82d0019a0b) | Jun 08, 2023 |
| Acer          | AO722                       | Notebook    | [a57b6cf2ff](https://linux-hardware.org/?probe=a57b6cf2ff) | Jun 08, 2023 |
| HP            | Pavilion dv7                | Notebook    | [75a37cd4c8](https://linux-hardware.org/?probe=75a37cd4c8) | Jun 07, 2023 |
| HP            | 1905                        | Desktop     | [0617f4e698](https://linux-hardware.org/?probe=0617f4e698) | Jun 07, 2023 |
| Apple         | Mac-77F17D7DA9285301 iMa... | All in one  | [2ad409f60a](https://linux-hardware.org/?probe=2ad409f60a) | Jun 07, 2023 |
| Onda TLC      | ONDA Oliver                 | Notebook    | [bbfcf4a3be](https://linux-hardware.org/?probe=bbfcf4a3be) | Jun 07, 2023 |
| Dell          | Latitude 5300               | Notebook    | [1eea10cfa3](https://linux-hardware.org/?probe=1eea10cfa3) | Jun 07, 2023 |
| HP            | Pavilion Notebook           | Notebook    | [5254a5fe09](https://linux-hardware.org/?probe=5254a5fe09) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [f4e4a4b982](https://linux-hardware.org/?probe=f4e4a4b982) | Jun 07, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [7948f267c2](https://linux-hardware.org/?probe=7948f267c2) | Jun 07, 2023 |
| Lenovo        | 317C SDK0J40700 WIN 3258... | Desktop     | [23b41d16db](https://linux-hardware.org/?probe=23b41d16db) | Jun 06, 2023 |
| Acer          | AO722                       | Notebook    | [8840b1284b](https://linux-hardware.org/?probe=8840b1284b) | Jun 06, 2023 |
| Acer          | Aspire E1-571               | Notebook    | [1139c69312](https://linux-hardware.org/?probe=1139c69312) | Jun 06, 2023 |
| Chuwi         | RZBOX                       | Desktop     | [f395c0f429](https://linux-hardware.org/?probe=f395c0f429) | Jun 06, 2023 |
| MSI           | GF63 Thin 9RCX              | Notebook    | [85ec51dbf3](https://linux-hardware.org/?probe=85ec51dbf3) | Jun 05, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [d288737b23](https://linux-hardware.org/?probe=d288737b23) | Jun 05, 2023 |
| Lenovo        | ThinkPad T15 Gen 1 20S60... | Notebook    | [c20dd8572a](https://linux-hardware.org/?probe=c20dd8572a) | Jun 05, 2023 |
| MSI           | B360M PRO-VH                | Desktop     | [8d150fb2b0](https://linux-hardware.org/?probe=8d150fb2b0) | Jun 05, 2023 |
| HUAWEI        | KPR-WX9                     | Notebook    | [3eb711e453](https://linux-hardware.org/?probe=3eb711e453) | Jun 05, 2023 |
| Dell          | XPS 13 9305                 | Notebook    | [450d20f29d](https://linux-hardware.org/?probe=450d20f29d) | Jun 05, 2023 |
| BESSTAR Te... | GB7                         | Mini pc     | [e3738c1f5a](https://linux-hardware.org/?probe=e3738c1f5a) | Jun 05, 2023 |
| Fujitsu       | D3061-A1 S26361-D3061-A1    | Desktop     | [cc575f0073](https://linux-hardware.org/?probe=cc575f0073) | Jun 05, 2023 |
| Unknown       | Unknown                     | Desktop     | [292269611c](https://linux-hardware.org/?probe=292269611c) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [b4f165f28d](https://linux-hardware.org/?probe=b4f165f28d) | Jun 05, 2023 |
| Acer          | Aspire F5-573G              | Notebook    | [e0ce9df73c](https://linux-hardware.org/?probe=e0ce9df73c) | Jun 05, 2023 |
| MSI           | Boston                      | Desktop     | [9f5efc29ad](https://linux-hardware.org/?probe=9f5efc29ad) | Jun 04, 2023 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [3af6e03b1c](https://linux-hardware.org/?probe=3af6e03b1c) | Jun 04, 2023 |
| MSI           | GL75 Leopard 10SER          | Notebook    | [24111ade43](https://linux-hardware.org/?probe=24111ade43) | Jun 04, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [4b162cac99](https://linux-hardware.org/?probe=4b162cac99) | Jun 04, 2023 |
| Acer          | Aspire E5-573G              | Notebook    | [3ef3c9ec82](https://linux-hardware.org/?probe=3ef3c9ec82) | Jun 04, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [6a50598ca6](https://linux-hardware.org/?probe=6a50598ca6) | Jun 04, 2023 |
| HP            | 255 G7 Notebook PC          | Notebook    | [8b14da5cf8](https://linux-hardware.org/?probe=8b14da5cf8) | Jun 04, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [70e5950511](https://linux-hardware.org/?probe=70e5950511) | Jun 04, 2023 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [f472cba5a6](https://linux-hardware.org/?probe=f472cba5a6) | Jun 04, 2023 |
| HP            | ZBook 15 G2                 | Notebook    | [19ed8e22e6](https://linux-hardware.org/?probe=19ed8e22e6) | Jun 03, 2023 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [ac6745cffb](https://linux-hardware.org/?probe=ac6745cffb) | Jun 03, 2023 |
| Dell          | Latitude E5430 non-vPro     | Notebook    | [ba2dfac7ae](https://linux-hardware.org/?probe=ba2dfac7ae) | Jun 03, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [fc0097b52f](https://linux-hardware.org/?probe=fc0097b52f) | Jun 03, 2023 |
| MSI           | MAG B550M MORTAR            | Desktop     | [3d911ac9c9](https://linux-hardware.org/?probe=3d911ac9c9) | Jun 03, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [fe03659a55](https://linux-hardware.org/?probe=fe03659a55) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Gaming F17 FX70... | Notebook    | [959b76650d](https://linux-hardware.org/?probe=959b76650d) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [35fff15a30](https://linux-hardware.org/?probe=35fff15a30) | Jun 02, 2023 |
| ASRock        | B365 Pro4                   | Desktop     | [54fcb811b8](https://linux-hardware.org/?probe=54fcb811b8) | Jun 02, 2023 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [174ffa62e4](https://linux-hardware.org/?probe=174ffa62e4) | Jun 02, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [a8f8239e40](https://linux-hardware.org/?probe=a8f8239e40) | Jun 02, 2023 |
| ASUSTek       | ASUS TUF Dash F15 FX516P... | Notebook    | [49ca1fd34f](https://linux-hardware.org/?probe=49ca1fd34f) | Jun 02, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [3bc50c5ccb](https://linux-hardware.org/?probe=3bc50c5ccb) | Jun 02, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [0a536c1198](https://linux-hardware.org/?probe=0a536c1198) | Jun 01, 2023 |
| MSI           | X470 GAMING PLUS MAX        | Desktop     | [5430a83fca](https://linux-hardware.org/?probe=5430a83fca) | Jun 01, 2023 |
| Samsung       | 300E4C/300E5C/300E7C        | Notebook    | [fcc2d0ed39](https://linux-hardware.org/?probe=fcc2d0ed39) | Jun 01, 2023 |
| HP            | 18E7                        | Desktop     | [a3f557389e](https://linux-hardware.org/?probe=a3f557389e) | Jun 01, 2023 |
| ASRock        | H310M-HDV                   | Desktop     | [3dc5138ecd](https://linux-hardware.org/?probe=3dc5138ecd) | Jun 01, 2023 |
| Fujitsu Si... | D2740-A2 S26361-D2740-A2    | Desktop     | [165491db1f](https://linux-hardware.org/?probe=165491db1f) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | Notebook    | [9324563727](https://linux-hardware.org/?probe=9324563727) | Jun 01, 2023 |
| Gigabyte      | B550M DS3H                  | Desktop     | [df7287f2c8](https://linux-hardware.org/?probe=df7287f2c8) | Jun 01, 2023 |
| MSI           | Prestige 15 A12UC           | Notebook    | [778e78d2a5](https://linux-hardware.org/?probe=778e78d2a5) | Jun 01, 2023 |
| ASRock        | X370 Pro4                   | Desktop     | [aaeac4c226](https://linux-hardware.org/?probe=aaeac4c226) | Jun 01, 2023 |
| MSI           | H110M PRO-VH PLUS           | Desktop     | [cfabc605f7](https://linux-hardware.org/?probe=cfabc605f7) | Jun 01, 2023 |
| Acer          | WG43M                       | Desktop     | [cdd78e1cac](https://linux-hardware.org/?probe=cdd78e1cac) | May 31, 2023 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [0b0c375bb8](https://linux-hardware.org/?probe=0b0c375bb8) | May 31, 2023 |
| Olidata       | Tehom cw4900                | Notebook    | [f5b147962f](https://linux-hardware.org/?probe=f5b147962f) | May 31, 2023 |
| ASRock        | H81M-HDS R2.0               | Desktop     | [810f6b35ea](https://linux-hardware.org/?probe=810f6b35ea) | May 31, 2023 |
| HONOR         | BBR-WAX9                    | Notebook    | [8630cfad52](https://linux-hardware.org/?probe=8630cfad52) | May 31, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [bfcb7f950d](https://linux-hardware.org/?probe=bfcb7f950d) | May 31, 2023 |
| ASUSTek       | P9X79                       | Desktop     | [c677ff5b2d](https://linux-hardware.org/?probe=c677ff5b2d) | May 31, 2023 |
| Dell          | Inspiron 15 5510            | Notebook    | [bd2319fd67](https://linux-hardware.org/?probe=bd2319fd67) | May 31, 2023 |
| Jumper        | EZbook                      | Notebook    | [3ccf2e1365](https://linux-hardware.org/?probe=3ccf2e1365) | May 31, 2023 |
| HP            | ENVY 15                     | Notebook    | [ad3cf182fe](https://linux-hardware.org/?probe=ad3cf182fe) | May 30, 2023 |
| HP            | ENVY 15                     | Notebook    | [5acbfb03f4](https://linux-hardware.org/?probe=5acbfb03f4) | May 30, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [de30e713bf](https://linux-hardware.org/?probe=de30e713bf) | May 30, 2023 |
| Lenovo        | IdeaPad 5 14ALC05 82LM      | Notebook    | [bb50e13268](https://linux-hardware.org/?probe=bb50e13268) | May 30, 2023 |
| ASUSTek       | P5KPL-AM                    | Desktop     | [48359795cc](https://linux-hardware.org/?probe=48359795cc) | May 30, 2023 |
| HP            | Pavilion 15                 | Notebook    | [ca18fafda8](https://linux-hardware.org/?probe=ca18fafda8) | May 29, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [4679a6e565](https://linux-hardware.org/?probe=4679a6e565) | May 29, 2023 |
| Fujitsu       | D3233-A1 S26361-D3233-A1    | Desktop     | [ec89dcb694](https://linux-hardware.org/?probe=ec89dcb694) | May 29, 2023 |
| Lenovo        | G50-45 80E3                 | Notebook    | [013d065e72](https://linux-hardware.org/?probe=013d065e72) | May 29, 2023 |
| Dell          | Latitude E5470              | Notebook    | [77d85b619e](https://linux-hardware.org/?probe=77d85b619e) | May 29, 2023 |
| Unknown       | Unknown                     | Notebook    | [351ca28b27](https://linux-hardware.org/?probe=351ca28b27) | May 29, 2023 |
| Acer          | Aspire A515-41G             | Notebook    | [644a5d7a16](https://linux-hardware.org/?probe=644a5d7a16) | May 29, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [2f44574d7c](https://linux-hardware.org/?probe=2f44574d7c) | May 29, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [81a267d02b](https://linux-hardware.org/?probe=81a267d02b) | May 28, 2023 |
| Apple         | MacBookAir7,2               | Notebook    | [5e146ef326](https://linux-hardware.org/?probe=5e146ef326) | May 28, 2023 |
| AZW           | SER V1.0                    | Mini pc     | [6ce88925e9](https://linux-hardware.org/?probe=6ce88925e9) | May 28, 2023 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [c7afdbbd76](https://linux-hardware.org/?probe=c7afdbbd76) | May 28, 2023 |
| Apple         | MacBookPro6,2               | Notebook    | [db9c87ce89](https://linux-hardware.org/?probe=db9c87ce89) | May 28, 2023 |
| Sony          | SVE1713X1EB                 | Notebook    | [2695d0a6c8](https://linux-hardware.org/?probe=2695d0a6c8) | May 28, 2023 |
| Lenovo        | IdeaPad 5 15IIL05 81YK      | Notebook    | [1eecbd5808](https://linux-hardware.org/?probe=1eecbd5808) | May 27, 2023 |
| HP            | G42                         | Notebook    | [7b9612a51a](https://linux-hardware.org/?probe=7b9612a51a) | May 27, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [e74ee1390f](https://linux-hardware.org/?probe=e74ee1390f) | May 26, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [ac75726738](https://linux-hardware.org/?probe=ac75726738) | May 26, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e21476b6d2](https://linux-hardware.org/?probe=e21476b6d2) | May 26, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [433b367e58](https://linux-hardware.org/?probe=433b367e58) | May 26, 2023 |
| Acer          | Aspire A515-52G             | Notebook    | [ac85063e46](https://linux-hardware.org/?probe=ac85063e46) | May 26, 2023 |
| Gigabyte      | B450M DS3H-CF               | Desktop     | [cc8e36e75a](https://linux-hardware.org/?probe=cc8e36e75a) | May 26, 2023 |
| ASRock        | 990FX Extreme4              | Desktop     | [8c61dd5381](https://linux-hardware.org/?probe=8c61dd5381) | May 26, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [1ddb5fe9a0](https://linux-hardware.org/?probe=1ddb5fe9a0) | May 26, 2023 |
| ASUSTek       | P7P55-M                     | Desktop     | [a8fd95ce79](https://linux-hardware.org/?probe=a8fd95ce79) | May 25, 2023 |
| Lenovo        | IdeaPad Z580                | Notebook    | [8d9c3b024d](https://linux-hardware.org/?probe=8d9c3b024d) | May 25, 2023 |
| ASUSTek       | PRIME H270-PRO              | Desktop     | [2a14c05edc](https://linux-hardware.org/?probe=2a14c05edc) | May 25, 2023 |
| ASUSTek       | S551LB                      | Notebook    | [86f50d3933](https://linux-hardware.org/?probe=86f50d3933) | May 25, 2023 |
| Mediacom      | SMARTBOOK ONE               | Notebook    | [ad010a6b3e](https://linux-hardware.org/?probe=ad010a6b3e) | May 25, 2023 |
| HPE           | ProLiant MicroServer Gen... | Desktop     | [530b841978](https://linux-hardware.org/?probe=530b841978) | May 25, 2023 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [4c9595e6ea](https://linux-hardware.org/?probe=4c9595e6ea) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [d674d76da5](https://linux-hardware.org/?probe=d674d76da5) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | Notebook    | [978ae98d6e](https://linux-hardware.org/?probe=978ae98d6e) | May 24, 2023 |
| Lenovo        | ThinkPad W541 20EGS24J00    | Notebook    | [3b74b092c6](https://linux-hardware.org/?probe=3b74b092c6) | May 24, 2023 |
| Sony          | SVE1513Q1ESI                | Notebook    | [422e8954f2](https://linux-hardware.org/?probe=422e8954f2) | May 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [c5baa41ff7](https://linux-hardware.org/?probe=c5baa41ff7) | May 24, 2023 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [174a3139c4](https://linux-hardware.org/?probe=174a3139c4) | May 24, 2023 |
| ASUSTek       | ROG Strix G733PZ_G733PZ     | Notebook    | [e484eaf025](https://linux-hardware.org/?probe=e484eaf025) | May 24, 2023 |
| Dell          | Precision 3571              | Notebook    | [3806fcdb9c](https://linux-hardware.org/?probe=3806fcdb9c) | May 24, 2023 |
| HP            | EliteBook 845 G8 Noteboo... | Notebook    | [1280876877](https://linux-hardware.org/?probe=1280876877) | May 24, 2023 |
| Sony          | SVF13N2J2ES                 | Notebook    | [01e2285654](https://linux-hardware.org/?probe=01e2285654) | May 24, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [4ddad1d733](https://linux-hardware.org/?probe=4ddad1d733) | May 24, 2023 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [0dfd1ede62](https://linux-hardware.org/?probe=0dfd1ede62) | May 23, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [e1baf451db](https://linux-hardware.org/?probe=e1baf451db) | May 23, 2023 |
| ASRock        | AB350M Pro4                 | Desktop     | [9f7d80df58](https://linux-hardware.org/?probe=9f7d80df58) | May 23, 2023 |
| Apple         | MacBookPro7,1               | Notebook    | [61ef8e4e63](https://linux-hardware.org/?probe=61ef8e4e63) | May 23, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [e177bb8db5](https://linux-hardware.org/?probe=e177bb8db5) | May 23, 2023 |
| Valve         | Jupiter                     | Notebook    | [223ab4f15c](https://linux-hardware.org/?probe=223ab4f15c) | May 23, 2023 |
| HP            | ENVY 15                     | Notebook    | [85a97390d5](https://linux-hardware.org/?probe=85a97390d5) | May 23, 2023 |
| Sony          | SVE1513Q1ESI                | Notebook    | [eef57d6c26](https://linux-hardware.org/?probe=eef57d6c26) | May 23, 2023 |
| MSI           | B550-A PRO                  | Desktop     | [1ec3710265](https://linux-hardware.org/?probe=1ec3710265) | May 23, 2023 |
| MSI           | X99A GAMING PRO CARBON      | Desktop     | [d0312b1a56](https://linux-hardware.org/?probe=d0312b1a56) | May 23, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [f9f3305d0b](https://linux-hardware.org/?probe=f9f3305d0b) | May 23, 2023 |
| HP            | 2AF3                        | Desktop     | [e70a1c12fb](https://linux-hardware.org/?probe=e70a1c12fb) | May 22, 2023 |
| HUAWEI        | NBLB-WAX9N                  | Notebook    | [14b20068ca](https://linux-hardware.org/?probe=14b20068ca) | May 22, 2023 |
| Lenovo        | Legion 5 15ARH05H 82B1      | Notebook    | [5300f7df17](https://linux-hardware.org/?probe=5300f7df17) | May 22, 2023 |
| Unknown       | Unknown                     | Desktop     | [9cc7b8d0a8](https://linux-hardware.org/?probe=9cc7b8d0a8) | May 22, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a8e6f277e2](https://linux-hardware.org/?probe=a8e6f277e2) | May 22, 2023 |
| Dell          | Latitude E6230              | Notebook    | [89c5618eb8](https://linux-hardware.org/?probe=89c5618eb8) | May 22, 2023 |
| HUAWEI        | KLVL-WXX9                   | Notebook    | [5cb11eee20](https://linux-hardware.org/?probe=5cb11eee20) | May 22, 2023 |
| HP            | ENVY 15                     | Notebook    | [21a38278ca](https://linux-hardware.org/?probe=21a38278ca) | May 21, 2023 |
| MSI           | Modern 14 B11MOL            | Notebook    | [7bc8f5e875](https://linux-hardware.org/?probe=7bc8f5e875) | May 21, 2023 |
| Lenovo        | ThinkPad X395 20NLCTO1WW    | Notebook    | [55a289b426](https://linux-hardware.org/?probe=55a289b426) | May 21, 2023 |
| ASUSTek       | ZenBook UX425JA_UX425JA     | Notebook    | [916d381f2f](https://linux-hardware.org/?probe=916d381f2f) | May 21, 2023 |
| Intel         | NUC11ATBC2 M53055-202       | Mini pc     | [6f50de46aa](https://linux-hardware.org/?probe=6f50de46aa) | May 21, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [2eb8cdff34](https://linux-hardware.org/?probe=2eb8cdff34) | May 21, 2023 |
| ASUSTek       | N53TK                       | Notebook    | [275e480739](https://linux-hardware.org/?probe=275e480739) | May 21, 2023 |
| Acer          | Aspire 7750G                | Notebook    | [61ebf173dc](https://linux-hardware.org/?probe=61ebf173dc) | May 21, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [fa899a9a41](https://linux-hardware.org/?probe=fa899a9a41) | May 21, 2023 |
| MSI           | PRO B760-P WIFI DDR4        | Desktop     | [c8c091e2d8](https://linux-hardware.org/?probe=c8c091e2d8) | May 21, 2023 |
| ASUSTek       | ROG Strix G713PV_G713PV     | Notebook    | [8ec7bb4682](https://linux-hardware.org/?probe=8ec7bb4682) | May 21, 2023 |
| Acer          | Aspire V3-572G              | Notebook    | [8f1be2d961](https://linux-hardware.org/?probe=8f1be2d961) | May 21, 2023 |
| Lenovo        | V15 G2 ALC 82KD             | Notebook    | [74274a1304](https://linux-hardware.org/?probe=74274a1304) | May 21, 2023 |
| Dell          | 0FGCC7 A01                  | Server      | [3900d6a330](https://linux-hardware.org/?probe=3900d6a330) | May 21, 2023 |
| Samsung       | RV411/RV511/E3511/S3511/... | Notebook    | [07039bd959](https://linux-hardware.org/?probe=07039bd959) | May 21, 2023 |
| Toshiba       | Satellite Pro S500          | Notebook    | [b08ca84ea8](https://linux-hardware.org/?probe=b08ca84ea8) | May 20, 2023 |
| HP            | Pavilion dv6                | Notebook    | [51e808c93a](https://linux-hardware.org/?probe=51e808c93a) | May 20, 2023 |
| Valve         | Jupiter                     | Notebook    | [6b5b728c7e](https://linux-hardware.org/?probe=6b5b728c7e) | May 20, 2023 |
| HP            | 8437                        | Desktop     | [d41a0c8439](https://linux-hardware.org/?probe=d41a0c8439) | May 20, 2023 |
| Unknown       | Unknown                     | Notebook    | [c7157cc723](https://linux-hardware.org/?probe=c7157cc723) | May 20, 2023 |
| HP            | Pavilion dv3                | Notebook    | [34c6a2c14a](https://linux-hardware.org/?probe=34c6a2c14a) | May 20, 2023 |
| Lenovo        | ThinkPad T470s 20HF0000M... | Notebook    | [3976703e20](https://linux-hardware.org/?probe=3976703e20) | May 20, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X509... | Notebook    | [1f6220f21a](https://linux-hardware.org/?probe=1f6220f21a) | May 19, 2023 |
| HP            | 8437                        | Desktop     | [ceacc79bf6](https://linux-hardware.org/?probe=ceacc79bf6) | May 19, 2023 |
| MSI           | Alpha 15 B5EEK              | Notebook    | [b309bee7e9](https://linux-hardware.org/?probe=b309bee7e9) | May 19, 2023 |
| Fujitsu       | D3161-A1 S26361-D3161-A1    | Desktop     | [76a17acffb](https://linux-hardware.org/?probe=76a17acffb) | May 19, 2023 |
| Lenovo        | ThinkPad T14 Gen 1 20S00... | Notebook    | [5e6991f9e3](https://linux-hardware.org/?probe=5e6991f9e3) | May 19, 2023 |
| Dell          | 0D881F A06                  | Desktop     | [2d5184956b](https://linux-hardware.org/?probe=2d5184956b) | May 18, 2023 |
| Unknown       | Unknown                     | Notebook    | [49c702a8c9](https://linux-hardware.org/?probe=49c702a8c9) | May 18, 2023 |
| ASUSTek       | P5B                         | Desktop     | [9d815bcd44](https://linux-hardware.org/?probe=9d815bcd44) | May 18, 2023 |
| Acer          | Aspire Z3-705               | All in one  | [95fcf79dd4](https://linux-hardware.org/?probe=95fcf79dd4) | May 18, 2023 |
| ASUSTek       | P5B                         | Desktop     | [70be41e795](https://linux-hardware.org/?probe=70be41e795) | May 18, 2023 |
| ASUSTek       | X555LPB                     | Notebook    | [c1082eef21](https://linux-hardware.org/?probe=c1082eef21) | May 18, 2023 |
| Acer          | Aspire 5920G                | Notebook    | [65638219a5](https://linux-hardware.org/?probe=65638219a5) | May 18, 2023 |
| Apple         | Mac-F65AE981FFA204ED Mac... | Mini pc     | [c9d1849e5e](https://linux-hardware.org/?probe=c9d1849e5e) | May 18, 2023 |
| HUAWEI        | BOD-WXX9                    | Notebook    | [62e064b7d0](https://linux-hardware.org/?probe=62e064b7d0) | May 18, 2023 |
| ASUSTek       | PRIME Z270-A                | Desktop     | [790c5137ba](https://linux-hardware.org/?probe=790c5137ba) | May 18, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [a35e6c0b2d](https://linux-hardware.org/?probe=a35e6c0b2d) | May 17, 2023 |
| ASUSTek       | CROSSHAIR VI HERO           | Desktop     | [bb4c9d6b4c](https://linux-hardware.org/?probe=bb4c9d6b4c) | May 17, 2023 |
| HP            | 3048h                       | Desktop     | [9e65995057](https://linux-hardware.org/?probe=9e65995057) | May 17, 2023 |
| HP            | Pavilion Laptop 15-eg1xx... | Notebook    | [b5aef01bc9](https://linux-hardware.org/?probe=b5aef01bc9) | May 17, 2023 |
| ASUSTek       | ROG STRIX B560-G GAMING ... | Desktop     | [7f3487434e](https://linux-hardware.org/?probe=7f3487434e) | May 17, 2023 |
| HP            | 09F8h                       | Desktop     | [380bbcda71](https://linux-hardware.org/?probe=380bbcda71) | May 17, 2023 |
| Lenovo        | 317E SDK0J40700 WIN 3258... | Desktop     | [281042ebf0](https://linux-hardware.org/?probe=281042ebf0) | May 17, 2023 |
| HP            | ENVY 15                     | Notebook    | [4576cea8b0](https://linux-hardware.org/?probe=4576cea8b0) | May 17, 2023 |
| HP            | 18E5                        | Desktop     | [5e25e2156a](https://linux-hardware.org/?probe=5e25e2156a) | May 16, 2023 |
| ASUSTek       | UX305FA                     | Notebook    | [36cb231f34](https://linux-hardware.org/?probe=36cb231f34) | May 16, 2023 |
| HP            | Pavilion dv6                | Notebook    | [bc505434f7](https://linux-hardware.org/?probe=bc505434f7) | May 16, 2023 |
| Dell          | Latitude E5530 non-vPro     | Notebook    | [7c05862259](https://linux-hardware.org/?probe=7c05862259) | May 16, 2023 |
| Dell          | 0D24M8 A01                  | Desktop     | [4dcf0cf794](https://linux-hardware.org/?probe=4dcf0cf794) | May 16, 2023 |
| Acer          | Nitro AN515-45              | Notebook    | [62e3c494bd](https://linux-hardware.org/?probe=62e3c494bd) | May 16, 2023 |
| ASUSTek       | PRIME B650-PLUS             | Desktop     | [212936564d](https://linux-hardware.org/?probe=212936564d) | May 16, 2023 |
| MSI           | MS-7369                     | Desktop     | [4a083f89af](https://linux-hardware.org/?probe=4a083f89af) | May 16, 2023 |
| Valve         | Jupiter                     | Notebook    | [6c64da33ef](https://linux-hardware.org/?probe=6c64da33ef) | May 16, 2023 |
| Apple         | MacBook4,1                  | Notebook    | [755f1920f2](https://linux-hardware.org/?probe=755f1920f2) | May 15, 2023 |
| Lenovo        | SHARKBAY NOK                | Desktop     | [16308738b3](https://linux-hardware.org/?probe=16308738b3) | May 15, 2023 |
| HUAWEI        | KLVD-WXX9                   | Notebook    | [ba609eb1e6](https://linux-hardware.org/?probe=ba609eb1e6) | May 15, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [bfd8d8244b](https://linux-hardware.org/?probe=bfd8d8244b) | May 15, 2023 |
| HP            | Pavilion dv6                | Notebook    | [fd5291d10e](https://linux-hardware.org/?probe=fd5291d10e) | May 15, 2023 |
| Dell          | Precision 7520              | Notebook    | [cbfb960bae](https://linux-hardware.org/?probe=cbfb960bae) | May 15, 2023 |
| Dell          | Precision 7520              | Notebook    | [a42d1a8bf5](https://linux-hardware.org/?probe=a42d1a8bf5) | May 15, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [2750a05721](https://linux-hardware.org/?probe=2750a05721) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [e9e5b21145](https://linux-hardware.org/?probe=e9e5b21145) | May 15, 2023 |
| HP            | Pavilion x2 Detachable      | Notebook    | [34c6621991](https://linux-hardware.org/?probe=34c6621991) | May 15, 2023 |
| BESSTAR Te... | UM350                       | Desktop     | [fafdf532fb](https://linux-hardware.org/?probe=fafdf532fb) | May 15, 2023 |
| TEXA          | NEMO MINI                   | Tablet      | [81fc17efec](https://linux-hardware.org/?probe=81fc17efec) | May 14, 2023 |
| Lenovo        | ThinkPad X100e 0022CTO      | Notebook    | [842b7a3ee2](https://linux-hardware.org/?probe=842b7a3ee2) | May 14, 2023 |
| TEXA          | NEMO MINI                   | Tablet      | [4b0f306d78](https://linux-hardware.org/?probe=4b0f306d78) | May 14, 2023 |
| Lenovo        | ThinkPad T14 Gen 3 21CFC... | Notebook    | [bb119829d0](https://linux-hardware.org/?probe=bb119829d0) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [020d4612bd](https://linux-hardware.org/?probe=020d4612bd) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [ca65ed1052](https://linux-hardware.org/?probe=ca65ed1052) | May 14, 2023 |
| Gigabyte      | AB350M-DS3H V2-CF           | Desktop     | [0495c4f485](https://linux-hardware.org/?probe=0495c4f485) | May 14, 2023 |
| HP            | Compaq CQ58                 | Notebook    | [0df5818390](https://linux-hardware.org/?probe=0df5818390) | May 14, 2023 |
| Valve         | Jupiter                     | Notebook    | [af70e39629](https://linux-hardware.org/?probe=af70e39629) | May 14, 2023 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [2be4ad0e3d](https://linux-hardware.org/?probe=2be4ad0e3d) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [1bb0ed422e](https://linux-hardware.org/?probe=1bb0ed422e) | May 14, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [5f3a14748e](https://linux-hardware.org/?probe=5f3a14748e) | May 13, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [ab7d27081e](https://linux-hardware.org/?probe=ab7d27081e) | May 13, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [24aaf9e627](https://linux-hardware.org/?probe=24aaf9e627) | May 13, 2023 |
| HP            | Pavilion dv6                | Notebook    | [e20ba378ac](https://linux-hardware.org/?probe=e20ba378ac) | May 13, 2023 |
| Gigabyte      | A520M DS3H                  | Desktop     | [e053d0d304](https://linux-hardware.org/?probe=e053d0d304) | May 13, 2023 |
| HP            | ENVY 15                     | Notebook    | [e188fe21b7](https://linux-hardware.org/?probe=e188fe21b7) | May 12, 2023 |
| Lenovo        | ThinkPad Edge 02173BG       | Notebook    | [05f67c346b](https://linux-hardware.org/?probe=05f67c346b) | May 12, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [4e603c1756](https://linux-hardware.org/?probe=4e603c1756) | May 12, 2023 |
| ASRock        | 775Dual-VSTA                | Desktop     | [5379481e09](https://linux-hardware.org/?probe=5379481e09) | May 12, 2023 |
| Unknown       | Unknown                     | Notebook    | [8375f52559](https://linux-hardware.org/?probe=8375f52559) | May 12, 2023 |
| HP            | 1998                        | Desktop     | [b806151d9f](https://linux-hardware.org/?probe=b806151d9f) | May 12, 2023 |
| Gigabyte      | Z87X-OC-CF                  | Desktop     | [068ef24174](https://linux-hardware.org/?probe=068ef24174) | May 12, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [8b187d1291](https://linux-hardware.org/?probe=8b187d1291) | May 11, 2023 |
| Unknown       | Unknown                     | Notebook    | [00f98129ce](https://linux-hardware.org/?probe=00f98129ce) | May 11, 2023 |
| ASUSTek       | PRO B460M-C                 | Desktop     | [80892a273c](https://linux-hardware.org/?probe=80892a273c) | May 11, 2023 |
| MSI           | B150M PRO-VDH               | Desktop     | [59efd46e1c](https://linux-hardware.org/?probe=59efd46e1c) | May 11, 2023 |
| Valve         | Jupiter                     | Notebook    | [ec8ac0aafd](https://linux-hardware.org/?probe=ec8ac0aafd) | May 11, 2023 |
| Dell          | XPS 9315                    | Notebook    | [d53e7f5d92](https://linux-hardware.org/?probe=d53e7f5d92) | May 11, 2023 |
| ASRock        | Z370 Extreme4               | Desktop     | [bdd9bcedf5](https://linux-hardware.org/?probe=bdd9bcedf5) | May 11, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [4d4946eec9](https://linux-hardware.org/?probe=4d4946eec9) | May 11, 2023 |
| Samsung       | RV410/RV510/S3510/E3510     | Notebook    | [d6a837c94d](https://linux-hardware.org/?probe=d6a837c94d) | May 11, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [e03da60adf](https://linux-hardware.org/?probe=e03da60adf) | May 11, 2023 |
| Acer          | Aspire 5715Z                | Notebook    | [81c255952d](https://linux-hardware.org/?probe=81c255952d) | May 10, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [0a3aa24894](https://linux-hardware.org/?probe=0a3aa24894) | May 10, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [8eae6560cb](https://linux-hardware.org/?probe=8eae6560cb) | May 10, 2023 |
| HP            | 2ADE                        | Desktop     | [ef4aa64bd5](https://linux-hardware.org/?probe=ef4aa64bd5) | May 10, 2023 |
| Lenovo        | ThinkPad E14 Gen 3 20Y70... | Notebook    | [eb6941b1b8](https://linux-hardware.org/?probe=eb6941b1b8) | May 10, 2023 |
| Acer          | Aspire E5-553G              | Notebook    | [922a392eee](https://linux-hardware.org/?probe=922a392eee) | May 09, 2023 |
| Dell          | Latitude 7420               | Notebook    | [4b8927333b](https://linux-hardware.org/?probe=4b8927333b) | May 09, 2023 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [666c071a8b](https://linux-hardware.org/?probe=666c071a8b) | May 09, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [0b1518261e](https://linux-hardware.org/?probe=0b1518261e) | May 09, 2023 |
| ASUSTek       | M32CD4-K                    | Desktop     | [0bca52bcc5](https://linux-hardware.org/?probe=0bca52bcc5) | May 09, 2023 |
| Dell          | Latitude E6520              | Notebook    | [668b26cd28](https://linux-hardware.org/?probe=668b26cd28) | May 09, 2023 |
| HP            | 255 G5                      | Notebook    | [4ed50eeba3](https://linux-hardware.org/?probe=4ed50eeba3) | May 09, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [4e95a5b88e](https://linux-hardware.org/?probe=4e95a5b88e) | May 08, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [5cbf24306a](https://linux-hardware.org/?probe=5cbf24306a) | May 08, 2023 |
| HP            | 2ADE                        | Desktop     | [bb8ee11580](https://linux-hardware.org/?probe=bb8ee11580) | May 08, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [3b4eb54186](https://linux-hardware.org/?probe=3b4eb54186) | May 08, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [6b908b35cc](https://linux-hardware.org/?probe=6b908b35cc) | May 08, 2023 |
| HUAWEI        | NBLK-WAX9X                  | Notebook    | [a4f5dce6d6](https://linux-hardware.org/?probe=a4f5dce6d6) | May 08, 2023 |
| Dell          | XPS 15 9570                 | Notebook    | [100534a570](https://linux-hardware.org/?probe=100534a570) | May 08, 2023 |
| Notebook      | P750ZM                      | Notebook    | [2cbd56abdc](https://linux-hardware.org/?probe=2cbd56abdc) | May 08, 2023 |
| Apple         | MacBookPro3,1               | Notebook    | [561202c004](https://linux-hardware.org/?probe=561202c004) | May 07, 2023 |
| HP            | 255 G3                      | Notebook    | [d95f6211dc](https://linux-hardware.org/?probe=d95f6211dc) | May 07, 2023 |
| HP            | Pavilion dv6                | Notebook    | [978d2165ac](https://linux-hardware.org/?probe=978d2165ac) | May 07, 2023 |
| ASUSTek       | TUF Gaming B650-PLUS WIF... | Desktop     | [ecfcb0cab6](https://linux-hardware.org/?probe=ecfcb0cab6) | May 07, 2023 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [d6085d9a0b](https://linux-hardware.org/?probe=d6085d9a0b) | May 07, 2023 |
| HP            | 250 G5 Notebook PC          | Notebook    | [c1a5a5b4d9](https://linux-hardware.org/?probe=c1a5a5b4d9) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [e81eb02947](https://linux-hardware.org/?probe=e81eb02947) | May 07, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [96cfd64792](https://linux-hardware.org/?probe=96cfd64792) | May 07, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [ab9ff23d88](https://linux-hardware.org/?probe=ab9ff23d88) | May 07, 2023 |
| Acer          | Aspire E5-551G              | Notebook    | [a21a8395d8](https://linux-hardware.org/?probe=a21a8395d8) | May 07, 2023 |
| Lenovo        | G50-70 20351                | Notebook    | [784570bae3](https://linux-hardware.org/?probe=784570bae3) | May 07, 2023 |
| Dell          | XPS 13 9343                 | Notebook    | [5e91733408](https://linux-hardware.org/?probe=5e91733408) | May 07, 2023 |
| Lenovo        | ThinkPad X260 20F6CTO1WW    | Notebook    | [7998abcdcd](https://linux-hardware.org/?probe=7998abcdcd) | May 07, 2023 |
| HP            | Notebook                    | Notebook    | [cb89261339](https://linux-hardware.org/?probe=cb89261339) | May 06, 2023 |
| HP            | Laptop 15s-fq5xxx           | Notebook    | [8ce0b92713](https://linux-hardware.org/?probe=8ce0b92713) | May 06, 2023 |
| HP            | EliteBook 2530p             | Notebook    | [9963aba3a2](https://linux-hardware.org/?probe=9963aba3a2) | May 06, 2023 |
| Lenovo        | IdeaPad U510 20191          | Notebook    | [23414f0626](https://linux-hardware.org/?probe=23414f0626) | May 06, 2023 |
| HP            | Notebook                    | Notebook    | [74f9f1122e](https://linux-hardware.org/?probe=74f9f1122e) | May 06, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [46894747b1](https://linux-hardware.org/?probe=46894747b1) | May 05, 2023 |
| MSI           | X570-A PRO                  | Desktop     | [2723e21a6e](https://linux-hardware.org/?probe=2723e21a6e) | May 05, 2023 |
| TrekStor      | SurfTab twin 11.6           | Convertible | [2d5ecba977](https://linux-hardware.org/?probe=2d5ecba977) | May 05, 2023 |
| Lenovo        | IdeaPad 3 15ITL6 82H8       | Notebook    | [7aeb31c7f1](https://linux-hardware.org/?probe=7aeb31c7f1) | May 05, 2023 |
| Dell          | Inspiron 5406 2n1           | Convertible | [91c6b0d769](https://linux-hardware.org/?probe=91c6b0d769) | May 05, 2023 |
| MSI           | Modern 14 B11MOL            | Notebook    | [d6bc185f4e](https://linux-hardware.org/?probe=d6bc185f4e) | May 05, 2023 |
| Lenovo        | IdeaPad Gaming 3 15ARH7 ... | Notebook    | [bd885c202d](https://linux-hardware.org/?probe=bd885c202d) | May 05, 2023 |
| Lenovo        | ThinkPad T495s 20QJCTO1W... | Notebook    | [a27c899176](https://linux-hardware.org/?probe=a27c899176) | May 04, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [af9621c92b](https://linux-hardware.org/?probe=af9621c92b) | May 04, 2023 |
| HP            | Elite x2 1012 G1            | Notebook    | [20dcc3e6b3](https://linux-hardware.org/?probe=20dcc3e6b3) | May 04, 2023 |
| KUU           | Andes II                    | Notebook    | [b15876e521](https://linux-hardware.org/?probe=b15876e521) | May 04, 2023 |
| Dell          | XPS 15 9510                 | Notebook    | [ce70c65f11](https://linux-hardware.org/?probe=ce70c65f11) | May 03, 2023 |
| HP            | Compaq Presario C700        | Notebook    | [8c62d76e28](https://linux-hardware.org/?probe=8c62d76e28) | May 03, 2023 |
| Sony          | SVF1521G1EW                 | Notebook    | [b84b2ed08a](https://linux-hardware.org/?probe=b84b2ed08a) | May 03, 2023 |
| Acer          | Swift SF515-51T             | Notebook    | [80d7446f47](https://linux-hardware.org/?probe=80d7446f47) | May 03, 2023 |
| Olivetti      | OLIBOOK P35-XXXAEU          | Notebook    | [bb924b0c19](https://linux-hardware.org/?probe=bb924b0c19) | May 03, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X510... | Notebook    | [4280750d03](https://linux-hardware.org/?probe=4280750d03) | May 03, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [f8d80b7cf0](https://linux-hardware.org/?probe=f8d80b7cf0) | May 03, 2023 |
| Samsung       | 750XDA                      | Notebook    | [2e99c882ff](https://linux-hardware.org/?probe=2e99c882ff) | May 03, 2023 |
| HUAWEI        | BOM-WXX9                    | Notebook    | [fd0dee0606](https://linux-hardware.org/?probe=fd0dee0606) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | Notebook    | [d8256a8177](https://linux-hardware.org/?probe=d8256a8177) | May 03, 2023 |
| TELECOMITA... | M7x0S                       | Notebook    | [d4019e13f1](https://linux-hardware.org/?probe=d4019e13f1) | May 03, 2023 |
| Lenovo        | IdeaPad 320-15AST 80XV      | Notebook    | [910824ac40](https://linux-hardware.org/?probe=910824ac40) | May 03, 2023 |
| Gigabyte      | Z170X-Gaming 3              | Desktop     | [50f922927f](https://linux-hardware.org/?probe=50f922927f) | May 03, 2023 |
| Lenovo        | ThinkPad X220 4291IR6       | Notebook    | [56d274f769](https://linux-hardware.org/?probe=56d274f769) | May 03, 2023 |
| Lenovo        | V130-15IKB 81HN             | Notebook    | [8c3e5e8d50](https://linux-hardware.org/?probe=8c3e5e8d50) | May 03, 2023 |
| Unknown       | 1.0                         | Desktop     | [5f99ebeed7](https://linux-hardware.org/?probe=5f99ebeed7) | May 02, 2023 |
| Dell          | Latitude E7270              | Notebook    | [62c1cdc600](https://linux-hardware.org/?probe=62c1cdc600) | May 02, 2023 |
| ASUSTek       | ROG STRIX X299-E GAMING     | Desktop     | [553a101cf8](https://linux-hardware.org/?probe=553a101cf8) | May 02, 2023 |
| Sony          | VPCF11C5E                   | Notebook    | [77f08d3d00](https://linux-hardware.org/?probe=77f08d3d00) | May 02, 2023 |
| Dell          | Latitude E7270              | Notebook    | [96e1a00bae](https://linux-hardware.org/?probe=96e1a00bae) | May 02, 2023 |
| HP            | Laptop 15s-eq3xxx           | Notebook    | [5375a4f57c](https://linux-hardware.org/?probe=5375a4f57c) | May 02, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [12d9338aba](https://linux-hardware.org/?probe=12d9338aba) | May 02, 2023 |
| Acer          | H11H4-AI V:1.0              | Desktop     | [eaa909b055](https://linux-hardware.org/?probe=eaa909b055) | May 02, 2023 |
| Lenovo        | IdeaPad 330S-15IKB 81F5     | Notebook    | [b56701568d](https://linux-hardware.org/?probe=b56701568d) | May 01, 2023 |
| HP            | 255 G4                      | Notebook    | [b06ddec94b](https://linux-hardware.org/?probe=b06ddec94b) | May 01, 2023 |
| Timi          | RedmiBook 16                | Notebook    | [01706331eb](https://linux-hardware.org/?probe=01706331eb) | May 01, 2023 |
| HP            | Compaq 8510w                | Notebook    | [eea89c8c92](https://linux-hardware.org/?probe=eea89c8c92) | May 01, 2023 |
| ASRock        | G41M-GS                     | Desktop     | [0824a9c571](https://linux-hardware.org/?probe=0824a9c571) | May 01, 2023 |
| HP            | ENVY 15                     | Notebook    | [935dc183e1](https://linux-hardware.org/?probe=935dc183e1) | May 01, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [bfbda66d8b](https://linux-hardware.org/?probe=bfbda66d8b) | May 01, 2023 |
| Dell          | 0WR7PY A01                  | Desktop     | [dfe07c7749](https://linux-hardware.org/?probe=dfe07c7749) | May 01, 2023 |
| ASRock        | H61M-DGS                    | Desktop     | [f395109c45](https://linux-hardware.org/?probe=f395109c45) | May 01, 2023 |
| ASUSTek       | K52Jc                       | Notebook    | [ae414cf185](https://linux-hardware.org/?probe=ae414cf185) | May 01, 2023 |
| ASUSTek       | T103HAF                     | Tablet      | [961e13c584](https://linux-hardware.org/?probe=961e13c584) | May 01, 2023 |
| Pegatron      | 2A94                        | Desktop     | [7dcdfa9b9f](https://linux-hardware.org/?probe=7dcdfa9b9f) | May 01, 2023 |
| Mediacom      | SmartBook 14 FullHD - SB... | Notebook    | [cbc75f825e](https://linux-hardware.org/?probe=cbc75f825e) | May 01, 2023 |
| MSI           | MPG X570 GAMING PRO CARB... | Desktop     | [d02d21f47a](https://linux-hardware.org/?probe=d02d21f47a) | May 01, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [26681d2879](https://linux-hardware.org/?probe=26681d2879) | May 01, 2023 |
| ASRock        | 970 Pro3 R2.0               | Desktop     | [577b5e8f51](https://linux-hardware.org/?probe=577b5e8f51) | May 01, 2023 |
| Lenovo        | Legion S7 15IMH5 82BC       | Notebook    | [a57d01b946](https://linux-hardware.org/?probe=a57d01b946) | May 01, 2023 |
| HP            | Pavilion x360 Convertibl... | Convertible | [1b2adc0ae5](https://linux-hardware.org/?probe=1b2adc0ae5) | May 01, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X580... | Notebook    | [05251702aa](https://linux-hardware.org/?probe=05251702aa) | Apr 30, 2023 |
| HP            | 255 G8 Notebook PC          | Notebook    | [7262375294](https://linux-hardware.org/?probe=7262375294) | Apr 30, 2023 |
| MSI           | 760GM-P23                   | Desktop     | [4ac55a6bbe](https://linux-hardware.org/?probe=4ac55a6bbe) | Apr 30, 2023 |
| HP            | Compaq 6720s                | Notebook    | [cc5f5ee72c](https://linux-hardware.org/?probe=cc5f5ee72c) | Apr 30, 2023 |

...

See full list of test cases in the file [Test_Cases.md](</Location/Italy/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                         | Computers | Percent |
|------------------------------|-----------|---------|
| Ubuntu 20.04                 | 905       | 10.98%  |
| Ubuntu 18.04                 | 564       | 6.84%   |
| Ubuntu 22.04                 | 475       | 5.76%   |
| Arch Rolling                 | 239       | 2.9%    |
| OpenMandriva 4.2             | 221       | 2.68%   |
| Debian 11                    | 202       | 2.45%   |
| OpenMandriva 4.3             | 194       | 2.35%   |
| Fedora 36                    | 151       | 1.83%   |
| Linux Mint 21.1              | 146       | 1.77%   |
| Ubuntu 20.10                 | 130       | 1.58%   |
| Ubuntu 22.10                 | 129       | 1.56%   |
| Arch                         | 123       | 1.49%   |
| Ubuntu 19.10                 | 120       | 1.46%   |
| Zorin 16                     | 119       | 1.44%   |
| Pop!_OS 22.04                | 117       | 1.42%   |
| Ubuntu 19.04                 | 108       | 1.31%   |
| Xubuntu 18.04                | 107       | 1.3%    |
| Xubuntu 20.04                | 104       | 1.26%   |
| Linux Mint 20.3              | 104       | 1.26%   |
| Fedora 37                    | 103       | 1.25%   |
| KDE neon 20.04               | 102       | 1.24%   |
| OpenMandriva 23.03           | 101       | 1.22%   |
| Ubuntu 21.10                 | 96        | 1.16%   |
| Linux Mint 21                | 93        | 1.13%   |
| OpenMandriva 23.01           | 91        | 1.1%    |
| EndeavourOS Rolling          | 90        | 1.09%   |
| Ubuntu 21.04                 | 83        | 1.01%   |
| Debian 10                    | 81        | 0.98%   |
| Manjaro                      | 77        | 0.93%   |
| Zorin 15                     | 71        | 0.86%   |
| Ubuntu 18.10                 | 68        | 0.82%   |
| Kubuntu 22.04                | 68        | 0.82%   |
| Fedora 38                    | 68        | 0.82%   |
| Fedora 35                    | 68        | 0.82%   |
| Linux Mint 19.3              | 66        | 0.8%    |
| Kubuntu 20.04                | 66        | 0.8%    |
| openSUSE Tumbleweed-XXXXXXXX | 63        | 0.76%   |
| ROSA R10                     | 62        | 0.75%   |
| Linux Mint 20.2              | 60        | 0.73%   |
| Linux Mint 20.1              | 60        | 0.73%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name          | Computers | Percent |
|---------------|-----------|---------|
| Ubuntu        | 2622      | 33.8%   |
| OpenMandriva  | 681       | 8.78%   |
| Linux Mint    | 601       | 7.75%   |
| Fedora        | 517       | 6.66%   |
| Debian        | 372       | 4.8%    |
| Arch          | 353       | 4.55%   |
| Xubuntu       | 309       | 3.98%   |
| Pop!_OS       | 265       | 3.42%   |
| Manjaro       | 230       | 2.96%   |
| Kubuntu       | 211       | 2.72%   |
| Zorin         | 200       | 2.58%   |
| ROSA          | 185       | 2.38%   |
| KDE neon      | 150       | 1.93%   |
| Lubuntu       | 97        | 1.25%   |
| EndeavourOS   | 96        | 1.24%   |
| openSUSE      | 89        | 1.15%   |
| Ubuntu MATE   | 77        | 0.99%   |
| Elementary    | 61        | 0.79%   |
| Endless       | 48        | 0.62%   |
| Ubuntu Unity  | 43        | 0.55%   |
| ArcoLinux     | 42        | 0.54%   |
| Clear Linux   | 39        | 0.5%    |
| LMDE          | 37        | 0.48%   |
| MX            | 36        | 0.46%   |
| BlackPanther  | 35        | 0.45%   |
| Gentoo        | 33        | 0.43%   |
| Kali          | 27        | 0.35%   |
| Garuda Linux  | 25        | 0.32%   |
| Ubuntu Budgie | 23        | 0.3%    |
| Peppermint    | 20        | 0.26%   |
| Parrot        | 16        | 0.21%   |
| SteamOS       | 15        | 0.19%   |
| Nobara        | 15        | 0.19%   |
| LinuxFX       | 12        | 0.15%   |
| Ubuntu Studio | 11        | 0.14%   |
| NixOS         | 11        | 0.14%   |
| Xero          | 10        | 0.13%   |
| Raspbian      | 10        | 0.13%   |
| Slackware     | 9         | 0.12%   |
| Q4OS          | 9         | 0.12%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                  | Computers | Percent |
|--------------------------|-----------|---------|
| 5.10.14-desktop-1omv4002 | 214       | 2.33%   |
| 5.16.7-desktop-1omv4003  | 184       | 2.01%   |
| 5.15.0-52-generic        | 168       | 1.83%   |
| 5.4.0-42-generic         | 125       | 1.36%   |
| 5.15.0-56-generic        | 122       | 1.33%   |
| 6.2.6-desktop-1omv2390   | 100       | 1.09%   |
| 5.4.0-52-generic         | 81        | 0.88%   |
| 6.1.1-desktop-1omv2290   | 76        | 0.83%   |
| 5.15.0-58-generic        | 74        | 0.81%   |
| 5.15.0-47-generic        | 71        | 0.77%   |
| 5.4.0-26-generic         | 66        | 0.72%   |
| 5.3.0-46-generic         | 66        | 0.72%   |
| 5.15.0-46-generic        | 65        | 0.71%   |
| 5.4.0-58-generic         | 60        | 0.65%   |
| 5.4.0-29-generic         | 59        | 0.64%   |
| 5.3.0-40-generic         | 58        | 0.63%   |
| 5.4.0-48-generic         | 56        | 0.61%   |
| 5.15.0-43-generic        | 54        | 0.59%   |
| 5.3.0-42-generic         | 48        | 0.52%   |
| 5.4.0-54-generic         | 46        | 0.5%    |
| 5.10.0-19-amd64          | 42        | 0.46%   |
| 5.19.0-23-generic        | 41        | 0.45%   |
| 5.15.0-53-generic        | 41        | 0.45%   |
| 5.15.0-41-generic        | 41        | 0.45%   |
| 6.0.2-arch1-1            | 40        | 0.44%   |
| 5.4.0-28-generic         | 40        | 0.44%   |
| 5.19.0-35-generic        | 40        | 0.44%   |
| 5.15.0-60-generic        | 40        | 0.44%   |
| 5.0.0-37-generic         | 39        | 0.43%   |
| 5.4.0-56-generic         | 38        | 0.41%   |
| 5.4.0-37-generic         | 38        | 0.41%   |
| 5.4.0-33-generic         | 38        | 0.41%   |
| 5.15.0-48-generic        | 38        | 0.41%   |
| 5.4.0-47-generic         | 37        | 0.4%    |
| 5.19.0-32-generic        | 37        | 0.4%    |
| 5.11.0-38-generic        | 37        | 0.4%    |
| 5.4.0-40-generic         | 35        | 0.38%   |
| 5.13.0-28-generic        | 35        | 0.38%   |
| 5.15.0-50-generic        | 34        | 0.37%   |
| 5.10.0-21-amd64          | 34        | 0.37%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4.0   | 1264      | 14.8%   |
| 5.15.0  | 903       | 10.58%  |
| 4.15.0  | 472       | 5.53%   |
| 5.8.0   | 395       | 4.63%   |
| 5.3.0   | 385       | 4.51%   |
| 5.19.0  | 380       | 4.45%   |
| 5.11.0  | 309       | 3.62%   |
| 5.13.0  | 303       | 3.55%   |
| 5.10.0  | 239       | 2.8%    |
| 5.0.0   | 224       | 2.62%   |
| 5.10.14 | 215       | 2.52%   |
| 5.16.7  | 187       | 2.19%   |
| 4.18.0  | 158       | 1.85%   |
| 6.2.6   | 127       | 1.49%   |
| 6.2.0   | 93        | 1.09%   |
| 6.1.1   | 89        | 1.04%   |
| 6.0.2   | 83        | 0.97%   |
| 4.19.0  | 79        | 0.93%   |
| 6.1.0   | 56        | 0.66%   |
| 5.19.16 | 47        | 0.55%   |
| 6.4.11  | 40        | 0.47%   |
| 6.0.0   | 38        | 0.45%   |
| 4.9.60  | 36        | 0.42%   |
| 4.9.20  | 36        | 0.42%   |
| 6.0.6   | 35        | 0.41%   |
| 6.0.12  | 34        | 0.4%    |
| 4.18.16 | 34        | 0.4%    |
| 5.17.5  | 32        | 0.37%   |
| 4.4.0   | 29        | 0.34%   |
| 5.19.6  | 28        | 0.33%   |
| 6.0.7   | 26        | 0.3%    |
| 6.0.10  | 24        | 0.28%   |
| 6.2.9   | 21        | 0.25%   |
| 6.0.5   | 21        | 0.25%   |
| 5.16.11 | 20        | 0.23%   |
| 6.1.8   | 19        | 0.22%   |
| 6.0.9   | 19        | 0.22%   |
| 5.17.1  | 19        | 0.22%   |
| 5.12.4  | 18        | 0.21%   |
| 6.4.8   | 17        | 0.2%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.4     | 1344      | 15.95%  |
| 5.15    | 1072      | 12.73%  |
| 5.19    | 567       | 6.73%   |
| 5.10    | 550       | 6.53%   |
| 4.15    | 474       | 5.63%   |
| 5.8     | 465       | 5.52%   |
| 5.3     | 415       | 4.93%   |
| 5.11    | 371       | 4.4%    |
| 5.13    | 336       | 3.99%   |
| 6.2     | 333       | 3.95%   |
| 6.0     | 328       | 3.89%   |
| 6.1     | 299       | 3.55%   |
| 5.16    | 283       | 3.36%   |
| 5.0     | 232       | 2.75%   |
| 4.18    | 199       | 2.36%   |
| 6.4     | 125       | 1.48%   |
| 4.9     | 124       | 1.47%   |
| 5.17    | 107       | 1.27%   |
| 4.19    | 104       | 1.23%   |
| 5.18    | 99        | 1.18%   |
| 6.3     | 92        | 1.09%   |
| 5.9     | 82        | 0.97%   |
| 5.14    | 82        | 0.97%   |
| 5.6     | 64        | 0.76%   |
| 5.12    | 62        | 0.74%   |
| 5.7     | 50        | 0.59%   |
| 5.5     | 47        | 0.56%   |
| 4.4     | 31        | 0.37%   |
| 4.1     | 16        | 0.19%   |
| 5.2     | 13        | 0.15%   |
| 4.13    | 12        | 0.14%   |
| 6.5     | 7         | 0.08%   |
| 5.1     | 7         | 0.08%   |
| 4.20    | 5         | 0.06%   |
| 4.17    | 5         | 0.06%   |
| 4.12    | 5         | 0.06%   |
| 4.14    | 4         | 0.05%   |
| 3.10    | 3         | 0.04%   |
| 4.16    | 2         | 0.02%   |
| 4.10    | 2         | 0.02%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| x86_64  | 7077      | 94.96%  |
| i686    | 324       | 4.35%   |
| aarch64 | 36        | 0.48%   |
| armv7l  | 15        | 0.2%    |
| ppc64le | 1         | 0.01%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| GNOME             | 3292      | 42.19%  |
| KDE5              | 1532      | 19.63%  |
| Unknown           | 847       | 10.85%  |
| XFCE              | 653       | 8.37%   |
| X-Cinnamon        | 495       | 6.34%   |
| MATE              | 217       | 2.78%   |
| KDE               | 140       | 1.79%   |
| LXQt              | 125       | 1.6%    |
| KDE4              | 108       | 1.38%   |
| Pantheon          | 60        | 0.77%   |
| Cinnamon          | 55        | 0.7%    |
| LXDE              | 51        | 0.65%   |
| Unity             | 45        | 0.58%   |
| Budgie            | 34        | 0.44%   |
| GNOME Flashback   | 29        | 0.37%   |
| i3                | 22        | 0.28%   |
| GNOME Classic     | 16        | 0.21%   |
| sway              | 11        | 0.14%   |
| Deepin            | 11        | 0.14%   |
| Hyprland          | 10        | 0.13%   |
| Openbox           | 9         | 0.12%   |
| Trinity           | 6         | 0.08%   |
| bspwm             | 6         | 0.08%   |
| lightdm-xsession  | 5         | 0.06%   |
| DWM               | 4         | 0.05%   |
| xubuntu           | 2         | 0.03%   |
| qtile             | 2         | 0.03%   |
| icewm             | 2         | 0.03%   |
| enlightenment     | 2         | 0.03%   |
| awesome           | 2         | 0.03%   |
| ubuntu:pika:GNOME | 1         | 0.01%   |
| ubuntu            | 1         | 0.01%   |
| pika:GNOME        | 1         | 0.01%   |
| none+i3           | 1         | 0.01%   |
| none+bspwm        | 1         | 0.01%   |
| Lubuntu           | 1         | 0.01%   |
| herbstluftwm      | 1         | 0.01%   |
| gamescope         | 1         | 0.01%   |
| FVWM              | 1         | 0.01%   |
| Cutefish          | 1         | 0.01%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 5804      | 75.21%  |
| Wayland | 1370      | 17.75%  |
| Unknown | 429       | 5.56%   |
| Tty     | 114       | 1.48%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3461      | 44.37%  |
| SDDM    | 1442      | 18.48%  |
| GDM3    | 950       | 12.18%  |
| GDM     | 831       | 10.65%  |
| LightDM | 800       | 10.26%  |
| TDM     | 170       | 2.18%   |
| KDM     | 111       | 1.42%   |
| XDM     | 15        | 0.19%   |
| SLiM    | 7         | 0.09%   |
| LXDM    | 5         | 0.06%   |
| GREETD  | 3         | 0.04%   |
| Ly      | 2         | 0.03%   |
| WDM     | 1         | 0.01%   |
| SLIMSKI | 1         | 0.01%   |
| NODM    | 1         | 0.01%   |
| MDM     | 1         | 0.01%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang         | Computers | Percent |
|--------------|-----------|---------|
| it_IT        | 4771      | 62.2%   |
| en_US        | 1582      | 20.62%  |
| Unknown      | 865       | 11.28%  |
| en_GB        | 169       | 2.2%    |
| C            | 147       | 1.92%   |
| de_DE        | 26        | 0.34%   |
| fr_FR        | 16        | 0.21%   |
| es_ES        | 12        | 0.16%   |
| de_IT        | 12        | 0.16%   |
| POSIX        | 9         | 0.12%   |
| ru_RU        | 8         | 0.1%    |
| it_CH        | 8         | 0.1%    |
| en_IE        | 6         | 0.08%   |
| en_AG        | 5         | 0.07%   |
| it_IT@euro   | 4         | 0.05%   |
| de_AT        | 4         | 0.05%   |
| en_AU        | 3         | 0.04%   |
| en_US.UTF8   | 2         | 0.03%   |
| sc_IT        | 1         | 0.01%   |
| ro_RO        | 1         | 0.01%   |
| pt_BR        | 1         | 0.01%   |
| pl_PL        | 1         | 0.01%   |
| it_ITutf8    | 1         | 0.01%   |
| it_IT.UTF -8 | 1         | 0.01%   |
| it           | 1         | 0.01%   |
| hu_HU        | 1         | 0.01%   |
| fur_IT       | 1         | 0.01%   |
| fr_CH        | 1         | 0.01%   |
| fr_BE        | 1         | 0.01%   |
| es_US        | 1         | 0.01%   |
| es_MX        | 1         | 0.01%   |
| en_US@euro   | 1         | 0.01%   |
| en_US.utf-8  | 1         | 0.01%   |
| en_US.ASCII  | 1         | 0.01%   |
| en_IN        | 1         | 0.01%   |
| en_DK        | 1         | 0.01%   |
| de_CH        | 1         | 0.01%   |
| Default      | 1         | 0.01%   |
| C.UTF8       | 1         | 0.01%   |
| bg_BG        | 1         | 0.01%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 3897      | 51.11%  |
| EFI  | 3728      | 48.89%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type     | Computers | Percent |
|----------|-----------|---------|
| Ext4     | 5716      | 74.39%  |
| Overlay  | 794       | 10.33%  |
| Btrfs    | 636       | 8.28%   |
| Unknown  | 230       | 2.99%   |
| Tmpfs    | 137       | 1.78%   |
| Xfs      | 76        | 0.99%   |
| Zfs      | 38        | 0.49%   |
| Ext2     | 19        | 0.25%   |
| Ext3     | 17        | 0.22%   |
| F2fs     | 13        | 0.17%   |
| Aufs     | 3         | 0.04%   |
| XXX4     | 2         | 0.03%   |
| XXXX     | 1         | 0.01%   |
| Reiserfs | 1         | 0.01%   |
| Jfs      | 1         | 0.01%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 3702      | 48.22%  |
| GPT     | 3066      | 39.93%  |
| MBR     | 910       | 11.85%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 6398      | 83.92%  |
| Yes       | 1226      | 16.08%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 4833      | 63.38%  |
| Yes       | 2793      | 36.62%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| ASUSTek Computer        | 1531      | 20.56%  |
| Hewlett-Packard         | 1266      | 17%     |
| Lenovo                  | 852       | 11.44%  |
| Dell                    | 603       | 8.1%    |
| Acer                    | 598       | 8.03%   |
| MSI                     | 430       | 5.77%   |
| ASRock                  | 334       | 4.49%   |
| Gigabyte Technology     | 263       | 3.53%   |
| Apple                   | 167       | 2.24%   |
| Intel                   | 109       | 1.46%   |
| HUAWEI                  | 108       | 1.45%   |
| Toshiba                 | 106       | 1.42%   |
| Sony                    | 96        | 1.29%   |
| Unknown                 | 81        | 1.09%   |
| Fujitsu                 | 80        | 1.07%   |
| Samsung Electronics     | 78        | 1.05%   |
| Packard Bell            | 57        | 0.77%   |
| Pegatron                | 46        | 0.62%   |
| Raspberry Pi Foundation | 37        | 0.5%    |
| Mediacom                | 34        | 0.46%   |
| Fujitsu Siemens         | 33        | 0.44%   |
| Chuwi                   | 33        | 0.44%   |
| Teclast                 | 27        | 0.36%   |
| AMI                     | 25        | 0.34%   |
| Notebook                | 24        | 0.32%   |
| Microsoft               | 24        | 0.32%   |
| Foxconn                 | 22        | 0.3%    |
| Microtech               | 20        | 0.27%   |
| BESSTAR Tech            | 20        | 0.27%   |
| Timi                    | 18        | 0.24%   |
| AZW                     | 15        | 0.2%    |
| TUXEDO                  | 14        | 0.19%   |
| PC Specialist           | 14        | 0.19%   |
| Supermicro              | 13        | 0.17%   |
| Valve                   | 12        | 0.16%   |
| TrekStor                | 9         | 0.12%   |
| SANTECH                 | 9         | 0.12%   |
| Jumper                  | 9         | 0.12%   |
| Google                  | 9         | 0.12%   |
| eMachines               | 9         | 0.12%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                  | Computers | Percent |
|---------------------------------------|-----------|---------|
| Unknown                               | 98        | 1.32%   |
| ASUS All Series                       | 77        | 1.03%   |
| HP Pavilion dv6                       | 55        | 0.74%   |
| HP Notebook                           | 42        | 0.56%   |
| HP Pavilion 15                        | 28        | 0.38%   |
| HP Pavilion g6                        | 23        | 0.31%   |
| HP 255 G8 Notebook PC                 | 23        | 0.31%   |
| HUAWEI NBLK-WAX9X                     | 20        | 0.27%   |
| MSI MS-7C37                           | 17        | 0.23%   |
| Mediacom SmartBook 14 FullHD - SB14UC | 17        | 0.23%   |
| ASUS PRIME A320M-K                    | 17        | 0.23%   |
| HP 15                                 | 16        | 0.21%   |
| Dell OptiPlex 7010                    | 16        | 0.21%   |
| MSI MS-7C56                           | 14        | 0.19%   |
| HP Pavilion x2 Detachable             | 14        | 0.19%   |
| Dell XPS 15 7590                      | 14        | 0.19%   |
| MSI MS-7B86                           | 13        | 0.17%   |
| HP ENVY 15                            | 13        | 0.17%   |
| HP 255 G7 Notebook PC                 | 13        | 0.17%   |
| Valve Jupiter                         | 12        | 0.16%   |
| Lenovo IdeaPad 3 15ADA05 81W1         | 12        | 0.16%   |
| HUAWEI KLVL-WXX9                      | 12        | 0.16%   |
| HP G62                                | 12        | 0.16%   |
| HP 250 G6 Notebook PC                 | 12        | 0.16%   |
| ASUS T101HA                           | 12        | 0.16%   |
| Apple MacBook4,1                      | 12        | 0.16%   |
| RPi Raspberry Pi                      | 11        | 0.15%   |
| Lenovo IdeaPad 330S-15IKB 81F5        | 11        | 0.15%   |
| HP 255 G6 Notebook PC                 | 11        | 0.15%   |
| Gigabyte B450M DS3H                   | 11        | 0.15%   |
| Dell XPS 15 9570                      | 11        | 0.15%   |
| AMI Intel                             | 11        | 0.15%   |
| Acer Aspire 5750G                     | 11        | 0.15%   |
| MSI MS-7B79                           | 10        | 0.13%   |
| HP Pavilion dv7                       | 10        | 0.13%   |
| HP Laptop 15s-eq2xxx                  | 10        | 0.13%   |
| HP Compaq Elite 8300 SFF              | 10        | 0.13%   |
| Dell XPS 15 9560                      | 10        | 0.13%   |
| Acer Aspire 5920G                     | 10        | 0.13%   |
| Microtech ebookPro                    | 9         | 0.12%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                  | Computers | Percent |
|-----------------------|-----------|---------|
| Acer Aspire           | 381       | 5.12%   |
| Lenovo ThinkPad       | 343       | 4.61%   |
| HP Pavilion           | 285       | 3.83%   |
| Lenovo IdeaPad        | 176       | 2.36%   |
| Dell Latitude         | 176       | 2.36%   |
| HP Compaq             | 158       | 2.12%   |
| ASUS PRIME            | 128       | 1.72%   |
| HP EliteBook          | 120       | 1.61%   |
| Dell XPS              | 111       | 1.49%   |
| ASUS VivoBook         | 102       | 1.37%   |
| Dell Inspiron         | 98        | 1.32%   |
| Unknown               | 98        | 1.32%   |
| HP Laptop             | 94        | 1.26%   |
| Toshiba Satellite     | 91        | 1.22%   |
| HP ProBook            | 90        | 1.21%   |
| Dell OptiPlex         | 82        | 1.1%    |
| ASUS ROG              | 81        | 1.09%   |
| ASUS All              | 77        | 1.03%   |
| HP 255                | 65        | 0.87%   |
| ASUS TUF              | 59        | 0.79%   |
| HP 250                | 58        | 0.78%   |
| Dell Precision        | 57        | 0.77%   |
| Lenovo ThinkCentre    | 55        | 0.74%   |
| HP Notebook           | 42        | 0.56%   |
| Dell Vostro           | 41        | 0.55%   |
| Fujitsu LIFEBOOK      | 38        | 0.51%   |
| RPi Raspberry         | 37        | 0.5%    |
| HP ENVY               | 37        | 0.5%    |
| Acer TravelMate       | 37        | 0.5%    |
| Acer Swift            | 37        | 0.5%    |
| Acer Extensa          | 37        | 0.5%    |
| Fujitsu ESPRIMO       | 36        | 0.48%   |
| Acer Veriton          | 36        | 0.48%   |
| Lenovo Yoga           | 33        | 0.44%   |
| Lenovo ThinkBook      | 30        | 0.4%    |
| HP ProDesk            | 26        | 0.35%   |
| Packard Bell EasyNote | 24        | 0.32%   |
| Microsoft Surface     | 24        | 0.32%   |
| ASUS P8H61-M          | 23        | 0.31%   |
| Mediacom SmartBook    | 21        | 0.28%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year    | Computers | Percent |
|---------|-----------|---------|
| 2018    | 637       | 8.55%   |
| 2020    | 610       | 8.19%   |
| 2019    | 601       | 8.07%   |
| 2013    | 505       | 6.78%   |
| 2021    | 497       | 6.67%   |
| 2017    | 478       | 6.42%   |
| 2012    | 478       | 6.42%   |
| 2011    | 446       | 5.99%   |
| 2008    | 431       | 5.79%   |
| 2014    | 420       | 5.64%   |
| 2009    | 407       | 5.47%   |
| 2016    | 404       | 5.43%   |
| 2010    | 400       | 5.37%   |
| 2015    | 396       | 5.32%   |
| 2007    | 254       | 3.41%   |
| 2022    | 180       | 2.42%   |
| 2006    | 139       | 1.87%   |
| 2005    | 68        | 0.91%   |
| Unknown | 48        | 0.64%   |
| 2023    | 24        | 0.32%   |
| 2004    | 14        | 0.19%   |
| 2003    | 6         | 0.08%   |
| 2001    | 2         | 0.03%   |
| 2002    | 1         | 0.01%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| Notebook       | 4202      | 56.43%  |
| Desktop        | 2711      | 36.41%  |
| Convertible    | 159       | 2.14%   |
| Mini pc        | 109       | 1.46%   |
| All in one     | 104       | 1.4%    |
| Tablet         | 90        | 1.21%   |
| System on chip | 49        | 0.66%   |
| Server         | 21        | 0.28%   |
| Phone          | 1         | 0.01%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 6963      | 92.67%  |
| Enabled  | 551       | 7.33%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7429      | 99.77%  |
| Yes  | 17        | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 4.01-8.0        | 1801      | 23.83%  |
| 3.01-4.0        | 1691      | 22.37%  |
| 16.01-24.0      | 1381      | 18.27%  |
| 8.01-16.0       | 1312      | 17.36%  |
| 32.01-64.0      | 518       | 6.85%   |
| 1.01-2.0        | 437       | 5.78%   |
| 2.01-3.0        | 135       | 1.79%   |
| 64.01-256.0     | 100       | 1.32%   |
| 24.01-32.0      | 88        | 1.16%   |
| 0.51-1.0        | 82        | 1.08%   |
| 0.01-0.5        | 8         | 0.11%   |
| More than 256.0 | 6         | 0.08%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 3214      | 38.7%   |
| 2.01-3.0   | 2024      | 24.37%  |
| 4.01-8.0   | 1017      | 12.25%  |
| 3.01-4.0   | 984       | 11.85%  |
| 0.51-1.0   | 679       | 8.18%   |
| 8.01-16.0  | 243       | 2.93%   |
| 0.01-0.5   | 105       | 1.26%   |
| 16.01-24.0 | 25        | 0.3%    |
| 24.01-32.0 | 8         | 0.1%    |
| Unknown    | 3         | 0.04%   |
| 32.01-64.0 | 2         | 0.02%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives  | Computers | Percent |
|---------|-----------|---------|
| 1       | 4654      | 60.67%  |
| 2       | 1904      | 24.82%  |
| 3       | 588       | 7.67%   |
| 4       | 245       | 3.19%   |
| 5       | 111       | 1.45%   |
| 0       | 70        | 0.91%   |
| 6       | 54        | 0.7%    |
| 7       | 19        | 0.25%   |
| 8       | 13        | 0.17%   |
| 10      | 4         | 0.05%   |
| 12      | 3         | 0.04%   |
| 9       | 3         | 0.04%   |
| Unknown | 2         | 0.03%   |
| 13      | 1         | 0.01%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 4033      | 53.76%  |
| Yes       | 3469      | 46.24%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 6338      | 84.83%  |
| No        | 1133      | 15.17%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 5739      | 76.62%  |
| No        | 1751      | 23.38%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 4274      | 56.5%   |
| No        | 3291      | 43.5%   |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Italy   | 7446      | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City                | Computers | Percent |
|---------------------|-----------|---------|
| Milan               | 1046      | 12.27%  |
| Rome                | 866       | 10.16%  |
| Turin               | 271       | 3.18%   |
| Bologna             | 177       | 2.08%   |
| Florence            | 160       | 1.88%   |
| Naples              | 153       | 1.8%    |
| Genoa               | 121       | 1.42%   |
| Rho                 | 116       | 1.36%   |
| Padova              | 102       | 1.2%    |
| Milano              | 94        | 1.1%    |
| Palermo             | 93        | 1.09%   |
| Verona              | 80        | 0.94%   |
| Catania             | 70        | 0.82%   |
| Bari                | 67        | 0.79%   |
| Brescia             | 62        | 0.73%   |
| Trieste             | 56        | 0.66%   |
| Venice              | 52        | 0.61%   |
| Parma               | 51        | 0.6%    |
| Bergamo             | 46        | 0.54%   |
| Pisa                | 45        | 0.53%   |
| Reggio Emilia       | 40        | 0.47%   |
| Modena              | 40        | 0.47%   |
| Pescara             | 39        | 0.46%   |
| Cagliari            | 39        | 0.46%   |
| Monza               | 38        | 0.45%   |
| Casalecchio di Reno | 36        | 0.42%   |
| Trento              | 34        | 0.4%    |
| Perugia             | 34        | 0.4%    |
| Sesto San Giovanni  | 33        | 0.39%   |
| Bolzano             | 30        | 0.35%   |
| Taranto             | 29        | 0.34%   |
| Vicenza             | 28        | 0.33%   |
| Udine               | 26        | 0.31%   |
| Seregno             | 25        | 0.29%   |
| Salerno             | 24        | 0.28%   |
| Mestre              | 24        | 0.28%   |
| Como                | 24        | 0.28%   |
| Reggio Calabria     | 23        | 0.27%   |
| Legnano             | 21        | 0.25%   |
| Forlì              | 21        | 0.25%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 1750      | 2550   | 16.21%  |
| Seagate                     | 1507      | 2308   | 13.96%  |
| WDC                         | 1444      | 2213   | 13.38%  |
| Kingston                    | 699       | 922    | 6.48%   |
| Crucial                     | 631       | 801    | 5.85%   |
| Toshiba                     | 625       | 882    | 5.79%   |
| SanDisk                     | 546       | 748    | 5.06%   |
| Unknown                     | 521       | 713    | 4.83%   |
| Hitachi                     | 407       | 522    | 3.77%   |
| SK hynix                    | 244       | 298    | 2.26%   |
| HGST                        | 221       | 300    | 2.05%   |
| Maxtor                      | 190       | 261    | 1.76%   |
| Micron Technology           | 174       | 219    | 1.61%   |
| Intel                       | 168       | 226    | 1.56%   |
| Phison                      | 109       | 153    | 1.01%   |
| China                       | 93        | 106    | 0.86%   |
| KIOXIA                      | 78        | 106    | 0.72%   |
| SPCC                        | 74        | 92     | 0.69%   |
| Apple                       | 59        | 74     | 0.55%   |
| Intenso                     | 56        | 70     | 0.52%   |
| Fujitsu                     | 55        | 64     | 0.51%   |
| Micron/Crucial Technology   | 54        | 72     | 0.5%    |
| Transcend                   | 48        | 62     | 0.44%   |
| Phison Electronics          | 46        | 60     | 0.43%   |
| A-DATA Technology           | 46        | 61     | 0.43%   |
| PNY                         | 38        | 47     | 0.35%   |
| Corsair                     | 38        | 55     | 0.35%   |
| JMicron Technology          | 37        | 41     | 0.34%   |
| LITEON                      | 35        | 44     | 0.32%   |
| KingDian                    | 35        | 41     | 0.32%   |
| Kingston Technology Company | 33        | 41     | 0.31%   |
| Unknown                     | 32        | 41     | 0.3%    |
| Silicon Motion              | 28        | 42     | 0.26%   |
| OCZ                         | 27        | 32     | 0.25%   |
| Netac                       | 25        | 27     | 0.23%   |
| SABRENT                     | 24        | 25     | 0.22%   |
| Patriot                     | 24        | 34     | 0.22%   |
| Teclast                     | 23        | 29     | 0.21%   |
| Drevo                       | 23        | 25     | 0.21%   |
| ASMT                        | 19        | 22     | 0.18%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Kingston SA400S37240G 240GB SSD                     | 191       | 1.62%   |
| Samsung SSD 860 EVO 500GB                           | 151       | 1.28%   |
| Crucial CT500MX500SSD1 500GB                        | 150       | 1.27%   |
| Samsung SSD 850 EVO 250GB                           | 130       | 1.1%    |
| Seagate ST500DM002-1BD142 500GB                     | 113       | 0.96%   |
| Unknown MMC Card  32GB                              | 94        | 0.8%    |
| Kingston SA400S37480G 480GB SSD                     | 92        | 0.78%   |
| Samsung SSD 850 EVO 500GB                           | 91        | 0.77%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 500GB | 76        | 0.64%   |
| Crucial CT240BX500SSD1 240GB                        | 76        | 0.64%   |
| Unknown MMC Card  64GB                              | 75        | 0.63%   |
| Seagate ST1000DM010-2EP102 1TB                      | 75        | 0.63%   |
| Toshiba MQ01ABF050 500GB                            | 71        | 0.6%    |
| Samsung SSD 860 EVO 250GB                           | 71        | 0.6%    |
| Crucial CT1000MX500SSD1 1TB                         | 66        | 0.56%   |
| Toshiba DT01ACA100 1TB                              | 64        | 0.54%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 63        | 0.53%   |
| Kingston SA400S37120G 120GB SSD                     | 62        | 0.52%   |
| Crucial CT480BX500SSD1 480GB                        | 60        | 0.51%   |
| HGST HTS545050A7E680 500GB                          | 56        | 0.47%   |
| Seagate ST2000DM008-2FR102 2TB                      | 55        | 0.47%   |
| Seagate ST500LT012-1DG142 500GB                     | 54        | 0.46%   |
| Seagate ST1000LM035-1RK172 1TB                      | 53        | 0.45%   |
| Seagate ST3500418AS 500GB                           | 52        | 0.44%   |
| HGST HTS721010A9E630 1TB                            | 52        | 0.44%   |
| Kingston SV300S37A120G 120GB SSD                    | 50        | 0.42%   |
| Unknown SD/MMC/MS PRO 1GB                           | 49        | 0.41%   |
| Seagate M3 Portable 1TB                             | 48        | 0.41%   |
| SanDisk SSD PLUS 240GB                              | 45        | 0.38%   |
| Samsung SSD 860 EVO 1TB                             | 44        | 0.37%   |
| Samsung SSD 840 EVO 250GB                           | 43        | 0.36%   |
| Samsung NVMe SSD Drive 512GB                        | 43        | 0.36%   |
| Unknown MMC Card  128GB                             | 42        | 0.36%   |
| Seagate ST9500325AS 500GB                           | 42        | 0.36%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 41        | 0.35%   |
| Seagate Expansion 2TB                               | 41        | 0.35%   |
| Phison Sabrent 256GB                                | 41        | 0.35%   |
| Seagate ST1000DM003-1CH162 1TB                      | 40        | 0.34%   |
| Toshiba MQ01ABD100 1TB                              | 39        | 0.33%   |
| Seagate ST31000528AS 1TB                            | 39        | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 1459      | 2222   | 33.86%  |
| WDC                 | 1200      | 1858   | 27.85%  |
| Toshiba             | 460       | 639    | 10.68%  |
| Hitachi             | 407       | 522    | 9.45%   |
| HGST                | 220       | 299    | 5.11%   |
| Maxtor              | 188       | 259    | 4.36%   |
| Samsung Electronics | 145       | 181    | 3.37%   |
| Unknown             | 62        | 73     | 1.44%   |
| Fujitsu             | 55        | 64     | 1.28%   |
| SABRENT             | 23        | 24     | 0.53%   |
| Apple               | 21        | 24     | 0.49%   |
| External            | 12        | 13     | 0.28%   |
| ASMT                | 8         | 8      | 0.19%   |
| USB3.0              | 5         | 6      | 0.12%   |
| HGST HTS            | 5         | 5      | 0.12%   |
| Inateck             | 4         | 4      | 0.09%   |
| IBM/Hitachi         | 4         | 5      | 0.09%   |
| SSK                 | 3         | 3      | 0.07%   |
| Hewlett-Packard     | 3         | 4      | 0.07%   |
| WD MediaMax         | 2         | 2      | 0.05%   |
| LaCie               | 2         | 3      | 0.05%   |
| Intenso             | 2         | 4      | 0.05%   |
| ASMT109x            | 2         | 2      | 0.05%   |
| USB 3.0             | 1         | 2      | 0.02%   |
| USB                 | 1         | 1      | 0.02%   |
| StoreJet            | 1         | 1      | 0.02%   |
| QUANTUM             | 1         | 1      | 0.02%   |
| Promise             | 1         | 1      | 0.02%   |
| PI-041              | 1         | 1      | 0.02%   |
| MARVELL             | 1         | 2      | 0.02%   |
| Initio              | 1         | 1      | 0.02%   |
| IBM-ESXS            | 1         | 2      | 0.02%   |
| IBM-207x            | 1         | 4      | 0.02%   |
| HPE                 | 1         | 1      | 0.02%   |
| Generic-            | 1         | 1      | 0.02%   |
| FC-1307             | 1         | 2      | 0.02%   |
| DAS                 | 1         | 4      | 0.02%   |
| Config              | 1         | 1      | 0.02%   |
| China               | 1         | 1      | 0.02%   |
| ASMedia             | 1         | 1      | 0.02%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 969       | 1369   | 26.32%  |
| Kingston            | 590       | 783    | 16.03%  |
| Crucial             | 567       | 721    | 15.4%   |
| SanDisk             | 323       | 449    | 8.77%   |
| WDC                 | 121       | 165    | 3.29%   |
| China               | 91        | 104    | 2.47%   |
| Micron Technology   | 76        | 94     | 2.06%   |
| SPCC                | 63        | 78     | 1.71%   |
| Toshiba             | 56        | 79     | 1.52%   |
| SK hynix            | 53        | 61     | 1.44%   |
| Intenso             | 49        | 59     | 1.33%   |
| Transcend           | 45        | 59     | 1.22%   |
| Intel               | 39        | 54     | 1.06%   |
| A-DATA Technology   | 37        | 50     | 1.01%   |
| PNY                 | 35        | 43     | 0.95%   |
| KingDian            | 34        | 40     | 0.92%   |
| Apple               | 33        | 36     | 0.9%    |
| Corsair             | 32        | 47     | 0.87%   |
| LITEON              | 31        | 35     | 0.84%   |
| OCZ                 | 26        | 31     | 0.71%   |
| Patriot             | 24        | 34     | 0.65%   |
| Teclast             | 23        | 29     | 0.62%   |
| Netac               | 21        | 22     | 0.57%   |
| Drevo               | 21        | 22     | 0.57%   |
| JMicron Technology  | 18        | 20     | 0.49%   |
| LITEONIT            | 16        | 27     | 0.43%   |
| GOODRAM             | 16        | 24     | 0.43%   |
| Dogfish             | 16        | 20     | 0.43%   |
| Unknown             | 14        | 20     | 0.38%   |
| TCSUNBOW            | 13        | 14     | 0.35%   |
| Team                | 12        | 23     | 0.33%   |
| Verbatim            | 11        | 16     | 0.3%    |
| FORESEE             | 11        | 13     | 0.3%    |
| Unknown             | 10        | 11     | 0.27%   |
| BAITITON            | 10        | 14     | 0.27%   |
| ASMT                | 10        | 13     | 0.27%   |
| TO Exter            | 9         | 9      | 0.24%   |
| Lexar               | 9         | 12     | 0.24%   |
| KingSpec            | 9         | 11     | 0.24%   |
| Microtech           | 8         | 18     | 0.22%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 3628      | 6251   | 37.65%  |
| SSD     | 3276      | 4892   | 33.99%  |
| NVMe    | 2075      | 3023   | 21.53%  |
| MMC     | 473       | 670    | 4.91%   |
| Unknown | 185       | 234    | 1.92%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 5630      | 10821  | 65.46%  |
| NVMe | 2073      | 3011   | 24.1%   |
| MMC  | 473       | 670    | 5.5%    |
| SAS  | 425       | 568    | 4.94%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB      | Computers | Drives | Percent |
|-----------------|-----------|--------|---------|
| 0.01-0.5        | 4616      | 7346   | 65.64%  |
| 0.51-1.0        | 1719      | 2586   | 24.45%  |
| 1.01-2.0        | 418       | 703    | 5.94%   |
| 3.01-4.0        | 109       | 194    | 1.55%   |
| 2.01-3.0        | 102       | 174    | 1.45%   |
| 4.01-10.0       | 60        | 124    | 0.85%   |
| 10.01-20.0      | 7         | 15     | 0.1%    |
| More than 100.0 | 1         | 1      | 0.01%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 2149      | 26.96%  |
| 251-500        | 1739      | 21.81%  |
| 501-1000       | 953       | 11.95%  |
| 1-20           | 803       | 10.07%  |
| 51-100         | 627       | 7.87%   |
| 1001-2000      | 568       | 7.12%   |
| 21-50          | 380       | 4.77%   |
| More than 3000 | 303       | 3.8%    |
| 2001-3000      | 231       | 2.9%    |
| Unknown        | 218       | 2.73%   |
| 0              | 1         | 0.01%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 3396      | 41.12%  |
| 21-50          | 1261      | 15.27%  |
| 101-250        | 1002      | 12.13%  |
| 51-100         | 917       | 11.1%   |
| 251-500        | 612       | 7.41%   |
| 501-1000       | 428       | 5.18%   |
| 1001-2000      | 228       | 2.76%   |
| Unknown        | 218       | 2.64%   |
| More than 3000 | 113       | 1.37%   |
| 2001-3000      | 83        | 1%      |
| 0              | 1         | 0.01%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                 | Computers | Drives | Percent |
|---------------------------------------|-----------|--------|---------|
| Seagate ST500DM002-1BD142 500GB       | 21        | 24     | 2.98%   |
| HGST HTS545050A7E680 500GB            | 17        | 21     | 2.41%   |
| Seagate ST3500418AS 500GB             | 12        | 16     | 1.7%    |
| Seagate ST9500325AS 500GB             | 10        | 10     | 1.42%   |
| Seagate ST1000LM035-1RK172 1TB        | 8         | 10     | 1.13%   |
| Maxtor STM3250310AS 250GB             | 8         | 9      | 1.13%   |
| Hitachi HTS725050A9A364 500GB         | 8         | 9      | 1.13%   |
| Seagate ST1000LM024 HN-M101MBB 1TB    | 7         | 9      | 0.99%   |
| Toshiba MQ01ABF050 500GB              | 6         | 6      | 0.85%   |
| Seagate ST500LT012-1DG142 500GB       | 6         | 6      | 0.85%   |
| SanDisk SSD PLUS 480GB                | 6         | 7      | 0.85%   |
| WDC WD40EFRX-68N32N0 4TB              | 5         | 6      | 0.71%   |
| WDC WD3200BEVT-60A23T0 320GB          | 5         | 5      | 0.71%   |
| Seagate ST500LM012 HN-M500MBB 500GB   | 5         | 7      | 0.71%   |
| Maxtor STM3320820AS 320GB             | 5         | 5      | 0.71%   |
| Kingston SA400S37240G 240GB SSD       | 5         | 5      | 0.71%   |
| Hitachi HTS545050A7E380 500GB         | 5         | 5      | 0.71%   |
| HGST HTS725050A7E630 500GB            | 5         | 6      | 0.71%   |
| HGST HTS721010A9E630 1TB              | 5         | 5      | 0.71%   |
| WDC WD5000LPCX-24C6HT0 500GB          | 4         | 4      | 0.57%   |
| Unknown MM0500EANCR 500GB             | 4         | 9      | 0.57%   |
| Toshiba MK5065GSX 500GB               | 4         | 4      | 0.57%   |
| Seagate ST9320325AS 320GB             | 4         | 4      | 0.57%   |
| Seagate ST31500341AS 1TB              | 4         | 4      | 0.57%   |
| Seagate ST31000528AS 1TB              | 4         | 7      | 0.57%   |
| Samsung Electronics HD103UJ 1TB       | 4         | 4      | 0.57%   |
| Hitachi HTS547550A9E384 500GB         | 4         | 4      | 0.57%   |
| Hitachi HTS543232A7A384 320GB         | 4         | 5      | 0.57%   |
| WDC WD20EFRX-68EUZN0 2TB              | 3         | 4      | 0.43%   |
| WDC WD10EZEX-60WN4A0 1TB              | 3         | 4      | 0.43%   |
| WDC WD10EZEX-60M2NA0 1TB              | 3         | 3      | 0.43%   |
| Toshiba MQ01ABD100 1TB                | 3         | 4      | 0.43%   |
| Toshiba DT01ACA100 1TB                | 3         | 3      | 0.43%   |
| Toshiba DT01ACA050 500GB              | 3         | 3      | 0.43%   |
| SK hynix HFS512G39TND-N210A 512GB SSD | 3         | 3      | 0.43%   |
| Seagate ST500LT012-9WS142 500GB       | 3         | 3      | 0.43%   |
| Seagate ST3500413AS 500GB             | 3         | 5      | 0.43%   |
| Seagate ST3500320AS 500GB             | 3         | 3      | 0.43%   |
| Seagate ST3250310AS 250GB             | 3         | 3      | 0.43%   |
| Seagate ST2000DM001-1ER164 2TB        | 3         | 7      | 0.43%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Seagate                     | 181       | 235    | 26.42%  |
| WDC                         | 133       | 164    | 19.42%  |
| Hitachi                     | 79        | 85     | 11.53%  |
| Toshiba                     | 46        | 47     | 6.72%   |
| Samsung Electronics         | 42        | 46     | 6.13%   |
| Maxtor                      | 39        | 48     | 5.69%   |
| HGST                        | 37        | 46     | 5.4%    |
| Crucial                     | 20        | 20     | 2.92%   |
| Kingston                    | 17        | 17     | 2.48%   |
| SK hynix                    | 13        | 15     | 1.9%    |
| SanDisk                     | 11        | 12     | 1.61%   |
| Micron Technology           | 10        | 10     | 1.46%   |
| Intel                       | 7         | 12     | 1.02%   |
| Fujitsu                     | 6         | 6      | 0.88%   |
| Unknown                     | 5         | 10     | 0.73%   |
| OCZ                         | 3         | 3      | 0.44%   |
| Drevo                       | 3         | 3      | 0.44%   |
| ASMT                        | 3         | 3      | 0.44%   |
| TCSUNBOW                    | 2         | 2      | 0.29%   |
| Intenso                     | 2         | 3      | 0.29%   |
| Corsair                     | 2         | 3      | 0.29%   |
| BAITITON                    | 2         | 4      | 0.29%   |
| Apple                       | 2         | 2      | 0.29%   |
| A-DATA Technology           | 2         | 2      | 0.29%   |
| Yangtze Memory Technologies | 1         | 1      | 0.15%   |
| WINTEC                      | 1         | 1      | 0.15%   |
| WDC WDS2                    | 1         | 1      | 0.15%   |
| WD MediaMax                 | 1         | 1      | 0.15%   |
| USB3.0                      | 1         | 1      | 0.15%   |
| Transcend                   | 1         | 2      | 0.15%   |
| Teclast                     | 1         | 1      | 0.15%   |
| SSSTC                       | 1         | 1      | 0.15%   |
| QUANTUM                     | 1         | 1      | 0.15%   |
| NGFF                        | 1         | 1      | 0.15%   |
| LITEONIT                    | 1         | 1      | 0.15%   |
| LITEON                      | 1         | 1      | 0.15%   |
| KingSpec                    | 1         | 1      | 0.15%   |
| KingDian                    | 1         | 1      | 0.15%   |
| GSemi                       | 1         | 1      | 0.15%   |
| Emtec                       | 1         | 1      | 0.15%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 181       | 235    | 32.91%  |
| WDC                 | 129       | 157    | 23.45%  |
| Hitachi             | 79        | 85     | 14.36%  |
| Toshiba             | 44        | 45     | 8%      |
| Maxtor              | 39        | 48     | 7.09%   |
| HGST                | 37        | 46     | 6.73%   |
| Samsung Electronics | 23        | 25     | 4.18%   |
| Fujitsu             | 6         | 6      | 1.09%   |
| Unknown             | 5         | 10     | 0.91%   |
| ASMT                | 2         | 2      | 0.36%   |
| Apple               | 2         | 2      | 0.36%   |
| WD MediaMax         | 1         | 1      | 0.18%   |
| USB3.0              | 1         | 1      | 0.18%   |
| QUANTUM             | 1         | 1      | 0.18%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 519       | 664    | 79.24%  |
| SSD  | 118       | 131    | 18.02%  |
| NVMe | 18        | 23     | 2.75%   |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                                            | Computers | Drives | Percent |
|--------------------------------------------------|-----------|--------|---------|
| Seagate ST9500420AS 500GB                        | 2         | 4      | 13.33%  |
| Seagate ST500DM002-1BD142 500GB                  | 2         | 3      | 13.33%  |
| WDC WD5000BEVT-26A0RT0 500GB                     | 1         | 1      | 6.67%   |
| WDC WD5000BEVT-22A0RT0 500GB                     | 1         | 1      | 6.67%   |
| WDC WD10JPVX-60JC3T0 1TB                         | 1         | 1      | 6.67%   |
| WDC PC SN520 SDAPNUW-256G-1102 256GB             | 1         | 1      | 6.67%   |
| Toshiba MK3265GSX 320GB                          | 1         | 1      | 6.67%   |
| Seagate STM3250318AS 250GB                       | 1         | 1      | 6.67%   |
| Seagate ST2000LX001-1RG174 2TB                   | 1         | 1      | 6.67%   |
| Samsung Electronics MZNTY128HDHP-00000 128GB SSD | 1         | 1      | 6.67%   |
| Hitachi HTS725050A7E630 500GB                    | 1         | 1      | 6.67%   |
| Hitachi HTS545050A7E380 500GB                    | 1         | 1      | 6.67%   |
| Hitachi HTS543216L9A300 160GB                    | 1         | 1      | 6.67%   |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 6         | 9      | 40%     |
| WDC                 | 4         | 4      | 26.67%  |
| Hitachi             | 3         | 3      | 20%     |
| Toshiba             | 1         | 1      | 6.67%   |
| Samsung Electronics | 1         | 1      | 6.67%   |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 4425      | 8757   | 54.43%  |
| Works    | 3054      | 5477   | 37.56%  |
| Malfunc  | 636       | 818    | 7.82%   |
| Failed   | 15        | 18     | 0.18%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Intel                            | 4990      | 54.46%  |
| AMD                              | 1252      | 13.66%  |
| Samsung Electronics              | 762       | 8.32%   |
| SanDisk                          | 320       | 3.49%   |
| Nvidia                           | 187       | 2.04%   |
| SK hynix                         | 180       | 1.96%   |
| Phison Electronics               | 163       | 1.78%   |
| ASMedia Technology               | 145       | 1.58%   |
| Kingston Technology Company      | 144       | 1.57%   |
| JMicron Technology               | 137       | 1.5%    |
| Marvell Technology Group         | 130       | 1.42%   |
| Micron/Crucial Technology        | 117       | 1.28%   |
| Toshiba America Info Systems     | 114       | 1.24%   |
| Micron Technology                | 103       | 1.12%   |
| KIOXIA                           | 87        | 0.95%   |
| VIA Technologies                 | 59        | 0.64%   |
| Silicon Motion                   | 39        | 0.43%   |
| Silicon Integrated Systems [SiS] | 35        | 0.38%   |
| ADATA Technology                 | 20        | 0.22%   |
| MAXIO Technology (Hangzhou)      | 19        | 0.21%   |
| Union Memory (Shenzhen)          | 17        | 0.19%   |
| Adaptec                          | 16        | 0.17%   |
| Solid State Storage Technology   | 15        | 0.16%   |
| Silicon Image                    | 14        | 0.15%   |
| LSI Logic / Symbios Logic        | 11        | 0.12%   |
| Broadcom / LSI                   | 10        | 0.11%   |
| Realtek Semiconductor            | 9         | 0.1%    |
| Apple                            | 9         | 0.1%    |
| Shenzhen Longsys Electronics     | 7         | 0.08%   |
| Lite-On Technology               | 7         | 0.08%   |
| Lenovo                           | 7         | 0.08%   |
| Seagate Technology               | 6         | 0.07%   |
| Yangtze Memory Technologies      | 4         | 0.04%   |
| Hewlett-Packard                  | 4         | 0.04%   |
| Promise Technology               | 3         | 0.03%   |
| Integrated Technology Express    | 3         | 0.03%   |
| HighPoint Technologies           | 3         | 0.03%   |
| Broadcom                         | 3         | 0.03%   |
| ULi Electronics                  | 2         | 0.02%   |
| INNOGRIT                         | 2         | 0.02%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 834       | 7.8%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 389       | 3.64%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 375       | 3.51%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 306       | 2.86%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 280       | 2.62%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 254       | 2.37%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 223       | 2.09%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]          | 207       | 1.94%   |
| Samsung NVMe SSD Controller 980                                                | 190       | 1.78%   |
| Intel 82801G (ICH7 Family) IDE Controller                                      | 176       | 1.65%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 173       | 1.62%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 162       | 1.51%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                              | 160       | 1.5%    |
| AMD 400 Series Chipset SATA Controller                                         | 160       | 1.5%    |
| Intel Volume Management Device NVMe RAID Controller                            | 156       | 1.46%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                         | 153       | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 144       | 1.35%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 144       | 1.35%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 135       | 1.26%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 135       | 1.26%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                               | 134       | 1.25%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 117       | 1.09%   |
| Intel SATA Controller [RAID mode]                                              | 115       | 1.08%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                  | 115       | 1.08%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                             | 114       | 1.07%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 114       | 1.07%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                 | 113       | 1.06%   |
| Intel Comet Lake SATA AHCI Controller                                          | 106       | 0.99%   |
| Phison E12 NVMe Controller                                                     | 100       | 0.94%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                 | 95        | 0.89%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 93        | 0.87%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 91        | 0.85%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 86        | 0.8%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                               | 83        | 0.78%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 82        | 0.77%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 80        | 0.75%   |
| KIOXIA NVMe SSD Controller BG4 (DRAM-less)                                     | 76        | 0.71%   |
| AMD 500 Series Chipset SATA Controller                                         | 75        | 0.7%    |
| JMicron JMB363 SATA/IDE Controller                                             | 73        | 0.68%   |
| Intel SSD 660P Series                                                          | 69        | 0.65%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 5164      | 55.77%  |
| NVMe | 2087      | 22.54%  |
| IDE  | 1344      | 14.52%  |
| RAID | 642       | 6.93%   |
| SAS  | 11        | 0.12%   |
| SCSI | 11        | 0.12%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 5747      | 77.18%  |
| AMD                      | 1642      | 22.05%  |
| ARM                      | 51        | 0.68%   |
| CentaurHauls             | 4         | 0.05%   |
| PowerNV C1P9S01 REV 1.01 | 1         | 0.01%   |
| Unknown                  | 1         | 0.01%   |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-8550U CPU @ 1.80GHz             | 97        | 1.3%    |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 84        | 1.13%   |
| Intel Core i5-8250U CPU @ 1.60GHz             | 77        | 1.03%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 75        | 1%      |
| Intel Atom x5-Z8350 CPU @ 1.44GHz             | 73        | 0.98%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 59        | 0.79%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 57        | 0.76%   |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 57        | 0.76%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 56        | 0.75%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 53        | 0.71%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 52        | 0.7%    |
| AMD Ryzen 5 3600 6-Core Processor             | 51        | 0.68%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 49        | 0.66%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 49        | 0.66%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 47        | 0.63%   |
| Intel Core i7-6500U CPU @ 2.50GHz             | 46        | 0.62%   |
| Intel Atom x5-Z8300 CPU @ 1.44GHz             | 45        | 0.6%    |
| AMD Ryzen 7 5700U with Radeon Graphics        | 43        | 0.58%   |
| Intel Core i5-3470 CPU @ 3.20GHz              | 42        | 0.56%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 41        | 0.55%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 39        | 0.52%   |
| Intel Core i7-2670QM CPU @ 2.20GHz            | 38        | 0.51%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 38        | 0.51%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 37        | 0.5%    |
| Intel Core 2 Quad CPU Q6600 @ 2.40GHz         | 37        | 0.5%    |
| AMD Ryzen 5 5500U with Radeon Graphics        | 36        | 0.48%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 35        | 0.47%   |
| ARM Processor                                 | 34        | 0.46%   |
| Intel Core i5-3320M CPU @ 2.60GHz             | 33        | 0.44%   |
| Intel Core i5-2400 CPU @ 3.10GHz              | 33        | 0.44%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 33        | 0.44%   |
| Intel Core i7-3770 CPU @ 3.40GHz              | 31        | 0.42%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 30        | 0.4%    |
| Intel Core i5-2520M CPU @ 2.50GHz             | 30        | 0.4%    |
| Intel Core i5-5200U CPU @ 2.20GHz             | 29        | 0.39%   |
| Intel Core 2 Duo CPU P8600 @ 2.40GHz          | 29        | 0.39%   |
| Intel 11th Gen Core i7-1185G7 @ 3.00GHz       | 29        | 0.39%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 28        | 0.38%   |
| Intel Core i5-6300U CPU @ 2.40GHz             | 28        | 0.38%   |
| Intel Core i5-4210U CPU @ 1.70GHz             | 28        | 0.38%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 1455      | 19.51%  |
| Intel Core i5           | 1421      | 19.05%  |
| Intel Core i3           | 503       | 6.74%   |
| Other                   | 453       | 6.07%   |
| Intel Core 2 Duo        | 423       | 5.67%   |
| Intel Celeron           | 404       | 5.42%   |
| AMD Ryzen 5             | 374       | 5.01%   |
| AMD Ryzen 7             | 301       | 4.04%   |
| Intel Atom              | 267       | 3.58%   |
| Intel Pentium           | 140       | 1.88%   |
| Intel Pentium Dual-Core | 124       | 1.66%   |
| Intel Core 2 Quad       | 108       | 1.45%   |
| Intel Xeon              | 107       | 1.43%   |
| AMD Ryzen 9             | 81        | 1.09%   |
| Intel Core 2            | 75        | 1.01%   |
| AMD Ryzen 3             | 75        | 1.01%   |
| AMD FX                  | 75        | 1.01%   |
| Intel Pentium Dual      | 72        | 0.97%   |
| Intel Pentium 4         | 66        | 0.88%   |
| AMD A8                  | 57        | 0.76%   |
| AMD E1                  | 53        | 0.71%   |
| AMD A10                 | 52        | 0.7%    |
| AMD Athlon 64 X2        | 50        | 0.67%   |
| Intel Core i9           | 49        | 0.66%   |
| AMD A4                  | 47        | 0.63%   |
| AMD A6                  | 46        | 0.62%   |
| Intel Genuine           | 40        | 0.54%   |
| AMD Sempron             | 33        | 0.44%   |
| AMD Phenom II X4        | 32        | 0.43%   |
| AMD E2                  | 26        | 0.35%   |
| Intel Pentium D         | 24        | 0.32%   |
| Intel Pentium Silver    | 22        | 0.29%   |
| AMD Phenom II X6        | 21        | 0.28%   |
| AMD Athlon              | 20        | 0.27%   |
| AMD Ryzen 7 PRO         | 19        | 0.25%   |
| AMD Ryzen 5 PRO         | 19        | 0.25%   |
| AMD Athlon II X2        | 19        | 0.25%   |
| Intel Pentium M         | 16        | 0.21%   |
| AMD Phenom              | 16        | 0.21%   |
| AMD Athlon II X4        | 16        | 0.21%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 3032      | 40.64%  |
| 4       | 2805      | 37.6%   |
| 6       | 600       | 8.04%   |
| 8       | 462       | 6.19%   |
| 1       | 311       | 4.17%   |
| 12      | 80        | 1.07%   |
| 10      | 47        | 0.63%   |
| 14      | 37        | 0.5%    |
| 3       | 36        | 0.48%   |
| 16      | 28        | 0.38%   |
| Unknown | 7         | 0.09%   |
| 24      | 6         | 0.08%   |
| 5       | 3         | 0.04%   |
| 40      | 2         | 0.03%   |
| 28      | 2         | 0.03%   |
| 20      | 2         | 0.03%   |
| 64      | 1         | 0.01%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 1       | 7387      | 99.21%  |
| 2       | 50        | 0.67%   |
| Unknown | 5         | 0.07%   |
| 4       | 3         | 0.04%   |
| 3       | 1         | 0.01%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 4486      | 60.13%  |
| 1       | 2961      | 39.69%  |
| Unknown | 7         | 0.09%   |
| 4       | 5         | 0.07%   |
| 12      | 1         | 0.01%   |
| 8       | 1         | 0.01%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 7239      | 97.06%  |
| 32-bit         | 125       | 1.68%   |
| Unknown        | 92        | 1.23%   |
| 64-bit         | 2         | 0.03%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 1897      | 24.34%  |
| 0x206a7    | 372       | 4.77%   |
| 0x306a9    | 360       | 4.62%   |
| 0x1067a    | 300       | 3.85%   |
| 0x306c3    | 295       | 3.78%   |
| 0x806ea    | 177       | 2.27%   |
| 0x806c1    | 156       | 2%      |
| 0x906ea    | 153       | 1.96%   |
| 0x806ec    | 151       | 1.94%   |
| 0x40651    | 151       | 1.94%   |
| 0x806e9    | 147       | 1.89%   |
| 0x506e3    | 139       | 1.78%   |
| 0x406e3    | 139       | 1.78%   |
| 0x6fd      | 134       | 1.72%   |
| 0x906e9    | 129       | 1.66%   |
| 0x20655    | 115       | 1.48%   |
| 0x08108109 | 109       | 1.4%    |
| 0x10676    | 104       | 1.33%   |
| 0x08701021 | 93        | 1.19%   |
| 0x306d4    | 91        | 1.17%   |
| 0x406c4    | 85        | 1.09%   |
| 0x6fb      | 77        | 0.99%   |
| 0x406c3    | 74        | 0.95%   |
| 0x30678    | 73        | 0.94%   |
| 0x0a50000c | 72        | 0.92%   |
| 0x20652    | 66        | 0.85%   |
| 0x706e5    | 65        | 0.83%   |
| 0x706a1    | 64        | 0.82%   |
| 0x706a8    | 55        | 0.71%   |
| 0x806eb    | 54        | 0.69%   |
| 0x08608103 | 54        | 0.69%   |
| 0x6f6      | 52        | 0.67%   |
| 0x010000c8 | 52        | 0.67%   |
| 0x06006705 | 50        | 0.64%   |
| 0x506c9    | 49        | 0.63%   |
| 0x106e5    | 48        | 0.62%   |
| 0x906ed    | 47        | 0.6%    |
| 0xa0652    | 44        | 0.56%   |
| 0x106ca    | 44        | 0.56%   |
| 0x08600106 | 44        | 0.56%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 1107      | 14.83%  |
| Haswell          | 599       | 8.03%   |
| Penryn           | 519       | 6.95%   |
| SandyBridge      | 482       | 6.46%   |
| IvyBridge        | 464       | 6.22%   |
| Skylake          | 372       | 4.98%   |
| Core             | 358       | 4.8%    |
| Silvermont       | 298       | 3.99%   |
| Zen 2            | 253       | 3.39%   |
| Unknown          | 236       | 3.16%   |
| Westmere         | 232       | 3.11%   |
| TigerLake        | 218       | 2.92%   |
| Zen+             | 214       | 2.87%   |
| Zen 3            | 188       | 2.52%   |
| K10              | 170       | 2.28%   |
| Goldmont plus    | 157       | 2.1%    |
| CometLake        | 145       | 1.94%   |
| Broadwell        | 129       | 1.73%   |
| Zen              | 122       | 1.63%   |
| Excavator        | 119       | 1.59%   |
| K8 Hammer        | 113       | 1.51%   |
| Icelake          | 113       | 1.51%   |
| Bonnell          | 100       | 1.34%   |
| Piledriver       | 99        | 1.33%   |
| NetBurst         | 98        | 1.31%   |
| Nehalem          | 95        | 1.27%   |
| Alderlake Hybrid | 77        | 1.03%   |
| Goldmont         | 70        | 0.94%   |
| P6               | 60        | 0.8%    |
| Jaguar           | 53        | 0.71%   |
| Puma             | 51        | 0.68%   |
| Bobcat           | 39        | 0.52%   |
| K10 Llano        | 35        | 0.47%   |
| Steamroller      | 33        | 0.44%   |
| K8 & K10 hybrid  | 19        | 0.25%   |
| Tremont          | 12        | 0.16%   |
| Bulldozer        | 12        | 0.16%   |
| Gracemont        | 2         | 0.03%   |
| K6               | 1         | 0.01%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor                                       | Computers | Percent |
|----------------------------------------------|-----------|---------|
| Intel                                        | 4184      | 47.93%  |
| Nvidia                                       | 2455      | 28.12%  |
| AMD                                          | 2021      | 23.15%  |
| Silicon Integrated Systems [SiS]             | 22        | 0.25%   |
| Matrox Electronics Systems                   | 17        | 0.19%   |
| VIA Technologies                             | 16        | 0.18%   |
| ASPEED Technology                            | 8         | 0.09%   |
| XGI Technology (eXtreme Graphics Innovation) | 3         | 0.03%   |
| S3 Graphics                                  | 2         | 0.02%   |
| ATI Technologies                             | 2         | 0.02%   |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 334       | 3.68%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 265       | 2.92%   |
| Intel UHD Graphics 620                                                                   | 206       | 2.27%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 200       | 2.2%    |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 196       | 2.16%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 190       | 2.09%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 163       | 1.79%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 157       | 1.73%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 156       | 1.72%   |
| Intel HD Graphics 620                                                                    | 151       | 1.66%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 135       | 1.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 132       | 1.45%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 132       | 1.45%   |
| Intel Core Processor Integrated Graphics Controller                                      | 116       | 1.28%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 114       | 1.26%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller              | 111       | 1.22%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 108       | 1.19%   |
| AMD Renoir                                                                               | 106       | 1.17%   |
| Intel HD Graphics 5500                                                                   | 102       | 1.12%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 100       | 1.1%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 100       | 1.1%    |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                             | 98        | 1.08%   |
| Intel HD Graphics 630                                                                    | 89        | 0.98%   |
| Intel HD Graphics 530                                                                    | 87        | 0.96%   |
| AMD Lucienne                                                                             | 87        | 0.96%   |
| Nvidia GK208B [GeForce GT 710]                                                           | 77        | 0.85%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (secondary)                      | 76        | 0.84%   |
| Intel Mobile GM965/GL960 Integrated Graphics Controller (primary)                        | 76        | 0.84%   |
| AMD Stoney [Radeon R2/R3/R4/R5 Graphics]                                                 | 74        | 0.81%   |
| Intel Mobile 945GM/GMS/GME, 943/940GML Express Integrated Graphics Controller            | 73        | 0.8%    |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 70        | 0.77%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 67        | 0.74%   |
| Nvidia GT218 [GeForce 210]                                                               | 62        | 0.68%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller                         | 62        | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 60        | 0.66%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 60        | 0.66%   |
| Intel HD Graphics 500                                                                    | 59        | 0.65%   |
| AMD Topaz XT [Radeon R7 M260/M265 / M340/M360 / M440/M445 / 530/535 / 620/625 Mobile]    | 59        | 0.65%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]                         | 58        | 0.64%   |
| Intel CometLake-H GT2 [UHD Graphics]                                                     | 56        | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name                    | Computers | Percent |
|-------------------------|-----------|---------|
| 1 x Intel               | 2952      | 39.45%  |
| 1 x AMD                 | 1570      | 20.98%  |
| 1 x Nvidia              | 1392      | 18.6%   |
| Intel + Nvidia          | 953       | 12.74%  |
| Intel + AMD             | 201       | 2.69%   |
| 2 x AMD                 | 158       | 2.11%   |
| AMD + Nvidia            | 90        | 1.2%    |
| Other                   | 58        | 0.78%   |
| 2 x Intel               | 25        | 0.33%   |
| 1 x SiS                 | 22        | 0.29%   |
| 1 x VIA                 | 16        | 0.21%   |
| 2 x Nvidia              | 11        | 0.15%   |
| 1 x Matrox              | 9         | 0.12%   |
| Nvidia + Matrox         | 4         | 0.05%   |
| 1 x ASPEED              | 4         | 0.05%   |
| 1 x XGI                 | 3         | 0.04%   |
| Nvidia + ASPEED         | 3         | 0.04%   |
| AMD + Matrox            | 3         | 0.04%   |
| 1 x S3 Graphics         | 2         | 0.03%   |
| 3 x AMD                 | 1         | 0.01%   |
| 2 x Nvidia + 1 x Matrox | 1         | 0.01%   |
| 2 x AMD + 1 x Nvidia    | 1         | 0.01%   |
| Intel + 2 x AMD         | 1         | 0.01%   |
| AMD + 2 x Nvidia        | 1         | 0.01%   |
| AMD + ASPEED            | 1         | 0.01%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 6128      | 80.83%  |
| Proprietary | 1184      | 15.62%  |
| Unknown     | 269       | 3.55%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 4115      | 53.45%  |
| 0.01-0.5   | 1049      | 13.63%  |
| 1.01-2.0   | 1016      | 13.2%   |
| 0.51-1.0   | 666       | 8.65%   |
| 3.01-4.0   | 402       | 5.22%   |
| 7.01-8.0   | 199       | 2.58%   |
| 5.01-6.0   | 155       | 2.01%   |
| 8.01-16.0  | 48        | 0.62%   |
| 2.01-3.0   | 47        | 0.61%   |
| 4.01-5.0   | 1         | 0.01%   |
| 16.01-24.0 | 1         | 0.01%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 1141      | 14.61%  |
| AU Optronics            | 917       | 11.74%  |
| Chimei Innolux          | 708       | 9.07%   |
| BOE                     | 646       | 8.27%   |
| LG Display              | 632       | 8.09%   |
| Hewlett-Packard         | 395       | 5.06%   |
| Goldstar                | 355       | 4.55%   |
| Philips                 | 347       | 4.44%   |
| Ancor Communications    | 293       | 3.75%   |
| Acer                    | 254       | 3.25%   |
| Dell                    | 194       | 2.48%   |
| BenQ                    | 175       | 2.24%   |
| Sharp                   | 144       | 1.84%   |
| Apple                   | 144       | 1.84%   |
| Chi Mei Optoelectronics | 142       | 1.82%   |
| AOC                     | 133       | 1.7%    |
| Lenovo                  | 109       | 1.4%    |
| Sony                    | 75        | 0.96%   |
| HannStar                | 74        | 0.95%   |
| LG Philips              | 66        | 0.85%   |
| PANDA                   | 63        | 0.81%   |
| ASUSTek Computer        | 46        | 0.59%   |
| InfoVision              | 45        | 0.58%   |
| Unknown                 | 43        | 0.55%   |
| LG Electronics          | 39        | 0.5%    |
| MSI                     | 29        | 0.37%   |
| CPT                     | 25        | 0.32%   |
| CSO                     | 24        | 0.31%   |
| Eizo                    | 23        | 0.29%   |
| Fujitsu Siemens         | 22        | 0.28%   |
| Toshiba                 | 17        | 0.22%   |
| Panasonic               | 16        | 0.2%    |
| Iiyama                  | 16        | 0.2%    |
| Packard Bell            | 15        | 0.19%   |
| Vestel Elektronik       | 14        | 0.18%   |
| NEC Computers           | 14        | 0.18%   |
| Quanta Display          | 13        | 0.17%   |
| LGD                     | 13        | 0.17%   |
| Mi                      | 12        | 0.15%   |
| RTK                     | 11        | 0.14%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15DB 1366x768 344x193mm 15.5-inch          | 69        | 0.86%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                   | 43        | 0.54%   |
| Chimei Innolux LCD Monitor CMN14D4 1920x1080 309x173mm 13.9-inch         | 39        | 0.49%   |
| Samsung Electronics C27F390 SAM0D32 1920x1080 598x336mm 27.0-inch        | 35        | 0.44%   |
| BOE LCD Monitor BOE06A5 1366x768 344x194mm 15.5-inch                     | 35        | 0.44%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch              | 34        | 0.42%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch         | 33        | 0.41%   |
| AU Optronics LCD Monitor AUO71EC 1366x768 344x193mm 15.5-inch            | 33        | 0.41%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch           | 33        | 0.41%   |
| Chimei Innolux LCD Monitor CMN15C9 1366x768 344x193mm 15.5-inch          | 30        | 0.37%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch           | 29        | 0.36%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch            | 28        | 0.35%   |
| AU Optronics LCD Monitor AUO22EC 1366x768 344x193mm 15.5-inch            | 27        | 0.34%   |
| Chi Mei Optoelectronics LCD Monitor CMO15A7 1366x768 344x193mm 15.5-inch | 26        | 0.32%   |
| Samsung Electronics S24F350 SAM0D20 1920x1080 521x293mm 23.5-inch        | 25        | 0.31%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 520x290mm 23.4-inch                  | 25        | 0.31%   |
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch         | 24        | 0.3%    |
| Chimei Innolux LCD Monitor CMN15E6 1366x768 344x193mm 15.5-inch          | 24        | 0.3%    |
| Ancor Communications ASUS VS228 ACI22FD 1920x1080 476x268mm 21.5-inch    | 24        | 0.3%    |
| BOE LCD Monitor BOE0872 1920x1080 344x194mm 15.5-inch                    | 23        | 0.29%   |
| Samsung Electronics LCD Monitor SEC5441 1280x800 331x207mm 15.4-inch     | 22        | 0.27%   |
| LG Display LCD Monitor LGD039F 1366x768 345x194mm 15.6-inch              | 22        | 0.27%   |
| AU Optronics LCD Monitor AUO45EC 1366x768 344x193mm 15.5-inch            | 22        | 0.27%   |
| AU Optronics LCD Monitor AUO403D 1920x1080 309x173mm 13.9-inch           | 22        | 0.27%   |
| AU Optronics LCD Monitor AUO23EC 1366x768 344x193mm 15.5-inch            | 22        | 0.27%   |
| Chimei Innolux LCD Monitor CMN15CA 1366x768 344x193mm 15.5-inch          | 20        | 0.25%   |
| BOE LCD Monitor BOE06A4 1366x768 344x194mm 15.5-inch                     | 20        | 0.25%   |
| Samsung Electronics S24D330 SAM0D92 1920x1080 531x299mm 24.0-inch        | 18        | 0.22%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                  | 18        | 0.22%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch            | 18        | 0.22%   |
| AU Optronics LCD Monitor AUO106C 1366x768 276x155mm 12.5-inch            | 18        | 0.22%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch        | 17        | 0.21%   |
| LG Display LCD Monitor LGD046F 1920x1080 345x194mm 15.6-inch             | 17        | 0.21%   |
| Philips 226V4 PHLC0B1 1920x1080 477x268mm 21.5-inch                      | 16        | 0.2%    |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                    | 16        | 0.2%    |
| AU Optronics LCD Monitor AUO18D4 1280x800 216x135mm 10.0-inch            | 16        | 0.2%    |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch     | 15        | 0.19%   |
| Hewlett-Packard 24f HPN3545 1920x1080 527x296mm 23.8-inch                | 15        | 0.19%   |
| HannStar LCD Monitor HSD03E9 1024x600 220x129mm 10.0-inch                | 15        | 0.19%   |
| BOE LCD Monitor BOE0893 2160x1440 296x197mm 14.0-inch                    | 15        | 0.19%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 3280      | 43.67%  |
| 1366x768 (WXGA)    | 1516      | 20.18%  |
| 3840x2160 (4K)     | 384       | 5.11%   |
| 1280x1024 (SXGA)   | 322       | 4.29%   |
| 1280x800 (WXGA)    | 305       | 4.06%   |
| 1440x900 (WXGA+)   | 240       | 3.2%    |
| 2560x1440 (QHD)    | 236       | 3.14%   |
| 1680x1050 (WSXGA+) | 222       | 2.96%   |
| 1600x900 (HD+)     | 200       | 2.66%   |
| 1920x1200 (WUXGA)  | 127       | 1.69%   |
| 1360x768           | 74        | 0.99%   |
| 1024x600           | 61        | 0.81%   |
| Unknown            | 61        | 0.81%   |
| 2560x1080          | 50        | 0.67%   |
| 3440x1440          | 42        | 0.56%   |
| 2560x1600          | 42        | 0.56%   |
| 1024x768 (XGA)     | 38        | 0.51%   |
| 2160x1440          | 37        | 0.49%   |
| 3840x1080          | 31        | 0.41%   |
| 2880x1800          | 25        | 0.33%   |
| 3840x2400          | 18        | 0.24%   |
| 1920x540           | 16        | 0.21%   |
| 1600x1200          | 15        | 0.2%    |
| 1280x720 (HD)      | 13        | 0.17%   |
| 1920x1280          | 11        | 0.15%   |
| 800x1280           | 10        | 0.13%   |
| 3000x2000          | 10        | 0.13%   |
| 3200x1800 (QHD+)   | 9         | 0.12%   |
| 2736x1824          | 9         | 0.12%   |
| 3840x1600          | 6         | 0.08%   |
| 3072x1920          | 6         | 0.08%   |
| 2880x1920          | 6         | 0.08%   |
| 2520x1680          | 5         | 0.07%   |
| 2288x1287          | 5         | 0.07%   |
| 1800x1200          | 5         | 0.07%   |
| 1280x768           | 5         | 0.07%   |
| 4480x1440          | 4         | 0.05%   |
| 2256x1504          | 4         | 0.05%   |
| 2240x1400          | 4         | 0.05%   |
| 1400x1050          | 4         | 0.05%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 2386      | 30.49%  |
| 13      | 655       | 8.37%   |
| 24      | 536       | 6.85%   |
| 27      | 515       | 6.58%   |
| 21      | 494       | 6.31%   |
| 14      | 439       | 5.61%   |
| 23      | 418       | 5.34%   |
| Unknown | 397       | 5.07%   |
| 17      | 361       | 4.61%   |
| 19      | 289       | 3.69%   |
| 18      | 156       | 1.99%   |
| 12      | 147       | 1.88%   |
| 20      | 125       | 1.6%    |
| 22      | 115       | 1.47%   |
| 31      | 93        | 1.19%   |
| 34      | 84        | 1.07%   |
| 10      | 84        | 1.07%   |
| 11      | 75        | 0.96%   |
| 16      | 59        | 0.75%   |
| 40      | 54        | 0.69%   |
| 54      | 44        | 0.56%   |
| 84      | 40        | 0.51%   |
| 72      | 36        | 0.46%   |
| 25      | 25        | 0.32%   |
| 32      | 23        | 0.29%   |
| 26      | 15        | 0.19%   |
| 46      | 13        | 0.17%   |
| 28      | 13        | 0.17%   |
| 52      | 12        | 0.15%   |
| 48      | 11        | 0.14%   |
| 65      | 10        | 0.13%   |
| 42      | 10        | 0.13%   |
| 37      | 9         | 0.12%   |
| 7       | 9         | 0.12%   |
| 36      | 8         | 0.1%    |
| 39      | 7         | 0.09%   |
| 29      | 6         | 0.08%   |
| 8       | 6         | 0.08%   |
| 142     | 5         | 0.06%   |
| 43      | 5         | 0.06%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm    | Computers | Percent |
|----------------|-----------|---------|
| 301-350        | 3233      | 41.8%   |
| 501-600        | 1383      | 17.88%  |
| 401-500        | 1004      | 12.98%  |
| 201-300        | 685       | 8.86%   |
| 351-400        | 448       | 5.79%   |
| Unknown        | 397       | 5.13%   |
| 601-700        | 164       | 2.12%   |
| 701-800        | 118       | 1.53%   |
| 1001-1500      | 107       | 1.38%   |
| 1501-2000      | 81        | 1.05%   |
| 801-900        | 76        | 0.98%   |
| 901-1000       | 15        | 0.19%   |
| 1-100          | 10        | 0.13%   |
| 101-200        | 8         | 0.1%    |
| More than 2000 | 5         | 0.06%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 5288      | 73.37%  |
| 16/10   | 962       | 13.35%  |
| Unknown | 328       | 4.55%   |
| 5/4     | 310       | 4.3%    |
| 3/2     | 103       | 1.43%   |
| 21/9    | 94        | 1.3%    |
| 4/3     | 82        | 1.14%   |
| 6/5     | 14        | 0.19%   |
| 32/9    | 10        | 0.14%   |
| 0.67    | 9         | 0.12%   |
| 1.00    | 5         | 0.07%   |
| 2.65    | 1         | 0.01%   |
| 2.21    | 1         | 0.01%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 2382      | 30.7%   |
| 201-250        | 1269      | 16.36%  |
| 81-90          | 796       | 10.26%  |
| 151-200        | 578       | 7.45%   |
| 301-350        | 530       | 6.83%   |
| Unknown        | 397       | 5.12%   |
| 71-80          | 302       | 3.89%   |
| 141-150        | 248       | 3.2%    |
| 351-500        | 212       | 2.73%   |
| 121-130        | 180       | 2.32%   |
| More than 1000 | 170       | 2.19%   |
| 251-300        | 165       | 2.13%   |
| 61-70          | 132       | 1.7%    |
| 501-1000       | 120       | 1.55%   |
| 41-50          | 83        | 1.07%   |
| 51-60          | 77        | 0.99%   |
| 111-120        | 46        | 0.59%   |
| 131-140        | 34        | 0.44%   |
| 91-100         | 21        | 0.27%   |
| 1-40           | 17        | 0.22%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 2658      | 34.95%  |
| 101-120       | 1997      | 26.26%  |
| 121-160       | 1849      | 24.31%  |
| 161-240       | 425       | 5.59%   |
| Unknown       | 397       | 5.22%   |
| 1-50          | 149       | 1.96%   |
| More than 240 | 131       | 1.72%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 6285      | 82.61%  |
| 2     | 944       | 12.41%  |
| 0     | 290       | 3.81%   |
| 3     | 85        | 1.12%   |
| 4     | 4         | 0.05%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 4084      | 36.24%  |
| Intel                             | 3223      | 28.6%   |
| Qualcomm Atheros                  | 1355      | 12.03%  |
| Broadcom                          | 664       | 5.89%   |
| Marvell Technology Group          | 213       | 1.89%   |
| TP-Link                           | 161       | 1.43%   |
| Broadcom Limited                  | 158       | 1.4%    |
| Nvidia                            | 143       | 1.27%   |
| Ralink Technology                 | 136       | 1.21%   |
| Ralink                            | 119       | 1.06%   |
| MediaTek                          | 117       | 1.04%   |
| Qualcomm Atheros Communications   | 55        | 0.49%   |
| Huawei Technologies               | 55        | 0.49%   |
| ASIX Electronics                  | 52        | 0.46%   |
| Samsung Electronics               | 46        | 0.41%   |
| Xiaomi                            | 44        | 0.39%   |
| D-Link System                     | 43        | 0.38%   |
| D-Link                            | 39        | 0.35%   |
| VIA Technologies                  | 32        | 0.28%   |
| Sitecom Europe                    | 32        | 0.28%   |
| Dell                              | 32        | 0.28%   |
| NetGear                           | 28        | 0.25%   |
| Silicon Integrated Systems [SiS]  | 26        | 0.23%   |
| Sierra Wireless                   | 22        | 0.2%    |
| ASUSTek Computer                  | 22        | 0.2%    |
| OPPO Electronics                  | 21        | 0.19%   |
| Microsoft                         | 21        | 0.19%   |
| JMicron Technology                | 21        | 0.19%   |
| Ericsson Business Mobile Networks | 21        | 0.19%   |
| Qualcomm                          | 17        | 0.15%   |
| Attansic Technology               | 17        | 0.15%   |
| DisplayLink                       | 16        | 0.14%   |
| Microchip Technology              | 14        | 0.12%   |
| Belkin Components                 | 14        | 0.12%   |
| Hewlett-Packard                   | 13        | 0.12%   |
| ZTE WCDMA Technologies MSM        | 11        | 0.1%    |
| OnePlus Technology (Shenzhen)     | 9         | 0.08%   |
| Lenovo                            | 9         | 0.08%   |
| Gemtek                            | 9         | 0.08%   |
| T & A Mobile Phones               | 8         | 0.07%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 2764      | 21.19%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 472       | 3.62%   |
| Intel Wi-Fi 6 AX200                                                     | 255       | 1.96%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 241       | 1.85%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                   | 224       | 1.72%   |
| Intel Wireless 8265 / 8275                                              | 203       | 1.56%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 200       | 1.53%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 195       | 1.5%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 194       | 1.49%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 180       | 1.38%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 177       | 1.36%   |
| Intel Wireless 7265                                                     | 175       | 1.34%   |
| Intel Wireless 3165                                                     | 162       | 1.24%   |
| Intel Wi-Fi 6 AX201                                                     | 154       | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 149       | 1.14%   |
| Intel Ethernet Connection (2) I219-V                                    | 119       | 0.91%   |
| Intel I211 Gigabit Network Connection                                   | 113       | 0.87%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 112       | 0.86%   |
| Intel Wireless 7260                                                     | 110       | 0.84%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 96        | 0.74%   |
| Realtek RTL8125 2.5GbE Controller                                       | 95        | 0.73%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 93        | 0.71%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter                   | 89        | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 88        | 0.67%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 84        | 0.64%   |
| Intel Wireless 8260                                                     | 83        | 0.64%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 83        | 0.64%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 80        | 0.61%   |
| Intel 82579V Gigabit Network Connection                                 | 80        | 0.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 79        | 0.61%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 76        | 0.58%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 74        | 0.57%   |
| Intel Ethernet Connection I217-LM                                       | 72        | 0.55%   |
| Intel WiFi Link 5100                                                    | 70        | 0.54%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 69        | 0.53%   |
| Broadcom BCM43142 802.11b/g/n                                           | 66        | 0.51%   |
| Intel Wireless-AC 9260                                                  | 60        | 0.46%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 59        | 0.45%   |
| Intel Ethernet Controller I225-V                                        | 59        | 0.45%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 57        | 0.44%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                                | Computers | Percent |
|---------------------------------------|-----------|---------|
| Intel                                 | 2429      | 40.02%  |
| Qualcomm Atheros                      | 1142      | 18.81%  |
| Realtek Semiconductor                 | 1099      | 18.11%  |
| Broadcom                              | 437       | 7.2%    |
| TP-Link                               | 144       | 2.37%   |
| Ralink Technology                     | 136       | 2.24%   |
| Ralink                                | 119       | 1.96%   |
| MediaTek                              | 108       | 1.78%   |
| Broadcom Limited                      | 93        | 1.53%   |
| Qualcomm Atheros Communications       | 55        | 0.91%   |
| D-Link                                | 38        | 0.63%   |
| D-Link System                         | 35        | 0.58%   |
| Sitecom Europe                        | 31        | 0.51%   |
| NetGear                               | 27        | 0.44%   |
| Sierra Wireless                       | 22        | 0.36%   |
| ASUSTek Computer                      | 21        | 0.35%   |
| Dell                                  | 20        | 0.33%   |
| Microsoft                             | 18        | 0.3%    |
| Marvell Technology Group              | 14        | 0.23%   |
| Belkin Components                     | 14        | 0.23%   |
| Gemtek                                | 9         | 0.15%   |
| Ericsson Business Mobile Networks     | 7         | 0.12%   |
| Qualcomm                              | 6         | 0.1%    |
| Linksys                               | 6         | 0.1%    |
| Fibocom                               | 6         | 0.1%    |
| AVM                                   | 6         | 0.1%    |
| ZyDAS                                 | 5         | 0.08%   |
| Edimax Technology                     | 4         | 0.07%   |
| 802.11g Adapter [Linksys WUSB54GC v3] | 4         | 0.07%   |
| ZyXEL Communications                  | 2         | 0.03%   |
| U.S. Robotics                         | 2         | 0.03%   |
| Qcom                                  | 2         | 0.03%   |
| Hewlett-Packard                       | 2         | 0.03%   |
| Wilocity                              | 1         | 0.02%   |
| Wacom                                 | 1         | 0.02%   |
| Samsung Electronics                   | 1         | 0.02%   |
| Micro Star International              | 1         | 0.02%   |
| Fiberline                             | 1         | 0.02%   |
| Accton Technology                     | 1         | 0.02%   |
| AboCom Systems                        | 1         | 0.02%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                                     | 255       | 4.18%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 241       | 3.95%   |
| Intel Wireless 8265 / 8275                                              | 203       | 3.32%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 200       | 3.27%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 195       | 3.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 180       | 2.95%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 177       | 2.9%    |
| Intel Wireless 7265                                                     | 175       | 2.87%   |
| Intel Wireless 3165                                                     | 162       | 2.65%   |
| Intel Wi-Fi 6 AX201                                                     | 154       | 2.52%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 149       | 2.44%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 112       | 1.83%   |
| Intel Wireless 7260                                                     | 110       | 1.8%    |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 96        | 1.57%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 93        | 1.52%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 88        | 1.44%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 84        | 1.38%   |
| Intel Wireless 8260                                                     | 83        | 1.36%   |
| Intel PRO/Wireless 3945ABG [Golan] Network Connection                   | 83        | 1.36%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                            | 80        | 1.31%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 79        | 1.29%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 76        | 1.24%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 74        | 1.21%   |
| Intel WiFi Link 5100                                                    | 70        | 1.15%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express)          | 69        | 1.13%   |
| Broadcom BCM43142 802.11b/g/n                                           | 66        | 1.08%   |
| Intel Wireless-AC 9260                                                  | 60        | 0.98%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter           | 59        | 0.97%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 57        | 0.93%   |
| Realtek 802.11ac NIC                                                    | 54        | 0.88%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                      | 52        | 0.85%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 52        | 0.85%   |
| Intel Alder Lake-P PCH CNVi WiFi                                        | 52        | 0.85%   |
| Qualcomm Atheros AR9271 802.11n                                         | 50        | 0.82%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 48        | 0.79%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                             | 47        | 0.77%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                                  | 45        | 0.74%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 45        | 0.74%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 41        | 0.67%   |
| Broadcom BCM4312 802.11b/g LP-PHY                                       | 41        | 0.67%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                           | Computers | Percent |
|----------------------------------|-----------|---------|
| Realtek Semiconductor            | 3659      | 54.47%  |
| Intel                            | 1516      | 22.57%  |
| Qualcomm Atheros                 | 352       | 5.24%   |
| Broadcom                         | 311       | 4.63%   |
| Marvell Technology Group         | 199       | 2.96%   |
| Nvidia                           | 142       | 2.11%   |
| Broadcom Limited                 | 66        | 0.98%   |
| ASIX Electronics                 | 52        | 0.77%   |
| Huawei Technologies              | 45        | 0.67%   |
| Xiaomi                           | 44        | 0.66%   |
| Samsung Electronics              | 44        | 0.66%   |
| VIA Technologies                 | 30        | 0.45%   |
| Silicon Integrated Systems [SiS] | 24        | 0.36%   |
| OPPO Electronics                 | 21        | 0.31%   |
| JMicron Technology               | 21        | 0.31%   |
| TP-Link                          | 17        | 0.25%   |
| Attansic Technology              | 17        | 0.25%   |
| DisplayLink                      | 16        | 0.24%   |
| Qualcomm                         | 11        | 0.16%   |
| ZTE WCDMA Technologies MSM       | 10        | 0.15%   |
| Microchip Technology             | 10        | 0.15%   |
| MediaTek                         | 9         | 0.13%   |
| Lenovo                           | 9         | 0.13%   |
| OnePlus Technology (Shenzhen)    | 8         | 0.12%   |
| D-Link System                    | 8         | 0.12%   |
| Aquantia                         | 8         | 0.12%   |
| Apple                            | 7         | 0.1%    |
| HMD Global                       | 6         | 0.09%   |
| 3Com                             | 6         | 0.09%   |
| Motorola PCS                     | 5         | 0.07%   |
| ICS Advent                       | 5         | 0.07%   |
| Google                           | 5         | 0.07%   |
| T & A Mobile Phones              | 4         | 0.06%   |
| Hewlett-Packard                  | 4         | 0.06%   |
| LG Electronics                   | 3         | 0.04%   |
| Spreadtrum Communications        | 2         | 0.03%   |
| NetXen Incorporated              | 2         | 0.03%   |
| Foxconn / Hon Hai                | 2         | 0.03%   |
| ULi Electronics                  | 1         | 0.01%   |
| SysKonnect                       | 1         | 0.01%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 2764      | 40.55%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 472       | 6.92%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 224       | 3.29%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 194       | 2.85%   |
| Intel Ethernet Connection (2) I219-V                              | 119       | 1.75%   |
| Intel I211 Gigabit Network Connection                             | 113       | 1.66%   |
| Realtek RTL8125 2.5GbE Controller                                 | 95        | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 89        | 1.31%   |
| Intel 82579V Gigabit Network Connection                           | 80        | 1.17%   |
| Intel Ethernet Connection I217-LM                                 | 72        | 1.06%   |
| Intel Ethernet Controller I225-V                                  | 59        | 0.87%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 56        | 0.82%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                     | 48        | 0.7%    |
| Intel Ethernet Connection (4) I219-LM                             | 47        | 0.69%   |
| Intel Ethernet Connection I217-V                                  | 46        | 0.67%   |
| Intel Ethernet Connection (7) I219-V                              | 44        | 0.65%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 42        | 0.62%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                          | 41        | 0.6%    |
| Nvidia MCP61 Ethernet                                             | 39        | 0.57%   |
| Intel Ethernet Connection I218-LM                                 | 39        | 0.57%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                   | 39        | 0.57%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 37        | 0.54%   |
| Intel 82567LM Gigabit Network Connection                          | 37        | 0.54%   |
| Intel 82577LM Gigabit Network Connection                          | 36        | 0.53%   |
| ASIX AX88179 Gigabit Ethernet                                     | 36        | 0.53%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 34        | 0.5%    |
| Nvidia MCP79 Ethernet                                             | 33        | 0.48%   |
| Intel Ethernet Connection I219-LM                                 | 33        | 0.48%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 33        | 0.48%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 33        | 0.48%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 32        | 0.47%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 31        | 0.45%   |
| Intel 82567LM-3 Gigabit Network Connection                        | 31        | 0.45%   |
| Intel Ethernet Connection (4) I219-V                              | 30        | 0.44%   |
| Intel Ethernet Connection (6) I219-V                              | 29        | 0.43%   |
| VIA VT6102/VT6103 [Rhine-II]                                      | 28        | 0.41%   |
| Qualcomm Atheros AR8132 Fast Ethernet                             | 28        | 0.41%   |
| Huawei MLA-L11                                                    | 28        | 0.41%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 28        | 0.41%   |
| Intel Ethernet Connection (2) I219-LM                             | 26        | 0.38%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 6323      | 51.93%  |
| WiFi     | 5735      | 47.1%   |
| Modem    | 104       | 0.85%   |
| Unknown  | 13        | 0.11%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 4458      | 58.67%  |
| Ethernet | 3136      | 41.27%  |
| Unknown  | 3         | 0.04%   |
| Modem    | 1         | 0.01%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 4014      | 53.73%  |
| 1     | 3125      | 41.83%  |
| 0     | 188       | 2.52%   |
| 3     | 122       | 1.63%   |
| 4     | 15        | 0.2%    |
| 5     | 3         | 0.04%   |
| 6     | 2         | 0.03%   |
| 12    | 1         | 0.01%   |
| 7     | 1         | 0.01%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 7025      | 93.33%  |
| Yes  | 502       | 6.67%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 1893      | 43.81%  |
| Realtek Semiconductor           | 538       | 12.45%  |
| Qualcomm Atheros Communications | 261       | 6.04%   |
| Cambridge Silicon Radio         | 255       | 5.9%    |
| IMC Networks                    | 226       | 5.23%   |
| Broadcom                        | 221       | 5.11%   |
| Lite-On Technology              | 188       | 4.35%   |
| Apple                           | 159       | 3.68%   |
| Foxconn / Hon Hai               | 146       | 3.38%   |
| Hewlett-Packard                 | 68        | 1.57%   |
| ASUSTek Computer                | 64        | 1.48%   |
| Realtek                         | 60        | 1.39%   |
| Dell                            | 45        | 1.04%   |
| Toshiba                         | 35        | 0.81%   |
| Ralink                          | 35        | 0.81%   |
| MediaTek                        | 21        | 0.49%   |
| Alps Electric                   | 16        | 0.37%   |
| Marvell Semiconductor           | 13        | 0.3%    |
| TP-Link                         | 11        | 0.25%   |
| Integrated System Solution      | 10        | 0.23%   |
| Ralink Technology               | 7         | 0.16%   |
| Foxconn International           | 5         | 0.12%   |
| Belkin Components               | 5         | 0.12%   |
| Sitecom Europe                  | 4         | 0.09%   |
| Chicony Electronics             | 4         | 0.09%   |
| Askey Computer                  | 4         | 0.09%   |
| Taiyo Yuden                     | 3         | 0.07%   |
| Conwise Technology              | 3         | 0.07%   |
| SINO WEALTH                     | 2         | 0.05%   |
| ISSC                            | 2         | 0.05%   |
| D-Link System                   | 2         | 0.05%   |
| Accel Semiconductor             | 2         | 0.05%   |
| USI                             | 1         | 0.02%   |
| Unknown                         | 1         | 0.02%   |
| Qcom                            | 1         | 0.02%   |
| Opticis                         | 1         | 0.02%   |
| Logitech                        | 1         | 0.02%   |
| HTC (High Tech Computer)        | 1         | 0.02%   |
| Fujitsu Siemens Computers       | 1         | 0.02%   |
| Fujitsu                         | 1         | 0.02%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 760       | 17.58%  |
| Realtek Bluetooth Radio                                                             | 391       | 9.05%   |
| Intel AX201 Bluetooth                                                               | 326       | 7.54%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 272       | 6.29%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 255       | 5.9%    |
| Intel AX200 Bluetooth                                                               | 237       | 5.48%   |
| Realtek  Bluetooth 4.2 Adapter                                                      | 131       | 3.03%   |
| Intel Bluetooth Device                                                              | 125       | 2.89%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 103       | 2.38%   |
| IMC Networks Bluetooth Device                                                       | 102       | 2.36%   |
| Apple Bluetooth Host Controller                                                     | 76        | 1.76%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 64        | 1.48%   |
| IMC Networks Bluetooth Radio                                                        | 59        | 1.37%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 56        | 1.3%    |
| Intel Wireless-AC 9260 Bluetooth Adapter                                            | 56        | 1.3%    |
| Intel Centrino Bluetooth Wireless Transceiver                                       | 54        | 1.25%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 48        | 1.11%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 48        | 1.11%   |
| Lite-On Bluetooth Device                                                            | 48        | 1.11%   |
| Realtek 802.11ac WLAN Adapter                                                       | 47        | 1.09%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 46        | 1.06%   |
| Intel AX210 Bluetooth                                                               | 41        | 0.95%   |
| Broadcom BCM2045 Bluetooth                                                          | 41        | 0.95%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 37        | 0.86%   |
| Ralink RT3290 Bluetooth                                                             | 35        | 0.81%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]                                       | 33        | 0.76%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 32        | 0.74%   |
| IMC Networks Wireless_Device                                                        | 31        | 0.72%   |
| Apple Bluetooth HCI                                                                 | 29        | 0.67%   |
| Apple Bluetooth USB Host Controller                                                 | 28        | 0.65%   |
| Broadcom BCM20702A0 Bluetooth 4.0                                                   | 25        | 0.58%   |
| Intel Centrino Advanced-N 6230 Bluetooth adapter                                    | 23        | 0.53%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 23        | 0.53%   |
| Apple Built-in Bluetooth 2.0+EDR HCI                                                | 23        | 0.53%   |
| Dell BCM20702A0 Bluetooth Module                                                    | 18        | 0.42%   |
| MediaTek Wireless_Device                                                            | 17        | 0.39%   |
| Lite-On Broadcom BCM43142A0 Bluetooth Device                                        | 17        | 0.39%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter                                        | 17        | 0.39%   |
| Broadcom BCM43142A0 Bluetooth Device                                                | 17        | 0.39%   |
| ASUS Broadcom BCM20702A0 Bluetooth                                                  | 17        | 0.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                               | Computers | Percent |
|--------------------------------------|-----------|---------|
| Intel                                | 5376      | 54.51%  |
| AMD                                  | 2004      | 20.32%  |
| Nvidia                               | 1579      | 16.01%  |
| C-Media Electronics                  | 172       | 1.74%   |
| Logitech                             | 59        | 0.6%    |
| Creative Labs                        | 57        | 0.58%   |
| VIA Technologies                     | 43        | 0.44%   |
| Silicon Integrated Systems [SiS]     | 35        | 0.35%   |
| JMTek                                | 31        | 0.31%   |
| GN Netcom                            | 30        | 0.3%    |
| Generalplus Technology               | 24        | 0.24%   |
| Razer USA                            | 23        | 0.23%   |
| Creative Technology                  | 23        | 0.23%   |
| Texas Instruments                    | 22        | 0.22%   |
| Realtek Semiconductor                | 22        | 0.22%   |
| Focusrite-Novation                   | 21        | 0.21%   |
| M-Audio                              | 17        | 0.17%   |
| ASUSTek Computer                     | 14        | 0.14%   |
| Micro Star International             | 13        | 0.13%   |
| BEHRINGER International              | 13        | 0.13%   |
| Kingston Technology                  | 12        | 0.12%   |
| Samson Technologies                  | 11        | 0.11%   |
| Tenx Technology                      | 10        | 0.1%    |
| Plantronics                          | 10        | 0.1%    |
| Dell                                 | 10        | 0.1%    |
| Hewlett-Packard                      | 9         | 0.09%   |
| Corsair                              | 9         | 0.09%   |
| Lenovo                               | 8         | 0.08%   |
| CMX Systems                          | 8         | 0.08%   |
| Trust                                | 7         | 0.07%   |
| Thesycon Systemsoftware & Consulting | 7         | 0.07%   |
| Microsoft                            | 7         | 0.07%   |
| Ensoniq                              | 7         | 0.07%   |
| Sony                                 | 6         | 0.06%   |
| Apple                                | 6         | 0.06%   |
| SteelSeries ApS                      | 5         | 0.05%   |
| SAVITECH                             | 5         | 0.05%   |
| Jieli Technology                     | 5         | 0.05%   |
| Cambridge Silicon Radio              | 5         | 0.05%   |
| Yamaha                               | 4         | 0.04%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Intel Sunrise Point-LP HD Audio                                            | 569       | 4.9%    |
| AMD Family 17h/19h HD Audio Controller                                     | 559       | 4.82%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 457       | 3.94%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 444       | 3.83%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 335       | 2.89%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 331       | 2.85%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 315       | 2.71%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 291       | 2.51%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 275       | 2.37%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 240       | 2.07%   |
| AMD FCH Azalia Controller                                                  | 225       | 1.94%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 224       | 1.93%   |
| Intel Cannon Lake PCH cAVS                                                 | 222       | 1.91%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 218       | 1.88%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 208       | 1.79%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 204       | 1.76%   |
| AMD Starship/Matisse HD Audio Controller                                   | 204       | 1.76%   |
| Intel Haswell-ULT HD Audio Controller                                      | 192       | 1.65%   |
| Intel 8 Series HD Audio Controller                                         | 192       | 1.65%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 159       | 1.37%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 156       | 1.34%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 146       | 1.26%   |
| Intel Comet Lake PCH-LP cAVS                                               | 144       | 1.24%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 143       | 1.23%   |
| AMD Kabini HDMI/DP Audio                                                   | 135       | 1.16%   |
| Intel Broadwell-U Audio Controller                                         | 126       | 1.09%   |
| Intel 200 Series PCH HD Audio                                              | 126       | 1.09%   |
| Nvidia GP107GL High Definition Audio Controller                            | 125       | 1.08%   |
| Nvidia GF108 High Definition Audio Controller                              | 123       | 1.06%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 121       | 1.04%   |
| AMD Family 15h (Models 60h-6fh) Audio Controller                           | 116       | 1%      |
| Nvidia High Definition Audio Controller                                    | 115       | 0.99%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 109       | 0.94%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 104       | 0.9%    |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 102       | 0.88%   |
| Intel Comet Lake PCH cAVS                                                  | 93        | 0.8%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 86        | 0.74%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 81        | 0.7%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 79        | 0.68%   |
| AMD High Definition Audio Controller                                       | 74        | 0.64%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 1047      | 22.12%  |
| SK hynix                     | 794       | 16.77%  |
| Kingston                     | 557       | 11.77%  |
| Unknown                      | 539       | 11.39%  |
| Micron Technology            | 475       | 10.03%  |
| Crucial                      | 329       | 6.95%   |
| Corsair                      | 290       | 6.13%   |
| G.Skill                      | 94        | 1.99%   |
| Unknown (ABCD)               | 91        | 1.92%   |
| Ramaxel Technology           | 87        | 1.84%   |
| Elpida                       | 81        | 1.71%   |
| A-DATA Technology            | 69        | 1.46%   |
| Nanya Technology             | 50        | 1.06%   |
| Team                         | 40        | 0.84%   |
| Unknown                      | 33        | 0.7%    |
| Patriot                      | 29        | 0.61%   |
| Transcend                    | 19        | 0.4%    |
| ASint Technology             | 10        | 0.21%   |
| Unifosa                      | 8         | 0.17%   |
| Toshiba                      | 6         | 0.13%   |
| Timetec                      | 6         | 0.13%   |
| Qimonda                      | 6         | 0.13%   |
| 48spaces                     | 6         | 0.13%   |
| Silicon Power                | 4         | 0.08%   |
| Patriot Memory (PDP Systems) | 4         | 0.08%   |
| Hewlett-Packard              | 4         | 0.08%   |
| GOODRAM                      | 4         | 0.08%   |
| Unknown (AB)                 | 3         | 0.06%   |
| GeIL                         | 3         | 0.06%   |
| A Force                      | 3         | 0.06%   |
| PLEXHD                       | 2         | 0.04%   |
| Netac                        | 2         | 0.04%   |
| Lexar                        | 2         | 0.04%   |
| Goldkey                      | 2         | 0.04%   |
| CSX                          | 2         | 0.04%   |
| ChangXin Memory              | 2         | 0.04%   |
| Apacer                       | 2         | 0.04%   |
| V-Color                      | 1         | 0.02%   |
| Unknown (D386)               | 1         | 0.02%   |
| Unknown (8A5D)               | 1         | 0.02%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 63        | 1.23%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s            | 49        | 0.96%   |
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s            | 42        | 0.82%   |
| Samsung RAM M471A1K43CB1-CRC 8GB SODIMM DDR4 2667MT/s            | 39        | 0.76%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s            | 36        | 0.71%   |
| Corsair RAM CMK16GX4M2B3200C16 8GB DIMM DDR4 3600MT/s            | 35        | 0.69%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 34        | 0.67%   |
| SK hynix RAM HMT451S6BFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 33        | 0.65%   |
| Unknown                                                          | 33        | 0.65%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 30        | 0.59%   |
| Samsung RAM M471B5173QH0-YK0 4GB SODIMM DDR3 1600MT/s            | 30        | 0.59%   |
| Unknown (ABCD) RAM 123456789012345678 2GB DIMM LPDDR4 2400MT/s   | 28        | 0.55%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s            | 28        | 0.55%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 27        | 0.53%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s            | 27        | 0.53%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s           | 25        | 0.49%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s            | 25        | 0.49%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 24        | 0.47%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s            | 23        | 0.45%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s            | 22        | 0.43%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s            | 21        | 0.41%   |
| Samsung RAM M471A2K43DB1-CWE 16GB SODIMM DDR4 3200MT/s           | 21        | 0.41%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s            | 21        | 0.41%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 20        | 0.39%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 20        | 0.39%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 20        | 0.39%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 20        | 0.39%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 20        | 0.39%   |
| SK hynix RAM HMA851S6CJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 19        | 0.37%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 19        | 0.37%   |
| Micron RAM 4ATF51264HZ-2G3B1 4GB SODIMM DDR4 3200MT/s            | 19        | 0.37%   |
| Samsung RAM M471A5244CB0-CWE 4GB Row Of Chips DDR4 3200MT/s      | 18        | 0.35%   |
| Samsung RAM M471A2K43CB1-CTD 16GB SODIMM DDR4 8400MT/s           | 18        | 0.35%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 18        | 0.35%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8192MB SODIMM DDR3 1600MT/s        | 17        | 0.33%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 17        | 0.33%   |
| Unknown RAM Module 4GB SODIMM DDR3                               | 16        | 0.31%   |
| SK hynix RAM HMT351S6BFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 16        | 0.31%   |
| Samsung RAM M471A5244CB0-CTD 4GB Row Of Chips DDR4 2667MT/s      | 16        | 0.31%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s            | 16        | 0.31%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 1887      | 45.34%  |
| DDR3    | 1353      | 32.51%  |
| DDR2    | 281       | 6.75%   |
| LPDDR4  | 199       | 4.78%   |
| SDRAM   | 145       | 3.48%   |
| LPDDR3  | 108       | 2.59%   |
| Unknown | 88        | 2.11%   |
| DDR5    | 37        | 0.89%   |
| DDR     | 33        | 0.79%   |
| LPDDR5  | 18        | 0.43%   |
| DRAM    | 13        | 0.31%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 2422      | 58.59%  |
| DIMM         | 1372      | 33.19%  |
| Row Of Chips | 321       | 7.76%   |
| Chip         | 12        | 0.29%   |
| FB-DIMM      | 4         | 0.1%    |
| Unknown      | 3         | 0.07%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 1686      | 37.21%  |
| 4096  | 1291      | 28.49%  |
| 2048  | 670       | 14.79%  |
| 16384 | 571       | 12.6%   |
| 1024  | 167       | 3.69%   |
| 32768 | 102       | 2.25%   |
| 512   | 36        | 0.79%   |
| 256   | 5         | 0.11%   |
| 3072  | 2         | 0.04%   |
| 32    | 1         | 0.02%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 817       | 18.18%  |
| 2667    | 636       | 14.15%  |
| 3200    | 633       | 14.09%  |
| 2400    | 344       | 7.65%   |
| 1333    | 280       | 6.23%   |
| 2133    | 188       | 4.18%   |
| 1334    | 156       | 3.47%   |
| Unknown | 134       | 2.98%   |
| 667     | 127       | 2.83%   |
| 3600    | 126       | 2.8%    |
| 800     | 119       | 2.65%   |
| 1867    | 105       | 2.34%   |
| 4267    | 63        | 1.4%    |
| 1066    | 62        | 1.38%   |
| 3266    | 60        | 1.34%   |
| 2933    | 38        | 0.85%   |
| 3400    | 37        | 0.82%   |
| 1067    | 37        | 0.82%   |
| 3000    | 35        | 0.78%   |
| 4800    | 32        | 0.71%   |
| 1800    | 32        | 0.71%   |
| 3733    | 30        | 0.67%   |
| 533     | 26        | 0.58%   |
| 1866    | 24        | 0.53%   |
| 3533    | 22        | 0.49%   |
| 3666    | 21        | 0.47%   |
| 2048    | 21        | 0.47%   |
| 4199    | 20        | 0.45%   |
| 8400    | 18        | 0.4%    |
| 6400    | 18        | 0.4%    |
| 400     | 17        | 0.38%   |
| 2666    | 16        | 0.36%   |
| 3800    | 15        | 0.33%   |
| 266     | 15        | 0.33%   |
| 4266    | 10        | 0.22%   |
| 2800    | 10        | 0.22%   |
| 333     | 10        | 0.22%   |
| 2000    | 9         | 0.2%    |
| 975     | 9         | 0.2%    |
| 1639    | 7         | 0.16%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Hewlett-Packard       | 110       | 36.07%  |
| Samsung Electronics   | 54        | 17.7%   |
| Canon                 | 43        | 14.1%   |
| Brother Industries    | 35        | 11.48%  |
| Seiko Epson           | 33        | 10.82%  |
| Xerox                 | 4         | 1.31%   |
| Lexmark International | 4         | 1.31%   |
| Dymo-CoStar           | 4         | 1.31%   |
| Pantum                | 3         | 0.98%   |
| Prolific Technology   | 2         | 0.66%   |
| Oki Data              | 2         | 0.66%   |
| Kyocera               | 2         | 0.66%   |
| Apple                 | 2         | 0.66%   |
| Toshiba TEC           | 1         | 0.33%   |
| STMicroelectronics    | 1         | 0.33%   |
| Sato                  | 1         | 0.33%   |
| Sagem                 | 1         | 0.33%   |
| Ricoh                 | 1         | 0.33%   |
| QinHeng Electronics   | 1         | 0.33%   |
| ICS Advent            | 1         | 0.33%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Samsung M2020 Series                                                  | 9         | 2.94%   |
| Seiko Epson WF-2510 Series                                            | 8         | 2.61%   |
| HP OfficeJet 6950                                                     | 8         | 2.61%   |
| Samsung ML-216x Series Laser Printer                                  | 7         | 2.29%   |
| Samsung M267x 287x Series                                             | 7         | 2.29%   |
| HP Deskjet 2050 J510                                                  | 7         | 2.29%   |
| Samsung M2070 Series                                                  | 6         | 1.96%   |
| Seiko Epson Printer                                                   | 5         | 1.63%   |
| HP LaserJet 1018                                                      | 5         | 1.63%   |
| HP ENVY 4520 series                                                   | 5         | 1.63%   |
| Canon LiDE 400                                                        | 5         | 1.63%   |
| Seiko Epson ME OFFICE 620F Series/Stylus Office BX305F/BX305FW/TX320F | 4         | 1.31%   |
| HP Officejet 2620 series                                              | 4         | 1.31%   |
| HP LaserJet P1102                                                     | 4         | 1.31%   |
| Canon PIXMA MG3600 Series                                             | 4         | 1.31%   |
| Samsung ML-1660 Series                                                | 3         | 0.98%   |
| Samsung ML-1640 Series Laser Printer                                  | 3         | 0.98%   |
| Samsung Composite Device                                              | 3         | 0.98%   |
| HP LaserJet Professional P 1102w                                      | 3         | 0.98%   |
| HP LaserJet P1005                                                     | 3         | 0.98%   |
| HP LaserJet 1200                                                      | 3         | 0.98%   |
| HP ENVY 5000 series                                                   | 3         | 0.98%   |
| HP Deskjet F4500 series                                               | 3         | 0.98%   |
| HP Deskjet 3520 series                                                | 3         | 0.98%   |
| HP Deskjet 3050A                                                      | 3         | 0.98%   |
| Dymo-CoStar LabelWriter 450                                           | 3         | 0.98%   |
| Canon PIXMA MG2500 Series                                             | 3         | 0.98%   |
| Brother MFC-L2700DW                                                   | 3         | 0.98%   |
| Brother HL-3140CW series                                              | 3         | 0.98%   |
| Brother DCP-1610W                                                     | 3         | 0.98%   |
| Seiko Epson ET-2820 Series                                            | 2         | 0.65%   |
| Samsung SCX-4623 Series                                               | 2         | 0.65%   |
| Samsung SCX-4300 Series                                               | 2         | 0.65%   |
| Prolific PL2305 Parallel Port                                         | 2         | 0.65%   |
| Oki Data USB Device                                                   | 2         | 0.65%   |
| Lexmark International InkJet Color Printer                            | 2         | 0.65%   |
| HP Officejet Pro 6230                                                 | 2         | 0.65%   |
| HP OfficeJet 5200 series                                              | 2         | 0.65%   |
| HP OfficeJet 4650 series                                              | 2         | 0.65%   |
| HP Officejet 4630 series                                              | 2         | 0.65%   |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor             | Computers | Percent |
|--------------------|-----------|---------|
| Canon              | 43        | 54.43%  |
| Seiko Epson        | 21        | 26.58%  |
| Hewlett-Packard    | 9         | 11.39%  |
| Mustek Systems     | 4         | 5.06%   |
| Ultima Electronics | 1         | 1.27%   |
| Plustek            | 1         | 1.27%   |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                                                                                 | Computers | Percent |
|---------------------------------------------------------------------------------------|-----------|---------|
| Canon CanoScan LiDE 110                                                               | 10        | 12.5%   |
| Canon CanoScan LiDE 210                                                               | 6         | 7.5%    |
| Canon CanoScan N670U/N676U/LiDE 20                                                    | 5         | 6.25%   |
| Canon CanoScan LiDE 120                                                               | 4         | 5%      |
| Seiko Epson GT-F520/GT-F570 [Perfection 3590 PHOTO]                                   | 3         | 3.75%   |
| Seiko Epson GT-F500/GT-F550 [Perfection 2480/2580 PHOTO]                              | 3         | 3.75%   |
| Canon CanoScan LiDE 220                                                               | 3         | 3.75%   |
| Canon CanoScan LiDE 100                                                               | 3         | 3.75%   |
| Seiko Epson GT-7700U [Perfection 1240U]                                               | 2         | 2.5%    |
| Seiko Epson GT-7300U [Perfection 1260/1260 PHOTO]                                     | 2         | 2.5%    |
| Mustek Systems BearPaw 1200 CU Plus                                                   | 2         | 2.5%    |
| HP Scanjet 200                                                                        | 2         | 2.5%    |
| Canon CanoScan N1240U/LiDE 30                                                         | 2         | 2.5%    |
| Canon CanoScan LiDE 60                                                                | 2         | 2.5%    |
| Canon CanoScan LIDE 25                                                                | 2         | 2.5%    |
| Ultima Artec Ultima 2000 (GT6801 based)/Lifetec LT9385/ScanMagic 1200 UB Plus Scanner | 1         | 1.25%   |
| Seiko Epson GT-X800 [Perfection 4990 PHOTO]                                           | 1         | 1.25%   |
| Seiko Epson GT-X750 [Perfection 4490 Photo]                                           | 1         | 1.25%   |
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]                               | 1         | 1.25%   |
| Seiko Epson GT-F700 [Perfection V350]                                                 | 1         | 1.25%   |
| Seiko Epson GT-9700F [Perfection 2450 PHOTO]                                          | 1         | 1.25%   |
| Seiko Epson GT-9300UF [Perfection 2400 PHOTO]                                         | 1         | 1.25%   |
| Seiko Epson GT-8400UF [Perfection 1670/1670 PHOTO]                                    | 1         | 1.25%   |
| Seiko Epson GT-7600UF [Perfection 1200U/1200U Photo]                                  | 1         | 1.25%   |
| Seiko Epson GT-6600U [Perfection 610]                                                 | 1         | 1.25%   |
| Seiko Epson ES-D400 [GT-S80]                                                          | 1         | 1.25%   |
| Seiko Epson CC-570L [Stylus CX3100/CX3200]                                            | 1         | 1.25%   |
| Plustek 600DPI USB Scanner                                                            | 1         | 1.25%   |
| Mustek Systems SNAPSCAN e22                                                           | 1         | 1.25%   |
| Mustek Systems ScanExpress A3 USB 1200 PRO                                            | 1         | 1.25%   |
| HP Scanjet G2710                                                                      | 1         | 1.25%   |
| HP ScanJet 3800c                                                                      | 1         | 1.25%   |
| HP ScanJet 3570c                                                                      | 1         | 1.25%   |
| HP ScanJet 3400cse                                                                    | 1         | 1.25%   |
| HP ScanJet 2400c                                                                      | 1         | 1.25%   |
| HP PSC 1200                                                                           | 1         | 1.25%   |
| HP HP4470C                                                                            | 1         | 1.25%   |
| Canon CanoScan LiDE 90                                                                | 1         | 1.25%   |
| Canon CanoScan LiDE 700F                                                              | 1         | 1.25%   |
| Canon CanoScan LiDE 600F                                                              | 1         | 1.25%   |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 1052      | 22.86%  |
| IMC Networks                           | 484       | 10.52%  |
| Microdia                               | 338       | 7.34%   |
| Realtek Semiconductor                  | 320       | 6.95%   |
| Bison Electronics                      | 262       | 5.69%   |
| Logitech                               | 225       | 4.89%   |
| Quanta                                 | 210       | 4.56%   |
| Sunplus Innovation Technology          | 195       | 4.24%   |
| Suyin                                  | 192       | 4.17%   |
| Cheng Uei Precision Industry (Foxlink) | 178       | 3.87%   |
| Apple                                  | 135       | 2.93%   |
| Alcor Micro                            | 110       | 2.39%   |
| Syntek                                 | 108       | 2.35%   |
| Lite-On Technology                     | 92        | 2%      |
| Luxvisions Innotech Limited            | 84        | 1.83%   |
| Acer                                   | 70        | 1.52%   |
| Microsoft                              | 69        | 1.5%    |
| Silicon Motion                         | 52        | 1.13%   |
| Ricoh                                  | 51        | 1.11%   |
| Samsung Electronics                    | 29        | 0.63%   |
| Z-Star Microelectronics                | 28        | 0.61%   |
| ARC International                      | 26        | 0.56%   |
| Trust                                  | 18        | 0.39%   |
| ALi                                    | 17        | 0.37%   |
| Primax Electronics                     | 15        | 0.33%   |
| Generalplus Technology                 | 15        | 0.33%   |
| KYE Systems (Mouse Systems)            | 13        | 0.28%   |
| icSpring                               | 13        | 0.28%   |
| GEMBIRD                                | 12        | 0.26%   |
| SunplusIT                              | 11        | 0.24%   |
| Sonix Technology                       | 11        | 0.24%   |
| Sunplus Technology                     | 10        | 0.22%   |
| Lenovo                                 | 10        | 0.22%   |
| Cubeternet                             | 9         | 0.2%    |
| WaveRider Communications               | 8         | 0.17%   |
| Genesys Logic                          | 8         | 0.17%   |
| Importek                               | 7         | 0.15%   |
| DigiTech                               | 7         | 0.15%   |
| Sunplus IT                             | 6         | 0.13%   |
| Huawei Technologies                    | 6         | 0.13%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                   | Computers | Percent |
|---------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                               | 165       | 3.56%   |
| Microdia Integrated_Webcam_HD                           | 116       | 2.5%    |
| IMC Networks USB2.0 HD UVC WebCam                       | 96        | 2.07%   |
| Chicony HD WebCam                                       | 82        | 1.77%   |
| IMC Networks Integrated Camera                          | 80        | 1.73%   |
| Bison Integrated Camera                                 | 79        | 1.7%    |
| Realtek Integrated_Webcam_HD                            | 77        | 1.66%   |
| IMC Networks USB2.0 VGA UVC WebCam                      | 72        | 1.55%   |
| Logitech Webcam C270                                    | 63        | 1.36%   |
| Syntek Integrated Camera                                | 61        | 1.32%   |
| Alcor Micro USB 2.0 PC cam                              | 55        | 1.19%   |
| Realtek USB Camera                                      | 48        | 1.04%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera     | 47        | 1.01%   |
| Chicony USB2.0 VGA UVC WebCam                           | 46        | 0.99%   |
| Chicony USB2.0 HD UVC WebCam                            | 46        | 0.99%   |
| Chicony HP TrueVision HD                                | 46        | 0.99%   |
| Apple Built-in iSight                                   | 44        | 0.95%   |
| Sunplus Integrated_Webcam_HD                            | 42        | 0.91%   |
| Apple iPhone 5/5C/5S/6/SE/7/8/X                         | 39        | 0.84%   |
| Quanta HP TrueVision HD Camera                          | 38        | 0.82%   |
| Chicony HP TrueVision HD Camera                         | 38        | 0.82%   |
| IMC Networks HD Camera                                  | 37        | 0.8%    |
| Bison HD Webcam                                         | 37        | 0.8%    |
| Chicony HP HD Camera                                    | 35        | 0.75%   |
| Microdia Webcam Vitade AF                               | 34        | 0.73%   |
| Logitech HD Pro Webcam C920                             | 32        | 0.69%   |
| Chicony HP Wide Vision HD Camera                        | 32        | 0.69%   |
| Chicony HP Webcam                                       | 31        | 0.67%   |
| Sunplus HD WebCam                                       | 30        | 0.65%   |
| Microsoft LifeCam HD-3000                               | 30        | 0.65%   |
| Chicony FJ Camera                                       | 30        | 0.65%   |
| Samsung Galaxy series, misc. (MTP mode)                 | 29        | 0.63%   |
| Cheng Uei Precision Industry (Foxlink) HP TrueVision HD | 29        | 0.63%   |
| Quanta HP Webcam                                        | 28        | 0.6%    |
| Chicony USB2.0 Camera                                   | 27        | 0.58%   |
| Apple FaceTime HD Camera (Built-in)                     | 27        | 0.58%   |
| Suyin HP TrueVision HD                                  | 26        | 0.56%   |
| ARC International Camera                                | 26        | 0.56%   |
| Realtek USB2.0 VGA UVC WebCam                           | 25        | 0.54%   |
| Suyin Acer/HP Integrated Webcam [CN0314]                | 24        | 0.52%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                             | Computers | Percent |
|------------------------------------|-----------|---------|
| Validity Sensors                   | 227       | 28.16%  |
| Synaptics                          | 196       | 24.32%  |
| Shenzhen Goodix Technology         | 143       | 17.74%  |
| Elan Microelectronics              | 98        | 12.16%  |
| Upek                               | 43        | 5.33%   |
| AuthenTec                          | 43        | 5.33%   |
| LighTuning Technology              | 39        | 4.84%   |
| STMicroelectronics                 | 6         | 0.74%   |
| Focal-systems.Corp                 | 6         | 0.74%   |
| Realtek USB2.0 Finger Print Bridge | 2         | 0.25%   |
| Microsoft                          | 1         | 0.12%   |
| HOLTEK                             | 1         | 0.12%   |
| Dell                               | 1         | 0.12%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Shenzhen Goodix  FingerPrint Device                                        | 101       | 12.53%  |
| Elan ELAN:ARM-M4                                                           | 67        | 8.31%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 45        | 5.58%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 42        | 5.21%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor                     | 38        | 4.71%   |
| Shenzhen Goodix Fingerprint Reader                                         | 30        | 3.72%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 27        | 3.35%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 25        | 3.1%    |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 22        | 2.73%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 21        | 2.61%   |
| Synaptics WBDI Fingerprint Reader USB 086                                  | 21        | 2.61%   |
| Elan ELAN:Fingerprint                                                      | 21        | 2.61%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 20        | 2.48%   |
| Synaptics  WBDI                                                            | 18        | 2.23%   |
| Synaptics UWP WBDI                                                         | 17        | 2.11%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 16        | 1.99%   |
| Validity Sensors Fingerprint scanner                                       | 16        | 1.99%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 14        | 1.74%   |
| AuthenTec AES2501 Fingerprint Sensor                                       | 14        | 1.74%   |
| Validity Sensors Synaptics WBDI                                            | 13        | 1.61%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 12        | 1.49%   |
| Synaptics WBDI                                                             | 12        | 1.49%   |
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint                  | 12        | 1.49%   |
| Shenzhen Goodix FingerPrint                                                | 12        | 1.49%   |
| Validity Sensors VFS491                                                    | 11        | 1.36%   |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint                   | 10        | 1.24%   |
| Elan WBF Fingerprint Sensor                                                | 10        | 1.24%   |
| Unknown                                                                    | 10        | 1.24%   |
| Synaptics Metallica MOH Touch Fingerprint Reader                           | 9         | 1.12%   |
| Synaptics Fingerprint reader [HP G6]                                       | 9         | 1.12%   |
| Validity Sensors VFS101 Fingerprint Reader                                 | 8         | 0.99%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor                | 8         | 0.99%   |
| AuthenTec Fingerprint Sensor                                               | 8         | 0.99%   |
| Validity Sensors VFS Fingerprint sensor                                    | 7         | 0.87%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 7         | 0.87%   |
| AuthenTec AES2810                                                          | 7         | 0.87%   |
| AuthenTec AES1600                                                          | 7         | 0.87%   |
| STMicroelectronics Fingerprint Reader                                      | 6         | 0.74%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 6         | 0.74%   |
| Validity Sensors VFS301 Fingerprint Reader                                 | 5         | 0.62%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Broadcom                  | 123       | 36.18%  |
| Alcor Micro               | 95        | 27.94%  |
| O2 Micro                  | 28        | 8.24%   |
| Advanced Card Systems     | 23        | 6.76%   |
| Lenovo                    | 16        | 4.71%   |
| Upek                      | 12        | 3.53%   |
| BIT4ID                    | 12        | 3.53%   |
| Gemalto (was Gemplus)     | 8         | 2.35%   |
| Realtek Semiconductor     | 7         | 2.06%   |
| SCM Microsystems          | 5         | 1.47%   |
| OmniKey                   | 3         | 0.88%   |
| Clay Logic                | 3         | 0.88%   |
| Reiner SCT Kartensysteme  | 2         | 0.59%   |
| Microchip Technology      | 1         | 0.29%   |
| In Focus Systems          | 1         | 0.29%   |
| Fujitsu Siemens Computers | 1         | 0.29%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 90        | 26.39%  |
| Broadcom 58200                                                               | 39        | 11.44%  |
| Broadcom BCM5880 Secure Applications Processor                               | 35        | 10.26%  |
| Broadcom 5880                                                                | 27        | 7.92%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 24        | 7.04%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 20        | 5.87%   |
| Advanced Card Systems ACR38 SmartCard Reader                                 | 17        | 4.99%   |
| Lenovo Integrated Smart Card Reader                                          | 16        | 4.69%   |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 12        | 3.52%   |
| BIT4ID miniLector EVO                                                        | 11        | 3.23%   |
| Realtek Semiconductor Smart Card Reader Interface                            | 7         | 2.05%   |
| Advanced Card Systems ACR122U                                                | 6         | 1.76%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 5         | 1.47%   |
| Alcor Micro Watchdata W 1981                                                 | 5         | 1.47%   |
| O2 Micro Oz776 SmartCard Reader                                              | 4         | 1.17%   |
| Gemalto (was Gemplus) Compact Smart Card Reader Writer                       | 3         | 0.88%   |
| Clay Logic Nitrokey Pro                                                      | 3         | 0.88%   |
| SCM Microsystems uTrust 3700 F CL Reader                                     | 2         | 0.59%   |
| Reiner SCT Kartensysteme cyberJack RFID basis contactless smartcard reader   | 2         | 0.59%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint touch sensor | 2         | 0.59%   |
| SCM Microsystems SCR35xx Smart Card Reader                                   | 1         | 0.29%   |
| SCM Microsystems SCR335 SmartCard Reader                                     | 1         | 0.29%   |
| SCM Microsystems Identiv SmartOS Reader                                      | 1         | 0.29%   |
| OmniKey CardMan Smart@Link                                                   | 1         | 0.29%   |
| OmniKey CardMan 3021 / 3121                                                  | 1         | 0.29%   |
| OmniKey 3x21 Smart Card Reader                                               | 1         | 0.29%   |
| Microchip Technology SMSC USX101x Reader                                     | 1         | 0.29%   |
| In Focus Systems EMV Smartcard Reader                                        | 1         | 0.29%   |
| Fujitsu Siemens Computers SmartCard Reader 2A                                | 1         | 0.29%   |
| BIT4ID miniLector AIR NFC v3                                                 | 1         | 0.29%   |
| Advanced Card Systems ACR1281 1S Dual Reader                                 | 1         | 0.29%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 5371      | 70.2%   |
| 1     | 1831      | 23.93%  |
| 2     | 386       | 5.05%   |
| 3     | 42        | 0.55%   |
| 4     | 13        | 0.17%   |
| 5     | 6         | 0.08%   |
| 6     | 2         | 0.03%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 797       | 29.52%  |
| Graphics card            | 692       | 25.63%  |
| Net/wireless             | 320       | 11.85%  |
| Chipcard                 | 284       | 10.52%  |
| Multimedia controller    | 131       | 4.85%   |
| Camera                   | 93        | 3.44%   |
| Communication controller | 85        | 3.15%   |
| Bluetooth                | 64        | 2.37%   |
| Sound                    | 36        | 1.33%   |
| Storage                  | 34        | 1.26%   |
| Unassigned class         | 33        | 1.22%   |
| Modem                    | 25        | 0.93%   |
| Card reader              | 24        | 0.89%   |
| Net/ethernet             | 20        | 0.74%   |
| Flash memory             | 18        | 0.67%   |
| Network                  | 13        | 0.48%   |
| Storage/raid             | 8         | 0.3%    |
| Dvb card                 | 7         | 0.26%   |
| Firewire controller      | 5         | 0.19%   |
| Storage/ide              | 4         | 0.15%   |
| Wireless                 | 2         | 0.07%   |
| Video                    | 2         | 0.07%   |
| Tv card                  | 2         | 0.07%   |
| Storage/nvme             | 1         | 0.04%   |

