Linux in Moldova - Tested Hardware & Statistics
-----------------------------------------------

A project to collect tested hardware configurations for Linux in Moldova.

Anyone can contribute to this report by the [hw-probe](https://github.com/linuxhw/hw-probe) tool:

    sudo -E hw-probe -all -upload

Please contribute! Especially if your hardware is rare.

This is a report for all computer types. See also reports for [desktops](/Location/Moldova/Desktop/README.md) and [notebooks](/Location/Moldova/Notebook/README.md).

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

Total: 258

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
| Google   | Droid                       | Notebook    | [c8e4007ce4](https://linux-hardware.org/?probe=c8e4007ce4) | Oct 26, 2022 |
| Lenovo   | IdeaPad 5 Pro 16ACH6 82L... | Notebook    | [71f188e90c](https://linux-hardware.org/?probe=71f188e90c) | Oct 19, 2022 |
| Intel    | NUC5i3RYB H41000-503        | Mini pc     | [52764efed5](https://linux-hardware.org/?probe=52764efed5) | Oct 12, 2022 |
| Biostar  | TB250-BTC PRO               | Desktop     | [09be95ac2c](https://linux-hardware.org/?probe=09be95ac2c) | Oct 10, 2022 |
| Acer     | Extensa 215-32              | Notebook    | [3e6ce67bb5](https://linux-hardware.org/?probe=3e6ce67bb5) | Oct 08, 2022 |
| Acer     | Extensa 215-32              | Notebook    | [366f0e7930](https://linux-hardware.org/?probe=366f0e7930) | Oct 08, 2022 |
| ASUSTek  | P8H61-M LX2 R2.0            | Desktop     | [0f690e6e12](https://linux-hardware.org/?probe=0f690e6e12) | Oct 08, 2022 |
| ASUSTek  | P8H61-M LX2 R2.0            | Desktop     | [e9bc8b1f10](https://linux-hardware.org/?probe=e9bc8b1f10) | Sep 26, 2022 |
| Acer     | Aspire A315-56              | Notebook    | [644bb082f4](https://linux-hardware.org/?probe=644bb082f4) | Sep 18, 2022 |
| ASUSTek  | VivoBook_ASUSLaptop X509... | Notebook    | [3c214d75b2](https://linux-hardware.org/?probe=3c214d75b2) | Sep 10, 2022 |
| HP       | ProBook 450 G7              | Notebook    | [5fa4bf5fc8](https://linux-hardware.org/?probe=5fa4bf5fc8) | Aug 29, 2022 |
| Lenovo   | Legion 5 Pro 16ITH6H 82J... | Notebook    | [681486095a](https://linux-hardware.org/?probe=681486095a) | Aug 27, 2022 |
| Gigabyte | B550 AORUS ELITE            | Desktop     | [08e3444b3c](https://linux-hardware.org/?probe=08e3444b3c) | Aug 15, 2022 |
| Foxconn  | nT-330i                     | Desktop     | [64504a98ed](https://linux-hardware.org/?probe=64504a98ed) | Aug 04, 2022 |
| Timi     | TM1701                      | Notebook    | [5b62dea22f](https://linux-hardware.org/?probe=5b62dea22f) | Aug 03, 2022 |
| Timi     | TM1701                      | Notebook    | [cddc7cb825](https://linux-hardware.org/?probe=cddc7cb825) | Aug 03, 2022 |
| Lenovo   | ThinkPad X1 Carbon 5th 2... | Notebook    | [d77ac14ae9](https://linux-hardware.org/?probe=d77ac14ae9) | Aug 01, 2022 |
| HP       | EliteBook 820 G3            | Notebook    | [a96c616d62](https://linux-hardware.org/?probe=a96c616d62) | Jul 28, 2022 |
| Dell     | Latitude 5480               | Notebook    | [151c4b8c85](https://linux-hardware.org/?probe=151c4b8c85) | Jul 21, 2022 |
| HP       | ProBook 450 G7              | Notebook    | [e011908e80](https://linux-hardware.org/?probe=e011908e80) | Jul 18, 2022 |
| HP       | ENVY 15                     | Notebook    | [9c0990eedf](https://linux-hardware.org/?probe=9c0990eedf) | Jul 18, 2022 |
| HP       | ProBook 450 G7              | Notebook    | [5d41d810e8](https://linux-hardware.org/?probe=5d41d810e8) | Jul 18, 2022 |
| ASUSTek  | TUF Gaming FX705DT_FX705... | Notebook    | [1d5a0f6177](https://linux-hardware.org/?probe=1d5a0f6177) | Jul 12, 2022 |
| Dell     | 0782GW A01                  | Desktop     | [20cb4c3e27](https://linux-hardware.org/?probe=20cb4c3e27) | Jul 11, 2022 |
| Lenovo   | IdeaPad Gaming 3 15ARH05... | Notebook    | [567077c28d](https://linux-hardware.org/?probe=567077c28d) | Jul 08, 2022 |
| Gigabyte | B450M S2H V2                | Desktop     | [e0e21604de](https://linux-hardware.org/?probe=e0e21604de) | Jun 24, 2022 |
| Lenovo   | IdeaPad L340-15API 81LW     | Notebook    | [dda5fb9c20](https://linux-hardware.org/?probe=dda5fb9c20) | Jun 21, 2022 |
| ASUSTek  | X555LD                      | Notebook    | [d5d6eeb639](https://linux-hardware.org/?probe=d5d6eeb639) | Jun 11, 2022 |
| Lenovo   | Legion 5 15IMH05 82AU       | Notebook    | [cd7bc92bcd](https://linux-hardware.org/?probe=cd7bc92bcd) | Jun 06, 2022 |
| ASUSTek  | PRIME A520M-K               | Desktop     | [72dd09a86a](https://linux-hardware.org/?probe=72dd09a86a) | Jun 05, 2022 |
| Lenovo   | IdeaPad 100-15IBY 80MJ      | Notebook    | [db944454c8](https://linux-hardware.org/?probe=db944454c8) | May 23, 2022 |
| Lenovo   | Legion Y530-15ICH 81FV      | Notebook    | [428509b262](https://linux-hardware.org/?probe=428509b262) | May 01, 2022 |
| ASUSTek  | X541NC                      | Notebook    | [d1dc342eb9](https://linux-hardware.org/?probe=d1dc342eb9) | Apr 17, 2022 |
| ASUSTek  | M4A785-M                    | Desktop     | [25526ee77d](https://linux-hardware.org/?probe=25526ee77d) | Apr 17, 2022 |
| ASUSTek  | PRIME B550-PLUS             | Desktop     | [8c88f1c50a](https://linux-hardware.org/?probe=8c88f1c50a) | Apr 12, 2022 |
| Lenovo   | ThinkPad X240 20AL0067RT    | Notebook    | [f246d643b4](https://linux-hardware.org/?probe=f246d643b4) | Feb 26, 2022 |
| Gigabyte | Z690 UD DDR4                | Desktop     | [6c4ff21b02](https://linux-hardware.org/?probe=6c4ff21b02) | Feb 21, 2022 |
| Sony     | VPCEB1J8E                   | Notebook    | [b00a6a15b2](https://linux-hardware.org/?probe=b00a6a15b2) | Feb 20, 2022 |
| ASUSTek  | U32U                        | Notebook    | [f7b7d4d2db](https://linux-hardware.org/?probe=f7b7d4d2db) | Feb 20, 2022 |
| ASUSTek  | U32U                        | Notebook    | [1cb943e596](https://linux-hardware.org/?probe=1cb943e596) | Feb 20, 2022 |
| Acer     | Swift SF314-57              | Notebook    | [de92ca9fec](https://linux-hardware.org/?probe=de92ca9fec) | Feb 05, 2022 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | Notebook    | [4c95ae549f](https://linux-hardware.org/?probe=4c95ae549f) | Jan 21, 2022 |
| HP       | 21F5                        | Desktop     | [ce8e06508d](https://linux-hardware.org/?probe=ce8e06508d) | Jan 16, 2022 |
| HP       | Unknown                     | Notebook    | [1fbb31af8d](https://linux-hardware.org/?probe=1fbb31af8d) | Jan 05, 2022 |
| Jumper   | EZbook                      | Notebook    | [6e9ee100f8](https://linux-hardware.org/?probe=6e9ee100f8) | Dec 22, 2021 |
| HP       | Pavilion Laptop 15-eh1xx... | Notebook    | [ab93ce9eb8](https://linux-hardware.org/?probe=ab93ce9eb8) | Dec 21, 2021 |
| Jumper   | EZbook                      | Notebook    | [992b2479e4](https://linux-hardware.org/?probe=992b2479e4) | Dec 21, 2021 |
| HP       | EliteBook 8470p             | Notebook    | [8ab831bf5f](https://linux-hardware.org/?probe=8ab831bf5f) | Dec 21, 2021 |
| Biostar  | N68S3+                      | Desktop     | [8812de783f](https://linux-hardware.org/?probe=8812de783f) | Dec 16, 2021 |
| ASUSTek  | A_F_K20CE                   | Desktop     | [926db6c655](https://linux-hardware.org/?probe=926db6c655) | Dec 15, 2021 |
| ASUSTek  | Z97I-PLUS                   | Desktop     | [a379cfa431](https://linux-hardware.org/?probe=a379cfa431) | Dec 12, 2021 |
| Chuwi    | GemiBook Pro                | Notebook    | [493d55cb16](https://linux-hardware.org/?probe=493d55cb16) | Dec 11, 2021 |
| Dell     | Latitude 3520               | Notebook    | [8fb7494494](https://linux-hardware.org/?probe=8fb7494494) | Dec 06, 2021 |
| Gigabyte | H61M-S2-B3                  | Desktop     | [960d7d5035](https://linux-hardware.org/?probe=960d7d5035) | Dec 05, 2021 |
| ASRock   | M3A770DE                    | Desktop     | [b6ee8bc974](https://linux-hardware.org/?probe=b6ee8bc974) | Dec 01, 2021 |
| Gigabyte | H81M-HD3                    | Desktop     | [953c3f9284](https://linux-hardware.org/?probe=953c3f9284) | Nov 13, 2021 |
| Acer     | Aspire 5253G                | Notebook    | [f7c885dedd](https://linux-hardware.org/?probe=f7c885dedd) | Nov 08, 2021 |
| MSI      | MS-7309                     | Desktop     | [0a4d7fb95d](https://linux-hardware.org/?probe=0a4d7fb95d) | Oct 30, 2021 |
| MSI      | A75A-G35                    | Desktop     | [7223bfa184](https://linux-hardware.org/?probe=7223bfa184) | Oct 22, 2021 |
| Toshiba  | Satellite Pro S300L         | Notebook    | [93c5def444](https://linux-hardware.org/?probe=93c5def444) | Oct 06, 2021 |
| ASUSTek  | VivoBook S15 X510UF         | Notebook    | [336bbdae35](https://linux-hardware.org/?probe=336bbdae35) | Oct 02, 2021 |
| Lenovo   | ThinkPad E15 Gen 2 20TD0... | Notebook    | [7820254b55](https://linux-hardware.org/?probe=7820254b55) | Sep 23, 2021 |
| Dell     | Latitude 5591               | Notebook    | [0235ac49c6](https://linux-hardware.org/?probe=0235ac49c6) | Sep 15, 2021 |
| Lenovo   | ThinkPad E15 Gen 3 20YG0... | Notebook    | [02666996c0](https://linux-hardware.org/?probe=02666996c0) | Sep 12, 2021 |
| Lenovo   | ThinkPad E15 Gen 3 20YG0... | Notebook    | [97b45da8a7](https://linux-hardware.org/?probe=97b45da8a7) | Sep 12, 2021 |
| HP       | Laptop 15-da1xxx            | Notebook    | [c6f3848c20](https://linux-hardware.org/?probe=c6f3848c20) | Sep 12, 2021 |
| HP       | Laptop 15-da1xxx            | Notebook    | [b73b5ecab7](https://linux-hardware.org/?probe=b73b5ecab7) | Sep 11, 2021 |
| Lenovo   | Yoga 730-15IKB 81CU         | Convertible | [f0da92a413](https://linux-hardware.org/?probe=f0da92a413) | Aug 25, 2021 |
| Lenovo   | Yoga 730-15IKB 81CU         | Convertible | [c7b0b8b25a](https://linux-hardware.org/?probe=c7b0b8b25a) | Aug 21, 2021 |
| HP       | ProBook 450 G6              | Notebook    | [227d87ab66](https://linux-hardware.org/?probe=227d87ab66) | Aug 20, 2021 |
| Biostar  | N68S3+                      | Desktop     | [1eae78eec0](https://linux-hardware.org/?probe=1eae78eec0) | Aug 04, 2021 |
| Gigabyte | B460M DS3H V2               | Desktop     | [6177f24834](https://linux-hardware.org/?probe=6177f24834) | Aug 02, 2021 |
| Gigabyte | B460M DS3H V2               | Desktop     | [7fa66f2f95](https://linux-hardware.org/?probe=7fa66f2f95) | Aug 02, 2021 |
| Toshiba  | TECRA Z40-B                 | Notebook    | [d353412a4f](https://linux-hardware.org/?probe=d353412a4f) | Jul 29, 2021 |
| Lenovo   | IdeaPad 5 15ARE05 81YQ      | Notebook    | [8430084f74](https://linux-hardware.org/?probe=8430084f74) | Jul 15, 2021 |
| System76 | Adder WS                    | Notebook    | [d128c1d16b](https://linux-hardware.org/?probe=d128c1d16b) | Jul 08, 2021 |
| HP       | ProLiant DL360 G5           | Server      | [e1ec1d09c1](https://linux-hardware.org/?probe=e1ec1d09c1) | Jul 07, 2021 |
| Lenovo   | ThinkPad T440 20B7S1N809    | Notebook    | [b9ab49e917](https://linux-hardware.org/?probe=b9ab49e917) | Jul 07, 2021 |
| Gigabyte | EP43-UD3L                   | Desktop     | [3b6839e225](https://linux-hardware.org/?probe=3b6839e225) | Jul 01, 2021 |
| Dell     | Vostro 5590                 | Notebook    | [1cc0df9bfd](https://linux-hardware.org/?probe=1cc0df9bfd) | Jun 28, 2021 |
| Dell     | Vostro 5590                 | Notebook    | [0caade1304](https://linux-hardware.org/?probe=0caade1304) | Jun 28, 2021 |
| ASUSTek  | X555LJ                      | Notebook    | [aab7280bd9](https://linux-hardware.org/?probe=aab7280bd9) | Jun 20, 2021 |
| Timi     | A35S                        | Notebook    | [226823eb5b](https://linux-hardware.org/?probe=226823eb5b) | Jun 19, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | Notebook    | [79e70ff708](https://linux-hardware.org/?probe=79e70ff708) | Jun 17, 2021 |
| ASUSTek  | TUF Gaming FX705DT_FX705... | Notebook    | [447e508593](https://linux-hardware.org/?probe=447e508593) | Jun 14, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | Notebook    | [47d894d771](https://linux-hardware.org/?probe=47d894d771) | Jun 12, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | Notebook    | [5c14296bc9](https://linux-hardware.org/?probe=5c14296bc9) | Jun 12, 2021 |
| ASUSTek  | VivoBook_ASUSLaptop X521... | Notebook    | [73e1185f6e](https://linux-hardware.org/?probe=73e1185f6e) | Jun 12, 2021 |
| ASUSTek  | F1A75-M LE                  | Desktop     | [b453e98364](https://linux-hardware.org/?probe=b453e98364) | May 21, 2021 |
| ASUSTek  | TUF Gaming FX705DT_FX705... | Notebook    | [666ddeb09c](https://linux-hardware.org/?probe=666ddeb09c) | May 19, 2021 |
| Dell     | Inspiron 3541               | Notebook    | [88d0f731fd](https://linux-hardware.org/?probe=88d0f731fd) | Apr 29, 2021 |
| Dell     | Inspiron 3541               | Notebook    | [4267385ad8](https://linux-hardware.org/?probe=4267385ad8) | Apr 29, 2021 |
| Dell     | Inspiron 3593               | Notebook    | [5facbef10b](https://linux-hardware.org/?probe=5facbef10b) | Apr 24, 2021 |
| Biostar  | A58MD                       | Desktop     | [3effc9a4ed](https://linux-hardware.org/?probe=3effc9a4ed) | Apr 18, 2021 |
| Dell     | Latitude E7440              | Notebook    | [c59d5358b3](https://linux-hardware.org/?probe=c59d5358b3) | Apr 04, 2021 |
| Biostar  | H110MHC                     | Desktop     | [acc13c8156](https://linux-hardware.org/?probe=acc13c8156) | Mar 24, 2021 |
| HP       | Pavilion dv7                | Notebook    | [b7756075fd](https://linux-hardware.org/?probe=b7756075fd) | Mar 15, 2021 |
| Lenovo   | Legion Y530-15ICH 81FV      | Notebook    | [bd5d97f7e7](https://linux-hardware.org/?probe=bd5d97f7e7) | Mar 07, 2021 |
| HP       | ZBook Fury 15 G7 Mobile ... | Notebook    | [c2435842e1](https://linux-hardware.org/?probe=c2435842e1) | Mar 04, 2021 |
| HP       | ZBook Fury 15 G7 Mobile ... | Notebook    | [5cc3d3f3ed](https://linux-hardware.org/?probe=5cc3d3f3ed) | Mar 04, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | Notebook    | [16d0cd0b17](https://linux-hardware.org/?probe=16d0cd0b17) | Mar 04, 2021 |
| Lenovo   | IdeaPad 330-15IKB 81DE      | Notebook    | [7a3239606c](https://linux-hardware.org/?probe=7a3239606c) | Mar 04, 2021 |
| ASUSTek  | P8Z77-V PRO                 | Desktop     | [a3d54dee1b](https://linux-hardware.org/?probe=a3d54dee1b) | Feb 22, 2021 |
| ASUSTek  | P8Z77-V PRO                 | Desktop     | [7f75cd3e14](https://linux-hardware.org/?probe=7f75cd3e14) | Feb 22, 2021 |
| Lenovo   | Legion Y530-15ICH 81FV      | Notebook    | [88bab7f6e7](https://linux-hardware.org/?probe=88bab7f6e7) | Feb 22, 2021 |
| ASUSTek  | PRIME B350-PLUS             | Desktop     | [23ddb098d4](https://linux-hardware.org/?probe=23ddb098d4) | Feb 18, 2021 |
| ASRock   | Z87 Extreme4                | Desktop     | [2fc1d961c0](https://linux-hardware.org/?probe=2fc1d961c0) | Feb 14, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | Notebook    | [454ea43e4a](https://linux-hardware.org/?probe=454ea43e4a) | Feb 11, 2021 |
| HP       | ProBook 650 G2              | Notebook    | [043b7f867b](https://linux-hardware.org/?probe=043b7f867b) | Jan 23, 2021 |
| HP       | Laptop 15-dw0xxx            | Notebook    | [a69f5fa59f](https://linux-hardware.org/?probe=a69f5fa59f) | Jan 17, 2021 |
| Gateway  | NV55S                       | Notebook    | [8ed7215a68](https://linux-hardware.org/?probe=8ed7215a68) | Jan 17, 2021 |
| ASUSTek  | B85M-E                      | Desktop     | [024b12b22d](https://linux-hardware.org/?probe=024b12b22d) | Jan 17, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | Notebook    | [a2da0e78db](https://linux-hardware.org/?probe=a2da0e78db) | Jan 14, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | Notebook    | [84f50057c5](https://linux-hardware.org/?probe=84f50057c5) | Jan 14, 2021 |
| ASUSTek  | ZenBook UX333FA_UX333FA     | Notebook    | [c3b5acb8ff](https://linux-hardware.org/?probe=c3b5acb8ff) | Jan 14, 2021 |
| Gateway  | NV55S                       | Notebook    | [149e658abf](https://linux-hardware.org/?probe=149e658abf) | Jan 10, 2021 |
| HP       | EliteBook 855 G7 Noteboo... | Notebook    | [9f70a6e397](https://linux-hardware.org/?probe=9f70a6e397) | Jan 06, 2021 |
| HP       | Pavilion 17                 | Notebook    | [ac1360247b](https://linux-hardware.org/?probe=ac1360247b) | Dec 22, 2020 |
| HP       | EliteBook 855 G7 Noteboo... | Notebook    | [049fa926a1](https://linux-hardware.org/?probe=049fa926a1) | Dec 21, 2020 |
| Gigabyte | GA-970A-DS3                 | Desktop     | [f333aed432](https://linux-hardware.org/?probe=f333aed432) | Dec 04, 2020 |
| Gigabyte | X570 AORUS ULTRA            | Desktop     | [bdc9ccf5d5](https://linux-hardware.org/?probe=bdc9ccf5d5) | Nov 23, 2020 |
| HP       | EliteBook 855 G7 Noteboo... | Notebook    | [69e21f1387](https://linux-hardware.org/?probe=69e21f1387) | Nov 09, 2020 |
| Lenovo   | ThinkPad Yoga 11e 3rd Ge... | Notebook    | [bc1158d1d3](https://linux-hardware.org/?probe=bc1158d1d3) | Nov 09, 2020 |
| HP       | EliteBook 855 G7 Noteboo... | Notebook    | [8725886c61](https://linux-hardware.org/?probe=8725886c61) | Nov 06, 2020 |
| Dell     | Inspiron N5110              | Notebook    | [ee5fa15c46](https://linux-hardware.org/?probe=ee5fa15c46) | Nov 06, 2020 |
| ASUSTek  | Strix 17 GL703GE            | Notebook    | [6e4daa0a3c](https://linux-hardware.org/?probe=6e4daa0a3c) | Nov 05, 2020 |
| ASUSTek  | Strix 17 GL703GE            | Notebook    | [3a9f43c320](https://linux-hardware.org/?probe=3a9f43c320) | Nov 04, 2020 |
| HUAWEI   | NBLK-WAX9X                  | Notebook    | [4088a13026](https://linux-hardware.org/?probe=4088a13026) | Oct 09, 2020 |
| Biostar  | A960D+V3                    | Desktop     | [86864a3f9a](https://linux-hardware.org/?probe=86864a3f9a) | Oct 01, 2020 |
| Biostar  | A960D+V3                    | Desktop     | [781ac4ebab](https://linux-hardware.org/?probe=781ac4ebab) | Sep 30, 2020 |
| Gigabyte | P41-ES3G                    | Desktop     | [30feb0323e](https://linux-hardware.org/?probe=30feb0323e) | Sep 29, 2020 |
| Gigabyte | P41-ES3G                    | Desktop     | [395e492e72](https://linux-hardware.org/?probe=395e492e72) | Sep 29, 2020 |
| ASUSTek  | X200MA                      | Notebook    | [794220eee6](https://linux-hardware.org/?probe=794220eee6) | Sep 26, 2020 |
| Lenovo   | G710 20252                  | Notebook    | [c166b56839](https://linux-hardware.org/?probe=c166b56839) | Aug 26, 2020 |
| ASUSTek  | P8H61-MX                    | Desktop     | [46cff277d4](https://linux-hardware.org/?probe=46cff277d4) | Aug 16, 2020 |
| ASUSTek  | M2N-SLI DELUXE              | Desktop     | [02ab999339](https://linux-hardware.org/?probe=02ab999339) | Aug 04, 2020 |
| ASUSTek  | X541NA                      | Notebook    | [3f4978f463](https://linux-hardware.org/?probe=3f4978f463) | Aug 03, 2020 |
| HP       | ProBook 6465b               | Notebook    | [378cd77f66](https://linux-hardware.org/?probe=378cd77f66) | Jul 26, 2020 |
| ASRock   | A320M-HDV R4.0              | Desktop     | [0320a45205](https://linux-hardware.org/?probe=0320a45205) | Jul 25, 2020 |
| ASUSTek  | VivoBook S15 X510UF         | Notebook    | [66a180cdab](https://linux-hardware.org/?probe=66a180cdab) | Jul 24, 2020 |
| ASUSTek  | VivoBook S15 X510UF         | Notebook    | [ed25557a01](https://linux-hardware.org/?probe=ed25557a01) | Jul 20, 2020 |
| HP       | Compaq Presario CQ60        | Notebook    | [8d24316f6b](https://linux-hardware.org/?probe=8d24316f6b) | Jul 15, 2020 |
| HP       | ProBook 450 G7              | Notebook    | [3638848f89](https://linux-hardware.org/?probe=3638848f89) | Jun 24, 2020 |
| Dell     | XPS 15 9570                 | Notebook    | [c14028664d](https://linux-hardware.org/?probe=c14028664d) | Jun 23, 2020 |
| ASUSTek  | X541NA                      | Notebook    | [6d3495ee91](https://linux-hardware.org/?probe=6d3495ee91) | Jun 14, 2020 |
| HP       | ProBook 470 G2              | Notebook    | [bce3965ebb](https://linux-hardware.org/?probe=bce3965ebb) | Jun 13, 2020 |
| ASUSTek  | M4A785TD-V EVO              | Desktop     | [734d413d2f](https://linux-hardware.org/?probe=734d413d2f) | May 25, 2020 |
| ASUSTek  | M4A785TD-V EVO              | Desktop     | [a5f24237a6](https://linux-hardware.org/?probe=a5f24237a6) | May 22, 2020 |
| ASUSTek  | P8B75-M LE                  | Desktop     | [3051982d33](https://linux-hardware.org/?probe=3051982d33) | Apr 28, 2020 |
| ASUSTek  | P8B75-M LE                  | Desktop     | [6e3a1017c8](https://linux-hardware.org/?probe=6e3a1017c8) | Apr 28, 2020 |
| Lenovo   | IdeaPad 130-15IKB 81H7      | Notebook    | [54b25b6a82](https://linux-hardware.org/?probe=54b25b6a82) | Apr 18, 2020 |
| HP       | EliteBook 850 G6            | Notebook    | [92d96a7e87](https://linux-hardware.org/?probe=92d96a7e87) | Apr 11, 2020 |
| Acer     | Aspire C22-820              | All in one  | [3075b9fbfc](https://linux-hardware.org/?probe=3075b9fbfc) | Apr 07, 2020 |
| ASUSTek  | H110M-K                     | Desktop     | [d65e7d1bb6](https://linux-hardware.org/?probe=d65e7d1bb6) | Mar 28, 2020 |
| ASUSTek  | F1A75-M LE                  | Desktop     | [3cee091303](https://linux-hardware.org/?probe=3cee091303) | Mar 25, 2020 |
| Acer     | Aspire C22-820              | All in one  | [cfac371a18](https://linux-hardware.org/?probe=cfac371a18) | Mar 24, 2020 |
| Acer     | Aspire C22-820              | All in one  | [b283f093f1](https://linux-hardware.org/?probe=b283f093f1) | Mar 24, 2020 |
| ASUSTek  | H110M-K                     | Desktop     | [c0aa963f37](https://linux-hardware.org/?probe=c0aa963f37) | Mar 21, 2020 |
| MSI      | 2A9C                        | Desktop     | [cb1789ae00](https://linux-hardware.org/?probe=cb1789ae00) | Mar 18, 2020 |
| Samsung  | RV413/RV513                 | Notebook    | [996451817e](https://linux-hardware.org/?probe=996451817e) | Mar 12, 2020 |
| Lenovo   | IdeaPad 330-15IGM 81D1      | Notebook    | [c0c091dee5](https://linux-hardware.org/?probe=c0c091dee5) | Feb 22, 2020 |
| Lenovo   | IdeaPad 330-15IGM 81D1      | Notebook    | [f1e8d4fb95](https://linux-hardware.org/?probe=f1e8d4fb95) | Feb 22, 2020 |
| ASUSTek  | X541NA                      | Notebook    | [3df0912982](https://linux-hardware.org/?probe=3df0912982) | Feb 15, 2020 |
| Lenovo   | G710 20252                  | Notebook    | [7df7fd3c10](https://linux-hardware.org/?probe=7df7fd3c10) | Feb 15, 2020 |
| Toshiba  | Satellite C55D-A            | Notebook    | [19713fa1aa](https://linux-hardware.org/?probe=19713fa1aa) | Feb 05, 2020 |
| Dell     | Inspiron 3582               | Notebook    | [6916c1087b](https://linux-hardware.org/?probe=6916c1087b) | Jan 21, 2020 |
| Dell     | Inspiron 3582               | Notebook    | [b873ab0117](https://linux-hardware.org/?probe=b873ab0117) | Jan 16, 2020 |
| Dell     | Inspiron 3582               | Notebook    | [cf3745ead4](https://linux-hardware.org/?probe=cf3745ead4) | Jan 16, 2020 |
| ASUSTek  | K54C                        | Notebook    | [42b284e62d](https://linux-hardware.org/?probe=42b284e62d) | Dec 17, 2019 |
| ASUSTek  | X542UR                      | Notebook    | [8c29a78852](https://linux-hardware.org/?probe=8c29a78852) | Dec 15, 2019 |
| ASUSTek  | M5A78L-M LX                 | Desktop     | [90f55c011b](https://linux-hardware.org/?probe=90f55c011b) | Dec 04, 2019 |
| ASUSTek  | X542UR                      | Notebook    | [106dcde5e2](https://linux-hardware.org/?probe=106dcde5e2) | Oct 24, 2019 |
| ASUSTek  | P5QL/EPU                    | Desktop     | [8f31c009af](https://linux-hardware.org/?probe=8f31c009af) | Oct 20, 2019 |
| ASUSTek  | X542UR                      | Notebook    | [d5d9fe7ed0](https://linux-hardware.org/?probe=d5d9fe7ed0) | Oct 15, 2019 |
| ASUSTek  | X542UR                      | Notebook    | [f0e44b13bf](https://linux-hardware.org/?probe=f0e44b13bf) | Sep 15, 2019 |
| ASUSTek  | X541SA                      | Notebook    | [f4ec1608f1](https://linux-hardware.org/?probe=f4ec1608f1) | Aug 19, 2019 |
| Samsung  | RV413/RV513                 | Notebook    | [a569d1638b](https://linux-hardware.org/?probe=a569d1638b) | Aug 16, 2019 |
| ASUSTek  | F1A75-M LE                  | Desktop     | [bdb727808f](https://linux-hardware.org/?probe=bdb727808f) | Jul 26, 2019 |
| ASUSTek  | F1A75-M LE                  | Desktop     | [961de73328](https://linux-hardware.org/?probe=961de73328) | Jul 26, 2019 |
| HP       | Compaq 6910p                | Notebook    | [2b9b5142af](https://linux-hardware.org/?probe=2b9b5142af) | Jul 02, 2019 |
| Dell     | Inspiron 3521               | Notebook    | [5129fbc2b3](https://linux-hardware.org/?probe=5129fbc2b3) | Jun 13, 2019 |
| Dell     | Inspiron 3521               | Notebook    | [de72a9023b](https://linux-hardware.org/?probe=de72a9023b) | Jun 12, 2019 |
| Acer     | Aspire C24-865              | All in one  | [2288828f06](https://linux-hardware.org/?probe=2288828f06) | Jun 11, 2019 |
| Timi     | TM1701                      | Notebook    | [b2b217c7ba](https://linux-hardware.org/?probe=b2b217c7ba) | Jun 04, 2019 |
| Lenovo   | IdeaPad 330S-14IKB 81F4     | Notebook    | [1df14b9671](https://linux-hardware.org/?probe=1df14b9671) | May 31, 2019 |
| Acer     | Aspire E1-572G              | Notebook    | [d7c9cc59b9](https://linux-hardware.org/?probe=d7c9cc59b9) | May 17, 2019 |
| ASUSTek  | X550JX                      | Notebook    | [a268d267b1](https://linux-hardware.org/?probe=a268d267b1) | May 14, 2019 |
| Toshiba  | Satellite A210              | Notebook    | [b08d78a7fe](https://linux-hardware.org/?probe=b08d78a7fe) | May 12, 2019 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | Notebook    | [adff6b4ec1](https://linux-hardware.org/?probe=adff6b4ec1) | May 08, 2019 |
| ASUSTek  | VivoBook 15_ASUS Laptop ... | Notebook    | [1427bdb593](https://linux-hardware.org/?probe=1427bdb593) | May 08, 2019 |
| Biostar  | GF8100 M2+ SE               | Desktop     | [52b394c153](https://linux-hardware.org/?probe=52b394c153) | May 05, 2019 |
| ASUSTek  | P5P43TD                     | Desktop     | [bbfc5c83ed](https://linux-hardware.org/?probe=bbfc5c83ed) | Apr 23, 2019 |
| ASUSTek  | P5P43TD                     | Desktop     | [a1df618ae9](https://linux-hardware.org/?probe=a1df618ae9) | Apr 18, 2019 |
| Gigabyte | G41M-ES2L                   | Desktop     | [62f911ea35](https://linux-hardware.org/?probe=62f911ea35) | Apr 09, 2019 |
| HP       | Compaq Presario CQ60        | Notebook    | [c4ee62ecc8](https://linux-hardware.org/?probe=c4ee62ecc8) | Mar 21, 2019 |
| HP       | 82A1                        | Desktop     | [f04f3b1720](https://linux-hardware.org/?probe=f04f3b1720) | Mar 18, 2019 |
| Acer     | Aspire A515-51G             | Notebook    | [bc2c6a0308](https://linux-hardware.org/?probe=bc2c6a0308) | Jan 21, 2019 |
| Acer     | Aspire A515-51G             | Notebook    | [a4fa6be429](https://linux-hardware.org/?probe=a4fa6be429) | Jan 21, 2019 |
| Samsung  | 300E4C/300E5C/300E7C        | Notebook    | [761e996b51](https://linux-hardware.org/?probe=761e996b51) | Jan 13, 2019 |
| HP       | 635                         | Notebook    | [26ac239a00](https://linux-hardware.org/?probe=26ac239a00) | Jan 13, 2019 |
| HP       | 635                         | Notebook    | [88b6088e86](https://linux-hardware.org/?probe=88b6088e86) | Jan 13, 2019 |
| Dell     | Latitude E5420              | Notebook    | [58a37ca1d7](https://linux-hardware.org/?probe=58a37ca1d7) | Jan 08, 2019 |
| ASRock   | B250M Pro4                  | Desktop     | [05dfa7d080](https://linux-hardware.org/?probe=05dfa7d080) | Jan 07, 2019 |
| ASRock   | B250M Pro4                  | Desktop     | [4ca432ffe1](https://linux-hardware.org/?probe=4ca432ffe1) | Jan 03, 2019 |
| HP       | Compaq CQ58                 | Notebook    | [f930811937](https://linux-hardware.org/?probe=f930811937) | Dec 25, 2018 |
| HP       | Compaq CQ58                 | Notebook    | [092addb321](https://linux-hardware.org/?probe=092addb321) | Dec 25, 2018 |
| Samsung  | R517/R717                   | Notebook    | [cf1386553c](https://linux-hardware.org/?probe=cf1386553c) | Dec 11, 2018 |
| HP       | ENVY m6                     | Notebook    | [a2443c2500](https://linux-hardware.org/?probe=a2443c2500) | Nov 28, 2018 |
| Biostar  | NF61D-A2                    | Desktop     | [8920fb5da2](https://linux-hardware.org/?probe=8920fb5da2) | Nov 24, 2018 |
| Lenovo   | ThinkPad X131e 33711T0      | Notebook    | [d765880811](https://linux-hardware.org/?probe=d765880811) | Nov 20, 2018 |
| Gigabyte | H61M-S1                     | Desktop     | [f035a927b4](https://linux-hardware.org/?probe=f035a927b4) | Oct 16, 2018 |
| Gigabyte | H61M-S1                     | Desktop     | [0cb176039a](https://linux-hardware.org/?probe=0cb176039a) | Oct 16, 2018 |
| ASUSTek  | K56CM                       | Notebook    | [9801230a74](https://linux-hardware.org/?probe=9801230a74) | Oct 11, 2018 |
| ASUSTek  | H110M-R                     | Desktop     | [e8cf4914df](https://linux-hardware.org/?probe=e8cf4914df) | Oct 11, 2018 |
| Lenovo   | G710 20252                  | Notebook    | [67b5fc31a6](https://linux-hardware.org/?probe=67b5fc31a6) | Sep 03, 2018 |
| ASUSTek  | TUF X299 MARK 1             | Desktop     | [4ff6f8b306](https://linux-hardware.org/?probe=4ff6f8b306) | Aug 28, 2018 |
| ASUSTek  | H110M-R                     | Desktop     | [856815508e](https://linux-hardware.org/?probe=856815508e) | Jul 20, 2018 |
| ASUSTek  | H110M-R                     | Desktop     | [2c6e982e0a](https://linux-hardware.org/?probe=2c6e982e0a) | Jul 20, 2018 |
| ASUSTek  | K50AB                       | Notebook    | [5309fc98bb](https://linux-hardware.org/?probe=5309fc98bb) | Jun 21, 2018 |
| Lenovo   | Y520-15IKBN 80WK            | Notebook    | [9c2fa220c0](https://linux-hardware.org/?probe=9c2fa220c0) | Jun 07, 2018 |
| Lenovo   | Y520-15IKBN 80WK            | Notebook    | [23cd9fcd79](https://linux-hardware.org/?probe=23cd9fcd79) | Jun 07, 2018 |
| ASRock   | H110M-DGS                   | Desktop     | [2bf308c36a](https://linux-hardware.org/?probe=2bf308c36a) | Apr 22, 2018 |
| Gigabyte | H81M-S2PV                   | Desktop     | [d73e7cdaf7](https://linux-hardware.org/?probe=d73e7cdaf7) | Apr 10, 2018 |
| ASUSTek  | M5A78L LE                   | Desktop     | [324ea287af](https://linux-hardware.org/?probe=324ea287af) | Mar 25, 2018 |
| ASUSTek  | M5A78L LE                   | Desktop     | [c4796ca0ba](https://linux-hardware.org/?probe=c4796ca0ba) | Mar 25, 2018 |
| MSI      | G31M3-L V2                  | Desktop     | [a010b34c1d](https://linux-hardware.org/?probe=a010b34c1d) | Mar 14, 2018 |
| ASUSTek  | K52N                        | Notebook    | [9b6027f7f9](https://linux-hardware.org/?probe=9b6027f7f9) | Mar 04, 2018 |
| Gigabyte | GA-880GM-USB3               | Desktop     | [488c7af7b3](https://linux-hardware.org/?probe=488c7af7b3) | Feb 13, 2018 |
| ASUSTek  | K52N                        | Notebook    | [a31f696968](https://linux-hardware.org/?probe=a31f696968) | Jan 27, 2018 |
| Biostar  | H61MGV3                     | Desktop     | [601f3981af](https://linux-hardware.org/?probe=601f3981af) | Jan 25, 2018 |
| MSI      | G31M3-L V2                  | Desktop     | [cb825d670e](https://linux-hardware.org/?probe=cb825d670e) | Jan 23, 2018 |
| Biostar  | A960G+                      | Desktop     | [1ed969e51e](https://linux-hardware.org/?probe=1ed969e51e) | Jan 02, 2018 |
| ASUSTek  | E502SA                      | Notebook    | [f82780c45f](https://linux-hardware.org/?probe=f82780c45f) | Dec 22, 2017 |
| Samsung  | R517/R717                   | Notebook    | [88501ec4d2](https://linux-hardware.org/?probe=88501ec4d2) | Nov 23, 2017 |
| Acer     | Aspire E5-575               | Notebook    | [d7a774808d](https://linux-hardware.org/?probe=d7a774808d) | Nov 07, 2017 |
| Gigabyte | H81M-S2PV                   | Desktop     | [b4b5168bf0](https://linux-hardware.org/?probe=b4b5168bf0) | Oct 22, 2017 |
| Biostar  | TA790GX 128M                | Desktop     | [13dafc619e](https://linux-hardware.org/?probe=13dafc619e) | Sep 07, 2017 |
| Lenovo   | V580 20147                  | Notebook    | [7b4ec145fd](https://linux-hardware.org/?probe=7b4ec145fd) | Sep 05, 2017 |
| ASUSTek  | E502SA                      | Notebook    | [f80e3a3361](https://linux-hardware.org/?probe=f80e3a3361) | Jul 02, 2017 |
| Acer     | AO756                       | Notebook    | [750d61ea27](https://linux-hardware.org/?probe=750d61ea27) | Jun 28, 2017 |
| ASUSTek  | E502SA                      | Notebook    | [e638970390](https://linux-hardware.org/?probe=e638970390) | Jun 27, 2017 |
| Samsung  | R517/R717                   | Notebook    | [a037b05f1c](https://linux-hardware.org/?probe=a037b05f1c) | Jun 07, 2017 |
| Lenovo   | V580 20147                  | Notebook    | [e4a66b20cf](https://linux-hardware.org/?probe=e4a66b20cf) | May 09, 2017 |
| ASUSTek  | P7P55D-E                    | Desktop     | [7ead295d4f](https://linux-hardware.org/?probe=7ead295d4f) | May 04, 2017 |
| ASUSTek  | P5GPL                       | Desktop     | [dc412a96d7](https://linux-hardware.org/?probe=dc412a96d7) | Mar 11, 2017 |
| ASUSTek  | P5GPL                       | Desktop     | [704d76d7f0](https://linux-hardware.org/?probe=704d76d7f0) | Mar 11, 2017 |
| HP       | 550                         | Notebook    | [21d69ed69f](https://linux-hardware.org/?probe=21d69ed69f) | Feb 14, 2017 |
| ECS      | GeForce7050M-M              | Desktop     | [dffec0e1ef](https://linux-hardware.org/?probe=dffec0e1ef) | Jan 26, 2017 |
| MSI      | G41M-P26                    | Desktop     | [3a93859874](https://linux-hardware.org/?probe=3a93859874) | Jan 21, 2017 |
| Dell     | 0HJ054                      | Desktop     | [3a64a2e7cc](https://linux-hardware.org/?probe=3a64a2e7cc) | Jan 14, 2017 |
| ASUSTek  | M5A78L-M LX3                | Desktop     | [de5986b48c](https://linux-hardware.org/?probe=de5986b48c) | Dec 27, 2016 |
| Acer     | Aspire E1-531G              | Notebook    | [0481735487](https://linux-hardware.org/?probe=0481735487) | Dec 19, 2016 |
| ASUSTek  | P8H61-M LX3                 | Desktop     | [51108b9a7b](https://linux-hardware.org/?probe=51108b9a7b) | Nov 26, 2016 |
| ASUSTek  | A88X-PLUS                   | Desktop     | [e5165dfe31](https://linux-hardware.org/?probe=e5165dfe31) | Nov 25, 2016 |
| ASUSTek  | A88X-PLUS                   | Desktop     | [53f70342b5](https://linux-hardware.org/?probe=53f70342b5) | Nov 23, 2016 |
| MSI      | CR610                       | Notebook    | [fa269a3f05](https://linux-hardware.org/?probe=fa269a3f05) | Nov 20, 2016 |
| ASUSTek  | P5KPL-AM IN/ROEM/SI         | Desktop     | [c140d93dd9](https://linux-hardware.org/?probe=c140d93dd9) | Nov 08, 2016 |
| ECS      | GeForce7050M-M              | Desktop     | [3f276c748c](https://linux-hardware.org/?probe=3f276c748c) | Nov 04, 2016 |

System
------

OS
--

Installed operating systems

![OS](./All/images/pie_chart/os_name.svg)


| Name              | Computers | Percent |
|-------------------|-----------|---------|
| ROSA R10          | 21        | 10.82%  |
| Ubuntu 20.04      | 15        | 7.73%   |
| Ubuntu 18.04      | 15        | 7.73%   |
| ROSA R11          | 14        | 7.22%   |
| ROSA R8           | 10        | 5.15%   |
| ROSA R11.1        | 9         | 4.64%   |
| ROSA R8.1         | 8         | 4.12%   |
| OpenMandriva 4.2  | 6         | 3.09%   |
| Linux Mint 20.1   | 5         | 2.58%   |
| KDE neon 20.04    | 5         | 2.58%   |
| Ubuntu 22.04      | 4         | 2.06%   |
| ROSA R9           | 4         | 2.06%   |
| ROSA 12.2         | 4         | 2.06%   |
| Manjaro           | 4         | 2.06%   |
| Arch              | 4         | 2.06%   |
| OpenMandriva 4.3  | 3         | 1.55%   |
| Linux Mint 19.1   | 3         | 1.55%   |
| Fedora 36         | 3         | 1.55%   |
| Fedora 34         | 3         | 1.55%   |
| Zorin 16          | 2         | 1.03%   |
| Ubuntu 19.10      | 2         | 1.03%   |
| Ubuntu 16.04      | 2         | 1.03%   |
| Pop!_OS 21.04     | 2         | 1.03%   |
| Pop!_OS 20.10     | 2         | 1.03%   |
| Linux Mint 20.2   | 2         | 1.03%   |
| Linux Mint 20     | 2         | 1.03%   |
| Linux Mint 19.3   | 2         | 1.03%   |
| BlackPanther 18.1 | 2         | 1.03%   |
| Arch Rolling      | 2         | 1.03%   |
| Ubuntu 22.10      | 1         | 0.52%   |
| Ubuntu 21.10      | 1         | 0.52%   |
| Ubuntu 21.04      | 1         | 0.52%   |
| Ubuntu 19.04      | 1         | 0.52%   |
| SteamOS 3.3       | 1         | 0.52%   |
| ROSA 12.1         | 1         | 0.52%   |
| Pop!_OS 21.10     | 1         | 0.52%   |
| Pop!_OS 20.04     | 1         | 0.52%   |
| OpenMandriva 4.50 | 1         | 0.52%   |
| Manjaro 22.0.0    | 1         | 0.52%   |
| Manjaro 21.3.0    | 1         | 0.52%   |

OS Family
---------

OS without a version

![OS Family](./All/images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| ROSA         | 66        | 35.29%  |
| Ubuntu       | 42        | 22.46%  |
| Linux Mint   | 15        | 8.02%   |
| OpenMandriva | 10        | 5.35%   |
| Manjaro      | 10        | 5.35%   |
| Fedora       | 10        | 5.35%   |
| Pop!_OS      | 6         | 3.21%   |
| Arch         | 6         | 3.21%   |
| KDE neon     | 5         | 2.67%   |
| Endless      | 4         | 2.14%   |
| Zorin        | 2         | 1.07%   |
| Kubuntu      | 2         | 1.07%   |
| Kali         | 2         | 1.07%   |
| Debian       | 2         | 1.07%   |
| BlackPanther | 2         | 1.07%   |
| SteamOS      | 1         | 0.53%   |
| Ctlos        | 1         | 0.53%   |
| BuildRoot    | 1         | 0.53%   |

Kernel
------

Version of the Linux kernel

![Kernel](./All/images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64    | 10        | 4.9%    |
| 5.10.14-desktop-1omv4002           | 6         | 2.94%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 6         | 2.94%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 6         | 2.94%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 5         | 2.45%   |
| 5.15.0-41-generic                  | 4         | 1.96%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 4         | 1.96%   |
| 4.9.60-nrj-desktop-1rosa-i586      | 4         | 1.96%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 4         | 1.96%   |
| 4.15.0-desktop-68.5rosa-x86_64     | 4         | 1.96%   |
| 5.8.0-33-generic                   | 3         | 1.47%   |
| 5.16.7-desktop-1omv4003            | 3         | 1.47%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 0.98%   |
| 5.4.0-48-generic                   | 2         | 0.98%   |
| 5.4.0-37-generic                   | 2         | 0.98%   |
| 5.17.11-generic-2rosa2021.1-x86_64 | 2         | 0.98%   |
| 5.11.0-7614-generic                | 2         | 0.98%   |
| 5.11.0-41-generic                  | 2         | 0.98%   |
| 5.11.0-34-generic                  | 2         | 0.98%   |
| 5.11.0-25-generic                  | 2         | 0.98%   |
| 5.10.2-2-MANJARO                   | 2         | 0.98%   |
| 4.9.95-nrj-desktop-2rosa-x86_64    | 2         | 0.98%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 2         | 0.98%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 2         | 0.98%   |
| 4.15.0-desktop-47.2rosa-x86_64     | 2         | 0.98%   |
| 4.1.34-nrj-desktop-2rosa-i586      | 2         | 0.98%   |
| 4.1.25-nrj-desktop-1rosa-i586      | 2         | 0.98%   |
| 5.9.3-1-MANJARO                    | 1         | 0.49%   |
| 5.9.3-050903-generic               | 1         | 0.49%   |
| 5.8.18-100.fc31.x86_64             | 1         | 0.49%   |
| 5.8.18-1-MANJARO                   | 1         | 0.49%   |
| 5.8.0-7642-generic                 | 1         | 0.49%   |
| 5.8.0-38-generic                   | 1         | 0.49%   |
| 5.8.0-36-generic                   | 1         | 0.49%   |
| 5.8.0-25-lowlatency                | 1         | 0.49%   |
| 5.6.14-desktop-2bP                 | 1         | 0.49%   |
| 5.5.9-zen1-2-zen                   | 1         | 0.49%   |
| 5.4.83-generic-2rosa-x86_64        | 1         | 0.49%   |
| 5.4.49-nrj-desktop-1rosa-x86_64    | 1         | 0.49%   |
| 5.4.32-generic-2rosa-i586          | 1         | 0.49%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./All/images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 26        | 13.07%  |
| 5.4.0   | 17        | 8.54%   |
| 4.9.60  | 13        | 6.53%   |
| 5.11.0  | 12        | 6.03%   |
| 5.8.0   | 7         | 3.52%   |
| 5.15.0  | 7         | 3.52%   |
| 4.1.34  | 7         | 3.52%   |
| 5.10.14 | 6         | 3.02%   |
| 4.9.20  | 6         | 3.02%   |
| 5.3.0   | 5         | 2.51%   |
| 5.13.0  | 4         | 2.01%   |
| 5.10.74 | 4         | 2.01%   |
| 5.0.0   | 4         | 2.01%   |
| 4.9.155 | 4         | 2.01%   |
| 4.18.0  | 4         | 2.01%   |
| 5.4.32  | 3         | 1.51%   |
| 5.16.7  | 3         | 1.51%   |
| 4.9.124 | 3         | 1.51%   |
| 4.1.38  | 3         | 1.51%   |
| 5.9.3   | 2         | 1.01%   |
| 5.8.18  | 2         | 1.01%   |
| 5.18.1  | 2         | 1.01%   |
| 5.17.11 | 2         | 1.01%   |
| 5.10.2  | 2         | 1.01%   |
| 5.10.0  | 2         | 1.01%   |
| 4.9.95  | 2         | 1.01%   |
| 4.9.9   | 2         | 1.01%   |
| 4.9.76  | 2         | 1.01%   |
| 4.9.41  | 2         | 1.01%   |
| 4.10.0  | 2         | 1.01%   |
| 4.1.25  | 2         | 1.01%   |
| 5.6.14  | 1         | 0.5%    |
| 5.5.9   | 1         | 0.5%    |
| 5.4.83  | 1         | 0.5%    |
| 5.4.49  | 1         | 0.5%    |
| 5.2.0   | 1         | 0.5%    |
| 5.19.7  | 1         | 0.5%    |
| 5.19.4  | 1         | 0.5%    |
| 5.19.0  | 1         | 0.5%    |
| 5.18.5  | 1         | 0.5%    |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./All/images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 32        | 16.49%  |
| 4.15    | 26        | 13.4%   |
| 5.4     | 22        | 11.34%  |
| 5.10    | 18        | 9.28%   |
| 5.11    | 13        | 6.7%    |
| 5.15    | 12        | 6.19%   |
| 4.1     | 12        | 6.19%   |
| 5.8     | 9         | 4.64%   |
| 5.3     | 5         | 2.58%   |
| 5.18    | 5         | 2.58%   |
| 5.16    | 5         | 2.58%   |
| 5.13    | 5         | 2.58%   |
| 5.0     | 5         | 2.58%   |
| 5.17    | 4         | 2.06%   |
| 4.18    | 4         | 2.06%   |
| 5.19    | 3         | 1.55%   |
| 5.9     | 2         | 1.03%   |
| 5.14    | 2         | 1.03%   |
| 5.12    | 2         | 1.03%   |
| 4.10    | 2         | 1.03%   |
| 5.6     | 1         | 0.52%   |
| 5.5     | 1         | 0.52%   |
| 5.2     | 1         | 0.52%   |
| 5.1     | 1         | 0.52%   |
| 4.19    | 1         | 0.52%   |
| 4.16    | 1         | 0.52%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./All/images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 172       | 91.49%  |
| i686   | 16        | 8.51%   |

DE
--

Desktop Environment

![DE](./All/images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| GNOME           | 48        | 25.26%  |
| KDE4            | 46        | 24.21%  |
| KDE5            | 45        | 23.68%  |
| Unknown         | 17        | 8.95%   |
| X-Cinnamon      | 11        | 5.79%   |
| XFCE            | 7         | 3.68%   |
| MATE            | 3         | 1.58%   |
| LXQt            | 3         | 1.58%   |
| KDE             | 3         | 1.58%   |
| sway            | 2         | 1.05%   |
| GNOME Flashback | 2         | 1.05%   |
| Cinnamon        | 2         | 1.05%   |
| xinitrc         | 1         | 0.53%   |

Display Server
--------------

X11 or Wayland

![Display Server](./All/images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 152       | 80.85%  |
| Wayland | 23        | 12.23%  |
| Unknown | 13        | 6.91%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./All/images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 61        | 31.94%  |
| KDM     | 46        | 24.08%  |
| SDDM    | 42        | 21.99%  |
| GDM     | 21        | 10.99%  |
| TDM     | 8         | 4.19%   |
| GDM3    | 7         | 3.66%   |
| LightDM | 6         | 3.14%   |

OS Lang
-------

Language

![OS Lang](./All/images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 39.15%  |
| en_US   | 51        | 26.98%  |
| ru_RU   | 42        | 22.22%  |
| ro_RO   | 9         | 4.76%   |
| en_GB   | 4         | 2.12%   |
| C       | 4         | 2.12%   |
| ru_UA   | 2         | 1.06%   |
| nl_NL   | 1         | 0.53%   |
| en_150  | 1         | 0.53%   |
| de_DE   | 1         | 0.53%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./All/images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 111       | 59.04%  |
| EFI  | 77        | 40.96%  |

Filesystem
----------

Type of filesystem

![Filesystem](./All/images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 126       | 67.38%  |
| Unknown | 37        | 19.79%  |
| Overlay | 12        | 6.42%   |
| Btrfs   | 10        | 5.35%   |
| Xfs     | 2         | 1.07%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./All/images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 73        | 38.22%  |
| MBR     | 63        | 32.98%  |
| GPT     | 55        | 28.8%   |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./All/images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 166       | 88.3%   |
| Yes       | 22        | 11.7%   |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./All/images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 134       | 71.28%  |
| Yes       | 54        | 28.72%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./All/images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 52        | 27.96%  |
| Hewlett-Packard     | 28        | 15.05%  |
| Lenovo              | 25        | 13.44%  |
| Gigabyte Technology | 14        | 7.53%   |
| Dell                | 14        | 7.53%   |
| Acer                | 11        | 5.91%   |
| Biostar             | 10        | 5.38%   |
| MSI                 | 6         | 3.23%   |
| ASRock              | 5         | 2.69%   |
| Toshiba             | 4         | 2.15%   |
| Samsung Electronics | 4         | 2.15%   |
| Timi                | 3         | 1.61%   |
| System76            | 1         | 0.54%   |
| Sony                | 1         | 0.54%   |
| Jumper              | 1         | 0.54%   |
| Intel               | 1         | 0.54%   |
| HUAWEI              | 1         | 0.54%   |
| Google              | 1         | 0.54%   |
| Gateway             | 1         | 0.54%   |
| Foxconn             | 1         | 0.54%   |
| ECS                 | 1         | 0.54%   |
| Chuwi               | 1         | 0.54%   |

Model
-----

Motherboard model

![Model](./All/images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop X521IA_D533IA      | 3         | 1.61%   |
| Timi TM1701                                 | 2         | 1.08%   |
| Samsung RV413/RV513                         | 2         | 1.08%   |
| Lenovo Legion Y530-15ICH 81FV               | 2         | 1.08%   |
| HP ProBook 450 G7                           | 2         | 1.08%   |
| HP Compaq Presario CQ60                     | 2         | 1.08%   |
| ASUS VivoBook S15 X510UF                    | 2         | 1.08%   |
| ASUS H110M-R                                | 2         | 1.08%   |
| ASUS All Series                             | 2         | 1.08%   |
| Toshiba TECRA Z40-B                         | 1         | 0.54%   |
| Toshiba Satellite Pro S300L                 | 1         | 0.54%   |
| Toshiba Satellite C55D-A                    | 1         | 0.54%   |
| Toshiba Satellite A210                      | 1         | 0.54%   |
| Timi A35S                                   | 1         | 0.54%   |
| System76 Adder WS                           | 1         | 0.54%   |
| Sony VPCEB1J8E                              | 1         | 0.54%   |
| Samsung R517/R717                           | 1         | 0.54%   |
| Samsung 300E4C/300E5C/300E7C                | 1         | 0.54%   |
| MSI Pro 3130 Microtower PC                  | 1         | 0.54%   |
| MSI MS-7695                                 | 1         | 0.54%   |
| MSI MS-7592                                 | 1         | 0.54%   |
| MSI MS-7529                                 | 1         | 0.54%   |
| MSI MS-7309                                 | 1         | 0.54%   |
| MSI CR610                                   | 1         | 0.54%   |
| Lenovo Yoga 730-15IKB 81CU                  | 1         | 0.54%   |
| Lenovo Y520-15IKBN 80WK                     | 1         | 0.54%   |
| Lenovo V580 20147                           | 1         | 0.54%   |
| Lenovo ThinkPad Yoga 11e 3rd Gen 20G8S0MG00 | 1         | 0.54%   |
| Lenovo ThinkPad X240 20AL0067RT             | 1         | 0.54%   |
| Lenovo ThinkPad X131e 33711T0               | 1         | 0.54%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002MMX    | 1         | 0.54%   |
| Lenovo ThinkPad T440 20B7S1N809             | 1         | 0.54%   |
| Lenovo ThinkPad E15 Gen 3 20YG004BRT        | 1         | 0.54%   |
| Lenovo ThinkPad E15 Gen 2 20TD003TRT        | 1         | 0.54%   |
| Lenovo ThinkPad E15 Gen 2 20TD002NRA        | 1         | 0.54%   |
| Lenovo Legion 5 Pro 16ITH6H 82JD            | 1         | 0.54%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 0.54%   |
| Lenovo IdeaPad L340-15API 81LW              | 1         | 0.54%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 0.54%   |
| Lenovo IdeaPad 5 Pro 16ACH6 82L5            | 1         | 0.54%   |

Model Family
------------

Motherboard model prefix

![Model Family](./All/images/pie_chart/node_model_family.svg)


| Name               | Computers | Percent |
|--------------------|-----------|---------|
| Lenovo IdeaPad     | 9         | 4.84%   |
| Lenovo ThinkPad    | 8         | 4.3%    |
| Acer Aspire        | 8         | 4.3%    |
| ASUS VivoBook      | 7         | 3.76%   |
| HP ProBook         | 6         | 3.23%   |
| Dell Latitude      | 5         | 2.69%   |
| Dell Inspiron      | 5         | 2.69%   |
| Lenovo Legion      | 4         | 2.15%   |
| HP EliteBook       | 4         | 2.15%   |
| HP Compaq          | 4         | 2.15%   |
| Toshiba Satellite  | 3         | 1.61%   |
| HP Pavilion        | 3         | 1.61%   |
| ASUS PRIME         | 3         | 1.61%   |
| Timi TM1701        | 2         | 1.08%   |
| Samsung RV413      | 2         | 1.08%   |
| HP ProDesk         | 2         | 1.08%   |
| HP Laptop          | 2         | 1.08%   |
| HP ENVY            | 2         | 1.08%   |
| ASUS TUF           | 2         | 1.08%   |
| ASUS P8H61-M       | 2         | 1.08%   |
| ASUS M5A78L-M      | 2         | 1.08%   |
| ASUS H110M-R       | 2         | 1.08%   |
| ASUS All           | 2         | 1.08%   |
| Toshiba TECRA      | 1         | 0.54%   |
| Timi A35S          | 1         | 0.54%   |
| System76 Adder     | 1         | 0.54%   |
| Sony VPCEB1J8E     | 1         | 0.54%   |
| Samsung R517       | 1         | 0.54%   |
| Samsung 300E4C     | 1         | 0.54%   |
| MSI Pro            | 1         | 0.54%   |
| MSI MS-7695        | 1         | 0.54%   |
| MSI MS-7592        | 1         | 0.54%   |
| MSI MS-7529        | 1         | 0.54%   |
| MSI MS-7309        | 1         | 0.54%   |
| MSI CR610          | 1         | 0.54%   |
| Lenovo Yoga        | 1         | 0.54%   |
| Lenovo Y520-15IKBN | 1         | 0.54%   |
| Lenovo V580        | 1         | 0.54%   |
| Lenovo G710        | 1         | 0.54%   |
| Jumper EZbook      | 1         | 0.54%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./All/images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 18        | 9.68%   |
| 2011 | 18        | 9.68%   |
| 2017 | 17        | 9.14%   |
| 2012 | 17        | 9.14%   |
| 2019 | 16        | 8.6%    |
| 2009 | 15        | 8.06%   |
| 2021 | 13        | 6.99%   |
| 2013 | 13        | 6.99%   |
| 2020 | 12        | 6.45%   |
| 2016 | 11        | 5.91%   |
| 2010 | 9         | 4.84%   |
| 2015 | 7         | 3.76%   |
| 2014 | 5         | 2.69%   |
| 2008 | 5         | 2.69%   |
| 2007 | 4         | 2.15%   |
| 2006 | 3         | 1.61%   |
| 2022 | 2         | 1.08%   |
| 2005 | 1         | 0.54%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./All/images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 113       | 60.75%  |
| Desktop     | 68        | 36.56%  |
| All in one  | 2         | 1.08%   |
| Convertible | 1         | 0.54%   |
| Mini pc     | 1         | 0.54%   |
| Server      | 1         | 0.54%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./All/images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 176       | 94.62%  |
| Enabled  | 10        | 5.38%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./All/images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 185       | 99.46%  |
| Yes  | 1         | 0.54%   |

RAM Size
--------

Total RAM memory

![RAM Size](./All/images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 56        | 29.95%  |
| 4.01-8.0    | 40        | 21.39%  |
| 8.01-16.0   | 36        | 19.25%  |
| 16.01-24.0  | 24        | 12.83%  |
| 32.01-64.0  | 11        | 5.88%   |
| 1.01-2.0    | 10        | 5.35%   |
| 2.01-3.0    | 8         | 4.28%   |
| 64.01-256.0 | 1         | 0.53%   |
| 0.51-1.0    | 1         | 0.53%   |

RAM Used
--------

Used RAM memory

![RAM Used](./All/images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 74        | 37%     |
| 0.51-1.0   | 42        | 21%     |
| 2.01-3.0   | 33        | 16.5%   |
| 4.01-8.0   | 24        | 12%     |
| 3.01-4.0   | 16        | 8%      |
| 8.01-16.0  | 5         | 2.5%    |
| 0.01-0.5   | 3         | 1.5%    |
| 16.01-24.0 | 2         | 1%      |
| 24.01-32.0 | 1         | 0.5%    |

Total Drives
------------

Number of drives on board

![Total Drives](./All/images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 131       | 70.05%  |
| 2      | 38        | 20.32%  |
| 3      | 13        | 6.95%   |
| 4      | 4         | 2.14%   |
| 0      | 1         | 0.53%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./All/images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 119       | 63.98%  |
| Yes       | 67        | 36.02%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./All/images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 167       | 89.3%   |
| No        | 20        | 10.7%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./All/images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 132       | 70.97%  |
| No        | 54        | 29.03%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./All/images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 96        | 51.34%  |
| No        | 91        | 48.66%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./All/images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Moldova | 186       | 100%    |

City
----

Geographic location (city)

![City](./All/images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Chisinau        | 104       | 55.03%  |
| Tiraspol        | 38        | 20.11%  |
| Bălţi         | 6         | 3.17%   |
| Straseni        | 5         | 2.65%   |
| Tighina         | 4         | 2.12%   |
| Hincesti        | 3         | 1.59%   |
| Soroca          | 2         | 1.06%   |
| Ialoveni        | 2         | 1.06%   |
| Căușeni       | 2         | 1.06%   |
| Zaicana         | 1         | 0.53%   |
| Tintareni       | 1         | 0.53%   |
| Soldanesti      | 1         | 0.53%   |
| Sofia           | 1         | 0.53%   |
| Singera         | 1         | 0.53%   |
| Rîbniţa       | 1         | 0.53%   |
| Rezina          | 1         | 0.53%   |
| Rautel          | 1         | 0.53%   |
| Prajila         | 1         | 0.53%   |
| Pociumbeni      | 1         | 0.53%   |
| Lapusna         | 1         | 0.53%   |
| Gangura         | 1         | 0.53%   |
| Floresti        | 1         | 0.53%   |
| Floreni         | 1         | 0.53%   |
| Edineţ         | 1         | 0.53%   |
| Drochia         | 1         | 0.53%   |
| Donduseni       | 1         | 0.53%   |
| Criuleni        | 1         | 0.53%   |
| Crasnoarmeiscoe | 1         | 0.53%   |
| Cojusna         | 1         | 0.53%   |
| Cenac           | 1         | 0.53%   |
| Cazanesti       | 1         | 0.53%   |
| Cahul           | 1         | 0.53%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./All/images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 52        | 63     | 20.55%  |
| WDC                 | 35        | 37     | 13.83%  |
| Seagate             | 33        | 37     | 13.04%  |
| Toshiba             | 27        | 32     | 10.67%  |
| Hitachi             | 17        | 20     | 6.72%   |
| Kingston            | 13        | 16     | 5.14%   |
| SanDisk             | 9         | 9      | 3.56%   |
| SK hynix            | 6         | 6      | 2.37%   |
| Transcend           | 5         | 5      | 1.98%   |
| SPCC                | 5         | 6      | 1.98%   |
| Micron Technology   | 5         | 7      | 1.98%   |
| Unknown             | 4         | 4      | 1.58%   |
| HGST                | 4         | 4      | 1.58%   |
| Apacer              | 4         | 4      | 1.58%   |
| Maxtor              | 3         | 4      | 1.19%   |
| Intel               | 3         | 5      | 1.19%   |
| Phison              | 2         | 3      | 0.79%   |
| GOODRAM             | 2         | 2      | 0.79%   |
| Fujitsu             | 2         | 2      | 0.79%   |
| Crucial             | 2         | 3      | 0.79%   |
| A-DATA Technology   | 2         | 2      | 0.79%   |
| ZOTAC               | 1         | 3      | 0.4%    |
| XPG                 | 1         | 1      | 0.4%    |
| Team                | 1         | 1      | 0.4%    |
| Solid State Storage | 1         | 1      | 0.4%    |
| PNY                 | 1         | 1      | 0.4%    |
| Patriot             | 1         | 1      | 0.4%    |
| OCZ                 | 1         | 1      | 0.4%    |
| Netac               | 1         | 1      | 0.4%    |
| LITEONIT            | 1         | 1      | 0.4%    |
| Leven               | 1         | 1      | 0.4%    |
| Lenovo              | 1         | 1      | 0.4%    |
| KIOXIA              | 1         | 1      | 0.4%    |
| Intenso             | 1         | 1      | 0.4%    |
| Goldkey             | 1         | 1      | 0.4%    |
| Gigabyte Technology | 1         | 2      | 0.4%    |
| CHN25SATAS1         | 1         | 1      | 0.4%    |
| China               | 1         | 1      | 0.4%    |
| ASMT                | 1         | 1      | 0.4%    |

Drive Model
-----------

Hard drive models

![Drive Model](./All/images/pie_chart/drive_model.svg)


| Model                                  | Computers | Percent |
|----------------------------------------|-----------|---------|
| Kingston SHFS37A120G 120GB SSD         | 7         | 2.69%   |
| Samsung NVMe SSD Drive 512GB           | 6         | 2.31%   |
| Toshiba MQ01ABD100 1TB                 | 4         | 1.54%   |
| Toshiba DT01ACA050 500GB               | 4         | 1.54%   |
| Seagate ST500LT012-9WS142 500GB        | 4         | 1.54%   |
| Seagate ST1000LM035-1RK172 1TB         | 4         | 1.54%   |
| Samsung SSD 860 EVO 500GB              | 4         | 1.54%   |
| Toshiba MQ04ABF100 1TB                 | 3         | 1.15%   |
| Toshiba DT01ACA100 1TB                 | 3         | 1.15%   |
| SanDisk NVMe SSD Drive 512GB           | 3         | 1.15%   |
| Samsung HD502HJ 500GB                  | 3         | 1.15%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD    | 3         | 1.15%   |
| Hitachi HTS543232A7A384 320GB          | 3         | 1.15%   |
| WDC WD5000AZRX-00A8LB0 500GB           | 2         | 0.77%   |
| WDC WD10SPZX-24Z10T0 1TB               | 2         | 0.77%   |
| WDC WD10SPZX-22Z10T1 1TB               | 2         | 0.77%   |
| Unknown MMC Card  64GB                 | 2         | 0.77%   |
| Transcend TS64GSSD370S 64GB            | 2         | 0.77%   |
| Toshiba MQ01ACF032 320GB               | 2         | 0.77%   |
| Toshiba MQ01ABF050 500GB               | 2         | 0.77%   |
| Toshiba HDWD110 1TB                    | 2         | 0.77%   |
| SPCC Solid State Disk 128GB            | 2         | 0.77%   |
| SK hynix NVMe SSD Drive 256GB          | 2         | 0.77%   |
| Seagate ST500DM002-1BD142 500GB        | 2         | 0.77%   |
| Seagate ST4000VM000-2AF166 4TB         | 2         | 0.77%   |
| Seagate ST2000DM008-2FR102 2TB         | 2         | 0.77%   |
| Seagate ST1000DL002-9TT153 1TB         | 2         | 0.77%   |
| SanDisk SD7UB3Q256G1001 256GB SSD      | 2         | 0.77%   |
| Samsung SM963 2.5" NVMe PCIe SSD 256GB | 2         | 0.77%   |
| Samsung MZVLW256HEHP-00000 256GB       | 2         | 0.77%   |
| Samsung HD251HJ 249GB                  | 2         | 0.77%   |
| Samsung HD082GJ 80GB                   | 2         | 0.77%   |
| Intel NVMe SSD Drive 512GB             | 2         | 0.77%   |
| Hitachi HTS547575A9E384 752GB          | 2         | 0.77%   |
| Hitachi HTS542525K9SA00 250GB          | 2         | 0.77%   |
| Apacer AS340 240GB SSD                 | 2         | 0.77%   |
| ZOTAC ZTSSD-S11-240G-P 240GB           | 1         | 0.38%   |
| XPG NVMe SSD Drive 512GB               | 1         | 0.38%   |
| WDC WDS512G1X0C-00ENX0 512GB           | 1         | 0.38%   |
| WDC WD800JD-22LSA0 80GB                | 1         | 0.38%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./All/images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| WDC                 | 34        | 36     | 25%     |
| Seagate             | 33        | 37     | 24.26%  |
| Toshiba             | 23        | 28     | 16.91%  |
| Samsung Electronics | 18        | 21     | 13.24%  |
| Hitachi             | 17        | 20     | 12.5%   |
| HGST                | 4         | 4      | 2.94%   |
| Maxtor              | 3         | 4      | 2.21%   |
| Fujitsu             | 2         | 2      | 1.47%   |
| Unknown             | 1         | 1      | 0.74%   |
| ASMT                | 1         | 1      | 0.74%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./All/images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Kingston            | 12        | 15     | 19.05%  |
| Samsung Electronics | 11        | 14     | 17.46%  |
| Transcend           | 5         | 5      | 7.94%   |
| SPCC                | 5         | 6      | 7.94%   |
| SanDisk             | 4         | 4      | 6.35%   |
| Apacer              | 4         | 4      | 6.35%   |
| Micron Technology   | 3         | 3      | 4.76%   |
| GOODRAM             | 2         | 2      | 3.17%   |
| Crucial             | 2         | 3      | 3.17%   |
| ZOTAC               | 1         | 3      | 1.59%   |
| Toshiba             | 1         | 1      | 1.59%   |
| Team                | 1         | 1      | 1.59%   |
| PNY                 | 1         | 1      | 1.59%   |
| Patriot             | 1         | 1      | 1.59%   |
| OCZ                 | 1         | 1      | 1.59%   |
| Netac               | 1         | 1      | 1.59%   |
| LITEONIT            | 1         | 1      | 1.59%   |
| Leven               | 1         | 1      | 1.59%   |
| Intenso             | 1         | 1      | 1.59%   |
| Goldkey             | 1         | 1      | 1.59%   |
| Gigabyte Technology | 1         | 2      | 1.59%   |
| CHN25SATAS1         | 1         | 1      | 1.59%   |
| China               | 1         | 1      | 1.59%   |
| A-DATA Technology   | 1         | 1      | 1.59%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./All/images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 116       | 154    | 51.33%  |
| SSD  | 59        | 74     | 26.11%  |
| NVMe | 48        | 61     | 21.24%  |
| MMC  | 3         | 3      | 1.33%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./All/images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 148       | 226    | 73.63%  |
| NVMe | 48        | 61     | 23.88%  |
| MMC  | 3         | 3      | 1.49%   |
| SAS  | 2         | 2      | 1%      |

Drive Size
----------

Size of hard drive

![Drive Size](./All/images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 122       | 171    | 72.19%  |
| 0.51-1.0   | 37        | 47     | 21.89%  |
| 1.01-2.0   | 6         | 6      | 3.55%   |
| 3.01-4.0   | 3         | 3      | 1.78%   |
| 4.01-10.0  | 1         | 1      | 0.59%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./All/images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 251-500        | 54        | 27.69%  |
| 101-250        | 54        | 27.69%  |
| 501-1000       | 23        | 11.79%  |
| 51-100         | 23        | 11.79%  |
| 1-20           | 17        | 8.72%   |
| 21-50          | 8         | 4.1%    |
| 1001-2000      | 6         | 3.08%   |
| Unknown        | 6         | 3.08%   |
| More than 3000 | 2         | 1.03%   |
| 2001-3000      | 2         | 1.03%   |

Space Used
----------

Amount of used disk space

![Space Used](./All/images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 95        | 47.98%  |
| 21-50          | 32        | 16.16%  |
| 51-100         | 24        | 12.12%  |
| 101-250        | 18        | 9.09%   |
| 251-500        | 13        | 6.57%   |
| 501-1000       | 7         | 3.54%   |
| Unknown        | 6         | 3.03%   |
| 1001-2000      | 2         | 1.01%   |
| More than 3000 | 1         | 0.51%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./All/images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB   | 3         | 3      | 6.52%   |
| Samsung Electronics HD082GJ 80GB  | 2         | 2      | 4.35%   |
| Kingston SHFS37A120G 120GB SSD    | 2         | 4      | 4.35%   |
| Hitachi HTS547575A9E384 752GB     | 2         | 2      | 4.35%   |
| WDC WD800JD-22LSA0 80GB           | 1         | 1      | 2.17%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1         | 1      | 2.17%   |
| WDC WD5000AAKS-75V0A0 500GB       | 1         | 1      | 2.17%   |
| WDC WD5000AAKS-00WWPA0 500GB      | 1         | 1      | 2.17%   |
| WDC WD5000AADS-56S9B1 500GB       | 1         | 1      | 2.17%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 2.17%   |
| WDC WD2500AAKX-00U6AA0 250GB      | 1         | 1      | 2.17%   |
| WDC WD1600BEVS-60RST0 160GB       | 1         | 1      | 2.17%   |
| WDC WD1600BEVS-07RST0 160GB       | 1         | 1      | 2.17%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 2.17%   |
| Toshiba MQ01ABD032 320GB          | 1         | 1      | 2.17%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 2.17%   |
| Team L5 LITE SSD 240GB            | 1         | 1      | 2.17%   |
| SPCC SSD162 120GB                 | 1         | 1      | 2.17%   |
| SPCC Solid State Disk 56GB        | 1         | 2      | 2.17%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 2.17%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 2.17%   |
| Seagate ST320DM001 HD322GJ 320GB  | 1         | 1      | 2.17%   |
| Seagate ST3160023A 160GB          | 1         | 1      | 2.17%   |
| Seagate ST31000340NS 1TB          | 1         | 1      | 2.17%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 2.17%   |
| Seagate ST1000DL002-9TT153 1TB    | 1         | 1      | 2.17%   |
| SanDisk SD7UB3Q256G1001 256GB SSD | 1         | 1      | 2.17%   |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 2.17%   |
| Samsung Electronics HD103UJ 1TB   | 1         | 1      | 2.17%   |
| Samsung Electronics HD080HJ 80GB  | 1         | 1      | 2.17%   |
| Maxtor STM380215AS 80GB           | 1         | 1      | 2.17%   |
| Maxtor STM3160811AS 160GB         | 1         | 1      | 2.17%   |
| Maxtor STM3160211AS 160GB         | 1         | 1      | 2.17%   |
| Maxtor 4R120L0 128GB              | 1         | 1      | 2.17%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 2.17%   |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 2.17%   |
| Hitachi HDT721010SLA360 1TB       | 1         | 2      | 2.17%   |
| Hitachi HDP725050GLA360 500GB     | 1         | 1      | 2.17%   |
| Hitachi HDP725025GLA380 250GB     | 1         | 2      | 2.17%   |
| Fujitsu MHW2080BH PL 80GB         | 1         | 1      | 2.17%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./All/images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 22.22%  |
| WDC                 | 9         | 9      | 20%     |
| Hitachi             | 7         | 9      | 15.56%  |
| Samsung Electronics | 5         | 5      | 11.11%  |
| Toshiba             | 3         | 3      | 6.67%   |
| Maxtor              | 3         | 4      | 6.67%   |
| SPCC                | 2         | 3      | 4.44%   |
| Kingston            | 2         | 4      | 4.44%   |
| Team                | 1         | 1      | 2.22%   |
| SanDisk             | 1         | 1      | 2.22%   |
| Fujitsu             | 1         | 1      | 2.22%   |
| A-DATA Technology   | 1         | 1      | 2.22%   |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./All/images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 26.32%  |
| WDC                 | 9         | 9      | 23.68%  |
| Hitachi             | 7         | 9      | 18.42%  |
| Samsung Electronics | 5         | 5      | 13.16%  |
| Toshiba             | 3         | 3      | 7.89%   |
| Maxtor              | 3         | 4      | 7.89%   |
| Fujitsu             | 1         | 1      | 2.63%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./All/images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 34        | 41     | 82.93%  |
| SSD  | 7         | 10     | 17.07%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./All/images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-24ZEST0 320GB      | 1         | 1      | 25%     |
| Seagate ST9250315AS 250GB         | 1         | 1      | 25%     |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 25%     |
| Samsung Electronics HD322GJ 320GB | 1         | 2      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./All/images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 50%     |
| WDC                 | 1         | 1      | 25%     |
| Seagate             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./All/images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 92        | 138    | 44.88%  |
| Detected | 68        | 98     | 33.17%  |
| Malfunc  | 41        | 51     | 20%     |
| Failed   | 4         | 5      | 1.95%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./All/images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 115       | 49.78%  |
| AMD                            | 50        | 21.65%  |
| Samsung Electronics            | 23        | 9.96%   |
| Nvidia                         | 9         | 3.9%    |
| SK hynix                       | 6         | 2.6%    |
| SanDisk                        | 6         | 2.6%    |
| JMicron Technology             | 5         | 2.16%   |
| Toshiba America Info Systems   | 3         | 1.3%    |
| Phison Electronics             | 2         | 0.87%   |
| Micron Technology              | 2         | 0.87%   |
| ASMedia Technology             | 2         | 0.87%   |
| ADATA Technology               | 2         | 0.87%   |
| Solid State Storage Technology | 1         | 0.43%   |
| Marvell Technology Group       | 1         | 0.43%   |
| Lenovo                         | 1         | 0.43%   |
| KIOXIA                         | 1         | 0.43%   |
| Kingston Technology Company    | 1         | 0.43%   |
| Hewlett-Packard                | 1         | 0.43%   |

Storage Model
-------------

Storage controller models

![Storage Model](./All/images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 24        | 8.57%   |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13        | 4.64%   |
| Samsung NVMe SSD Controller 980                                                         | 11        | 3.93%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 11        | 3.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11        | 3.93%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8         | 2.86%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 2.5%    |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 2.5%    |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 2.14%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 2.14%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 2.14%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 5         | 1.79%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.79%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 5         | 1.79%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 5         | 1.79%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 4         | 1.43%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4         | 1.43%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.43%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 1.43%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.43%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.43%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 1.43%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 4         | 1.43%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 3         | 1.07%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 3         | 1.07%   |
| Nvidia MCP61 SATA Controller                                                            | 3         | 1.07%   |
| Nvidia MCP61 IDE                                                                        | 3         | 1.07%   |
| JMicron JMB368 IDE controller                                                           | 3         | 1.07%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 1.07%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3         | 1.07%   |
| AMD FCH IDE Controller                                                                  | 3         | 1.07%   |
| AMD 500 Series Chipset SATA Controller                                                  | 3         | 1.07%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.71%   |
| SK hynix Gold P31 SSD                                                                   | 2         | 0.71%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.71%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 2         | 0.71%   |
| Micron Non-Volatile memory controller                                                   | 2         | 0.71%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.71%   |
| Intel SSD 660P Series                                                                   | 2         | 0.71%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./All/images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 139       | 56.73%  |
| NVMe | 48        | 19.59%  |
| IDE  | 48        | 19.59%  |
| RAID | 10        | 4.08%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./All/images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 125       | 67.2%   |
| AMD    | 61        | 32.8%   |

CPU Model
---------

Processor models

![CPU Model](./All/images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.69%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.61%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.61%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 3         | 1.61%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.61%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 3         | 1.61%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 3         | 1.61%   |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 1.61%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 2         | 1.08%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 1.08%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.08%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.08%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.08%   |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2         | 1.08%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.08%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.08%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.08%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.08%   |
| Intel Core i3-5010U CPU @ 2.10GHz             | 2         | 1.08%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 1.08%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 1.08%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.08%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.08%   |
| AMD Ryzen 7 5800H with Radeon Graphics        | 2         | 1.08%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.08%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 1.08%   |
| AMD Phenom II X6 1055T Processor              | 2         | 1.08%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 1.08%   |
| AMD Athlon II X2 280 Processor                | 2         | 1.08%   |
| Intel Xeon CPU E5405 @ 2.00GHz                | 1         | 0.54%   |
| Intel Pentium Silver N5030 CPU @ 1.10GHz      | 1         | 0.54%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.54%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.54%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.54%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1         | 0.54%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.54%   |
| Intel Pentium D CPU 2.80GHz                   | 1         | 0.54%   |
| Intel Pentium D CPU 2.66GHz                   | 1         | 0.54%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.54%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.54%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./All/images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 39        | 20.97%  |
| Intel Core i7                  | 19        | 10.22%  |
| Intel Core i3                  | 19        | 10.22%  |
| Intel Celeron                  | 13        | 6.99%   |
| Intel Pentium                  | 12        | 6.45%   |
| AMD Ryzen 5                    | 9         | 4.84%   |
| AMD Ryzen 7                    | 7         | 3.76%   |
| AMD Athlon II X2               | 6         | 3.23%   |
| Other                          | 5         | 2.69%   |
| Intel Core 2 Duo               | 5         | 2.69%   |
| AMD E                          | 5         | 2.69%   |
| AMD Athlon 64 X2               | 5         | 2.69%   |
| AMD A4                         | 4         | 2.15%   |
| Intel Pentium Silver           | 3         | 1.61%   |
| AMD Ryzen 3                    | 3         | 1.61%   |
| AMD E1                         | 3         | 1.61%   |
| AMD A10                        | 3         | 1.61%   |
| Intel Pentium Dual-Core        | 2         | 1.08%   |
| Intel Pentium D                | 2         | 1.08%   |
| AMD Sempron                    | 2         | 1.08%   |
| AMD Phenom II X6               | 2         | 1.08%   |
| AMD FX                         | 2         | 1.08%   |
| AMD Athlon II X4               | 2         | 1.08%   |
| AMD Athlon                     | 2         | 1.08%   |
| Intel Xeon                     | 1         | 0.54%   |
| Intel Pentium Dual             | 1         | 0.54%   |
| Intel Pentium 4                | 1         | 0.54%   |
| Intel Core i9                  | 1         | 0.54%   |
| Intel Core 2 Quad              | 1         | 0.54%   |
| Intel Atom                     | 1         | 0.54%   |
| AMD V140                       | 1         | 0.54%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.54%   |
| AMD Ryzen 5 PRO                | 1         | 0.54%   |
| AMD Phenom II X4               | 1         | 0.54%   |
| AMD A8                         | 1         | 0.54%   |
| AMD A6                         | 1         | 0.54%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./All/images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 90        | 48.13%  |
| 4       | 63        | 33.69%  |
| 6       | 14        | 7.49%   |
| 8       | 10        | 5.35%   |
| 1       | 5         | 2.67%   |
| Unknown | 4         | 2.14%   |
| 10      | 1         | 0.53%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./All/images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 185       | 99.46%  |
| 2      | 1         | 0.54%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./All/images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 97        | 51.87%  |
| 1       | 86        | 45.99%  |
| Unknown | 4         | 2.14%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./All/images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 183       | 98.39%  |
| Unknown        | 3         | 1.61%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./All/images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 27        | 14.44%  |
| 0x206a7    | 12        | 6.42%   |
| 0x806ea    | 10        | 5.35%   |
| 0x306c3    | 8         | 4.28%   |
| 0x05000119 | 8         | 4.28%   |
| 0x306a9    | 7         | 3.74%   |
| 0x010000c8 | 7         | 3.74%   |
| 0x806ec    | 6         | 3.21%   |
| 0x906e9    | 5         | 2.67%   |
| 0x08600106 | 5         | 2.67%   |
| 0x906ea    | 4         | 2.14%   |
| 0x506e3    | 4         | 2.14%   |
| 0x40651    | 4         | 2.14%   |
| 0x306d4    | 4         | 2.14%   |
| 0x1067a    | 4         | 2.14%   |
| 0x806e9    | 3         | 1.6%    |
| 0x706a1    | 3         | 1.6%    |
| 0x6fd      | 3         | 1.6%    |
| 0x506c9    | 3         | 1.6%    |
| 0x406e3    | 3         | 1.6%    |
| 0x03000027 | 3         | 1.6%    |
| 0xf47      | 2         | 1.07%   |
| 0xa0652    | 2         | 1.07%   |
| 0x806c1    | 2         | 1.07%   |
| 0x706e5    | 2         | 1.07%   |
| 0x406c4    | 2         | 1.07%   |
| 0x406c3    | 2         | 1.07%   |
| 0x30678    | 2         | 1.07%   |
| 0x10676    | 2         | 1.07%   |
| 0x0a50000c | 2         | 1.07%   |
| 0x08701021 | 2         | 1.07%   |
| 0x08608103 | 2         | 1.07%   |
| 0x08108109 | 2         | 1.07%   |
| 0x08108102 | 2         | 1.07%   |
| 0x06001119 | 2         | 1.07%   |
| 0x02000057 | 2         | 1.07%   |
| 0x010000dc | 2         | 1.07%   |
| 0xf49      | 1         | 0.53%   |
| 0xf41      | 1         | 0.53%   |
| 0xa0655    | 1         | 0.53%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./All/images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 33        | 17.74%  |
| Haswell          | 15        | 8.06%   |
| K10              | 13        | 6.99%   |
| SandyBridge      | 12        | 6.45%   |
| Zen 2            | 10        | 5.38%   |
| Skylake          | 9         | 4.84%   |
| Bobcat           | 8         | 4.3%    |
| IvyBridge        | 7         | 3.76%   |
| Silvermont       | 6         | 3.23%   |
| Penryn           | 6         | 3.23%   |
| Zen+             | 5         | 2.69%   |
| K8 Hammer        | 5         | 2.69%   |
| Goldmont plus    | 5         | 2.69%   |
| Core             | 5         | 2.69%   |
| Piledriver       | 4         | 2.15%   |
| NetBurst         | 4         | 2.15%   |
| K10 Llano        | 4         | 2.15%   |
| Icelake          | 4         | 2.15%   |
| Broadwell        | 4         | 2.15%   |
| TigerLake        | 3         | 1.61%   |
| K8 & K10 hybrid  | 3         | 1.61%   |
| Goldmont         | 3         | 1.61%   |
| CometLake        | 3         | 1.61%   |
| Unknown          | 3         | 1.61%   |
| Zen 3            | 2         | 1.08%   |
| Zen              | 2         | 1.08%   |
| Westmere         | 2         | 1.08%   |
| Steamroller      | 1         | 0.54%   |
| Puma             | 1         | 0.54%   |
| Nehalem          | 1         | 0.54%   |
| Bulldozer        | 1         | 0.54%   |
| Bonnell          | 1         | 0.54%   |
| Alderlake Hybrid | 1         | 0.54%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./All/images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 99        | 45.83%  |
| Nvidia | 59        | 27.31%  |
| AMD    | 58        | 26.85%  |

GPU Model
---------

Graphics card models

![GPU Model](./All/images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 4.93%   |
| Intel UHD Graphics 620                                                                   | 10        | 4.48%   |
| AMD Renoir                                                                               | 7         | 3.14%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.69%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.24%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.24%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 5         | 2.24%   |
| Intel HD Graphics 620                                                                    | 4         | 1.79%   |
| Intel HD Graphics 5500                                                                   | 4         | 1.79%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.79%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.79%   |
| Nvidia GP108M [GeForce MX150]                                                            | 3         | 1.35%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.35%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.35%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3         | 1.35%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.35%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.35%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 3         | 1.35%   |
| Intel HD Graphics 630                                                                    | 3         | 1.35%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 3         | 1.35%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.35%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 1.35%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 3         | 1.35%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 1.35%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 3         | 1.35%   |
| Nvidia TU117M                                                                            | 2         | 0.9%    |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.9%    |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.9%    |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.9%    |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.9%    |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.9%    |
| Nvidia GF108 [GeForce GT 440]                                                            | 2         | 0.9%    |
| Nvidia C77 [GeForce 8200M G]                                                             | 2         | 0.9%    |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.9%    |
| Intel HD Graphics 530                                                                    | 2         | 0.9%    |
| Intel HD Graphics 500                                                                    | 2         | 0.9%    |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.9%    |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.9%    |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.9%    |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.9%    |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./All/images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 72        | 38.3%   |
| 1 x AMD        | 47        | 25%     |
| 1 x Nvidia     | 34        | 18.09%  |
| Intel + Nvidia | 23        | 12.23%  |
| 2 x AMD        | 6         | 3.19%   |
| Intel + AMD    | 3         | 1.6%    |
| AMD + Nvidia   | 2         | 1.06%   |
| Other          | 1         | 0.53%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./All/images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 155       | 80.31%  |
| Proprietary | 26        | 13.47%  |
| Unknown     | 12        | 6.22%   |

GPU Memory
----------

Total video memory

![GPU Memory](./All/images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 85        | 43.59%  |
| 0.01-0.5   | 41        | 21.03%  |
| 1.01-2.0   | 38        | 19.49%  |
| 3.01-4.0   | 15        | 7.69%   |
| 0.51-1.0   | 11        | 5.64%   |
| 7.01-8.0   | 2         | 1.03%   |
| 5.01-6.0   | 2         | 1.03%   |
| 2.01-3.0   | 1         | 0.51%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./All/images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 32        | 16.16%  |
| Samsung Electronics     | 30        | 15.15%  |
| LG Display              | 20        | 10.1%   |
| Chimei Innolux          | 19        | 9.6%    |
| Goldstar                | 16        | 8.08%   |
| Philips                 | 15        | 7.58%   |
| BOE                     | 12        | 6.06%   |
| Dell                    | 8         | 4.04%   |
| Acer                    | 8         | 4.04%   |
| AOC                     | 6         | 3.03%   |
| Chi Mei Optoelectronics | 5         | 2.53%   |
| InfoVision              | 4         | 2.02%   |
| Hewlett-Packard         | 4         | 2.02%   |
| Sharp                   | 3         | 1.52%   |
| Lenovo                  | 2         | 1.01%   |
| CSO                     | 2         | 1.01%   |
| BenQ                    | 2         | 1.01%   |
| ViewSonic               | 1         | 0.51%   |
| Toshiba                 | 1         | 0.51%   |
| Plain Tree Systems      | 1         | 0.51%   |
| PANDA                   | 1         | 0.51%   |
| Medion                  | 1         | 0.51%   |
| KTC                     | 1         | 0.51%   |
| Hitachi                 | 1         | 0.51%   |
| HannStar                | 1         | 0.51%   |
| ASUSTek Computer        | 1         | 0.51%   |
| Ancor Communications    | 1         | 0.51%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./All/images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x193mm 15.5-inch         | 4         | 1.99%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch           | 3         | 1.49%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 3         | 1.49%   |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch          | 3         | 1.49%   |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 3         | 1.49%   |
| Samsung Electronics SyncMaster SAM0108 1280x1024 312x234mm 15.4-inch   | 2         | 1%      |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                     | 2         | 1%      |
| InfoVision LCD Monitor IVO057D 1920x1080 309x174mm 14.0-inch           | 2         | 1%      |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch             | 2         | 1%      |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 798x334mm 34.1-inch               | 2         | 1%      |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x194mm 15.5-inch        | 2         | 1%      |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                  | 2         | 1%      |
| BOE LCD Monitor BOE0747 1920x1080 344x194mm 15.5-inch                  | 2         | 1%      |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 2         | 1%      |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                        | 2         | 1%      |
| ViewSonic VA521-1 VSCF318 1024x768 304x228mm 15.0-inch                 | 1         | 0.5%    |
| Toshiba TV TSB0108 1920x540 698x393mm 31.5-inch                        | 1         | 0.5%    |
| Sharp LQ156M1JW01 SHP14C3 1920x1080 344x194mm 15.5-inch                | 1         | 0.5%    |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.5%    |
| Sharp LCD Monitor SHP13CF 1280x800 331x207mm 15.4-inch                 | 1         | 0.5%    |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch      | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM03D1 1680x1050 433x271mm 20.1-inch   | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch    | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM036E 1280x1024 380x300mm 19.1-inch   | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch    | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch    | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM022B 1280x1024 340x270mm 17.1-inch   | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0213 1680x1050 408x306mm 20.1-inch   | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch   | 1         | 0.5%    |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch    | 1         | 0.5%    |
| Samsung Electronics SMB2440 SAM06AF 1920x1080 531x299mm 24.0-inch      | 1         | 0.5%    |
| Samsung Electronics SMB2030 SAM063D 1600x900 443x249mm 20.0-inch       | 1         | 0.5%    |
| Samsung Electronics S27F358 SAM0D73 1920x1080 598x336mm 27.0-inch      | 1         | 0.5%    |
| Samsung Electronics S22E391 SAM0C0D 1920x1080 477x268mm 21.5-inch      | 1         | 0.5%    |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1         | 0.5%    |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1         | 0.5%    |
| Samsung Electronics S/T 77E/76E STN0005 1280x1024 312x234mm 15.4-inch  | 1         | 0.5%    |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1         | 0.5%    |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch    | 1         | 0.5%    |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch   | 1         | 0.5%    |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./All/images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 79        | 42.02%  |
| 1366x768 (WXGA)    | 48        | 25.53%  |
| 1600x900 (HD+)     | 13        | 6.91%   |
| 1280x1024 (SXGA)   | 12        | 6.38%   |
| 2560x1440 (QHD)    | 7         | 3.72%   |
| 1680x1050 (WSXGA+) | 5         | 2.66%   |
| 1440x900 (WXGA+)   | 5         | 2.66%   |
| 3840x2160 (4K)     | 4         | 2.13%   |
| 1280x800 (WXGA)    | 3         | 1.6%    |
| 2560x1600          | 2         | 1.06%   |
| 2560x1080          | 2         | 1.06%   |
| 1600x1200          | 2         | 1.06%   |
| 1024x768 (XGA)     | 2         | 1.06%   |
| 3456x2160          | 1         | 0.53%   |
| 2160x1440          | 1         | 0.53%   |
| 1920x540           | 1         | 0.53%   |
| 1360x768           | 1         | 0.53%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./All/images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 85        | 42.5%   |
| 23     | 14        | 7%      |
| 24     | 13        | 6.5%    |
| 21     | 11        | 5.5%    |
| 19     | 11        | 5.5%    |
| 17     | 11        | 5.5%    |
| 27     | 10        | 5%      |
| 14     | 10        | 5%      |
| 20     | 8         | 4%      |
| 18     | 6         | 3%      |
| 13     | 6         | 3%      |
| 11     | 4         | 2%      |
| 34     | 2         | 1%      |
| 16     | 2         | 1%      |
| 12     | 2         | 1%      |
| 84     | 1         | 0.5%    |
| 72     | 1         | 0.5%    |
| 32     | 1         | 0.5%    |
| 31     | 1         | 0.5%    |
| 22     | 1         | 0.5%    |

Monitor Width
-------------

Physical width

![Monitor Width](./All/images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 104       | 52.53%  |
| 501-600     | 34        | 17.17%  |
| 401-500     | 31        | 15.66%  |
| 351-400     | 13        | 6.57%   |
| 201-300     | 9         | 4.55%   |
| 701-800     | 3         | 1.52%   |
| 601-700     | 2         | 1.01%   |
| 1501-2000   | 2         | 1.01%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./All/images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 143       | 80.34%  |
| 16/10 | 14        | 7.87%   |
| 5/4   | 10        | 5.62%   |
| 4/3   | 7         | 3.93%   |
| 3/2   | 2         | 1.12%   |
| 21/9  | 2         | 1.12%   |

Monitor Area
------------

Area in inch²

![Monitor Area](./All/images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 81        | 40.7%   |
| 201-250        | 35        | 17.59%  |
| 151-200        | 23        | 11.56%  |
| 81-90          | 14        | 7.04%   |
| 301-350        | 10        | 5.03%   |
| 141-150        | 10        | 5.03%   |
| 111-120        | 6         | 3.02%   |
| 51-60          | 4         | 2.01%   |
| 351-500        | 4         | 2.01%   |
| 121-130        | 4         | 2.01%   |
| More than 1000 | 2         | 1.01%   |
| 71-80          | 2         | 1.01%   |
| 61-70          | 2         | 1.01%   |
| 131-140        | 2         | 1.01%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./All/images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 71        | 36.41%  |
| 121-160       | 59        | 30.26%  |
| 101-120       | 57        | 29.23%  |
| 161-240       | 5         | 2.56%   |
| More than 240 | 2         | 1.03%   |
| 1-50          | 1         | 0.51%   |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./All/images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 161       | 85.64%  |
| 2     | 23        | 12.23%  |
| 0     | 4         | 2.13%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./All/images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 122       | 45.02%  |
| Intel                             | 57        | 21.03%  |
| Qualcomm Atheros                  | 44        | 16.24%  |
| Broadcom                          | 11        | 4.06%   |
| Nvidia                            | 8         | 2.95%   |
| Xiaomi                            | 4         | 1.48%   |
| Ralink                            | 4         | 1.48%   |
| Broadcom Limited                  | 4         | 1.48%   |
| TP-Link                           | 2         | 0.74%   |
| MediaTek                          | 2         | 0.74%   |
| Marvell Technology Group          | 2         | 0.74%   |
| Sierra Wireless                   | 1         | 0.37%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.37%   |
| Mercucys                          | 1         | 0.37%   |
| JMicron Technology                | 1         | 0.37%   |
| ICS Advent                        | 1         | 0.37%   |
| Huawei Technologies               | 1         | 0.37%   |
| Hewlett-Packard                   | 1         | 0.37%   |
| Ericsson Business Mobile Networks | 1         | 0.37%   |
| D-Link System                     | 1         | 0.37%   |
| D-Link                            | 1         | 0.37%   |
| ASIX Electronics                  | 1         | 0.37%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./All/images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 88        | 28.3%   |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 21        | 6.75%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 2.89%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 2.89%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 2.57%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 2.57%   |
| Intel Wireless 8265 / 8275                                              | 8         | 2.57%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.61%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.61%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 1.29%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.29%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.29%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 0.96%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 0.96%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 0.96%   |
| Nvidia MCP77 Ethernet                                                   | 3         | 0.96%   |
| Nvidia MCP61 Ethernet                                                   | 3         | 0.96%   |
| Intel Wireless 7260                                                     | 3         | 0.96%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 0.96%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 0.96%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 0.96%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 0.96%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.64%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.64%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.64%   |
| Realtek RTL8125 2.5GbE Controller                                       | 2         | 0.64%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.64%   |
| Intel Wireless 8260                                                     | 2         | 0.64%   |
| Intel Wireless 7265                                                     | 2         | 0.64%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.64%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 0.64%   |
| Intel Ethernet Connection I217-V                                        | 2         | 0.64%   |
| Intel Ethernet Connection (3) I218-V                                    | 2         | 0.64%   |
| Intel Ethernet Connection (2) I219-V                                    | 2         | 0.64%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.64%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.64%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.64%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.64%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 2         | 0.64%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 0.64%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./All/images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 47        | 34.81%  |
| Qualcomm Atheros      | 38        | 28.15%  |
| Realtek Semiconductor | 30        | 22.22%  |
| Broadcom              | 8         | 5.93%   |
| Ralink                | 4         | 2.96%   |
| TP-Link               | 2         | 1.48%   |
| Sierra Wireless       | 1         | 0.74%   |
| Mercucys              | 1         | 0.74%   |
| MediaTek              | 1         | 0.74%   |
| D-Link System         | 1         | 0.74%   |
| D-Link                | 1         | 0.74%   |
| Broadcom Limited      | 1         | 0.74%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./All/images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 6.67%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 9         | 6.67%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 8         | 5.93%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 8         | 5.93%   |
| Intel Wireless 8265 / 8275                                              | 8         | 5.93%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 3.7%    |
| Intel Wi-Fi 6 AX200                                                     | 5         | 3.7%    |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 2.96%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 2.96%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.22%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 2.22%   |
| Intel Wireless 7260                                                     | 3         | 2.22%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 2.22%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.22%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.22%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.48%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.48%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.48%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.48%   |
| Intel Wireless 8260                                                     | 2         | 1.48%   |
| Intel Wireless 7265                                                     | 2         | 1.48%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.48%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.48%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.48%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.48%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.48%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.48%   |
| Sierra Wireless EM7455 Qualcomm Snapdragon X7 LTE-A                     | 1         | 0.74%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.74%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.74%   |
| Realtek RTL8812AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.74%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.74%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.74%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.74%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.74%   |
| Realtek 802.11ac NIC                                                    | 1         | 0.74%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]        | 1         | 0.74%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.74%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.74%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 1         | 0.74%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./All/images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 113       | 65.7%   |
| Intel                    | 25        | 14.53%  |
| Qualcomm Atheros         | 8         | 4.65%   |
| Nvidia                   | 8         | 4.65%   |
| Xiaomi                   | 4         | 2.33%   |
| Broadcom Limited         | 3         | 1.74%   |
| Broadcom                 | 3         | 1.74%   |
| Marvell Technology Group | 2         | 1.16%   |
| MediaTek                 | 1         | 0.58%   |
| JMicron Technology       | 1         | 0.58%   |
| ICS Advent               | 1         | 0.58%   |
| Huawei Technologies      | 1         | 0.58%   |
| Hewlett-Packard          | 1         | 0.58%   |
| ASIX Electronics         | 1         | 0.58%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./All/images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 88        | 50.57%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 21        | 12.07%  |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 2.3%    |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 1.72%   |
| Nvidia MCP77 Ethernet                                                          | 3         | 1.72%   |
| Nvidia MCP61 Ethernet                                                          | 3         | 1.72%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.72%   |
| Realtek RTL8125 2.5GbE Controller                                              | 2         | 1.15%   |
| Intel I211 Gigabit Network Connection                                          | 2         | 1.15%   |
| Intel Ethernet Connection I217-V                                               | 2         | 1.15%   |
| Intel Ethernet Connection (3) I218-V                                           | 2         | 1.15%   |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 1.15%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.15%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.57%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.57%   |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.57%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.57%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.57%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.57%   |
| Qualcomm Atheros AR8131 Gigabit Ethernet                                       | 1         | 0.57%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.57%   |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.57%   |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.57%   |
| MediaTek TECNO Pouvoir 3 Air                                                   | 1         | 0.57%   |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.57%   |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.57%   |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.57%   |
| Intel NM10/ICH7 Family LAN Controller                                          | 1         | 0.57%   |
| Intel Ethernet Connection I219-V                                               | 1         | 0.57%   |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.57%   |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.57%   |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.57%   |
| Intel Ethernet Connection (5) I219-V                                           | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.57%   |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.57%   |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.57%   |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.57%   |
| Intel Ethernet Connection (10) I219-LM                                         | 1         | 0.57%   |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.57%   |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 0.57%   |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./All/images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 167       | 55.48%  |
| WiFi     | 132       | 43.85%  |
| Modem    | 1         | 0.33%   |
| Unknown  | 1         | 0.33%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./All/images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 97        | 51.32%  |
| Ethernet | 92        | 48.68%  |

NICs
----

Total network controllers on board

![NICs](./All/images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 104       | 55.91%  |
| 1     | 82        | 44.09%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./All/images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 179       | 96.24%  |
| Yes  | 7         | 3.76%   |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./All/images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 39        | 40.63%  |
| Qualcomm Atheros Communications | 12        | 12.5%   |
| Realtek Semiconductor           | 11        | 11.46%  |
| IMC Networks                    | 11        | 11.46%  |
| Broadcom                        | 6         | 6.25%   |
| Lite-On Technology              | 5         | 5.21%   |
| Foxconn / Hon Hai               | 3         | 3.13%   |
| Cambridge Silicon Radio         | 2         | 2.08%   |
| Toshiba                         | 1         | 1.04%   |
| Realtek                         | 1         | 1.04%   |
| Ralink Technology               | 1         | 1.04%   |
| Integrated System Solution      | 1         | 1.04%   |
| Hewlett-Packard                 | 1         | 1.04%   |
| Dell                            | 1         | 1.04%   |
| ASUSTek Computer                | 1         | 1.04%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./All/images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 16        | 16.67%  |
| Realtek Bluetooth Radio                                                             | 9         | 9.38%   |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 8         | 8.33%   |
| Intel AX201 Bluetooth                                                               | 8         | 8.33%   |
| IMC Networks Bluetooth Radio                                                        | 6         | 6.25%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 5         | 5.21%   |
| Intel AX200 Bluetooth                                                               | 5         | 5.21%   |
| IMC Networks Bluetooth Device                                                       | 4         | 4.17%   |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 3         | 3.13%   |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 2.08%   |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2.08%   |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 2.08%   |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.08%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 2         | 2.08%   |
| Broadcom BCM20702A0                                                                 | 2         | 2.08%   |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1.04%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.04%   |
| Ralink CSR BS8510                                                                   | 1         | 1.04%   |
| Qualcomm Atheros QCA61x4 Bluetooth 4.0                                              | 1         | 1.04%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.04%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 1.04%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.04%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.04%   |
| Integrated System Solution Bluetooth Device                                         | 1         | 1.04%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 1.04%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.04%   |
| Foxconn / Hon Hai Wireless_Device                                                   | 1         | 1.04%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.04%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.04%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.04%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 1.04%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 1.04%   |
| Broadcom BCM92045B3 ROM                                                             | 1         | 1.04%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.04%   |
| ASUS BCM20702A0                                                                     | 1         | 1.04%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./All/images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 122       | 51.69%  |
| AMD                       | 61        | 25.85%  |
| Nvidia                    | 40        | 16.95%  |
| Plantronics               | 2         | 0.85%   |
| Logitech                  | 2         | 0.85%   |
| Creative Labs             | 2         | 0.85%   |
| Texas Instruments         | 1         | 0.42%   |
| SteelSeries ApS           | 1         | 0.42%   |
| Shenzhen Rapoo Technology | 1         | 0.42%   |
| Sennheiser Communications | 1         | 0.42%   |
| Kingston Technology       | 1         | 0.42%   |
| GN Netcom                 | 1         | 0.42%   |
| C-Media Electronics       | 1         | 0.42%   |

Sound Model
-----------

Sound card models

![Sound Model](./All/images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                                      | 20        | 6.9%    |
| Intel Sunrise Point-LP HD Audio                                                                   | 17        | 5.86%   |
| AMD Family 17h/19h HD Audio Controller                                                            | 17        | 5.86%   |
| AMD FCH Azalia Controller                                                                         | 12        | 4.14%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 10        | 3.45%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 10        | 3.45%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 3.1%    |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 2.76%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.76%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 2.76%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.07%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.07%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.72%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.72%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 5         | 1.72%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.72%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.72%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.72%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 5         | 1.72%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.38%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.38%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 4         | 1.38%   |
| Intel Broadwell-U Audio Controller                                                                | 4         | 1.38%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.38%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.38%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 3         | 1.03%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 1.03%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 1.03%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 3         | 1.03%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.03%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.03%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 3         | 1.03%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.03%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.03%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.03%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.03%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.03%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.03%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 3         | 1.03%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 3         | 1.03%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./All/images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 34        | 22.97%  |
| Samsung Electronics | 29        | 19.59%  |
| SK hynix            | 19        | 12.84%  |
| Kingston            | 18        | 12.16%  |
| Micron Technology   | 8         | 5.41%   |
| GOODRAM             | 6         | 4.05%   |
| Transcend           | 3         | 2.03%   |
| Elpida              | 3         | 2.03%   |
| Unknown (ABCD)      | 2         | 1.35%   |
| Ramaxel Technology  | 2         | 1.35%   |
| Patriot             | 2         | 1.35%   |
| Nanya Technology    | 2         | 1.35%   |
| G.Skill             | 2         | 1.35%   |
| Crucial             | 2         | 1.35%   |
| Corsair             | 2         | 1.35%   |
| Apacer              | 2         | 1.35%   |
| A-DATA Technology   | 2         | 1.35%   |
| Unifosa             | 1         | 0.68%   |
| Team                | 1         | 0.68%   |
| Silicon Power       | 1         | 0.68%   |
| SGS/Thomson         | 1         | 0.68%   |
| Hexon               | 1         | 0.68%   |
| Goldkey             | 1         | 0.68%   |
| Axiom               | 1         | 0.68%   |
| AVEXIR              | 1         | 0.68%   |
| ASint Technology    | 1         | 0.68%   |
| Unknown             | 1         | 0.68%   |

Memory Model
------------

Memory module models

![Memory Model](./All/images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                      | 3         | 1.82%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 3         | 1.82%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.82%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 1.21%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 2         | 1.21%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                    | 2         | 1.21%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 2         | 1.21%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 2         | 1.21%   |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                    | 2         | 1.21%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                      | 2         | 1.21%   |
| Unknown (ABCD) RAM 123456789012345678 2GB SODIMM LPDDR4 2400MT/s | 2         | 1.21%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.21%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.21%   |
| Samsung RAM M471B2873FHS-CF8 1GB SODIMM DDR3 1067MT/s            | 2         | 1.21%   |
| Samsung RAM M471A1K43BB1-CRC 8GB SODIMM DDR4 2667MT/s            | 2         | 1.21%   |
| Samsung RAM M471A1G44AB0-CWE 8GB Row Of Chips DDR4 3200MT/s      | 2         | 1.21%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 2133MT/s              | 2         | 1.21%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.61%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM DDR3 1333MT/s                        | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 0.61%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.61%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.61%   |
| Unknown RAM Module 4096MB FB-DIMM DDR2 667MT/s                   | 1         | 0.61%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 0.61%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.61%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.61%   |
| Unknown RAM Module 2048MB SODIMM DDR2 400MT/s                    | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                     | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                       | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 2048MB DIMM                                   | 1         | 0.61%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.61%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1         | 0.61%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s                       | 1         | 0.61%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s        | 1         | 0.61%   |
| Unknown RAM ..E-D3U1600M/4G 4096MB DIMM DDR3 800MT/s             | 1         | 0.61%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./All/images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 47        | 35.07%  |
| DDR4    | 43        | 32.09%  |
| DDR2    | 12        | 8.96%   |
| Unknown | 11        | 8.21%   |
| SDRAM   | 10        | 7.46%   |
| LPDDR4  | 4         | 2.99%   |
| DDR     | 3         | 2.24%   |
| LPDDR3  | 2         | 1.49%   |
| DRAM    | 2         | 1.49%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./All/images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 64        | 49.61%  |
| DIMM         | 57        | 44.19%  |
| Row Of Chips | 7         | 5.43%   |
| FB-DIMM      | 1         | 0.78%   |

Memory Size
-----------

Memory module size

![Memory Size](./All/images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 52        | 34.67%  |
| 2048  | 37        | 24.67%  |
| 8192  | 30        | 20%     |
| 16384 | 13        | 8.67%   |
| 1024  | 13        | 8.67%   |
| 32768 | 3         | 2%      |
| 512   | 2         | 1.33%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./All/images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 34        | 23.78%  |
| 2667    | 22        | 15.38%  |
| 1333    | 17        | 11.89%  |
| 3200    | 8         | 5.59%   |
| 2133    | 7         | 4.9%    |
| 800     | 7         | 4.9%    |
| 667     | 6         | 4.2%    |
| 2400    | 5         | 3.5%    |
| 1334    | 5         | 3.5%    |
| Unknown | 4         | 2.8%    |
| 2048    | 3         | 2.1%    |
| 400     | 3         | 2.1%    |
| 333     | 3         | 2.1%    |
| 4199    | 2         | 1.4%    |
| 3600    | 2         | 1.4%    |
| 3000    | 2         | 1.4%    |
| 2933    | 2         | 1.4%    |
| 1067    | 2         | 1.4%    |
| 4800    | 1         | 0.7%    |
| 3500    | 1         | 0.7%    |
| 3266    | 1         | 0.7%    |
| 2800    | 1         | 0.7%    |
| 2666    | 1         | 0.7%    |
| 1867    | 1         | 0.7%    |
| 1400    | 1         | 0.7%    |
| 975     | 1         | 0.7%    |
| 533     | 1         | 0.7%    |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./All/images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 40%     |
| Canon           | 2         | 40%     |
| Seiko Epson     | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./All/images/pie_chart/printer_model.svg)


| Model                                 | Computers | Percent |
|---------------------------------------|-----------|---------|
| Seiko Epson USB2.0 Printer (Hi-speed) | 1         | 20%     |
| HP LaserJet M14-M17                   | 1         | 20%     |
| HP LaserJet 1020                      | 1         | 20%     |
| Canon LaserShot LBP-1120 Printer      | 1         | 20%     |
| Canon iP7200 series                   | 1         | 20%     |

Scanner Vendor
--------------

Scanner device vendors

![Scanner Vendor](./All/images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./All/images/pie_chart/scanner_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon CanoScan LiDE 700F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./All/images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 26        | 20.97%  |
| IMC Networks                           | 22        | 17.74%  |
| Realtek Semiconductor                  | 12        | 9.68%   |
| Microdia                               | 10        | 8.06%   |
| Acer                                   | 6         | 4.84%   |
| Quanta                                 | 5         | 4.03%   |
| Cheng Uei Precision Industry (Foxlink) | 5         | 4.03%   |
| Logitech                               | 4         | 3.23%   |
| Z-Star Microelectronics                | 3         | 2.42%   |
| Syntek                                 | 3         | 2.42%   |
| Sunplus Innovation Technology          | 3         | 2.42%   |
| Silicon Motion                         | 3         | 2.42%   |
| Lite-On Technology                     | 3         | 2.42%   |
| Suyin                                  | 2         | 1.61%   |
| Samsung Electronics                    | 2         | 1.61%   |
| Luxvisions Innotech Limited            | 2         | 1.61%   |
| KYE Systems (Mouse Systems)            | 2         | 1.61%   |
| Alcor Micro                            | 2         | 1.61%   |
| YGTek                                  | 1         | 0.81%   |
| Trust                                  | 1         | 0.81%   |
| Pixart Imaging                         | 1         | 0.81%   |
| Microsoft                              | 1         | 0.81%   |
| Importek                               | 1         | 0.81%   |
| Genesys Logic                          | 1         | 0.81%   |
| GEMBIRD                                | 1         | 0.81%   |
| Cubeternet                             | 1         | 0.81%   |
| Aveo Technology                        | 1         | 0.81%   |

Camera Model
------------

Camera device models

![Camera Model](./All/images/pie_chart/camera_model.svg)


| Model                                                        | Computers | Percent |
|--------------------------------------------------------------|-----------|---------|
| Chicony Integrated Camera                                    | 6         | 4.84%   |
| IMC Networks USB2.0 VGA UVC WebCam                           | 5         | 4.03%   |
| IMC Networks USB2.0 HD UVC WebCam                            | 5         | 4.03%   |
| IMC Networks Integrated Camera                               | 4         | 3.23%   |
| Realtek Integrated_Webcam_HD                                 | 3         | 2.42%   |
| Quanta HP HD Camera                                          | 3         | 2.42%   |
| Microdia Camera                                              | 3         | 2.42%   |
| Chicony HD WebCam                                            | 3         | 2.42%   |
| Z-Star Venus USB2.0 Camera                                   | 2         | 1.61%   |
| Syntek Lenovo EasyCamera                                     | 2         | 1.61%   |
| Silicon Motion WebCam SC-0311139N                            | 2         | 1.61%   |
| Realtek USB Camera                                           | 2         | 1.61%   |
| Microdia Laptop_Integrated_Webcam_HD                         | 2         | 1.61%   |
| Microdia Integrated_Webcam_HD                                | 2         | 1.61%   |
| Logitech Webcam C270                                         | 2         | 1.61%   |
| Lite-On HP HD Webcam                                         | 2         | 1.61%   |
| IMC Networks VGA UVC WebCam                                  | 2         | 1.61%   |
| Chicony USB2.0 VGA UVC WebCam                                | 2         | 1.61%   |
| Chicony Integrated Camera (1280x720@30)                      | 2         | 1.61%   |
| Chicony EasyCamera                                           | 2         | 1.61%   |
| Cheng Uei Precision Industry (Foxlink) XiaoMi USB 2.0 Webcam | 2         | 1.61%   |
| Z-Star WebCam SCB-0320N                                      | 1         | 0.81%   |
| YGTek Webcam                                                 | 1         | 0.81%   |
| Trust Full HD Webcam                                         | 1         | 0.81%   |
| Syntek Integrated Camera                                     | 1         | 0.81%   |
| Suyin HP Truevision HD                                       | 1         | 0.81%   |
| Suyin HD WebCam                                              | 1         | 0.81%   |
| Sunplus Laptop_Integrated_Webcam_FHD                         | 1         | 0.81%   |
| Sunplus Integrated_Webcam_HD                                 | 1         | 0.81%   |
| Sunplus HD WebCam                                            | 1         | 0.81%   |
| Silicon Motion WebCam SC-13HDL11939N                         | 1         | 0.81%   |
| Samsung Galaxy series, misc. (MTP mode)                      | 1         | 0.81%   |
| Samsung Galaxy (PTP mode)                                    | 1         | 0.81%   |
| Realtek USB2.0 VGA UVC WebCam                                | 1         | 0.81%   |
| Realtek TOSHIBA Web Camera                                   | 1         | 0.81%   |
| Realtek Integrated Webcam_HD                                 | 1         | 0.81%   |
| Realtek Integrated Webcam HD                                 | 1         | 0.81%   |
| Realtek HP Truevision HD                                     | 1         | 0.81%   |
| Realtek HP "Truevision HD" laptop camera                     | 1         | 0.81%   |
| Realtek HD WebCam                                            | 1         | 0.81%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./All/images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 34.62%  |
| Synaptics                  | 8         | 30.77%  |
| Shenzhen Goodix Technology | 3         | 11.54%  |
| Elan Microelectronics      | 3         | 11.54%  |
| Upek                       | 1         | 3.85%   |
| LighTuning Technology      | 1         | 3.85%   |
| AuthenTec                  | 1         | 3.85%   |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./All/images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 4         | 15.38%  |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 11.54%  |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 7.69%   |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 7.69%   |
| Validity Sensors Fingerprint scanner                       | 2         | 7.69%   |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 7.69%   |
| Elan ELAN:Fingerprint                                      | 2         | 7.69%   |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 3.85%   |
| Validity Sensors Synaptics WBDI                            | 1         | 3.85%   |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 3.85%   |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 3.85%   |
| Synaptics  WBDI                                            | 1         | 3.85%   |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 3.85%   |
| Elan ELAN:ARM-M4                                           | 1         | 3.85%   |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 3.85%   |
| Unknown                                                    | 1         | 3.85%   |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./All/images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1         | 50%     |
| O2 Micro              | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./All/images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./All/images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 139       | 72.02%  |
| 1     | 45        | 23.32%  |
| 2     | 8         | 4.15%   |
| 3     | 1         | 0.52%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./All/images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 26        | 43.33%  |
| Graphics card         | 21        | 35%     |
| Net/wireless          | 5         | 8.33%   |
| Multimedia controller | 2         | 3.33%   |
| Chipcard              | 2         | 3.33%   |
| Camera                | 2         | 3.33%   |
| Storage               | 1         | 1.67%   |
| Sound                 | 1         | 1.67%   |

