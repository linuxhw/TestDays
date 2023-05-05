openSUSE Leap-15.4 - Tested Hardware & Statistics
-------------------------------------------------

A project to collect tested hardware configurations for openSUSE Leap-15.4.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Dist/openSUSE_Leap-15.4/Desktop/README.md) and [notebooks](/Dist/openSUSE_Leap-15.4/Notebook/README.md).

Contents
--------

* [ Test Cases ](#test-cases)

* [ System ](#system)
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

Total: 168

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| ASRock        | B550M-ITX/ac                | Desktop     | [0295ab04a7](https://linux-hardware.org/?probe=0295ab04a7) | Apr 28, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [ec41184680](https://linux-hardware.org/?probe=ec41184680) | Apr 27, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [3ec3c7aa7b](https://linux-hardware.org/?probe=3ec3c7aa7b) | Apr 26, 2023 |
| ASUSTek       | N750JV                      | Notebook    | [53c0f79af9](https://linux-hardware.org/?probe=53c0f79af9) | Apr 26, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [4fad4d4a09](https://linux-hardware.org/?probe=4fad4d4a09) | Apr 21, 2023 |
| Gateway       | NV55C                       | Notebook    | [e77192c3b1](https://linux-hardware.org/?probe=e77192c3b1) | Apr 20, 2023 |
| Lenovo        | ThinkPad T16 Gen 1 21BVC... | Notebook    | [69b2b1c95f](https://linux-hardware.org/?probe=69b2b1c95f) | Apr 19, 2023 |
| Gigabyte      | H55M-S2H                    | Desktop     | [f44b68cf93](https://linux-hardware.org/?probe=f44b68cf93) | Apr 16, 2023 |
| HP            | Mini 210-1000               | Notebook    | [e8b0b26e10](https://linux-hardware.org/?probe=e8b0b26e10) | Apr 15, 2023 |
| ASRock        | X670E Pro RS                | Desktop     | [0f078152ca](https://linux-hardware.org/?probe=0f078152ca) | Apr 10, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [19fd2b6d0d](https://linux-hardware.org/?probe=19fd2b6d0d) | Apr 09, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [bc402eee2e](https://linux-hardware.org/?probe=bc402eee2e) | Apr 09, 2023 |
| ASRock        | B450 Gaming K4              | Desktop     | [dcf97ad331](https://linux-hardware.org/?probe=dcf97ad331) | Apr 05, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [f89b2c8b2a](https://linux-hardware.org/?probe=f89b2c8b2a) | Apr 05, 2023 |
| HP            | EliteBook 865 16 inch G9... | Notebook    | [6906a8d309](https://linux-hardware.org/?probe=6906a8d309) | Apr 03, 2023 |
| MSI           | P67A-C43                    | Desktop     | [f3e7913310](https://linux-hardware.org/?probe=f3e7913310) | Apr 01, 2023 |
| ASUSTek       | N550JX                      | Notebook    | [a505a62a71](https://linux-hardware.org/?probe=a505a62a71) | Mar 28, 2023 |
| Fujitsu       | LIFEBOOK U938               | Notebook    | [e972904a83](https://linux-hardware.org/?probe=e972904a83) | Mar 28, 2023 |
| HP            | Compaq 6730s                | Notebook    | [8d4cea5a81](https://linux-hardware.org/?probe=8d4cea5a81) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [6f4e3ec28b](https://linux-hardware.org/?probe=6f4e3ec28b) | Mar 28, 2023 |
| MSI           | Delta 15 A5EFK              | Notebook    | [9dd1b67b2f](https://linux-hardware.org/?probe=9dd1b67b2f) | Mar 28, 2023 |
| Packard Be... | EasyNote TE11HC             | Notebook    | [6c942c5a39](https://linux-hardware.org/?probe=6c942c5a39) | Mar 26, 2023 |
| ASUSTek       | ROG CROSSHAIR X670E HERO    | Desktop     | [f78ca791e0](https://linux-hardware.org/?probe=f78ca791e0) | Mar 25, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [dfd3b8546c](https://linux-hardware.org/?probe=dfd3b8546c) | Mar 14, 2023 |
| Lenovo        | ThinkPad Edge E530 3259H... | Notebook    | [74348d01f3](https://linux-hardware.org/?probe=74348d01f3) | Mar 13, 2023 |
| Wortmann      | Terra 3100                  | Desktop     | [126586f434](https://linux-hardware.org/?probe=126586f434) | Mar 12, 2023 |
| Intel         | NUC12WSBi5 M46425-302       | Mini pc     | [2002eaa403](https://linux-hardware.org/?probe=2002eaa403) | Mar 12, 2023 |
| Lenovo        | ThinkPad T520 42435GG       | Notebook    | [fac1ee2528](https://linux-hardware.org/?probe=fac1ee2528) | Mar 12, 2023 |
| Lenovo        | 102F SDK0J40697 WIN 3305... | Desktop     | [97741c600c](https://linux-hardware.org/?probe=97741c600c) | Mar 11, 2023 |
| Jumper        | EZbook                      | Notebook    | [ed607c4113](https://linux-hardware.org/?probe=ed607c4113) | Mar 11, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [5cb06ca8ce](https://linux-hardware.org/?probe=5cb06ca8ce) | Mar 10, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [4b47face39](https://linux-hardware.org/?probe=4b47face39) | Mar 05, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [268413a47c](https://linux-hardware.org/?probe=268413a47c) | Mar 01, 2023 |
| Lenovo        | Bantry CRB 31900058 STD     | Desktop     | [169e938f25](https://linux-hardware.org/?probe=169e938f25) | Mar 01, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [ca878d6577](https://linux-hardware.org/?probe=ca878d6577) | Feb 27, 2023 |
| Samsung       | 550XDA                      | Notebook    | [0c3e0dd389](https://linux-hardware.org/?probe=0c3e0dd389) | Feb 13, 2023 |
| ASRock        | B550M-ITX/ac                | Desktop     | [79204339d0](https://linux-hardware.org/?probe=79204339d0) | Feb 11, 2023 |
| HP            | 1494                        | Desktop     | [ba7c61bf23](https://linux-hardware.org/?probe=ba7c61bf23) | Feb 07, 2023 |
| HP            | 0B54h D                     | Desktop     | [fa38931f1f](https://linux-hardware.org/?probe=fa38931f1f) | Feb 06, 2023 |
| TUXEDO        | InfinityBook S 15/17 Gen... | Notebook    | [9b92561723](https://linux-hardware.org/?probe=9b92561723) | Feb 06, 2023 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [f05a20fe00](https://linux-hardware.org/?probe=f05a20fe00) | Feb 01, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [f2636de53b](https://linux-hardware.org/?probe=f2636de53b) | Jan 31, 2023 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [32dfb5ebe2](https://linux-hardware.org/?probe=32dfb5ebe2) | Jan 31, 2023 |
| Lenovo        | ThinkPad Edge E431 62779... | Notebook    | [8d7c1dbf4d](https://linux-hardware.org/?probe=8d7c1dbf4d) | Jan 30, 2023 |
| Gigabyte      | Z690 GAMING X DDR4          | Desktop     | [6bf8eb9c73](https://linux-hardware.org/?probe=6bf8eb9c73) | Jan 30, 2023 |
| Toshiba       | Satellite L500              | Notebook    | [327e2d4e3e](https://linux-hardware.org/?probe=327e2d4e3e) | Jan 28, 2023 |
| Lenovo        | IdeaPad 330-15IKB 81FD      | Notebook    | [31698019a3](https://linux-hardware.org/?probe=31698019a3) | Jan 20, 2023 |
| Lenovo        | ThinkPad X1 Carbon 7th 2... | Notebook    | [004b2669ef](https://linux-hardware.org/?probe=004b2669ef) | Jan 18, 2023 |
| HP            | ProBook 4540s               | Notebook    | [3f9e3a1cbb](https://linux-hardware.org/?probe=3f9e3a1cbb) | Jan 17, 2023 |
| HP            | ProBook 4540s               | Notebook    | [7b9cd1b51c](https://linux-hardware.org/?probe=7b9cd1b51c) | Jan 16, 2023 |
| ASUSTek       | PRIME A320M-K               | Desktop     | [17fd020689](https://linux-hardware.org/?probe=17fd020689) | Jan 16, 2023 |
| HP            | EliteBook 840 G8 Noteboo... | Notebook    | [9b874af8a4](https://linux-hardware.org/?probe=9b874af8a4) | Jan 16, 2023 |
| Dell          | 0WG261                      | Desktop     | [c994d9e8ee](https://linux-hardware.org/?probe=c994d9e8ee) | Jan 13, 2023 |
| Dell          | 0WG261                      | Desktop     | [5d1fe40a1f](https://linux-hardware.org/?probe=5d1fe40a1f) | Jan 13, 2023 |
| Lenovo        | IdeaPad L340-15IRH Gamin... | Notebook    | [a5ea710efd](https://linux-hardware.org/?probe=a5ea710efd) | Jan 11, 2023 |
| Dell          | 081VG9 A05                  | Server      | [23031aa11a](https://linux-hardware.org/?probe=23031aa11a) | Jan 06, 2023 |
| Lenovo        | ThinkPad P16s Gen 1 21BT... | Notebook    | [b68fa80860](https://linux-hardware.org/?probe=b68fa80860) | Dec 31, 2022 |
| HP            | Victus by Laptop 16-e0xx... | Notebook    | [60989ad0c4](https://linux-hardware.org/?probe=60989ad0c4) | Dec 31, 2022 |
| Dell          | Inspiron 15 7510            | Notebook    | [d5702b0c66](https://linux-hardware.org/?probe=d5702b0c66) | Dec 24, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [8a3788aa78](https://linux-hardware.org/?probe=8a3788aa78) | Dec 23, 2022 |
| Dell          | Vostro 3501                 | Notebook    | [258dc5c40d](https://linux-hardware.org/?probe=258dc5c40d) | Dec 23, 2022 |
| Schenker      | VIA 15 Pro                  | Notebook    | [b1a40c91d2](https://linux-hardware.org/?probe=b1a40c91d2) | Dec 22, 2022 |
| Schenker      | VIA 15 Pro                  | Notebook    | [75efe6fb52](https://linux-hardware.org/?probe=75efe6fb52) | Dec 22, 2022 |
| Acer          | Aspire E1-572G              | Notebook    | [adc5196d64](https://linux-hardware.org/?probe=adc5196d64) | Dec 17, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [1e2ba2a16d](https://linux-hardware.org/?probe=1e2ba2a16d) | Dec 14, 2022 |
| HP            | Spectre x360 Convertible... | Convertible | [9369afea1b](https://linux-hardware.org/?probe=9369afea1b) | Dec 14, 2022 |
| MSI           | X470 GAMING PRO CARBON      | Desktop     | [947534b3be](https://linux-hardware.org/?probe=947534b3be) | Dec 09, 2022 |
| ASUSTek       | PRIME B350M-A               | Desktop     | [31ae5769eb](https://linux-hardware.org/?probe=31ae5769eb) | Dec 07, 2022 |
| MSI           | B85-G41 PC Mate             | Desktop     | [a54611689d](https://linux-hardware.org/?probe=a54611689d) | Dec 06, 2022 |
| ASUSTek       | Z450LA                      | Notebook    | [ffd2220d21](https://linux-hardware.org/?probe=ffd2220d21) | Nov 25, 2022 |
| Dell          | Latitude E5570              | Notebook    | [ed2e9cfb4f](https://linux-hardware.org/?probe=ed2e9cfb4f) | Nov 24, 2022 |
| Lenovo        | ThinkPad T530 2394D56       | Notebook    | [3d44b768e5](https://linux-hardware.org/?probe=3d44b768e5) | Nov 12, 2022 |
| HP            | ZBook 17                    | Notebook    | [e866fa1319](https://linux-hardware.org/?probe=e866fa1319) | Nov 09, 2022 |
| HP            | ZBook 17                    | Notebook    | [af26e94623](https://linux-hardware.org/?probe=af26e94623) | Nov 08, 2022 |
| Dell          | 0C522T A01                  | Desktop     | [efee8139b0](https://linux-hardware.org/?probe=efee8139b0) | Nov 01, 2022 |
| Gigabyte      | GA-770TA-UD3                | Desktop     | [4833a609c3](https://linux-hardware.org/?probe=4833a609c3) | Oct 31, 2022 |
| Lenovo        | ThinkPad X1 Carbon Gen 1... | Notebook    | [dcd40f9f78](https://linux-hardware.org/?probe=dcd40f9f78) | Oct 28, 2022 |
| Dell          | Latitude 9420               | Notebook    | [a601281b46](https://linux-hardware.org/?probe=a601281b46) | Oct 27, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [3a60ac01f4](https://linux-hardware.org/?probe=3a60ac01f4) | Oct 23, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [94f3d7aa9d](https://linux-hardware.org/?probe=94f3d7aa9d) | Oct 22, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [fbc271b648](https://linux-hardware.org/?probe=fbc271b648) | Oct 22, 2022 |
| HP            | ZBook 17                    | Notebook    | [6dc9848327](https://linux-hardware.org/?probe=6dc9848327) | Oct 20, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [a29fae2a74](https://linux-hardware.org/?probe=a29fae2a74) | Oct 14, 2022 |
| Toshiba       | Satellite P55t-A            | Notebook    | [60d52e85a0](https://linux-hardware.org/?probe=60d52e85a0) | Oct 12, 2022 |
| MSI           | Z170-A PRO                  | Desktop     | [50b8cde0ed](https://linux-hardware.org/?probe=50b8cde0ed) | Oct 10, 2022 |
| ASUSTek       | F3Sv                        | Notebook    | [042104bbc2](https://linux-hardware.org/?probe=042104bbc2) | Oct 08, 2022 |
| Dell          | 0D90HM A00                  | All in one  | [9ef16d569e](https://linux-hardware.org/?probe=9ef16d569e) | Oct 06, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c12ce7288b](https://linux-hardware.org/?probe=c12ce7288b) | Oct 05, 2022 |
| MSI           | B450-A PRO MAX              | Desktop     | [c3306965d6](https://linux-hardware.org/?probe=c3306965d6) | Oct 05, 2022 |
| Lenovo        | ThinkPad T470 20HES0FW00    | Notebook    | [33a0cb05e8](https://linux-hardware.org/?probe=33a0cb05e8) | Oct 04, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [79f922d367](https://linux-hardware.org/?probe=79f922d367) | Oct 02, 2022 |
| Dell          | Vostro 3560                 | Notebook    | [59c14fb5c0](https://linux-hardware.org/?probe=59c14fb5c0) | Oct 02, 2022 |
| Dell          | Latitude E5250              | Notebook    | [6116460e52](https://linux-hardware.org/?probe=6116460e52) | Sep 27, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [d6d9af3173](https://linux-hardware.org/?probe=d6d9af3173) | Sep 26, 2022 |
| HP            | ZBook 17 G2                 | Notebook    | [ff70118578](https://linux-hardware.org/?probe=ff70118578) | Sep 26, 2022 |
| Dell          | Inspiron 5515               | Notebook    | [a7f0e24464](https://linux-hardware.org/?probe=a7f0e24464) | Sep 20, 2022 |
| Dell          | Inspiron 3542               | Notebook    | [7f7ef47d4b](https://linux-hardware.org/?probe=7f7ef47d4b) | Sep 20, 2022 |
| ASUSTek       | X55CR                       | Notebook    | [43b77d436c](https://linux-hardware.org/?probe=43b77d436c) | Sep 14, 2022 |
| ASUSTek       | ROG CROSSHAIR VIII EXTRE... | Desktop     | [6e0984d7ff](https://linux-hardware.org/?probe=6e0984d7ff) | Sep 06, 2022 |
| ASUSTek       | P5P43TD PRO                 | Desktop     | [f79c38f9ff](https://linux-hardware.org/?probe=f79c38f9ff) | Sep 02, 2022 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [3772ec2911](https://linux-hardware.org/?probe=3772ec2911) | Sep 02, 2022 |
| ASUSTek       | VivoBook_ASUSLaptop X421... | Notebook    | [dea9852124](https://linux-hardware.org/?probe=dea9852124) | Sep 02, 2022 |
| HP            | ZBook 17                    | Notebook    | [98e643f5af](https://linux-hardware.org/?probe=98e643f5af) | Aug 30, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [e27f786190](https://linux-hardware.org/?probe=e27f786190) | Aug 28, 2022 |
| Google        | Eldrid                      | Notebook    | [6a0c6eb1de](https://linux-hardware.org/?probe=6a0c6eb1de) | Aug 27, 2022 |
| Gigabyte      | 965P-DS3                    | Desktop     | [38a4407789](https://linux-hardware.org/?probe=38a4407789) | Aug 25, 2022 |
| HP            | 802F                        | Desktop     | [2c52215323](https://linux-hardware.org/?probe=2c52215323) | Aug 23, 2022 |
| HP            | 802F                        | Desktop     | [e181d03426](https://linux-hardware.org/?probe=e181d03426) | Aug 23, 2022 |
| ASRock        | Z490 Phantom Gaming 4       | Desktop     | [7b66b20b9f](https://linux-hardware.org/?probe=7b66b20b9f) | Aug 17, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [0e2658915d](https://linux-hardware.org/?probe=0e2658915d) | Aug 17, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [a05b95b836](https://linux-hardware.org/?probe=a05b95b836) | Aug 15, 2022 |
| HP            | Pavilion Notebook           | Notebook    | [aea2bfde6a](https://linux-hardware.org/?probe=aea2bfde6a) | Aug 15, 2022 |
| Acer          | Aspire 4732Z                | Notebook    | [73027b2cca](https://linux-hardware.org/?probe=73027b2cca) | Aug 07, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [99f7986364](https://linux-hardware.org/?probe=99f7986364) | Aug 02, 2022 |
| Unknown       | Unknown                     | Notebook    | [4d9a472691](https://linux-hardware.org/?probe=4d9a472691) | Jul 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [ded9f7587a](https://linux-hardware.org/?probe=ded9f7587a) | Jul 27, 2022 |
| Unknown       | Unknown                     | Notebook    | [0c4182ee0a](https://linux-hardware.org/?probe=0c4182ee0a) | Jul 23, 2022 |
| Unknown       | Unknown                     | Notebook    | [7a29580deb](https://linux-hardware.org/?probe=7a29580deb) | Jul 23, 2022 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [df5bd62f9a](https://linux-hardware.org/?probe=df5bd62f9a) | Jul 23, 2022 |
| Notebook      | NLx0MU                      | Notebook    | [7cb795f428](https://linux-hardware.org/?probe=7cb795f428) | Jul 22, 2022 |
| Biostar       | B450MH                      | Desktop     | [f69c4e3a03](https://linux-hardware.org/?probe=f69c4e3a03) | Jul 21, 2022 |
| Biostar       | B450MH                      | Desktop     | [79084ef4c9](https://linux-hardware.org/?probe=79084ef4c9) | Jul 21, 2022 |
| ASUSTek       | TUF Gaming X570-PRO         | Desktop     | [f2cda5634e](https://linux-hardware.org/?probe=f2cda5634e) | Jul 18, 2022 |
| MSI           | B450 GAMING PRO CARBON A... | Desktop     | [03d7fde009](https://linux-hardware.org/?probe=03d7fde009) | Jul 18, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [5ac3a7aa95](https://linux-hardware.org/?probe=5ac3a7aa95) | Jul 17, 2022 |
| Dell          | 0Y2YM6 A00                  | Desktop     | [8b5480a55e](https://linux-hardware.org/?probe=8b5480a55e) | Jul 16, 2022 |
| Dell          | Inspiron 5584               | Notebook    | [b6d23c8307](https://linux-hardware.org/?probe=b6d23c8307) | Jul 16, 2022 |
| Multilaser    | PC150                       | Notebook    | [b6fcf6d507](https://linux-hardware.org/?probe=b6fcf6d507) | Jul 04, 2022 |
| MSI           | X399 GAMING PRO CARBON A... | Desktop     | [153a698b74](https://linux-hardware.org/?probe=153a698b74) | Jul 01, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [bec2a7697f](https://linux-hardware.org/?probe=bec2a7697f) | Jun 30, 2022 |
| Dell          | 0J3C2F A03                  | Desktop     | [6f5f6a7417](https://linux-hardware.org/?probe=6f5f6a7417) | Jun 26, 2022 |
| ASRock        | J3355B-ITX                  | Desktop     | [a00111330b](https://linux-hardware.org/?probe=a00111330b) | Jun 24, 2022 |
| Acer          | Swift SFX14-41G             | Notebook    | [c3c9ce7e40](https://linux-hardware.org/?probe=c3c9ce7e40) | Jun 23, 2022 |
| ASUSTek       | TUF Gaming Z590-PLUS        | Desktop     | [520f9b42b8](https://linux-hardware.org/?probe=520f9b42b8) | Jun 20, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [ff63b72fd2](https://linux-hardware.org/?probe=ff63b72fd2) | Jun 19, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [3ec9bac70f](https://linux-hardware.org/?probe=3ec9bac70f) | Jun 17, 2022 |
| Lenovo        | IdeaPad Gaming 3 15IMH05... | Notebook    | [cc0719c813](https://linux-hardware.org/?probe=cc0719c813) | Jun 16, 2022 |
| HP            | ProBook 455 G8 Notebook ... | Notebook    | [52276b3971](https://linux-hardware.org/?probe=52276b3971) | Jun 16, 2022 |
| HP            | Laptop 15s-eq0xxx           | Notebook    | [74770880f9](https://linux-hardware.org/?probe=74770880f9) | Jun 15, 2022 |
| HP            | Mini 210-1000               | Notebook    | [8746b5b684](https://linux-hardware.org/?probe=8746b5b684) | Jun 10, 2022 |
| HP            | 87C3                        | Desktop     | [1383f85e70](https://linux-hardware.org/?probe=1383f85e70) | Jun 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [06e496124a](https://linux-hardware.org/?probe=06e496124a) | Jun 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [fd421da52b](https://linux-hardware.org/?probe=fd421da52b) | Jun 08, 2022 |
| Toshiba       | Satellite L500              | Notebook    | [b4b4831c86](https://linux-hardware.org/?probe=b4b4831c86) | Jun 05, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [aae8744a5c](https://linux-hardware.org/?probe=aae8744a5c) | May 31, 2022 |
| MSI           | B450 TOMAHAWK               | Desktop     | [0020802901](https://linux-hardware.org/?probe=0020802901) | May 30, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [0f70996b58](https://linux-hardware.org/?probe=0f70996b58) | May 15, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [e01bfd360d](https://linux-hardware.org/?probe=e01bfd360d) | May 14, 2022 |
| ASUSTek       | PRIME B550M-A WIFI II       | Desktop     | [2e8f888ca3](https://linux-hardware.org/?probe=2e8f888ca3) | May 11, 2022 |
| ASUSTek       | M5A78L-M/USB3               | Desktop     | [ace8669bdd](https://linux-hardware.org/?probe=ace8669bdd) | May 10, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [99078d316d](https://linux-hardware.org/?probe=99078d316d) | May 10, 2022 |
| Lenovo        | ThinkPad T495s 20QJ0012U... | Notebook    | [2add3d77c6](https://linux-hardware.org/?probe=2add3d77c6) | May 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E          | Desktop     | [a3c1257116](https://linux-hardware.org/?probe=a3c1257116) | May 09, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [27b384c114](https://linux-hardware.org/?probe=27b384c114) | May 08, 2022 |
| ASUSTek       | TUF Gaming B550M-E WIFI     | Desktop     | [d427368abd](https://linux-hardware.org/?probe=d427368abd) | May 08, 2022 |
| Samsung       | 550XDA                      | Notebook    | [a616d83a41](https://linux-hardware.org/?probe=a616d83a41) | May 07, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [622ff28b28](https://linux-hardware.org/?probe=622ff28b28) | May 05, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [e5a11e0fdd](https://linux-hardware.org/?probe=e5a11e0fdd) | May 04, 2022 |
| ASUSTek       | CROSSHAIR V FORMULA-Z       | Desktop     | [34dcc7bc0c](https://linux-hardware.org/?probe=34dcc7bc0c) | May 04, 2022 |
| ASUSTek       | M4A785TD-V EVO              | Desktop     | [aea37c880d](https://linux-hardware.org/?probe=aea37c880d) | May 04, 2022 |
| Lenovo        | ThinkPad P50 20EQS0VV0C     | Notebook    | [4ce87e4da1](https://linux-hardware.org/?probe=4ce87e4da1) | May 04, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [584ec1055a](https://linux-hardware.org/?probe=584ec1055a) | May 03, 2022 |
| Lenovo        | ThinkPad T410 25223FG       | Notebook    | [2e4fdc00b2](https://linux-hardware.org/?probe=2e4fdc00b2) | May 03, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [652cd5fc07](https://linux-hardware.org/?probe=652cd5fc07) | Apr 06, 2022 |
| LG Electro... | C400-G.BC22P1               | Notebook    | [fb656318f6](https://linux-hardware.org/?probe=fb656318f6) | Feb 27, 2022 |
| ASUSTek       | ROG Strix G713QE_G713QE     | Notebook    | [af586bb69e](https://linux-hardware.org/?probe=af586bb69e) | Feb 05, 2022 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [c2d30af3ce](https://linux-hardware.org/?probe=c2d30af3ce) | Dec 25, 2021 |
| Intel         | DG965RY AAD41691-301        | Desktop     | [586e536e6c](https://linux-hardware.org/?probe=586e536e6c) | Dec 25, 2021 |

System
------

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                             | Computers | Percent |
|-------------------------------------|-----------|---------|
| 5.14.21-150400.22-default           | 24        | 18.46%  |
| 5.14.21-150400.24.21-default        | 16        | 12.31%  |
| 5.14.21-150400.24.46-default        | 15        | 11.54%  |
| 5.14.21-150400.24.41-default        | 10        | 7.69%   |
| 5.14.21-150400.24.38-default        | 10        | 7.69%   |
| 5.14.21-150400.24.18-default        | 10        | 7.69%   |
| 5.14.21-150400.19-default           | 10        | 7.69%   |
| 5.14.21-150400.24.55-default        | 9         | 6.92%   |
| 5.14.21-150400.24.33-default        | 9         | 6.92%   |
| 5.14.21-150400.24.60-default        | 4         | 3.08%   |
| 5.14.21-150400.24.11-default        | 4         | 3.08%   |
| 5.18.0-rc6-lp153.2.ged50f8f-default | 2         | 1.54%   |
| 5.14.21-150400.24.28-default        | 2         | 1.54%   |
| 5.18.2-lp153.4.g6d13af9-default     | 1         | 0.77%   |
| 5.14.21-150400.9-default            | 1         | 0.77%   |
| 5.14.21-150400.3-default            | 1         | 0.77%   |
| 5.14.21-150400.15-default           | 1         | 0.77%   |
| 5.14.19-150400.1-default            | 1         | 0.77%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.21 | 111       | 96.52%  |
| 5.18.0  | 2         | 1.74%   |
| 5.18.2  | 1         | 0.87%   |
| 5.14.19 | 1         | 0.87%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 112       | 97.39%  |
| 5.18    | 3         | 2.61%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 114       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KDE5        | 80        | 70.18%  |
| GNOME       | 15        | 13.16%  |
| Unknown     | 8         | 7.02%   |
| XFCE        | 5         | 4.39%   |
| Cinnamon    | 2         | 1.75%   |
| X-Cinnamon  | 1         | 0.88%   |
| WindowMaker | 1         | 0.88%   |
| LXDE        | 1         | 0.88%   |
| ICEWM       | 1         | 0.88%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 95        | 82.61%  |
| Wayland | 13        | 11.3%   |
| Tty     | 5         | 4.35%   |
| Unknown | 2         | 1.74%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 51        | 44.74%  |
| SDDM    | 37        | 32.46%  |
| LightDM | 21        | 18.42%  |
| XDM     | 5         | 4.39%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 42        | 36.84%  |
| de_DE   | 19        | 16.67%  |
| pt_BR   | 13        | 11.4%   |
| POSIX   | 13        | 11.4%   |
| nl_NL   | 4         | 3.51%   |
| es_ES   | 4         | 3.51%   |
| en_GB   | 4         | 3.51%   |
| fr_FR   | 3         | 2.63%   |
| ru_RU   | 2         | 1.75%   |
| nn_NO   | 2         | 1.75%   |
| ro_RO   | 1         | 0.88%   |
| pl_PL   | 1         | 0.88%   |
| it_IT   | 1         | 0.88%   |
| hu_HU   | 1         | 0.88%   |
| el_GR   | 1         | 0.88%   |
| de_CH   | 1         | 0.88%   |
| ca_ES   | 1         | 0.88%   |
| Unknown | 1         | 0.88%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 70        | 61.4%   |
| EFI  | 44        | 38.6%   |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type  | Computers | Percent |
|-------|-----------|---------|
| Btrfs | 80        | 70.18%  |
| Ext4  | 27        | 23.68%  |
| Xfs   | 6         | 5.26%   |
| Ext3  | 1         | 0.88%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 56        | 49.12%  |
| Unknown | 48        | 42.11%  |
| MBR     | 10        | 8.77%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 103       | 89.57%  |
| Yes       | 12        | 10.43%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 95        | 83.33%  |
| Yes       | 19        | 16.67%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 23        | 20.18%  |
| Hewlett-Packard     | 18        | 15.79%  |
| Lenovo              | 17        | 14.91%  |
| Dell                | 16        | 14.04%  |
| MSI                 | 9         | 7.89%   |
| Gigabyte Technology | 5         | 4.39%   |
| ASRock              | 5         | 4.39%   |
| Acer                | 3         | 2.63%   |
| Toshiba             | 2         | 1.75%   |
| Samsung Electronics | 2         | 1.75%   |
| Intel               | 2         | 1.75%   |
| Unknown             | 2         | 1.75%   |
| Wortmann AG         | 1         | 0.88%   |
| TUXEDO              | 1         | 0.88%   |
| Schenker            | 1         | 0.88%   |
| Notebook            | 1         | 0.88%   |
| Multilaser          | 1         | 0.88%   |
| LG Electronics      | 1         | 0.88%   |
| Jumper              | 1         | 0.88%   |
| Gateway             | 1         | 0.88%   |
| Fujitsu             | 1         | 0.88%   |
| Biostar             | 1         | 0.88%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung 550XDA                           | 2         | 1.75%   |
| HP Spectre x360 Convertible 13t-aw100    | 2         | 1.75%   |
| ASUS TUF Gaming B550M-E                  | 2         | 1.75%   |
| ASUS M4A785TD-V EVO                      | 2         | 1.75%   |
| ASUS CROSSHAIR V FORMULA-Z               | 2         | 1.75%   |
| Unknown                                  | 2         | 1.75%   |
| Wortmann AG Terra 3100                   | 1         | 0.88%   |
| TUXEDO InfinityBook S 15/17 Gen7         | 1         | 0.88%   |
| Toshiba Satellite P55t-A                 | 1         | 0.88%   |
| Toshiba Satellite L500                   | 1         | 0.88%   |
| Schenker VIA 15 Pro                      | 1         | 0.88%   |
| Notebook NLx0MU                          | 1         | 0.88%   |
| Multilaser PC150                         | 1         | 0.88%   |
| MSI MS-7C02                              | 1         | 0.88%   |
| MSI MS-7B86                              | 1         | 0.88%   |
| MSI MS-7B85                              | 1         | 0.88%   |
| MSI MS-7B78                              | 1         | 0.88%   |
| MSI MS-7B09                              | 1         | 0.88%   |
| MSI MS-7971                              | 1         | 0.88%   |
| MSI MS-7850                              | 1         | 0.88%   |
| MSI MS-7673                              | 1         | 0.88%   |
| MSI Delta 15 A5EFK                       | 1         | 0.88%   |
| LG C400-G.BC22P1                         | 1         | 0.88%   |
| Lenovo ThinkStation P520 30BE008VGE      | 1         | 0.88%   |
| Lenovo ThinkStation P500 30A6S4JU00      | 1         | 0.88%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDS3B600 | 1         | 0.88%   |
| Lenovo ThinkPad T530 2394D56             | 1         | 0.88%   |
| Lenovo ThinkPad T520 42435GG             | 1         | 0.88%   |
| Lenovo ThinkPad T495s 20QJ0012UK         | 1         | 0.88%   |
| Lenovo ThinkPad T470 20HES0FW00          | 1         | 0.88%   |
| Lenovo ThinkPad T410 25223FG             | 1         | 0.88%   |
| Lenovo ThinkPad T16 Gen 1 21BVCTO1WW     | 1         | 0.88%   |
| Lenovo ThinkPad P50 20EQS0VV0C           | 1         | 0.88%   |
| Lenovo ThinkPad P16s Gen 1 21BT000MUK    | 1         | 0.88%   |
| Lenovo ThinkPad Edge E530 3259HHG        | 1         | 0.88%   |
| Lenovo ThinkPad Edge E431 62779XP        | 1         | 0.88%   |
| Lenovo IdeaPad L340-15IRH Gaming 81LK    | 1         | 0.88%   |
| Lenovo IdeaPad Gaming 3 15IMH05 82CG     | 1         | 0.88%   |
| Lenovo IdeaPad 330-15IKB 81FD            | 1         | 0.88%   |
| Lenovo H50-55 90BF001SUK                 | 1         | 0.88%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 11        | 9.65%   |
| Dell Inspiron       | 5         | 4.39%   |
| ASUS TUF            | 5         | 4.39%   |
| ASUS PRIME          | 4         | 3.51%   |
| Lenovo IdeaPad      | 3         | 2.63%   |
| Dell Vostro         | 3         | 2.63%   |
| Dell Latitude       | 3         | 2.63%   |
| ASUS ROG            | 3         | 2.63%   |
| Toshiba Satellite   | 2         | 1.75%   |
| Samsung 550XDA      | 2         | 1.75%   |
| Lenovo ThinkStation | 2         | 1.75%   |
| HP ZBook            | 2         | 1.75%   |
| HP Spectre          | 2         | 1.75%   |
| HP ProBook          | 2         | 1.75%   |
| HP EliteBook        | 2         | 1.75%   |
| HP Compaq           | 2         | 1.75%   |
| Dell OptiPlex       | 2         | 1.75%   |
| ASUS M4A785TD-V     | 2         | 1.75%   |
| ASUS CROSSHAIR      | 2         | 1.75%   |
| Acer Aspire         | 2         | 1.75%   |
| Unknown             | 2         | 1.75%   |
| Wortmann AG Terra   | 1         | 0.88%   |
| TUXEDO InfinityBook | 1         | 0.88%   |
| Schenker VIA        | 1         | 0.88%   |
| Notebook NLx0MU     | 1         | 0.88%   |
| Multilaser PC150    | 1         | 0.88%   |
| MSI MS-7C02         | 1         | 0.88%   |
| MSI MS-7B86         | 1         | 0.88%   |
| MSI MS-7B85         | 1         | 0.88%   |
| MSI MS-7B78         | 1         | 0.88%   |
| MSI MS-7B09         | 1         | 0.88%   |
| MSI MS-7971         | 1         | 0.88%   |
| MSI MS-7850         | 1         | 0.88%   |
| MSI MS-7673         | 1         | 0.88%   |
| MSI Delta           | 1         | 0.88%   |
| LG C400-G.BC22P1    | 1         | 0.88%   |
| Lenovo H50-55       | 1         | 0.88%   |
| Jumper EZbook       | 1         | 0.88%   |
| Intel NUC12WSHi5    | 1         | 0.88%   |
| Intel DG965RY       | 1         | 0.88%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 24        | 21.05%  |
| 2022 | 10        | 8.77%   |
| 2019 | 9         | 7.89%   |
| 2020 | 8         | 7.02%   |
| 2018 | 8         | 7.02%   |
| 2009 | 8         | 7.02%   |
| 2017 | 6         | 5.26%   |
| 2015 | 6         | 5.26%   |
| 2014 | 6         | 5.26%   |
| 2012 | 6         | 5.26%   |
| 2011 | 6         | 5.26%   |
| 2013 | 5         | 4.39%   |
| 2010 | 4         | 3.51%   |
| 2016 | 3         | 2.63%   |
| 2007 | 2         | 1.75%   |
| 2008 | 1         | 0.88%   |
| 2006 | 1         | 0.88%   |
| 2005 | 1         | 0.88%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 58        | 50.88%  |
| Desktop     | 50        | 43.86%  |
| Convertible | 3         | 2.63%   |
| Mini pc     | 1         | 0.88%   |
| All in one  | 1         | 0.88%   |
| Server      | 1         | 0.88%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 105       | 92.11%  |
| Enabled  | 9         | 7.89%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 114       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 32.01-64.0  | 22        | 19.13%  |
| 16.01-24.0  | 20        | 17.39%  |
| 8.01-16.0   | 20        | 17.39%  |
| 4.01-8.0    | 18        | 15.65%  |
| 3.01-4.0    | 15        | 13.04%  |
| 64.01-256.0 | 11        | 9.57%   |
| 24.01-32.0  | 5         | 4.35%   |
| 2.01-3.0    | 2         | 1.74%   |
| 1.01-2.0    | 1         | 0.87%   |
| 0.51-1.0    | 1         | 0.87%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 1.01-2.0  | 35        | 28.93%  |
| 2.01-3.0  | 31        | 25.62%  |
| 4.01-8.0  | 25        | 20.66%  |
| 3.01-4.0  | 16        | 13.22%  |
| 0.51-1.0  | 7         | 5.79%   |
| 8.01-16.0 | 6         | 4.96%   |
| 0.01-0.5  | 1         | 0.83%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 61        | 51.69%  |
| 2      | 33        | 27.97%  |
| 3      | 11        | 9.32%   |
| 5      | 5         | 4.24%   |
| 7      | 3         | 2.54%   |
| 4      | 3         | 2.54%   |
| 9      | 1         | 0.85%   |
| 6      | 1         | 0.85%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 66        | 57.89%  |
| Yes       | 48        | 42.11%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 104       | 90.43%  |
| No        | 11        | 9.57%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 81        | 71.05%  |
| No        | 33        | 28.95%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 71        | 61.74%  |
| No        | 44        | 38.26%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 29        | 25.44%  |
| USA          | 20        | 17.54%  |
| Brazil       | 13        | 11.4%   |
| UK           | 5         | 4.39%   |
| Spain        | 5         | 4.39%   |
| Russia       | 5         | 4.39%   |
| Netherlands  | 5         | 4.39%   |
| Italy        | 4         | 3.51%   |
| Norway       | 3         | 2.63%   |
| France       | 3         | 2.63%   |
| Switzerland  | 2         | 1.75%   |
| South Africa | 2         | 1.75%   |
| Mexico       | 2         | 1.75%   |
| Taiwan       | 1         | 0.88%   |
| Sweden       | 1         | 0.88%   |
| Slovenia     | 1         | 0.88%   |
| Serbia       | 1         | 0.88%   |
| Romania      | 1         | 0.88%   |
| Poland       | 1         | 0.88%   |
| Martinique   | 1         | 0.88%   |
| Kazakhstan   | 1         | 0.88%   |
| Indonesia    | 1         | 0.88%   |
| India        | 1         | 0.88%   |
| Hungary      | 1         | 0.88%   |
| Greece       | 1         | 0.88%   |
| Finland      | 1         | 0.88%   |
| Czechia      | 1         | 0.88%   |
| Bulgaria     | 1         | 0.88%   |
| Australia    | 1         | 0.88%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City             | Computers | Percent |
|------------------|-----------|---------|
| Haßfurt         | 5         | 4.07%   |
| Madrid           | 3         | 2.44%   |
| Darmstadt        | 3         | 2.44%   |
| Almere Stad      | 3         | 2.44%   |
| Sao Paulo        | 2         | 1.63%   |
| Saint Joseph     | 2         | 1.63%   |
| Rio de Janeiro   | 2         | 1.63%   |
| Paris            | 2         | 1.63%   |
| Moscow           | 2         | 1.63%   |
| Louisville       | 2         | 1.63%   |
| London           | 2         | 1.63%   |
| Joinville        | 2         | 1.63%   |
| Berlin           | 2         | 1.63%   |
| Zierikzee        | 1         | 0.81%   |
| Yekaterinburg    | 1         | 0.81%   |
| Vaksdal          | 1         | 0.81%   |
| Ulyanovsk        | 1         | 0.81%   |
| Taichung         | 1         | 0.81%   |
| Sydney           | 1         | 0.81%   |
| Stockholm        | 1         | 0.81%   |
| Stazione-Fornola | 1         | 0.81%   |
| Skokie           | 1         | 0.81%   |
| Schonbuhl        | 1         | 0.81%   |
| Santa Rosa       | 1         | 0.81%   |
| San Francisco    | 1         | 0.81%   |
| Saki             | 1         | 0.81%   |
| Sainte-Tulle     | 1         | 0.81%   |
| Rostock          | 1         | 0.81%   |
| Roslindale       | 1         | 0.81%   |
| Rome             | 1         | 0.81%   |
| Riviere Salee    | 1         | 0.81%   |
| Recife           | 1         | 0.81%   |
| Rattelsdorf      | 1         | 0.81%   |
| Pretoria         | 1         | 0.81%   |
| Pirmasens        | 1         | 0.81%   |
| Peize            | 1         | 0.81%   |
| Pedro Leopoldo   | 1         | 0.81%   |
| Overland Park    | 1         | 0.81%   |
| Osorio           | 1         | 0.81%   |
| Ocala            | 1         | 0.81%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Samsung Electronics            | 38        | 57     | 21.23%  |
| Seagate                        | 35        | 48     | 19.55%  |
| WDC                            | 19        | 34     | 10.61%  |
| Toshiba                        | 11        | 17     | 6.15%   |
| Kingston                       | 11        | 17     | 6.15%   |
| Crucial                        | 8         | 9      | 4.47%   |
| SanDisk                        | 7         | 10     | 3.91%   |
| SK hynix                       | 5         | 5      | 2.79%   |
| Unknown                        | 4         | 5      | 2.23%   |
| Intel                          | 4         | 5      | 2.23%   |
| Hitachi                        | 3         | 4      | 1.68%   |
| PNY                            | 2         | 3      | 1.12%   |
| Patriot                        | 2         | 2      | 1.12%   |
| Maxtor                         | 2         | 2      | 1.12%   |
| Kingston Technology Company    | 2         | 2      | 1.12%   |
| HGST                           | 2         | 2      | 1.12%   |
| A-DATA Technology              | 2         | 2      | 1.12%   |
| Unknown                        | 2         | 2      | 1.12%   |
| VISIPRO                        | 1         | 1      | 0.56%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.56%   |
| TO Exter                       | 1         | 1      | 0.56%   |
| Team                           | 1         | 1      | 0.56%   |
| StoreJet                       | 1         | 1      | 0.56%   |
| Solid State Storage Technology | 1         | 1      | 0.56%   |
| Solid State Storage            | 1         | 1      | 0.56%   |
| Smartbuy                       | 1         | 2      | 0.56%   |
| Plextor                        | 1         | 2      | 0.56%   |
| Phison Electronics             | 1         | 1      | 0.56%   |
| Micron Technology              | 1         | 1      | 0.56%   |
| MATSHITA                       | 1         | 1      | 0.56%   |
| KIOXIA                         | 1         | 1      | 0.56%   |
| JMicron Technology             | 1         | 1      | 0.56%   |
| Intenso                        | 1         | 1      | 0.56%   |
| Hewlett-Packard                | 1         | 3      | 0.56%   |
| Gigabyte Technology            | 1         | 1      | 0.56%   |
| Fujitsu                        | 1         | 1      | 0.56%   |
| Biwin Storage Technology       | 1         | 1      | 0.56%   |
| ADATA Technology               | 1         | 1      | 0.56%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 5         | 2.39%   |
| Samsung SSD 840 EVO 120GB                           | 5         | 2.39%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 1TB   | 4         | 1.91%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3         | 1.44%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 3         | 1.44%   |
| Kingston SA400S37480G 480GB SSD                     | 3         | 1.44%   |
| WDC WD10EZEX-08M2NA0 1TB                            | 2         | 0.96%   |
| Unknown MMC Card  128GB                             | 2         | 0.96%   |
| Toshiba XG6 NVMe SSD Controller 1024GB              | 2         | 0.96%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 0.96%   |
| Seagate ST3500418AS 500GB                           | 2         | 0.96%   |
| Seagate ST3000NM0053 3TB                            | 2         | 0.96%   |
| Seagate ST1000LM035-1RK172 970GB                    | 2         | 0.96%   |
| Seagate Expansion 4TB                               | 2         | 0.96%   |
| Sandisk WD Black SN850 1TB                          | 2         | 0.96%   |
| SanDisk NVMe SSD Drive 240GB                        | 2         | 0.96%   |
| Samsung SSD 870 QVO 2TB                             | 2         | 0.96%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 500GB | 2         | 0.96%   |
| PNY CS900 480GB SSD                                 | 2         | 0.96%   |
| Kingston Company A2000 NVMe SSD 500GB               | 2         | 0.96%   |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.96%   |
| Kingston SA400S37240G 240GB SSD                     | 2         | 0.96%   |
| Intel SSD 600P Series 256GB                         | 2         | 0.96%   |
| Crucial CT1000MX500SSD1 1TB                         | 2         | 0.96%   |
| Unknown                                             | 2         | 0.96%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 1         | 0.48%   |
| WDC WDS500G1B0B-00AS40 500GB SSD                    | 1         | 0.48%   |
| WDC WDS250G1B0A-00H9H0 250GB SSD                    | 1         | 0.48%   |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1         | 0.48%   |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.48%   |
| WDC WD5000AZRX-00L4HB0 500GB                        | 1         | 0.48%   |
| WDC WD40EFRX-68WT0N0 4TB                            | 1         | 0.48%   |
| WDC WD4003FRYZ-01F0DB0 4TB                          | 1         | 0.48%   |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 0.48%   |
| WDC WD30EZRX-00SPEB0 3TB                            | 1         | 0.48%   |
| WDC WD20SPZX-22UA7T0 2TB                            | 1         | 0.48%   |
| WDC WD20EZRZ-00Z5HB0 2TB                            | 1         | 0.48%   |
| WDC WD20EZRX-00DC0B0 2TB                            | 1         | 0.48%   |
| WDC WD20EFRX-68EUZN0 2TB                            | 1         | 0.48%   |
| WDC WD20EARX-00PASB0 2TB                            | 1         | 0.48%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 34        | 44     | 48.57%  |
| WDC                 | 16        | 27     | 22.86%  |
| Toshiba             | 8         | 14     | 11.43%  |
| Samsung Electronics | 4         | 4      | 5.71%   |
| Hitachi             | 3         | 4      | 4.29%   |
| Maxtor              | 2         | 2      | 2.86%   |
| HGST                | 2         | 2      | 2.86%   |
| Fujitsu             | 1         | 1      | 1.43%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 28     | 36.36%  |
| Kingston            | 9         | 12     | 13.64%  |
| Crucial             | 7         | 8      | 10.61%  |
| WDC                 | 4         | 4      | 6.06%   |
| PNY                 | 2         | 3      | 3.03%   |
| Patriot             | 2         | 2      | 3.03%   |
| Intel               | 2         | 3      | 3.03%   |
| A-DATA Technology   | 2         | 2      | 3.03%   |
| Unknown             | 2         | 2      | 3.03%   |
| VISIPRO             | 1         | 1      | 1.52%   |
| Toshiba             | 1         | 1      | 1.52%   |
| TO Exter            | 1         | 1      | 1.52%   |
| Team                | 1         | 1      | 1.52%   |
| StoreJet            | 1         | 1      | 1.52%   |
| Smartbuy            | 1         | 2      | 1.52%   |
| SK hynix            | 1         | 1      | 1.52%   |
| SanDisk             | 1         | 3      | 1.52%   |
| Plextor             | 1         | 2      | 1.52%   |
| Intenso             | 1         | 1      | 1.52%   |
| Hewlett-Packard     | 1         | 3      | 1.52%   |
| Gigabyte Technology | 1         | 1      | 1.52%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 60        | 98     | 35.5%   |
| SSD     | 56        | 82     | 33.14%  |
| NVMe    | 47        | 63     | 27.81%  |
| MMC     | 4         | 5      | 2.37%   |
| Unknown | 2         | 2      | 1.18%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 88        | 173    | 59.86%  |
| NVMe | 47        | 63     | 31.97%  |
| SAS  | 8         | 9      | 5.44%   |
| MMC  | 4         | 5      | 2.72%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 64        | 96     | 53.78%  |
| 0.51-1.0   | 28        | 43     | 23.53%  |
| 1.01-2.0   | 12        | 22     | 10.08%  |
| 2.01-3.0   | 6         | 7      | 5.04%   |
| 3.01-4.0   | 5         | 7      | 4.2%    |
| 10.01-20.0 | 2         | 2      | 1.68%   |
| 4.01-10.0  | 2         | 3      | 1.68%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 37        | 32.46%  |
| 1001-2000      | 27        | 23.68%  |
| 2001-3000      | 16        | 14.04%  |
| 501-1000       | 13        | 11.4%   |
| 251-500        | 12        | 10.53%  |
| 101-250        | 6         | 5.26%   |
| Unknown        | 2         | 1.75%   |
| 21-50          | 1         | 0.88%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 34        | 28.1%   |
| 51-100         | 23        | 19.01%  |
| 501-1000       | 16        | 13.22%  |
| 1001-2000      | 14        | 11.57%  |
| 251-500        | 13        | 10.74%  |
| 1-20           | 10        | 8.26%   |
| More than 3000 | 5         | 4.13%   |
| 2001-3000      | 3         | 2.48%   |
| Unknown        | 2         | 1.65%   |
| 21-50          | 1         | 0.83%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 840 EVO 120GB     | 4         | 5      | 23.53%  |
| WDC WD20EFRX-68EUZN0 2TB                  | 1         | 1      | 5.88%   |
| Toshiba MK5055GSX 500GB                   | 1         | 3      | 5.88%   |
| Seagate ST9500420AS 500GB                 | 1         | 1      | 5.88%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 5.88%   |
| Seagate ST2000DM001-1CH164 2TB            | 1         | 1      | 5.88%   |
| Samsung Electronics SSD 850 PRO 256GB     | 1         | 1      | 5.88%   |
| Maxtor 6L250S0 256GB                      | 1         | 1      | 5.88%   |
| Kingston SV300S37A120G 120GB SSD          | 1         | 1      | 5.88%   |
| Kingston SUV300S37A240G 240GB SSD         | 1         | 2      | 5.88%   |
| Intel SSD 600P Series 256GB               | 1         | 1      | 5.88%   |
| Hitachi HTS725025A9A364 250GB             | 1         | 2      | 5.88%   |
| Crucial CT250BX100SSD1 250GB              | 1         | 1      | 5.88%   |
| Biwin Storage Technology HP SSD EX900 1TB | 1         | 1      | 5.88%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Samsung Electronics      | 5         | 6      | 29.41%  |
| Seagate                  | 3         | 3      | 17.65%  |
| Kingston                 | 2         | 3      | 11.76%  |
| WDC                      | 1         | 1      | 5.88%   |
| Toshiba                  | 1         | 3      | 5.88%   |
| Maxtor                   | 1         | 1      | 5.88%   |
| Intel                    | 1         | 1      | 5.88%   |
| Hitachi                  | 1         | 2      | 5.88%   |
| Crucial                  | 1         | 1      | 5.88%   |
| Biwin Storage Technology | 1         | 1      | 5.88%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 42.86%  |
| WDC     | 1         | 1      | 14.29%  |
| Toshiba | 1         | 3      | 14.29%  |
| Maxtor  | 1         | 1      | 14.29%  |
| Hitachi | 1         | 2      | 14.29%  |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 8         | 10     | 50%     |
| HDD  | 6         | 10     | 37.5%   |
| NVMe | 2         | 2      | 12.5%   |

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

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Detected | 56        | 126    | 44.8%   |
| Works    | 53        | 102    | 42.4%   |
| Malfunc  | 16        | 22     | 12.8%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 71        | 42.01%  |
| AMD                            | 32        | 18.93%  |
| Samsung Electronics            | 16        | 9.47%   |
| SanDisk                        | 9         | 5.33%   |
| Kingston Technology Company    | 6         | 3.55%   |
| ASMedia Technology             | 6         | 3.55%   |
| SK hynix                       | 4         | 2.37%   |
| JMicron Technology             | 4         | 2.37%   |
| Marvell Technology Group       | 3         | 1.78%   |
| LSI Logic / Symbios Logic      | 3         | 1.78%   |
| Toshiba America Info Systems   | 2         | 1.18%   |
| Solid State Storage Technology | 2         | 1.18%   |
| Seagate Technology             | 2         | 1.18%   |
| Micron Technology              | 2         | 1.18%   |
| Union Memory (Shenzhen)        | 1         | 0.59%   |
| Silicon Image                  | 1         | 0.59%   |
| Promise Technology             | 1         | 0.59%   |
| Phison Electronics             | 1         | 0.59%   |
| KIOXIA                         | 1         | 0.59%   |
| Biwin Storage Technology       | 1         | 0.59%   |
| ADATA Technology               | 1         | 0.59%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 17        | 8.9%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 7         | 3.66%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 3.66%   |
| AMD 500 Series Chipset SATA Controller                                                  | 6         | 3.14%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 5         | 2.62%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 5         | 2.62%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 2.62%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 2.62%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 2.09%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 4         | 2.09%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 2.09%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 2.09%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 2.09%   |
| SK hynix Gold P31/PC711 NVMe Solid State Drive                                          | 3         | 1.57%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3         | 1.57%   |
| SanDisk WD Black SN750 / PC SN730 NVMe SSD                                              | 3         | 1.57%   |
| Kingston Company Company Non-Volatile memory controller                                 | 3         | 1.57%   |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 1.57%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 3         | 1.57%   |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.57%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 1.05%   |
| Solid State Storage Non-Volatile memory controller                                      | 2         | 1.05%   |
| Seagate FireCuda 530 SSD                                                                | 2         | 1.05%   |
| SanDisk Non-Volatile memory controller                                                  | 2         | 1.05%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 1.05%   |
| Samsung NVMe SSD Controller 980                                                         | 2         | 1.05%   |
| Micron NVMe Storage Controller                                                          | 2         | 1.05%   |
| Kingston Company A2000 NVMe SSD                                                         | 2         | 1.05%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 1.05%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 2         | 1.05%   |
| Intel SSD 600P Series                                                                   | 2         | 1.05%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 1.05%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 1.05%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 1.05%   |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                                 | 2         | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 1.05%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 2         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 6 port SATA AHCI Controller                          | 2         | 1.05%   |
| Intel 5 Series/3400 Series Chipset 4 port SATA AHCI Controller                          | 2         | 1.05%   |
| Union Memory (Shenzhen) Non-Volatile memory controller                                  | 1         | 0.52%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 90        | 54.88%  |
| NVMe | 46        | 28.05%  |
| IDE  | 16        | 9.76%   |
| RAID | 11        | 6.71%   |
| SCSI | 1         | 0.61%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 75        | 65.79%  |
| AMD    | 39        | 34.21%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                       | Computers | Percent |
|---------------------------------------------|-----------|---------|
| AMD Ryzen 7 5700G with Radeon Graphics      | 4         | 3.51%   |
| AMD Ryzen 7 5800U with Radeon Graphics      | 3         | 2.63%   |
| AMD Ryzen 5 2600 Six-Core Processor         | 3         | 2.63%   |
| Intel Pentium CPU P6200 @ 2.13GHz           | 2         | 1.75%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz          | 2         | 1.75%   |
| Intel Core i5-4200U CPU @ 1.60GHz           | 2         | 1.75%   |
| Intel Core i5-3230M CPU @ 2.60GHz           | 2         | 1.75%   |
| Intel Core i3-4005U CPU @ 1.70GHz           | 2         | 1.75%   |
| Intel Core i3-2370M CPU @ 2.40GHz           | 2         | 1.75%   |
| Intel Celeron N4020 CPU @ 1.10GHz           | 2         | 1.75%   |
| Intel 12th Gen Core i7-1260P                | 2         | 1.75%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz     | 2         | 1.75%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz     | 2         | 1.75%   |
| AMD Ryzen 7 5800H with Radeon Graphics      | 2         | 1.75%   |
| AMD Ryzen 5 3600 6-Core Processor           | 2         | 1.75%   |
| AMD Ryzen 5 1600 Six-Core Processor         | 2         | 1.75%   |
| AMD Phenom II X6 1100T Processor            | 2         | 1.75%   |
| AMD FX-8350 Eight-Core Processor            | 2         | 1.75%   |
| Intel Xeon W-2135 CPU @ 3.70GHz             | 1         | 0.88%   |
| Intel Xeon Silver 4110 CPU @ 2.10GHz        | 1         | 0.88%   |
| Intel Xeon CPU X5675 @ 3.07GHz              | 1         | 0.88%   |
| Intel Xeon CPU E5450 @ 3.00GHz              | 1         | 0.88%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz         | 1         | 0.88%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz         | 1         | 0.88%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz | 1         | 0.88%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz | 1         | 0.88%   |
| Intel Pentium 4 CPU 3.20GHz                 | 1         | 0.88%   |
| Intel Core i7-9750H CPU @ 2.60GHz           | 1         | 0.88%   |
| Intel Core i7-8665U CPU @ 1.90GHz           | 1         | 0.88%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz          | 1         | 0.88%   |
| Intel Core i7-6700K CPU @ 4.00GHz           | 1         | 0.88%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz          | 1         | 0.88%   |
| Intel Core i7-4720HQ CPU @ 2.60GHz          | 1         | 0.88%   |
| Intel Core i7-4700MQ CPU @ 2.40GHz          | 1         | 0.88%   |
| Intel Core i7-4700HQ CPU @ 2.40GHz          | 1         | 0.88%   |
| Intel Core i7-2670QM CPU @ 2.20GHz          | 1         | 0.88%   |
| Intel Core i7-2600 CPU @ 3.40GHz            | 1         | 0.88%   |
| Intel Core i7-10750H CPU @ 2.60GHz          | 1         | 0.88%   |
| Intel Core i7 CPU M 620 @ 2.67GHz           | 1         | 0.88%   |
| Intel Core i5-8300H CPU @ 2.30GHz           | 1         | 0.88%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 17        | 14.91%  |
| Intel Core i7           | 14        | 12.28%  |
| Other                   | 13        | 11.4%   |
| AMD Ryzen 7             | 12        | 10.53%  |
| AMD Ryzen 5             | 12        | 10.53%  |
| Intel Core i3           | 10        | 8.77%   |
| Intel Xeon              | 5         | 4.39%   |
| Intel Celeron           | 4         | 3.51%   |
| AMD Ryzen 9             | 4         | 3.51%   |
| Intel Core 2 Duo        | 3         | 2.63%   |
| Intel Pentium Dual-Core | 2         | 1.75%   |
| Intel Pentium           | 2         | 1.75%   |
| Intel Atom              | 2         | 1.75%   |
| AMD Phenom II X6        | 2         | 1.75%   |
| AMD Phenom II X4        | 2         | 1.75%   |
| AMD FX                  | 2         | 1.75%   |
| Intel Xeon Silver       | 1         | 0.88%   |
| Intel Pentium 4         | 1         | 0.88%   |
| Intel Core 2            | 1         | 0.88%   |
| AMD Ryzen Threadripper  | 1         | 0.88%   |
| AMD Ryzen 7 PRO         | 1         | 0.88%   |
| AMD Ryzen 3             | 1         | 0.88%   |
| AMD A4                  | 1         | 0.88%   |
| AMD A10                 | 1         | 0.88%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 34        | 29.82%  |
| 2      | 33        | 28.95%  |
| 8      | 16        | 14.04%  |
| 6      | 16        | 14.04%  |
| 12     | 6         | 5.26%   |
| 16     | 4         | 3.51%   |
| 1      | 4         | 3.51%   |
| 10     | 1         | 0.88%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 112       | 98.25%  |
| 2      | 2         | 1.75%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 88        | 77.19%  |
| 1      | 26        | 22.81%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 114       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 50        | 43.48%  |
| 0x0a50000c | 6         | 5.22%   |
| 0x806c1    | 5         | 4.35%   |
| 0x206a7    | 4         | 3.48%   |
| 0x906a3    | 3         | 2.61%   |
| 0x706a8    | 2         | 1.74%   |
| 0x506e3    | 2         | 1.74%   |
| 0x106ca    | 2         | 1.74%   |
| 0x1067a    | 2         | 1.74%   |
| 0x0a50000d | 2         | 1.74%   |
| 0x0800820d | 2         | 1.74%   |
| 0x06000852 | 2         | 1.74%   |
| 0x010000dc | 2         | 1.74%   |
| 0x010000c8 | 2         | 1.74%   |
| 0xf4a      | 1         | 0.87%   |
| 0xa0671    | 1         | 0.87%   |
| 0x906ea    | 1         | 0.87%   |
| 0x906e9    | 1         | 0.87%   |
| 0x906a4    | 1         | 0.87%   |
| 0x90672    | 1         | 0.87%   |
| 0x806ec    | 1         | 0.87%   |
| 0x806ea    | 1         | 0.87%   |
| 0x706e5    | 1         | 0.87%   |
| 0x6fb      | 1         | 0.87%   |
| 0x6f6      | 1         | 0.87%   |
| 0x506ca    | 1         | 0.87%   |
| 0x50654    | 1         | 0.87%   |
| 0x406e3    | 1         | 0.87%   |
| 0x40651    | 1         | 0.87%   |
| 0x306c3    | 1         | 0.87%   |
| 0x306a9    | 1         | 0.87%   |
| 0x20655    | 1         | 0.87%   |
| 0x106e5    | 1         | 0.87%   |
| 0x0a601201 | 1         | 0.87%   |
| 0x0a50000b | 1         | 0.87%   |
| 0x0a404102 | 1         | 0.87%   |
| 0x0a201016 | 1         | 0.87%   |
| 0x08701021 | 1         | 0.87%   |
| 0x08608103 | 1         | 0.87%   |
| 0x08108109 | 1         | 0.87%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Zen 3            | 12        | 10.53%  |
| Haswell          | 11        | 9.65%   |
| Zen+             | 8         | 7.02%   |
| KabyLake         | 8         | 7.02%   |
| Skylake          | 7         | 6.14%   |
| SandyBridge      | 7         | 6.14%   |
| Unknown          | 6         | 5.26%   |
| Zen 2            | 5         | 4.39%   |
| Westmere         | 5         | 4.39%   |
| TigerLake        | 5         | 4.39%   |
| Penryn           | 5         | 4.39%   |
| Alderlake Hybrid | 5         | 4.39%   |
| K10              | 4         | 3.51%   |
| Icelake          | 4         | 3.51%   |
| IvyBridge        | 3         | 2.63%   |
| Zen              | 2         | 1.75%   |
| Piledriver       | 2         | 1.75%   |
| Goldmont plus    | 2         | 1.75%   |
| Goldmont         | 2         | 1.75%   |
| Core             | 2         | 1.75%   |
| CometLake        | 2         | 1.75%   |
| Bonnell          | 2         | 1.75%   |
| Steamroller      | 1         | 0.88%   |
| NetBurst         | 1         | 0.88%   |
| Nehalem          | 1         | 0.88%   |
| Excavator        | 1         | 0.88%   |
| Broadwell        | 1         | 0.88%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 50        | 38.17%  |
| AMD                        | 42        | 32.06%  |
| Nvidia                     | 37        | 28.24%  |
| S3 Graphics                | 1         | 0.76%   |
| Matrox Electronics Systems | 1         | 0.76%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 11        | 8.21%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 2.99%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 2.99%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 3         | 2.24%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 3         | 2.24%   |
| Intel Alder Lake-P Integrated Graphics Controller                         | 3         | 2.24%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 3         | 2.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 3         | 2.24%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3         | 2.24%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 2         | 1.49%   |
| Nvidia GK107 [GeForce GT 640]                                             | 2         | 1.49%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 2         | 1.49%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.49%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 2         | 1.49%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 1.49%   |
| Intel Iris Plus Graphics G7                                               | 2         | 1.49%   |
| Intel HD Graphics 620                                                     | 2         | 1.49%   |
| Intel HD Graphics 500                                                     | 2         | 1.49%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.49%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.49%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.49%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 2         | 1.49%   |
| AMD RS880 [Radeon HD 4200]                                                | 2         | 1.49%   |
| AMD Raphael                                                               | 2         | 1.49%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                | 2         | 1.49%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 2         | 1.49%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                | 2         | 1.49%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 2         | 1.49%   |
| S3 Graphics 86c764/765 [Trio32/64/64V+]                                   | 1         | 0.75%   |
| Nvidia TU117M                                                             | 1         | 0.75%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                         | 1         | 0.75%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 0.75%   |
| Nvidia TU106 [GeForce RTX 2070]                                           | 1         | 0.75%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.75%   |
| Nvidia GT218M [ION]                                                       | 1         | 0.75%   |
| Nvidia GT216 [GeForce GT 220]                                             | 1         | 0.75%   |
| Nvidia GP108 [GeForce GT 1030]                                            | 1         | 0.75%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                | 1         | 0.75%   |
| Nvidia GM206 [GeForce GTX 960]                                            | 1         | 0.75%   |
| Nvidia GM204 [GeForce GTX 970]                                            | 1         | 0.75%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 38        | 33.33%  |
| 1 x AMD         | 32        | 28.07%  |
| 1 x Nvidia      | 22        | 19.3%   |
| Intel + Nvidia  | 10        | 8.77%   |
| AMD + Nvidia    | 5         | 4.39%   |
| 2 x AMD         | 3         | 2.63%   |
| Intel + AMD     | 2         | 1.75%   |
| 1 x S3 Graphics | 1         | 0.88%   |
| 1 x Matrox      | 1         | 0.88%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 93        | 80.87%  |
| Proprietary | 18        | 15.65%  |
| Unknown     | 4         | 3.48%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 70        | 60.87%  |
| 0.01-0.5   | 16        | 13.91%  |
| 1.01-2.0   | 10        | 8.7%    |
| 3.01-4.0   | 9         | 7.83%   |
| 0.51-1.0   | 4         | 3.48%   |
| 7.01-8.0   | 3         | 2.61%   |
| 8.01-16.0  | 3         | 2.61%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 17        | 13.6%   |
| Samsung Electronics     | 14        | 11.2%   |
| Dell                    | 12        | 9.6%    |
| BOE                     | 12        | 9.6%    |
| Fujitsu Siemens         | 9         | 7.2%    |
| LG Display              | 7         | 5.6%    |
| Goldstar                | 7         | 5.6%    |
| Lenovo                  | 5         | 4%      |
| Hewlett-Packard         | 5         | 4%      |
| InfoVision              | 4         | 3.2%    |
| Chimei Innolux          | 4         | 3.2%    |
| Iiyama                  | 3         | 2.4%    |
| AOC                     | 3         | 2.4%    |
| Ancor Communications    | 3         | 2.4%    |
| Acer                    | 3         | 2.4%    |
| ViewSonic               | 2         | 1.6%    |
| Sharp                   | 2         | 1.6%    |
| HannStar                | 2         | 1.6%    |
| Unknown                 | 1         | 0.8%    |
| Philips                 | 1         | 0.8%    |
| NEC Computers           | 1         | 0.8%    |
| LG Electronics          | 1         | 0.8%    |
| Insignia                | 1         | 0.8%    |
| Hitachi                 | 1         | 0.8%    |
| Gigabyte Technology     | 1         | 0.8%    |
| Eizo                    | 1         | 0.8%    |
| Chi Mei Optoelectronics | 1         | 0.8%    |
| BenQ                    | 1         | 0.8%    |
| ASUSTek Computer        | 1         | 0.8%    |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Fujitsu Siemens P19-2 FUS0552 1280x1024 376x301mm 19.0-inch           | 6         | 4.72%   |
| BOE LCD Monitor BOE08CD 1366x768 344x194mm 15.5-inch                  | 3         | 2.36%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch          | 2         | 1.57%   |
| Hewlett-Packard 27f HPN354A 1920x1080 598x336mm 27.0-inch             | 2         | 1.57%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 1.57%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 2         | 1.57%   |
| ViewSonic VA2265 SERIES VSCB330 1920x1080 476x268mm 21.5-inch         | 1         | 0.79%   |
| ViewSonic EP3220T VSC33F3 1920x1080 700x390mm 31.5-inch               | 1         | 0.79%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1         | 0.79%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 0.79%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.79%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 607x345mm 27.5-inch     | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 477x268mm 21.5-inch  | 1         | 0.79%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 0.79%   |
| Samsung Electronics SMS24A850 SAM0825 1920x1200 518x324mm 24.1-inch   | 1         | 0.79%   |
| Samsung Electronics S27E450 SAM0C83 1920x1080 598x336mm 27.0-inch     | 1         | 0.79%   |
| Samsung Electronics S23B350 SAM08F4 1920x1080 510x287mm 23.0-inch     | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC894F 1920x1080 344x194mm 15.5-inch | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch  | 1         | 0.79%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 0.79%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.79%   |
| Samsung Electronics C32JG5x SAM0F55 2560x1440 697x392mm 31.5-inch     | 1         | 0.79%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.79%   |
| Philips 190X PHL084C 1280x1024 376x301mm 19.0-inch                    | 1         | 0.79%   |
| NEC Computers LCD1545V NEC65D7 1024x768 304x228mm 15.0-inch           | 1         | 0.79%   |
| LG Electronics LCD Monitor E2260 1920x1080                            | 1         | 0.79%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0584 1920x1080 294x165mm 13.3-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0521 1920x1080 309x174mm 14.0-inch          | 1         | 0.79%   |
| LG Display LCD Monitor LGD0430 1366x768 345x194mm 15.6-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD02E9 1366x768 309x174mm 14.0-inch           | 1         | 0.79%   |
| LG Display LCD Monitor LGD0250 1366x768 345x194mm 15.6-inch           | 1         | 0.79%   |
| Lenovo LEN P32p-20 LEN62A2 3840x2160 697x392mm 31.5-inch              | 1         | 0.79%   |
| Lenovo LCD Monitor LEN40B2 1920x1080 344x193mm 15.5-inch              | 1         | 0.79%   |
| Lenovo LCD Monitor LEN40B1 1600x900 345x194mm 15.6-inch               | 1         | 0.79%   |
| Lenovo LCD Monitor LEN4035 1280x800 303x189mm 14.1-inch               | 1         | 0.79%   |
| Lenovo LCD Monitor LEN1144 1920x1080 518x324mm 24.1-inch              | 1         | 0.79%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 55        | 47.01%  |
| 1366x768 (WXGA)    | 21        | 17.95%  |
| 2560x1440 (QHD)    | 10        | 8.55%   |
| 1280x1024 (SXGA)   | 10        | 8.55%   |
| 1920x1200 (WUXGA)  | 3         | 2.56%   |
| 1680x1050 (WSXGA+) | 3         | 2.56%   |
| 1600x900 (HD+)     | 3         | 2.56%   |
| 1440x900 (WXGA+)   | 3         | 2.56%   |
| 3840x2160 (4K)     | 2         | 1.71%   |
| 3440x1440          | 1         | 0.85%   |
| 2560x1600          | 1         | 0.85%   |
| 1600x1200          | 1         | 0.85%   |
| 1280x960           | 1         | 0.85%   |
| 1280x800 (WXGA)    | 1         | 0.85%   |
| 1024x768 (XGA)     | 1         | 0.85%   |
| 1024x600           | 1         | 0.85%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 31        | 25%     |
| 27      | 11        | 8.87%   |
| 13      | 11        | 8.87%   |
| 24      | 10        | 8.06%   |
| 19      | 10        | 8.06%   |
| 23      | 9         | 7.26%   |
| 17      | 7         | 5.65%   |
| 14      | 7         | 5.65%   |
| 31      | 5         | 4.03%   |
| 21      | 5         | 4.03%   |
| 16      | 3         | 2.42%   |
| 22      | 2         | 1.61%   |
| 20      | 2         | 1.61%   |
| 18      | 2         | 1.61%   |
| 54      | 1         | 0.81%   |
| 38      | 1         | 0.81%   |
| 34      | 1         | 0.81%   |
| 32      | 1         | 0.81%   |
| 30      | 1         | 0.81%   |
| 26      | 1         | 0.81%   |
| 12      | 1         | 0.81%   |
| 10      | 1         | 0.81%   |
| Unknown | 1         | 0.81%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 46        | 37.7%   |
| 501-600     | 27        | 22.13%  |
| 351-400     | 16        | 13.11%  |
| 401-500     | 14        | 11.48%  |
| 601-700     | 7         | 5.74%   |
| 201-300     | 7         | 5.74%   |
| 701-800     | 2         | 1.64%   |
| 801-900     | 1         | 0.82%   |
| 1001-1500   | 1         | 0.82%   |
| Unknown     | 1         | 0.82%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 84        | 75%     |
| 16/10   | 12        | 10.71%  |
| 5/4     | 9         | 8.04%   |
| 4/3     | 3         | 2.68%   |
| 6/5     | 1         | 0.89%   |
| 3/2     | 1         | 0.89%   |
| 21/9    | 1         | 0.89%   |
| Unknown | 1         | 0.89%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 32        | 26.02%  |
| 201-250        | 19        | 15.45%  |
| 81-90          | 13        | 10.57%  |
| 151-200        | 13        | 10.57%  |
| 301-350        | 12        | 9.76%   |
| 351-500        | 8         | 6.5%    |
| 121-130        | 6         | 4.88%   |
| 71-80          | 5         | 4.07%   |
| 251-300        | 5         | 4.07%   |
| 141-150        | 4         | 3.25%   |
| More than 1000 | 1         | 0.81%   |
| 61-70          | 1         | 0.81%   |
| 41-50          | 1         | 0.81%   |
| 111-120        | 1         | 0.81%   |
| 501-1000       | 1         | 0.81%   |
| Unknown        | 1         | 0.81%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 50        | 42.02%  |
| 101-120 | 32        | 26.89%  |
| 121-160 | 29        | 24.37%  |
| 161-240 | 6         | 5.04%   |
| 1-50    | 1         | 0.84%   |
| Unknown | 1         | 0.84%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 92        | 80%     |
| 2     | 15        | 13.04%  |
| 0     | 5         | 4.35%   |
| 3     | 3         | 2.61%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 69        | 39.43%  |
| Intel                    | 61        | 34.86%  |
| Qualcomm Atheros         | 12        | 6.86%   |
| Broadcom                 | 6         | 3.43%   |
| MediaTek                 | 4         | 2.29%   |
| Ralink                   | 3         | 1.71%   |
| TP-Link                  | 2         | 1.14%   |
| NetGear                  | 2         | 1.14%   |
| Marvell Technology Group | 2         | 1.14%   |
| Lenovo                   | 2         | 1.14%   |
| Broadcom Limited         | 2         | 1.14%   |
| Sitecom Europe           | 1         | 0.57%   |
| Sierra Wireless          | 1         | 0.57%   |
| Samsung Electronics      | 1         | 0.57%   |
| Ralink Technology        | 1         | 0.57%   |
| Qualcomm                 | 1         | 0.57%   |
| Microchip Technology     | 1         | 0.57%   |
| JMicron Technology       | 1         | 0.57%   |
| Dell                     | 1         | 0.57%   |
| Atmel                    | 1         | 0.57%   |
| Aquantia                 | 1         | 0.57%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 22.66%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.96%   |
| Intel Wi-Fi 6 AX200                                               | 6         | 2.96%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 2.46%   |
| Intel Ethernet Controller I225-V                                  | 5         | 2.46%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.97%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 1.97%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 1.97%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.48%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.48%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.48%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 1.48%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.48%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.99%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.99%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.99%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.99%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.99%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.99%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 0.99%   |
| Intel Wireless-AC 9260                                            | 2         | 0.99%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.99%   |
| Intel Wireless 8260                                               | 2         | 0.99%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 0.99%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.99%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.99%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 0.99%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.99%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.99%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.99%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 0.99%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 0.99%   |
| Broadcom BCM43142 802.11b/g/n                                     | 2         | 0.99%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.49%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                               | 1         | 0.49%   |
| Sitecom Europe AX88179 Gigabit Ethernet [Sitecom]                 | 1         | 0.49%   |
| Sierra Wireless EM7455                                            | 1         | 0.49%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.49%   |
| Realtek RTL88x2bu [AC1200 Techkey]                                | 1         | 0.49%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter          | 1         | 0.49%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 44        | 53.01%  |
| Realtek Semiconductor | 14        | 16.87%  |
| Qualcomm Atheros      | 9         | 10.84%  |
| MediaTek              | 4         | 4.82%   |
| Ralink                | 3         | 3.61%   |
| NetGear               | 2         | 2.41%   |
| Broadcom              | 2         | 2.41%   |
| TP-Link               | 1         | 1.2%    |
| Sierra Wireless       | 1         | 1.2%    |
| Ralink Technology     | 1         | 1.2%    |
| Qualcomm              | 1         | 1.2%    |
| Broadcom Limited      | 1         | 1.2%    |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                          | Computers | Percent |
|----------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                            | 6         | 7.06%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                         | 4         | 4.71%   |
| Intel Alder Lake-P PCH CNVi WiFi                               | 4         | 4.71%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter     | 3         | 3.53%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter  | 3         | 3.53%   |
| Intel Wi-Fi 6 AX201                                            | 3         | 3.53%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                | 3         | 3.53%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter       | 2         | 2.35%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.35%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter       | 2         | 2.35%   |
| Realtek 802.11n WLAN Adapter                                   | 2         | 2.35%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter     | 2         | 2.35%   |
| Intel Wireless-AC 9260                                         | 2         | 2.35%   |
| Intel Wireless 8265 / 8275                                     | 2         | 2.35%   |
| Intel Wireless 8260                                            | 2         | 2.35%   |
| Intel Comet Lake PCH CNVi WiFi                                 | 2         | 2.35%   |
| Intel Centrino Ultimate-N 6300                                 | 2         | 2.35%   |
| Intel Cannon Lake PCH CNVi WiFi                                | 2         | 2.35%   |
| Broadcom BCM43142 802.11b/g/n                                  | 2         | 2.35%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                            | 1         | 1.18%   |
| Sierra Wireless EM7455                                         | 1         | 1.18%   |
| Realtek RTL88x2bu [AC1200 Techkey]                             | 1         | 1.18%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter       | 1         | 1.18%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                     | 1         | 1.18%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                | 1         | 1.18%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter                | 1         | 1.18%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter            | 1         | 1.18%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                     | 1         | 1.18%   |
| Ralink MT7601U Wireless Adapter                                | 1         | 1.18%   |
| Ralink RT5392 PCIe Wireless Network Adapter                    | 1         | 1.18%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.18%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                      | 1         | 1.18%   |
| Qualcomm QCNFA765 Wireless Network Adapter                     | 1         | 1.18%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter               | 1         | 1.18%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter               | 1         | 1.18%   |
| Qualcomm Atheros AR928X Wireless Network Adapter (PCI-Express) | 1         | 1.18%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express) | 1         | 1.18%   |
| NetGear WNDA3100v3 802.11abgn 2x2:2 [MediaTek MT7632U]         | 1         | 1.18%   |
| NetGear A6150                                                  | 1         | 1.18%   |
| MediaTek MT7922 802.11ax PCI Express Wireless Network Adapter  | 1         | 1.18%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 61        | 53.04%  |
| Intel                    | 34        | 29.57%  |
| Qualcomm Atheros         | 5         | 4.35%   |
| Broadcom                 | 4         | 3.48%   |
| Marvell Technology Group | 2         | 1.74%   |
| Lenovo                   | 2         | 1.74%   |
| TP-Link                  | 1         | 0.87%   |
| Sitecom Europe           | 1         | 0.87%   |
| Samsung Electronics      | 1         | 0.87%   |
| JMicron Technology       | 1         | 0.87%   |
| Dell                     | 1         | 0.87%   |
| Broadcom Limited         | 1         | 0.87%   |
| Aquantia                 | 1         | 0.87%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 46        | 39.66%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 5.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 4.31%   |
| Intel Ethernet Controller I225-V                                  | 5         | 4.31%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 4         | 3.45%   |
| Intel I211 Gigabit Network Connection                             | 3         | 2.59%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.72%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 2         | 1.72%   |
| Intel Ethernet Connection I217-LM                                 | 2         | 1.72%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.72%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.72%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 1.72%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 1.72%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 1.72%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.86%   |
| Sitecom Europe AX88179 Gigabit Ethernet [Sitecom]                 | 1         | 0.86%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.86%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 1         | 0.86%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.86%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 1         | 0.86%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.86%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.86%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.86%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.86%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 1         | 0.86%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.86%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.86%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.86%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.86%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.86%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.86%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.86%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.86%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.86%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.86%   |
| Intel Ethernet Connection (11) I219-V                             | 1         | 0.86%   |
| Intel 82578DM Gigabit Network Connection                          | 1         | 0.86%   |
| Intel 82577LM Gigabit Network Connection                          | 1         | 0.86%   |
| Intel 82566DC Gigabit Network Connection                          | 1         | 0.86%   |
| Intel 82541PI Gigabit Ethernet Controller                         | 1         | 0.86%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 104       | 56.22%  |
| WiFi     | 80        | 43.24%  |
| Modem    | 1         | 0.54%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 69        | 58.97%  |
| WiFi     | 48        | 41.03%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 63        | 55.26%  |
| 1     | 42        | 36.84%  |
| 3     | 4         | 3.51%   |
| 0     | 4         | 3.51%   |
| 4     | 1         | 0.88%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 79        | 66.95%  |
| Yes  | 39        | 33.05%  |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 37        | 51.39%  |
| Realtek Semiconductor           | 9         | 12.5%   |
| Cambridge Silicon Radio         | 6         | 8.33%   |
| IMC Networks                    | 5         | 6.94%   |
| Broadcom                        | 4         | 5.56%   |
| Qualcomm Atheros Communications | 3         | 4.17%   |
| Hewlett-Packard                 | 2         | 2.78%   |
| Ralink                          | 1         | 1.39%   |
| MediaTek                        | 1         | 1.39%   |
| Lite-On Technology              | 1         | 1.39%   |
| Edimax Technology               | 1         | 1.39%   |
| Belkin Components               | 1         | 1.39%   |
| ASUSTek Computer                | 1         | 1.39%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Realtek Bluetooth Radio                                     | 7         | 9.72%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 9.72%   |
| Intel Bluetooth wireless interface                          | 6         | 8.33%   |
| Intel AX201 Bluetooth                                       | 6         | 8.33%   |
| Intel AX200 Bluetooth                                       | 6         | 8.33%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 6         | 8.33%   |
| Intel AX210 Bluetooth                                       | 4         | 5.56%   |
| Intel Bluetooth Device                                      | 3         | 4.17%   |
| Qualcomm Atheros  Bluetooth Device                          | 2         | 2.78%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.78%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.78%   |
| IMC Networks Wireless_Device                                | 2         | 2.78%   |
| IMC Networks Bluetooth Device                               | 2         | 2.78%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.78%   |
| Realtek RTL8821A Bluetooth                                  | 1         | 1.39%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.39%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.39%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.39%   |
| MediaTek Wireless_Device                                    | 1         | 1.39%   |
| Lite-On Wireless_Device                                     | 1         | 1.39%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.39%   |
| IMC Networks Atheros AR3012 Bluetooth                       | 1         | 1.39%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 1.39%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.39%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1         | 1.39%   |
| Broadcom Bluetooth Controller                               | 1         | 1.39%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.39%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter       | 1         | 1.39%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 1.39%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 73        | 43.45%  |
| AMD                         | 45        | 26.79%  |
| Nvidia                      | 28        | 16.67%  |
| C-Media Electronics         | 6         | 3.57%   |
| Creative Labs               | 3         | 1.79%   |
| Lenovo                      | 2         | 1.19%   |
| GN Netcom                   | 2         | 1.19%   |
| Texas Instruments           | 1         | 0.6%    |
| Realtek Semiconductor       | 1         | 0.6%    |
| Plantronics                 | 1         | 0.6%    |
| Microsoft                   | 1         | 0.6%    |
| Logitech                    | 1         | 0.6%    |
| JMTek                       | 1         | 0.6%    |
| FiiO Electronics Technology | 1         | 0.6%    |
| Ensoniq                     | 1         | 0.6%    |
| ASUSTek Computer            | 1         | 0.6%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 18        | 8.49%   |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 6.13%   |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7         | 3.3%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 6         | 2.83%   |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 2.83%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 5         | 2.36%   |
| Intel Sunrise Point-LP HD Audio                                            | 5         | 2.36%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 5         | 2.36%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 5         | 2.36%   |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 2.36%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 4         | 1.89%   |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.89%   |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.89%   |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.89%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 4         | 1.89%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 4         | 1.89%   |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 1.89%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 3         | 1.42%   |
| Nvidia GP107GL High Definition Audio Controller                            | 3         | 1.42%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.42%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.42%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 3         | 1.42%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.42%   |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 1.42%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 3         | 1.42%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 3         | 1.42%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 1.42%   |
| Nvidia High Definition Audio Controller                                    | 2         | 0.94%   |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.94%   |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 2         | 0.94%   |
| Nvidia GK107 HDMI Audio Controller                                         | 2         | 0.94%   |
| Nvidia GF119 HDMI Audio Controller                                         | 2         | 0.94%   |
| Nvidia GF108 High Definition Audio Controller                              | 2         | 0.94%   |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.94%   |
| Nvidia Audio device                                                        | 2         | 0.94%   |
| Intel Tiger Lake-H HD Audio Controller                                     | 2         | 0.94%   |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.94%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio               | 2         | 0.94%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster          | 2         | 0.94%   |
| Intel Cannon Point-LP High Definition Audio Controller                     | 2         | 0.94%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 14        | 20%     |
| Samsung Electronics | 10        | 14.29%  |
| SK hynix            | 8         | 11.43%  |
| Unknown             | 7         | 10%     |
| Micron Technology   | 7         | 10%     |
| Corsair             | 6         | 8.57%   |
| Unknown (ABCD)      | 3         | 4.29%   |
| G.Skill             | 3         | 4.29%   |
| Unknown             | 3         | 4.29%   |
| Transcend           | 1         | 1.43%   |
| Toshiba             | 1         | 1.43%   |
| TakeMS              | 1         | 1.43%   |
| Smart               | 1         | 1.43%   |
| Qimonda             | 1         | 1.43%   |
| CSX                 | 1         | 1.43%   |
| Crucial             | 1         | 1.43%   |
| Avant               | 1         | 1.43%   |
| A-DATA Technology   | 1         | 1.43%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 3GB SODIMM LPDDR4 2400MT/s | 3         | 4%      |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s            | 3         | 4%      |
| Unknown                                                          | 3         | 4%      |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 2.67%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 2         | 2.67%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 1.33%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 1.33%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 1.33%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.33%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 1         | 1.33%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.33%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s            | 1         | 1.33%   |
| Toshiba RAM 8HTF12864HDY-800G1 4GB SODIMM 1066MT/s               | 1         | 1.33%   |
| Toshiba RAM 64T128020EDL2.5C2 1GB SODIMM 1066MT/s                | 1         | 1.33%   |
| TakeMS RAM Module 2048MB DIMM DDR2 800MT/s                       | 1         | 1.33%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 1         | 1.33%   |
| Smart RAM SH564288FH8NWPHSFR 1024MB SODIMM DDR3 1067MT/s         | 1         | 1.33%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 1.33%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.33%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 1.33%   |
| SK hynix RAM HMT351S6CFR8C-H9 4096MB SODIMM DDR3 1333MT/s        | 1         | 1.33%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| SK hynix RAM HMA82GU6AFR8N-UH 16GB DIMM DDR4 2400MT/s            | 1         | 1.33%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8192MB DIMM DDR4 2666MT/s          | 1         | 1.33%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.33%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.33%   |
| Samsung RAM Module 32GB SODIMM DDR5 4800MT/s                     | 1         | 1.33%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.33%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.33%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.33%   |
| Samsung RAM M471A4G43AB1-CWE 32GB SODIMM DDR4 3200MT/s           | 1         | 1.33%   |
| Samsung RAM M471A2K43CB1-CTD 16384MB SODIMM DDR4 8400MT/s        | 1         | 1.33%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 1         | 1.33%   |
| Samsung RAM M471A2G43BB2-CWE 16GB SODIMM DDR4 3200MT/s           | 1         | 1.33%   |
| Samsung RAM M471A1K43EB1-CWE 8GB SODIMM DDR4 3200MT/s            | 1         | 1.33%   |
| Qimonda RAM 64T256020EDL2.5C2 2GB SODIMM DDR2 2048MT/s           | 1         | 1.33%   |
| Micron RAM Module 16384MB SODIMM DDR4 3200MT/s                   | 1         | 1.33%   |
| Micron RAM 8KTF51264HZ-1G6E1 4GB SODIMM DDR3 1600MT/s            | 1         | 1.33%   |
| Micron RAM 4ATS1G64HZ-2G6E1 8GB SODIMM DDR4 2667MT/s             | 1         | 1.33%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 33        | 52.38%  |
| DDR3    | 12        | 19.05%  |
| DDR2    | 5         | 7.94%   |
| LPDDR4  | 4         | 6.35%   |
| Unknown | 4         | 6.35%   |
| DDR5    | 2         | 3.17%   |
| SDRAM   | 1         | 1.59%   |
| LPDDR3  | 1         | 1.59%   |
| DDR     | 1         | 1.59%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 33        | 51.56%  |
| DIMM         | 28        | 43.75%  |
| Row Of Chips | 3         | 4.69%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 18        | 26.87%  |
| 16384 | 16        | 23.88%  |
| 4096  | 16        | 23.88%  |
| 32768 | 7         | 10.45%  |
| 2048  | 6         | 8.96%   |
| 1024  | 4         | 5.97%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 16        | 23.88%  |
| 1600  | 8         | 11.94%  |
| 2667  | 6         | 8.96%   |
| 2400  | 6         | 8.96%   |
| 2133  | 6         | 8.96%   |
| 1333  | 6         | 8.96%   |
| 3933  | 3         | 4.48%   |
| 4800  | 2         | 2.99%   |
| 3600  | 2         | 2.99%   |
| 1334  | 2         | 2.99%   |
| 800   | 2         | 2.99%   |
| 667   | 2         | 2.99%   |
| 8400  | 1         | 1.49%   |
| 4267  | 1         | 1.49%   |
| 2666  | 1         | 1.49%   |
| 2048  | 1         | 1.49%   |
| 1066  | 1         | 1.49%   |
| 533   | 1         | 1.49%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Brother Industries  | 2         | 50%     |
| Samsung Electronics | 1         | 25%     |
| Hewlett-Packard     | 1         | 25%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Samsung ML-191x/ML-252x Laser Printer | 1         | 25%     |
| HP Color LaserJet CP1215              | 1         | 25%     |
| Brother Printer                       | 1         | 25%     |
| Brother HL-4150CDN series             | 1         | 25%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor         | Computers | Percent |
|----------------|-----------|---------|
| Seiko Epson    | 1         | 50%     |
| Mustek Systems | 1         | 50%     |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 50%     |
| Mustek Systems ScanExpress A3 USB                             | 1         | 50%     |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 17        | 23.29%  |
| Microdia                               | 7         | 9.59%   |
| Sunplus Innovation Technology          | 6         | 8.22%   |
| Logitech                               | 6         | 8.22%   |
| Luxvisions Innotech Limited            | 4         | 5.48%   |
| Alcor Micro                            | 4         | 5.48%   |
| Syntek                                 | 3         | 4.11%   |
| Quanta                                 | 3         | 4.11%   |
| Lite-On Technology                     | 3         | 4.11%   |
| Acer                                   | 3         | 4.11%   |
| Realtek Semiconductor                  | 2         | 2.74%   |
| IMC Networks                           | 2         | 2.74%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.74%   |
| Bison Electronics                      | 2         | 2.74%   |
| 2M UVC CAMERA                          | 2         | 2.74%   |
| vivo                                   | 1         | 1.37%   |
| Suyin                                  | 1         | 1.37%   |
| Microsoft                              | 1         | 1.37%   |
| Lenovo                                 | 1         | 1.37%   |
| kingcome                               | 1         | 1.37%   |
| Huawei Technologies                    | 1         | 1.37%   |
| ARC International                      | 1         | 1.37%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 5.48%   |
| Microdia Integrated_Webcam_HD                        | 3         | 4.11%   |
| Alcor Micro SHUNCCM2MP                               | 3         | 4.11%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 2.74%   |
| Quanta HP True Vision HD Camera                      | 2         | 2.74%   |
| Logitech HD Webcam C615                              | 2         | 2.74%   |
| 2M UVC CAMERA NexiGo N60 FHD Webcam                  | 2         | 2.74%   |
| vivo V2023                                           | 1         | 1.37%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                 | 1         | 1.37%   |
| Syntek Integrated Camera                             | 1         | 1.37%   |
| Syntek EasyCamera                                    | 1         | 1.37%   |
| Suyin USB 2.0 Camera                                 | 1         | 1.37%   |
| Sunplus Laptop Integrated Webcam HD                  | 1         | 1.37%   |
| Sunplus HD WebCam                                    | 1         | 1.37%   |
| Sunplus HD 720P webcam                               | 1         | 1.37%   |
| Sunplus Dell E5570 integrated webcam                 | 1         | 1.37%   |
| Realtek USB2.0 camera                                | 1         | 1.37%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.37%   |
| Quanta HP HD Camera                                  | 1         | 1.37%   |
| Microsoft LifeCam VX-700                             | 1         | 1.37%   |
| Microdia Webcam Vitade AF                            | 1         | 1.37%   |
| Microdia USB 2.0 Camera                              | 1         | 1.37%   |
| Microdia Integrated Webcam                           | 1         | 1.37%   |
| Microdia Camera                                      | 1         | 1.37%   |
| Luxvisions Innotech Limited Integrated Camera        | 1         | 1.37%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.37%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 1.37%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 1.37%   |
| Logitech Webcam C270                                 | 1         | 1.37%   |
| Logitech Webcam C170                                 | 1         | 1.37%   |
| Logitech HD Pro Webcam C920                          | 1         | 1.37%   |
| Logitech BRIO Ultra HD Webcam                        | 1         | 1.37%   |
| Lite-On TOSHIBA Web Camera - HD                      | 1         | 1.37%   |
| Lite-On Integrated Camera                            | 1         | 1.37%   |
| Lite-On HP HD Webcam                                 | 1         | 1.37%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.37%   |
| kingcome 480p VGA Camera                             | 1         | 1.37%   |
| IMC Networks USB2.0 UVC HD Webcam                    | 1         | 1.37%   |
| IMC Networks Integrated Camera                       | 1         | 1.37%   |
| Huawei HiCamera                                      | 1         | 1.37%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Synaptics        | 7         | 41.18%  |
| Validity Sensors | 6         | 35.29%  |
| Upek             | 3         | 17.65%  |
| AuthenTec        | 1         | 5.88%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 17.65%  |
| Synaptics UWP WBDI                                       | 3         | 17.65%  |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 11.76%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 11.76%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 11.76%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 5.88%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 5.88%   |
| Validity Sensors VFS491                                  | 1         | 5.88%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 5.88%   |
| AuthenTec AES1600                                        | 1         | 5.88%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 4         | 50%     |
| Broadcom              | 2         | 25%     |
| Lenovo                | 1         | 12.5%   |
| Gemalto (was Gemplus) | 1         | 12.5%   |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 4         | 50%     |
| Lenovo Integrated Smart Card Reader                                          | 1         | 12.5%   |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 12.5%   |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 12.5%   |
| Broadcom 58200                                                               | 1         | 12.5%   |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 70        | 60.87%  |
| 1     | 30        | 26.09%  |
| 2     | 11        | 9.57%   |
| 3     | 3         | 2.61%   |
| 4     | 1         | 0.87%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 17        | 28.33%  |
| Graphics card            | 10        | 16.67%  |
| Net/wireless             | 8         | 13.33%  |
| Chipcard                 | 8         | 13.33%  |
| Multimedia controller    | 4         | 6.67%   |
| Camera                   | 3         | 5%      |
| Unassigned class         | 2         | 3.33%   |
| Network                  | 2         | 3.33%   |
| Communication controller | 2         | 3.33%   |
| Card reader              | 2         | 3.33%   |
| Sound                    | 1         | 1.67%   |
| Bluetooth                | 1         | 1.67%   |

