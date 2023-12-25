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

Total: 213

| Vendor        | Model                       | Form-Factor | Probe                                                      | Date         |
|---------------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Intel         | MIR1 RVP7                   | Desktop     | [eade46459a](https://linux-hardware.org/?probe=eade46459a) | Dec 13, 2023 |
| Samsung       | 550XDA                      | Notebook    | [5778304f73](https://linux-hardware.org/?probe=5778304f73) | Nov 30, 2023 |
| ASUSTek       | PRIME B550M-K               | Desktop     | [186ea5595b](https://linux-hardware.org/?probe=186ea5595b) | Nov 25, 2023 |
| Medion        | MS-7848                     | Desktop     | [ab89c9cc22](https://linux-hardware.org/?probe=ab89c9cc22) | Oct 26, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [4e83b42f8d](https://linux-hardware.org/?probe=4e83b42f8d) | Oct 11, 2023 |
| Gigabyte      | F2A78M-HD2                  | Desktop     | [e9b2c833e0](https://linux-hardware.org/?probe=e9b2c833e0) | Oct 08, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [5d41b45d45](https://linux-hardware.org/?probe=5d41b45d45) | Sep 30, 2023 |
| Fujitsu       | D3401-A1 S26361-D3401-A1    | Desktop     | [65643e78ef](https://linux-hardware.org/?probe=65643e78ef) | Sep 30, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [1521626729](https://linux-hardware.org/?probe=1521626729) | Sep 02, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [625ff7df38](https://linux-hardware.org/?probe=625ff7df38) | Aug 22, 2023 |
| Dell          | 0427JK A00                  | Desktop     | [857e3132c1](https://linux-hardware.org/?probe=857e3132c1) | Aug 19, 2023 |
| ASRock        | Z270 Pro4                   | Desktop     | [de0587ccf3](https://linux-hardware.org/?probe=de0587ccf3) | Aug 19, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [e21dbce888](https://linux-hardware.org/?probe=e21dbce888) | Aug 17, 2023 |
| HP            | ENVY x360 Convertible 13... | Convertible | [4e79ef6905](https://linux-hardware.org/?probe=4e79ef6905) | Aug 15, 2023 |
| Dell          | 0DT021 A00                  | Server      | [f472313f3a](https://linux-hardware.org/?probe=f472313f3a) | Aug 08, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [35e4fef6c6](https://linux-hardware.org/?probe=35e4fef6c6) | Aug 07, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [297a14921c](https://linux-hardware.org/?probe=297a14921c) | Aug 04, 2023 |
| Dell          | 0DT021 A00                  | Server      | [354c40df4e](https://linux-hardware.org/?probe=354c40df4e) | Aug 04, 2023 |
| Dell          | 0W13NR A06                  | Server      | [b1820a9229](https://linux-hardware.org/?probe=b1820a9229) | Aug 04, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [46e96687a1](https://linux-hardware.org/?probe=46e96687a1) | Aug 04, 2023 |
| Dell          | 09M8Y8 A01                  | Desktop     | [e5649696d0](https://linux-hardware.org/?probe=e5649696d0) | Aug 03, 2023 |
| Dell          | 0272WF A00                  | Server      | [2867ef6d1f](https://linux-hardware.org/?probe=2867ef6d1f) | Jul 29, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [270ce3344c](https://linux-hardware.org/?probe=270ce3344c) | Jul 28, 2023 |
| ASUSTek       | ZenBook UX482EA_UX482EA     | Notebook    | [52d550e878](https://linux-hardware.org/?probe=52d550e878) | Jul 17, 2023 |
| ASUSTek       | P5E Deluxe                  | Desktop     | [895759fa79](https://linux-hardware.org/?probe=895759fa79) | Jul 01, 2023 |
| Acer          | Aspire V3-571G              | Notebook    | [9d4c4f5506](https://linux-hardware.org/?probe=9d4c4f5506) | Jun 29, 2023 |
| Gigabyte      | Z97-HD3                     | Desktop     | [731b4a6479](https://linux-hardware.org/?probe=731b4a6479) | Jun 26, 2023 |
| ASUSTek       | P8H61-M LX                  | Desktop     | [23b64edd39](https://linux-hardware.org/?probe=23b64edd39) | Jun 17, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [df63208f37](https://linux-hardware.org/?probe=df63208f37) | Jun 15, 2023 |
| HP            | Laptop 17-bs0xx             | Notebook    | [1cddf187c5](https://linux-hardware.org/?probe=1cddf187c5) | Jun 13, 2023 |
| ASUSTek       | PRIME B350-PLUS             | Desktop     | [cc1f571000](https://linux-hardware.org/?probe=cc1f571000) | Jun 09, 2023 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [1d36e85f27](https://linux-hardware.org/?probe=1d36e85f27) | Jun 07, 2023 |
| Sony          | VPCEH25EN                   | Notebook    | [2b47c1b9a5](https://linux-hardware.org/?probe=2b47c1b9a5) | Jun 05, 2023 |
| Fujitsu       | LIFEBOOK A357               | Notebook    | [a8baa03316](https://linux-hardware.org/?probe=a8baa03316) | Jun 03, 2023 |
| ASUSTek       | P5Q-PRO                     | Desktop     | [76cd01b045](https://linux-hardware.org/?probe=76cd01b045) | Jun 03, 2023 |
| Lenovo        | 1038 NO DPK                 | Server      | [e91c644324](https://linux-hardware.org/?probe=e91c644324) | Jun 02, 2023 |
| Acer          | Nitro AN517-54              | Notebook    | [4feb3e3196](https://linux-hardware.org/?probe=4feb3e3196) | May 27, 2023 |
| HP            | 0B4Ch D                     | Desktop     | [5352a94049](https://linux-hardware.org/?probe=5352a94049) | May 20, 2023 |
| Gigabyte      | P55-UD3                     | Desktop     | [12da248164](https://linux-hardware.org/?probe=12da248164) | May 19, 2023 |
| Dell          | Latitude 5320               | Notebook    | [5e8463c682](https://linux-hardware.org/?probe=5e8463c682) | May 16, 2023 |
| Dell          | Latitude 5320               | Notebook    | [093e6a63c8](https://linux-hardware.org/?probe=093e6a63c8) | May 16, 2023 |
| Dell          | 0GY6Y8 A02                  | Desktop     | [99ad79383e](https://linux-hardware.org/?probe=99ad79383e) | May 11, 2023 |
| Lenovo        | ThinkPad W541 20EF001UGE    | Notebook    | [29c8170a0e](https://linux-hardware.org/?probe=29c8170a0e) | May 10, 2023 |
| Lenovo        | V15-ADA 82C7                | Notebook    | [8eae6560cb](https://linux-hardware.org/?probe=8eae6560cb) | May 10, 2023 |
| Lenovo        | 1036 SDK0K17763 WIN 1801... | Desktop     | [eeb37c9c4f](https://linux-hardware.org/?probe=eeb37c9c4f) | May 07, 2023 |
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
| 5.14.21-150400.22-default           | 25        | 15.43%  |
| 5.14.21-150400.24.46-default        | 16        | 9.88%   |
| 5.14.21-150400.24.21-default        | 16        | 9.88%   |
| 5.14.21-150400.24.63-default        | 11        | 6.79%   |
| 5.14.21-150400.24.38-default        | 11        | 6.79%   |
| 5.14.21-150400.24.41-default        | 10        | 6.17%   |
| 5.14.21-150400.24.18-default        | 10        | 6.17%   |
| 5.14.21-150400.19-default           | 10        | 6.17%   |
| 5.14.21-150400.24.55-default        | 9         | 5.56%   |
| 5.14.21-150400.24.33-default        | 9         | 5.56%   |
| 5.14.21-150400.24.60-default        | 7         | 4.32%   |
| 5.14.21-150400.24.69-default        | 5         | 3.09%   |
| 5.14.21-150400.24.11-default        | 4         | 2.47%   |
| 5.18.0-rc6-lp153.2.ged50f8f-default | 2         | 1.23%   |
| 5.14.21-150400.24.97-default        | 2         | 1.23%   |
| 5.14.21-150400.24.84-default        | 2         | 1.23%   |
| 5.14.21-150400.24.28-default        | 2         | 1.23%   |
| 6.3.5-lp154.6-default               | 1         | 0.62%   |
| 5.18.2-lp153.4.g6d13af9-default     | 1         | 0.62%   |
| 5.14.21-150500.43-default           | 1         | 0.62%   |
| 5.14.21-150400.9-default            | 1         | 0.62%   |
| 5.14.21-150400.3-default            | 1         | 0.62%   |
| 5.14.21-150400.24.88-default        | 1         | 0.62%   |
| 5.14.21-150400.24.81-default        | 1         | 0.62%   |
| 5.14.21-150400.24.74-default        | 1         | 0.62%   |
| 5.14.21-150400.24.66-default        | 1         | 0.62%   |
| 5.14.21-150400.15-default           | 1         | 0.62%   |
| 5.14.19-150400.1-default            | 1         | 0.62%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14.21 | 133       | 96.38%  |
| 5.18.0  | 2         | 1.45%   |
| 6.3.5   | 1         | 0.72%   |
| 5.18.2  | 1         | 0.72%   |
| 5.14.19 | 1         | 0.72%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 5.14    | 134       | 97.1%   |
| 5.18    | 3         | 2.17%   |
| 6.3     | 1         | 0.72%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 137       | 100%    |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| KDE5        | 98        | 71.01%  |
| GNOME       | 17        | 12.32%  |
| Unknown     | 10        | 7.25%   |
| XFCE        | 6         | 4.35%   |
| Cinnamon    | 2         | 1.45%   |
| X-Cinnamon  | 1         | 0.72%   |
| WindowMaker | 1         | 0.72%   |
| LXDE        | 1         | 0.72%   |
| ICEWM       | 1         | 0.72%   |
| Deepin      | 1         | 0.72%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 115       | 82.73%  |
| Wayland | 16        | 11.51%  |
| Tty     | 6         | 4.32%   |
| Unknown | 2         | 1.44%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 60        | 43.8%   |
| SDDM    | 50        | 36.5%   |
| LightDM | 22        | 16.06%  |
| XDM     | 5         | 3.65%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| en_US   | 48        | 34.78%  |
| de_DE   | 28        | 20.29%  |
| POSIX   | 17        | 12.32%  |
| pt_BR   | 14        | 10.14%  |
| nl_NL   | 4         | 2.9%    |
| fr_FR   | 4         | 2.9%    |
| es_ES   | 4         | 2.9%    |
| en_GB   | 4         | 2.9%    |
| ru_RU   | 3         | 2.17%   |
| nn_NO   | 2         | 1.45%   |
| it_IT   | 2         | 1.45%   |
| ro_RO   | 1         | 0.72%   |
| pl_PL   | 1         | 0.72%   |
| hu_HU   | 1         | 0.72%   |
| en_IN   | 1         | 0.72%   |
| el_GR   | 1         | 0.72%   |
| de_CH   | 1         | 0.72%   |
| ca_ES   | 1         | 0.72%   |
| Unknown | 1         | 0.72%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 84        | 60.87%  |
| EFI  | 54        | 39.13%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Btrfs   | 95        | 69.34%  |
| Ext4    | 33        | 24.09%  |
| Xfs     | 6         | 4.38%   |
| Tmpfs   | 1         | 0.73%   |
| Overlay | 1         | 0.73%   |
| Ext3    | 1         | 0.73%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| GPT     | 71        | 51.45%  |
| Unknown | 57        | 41.3%   |
| MBR     | 10        | 7.25%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 122       | 87.77%  |
| Yes       | 17        | 12.23%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 115       | 83.94%  |
| Yes       | 22        | 16.06%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 28        | 20.44%  |
| Lenovo              | 20        | 14.6%   |
| Dell                | 20        | 14.6%   |
| Hewlett-Packard     | 19        | 13.87%  |
| MSI                 | 9         | 6.57%   |
| Gigabyte Technology | 7         | 5.11%   |
| ASRock              | 6         | 4.38%   |
| Acer                | 5         | 3.65%   |
| Intel               | 3         | 2.19%   |
| Fujitsu             | 3         | 2.19%   |
| Toshiba             | 2         | 1.46%   |
| Samsung Electronics | 2         | 1.46%   |
| Unknown             | 2         | 1.46%   |
| Wortmann AG         | 1         | 0.73%   |
| TUXEDO              | 1         | 0.73%   |
| Sony                | 1         | 0.73%   |
| Schenker            | 1         | 0.73%   |
| Notebook            | 1         | 0.73%   |
| Multilaser          | 1         | 0.73%   |
| Medion              | 1         | 0.73%   |
| LG Electronics      | 1         | 0.73%   |
| Jumper              | 1         | 0.73%   |
| Gateway             | 1         | 0.73%   |
| Biostar             | 1         | 0.73%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                     | Computers | Percent |
|------------------------------------------|-----------|---------|
| Samsung 550XDA                           | 2         | 1.46%   |
| HP Spectre x360 Convertible 13t-aw100    | 2         | 1.46%   |
| ASUS TUF Gaming B550M-E                  | 2         | 1.46%   |
| ASUS P5Q-PRO                             | 2         | 1.46%   |
| ASUS M4A785TD-V EVO                      | 2         | 1.46%   |
| ASUS CROSSHAIR V FORMULA-Z               | 2         | 1.46%   |
| Unknown                                  | 2         | 1.46%   |
| Wortmann AG Terra 3100                   | 1         | 0.73%   |
| TUXEDO InfinityBook S 15/17 Gen7         | 1         | 0.73%   |
| Toshiba Satellite P55t-A                 | 1         | 0.73%   |
| Toshiba Satellite L500                   | 1         | 0.73%   |
| Sony VPCEH25EN                           | 1         | 0.73%   |
| Schenker VIA 15 Pro                      | 1         | 0.73%   |
| Notebook NLx0MU                          | 1         | 0.73%   |
| Multilaser PC150                         | 1         | 0.73%   |
| MSI MS-7C02                              | 1         | 0.73%   |
| MSI MS-7B86                              | 1         | 0.73%   |
| MSI MS-7B85                              | 1         | 0.73%   |
| MSI MS-7B78                              | 1         | 0.73%   |
| MSI MS-7B09                              | 1         | 0.73%   |
| MSI MS-7971                              | 1         | 0.73%   |
| MSI MS-7850                              | 1         | 0.73%   |
| MSI MS-7673                              | 1         | 0.73%   |
| MSI Delta 15 A5EFK                       | 1         | 0.73%   |
| Medion MS-7848                           | 1         | 0.73%   |
| LG C400-G.BC22P1                         | 1         | 0.73%   |
| Lenovo V15-ADA 82C7                      | 1         | 0.73%   |
| Lenovo ThinkStation P920 30BDS2H804      | 1         | 0.73%   |
| Lenovo ThinkStation P520 30BE008VGE      | 1         | 0.73%   |
| Lenovo ThinkStation P500 30A6S4JU00      | 1         | 0.73%   |
| Lenovo ThinkPad X1 Carbon 7th 20QDS3B600 | 1         | 0.73%   |
| Lenovo ThinkPad W541 20EF001UGE          | 1         | 0.73%   |
| Lenovo ThinkPad T530 2394D56             | 1         | 0.73%   |
| Lenovo ThinkPad T520 42435GG             | 1         | 0.73%   |
| Lenovo ThinkPad T495s 20QJ0012UK         | 1         | 0.73%   |
| Lenovo ThinkPad T470 20HES0FW00          | 1         | 0.73%   |
| Lenovo ThinkPad T410 25223FG             | 1         | 0.73%   |
| Lenovo ThinkPad T16 Gen 1 21BVCTO1WW     | 1         | 0.73%   |
| Lenovo ThinkPad P50 20EQS0VV0C           | 1         | 0.73%   |
| Lenovo ThinkPad P16s Gen 1 21BT000MUK    | 1         | 0.73%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| Lenovo ThinkPad     | 12        | 8.76%   |
| Dell Inspiron       | 5         | 3.65%   |
| ASUS TUF            | 5         | 3.65%   |
| ASUS PRIME          | 5         | 3.65%   |
| Lenovo ThinkStation | 3         | 2.19%   |
| Lenovo IdeaPad      | 3         | 2.19%   |
| Dell Vostro         | 3         | 2.19%   |
| Dell PowerEdge      | 3         | 2.19%   |
| Dell OptiPlex       | 3         | 2.19%   |
| Dell Latitude       | 3         | 2.19%   |
| ASUS ROG            | 3         | 2.19%   |
| Acer Aspire         | 3         | 2.19%   |
| Toshiba Satellite   | 2         | 1.46%   |
| Samsung 550XDA      | 2         | 1.46%   |
| HP ZBook            | 2         | 1.46%   |
| HP Spectre          | 2         | 1.46%   |
| HP ProBook          | 2         | 1.46%   |
| HP EliteBook        | 2         | 1.46%   |
| HP Compaq           | 2         | 1.46%   |
| Fujitsu LIFEBOOK    | 2         | 1.46%   |
| ASUS P5Q-PRO        | 2         | 1.46%   |
| ASUS M4A785TD-V     | 2         | 1.46%   |
| ASUS CROSSHAIR      | 2         | 1.46%   |
| Unknown             | 2         | 1.46%   |
| Wortmann AG Terra   | 1         | 0.73%   |
| TUXEDO InfinityBook | 1         | 0.73%   |
| Sony VPCEH25EN      | 1         | 0.73%   |
| Schenker VIA        | 1         | 0.73%   |
| Notebook NLx0MU     | 1         | 0.73%   |
| Multilaser PC150    | 1         | 0.73%   |
| MSI MS-7C02         | 1         | 0.73%   |
| MSI MS-7B86         | 1         | 0.73%   |
| MSI MS-7B85         | 1         | 0.73%   |
| MSI MS-7B78         | 1         | 0.73%   |
| MSI MS-7B09         | 1         | 0.73%   |
| MSI MS-7971         | 1         | 0.73%   |
| MSI MS-7850         | 1         | 0.73%   |
| MSI MS-7673         | 1         | 0.73%   |
| MSI Delta           | 1         | 0.73%   |
| Medion MS-7848      | 1         | 0.73%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2021 | 26        | 18.98%  |
| 2020 | 10        | 7.3%    |
| 2019 | 10        | 7.3%    |
| 2018 | 10        | 7.3%    |
| 2022 | 9         | 6.57%   |
| 2009 | 9         | 6.57%   |
| 2017 | 8         | 5.84%   |
| 2015 | 8         | 5.84%   |
| 2013 | 8         | 5.84%   |
| 2012 | 8         | 5.84%   |
| 2014 | 7         | 5.11%   |
| 2011 | 7         | 5.11%   |
| 2010 | 6         | 4.38%   |
| 2008 | 4         | 2.92%   |
| 2016 | 3         | 2.19%   |
| 2007 | 2         | 1.46%   |
| 2006 | 1         | 0.73%   |
| 2005 | 1         | 0.73%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 65        | 47.45%  |
| Desktop     | 63        | 45.99%  |
| Server      | 4         | 2.92%   |
| Convertible | 3         | 2.19%   |
| Mini pc     | 1         | 0.73%   |
| All in one  | 1         | 0.73%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 127       | 92.03%  |
| Enabled  | 11        | 7.97%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 137       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB      | Computers | Percent |
|-----------------|-----------|---------|
| 8.01-16.0       | 27        | 19.29%  |
| 16.01-24.0      | 26        | 18.57%  |
| 32.01-64.0      | 25        | 17.86%  |
| 4.01-8.0        | 22        | 15.71%  |
| 3.01-4.0        | 16        | 11.43%  |
| 64.01-256.0     | 12        | 8.57%   |
| 24.01-32.0      | 6         | 4.29%   |
| More than 256.0 | 2         | 1.43%   |
| 2.01-3.0        | 2         | 1.43%   |
| 1.01-2.0        | 1         | 0.71%   |
| 0.51-1.0        | 1         | 0.71%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB   | Computers | Percent |
|-----------|-----------|---------|
| 2.01-3.0  | 39        | 26.17%  |
| 1.01-2.0  | 39        | 26.17%  |
| 4.01-8.0  | 35        | 23.49%  |
| 3.01-4.0  | 21        | 14.09%  |
| 8.01-16.0 | 7         | 4.7%    |
| 0.51-1.0  | 7         | 4.7%    |
| 0.01-0.5  | 1         | 0.67%   |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 71        | 50%     |
| 2      | 37        | 26.06%  |
| 3      | 17        | 11.97%  |
| 5      | 6         | 4.23%   |
| 4      | 5         | 3.52%   |
| 7      | 3         | 2.11%   |
| 6      | 2         | 1.41%   |
| 9      | 1         | 0.7%    |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 76        | 55.47%  |
| Yes       | 61        | 44.53%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 125       | 90.58%  |
| No        | 13        | 9.42%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 92        | 67.15%  |
| No        | 45        | 32.85%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 80        | 57.97%  |
| No        | 58        | 42.03%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country      | Computers | Percent |
|--------------|-----------|---------|
| Germany      | 39        | 28.47%  |
| USA          | 21        | 15.33%  |
| Brazil       | 14        | 10.22%  |
| Russia       | 7         | 5.11%   |
| Spain        | 6         | 4.38%   |
| UK           | 5         | 3.65%   |
| Netherlands  | 5         | 3.65%   |
| Italy        | 5         | 3.65%   |
| France       | 5         | 3.65%   |
| Norway       | 3         | 2.19%   |
| Switzerland  | 2         | 1.46%   |
| South Africa | 2         | 1.46%   |
| Serbia       | 2         | 1.46%   |
| Poland       | 2         | 1.46%   |
| Mexico       | 2         | 1.46%   |
| India        | 2         | 1.46%   |
| Australia    | 2         | 1.46%   |
| Taiwan       | 1         | 0.73%   |
| Sweden       | 1         | 0.73%   |
| Slovenia     | 1         | 0.73%   |
| Romania      | 1         | 0.73%   |
| Martinique   | 1         | 0.73%   |
| Luxembourg   | 1         | 0.73%   |
| Kazakhstan   | 1         | 0.73%   |
| Indonesia    | 1         | 0.73%   |
| Hungary      | 1         | 0.73%   |
| Greece       | 1         | 0.73%   |
| Finland      | 1         | 0.73%   |
| Czechia      | 1         | 0.73%   |
| Bulgaria     | 1         | 0.73%   |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City                 | Computers | Percent |
|----------------------|-----------|---------|
| Haßfurt             | 5         | 3.45%   |
| Moscow               | 3         | 2.07%   |
| Madrid               | 3         | 2.07%   |
| Darmstadt            | 3         | 2.07%   |
| Almere Stad          | 3         | 2.07%   |
| Stuttgart            | 2         | 1.38%   |
| Sao Paulo            | 2         | 1.38%   |
| Saint Joseph         | 2         | 1.38%   |
| Rio de Janeiro       | 2         | 1.38%   |
| Paris                | 2         | 1.38%   |
| Louisville           | 2         | 1.38%   |
| London               | 2         | 1.38%   |
| Joinville            | 2         | 1.38%   |
| Berlin               | 2         | 1.38%   |
| Bergisch Gladbach    | 2         | 1.38%   |
| Zierikzee            | 1         | 0.69%   |
| Yekaterinburg        | 1         | 0.69%   |
| West Bend            | 1         | 0.69%   |
| Vladivostok          | 1         | 0.69%   |
| Vaksdal              | 1         | 0.69%   |
| Ulyanovsk            | 1         | 0.69%   |
| Taichung             | 1         | 0.69%   |
| Sydney               | 1         | 0.69%   |
| Stockholm            | 1         | 0.69%   |
| Stazione-Fornola     | 1         | 0.69%   |
| Stadthagen           | 1         | 0.69%   |
| Skokie               | 1         | 0.69%   |
| Sao José dos Campos | 1         | 0.69%   |
| Santa Rosa           | 1         | 0.69%   |
| San Francisco        | 1         | 0.69%   |
| Saki                 | 1         | 0.69%   |
| Sainte-Tulle         | 1         | 0.69%   |
| Saint-Andre-le-Puy   | 1         | 0.69%   |
| Rostock              | 1         | 0.69%   |
| Roslindale           | 1         | 0.69%   |
| Rome                 | 1         | 0.69%   |
| Riviere Salee        | 1         | 0.69%   |
| Reggio Emilia        | 1         | 0.69%   |
| Recife               | 1         | 0.69%   |
| Rattelsdorf          | 1         | 0.69%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor                         | Computers | Drives | Percent |
|--------------------------------|-----------|--------|---------|
| Seagate                        | 44        | 65     | 20.18%  |
| Samsung Electronics            | 41        | 65     | 18.81%  |
| WDC                            | 26        | 49     | 11.93%  |
| Toshiba                        | 14        | 20     | 6.42%   |
| Kingston                       | 14        | 20     | 6.42%   |
| Crucial                        | 11        | 12     | 5.05%   |
| SanDisk                        | 7         | 12     | 3.21%   |
| SK hynix                       | 6         | 6      | 2.75%   |
| Intel                          | 5         | 6      | 2.29%   |
| Unknown                        | 4         | 5      | 1.83%   |
| Intenso                        | 3         | 4      | 1.38%   |
| Hitachi                        | 3         | 4      | 1.38%   |
| HGST                           | 3         | 3      | 1.38%   |
| PNY                            | 2         | 3      | 0.92%   |
| Patriot                        | 2         | 2      | 0.92%   |
| Micron Technology              | 2         | 2      | 0.92%   |
| Maxtor                         | 2         | 2      | 0.92%   |
| Kingston Technology Company    | 2         | 2      | 0.92%   |
| A-DATA Technology              | 2         | 2      | 0.92%   |
| Unknown                        | 2         | 2      | 0.92%   |
| VISIPRO                        | 1         | 1      | 0.46%   |
| Union Memory (Shenzhen)        | 1         | 1      | 0.46%   |
| TO Exter                       | 1         | 1      | 0.46%   |
| Team                           | 1         | 1      | 0.46%   |
| StoreJet                       | 1         | 1      | 0.46%   |
| SPCC                           | 1         | 2      | 0.46%   |
| Solid State Storage Technology | 1         | 1      | 0.46%   |
| Solid State Storage            | 1         | 1      | 0.46%   |
| Smartbuy                       | 1         | 2      | 0.46%   |
| Silicon Motion                 | 1         | 1      | 0.46%   |
| Plextor                        | 1         | 3      | 0.46%   |
| Phison Electronics             | 1         | 1      | 0.46%   |
| MAXIO Technology (Hangzhou)    | 1         | 1      | 0.46%   |
| MATSHITA                       | 1         | 1      | 0.46%   |
| Leven                          | 1         | 1      | 0.46%   |
| KIOXIA                         | 1         | 1      | 0.46%   |
| JMicron Technology             | 1         | 1      | 0.46%   |
| Hewlett-Packard                | 1         | 3      | 0.46%   |
| Gigabyte Technology            | 1         | 1      | 0.46%   |
| Fujitsu                        | 1         | 1      | 0.46%   |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                               | Computers | Percent |
|-----------------------------------------------------|-----------|---------|
| Samsung SSD 860 EVO 500GB                           | 5         | 1.98%   |
| Samsung SSD 840 EVO 120GB                           | 5         | 1.98%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983 250GB | 5         | 1.98%   |
| Kingston SA400S37480G 480GB SSD                     | 4         | 1.58%   |
| Kingston SA400S37240G 240GB SSD                     | 4         | 1.58%   |
| Seagate ST2000DM001-1ER164 2TB                      | 3         | 1.19%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO 2TB  | 3         | 1.19%   |
| Crucial CT1000MX500SSD1 1TB                         | 3         | 1.19%   |
| WDC WDS500G2B0A-00SM50 500GB SSD                    | 2         | 0.79%   |
| WDC WD10EZEX-08M2NA0 1TB                            | 2         | 0.79%   |
| WDC WD1003FZEX-00MK2A0 1TB                          | 2         | 0.79%   |
| Unknown MMC Card  128GB                             | 2         | 0.79%   |
| Toshiba XG6 NVMe SSD Controller 512GB               | 2         | 0.79%   |
| Seagate ST500DM002-1BD142 500GB                     | 2         | 0.79%   |
| Seagate ST3500418AS 500GB                           | 2         | 0.79%   |
| Seagate ST3000NM0053 3TB                            | 2         | 0.79%   |
| Seagate ST1000VX000-1CU162 1TB                      | 2         | 0.79%   |
| Seagate ST1000LM035-1RK172 1TB                      | 2         | 0.79%   |
| Seagate ST1000DM003-1CH162 1TB                      | 2         | 0.79%   |
| Seagate Expansion 1TB                               | 2         | 0.79%   |
| Sandisk WD Black SN850 1024GB                       | 2         | 0.79%   |
| SanDisk NVMe SSD Drive 240GB                        | 2         | 0.79%   |
| Samsung SSD 870 QVO 2TB                             | 2         | 0.79%   |
| Samsung SSD 860 EVO 250GB                           | 2         | 0.79%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963 256GB | 2         | 0.79%   |
| PNY CS900 480GB SSD                                 | 2         | 0.79%   |
| Kingston Company A2000 NVMe SSD 250GB               | 2         | 0.79%   |
| Kingston SA400S37960G 960GB SSD                     | 2         | 0.79%   |
| Intel SSD 600P Series 256GB                         | 2         | 0.79%   |
| Unknown                                             | 2         | 0.79%   |
| WDC WDS500G1B0B-00AS40 500GB SSD                    | 1         | 0.4%    |
| WDC WDS250G1B0A-00H9H0 250GB SSD                    | 1         | 0.4%    |
| WDC WDS100T2B0A-00SM50 1TB SSD                      | 1         | 0.4%    |
| WDC WDS100T1X0E-00AFY0 1TB                          | 1         | 0.4%    |
| WDC WD5000AZRX-00L4HB0 500GB                        | 1         | 0.4%    |
| WDC WD40EZRZ-00GXCB0 4TB                            | 1         | 0.4%    |
| WDC WD40EFRX-68WT0N0 4TB                            | 1         | 0.4%    |
| WDC WD4003FRYZ-01F0DB0 4TB                          | 1         | 0.4%    |
| WDC WD3200BPVT-22JJ5T0 320GB                        | 1         | 0.4%    |
| WDC WD3200AAKX-00ERMA0 320GB                        | 1         | 0.4%    |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 43        | 60     | 47.25%  |
| WDC                 | 23        | 41     | 25.27%  |
| Toshiba             | 10        | 16     | 10.99%  |
| Samsung Electronics | 4         | 4      | 4.4%    |
| Hitachi             | 3         | 4      | 3.3%    |
| HGST                | 3         | 3      | 3.3%    |
| Maxtor              | 2         | 2      | 2.2%    |
| TO Exter            | 1         | 1      | 1.1%    |
| StoreJet            | 1         | 1      | 1.1%    |
| Fujitsu             | 1         | 1      | 1.1%    |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 24        | 28     | 30.77%  |
| Kingston            | 12        | 15     | 15.38%  |
| Crucial             | 10        | 11     | 12.82%  |
| WDC                 | 5         | 5      | 6.41%   |
| Intenso             | 3         | 4      | 3.85%   |
| Toshiba             | 2         | 2      | 2.56%   |
| PNY                 | 2         | 3      | 2.56%   |
| Patriot             | 2         | 2      | 2.56%   |
| Intel               | 2         | 3      | 2.56%   |
| A-DATA Technology   | 2         | 2      | 2.56%   |
| Unknown             | 2         | 2      | 2.56%   |
| VISIPRO             | 1         | 1      | 1.28%   |
| Team                | 1         | 1      | 1.28%   |
| SPCC                | 1         | 2      | 1.28%   |
| Smartbuy            | 1         | 2      | 1.28%   |
| SK hynix            | 1         | 1      | 1.28%   |
| SanDisk             | 1         | 3      | 1.28%   |
| Plextor             | 1         | 3      | 1.28%   |
| Micron Technology   | 1         | 1      | 1.28%   |
| Leven               | 1         | 1      | 1.28%   |
| Hewlett-Packard     | 1         | 3      | 1.28%   |
| Gigabyte Technology | 1         | 1      | 1.28%   |
| China               | 1         | 1      | 1.28%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind    | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| HDD     | 74        | 133    | 37%     |
| SSD     | 66        | 97     | 33%     |
| NVMe    | 53        | 77     | 26.5%   |
| MMC     | 4         | 5      | 2%      |
| Unknown | 3         | 3      | 1.5%    |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 106       | 224    | 61.63%  |
| NVMe | 53        | 76     | 30.81%  |
| SAS  | 9         | 10     | 5.23%   |
| MMC  | 4         | 5      | 2.33%   |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 75        | 111    | 50.34%  |
| 0.51-1.0   | 41        | 67     | 27.52%  |
| 1.01-2.0   | 18        | 28     | 12.08%  |
| 2.01-3.0   | 6         | 8      | 4.03%   |
| 3.01-4.0   | 5         | 9      | 3.36%   |
| 4.01-10.0  | 3         | 6      | 2.01%   |
| 10.01-20.0 | 1         | 1      | 0.67%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| More than 3000 | 50        | 36.5%   |
| 1001-2000      | 28        | 20.44%  |
| 2001-3000      | 20        | 14.6%   |
| 501-1000       | 16        | 11.68%  |
| 251-500        | 14        | 10.22%  |
| 101-250        | 6         | 4.38%   |
| Unknown        | 2         | 1.46%   |
| 21-50          | 1         | 0.73%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 37        | 25.34%  |
| 51-100         | 24        | 16.44%  |
| 501-1000       | 20        | 13.7%   |
| 251-500        | 18        | 12.33%  |
| 1001-2000      | 16        | 10.96%  |
| More than 3000 | 11        | 7.53%   |
| 1-20           | 10        | 6.85%   |
| 2001-3000      | 7         | 4.79%   |
| Unknown        | 2         | 1.37%   |
| 21-50          | 1         | 0.68%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                                     | Computers | Drives | Percent |
|-------------------------------------------|-----------|--------|---------|
| Samsung Electronics SSD 840 EVO 120GB     | 4         | 5      | 22.22%  |
| WDC WD20EZRX-00D8PB0 2TB                  | 1         | 1      | 5.56%   |
| WDC WD20EFRX-68EUZN0 2TB                  | 1         | 1      | 5.56%   |
| Toshiba MK5055GSX 500GB                   | 1         | 3      | 5.56%   |
| Seagate ST9500420AS 500GB                 | 1         | 1      | 5.56%   |
| Seagate ST320LT007-9ZV142 320GB           | 1         | 1      | 5.56%   |
| Seagate ST2000DM001-1CH164 2TB            | 1         | 1      | 5.56%   |
| Samsung Electronics SSD 850 PRO 256GB     | 1         | 1      | 5.56%   |
| Maxtor 6L250S0 256GB                      | 1         | 1      | 5.56%   |
| Kingston SV300S37A120G 120GB SSD          | 1         | 1      | 5.56%   |
| Kingston SUV300S37A240G 240GB SSD         | 1         | 2      | 5.56%   |
| Intel SSD 600P Series 256GB               | 1         | 1      | 5.56%   |
| Hitachi HTS725025A9A364 250GB             | 1         | 2      | 5.56%   |
| Crucial CT250BX100SSD1 250GB              | 1         | 1      | 5.56%   |
| Biwin Storage Technology HP SSD EX900 1TB | 1         | 1      | 5.56%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor                   | Computers | Drives | Percent |
|--------------------------|-----------|--------|---------|
| Samsung Electronics      | 5         | 6      | 27.78%  |
| Seagate                  | 3         | 3      | 16.67%  |
| WDC                      | 2         | 2      | 11.11%  |
| Kingston                 | 2         | 3      | 11.11%  |
| Toshiba                  | 1         | 3      | 5.56%   |
| Maxtor                   | 1         | 1      | 5.56%   |
| Intel                    | 1         | 1      | 5.56%   |
| Hitachi                  | 1         | 2      | 5.56%   |
| Crucial                  | 1         | 1      | 5.56%   |
| Biwin Storage Technology | 1         | 1      | 5.56%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor  | Computers | Drives | Percent |
|---------|-----------|--------|---------|
| Seagate | 3         | 3      | 37.5%   |
| WDC     | 2         | 2      | 25%     |
| Toshiba | 1         | 3      | 12.5%   |
| Maxtor  | 1         | 1      | 12.5%   |
| Hitachi | 1         | 2      | 12.5%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SSD  | 8         | 10     | 47.06%  |
| HDD  | 7         | 11     | 41.18%  |
| NVMe | 2         | 2      | 11.76%  |

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
| Works    | 68        | 132    | 45.95%  |
| Detected | 63        | 160    | 42.57%  |
| Malfunc  | 17        | 23     | 11.49%  |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 90        | 44.78%  |
| AMD                            | 36        | 17.91%  |
| Samsung Electronics            | 18        | 8.96%   |
| SanDisk                        | 9         | 4.48%   |
| Kingston Technology Company    | 6         | 2.99%   |
| ASMedia Technology             | 6         | 2.99%   |
| SK hynix                       | 5         | 2.49%   |
| JMicron Technology             | 5         | 2.49%   |
| Marvell Technology Group       | 4         | 1.99%   |
| LSI Logic / Symbios Logic      | 4         | 1.99%   |
| Toshiba America Info Systems   | 2         | 1%      |
| Solid State Storage Technology | 2         | 1%      |
| Seagate Technology             | 2         | 1%      |
| Micron Technology              | 2         | 1%      |
| Union Memory (Shenzhen)        | 1         | 0.5%    |
| Silicon Motion                 | 1         | 0.5%    |
| Silicon Image                  | 1         | 0.5%    |
| Promise Technology             | 1         | 0.5%    |
| Phison Electronics             | 1         | 0.5%    |
| MAXIO Technology (Hangzhou)    | 1         | 0.5%    |
| KIOXIA                         | 1         | 0.5%    |
| Dell                           | 1         | 0.5%    |
| Biwin Storage Technology       | 1         | 0.5%    |
| ADATA Technology               | 1         | 0.5%    |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 20        | 8.66%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 8         | 3.46%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 3.03%   |
| AMD 400 Series Chipset SATA Controller                                                  | 7         | 3.03%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 6         | 2.6%    |
| AMD 500 Series Chipset SATA Controller                                                  | 6         | 2.6%    |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 5         | 2.16%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 2.16%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 5         | 2.16%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 5         | 2.16%   |
| SK hynix Gold P31/BC711/PC711 NVMe Solid State Drive                                    | 4         | 1.73%   |
| Samsung NVMe SSD Controller PM9A1/PM9A3/980PRO                                          | 4         | 1.73%   |
| Intel Volume Management Device NVMe RAID Controller                                     | 4         | 1.73%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 4         | 1.73%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.73%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 4         | 1.73%   |
| SanDisk WD PC SN810 / Black SN850 NVMe SSD                                              | 3         | 1.3%    |
| SanDisk Extreme Pro / WD Black SN750 / PC SN730 / Red SN700 NVMe SSD                    | 3         | 1.3%    |
| Samsung NVMe SSD Controller 980 (DRAM-less)                                             | 3         | 1.3%    |
| JMicron JMB363 SATA/IDE Controller                                                      | 3         | 1.3%    |
| Intel Tiger Lake-LP SATA Controller                                                     | 3         | 1.3%    |
| Intel 82801JI (ICH10 Family) SATA AHCI Controller                                       | 3         | 1.3%    |
| Intel 82801IBM/IEM (ICH9M/ICH9M-E) 4 port SATA Controller [AHCI mode]                   | 3         | 1.3%    |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.87%   |
| Solid State Storage CL1-3D256-Q11 NVMe SSD M.2                                          | 2         | 0.87%   |
| Seagate FireCuda 530 SSD                                                                | 2         | 0.87%   |
| SanDisk WD Green SN350 240GB (DRAM-less) / SN560E NVMe SSD                              | 2         | 0.87%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 2         | 0.87%   |
| LSI Logic / Symbios Logic MegaRAID SAS 2108 [Liberator]                                 | 2         | 0.87%   |
| Kingston Company A2000 NVMe SSD SM2263EN                                                | 2         | 0.87%   |
| Intel SSD 600P Series                                                                   | 2         | 0.87%   |
| Intel NM10/ICH7 Family SATA Controller [AHCI mode]                                      | 2         | 0.87%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 2         | 0.87%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 2         | 0.87%   |
| Intel C620 Series Chipset Family SSATA Controller [AHCI mode]                           | 2         | 0.87%   |
| Intel C620 Series Chipset Family SATA Controller [AHCI mode]                            | 2         | 0.87%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 0.87%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2         | 0.87%   |
| Intel 82801HB (ICH8) 4 port SATA Controller [AHCI mode]                                 | 2         | 0.87%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 2         | 0.87%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 109       | 55.33%  |
| NVMe | 52        | 26.4%   |
| IDE  | 21        | 10.66%  |
| RAID | 14        | 7.11%   |
| SCSI | 1         | 0.51%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 94        | 68.61%  |
| AMD    | 43        | 31.39%  |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| AMD Ryzen 7 5700G with Radeon Graphics        | 4         | 2.92%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 3         | 2.19%   |
| AMD Ryzen 7 5800U with Radeon Graphics        | 3         | 2.19%   |
| AMD Ryzen 5 2600 Six-Core Processor           | 3         | 2.19%   |
| Intel Pentium CPU P6200 @ 2.13GHz             | 2         | 1.46%   |
| Intel Core i7-4810MQ CPU @ 2.80GHz            | 2         | 1.46%   |
| Intel Core i7-1065G7 CPU @ 1.30GHz            | 2         | 1.46%   |
| Intel Core i5-7600K CPU @ 3.80GHz             | 2         | 1.46%   |
| Intel Core i5-4200U CPU @ 1.60GHz             | 2         | 1.46%   |
| Intel Core i5-3230M CPU @ 2.60GHz             | 2         | 1.46%   |
| Intel Core i5 CPU 750 @ 2.67GHz               | 2         | 1.46%   |
| Intel Core i3-4005U CPU @ 1.70GHz             | 2         | 1.46%   |
| Intel Core i3-2370M CPU @ 2.40GHz             | 2         | 1.46%   |
| Intel Core 2 Quad CPU Q9550 @ 2.83GHz         | 2         | 1.46%   |
| Intel Celeron N4020 CPU @ 1.10GHz             | 2         | 1.46%   |
| Intel 12th Gen Core i7-1260P                  | 2         | 1.46%   |
| Intel 11th Gen Core i3-1115G4 @ 3.00GHz       | 2         | 1.46%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.46%   |
| AMD Ryzen 5 3600 6-Core Processor             | 2         | 1.46%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.46%   |
| AMD Ryzen 5 1600 Six-Core Processor           | 2         | 1.46%   |
| AMD Phenom II X6 1100T Processor              | 2         | 1.46%   |
| AMD FX-8350 Eight-Core Processor              | 2         | 1.46%   |
| Intel Xeon W-2135 CPU @ 3.70GHz               | 1         | 0.73%   |
| Intel Xeon Silver 4110 CPU @ 2.10GHz          | 1         | 0.73%   |
| Intel Xeon Gold 6154 CPU @ 3.00GHz            | 1         | 0.73%   |
| Intel Xeon CPU X5675 @ 3.07GHz                | 1         | 0.73%   |
| Intel Xeon CPU W3530 @ 2.80GHz                | 1         | 0.73%   |
| Intel Xeon CPU E5450 @ 3.00GHz                | 1         | 0.73%   |
| Intel Xeon CPU E5-1620 v3 @ 3.50GHz           | 1         | 0.73%   |
| Intel Xeon CPU E5-1607 v2 @ 3.00GHz           | 1         | 0.73%   |
| Intel Xeon CPU E3-1230 v5 @ 3.40GHz           | 1         | 0.73%   |
| Intel Xeon CPU 5130 @ 2.00GHz                 | 1         | 0.73%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.73%   |
| Intel Pentium Dual-Core CPU E6500 @ 2.93GHz   | 1         | 0.73%   |
| Intel Pentium 4 CPU 3.20GHz                   | 1         | 0.73%   |
| Intel Core i7-9750H CPU @ 2.60GHz             | 1         | 0.73%   |
| Intel Core i7-8665U CPU @ 1.90GHz             | 1         | 0.73%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 1         | 0.73%   |
| Intel Core i7-6820HQ CPU @ 2.70GHz            | 1         | 0.73%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                   | Computers | Percent |
|-------------------------|-----------|---------|
| Intel Core i5           | 23        | 16.79%  |
| Intel Core i7           | 17        | 12.41%  |
| Other                   | 15        | 10.95%  |
| AMD Ryzen 7             | 13        | 9.49%   |
| AMD Ryzen 5             | 13        | 9.49%   |
| Intel Core i3           | 11        | 8.03%   |
| Intel Xeon              | 8         | 5.84%   |
| Intel Celeron           | 4         | 2.92%   |
| AMD Ryzen 9             | 4         | 2.92%   |
| Intel Core 2 Quad       | 3         | 2.19%   |
| Intel Core 2 Duo        | 3         | 2.19%   |
| Intel Pentium Dual-Core | 2         | 1.46%   |
| Intel Pentium           | 2         | 1.46%   |
| Intel Atom              | 2         | 1.46%   |
| AMD Phenom II X6        | 2         | 1.46%   |
| AMD Phenom II X4        | 2         | 1.46%   |
| AMD FX                  | 2         | 1.46%   |
| Intel Xeon Silver       | 1         | 0.73%   |
| Intel Xeon Gold         | 1         | 0.73%   |
| Intel Pentium 4         | 1         | 0.73%   |
| Intel Core 2            | 1         | 0.73%   |
| AMD Ryzen Threadripper  | 1         | 0.73%   |
| AMD Ryzen 7 PRO         | 1         | 0.73%   |
| AMD Ryzen 3             | 1         | 0.73%   |
| AMD Opteron             | 1         | 0.73%   |
| AMD A6                  | 1         | 0.73%   |
| AMD A4                  | 1         | 0.73%   |
| AMD A10                 | 1         | 0.73%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 4      | 50        | 36.5%   |
| 2      | 35        | 25.55%  |
| 8      | 17        | 12.41%  |
| 6      | 17        | 12.41%  |
| 12     | 6         | 4.38%   |
| 1      | 5         | 3.65%   |
| 16     | 4         | 2.92%   |
| 36     | 1         | 0.73%   |
| 32     | 1         | 0.73%   |
| 10     | 1         | 0.73%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 132       | 96.35%  |
| 2      | 4         | 2.92%   |
| 4      | 1         | 0.73%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 2      | 101       | 73.72%  |
| 1      | 36        | 26.28%  |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 137       | 100%    |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 58        | 41.73%  |
| 0x806c1    | 6         | 4.32%   |
| 0x0a50000c | 6         | 4.32%   |
| 0x206a7    | 4         | 2.88%   |
| 0x906a3    | 3         | 2.16%   |
| 0x506e3    | 3         | 2.16%   |
| 0x50654    | 3         | 2.16%   |
| 0x306c3    | 3         | 2.16%   |
| 0x1067a    | 3         | 2.16%   |
| 0x906e9    | 2         | 1.44%   |
| 0x806ea    | 2         | 1.44%   |
| 0x706a8    | 2         | 1.44%   |
| 0x106e5    | 2         | 1.44%   |
| 0x106ca    | 2         | 1.44%   |
| 0x0a50000d | 2         | 1.44%   |
| 0x08108109 | 2         | 1.44%   |
| 0x0800820d | 2         | 1.44%   |
| 0x06000852 | 2         | 1.44%   |
| 0x010000dc | 2         | 1.44%   |
| 0x010000c8 | 2         | 1.44%   |
| 0xf4a      | 1         | 0.72%   |
| 0xa0671    | 1         | 0.72%   |
| 0x906ea    | 1         | 0.72%   |
| 0x906a4    | 1         | 0.72%   |
| 0x90672    | 1         | 0.72%   |
| 0x806ec    | 1         | 0.72%   |
| 0x806e9    | 1         | 0.72%   |
| 0x806d1    | 1         | 0.72%   |
| 0x706e5    | 1         | 0.72%   |
| 0x6fb      | 1         | 0.72%   |
| 0x6f6      | 1         | 0.72%   |
| 0x506ca    | 1         | 0.72%   |
| 0x406e3    | 1         | 0.72%   |
| 0x40651    | 1         | 0.72%   |
| 0x306e4    | 1         | 0.72%   |
| 0x306a9    | 1         | 0.72%   |
| 0x20655    | 1         | 0.72%   |
| 0x0a601201 | 1         | 0.72%   |
| 0x0a50000b | 1         | 0.72%   |
| 0x0a404102 | 1         | 0.72%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| Haswell          | 13        | 9.49%   |
| Zen 3            | 12        | 8.76%   |
| KabyLake         | 11        | 8.03%   |
| Zen+             | 9         | 6.57%   |
| Skylake          | 9         | 6.57%   |
| SandyBridge      | 8         | 5.84%   |
| Penryn           | 8         | 5.84%   |
| TigerLake        | 6         | 4.38%   |
| IvyBridge        | 6         | 4.38%   |
| Unknown          | 6         | 4.38%   |
| Zen 2            | 5         | 3.65%   |
| Westmere         | 5         | 3.65%   |
| IceLake          | 5         | 3.65%   |
| Alderlake Hybrid | 5         | 3.65%   |
| Piledriver       | 4         | 2.92%   |
| K10              | 4         | 2.92%   |
| Zen              | 3         | 2.19%   |
| Nehalem          | 3         | 2.19%   |
| Core             | 3         | 2.19%   |
| Goldmont plus    | 2         | 1.46%   |
| Goldmont         | 2         | 1.46%   |
| CometLake        | 2         | 1.46%   |
| Bonnell          | 2         | 1.46%   |
| Steamroller      | 1         | 0.73%   |
| NetBurst         | 1         | 0.73%   |
| Excavator        | 1         | 0.73%   |
| Broadwell        | 1         | 0.73%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Intel                      | 58        | 36.94%  |
| Nvidia                     | 50        | 31.85%  |
| AMD                        | 47        | 29.94%  |
| S3 Graphics                | 1         | 0.64%   |
| Matrox Electronics Systems | 1         | 0.64%   |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                     | Computers | Percent |
|---------------------------------------------------------------------------|-----------|---------|
| AMD Cezanne [Radeon Vega Series / Radeon Vega Mobile Series]              | 11        | 6.83%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                           | 4         | 2.48%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                 | 4         | 2.48%   |
| Intel Haswell-ULT Integrated Graphics Controller                          | 4         | 2.48%   |
| Intel 3rd Gen Core processor Graphics Controller                          | 4         | 2.48%   |
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller | 4         | 2.48%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]      | 4         | 2.48%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                        | 3         | 1.86%   |
| Intel HD Graphics 620                                                     | 3         | 1.86%   |
| Intel Alder Lake-P GT2 [Iris Xe Graphics]                                 | 3         | 1.86%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller               | 3         | 1.86%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                   | 3         | 1.86%   |
| AMD Cedar [Radeon HD 5000/6000/7350/8350 Series]                          | 3         | 1.86%   |
| Nvidia GK107 [GeForce GT 640]                                             | 2         | 1.24%   |
| Nvidia GF119 [GeForce GT 610]                                             | 2         | 1.24%   |
| Nvidia GF108 [GeForce GT 630]                                             | 2         | 1.24%   |
| Nvidia GA107M [GeForce RTX 3050 Ti Mobile]                                | 2         | 1.24%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                | 2         | 1.24%   |
| Intel UHD Graphics 620                                                    | 2         | 1.24%   |
| Intel TigerLake-H GT1 [UHD Graphics]                                      | 2         | 1.24%   |
| Intel Tiger Lake-LP GT2 [UHD Graphics G4]                                 | 2         | 1.24%   |
| Intel Skylake GT2 [HD Graphics 520]                                       | 2         | 1.24%   |
| Intel Iris Plus Graphics G7                                               | 2         | 1.24%   |
| Intel HD Graphics 530                                                     | 2         | 1.24%   |
| Intel HD Graphics 500                                                     | 2         | 1.24%   |
| Intel GeminiLake [UHD Graphics 600]                                       | 2         | 1.24%   |
| Intel Core Processor Integrated Graphics Controller                       | 2         | 1.24%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                 | 2         | 1.24%   |
| AMD RS880 [Radeon HD 4200]                                                | 2         | 1.24%   |
| AMD Raphael                                                               | 2         | 1.24%   |
| AMD Navi 23 [Radeon RX 6600/6600 XT/6600M]                                | 2         | 1.24%   |
| AMD Navi 22 [Radeon RX 6700/6700 XT/6750 XT / 6800M/6850M XT]             | 2         | 1.24%   |
| AMD Lexa PRO [Radeon 540/540X/550/550X / RX 540X/550/550X]                | 2         | 1.24%   |
| S3 Graphics 86c764/765 [Trio32/64/64V+]                                   | 1         | 0.62%   |
| Nvidia TU117GLM [T550 Laptop GPU]                                         | 1         | 0.62%   |
| Nvidia TU117 [GeForce GTX 1650]                                           | 1         | 0.62%   |
| Nvidia TU106 [GeForce RTX 2070]                                           | 1         | 0.62%   |
| Nvidia GT218M [NVS 3100M]                                                 | 1         | 0.62%   |
| Nvidia GT218M [ION]                                                       | 1         | 0.62%   |
| Nvidia GT216 [GeForce GT 220]                                             | 1         | 0.62%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| 1 x Intel       | 43        | 31.39%  |
| 1 x AMD         | 37        | 27.01%  |
| 1 x Nvidia      | 31        | 22.63%  |
| Intel + Nvidia  | 13        | 9.49%   |
| AMD + Nvidia    | 5         | 3.65%   |
| 2 x AMD         | 3         | 2.19%   |
| Intel + AMD     | 2         | 1.46%   |
| 2 x Nvidia      | 1         | 0.73%   |
| 1 x S3 Graphics | 1         | 0.73%   |
| 1 x Matrox      | 1         | 0.73%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 108       | 78.26%  |
| Proprietary | 26        | 18.84%  |
| Unknown     | 4         | 2.9%    |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 80        | 57.97%  |
| 0.01-0.5   | 17        | 12.32%  |
| 1.01-2.0   | 14        | 10.14%  |
| 3.01-4.0   | 13        | 9.42%   |
| 0.51-1.0   | 5         | 3.62%   |
| 8.01-16.0  | 4         | 2.9%    |
| 7.01-8.0   | 3         | 2.17%   |
| 2.01-3.0   | 2         | 1.45%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 19        | 12.67%  |
| Samsung Electronics     | 18        | 12%     |
| Dell                    | 13        | 8.67%   |
| BOE                     | 13        | 8.67%   |
| Goldstar                | 10        | 6.67%   |
| LG Display              | 9         | 6%      |
| Fujitsu Siemens         | 9         | 6%      |
| Hewlett-Packard         | 6         | 4%      |
| Chimei Innolux          | 6         | 4%      |
| Lenovo                  | 5         | 3.33%   |
| InfoVision              | 4         | 2.67%   |
| Ancor Communications    | 4         | 2.67%   |
| Acer                    | 4         | 2.67%   |
| Philips                 | 3         | 2%      |
| LG Electronics          | 3         | 2%      |
| Iiyama                  | 3         | 2%      |
| AOC                     | 3         | 2%      |
| ViewSonic               | 2         | 1.33%   |
| Sharp                   | 2         | 1.33%   |
| NEC Computers           | 2         | 1.33%   |
| HannStar                | 2         | 1.33%   |
| Eizo                    | 2         | 1.33%   |
| BenQ                    | 2         | 1.33%   |
| Unknown                 | 1         | 0.67%   |
| Insignia                | 1         | 0.67%   |
| Hitachi                 | 1         | 0.67%   |
| Gigabyte Technology     | 1         | 0.67%   |
| Chi Mei Optoelectronics | 1         | 0.67%   |
| ASUSTek Computer        | 1         | 0.67%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                 | Computers | Percent |
|-----------------------------------------------------------------------|-----------|---------|
| Fujitsu Siemens P19-2 FUS0552 1280x1024 376x301mm 19.0-inch           | 6         | 3.85%   |
| BOE LCD Monitor BOE08CD 1366x768 344x194mm 15.5-inch                  | 3         | 1.92%   |
| LG Electronics LCD Monitor LG ULTRAGEAR 1920x1080                     | 2         | 1.28%   |
| InfoVision LCD Monitor IVO8584 1920x1080 294x165mm 13.3-inch          | 2         | 1.28%   |
| Hewlett-Packard 27fh HPN354A 1920x1080 598x336mm 27.0-inch            | 2         | 1.28%   |
| Dell DELL3007WFPHC DEL4016 2560x1600 646x406mm 30.0-inch              | 2         | 1.28%   |
| BOE LCD Monitor BOE0812 1920x1080 344x194mm 15.5-inch                 | 2         | 1.28%   |
| AU Optronics LCD Monitor AUO219D 1920x1080 381x214mm 17.2-inch        | 2         | 1.28%   |
| ViewSonic VA2265 SERIES VSCB330 1920x1080 476x268mm 21.5-inch         | 1         | 0.64%   |
| ViewSonic EP3220T VSC33F3 1920x1080 700x390mm 31.5-inch               | 1         | 0.64%   |
| Unknown SMART TV 0563 1920x1080 1209x680mm 54.6-inch                  | 1         | 0.64%   |
| Sharp LQ156M1JW03 SHP155D 1920x1080 344x194mm 15.5-inch               | 1         | 0.64%   |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch               | 1         | 0.64%   |
| Samsung Electronics U28E590 SAM0C4D 3840x2160 610x350mm 27.7-inch     | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM058F 1920x1080 477x268mm 21.5-inch  | 1         | 0.64%   |
| Samsung Electronics SyncMaster SAM0226 1440x900 410x257mm 19.1-inch   | 1         | 0.64%   |
| Samsung Electronics SMS24A850 SAM0825 1920x1200 518x324mm 24.1-inch   | 1         | 0.64%   |
| Samsung Electronics SMS24A450 SAM0839 1920x1200 520x320mm 24.0-inch   | 1         | 0.64%   |
| Samsung Electronics S27E450 SAM0C83 1920x1080 598x336mm 27.0-inch     | 1         | 0.64%   |
| Samsung Electronics S24E650 SAM0C85 1920x1200 518x324mm 24.1-inch     | 1         | 0.64%   |
| Samsung Electronics S23B350 SAM08F4 1920x1080 510x287mm 23.0-inch     | 1         | 0.64%   |
| Samsung Electronics S22A33x SAM7122 1920x1080 479x260mm 21.5-inch     | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 309x174mm 14.0-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SEC3152 1366x768 344x194mm 15.5-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC894F 1920x1080 344x194mm 15.5-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC3754 1600x900 382x215mm 17.3-inch  | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SDC324C 1920x1080 344x194mm 15.5-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM07C3 1920x1080 700x390mm 31.5-inch | 1         | 0.64%   |
| Samsung Electronics LCD Monitor SAM0509 1920x1080                     | 1         | 0.64%   |
| Samsung Electronics F27G3xTF SAM710D 1920x1080 600x330mm 27.0-inch    | 1         | 0.64%   |
| Samsung Electronics C32JG5x SAM0F55 2560x1440 697x392mm 31.5-inch     | 1         | 0.64%   |
| Samsung Electronics C24F390 SAM0D2C 1920x1080 521x293mm 23.5-inch     | 1         | 0.64%   |
| Philips PHL 273V5 PHLC0D2 1920x1080 598x336mm 27.0-inch               | 1         | 0.64%   |
| Philips PHL 243V7 PHLC155 1920x1080 527x296mm 23.8-inch               | 1         | 0.64%   |
| Philips 190X PHL084C 1280x1024 376x301mm 19.0-inch                    | 1         | 0.64%   |
| NEC Computers LCD1960NX NEC661F 1280x1024 376x301mm 19.0-inch         | 1         | 0.64%   |
| NEC Computers LCD1545V NEC65D7 1024x768 304x228mm 15.0-inch           | 1         | 0.64%   |
| LG Electronics LCD Monitor E2260 1920x1080                            | 1         | 0.64%   |
| LG Display LCD Monitor LGDD801 1366x768 344x194mm 15.5-inch           | 1         | 0.64%   |
| LG Display LCD Monitor LGD05E5 1920x1080 344x194mm 15.5-inch          | 1         | 0.64%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 71        | 49.31%  |
| 1366x768 (WXGA)    | 22        | 15.28%  |
| 1280x1024 (SXGA)   | 13        | 9.03%   |
| 2560x1440 (QHD)    | 11        | 7.64%   |
| 1920x1200 (WUXGA)  | 5         | 3.47%   |
| 1680x1050 (WSXGA+) | 3         | 2.08%   |
| 1600x900 (HD+)     | 3         | 2.08%   |
| 1440x900 (WXGA+)   | 3         | 2.08%   |
| 3840x2160 (4K)     | 2         | 1.39%   |
| 2560x1600          | 2         | 1.39%   |
| 1600x1200          | 2         | 1.39%   |
| 3840x1600          | 1         | 0.69%   |
| 3440x1440          | 1         | 0.69%   |
| 1920x515           | 1         | 0.69%   |
| 1280x960           | 1         | 0.69%   |
| 1280x800 (WXGA)    | 1         | 0.69%   |
| 1024x768 (XGA)     | 1         | 0.69%   |
| 1024x600           | 1         | 0.69%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches  | Computers | Percent |
|---------|-----------|---------|
| 15      | 35        | 23.03%  |
| 24      | 15        | 9.87%   |
| 27      | 14        | 9.21%   |
| 19      | 12        | 7.89%   |
| 13      | 11        | 7.24%   |
| 23      | 10        | 6.58%   |
| 21      | 9         | 5.92%   |
| 17      | 9         | 5.92%   |
| 14      | 8         | 5.26%   |
| 31      | 5         | 3.29%   |
| Unknown | 5         | 3.29%   |
| 16      | 3         | 1.97%   |
| 54      | 2         | 1.32%   |
| 30      | 2         | 1.32%   |
| 22      | 2         | 1.32%   |
| 20      | 2         | 1.32%   |
| 18      | 2         | 1.32%   |
| 38      | 1         | 0.66%   |
| 37      | 1         | 0.66%   |
| 34      | 1         | 0.66%   |
| 32      | 1         | 0.66%   |
| 12      | 1         | 0.66%   |
| 10      | 1         | 0.66%   |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 52        | 35.14%  |
| 501-600     | 33        | 22.3%   |
| 351-400     | 19        | 12.84%  |
| 401-500     | 18        | 12.16%  |
| 601-700     | 8         | 5.41%   |
| 201-300     | 7         | 4.73%   |
| Unknown     | 5         | 3.38%   |
| 801-900     | 2         | 1.35%   |
| 701-800     | 2         | 1.35%   |
| 1001-1500   | 2         | 1.35%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio   | Computers | Percent |
|---------|-----------|---------|
| 16/9    | 100       | 71.94%  |
| 16/10   | 15        | 10.79%  |
| 5/4     | 12        | 8.63%   |
| 4/3     | 4         | 2.88%   |
| Unknown | 3         | 2.16%   |
| 21/9    | 2         | 1.44%   |
| 6/5     | 1         | 0.72%   |
| 3/2     | 1         | 0.72%   |
| 3.73    | 1         | 0.72%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 36        | 24%     |
| 201-250        | 25        | 16.67%  |
| 151-200        | 16        | 10.67%  |
| 81-90          | 14        | 9.33%   |
| 301-350        | 14        | 9.33%   |
| 351-500        | 10        | 6.67%   |
| 251-300        | 7         | 4.67%   |
| 121-130        | 7         | 4.67%   |
| 71-80          | 5         | 3.33%   |
| 141-150        | 5         | 3.33%   |
| Unknown        | 5         | 3.33%   |
| More than 1000 | 2         | 1.33%   |
| 61-70          | 1         | 0.67%   |
| 41-50          | 1         | 0.67%   |
| 111-120        | 1         | 0.67%   |
| 501-1000       | 1         | 0.67%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density | Computers | Percent |
|---------|-----------|---------|
| 51-100  | 57        | 39.86%  |
| 101-120 | 39        | 27.27%  |
| 121-160 | 34        | 23.78%  |
| 161-240 | 6         | 4.2%    |
| Unknown | 5         | 3.5%    |
| 1-50    | 2         | 1.4%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 110       | 79.14%  |
| 2     | 17        | 12.23%  |
| 3     | 6         | 4.32%   |
| 0     | 6         | 4.32%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 82        | 38.5%   |
| Intel                    | 72        | 33.8%   |
| Qualcomm Atheros         | 18        | 8.45%   |
| Broadcom                 | 10        | 4.69%   |
| MediaTek                 | 4         | 1.88%   |
| Ralink                   | 3         | 1.41%   |
| Marvell Technology Group | 3         | 1.41%   |
| TP-Link                  | 2         | 0.94%   |
| Samsung Electronics      | 2         | 0.94%   |
| NetGear                  | 2         | 0.94%   |
| Lenovo                   | 2         | 0.94%   |
| Broadcom Limited         | 2         | 0.94%   |
| Sitecom Europe           | 1         | 0.47%   |
| Sierra Wireless          | 1         | 0.47%   |
| Ralink Technology        | 1         | 0.47%   |
| Qualcomm                 | 1         | 0.47%   |
| Microchip Technology     | 1         | 0.47%   |
| Linksys                  | 1         | 0.47%   |
| JMicron Technology       | 1         | 0.47%   |
| Dell                     | 1         | 0.47%   |
| AVM                      | 1         | 0.47%   |
| Atmel                    | 1         | 0.47%   |
| Aquantia                 | 1         | 0.47%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 22.63%  |
| Intel Wi-Fi 6 AX200                                               | 7         | 2.88%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 2.47%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 2.47%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 2.06%   |
| Intel Ethernet Controller I225-V                                  | 5         | 2.06%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 1.65%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                            | 4         | 1.65%   |
| Intel Alder Lake-P PCH CNVi WiFi                                  | 4         | 1.65%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter        | 3         | 1.23%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter     | 3         | 1.23%   |
| Intel Wi-Fi 6 AX201                                               | 3         | 1.23%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                   | 3         | 1.23%   |
| Intel I211 Gigabit Network Connection                             | 3         | 1.23%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 1.23%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter          | 2         | 0.82%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.82%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter          | 2         | 0.82%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 0.82%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 0.82%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 0.82%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 0.82%   |
| Realtek 802.11n WLAN Adapter                                      | 2         | 0.82%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter        | 2         | 0.82%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                  | 2         | 0.82%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 0.82%   |
| Intel Wireless-AC 9260                                            | 2         | 0.82%   |
| Intel Wireless 8265 / 8275                                        | 2         | 0.82%   |
| Intel Wireless 8260                                               | 2         | 0.82%   |
| Intel Wireless 7265                                               | 2         | 0.82%   |
| Intel Wireless 7260                                               | 2         | 0.82%   |
| Intel Tiger Lake PCH CNVi WiFi                                    | 2         | 0.82%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 0.82%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 0.82%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 0.82%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 0.82%   |
| Intel Comet Lake PCH CNVi WiFi                                    | 2         | 0.82%   |
| Intel Centrino Ultimate-N 6300                                    | 2         | 0.82%   |
| Intel Cannon Lake PCH CNVi WiFi                                   | 2         | 0.82%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 0.82%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 49        | 51.58%  |
| Realtek Semiconductor | 14        | 14.74%  |
| Qualcomm Atheros      | 13        | 13.68%  |
| MediaTek              | 4         | 4.21%   |
| Ralink                | 3         | 3.16%   |
| NetGear               | 2         | 2.11%   |
| Broadcom              | 2         | 2.11%   |
| TP-Link               | 1         | 1.05%   |
| Sierra Wireless       | 1         | 1.05%   |
| Samsung Electronics   | 1         | 1.05%   |
| Ralink Technology     | 1         | 1.05%   |
| Qualcomm              | 1         | 1.05%   |
| Linksys               | 1         | 1.05%   |
| Broadcom Limited      | 1         | 1.05%   |
| AVM                   | 1         | 1.05%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Intel Wi-Fi 6 AX200                                           | 7         | 7.22%   |
| Intel Wi-Fi 6 AX210/AX211/AX411 160MHz                        | 4         | 4.12%   |
| Intel Alder Lake-P PCH CNVi WiFi                              | 4         | 4.12%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter    | 3         | 3.09%   |
| MediaTek MT7921 802.11ax PCI Express Wireless Network Adapter | 3         | 3.09%   |
| Intel Wi-Fi 6 AX201                                           | 3         | 3.09%   |
| Intel Ice Lake-LP PCH CNVi WiFi                               | 3         | 3.09%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter      | 2         | 2.06%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter      | 2         | 2.06%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter      | 2         | 2.06%   |
| Realtek 802.11n WLAN Adapter                                  | 2         | 2.06%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter    | 2         | 2.06%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter              | 2         | 2.06%   |
| Intel Wireless-AC 9260                                        | 2         | 2.06%   |
| Intel Wireless 8265 / 8275                                    | 2         | 2.06%   |
| Intel Wireless 8260                                           | 2         | 2.06%   |
| Intel Wireless 7265                                           | 2         | 2.06%   |
| Intel Wireless 7260                                           | 2         | 2.06%   |
| Intel Tiger Lake PCH CNVi WiFi                                | 2         | 2.06%   |
| Intel Comet Lake PCH CNVi WiFi                                | 2         | 2.06%   |
| Intel Centrino Ultimate-N 6300                                | 2         | 2.06%   |
| Intel Cannon Lake PCH CNVi WiFi                               | 2         | 2.06%   |
| Broadcom BCM43142 802.11b/g/n                                 | 2         | 2.06%   |
| TP-Link TL-WN821N v5/v6 [RTL8192EU]                           | 1         | 1.03%   |
| Sierra Wireless EM7455                                        | 1         | 1.03%   |
| Samsung WIS09ABGN LinkStick Wireless LAN Adapter              | 1         | 1.03%   |
| Realtek RTL88x2bu [AC1200 Techkey]                            | 1         | 1.03%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter      | 1         | 1.03%   |
| Realtek RTL8723BU 802.11b/g/n WLAN Adapter                    | 1         | 1.03%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter               | 1         | 1.03%   |
| Realtek RTL8192EE PCIe Wireless Network Adapter               | 1         | 1.03%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter           | 1         | 1.03%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                    | 1         | 1.03%   |
| Ralink MT7601U Wireless Adapter                               | 1         | 1.03%   |
| Ralink RT5392 PCIe Wireless Network Adapter                   | 1         | 1.03%   |
| Ralink RT3290 Wireless 802.11n 1T/1R PCIe                     | 1         | 1.03%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                     | 1         | 1.03%   |
| Qualcomm QCNFA765 Wireless Network Adapter                    | 1         | 1.03%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter    | 1         | 1.03%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter              | 1         | 1.03%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 74        | 52.11%  |
| Intel                    | 41        | 28.87%  |
| Broadcom                 | 8         | 5.63%   |
| Qualcomm Atheros         | 7         | 4.93%   |
| Marvell Technology Group | 3         | 2.11%   |
| Lenovo                   | 2         | 1.41%   |
| TP-Link                  | 1         | 0.7%    |
| Sitecom Europe           | 1         | 0.7%    |
| Samsung Electronics      | 1         | 0.7%    |
| JMicron Technology       | 1         | 0.7%    |
| Dell                     | 1         | 0.7%    |
| Broadcom Limited         | 1         | 0.7%    |
| Aquantia                 | 1         | 0.7%    |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                             | Computers | Percent |
|-------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller | 55        | 38.19%  |
| Realtek RTL8153 Gigabit Ethernet Adapter                          | 6         | 4.17%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)             | 6         | 4.17%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller             | 5         | 3.47%   |
| Intel Ethernet Controller I225-V                                  | 5         | 3.47%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet    | 4         | 2.78%   |
| Intel I211 Gigabit Network Connection                             | 3         | 2.08%   |
| Intel Ethernet Connection I217-LM                                 | 3         | 2.08%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                   | 2         | 1.39%   |
| Realtek RTL8125 2.5GbE Controller                                 | 2         | 1.39%   |
| Realtek RTL-8100/8101L/8139 PCI Fast Ethernet Adapter             | 2         | 1.39%   |
| Realtek Killer E2600 Gigabit Ethernet Controller                  | 2         | 1.39%   |
| Marvell Group 88E8056 PCI-E Gigabit Ethernet Controller           | 2         | 1.39%   |
| Intel Ethernet Connection (4) I219-LM                             | 2         | 1.39%   |
| Intel Ethernet Connection (2) I219-V                              | 2         | 1.39%   |
| Intel Ethernet Connection (2) I219-LM                             | 2         | 1.39%   |
| Intel Ethernet Connection (16) I219-V                             | 2         | 1.39%   |
| Intel 82583V Gigabit Network Connection                           | 2         | 1.39%   |
| Broadcom NetXtreme BCM5764M Gigabit Ethernet PCIe                 | 2         | 1.39%   |
| Broadcom NetXtreme BCM5720 Gigabit Ethernet PCIe                  | 2         | 1.39%   |
| TP-Link UE300 10/100/1000 LAN (ethernet mode) [Realtek RTL8153]   | 1         | 0.69%   |
| Sitecom Europe AX88179 Gigabit Ethernet [Sitecom]                 | 1         | 0.69%   |
| Samsung Galaxy series, misc. (tethering mode)                     | 1         | 0.69%   |
| Realtek RTL8152 Fast Ethernet Adapter                             | 1         | 0.69%   |
| Qualcomm Atheros QCA8171 Gigabit Ethernet                         | 1         | 0.69%   |
| Qualcomm Atheros Attansic L1 Gigabit Ethernet                     | 1         | 0.69%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                          | 1         | 0.69%   |
| Marvell Group 88E8072 PCI-E Gigabit Ethernet Controller           | 1         | 0.69%   |
| Lenovo USB-C Dock Ethernet                                        | 1         | 0.69%   |
| Lenovo ThinkPad TBT 3 Dock                                        | 1         | 0.69%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller            | 1         | 0.69%   |
| Intel NM10/ICH7 Family LAN Controller                             | 1         | 0.69%   |
| Intel I350 Gigabit Network Connection                             | 1         | 0.69%   |
| Intel I210 Gigabit Network Connection                             | 1         | 0.69%   |
| Intel Ethernet Connection I219-LM                                 | 1         | 0.69%   |
| Intel Ethernet Connection (6) I219-LM                             | 1         | 0.69%   |
| Intel Ethernet Connection (3) I219-LM                             | 1         | 0.69%   |
| Intel Ethernet Connection (3) I218-LM                             | 1         | 0.69%   |
| Intel Ethernet Connection (2) I218-LM                             | 1         | 0.69%   |
| Intel Ethernet Connection (13) I219-V                             | 1         | 0.69%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 125       | 57.6%   |
| WiFi     | 91        | 41.94%  |
| Modem    | 1         | 0.46%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 84        | 59.57%  |
| WiFi     | 57        | 40.43%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 75        | 54.74%  |
| 1     | 51        | 37.23%  |
| 3     | 4         | 2.92%   |
| 0     | 4         | 2.92%   |
| 4     | 2         | 1.46%   |
| 5     | 1         | 0.73%   |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 95        | 66.9%   |
| Yes  | 47        | 33.1%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 42        | 51.85%  |
| Realtek Semiconductor           | 9         | 11.11%  |
| Cambridge Silicon Radio         | 7         | 8.64%   |
| Qualcomm Atheros Communications | 5         | 6.17%   |
| IMC Networks                    | 5         | 6.17%   |
| Broadcom                        | 5         | 6.17%   |
| Hewlett-Packard                 | 2         | 2.47%   |
| Ralink                          | 1         | 1.23%   |
| MediaTek                        | 1         | 1.23%   |
| Lite-On Technology              | 1         | 1.23%   |
| Edimax Technology               | 1         | 1.23%   |
| Belkin Components               | 1         | 1.23%   |
| ASUSTek Computer                | 1         | 1.23%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                       | Computers | Percent |
|-------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                          | 9         | 11.11%  |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)              | 7         | 8.64%   |
| Intel AX201 Bluetooth                                       | 7         | 8.64%   |
| Intel AX200 Bluetooth                                       | 7         | 8.64%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)         | 7         | 8.64%   |
| Realtek Bluetooth Radio                                     | 6         | 7.41%   |
| Intel AX210 Bluetooth                                       | 4         | 4.94%   |
| Intel Bluetooth Device                                      | 3         | 3.7%    |
| Realtek 802.11ac WLAN Adapter                               | 2         | 2.47%   |
| Qualcomm Atheros  Bluetooth Device                          | 2         | 2.47%   |
| Intel Wireless-AC 9260 Bluetooth Adapter                    | 2         | 2.47%   |
| Intel Centrino Bluetooth Wireless Transceiver               | 2         | 2.47%   |
| IMC Networks Wireless_Device                                | 2         | 2.47%   |
| IMC Networks Bluetooth Device                               | 2         | 2.47%   |
| Broadcom BCM2045B (BDC-2.1)                                 | 2         | 2.47%   |
| Realtek  Bluetooth 4.2 Adapter                              | 1         | 1.23%   |
| Ralink RT3290 Bluetooth                                     | 1         | 1.23%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                      | 1         | 1.23%   |
| Qualcomm Atheros AR9462 Bluetooth                           | 1         | 1.23%   |
| Qualcomm Atheros AR3011 Bluetooth                           | 1         | 1.23%   |
| MediaTek Wireless_Device                                    | 1         | 1.23%   |
| Lite-On Wireless_Device                                     | 1         | 1.23%   |
| Intel Wireless-AC 3168 Bluetooth                            | 1         | 1.23%   |
| IMC Networks Atheros AR3012 Bluetooth                       | 1         | 1.23%   |
| HP Integrated Module with Bluetooth 2.1 Wireless technology | 1         | 1.23%   |
| HP Bluetooth 2.0 Interface [Broadcom BCM2045]               | 1         | 1.23%   |
| Edimax EW-7611ULB 802.11b/g/n and Bluetooth 4.0 Adapter     | 1         | 1.23%   |
| Broadcom Bluetooth Controller                               | 1         | 1.23%   |
| Broadcom BCM43142 Bluetooth 4.0                             | 1         | 1.23%   |
| Broadcom BCM20702A0 Bluetooth 4.0                           | 1         | 1.23%   |
| Belkin Components F8T065BF Mini Bluetooth 4.0 Adapter       | 1         | 1.23%   |
| ASUS Broadcom BCM20702A0 Bluetooth                          | 1         | 1.23%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                      | Computers | Percent |
|-----------------------------|-----------|---------|
| Intel                       | 90        | 44.55%  |
| AMD                         | 49        | 24.26%  |
| Nvidia                      | 39        | 19.31%  |
| C-Media Electronics         | 6         | 2.97%   |
| Creative Labs               | 3         | 1.49%   |
| Lenovo                      | 2         | 0.99%   |
| GN Netcom                   | 2         | 0.99%   |
| Ensoniq                     | 2         | 0.99%   |
| VIA Technologies            | 1         | 0.5%    |
| Texas Instruments           | 1         | 0.5%    |
| Realtek Semiconductor       | 1         | 0.5%    |
| Plantronics                 | 1         | 0.5%    |
| Microsoft                   | 1         | 0.5%    |
| Logitech                    | 1         | 0.5%    |
| JMTek                       | 1         | 0.5%    |
| FiiO Electronics Technology | 1         | 0.5%    |
| ASUSTek Computer            | 1         | 0.5%    |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                      | Computers | Percent |
|----------------------------------------------------------------------------|-----------|---------|
| AMD Family 17h/19h HD Audio Controller                                     | 19        | 7.6%    |
| AMD Renoir Radeon High Definition Audio Controller                         | 13        | 5.2%    |
| Intel Sunrise Point-LP HD Audio                                            | 7         | 2.8%    |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller        | 7         | 2.8%    |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller        | 7         | 2.8%    |
| AMD Family 17h (Models 00h-0fh) HD Audio Controller                        | 7         | 2.8%    |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                | 6         | 2.4%    |
| Intel 5 Series/3400 Series Chipset High Definition Audio                   | 6         | 2.4%    |
| AMD SBx00 Azalia (Intel HDA)                                               | 6         | 2.4%    |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller           | 5         | 2%      |
| Intel 82801JI (ICH10 Family) HD Audio Controller                           | 5         | 2%      |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller | 5         | 2%      |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller            | 5         | 2%      |
| AMD Starship/Matisse HD Audio Controller                                   | 5         | 2%      |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller             | 4         | 1.6%    |
| Nvidia GP107GL High Definition Audio Controller                            | 4         | 1.6%    |
| Nvidia GF119 HDMI Audio Controller                                         | 4         | 1.6%    |
| Nvidia GF108 High Definition Audio Controller                              | 4         | 1.6%    |
| Intel Haswell-ULT HD Audio Controller                                      | 4         | 1.6%    |
| Intel Alder Lake PCH-P High Definition Audio Controller                    | 4         | 1.6%    |
| Intel 82801I (ICH9 Family) HD Audio Controller                             | 4         | 1.6%    |
| Intel 8 Series HD Audio Controller                                         | 4         | 1.6%    |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                        | 4         | 1.6%    |
| AMD Navi 21/23 HDMI/DP Audio Controller                                    | 4         | 1.6%    |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                 | 4         | 1.6%    |
| Nvidia GK208 HDMI/DP Audio Controller                                      | 3         | 1.2%    |
| Nvidia GK107 HDMI Audio Controller                                         | 3         | 1.2%    |
| Intel Tiger Lake-H HD Audio Controller                                     | 3         | 1.2%    |
| Intel NM10/ICH7 Family High Definition Audio Controller                    | 3         | 1.2%    |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                  | 3         | 1.2%    |
| Intel 82801H (ICH8 Family) HD Audio Controller                             | 3         | 1.2%    |
| AMD Rembrandt Radeon High Definition Audio Controller                      | 3         | 1.2%    |
| AMD Cedar HDMI Audio [Radeon HD 5400/6300/7300 Series]                     | 3         | 1.2%    |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]               | 3         | 1.2%    |
| Nvidia High Definition Audio Controller                                    | 2         | 0.8%    |
| Nvidia GM107 High Definition Audio Controller [GeForce 940MX]              | 2         | 0.8%    |
| Nvidia GK106 HDMI Audio Controller                                         | 2         | 0.8%    |
| Nvidia GA106 High Definition Audio Controller                              | 2         | 0.8%    |
| Nvidia Audio device                                                        | 2         | 0.8%    |
| Intel Comet Lake PCH cAVS                                                  | 2         | 0.8%    |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Kingston            | 16        | 17.78%  |
| SK hynix            | 12        | 13.33%  |
| Samsung Electronics | 12        | 13.33%  |
| Unknown             | 10        | 11.11%  |
| Micron Technology   | 10        | 11.11%  |
| G.Skill             | 7         | 7.78%   |
| Corsair             | 6         | 6.67%   |
| Unknown (ABCD)      | 3         | 3.33%   |
| Unknown             | 3         | 3.33%   |
| Crucial             | 2         | 2.22%   |
| A-DATA Technology   | 2         | 2.22%   |
| Transcend           | 1         | 1.11%   |
| Toshiba             | 1         | 1.11%   |
| TakeMS              | 1         | 1.11%   |
| Smart               | 1         | 1.11%   |
| Qimonda             | 1         | 1.11%   |
| CSX                 | 1         | 1.11%   |
| Avant               | 1         | 1.11%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 3         | 3.13%   |
| Kingston RAM KF3200C16D4/32GX 32GB DIMM DDR4 3933MT/s            | 3         | 3.13%   |
| Unknown                                                          | 3         | 3.13%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 2.08%   |
| Unknown RAM Module 2GB DIMM 1333MT/s                             | 2         | 2.08%   |
| Samsung RAM M471A2K43CB1-CRC 16GB SODIMM DDR4 2667MT/s           | 2         | 2.08%   |
| Micron RAM 4ATS2G64HZ-3G2B1 16GB SODIMM DDR4 3200MT/s            | 2         | 2.08%   |
| Unknown RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.04%   |
| Unknown RAM Module 4GB SODIMM DDR2 800MT/s                       | 1         | 1.04%   |
| Unknown RAM Module 4096MB SODIMM DDR4 2667MT/s                   | 1         | 1.04%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 1         | 1.04%   |
| Unknown RAM Module 2GB SODIMM DDR2 667MT/s                       | 1         | 1.04%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 1.04%   |
| Unknown RAM Module 1GB SODIMM DDR2 667MT/s                       | 1         | 1.04%   |
| Transcend RAM JM3200HSB-16G 16GB SODIMM DDR4 3200MT/s            | 1         | 1.04%   |
| Toshiba RAM 8HTF12864HDY-800G1 1GB SODIMM 1066MT/s               | 1         | 1.04%   |
| Toshiba RAM 64T128020EDL2.5C2 2GB SODIMM 1066MT/s                | 1         | 1.04%   |
| TakeMS RAM Module 2048MB DIMM DDR2 800MT/s                       | 1         | 1.04%   |
| Smart RAM SH564568FH8NWPHSFG 2GB SODIMM DDR3 1333MT/s            | 1         | 1.04%   |
| Smart RAM SH564288FH8NWPHSFR 1024MB SODIMM DDR3 1067MT/s         | 1         | 1.04%   |
| SK hynix RAM Module 8GB Row Of Chips LPDDR3 2133MT/s             | 1         | 1.04%   |
| SK hynix RAM Module 32GB DIMM DDR4 2400MT/s                      | 1         | 1.04%   |
| SK hynix RAM HMT451U6BFR8C-PB 4GB DIMM DDR3 1600MT/s             | 1         | 1.04%   |
| SK hynix RAM HMT451R7AFR8C-RD 4GB DIMM DDR3 1866MT/s             | 1         | 1.04%   |
| SK hynix RAM HMT41GU6BFR8C-PB 8GB DIMM DDR3 1600MT/s             | 1         | 1.04%   |
| SK hynix RAM HMT351S6CFR8C-H9 4GB SODIMM DDR3 1333MT/s           | 1         | 1.04%   |
| SK hynix RAM HMAA1GS6CJR6N-XN 8GB SODIMM DDR4 3200MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA82GU6AFR8N-UH 16GB DIMM DDR4 2400MT/s            | 1         | 1.04%   |
| SK hynix RAM HMA82GR7CJR8N-VK 16GB DIMM DDR4 2666MT/s            | 1         | 1.04%   |
| SK hynix RAM HMA82GR7AFR8N-VK 16GB DIMM DDR4 2666MT/s            | 1         | 1.04%   |
| SK hynix RAM HMA81GS6AFR8N-UH 8GB SODIMM DDR4 2667MT/s           | 1         | 1.04%   |
| SK hynix RAM HMA81GR7AFR8N-VK 8192MB DIMM DDR4 2666MT/s          | 1         | 1.04%   |
| SK hynix RAM HCNNNFAMMLXR-NEE 4GB Row Of Chips LPDDR4 4267MT/s   | 1         | 1.04%   |
| Samsung RAM Module 8GB SODIMM DDR4 3200MT/s                      | 1         | 1.04%   |
| Samsung RAM Module 32GB SODIMM DDR5 4800MT/s                     | 1         | 1.04%   |
| Samsung RAM Module 32GB DIMM DDR4 2400MT/s                       | 1         | 1.04%   |
| Samsung RAM M471B5273DH0-CK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.04%   |
| Samsung RAM M471B5273DH0-CH9 4GB SODIMM DDR3 1334MT/s            | 1         | 1.04%   |
| Samsung RAM M471B5173EB0-YK0 4GB SODIMM DDR3 1600MT/s            | 1         | 1.04%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR4    | 42        | 53.85%  |
| DDR3    | 15        | 19.23%  |
| DDR2    | 6         | 7.69%   |
| LPDDR4  | 5         | 6.41%   |
| Unknown | 5         | 6.41%   |
| DDR5    | 2         | 2.56%   |
| SDRAM   | 1         | 1.28%   |
| LPDDR3  | 1         | 1.28%   |
| DDR     | 1         | 1.28%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 38        | 47.5%   |
| DIMM         | 37        | 46.25%  |
| Row Of Chips | 5         | 6.25%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 8192  | 27        | 31.76%  |
| 16384 | 20        | 23.53%  |
| 4096  | 18        | 21.18%  |
| 32768 | 8         | 9.41%   |
| 2048  | 8         | 9.41%   |
| 1024  | 4         | 4.71%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed | Computers | Percent |
|-------|-----------|---------|
| 3200  | 17        | 20.24%  |
| 2667  | 10        | 11.9%   |
| 1600  | 10        | 11.9%   |
| 2400  | 9         | 10.71%  |
| 1333  | 7         | 8.33%   |
| 2133  | 6         | 7.14%   |
| 3933  | 3         | 3.57%   |
| 3600  | 3         | 3.57%   |
| 800   | 3         | 3.57%   |
| 4800  | 2         | 2.38%   |
| 4267  | 2         | 2.38%   |
| 2666  | 2         | 2.38%   |
| 1334  | 2         | 2.38%   |
| 667   | 2         | 2.38%   |
| 8400  | 1         | 1.19%   |
| 3000  | 1         | 1.19%   |
| 2048  | 1         | 1.19%   |
| 1866  | 1         | 1.19%   |
| 1066  | 1         | 1.19%   |
| 533   | 1         | 1.19%   |

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
| Seiko Epson    | 2         | 66.67%  |
| Mustek Systems | 1         | 33.33%  |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                                                         | Computers | Percent |
|---------------------------------------------------------------|-----------|---------|
| Seiko Epson GT-F730 [GT-S630/Perfection V33/V330 Photo]       | 1         | 33.33%  |
| Seiko Epson GT-8700/GT-8700F [Perfection 1640SU/1640SU PHOTO] | 1         | 33.33%  |
| Mustek Systems ScanExpress A3 USB                             | 1         | 33.33%  |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 18        | 21.43%  |
| Sunplus Innovation Technology          | 7         | 8.33%   |
| Microdia                               | 7         | 8.33%   |
| Logitech                               | 7         | 8.33%   |
| Bison Electronics                      | 5         | 5.95%   |
| Syntek                                 | 4         | 4.76%   |
| Quanta                                 | 4         | 4.76%   |
| Luxvisions Innotech Limited            | 4         | 4.76%   |
| Alcor Micro                            | 4         | 4.76%   |
| Lite-On Technology                     | 3         | 3.57%   |
| IMC Networks                           | 3         | 3.57%   |
| Realtek Semiconductor                  | 2         | 2.38%   |
| HDR webcam                             | 2         | 2.38%   |
| Generalplus Technology                 | 2         | 2.38%   |
| Cheng Uei Precision Industry (Foxlink) | 2         | 2.38%   |
| Acer                                   | 2         | 2.38%   |
| vivo                                   | 1         | 1.19%   |
| Suyin                                  | 1         | 1.19%   |
| Microsoft                              | 1         | 1.19%   |
| Lenovo                                 | 1         | 1.19%   |
| kingcome                               | 1         | 1.19%   |
| Huawei Technologies                    | 1         | 1.19%   |
| eMeet                                  | 1         | 1.19%   |
| ARC International                      | 1         | 1.19%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                            | 4         | 4.76%   |
| Microdia Integrated_Webcam_HD                        | 3         | 3.57%   |
| Alcor Micro USB 2.0 Camera                           | 3         | 3.57%   |
| Syntek Integrated Camera                             | 2         | 2.38%   |
| Sunplus Integrated_Webcam_HD                         | 2         | 2.38%   |
| Sunplus HD WebCam                                    | 2         | 2.38%   |
| Quanta HP True Vision HD Camera                      | 2         | 2.38%   |
| Logitech HD Webcam C615                              | 2         | 2.38%   |
| HDR webcam HDR webcam                                | 2         | 2.38%   |
| Chicony FJ Camera                                    | 2         | 2.38%   |
| Bison Integrated Camera                              | 2         | 2.38%   |
| vivo V2036                                           | 1         | 1.19%   |
| Syntek Web Cam - Asus F3SA, F9J, F9S                 | 1         | 1.19%   |
| Syntek EasyCamera                                    | 1         | 1.19%   |
| Suyin USB 2.0 Camera                                 | 1         | 1.19%   |
| Sunplus Laptop Integrated Webcam HD                  | 1         | 1.19%   |
| Sunplus HD 720P webcam                               | 1         | 1.19%   |
| Sunplus Dell E5570 integrated webcam                 | 1         | 1.19%   |
| Realtek USB Camera                                   | 1         | 1.19%   |
| Realtek Integrated_Webcam_HD                         | 1         | 1.19%   |
| Quanta HP HD Camera                                  | 1         | 1.19%   |
| Quanta HD User Facing                                | 1         | 1.19%   |
| Microsoft LifeCam VX-700                             | 1         | 1.19%   |
| Microdia Webcam Vitade AF                            | 1         | 1.19%   |
| Microdia USB Camera                                  | 1         | 1.19%   |
| Microdia Integrated Webcam                           | 1         | 1.19%   |
| Microdia Camera                                      | 1         | 1.19%   |
| Luxvisions Innotech Limited Integrated Camera        | 1         | 1.19%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 1.19%   |
| Luxvisions Innotech Limited HP TrueVision HD Camera  | 1         | 1.19%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 1.19%   |
| Logitech Webcam C270                                 | 1         | 1.19%   |
| Logitech Webcam C170                                 | 1         | 1.19%   |
| Logitech HD Pro Webcam C920                          | 1         | 1.19%   |
| Logitech BRIO Ultra HD Webcam                        | 1         | 1.19%   |
| Logitech B525 HD Webcam                              | 1         | 1.19%   |
| Lite-On TOSHIBA Web Camera - HD                      | 1         | 1.19%   |
| Lite-On Integrated Camera                            | 1         | 1.19%   |
| Lite-On HP HD Webcam                                 | 1         | 1.19%   |
| Lenovo Integrated Webcam [R5U877]                    | 1         | 1.19%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor           | Computers | Percent |
|------------------|-----------|---------|
| Validity Sensors | 7         | 38.89%  |
| Synaptics        | 7         | 38.89%  |
| Upek             | 3         | 16.67%  |
| AuthenTec        | 1         | 5.56%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                    | Computers | Percent |
|----------------------------------------------------------|-----------|---------|
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor   | 3         | 16.67%  |
| Synaptics UWP WBDI                                       | 3         | 16.67%  |
| Validity Sensors VFS5011 Fingerprint Reader              | 2         | 11.11%  |
| Synaptics Prometheus MIS Touch Fingerprint Reader        | 2         | 11.11%  |
| Synaptics FS7604 Touch Fingerprint Sensor with PurePrint | 2         | 11.11%  |
| Validity Sensors VFS7500 Touch Fingerprint Sensor        | 1         | 5.56%   |
| Validity Sensors VFS495 Fingerprint Reader               | 1         | 5.56%   |
| Validity Sensors VFS491                                  | 1         | 5.56%   |
| Validity Sensors VFS 5011 fingerprint sensor             | 1         | 5.56%   |
| Validity Sensors Swipe Fingerprint Sensor                | 1         | 5.56%   |
| AuthenTec AES1600                                        | 1         | 5.56%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Alcor Micro           | 5         | 55.56%  |
| Broadcom              | 2         | 22.22%  |
| Lenovo                | 1         | 11.11%  |
| Gemalto (was Gemplus) | 1         | 11.11%  |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                                                        | Computers | Percent |
|------------------------------------------------------------------------------|-----------|---------|
| Alcor Micro AU9540 Smartcard Reader                                          | 5         | 55.56%  |
| Lenovo Integrated Smart Card Reader                                          | 1         | 11.11%  |
| Gemalto (was Gemplus) GemPC Twin SmartCard Reader                            | 1         | 11.11%  |
| Broadcom BCM5880 Secure Applications Processor with fingerprint swipe sensor | 1         | 11.11%  |
| Broadcom 58200                                                               | 1         | 11.11%  |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 91        | 65.47%  |
| 1     | 31        | 22.3%   |
| 2     | 13        | 9.35%   |
| 3     | 3         | 2.16%   |
| 4     | 1         | 0.72%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                     | Computers | Percent |
|--------------------------|-----------|---------|
| Fingerprint reader       | 18        | 27.27%  |
| Net/wireless             | 9         | 13.64%  |
| Graphics card            | 9         | 13.64%  |
| Chipcard                 | 9         | 13.64%  |
| Multimedia controller    | 4         | 6.06%   |
| Camera                   | 4         | 6.06%   |
| Unassigned class         | 3         | 4.55%   |
| Card reader              | 3         | 4.55%   |
| Sound                    | 2         | 3.03%   |
| Network                  | 2         | 3.03%   |
| Communication controller | 2         | 3.03%   |
| Bluetooth                | 1         | 1.52%   |

