Garuda Linux - Tested Hardware & Statistics
-------------------------------------------

A project to collect tested hardware configurations for Garuda Linux.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/Garuda_Linux/Desktop/README.md) and [notebooks](/Dist/Garuda_Linux/Notebook/README.md).

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

Total: 656

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASUSTek       | ZenBook UX331FA_UX331FA     | Notebook    | [8c4d9c62b5](https://linux-hardware.org/?probe=8c4d9c62b5) | Jun 10, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [2e6901471f](https://linux-hardware.org/?probe=2e6901471f) | Jun 10, 2023 |
| ASUSTek       | ROG STRIX B550-A GAMING     | Desktop     | [933978a1ae](https://linux-hardware.org/?probe=933978a1ae) | Jun 07, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [f73406fa5d](https://linux-hardware.org/?probe=f73406fa5d) | Jun 04, 2023 |
| Apple         | MacBookPro14,1              | Notebook    | [1c2d6e0e5e](https://linux-hardware.org/?probe=1c2d6e0e5e) | Jun 04, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [21b7236d20](https://linux-hardware.org/?probe=21b7236d20) | Jun 03, 2023 |
| Lenovo        | IdeaPad S145-15AST 81N3     | Notebook    | [7f0cf2e62d](https://linux-hardware.org/?probe=7f0cf2e62d) | Jun 01, 2023 |
| HP            | Notebook                    | Notebook    | [10ab4427b5](https://linux-hardware.org/?probe=10ab4427b5) | May 29, 2023 |
| Lenovo        | ThinkCentre M58p 6137AU8    | Desktop     | [bd80dea70f](https://linux-hardware.org/?probe=bd80dea70f) | May 29, 2023 |
| Dell          | Precision 5520              | Notebook    | [c7097157ab](https://linux-hardware.org/?probe=c7097157ab) | May 28, 2023 |
| ASUSTek       | Rampage V EDITION 10        | Desktop     | [a7fbdc21bc](https://linux-hardware.org/?probe=a7fbdc21bc) | May 26, 2023 |
| Win elemen... | M600                        | Desktop     | [4c5d685663](https://linux-hardware.org/?probe=4c5d685663) | May 21, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [88d77ec57e](https://linux-hardware.org/?probe=88d77ec57e) | May 21, 2023 |
| ASUSTek       | ROG STRIX B650E-F GAMING... | Desktop     | [262bc7c88f](https://linux-hardware.org/?probe=262bc7c88f) | May 21, 2023 |
| MICROBYTE     | ezbook                      | Notebook    | [aacd79e1c7](https://linux-hardware.org/?probe=aacd79e1c7) | May 20, 2023 |
| Win elemen... | M600                        | Desktop     | [84de4a3207](https://linux-hardware.org/?probe=84de4a3207) | May 20, 2023 |
| Acer          | Extensa 215-52              | Notebook    | [83f139d228](https://linux-hardware.org/?probe=83f139d228) | May 15, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [ad5fd46d55](https://linux-hardware.org/?probe=ad5fd46d55) | May 14, 2023 |
| ASUSTek       | TUF Gaming B550-PLUS        | Desktop     | [194f7f96e5](https://linux-hardware.org/?probe=194f7f96e5) | May 13, 2023 |
| HP            | OMEN by Laptop              | Notebook    | [8b187d1291](https://linux-hardware.org/?probe=8b187d1291) | May 11, 2023 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [fda523de2a](https://linux-hardware.org/?probe=fda523de2a) | May 11, 2023 |
| ASUSTek       | Z170 PRO GAMING             | Desktop     | [3b4eb54186](https://linux-hardware.org/?probe=3b4eb54186) | May 08, 2023 |
| Acer          | Aspire 5750G                | Notebook    | [6b908b35cc](https://linux-hardware.org/?probe=6b908b35cc) | May 08, 2023 |
| MSI           | GL75 9SD                    | Notebook    | [522594401b](https://linux-hardware.org/?probe=522594401b) | May 07, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [3f2fa70636](https://linux-hardware.org/?probe=3f2fa70636) | May 06, 2023 |
| Acer          | Extensa 215-52              | Notebook    | [d4d069aa0c](https://linux-hardware.org/?probe=d4d069aa0c) | May 04, 2023 |
| Lenovo        | ThinkPad W520 42824UU       | Notebook    | [c8474ef15e](https://linux-hardware.org/?probe=c8474ef15e) | May 01, 2023 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [7a5a0f75aa](https://linux-hardware.org/?probe=7a5a0f75aa) | May 01, 2023 |
| Dell          | Inspiron 14 5410 2-in-1     | Convertible | [182acb48b9](https://linux-hardware.org/?probe=182acb48b9) | May 01, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [7d6b0027b3](https://linux-hardware.org/?probe=7d6b0027b3) | Apr 30, 2023 |
| Monster       | TULPAR T5 V21.7             | Notebook    | [1e942ee672](https://linux-hardware.org/?probe=1e942ee672) | Apr 28, 2023 |
| ASRock        | A320M-HD                    | Desktop     | [43b57e5088](https://linux-hardware.org/?probe=43b57e5088) | Apr 28, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [cb87589d9f](https://linux-hardware.org/?probe=cb87589d9f) | Apr 28, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [312db1147a](https://linux-hardware.org/?probe=312db1147a) | Apr 26, 2023 |
| AZW           | SER                         | Mini pc     | [74f148fb60](https://linux-hardware.org/?probe=74f148fb60) | Apr 26, 2023 |
| Apple         | MacBookPro9,2               | Notebook    | [f48b78bda1](https://linux-hardware.org/?probe=f48b78bda1) | Apr 23, 2023 |
| Shenzhen M... | F7BFC                       | Desktop     | [bb189b2507](https://linux-hardware.org/?probe=bb189b2507) | Apr 22, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d9fd347989](https://linux-hardware.org/?probe=d9fd347989) | Apr 20, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [7631901c7a](https://linux-hardware.org/?probe=7631901c7a) | Apr 20, 2023 |
| Gigabyte      | X670 AORUS ELITE AX         | Desktop     | [d5adb940b4](https://linux-hardware.org/?probe=d5adb940b4) | Apr 19, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X170... | Notebook    | [a76057a8be](https://linux-hardware.org/?probe=a76057a8be) | Apr 19, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [4be523b9a9](https://linux-hardware.org/?probe=4be523b9a9) | Apr 18, 2023 |
| Lenovo        | IdeaPad 3 15ITL05 81X8      | Notebook    | [7c35c1ba82](https://linux-hardware.org/?probe=7c35c1ba82) | Apr 15, 2023 |
| Intel         | DH67CL AAG10212-210         | Desktop     | [8519b4cda2](https://linux-hardware.org/?probe=8519b4cda2) | Apr 15, 2023 |
| Gigabyte      | B550M AORUS PRO-P           | Desktop     | [424d545740](https://linux-hardware.org/?probe=424d545740) | Apr 14, 2023 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [e6b0deb213](https://linux-hardware.org/?probe=e6b0deb213) | Apr 14, 2023 |
| Acer          | Veriton K8-680G V:1.0       | Desktop     | [9ab3fc183a](https://linux-hardware.org/?probe=9ab3fc183a) | Apr 13, 2023 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a0e44bf0d1](https://linux-hardware.org/?probe=a0e44bf0d1) | Apr 13, 2023 |
| Win elemen... | M600                        | Desktop     | [7723a03558](https://linux-hardware.org/?probe=7723a03558) | Apr 10, 2023 |
| Win elemen... | M600                        | Desktop     | [e20927ec15](https://linux-hardware.org/?probe=e20927ec15) | Apr 10, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [e2521c6d93](https://linux-hardware.org/?probe=e2521c6d93) | Apr 09, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [b6f721687e](https://linux-hardware.org/?probe=b6f721687e) | Apr 06, 2023 |
| HP            | 8053                        | Desktop     | [9897b3e51f](https://linux-hardware.org/?probe=9897b3e51f) | Apr 04, 2023 |
| ASUSTek       | ASUS TUF Gaming F15 FX50... | Notebook    | [0c0196b199](https://linux-hardware.org/?probe=0c0196b199) | Apr 04, 2023 |
| HP            | Pavilion 15                 | Notebook    | [d928981385](https://linux-hardware.org/?probe=d928981385) | Apr 02, 2023 |
| HP            | Pavilion 15                 | Notebook    | [bc5dd02c14](https://linux-hardware.org/?probe=bc5dd02c14) | Apr 02, 2023 |
| ASUSTek       | M5A78L-M LX PLUS            | Desktop     | [7a2bce56b1](https://linux-hardware.org/?probe=7a2bce56b1) | Mar 26, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [300fe5d1b2](https://linux-hardware.org/?probe=300fe5d1b2) | Mar 24, 2023 |
| Lenovo        | Legion R9000P ARH7H 82RG    | Notebook    | [8291e7598a](https://linux-hardware.org/?probe=8291e7598a) | Mar 24, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [946646a961](https://linux-hardware.org/?probe=946646a961) | Mar 22, 2023 |
| MSI           | MS-ACD21                    | All in one  | [de7c54aec1](https://linux-hardware.org/?probe=de7c54aec1) | Mar 22, 2023 |
| MSI           | MS-ACD21                    | All in one  | [fdea1b7da5](https://linux-hardware.org/?probe=fdea1b7da5) | Mar 22, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [f886dec5e7](https://linux-hardware.org/?probe=f886dec5e7) | Mar 22, 2023 |
| HP            | ZBook 15 G5                 | Notebook    | [83ddb49a8a](https://linux-hardware.org/?probe=83ddb49a8a) | Mar 21, 2023 |
| Samsung       | R530/R730                   | Notebook    | [9cd7e18a6d](https://linux-hardware.org/?probe=9cd7e18a6d) | Mar 21, 2023 |
| Samsung       | R530/R730                   | Notebook    | [87292d633d](https://linux-hardware.org/?probe=87292d633d) | Mar 21, 2023 |
| HP            | 8053                        | Desktop     | [82eb90837f](https://linux-hardware.org/?probe=82eb90837f) | Mar 21, 2023 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e0317127ea](https://linux-hardware.org/?probe=e0317127ea) | Mar 20, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [40372e4af3](https://linux-hardware.org/?probe=40372e4af3) | Mar 19, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [da8abe8a8e](https://linux-hardware.org/?probe=da8abe8a8e) | Mar 19, 2023 |
| MSI           | B450-A PRO MAX              | Desktop     | [15f0543609](https://linux-hardware.org/?probe=15f0543609) | Mar 19, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [9d10f13efc](https://linux-hardware.org/?probe=9d10f13efc) | Mar 18, 2023 |
| ASUSTek       | GL753VE                     | Notebook    | [13c8ab8634](https://linux-hardware.org/?probe=13c8ab8634) | Mar 18, 2023 |
| Gigabyte      | G5 KD                       | Notebook    | [a3234542a9](https://linux-hardware.org/?probe=a3234542a9) | Mar 17, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [8bab1523ae](https://linux-hardware.org/?probe=8bab1523ae) | Mar 16, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [02015c3c38](https://linux-hardware.org/?probe=02015c3c38) | Mar 15, 2023 |
| HP            | 8053                        | Desktop     | [273a6c822b](https://linux-hardware.org/?probe=273a6c822b) | Mar 12, 2023 |
| HP            | 8053                        | Desktop     | [be27383efc](https://linux-hardware.org/?probe=be27383efc) | Mar 11, 2023 |
| ASUSTek       | ROG STRIX X670E-I GAMING... | Desktop     | [51b92fb276](https://linux-hardware.org/?probe=51b92fb276) | Mar 11, 2023 |
| Lenovo        | V15-IIL 82C5                | Notebook    | [da8c40d88c](https://linux-hardware.org/?probe=da8c40d88c) | Mar 11, 2023 |
| Dell          | 0VYXHD A00                  | Desktop     | [d7618c5b6c](https://linux-hardware.org/?probe=d7618c5b6c) | Mar 08, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [f43d0b8fa2](https://linux-hardware.org/?probe=f43d0b8fa2) | Mar 06, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [3549cfad14](https://linux-hardware.org/?probe=3549cfad14) | Feb 27, 2023 |
| Acer          | Aspire E5-575G              | Notebook    | [b2fa34d832](https://linux-hardware.org/?probe=b2fa34d832) | Feb 27, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | Desktop     | [575a7f4897](https://linux-hardware.org/?probe=575a7f4897) | Feb 26, 2023 |
| MSI           | MAG B760 TOMAHAWK WIFI D... | Desktop     | [466f8533fb](https://linux-hardware.org/?probe=466f8533fb) | Feb 26, 2023 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [fad109dc98](https://linux-hardware.org/?probe=fad109dc98) | Feb 25, 2023 |
| Lenovo        | ThinkPad T14s Gen 3 21CQ... | Notebook    | [277834a459](https://linux-hardware.org/?probe=277834a459) | Feb 24, 2023 |
| MSI           | MAG B650 TOMAHAWK WIFI      | Desktop     | [a53235325f](https://linux-hardware.org/?probe=a53235325f) | Feb 23, 2023 |
| HP            | Unknown                     | Notebook    | [06f5e98fdd](https://linux-hardware.org/?probe=06f5e98fdd) | Feb 20, 2023 |
| MSI           | MPG X570 GAMING PLUS        | Desktop     | [bd6a746c89](https://linux-hardware.org/?probe=bd6a746c89) | Feb 20, 2023 |
| MSI           | GE75 Raider 9SE             | Notebook    | [0cf7067e58](https://linux-hardware.org/?probe=0cf7067e58) | Feb 18, 2023 |
| MSI           | B450-A PRO                  | Desktop     | [014bf5276e](https://linux-hardware.org/?probe=014bf5276e) | Feb 17, 2023 |
| Dell          | Precision 7710              | Notebook    | [3db09e931e](https://linux-hardware.org/?probe=3db09e931e) | Feb 15, 2023 |
| Dell          | Precision 7710              | Notebook    | [ed02038c00](https://linux-hardware.org/?probe=ed02038c00) | Feb 15, 2023 |
| ASUSTek       | BT6130                      | Desktop     | [db3b191eb2](https://linux-hardware.org/?probe=db3b191eb2) | Feb 13, 2023 |
| MobileDema... | xTablet T1200               | Notebook    | [905b6efd7a](https://linux-hardware.org/?probe=905b6efd7a) | Feb 12, 2023 |
| Acer          | Aspire A715-41G             | Notebook    | [92b7a6f08d](https://linux-hardware.org/?probe=92b7a6f08d) | Feb 11, 2023 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [59271934a3](https://linux-hardware.org/?probe=59271934a3) | Feb 10, 2023 |
| Lenovo        | ThinkPad P14s Gen 1 20Y1... | Notebook    | [d26fa55616](https://linux-hardware.org/?probe=d26fa55616) | Feb 10, 2023 |
| ASRock        | A520M-ITX/ac                | Desktop     | [a6e401a1d3](https://linux-hardware.org/?probe=a6e401a1d3) | Feb 09, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [5140856482](https://linux-hardware.org/?probe=5140856482) | Feb 06, 2023 |
| HP            | EliteBook 8560w             | Notebook    | [62c1d53a4a](https://linux-hardware.org/?probe=62c1d53a4a) | Feb 06, 2023 |
| HP            | Unknown                     | Notebook    | [b1dacc0d29](https://linux-hardware.org/?probe=b1dacc0d29) | Feb 04, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [2c6c4d9777](https://linux-hardware.org/?probe=2c6c4d9777) | Feb 04, 2023 |
| HP            | Dev One Notebook PC         | Notebook    | [683f389938](https://linux-hardware.org/?probe=683f389938) | Feb 04, 2023 |
| Intel         | X79M-S                      | Desktop     | [91ab5e33ed](https://linux-hardware.org/?probe=91ab5e33ed) | Feb 03, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [6bb85ebe8a](https://linux-hardware.org/?probe=6bb85ebe8a) | Feb 02, 2023 |
| ASUSTek       | TUF Gaming Z690-PLUS D4     | Desktop     | [d6d4c6c38c](https://linux-hardware.org/?probe=d6d4c6c38c) | Jan 31, 2023 |
| ASUSTek       | PRIME Z490-A                | Desktop     | [91dbb8d045](https://linux-hardware.org/?probe=91dbb8d045) | Jan 26, 2023 |
| Standard      | Unknown                     | Notebook    | [d9a5e68741](https://linux-hardware.org/?probe=d9a5e68741) | Jan 25, 2023 |
| HP            | Pavilion dv6                | Notebook    | [0c262643a2](https://linux-hardware.org/?probe=0c262643a2) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [5c24095f67](https://linux-hardware.org/?probe=5c24095f67) | Jan 23, 2023 |
| HP            | Pavilion dv6                | Notebook    | [25269a9baa](https://linux-hardware.org/?probe=25269a9baa) | Jan 23, 2023 |
| Sony          | SVF1521Q1EW                 | Notebook    | [1e8cceb35b](https://linux-hardware.org/?probe=1e8cceb35b) | Jan 23, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [c3c2743dd0](https://linux-hardware.org/?probe=c3c2743dd0) | Jan 22, 2023 |
| Intel         | X79M-S                      | Desktop     | [ccad523936](https://linux-hardware.org/?probe=ccad523936) | Jan 22, 2023 |
| ASUSTek       | PRIME A320M-A               | Desktop     | [918dbdb148](https://linux-hardware.org/?probe=918dbdb148) | Jan 22, 2023 |
| HP            | Pavilion dv6                | Notebook    | [b71b30c5e1](https://linux-hardware.org/?probe=b71b30c5e1) | Jan 22, 2023 |
| MSI           | Stealth 15M B12UE           | Notebook    | [a24b19a2e7](https://linux-hardware.org/?probe=a24b19a2e7) | Jan 21, 2023 |
| Unknown       | Unknown                     | Notebook    | [39bd375140](https://linux-hardware.org/?probe=39bd375140) | Jan 19, 2023 |
| ASUSTek       | Rampage IV GENE             | Desktop     | [64553c4fd7](https://linux-hardware.org/?probe=64553c4fd7) | Jan 17, 2023 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [87e7a60bfa](https://linux-hardware.org/?probe=87e7a60bfa) | Jan 15, 2023 |
| HP            | ProBook 6570b               | Notebook    | [919b330a89](https://linux-hardware.org/?probe=919b330a89) | Jan 15, 2023 |
| ASUSTek       | CM6850                      | Desktop     | [7eac1c6a7a](https://linux-hardware.org/?probe=7eac1c6a7a) | Jan 13, 2023 |
| HP            | OMEN by Laptop 16-b0xxx     | Notebook    | [06fc7ee349](https://linux-hardware.org/?probe=06fc7ee349) | Jan 10, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [5e29a1afb7](https://linux-hardware.org/?probe=5e29a1afb7) | Jan 10, 2023 |
| ASUSTek       | P8H61/USB3 R2.0             | Desktop     | [8daa546122](https://linux-hardware.org/?probe=8daa546122) | Jan 09, 2023 |
| Gigabyte      | X570 I AORUS PRO WIFI       | Desktop     | [919b259ea2](https://linux-hardware.org/?probe=919b259ea2) | Jan 09, 2023 |
| ASUSTek       | PRIME X570-P                | Desktop     | [95c21fc90e](https://linux-hardware.org/?probe=95c21fc90e) | Jan 09, 2023 |
| Acer          | Aspire A515-46              | Notebook    | [1ba0c80baf](https://linux-hardware.org/?probe=1ba0c80baf) | Jan 09, 2023 |
| Lenovo        | ThinkPad Edge E540 20C60... | Notebook    | [774902b83f](https://linux-hardware.org/?probe=774902b83f) | Jan 09, 2023 |
| HP            | ProBook 6570b               | Notebook    | [71e645c6db](https://linux-hardware.org/?probe=71e645c6db) | Jan 08, 2023 |
| Gigabyte      | GA-78LMT-USB3               | Desktop     | [d759bb7551](https://linux-hardware.org/?probe=d759bb7551) | Jan 08, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [c3162b7bfa](https://linux-hardware.org/?probe=c3162b7bfa) | Jan 07, 2023 |
| Lenovo        | G570 4334                   | Notebook    | [8d0c80e474](https://linux-hardware.org/?probe=8d0c80e474) | Jan 07, 2023 |
| HP            | ProBook 6570b               | Notebook    | [6db7bfdd12](https://linux-hardware.org/?probe=6db7bfdd12) | Jan 07, 2023 |
| Dell          | G15 5515                    | Notebook    | [f5a10999c3](https://linux-hardware.org/?probe=f5a10999c3) | Jan 06, 2023 |
| MSI           | H61M-E22/W8                 | Desktop     | [92280cb6ae](https://linux-hardware.org/?probe=92280cb6ae) | Jan 06, 2023 |
| HP            | ProBook 6570b               | Notebook    | [32d96991fd](https://linux-hardware.org/?probe=32d96991fd) | Jan 06, 2023 |
| ASUSTek       | PRIME B360M-C               | Desktop     | [7685480bf0](https://linux-hardware.org/?probe=7685480bf0) | Jan 05, 2023 |
| Intel         | X79M-S                      | Desktop     | [3b38d8023e](https://linux-hardware.org/?probe=3b38d8023e) | Jan 03, 2023 |
| Dell          | 0VHWTR A02                  | Desktop     | [0d9d6203e1](https://linux-hardware.org/?probe=0d9d6203e1) | Jan 03, 2023 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [c0a7ecae1a](https://linux-hardware.org/?probe=c0a7ecae1a) | Jan 03, 2023 |
| Intel         | X79M-S                      | Desktop     | [5c97a3976d](https://linux-hardware.org/?probe=5c97a3976d) | Jan 01, 2023 |
| ASUSTek       | TUF Gaming B660M-E D4       | Desktop     | [a294963db9](https://linux-hardware.org/?probe=a294963db9) | Jan 01, 2023 |
| Gigabyte      | G5 MD                       | Notebook    | [901f1e43f0](https://linux-hardware.org/?probe=901f1e43f0) | Dec 31, 2022 |
| Gigabyte      | G5 MD                       | Notebook    | [631ee5c81c](https://linux-hardware.org/?probe=631ee5c81c) | Dec 31, 2022 |
| AZW           | SER V1.0                    | Mini pc     | [1c406a3696](https://linux-hardware.org/?probe=1c406a3696) | Dec 31, 2022 |
| AZW           | SER V1.0                    | Mini pc     | [08ac155787](https://linux-hardware.org/?probe=08ac155787) | Dec 31, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [9561e51689](https://linux-hardware.org/?probe=9561e51689) | Dec 31, 2022 |
| MSI           | Stealth 15M B12UE           | Notebook    | [45ef7b8ac9](https://linux-hardware.org/?probe=45ef7b8ac9) | Dec 30, 2022 |
| Intel         | H61                         | Desktop     | [39f3cddffb](https://linux-hardware.org/?probe=39f3cddffb) | Dec 29, 2022 |
| Acer          | Aspire F5-572G              | Notebook    | [71168d8107](https://linux-hardware.org/?probe=71168d8107) | Dec 29, 2022 |
| ASUSTek       | ROG STRIX B450-F GAMING ... | Desktop     | [ee98173357](https://linux-hardware.org/?probe=ee98173357) | Dec 27, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [e18b58bbde](https://linux-hardware.org/?probe=e18b58bbde) | Dec 26, 2022 |
| HP            | Compaq CQ58                 | Notebook    | [7e0cac17f6](https://linux-hardware.org/?probe=7e0cac17f6) | Dec 26, 2022 |
| ASUSTek       | Zenbook UM5401QAB_UM5401... | Notebook    | [0de58e9b07](https://linux-hardware.org/?probe=0de58e9b07) | Dec 26, 2022 |
| HONOR         | BOD-WXX9                    | Notebook    | [894521b876](https://linux-hardware.org/?probe=894521b876) | Dec 25, 2022 |
| Lenovo        | IdeaPadFlex 5 14ALC7 82R... | Convertible | [8fe5127ba0](https://linux-hardware.org/?probe=8fe5127ba0) | Dec 25, 2022 |
| HP            | Dev One Notebook PC         | Notebook    | [0e92e9aaf2](https://linux-hardware.org/?probe=0e92e9aaf2) | Dec 23, 2022 |
| Acer          | Nitro AN515-45              | Notebook    | [5cc9050d12](https://linux-hardware.org/?probe=5cc9050d12) | Dec 22, 2022 |
| ASRock        | X570 Taichi                 | Desktop     | [e48882ad67](https://linux-hardware.org/?probe=e48882ad67) | Dec 22, 2022 |
| ASUSTek       | PRIME Z390-P                | Desktop     | [1a9f9ac05f](https://linux-hardware.org/?probe=1a9f9ac05f) | Dec 22, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [7ce8a10de4](https://linux-hardware.org/?probe=7ce8a10de4) | Dec 21, 2022 |
| Lenovo        | Win8 Pro DPK TPG            | Desktop     | [a4c1397ad3](https://linux-hardware.org/?probe=a4c1397ad3) | Dec 21, 2022 |
| Alienware     | m15 R7                      | Notebook    | [56fbeff19d](https://linux-hardware.org/?probe=56fbeff19d) | Dec 18, 2022 |
| HP            | Pavilion Laptop 15-eg0xx... | Notebook    | [016e7d7ef2](https://linux-hardware.org/?probe=016e7d7ef2) | Dec 16, 2022 |
| Lenovo        | IdeaPad L340-17API 81LY     | Notebook    | [b262201707](https://linux-hardware.org/?probe=b262201707) | Dec 10, 2022 |
| BESSTAR Te... | B550                        | Desktop     | [d9fbac807d](https://linux-hardware.org/?probe=d9fbac807d) | Dec 10, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [a2e7958d4a](https://linux-hardware.org/?probe=a2e7958d4a) | Dec 08, 2022 |
| ASRock        | Z77 Pro3                    | Desktop     | [3184df2bf6](https://linux-hardware.org/?probe=3184df2bf6) | Dec 07, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [54d896b9ed](https://linux-hardware.org/?probe=54d896b9ed) | Dec 06, 2022 |
| Lenovo        | Yoga 720-15IKB 80X7         | Convertible | [a7f86279b6](https://linux-hardware.org/?probe=a7f86279b6) | Dec 04, 2022 |
| HP            | Victus by Laptop 16-e1xx... | Notebook    | [0247b424ca](https://linux-hardware.org/?probe=0247b424ca) | Dec 04, 2022 |
| Dell          | Latitude E5450              | Notebook    | [eced7855f2](https://linux-hardware.org/?probe=eced7855f2) | Dec 03, 2022 |
| Dell          | Latitude E7450              | Notebook    | [2df62b206f](https://linux-hardware.org/?probe=2df62b206f) | Dec 03, 2022 |
| Dell          | XPS 13 9360                 | Notebook    | [93aed684b7](https://linux-hardware.org/?probe=93aed684b7) | Dec 03, 2022 |
| Standard      | Unknown                     | Notebook    | [43891b2653](https://linux-hardware.org/?probe=43891b2653) | Dec 02, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [c9ccbe1018](https://linux-hardware.org/?probe=c9ccbe1018) | Dec 01, 2022 |
| MSI           | H510I PRO WIFI              | Desktop     | [f46e59c772](https://linux-hardware.org/?probe=f46e59c772) | Nov 27, 2022 |
| Kogan         | KAL11C250SB                 | Notebook    | [9ca4f71bb9](https://linux-hardware.org/?probe=9ca4f71bb9) | Nov 26, 2022 |
| HP            | EliteBook 840 G5            | Notebook    | [8967d04a19](https://linux-hardware.org/?probe=8967d04a19) | Nov 25, 2022 |
| HP            | 250 G6 Notebook PC          | Notebook    | [8f1bec4fe9](https://linux-hardware.org/?probe=8f1bec4fe9) | Nov 24, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [27109cda18](https://linux-hardware.org/?probe=27109cda18) | Nov 20, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [6dbdd86e08](https://linux-hardware.org/?probe=6dbdd86e08) | Nov 20, 2022 |
| HP            | 8767 A                      | Desktop     | [375e0d4525](https://linux-hardware.org/?probe=375e0d4525) | Nov 19, 2022 |
| ASUSTek       | X541UV                      | Notebook    | [74aca760f1](https://linux-hardware.org/?probe=74aca760f1) | Nov 17, 2022 |
| MSI           | Modern 14 B4MW              | Notebook    | [967a4c4e4d](https://linux-hardware.org/?probe=967a4c4e4d) | Nov 17, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ARH7 82S... | Notebook    | [5c079d3e41](https://linux-hardware.org/?probe=5c079d3e41) | Nov 17, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [e48c737ed6](https://linux-hardware.org/?probe=e48c737ed6) | Nov 17, 2022 |
| Lenovo        | Legion 5 15ACH6H 82JU       | Notebook    | [68db7ff193](https://linux-hardware.org/?probe=68db7ff193) | Nov 16, 2022 |
| Gigabyte      | 990FXA-UD3                  | Desktop     | [985fb6d758](https://linux-hardware.org/?probe=985fb6d758) | Nov 16, 2022 |
| Dell          | 0K3CM7 A00                  | Desktop     | [3c426cb32b](https://linux-hardware.org/?probe=3c426cb32b) | Nov 14, 2022 |
| ASUSTek       | Q505UAR                     | Convertible | [2a5b05500a](https://linux-hardware.org/?probe=2a5b05500a) | Nov 11, 2022 |
| ASUSTek       | Q505UAR                     | Convertible | [f0b3051737](https://linux-hardware.org/?probe=f0b3051737) | Nov 11, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [217544b651](https://linux-hardware.org/?probe=217544b651) | Nov 11, 2022 |
| Dell          | Precision 3571              | Notebook    | [6f845855a5](https://linux-hardware.org/?probe=6f845855a5) | Nov 08, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [27fcb50d7a](https://linux-hardware.org/?probe=27fcb50d7a) | Nov 07, 2022 |
| Lenovo        | ThinkPad E14 20RA000WMH     | Notebook    | [bf3f9b3384](https://linux-hardware.org/?probe=bf3f9b3384) | Nov 07, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [1fd362dd3c](https://linux-hardware.org/?probe=1fd362dd3c) | Nov 06, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [8641947cf9](https://linux-hardware.org/?probe=8641947cf9) | Nov 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [7cd5f4c280](https://linux-hardware.org/?probe=7cd5f4c280) | Nov 05, 2022 |
| Unknown       | Unknown                     | Notebook    | [d808be6d90](https://linux-hardware.org/?probe=d808be6d90) | Oct 31, 2022 |
| HP            | 2B2C                        | Desktop     | [6f90b1e25e](https://linux-hardware.org/?probe=6f90b1e25e) | Oct 26, 2022 |
| Dell          | Inspiron 7737               | Notebook    | [727b48a339](https://linux-hardware.org/?probe=727b48a339) | Oct 25, 2022 |
| Lenovo        | IdeaPad Z500 20202          | Notebook    | [68aeedffa7](https://linux-hardware.org/?probe=68aeedffa7) | Oct 24, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [5558f9e3f7](https://linux-hardware.org/?probe=5558f9e3f7) | Oct 23, 2022 |
| Acer          | Aspire TC-780               | Desktop     | [fd6c66dac7](https://linux-hardware.org/?probe=fd6c66dac7) | Oct 22, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [2f761b8c2f](https://linux-hardware.org/?probe=2f761b8c2f) | Oct 21, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop M350... | Notebook    | [ef7b367052](https://linux-hardware.org/?probe=ef7b367052) | Oct 21, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [d607def641](https://linux-hardware.org/?probe=d607def641) | Oct 20, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [5fa4e96f1c](https://linux-hardware.org/?probe=5fa4e96f1c) | Oct 18, 2022 |
| ASUSTek       | X555LAB                     | Notebook    | [b0fb3c2590](https://linux-hardware.org/?probe=b0fb3c2590) | Oct 18, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [a7d6f0bd9e](https://linux-hardware.org/?probe=a7d6f0bd9e) | Oct 15, 2022 |
| Gigabyte      | G5 MD                       | Notebook    | [fd8b812638](https://linux-hardware.org/?probe=fd8b812638) | Oct 13, 2022 |
| Dell          | XPS 15 9500                 | Notebook    | [e744ed6ac6](https://linux-hardware.org/?probe=e744ed6ac6) | Oct 12, 2022 |
| HP            | ProBook 640 G1              | Notebook    | [06fbfa78a5](https://linux-hardware.org/?probe=06fbfa78a5) | Oct 11, 2022 |
| Acer          | Swift SF314-42              | Notebook    | [e009be07a6](https://linux-hardware.org/?probe=e009be07a6) | Oct 11, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [4bb56ef4e6](https://linux-hardware.org/?probe=4bb56ef4e6) | Oct 06, 2022 |
| HP            | ZBook 15 G5                 | Notebook    | [ae7f5753fd](https://linux-hardware.org/?probe=ae7f5753fd) | Oct 05, 2022 |
| Lenovo        | Yoga 6 13ARE05 82FN         | Convertible | [1c50c72b71](https://linux-hardware.org/?probe=1c50c72b71) | Oct 02, 2022 |
| Gigabyte      | B550 AORUS ELITE V2         | Desktop     | [541e327f0f](https://linux-hardware.org/?probe=541e327f0f) | Oct 01, 2022 |
| HP            | Notebook                    | Notebook    | [6b7215bcba](https://linux-hardware.org/?probe=6b7215bcba) | Sep 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [89c48e7d5a](https://linux-hardware.org/?probe=89c48e7d5a) | Sep 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X512... | Notebook    | [b39aefdcda](https://linux-hardware.org/?probe=b39aefdcda) | Sep 27, 2022 |
| Fujitsu       | FMVA1200G                   | Notebook    | [e91d3af852](https://linux-hardware.org/?probe=e91d3af852) | Sep 27, 2022 |
| Acer          | Aspire V5-552P              | Notebook    | [46395f51b5](https://linux-hardware.org/?probe=46395f51b5) | Sep 27, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [a5e00e04bd](https://linux-hardware.org/?probe=a5e00e04bd) | Sep 25, 2022 |
| HP            | Notebook                    | Notebook    | [f4e47792c1](https://linux-hardware.org/?probe=f4e47792c1) | Sep 24, 2022 |
| Dell          | Precision 7510              | Notebook    | [5f94678049](https://linux-hardware.org/?probe=5f94678049) | Sep 23, 2022 |
| Lenovo        | G505s 20255                 | Notebook    | [671c1cb6c4](https://linux-hardware.org/?probe=671c1cb6c4) | Sep 21, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [6647dc20ac](https://linux-hardware.org/?probe=6647dc20ac) | Sep 21, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9d0697ec96](https://linux-hardware.org/?probe=9d0697ec96) | Sep 20, 2022 |
| ASUSTek       | ROG Zephyrus G15 GA503QR... | Notebook    | [44a3455d48](https://linux-hardware.org/?probe=44a3455d48) | Sep 17, 2022 |
| HP            | ProBook 470 G5              | Notebook    | [b15d9e1fe4](https://linux-hardware.org/?probe=b15d9e1fe4) | Sep 16, 2022 |
| Acer          | Swift SF314-54              | Notebook    | [c3b076c416](https://linux-hardware.org/?probe=c3b076c416) | Sep 15, 2022 |
| Lenovo        | ThinkPad X1 Carbon 2nd 2... | Notebook    | [1cf1136fb8](https://linux-hardware.org/?probe=1cf1136fb8) | Sep 13, 2022 |
| Dell          | Inspiron 5548               | Notebook    | [341b48f953](https://linux-hardware.org/?probe=341b48f953) | Sep 12, 2022 |
| Lenovo        | ThinkPad L15 Gen 2 20X30... | Notebook    | [c1c2e05a86](https://linux-hardware.org/?probe=c1c2e05a86) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [afbb849b02](https://linux-hardware.org/?probe=afbb849b02) | Sep 11, 2022 |
| ASRock        | A320M-HDV R4.0              | Desktop     | [5e98f641f1](https://linux-hardware.org/?probe=5e98f641f1) | Sep 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [c2f25bcea8](https://linux-hardware.org/?probe=c2f25bcea8) | Sep 08, 2022 |
| HP            | Victus by Gaming Laptop ... | Notebook    | [1a8681a1f5](https://linux-hardware.org/?probe=1a8681a1f5) | Sep 07, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [4adadf9e6a](https://linux-hardware.org/?probe=4adadf9e6a) | Sep 06, 2022 |
| Acer          | Aspire E5-573G              | Notebook    | [cfb1abc54b](https://linux-hardware.org/?probe=cfb1abc54b) | Sep 03, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [87fac1a064](https://linux-hardware.org/?probe=87fac1a064) | Sep 02, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [ac65980e25](https://linux-hardware.org/?probe=ac65980e25) | Sep 02, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [2c79168e77](https://linux-hardware.org/?probe=2c79168e77) | Sep 01, 2022 |
| HP            | Laptop 15-da0xxx            | Notebook    | [40482ce9a3](https://linux-hardware.org/?probe=40482ce9a3) | Sep 01, 2022 |
| Gigabyte      | F2A88XM-HD3                 | Desktop     | [44e355eb93](https://linux-hardware.org/?probe=44e355eb93) | Aug 30, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [c63d9bede8](https://linux-hardware.org/?probe=c63d9bede8) | Aug 27, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [a4a7c87b06](https://linux-hardware.org/?probe=a4a7c87b06) | Aug 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [7bc56eb3d4](https://linux-hardware.org/?probe=7bc56eb3d4) | Aug 25, 2022 |
| ASUSTek       | ROG Flow Z13 GZ301ZE_GZ3... | Tablet      | [f9fbb00a0b](https://linux-hardware.org/?probe=f9fbb00a0b) | Aug 23, 2022 |
| HP            | Notebook                    | Notebook    | [bd5bad0b49](https://linux-hardware.org/?probe=bd5bad0b49) | Aug 21, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [57f1970999](https://linux-hardware.org/?probe=57f1970999) | Aug 20, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [ca0fbaa451](https://linux-hardware.org/?probe=ca0fbaa451) | Aug 19, 2022 |
| MSI           | Sword 15 A11UD              | Notebook    | [565a6f9022](https://linux-hardware.org/?probe=565a6f9022) | Aug 19, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [f095219c78](https://linux-hardware.org/?probe=f095219c78) | Aug 19, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [fc5923b017](https://linux-hardware.org/?probe=fc5923b017) | Aug 15, 2022 |
| ASUSTek       | PRIME X570-P                | Desktop     | [e53bbe7c1b](https://linux-hardware.org/?probe=e53bbe7c1b) | Aug 14, 2022 |
| Acer          | Aspire A515-51G             | Notebook    | [f0e405bc07](https://linux-hardware.org/?probe=f0e405bc07) | Aug 13, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [3ad1413aaa](https://linux-hardware.org/?probe=3ad1413aaa) | Aug 13, 2022 |
| MSI           | A68HM-E33 V2                | Desktop     | [762f08a697](https://linux-hardware.org/?probe=762f08a697) | Aug 13, 2022 |
| ASRock        | A520M-HDV                   | Desktop     | [f23bdacb56](https://linux-hardware.org/?probe=f23bdacb56) | Aug 11, 2022 |
| Samsung       | 340XAA/350XAA/550XAA        | Notebook    | [abb938b917](https://linux-hardware.org/?probe=abb938b917) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [8090e74c22](https://linux-hardware.org/?probe=8090e74c22) | Aug 10, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [53efca63c3](https://linux-hardware.org/?probe=53efca63c3) | Aug 10, 2022 |
| Acer          | Aspire 5740                 | Notebook    | [1934c32bc7](https://linux-hardware.org/?probe=1934c32bc7) | Aug 09, 2022 |
| ASUSTek       | GL752VW                     | Notebook    | [9ff6515c13](https://linux-hardware.org/?probe=9ff6515c13) | Aug 07, 2022 |
| Dell          | Latitude E6420              | Notebook    | [c13142690c](https://linux-hardware.org/?probe=c13142690c) | Aug 04, 2022 |
| Microsoft     | Surface with Windows 8 P... | Tablet      | [822e93c1db](https://linux-hardware.org/?probe=822e93c1db) | Aug 02, 2022 |
| ASUSTek       | Maximus IX FORMULA          | Desktop     | [2212732244](https://linux-hardware.org/?probe=2212732244) | Aug 01, 2022 |
| Dell          | Latitude E5450              | Notebook    | [b7618f5c14](https://linux-hardware.org/?probe=b7618f5c14) | Jul 31, 2022 |
| HP            | OMEN by Laptop 15-dh1xxx    | Notebook    | [b44feede78](https://linux-hardware.org/?probe=b44feede78) | Jul 30, 2022 |
| MSI           | B450M PRO-VDH MAX           | Desktop     | [941092ee95](https://linux-hardware.org/?probe=941092ee95) | Jul 26, 2022 |
| MSI           | B450 TOMAHAWK MAX II        | Desktop     | [dfe6047aa7](https://linux-hardware.org/?probe=dfe6047aa7) | Jul 21, 2022 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [f9996d6494](https://linux-hardware.org/?probe=f9996d6494) | Jul 21, 2022 |
| Razer         | Blade 17 (Mid 2021) - RZ... | Notebook    | [0b73c72c74](https://linux-hardware.org/?probe=0b73c72c74) | Jul 19, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [0687ecd744](https://linux-hardware.org/?probe=0687ecd744) | Jul 14, 2022 |
| ASUSTek       | ZenBook UX564EH_Q528EH      | Convertible | [e8770aea50](https://linux-hardware.org/?probe=e8770aea50) | Jul 14, 2022 |
| Lenovo        | Yoga 6 13ALC6 82ND          | Convertible | [f44445fbe2](https://linux-hardware.org/?probe=f44445fbe2) | Jul 13, 2022 |
| HP            | Elite x2 1012 G2            | Tablet      | [9ade46617e](https://linux-hardware.org/?probe=9ade46617e) | Jul 06, 2022 |
| HP            | Pavilion dv6                | Notebook    | [fcb28ad60c](https://linux-hardware.org/?probe=fcb28ad60c) | Jul 05, 2022 |
| HP            | Pavilion dv6                | Notebook    | [31941e5972](https://linux-hardware.org/?probe=31941e5972) | Jul 05, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [7d6a8718a8](https://linux-hardware.org/?probe=7d6a8718a8) | Jul 05, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [dc6e8358f8](https://linux-hardware.org/?probe=dc6e8358f8) | Jul 04, 2022 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [92fe4c2ff3](https://linux-hardware.org/?probe=92fe4c2ff3) | Jul 03, 2022 |
| ASUSTek       | PRIME B550-PLUS AC-HES      | Desktop     | [dde2246ae8](https://linux-hardware.org/?probe=dde2246ae8) | Jul 01, 2022 |
| ASUSTek       | ROG Strix G513IC_G513IC     | Notebook    | [77f0b32727](https://linux-hardware.org/?probe=77f0b32727) | Jun 30, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [5bf5fec549](https://linux-hardware.org/?probe=5bf5fec549) | Jun 27, 2022 |
| HP            | 15 Notebook PC              | Notebook    | [b88589b731](https://linux-hardware.org/?probe=b88589b731) | Jun 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [7c08b4e995](https://linux-hardware.org/?probe=7c08b4e995) | Jun 26, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [06504aecc5](https://linux-hardware.org/?probe=06504aecc5) | Jun 24, 2022 |
| Gigabyte      | Z77X-UD3H                   | Desktop     | [7d7828a253](https://linux-hardware.org/?probe=7d7828a253) | Jun 23, 2022 |
| MSI           | B550-A PRO                  | Desktop     | [a7a76f04f9](https://linux-hardware.org/?probe=a7a76f04f9) | Jun 19, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [f0cf5e0f30](https://linux-hardware.org/?probe=f0cf5e0f30) | Jun 18, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X340... | Notebook    | [5fb74a78d8](https://linux-hardware.org/?probe=5fb74a78d8) | Jun 17, 2022 |
| Lenovo        | IdeaPad Z480                | Notebook    | [1e34fa546d](https://linux-hardware.org/?probe=1e34fa546d) | Jun 15, 2022 |
| MSI           | B450M MORTAR MAX            | Desktop     | [e1f785770e](https://linux-hardware.org/?probe=e1f785770e) | Jun 11, 2022 |
| ASUSTek       | ROG Strix G533QS_G533QS     | Notebook    | [0c1e336ddc](https://linux-hardware.org/?probe=0c1e336ddc) | Jun 11, 2022 |
| Lenovo        | IdeaPad C340-15IML 81TL     | Convertible | [042c11425c](https://linux-hardware.org/?probe=042c11425c) | Jun 10, 2022 |
| T-bao         | MINI PC V1.0                | Desktop     | [8108463ab7](https://linux-hardware.org/?probe=8108463ab7) | Jun 09, 2022 |
| ASRock        | Z87M Extreme4               | Desktop     | [5ca7bb09b0](https://linux-hardware.org/?probe=5ca7bb09b0) | Jun 05, 2022 |
| Acer          | Swift SF315-41              | Notebook    | [389e13e580](https://linux-hardware.org/?probe=389e13e580) | Jun 03, 2022 |
| Lenovo        | IdeaPad 320-14ISK 80XG      | Notebook    | [83cb6d1fe4](https://linux-hardware.org/?probe=83cb6d1fe4) | Jun 01, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [959728c7eb](https://linux-hardware.org/?probe=959728c7eb) | May 29, 2022 |
| Lenovo        | Z50-70 20354                | Notebook    | [cd40cf2e16](https://linux-hardware.org/?probe=cd40cf2e16) | May 28, 2022 |
| Dell          | Latitude E6420              | Notebook    | [425a9e4f0d](https://linux-hardware.org/?probe=425a9e4f0d) | May 26, 2022 |
| HP            | Laptop 15-ef0xxx            | Notebook    | [a214740f99](https://linux-hardware.org/?probe=a214740f99) | May 25, 2022 |
| Dell          | Latitude E5450              | Notebook    | [7d23576abb](https://linux-hardware.org/?probe=7d23576abb) | May 23, 2022 |
| Dell          | Latitude E5450              | Notebook    | [f0c746ba9e](https://linux-hardware.org/?probe=f0c746ba9e) | May 23, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [36a8a2a0ee](https://linux-hardware.org/?probe=36a8a2a0ee) | May 23, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [914eca828e](https://linux-hardware.org/?probe=914eca828e) | May 22, 2022 |
| HUAWEI        | BOHB-WAX9                   | Notebook    | [c0c592bdd7](https://linux-hardware.org/?probe=c0c592bdd7) | May 22, 2022 |
| Unknown       | Unknown                     | Notebook    | [114aa0b977](https://linux-hardware.org/?probe=114aa0b977) | May 22, 2022 |
| Dell          | XPS 13 9370                 | Notebook    | [c7f7168362](https://linux-hardware.org/?probe=c7f7168362) | May 18, 2022 |
| Samsung       | 730QDA                      | Convertible | [c46de205cd](https://linux-hardware.org/?probe=c46de205cd) | May 17, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [cd15058963](https://linux-hardware.org/?probe=cd15058963) | May 16, 2022 |
| Lenovo        | 3716 SDK0T76463 WIN 3422... | Desktop     | [4043d7e26a](https://linux-hardware.org/?probe=4043d7e26a) | May 11, 2022 |
| Razer         | Blade                       | Notebook    | [0e1cc80117](https://linux-hardware.org/?probe=0e1cc80117) | May 07, 2022 |
| Gigabyte      | B450 I AORUS PRO WIFI-CF    | Desktop     | [8c34e423f4](https://linux-hardware.org/?probe=8c34e423f4) | May 04, 2022 |
| Unknown       | Unknown                     | Notebook    | [bd151331c1](https://linux-hardware.org/?probe=bd151331c1) | May 04, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [c8d977cf63](https://linux-hardware.org/?probe=c8d977cf63) | May 02, 2022 |
| Lenovo        | ThinkPad S3 Yoga 14 20DM... | Notebook    | [5d0f1a15e1](https://linux-hardware.org/?probe=5d0f1a15e1) | Apr 30, 2022 |
| Dell          | 0WR7PY A01                  | Desktop     | [66c6e57421](https://linux-hardware.org/?probe=66c6e57421) | Apr 23, 2022 |
| HP            | Laptop 15-bs0xx             | Notebook    | [3ce5eb80eb](https://linux-hardware.org/?probe=3ce5eb80eb) | Apr 22, 2022 |
| ASRock        | B550M Pro4                  | Desktop     | [b82721163b](https://linux-hardware.org/?probe=b82721163b) | Apr 22, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [51eac6f63f](https://linux-hardware.org/?probe=51eac6f63f) | Apr 21, 2022 |
| Dell          | Latitude E7250              | Notebook    | [fa677cf244](https://linux-hardware.org/?probe=fa677cf244) | Apr 21, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [c6d6bddd17](https://linux-hardware.org/?probe=c6d6bddd17) | Apr 18, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [6db9a3dea0](https://linux-hardware.org/?probe=6db9a3dea0) | Apr 18, 2022 |
| ASUSTek       | Z97-P                       | Desktop     | [bf54ec19d0](https://linux-hardware.org/?probe=bf54ec19d0) | Apr 16, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [e5e0f208d9](https://linux-hardware.org/?probe=e5e0f208d9) | Apr 14, 2022 |
| MSI           | GF63 Thin 10SC              | Notebook    | [b5beb1add9](https://linux-hardware.org/?probe=b5beb1add9) | Apr 14, 2022 |
| Lenovo        | ThinkPad X1 Carbon 4th 2... | Notebook    | [7204116754](https://linux-hardware.org/?probe=7204116754) | Apr 14, 2022 |
| ASRock        | X99X Killer                 | Desktop     | [3be92995ff](https://linux-hardware.org/?probe=3be92995ff) | Apr 11, 2022 |
| ASUSTek       | ROG Flow X13 GV301QH_GV3... | Notebook    | [fcfc2b41a7](https://linux-hardware.org/?probe=fcfc2b41a7) | Apr 10, 2022 |
| Unknown       | Unknown                     | Notebook    | [ba87ebf29f](https://linux-hardware.org/?probe=ba87ebf29f) | Apr 08, 2022 |
| ASUSTek       | P8B75-M                     | Desktop     | [808661699f](https://linux-hardware.org/?probe=808661699f) | Apr 07, 2022 |
| HUAWEI        | CREM-WXX9                   | Notebook    | [2803fbf2ab](https://linux-hardware.org/?probe=2803fbf2ab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [658e58fcab](https://linux-hardware.org/?probe=658e58fcab) | Apr 06, 2022 |
| MSI           | GE75 Raider 9SE             | Notebook    | [67966ea318](https://linux-hardware.org/?probe=67966ea318) | Apr 04, 2022 |
| HP            | 8433 11                     | Desktop     | [30c5d1d62f](https://linux-hardware.org/?probe=30c5d1d62f) | Apr 03, 2022 |
| ASUSTek       | ZenBook UX363EA_UX371EA     | Convertible | [c092681184](https://linux-hardware.org/?probe=c092681184) | Apr 03, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [a47ab656ab](https://linux-hardware.org/?probe=a47ab656ab) | Apr 01, 2022 |
| Gigabyte      | B550 GAMING X V2            | Desktop     | [3d37374fae](https://linux-hardware.org/?probe=3d37374fae) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [dc11ff8996](https://linux-hardware.org/?probe=dc11ff8996) | Apr 01, 2022 |
| Casper        | EXCALIBUR G770              | Notebook    | [4a0436ece5](https://linux-hardware.org/?probe=4a0436ece5) | Apr 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [cd6ebcba97](https://linux-hardware.org/?probe=cd6ebcba97) | Mar 31, 2022 |
| Dell          | Latitude E7250              | Notebook    | [a33f627737](https://linux-hardware.org/?probe=a33f627737) | Mar 30, 2022 |
| Unknown       | Unknown                     | Notebook    | [f339c6f710](https://linux-hardware.org/?probe=f339c6f710) | Mar 29, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X515... | Notebook    | [58c7c253ca](https://linux-hardware.org/?probe=58c7c253ca) | Mar 28, 2022 |
| MSI           | GS76 Stealth 11UG           | Notebook    | [d05ccc7f12](https://linux-hardware.org/?probe=d05ccc7f12) | Mar 28, 2022 |
| Apple         | MacBookPro12,1              | Notebook    | [066b026c69](https://linux-hardware.org/?probe=066b026c69) | Mar 28, 2022 |
| MSI           | GE63 Raider RGB 8RE         | Notebook    | [df2ffaa70a](https://linux-hardware.org/?probe=df2ffaa70a) | Mar 25, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII HERO     | Desktop     | [fc5cdc4595](https://linux-hardware.org/?probe=fc5cdc4595) | Mar 23, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [ddcbb702c6](https://linux-hardware.org/?probe=ddcbb702c6) | Mar 17, 2022 |
| HUAWEI        | HVY-WXX9                    | Notebook    | [d54d90820a](https://linux-hardware.org/?probe=d54d90820a) | Mar 17, 2022 |
| MSI           | MPG B550 GAMING CARBON W... | Desktop     | [c1a26607fd](https://linux-hardware.org/?probe=c1a26607fd) | Mar 13, 2022 |
| Toshiba       | Satellite E45DW-C           | Notebook    | [2b815d9219](https://linux-hardware.org/?probe=2b815d9219) | Mar 12, 2022 |
| MSI           | MAG B550 TOMAHAWK           | Desktop     | [95b7c99a5a](https://linux-hardware.org/?probe=95b7c99a5a) | Mar 08, 2022 |
| ASRock        | B450 Gaming K4              | Desktop     | [504b20acce](https://linux-hardware.org/?probe=504b20acce) | Mar 04, 2022 |
| Lenovo        | Legion 7 15IMH05 81YT       | Notebook    | [94786f0b30](https://linux-hardware.org/?probe=94786f0b30) | Mar 02, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [336ddc137d](https://linux-hardware.org/?probe=336ddc137d) | Mar 01, 2022 |
| ASUSTek       | A68HM-PLUS                  | Desktop     | [edfa6eb6e3](https://linux-hardware.org/?probe=edfa6eb6e3) | Feb 28, 2022 |
| ASUSTek       | ProArt X570-CREATOR WIFI    | Desktop     | [abc925b917](https://linux-hardware.org/?probe=abc925b917) | Feb 26, 2022 |
| ASUSTek       | M4A89TD PRO USB3            | Desktop     | [66c0fc8423](https://linux-hardware.org/?probe=66c0fc8423) | Feb 26, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [b4c8253286](https://linux-hardware.org/?probe=b4c8253286) | Feb 23, 2022 |
| Apple         | Mac-031AEE4D24BFF0B1 Mac... | Mini pc     | [a88902a823](https://linux-hardware.org/?probe=a88902a823) | Feb 18, 2022 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [499191c566](https://linux-hardware.org/?probe=499191c566) | Feb 18, 2022 |
| Lenovo        | IdeaPad S340-14API 81NB     | Notebook    | [25da470504](https://linux-hardware.org/?probe=25da470504) | Feb 14, 2022 |
| Unknown       | Unknown                     | Notebook    | [df78a2fff6](https://linux-hardware.org/?probe=df78a2fff6) | Feb 14, 2022 |
| Lenovo        | ThinkPad T530 24296KG       | Notebook    | [9940aacd34](https://linux-hardware.org/?probe=9940aacd34) | Feb 13, 2022 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [e3fd65aa29](https://linux-hardware.org/?probe=e3fd65aa29) | Feb 13, 2022 |
| HP            | 8767 A                      | Desktop     | [e048574911](https://linux-hardware.org/?probe=e048574911) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [a63d909e46](https://linux-hardware.org/?probe=a63d909e46) | Feb 12, 2022 |
| HP            | 8767 A                      | Desktop     | [6cb1e6b72f](https://linux-hardware.org/?probe=6cb1e6b72f) | Feb 12, 2022 |
| ASUSTek       | ROG Maximus XII FORMULA     | Desktop     | [885617bdda](https://linux-hardware.org/?probe=885617bdda) | Feb 12, 2022 |
| Lenovo        | ThinkBook 14-IIL 20SL       | Notebook    | [52eb1d5693](https://linux-hardware.org/?probe=52eb1d5693) | Feb 11, 2022 |
| ASRock        | B450M Pro4                  | Desktop     | [0d80dc8143](https://linux-hardware.org/?probe=0d80dc8143) | Feb 11, 2022 |
| HP            | 86F3 00100                  | All in one  | [6dc9aa1e88](https://linux-hardware.org/?probe=6dc9aa1e88) | Feb 10, 2022 |
| HP            | ENVY x360 Convertible 13... | Convertible | [3c46e807da](https://linux-hardware.org/?probe=3c46e807da) | Feb 09, 2022 |
| Lenovo        | 31900058 STD                | Desktop     | [03540e9cb2](https://linux-hardware.org/?probe=03540e9cb2) | Feb 07, 2022 |
| HONOR         | HLYL-WXX9                   | Notebook    | [9cb5307823](https://linux-hardware.org/?probe=9cb5307823) | Feb 06, 2022 |
| Unknown       | Unknown                     | Notebook    | [e4beeac4a1](https://linux-hardware.org/?probe=e4beeac4a1) | Feb 06, 2022 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [7c19747b0a](https://linux-hardware.org/?probe=7c19747b0a) | Feb 05, 2022 |
| MSI           | GF63 Thin 9SC               | Notebook    | [2e3070dc30](https://linux-hardware.org/?probe=2e3070dc30) | Feb 04, 2022 |
| Dell          | Latitude 5480               | Notebook    | [c96d03d27f](https://linux-hardware.org/?probe=c96d03d27f) | Feb 03, 2022 |
| Lenovo        | ThinkPad P1 20MDS00P00      | Notebook    | [4ff53df600](https://linux-hardware.org/?probe=4ff53df600) | Feb 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X513... | Notebook    | [387da722fe](https://linux-hardware.org/?probe=387da722fe) | Feb 02, 2022 |
| HP            | Laptop 15s-gr0xxx           | Notebook    | [5943c38ac0](https://linux-hardware.org/?probe=5943c38ac0) | Feb 01, 2022 |
| Gigabyte      | MFLP3AP-00\2.x              | Desktop     | [b7441a0e94](https://linux-hardware.org/?probe=b7441a0e94) | Jan 31, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [0497eabcf7](https://linux-hardware.org/?probe=0497eabcf7) | Jan 28, 2022 |
| Lenovo        | ThinkPad T440p 20AWS58F0... | Notebook    | [e7efa96c01](https://linux-hardware.org/?probe=e7efa96c01) | Jan 28, 2022 |
| Unknown       | Unknown                     | Notebook    | [aa0e21b159](https://linux-hardware.org/?probe=aa0e21b159) | Jan 27, 2022 |
| Gigabyte      | B85-HD3                     | Desktop     | [ad70601774](https://linux-hardware.org/?probe=ad70601774) | Jan 26, 2022 |
| Lenovo        | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [9091cc83ba](https://linux-hardware.org/?probe=9091cc83ba) | Jan 26, 2022 |
| Lenovo        | Unknown                     | Notebook    | [b78e96aff8](https://linux-hardware.org/?probe=b78e96aff8) | Jan 22, 2022 |
| Dell          | Inspiron 15-3567            | Notebook    | [af6171a374](https://linux-hardware.org/?probe=af6171a374) | Jan 22, 2022 |
| MSI           | GP75 Leopard 9SD            | Notebook    | [6935c7fc83](https://linux-hardware.org/?probe=6935c7fc83) | Jan 17, 2022 |
| ASRock        | 970M Pro3                   | Desktop     | [402a4f960e](https://linux-hardware.org/?probe=402a4f960e) | Jan 17, 2022 |
| ASUSTek       | ROG Maximus X CODE          | Desktop     | [8fac80f31d](https://linux-hardware.org/?probe=8fac80f31d) | Jan 16, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [9fab263b02](https://linux-hardware.org/?probe=9fab263b02) | Jan 11, 2022 |
| MSI           | Z270 GAMING M5              | Desktop     | [02d70182fd](https://linux-hardware.org/?probe=02d70182fd) | Jan 10, 2022 |
| Lenovo        | Yoga Slim 7 14ARE05 82A2    | Notebook    | [10f53d4021](https://linux-hardware.org/?probe=10f53d4021) | Jan 09, 2022 |
| Lenovo        | IdeaPad 110-15ACL 80TJ      | Notebook    | [a338d9f2d1](https://linux-hardware.org/?probe=a338d9f2d1) | Jan 08, 2022 |
| Gigabyte      | AB350-Gaming 3-CF           | Desktop     | [8a1167daea](https://linux-hardware.org/?probe=8a1167daea) | Jan 08, 2022 |
| Unknown       | Unknown                     | Notebook    | [b75e231fb3](https://linux-hardware.org/?probe=b75e231fb3) | Jan 08, 2022 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [1a4570a458](https://linux-hardware.org/?probe=1a4570a458) | Jan 08, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [34d2cd6d9c](https://linux-hardware.org/?probe=34d2cd6d9c) | Jan 08, 2022 |
| Pegatron      | 2AD5                        | Desktop     | [91ee5ba1df](https://linux-hardware.org/?probe=91ee5ba1df) | Jan 08, 2022 |
| HP            | OMEN Laptop 15-en1xxx       | Notebook    | [9ad04f3022](https://linux-hardware.org/?probe=9ad04f3022) | Jan 07, 2022 |
| Gigabyte      | B460M DS3H                  | Desktop     | [40f4de9da7](https://linux-hardware.org/?probe=40f4de9da7) | Jan 07, 2022 |
| Lenovo        | Legion 5 15IMH05H 81Y6      | Notebook    | [c4db605668](https://linux-hardware.org/?probe=c4db605668) | Jan 06, 2022 |
| Dell          | Precision M4500             | Notebook    | [2504901038](https://linux-hardware.org/?probe=2504901038) | Jan 04, 2022 |
| HP            | Pavilion 14                 | Notebook    | [34167c8022](https://linux-hardware.org/?probe=34167c8022) | Jan 04, 2022 |
| HP            | Pavilion Laptop 15z-eh10... | Notebook    | [29b9cb755b](https://linux-hardware.org/?probe=29b9cb755b) | Dec 25, 2021 |
| Dell          | G15 5515                    | Notebook    | [7e8108b3c2](https://linux-hardware.org/?probe=7e8108b3c2) | Dec 24, 2021 |
| Gigabyte      | B550 AORUS PRO AC           | Desktop     | [1b62246b10](https://linux-hardware.org/?probe=1b62246b10) | Dec 21, 2021 |
| GPU Compan... | GWTN156-11                  | Notebook    | [3700827ecd](https://linux-hardware.org/?probe=3700827ecd) | Dec 19, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [c7147f0bf8](https://linux-hardware.org/?probe=c7147f0bf8) | Dec 16, 2021 |
| ASUSTek       | X550CC                      | Notebook    | [f8a99e7645](https://linux-hardware.org/?probe=f8a99e7645) | Dec 16, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [9e73346fb8](https://linux-hardware.org/?probe=9e73346fb8) | Dec 15, 2021 |
| Razer         | Blade 14 - RZ09-0370        | Notebook    | [c3144c3e22](https://linux-hardware.org/?probe=c3144c3e22) | Dec 13, 2021 |
| Gigabyte      | X570 AORUS ELITE WIFI       | Desktop     | [196b460373](https://linux-hardware.org/?probe=196b460373) | Dec 13, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [df628cbd13](https://linux-hardware.org/?probe=df628cbd13) | Dec 12, 2021 |
| ASRock        | H77M-ITX                    | Desktop     | [5e98a2fce2](https://linux-hardware.org/?probe=5e98a2fce2) | Dec 11, 2021 |
| ASRock        | B450M Pro4                  | Desktop     | [e4fb1e4fe4](https://linux-hardware.org/?probe=e4fb1e4fe4) | Dec 09, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [731c890641](https://linux-hardware.org/?probe=731c890641) | Dec 08, 2021 |
| Acer          | Aspire F5-573G              | Notebook    | [a49a5a129c](https://linux-hardware.org/?probe=a49a5a129c) | Dec 07, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [f499f9a375](https://linux-hardware.org/?probe=f499f9a375) | Dec 06, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [f0df07c0e4](https://linux-hardware.org/?probe=f0df07c0e4) | Dec 06, 2021 |
| HP            | Laptop 15-dy2xxx            | Notebook    | [e6b9de389b](https://linux-hardware.org/?probe=e6b9de389b) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [8ce02488c4](https://linux-hardware.org/?probe=8ce02488c4) | Dec 06, 2021 |
| Acer          | TravelMate 5720             | Notebook    | [b68e789e42](https://linux-hardware.org/?probe=b68e789e42) | Dec 06, 2021 |
| Acer          | Aspire TC-895 V:1.0         | Desktop     | [c743459a71](https://linux-hardware.org/?probe=c743459a71) | Dec 04, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [2b4abcf54f](https://linux-hardware.org/?probe=2b4abcf54f) | Dec 02, 2021 |
| ASUSTek       | H87M-E                      | Desktop     | [72cf0ed74d](https://linux-hardware.org/?probe=72cf0ed74d) | Dec 02, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [f031548aac](https://linux-hardware.org/?probe=f031548aac) | Dec 01, 2021 |
| Lenovo        | ThinkStation S20 4105O1U    | Desktop     | [48f73af82d](https://linux-hardware.org/?probe=48f73af82d) | Nov 30, 2021 |
| Acer          | Aspire A515-51G             | Notebook    | [6ee6a2bc49](https://linux-hardware.org/?probe=6ee6a2bc49) | Nov 30, 2021 |
| Acer          | Nitro AN715-52              | Notebook    | [2b74aabc3a](https://linux-hardware.org/?probe=2b74aabc3a) | Nov 29, 2021 |
| Lenovo        | IdeaPad 330-15ARR 81D2      | Notebook    | [b5b437249c](https://linux-hardware.org/?probe=b5b437249c) | Nov 29, 2021 |
| Unknown       | Unknown                     | Notebook    | [0b1d816eff](https://linux-hardware.org/?probe=0b1d816eff) | Nov 28, 2021 |
| ASUSTek       | K53SD                       | Notebook    | [b2826b96f2](https://linux-hardware.org/?probe=b2826b96f2) | Nov 24, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [fac556ebbe](https://linux-hardware.org/?probe=fac556ebbe) | Nov 24, 2021 |
| Dell          | XPS 15 7590                 | Notebook    | [63f386f998](https://linux-hardware.org/?probe=63f386f998) | Nov 23, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [bbb0689dea](https://linux-hardware.org/?probe=bbb0689dea) | Nov 21, 2021 |
| Dell          | Latitude E5570              | Notebook    | [48ea4215ad](https://linux-hardware.org/?probe=48ea4215ad) | Nov 18, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [1ea5d23a86](https://linux-hardware.org/?probe=1ea5d23a86) | Nov 17, 2021 |
| Lenovo        | Legion S7 15ACH6 82K8       | Notebook    | [2713c3bae1](https://linux-hardware.org/?probe=2713c3bae1) | Nov 16, 2021 |
| Apple         | MacBookPro9,2               | Notebook    | [2c8fef35c1](https://linux-hardware.org/?probe=2c8fef35c1) | Nov 14, 2021 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f455ee4572](https://linux-hardware.org/?probe=f455ee4572) | Nov 14, 2021 |
| ASUSTek       | Rampage IV EXTREME          | Desktop     | [50999d4796](https://linux-hardware.org/?probe=50999d4796) | Nov 14, 2021 |
| HP            | Pavilion Laptop 15-eh0xx... | Notebook    | [d74b03de25](https://linux-hardware.org/?probe=d74b03de25) | Nov 13, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [6584d17e10](https://linux-hardware.org/?probe=6584d17e10) | Nov 09, 2021 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [ed9cd44b17](https://linux-hardware.org/?probe=ed9cd44b17) | Nov 08, 2021 |
| HP            | ProBook 640 G1              | Notebook    | [acb5ceea62](https://linux-hardware.org/?probe=acb5ceea62) | Nov 05, 2021 |
| ASUSTek       | TUF Gaming X570-PLUS        | Desktop     | [cd295bb56c](https://linux-hardware.org/?probe=cd295bb56c) | Nov 04, 2021 |
| ASUSTek       | ASUS EXPERTBOOK P2451FB_... | Notebook    | [976bcf4121](https://linux-hardware.org/?probe=976bcf4121) | Nov 04, 2021 |
| Unknown       | Unknown                     | Notebook    | [86f08832c0](https://linux-hardware.org/?probe=86f08832c0) | Oct 31, 2021 |
| Lenovo        | G510 20238                  | Notebook    | [60fa5ff04c](https://linux-hardware.org/?probe=60fa5ff04c) | Oct 28, 2021 |
| ASUSTek       | P8B75-M                     | Desktop     | [2130c28d33](https://linux-hardware.org/?probe=2130c28d33) | Oct 27, 2021 |
| Panasonic     | CF-191HYAX1M                | Notebook    | [1aed5aedc2](https://linux-hardware.org/?probe=1aed5aedc2) | Oct 25, 2021 |
| Dell          | XPS 13 9350                 | Notebook    | [dde814d7ca](https://linux-hardware.org/?probe=dde814d7ca) | Oct 25, 2021 |
| Apple         | Mac-FC02E91DDD3FA6A4 iMa... | All in one  | [5154b1932f](https://linux-hardware.org/?probe=5154b1932f) | Oct 24, 2021 |
| MSI           | Z77A-G43                    | Desktop     | [3bd9604ae7](https://linux-hardware.org/?probe=3bd9604ae7) | Oct 20, 2021 |
| MSI           | B460M PRO-VDH WIFI          | Desktop     | [76071ec77b](https://linux-hardware.org/?probe=76071ec77b) | Oct 19, 2021 |
| MSI           | B450M-A PRO MAX             | Desktop     | [4148046f02](https://linux-hardware.org/?probe=4148046f02) | Oct 17, 2021 |
| Samsung       | 300V3A/300V4A/300V5A/200... | Notebook    | [d8167a915b](https://linux-hardware.org/?probe=d8167a915b) | Oct 17, 2021 |
| Unknown       | Unknown                     | Notebook    | [ff6b763448](https://linux-hardware.org/?probe=ff6b763448) | Oct 16, 2021 |
| Lenovo        | ThinkPad T510 4384WB4       | Notebook    | [4a54d7fd48](https://linux-hardware.org/?probe=4a54d7fd48) | Oct 16, 2021 |
| Lenovo        | ThinkPad W530 24474KG       | Notebook    | [64fd7ae16c](https://linux-hardware.org/?probe=64fd7ae16c) | Oct 11, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [5070a2bdc7](https://linux-hardware.org/?probe=5070a2bdc7) | Oct 10, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [30036170b1](https://linux-hardware.org/?probe=30036170b1) | Oct 05, 2021 |
| Acer          | Aspire E5-523               | Notebook    | [841a71eac1](https://linux-hardware.org/?probe=841a71eac1) | Oct 04, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [45a0e8618a](https://linux-hardware.org/?probe=45a0e8618a) | Sep 28, 2021 |
| Acer          | Aspire E3-111               | Notebook    | [f0100402ec](https://linux-hardware.org/?probe=f0100402ec) | Sep 28, 2021 |
| Notebook      | P7xxDM2(-G)                 | Notebook    | [284ab5f28e](https://linux-hardware.org/?probe=284ab5f28e) | Sep 28, 2021 |
| Acer          | Aspire V3-572P              | Notebook    | [3eecfd13ad](https://linux-hardware.org/?probe=3eecfd13ad) | Sep 25, 2021 |
| Chuwi         | GemiBook Pro                | Notebook    | [10b47851d2](https://linux-hardware.org/?probe=10b47851d2) | Sep 25, 2021 |
| Lenovo        | IdeaPad S340-15API 81NC     | Notebook    | [2e3e323c0d](https://linux-hardware.org/?probe=2e3e323c0d) | Sep 21, 2021 |
| Acer          | Swift SF114-32              | Notebook    | [91a1652ef2](https://linux-hardware.org/?probe=91a1652ef2) | Sep 18, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [fdd8f9dd8e](https://linux-hardware.org/?probe=fdd8f9dd8e) | Sep 17, 2021 |
| Fujitsu       | D3120-A1 S26361-D3120-A1    | Desktop     | [ab3ad8009e](https://linux-hardware.org/?probe=ab3ad8009e) | Sep 16, 2021 |
| ASUSTek       | PRIME B450M-K               | Desktop     | [b8b49f201f](https://linux-hardware.org/?probe=b8b49f201f) | Sep 14, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [0b9ee7a59d](https://linux-hardware.org/?probe=0b9ee7a59d) | Sep 12, 2021 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [646d26abf7](https://linux-hardware.org/?probe=646d26abf7) | Sep 08, 2021 |
| Razer         | Blade                       | Notebook    | [1ce95784c0](https://linux-hardware.org/?probe=1ce95784c0) | Sep 05, 2021 |
| Razer         | Blade                       | Notebook    | [58a2a48dc4](https://linux-hardware.org/?probe=58a2a48dc4) | Sep 05, 2021 |
| Fujitsu       | LIFEBOOK T936               | Convertible | [e4593929ff](https://linux-hardware.org/?probe=e4593929ff) | Sep 05, 2021 |
| Samsung       | 550XCJ/550XCR               | Notebook    | [85fa26ea9e](https://linux-hardware.org/?probe=85fa26ea9e) | Aug 31, 2021 |
| ASUSTek       | ASUS TUF Gaming A15 FA50... | Notebook    | [b9a6b71efc](https://linux-hardware.org/?probe=b9a6b71efc) | Aug 28, 2021 |
| MSI           | H310M PRO-VDH PLUS          | Desktop     | [65fcfef06f](https://linux-hardware.org/?probe=65fcfef06f) | Aug 27, 2021 |
| Alienware     | 0TYR0X A00                  | Desktop     | [5ea23ebfb2](https://linux-hardware.org/?probe=5ea23ebfb2) | Aug 19, 2021 |
| ASRock        | X399 Professional Gaming    | Desktop     | [bb53a385c3](https://linux-hardware.org/?probe=bb53a385c3) | Aug 19, 2021 |
| Google        | Kindred                     | Notebook    | [ac298188ae](https://linux-hardware.org/?probe=ac298188ae) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [4ec8d56e38](https://linux-hardware.org/?probe=4ec8d56e38) | Aug 13, 2021 |
| Acer          | Aspire E1-522               | Notebook    | [c8892394cf](https://linux-hardware.org/?probe=c8892394cf) | Aug 13, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [ca250625bd](https://linux-hardware.org/?probe=ca250625bd) | Aug 11, 2021 |
| HP            | ProBook 650 G2              | Notebook    | [7705938f1f](https://linux-hardware.org/?probe=7705938f1f) | Aug 11, 2021 |
| Medion        | H110H4-EM2                  | Desktop     | [f4e01958e5](https://linux-hardware.org/?probe=f4e01958e5) | Aug 10, 2021 |
| Unknown       | Unknown                     | Notebook    | [a919fef17f](https://linux-hardware.org/?probe=a919fef17f) | Aug 07, 2021 |
| MSI           | Z97 MPOWER                  | Desktop     | [dee7d3af4a](https://linux-hardware.org/?probe=dee7d3af4a) | Aug 06, 2021 |
| MSI           | Z97 MPOWER                  | Desktop     | [f30e5a3a86](https://linux-hardware.org/?probe=f30e5a3a86) | Aug 06, 2021 |
| HP            | EliteBook 845 G7 Noteboo... | Notebook    | [c505820537](https://linux-hardware.org/?probe=c505820537) | Aug 04, 2021 |
| Acer          | IPMBW-BR                    | All in one  | [a2ef77ad47](https://linux-hardware.org/?probe=a2ef77ad47) | Aug 03, 2021 |
| ASUSTek       | G750JZ                      | Notebook    | [f35df8640b](https://linux-hardware.org/?probe=f35df8640b) | Aug 02, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d25176b845](https://linux-hardware.org/?probe=d25176b845) | Jul 30, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [0340b4c57f](https://linux-hardware.org/?probe=0340b4c57f) | Jul 30, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [e134bae415](https://linux-hardware.org/?probe=e134bae415) | Jul 29, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [e436ae3019](https://linux-hardware.org/?probe=e436ae3019) | Jul 23, 2021 |
| ASUSTek       | X550ZE                      | Notebook    | [49cd19882f](https://linux-hardware.org/?probe=49cd19882f) | Jul 23, 2021 |
| HP            | Spectre x360 Convertible... | Convertible | [cfaf6bb9ab](https://linux-hardware.org/?probe=cfaf6bb9ab) | Jul 21, 2021 |
| Lenovo        | Legion 5 Pro 16ACH6H 82J... | Notebook    | [83c21e1a99](https://linux-hardware.org/?probe=83c21e1a99) | Jul 21, 2021 |
| Notebook      | W54_W550SU2                 | Notebook    | [b026148da5](https://linux-hardware.org/?probe=b026148da5) | Jul 15, 2021 |
| Dell          | Inspiron 3501               | Notebook    | [f72a03865c](https://linux-hardware.org/?probe=f72a03865c) | Jul 11, 2021 |
| HP            | Pavilion Laptop 14-dv0xx... | Notebook    | [c65f4896a2](https://linux-hardware.org/?probe=c65f4896a2) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [2878014d7a](https://linux-hardware.org/?probe=2878014d7a) | Jul 11, 2021 |
| Sony          | VPCSB1C5E                   | Notebook    | [4cfb82cbfe](https://linux-hardware.org/?probe=4cfb82cbfe) | Jul 11, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [826edd51bc](https://linux-hardware.org/?probe=826edd51bc) | Jul 07, 2021 |
| Lenovo        | Legion 5 15IMH05 82AU       | Notebook    | [cab06ed3ed](https://linux-hardware.org/?probe=cab06ed3ed) | Jul 01, 2021 |
| Gigabyte      | X470 AORUS ULTRA GAMING-... | Desktop     | [aa05cca9b7](https://linux-hardware.org/?probe=aa05cca9b7) | Jun 30, 2021 |
| Biostar       | H310MHP                     | Desktop     | [0d3f648f3e](https://linux-hardware.org/?probe=0d3f648f3e) | Jun 30, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [cc5fd0194e](https://linux-hardware.org/?probe=cc5fd0194e) | Jun 26, 2021 |
| Lenovo        | SHARKBAY SDK0E50510 WIN     | Desktop     | [fb3d7de63c](https://linux-hardware.org/?probe=fb3d7de63c) | Jun 26, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [486775a989](https://linux-hardware.org/?probe=486775a989) | Jun 23, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [4629f86f56](https://linux-hardware.org/?probe=4629f86f56) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [69dea4e3cf](https://linux-hardware.org/?probe=69dea4e3cf) | Jun 22, 2021 |
| MSI           | A320M-HDV R4.0              | Desktop     | [2fd89c951e](https://linux-hardware.org/?probe=2fd89c951e) | Jun 22, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [11e99b82d5](https://linux-hardware.org/?probe=11e99b82d5) | Jun 22, 2021 |
| MSI           | X370 GAMING PRO CARBON      | Desktop     | [9ead1e1bb5](https://linux-hardware.org/?probe=9ead1e1bb5) | Jun 22, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [8144c83b50](https://linux-hardware.org/?probe=8144c83b50) | Jun 22, 2021 |
| Dell          | Inspiron N5050              | Notebook    | [92ae7459b4](https://linux-hardware.org/?probe=92ae7459b4) | Jun 20, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [376c0ff95d](https://linux-hardware.org/?probe=376c0ff95d) | Jun 15, 2021 |
| Gigabyte      | B550I AORUS PRO AX          | Desktop     | [34801a2f74](https://linux-hardware.org/?probe=34801a2f74) | Jun 12, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [38b9682492](https://linux-hardware.org/?probe=38b9682492) | Jun 11, 2021 |
| PC Special... | GK5NPFO                     | Notebook    | [47a7837795](https://linux-hardware.org/?probe=47a7837795) | Jun 11, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [abd01e8eac](https://linux-hardware.org/?probe=abd01e8eac) | Jun 09, 2021 |
| Dell          | Inspiron 5570               | Notebook    | [a93d77d45b](https://linux-hardware.org/?probe=a93d77d45b) | Jun 06, 2021 |
| ASUSTek       | TUF Gaming FX505DT_FX505... | Notebook    | [f794ea73e4](https://linux-hardware.org/?probe=f794ea73e4) | May 28, 2021 |
| MSI           | GE72VR 6RF                  | Notebook    | [faea47290a](https://linux-hardware.org/?probe=faea47290a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [e7fda6091a](https://linux-hardware.org/?probe=e7fda6091a) | May 26, 2021 |
| Lenovo        | IdeaPad 3 15ADA05 81W1      | Notebook    | [d2a26e0f30](https://linux-hardware.org/?probe=d2a26e0f30) | May 26, 2021 |
| ASUSTek       | ROG CROSSHAIR VII HERO      | Desktop     | [51e1e33185](https://linux-hardware.org/?probe=51e1e33185) | May 20, 2021 |
| MSI           | B350M GAMING PRO            | Desktop     | [c04e6666e7](https://linux-hardware.org/?probe=c04e6666e7) | May 20, 2021 |
| Dell          | 0D28YY A02                  | Desktop     | [14edf3bd00](https://linux-hardware.org/?probe=14edf3bd00) | May 16, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [ffc46c9472](https://linux-hardware.org/?probe=ffc46c9472) | May 14, 2021 |
| Acer          | Spin SP513-54N              | Convertible | [aa8934716b](https://linux-hardware.org/?probe=aa8934716b) | May 13, 2021 |
| Gigabyte      | A320M-S2H-CF                | Desktop     | [066f815622](https://linux-hardware.org/?probe=066f815622) | May 12, 2021 |
| HP            | 844C                        | Desktop     | [29f7cf64ce](https://linux-hardware.org/?probe=29f7cf64ce) | May 06, 2021 |
| HP            | 844C                        | Desktop     | [0534f06ec4](https://linux-hardware.org/?probe=0534f06ec4) | May 06, 2021 |
| Alienware     | 17 R3                       | Notebook    | [f9ee772f9e](https://linux-hardware.org/?probe=f9ee772f9e) | May 05, 2021 |
| ASUSTek       | PRIME Z590-A                | Desktop     | [cb3058760e](https://linux-hardware.org/?probe=cb3058760e) | May 04, 2021 |
| Gigabyte      | P67A-UD3-B3                 | Desktop     | [08ea956bfa](https://linux-hardware.org/?probe=08ea956bfa) | Apr 24, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d9bf75c99c](https://linux-hardware.org/?probe=d9bf75c99c) | Apr 23, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [22931f83cc](https://linux-hardware.org/?probe=22931f83cc) | Apr 20, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [25808be952](https://linux-hardware.org/?probe=25808be952) | Apr 19, 2021 |
| Lenovo        | IdeaPad Gaming 3 15ARH05... | Notebook    | [3c7f354ce4](https://linux-hardware.org/?probe=3c7f354ce4) | Apr 19, 2021 |
| Lenovo        | IdeaPad Slim 1-14AST-05 ... | Notebook    | [d97babb331](https://linux-hardware.org/?probe=d97babb331) | Apr 18, 2021 |
| ASUSTek       | GL503VM                     | Notebook    | [743ff3a2aa](https://linux-hardware.org/?probe=743ff3a2aa) | Apr 18, 2021 |
| Medion        | P861X                       | Notebook    | [109599a6f6](https://linux-hardware.org/?probe=109599a6f6) | Apr 15, 2021 |
| Medion        | P861X                       | Notebook    | [ae05cea55d](https://linux-hardware.org/?probe=ae05cea55d) | Apr 15, 2021 |
| Medion        | E7419 MD60025               | Notebook    | [4deb77ef82](https://linux-hardware.org/?probe=4deb77ef82) | Apr 10, 2021 |
| MSI           | Z87 MPOWER                  | Desktop     | [ff6aa3811c](https://linux-hardware.org/?probe=ff6aa3811c) | Apr 08, 2021 |
| ASUSTek       | ROG Strix G512LW_G512LW     | Notebook    | [2012ac3d84](https://linux-hardware.org/?probe=2012ac3d84) | Apr 07, 2021 |
| Dell          | Inspiron 5755               | Notebook    | [ae6589874e](https://linux-hardware.org/?probe=ae6589874e) | Apr 07, 2021 |
| HP            | 2B3B                        | All in one  | [1a5d2c36ec](https://linux-hardware.org/?probe=1a5d2c36ec) | Apr 06, 2021 |
| Acer          | Nitro AN515-44              | Notebook    | [9f68dee6f5](https://linux-hardware.org/?probe=9f68dee6f5) | Apr 04, 2021 |
| HP            | Pavilion Gaming Laptop 1... | Notebook    | [2af0a44c72](https://linux-hardware.org/?probe=2af0a44c72) | Apr 04, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [23502edac5](https://linux-hardware.org/?probe=23502edac5) | Apr 01, 2021 |
| ASRock        | AB350M-HDV                  | Desktop     | [13b2fdddc0](https://linux-hardware.org/?probe=13b2fdddc0) | Apr 01, 2021 |
| Dell          | 07KY25 A01                  | Desktop     | [8c4f2f9922](https://linux-hardware.org/?probe=8c4f2f9922) | Mar 31, 2021 |
| Medion        | E7419 MD60025               | Notebook    | [938494cf89](https://linux-hardware.org/?probe=938494cf89) | Mar 31, 2021 |
| Dell          | 07KY25 A01                  | Desktop     | [1b9efb1b29](https://linux-hardware.org/?probe=1b9efb1b29) | Mar 24, 2021 |
| Lenovo        | ThinkPad T470 20HD000RUS    | Notebook    | [751dd3bb74](https://linux-hardware.org/?probe=751dd3bb74) | Mar 19, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [097a0d616c](https://linux-hardware.org/?probe=097a0d616c) | Mar 18, 2021 |
| Gigabyte      | B450 AORUS M                | Desktop     | [22054ffd75](https://linux-hardware.org/?probe=22054ffd75) | Mar 18, 2021 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1e6cbeb181](https://linux-hardware.org/?probe=1e6cbeb181) | Mar 17, 2021 |
| Acer          | Nitro AN515-54              | Notebook    | [b4580812c2](https://linux-hardware.org/?probe=b4580812c2) | Mar 15, 2021 |
| HP            | 2AF7                        | Desktop     | [e0639ea4a5](https://linux-hardware.org/?probe=e0639ea4a5) | Mar 11, 2021 |
| HP            | 2AF7                        | Desktop     | [fb8d76722c](https://linux-hardware.org/?probe=fb8d76722c) | Mar 11, 2021 |
| Dell          | System XPS L702X            | Notebook    | [e3af15a170](https://linux-hardware.org/?probe=e3af15a170) | Mar 09, 2021 |
| Dell          | System XPS L702X            | Notebook    | [7fb3f476cf](https://linux-hardware.org/?probe=7fb3f476cf) | Mar 09, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [3741826c9a](https://linux-hardware.org/?probe=3741826c9a) | Mar 08, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [c1f22a7521](https://linux-hardware.org/?probe=c1f22a7521) | Mar 05, 2021 |
| Gigabyte      | GA-MA790FXT-UD5P            | Desktop     | [404dab2464](https://linux-hardware.org/?probe=404dab2464) | Feb 27, 2021 |
| HP            | OMEN Laptop 15-en0xxx       | Notebook    | [29784f5b45](https://linux-hardware.org/?probe=29784f5b45) | Feb 23, 2021 |
| ASRock        | FM2A88X Extreme6+           | Desktop     | [13f9fc2ef3](https://linux-hardware.org/?probe=13f9fc2ef3) | Feb 18, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [c7e8878f7b](https://linux-hardware.org/?probe=c7e8878f7b) | Feb 18, 2021 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [2e19f3b1af](https://linux-hardware.org/?probe=2e19f3b1af) | Feb 18, 2021 |
| Lenovo        | ThinkPad T440p 20AWS4RC0... | Notebook    | [3e146ba45b](https://linux-hardware.org/?probe=3e146ba45b) | Feb 18, 2021 |
| ASUSTek       | TUF Gaming FX505DD_FX505... | Notebook    | [de3199a457](https://linux-hardware.org/?probe=de3199a457) | Feb 17, 2021 |
| Dell          | 0C2KJT A00                  | Desktop     | [f821a0035b](https://linux-hardware.org/?probe=f821a0035b) | Feb 12, 2021 |
| ASUSTek       | PRIME B360M-K               | Desktop     | [b73941c431](https://linux-hardware.org/?probe=b73941c431) | Feb 08, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [92487a475d](https://linux-hardware.org/?probe=92487a475d) | Feb 06, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [1bdd227b6f](https://linux-hardware.org/?probe=1bdd227b6f) | Feb 02, 2021 |
| HP            | 1825                        | Desktop     | [3b6b80db46](https://linux-hardware.org/?probe=3b6b80db46) | Jan 31, 2021 |
| HP            | 1825                        | Desktop     | [1df894dea4](https://linux-hardware.org/?probe=1df894dea4) | Jan 31, 2021 |
| Dell          | Latitude E6520              | Notebook    | [24cbaa1c59](https://linux-hardware.org/?probe=24cbaa1c59) | Jan 30, 2021 |
| HP            | Pavilion Laptop 15-cs0xx... | Notebook    | [793615c0de](https://linux-hardware.org/?probe=793615c0de) | Jan 30, 2021 |
| Lenovo        | ThinkPad T470s 20HGS0B90... | Notebook    | [dfb9858a8f](https://linux-hardware.org/?probe=dfb9858a8f) | Jan 29, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [dd3793c498](https://linux-hardware.org/?probe=dd3793c498) | Jan 28, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [36eaf717e9](https://linux-hardware.org/?probe=36eaf717e9) | Jan 26, 2021 |
| ASRock        | X470 Master SLI             | Desktop     | [b1be9375c0](https://linux-hardware.org/?probe=b1be9375c0) | Jan 24, 2021 |
| ASUSTek       | ROG STRIX X570-E GAMING     | Desktop     | [7332b50f98](https://linux-hardware.org/?probe=7332b50f98) | Jan 24, 2021 |
| Dell          | XPS 15 9500                 | Notebook    | [11b9018ef1](https://linux-hardware.org/?probe=11b9018ef1) | Jan 23, 2021 |
| ASUSTek       | PRIME H270-PLUS             | Desktop     | [3f895b585b](https://linux-hardware.org/?probe=3f895b585b) | Jan 22, 2021 |
| Lenovo        | SHARKBAY 0B98401 PRO        | Desktop     | [61976e9745](https://linux-hardware.org/?probe=61976e9745) | Jan 18, 2021 |
| HP            | Compaq 6735b                | Notebook    | [84a4616a8d](https://linux-hardware.org/?probe=84a4616a8d) | Jan 18, 2021 |
| Fujitsu Si... | ESPRIMO Mobile D9500        | Notebook    | [9703bdf4f6](https://linux-hardware.org/?probe=9703bdf4f6) | Jan 12, 2021 |
| Unknown       | Unknown                     | Notebook    | [09f3ac6567](https://linux-hardware.org/?probe=09f3ac6567) | Jan 11, 2021 |
| MSI           | X399 SLI PLUS               | Desktop     | [e392838a54](https://linux-hardware.org/?probe=e392838a54) | Jan 10, 2021 |
| ASUSTek       | CM5671                      | Desktop     | [069344a54e](https://linux-hardware.org/?probe=069344a54e) | Jan 07, 2021 |
| HP            | EliteBook 8540p             | Notebook    | [a5612ca66a](https://linux-hardware.org/?probe=a5612ca66a) | Jan 07, 2021 |
| MSI           | B85-G43 GAMING              | Desktop     | [8fe013f04a](https://linux-hardware.org/?probe=8fe013f04a) | Jan 04, 2021 |
| Dell          | Latitude E6430              | Notebook    | [2e0ef916c6](https://linux-hardware.org/?probe=2e0ef916c6) | Jan 03, 2021 |
| ASRock        | G41M-VS3                    | Desktop     | [e1217b1871](https://linux-hardware.org/?probe=e1217b1871) | Jan 02, 2021 |
| HP            | OMEN by Laptop 15-dc1xxx    | Notebook    | [d28d862d9f](https://linux-hardware.org/?probe=d28d862d9f) | Dec 28, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1d461bb9db](https://linux-hardware.org/?probe=1d461bb9db) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [436a2ca3ce](https://linux-hardware.org/?probe=436a2ca3ce) | Dec 25, 2020 |
| Pegatron      | 2AC2A                       | Desktop     | [2df3b195c6](https://linux-hardware.org/?probe=2df3b195c6) | Dec 25, 2020 |
| Unknown       | Unknown                     | Notebook    | [ce7f267835](https://linux-hardware.org/?probe=ce7f267835) | Dec 23, 2020 |
| Toshiba       | Satellite C55-A             | Notebook    | [43dbeef737](https://linux-hardware.org/?probe=43dbeef737) | Dec 22, 2020 |
| ASUSTek       | PRIME Z370-P                | Desktop     | [35365be0e8](https://linux-hardware.org/?probe=35365be0e8) | Dec 19, 2020 |
| Notebook      | N85_N87,HJ,HJ1,HK1          | Notebook    | [b02c7cd17e](https://linux-hardware.org/?probe=b02c7cd17e) | Dec 19, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [ea7a52fdac](https://linux-hardware.org/?probe=ea7a52fdac) | Dec 16, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [62a5c95d51](https://linux-hardware.org/?probe=62a5c95d51) | Dec 14, 2020 |
| HP            | 8643 SMVB                   | Desktop     | [dccfba36f1](https://linux-hardware.org/?probe=dccfba36f1) | Dec 06, 2020 |
| Gigabyte      | B450 AORUS ELITE            | Desktop     | [2a35d394f9](https://linux-hardware.org/?probe=2a35d394f9) | Dec 04, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [05e3eb32c9](https://linux-hardware.org/?probe=05e3eb32c9) | Dec 03, 2020 |
| HP            | Laptop 17-ak0xx             | Notebook    | [e63bb99c0a](https://linux-hardware.org/?probe=e63bb99c0a) | Nov 30, 2020 |
| MSI           | Z390-A PRO                  | Desktop     | [dc6ea9bfb8](https://linux-hardware.org/?probe=dc6ea9bfb8) | Nov 29, 2020 |
| ASUSTek       | M5A97 LE R2.0               | Desktop     | [d4b3f84c86](https://linux-hardware.org/?probe=d4b3f84c86) | Nov 28, 2020 |
| Lenovo        | ThinkPad T14 Gen 1 20UDS... | Notebook    | [05a70db99a](https://linux-hardware.org/?probe=05a70db99a) | Nov 22, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [a3d68dc126](https://linux-hardware.org/?probe=a3d68dc126) | Nov 19, 2020 |
| Gigabyte      | B450 AORUS M                | Desktop     | [d9faeae0d4](https://linux-hardware.org/?probe=d9faeae0d4) | Nov 19, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [11c79940a4](https://linux-hardware.org/?probe=11c79940a4) | Nov 19, 2020 |
| Dell          | Inspiron 15 7000 Gaming     | Notebook    | [1ff8a24823](https://linux-hardware.org/?probe=1ff8a24823) | Nov 18, 2020 |
| HP            | 18E7                        | Desktop     | [f84cbfd465](https://linux-hardware.org/?probe=f84cbfd465) | Nov 10, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [79608bd849](https://linux-hardware.org/?probe=79608bd849) | Nov 06, 2020 |
| Dell          | Latitude E6430              | Notebook    | [760e7ca474](https://linux-hardware.org/?probe=760e7ca474) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [e80ddac12f](https://linux-hardware.org/?probe=e80ddac12f) | Nov 02, 2020 |
| ASUSTek       | ROG STRIX B550-F GAMING     | Desktop     | [876b039494](https://linux-hardware.org/?probe=876b039494) | Nov 01, 2020 |
| Gigabyte      | X570 AORUS PRO WIFI         | Desktop     | [4e573bc6ff](https://linux-hardware.org/?probe=4e573bc6ff) | Oct 28, 2020 |
| MSI           | MPG B550 GAMING EDGE WIF... | Desktop     | [4b9d2b77cb](https://linux-hardware.org/?probe=4b9d2b77cb) | Oct 26, 2020 |
| ASUSTek       | PRIME X399-A                | Desktop     | [b7772d9ff8](https://linux-hardware.org/?probe=b7772d9ff8) | Oct 13, 2020 |
| Dell          | 0R6JMP A00                  | Desktop     | [c4cbec5b80](https://linux-hardware.org/?probe=c4cbec5b80) | Oct 11, 2020 |
| OEM           | Unknown                     | Desktop     | [2e7a212437](https://linux-hardware.org/?probe=2e7a212437) | Sep 26, 2020 |
| Lenovo        | ThinkCentre M91p 7033CG1    | Desktop     | [c08fed8ecb](https://linux-hardware.org/?probe=c08fed8ecb) | Sep 11, 2020 |
| Samsung       | 350V5C/351V5C/3540VC/344... | Notebook    | [4a3037422e](https://linux-hardware.org/?probe=4a3037422e) | Sep 04, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [7b8babe846](https://linux-hardware.org/?probe=7b8babe846) | Aug 27, 2020 |
| ASUSTek       | Maximus VIII FORMULA        | Desktop     | [73462df387](https://linux-hardware.org/?probe=73462df387) | Aug 07, 2020 |
| HP            | 450                         | Notebook    | [edeb9f6780](https://linux-hardware.org/?probe=edeb9f6780) | Apr 25, 2020 |

...

See full list of test cases in the file [Test_Cases.md](</Dist/Garuda_Linux/All/Test_Cases.md>).

System
------

OS
--

Installed operating systems

![OS](./images/pie_chart/os_name.svg)


| Name                 | Computers | Percent |
|----------------------|-----------|---------|
| Garuda Linux Soaring | 280       | 63.06%  |
| Garuda Linux         | 107       | 24.1%   |
| Garuda Linux Rolling | 57        | 12.84%  |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| Garuda Linux | 436       | 100%    |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version            | Computers | Percent |
|--------------------|-----------|---------|
| 6.1.1-zen1-1-zen   | 13        | 2.55%   |
| 6.0.2-zen1-1-zen   | 11        | 2.16%   |
| 5.17.1-zen1-1-zen  | 9         | 1.76%   |
| 5.15.2-zen1-1-zen  | 7         | 1.37%   |
| 5.14.14-zen1-1-zen | 7         | 1.37%   |
| 6.2.10-zen1-1-zen  | 6         | 1.18%   |
| 5.17.9-zen1-1-zen  | 6         | 1.18%   |
| 5.16.4-zen1-1-zen  | 6         | 1.18%   |
| 6.2.7-zen1-1-zen   | 5         | 0.98%   |
| 6.2.12-zen1-1-zen  | 5         | 0.98%   |
| 6.1.7-zen1-1-zen   | 5         | 0.98%   |
| 6.0.9-zen1-1-zen   | 5         | 0.98%   |
| 6.0.8-zen1-1-zen   | 5         | 0.98%   |
| 6.0.12-zen1-1-zen  | 5         | 0.98%   |
| 5.18.16-zen1-1-zen | 5         | 0.98%   |
| 5.15.7-zen1-1-zen  | 5         | 0.98%   |
| 5.15.13-zen1-1-zen | 5         | 0.98%   |
| 5.15.12-zen1-1-zen | 5         | 0.98%   |
| 5.13.9-zen1-1-zen  | 5         | 0.98%   |
| 5.13.13-zen1-1-zen | 5         | 0.98%   |
| 5.11.16-zen1-1-zen | 5         | 0.98%   |
| 5.11.11-zen1-1-zen | 5         | 0.98%   |
| 6.3.2-zen1-1-zen   | 4         | 0.78%   |
| 6.2.13-zen-1-zen   | 4         | 0.78%   |
| 6.1.12-zen1-1-zen  | 4         | 0.78%   |
| 6.0.6-zen1-1-zen   | 4         | 0.78%   |
| 6.0.11-zen1-1-zen  | 4         | 0.78%   |
| 6.0.10-zen2-1-zen  | 4         | 0.78%   |
| 5.19.7-zen2-1-zen  | 4         | 0.78%   |
| 5.18.6-zen1-1-zen  | 4         | 0.78%   |
| 5.18.12-zen1-1-zen | 4         | 0.78%   |
| 5.18.1-zen1-1-zen  | 4         | 0.78%   |
| 5.17.3-zen1-1-zen  | 4         | 0.78%   |
| 5.16.2-zen1-1-zen  | 4         | 0.78%   |
| 5.16.16-zen1-1-zen | 4         | 0.78%   |
| 5.15.6-zen2-1-zen  | 4         | 0.78%   |
| 5.10.4-107-tkg-bmq | 4         | 0.78%   |
| 5.10.1-103-tkg-bmq | 4         | 0.78%   |
| 6.3.1-zen2-1-zen   | 3         | 0.59%   |
| 6.2.9-zen1-1-zen   | 3         | 0.59%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 6.1.1   | 14        | 2.75%   |
| 6.0.2   | 12        | 2.35%   |
| 5.17.1  | 11        | 2.16%   |
| 6.2.10  | 7         | 1.37%   |
| 5.15.2  | 7         | 1.37%   |
| 5.14.14 | 7         | 1.37%   |
| 6.2.7   | 6         | 1.18%   |
| 6.1.9   | 6         | 1.18%   |
| 6.0.8   | 6         | 1.18%   |
| 5.18.16 | 6         | 1.18%   |
| 5.17.9  | 6         | 1.18%   |
| 5.17.5  | 6         | 1.18%   |
| 5.17.3  | 6         | 1.18%   |
| 5.16.4  | 6         | 1.18%   |
| 5.15.7  | 6         | 1.18%   |
| 5.11.11 | 6         | 1.18%   |
| 5.10.4  | 6         | 1.18%   |
| 6.3.1   | 5         | 0.98%   |
| 6.2.12  | 5         | 0.98%   |
| 6.1.7   | 5         | 0.98%   |
| 6.0.9   | 5         | 0.98%   |
| 6.0.12  | 5         | 0.98%   |
| 6.0.11  | 5         | 0.98%   |
| 6.0.10  | 5         | 0.98%   |
| 5.19.7  | 5         | 0.98%   |
| 5.16.5  | 5         | 0.98%   |
| 5.16.2  | 5         | 0.98%   |
| 5.15.13 | 5         | 0.98%   |
| 5.15.12 | 5         | 0.98%   |
| 5.13.9  | 5         | 0.98%   |
| 5.13.13 | 5         | 0.98%   |
| 5.11.16 | 5         | 0.98%   |
| 6.3.2   | 4         | 0.78%   |
| 6.2.2   | 4         | 0.78%   |
| 6.2.13  | 4         | 0.78%   |
| 6.1.4   | 4         | 0.78%   |
| 6.1.3   | 4         | 0.78%   |
| 6.1.12  | 4         | 0.78%   |
| 6.0.6   | 4         | 0.78%   |
| 5.19.2  | 4         | 0.78%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.15    | 54        | 11.02%  |
| 6.1     | 48        | 9.8%    |
| 6.0     | 48        | 9.8%    |
| 5.16    | 41        | 8.37%   |
| 5.18    | 36        | 7.35%   |
| 5.10    | 36        | 7.35%   |
| 6.2     | 35        | 7.14%   |
| 5.19    | 32        | 6.53%   |
| 5.17    | 31        | 6.33%   |
| 5.14    | 27        | 5.51%   |
| 5.12    | 23        | 4.69%   |
| 5.11    | 23        | 4.69%   |
| 5.13    | 21        | 4.29%   |
| 6.3     | 15        | 3.06%   |
| 5.9     | 13        | 2.65%   |
| 5.8     | 5         | 1.02%   |
| 5.6     | 1         | 0.2%    |
| 5.4     | 1         | 0.2%    |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 436       | 100%    |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| KDE5              | 299       | 67.65%  |
| GNOME             | 52        | 11.76%  |
| KDE               | 34        | 7.69%   |
| XFCE              | 18        | 4.07%   |
| X-Cinnamon        | 12        | 2.71%   |
| sway              | 7         | 1.58%   |
| Deepin            | 3         | 0.68%   |
| Unknown           | 3         | 0.68%   |
| qtile-default     | 2         | 0.45%   |
| MATE              | 2         | 0.45%   |
| LXQt              | 2         | 0.45%   |
| i3                | 2         | 0.45%   |
| Yaru:ubuntu:GNOME | 1         | 0.23%   |
| Unity             | 1         | 0.23%   |
| qtile             | 1         | 0.23%   |
| Cinnamon          | 1         | 0.23%   |
| Budgie            | 1         | 0.23%   |
| awesome           | 1         | 0.23%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 392       | 88.69%  |
| Wayland | 31        | 7.01%   |
| Tty     | 10        | 2.26%   |
| Unknown | 9         | 2.04%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| SDDM    | 211       | 47.85%  |
| Unknown | 159       | 36.05%  |
| LightDM | 39        | 8.84%   |
| GDM     | 27        | 6.12%   |
| GREETD  | 5         | 1.13%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang  | Computers | Percent |
|-------|-----------|---------|
| en_US | 227       | 51.59%  |
| en_GB | 42        | 9.55%   |
| de_DE | 35        | 7.95%   |
| en_IN | 21        | 4.77%   |
| it_IT | 13        | 2.95%   |
| en_CA | 12        | 2.73%   |
| pt_BR | 9         | 2.05%   |
| es_ES | 8         | 1.82%   |
| pl_PL | 6         | 1.36%   |
| nl_NL | 6         | 1.36%   |
| ru_RU | 5         | 1.14%   |
| tr_TR | 4         | 0.91%   |
| fr_FR | 4         | 0.91%   |
| es_MX | 4         | 0.91%   |
| en_AU | 4         | 0.91%   |
| en_ZA | 3         | 0.68%   |
| de_AT | 3         | 0.68%   |
| sv_SE | 2         | 0.45%   |
| sk_SK | 2         | 0.45%   |
| fr_BE | 2         | 0.45%   |
| fi_FI | 2         | 0.45%   |
| es_VE | 2         | 0.45%   |
| es_EC | 2         | 0.45%   |
| es_CO | 2         | 0.45%   |
| en_DK | 2         | 0.45%   |
| en_AG | 2         | 0.45%   |
| da_DK | 2         | 0.45%   |
| zh_CN | 1         | 0.23%   |
| uk_UA | 1         | 0.23%   |
| nl_BE | 1         | 0.23%   |
| nb_NO | 1         | 0.23%   |
| ko_KR | 1         | 0.23%   |
| ja_JP | 1         | 0.23%   |
| iu_CA | 1         | 0.23%   |
| hu_HU | 1         | 0.23%   |
| es_AR | 1         | 0.23%   |
| en_DE | 1         | 0.23%   |
| el_GR | 1         | 0.23%   |
| de_CH | 1         | 0.23%   |
| cs_CZ | 1         | 0.23%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| EFI  | 266       | 60.59%  |
| BIOS | 173       | 39.41%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 421       | 96.56%  |
| Overlay | 9         | 2.06%   |
| Ext4    | 2         | 0.46%   |
| XXXXX   | 1         | 0.23%   |
| Xfs     | 1         | 0.23%   |
| Tmpfs   | 1         | 0.23%   |
| F2fs    | 1         | 0.23%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 263       | 59.91%  |
| Unknown | 157       | 35.76%  |
| MBR     | 19        | 4.33%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 380       | 85.97%  |
| Yes       | 62        | 14.03%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 298       | 67.57%  |
| Yes       | 143       | 32.43%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                                 | Computers | Percent |
|--------------------------------------|-----------|---------|
| ASUSTek Computer                     | 87        | 19.95%  |
| Lenovo                               | 66        | 15.14%  |
| Hewlett-Packard                      | 59        | 13.53%  |
| MSI                                  | 41        | 9.4%    |
| Dell                                 | 39        | 8.94%   |
| Gigabyte Technology                  | 30        | 6.88%   |
| Acer                                 | 30        | 6.88%   |
| ASRock                               | 17        | 3.9%    |
| Apple                                | 8         | 1.83%   |
| Samsung Electronics                  | 5         | 1.15%   |
| Unknown                              | 4         | 0.92%   |
| Razer                                | 3         | 0.69%   |
| Notebook                             | 3         | 0.69%   |
| Medion                               | 3         | 0.69%   |
| Intel                                | 3         | 0.69%   |
| HUAWEI                               | 3         | 0.69%   |
| Fujitsu                              | 3         | 0.69%   |
| Alienware                            | 3         | 0.69%   |
| Toshiba                              | 2         | 0.46%   |
| Sony                                 | 2         | 0.46%   |
| Pegatron                             | 2         | 0.46%   |
| HONOR                                | 2         | 0.46%   |
| AZW                                  | 2         | 0.46%   |
| Win element                          | 1         | 0.23%   |
| T-bao                                | 1         | 0.23%   |
| Standard                             | 1         | 0.23%   |
| Shenzhen Meigao Electronic Equipment | 1         | 0.23%   |
| PC Specialist                        | 1         | 0.23%   |
| Panasonic                            | 1         | 0.23%   |
| OEM                                  | 1         | 0.23%   |
| Monster                              | 1         | 0.23%   |
| MobileDemand                         | 1         | 0.23%   |
| Microsoft                            | 1         | 0.23%   |
| MICROBYTE                            | 1         | 0.23%   |
| Kogan                                | 1         | 0.23%   |
| GPU Company                          | 1         | 0.23%   |
| Google                               | 1         | 0.23%   |
| Fujitsu Siemens                      | 1         | 0.23%   |
| Chuwi                                | 1         | 0.23%   |
| Casper                               | 1         | 0.23%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                       | Computers | Percent |
|--------------------------------------------|-----------|---------|
| Unknown                                    | 8         | 1.83%   |
| ASUS TUF Gaming X570-PLUS                  | 6         | 1.38%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY       | 5         | 1.15%   |
| MSI MS-7C91                                | 3         | 0.69%   |
| MSI MS-7B86                                | 3         | 0.69%   |
| ASUS All Series                            | 3         | 0.69%   |
| Apple MacBookPro9,2                        | 3         | 0.69%   |
| Lenovo ThinkPad W530 24474KG               | 2         | 0.46%   |
| HUAWEI HVY-WXX9                            | 2         | 0.46%   |
| HP ProBook 640 G1                          | 2         | 0.46%   |
| HP Pavilion Gaming Laptop 15-cx0xxx        | 2         | 0.46%   |
| HP Pavilion dv6                            | 2         | 0.46%   |
| HP Notebook                                | 2         | 0.46%   |
| HP Laptop 15-dy2xxx                        | 2         | 0.46%   |
| Gigabyte X570 AORUS PRO WIFI               | 2         | 0.46%   |
| Gigabyte G5 MD                             | 2         | 0.46%   |
| Gigabyte AB350-Gaming 3                    | 2         | 0.46%   |
| Dell XPS 15 9500                           | 2         | 0.46%   |
| Dell Latitude E6420                        | 2         | 0.46%   |
| Dell Inspiron 3668                         | 2         | 0.46%   |
| Dell Inspiron 15 7000 Gaming               | 2         | 0.46%   |
| AZW SER                                    | 2         | 0.46%   |
| ASUS ROG STRIX X570-E GAMING               | 2         | 0.46%   |
| ASUS ROG STRIX B550-F GAMING               | 2         | 0.46%   |
| ASUS ROG Flow X13 GV301QH_GV301QH          | 2         | 0.46%   |
| ASUS PRIME X570-P                          | 2         | 0.46%   |
| Apple Macmini6,1                           | 2         | 0.46%   |
| Acer Nitro AN515-44                        | 2         | 0.46%   |
| Acer Aspire A515-51G                       | 2         | 0.46%   |
| Win element M600                           | 1         | 0.23%   |
| Toshiba Satellite E45DW-C                  | 1         | 0.23%   |
| Toshiba Satellite C55-A                    | 1         | 0.23%   |
| T-bao MINI PC                              | 1         | 0.23%   |
| Sony VPCSB1C5E                             | 1         | 0.23%   |
| Sony SVF1521Q1EW                           | 1         | 0.23%   |
| Shenzhen Meigao Electronic Equipment UM690 | 1         | 0.23%   |
| Samsung R530/R730                          | 1         | 0.23%   |
| Samsung 730QDA                             | 1         | 0.23%   |
| Samsung 550XCJ/550XCR                      | 1         | 0.23%   |
| Samsung 340XAA/350XAA/550XAA               | 1         | 0.23%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 20        | 4.59%   |
| Lenovo ThinkPad    | 19        | 4.36%   |
| ASUS ROG           | 19        | 4.36%   |
| Acer Aspire        | 17        | 3.9%    |
| Dell Inspiron      | 15        | 3.44%   |
| HP Pavilion        | 14        | 3.21%   |
| ASUS PRIME         | 12        | 2.75%   |
| ASUS VivoBook      | 11        | 2.52%   |
| ASUS TUF           | 11        | 2.52%   |
| Dell Latitude      | 9         | 2.06%   |
| Lenovo Legion      | 8         | 1.83%   |
| HP Laptop          | 8         | 1.83%   |
| Unknown            | 8         | 1.83%   |
| HP OMEN            | 6         | 1.38%   |
| Dell XPS           | 6         | 1.38%   |
| Lenovo ThinkCentre | 5         | 1.15%   |
| Acer Nitro         | 5         | 1.15%   |
| Lenovo Yoga        | 4         | 0.92%   |
| HP EliteBook       | 4         | 0.92%   |
| Gigabyte X570      | 4         | 0.92%   |
| Dell Precision     | 4         | 0.92%   |
| Acer Swift         | 4         | 0.92%   |
| Razer Blade        | 3         | 0.69%   |
| MSI MS-7C91        | 3         | 0.69%   |
| MSI MS-7B86        | 3         | 0.69%   |
| HP ProBook         | 3         | 0.69%   |
| Gigabyte G5        | 3         | 0.69%   |
| Gigabyte B550      | 3         | 0.69%   |
| Gigabyte B450      | 3         | 0.69%   |
| Dell OptiPlex      | 3         | 0.69%   |
| ASUS ZenBook       | 3         | 0.69%   |
| ASUS ASUS          | 3         | 0.69%   |
| ASUS All           | 3         | 0.69%   |
| Apple MacBookPro9  | 3         | 0.69%   |
| Toshiba Satellite  | 2         | 0.46%   |
| MSI GF63           | 2         | 0.46%   |
| HUAWEI HVY-WXX9    | 2         | 0.46%   |
| HP Victus          | 2         | 0.46%   |
| HP Notebook        | 2         | 0.46%   |
| HP ENVY            | 2         | 0.46%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2020 | 75        | 17.2%   |
| 2021 | 58        | 13.3%   |
| 2019 | 51        | 11.7%   |
| 2018 | 40        | 9.17%   |
| 2017 | 36        | 8.26%   |
| 2012 | 26        | 5.96%   |
| 2022 | 25        | 5.73%   |
| 2013 | 25        | 5.73%   |
| 2016 | 24        | 5.5%    |
| 2014 | 24        | 5.5%    |
| 2011 | 18        | 4.13%   |
| 2015 | 15        | 3.44%   |
| 2010 | 6         | 1.38%   |
| 2009 | 6         | 1.38%   |
| 2008 | 4         | 0.92%   |
| 2007 | 2         | 0.46%   |
| 2023 | 1         | 0.23%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 244       | 55.96%  |
| Desktop     | 166       | 38.07%  |
| Convertible | 14        | 3.21%   |
| All in one  | 5         | 1.15%   |
| Mini pc     | 4         | 0.92%   |
| Tablet      | 3         | 0.69%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 436       | 100%    |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 435       | 99.77%  |
| Yes  | 1         | 0.23%   |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 16.01-24.0  | 112       | 25.4%   |
| 4.01-8.0    | 99        | 22.45%  |
| 8.01-16.0   | 96        | 21.77%  |
| 32.01-64.0  | 72        | 16.33%  |
| 3.01-4.0    | 27        | 6.12%   |
| 24.01-32.0  | 18        | 4.08%   |
| 64.01-256.0 | 16        | 3.63%   |
| 2.01-3.0    | 1         | 0.23%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 4.01-8.0   | 165       | 35.11%  |
| 3.01-4.0   | 111       | 23.62%  |
| 2.01-3.0   | 100       | 21.28%  |
| 8.01-16.0  | 51        | 10.85%  |
| 1.01-2.0   | 34        | 7.23%   |
| 16.01-24.0 | 6         | 1.28%   |
| 32.01-64.0 | 2         | 0.43%   |
| 0.51-1.0   | 1         | 0.21%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 198       | 44%     |
| 2      | 138       | 30.67%  |
| 3      | 58        | 12.89%  |
| 4      | 26        | 5.78%   |
| 5      | 14        | 3.11%   |
| 6      | 7         | 1.56%   |
| 9      | 4         | 0.89%   |
| 18     | 1         | 0.22%   |
| 14     | 1         | 0.22%   |
| 11     | 1         | 0.22%   |
| 7      | 1         | 0.22%   |
| 0      | 1         | 0.22%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 328       | 74.55%  |
| Yes       | 112       | 25.45%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 360       | 82.38%  |
| No        | 77        | 17.62%  |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 358       | 81.18%  |
| No        | 83        | 18.82%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 322       | 73.18%  |
| No        | 118       | 26.82%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| USA          | 130       | 29.61%  |
| Germany      | 50        | 11.39%  |
| India        | 24        | 5.47%   |
| UK           | 23        | 5.24%   |
| Italy        | 23        | 5.24%   |
| Canada       | 18        | 4.1%    |
| Brazil       | 15        | 3.42%   |
| Poland       | 12        | 2.73%   |
| Spain        | 10        | 2.28%   |
| Netherlands  | 10        | 2.28%   |
| Romania      | 7         | 1.59%   |
| Mexico       | 7         | 1.59%   |
| France       | 7         | 1.59%   |
| Belgium      | 7         | 1.59%   |
| Turkey       | 6         | 1.37%   |
| Sweden       | 6         | 1.37%   |
| Russia       | 6         | 1.37%   |
| Denmark      | 5         | 1.14%   |
| Australia    | 5         | 1.14%   |
| Switzerland  | 4         | 0.91%   |
| South Africa | 4         | 0.91%   |
| Finland      | 4         | 0.91%   |
| Latvia       | 3         | 0.68%   |
| Austria      | 3         | 0.68%   |
| Venezuela    | 2         | 0.46%   |
| Slovakia     | 2         | 0.46%   |
| Singapore    | 2         | 0.46%   |
| Serbia       | 2         | 0.46%   |
| Puerto Rico  | 2         | 0.46%   |
| Portugal     | 2         | 0.46%   |
| Norway       | 2         | 0.46%   |
| Kuwait       | 2         | 0.46%   |
| Japan        | 2         | 0.46%   |
| Hungary      | 2         | 0.46%   |
| Greece       | 2         | 0.46%   |
| Ecuador      | 2         | 0.46%   |
| Czechia      | 2         | 0.46%   |
| Colombia     | 2         | 0.46%   |
| China        | 2         | 0.46%   |
| Ukraine      | 1         | 0.23%   |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City              | Computers | Percent |
|-------------------|-----------|---------|
| Milan             | 5         | 1.08%   |
| London            | 5         | 1.08%   |
| Berlin            | 5         | 1.08%   |
| Warsaw            | 4         | 0.87%   |
| Frankfurt am Main | 4         | 0.87%   |
| Düsseldorf       | 4         | 0.87%   |
| Dallas            | 4         | 0.87%   |
| Cape Town         | 4         | 0.87%   |
| San Jose          | 3         | 0.65%   |
| Riga              | 3         | 0.65%   |
| Portland          | 3         | 0.65%   |
| Mumbai            | 3         | 0.65%   |
| Los Angeles       | 3         | 0.65%   |
| Kansas City       | 3         | 0.65%   |
| Copenhagen        | 3         | 0.65%   |
| Chicago           | 3         | 0.65%   |
| Belo Horizonte    | 3         | 0.65%   |
| Wroclaw           | 2         | 0.43%   |
| Wasmes            | 2         | 0.43%   |
| Valencia          | 2         | 0.43%   |
| Turin             | 2         | 0.43%   |
| Toronto           | 2         | 0.43%   |
| Timișoara        | 2         | 0.43%   |
| Sydney            | 2         | 0.43%   |
| St Louis          | 2         | 0.43%   |
| Singapore         | 2         | 0.43%   |
| Seattle           | 2         | 0.43%   |
| Sao Paulo         | 2         | 0.43%   |
| Rotterdam         | 2         | 0.43%   |
| Pune              | 2         | 0.43%   |
| Puebla City       | 2         | 0.43%   |
| Prague            | 2         | 0.43%   |
| Plymouth          | 2         | 0.43%   |
| Peterborough      | 2         | 0.43%   |
| Oklahoma City     | 2         | 0.43%   |
| Noida             | 2         | 0.43%   |
| New York          | 2         | 0.43%   |
| New Glasgow       | 2         | 0.43%   |
| Montreal          | 2         | 0.43%   |
| Mississauga       | 2         | 0.43%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor                      | Computers | Drives | Percent |
|-----------------------------|-----------|--------|---------|
| Samsung Electronics         | 136       | 230    | 17.02%  |
| WDC                         | 110       | 160    | 13.77%  |
| Seagate                     | 108       | 151    | 13.52%  |
| SanDisk                     | 52        | 66     | 6.51%   |
| Toshiba                     | 44        | 56     | 5.51%   |
| SK hynix                    | 33        | 44     | 4.13%   |
| Crucial                     | 30        | 40     | 3.75%   |
| Kingston                    | 27        | 36     | 3.38%   |
| Intel                       | 24        | 33     | 3%      |
| Unknown                     | 20        | 21     | 2.5%    |
| HGST                        | 17        | 23     | 2.13%   |
| Hitachi                     | 16        | 16     | 2%      |
| Silicon Motion              | 12        | 12     | 1.5%    |
| Micron Technology           | 12        | 14     | 1.5%    |
| Phison                      | 10        | 11     | 1.25%   |
| SPCC                        | 9         | 9      | 1.13%   |
| PNY                         | 8         | 8      | 1%      |
| Phison Electronics          | 8         | 10     | 1%      |
| Micron/Crucial Technology   | 8         | 12     | 1%      |
| A-DATA Technology           | 8         | 12     | 1%      |
| KIOXIA                      | 7         | 9      | 0.88%   |
| China                       | 6         | 8      | 0.75%   |
| Kingston Technology Company | 5         | 5      | 0.63%   |
| Intenso                     | 5         | 6      | 0.63%   |
| OCZ                         | 4         | 4      | 0.5%    |
| LITEON                      | 4         | 4      | 0.5%    |
| Corsair                     | 4         | 7      | 0.5%    |
| XPG                         | 3         | 4      | 0.38%   |
| Transcend                   | 3         | 3      | 0.38%   |
| LITEONIT                    | 3         | 3      | 0.38%   |
| JMicron Technology          | 3         | 3      | 0.38%   |
| Emtec                       | 3         | 5      | 0.38%   |
| Apple                       | 3         | 4      | 0.38%   |
| ADATA Technology            | 3         | 5      | 0.38%   |
| Union Memory (Shenzhen)     | 2         | 2      | 0.25%   |
| TO Exter                    | 2         | 2      | 0.25%   |
| Team                        | 2         | 3      | 0.25%   |
| SABRENT                     | 2         | 4      | 0.25%   |
| Patriot                     | 2         | 2      | 0.25%   |
| Mushkin                     | 2         | 2      | 0.25%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung NVMe SSD Controller SM981/PM981/PM983 256GB | 17        | 1.87%   |
| Samsung NVMe SSD Drive 1TB                          | 12        | 1.32%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 1TB  | 10        | 1.1%    |
| Seagate ST1000LM035-1RK172 1TB                      | 9         | 0.99%   |
| Seagate ST1000LM024 HN-M101MBB 1TB                  | 9         | 0.99%   |
| Samsung SSD 860 EVO 500GB                           | 9         | 0.99%   |
| Samsung SSD 850 EVO 250GB                           | 9         | 0.99%   |
| Sandisk WD Blue SN550 NVMe SSD 512GB                | 8         | 0.88%   |
| Crucial CT1000MX500SSD1 1TB                         | 8         | 0.88%   |
| Samsung SSD 860 EVO 1TB                             | 7         | 0.77%   |
| Sandisk WD Black SN750 / PC SN730 NVMe SSD 256GB    | 6         | 0.66%   |
| Samsung SSD 970 EVO Plus 500GB                      | 6         | 0.66%   |
| Intel SSD 660P Series 512GB                         | 6         | 0.66%   |
| HGST HTS721010A9E630 1TB                            | 6         | 0.66%   |
| Seagate ST2000DM008-2FR102 2TB                      | 5         | 0.55%   |
| Seagate ST1000LM049-2GH172 1TB                      | 5         | 0.55%   |
| Seagate ST1000DM010-2EP102 1TB                      | 5         | 0.55%   |
| SanDisk SSD PLUS 1000GB                             | 5         | 0.55%   |
| Samsung NVMe SSD Drive 500GB                        | 5         | 0.55%   |
| Intel SSDPEKNU512GZ 512GB                           | 5         | 0.55%   |
| WDC WD10JPVX-22JC3T0 1TB                            | 4         | 0.44%   |
| WDC WD10EZEX-60WN4A0 1TB                            | 4         | 0.44%   |
| WDC WD10EZEX-08WN4A0 1TB                            | 4         | 0.44%   |
| Toshiba MQ01ABD100 1TB                              | 4         | 0.44%   |
| Toshiba HDWD110 1TB                                 | 4         | 0.44%   |
| Toshiba DT01ACA050 500GB                            | 4         | 0.44%   |
| SPCC Solid State Disk 512GB                         | 4         | 0.44%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller 1TB | 4         | 0.44%   |
| Seagate ST4000DM004-2CV104 4TB                      | 4         | 0.44%   |
| Seagate Portable 2TB                                | 4         | 0.44%   |
| SanDisk NVMe SSD Drive 1TB                          | 4         | 0.44%   |
| Samsung SSD 980 1TB                                 | 4         | 0.44%   |
| Samsung SSD 860 QVO 1TB                             | 4         | 0.44%   |
| Samsung SSD 860 EVO 250GB                           | 4         | 0.44%   |
| Samsung NVMe SSD Drive 1024GB                       | 4         | 0.44%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 4         | 0.44%   |
| Phison E16 PCIe4 NVMe Controller 1TB                | 4         | 0.44%   |
| Micron/Crucial P2 NVMe PCIe SSD 1TB                 | 4         | 0.44%   |
| Crucial CT500MX500SSD1 500GB                        | 4         | 0.44%   |
| WDC WDS240G2G0A-00JH30 240GB SSD                    | 3         | 0.33%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 103       | 144    | 39.02%  |
| WDC                 | 78        | 124    | 29.55%  |
| Toshiba             | 33        | 40     | 12.5%   |
| HGST                | 17        | 23     | 6.44%   |
| Hitachi             | 16        | 16     | 6.06%   |
| Samsung Electronics | 5         | 5      | 1.89%   |
| Unknown             | 3         | 3      | 1.14%   |
| Intenso             | 3         | 4      | 1.14%   |
| Apple               | 2         | 2      | 0.76%   |
| LaCie               | 1         | 1      | 0.38%   |
| Inateck             | 1         | 1      | 0.38%   |
| Hewlett-Packard     | 1         | 1      | 0.38%   |
| ASMedia             | 1         | 2      | 0.38%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 64        | 92     | 26.67%  |
| Crucial             | 25        | 33     | 10.42%  |
| SanDisk             | 21        | 31     | 8.75%   |
| Kingston            | 19        | 25     | 7.92%   |
| WDC                 | 15        | 16     | 6.25%   |
| SPCC                | 8         | 8      | 3.33%   |
| A-DATA Technology   | 8         | 12     | 3.33%   |
| SK hynix            | 7         | 10     | 2.92%   |
| PNY                 | 7         | 7      | 2.92%   |
| Toshiba             | 6         | 9      | 2.5%    |
| China               | 6         | 8      | 2.5%    |
| Micron Technology   | 5         | 6      | 2.08%   |
| OCZ                 | 4         | 4      | 1.67%   |
| LITEON              | 4         | 4      | 1.67%   |
| Transcend           | 3         | 3      | 1.25%   |
| LITEONIT            | 3         | 3      | 1.25%   |
| Emtec               | 3         | 5      | 1.25%   |
| TO Exter            | 2         | 2      | 0.83%   |
| Team                | 2         | 3      | 0.83%   |
| SABRENT             | 2         | 4      | 0.83%   |
| Mushkin             | 2         | 2      | 0.83%   |
| FORESEE             | 2         | 2      | 0.83%   |
| WODPOSIT            | 1         | 2      | 0.42%   |
| WDC WDS             | 1         | 1      | 0.42%   |
| VisionTek           | 1         | 2      | 0.42%   |
| USB30               | 1         | 2      | 0.42%   |
| Unknown             | 1         | 1      | 0.42%   |
| T-FORCE             | 1         | 1      | 0.42%   |
| SATAFIRM            | 1         | 1      | 0.42%   |
| Qumo                | 1         | 1      | 0.42%   |
| PNY CS90            | 1         | 1      | 0.42%   |
| Plextor             | 1         | 1      | 0.42%   |
| Patriot             | 1         | 1      | 0.42%   |
| OWC                 | 1         | 1      | 0.42%   |
| Netac               | 1         | 1      | 0.42%   |
| KIOXIA-EXCERIA      | 1         | 1      | 0.42%   |
| JMicron Technology  | 1         | 1      | 0.42%   |
| Intenso             | 1         | 1      | 0.42%   |
| HS-SSD-C100         | 1         | 1      | 0.42%   |
| Fanxiang            | 1         | 1      | 0.42%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| NVMe    | 244       | 380    | 35.88%  |
| HDD     | 205       | 366    | 30.15%  |
| SSD     | 198       | 314    | 29.12%  |
| Unknown | 17        | 17     | 2.5%    |
| MMC     | 16        | 17     | 2.35%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 293       | 629    | 48.83%  |
| NVMe | 244       | 380    | 40.67%  |
| SAS  | 47        | 68     | 7.83%   |
| MMC  | 16        | 17     | 2.67%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 192       | 306    | 41.92%  |
| 0.51-1.0   | 158       | 217    | 34.5%   |
| 1.01-2.0   | 57        | 83     | 12.45%  |
| 3.01-4.0   | 21        | 29     | 4.59%   |
| 2.01-3.0   | 13        | 20     | 2.84%   |
| 4.01-10.0  | 13        | 18     | 2.84%   |
| 10.01-20.0 | 4         | 7      | 0.87%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 195       | 43.53%  |
| 1001-2000      | 85        | 18.97%  |
| 501-1000       | 68        | 15.18%  |
| 2001-3000      | 46        | 10.27%  |
| 251-500        | 21        | 4.69%   |
| Unknown        | 15        | 3.35%   |
| 1-20           | 14        | 3.13%   |
| 101-250        | 4         | 0.89%   |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 104       | 22.41%  |
| 251-500        | 83        | 17.89%  |
| 501-1000       | 72        | 15.52%  |
| 1001-2000      | 57        | 12.28%  |
| 51-100         | 47        | 10.13%  |
| More than 3000 | 39        | 8.41%   |
| 2001-3000      | 29        | 6.25%   |
| 1-20           | 15        | 3.23%   |
| Unknown        | 15        | 3.23%   |
| 21-50          | 3         | 0.65%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                                    | Computers | Drives | Percent |
|------------------------------------------|-----------|--------|---------|
| Toshiba DT01ACA050 500GB                 | 2         | 2      | 3.77%   |
| Intenso USB 3.0 device 4TB               | 2         | 2      | 3.77%   |
| HGST HTS725050A7E630 500GB               | 2         | 5      | 3.77%   |
| HGST HTS721010A9E630 1TB                 | 2         | 2      | 3.77%   |
| WDC WD6400AAKS-65A7B0 640GB              | 1         | 1      | 1.89%   |
| WDC WD5000BEVT-60A0RT0 500GB             | 1         | 1      | 1.89%   |
| WDC WD5000AAKX-60U6AA0 500GB             | 1         | 1      | 1.89%   |
| WDC WD5000AAKS-00E4A0 500GB              | 1         | 1      | 1.89%   |
| WDC WD30EZRX-00DC0B0 3TB                 | 1         | 1      | 1.89%   |
| WDC WD30EFRX-68EUZN0 3TB                 | 1         | 1      | 1.89%   |
| WDC WD20EARX-00PASB0 2TB                 | 1         | 1      | 1.89%   |
| WDC WD20EARS-00MVWB0 2TB                 | 1         | 1      | 1.89%   |
| WDC WD10JPVX-22JC3T0 1TB                 | 1         | 1      | 1.89%   |
| WDC WD10EZRX-00L4HB0 1TB                 | 1         | 1      | 1.89%   |
| WDC WD10EZEX-60ZF5A0 1TB                 | 1         | 1      | 1.89%   |
| WDC WD10EARS-00Y5B1 1TB                  | 1         | 1      | 1.89%   |
| WDC WD10EALX-009BA0 1TB                  | 1         | 1      | 1.89%   |
| WDC WD10EADS-22M2B0 1TB                  | 1         | 1      | 1.89%   |
| WDC WD10EADS-00M2B0 1TB                  | 1         | 1      | 1.89%   |
| SK hynix PC711 HFS512GDE9X073N 512GB     | 1         | 1      | 1.89%   |
| SK hynix PC711 HFS001TDE9X073N 1TB       | 1         | 2      | 1.89%   |
| Seagate ST9250827AS 250GB                | 1         | 1      | 1.89%   |
| Seagate ST500LT012-1DG142 500GB          | 1         | 1      | 1.89%   |
| Seagate ST4000DM004-2CV104 4TB           | 1         | 1      | 1.89%   |
| Seagate ST3000DM003-1F216N 3TB           | 1         | 1      | 1.89%   |
| Seagate ST2000LM003 HN-M201RAD 2TB       | 1         | 1      | 1.89%   |
| Seagate ST2000DL003-9VT166 2TB           | 1         | 1      | 1.89%   |
| Seagate ST1000LM048-2E7172 1TB           | 1         | 1      | 1.89%   |
| Seagate ST1000LM035-1RK172 1TB           | 1         | 1      | 1.89%   |
| Seagate ST1000LM014-1EJ164 1TB           | 1         | 1      | 1.89%   |
| SanDisk SSD PLUS 1000GB                  | 1         | 1      | 1.89%   |
| SanDisk SD6SF1M128G1022I 128GB SSD       | 1         | 1      | 1.89%   |
| Samsung Electronics SSD 980 1TB          | 1         | 6      | 1.89%   |
| Samsung Electronics SSD 960 EVO 250GB    | 1         | 5      | 1.89%   |
| Samsung Electronics SSD 850 PRO 512GB    | 1         | 1      | 1.89%   |
| Samsung Electronics SSD 840 Series 120GB | 1         | 1      | 1.89%   |
| OCZ TRION100 480GB SSD                   | 1         | 1      | 1.89%   |
| Kingston SV300S37A120G 120GB SSD         | 1         | 1      | 1.89%   |
| Kingston SH103S3240G 240GB SSD           | 1         | 1      | 1.89%   |
| Hitachi HTS547575A9E384 752GB            | 1         | 1      | 1.89%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 13        | 15     | 26.53%  |
| Seagate             | 9         | 9      | 18.37%  |
| HGST                | 5         | 11     | 10.2%   |
| Hitachi             | 4         | 4      | 8.16%   |
| Samsung Electronics | 3         | 13     | 6.12%   |
| Toshiba             | 2         | 2      | 4.08%   |
| SK hynix            | 2         | 3      | 4.08%   |
| SanDisk             | 2         | 2      | 4.08%   |
| Kingston            | 2         | 2      | 4.08%   |
| Intenso             | 2         | 2      | 4.08%   |
| OCZ                 | 1         | 1      | 2.04%   |
| Hewlett-Packard     | 1         | 1      | 2.04%   |
| Crucial             | 1         | 1      | 2.04%   |
| Apple               | 1         | 1      | 2.04%   |
| A-DATA Technology   | 1         | 1      | 2.04%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| WDC     | 13        | 15     | 36.11%  |
| Seagate | 9         | 9      | 25%     |
| HGST    | 5         | 11     | 13.89%  |
| Hitachi | 4         | 4      | 11.11%  |
| Toshiba | 2         | 2      | 5.56%   |
| Intenso | 2         | 2      | 5.56%   |
| Apple   | 1         | 1      | 2.78%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 32        | 44     | 71.11%  |
| SSD  | 9         | 9      | 20%     |
| NVMe | 4         | 15     | 8.89%   |

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
| Works    | 236       | 493    | 46.18%  |
| Detected | 232       | 533    | 45.4%   |
| Malfunc  | 43        | 68     | 8.41%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 248       | 38.21%  |
| AMD                            | 136       | 20.96%  |
| Samsung Electronics            | 80        | 12.33%  |
| SanDisk                        | 47        | 7.24%   |
| SK hynix                       | 26        | 4.01%   |
| Phison Electronics             | 22        | 3.39%   |
| Kingston Technology Company    | 14        | 2.16%   |
| Silicon Motion                 | 13        | 2%      |
| Micron/Crucial Technology      | 11        | 1.69%   |
| ASMedia Technology             | 8         | 1.23%   |
| Micron Technology              | 6         | 0.92%   |
| KIOXIA                         | 6         | 0.92%   |
| Toshiba America Info Systems   | 5         | 0.77%   |
| Marvell Technology Group       | 5         | 0.77%   |
| ADATA Technology               | 5         | 0.77%   |
| Union Memory (Shenzhen)        | 4         | 0.62%   |
| Realtek Semiconductor          | 2         | 0.31%   |
| MAXIO Technology (Hangzhou)    | 2         | 0.31%   |
| JMicron Technology             | 2         | 0.31%   |
| Yangtze Memory Technologies    | 1         | 0.15%   |
| Solid State Storage Technology | 1         | 0.15%   |
| Shenzhen Longsys Electronics   | 1         | 0.15%   |
| Seagate Technology             | 1         | 0.15%   |
| Nvidia                         | 1         | 0.15%   |
| Lenovo                         | 1         | 0.15%   |
| Apple                          | 1         | 0.15%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                            | 99        | 13.54%  |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                  | 54        | 7.39%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                             | 22        | 3.01%   |
| SanDisk WD Blue SN550 NVMe SSD                                                 | 20        | 2.74%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                 | 20        | 2.74%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode] | 20        | 2.74%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]               | 20        | 2.74%   |
| AMD 500 Series Chipset SATA Controller                                         | 20        | 2.74%   |
| AMD 400 Series Chipset SATA Controller                                         | 20        | 2.74%   |
| Intel Volume Management Device NVMe RAID Controller                            | 17        | 2.33%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                 | 13        | 1.78%   |
| Samsung NVMe SSD Controller 980                                                | 12        | 1.64%   |
| Phison E12 NVMe Controller                                                     | 12        | 1.64%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                 | 11        | 1.5%    |
| Intel SSD 660P Series                                                          | 11        | 1.5%    |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]  | 10        | 1.37%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                     | 9         | 1.23%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                  | 9         | 1.23%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                              | 9         | 1.23%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Desktop SATA AHCI Controller  | 9         | 1.23%   |
| Silicon Motion SM2263EN/SM2263XT SSD Controller                                | 8         | 1.09%   |
| Intel 500 Series Chipset Family SATA AHCI Controller                           | 8         | 1.09%   |
| ASMedia ASM1062 Serial ATA Controller                                          | 8         | 1.09%   |
| SK hynix BC501 NVMe Solid State Drive                                          | 7         | 0.96%   |
| Micron/Crucial P2 NVMe PCIe SSD                                                | 7         | 0.96%   |
| Intel Comet Lake SATA AHCI Controller                                          | 7         | 0.96%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                   | 7         | 0.96%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller   | 7         | 0.96%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                           | 7         | 0.96%   |
| Phison E16 PCIe4 NVMe Controller                                               | 6         | 0.82%   |
| Micron NVMe Storage Controller                                                 | 6         | 0.82%   |
| KIOXIA NVMe SSD Controller BG4                                                 | 6         | 0.82%   |
| Intel HM170/QM170 Chipset SATA Controller [AHCI Mode]                          | 6         | 0.82%   |
| Intel Cannon Lake PCH SATA AHCI Controller                                     | 6         | 0.82%   |
| Intel 7 Series/C210 Series Chipset Family 6-port SATA Controller [AHCI mode]   | 6         | 0.82%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                               | 6         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                              | 6         | 0.82%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                           | 6         | 0.82%   |
| AMD FCH SATA Controller D                                                      | 6         | 0.82%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                      | 5         | 0.68%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 326       | 51.66%  |
| NVMe | 242       | 38.35%  |
| RAID | 44        | 6.97%   |
| IDE  | 19        | 3.01%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 262       | 60.09%  |
| AMD    | 174       | 39.91%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i7-10750H CPU @ 2.60GHz            | 9         | 2.06%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 8         | 1.83%   |
| AMD Ryzen 7 4800H with Radeon Graphics        | 8         | 1.83%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 7         | 1.6%    |
| Intel 11th Gen Core i5-1135G7 @ 2.40GHz       | 7         | 1.6%    |
| AMD Ryzen 7 3700X 8-Core Processor            | 7         | 1.6%    |
| Intel Core i7-9750H CPU @ 2.60GHz             | 6         | 1.37%   |
| Intel Core i5-3210M CPU @ 2.50GHz             | 6         | 1.37%   |
| AMD Ryzen 9 3900X 12-Core Processor           | 6         | 1.37%   |
| AMD Ryzen 5 3600 6-Core Processor             | 6         | 1.37%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 5         | 1.14%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 5         | 1.14%   |
| AMD Ryzen 7 5700G with Radeon Graphics        | 5         | 1.14%   |
| AMD Ryzen 5 4600H with Radeon Graphics        | 5         | 1.14%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 5         | 1.14%   |
| Intel Core i7-6700HQ CPU @ 2.60GHz            | 4         | 0.92%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 4         | 0.92%   |
| Intel Core i3-2350M CPU @ 2.30GHz             | 4         | 0.92%   |
| Intel Core i3-1005G1 CPU @ 1.20GHz            | 4         | 0.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 4         | 0.92%   |
| Intel 11th Gen Core i5-11400H @ 2.70GHz       | 4         | 0.92%   |
| AMD Ryzen 7 5800X 8-Core Processor            | 4         | 0.92%   |
| AMD Ryzen 7 3700U with Radeon Vega Mobile Gfx | 4         | 0.92%   |
| AMD Ryzen 5 5600X 6-Core Processor            | 4         | 0.92%   |
| AMD Ryzen 5 5600H with Radeon Graphics        | 4         | 0.92%   |
| AMD Ryzen 5 3400G with Radeon Vega Graphics   | 4         | 0.92%   |
| AMD Ryzen 3 3200G with Radeon Vega Graphics   | 4         | 0.92%   |
| Intel Core i7-4790 CPU @ 3.60GHz              | 3         | 0.69%   |
| Intel Core i5-9300H CPU @ 2.40GHz             | 3         | 0.69%   |
| Intel Core i5-4300M CPU @ 2.60GHz             | 3         | 0.69%   |
| Intel Core i5-4210M CPU @ 2.60GHz             | 3         | 0.69%   |
| Intel Core i5-2520M CPU @ 2.50GHz             | 3         | 0.69%   |
| Intel 12th Gen Core i5-12600K                 | 3         | 0.69%   |
| Intel 11th Gen Core i7-11800H @ 2.30GHz       | 3         | 0.69%   |
| AMD Ryzen 9 7900X 12-Core Processor           | 3         | 0.69%   |
| AMD Ryzen 9 5950X 16-Core Processor           | 3         | 0.69%   |
| AMD Ryzen 7 PRO 4750U with Radeon Graphics    | 3         | 0.69%   |
| AMD Ryzen 7 3800X 8-Core Processor            | 3         | 0.69%   |
| AMD Ryzen 7 2700X Eight-Core Processor        | 3         | 0.69%   |
| AMD Ryzen 5 5500U with Radeon Graphics        | 3         | 0.69%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i7           | 87        | 19.95%  |
| Intel Core i5           | 78        | 17.89%  |
| AMD Ryzen 7             | 57        | 13.07%  |
| AMD Ryzen 5             | 51        | 11.7%   |
| Other                   | 36        | 8.26%   |
| Intel Core i3           | 33        | 7.57%   |
| AMD Ryzen 9             | 20        | 4.59%   |
| Intel Celeron           | 11        | 2.52%   |
| AMD Ryzen 3             | 10        | 2.29%   |
| AMD FX                  | 6         | 1.38%   |
| Intel Xeon              | 5         | 1.15%   |
| AMD Ryzen 7 PRO         | 5         | 1.15%   |
| AMD A8                  | 5         | 1.15%   |
| AMD A10                 | 4         | 0.92%   |
| Intel Pentium Dual-Core | 3         | 0.69%   |
| Intel Pentium           | 3         | 0.69%   |
| Intel Core 2 Duo        | 3         | 0.69%   |
| AMD Ryzen Threadripper  | 3         | 0.69%   |
| AMD A6                  | 3         | 0.69%   |
| Intel Pentium Silver    | 2         | 0.46%   |
| AMD A4                  | 2         | 0.46%   |
| Intel Core m3           | 1         | 0.23%   |
| Intel Core i9           | 1         | 0.23%   |
| Intel Core 2 Quad       | 1         | 0.23%   |
| AMD Turion              | 1         | 0.23%   |
| AMD Phenom II X6        | 1         | 0.23%   |
| AMD Phenom II X4        | 1         | 0.23%   |
| AMD Phenom II X2        | 1         | 0.23%   |
| AMD Athlon X4           | 1         | 0.23%   |
| AMD Athlon              | 1         | 0.23%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 141       | 32.34%  |
| 2      | 121       | 27.75%  |
| 8      | 77        | 17.66%  |
| 6      | 71        | 16.28%  |
| 12     | 12        | 2.75%   |
| 16     | 5         | 1.15%   |
| 10     | 4         | 0.92%   |
| 14     | 3         | 0.69%   |
| 24     | 1         | 0.23%   |
| 3      | 1         | 0.23%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 436       | 100%    |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 363       | 83.26%  |
| 1      | 73        | 16.74%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 436       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 217       | 48.33%  |
| 0x306a9    | 17        | 3.79%   |
| 0x0a50000c | 15        | 3.34%   |
| 0x206a7    | 12        | 2.67%   |
| 0x08108109 | 12        | 2.67%   |
| 0x306c3    | 11        | 2.45%   |
| 0x806c1    | 10        | 2.23%   |
| 0x906ea    | 9         | 2%      |
| 0x08701021 | 9         | 2%      |
| 0x506e3    | 7         | 1.56%   |
| 0x08600106 | 7         | 1.56%   |
| 0x0800820d | 7         | 1.56%   |
| 0xa0652    | 6         | 1.34%   |
| 0x906e9    | 6         | 1.34%   |
| 0x806ea    | 5         | 1.11%   |
| 0x0a404102 | 5         | 1.11%   |
| 0x806e9    | 4         | 0.89%   |
| 0x08608103 | 4         | 0.89%   |
| 0x08600103 | 4         | 0.89%   |
| 0x406e3    | 3         | 0.67%   |
| 0x40651    | 3         | 0.67%   |
| 0x0a601203 | 3         | 0.67%   |
| 0x0a50000b | 3         | 0.67%   |
| 0x0a20120a | 3         | 0.67%   |
| 0x0a201009 | 3         | 0.67%   |
| 0x08600104 | 3         | 0.67%   |
| 0x08108102 | 3         | 0.67%   |
| 0x08001137 | 3         | 0.67%   |
| 0x06006705 | 3         | 0.67%   |
| 0xa0653    | 2         | 0.45%   |
| 0x906ed    | 2         | 0.45%   |
| 0x906a3    | 2         | 0.45%   |
| 0x90672    | 2         | 0.45%   |
| 0x806ec    | 2         | 0.45%   |
| 0x106e5    | 2         | 0.45%   |
| 0x1067a    | 2         | 0.45%   |
| 0x0a201204 | 2         | 0.45%   |
| 0x0810100b | 2         | 0.45%   |
| 0x08101007 | 2         | 0.45%   |
| 0x06000852 | 2         | 0.45%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 65        | 14.87%  |
| Zen 2            | 46        | 10.53%  |
| Zen 3            | 41        | 9.38%   |
| Zen+             | 34        | 7.78%   |
| IvyBridge        | 31        | 7.09%   |
| Haswell          | 29        | 6.64%   |
| Unknown          | 26        | 5.95%   |
| SandyBridge      | 25        | 5.72%   |
| Skylake          | 23        | 5.26%   |
| CometLake        | 19        | 4.35%   |
| TigerLake        | 15        | 3.43%   |
| Zen              | 11        | 2.52%   |
| Broadwell        | 9         | 2.06%   |
| Piledriver       | 8         | 1.83%   |
| IceLake          | 8         | 1.83%   |
| Penryn           | 7         | 1.6%    |
| Alderlake Hybrid | 6         | 1.37%   |
| Puma             | 5         | 1.14%   |
| Excavator        | 5         | 1.14%   |
| Steamroller      | 4         | 0.92%   |
| Westmere         | 3         | 0.69%   |
| Silvermont       | 3         | 0.69%   |
| Nehalem          | 3         | 0.69%   |
| K10              | 3         | 0.69%   |
| Goldmont plus    | 3         | 0.69%   |
| Goldmont         | 3         | 0.69%   |
| K8 & K10 hybrid  | 1         | 0.23%   |
| Jaguar           | 1         | 0.23%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 209       | 36.47%  |
| Nvidia | 190       | 33.16%  |
| AMD    | 174       | 30.37%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                       | Computers | Percent |
|-----------------------------------------------------------------------------|-----------|---------|
| AMD Renoir                                                                  | 22        | 3.75%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]        | 22        | 3.75%   |
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]                | 22        | 3.75%   |
| Intel 3rd Gen Core processor Graphics Controller                            | 19        | 3.24%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller   | 17        | 2.9%    |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                     | 15        | 2.56%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                   | 13        | 2.21%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                   | 12        | 2.04%   |
| Nvidia GA106M [GeForce RTX 3060 Mobile / Max-Q]                             | 10        | 1.7%    |
| Intel UHD Graphics 620                                                      | 10        | 1.7%    |
| Intel HD Graphics 630                                                       | 10        | 1.7%    |
| Intel CometLake-H GT2 [UHD Graphics]                                        | 10        | 1.7%    |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]               | 10        | 1.7%    |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                             | 9         | 1.53%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor Integrated Graphics Controller | 9         | 1.53%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                        | 9         | 1.53%   |
| Intel Skylake GT2 [HD Graphics 520]                                         | 9         | 1.53%   |
| Intel HD Graphics 620                                                       | 9         | 1.53%   |
| AMD Navi 10 [Radeon RX 5600 OEM/5600 XT / 5700/5700 XT]                     | 9         | 1.53%   |
| Nvidia TU117M [GeForce GTX 1650 Ti Mobile]                                  | 7         | 1.19%   |
| Nvidia TU117M                                                               | 7         | 1.19%   |
| Intel HD Graphics 5500                                                      | 7         | 1.19%   |
| Intel Haswell-ULT Integrated Graphics Controller                            | 7         | 1.19%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                 | 7         | 1.19%   |
| AMD Rembrandt [Radeon 680M]                                                 | 7         | 1.19%   |
| Nvidia TU116M [GeForce GTX 1660 Ti Mobile]                                  | 6         | 1.02%   |
| Intel HD Graphics 530                                                       | 6         | 1.02%   |
| AMD Navi 21 [Radeon RX 6800/6800 XT / 6900 XT]                              | 6         | 1.02%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                  | 5         | 0.85%   |
| Nvidia GA104M [GeForce RTX 3070 Mobile / Max-Q]                             | 5         | 0.85%   |
| Intel Xeon E3-1200 v2/3rd Gen Core processor Graphics Controller            | 5         | 0.85%   |
| Intel CometLake-U GT2 [UHD Graphics]                                        | 5         | 0.85%   |
| AMD Vega 10 XL/XT [Radeon RX Vega 56/64]                                    | 5         | 0.85%   |
| AMD Raven Ridge [Radeon Vega Series / Radeon Vega Mobile Series]            | 5         | 0.85%   |
| AMD Lucienne                                                                | 5         | 0.85%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                  | 4         | 0.68%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                     | 4         | 0.68%   |
| Nvidia GP106M [GeForce GTX 1060 Mobile]                                     | 4         | 0.68%   |
| Nvidia GP104 [GeForce GTX 1070]                                             | 4         | 0.68%   |
| Nvidia GM204 [GeForce GTX 970]                                              | 4         | 0.68%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| 1 x AMD            | 123       | 27.95%  |
| 1 x Intel          | 109       | 24.77%  |
| Intel + Nvidia     | 78        | 17.73%  |
| 1 x Nvidia         | 72        | 16.36%  |
| AMD + Nvidia       | 36        | 8.18%   |
| Intel + AMD        | 9         | 2.05%   |
| 2 x AMD            | 7         | 1.59%   |
| 2 x Nvidia         | 2         | 0.45%   |
| 2 x Intel          | 2         | 0.45%   |
| Intel + 2 x Nvidia | 2         | 0.45%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 289       | 65.38%  |
| Proprietary | 152       | 34.39%  |
| Unknown     | 1         | 0.23%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 260       | 57.78%  |
| 0.01-0.5   | 46        | 10.22%  |
| 1.01-2.0   | 34        | 7.56%   |
| 7.01-8.0   | 31        | 6.89%   |
| 3.01-4.0   | 27        | 6%      |
| 8.01-16.0  | 19        | 4.22%   |
| 5.01-6.0   | 14        | 3.11%   |
| 0.51-1.0   | 13        | 2.89%   |
| 2.01-3.0   | 3         | 0.67%   |
| 16.01-24.0 | 3         | 0.67%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| Samsung Electronics     | 60        | 11.32%  |
| AU Optronics            | 59        | 11.13%  |
| BOE                     | 47        | 8.87%   |
| Chimei Innolux          | 43        | 8.11%   |
| LG Display              | 39        | 7.36%   |
| Goldstar                | 29        | 5.47%   |
| Dell                    | 29        | 5.47%   |
| Acer                    | 23        | 4.34%   |
| AOC                     | 21        | 3.96%   |
| Hewlett-Packard         | 17        | 3.21%   |
| Sharp                   | 13        | 2.45%   |
| PANDA                   | 13        | 2.45%   |
| BenQ                    | 13        | 2.45%   |
| Ancor Communications    | 10        | 1.89%   |
| Philips                 | 8         | 1.51%   |
| Lenovo                  | 8         | 1.51%   |
| ASUSTek Computer        | 7         | 1.32%   |
| ViewSonic               | 6         | 1.13%   |
| Unknown                 | 6         | 1.13%   |
| Apple                   | 6         | 1.13%   |
| MSI                     | 5         | 0.94%   |
| Sony                    | 4         | 0.75%   |
| Mi                      | 4         | 0.75%   |
| InfoVision              | 4         | 0.75%   |
| Iiyama                  | 4         | 0.75%   |
| Gigabyte Technology     | 4         | 0.75%   |
| Vizio                   | 3         | 0.57%   |
| NEC Computers           | 3         | 0.57%   |
| CSO                     | 3         | 0.57%   |
| Chi Mei Optoelectronics | 3         | 0.57%   |
| Toshiba                 | 2         | 0.38%   |
| LG Electronics          | 2         | 0.38%   |
| Insignia                | 2         | 0.38%   |
| HKC                     | 2         | 0.38%   |
| Unknown                 | 2         | 0.38%   |
| Xiaomi                  | 1         | 0.19%   |
| Vestel                  | 1         | 0.19%   |
| RTK                     | 1         | 0.19%   |
| OUT                     | 1         | 0.19%   |
| Optoma                  | 1         | 0.19%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Chimei Innolux LCD Monitor CMN15E7 1920x1080 344x193mm 15.5-inch      | 4         | 0.73%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch        | 4         | 0.73%   |
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch        | 4         | 0.73%   |
| Samsung Electronics LCD Monitor SDC4161 1920x1080 344x194mm 15.5-inch | 3         | 0.55%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 3         | 0.55%   |
| PANDA LCD Monitor NCP004D 1920x1080 344x194mm 15.5-inch               | 3         | 0.55%   |
| Mi Monitor XMI3444 3440x1440 797x334mm 34.0-inch                      | 3         | 0.55%   |
| Goldstar FULL HD GSM5B55 1920x1080 480x270mm 21.7-inch                | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch      | 3         | 0.55%   |
| Chimei Innolux LCD Monitor CMN15C4 1920x1080 344x193mm 15.5-inch      | 3         | 0.55%   |
| BOE LCD Monitor BOE0700 1920x1080 344x194mm 15.5-inch                 | 3         | 0.55%   |
| AU Optronics LCD Monitor AUOAF90 1920x1080 344x193mm 15.5-inch        | 3         | 0.55%   |
| AOC Q32G1WG4 AOC3201 2560x1440 697x393mm 31.5-inch                    | 3         | 0.55%   |
| ViewSonic VX3276-QHD VSCE635 2560x1440 698x393mm 31.5-inch            | 2         | 0.37%   |
| ViewSonic VX3258 series VSCDE35 2560x1440 700x390mm 31.5-inch         | 2         | 0.37%   |
| Sharp LQ134N1JW52 SHP151E 1920x1200 288x180mm 13.4-inch               | 2         | 0.37%   |
| Samsung Electronics S34J55x SAM0F72 3440x1440 797x333mm 34.0-inch     | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SEC544B 1600x900 310x174mm 14.0-inch  | 2         | 0.37%   |
| Samsung Electronics LCD Monitor SDC4C48 1920x1080 239x134mm 10.8-inch | 2         | 0.37%   |
| Samsung Electronics C32F391 SAM0D34 1920x1080 698x393mm 31.5-inch     | 2         | 0.37%   |
| Philips PHL 276E8V PHLC18F 3840x2160 597x336mm 27.0-inch              | 2         | 0.37%   |
| PANDA LCD Monitor NCP0036 1920x1080 344x194mm 15.5-inch               | 2         | 0.37%   |
| LG Display LCD Monitor LGD046D 1920x1080 309x174mm 14.0-inch          | 2         | 0.37%   |
| LG Display LCD Monitor LGD045E 1366x768 310x174mm 14.0-inch           | 2         | 0.37%   |
| LG Display LCD Monitor LGD02DC 1366x768 344x194mm 15.5-inch           | 2         | 0.37%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 2         | 0.37%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch              | 2         | 0.37%   |
| Goldstar LG TV SSCR2 GSMC0C8 3840x2160                                | 2         | 0.37%   |
| Goldstar IPS FULLHD GSM5AB8 1920x1080 480x270mm 21.7-inch             | 2         | 0.37%   |
| Dell U2412M DELA07A 1920x1200 518x324mm 24.1-inch                     | 2         | 0.37%   |
| Dell U2312HM DEL4073 1920x1080 510x287mm 23.0-inch                    | 2         | 0.37%   |
| Dell 1909W DELA03C 1440x900 408x255mm 18.9-inch                       | 2         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E8 1920x1080 344x193mm 15.5-inch      | 2         | 0.37%   |
| Chimei Innolux LCD Monitor CMN15E3 1920x1080 344x193mm 15.5-inch      | 2         | 0.37%   |
| Chimei Innolux LCD Monitor CMN1521 1920x1080 344x193mm 15.5-inch      | 2         | 0.37%   |
| BOE LCD Monitor BOE0878 1920x1080 355x200mm 16.0-inch                 | 2         | 0.37%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 0.37%   |
| BOE LCD Monitor BOE07A1 1920x1080 344x193mm 15.5-inch                 | 2         | 0.37%   |
| BOE LCD Monitor BOE0610 1920x1080 344x193mm 15.5-inch                 | 2         | 0.37%   |
| AU Optronics LCD Monitor AUOD1ED 1920x1080 344x193mm 15.5-inch        | 2         | 0.37%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 253       | 50.5%   |
| 1366x768 (WXGA)    | 54        | 10.78%  |
| 3840x2160 (4K)     | 41        | 8.18%   |
| 2560x1440 (QHD)    | 33        | 6.59%   |
| 1600x900 (HD+)     | 16        | 3.19%   |
| 3440x1440          | 14        | 2.79%   |
| 1920x1200 (WUXGA)  | 11        | 2.2%    |
| 1680x1050 (WSXGA+) | 11        | 2.2%    |
| Unknown            | 10        | 2%      |
| 2560x1080          | 7         | 1.4%    |
| 2560x1600          | 6         | 1.2%    |
| 1280x1024 (SXGA)   | 6         | 1.2%    |
| 3840x1080          | 5         | 1%      |
| 1440x900 (WXGA+)   | 4         | 0.8%    |
| 1280x800 (WXGA)    | 4         | 0.8%    |
| 2880x1800          | 3         | 0.6%    |
| 1360x768           | 3         | 0.6%    |
| 7680x2160          | 2         | 0.4%    |
| 2256x1504          | 2         | 0.4%    |
| 9600x2160          | 1         | 0.2%    |
| 4480x1440          | 1         | 0.2%    |
| 3840x2400          | 1         | 0.2%    |
| 3840x1200          | 1         | 0.2%    |
| 3520x1080          | 1         | 0.2%    |
| 3200x1800 (QHD+)   | 1         | 0.2%    |
| 2880x1440          | 1         | 0.2%    |
| 2736x1824          | 1         | 0.2%    |
| 2240x1400          | 1         | 0.2%    |
| 2160x1440          | 1         | 0.2%    |
| 2048x1152          | 1         | 0.2%    |
| 1920x540           | 1         | 0.2%    |
| 1680x945           | 1         | 0.2%    |
| 1600x1200          | 1         | 0.2%    |
| 1280x768           | 1         | 0.2%    |
| 1280x720 (HD)      | 1         | 0.2%    |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 151       | 29.09%  |
| 27      | 51        | 9.83%   |
| 24      | 39        | 7.51%   |
| 14      | 37        | 7.13%   |
| Unknown | 34        | 6.55%   |
| 13      | 31        | 5.97%   |
| 23      | 28        | 5.39%   |
| 17      | 21        | 4.05%   |
| 21      | 18        | 3.47%   |
| 31      | 17        | 3.28%   |
| 34      | 15        | 2.89%   |
| 16      | 10        | 1.93%   |
| 22      | 9         | 1.73%   |
| 19      | 9         | 1.73%   |
| 18      | 7         | 1.35%   |
| 72      | 5         | 0.96%   |
| 20      | 5         | 0.96%   |
| 40      | 3         | 0.58%   |
| 28      | 3         | 0.58%   |
| 25      | 3         | 0.58%   |
| 74      | 2         | 0.39%   |
| 54      | 2         | 0.39%   |
| 49      | 2         | 0.39%   |
| 48      | 2         | 0.39%   |
| 47      | 2         | 0.39%   |
| 43      | 2         | 0.39%   |
| 12      | 2         | 0.39%   |
| 11      | 2         | 0.39%   |
| 85      | 1         | 0.19%   |
| 58      | 1         | 0.19%   |
| 52      | 1         | 0.19%   |
| 46      | 1         | 0.19%   |
| 35      | 1         | 0.19%   |
| 33      | 1         | 0.19%   |
| 26      | 1         | 0.19%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 203       | 40.12%  |
| 501-600     | 107       | 21.15%  |
| 401-500     | 43        | 8.5%    |
| Unknown     | 34        | 6.72%   |
| 351-400     | 28        | 5.53%   |
| 601-700     | 25        | 4.94%   |
| 201-300     | 25        | 4.94%   |
| 701-800     | 16        | 3.16%   |
| 1001-1500   | 11        | 2.17%   |
| 1501-2000   | 8         | 1.58%   |
| 801-900     | 4         | 0.79%   |
| 901-1000    | 2         | 0.4%    |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 356       | 76.56%  |
| 16/10   | 46        | 9.89%   |
| Unknown | 30        | 6.45%   |
| 21/9    | 17        | 3.66%   |
| 5/4     | 6         | 1.29%   |
| 3/2     | 4         | 0.86%   |
| 32/9    | 3         | 0.65%   |
| 4/3     | 2         | 0.43%   |
| 2.00    | 1         | 0.22%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 153       | 30%     |
| 201-250        | 73        | 14.31%  |
| 81-90          | 53        | 10.39%  |
| 301-350        | 52        | 10.2%   |
| 351-500        | 36        | 7.06%   |
| Unknown        | 34        | 6.67%   |
| 121-130        | 19        | 3.73%   |
| 151-200        | 16        | 3.14%   |
| 251-300        | 15        | 2.94%   |
| More than 1000 | 14        | 2.75%   |
| 71-80          | 14        | 2.75%   |
| 501-1000       | 10        | 1.96%   |
| 141-150        | 9         | 1.76%   |
| 111-120        | 5         | 0.98%   |
| 61-70          | 2         | 0.39%   |
| 51-60          | 2         | 0.39%   |
| 91-100         | 2         | 0.39%   |
| 131-140        | 1         | 0.2%    |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 121-160       | 160       | 32.52%  |
| 51-100        | 137       | 27.85%  |
| 101-120       | 103       | 20.93%  |
| Unknown       | 34        | 6.91%   |
| 161-240       | 33        | 6.71%   |
| 1-50          | 13        | 2.64%   |
| More than 240 | 12        | 2.44%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 326       | 73.09%  |
| 2     | 99        | 22.2%   |
| 3     | 14        | 3.14%   |
| 0     | 5         | 1.12%   |
| 4     | 2         | 0.45%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 264       | 38.37%  |
| Intel                             | 233       | 33.87%  |
| Qualcomm Atheros                  | 63        | 9.16%   |
| Broadcom                          | 28        | 4.07%   |
| MediaTek                          | 24        | 3.49%   |
| TP-Link                           | 8         | 1.16%   |
| Ralink Technology                 | 6         | 0.87%   |
| NetGear                           | 6         | 0.87%   |
| Samsung Electronics               | 5         | 0.73%   |
| Linksys                           | 4         | 0.58%   |
| DisplayLink                       | 4         | 0.58%   |
| ASIX Electronics                  | 4         | 0.58%   |
| Qualcomm                          | 3         | 0.44%   |
| Microsoft                         | 3         | 0.44%   |
| Aquantia                          | 3         | 0.44%   |
| Xiaomi                            | 2         | 0.29%   |
| Wacom                             | 2         | 0.29%   |
| Ralink                            | 2         | 0.29%   |
| OnePlus Technology (Shenzhen)     | 2         | 0.29%   |
| AVM                               | 2         | 0.29%   |
| ASUSTek Computer                  | 2         | 0.29%   |
| ZTE WCDMA Technologies MSM        | 1         | 0.15%   |
| Sitecom Europe                    | 1         | 0.15%   |
| Sierra Wireless                   | 1         | 0.15%   |
| Shenzhen Goodix Technology        | 1         | 0.15%   |
| Nvidia                            | 1         | 0.15%   |
| Motorola PCS                      | 1         | 0.15%   |
| Marvell Technology Group          | 1         | 0.15%   |
| Lenovo                            | 1         | 0.15%   |
| InterBiometrics                   | 1         | 0.15%   |
| Holtek Semiconductor              | 1         | 0.15%   |
| Google                            | 1         | 0.15%   |
| Ericsson Business Mobile Networks | 1         | 0.15%   |
| Dell                              | 1         | 0.15%   |
| D-Link                            | 1         | 0.15%   |
| Broadcom Limited                  | 1         | 0.15%   |
| Belkin Components                 | 1         | 0.15%   |
| Alteon Networks                   | 1         | 0.15%   |
| Accton Technology                 | 1         | 0.15%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 180       | 22.84%  |
| Intel Wi-Fi 6 AX200                                               | 43        | 5.46%   |
| Realtek RTL8125 2.5GbE Controller                                 | 23        | 2.92%   |
| Intel I211 Gigabit Network Connection                             | 19        | 2.41%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 18        | 2.28%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 2.28%   |
| Intel Ethernet Controller I225-V                                  | 14        | 1.78%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 1.78%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter        | 13        | 1.65%   |
| Intel Wireless 7265                                               | 13        | 1.65%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 12        | 1.52%   |
| Intel Wireless 8265 / 8275                                        | 11        | 1.4%    |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 11        | 1.4%    |
| Intel Comet Lake PCH CNVi WiFi                                    | 11        | 1.4%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 10        | 1.27%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 10        | 1.27%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                  | 10        | 1.27%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 10        | 1.27%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 9         | 1.14%   |
| Intel Wi-Fi 6 AX201                                               | 9         | 1.14%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 1.02%   |
| Intel Wireless-AC 9260                                            | 8         | 1.02%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 8         | 1.02%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                   | 7         | 0.89%   |
| Intel Wireless 7260                                               | 7         | 0.89%   |
| Intel Wireless 3165                                               | 7         | 0.89%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 0.89%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                 | 6         | 0.76%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 0.63%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 5         | 0.63%   |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                           | 5         | 0.63%   |
| Intel Wireless 8260                                               | 5         | 0.63%   |
| Broadcom BCM4331 802.11a/b/g/n                                    | 5         | 0.63%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 4         | 0.51%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 0.51%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter     | 4         | 0.51%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 4         | 0.51%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 0.51%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 0.51%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 0.51%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 189       | 49.35%  |
| Realtek Semiconductor | 60        | 15.67%  |
| Qualcomm Atheros      | 49        | 12.79%  |
| MediaTek              | 22        | 5.74%   |
| Broadcom              | 22        | 5.74%   |
| TP-Link               | 7         | 1.83%   |
| Ralink Technology     | 6         | 1.57%   |
| NetGear               | 6         | 1.57%   |
| Linksys               | 4         | 1.04%   |
| Microsoft             | 3         | 0.78%   |
| Wacom                 | 2         | 0.52%   |
| Ralink                | 2         | 0.52%   |
| AVM                   | 2         | 0.52%   |
| ASUSTek Computer      | 2         | 0.52%   |
| Sitecom Europe        | 1         | 0.26%   |
| Sierra Wireless       | 1         | 0.26%   |
| Qualcomm              | 1         | 0.26%   |
| Dell                  | 1         | 0.26%   |
| D-Link                | 1         | 0.26%   |
| Broadcom Limited      | 1         | 0.26%   |
| Accton Technology     | 1         | 0.26%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 43        | 11.14%  |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 18        | 4.66%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter     | 13        | 3.37%   |
| Intel Wireless 7265                                            | 13        | 3.37%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 12        | 3.11%   |
| Intel Wireless 8265 / 8275                                     | 11        | 2.85%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 11        | 2.85%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 11        | 2.85%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 10        | 2.59%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 10        | 2.59%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]               | 10        | 2.59%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 10        | 2.59%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 9         | 2.33%   |
| Intel Wi-Fi 6 AX201                                            | 9         | 2.33%   |
| Intel Wireless-AC 9260                                         | 8         | 2.07%   |
| Intel Tiger Lake PCH CNVi WiFi                                 | 8         | 2.07%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                | 7         | 1.81%   |
| Intel Wireless 7260                                            | 7         | 1.81%   |
| Intel Wireless 3165                                            | 7         | 1.81%   |
| Intel Comet Lake PCH-LP CNVi WiFi                              | 6         | 1.55%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 5         | 1.3%    |
| MediaTek MT7921K (RZ608) Wi-Fi 6E 80MHz                        | 5         | 1.3%    |
| Intel Wireless 8260                                            | 5         | 1.3%    |
| Broadcom BCM4331 802.11a/b/g/n                                 | 5         | 1.3%    |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 4         | 1.04%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 4         | 1.04%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 4         | 1.04%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 1.04%   |
| Broadcom BCM43142 802.11b/g/n                                  | 4         | 1.04%   |
| TP-Link TL-WN823N v2/v3 [Realtek RTL8192EU]                    | 3         | 0.78%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 3         | 0.78%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 3         | 0.78%   |
| Ralink RT2870/RT3070 Wireless Adapter                          | 3         | 0.78%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 3         | 0.78%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express) | 3         | 0.78%   |
| Intel Centrino Wireless-N 2230                                 | 3         | 0.78%   |
| Intel Centrino Ultimate-N 6300                                 | 3         | 0.78%   |
| Intel Centrino Advanced-N 6205 [Taylor Peak]                   | 3         | 0.78%   |
| Intel Centrino Advanced-N 6200                                 | 3         | 0.78%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter            | 3         | 0.78%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                        | Computers | Percent |
|-------------------------------|-----------|---------|
| Realtek Semiconductor         | 234       | 60.62%  |
| Intel                         | 91        | 23.58%  |
| Qualcomm Atheros              | 21        | 5.44%   |
| Broadcom                      | 12        | 3.11%   |
| DisplayLink                   | 4         | 1.04%   |
| ASIX Electronics              | 4         | 1.04%   |
| Aquantia                      | 3         | 0.78%   |
| Xiaomi                        | 2         | 0.52%   |
| Samsung Electronics           | 2         | 0.52%   |
| Qualcomm                      | 2         | 0.52%   |
| MediaTek                      | 2         | 0.52%   |
| ZTE WCDMA Technologies MSM    | 1         | 0.26%   |
| TP-Link                       | 1         | 0.26%   |
| OnePlus Technology (Shenzhen) | 1         | 0.26%   |
| Nvidia                        | 1         | 0.26%   |
| Marvell Technology Group      | 1         | 0.26%   |
| Lenovo                        | 1         | 0.26%   |
| Google                        | 1         | 0.26%   |
| Belkin Components             | 1         | 0.26%   |
| Alteon Networks               | 1         | 0.26%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 180       | 45.8%   |
| Realtek RTL8125 2.5GbE Controller                                 | 23        | 5.85%   |
| Intel I211 Gigabit Network Connection                             | 19        | 4.83%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 18        | 4.58%   |
| Intel Ethernet Controller I225-V                                  | 14        | 3.56%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 14        | 3.56%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 8         | 2.04%   |
| Intel Ethernet Connection I217-LM                                 | 7         | 1.78%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 5         | 1.27%   |
| Qualcomm Atheros Killer E2400 Gigabit Ethernet Controller         | 4         | 1.02%   |
| Intel Ethernet Connection (2) I219-V                              | 4         | 1.02%   |
| Intel 82579V Gigabit Network Connection                           | 4         | 1.02%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 3         | 0.76%   |
| Qualcomm Atheros Killer E2500 Gigabit Ethernet Controller         | 3         | 0.76%   |
| Qualcomm Atheros Killer E220x Gigabit Ethernet Controller         | 3         | 0.76%   |
| Intel Ethernet Connection I219-LM                                 | 3         | 0.76%   |
| Intel Ethernet Connection (4) I219-LM                             | 3         | 0.76%   |
| Intel Ethernet Connection (3) I218-LM                             | 3         | 0.76%   |
| Intel Ethernet Connection (2) I219-LM                             | 3         | 0.76%   |
| Intel 82577LM Gigabit Network Connection                          | 3         | 0.76%   |
| Broadcom NetXtreme BCM57766 Gigabit Ethernet PCIe                 | 3         | 0.76%   |
| Broadcom NetXtreme BCM57765 Gigabit Ethernet PCIe                 | 3         | 0.76%   |
| ASIX AX88179 Gigabit Ethernet                                     | 3         | 0.76%   |
| Xiaomi Mi/Redmi series (RNDIS)                                    | 2         | 0.51%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 2         | 0.51%   |
| Realtek Killer E3000 2.5GbE Controller                            | 2         | 0.51%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                            | 2         | 0.51%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 2         | 0.51%   |
| Qualcomm Atheros AR8152 v2.0 Fast Ethernet                        | 2         | 0.51%   |
| Intel Ethernet Connection I217-V                                  | 2         | 0.51%   |
| Intel Ethernet Connection (7) I219-V                              | 2         | 0.51%   |
| Intel Ethernet Connection (7) I219-LM                             | 2         | 0.51%   |
| Intel Ethernet Connection (2) I218-V                              | 2         | 0.51%   |
| DisplayLink USB3.0 5K Graphic Docking                             | 2         | 0.51%   |
| Broadcom NetLink BCM5787M Gigabit Ethernet PCI Express            | 2         | 0.51%   |
| Aquantia AQC107 NBase-T/IEEE 802.3bz Ethernet Controller [AQtion] | 2         | 0.51%   |
| ZTE WCDMA MSM ZTE WCDMA MSM                                       | 1         | 0.25%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.25%   |
| Realtek USB 10/100/1G/2.5G LAN                                    | 1         | 0.25%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.25%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 359       | 49.52%  |
| WiFi     | 357       | 49.24%  |
| Modem    | 5         | 0.69%   |
| Unknown  | 4         | 0.55%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 279       | 61.86%  |
| Ethernet | 171       | 37.92%  |
| Modem    | 1         | 0.22%   |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 236       | 53.76%  |
| 1     | 182       | 41.46%  |
| 3     | 16        | 3.64%   |
| 0     | 4         | 0.91%   |
| 4     | 1         | 0.23%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 322       | 73.02%  |
| Yes  | 119       | 26.98%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 165       | 50.77%  |
| Realtek Semiconductor           | 42        | 12.92%  |
| Qualcomm Atheros Communications | 29        | 8.92%   |
| Cambridge Silicon Radio         | 17        | 5.23%   |
| IMC Networks                    | 14        | 4.31%   |
| Foxconn / Hon Hai               | 10        | 3.08%   |
| Broadcom                        | 10        | 3.08%   |
| Lite-On Technology              | 8         | 2.46%   |
| MediaTek                        | 7         | 2.15%   |
| ASUSTek Computer                | 7         | 2.15%   |
| Apple                           | 7         | 2.15%   |
| Hewlett-Packard                 | 2         | 0.62%   |
| Dell                            | 2         | 0.62%   |
| USI                             | 1         | 0.31%   |
| Realtek                         | 1         | 0.31%   |
| Edimax Technology               | 1         | 0.31%   |
| Dynex                           | 1         | 0.31%   |
| AboCom Systems                  | 1         | 0.31%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                  | 39        | 12%     |
| Intel AX200 Bluetooth                               | 39        | 12%     |
| Intel AX201 Bluetooth                               | 32        | 9.85%   |
| Realtek Bluetooth Radio                             | 26        | 8%      |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)      | 19        | 5.85%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode) | 17        | 5.23%   |
| Qualcomm Atheros  Bluetooth Device                  | 15        | 4.62%   |
| Realtek  Bluetooth 4.2 Adapter                      | 13        | 4%      |
| Intel Wireless-AC 3168 Bluetooth                    | 10        | 3.08%   |
| Intel AX210 Bluetooth                               | 9         | 2.77%   |
| Intel Wireless-AC 9260 Bluetooth Adapter            | 8         | 2.46%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0              | 7         | 2.15%   |
| MediaTek Wireless_Device                            | 6         | 1.85%   |
| IMC Networks Wireless_Device                        | 6         | 1.85%   |
| IMC Networks Bluetooth Radio                        | 6         | 1.85%   |
| Apple Bluetooth USB Host Controller                 | 6         | 1.85%   |
| Intel Centrino Bluetooth Wireless Transceiver       | 5         | 1.54%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth          | 4         | 1.23%   |
| Intel Bluetooth Device                              | 4         | 1.23%   |
| Foxconn / Hon Hai Bluetooth Device                  | 4         | 1.23%   |
| Foxconn / Hon Hai MediaTek Bluetooth Adapter        | 3         | 0.92%   |
| Realtek RTL8821A Bluetooth                          | 2         | 0.62%   |
| Qualcomm Atheros AR9462 Bluetooth                   | 2         | 0.62%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0               | 2         | 0.62%   |
| Qualcomm Atheros AR3011 Bluetooth                   | 2         | 0.62%   |
| Lite-On Atheros AR3012 Bluetooth                    | 2         | 0.62%   |
| Broadcom BCM43142A0 Bluetooth Device                | 2         | 0.62%   |
| Broadcom BCM20702A0 Bluetooth 4.0                   | 2         | 0.62%   |
| Broadcom BCM2045B (BDC-2.1)                         | 2         | 0.62%   |
| ASUS Bluetooth Radio                                | 2         | 0.62%   |
| USI Bluetooth Device                                | 1         | 0.31%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter             | 1         | 0.31%   |
| Realtek Bluetooth Radio                             | 1         | 0.31%   |
| Qualcomm Atheros Bluetooth                          | 1         | 0.31%   |
| MediaTek MT7630e Bluetooth Adapter                  | 1         | 0.31%   |
| Lite-On Wireless_Device                             | 1         | 0.31%   |
| Lite-On Bluetooth Device                            | 1         | 0.31%   |
| IMC Networks Bluetooth Device                       | 1         | 0.31%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter   | 1         | 0.31%   |
| HP Broadcom 2070 Bluetooth Combo                    | 1         | 0.31%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Intel                    | 260       | 38.58%  |
| AMD                      | 190       | 28.19%  |
| Nvidia                   | 134       | 19.88%  |
| C-Media Electronics      | 13        | 1.93%   |
| Logitech                 | 12        | 1.78%   |
| Kingston Technology      | 5         | 0.74%   |
| Texas Instruments        | 4         | 0.59%   |
| Sony                     | 4         | 0.59%   |
| Blue Microphones         | 4         | 0.59%   |
| Trust                    | 3         | 0.45%   |
| RODE Microphones         | 3         | 0.45%   |
| JMTek                    | 3         | 0.45%   |
| DSEA A/S                 | 3         | 0.45%   |
| Yamaha                   | 2         | 0.3%    |
| Generalplus Technology   | 2         | 0.3%    |
| Focusrite-Novation       | 2         | 0.3%    |
| Digidesign               | 2         | 0.3%    |
| Creative Technology      | 2         | 0.3%    |
| Creative Labs            | 2         | 0.3%    |
| Corsair                  | 2         | 0.3%    |
| Turtle Beach             | 1         | 0.15%   |
| Tenx Technology          | 1         | 0.15%   |
| SteelSeries ApS          | 1         | 0.15%   |
| Samson Technologies      | 1         | 0.15%   |
| ROCCAT                   | 1         | 0.15%   |
| Realtek Semiconductor    | 1         | 0.15%   |
| Razer USA                | 1         | 0.15%   |
| Plantronics              | 1         | 0.15%   |
| Phison Electronics       | 1         | 0.15%   |
| Micro Star International | 1         | 0.15%   |
| KORG                     | 1         | 0.15%   |
| Huawei Technologies      | 1         | 0.15%   |
| Hewlett-Packard          | 1         | 0.15%   |
| Harman International     | 1         | 0.15%   |
| GN Netcom                | 1         | 0.15%   |
| EVGA                     | 1         | 0.15%   |
| DigiTech                 | 1         | 0.15%   |
| BR23                     | 1         | 0.15%   |
| Audio-Technica           | 1         | 0.15%   |
| ASUSTek Computer         | 1         | 0.15%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 89        | 10.56%  |
| AMD Starship/Matisse HD Audio Controller                                   | 40        | 4.74%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 36        | 4.27%   |
| Intel Sunrise Point-LP HD Audio                                            | 33        | 3.91%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 30        | 3.56%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 25        | 2.97%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 24        | 2.85%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 20        | 2.37%   |
| Intel Cannon Lake PCH cAVS                                                 | 19        | 2.25%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 18        | 2.14%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 18        | 2.14%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 16        | 1.9%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 15        | 1.78%   |
| Intel Comet Lake PCH cAVS                                                  | 14        | 1.66%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 14        | 1.66%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 14        | 1.66%   |
| Nvidia GA104 High Definition Audio Controller                              | 13        | 1.54%   |
| AMD FCH Azalia Controller                                                  | 12        | 1.42%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 11        | 1.3%    |
| Nvidia TU116 High Definition Audio Controller                              | 10        | 1.19%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 10        | 1.19%   |
| Nvidia GP104 High Definition Audio Controller                              | 10        | 1.19%   |
| Nvidia GA106 High Definition Audio Controller                              | 10        | 1.19%   |
| Intel CM238 HD Audio Controller                                            | 9         | 1.07%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 9         | 1.07%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 9         | 1.07%   |
| AMD Navi 10 HDMI Audio                                                     | 9         | 1.07%   |
| Nvidia GM204 High Definition Audio Controller                              | 8         | 0.95%   |
| Intel Wildcat Point-LP High Definition Audio Controller                    | 8         | 0.95%   |
| Intel Broadwell-U Audio Controller                                         | 8         | 0.95%   |
| AMD Kabini HDMI/DP Audio                                                   | 8         | 0.95%   |
| Nvidia GP107GL High Definition Audio Controller                            | 7         | 0.83%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 7         | 0.83%   |
| Nvidia Audio device                                                        | 7         | 0.83%   |
| Intel Haswell-ULT HD Audio Controller                                      | 7         | 0.83%   |
| Intel 8 Series HD Audio Controller                                         | 7         | 0.83%   |
| Intel 200 Series PCH HD Audio                                              | 7         | 0.83%   |
| Nvidia TU104 HD Audio Controller                                           | 6         | 0.71%   |
| Nvidia GP106 High Definition Audio Controller                              | 6         | 0.71%   |
| Intel Comet Lake PCH-LP cAVS                                               | 6         | 0.71%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor                       | Computers | Percent |
|------------------------------|-----------|---------|
| Samsung Electronics          | 71        | 21.26%  |
| SK hynix                     | 58        | 17.37%  |
| Micron Technology            | 35        | 10.48%  |
| G.Skill                      | 27        | 8.08%   |
| Crucial                      | 27        | 8.08%   |
| Kingston                     | 22        | 6.59%   |
| Corsair                      | 21        | 6.29%   |
| Unknown                      | 12        | 3.59%   |
| Ramaxel Technology           | 9         | 2.69%   |
| A-DATA Technology            | 8         | 2.4%    |
| Patriot                      | 7         | 2.1%    |
| Nanya Technology             | 5         | 1.5%    |
| Team                         | 4         | 1.2%    |
| Unknown                      | 4         | 1.2%    |
| Unknown (ABCD)               | 3         | 0.9%    |
| Smart                        | 3         | 0.9%    |
| Patriot Memory (PDP Systems) | 3         | 0.9%    |
| Transcend                    | 2         | 0.6%    |
| Timetec                      | 2         | 0.6%    |
| Elpida                       | 2         | 0.6%    |
| Wilk                         | 1         | 0.3%    |
| PNY                          | 1         | 0.3%    |
| Hewlett-Packard              | 1         | 0.3%    |
| GOODRAM                      | 1         | 0.3%    |
| Essencore                    | 1         | 0.3%    |
| CSX                          | 1         | 0.3%    |
| Avant                        | 1         | 0.3%    |
| Apacer                       | 1         | 0.3%    |
| 48spaces                     | 1         | 0.3%    |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                                    | Computers | Percent |
|--------------------------------------------------------------------------|-----------|---------|
| Samsung RAM M471A1G44AB0-CWE 8GB SODIMM DDR4 3200MT/s                    | 8         | 2.25%   |
| SK hynix RAM HMA81GS6DJR8N-XN 8GB SODIMM DDR4 3200MT/s                   | 6         | 1.69%   |
| Samsung RAM M471A1K43CB1-CTD 8GB SODIMM DDR4 2667MT/s                    | 6         | 1.69%   |
| G.Skill RAM F4-3200C16-16GVK 16384MB DIMM DDR4 3600MT/s                  | 6         | 1.69%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 5         | 1.41%   |
| Samsung RAM M471A1K43DB1-CWE 8GB SODIMM DDR4 3200MT/s                    | 5         | 1.41%   |
| Samsung RAM M471A5244CB0-CTD 4GB SODIMM DDR4 3266MT/s                    | 4         | 1.13%   |
| Corsair RAM CMK16GX4M2B3000C15 8GB DIMM DDR4 3533MT/s                    | 4         | 1.13%   |
| Unknown                                                                  | 4         | 1.13%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s         | 3         | 0.85%   |
| SK hynix RAM HMT41GS6AFR8A-PB 8GB SODIMM DDR3 1600MT/s                   | 3         | 0.85%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s                   | 3         | 0.85%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s                    | 3         | 0.85%   |
| Samsung RAM M471B1G73QH0-YK0 8GB SODIMM DDR3 1867MT/s                    | 3         | 0.85%   |
| Samsung RAM M471B1G73DB0-YK0 8GB SODIMM DDR3 1600MT/s                    | 3         | 0.85%   |
| Samsung RAM M471A5244CB0-CWE 4GB SODIMM DDR4 3200MT/s                    | 3         | 0.85%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s              | 3         | 0.85%   |
| G.Skill RAM F4-3000C16-8GISB 8192MB DIMM DDR4 3200MT/s                   | 3         | 0.85%   |
| Crucial RAM CT51264BF160B.C16F 4GB SODIMM DDR3 1600MT/s                  | 3         | 0.85%   |
| SK hynix RAM HMT451S6MFR8A-PB 4096MB SODIMM DDR3 1600MT/s                | 2         | 0.56%   |
| SK hynix RAM HMT41GS6BFR8A-PB 8GB SODIMM DDR3 1600MT/s                   | 2         | 0.56%   |
| SK hynix RAM HMT351U6CFR8C-PB 4GB DIMM DDR3 1800MT/s                     | 2         | 0.56%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s                   | 2         | 0.56%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s                   | 2         | 0.56%   |
| SK hynix RAM HMA851S6DJR6N-XN 4GB SODIMM DDR4 3200MT/s                   | 2         | 0.56%   |
| SK hynix RAM HMA82GS6AFR8N-UH 16GB SODIMM DDR4 2667MT/s                  | 2         | 0.56%   |
| SK hynix RAM HMA81GU6AFR8N-UH 8GB DIMM DDR4 2400MT/s                     | 2         | 0.56%   |
| SK hynix RAM HMA41GS6AFR8N-TF 8GB SODIMM DDR4 2667MT/s                   | 2         | 0.56%   |
| Samsung RAM M471A5244CB0-CRC 4GB SODIMM DDR4 2667MT/s                    | 2         | 0.56%   |
| Samsung RAM M471A1K43DB1-CTD 8GB SODIMM DDR4 2667MT/s                    | 2         | 0.56%   |
| Ramaxel RAM RMSA3260ME78HAF-2666 8GB SODIMM DDR4 2667MT/s                | 2         | 0.56%   |
| Patriot RAM 2666 C16 Series 4GB DIMM DDR4 2800MT/s                       | 2         | 0.56%   |
| Patriot Memory (PDP Systems) RAM 3600 C18 Series 16GB DIMM DDR4 3600MT/s | 2         | 0.56%   |
| Nanya RAM NT8GA64D88CX3S-JR 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.56%   |
| Nanya RAM NT4GC64B8HG0NS-DI 4GB SODIMM DDR3 1600MT/s                     | 2         | 0.56%   |
| Micron RAM Module 8GB SODIMM DDR4 3200MT/s                               | 2         | 0.56%   |
| Micron RAM 8ATF1G64HZ-3G2J1 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.56%   |
| Micron RAM 4ATF51264HZ-2G6E1 4GB SODIMM DDR4 2667MT/s                    | 2         | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E2 8GB SODIMM DDR4 3200MT/s                     | 2         | 0.56%   |
| Micron RAM 4ATF1G64HZ-3G2E1 8GB Row Of Chips DDR4 3200MT/s               | 2         | 0.56%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 188       | 65.51%  |
| DDR3    | 65        | 22.65%  |
| LPDDR4  | 11        | 3.83%   |
| DDR5    | 10        | 3.48%   |
| LPDDR3  | 4         | 1.39%   |
| DDR2    | 4         | 1.39%   |
| Unknown | 4         | 1.39%   |
| LPDDR5  | 1         | 0.35%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 182       | 62.54%  |
| DIMM         | 89        | 30.58%  |
| Row Of Chips | 18        | 6.19%   |
| Chip         | 1         | 0.34%   |
| Unknown      | 1         | 0.34%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 157       | 49.53%  |
| 4096  | 79        | 24.92%  |
| 16384 | 62        | 19.56%  |
| 32768 | 11        | 3.47%   |
| 2048  | 7         | 2.21%   |
| 1024  | 1         | 0.32%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 3200    | 79        | 25.08%  |
| 2667    | 48        | 15.24%  |
| 1600    | 48        | 15.24%  |
| 2400    | 28        | 8.89%   |
| 3600    | 18        | 5.71%   |
| 2133    | 9         | 2.86%   |
| 4800    | 8         | 2.54%   |
| 1334    | 6         | 1.9%    |
| 1333    | 6         | 1.9%    |
| 4266    | 5         | 1.59%   |
| 3666    | 5         | 1.59%   |
| 3533    | 4         | 1.27%   |
| 3266    | 4         | 1.27%   |
| 3733    | 3         | 0.95%   |
| 2933    | 3         | 0.95%   |
| 2666    | 3         | 0.95%   |
| 1867    | 3         | 0.95%   |
| 1866    | 3         | 0.95%   |
| 1800    | 3         | 0.95%   |
| 800     | 3         | 0.95%   |
| 4267    | 2         | 0.63%   |
| 3866    | 2         | 0.63%   |
| 3800    | 2         | 0.63%   |
| 3466    | 2         | 0.63%   |
| 3000    | 2         | 0.63%   |
| 2800    | 2         | 0.63%   |
| 667     | 2         | 0.63%   |
| 8400    | 1         | 0.32%   |
| 6400    | 1         | 0.32%   |
| 5600    | 1         | 0.32%   |
| 5200    | 1         | 0.32%   |
| 4200    | 1         | 0.32%   |
| 4000    | 1         | 0.32%   |
| 3534    | 1         | 0.32%   |
| 2200    | 1         | 0.32%   |
| 1200    | 1         | 0.32%   |
| 1067    | 1         | 0.32%   |
| 1066    | 1         | 0.32%   |
| Unknown | 1         | 0.32%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Hewlett-Packard     | 3         | 27.27%  |
| Samsung Electronics | 2         | 18.18%  |
| Dymo-CoStar         | 2         | 18.18%  |
| Brother Industries  | 2         | 18.18%  |
| Kyocera             | 1         | 9.09%   |
| Fuji Xerox          | 1         | 9.09%   |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


| Model                            | Computers | Percent |
|----------------------------------|-----------|---------|
| Dymo-CoStar LabelWriter 450      | 2         | 18.18%  |
| Samsung M337x 387x 407x Series   | 1         | 9.09%   |
| Samsung M267x 287x Series        | 1         | 9.09%   |
| Kyocera FS-1030D printer         | 1         | 9.09%   |
| HP OfficeJet Pro 8020 series     | 1         | 9.09%   |
| HP LaserJet 200 colorMFP M275nw  | 1         | 9.09%   |
| HP DeskJet Plus 4100 series      | 1         | 9.09%   |
| Fuji Xerox DocuPrint CM315/318 z | 1         | 9.09%   |
| Brother MFC Composite Device     | 1         | 9.09%   |
| Brother HL-5370DW series         | 1         | 9.09%   |

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


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 58        | 20.49%  |
| IMC Networks                           | 37        | 13.07%  |
| Logitech                               | 25        | 8.83%   |
| Quanta                                 | 18        | 6.36%   |
| Sunplus Innovation Technology          | 17        | 6.01%   |
| Realtek Semiconductor                  | 17        | 6.01%   |
| Microdia                               | 17        | 6.01%   |
| Syntek                                 | 9         | 3.18%   |
| Luxvisions Innotech Limited            | 9         | 3.18%   |
| Acer                                   | 9         | 3.18%   |
| Microsoft                              | 8         | 2.83%   |
| Cheng Uei Precision Industry (Foxlink) | 8         | 2.83%   |
| Bison Electronics                      | 8         | 2.83%   |
| Suyin                                  | 6         | 2.12%   |
| Apple                                  | 6         | 2.12%   |
| Lite-On Technology                     | 4         | 1.41%   |
| Silicon Motion                         | 3         | 1.06%   |
| Jieli Technology                       | 3         | 1.06%   |
| Sonix Technology                       | 2         | 0.71%   |
| Primax Electronics                     | 2         | 0.71%   |
| Generalplus Technology                 | 2         | 0.71%   |
| Alcor Micro                            | 2         | 0.71%   |
| Z-Star Microelectronics                | 1         | 0.35%   |
| WaveRider Communications               | 1         | 0.35%   |
| Trust                                  | 1         | 0.35%   |
| Shenzhen Kingcome Optoelectronic       | 1         | 0.35%   |
| Samsung Electronics                    | 1         | 0.35%   |
| Razer USA                              | 1         | 0.35%   |
| MacroSilicon                           | 1         | 0.35%   |
| Lenovo                                 | 1         | 0.35%   |
| Importek                               | 1         | 0.35%   |
| Genesys Logic                          | 1         | 0.35%   |
| GEMBIRD                                | 1         | 0.35%   |
| DigiTech                               | 1         | 0.35%   |
| Creative Technology                    | 1         | 0.35%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 18        | 6.32%   |
| IMC Networks Integrated Camera                       | 12        | 4.21%   |
| Chicony HD WebCam                                    | 12        | 4.21%   |
| Microdia Integrated_Webcam_HD                        | 9         | 3.16%   |
| Syntek Integrated Camera                             | 7         | 2.46%   |
| Chicony Integrated Camera                            | 7         | 2.46%   |
| Sunplus Integrated_Webcam_HD                         | 6         | 2.11%   |
| Logitech HD Pro Webcam C920                          | 6         | 2.11%   |
| Realtek Integrated_Webcam_HD                         | 5         | 1.75%   |
| Quanta HD User Facing                                | 5         | 1.75%   |
| Chicony HP Wide Vision HD Camera                     | 5         | 1.75%   |
| Acer HD Webcam                                       | 5         | 1.75%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 4         | 1.4%    |
| Logitech Webcam C270                                 | 4         | 1.4%    |
| Chicony USB2.0 Camera                                | 4         | 1.4%    |
| Chicony HD User Facing                               | 4         | 1.4%    |
| Bison Integrated Camera                              | 4         | 1.4%    |
| Sunplus FHD Camera                                   | 3         | 1.05%   |
| Quanta HP Wide Vision HD Camera                      | 3         | 1.05%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 3         | 1.05%   |
| Logitech Webcam C930e                                | 3         | 1.05%   |
| Logitech BRIO Ultra HD Webcam                        | 3         | 1.05%   |
| Lite-On HP Wide Vision HD Camera                     | 3         | 1.05%   |
| Jieli USB PHY 2.0                                    | 3         | 1.05%   |
| Apple FaceTime HD Camera                             | 3         | 1.05%   |
| Sonix USB2.0 HD UVC WebCam                           | 2         | 0.7%    |
| Silicon Motion Web Camera                            | 2         | 0.7%    |
| Realtek HP Truevision HD                             | 2         | 0.7%    |
| Quanta HD Camera                                     | 2         | 0.7%    |
| Primax HP HD Webcam [Fixed]                          | 2         | 0.7%    |
| Microsoft LifeCam HD-5000                            | 2         | 0.7%    |
| Microsoft LifeCam HD-3000                            | 2         | 0.7%    |
| Microdia Webcam Vitade AF                            | 2         | 0.7%    |
| Logitech HD Webcam C910                              | 2         | 0.7%    |
| Logitech C922 Pro Stream Webcam                      | 2         | 0.7%    |
| IMC Networks USB2.0 VGA UVC WebCam                   | 2         | 0.7%    |
| IMC Networks HD Camera                               | 2         | 0.7%    |
| Generalplus GENERAL WEBCAM                           | 2         | 0.7%    |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 0.7%    |
| Chicony USB2.0 HD UVC WebCam                         | 2         | 0.7%    |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 14        | 28.57%  |
| Synaptics                  | 11        | 22.45%  |
| Elan Microelectronics      | 9         | 18.37%  |
| Shenzhen Goodix Technology | 7         | 14.29%  |
| LighTuning Technology      | 4         | 8.16%   |
| AuthenTec                  | 2         | 4.08%   |
| Samsung Electronics        | 1         | 2.04%   |
| Focal-systems.Corp         | 1         | 2.04%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| Elan ELAN:ARM-M4                                                           | 5         | 10.2%   |
| Elan ELAN:Fingerprint                                                      | 4         | 8.16%   |
| Synaptics UWP WBDI                                                         | 3         | 6.12%   |
| Synaptics Prometheus MIS Touch Fingerprint Reader                          | 3         | 6.12%   |
| Shenzhen Goodix  FingerPrint Device                                        | 3         | 6.12%   |
| Shenzhen Goodix Fingerprint Reader                                         | 3         | 6.12%   |
| LighTuning EgisTec Touch Fingerprint Sensor                                | 3         | 6.12%   |
| Validity Sensors VFS 5011 fingerprint sensor                               | 2         | 4.08%   |
| Validity Sensors Synaptics WBDI                                            | 2         | 4.08%   |
| Validity Sensors Fingerprint scanner                                       | 2         | 4.08%   |
| Validity Sensors VFS7500 Touch Fingerprint Sensor                          | 1         | 2.04%   |
| Validity Sensors VFS5011 Fingerprint Reader                                | 1         | 2.04%   |
| Validity Sensors VFS495 Fingerprint Reader                                 | 1         | 2.04%   |
| Validity Sensors VFS491                                                    | 1         | 2.04%   |
| Validity Sensors VFS471 Fingerprint Reader                                 | 1         | 2.04%   |
| Validity Sensors VFS451 Fingerprint Reader                                 | 1         | 2.04%   |
| Validity Sensors Synaptics VFS7552 Touch Fingerprint Sensor with PurePrint | 1         | 2.04%   |
| Validity Sensors Swipe Fingerprint Sensor                                  | 1         | 2.04%   |
| Synaptics WBDI Device                                                      | 1         | 2.04%   |
| Synaptics WBDI                                                             | 1         | 2.04%   |
| Synaptics  WBDI Fingerprint Reader - USB 052                               | 1         | 2.04%   |
| Synaptics  WBDI                                                            | 1         | 2.04%   |
| Synaptics Metallica MIS Touch Fingerprint Reader                           | 1         | 2.04%   |
| Shenzhen Goodix FingerPrint                                                | 1         | 2.04%   |
| Samsung Fingerprint Sensor Device - 730B                                   | 1         | 2.04%   |
| LighTuning ES603 Swipe Fingerprint Sensor                                  | 1         | 2.04%   |
| Focal-systems.Corp FT9201Fingerprint.                                      | 1         | 2.04%   |
| AuthenTec AES2810                                                          | 1         | 2.04%   |
| AuthenTec AES1660 Fingerprint Sensor                                       | 1         | 2.04%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Broadcom         | 11        | 57.89%  |
| Alcor Micro      | 4         | 21.05%  |
| Upek             | 1         | 5.26%   |
| SCM Microsystems | 1         | 5.26%   |
| O2 Micro         | 1         | 5.26%   |
| Lenovo           | 1         | 5.26%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Broadcom BCM5880 Secure Applications Processor                               | 4         | 21.05%  |
| Broadcom 5880                                                                | 4         | 21.05%  |
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 21.05%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 3         | 15.79%  |
| Upek TouchChip Fingerprint Coprocessor (WBF advanced mode)                   | 1         | 5.26%   |
| SCM Microsystems SCR3500 C Contact Reader                                    | 1         | 5.26%   |
| O2 Micro OZ776 CCID Smartcard Reader                                         | 1         | 5.26%   |
| Lenovo Integrated Smart Card Reader                                          | 1         | 5.26%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 214       | 48.09%  |
| 0     | 146       | 32.81%  |
| 2     | 72        | 16.18%  |
| 3     | 12        | 2.7%    |
| 4     | 1         | 0.22%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Communication controller | 252       | 62.69%  |
| Fingerprint reader       | 49        | 12.19%  |
| Graphics card            | 29        | 7.21%   |
| Net/wireless             | 19        | 4.73%   |
| Chipcard                 | 18        | 4.48%   |
| Multimedia controller    | 10        | 2.49%   |
| Net/ethernet             | 8         | 1.99%   |
| Camera                   | 7         | 1.74%   |
| Storage                  | 3         | 0.75%   |
| Unassigned class         | 2         | 0.5%    |
| Network                  | 2         | 0.5%    |
| Bluetooth                | 2         | 0.5%    |
| Wireless                 | 1         | 0.25%   |

