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

Total: 242

| Vendor   | Model                       | Form-Factor | Probe                                                      | Date         |
|----------|-----------------------------|-------------|------------------------------------------------------------|--------------|
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

![OS](./images/pie_chart/os_name.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| ROSA R10               | 21        | 11.54%  |
| Ubuntu 20.04           | 15        | 8.24%   |
| Ubuntu 18.04           | 14        | 7.69%   |
| ROSA R11               | 14        | 7.69%   |
| ROSA R8                | 10        | 5.49%   |
| ROSA R8.1              | 8         | 4.4%    |
| ROSA R11.1             | 8         | 4.4%    |
| OpenMandriva 4.2       | 6         | 3.3%    |
| Linux Mint 20.1        | 5         | 2.75%   |
| KDE neon 20.04         | 5         | 2.75%   |
| ROSA R9                | 4         | 2.2%    |
| Manjaro                | 4         | 2.2%    |
| Linux Mint 19.1        | 3         | 1.65%   |
| Fedora 36              | 3         | 1.65%   |
| Fedora 34              | 3         | 1.65%   |
| Arch                   | 3         | 1.65%   |
| Zorin 16               | 2         | 1.1%    |
| Ubuntu 22.04           | 2         | 1.1%    |
| Ubuntu 19.10           | 2         | 1.1%    |
| Ubuntu 16.04           | 2         | 1.1%    |
| ROSA 12.2              | 2         | 1.1%    |
| Pop!_OS 21.04          | 2         | 1.1%    |
| Pop!_OS 20.10          | 2         | 1.1%    |
| OpenMandriva 4.3       | 2         | 1.1%    |
| Linux Mint 20.2        | 2         | 1.1%    |
| Linux Mint 20          | 2         | 1.1%    |
| Linux Mint 19.3        | 2         | 1.1%    |
| BlackPanther 18.1      | 2         | 1.1%    |
| Arch Rolling           | 2         | 1.1%    |
| Ubuntu 21.10           | 1         | 0.55%   |
| Ubuntu 21.04           | 1         | 0.55%   |
| Ubuntu 19.04           | 1         | 0.55%   |
| ROSA 12.1              | 1         | 0.55%   |
| Pop!_OS 21.10          | 1         | 0.55%   |
| Pop!_OS 20.04          | 1         | 0.55%   |
| OpenMandriva 4.50      | 1         | 0.55%   |
| Manjaro 21.3.0         | 1         | 0.55%   |
| Manjaro 20.2.1         | 1         | 0.55%   |
| Manjaro 20.2           | 1         | 0.55%   |
| Manjaro 19.0.2         | 1         | 0.55%   |
| Manjaro 18.0.4         | 1         | 0.55%   |
| Linux Mint 20.3        | 1         | 0.55%   |
| Kubuntu 20.10          | 1         | 0.55%   |
| Kubuntu 20.04          | 1         | 0.55%   |
| Kali 2021.3            | 1         | 0.55%   |
| Kali 2019.3            | 1         | 0.55%   |
| Fedora 35              | 1         | 0.55%   |
| Fedora 33              | 1         | 0.55%   |
| Fedora 31              | 1         | 0.55%   |
| Endless 3.7.8          | 1         | 0.55%   |
| Endless 3.7.5          | 1         | 0.55%   |
| Endless 3.6.4          | 1         | 0.55%   |
| Endless 3.6.3          | 1         | 0.55%   |
| Endless 3.4.3-nexthw1  | 1         | 0.55%   |
| Endless 3.3.16-nexthw1 | 1         | 0.55%   |
| Debian Unstable        | 1         | 0.55%   |
| Debian 11              | 1         | 0.55%   |
| Ctlos 1.4.0            | 1         | 0.55%   |
| BuildRoot 2021.08.2    | 1         | 0.55%   |

OS Family
---------

OS without a version

![OS Family](./images/pie_chart/os_family.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| ROSA         | 63        | 36%     |
| Ubuntu       | 38        | 21.71%  |
| Linux Mint   | 15        | 8.57%   |
| OpenMandriva | 9         | 5.14%   |
| Manjaro      | 9         | 5.14%   |
| Fedora       | 9         | 5.14%   |
| Pop!_OS      | 6         | 3.43%   |
| KDE neon     | 5         | 2.86%   |
| Arch         | 5         | 2.86%   |
| Endless      | 4         | 2.29%   |
| Zorin        | 2         | 1.14%   |
| Kubuntu      | 2         | 1.14%   |
| Kali         | 2         | 1.14%   |
| Debian       | 2         | 1.14%   |
| BlackPanther | 2         | 1.14%   |
| Ctlos        | 1         | 0.57%   |
| BuildRoot    | 1         | 0.57%   |

Kernel
------

Version of the Linux kernel

![Kernel](./images/pie_chart/os_kernel.svg)


| Version                            | Computers | Percent |
|------------------------------------|-----------|---------|
| 4.9.60-nrj-desktop-1rosa-x86_64    | 10        | 5.26%   |
| 5.10.14-desktop-1omv4002           | 6         | 3.16%   |
| 4.9.20-nrj-desktop-1rosa-x86_64    | 6         | 3.16%   |
| 4.15.0-desktop-45.1rosa-x86_64     | 6         | 3.16%   |
| 4.1.34-nrj-desktop-2rosa-x86_64    | 5         | 2.63%   |
| 5.15.0-41-generic                  | 4         | 2.11%   |
| 4.9.60-nrj-desktop-1rosa-i586      | 4         | 2.11%   |
| 4.9.155-nrj-desktop-1rosa-x86_64   | 4         | 2.11%   |
| 4.15.0-desktop-68.5rosa-x86_64     | 4         | 2.11%   |
| 5.8.0-33-generic                   | 3         | 1.58%   |
| 5.10.74-generic-2rosa2021.1-x86_64 | 3         | 1.58%   |
| 5.4.32-generic-2rosa-x86_64        | 2         | 1.05%   |
| 5.4.0-48-generic                   | 2         | 1.05%   |
| 5.4.0-37-generic                   | 2         | 1.05%   |
| 5.16.7-desktop-1omv4003            | 2         | 1.05%   |
| 5.11.0-7614-generic                | 2         | 1.05%   |
| 5.11.0-41-generic                  | 2         | 1.05%   |
| 5.11.0-34-generic                  | 2         | 1.05%   |
| 5.11.0-25-generic                  | 2         | 1.05%   |
| 5.10.2-2-MANJARO                   | 2         | 1.05%   |
| 4.9.95-nrj-desktop-2rosa-x86_64    | 2         | 1.05%   |
| 4.9.41-nrj-desktop-1rosa-x86_64    | 2         | 1.05%   |
| 4.9.124-nrj-desktop-1rosa-x86_64   | 2         | 1.05%   |
| 4.15.0-desktop-47.2rosa-x86_64     | 2         | 1.05%   |
| 4.1.34-nrj-desktop-2rosa-i586      | 2         | 1.05%   |
| 4.1.25-nrj-desktop-1rosa-i586      | 2         | 1.05%   |
| 5.9.3-1-MANJARO                    | 1         | 0.53%   |
| 5.9.3-050903-generic               | 1         | 0.53%   |
| 5.8.18-100.fc31.x86_64             | 1         | 0.53%   |
| 5.8.18-1-MANJARO                   | 1         | 0.53%   |
| 5.8.0-7642-generic                 | 1         | 0.53%   |
| 5.8.0-38-generic                   | 1         | 0.53%   |
| 5.8.0-36-generic                   | 1         | 0.53%   |
| 5.8.0-25-lowlatency                | 1         | 0.53%   |
| 5.6.14-desktop-2bP                 | 1         | 0.53%   |
| 5.5.9-zen1-2-zen                   | 1         | 0.53%   |
| 5.4.83-generic-2rosa-x86_64        | 1         | 0.53%   |
| 5.4.49-nrj-desktop-1rosa-x86_64    | 1         | 0.53%   |
| 5.4.0-90-generic                   | 1         | 0.53%   |
| 5.4.0-86-generic                   | 1         | 0.53%   |
| 5.4.0-84-generic                   | 1         | 0.53%   |
| 5.4.0-77-generic                   | 1         | 0.53%   |
| 5.4.0-7634-generic                 | 1         | 0.53%   |
| 5.4.0-72-generic                   | 1         | 0.53%   |
| 5.4.0-70-generic                   | 1         | 0.53%   |
| 5.4.0-67-generic                   | 1         | 0.53%   |
| 5.4.0-58-generic                   | 1         | 0.53%   |
| 5.4.0-56-generic                   | 1         | 0.53%   |
| 5.4.0-52-generic                   | 1         | 0.53%   |
| 5.4.0-42-generic                   | 1         | 0.53%   |
| 5.4.0-40-generic                   | 1         | 0.53%   |
| 5.3.0-59-generic                   | 1         | 0.53%   |
| 5.3.0-42-generic                   | 1         | 0.53%   |
| 5.3.0-40-generic                   | 1         | 0.53%   |
| 5.3.0-28-generic                   | 1         | 0.53%   |
| 5.3.0-23-generic                   | 1         | 0.53%   |
| 5.2.0-kali2-amd64                  | 1         | 0.53%   |
| 5.18.5-201.fsync.fc36.x86_64       | 1         | 0.53%   |
| 5.18.15-arch1-1                    | 1         | 0.53%   |
| 5.18.13-200.fc36.x86_64            | 1         | 0.53%   |

Kernel Family
-------------

Linux kernel without a distro release

![Kernel Family](./images/pie_chart/os_kernel_family.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.15.0  | 25        | 13.44%  |
| 5.4.0   | 17        | 9.14%   |
| 4.9.60  | 13        | 6.99%   |
| 5.11.0  | 12        | 6.45%   |
| 5.8.0   | 7         | 3.76%   |
| 4.1.34  | 7         | 3.76%   |
| 5.10.14 | 6         | 3.23%   |
| 4.9.20  | 6         | 3.23%   |
| 5.3.0   | 5         | 2.69%   |
| 5.15.0  | 5         | 2.69%   |
| 5.13.0  | 4         | 2.15%   |
| 5.0.0   | 4         | 2.15%   |
| 4.9.155 | 4         | 2.15%   |
| 4.18.0  | 4         | 2.15%   |
| 5.10.74 | 3         | 1.61%   |
| 4.9.124 | 3         | 1.61%   |
| 4.1.38  | 3         | 1.61%   |
| 5.9.3   | 2         | 1.08%   |
| 5.8.18  | 2         | 1.08%   |
| 5.4.32  | 2         | 1.08%   |
| 5.16.7  | 2         | 1.08%   |
| 5.10.2  | 2         | 1.08%   |
| 5.10.0  | 2         | 1.08%   |
| 4.9.95  | 2         | 1.08%   |
| 4.9.9   | 2         | 1.08%   |
| 4.9.76  | 2         | 1.08%   |
| 4.9.41  | 2         | 1.08%   |
| 4.10.0  | 2         | 1.08%   |
| 4.1.25  | 2         | 1.08%   |
| 5.6.14  | 1         | 0.54%   |
| 5.5.9   | 1         | 0.54%   |
| 5.4.83  | 1         | 0.54%   |
| 5.4.49  | 1         | 0.54%   |
| 5.2.0   | 1         | 0.54%   |
| 5.18.5  | 1         | 0.54%   |
| 5.18.15 | 1         | 0.54%   |
| 5.18.13 | 1         | 0.54%   |
| 5.18.1  | 1         | 0.54%   |
| 5.17.9  | 1         | 0.54%   |
| 5.17.3  | 1         | 0.54%   |
| 5.16.9  | 1         | 0.54%   |
| 5.16.0  | 1         | 0.54%   |
| 5.15.49 | 1         | 0.54%   |
| 5.15.48 | 1         | 0.54%   |
| 5.15.2  | 1         | 0.54%   |
| 5.15.11 | 1         | 0.54%   |
| 5.14.7  | 1         | 0.54%   |
| 5.14.14 | 1         | 0.54%   |
| 5.13.10 | 1         | 0.54%   |
| 5.12.9  | 1         | 0.54%   |
| 5.12.12 | 1         | 0.54%   |
| 5.11.12 | 1         | 0.54%   |
| 5.10.53 | 1         | 0.54%   |
| 5.10.47 | 1         | 0.54%   |
| 5.10.26 | 1         | 0.54%   |
| 5.10.19 | 1         | 0.54%   |
| 5.10.13 | 1         | 0.54%   |
| 5.1.15  | 1         | 0.54%   |
| 5.0.18  | 1         | 0.54%   |
| 4.9.87  | 1         | 0.54%   |

Kernel Major Ver.
-----------------

Linux kernel major version

![Kernel Major Ver.](./images/pie_chart/os_kernel_major.svg)


| Version | Computers | Percent |
|---------|-----------|---------|
| 4.9     | 32        | 17.68%  |
| 4.15    | 25        | 13.81%  |
| 5.4     | 21        | 11.6%   |
| 5.10    | 17        | 9.39%   |
| 5.11    | 13        | 7.18%   |
| 4.1     | 12        | 6.63%   |
| 5.8     | 9         | 4.97%   |
| 5.15    | 9         | 4.97%   |
| 5.3     | 5         | 2.76%   |
| 5.13    | 5         | 2.76%   |
| 5.0     | 5         | 2.76%   |
| 5.18    | 4         | 2.21%   |
| 5.16    | 4         | 2.21%   |
| 4.18    | 4         | 2.21%   |
| 5.9     | 2         | 1.1%    |
| 5.17    | 2         | 1.1%    |
| 5.14    | 2         | 1.1%    |
| 5.12    | 2         | 1.1%    |
| 4.10    | 2         | 1.1%    |
| 5.6     | 1         | 0.55%   |
| 5.5     | 1         | 0.55%   |
| 5.2     | 1         | 0.55%   |
| 5.1     | 1         | 0.55%   |
| 4.19    | 1         | 0.55%   |
| 4.16    | 1         | 0.55%   |

Arch
----

OS architecture (x86_64, i586, etc.)

![Arch](./images/pie_chart/os_arch.svg)


| Name   | Computers | Percent |
|--------|-----------|---------|
| x86_64 | 161       | 91.48%  |
| i686   | 15        | 8.52%   |

DE
--

Desktop Environment

![DE](./images/pie_chart/os_de.svg)


| Name            | Computers | Percent |
|-----------------|-----------|---------|
| KDE4            | 45        | 25.28%  |
| GNOME           | 42        | 23.6%   |
| KDE5            | 40        | 22.47%  |
| Unknown         | 17        | 9.55%   |
| X-Cinnamon      | 11        | 6.18%   |
| XFCE            | 7         | 3.93%   |
| MATE            | 3         | 1.69%   |
| LXQt            | 3         | 1.69%   |
| KDE             | 3         | 1.69%   |
| sway            | 2         | 1.12%   |
| GNOME Flashback | 2         | 1.12%   |
| Cinnamon        | 2         | 1.12%   |
| xinitrc         | 1         | 0.56%   |

Display Server
--------------

X11 or Wayland

![Display Server](./images/pie_chart/os_display_server.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| X11     | 147       | 84%     |
| Wayland | 15        | 8.57%   |
| Unknown | 13        | 7.43%   |

Display Manager
---------------

SDDM, LightDM, etc.

![Display Manager](./images/pie_chart/os_display_manager.svg)


| Name    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 58        | 32.4%   |
| KDM     | 45        | 25.14%  |
| SDDM    | 38        | 21.23%  |
| GDM     | 20        | 11.17%  |
| TDM     | 8         | 4.47%   |
| LightDM | 6         | 3.35%   |
| GDM3    | 4         | 2.23%   |

OS Lang
-------

Language

![OS Lang](./images/pie_chart/os_lang.svg)


| Lang    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 74        | 41.81%  |
| en_US   | 47        | 26.55%  |
| ru_RU   | 37        | 20.9%   |
| ro_RO   | 7         | 3.95%   |
| C       | 4         | 2.26%   |
| en_GB   | 3         | 1.69%   |
| ru_UA   | 2         | 1.13%   |
| nl_NL   | 1         | 0.56%   |
| en_150  | 1         | 0.56%   |
| de_DE   | 1         | 0.56%   |

Boot Mode
---------

EFI or BIOS

![Boot Mode](./images/pie_chart/os_boot_mode.svg)


| Mode | Computers | Percent |
|------|-----------|---------|
| BIOS | 104       | 59.09%  |
| EFI  | 72        | 40.91%  |

Filesystem
----------

Type of filesystem

![Filesystem](./images/pie_chart/os_filesystem.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Ext4    | 118       | 67.43%  |
| Unknown | 37        | 21.14%  |
| Overlay | 11        | 6.29%   |
| Btrfs   | 7         | 4%      |
| Xfs     | 2         | 1.14%   |

Part. scheme
------------

Scheme of partitioning

![Part. scheme](./images/pie_chart/os_part_scheme.svg)


| Type    | Computers | Percent |
|---------|-----------|---------|
| Unknown | 69        | 38.76%  |
| MBR     | 60        | 33.71%  |
| GPT     | 49        | 27.53%  |

Dual Boot with Linux/BSD
------------------------

Hosting more than one Linux/BSD

![Dual Boot with Linux/BSD](./images/pie_chart/os_dual_boot.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 157       | 89.71%  |
| Yes       | 18        | 10.29%  |

Dual Boot (Win)
---------------

Hosting Linux and Windows

![Dual Boot (Win)](./images/pie_chart/os_dual_boot_win.svg)


| Dual boot | Computers | Percent |
|-----------|-----------|---------|
| No        | 126       | 71.59%  |
| Yes       | 50        | 28.41%  |

Board
-----

Vendor
------

Motherboard manufacturer

![Vendor](./images/pie_chart/node_vendor.svg)


| Name                | Computers | Percent |
|---------------------|-----------|---------|
| ASUSTek Computer    | 50        | 28.74%  |
| Hewlett-Packard     | 28        | 16.09%  |
| Lenovo              | 23        | 13.22%  |
| Dell                | 14        | 8.05%   |
| Gigabyte Technology | 13        | 7.47%   |
| Biostar             | 9         | 5.17%   |
| Acer                | 9         | 5.17%   |
| MSI                 | 6         | 3.45%   |
| ASRock              | 5         | 2.87%   |
| Toshiba             | 4         | 2.3%    |
| Samsung Electronics | 4         | 2.3%    |
| Timi                | 2         | 1.15%   |
| System76            | 1         | 0.57%   |
| Sony                | 1         | 0.57%   |
| Jumper              | 1         | 0.57%   |
| HUAWEI              | 1         | 0.57%   |
| Gateway             | 1         | 0.57%   |
| ECS                 | 1         | 0.57%   |
| Chuwi               | 1         | 0.57%   |

Model
-----

Motherboard model

![Model](./images/pie_chart/node_model.svg)


| Name                                        | Computers | Percent |
|---------------------------------------------|-----------|---------|
| ASUS VivoBook_ASUSLaptop X521IA_D533IA      | 3         | 1.72%   |
| Samsung RV413/RV513                         | 2         | 1.15%   |
| Lenovo Legion Y530-15ICH 81FV               | 2         | 1.15%   |
| HP ProBook 450 G7                           | 2         | 1.15%   |
| HP Compaq Presario CQ60                     | 2         | 1.15%   |
| ASUS VivoBook S15 X510UF                    | 2         | 1.15%   |
| ASUS H110M-R                                | 2         | 1.15%   |
| ASUS All Series                             | 2         | 1.15%   |
| Toshiba TECRA Z40-B                         | 1         | 0.57%   |
| Toshiba Satellite Pro S300L                 | 1         | 0.57%   |
| Toshiba Satellite C55D-A                    | 1         | 0.57%   |
| Toshiba Satellite A210                      | 1         | 0.57%   |
| Timi TM1701                                 | 1         | 0.57%   |
| Timi A35S                                   | 1         | 0.57%   |
| System76 Adder WS                           | 1         | 0.57%   |
| Sony VPCEB1J8E                              | 1         | 0.57%   |
| Samsung R517/R717                           | 1         | 0.57%   |
| Samsung 300E4C/300E5C/300E7C                | 1         | 0.57%   |
| MSI Pro 3130 Microtower PC                  | 1         | 0.57%   |
| MSI MS-7695                                 | 1         | 0.57%   |
| MSI MS-7592                                 | 1         | 0.57%   |
| MSI MS-7529                                 | 1         | 0.57%   |
| MSI MS-7309                                 | 1         | 0.57%   |
| MSI CR610                                   | 1         | 0.57%   |
| Lenovo Yoga 730-15IKB 81CU                  | 1         | 0.57%   |
| Lenovo Y520-15IKBN 80WK                     | 1         | 0.57%   |
| Lenovo V580 20147                           | 1         | 0.57%   |
| Lenovo ThinkPad Yoga 11e 3rd Gen 20G8S0MG00 | 1         | 0.57%   |
| Lenovo ThinkPad X240 20AL0067RT             | 1         | 0.57%   |
| Lenovo ThinkPad X131e 33711T0               | 1         | 0.57%   |
| Lenovo ThinkPad X1 Carbon 5th 20HR002MMX    | 1         | 0.57%   |
| Lenovo ThinkPad T440 20B7S1N809             | 1         | 0.57%   |
| Lenovo ThinkPad E15 Gen 3 20YG004BRT        | 1         | 0.57%   |
| Lenovo ThinkPad E15 Gen 2 20TD003TRT        | 1         | 0.57%   |
| Lenovo ThinkPad E15 Gen 2 20TD002NRA        | 1         | 0.57%   |
| Lenovo Legion 5 15IMH05 82AU                | 1         | 0.57%   |
| Lenovo IdeaPad L340-15API 81LW              | 1         | 0.57%   |
| Lenovo IdeaPad Gaming 3 15ARH05 82EY        | 1         | 0.57%   |
| Lenovo IdeaPad 5 15ARE05 81YQ               | 1         | 0.57%   |
| Lenovo IdeaPad 330S-14IKB 81F4              | 1         | 0.57%   |
| Lenovo IdeaPad 330-15IKB 81DE               | 1         | 0.57%   |
| Lenovo IdeaPad 330-15IGM 81D1               | 1         | 0.57%   |
| Lenovo IdeaPad 130-15IKB 81H7               | 1         | 0.57%   |
| Lenovo IdeaPad 100-15IBY 80MJ               | 1         | 0.57%   |
| Lenovo G710 20252                           | 1         | 0.57%   |
| Jumper EZbook                               | 1         | 0.57%   |
| HUAWEI NBLK-WAX9X                           | 1         | 0.57%   |
| HP ZBook Fury 15 G7 Mobile Workstation      | 1         | 0.57%   |
| HP ProLiant DL360 G5                        | 1         | 0.57%   |
| HP ProDesk 490 G2 MT                        | 1         | 0.57%   |
| HP ProDesk 400 G4 MT                        | 1         | 0.57%   |
| HP ProBook 650 G2                           | 1         | 0.57%   |
| HP ProBook 6465b                            | 1         | 0.57%   |
| HP ProBook 470 G2                           | 1         | 0.57%   |
| HP ProBook 450 G6                           | 1         | 0.57%   |
| HP Pavilion Laptop 15-eh1xxx                | 1         | 0.57%   |
| HP Pavilion dv7                             | 1         | 0.57%   |
| HP Pavilion 17                              | 1         | 0.57%   |
| HP Laptop 15-dw0xxx                         | 1         | 0.57%   |
| HP Laptop 15-da1xxx                         | 1         | 0.57%   |

Model Family
------------

Motherboard model prefix

![Model Family](./images/pie_chart/node_model_family.svg)


| Name                   | Computers | Percent |
|------------------------|-----------|---------|
| Lenovo ThinkPad        | 8         | 4.6%    |
| Lenovo IdeaPad         | 8         | 4.6%    |
| Acer Aspire            | 7         | 4.02%   |
| HP ProBook             | 6         | 3.45%   |
| ASUS VivoBook          | 6         | 3.45%   |
| Dell Latitude          | 5         | 2.87%   |
| Dell Inspiron          | 5         | 2.87%   |
| HP EliteBook           | 4         | 2.3%    |
| HP Compaq              | 4         | 2.3%    |
| Toshiba Satellite      | 3         | 1.72%   |
| Lenovo Legion          | 3         | 1.72%   |
| HP Pavilion            | 3         | 1.72%   |
| ASUS PRIME             | 3         | 1.72%   |
| Samsung RV413          | 2         | 1.15%   |
| HP ProDesk             | 2         | 1.15%   |
| HP Laptop              | 2         | 1.15%   |
| HP ENVY                | 2         | 1.15%   |
| ASUS TUF               | 2         | 1.15%   |
| ASUS M5A78L-M          | 2         | 1.15%   |
| ASUS H110M-R           | 2         | 1.15%   |
| ASUS All               | 2         | 1.15%   |
| Toshiba TECRA          | 1         | 0.57%   |
| Timi TM1701            | 1         | 0.57%   |
| Timi A35S              | 1         | 0.57%   |
| System76 Adder         | 1         | 0.57%   |
| Sony VPCEB1J8E         | 1         | 0.57%   |
| Samsung R517           | 1         | 0.57%   |
| Samsung 300E4C         | 1         | 0.57%   |
| MSI Pro                | 1         | 0.57%   |
| MSI MS-7695            | 1         | 0.57%   |
| MSI MS-7592            | 1         | 0.57%   |
| MSI MS-7529            | 1         | 0.57%   |
| MSI MS-7309            | 1         | 0.57%   |
| MSI CR610              | 1         | 0.57%   |
| Lenovo Yoga            | 1         | 0.57%   |
| Lenovo Y520-15IKBN     | 1         | 0.57%   |
| Lenovo V580            | 1         | 0.57%   |
| Lenovo G710            | 1         | 0.57%   |
| Jumper EZbook          | 1         | 0.57%   |
| HUAWEI NBLK-WAX9X      | 1         | 0.57%   |
| HP ZBook               | 1         | 0.57%   |
| HP ProLiant            | 1         | 0.57%   |
| HP 635                 | 1         | 0.57%   |
| HP 550                 | 1         | 0.57%   |
| Gigabyte Z690          | 1         | 0.57%   |
| Gigabyte X570          | 1         | 0.57%   |
| Gigabyte P41-ES3G      | 1         | 0.57%   |
| Gigabyte H81M-S2PV     | 1         | 0.57%   |
| Gigabyte H81M-HD3      | 1         | 0.57%   |
| Gigabyte H61M-S2-B3    | 1         | 0.57%   |
| Gigabyte H61M-S1       | 1         | 0.57%   |
| Gigabyte GA-970A-DS3   | 1         | 0.57%   |
| Gigabyte GA-880GM-USB3 | 1         | 0.57%   |
| Gigabyte G41M-ES2L     | 1         | 0.57%   |
| Gigabyte EP43-UD3L     | 1         | 0.57%   |
| Gigabyte B460MDS3HV2   | 1         | 0.57%   |
| Gigabyte B450M         | 1         | 0.57%   |
| Gateway NV55S          | 1         | 0.57%   |
| ECS GeForce7050M-M     | 1         | 0.57%   |
| Dell XPS               | 1         | 0.57%   |

MFG Year
--------

Motherboard manufacture year

![MFG Year](./images/pie_chart/node_year.svg)


| Year | Computers | Percent |
|------|-----------|---------|
| 2018 | 19        | 10.92%  |
| 2012 | 17        | 9.77%   |
| 2011 | 17        | 9.77%   |
| 2019 | 15        | 8.62%   |
| 2009 | 14        | 8.05%   |
| 2017 | 13        | 7.47%   |
| 2013 | 13        | 7.47%   |
| 2016 | 11        | 6.32%   |
| 2021 | 10        | 5.75%   |
| 2020 | 10        | 5.75%   |
| 2010 | 9         | 5.17%   |
| 2015 | 7         | 4.02%   |
| 2014 | 5         | 2.87%   |
| 2008 | 5         | 2.87%   |
| 2007 | 5         | 2.87%   |
| 2006 | 2         | 1.15%   |
| 2022 | 1         | 0.57%   |
| 2005 | 1         | 0.57%   |

Form Factor
-----------

Physical design of the computer

![Form Factor](./images/pie_chart/node_formfactor.svg)


| Name        | Computers | Percent |
|-------------|-----------|---------|
| Notebook    | 106       | 60.92%  |
| Desktop     | 64        | 36.78%  |
| All in one  | 2         | 1.15%   |
| Convertible | 1         | 0.57%   |
| Server      | 1         | 0.57%   |

Secure Boot
-----------

Enabled or disabled

![Secure Boot](./images/pie_chart/node_secureboot.svg)


| State    | Computers | Percent |
|----------|-----------|---------|
| Disabled | 165       | 94.83%  |
| Enabled  | 9         | 5.17%   |

Coreboot
--------

Have coreboot on board

![Coreboot](./images/pie_chart/node_coreboot.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 174       | 100%    |

RAM Size
--------

Total RAM memory

![RAM Size](./images/pie_chart/node_ram_total.svg)


| Size in GB  | Computers | Percent |
|-------------|-----------|---------|
| 3.01-4.0    | 55        | 31.43%  |
| 4.01-8.0    | 37        | 21.14%  |
| 8.01-16.0   | 33        | 18.86%  |
| 16.01-24.0  | 21        | 12%     |
| 32.01-64.0  | 10        | 5.71%   |
| 1.01-2.0    | 9         | 5.14%   |
| 2.01-3.0    | 8         | 4.57%   |
| 64.01-256.0 | 1         | 0.57%   |
| 0.51-1.0    | 1         | 0.57%   |

RAM Used
--------

Used RAM memory

![RAM Used](./images/pie_chart/node_ram_used.svg)


| Used GB    | Computers | Percent |
|------------|-----------|---------|
| 1.01-2.0   | 71        | 37.97%  |
| 0.51-1.0   | 41        | 21.93%  |
| 2.01-3.0   | 29        | 15.51%  |
| 4.01-8.0   | 23        | 12.3%   |
| 3.01-4.0   | 13        | 6.95%   |
| 8.01-16.0  | 5         | 2.67%   |
| 0.01-0.5   | 3         | 1.6%    |
| 24.01-32.0 | 1         | 0.53%   |
| 16.01-24.0 | 1         | 0.53%   |

Total Drives
------------

Number of drives on board

![Total Drives](./images/pie_chart/node_total_drives.svg)


| Drives | Computers | Percent |
|--------|-----------|---------|
| 1      | 124       | 70.86%  |
| 2      | 36        | 20.57%  |
| 3      | 11        | 6.29%   |
| 4      | 3         | 1.71%   |
| 0      | 1         | 0.57%   |

Has CD-ROM
----------

Has CD-ROM on board

![Has CD-ROM](./images/pie_chart/node_has_cdrom.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 108       | 62.07%  |
| Yes       | 66        | 37.93%  |

Has Ethernet
------------

Has Ethernet on board

![Has Ethernet](./images/pie_chart/node_has_ethernet.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 159       | 90.86%  |
| No        | 16        | 9.14%   |

Has WiFi
--------

Has WiFi module

![Has WiFi](./images/pie_chart/node_has_wifi.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| Yes       | 121       | 69.54%  |
| No        | 53        | 30.46%  |

Has Bluetooth
-------------

Has Bluetooth module

![Has Bluetooth](./images/pie_chart/node_has_bluetooth.svg)


| Presented | Computers | Percent |
|-----------|-----------|---------|
| No        | 88        | 50.29%  |
| Yes       | 87        | 49.71%  |

Location
--------

Country
-------

Geographic location (country)

![Country](./images/pie_chart/node_location.svg)


| Country | Computers | Percent |
|---------|-----------|---------|
| Moldova | 174       | 100%    |

City
----

Geographic location (city)

![City](./images/pie_chart/node_city.svg)


| City            | Computers | Percent |
|-----------------|-----------|---------|
| Chisinau        | 100       | 56.5%   |
| Tiraspol        | 33        | 18.64%  |
| Straseni        | 5         | 2.82%   |
| Tighina         | 4         | 2.26%   |
| Bălţi         | 4         | 2.26%   |
| Hincesti        | 3         | 1.69%   |
| Soroca          | 2         | 1.13%   |
| Ialoveni        | 2         | 1.13%   |
| Căușeni       | 2         | 1.13%   |
| Tintareni       | 1         | 0.56%   |
| Soldanesti      | 1         | 0.56%   |
| Sofia           | 1         | 0.56%   |
| Singera         | 1         | 0.56%   |
| Rîbniţa       | 1         | 0.56%   |
| Rezina          | 1         | 0.56%   |
| Rautel          | 1         | 0.56%   |
| Prajila         | 1         | 0.56%   |
| Pociumbeni      | 1         | 0.56%   |
| Lapusna         | 1         | 0.56%   |
| Gangura         | 1         | 0.56%   |
| Floresti        | 1         | 0.56%   |
| Floreni         | 1         | 0.56%   |
| Edineţ         | 1         | 0.56%   |
| Drochia         | 1         | 0.56%   |
| Donduseni       | 1         | 0.56%   |
| Criuleni        | 1         | 0.56%   |
| Crasnoarmeiscoe | 1         | 0.56%   |
| Cojusna         | 1         | 0.56%   |
| Cenac           | 1         | 0.56%   |
| Cazanesti       | 1         | 0.56%   |
| Cahul           | 1         | 0.56%   |

Drives
------

Drive Vendor
------------

Hard drive vendors

![Drive Vendor](./images/pie_chart/drive_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 48        | 58     | 20.69%  |
| Seagate             | 33        | 37     | 14.22%  |
| WDC                 | 32        | 34     | 13.79%  |
| Toshiba             | 24        | 29     | 10.34%  |
| Hitachi             | 16        | 18     | 6.9%    |
| Kingston            | 12        | 15     | 5.17%   |
| SanDisk             | 7         | 7      | 3.02%   |
| Transcend           | 5         | 5      | 2.16%   |
| SPCC                | 5         | 6      | 2.16%   |
| SK hynix            | 5         | 5      | 2.16%   |
| Micron Technology   | 5         | 7      | 2.16%   |
| HGST                | 4         | 4      | 1.72%   |
| Apacer              | 4         | 4      | 1.72%   |
| Unknown             | 3         | 3      | 1.29%   |
| Maxtor              | 3         | 4      | 1.29%   |
| Intel               | 3         | 5      | 1.29%   |
| Phison              | 2         | 3      | 0.86%   |
| Fujitsu             | 2         | 2      | 0.86%   |
| A-DATA Technology   | 2         | 2      | 0.86%   |
| ZOTAC               | 1         | 3      | 0.43%   |
| XPG                 | 1         | 1      | 0.43%   |
| Team                | 1         | 1      | 0.43%   |
| Solid State Storage | 1         | 1      | 0.43%   |
| Patriot             | 1         | 1      | 0.43%   |
| OCZ                 | 1         | 1      | 0.43%   |
| Netac               | 1         | 1      | 0.43%   |
| LITEONIT            | 1         | 1      | 0.43%   |
| Leven               | 1         | 1      | 0.43%   |
| Lenovo              | 1         | 1      | 0.43%   |
| KIOXIA              | 1         | 1      | 0.43%   |
| Intenso             | 1         | 1      | 0.43%   |
| GOODRAM             | 1         | 1      | 0.43%   |
| Goldkey             | 1         | 1      | 0.43%   |
| Crucial             | 1         | 1      | 0.43%   |
| CHN25SATAS1         | 1         | 1      | 0.43%   |
| China               | 1         | 1      | 0.43%   |

Drive Model
-----------

Hard drive models

![Drive Model](./images/pie_chart/drive_model.svg)


| Model                               | Computers | Percent |
|-------------------------------------|-----------|---------|
| Kingston SHFS37A120G 120GB SSD      | 7         | 2.94%   |
| Samsung NVMe SSD Drive 512GB        | 6         | 2.52%   |
| Toshiba MQ01ABD100 1TB              | 4         | 1.68%   |
| Toshiba DT01ACA050 500GB            | 4         | 1.68%   |
| Seagate ST500LT012-9WS142 500GB     | 4         | 1.68%   |
| Seagate ST1000LM035-1RK172 1TB      | 4         | 1.68%   |
| Samsung SSD 860 EVO 500GB           | 4         | 1.68%   |
| Toshiba DT01ACA100 1TB              | 3         | 1.26%   |
| SanDisk NVMe SSD Drive 512GB        | 3         | 1.26%   |
| Samsung HD502HJ 500GB               | 3         | 1.26%   |
| Micron 1100_MTFDDAV256TBN 256GB SSD | 3         | 1.26%   |
| Hitachi HTS543232A7A384 320GB       | 3         | 1.26%   |
| WDC WD5000AZRX-00A8LB0 500GB        | 2         | 0.84%   |
| WDC WD10SPZX-24Z10T0 1TB            | 2         | 0.84%   |
| Transcend TS64GSSD370S 64GB         | 2         | 0.84%   |
| Toshiba MQ04ABF100 1TB              | 2         | 0.84%   |
| Toshiba MQ01ACF032 320GB            | 2         | 0.84%   |
| Toshiba MQ01ABF050 500GB            | 2         | 0.84%   |
| Toshiba HDWD110 1TB                 | 2         | 0.84%   |
| SPCC Solid State Disk 128GB         | 2         | 0.84%   |
| SK hynix NVMe SSD Drive 256GB       | 2         | 0.84%   |
| Seagate ST500DM002-1BD142 500GB     | 2         | 0.84%   |
| Seagate ST4000VM000-2AF166 4TB      | 2         | 0.84%   |
| Seagate ST2000DM008-2FR102 2TB      | 2         | 0.84%   |
| Seagate ST1000DL002-9TT153 1TB      | 2         | 0.84%   |
| SanDisk SD7UB3Q256G1001 256GB SSD   | 2         | 0.84%   |
| Samsung NVMe SSD Drive 256GB        | 2         | 0.84%   |
| Samsung HD251HJ 249GB               | 2         | 0.84%   |
| Samsung HD082GJ 80GB                | 2         | 0.84%   |
| Intel NVMe SSD Drive 512GB          | 2         | 0.84%   |
| Hitachi HTS547575A9E384 752GB       | 2         | 0.84%   |
| Hitachi HTS542525K9SA00 250GB       | 2         | 0.84%   |
| Apacer AS340 240GB SSD              | 2         | 0.84%   |
| ZOTAC ZTSSD-S11-240G-P 240GB        | 1         | 0.42%   |
| XPG NVMe SSD Drive 512GB            | 1         | 0.42%   |
| WDC WDS512G1X0C-00ENX0 512GB        | 1         | 0.42%   |
| WDC WD62PURZ-85B3AY0 6TB            | 1         | 0.42%   |
| WDC WD5000LPVX-80V0TT0 500GB        | 1         | 0.42%   |
| WDC WD5000LPVX-75V0TT0 500GB        | 1         | 0.42%   |
| WDC WD5000LPCX-75VHAT1 500GB        | 1         | 0.42%   |
| WDC WD5000BPVT-08HXZT3 500GB        | 1         | 0.42%   |
| WDC WD5000BEVT-22A0RT0 500GB        | 1         | 0.42%   |
| WDC WD5000AZRZ-00HTKB0 500GB        | 1         | 0.42%   |
| WDC WD5000AUDX-63WNHY0 500GB        | 1         | 0.42%   |
| WDC WD5000AAKX-08ERMA0 500GB        | 1         | 0.42%   |
| WDC WD5000AAKS-75V0A0 500GB         | 1         | 0.42%   |
| WDC WD5000AAKS-00WWPA0 500GB        | 1         | 0.42%   |
| WDC WD5000AAJS-00A8B0 500GB         | 1         | 0.42%   |
| WDC WD5000AADS-56S9B1 500GB         | 1         | 0.42%   |
| WDC WD3200BPVT-80JJ5T0 320GB        | 1         | 0.42%   |
| WDC WD3200BPVT-24ZEST0 320GB        | 1         | 0.42%   |
| WDC WD3200BEVT-63ZCT0 320GB         | 1         | 0.42%   |
| WDC WD3200BEVT-22A23T0 320GB        | 1         | 0.42%   |
| WDC WD3200BEVT-00ZCT0 320GB         | 1         | 0.42%   |
| WDC WD3200AVJS-63B6A0 320GB         | 1         | 0.42%   |
| WDC WD2500AAKX-00U6AA0 250GB        | 1         | 0.42%   |
| WDC WD20EZAZ-00GGJB0 2TB            | 1         | 0.42%   |
| WDC WD200EB-00CPF0 20GB             | 1         | 0.42%   |
| WDC WD1600BEVS-07RST0 160GB         | 1         | 0.42%   |
| WDC WD10SPZX-24Z10 1TB              | 1         | 0.42%   |

HDD Vendor
----------

Hard disk drive vendors

![HDD Vendor](./images/pie_chart/drive_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 33        | 37     | 25.78%  |
| WDC                 | 31        | 33     | 24.22%  |
| Toshiba             | 21        | 26     | 16.41%  |
| Samsung Electronics | 17        | 20     | 13.28%  |
| Hitachi             | 16        | 18     | 12.5%   |
| HGST                | 4         | 4      | 3.13%   |
| Maxtor              | 3         | 4      | 2.34%   |
| Fujitsu             | 2         | 2      | 1.56%   |
| Unknown             | 1         | 1      | 0.78%   |

SSD Vendor
----------

Solid state drive vendors

![SSD Vendor](./images/pie_chart/drive_ssd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 11        | 14     | 18.97%  |
| Kingston            | 11        | 14     | 18.97%  |
| Transcend           | 5         | 5      | 8.62%   |
| SPCC                | 5         | 6      | 8.62%   |
| SanDisk             | 4         | 4      | 6.9%    |
| Apacer              | 4         | 4      | 6.9%    |
| Micron Technology   | 3         | 3      | 5.17%   |
| ZOTAC               | 1         | 3      | 1.72%   |
| Toshiba             | 1         | 1      | 1.72%   |
| Team                | 1         | 1      | 1.72%   |
| Patriot             | 1         | 1      | 1.72%   |
| OCZ                 | 1         | 1      | 1.72%   |
| Netac               | 1         | 1      | 1.72%   |
| LITEONIT            | 1         | 1      | 1.72%   |
| Leven               | 1         | 1      | 1.72%   |
| Intenso             | 1         | 1      | 1.72%   |
| GOODRAM             | 1         | 1      | 1.72%   |
| Goldkey             | 1         | 1      | 1.72%   |
| Crucial             | 1         | 1      | 1.72%   |
| CHN25SATAS1         | 1         | 1      | 1.72%   |
| China               | 1         | 1      | 1.72%   |
| A-DATA Technology   | 1         | 1      | 1.72%   |

Drive Kind
----------

HDD or SSD

![Drive Kind](./images/pie_chart/drive_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 110       | 145    | 53.14%  |
| SSD  | 54        | 67     | 26.09%  |
| NVMe | 41        | 53     | 19.81%  |
| MMC  | 2         | 2      | 0.97%   |

Drive Connector
---------------

SATA, SAS, NVMe, etc.

![Drive Connector](./images/pie_chart/drive_bus.svg)


| Type | Computers | Drives | Percent |
|------|-----------|--------|---------|
| SATA | 140       | 211    | 76.09%  |
| NVMe | 41        | 53     | 22.28%  |
| MMC  | 2         | 2      | 1.09%   |
| SAS  | 1         | 1      | 0.54%   |

Drive Size
----------

Size of hard drive

![Drive Size](./images/pie_chart/drive_size.svg)


| Size in TB | Computers | Drives | Percent |
|------------|-----------|--------|---------|
| 0.01-0.5   | 115       | 162    | 72.78%  |
| 0.51-1.0   | 33        | 40     | 20.89%  |
| 1.01-2.0   | 6         | 6      | 3.8%    |
| 3.01-4.0   | 3         | 3      | 1.9%    |
| 4.01-10.0  | 1         | 1      | 0.63%   |

Space Total
-----------

Amount of disk space available on the file system

![Space Total](./images/pie_chart/drive_space_total.svg)


| Size in GB     | Computers | Percent |
|----------------|-----------|---------|
| 101-250        | 52        | 28.73%  |
| 251-500        | 49        | 27.07%  |
| 501-1000       | 21        | 11.6%   |
| 51-100         | 21        | 11.6%   |
| 1-20           | 15        | 8.29%   |
| 21-50          | 8         | 4.42%   |
| Unknown        | 6         | 3.31%   |
| 1001-2000      | 5         | 2.76%   |
| More than 3000 | 2         | 1.1%    |
| 2001-3000      | 2         | 1.1%    |

Space Used
----------

Amount of used disk space

![Space Used](./images/pie_chart/drive_space_used.svg)


| Used GB        | Computers | Percent |
|----------------|-----------|---------|
| 1-20           | 86        | 46.49%  |
| 21-50          | 31        | 16.76%  |
| 51-100         | 24        | 12.97%  |
| 101-250        | 16        | 8.65%   |
| 251-500        | 12        | 6.49%   |
| 501-1000       | 7         | 3.78%   |
| Unknown        | 6         | 3.24%   |
| 1001-2000      | 2         | 1.08%   |
| More than 3000 | 1         | 0.54%   |

Malfunc. Drives
---------------

Drive models with a malfunction

![Malfunc. Drives](./images/pie_chart/drive_malfunc.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| Seagate ST500LT012-9WS142 500GB   | 3         | 3      | 7.32%   |
| Samsung Electronics HD082GJ 80GB  | 2         | 2      | 4.88%   |
| Kingston SHFS37A120G 120GB SSD    | 2         | 4      | 4.88%   |
| Hitachi HTS547575A9E384 752GB     | 2         | 2      | 4.88%   |
| WDC WD5000AAKX-08ERMA0 500GB      | 1         | 1      | 2.44%   |
| WDC WD5000AAKS-75V0A0 500GB       | 1         | 1      | 2.44%   |
| WDC WD5000AAKS-00WWPA0 500GB      | 1         | 1      | 2.44%   |
| WDC WD5000AADS-56S9B1 500GB       | 1         | 1      | 2.44%   |
| WDC WD3200BEVT-22A23T0 320GB      | 1         | 1      | 2.44%   |
| WDC WD2500AAKX-00U6AA0 250GB      | 1         | 1      | 2.44%   |
| WDC WD1600BEVS-07RST0 160GB       | 1         | 1      | 2.44%   |
| Toshiba MQ01ABD050 500GB          | 1         | 1      | 2.44%   |
| Toshiba DT01ACA050 500GB          | 1         | 1      | 2.44%   |
| Team L5 LITE SSD 240GB            | 1         | 1      | 2.44%   |
| SPCC SSD162 120GB                 | 1         | 1      | 2.44%   |
| SPCC Solid State Disk 56GB        | 1         | 2      | 2.44%   |
| Seagate ST9500325AS 500GB         | 1         | 1      | 2.44%   |
| Seagate ST3500418AS 500GB         | 1         | 1      | 2.44%   |
| Seagate ST320DM001 HD322GJ 320GB  | 1         | 1      | 2.44%   |
| Seagate ST3160023A 160GB          | 1         | 1      | 2.44%   |
| Seagate ST31000340NS 1TB          | 1         | 1      | 2.44%   |
| Seagate ST1000LM035-1RK172 1TB    | 1         | 1      | 2.44%   |
| Seagate ST1000DL002-9TT153 1TB    | 1         | 1      | 2.44%   |
| SanDisk SD7UB3Q256G1001 256GB SSD | 1         | 1      | 2.44%   |
| Samsung Electronics HD753LJ 752GB | 1         | 1      | 2.44%   |
| Samsung Electronics HD080HJ/ 80GB | 1         | 1      | 2.44%   |
| Maxtor STM380215AS 80GB           | 1         | 1      | 2.44%   |
| Maxtor STM3160811AS 160GB         | 1         | 1      | 2.44%   |
| Maxtor STM3160211AS 160GB         | 1         | 1      | 2.44%   |
| Maxtor 4R120L0 128GB              | 1         | 1      | 2.44%   |
| Hitachi HTS545050B9A300 500GB     | 1         | 1      | 2.44%   |
| Hitachi HTS545025B9A300 250GB     | 1         | 1      | 2.44%   |
| Hitachi HDP725050GLA360 500GB     | 1         | 1      | 2.44%   |
| Hitachi HDP725025GLA380 250GB     | 1         | 2      | 2.44%   |
| Fujitsu MHW2080BH PL 80GB         | 1         | 1      | 2.44%   |
| A-DATA Technology SX900 256GB SSD | 1         | 1      | 2.44%   |

Malfunc. Drive Vendor
---------------------

Vendors of faulty drives

![Malfunc. Drive Vendor](./images/pie_chart/drive_malfunc_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 25%     |
| WDC                 | 7         | 7      | 17.5%   |
| Hitachi             | 6         | 7      | 15%     |
| Samsung Electronics | 4         | 4      | 10%     |
| Maxtor              | 3         | 4      | 7.5%    |
| Toshiba             | 2         | 2      | 5%      |
| SPCC                | 2         | 3      | 5%      |
| Kingston            | 2         | 4      | 5%      |
| Team                | 1         | 1      | 2.5%    |
| SanDisk             | 1         | 1      | 2.5%    |
| Fujitsu             | 1         | 1      | 2.5%    |
| A-DATA Technology   | 1         | 1      | 2.5%    |

Malfunc. HDD Vendor
-------------------

Vendors of faulty HDD drives

![Malfunc. HDD Vendor](./images/pie_chart/drive_malfunc_hdd_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Seagate             | 10        | 10     | 30.3%   |
| WDC                 | 7         | 7      | 21.21%  |
| Hitachi             | 6         | 7      | 18.18%  |
| Samsung Electronics | 4         | 4      | 12.12%  |
| Maxtor              | 3         | 4      | 9.09%   |
| Toshiba             | 2         | 2      | 6.06%   |
| Fujitsu             | 1         | 1      | 3.03%   |

Malfunc. Drive Kind
-------------------

Kinds of faulty drives

![Malfunc. Drive Kind](./images/pie_chart/drive_malfunc_kind.svg)


| Kind | Computers | Drives | Percent |
|------|-----------|--------|---------|
| HDD  | 31        | 35     | 81.58%  |
| SSD  | 7         | 10     | 18.42%  |

Failed Drives
-------------

Failed drive models

![Failed Drives](./images/pie_chart/drive_failed.svg)


| Model                             | Computers | Drives | Percent |
|-----------------------------------|-----------|--------|---------|
| WDC WD3200BPVT-24ZEST0 320GB      | 1         | 1      | 25%     |
| Seagate ST9250315AS 250GB         | 1         | 1      | 25%     |
| Samsung Electronics HD502HJ 500GB | 1         | 1      | 25%     |
| Samsung Electronics HD322GJ 320GB | 1         | 2      | 25%     |

Failed Drive Vendor
-------------------

Failed drive vendors

![Failed Drive Vendor](./images/pie_chart/drive_failed_vendor.svg)


| Vendor              | Computers | Drives | Percent |
|---------------------|-----------|--------|---------|
| Samsung Electronics | 2         | 3      | 50%     |
| WDC                 | 1         | 1      | 25%     |
| Seagate             | 1         | 1      | 25%     |

Drive Status
------------

Number of failed and malfunc. drives

![Drive Status](./images/pie_chart/drive_status.svg)


| Status   | Computers | Drives | Percent |
|----------|-----------|--------|---------|
| Works    | 87        | 129    | 45.31%  |
| Detected | 63        | 88     | 32.81%  |
| Malfunc  | 38        | 45     | 19.79%  |
| Failed   | 4         | 5      | 2.08%   |

Storage controller
------------------

Storage Vendor
--------------

Storage controller vendors

![Storage Vendor](./images/pie_chart/storage_vendor.svg)


| Vendor                         | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel                          | 109       | 50.93%  |
| AMD                            | 47        | 21.96%  |
| Samsung Electronics            | 20        | 9.35%   |
| Nvidia                         | 8         | 3.74%   |
| SK hynix                       | 5         | 2.34%   |
| JMicron Technology             | 5         | 2.34%   |
| SanDisk                        | 4         | 1.87%   |
| Toshiba America Info Systems   | 2         | 0.93%   |
| Phison Electronics             | 2         | 0.93%   |
| Micron Technology              | 2         | 0.93%   |
| ASMedia Technology             | 2         | 0.93%   |
| ADATA Technology               | 2         | 0.93%   |
| Solid State Storage Technology | 1         | 0.47%   |
| Marvell Technology Group       | 1         | 0.47%   |
| Lenovo                         | 1         | 0.47%   |
| KIOXIA                         | 1         | 0.47%   |
| Kingston Technology Company    | 1         | 0.47%   |
| Hewlett-Packard                | 1         | 0.47%   |

Storage Model
-------------

Storage controller models

![Storage Model](./images/pie_chart/storage_model.svg)


| Model                                                                                   | Computers | Percent |
|-----------------------------------------------------------------------------------------|-----------|---------|
| AMD FCH SATA Controller [AHCI mode]                                                     | 22        | 8.4%    |
| AMD SB7x0/SB8x0/SB9x0 IDE Controller                                                    | 13        | 4.96%   |
| Intel Sunrise Point-LP SATA Controller [AHCI mode]                                      | 11        | 4.2%    |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [IDE mode]                                        | 11        | 4.2%    |
| Samsung NVMe SSD Controller 980                                                         | 10        | 3.82%   |
| AMD SB7x0/SB8x0/SB9x0 SATA Controller [AHCI mode]                                       | 8         | 3.05%   |
| Intel 8 Series/C220 Series Chipset Family 6-port SATA Controller 1 [AHCI mode]          | 7         | 2.67%   |
| Intel 7 Series Chipset Family 6-port SATA Controller [AHCI mode]                        | 7         | 2.67%   |
| Samsung NVMe SSD Controller SM981/PM981/PM983                                           | 6         | 2.29%   |
| Intel Cannon Lake Mobile PCH SATA AHCI Controller                                       | 6         | 2.29%   |
| Intel 82801 Mobile SATA Controller [RAID mode]                                          | 6         | 2.29%   |
| Intel Q170/Q150/B150/H170/H110/Z170/CM236 Chipset SATA Controller [AHCI Mode]           | 5         | 1.91%   |
| Intel NM10/ICH7 Family SATA Controller [IDE mode]                                       | 5         | 1.91%   |
| Samsung NVMe SSD Controller SM961/PM961/SM963                                           | 4         | 1.53%   |
| Intel Comet Lake SATA AHCI Controller                                                   | 4         | 1.53%   |
| Intel Celeron/Pentium Silver Processor SATA Controller                                  | 4         | 1.53%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series SATA Controller        | 4         | 1.53%   |
| Intel 82801G (ICH7 Family) IDE Controller                                               | 4         | 1.53%   |
| Intel 8 Series SATA Controller 1 [AHCI mode]                                            | 4         | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 4-5) | 4         | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family Desktop SATA Controller (IDE mode, ports 0-3) | 4         | 1.53%   |
| Intel 6 Series/C200 Series Chipset Family 6 port Mobile SATA AHCI Controller            | 4         | 1.53%   |
| Nvidia MCP78S [GeForce 8200] SATA Controller (non-AHCI mode)                            | 3         | 1.15%   |
| Nvidia MCP78S [GeForce 8200] IDE                                                        | 3         | 1.15%   |
| Nvidia MCP61 SATA Controller                                                            | 3         | 1.15%   |
| Nvidia MCP61 IDE                                                                        | 3         | 1.15%   |
| JMicron JMB368 IDE controller                                                           | 3         | 1.15%   |
| Intel Wildcat Point-LP SATA Controller [AHCI Mode]                                      | 3         | 1.15%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series SATA AHCI Controller                | 3         | 1.15%   |
| Intel 200 Series PCH SATA controller [AHCI mode]                                        | 3         | 1.15%   |
| AMD FCH SATA Controller [IDE mode]                                                      | 3         | 1.15%   |
| AMD FCH IDE Controller                                                                  | 3         | 1.15%   |
| Toshiba America Info Systems XG6 NVMe SSD Controller                                    | 2         | 0.76%   |
| SK hynix BC501 NVMe Solid State Drive                                                   | 2         | 0.76%   |
| Micron Non-Volatile memory controller                                                   | 2         | 0.76%   |
| JMicron JMB363 SATA/IDE Controller                                                      | 2         | 0.76%   |
| Intel SSD 660P Series                                                                   | 2         | 0.76%   |
| Intel Atom Processor E3800 Series SATA AHCI Controller                                  | 2         | 0.76%   |
| Intel 9 Series Chipset Family SATA Controller [AHCI Mode]                               | 2         | 0.76%   |
| Intel 82801JI (ICH10 Family) 4 port SATA IDE Controller #1                              | 2         | 0.76%   |
| Intel 82801JI (ICH10 Family) 2 port SATA IDE Controller #2                              | 2         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) SATA Controller [AHCI mode]                           | 2         | 0.76%   |
| Intel 82801HM/HEM (ICH8M/ICH8M-E) IDE Controller                                        | 2         | 0.76%   |
| Intel 400 Series Chipset Family SATA AHCI Controller                                    | 2         | 0.76%   |
| ASMedia ASM1062 Serial ATA Controller                                                   | 2         | 0.76%   |
| AMD 500 Series Chipset SATA Controller                                                  | 2         | 0.76%   |
| Solid State Storage Non-Volatile memory controller                                      | 1         | 0.38%   |
| SK hynix Non-Volatile memory controller                                                 | 1         | 0.38%   |
| SK hynix Gold P31 SSD                                                                   | 1         | 0.38%   |
| SK hynix BC511                                                                          | 1         | 0.38%   |
| SanDisk WD Blue SN500 / PC SN520 NVMe SSD                                               | 1         | 0.38%   |
| SanDisk WD Black NVMe SSD                                                               | 1         | 0.38%   |
| SanDisk PC SN520 NVMe SSD                                                               | 1         | 0.38%   |
| SanDisk Non-Volatile memory controller                                                  | 1         | 0.38%   |
| Phison PS5013 E13 NVMe Controller                                                       | 1         | 0.38%   |
| Phison E12 NVMe Controller                                                              | 1         | 0.38%   |
| Nvidia MCP67 IDE Controller                                                             | 1         | 0.38%   |
| Nvidia MCP67 AHCI Controller                                                            | 1         | 0.38%   |
| Nvidia MCP55 SATA Controller                                                            | 1         | 0.38%   |
| Nvidia MCP55 IDE                                                                        | 1         | 0.38%   |

Storage Kind
------------

Kind of storage controller (IDE, SATA, NVMe, SAS, ...)

![Storage Kind](./images/pie_chart/storage_kind.svg)


| Kind | Computers | Percent |
|------|-----------|---------|
| SATA | 131       | 57.46%  |
| IDE  | 46        | 20.18%  |
| NVMe | 41        | 17.98%  |
| RAID | 10        | 4.39%   |

Processor
---------

CPU Vendor
----------

Processor vendors

![CPU Vendor](./images/pie_chart/cpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 116       | 66.67%  |
| AMD    | 58        | 33.33%  |

CPU Model
---------

Processor models

![CPU Model](./images/pie_chart/cpu_model.svg)


| Model                                         | Computers | Percent |
|-----------------------------------------------|-----------|---------|
| Intel Core i5-8250U CPU @ 1.60GHz             | 5         | 2.87%   |
| Intel Core i7-8750H CPU @ 2.20GHz             | 3         | 1.72%   |
| Intel Core i7-8565U CPU @ 1.80GHz             | 3         | 1.72%   |
| AMD Ryzen 5 4500U with Radeon Graphics        | 3         | 1.72%   |
| AMD E1-1200 APU with Radeon HD Graphics       | 3         | 1.72%   |
| AMD E-450 APU with Radeon HD Graphics         | 3         | 1.72%   |
| Intel Pentium CPU G4400 @ 3.30GHz             | 2         | 1.15%   |
| Intel Pentium CPU B960 @ 2.20GHz              | 2         | 1.15%   |
| Intel Core i7-8550U CPU @ 1.80GHz             | 2         | 1.15%   |
| Intel Core i5-8265U CPU @ 1.60GHz             | 2         | 1.15%   |
| Intel Core i5-6200U CPU @ 2.30GHz             | 2         | 1.15%   |
| Intel Core i5-5200U CPU @ 2.20GHz             | 2         | 1.15%   |
| Intel Core i5-4670K CPU @ 3.40GHz             | 2         | 1.15%   |
| Intel Core i5-2410M CPU @ 2.30GHz             | 2         | 1.15%   |
| Intel Core i5-1035G1 CPU @ 1.00GHz            | 2         | 1.15%   |
| Intel Core i5-10210U CPU @ 1.60GHz            | 2         | 1.15%   |
| Intel Core i3-8130U CPU @ 2.20GHz             | 2         | 1.15%   |
| Intel Core 2 Duo CPU E8400 @ 3.00GHz          | 2         | 1.15%   |
| Intel Celeron CPU N3450 @ 1.10GHz             | 2         | 1.15%   |
| Intel Celeron CPU N2840 @ 2.16GHz             | 2         | 1.15%   |
| Intel 11th Gen Core i7-1165G7 @ 2.80GHz       | 2         | 1.15%   |
| AMD Ryzen 7 5700U with Radeon Graphics        | 2         | 1.15%   |
| AMD Ryzen 7 3700X 8-Core Processor            | 2         | 1.15%   |
| AMD Ryzen 5 3500U with Radeon Vega Mobile Gfx | 2         | 1.15%   |
| AMD Phenom II X6 1055T Processor              | 2         | 1.15%   |
| AMD E-300 APU with Radeon HD Graphics         | 2         | 1.15%   |
| AMD Athlon II X2 280 Processor                | 2         | 1.15%   |
| Intel Xeon CPU E5405 @ 2.00GHz                | 1         | 0.57%   |
| Intel Pentium Silver N5000 CPU @ 1.10GHz      | 1         | 0.57%   |
| Intel Pentium Silver J5005 CPU @ 1.50GHz      | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU T4300 @ 2.10GHz   | 1         | 0.57%   |
| Intel Pentium Dual-Core CPU E5400 @ 2.70GHz   | 1         | 0.57%   |
| Intel Pentium Dual CPU E2160 @ 1.80GHz        | 1         | 0.57%   |
| Intel Pentium D CPU 2.80GHz                   | 1         | 0.57%   |
| Intel Pentium D CPU 2.66GHz                   | 1         | 0.57%   |
| Intel Pentium CPU N4200 @ 1.10GHz             | 1         | 0.57%   |
| Intel Pentium CPU N3710 @ 1.60GHz             | 1         | 0.57%   |
| Intel Pentium CPU N3700 @ 1.60GHz             | 1         | 0.57%   |
| Intel Pentium CPU G640 @ 2.80GHz              | 1         | 0.57%   |
| Intel Pentium CPU G4620 @ 3.70GHz             | 1         | 0.57%   |
| Intel Pentium CPU G4560 @ 3.50GHz             | 1         | 0.57%   |
| Intel Pentium CPU G3240 @ 3.10GHz             | 1         | 0.57%   |
| Intel Pentium CPU 987 @ 1.50GHz               | 1         | 0.57%   |
| Intel Pentium 4 CPU 2.66GHz                   | 1         | 0.57%   |
| Intel Core i9-9980HK CPU @ 2.40GHz            | 1         | 0.57%   |
| Intel Core i7-7820X CPU @ 3.60GHz             | 1         | 0.57%   |
| Intel Core i7-7700HQ CPU @ 2.80GHz            | 1         | 0.57%   |
| Intel Core i7-7500U CPU @ 2.70GHz             | 1         | 0.57%   |
| Intel Core i7-6700T CPU @ 2.80GHz             | 1         | 0.57%   |
| Intel Core i7-6600U CPU @ 2.60GHz             | 1         | 0.57%   |
| Intel Core i7-3770K CPU @ 3.50GHz             | 1         | 0.57%   |
| Intel Core i7-10850H CPU @ 2.70GHz            | 1         | 0.57%   |
| Intel Core i7-10750H CPU @ 2.60GHz            | 1         | 0.57%   |
| Intel Core i7-10510U CPU @ 1.80GHz            | 1         | 0.57%   |
| Intel Core i5-8400H CPU @ 2.50GHz             | 1         | 0.57%   |
| Intel Core i5-8300H CPU @ 2.30GHz             | 1         | 0.57%   |
| Intel Core i5-7500 CPU @ 3.40GHz              | 1         | 0.57%   |
| Intel Core i5-7200U CPU @ 2.50GHz             | 1         | 0.57%   |
| Intel Core i5-4690 CPU @ 3.50GHz              | 1         | 0.57%   |
| Intel Core i5-4570 CPU @ 3.20GHz              | 1         | 0.57%   |

CPU Model Family
----------------

Processor model prefix

![CPU Model Family](./images/pie_chart/cpu_family.svg)


| Model                          | Computers | Percent |
|--------------------------------|-----------|---------|
| Intel Core i5                  | 38        | 21.84%  |
| Intel Core i7                  | 17        | 9.77%   |
| Intel Core i3                  | 17        | 9.77%   |
| Intel Pentium                  | 12        | 6.9%    |
| Intel Celeron                  | 12        | 6.9%    |
| AMD Ryzen 5                    | 7         | 4.02%   |
| AMD Ryzen 7                    | 6         | 3.45%   |
| AMD Athlon II X2               | 6         | 3.45%   |
| Intel Core 2 Duo               | 5         | 2.87%   |
| AMD E                          | 5         | 2.87%   |
| AMD Athlon 64 X2               | 5         | 2.87%   |
| Other                          | 4         | 2.3%    |
| AMD A4                         | 4         | 2.3%    |
| AMD Ryzen 3                    | 3         | 1.72%   |
| AMD E1                         | 3         | 1.72%   |
| AMD A10                        | 3         | 1.72%   |
| Intel Pentium Silver           | 2         | 1.15%   |
| Intel Pentium Dual-Core        | 2         | 1.15%   |
| Intel Pentium D                | 2         | 1.15%   |
| AMD Sempron                    | 2         | 1.15%   |
| AMD Phenom II X6               | 2         | 1.15%   |
| AMD FX                         | 2         | 1.15%   |
| AMD Athlon II X4               | 2         | 1.15%   |
| AMD Athlon                     | 2         | 1.15%   |
| Intel Xeon                     | 1         | 0.57%   |
| Intel Pentium Dual             | 1         | 0.57%   |
| Intel Pentium 4                | 1         | 0.57%   |
| Intel Core i9                  | 1         | 0.57%   |
| Intel Core 2 Quad              | 1         | 0.57%   |
| AMD V140                       | 1         | 0.57%   |
| AMD Turion X2 Dual-Core Mobile | 1         | 0.57%   |
| AMD Ryzen 5 PRO                | 1         | 0.57%   |
| AMD Phenom II X4               | 1         | 0.57%   |
| AMD A8                         | 1         | 0.57%   |
| AMD A6                         | 1         | 0.57%   |

CPU Cores
---------

Number of processor cores

![CPU Cores](./images/pie_chart/cpu_cores.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 87        | 49.71%  |
| 4       | 57        | 32.57%  |
| 6       | 13        | 7.43%   |
| 8       | 8         | 4.57%   |
| 1       | 5         | 2.86%   |
| Unknown | 4         | 2.29%   |
| 10      | 1         | 0.57%   |

CPU Sockets
-----------

Number of sockets

![CPU Sockets](./images/pie_chart/cpu_sockets.svg)


| Number | Computers | Percent |
|--------|-----------|---------|
| 1      | 173       | 99.43%  |
| 2      | 1         | 0.57%   |

CPU Threads
-----------

Threads per core (Hyper-Threading)

![CPU Threads](./images/pie_chart/cpu_threads.svg)


| Number  | Computers | Percent |
|---------|-----------|---------|
| 2       | 88        | 50.29%  |
| 1       | 83        | 47.43%  |
| Unknown | 4         | 2.29%   |

CPU Op-Modes
------------

CPU Operation Modes (32-bit, 64-bit)

![CPU Op-Modes](./images/pie_chart/cpu_op_modes.svg)


| Op mode        | Computers | Percent |
|----------------|-----------|---------|
| 32-bit, 64-bit | 171       | 98.28%  |
| Unknown        | 3         | 1.72%   |

CPU Microcode
-------------

Microcode number

![CPU Microcode](./images/pie_chart/cpu_microcode.svg)


| Number     | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 23        | 13.14%  |
| 0x206a7    | 11        | 6.29%   |
| 0x806ea    | 9         | 5.14%   |
| 0x306c3    | 8         | 4.57%   |
| 0x05000119 | 8         | 4.57%   |
| 0x306a9    | 7         | 4%      |
| 0x010000c8 | 7         | 4%      |
| 0x806ec    | 6         | 3.43%   |
| 0x906e9    | 5         | 2.86%   |
| 0x08600106 | 5         | 2.86%   |
| 0x906ea    | 4         | 2.29%   |
| 0x40651    | 4         | 2.29%   |
| 0x1067a    | 4         | 2.29%   |
| 0x806e9    | 3         | 1.71%   |
| 0x706a1    | 3         | 1.71%   |
| 0x6fd      | 3         | 1.71%   |
| 0x506e3    | 3         | 1.71%   |
| 0x506c9    | 3         | 1.71%   |
| 0x406e3    | 3         | 1.71%   |
| 0x306d4    | 3         | 1.71%   |
| 0x03000027 | 3         | 1.71%   |
| 0xf47      | 2         | 1.14%   |
| 0xa0652    | 2         | 1.14%   |
| 0x806c1    | 2         | 1.14%   |
| 0x706e5    | 2         | 1.14%   |
| 0x406c4    | 2         | 1.14%   |
| 0x406c3    | 2         | 1.14%   |
| 0x30678    | 2         | 1.14%   |
| 0x10676    | 2         | 1.14%   |
| 0x08608103 | 2         | 1.14%   |
| 0x08108109 | 2         | 1.14%   |
| 0x08108102 | 2         | 1.14%   |
| 0x06001119 | 2         | 1.14%   |
| 0x02000057 | 2         | 1.14%   |
| 0x010000dc | 2         | 1.14%   |
| 0xf49      | 1         | 0.57%   |
| 0xf41      | 1         | 0.57%   |
| 0xa0655    | 1         | 0.57%   |
| 0x90672    | 1         | 0.57%   |
| 0x706a8    | 1         | 0.57%   |
| 0x6fb      | 1         | 0.57%   |
| 0x50654    | 1         | 0.57%   |
| 0x20655    | 1         | 0.57%   |
| 0x20652    | 1         | 0.57%   |
| 0x106e5    | 1         | 0.57%   |
| 0x0a50000c | 1         | 0.57%   |
| 0x08701021 | 1         | 0.57%   |
| 0x08101102 | 1         | 0.57%   |
| 0x08001138 | 1         | 0.57%   |
| 0x06003106 | 1         | 0.57%   |
| 0x06000852 | 1         | 0.57%   |
| 0x0600063e | 1         | 0.57%   |
| 0x03000025 | 1         | 0.57%   |
| 0x02000032 | 1         | 0.57%   |
| 0x010000db | 1         | 0.57%   |
| 0x010000b6 | 1         | 0.57%   |
| 0x0100009f | 1         | 0.57%   |

CPU Microarch
-------------

Microarchitecture

![CPU Microarch](./images/pie_chart/cpu_microarch.svg)


| Name             | Computers | Percent |
|------------------|-----------|---------|
| KabyLake         | 32        | 18.39%  |
| Haswell          | 15        | 8.62%   |
| K10              | 13        | 7.47%   |
| SandyBridge      | 11        | 6.32%   |
| Zen 2            | 9         | 5.17%   |
| Skylake          | 8         | 4.6%    |
| Bobcat           | 8         | 4.6%    |
| IvyBridge        | 7         | 4.02%   |
| Silvermont       | 6         | 3.45%   |
| Penryn           | 6         | 3.45%   |
| K8 Hammer        | 5         | 2.87%   |
| Core             | 5         | 2.87%   |
| Zen+             | 4         | 2.3%    |
| Piledriver       | 4         | 2.3%    |
| NetBurst         | 4         | 2.3%    |
| K10 Llano        | 4         | 2.3%    |
| Goldmont plus    | 4         | 2.3%    |
| TigerLake        | 3         | 1.72%   |
| K8 & K10 hybrid  | 3         | 1.72%   |
| Goldmont         | 3         | 1.72%   |
| CometLake        | 3         | 1.72%   |
| Broadwell        | 3         | 1.72%   |
| Zen              | 2         | 1.15%   |
| Westmere         | 2         | 1.15%   |
| IceLake          | 2         | 1.15%   |
| Unknown          | 2         | 1.15%   |
| Zen 3            | 1         | 0.57%   |
| Steamroller      | 1         | 0.57%   |
| Puma             | 1         | 0.57%   |
| Nehalem          | 1         | 0.57%   |
| Bulldozer        | 1         | 0.57%   |
| Alderlake Hybrid | 1         | 0.57%   |

Graphics
--------

GPU Vendor
----------

Vendors of graphics cards

![GPU Vendor](./images/pie_chart/gpu_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Intel  | 93        | 46.04%  |
| AMD    | 55        | 27.23%  |
| Nvidia | 54        | 26.73%  |

GPU Model
---------

Graphics card models

![GPU Model](./images/pie_chart/gpu_model.svg)


| Model                                                                                    | Computers | Percent |
|------------------------------------------------------------------------------------------|-----------|---------|
| Intel 2nd Generation Core Processor Family Integrated Graphics Controller                | 11        | 5.26%   |
| Intel UHD Graphics 620                                                                   | 9         | 4.31%   |
| AMD Renoir                                                                               | 7         | 3.35%   |
| Intel CoffeeLake-H GT2 [UHD Graphics 630]                                                | 6         | 2.87%   |
| Intel WhiskeyLake-U GT2 [UHD Graphics 620]                                               | 5         | 2.39%   |
| Intel Haswell-ULT Integrated Graphics Controller                                         | 5         | 2.39%   |
| Intel HD Graphics 620                                                                    | 4         | 1.91%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Integrated Graphics Controller | 4         | 1.91%   |
| Intel 4th Gen Core Processor Integrated Graphics Controller                              | 4         | 1.91%   |
| AMD Picasso/Raven 2 [Radeon Vega Series / Radeon Vega Mobile Series]                     | 4         | 1.91%   |
| Nvidia GP107M [GeForce GTX 1050 Ti Mobile]                                               | 3         | 1.44%   |
| Nvidia GF117M [GeForce 610M/710M/810M/820M / GT 620M/625M/630M/720M]                     | 3         | 1.44%   |
| Nvidia GF108 [GeForce GT 630]                                                            | 3         | 1.44%   |
| Intel TigerLake-LP GT2 [Iris Xe Graphics]                                                | 3         | 1.44%   |
| Intel Skylake GT2 [HD Graphics 520]                                                      | 3         | 1.44%   |
| Intel HD Graphics 630                                                                    | 3         | 1.44%   |
| Intel HD Graphics 5500                                                                   | 3         | 1.44%   |
| Intel CometLake-U GT2 [UHD Graphics]                                                     | 3         | 1.44%   |
| Intel 3rd Gen Core processor Graphics Controller                                         | 3         | 1.44%   |
| AMD Wrestler [Radeon HD 7310]                                                            | 3         | 1.44%   |
| AMD Wrestler [Radeon HD 6320]                                                            | 3         | 1.44%   |
| Nvidia TU117M                                                                            | 2         | 0.96%   |
| Nvidia GP108M [GeForce MX150]                                                            | 2         | 0.96%   |
| Nvidia GP107M [GeForce GTX 1050 Mobile]                                                  | 2         | 0.96%   |
| Nvidia GP106 [GeForce GTX 1060 6GB]                                                      | 2         | 0.96%   |
| Nvidia GM204 [GeForce GTX 970]                                                           | 2         | 0.96%   |
| Nvidia GM108M [GeForce MX130]                                                            | 2         | 0.96%   |
| Nvidia GF108 [GeForce GT 730]                                                            | 2         | 0.96%   |
| Nvidia GF108 [GeForce GT 440]                                                            | 2         | 0.96%   |
| Nvidia C77 [GeForce 8200M G]                                                             | 2         | 0.96%   |
| Intel Mobile 4 Series Chipset Integrated Graphics Controller                             | 2         | 0.96%   |
| Intel Iris Plus Graphics G1 (Ice Lake)                                                   | 2         | 0.96%   |
| Intel HD Graphics 530                                                                    | 2         | 0.96%   |
| Intel HD Graphics 500                                                                    | 2         | 0.96%   |
| Intel GeminiLake [UHD Graphics 605]                                                      | 2         | 0.96%   |
| Intel GeminiLake [UHD Graphics 600]                                                      | 2         | 0.96%   |
| Intel Core Processor Integrated Graphics Controller                                      | 2         | 0.96%   |
| Intel Atom Processor Z36xxx/Z37xxx Series Graphics & Display                             | 2         | 0.96%   |
| Intel 4 Series Chipset Integrated Graphics Controller                                    | 2         | 0.96%   |
| AMD Wrestler [Radeon HD 6310]                                                            | 2         | 0.96%   |
| AMD Seymour [Radeon HD 6400M/7400M Series]                                               | 2         | 0.96%   |
| AMD RS880M [Mobility Radeon HD 4225/4250]                                                | 2         | 0.96%   |
| AMD Lucienne                                                                             | 2         | 0.96%   |
| AMD Ellesmere [Radeon RX 470/480/570/570X/580/580X/590]                                  | 2         | 0.96%   |
| AMD Caicos [Radeon HD 6450/7450/8450 / R5 230 OEM]                                       | 2         | 0.96%   |
| Nvidia TU117M [GeForce GTX 1650 Mobile / Max-Q]                                          | 1         | 0.48%   |
| Nvidia TU117GLM [Quadro T2000 Mobile / Max-Q]                                            | 1         | 0.48%   |
| Nvidia TU106M [GeForce RTX 2070 Mobile]                                                  | 1         | 0.48%   |
| Nvidia GT218 [GeForce 210]                                                               | 1         | 0.48%   |
| Nvidia GT216 [GeForce GT 220]                                                            | 1         | 0.48%   |
| Nvidia GP107 [GeForce GTX 1050]                                                          | 1         | 0.48%   |
| Nvidia GP107 [GeForce GTX 1050 Ti]                                                       | 1         | 0.48%   |
| Nvidia GP106 [GeForce GTX 1060 3GB]                                                      | 1         | 0.48%   |
| Nvidia GM108M [GeForce MX110]                                                            | 1         | 0.48%   |
| Nvidia GM108M [GeForce 930MX]                                                            | 1         | 0.48%   |
| Nvidia GM107M [GeForce GTX 950M]                                                         | 1         | 0.48%   |
| Nvidia GM107 [GeForce GTX 750 Ti]                                                        | 1         | 0.48%   |
| Nvidia GK208M [GeForce GT 740M]                                                          | 1         | 0.48%   |
| Nvidia GK208BM [GeForce 920M]                                                            | 1         | 0.48%   |
| Nvidia GK208B [GeForce GT 730]                                                           | 1         | 0.48%   |

GPU Combo
---------

Combinations of graphics cards

![GPU Combo](./images/pie_chart/gpu_combo.svg)


| Name           | Computers | Percent |
|----------------|-----------|---------|
| 1 x Intel      | 69        | 39.2%   |
| 1 x AMD        | 44        | 25%     |
| 1 x Nvidia     | 31        | 17.61%  |
| Intel + Nvidia | 21        | 11.93%  |
| 2 x AMD        | 6         | 3.41%   |
| Intel + AMD    | 3         | 1.7%    |
| AMD + Nvidia   | 2         | 1.14%   |

GPU Driver
----------

Free vs proprietary

![GPU Driver](./images/pie_chart/gpu_driver.svg)


| Driver      | Computers | Percent |
|-------------|-----------|---------|
| Free        | 144       | 79.56%  |
| Proprietary | 25        | 13.81%  |
| Unknown     | 12        | 6.63%   |

GPU Memory
----------

Total video memory

![GPU Memory](./images/pie_chart/gpu_memory.svg)


| Size in GB | Computers | Percent |
|------------|-----------|---------|
| Unknown    | 79        | 43.17%  |
| 0.01-0.5   | 39        | 21.31%  |
| 1.01-2.0   | 36        | 19.67%  |
| 3.01-4.0   | 14        | 7.65%   |
| 0.51-1.0   | 11        | 6.01%   |
| 5.01-6.0   | 2         | 1.09%   |
| 7.01-8.0   | 1         | 0.55%   |
| 2.01-3.0   | 1         | 0.55%   |

Monitor
-------

Monitor Vendor
--------------

Monitor vendors

![Monitor Vendor](./images/pie_chart/mon_vendor.svg)


| Vendor                  | Computers | Percent |
|-------------------------|-----------|---------|
| AU Optronics            | 32        | 17.3%   |
| Samsung Electronics     | 30        | 16.22%  |
| LG Display              | 20        | 10.81%  |
| Chimei Innolux          | 18        | 9.73%   |
| Philips                 | 15        | 8.11%   |
| Goldstar                | 15        | 8.11%   |
| BOE                     | 10        | 5.41%   |
| Dell                    | 8         | 4.32%   |
| Acer                    | 7         | 3.78%   |
| AOC                     | 6         | 3.24%   |
| Chi Mei Optoelectronics | 5         | 2.7%    |
| Hewlett-Packard         | 4         | 2.16%   |
| InfoVision              | 3         | 1.62%   |
| Sharp                   | 2         | 1.08%   |
| Lenovo                  | 2         | 1.08%   |
| BenQ                    | 2         | 1.08%   |
| ViewSonic               | 1         | 0.54%   |
| Plain Tree Systems      | 1         | 0.54%   |
| PANDA                   | 1         | 0.54%   |
| Medion                  | 1         | 0.54%   |
| HannStar                | 1         | 0.54%   |
| Ancor Communications    | 1         | 0.54%   |

Monitor Model
-------------

Monitor models

![Monitor Model](./images/pie_chart/mon_model.svg)


| Model                                                                  | Computers | Percent |
|------------------------------------------------------------------------|-----------|---------|
| AU Optronics LCD Monitor AUO21ED 1920x1080 344x194mm 15.5-inch         | 4         | 2.14%   |
| LG Display LCD Monitor LGD0563 1920x1080 344x194mm 15.5-inch           | 3         | 1.6%    |
| AU Optronics LCD Monitor AUO46EC 1366x768 344x193mm 15.5-inch          | 3         | 1.6%    |
| AU Optronics LCD Monitor AUO38ED 1920x1080 344x193mm 15.5-inch         | 3         | 1.6%    |
| Samsung Electronics SyncMaster SAM0108 1280x1024 312x234mm 15.4-inch   | 2         | 1.07%   |
| Philips 223E PHLC049 1920x1080 476x268mm 21.5-inch                     | 2         | 1.07%   |
| Hewlett-Packard E243 HPN3468 1920x1080 527x296mm 23.8-inch             | 2         | 1.07%   |
| Goldstar ULTRAWIDE GSM59F1 2560x1080 673x284mm 28.8-inch               | 2         | 1.07%   |
| Chimei Innolux LCD Monitor CMN15F5 1920x1080 344x193mm 15.5-inch       | 2         | 1.07%   |
| Chimei Innolux LCD Monitor CMN15AB 1366x768 344x193mm 15.5-inch        | 2         | 1.07%   |
| BOE LCD Monitor BOE085E 1920x1080 344x194mm 15.5-inch                  | 2         | 1.07%   |
| AU Optronics LCD Monitor AUO26EC 1366x768 344x193mm 15.5-inch          | 2         | 1.07%   |
| AOC 2369M AOC2369 1920x1080 509x286mm 23.0-inch                        | 2         | 1.07%   |
| ViewSonic VA521-1 VSCF318 1024x768 304x228mm 15.0-inch                 | 1         | 0.53%   |
| Sharp LCD Monitor SHP149A 1920x1080 344x194mm 15.5-inch                | 1         | 0.53%   |
| Sharp LCD Monitor SHP13CF 1280x800 331x207mm 15.4-inch                 | 1         | 0.53%   |
| Samsung Electronics U28H75x SAM0DFE 3840x2160 608x345mm 27.5-inch      | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM03D1 1680x1050 433x271mm 20.1-inch   | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM036F 1440x900 428x255mm 19.6-inch    | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM036E 1280x1024 376x301mm 19.0-inch   | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM02AD 1440x900 410x257mm 19.1-inch    | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM0285 1440x900 410x257mm 19.1-inch    | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM022B 1280x1024 340x270mm 17.1-inch   | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM0213 1680x1050 408x306mm 20.1-inch   | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM01E1 1280x1024 376x301mm 19.0-inch   | 1         | 0.53%   |
| Samsung Electronics SyncMaster SAM0088 1024x768 304x228mm 15.0-inch    | 1         | 0.53%   |
| Samsung Electronics SMB2440 SAM06AF 1920x1080 531x299mm 24.0-inch      | 1         | 0.53%   |
| Samsung Electronics SMB2030 SAM063D 1600x900 443x249mm 20.0-inch       | 1         | 0.53%   |
| Samsung Electronics S27F358 SAM0D73 1920x1080 598x336mm 27.0-inch      | 1         | 0.53%   |
| Samsung Electronics S22E391 SAM0C0D 1920x1080 477x268mm 21.5-inch      | 1         | 0.53%   |
| Samsung Electronics S22D300 SAM0B3F 1920x1080 477x268mm 21.5-inch      | 1         | 0.53%   |
| Samsung Electronics S19D300 SAM0B34 1366x768 410x230mm 18.5-inch       | 1         | 0.53%   |
| Samsung Electronics S/T 77E/76E STN0005 1280x1024 312x234mm 15.4-inch  | 1         | 0.53%   |
| Samsung Electronics S/T 77/76BDF STN0007 1280x1024 312x234mm 15.4-inch | 1         | 0.53%   |
| Samsung Electronics LF24T450F SAM7095 1920x1080 527x296mm 23.8-inch    | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5842 1366x768 309x174mm 14.0-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC5441 1366x768 344x194mm 15.5-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4E45 1280x800 331x207mm 15.4-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC4351 1366x768 340x190mm 15.3-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC364A 1366x768 344x194mm 15.5-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3551 1366x768 344x194mm 15.5-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SEC3245 1280x800 331x207mm 15.4-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDCA029 3840x2160 344x194mm 15.5-inch  | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4347 1366x768 344x193mm 15.5-inch   | 1         | 0.53%   |
| Samsung Electronics LCD Monitor SDC4150 3456x2160 336x210mm 15.6-inch  | 1         | 0.53%   |
| Plain Tree Systems XAP-192i PTS03D5 1280x1024 376x301mm 19.0-inch      | 1         | 0.53%   |
| Philips PHL 275E2F PHLC23A 2560x1440 597x336mm 27.0-inch               | 1         | 0.53%   |
| Philips PHL 246E9Q PHLC17C 1920x1080 527x296mm 23.8-inch               | 1         | 0.53%   |
| Philips PHL 246E7 PHLC107 1920x1080 521x293mm 23.5-inch                | 1         | 0.53%   |
| Philips PHL 243V5 PHLC0D1 1920x1080 521x293mm 23.5-inch                | 1         | 0.53%   |
| Philips PHL 243S7 PHL090F 1920x1080 527x296mm 23.8-inch                | 1         | 0.53%   |
| Philips PHL 240V5A PHLC10C 1920x1080 527x296mm 23.8-inch               | 1         | 0.53%   |
| Philips PHL 240V5 PHLC10A 1920x1080 527x296mm 23.8-inch                | 1         | 0.53%   |
| Philips PHL 234E5 PHLC0C7 1920x1080 510x290mm 23.1-inch                | 1         | 0.53%   |
| Philips PHL 223V7 PHLC154 1920x1080 476x268mm 21.5-inch                | 1         | 0.53%   |
| Philips PHL 223V5 PHLC0CF 1920x1080 477x268mm 21.5-inch                | 1         | 0.53%   |
| Philips 247ELH PHLC085 1920x1080 521x293mm 23.5-inch                   | 1         | 0.53%   |
| Philips 227E4LH PHLC0AC 1920x1080 480x270mm 21.7-inch                  | 1         | 0.53%   |
| Philips 201E PHLC033 1600x900 443x249mm 20.0-inch                      | 1         | 0.53%   |
| Philips 196VL PHLC07F 1366x768 409x230mm 18.5-inch                     | 1         | 0.53%   |

Monitor Resolution
------------------

Monitor screen resolution

![Monitor Resolution](./images/pie_chart/mon_resolution.svg)


| Resolution         | Computers | Percent |
|--------------------|-----------|---------|
| 1920x1080 (FHD)    | 71        | 40.57%  |
| 1366x768 (WXGA)    | 48        | 27.43%  |
| 1600x900 (HD+)     | 13        | 7.43%   |
| 1280x1024 (SXGA)   | 12        | 6.86%   |
| 2560x1440 (QHD)    | 6         | 3.43%   |
| 1680x1050 (WSXGA+) | 5         | 2.86%   |
| 1440x900 (WXGA+)   | 5         | 2.86%   |
| 3840x2160 (4K)     | 3         | 1.71%   |
| 1280x800 (WXGA)    | 3         | 1.71%   |
| 2560x1080          | 2         | 1.14%   |
| 1600x1200          | 2         | 1.14%   |
| 1024x768 (XGA)     | 2         | 1.14%   |
| 3456x2160          | 1         | 0.57%   |
| 2160x1440          | 1         | 0.57%   |
| 1360x768           | 1         | 0.57%   |

Monitor Diagonal
----------------

Diagonal size in inches

![Monitor Diagonal](./images/pie_chart/mon_diagonal.svg)


| Inches | Computers | Percent |
|--------|-----------|---------|
| 15     | 80        | 43.01%  |
| 23     | 13        | 6.99%   |
| 24     | 12        | 6.45%   |
| 21     | 11        | 5.91%   |
| 19     | 11        | 5.91%   |
| 17     | 11        | 5.91%   |
| 27     | 9         | 4.84%   |
| 14     | 9         | 4.84%   |
| 20     | 8         | 4.3%    |
| 18     | 6         | 3.23%   |
| 13     | 6         | 3.23%   |
| 11     | 4         | 2.15%   |
| 34     | 2         | 1.08%   |
| 12     | 2         | 1.08%   |
| 31     | 1         | 0.54%   |
| 22     | 1         | 0.54%   |

Monitor Width
-------------

Physical width

![Monitor Width](./images/pie_chart/mon_width.svg)


| Width in mm | Computers | Percent |
|-------------|-----------|---------|
| 301-350     | 96        | 52.17%  |
| 501-600     | 31        | 16.85%  |
| 401-500     | 31        | 16.85%  |
| 351-400     | 13        | 7.07%   |
| 201-300     | 9         | 4.89%   |
| 701-800     | 2         | 1.09%   |
| 601-700     | 2         | 1.09%   |

Aspect Ratio
------------

Proportional relationship between the width and the height

![Aspect Ratio](./images/pie_chart/mon_ratio.svg)


| Ratio | Computers | Percent |
|-------|-----------|---------|
| 16/9  | 133       | 80.12%  |
| 16/10 | 12        | 7.23%   |
| 5/4   | 10        | 6.02%   |
| 4/3   | 7         | 4.22%   |
| 3/2   | 2         | 1.2%    |
| 21/9  | 2         | 1.2%    |

Monitor Area
------------

Area in inch²

![Monitor Area](./images/pie_chart/mon_area.svg)


| Area in inch² | Computers | Percent |
|----------------|-----------|---------|
| 101-110        | 76        | 41.08%  |
| 201-250        | 33        | 17.84%  |
| 151-200        | 23        | 12.43%  |
| 81-90          | 13        | 7.03%   |
| 141-150        | 10        | 5.41%   |
| 301-350        | 9         | 4.86%   |
| 51-60          | 4         | 2.16%   |
| 121-130        | 4         | 2.16%   |
| 111-120        | 4         | 2.16%   |
| 351-500        | 3         | 1.62%   |
| 71-80          | 2         | 1.08%   |
| 61-70          | 2         | 1.08%   |
| 131-140        | 2         | 1.08%   |

Pixel Density
-------------

Pixels per inch

![Pixel Density](./images/pie_chart/mon_density.svg)


| Density       | Computers | Percent |
|---------------|-----------|---------|
| 51-100        | 66        | 36.46%  |
| 101-120       | 56        | 30.94%  |
| 121-160       | 54        | 29.83%  |
| 161-240       | 3         | 1.66%   |
| More than 240 | 2         | 1.1%    |

Multiple Monitors
-----------------

Total monitors connected

![Multiple Monitors](./images/pie_chart/mon_total.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 1     | 150       | 85.23%  |
| 2     | 22        | 12.5%   |
| 0     | 4         | 2.27%   |

Network
-------

Net Controller Vendor
---------------------

Controller vendors

![Net Controller Vendor](./images/pie_chart/net_vendor.svg)


| Vendor                            | Computers | Percent |
|-----------------------------------|-----------|---------|
| Realtek Semiconductor             | 115       | 44.92%  |
| Intel                             | 52        | 20.31%  |
| Qualcomm Atheros                  | 42        | 16.41%  |
| Broadcom                          | 11        | 4.3%    |
| Nvidia                            | 8         | 3.13%   |
| Xiaomi                            | 4         | 1.56%   |
| Ralink                            | 4         | 1.56%   |
| Broadcom Limited                  | 4         | 1.56%   |
| TP-Link                           | 2         | 0.78%   |
| Marvell Technology Group          | 2         | 0.78%   |
| Sierra Wireless                   | 1         | 0.39%   |
| OnePlus Technology (Shenzhen)     | 1         | 0.39%   |
| Mercucys                          | 1         | 0.39%   |
| MediaTek                          | 1         | 0.39%   |
| JMicron Technology                | 1         | 0.39%   |
| ICS Advent                        | 1         | 0.39%   |
| Huawei Technologies               | 1         | 0.39%   |
| Hewlett-Packard                   | 1         | 0.39%   |
| Ericsson Business Mobile Networks | 1         | 0.39%   |
| D-Link System                     | 1         | 0.39%   |
| D-Link                            | 1         | 0.39%   |
| ASIX Electronics                  | 1         | 0.39%   |

Net Controller Model
--------------------

Controller models

![Net Controller Model](./images/pie_chart/net_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller       | 83        | 28.42%  |
| Realtek RTL810xE PCI Express Fast Ethernet controller                   | 21        | 7.19%   |
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 3.08%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 2.74%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 2.4%    |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 2.4%    |
| Intel Wireless 8265 / 8275                                              | 7         | 2.4%    |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 1.71%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 1.71%   |
| Xiaomi Mi/Redmi series (RNDIS)                                          | 4         | 1.37%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 1.37%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 1.37%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 1.03%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 1.03%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                           | 3         | 1.03%   |
| Nvidia MCP77 Ethernet                                                   | 3         | 1.03%   |
| Nvidia MCP61 Ethernet                                                   | 3         | 1.03%   |
| Intel Wireless 7260                                                     | 3         | 1.03%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 1.03%   |
| Intel Ethernet Connection I218-LM                                       | 3         | 1.03%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 1.03%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 1.03%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 0.68%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 0.68%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 0.68%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 0.68%   |
| Intel Wireless 8260                                                     | 2         | 0.68%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 0.68%   |
| Intel I211 Gigabit Network Connection                                   | 2         | 0.68%   |
| Intel Ethernet Connection I217-V                                        | 2         | 0.68%   |
| Intel Ethernet Connection (2) I219-V                                    | 2         | 0.68%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 0.68%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 0.68%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 0.68%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 0.68%   |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                         | 2         | 0.68%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 0.68%   |
| Sierra Wireless EM7455                                                  | 1         | 0.34%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.34%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.34%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.34%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.34%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.34%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.34%   |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                         | 1         | 0.34%   |
| Realtek RTL8153 Gigabit Ethernet Adapter                                | 1         | 0.34%   |
| Realtek RTL8152 Fast Ethernet Adapter                                   | 1         | 0.34%   |
| Realtek RTL8125 2.5GbE Controller                                       | 1         | 0.34%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]        | 1         | 0.34%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.34%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.34%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 1         | 0.34%   |
| Qualcomm Atheros QCA8172 Fast Ethernet                                  | 1         | 0.34%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.34%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.34%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.34%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 0.34%   |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                | 1         | 0.34%   |
| Qualcomm Atheros AR8132 Fast Ethernet                                   | 1         | 0.34%   |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet          | 1         | 0.34%   |

Wireless Vendor
---------------

Wireless vendors

![Wireless Vendor](./images/pie_chart/net_wireless_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Intel                 | 42        | 33.87%  |
| Qualcomm Atheros      | 36        | 29.03%  |
| Realtek Semiconductor | 27        | 21.77%  |
| Broadcom              | 8         | 6.45%   |
| Ralink                | 4         | 3.23%   |
| TP-Link               | 2         | 1.61%   |
| Sierra Wireless       | 1         | 0.81%   |
| Mercucys              | 1         | 0.81%   |
| D-Link System         | 1         | 0.81%   |
| D-Link                | 1         | 0.81%   |
| Broadcom Limited      | 1         | 0.81%   |

Wireless Model
--------------

Wireless models

![Wireless Model](./images/pie_chart/net_wireless_model.svg)


| Model                                                                   | Computers | Percent |
|-------------------------------------------------------------------------|-----------|---------|
| Qualcomm Atheros QCA9565 / AR9565 Wireless Network Adapter              | 9         | 7.26%   |
| Qualcomm Atheros QCA9377 802.11ac Wireless Network Adapter              | 8         | 6.45%   |
| Realtek RTL8821CE 802.11ac PCIe Wireless Network Adapter                | 7         | 5.65%   |
| Qualcomm Atheros AR9285 Wireless Network Adapter (PCI-Express)          | 7         | 5.65%   |
| Intel Wireless 8265 / 8275                                              | 7         | 5.65%   |
| Qualcomm Atheros AR9485 Wireless Network Adapter                        | 5         | 4.03%   |
| Intel Wi-Fi 6 AX200                                                     | 5         | 4.03%   |
| Realtek RTL8822CE 802.11ac PCIe Wireless Network Adapter                | 4         | 3.23%   |
| Broadcom BCM4313 802.11bgn Wireless Network Adapter                     | 4         | 3.23%   |
| Realtek RTL8723BE PCIe Wireless Network Adapter                         | 3         | 2.42%   |
| Realtek RTL8188EE Wireless Network Adapter                              | 3         | 2.42%   |
| Intel Wireless 7260                                                     | 3         | 2.42%   |
| Intel Wi-Fi 6 AX201                                                     | 3         | 2.42%   |
| Intel Comet Lake PCH-LP CNVi WiFi                                       | 3         | 2.42%   |
| Intel Cannon Lake PCH CNVi WiFi                                         | 3         | 2.42%   |
| TP-Link TL-WN722N v2/v3 [Realtek RTL8188EUS]                            | 2         | 1.61%   |
| Realtek RTL8822BE 802.11a/b/g/n/ac WiFi adapter                         | 2         | 1.61%   |
| Realtek RTL8188CE 802.11b/g/n WiFi Adapter                              | 2         | 1.61%   |
| Qualcomm Atheros AR242x / AR542x Wireless Network Adapter (PCI-Express) | 2         | 1.61%   |
| Intel Wireless 8260                                                     | 2         | 1.61%   |
| Intel PRO/Wireless 4965 AG or AGN [Kedron] Network Connection           | 2         | 1.61%   |
| Intel Dual Band Wireless-AC 3168NGW [Stone Peak]                        | 2         | 1.61%   |
| Intel Dual Band Wireless-AC 3165 Plus Bluetooth                         | 2         | 1.61%   |
| Intel Comet Lake PCH CNVi WiFi                                          | 2         | 1.61%   |
| Intel Cannon Point-LP CNVi [Wireless-AC]                                | 2         | 1.61%   |
| Broadcom BCM43228 802.11a/b/g/n                                         | 2         | 1.61%   |
| Sierra Wireless EM7455                                                  | 1         | 0.81%   |
| Realtek RTL8852AE 802.11ax PCIe Wireless Network Adapter                | 1         | 0.81%   |
| Realtek RTL8821AE 802.11ac PCIe Wireless Network Adapter                | 1         | 0.81%   |
| Realtek RTL8723DE Wireless Network Adapter                              | 1         | 0.81%   |
| Realtek RTL8192CU 802.11n WLAN Adapter                                  | 1         | 0.81%   |
| Realtek RTL8188EUS 802.11n Wireless Network Adapter                     | 1         | 0.81%   |
| Realtek RTL8187B Wireless Adapter                                       | 1         | 0.81%   |
| Ralink RT5390 [802.11 b/g/n 1T1R G-band PCI Express Single Chip]        | 1         | 0.81%   |
| Ralink RT5390 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.81%   |
| Ralink RT3090 Wireless 802.11n 1T/1R PCIe                               | 1         | 0.81%   |
| Ralink RT3060 Wireless 802.11n 1T/1R                                    | 1         | 0.81%   |
| Qualcomm Atheros QCA6174 802.11ac Wireless Network Adapter              | 1         | 0.81%   |
| Qualcomm Atheros AR9462 Wireless Network Adapter                        | 1         | 0.81%   |
| Qualcomm Atheros AR9287 Wireless Network Adapter (PCI-Express)          | 1         | 0.81%   |
| Qualcomm Atheros AR9227 Wireless Network Adapter                        | 1         | 0.81%   |
| Qualcomm Atheros AR5416 Wireless Network Adapter [AR5008 802.11(a)bgn]  | 1         | 0.81%   |
| Mercucys 802.11n NIC                                                    | 1         | 0.81%   |
| Intel Wireless 7265                                                     | 1         | 0.81%   |
| Intel Wireless 3165                                                     | 1         | 0.81%   |
| Intel Wireless 3160                                                     | 1         | 0.81%   |
| Intel Ice Lake-LP PCH CNVi WiFi                                         | 1         | 0.81%   |
| Intel Centrino Wireless-N 105                                           | 1         | 0.81%   |
| Intel Centrino Ultimate-N 6300                                          | 1         | 0.81%   |
| D-Link System DWA-125 Wireless N 150 Adapter(rev.A2) [Ralink RT3070]    | 1         | 0.81%   |
| D-Link 802.11 n WLAN                                                    | 1         | 0.81%   |
| Broadcom Limited BCM4352 802.11ac Wireless Network Adapter              | 1         | 0.81%   |
| Broadcom BCM4352 802.11ac Wireless Network Adapter                      | 1         | 0.81%   |
| Broadcom BCM43227 802.11b/g/n                                           | 1         | 0.81%   |

Ethernet Vendor
---------------

Ethernet vendors

![Ethernet Vendor](./images/pie_chart/net_ethernet_vendor.svg)


| Vendor                   | Computers | Percent |
|--------------------------|-----------|---------|
| Realtek Semiconductor    | 107       | 65.24%  |
| Intel                    | 24        | 14.63%  |
| Nvidia                   | 8         | 4.88%   |
| Qualcomm Atheros         | 7         | 4.27%   |
| Xiaomi                   | 4         | 2.44%   |
| Broadcom Limited         | 3         | 1.83%   |
| Broadcom                 | 3         | 1.83%   |
| Marvell Technology Group | 2         | 1.22%   |
| MediaTek                 | 1         | 0.61%   |
| JMicron Technology       | 1         | 0.61%   |
| ICS Advent               | 1         | 0.61%   |
| Huawei Technologies      | 1         | 0.61%   |
| Hewlett-Packard          | 1         | 0.61%   |
| ASIX Electronics         | 1         | 0.61%   |

Ethernet Model
--------------

Ethernet models

![Ethernet Model](./images/pie_chart/net_ethernet_model.svg)


| Model                                                                          | Computers | Percent |
|--------------------------------------------------------------------------------|-----------|---------|
| Realtek RTL8111/8168/8411 PCI Express Gigabit Ethernet Controller              | 83        | 50%     |
| Realtek RTL810xE PCI Express Fast Ethernet controller                          | 21        | 12.65%  |
| Xiaomi Mi/Redmi series (RNDIS)                                                 | 4         | 2.41%   |
| Qualcomm Atheros AR8151 v2.0 Gigabit Ethernet                                  | 3         | 1.81%   |
| Nvidia MCP77 Ethernet                                                          | 3         | 1.81%   |
| Nvidia MCP61 Ethernet                                                          | 3         | 1.81%   |
| Intel Ethernet Connection I218-LM                                              | 3         | 1.81%   |
| Intel I211 Gigabit Network Connection                                          | 2         | 1.2%    |
| Intel Ethernet Connection I217-V                                               | 2         | 1.2%    |
| Intel Ethernet Connection (2) I219-V                                           | 2         | 1.2%    |
| Broadcom NetLink BCM57785 Gigabit Ethernet PCIe                                | 2         | 1.2%    |
| Realtek RTL8169 PCI Gigabit Ethernet Controller                                | 1         | 0.6%    |
| Realtek RTL8153 Gigabit Ethernet Adapter                                       | 1         | 0.6%    |
| Realtek RTL8152 Fast Ethernet Adapter                                          | 1         | 0.6%    |
| Realtek RTL8125 2.5GbE Controller                                              | 1         | 0.6%    |
| Qualcomm Atheros QCA8172 Fast Ethernet                                         | 1         | 0.6%    |
| Qualcomm Atheros AR8161 Gigabit Ethernet                                       | 1         | 0.6%    |
| Qualcomm Atheros AR8132 Fast Ethernet                                          | 1         | 0.6%    |
| Qualcomm Atheros AR8121/AR8113/AR8114 Gigabit or Fast Ethernet                 | 1         | 0.6%    |
| Nvidia MCP67 Ethernet                                                          | 1         | 0.6%    |
| Nvidia MCP55 Ethernet                                                          | 1         | 0.6%    |
| MediaTek moto e(6) plus                                                        | 1         | 0.6%    |
| Marvell Group Yukon Optima 88E8059 [PCIe Gigabit Ethernet Controller with AVB] | 1         | 0.6%    |
| Marvell Group 88E8053 PCI-E Gigabit Ethernet Controller                        | 1         | 0.6%    |
| JMicron JMC250 PCI Express Gigabit Ethernet Controller                         | 1         | 0.6%    |
| Intel NM10/ICH7 Family LAN Controller                                          | 1         | 0.6%    |
| Intel Ethernet Connection I219-V                                               | 1         | 0.6%    |
| Intel Ethernet Connection I219-LM                                              | 1         | 0.6%    |
| Intel Ethernet Connection (7) I219-LM                                          | 1         | 0.6%    |
| Intel Ethernet Connection (6) I219-V                                           | 1         | 0.6%    |
| Intel Ethernet Connection (5) I219-V                                           | 1         | 0.6%    |
| Intel Ethernet Connection (4) I219-V                                           | 1         | 0.6%    |
| Intel Ethernet Connection (4) I219-LM                                          | 1         | 0.6%    |
| Intel Ethernet Connection (3) I218-V                                           | 1         | 0.6%    |
| Intel Ethernet Connection (2) I218-V                                           | 1         | 0.6%    |
| Intel Ethernet Connection (11) I219-V                                          | 1         | 0.6%    |
| Intel Ethernet Connection (10) I219-LM                                         | 1         | 0.6%    |
| Intel 82579V Gigabit Network Connection                                        | 1         | 0.6%    |
| Intel 82579LM Gigabit Network Connection (Lewisville)                          | 1         | 0.6%    |
| Intel 82566MM Gigabit Network Connection                                       | 1         | 0.6%    |
| Intel 82562GT 10/100 Network Connection                                        | 1         | 0.6%    |
| ICS Advent DM9601 Fast Ethernet Adapter                                        | 1         | 0.6%    |
| Huawei E353/E3131                                                              | 1         | 0.6%    |
| HP lt4120 Snapdragon X5 LTE                                                    | 1         | 0.6%    |
| Broadcom NetXtreme BCM57786 Gigabit Ethernet PCIe                              | 1         | 0.6%    |
| Broadcom Limited NetXtreme II BCM5708 Gigabit Ethernet                         | 1         | 0.6%    |
| Broadcom Limited NetXtreme BCM5761 Gigabit Ethernet PCIe                       | 1         | 0.6%    |
| Broadcom Limited NetLink BCM57785 Gigabit Ethernet PCIe                        | 1         | 0.6%    |
| ASIX AX88179 Gigabit Ethernet                                                  | 1         | 0.6%    |

Net Controller Kind
-------------------

Ethernet, WiFi or modem

![Net Controller Kind](./images/pie_chart/net_kind.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| Ethernet | 159       | 56.38%  |
| WiFi     | 121       | 42.91%  |
| Modem    | 1         | 0.35%   |
| Unknown  | 1         | 0.35%   |

Used Controller
---------------

Currently used network controller

![Used Controller](./images/pie_chart/net_used.svg)


| Kind     | Computers | Percent |
|----------|-----------|---------|
| WiFi     | 88        | 50.29%  |
| Ethernet | 87        | 49.71%  |

NICs
----

Total network controllers on board

![NICs](./images/pie_chart/net_nics.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 2     | 98        | 56.32%  |
| 1     | 76        | 43.68%  |

IPv6
----

IPv6 vs IPv4

![IPv6](./images/pie_chart/node_ipv6.svg)


| Used | Computers | Percent |
|------|-----------|---------|
| No   | 170       | 97.7%   |
| Yes  | 4         | 2.3%    |

Bluetooth
---------

Bluetooth Vendor
----------------

Controller vendors

![Bluetooth Vendor](./images/pie_chart/bt_vendor.svg)


| Vendor                          | Computers | Percent |
|---------------------------------|-----------|---------|
| Intel                           | 34        | 39.08%  |
| Qualcomm Atheros Communications | 12        | 13.79%  |
| Realtek Semiconductor           | 11        | 12.64%  |
| IMC Networks                    | 10        | 11.49%  |
| Broadcom                        | 6         | 6.9%    |
| Lite-On Technology              | 4         | 4.6%    |
| Foxconn / Hon Hai               | 2         | 2.3%    |
| Toshiba                         | 1         | 1.15%   |
| Realtek                         | 1         | 1.15%   |
| Ralink Technology               | 1         | 1.15%   |
| Integrated System Solution      | 1         | 1.15%   |
| Hewlett-Packard                 | 1         | 1.15%   |
| Dell                            | 1         | 1.15%   |
| Cambridge Silicon Radio         | 1         | 1.15%   |
| ASUSTek Computer                | 1         | 1.15%   |

Bluetooth Model
---------------

Controller models

![Bluetooth Model](./images/pie_chart/bt_model.svg)


| Model                                                                               | Computers | Percent |
|-------------------------------------------------------------------------------------|-----------|---------|
| Intel Bluetooth wireless interface                                                  | 14        | 16.09%  |
| Realtek Bluetooth Radio                                                             | 9         | 10.34%  |
| Intel AX201 Bluetooth                                                               | 7         | 8.05%   |
| Qualcomm Atheros  Bluetooth Device                                                  | 6         | 6.9%    |
| Intel Bluetooth 9460/9560 Jefferson Peak (JfP)                                      | 6         | 6.9%    |
| Intel AX200 Bluetooth                                                               | 5         | 5.75%   |
| IMC Networks Bluetooth Radio                                                        | 5         | 5.75%   |
| IMC Networks Bluetooth Device                                                       | 4         | 4.6%    |
| Realtek RTL8822BE Bluetooth 4.2 Adapter                                             | 2         | 2.3%    |
| Qualcomm Atheros AR3012 Bluetooth 4.0                                               | 2         | 2.3%    |
| Qualcomm Atheros AR3011 Bluetooth                                                   | 2         | 2.3%    |
| Lite-On Qualcomm Atheros QCA9377 Bluetooth                                          | 2         | 2.3%    |
| Intel Wireless-AC 3168 Bluetooth                                                    | 2         | 2.3%    |
| Broadcom BCM20702A0                                                                 | 2         | 2.3%    |
| Toshiba Integrated Bluetooth HCI                                                    | 1         | 1.15%   |
| Realtek Bluetooth Radio                                                             | 1         | 1.15%   |
| Ralink CSR BS8510                                                                   | 1         | 1.15%   |
| Qualcomm Atheros AR9462 Bluetooth                                                   | 1         | 1.15%   |
| Qualcomm Atheros AR3012 Bluetooth                                                   | 1         | 1.15%   |
| Lite-On Bluetooth Device                                                            | 1         | 1.15%   |
| Lite-On Atheros AR3012 Bluetooth                                                    | 1         | 1.15%   |
| Integrated System Solution Bluetooth Device                                         | 1         | 1.15%   |
| IMC Networks Atheros AR3012 Bluetooth 4.0 Adapter                                   | 1         | 1.15%   |
| HP Broadcom 2070 Bluetooth Combo                                                    | 1         | 1.15%   |
| Foxconn / Hon Hai Foxconn T77H114 BCM2070 [Single-Chip Bluetooth 2.1 + EDR Adapter] | 1         | 1.15%   |
| Foxconn / Hon Hai Bluetooth Device                                                  | 1         | 1.15%   |
| Dell DW375 Bluetooth Module                                                         | 1         | 1.15%   |
| Cambridge Silicon Radio Bluetooth Dongle (HCI mode)                                 | 1         | 1.15%   |
| Broadcom HP Portable SoftSailing                                                    | 1         | 1.15%   |
| Broadcom HP Portable Bumble Bee                                                     | 1         | 1.15%   |
| Broadcom BCM92045B3 ROM                                                             | 1         | 1.15%   |
| Broadcom BCM2070 Bluetooth Device                                                   | 1         | 1.15%   |
| ASUS BCM20702A0                                                                     | 1         | 1.15%   |

Sound
-----

Sound Vendor
------------

Sound card vendors

![Sound Vendor](./images/pie_chart/snd_vendor.svg)


| Vendor                    | Computers | Percent |
|---------------------------|-----------|---------|
| Intel                     | 115       | 52.27%  |
| AMD                       | 57        | 25.91%  |
| Nvidia                    | 37        | 16.82%  |
| Plantronics               | 2         | 0.91%   |
| Logitech                  | 2         | 0.91%   |
| Texas Instruments         | 1         | 0.45%   |
| Shenzhen Rapoo Technology | 1         | 0.45%   |
| Sennheiser Communications | 1         | 0.45%   |
| Kingston Technology       | 1         | 0.45%   |
| GN Netcom                 | 1         | 0.45%   |
| Creative Labs             | 1         | 0.45%   |
| C-Media Electronics       | 1         | 0.45%   |

Sound Model
-----------

Sound card models

![Sound Model](./images/pie_chart/snd_model.svg)


| Model                                                                                             | Computers | Percent |
|---------------------------------------------------------------------------------------------------|-----------|---------|
| AMD SBx00 Azalia (Intel HDA)                                                                      | 20        | 7.38%   |
| Intel Sunrise Point-LP HD Audio                                                                   | 16        | 5.9%    |
| AMD Family 17h/19h HD Audio Controller                                                            | 15        | 5.54%   |
| AMD FCH Azalia Controller                                                                         | 12        | 4.43%   |
| Intel 7 Series/C216 Chipset Family High Definition Audio Controller                               | 9         | 3.32%   |
| Intel 6 Series/C200 Series Chipset Family High Definition Audio Controller                        | 9         | 3.32%   |
| AMD Renoir Radeon High Definition Audio Controller                                                | 9         | 3.32%   |
| Nvidia GF108 High Definition Audio Controller                                                     | 8         | 2.95%   |
| Intel 8 Series/C220 Series Chipset High Definition Audio Controller                               | 8         | 2.95%   |
| AMD Wrestler HDMI Audio                                                                           | 8         | 2.95%   |
| Intel NM10/ICH7 Family High Definition Audio Controller                                           | 6         | 2.21%   |
| Intel Cannon Lake PCH cAVS                                                                        | 6         | 2.21%   |
| Intel Xeon E3-1200 v3/4th Gen Core Processor HD Audio Controller                                  | 5         | 1.85%   |
| Intel Haswell-ULT HD Audio Controller                                                             | 5         | 1.85%   |
| Intel Cannon Point-LP High Definition Audio Controller                                            | 5         | 1.85%   |
| Intel 8 Series HD Audio Controller                                                                | 5         | 1.85%   |
| Intel 100 Series/C230 Series Chipset Family HD Audio Controller                                   | 5         | 1.85%   |
| Nvidia TU107 GeForce GTX 1650 High Definition Audio Controller                                    | 4         | 1.48%   |
| Nvidia GP107GL High Definition Audio Controller                                                   | 4         | 1.48%   |
| Intel Celeron/Pentium Silver Processor High Definition Audio                                      | 4         | 1.48%   |
| Intel Atom/Celeron/Pentium Processor x5-E8000/J3xxx/N3xxx Series High Definition Audio Controller | 4         | 1.48%   |
| Intel 200 Series PCH HD Audio                                                                     | 4         | 1.48%   |
| AMD Raven/Raven2/Fenghuang HDMI/DP Audio Controller                                               | 4         | 1.48%   |
| Nvidia MCP72XE/MCP72P/MCP78U/MCP78S High Definition Audio                                         | 3         | 1.11%   |
| Nvidia MCP61 High Definition Audio                                                                | 3         | 1.11%   |
| Nvidia GP106 High Definition Audio Controller                                                     | 3         | 1.11%   |
| Nvidia GK208 HDMI/DP Audio Controller                                                             | 3         | 1.11%   |
| Intel Wildcat Point-LP High Definition Audio Controller                                           | 3         | 1.11%   |
| Intel Tiger Lake-LP Smart Sound Technology Audio Controller                                       | 3         | 1.11%   |
| Intel Comet Lake PCH-LP cAVS                                                                      | 3         | 1.11%   |
| Intel Comet Lake PCH cAVS                                                                         | 3         | 1.11%   |
| Intel Celeron N3350/Pentium N4200/Atom E3900 Series Audio Cluster                                 | 3         | 1.11%   |
| Intel Broadwell-U Audio Controller                                                                | 3         | 1.11%   |
| Intel 82801JI (ICH10 Family) HD Audio Controller                                                  | 3         | 1.11%   |
| Intel 5 Series/3400 Series Chipset High Definition Audio                                          | 3         | 1.11%   |
| AMD Trinity HDMI Audio Controller                                                                 | 3         | 1.11%   |
| Nvidia GM204 High Definition Audio Controller                                                     | 2         | 0.74%   |
| Nvidia GK107 HDMI Audio Controller                                                                | 2         | 0.74%   |
| Logitech H600 [Wireless Headset]                                                                  | 2         | 0.74%   |
| Intel Ice Lake-LP Smart Sound Technology Audio Controller                                         | 2         | 0.74%   |
| Intel Atom Processor Z36xxx/Z37xxx Series High Definition Audio Controller                        | 2         | 0.74%   |
| Intel 9 Series Chipset Family HD Audio Controller                                                 | 2         | 0.74%   |
| Intel 82801I (ICH9 Family) HD Audio Controller                                                    | 2         | 0.74%   |
| Intel 82801H (ICH8 Family) HD Audio Controller                                                    | 2         | 0.74%   |
| AMD Starship/Matisse HD Audio Controller                                                          | 2         | 0.74%   |
| AMD RV710/730 HDMI Audio [Radeon HD 4000 series]                                                  | 2         | 0.74%   |
| AMD RS880 HDMI Audio [Radeon HD 4200 Series]                                                      | 2         | 0.74%   |
| AMD Ellesmere HDMI Audio [Radeon RX 470/480 / 570/580/590]                                        | 2         | 0.74%   |
| AMD Caicos HDMI Audio [Radeon HD 6450 / 7450/8450/8490 OEM / R5 230/235/235X OEM]                 | 2         | 0.74%   |
| AMD BeaverCreek HDMI Audio [Radeon HD 6500D and 6400G-6600G series]                               | 2         | 0.74%   |
| AMD Baffin HDMI/DP Audio [Radeon RX 550 640SP / RX 560/560X]                                      | 2         | 0.74%   |
| Texas Instruments PCM2902 Audio Codec                                                             | 1         | 0.37%   |
| Shenzhen Rapoo Technology Wireless Audio                                                          | 1         | 0.37%   |
| Sennheiser Communications SC60 for Lync                                                           | 1         | 0.37%   |
| Plantronics Audio 628 USB                                                                         | 1         | 0.37%   |
| Plantronics Audio 622 USB                                                                         | 1         | 0.37%   |
| Nvidia TU106 High Definition Audio Controller                                                     | 1         | 0.37%   |
| Nvidia MCP67 High Definition Audio                                                                | 1         | 0.37%   |
| Nvidia MCP55 High Definition Audio                                                                | 1         | 0.37%   |
| Nvidia GT216 HDMI Audio Controller                                                                | 1         | 0.37%   |

Memory
------

Memory Vendor
-------------

Memory module vendors

![Memory Vendor](./images/pie_chart/memory_vendor.svg)


| Vendor              | Computers | Percent |
|---------------------|-----------|---------|
| Unknown             | 33        | 23.74%  |
| Samsung Electronics | 27        | 19.42%  |
| SK hynix            | 19        | 13.67%  |
| Kingston            | 17        | 12.23%  |
| Micron Technology   | 8         | 5.76%   |
| Goodram             | 5         | 3.6%    |
| Transcend           | 3         | 2.16%   |
| Elpida              | 3         | 2.16%   |
| Unknown (ABCD)      | 2         | 1.44%   |
| Ramaxel Technology  | 2         | 1.44%   |
| Nanya Technology    | 2         | 1.44%   |
| G.Skill             | 2         | 1.44%   |
| Crucial             | 2         | 1.44%   |
| Apacer              | 2         | 1.44%   |
| A-DATA Technology   | 2         | 1.44%   |
| Unifosa             | 1         | 0.72%   |
| Team                | 1         | 0.72%   |
| Silicon Power       | 1         | 0.72%   |
| Hexon               | 1         | 0.72%   |
| Goldkey             | 1         | 0.72%   |
| Corsair             | 1         | 0.72%   |
| Axiom               | 1         | 0.72%   |
| AVEXIR              | 1         | 0.72%   |
| ASint Technology    | 1         | 0.72%   |
| Unknown             | 1         | 0.72%   |

Memory Model
------------

Memory module models

![Memory Model](./images/pie_chart/memory_model.svg)


| Model                                                            | Computers | Percent |
|------------------------------------------------------------------|-----------|---------|
| Unknown RAM Module 2048MB DIMM DDR2 333MT/s                      | 3         | 1.94%   |
| Unknown RAM Module 2048MB DIMM 1333MT/s                          | 3         | 1.94%   |
| SK hynix RAM HMT351S6CFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 3         | 1.94%   |
| Unknown RAM Module 4096MB DIMM 1600MT/s                          | 2         | 1.29%   |
| Unknown RAM Module 4096MB DIMM 1333MT/s                          | 2         | 1.29%   |
| Unknown RAM Module 2048MB SODIMM DRAM 667MT/s                    | 2         | 1.29%   |
| Unknown RAM Module 2048MB DIMM DDR3 1333MT/s                     | 2         | 1.29%   |
| Unknown RAM Module 2048MB DIMM 800MT/s                           | 2         | 1.29%   |
| Unknown RAM Module 1024MB SODIMM DRAM 667MT/s                    | 2         | 1.29%   |
| Unknown RAM Module 1024MB DIMM DDR2 333MT/s                      | 2         | 1.29%   |
| Unknown (ABCD) RAM 123456789012345678 4GB SODIMM LPDDR4 2400MT/s | 2         | 1.29%   |
| Samsung RAM M471B5273CH0-CK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.29%   |
| Samsung RAM M471B5173DB0-YK0 4GB SODIMM DDR3 1600MT/s            | 2         | 1.29%   |
| Samsung RAM M471B2873FHS-CF8 1024MB SODIMM DDR3 1067MT/s         | 2         | 1.29%   |
| Kingston RAM KHX1866C10D3/8G 8GB DIMM DDR3 1867MT/s              | 2         | 1.29%   |
| Unknown RAM Module 8192MB DIMM 1333MT/s                          | 1         | 0.65%   |
| Unknown RAM Module 512MB DIMM SDRAM                              | 1         | 0.65%   |
| Unknown RAM Module 4GB DIMM 667MT/s                              | 1         | 0.65%   |
| Unknown RAM Module 4GB DIMM 1333MT/s                             | 1         | 0.65%   |
| Unknown RAM Module 4096MB SODIMM DDR3 1600MT/s                   | 1         | 0.65%   |
| Unknown RAM Module 4096MB FB-DIMM DDR2 667MT/s                   | 1         | 0.65%   |
| Unknown RAM Module 4096MB DIMM DDR3 1600MT/s                     | 1         | 0.65%   |
| Unknown RAM Module 2GB SODIMM DDR3                               | 1         | 0.65%   |
| Unknown RAM Module 2GB DIMM DDR2 800MT/s                         | 1         | 0.65%   |
| Unknown RAM Module 2GB DIMM 667MT/s                              | 1         | 0.65%   |
| Unknown RAM Module 2048MB SODIMM DDR2 400MT/s                    | 1         | 0.65%   |
| Unknown RAM Module 2048MB DIMM SDRAM 800MT/s                     | 1         | 0.65%   |
| Unknown RAM Module 2048MB DIMM SDRAM                             | 1         | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR2 800MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR 667MT/s                       | 1         | 0.65%   |
| Unknown RAM Module 2048MB DIMM DDR 1333MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 2048MB DIMM                                   | 1         | 0.65%   |
| Unknown RAM Module 1024MB DIMM SDRAM                             | 1         | 0.65%   |
| Unknown RAM Module 1024MB DIMM DDR2 667MT/s                      | 1         | 0.65%   |
| Unknown RAM Module 1024MB DIMM DDR 667MT/s                       | 1         | 0.65%   |
| Unknown RAM CL17-17-17 D4-2400 16384MB DIMM DDR4 2400MT/s        | 1         | 0.65%   |
| Unknown RAM ..E-D3U1600M/4G 4096MB DIMM DDR3 800MT/s             | 1         | 0.65%   |
| Unifosa RAM GU672203EP0200 1GB SODIMM DDR3 1333MT/s              | 1         | 0.65%   |
| Transcend RAM Module 8192MB SODIMM DDR4 2133MT/s                 | 1         | 0.65%   |
| Transcend RAM JM1333KSN-4G 4096MB SODIMM DDR3 1334MT/s           | 1         | 0.65%   |
| Transcend RAM JM1333KLH-4G 4GB DIMM DDR3 1333MT/s                | 1         | 0.65%   |
| Team RAM Elite-1333 4GB DIMM DDR3 1333MT/s                       | 1         | 0.65%   |
| SK hynix RAM Module 32GB SODIMM DDR4 2667MT/s                    | 1         | 0.65%   |
| SK hynix RAM HYMP125U64CP8-S6 2GB DIMM DDR2 400MT/s              | 1         | 0.65%   |
| SK hynix RAM HYMP125S64CP8-S6 2GB SODIMM SDRAM 2048MT/s          | 1         | 0.65%   |
| SK hynix RAM HYMP112U64CP8-S6 1024MB DIMM DDR2 400MT/s           | 1         | 0.65%   |
| SK hynix RAM HYMP112U64CP8-S6 1024MB DIMM DDR 800MT/s            | 1         | 0.65%   |
| SK hynix RAM HMT451S6MFR8C-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT351S6EFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT351S6CFR8A-PB 4GB SODIMM DDR3 1600MT/s           | 1         | 0.65%   |
| SK hynix RAM HMT325S6CFR8C-PB 2048MB SODIMM DDR3 1600MT/s        | 1         | 0.65%   |
| SK hynix RAM HMT325S6CFR8C-H9 2048MB SODIMM DDR3 1333MT/s        | 1         | 0.65%   |
| SK hynix RAM HMT125S6TFR8C-H9 2048MB SODIMM DDR3 4199MT/s        | 1         | 0.65%   |
| SK hynix RAM HMAA4GS6AJR8N-XN 32GB SODIMM DDR4 3200MT/s          | 1         | 0.65%   |
| SK hynix RAM HMAA2GS6CJR8N-XN 16GB SODIMM DDR4 3200MT/s          | 1         | 0.65%   |
| SK hynix RAM HMA851S6JJR6N-VK 4GB SODIMM DDR4 2667MT/s           | 1         | 0.65%   |
| SK hynix RAM HMA851S6AFR6N-UH 4GB SODIMM DDR4 2667MT/s           | 1         | 0.65%   |
| SK hynix RAM HMA82GS6CJR8N-VK 16384MB SODIMM DDR4 2667MT/s       | 1         | 0.65%   |
| SK hynix RAM HMA81GS6JJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.65%   |
| SK hynix RAM HMA81GS6CJR8N-VK 8GB SODIMM DDR4 2667MT/s           | 1         | 0.65%   |

Memory Kind
-----------

Memory module kinds

![Memory Kind](./images/pie_chart/memory_kind.svg)


| Kind    | Computers | Percent |
|---------|-----------|---------|
| DDR3    | 45        | 35.43%  |
| DDR4    | 39        | 30.71%  |
| DDR2    | 12        | 9.45%   |
| Unknown | 11        | 8.66%   |
| SDRAM   | 9         | 7.09%   |
| LPDDR4  | 4         | 3.15%   |
| DDR     | 3         | 2.36%   |
| LPDDR3  | 2         | 1.57%   |
| DRAM    | 2         | 1.57%   |

Memory Form Factor
------------------

Physical design of the memory module

![Memory Form Factor](./images/pie_chart/memory_formfactor.svg)


| Name         | Computers | Percent |
|--------------|-----------|---------|
| SODIMM       | 62        | 50.82%  |
| DIMM         | 53        | 43.44%  |
| Row Of Chips | 6         | 4.92%   |
| FB-DIMM      | 1         | 0.82%   |

Memory Size
-----------

Memory module size

![Memory Size](./images/pie_chart/memory_size.svg)


| Size  | Computers | Percent |
|-------|-----------|---------|
| 4096  | 51        | 35.92%  |
| 2048  | 36        | 25.35%  |
| 8192  | 28        | 19.72%  |
| 1024  | 13        | 9.15%   |
| 16384 | 10        | 7.04%   |
| 32768 | 2         | 1.41%   |
| 512   | 2         | 1.41%   |

Memory Speed
------------

Memory module speed

![Memory Speed](./images/pie_chart/memory_speed.svg)


| Speed   | Computers | Percent |
|---------|-----------|---------|
| 1600    | 32        | 23.88%  |
| 2667    | 20        | 14.93%  |
| 1333    | 16        | 11.94%  |
| 2133    | 8         | 5.97%   |
| 800     | 7         | 5.22%   |
| 3200    | 6         | 4.48%   |
| 667     | 6         | 4.48%   |
| 2400    | 5         | 3.73%   |
| 1334    | 5         | 3.73%   |
| Unknown | 4         | 2.99%   |
| 400     | 3         | 2.24%   |
| 333     | 3         | 2.24%   |
| 4199    | 2         | 1.49%   |
| 3000    | 2         | 1.49%   |
| 2048    | 2         | 1.49%   |
| 1067    | 2         | 1.49%   |
| 4800    | 1         | 0.75%   |
| 3600    | 1         | 0.75%   |
| 3500    | 1         | 0.75%   |
| 3266    | 1         | 0.75%   |
| 2933    | 1         | 0.75%   |
| 2800    | 1         | 0.75%   |
| 2666    | 1         | 0.75%   |
| 1867    | 1         | 0.75%   |
| 1400    | 1         | 0.75%   |
| 975     | 1         | 0.75%   |
| 533     | 1         | 0.75%   |

Printers & scanners
-------------------

Printer Vendor
--------------

Printer device vendors

![Printer Vendor](./images/pie_chart/printer_vendor.svg)


| Vendor          | Computers | Percent |
|-----------------|-----------|---------|
| Hewlett-Packard | 2         | 40%     |
| Canon           | 2         | 40%     |
| Seiko Epson     | 1         | 20%     |

Printer Model
-------------

Printer device models

![Printer Model](./images/pie_chart/printer_model.svg)


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

![Scanner Vendor](./images/pie_chart/scanner_vendor.svg)


| Vendor | Computers | Percent |
|--------|-----------|---------|
| Canon  | 1         | 100%    |

Scanner Model
-------------

Scanner device models

![Scanner Model](./images/pie_chart/scanner_model.svg)


| Model                    | Computers | Percent |
|--------------------------|-----------|---------|
| Canon CanoScan LiDE 700F | 1         | 100%    |

Camera
------

Camera Vendor
-------------

Camera device vendors

![Camera Vendor](./images/pie_chart/camera_vendor.svg)


| Vendor                                 | Computers | Percent |
|----------------------------------------|-----------|---------|
| Chicony Electronics                    | 23        | 19.66%  |
| IMC Networks                           | 21        | 17.95%  |
| Realtek Semiconductor                  | 12        | 10.26%  |
| Microdia                               | 10        | 8.55%   |
| Acer                                   | 6         | 5.13%   |
| Quanta                                 | 4         | 3.42%   |
| Logitech                               | 4         | 3.42%   |
| Cheng Uei Precision Industry (Foxlink) | 4         | 3.42%   |
| Z-Star Microelectronics                | 3         | 2.56%   |
| Syntek                                 | 3         | 2.56%   |
| Sunplus Innovation Technology          | 3         | 2.56%   |
| Silicon Motion                         | 3         | 2.56%   |
| Lite-On Technology                     | 3         | 2.56%   |
| Suyin                                  | 2         | 1.71%   |
| Samsung Electronics                    | 2         | 1.71%   |
| Luxvisions Innotech Limited            | 2         | 1.71%   |
| KYE Systems (Mouse Systems)            | 2         | 1.71%   |
| Alcor Micro                            | 2         | 1.71%   |
| YGTek                                  | 1         | 0.85%   |
| Trust                                  | 1         | 0.85%   |
| Pixart Imaging                         | 1         | 0.85%   |
| Microsoft                              | 1         | 0.85%   |
| Importek                               | 1         | 0.85%   |
| Genesys Logic                          | 1         | 0.85%   |
| Cubeternet                             | 1         | 0.85%   |
| Aveo Technology                        | 1         | 0.85%   |

Camera Model
------------

Camera device models

![Camera Model](./images/pie_chart/camera_model.svg)


| Model                                                | Computers | Percent |
|------------------------------------------------------|-----------|---------|
| IMC Networks USB2.0 HD UVC WebCam                    | 5         | 4.27%   |
| Chicony Integrated Camera                            | 5         | 4.27%   |
| IMC Networks USB2.0 VGA UVC WebCam                   | 4         | 3.42%   |
| IMC Networks Integrated Camera                       | 4         | 3.42%   |
| Realtek Integrated_Webcam_HD                         | 3         | 2.56%   |
| Quanta HP HD Camera                                  | 3         | 2.56%   |
| Microdia Camera                                      | 3         | 2.56%   |
| Chicony HD WebCam                                    | 3         | 2.56%   |
| Z-Star Venus USB2.0 Camera                           | 2         | 1.71%   |
| Syntek Lenovo EasyCamera                             | 2         | 1.71%   |
| Silicon Motion WebCam SC-0311139N                    | 2         | 1.71%   |
| Realtek USB Camera                                   | 2         | 1.71%   |
| Microdia Laptop_Integrated_Webcam_HD                 | 2         | 1.71%   |
| Microdia Integrated_Webcam_HD                        | 2         | 1.71%   |
| Logitech Webcam C270                                 | 2         | 1.71%   |
| Lite-On HP HD Camera                                 | 2         | 1.71%   |
| IMC Networks VGA UVC WebCam                          | 2         | 1.71%   |
| Chicony USB2.0 VGA UVC WebCam                        | 2         | 1.71%   |
| Chicony Integrated Camera (1280x720@30)              | 2         | 1.71%   |
| Chicony EasyCamera                                   | 2         | 1.71%   |
| Z-Star WebCam SCB-0320N                              | 1         | 0.85%   |
| YGTek Webcam                                         | 1         | 0.85%   |
| Trust Full HD Webcam                                 | 1         | 0.85%   |
| Syntek Integrated Camera                             | 1         | 0.85%   |
| Suyin HP Truevision HD                               | 1         | 0.85%   |
| Suyin HD WebCam                                      | 1         | 0.85%   |
| Sunplus Laptop_Integrated_Webcam_FHD                 | 1         | 0.85%   |
| Sunplus Integrated_Webcam_HD                         | 1         | 0.85%   |
| Sunplus HD Webcam                                    | 1         | 0.85%   |
| Silicon Motion WebCam SC-13HDL11939N                 | 1         | 0.85%   |
| Samsung Galaxy A5 (MTP)                              | 1         | 0.85%   |
| Samsung Galaxy (PTP mode)                            | 1         | 0.85%   |
| Realtek USB2.0 VGA UVC WebCam                        | 1         | 0.85%   |
| Realtek Integrated Webcam_HD                         | 1         | 0.85%   |
| Realtek Integrated Webcam HD                         | 1         | 0.85%   |
| Realtek HP Truevision HD                             | 1         | 0.85%   |
| Realtek HP "Truevision HD" laptop camera             | 1         | 0.85%   |
| Realtek HD WebCam                                    | 1         | 0.85%   |
| Realtek EasyCamera                                   | 1         | 0.85%   |
| Quanta HP TrueVision HD Camera                       | 1         | 0.85%   |
| Pixart Imaging GE 1.3 MP MiniCam Pro                 | 1         | 0.85%   |
| Microsoft LifeCam VX-700                             | 1         | 0.85%   |
| Microdia Webcam                                      | 1         | 0.85%   |
| Microdia Integrated Webcam                           | 1         | 0.85%   |
| Microdia Amcrest AWC2198 USB Webcam                  | 1         | 0.85%   |
| Luxvisions Innotech Limited HP Wide Vision HD Camera | 1         | 0.85%   |
| Luxvisions Innotech Limited HP HD Camera             | 1         | 0.85%   |
| Logitech Webcam C170                                 | 1         | 0.85%   |
| Logitech Webcam C110                                 | 1         | 0.85%   |
| Lite-On HP HD Webcam                                 | 1         | 0.85%   |
| KYE Systems (Mouse Systems) FaceCam 1000X            | 1         | 0.85%   |
| KYE Systems (Mouse Systems) eFace 2025               | 1         | 0.85%   |
| Importek TOSHIBA Web Camera - HD                     | 1         | 0.85%   |
| IMC Networks XiaoMi Webcam                           | 1         | 0.85%   |
| IMC Networks UVC VGA Webcam                          | 1         | 0.85%   |
| IMC Networks USB2.0 HD IR UVC WebCam                 | 1         | 0.85%   |
| IMC Networks USB Camera                              | 1         | 0.85%   |
| IMC Networks ov9734_azurewave_camera                 | 1         | 0.85%   |
| IMC Networks Integrated Webcam                       | 1         | 0.85%   |
| Genesys Logic U2 EE Cam                              | 1         | 0.85%   |

Security
--------

Fingerprint Vendor
------------------

Fingerprint sensor vendors

![Fingerprint Vendor](./images/pie_chart/fingerprint_vendor.svg)


| Vendor                     | Computers | Percent |
|----------------------------|-----------|---------|
| Validity Sensors           | 9         | 36%     |
| Synaptics                  | 8         | 32%     |
| Shenzhen Goodix Technology | 3         | 12%     |
| Elan Microelectronics      | 2         | 8%      |
| Upek                       | 1         | 4%      |
| LighTuning Technology      | 1         | 4%      |
| AuthenTec                  | 1         | 4%      |

Fingerprint Model
-----------------

Fingerprint sensor models

![Fingerprint Model](./images/pie_chart/fingerprint_model.svg)


| Model                                                      | Computers | Percent |
|------------------------------------------------------------|-----------|---------|
| Synaptics  FS7604 Touch Fingerprint Sensor with PurePrint  | 4         | 16%     |
| Shenzhen Goodix  FingerPrint Device                        | 3         | 12%     |
| Validity Sensors VFS495 Fingerprint Reader                 | 2         | 8%      |
| Validity Sensors VFS 5011 fingerprint sensor               | 2         | 8%      |
| Validity Sensors Fingerprint scanner                       | 2         | 8%      |
| Synaptics  VFS7552 Touch Fingerprint Sensor with PurePrint | 2         | 8%      |
| Validity Sensors VFS Fingerprint sensor                    | 1         | 4%      |
| Validity Sensors Synaptics WBDI                            | 1         | 4%      |
| Validity Sensors Swipe Fingerprint Sensor                  | 1         | 4%      |
| Upek Biometric Touchchip/Touchstrip Fingerprint Sensor     | 1         | 4%      |
| Synaptics  WBDI                                            | 1         | 4%      |
| LighTuning EgisTec Touch Fingerprint Sensor                | 1         | 4%      |
| Elan ELAN:Fingerprint                                      | 1         | 4%      |
| Elan ELAN:ARM-M4                                           | 1         | 4%      |
| AuthenTec AES2501 Fingerprint Sensor                       | 1         | 4%      |
| Unknown                                                    | 1         | 4%      |

Chipcard Vendor
---------------

Chipcard module vendors

![Chipcard Vendor](./images/pie_chart/chipcard_vendor.svg)


| Vendor                | Computers | Percent |
|-----------------------|-----------|---------|
| Realtek Semiconductor | 1         | 50%     |
| O2 Micro              | 1         | 50%     |

Chipcard Model
--------------

Chipcard module models

![Chipcard Model](./images/pie_chart/chipcard_model.svg)


| Model                                             | Computers | Percent |
|---------------------------------------------------|-----------|---------|
| Realtek Semiconductor Smart Card Reader Interface | 1         | 50%     |
| O2 Micro OZ776 CCID Smartcard Reader              | 1         | 50%     |

Unsupported
-----------

Unsupported Devices
-------------------

Total unsupported devices on board

![Unsupported Devices](./images/pie_chart/device_unsupported.svg)


| Total | Computers | Percent |
|-------|-----------|---------|
| 0     | 128       | 71.11%  |
| 1     | 44        | 24.44%  |
| 2     | 7         | 3.89%   |
| 3     | 1         | 0.56%   |

Unsupported Device Types
------------------------

Types of unsupported devices

![Unsupported Device Types](./images/pie_chart/device_unsupported_type.svg)


| Type                  | Computers | Percent |
|-----------------------|-----------|---------|
| Fingerprint reader    | 25        | 43.86%  |
| Graphics card         | 20        | 35.09%  |
| Net/wireless          | 4         | 7.02%   |
| Multimedia controller | 2         | 3.51%   |
| Chipcard              | 2         | 3.51%   |
| Camera                | 2         | 3.51%   |
| Storage               | 1         | 1.75%   |
| Sound                 | 1         | 1.75%   |

